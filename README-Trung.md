Ghi chú của Trung Nguyễn Minh:

- Khóa "Modern React with Redux" của Stephen Grider tuy được đánh giá rất cao, nhưng nó có một vấn đề:
    - Chỉ 25% thời lượng dành cho React (01 app Youtube search)
    - Tận 75% thời lượng dành cho Redux (và React Router) (03 app còn lại)

- Dẫu Redux hiện tại cực kỳ phổ biến, rất nhiều người cứ dùng React là dùng theo Redux, nhưng vẫn cần luyện tập thêm React trước khi học đến Redux. Đây là những gì Dan Abramov - tác giả của Redux viết:
    > It looks like you dived into using Redux without first getting a firm grip of React. I wouldn’t recommend doing this because you appear to be somewhat confused now.
    >
    > [Thinking in React](https://reactjs.org/docs/thinking-in-react.html) is a great guide and I recommend you to go through it first and get comfortable with the idea of state ownership in React, before using Redux.

- Do vậy, mình sẽ học theo thứ tự sau:
    - **Giai đoạn 1**: Học *pure* React và 1 thư viện quan trọng là React Router
        - Học section 1 và section 2 khóa "**Modern React with Redux**" của Stephen Grider. Khóa này thực sự hay bởi tác giả rất biết cách giải thích, chia nhỏ vấn đề, lật đi lật lại để người học hiểu. Bản thân app "Youtube Video" của tác giả hướng dẫn cũng thú vị. 
        - Đọc hiểu và dịch phần [Quick Start](https://reactjs.org/docs/hello-world.html) trong tài liệu chính thức của ReactJS. Đây là phần rất cơ bản và được tổ chức có hệ thống, không thể bỏ qua.
        - Học khóa "[React for beginners](https://reactforbeginners.com/) của Wes Bos. Wes Bos nổi tiếng,  mình đã thấy được mời trình bày tại nhiều JS Conference ở châu Âu. Khóa học của Wes Bos cũng *chỉ tập trung* vào React, không hề đụng đến Redux. App trông rất ấn tượng, đủ để người dùng luyện tập với props và state. Ngoài ra còn những thứ hữu ích như:
            - React Router -> thư viện này rất quan trọng, vì nó đụng đến vấn đề chuyển giữa các trang theo kiểu hoàn toàn khác so với web tĩnh (sử dụng thẻ `<a>`)
            - Deploy sản phẩm (liên quan đến authentication, Firebase, now.sh, v.v)
        - Học theo [tutorial của chính React Router]((https://github.com/reactjs/react-router-tutorial/tree/master/lessons/01-setting-up). Như đã nói ở trên, phần routing trong React rất mới, bắt buộc phải biết để làm những thứ tưởng chừng đơn giản, đó là nav bar.
        - Ngoài ra, có thể tham khảo các demo app thực hiện bởi Mr. Lê Quân ở [Facebook group "Pure React"](https://www.facebook.com/groups/purereact/)

    - **Giai đoạn 2**: Học Redux trong các section tiếp theo của "Modern React with Redux".

