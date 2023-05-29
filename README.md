# Prime-number-



class Prime {

    static boolean isPrime(int n) {

        if (n == 0 || n == 1) {

            return false;

        }

        if (n == 2) {

            return true;

        }

        for (int i = 2; i <= n / 2; i++) {

            if (n % i == 0) {

                return false;

            }

        }

        return true;

    }

    public static void main(String... args) {

        System.out.println(isPrime(8));

        System.out.println(isPrime(2));

    }

}

/*

false

true

 */

class Prime{

    static boolean isPrime(int n){

        for(int i=2;i<=n/2;i++){

            if(n%i==0){

                return false;

            }

        }

        return true;

    }

    public static void main(String... prime){

        Scanner sc=new Scanner(System.in);

        int g=sc.nextInt();

        System.out.println(isPrime(2));

    }

}

class Prime {

    static boolean isPrime(int n) {

        if (n == 0 || n == 1) {

            return false;

        }

        if (n == 2) {

            return true;

        }

        for (int i = 2; i <= n / 2; i++) {

            if (n % i == 0) {

                return false;

            }

        }

        return true;

    }

    public static void main(String... args) {

        while (true) {

            System.out.println("Enter the number of your choice: ");

            Scanner s = new Scanner(System.in);

            int n = s.nextInt();

            System.out.println(isPrime(n));

        }

    }

}
