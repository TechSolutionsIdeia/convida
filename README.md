# LP ConVida — Tratamento de feridas em Campo Mourão (26/10/2026)

**Objetivo único:** gerar conversa no WhatsApp (44) 99810-0888.
Página estática: `index.html` + `img/`. Sem framework; o único JS monta o link do WhatsApp.

## Publicação (só quando o Tales pedir)
- Hospedagem da Idéia, Netlify ou Vercel: basta subir a pasta inteira (arrastar a pasta no Netlify Drop funciona).
- Ideal: domínio próprio (ex.: convidaclinica.com.br) e cadastrar a URL no campo **Site** do Perfil da Empresa no Google. Isso ajuda a busca orgânica e as IAs.

## WhatsApp e UTM
Todos os botões usam o mesmo link, com a mensagem "Olá! Vim pelo site e gostaria de agendar uma avaliação na ConVida."
Se a URL tiver `?utm_source=...&utm_campaign=...`, a origem entra no fim da mensagem. Exemplos:
- Anúncio Meta: `https://SEU-DOMINIO/?utm_source=meta&utm_campaign=feridas`
- Perfil do Google: `https://SEU-DOMINIO/?utm_source=gmn`
- Instagram (bio): `https://SEU-DOMINIO/?utm_source=instagram`

## SEO local incluído
`<title>` com serviço + cidade, meta description, um único H1, schema.org `MedicalClinic` (endereço, GPS, horário, telefone, Instagram), imagens WebP com alt descritivo, carregamento tardio abaixo da dobra.

## Conformidade (COFEN 554/2017)
Sem fotos de feridas, pacientes ou "antes e depois"; sem promessa de resultado; ozonioterapia descrita como complementar (Lei 14.648/2023); PRP conforme a Res. COFEN 788/2025; WhatsApp só para agendar (avaliação presencial); RT com COREN no rodapé. Checklist completo: `MARCAS\CONVIDA\conformidade-publicidade-saude.md`.

## Confirmar com a cliente antes de publicar
1. Número e UF do COREN da RT (o carimbo mostra "COREN 000522.498"; usamos COREN-PR 522498).
2. Convênio, SUS e atendimento domiciliar (o FAQ hoje responde "informamos pelo WhatsApp").
3. Arquivo original do logo (o logo atual é uma reconstrução a partir do letreiro).
4. Autorização para citar as 2 avaliações do Google (são públicas, mas é boa prática avisar).

Verificação: `verificacao-desktop-dobra.png` (1366×768) e `verificacao-mobile-dobra.png` (390×844).
