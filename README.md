# 기술 블로그 백엔드

> 기술블로그의 백엔드 입니다.
> `nest JS`기반으로 작성 되었습니다.

## 백엔드 링크

- [http://localhost:3000](http://localhost:3000)

## 목차

- [기술 블로그 백엔드](#기술-블로그-백엔드)
  - [백엔드 링크](#백엔드-링크)
  - [목차](#목차)
  - [내용](#내용)
    - [포스트](#포스트)
    - [유저](#유저)
    - [분류](#분류)
  - [Deploy](#deploy)
    - [Heroku](#heroku)

## 내용

### 포스트

```
{
  id: number
  title: string
  content: string
  createdAt: Date
  userId: number
  user: User
  divisionId: number
  division: Division
}
```

### 유저

```
{
  id: number
  nickname: string
  email: string
  postId: number[]
  post: Post[]
  isVerified: boolean
}
```

### 분류

```

{
  id: number
  name: string
  postId: number[]
  post: Post[]
}

```

## Deploy

### Heroku

> 헤로쿠에 관련된 내용입니다.
