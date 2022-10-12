# IA UAM

Repositório com os conteúdos da aula. Se alguém quiser subir algo, basta me avisar que eu libero.

## Fuzzy
---
Para conseguir executar o fuzzy, será necessário instalar 3 dependências:

| Biblioteca | URL |
| ---------- | --- |
| Matplotlib | https://matplotlib.org/ |
| Scikit-fuzzy | https://pythonhosted.org/scikit-fuzzy/overview.html |
| NumPy | https://numpy.org/ |

---

Para instalar as bibliotecas, siga o seguinte passo a passo:

1. Inicie um ambiente virtual para não bagunçar o seu ambiente. Execute o seguinte comando:
    - `python -m venv ./venv`
2. Agora, dependendo do seu sistema operacional execute:
    - | OS | Comando |
      | -- | ------- |
      | Linux/MacOS | `source venv/bin/activate` |
      | Windows | `venv/Scripts/activate.ps1` |
3. Instale as dependencias, executando:
    - `pip install -r requirements.txt`
4. Pronto, as bibliotecas estão instaladas!

**Obs.: Isso apenas se rodar na máquina local.**

### Configuração no VS Code

Para utilizar no VS Code, você pode ter que selecionar o ambiente python, faça isso da seguinte forma:

1. Abra o notebook (fuzzy.ipynb)
2. No canto superior direito, clique para selecionar o ambiente
    - ![Selecionar ambiente](/imagens/interpretador.png)
3. Selecione o ambiente `venv`
    - ![Selecionar venv](/imagens/venv.png)
4. Pronto! O Jupyter já deve identificar o ambiente virtual

---

