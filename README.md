## Video-LLaVA
```bash
cd Video-LLaVA
bash finetune.sh
bash inference.sh
```

## LLaMA-VID
```bash
cd LLaMA-VID
bash finetune.sh
bash inference.sh
```

## LongVU
```bash
cd LongVU
bash train_longvitu_qwen.sh
python scripts/consolidate_checkpoint.py --model_path output/cambrian_qwen2_7b_longvitu_train_101k/checkpoint-xxxx
bash eval_egoschema&videomme.sh
```

## Acknowledgement
Thanks for the codebase of [Video-LLaVA](https://github.com/PKU-YuanGroup/Video-LLaVA), [LLaMA-VID](https://github.com/dvlab-research/LLaMA-VID) and [LongVU](https://github.com/Vision-CAIR/LongVU).

## License
- Code: [Apache](LICENSE)
- Data: [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.en)
