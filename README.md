# SQL

# header

INSERT INTO work (workid, title, longtitle, year, genretype, source, totalwords, totalparagraphs)
VALUES  ('lostwork', 'lost work', 'Shakespeare''s lost work', 2020, 'L', 'private', 2000, 10)

UPDATE work
SET totalwords = 3000, totalparagraphs = 15
WHERE workid = 'lostwork'

DELETE FROM work
WHERE workid = 'lostwork'
