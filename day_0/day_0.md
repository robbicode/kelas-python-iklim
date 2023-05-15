# python-data-iklim
## Menginstall Conda dan IDE⚙️
### Instalasi IDE📟
>Kita akan menggunakan **Visual Studio Code (VSCode)**.
1. Installer bisa didownload di [sini](https://code.visualstudio.com/Download)
2. Instal seperti program biasa
3. Jika muncul ini, centang semua:

![vscode](https://ashutoshtripathicom.files.wordpress.com/2021/04/image-19.png)

### Instalasi Conda🐛
>Kita akan menggunakan **Miniconda**.
1. Installer bisa didownload di [sini](https://docs.conda.io/en/latest/miniconda.html)
2. Instal seperti program biasa
3. Jika muncul ini, centang semua:

![miniconda](https://i.stack.imgur.com/WogNs.jpg)

4. Beberapa command conda:
> * `conda --version` --> versi conda
> * `conda env list` --> list virtual environment yang ada
> * `conda list` --> melihat module yang terinstall
> * `conda update -n base conda` --> update conda
> * `conda create --name myenv` --> membuat virtual environment bernama `myenv`
> * `conda activate myenv` --> mengaktifkan virtual environment `myenv` 
> * `conda deactivate` --> mengonaktifkan virtual environment `myenv`
> * `conda env remove --name myenv` --> menghapus virtual environment `myenv`
> * `conda install packages-name` --> menginstall module `packages-name`
> * `conda update packages-name` --> update module `packages-name`
> * `conda remove -n myenv scipy` --> menghapus module `scipy` di `myenv`

>**Note:** Jika terjadi error coba ketik `conda init` di terminal atau ikuti [link](https://answers.microsoft.com/en-us/windows/forum/all/whats-wrong-with-my-windows-powershell/f05e72f2-a429-4ee0-81fb-910c8c8a1306) ini
