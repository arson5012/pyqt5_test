# pyqt5_test
다양한 인식알고리즘을 통합

#설치모듈
--------------------설치 모듈-------------------

import 모듈


from PyQt5.QtCore import *
from PyQt5.QtGui import *
from PyQt5.QtWidgets import * //ptqt5 
from threading import Thread //처리 속도 및 충돌 방지를 위한 멀티스레딩
import speech_recognition as sr // STT
from gtts import gTTS //TTS
import cv2 //opencv
import time
from pyfirmata import Arduino, util//아두이노와 시리얼 통신
import sys
import numpy as np//연산
from os import listdir
from os.path import isfile, join
from PIL import Image
import pytesseract//OCR을 위한 테서렉트
import os
import cvlib as cv//물체 인식
from cvlib.object_detection import draw_bbox//물체 인식
import pyautogui//메세지 박스 간단 생성
import ctypes//메세지 박스 간단 생성

#실행 방법

1.설치 모듈을 설치한다

2. 오픈xml파일에 있는 인식 알고리즘을 파이썬 파일에 붙혀넣는다

3.사진찍기.py 파일을 실행하여 세이브데이터에 자신의 얼굴 사진을 저장한다

4.메인과 비디오 그리고, xml이 한 파일에 있다 가정하에 메인 파일을 실행한다


