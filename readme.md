# **Diagrama Entidade Relacionamento**

Projeto desenvolvido como atividade individual do módulo de Back-end do curso de WebDev Full-Stack do programa "Programadores Cariocas". Uma parceria entre a Prefeitura do Rio de Janeiro com o Senac Rio, tendo como metodologia de ensino a Resília Educação.

---

## **Detalhamento do projeto**

A Resília quer lançar um novo sistema e precisa modelar um banco de dados para armazenar seus *cursos*, *turmas* e *alunos*.

Questões levantadas:
- **Existem outras entidades além dessas três?**
    A priori, criei a entidade *polo* e a *professores*. Para que o relacionamento fosse mais completo.

- **Quais são os principais campos e tipos?**
    Todas as entidades possuem ID, seu tipo é INT, e são Primary Key.
    Em cada uma das entidades, pode-se ver seus atributos, que em sua maioria são do tipo VARCHAR.

- **Como essas entidades estão relacionadas?**
    Cada *polo* contem seus *cursos*, que contem *turmas* e *professores*. 
    Cada *turma* contém seus *alunos* e *professores*.

### **Tecnologias utilizadas**
- Miro (para construir o diagrama)
- SQL

---

## **Desenvolvedor**
*Juliana Jesus*<br>
Rio de Janeiro/RJ
