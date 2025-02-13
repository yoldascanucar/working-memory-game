## WORKING MEMORY GAME


The Digit Span Game is a web-based application designed to test and improve working memory. The game presents users with sequences of digits or letters and numbers, and the user must recall and input the sequences in various modes such as forwards, backwards, sequencing, and letter-number sequencing. The game increases in difficulty as the user progresses by increasing the length of the sequences.
It is essentially a direct digital clone of the WAIS-IV Digit Span and Letter-Number Sequencing subtests, replicating these well-known cognitive assessments. This project offers users an authentic experience that mirrors the memory tasks used in professional IQ testing to measure working memory.

## FEATURES

### Multiple Modes

- **Forwards**: Recall the sequence in the same order.

- **Backwards**: Recall the sequence in reverse order.

- **Sequencing**: Recall the sequence in ascending order.

- **Letter-Number Sequencing**: Recall a mixed sequence of letters and numbers in a specific order.

### Dynamic Sequence Generation
- Sequences are randomly generated and increase in length as the user progresses.

### Session Management
- User progress is managed through sessions, allowing for a continuous experience.

### Responsive Design 
- The game is designed to be responsive and works well on various screen sizes.


## TECHNOLOGIES USED

- **Java**: Core logic and backend processing.

- **Servlets**: Handling HTTP requests and responses.

- **JSP (JavaServer Pages)**: Frontend rendering and dynamic content.

- **Hibernate**: ORM for database interactions (if needed).

- **Maven**: Dependency management and project building.

- **HTML/CSS/JavaScript**: Frontend design and interactivity.


## INSTALLATION

### Prerequisites

- Java Development Kit (JDK) 14 or higher.
- Apache Maven.
- A servlet container like Apache Tomcat.
- MySQL (if using Hibernate for database interactions).

### Steps

#### Clone the Repository:

      git clone https://github.com/yourusername/digit-span-game.git
      cd digit-span-game

#### Build the Project

      mvn clean install


#### Deploy to Tomcat

- Copy the generated WAR file from the target directory to the webapps directory of your Tomcat installation.
- Start Tomcat.

#### Access the Application

Open a web browser and navigate to http://localhost:8080/digit-span

## USAGE

### Start the Game

- On the main page, select the desired mode and click "Start".

### Recall the Sequence

- After the sequence is displayed, enter the sequence in the input field and click "Check".

### Progress

- If the sequence is correct, the game will increase the sequence length.

- If incorrect, the game will reset the sequence length.

### Reset

- Click "Reset" to start over from the beginning.

