# PythonProjects
# My projects using python language.
import pyautogui #biblioteca externa de automação
import time 

# Abrir o menu iniciar do Win10
pyautogui.PAUSE = 1

pyautogui.press('winleft')
pyautogui.PAUSE = 1

pyautogui.write('Chrome')
pyautogui.press('enter')
time.sleep(1)

#abrir o whatsapp

pyautogui.write('https://web.whatsapp.com/')
pyautogui.press('enter')
time.sleep(3)

# abrir o spotify

pyautogui.press('winleft')
pyautogui.PAUSE = 1
pyautogui.write('spotify')
pyautogui.press('enter')
time.sleep(1)

# abrir o Discord

pyautogui.press('winleft')
pyautogui.PAUSE = 1
pyautogui.write('Discord')
pyautogui.press('enter')
time.sleep(1)

pyautogui.alert('OK! Programa executado com sucesso.'
                '\n Qualquer problema entre em contato com o suporte.'
                '\n by, Hércullys.')
