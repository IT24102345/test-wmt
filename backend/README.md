# Backend - Item Manager Lab Test

## Setup
1. Open a terminal inside the backend folder.
2. Run:
   ```bash
   npm install
   ```
3. Copy `.env.example` to `.env`
4. Update `MONGO_URI`:
   - for Atlas, use a valid `mongodb+srv://<username>:<password>@cluster0.x1jjdb6.mongodb.net/<dbname>?retryWrites=true&w=majority` string and make sure your current IP is allowlisted
   - or use local MongoDB: `mongodb://127.0.0.1:27017/item-manager`
5. Start the server:
   ```bash
   npm run dev
   ```

## API Endpoints
- `GET /api/items`
- `GET /api/items/:id`
- `POST /api/items`
- `PUT /api/items/:id`
- `DELETE /api/items/:id`
