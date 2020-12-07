# ForLoopInterestRateExercise
package academy.learnprogrmming;

public class Main {


    public static void main(String[] args) {

        for(int i = 2; i<8; i++) {
            System.out.println("10,000 at " + i + " % interest " + calculateInterest(10000,i));
        }

    }




    public static double calculateInterest(double amount, double interestRate){
        return(amount * (interestRate /100));
    }

}
"C:\Program Files\Java\jdk-15.0.1\bin\java.exe" "-javaagent:C:\Users\nadiy\OneDrive\Desktop\IntelliJ IDEA Community Edition 2020.2.3\lib\idea_rt.jar=50136:C:\Users\nadiy\OneDrive\Desktop\IntelliJ IDEA Community Edition 2020.2.3\bin" -Dfile.encoding=UTF-8 -classpath C:\Users\nadiy\IdeaProjects\AreaCalculatorExercise\out\production\AreaCalculatorExercise academy.learnprogrmming.Main
10,000 at 2 % interest 200.0
10,000 at 3 % interest 300.0
10,000 at 4 % interest 400.0
10,000 at 5 % interest 500.0
10,000 at 6 % interest 600.0
10,000 at 7 % interest 700.0000000000001

Process finished with exit code 0
