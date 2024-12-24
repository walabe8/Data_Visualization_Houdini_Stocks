# Data_Visualization_Houdini_Stocks
A Houdini data-driven setup and procedural animation. Imported stock performance data generated from a CSV file, and a Houdini setup that visualizes the data and animates the stocks' performance from week to week.

https://github.com/user-attachments/assets/4dab7cb9-19c1-496e-a271-54c5aa264795

<img width="869" alt="image" src="https://github.com/user-attachments/assets/0a4847c4-4e4f-4e29-be2f-9ce5b7847692" />

1. We bring our CSV table data into Houdini, extract some of the key data points from it, and set up our base geometry.
2. Create a procedural animation system that will animate the data from state to state - without keyframes. Because we use this system multiple times, we turn it into a Houdini Digital Asset (HDA).
3. After setting up the data blocks and data animation, extract text from the CSV file, convert it into 3D text, and procedurally place it in the layout.
4. Finally, frame the layout for the camera. Apply procedural methods to normalize the data and limit it within the camera's view angle.
