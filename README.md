# ProvaD
// validar o checkbox e o contador
EXEMPLO
<input type="checkbox" id="termos_de_contrato"><label for="termos_de_contrato">Afirmo que li todo o contrato</label>
let checkbox = document.getElementById('termos_de_contrato');
if(checkbox.checked) {
    console.log("O cliente marcou o checkbox");
} else {
    console.log("O cliente não marcou o checkbox");
}
