# CubeRace - AI learning to complete 'CubeRace'

### Introduction
Cube race is a game that requires the you to dodge obstacles to reach the end of the obstacle course. The obstacles are generated and placed randomly encouraging the agent to learn the generalised skill to avoid obstacles, as opposed to learning how to complete one static level.

The game can be made more advanced to assess the performance on teaching an AI agent, and exploring what techniques are required to help overcome such complexities. Some examples include:
- Varying speed over the course  (Apply more force per second)
How could the agent be aware of speed with only using pixel information ? (Stacking frames?)
- Add rotating obstacles
- Reduce platform width and increase number of obstacles in a short space


AvaSentinels is a community I created at work, helping find other people interested in Deep Reinforcement Learning. CubeRace is a game created by X, please follow the link below to play the original game.

[ADD GIF OF GAME]

The following changes where implmeneted from the original game:
- Script to create level by placing objects randomly across the platform.
- Adjusted physics (z-velocity reached within few seconds and constant speed maintained by applying force in the opposite direction)
- Added skybox (Star background)
- Trained agent using PPO Algorithm through the ML-Agents library, enabling the computer to learn how to solve the game using pixel data (Computer see's exactly what a human would see).


### Folder Structure (Update soon)

```
📦app
 ┣ main.py ⭐
 ┣ 📂routers 
 ┃ ┣ 📜machine_learning_gallery.py   #API routes - keeps main.py clean
 ┣ 📂helpers
 ┃  ┣ 📂 data_processing.py   #API routes - keeps main.py clean
 ┃  ┃  ┣  📜azure_blob_wrapper.py
 ┃  ┃  ┣  📜img_utils.py
 ┃  ┃  ┣  📜background_tasks.py
 ┃  ┃  ┗  📜schemas.py
 ┃  ┣ 📂 machine_learning.py
 ┃  ┃  ┗ 📜image_segmentation.py
 ┃  ┣ 📂responses.py
 ┃  ┃  ┗ 📜responses_json.py
 ┣ 📂static
 ┃ ┣ 📂home_page
 ┃ ┃  ┣ 📂assets
 ┃ ┃  ┣ 📂css
 ┃ ┃  ┗ 📂js
 ┗ 📂templates
  ┗ 📜clustering_examples.html
```

### Getting Started

#### Step 1: Create 3D Project inside Unity

#### Step 2: Import Repositary inside Unity Project

#### Step 3: Open Scenes folder and select LeveL 1

#### Step 4: Select Heuristics to play the game yourself

#### Step 5: Drag and drop the model onnx file from the model folder to the Player GameObject, Behaviours component
