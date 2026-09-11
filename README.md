# Contact Form

Um formulário de contato HTML acessível e responsivo, construído conforme os requisitos do [roadmap.sh](https://roadmap.sh/packs/html/contact-form).

## 🎯 Requisitos Implementados

- ✅ Formulário com `<form>` elemento com `action` e `method="post"`
- ✅ Labels reais para cada input (não placeholders)
- ✅ Validação de navegador com atributos como `required`, `minlength` e `type="email"`
- ✅ Campos obrigatórios:
  - **Full Name** (texto, obrigatório)
  - **Email** (email, obrigatório)
  - **Subject** (select com 4 opções)
  - **Message** (textarea, obrigatório, minlength=10)
  - **How did you hear about us?** (radio buttons agrupados em fieldset com legend)
- ✅ Campo opcional:
  - **Newsletter** (checkbox)
- ✅ Botão submit com texto claro "Send Message"
- ✅ Metadata no `<head>`:
  - `<title>` - Contact Form
  - `<meta charset="UTF-8">`
  - `<meta viewport>`
- ✅ Acessibilidade:
  - Labels associados via `for` attribute
  - Radio buttons agrupados com `<fieldset>` e `<legend>`
  - `aria-required` nos campos obrigatórios

## 🎨 Design

- Design responsivo e moderno
- Gradiente roxo como background
- Validação visual com cores e sombras
- Compatível com navegadores modernos

## 🚀 Como usar

1. Clone o repositório:
```bash
git clone <repository-url>
cd roadmap-contact-form
```

2. Abra o arquivo `index.html` em um navegador

3. Teste o formulário com dados válidos e inválidos

## 📋 Testing Checklist

- [ ] Form tem `action` e `method="post"`
- [ ] Cada input tem um label associado via `for`
- [ ] Campos obrigatórios têm atributo `required`
- [ ] Email valida tipo com `type="email"`
- [ ] Message tem `minlength` definido
- [ ] Radio buttons estão em `<fieldset>` com `<legend>`
- [ ] Submit button tem `type="submit"`
- [ ] Abra DevTools → Network tab → Preserve log → Submit para ver dados sendo enviados

## 📱 Responsividade

O formulário é completamente responsivo e funciona perfeitamente em:
- Desktop
- Tablet
- Mobile

## 🔗 Links

- [Roadmap.sh - Contact Form](https://roadmap.sh/packs/html/contact-form)
- [HTML Forms - MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form)
