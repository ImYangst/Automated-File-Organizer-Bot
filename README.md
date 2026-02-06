# Automated-File-Organizer-Bot

📁 File Organizer Bot

Este é um script em Python desenvolvido para automatizar a organização da sua pasta de downloads (ou qualquer outra pasta específica). Ele monitora a pasta em tempo real e move arquivos para diretórios específicos baseando-se na extensão do arquivo.

🚀 Funcionalidades

- Monitoramento Ativo: Utiliza a biblioteca watchdog para detectar novos arquivos instantaneamente.

- Organização por Extensão: Suporta diversos formatos (PDF, imagens, vídeos, arquivos compactados, etc.).

- Criação Automática de Pastas: Se a pasta de destino não existir, o script a cria para você.

- Registro de Atividades (Logs): Gera um arquivo app.log para você acompanhar o que foi movido e quando.

🛠️ Pré-requisitos

Antes de começar, você precisará ter o Python 3.x instalado em sua máquina. Além disso, é necessário instalar a biblioteca que faz o monitoramento dos arquivos:

    pip install watchdog

⚙️ Configuração

Para que o script funcione no seu computador, você precisa editar duas partes no código:

- downloads_path: Altere "path" para o caminho da pasta que você deseja monitorar (ex: "/home/usuario/Downloads").

- destinos: No dicionário, altere os valores "path" para o nome das pastas onde cada tipo de arquivo deve ser guardado.
