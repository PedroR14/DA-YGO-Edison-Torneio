# Torneio Suíço – Formato Edison

Gerenciador de torneio de Yu-Gi-Oh! no **formato Edison** (lista de março de 2010), feito para lojas e grupos de jogo. Funciona no navegador do celular ou do computador, sem instalar nada e sem servidor.

## Funcionalidades

- **Sistema suíço** com número de rodadas à sua escolha (automático ou de 1 a 10). Dá para fazer, por exemplo, 4 rodadas com 8 jogadores.
- **Emparelhamento:** a 1ª rodada é sorteada. Da 2ª em diante, quem tem a mesma pontuação se enfrenta, sem repetir adversário. O bye vai para o pior colocado que ainda não teve bye.
- **Resultados** em melhor de 3: 2-0, 2-1, empate, 1-2 e 0-2.
- **Desempate** por Pts → OWP → OOWP → GW%.
- **Estatísticas:** MW%, games, GW%, OGW%, vitórias 2-0 e 2-1, byes, histórico por duelista e resumo do torneio.
- **Top cut** de 2, 4, 8 ou 16, com seeds no padrão 1×8, 4×5, 2×7 e 3×6. Também dá para jogar só o suíço.
- **Drop** de jogador, correção de resultados e desfazer rodada.
- **Cadastro de duelistas**, com importação de lista (.txt/.csv ou colando os nomes) e exportação.
- **Histórico de torneios** salvo automaticamente, com registro completo e download em .txt e .csv.
- **Instalável no celular:** é só usar "Adicionar à tela inicial".

Os dados ficam salvos no navegador do aparelho (localStorage). Limpar os dados do navegador apaga o cadastro e o histórico, então exporte quando quiser guardar uma cópia.

## Como publicar no GitHub Pages (grátis)

1. Crie um repositório público no GitHub, por exemplo `torneio-suico-edison`.
2. Envie os arquivos desta pasta para o repositório. Pode ser pelo botão **Add file → Upload files**.
3. Vá em **Settings → Pages**. Em *Source*, escolha **Deploy from a branch**, branch `main` e pasta `/ (root)`. Clique em **Save**.
4. Em cerca de 1 minuto o site fica disponível em `https://SEU-USUARIO.github.io/torneio-suico-edison/`.

## Arquivos

| Arquivo | Para que serve |
|---|---|
| `index.html` | O app inteiro: HTML, CSS e JavaScript num arquivo só |
| `manifest.json` | Permite instalar como app no celular |
| `icon.svg`, `icon-192.png`, `icon-512.png` | Ícones |

## Aviso

Projeto de fã, sem vínculo com a Konami. Yu-Gi-Oh! é marca registrada dos seus respectivos donos. O app não usa logos nem artes oficiais.

## Licença

MIT. Veja o arquivo [LICENSE](LICENSE).
