# Travel Project

---

### Make migrations
@Travel.Data folder 

```c#
# create initial migration file
dotnet ef migrations add InitialCreate --startup-project ../../presentation/Travel.WebApi/

# migrate
dotnet ef database update --startup-project ../../presentation/Travel.WebApi/
```