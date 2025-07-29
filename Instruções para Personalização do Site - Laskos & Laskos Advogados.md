# Instruções para Personalização do Site - Laskos & Laskos Advogados

## Site Implantado
**URURL: https://zmxlwtqy.manus.space

## Como Adicionar Suas Imagens

### 1. Logo do Escritório
- **Localização no código:** Procure por `<div class="logo-placeholder">`
- **Substituir por:** `<img src="caminho-da-sua-logo.png" alt="Laskos & Laskos Advogados" style="width: 80px; height: 60px;">`
- **Formato recomendado:** PNG ou SVG, tamanho 80x60 pixels

### 2. Foto da Fachada do Escritório
- **Localização no código:** Procure por `<div class="office-photo-placeholder">`
- **Substituir por:** `<img src="caminho-da-foto-fachada.jpg" alt="Fachada do Escritório" style="width: 100%; height: 400px; object-fit: cover; border-radius: 15px;">`
- **Formato recomendado:** JPG ou PNG, tamanho mínimo 800x400 pixels

### 3. Fotos dos Advogados
- **Localização no código:** Procure por `<div class="member-photo">` (3 vezes)
- **Substituir por:** `<img src="caminho-da-foto-advogado.jpg" alt="Nome do Advogado" style="width: 150px; height: 150px; border-radius: 50%; object-fit: cover;">`
- **Formato recomendado:** JPG ou PNG, tamanho 300x300 pixels (será exibido como 150x150)

## Estrutura de Arquivos

```
laskos-site/
├── index.html          (arquivo principal)
├── styles.css          (estilos do site)
├── script.js           (funcionalidades)
└── images/             (pasta para suas imagens)
    ├── logo.png
    ├── fachada.jpg
    ├── tainan.jpg
    ├── glauber.jpg
    └── lucas.jpg
```

## Cores Utilizadas

- **Preto:** #000000
- **Branco:** #FFFFFF  
- **Cinza:** #696865
- **Dourado:** #FFD700

## Funcionalidades Implementadas

✅ **Design Responsivo** - Adapta-se a desktop, tablet e mobile
✅ **Botão WhatsApp Flutuante** - Link direto para o WhatsApp
✅ **Links Funcionais** - WhatsApp e Google Maps
✅ **Navegação Suave** - Scroll suave entre seções
✅ **Animações** - Efeitos visuais elegantes
✅ **Placeholders Prontos** - Espaços marcados para suas imagens

## Links Importantes

- **WhatsApp:** https://api.whatsapp.com/send/?phone=5542998352695&text&type=phone_number&app_absent=0
- **Google Maps:** https://share.google/vQUdWoSAWS873JzGq

## Próximos Passos

1. **Adicione suas imagens** nos locais indicados
2. **Teste o site** em diferentes dispositivos
3. **Personalize textos** se necessário
4. **Compartilhe o link** com seus clientes

## Suporte

O site está totalmente funcional e pronto para uso. Todas as informações fornecidas foram implementadas conforme solicitado, incluindo:

- Nome do escritório e áreas de atuação
- Dados dos advogados (Tainan, Glauber e Lucas)
- Endereço completo em Ponta Grossa
- Número do WhatsApp com link direto
- Informações sobre experiência e atendimento nacional

