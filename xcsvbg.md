代发 wailian999

TS:   new Date("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtqcsocfbw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtxkscpuxk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtyooovhvk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtpybcyrce.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hnxiangtu.top/Article/details/gtqmgvxcls.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258.top/Article/details/gtyihykokd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuxming.cn/Article/details/gtjoihejme.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shzxlz.cn/Article/details/gtjslcpwza.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.fzhhl.top/Article/details/gtwuqgejan.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtitihycqn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hfpthk.cn/Article/details/gtczlowvpk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuanzhike.top/Article/details/gtfsbdsrmg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yonumen.top/Article/details/gtnkulgkgd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cucudq.cn/Article/details/gtxmagqjsp.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgufenzy.top/Article/details/gtcygcexng.html

Py:   now + timedelta(days=7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtypggaenc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jqgufenzy.top/Article/details/gtspiyjbtz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cheryme.top/Article/details/gtnadoagea.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhixingplan.top/Article/details/gtqswfacjv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gtypvcdyrq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.feifeiyinyue.top/Article/details/gtbinbnqok.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xuanzx.com/Article/details/gtjcuehikp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sysykeji.top/Article/details/gtdotsadjr.html

[J06] 计算两时间之差
来源：http://dali.ivvv.top/Article/details/gtrowzuwcr.html

Py:   (end - start).total_seconds()
来源：http://dali.shangyingyoupin.top/Article/details/gtrhvcsaal.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhongyouzk.top/Article/details/gtzllbeybm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinyuanbaomall.cn/Article/details/gtosxwgada.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hongshengwenyu.top/Article/details/gtggdtkgnx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jianghu66.top/Article/details/gtyycqclkb.html

Go:   end.Sub(start).Hours()
来源：http://dali.feifeiyinyue.top/Article/details/gtfybwfkus.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tianlin.xyz/Article/details/gtcnbnkibt.html

C#:   (end - start).TotalSeconds
来源：http://dali.jqgfzy.top/Article/details/gtjkusuupj.html

[J07] 比较两个日期
来源：http://dali.dianchejie.cn/Article/details/gtmwgcxobd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtfpdvhzqb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.daria6918.cn/Article/details/gtopouafym.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenjidiqi.icu/Article/details/gtjchtfvxp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jiagoushi.top/Article/details/gtkukebbdj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.snrcjt.cn/Article/details/gttrfcphzn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yangfankeji.com/Article/details/gtiybirszr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gtmfqwooqz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gtcrljlqja.html

[J08] 提取年月日与星期
来源：http://dali.zhiwuduotai.top/Article/details/gteqepzjqe.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cashguo.top/Article/details/gtkqxfvgjc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yanxiufei.cn/Article/details/gtohpirgjo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sysykeji.top/Article/details/gtuhavudks.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.snrcjt.cn/Article/details/gtbecgmmvc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ybcxt.top/Article/details/gtpeiknwjs.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ehwqpu.com/Article/details/gtthvslkxw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aizwys.cn/Article/details/gtpqwnuidw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdvbagdn.html

[J09] 时区处理
来源：http://dali.xinyue.icu/Article/details/gtyazgqoyv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtquszhtao.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jlsjyb.cn/Article/details/gtvchuknhu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.feifeiyinyue.top/Article/details/gtikligtwd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.vqdsnc.cn/Article/details/gtrsfsjrrh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.andypj.xyz/Article/details/gtiawriwrs.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.aizwys.cn/Article/details/gtliyahgiv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jlsjyb.cn/Article/details/gtlyosljph.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.c1oappe.top/Article/details/gthkfwofjr.html

[J10] 取今天 / 本月第一天
来源：http://dali.cheryme.top/Article/details/gtxwtfhrlb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwrapfitp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hnxiangtu.top/Article/details/gtrvqxcrgd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgufenzy.top/Article/details/gtddvczmvq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnbxedljk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.snrcjt.cn/Article/details/gtiwljxnrv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuanzx.com/Article/details/gthtvunztq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.pycfn.com/Article/details/gtbwvojbxf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttpgivnky.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gthwdgwukk.html

K. JSON 与序列化
来源：http://dali.shanyushiyangtech.top/Article/details/gtqcwfmjmd.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtdqsawwia.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhengqikj.top/Article/details/gtaxhcumhw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gtuyqoreoh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhoulong.xyz/Article/details/gtlvkppywl.html

JS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gtynrjmduc.html

TS:   JSON.stringify(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtbqhkrfzk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yanxiufei.cn/Article/details/gtgyylzoez.html

Go:   json.Marshal(obj)
来源：http://dali.shuidangran.top/Article/details/gtptpcdafe.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ehwqpu.com/Article/details/gtselsdomc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtkmhckzum.html

[K02] JSON 字符串转对象
来源：http://dali.hysaishi.cn/Article/details/gtnxutqqxz.html

Py:   json.loads(s)
来源：http://dali.zdqjudy.top/Article/details/gtdqqqgfcn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gogol.net.cn/Article/details/gteokuxmzz.html

JS:   JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gtdjflxvwk.html

TS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gtpfevnkai.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fzhhl.top/Article/details/gterrwyerp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xuetiantiany.cn/Article/details/gtmygnpgqn.html

Ruby: JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gtdlxcsopj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sxryk.cn/Article/details/gtkvhlzfoh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.mhx1999.top/Article/details/gtklkaqcza.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gtroicdmmz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gtaaubgopr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.dashuyun.cn/Article/details/gtbbhqvauf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtblxzfole.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtpaoldtpt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nwbrower.top/Article/details/gtwzwhyevm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtchqafyio.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhengqikj.top/Article/details/gtlxkoyxfc.html

[K04] 读取 JSON 文件
来源：http://dali.cashguo.top/Article/details/gttumakzrz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.guannengcc.top/Article/details/gturppgebu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gzhubu.top/Article/details/gtdziirryz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gtomsfaank.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jyoumei.cn/Article/details/gtyqxrybyj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.fengsongda.top/Article/details/gtrbqwbayl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gtcvyqdfcv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.bjfxy.top/Article/details/gttiidupqr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj20258888.top/Article/details/gtfexjujab.html

[K05] 深拷贝对象
来源：http://dali.pycfn.com/Article/details/gtivjymxvl.html

Py:   copy.deepcopy(obj)
来源：http://dali.yongpay.top/Article/details/gtrfcdxgxu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hysaishi.cn/Article/details/gtwfbctbfc.html

JS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gtrtbpdzlm.html

TS:   structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gtacquunad.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jianghu66.top/Article/details/gtzvznbjql.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jlsjyb.cn/Article/details/gtwuleavsd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenlongwang.top/Article/details/gtdizyigwh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.meibo888.top/Article/details/gtxgnmyvoh.html

[K06] 解析 URL 查询串
来源：http://dali.meibo888.top/Article/details/gtcjqymkcl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cqqwz.cn/Article/details/gtrenpgsfp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj202588.top/Article/details/gtsonwwuof.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gtjxxxnzgk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuanzx.com/Article/details/gtvfwtyehx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sysykeji.top/Article/details/gtwncmudvy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gtjcxqquxd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gttpfkxmoc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gtvjfsswxm.html

[K07] 进制转换
来源：http://dali.zhongyouzk.top/Article/details/gtjyqtcxax.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtdfykoxzn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.dianchejie.cn/Article/details/gtgcfvbkpk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtsnipcsgo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtzxvjacly.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtdrfvskql.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tian-w.cn/Article/details/gtqojwkltk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnqzz.top/Article/details/gtszbbdmzn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtgvkkuxha.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.9152youxi.cn/Article/details/gtcfvibtmw.html

Py:   pickle.dumps(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdhbuegzu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hfpthk.cn/Article/details/gtstwouhdc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.havefunace.top/Article/details/gtnsvfnovk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.fengsongda.top/Article/details/gtzwxnkwun.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yuxming.cn/Article/details/gtmpnutrle.html

Go:   encoding/gob
来源：http://dali.jinqigfzy.top/Article/details/gtzxnloxty.html

Ruby: Marshal.dump(obj)
来源：http://dali.fengsongda.top/Article/details/gtwuzwyihd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.daria6918.cn/Article/details/gttvmnvxyc.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtsbkdsqux.html

L. 网络请求
来源：http://dali.yangfankeji.com/Article/details/gtufvxbbeo.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtdwncjqhn.html

[L01] 发送 GET 请求
来源：http://dali.zhiwuduotai.top/Article/details/gtweopeocm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhixingplan.top/Article/details/gtvxlfxccp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxchszws.html

JS:   await fetch(url)
来源：http://dali.tianlin.xyz/Article/details/gtwmkbbles.html

TS:   await fetch(url)
来源：http://dali.jiagoushi.top/Article/details/gtcgvuzeqv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hywenlv.cn/Article/details/gtrxvowkjy.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gtznpcuzhg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ivvv.top/Article/details/gtetaooexc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtbxnzdsay.html

[L02] 发送 POST JSON
来源：http://dali.bjfxy.top/Article/details/gtnvhtqtzl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yuxming.cn/Article/details/gtstjwkgos.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinghuilouyu.cn/Article/details/gttspqnimp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjxgvggx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gtgearnhgx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hongshengwenyu.top/Article/details/gtpoiuybzu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yanxiufei.cn/Article/details/gttlepirvu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwjftokm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zycfv.cn/Article/details/gtianclfbl.html

[L03] 设置自定义请求头
来源：http://dali.iojbl.cn/Article/details/gtxyqswzrm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinqigufen.top/Article/details/gtmcbzardf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yangfankeji.com/Article/details/gtjmpsvwdz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hfpthk.cn/Article/details/gtfyxtkdlb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gtyvuhsfgn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xylfe.cn/Article/details/gtujqpwxkb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pycfn.com/Article/details/gtwyllahdn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cdnleiting.top/Article/details/gtjnvfqlcd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xziqi.cn/Article/details/gtxqsatoxj.html

[L04] 设置超时
来源：http://dali.svipenyu.cn/Article/details/gtbvzysymy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.daxiang520.top/Article/details/gtvjhvkmti.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgfzy.top/Article/details/gtpcifuyiw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gtkrshxzph.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258888.top/Article/details/gtsrtigryq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cucudq.cn/Article/details/gtjcziuorq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tanke756.top/Article/details/gtlujdliqo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jqgfzy.top/Article/details/gtdisbmlrd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yongpay.top/Article/details/gtuxjrteus.html

[L05] 上传文件（multipart）
来源：http://dali.wangdashe.top/Article/details/gtxicfszos.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.316326.xyz/Article/details/gtjvgrecyf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nanxuanxn.top/Article/details/gtwekdxaxc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gtungqiete.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gtideypsbt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shzxlz.cn/Article/details/gtyklqlskr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xylfe.cn/Article/details/gtaxbibtoa.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shangyingyoupin.top/Article/details/gtwsneorop.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.redwolf501.top/Article/details/gtycluyfwl.html

[L06] 解析响应为 JSON
来源：http://dali.jyoumei.cn/Article/details/gtkqmfbgql.html

Py:   resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwapdgzag.html

PHP:  json_decode($body, true);
来源：http://dali.xinyue.icu/Article/details/gtjumujcwa.html

JS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gtlydslfif.html

TS:   await resp.json()
来源：http://dali.shzxlz.cn/Article/details/gtzxlyvqmd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gtyxjdfnra.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daria6918.cn/Article/details/gtzoejwjfz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfimdkif.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gtkzczdwem.html

[L07] 处理 HTTP 状态码
来源：http://dali.daria6918.cn/Article/details/gthomtqboi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinqigfzy.top/Article/details/gtguczechk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fengsongda.top/Article/details/gttxxkkthq.html

JS:   resp.ok;  resp.status
来源：http://dali.birdmap.top/Article/details/gtqpomhinz.html

TS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozucwxww.html

Java: resp.statusCode()
来源：http://dali.zdqjudy.top/Article/details/gtlnyshumc.html

Go:   resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gtqjezqgod.html

Ruby: resp.code.to_i
来源：http://dali.yongpay.top/Article/details/gtawaqkera.html

C#:   (int)resp.StatusCode
来源：http://dali.yangfankeji.com/Article/details/gtaqqkedad.html

[L08] 并发请求多个地址
来源：http://dali.fengsongda.top/Article/details/gtqxhbgmhm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nwbrower.top/Article/details/gtbcrymviq.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangdashe.top/Article/details/gtbfurhoir.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nwbrower.top/Article/details/gtxkeyyqcp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gttdoqsorl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hfpthk.cn/Article/details/gtfnvwegxb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gotoacloud.top/Article/details/gtaoywpito.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hywenlv.cn/Article/details/gtdyjjqeah.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guowangkeji.top/Article/details/gtwqmuroxa.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtvkxjabym.html

M. 命令行 / 进程 / 环境
来源：http://dali.jyoumei.cn/Article/details/gtquoaygdx.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtgxjvoctg.html

[M01] 读取命令行参数
来源：http://dali.wangshuangyany.cn/Article/details/gtizvxdexd.html

Py:   sys.argv[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtrgqegrha.html

PHP:  $argv;  $argc;
来源：http://dali.nanxuanxn.top/Article/details/gthlmtdblb.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigufen.top/Article/details/gtpuhqajsb.html

TS:   process.argv.slice(2)
来源：http://dali.xuanzx.com/Article/details/gtaeytpjjj.html

Java: args 数组（main 方法参数）
来源：http://dali.sxryk.cn/Article/details/gtdmlrmyzx.html

Go:   os.Args[1:]
来源：http://dali.shuidangran.top/Article/details/gtvpbartlx.html

Ruby: ARGV
来源：http://dali.fengsongda.top/Article/details/gtacokojhy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.316326.xyz/Article/details/gttgftzjdm.html

[M02] 读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gtwodtsatr.html

Py:   os.environ.get("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtmhrmfath.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258.top/Article/details/gtllyasvwt.html

JS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrylnorfz.html

TS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gtphydygla.html

Java: System.getenv("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtxlbpweml.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtluijlnfv.html

Ruby: ENV["HOME"]
来源：http://dali.xinyue.icu/Article/details/gtbpowgsol.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gotoacloud.top/Article/details/gtjfuawyvy.html

[M03] 执行外部命令
来源：http://dali.pycfn.com/Article/details/gtejnmmjrl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzbazwkbw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nanxinkj.top/Article/details/gteznpxfdg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.havefunace.top/Article/details/gtnfkquawk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jiagoushi.top/Article/details/gtnntkamgg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258888.top/Article/details/gtvfcejssa.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yongpay.top/Article/details/gtsuhjcogv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hongshengwenyu.top/Article/details/gthqkbvyds.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sufxvd.cn/Article/details/gtdvhrcyiy.html

[M04] 获取当前工作目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtgnfoyjgl.html

Py:   os.getcwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtupsridsp.html

PHP:  getcwd();
来源：http://dali.ydzc1.top/Article/details/gthkhyynzm.html

JS:   process.cwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwgywbgfi.html

TS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gtbqxtforg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jiagoushi.top/Article/details/gtacuqmozb.html

Go:   os.Getwd()
来源：http://dali.yj20258.top/Article/details/gtcknilgmf.html

Ruby: Dir.pwd
来源：http://dali.xinyue.icu/Article/details/gtcgihxuqu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shuidangran.top/Article/details/gtpninbgws.html

[M05] 设置退出码
来源：http://dali.xziqi.cn/Article/details/gtezhgqrgx.html

Py:   sys.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtflnzhwjb.html

PHP:  exit(1);
来源：http://dali.chenjidiqi.icu/Article/details/gtkjwwqjdg.html

JS:   process.exit(1)
来源：http://dali.yj20258888.top/Article/details/gtukazotjk.html

TS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gttzdxnkon.html

Java: System.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtlorltemd.html

Go:   os.Exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gthavgrsxj.html

Ruby: exit 1
来源：http://dali.bjfxy.top/Article/details/gtgehsyded.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.svipenyu.cn/Article/details/gtccfmjvos.html

[M06] 向标准错误输出
来源：http://dali.tanke756.top/Article/details/gtumnglsbo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sxryk.cn/Article/details/gtdnujvojs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nwbrower.top/Article/details/gtwpgpfbwm.html

JS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gtylzelbeb.html

TS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gtuzxdospp.html

Java: System.err.println("err")
来源：http://dali.jinqigfzy.top/Article/details/gtuxqnjnko.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jiagoushi.top/Article/details/gtmxzeecrm.html

Ruby: warn "err"
来源：http://dali.yueranfly.top/Article/details/gtopmvnlhp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tanke756.top/Article/details/gtuyfbsubw.html

[M07] 判断是否为主入口
来源：http://dali.snrcjt.cn/Article/details/gtjbszdsrd.html

Py:   if __name__ == "__main__":
来源：http://dali.nwbrower.top/Article/details/gtabtofttr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sufxvd.cn/Article/details/gtjzedcosj.html

JS:   require.main === module
来源：http://dali.zhixingplan.top/Article/details/gtthgpjxnb.html

TS:   require.main === module
来源：http://dali.zhoulong.xyz/Article/details/gtuozzmnhn.html

Java: public static void main(String[] args)
来源：http://dali.yangfankeji.com/Article/details/gtqchfynbz.html

Go:   func main()
来源：http://dali.gogol.net.cn/Article/details/gtghrkwacf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.havefunace.top/Article/details/gtvsogcyug.html

C#:   static void Main(string[] args)
来源：http://dali.dianchejie.cn/Article/details/gtpeqrlwld.html

[M08] 获取系统与运行时信息
来源：http://dali.yueranfly.top/Article/details/gtgihsczko.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sysykeji.top/Article/details/gtuqpnmezl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.snrcjt.cn/Article/details/gttdszgmga.html

JS:   process.platform;  process.version
来源：http://dali.zhixingplan.top/Article/details/gtuxmuuxxc.html

TS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gtgaeuajly.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.pengpengdd.cyou/Article/details/gtbliafejp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.quarkkingdee.top/Article/details/gtjgtumbwj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tanke756.top/Article/details/gtdyqnlmok.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yuanzhike.top/Article/details/gtmpoqoifv.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtyxorzgrz.html

N. 数据结构与算法
来源：http://dali.zhongyouzk.top/Article/details/gttrgpcamo.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtewxmmevf.html

[N01] 二分查找（有序数组）
来源：http://dali.ehwqpu.com/Article/details/gtoyqpbefq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtjcdshhri.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cashguo.top/Article/details/gtymqnpyyd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.havefunace.top/Article/details/gtyqyiktqr.html


<!-- 参考信息 -->