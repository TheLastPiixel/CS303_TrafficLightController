# cs303-my-ass-1
CS303 Assignment 1

## Currently Working
* SOF File
* SOPCINFO File
* Mode 1
* Mode 2
* Mode 3
* Mode 4

## Instructions
* All switches 3 to 17 is to be **turned down at ALL times.**
* **MODE 2**: **KEY0** and **KEY1** to simulate pedestrian presses at traffic crossings at **NS and WE respectively.**
* **MODE 3**: Configurations can be accessed using **SW[2] to 1 only when in this mode** and the number represents **number of 100ms to increment**. Currently assessible to PuTTY.
* **MODE 4**: **KEY2** to simulate car entry (odd number of presses) and exit (even number of presses) on RY, YR and RR states.
* To set modes:

SW[0] = 0, SW[1] = 0 to access MODE 1.

SW[0] = 1, SW[1] = 0 to access MODE 2.

SW[0] = 0, SW[1] = 1 to access MODE 3.

SW[0] = 1, SW[1] = 1 to access MODE 4.

## Notes
* MODE 3 default values are [5,5,5,5,5,5].
* Configurations for **MODE 3** are **forced** to follow 1-4 number with 5 commas in the form `#,#,#,#,#,#` where # is any 1 to 4 digit number. If you accidently enter the wrong details, you will have to reset using **KEY3**.



