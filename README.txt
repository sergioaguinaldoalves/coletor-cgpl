COLETOR PATRIMONIAL CGPL – PWA V2

1. FINALIDADE
Aplicativo web instalável para coleta patrimonial da CGPL/SECOM, com:
- câmera do celular/iPad;
- leitor Bluetooth;
- importação de base CSV;
- busca por patrimônio, número de série ou IMEI;
- sessão por local/responsável;
- identificação de divergências;
- histórico local;
- exportação CSV.

2. IMPORTANTE PARA IPHONE/IPAD
A câmera do Safari exige contexto seguro. Portanto, publique esta pasta em um endereço HTTPS.
Abrir index.html diretamente pelo app Arquivos (file://) não é suficiente.

3. FORMAS SIMPLES DE PUBLICAÇÃO
- GitHub Pages;
- Cloudflare Pages;
- Netlify;
- servidor web HTTPS interno da organização.

4. INSTALAR NO IOS
Após abrir o endereço HTTPS no Safari:
Compartilhar > Adicionar à Tela de Início.

5. BASE DE DADOS
Use BASE_BENS_MODELO.csv como referência.
O sistema aceita pequenas variações nos nomes das colunas e pesquisa por:
- patrimônio;
- número de série;
- IMEI.

6. OFFLINE
Após a primeira abertura, os arquivos principais ficam em cache.
A base e as coletas ficam salvas no armazenamento local do navegador.
A biblioteca de leitura da câmera é carregada inicialmente pela internet.

7. SEGURANÇA
Os dados ficam no próprio dispositivo e não são enviados a servidor por este código.
Para uso institucional definitivo, recomenda-se hospedar a biblioteca de leitura também internamente e definir política de backup/exportação.
