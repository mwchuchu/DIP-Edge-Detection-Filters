# DIP-Edge-Detection-Filters
A Python-based repository for Digital Image Processing (DIP) operations, showcasing the application of Sobel, Prewitt, and Laplacian filters for edge detection.

## Features
- Implementation of Sobel filters (horizontal, vertical, and diagonal) for directional edge detection.
- Application of Prewitt filters to compare edge detection performance.
- Usage of the Laplacian filter to explore second-order derivative edge detection.
- Analysis of the effects of kernel size and noise on edge detection performance.

## Requirements
To run the code, ensure the following Python libraries are installed:
- OpenCV
- NumPy
- Matplotlib

Install the requirements using pip:
```bash
pip install opencv-python numpy matplotlib
```

## Usage
1. Clone the repository:
```bash
git clone https://github.com/your-username/DIP-Edge-Detection-Filters.git
```
2. Navigate to the project directory:
```bash
cd DIP-Edge-Detection-Filters
```
3. Run the provided `.py` scripts or use the `.ipynb` notebook for interactive exploration:
```bash
python <script_name>.py
```
4. Replace `image_path` in the scripts with the path to your test image.

## Files
- `DIP_lab10.ipynb`: A Jupyter notebook with edge detection demonstrations.
- `sobel_filters.py`: Python script for applying Sobel filters.
- `readme_repo_setup.md`: Project description and instructions.

## Results
The repository includes visual comparisons of edge detection using different filters. Example outputs showcase the effects of kernel size, noise levels, and preprocessing techniques.

## Contributing
Contributions are welcome! Please fork the repository, make changes, and submit a pull request.

## License
This project is licensed under the MIT License.

---

Push the repository to GitHub using the following commands:
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/your-username/DIP-Edge-Detection-Filters.git
git push -u origin main
