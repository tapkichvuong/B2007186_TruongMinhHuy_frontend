<template>
    <nav class="nav-bar navbar-expand navbar-dark bg-dark">
        <a href="/" class="navbar-brand">Ứng dụng Quản lý danh bạ</a>
        <div class="mr-auto navbar-nav">
            <li class="nav-item">
                <router-link :to="{name: 'contactbook'}" class="nav-link">
                    Danh bạ
                    <font-awesome-icon icon="fa-solid fa-address-book" />
                </router-link>
            </li>
        </div>
    </nav>
</template>