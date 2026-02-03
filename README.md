Tabela Periódica Interativa para Anotações

Este projeto é uma ferramenta pedagógica e técnica que permite aos utilizadores inserir anotações personalizadas em cada elemento da Tabela Periódica, com suporte para exportação visual e persistência de dados.

🚀 Funcionalidades

Anotações Diretas: Cada célula de elemento possui um campo de texto (textarea) para inserção de dados.

Estrutura Completa: Inclui os 118 elementos, com separação correta para Lantanídeos e Actinídeos.

Exportação para Imagem: Gera um ficheiro PNG de alta resolução da tabela preenchida, ocultando automaticamente os controlos de interface no momento da captura.

Persistência em JSON: Permite salvar o estado atual das anotações num ficheiro .json e carregá-lo posteriormente.

Interface Responsiva: Design limpo com numeração de grupos (1-18) e períodos (1-7).

🛠️ Tecnologias Utilizadas

HTML5/CSS3: Estrutura em Grid Layout para precisão posicional.

JavaScript (Vanilla): Lógica de manipulação do DOM e gestão de ficheiros.

html2canvas: Biblioteca utilizada para converter o container HTML em representação de imagem (Canvas).

📖 Como Utilizar

Escrever: Clique no campo branco de qualquer elemento e digite a sua nota. O número atômico aparece como marca d'água (placeholder).

Salvar Imagem: Clique em "Salvar como Imagem". O sistema irá processar a tabela e descarregar um ficheiro tabela_periodica_anotacoes.png.

Backup de Dados (JSON):

Use "Salvar Anotações (JSON)" para descarregar um backup de texto das suas notas.

Use "Carregar Anotações (JSON)" para restaurar notas de um backup anterior.

Limpar: O botão "Limpar Tudo" remove instantaneamente todos os textos inseridos.

⚙️ Configuração Técnica

O ficheiro é autocontido (Single File Application). Para executar:

Basta abrir o ficheiro tabela_periodica_anotacoes.html em qualquer navegador moderno.

Requer ligação à internet para carregar a biblioteca html2canvas via CDN.

Desenvolvido para fins educacionais e de organização de estudo.
