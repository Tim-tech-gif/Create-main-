# Create-main-
fn is_prime(n: u32) -> bool {     if n &lt; 2 {         return false;     }     for i in 2..=((n as f64).sqrt() as u32) {         if n % i == 0 {             return false;         }     }     true
