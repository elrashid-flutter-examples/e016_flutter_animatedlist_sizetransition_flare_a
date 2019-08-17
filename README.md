# e016_flutter_animatedlist_sizetransition_flare_a

## Based On e015

- [elrashid-flutter-examples/e015_flutter_animatedlist_sizetransition_e004base](https://github.com/elrashid-flutter-examples/e015_flutter_animatedlist_sizetransition_e004base)

  - Based On e014

    - [elrashid-flutter-examples/e014_flutter_animatedlist_noanimation_e004base](https://github.com/elrashid-flutter-examples/e014_flutter_animatedlist_noanimation_e004base)

      - Based On e004 :

        - [elrashid-flutter-examples/e004_flutter_listview_crud_app_using_nonsecure_rest_api](https://github.com/elrashid-flutter-examples/e004_flutter_listview_crud_app_using_nonsecure_rest_api)

## Screen Record

![app screen record](docs/screen_record.gif)

## What

-AnimatedList useing Flare with BoxFit.contain for removeItem Animation for tasks in flutter Task app (e004)

- must run with :

  - [elrashid-flutter-examples/e002-aspcore-rest-api-server-for-flutter](https://github.com/elrashid-flutter-examples/e002-aspcore-rest-api-server-for-flutter)

## Full code

    _myListKey.currentState.removeItem(
        ti,
        (BuildContext context, Animation<double> animation) => SizedBox(
            height: 80,
            child: FlareActor("assets/Penguin.flr",
                alignment: Alignment.center,
                fit: BoxFit.contain,
                animation: "walk"),
            ),
        duration: Duration(seconds: 3));

## Ref

[e015](https://github.com/elrashid-flutter-examples/e014_flutter_animatedlist_noanimation_e004base)

[AnimatedList (Flutter Widget of the Week) - YouTube](https://www.youtube.com/watch?v=ZtfItHwFlZ8)

[2D - Explore](https://www.2dimensions.com/explore/popular/trending/all)

[Flare-Flutter/main.dart at master · 2d-inc/Flare-Flutter](https://github.com/2d-inc/Flare-Flutter/blob/master/example/penguin_dance/lib/main.dart)

[How to Flare a Flutter app? Part 1 - Create Animation](https://proandroiddev.com/how-to-flare-a-flutter-app-part-1-create-animation-3829fb2ed72a)

[2d-inc/Flare-Flutter: Load and get full control of your Flare files in a Flutter project using this library.](https://github.com/2d-inc/Flare-Flutter)

[Flutter Flare Basics - Let's Build Giphy's Nav Menu - YouTube](https://www.youtube.com/watch?v=hwBUU9CP4qI)

[flare_flutter | Flutter Package](https://pub.dev/packages/flare_flutter#-readme-tab-)

[Flare-Flutter/main.dart at master · 2d-inc/Flare-Flutter](https://github.com/2d-inc/Flare-Flutter/blob/master/example/penguin_dance/lib/main.dart)

[Adding assets and images - Flutter](https://flutter.dev/docs/development/ui/assets-and-images)