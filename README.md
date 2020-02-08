### 这是参考码匠老师

##
create table USER
(
	ID int AUTO_INCREMENT primary key not null,
	ACCOUNT_ID varchar(100),
	NAME varchar(50),
	TOKEN character(36),
	GMT_CREATE bigint,
	GMT_MODIFIED bigint
);
