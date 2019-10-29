### Welcome to my page!!

This is something new. A test basically.

* [link to youtube](https://www.youtube.com)
* [link to github](https://www.github.com)
* [link to arduino](https://www.arduino.cc)

### Markdown

Arduino program to blink led and buzzer when button is pressed

```markdown
                    `// initializing buzzer, led and button to pin 1,2 and 3 respectively.`
int buzzer=1;    
int led=2;
int button=3;

setup()
{
  pinMode (buzzer , OUTPUT);        `// set buzzer as output`
  pinMode (led , OUTPUT);           `// set led as output`
  pinMode (button , INPUT);         `// set button as input`
}

loop()
{
  while(button)                     `// let both buzzer and led to blink with a interval of 0.5 seconds when the button is pressed`
  {                                               
    digitalWrite (buzzer , HIGH);                   
    digitalWrite (led , HIGH);
    delay (500);                    `// delay of 0.5 seconds`
    
   digitalWrite (buzzer , LOW);
   digitalWrite (led , LOW);
   delay (500);                    `// delay of 0.5 seconds`
  }

```

I shall write more programs if and when possible


