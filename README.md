<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nhà Trẻ 12A1 2024-2025</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #ffe6f2;
            color: #d63384;
        }
        h1 {
            color: #fff;
            background: #ff85a2;
            padding: 15px;
            border-radius: 10px;
            display: inline-block;
            margin-top: 20px;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
        }
        .person {
            width: 250px;
            margin: 10px;
            padding: 15px;
            background: #ffb3c6;
            border: 2px solid #ff4d79;
            border-radius: 12px;
            text-align: center;
            box-shadow: 2px 2px 10px rgba(255, 77, 121, 0.2);
        }
        .person img {
            width: 100%;
            height: auto;
            border-radius: 10px;
            border: 3px solid #ff4d79;
        }
    </style>
</head>
<body>

    <h1>Nhà Trẻ 12A1 2024-2025</h1>
    <div class="container">
        <!-- Danh sách người -->
        <script>
            let people = [
                { name: "Lê Văn An", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=A" },
                { name: "Trần Huỳnh Quyền Anh", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=B" },
                { name: "Nguyễn Chi Bảo", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=C" },
                { name: "Danh Ngọc Duy", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=D" },
                { name: "Trần Hoàng Duy", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=E" },
                { name: "Nguyễn Ngọc Thùy Dương", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=F" },
                { name: "Trần Nhật Dương", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=G" },
                { name: "Võ Thành Đạt", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=H" },
                { name: "Nguyễn Thanh Điền", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=I" },
                { name: "Võ Nguyễn Anh Hào", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=J" },
                { name: "Nguyễn Khang Hy", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=A" },
                { name: "Phan Chung Kin", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=J" },
                { name: "Quách Tín Hỷ", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=B" },
                { name: "Vương Hào Kiệt", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=C" },
                { name: "Lê Thị Yến Linh", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=D" },
                { name: "Mai Bích Ngọc", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=E" },
                { name: "Quan Như Ngọc", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=F" },
                { name: "Trần Khánh Ngọc ", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=G" },
                { name: "Lâm Ý Nguyện", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=H" },
                { name: "Nguyễn Hoàng Nhật", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=I" },
                { name: "Nguyễn Yến Nhi", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=J" },
                { name: "Trần Huỳnh Bảo Như", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=A" },
                { name: "Chung Tấn Phát", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=B" },
                { name: "Nguyễn Tấn Phát", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=C" },
                { name: "Nguyễn Thị Hồng Phấn", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=D" },
                { name: "Nguyễn Triệu Phú", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=E" },
                { name: "Nguyễn Lê Kim Thanh Phúc", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=F" },
                { name: "Huỳnh Thị Ngọc Thanh ", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=G" },
                { name: "Nguyễn Chí Thành", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=H" },
                { name: "Trần Thị Như Thảo", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=I" },
                { name: "Lý Huy Thiếp", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=J" },
                { name: "Phạm Ngọc Thoại", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=A" },
                { name: "Võ Huỳnh Minh Thư", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=B" },
                { name: "Võ Lê Bảo Thy", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=C" },
                { name: "Trần Trung Toàn", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=D" },
                { name: "Nguyễn Huỳnh Trâm", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=E" },
                { name: "Trần Thị Bảo Trâm", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=F" },
                { name: "Thạch Trần Thiên Tú", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=G" },
                { name: "Huỳnh Sơn Thiên Tứ", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=H" },
                { name: "Trần Gia Tường", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=I" },
                { name: "Trần Khương Tường", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=A" },
                { name : "Trần Phương Vy", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=B" },
                { name: "Trần Thanh Kiều Vy", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=C" },
                { name: "Trần Thị Thúy Vy", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=D" },
                { name: "Trần Ngọc Bảo Xuyến", img: "https://via.placeholder.com/250x200/ff85a2/ffffff?text=E" }
            ];

            let container = document.querySelector('.container');

            people.forEach((person, index) => {
                let div = document.createElement('div');
                div.classList.add('person');
                div.innerHTML = `
                    <h3>${index + 1}. ${person.name}</h3>
                    <img src="${person.img}" alt="${person.name}">
                `;
                container.appendChild(div);
            });
        </script>
    </div>

</body>
</html>
