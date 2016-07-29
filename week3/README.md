# week3 回家作業

# Sails
## 目標

1. 使用 [sails-sample](https://github.com/trunk-studio/sails-sample)， C9 環境下也有該專案
2. 把上次 tdd 的作業定義的 friend model 移置 sails-sample 下
3. 定義 Routes 讓 Postman 可以使用 `Restful api` 對 friend CRUD
4. 撰寫 mocha 測試 Restful api

例如：
```javascript
describe('test user api', () => {
  let use;
  before(async (done) => {
    try {
      user = await User.create({
        email: 'test@gmail.com',
        password: 'test'
      });
      done();
    } catch (e) {
      done(e);
    }
  });

  it('get all user', async(done) => {
    try {
      const res = await request(sails.hooks.http.app)
      .get(`/user`);
      res.status.should.be.eq(200);
      done()
    } catch (e) {
      done(e)
    }
  });

});
```

## 繳交方式
直接 fork  [sails-sample](https://github.com/trunk-studio/sails-sample) 寫完作業後發 Pull requests 回來 sails-sample 專案中，我們 review 完成後會把該 Pull requests close
