# AI-Music-Feature-Extraction
Python,Librosa,Audio feature extraction
# AI Music Feature Extraction (AI音乐客观特征提取)

## 项目简介
本项目使用 Python 和 Librosa 库，对 21 条可灵(Kling)生成的 AI 音乐进行客观音频特征提取，将主观听感量化。

## 提取的特征
- **频谱质心 (Spectral Centroid)**：衡量音频的明亮度，用于客观验证AI音乐的“刺耳/失真”问题。
- **MFCC (梅尔频率倒谱系数)**：提取音色和质感特征。

## 文件说明
- `AI_Music_Feature_Extraction.ipynb`：完整的 Python 处理脚本。
- `kling_evaluation_data.csv`：提取出的 21 条音频结构化数据。

## 核心结论
通过主客观交叉验证，发现部分 AI 音乐（如 7-kling.mp3）的频谱质心高达 **3675.68 Hz**，客观数据印证了主观听感中“高频刺耳、音色失真”的系统性缺陷。
