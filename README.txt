COLETOR PATRIMONIAL CGPL – PWA V2.1

ALTERAÇÕES DA V2.1
- câmera otimizada para códigos de barras 1D;
- prioridade para CODE 128, CODE 39, CODE 93, CODABAR e ITF;
- área de leitura horizontal e mais estreita;
- leitura a 20 FPS;
- preferência por câmera traseira em 1920x1080;
- foco contínuo quando suportado;
- tentativa de zoom automático moderado;
- botão de lanterna quando suportado;
- indicação do formato detectado;
- mantém Bluetooth, digitação manual, base CSV, sessão, histórico e exportação.

PARA ATUALIZAR NO GITHUB
1. Abra o repositório coletor-cgpl.
2. Faça upload substituindo index.html, sw.js, manifest.json e os ícones.
3. Confirme o commit.
4. Aguarde o GitHub Pages publicar.
5. No iPhone, feche completamente a PWA/Safari e abra novamente.
6. Se ainda aparecer a versão antiga, remova o ícone da Tela de Início e abra novamente pelo Safari.

DICA PARA A ETIQUETA
Mantenha a etiqueta horizontal, sem reflexo, e aproxime/afaste lentamente até as barras ocuparem quase toda a faixa de leitura.


ATUALIZAÇÃO V2.2
- emite dois bipes curtos quando uma coleta é registrada;
- mantém vibração curta de confirmação;
- ao ler novamente o mesmo patrimônio/código, emite alerta sonoro diferente;
- mostra a mensagem "JÁ COLETADO — registro duplicado bloqueado";
- não grava uma segunda linha no histórico;
- mantém câmera 1D, Bluetooth, lanterna, importação CSV e exportação.

OBSERVAÇÃO IOS
O Safari pode exigir uma primeira interação do usuário para liberar áudio. Como a câmera é iniciada por toque, normalmente o áudio já fica autorizado após o início da coleta.


ATUALIZAÇÃO V2.3 — GPAT
- importa diretamente o arquivo .xls exportado pelo GPAT, mesmo quando o conteúdo interno é HTML;
- reconhece Patrimônio, Material, Marca, Modelo, Série, Fabricante, UORG, Destinação, Patrimônio Anterior, Tombamento, Conta Contábil e Detentor;
- pesquisa também por Patrimônio Anterior e Série;
- exibe UORG, Destinação, Detentor e Patrimônio Anterior após a leitura;
- mantém alerta sonoro e bloqueio de duplicidade da V2.2.

USO
No GPAT, exporte a Relação de Patrimônio em .xls. No Coletor, toque em Importar GPAT (.xls) ou CSV e selecione o arquivo original, sem conversão.
