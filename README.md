# final_project_stat150

## 🚀 Getting Started

Follow these steps to get the project set up on your local machine.

### 1. Clone the Repository

The easiest way to get the project is to clone it using RStudio:

1.  In RStudio, go to **File > New Project...**
2.  Select **Version Control** > **Git**.
3.  Paste in the repository URL: `https://github.com/sNIKyf/final_project_stat150.git`
4.  Click **"Create Project"**.

### 2. Set Up the Data (Important!)

This project uses large data files that are **not** tracked by Git. You must add them to the project manually.

1.  In the project's main folder, create a new folder named `Data/`.
2.  Download the required data files from: **[[LINK HERE](https://drive.google.com/drive/folders/14iUsiuDiTaw6Fe8dhUjaYq_k-WIOwlN2?usp=share_link)]**
3.  Place the downloaded data inside the `Data/` folder. The final folder structure must look like this for the code to work:

    ```
    final_project_stat150/
    ├── Data/
    │   ├── green_tripdata_2025-05/   (This is a folder)
    │   │   └── ... (parquet files go in here)
    │   ├── yellow_tripdata_2025-05/  (This is a folder)
    │   │   └── ... (parquet files go in here)
    │   └── NYC_Event_Information_Historical_05.2025.csv
    ├── .gitignore
    ├── README.md
    ├── final_project_stat150.Rproj
    └── ... (your .R files, etc.)
    ```

## 🤝 How to Contribute

Please follow this simple workflow to add your work and collaborate with the team.

1.  **Pull Changes (Start of your session)**
    Before you start working, always get the latest changes from GitHub. This prevents merge conflicts.
    * In RStudio, go to the **Git** pane and click the blue **"Pull"** button (⬇️).

2.  **Do Your Work**
    Write your code, save your scripts, and run your analysis as usual.

3.  **Commit Your Changes (End of your session)**
    When you've finished a task (or at the end of the day), save a snapshot of your changes to the project's history.
    * Go to the **Git** pane.
    * Check the **"Staged"** box next to all the files you changed.
    * Click **"Commit"**.
    * Write a clear "Commit message" (e.g., "Updated geocoding logic for events") and click **"Commit"**.

4.  **Push Your Changes**
    To share your new commits with the team, click the green **"Push"** button (⬆️) in the Git pane. This sends your local commits to GitHub.
