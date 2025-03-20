# 🔒 **Sistema de Cadastro Biométrico com Arduino**  

Sistema de controle de acesso utilizando um **leitor biométrico autônomo**, capaz de armazenar e autenticar até **240 digitais** sem a necessidade de um banco de dados externo.  

## 🚀 **Tecnologias Utilizadas**  

- **Arduino (UNO, Mega, etc.)** – Processamento e controle do sistema  
- **Leitor Biométrico (FPS/FPM)** – Armazenamento e autenticação de digitais  
- **C (Arduino IDE)** – Programação do firmware  
- **LCD 16x2 (Opcional)** – Exibição de mensagens ao usuário  
- **Buzzer (Opcional)** – Feedback sonoro para ações  

---

## ⚠️ **Demonstração**

📹 Digital não cadastrada [Clique aqui para ver a demonstração](caminho/do/video.mp4)
📹 Digital cadastrando [Clique aqui para ver a demonstração](caminho/do/video.mp4)
📹 Digital cadastrada [Clique aqui para ver a demonstração](caminho/do/video.mp4)

---
## 🎯 **Funcionalidades**  

✅ **Cadastro e armazenamento de digitais** no próprio sensor  
✅ **Autenticação biométrica** sem uso de banco de dados externo  
✅ **Exibição de mensagens no monitor serial ou LCD**  
✅ **Indicação sonora e visual** para sucesso ou erro na leitura  
✅ **Capacidade para armazenar até 240 impressões digitais**  

---

## 🛠 **Configuração e Instalação**  

### **1️⃣ Configuração do Hardware**  
**Conexões do leitor biométrico (FPS/FPM)** com Arduino:  

| Leitor Biométrico | Arduino Uno |  
|-------------------|-------------|  
| VCC              | 5V          |  
| GND              | GND         |  
| TX              | RX (pino 2)  |  
| RX              | TX (pino 3)  |  

⚠️ **Atenção:** Caso utilize um **Arduino Mega**, os pinos podem ser diferentes.  

---

### **2️⃣ Configuração do Código**  
1️⃣ Instale a **IDE do Arduino**: [Download aqui](https://www.arduino.cc/en/software)  
2️⃣ Instale a **biblioteca do leitor biométrico**:  
   - Acesse **Gerenciador de Bibliotecas** na IDE  
   - Busque por **Adafruit Fingerprint Sensor Library**  
   - Instale a biblioteca  

3️⃣ **Carregue o código no Arduino** a partir do arquivo disponível no repositório.  

---

## ⚠️ **Possíveis Erros e Soluções**  

❌ **"Leitor biométrico não detectado"**  
🔹 Verifique as conexões **RX e TX**.  
🔹 Confira se o leitor está alimentado corretamente (5V).  

❌ **"Erro ao cadastrar digital"**  
🔹 Certifique-se de que **não há digitais repetidas**.  
🔹 Mantenha o dedo firme sobre o sensor ao cadastrar.  

❌ **"A digital não está sendo reconhecida"**  
🔹 O dedo pode estar sujo ou úmido. Tente novamente.  
🔹 Cadastre novamente a digital e teste.  

---

## 📜 **Licença e Direitos Autorais**  

Este projeto é **open-source**, mas exige **atribuição de crédito** ao autor para qualquer uso, modificação ou distribuição.  

🔹 **Permitido**:  
- Uso e modificação **com créditos ao autor**.  
- Melhorias e contribuições para o projeto.  

🔸 **Proibido**:  
- Remover créditos do autor.  
- Revender ou redistribuir sem permissão.  

---

## 🤝 **Contribuindo**  

Se quiser contribuir com melhorias:  
1️⃣ Faça um **fork** do repositório  
2️⃣ Crie um **branch** com sua funcionalidade:  
   ```bash
   git checkout -b minha-nova-feature
   ```  
3️⃣ Faça o **commit** das mudanças:  
   ```bash
   git commit -m "Adicionando nova feature"
   ```  
4️⃣ Envie um **pull request**  

---

## 📩 **Contato**  

📧 Desenvolvedor 1 - Email: jonathanrenanborges@gmail.com  
🌐 Portfólio: https://portfolio-jonathanborgess.netlify.app/
📧 Desenvolvedor 2 - Email: joaogabrielvasques16@gmail.com


Se gostou do projeto, deixe uma ⭐ no repositório! 🚀🔒  
