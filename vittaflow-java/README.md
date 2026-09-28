# VittaFlow MVP

Projeto acadêmico Java 21 + Spring Boot + JSF/PrimeFaces + JPA/Hibernate + H2 em memória.

## Executar

1. Abra a pasta no VSCode.
2. Verifique Java 21: `java -version`
3. Verifique Maven: `mvn -version`
4. Execute: `mvn spring-boot:run`
5. Abra: <http://localhost:8080/login.xhtml>

## Dados demonstrativos

Usuário: <mariana@vittaflow.com> / 123456
Profissional: <ana.nutri@vittaflow.com> / 123456
Profissional: <carlos.edu@vittaflow.com> / 123456

O banco é H2 em memória e usa create-drop. Não há MySQL, PostgreSQL, Firebase, Docker, APIs externas, Google Fit, sensores, React, Angular, Vue, Thymeleaf, Bootstrap ou Tailwind.

## Novas funcionalidades do acompanhamento profissional

- Dashboard separado para o profissional.
- Lista de usuários vinculados/aceitos.
- Consultas online demonstrativas.
- Acompanhamento de água, passos, sono, exercícios e gráficos.
- Dados do usuário em modo somente leitura para o profissional.
- Aba de feedback para registrar orientações.
- Usuário consulta os profissionais selecionados e os feedbacks recebidos.
- Requisitos detalhados em `REQUISITOS.md`.

### Fluxo demonstrativo

Usuário: `mariana@vittaflow.com` / `123456`

A usuária Mariana já inicia o MVP com vínculo aceito, consulta online agendada e um feedback da profissional Ana Paula para demonstrar o fluxo.

Profissional: `ana.nutri@vittaflow.com` / `123456`

Ao entrar como Ana Paula, a tela inicial apresenta Mariana em acompanhamento e permite abrir seus dados e gráficos sem editar os registros.
