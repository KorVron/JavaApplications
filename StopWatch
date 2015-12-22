package <Your Package Name>;

/**
 * Author: KorVron
 * GitHub: https://github.com/KorVron/
 *
 * Constructor for a StopWatch.
 * Use it to pause your program for however many seconds/minutes you please.
 * 
 * Usage:
 *       Create object from constructor:
 *       StopWatch <Object Name> = new StopWatch();
 * 
 *       Invoke method waitTime();:
 *       waitTime(<Amount of Time>,<Object Name>.<Time Type: S/M,  S = Seconds, M =Minutes.>);
 * 
 *       Example, pauses the program for one second:
 *       StopWatch SW = new StopWatch();
 *       System.out.println("Waiting for one second...");
 *       waitTime(1,SW.S);
 *       System.out.println("Waited for one second!");
 **/
 
public class StopWatch {
    final String S = "seconds",  M = "minutes";
    void waitTime(int timeLength, String timeType) {
        try {
             if ("seconds".equals(timeType)) {
                 Thread.sleep(timeLength * 1000);
             } else if ("minutes".equals(timeType)) {
                 Thread.sleep((timeLength * 60) * 1000);
             }
        } catch(InterruptedException e) {
        }
    }
}

