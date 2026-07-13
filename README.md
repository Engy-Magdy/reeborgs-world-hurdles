# Reeborg's World - Hurdles Challenge 🤖➡️🏁

My journey solving the Hurdles in Reeborg's World with Python!  
Building from simple to general, one hurdle at a time 🧱➡️🏆

### Project Progression

**hurdle1.py - Single Hurdle** 1️⃣  
**What I learned:** Created `turn_right()` function 🔄  
Used a `for` loop 🔂 because the number of hurdles was fixed.

**hurdle2.py - Multiple Hurdles** ♾️  
**What I learned:** Switched to `while not at_goal()` ➡️🏁 to handle unknown number of hurdles.  
Repeated the same jump pattern on each loop 🔁

**hurdle3.py - Add Decision Making** 🤔  
**What I learned:** Built on Hurdle 2.  
Added `if front_is_clear()` 👀 inside the while loop.  
Move forward ➡️ if clear, else jump 🦘

**hurdle4.py - The General Solution** 🌍✅  
**What I learned:** Combined everything from before 🧩  
Added `while wall_on_right()` 🧱 in the `moves()` function because hurdle height is unknown 📏❓  
This is the final algorithm that works for any hurdle world 🌍➡️🏁

### Key Takeaways ✨
- **Functions**: `turn_right()` 🔄, `moves()` 🦘 to avoid repeating code
- **Loops**: `for` 🔂 → `while` 🔁 → `while + if` 🤔  
- **Sensors**: `wall_on_right()` 🧱 to handle unknown environments
- **Growth**: From specific case 1️⃣ to general solution 🌍
