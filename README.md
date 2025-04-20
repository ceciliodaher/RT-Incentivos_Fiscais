# Simulador de Incentivos Fiscais da Reforma Tributária - IVA Dual (CBS/IBS)

Este simulador implementa as regras do sistema de IVA Dual (CBS/IBS) conforme estabelecido pela Lei Complementar 214/2025, que institui a Reforma Tributária no Brasil. Seu principal diferencial reside na capacidade de modelagem comparativa 
de incentivos fiscais setoriais, permitindo análise detalhada dos 
impactos diferenciais entre o regime atual e o novo sistema que entrará 
em vigor gradualmente a partir de 2026.

## Problemas Conhecidos (Versão 1.0)

A versão atual do simulador apresenta as seguintes limitações técnicas que estão sendo corrigidas para o lançamento da versão 2.0:

**1. Entrada Numérica por Digitação Direta**
O campo de entrada de valores numéricos apresenta inconsistências quando os dados são inseridos via teclado. A solução temporária consiste em utilizar as setas de incremento/decremento disponíveis no controle de entrada até que a correção definitiva seja implementada.

**2. Exportação para PDF**
A funcionalidade de exportação de resultados para formato PDF encontra-se temporariamente indisponível devido a problemas de renderização gráfica. Como alternativa funcional, recomenda-se a utilização da exportação para Excel que opera com total estabilidade.

## Próximas Atualizações (Versão 2.0)

A nova versão em desenvolvimento trará as seguintes correções e melhorias:

### Correções Prioritárias

- **Reformulação do Sistema de Entrada de Dados**
  Substituição completa do componente de entrada numérica para permitir digitação direta sem restrições, mantendo a funcionalidade das setas de ajuste incremental.
- **Integração de Biblioteca PDF**
  Implementação da biblioteca jsPDF para geração de relatórios em PDF com layout otimizado, incluindo gráficos interativos e tabelas formatadas.

### Melhorias Adicionais

- **Sistema de Validação em Tempo Real**
  Adição de verificações automáticas para valores inválidos durante a digitação, com mensagens contextualizadas de erro.
- **Personalização de Relatórios**
  Novas opções para selecionar elementos específicos da simulação a serem incluídos nos relatórios exportados.
- **Histórico de Simulações**
  Implementação de armazenamento local para recuperação de cenários anteriores, com capacidade de comparação lado a lado.

## Cronograma de Lançamento

| Versão | Status | Previsão | Principais Recursos |
| --- | --- | --- | --- |
| 1.0 | Lançada | Abril/2025 | Funcionalidades básicas |
| 1.1 | Em teste | Abril/2025 | Correções de interface |
| 2.0 | Em desenvolvimento | Maio/2025 | Sistema completo de exportação |

## Funcionalidades

### Simulação de Cargas Tributárias

A ferramenta mantém todas as capacidades de cálculo enquanto recebe melhorias de precisão:

- Progressão anual detalhada (2026-2033)
- Comparação lado a lado entre sistemas tributários
- Análise setorial com parâmetros customizáveis

### Exportação de Dados

A funcionalidade estável de exportação para Excel permanece disponível, fornecendo:

- Planilhas estruturadas com fórmulas pré-configuradas
- Gráficos dinâmicos atualizáveis
- Metadados completos da simulação

## Orientação para Usuários Atuais

Enquanto aguardam a atualização para a versão 2.0, os usuários podem:

1. Utilizar controles de seta para ajustes numéricos
2. Exportar resultados intermediários para Excel
3. Reportar quaisquer anomalias via sistema de issues do GitHub
4. Acompanhar o progresso das correções na aba "Projects"

## Como Utilizar

1. **Instalação** 
  Faça download do arquivo `Simulador-RT-Incentivos-Fiscais.html`
  
2. **Execução**  
  Abra o arquivo `Simulador-RT-Incentivos-Fiscais.html` em qualquer navegador moderno.
  
3. **Fluxo Básico**
  
  - Preencha os dados da empresa na aba **Simulação**
  - Ajuste parâmetros na aba **Configurações** (opcional)
  - Clique em **Simular** para gerar projeções
  - Explore resultados em gráficos e tabelas
  - Exporte relatórios em PDF/Excel

## Configuração Personalizada

### Alíquotas Base

```javascript
// Exemplo de configuração programática
const config = {
  CBS: 0.088,   // 8.8%
  IBS: 0.177    // 17.7%
};
```

### Fases de Transição

| Ano | Implementação |
| --- | --- |
| 2026 | 10% |
| 2027 | 25% |
| ... | ... |
| 2033 | 100% |

## Contribuição

Contribuições são bem-vindas! Siga estes passos:

1. Faça um fork do projeto
2. Crie uma branch (`git checkout -b feature/nova-funcionalidade`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova funcionalidade'`)
4. Push para a branch (`git push origin feature/nova-funcionalidade`)
5. Abra um Pull Request

## Licença

Copyright © 2025 [Expertzy Inteligência Tributária](https://www.expertzy.com.br).  
Distribuído sob licença interna. Para uso comercial, consulte os termos de licenciamento.

## Contato

Equipe Expertzy - [contato@expertzy.com.br](mailto:contato@expertzy.com.br)

<div style="text-align: center">⁂</div>

[^1]: https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/8663280/aaf51013-2870-4d1a-83ef-586559abebc1/Simulador-RT-Incentivos-Fiscais.html
