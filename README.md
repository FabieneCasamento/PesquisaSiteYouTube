# PesquisaSiteYouTube
Pesquisa de um tema no site YouTube, através de um arquivo em .csv, que pode ser visualizados no excel. Consequentemente, se tem como resposta vários links sobre o tema, contendo inclusive aulas, contidos dentro do site do youtube.

O programa para utilizar é o Pesquisa_site_2.ipynb 

Utilizando as bibliotecas Selenium e Webdriver_manager, com o arquivo chromedriver dentro do anaconda3.  

https://chromedriver.chromium.org/downloads
https://googlechromelabs.github.io/chrome-for-testing/

## instalando as bibliotecas

#!pip install selenium
#!pip install webdriver_manager

# mais dicas de utilização do programa

Utilizando o Tkinter para obter arquivos dentro do computador para analisar e buscar no site de interesse os resultados da pesquisa.


from tkinter import *
import tkinter.filedialog
from tkinter import messagebox

tkinter.filedialog.askopenfilename(title = 'mensagem')

avisando ao cliente que o resultado foi feito

abaixo segue a mensagem no computador.

janela = Tk()

messagebox.showinfo('mensagem' )
janela.destroy()

sempre abrir e fechar (destroy) o comando tkinter. 



para criar um executável no seu computador .exe

transformar o arquivo para .py

usando o comando:
ipynb-py-convert Pesquisa_site_2.ipynb Pesquisa_site_2_convertendo.py



Para não ficar pesado o programa, instale em um ambine virtual e instalei o seguinte programa:
pip install auto-py-to-exe


no terminal, o comando para converter o programa para .exe:

auto-py-to-exe


#colocar o chromedriver que esta nesta pasta  anaconda3
script locacion o arquivo em .py 

onefile
ondirecty

console windows
console based

advanced
debug
imports
#clico em converter







 

