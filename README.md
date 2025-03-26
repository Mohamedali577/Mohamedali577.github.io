# Mohamedali577.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Azzuria Store</title>
</head>
<body style="margin: 0; font-family: Arial, sans-serif; text-transform: uppercase; text-align: center; background-color: #f5f5f5; overflow-x: hidden;">

    <!-- Header -->
    <div style="background-color: black; color: white; padding: 20px; display: flex; flex-direction: column; align-items: center;">
        <!-- Centered & Enlarged Logo -->
        <img src="https://i.ibb.co/cSddNnNM/IMG-20240418-WA0000.jpg" alt="Azzuria Store Logo" style="height: 150px; transition: transform 0.3s ease;" onmouseover="this.style.transform='scale(1.05)'" onmouseout="this.style.transform='scale(1)'">

        <!-- Buttons and Cart Icon -->
        <div style="margin-top: 10px;">
            <button style="background: none; border: none; color: white; font-size: 14px; cursor: pointer; margin-right: 20px; transition: opacity 0.3s ease;" onmouseover="this.style.opacity='0.8'" onmouseout="this.style.opacity='1'">Contact</button>
            <button style="background: none; border: none; color: white; font-size: 14px; cursor: pointer; margin-right: 20px; transition: opacity 0.3s ease;" onmouseover="this.style.opacity='0.8'" onmouseout="this.style.opacity='1'">About</button>
            <!-- White Cart Icon -->
            <button style="background: none; border: none; cursor: pointer;">
                <img src="https://cdn-icons-png.flaticon.com/512/1413/1413908.png" alt="Cart Icon" style="height: 15px; filter: brightness(0) invert(1);">
            </button>
        </div>
    </div>

    <!-- Navigation -->
    <div style="background-color: white; padding: 15px; text-align: center; font-size: 18px; font-weight: bold; justify-content:space-between ">
        <button style="background: none; border: 2px solid black; border-radius: 5px; font-size: 18px; font-weight: bold; margin: 0 15px; cursor: pointer; padding: 10px 20px; transition: all 0.3s ease;" onmouseover="this.style.backgroundColor='black'; this.style.color='white'" onmouseout="this.style.backgroundColor='transparent'; this.style.color='black'">Menswear</button>
        <button style="background: none; border: 2px solid black; border-radius: 5px; font-size: 18px; font-weight: bold; margin: 0 15px; cursor: pointer; padding: 10px 20px; transition: all 0.3s ease;" onmouseover="this.style.backgroundColor='black'; this.style.color='white'" onmouseout="this.style.backgroundColor='transparent'; this.style.color='black'">Womenswear</button>
        <button style="background: none; border: 2px solid black; border-radius: 5px; font-size: 18px; font-weight: bold; margin: 0 15px; cursor: pointer; padding: 10px 20px; transition: all 0.3s ease;" onmouseover="this.style.backgroundColor='black'; this.style.color='white'" onmouseout="this.style.backgroundColor='transparent'; this.style.color='black'">Accessories</button>
        <button style="background: none; border: 2px solid black; border-radius: 5px; font-size: 18px; font-weight: bold; margin: 0 15px; cursor: pointer; padding: 10px 20px; transition: all 0.3s ease;" onmouseover="this.style.backgroundColor='black'; this.style.color='white'" onmouseout="this.style.backgroundColor='transparent'; this.style.color='black'">Other</button>
    </div>

    <!-- Shop Category -->
    <div style="background-color: #000000; width: 100%; height: 50px; display: flex; justify-content: space-between; align-items: center; padding: 0 20px; box-sizing: border-box;">
        <!-- Shop Text (Left) -->
        <h2 style="color: #fff; margin: 0;">SHOP</h2>
        <!-- Align Justify Icon (Right) -->
        <svg id="menu-button" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512" style="width: 24px; height: 24px; fill: white; cursor: pointer;">
            <path d="M0 64C0 46.3 14.3 32 32 32H416c17.7 0 32 14.3 32 32s-14.3 32-32 32H32C14.3 96 0 81.7 0 64zM0 256c0-17.7 14.3-32 32-32H416c17.7 0 32 14.3 32 32s-14.3 32-32 32H32c-17.7 0-32-14.3-32-32zM448 448c0 17.7-14.3 32-32 32H32c-17.7 0-32-14.3-32-32s14.3-32 32-32H416c17.7 0 32 14.3 32 32z"/>
        </svg>
    </div>

    <!-- Slide-out Menu -->
    <div id="slide-out-menu" style="position: fixed; top: 0; right: -300px; width: 300px; height: 100%; background-color: black; color: white; transition: right 0.3s ease; z-index: 1000;">
        <!-- Close Button -->
        <div style="display: flex; justify-content: flex-end; padding: 10px;">
            <svg id="close-button" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512" style="width: 24px; height: 24px; fill: white; cursor: pointer;">
                <path d="M376.6 84.5c11.3-13.6 9.5-33.8-4.1-45.1s-33.8-9.5-45.1 4.1L192 206 56.6 43.5C45.3 29.9 25.1 28.1 11.5 39.4S-3.9 70.9 7.4 84.5L150.3 256 7.4 427.5c-11.3 13.6-9.5 33.8 4.1 45.1s33.8 9.5 45.1-4.1L192 306 327.4 468.5c11.3 13.6 31.5 15.4 45.1 4.1s15.4-31.5 4.1-45.1L233.7 256 376.6 84.5z"/>
            </svg>
        </div>
        <!-- Menu Content -->
        <div style="padding: 20px;">
            <h2 style="color: white; margin: 0;">Menu</h2>
            <ul style="list-style: none; padding: 0;">
                <li style="margin: 15px 0;">
                    <a href="index.html" style="color: white; text-decoration: none;">Home</a>
                </li>
                <li style="margin: 15px 0;"><a href="#" style="color: white; text-decoration: none;">Products</a></li>
                <li style="margin: 15px 0;"><a href="#" style="color: white; text-decoration: none;">About Us</a></li>
                <li style="margin: 15px 0;"><a href="#" style="color: white; text-decoration: none;">Contact</a></li>
            </ul>
        </div>
    </div>

    <!-- Overlay -->
    <div id="overlay" style="position: fixed; top: 0; left: 0; width: 100%; height: 100%; background-color: rgba(0, 0, 0, 0.5); display: none; z-index: 999;"></div>

    <!-- New Black Div with 6 White Radius Signs -->
    <div style="background-color: black; padding: 20px;">
        <div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 20px;">
            <!-- T-Shirts -->
            <button style="background-color: white; border: none; border-radius: 10px; padding: 20px; text-align: center; cursor: pointer; transition: transform 0.3s ease;" onmouseover="this.style.transform='scale(1.05)'" onmouseout="this.style.transform='scale(1)'">
                <img src="https://cdn-icons-png.flaticon.com/512/3005/3005895.png" alt="T-Shirts" style="width: 50px; height: 50px;">
                <p style="color: black; margin: 10px 0 0; font-weight: bold;">T-Shirts</p>
            </button>
            <!-- Pants -->
            <button style="background-color: white; border: none; border-radius: 10px; padding: 20px; text-align: center; cursor: pointer; transition: transform 0.3s ease;" onmouseover="this.style.transform='scale(1.05)'" onmouseout="this.style.transform='scale(1)'">
                <img src="https://cdn-icons-png.flaticon.com/512/2122/2122621.png" alt="Pants" style="width: 50px; height: 50px;">
                <p style="color: black; margin: 10px 0 0; font-weight: bold;">Pants</p>
            </button>
            <!-- Dresses -->
            <button style="background-color: white; border: none; border-radius: 10px; padding: 20px; text-align: center; cursor: pointer; transition: transform 0.3s ease;" onmouseover="this.style.transform='scale(1.05)'" onmouseout="this.style.transform='scale(1)'">
                <img src="https://cdn-icons-png.flaticon.com/512/14300/14300563.png" alt="Dresses" style="width: 50px; height: 50px;">
                <p style="color: black; margin: 10px 0 0; font-weight: bold;">Dresses</p>
            </button>
            <!-- Shoes -->
            <button style="background-color: white; border: none; border-radius: 10px; padding: 20px; text-align: center; cursor: pointer; transition: transform 0.3s ease;" onmouseover="this.style.transform='scale(1.05)'" onmouseout="this.style.transform='scale(1)'">
                <img src="https://cdn-icons-png.flaticon.com/512/2742/2742687.png" alt="Shoes" style="width: 50px; height: 50px;">
                <p style="color: black; margin: 10px 0 0; font-weight: bold;">Shoes</p>
            </button>
            <!-- Watches -->
            <button style="background-color: white; border: none; border-radius: 10px; padding: 20px; text-align: center; cursor: pointer; transition: transform 0.3s ease;" onmouseover="this.style.transform='scale(1.05)'" onmouseout="this.style.transform='scale(1)'">
                <img src="https://cdn-icons-png.flaticon.com/512/3109/3109881.png" alt="Watches" style="width: 50px; height: 50px;">
                <p style="color: black; margin: 10px 0 0; font-weight: bold;">Watches</p>
            </button>
            <!-- Accessories -->
            <button style="background-color: white; border: none; border-radius: 10px; padding: 20px; text-align: center; cursor: pointer; transition: transform 0.3s ease;" onmouseover="this.style.transform='scale(1.05)'" onmouseout="this.style.transform='scale(1)'">
                <img src="https://cdn-icons-png.flaticon.com/512/4100/4100910.png" alt="Accessories" style="width: 50px; height: 50px;">
                <p style="color: black; margin: 10px 0 0; font-weight: bold;">Accessories</p>
            </button>
        </div>
    </div>

    <!-- Featured Products Section with Images -->
    <div style="background-color: white; padding: 40px 20px;">
        <h2 style="color: black; margin-bottom: 20px;">FEATURED PRODUCTS</h2>
        <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 30px; padding: 0 20px;">
            <!-- Product 1 -->
            <div style="background-color: #f9f9f9; border-radius: 10px; overflow: hidden; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); transition: all 0.3s ease;" onmouseover="this.style.transform='scale(1.05)'" onmouseout="this.style.transform='scale(1)'">
                <img src="https://images.unsplash.com/photo-1591047139829-d91aecb6caea?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80" alt="Leather Jacket" style="width: 100%; height: 250px; object-fit: cover;">
                <div style="padding: 15px;">
                    <h3 style="color: black; margin: 10px 0;">LEATHER JACKET</h3>
                    <p style="color: #555; margin: 5px 0;">199 TND</p>
                    <button style="background-color: black; color: white; border: none; border-radius: 5px; padding: 10px 20px; cursor: pointer; transition: opacity 0.3s ease;" onmouseover="this.style.opacity='0.8'" onmouseout="this.style.opacity='1'">ADD TO CART</button>
                </div>
            </div>
            
            <!-- Product 2 -->
            <div style="background-color: #f9f9f9; border-radius: 10px; overflow: hidden; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); transition: all 0.3s ease;" onmouseover="this.style.transform='scale(1.05)'" onmouseout="this.style.transform='scale(1)'">
                <img src="https://images.unsplash.com/photo-1539109136881-3be0616acf4b?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80" alt="Black Dress" style="width: 100%; height: 250px; object-fit: cover;">
                <div style="padding: 15px;">
                    <h3 style="color: black; margin: 10px 0;">ELEGANT DRESS</h3>
                    <p style="color: #555; margin: 5px 0;">149 TND</p>
                    <button style="background-color: black; color: white; border: none; border-radius: 5px; padding: 10px 20px; cursor: pointer; transition: opacity 0.3s ease;" onmouseover="this.style.opacity='0.8'" onmouseout="this.style.opacity='1'">ADD TO CART</button>
                </div>
            </div>
            
            <!-- Product 3 -->
            <div style="background-color: #f9f9f9; border-radius: 10px; overflow: hidden; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); transition: all 0.3s ease;" onmouseover="this.style.transform='scale(1.05)'" onmouseout="this.style.transform='scale(1)'">
                <img src="https://images.unsplash.com/photo-1600269452121-4f2416e55c28?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80" alt="White Sneakers" style="width: 100%; height: 250px; object-fit: cover;">
                <div style="padding: 15px;">
                    <h3 style="color: black; margin: 10px 0;">CLASSIC SNEAKERS</h3>
                    <p style="color: #555; margin: 5px 0;">129 TND</p>
                    <button style="background-color: black; color: white; border: none; border-radius: 5px; padding: 10px 20px; cursor: pointer; transition: opacity 0.3s ease;" onmouseover="this.style.opacity='0.8'" onmouseout="this.style.opacity='1'">ADD TO CART</button>
                </div>
            </div>
            
            <!-- Product 4 -->
            <div style="background-color: #f9f9f9; border-radius: 10px; overflow: hidden; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); transition: all 0.3s ease;" onmouseover="this.style.transform='scale(1.05)'" onmouseout="this.style.transform='scale(1)'">
                <img src="https://images.unsplash.com/photo-1523170335258-f5ed11844a49?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80" alt="Luxury Watch" style="width: 100%; height: 250px; object-fit: cover;">
                <div style="padding: 15px;">
                    <h3 style="color: black; margin: 10px 0;">PREMIUM WATCH</h3>
                    <p style="color: #555; margin: 5px 0;">299 TND</p>
                    <button style="background-color: black; color: white; border: none; border-radius: 5px; padding: 10px 20px; cursor: pointer; transition: opacity 0.3s ease;" onmouseover="this.style.opacity='0.8'" onmouseout="this.style.opacity='1'">ADD TO CART</button>
                </div>
            </div>
        </div>
    </div>

    <!-- New Div: Picture Section -->
    <div style="
        background-image: url('https://images.unsplash.com/photo-1607083206968-13611e3d76db?ixlib=rb-1.2.1&auto=format&fit=crop&w=1950&q=80');
        background-size: cover;
        background-position: center;
        height: 400px;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        color: white;
        text-align: center;
        padding: 0 20px;
    ">
        <h2 style="font-size: 2.5rem; margin: 0; text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);">NEW COLLECTION</h2>
        <p style="font-size: 1.2rem; margin: 10px 0; text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);">EXPLORE OUR LATEST FASHION TRENDS.</p>
        <button style="
            background-color: black;
            color: white;
            border: none;
            border-radius: 5px;
            padding: 10px 20px;
            font-size: 1rem;
            cursor: pointer;
            transition: opacity 0.3s ease;
        " onmouseover="this.style.opacity='0.8'" onmouseout="this.style.opacity='1'">SHOP NOW</button>
    </div>

    <!-- New Div: Contact Us Section -->
    <div style="background-color: black; color: white; padding: 40px 20px;">
        <h2 style="margin: 0; font-size: 2rem;">CONTACT US</h2>
        <p style="font-size: 1.2rem; margin: 10px 0;">FOLLOW US ON SOCIAL MEDIA OR REACH OUT DIRECTLY:</p>
        
        <!-- Social Media Icons -->
        <div style="display: flex; justify-content: center; gap: 20px; margin: 20px 0;">
            <!-- Facebook -->
            <a href="#" style="color: white; text-decoration: none;">
                <img src="https://cdn-icons-png.flaticon.com/512/1384/1384053.png" alt="Facebook" style="width: 30px; height: 30px;">
            </a>
            <!-- Instagram -->
            <a href="#" style="color: white; text-decoration: none;">
                <img src="https://cdn-icons-png.flaticon.com/512/1384/1384063.png" alt="Instagram" style="width: 30px; height: 30px;">
            </a>
            <!-- Twitter -->
            <a href="#" style="color: white; text-decoration: none;">
                <img src="https://cdn-icons-png.flaticon.com/512/1384/1384068.png" alt="Twitter" style="width: 30px; height: 30px;">
            </a>
        </div>

        <!-- Email and Phone -->
        <div style="margin-top: 20px;">
            <p style="font-size: 1rem; margin: 5px 0;">EMAIL: <a href="mailto:azzuriaaccess@gmail.com" style="color: white; text-decoration: none;">AZZURIAACCESS@GMAIL.COM</a></p>
            <p style="font-size: 1rem; margin: 5px 0;">PHONE: <a href="tel:+21690736044" style="color: white; text-decoration: none;">+216 90 736 044</a></p>
        </div>
    </div>

    <script>
        // Toggle the slide-out menu
        const menuButton = document.getElementById('menu-button');
        const slideOutMenu = document.getElementById('slide-out-menu');
        const overlay = document.getElementById('overlay');
        const closeButton = document.getElementById('close-button');

        menuButton.addEventListener('click', () => {
            if (slideOutMenu.style.right === '-300px') {
                slideOutMenu.style.right = '0';
                overlay.style.display = 'block';
            } else {
                slideOutMenu.style.right = '-300px';
                overlay.style.display = 'none';
            }
        });

        closeButton.addEventListener('click', () => {
            slideOutMenu.style.right = '-300px';
            overlay.style.display = 'none';
        });

        overlay.addEventListener('click', () => {
            slideOutMenu.style.right = '-300px';
            overlay.style.display = 'none';
        });
    </script>
</body>
</html>
