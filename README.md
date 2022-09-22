# 111-1-師大科技系程式語言
授課教師： 蔡芸琤老師   
姓名   ： 林逸豪  
系級   ：科技系114級  
## 課程筆記區   
#### *week 2* 
     int   = 整數
     float = 浮點數
     str   = 字串
     bool  = 布林值
## 作業連結區  
#### *week 2* http://localhost:8888/notebooks/Desktop/習題.ipynb
              {
 "cells": [
  {
   "cell_type": "code",
   "execution_count": 2,
   "id": "02ebe0cd",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "被告要分擔的賠償金為 17981 元 ， 原告要分擔的賠償金為 7706 元\n"
     ]
    }
   ],
   "source": [
    "#題目一\n",
    "total = 25688\n",
    "被告 = int(total) *0.7 \n",
    "原告 = int(total) *0.3\n",
    "print (\"被告要分擔的賠償金為\", int(被告),\"元 ， 原告要分擔的賠償金為\", int(原告),\"元\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 5,
   "id": "ffa29199",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "總告要繳的金額為 12608 元\n"
     ]
    }
   ],
   "source": [
    "#題目二\n",
    "money = 11805\n",
    "days = 59\n",
    "rate = 0.0005\n",
    "利息 =money *(1+rate)**days\n",
    "違約金 = 150+300\n",
    "total = 利息+違約金\n",
    "print (\"總告要繳的金額為\", int(total),\"元\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 10,
   "id": "42e7a472",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "請輸入案件：被告原告皆闖紅燈\n",
      "原告50%被告50％\n"
     ]
    }
   ],
   "source": [
    "#題目三\n",
    "event =input(\"請輸入案件：\")\n",
    "\n",
    "if event == \"被告闖紅燈\" :\n",
    "    print (\"被告判賠100%\")\n",
    "elif event == \"原告闖紅燈\" :\n",
    "    print (\"原告多被告少\")\n",
    "elif event == \"被告原告皆闖紅燈\" :\n",
    "    print (\"原告50%被告50％\")\n",
    "else:\n",
    "    print (\"請填入有效訊息\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "34b60f4f",
   "metadata": {},
   "outputs": [],
   "source": []
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "58e646be",
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.9.12"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
## 專題連結區  
