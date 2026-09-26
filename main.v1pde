PFont comicFont; 

fill(152, 158, 161); 
rect(360, 0, 140, 400); 

comicFont = createFont("Comic Sans MS", 32); 
textFont(comicFont); 

fill(0); 
textSize(25); 
text("   LifeSim", 365, 55); 

fill(152, 158, 161); 
rect(0, 0, 80, 70);

String generateEntityName() {
  String[] consonants = { 
    "b", "c", "d", "f", "g", "h", "j", "k", "l", "m", "n", 
    "p", "r", "s", "t", "v", "w", "z", "bl", "st", "str", "fl" 
  };
  String[] vowels = { 
    "a", "e", "i", "o", "u", "ee", "oo", "ai", "ay" 
  };

  int numSyllables = int(random(2, 5)); 
  String name = "";

  for (int i = 0; i < numSyllables; i++) {
    int cIndex = int(random(consonants.length));
    int vIndex = int(random(vowels.length));
    
    name += consonants[cIndex];
    name += vowels[vIndex];
  }

  // Capitalize the first letter if the name is not empty
  if (name.length() > 0) {
    name = name.substring(0, 1).toUpperCase() + name.substring(1);
  }

  return name;
}

void showName(String name) { 
  textSize(20); 
  text(name, 375, 105); 
} 

void showInfo(int BirthWeight, int Weight, int Sex, int Age, int Children, int Gen) { 
  textSize(10); 
  fill(0);
  text("Birth Weight: " + BirthWeight, 375, 130); 
  text("Current Weight: " + Weight, 375, 150);
  text("Sex: " + Sex, 375, 170); 
  text("Age: " + Age, 375, 190);
  text("Children: " + Children, 375, 210); 
  text("Gen: " + Gen, 375, 230);
}

void footerText(int Day, int Hour, int Min) {
   text("Day " + Day + " at " + Hour + ":" + Min, 365, 390); 
}

void worldText(int carni, int omni, int herbo, int sick, int plants) {
    text("Carnivores: " + carni, 375, 270);
    text("Onmivores: " + omni, 375, 290);
    text("Herbivores: " + herbo, 375, 310); 
    text("Sick: " + sick, 375, 330); 
    text("Plants: " + plants, 375, 350); 
}

void info(int health, int hunger, int sleepy, int naughty) {
    text("Health: " + health, 10, 20);
    text("Hunger: " + hunger, 10, 32);
    text("Sleepy: " + sleepy, 10, 43);
    text("Naughty: " + naughty, 10, 55);
}

//--------------------
showInfo(0, 0, 0);
footerText(12, 12, 50);
worldText(0, 0, 0, 0, 3432432);
info(100, 100, 100, 10);
//---------------------

textSize(10);
text("    _________________", 365, 250)
text("Made by Bemnet, 2026", 365, 375)

//---------------------

showName(generateEntityName());
