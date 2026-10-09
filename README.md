<p align="center"><img src="icon.png" width="96" alt="Schemawise icon"></p>

# Schemawise

**EF Core superpowers for VS Code.** Navigate. Compare. Migrate safely.

Schemawise is a VS Code extension for .NET developers using Entity Framework Core:

- **EF Model**: see the effective EF Core model (tables, columns, keys, indexes) and jump to the code.
- **Schema drift**: compare your model with a real SQL Server or PostgreSQL database.
- **Migration risks**: understand what a migration can break **before** you apply it.

Everything runs locally: no source code, connection string, schema or data leaves your machine.

![EF Model view](media/screenshots/ef-model.png)

## Install

- **VS Code**: search for "Schemawise" in the Extensions view, or visit the
  [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=eflens.schemawise).
- **Cursor, VSCodium, Windsurf**: [Open VSX](https://open-vsx.org/extension/eflens/schemawise).

Requires the .NET 8 runtime (or later) and the .NET SDK your projects need. Supports EF Core 8, 9
and 10 with SQL Server and PostgreSQL.

## Report a problem or suggest an idea

1. In VS Code, run **Schemawise: Copy Diagnostics** (it copies versions and statuses only: no code,
   connection strings or absolute paths).
2. [Open an issue](https://github.com/elite3448/schemawise/issues/new/choose) and paste it.

False positives (drift or migration risks reported wrongly) are the most useful reports.

## License

Schemawise is proprietary software, free during the preview: see [LICENSE.txt](LICENSE.txt) and
[THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt). This repository holds the public page, images
and issues; the source code is private.
