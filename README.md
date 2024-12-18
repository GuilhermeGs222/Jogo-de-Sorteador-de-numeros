<h1>Aplicativo do Sorteador de Numero</h1>

<h2> Sobre</h2>
<p>O aplicativo web é uma ferramenta simples e interativa que permite ao usuário sortear múltiplos números aleatórios dentro de um intervalo personalizado. A página contém três campos principais para interação:

Quantidade de Números: O usuário define quantos números aleatórios deseja sortear.
Do Número: O valor mínimo do intervalo de sorteio.
Até o Número: O valor máximo do intervalo de sorteio.
Ao clicar no botão "Sortear", o programa gera a quantidade de números aleatórios solicitada dentro do intervalo definido e exibe os números sorteados na tela. A lógica de programação é feita com HTML para a estrutura, CSS para a estilização, e JavaScript para a lógica de sorteio e interação com os campos.

Além do botão "Sortear", o aplicativo também possui um botão "Reiniciar". Esse botão permite que o usuário limpe os resultados exibidos e redefine os campos de entrada para novos valores, proporcionando uma experiência contínua de sorteio, sem a necessidade de recarregar a página.

Lógica de Validação
Uma parte importante da lógica do aplicativo envolve garantir que o número de sorteios solicitado não seja maior do que o intervalo de números disponíveis. O código a seguir faz essa verificação:

javascript
Copiar código
if (quantidade > (ate - de + 1)) {
    alert('Campo "Quantidade" deve ser menor ou igual ao intervalo informado no campo "Do número" até o campo "Até o número". Verifique!');
    return;
}
Essa função verifica se a quantidade de números solicitada é maior do que o intervalo possível entre o valor "do número" (início) e o valor "até o número" (fim). A condição (ate - de + 1) calcula o número total de valores disponíveis dentro do intervalo, incluindo ambos os extremos. Se a quantidade solicitada for maior que esse número, o aplicativo exibe um alerta pedindo que o usuário verifique os campos, garantindo que o número de sorteios não exceda o intervalo disponível.

Essa validação ajuda a evitar erros de sorteio, garantindo que o processo seja executado de forma lógica e consistente.</p>

## Tecnologias
<div>
  <img src="https://img.shields.io/badge/HTML-239120?style=for-the-badge&logo=html5&logoColor=white">
  <img src="https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
</div>

## Time
<table>
  <tr>
    <td><img src="https://avatars.githubusercontent.com/u/190558110?s=400&u=e062922b9714d10dd0b94f0ba755dcb1ba908948&v=4" width="100" alt="Sua Foto"></td>
    <td>GuilhermeSioz</td>
  </tr>
</table>
