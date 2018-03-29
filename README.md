# SchoolMeal
전국 학교급식정보를 가져오는 라이브러리
https://blog.naver.com/aquayo/220864091222

Example)
급식메뉴를 나이스 홈페이지에서 불러와서 List형태로 제공

List<MealMenu> MealList = new List<MealMenu>();
  
Meal meal = new Meal(Regions.Daegu, SchoolType.High, "학교코드");

MealList = meal.GetMealMenu();


  
  
