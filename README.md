# Participantes
- Ana Zerlin         RM98065
- Bianca Dancs       RM551645
- Gabriel Pimentel   RM99880
- Hellen Assis       RM98284

# O que é
<div align="justify">Este projeto foi criado para monitorar os gases inflamáveis nos galpões utilizados pela Urbitável, onde o lixo é armazenado e separado antes de ser encaminhado para a unidade principal de descarte, visando garantir a segurança dos funcionários. As estações de separação de lixo estão localizadas em bairros residenciais, facilitando o acesso da população. Como esses galpões abrigam diferentes tipos de resíduos, alguns altamente inflamáveis, é crucial contar com um sistema de detecção de gases inflamáveis para assegurar uma resposta rápida por parte do corpo de bombeiros.</div>

# Recursos necessários para a implementação
- Sensor de Gás MQ-2, para verificar a presença de gases inflamáveis nos galpões e em que concentração se encontram;
- ESP32, tornando a conexão por WI-FI entre o sistema operacional e o sensor possível;
- IoT, conecta com o ESP32 e recebe as informações dadas pelo medidor;
- Lâmpada ou led, alerta visual;
- Campainha ou buzzer(maiores proporções do que de um protótipo), aviso sonoro.

# Protocolo de funcionamento
1. O sensor estará coletando informações sobre o ambiente a todo momento;
2. Esses dados são passados para o sistema principal através do ESP32(WI-FI);
3. Os números recebidos serão analizados e determinarão se é necessário ou não iniciar a operação para ventilação e evacuação do prédio;
   -  O sistema chega a uma conclusão a partir de um cógido dentro dele, introduzido posteriormente, e criado seguindo instruções de especialistas em segurança;
4. Caso a quantidade de gases inflamáveis no ambiente seja maior do que a norma considerada segura para esses espaços, as luzes e campainhas ligarão;
5. O corpo de bombeiros será acionado automaticamente pelo próprio sistema, para fazer uma inspeção e garantir a segurança de todos;
6. Um operador/funcionário da unidade, responsável pelo monitoramento do sistema de segurança, irá abrir as ventilções do galpão enquanto o corpo de bombeiros não chega;
7. Após a avaliação dos especialistas, o líder da unidade irá decidir se as operações voltarão no dia ou irão ser encerradas até que seja seguro.

![Foto da demonstração de como o sistema funciona](Demonstra%C3%A7%C3%A3o.jpg)

## Demonstração do funcionamento
[Link da demonstração do funcionamento do sistema de alarme de forma simplificada(sem o ESP32)](https://www.tinkercad.com/things/9rcP97f9xNt)

### Vídeo sobre IoT :
[YOUTUBE](https://youtu.be/dfqplwQoEUk)
