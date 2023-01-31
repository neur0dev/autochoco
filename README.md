# autochoco
Script de Instalação Automatizada de Aplicativos via Chocolatey

Este script é destinado a automatizar a instalação de vários aplicativos em um sistema Windows utilizando o gerenciador de pacotes Chocolatey. O script verifica se o Chocolatey está instalado e, se não estiver, o instala antes de instalar os aplicativos especificados.
Requisitos

* Sistema operacional Windows
* Acesso à Internet
* Git instalado

## Instruções de uso

1. Abra o PowerShell com privilégios de administrador.
2. Clone o repositório que contém o script e o arquivo de aplicativos no seu sistema, utilizando o seguinte comando:

```powershell
git clone https://github.com/lobocode/autochoco.git
cd autochoco
.\install-apps.ps1
```

O script irá verificar se o Chocolatey está instalado e, se não estiver, o instalará antes de instalar cada aplicativo especificado no arquivo `apps.txt`.



## Notas

* O script funciona somente em sistemas operacionais Windows.
* O script requer privilégios de administrador para executar corretamente.
* O arquivo apps.txt deve conter um nome de aplicativo por linha e estar no formato:

```powershell
gimp
inkscape
audacious
audacity
p7zip
vlc
shotcut
blender
```