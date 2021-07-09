<!DOCTYPE html>
<html lang="pt-br">
<head>
    <title>Exemplo</title>
    <link href="desig.css" rel="stylesheet">
</head>
<body>
        <button>Explicação</button>
          <br>
          <div>
              <strong>O código feito tem como função inserir um usuário, e caso ele já tenho sido utilizado, será mandado uma
                mensagem dizendo isso. Caso contrário ele será inserido e no código seguinte imprimira todos os usuários.</strong> 
            </div>
            <br>
            <button>Código</button>
  <br>
  <div>
              <strong>usuarios={'Eduardo':['09/06/2002','maq5'],
                  <br>
                  &nbsp &nbsp &nbsp    'Luiz':['15/10/2203','maq4'],
                <br>
                &nbsp &nbsp &nbsp     'Gustavo':['23/11/2000','maq6']}
        <br>
        usu = input('Digite um nome: ')
        <br>
        if usu not in usuarios.keys():
        <br>
        &nbsp &nbsp &nbsp        data = input('Digite uma data: ')
                <br>
                &nbsp &nbsp &nbsp        maq = input('Digite uma máquina: ')
                <br>
                &nbsp &nbsp &nbsp        usuarios[usu] = [data, maq]
                <br>
                &nbsp &nbsp &nbsp        print(usuarios)
                <br>
        else:
        <br>
        &nbsp &nbsp &nbsp    print('Usuário já existe!')
            <br>
        print('\n')
        <br>
        for chave in usuarios.keys():
        <br>
        &nbsp &nbsp &nbsp        print('Usuários: ', chave)</strong> 
              </div>
            </div>
          </div>
        </div>
        <br>
</body>
</html>
