<template>
    <div>

        <head>
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>
                C4P741NTH
            </title>
        </head>
        <header>
            <BNavbar toggleable="lg" variant="transparent">
                <BNavbarBrand href="/">Home</BNavbarBrand>
                <BNavbarToggle target="nav-collapse" />
                <BCollapse id="nav-collapse" is-nav>
                    <!-- Right aligned nav items -->
                    <BNavbarNav class="ms-auto mb-2 mb-lg-0">
                        <BNavItemDropdown text="About" right>
                            <BDropdownItem href="https://github.com/c4p741nth">GitHub</BDropdownItem>
                            <BDropdownItem href="https://osu.ppy.sh/users/7892722">osu!</BDropdownItem>
                            <BDropdownItem href="https://discordapp.com/users/311453367371038721">Discord</BDropdownItem>
                        </BNavItemDropdown>
                    </BNavbarNav>
                </BCollapse>
            </BNavbar>
        </header>
        <div class="container">
            <slot />
        </div>
        <footer></footer>
    </div>
</template>

<script setup>

</script>

<style scoped></style>