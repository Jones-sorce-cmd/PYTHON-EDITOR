# PYTHON-EDITOR
while True:
    display.scroll('Hello, World!')
    display.show(Image.HEART)
    sleep(2000) 
    display.show(Image.SMILE)
    sleep(1000)
    display.show(Image.SAD)
    sleep(1000)
    display.show(Image.HAPPY)
    reading = accelerometer.get_x()
    if reading > 20:
        display.show("R")
    elif reading < -20:
        display.show("JONEs")
    else:
        display.show("NATHAN")
        
        This should, in theory make it show a seires of faces and then execute pre programed commandes beased on how fast the dipslay is going. If it going above 20 than it says Jones if it goes below 20 it says NATHAN
