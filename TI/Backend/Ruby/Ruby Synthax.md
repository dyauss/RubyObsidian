## % Notation

Ruby usa a notação `%` para várias formas de criar literais de maneira concisa. Aqui estão alguns exemplos:

- `%w` para criar um array de strings.
- `%i` para criar um array de símbolos.
- `%q` para criar uma string simples.
- `%Q` para criar uma string interpolada.
- `%r` para criar uma expressão regular.

### Exemplo de Uso

- **Array de Strings**:
  ```rb
  %w[one two three]  # Equivalente a ["one", "two", "three"]
  ```

- **Array de Símbolos**:
  ```rb
  %i[one two three]  # Equivalente a [:one, :two, :three]
  ```

- **String Simples**:
  ```rb
  %q[Hello, world!]  # Equivalente a "Hello, world!"
  ```

- **String Interpolada**:
  ```rb
  name = "Ruby"
  %Q[Hello, #{name}!]  # Equivalente a "Hello, Ruby!"
  ```

- **Expressão Regular**:
  ```rb
  %r[hello]  # Equivalente a /hello/
  ```

