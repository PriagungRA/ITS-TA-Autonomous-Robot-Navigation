# ITS Undergraduate Thesis

## Autonomous Wheeled Robot Navigation Based on Fuzzy Logic Using LiDAR and Thermal Camera

This repository contains the complete LaTeX source code of an undergraduate thesis submitted to the Department of Electrical Engineering, Institut Teknologi Sepuluh Nopember (ITS), Surabaya, Indonesia.

---

## Author

**Priagung Ramadhan Alfalakhi**
NRP: 5022221161
Department of Electrical Engineering
Institut Teknologi Sepuluh Nopember (ITS)

---

## Thesis Abstract

This research proposes an autonomous wheeled robot navigation system that integrates LiDAR sensing and thermal camera perception through a Mamdani fuzzy logic framework. The system combines obstacle information obtained from LiDAR with traversability estimation derived from thermal image segmentation to improve navigation safety, particularly in areas that are difficult to observe using a single sensor modality. Artificial Potential Field (APF) is employed as the local navigation strategy, while fuzzy inference dynamically adjusts navigation behavior according to environmental conditions.

The proposed approach is evaluated in multiple indoor simulation scenarios using ROS and Gazebo, including environments with static and dynamic obstacles. Experimental results demonstrate that the integration of fuzzy logic and multi-sensor perception can improve navigation robustness and obstacle avoidance performance.

---

## Research Areas

* Autonomous Mobile Robots
* Robot Navigation
* LiDAR Perception
* Thermal Vision
* Sensor Fusion
* Mamdani Fuzzy Logic
* Artificial Potential Field (APF)
* ROS Navigation Stack
* Gazebo Simulation

---

## Repository Structure

```text
.
├── abstrak/      # Indonesian and English abstracts
├── bab/          # Thesis chapters
├── gambar/       # Figures and illustrations
├── lampiran/     # Appendices
├── lainnya/      # Acknowledgement, biography, approval pages
├── pustaka/      # Bibliography and thesis variables
├── sampul/       # Thesis cover files
└── main.tex      # Main LaTeX document
```

---

## Compilation

Compile using XeLaTeX and Biber:

```bash
xelatex main.tex
biber main
xelatex main.tex
xelatex main.tex
```

or

```bash
latexmk -xelatex main.tex
```

---

## Related Repository

The implementation source code, ROS packages, simulation environment, and experimental framework used in this research are available at:

https://github.com/PriagungRA/TA-Autonomous-Robot-Navigation-Fuzzy-Lidar-Thermal

---

## License

This repository is provided for academic and educational purposes.

© Priagung Ramadhan Alfalakhi
