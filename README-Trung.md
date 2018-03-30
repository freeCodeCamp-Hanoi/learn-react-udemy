# Ghi chú của Trung Nguyễn Minh:

- Khóa ["Modern React with Redux" của Stephen Grider](https://www.udemy.com/react-redux/) tuy được đánh giá rất cao, nhưng nó có một vấn đề:
    - Chỉ 25% thời lượng dành cho React (01 app Youtube search)
    - Tận 75% thời lượng dành cho Redux (và React Router) (03 app còn lại)

- Dẫu Redux hiện tại cực kỳ phổ biến, rất nhiều người cứ nghĩ đến React là kết hợp luôn với Redux, nhưng bản thân [Dan Abramov - tác giả của Redux lại nói như sau](https://stackoverflow.com/questions/36634522/how-to-avoid-using-setprops-in-react/36636886#36636886):
    > It looks like you dived into using Redux without first getting a firm grip of React. I wouldn’t recommend doing this because you appear to be somewhat confused now.
    >
    > [Thinking in React](https://reactjs.org/docs/thinking-in-react.html) is a great guide and I recommend you to go through it first and get comfortable with the idea of state ownership in React, before using Redux.

- Do vậy, tốt hơn là nên luyện tập thêm React trước khi học đến Redux. Việc này tạm thời theo thứ tự sau:

    - **Giai đoạn 1**: Học *pure* React và 1 thư viện quan trọng là React Router

        - Học section 1 và section 2 khóa "**Modern React with Redux**" của Stephen Grider. Khóa này thực sự hay bởi tác giả rất biết cách giải thích, chia nhỏ vấn đề, lật đi lật lại để người học hiểu. Bản thân app "Youtube Video" của tác giả hướng dẫn cũng thú vị. 

        - Đọc hiểu và dịch phần [Quick Start](https://reactjs.org/docs/hello-world.html) trong tài liệu chính thức của ReactJS. Đây là phần rất cơ bản và được tổ chức có hệ thống, không thể bỏ qua.

        - Học khóa "[React for beginners](https://reactforbeginners.com/) của Wes Bos. Wes Bos nổi tiếng,  mình đã thấy được mời trình bày tại nhiều JS Conference ở châu Âu. Khóa học của Wes Bos cũng *chỉ tập trung* vào React, không hề đụng đến Redux. App trông rất ấn tượng, đủ để người dùng luyện tập với props và state. Ngoài ra còn những thứ hữu ích như:
            - React Router -> thư viện này rất quan trọng, vì nó đụng đến vấn đề chuyển giữa các trang theo kiểu hoàn toàn khác so với web tĩnh (vốn sử dụng thẻ `<a>`)
            - Deploy sản phẩm (liên quan đến authentication, Firebase, now.sh, v.v)
            - Sử dụng React Developper Tool. Tham khảo bài viết ở [đây](https://github.com/freeCodeCamp-Hanoi/learn-react-udemy/blob/master/posts/Trung-react-developper.md).

        - Tự làm 2 -3 "app" chỉ có MỘT và CHỈ MỘT trang bằng React. Một app dạng này có thể tham khảo là [Pabla](https://goshakkk.name/pabla/index.html)

        - Đọc[Hướng dẫn sử dụng create-react-app](https://github.com/facebook/create-react-app/blob/master/packages/react-scripts/template/README.md). Phát hiện ra cái này cực kỳ chi tiết, đội Facebook rất chăm chút cho nó, và viết hướng dẫn sử dụng không khác gì hướng dẫn làm app. Đây là 1 điểm khởi đầu rất tốt để phát triển ứng dụng App thay vì sử dụng ReactSimpleStarter của Stephen Grider.

        - Học theo [tutorial của chính React Router](https://github.com/reactjs/react-router-tutorial/tree/master/lessons/01-setting-up). Như đã nói ở trên, phần routing trong React rất mới, bắt buộc phải biết để làm những thứ tưởng chừng đơn giản, đó là nav bar.
        
        - Ngoài ra, có thể tham khảo các demo app thực hiện bởi Mr. Lê Quân ở [Facebook group "Pure React"](https://www.facebook.com/groups/purereact/)

    - **Giai đoạn 2**: Học Redux trong các section tiếp theo của "Modern React with Redux". 

## App tự làm:

- Kính vạn hoa bản đơn giản: Vẽ 01 siprograph dựa trên các thông số về màu nền, màu nét, và các thông số khác:
    - Link product: http://travisnguyen.net/react-draw-spirograph/
    - Link Github repo: https://github.com/ngminhtrung/react-draw-spirograph

## Bài viết hay

### Kỹ thuật
- [https://goshakkk.name/controlled-vs-uncontrolled-inputs-react/](https://goshakkk.name/controlled-vs-uncontrolled-inputs-react/): So sánh 2 kỹ thuật tạo form trong React.
- [Hướng dẫn sử dụng create-react-app](https://github.com/facebook/create-react-app/blob/master/packages/react-scripts/template/README.md): Cực kỳ chi tiết

### Kinh nghiệm chung
- [So you completed the official React tutorial. What's next?](https://goshakkk.name/next-steps-official-react-tutorial/): Một vài hướng đi sau khi làm xong tutorial (game X O) trên trang của React. 
- [Where do I get ideas for my learning projects?](https://goshakkk.name/learning-project-ideas/): Lấy ý tưởng để làm projec tự học ở đâu?
- [5 practical tips to finally learn React in 2018](https://goshakkk.name/tips-finally-learn-react/): 5 kinh nghiệm thực tế để học React năm 2018
- [You Might Not Need Redux](https://medium.com/@dan_abramov/you-might-not-need-redux-be46360cf367): Bài viết của Dan Abramov - tác giả Redux.

### Nguồn bài viết tiếng Việt
- [kipalog](https://kipalog.com/search?q=reactjs)
- [ehkoo](https://ehkoo.com/chu-de/react)
- [viblog.asia](https://viblo.asia/search?q=reactjs)

## Ghi chú chi tiết:

- [Sử dụng React Developper Tool để sờ nắn được state, props, method](https://github.com/freeCodeCamp-Hanoi/learn-react-udemy/blob/master/posts/Trung-react-developper.md)
- [Style trong React như thế nào](https://github.com/freeCodeCamp-Hanoi/learn-react-udemy/blob/master/posts/Trung-style-in-react.md)


## Danh sách câu hỏi:

1. Làm sao truyền props vào component để thay đổi style của component đó?
2. Trong hướng dẫn sử dụng "create-reat-app" có mục "ejecting". Vậy "ejecting" là gì?
3. Có thể truyền props để đổi class của component được hay không?
