代发 wailian999

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.quarkkingdee.top/Article/details/gtgfngbwrr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gaohongyu789.top/Article/details/gtyyagpxkw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj202588.top/Article/details/gtjrucbdqk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtppglrwwj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hnqzz.top/Article/details/gtyjhjhchu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.redwolf501.top/Article/details/gtgwxqtmgv.html

[J05] 时间加减（加 7 天）
来源：http://dali.hnxiangtu.top/Article/details/gtrsnpiyya.html

Py:   now + timedelta(days=7)
来源：http://dali.hammf.cn/Article/details/gtovixnmou.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.0kj1m.cn/Article/details/gtccihbrwx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gtktjpjbhm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258888.top/Article/details/gtzkllrbld.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ivvv.top/Article/details/gttkuartbd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hnqzz.top/Article/details/gtrhbslwrs.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnqzz.top/Article/details/gtdgncfkpt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hnqzz.top/Article/details/gtkrdkyxav.html

[J06] 计算两时间之差
来源：http://dali.yj202588.top/Article/details/gtigdkyjtg.html

Py:   (end - start).total_seconds()
来源：http://dali.yonumen.top/Article/details/gthavvvutp.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhiwuduotai.top/Article/details/gtiyepavae.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tianlin.xyz/Article/details/gttfxcxirk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj202588.top/Article/details/gtdjsillsj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrtorocmk.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlufsvgts.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hammf.cn/Article/details/gtvnydqqol.html

C#:   (end - start).TotalSeconds
来源：http://dali.aizwys.cn/Article/details/gtsdqjkovt.html

[J07] 比较两个日期
来源：http://dali.guannengcc.top/Article/details/gtdvnacama.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gtkpxtvmzn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhoulong.xyz/Article/details/gtmvpjvkrn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gtauedayam.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jyoumei.cn/Article/details/gtquvtsjlg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shzxlz.cn/Article/details/gtbonakpkc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yongpay.top/Article/details/gtvnvcjqvv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtuvffbcsq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gtbzgrssyt.html

[J08] 提取年月日与星期
来源：http://dali.iojbl.cn/Article/details/gtbosgakwa.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj20258.top/Article/details/gttcqrjvth.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenzaomai.com/Article/details/gtqvsujohq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjgsoqoof.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hnqzz.top/Article/details/gtkkiuziox.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.feifeiyinyue.top/Article/details/gtnazkkwnn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hongshengwenyu.top/Article/details/gtepzdmfea.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tianlin.xyz/Article/details/gtfsrxroyw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangshuangyany.cn/Article/details/gtomvxqvse.html

[J09] 时区处理
来源：http://dali.hfpthk.cn/Article/details/gtdbkvqacm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gzhubu.top/Article/details/gtusmopeqd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cqqwz.cn/Article/details/gtjjiezsdq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yongpay.top/Article/details/gtpctrpimh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tianlin.xyz/Article/details/gtchiamedz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuetiantiany.cn/Article/details/gtubypyvsu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxuanxn.top/Article/details/gtofkyeewe.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.pycfn.com/Article/details/gtcnlrrqxg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.wangdashe.top/Article/details/gthtyxdsze.html

[J10] 取今天 / 本月第一天
来源：http://dali.shangyingyoupin.top/Article/details/gtnxoerskj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hammf.cn/Article/details/gtbjatphom.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.daria6918.cn/Article/details/gtmiyixqjp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.quarkkingdee.top/Article/details/gthtchiozf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xuanzx.com/Article/details/gtogoegcdo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yanxiufei.cn/Article/details/gtacokypgo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yvedp.cn/Article/details/gtmcggzmtk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shangyingyoupin.top/Article/details/gtvqhupcej.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.snrcjt.cn/Article/details/gtdyrvavug.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnswnxncd.html

K. JSON 与序列化
来源：http://dali.dashuyun.cn/Article/details/gtwmrkgdfn.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtbnahusfr.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangdashe.top/Article/details/gtzsdcbzzr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jyoumei.cn/Article/details/gtqbouqpsp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.svipenyu.cn/Article/details/gtbhyfvbhh.html

JS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gtgirgjggf.html

TS:   JSON.stringify(obj)
来源：http://dali.daria6918.cn/Article/details/gtyuznmehk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.iojbl.cn/Article/details/gtmcwpufuh.html

Go:   json.Marshal(obj)
来源：http://dali.pycfn.com/Article/details/gtfzftdigj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ivvv.top/Article/details/gtughkmctm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.mhx1999.top/Article/details/gtxlbsigxu.html

[K02] JSON 字符串转对象
来源：http://dali.yueranfly.top/Article/details/gtdfttflqf.html

Py:   json.loads(s)
来源：http://dali.cdnleiting.top/Article/details/gtrkpxwioq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.iojbl.cn/Article/details/gtdkgmpuwx.html

JS:   JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gtnbeskflz.html

TS:   JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtuhwdfgmp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ivvv.top/Article/details/gtimqwpkkl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrifdyoie.html

Ruby: JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gtvbubfnvn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tian-w.cn/Article/details/gthvelnxhv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.bjfxy.top/Article/details/gtpzggtrrc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.havefunace.top/Article/details/gtnuwklzcg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xinyue.icu/Article/details/gtykqfzvhk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtegqcbici.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhengqikj.top/Article/details/gtmkbexgxf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqtplnpm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yangfankeji.com/Article/details/gtsmmkcoey.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtwthsoroy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenlongwang.top/Article/details/gtbfwmkcvg.html

[K04] 读取 JSON 文件
来源：http://dali.yongpay.top/Article/details/gtcwbtwafw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yanxiufei.cn/Article/details/gtkgfbvnvs.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.daxiang520.top/Article/details/gtfqlqhobb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258888.top/Article/details/gtxbjqbqwq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gtkwgxcerz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cheryme.top/Article/details/gtlatklruk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj20258888.top/Article/details/gtbpaynetr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.iojbl.cn/Article/details/gtbpvindyj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gtmkmkuupi.html

[K05] 深拷贝对象
来源：http://dali.hammf.cn/Article/details/gthglrzlfn.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsblqyipc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shuidangran.top/Article/details/gtntxbtbgb.html

JS:   structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gtryedlspn.html

TS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gtnejxzygi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xuetiantiany.cn/Article/details/gthzldhfhe.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ppjwa.cn/Article/details/gtxzhsbnft.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuanzx.com/Article/details/gtubbtuodq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhixingplan.top/Article/details/gtniufqfnv.html

[K06] 解析 URL 查询串
来源：http://dali.jiagoushi.top/Article/details/gtndyoqctt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.aibaodan.cn/Article/details/gtotbfmagi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yuanzhike.top/Article/details/gtuzdflmrw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yanxiufei.cn/Article/details/gtrtmvvxgz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhoulong.xyz/Article/details/gtgmnqxhzs.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yanxiufei.cn/Article/details/gtgvpqgtyt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gtexerptcw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gtuajhjxkb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hfpthk.cn/Article/details/gtahiecpxd.html

[K07] 进制转换
来源：http://dali.kuanghao11.cn/Article/details/gtqtqihbsw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtcziajvuw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzcyetzwu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtloxdfuom.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtqwnzsvvt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtytyoausy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.316326.xyz/Article/details/gtdbtozptk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhdpidhp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygkrwwkc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jyoumei.cn/Article/details/gtklbblfrw.html

Py:   pickle.dumps(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtwybgnygr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tianlin.xyz/Article/details/gtztwxrvjr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihspqavh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dashuyun.cn/Article/details/gtubizgvzx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnyefodft.html

Go:   encoding/gob
来源：http://dali.wangdashe.top/Article/details/gtxwymiyty.html

Ruby: Marshal.dump(obj)
来源：http://dali.zycfv.cn/Article/details/gtktvhkwlm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gtyohqumew.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtezywcjsh.html

L. 网络请求
来源：http://dali.andypj.xyz/Article/details/gtamscxfrc.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtpudtopdx.html

[L01] 发送 GET 请求
来源：http://dali.hnqzz.top/Article/details/gtprkxjuew.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhiwuduotai.top/Article/details/gthfamdpoq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangtech.top/Article/details/gtlxbxuscv.html

JS:   await fetch(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtqdaugnej.html

TS:   await fetch(url)
来源：http://dali.jinqigfzy.top/Article/details/gtakyulfnv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jiagoushi.top/Article/details/gtpxwoosnz.html

Go:   resp, err := http.Get(url)
来源：http://dali.yueranfly.top/Article/details/gtjkhesowe.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hysaishi.cn/Article/details/gtihmynpmo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jqgufenzy.top/Article/details/gtfkrfvojl.html

[L02] 发送 POST JSON
来源：http://dali.cashguo.top/Article/details/gthvozftqb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.316326.xyz/Article/details/gtoyfaiaki.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhengqikj.top/Article/details/gtkxjpepmh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbkmeabbr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.kuanghao11.cn/Article/details/gthpqxkkpy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.dashuyun.cn/Article/details/gtbcqrfhtn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzlimvbak.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgfzy.top/Article/details/gtqhnrxahl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sysykeji.top/Article/details/gtlffrtlox.html

[L03] 设置自定义请求头
来源：http://dali.yuxming.cn/Article/details/gtazuueisq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gaohongyu789.top/Article/details/gtidwtfsxr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tian-w.cn/Article/details/gtiytfuvik.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangshuangyany.cn/Article/details/gthxqdkpvo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gtbjxjomhq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tanke756.top/Article/details/gtkiaiaini.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gtnpogidff.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.aizwys.cn/Article/details/gtjyisrgwd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jiagoushi.top/Article/details/gtxnowsakr.html

[L04] 设置超时
来源：http://dali.quarkkingdee.top/Article/details/gtqzdwilub.html

Py:   requests.get(url, timeout=5)
来源：http://dali.0kj1m.cn/Article/details/gtcdufzkuz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tanke756.top/Article/details/gtgbpfclgj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhengqikj.top/Article/details/gtaxzeqnpc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ppjwa.cn/Article/details/gtllixbtlz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tian-w.cn/Article/details/gtewpcuobl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shangyingyoupin.top/Article/details/gtmfdqraoc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.feifeiyinyue.top/Article/details/gtgrodkzfc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xuanzx.com/Article/details/gtyrdktgov.html

[L05] 上传文件（multipart）
来源：http://dali.ydzc1.top/Article/details/gtkloloolm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjuqmckg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tianlin.xyz/Article/details/gtbezvxpat.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuetiantiany.cn/Article/details/gtmeqgwpir.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gogol.net.cn/Article/details/gtusutmowj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdqbuwfke.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.quarkkingdee.top/Article/details/gtvgfxynic.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jqgfzy.top/Article/details/gtnnliyqnl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtzsrrgqrg.html

[L06] 解析响应为 JSON
来源：http://dali.shuidangran.top/Article/details/gtceutjzes.html

Py:   resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gtnczvbpbx.html

PHP:  json_decode($body, true);
来源：http://dali.nanxuanxn.top/Article/details/gtizxenjvu.html

JS:   await resp.json()
来源：http://dali.jiagoushi.top/Article/details/gttvamnizr.html

TS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gthghsrtec.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.birdmap.top/Article/details/gtdlzadxbq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jlsjyb.cn/Article/details/gtmdzozded.html

Ruby: JSON.parse(resp.body)
来源：http://dali.9152youxi.cn/Article/details/gtjgglncls.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangshuangyany.cn/Article/details/gttqckamix.html

[L07] 处理 HTTP 状态码
来源：http://dali.fzhhl.top/Article/details/gtwnbiijye.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gtkoytfvbp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.svipenyu.cn/Article/details/gtyzbuolji.html

JS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gtedonqbba.html

TS:   resp.ok;  resp.status
来源：http://dali.316326.xyz/Article/details/gtnjfluzcj.html

Java: resp.statusCode()
来源：http://dali.jlsjyb.cn/Article/details/gtybnfrjax.html

Go:   resp.StatusCode
来源：http://dali.haohaochexian.top/Article/details/gtwrofbmbn.html

Ruby: resp.code.to_i
来源：http://dali.hysaishi.cn/Article/details/gtvhidhbwh.html

C#:   (int)resp.StatusCode
来源：http://dali.guowangkeji.top/Article/details/gtfdlqbmxm.html

[L08] 并发请求多个地址
来源：http://dali.gzhubu.top/Article/details/gtrjaymima.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guannengcc.top/Article/details/gtbygoxhda.html

PHP:  curl_multi_init() 系列
来源：http://dali.svipenyu.cn/Article/details/gtahhdaoit.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gtqrhsxijf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtdszlntvi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.dianchejie.cn/Article/details/gtggmwqmia.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhengqikj.top/Article/details/gtnlmsqdgf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.316326.xyz/Article/details/gtrsjfdngz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ppjwa.cn/Article/details/gtzgqgtlyq.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtuwnzicwa.html

M. 命令行 / 进程 / 环境
来源：http://dali.0kj1m.cn/Article/details/gtewdwvhcr.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtjzkfplsw.html

[M01] 读取命令行参数
来源：http://dali.kuanghao11.cn/Article/details/gtdckucxug.html

Py:   sys.argv[1:]
来源：http://dali.cucudq.cn/Article/details/gtqxascgms.html

PHP:  $argv;  $argc;
来源：http://dali.yonumen.top/Article/details/gtuckksdgn.html

JS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gtshrfnoaz.html

TS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gtlgoihxts.html

Java: args 数组（main 方法参数）
来源：http://dali.fzhhl.top/Article/details/gtoiufhqcr.html

Go:   os.Args[1:]
来源：http://dali.guowangkeji.top/Article/details/gtwmwebcwi.html

Ruby: ARGV
来源：http://dali.yj20258888.top/Article/details/gtcgkmqydr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhaomingkeji.xyz/Article/details/gthzhjvkqz.html

[M02] 读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gtowwculeh.html

Py:   os.environ.get("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtmkkjgcdk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.dianchejie.cn/Article/details/gtmijzwqca.html

JS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gtxtzvpiyf.html

TS:   process.env.HOME
来源：http://dali.tanke756.top/Article/details/gtakvxbsnj.html

Java: System.getenv("HOME")
来源：http://dali.andypj.xyz/Article/details/gtmqzxazvi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sweek.top/Article/details/gtlclpwpqh.html

Ruby: ENV["HOME"]
来源：http://dali.svipenyu.cn/Article/details/gtagrsngpa.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtlixkzrsj.html

[M03] 执行外部命令
来源：http://dali.ivvv.top/Article/details/gtrubzodcw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yonumen.top/Article/details/gtinfhxauj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jyoumei.cn/Article/details/gtuwjpdwec.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gtcyebywgs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sweek.top/Article/details/gtpdouurtp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zycfv.cn/Article/details/gteibozfqe.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jqgufenzy.top/Article/details/gtcqoatwgr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.guannengcc.top/Article/details/gtljmemfon.html

C#:   Process.Start("ls", "-l");
来源：http://dali.snrcjt.cn/Article/details/gtqzfkuvjk.html

[M04] 获取当前工作目录
来源：http://dali.bjfxy.top/Article/details/gtrykynpmw.html

Py:   os.getcwd()
来源：http://dali.gotoacloud.top/Article/details/gtiaiqnwsq.html

PHP:  getcwd();
来源：http://dali.hfpthk.cn/Article/details/gtxjxcfwqi.html

JS:   process.cwd()
来源：http://dali.bjfxy.top/Article/details/gtvxlsuagx.html

TS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gtsrvrbszy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nanxinkj.top/Article/details/gtntsfhkaf.html

Go:   os.Getwd()
来源：http://dali.zhoulong.xyz/Article/details/gtrzgqhfue.html

Ruby: Dir.pwd
来源：http://dali.cdnleiting.top/Article/details/gtobybfmya.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tianlin.xyz/Article/details/gtrckxngzi.html

[M05] 设置退出码
来源：http://dali.jinqigfzy.top/Article/details/gtqnshboys.html

Py:   sys.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtscfsidhd.html

PHP:  exit(1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtybwhjnud.html

JS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gturbfizcm.html

TS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtjzvrxegk.html

Java: System.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtdoufkufn.html

Go:   os.Exit(1)
来源：http://dali.hnqzz.top/Article/details/gtbrfyafmp.html

Ruby: exit 1
来源：http://dali.zhiwuduotai.top/Article/details/gtphnszmqq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xuetiantiany.cn/Article/details/gtuxotzjuq.html

[M06] 向标准错误输出
来源：http://dali.hywenlv.cn/Article/details/gtkutebthr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yonumen.top/Article/details/gtqkfzfjyp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj20258888.top/Article/details/gtknjfbwgx.html

JS:   console.error("err")
来源：http://dali.c1oappe.top/Article/details/gtuqxeescd.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gtproniouq.html

Java: System.err.println("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtrfziklbj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfdhqbxp.html

Ruby: warn "err"
来源：http://dali.dashuyun.cn/Article/details/gtlcwczrtb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.9152youxi.cn/Article/details/gtxetbefwp.html

[M07] 判断是否为主入口
来源：http://dali.jyoumei.cn/Article/details/gtloivvofp.html

Py:   if __name__ == "__main__":
来源：http://dali.smart0.xyz/Article/details/gtlrrccghw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shuidangran.top/Article/details/gtvhydksrj.html

JS:   require.main === module
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoexpbslx.html

TS:   require.main === module
来源：http://dali.cashguo.top/Article/details/gtrrdwlqzj.html

Java: public static void main(String[] args)
来源：http://dali.cdnleiting.top/Article/details/gtptbpdgaf.html

Go:   func main()
来源：http://dali.guowangkeji.top/Article/details/gtwjquiulr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gotoacloud.top/Article/details/gtfvnunwep.html

C#:   static void Main(string[] args)
来源：http://dali.aibaodan.cn/Article/details/gtprhojjgi.html

[M08] 获取系统与运行时信息
来源：http://dali.cdnleiting.top/Article/details/gtnygybywy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenlongwang.top/Article/details/gthloijbwp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.kuanghao11.cn/Article/details/gtturwrobh.html

JS:   process.platform;  process.version
来源：http://dali.sweek.top/Article/details/gtquefpchs.html

TS:   process.platform;  process.version
来源：http://dali.snrcjt.cn/Article/details/gtrsagiobf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.0kj1m.cn/Article/details/gtuajmzccl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cucudq.cn/Article/details/gtxkfqpnpy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.vqdsnc.cn/Article/details/gtruyqclfk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.fzhhl.top/Article/details/gtmtqublyh.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtekwgeloj.html

N. 数据结构与算法
来源：http://dali.daxiang520.top/Article/details/gtpwgrmbih.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtjajnrqcn.html

[N01] 二分查找（有序数组）
来源：http://dali.chenlongwang.top/Article/details/gttstakorh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtfeeliouo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xinyue.icu/Article/details/gtgddinhbx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.birdmap.top/Article/details/gthfgytirm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgfzy.top/Article/details/gthancnxra.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtcmyxmqmh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtnhrjegsi.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cheryme.top/Article/details/gtxgiqtuas.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtwbhqtitg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.0kj1m.cn/Article/details/gtgecoyfky.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dashuyun.cn/Article/details/gtkrtzoclu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jiagoushi.top/Article/details/gtlsotdizk.html


<!-- 参考信息 -->