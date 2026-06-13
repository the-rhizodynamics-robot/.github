# The Rhizodynamics Robot

**Automated, high-throughput time-lapse imaging for studying long-term root growth.**

The Rhizodynamics Robot *GROOT* (Generating Rhizodynamic Observations Over Time) is
a low-cost robotic imaging platform that photographs many containers of plants growing
in a clear gel medium, repeatedly, over days to months. A 2-axis camera gantry visits
each container on a fixed schedule and captures images, enabling time-lapse study of
root systems that are normally hidden underground.

The system was built from widely available, inexpensive parts and has been used to image
root growth in *Arabidopsis*, *Oryza sativa* (rice), *Hudsonia montana*, and several orchid species
including *Platanthera integrilabia*.

---

## Repositories

| Repo | What it is |
|------|------------|
| [**robot-control**](https://github.com/the-rhizodynamics-robot/robot-control) | Arduino firmware for the camera gantry + a Python host program that configures a run, drives the robot over serial, and supervises image capture. |
| [**qr-coding**](https://github.com/the-rhizodynamics-robot/qr-coding) | A tool for generating printable QR-code labels for the growth containers, so each plant is uniquely identified in the image record. |

---

## Origin & contributions

This project grew out of a collaboration between the lab of **Dr. Daniel I. Goldman**
(Georgia Institute of Technology) and the lab of **Dr. Philip N. Benfey** (Duke
University), and is currently supported by **Dr. Mingyuan Zhu** (Texas A&M University).

- **Lead developer:** [Isaiah W. Taylor](https://github.com/the-rhizodynamics-robot)
- **Key past contributors:** Aradhya Rajanala, Erin McCaskey, Carrie Hunner, and Anupam Mijar.
- **Additional collaborators:**Christopher Pierce, Jason Ligon, Enes Aydin, Amanda Carmichael, 
 Lauren Eserman, Emily E. D. Coffee, Milan Shah, and the Goldman and Benfey labs.

Contributions and questions from people using the system are welcome: open an issue or
a pull request on the relevant repository.

---

## How to cite

If you use the Rhizodynamics Robot in your research, please cite the paper that describes
the system:

> Rajanala A, Taylor IW, McCaskey E, Pierce C, Ligon J, Aydin E, Hunner C, Carmichael A,
> Eserman L, Coffee EED, Mijar A, Shah M, Benfey PN, Goldman DI. **The rhizodynamics
> robot: Automated imaging system for studying long-term dynamic root growth.**
> *PLOS ONE* 18(12): e0295823 (2023). https://doi.org/10.1371/journal.pone.0295823

📄 Read the paper: <https://doi.org/10.1371/journal.pone.0295823>
