# fal.ai/happyhorse-1.0 页面内容

## 标题
HappyHorse-1.0 | AI Video Generator | Official API Partner

## Hero
- **标题**：HappyHorse-1.0 — The Top Ranked AI Video Model
- **描述**：#1 on the Artificial Analysis Video Arena in both Text-to-Video and Image-to-Video, ranked by blind human preference votes. Joint audio-video generation in a single pass. Available now as of April 27, 2026 on fal as an official API partner.

## API 端点
1. **alibaba/happy-horse/text-to-video** — 从文本提示词生成 1080p 视频，同步原生音频。宽高比：16:9, 9:16, 1:1, 4:3, 3:4。时长：3-15s
2. **alibaba/happy-horse/image-to-video** — 阿里巴巴 #1 排名的 Happy Horse 1.0，从文本或图片生成 1080p 视频，同步音频和多语言唇形同步
3. **alibaba/happy-horse/video-edit** — 通过自然语言指令进行高级视频编辑，支持多达5张参考图片的局部或全局编辑
4. **alibaba/happy-horse/reference-to-video** — 从文本提示词和参考图片生成 1080p 视频，同步音频。标签：stylized, transform, lipsync

## 排行榜数据 (Artificial Analysis Video Arena)
- **Text-to-Video (无音频)**：#1，Elo 1333
- **Image-to-Video (无音频)**：#1，Elo 1392
- **Text-to-Video (含音频)**：#2，Elo 1205
- **Image-to-Video (含音频)**：#2，Elo 1161

## 为什么 HappyHorse-1.0 是 #1

### 1. 盲测偏好排名第一
在 Artificial Analysis Video Arena 中，Text-to-Video 和 Image-to-Video 都排名第一。排名基于真实用户的盲测偏好投票。

### 2. 联合音频-视频生成
使用统一的 40 层自注意力 Transformer（无交叉注意力模块），在单次前向传播中同时生成视频和音频。

### 3. 推理速度
- 1080p 输出：约 38 秒（单张 NVIDIA H100 GPU）
- 256p 5秒片段：约 2 秒

## 背景故事 — 团队
- **2026年4月9日**，阿里巴巴集团确认创造了 "Happy Horse" 视频 AI 模型
- 由 **Alibaba Token Hub (ATH)** 创新业务部门开发
- **张迪 (Zhang Di)** 领导：
  - 15+ 年 AI 工程经验
  - 2010-2022 任阿里巴巴集团总监
  - 加入快手担任副总裁，是 **Kling AI** 的技术架构师
  - 2025年底回归阿里巴巴，领导 ATH 下的淘天未来生活实验室
  - 数月内交付了 Happy Horse 1.0

### 开源状态
fal.ai 确认 HappyHorse-1.0 将**不开源**，不可许可或开源。

## 集成步骤
1. 安装客户端（支持 npm/yarn/pnpm/bun/pip）
2. 注册 fal 账户
3. 获取 API Key
4. 提交请求

## 其他平台模型
fal.ai 同时托管：GPT Image 2、Seedance 2.0、Flux 2、Kling 3.0、Veo 3.1、Nano Banana Pro
