# dodatok
Це чат який може відправляти повідомлення, зображення та зробити собі нікнейм.
Чат зроблений на мові програмування Python.
При стоворенні я надихався чатами Telegram, Discord.
## Пояснення коду
import base64
import io
import threading
from socket import socket, AF_INET, SOCK_STREAM
from textwrap import shorten

from customtkinter import *
from tkinter import filedialog
from PIL import Image

Цей фрагмент кода додає бібліотеки.Base64-це спосіб перетворення будь-яких бінарних даних (картинок, файлів, аудіо) у текстовий формат.io-це стандартний інструмент для роботи з потоками даних.threading-озволяє виконувати кілька частин програми одночасно.AF_INET та SOCK_STREAM — це константи, що використовуються при створенні сокетів для налаштування мережевої взаємодії.CustomTkinter — це бібліотека Python для створення сучасних графічних інтерфейсів (GUI), побудована поверх стандартного Tkinter.Tkinter — це стандартна бібліотека (модуль) у Python для створення графічного інтерфейсу користувача.(GUI — Graphical User Interface).PIL (Python Imaging Library) — це бібліотека з відкритим сирцевим кодом для мови програмування Python, призначена для обробки растрової графіки.

class MainWindow(CTk)

Це загальне вікно та в всередині написано як воно буде виглядати.

