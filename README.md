# Thamires Martins | Massoterapia e Estética Corporal

Site institucional da **Thamires Martins**, especialista em cuidados de bem-estar feminino, massoterapia, estética corporal e depilação em Rio das Ostras, RJ.

**Site:** https://thamiresmartins.store/  
**Instagram:** https://www.instagram.com/thamiresmartins_massoterapeuta/  
**WhatsApp:** +55 (22) 99275-2182  
**Endereço:** Rua Tijuca, 438, Centro, Rio das Ostras, RJ, CEP 28890-000.

**Horários:** segunda a sexta das 08:00 às 20:00, sábado das 08:00 às 13:00, domingo fechado. Atendimento mediante agendamento.

## Site e deploy
A página de produção está no **index.html**, em um único arquivo HTML com CSS, JavaScript e imagens conceituais incorporadas. Isso evita imagens quebradas e permite prévia sem dependência de servidores de mídia.

Hospedagem pretendida: GitHub Pages, branch `main`, raiz `/(root)`. O `CNAME` já aponta para `thamiresmartins.store`. Confira se o Pages está ativo, se o DNS da Hostinger está apontado e se o HTTPS está habilitado.

## Catálogo e mídias
O site possui 10 tratamentos, todos com **drawer lateral** de detalhes, foto ilustrativa e botão para conversar no WhatsApp. Dentro do JavaScript incorporado ao `index.html`, cada serviço possui os campos `audioUrl` e `videoUrl`, inicialmente `null`. Essas mídias só aparecem quando um link válido for acrescentado ao serviço correspondente.

As fotos dos serviços e do ambiente são conceituais e **não representam necessariamente o espaço ou o procedimento real**. Substituir pelas imagens autorizadas quando a Thamires enviar o material. Não foram inventados preços, avaliações, certificações ou resultados garantidos.

**Nota:** `styles.css` e `script.js` antigos não são carregados pelo site de produção, que é autossuficiente. A versão organizada por arquivos pode ser consultada no pacote entregue à parte.