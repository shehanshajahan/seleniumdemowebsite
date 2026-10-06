# seleniumdemowebsite(form_filling)
```py
from selenium import webdriver
from selenium.webdriver.common.by import By
import time

driver = webdriver.Chrome()
driver.maximize_window()

driver.get("https://vinothqaacademy.com/demo-site/")

time.sleep(5)

driver.find_element(By.ID, "vfb-5").send_keys("Shehan")
time.sleep(1)

driver.find_element(By.ID, "vfb-7").send_keys("Shajahan")
time.sleep(1)

driver.find_element(By.ID, "vfb-31-1").click()
time.sleep(1)

driver.find_element(
    By.XPATH,
    "//label[contains(.,'Selenium WebDriver')]"
).click()
time.sleep(1)

driver.find_element(By.ID, "vfb-20-4").click()
time.sleep(1)

driver.find_element(
    By.ID, "vfb-13-address"
).send_keys("Chennai City")
time.sleep(1)

driver.find_element(
    By.CSS_SELECTOR, ".select2-selection"
).click()

time.sleep(2)

driver.find_element(
    By.XPATH,
    "//li[normalize-space()='India']"
).click()

time.sleep(1)

driver.find_element(By.ID, "vfb-14").send_keys("shehan@gmail.com")
time.sleep(1)

driver.find_element(By.ID, "vfb-19").send_keys("7836659784")
time.sleep(1)

driver.find_element(
    By.ID,
    "vfb-23"
).send_keys("I am interested to learn automation testing!")

time.sleep(2)

input("Press ENTER to close the browser...")

driver.quit()
```
<img width="1122" height="477" alt="Screenshot 2026-10-06 115902" src="https://github.com/user-attachments/assets/c47dd63c-d19b-44cf-afb3-989e823c25ec" />
<img width="547" height="123" alt="Screenshot 2026-10-06 115919" src="https://github.com/user-attachments/assets/a86fbcd1-997b-442f-8e9e-58ff2d181df2" />
<img width="1077" height="323" alt="Screenshot 2026-10-06 115923" src="https://github.com/user-attachments/assets/4dc83229-33a2-4592-b416-08af2e081089" />



driver.quit()
