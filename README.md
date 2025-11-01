#  Intelligent Video Frame Reordering System

A powerful computer vision tool that scrambles and reconstructs video sequences using AI-driven frame analysis, optical flow detection, and temporal pattern recognition.

## 📋 Overview

This project reconstructs jumbled or shuffled video sequences back into their original temporal order using computer vision techniques. The algorithm analyzes frame-to-frame similarities and builds an optimal sequence representing the most likely chronological order.

**Input**: Jumbled video file (e.g., `jumbled_video.mp4`)  
**Output**: Reconstructed video (e.g., `reconstructed_video.mp4`)

### 

## 📄 **How It Works (Explanation of Approach and Thought Process) (PDF)**

> ⚡ **Access the full technical documentation here:**  
> [ALGORITHMIC APPROACH AND THOUGHT PROCESS (PDF)]([./DMMS_Special_Issue_on_BPM___Research___Case_Study_Template__3_.pdf](https://drive.google.com/file/d/1IgmjLNp-j39k9XEcR1kfd0MbBy7X95ea/view?usp=sharing))

---

## 🚀 Quick Start

### Prerequisites

- Python 3.7+
- Jupyter Notebook or VS Code with Jupyter extension
- 4GB+ RAM recommended

### Installation

---

1. **Clone the repository**

```bash
git clone https://github.com/AKSHITAK1040/tecdia-video-reconstruction.git
cd tecdia
```

2. **Install Required Packages**

* In the first cell of the notebook file (tecdia.ipynb), run:

```bash
pip install -r requirements.txt
```

* Required packages include: `opencv-python`, `numpy`, `torch`, `tqdm`

3. **After running the first cell, execute the second (main) cell to produce the jumbled video output.**
---



* **Step 1:** Run the first cell to ensure all packages are installed.
* **Step 2:** To **unjumble a video**, make sure your input video file is named `jumbled_video.mp4` and placed in the notebook folder. Run the second cell to process the video.
* **Step 3:** To **jumble any video**, place your video in the folder, update the filename in the cell, and run the cell to generate a jumbled version.

4. **Output**

* All processed videos (jumbled or unjumbled) will be saved in the same folder as the notebook.

---

## Notes

* Ensure that your video files are in `.mp4` format.
* Make sure to run the notebook in the same directory where the video files are located.


## 📖 Usage

### Unjumble a Video

1. Place your scrambled video as `jumbled_video.mp4`
2. Open `tecdia.ipynb`
3. Run the **MAIN CELL** (marked at top of notebook)
4. Output: `reconstructed_video.mp4`

### Process Custom Video

Modify the filename in the main cell:
```python
if __name__ == "__main__":
    main("your_video.mp4")
```

### Sample Output
```
✅ Using device: cpu with 16 threads
🎞️ Extracting frames...
✅ Extracted 240 frames
🧮 Computing similarity matrix...
🔍 Building optimal chain...
✅ Best chain: Avg=0.8734
🎬 Rebuilding video...
✅ Done! Total: 45.32s
```

## 📁 Project Structure

```
video-unjumbler/
│
├── tecdia.ipynb                    # Main notebook
├── requirements.txt                # Dependencies
├── DMMS_Special_Issue_...pdf      # Algorithm documentation
├── jumbled_video.mp4              # Input video
├── reconstructed_video.mp4        # Output video
├── frames/                        # Temp storage (auto-created)
└── README.md                      # This file
```

## 📚 Documentation

**Complete technical documentation available in the PDF:**
- Algorithm pipeline and flowchart
- Mathematical formulations
- Similarity metrics equations
- Computational complexity analysis
- Implementation details

📄 **[→ Open Documentation PDF](./DMMS_Special_Issue_on_BPM___Research___Case_Study_Template__3_.pdf)**

## ⚙️ Performance

| Video Length | Processing Time |
|--------------|-----------------|
| < 5 minutes  | 30-60 seconds   |
| 5-15 minutes | 1-3 minutes     |
| > 15 minutes | 3-10 minutes    |

*Multi-threaded processing uses all available CPU cores*

## 💡 Use Cases

- 🔍 Video forensics and recovery
- 🎓 Computer vision education
- 🧩 Video puzzle creation
- 📹 Corrupted data restoration

## 🎯 Key Features

- Fully automatic reconstruction
- Multi-threaded parallel processing
- Temporal flow validation
- Outlier detection and removal
- Real-time progress tracking

## 🤝 Contributing

Contributions welcome! Submit Pull Requests or open issues.

## 📧 Contact

**Author**: Akshit Chaudhary  
**Date**: November 2025

---

**For detailed algorithm explanation, see the [PDF documentation](./DMMS_Special_Issue_on_BPM___Research___Case_Study_Template__3_.pdf)*
