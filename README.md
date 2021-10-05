# fsdohwifiwcfwe-

// 先程生成したURL
const url = 'https://app.rakuten.co.jp/services/api/Recipe/CategoryRanking/20170426?applicationId=1048445474139185419';

$.getJSON(url, (data) => {
    console.log(data.result);
});
