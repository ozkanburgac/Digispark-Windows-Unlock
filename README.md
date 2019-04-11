#include "DigiKeyboard.h"
void setup() {
  DigiKeyboard.sendKeyStroke(0);
  DigiKeyboard.println("bilgisayar şifresi");
  DigiKeyboard.delay(1000);
  DigiKeyboard.println("bilgisayar şifresi");
}
void loop() {
}
