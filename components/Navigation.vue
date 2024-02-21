<template>
  <nav class="grid uppercase pl-4 pr-2 py-2 self-end w-full border-t border-emerald-300">
    <div class="space-y-2">
      <div>
        <HeadingSans>
          Projects
        </HeadingSans>
        <ul role="list" class="space-y-px">
          <li class="flex">
            <NavigationLink
              color="hover:text-white hover:bg-gray-700"
              class="flex-1"
              id="acommentonthedevilslove"
              to="/acommentonthedevilslove"
            >
              A.C.O.T.D.L
            </NavigationLink>
          </li>
          <li class="flex">
            <NavigationLink
              color="hover:text-white hover:bg-gray-700"
              class="flex-1"
              id="evenbettermotherfuckingwebsite"
              to="/evenbettermotherfuckingwebsite"
            >
              E.B.M.F.W
            </NavigationLink>
          </li>
          <li class="flex">
            <NavigationLink
              color="hover:text-white hover:bg-gray-700"
              class="flex-1"
              id="archive-two"
              to="/archive-two"
            >
              Archive Two
            </NavigationLink>
          </li>
          <li class="flex">
            <NavigationLink
              color="hover:text-white hover:bg-gray-700"
              class="flex-1"
              id="inkstarter"
              to="/inkstarter"
            >
              InkStarter
            </NavigationLink>
          </li>
          <li class="flex">
            <NavigationLink
              color="hover:text-white hover:bg-gray-700"
              class="flex-1"
              id="milico"
              to="/milico"
            >
              Milico
            </NavigationLink>
          </li>
          <li class="flex">
            <NavigationLink
              color="hover:text-white hover:bg-gray-700"
              class="flex-1"
              to="/moqueca"
              id="moqueca"
            >
              Moqueca
            </NavigationLink>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>
