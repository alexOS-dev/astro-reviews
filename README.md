# Astro Reviews

## Instalación

1. Clonar el repositorio

```bash
git clone https://github.com/alexOS-dev/astro-reviews.git
```

2. Instalar dependencias

```bash
bun install
```

3. Copiar el archivo `.env.template` a `.env` y configurar las variables de entorno

4. Aplicar las migraciones y generar el prisma client

```bash
bunx prisma migrate dev && bunx prisma generate
```

5. Iniciar el proyecto

```bash
bun run dev
```
