#  Cowsay Variants Project

This project is a playful collection of C programs and shell scripts that simulate different types of **cows** with unique personalities.  
It is inspired by the classic [cowsay](https://en.wikipedia.org/wiki/Cowsay) program, but extends the idea with multiple scenarios and behaviors.

---

## Project Structure

- `reading_cow.c` – A C program where the cow is reading.  
- `wild_cow.c` – A wild cow variant.  
- `tamagoshi cow.c` – A Tamagotchi-style interactive cow.  
- `newcow.c` – Another cow variant implementation.  
- `readingcowTxt` – Text resource used by the reading cow program.  
- `cow_primaryschool.sh` – Script to run a primary school cow.  
- `cow_highschool.sh` – Script to run a high school cow.  
- `cow_college.sh` – Script to run a college cow.  
- `cow_university.sh` – Script to run a university cow.  
- `smart_cow.sh` – Script for a “smart” cow.  
- `crazy_cow.sh` – Script for a “crazy” cow.  
- `exemple-reaadingcow.mov` – Example demo video.  
- `Commentaire sur chaque partie: .pdf` – Documentation with comments on each part.

---

## Compilation

Each C file can be compiled separately using `gcc`:

```bash
gcc reading_cow.c -o reading_cow
gcc wild_cow.c -o wild_cow
gcc "tamagoshi cow.c" -o tamagoshi_cow
gcc newcow.c -o newcow
```

This will generate the corresponding executables (`reading_cow`, `wild_cow`, `tamagoshi_cow`, `newcow`).

---

##  Usage

Run the compiled programs directly:

```bash
./reading_cow
./wild_cow
./tamagoshi_cow
./newcow
```

Or use one of the **scenario scripts**:

```bash
bash cow_primaryschool.sh
bash cow_highschool.sh
bash cow_college.sh
bash cow_university.sh
bash smart_cow.sh
bash crazy_cow.sh
```

---

## Notes

- The project was created as a fun programming exercise in C and Bash scripting.  
- Some scripts may depend on the compiled C executables.  
- See the included PDF (`Commentaire sur chaque partie: .pdf`) for detailed explanations.

---

## 🎥 Demo

Check `exemple-reaadingcow.mov` for a demo of the program in action.
