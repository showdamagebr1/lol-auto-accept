## lol-auto-accept

```
accept = 'template.png'
while 1:
    try:
        button7location = pyautogui.locateOnScreen(accept, confidence=0.9)
        print(f"MATCH FOUND: BOX[left={button7location[0]}, top={button7location[1]}, w={button7location[2]}, h={button7location[3]}]")
        pyautogui.click(button7location)
        time.sleep(2)
    except:
        pass
    time.sleep(1)
```
![template](https://github.com/showdamagebr1/lol-auto-accept/assets/158983772/87c8266d-7078-4f7b-a3fa-b64c2b30dfd5)
