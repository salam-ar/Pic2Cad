# Pic2Cad

Pipeline generates 3D reconstruction from single 2D image inputs. 

Monocoular Depth Estimation model is used to generate a depth map of input image. 

Gaussian smoothing filter is used before numpy transform to generate initial point cloud. 

Normal estimation and Poission surface reconstruction post-processing. 

.ply export 

Next steps: .stl export and improve masking/trimming capabilities to prevent skirts/cliff artifacts


VIDEO DEMO: 
