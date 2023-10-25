আমি সেই সমস্ত অপারেটরগুলির জন্য উদাহরণ সাথে কিছু উদাহরণ দেয়া যাক:

**7-2: $ne, $gt, $lt, $gte, $lte অপারেটর**

- **$ne (সমান নয়) অপারেটর:**
  উদাহরণ: সমান নয় অপারেটর ($ne) ব্যবহার করে "age" ফিল্ডের মান 25 নয়:

  ```javascript
  db.users.find({ age: { $ne: 25 } })
  ```

- **$gt (বড় হওয়া) অপারেটর:**
  উদাহরণ: বড় অপারেটর ($gt) ব্যবহার করে "score" ফিল্ডের মান 80 এর চেয়ে বড়:

  ```javascript
  db.scores.find({ score: { $gt: 80 } })
  ```

- **$lt (ছোট হওয়া) অপারেটর:**
  উদাহরণ: ছোট অপারেটর ($lt) ব্যবহার করে "price" ফিল্ডের মান 50 এর চেয়ে ছোট:

  ```javascript
  db.products.find({ price: { $lt: 50 } })
  ```

- **$gte (বড় অথবা সমান হওয়া) অপারেটর:**
  উদাহরণ: বড় অথবা সমান অপারেটর ($gte) ব্যবহার করে "quantity" ফিল্ডের মান 100 এর চেয়ে বড় অথবা সমান:

  ```javascript
  db.inventory.find({ quantity: { $gte: 100 } })
  ```

- **$lte (ছোট অথবা সমান হওয়া) অপারেটর:**
  উদাহরণ: ছোট অথবা সমান অপারেটর ($lte) ব্যবহার করে "temperature" ফিল্ডের মান 30 এর চেয়ে ছোট অথবা সমান:

  ```javascript
  db.weather.find({ temperature: { $lte: 30 } })
  ```

**7-3: $in, $nin, নেস্টেড কন্ডিশন**

- **$in (সম্মিলিত) অপারেটর:**
  উদাহরণ: $in অপারেটর ব্যবহার করে "tags" ফিল্ডের মানের মধ্যে "mongodb" বা "node.js" সম্মিলিত ডকুমেন্ট সিলেক্ট করা:

  ```javascript
  db.articles.find({ tags: { $in: ["mongodb", "node.js"] } })
  ```

- **$nin (সম্মিলিত নয়) অপারেটর:**
  উদাহরণ: $nin অপারেটর ব্যবহার করে "colors" ফিল্ডের মানের মধ্যে "red" এবং "blue" সম্মিলিত না থাকা ডকুমেন্ট সিলেক্ট করা:

  ```javascript
  db.products.find({ colors: { $nin: ["red", "blue"] } })
  ```

- **নেস্টেড কন্ডিশন:**
  উদাহরণ: নেস্টেড কন্ডিশন ব্যবহার করে, "students" কালেকশনের ডকুমেন্ট সিলেক্ট করা হয় যেগুলির "grades" ফিল্ডের "math" সাবফিল্ডের মান 90 এর চেয়ে বড়:

  ```javascript
  db.students.find({ "grades.math": { $gt: 90 } })
  ```

আপনি এই উদাহরণগুলি ব্যবহার করে MongoDB ডেটাবেসে ডকুমেন্ট সিলেক্ট করার প্রক্রিয়া বুঝতে সাহায্য পেতে পারেন।
