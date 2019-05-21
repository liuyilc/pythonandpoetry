import  requests
from bs4 import BeautifulSoup
import re
import os
import time

url='https://www.nytimes.com/'
r=requests.get(url)
soup=BeautifulSoup(r.text,'html.parser')

fo=open('1.txt','ab+')
fo.write(soup.encode())
fo.close
