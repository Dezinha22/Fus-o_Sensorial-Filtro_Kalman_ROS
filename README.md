# Fusao_Sensorial-Filtro_Kalman_ROS
Repositório com as steps necessárias a aplicação do filtro kalman a partir do input de dados provenientes do ambiente simulado do LaR - UFBA no gazebo e o clearpath husky.

## Configuração de Startup

### Pré-Requisitos de Sistemas

1 - Utilize a distribuição **Ubuntu 24.04 LTS**;
    
2 - Instale o **Docker 29.5.3**;

3 - Possua acesso aos navegadores **Google Chrome**, **Mozilla Firefox** ou similares.

### Pré-Requisitos de Arquivos

4 - Faça a transferência dos dados de simulação contidos no [(link do google drive)](https://drive.google.com/drive/folders/1lF4HExtL49w9botrIfjxp7nfLHgtEdTF?usp=drive_link).

5 - Faça a transferência do pacote ROS contido neste repositório.

### Primeiros Passos 

6 - Acesse o terminal (recomenda-se utilizar o _[terminator](https://gnome-terminator.org/)_);

7 - Localize os arquivos transferidos e reserve os seus respectivos endereços. Para localizá-los, pode utilizar o comando *find*, *locale*, *ls*, *pwd*, dentre outros. Consulte o [Tutorial A](https://www.hostinger.com/br/tutoriais/comandos-linux), [Tutorial B](https://info-ee.surrey.ac.uk/Teaching/Unix/index.html) ou similares para ter conhecimento de outros comandos e sua estrutura;

8 - Clone o repositório do lar_gazebo: _https://github.com/lar-deeufba/lar_gazebo?tab=readme-ov-file_ ;

9 - Localize o local onde o repositório foi clonado e acesse a pasta. Para isso, utilize os comandos *cd*, *find*, *locale*, *ls*, *pwd*, dentre outros (verifique o intem 7). Você deve chegar a algo similar a isso: 

    (base) matheus@matheus-VivoBook-ASUSLaptop-X512FBC-X512FBC:~$ cd
    (base) matheus@matheus-VivoBook-ASUSLaptop-X512FBC-X512FBC:~$ ls
    CoppeliaSim  google-chrome-stable_current_amd64.deb  Music      rosbags_env
    Desktop      lar_gazebo                              OpenPCDet  Templates
    Documents    miniconda3                              Pictures   Videos
    Downloads    Miniconda3-latest-Linux-x86_64.sh       Public
    (base) matheus@matheus-VivoBook-ASUSLaptop-X512FBC-X512FBC:~$ cd lar_gazebo/
    (base) matheus@matheus-VivoBook-ASUSLaptop-X512FBC-X512FBC:~/lar_gazebo$  

10 - Utilize o comando *ls* ou similar para verificar os arquivos contidos na pasta lar_gazebo e validar se a transferência do repositório foi satisfeita. A saída será similar a essa:

    (base) matheus@matheus-VivoBook-ASUSLaptop-X512FBC-X512FBC:~/lar_gazebo$ ls
    2026-06-16-00-36-58-001.bag  docker                LICENSE      README.md
    april_tags                   docker-compose.yml    maps         scripts
    CMakeLists.txt               husky_accessories.sh  models       worlds
    config                       husky_urdf_extras     Ola
    doc                          launch                package.xml

11 - 


    
     
