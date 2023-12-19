#换成自己的仓库地址
git clone https://github.com/mannysys/my-pixie-images
cd my-pixie-images
mkdir -p ghcr.io/pixie-io/cloud-vzmgr_server_image-0.1.7/
echo "FROM ghcr.io/pixie-io/cloud-vzmgr_server_image:0.1.7" > ghcr.io/pixie-io/cloud-vzmgr_server_image-0.1.7/Dockerfile
git add .
git commit -m 'new image: ghcr.io/pixie-io/cloud-vzmgr_server_image:0.1.7'
# 默认分支可能是main，取决于你的github设置
git push origin main
