# 📊 Controle de Registros de Teletrabalho

Uma aplicação web executada inteiramente no lado do cliente (*client-side*) para gerenciar, calcular e acompanhar os registos de atividades e pontuações de teletrabalho. Desenvolvida para ser simples, offline e focada na privacidade do utilizador.

## 🚀 Funcionalidades Principais

* **Cálculo Automático:** As metas, feriados nacionais e reduções de expediente são calculados e descontados automaticamente.
* **Privacidade e Offline:** Os seus dados são guardados num ficheiro JSON local na sua máquina. Não há envio de dados para servidores externos.
* **Geração de Relatórios:** Exporte resumos anuais ou consolidados semanais diretamente para formato PDF, prontos para envio.
* **Dashboard e Estatísticas:** Painel gráfico gerado automaticamente com a sua taxa de sucesso (*hit rate*), ranking de tarefas, horas trabalhadas e saldo de pontos.
* **Acompanhamento Visual:** Indicadores de cor mostram instantaneamente o progresso da pontuação e se a meta semanal foi atingida.
* **Multi-dispositivo e Temas:** Interface totalmente responsiva (telemóveis, tablets ou PC) com suporte integrado para modos claro e escuro.

## 🛠️ Tecnologias Utilizadas

* **HTML5 & CSS3:** Estrutura e estilização com variáveis CSS para suporte nativo a temas (Dark/Light).
* **JavaScript (Vanilla):** Toda a lógica de cálculo, manipulação de DOM e exportação de dados sem frameworks complexos.
* **Chart.js:** Biblioteca externa utilizada para a renderização dos gráficos no Dashboard.

## 💻 Como Usar

Por ser uma aplicação estática e baseada inteiramente no navegador, a instalação é imediata e não requer a configuração de um ambiente de desenvolvimento ou base de dados.

1. Faça o clone deste repositório ou descarregue os ficheiros para o seu computador.
2. Dê um duplo clique no ficheiro `index.html` para abri-lo em qualquer navegador web moderno.
3. Na janela inicial:
   * Clique em **✨ Novo** para criar um novo registo do zero (informando os seus dados de identificação e unidade).
   * Clique em **📂 Carregar** para importar um ficheiro `.json` guardado anteriormente.
4. Adicione as semanas de trabalho, insira as suas atividades diárias e acompanhe o progresso das suas metas.
5. Ao finalizar as edições, clique em **✔️ Salvar** para exportar o ficheiro `.json` atualizado para a sua máquina.

## 📄 Geração de PDFs

A ferramenta utiliza o recurso nativo de impressão do navegador para gerar PDFs limpos e formatados. Basta clicar em **Relatório desta Semana** dentro de uma semana específica, ou usar as opções de **Resumo de Semanas** e **Semanas Consolidadas** na lista para gerar o documento e escolher a opção "Guardar como PDF" na janela de impressão do seu sistema.
