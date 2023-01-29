<template>
    <header>
        <div class="container">
            <div class="header__wrapper">
                <Logo />
                <Navbar />
                <SearchForm />
                <UsersActivities />
            </div>
        </div>
    </header>
</template>

<style scoped>
header{
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    background-color: #fff;
    box-shadow: 0 2px 4px rgb(159 98 18 / 12%);
    height: 60px;
    width: 100%;
}

.header__wrapper {
    display: flex;
    width: 100%;
    align-items: center;
    flex-wrap: wrap;
    justify-content: space-between;
}
</style>