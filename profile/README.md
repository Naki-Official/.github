
# Naki - Community Owned & Collectively Built AI Agent Protocol

![Naki Architecture](./naki-architecture.png)

## Project Overview

Naki is building a **Community Owned & Collectively Built AI Agent protocol for Entertainment**, where Virtual Humans and Characters evolve over time based on Community Input. These AI-driven Virtual Characters have their own unique personalities, generate content, and interact directly with fans. The platform allows contributors to add value through data, content, and interactions, refining and improving the AI models over time.

## System Architecture

The architecture of Naki's system includes several key components and layers:

1. **Contributors**: Individuals who provide data, content, and interactions that contribute to the development and refinement of AI models. Contributors are rewarded through the Revenue Factory Smart Contract.

2. **Revenue Factory Smart Contract**: Manages the distribution of rewards to contributors based on the value and impact of their contributions.

3. **Contribution NFT Smart Contract**: Mints NFTs that represent the contributions made by users, which can be used within the ecosystem.

4. **DApp/SocialApp**: The interface for users to interact with Virtual Characters, view content, and participate in community-driven governance.

5. **AI Studio (Off-Chain)**: Processes contributions, creates content, and trains AI models based on the input received from contributors. 

6. **Governance Platform (Naki DAO)**: The decentralized platform where community members create proposals, vote on decisions, and influence the training and development of AI models.

7. **IPFS**: A decentralized file system that stores AI models, content, and data contributions securely. Data and models are uploaded and retrieved from IPFS as needed.

8. **Multimodal AI (Off-Chain)**: A sophisticated AI system that incorporates various forms of data (e.g., images, voice, text) to enhance the capabilities of Virtual Characters. This system also includes vector databases and tools for voice cloning and ID preservation.

9. **Messaging**: Enables direct communication between users and Virtual Characters, facilitating ongoing interaction and content generation.

## Key Components & Techniques

| Component | Technique | Description | Link |
| --------- | --------- | ----------- | ---- |
| **AI Model Training** | LLM, Stable Diffusion | Trains AI models to generate content, process voice data, and enhance Virtual Characters based on community input. | [AI Model Training](https://github.com/Naki-Official/llm-fine-tuning) |
| **Content Creation** | Image, Music, Video | AI-generated content is created based on community standards and input, stored, and retrieved from IPFS. | [Content Creation](https://github.com/Naki-Official/content-creation) |
| **Governance** | Naki DAO | Community members create proposals, vote, and contribute to the training and evolution of Virtual Characters. | [Governance](https://github.com/Naki-Official/governance) |
| **Voice and Text Processing** | Voice Cloning, Prompt Templates | AI processes voice data and text interactions to enhance the realism and personalization of Virtual Characters. | [Voice and Text Processing](https://github.com/Naki-Official/voice-cloning) |
| **UI** | React, Next.js | The frontend interfaces and smart contracts managing user interactions, NFTs, and social applications. | [UI](https://github.com/Naki-Official/naki-web-app-ui) |
| **Backend** | FastAPI, MongoDB | The off-chain AI processing, model training, and data management, including integration with IPFS and governance platforms. | [Backend](https://github.com/Naki-Official/naki-web-app-backend) |

## Workflow

1. **Content Submission**: Contributors submit data (e.g., image, music, voice) through the UI.
2. **Data Processing**: The AI Studio processes the data, enhancing the Virtual Characters' personalities and content generation capabilities.
3. **Proposal Creation**: Community members create proposals through the Governance Platform (Naki DAO) to train or refine AI models.
4. **Model Training**: Proposals that are accepted lead to the training of AI models using community-contributed data.
5. **Content Creation**: The trained models generate new content, which is uploaded to IPFS and made available to users.
6. **User Interaction**: Users interact with Virtual Characters via the DApp/SocialApp, and their interactions are used to further refine the models.

## Contributing

Naki is built collectively by the community. Contributions can be made by providing data, participating in governance, or developing new features. All contributions are rewarded through the Revenue Factory Smart Contract.
