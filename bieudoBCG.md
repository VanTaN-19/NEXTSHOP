quadrantChart
    title Ma trận BCG của Vinamilk (Dựa trên số liệu cung cấp)
    x-axis "Thị phần tương đối (Thấp)" --> "Thị phần tương đối (Cao)"
    y-axis "Tăng trưởng ngành (Thấp)" --> "Tăng trưởng ngành (Cao)"
    
    %% Trục X (Thị phần tương đối) chia tại 1.0
    %% Trục Y (Tăng trưởng ngành) chia tại 10%
    
    quadrant-1 "Ngôi sao (Stars)"
    quadrant-2 "Dấu chấm hỏi (?)"
    quadrant-3 "Con chó (Dogs)"
    quadrant-4 "Bò sữa (Cash Cows)"
    
    %% -- Dữ liệu SBU: [X = Thị phần tương đối, Y = Tăng trưởng ngành, Kích thước = Doanh thu] --
    
    %% --- Ô NGÔI SAO (Tăng trưởng > 10%, Thị phần > 1.0) ---
    "Sữa nước": [1.68, 20.5, 9500]
    "Sữa bột": [1.66, 22.8, 7850]
    "Sữa chua uống": [1.81, 17.5, 3200]
    "Sữa chua ăn": [8.70, 11.8, 4700]

    %% --- Ô BÒ SỮA (Tăng trưởng < 10%, Thị phần > 1.0) ---
    "Sữa đặc": [3.22, 9.5, 4600]

    %% --- Ô CON CHÓ (Tăng trưởng < 10%, Thị phần < 1.0) ---
    "Kem ăn": [0.37, 2.1, 500] %% Doanh thu "Không đáng kể", dùng giá trị nhỏ tượng trưng

    %% --- Ô DẤU HỎI (Tăng trưởng > 10%, Thị phần < 1.0) ---
    %% (Không có SBU nào trong ô này dựa trên dữ liệu)
