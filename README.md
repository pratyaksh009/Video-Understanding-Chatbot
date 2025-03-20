# AI-Powered RAG (Retrieval Augmented Generation) Chatbot

An advanced AI-powered chatbot capable of answering questions about videos in various formats. This system utilizes cutting-edge models and tools to process and understand videos, then generate relevant answers to any queries about the video.

---

## 🚀 **Features**

- **Video Understanding**: Supports various video formats for question-answering.
- **AI-Powered Retrieval**: Uses RAG (Retrieval Augmented Generation) techniques to provide accurate answers.
- **Supports Multimedia**: Utilizes models for both vision and language processing.
- **Scalable & Flexible**: Can handle large video data and various types of user queries.

---

## 🔧 **Tools Used**

The chatbot leverages a suite of powerful tools to achieve its goals:

- **LangChain**: A framework for building language model-powered applications.
- **HuggingFace**: Models for natural language processing and visual understanding.
- **OpenCV**: Library for video processing and analysis.
- **Transformers - CLIP & BLIP Models**: For video and image understanding via text and vision.
- **MoviePy**: A library to handle video editing and processing.
- **ChromaDB**: A database to store and retrieve video-related data for efficient RAG.

---

## 🛠️ **How It Works**

The system is designed to extract information from videos using the following steps:

1. **Video Input**: The chatbot accepts videos in a wide range of formats.
2. **Video Processing**: OpenCV and MoviePy handle video frame extraction and preprocessing.
3. **Model Inference**: CLIP and BLIP models are used to extract meaning from both images and text within the video.
4. **Database Storage**: ChromaDB stores indexed information for fast retrieval.
5. **Query Handling**: LangChain orchestrates the video retrieval process and provides intelligent answers.

---

## 🖥️ **Getting Started**

To get started with the project, follow these steps:

### 1. **Clone the repository**

```bash
git clone https://github.com/pratyaksh009/Video-Understanding-Chatbot.git

   
   
