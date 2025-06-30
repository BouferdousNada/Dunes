## 📁 Output Folders (Logs and Results)

The model is initially **pretrained on MS COCO weights**, which can be downloaded here:  
🔗 [mask_rcnn_coco.h5](https://github.com/matterport/Mask_RCNN/releases/download/v2.0/mask_rcnn_coco.h5)

These weights serve as a starting point for training on the submarine dune dataset. When running the `dunes.py` script, two key output directories are generated:

### 📂 `logs/`
This folder contains:
- **Model checkpoints** automatically saved during training (`mask_rcnn_dunes_*.h5`)
- **TensorBoard logs**, useful for tracking loss, accuracy, and other training metrics

By default, logs are saved in the `logs/` directory at the project root unless another path is specified via the `--logs` argument.

### 📂 `results/dunes/`
This folder includes:
- **Prediction results**, such as annotated images and masks
- A `submit.csv` file containing the masks encoded in RLE (Run-Length Encoding) format, useful for submissions or further automated analysis

Each `detect` command execution creates a timestamped subfolder like:  
`results/dunes/submit_20250615T142311/`
