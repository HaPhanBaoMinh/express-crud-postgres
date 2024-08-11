# express-crud-postgres

CREATE TABLE items (
  id SERIAL PRIMARY KEY,
  name VARCHAR(100) NOT NULL,
  description TEXT
);

INSERT INTO items (name, description) VALUES
('Item 1', 'This is the description for Item 1.'),
('Item 2', 'This is the description for Item 2.'),
('Item 3', 'This is the description for Item 3.'),
('Item 4', 'This is the description for Item 4.'),
('Item 5', 'This is the description for Item 5.'),
('Item 6', 'This is the description for Item 6.'),
('Item 7', 'This is the description for Item 7.'),
('Item 8', 'This is the description for Item 8.'),
('Item 9', 'This is the description for Item 9.'),
('Item 10', 'This is the description for Item 10.');

