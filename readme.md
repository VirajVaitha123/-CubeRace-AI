# Portfolio

### Introduction
AvaSentinels is a community I created at work, helping find other people interested in Deep Reinforcement Learning. CubeRace is a game created by X, please follow the link below to play the original game.

[ADD GIF OF GAME]

The following changes where added by self:
- Script to create level by placing objects randomly across the platform.
- Adjusted physics (z-velocity reached within few seconds and constant speed maintained by applying force in the opposite direction)
- Added skybox (Star background)
- Trained agent using PPO Algorithm through the ML-Agents library, enabling the computer to learn how to solve the game using pixel data (Computer see's exactly what a human would see).


### Folder Structure (Update soon)

From my research the ideal structure for a FastAPI application can be seen below:
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
