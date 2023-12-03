pip install ninja

cd Self-Correction-Human-Parsing

tải https://drive.google.com/uc?id=1k4dllHpu0bdx38J7H28rVVLpU-kOHmnH
rename nó thành final.pth nhét vô cái checkpoints

python simple_extractor.py --dataset 'lip' --model-restore 'checkpoints/final.pth' --input-dir 'inputs' --output-dir 'outputs'