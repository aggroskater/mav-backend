Initial
=======

Since everybody has to have code on their github --and **recent** code at
that-- this is me writing some code. I've made a habit of compulsively
downloading most of the media I consume. I've been saved by this habit multiple
times, what with videos getting removed, hidden, deleted, etc. It'd be nice to
have a clean front-end that I can browse, my own "Media WayBack Machine" if you
will.

So... in the interest of having something to point at when recruiters and
hiring managers are unconvinced by my years of experience in the field, I now
introduce... `mav-backend`, the Media Archive Viewer backend, written in C#
on .NET core 6 as a Web API (that might support Angular Universal, and nojs
environments too a la Razor pages) that uses... I guess the default DI for
.NET core (though I have experience with SimpleInjector), ASP.NET Identity
for users, OData for client-side querying, EF Core for ORM, MSSQL for
persistence.

I don't have any intention of this becoming an actual open source project.
It'll likely just be my own personal archive viewer.

