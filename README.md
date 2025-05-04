# Segment_Anything_2

How to use Segment Anything 2.1?

1. Go to https://github.com/facebookresearch/sam2

2. In your Anaconda Prompt, paste

git clone https://github.com/facebookresearch/sam2.git && cd sam2

3. Then paste

pip install -e .

4. Open https://github.com/facebookresearch/sam2?tab=readme-ov-file#model-description

And download all the SAM 2.1 checkpoints and configs files.

5. Paste the checkpoint files in sam2/checkpoints path.

6. Paste the config files in sam2/sam2/configs/sam2.1 path.

7. With Segment_Anything_2_annotation.ipynb in the sam2 path, open and start using the script to segment the object by drawing each bounding box.

8. To undo the drawing of a bounding box, press u, to finish drawing the bounding boxes, press ENTER.

9. The Segment Anything 2.1 programme, will automatically segment your objects in the bounding boxes into masks and segmented images.
