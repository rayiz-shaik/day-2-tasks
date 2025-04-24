# day-2-tasks
Day-2 tasks of front end dev(html)

DAY-2
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Tasks</title>
</head>
<body>

    <!-- Task 1: Create a table with Name, Age, and Country -->
    <table border="1">
        <tr>
            <th>Name</th>
            <th>Age</th>
            <th>Country</th>
        </tr>
        <tr>
            <td>Aman</td>
            <td>25</td>
            <td>India</td>
        </tr>
        <tr>
            <td>Raj</td>
            <td>30</td>
            <td>India</td>
        </tr>
        <tr>
            <td>Kumar</td>
            <td>22</td>
            <td>India</td>
        </tr>
    </table>

    <!-- Task 2: Create a table with thead, tbody, and tfoot -->
    <table border="1">
        <thead>
            <tr>
                <th>Name</th>
                <th>Score</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Rajesh</td>
                <td>85</td>
            </tr>
            <tr>
                <td>Kishore</td>
                <td>90</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <td colspan="2">Total Students: 2</td>
            </tr>
        </tfoot>
    </table>

    <!-- Task 3: Add a table caption -->
    <table border="1">
        <caption>Student Data</caption>
        <tr>
            <th>Name</th>
            <th>Marks</th>
        </tr>
        <tr>
            <td>Zakir</td>
            <td>78</td>
        </tr>
    </table>

    <!-- Task 4: Use colspan to span 2 columns -->
    <table border="1">
        <tr>
            <th>Name</th>
            <th colspan="2">Details</th>
        </tr>
        <tr>
            <td>Kartik</td>
            <td>20</td>
            <td>India</td>
        </tr>
    </table>

    <!-- Task 5: Use rowspan to span 2 rows -->
    <table border="1">
        <tr>
            <th>Name</th>
            <th>Age</th>
        </tr>
        <tr>
            <td rowspan="2">Rajesh</td>
            <td>20</td>
        </tr>
        <tr>
            <td>21</td>
        </tr>
    </table>

    <!-- Task 6-10: HTML Form and Inputs -->
    <form>
        <!-- Task 6: Basic form -->
        <label>Name:</label>
        <input type="text" name="name"><br>
        <label>Email:</label>
        <input type="email" name="email"><br>
        <input type="submit" value="Submit"><br>

        <!-- Task 7: Password field and checkbox -->
        <label>Password:</label>
        <input type="password" name="password"><br>
        <input type="checkbox" name="remember"> Remember Me<br>

        <!-- Task 8: Radio buttons -->
        <input type="radio" name="gender" value="Male"> Male
        <input type="radio" name="gender" value="Female"> Female
        <input type="radio" name="gender" value="Other"> Other<br>

        <!-- Task 9: Dropdown -->
        <label>Country:</label>
        <select>
            <option>USA</option>
            <option>UK</option>
            <option>India</option>
        </select><br>

        <!-- Task 10: Textarea and reset button -->
        <label>Feedback:</label>
        <textarea></textarea><br>
        <input type="reset" value="Reset">
    </form>

    <!-- Task 11-15: Semantic Elements -->
    <header><h1>Welcome to My Page</h1></header>
    <nav><a href="#">Home</a> | <a href="#">About</a></nav>
    <main>
        <!-- Task 12: Article -->
        <article><h2>About Us</h2><p>We are a tech company.</p></article>

        <!-- Task 13: Section -->
        <section><h3>Services</h3><p>We provide web development.</p></section>
        <section><h3>Portfolio</h3><p>Check our work.</p></section>
        <section><h3>Contact</h3><p>Email us at info@example.com.</p></section>
    </main>
    <aside><p>Related Links:</p><a href="#">Blog</a></aside>
    <footer>&copy; 2025 My Website</footer>

    <!-- Task 15: Figure -->
    <figure>
        <img src="image.jpg" alt="Example Image">
        <figcaption>Sample Image</figcaption>
    </figure>

    <!-- Task 16-18: HTML Entities -->
    <p>@ &reg; &trade; &gt; &lt; &amp;</p>
    <p>H&nbsp;e&nbsp;l&nbsp;l&nbsp;o&nbsp; W&nbsp;o&nbsp;r&nbsp;l&nbsp;d</p>
    <p>Love &hearts; Money &dollar; Euros &euro;</p>

    <!-- Task 19: HTML Comments -->
    <!-- This is the header section -->
    <header><h1>My Website</h1></header>
    <!-- Navigation -->
    <nav><a href="#">Home</a> | <a href="#">Contact</a></nav>
    <!-- Footer section -->
    <footer>End of the page</footer>

    <!-- Task 20: File Paths -->
    <img src="./images/sample.jpg" alt="Relative Path">
    <img src="https://example.com/sample.jpg" alt="Absolute Path">

</body>
</html>
