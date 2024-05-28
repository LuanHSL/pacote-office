# Instalação do Pacote Office

## 1º PASSO
- Criar pasta "MS OFFICE SETUP" no diretório *C:*
 
## 2º PASSO
- Baixar <a href="https://drive.google.com/file/d/1dWZzeVsW4q1pvK7BoY2gnuXMVm70Qzqt/view?usp=drive_link" target="_blank">Link 1</a> <a href="https://drive.google.com/file/d/1pH3zHYffJCrR1m8rf1BH2EVAZVpP7tau/view?usp=drive_link" target="_blank">Link 2</a>
- Mover arquivos para pasta "MS OFFICE SETUP"
## 2.1º PASSO ALTERNATIVO
- Ir no site <a href="https://config.office.com/deploymentsettings" target="_blank">Office Customization Tool</a>
- Escolher arquitetura do computador (32 bits ou 64 bits)
- Escolher na seção *Office Suites* a opção **Office LTSC Professional Plus 2021 - Licença de Volume**
- Escolher na seção *Idioma* a opção **Corresponder com o Sistema Operacional**
- Clicar em *Exportar* e marque a opção **Formatos Office Open XML**
- Ir no site <a href="https://www.microsoft.com/en-us/download/details.aspx?id=49117" target="_blank">Office Deployment Tool</a>
- Clicar no botão **Download**
 
## 3º PASSO
- Abrir como **Administrador** o arquivo *officedeploymenttool_17531-20046.exe*
- Escolher a pasta "MS OFFICE SETUP"

## 4º PASSO
- Abrir cmd como **Administrador**
- Copiar comando
```
cd c:\"MS OFFICE SETUP"
```
- Rodar o seguinte comando dentro da pasta "MS OFFICE SETUP"
```
setup.exe/configure Configuration.xml
```
