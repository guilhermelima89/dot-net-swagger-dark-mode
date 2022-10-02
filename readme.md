if (app.Environment.IsDevelopment())
{
app.UseSwagger();
app.UseSwaggerUI(c => c.InjectStylesheet("/swagger-ui/SwaggerDark.css"));
}

app.UseStaticFiles();
