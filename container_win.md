(arquivo container_win.md  )

# Tutorial: Execução de Container Windows usando Docker

Neste tutorial, você aprenderá como executar um container Windows usando o Docker no Windows.

## Pré-requisitos
 
- Windows 10 ou superior com o Docker instalado.

## Passo a Passo

1. Abra o PowerShell ou o terminal do Windows.

2. Verifique se o Docker está em execução:

   ```bash

   docker --version


(wsl_win.md)

**Tutorial 2: Executando Comandos Linux com WSL**

Arquivo: `wsl_win.md`

```markdown

# Tutorial: Executando Comandos Linux com WSL no Windows
 
Neste tutorial, você aprenderá como executar comandos Linux utilizando o Windows Subsystem for Linux (WSL).

## Passo 1: Instalação do WSL

Se você ainda não tem o WSL instalado, siga as instruções em https://docs.microsoft.com/pt-br/windows/wsl/install para habilitar o WSL no seu sistema.

## Passo 2: Configurando uma Distribuição Linux

1. Abra o Visual Studio Code.

2. Crie uma pasta para o seu projeto, se ainda não tiver feito isso, e navegue até ela usando o terminal integrado do VS Code.

## Passo 3: Executando Comandos Linux

1. Abra o terminal integrado do VS Code.

2. Execute o seguinte comando para iniciar sua distribuição WSL (por exemplo, Ubuntu):


```bash

wsl

Instalar o WSL

Instale o Subsistema do Windows para Linux com o comando wsl --install. Use um terminal Bash em seu computador Windows executado pela distribuição do Linux de sua preferência: Ubuntu, Debian, SUSE,...