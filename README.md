<h1>🚀 CI/CD com GitHub Actions</h1>

<p>
Este repositório contém exemplos práticos de <b>pipelines CI/CD utilizando GitHub Actions</b>, 
abordando desde conceitos básicos até variações mais avançadas, como 
<b>triggers personalizados, secrets, variables, workflows com dependências, matriz de builds, condicionais e gerenciamento de erros</b>.
</p>

<p>
O objetivo é servir como um guia de aprendizado e referência para implementar 
<b>integração contínua (CI)</b> e <b>entrega contínua (CD)</b> em projetos de diferentes contextos.
</p>

<hr/>

<h2>📌 Conteúdo do Repositório</h2>

<h3>🔹 Triggers</h3>
<ul>
  <li>Execução por <b>push</b> e <b>pull_request</b></li>
  <li><b>Agendamento</b> com <code>cron</code></li>
  <li>Execução <b>manual</b> com <code>workflow_dispatch</code></li>
  <li><b>Triggers condicionais</b> baseados em branches, paths e tags</li>
</ul>

<h3>🔹 Secrets & Variables</h3>
<ul>
  <li>Uso de <b>GitHub Secrets</b> para armazenar credenciais sensíveis</li>
  <li>Definição de <b>variáveis de ambiente</b> no workflow</li>
  <li>Boas práticas de <b>segurança no gerenciamento de informações</b></li>
</ul>

<h3>🔹 Workflows Avançados</h3>
<ul>
  <li><b>Dependências entre jobs</b> (<code>needs</code>)</li>
  <li><b>Estratégias de matriz</b> (<code>matrix</code>) para múltiplas versões e ambientes</li>
  <li><b>Condicionais</b> (<code>if</code>) para controlar a execução de jobs e steps</li>
  <li><b>Retry e continue-on-error</b> para gerenciamento de falhas</li>
  <li><b>Notificações e feedbacks</b> no fluxo de execução</li>
</ul>
