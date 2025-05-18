# Projeto-Alura-Goldfish
# 🐟 **Goldfish** - Seu Consultor de Negócios Inteligente  

**Transformando regiões e habilidades em oportunidades reais**  

---

## ✨ **O que é o Goldfish?**  
Um chatbot **poderoso e direto** que ajuda jovens empreendedores a:  
✅ **Descobrir oportunidades** adaptadas à sua região  
✅ **Validar ideias** com dados reais e análise de mercado  
✅ **Criar planos** executáveis com os recursos disponíveis  

Inspirado na filosofia do *"goldfish que só cresce fora da zona de conforto"* 🐟➡️🐠  

---

## 🚀 **Como Usar (em 3 Passos)**  

1. **Preparação**  
   ```python
   !pip install google-generativeai google-api-python-client
   ```
   - Adicione sua API Key do Google AI Studio como `GOOGLE_API_KEY` nas Secrets do Colab  

2. **Fluxo do Assistente**  
   - O Goldfish guiará você por 5 etapas:  
     1. 📍 **Localização** (cidade, economia local)  
     2. 🛠️ **Habilidades** (seus talentos e interesses)  
     3. 🔍 **Viabilidade** (demanda, concorrência)  
     4. 💎 **Refinamento** (top 5 ideias com prós/contras)  
     5. 🚀 **Plano de Ação** (passo a passo inicial)  

3. **Comandos Úteis**  
   - `"sair"`: Encerra a conversa  
   - `"[BUSCA]termo"`: Solicita dados em tempo real *(ex: "[BUSCA]mercado de artesanato em SP")*  

---

## 🔥 **Por Que Goldfish?**  
- **Cresce com você**: Assim como o peixe dourado, seu negócio só se expande quando você sai do "aquário pequeno"  
- **Linguagem jovem**, mas com **dados sólidos** (nada de conselhos vagos!)  
- **Foco em realidade local**: oportunidades que fazem sentido *para você*  

---

## 🌟 **Exemplo de Saída**  
```  
🐟 Goldfish: "Beleza, você tem talento com doces e mora no interior de MG...  
   💡 Sugiro: 1. Kit festa caipira, 2. Geleias artesanais com frutas da região  
   🔍 [BUSCA]preço médio do kg de goiabada em Minas Gerais..."  
```  

---

## 📂 **Estrutura do Código**  
```  
goldfish.py  
├── Configuração do Gemini 2.0 Flash  
├── Sistema de buscas no Google (opcional)  
├── Fluxo conversacional em 5 etapas  
└── Tratamento de erros automático  
```  

---

## 💡 **Intenção do Projeto**  
Democratizar **acesso a análise de mercado inteligente** para:  
- Quem quer empreender mas não sabe por onde começar  
- Negócios que precisam se adaptar à realidade local  
- Jovens que querem fugir de "receitas prontas" e criar algo único  

---

**👉 Rodando em 1 minuto no Google Colab:**  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/seuuser/goldfish/blob/main/goldfish.ipynb)  

*"Todo mundo pode ser empreendedor, mas só os adaptáveis viram donos do próprio oceano."* 🌊💛  

---  
*(Documentação atualizada em: 17/05/2025)*  

> ✨ **Dica**: Personalize o `system_instruction` para focar em nichos específicos (ex: "Goldfish Agro" para negócios rurais).
