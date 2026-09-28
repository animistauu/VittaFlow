# VittaFlow — Requisitos do MVP

## Perfis de acesso
- Usuário comum: registra e consulta os próprios hábitos, seleciona profissionais e consulta feedbacks.
- Profissional: consulta usuários vinculados, gráficos e registros; registra feedback; não altera, exclui ou atualiza os registros do usuário.

## Requisitos Funcionais
- RF01 — Autenticação e identificação do tipo de perfil.
- RF02 — Dashboard do usuário com água, sono, passos, exercícios e evolução.
- RF03 — Usuário pesquisa e seleciona profissionais.
- RF04 — Usuário consulta dados do profissional e status do vínculo.
- RF05 — Usuário solicita acompanhamento/consulta online após vínculo aceito.
- RF06 — Profissional visualiza somente usuários vinculados/aceitos.
- RF07 — Profissional consulta dados, hábitos, histórico e gráficos do usuário.
- RF08 — Profissional consulta as consultas online relacionadas aos seus usuários.
- RF09 — Profissional registra feedback para usuário vinculado.
- RF10 — Profissional consulta histórico de feedbacks enviados.
- RF11 — Usuário consulta feedbacks recebidos na aba Profissionais e no perfil.
- RF12 — Profissional possui perfil próprio, diferente do usuário comum.
- RF13 — Dashboard do profissional apresenta usuários, consultas e feedbacks.
- RF14 — Dados do usuário exibidos ao profissional são somente leitura.
- RF15 — Usuário e profissional podem excluir a própria conta no MVP.

## Requisitos Não Funcionais
- RNF01 — Java 21.
- RNF02 — Spring Boot + JSF/Jakarta Faces + PrimeFaces.
- RNF03 — JPA/Hibernate + H2 em memória.
- RNF04 — Maven.
- RNF05 — Controle de acesso por tipo de usuário e vínculo aceito.
- RNF06 — Interface responsiva, simples e em português.
- RNF07 — Identidade visual baseada em Primary `#2D8A4F`, Secondary `#89C2D9`, Tertiary `#D8F3DC` e Neutral `#F8F9FA`.
- RNF08 — O profissional não deve receber ações de editar/excluir/atualizar dados de usuários acompanhados.
- RNF09 — O MVP não realiza diagnóstico médico automático; os dados servem como apoio à consulta e acompanhamento profissional.
