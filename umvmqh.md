代发 wailian999

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.vqdsnc.cn/Article/details/gt2cdqcikof.html

[J04] 时间戳与日期互转
来源：http://dali.xziqi.cn/Article/details/gt2dmjcgpzp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nanxinkj.top/Article/details/gt2mbntvdqk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cdnleiting.top/Article/details/gt2saazbwpo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sysykeji.top/Article/details/gt2tdiqrqzd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.iojbl.cn/Article/details/gt2nypggmjb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bptebtvm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gogol.net.cn/Article/details/gt2ryowjqzj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.9152youxi.cn/Article/details/gt2qwhuzycc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenlongwang.top/Article/details/gt2rzgkiehz.html

[J05] 时间加减（加 7 天）
来源：http://dali.xziqi.cn/Article/details/gt2rkfyntpr.html

Py:   now + timedelta(days=7)
来源：http://dali.guannengcc.top/Article/details/gt2uxcecogm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.mhx1999.top/Article/details/gt2mfijhfmv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.c1oappe.top/Article/details/gt2fxvalgjk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gt2zaapjrpa.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cdnleiting.top/Article/details/gt2kqskueue.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.mhx1999.top/Article/details/gt2ojrfuqqo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cdnleiting.top/Article/details/gt2ddyuijnl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuxming.cn/Article/details/gt2hscyrccq.html

[J06] 计算两时间之差
来源：http://dali.jyoumei.cn/Article/details/gt2fnqbgcxu.html

Py:   (end - start).total_seconds()
来源：http://dali.pengpengdd.cyou/Article/details/gt2gccbrrhb.html

PHP:  $end->diff($start)->days;
来源：http://dali.xylfe.cn/Article/details/gt2szmhfkxx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daxiang520.top/Article/details/gt2ikngiqok.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.redwolf501.top/Article/details/gt2xgnqfsqi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhengqikj.top/Article/details/gt2jujwaljq.html

Go:   end.Sub(start).Hours()
来源：http://dali.wangdashe.top/Article/details/gt2vudfolte.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jiagoushi.top/Article/details/gt2hhruxqvl.html

C#:   (end - start).TotalSeconds
来源：http://dali.fengsongda.top/Article/details/gt2yisgpeub.html

[J07] 比较两个日期
来源：http://dali.svipenyu.cn/Article/details/gt2junhpaqj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gt2knymmpll.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xgvwjymu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yuxming.cn/Article/details/gt2jjpftzfu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gt2xtghzpol.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.birdmap.top/Article/details/gt2bdljsgvo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nanxinkj.top/Article/details/gt2yanbllku.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gt2gigqredd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gt2ayhpbimv.html

[J08] 提取年月日与星期
来源：http://dali.jianghu66.top/Article/details/gt2exswycsa.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ydzc1.top/Article/details/gt2hrwaecrh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sweek.top/Article/details/gt2aczpkajc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.0kj1m.cn/Article/details/gt2qnbmmvaa.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.meibo888.top/Article/details/gt2dbbdokma.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgfzy.top/Article/details/gt2rjtftjid.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj20258.top/Article/details/gt2ieowyulx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.svipenyu.cn/Article/details/gt2bzktavqv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.smart0.xyz/Article/details/gt2qntqlqrb.html

[J09] 时区处理
来源：http://dali.vqdsnc.cn/Article/details/gt2evswahjg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shuidangran.top/Article/details/gt2ivvjahen.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.meibo888.top/Article/details/gt2scmxkfkh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gt2jxwdmdwz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fengsongda.top/Article/details/gt2wwsvssfq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tianlin.xyz/Article/details/gt2sjznpajy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yangfankeji.com/Article/details/gt2fyegzval.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhixingplan.top/Article/details/gt2ywhbciiy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.birdmap.top/Article/details/gt2wairelif.html

[J10] 取今天 / 本月第一天
来源：http://dali.cqqwz.cn/Article/details/gt2kfegiluw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.bjfxy.top/Article/details/gt2rodcxszz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxuanxn.top/Article/details/gt2hxuamrfk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hikzpgdd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xziqi.cn/Article/details/gt2dstttoju.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yangfankeji.com/Article/details/gt2pyahsxiz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj20258.top/Article/details/gt2xwwmrcsw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.quarkkingdee.top/Article/details/gt2fngcypyl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ydzc1.top/Article/details/gt2pdfsgljl.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2carwgvds.html

K. JSON 与序列化
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pifkkxka.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2rqwcuock.html

[K01] 对象转 JSON 字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oreiwrdo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ehwqpu.com/Article/details/gt2eqynumep.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gt2prtvmsmc.html

JS:   JSON.stringify(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2fybvifxx.html

TS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gt2yrbmftuy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.mhx1999.top/Article/details/gt2qbbcsulj.html

Go:   json.Marshal(obj)
来源：http://dali.316326.xyz/Article/details/gt2uggbzylk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tianlin.xyz/Article/details/gt2knjpnnfu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2ircweuzi.html

[K02] JSON 字符串转对象
来源：http://dali.zhongyouzk.top/Article/details/gt2cskrhzqr.html

Py:   json.loads(s)
来源：http://dali.birdmap.top/Article/details/gt2evitafkj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenjidiqi.icu/Article/details/gt2ykcgnodl.html

JS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gt2icprypfr.html

TS:   JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fdhaxccx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.guannengcc.top/Article/details/gt2pvfjoclr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tianlin.xyz/Article/details/gt2pzsqodhx.html

Ruby: JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gt2debdijlg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ppjwa.cn/Article/details/gt2vhvxsqlz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinqigfzy.top/Article/details/gt2txsmdxdr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tian-w.cn/Article/details/gt2dquilfyk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tszudizk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.birdmap.top/Article/details/gt2taiiznet.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yvedp.cn/Article/details/gt2cozvasqj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2aouuwokq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.havefunace.top/Article/details/gt2nuzgfoye.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.daria6918.cn/Article/details/gt2azojcjca.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.wangdashe.top/Article/details/gt2serlqnzr.html

[K04] 读取 JSON 文件
来源：http://dali.svipenyu.cn/Article/details/gt2panmxgnz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.daxiang520.top/Article/details/gt2vmtfalgb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.meibo888.top/Article/details/gt2jfccwcpg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zdqjudy.top/Article/details/gt2rexvmaxn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2rzluclge.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shzxlz.cn/Article/details/gt2slqozqjo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gt2jfhjfwsv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hnxiangtu.top/Article/details/gt2cllaewrv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ehwqpu.com/Article/details/gt2ubwfarer.html

[K05] 深拷贝对象
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eujhyuda.html

Py:   copy.deepcopy(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2pihpiatd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhiwuduotai.top/Article/details/gt2hvdrmrqe.html

JS:   structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2itnjizws.html

TS:   structuredClone(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dmjtupwc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.fzhhl.top/Article/details/gt2ajfsrnzb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jqgufenzy.top/Article/details/gt2qyxmceko.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fengsongda.top/Article/details/gt2nwnsemdu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gaohongyu789.top/Article/details/gt2oczyhcum.html

[K06] 解析 URL 查询串
来源：http://dali.ivvv.top/Article/details/gt2mnjsfrgw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sysykeji.top/Article/details/gt2xceecvku.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yonumen.top/Article/details/gt2dqazkvrr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnqzz.top/Article/details/gt2mqmdchax.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sweek.top/Article/details/gt2ktzhbvws.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gogol.net.cn/Article/details/gt2ylqdyrwf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gt2jynpmodg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ezeionbo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gt2fokyqchk.html

[K07] 进制转换
来源：http://dali.svipenyu.cn/Article/details/gt2vdmnavan.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gt2nzhgndkt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigfzy.top/Article/details/gt2hakxlgqh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xwgyvpis.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2ukbmrcwq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gt2fshobjrk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sysykeji.top/Article/details/gt2mnirviza.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.c1oappe.top/Article/details/gt2dnuzliid.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2vuxexbaa.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yonumen.top/Article/details/gt2ibtmcasb.html

Py:   pickle.dumps(obj)
来源：http://dali.daxiang520.top/Article/details/gt2wgrswbcd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.fengsongda.top/Article/details/gt2beiodyft.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gt2ziusozeq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yueranfly.top/Article/details/gt2fcvrmzjd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yonumen.top/Article/details/gt2owqscxwn.html

Go:   encoding/gob
来源：http://dali.jianghu66.top/Article/details/gt2ezuewytw.html

Ruby: Marshal.dump(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2mxizfbcd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gt2dfrzrnud.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2wexzswvr.html

L. 网络请求
来源：http://dali.fzhhl.top/Article/details/gt2akvsdghw.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2pundyvkj.html

[L01] 发送 GET 请求
来源：http://dali.cqqwz.cn/Article/details/gt2vbgkrmze.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.daxiang520.top/Article/details/gt2xafubzui.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.fengsongda.top/Article/details/gt2gtuvypqp.html

JS:   await fetch(url)
来源：http://dali.andypj.xyz/Article/details/gt2pntnxtjy.html

TS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gt2gvkxxmdv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2srltlnpi.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mcqcblwm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xuetiantiany.cn/Article/details/gt2yktkcehy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rhhvoiuv.html

[L02] 发送 POST JSON
来源：http://dali.gzhubu.top/Article/details/gt2zkuboofy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jlaughjw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jlsjyb.cn/Article/details/gt2uvfogiqf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj202588.top/Article/details/gt2xhprcgbl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gt2lwsmjnsd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.aibaodan.cn/Article/details/gt2oyatiqmu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhoulong.xyz/Article/details/gt2imwcvuau.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sysykeji.top/Article/details/gt2osugmnjg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yonumen.top/Article/details/gt2wpdabdxs.html

[L03] 设置自定义请求头
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kcxkgnky.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fzhhl.top/Article/details/gt2jkupelti.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ybcxt.top/Article/details/gt2wdfitohx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gt2wcoqenzb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gt2xczhqkzs.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.vqdsnc.cn/Article/details/gt2grrjcell.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.316326.xyz/Article/details/gt2hbwzvcvj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258.top/Article/details/gt2ctgzfdxj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gt2ejdjataj.html

[L04] 设置超时
来源：http://dali.nanxuanxn.top/Article/details/gt2yqfezrxk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gaohongyu789.top/Article/details/gt2zaeiznoe.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ppjwa.cn/Article/details/gt2cqyioxvr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hysaishi.cn/Article/details/gt2otscfcrc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fengsongda.top/Article/details/gt2ustzfvdp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.andypj.xyz/Article/details/gt2vqpwuyiy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hfpthk.cn/Article/details/gt2ubcckhvb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.havefunace.top/Article/details/gt2xrqpblzd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.9152youxi.cn/Article/details/gt2gwtgkxau.html

[L05] 上传文件（multipart）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vkygnrhq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.smart0.xyz/Article/details/gt2trvudarq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cqqwz.cn/Article/details/gt2srowllty.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yongpay.top/Article/details/gt2yhelywye.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gt2csapdxvf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgfzy.top/Article/details/gt2eapndnhm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.snrcjt.cn/Article/details/gt2kqzswuov.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.meibo888.top/Article/details/gt2iuuprlws.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2ydmtqjsi.html

[L06] 解析响应为 JSON
来源：http://dali.sxryk.cn/Article/details/gt2fsxwmawy.html

Py:   resp.json()
来源：http://dali.ppjwa.cn/Article/details/gt2dvfrpkpf.html

PHP:  json_decode($body, true);
来源：http://dali.zhoulong.xyz/Article/details/gt2vwmhqevu.html

JS:   await resp.json()
来源：http://dali.jinqigufen.top/Article/details/gt2xfpabjxe.html

TS:   await resp.json()
来源：http://dali.jinqigufen.top/Article/details/gt2kjpvzqcm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gt2rbukjmja.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.wangdashe.top/Article/details/gt2bjmxhemn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gzhubu.top/Article/details/gt2cdrndwud.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gaohongyu789.top/Article/details/gt2qqwkdyqt.html

[L07] 处理 HTTP 状态码
来源：http://dali.snrcjt.cn/Article/details/gt2kceyecuo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.svipenyu.cn/Article/details/gt2bswkvgfy.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.bjfxy.top/Article/details/gt2wahkgeuc.html

JS:   resp.ok;  resp.status
来源：http://dali.sweek.top/Article/details/gt2wyhcwdte.html

TS:   resp.ok;  resp.status
来源：http://dali.hnxiangtu.top/Article/details/gt2wftnzjzk.html

Java: resp.statusCode()
来源：http://dali.smart0.xyz/Article/details/gt2tlvvqhsz.html

Go:   resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gt2eascyawl.html

Ruby: resp.code.to_i
来源：http://dali.sxryk.cn/Article/details/gt2mmvnmblj.html

C#:   (int)resp.StatusCode
来源：http://dali.ehwqpu.com/Article/details/gt2pvpvkkfh.html

[L08] 并发请求多个地址
来源：http://dali.ydzc1.top/Article/details/gt2hvdagyzi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.svipenyu.cn/Article/details/gt2ihkpbkzo.html

PHP:  curl_multi_init() 系列
来源：http://dali.guowangkeji.top/Article/details/gt2evmirwpc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gt2tltagnxw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gt2qqhmjwmp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhixingplan.top/Article/details/gt2pgbzozzh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mgebtuay.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cqqwz.cn/Article/details/gt2fnkpcvnw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cqqwz.cn/Article/details/gt2yunewjtt.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2qvcunobx.html

M. 命令行 / 进程 / 环境
来源：http://dali.guannengcc.top/Article/details/gt2sgevvwez.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2zqllradi.html

[M01] 读取命令行参数
来源：http://dali.smart0.xyz/Article/details/gt2mbtjprwe.html

Py:   sys.argv[1:]
来源：http://dali.yueranfly.top/Article/details/gt2oryaqnrh.html

PHP:  $argv;  $argc;
来源：http://dali.mhx1999.top/Article/details/gt2sfswrdfv.html

JS:   process.argv.slice(2)
来源：http://dali.ehwqpu.com/Article/details/gt2dlhhlqju.html

TS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gt2wuhrzouy.html

Java: args 数组（main 方法参数）
来源：http://dali.jyoumei.cn/Article/details/gt2xlgbqvng.html

Go:   os.Args[1:]
来源：http://dali.cheryme.top/Article/details/gt2qnijcahm.html

Ruby: ARGV
来源：http://dali.sxryk.cn/Article/details/gt2uuhysmrj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yonumen.top/Article/details/gt2gnkurxqp.html

[M02] 读取环境变量
来源：http://dali.hysaishi.cn/Article/details/gt2zsohmndh.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2slsnszlg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gt2xqxymtsn.html

JS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gt2cdwmplcp.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2amukbnzd.html

Java: System.getenv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gt2mjxbsmgi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xinyue.icu/Article/details/gt2nvzxmini.html

Ruby: ENV["HOME"]
来源：http://dali.pengpengdd.cyou/Article/details/gt2xjeygiex.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jianghu66.top/Article/details/gt2ejddvqes.html

[M03] 执行外部命令
来源：http://dali.smart0.xyz/Article/details/gt2tndvtavd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2znwgqnbk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cdnleiting.top/Article/details/gt2nylsantx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uikdxlbx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.redwolf501.top/Article/details/gt2oenvhrjg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gogol.net.cn/Article/details/gt2euvnfxxz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sweek.top/Article/details/gt2oppqauqz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.quarkkingdee.top/Article/details/gt2gdtozrfs.html

C#:   Process.Start("ls", "-l");
来源：http://dali.pycfn.com/Article/details/gt2yrcecbjz.html

[M04] 获取当前工作目录
来源：http://dali.cqqwz.cn/Article/details/gt2qxwshaem.html

Py:   os.getcwd()
来源：http://dali.quarkkingdee.top/Article/details/gt2quandgrl.html

PHP:  getcwd();
来源：http://dali.tianlin.xyz/Article/details/gt2deabysmv.html

JS:   process.cwd()
来源：http://dali.daria6918.cn/Article/details/gt2gaatwomu.html

TS:   process.cwd()
来源：http://dali.jianghu66.top/Article/details/gt2gnklczav.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hnqzz.top/Article/details/gt2fgonehgs.html

Go:   os.Getwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wqntqjij.html

Ruby: Dir.pwd
来源：http://dali.yongpay.top/Article/details/gt2rhzqvfpv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.guowangkeji.top/Article/details/gt2qewqfppt.html

[M05] 设置退出码
来源：http://dali.hnxiangtu.top/Article/details/gt2nldghlza.html

Py:   sys.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gt2jfrdxhcg.html

PHP:  exit(1);
来源：http://dali.sufxvd.cn/Article/details/gt2zhlwhmjq.html

JS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gt2ykzemzfk.html

TS:   process.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gt2qxwoijcz.html

Java: System.exit(1)
来源：http://dali.shuidangran.top/Article/details/gt2nkezfrtc.html

Go:   os.Exit(1)
来源：http://dali.tanke756.top/Article/details/gt2ypfteyxb.html

Ruby: exit 1
来源：http://dali.svipenyu.cn/Article/details/gt2hurwvlxh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.andypj.xyz/Article/details/gt2jofnvrvj.html

[M06] 向标准错误输出
来源：http://dali.9152youxi.cn/Article/details/gt2nxtnprfv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.quarkkingdee.top/Article/details/gt2dtkvaras.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sufxvd.cn/Article/details/gt2nkgtwdjo.html

JS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gt2xyivouub.html

TS:   console.error("err")
来源：http://dali.pycfn.com/Article/details/gt2xddledys.html

Java: System.err.println("err")
来源：http://dali.316326.xyz/Article/details/gt2jcvohahl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ppjwa.cn/Article/details/gt2gsfybqcy.html

Ruby: warn "err"
来源：http://dali.vqdsnc.cn/Article/details/gt2vrsvsgst.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hongshengwenyu.top/Article/details/gt2njfygsot.html

[M07] 判断是否为主入口
来源：http://dali.redwolf501.top/Article/details/gt2xwixizok.html

Py:   if __name__ == "__main__":
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nuzgqpaq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinqigfzy.top/Article/details/gt2fublhgac.html

JS:   require.main === module
来源：http://dali.yonumen.top/Article/details/gt2dsssdkgs.html

TS:   require.main === module
来源：http://dali.yj20258888.top/Article/details/gt2axcppdaj.html

Java: public static void main(String[] args)
来源：http://dali.yj20258.top/Article/details/gt2ihxidify.html

Go:   func main()
来源：http://dali.hywenlv.cn/Article/details/gt2azxbenkj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.havefunace.top/Article/details/gt2jbdkcelk.html

C#:   static void Main(string[] args)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jswsuvrw.html

[M08] 获取系统与运行时信息
来源：http://dali.aizwys.cn/Article/details/gt2nznhkwlt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yonumen.top/Article/details/gt2uauscwxn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.birdmap.top/Article/details/gt2dahzdqxd.html

JS:   process.platform;  process.version
来源：http://dali.fengsongda.top/Article/details/gt2qovdtgkv.html

TS:   process.platform;  process.version
来源：http://dali.shzxlz.cn/Article/details/gt2heyrtscv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj20258.top/Article/details/gt2dkbepcba.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nanxinkj.top/Article/details/gt2jqncekdl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gzhubu.top/Article/details/gt2ecyyxyoo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guowangkeji.top/Article/details/gt2fbcrdmrz.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2ejqlqinm.html

N. 数据结构与算法
来源：http://dali.xinyue.icu/Article/details/gt2marnozjc.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2xtpkckxf.html

[N01] 二分查找（有序数组）
来源：http://dali.zhiwuduotai.top/Article/details/gt2mfegmquf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dehvcckv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.dashuyun.cn/Article/details/gt2mzzqkwzu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gt2jcmogssw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.316326.xyz/Article/details/gt2ympkixew.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cashguo.top/Article/details/gt2gggdvgbs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sxvfictl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hammf.cn/Article/details/gt2lwjduuez.html


<!-- 参考信息 -->