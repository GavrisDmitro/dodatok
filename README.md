# dodatok
Це чат який може відправляти повідомлення, зображення та зробити собі нікнейм.
Чат зроблений на мові програмування Python.
При стоворенні я надихався чатами Telegram, Discord.
##Пояснення коду.
import base64
import io
import threading
from socket import socket, AF_INET, SOCK_STREAM
from textwrap import shorten

from customtkinter import *
from tkinter import filedialog
from PIL import Image
Цей фрагмент кода додає бібліотеки.Base64-це спосіб перетворення будь-яких бінарних даних (картинок, файлів, аудіо) у текстовий формат.io-це стандартний інструмент для роботи з потоками даних.threading-озволяє виконувати кілька частин програми одночасно.

