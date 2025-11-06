# Comparing Vision Models

1. Ultralytics/SAM 2.1 base
2. Ultralytics/SAM 2.1 large
3. Ultralytics/FastSAM-s with YOLOv8 backbone
4. facebook/sam-vit-huge
5. finegrain/finegrain-box-segmenter

## SAM Loading Time comparision
![sam_loading_time](sam_loading_time.png)

## SAM Running Time comparision on Llama Image
![sam_model_performance](sam_model_performance.png)

## Models Total Time comparision on Llama Image
![total_time](total_time.png)

## Models comparision on BaseLine Images
[! NOTE] Matting can be applied to any of the masks, here I applied it just in finegrain model (without prompts)
![comparison_grid](comparison_grid.png)
