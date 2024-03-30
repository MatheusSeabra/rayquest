### Atividade RayCast
  Link atividade https://drive.google.com/file/d/11OsVVTQVgXOay87jK7GR_ooPj9OkYfAQ/view<br>
  Alunos: Matheus Seabra, Erick Felipe Mendes Galvez<br>
  Fizemos esses  scrips para realizar essa atividade<br>
  ![image](https://github.com/MatheusSeabra/rayquest/assets/101134295/e2336948-d629-42e3-a3a7-69b198059c9b)<br>
==============================================================================================================================<br>
  ### Bullet<br>
  ![image](https://github.com/MatheusSeabra/rayquest/assets/101134295/0e9f2e5c-ca09-400b-b8db-4d810a9a347f)<BR>
este código controla a física do projétil e detecta colisões com outros objetos, permitindo que o jogo saiba quando o projétil atingiu um alvo ou saiu do mundo do jogo.<br>
==============================================================================================================================<br>
### FirstPersonCamera<br>
![image](https://github.com/MatheusSeabra/rayquest/assets/101134295/e02c151c-a0bc-4f61-b0b5-9a94ce44092f)<br>
![image](https://github.com/MatheusSeabra/rayquest/assets/101134295/024e9ab6-c9ea-4069-a53c-bd5f6c8ae5c9)
![image](https://github.com/MatheusSeabra/rayquest/assets/101134295/29324553-d767-41af-a2fb-b0cd80f6fe1d)
![image](https://github.com/MatheusSeabra/rayquest/assets/101134295/ad587006-5054-47fc-a0c9-9b72a99db35f)<br>
esse código roda uma câmera na perspectiva de primeira pessoa, permitindo que o jogador olhe em diferentes direções ao mover o mouse. Os movimentos da câmera são suavizados para evitar movimentos bruscos.<br>
==============================================================================================================================<br>
### Gun<br>
![image](https://github.com/MatheusSeabra/rayquest/assets/101134295/515ad52c-4078-40da-8d40-a1b07b892d9c)
![image](https://github.com/MatheusSeabra/rayquest/assets/101134295/48673b42-86a8-478e-bdda-640de46b4371)<br>
![image](https://github.com/MatheusSeabra/rayquest/assets/101134295/1176163f-c479-4929-a00c-07f44a9e2fb0)
![image](https://github.com/MatheusSeabra/rayquest/assets/101134295/a6c3f953-c076-4407-946f-edd0df3eccf0)
![image](https://github.com/MatheusSeabra/rayquest/assets/101134295/d2cd107b-858d-4e4e-a7ea-1503b9d98489)<br>

controla o disparo da arma em um jogo, instanciando e disparando um projétil na direção do primeiro objeto que o Raycast atinge. O script também contém componentes para a animação do disparo, o som do disparo, e efeitos do disparo.<br>
==============================================================================================================================<br>
### IShotHit<br>
![image](https://github.com/MatheusSeabra/rayquest/assets/101134295/0b11e6fc-ff11-4d1a-ba25-11acd6985f42)<br>

declara uma interface IShotHit que define um método Hit que todos os objetos que implementam a interface devem ter.<br>
A interface IShotHit é usada na classe Bullet, onde o objeto é destruído quando colide com um objeto que implementa a interface IShotHit.<br>
==============================================================================================================================<br>
### Player<br>
![image](https://github.com/MatheusSeabra/rayquest/assets/101134295/c8dd5a28-4e00-4aa3-9866-7a15804e77ef)
![image](https://github.com/MatheusSeabra/rayquest/assets/101134295/c4cfc933-93b9-4c7b-8af4-e6f5fdac1086)
![image](https://github.com/MatheusSeabra/rayquest/assets/101134295/d7c8b4f4-39e8-45a2-af73-80086f998c2c)<br>

Este código é um motor de jogo Unity, o qual controla o movimento de um personagem do jogo<br>
==============================================================================================================================<br>
### Shell<br>
![image](https://github.com/MatheusSeabra/rayquest/assets/101134295/1373ac11-0950-49d9-aebd-abecc1ff0816)<br>
responsável pelo movimento de algum objeto que representa uma "casca" de algum projétil. O objeto é instanciado com uma velocidade inicial aleatória e aumenta sua velocidade vertical pela gravidade a cada frame. A velocidade horizontal é definida pela direção do objeto, multiplicada pela velocidade inicial com um pequeno desvio aleatório para dar um efeito mais realista.<br>
==============================================================================================================================<br>
### Tin<br>
![image](https://github.com/MatheusSeabra/rayquest/assets/101134295/f1bacbcd-7d5d-4b39-9f4e-716493ea519e)<br>
Este código define uma classe Tin que herda da classe MonoBehaviour e implementa a interface IShotHit.<br>

Nesse trabalho inteiro aprendemos alguns scripts significativos para quando formos fazer nosso tcc utilizarmos e ser bem útil

![Screenshot 2024-03-29 121403](https://github.com/MatheusSeabra/rayquest/assets/101134295/db8f4563-d9db-4b6e-8175-642e0b5e9ac8)<br>
Pistola de BANANA, pegamos esse object dos assents do unity para demonstrar o raycast. <br>
![image](https://github.com/MatheusSeabra/rayquest/assets/101134295/20c60379-b667-412f-8f45-620b7dddf537)<br>
Cenario ( tiro ao alvo ), pegamos esses objects dos assents do unity para demonstrar o funcionamento do raycast.<br>
https://youtu.be/R6pYdtUekqg<br>
Uma desmonstração de como ficou a gameplay
