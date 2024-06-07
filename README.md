# DAGitty DAGs:
## Code to parse an exported Tikz DAG model into Dagitty DAG model. 

- For those who have chosen "Save Model as Tikz Code" and wish to reload into [Dagitty](https://www.dagitty.net/dags.html)

## How to Use
<table>
  <tr>
    <td>
      <h1>1. Make DAG</h1>
      <img src="https://github.com/pmdscully/DagittyDAGs/assets/3637403/16f6a1db-43c2-4e24-91bd-897e0a813063" width="400px"/>
    </td>
    <td>
      <h1>2. Export to TIKZ</h1>
      <img src="https://github.com/pmdscully/DagittyDAGs/assets/3637403/9416cdde-b2fa-4230-af22-c77a3a6cbd88" width="350px"/>
    </td>
  </tr>
  <tr>
    <td>
      <h1>3. Convert Tikz to DAGitty</h1>
      <ol>
        <li>
        Paste in your Tikz code nodes and edges into this tool. <a href="https://colab.research.google.com/drive/1XQopJki5su_BFDreTBMJNFtuaRe46YLy?usp=sharing">e.g. in colab</a>
        </li>
        <li>
          Copy the output DAGitty model code back into DAGitty (bottom right), and press "Update DAG".
        </li>
      </ol>
    </td>
    <td>
      <h1>4. Import into DAGitty</h1>
      <img src="https://github.com/pmdscully/DagittyDAGs/assets/3637403/93e4cc3a-37da-4e61-af5d-0d2919be758e" width="250px"/>
    </td>
  </tr>
</table>

## Example Notebook on Google Colab:
Just paste in your Tikz code nodes and edges:
[Google Colab notebook](https://colab.research.google.com/drive/1XQopJki5su_BFDreTBMJNFtuaRe46YLy?usp=sharing)

## Limits:
- Currently will parse the following variable types: `exposure`, `outcome`, `adjusted`. However you will have to specify `selected` and `unobserved` variables within your loaded DAG. (It is quite easy to update the code if you prefer).
