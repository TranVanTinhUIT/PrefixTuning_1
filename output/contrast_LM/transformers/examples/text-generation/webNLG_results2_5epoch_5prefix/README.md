# Data Description

This data comprises the output of model training (Training precess with prefix length batch size = 5 and epoch = 5) for the text generation task. Initially, the files were named as follows:

- webnlgprefixtune_y_5_act_cat_b=5-e=5_d=0.0_u=no_lr=5e-05_w=0.0_s=101_r=n_m=512_o=1_o=1_test_beam
- webnlgprefixtune_y_5_act_cat_b=5-e=5_d=0.0_u=no_lr=5e-05_w=0.0_s=101_r=n_m=512_o=1_o=1_test_beam_eval
- webnlgprefixtune_y_5_act_cat_b=5-e=5_d=0.0_u=no_lr=5e-05_w=0.0_s=101_r=n_m=512_o=1_o=1_test_gold
- webnlgprefixtune_y_5_act_cat_b=5-e=5_d=0.0_u=no_lr=5e-05_w=0.0_s=101_r=n_m=512_o=1_o=1_test_src
- webnlgprefixtune_y_5_act_cat_b=5-e=5_d=0.0_u=no_lr=5e-05_w=0.0_s=101_r=n_m=512_o=1_o=1_valid_beam
- webnlgprefixtune_y_5_act_cat_b=5-e=5_d=0.0_u=no_lr=5e-05_w=0.0_s=101_r=n_m=512_o=1_o=1_valid_beam_eval
- webnlgprefixtune_y_5_act_cat_b=5-e=5_d=0.0_u=no_lr=5e-05_w=0.0_s=101_r=n_m=512_o=1_o=1_valid_gold
- webnlgprefixtune_y_5_act_cat_b=5-e=5_d=0.0_u=no_lr=5e-05_w=0.0_s=101_r=n_m=512_o=1_o=1_valid_src

For ease of evaluation, these files have been renamed as follows:

- webnlgprefixtune_test_beam.txt
- webnlgprefixtune_test_beam_eval.txt
- webnlgprefixtune_test_gold.txt
- webnlgprefixtune_test_src.txt
- webnlgprefixtune_valid_beam.txt
- webnlgprefixtune_valid_beam_eval.txt
- webnlgprefixtune_valid_gold.txt
- webnlgprefixtune_valid_src.txt

These renamed files facilitate a smoother evaluation process.
