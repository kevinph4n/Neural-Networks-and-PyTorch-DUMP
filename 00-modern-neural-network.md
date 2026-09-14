# Transformers
- Introduced in 2017 by Google in the famous newspaper "Attention Is All You Need"

### Significance
- Opens a new era for LLMs

### Mechanism
- Can consider entire sequences simultaneously
- Can understand long-range dependencies

### Scalability
- Scale on modern GPU/TPU
- Parallel computation (parallelization): Process all the data simultaneously, save a lot of time for training when training on a huge amount of data

### Applications
- **Natural Language Processing (NLP)**: translating, summarizing, analyzing syntax
- **Computer Vision (CV)**: divide a picture into patches and process them like "words"
- **Audio Processing**: Speech recognition, writing out speeches
- **Multimodal**: Models that can understand and generate texts, pictures, videos (Gemini Omni, Sora, DALL-E)
- **Basic Science**: AlphaFold, creating new chemical pill, new materials,...

---

# Deep feed forward neural networks
- Build on the idea of basic neural networks by using multiple hidden layers instead of just one
<img width="521" height="256" alt="image" src="https://github.com/user-attachments/assets/b8d0e092-2b06-40bc-b507-8622f48d831a" />
- Uses multiple hidden layers, input -> output
- Learns abstract features progressively; Detect patterns to objects
- Captures complex nonlinear relationships
- It also brings challenges: Vanishing gradients, Training time increased
- Modern improvements: uses advanced optimizers; applies normalization techniques
- Arch role: provides foundational architecture; Support CNNs* and transformers

---

# Convolutional Neural Network (CNN)
- Processes grid-like data (images,...)
- Exploits spatial structure
- Applies shared local filters; Detect edges and textures (for Computer Vision)
- Reduce spatial dimensions; Preserve important features
- Applications: Image classification; Object detection; Medical image analysis,...
<img width="984" height="623" alt="image" src="https://github.com/user-attachments/assets/4a21b83f-1dc6-45a4-9397-f2684734c285" />


---

# Recurrent Neural Network (RNN)
- Maintain evolving hidden state
- Model sequential data patterns
- Capture temporal dependencies
- Long short-term memory (LSTM): Retain long-term context; Control information with gates
- Gated recurrent unit (GRU): Simplify gating mechanisms; Maintain similar performance
- Applications: NLP; Speech recognition; Time series forecasting
