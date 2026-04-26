# Motivational Car Quotes Repository

---

## Features
- Car-themed motivational quotes
- Java example program
- Clean repository structure
- Git branching and merge practice

---

## Text Formatting Examples

This is **bold text**  
This is *italic text*  
This is <u>underlined text</u>

---

## Image

![Car Image](https://images.unsplash.com/photo-1503376780353-7e6692767b70)

---

## Link

https://www.motortrend.com/

---


```java
import java.util.Random;

public class Main {
    public static void main(String[] args) {

        String[] quotes = {
            "Drive your ambition further than your fears.",
            "Speed is nothing without control.",
            "Success is built mile by mile.",
            "Discipline drives faster than motivation."
        };

        Random random = new Random();
        int index = random.nextInt(quotes.length);

        System.out.println("Motivational Quote:");
        System.out.println(quotes[index]);
    }
}

---


1. Go to your repo
2. Click the dropdown that says `main`
3. Type:
4. Click **Create branch**

---


1. Open `README.md`
2. Click edit
3. Add this line under the quotes section:

4. Click **Commit changes**

---

1. Go to **Pull Requests**
2. Click **New Pull Request**
3. Compare:
   - base: `main`
   - compare: `feature-quotes`
4. Click **Create Pull Request**
5. Click **Merge Pull Request**
6. Confirm merge

---

