DB_Drako_IA - Base de Datos

Repositorio que contiene el esquema, scripts y respaldos de la base de datos del proyecto **DB_Drako_IA**.

#1 📁 Estructura del Repositorio

- `sql/` - Scripts SQL para crear tablas, funciones y triggers
- `backups/` - Respaldos de la base de datos
- `README.md` - Este archivo

#2 🗄️ Tablas del Sistema

1. `account` - Cuentas principales
2. `kitchen` - Tipos de cocina
3. `account_user` - Usuarios del sistema
4. `account_user_type_of_kitchen` - Relación usuario-cocina
5. `account_user_linkable_devices` - Dispositivos enlazables
6. `account_user_has` - Relaciones adicionales
7. `audit_log` - Registro de auditoría

#3 🔧 Tecnologías

- **Base de Datos**: PostgreSQL 17.6 (Supabase)
- **Cliente**: psql 18.6
- **Región**: us-east-2 (East US Ohio)

#4 🚀 Cómo usar

1. Conéctate a tu base de datos PostgreSQL:
   ```bash
   psql "postgresql://postgres:[PASSWORD]@db.wliyciokmffguopcpzuy.supabase.co:5432/postgres"
