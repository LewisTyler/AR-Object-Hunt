# \# AR Object Hunt – Unity AR Foundation Prototype

# 

# This is a Unity-based mobile AR prototype designed to demonstrate spatial gameplay, collectible object interactions, and a backend-ready architecture. It serves as a technical demo for an AR developer role and lays the groundwork for integration with AWS (API Gateway, Lambda, and DynamoDB).

# 

# ---

# 

# \## 🎯 Project Goals

# 

# \- ✅ Demonstrate real-world AR interactions via AR Foundation

# \- ✅ Enable spatial gameplay using plane detection and object placement

# \- ✅ Implement a collectible mechanic with session tracking

# \- ✅ Decouple data logic to support later AWS integration

# \- ✅ Use clean and scalable Unity architecture

# \- ✅ Build-ready for Android (iOS optional)

# 

# ---

# 

# \## 🧱 Architecture Overview

# 

# ```plaintext

# Assets/

# ├── Scripts/

# │   ├── AR/                  # AR Foundation systems (placement, raycasting)

# │   ├── Game/                # Game state and gameplay logic

# │   ├── Data/                # Data abstraction layer (mock and AWS-ready)

# ├── Prefabs/                 # Collectible AR objects

# ├── Scenes/                 

# │   └── ARPrototypeScene.unity

