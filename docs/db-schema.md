
# Database Schema

[back to home](../readme.md)
y
## Categories

Example category document in CouchDB:

```
{
  _id: "category_basic-needs-assistance",
  type: "category",
  name: "Basic Needs",
  desc: "Basic Needs Assistance includes organizations that provide one or more of the following services: shelter facilities for the homeless and for those escaping situations of domestic violence, food/supplemental nutrition resources, and single-transaction emergency financial assistance in cases of involuntary hardship.",
  shortDesc: "shelter, food, financial, domestic violence"
}

```

## Resources

Example resource document in CouchDB:

```
{
  _id: "resource_american-red-cross-of-lowcountry-sc",
  type: "resource",
  categoryId: "category_basic-needs-assistance",
  name:  "Red Cross",
  formalName: "American Red Cross of Lowcountry – SC"
  avatarImgURL: "https://blah.whatevs.com/image.png"
  shortDesc: "communication, transition, disaster services",
  purpose: "The American Red Cross provides emergency communication services to military (active duty, National Guard, Reserves, retired, and veterans) and their families, helping them locate and send messages to their loved ones across the globe. When service members return home, they have access to several programs and American Red Cross volunteers who are ready and willing to ease the transition from deployment or discharge
into the civilian sector. Programs provided include, but are not limited to, emergency financial assistance referrals, disaster preparedness and response, reconnection and family mental health education, resiliency training to cope with the challenges of life in the military, and supportive transitional services for wounded soldiers and their family members. We also offer volunteer opportunities in all lines of service. To initiate an Emergency Communication Message, call 1-877-272-7337 when you need to contact a service member in the event of a family emergency. This service is available 365 days a year, 24 hours a day.",
  website: "http://www.redcross.org/what-we-do/support-military-families",
  contacts: [
  { name:  "Jeanne Carmichael"
    , title: "Manager, Service to the Armed Forces"
    , phone: "843-764-2323"
    , email: "Jeanne.Carmichael@redcross.org"
    , isPrimary: true},
  { name:  "Emergency Communication Message"
    , title: ""
    , phone: "1-877-272-7337"
    , email: ""
    , isPrimary: false}
  ],
  addresses: [
    {isPrimary: true, location: "Name: American Red Cross of Lowcountry – SC", street1: "2424 City Hall Lane", street2: "Suite A", city: "North Charleston", state: "SC", zip: "29406"}
  ]
}
```


[back to home](../readme.md)
