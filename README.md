## How to run the app locally

1. Build the image:

```bash
docker build -t sangalang_joezer_site_image .

2. Run the container(localhost-only)

docker run -p 127.0.0.1:7775:7775 sangalang_joezer_site_image

#it will give a local(http://localhost:7775) and network host(http://172.17.0.2:7775/)
#only localhost works
#network host gets connection error
