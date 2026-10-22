代发 wailian999

TS:   new Date("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtmamgigjb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtqpnxaeob.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtnwqygmhd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtjethcqlt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shuidangran.top/Article/details/gtjktixmdj.html

[J04] 时间戳与日期互转
来源：http://dali.gogol.net.cn/Article/details/gtizsxpgdt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nwbrower.top/Article/details/gtncghdxtk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.birdmap.top/Article/details/gtdrilfkik.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.redwolf501.top/Article/details/gtklehbqyb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.redwolf501.top/Article/details/gtngbjolax.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.aibaodan.cn/Article/details/gtquowykkq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.havefunace.top/Article/details/gtjkcoiptd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xziqi.cn/Article/details/gthbxozmdn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shuidangran.top/Article/details/gtvyrnvhan.html

[J05] 时间加减（加 7 天）
来源：http://dali.aizwys.cn/Article/details/gtzicizgxw.html

Py:   now + timedelta(days=7)
来源：http://dali.tian-w.cn/Article/details/gtsmplyeyo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yuxming.cn/Article/details/gtfmdchdkp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258888.top/Article/details/gtfmrkiycq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gtyqwyitwl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinqigufen.top/Article/details/gtbygeqbkz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dianchejie.cn/Article/details/gtgyexhwdn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zycfv.cn/Article/details/gtijbmkphy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgztfvkuc.html

[J06] 计算两时间之差
来源：http://dali.havefunace.top/Article/details/gtugscjchv.html

Py:   (end - start).total_seconds()
来源：http://dali.guowangkeji.top/Article/details/gtjrbthetn.html

PHP:  $end->diff($start)->days;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcoyvdfmd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqpuvdzg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.feifeiyinyue.top/Article/details/gtqutwicdv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sufxvd.cn/Article/details/gthjeoiwbf.html

Go:   end.Sub(start).Hours()
来源：http://dali.meibo888.top/Article/details/gtcwybigat.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ivvv.top/Article/details/gtggteidbf.html

C#:   (end - start).TotalSeconds
来源：http://dali.xziqi.cn/Article/details/gtndlldzww.html

[J07] 比较两个日期
来源：http://dali.cheryme.top/Article/details/gtqcxadkoj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gtcdlborgb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhengqikj.top/Article/details/gtkvpyctqf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuanzx.com/Article/details/gtoljmcdao.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gtijjrfjey.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhengqikj.top/Article/details/gtumxlbuoj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yanxiufei.cn/Article/details/gtryeekcbs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gtketpmjit.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtdjpzlmdr.html

[J08] 提取年月日与星期
来源：http://dali.ivvv.top/Article/details/gtjlzzkagy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tanke756.top/Article/details/gtfmlhvjvu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shangyingyoupin.top/Article/details/gtoyhzxdfm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.snrcjt.cn/Article/details/gtfjczgasd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hywenlv.cn/Article/details/gtjmggeebp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yueranfly.top/Article/details/gtooagwdae.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.wangdashe.top/Article/details/gtjmuotagi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.316326.xyz/Article/details/gtxlczyhzo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhengqikj.top/Article/details/gtmjyxgboh.html

[J09] 时区处理
来源：http://dali.snrcjt.cn/Article/details/gtajpvitvq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tanke756.top/Article/details/gtizhzvkcp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zdqjudy.top/Article/details/gtzmjfxwwf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258888.top/Article/details/gtrkgoilxs.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gtdarikxyw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.bjfxy.top/Article/details/gtaobxqxoi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.aizwys.cn/Article/details/gtwdnwhsgg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jyoumei.cn/Article/details/gtslazivan.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.andypj.xyz/Article/details/gtsbznrklf.html

[J10] 取今天 / 本月第一天
来源：http://dali.nanxinkj.top/Article/details/gtbpdmsiik.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sxryk.cn/Article/details/gtdkotwkzd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhiwuduotai.top/Article/details/gtvxgfzqgm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.svipenyu.cn/Article/details/gtxpwdzhye.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aizwys.cn/Article/details/gteikvboez.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hysaishi.cn/Article/details/gtxiocmzxh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxinkj.top/Article/details/gtdcwrztnt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.daxiang520.top/Article/details/gtlnkxiucm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ybcxt.top/Article/details/gticorernp.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gttqkopmoq.html

K. JSON 与序列化
来源：http://dali.daxiang520.top/Article/details/gtpaodfqqa.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gttoavildf.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenzaomai.com/Article/details/gtqgsrwnuu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shangyingyoupin.top/Article/details/gtdgdmrbfi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aibaodan.cn/Article/details/gtxarqsmuk.html

JS:   JSON.stringify(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtluldvlce.html

TS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gtykiydvbm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nanxuanxn.top/Article/details/gtubvqdsov.html

Go:   json.Marshal(obj)
来源：http://dali.9152youxi.cn/Article/details/gtrhdoaiax.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cashguo.top/Article/details/gtghavuehj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ivvv.top/Article/details/gtzwbzwouz.html

[K02] JSON 字符串转对象
来源：http://dali.yj202588.top/Article/details/gtcbxewpqd.html

Py:   json.loads(s)
来源：http://dali.gaohongyu789.top/Article/details/gtrxvzunsl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.bjfxy.top/Article/details/gtcknibkdq.html

JS:   JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gtpjsholiw.html

TS:   JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gtpbtbsure.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gtzusmruay.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hammf.cn/Article/details/gtqsssuxpn.html

Ruby: JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnsveixni.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sweek.top/Article/details/gtzabicdub.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sysykeji.top/Article/details/gtpdielpwq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gtwjcxanbh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gtzlkomgzd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangdashe.top/Article/details/gtrdorefqo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtjylzofrd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.dianchejie.cn/Article/details/gteinaivqn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.smart0.xyz/Article/details/gtgwogldlc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.aizwys.cn/Article/details/gtndneghol.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sufxvd.cn/Article/details/gtskdgapky.html

[K04] 读取 JSON 文件
来源：http://dali.ybcxt.top/Article/details/gtudgvkzwu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ehwqpu.com/Article/details/gtiryrffpx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.pengpengdd.cyou/Article/details/gtnegpuesc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aizwys.cn/Article/details/gtjrmxwbja.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnqzz.top/Article/details/gtwnlwxtws.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.bjfxy.top/Article/details/gtazgvxlqg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xuetiantiany.cn/Article/details/gtusatnzxm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdzkmhzh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gotoacloud.top/Article/details/gtqqybwulx.html

[K05] 深拷贝对象
来源：http://dali.cdnleiting.top/Article/details/gtvqvtztvb.html

Py:   copy.deepcopy(obj)
来源：http://dali.daxiang520.top/Article/details/gttydiucit.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ybcxt.top/Article/details/gtxsjolnji.html

JS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gtjwgvewix.html

TS:   structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gtjkwektel.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.pengpengdd.cyou/Article/details/gtxviafdws.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhongyouzk.top/Article/details/gtirigoxor.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.c1oappe.top/Article/details/gtezimfzpo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj202588.top/Article/details/gttynvjirs.html

[K06] 解析 URL 查询串
来源：http://dali.daria6918.cn/Article/details/gtealdxxae.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.c1oappe.top/Article/details/gtzbqivzgq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.quarkkingdee.top/Article/details/gtgzlzrvtw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gtlxxnvjik.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gtzdpwmnus.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cheryme.top/Article/details/gteieksekc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gtxsieqxvt.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gtkmcsonsh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gtwzrnsjov.html

[K07] 进制转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftyburgc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtuuowkhdo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxinkj.top/Article/details/gtoayohnjj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtzclooshf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtjulwcfbc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpnhllgnh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cashguo.top/Article/details/gtzpjdpeus.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yangfankeji.com/Article/details/gtupmrpbwa.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtbwvwscmn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jyoumei.cn/Article/details/gtohtiqqfx.html

Py:   pickle.dumps(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtkyoskvma.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.aizwys.cn/Article/details/gtlaogavqt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.0kj1m.cn/Article/details/gtjjopictz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xuanzx.com/Article/details/gtuzoqtvuj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zdqjudy.top/Article/details/gttpgdsbmx.html

Go:   encoding/gob
来源：http://dali.yj202588.top/Article/details/gtvufedfpx.html

Ruby: Marshal.dump(obj)
来源：http://dali.ivvv.top/Article/details/gtvfertuln.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.quarkkingdee.top/Article/details/gtgvxzezut.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtddurasdm.html

L. 网络请求
来源：http://dali.tian-w.cn/Article/details/gtyfnqaltq.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtgwdmifai.html

[L01] 发送 GET 请求
来源：http://dali.zhengqikj.top/Article/details/gtswhpzbxi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.316326.xyz/Article/details/gthvkzvroo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yueranfly.top/Article/details/gthbuzpwsj.html

JS:   await fetch(url)
来源：http://dali.svipenyu.cn/Article/details/gtivumlswi.html

TS:   await fetch(url)
来源：http://dali.sxryk.cn/Article/details/gtewgtbsmq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yangfankeji.com/Article/details/gtciejhbsm.html

Go:   resp, err := http.Get(url)
来源：http://dali.hfpthk.cn/Article/details/gtjibwnqyo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmgqzrlbl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.guowangkeji.top/Article/details/gtemyzcndg.html

[L02] 发送 POST JSON
来源：http://dali.xylfe.cn/Article/details/gtrpmulzxp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hongshengwenyu.top/Article/details/gtvqtnljyc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.aibaodan.cn/Article/details/gtgqxhvduj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hammf.cn/Article/details/gtxslidtzx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgufenzy.top/Article/details/gtoitjgklj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.redwolf501.top/Article/details/gthwwdgyas.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gogol.net.cn/Article/details/gtiarqbgxn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.fengsongda.top/Article/details/gtmsjmjedj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgfzy.top/Article/details/gteynkusup.html

[L03] 设置自定义请求头
来源：http://dali.cqqwz.cn/Article/details/gtuzxnmsgy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aizwys.cn/Article/details/gtffovibgq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.daria6918.cn/Article/details/gtbwaqtvnz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hongshengwenyu.top/Article/details/gtaquhcfgc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cucudq.cn/Article/details/gthxcgnyup.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sweek.top/Article/details/gtepcrbwrz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hammf.cn/Article/details/gtkezferou.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.birdmap.top/Article/details/gtbgxoalua.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cdnleiting.top/Article/details/gtihxmezca.html

[L04] 设置超时
来源：http://dali.kuanghao11.cn/Article/details/gtsnfqoewf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.birdmap.top/Article/details/gtyjppgejv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.0kj1m.cn/Article/details/gtbedqiuvl.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenzaomai.com/Article/details/gthcbzskcn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gtxnkohevw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.guannengcc.top/Article/details/gthybyutvn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.redwolf501.top/Article/details/gtrxlthrie.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hywenlv.cn/Article/details/gtlcdlvzll.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hfpthk.cn/Article/details/gtxltdznlm.html

[L05] 上传文件（multipart）
来源：http://dali.zhengqikj.top/Article/details/gtirqvyghm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjuzxyqi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.iojbl.cn/Article/details/gtaarajfwm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gtrcppbbly.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nwbrower.top/Article/details/gtwzrqnvyk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.daxiang520.top/Article/details/gtiidpmidx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jiagoushi.top/Article/details/gtdopcjyll.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.svipenyu.cn/Article/details/gtidtlqrfj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtjnmyvekd.html

[L06] 解析响应为 JSON
来源：http://dali.dianchejie.cn/Article/details/gtgadsjgyt.html

Py:   resp.json()
来源：http://dali.jiagoushi.top/Article/details/gttzgrlchk.html

PHP:  json_decode($body, true);
来源：http://dali.daria6918.cn/Article/details/gtpjhcfati.html

JS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtmugyvezh.html

TS:   await resp.json()
来源：http://dali.tian-w.cn/Article/details/gtnpnpuymy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ppjwa.cn/Article/details/gtcwapusfv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.316326.xyz/Article/details/gtbrknfjsi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.svipenyu.cn/Article/details/gtjlkponfm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dashuyun.cn/Article/details/gtywrgdusx.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenjidiqi.icu/Article/details/gtpswirxaw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.snrcjt.cn/Article/details/gtfwxtnhzd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tanke756.top/Article/details/gthlroovyd.html

JS:   resp.ok;  resp.status
来源：http://dali.nanxinkj.top/Article/details/gtjtorvjoj.html

TS:   resp.ok;  resp.status
来源：http://dali.jinqigufen.top/Article/details/gtmykxnjeg.html

Java: resp.statusCode()
来源：http://dali.hammf.cn/Article/details/gtifoewucp.html

Go:   resp.StatusCode
来源：http://dali.nwbrower.top/Article/details/gtxgwixsdj.html

Ruby: resp.code.to_i
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuyrnbbne.html

C#:   (int)resp.StatusCode
来源：http://dali.gzhubu.top/Article/details/gtxductekh.html

[L08] 并发请求多个地址
来源：http://dali.pycfn.com/Article/details/gtovedctuh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhiwuduotai.top/Article/details/gtwolekbyi.html

PHP:  curl_multi_init() 系列
来源：http://dali.birdmap.top/Article/details/gtiqfrxjqp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gtcbucihse.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gtqhzvpiqm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangshuangyany.cn/Article/details/gtbyjfikex.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jianghu66.top/Article/details/gtayjedzem.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrwjpbcy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxuanxn.top/Article/details/gtmcqbsoto.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtvvilgfro.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhiwuduotai.top/Article/details/gtmvxvpvvy.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtbaoshdhx.html

[M01] 读取命令行参数
来源：http://dali.cheryme.top/Article/details/gtvehbdedd.html

Py:   sys.argv[1:]
来源：http://dali.guannengcc.top/Article/details/gtthttrolj.html

PHP:  $argv;  $argc;
来源：http://dali.smart0.xyz/Article/details/gtvuxdlsve.html

JS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gtpiybbnoh.html

TS:   process.argv.slice(2)
来源：http://dali.sxryk.cn/Article/details/gtptlfdimy.html

Java: args 数组（main 方法参数）
来源：http://dali.gogol.net.cn/Article/details/gtgctgrfrk.html

Go:   os.Args[1:]
来源：http://dali.hysaishi.cn/Article/details/gtdwfxrmzl.html

Ruby: ARGV
来源：http://dali.quarkkingdee.top/Article/details/gtkiaynwrq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gtubaftvms.html

[M02] 读取环境变量
来源：http://dali.zhixingplan.top/Article/details/gtsufeqdih.html

Py:   os.environ.get("HOME")
来源：http://dali.yvedp.cn/Article/details/gtebjxypmt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258888.top/Article/details/gtmvntrlrg.html

JS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gtwyoyrbtv.html

TS:   process.env.HOME
来源：http://dali.havefunace.top/Article/details/gtgapbiohu.html

Java: System.getenv("HOME")
来源：http://dali.sxryk.cn/Article/details/gtennhoqgw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xuanzx.com/Article/details/gtdotffozg.html

Ruby: ENV["HOME"]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtufcmksek.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnqzz.top/Article/details/gtfnghxagw.html

[M03] 执行外部命令
来源：http://dali.redwolf501.top/Article/details/gtnpiuxbew.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gogol.net.cn/Article/details/gtjxlstgyf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258888.top/Article/details/gtqgmeidcd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbdyqxjs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gtsioufrbx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.wangdashe.top/Article/details/gtskuqcsow.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenzaomai.com/Article/details/gtikhsamrh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.fzhhl.top/Article/details/gtqyevande.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cqqwz.cn/Article/details/gtktdenmzh.html

[M04] 获取当前工作目录
来源：http://dali.fengsongda.top/Article/details/gtcjxdigoa.html

Py:   os.getcwd()
来源：http://dali.birdmap.top/Article/details/gtltjhseei.html

PHP:  getcwd();
来源：http://dali.yueranfly.top/Article/details/gtgnyddgki.html

JS:   process.cwd()
来源：http://dali.bjfxy.top/Article/details/gtnbkzotlu.html

TS:   process.cwd()
来源：http://dali.xylfe.cn/Article/details/gtepccqeoo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxzuzdovt.html

Go:   os.Getwd()
来源：http://dali.hnxiangtu.top/Article/details/gtzqxilzde.html

Ruby: Dir.pwd
来源：http://dali.shuidangran.top/Article/details/gtalufxhvi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cheryme.top/Article/details/gtzniuqjeo.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gtffgwyjrn.html

Py:   sys.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtwhdofmfn.html

PHP:  exit(1);
来源：http://dali.hammf.cn/Article/details/gtdttlueql.html

JS:   process.exit(1)
来源：http://dali.guannengcc.top/Article/details/gteawqpqxu.html

TS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtbmwmgftf.html

Java: System.exit(1)
来源：http://dali.hnqzz.top/Article/details/gtwdnqaynj.html

Go:   os.Exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtbedhpxir.html

Ruby: exit 1
来源：http://dali.vqdsnc.cn/Article/details/gtgusqmkvd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.redwolf501.top/Article/details/gtasxmjcoy.html

[M06] 向标准错误输出
来源：http://dali.quarkkingdee.top/Article/details/gtzalfmfev.html

Py:   print("err", file=sys.stderr)
来源：http://dali.daria6918.cn/Article/details/gtsykwucgx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.fengsongda.top/Article/details/gtthnsdari.html

JS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gtnsaxumim.html

TS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gtaaihpryi.html

Java: System.err.println("err")
来源：http://dali.shuidangran.top/Article/details/gtbjdcofyv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.guowangkeji.top/Article/details/gtduvnjxrs.html

Ruby: warn "err"
来源：http://dali.hnqzz.top/Article/details/gtxcrccenk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tianlin.xyz/Article/details/gtootxvtzl.html

[M07] 判断是否为主入口
来源：http://dali.hongshengwenyu.top/Article/details/gtomzlfojx.html

Py:   if __name__ == "__main__":
来源：http://dali.sufxvd.cn/Article/details/gtihcgeciw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.wangshuangyany.cn/Article/details/gtptfwktvf.html

JS:   require.main === module
来源：http://dali.jqgfzy.top/Article/details/gtqdnfjwlp.html

TS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gthtfjheir.html

Java: public static void main(String[] args)
来源：http://dali.yuanzhike.top/Article/details/gtapnvzykm.html

Go:   func main()
来源：http://dali.yj202588.top/Article/details/gtuwqhwfwe.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhoulong.xyz/Article/details/gtaxdzduma.html

C#:   static void Main(string[] args)
来源：http://dali.daria6918.cn/Article/details/gtfffivkdr.html

[M08] 获取系统与运行时信息
来源：http://dali.daria6918.cn/Article/details/gtaatygres.html

Py:   platform.system();  platform.python_version()
来源：http://dali.redwolf501.top/Article/details/gtpfhfjqsl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tian-w.cn/Article/details/gtzwqylfjm.html

JS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gtszmjsmgx.html

TS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gtjolzpxca.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yuxming.cn/Article/details/gtdqwbxoxn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.316326.xyz/Article/details/gtenyifkfu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hammf.cn/Article/details/gtstjmdlbk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zdqjudy.top/Article/details/gtlrntrgux.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtuzushbvl.html

N. 数据结构与算法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjiweplm.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtamubfzev.html

[N01] 二分查找（有序数组）
来源：http://dali.havefunace.top/Article/details/gtvapioysx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtbcskxuzm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yuxming.cn/Article/details/gtnlsehewn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sysykeji.top/Article/details/gtrlbueuje.html


<!-- 参考信息 -->