# 🎯 Edital de Mercado - Diagnóstico de Maturidade Digital

Aplicação de diagnóstico completo para avaliar o potencial de transformar sua estrutura atual em receita com o **Sistema S** (Sebrae e instituições similares).

## ✨ Funcionalidades

- ✅ **Formulário Inicial** - Coleta nome e contexto do usuário
- ✅ **28 Perguntas Estratégicas** - 7 áreas com 4 perguntas cada
- ✅ **Sliders Interativos** - Escala de 0 a 10 com feedback visual
- ✅ **Navegação por Áreas** - Uma categoria por vez com transições suaves
- ✅ **Score Geral e por Área** - Percentuais com classificação automática
- ✅ **Gráfico de Barras** - Comparativo visual entre áreas
- ✅ **Gráfico Radar 360°** - Visão completa do negócio vs ideal
- ✅ **Análise Detalhada** - Prioridades, oportunidades e pontos fortes
- ✅ **Próximos Passos** - Recomendações estratégicas
- ✅ **Geração de PDF** - Download do relatório completo
- ✅ **Nova Avaliação** - Reiniciar diagnóstico
- ✅ **Design Premium** - Tema escuro azul profissional
- ✅ **Mobile-First** - Otimizado para todos os dispositivos

## 📊 As 7 Áreas Avaliadas

1. **Potencial de Impacto** (4 perguntas)
   - Avalia ativos digitais aplicados ao modelo institucional

2. **Potencial de Negócio** (4 perguntas)
   - Mede o canal institucional como novo fluxo de receita

3. **Estrutura de Oferta** (4 perguntas)
   - Analisa adaptação do produto para compra institucional

4. **Potencial de Escala** (4 perguntas)
   - Avalia crescimento com menos esforço de aquisição

5. **Atração de Clientes Institucionais** (4 perguntas)
   - Mede prontidão para ser referência no Sistema S

6. **Estratégia de Venda para o Sistema S** (4 perguntas)
   - Analisa domínio dos caminhos de contratação

7. **Demanda e Urgência** (4 perguntas)
   - Mede oportunidades perdidas no mercado institucional

## 🎨 Design

### Paleta de Cores
- **#0a1628** - Azul escuro (background principal)
- **#1a2744** - Azul card (cards)
- **#3b82f6** - Azul primary (destaques)
- **#10b981** - Verde (excelente/sucesso)
- **#f59e0b** - Amarelo (oportunidade/moderado)
- **#ef4444** - Vermelho (crítico/prioridade)
- **#ffffff** - Branco (textos)

### Tipografia
- **Sora** - Títulos e destaques
- **Outfit** - Textos e interface

## 📈 Referência de Pontuação

| Percentual | Classificação | Cor |
|------------|---------------|-----|
| 81-100% | Ponto Forte | 🟢 Verde |
| 61-80% | Bom | 🟢 Verde claro |
| 41-60% | Oportunidade | 🟡 Amarelo |
| 21-40% | Atenção | 🟠 Laranja |
| 0-20% | Prioridade | 🔴 Vermelho |

## 🚀 Deploy

### Netlify (Recomendado)

1. **Fork ou clone o repositório**
2. **Conecte ao Netlify:**
   - Acesse [netlify.com](https://netlify.com)
   - "New site from Git"
   - Selecione o repositório
   - Deploy automático!

### Deploy Manual

1. Faça download dos arquivos
2. Arraste para o Netlify Drop
3. Pronto!

## 🔧 Personalização

### Alterar Cores
No `index.html`, encontre as variáveis CSS no `:root`:

```css
:root {
    --bg-primary: #0a1628;
    --blue-primary: #3b82f6;
    /* ... outras cores */
}
```

### Alterar Perguntas
No JavaScript, encontre o array `areas` e edite as `questions`:

```javascript
const areas = [
    {
        id: 'potencial_impacto',
        name: 'Potencial de Impacto',
        questions: [
            'Sua pergunta aqui...',
            // ...
        ]
    },
    // ...
];
```

## 📱 Recursos

- **Sliders** - Arrastar de 0 a 10 para cada pergunta
- **Navegação** - Voltar/Avançar entre áreas
- **Gráficos** - Chart.js para visualizações
- **PDF** - html2pdf.js para geração do relatório

## 📄 Licença

Desenvolvido para o programa Edital de Mercado - Sistema S.

---

**Desenvolvido com 💙 para transformar negócios digitais em fornecedores institucionais**
