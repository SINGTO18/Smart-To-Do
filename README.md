สร้างเว็บไซต์ Smart Todo List ด้วย React + JavaScript และ CSS รองรับมือถือ ไม่เพิ่ม library และเก็บข้อมูลใน localStorage
มีเพิ่ม แก้ไข ค้นหา กรองงาน และ TodoItem รับ props: title, priority, dueDate, completed พร้อมปุ่ม toggle/delete ส่ง callback กลับ Parent
ส่ง Prompt ที่ใช้ + Code ที่ได้ครบทุกไฟล์ พร้อมวิธีรันและคำอธิบาย props/callback โดยไม่แก้ไข props โดยตรง
ส่ง Checklist 5 จุดให้ตรวจเอง: แสดง props, toggle, delete, validation/localStorage และ responsive/คีย์บอร์ด พร้อมชี้โค้ดหนึ่งจุดให้ลองแก้
**Checklist:**

1. **Props:** `TodoItem` renders `title`, `priority`, `dueDate`, and `completed`. It also receives `id` for task actions.
2. **Callbacks:** `App` passes `id={[task.id](http://task.id)}`. Toggle calls `onToggle(id)` and Delete calls `onDelete(id)`, forwarding that task's ID.
3. **Buttons:** Both actions use real `<button type="button">` elements.
4. **Dependencies:** `TodoItem` imports only its local stylesheet; it uses no additional libraries.
5. 
**Readability and responsiveness:** Descriptive class names organize
the markup and styles. The item wraps on narrow screens, and its actions
expand to full width below 480px.
เปลี่ยนโทนของ website เป็นโทนสี Cream และฟ้าอ่อนๆ และ หากเม้าส์ Hover มีประกายรอบๆเม้าส้์ด้วย
และเปลี่ยนหน้าตาเว็บเป็นภาษาอังกฤษหน่อยครับ
่เช่นงาน ทั้งหมด เป็น All Tasks
ทำเสร็จแล้วเป็น Complete
ความคืบหน้า เป็น on process
เป็นตันครับ
