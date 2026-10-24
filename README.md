# AutoVolt | Elétrica Automotiva & Diagnóstico Computadorizado

Landing page de altíssimo padrão desenvolvida para oficinas de auto elétrica automotiva e serviços de socorro emergencial de baterias (SOS no local), com foco total em conversão para WhatsApp e chamadas telefônicas diretas.

## 🚀 Tecnologias e Diferenciais
- **HTML5 Semântico:** Estrutura otimizada com microdados Schema.org (`AutoRepair`), tags Open Graph e acessibilidade completa (ARIA labels).
- **CSS3 Moderno (Vanilla):** Design tokens em paleta Grafite Carbono (`#0B0F17`), Amarelo Esportivo (`#EAB308`) e Ciano Técnico (`#06B6D4`), tipografia moderna (*Outfit* + *Plus Jakarta Sans*), zero dependências pesadas e carregamento instantâneo.
- **JavaScript Modular Puro:** Modal de triagem inteligente com chips por tipo de serviço, contador animado com *IntersectionObserver*, accordion de FAQ técnico automotivo e menu mobile responsivo.
- **Identidade Visual e Imagens Reais:** Logotipo estilizado (`logo-autovolt.jpg`), foto de diagnóstico computadorizado (`hero-autoeletrica.jpg`) e bancada de oficina (`showcase-autoeletrica.jpg`).

## 📦 Como Subir na Vercel
1. Acesse [vercel.com/new](https://vercel.com/new);
2. Conecte sua conta do GitHub e selecione o repositório `site-autoeletrica`;
3. Mantenha as configurações padrão (Framework Preset: **Other**) e clique em **Deploy**;
4. Seu site estará no ar em segundos com certificado SSL gratuito e CDN global ultra rápida!

## ⚙️ Personalização do WhatsApp e Telefone
Para alterar o número do WhatsApp de destino:
Abra o arquivo `script.js` e altere a constante `WHATSAPP_PHONE` na linha 8 com o seu número com DDI e DDD (ex: `5511999999999`).
Para alterar o telefone exibido e os links `tel:`, substitua `(11) 99999-9999` e `tel:+5511999999999` no `index.html`.
