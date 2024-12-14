# desafio-cybersecurity-santander-phishing
Este é um desafio proposto pelo Bootcamp Cybersecurity Santander, onde a gente precisa demonstrar o uso da ferramenta Setoolkit usando phishing para captura de senhas do Facebook.

# Simulação de Phishing para Captura de Credenciais do Facebook

## Introdução

Este projeto consiste em uma simulação de phishing educacional utilizando o Kali Linux e o Social-Engineer Toolkit (SET). O objetivo é aprender sobre técnicas de engenharia social e como elas podem ser usadas em ataques de cibersegurança, sempre em um ambiente controlado e ético. Este repositório documenta o processo, incluindo as ferramentas utilizadas, as etapas de configuração e os resultados obtidos.

> **Nota:** Este projeto é exclusivamente para fins educacionais. Não use essas técnicas para atividades maliciosas. O uso indevido pode ter implicações legais.

---

## Ferramentas Utilizadas

- **Sistema Operacional:** Kali Linux
- **Ferramenta Principal:** Social-Engineer Toolkit (SET)

---

## Pré-requisitos

1. **Kali Linux instalado:** Certifique-se de que o Kali Linux esteja devidamente configurado.
2. **Acesso root:** Muitas das ferramentas requerem permissões administrativas.
3. **Conexão de rede ativa:** Necessário para hospedar o site clonado.

---

## Passo a Passo da Configuração

### 1. Acessar o SET

- Abra o terminal no Kali Linux.
- Torne-se root usando o comando:
  ```bash
  sudo su
  ```
- Inicie o Social-Engineer Toolkit:
  ```bash
  setoolkit
  ```

### 2. Escolher o Tipo de Ataque

- No menu principal do SET, escolha:
  ```
  1) Social-Engineering Attacks
  ```

### 3. Escolher o Vetor de Ataque

- No submenu, escolha:
  ```
  2) Website Attack Vectors
  ```

### 4. Escolher o Método de Ataque

- No próximo submenu, escolha:
  ```
  3) Credential Harvester Attack Method
  ```

### 5. Clonar o Site

- Escolha a opção "Site Cloner".
- Insira o endereço URL do site a ser clonado (por exemplo, Facebook):
  ```
  http://www.facebook.com
  ```

### 6. Configurar a Máquina

- Obtenha o endereço IP da máquina com o comando:
  ```bash
  ifconfig
  ```
- Use o IP retornado para configurar o servidor local do SET.

### 7. Iniciar o Ataque Simulado

- Após configurar, o SET iniciará um servidor local para hospedar o site clonado.
- Quando uma vítima em potencial acessar o site falso, as credenciais inseridas serão registradas no terminal do SET.

---

## Resultados

- As credenciais capturadas serão exibidas no terminal.
- **Exemplo:**
  ```
![image](https://github.com/user-attachments/assets/d3648089-c2f4-4294-86ae-82fb72879c7b)

  ```


## Considerações Éticas

Este projeto deve ser usado apenas para aprendizado e conscientização. Sempre realize esses testes em ambientes controlados e com permissão explícita. O uso irresponsável dessas técnicas é ilegal e antiético.

---
