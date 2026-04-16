<h1 align="center">Yihan Li</h1>
<h3 align="center">Liyihan11unique@outlook.com | https://www.linkedin.com/in/yihan-li-b882593b3/</h3>

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
**performance on a android device Helio G99 (CPU) processor using armv8 libs only running ASR model**
| Metric       | Value   |
| ------------ | ------- |
| Memory Usage | ~250 MB  |
| Latency      | ~120 ms  |
| Chinese Accuracy (in chaos environment)     | ~89%  |
| Chinese Accuracy (in quiet environment)     | ~95%  |
| English Accuracy (in chaos environment)     | ~92%  |
| English Accuracy (in quiet environment)     | ~97%  |

**performance on a android device Helio G99 (CPU) processor running LLM model**
| Metric       | Value   |
| ------------ | ------- |
| Memory Usage | ~1.4 GB  |
| Quantization | 4-bit Integer |
| Throughput | ~1.0 token/s |
| Latency (Average Summary)      | ~60 seconds  |
- Kotlin + sherpa-ncnn + llama-cpp Runtime deployment
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


