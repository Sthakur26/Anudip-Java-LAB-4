class User {
    // Properties
    private int id;
    private String name;

    // Parameterized constructor
    public User(int id, String name) {
        this.id = id;
        this.name = name;
    }

    // Getters
    public int getId() {
        return id;
    }

    public String getName() {
        return name;
    }
}

class Employee extends User {
    // Additional properties
    private double salary;

    // Parameterized constructor
    public Employee(int id, String name, double salary) {
        super(id, name);
        this.salary = salary;
    }

    // Method to calculate annual salary
    public double calculateAnnualSalary() {
        return salary * 12;
    }
}

public class SalaryCalculator {
    public static void main(String[] args) {
        // Create an object of Employee class
        Employee employee = new Employee(1, "John", 20000);

        // Calculate and display the annual salary
        double annualSalary = employee.calculateAnnualSalary();
        System.out.println("Employee ID: " + employee.getId());
        System.out.println("Employee Name: " + employee.getName());
        System.out.println("Annual Salary: " + annualSalary);
    }
}
