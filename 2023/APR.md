## 2023년 4월 5일(수)

- 빅데이터 시스템 설계
  db.restaurants.find({$and: [{"grades.grade": "A"}, {cuisine: "Hamburgers"}, {borough: {$nin: ["Manhattan", "Queens", "Staten Island" , "Bronx"] }}]}, {restaurant_id: 1, name: 1, borough: 1, cuisine: 1, \_id:0})
