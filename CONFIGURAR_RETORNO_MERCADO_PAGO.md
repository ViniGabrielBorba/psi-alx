# Configurar URL de retorno no Mercado Pago

Para que o cliente seja redirecionado de volta ao site após o pagamento e o download do ebook seja liberado automaticamente, é necessário configurar a **Redirecionamento** no Mercado Pago.

## URL que deve ser configurada

**URL de sucesso (pagamento aprovado):**
```
https://www.ebookpsialexandre.com.br/
```

O Mercado Pago adiciona automaticamente os parâmetros de status na URL quando redireciona o cliente.

---

## Como configurar (Link de pagamento - mpago.la)

### Passo a passo

1. Acesse [Mercado Pago](https://www.mercadopago.com.br/) e faça login
2. Vá em **Link de pagamento** em [Ferramentas para vender](https://www.mercadopago.com.br/tools/list)
3. Encontre o link do ebook e clique em **Editar** (ou crie um novo)
4. Clique em **"Mais opções"** ou **"Configurações avançadas"**
5. Na seção **"Redirecionamento"**, ative a opção e cole a URL:
   ```
   https://www.ebookpsialexandre.com.br/
   ```
6. Salve as alterações

A opção "Redirecionamento" permite enviar o comprador para o site desejado após o pagamento.

---

## Verificar se está funcionando

Após configurar:

1. Faça um pagamento de teste (valor mínimo)
2. Após aprovar, você deve ser redirecionado para `https://www.ebookpsialexandre.com.br/?status=approved` (ou parâmetros similares)
3. O download do PDF deve iniciar automaticamente

---

## Enquanto não configurar

Se o cliente pagou mas não foi redirecionado e não conseguiu baixar:

- O cliente pode entrar em contato em **alexandrepsi1901@gmail.com** informando que realizou o pagamento
- Você envia o PDF manualmente por e-mail
