****❤#cara upload ke github pertama kali <br /><br />****
  ◾ echo "# basic-template-ktc" >> README.md  --> membuaat template README <br />
  ◾ git init --> membuat layanan git di folder yg mau di upload ke github <br />
  ◾ git add REAME.md --> membuat file README (kebiasaan di github) <br />
  ◾ git commit -m "commit pertama" --> membuat komentar di github bahwa melakukan upload <br />
  ◾ git branch -M main --> memilih branch yg akan di masukkan <br />
  ◾ git remote add origin https://github.com/dennydenkurniawan/Project-Kelas-Android-K.git --> memasukkan link repo github yg akan di upload <br />
  ◾ git push -u origin main --> mengupload file ke branch main <br />


****❤#cara upload ulang file baru ke github <br /><br />****
◾ git remote add origin https://github.com/dennydenkurniawan/Project-Kelas-Android-K.git <br />
◾ git commit -m "commit kedua" <br />
◾ git branch -M main <br /> 
◾ git push -u origin main <br />

****Mengatasi Error Saat debug project****
◾  Use:
    flutter build web --base-href="/base_href_path/"

    or just edit {project}/web/index.html:

    <base href="/web/">


# bmi_calculator_praktikum_k

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
