![map](https://user-images.githubusercontent.com/29266933/44431504-cc90dc80-a5a6-11e8-90c8-e3eb6609a40d.jpg)

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
