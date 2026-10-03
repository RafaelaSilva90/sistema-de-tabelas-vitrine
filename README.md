# 📊 Sistema de Tabelas

Aplicação web que transforma planilhas de cálculos financeiros de um setor de pagamento de pessoal em um sistema único, rápido e confiável, com demonstrativos prontos em PDF.

> 🔒 Este repositório é uma **vitrine**: o sistema está em uso real por uma equipe, então o código-fonte é privado. Todos os prints usam dados fictícios.

## 🎯 O problema

Os cálculos do setor (rescisões, substituições, progressões e outros acertos financeiros) eram feitos em várias planilhas separadas. Isso tomava tempo, aumentava o risco de erros e dificultava a padronização dos documentos.

## 💡 A solução

Um sistema web que reúne todos esses cálculos em um só lugar:

- Cálculos automáticos com base na legislação vigente
- Demonstrativos em PDF gerados no formato oficial, prontos para anexar aos processos
- Leitura automática de PDFs do sistema de folha, preenchendo dados sem digitação
- Cronograma da folha com contagem regressiva para o fechamento
- Login com Google e controle de acesso por aprovação
- Nenhum armazenamento de dados sensíveis: os cálculos são feitos na hora e o PDF é baixado localmente

## 🛠️ Tecnologias

React · TypeScript · Vite · Supabase · Git · Vercel (deploy automático a cada atualização)

## 🖼️ Telas do sistema

### Acesso e painel

![Tela de login](prints/vitrine-01-login.png)
![Painel inicial com cronograma da folha](prints/vitrine-02-painel.png)

### Rescisões

![Formulário de rescisão](prints/vitrine-03-rescisao-formulario.png)
![Memorial de cálculos da rescisão](prints/vitrine-04-rescisao-memorial.png)

### Pagamento de substituição

![Cálculo de substituição](prints/vitrine-05-substituicao-calculo.png)
![Demonstrativo em PDF](prints/vitrine-06-substituicao-pdf.png)

### Outros módulos

![Progressões funcionais com leitura automática de PDF](prints/vitrine-07-progressoes.png)
![Cálculo de auxílio-transporte](prints/vitrine-08-auxilio-transporte.png)

## 🚧 Status

Em uso e em evolução contínua, com novos módulos sendo adicionados conforme as necessidades da equipe.

---

Desenvolvido por [Rafaela Silva](https://github.com/RafaelaSilva90) 💜
