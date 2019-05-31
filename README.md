# Hibernate-OneToMany-ManyToOne-Using-Annotation

Hibernate: select sequence_next_hi_value from hibernate_sequences where sequence_name = 'q501' for update

Hibernate: insert into hibernate_sequences(sequence_name, sequence_next_hi_value) values('q501', ?)

Hibernate: update hibernate_sequences set sequence_next_hi_value = ? where sequence_next_hi_value = ? and sequence_name = 'q501'

Hibernate: select sequence_next_hi_value from hibernate_sequences where sequence_name = 'ans501' for update

Hibernate: insert into hibernate_sequences(sequence_name, sequence_next_hi_value) values('ans501', ?)

Hibernate: update hibernate_sequences set sequence_next_hi_value = ? where sequence_next_hi_value = ? and sequence_name = 'ans501'

Hibernate: insert into q501 (qname, id) values (?, ?)

Hibernate: insert into ans501 (answername, postedBy, question_id, id) values (?, ?, ?, ?)

Hibernate: insert into ans501 (answername, postedBy, question_id, id) values (?, ?, ?, ?)

Hibernate: insert into q501 (qname, id) values (?, ?)

Hibernate: insert into ans501 (answername, postedBy, question_id, id) values (?, ?, ?, ?)

Hibernate: insert into ans501 (answername, postedBy, question_id, id) values (?, ?, ?, ?)

Hibernate: update ans501 set type=? where id=?

Hibernate: update ans501 set type=? where id=?

Hibernate: update ans501 set type=? where id=?

Hibernate: update ans501 set type=? where id=?

SQL> select * from q501;

	ID QNAME
	 1 What is Java?
	 2 What is Servlet?

SQL> select *  from ans501;

	ID	  QUESTION_ID POSTEDB ANSWERNAME		TYPE
	 1	    1 Ravi    Java is a programming language	0
	 2	    1 Sudhir  Java is a platform		1
	 3	    2 Jai     Servlet is an Interface		0
	 4	    2 Arun    Servlet is an API 		1




