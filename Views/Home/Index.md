@model SampleModel

<!DOCTYPE html>
<html>
<head>
    <title>Login</title>
    <link rel="stylesheet" href="~/css/site.css" />
</head>
<body>
    <div class="container">
        <h1>Bienvenido</h1>
        <p>SEL5M</p>
        
        @if (Model != null)
        {
            <div>
                <h2>Sample Model Data</h2>
                <p>@Model.PropertyName</p> <!-- Replace PropertyName with actual property from SampleModel -->
            </div>
        }
    </div>
</body>
</html>