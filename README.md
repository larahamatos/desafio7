# desafio7

# questao1
```java
        int n;
        Scanner ler = new Scanner (System.in);
        System.out.println("Informe um valor: ");
        n = ler.nextInt();
        executar (n);
    }
    public static void executar (int x){    
        int y, calculo;
        y = 0;
        while ( y <= 10 ) {
            calculo = y*x;
            System.out.println(y+"x"+x+"="+calculo);
            y++;
```
# questao2
```java
        Scanner ler = new Scanner (System.in);
        System.out.println("Informe o 1º número: ");
        int numero1 = ler.nextInt();
        System.out.println("Informe o 2º número: ");
        int numero2 = ler.nextInt();
        
        mostrarMaior ( numero1, numero2 );
    }
    public static void mostrarMaior(int n1, int n2) {
        String resp = "Maior valor \n";
                if ( n1 > n2 ) {
                    resp = resp+ "O maoior valor é: "+n1;
                } else { 
                    resp = resp+ "O maior valor é: "+n2;
                }
                System.out.println(resp);
```
# questao3
```java
        Scanner ler = new Scanner(System.in);
        String nome1, nome2;
        System.out.println("Digite o 1º nome: ");
        nome1 = ler.next();
        System.out.println("Digite o 2º nome: ");
        nome2 = ler.next();
        System.out.println(comparador (nome1, nome2));

    }

    public static String comparador(String v1, String v2) {
        String resp = "Resultado \n";
        if (v1.equals(v2)) {
            resp = resp + "Os nomes são iguais!";
        } else {
            resp = resp + "Os nomes NÃO são iguais!";
        }
        return resp;
```
# questao4
```java
        int numero1, numero2;
        Scanner ler = new Scanner (System.in);
      
        System.out.println("Digite o 1º número: ");
        numero1 = ler.nextInt();
        System.out.println("Digite o 2º número: ");
        numero2 = ler.nextInt();
        NumerosInteiros(numero1, numero2);
        
    }
    public static void NumerosInteiros ( int n1, int n2 ) {
        String resp = "Menor valor \n";
        if ( n1 < n2 ) {
            resp = resp+"O número "+n1+" é o menor";
        } else {
            resp = resp+"O número "+n2+" é o menor";
                    
        }
        System.out.println(resp);
```
# questao5
```java
        String nome1, nome2;
        Scanner ler = new Scanner(System.in);
        nome1 = JOptionPane.showInputDialog("Digite o 1 nome");
        nome2 = JOptionPane.showInputDialog("Digite o 2 nome");
        ImprimirTexto(CompararTexto(nome1, nome2));

    }

    public static String CompararTexto(String n1, String n2) {
        String resp = "resposta: ";
        if (n1.equals(n2)) {
            resp = resp + "Os nomes são iguais";
        }else{ 
            resp = resp + "Os nomes NÃO são iguais";
        }
        
        return resp;
    }

    public static void ImprimirTexto(String texto) {
        JOptionPane.showMessageDialog(null, texto);
```
# questao6
```java
        Scanner ler = new Scanner(System.in);
        double celsius;
        System.out.println("Informe a tremperatura Celsius: ");
        celsius = ler.nextDouble();
        System.out.println("A temperatura Cº convertida para Fº é: "+conversor (celsius));
        
    }
    public static double conversor(double temp) {
        return ( temp * 1.8 + 32 );
```
# questao7
```java
