# 📚 Sistema de Gestão de Horários Escolares

Um site moderno e funcional para gerenciar horários de aulas em escolas.

## 🎯 Funcionalidades

### 1. **Visualizar Horários** 📅
- Visualize todos os horários de aulas de forma organizada
- Filtre por turma e dia da semana
- Veja informações completas: professor, matéria, sala e observações
- Design de cards responsivo e intuitivo

### 2. **Adicionar Aula** ➕
- Formulário completo para criar novos horários
- Campos obrigatórios: dia, horário, turma, professor, matéria e sala
- Campo opcional para observações
- Validação automática de dados

### 3. **Gerenciar Aulas** ⚙️
- Tabela com todos os horários cadastrados
- Editar horários existentes
- Deletar aulas com confirmação de segurança
- Opção de limpar todos os dados

## 📋 Como Usar

### Acessar o Site
1. Abra o arquivo `index.html` em um navegador web
2. Ou execute um servidor local:
   ```bash
   python -m http.server 8000
   ```
   E acesse: http://localhost:8000

### Adicionar uma Aula
1. Clique em "➕ Adicionar Aula"
2. Preencha os campos obrigatórios:
   - Dia da semana
   - Horário de início (formato HH:MM)
   - Duração em minutos
   - Turma
   - Professor(a)
   - Matéria/Disciplina
   - Sala de aula
3. Opcionalmente, adicione observações
4. Clique em "Adicionar Aula"

### Visualizar Horários
1. Clique em "📅 Horários"
2. Use os filtros para:
   - Selecionar uma turma específica
   - Filtrar por dia da semana
3. Clique em "Limpar Filtros" para ver todos

### Editar uma Aula
1. Vá para "⚙️ Gerenciar"
2. Encontre a aula que deseja editar
3. Clique no botão "✏️ Editar"
4. Modifique os dados na janela que aparecerá
5. Clique "Salvar Alterações"

### Deletar uma Aula
1. Vá para "⚙️ Gerenciar"
2. Encontre a aula que deseja remover
3. Clique no botão "🗑️ Deletar"
4. Confirme a exclusão

## 💾 Armazenamento de Dados

- ✅ Todos os dados são armazenados localmente no navegador (localStorage)
- ✅ Os dados persistem mesmo após fechar e reabrir o navegador
- ✅ Não há necessidade de servidor ou banco de dados
- ⚠️ Os dados são específicos do navegador/computador

## 🎨 Design

- Interface limpa e moderna
- Paleta de cores profissional
- Totalmente responsivo (funciona em celulares, tablets e desktops)
- Animações suaves e transições agradáveis
- Menu de navegação fixo para fácil acesso

## 📱 Compatibilidade

- ✅ Chrome, Firefox, Safari, Edge
- ✅ Tablets e dispositivos móveis
- ✅ Funciona offline

## 🔧 Arquivos

- `index.html` - Estrutura HTML do site
- `style.css` - Estilos e design responsivo
- `script.js` - Lógica e funcionalidades
- `README.md` - Este arquivo

## 💡 Dicas

- Use uma nomenclatura consistente para turmas (ex: "1º A", "2º B")
- Adicione observações para aulas especiais ou mudanças
- O sistema detecta automaticamente todas as turmas para o filtro
- Os horários são ordenados por dia e hora automaticamente

## 📝 Exemplo de Dados

Turma: 1º A
Professor: Maria Silva
Matéria: Matemática
Sala: Sala 01
Dia: Segunda-feira
Horário: 08:00
Duração: 50 minutos

## 🚀 Próximas Melhorias Possíveis

- Exportar dados em PDF ou Excel
- Importar dados de arquivo
- Detectar conflitos de horários
- Sistema de backup automático
- Múltiplos usuários/escolas
- Calendário visual

---

**Desenvolvido para facilitar a gestão de horários escolares** 📚✨
