# Product Card - Short Code Documentation

## Pattern
Each item uses the same minimal card structure:
- `<img>` — product image
- `<h3>` — product name
- `<p>` — short description
- `<span>` — price
- `<button>` — Buy Now action

## Products covered

### Stationery
| Item    | Price  |
|---------|--------|
| Pen     | $2.29  |
| Pencil  | $1.49  |
| Eraser  | $0.99  |


## Code block 
```
<!DOCTYPE html>
<html>
<head>
    <title>Product Cards</title>
</head>
<body>

    <!-- Product 1 -->
    <div style="border:1px solid black; width:220px; padding:10px; margin:10px;">
        <img src="pen.jpg" alt="Pen" width="200">
        <h2>Ball Pen</h2>
        <p>Smooth writing blue ink pen.</p>
        <h3>$2.00</h3>
        <button>Buy Now</button>
    </div>

    <!-- Product 2 -->
    <div style="border:1px solid black; width:220px; padding:10px; margin:10px;">
        <img src="pencil.jpg" alt="Pencil" width="200">
        <h2>HB Pencil</h2>
        <p>High-quality wooden HB pencil.</p>
        <h3>$1.00</h3>
        <button>Buy Now</button>
    </div>

    <!-- Product 3 -->
    <div style="border:1px solid black; width:220px; padding:10px; margin:10px;">
        <img src="eraser.jpg" alt="Eraser" width="200">
        <h2>Soft Eraser</h2>
        <p>Removes pencil marks cleanly.</p>
        <h3>$0.50</h3>
        <button>Buy Now</button>
    </div>

</body>
</html>
```
## Notes
- Each item is a standalone `.card` block — swap the image, name,
  description, and price to reuse it for any product.
- Kept intentionally short (no CSS/JS) so the structure is easy to
  copy into a larger page and style as needed.
- To make it a full page, wrap items in a `<div class="grid">` and
  add CSS for layout, spacing, and button styling.