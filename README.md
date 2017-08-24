[![Travis build status](https://img.shields.io/travis/souchprod/SouchProd.EntityFrameworkCore.Firebird.svg?label=travis-ci&branch=master)](https://travis-ci.org/souchprod/SouchProd.EntityFrameworkCore.Firebird)

# SouchProd.EntityFrameworkCore.Firebird

SouchProd.EntityFrameworkCore.Firebird is an Entity Framework Core provider built on top of the Firebird ADO.NET Data Provider. It enables use the Entity Framework Core 2.0 ORM with Firebird (2.x, 3.0) and Interbase.

## Status

Work in progress at an early stage**, **not** production ready, **not** beta ready.

  - ~~Last inserted id  propagation to the entity after an insert not yet supported.~~
  
  - GUID not yet supported.
  
  - BLOB & CLOB not yet supported.

  - Scaffolding not yet supported.

  - Migrations not yet supported.
  
  - Nuget package not yet available.

## Roadmap

Version | Content | Status
------------|------------|------------
2.0 Preview 1 | First release, read/write support limited to basic field types | :heavy_check_mark: Available
2.0 Preview 2 | Last inserted id support | :heavy_check_mark: Available
2.0 Preview 3 | Read/Write support for all the Firebird data types | :fire: In progress
2.0 Preview 4 | Scaffolding support | :date: Scheduled
2.0 Preview 5 | Migration support | :date: Scheduled
2.0 Final | Cleanup, refactoring and perf tuning | :confetti_ball: Scheduled

## Dependencies 

The nuget package SouchProd.Data.FirebirdClient is currently required. It will be replaced by the official FirebirdSql.Data.FirebirdClient as soon as it will be updated accordingly t support .Net standard 2.

## Contributing 

Wanna add a feature, fix a bug or improve my crappy code ? 

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Credits

This project inherit from the [Microsoft Entity Framework Core](https://github.com/aspnet/EntityFrameworkCore) (under Apache licence).

This  benefit also from the great work made on the [Pomelos MySql EF Core provider](https://github.com/PomeloFoundation/Pomelo.EntityFrameworkCore.MySql), a large part of this repository code was forked from this it.

## License

[MIT](https://github.com/SouchProd/SouchProd.EntityFrameworkCore.Firebird/blob/master/LICENSE)
