CREATE TABLE IF NOT EXISTS position (
    id INTEGER PRIMARY KEY,
    title TEXT,
    salary NUMERIC,
    work_time TEXT
);

CREATE TABLE IF NOT EXISTS location_shop (
    id INTEGER PRIMARY KEY,
    city TEXT,
    street TEXT,
    house TEXT,
    work_time TEXT
);
