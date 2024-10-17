### Parte 1: Blink Led Interno  
Segue duas imagens mostrando evidências da relaização do Blink com LED Interno do Arduino. Contendo, minha tela com o IDE, meu código e o arduino físico piscando.

* Imagem 1 -> Led builtin Ligado:

<div style="text-align: center;">
<img title="Led builtin Ligado" src="assets\ledBuiltInOn.jpg"  style="width: 70%;">
</div>

<br>

* Imagem 2 -> Led builtin Desligado:
<div style="text-align: center;">
<img title="Led builtin Desligado" src="assets\ledBuiltInOff.jpg"  style="width: 70%;">
</div>

<br>

### Parte 2: Simulando Blink Externo

Código executado no arduino do **TinkerCad**
```
// C++ code
//
void setup()
{
  pinMode(10, OUTPUT);
}

void loop()
{
  digitalWrite(10, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(10, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
}
```

link do projeto no ThinkCad: https://www.tinkercad.com/things/hzocOrJCmw9/editel
