Thư viện,Mục đích,Dùng để làm gì trong Smart Doc Search,Ví dụ thực tế
react-router-dom,Điều hướng trang (Routing),"Chuyển đổi giữa các trang: /login, /dashboard, /search, /admin","<Route path=""/search"" element={<SearchPage />} />"
axios,Gọi API HTTP,"Gửi request đến backend: POST /api/documents/upload, GET /api/search","axios.post('/api/auth/login', { email, password })"
lucide-react,"Icon hiện đại, nhẹ, đẹp","Thay thế FontAwesome, dùng icon: Search, Upload, User, Bell","<Search className=""w-5 h-5"" />"
framer-motion,Animation mượt như phim,"Hiệu ứng: fade in, slide, hover scale, drag & drop",<motion.div animate={{ scale: 1.05 }}>
react-hot-toast,Thông báo đẹp (Toast),"Hiển thị: ""Upload thành công!"", ""Lỗi mật khẩu"", ""Đang xử lý...""",toast.success('Tài liệu đã được tải lên!')
react-dropzone,Drag & Drop file,Kéo thả file PDF/JPG vào vùng upload,<div {...getRootProps()}>Kéo file vào đây</div>
react-pdf,Xem PDF trong trình duyệt,Hiển thị file PDF + highlight từ khóa tìm được,<Document file={url}><Page pageNumber={1} /></Document>
@headlessui/react,UI không kiểu sẵn (unstyled),"Tạo dropdown, modal, tab đẹp + accessible mà vẫn tùy chỉnh",<Menu><Menu.Button>More</Menu.Button></Menu>
@heroicons/react,"Icon đơn giản, chuẩn Tailwind","Icon nhỏ: X, Check, Arrow, dùng trong button, list","<X className=""w-4 h-4"" />"
