# MANUAL DE SEGURANÇA DA INFORMAÇÃO CRUZEIROGAMES

Este manual foi desenvolvido para orientar todos os colaboradores da CruzeiroGames de Desenvolvimento de Jogos Digitais sobre as melhores práticas de segurança e conformidade com a Lei Geral de Proteção de Dados (LGPD).

## 1. Entendendo a LGPD (Lei 13.709/2018)

A LGPD é a lei brasileira que regulamenta o tratamento de dados pessoais. Ela não serve para "proibir" o uso de dados, mas para garantir que o usuário tenha controle sobre suas informações.

**Como a lei funciona?**

A lei se baseia no princípio de que o dado pertence ao indivíduo e não à empresa. Para tratar um dado (coletar, armazenar, editar ou excluir), precisamos de uma base legal, como o <ins>consentimento do jogador ou a execução de um contrato.</ins>

**Os 3 Pilares da LGPD no Desenvolvimento de Jogos:**

- **Finalidade:** Devemos coletar <ins>apenas</ins> o que é estritamente necessário para o jogo funcionar.
- **Transparência:** O jogador deve saber exatamente o que estamos fazendo com os dados dele.
- **Segurança:** <ins>Somos responsáveis por proteger esses dados</ins> contra acessos não autorizados ou vazamentos.

## 2. Segurança no Desenvolvimento

Segurança não é algo que adicionamos ao final do projeto; ela deve nascer com o código.

- **Minimização de Dados:** Se o jogo não precisa do CPF ou da localização exata do usuário para funcionar, <ins>não colete.</ins>
- **Anonimização:** Sempre que possível, utilize técnicas para que um dado não possa ser vinculado a um indivíduo específico, especialmente em análises de telemetria e comportamento de jogo.
- **Ambientes Seguros:** Nunca utilize dados reais de usuários em ambientes de teste. Utilize dados fictícios.

## 3. Cuidados no Dia a Dia do Colaborador

A maior parte das brechas de segurança ocorre por falhas humanas. Siga estas diretrizes:

**Gestão de Acessos e Senhas**

- **Autenticação de Dois Fatores (2FA):** Obrigatório em todas as contas.
- **Gerenciadores de Senhas:** Proibido anotar senhas em post-its ou arquivos de texto sem criptografia. Utilize o gerenciador corporativo.
- **Bloqueio de Tela:** Ao se afastar da sua mesa de trabalho certifique-se de bloquear o usuário, mesmo que tenha somente amigos por perto.

**Comunicação e Compartilhamento**

- **Código Fonte:** Nunca suba chaves de API, tokens ou credenciais de banco de dados para repositórios públicos ou mesmo privados sem proteção de variáveis de ambiente.
- **Phishing:** Desconfie de e-mails ou mensagens externas pedindo acesso a documentos. Na dúvida, reporte ao time de TI.

## 4. Proteção da Propriedade Intelectual

Em uma empresa de games, o vazamento do roteiro pode destruir anos de investimento.

1. **Acordo de Confidencialidade:** Lembre-se que seu contrato inclui cláusulas de sigilo sobre projetos não anunciados.
2. **Redes Sociais:** Não publique fotos do seu setup de trabalho se houver telas visíveis com código, artes conceituais ou ferramentas internas.
3. **Dispositivos Externos:** O uso de pen drives ou HDs externos não autorizados é estritamente proibido nas máquinas de desenvolvimento.

## 5. O que fazer em caso de Incidentes?

Se você suspeitar que sua conta foi invadida, que perdeu um equipamento da empresa ou que houve um acesso indevido a dados de usuários:

1. **Mantenha a calma:** O erro humano acontece, mas a omissão é grave.
2. **Notifique imediatamente:** Entre em contato com o time de Segurança da Informação.
3. **Não tente "consertar" sozinho:** Isso pode apagar rastros importantes para a investigação.

##

**Lembre-se:** A segurança da informação é uma responsabilidade compartilhada. Um código seguro e um comportamento consciente protegem não apenas a empresa, mas a experiência de **TODOS.**
