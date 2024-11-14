<p align="center">
  <b>🚧 Projeto em construção... 🚧</b>
</p>

##

# 🚀 Automação de Extração de Dados de Relatórios de Exposição Ocupacional

## 📑 Índice

- [Objetivo do Projeto](#objetivo-do-projeto)
- [Funcionalidades Implementadas](#funcionalidades-implementadas)
- [Telas de Saídas](#telas-de-saídas)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Como Utilizar](#como_utilizar)
- [Resultados e Conclusão](#resultados-e-conclusão)
- [Autora](#autora)

## <a name="objetivo-do-projeto"></a> 🎯 Objetivo do Projeto

Este projeto foi desenvolvido para resolver um problema comum e altamente repetitivo em minha função atual, onde atuo na manipulação de dados relacionados à exposição ocupacional a riscos químicos. Com frequência, recebemos relatórios de análises laboratoriais que precisam ser processados e incluídos em planilhas para a geração automatizada de pareceres técnicos. Inicialmente, esse processo era feito manualmente, exigindo que cada dado fosse digitado em uma planilha — uma tarefa que se torna extremamente cansativa quando lidamos com um número elevado de relatórios.

Diante do aumento no volume desses relatórios, percebi que uma solução manual não era mais viável, pois em situações de alto fluxo, eu precisava processar até 100 relatórios, o que consumia muito tempo. Para otimizar esse processo, decidi desenvolver um script em Python que automatizasse a extração de dados dos PDFs desses relatórios, reduzindo uma tarefa de horas para segundos.

Este projeto é meu primeiro trabalho independente em automação de dados e representa uma combinação de estudos autodidatas em análise de dados e uma aplicação direta para resolver um problema real no ambiente de trabalho.

## <a name="funcionalidades-implementadas"></a> ⚙️ Funcionalidades Implementadas

- **📄 Extração automática de dados de PDFs:** Utiliza o `pdfplumber` para extrair informações de relatórios laboratoriais.
- **💻 Gerenciamento de dados com input do usuário:** Solicita ao usuário o diretório de origem dos arquivos e o nome dos arquivos de saída, permitindo flexibilidade e eliminando a necessidade de alterações no código.
- **📊 Saída dos dados em Excel e CSV:** Os dados extraídos são organizados e salvos automaticamente em planilhas Excel e arquivos CSV, facilitando o uso posterior e integrando-se facilmente a outros sistemas.
- **📝 Tratamento de erros e logs:** Qualquer erro encontrado durante o processamento é registrado no arquivo de saída, permitindo o acompanhamento do que foi ou não processado corretamente.

## <a name="telas-de-saídas"></a> 🖥️ Telas de Saídas

XXX

## <a name="tecnologias-utilizadas"></a> 🛠️ Tecnologias Utilizadas

- **🐍 Python 3**
- **📄 pdfplumber** - Para extração de texto de arquivos PDF
- **📊 openpyxl** - Para manipulação de arquivos Excel
- **📁 csv** - Para gravação de dados em arquivos CSV

## <a name="como_utilizar"></a> 🏁 Como Utilizar

1. **🔧 Instale as dependências** com `pip install -r requirements.txt`.
2. **🚀 Execute o script**:
   ```bash
   python reader_pdf_locale.py
   ```
3. **📥 Siga as instruções do script**:
   - Insira o diretório onde os PDFs estão armazenados.
   - Escolha os nomes dos arquivos de saída (Excel e CSV).
4. **📂 Verifique os arquivos de saída** no mesmo diretório do script ou conforme especificado pelo usuário.

## <a name="resultados-e-conclusão"></a> 📊 Resultados e Conclusão

Nos meus cinco anos trabalhando com dados de segurança ocupacional, observei como processos manuais, apesar de precisos, podem se tornar um gargalo quando o volume de trabalho aumenta. Meu objetivo com esse projeto era encontrar uma maneira de automatizar a inserção de dados para que, além de poupar tempo, a empresa tivesse uma solução que reduzisse possíveis erros humanos e mantivesse a qualidade dos registros.

Esse projeto já me permitiu processar 120 relatórios em poucos segundos, uma economia de tempo significativa e uma melhoria notável na produtividade. Além disso, ele beneficiará o estagiário que assumirá parte dessas tarefas, proporcionando um fluxo de trabalho simplificado e eficiente. Com o tempo, espero aprimorar e adicionar novas funcionalidades a este script, continuando a contribuir para a eficiência e a organização da equipe.

Embora o projeto já esteja totalmente funcional, estou sempre buscando melhorias, tanto na otimização do código quanto na adição de novas funcionalidades, para atender ainda mais as necessidades da equipe e da empresa.

## <a name="autora"></a> 👩‍💻 Autora

Este projeto foi desenvolvido por **Bárbara Rocha**, estudante do curso de Engenharia de Software. O projeto foi realizado como parte de um trabalho prático, com o objetivo de aplicar e aprofundar os conhecimentos adquiridos sobre manipulação de dados e automação de tarefas. A solução foi construída utilizando **Python** e bibliotecas como **pdfplumber**, **openpyxl** e **csv**, com foco na automação da extração de dados de relatórios laboratoriais e sua organização em planilhas.

A principal motivação foi otimizar um processo manual repetitivo, reduzindo significativamente o tempo gasto e o risco de erros humanos, além de aprimorar as habilidades de automação e análise de dados.
