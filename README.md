### ⚙️ Local Setup (using `venv`)

To run this project locally in an isolated environment:

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/supply-chain-object-tracking.git
cd supply-chain-object-tracking

# Create and activate a virtual environment
python3 -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate.bat  # Windows (if needed)

# Install required dependencies
pip install -r requirements.txt

### 🔗 YOLOv5 Integration

This project uses [YOLOv5](https://github.com/ultralytics/yolov5) as a submodule for real-time object detection.

To clone the repository with YOLOv5 included, use:

```bash
git clone --recurse-submodules https://github.com/meelsaw/supply-chain-object-tracking.git
