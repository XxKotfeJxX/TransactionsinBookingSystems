# Transactions in Booking Systems

An interactive browser presentation about database transactions and data
consistency in booking systems. The slides explain why concurrent bookings are
difficult and how transactional guarantees help prevent double booking and
partial updates.

## View the presentation

Open `index.html` in a modern browser, or serve the project locally:

```bash
python -m http.server 8000
```

Then open <http://localhost:8000>. Use the on-screen navigation or keyboard
controls to move between slides.

## Structure

- `index.html` — presentation shell and slide navigation;
- `slides/` — individual HTML slides.

No build step or backend is required.

## License

MIT. See [LICENSE](LICENSE).
