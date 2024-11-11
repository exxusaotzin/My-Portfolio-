# Module 4: Working with Data (DML)

# My code
CREATE TABLE cartoons (
cartoon_id NUMBER,
title VARCHAR2(50),
channel NUMBER,
main_character VARCHAR2(50)
);

INSERT INTO cartoons (cartoon_id, title, channel, main_character)
VALUES (1, 'Spongebob', 83, 'Spongebob');

INSERT INTO cartoons (cartoon_id, title, channel, main_character)
VALUES (2, 'Amazing World of Gumball', 82, 'Gumball');

INSERT INTO cartoons (cartoon_id, title, channel, main_character)
VALUES (3, 'The Heroic Quest of the Valiant Prince Ivandoe', 82, 'Ivandoe');

UPDATE cartoons
SET main_character = 'Patrick'
WHERE cartoon_id = 1

DELETE FROM cartoons
WHERE cartoon_id = 3

# What I learned
In this module, I learned how to manage a list by creating, inserting, updating and deleting item from the table.

