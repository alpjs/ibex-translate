# ibex-translate

```js
import Ibex from 'ibex';
import config from 'ibex-config';
import language from 'ibex-language';
import translate from 'ibex-translate';

(async function main() {
    const app = new Ibex();
    await config('/js/config')(app);
    await language(app);
    await translate('locales')(app);
    await app.run();
})();
```
