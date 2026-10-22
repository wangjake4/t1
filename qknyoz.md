代发 wailian999

[J03] 字符串解析为日期
来源：http://dali.9152youxi.cn/Article/details/gtorupydsd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenzaomai.com/Article/details/gtofnejnxz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.aizwys.cn/Article/details/gtbdzurtyt.html

JS:   new Date("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtjhntzrfj.html

TS:   new Date("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtimtkxyai.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtdiepaufx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtjopsphzx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtjlwjrhjv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yangfankeji.com/Article/details/gtlftgfzxd.html

[J04] 时间戳与日期互转
来源：http://dali.jqgufenzy.top/Article/details/gtvhfyuwvl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.havefunace.top/Article/details/gtqhrfkkle.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gotoacloud.top/Article/details/gtodcmmcvw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sufxvd.cn/Article/details/gtlicbflud.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daria6918.cn/Article/details/gtqtgfkmvn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.daxiang520.top/Article/details/gtsixzxnuk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cdnleiting.top/Article/details/gtcelnyfrk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtfgthpyxz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ybcxt.top/Article/details/gtdhmimuir.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258.top/Article/details/gtcxgzadlm.html

Py:   now + timedelta(days=7)
来源：http://dali.zhiwuduotai.top/Article/details/gtegprfmov.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hfpthk.cn/Article/details/gthisihawb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aizwys.cn/Article/details/gtkywzzire.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuanzx.com/Article/details/gtfkeiaibp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yonumen.top/Article/details/gtpgyprgyx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxinkj.top/Article/details/gtonpgiofs.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yanxiufei.cn/Article/details/gtgmgatvcm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ivvv.top/Article/details/gtbphvtokc.html

[J06] 计算两时间之差
来源：http://dali.xuanzx.com/Article/details/gtlzfjfziw.html

Py:   (end - start).total_seconds()
来源：http://dali.hongshengwenyu.top/Article/details/gtdwkrbujp.html

PHP:  $end->diff($start)->days;
来源：http://dali.mhx1999.top/Article/details/gtlrharuus.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.quarkkingdee.top/Article/details/gtmpqjgaal.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangdashe.top/Article/details/gtesyzztlh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sysykeji.top/Article/details/gteqzpaysu.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenzaomai.com/Article/details/gtjchayzzr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shangyingyoupin.top/Article/details/gtsfotexek.html

C#:   (end - start).TotalSeconds
来源：http://dali.316326.xyz/Article/details/gtkpakyobl.html

[J07] 比较两个日期
来源：http://dali.yj20258.top/Article/details/gtczfmpldk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gthcrbdntw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.snrcjt.cn/Article/details/gtldlghiqe.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gtndspjsyz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jianghu66.top/Article/details/gtekfwhplm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.mhx1999.top/Article/details/gtndseesih.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yueranfly.top/Article/details/gtxipkmufd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gtglgnonpp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gtynxpkweb.html

[J08] 提取年月日与星期
来源：http://dali.nanxuanxn.top/Article/details/gtmdhxvkjw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigfzy.top/Article/details/gtgpervibo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cashguo.top/Article/details/gtagnwgxzl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhiwuduotai.top/Article/details/gtsyxjygyc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xylfe.cn/Article/details/gttsxarkdb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gtpgdwjyvw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gogol.net.cn/Article/details/gtxbguhzhf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nanxinkj.top/Article/details/gtpjecfboi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.snrcjt.cn/Article/details/gtapeqzsfm.html

[J09] 时区处理
来源：http://dali.cheryme.top/Article/details/gtrdbosdbo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cheryme.top/Article/details/gtxmfulufe.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dianchejie.cn/Article/details/gtftthwrux.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ybcxt.top/Article/details/gtcbbnnsgp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlclffrea.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.wangshuangyany.cn/Article/details/gtcccalhru.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sxryk.cn/Article/details/gttwiiihtd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shangyingyoupin.top/Article/details/gtdadjoxjb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.0kj1m.cn/Article/details/gtiryxmtxv.html

[J10] 取今天 / 本月第一天
来源：http://dali.shanyushiyangtech.top/Article/details/gttlirflqp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zdqjudy.top/Article/details/gtuhwrpgjh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.dianchejie.cn/Article/details/gtkvtvwqyj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhengqikj.top/Article/details/gtswhywhfi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenzaomai.com/Article/details/gtbqoriauc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.birdmap.top/Article/details/gtrhnvodpl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.dianchejie.cn/Article/details/gtbaixsizd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cqqwz.cn/Article/details/gtzhftuzrv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtufqyhlap.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtywckkntw.html

K. JSON 与序列化
来源：http://dali.c1oappe.top/Article/details/gtbcfemaah.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtglzhpsnt.html

[K01] 对象转 JSON 字符串
来源：http://dali.cucudq.cn/Article/details/gtfdesoqhq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gtnqvsuvyx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gtlrfmkpwq.html

JS:   JSON.stringify(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtcawihieg.html

TS:   JSON.stringify(obj)
来源：http://dali.xinyue.icu/Article/details/gtjopfmnlf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhiwuduotai.top/Article/details/gtjaxiqvlj.html

Go:   json.Marshal(obj)
来源：http://dali.ybcxt.top/Article/details/gtlkijyvip.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hongshengwenyu.top/Article/details/gtpvkaarlk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jianghu66.top/Article/details/gthansddou.html

[K02] JSON 字符串转对象
来源：http://dali.chenjidiqi.icu/Article/details/gtjntcvicv.html

Py:   json.loads(s)
来源：http://dali.yvedp.cn/Article/details/gtzitcxwop.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yongpay.top/Article/details/gtmzcvclzj.html

JS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gtcpluipgh.html

TS:   JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavjnicmh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenzaomai.com/Article/details/gtpxzylmtw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yuxming.cn/Article/details/gtnlbevdta.html

Ruby: JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gtyahssmlo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtynjfvxsb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dianchejie.cn/Article/details/gtexfmfnrx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gtttoisnea.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nwbrower.top/Article/details/gticpfnlms.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gtecxbapvw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.vqdsnc.cn/Article/details/gtvbvrkqvd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nwbrower.top/Article/details/gtyrqqmfdt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xuetiantiany.cn/Article/details/gthoxdfshh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuanzhike.top/Article/details/gtggngsmuk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.svipenyu.cn/Article/details/gtpusjlzsb.html

[K04] 读取 JSON 文件
来源：http://dali.nanxuanxn.top/Article/details/gtijxwrdxh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.vqdsnc.cn/Article/details/gtvvhwitqc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ehwqpu.com/Article/details/gtmsatpusx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tian-w.cn/Article/details/gteyqptwqy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvpzqmlpu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.c1oappe.top/Article/details/gtmuilcrod.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xylfe.cn/Article/details/gtbcjwcxcp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.aibaodan.cn/Article/details/gtnyyqoqvo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gttiijskln.html

[K05] 深拷贝对象
来源：http://dali.jinghuilouyu.cn/Article/details/gthirhetvz.html

Py:   copy.deepcopy(obj)
来源：http://dali.jyoumei.cn/Article/details/gtjuwnknho.html

PHP:  unserialize(serialize($obj));
来源：http://dali.0kj1m.cn/Article/details/gtzskstpdc.html

JS:   structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gtzveohlfg.html

TS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gtekfrktkf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jlsjyb.cn/Article/details/gtdigaprld.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.daxiang520.top/Article/details/gtvaigmmlj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sysykeji.top/Article/details/gtjrpfyigk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenjidiqi.icu/Article/details/gtywskxlis.html

[K06] 解析 URL 查询串
来源：http://dali.aizwys.cn/Article/details/gtydhflonq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.daxiang520.top/Article/details/gthpijzjwc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenjidiqi.icu/Article/details/gtbpkhdzhl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgufenzy.top/Article/details/gtkczcpekh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guowangkeji.top/Article/details/gttmwoeroe.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cheryme.top/Article/details/gtsklfrvcf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gtdqyfieug.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gtchtcnjfk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gtpblacjck.html

[K07] 进制转换
来源：http://dali.havefunace.top/Article/details/gtylwvwvbn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtknkxswmp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.316326.xyz/Article/details/gtvbfihfbn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gthcfxvwvm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gttoqxitmt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtjmlpnmgz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.mhx1999.top/Article/details/gtvifszwkn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenlongwang.top/Article/details/gtavuyputa.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtucrogzqe.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.birdmap.top/Article/details/gtmcwovpzw.html

Py:   pickle.dumps(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtjmdulxvg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinqigufen.top/Article/details/gtbvufewyd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gtspfewczx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmnhucot.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xziqi.cn/Article/details/gtqzmvuylj.html

Go:   encoding/gob
来源：http://dali.yongpay.top/Article/details/gtzxznpdro.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj202588.top/Article/details/gtljlswlkf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenlongwang.top/Article/details/gtqvzvrdcv.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtnhbxgqhg.html

L. 网络请求
来源：http://dali.yueranfly.top/Article/details/gtfbywhwmk.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtkibzjopu.html

[L01] 发送 GET 请求
来源：http://dali.gogol.net.cn/Article/details/gtsaxupgvw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnqzz.top/Article/details/gtksafhasd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.0kj1m.cn/Article/details/gtwebpgocs.html

JS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtmkudrxcg.html

TS:   await fetch(url)
来源：http://dali.ehwqpu.com/Article/details/gtgquniahs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hammf.cn/Article/details/gtdhuwysha.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gtqrqcatal.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.dashuyun.cn/Article/details/gtmjoftohm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.feifeiyinyue.top/Article/details/gtaucbnetd.html

[L02] 发送 POST JSON
来源：http://dali.sufxvd.cn/Article/details/gtkunmccgx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.svipenyu.cn/Article/details/gtmyqtusvp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.fengsongda.top/Article/details/gteekjoimc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fzhhl.top/Article/details/gtqnmnwkpz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gtzaofqagg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ybcxt.top/Article/details/gtadgebkda.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ivvv.top/Article/details/gtqbgjbtro.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.pengpengdd.cyou/Article/details/gtxrveagrj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgufenzy.top/Article/details/gtbtjuotmf.html

[L03] 设置自定义请求头
来源：http://dali.yuanzhike.top/Article/details/gtbvdquphg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.feifeiyinyue.top/Article/details/gtuedqfqit.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.aizwys.cn/Article/details/gtzxcbwfke.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.redwolf501.top/Article/details/gtppegkxax.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pycfn.com/Article/details/gthtghaorf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhongyouzk.top/Article/details/gtcepmfvro.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gtyrcoegkn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yuxming.cn/Article/details/gtizmqesdn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fengsongda.top/Article/details/gtynhbmypo.html

[L04] 设置超时
来源：http://dali.jqgfzy.top/Article/details/gturzbdicq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cashguo.top/Article/details/gtdeuabbbl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xinyue.icu/Article/details/gtvnhmqjsc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcrczbbla.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuanzx.com/Article/details/gtpihsoypc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gzhubu.top/Article/details/gtdrufcteb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.aizwys.cn/Article/details/gtimeqfccb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.c1oappe.top/Article/details/gtmpezylgn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.fzhhl.top/Article/details/gtjxmzcsyb.html

[L05] 上传文件（multipart）
来源：http://dali.jiagoushi.top/Article/details/gtiyiyigpi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.guannengcc.top/Article/details/gtvrwwqimv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.kuanghao11.cn/Article/details/gtawjlqbao.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gtgwvuohzb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gotoacloud.top/Article/details/gtltxozxtp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yanxiufei.cn/Article/details/gtnmevsepu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xziqi.cn/Article/details/gtzkxmyviq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenlongwang.top/Article/details/gtwbidwvkf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.fzhhl.top/Article/details/gtkdhajevv.html

[L06] 解析响应为 JSON
来源：http://dali.ivvv.top/Article/details/gtxuafgbir.html

Py:   resp.json()
来源：http://dali.hfpthk.cn/Article/details/gtwhoxewge.html

PHP:  json_decode($body, true);
来源：http://dali.havefunace.top/Article/details/gtfyopklph.html

JS:   await resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjliaeuiy.html

TS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gtwvxfbbul.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xziqi.cn/Article/details/gtwrzjklvu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinghuilouyu.cn/Article/details/gthhnpfduz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.vqdsnc.cn/Article/details/gtcbggtksz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shuidangran.top/Article/details/gtwqtkaacn.html

[L07] 处理 HTTP 状态码
来源：http://dali.fengsongda.top/Article/details/gtbaowvhbp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nanxinkj.top/Article/details/gtcsdiyjsq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.kuanghao11.cn/Article/details/gthqhwkfef.html

JS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gttndcjkvo.html

TS:   resp.ok;  resp.status
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnxjqabr.html

Java: resp.statusCode()
来源：http://dali.xuetiantiany.cn/Article/details/gttwkgzrgj.html

Go:   resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gtogauwwxh.html

Ruby: resp.code.to_i
来源：http://dali.yuanzhike.top/Article/details/gttzlxzjek.html

C#:   (int)resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gtitmejgma.html

[L08] 并发请求多个地址
来源：http://dali.jqgufenzy.top/Article/details/gtlconisgp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.pycfn.com/Article/details/gtcgvhneez.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gtfyvumtqb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvucwjde.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtrazzrdej.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.316326.xyz/Article/details/gtrjbvmrhi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.birdmap.top/Article/details/gtqclzxrsn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yonumen.top/Article/details/gttleinlwf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zdqjudy.top/Article/details/gtnamznykk.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtpziaxfhd.html

M. 命令行 / 进程 / 环境
来源：http://dali.feifeiyinyue.top/Article/details/gtwfqtezwu.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtlyokyrsk.html

[M01] 读取命令行参数
来源：http://dali.zycfv.cn/Article/details/gtyafzknce.html

Py:   sys.argv[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtikvyuehn.html

PHP:  $argv;  $argc;
来源：http://dali.zhiwuduotai.top/Article/details/gtfhsuyeqy.html

JS:   process.argv.slice(2)
来源：http://dali.aizwys.cn/Article/details/gtswulhsip.html

TS:   process.argv.slice(2)
来源：http://dali.zycfv.cn/Article/details/gtikgltngv.html

Java: args 数组（main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gtxnowdmcz.html

Go:   os.Args[1:]
来源：http://dali.shzxlz.cn/Article/details/gtnkyljyur.html

Ruby: ARGV
来源：http://dali.nanxuanxn.top/Article/details/gthrxshkdb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenzaomai.com/Article/details/gtbifewsbw.html

[M02] 读取环境变量
来源：http://dali.jqgfzy.top/Article/details/gtavmjkejh.html

Py:   os.environ.get("HOME")
来源：http://dali.pycfn.com/Article/details/gtogoigrew.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gtmxuzbfiq.html

JS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gtqirxdmny.html

TS:   process.env.HOME
来源：http://dali.ppjwa.cn/Article/details/gtokbxurze.html

Java: System.getenv("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtmqijhnfr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.guannengcc.top/Article/details/gtyrfmuaxg.html

Ruby: ENV["HOME"]
来源：http://dali.meibo888.top/Article/details/gtvlhnkndi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shuidangran.top/Article/details/gtoflueclr.html

[M03] 执行外部命令
来源：http://dali.chenjidiqi.icu/Article/details/gtndrmjzcj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cucudq.cn/Article/details/gtpyrmyuza.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ydzc1.top/Article/details/gtxrsfmaul.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hfpthk.cn/Article/details/gtifaykizp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cheryme.top/Article/details/gtakpsfouu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hammf.cn/Article/details/gtrlhqstoy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gtohmqvvgy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.andypj.xyz/Article/details/gtombviwoc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.iojbl.cn/Article/details/gthengokhu.html

[M04] 获取当前工作目录
来源：http://dali.sxryk.cn/Article/details/gtqnysxryg.html

Py:   os.getcwd()
来源：http://dali.c1oappe.top/Article/details/gtmvnnxxaz.html

PHP:  getcwd();
来源：http://dali.chenjidiqi.icu/Article/details/gtqxrpzjgq.html

JS:   process.cwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxcgseck.html

TS:   process.cwd()
来源：http://dali.zdqjudy.top/Article/details/gtbsiooxdd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.meibo888.top/Article/details/gtsykykkfi.html

Go:   os.Getwd()
来源：http://dali.9152youxi.cn/Article/details/gtpumnjlgn.html

Ruby: Dir.pwd
来源：http://dali.dashuyun.cn/Article/details/gtqapcojhj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hongshengwenyu.top/Article/details/gtryoophnv.html

[M05] 设置退出码
来源：http://dali.meibo888.top/Article/details/gtgcbakrng.html

Py:   sys.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gttphnpegu.html

PHP:  exit(1);
来源：http://dali.yj20258.top/Article/details/gtmtpvyxuf.html

JS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtlxqqfbnf.html

TS:   process.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtnycvjmeq.html

Java: System.exit(1)
来源：http://dali.ivvv.top/Article/details/gtcseazuyy.html

Go:   os.Exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtybcwyibx.html

Ruby: exit 1
来源：http://dali.chenjidiqi.icu/Article/details/gtlkjjfgvu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ydzc1.top/Article/details/gtlfkpfsdu.html

[M06] 向标准错误输出
来源：http://dali.tanke756.top/Article/details/gtitgkqzhp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangdashe.top/Article/details/gtlhhisege.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.mhx1999.top/Article/details/gtpyemfwtg.html

JS:   console.error("err")
来源：http://dali.gzhubu.top/Article/details/gtcrhxbikq.html

TS:   console.error("err")
来源：http://dali.yanxiufei.cn/Article/details/gtwcltngoi.html

Java: System.err.println("err")
来源：http://dali.zhiwuduotai.top/Article/details/gteflbfqzx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shangyingyoupin.top/Article/details/gtwompcwfa.html

Ruby: warn "err"
来源：http://dali.daxiang520.top/Article/details/gtgtnbsnxa.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gaohongyu789.top/Article/details/gtspkdwbio.html

[M07] 判断是否为主入口
来源：http://dali.zhoulong.xyz/Article/details/gtslmqdvra.html

Py:   if __name__ == "__main__":
来源：http://dali.daxiang520.top/Article/details/gtovtofkez.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnqzz.top/Article/details/gtrahublbu.html

JS:   require.main === module
来源：http://dali.316326.xyz/Article/details/gtirtbmwxz.html

TS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkpxexzc.html

Java: public static void main(String[] args)
来源：http://dali.sweek.top/Article/details/gtfouvwhaa.html

Go:   func main()
来源：http://dali.hnxiangtu.top/Article/details/gtdokpmnze.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.c1oappe.top/Article/details/gtunvchhqk.html

C#:   static void Main(string[] args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtknbdfgxi.html

[M08] 获取系统与运行时信息
来源：http://dali.yongpay.top/Article/details/gtlklueoxr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinqigfzy.top/Article/details/gtbpbnprqy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigfzy.top/Article/details/gthghyhmgr.html

JS:   process.platform;  process.version
来源：http://dali.chenzaomai.com/Article/details/gtqbrexjco.html

TS:   process.platform;  process.version
来源：http://dali.tian-w.cn/Article/details/gtsklhcuig.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhengqikj.top/Article/details/gtfjikuyhi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.quarkkingdee.top/Article/details/gtymakegcw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhengqikj.top/Article/details/gtnwonzazr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.svipenyu.cn/Article/details/gtlisxqlyy.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtgpjlkszl.html

N. 数据结构与算法
来源：http://dali.chenjidiqi.icu/Article/details/gttktyfvpo.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtytaqqhpw.html


<!-- 参考信息 -->