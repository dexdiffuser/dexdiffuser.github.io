# Demonstration Videos for DexDiffuser

This folder contains demonstration videos showing DexDiffuser's performance on various dexterous manipulation tasks:

## Door Manipulation
- `1_door_open_30.mp4` to `5_door_open_110.mp4`: Goal-adaptive door opening to different angles (30°, 50°, 70°, 90°, 110°). Note that only 90° is in training distribution.
- `6_door_closing.mp4`: Goal-adaptive door closing demonstration.

## Pen Manipulation
- `7_pen_right_reorien_(in_domain).mp4`: In-domain pen re-orientation to right hemisphere.
- `8_pen_left_orien_(goal_adaptive).mp4`: Goal-adaptive pen re-orientation to left hemisphere, requiring large-arc rotation.
- `9_pen_dynamic_rotate_(goal_adaptive).mp4`: Novel dynamic goal tracking where target yaw angle rotates uniformly over time (not reported in main paper).

## Hammer Manipulation
- `10_hammer_full_nail_(in_domain).mp4`: In-domain full nail driving.
- `11_hammer_half_nail(goal_adaptive).mp4`: Goal-adaptive partial nail driving with controlled retraction.

## Block Manipulation
- `12_block_full_reorien_(in_domain).mp4`: In-domain block re-orientation with positive yaw.
- `13_block_half_reorien_(goal_adaptive).mp4`: Goal-adaptive block re-orientation with negative yaw, requiring quaternion-based multi-angle alignment.

Note: Videos demonstrate both in-domain performance and goal adaptation capabilities, with particular emphasis on challenging scenarios requiring large state changes or precise control.