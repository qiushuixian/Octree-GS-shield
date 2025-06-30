Octree遮挡
遮挡模块在scene/gaussian_model.py第580行的additional_mask函数
只能用于推理。所以需要关闭遮挡模块（注释scene/gaussian_model.py第431行和render.py第50行，正常进行一个场景的训练，然后取消注释，带着遮挡模块进行推理。
配环境：
git clone https://github.com/qiushuixian/Octree-GS-shield
cd Octree-GS-shield
chmod +x ./os.sh
./os.sh
conda activate e0

接下来参照Octree-GS训练及渲染

