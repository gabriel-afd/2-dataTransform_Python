Este projeto tem como objetivo automatizar a extração, transformação e compactação de dados da tabela **Rol de Procedimentos e Eventos em Saúde** contida em um PDF da ANS (Agência Nacional de Saúde Suplementar). 

---
---
##  Versão Python (Google Colab)

Foi desenvolvida uma versão deste projeto utilizando **Python** no ambiente **Google Colab**:

### Funcionalidades
- Extração dos dados com `tabula-py`.
- Substituição de siglas `OD` e `AMB`.
- Limpeza e análise de dados nulos.
- Exportação para `.csv`.
- Compactação em `.zip` com `zipfile`.

### Bibliotecas utilizadas
- `tabula-py`
- `pandas`
- `seaborn`
- `matplotlib`
- `zipfile`
- `os`

### Como executar no Google Colab
1. Instale o `tabula-py` com:
```python
!pip install tabula-py
```
2. Faça upload do arquivo PDF para o ambiente
3. Execute o código linha a linha, conforme o notebook.
4. Os arquivos finais `Teste_GabrielMedeiros.zip e tabela.cvs` serão gerados com os dados tratados.

<img src="https://github.com/user-attachments/assets/7ec407fb-4fc9-49e3-bace-3723c2e878f7" width="300"/>   

---

## Autor
**Gabriel Medeiros**
**gmedeiros144@gmail.com**
