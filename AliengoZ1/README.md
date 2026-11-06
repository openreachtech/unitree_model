# AliengoZ1

Aliengo quadruped with the Z1 arm and the Unitree gripper, as a single URDF.

Generated from [unitree_ros](https://github.com/unitreerobotics/unitree_ros)
(`aliengo_description` + `z1_description`, mounted as in `aliengoZ1_description`) by
`scripts/tools/build_quadruped_z1_urdf.py` in unitree_rl_lab:

```bash
python scripts/tools/build_quadruped_z1_urdf.py --base aliengo --out-dir <unitree_model>/AliengoZ1/urdf
```

Do not edit `urdf/aliengo_z1.urdf` by hand; change the script and regenerate.
No USD is committed: Isaac Lab converts the URDF at launch (`UrdfFileCfg`).
