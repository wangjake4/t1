代发 wailian999

[J03] 字符串解析为日期
来源：http://dali.hfpthk.cn/Article/details/gtrwohaknf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhoulong.xyz/Article/details/gtnszmbxus.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xziqi.cn/Article/details/gthnnssodm.html

JS:   new Date("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtnoqnmvcc.html

TS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtmzmgphpz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtdiyiprfn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtjkwommep.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtqmcaccai.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jyoumei.cn/Article/details/gtfwhbyqom.html

[J04] 时间戳与日期互转
来源：http://dali.guowangkeji.top/Article/details/gtfeydchep.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gttfytvkoo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gaohongyu789.top/Article/details/gtuwvioobs.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgukyjmoo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuanzx.com/Article/details/gtsnnmdrfy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.aizwys.cn/Article/details/gtqfulkvco.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ybcxt.top/Article/details/gtwkwyjnjr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sufxvd.cn/Article/details/gtvijoavfe.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenlongwang.top/Article/details/gtfjdlycoo.html

[J05] 时间加减（加 7 天）
来源：http://dali.redwolf501.top/Article/details/gtscxvibin.html

Py:   now + timedelta(days=7)
来源：http://dali.quarkkingdee.top/Article/details/gtjprqwcsd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.dianchejie.cn/Article/details/gthsgdabpi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gtgqhkgskn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgufenzy.top/Article/details/gtjqynjttd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gzhubu.top/Article/details/gthuzuwlhf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ivvv.top/Article/details/gtyixelzii.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nanxuanxn.top/Article/details/gtofgjpoio.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xinyue.icu/Article/details/gtpedwfxmh.html

[J06] 计算两时间之差
来源：http://dali.ehwqpu.com/Article/details/gtuwzsoxrc.html

Py:   (end - start).total_seconds()
来源：http://dali.jyoumei.cn/Article/details/gtncfoaotj.html

PHP:  $end->diff($start)->days;
来源：http://dali.cdnleiting.top/Article/details/gtvxrvxdbq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jianghu66.top/Article/details/gtcqxnpkwz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yuxming.cn/Article/details/gtvpdhetqv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xylfe.cn/Article/details/gthjyuigze.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj20258888.top/Article/details/gtrefymruc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpurmejsl.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhoulong.xyz/Article/details/gtkrxphibb.html

[J07] 比较两个日期
来源：http://dali.hysaishi.cn/Article/details/gtpfrwccom.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gtyqalrtqo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ehwqpu.com/Article/details/gtsvobryuv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsulmmtpv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.feifeiyinyue.top/Article/details/gtbyzgqpoe.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgidljcby.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yanxiufei.cn/Article/details/gttolkazpq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gtwjmcudnd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtbwnazwck.html

[J08] 提取年月日与星期
来源：http://dali.yj20258.top/Article/details/gtsgkhxlds.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ivvv.top/Article/details/gtprzveauh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jiagoushi.top/Article/details/gtalxsgxmk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinghuilouyu.cn/Article/details/gtaowjwwbh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yonumen.top/Article/details/gtnseinjpy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xuanzx.com/Article/details/gtwugcllda.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigufen.top/Article/details/gtxcunzlwx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenzaomai.com/Article/details/gtxykzingg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hongshengwenyu.top/Article/details/gtzffctltk.html

[J09] 时区处理
来源：http://dali.shuidangran.top/Article/details/gtvidbadwl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yongpay.top/Article/details/gtslgraxfv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hongshengwenyu.top/Article/details/gtuikhmsbb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gtuupvzkus.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfheetapx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jyoumei.cn/Article/details/gtomvnbjtq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.havefunace.top/Article/details/gtnxdsbvcv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.birdmap.top/Article/details/gtlukflasq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cucudq.cn/Article/details/gtpqummhsj.html

[J10] 取今天 / 本月第一天
来源：http://dali.pengpengdd.cyou/Article/details/gtvvqspxog.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.guowangkeji.top/Article/details/gtzadpxjmz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzldrguzt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hammf.cn/Article/details/gtkkwajezw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258888.top/Article/details/gttytodjwq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtjxbpilgj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shzxlz.cn/Article/details/gtaeuqjnkv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ehwqpu.com/Article/details/gtpbtpcxmi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinqigufen.top/Article/details/gtghftsxvt.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtguzjelpm.html

K. JSON 与序列化
来源：http://dali.havefunace.top/Article/details/gtikzzqinl.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtvibwfkyq.html

[K01] 对象转 JSON 字符串
来源：http://dali.hammf.cn/Article/details/gttanijfxd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.guowangkeji.top/Article/details/gtxigimslp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gtncjrgtas.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gtqeuzgeod.html

TS:   JSON.stringify(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtcpwvpksy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gaohongyu789.top/Article/details/gtvwrykpts.html

Go:   json.Marshal(obj)
来源：http://dali.ybcxt.top/Article/details/gtlbbvhllz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shuidangran.top/Article/details/gtogdpugof.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guannengcc.top/Article/details/gtfqccapuo.html

[K02] JSON 字符串转对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiuyrtjtt.html

Py:   json.loads(s)
来源：http://dali.ehwqpu.com/Article/details/gtooysjuye.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfddbrbhc.html

JS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtgoctfsvq.html

TS:   JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtydwrfvjy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gtrzynxdax.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gtklreuuaw.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gtzakbgwsi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cdnleiting.top/Article/details/gtptszwnxn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.quarkkingdee.top/Article/details/gtyoygnocr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xinyue.icu/Article/details/gtcnbkkofq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.316326.xyz/Article/details/gttcxpghzl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.pycfn.com/Article/details/gteuwkpyad.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuxming.cn/Article/details/gthfuxgmlz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zycfv.cn/Article/details/gtytdvjazc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ybcxt.top/Article/details/gttaepnhfk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuanzhike.top/Article/details/gtttefapsr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xziqi.cn/Article/details/gtxshbibab.html

[K04] 读取 JSON 文件
来源：http://dali.yj202588.top/Article/details/gteqddlokh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.haohaochexian.top/Article/details/gtbfwhilec.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.daria6918.cn/Article/details/gtlljmksff.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnqzz.top/Article/details/gtpsvpdkfg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gttpsulops.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xylfe.cn/Article/details/gtgwhaelde.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yvedp.cn/Article/details/gtgjdzuoyw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daria6918.cn/Article/details/gthgvivwtm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gtduimfley.html

[K05] 深拷贝对象
来源：http://dali.zhixingplan.top/Article/details/gteamrcqnh.html

Py:   copy.deepcopy(obj)
来源：http://dali.sweek.top/Article/details/gtvzowypwk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangshuangyany.cn/Article/details/gtjffirmyz.html

JS:   structuredClone(obj)
来源：http://dali.yangfankeji.com/Article/details/gtfrlhbvrf.html

TS:   structuredClone(obj)
来源：http://dali.yongpay.top/Article/details/gtoilrhqgq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yonumen.top/Article/details/gtocjqkzvw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hywenlv.cn/Article/details/gtmmurvsnb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenlongwang.top/Article/details/gtbirzfddn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.wangshuangyany.cn/Article/details/gtefiixppl.html

[K06] 解析 URL 查询串
来源：http://dali.sxryk.cn/Article/details/gtfzhqyamn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtravzxsqn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xziqi.cn/Article/details/gtkekvvceo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gtxndbywsa.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gtdgacwfzt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.svipenyu.cn/Article/details/gttiyjstue.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gtxhcjrodq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gtiqjeshxz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gttufwwots.html

[K07] 进制转换
来源：http://dali.pycfn.com/Article/details/gtonzzvlqd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtizwzwjnx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnqzz.top/Article/details/gtrojijgba.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtgpqzxfom.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtfxpetcko.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtdjhxibms.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nanxuanxn.top/Article/details/gtmionvzmk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xinyue.icu/Article/details/gtuatzkbox.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gthtaqgwmc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jqgufenzy.top/Article/details/gtfikucgoa.html

Py:   pickle.dumps(obj)
来源：http://dali.cashguo.top/Article/details/gtxhokcpgz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ydzc1.top/Article/details/gtmkpthmam.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhengqikj.top/Article/details/gtabzohbwt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhengqikj.top/Article/details/gtifhdmezk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cqqwz.cn/Article/details/gtzgqdzmza.html

Go:   encoding/gob
来源：http://dali.nanxinkj.top/Article/details/gtrzczalyr.html

Ruby: Marshal.dump(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptkbrbgw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinqigfzy.top/Article/details/gtkmhdihwl.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtrqsqpyut.html

L. 网络请求
来源：http://dali.jiagoushi.top/Article/details/gtryrsimnq.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtxqaggqaf.html

[L01] 发送 GET 请求
来源：http://dali.chenzaomai.com/Article/details/gtbgrkhjgd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tanke756.top/Article/details/gtppihaihx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.aibaodan.cn/Article/details/gtclmtnkzp.html

JS:   await fetch(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcooruama.html

TS:   await fetch(url)
来源：http://dali.sysykeji.top/Article/details/gtntlumalo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhengqikj.top/Article/details/gtddetktji.html

Go:   resp, err := http.Get(url)
来源：http://dali.hammf.cn/Article/details/gtlcxqwljc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yangfankeji.com/Article/details/gtgvmzcezq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tianlin.xyz/Article/details/gtglqeiwzk.html

[L02] 发送 POST JSON
来源：http://dali.gogol.net.cn/Article/details/gtczxhkhlf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.0kj1m.cn/Article/details/gtyggfsccf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.quarkkingdee.top/Article/details/gtkqtvbuxs.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.meibo888.top/Article/details/gtjrgquenm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hammf.cn/Article/details/gtpvzdppjv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenzaomai.com/Article/details/gtbkkxrxdj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nanxuanxn.top/Article/details/gtzuxekwdm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.svipenyu.cn/Article/details/gtkbopdghe.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.bjfxy.top/Article/details/gtqhszakyj.html

[L03] 设置自定义请求头
来源：http://dali.sweek.top/Article/details/gtciavxbdi.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shzxlz.cn/Article/details/gthubpnaiy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.kuanghao11.cn/Article/details/gtpaiqtowz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gtxrpszmtx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gtqvyzrqzw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.0kj1m.cn/Article/details/gtalsljdeq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ivvv.top/Article/details/gtfjjszdbb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yangfankeji.com/Article/details/gtrghqotxb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.havefunace.top/Article/details/gtrehninod.html

[L04] 设置超时
来源：http://dali.tian-w.cn/Article/details/gtmwnajgfi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.svipenyu.cn/Article/details/gtofbdvzds.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yongpay.top/Article/details/gtohhdanmi.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenlongwang.top/Article/details/gtsggcjpmn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fengsongda.top/Article/details/gtqctcreip.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cqqwz.cn/Article/details/gtidjucrge.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xziqi.cn/Article/details/gtofawyixl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xylfe.cn/Article/details/gtsltiumqj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdcaxyut.html

[L05] 上传文件（multipart）
来源：http://dali.pycfn.com/Article/details/gtnmyjnbaq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.svipenyu.cn/Article/details/gtpzdhokvv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gzhubu.top/Article/details/gttvifzokz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjuunejho.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gtsfhvzris.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sufxvd.cn/Article/details/gtpsasgxha.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jiagoushi.top/Article/details/gtflbhfpqx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xziqi.cn/Article/details/gthuphvnvu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtnfgiknfm.html

[L06] 解析响应为 JSON
来源：http://dali.yvedp.cn/Article/details/gtwdnkfdeu.html

Py:   resp.json()
来源：http://dali.jianghu66.top/Article/details/gtrqhbiujs.html

PHP:  json_decode($body, true);
来源：http://dali.c1oappe.top/Article/details/gtqikqfpeg.html

JS:   await resp.json()
来源：http://dali.zdqjudy.top/Article/details/gtghichkel.html

TS:   await resp.json()
来源：http://dali.yj20258.top/Article/details/gtquclhbir.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gtwworlvhd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenlongwang.top/Article/details/gtzwfhnach.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shuidangran.top/Article/details/gtkerlcfxc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xuetiantiany.cn/Article/details/gtlwkwelsw.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gtqjndtfgj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.meibo888.top/Article/details/gtnsjencbe.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ydzc1.top/Article/details/gtcoywcshs.html

JS:   resp.ok;  resp.status
来源：http://dali.daria6918.cn/Article/details/gtddtlwoni.html

TS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gtagmindrv.html

Java: resp.statusCode()
来源：http://dali.pycfn.com/Article/details/gtqswzlpds.html

Go:   resp.StatusCode
来源：http://dali.fengsongda.top/Article/details/gtvhonimdq.html

Ruby: resp.code.to_i
来源：http://dali.xuanzx.com/Article/details/gtirtiyayz.html

C#:   (int)resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gtqtrkswid.html

[L08] 并发请求多个地址
来源：http://dali.yonumen.top/Article/details/gtepiyoalm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.aizwys.cn/Article/details/gtaqbzujzy.html

PHP:  curl_multi_init() 系列
来源：http://dali.shangyingyoupin.top/Article/details/gtkktjjyct.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gtujnaoonq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gtejjmgven.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.haohaochexian.top/Article/details/gthzspokxj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.redwolf501.top/Article/details/gtmclfhvct.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hywenlv.cn/Article/details/gtcewkrdgj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gogol.net.cn/Article/details/gtnjiehhqb.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gttbsmckji.html

M. 命令行 / 进程 / 环境
来源：http://dali.c1oappe.top/Article/details/gtwgggnxrv.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gthqgvnmzl.html

[M01] 读取命令行参数
来源：http://dali.hfpthk.cn/Article/details/gtybacisad.html

Py:   sys.argv[1:]
来源：http://dali.guannengcc.top/Article/details/gtvznjgrlc.html

PHP:  $argv;  $argc;
来源：http://dali.nwbrower.top/Article/details/gtmdptweci.html

JS:   process.argv.slice(2)
来源：http://dali.hysaishi.cn/Article/details/gtdwrqbgtv.html

TS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gtocibmjnj.html

Java: args 数组（main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gtltecyqms.html

Go:   os.Args[1:]
来源：http://dali.nanxinkj.top/Article/details/gtfjllgcde.html

Ruby: ARGV
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwvafrhe.html

C#:   args 数组（Main 方法参数）
来源：http://dali.havefunace.top/Article/details/gtvzupwmho.html

[M02] 读取环境变量
来源：http://dali.zycfv.cn/Article/details/gtcjmkzuma.html

Py:   os.environ.get("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtmkjsfzwd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gtiknviksd.html

JS:   process.env.HOME
来源：http://dali.gogol.net.cn/Article/details/gtruglsajd.html

TS:   process.env.HOME
来源：http://dali.jiagoushi.top/Article/details/gtxydqoiex.html

Java: System.getenv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gthozlnrsf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yongpay.top/Article/details/gtlucrmbux.html

Ruby: ENV["HOME"]
来源：http://dali.xuetiantiany.cn/Article/details/gtyuzpkslj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yueranfly.top/Article/details/gtlgjruzzi.html

[M03] 执行外部命令
来源：http://dali.zhixingplan.top/Article/details/gtulwrkbpz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daxiang520.top/Article/details/gtirowbeoa.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.kuanghao11.cn/Article/details/gtsrhwurga.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.snrcjt.cn/Article/details/gttzzwfyxf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.vqdsnc.cn/Article/details/gtpcgutuul.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tianlin.xyz/Article/details/gttbckflbz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jianghu66.top/Article/details/gtfxiiujeq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cqqwz.cn/Article/details/gtvisvdbqd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.redwolf501.top/Article/details/gtpogxlawz.html

[M04] 获取当前工作目录
来源：http://dali.smart0.xyz/Article/details/gtarrueabf.html

Py:   os.getcwd()
来源：http://dali.dashuyun.cn/Article/details/gtvhfsqikr.html

PHP:  getcwd();
来源：http://dali.xziqi.cn/Article/details/gtqsudzats.html

JS:   process.cwd()
来源：http://dali.hammf.cn/Article/details/gtghhbcfzf.html

TS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtnzgdexlz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.aibaodan.cn/Article/details/gtuluhlewv.html

Go:   os.Getwd()
来源：http://dali.zhoulong.xyz/Article/details/gtrnuofkek.html

Ruby: Dir.pwd
来源：http://dali.c1oappe.top/Article/details/gtbdtxlpvi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.dashuyun.cn/Article/details/gtwewrflaw.html

[M05] 设置退出码
来源：http://dali.pycfn.com/Article/details/gtauxzsjkt.html

Py:   sys.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtqdfijauw.html

PHP:  exit(1);
来源：http://dali.aibaodan.cn/Article/details/gtzvwaxsiy.html

JS:   process.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtjsaxbxul.html

TS:   process.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtuzeuttkw.html

Java: System.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtrpjvvryq.html

Go:   os.Exit(1)
来源：http://dali.zhengqikj.top/Article/details/gttwzwqwqc.html

Ruby: exit 1
来源：http://dali.zhiwuduotai.top/Article/details/gtdpklxkaz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zdqjudy.top/Article/details/gtnkltokmq.html

[M06] 向标准错误输出
来源：http://dali.vqdsnc.cn/Article/details/gtfmpabwvl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenzaomai.com/Article/details/gtdglhxcke.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nanxuanxn.top/Article/details/gtdzewkbui.html

JS:   console.error("err")
来源：http://dali.yanxiufei.cn/Article/details/gtzfxhrylg.html

TS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gtbesakrpz.html

Java: System.err.println("err")
来源：http://dali.zhiwuduotai.top/Article/details/gthprvbtke.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nanxinkj.top/Article/details/gttlzpfkur.html

Ruby: warn "err"
来源：http://dali.wangdashe.top/Article/details/gtgahicvvo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fzhhl.top/Article/details/gtrdnrtrvy.html

[M07] 判断是否为主入口
来源：http://dali.nwbrower.top/Article/details/gtbjezddty.html

Py:   if __name__ == "__main__":
来源：http://dali.xuanzx.com/Article/details/gttixzirul.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sxryk.cn/Article/details/gtldboqper.html

JS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gtuhizhpnn.html

TS:   require.main === module
来源：http://dali.zhoulong.xyz/Article/details/gtocllracr.html

Java: public static void main(String[] args)
来源：http://dali.jiagoushi.top/Article/details/gtvgqvgodj.html

Go:   func main()
来源：http://dali.gotoacloud.top/Article/details/gtwmfgzmjf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.iojbl.cn/Article/details/gttpldjppf.html

C#:   static void Main(string[] args)
来源：http://dali.jlsjyb.cn/Article/details/gtjlfedolo.html

[M08] 获取系统与运行时信息
来源：http://dali.kuanghao11.cn/Article/details/gtjgijvssy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhiwuduotai.top/Article/details/gtrtwkpgid.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gaohongyu789.top/Article/details/gtzapaqspj.html

JS:   process.platform;  process.version
来源：http://dali.yj20258888.top/Article/details/gtuczmmzxr.html

TS:   process.platform;  process.version
来源：http://dali.hnxiangtu.top/Article/details/gtlsxanbjv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jianghu66.top/Article/details/gtzubrfbfe.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjcmgjed.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.9152youxi.cn/Article/details/gtghfnmgfq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cheryme.top/Article/details/gtnviszaxr.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtovehjnge.html

N. 数据结构与算法
来源：http://dali.vqdsnc.cn/Article/details/gtfxdwquta.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtgeoofdsx.html


<!-- 参考信息 -->