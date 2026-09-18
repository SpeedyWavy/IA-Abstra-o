# IA Abstração

# Banda Escolar

- Lucas Brulezzi dos Santos

# *Perguntas*

## 1 Quantas classes concretas (instrumentos) o texto descreve? Quais sao?
o texto descreve 2 Instrumentos/classe concretas, sendo elas Violão e Bateria

## 2 Quais atributos aparecem em TODOS os instrumentos? Esses vao para a classe abstrata.
os Atributos q aparecem em todos os instrumentos derivam da classe InstrumentoMusical.java, esses atributos são "Nome", "Material" e "Afinado" sendo compartilhados entre Violão.java e Bateria.java

## 3 Qual atributo e exclusivo de cada instrumento (aparece so no paragrafo dele)?
os atributos exclusivos existem em cada um separadamente, sendo o de Violão o "quantidadeCordas", e na bateria o "quantidadeTambores".

## 4  O texto descreve um comportamento que cada instrumento faz de um jeito DIFERENTE (vira metodo abstrato) e um comportamento que e IGUAL para todos (vira metodo normal na classe mae). Quais sao?
o comportamento descrito no texto q cada instrumento faz de uma forma diferente e "tocar()", o comportamento q e Igual em todos e o "afinar()"

## 5 Um trecho diz que "nao deve ser possivel criar um instrumento generico". Qual recurso do Java garante isso?
o fato da classe ser Abstract impede a criaçãodeum instrumento generico

## 6 Para percorrer todos os instrumentos no mesmo laco, sem instanceof e sem cast, que tipo a List<?> do teste deve ter?
a list precisa de "List<InstrumentoMusical> instrumentos = new ArrayList<>();" para percorrer todos os instrumentos