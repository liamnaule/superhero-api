# superhero-api
A Flask-based API for managing superheroes, their powers, and relationships using a many-to-many model with validations and RESTful routes.

## Models
- **Hero**: name, super_name
- **Power**: name, description (min 20 chars)
- **HeroPower**: strength (Strong, Weak, Average), hero_id, power_id

## Endpoints
- `GET /heroes`
- `GET /heroes/<id>`
- `GET /powers`
- `GET /powers/<id>`
- `PATCH /powers/<id>`
- `POST /hero_powers`

## Setup
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/liamnaule/superhero-api
   cd superhero-api

## Validations
- Power description: min 20 chars
- HeroPower strength: "Strong", "Weak", or "Average"

## Author
- Liam Naule
