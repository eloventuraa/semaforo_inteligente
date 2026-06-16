# 🚦 Semáforo Inteligente com Acessibilidade 

Este projeto é a simulação de um **Semáforo Inteligente** focado em inclusão e mobilidade urbana. Através de um **sensor de presença**, o sistema detecta automaticamente quando um pedestre está aguardando na calçada e estende o tempo de travessia em **+25 segundos**, garantindo mais segurança e tranquilidade para pessoas com deficiência visual e pessoas autistas.

---

## 🎯 Por que este projeto é importante?

A travessia de pedestres comum impõe pressa e estímulos que geram barreiras urbanas:

* **Para pessoas com deficiência visual:** O tempo curto e a falta de aviso sonoro geram grande insegurança ao atravessar.
* **Para pessoas autistas:** Ambientes barulhentos, a pressa dos carros e o medo do fechamento repentino do sinal podem causar sobrecarga sensorial e ansiedade.

**A Solução:** Ao eliminar botões ou cartões físicos, o semáforo se torna 100% autônomo. Basta o pedestre se posicionar na área de espera para que o sistema entenda a necessidade de um tempo de travessia maior e acione os bipes sonoros de orientação.

---

## 🚀 Como Funciona na Prática?

1. **Ciclo Padrão:** O semáforo opera normalmente, dividindo o tempo padrão entre carros e pedestres.
2. **Detecção Automática:** O pedestre chega à calçada para atravessar. O **sensor de presença** detecta sua permanência na área de espera.
3. **Travessia Segura:** O sistema ativa o modo de acessibilidade, adicionando automaticamente **25 segundos extras** ao tempo verde do pedestre e ligando o aviso sonoro guiado.

---

## 🏗️ Estrutura da Maquete

O projeto foi montado em uma maquete cenográfica para demonstrar a aplicação real do sistema de forma limpa e organizada:

* **Base da Maquete:** Onde fica guardada a placa **Arduino** e as conexões elétricas, mantendo a superfície limpa.
* **Área de Espera:** Onde fica instalado o **Sensor de Presença** direcionado para a calçada, capturando a chegada do pedestre próximo à faixa.
* **Poste do Semáforo:** Onde ficam instalados os **LEDs** de sinalização visual e o **Buzzer** (alto-falante) que emite os bipes para orientação do pedestre.

---

## 🛠️ Componentes Utilizados

* 1x Placa Arduino
* 1x Protonboard
* 1x Sensor de Presença (Ultrassônico ou Sensor de Movimento PIR)
* 1x Módulo semáforo led para arduino
* 1x Buzzer (para o sinal sonoro de acessibilidade)
* Cabos e resistores para as conexões

---

👥 Equipe do Projeto
O desenvolvimento deste projeto foi realizado pelo seguinte time:

👑 Samilly Matos — Product Owner (P.O)

📋 Vitor Andrade — Scrum Master

💻 Eloísa Ventura — Desenvolvedora

💻 Enzo Ferrari — Desenvolvedor

💻 Tainá Silveira — Desenvolvedora

---

> 💡 *A tecnologia só é verdadeiramente inteligente quando inclui a todos.*
