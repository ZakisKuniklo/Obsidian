### Sobre
Essa é uma aula prática de automação.
O programa em python importará as informações de um arquivo CSV e fará a automação do cadastro de produtos de uma empresa.
Usará a biblioteca PyAutoGUI.
https://pyautogui.readthedocs.io/en/latest/

### Alguns métodos
A biblioteca PyautoGUI usa alguns métodos como:
```
import pyautogui
pyautogui.click - clique com o mouse
pyautogui.write - escrita
pyautogui.press - apertar 1 tecla
pyautogui.hotkey("x","y") - tecla de função
pyautogui.scroll - rolar a tela
time.sleep(tempo) - pausa por certo tempo
```

## Importar dados
Revisei também como importar dados com o pandas:
```
tabela = pd.read_csv(path)
```

## Caminho do arquivo
Também tem essa forma de descobrir o caminho com a biblioteca **pathlib**
```
from pathlib import Path
PROJECT_DIR = Path(__file__).parent
path = PROJECT_DIR / 'nome do arquivo'
```
