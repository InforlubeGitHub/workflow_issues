# workflow_issues

Vou te ajudar a criar um workflow do GitHub Actions que automatiza o gerenciamento de labels para issues. Vou mostrar dois exemplos: um para criar labels automaticamente e outro para aplicar labels baseado em regras.
1. Criar Labels Automaticamente
Crie um arquivo .github/workflows/manage-labels.yml:
Apply to project-base...
2. Aplicar Labels Automaticamente em Issues
Crie um arquivo .github/workflows/auto-label-issues.yml:
Apply to project-base...
3. Workflow para Label Baseado em Templates
Crie um arquivo .github/workflows/template-based-labels.yml:
Apply to project-base...
4. Workflow para Label Baseado em Projetos
Crie um arquivo .github/workflows/project-based-labels.yml:
Apply to project-base...
Como usar:
Crie a pasta .github/workflows/ no seu repositório
Adicione os arquivos de workflow que desejar
Faça commit e push para o repositório
Exemplos de Templates de Issue
Para complementar, você pode criar templates de issue em .github/ISSUE_TEMPLATE/:
bug_report.md:
Apply to project-base...
feature_request.md:
Apply to project-base...
Dicas de Uso:
Personalização:
Ajuste as cores e descrições das labels conforme necessário
Modifique as regras de auto-labeling de acordo com suas necessidades
Adicione ou remova labels conforme seu fluxo de trabalho
Segurança:
Use secrets.GITHUB_TOKEN para autenticação
Considere usar tokens personalizados para ações mais específicas
Manutenção:
Mantenha as labels organizadas e com propósito claro
Documente o significado de cada label
Revise periodicamente as regras de auto-labeling
Boas Práticas:
Use cores consistentes para labels relacionadas
Mantenha nomes de labels curtos e descritivos
Use prefixos para agrupar labels relacionadas (ex: priority:, type:)
Se precisar de ajuda para personalizar alguma dessas configurações ou tiver dúvidas específicas, me avise!
