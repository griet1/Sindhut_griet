import java.util.Date;

/**
 * A fix-sized array of students
 * array length should always be equal to the number of stored elements
 * after the element was removed the size of the array should be equal to the number of stored elements
a * after the element was added the size of the array should be equal to the number of stored elements
 * null elements are not allowed to be stored in the array
 * 
 * You may add new methods, fields to this class, but DO NOT RENAME any given class, interface or method
 * DO NOT PUT any classes into packages
 *
 */
public class StudentGroup implements StudentArrayOperation {

	private Student[] students;

	 *private string students[]=new student[100];

	 * if students == null method should throw IllegalArgumentException
	
	/**
	 * DO NOT remove or change this constructor, it will be used during task check
	 * @param length
	 */
	public StudentGroup(int length) {
		this.students = new Student[length];
	}

	@Override
	public Student[] getStudents() {
		private string student[]=new student[100];
               
                                }

	@Override
	public void setStudents(Student[] students) {
		try
    {
        for(int i = 0 ; i<array.length ; i++)
            System.out.println("This array has: "+array[i]);

    } catch (IllegalArgumentException e)
    {
        System.out.println("Null!!!");
    }
                             }
	

	@Override
	public Student getStudent(int index) {
             student[i] = student[i].replace('3',"David");
              System.out.println(dna[i]);
try{
for(int i = 0 ; i<array.length ; i++)
            System.out.println("This array has: "+array[i]);

    } catch (IllegalArgumentException e)
    {
        System.out.println("Null!!!");
    }
		
	}

	@Override
	public void setStudent(Student student, int index) {
		student.add("4","Color");
try{
for(int i = 0 ; i<array.length ; i++)
            System.out.println("This array has: "+array[i]);

    } catch (IllegalArgumentException e)
    {
        System.out.println("Null!!!");
    }
	}

	@Override
	public void addFirst(Student student) {
		student.add(0,56);
	}

	@Override
	public void addLast(Student student) {
		student[array.length - 1] = 4;
    System.out.println(student.toString(student));
	}

	@Override
	public void add(Student student, int index) {
		// Add your implementation here
	}

	@Override
	public void remove(int index) {
		// Add your implementation here
	}

	@Override
	public void remove(Student student) {
		// Add your implementation here
	}

	@Override
	public void removeFromIndex(int index) {
		// Add your implementation here
	}

	@Override
	public void removeFromElement(Student student) {
		// Add your implementation here
	}

	@Override
	public void removeToIndex(int index) {
		// Add your implementation here
	}

	@Override
	public void removeToElement(Student student) {
		// Add your implementation here
	}

	@Override
	public void bubbleSort() {
		// Add your implementation here
	}

	@Override
	public Student[] getByBirthDate(Date date) {
		// Add your implementation here
		return null;
	}

	@Override
	public Student[] getBetweenBirthDates(Date firstDate, Date lastDate) {
		// Add your implementation here
		return null;
	}

	@Override
	public Student[] getNearBirthDate(Date date, int days) {
		// Add your implementation here
		return null;
	}

	@Override
	public int getCurrentAgeByDate(int indexOfStudent) {
		// Add your implementation here
		return 0;
	}

	@Override
	public Student[] getStudentsByAge(int age) {
		// Add your implementation here
		return null;
	}

	@Override
	public Student[] getStudentsWithMaxAvgMark() {
		// Add your implementation here
		return null;
	}

	@Override
	public Student getNextStudent(Student student) {
		// Add your implementation here
		return null;
	}
}

