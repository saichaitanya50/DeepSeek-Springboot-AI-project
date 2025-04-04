Developed an AI chat system using Spring Boot and Spring AI, integrating DeepSeek language models locally via Ollama.

Configured Ollama to interface with the DeepSeek model using custom API keys and endpoint configurations, enabling efficient local model hosting.

Utilized Spring Web to build RESTful APIs and integrated Spring AI’s ChatModel to facilitate seamless interaction with the locally served LLM.

Achieved low-latency responses by optimizing local LLM inference with Ollama instead of relying on cloud-based LLM APIs.

Enabled pluggable model architecture, making it easy to swap in different LLMs (e.g., DeepSeek, LLaMA, Mistral) with minimal config changes.

Emphasized secure key and endpoint management for model access and integrated logging & tracing to monitor LLM interactions.

Designed system with scalability and local inference performance in mind, suitable for privacy-sensitive or offline applications.
