# Simulação de Malware com Python

## 📌 Sobre o projeto

Projeto desenvolvido para o desafio da **DIO (Digital Innovation One)**, com o objetivo de compreender o funcionamento de ameaças digitais por meio de simulações seguras em Python.

O projeto aborda conceitos de ransomware e keylogger de forma educacional, destacando os riscos envolvidos e a importância das medidas de prevenção e defesa na segurança da informação.

## 🎯 Objetivos

- Compreender conceitos básicos sobre malwares.
- Estudar os riscos associados a ransomware e keyloggers.
- Praticar programação com Python.
- Conhecer medidas de prevenção e proteção contra ameaças digitais.

## 🛠️ Tecnologias utilizadas

- Python 3
- Visual Studio Code
- Terminal ou PowerShell
- Ambiente de testes controlado

## 🔬 Simulações

- **Ransomware:** demonstração controlada do conceito de criptografia usando arquivos fictícios de teste.
- **Keylogger:** demonstração educacional da captura de teclas, restrita a entradas explícitas de teste, sem monitoramento oculto ou envio de dados a terceiros.

## ▶️ Instruções de execução segura

### 1. Preparar o ambiente

Instale o Python 3 a partir do site oficial:

https://www.python.org/downloads/

Verifique se a instalação foi concluída:

```bash
python --version
```

### 2. Baixar o projeto

Clone o repositório ou baixe os arquivos do projeto. No terminal, acesse a pasta correspondente:

```bash
cd nome-do-projeto
```

### 3. Criar um ambiente virtual

Crie um ambiente virtual para manter as dependências isoladas:

```bash
python -m venv .venv
```

Ative-o no Windows PowerShell:

```powershell
.\.venv\Scripts\Activate.ps1
```

No Linux:

```bash
source .venv/bin/activate
```

### 4. Preparar os arquivos de teste

- Crie uma pasta exclusiva para os experimentos, como `arquivos_teste`.
- Utilize somente arquivos fictícios, sem informações pessoais.
- Mantenha cópias de segurança fora da pasta de experimentação.
- Não execute testes em documentos reais, pastas do sistema ou unidades compartilhadas.

### 5. Executar as simulações

Execute somente os scripts revisados e compreendidos:

```bash
python nome_do_script.py
```

Substitua `nome_do_script.py` pelo nome real do arquivo Python do projeto.

Antes da execução, confirme que o código está limitado aos arquivos de teste e que não possui funções de monitoramento oculto, persistência, exclusão de dados ou transmissão automática de informações.

### 6. Encerrar o ambiente

Ao concluir os testes, desative o ambiente virtual:

```bash
deactivate
```

Se houver qualquer comportamento inesperado, interrompa a execução e não utilize o script em outros sistemas.

## 🛡️ Boas práticas de segurança

- Prefira uma máquina virtual isolada, sem acesso a arquivos pessoais.
- Desative o compartilhamento de pastas e a área de transferência com o sistema principal durante os testes.
- Não execute scripts com privilégios de administrador ou root.
- Não utilize dados reais ou dispositivos de terceiros.
- Não envie informações capturadas para servidores externos.
- Revise o código antes de executá-lo.

## 📚 Aprendizados

- Fundamentos de Python aplicados à segurança da informação.
- Funcionamento conceitual de ransomware e keyloggers.
- Importância do isolamento de ambientes de teste.
- Medidas de prevenção e defesa contra malwares.

## 👨‍💻 Autor

Projeto desenvolvido como parte dos desafios educacionais da DIO.

---

**Aviso:** Este projeto possui finalidade exclusivamente educacional. Execute os experimentos apenas em ambientes próprios e autorizados.
