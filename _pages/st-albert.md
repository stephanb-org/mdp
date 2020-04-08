---
title: "St Albert the Great College"
permalink: "/st-albert"
image: "/assets/images/15.jpg"
---

<div class="jumbotron jumbotron-fluid jumbotron-home pt-0 pb-0 mt-3 mb-3 rem bg-lightblue position-relative w-100">
            <div class="pl-0 pr-0 tofront">
                <div class="row justify-content-between">
                    <div class="col-md-12 col-sm-12 pt-6 pb-6 pr-lg-4 align-self-center rounded" style="height:500px;background-size:cover;background-image:url({{ page.image }});">
                    </div>
                </div>
            </div>
        </div>

The college caters for boys and girls from the age of 5 to 16, hailing from different parts of the island and beyond.  The college is inclusive of all children and youths regardless of race, religious beliefs, abilities, and socio-economic background etc.  The college strives to provide a creative education that caters for individuals within the context of a caring community.

We are also proud to form part of the larger Valletta community, with its buzzing cultural, historic, artistic and social goings on. The college forms part of the Maltese Dominican Province. 


   <h4 class="font-weight-bold"><span>Contact Details</span></h4>
<div class="row gap-y listrecent listrecent listauthor">
        {% for stalbert in site.stalberts %}
        <div class="col-lg-6 mb-4">
            <div class="p-4 border rounded">
                <div class="row">

  <div class="col-md-12">

   <h4 class="text-dark mb-0"> {{ stalbert[1].name }} </h4>
                            <small class="d-inline-block mt-1 mb-3 font-weight-normal">{{ stalbert[1].qual }}</small>
                            <div class="excerpt">{{ stalbert[1].role }}</div>
                        <div class="excerpt">
<a href="mailto:{{ stalbert[1].email }}">{{ stalbert[1].email }}</a>
</div>
                    </div>
                </div>
            </div>
        </div>
        {% endfor %}
    </div>


