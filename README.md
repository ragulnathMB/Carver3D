
# 🚀 Carver3D

**Carver3D** is a 3D reconstruction pipeline that transforms **2D orthographic views** (like front, top, and side images) into **3D models** using **silhouette carving**, **OpenCV** for image processing, and **Vulkan** for GPU-accelerated rendering. The goal is to create a fast, real-time tool that bridges low-level graphics programming and geometric modeling.

## 📽️ Demo Video
Watch the demo of Carver3D here [LinkedIn](https://www.linkedin.com/posts/ragulnathmb_3dmodeling-vulkan-cplusplus-activity-7344560022930001922-YUHx?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFPm830Bb6bt4s9etCOG8WGsJhNUTfwCvJQ).

![Carver3D Preview](https://i.ibb.co/GQq5cNDs/Screenshot-2025-07-01-091935.png)


---

## 📌 Features

- 🔺 **Silhouette Carving Algorithm** for accurate 3D shape generation from 2D contours  
- 🖼️ Supports standard **orthographic views** (Front, Top, Side)  
- ⚡ Built with **C++** for maximum performance and low-level control  
- 🎮 Real-time rendering using **Vulkan**  
- 🧠 **OpenCV**-powered image processing pipeline (thresholding, edge detection, segmentation)  
- 🔧 In-progress: **Surface refinement** with Gaussian smoothing and mesh optimization

---

## 📷 Example Workflow

1. Input 2D silhouettes (e.g., engineering drawings)  
2. Extract contours and preprocess with OpenCV  
3. Apply silhouette carving to create voxel model  
4. Render 3D output with Vulkan  
5. (Optional) Refine with smoothing & mesh cleanup

---

## 💻 Technologies Used

| Tool           | Purpose                           |
|----------------|-----------------------------------|
| **C++**         | Core logic and performance        |
| **OpenCV**      | Image preprocessing and analysis  |
| **Vulkan API**  | GPU-based real-time rendering     |
| **STL/OBJ**     | 3D mesh export (planned)          |

---

## 🚀 Getting Started

### 🔧 Prerequisites

- C++17 compatible compiler (MSVC, GCC, Clang)
- Vulkan SDK ([Install Here](https://vulkan.lunarg.com/sdk/home))
- OpenCV >= 4.x
- CMake >= 3.16

### 🛠️ Build Instructions

```bash
git clone https://github.com/yourusername/Carver3D.git
cd Carver3D
mkdir build && cd build
cmake ..
make
./Carver3D
```

---

## 🎯 Use Cases

- 📐 Engineering/CAD model reconstruction  
- 🕹️ Game asset generation from sketches  
- 🛠️ AR/VR scene prototyping  
- 📷 Educational visualization of 3D geometry concepts

---

## 🔍 Roadmap

- [x] Silhouette carving engine  
- [x] Vulkan-based preview renderer  
- [ ] STL/OBJ export  
- [ ] Mesh refinement (Laplacian smoothing, decimation)  
- [ ] GUI frontend using Dear ImGui or Qt  
- [ ] Interactive model manipulation (zoom, rotate, slice view)

---

## 🙌 Contributing

Contributions are welcome! Please fork the repo, open issues, or submit a pull request.

```bash
# Clone your fork
git clone https://github.com/yourusername/Carver3D.git
```

---

## 📬 Contact

**Ragulnath M B**  
📧 ragulnath2004@outlook.com  
📎 [LinkedIn](https://linkedin.com/in/ragulnathmb) | [GitHub](https://github.com/ragulnathMB)

---

## 📄 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

---

> *"Turning sketches into spatial reality, one voxel at a time."*
