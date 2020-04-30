# Octopus源码解析
 
## octopus的参数

num：图片数
img_size:图片大小
imputs:images，Js,posetrans_init
poses:
ts:
image_features:
dense_merged:
betas:shape的参数
faces:
offsets:
vertices:
vertices_tposed:
laplacian:
symmetry
Js
face_kps
repr_loss
rendered

## octopus的三个模型

### inference_model

输入：self.inputs
输出：
* self.vertices_tposed
* self.vertices
* self.betas
* self.offsets
* self.poses
* self.ts

### op_pose_model

输入：self.inpus

输出：self.Js

### op_shape_model

输入：self.inputs
输出：
* self.Js
* self.face_kps
* self.rendered
* self.symmetry
* self.laplacian










