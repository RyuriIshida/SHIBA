# SHIBA
DBテーブルスキーマ
CREATE TABLE t_fanclub(
fanclub_no character varying(10) not null,
name_last text not null,
name_first text not null,
eng_last text not null,
eng_first text not null,
birthday date not null,
sex text not null,
email text,
password text,
comment text,
register_time timestamp with time zone DEFAULT now() not null
);
