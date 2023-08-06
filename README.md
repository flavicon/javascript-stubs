# Javascript stubs

Implementação de stubs para tests com nodejs.

## sobre o projeto

Nessa aula foi apresentada a lib sinon.js utilizada para criar stubs.
Um stub é uma implementação que nos permiti fornecer respostas prontas, são utilizadas
para cenários onde queremos validar apenas o resultado.

No projeto em questão criamos dois stubs, em ambos simulamos a resposta da api [swapi](https://swapi.dev/)
a api de Star Wars. No primeiro stub validamos a resposta para o endpoit ```https://swapi.dev/api/planets/1/``` e comparamos
com a resposta do método ```getPlanets()``` presente na classe ```Service```. Já o segundo stub testa a resposta do endpoint
```https://swapi.dev/api/planets/2/``` comporando com a resposta do mesmo método mencionado acima.

### como baixar o projeto?

```shell
git clone https://github.com/flavicon/javascript-stubs.git

cd javascript-stubs
```

### como executar o projeto?

> Certifique-se de que o nodejs está instalado na sua máquina.
> [Baixar nodejs](https://nodejs.org/en/download)

1 - instalando dependencias

```shell
npm install
```

2 - executando os testes

```shell
npm run test
```
