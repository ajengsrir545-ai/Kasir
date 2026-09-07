<!DOCTYPE html>
<html>
<head>
    <title>Salad Saturday - Kasir</title>

    <style>
        body {
            margin: 0;
            font-family: Arial;
            background: #f5f5f5;
        }

        .sidebar {
            width: 220px;
            height: 100vh;
            background: #1e293b;
            position: fixed;
            padding: 20px;
        }

        .sidebar h2 {
            color: white;
            text-align: center;
        }

        .sidebar a {
            display: block;
            color: white;
            text-decoration: none;
            padding: 12px;
            margin-top: 10px;
            background: #334155;
            border-radius: 8px;
        }

        .sidebar a:hover {
            background: #3b82f6;
        }

        .main {
            margin-left: 260px;
            padding: 30px;
        }

        .card {
            background: white;
            padding: 20px;
            border-radius: 15px;
            margin-bottom: 20px;
        }

        input, select, textarea {
            width: 100%;
            padding: 12px;
            margin: 8px 0;
            box-sizing: border-box;
        }

        button {
            padding: 12px 20px;
            border: none;
            border-radius: 8px;
            background: #3b82f6;
            color: white;
        }
    </style>
</head>

<body>

<div class="sidebar">

    <h2>🥗 Salad Saturday</h2>

    <a href="index.php">Dashboard</a>
    <a href="index.php?page=products">Produk</a>
    <a href="index.php?page=customers">Customer</a>
    <a href="index.php?page=cashier">Kasir</a>
    <a href="index.php?page=transactions">Transaksi</a>

</div>

<div class="main">

<?php if ($page == 'dashboard'): ?>

    <div class="card">
        <h1>Dashboard</h1>
        <p>Selamat datang di Aplikasi Kasir Salad Saturday.</p>
    </div>

<?php elseif ($page == 'products'): ?>

    <div class="card">

        <h1>Produk</h1>

        <form method="POST">

            <input
                type="text"
                name="name"
                placeholder="Nama Produk"
                required
            >

            <input
                type="number"
                name="price"
                placeholder="Harga"
                required
            >

            <input
                type="number"
                name="stock"
                placeholder="Stok"
                required
            >

            <select name="category" required>

                <option value="">
                    Pilih Kategori
                </option>

                <option value="Fresh">
                    Fresh
                </option>

                <option value="Healthy">
                    Healthy
                </option>

                <option value="Premium">
                    Premium
                </option>

                <option value="Combo">
                    Combo
                </option>

                <option value="Promo">
                    Promo
                </option>

            </select>

            <input
                type="date"
                name="expired_date"
                required
            >

            <button type="submit">
                Tambah Produk
            </button>

        </form>

    </div>

<?php elseif ($page == 'customers'): ?>

    <div class="card">

        <h1>Customer</h1>

        <input
            type="text"
            placeholder="Nama Customer"
        >

        <input
            type="text"
            placeholder="Nomor HP"
        >

        <textarea
            placeholder="Alamat"
        ></textarea>

        <button>
            Tambah Customer
        </button>

    </div>

<?php elseif ($page == 'cashier'): ?>

    <div class="card">

        <h1>Kasir</h1>

        <p>
            Pilih produk untuk dimasukkan ke keranjang.
        </p>

        <button>
            Tambah ke Keranjang
        </button>

    </div>

<?php elseif ($page == 'transactions'): ?>

    <div class="card">

        <h1>Transaksi</h1>

        <p>
            Riwayat transaksi akan tampil di sini.
        </p>

    </div>

<?php endif; ?>

</div>

</body>
</html>
