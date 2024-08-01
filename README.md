# agar-io-bot
This is a project that implements a script to play the online game [Agar io](https://agar.io/) using a binary classifier. 
This project is inspired by [Learning to fly by crashing](https://ieeexplore.ieee.org/document/8206247). 

## method
- [x] Built a binary classification dataset by capturing screenshots of the blob moving straight in some direction. 
The snapshots immediately before a game ending collision were labeled `danger` and the snapshots long before the 
collision were labeled `safe`.
- [x] Trained a binary classifier to classify the images as `safe` or `dangeroud`.
- [x] Use the classifier to determine danger in multiple directions use that to inform play.
- [x] Used `pyautogui` to control mouse

![Screenshot 2024-08-01 003654](https://github.com/user-attachments/assets/57d90efb-a459-45fd-9291-61bc60190d77)
