![map](https://user-images.githubusercontent.com/29266933/44430997-25f80c00-a5a5-11e8-9aef-aa1ed0c943d6.jpg)

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
