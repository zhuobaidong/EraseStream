# EraseStream

## 评测的几个模型以及对应 repo
EffectErase：https://github.com/FudanCVL/EffectErase <br>
MiniMax-Remover：https://github.com/zibojia/MiniMax-Remover <br>
VACE: https://github.com/ali-vilab/VACE

## 下载评测的数据（83个视频对 video+mask）
hf download --repo-type dataset --include "davis_evaluation/*" --local-dir ./davis_evaluation zhuobai/StreamErase
