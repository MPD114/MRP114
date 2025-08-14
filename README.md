# MRP114
make web
<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>เว็บไซต์หน่วยงาน</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts: Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            -webkit-font-smoothing: antialiased;
            -moz-osx-font-smoothing: grayscale;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <!-- Header Section -->
    <header class="bg-blue-700 text-white p-4 shadow-lg">
        <div class="container mx-auto flex justify-between items-center px-4">
            <a href="#" class="text-3xl font-bold tracking-tight rounded-md">หน่วยงานของเรา</a>
            <nav>
                <ul class="flex space-x-6 text-lg">
                    <li><a href="#home" class="hover:text-blue-200 transition duration-300 ease-in-out rounded-md p-2">หน้าแรก</a></li>
                    <li><a href="#about" class="hover:text-blue-200 transition duration-300 ease-in-out rounded-md p-2">เกี่ยวกับเรา</a></li>
                    <li><a href="#services" class="hover:text-blue-200 transition duration-300 ease-in-out rounded-md p-2">บริการ</a></li>
                    <li><a href="#contact" class="hover:text-blue-200 transition duration-300 ease-in-out rounded-md p-2">ติดต่อเรา</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="home" class="bg-blue-600 text-white py-20 md:py-32 text-center rounded-b-lg shadow-xl">
        <div class="container mx-auto px-4">
            <h1 class="text-4xl md:text-6xl font-extrabold mb-6 leading-tight">มุ่งมั่นให้บริการ เพื่อประชาชน</h1>
            <p class="text-xl md:text-2xl mb-10 max-w-3xl mx-auto opacity-90">
                เราคือหน่วยงานที่พร้อมดูแลและขับเคลื่อนสังคมไปข้างหน้า ด้วยความโปร่งใสและประสิทธิภาพ
            </p>
            <a href="#services" class="bg-white text-blue-700 hover:bg-blue-100 font-bold py-3 px-8 rounded-full shadow-lg transition duration-300 ease-in-out text-lg">
                ดูบริการของเรา
            </a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-16 md:py-24 bg-white rounded-lg shadow-md mx-auto my-12 max-w-6xl px-4">
        <div class="container mx-auto">
            <h2 class="text-4xl font-bold text-center text-blue-700 mb-12">เกี่ยวกับหน่วยงานของเรา</h2>
            <div class="flex flex-col md:flex-row items-center md:space-x-12">
                <div class="md:w-1/2 mb-8 md:mb-0">
                    <img src="https://placehold.co/600x400/C0D9EE/000000?text=Agency+Image" alt="ภาพอาคารหน่วยงาน" class="rounded-lg shadow-lg w-full h-auto object-cover">
                </div>
                <div class="md:w-1/2 text-lg leading-relaxed text-gray-700">
                    <p class="mb-6">
                        หน่วยงานของเราก่อตั้งขึ้นด้วยวิสัยทัศน์ที่จะเป็นกลไกสำคัญในการพัฒนาและยกระดับคุณภาพชีวิตของประชาชน เรามุ่งเน้นการทำงานด้วยความซื่อสัตย์ โปร่งใส และมีประสิทธิภาพสูงสุด
                    </p>
                    <p class="mb-6">
                        ด้วยทีมงานที่มีความรู้ความสามารถและประสบการณ์ เราพร้อมที่จะให้บริการอย่างเต็มที่ เพื่อตอบสนองความต้องการและความคาดหวังของทุกภาคส่วน เราเชื่อมั่นว่าการทำงานร่วมกันจะนำไปสู่ความสำเร็จที่ยั่งยืน
                    </p>
                    <p>
                        พันธกิจหลักของเราคือการสร้างสรรค์นวัตกรรมใหม่ๆ และปรับปรุงกระบวนการทำงานอย่างต่อเนื่อง เพื่อให้เกิดประโยชน์สูงสุดต่อสังคมและประเทศชาติ
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-16 md:py-24 bg-blue-50 rounded-lg shadow-md mx-auto my-12 max-w-6xl px-4">
        <div class="container mx-auto">
            <h2 class="text-4xl font-bold text-center text-blue-700 mb-12">บริการหลักของเรา</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Service 1 -->
                <div class="bg-white p-8 rounded-lg shadow-md hover:shadow-xl transition duration-300 ease-in-out transform hover:-translate-y-1">
                    <div class="text-5xl text-blue-500 mb-4 text-center">💡</div>
                    <h3 class="text-2xl font-semibold text-blue-600 mb-4 text-center">บริการให้คำปรึกษา</h3>
                    <p class="text-gray-700 text-center">
                        เรามีผู้เชี่ยวชาญพร้อมให้คำปรึกษาในหลากหลายด้าน เพื่อช่วยเหลือและแนะนำแนวทางที่เหมาะสมกับคุณ
                    </p>
                </div>
                <!-- Service 2 -->
                <div class="bg-white p-8 rounded-lg shadow-md hover:shadow-xl transition duration-300 ease-in-out transform hover:-translate-y-1">
                    <div class="text-5xl text-blue-500 mb-4 text-center">📄</div>
                    <h3 class="text-2xl font-semibold text-blue-600 mb-4 text-center">การยื่นเอกสารออนไลน์</h3>
                    <p class="text-gray-700 text-center">
                        อำนวยความสะดวกในการยื่นเอกสารต่างๆ ผ่านระบบออนไลน์ที่ปลอดภัยและใช้งานง่าย
                    </p>
                </div>
                <!-- Service 3 -->
                <div class="bg-white p-8 rounded-lg shadow-md hover:shadow-xl transition duration-300 ease-in-out transform hover:-translate-y-1">
                    <div class="text-5xl text-blue-500 mb-4 text-center">📚</div>
                    <h3 class="text-2xl font-semibold text-blue-600 mb-4 text-center">ศูนย์ข้อมูลความรู้</h3>
                    <p class="text-gray-700 text-center">
                        แหล่งรวมข้อมูลและข่าวสารที่เป็นประโยชน์ ให้คุณเข้าถึงข้อมูลที่ต้องการได้อย่างรวดเร็ว
                    </p>
                </div>
                <!-- Service 4 -->
                <div class="bg-white p-8 rounded-lg shadow-md hover:shadow-xl transition duration-300 ease-in-out transform hover:-translate-y-1">
                    <div class="text-5xl text-blue-500 mb-4 text-center">🤝</div>
                    <h3 class="text-2xl font-semibold text-blue-600 mb-4 text-center">ความร่วมมือกับภาคี</h3>
                    <p class="text-gray-700 text-center">
                        เราเปิดรับความร่วมมือกับองค์กรและภาคีต่างๆ เพื่อขับเคลื่อนภารกิจร่วมกัน
                    </p>
                </div>
                <!-- Service 5 -->
                <div class="bg-white p-8 rounded-lg shadow-md hover:shadow-xl transition duration-300 ease-in-out transform hover:-translate-y-1">
                    <div class="text-5xl text-blue-500 mb-4 text-center">📞</div>
                    <h3 class="text-2xl font-semibold text-blue-600 mb-4 text-center">ช่องทางร้องเรียน/เสนอแนะ</h3>
                    <p class="text-gray-700 text-center">
                        เราให้ความสำคัญกับทุกเสียง เพื่อนำไปปรับปรุงและพัฒนาการบริการให้ดียิ่งขึ้น
                    </p>
                </div>
                <!-- Service 6 -->
                <div class="bg-white p-8 rounded-lg shadow-md hover:shadow-xl transition duration-300 ease-in-out transform hover:-translate-y-1">
                    <div class="text-5xl text-blue-500 mb-4 text-center">🗓️</div>
                    <h3 class="text-2xl font-semibold text-blue-600 mb-4 text-center">กิจกรรมและประกาศ</h3>
                    <p class="text-gray-700 text-center">
                        ติดตามข่าวสาร กิจกรรม และประกาศสำคัญจากหน่วยงานของเราได้ที่นี่
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 md:py-24 bg-white rounded-lg shadow-md mx-auto my-12 max-w-6xl px-4">
        <div class="container mx-auto">
            <h2 class="text-4xl font-bold text-center text-blue-700 mb-12">ติดต่อเรา</h2>
            <div class="flex flex-col md:flex-row md:space-x-12 items-start">
                <div class="md:w-1/2 mb-8 md:mb-0">
                    <h3 class="text-2xl font-semibold text-blue-600 mb-4">ข้อมูลการติดต่อ</h3>
                    <p class="text-gray-700 text-lg mb-2">
                        ที่อยู่: เลขที่ 123 ถนนตัวอย่าง แขวง/ตำบล ตัวอย่าง, เขต/อำเภอ ตัวอย่าง, จังหวัด ตัวอย่าง 10000
                    </p>
                    <p class="text-gray-700 text-lg mb-2">
                        โทรศัพท์: 02-123-4567
                    </p>
                    <p class="text-gray-700 text-lg mb-2">
                        อีเมล: <a href="mailto:info@agency.th" class="text-blue-600 hover:underline">info@agency.th</a>
                    </p>
                    <p class="text-gray-700 text-lg mb-4">
                        เวลาทำการ: วันจันทร์ - วันศุกร์, 08:30 - 16:30 น.
                    </p>
                    <h3 class="text-2xl font-semibold text-blue-600 mb-4">แผนที่</h3>
                    <!-- Placeholder for embedded map (e.g., Google Maps iframe) -->
                    <div class="bg-gray-200 rounded-lg w-full h-64 flex items-center justify-center text-gray-500 text-xl shadow-inner">
                        <iframe
                            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3875.0000000000005!2d100.00000000000001!3d13.000000000000000!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zMj_gMjE4JzMwLjEiTiAxMDDPgDIwJzUwLjEiRTM!5e0!3m2!1sen!2sth!4v1678901234567!5m2!1sen!2sth"
                            width="100%"
                            height="100%"
                            style="border:0;"
                            allowfullscreen=""
                            loading="lazy"
                            referrerpolicy="no-referrer-when-downgrade"
                            class="rounded-lg shadow-md"
                        ></iframe>
                    </div>
                </div>
                <div class="md:w-1/2">
                    <h3 class="text-2xl font-semibold text-blue-600 mb-4">ส่งข้อความถึงเรา</h3>
                    <form class="space-y-4">
                        <div>
                            <label for="name" class="block text-gray-700 font-medium mb-1">ชื่อ-นามสกุล:</label>
                            <input type="text" id="name" name="name" class="w-full p-3 border border-gray-300 rounded-md focus:ring-2 focus:ring-blue-500 focus:border-transparent transition duration-200" placeholder="กรุณาใส่ชื่อของคุณ">
                        </div>
                        <div>
                            <label for="email" class="block text-gray-700 font-medium mb-1">อีเมล:</label>
                            <input type="email" id="email" name="email" class="w-full p-3 border border-gray-300 rounded-md focus:ring-2 focus:ring-blue-500 focus:border-transparent transition duration-200" placeholder="กรุณาใส่อีเมลของคุณ">
                        </div>
                        <div>
                            <label for="subject" class="block text-gray-700 font-medium mb-1">หัวข้อ:</label>
                            <input type="text" id="subject" name="subject" class="w-full p-3 border border-gray-300 rounded-md focus:ring-2 focus:ring-blue-500 focus:border-transparent transition duration-200" placeholder="หัวข้อที่คุณต้องการติดต่อ">
                        </div>
                        <div>
                            <label for="message" class="block text-gray-700 font-medium mb-1">ข้อความ:</label>
                            <textarea id="message" name="message" rows="5" class="w-full p-3 border border-gray-300 rounded-md focus:ring-2 focus:ring-blue-500 focus:border-transparent transition duration-200" placeholder="พิมพ์ข้อความของคุณที่นี่"></textarea>
                        </div>
                        <button type="submit" class="w-full bg-blue-700 text-white font-bold py-3 px-6 rounded-md hover:bg-blue-800 transition duration-300 ease-in-out shadow-lg">
                            ส่งข้อความ
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer Section -->
    <footer class="bg-gray-900 text-white py-8 text-center rounded-t-lg shadow-inner">
        <div class="container mx-auto px-4">
            <p>&copy; 2024 หน่วยงานของเรา. สงวนลิขสิทธิ์ทั้งหมด.</p>
            <p class="text-sm mt-2">
                <a href="#" class="hover:underline">นโยบายความเป็นส่วนตัว</a> |
                <a href="#" class="hover:underline">ข้อกำหนดการใช้งาน</a>
            </p>
        </div>
    </footer>

</body>
</html>
