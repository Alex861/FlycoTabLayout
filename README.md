# FlycoTabLayout-AndroidX
  - 修改自 https://github.com/H07000223/FlycoTabLayout
  - 迁移到 AndroidX
  - 使用 ViewPage2 进行替换 ViewPage
  - 增加与 ViewPage 无依赖的可滑动的 ScrollTabLayout
  - 增加可定制性很高的 DiyTabLayout，属性如下：
  ```
  public class TabItemBean {
    private String titleColor = "#d9000000";           //标题未选中颜色
    private String titleSelectedColor = "#66000000";   //标题选中颜色
    private String title = "";                         //标题名字
    private String indicatorColor = "#FF4FCAA4";       //滑块颜色
    }
  ```
  dependencyResolutionManagement {
  		repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
  		repositories {
  			mavenCentral()
  			maven { url 'https://jitpack.io' }
  		}
  	}

  dependencies {
  	        implementation 'com.github.Alex861:FlycoTabLayout:1.0.0'
  	}
  ![image](https://github.com/ldlywt/FlycoTabLayout_AndroidX/raw/master/Image/DiyTabLayout.gif)
