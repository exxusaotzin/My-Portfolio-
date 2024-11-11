# Module 5: Advanced Query Writing

# My code
CREATE TABLE badminton_players (
player_id NUMBER,
player_name VARCHAR2(50)
);

CREATE TABLE basketball_players (
player_id NUMBER,
player_name VARCHAR2(50)
);

INSERT INTO badminton_players VALUES (1, 'Chihiro');

INSERT INTO badminton_players VALUES (2, 'Violet');

INSERT INTO badminton_players VALUES (3, 'Ayase');

INSERT INTO basketball_players VALUES (1, 'Hanako');

INSERT INTO basketball_players VALUES (2, 'Inumaki');

INSERT INTO basketball_players VALUES (3, 'Okarun');

SELECT
    bp.player_id,
    bp.player_name AS badminton_player,
    bb.player_name AS basketball_player
FROM
    badminton_players bp
JOIN
    basketball_players bb ON bp.player_id = bb.player_id;

# What I learned
In this module, I learned how to use advanced SQL queries, such as combining information.

