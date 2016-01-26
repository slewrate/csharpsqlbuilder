# Introduction #

The library provides syntax and code generation tool to
write SQL statements in C#.

Example:
> Sql.Select(Users.Id).Where(Users.Name.Like(Sql.Const("%bla%")))

> translates to SELECT users.id FROM users WHERE (users.name LIKE '%bla%')