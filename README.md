# Superlink-GUI
User interface for Superlink Cryocooler
This program provides a serial interface for a Superconductor Technologies Superlink cryocooler, returning the cold finger temperature, rejection temperature, and power drawn. It also allows you to switch the cryocooler between auto and manual shutdown modes. I haven't used Python in ages, I'm sure there's goofs somewhere, if you find some, tell me!

To use the program, you'll need to have Python installed on your computer. Once you open the program, enter your serial port (eg. COM5) in the Com Port entry box, and click Start Serial. The program will attempt to connect to the Superlink. If it is successful, you should see cold stage wide range temperature, cooler rejection temperature, and power readings, along with the cooler's current state. To manually shut down the cryocooler, click the Toggle Mode button. To return the cryocooler to Automatic mode, click the toggle button again.
