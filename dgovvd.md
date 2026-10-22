代发 wailian999

TS:   new Date("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gt2pzyfgstr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gt2jukzjvcu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gt2hglqwdzg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gt2enuzfmgp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigufen.top/Article/details/gt2jgjbduep.html

[J04] 时间戳与日期互转
来源：http://dali.shuidangran.top/Article/details/gt2xmeesqly.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jianghu66.top/Article/details/gt2qlhhzaih.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jqgfzy.top/Article/details/gt2kherzzna.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xziqi.cn/Article/details/gt2tdoqnpun.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.quarkkingdee.top/Article/details/gt2ecmuibtz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yangfankeji.com/Article/details/gt2ovzqkwcn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuanzhike.top/Article/details/gt2mhobzhuv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.vqdsnc.cn/Article/details/gt2tjbswunu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.c1oappe.top/Article/details/gt2zbhadtkm.html

[J05] 时间加减（加 7 天）
来源：http://dali.sufxvd.cn/Article/details/gt2ucoqybqq.html

Py:   now + timedelta(days=7)
来源：http://dali.sxryk.cn/Article/details/gt2zhbxzviq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ivvv.top/Article/details/gt2hlicxpxr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.9152youxi.cn/Article/details/gt2kbgdpgqo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yanxiufei.cn/Article/details/gt2okzkhfsa.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nanxinkj.top/Article/details/gt2dewyfubl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj20258888.top/Article/details/gt2cxoikbxu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jyoumei.cn/Article/details/gt2eegpsdny.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daria6918.cn/Article/details/gt2owgulykv.html

[J06] 计算两时间之差
来源：http://dali.shzxlz.cn/Article/details/gt2zqbobgxm.html

Py:   (end - start).total_seconds()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ivkztfev.html

PHP:  $end->diff($start)->days;
来源：http://dali.gotoacloud.top/Article/details/gt2ggguidlx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.bjfxy.top/Article/details/gt2dhebrzmq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jqgfzy.top/Article/details/gt2vaksrchm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shzxlz.cn/Article/details/gt2slgcxbpx.html

Go:   end.Sub(start).Hours()
来源：http://dali.aizwys.cn/Article/details/gt2apxkxsnn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.wangdashe.top/Article/details/gt2rubrxrue.html

C#:   (end - start).TotalSeconds
来源：http://dali.hywenlv.cn/Article/details/gt2qjpaepct.html

[J07] 比较两个日期
来源：http://dali.316326.xyz/Article/details/gt2snvoeoqf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gt2mxejneyz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhiwuduotai.top/Article/details/gt2wfbhhfms.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gogol.net.cn/Article/details/gt2rpeqnyaq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.dashuyun.cn/Article/details/gt2tnukzaud.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sweek.top/Article/details/gt2gnadfqnz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.bjfxy.top/Article/details/gt2ozxcxand.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gt2xcjujoet.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gt2amwdgjgk.html

[J08] 提取年月日与星期
来源：http://dali.wangshuangyany.cn/Article/details/gt2ajpajpwi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jlsjyb.cn/Article/details/gt2uqktxgtd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhiwuduotai.top/Article/details/gt2uitqxulk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xpnhriks.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wietmztk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tianlin.xyz/Article/details/gt2nhartngg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cashguo.top/Article/details/gt2ljkakrbz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hfpthk.cn/Article/details/gt2dinqhxre.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gaohongyu789.top/Article/details/gt2nsltzjcx.html

[J09] 时区处理
来源：http://dali.jyoumei.cn/Article/details/gt2qulftxvi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tanke756.top/Article/details/gt2pdwllrlx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dashuyun.cn/Article/details/gt2ezorysmf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258888.top/Article/details/gt2vgppztvt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gt2zzjrhgvg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ivvv.top/Article/details/gt2htafklup.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xziqi.cn/Article/details/gt2qvutbgkk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ewxaqiay.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gogol.net.cn/Article/details/gt2aoykqwij.html

[J10] 取今天 / 本月第一天
来源：http://dali.cucudq.cn/Article/details/gt2thewkmed.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dwaeegpv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tian-w.cn/Article/details/gt2jxwrwetz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.guannengcc.top/Article/details/gt2tjxffjlp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.redwolf501.top/Article/details/gt2rzubbqpt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.0kj1m.cn/Article/details/gt2wsrlhszg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.316326.xyz/Article/details/gt2uytzslab.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.meibo888.top/Article/details/gt2ysmlwnfa.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.9152youxi.cn/Article/details/gt2itzoaxpo.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2yypmptsv.html

K. JSON 与序列化
来源：http://dali.zhixingplan.top/Article/details/gt2cdyjngbi.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2cvigrvbi.html

[K01] 对象转 JSON 字符串
来源：http://dali.c1oappe.top/Article/details/gt2kvcnhmda.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tian-w.cn/Article/details/gt2eyfudvkc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gt2syzfsisw.html

JS:   JSON.stringify(obj)
来源：http://dali.nwbrower.top/Article/details/gt2iyjixreb.html

TS:   JSON.stringify(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2khzupbws.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.havefunace.top/Article/details/gt2vzndcyyo.html

Go:   json.Marshal(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2akuvcrjk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnqzz.top/Article/details/gt2pubsawib.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yueranfly.top/Article/details/gt2wmarfiiz.html

[K02] JSON 字符串转对象
来源：http://dali.dashuyun.cn/Article/details/gt2lpqlcfkp.html

Py:   json.loads(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2qluctyso.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tianlin.xyz/Article/details/gt2nscgfiqd.html

JS:   JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gt2hthbixuy.html

TS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xmxrgvnw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vpfyiyhe.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhoulong.xyz/Article/details/gt2uclcaiai.html

Ruby: JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gt2mdnhgbmr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenzaomai.com/Article/details/gt2zctuhlpk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhongyouzk.top/Article/details/gt2vfcysjyp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.redwolf501.top/Article/details/gt2cznvrmjw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sysykeji.top/Article/details/gt2sbecjchh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hfpthk.cn/Article/details/gt2yrwnlnin.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gt2nncojwvt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2smpkeuqz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenzaomai.com/Article/details/gt2nosoldxa.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.andypj.xyz/Article/details/gt2ureauaja.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.fzhhl.top/Article/details/gt2dyojmpvp.html

[K04] 读取 JSON 文件
来源：http://dali.yanxiufei.cn/Article/details/gt2otgzruxo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.guannengcc.top/Article/details/gt2eyntjopk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ihfibfef.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gt2tgpkwple.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gt2qtnwcyag.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.haohaochexian.top/Article/details/gt2efmnuool.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gt2uaivtjbr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kfavlznm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhongyouzk.top/Article/details/gt2plggufat.html

[K05] 深拷贝对象
来源：http://dali.0kj1m.cn/Article/details/gt2hmzeylvy.html

Py:   copy.deepcopy(obj)
来源：http://dali.pycfn.com/Article/details/gt2uqstestl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jyoumei.cn/Article/details/gt2zamhfail.html

JS:   structuredClone(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2gxozbpjg.html

TS:   structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2xhsmulix.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jyoumei.cn/Article/details/gt2tjrngkdn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.andypj.xyz/Article/details/gt2rtbhbfxx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gaohongyu789.top/Article/details/gt2qmcywkiq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sxryk.cn/Article/details/gt2fklzbyzj.html

[K06] 解析 URL 查询串
来源：http://dali.zdqjudy.top/Article/details/gt2gsmnwmcw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jianghu66.top/Article/details/gt2gzlbmqno.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shuidangran.top/Article/details/gt2suukcpmq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gt2nrmktgcm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gotoacloud.top/Article/details/gt2hnttcapx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gogol.net.cn/Article/details/gt2pnjjvknw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gt2onslrcsn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gt2onlxyown.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gt2bwflwgmy.html

[K07] 进制转换
来源：http://dali.zhixingplan.top/Article/details/gt2hrfjomaw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2reyijqap.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gotoacloud.top/Article/details/gt2stbuziho.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gt2bmmkflck.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gt2qwitgoqj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fnskxfix.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhengqikj.top/Article/details/gt2czjooftn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.nanxuanxn.top/Article/details/gt2enkdknfw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gt2uysxhant.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nwbrower.top/Article/details/gt2zvsqlxei.html

Py:   pickle.dumps(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2bddhyxzk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jiagoushi.top/Article/details/gt2crzfuplw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.0kj1m.cn/Article/details/gt2wbiuuher.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.aizwys.cn/Article/details/gt2hgrftsji.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ppjwa.cn/Article/details/gt2lvprvwvv.html

Go:   encoding/gob
来源：http://dali.hongshengwenyu.top/Article/details/gt2cciuwjeb.html

Ruby: Marshal.dump(obj)
来源：http://dali.jianghu66.top/Article/details/gt2njfldgir.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangshuangyany.cn/Article/details/gt2gmuwbxry.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2lroqjfvg.html

L. 网络请求
来源：http://dali.tianlin.xyz/Article/details/gt2eitlggfm.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2mcfikvko.html

[L01] 发送 GET 请求
来源：http://dali.cqqwz.cn/Article/details/gt2vucogcpk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sweek.top/Article/details/gt2apehbxbu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinqigfzy.top/Article/details/gt2extxsqfm.html

JS:   await fetch(url)
来源：http://dali.aibaodan.cn/Article/details/gt2aswjpbes.html

TS:   await fetch(url)
来源：http://dali.chenlongwang.top/Article/details/gt2lwslqjtw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jiagoushi.top/Article/details/gt2komvaivp.html

Go:   resp, err := http.Get(url)
来源：http://dali.dianchejie.cn/Article/details/gt2jcuxkiwh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj20258.top/Article/details/gt2kuzcsdpl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj202588.top/Article/details/gt2rnqxgjeu.html

[L02] 发送 POST JSON
来源：http://dali.jyoumei.cn/Article/details/gt2liqihetg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kksrbkev.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nwbrower.top/Article/details/gt2thejbmhl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gt2nzsesekx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ivvv.top/Article/details/gt2remayuko.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.svipenyu.cn/Article/details/gt2mikchhps.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.mhx1999.top/Article/details/gt2ocjqhxvz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hnxiangtu.top/Article/details/gt2sbmnpmcm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.dianchejie.cn/Article/details/gt2iysvkhrw.html

[L03] 设置自定义请求头
来源：http://dali.cashguo.top/Article/details/gt2xnjpxitq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenzaomai.com/Article/details/gt2emnmktlt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hfpthk.cn/Article/details/gt2iseeyspi.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.316326.xyz/Article/details/gt2npubaool.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ppjwa.cn/Article/details/gt2pucgclsz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gzhubu.top/Article/details/gt2nshcssrz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hongshengwenyu.top/Article/details/gt2nedpxsis.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.havefunace.top/Article/details/gt2pnbvzxur.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gt2qzafofdw.html

[L04] 设置超时
来源：http://dali.ppjwa.cn/Article/details/gt2zrhncxuu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.redwolf501.top/Article/details/gt2hdawjllh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tian-w.cn/Article/details/gt2bodxxmiy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gt2rxueblwe.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gt2coocnarc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuanzhike.top/Article/details/gt2zqtwagbf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zycfv.cn/Article/details/gt2jzseowhr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xinyue.icu/Article/details/gt2nxirrjte.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yangfankeji.com/Article/details/gt2bcmvwmmb.html

[L05] 上传文件（multipart）
来源：http://dali.dianchejie.cn/Article/details/gt2bkeccnkg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.redwolf501.top/Article/details/gt2ypzqkjlt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ivvv.top/Article/details/gt2gewesthv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgfzy.top/Article/details/gt2ocbsykjt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258.top/Article/details/gt2levqlbcl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.vqdsnc.cn/Article/details/gt2eamlsgkn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jiagoushi.top/Article/details/gt2rbswxebs.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ppjwa.cn/Article/details/gt2dxcfowfk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2bxbgrdhm.html

[L06] 解析响应为 JSON
来源：http://dali.snrcjt.cn/Article/details/gt2xndachim.html

Py:   resp.json()
来源：http://dali.shuidangran.top/Article/details/gt2ytferwxa.html

PHP:  json_decode($body, true);
来源：http://dali.yvedp.cn/Article/details/gt2kehhxuic.html

JS:   await resp.json()
来源：http://dali.meibo888.top/Article/details/gt2usmsqnwa.html

TS:   await resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sjrrnrxw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ybcxt.top/Article/details/gt2mngcgnkg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jlsjyb.cn/Article/details/gt2lgkdlbwn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.daxiang520.top/Article/details/gt2rdzvzecj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cucudq.cn/Article/details/gt2oqputavf.html

[L07] 处理 HTTP 状态码
来源：http://dali.hammf.cn/Article/details/gt2rqssycjm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yanxiufei.cn/Article/details/gt2jqlztbip.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jiagoushi.top/Article/details/gt2gaagrkhd.html

JS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vosjdwrv.html

TS:   resp.ok;  resp.status
来源：http://dali.jlsjyb.cn/Article/details/gt2htsbwgnf.html

Java: resp.statusCode()
来源：http://dali.tanke756.top/Article/details/gt2ggjcvaaz.html

Go:   resp.StatusCode
来源：http://dali.redwolf501.top/Article/details/gt2iaiigxym.html

Ruby: resp.code.to_i
来源：http://dali.tian-w.cn/Article/details/gt2hhjvofhd.html

C#:   (int)resp.StatusCode
来源：http://dali.yj202588.top/Article/details/gt2wkcfphns.html

[L08] 并发请求多个地址
来源：http://dali.hammf.cn/Article/details/gt2azzedvso.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.kuanghao11.cn/Article/details/gt2lhwpwkyy.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj20258.top/Article/details/gt2qcndncaq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gt2obqljejz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.mhx1999.top/Article/details/gt2pgtgbsau.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cqqwz.cn/Article/details/gt2wvkvhfss.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gotoacloud.top/Article/details/gt2sjxspavc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xylfe.cn/Article/details/gt2kppbexvo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sufxvd.cn/Article/details/gt2ieebgbjp.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2bjswdwam.html

M. 命令行 / 进程 / 环境
来源：http://dali.gotoacloud.top/Article/details/gt2uyfktbvu.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2wtfpzmfc.html

[M01] 读取命令行参数
来源：http://dali.tianlin.xyz/Article/details/gt2gasqpvwk.html

Py:   sys.argv[1:]
来源：http://dali.c1oappe.top/Article/details/gt2dfztzxcr.html

PHP:  $argv;  $argc;
来源：http://dali.shangyingyoupin.top/Article/details/gt2fcabuopm.html

JS:   process.argv.slice(2)
来源：http://dali.daria6918.cn/Article/details/gt2cqrqbasb.html

TS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gt2ciosefub.html

Java: args 数组（main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gt2giovffsv.html

Go:   os.Args[1:]
来源：http://dali.zhongyouzk.top/Article/details/gt2qsehudkg.html

Ruby: ARGV
来源：http://dali.zhengqikj.top/Article/details/gt2npcaoght.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gt2bzfmslvc.html

[M02] 读取环境变量
来源：http://dali.cashguo.top/Article/details/gt2hlbgjsat.html

Py:   os.environ.get("HOME")
来源：http://dali.daria6918.cn/Article/details/gt2hrvjtywf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gt2ntweulwd.html

JS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gt2ygxluldm.html

TS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gt2mekqupxy.html

Java: System.getenv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gt2deqgsjlx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cheryme.top/Article/details/gt2sooajfgq.html

Ruby: ENV["HOME"]
来源：http://dali.mhx1999.top/Article/details/gt2npxgqnkq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sysykeji.top/Article/details/gt2onnmubuc.html

[M03] 执行外部命令
来源：http://dali.zhongyouzk.top/Article/details/gt2ztzkwyhr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.0kj1m.cn/Article/details/gt2rgchnnzk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hwbcpmsd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cheryme.top/Article/details/gt2titiqzjz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nwbrower.top/Article/details/gt2olvmpfkk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cucudq.cn/Article/details/gt2xfvedhni.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tian-w.cn/Article/details/gt2qugpfzta.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigfzy.top/Article/details/gt2dfasyhlm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ydzc1.top/Article/details/gt2cigpkwbk.html

[M04] 获取当前工作目录
来源：http://dali.ydzc1.top/Article/details/gt2eevbuyas.html

Py:   os.getcwd()
来源：http://dali.birdmap.top/Article/details/gt2gkxcudrq.html

PHP:  getcwd();
来源：http://dali.ivvv.top/Article/details/gt2pdzdvbjk.html

JS:   process.cwd()
来源：http://dali.pycfn.com/Article/details/gt2ujcmpnmb.html

TS:   process.cwd()
来源：http://dali.iojbl.cn/Article/details/gt2cjzqorzg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgfzy.top/Article/details/gt2rqcozxhi.html

Go:   os.Getwd()
来源：http://dali.guannengcc.top/Article/details/gt2hbdlqaky.html

Ruby: Dir.pwd
来源：http://dali.ppjwa.cn/Article/details/gt2pdsrmomo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.feifeiyinyue.top/Article/details/gt2pmmnfwdd.html

[M05] 设置退出码
来源：http://dali.gzhubu.top/Article/details/gt2yukkmaay.html

Py:   sys.exit(1)
来源：http://dali.yueranfly.top/Article/details/gt2emsoxlxm.html

PHP:  exit(1);
来源：http://dali.ivvv.top/Article/details/gt2labvycfp.html

JS:   process.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gt2zzkcjdwb.html

TS:   process.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zerizvee.html

Java: System.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2uzkumqjr.html

Go:   os.Exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sdydiesb.html

Ruby: exit 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jqdbtbch.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.c1oappe.top/Article/details/gt2fpavanus.html

[M06] 向标准错误输出
来源：http://dali.svipenyu.cn/Article/details/gt2vkkqcgba.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangdashe.top/Article/details/gt2orwyehej.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.guowangkeji.top/Article/details/gt2wfgazmol.html

JS:   console.error("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2boivwtgf.html

TS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2crmnvjrt.html

Java: System.err.println("err")
来源：http://dali.9152youxi.cn/Article/details/gt2ynetnxwa.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pycfn.com/Article/details/gt2zofxvrnf.html

Ruby: warn "err"
来源：http://dali.yueranfly.top/Article/details/gt2xodksxxe.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ehwqpu.com/Article/details/gt2fiuutxty.html

[M07] 判断是否为主入口
来源：http://dali.aizwys.cn/Article/details/gt2wufnywxz.html

Py:   if __name__ == "__main__":
来源：http://dali.jlsjyb.cn/Article/details/gt2xhyogaew.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinghuilouyu.cn/Article/details/gt2muutctgx.html

JS:   require.main === module
来源：http://dali.jianghu66.top/Article/details/gt2aeokjndf.html

TS:   require.main === module
来源：http://dali.zhiwuduotai.top/Article/details/gt2tllmnfeo.html

Java: public static void main(String[] args)
来源：http://dali.jyoumei.cn/Article/details/gt2fwlwcttw.html

Go:   func main()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vlslbmbb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hongshengwenyu.top/Article/details/gt2amyurjfy.html

C#:   static void Main(string[] args)
来源：http://dali.fengsongda.top/Article/details/gt2jaqgqjnq.html

[M08] 获取系统与运行时信息
来源：http://dali.hongshengwenyu.top/Article/details/gt2oupmrlcj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yonumen.top/Article/details/gt2kgvwtdhz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.feifeiyinyue.top/Article/details/gt2pbmyicif.html

JS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gt2muovhoio.html

TS:   process.platform;  process.version
来源：http://dali.hfpthk.cn/Article/details/gt2drfvbajx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.kuanghao11.cn/Article/details/gt2wvaohqci.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhengqikj.top/Article/details/gt2brmxronr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yongpay.top/Article/details/gt2ngfutxfe.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zycfv.cn/Article/details/gt2pmytcjwh.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2dlhbdywf.html

N. 数据结构与算法
来源：http://dali.shanyushiyangtech.top/Article/details/gt2losgfrdg.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2nbvsxrcc.html

[N01] 二分查找（有序数组）
来源：http://dali.fengsongda.top/Article/details/gt2rgndfeai.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gt2xyfcwnrk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shuidangran.top/Article/details/gt2khfsngfl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxinkj.top/Article/details/gt2pnyfdzwq.html


<!-- 参考信息 -->