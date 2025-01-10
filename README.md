# Módulo 02 | Python: Estruturas de Dados

Este projeto é parte do Módulo 02 do curso de Python da EBAC, ministrado pelo Professor Jailson Carvalho. O foco é entender e manipular as principais estruturas de dados em Python: **Listas**, **Conjuntos** e **Dicionários**.

## Tópicos Abordados
- Listas
- Conjuntos
- Dicionários

## Aulas

### 1. Listas

As listas são sequências mutáveis e ordenadas de valores. Elas podem armazenar vários tipos de dados e permitem adições, remoções e atualizações de elementos.

#### Exemplos:
```python
usuario_web = ['André Perez', 'andre.perez', 'andre123', 'andre.perez@gmail.com']
idade = 20
saldo_em_conta = 723.15
usuario_loggedin = True
usuario_web = ['André Perez', idade, 'andre.perez', 'andre123', 'andre.perez@gmail.com', saldo_em_conta, usuario_loggedin]
print(usuario_web)
```

#### Operações com Listas
- **Concatenação**: 
  ```python
  fabricantes_mobile = fabricantes_mobile_china + fabricantes_mobile_eua
  ```
- **Fatiamento**:
  ```python
  fabricantes_mobile[0:2]
  ```
- **Inserir e remover elementos**:
  ```python
  juros.insert(0, 0.10)
  juros.append(0.09)
  juros.remove(0.1)
  juros.pop(2)
  ```

### 2. Conjuntos

Conjuntos são sequências imutáveis, desordenadas e não permitem elementos repetidos. São úteis para operações como união, interseção e diferença entre coleções de dados.

#### Exemplos:
```python
frutas = {'banana', 'maca', 'uva'}
print(frutas)  # {'banana', 'uva', 'maca'}
```

#### Operações com Conjuntos:
- **Diferença**:
  ```python
  norte_europa_nao_escandivano = norte_europa - escandinavia
  ```
- **Inserir e remover elementos**:
  ```python
  cursos.add('Saúde')
  cursos.remove('Saúde')
  ```

### 3. Dicionários

Dicionários armazenam dados no formato chave-valor. São ideais para representar informações associadas a uma chave única, como em um banco de dados.

#### Exemplos:
```python
brasil = {'capital': 'Brasília', 'idioma': 'Português', 'populacao': 210}
print(brasil)
```

#### Operações com Dicionários:
- **Acessar e atualizar elementos**:
  ```python
  credito['123'] = 435
  ```
- **Adicionar novos elementos**:
  ```python
  credito['456'] = 1000
  ```

### Métodos Nativos de Python

- **Listas**: `insert()`, `append()`, `remove()`, `pop()`
- **Conjuntos**: `add()`, `remove()`
- **Dicionários**: `update()`

## Como Usar

Este projeto contém exemplos práticos e explicações sobre como usar as principais estruturas de dados em Python. Cada aula apresenta um tópico com código de exemplo que pode ser executado diretamente em seu ambiente Python.

## Requisitos

Para rodar este projeto, você precisará de:
- Python 3.x instalado
- Um editor de código, como Visual Studio Code ou Jupyter Notebook, para testar os exemplos.

## Licença

Este projeto é de uso educacional e segue a licença padrão da EBAC.

## Contato

Se você tiver dúvidas sobre o conteúdo do curso ou sobre como utilizar este código, entre em contato com o professor Jailson Carvalho ou acesse os fóruns de discussão da EBAC.
