## React - Thiết lập style như thế nào?

Lúc làm theo tutorial dạy React thì phần style rất đơn giản, đơn thuần đặt class cho component, rồi đặt style cho class đó trong 1 file CSS bên ngoài. Làm thêm 1 lúc lại thấy có những khái niệm như styled-component, CSS-in-JS, xem hướng dẫn của Semantic-UI càng thấy lạ. Tra thử tài liệu của React xem hướng dẫn thì thấy mấy phần hỏi - trả lời rất tốt cho người mới học. 

[React - Styling và CSS](https://reactjs.org/docs/faq-styling.html)

### Làm thế nào để thêm CSS class vào component?

Đơn giản là truyền tên class đó dưới dạng string vào props `className`:

```js
render() {
  return <span className="menu navigation-menu">Menu</span>
}
```
Sau đó đặt thông số style cho các class `menu`, `navigation-menu` ở 1 file `.css` bên ngoài.

Việc truyền string vào props có thể được xử lý ngay trước đó theo điều kiện của props hoặc state:

```js
render() {
   let className = 'menu';
   if (this.props.isActive) {
        className += 'menu-active';
   }
   return <span className={className}> Menu </span>
}
```
Nếu thường xuyên viết kiểu trên thì ta có thể cân nhắc sử dụng 1 package tên là `className`, xem ở [đây](https://www.npmjs.com/package/classnames)

### Ta có thể dụng style kiểu "inline" được không?

Được. Xem phần hướng dẫn ở [đây](https://reactjs.org/docs/dom-elements.html#style)

### "Inline" thì dùng được, nhưng có nên dùng kiểu đó hay không?

Thường thì viết ra 1 file CSS sẽ hiệu quả hơn viết dạng inline.

### CSS-in-JS là gì?

"CSS-in-JS" để chỉ cách viết CSS trực tiếp trong JavaScript thay vì định nghĩa CSS trong 1 file bên ngoài. Có 1 vài thư viện CSS-in-JS, bạn có thể đọc so sánh giữa các thư viện ở [đây](https://github.com/MicheleBertoli/css-in-js)

*Lưu ý rằng "functionality" (viết mọi thứ theo kiểu hàm) không phải là một phần của React, mà được cung cấp bởi bên thứ 3. React không can thiệp vào lựa chọn của người dùng; nhưng một khi bản thân người dùng vẫn phân vân, thì tốt nhất cứ khởi đầu bằng việc đặt style trong 1 file `*.css` ở bên ngoài, rồi trỏ đến nó trong component thông qua `className`. 

### Tôi có thể tạo animation trong React?

React hỗ trợ những animation phức tạp. Hãy đọc các mục như [React Transition Group](https://reactcommunity.org/react-transition-group/) và [React Motion](https://github.com/chenglou/react-motion)