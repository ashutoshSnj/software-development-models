
# 3️⃣ Incremental Model

![Incremental Model](https://raw.githubusercontent.com/ashutoshSnj/software-development-models/main/Incremental-Model.png)

## 📌 Overview
The Incremental Model delivers software in parts (increments). Each increment adds features to the previous release until the full system is complete. It combines Waterfall structure with Agile flexibility.

## 🧱 Suitable For
- Long-term projects
- Projects where early delivery of core functions is needed
- Systems with evolving requirements

## 🔁 Phases in Detail

### 1. Overall Requirement Planning
- Requirements are divided into core + optional modules.
- First delivery includes must-have features.

### 2. Incremental Planning
- Timeline, team allocation, and objectives are set for each increment.
- Increments may be planned monthly, quarterly, etc.

### 3. Design & Develop Each Increment
- Each increment follows its mini-waterfall: design → code → test.
- Can be developed in parallel (by teams) or sequentially.

### 4. Integration Testing
- Each increment is tested separately.
- After full integration, regression testing is done.

### 5. Deployment
- Early increments can be deployed (MVP release).
- Later increments are released via updates.

### 6. Maintenance
- Fix bugs from any increment.
- Next increment development can run in parallel.

## ✅ Advantages
- Faster delivery of useful software
- Risk is reduced due to early feedback
- Good for managing large teams

## ❌ Disadvantages
- Complex integration logic
- Poor planning may break continuity
- Dependency between increments can create delays

## 💡 Real-World Analogy
Like building a food delivery app: first build login and home screen → then order tracking → then payments → then rating system.

---
