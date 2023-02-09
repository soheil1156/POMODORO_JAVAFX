# POMODORO_JAVAFX
This code is a JavaFX application that implements a Pomodoro Timer. The Pomodoro technique is a time management method used to increase productivity. The code uses a TimerTask to update the current state of the Pomodoro timer based on the current time. The current state can be one of five states: LONG REST, PAUSE, POMODORO, SHORT REST, and FREE WORKING.
![POMODORO2](https://user-images.githubusercontent.com/24310606/217893590-dd2d963b-710f-470e-914f-6f492ffb7815.gif)
The code also includes methods for each state: longrestFunc(), pauseFunc(), pomodoroFunc(), shortrestFunc(), and freeworkFunc(). For example, the pomodoroFunc() method is executed when the state is set to POMODORO. In this method, the remaining time of the current POMODORO state is calculated and displayed on the timer. The code also includes some media player functionality, but it's commented out.
