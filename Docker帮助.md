docker compose up -d --build
docker start 容器名
docker stop 容器名
docker logs 容器名
docker stats

# 查看容器根目录
docker exec 容器名 ls -la /

# 复制文件夹到指定位置
docker cp 容器名:/app/data /home/user/backup/

# docker迁移数据库
docker exec -i mysql容器名 mysqldump -u root -p h_base > backup.sql







