<h1>Anotações de estudo de C# </h1>

<h3>

# Escrever Hello, World! no console
 Console.WriteLine("Hello, World!");

# Aguarda o comando do usuario
Console.ReadLine();

# ---- Tipos de dados ----
- bool = "Representa Verdadeiro ou Falso (True or False)";
- char = "Um caractere de um text";
- byte = "Representa valor sem sinal de 8 bits, podendo ter entre 0 a 255 números";
- int = "Representa valor inteiro negativo ou positivo com valores altos";
- long = "Numero inteiro de 64bits";
- float = "Armazena números quebrados";
- double = "Para números quebrados maiores";
- decimal = "Maior precisão, sendo utilizado em moedas";
- string = "Caracteres";

# Expressão ou Instrução, ao atribuir um valor a variavel
- int num1 = 100
- int num2 = num1 = 100

- Incremento (num2++);
- Decremento (num2--);

# Operadores aritmeticos 
- ( + Soma )
- ( - Subtração )
- ( * Multiplicação )
- ( / Divisão )
- ( % Módulo - resto da divisão )

# Operadores aritmeticos de Atribuição Reduzida
- ( += Mais Igual )
- ( -= Menos Igual )
- ( *= Vezes Igual )
- ( /= Dividido Igual )
- ( %= Módulo Igual )

# Operadores Relacionais
- ( == Igual a )
- ( != Diferente de )
- ( > Maior que )
- ( < Menor que )
- ( >= Maior do que ou igual a )
- ( <= Menor do que ou igual a )

# Operadores Lógicos
- ( && Operador e - AND )
- ( || Operador ou - OR )
- ( ! Operador não - NOT )

# Outros Sinais
- ( = Valor de atribuição, o lado esquerdo vai receber o que vem do lado direito )
- ( ?: Operador Condicional Ternario )
- ( num3 = num2 == 42 true ? 10 false : 20 )

# Formas de exibir um texto (string) com uma variavel
 Console.Write("Nome: ");
 string name = Console.ReadLine();

- Console.Write("Seu nome é: " + name);
- Console.Write($"Seja Bem-Vindo {name}!"); (Interpolação de strings)
- Console.ReadLine();

Console.Write("Ano de Nascimento: ");
int year = int.Parse(Console.ReadLine()); - (Converte um número representado como String para número)

int age = 2024 - year;
Console.WriteLine($"Você tem {age} anos.");

# IF desvio condicional
- if (se - se a expressão for igual, então executa uma instrução);
- else (se não - se a expressão for diferente, executa outra instrução);

if(age > 17){
    Console.WriteLine("Você é maior de idade");
}
else{
    Console.WriteLine("Você é menor de idade");
}
</h3>