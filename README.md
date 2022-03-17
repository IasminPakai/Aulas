# Aulas
## EXERCÍCIO 1
![](https://github.com/IasminPakai/Aulas/blob/main/ex1.jpg)

## EXERCÍCIO 2
![](https://github.com/IasminPakai/Aulas/blob/main/ex2.jpg)
void setup()
{
  pinMode(2, OUTPUT);
  pinMode(3, OUTPUT);
}

void loop()
{
  digitalWrite(2, HIGH);
  delay(1000); 
  digitalWrite(2, LOW);
  delay(1000);
  
  digitalWrite(3, HIGH);
  delay(1000); 
  digitalWrite(3, LOW);
  delay(1000);
}
