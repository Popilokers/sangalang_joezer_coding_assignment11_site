## How to run the app locally

all in terminal

1. Get the files:

git clone https://github.com/Popilokers/sangalang_joezer_coding_assignment11_site.git

2. Build the image:

cd sangalang_joezer_site

docker build -t sangalang_joezer_site .

3. Run the container(localhost-only)

docker run -p 7775:7775 sangalang_joezer_site

 it will give a local(http://localhost:7775) and network host(http://172.17.0.2:7775/)
only localhost works
 network host gets connection error
