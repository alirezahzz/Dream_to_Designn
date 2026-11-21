# Designing ultra low carbon reinforced concrete beams via imagination reinforcement learning

Official code repository for the manuscript **"Designing ultra low carbon reinforced concrete beams via imagination reinforcement learning"**.

## Accessing the Source Code (During Peer Review)

During the peer-review period, the source code archive (`Dream_to_Design_Code.zip`) is encrypted with **7-Zip**.  
Please use the **access password provided in the manuscript's Code Availability Statement**.

### How to Extract
- **Windows:** Right-click the file → **7-Zip** → **Extract Here** (recommended; built-in Windows 10 Explorer does not support AES-256 ZIP archives).
- **macOS:** Open with **The Unarchiver**, **Keka**, or run `7z x Dream_to_Design_Code.zip` via Homebrew (`brew install p7zip` or `sevenzip`).

(The full source code will be uploaded in unencrypted form upon publication.)

Repository Contents

Inside the archive:

  - Model classes: Recurrent State-Space Model (RSSM), world model (encoder,
    decoder, reward head), actor, and critic
  - RC beam RL environment (ACI 318-19 structural checks, concrete mix
    constraints, and surrogate integration)
  - Training, evaluation, and plotting scripts

Related Links & Interactive Tools

  - Dream to Design Web Application: https://MaterialAI.ir/Dream_to_Design
  - Baseline PPO Repository (Hosseinzadeh & Dehestani, 2025, Scientific
    Reports):
    https://github.com/alirezahzz/Low-Carbon-RC-Beam-Deep-Reinforcement-Learning

