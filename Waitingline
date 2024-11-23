let nomes = [];
let pacientes = []
let remaining = []
let number = 0
let choice = 0

nomes = ['José', 'Carlos', 'Manuel', 'Conceição']
for (let i = 0; i < nomes.length; i++) {
    number += 1
    pacientes.push("Senha " + number + " : " + nomes[i])
}
while(choice !== "3"){
    alert('Olá, seja bem vindo ao Consultório do Dr. Roberto!')

    choice = prompt('Atualmente, temos nas fila os seguintes pacientes: ' + pacientes.join(', ') + '\n O que você deseja fazer? \n\n1)Novo Paciente \n2)Consultar um paciente \n3)Sair ')

    if(choice === "1"){
        const novoPaciente = prompt('Ah, qual o nome do paciente:\n')
        paciente = "Senha " + (pacientes.length + remaining.length + 1) + ' : ' +  novoPaciente
        pacientes.push(paciente)
    }

    if(choice === "2")
    {
        if(pacientes){
            alert('"' + pacientes[0] + '. O Dr. Roberto já está lhe chamando. Pode ir na sala ao lado!"\n\n')
            remaining.push(pacientes[0])
            pacientes.shift()
        } else {
            alert('Não há mais ninguém na fila!')
        }
    }

}

alert('Finalizando o programa')
