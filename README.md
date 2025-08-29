# Raspagem-Curso-VIRTUS
- Curso: Fundamentos das Plataformas de Sensoriamento Inteligente para Indústria 
- Exemplo prático de automação web com a biblioteca Selenium onde além de buscar os links das aulas do curso, separa em planilhas o que é aula gravada do curso e o que foram de encontros síncronos (que também foram gravados e disponibilizados para assistir). Este código também faz o download de ambas as listas de vídeos e separa em pastas distintas;

- Forma robusta de se realizar uma automação web: tratamento de erros, código flexível, modular e mais ágil.

- Melhorias a serem feitas: não desenvolvi uma forma de buscar o link da aula de abertura do curso e acrescentei o link como sendo uma constante do código.

  # Dicas Iniciais:
 - Passo 1: Crie um ambiente virtual (trazendo um Python puro para sua pasta) -> py -m venv venv
 - Passo 2: Ativação do ambiente virtual criado -> \venv\Scripts\activate [ Na prática escreva: ve(aperta tab)sc(aperta tab)ac(aperta tab) ]
 
 - OBS-1: Caso dê errado e não dê nenhum aviso, tente: .\venv\Scripts\Activate.ps1 [ Na prática escreva: ve(aperta tab)sc(aperta tab)ac(aperta tab) e complete escrevendo .ps1 ]
 
 - Passo 3: Execute o seguinte comando para instalar todas as bibliotecas de uma única vez -> pip install -r \requirements.txt [ Na prática escreva: pip install -r req(aperta tab) ]

 # Ajustando Política de Privacidade:
 - OBS-2: Caso não esteja autorizando, é necessário executar o powershell como adm e verificar :
 
 - Get-ExecutionPolicy
 - Se estiver dando como restrito, utilizar este comando e autorizar -> Set-ExecutionPolicy Unrestricted
 - Depois se quiser reotrnar para política restrita utilizando -> Set-ExecutionPolicy Restricted
