
import jakarta.persistence.Column;
import jakarta.persistence.Entity;

### POJO classes (Entity classes)
@Entity

### Table name in database with student
@Table(name="student")



### Primary Key 
#### This annotation will make primary key in table 
@Id
@GeneratedValue(strategy=GenerationType.IDENTITY)


## change name of the column
@Column(name="" )






