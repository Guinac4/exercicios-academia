# exercicios-academia
Exercícios de academia 
#--------------------------------✿----------------------------------------------------------------✿--------------------------------
from datetime import date
data_atual = date.today()
data_atual = '{}/{}/{}'.format (data_atual.day, data_atual.month,data_atual.year)
from datetime import date
today = date.today()
today = '{}/{}/{}'.format (today.month,today.day, today.year)
#--------------------------------✿----------------------------------------------------------------✿--------------------------------
costas = 'costas'
peito = 'peito'
braco = 'braço'
perna = 'perna'
barriga = 'barriga'
sair = 'sair'
opt = int
back = 'back'
chest = 'chest'
arm = 'arm'
leg = 'leg'
belly = 'belly'
ex = 'ex'
#--------------------------------✿----------------------------------------------------------------✿
opt = int(input('Escolha o Idioma | Chose language\n' 
             f'1 - Português | 2 English : '))
if (opt == 1):
    print('--------------------------------✿--------------------------------\n'
      f"                         {data_atual}\n"
      f"           Exercícios para Iniciantes e Intermedíarios \n"
      f"                  Nunca é tarde para Desistir\n"
      '--------------------------------✿--------------------------------')
#--------------------------------✿----------------------------------------------------------------✿
    print('                     -- ! Vamos Treinar ! -- \n'
      f'Digite qual das regioes do corpo você gostaria de treinar hoje.\n'
      f'          |COSTAS| |PEITO| |BARRIGA| |BRAÇO| |PERNA| \n'
      f'             Digite Sair para Finalizar o programa')
    print('--------------------------------✿--------------------------------')
    while (sair):
        exer = (input('Digite aqui: '))
        if (exer == costas):
            print('Para as Costas recomendamos:\n'
            f'\n'
            f'\n'
            f'1° - Trapézio (Músculo Superior Central) \n'
            f'⤥ Cruxifixo Inverso 2x12 (2 séries de 12 repetições) \n'
            f'\n'
            f'2° - Dorsal (Músculos laterais Inferiores) \n'
            f'⤥ Cross Over 3x8 (3 séries de 8 repetições) \n'
            f'\n'
            f'3° - Deltoide Posterior (Músculo Superior Lateral)  \n'
            f'⤥ Remada Curva 3x8 (3 séries de 8 repetições) \n'
            f'\n'
            f'')
        elif (exer == peito):
            print('Para o Peito recomendamos:\n'
            f'\n'
            f'1° - Superior (Músculo da Parte Superior) \n'
            f'⤥ Supino Inclinado 2x10 (2 séries de 10 repetições) \n'
            f'\n'
            f'2° - Medial (Músculo na Parte Média) \n'
            f'⤥ Supino Reto 2x8 (2 séries de 8 repetições) \n'
            f'\n'
            f'3° - Inferior (Músculo da Parte Baixa)  \n'
            f'⤥ Supino Declinado 2x10 (2 séries 10 repetições) \n'
            f'\n'
            f'')
        elif (exer == braco):
            print('Para o braço recomendamos:\n'
            f'\n'
            f'1° - Deltoide (Músculo dos Ombros) \n'
            f'⤥ Elevação Lateral 2x6 (2 séries 6 repetições) \n'
            f'\n'
            f'2° - Biceps (Músculo entre o Ombro e Cotovelo) \n'
            f'⤥ Rosca Barra W 3x8 (3 séries 8 repetições) \n'
            f'\n'
            f'3° - Triceps (Músculo Posterior do Braço)  \n'
            f'⤥ Rosca Francesa (2 séries 10 repetições) \n'
            f'\n'
            f'')
        elif (exer == perna):
            print('Para a perna recomendamos:\n'
            f'\n'
            f'1° - Gluteos (Musculo Posterior da Perna) \n'
            f'⤥ Leg Press: 2x12 (2 séries 12 repetições) \n'
            f'\n'
            f'2° - Coxa (Músculo Superior da Perna) \n'
            f'⤥ Maquina Adutora 2x8 (2 séries 8 repetições) \n'
            f'\n'
            f'3° - Panturilha (Músculo inferior da Perna)  \n'
            f'⤥ Cadeira Flexora 2x8 (2 séries 8 repetições) \n'
            f'\n'
            f'')
        elif (exer == barriga):
            print('Temos exercicios para: \n'
            f'\n'
            f'Abdobem (Músculo Central da Barriga) \n'
            f'Abdominal 3x15 (3 séries de 15 repetições)'
            f'\n'
            f'Oblíquo (Músculos Laterais Inferiores do Abdobem)\n'
            f'Flexao lateral 3x10 (3 séries de 15 repetições)\n'
            f'')
        elif (exer == sair):
            print('Finalizando o programa. . .')
            break
elif (opt == 2):
    print('--------------------------------✿--------------------------------\n'
      f"                         {today}\n"
      f"           Exercises for Beginners and Intermediates \n"
      f"                  It's never too late to give up\n"
      '--------------------------------✿--------------------------------')
#--------------------------------✿----------------------------------------------------------------✿
    print('                     -- ! Lets practice ! -- \n'
      f'Enter which body region you would like to train today.\n'
      f'          |BACK| |CHEST| |BELLY| |ARM| |LEG| \n'
      f'            Type Exit to end the program')
    print('--------------------------------✿--------------------------------')
    while (ex):
        exer = (input('Type here: '))
        if (exer == back):
            print('For the Coasts we recommend:\n'
          f'\n'
          f'\n'
          f'1° - Trapezius (Upper Central Muscle) \n'
          f'⤥ Reverse Cruxifix 2x12 (2 sets of 12 repetitions) \n'
          f'\n'
          f'2° - Dorsalis (Lower lateral muscles) \n'
          f'⤥ Cross Over 3x8 (3 sets of 8 repetitions) \n'
          f'\n'
          f'3° - Posterior Deltoid (Upper Lateral Muscle) \n'
          f'⤥ Bent Row 3x8 (3 sets of 8 repetitions) \n'
          f'\n'
          f'')
        elif (exer == chest):
            print('For the Chest we recommend:\n'
          f'\n'
          f'1° - Superior (Upper Part Muscle) \n'
          f'⤥ Incline Bench Press 2x10 (2 sets of 10 repetitions) \n'
          f'\n'
          f'2° - Medial (Muscle in the Middle Part) \n'
          f'⤥ Bench Press 2x8 (2 sets of 8 repetitions) \n'
          f'\n'
          f'3° - Inferior (Lower Part Muscle) \n'
          f'⤥ Decline Bench Press 2x10 (2 sets 10 repetitions) \n'
          f'\n'
          f'')
        elif (exer == arm):
            print('For the arm we recommend:\n'
          f'\n'
          f'1° - Deltoid (Shoulder Muscle) \n'
          f'⤥ Lateral Raise 2x6 (2 sets 6 repetitions) \n'
          f'\n'
          f'2° - Biceps (Muscle between the Shoulder and Elbow) \n'
          f'⤥ Bar Curl W 3x8 (3 sets 8 repetitions) \n'
          f'\n'
          f'3° - Triceps (Back Muscle of the Arm) \n'
          f'⤥ French Curl (2 sets 10 repetitions) \n'
          f'\n'
          f'')
        elif (exer == leg):
            print('For the leg we recommend:\n'
          f'\n'
          f'1° - Gluteus (Posterior Leg Muscle) \n'
          f'⤥ Leg Press: 2x12 (2 sets 12 reps) \n'
          f'\n'
          f'2° - Thigh (Upper Leg Muscle) \n'
          f'⤥ Adductor Machine 2x8 (2 sets 8 repetitions) \n'
          f'\n'
          f'3° - Calf (Lower Leg Muscle) \n'
          f'⤥ Flexor Chair 2x8 (2 sets 8 repetitions) \n'
          f'\n'
          f'')
        elif (exer == belly):
            print('We have exercises for: \n'
          f'\n'
          f'Abdobem (Central Belly Muscle)\n'
          f'Abdominal 3x15 (3 sets of 15 repetitions)'
          f'\n'
          f'Obliques (Lower Lateral Muscles of the Abdobem)\n'
          f'Lateral flexion 3x10 (3 sets of 15 repetitions)\n'
          f'')
        elif (exer == ex):
            print('Finishing the program. . .')
            break
