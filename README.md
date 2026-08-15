# Detector de Palíndromos em Python

Este projeto é um script simples em Python criado para verificar se uma frase ou palavra é um palíndromo. O algoritmo limpa o texto digitado e valida se ele pode ser lido da mesma forma de trás para frente.

## 🛠️ Requisitos e Instalação

Para rodar este projeto, você só precisa ter o Python instalado na sua máquina.

* **Python 3.x** instalado.

Não é necessário instalar nenhuma biblioteca externa, pois o script utiliza apenas módulos nativos do Python.

## 🚀 Como Executar

1. Abra o seu terminal ou prompt de comando.
2. Navegue até a pasta raiz do projeto.
3. Execute o comando abaixo:

```bash
python main.py
```

*(Nota: substitua `main.py` pelo nome exato do arquivo caso ele tenha outro nome no seu repositório).*

## 🧠 Como o Algoritmo Funciona

A lógica do código foi estruturada em três etapas simples:
1. **Limpeza do texto:** O script usa expressões regulares (módulo `re`) para remover todos os espaços, traços, pontuações e acentos. Ele também transforma tudo em letras minúsculas.
2. **Inversão:** A string limpa é invertida de trás para frente usando o fatiamento de texto (`[::-1]`) do Python.
3. **Comparação:** O programa compara a string limpa com a string invertida. Se forem exatamente iguais, o texto é um palíndromo (retorna `True`). Caso contrário, retorna `False`.

## 📋 Exemplo de Entrada e Saída

O código possui dois testes pré-configurados. Veja o comportamento esperado:

### Textos de Entrada:
* **Texto 1:** "A sacada da casa de cadasa"
* **Texto 2:** "Socorram-me, subi no ônibus em Marrocos"

### Saída Esperada no Terminal:
```text
Teste 1: True
Teste 2: True
```
