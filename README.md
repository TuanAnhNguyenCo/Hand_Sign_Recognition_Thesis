
# Testing
- Run I3D:
  + Sim Knowledge Distillation: `python3 main.py --config configs/Knowledge_Distillation/i3d/test_cfg/i3d_one_view_finetune_from_autsl_knowledge_distillation_v1.yaml`
  + Three view:  `python3 main.py --config configs/i3d/test_cfg/i3d_three_view_finetune_from_one_view.yaml`
  + One view: `python3 main.py --config configs/i3d/test_cfg/i3d_one_view_finetune_from_autsl.yaml`
  

- Run MViTv2:
  + Sim Knowledge Distillation: `python3 main.py --config configs/Knowledge_Distillation/mvit_v2/test_cfg/mvit_v2_S_one_view_finetune_from_autsl.yaml`
  + Three view: `python3 main.py --config configs/mvit_v2/test_cfg/mvit_v2_S_three_view_finetune_from_one_view.yaml`
  + One view: `python3 main.py --config configs/mvit_v2/test_cfg/mvit_v2_S_one_view_finetune_from_autsl.yaml`



- Run Video Swin Transformer:
  + Sim Knowledge Distillation: `python3 main.py --config configs/Knowledge_Distillation/swin_transformer_3d/test_cfg/swin_transformer_3d_T_one_view_finetune_from_autsl.yaml`
  + Three view: `python3 main.py --config configs/swin_transformer_3d/test_cfg/swin_transformer_3d_T_three_view_finetune_from_one_view.yaml`
  + One view: `python3 main.py --config configs/swin_transformer_3d/test_cfg/swin_transformer_3d_T_one_view_finetune_from_autsl.yaml`



- Run VTNHCPF:
  + Sim Knowledge Distillation: `python3 main.py --config configs/Knowledge_Distillation/vtn_hc_pf/test_cfg/vtn_hc_pf_sim_KD_oneview.yaml`
  + Three view: `python3 main.py --config configs/vtn_att_poseflow/test_cfg/vtn_att_poseflow_three_view_finetune_from_one_view.yaml`
  + One view: `python3 main.py --config configs/vtn_att_poseflow/test_cfg/vtn_att_poseflow_autsl_to_vn_sign.yaml`