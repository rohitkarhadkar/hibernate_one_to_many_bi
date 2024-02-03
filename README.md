# Hibernate Project with One-to-Many Bidirectional Relationship

This Hibernate project introduces a one-to-many bidirectional relationship between the `Instructor` and `Course` entities. In this mapping, an instructor can have multiple courses, and each course belongs to one instructor. This relationship enables efficient querying and navigation between instructors and their respective courses.

## Features

- **One-to-Many Bidirectional Relationship**: Implements a one-to-many bidirectional relationship between `Instructor` and `Course` entities, allowing instructors to have multiple courses and each course to have one instructor.
- **Enhanced Data Access**: Provides efficient querying and navigation between instructors and their courses, enabling detailed analysis of the teaching assignments.
- **Cascading Delete Not Applied**: The project does not apply cascading delete operations, ensuring that deleting an instructor does not delete associated courses, and deleting a course does not delete the instructor.

## Project Structure

The project structure includes the following components:

- `Instructor` entity: Represents an instructor with basic details such as first name, last name, and email.
- `Course` entity: Represents a course with details such as title, description, and instructor.
- `Main` class: Contains the main method to demonstrate CRUD operations and bidirectional mappings.

## Usage

To run the Hibernate project with one-to-many bidirectional relationships locally, follow these steps:

1. Clone this repository.
2. Open the project in your preferred IDE.
3. Update the Hibernate configuration file (`hibernate.cfg.xml`) with your database connection details.
4. Run the `Main` class to execute the CRUD operations and observe the behavior of bidirectional mappings.

## Contributing

Contributions are welcome! If you have any suggestions, bug fixes, or feature implementations, please open an issue or submit a pull request.

