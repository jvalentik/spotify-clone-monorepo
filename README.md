# Angular Spotify

A simple Spotify client built with Angular 12, Nx workspace, ngrx, TailwindCSS and ng-zorro.

## Working application

**Spotify premium** is required for the Web Playback SDK to play music. If you are using a free account, you can still browse the app, but it couldn't play the music. Sorry about that 🤣

![Angular Spotify Demo][demo]

![Angular Spotify Visualizer][visualizer]

![Angular Spotify Browse][angular-spotify-browse]

![Angular Spotify Blurry Background][album-art]

![Angular Spotify PWA][pwa]

![Angular Spotify Web Player][web-player]

## Tech stack

- [Angular 12][angular]
- [Nx Workspace][nx]
- [ngneat][] packages includes: `ngneat/svg-icon` and `ngneat/until-destroy`
- [ngrx][ngrx] and [ngrx/component-store][component-store]
- [ng-zorro][ng-zorro] UI component: `tooltip`, `modal`, `slider`, `switch` and more.
- [TailwindCSS][tailwind] - See this video [Everything you need to know about TailwindCSS and Angular applications](https://youtu.be/zSXdJqEPy9w) by [@nartc][nartc] for integration TailwindCSS with Angular
- [Netlify][netlify] for deployment

[angular]: https://angular.io/
[ngrx]: https://ngrx.io/
[component-store]: https://ngrx.io/guide/component-store
[tailwind]: https://tailwindcss.com/
[ng-zorro]: https://ng.ant.design/docs/introduce/en
[netlify]: http://netlify.com/
[ngneat]: https://github.com/ngneat

[nx]: https://nx.dev/
[nartc]: https://github.com/nartc
[demo]: /libs/web/shared/assets/src/assets/readme/angular-spotify-demo-short.gif
[visualizer]: /libs/web/shared/assets/src/assets/readme/angular-spotify-visualization.gif
[angular-spotify-browse]: /libs/web/shared/assets/src/assets/readme/angular-spotify-browse.gif
[album-art]: /libs/web/shared/assets/src/assets/readme/angular-spotify-album-art.gif
[pwa]: /libs/web/shared/assets/src/assets/readme/angular-spotify-pwa.gif
[web-player]: /libs/web/shared/assets/src/assets/readme/angular-spotify-web-player.png
