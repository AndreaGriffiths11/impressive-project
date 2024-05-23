# impressive-project 🚀
An impressive project built with GitHub Copilot Chat in 5 mins - DevWeek Main Stage Demo

# Local Development
💡 Ensure you have python installed on your machine. 

- clone the repo to your machine
- `cd` into the project
- in your terminal run `python3 app.py`
- open up the UI `http://127.0.0.1:5000`
- enter a num and submit
- in a second terminal run `python3 plot.py`
- you should have an external screen with the moving plot.
- put the screen with the plot and the UI side by side
- update the num in the UI to a much higher number
- watch the plot move faster!

> Note: The higher the submitted num, the faster the line moves - or the more sine waves is shifted for each frame, which make the line appear to move faster.
> The number acts as a multiplier for the speed of the wave’s movement. 

# Execution Details
This project involves running two Python scripts: `app.py` and `plot.py` to demonstrate a dynamic interaction between a web form and a plot animation.

- **Technical Requirements:**
  - Python installed on your machine.
  - Flask installed for running the web server (`pip install flask`).
  - Matplotlib installed for plotting and animating the sine wave (`pip install matplotlib`).

- **Setup Steps:**
  1. Clone the repository to your local machine.
  2. Navigate into the project directory.
  3. Run `python3 app.py` to start the Flask web server.
  4. Open `http://127.0.0.1:5000` in a web browser to access the form.
  5. Submit a number through the form, which is then saved to `data.json`.
  6. In a separate terminal, run `python3 plot.py` to start the animation.
  7. The plot animation reads the submitted number from `data.json` and animates a sine wave plot accordingly, with the number affecting the animation speed.

The interaction between the web form and the plot animation is a key aspect of this project. Submitting different numbers through the form will result in varying speeds of the sine wave animation, demonstrating a real-time data-driven visualization.

# Contributing
Contributions are welcomed to improve the app. Please open an issue to discuss larger changes to the app.

# License
MIT
