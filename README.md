
## Train
python main.py \
    --title mjosavn_train \
    --model MJOSAVN \
    --gpu-ids 0\
    --workers 8 \
    --vis False \
    --save-model-dir trained_models
Other model options are "SAVN" and "GCN"

#### Full evaluation on training
python full_eval.py \
    --title mjolnir \
    --model MJOSAVN \
    --results_json MJOSAVN.json \
    --gpu-ids 0
    --save-model-dir trained_models
    

