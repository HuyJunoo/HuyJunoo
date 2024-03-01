```javascript
class Junoo {}

class Attributes extends Junoo {
    get contact() {
        const discord = "discord.gg/tB3tBVbG";
        const telegram = "t.me/WusJunoo";
        const facebook = "fb.com/NinhQuangHuy.Dev";
        const email = "JunooError404@gmail.com";

        return [discord, telegram, facebook, email];
    }

    get life() {
        const language = ['Vietnamese', 'English'];
        const age = 22;

        return [language, age];
    }

    get coding() {
        const langs = {
            'expert': ['python', 'typescript', 'html', 'css'],
            'intermediate': ['go', 'js', 'React.js', 'Angular.js', 'Vue.js', 'Node.js', 'Express.js', 'Next.js', 'Nest.js', 'Svelte.js', 'Meteor.js', 'Ember.js', 'Backbone.js'],
            'learning': ['c', 'c++', 'c#', 'asm', 'java']
        };
        const specialities = ['web/app reverse engineering', 'fullstack'];
        const environnement = ['vscode'];

        return [langs, specialities, environnement];
    }
}
```
