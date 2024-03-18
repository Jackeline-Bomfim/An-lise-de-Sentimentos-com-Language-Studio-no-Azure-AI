## Análise de Sentimentos com Language Studio no Azure AI

Primeiro vou deixar aqui os links da documentação:

[Explore Speech Studio](https://aka.ms/ai900-speech)

[Analyze text with Language Studio](https://aka.ms/ai900-text-analysis)

![dica](/img/tip.png) segure o Ctrl e clique no link para ele abrir em outra aba do seu navegador.

### Explore Speech Studio

* **Configurando o ambiente**

Acesse o portal [Speech Studio](https://speech.microsoft.com/portal) e entre com seu login e senha. Após conectado click no ícone de configurações ![setting](/img/setting.png) e crie um novo recurso. 

Aparecerá uma tela aonde você deverá preencher alguns dados:

![create a resource](/img/create%20a%20resource.png)

Preenchido, clique em criar recurso e volte para a página de ínicio.

* **Testando...**

Clique em **Conversão de voz em texto em tempo real** e importe um arquivo de áudio, caso não tenha um arquivo, você pode baixar um através deste link: [arquivo de áudio](https://aka.ms/mslearn-speech-files).

![upload](/img/upload.png)

E agora a mágica acontece, ela escuta tudinho e escreve para você logo ao lado, legal neh!

Veja abaixo o resultado:

![result](/output/result.png)

### Analyze text with Language Studio

* **Configurando o ambiente**

Acesse o [Portal Azure]( https://portal.azure.com) entre com seu login e senha e clique em **+ create a resource**. Na lateral em categorias clique em **AI + Machine Learning** e mostrará algumas opções no lado direito. Procure por **Language service** e clique em create.

![language service](/img/language%20service.png)

Na próxima tela clique em **continue to create your resource**. Na próxima tela, preencha os dados conforme orientado abaixo:

![create language](/img/create%20language.png)

E clique em **Review + create**, mas não se esqueça de deixar a caixinha selecionada. ![select](/img/select.png).

Feita a validação selecione **create**. 

Pronto! Agora vamos acessar o portal [Language Studio](https://language.cognitive.azure.com). Caso já não esteja logado, entre com seu login e senha no canto superior direito. 

Primeiro você deve preencher a tela abaixo para dar acesso ao serviços do language studio.

![Select resource](/img/Select%20an%20Azure%20resource.png)

PRONTO AGORA VAMOS TESTAR.

Clique na guia **Classicar texto** e na sequência clique em **Analisar sentimentos e extrair opiniões**. Agora vamos ver o resultado. Vou utilizar textos em português para uma melhor compreensão.

![result 1](/output/Language%20-%20result%201.png)

![result 2](/output/Language%20-%20result%202.png)

Na foto abaixo podemos notar que a IA não entendeu o comentário e avaliou como positivo.

![result 3](/output/Language%20-%20result%203.png)

Agora é sua vez de tentar. 






