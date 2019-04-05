# color_seed_demo
 This script produces a deterministic color field
 
 That is, it will seed a random.Random instance with a fixed value, and produce a series of 24 bit RGB colored ansi blocks on the terminal, demonstrating the deterministic nature (if so configured/desired) of pseudo random number generators.  This visualization can greatly aid in the understand of procedural generation methods.
 
 Two screenshots are included, one from a native Linux terminal, one from PuTTY on Windows, showing the exact same colors.
 
 If you pass an argument to the script, it will use this as the random number seed rather than the default, and it will render the same on different machines.
