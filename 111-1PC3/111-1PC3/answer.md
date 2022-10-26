# 第3次練習-練習-PC3
>
>學號：109111116
><br />
>姓名：朱羿安
><br />
>作業撰寫時間：60 (mins，包含程式撰寫時間)
><br />
>最後撰寫文件日期：2022/10/26
>

本份文件包含以下主題：(至少需下面兩項，若是有多者可以自行新增)
- [x]說明內容
- [x]個人認為完成作業須具備觀念

## 說明程式與內容


下段程式碼則為使用後結果：

```csharp
namespace _111_1PC3
{
    public partial class test : System.Web.UI.Page
    {
        protected void Page_Load(object sender, EventArgs e)
        {
            int i_Clothes = 300;
            int i_Hat = 350;
            int i_Pants = 400;
            int plus = i_Clothes*7 + i_Hat*8 + i_Pants*9;
            Response.Write("plus");


下段程式碼則為使用後結果：

<%@ Page Language="C#" AutoEventWireup="true" CodeBehind="test.aspx.cs" Inherits="_111_1PC3.test" %>

<!DOCTYPE html>

<html xmlns="http://www.w3.org/1999/xhtml">
<head runat="server">
<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
    <title></title>
</head>
<body>
    <form id="form1" runat="server">
        <div>
        </div>
    </form>
</body>
</html>

```


## 個人認為完成作業須具備觀念

需要有一定的數學能力，如何去定義變數並且計算。
