# Rental Property & Tenant Management System (JSF + Hibernate)

## Run
1. Start MySQL (XAMPP). Database `rental_db` is created automatically.
2. Edit `src/main/resources/hibernate.cfg.xml` if your MySQL root has a password.
3. Import as a Maven project (Eclipse/IntelliJ), run on Tomcat 9.
4. Open http://localhost:8080/rental/properties.xhtml

## Implemented CRUD entities
Property, Tenant (Tenant -> Property many-to-one)

## Validation types
1. Client-side: JavaScript
2. Server-side: JSF validators + custom PhoneValidator + lease date check
3. Database-level: Hibernate/JPA constraints (nullable, unique, length)

## CSS types
Inline (style attributes), internal (style tag in page head), external (resources/css/style.css)

GitHub link: <PASTE HERE>
Video link: <PASTE HERE>
