# MochaMatcher
MochaMatcher is a command line interface program intended to figure out who is going to pay for coffee (and subsequently who owes what) in a fair, orderly way. MochaMatcher alternates between all coworkers entered in order for everyone to pay a fair price.
# Assumptions
This program has 3 main assumptions:
1. Working week is only 5 days long (Monday-Friday)
 If the work week was assumed to be 7 days long, then one could say you could just set each coworker to be assigned to a specific day of coffee, however this is unrealistic as most working weeks are only 5-6 days long.
2. Every coworker orders the same item each day (However the program can be reset to accommodate different orders)
3. The amount of co-workers does not change (However the program can be reset to accommodate more or less co-workers than originally starting with.)
# Running MochaMatcher
After downloading the release file for your operating system, simply unzip the archive, and navigate to the unzipped archive directory in your terminal of choice.
Usage:
./MochaMatcher (-r)
-r (optional flag to reset the program’s data to start fresh, add or remove co-workers, and change prices of purchased items)

Keep in mind, I currently do not have access to alternate computer environments to test compatibility, so if the program does not run on your computer, please refer to the below section to build MochaMatcher for your environment. All the necessary data MochaMatcher needs to calculate who should pay for coffee is collected using terminal inputs during runtime.
# Building MochaMatcher from Source Code
If you would like to build MochaMatcher from its source code to run on your operating system, simply use g++ with MochaMatcher.cpp to compile the code in your computer environment. Then run ./a.out in your terminal (or cygwin/preferred windows terminal tool).
