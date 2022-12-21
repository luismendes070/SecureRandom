# SecureRandom

<code>

import java.security.SecureRandom;
import org.apache.commons.math3.complex.Complex;

public class ComplexRandom {
    // Secure random number generator
    private static final SecureRandom RANDOM = new SecureRandom();

    public static void main(String[] args) {
        // Generate a complex random number
        Complex complex = new Complex(RANDOM.nextDouble(), RANDOM.nextDouble() * 2 - 1);
        System.out.println(complex);
    }
}

</code>
