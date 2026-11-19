FROM nginx/nginx-unprivileged@sha256:8432c57ac86f178741af2b89948bd9087cb9df1c415bc1ab4d23735c4f0e3e61
LABEL org.nddev.fixture="std0004-native-container"
COPY --chmod=0644 index.html /usr/share/nginx/html/index.html
USER 101:101
EXPOSE 8080
