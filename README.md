# Week-3a-Data-manipulation-
-- Create the student table
CREATE TABLE student (
    id INTEGER PRIMARY KEY,
    fullName VARCHAR(100),
    age INTEGER
);

-- Insert records into the student table
INSERT INTO student (id, fullName, age) VALUES
(1, 'Alice Smith', 18),
(2, 'Bob Johnson', 19),
(3, 'Charlie Brown', 20);

-- Update the age of the student with ID 2
UPDATE student
SET age = 20
WHERE id = 2;
