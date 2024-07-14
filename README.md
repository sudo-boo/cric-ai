# Cric-AI

 The goal is to take a data-driven approach in cricket to achieve highly accurate results using minimal data.

---

## Pitch-Map

**Objective**

Determine pitch map of deliveries by just using the Umpire POV video feed

All the visualizations I used in this are mostly images that I provide along with explanations, and based visualizations. `generate-pitch-map.ipynb` is attached along with the report.

**Results**

![newplot3](https://github.com/user-attachments/assets/fddf62e4-65f1-4896-a507-1a342ecfb30f)

I also used a Desmos simulation for the ball pitching and perspective analysis. Each ball can be roughly assumed to be a skewed sine line in 3D space. To check that live : [Click Here](https://www.desmos.com/3d/a951e169b8)

---

## Ultra-Edge

 **Objective** 

Noise Suppression: Use two microphones (one near the bat, one further away) to filter out crowd noise.
Frequency Analysis: Identify spikes in bat-ball strike frequency band gaps using a frequency spectrum tool.
Detect spikes in specific frequency ranges that indicate bat-ball strikes.

**Results**

![image](https://github.com/user-attachments/assets/146ae5d4-011e-43f9-99d1-01b6f826377e)


---

## Prerequisites

- Python 3.x
- Required Python packages (listed in `requirements.txt`)

## Setup Instructions

1. **Clone the repository:**

    ```sh
    git clone https://github.com/sudo-boo/cric-ai
    cd cric-ai
    ```

2. **Install dependencies:**

    Make sure you have `pip` installed, then run:

    ```sh
    pip install -r requirements.txt
    ```

