### Original marker (with origin in centre of mass)
Naming scheme: val_<object_name>.vsk

# pelvis_val.vsk
- pelvis marker

# val_palm_left.vsk
- marker on left hand palm with shortened M3 threads

# val_palm_left_deprecated.vsk
- deprecated markers on left palm with slightly too long M3 threads


### Transformed marker with origin at attached robot frame origin
Naming scheme: val_frame_<frame_name>.vsk

# val_frame_leftPalm.vsk
- like "val_palm_left.vsk" but with markers transformed such that origin matches the "leftPalm" of Valkyrie

# val_frame_pelvis.vsk
- like "pelvis_val.vsk", but with transformation such that origin matches with "pelvis" frame
