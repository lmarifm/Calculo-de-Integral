# Calculadora de Integrais por Soma de Riemann

*Aluna: Maria Luisa Fernandes de Mendonça*  
*Cálculo 2 - 2025.2 - Prof. Renan da Silva Santos*

##  Objetivo
Calculadora para calcular integrais de funções elementares usando o método dos retângulos (soma de Riemann).

##  Configuração
- **Tolerância**: 1e-6  
- **Biblioteca**: math  
- **Método numérico**: Soma de Riemann 

##  Como Usar
Execute o arquivo `calculadora_integral.py` e digite:
1. A função f(x) usando sintaxe Python
2. O limite inferior do intervalo (a)
3. O limite superior do intervalo (b)

##  Casos de Teste

1. `x**2` em [0, 2] → ≈2.666667  
2. `math.sin(x)` em [0, π] → ≈2.000000  
3. `math.exp(x)` em [0, 1] → ≈1.718282  
4. `math.sqrt(x)` em [0, 4] → ≈5.333333  
5. `2*x + 1` em [0, 3] → ≈12.000000  

## ✅ Resultados
Todos os testes passaram com tolerância de 1e-6