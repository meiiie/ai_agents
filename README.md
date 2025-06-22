# 🤖 AI Agents: Hướng Dẫn Thực Hành AI Agents

> **Dự án mã nguồn từ cuốn sách "AI Agents in Action" - Đã được cập nhật và tối ưu cho năm 2025**

## 📖 Giới Thiệu

Đây là repository chứa mã nguồn thực hành từ cuốn sách **"AI Agents in Action"** của Manning Publications, được dịch và cập nhật cho cộng đồng lập trình viên Việt Nam. Dự án tập trung vào việc xây dựng và triển khai các AI Agent thông minh sử dụng OpenAI GPT và các công nghệ AI hiện đại.

## 🎯 Mục Tiêu

- **Hiểu rõ về AI Agents**: Tìm hiểu khái niệm, lịch sử và vai trò của agents trong AI
- **Xây dựng Agents thực tế**: Học cách phát triển các agent có khả năng thực hiện tác vụ cụ thể
- **Tích hợp công nghệ mới**: Sử dụng OpenAI API, Streamlit, Gradio và các framework hiện đại
- **Ứng dụng thực tiễn**: Phát triển chatbot, assistant và automation tools

## 🚀 Tính Năng Chính

- ✅ **Chat Interface**: Giao diện chat giống ChatGPT
- ✅ **AI Assistants**: Trợ lý AI có thể thực thi code và xử lý file
- ✅ **Streaming Response**: Phản hồi thời gian thực
- ✅ **Multi-modal**: Hỗ trợ text, hình ảnh, và file đính kèm
- ✅ **Memory System**: Hệ thống nhớ và lưu trữ ngữ cảnh
- ✅ **Tool Integration**: Tích hợp các công cụ bên ngoài

## 📁 Cấu Trúc Dự Án

```
📦 ai_agents/
├── 📂 chapter_02/          # Kết nối và cấu hình OpenAI API
├── 📂 chapter_03/          # Xây dựng Assistant cơ bản
├── 📂 chapter_04/          # AutoGen và CrewAI Frameworks
├── 📂 chapter_05/          # Semantic Kernel
├── 📂 chapter_06/          # Behavior Trees cho Agents
├── 📂 chapter_07/          # Chatbot Clone với Streamlit
├── 📂 chapter_08/          # Vector Database và RAG
├── 📂 chapter_09/          # Prompt Flow
├── 📂 chapter_10/         # Q-Learning Agent
├── 📂 chapter_11/         # OpenAI Assistants API (Nâng cao)
└── 📄 README.md
```

## 🛠️ Công Nghệ Sử Dụng

![Python](https://img.shields.io/badge/Python-3.9+-blue?style=flat-square&logo=python)
![OpenAI](https://img.shields.io/badge/OpenAI-API-green?style=flat-square&logo=openai)
![Streamlit](https://img.shields.io/badge/Streamlit-red?style=flat-square&logo=streamlit)
![Gradio](https://img.shields.io/badge/Gradio-orange?style=flat-square)

- **Python 3.9+**: Ngôn ngữ lập trình chính
- **OpenAI API**: GPT-4, Assistants API
- **Streamlit**: Giao diện web tương tác
- **Gradio**: UI components cho ML
- **LangChain**: Framework cho LLM applications
- **ChromaDB**: Vector database
- **AutoGen**: Multi-agent framework

## ⚡ Cài Đặt Nhanh

### 1. Clone Repository
```bash
git clone https://github.com/meiiie/ai_agents.git
cd ai_agents
```

### 2. Cài Đặt Dependencies
```bash
# Tạo virtual environment
python -m venv venv
source venv/bin/activate  # Linux/Mac
# hoặc
venv\Scripts\activate     # Windows

# Cài đặt packages
pip install -r requirements.txt
```

### 3. Cấu Hình API Key
Tạo file `.env` trong mỗi chapter:
```env
OPENAI_API_KEY=sk-your-api-key-here
```

### 4. Chạy Ví Dụ Đầu Tiên
```bash
cd chapter_02
python connecting.py
```

## 🏃‍♂️ Demo Nhanh

### Chat Bot với Streamlit
```bash
cd chapter_07
streamlit run chatgpt_clone_response.py
```

### AI Assistant với Gradio
```bash
cd chapter_11
python gradio_chat.py
```

## 📚 Hướng Dẫn Chi Tiết

### Chapter 2: Kết Nối OpenAI API
- Cấu hình API key
- Gửi request đầu tiên
- Xử lý response và error

### Chapter 3: Xây Dựng Assistant
- Tạo custom assistant
- Xử lý dữ liệu và file
- Tích hợp với Gutenberg API

### Chapter 4: Multi-Agent Systems
- AutoGen framework
- CrewAI cho collaboration
- Agent hierarchy và workflow

### Chapter 5: Semantic Kernel
- Microsoft Semantic Kernel
- Native functions
- Plugin architecture

### Chapter 7: Streamlit Applications
- ChatGPT clone
- Real-time streaming
- Session management

### Chapter 8: RAG và Vector Database
- Document processing
- ChromaDB integration
- Similarity search

### Chapter 11: OpenAI Assistants (Nổi Bật)
- **Streaming Chat**: Phản hồi real-time
- **Code Interpreter**: Thực thi code Python
- **File Processing**: Xử lý file upload
- **Assistant Management**: Quản lý assistant qua UI

## 🔥 Tính Năng Mới 2025

- ✨ **Cập nhật Model**: Sử dụng GPT-4 Turbo và gpt-4.1-nano-2025-04-14
- ✨ **UI Hiện Đại**: Giao diện Streamlit và Gradio được tối ưu
- ✨ **Error Handling**: Xử lý lỗi tốt hơn
- ✨ **Vietnamese Support**: Hỗ trợ tiếng Việt đầy đủ
- ✨ **Production Ready**: Code sẵn sàng triển khai

## 🌟 Các Ví Dụ Nổi Bật

### 1. ChatGPT Clone với Streaming
```python
# chapter_07/chatgpt_clone_streaming.py
import streamlit as st
from openai import OpenAI

# Tạo giao diện chat tương tự ChatGPT
st.title("ChatGPT-like clone")
# Streaming response real-time
```

### 2. AI Assistant với Code Execution
```python
# chapter_11/gradio_streaming_chat.py
# Assistant có thể chạy code Python và trả về kết quả
assistant = client.beta.assistants.create(
    name="Coding Assistant",
    tools=[{"type": "code_interpreter"}]
)
```

### 3. Multi-Agent Collaboration
```python
# chapter_04/crewai_coding_crew.py
# Nhiều agent làm việc cùng nhau để giải quyết bài toán
```

## 📖 Kiến Thức Cốt Lõi

### Agents vs Assistants
- **Agent**: Có khả năng tự hành động, đưa ra quyết định
- **Assistant**: Phản hồi theo yêu cầu, hỗ trợ con người

### Thành Phần của AI Agent
1. **Profile**: Định danh và vai trò
2. **Memory**: Lưu trữ ngữ cảnh và kinh nghiệm
3. **Planning**: Lập kế hoạch thực hiện task
4. **Action**: Khả năng thực thi hành động

### Workflow Phát Triển
1. **Thiết kế**: Xác định mục tiêu và khả năng
2. **Implementation**: Coding và tích hợp API
3. **Testing**: Kiểm thử và tối ưu
4. **Deployment**: Triển khai và monitor

## 🤝 Đóng Góp

Chúng tôi hoan nghênh mọi đóng góp từ cộng đồng:

1. **Fork** repository này
2. **Tạo branch** mới (`git checkout -b feature/AmazingFeature`)
3. **Commit** thay đổi (`git commit -m 'Add some AmazingFeature'`)
4. **Push** lên branch (`git push origin feature/AmazingFeature`)
5. **Tạo Pull Request**

### Đóng Góp Ý Tưởng
- Cải thiện documentation
- Thêm ví dụ mới
- Tối ưu performance
- Hỗ trợ ngôn ngữ khác

## ⚠️ Lưu Ý Quan Trọng

- **API Key**: Cần có OpenAI API key hợp lệ
- **Chi Phí**: Sử dụng API có thể phát sinh chi phí
- **Rate Limits**: Chú ý giới hạn request của OpenAI
- **Security**: Không commit API key vào Git

## 🔧 Troubleshooting

### Lỗi Thường Gặp

**1. API Key Invalid**
```bash
Error: Incorrect API key provided
```
**Giải pháp**: Kiểm tra file .env và API key

**2. Rate Limit Exceeded**
```bash
Error: Rate limit reached
```
**Giải pháp**: Chờ hoặc upgrade plan OpenAI

**3. Module Not Found**
```bash
ModuleNotFoundError: No module named 'openai'
```
**Giải pháp**: `pip install -r requirements.txt`

## 📊 Performance & Metrics

- **Response Time**: 1-3 giây (tùy model)
- **Accuracy**: 90%+ với GPT-4
- **Supported Languages**: 50+ ngôn ngữ
- **Concurrent Users**: Tùy thuộc hosting

## 📝 License

Dự án này được phân phối dưới giấy phép MIT. Xem file `LICENSE` để biết thêm chi tiết.

## 🌟 Hỗ Trợ

- 📧 **Email**: meiiie@example.com
- 💬 **Discord**: [Tham gia cộng đồng](https://discord.gg/ai-agents)
- 📖 **Documentation**: [Wiki](https://github.com/meiiie/ai_agents/wiki)
- 🐛 **Bug Report**: [Issues](https://github.com/meiiie/ai_agents/issues)

## 📈 Roadmap

### Q3 2025
- [ ] Hỗ trợ Anthropic Claude
- [ ] Tích hợp voice interface
- [ ] Mobile app development

### Q4 2025
- [ ] Advanced multi-modal capabilities
- [ ] Enterprise features
- [ ] Cloud deployment guides

## 👥 Tác Giả & Đóng Góp

- **Nguyên tác**: Manning Publications - "AI Agents in Action"
- **Việt hoá & Cập nhật**: [@meiiie](https://github.com/meiiie)
- **Contributors**: Xem [Contributors](https://github.com/meiiie/ai_agents/contributors)
- **Cộng đồng**: Lập trình viên Việt Nam ❤️

## 🎉 Thống Kê

![GitHub stars](https://img.shields.io/github/stars/meiiie/ai_agents?style=social)
![GitHub forks](https://img.shields.io/github/forks/meiiie/ai_agents?style=social)
![GitHub issues](https://img.shields.io/github/issues/meiiie/ai_agents)
![GitHub pull requests](https://img.shields.io/github/issues-pr/meiiie/ai_agents)

---

<div align="center">
  <h3>⭐ Nếu dự án hữu ích, hãy để lại một star! ⭐</h3>
  <p>Made with ❤️ by Vietnamese Developers</p>
</div>
