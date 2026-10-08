# Adaptive SVD-Based Low-Rank Compression for Efficient CCTV Video Storage

## About the Project

This project implements SVD-based low-rank compression for CCTV video frames. It evaluates the trade-off between video/image quality and storage reduction using metrics such as MSE, PSNR, SSIM and compression ratio.

The project also compares SVD compression with JPEG compression and generates a reconstructed CCTV video.

## Files

```text
CCTV-SVD-Compression/
│
├── README.md
├── CCTV_SVD_Compression.ipynb
└── sample_cctv.mp4
```

* **CCTV_SVD_Compression.ipynb** – Main project notebook containing the complete code and analysis.
* **sample_cctv.mp4** – Sample CCTV video used for testing.

## Requirements

The project is designed to run using **Google Colab**.

The required Python libraries are installed automatically by the notebook:

* OpenCV
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-image

## How to Run

1. Open `CCTV_SVD_Compression.ipynb` in Google Colab.
2. Run the cells from the beginning in order.
3. When the upload option appears, upload `sample_cctv.mp4`.
4. Continue running the remaining cells.
5. The notebook will display:

   * Original and reconstructed CCTV frames
   * MSE, PSNR and SSIM values
   * Compression ratios and storage savings
   * Graphs and analysis
   * JPEG comparison
   * Reconstructed CCTV video
6. Generated CSV files and the reconstructed video can be viewed in the **Files** section of Google Colab.

## Team Members

* Member 1 – Lochana Ashok J
* Member 2 – Hanna Tisa Roy
* Member 3 – Agreya Tejas K S
* Member 4 – Vihaan Khatri
