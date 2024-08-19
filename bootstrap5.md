Framework para auxiliar na criação de páginas HTML e CSS

O Bootstrap foi criado pelo Designer [Mark Otto](https://twitter.com/mdo), e pelo Desenvolvedor de Software [Jacob Thorton](https://twitter.com/fat) em 2010.

A ideia por trás dessa ferramenta, era tornar mais prática a implementação de padrões de layout das páginas do Twitter


Usar página para pegar modelos: https://getbootstrap.com/docs/5.3/getting-started/introduction/

## Adicionando o BS no seu código

No head, após o title:
```html
 <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH"
      crossorigin="anonymous"
    />
```

Antes de fechar o body (</body>)
```html
<script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz"
      crossorigin="anonymous"
    ></script>
```

## Responsividade

Os breakpoints é igual ao @media
![[Pasted image 20240818134333.png]]
https://cursos.alura.com.br/course/bootstrap5-landing-page-responsiva/task/123894

## Para importar icones ao projeto

No head, após o title:
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
```


## Flex Container

Use `d-flex` e `d-inline-flex`: para criar um container flexbox comum ou em linha e transformar os elementos filhos diretos em **itens flexíveis**.

O padrão de direção no flex é `row` ou linha, então ao utilizar o Bootstrap e aplicar a classe `d-flex`, por padrão a classe `flex-row` também é aplicada. Utilize `flex-column` para definir uma direção vertical.

Mais infos em https://cursos.alura.com.br/course/bootstrap5-landing-page-responsiva/task/125862

