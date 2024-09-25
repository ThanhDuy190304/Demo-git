# Sử dụng Nginx để serve các file HTML tĩnh
FROM nginx:alpine

# Copy toàn bộ nội dung trang web vào thư mục Nginx
COPY . /usr/share/nginx/html

# Expose port 80 để Nginx chạy
EXPOSE 80
