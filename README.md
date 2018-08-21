![Devre](https://raw.githubusercontent.com/alknbugra/Arduino-I2C-LCD-SCREEN/map.jpg)

#include <Wire.h> 

#include <LiquidCrystal_I2C.h>


LiquidCrystal_I2C lcd(0x27, 16, 2);

void setup()
{

  lcd.begin();
  
  lcd.backlight();
  
  lcd.clear();
  
  lcd.setCursor(1,0);
  
  lcd.print("GitHub");
  
  lcd.setCursor(0,1);
  
  lcd.print("Bugra Alkin");
  
}


void loop()
{

}
