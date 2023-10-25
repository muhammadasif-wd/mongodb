1: $ne, $neq, $gt, $lt, $gte, $lte অপারেটর এক্সপ্লোর করুন
   - $ne (সমান নয়) অপারেটর ব্যবহার করে নিষ্ক্রিয় না এমন ডকুমেন্ট সিলেক্ট করা যায়।
   - $gt (বড় হওয়া) অপারেটর দিয়ে একটি মৌলিক মানের চেয়ে বড় ডকুমেন্ট সিলেক্ট করা যায়।
   - $lt (ছোট হওয়া) অপারেটর দিয়ে একটি মৌলিক মানের চেয়ে ছোট ডকুমেন্ট সিলেক্ট করা যায়।
   - $gte (বড় অথবা সমান হওয়া) অপারেটর দিয়ে একটি মৌলিক মানের চেয়ে বড় অথবা সমান ডকুমেন্ট সিলেক্ট করা যায়।
   - $lte (ছোট অথবা সমান হওয়া) অপারেটর দিয়ে একটি মৌলিক মানের চেয়ে ছোট অথবা সমান ডকুমেন্ট সিলেক্ট করা যায়।

2: $in, $nin, নেস্টেড কন্ডিশন এক্সপ্লোর করুন
   - $in (সম্মিলিত) অপারেটর দিয়ে একটি মান একটি ফিল্ডের মধ্যে যেগুলি সম্মিলিত আছে তা সিলেক্ট করা যায়।
   - $nin (সম্মিলিত নয়) অপারেটর দিয়ে একটি মান একটি ফিল্ডের মধ্যে যেগুলি সম্মিলিত নয় তা সিলেক্ট করা যায়।
   - নেস্টেড কন্ডিশন ব্যবহার করে একটি ডকুমেন্টের সাথে আরও একটি কন্ডিশন সুনির্দিষ্ট ফিল্ডের জন্য এক্সপ্লোর করা যায়।

3: $and, $or, ইমপ্লিসিট vs. এক্সপ্লিসিট "এন্ড" অপারেটর এক্সপ্লোর করুন
   - $and (এন্ড) অপারেটর দিয়ে একের এক কন্ডিশন এবং আরেকের আরেক কন্ডিশন সম্মিলিত হয়ে ডকুমেন্ট সিলেক্ট করা যায়।
   - $or (অর) অপারেটর দিয়ে যেকোনো একটি কন্ডিশন সত্য হলে ডকুমেন্ট সিলেক্ট করা যায়।
   - ইমপ্লিসিট "এন্ড" অপারেটর এবং এক্সপ্লিসিট "এন্ড" অপারেটরের মধ্যে পার্থক্য নিরূপণ করা হয় এবং কোনটি কোন স্থিতিতে ব্যবহার করা উচিত তা নির্ধারণ করা হয়।

4: $exists, $type, $size অপারেটর এক্সপ্লোর করুন
   - $exists (উপস্থিত) অপারেটর দিয়ে একটি ফিল্ডের উপস্থিতি সনাক্ত করে ডকুমেন্ট সিলেক্ট করা যায়।
   - $type (ধরন) অপারেটর দিয়ে একটি ফিল্ডের ডেটা টাইপ নির্ধারণ করে ডকুমেন্ট সিলেক্ট করা যায়।
   - $size (সাইজ) অপারেটর দিয়ে একটি অ্যারের সাইজ নির্ধারণ করে ডকুমেন্ট সিলেক্ট করা যায়।

5: $all, $elemMatch অপারেটর পর্ব ১ এক্সপ্লোর করুন
   - $all (সব) অপারেটর দিয়ে একটি অ্যারেতে সব উপাদানের সাথে মিলে ডকুমেন্ট সিলেক্ট করা যায়।
   - $elemMatch (এলিমেন্ট ম্য্যাচ) অপারেটর দিয়ে একটি অ্যারে এবং একটি কন্ডিশনের সাথে মিলে ডকুমেন্ট সিলেক্ট করা যায়, এটি প্রথম মিলে যায়।

6: $set, $addToSet, $push অপারেটর এক্সপ্লোর করুন
   - $set (সেট) অপারেটর দিয়ে একটি ফিল্ডের মান সেট করা যায়।
   - $addToSet (যোগ করতে যোগ করুন) অপারেটর দিয়ে একটি অ্যারেতে মৌলিক মান যোগ করা হয়, তবে সমস্ত ডুপ্লিকেট মৌলিক মান স্থায়ী রূপে একবার শোধ করা হয়।
   - $push (পুশ) অপারেটর দিয়ে একটি অ্যারেতে মৌলিক মান যোগ করা যায়, সমস্ত মৌলিক মান স্থায়ী রূপে সংরক্ষণ করা হয়।

7: $unset, $pop, $pull, $pullAll অপারেটর এক্সপ্লোর করুন
   - $unset (অনসেট) অপারেটর দিয়ে একটি ফিল্ড অনসেট করা যায়, যা মৌলিক মান বা স্থায়ী মৌলিক মান হতে পারে।
   - $pop (পপ) অপারেটর দিয়ে একটি অ্যারে থেকে একটি মৌলিক মান বা স্থায়ী মৌলিক মান পপ করা যায়।
   - $pull (পুল) অপারেটর দিয়ে একটি অ্যারে থেকে মৌলিক মান বা স্থায়ী মৌলিক মান টি সরানো যায়।
   - $pullAll (পুল সব) অপারেটর দিয়ে একটি অ্যারে থেকে সমস্ত স্থায়ী মৌলিক মান সরানো যায়।

8: deleteOne, deleteMany, dropCollection, createCollection এক্সপ্লোর করুন
   - deleteOne (ডিলিটওয়ান) মেথড ব্যবহার করে একটি ডকুমেন্ট ডিলিট করা যায়।
   - deleteMany (ডিলিটম্যানি) মেথড ব্যবহার করে একাধিক ডকুমেন্ট ডিলিট করা যায়।
   - dropCollection (ড্রপকালেকশন) মেথড দিয়ে একটি কালেকশন ড্রপ করা যায়, অর্থাৎ সম্পূর্ণ কালেকশন মুছে ফেলা হয়।
   - createCollection (ক্রিয়েটকালেকশন) মেথড দিয়ে একটি কালেকশন তৈরি করা যায়।

9: $inc, $min, ডকুমেন্ট এক্সপ্লোর করতে কীভাবে
   - $inc (ইনক্রিমেন্ট) অপারেটর দিয়ে একটি ফিল্ডের মান ইনক্রিমেন্ট করা যায়।
   - $min (মিনিমাম) অপারেটর দিয়ে দুটি মৌলিক মানের মধ্যে ছোট মান নির্ধারণ করা যায়।
   - ডকুমেন্ট এক্সপ্লোর করতে বাংলায় আপনি MongoDB বা অন্য যেকোনো NoSQL ডাটাবেস ব্যবহার করতে পারেন এবং ডকুমেন্ট সিলেক্ট এবং ম্যানিপুলেট করতে পারেন।


<hr/>
- **$ne, $gt, $lt, $gte, $lte, $in, $nin, $and, $or অপারেটর**

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

**$and অপারেটর:**

- উদাহরণ 1: $and অপারেটর দিয়ে "age" এবং "gender" দুটি কন্ডিশন সম্মিলিত হলে ডকুমেন্ট সিলেক্ট করা:

```javascript
db.users.find({ $and: [{ age: 25 }, { gender: "female" }] })
```

- উদাহরণ 2: $and অপারেটর ব্যবহার করে "score" এবং "subject" দুটি কন্ডিশন সম্মিলিত হলে ডকুমেন্ট সিলেক্ট করা:

```javascript
db.scores.find({ $and: [{ score: { $gte: 90 } }, { subject: "Math" }] })
```

**$or অপারেটর:**

- উদাহরণ 1: $or অপারেটর ব্যবহার করে "age" বা "gender" দুটি কন্ডিশন যেকোনো একটি সত্য হলে ডকুমেন্ট সিলেক্ট করা:

```javascript
db.users.find({ $or: [{ age: 25 }, { gender: "female" }] })
```

- উদাহরণ 2: $or অপারেটর ব্যবহার করে "status" বা "priority" দুটি কন্ডিশন যেকোনো একটি সত্য হলে ডকুমেন্ট সিলেক্ট করা:

```javascript
db.tasks.find({ $or: [{ status: "completed" }, { priority: "high" }] })
```

**ইমপ্লিসিট এন্ড অপারেটর:**

ইমপ্লিসিট এন্ড অপারেটরের ব্যবহার উদাহরণ দেওয়া হল:

- উদাহরণ: ইমপ্লিসিট এন্ড অপারেটর ব্যবহার করে "age" এবং "gender" দুটি কন্ডিশন সম্মিলিত হলে ডকুমেন্ট সিলেক্ট করা:

```javascript
db.users.find({ age: 25, gender: "female" })
```

**এক্সপ্লিসিট "এন্ড" অপারেটর:**

এক্সপ্লিসিট "এন্ড" অপারেটরের ব্যবহার উদাহরণ দেওয়া হল:

- উদাহরণ: এক্সপ্লিসিট "এন্ড" অপারেটর ব্যবহার করে "age" এবং "gender" দুটি কন্ডিশন সম্মিলিত হলে ডকুমেন্ট সিলেক্ট করা:

```javascript
db.users.find({ $and: [{ age: 25 }, { gender: "female" }] })
```
* $exists, $type, $size, $all, $elemMatch, $set, $addToSet, $push, $unset, $pop, $pull, $pullAll, deleteOne, deleteMany, dropCollection, createCollection, $inc, $min অপারেটর এক্সপ্লোর করুন*

1. **$exists অপারেটর**:
   - ডকুমেন্টে একটি ফিল্ডের উপস্থিতি পরীক্ষা করতে নিম্নলিখিত মতে MongoDB কিউরি ব্যবহার করা যেতে পারে:

   ```json
   db.collection.find({ field_name: { $exists: true } })
   ```

2. **$type অপারেটর**:
   - ডকুমেন্টে একটি ফিল্ডের ডেটা টাইপ পরীক্ষা করতে নিম্নলিখিত মতে MongoDB কিউরি ব্যবহার করা যেতে পারে:

   ```json
   db.collection.find({ field_name: { $type: data_type } })
   ```

   উদাহরণঃ স্ট্রিং টাইপ এর ফিল্ড খুঁজে বের করার ক্যুরি:

   ```json
   db.collection.find({ field_name: { $type: "string" } })
   ```

3. **$size অপারেটর**:
   - ডকুমেন্টে একটি অ্যারের সাইজ পরীক্ষা করতে নিম্নলিখিত মতে MongoDB কিউরি ব্যবহার করা যেতে পারে:

   ```json
   db.collection.find({ array_field: { $size: size_value } })
   ```

   উদাহরণঃ একটি অ্যারে যার সাইজ 3:

   ```json
   db.collection.find({ array_field: { $size: 3 } })
   ```

4. **$all অপারেটর**:
   - ডকুমেন্টে একটি অ্যারেতে সব উপাদানের সাথে মিলে ডকুমেন্ট সিলেক্ট করতে নিম্নলিখিত মতে MongoDB কিউরি ব্যবহার করা যেতে পারে:

   ```json
   db.collection.find({ array_field: { $all: [element1, element2, element3] } })
   ```

5. **$elemMatch অপারেটর**:
   - ডকুমেন্টে একটি অ্যারে এবং একটি কন্ডিশনের সাথে মিলে ডকুমেন্ট সিলেক্ট করতে নিম্নলিখিত মতে MongoDB কিউরি ব্যবহার করা যেতে পারে:

   ```json
   db.collection.find({ array_field: { $elemMatch: { field_name: condition } } })
   ```

6. **$set অপারেটর**:
   - $set অপারেটর দিয়ে একটি ফিল্ডের মান সেট করা যায়।

   ```json
   db.collection.update({ _id: 1 }, { $set: { field_name: "new_value" } })
   ```

7. **$addToSet অপারেটর**:
   - $addToSet অপারেটর দিয়ে একটি অ্যারেতে মৌলিক মান যোগ করা হয়, তবে সমস্ত ডুপ্লিকেট মৌলিক মান স্থায়ী রূপে একবার শোধ করা হয়।

   ```json
   db.collection.update({ _id: 1 }, { $addToSet: { array_field: "new_value" } })
   ```

8. **$push অপারেটর**:
   - $push অপারেটর দিয়ে একটি অ্যারেতে মৌলিক মান যোগ করা যায়, সমস্ত মৌলিক মান স্থায়ী রূপে সংরক্ষণ করা হয়।

   ```json
   db.collection.update({ _id: 1 }, { $push: { array_field: "new_value" } })
   ```

9. **$unset অপারেটর**:
   - $unset অপারেটর দিয়ে একটি ফিল্ড অনসেট করা যায়, যা মৌলিক মান বা স্থায়ী মৌলিক ম

ান হতে পারে।

   ```json
   db.collection.update({ _id: 1 }, { $unset: { field_name: 1 } })
   ```

10. **$pop অপারেটর**:
   - $pop অপারেটর দিয়ে একটি অ্যারে থেকে একটি মৌলিক মান বা স্থায়ী মৌলিক মান পপ করা যায়।

   ```json
   db.collection.update({ _id: 1 }, { $pop: { array_field: 1 } })
   ```

11. **$pull অপারেটর**:
   - $pull অপারেটর দিয়ে একটি অ্যারে থেকে মৌলিক মান বা স্থায়ী মৌলিক মান টি সরানো যায়।

   ```json
   db.collection.update({ _id: 1 }, { $pull: { array_field: "value_to_remove" } })
   ```

12. **$pullAll অপারেটর**:
   - $pullAll অপারেটর দিয়ে একটি অ্যারে থেকে সমস্ত স্থায়ী মৌলিক মান সরানো যায়।

   ```json
   db.collection.update({ _id: 1 }, { $pullAll: { array_field: ["value1", "value2"] } })
   ```

13. **deleteOne মেথড**:
   - deleteOne মেথড ব্যবহার করে একটি ডকুমেন্ট ডিলিট করা যায়।

   ```json
   db.collection.deleteOne({ _id: 1 })
   ```

14. **deleteMany মেথড**:
   - deleteMany মেথড ব্যবহার করে একাধিক ডকুমেন্ট ডিলিট করা যায়।

   ```json
   db.collection.deleteMany({ field_name: "value_to_delete" })
   ```

15. **dropCollection মেথড**:
    - dropCollection মেথড দিয়ে একটি কালেকশন ড্রপ করা যায়, অর্থাৎ সম্পূর্ণ কালেকশন মুছে ফেলা হয়।

    ```json
    db.collection.drop()
    ```

16. **createCollection মেথড**:
    - createCollection মেথড দিয়ে একটি কালেকশন তৈরি করা যায়।

    ```json
    db.createCollection("new_collection")
    ```

17. **$inc অপারেটর**:
    - $inc অপারেটর দিয়ে একটি ফিল্ডের মান ইনক্রিমেন্ট করা যায়।

    ```json
    db.collection.update({ _id: 1 }, { $inc: { field_name: 1 } })
    ```

18. **$min অপারেটর**:
    - $min অপারেটর দিয়ে দুটি মৌলিক মানের মধ্যে ছোট মান নির্ধারণ করা যায়।

    ```json
    db.collection.update({ _id: 1 }, { $min: { field_name: min_value } })
    ```
