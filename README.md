# 📦 Sistema de Inventário Automatizado de Hardware

Sistema desktop para **logística e controle de ativos de TI**, desenvolvido em Python com interface gráfica. Permite gerenciar entradas e saídas de equipamentos, registrar tickets de pedidos e acompanhar o estoque em tempo real por meio de gráficos interativos.

---

## ✨ Funcionalidades

- **Listagem de ativos** separados por categoria (periféricos e notebooks), carregados automaticamente de uma planilha Excel
- **Registro de movimentações** de entrada e saída com quantidade, motivo e número de ticket
- **Atualização automática do estoque** na planilha após cada movimentação
- **Log completo** de todas as operações com timestamp, garantindo rastreabilidade e auditoria
- **Gráficos interativos** de movimentações por produto, data e categoria (barras, pizza e pirâmide)
- **Exportação de gráficos** para Excel
- **Gestão de ativos** com registro de marca, BP e número serial de notebooks

---

## 🛠️ Tecnologias

- **Python 3**
- **Tkinter** — interface gráfica desktop
- **pandas** — leitura e manipulação de dados da planilha
- **openpyxl** — escrita e exportação para Excel
- **matplotlib** — geração de gráficos de movimentação

---

## 🚀 Como usar

**1. Clone o repositório**
```bash
git clone https://github.com/Guilherme-das-Chagas/Inventario_automatizado.git
cd Inventario_automatizado
```

**2. Instale as dependências**
```bash
pip install pandas openpyxl matplotlib
```

**3. Execute o sistema**
```bash
python automatizacao_inventario.py
```

**4. Selecione sua planilha Excel** quando solicitado. A planilha deve conter as colunas `Produto` e `Quantidade`.

---

## 📊 Exemplo de uso

1. Carregue a planilha com os ativos cadastrados
2. Selecione o equipamento e informe a quantidade e o número do ticket
3. Registre a entrada ou saída — o estoque é atualizado automaticamente
4. Acesse "Gráficos e Filtros" para visualizar o histórico de movimentações

---

## 📁 Estrutura

```
├── automatizacao_inventario.py   # Aplicação principal
├── Book 1.xlsx                   # Planilha de exemplo
├── inventario_log.txt            # Log de movimentações (gerado automaticamente)
```

---

## 👤 Autor

**Guilherme Henrique das Chagas**  
[LinkedIn](https://www.linkedin.com/in/guilherme-henrique-das-chagas) • [GitHub](https://github.com/Guilherme-das-Chagas)
