import board
import neopixel
import time
 
pixel_pin = board.D2   #the ring data is connected to this pin
num_pixels = 12        #number of leds pixels on the ring
 
pixels = neopixel.NeoPixel(pixel_pin, num_pixels, brightness=0.3, auto_write=False)
 
RED = (255, 0, 0) #RGB
YELLOW = (255, 150, 0)
MINT = (0, 225, 5)
CYAN = (0, 202, 19)
BLUE = (90, 206, 232)
PURPLE = (100, 35, 255)
RASPERRY = (217, 33, 103)
OFF = (0,0,0)
 
while True:
    pixels[0] = RED
    pixels.show()     #required to update pixels
    time.sleep(1)
    
    pixels[1] = YELLOW
    pixels.show()
    time.sleep(1)
    
    pixels[2] = MINT
    pixels.show()
    time.sleep(1)
    
    pixels[3] = CYAN
    pixels.show()
    time.sleep(1)
    
    pixels[4] = BLUE
    pixels.show()
    time.sleep(1)
    
    pixels[5] = PURPLE
    pixels.show()
    time.sleep(1)
    
    pixels[6] = RASPERRY
    pixels.show()
    time.sleep(1)
    
    pixels[7] = RED
    pixels.show()    
    time.sleep(1)
    
    pixels[8] = YELLOW
    pixels.show()
    time.sleep(1)
    
    pixels[9] = MINT
    pixels.show()
    time.sleep(1)
    
    pixels[10] = CYAN
    pixels.show()
    time.sleep(1)
    
    pixels[11] = BLUE
    pixels.show()
    time.sleep(1)
    
    pixels[11] = OFF
    pixels.show()
    time.sleep
    
    pixels[10] = OFF
    pixels.show()
    time.sleep
    
    pixels[9] = OFF
    pixels.show()
    time.sleep
    
    pixels[8] = OFF
    pixels.show()
    time.sleep
    
    pixels[7] = OFF
    pixels.show()
    time.sleep
    
    pixels[6] = OFF
    pixels.show()
    time.sleep
    
    pixels[5] = OFF
    pixels.show()
    time.sleep
    
    pixels[4] = OFF
    pixels.show()
    time.sleep
    
    pixels[3] = OFF
    pixels.show()
    time.sleep
    
    pixels[2] = OFF
    pixels.show()
    time.sleep
    
    pixels[1] = OFF
    pixels.show()
    time.sleep
    
    pixels[0] = OFF
    pixels.show()
    time.sleep
    
    pixels[12] = OFF
    pixels.show()
    time.sleep
