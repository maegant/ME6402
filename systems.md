---
layout: page
title: Systems
description: Listing of Simulation Environments Used throughout the Course
---

<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">

<style>
    .card-img-top {
        height: 200px;
        object-fit: cover;
    }
</style>

<div class="container">
    <div class="row">
        <div class="col-md-4">
            <div class="card">
                <a href="{{ site.baseurl }}/code/pendulum-simulation">
                    <img class="card-img-top" src="gifs/pendulum.gif" alt="Pendulum">
                    <div class="card-body">
                        <h5 class="card-title">Pendulum</h5>
                    </div>
                </a>
            </div>
        </div>
        <div class="col-md-4">
            <div class="card">
                <a href="{{ site.baseurl }}/code/cartpole-simulation">
                    <img class="card-img-top" src="gifs/cartpole.gif" alt="Cart-Pole">
                    <div class="card-body">
                        <h5 class="card-title">Cart-Pole</h5>
                    </div>
                </a>
            </div>
        </div>
        <div class="col-md-4">
            <div class="card">
                <a href="">
                    <img class="card-img-top" src="gifs/planar_multirotor.gif" alt="Multirotor">
                    <div class="card-body">
                        <h5 class="card-title">Planar Multirotor</h5>
                    </div>
                </a>
            </div>
        </div>
    </div>
</div>