# Ukol10
Ukol10

SELECT name, address FROM FamousVilla WHERE architecturalStyle <> 'functionalismus' AND constructionCompleted - constructionStated>=2;
SELECT name FROM FamousVilla Where address LIKE '%Pisárky%';
UPDATE FamousVilla SET name = 'Norbert Schlesinger', constructionCompleted = 1935 WHERE id = 7;
INSERT INTO FamousVilla VALUES (10, 'Oleg Villa', 'Oleg', 'Oleg', 2020, 2021, 'funkcionalismus', 'Na Vaclavce 14, cp. 155, Praha 5-Smichov');
INSERT INTO FamousVilla VALUES (11, 'Druha Villa', 'Martin', 'Martin', 2021, 2022, 'secese', 'Janskeho 10, cp. 101, Praha 13-Stodulky');
DELETE FROM FamousVilla WHERE architecturalStyle = 'purismus';
DELETE FROM FamousVilla WHERE architecturalStyle = 'secese';
INSERT INTO FamousVilla (id, architect, constructionStated, architecturalStyle, address) VALUES (12, 'Richard Načrtl', 2021, 'modern', 'Karlovská 624, Dolní Kounice');
SELECT * FROM FamousVilla;
