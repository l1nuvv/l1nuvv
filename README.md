### Hi, I'm Danila

A self-taught **C++ Developer** with a strong focus on **High-Performance Computing** and **Computer
Vision**.

I am passionate about writing clean, efficient, and modern C++ code to solve complex engineering problems. I'm currently
the core developer on a stealth-mode startup project involving geospatial data analysis.


![My CodeWars](https://www.codewars.com/users/l1nuvv/badges/small)

---

### 🛠️ My Tech Stack

This is the technology I use daily and know from hands-on experience.

| Category                 | Technologies                                                                                        |
|:-------------------------|:----------------------------------------------------------------------------------------------------|
| **Language & Paradigms** | `C++ (11/17/20)`, `Object-Oriented Programming`, `Parallel Programming(OpenMP)`                                |
| **High-Performance C++** | `Multithreading`, `OpenMP`,                   |
| **Core Libraries**       | `OpenCV`, `GDAL`, `spdlog`, `Eigen`, `OpenGL`, `GLFW`                                                       |
| **Tools & Environment**  | `CMake`, `Git`, `Visual Studio`, `CLion`, `Ninja`, `Windows & Linux (Native, WSL, VM)`, `Wireshark` |
| **Domain Knowledge**     | `Computer Vision`, `GIS`, `Image Processing`, `Geostatistics (Variograms)`                          |

---

### 🔭 Featured Project

#### **Field Analyzer** (Private Startup Project)

A console-based engine for high-performance analysis of Sentinel-2 satellite imagery.

* **What it does:** Processes gigabytes of `.jp2` images to calculate vegetation indices (NDVI, EVI) and performs
  geostatistical analysis to model spatial dependencies.
* **My Contribution:**
    * Architected and implemented the core processing pipeline.
    * **Optimized the variogram calculation loop, achieving a 3-4x performance increase** by parallelizing the algorithm
      with **OpenMP**.
    * Designed and implemented a custom **thread-safe logging system** using `std::mutex` and `std::lock_guard` to
      prevent race conditions in parallel regions.
    * Reduced algorithmic complexity from $O(N^2)$ to $O(N \log N)$ by integrating the **FLANN KD-Tree** library for
      efficient nearest-neighbor search.

---

### 🌱 What I'm Learning Next

* **Vulkan API:** Deepening my knowledge in low-level graphics programming.
* **Advanced C++20/23:** Coroutines, Ranges, and Concepts.
* **CI/CD:** Automating builds and tests with GitHub Actions, focus on DevOps too

---
*Open to challenging opportunities in C++ Development, particularly in performance-critical domains.*
