# Video Jumbler/Unjumbler

This repository contains a Jupyter Notebook that allows you to **jumble** and **unjumble** videos.

---

## Instructions to Run

1. **Clone the repository**

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
```

2. **Open the Jupyter Notebook**

* Launch Jupyter Notebook in the repo folder:

```bash
jupyter notebook
```

* Open the notebook file (`tecdia.ipynb`).

3. **Install Required Packages**

* In the first cell of the notebook, run:

```python
!pip install -r requirements.txt
```

* This will install all necessary Python packages.

4. **Run the Program**

* In the next cell, follow the instructions to **unjumble a video**.
* The default jumbled/input video file is:

```
jumbled_video.mp4
```

* Run the second cell to process the video and get it unjumbled.

5. **Jumble Any Video**

* You can also jumble any video using the notebook:

  * Place your video in the notebook folder.
  * Update the video file name in the cell where jumbled videos are processed.
  * Run the cell to generate a jumbled version.

---

## Notes

* Make sure your video files are in the same folder as the notebook.
* Output videos will be saved in the notebook folder by default.
* The notebook works with `.mp4` videos.
