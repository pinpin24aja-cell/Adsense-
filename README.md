# Adsense-
DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Publisher Dashboard</title>

<style>
body {
    margin: 0;
    font-family: Arial, Helvetica, sans-serif;
    background: #f1f3f4;
    color: #202124;
}

.header {
    background: #fff;
    padding: 15px 25px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-bottom: 1px solid #ddd;
}

.logo {
    font-size: 20px;
    font-weight: bold;
    color: #1a73e8;
}

.container {
    max-width: 1100px;
    margin: auto;
    padding: 25px;
}

.cards {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
}

.card {
    background: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 6px rgba(0,0,0,0.08);
}

.card h3 {
    margin: 0;
    font-size: 14px;
    color: #5f6368;
}

.amount {
    font-size: 28px;
    margin-top: 10px;
    color: #1a73e8;
    font-weight: bold;
}

.section {
    margin-top: 40px;
    background: #fff;
    padding: 25px;
    border-radius: 8px;
    box-shadow: 0 2px 6px rgba(0,0,0,0.08);
}

.section h2 {
    margin-top: 0;
    font-size: 18px;
}

.table {
    width: 100%;
    border-collapse: collapse;
    margin-top: 15px;
}

.table th, .table td {
    padding: 12px;
    border-bottom: 1px solid #ddd;
    text-align: left;
}

.table th {
    background: #f8f9fa;
    font-size: 14px;
}

.status {
    color: green;
    font-weight: bold;
}

footer {
    text-align: center;
    padding: 20px;
    color: #777;
    font-size: 13px;
}
</style>
</head>

<body>

<div class="header">
    <div class="logo">MonetizeWeb</div>
    <div>Publisher</div>
</div>

<div class="container">

    <!-- SALDO -->
    <div class="cards">
        <div class="card">
            <h3>Saldo Saat Ini</h3>
            <div class="amount">Rp 19.200.120</div>
        </div>

        <div class="card">
            <h3>Pendapatan Hari Ini</h3>
            <div class="amount">Rp 75.000</div>
        </div>

        <div class="card">
            <h3>Pendapatan Bulan Ini</h3>
            <div class="amount">Rp 19.220.120</div>
        </div>

        <div class="card">
            <h3>Pendapatan Bulan Lalu</h3>
            <div class="amount">Rp 13.120.110</div>
        </div>
    </div>

    <!-- RIWAYAT -->
    <div class="section">
        <h2>Riwayat Pendapatan</h2>

        <table class="table">
            <tr>
                <th>Tanggal</th>
                <th>Tayangan</th>
                <th>Klik</th>
                <th>Pendapatan</th>
                <th>Status</th>
            </tr>

            <tr>
                <td>10 Feb 2026</td>
                <td>12.450</td>
                <td>315</td>
                <td>Rp 75.000</td>
                <td class="status">Final</td>
            </tr>

            <tr>
                <td>9 Feb 2026</td>
                <td>18.220</td>
                <td>460</td>
                <td>Rp 120.000</td>
                <td class="status">Final</td>
            </tr>

            <tr>
                <td>8 Feb 2026</td>
                <td>15.600</td>
                <td>390</td>
                <td>Rp 98.000</td>
                <td class="status">Final</td>
            </tr>

            <tr>
                <td>Feb 2026</td>
                <td>210.000</td>
                <td>5.600</td>
                <td>Rp 1.250.000</td>
                <td class="status">Berjalan</td>
            </tr>
        </table>
    </div>

</div>

<footer>
    © 2026 MonetizeWeb Publisher Dashboard
</footer>

</body>
</html>
