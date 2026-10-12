# Tines | Thamires Martins Massoterapia

Site institucional estático para Thamires Martins, massoterapeuta em Rio das Ostras, RJ.

## Projeto
- Domínio: https://thamiresmartins.store
- Instagram: https://www.instagram.com/thamiresmartins_massoterapeuta/
- WhatsApp: +55 22 99275-2182
- Localização: Rua Tijuca, 438, Centro, Rio das Ostras, RJ, CEP 28890-000
- Perfil no Google: https://share.google/yfPEvjeZcIU4XNdFD
- Hospedagem pretendida: GitHub Pages, repositório público sob a conta `ruanmeloandrade-alt`

## Arquivos
- `index.html`: conteúdo, SEO e dados estruturados do negócio.
- `styles.css`: identidade visual, design e responsividade.
- `script.js`: menu mobile e comportamento de cabeçalho.
- `favicon.svg`: ícone vetorial provisório.
- `CNAME`: domínio personalizado para GitHub Pages.
- `404.html`: página de erro.
- `sitemap.xml` e `robots.txt`: indexação.

## Como publicar (GitHub Pages)
1. Criar repositório **público** chamado `tines-thamires-martins` na conta `ruanmeloandrade-alt`.
2. Subir todos os arquivos deste diretório para a **raiz** da branch `main` (não apenas a pasta compactada).
3. Em **Settings > Pages**, escolher `Deploy from a branch` > `main` > `/(root)` e salvar.
4. Em `Settings > Pages > Custom domain`, informar `thamiresmartins.store` e salvar. O arquivo `CNAME` já contém o domínio, para publicação por branch.
5. Na zona DNS responsável pelo domínio, apontar quatro registros `A` para o domínio raiz `@`: 
   - 185.199.108.153
   - 185.199.109.153
   - 185.199.110.153
   - 185.199.111.153
6. Criar CNAME `www` apontando para `ruanmeloandrade-alt.github.io` (sem nome do repositório).
7. Após propagação e validação do certificado, marcar `Enforce HTTPS` no GitHub Pages.
8. Validar tanto `https://thamiresmartins.store` quanto `https://www.thamiresmartins.store`.

**Atenção:** Antes de editar registros DNS, confira se os nameservers do domínio apontam para a Hostinger, se existem registros A/CNAME conflitantes e se há serviços de e-mail: nunca remova MX/TXT por engano. Caso o domínio esteja associado a um site já publicado, faça backup e planeje a migração.

## Conteúdo a confirmar com a cliente
- Lista exata de massagens/procedimentos, duração e valores.
- Horário semanal completo e regras de agendamento.
- Fotos autorizadas do espaço e da profissional e identidade visual oficial, se houver.
- Depoimentos autorizados, se houver.

A versão inicial não contém depoimentos fictícios, preços inventados, fotos genéricas ou alegações terapêuticas não confirmadas.

## Desenvolvimento local
Iniciar servidor HTTP estático na raiz do projeto (ex.: `python -m http.server 8000`) e abrir `http://localhost:8000/`.
Nenhum build, conta de serviço, analytics, framework ou dependência externa é necessário para o site funcionar (exceto os links e o mapa Google incorporado).
