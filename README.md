<h1 align="center">Yihan Li</h1>
<p align="center">
  <a href="mailto:Liyihan11unique@outlook.com">Liyihan11unique@outlook.com</a> | 
  <a href="https://www.linkedin.com/in/yihan-li-b882593b3/">LinkedIn</a> | 
  <a href="https://stardazz-com.vercel.app/">Personal Website</a>
</p>

---

##  Tech Stack

**Languages**
- Kotlin / Java / Python / C / SQL

**AI & ML**
- sciket-learn / ONNX / sherpa-ncnn / ASR (Zipformer)
- Model Optimization / Quantization

**Development**
- Android / Gradle / Jetpack Compose / Kotlin Multiplatform
- Backend basics / API integration

---

## Featured Projects

###  smeeting

https://github.com/YihanLi-erisaer/smeeting

- On-device speech recognition and local AI summary system
- Kotlin + sherpa-ncnn + llama-cpp Runtime deployment

**performance on a android device Helio G99 (CPU) processor using armv8 libs only running ASR model**
| Metric       | Value   |
| ------------ | ------- |
| Memory Usage | ~250 MB  |
| Latency      | ~120 ms  |
| Chinese Accuracy (in chaos environment)     | ~89%  |
| Chinese Accuracy (in quiet environment)     | ~95%  |
| English Accuracy (in chaos environment)     | ~92%  |
| English Accuracy (in quiet environment)     | ~97%  |

**performance on a android device Helio G99 (CPU) processor running Qwen3.0_0.6b model**
| Metric       | Value   |
| ------------ | ------- |
| Memory Usage | ~3 GB  |
| Throughput | ~2 token/s |

- **Future change back to raw ncnn inference framework, and deploy a small LLM that can conclude the recognition text.**

---

###  AI Client

 https://github.com/YihanLi-erisaer/aiclient

- AI API integration client
- Modular design for LLM usage
- KMP multiplatform project (Android + web)
- Focus on usability + extensibility
- local deloyment of asr model using ONNX Runtime framework

---

### Web Crawler and Data Analysis
 https://github.com/YihanLi-erisaer/Elements-of-data-processing-webpage-crawler

- Data collection pipeline
- Parsing + structured storage
- Useful for LLM / RAG preprocessing


