from selenium import webdriver
from selenium.webdriver.chrome.service import Service
from selenium.webdriver.common.by import By

serv_obj=Service("G:\python chromium\chromedriver.exe")
driver=webdriver.Chrome(service=serv_obj) 
driver.minimize_window()

driver.get("https://coinmarketcap.com/")

price = driver.find_element(By.XPATH,"/html[1]/body[1]/div[1]/div[1]/div[1]/div[2]/div[1]/div[1]/div[5]/table[1]/tbody[1]/tr[2]/td[4]/div[1]/a[1]/span[1]").text

print("the current price is : " ,price)
