# ObraFácil

Controle de diárias de funcionários da construção civil — app web em um único arquivo (`index.html`), sem servidor e sem instalação.

**Diárias:** https://diogenesjardim.github.io/obrafacil/  
**Orçamentos:** https://diogenesjardim.github.io/obrafacil/orcamento/

## Funções
- Cadastro de trabalhadores e obras
- Marcar dia (um toque) e lançar vários dias de uma vez
- Vale, pagamento e acerto (dias − vales − pagamentos)
- Gastos ADM (café, almoço, gasolina, material) por trabalhador e por obra
- Resumo, relatório para PDF e exportação CSV
- Backup e importação em JSON

## Importante
Os dados ficam salvos **somente no navegador do aparelho** (localStorage). Faça backup em ⚙️ → Exportar backup com frequência.

No iPhone: abra o link no Safari → Compartilhar → **Adicionar à Tela de Início**, e use sempre pelo ícone.

## Orçamentos (`/orcamento/`)
- Orçamento com itens de mão de obra e material, desconto, validade, pagamento e prazo
- Tabela de preços que se preenche sozinha com o último preço usado
- PDF com logo e dados da empresa, e envio pelo WhatsApp
- Status: rascunho, enviado, aprovado, recusado
