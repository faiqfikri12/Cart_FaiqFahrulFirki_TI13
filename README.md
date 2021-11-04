# Cart_FaiqFahrulFirki_TI13<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cart-Faiq Fahrul Fikri</title>
    <style>
        * {
            margin: 0;
            padding: 0;
        }
    </style>
</head>
<body>
    
    <header style="background-color: rgb(230, 230, 230);">
        <nav style="display: flex; justify-content: space-between; align-items: center; width: 95%; margin: 0 auto; padding: 30px 0;">
            <div style="display: flex; align-items: center;">
                <h2 style="margin-right: 50px;">Site name</h2>
                <ul style="display: flex; align-items: center; list-style: none; padding: 0;">
                    <li><a href="#" style="margin: 0 20px;">Category 1 </a>|</li>
                    <li><a href="#" style="margin: 0 20px;">Category 2 </a>|</li>
                    <li><a href="#" style="margin: 0 20px;">Category 3 </a></li>
                </ul>
            </div>
            <div>
                <a href="#" style="text-decoration: none; color: black;"><b>Cart (1)</b></a>
            </div>
        </nav>
    </header>
    <hr/ style="margin: 0; padding: 0;">
    <main style="height: 460px;">
        <div style="display: flex; align-items: center; justify-content: space-between; width: 95%; margin: 0 auto; padding: 50px 0;">
            <section>
                <h1 style="margin: 10px 0;">Your Cart</h1>
                <table style="width: 900px;">
                    <thead>
                        <tr>
                            <th colspan="3"><hr/ style="margin: 10px 0;"></th>
                        </tr>
                        <tr>
                            <th style="text-align: start;">Item</th>
                            <th style="width: 150px; text-align: start;">Price</th>
                            <th style="width: 150px; text-align: start;">Quantity</th>
                        </tr>
                        <tr>
                            <th colspan="3"><hr/ style="margin: 10px 0;"></th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>
                                <figure style="display: flex; align-items: center; margin: 15px 0;">
                                    <img src="assets/images/images.jpeg" alt="T-Shirt image" width="130" height="130">
                                    <div style="margin-left: 20px;">
                                        <p style="margin: 15px 0;">T-Shirt</p>
                                        <p style="margin: 15px 0;">Size Small</p>
                                    </div>
                                </figure>
                            </td>
                            <td>
                                <h4><b>$20.00</b></h4>
                            </td>
                            <td>
                                <select name="quantity" id="quantity" style="width: 50%;">
                                    <option value="1">1</option>
                                    <option value="2">2</option>
                                    <option value="3">3</option>
                                    <option value="4">4</option>
                                    <option value="5">5</option>
                                </select>
                            </td>
                        </tr>
                        <tr>
                            <td colspan="3"><hr/ style="margin: 10px 0;"></td>
                        </tr>
                        <tr>
                            <td></td>
                            <td></td>
                            <td>Subtotal: <b>$20.00</b></td>
                        </tr>
                        <tr>
                            <td colspan="3"><hr/ style="margin: 10px 0;"></td>
                        </tr>
                    </tbody>
                </table>
            </section>
            <section style="background-color: rgb(230, 230, 230); padding: 30px;">
                <h3 style="padding: 10px 0; margin: 0;">Summary (1 item)</h3>
                <table style="width: 270px;">
                    <tbody>
                        <tr>
                            <td style="padding: 10px 0;">Subtotal</td>
                            <td style="padding: 10px 0; text-align: end;">$20.00</td>
                        </tr>
                        <tr>
                            <td style="padding: 10px 0;">Shipping</td>
                            <td style="padding: 10px 0; text-align: end;">-</td>
                        </tr>
                        <tr>
                            <td style="padding: 10px 0;">Est. Taxes</td>
                            <td style="padding: 10px 0; text-align: end;">-</td>
                        </tr>
                        <tr>
                            <td colspan="2"><hr/ style="margin: 10px 0;"></td>
                        </tr>
                        <tr>
                            <td><b>Total</b></td>
                            <td style="text-align: end;"><b>$20.00</b></td>
                        </tr>
                        <tr>
                            <td colspan="2" style="padding: 10px 0; text-align: center;"><button style="background-color: #00f; padding: 7px 0; margin: 0 auto; width: 100%; color: white;">Checkout</button></td>
                        </tr>
                    </tbody>
                </table>
            </section>
        </div>
    </main>
    <hr/ style="margin: 0; padding: 0;">
    <footer style="display: flex; justify-content: space-between; width: 95%; margin: 0 auto; padding: 20px 0;">
        <nav style="display: flex; align-items: center;">
            <h4 style="margin-right: 30px;">Site name</h4>
            <ul style="display: flex; align-items: center; list-style: none; padding: 0;">
                <li><a href="#" style="margin: 0 10px;">Category X </a>|</li>
                <li><a href="#" style="margin: 0 10px;">Category Y </a>|</li>
                <li><a href="#" style="margin: 0 10px;">Category Z </a></li>
            </ul>
        </nav>
        <nav>
            <p style="margin: 2px 0;">Stay in touch! Join our <b>Newsletter</b></p>
            <div>
                <input type="email" placeholder="Enter Email" style="padding: 5px;">
                <button style="padding: 5px; background-color: grey; font-weight: bold; color: white;">Subscribe</button>
            </div>
        </nav>
    </footer>
