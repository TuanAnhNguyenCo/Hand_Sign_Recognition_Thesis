
# Testing
- Run I3D:
  + Sim Knowledge Distillation: `python3 main.py --config configs/Knowledge_Distillation/i3d/test_cfg/i3d_one_view_finetune_from_autsl_knowledge_distillation_v1.yaml`
  + Three view (Finetune from one view):  `python3 main.py --config configs/i3d/test_cfg/i3d_three_view_finetune_from_one_view.yaml`
  + One view : `python3 main.py --config configs/i3d/test_cfg/i3d_one_view_finetune_from_autsl.yaml`
  + Three view share weights: `python3 main.py --config configs/ablation_study/share_weights/i3d/test_cfg/i3d_three_view_finetune_from_one_view_share_weights.yaml`
  + One view (From Charades): `python3 main.py --config configs/ablation_study/another_dataset/i3d/test_cfg/i3d_pretrained_charades_one_view.yaml`
  + Hand Crop (From Charades): `python3 main.py --config configs/ablation_study/hand_crop/i3d/test_cfg/i3d_pretrained_charades_one_view_HC.yaml`
  

- Run MViTv2:
  + Sim Knowledge Distillation: `python3 main.py --config configs/Knowledge_Distillation/mvit_v2/test_cfg/mvit_v2_S_one_view_finetune_from_autsl.yaml`
  + Three view (Finetune from one view): `python3 main.py --config configs/mvit_v2/test_cfg/mvit_v2_S_three_view_finetune_from_one_view.yaml`
  + One view: `python3 main.py --config configs/mvit_v2/test_cfg/mvit_v2_S_one_view_finetune_from_autsl.yaml`
  + Three view share weights: `python3 main.py --config configs/ablation_study/share_weights/mvit_v2/test_cfg/mvit_v2_S_three_view_finetune_from_one_view_share_weights.yaml`
  + One view (From Kinetics 400): `python3 main.py --config configs/ablation_study/another_dataset/mvit_v2/test_cfg/mvit_v2_S_one_view_pretrained_on_kinetics400.yaml`
  + Hand Crop (From Charades): `python3 main.py --config configs/ablation_study/hand_crop/mvit_v2/test_cfg/mvit_v2_S_one_view_pretrained_on_kinetics400.yaml`
  + MViTv2 + Visual Prompt Tunning (3 views): `python3 main.py --config configs/visual_prompt_tuning/mvit_v2/test_cfg/mvit_v2_S_three_view_finetune_from_one_view_share_weights.yaml`
  + Three view (Finetune from AUTSL): `python3 main.py --config configs/mvit_v2/test_cfg/mvit_v2_S_three_view_finetune_from_AUTSL.yaml`
  

- Run Video Swin Transformer:
  + Sim Knowledge Distillation: `python3 main.py --config configs/Knowledge_Distillation/swin_transformer_3d/test_cfg/swin_transformer_3d_T_one_view_finetune_from_autsl.yaml`
  + Three view (Finetune from one view): `python3 main.py --config configs/swin_transformer_3d/test_cfg/swin_transformer_3d_T_three_view_finetune_from_one_view.yaml`
  + One view: `python3 main.py --config configs/swin_transformer_3d/test_cfg/swin_transformer_3d_T_one_view_finetune_from_autsl.yaml`
  + Three view share weights: `python3 main.py --config configs/ablation_study/share_weights/swin_transformer_3d/test_cfg/swin_transformer_3d_T_three_view_finetune_from_one_view_share_weights.yaml`
  + One view (From Kinetics 400): `python3 main.py --config configs/ablation_study/another_dataset/swin_transformer_3d/test_cfg/swin_transformer_3d_T_one_view_pretrained_on_kinetics400.yaml`
  + Hand Crop (From Charades): `python3 main.py --config configs/ablation_study/hand_crop/video_swin_transformer/test_cfg/swin_transformer_3d_T_HC_one_view_pretrained_on_kinetics400.yaml`
9


- Run VTNHCPF:
  + Sim Knowledge Distillation: `python3 main.py --config configs/Knowledge_Distillation/vtn_hc_pf/test_cfg/vtn_hc_pf_sim_KD_oneview.yaml`
  + Three view (Finetune from one view): `python3 main.py --config configs/vtn_att_poseflow/test_cfg/vtn_att_poseflow_three_view_finetune_from_one_view.yaml`
  + One view: `python3 main.py --config configs/vtn_att_poseflow/test_cfg/vtn_att_poseflow_autsl_to_vn_sign.yaml`
  + One view (From Kinetics 400): `python3 main.py --config configs/ablation_study/another_dataset/vtn_att_poseflow/test_cfg/vtn_att_poseflow.yaml`