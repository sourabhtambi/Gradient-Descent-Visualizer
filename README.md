#Gradient Descent Visualizer 📉🚀

A hands-on, visual demonstration of how Linear Regression actually "learns." This project implements the Gradient Descent algorithm from scratch (no Scikit-Learn!) and animates the training process step-by-step.

🎯 What does this do?

Most tutorials show you the final result of a Machine Learning model. This project shows you the journey.

It creates a synthetic dataset, initializes a random "best guess" line, and then mathematically optimizes that line over 100 iterations. You can watch the line rotate and slide until it fits the data perfectly.

🧠 The Concept: "The Blind Paratrooper"

To understand Gradient Descent, imagine this:

The Drop (Initialization): A paratrooper is dropped onto a foggy, jagged mountain range. They are blindfolded. Their goal is to find the lowest point in the deepest valley (Zero Error).

The Feel (The Gradient): Since they can't see, they feel the slope of the ground under their feet. If it tilts up, they go the other way. If it tilts down, they take a step forward.

The Descent (Learning Rate): They keep taking steps. Big steps at first, then smaller ones as the ground flattens out.

The Arrival (Convergence): Eventually, the ground becomes flat. They have reached the bottom. The cost is minimized. The model is trained.

This code visualizes that exact descent!

🛠️ Installation & Usage

Option 1: Run in Google Colab (Recommended)

This code is optimized for Jupyter/Colab environments using the to_jshtml() method for interactive video playback.

Copy the code from main.py.

Paste it into a Google Colab cell.

Run the cell to see the interactive JavaScript animation.


