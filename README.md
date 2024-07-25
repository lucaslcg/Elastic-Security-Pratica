# Elastic-Security-Pratica

Prática de deployment e setup de agentes de endpoint e sysmon 

 **loguin** 

![App Screenshot](https://raw.githubusercontent.com/lucaslcg/Elastic-Security-Pratica/main/Elastic-Security-Pratica/Captura%201-1.png)

**Crie Elastic Cloud deployment**

![App Screenshot](https://github.com/lucaslcg/Elastic-Security-Pratica/blob/main/Elastic-Security-Pratica/Captura%201-2.png)

**Escolha um nome**

![App Screenshot](https://github.com/lucaslcg/Elastic-Security-Pratica/blob/main/Elastic-Security-Pratica/Captura%201-3.png)
![App Screenshot](https://github.com/lucaslcg/Elastic-Security-Pratica/blob/main/Elastic-Security-Pratica/Captura%201-4.png)

 **O ambiente ja sugere posiveis integraçoes**
 
![App Screenshot](https://github.com/lucaslcg/Elastic-Security-Pratica/blob/main/Elastic-Security-Pratica/Captura%202-1.png)
![App Screenshot](https://github.com/lucaslcg/Elastic-Security-Pratica/blob/main/Elastic-Security-Pratica/Captura%202-2.png)
![App Screenshot](https://github.com/lucaslcg/Elastic-Security-Pratica/blob/main/Elastic-Security-Pratica/Captura%202-3.png)

**Aqui e feita a instalaçao do Elastic Agent basta abrir o Prompt de Comando colar executar e aguardar a comfirmaçao do êxito**


![App Screenshot](https://github.com/lucaslcg/Elastic-Security-Pratica/blob/main/Elastic-Security-Pratica/Captura%202-4.png)
![App Screenshot](https://github.com/lucaslcg/Elastic-Security-Pratica/blob/main/Elastic-Security-Pratica/Captura%202-5.png)
![App Screenshot](https://github.com/lucaslcg/Elastic-Security-Pratica/blob/main/Elastic-Security-Pratica/Captura%202-6.png)
![App Screenshot](https://github.com/lucaslcg/Elastic-Security-Pratica/blob/main/Elastic-Security-Pratica/Captura%202-7.png)

**Extremamene simples de se fazer**

![App Screenshot](https://github.com/lucaslcg/Elastic-Security-Pratica/blob/main/Elastic-Security-Pratica/Captura%202-8.png)
![App Screenshot](https://github.com/lucaslcg/Elastic-Security-Pratica/blob/main/Elastic-Security-Pratica/Captura%202-9.png)
![App Screenshot](https://github.com/lucaslcg/Elastic-Security-Pratica/blob/main/Elastic-Security-Pratica/Captura%202-10.png)
![App Screenshot](https://github.com/lucaslcg/Elastic-Security-Pratica/blob/main/Elastic-Security-Pratica/Captura%202-11.png)
![App Screenshot](https://github.com/lucaslcg/Elastic-Security-Pratica/blob/main/Elastic-Security-Pratica/Captura%202-12.png)

**Aqui decido por mais um agente no mesmo host com o intuito de dar mais detalhes dos eventos da máquina, me utilizando do System Monitor (Sysmon)**

![App Screenshot](https://github.com/lucaslcg/Elastic-Security-Pratica/blob/main/Elastic-Security-Pratica/Captura%203-1.png)

**Instalo o driver.** 

![App Screenshot](https://github.com/lucaslcg/Elastic-Security-Pratica/blob/main/Elastic-Security-Pratica/Captura%203-2.png)
![App Screenshot](https://github.com/lucaslcg/Elastic-Security-Pratica/blob/main/Elastic-Security-Pratica/Captura%203-3.png)
![App Screenshot](https://github.com/lucaslcg/Elastic-Security-Pratica/blob/main/Elastic-Security-Pratica/Captura%203-4.png)

**escolho o agente que da suporte ao Sysmon**

![App Screenshot](https://github.com/lucaslcg/Elastic-Security-Pratica/blob/main/Elastic-Security-Pratica/Captura%203-5.png)
![App Screenshot](https://github.com/lucaslcg/Elastic-Security-Pratica/blob/main/Elastic-Security-Pratica/Captura%203-6.png)
![App Screenshot](https://github.com/lucaslcg/Elastic-Security-Pratica/blob/main/Elastic-Security-Pratica/Captura%203-7.png)

**aqui que esta o detalhe e posivel usar o mesmo host pra mais de un agete ajustando esta comfiguraçoa no agente**

![App Screenshot](https://github.com/lucaslcg/Elastic-Security-Pratica/blob/main/Elastic-Security-Pratica/Captura%203-8.png)
![App Screenshot](https://github.com/lucaslcg/Elastic-Security-Pratica/blob/main/Elastic-Security-Pratica/Captura%203-9.png)

**assim setamos um endpoint com um pouco mais de detalhes para o SIEM**
