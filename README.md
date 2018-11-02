# <h1 align='center'>Instalação do Arch Linux (i3-gaps) - Parte 3</h1>

### "Observação: Todos os pacotes e configurações aqui postados são necessários para executar a instalação do I3-GAPS." ###

## 1° Passo: Baixar os arquivos da configuração: ##
```git clone https://github.com/jirrezdex/archlinux-i3.git```  

## 2° Passo: Acessar a pasta para iniciar a aplicação dos arquvios: ##
```cd archlinux-i3```  

## 3° Passo: Mover os arquivos do ~/.config/i3 e dar permissão: ##
```sudo rm -dR ~/.config/i3```  
```mv i3/ ~/.config```  
```chmod +x ~/.config/i3/basico.sh```  

## 4° Passo: Mover os arquivos do ~/.config/polybar e dar permissão: ##
```sudo rm -dR ~/.config/polybar```  
```mv polybar/ ~/.config```  
```chmod +x ~/.config/polybar/launch.sh```  

## 5° Passo: Mover os arquivos do ~/.config/dunst: ##
```sudo rm -dR ~/.config/dunst```  
```mv dunst/ ~/.config```  

## 6° Passo: Mover os arquivos do ~/.config/rofi: ##
```sudo rm -dR ~/.config/rofi```  
```mv rofi/ ~/.config```  
```mv .dex.rasi ~```  

## 7° Passo: Mover os arquivos do ~/.oh-my-zsh: ##
```sudo rm -dR ~/.oh-my-zsh```  
```mv .oh-my-zsh ~```  
```sudo rm -dR ~/.zshrc```  
```mv .zshrc ~/```  

## 8° Passo: Mover os arquivos do ~/Imagens: ##
```mkdir ~/Imagens```  
```sudo rm -dR ~/Imagens/W1.png```  
```mv W1.png ~/Imagens```  

## 9° Passo: Mover os arquivos do /etc/xdg/termite: ##
```sudo rm -dR /etc/xdg/termite```  
```sudo mv termite/ /etc/xdg/```

## 9° Passo: Mover os arquivos do /etc/xdg/termite: ##
```sudo rm -dR /etc/xdg/termite```  
```sudo mv termite/ /etc/xdg/```  

## 9° Passo: Mover os arquivos do /etc/xdg/termite: ##
```sudo rm -dR /etc/xdg/termite```  
```sudo mv termite/ /etc/xdg/```

## 10° Passo: Criar diretórios necessários: ##
```mkdir ~/Imagens/Screenshots```  
