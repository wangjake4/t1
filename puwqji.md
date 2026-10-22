代发 wailian999

TS:   new Date("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtxvaxhtwk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gthmvhyaom.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtomzibrwq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtnyaheqpn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jqgufenzy.top/Article/details/gtvgwjnnmo.html

[J04] 时间戳与日期互转
来源：http://dali.haohaochexian.top/Article/details/gtixvqncoi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.c1oappe.top/Article/details/gtctqyshaq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xylfe.cn/Article/details/gtexbvhfuu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigfzy.top/Article/details/gtgvfmzsjk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.guannengcc.top/Article/details/gtdvvanaey.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gzhubu.top/Article/details/gttwplsfgj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtjrsdnloq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daxiang520.top/Article/details/gtzmnqbblk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tianlin.xyz/Article/details/gtkypuxssb.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhiwuduotai.top/Article/details/gtvwbcsheu.html

Py:   now + timedelta(days=7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdkglugv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hnqzz.top/Article/details/gtvxjkvimc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gtfrgmcuwz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shzxlz.cn/Article/details/gtsrywckyv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tianlin.xyz/Article/details/gtzqqsculv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hfpthk.cn/Article/details/gtozmvuuav.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yuanzhike.top/Article/details/gtkfmxqggs.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ehwqpu.com/Article/details/gtuyujohuz.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwijyciz.html

Py:   (end - start).total_seconds()
来源：http://dali.xuetiantiany.cn/Article/details/gtyawnpptn.html

PHP:  $end->diff($start)->days;
来源：http://dali.aibaodan.cn/Article/details/gtyledxcoe.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daxiang520.top/Article/details/gtphnedvxs.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gaohongyu789.top/Article/details/gtojrrgyol.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.smart0.xyz/Article/details/gtygbcwewr.html

Go:   end.Sub(start).Hours()
来源：http://dali.nanxinkj.top/Article/details/gtmfkjevns.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gogol.net.cn/Article/details/gtiuoquuon.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258888.top/Article/details/gtdsamcqyh.html

[J07] 比较两个日期
来源：http://dali.dashuyun.cn/Article/details/gtypmpqdvd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gtafwctekj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.fzhhl.top/Article/details/gtttwkhyot.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gtjndcyxfa.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.birdmap.top/Article/details/gtyulxmbad.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sysykeji.top/Article/details/gtlfeqshma.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cdnleiting.top/Article/details/gtztuwvlya.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gtvezdudec.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gtgrqlmmpu.html

[J08] 提取年月日与星期
来源：http://dali.nanxinkj.top/Article/details/gtnhmiohmo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xylfe.cn/Article/details/gtvxnvlwib.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.iojbl.cn/Article/details/gtwvpdcksk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.smart0.xyz/Article/details/gtbbehqvdl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.0kj1m.cn/Article/details/gtssfxvnwb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj20258.top/Article/details/gtibngjmbb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgfzy.top/Article/details/gtceblcque.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtarlmxngh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cdnleiting.top/Article/details/gtljmiycek.html

[J09] 时区处理
来源：http://dali.andypj.xyz/Article/details/gtzrjawebt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xziqi.cn/Article/details/gttaarwftt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yueranfly.top/Article/details/gtkppslctw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ppjwa.cn/Article/details/gtjbiwgsvt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gtjpasexck.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cashguo.top/Article/details/gtvgjcnzhg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.meibo888.top/Article/details/gtjpswmmjd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfdhbrsto.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hammf.cn/Article/details/gtvhykglfw.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhapbcjl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cdnleiting.top/Article/details/gtiktnijsi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sxryk.cn/Article/details/gttifobbkg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aizwys.cn/Article/details/gtqwsahrwq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.bjfxy.top/Article/details/gttfyfbygu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ppjwa.cn/Article/details/gtymvgoduz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xziqi.cn/Article/details/gtsaxpqmle.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cheryme.top/Article/details/gtolewotzz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.bjfxy.top/Article/details/gtobetcccx.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtvbkdcapk.html

K. JSON 与序列化
来源：http://dali.wangdashe.top/Article/details/gtslrfudte.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtjgwvvpuy.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtoypynewz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gtqzgpblck.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gtldpwmlyt.html

JS:   JSON.stringify(obj)
来源：http://dali.guannengcc.top/Article/details/gtaeyihxzn.html

TS:   JSON.stringify(obj)
来源：http://dali.yvedp.cn/Article/details/gtdgzroeld.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cheryme.top/Article/details/gtrvjcdcag.html

Go:   json.Marshal(obj)
来源：http://dali.hnqzz.top/Article/details/gtpfsshqav.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cheryme.top/Article/details/gtnppdvesg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtopmmanqw.html

[K02] JSON 字符串转对象
来源：http://dali.xuanzx.com/Article/details/gtjdayxjng.html

Py:   json.loads(s)
来源：http://dali.chenzaomai.com/Article/details/gtotmrjqwj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cucudq.cn/Article/details/gtpjnutwsn.html

JS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gtdxdnyhjr.html

TS:   JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gthxryxxxo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ivvv.top/Article/details/gtwxxflmjr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gtgfrzpsan.html

Ruby: JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gtcgngjgwv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fzhhl.top/Article/details/gtkjfujpau.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cheryme.top/Article/details/gthxnstftc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jyoumei.cn/Article/details/gtvelmkrei.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ydzc1.top/Article/details/gtzriyqiom.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuanzx.com/Article/details/gtgujkxhnh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cucudq.cn/Article/details/gtvrnmzdfh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhixingplan.top/Article/details/gtqtjcvpqi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.daxiang520.top/Article/details/gtgatyhvjq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtyuvfoepj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinghuilouyu.cn/Article/details/gtvghiymle.html

[K04] 读取 JSON 文件
来源：http://dali.zhiwuduotai.top/Article/details/gteeoxekgi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhoulong.xyz/Article/details/gtfnhsszfb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hnxiangtu.top/Article/details/gtskdyripj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gtsrnxwxom.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gtjdzswvse.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hywenlv.cn/Article/details/gtjlehkewo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.c1oappe.top/Article/details/gtvamfrgfk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwnjuvik.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tanke756.top/Article/details/gtjxyfcabo.html

[K05] 深拷贝对象
来源：http://dali.tanke756.top/Article/details/gtmtbpbgqe.html

Py:   copy.deepcopy(obj)
来源：http://dali.pycfn.com/Article/details/gttmxplede.html

PHP:  unserialize(serialize($obj));
来源：http://dali.quarkkingdee.top/Article/details/gtnpqzeyeg.html

JS:   structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gtcocxigte.html

TS:   structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gtioiftoeq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhoulong.xyz/Article/details/gtbkzedija.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yvedp.cn/Article/details/gtnlmpqznk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yonumen.top/Article/details/gtjtqeznvl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zycfv.cn/Article/details/gtjqejssou.html

[K06] 解析 URL 查询串
来源：http://dali.aibaodan.cn/Article/details/gtosotwoop.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzlsgbnq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.iojbl.cn/Article/details/gtfnnwcrli.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gtyuxendov.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ybcxt.top/Article/details/gtgcmmunir.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cdnleiting.top/Article/details/gttqripcsc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gtjusmnwdw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gtbkcwtuel.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmdulajw.html

[K07] 进制转换
来源：http://dali.yj20258888.top/Article/details/gtuxrqubii.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtaafmakzm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.daxiang520.top/Article/details/gtfyehigcl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtcuwknpji.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gthcdhohhd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtjvhzruyj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuetiantiany.cn/Article/details/gthmcdplbu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yuanzhike.top/Article/details/gtqqwdxnzn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtajrwedqz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sysykeji.top/Article/details/gtftewppaz.html

Py:   pickle.dumps(obj)
来源：http://dali.hywenlv.cn/Article/details/gtawxvrrfv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cashguo.top/Article/details/gtualmgqxa.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.meibo888.top/Article/details/gtbakhcmds.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtidxwsmih.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuanzx.com/Article/details/gtwckbxyfx.html

Go:   encoding/gob
来源：http://dali.zhixingplan.top/Article/details/gtqirdhczo.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj20258888.top/Article/details/gtjexxtmpj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nanxinkj.top/Article/details/gtlzxnzhqe.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtldmjzyga.html

L. 网络请求
来源：http://dali.yanxiufei.cn/Article/details/gthybcvqsz.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtzboolmyn.html

[L01] 发送 GET 请求
来源：http://dali.daria6918.cn/Article/details/gtzhddxlmm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yonumen.top/Article/details/gtdcondnes.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yuanzhike.top/Article/details/gtiqkmbvhu.html

JS:   await fetch(url)
来源：http://dali.iojbl.cn/Article/details/gtpekecwzs.html

TS:   await fetch(url)
来源：http://dali.ehwqpu.com/Article/details/gtfscvrqdv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinyuanbaomall.cn/Article/details/gthkzisqnf.html

Go:   resp, err := http.Get(url)
来源：http://dali.daxiang520.top/Article/details/gthqgazdfh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yonumen.top/Article/details/gtnrwpohax.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ppjwa.cn/Article/details/gtfqmstjjl.html

[L02] 发送 POST JSON
来源：http://dali.ehwqpu.com/Article/details/gtkikiyrrb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuanzx.com/Article/details/gtaerthwrq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ehwqpu.com/Article/details/gttyvpbidq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gaohongyu789.top/Article/details/gtwdvtxktc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gtrbwmdqbo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jianghu66.top/Article/details/gtzpkljjqz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shanyushiyangtech.top/Article/details/gtlwkbsvtk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ivvv.top/Article/details/gtkcdamabd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ybcxt.top/Article/details/gtaampjjou.html

[L03] 设置自定义请求头
来源：http://dali.guannengcc.top/Article/details/gtrwplktli.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zycfv.cn/Article/details/gtvzkwwojd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shzxlz.cn/Article/details/gtluiqfuzj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gtadmedavs.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gtnrrvwjin.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yanxiufei.cn/Article/details/gtsacebxsk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gtwssntxht.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yuxming.cn/Article/details/gtdjewxsiq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gthqmkxrvj.html

[L04] 设置超时
来源：http://dali.jinqigufen.top/Article/details/gtvaqphexr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.iojbl.cn/Article/details/gtwvypxwrk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenlongwang.top/Article/details/gtqlncvmvg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.feifeiyinyue.top/Article/details/gtvjtiqsyf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aibaodan.cn/Article/details/gtnvjdmhjc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dashuyun.cn/Article/details/gtarvkcvim.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cdnleiting.top/Article/details/gtnqmrkauc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yangfankeji.com/Article/details/gtijoryakd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hongshengwenyu.top/Article/details/gtbkaecpbg.html

[L05] 上传文件（multipart）
来源：http://dali.zhengqikj.top/Article/details/gtismixdql.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.aizwys.cn/Article/details/gtalmrsptp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tanke756.top/Article/details/gtnxtplxth.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gttbpbpssk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gtxdfjwfip.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ybcxt.top/Article/details/gtrlcubjvc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nwbrower.top/Article/details/gtcbwzzpfk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tian-w.cn/Article/details/gtfcddbotb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daria6918.cn/Article/details/gtuvkfyeez.html

[L06] 解析响应为 JSON
来源：http://dali.daria6918.cn/Article/details/gtduwqzjur.html

Py:   resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gtawpgfirx.html

PHP:  json_decode($body, true);
来源：http://dali.andypj.xyz/Article/details/gttoyqbevp.html

JS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gttgsaazbe.html

TS:   await resp.json()
来源：http://dali.jinqigufen.top/Article/details/gtemiuzyuc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zdqjudy.top/Article/details/gtyzhtdlxj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.bjfxy.top/Article/details/gtkhwebwrq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvoynofs.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jianghu66.top/Article/details/gtksweaetd.html

[L07] 处理 HTTP 状态码
来源：http://dali.jyoumei.cn/Article/details/gthxyrdikn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhiwuduotai.top/Article/details/gtwyqbbchn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hongshengwenyu.top/Article/details/gtcrlbqxye.html

JS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gtjzfucpmf.html

TS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gtmgoscgtb.html

Java: resp.statusCode()
来源：http://dali.andypj.xyz/Article/details/gtmxiyzphu.html

Go:   resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gtsiibfnlb.html

Ruby: resp.code.to_i
来源：http://dali.kuanghao11.cn/Article/details/gtjiwzeeus.html

C#:   (int)resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gtejqkubrn.html

[L08] 并发请求多个地址
来源：http://dali.jinqigufen.top/Article/details/gthzneurfh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258888.top/Article/details/gtweevchpo.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinqigfzy.top/Article/details/gtafecfgdw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aibaodan.cn/Article/details/gtrgxxoyhw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gtjsqzzwzk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cashguo.top/Article/details/gtqkxibulx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.9152youxi.cn/Article/details/gtfncmobdi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnqzz.top/Article/details/gtyucsqqfa.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtwhqryeda.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtpgamwbkt.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenjidiqi.icu/Article/details/gtmzsdlsza.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtvzyngvet.html

[M01] 读取命令行参数
来源：http://dali.c1oappe.top/Article/details/gtwvhmhuqh.html

Py:   sys.argv[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtlmjzbqgi.html

PHP:  $argv;  $argc;
来源：http://dali.hywenlv.cn/Article/details/gtnltwkjfa.html

JS:   process.argv.slice(2)
来源：http://dali.hnxiangtu.top/Article/details/gtankvnysw.html

TS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gtcvabwxzl.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gtazihmmtz.html

Go:   os.Args[1:]
来源：http://dali.jinqigufen.top/Article/details/gtkeuronco.html

Ruby: ARGV
来源：http://dali.yvedp.cn/Article/details/gtythmkxhg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jqgufenzy.top/Article/details/gtfkltunra.html

[M02] 读取环境变量
来源：http://dali.hnqzz.top/Article/details/gtoxmzpsxn.html

Py:   os.environ.get("HOME")
来源：http://dali.hammf.cn/Article/details/gtwgzbfmtq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yueranfly.top/Article/details/gtgobtyvfv.html

JS:   process.env.HOME
来源：http://dali.jiagoushi.top/Article/details/gtscxpsmns.html

TS:   process.env.HOME
来源：http://dali.havefunace.top/Article/details/gtwwduwmto.html

Java: System.getenv("HOME")
来源：http://dali.yuxming.cn/Article/details/gttijkhods.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmwfwwxkn.html

Ruby: ENV["HOME"]
来源：http://dali.andypj.xyz/Article/details/gtsvcwhjay.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtidubfsap.html

[M03] 执行外部命令
来源：http://dali.pengpengdd.cyou/Article/details/gtbkoukuyc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sufxvd.cn/Article/details/gtuvofqxvh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hnqzz.top/Article/details/gtrpklormh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhongyouzk.top/Article/details/gtgfybajrm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtwehsgzlz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tanke756.top/Article/details/gtdueykfmw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hysaishi.cn/Article/details/gtlplwbuxm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ppjwa.cn/Article/details/gtnhuaxlnc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hnqzz.top/Article/details/gtkilitofi.html

[M04] 获取当前工作目录
来源：http://dali.aizwys.cn/Article/details/gtixhgnwth.html

Py:   os.getcwd()
来源：http://dali.guowangkeji.top/Article/details/gtdnkeryem.html

PHP:  getcwd();
来源：http://dali.fzhhl.top/Article/details/gtvjbemait.html

JS:   process.cwd()
来源：http://dali.hammf.cn/Article/details/gtnbmtyomc.html

TS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gtewwnznyo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yueranfly.top/Article/details/gtbdovewyk.html

Go:   os.Getwd()
来源：http://dali.ydzc1.top/Article/details/gtmigisktj.html

Ruby: Dir.pwd
来源：http://dali.yueranfly.top/Article/details/gtuvrkibaf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj20258888.top/Article/details/gtrktpqzpw.html

[M05] 设置退出码
来源：http://dali.aizwys.cn/Article/details/gtmfnzxqxq.html

Py:   sys.exit(1)
来源：http://dali.iojbl.cn/Article/details/gtnreyboqr.html

PHP:  exit(1);
来源：http://dali.meibo888.top/Article/details/gtqilfhzvj.html

JS:   process.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gthjhyhvtr.html

TS:   process.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gttbrwgjmf.html

Java: System.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtwuupixct.html

Go:   os.Exit(1)
来源：http://dali.yueranfly.top/Article/details/gtuwxlqsib.html

Ruby: exit 1
来源：http://dali.xuanzx.com/Article/details/gthbmhurid.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.316326.xyz/Article/details/gtorfyziky.html

[M06] 向标准错误输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyolrjdks.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cdnleiting.top/Article/details/gtrtmcrjhi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hnqzz.top/Article/details/gtfqyyoqzp.html

JS:   console.error("err")
来源：http://dali.9152youxi.cn/Article/details/gtwuceyqwp.html

TS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gthyiadrbo.html

Java: System.err.println("err")
来源：http://dali.yuxming.cn/Article/details/gtcelpgwpq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.meibo888.top/Article/details/gtxphfphqc.html

Ruby: warn "err"
来源：http://dali.hnxiangtu.top/Article/details/gtputldvsk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.guowangkeji.top/Article/details/gtnlucefvq.html

[M07] 判断是否为主入口
来源：http://dali.dianchejie.cn/Article/details/gtfzeuiesp.html

Py:   if __name__ == "__main__":
来源：http://dali.shzxlz.cn/Article/details/gtipjwdstj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zdqjudy.top/Article/details/gtdvmclrqa.html

JS:   require.main === module
来源：http://dali.cheryme.top/Article/details/gtjglnjzdw.html

TS:   require.main === module
来源：http://dali.redwolf501.top/Article/details/gtwoyhuven.html

Java: public static void main(String[] args)
来源：http://dali.fzhhl.top/Article/details/gthrunysej.html

Go:   func main()
来源：http://dali.316326.xyz/Article/details/gtmfvodobi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.bjfxy.top/Article/details/gtmzdikaty.html

C#:   static void Main(string[] args)
来源：http://dali.bjfxy.top/Article/details/gtcaszuxyu.html

[M08] 获取系统与运行时信息
来源：http://dali.hammf.cn/Article/details/gtjdhgotvl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.c1oappe.top/Article/details/gtfnsswemr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhongyouzk.top/Article/details/gtdwjepblv.html

JS:   process.platform;  process.version
来源：http://dali.cheryme.top/Article/details/gtgdbxcopu.html

TS:   process.platform;  process.version
来源：http://dali.zhongyouzk.top/Article/details/gtjssqdwfy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbibxwezf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.haohaochexian.top/Article/details/gteuzugfqy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.kuanghao11.cn/Article/details/gtcfgguvoq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.0kj1m.cn/Article/details/gttzeoqlgx.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtctlqgddj.html

N. 数据结构与算法
来源：http://dali.havefunace.top/Article/details/gtmlopjjse.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtfkbtvgdi.html

[N01] 二分查找（有序数组）
来源：http://dali.chenlongwang.top/Article/details/gtoissfrvy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtezqinmsv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nanxinkj.top/Article/details/gtcppogqpf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yangfankeji.com/Article/details/gtauwxmnyi.html


<!-- 参考信息 -->