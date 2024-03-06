# agi2neus
convert agisoft .xml format to which NeuS can use

1. export point cloud file in agisoft as sparse_points.ply in NeuS, export .xml file in agisoft.
2. run agi2neus.py to output pose.npy
3. run gen_cameras.py in NeuS to output cameras_sphere.npz
