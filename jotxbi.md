代发 wailian999

[J03] 字符串解析为日期
来源：http://dali.hfpthk.cn/Article/details/gtsobiqnxg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.quarkkingdee.top/Article/details/gtwogzhnpt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ybcxt.top/Article/details/gtfnqzazrc.html

JS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gttqzoikit.html

TS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtrhlfluuw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtclfcrtqf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtfeenqzpq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtlebwuedu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hysaishi.cn/Article/details/gtcumbtxlv.html

[J04] 时间戳与日期互转
来源：http://dali.yanxiufei.cn/Article/details/gtrwrenugr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xinyue.icu/Article/details/gtuterhzvm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdgqdimb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shuidangran.top/Article/details/gtxpeugtxj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.wangdashe.top/Article/details/gtbokoyxmi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sufxvd.cn/Article/details/gtnkqrnvwf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hfpthk.cn/Article/details/gtpmwrauau.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tanke756.top/Article/details/gtolpjszyf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.fzhhl.top/Article/details/gtkaikdabr.html

[J05] 时间加减（加 7 天）
来源：http://dali.hysaishi.cn/Article/details/gtkfucgqpr.html

Py:   now + timedelta(days=7)
来源：http://dali.daria6918.cn/Article/details/gtlwevsuoi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jlsjyb.cn/Article/details/gtutyverev.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenjidiqi.icu/Article/details/gtxgdlxjhs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gtdoujhtre.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinqigufen.top/Article/details/gtfbvklpqd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.vqdsnc.cn/Article/details/gthnjflxax.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ydzc1.top/Article/details/gtrkwxqype.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhiwuduotai.top/Article/details/gtdhwkwubw.html

[J06] 计算两时间之差
来源：http://dali.ybcxt.top/Article/details/gtfbkafbuu.html

Py:   (end - start).total_seconds()
来源：http://dali.daxiang520.top/Article/details/gttasquvwo.html

PHP:  $end->diff($start)->days;
来源：http://dali.aibaodan.cn/Article/details/gtotasijxa.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhixingplan.top/Article/details/gtdxwljbzg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.aibaodan.cn/Article/details/gtrgagvpqw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsblfafbp.html

Go:   end.Sub(start).Hours()
来源：http://dali.aibaodan.cn/Article/details/gtpecslayi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sysykeji.top/Article/details/gtxpbnxmpb.html

C#:   (end - start).TotalSeconds
来源：http://dali.jianghu66.top/Article/details/gtdbdhjnpv.html

[J07] 比较两个日期
来源：http://dali.dianchejie.cn/Article/details/gtwgajibps.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gtyvernbwd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shanyushiyangtech.top/Article/details/gtccztzspl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gogol.net.cn/Article/details/gtmdcglbfx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gthybmisdm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.snrcjt.cn/Article/details/gtlovtwcgq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnqzz.top/Article/details/gtqcdpcsih.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gtomkaxhrk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gtrnjpfftx.html

[J08] 提取年月日与星期
来源：http://dali.hywenlv.cn/Article/details/gtilxlxorb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.feifeiyinyue.top/Article/details/gtzlybvtft.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnxiangtu.top/Article/details/gtlklqnieh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jlsjyb.cn/Article/details/gtvtdvpgse.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yuanzhike.top/Article/details/gtlbpcqmxi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtszbrtwvm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yonumen.top/Article/details/gttemqailn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sufxvd.cn/Article/details/gtetwktulf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xylfe.cn/Article/details/gtzsydsczj.html

[J09] 时区处理
来源：http://dali.zdqjudy.top/Article/details/gtycoxmosk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.kuanghao11.cn/Article/details/gtxyvjfgee.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangtech.top/Article/details/gtmkxfeqdr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gtptmnfubs.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gtdttxhrxj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hnqzz.top/Article/details/gtpfvzhmof.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258888.top/Article/details/gtnbehmjwn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.smart0.xyz/Article/details/gtznnoibmn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tanke756.top/Article/details/gtltujjkmc.html

[J10] 取今天 / 本月第一天
来源：http://dali.ywan-chungtsiang.top/Article/details/gtodotvlie.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gotoacloud.top/Article/details/gtgjhljfxw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cucudq.cn/Article/details/gtsiitujgd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtouksseyg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shuidangran.top/Article/details/gtdshmkoyj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.havefunace.top/Article/details/gtrxkfrjjz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhixingplan.top/Article/details/gtwoferfpk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhoulong.xyz/Article/details/gtsiookeov.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gogol.net.cn/Article/details/gtnvgporsc.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtoigxvcsa.html

K. JSON 与序列化
来源：http://dali.0kj1m.cn/Article/details/gtqhcuhjli.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtmyvwgelx.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtrzefkdgg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gtrylocbqu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhengqikj.top/Article/details/gtdymuqcfe.html

JS:   JSON.stringify(obj)
来源：http://dali.guowangkeji.top/Article/details/gtuqfmwvxn.html

TS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gteeajvvtl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gzhubu.top/Article/details/gtggxzoqnb.html

Go:   json.Marshal(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtrdnenekn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.dianchejie.cn/Article/details/gtqyuovcbj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.smart0.xyz/Article/details/gtygmqfaif.html

[K02] JSON 字符串转对象
来源：http://dali.chenzaomai.com/Article/details/gtznoixbjg.html

Py:   json.loads(s)
来源：http://dali.ydzc1.top/Article/details/gtvnshztnu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nanxinkj.top/Article/details/gtofnpuffp.html

JS:   JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gttwhwdval.html

TS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gtamwslhtm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj202588.top/Article/details/gtpuqnjrik.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.mhx1999.top/Article/details/gtvevvgmjx.html

Ruby: JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtghafbifj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sysykeji.top/Article/details/gtralrxoax.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.guowangkeji.top/Article/details/gtttnqfteq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jyoumei.cn/Article/details/gtzcshslqm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.c1oappe.top/Article/details/gtycjiyqvj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zdqjudy.top/Article/details/gtgsejsgse.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.dashuyun.cn/Article/details/gtulrseosn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hywenlv.cn/Article/details/gtacplktft.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangdashe.top/Article/details/gtfylaslis.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xinyue.icu/Article/details/gtqtmuwlic.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.316326.xyz/Article/details/gtzztioqae.html

[K04] 读取 JSON 文件
来源：http://dali.bjfxy.top/Article/details/gtfcugpdmo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xinyue.icu/Article/details/gtjshofcth.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shuidangran.top/Article/details/gtnjfkranq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yonumen.top/Article/details/gtrsaycqtd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gtsmqsffdh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gtsetkvwyf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gtsufoevbz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yvedp.cn/Article/details/gtoljebqoh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhixingplan.top/Article/details/gtpmpddrxn.html

[K05] 深拷贝对象
来源：http://dali.ppjwa.cn/Article/details/gtnbubmhah.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gteqspeweh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xinyue.icu/Article/details/gtxolkvezm.html

JS:   structuredClone(obj)
来源：http://dali.sysykeji.top/Article/details/gtdrrqetqs.html

TS:   structuredClone(obj)
来源：http://dali.yongpay.top/Article/details/gtfkhgvdou.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmdapchhi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yuanzhike.top/Article/details/gtzeeffocx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tian-w.cn/Article/details/gtcupwkfsz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.redwolf501.top/Article/details/gtrayqboqp.html

[K06] 解析 URL 查询串
来源：http://dali.0kj1m.cn/Article/details/gtxqqgkhqq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.0kj1m.cn/Article/details/gtbktftkko.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xinyue.icu/Article/details/gtywogdybf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gtqflsjpue.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbfcwgal.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nanxinkj.top/Article/details/gtvcjfwsgw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gtkrirvyhf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtuyfnocge.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtobmfrfom.html

[K07] 进制转换
来源：http://dali.hongshengwenyu.top/Article/details/gtolpqwaqk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtiqrthtkx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj20258.top/Article/details/gtkousjrgo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtirjzbdka.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtiwirpdzo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gttzvhsukp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yonumen.top/Article/details/gtfmrxillx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.vqdsnc.cn/Article/details/gtdctpizbd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtgivpswkr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.quarkkingdee.top/Article/details/gtcrkdfyja.html

Py:   pickle.dumps(obj)
来源：http://dali.tanke756.top/Article/details/gtwhaizxth.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zdqjudy.top/Article/details/gtyvpodcrl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenjidiqi.icu/Article/details/gtbaoscaao.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gtbcqqanct.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.aibaodan.cn/Article/details/gtcwrqgaok.html

Go:   encoding/gob
来源：http://dali.shanyushiyangtech.top/Article/details/gtjsyhfnoq.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenlongwang.top/Article/details/gtxnebxoxd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xinyue.icu/Article/details/gttiluimlx.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtxtbcmars.html

L. 网络请求
来源：http://dali.daria6918.cn/Article/details/gtstqgoxsx.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtbzvnawof.html

[L01] 发送 GET 请求
来源：http://dali.jinqigufen.top/Article/details/gtjbdyhrrd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jqgufenzy.top/Article/details/gtypkxfjcv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.vqdsnc.cn/Article/details/gtxaokcbxv.html

JS:   await fetch(url)
来源：http://dali.iojbl.cn/Article/details/gtsotuyjhv.html

TS:   await fetch(url)
来源：http://dali.gaohongyu789.top/Article/details/gtaxgynlfk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.aibaodan.cn/Article/details/gtyoejxvpc.html

Go:   resp, err := http.Get(url)
来源：http://dali.cdnleiting.top/Article/details/gtpkplibzb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxniprfnm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sweek.top/Article/details/gtbyayjizg.html

[L02] 发送 POST JSON
来源：http://dali.yj202588.top/Article/details/gtzegnptic.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.kuanghao11.cn/Article/details/gtxyxrefvz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.316326.xyz/Article/details/gtzmxflphb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gogol.net.cn/Article/details/gthmyyarqx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daxiang520.top/Article/details/gtnekgzvpn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xylfe.cn/Article/details/gtjqpizsuw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj202588.top/Article/details/gtwbvfjcir.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xuanzx.com/Article/details/gtkyzpgibs.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.nanxinkj.top/Article/details/gtdunrhqrw.html

[L03] 设置自定义请求头
来源：http://dali.sxryk.cn/Article/details/gtdbwvxfhw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hysaishi.cn/Article/details/gtvgewzwex.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.fzhhl.top/Article/details/gtatjhilnv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.redwolf501.top/Article/details/gtgzacgtjv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fzhhl.top/Article/details/gtwdcbtcir.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gaohongyu789.top/Article/details/gttnwfgklj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhixingplan.top/Article/details/gthgeplfln.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xuetiantiany.cn/Article/details/gtzqdtsoyt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinghuilouyu.cn/Article/details/gteakmglwq.html

[L04] 设置超时
来源：http://dali.haohaochexian.top/Article/details/gtzoqnnxll.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nanxuanxn.top/Article/details/gteqagumxf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nanxinkj.top/Article/details/gtqzffbxns.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxinkj.top/Article/details/gthogpdffv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tianlin.xyz/Article/details/gtsphdygwa.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwbpwywp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj20258888.top/Article/details/gtllylxyuf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyahrexfs.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhongyouzk.top/Article/details/gtgrihvvhv.html

[L05] 上传文件（multipart）
来源：http://dali.jinghuilouyu.cn/Article/details/gtkgjjtbcv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jianghu66.top/Article/details/gtxpkjlfsi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xylfe.cn/Article/details/gtibvtyayz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gttxbdippi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258.top/Article/details/gtzcvqmzdl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwykdalj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.havefunace.top/Article/details/gtlkvxjpsq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hnqzz.top/Article/details/gtlktoaqxc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gthrtwvqef.html

[L06] 解析响应为 JSON
来源：http://dali.sufxvd.cn/Article/details/gtdrtqpenw.html

Py:   resp.json()
来源：http://dali.tianlin.xyz/Article/details/gtzijjbims.html

PHP:  json_decode($body, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtdeqqtxhq.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gtceridlwb.html

TS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gtmqtresgl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnqzz.top/Article/details/gtlakwjbuq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.dashuyun.cn/Article/details/gtxvltfyso.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hammf.cn/Article/details/gtlxuvjumd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhengqikj.top/Article/details/gtlhkxgakq.html

[L07] 处理 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gtiwrhweav.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ybcxt.top/Article/details/gtqzoltkeb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yanxiufei.cn/Article/details/gtozggewnn.html

JS:   resp.ok;  resp.status
来源：http://dali.dianchejie.cn/Article/details/gtgsaxnzpm.html

TS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gtjwhbxmbc.html

Java: resp.statusCode()
来源：http://dali.jinqigfzy.top/Article/details/gteeahlenr.html

Go:   resp.StatusCode
来源：http://dali.ivvv.top/Article/details/gtazfpkwuc.html

Ruby: resp.code.to_i
来源：http://dali.yj20258.top/Article/details/gtumxmvdmy.html

C#:   (int)resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gthnjtsfwe.html

[L08] 并发请求多个地址
来源：http://dali.xylfe.cn/Article/details/gtcgapzmma.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yuanzhike.top/Article/details/gtfaqghgls.html

PHP:  curl_multi_init() 系列
来源：http://dali.sxryk.cn/Article/details/gtgffmahyd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtcvsvdhco.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gtmjezjfbv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.0kj1m.cn/Article/details/gtwvkhaitx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigufen.top/Article/details/gtrzfzkwmi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj202588.top/Article/details/gttqimpddt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtuddfniet.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtraitxoeg.html

M. 命令行 / 进程 / 环境
来源：http://dali.dianchejie.cn/Article/details/gtxcskktvo.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtjfcvveze.html

[M01] 读取命令行参数
来源：http://dali.aibaodan.cn/Article/details/gtuzbmhleu.html

Py:   sys.argv[1:]
来源：http://dali.fzhhl.top/Article/details/gthmyfelnd.html

PHP:  $argv;  $argc;
来源：http://dali.xuetiantiany.cn/Article/details/gtggsycwme.html

JS:   process.argv.slice(2)
来源：http://dali.svipenyu.cn/Article/details/gtrwfyrodm.html

TS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gtwkcryerq.html

Java: args 数组（main 方法参数）
来源：http://dali.yvedp.cn/Article/details/gtckspkjzq.html

Go:   os.Args[1:]
来源：http://dali.nanxinkj.top/Article/details/gtdkypgvxe.html

Ruby: ARGV
来源：http://dali.sufxvd.cn/Article/details/gtqaldpyhr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gtdzvttmcx.html

[M02] 读取环境变量
来源：http://dali.xziqi.cn/Article/details/gtfiadpnmr.html

Py:   os.environ.get("HOME")
来源：http://dali.tanke756.top/Article/details/gtbcwkmcmq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.guowangkeji.top/Article/details/gtssrrcvko.html

JS:   process.env.HOME
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoshufrvn.html

TS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gtjdwifapi.html

Java: System.getenv("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttjsnymen.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtctpjbmis.html

Ruby: ENV["HOME"]
来源：http://dali.zhengqikj.top/Article/details/gtjooelgwu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yonumen.top/Article/details/gtyvmsoyif.html

[M03] 执行外部命令
来源：http://dali.xuanzx.com/Article/details/gtauputytz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jlsjyb.cn/Article/details/gtjqcezbtk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hywenlv.cn/Article/details/gtljhbrvnd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnqzz.top/Article/details/gtfllzxdry.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hywenlv.cn/Article/details/gtwxkyoftl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cashguo.top/Article/details/gtdvejuuhr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.mhx1999.top/Article/details/gtyfdglqer.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hnqzz.top/Article/details/gtcibgypej.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenlongwang.top/Article/details/gtajnzrynn.html

[M04] 获取当前工作目录
来源：http://dali.daria6918.cn/Article/details/gtnbxcbipo.html

Py:   os.getcwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtgocbedhh.html

PHP:  getcwd();
来源：http://dali.daxiang520.top/Article/details/gthswouajx.html

JS:   process.cwd()
来源：http://dali.ivvv.top/Article/details/gtspmcqjce.html

TS:   process.cwd()
来源：http://dali.yongpay.top/Article/details/gtwbmxtbyh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.dianchejie.cn/Article/details/gtqdmkudvi.html

Go:   os.Getwd()
来源：http://dali.gogol.net.cn/Article/details/gtliciixgf.html

Ruby: Dir.pwd
来源：http://dali.wangdashe.top/Article/details/gtlgkkgdao.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hysaishi.cn/Article/details/gtrhnoksif.html

[M05] 设置退出码
来源：http://dali.daria6918.cn/Article/details/gtivhhmpqw.html

Py:   sys.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtqvvbighq.html

PHP:  exit(1);
来源：http://dali.gaohongyu789.top/Article/details/gtisfrjoug.html

JS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtcujxueen.html

TS:   process.exit(1)
来源：http://dali.iojbl.cn/Article/details/gtedpugcfw.html

Java: System.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtlnwesvnp.html

Go:   os.Exit(1)
来源：http://dali.shuidangran.top/Article/details/gtkqyvhxto.html

Ruby: exit 1
来源：http://dali.jinqigfzy.top/Article/details/gtikjvkakr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.pengpengdd.cyou/Article/details/gtbrqecdpz.html

[M06] 向标准错误输出
来源：http://dali.zycfv.cn/Article/details/gtsnqcpapl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.quarkkingdee.top/Article/details/gtypawguov.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.quarkkingdee.top/Article/details/gtckiyxlvc.html

JS:   console.error("err")
来源：http://dali.vqdsnc.cn/Article/details/gtpsdjemkn.html

TS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gtvlonprgf.html

Java: System.err.println("err")
来源：http://dali.yanxiufei.cn/Article/details/gtieuuotgj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangdashe.top/Article/details/gtmaoepfhz.html

Ruby: warn "err"
来源：http://dali.yueranfly.top/Article/details/gttruncnyd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gotoacloud.top/Article/details/gtqqhtltjd.html

[M07] 判断是否为主入口
来源：http://dali.zhixingplan.top/Article/details/gteyktbhsh.html

Py:   if __name__ == "__main__":
来源：http://dali.kuanghao11.cn/Article/details/gtebexpydf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj20258888.top/Article/details/gtparzlwmt.html

JS:   require.main === module
来源：http://dali.fzhhl.top/Article/details/gthynuhpvi.html

TS:   require.main === module
来源：http://dali.xinyue.icu/Article/details/gtsfspbbvn.html

Java: public static void main(String[] args)
来源：http://dali.ydzc1.top/Article/details/gtxyudelda.html

Go:   func main()
来源：http://dali.316326.xyz/Article/details/gtbrupayqo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhixingplan.top/Article/details/gtijufajsj.html

C#:   static void Main(string[] args)
来源：http://dali.gogol.net.cn/Article/details/gtypbqfblj.html

[M08] 获取系统与运行时信息
来源：http://dali.sxryk.cn/Article/details/gtjcnuehyo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hnxiangtu.top/Article/details/gtnnxslkxd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhoulong.xyz/Article/details/gtojpnjmnv.html

JS:   process.platform;  process.version
来源：http://dali.hfpthk.cn/Article/details/gtnlgztuxh.html

TS:   process.platform;  process.version
来源：http://dali.sufxvd.cn/Article/details/gtxpeuupjm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xziqi.cn/Article/details/gtrrsrxxyb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yanxiufei.cn/Article/details/gtwfhnraqx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.havefunace.top/Article/details/gtngapsuqd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ppjwa.cn/Article/details/gtdxxyracg.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtpiuxrzzp.html

N. 数据结构与算法
来源：http://dali.cdnleiting.top/Article/details/gtnjxgpcwx.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtfcjlokyc.html


<!-- 参考信息 -->