# Doce Sabor Premium

![HTML](https://img.shields.io/badge/linguagem-HTML-blue)

Protótipo de site para confeitaria com apresentação de produtos e formulário de personalização de bolo. O formulário prepara uma mensagem para WhatsApp.

## Tecnologias e requisitos

HTML, CSS e JavaScript, com Bootstrap. É necessário um navegador moderno e acesso à internet para fontes, bibliotecas e imagens hospedadas externamente.

## Executar localmente

Com Git e Python 3 instalados:

```sh
git clone https://github.com/sauloz20/doce_sabor.git
cd doce_sabor
python -m http.server 8000
```

Acesse `http://localhost:8000/`. Também é possível servir a pasta com Apache/XAMPP.

## Estrutura

```text
index.html   Conteúdo, formulário e interações
style.css    Estilos do site
```

## Limitações

O número de WhatsApp configurado é ilustrativo e deve ser substituído antes de uso real. As duas imagens de redes sociais no rodapé apontam para arquivos locais de outro computador e, portanto, não estão disponíveis no repositório. O projeto não contém backend de pedidos ou pagamento.
