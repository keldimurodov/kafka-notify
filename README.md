# kafka-notify

<!-- Barcha kodlarni yozib bo'lgach go mod init va go mod tidy qilish kerak -->
<!-- Undan so'ng esa terminalni ochib quyidagi buyruqni kiritish kerak go run cmd/producer/producer.go -->
<!-- Undan so'ng esa ikkinchi terminalni ochib quyidagi buyruqni kiritish kerak go run cmd/consumer/consumer.go -->
<!-- Endi esa uchinchi terminalni ochib curl bildirishnomalarini yuborish uchun 'curl -X POST http://localhost:8080/send \
-d "fromID=2&toID=1&message=Oybek started following you." ' buyruqni yozish kerak -->
<!-- Keyin esa bu komandani kiritamiz terminalga ' curl -X POST http://localhost:8080/send \
-d "fromID=1&toID=2&message=Aziza mentioned you in a comment: 'Great seeing you yesterday, @Oybek!'" ' -->
<!-- Keyin esa terminalga ' curl http://localhost:8081/notifications/1 ' bu komandani kiritsak Emmaga xabar kelganini ko'ramiz. -->