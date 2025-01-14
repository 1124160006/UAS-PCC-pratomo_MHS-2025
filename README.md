# UAS-PCC-pratomo_MHS-2025
Repository untuk UAS mata kuliah PCC tahun 2025

Nama : Pratomo Putranto
Nim : 1124160006
Deskiripsi Singkat : Design menggunakan Github dan penyertanya , menarik , Interactive dan Keren :-)
bagaimana cara untuk :-( : 
-Jika perubahan dirasa sudah sesuai dengan instruksi diatas, lakukan merge ke branch main
Nama docker image ketika build sama dengan nama repository UAS-PCC-Nama_MHS-2025,

- Ubah dan sesuaikan tag, repository, secrets pada file actions-workflow.yml sesuai repo masing-masing
docker build -t dockerhub_username/image_name:latest -f Dockerfile .
docker login -u ${{secrets.dockerhub_username}} -p ${{secrets.dockerhub_AccessToken}} && docker push dockerhub_username/image_name:latest
- Jika semua persiapan sudah selesai, silahkan push ke repository masing-masing
git add .
git commit -m "commit message"
git push origin main

