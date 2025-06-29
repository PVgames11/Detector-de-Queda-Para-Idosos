# Detector-de-Queda-Para-Idosos
Este projeto consiste no desenvolvimento de um protótipo funcional para detectar quedas em pessoas idosas, utilizando tecnologias de Internet das Coisas (IoT), com o objetivo de melhorar o tempo de resposta em situações de emergência. O sistema é baseado em uma plataforma com Arduino ESP32, sensores de movimento e um módulo GPS, que envia alertas automaticamente ao cuidador via aplicativo Blynk e e-mail.

## Objetivo

O objetivo principal deste projeto é aumentar a segurança de pessoas idosas por meio de um sistema de detecção de quedas que notifica o cuidador em tempo real, incluindo a localização geográfica do evento. O sistema visa ser acessível, eficiente e de fácil utilização, atuando como um suporte à autonomia e qualidade de vida do idoso.

## Parte Interessada
O principal público-alvo são idosos com idade superior a 65 anos, especialmente mulheres, que apresentam maior expectativa de vida. O projeto também considerou como parte interessada um cuidador (William Natal), que acompanhou o desenvolvimento do sistema como representante direto de uma idosa com necessidades específicas. Sua participação foi fundamental para validar a funcionalidade do protótipo.

## Problemática
Quedas são uma das principais causas de hospitalizações e óbitos entre idosos. Muitos desses acidentes ocorrem sem que haja assistência imediata, o que agrava as consequências. O projeto busca solucionar a dificuldade de identificar quedas rapidamente e acionar ajuda em tempo hábil.

## Justificativa
Soluções disponíveis no mercado, como pulseiras inteligentes, são frequentemente inacessíveis devido ao custo elevado. Além disso, esses dispositivos nem sempre são adequados ao perfil físico ou comportamental dos idosos. O sistema desenvolvido propõe uma alternativa mais acessível, utilizando componentes de baixo custo e amplamente disponíveis.

## Programas Utlizados
.Arduino IDE

.Blynk IoT

.Gmail

## Peças e Componentes Utilizados
.ESP32 com Wi-Fi e Bluetooth (30 pinos)

.Protoboard 830 pontos e 400 pontos

.Jumpers macho/macho e macho/fêmea

.Sensor de movimento MPU-6050 (acelerômetro e giroscópio)

.Módulo GPS NEO 6M com antena

.Fita dupla face e base de isopor

.Cabo USB para alimentação e programação

Custo total estimado: R$ 236,65

## Funcionamento do Sistema
O sensor MPU-6050 detecta movimentações bruscas (quedas).

O ESP32 processa as informações e solicita a localização via GPS NEO 6M.

Os dados são enviados ao aplicativo Blynk e ao e-mail do cuidador.

A localização é transmitida via coordenadas GPS e visualização no Blynk.

## Estrutura do Código
Leitura contínua dos sensores de aceleração e rotação.

Condicional para identificar padrões típicos de queda.

Validação de sinal do GPS.

Envio da localização via link do Google Maps.

Notificação instantânea no Blynk e por e-mail.

## Desenvolvimento
O projeto foi realizado por quatro alunos da Universidade Estácio de Sá, com reuniões presenciais e online, além de fases de testes práticos em ambiente real. Foram necessárias várias iterações para correção de falhas, ajustes nos sensores e testes de conectividade.

Responsabilidades
.Lucas Pereira: desenvolvimento do código e testes.

.Nínive Guimarães: montagem do circuito e comunicação com o stakeholder.

.Gabriel Roif: testes do protótipo e correção de erros.

.Paulo Vitor Quintanilha: aquisição de componentes, soldagem e supervisão geral.

.André Przewodowski Filho:professor responsável por ministrar a matéria de  Aplic. de Cloud, Iot e Indústria 4.0 em Python na Universidade Estácio de Sá

## Melhorias Futuras
Implementar envio de alertas via WhatsApp.

Tornar o dispositivo mais compacto (por exemplo, integrá-lo em uma pulseira).

Garantir que o sistema funcione mesmo em ambientes fechados com sinal GPS fraco (com uso de antenas externas).

Enviar localização em tempo real com atualização contínua.

## Considerações Finais
O projeto demonstrou ser viável como protótipo funcional, com grande potencial para desenvolvimento futuro. A solução representa uma contribuição prática para a segurança da população idosa, promovendo a aplicação de conhecimentos técnicos em benefício da sociedade.

## Licença
Este projeto foi desenvolvido com fins educacionais e não possui, neste momento, licença comercial.
