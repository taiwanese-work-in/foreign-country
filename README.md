# Taiwanese Work In 共同知識庫 & 站務 & Middleman 網站

## 共同知識庫

請前往 [本專案 wiki](https://github.com/taiwanese-work-in/foreign-country/wiki)

## 站務

* 關於本計畫未來發展的討論
* 不限於特定國家的資料提供、建議、需討論議題等，請 [開 issue](https://github.com/taiwanese-work-in/foreign-country/issues/new)。
* 與修改網站程式碼相關的 issue，請採用 [此樣版](/.github/ISSUE_TEMPLATE.md)

## Middleman 網站

* Source code for the <http://taiwanese-work.in/> website.

### Setup

```
ruby -v # double check your ruby version.
bundle install
middleman server
```

### Deploy

* Make sure that your git remote name is `origin`

```
middleman build
middleman deploy
```

### Git branching & pull request policy

* 使用 [GitHub flow](https://guides.github.com/introduction/flow/)-改 (merge 後才 deploy production)。
* PR description 請使用 [此樣版](/.github/PULL_REQUEST_TEMPLATE.md)。
* PR description 可以用中文寫，但 git commit message 請只使用英文。
* 可以的話，建議一個 PR 只含一個 commit，其 commit message == PR description (這個情況下請用英文)。
