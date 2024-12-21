# 💻 Cibersecurity: Desafio Ransomware  

Este repositório contém um exemplo de código utilizado para criptografia de arquivos como parte de um **desafio de cibersegurança**. A finalidade é **educativa**, voltada para o estudo de proteção contra ataques ransomware e compreensão de suas técnicas. ⚠️ **Use este código de forma ética e responsável.**

---

## 🛠️ Pré-requisitos  
Certifique-se de ter instalado no ambiente:  
- **Python 3.6+**  
- Módulo `pyaes` (instruções abaixo)  
- Sistema Linux ou compatível  

---

## 💻 Como usar  
1. **Crie um arquivo-alvo:**  
   - No terminal, execute:  
     ```bash
     nano teste.txt
     ```  
   - Adicione algum conteúdo ao arquivo e salve (`Ctrl+O` e `Ctrl+X`).  

2. **Configure o ambiente:**  
   - Caso o módulo `pyaes` não esteja instalado, configure-o:  
     ```bash
     python3 -m pip install pyaes
     ```

3. **Execute o script `encrypter.py`:**  
   - No terminal, rode o código de criptografia:  
     ```bash
     python3 encrypter.py
     ```  
   - Digitando o comando `ls` podemos ver arquivo `teste.txt` será apagado e surgirá um novo arquivo com nome `teste.txt.ransowaretroll` com conteudo criptografado.  

4. **Execute o script** `decrypter.py`
   - No terminal, rode o código de descriptografia
     ```bash
     python decrypter.py
     ```
   - O arquivo `teste.txt.ransowaretroll` irá ser apagado e o `teste.txt` voltar novamente com o conteudo legível 
---


