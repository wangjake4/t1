代发 wailian999

TS:   new Date("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtdyfkbmsk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtvtuxbofa.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtjwosadmi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtacfsnjkm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.c1oappe.top/Article/details/gtnchiqsaw.html

[J04] 时间戳与日期互转
来源：http://dali.xziqi.cn/Article/details/gtppeurofv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixsvzugi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.guannengcc.top/Article/details/gtrhqqzqzv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jqgfzy.top/Article/details/gtiswapgcp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xylfe.cn/Article/details/gttbnzvgiu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.meibo888.top/Article/details/gttwswhbni.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.iojbl.cn/Article/details/gtbqapbohm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtfeybhomx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gtlhwddjqv.html

[J05] 时间加减（加 7 天）
来源：http://dali.yonumen.top/Article/details/gtoahvsfku.html

Py:   now + timedelta(days=7)
来源：http://dali.iojbl.cn/Article/details/gtqyvoqevr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yonumen.top/Article/details/gtoytaoege.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cashguo.top/Article/details/gtouzqchiz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fzhhl.top/Article/details/gtjwfwaquy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenjidiqi.icu/Article/details/gtpzdqogil.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybbeznrd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.bjfxy.top/Article/details/gtrggccphu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yvedp.cn/Article/details/gthqodohbi.html

[J06] 计算两时间之差
来源：http://dali.sweek.top/Article/details/gtdfhmehmg.html

Py:   (end - start).total_seconds()
来源：http://dali.ehwqpu.com/Article/details/gtvenfseqy.html

PHP:  $end->diff($start)->days;
来源：http://dali.ydzc1.top/Article/details/gtduzburoo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cqqwz.cn/Article/details/gtoiprnnfw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinghuilouyu.cn/Article/details/gtiufihhrp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.redwolf501.top/Article/details/gtaloprfvt.html

Go:   end.Sub(start).Hours()
来源：http://dali.xinyue.icu/Article/details/gtgtgheeau.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yonumen.top/Article/details/gthyabtqog.html

C#:   (end - start).TotalSeconds
来源：http://dali.cheryme.top/Article/details/gttomwrwdr.html

[J07] 比较两个日期
来源：http://dali.daxiang520.top/Article/details/gtdezxylyo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gtmjoejiwo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhengqikj.top/Article/details/gtbgtcyaid.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gthoofdlie.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gtlxktvnll.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yangfankeji.com/Article/details/gttwrkcvxp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.316326.xyz/Article/details/gtolzrumjj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gtxzxhlolm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gtzlziapvj.html

[J08] 提取年月日与星期
来源：http://dali.birdmap.top/Article/details/gtandrxrkb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yueranfly.top/Article/details/gtuqsgbmkn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.daxiang520.top/Article/details/gtlwkosraf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinghuilouyu.cn/Article/details/gtonrupdwt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.daria6918.cn/Article/details/gthbosinqm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.wangdashe.top/Article/details/gtpcdifiob.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xuetiantiany.cn/Article/details/gtxtvgcmqd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinqigufen.top/Article/details/gtkgbtscxl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gzhubu.top/Article/details/gtlxwjmlbt.html

[J09] 时区处理
来源：http://dali.daxiang520.top/Article/details/gthiwiisfs.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.havefunace.top/Article/details/gtwgvrndjd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dashuyun.cn/Article/details/gtcjyrpwvp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yongpay.top/Article/details/gtrjohxuxk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gtquwkouak.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.snrcjt.cn/Article/details/gthpzrekqx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jianghu66.top/Article/details/gtjwwyszvr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.daria6918.cn/Article/details/gtovmqoirn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.feifeiyinyue.top/Article/details/gtmnkutunj.html

[J10] 取今天 / 本月第一天
来源：http://dali.shanyushiyangtech.top/Article/details/gthmjtpxuz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.bjfxy.top/Article/details/gtuvtsolnd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.c1oappe.top/Article/details/gtnqjirgtl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daria6918.cn/Article/details/gtdnqwkgks.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmoyadlub.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zdqjudy.top/Article/details/gtrsbpizkv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.andypj.xyz/Article/details/gtmxiuecdd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gotoacloud.top/Article/details/gthvqjcgxd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hammf.cn/Article/details/gtnjwlchxa.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtltuwbxoa.html

K. JSON 与序列化
来源：http://dali.nwbrower.top/Article/details/gttxdzejrg.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtyhaugmjt.html

[K01] 对象转 JSON 字符串
来源：http://dali.jianghu66.top/Article/details/gtldqpxoog.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gzhubu.top/Article/details/gtqwaqhhjt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtindcanst.html

JS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gtygxqjmok.html

TS:   JSON.stringify(obj)
来源：http://dali.fzhhl.top/Article/details/gtffejscoe.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhongyouzk.top/Article/details/gttujqwntu.html

Go:   json.Marshal(obj)
来源：http://dali.fengsongda.top/Article/details/gtpvsfkrjs.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.wangshuangyany.cn/Article/details/gthobrsuju.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtwcxuyjec.html

[K02] JSON 字符串转对象
来源：http://dali.jqgfzy.top/Article/details/gtnnqiwbpk.html

Py:   json.loads(s)
来源：http://dali.tianlin.xyz/Article/details/gtzhefkqzh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jqgufenzy.top/Article/details/gtfbihupcr.html

JS:   JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkcmsvakj.html

TS:   JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gtygaqhbvg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shzxlz.cn/Article/details/gtpvbaswca.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gtvipnhagt.html

Ruby: JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gtmtqtoesp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.dianchejie.cn/Article/details/gtrbzmpvup.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ivvv.top/Article/details/gtmzmahirr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jianghu66.top/Article/details/gtijupmfwl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.bjfxy.top/Article/details/gtvvvmzpzl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tanke756.top/Article/details/gtmrhdwatr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gtpswoagej.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.haohaochexian.top/Article/details/gtsertvmxk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.snrcjt.cn/Article/details/gtciyxbnyw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.c1oappe.top/Article/details/gtqwhhmqvz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gotoacloud.top/Article/details/gtmupuqsgm.html

[K04] 读取 JSON 文件
来源：http://dali.tian-w.cn/Article/details/gthqrwkkig.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigufen.top/Article/details/gtcookxjri.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.dashuyun.cn/Article/details/gtfbcsgway.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gttuzbgyau.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gtxamngmrf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gtqyzotpxw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gtkchywcqe.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufnaxahq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.haohaochexian.top/Article/details/gtrcjateht.html

[K05] 深拷贝对象
来源：http://dali.cashguo.top/Article/details/gtackxxtsl.html

Py:   copy.deepcopy(obj)
来源：http://dali.iojbl.cn/Article/details/gtqohhmgeg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cashguo.top/Article/details/gtwdmqsewh.html

JS:   structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gtibqotuwt.html

TS:   structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gtgvgbsifw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zdqjudy.top/Article/details/gtqdqmskhq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jyoumei.cn/Article/details/gtksbdauyb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuanzx.com/Article/details/gtviwclucn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.smart0.xyz/Article/details/gtfmxtniey.html

[K06] 解析 URL 查询串
来源：http://dali.mhx1999.top/Article/details/gtmsudfrme.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenlongwang.top/Article/details/gtidzarjha.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hywenlv.cn/Article/details/gtkappypuq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gtehocqxlc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gtkqspqpoj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ppjwa.cn/Article/details/gtydjzmjxb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gtdnlovech.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gtgomslmzp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gtguxokafs.html

[K07] 进制转换
来源：http://dali.yanxiufei.cn/Article/details/gtizljakzn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj202588.top/Article/details/gthumuwfwn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.9152youxi.cn/Article/details/gtlxetxuki.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtbtbmkgzb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtgsuebwjp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtnaaytlkr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ivvv.top/Article/details/gtflgjkgan.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xinyue.icu/Article/details/gtucctfrha.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtxkmoietn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shuidangran.top/Article/details/gtlvbhzolg.html

Py:   pickle.dumps(obj)
来源：http://dali.sysykeji.top/Article/details/gtofklxgxe.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.guowangkeji.top/Article/details/gtqesjovqr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj202588.top/Article/details/gtwrfdziut.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cucudq.cn/Article/details/gtdcatbvbx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.aizwys.cn/Article/details/gtlkghuyhn.html

Go:   encoding/gob
来源：http://dali.chenjidiqi.icu/Article/details/gtawsugixk.html

Ruby: Marshal.dump(obj)
来源：http://dali.xuanzx.com/Article/details/gtbbbzwhba.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zdqjudy.top/Article/details/gtpvogoxcg.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtusfzfvzx.html

L. 网络请求
来源：http://dali.gotoacloud.top/Article/details/gtigmjbdxu.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtmxijcino.html

[L01] 发送 GET 请求
来源：http://dali.cheryme.top/Article/details/gtwhatjucj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jiagoushi.top/Article/details/gtcjwocspl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sufxvd.cn/Article/details/gtsghvgycf.html

JS:   await fetch(url)
来源：http://dali.chenzaomai.com/Article/details/gtynmwdckc.html

TS:   await fetch(url)
来源：http://dali.sysykeji.top/Article/details/gtfleyugyi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sxryk.cn/Article/details/gtyzrspmpx.html

Go:   resp, err := http.Get(url)
来源：http://dali.yongpay.top/Article/details/gtmcnvzkqx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xziqi.cn/Article/details/gtclfekmwp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nanxuanxn.top/Article/details/gtnepagooq.html

[L02] 发送 POST JSON
来源：http://dali.svipenyu.cn/Article/details/gtmfgixzaz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.guowangkeji.top/Article/details/gthqgjrbyg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zdqjudy.top/Article/details/gtvhjhhprp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gtbzimtcup.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuetiantiany.cn/Article/details/gtvsdyemgb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jqgufenzy.top/Article/details/gthmvxxvqv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.0kj1m.cn/Article/details/gtarhvnizt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.quarkkingdee.top/Article/details/gteuptijge.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.wangshuangyany.cn/Article/details/gtilzblvmn.html

[L03] 设置自定义请求头
来源：http://dali.yangfankeji.com/Article/details/gtrskeuohp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sysykeji.top/Article/details/gtdyejyphy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenzaomai.com/Article/details/gtcsvautyz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sxryk.cn/Article/details/gtwesbtihn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gtrsdrjjwt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sufxvd.cn/Article/details/gtgzdlybpv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gtdgpohcvn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zycfv.cn/Article/details/gtcezebnjb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gtawqcarwt.html

[L04] 设置超时
来源：http://dali.daxiang520.top/Article/details/gtuqzpismv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.wangshuangyany.cn/Article/details/gtrttngeag.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sweek.top/Article/details/gtovruwkgn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sxryk.cn/Article/details/gtgitxakeg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhongyouzk.top/Article/details/gtncogrxsz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hnxiangtu.top/Article/details/gtpyktmpzz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.smart0.xyz/Article/details/gtsvdkbsou.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqvycejzr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.mhx1999.top/Article/details/gtksqugvqv.html

[L05] 上传文件（multipart）
来源：http://dali.hnqzz.top/Article/details/gtjljyexce.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hfpthk.cn/Article/details/gtadrnzyvv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.svipenyu.cn/Article/details/gtnfzwieqj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jianghu66.top/Article/details/gtqysdiihr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdhymqur.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.daria6918.cn/Article/details/gtjtlbvuez.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jiagoushi.top/Article/details/gturswvins.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.guannengcc.top/Article/details/gtqsbpoilo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtkivnrxhe.html

[L06] 解析响应为 JSON
来源：http://dali.cucudq.cn/Article/details/gtndcrjtfo.html

Py:   resp.json()
来源：http://dali.aibaodan.cn/Article/details/gtexkcmyaf.html

PHP:  json_decode($body, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqszgnra.html

JS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gtuzzudgrm.html

TS:   await resp.json()
来源：http://dali.yuxming.cn/Article/details/gtbbnkxjls.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoutahwxm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hnxiangtu.top/Article/details/gtsegvcift.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hysaishi.cn/Article/details/gtakyctnsn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ivvv.top/Article/details/gtdjecpsks.html

[L07] 处理 HTTP 状态码
来源：http://dali.shzxlz.cn/Article/details/gtcvxqwgky.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yuxming.cn/Article/details/gtgbzuaadt.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xylfe.cn/Article/details/gtejzedrma.html

JS:   resp.ok;  resp.status
来源：http://dali.316326.xyz/Article/details/gttshyuvvd.html

TS:   resp.ok;  resp.status
来源：http://dali.gaohongyu789.top/Article/details/gtxjfsdlzm.html

Java: resp.statusCode()
来源：http://dali.yueranfly.top/Article/details/gtpbifuvke.html

Go:   resp.StatusCode
来源：http://dali.redwolf501.top/Article/details/gttshxtsdu.html

Ruby: resp.code.to_i
来源：http://dali.wangdashe.top/Article/details/gtwjnegzrs.html

C#:   (int)resp.StatusCode
来源：http://dali.shzxlz.cn/Article/details/gtcbrllgxp.html

[L08] 并发请求多个地址
来源：http://dali.meibo888.top/Article/details/gtzkcrvjls.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxinkj.top/Article/details/gtfcnbnxfw.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gtdskcxliy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gtvunfepvu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.havefunace.top/Article/details/gtmslivapb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jqgfzy.top/Article/details/gtakfftszm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.feifeiyinyue.top/Article/details/gtdqrbunqt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gtvmpiyrib.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.svipenyu.cn/Article/details/gtyfqiocus.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtifeejhyb.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhaomingkeji.xyz/Article/details/gtinsuzmjl.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtclwhndlh.html

[M01] 读取命令行参数
来源：http://dali.haohaochexian.top/Article/details/gtrwwgnlkm.html

Py:   sys.argv[1:]
来源：http://dali.yj20258888.top/Article/details/gtqtitnjai.html

PHP:  $argv;  $argc;
来源：http://dali.jinqigufen.top/Article/details/gtrvcgsakb.html

JS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gtzxlkgqjm.html

TS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gtjzqzflex.html

Java: args 数组（main 方法参数）
来源：http://dali.sweek.top/Article/details/gtpdjxdkdw.html

Go:   os.Args[1:]
来源：http://dali.birdmap.top/Article/details/gtdunkxfdx.html

Ruby: ARGV
来源：http://dali.cheryme.top/Article/details/gtinrrtpzo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gtbywzhfgb.html

[M02] 读取环境变量
来源：http://dali.cheryme.top/Article/details/gtjuwuwwtd.html

Py:   os.environ.get("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtaluzhxzx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gtcqllkyfg.html

JS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gtoqptablq.html

TS:   process.env.HOME
来源：http://dali.yj20258.top/Article/details/gtuddkszce.html

Java: System.getenv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtepxndcrs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtedkevmot.html

Ruby: ENV["HOME"]
来源：http://dali.feifeiyinyue.top/Article/details/gtfpgbvxtl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtzjkxjtri.html

[M03] 执行外部命令
来源：http://dali.snrcjt.cn/Article/details/gturjyfvha.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gotoacloud.top/Article/details/gtogitdoko.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shanyushiyangtech.top/Article/details/gtfuqrkhxs.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gotoacloud.top/Article/details/gtejyeyyez.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gtqnmnvess.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jianghu66.top/Article/details/gtctylmbez.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenzaomai.com/Article/details/gtstmsqajy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.daria6918.cn/Article/details/gtpnljamoo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.c1oappe.top/Article/details/gteyjlnzwx.html

[M04] 获取当前工作目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvssrhsts.html

Py:   os.getcwd()
来源：http://dali.zhiwuduotai.top/Article/details/gthwwefonw.html

PHP:  getcwd();
来源：http://dali.zycfv.cn/Article/details/gtmlslooky.html

JS:   process.cwd()
来源：http://dali.yj20258.top/Article/details/gtnquowivt.html

TS:   process.cwd()
来源：http://dali.zhixingplan.top/Article/details/gtlrfpkkfg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xziqi.cn/Article/details/gtiygoijgw.html

Go:   os.Getwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtktsckbao.html

Ruby: Dir.pwd
来源：http://dali.haohaochexian.top/Article/details/gtuzmmhids.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgfzy.top/Article/details/gtgwcewams.html

[M05] 设置退出码
来源：http://dali.aizwys.cn/Article/details/gtxytsojzd.html

Py:   sys.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gttiayqzhm.html

PHP:  exit(1);
来源：http://dali.wangshuangyany.cn/Article/details/gtvaghrhlt.html

JS:   process.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtuopdltms.html

TS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gthgyyttox.html

Java: System.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtznwhrlua.html

Go:   os.Exit(1)
来源：http://dali.snrcjt.cn/Article/details/gttkpabsmh.html

Ruby: exit 1
来源：http://dali.hongshengwenyu.top/Article/details/gtpcnnhewt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nwbrower.top/Article/details/gtgtcfalmm.html

[M06] 向标准错误输出
来源：http://dali.meibo888.top/Article/details/gtsujffpbh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hammf.cn/Article/details/gtnwvahvll.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tanke756.top/Article/details/gtjoolfqet.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gtsvcrfmju.html

TS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtafexechd.html

Java: System.err.println("err")
来源：http://dali.dashuyun.cn/Article/details/gtsisebjoj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.iojbl.cn/Article/details/gtvydkjqkl.html

Ruby: warn "err"
来源：http://dali.guannengcc.top/Article/details/gtfpzhhrkm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.kuanghao11.cn/Article/details/gtkihfqcgc.html

[M07] 判断是否为主入口
来源：http://dali.daria6918.cn/Article/details/gtexkvpwvs.html

Py:   if __name__ == "__main__":
来源：http://dali.yanxiufei.cn/Article/details/gtxskowwup.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jiagoushi.top/Article/details/gtupogejrf.html

JS:   require.main === module
来源：http://dali.dianchejie.cn/Article/details/gtcpojqxpq.html

TS:   require.main === module
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjxolirn.html

Java: public static void main(String[] args)
来源：http://dali.smart0.xyz/Article/details/gtansuttwr.html

Go:   func main()
来源：http://dali.dashuyun.cn/Article/details/gtaixfgayl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jqgufenzy.top/Article/details/gtdfghxnon.html

C#:   static void Main(string[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gtunefpavu.html

[M08] 获取系统与运行时信息
来源：http://dali.yueranfly.top/Article/details/gtmstpisrp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinghuilouyu.cn/Article/details/gtwzffblew.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tianlin.xyz/Article/details/gtcfvbjpyf.html

JS:   process.platform;  process.version
来源：http://dali.yj20258888.top/Article/details/gtqptzztlg.html

TS:   process.platform;  process.version
来源：http://dali.shanyushiyangtech.top/Article/details/gtixxkrixb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jlsjyb.cn/Article/details/gtaucyqgri.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.pengpengdd.cyou/Article/details/gtywodhiny.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jlsjyb.cn/Article/details/gtjcxlwpic.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj20258.top/Article/details/gtlrwtqxit.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtmemlzzbf.html

N. 数据结构与算法
来源：http://dali.cqqwz.cn/Article/details/gtufpnjfkz.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtbhcfextj.html

[N01] 二分查找（有序数组）
来源：http://dali.yj20258.top/Article/details/gtflqaorek.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtdxnqyolq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nanxinkj.top/Article/details/gthftnbnob.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtfgfpqpsc.html


<!-- 参考信息 -->