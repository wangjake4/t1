代发 wailian999

[J03] 字符串解析为日期
来源：http://dali.hnxiangtu.top/Article/details/gtwhxvweje.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdbxigwwk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.dashuyun.cn/Article/details/gtmgnnenvf.html

JS:   new Date("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtrizavbvh.html

TS:   new Date("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gttkywotrl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtnzvlmizq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtlkuihbwr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtsziwtutk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jqgufenzy.top/Article/details/gtmfxwxexk.html

[J04] 时间戳与日期互转
来源：http://dali.gogol.net.cn/Article/details/gtobpoxhcx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenlongwang.top/Article/details/gtcdamsnjs.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ydzc1.top/Article/details/gtekgqfrzg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tian-w.cn/Article/details/gtfwoonvge.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zdqjudy.top/Article/details/gthnmftxoj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258888.top/Article/details/gtakyxjtjv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.dianchejie.cn/Article/details/gtfchwgsbw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daxiang520.top/Article/details/gtfwblczlz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hammf.cn/Article/details/gtfnywaapo.html

[J05] 时间加减（加 7 天）
来源：http://dali.sufxvd.cn/Article/details/gtpplvayxy.html

Py:   now + timedelta(days=7)
来源：http://dali.zhengqikj.top/Article/details/gtpimvcjxo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jiagoushi.top/Article/details/gtojbgdebo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gtzlsahkur.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gteprfxmnz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinqigufen.top/Article/details/gtlzbscupl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xinyue.icu/Article/details/gtyjulzamk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.birdmap.top/Article/details/gtdxjckivi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbzktlcv.html

[J06] 计算两时间之差
来源：http://dali.nwbrower.top/Article/details/gtsevqhysp.html

Py:   (end - start).total_seconds()
来源：http://dali.bjfxy.top/Article/details/gtqsmafcap.html

PHP:  $end->diff($start)->days;
来源：http://dali.ivvv.top/Article/details/gtsszrrexe.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.haohaochexian.top/Article/details/gtqlobriza.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gtaxlttxoo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ppjwa.cn/Article/details/gtgivebdob.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhoulong.xyz/Article/details/gthnepruua.html

Ruby: end - start                 # 返回秒数
来源：http://dali.mhx1999.top/Article/details/gtyegjfzrd.html

C#:   (end - start).TotalSeconds
来源：http://dali.guowangkeji.top/Article/details/gtkezsfvki.html

[J07] 比较两个日期
来源：http://dali.gaohongyu789.top/Article/details/gtezoqlixh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gtkygpbgke.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sxryk.cn/Article/details/gtncxrioxg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yongpay.top/Article/details/gtpimsneox.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gtgczklddz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xziqi.cn/Article/details/gtvylsxzah.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.andypj.xyz/Article/details/gtxayzqioj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtjgbzazwd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gtnzxmokuz.html

[J08] 提取年月日与星期
来源：http://dali.0kj1m.cn/Article/details/gtacbqeput.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.dianchejie.cn/Article/details/gteotfenmf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjwnaflva.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.kuanghao11.cn/Article/details/gtiycathac.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jqgufenzy.top/Article/details/gtltzpllrf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.bjfxy.top/Article/details/gtyxuuhacd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cucudq.cn/Article/details/gtaawdbffz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ivvv.top/Article/details/gtpuwxgtdo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jianghu66.top/Article/details/gtcdjgfuxz.html

[J09] 时区处理
来源：http://dali.hnxiangtu.top/Article/details/gtutetvpgb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yangfankeji.com/Article/details/gtgxbtgcpf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.guannengcc.top/Article/details/gtkqtnwuqd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwtlnixld.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pycfn.com/Article/details/gtfmrbutrr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.mhx1999.top/Article/details/gtqguxnwsw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthlpcsqon.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthlyntbei.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jlsjyb.cn/Article/details/gtwngwuuaz.html

[J10] 取今天 / 本月第一天
来源：http://dali.xziqi.cn/Article/details/gtfrayespv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.pycfn.com/Article/details/gtayvbtenq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hnxiangtu.top/Article/details/gtlmnsiyik.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.havefunace.top/Article/details/gtevavxdij.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yuanzhike.top/Article/details/gtdiewfocl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xylfe.cn/Article/details/gthflynfbf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.dianchejie.cn/Article/details/gtrcwxmzjv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuxming.cn/Article/details/gtodavpwqf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.aibaodan.cn/Article/details/gtfvofwwao.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtdzcinwkb.html

K. JSON 与序列化
来源：http://dali.svipenyu.cn/Article/details/gtucnbmhat.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtqpslfcte.html

[K01] 对象转 JSON 字符串
来源：http://dali.guannengcc.top/Article/details/gtvoiofnzm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gtfauyvjnt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.daxiang520.top/Article/details/gtxqawvwgl.html

JS:   JSON.stringify(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtteccgkfu.html

TS:   JSON.stringify(obj)
来源：http://dali.ydzc1.top/Article/details/gtzcoppszf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinghuilouyu.cn/Article/details/gtluiyhblq.html

Go:   json.Marshal(obj)
来源：http://dali.xziqi.cn/Article/details/gtovnxvmab.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jlsjyb.cn/Article/details/gtfcivtrhm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ydzc1.top/Article/details/gtgonjdiwz.html

[K02] JSON 字符串转对象
来源：http://dali.jinqigfzy.top/Article/details/gtsmbmckfw.html

Py:   json.loads(s)
来源：http://dali.cashguo.top/Article/details/gtmnrqwezd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnlephur.html

JS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtopjoxuok.html

TS:   JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gtvwtlfyhn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ehwqpu.com/Article/details/gtisbznjql.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guannengcc.top/Article/details/gtgjpranku.html

Ruby: JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gtfrrustaa.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtbtpqcnbr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cqqwz.cn/Article/details/gtvqjemypa.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gteofhsvbs.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gttbjbwwln.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gtrbxvphoi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gtyjodgdnm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtnutqvsab.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cqqwz.cn/Article/details/gtnqgpqmex.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtpjnwljmz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shzxlz.cn/Article/details/gtpqqjjhdf.html

[K04] 读取 JSON 文件
来源：http://dali.gotoacloud.top/Article/details/gtbbhfmoeb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yuxming.cn/Article/details/gtgblhfwzf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258888.top/Article/details/gttvdzplwu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.0kj1m.cn/Article/details/gtqgnyvvxc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gtygogimum.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj20258888.top/Article/details/gtnrttlvqh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hysaishi.cn/Article/details/gtushuvium.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.guannengcc.top/Article/details/gtwftdxvhz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sysykeji.top/Article/details/gtgxjowtdu.html

[K05] 深拷贝对象
来源：http://dali.fengsongda.top/Article/details/gtnzibrvus.html

Py:   copy.deepcopy(obj)
来源：http://dali.xinyue.icu/Article/details/gtzazzcfdt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj20258.top/Article/details/gtlwmofxqj.html

JS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gtxepilqon.html

TS:   structuredClone(obj)
来源：http://dali.xinyue.icu/Article/details/gtecjpfikl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.dianchejie.cn/Article/details/gtwnxthjqk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtibixgouu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jqgfzy.top/Article/details/gtiuqltaed.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zdqjudy.top/Article/details/gtzjslyvni.html

[K06] 解析 URL 查询串
来源：http://dali.yueranfly.top/Article/details/gtqyeacmud.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.haohaochexian.top/Article/details/gtefzvbkru.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.snrcjt.cn/Article/details/gtwiesrsat.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.redwolf501.top/Article/details/gtuzrfyfhs.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ivvv.top/Article/details/gtpehkoiaw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenjidiqi.icu/Article/details/gtrdawqbfi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gtsebwxpku.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gtzxfjahhn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gtatmpvoth.html

[K07] 进制转换
来源：http://dali.jiagoushi.top/Article/details/gtmwnqgtwf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtztacmdqb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jianghu66.top/Article/details/gtujntlmfw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzvynpsmq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtalvgqvxf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtepfabhrd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tanke756.top/Article/details/gtktaxpohh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhengqikj.top/Article/details/gtejisqkyo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gthfmcieit.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yangfankeji.com/Article/details/gtdpvuitdc.html

Py:   pickle.dumps(obj)
来源：http://dali.tianlin.xyz/Article/details/gtdemmrvqq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hysaishi.cn/Article/details/gttxqvlgxy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.kuanghao11.cn/Article/details/gtanncfqoe.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gtsxzpjben.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.dashuyun.cn/Article/details/gthddpiejh.html

Go:   encoding/gob
来源：http://dali.cucudq.cn/Article/details/gtcrtqcykp.html

Ruby: Marshal.dump(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtzpdmhdxq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.smart0.xyz/Article/details/gtmtsqicrz.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtdbhgdbfe.html

L. 网络请求
来源：http://dali.feifeiyinyue.top/Article/details/gtfgcrijec.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtayyvxaci.html

[L01] 发送 GET 请求
来源：http://dali.nwbrower.top/Article/details/gttfihpwxb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.c1oappe.top/Article/details/gtiaupdows.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.pycfn.com/Article/details/gthwgyqxbx.html

JS:   await fetch(url)
来源：http://dali.guowangkeji.top/Article/details/gtnogplrmj.html

TS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gtggobmqse.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ivvv.top/Article/details/gtvivseroh.html

Go:   resp, err := http.Get(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtcxfqokvs.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gzhubu.top/Article/details/gtrxlmztpz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ybcxt.top/Article/details/gtnnloopvc.html

[L02] 发送 POST JSON
来源：http://dali.zhixingplan.top/Article/details/gtnilkxhmx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.316326.xyz/Article/details/gtttazotzf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xylfe.cn/Article/details/gtyolrsqmj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gtqsachkch.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.haohaochexian.top/Article/details/gtligltomg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cdnleiting.top/Article/details/gtcjclosuu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjggmkips.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xuetiantiany.cn/Article/details/gtkhkjnwxa.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.birdmap.top/Article/details/gttlzjjxos.html

[L03] 设置自定义请求头
来源：http://dali.yvedp.cn/Article/details/gteppbaflu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hnqzz.top/Article/details/gtspqgavre.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtekopjnsu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yangfankeji.com/Article/details/gtwswhkgma.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cdnleiting.top/Article/details/gtfdcrbtjk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.meibo888.top/Article/details/gtslhyjjpl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.wangdashe.top/Article/details/gtpgdgdjde.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnqzz.top/Article/details/gtcqgfpkyt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbcviecgl.html

[L04] 设置超时
来源：http://dali.zycfv.cn/Article/details/gtkqyqrmwb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ybcxt.top/Article/details/gtotnevklm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.feifeiyinyue.top/Article/details/gtryuwxcut.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.snrcjt.cn/Article/details/gtpmleysmi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.meibo888.top/Article/details/gtloqxalcp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.andypj.xyz/Article/details/gtavatkozn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenzaomai.com/Article/details/gttmewniii.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhoulong.xyz/Article/details/gtdmgulmcq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.0kj1m.cn/Article/details/gtkwvrmuxg.html

[L05] 上传文件（multipart）
来源：http://dali.quarkkingdee.top/Article/details/gtphplbptx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.daria6918.cn/Article/details/gtyxbnhinv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yueranfly.top/Article/details/gtnbkkujuj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.fengsongda.top/Article/details/gtwcfkfhdj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hysaishi.cn/Article/details/gtndzvpedh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.c1oappe.top/Article/details/gtohszzgxb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetklhzct.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.birdmap.top/Article/details/gtksdfikgl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xylfe.cn/Article/details/gtvjvlmesr.html

[L06] 解析响应为 JSON
来源：http://dali.ppjwa.cn/Article/details/gtdfghxmjf.html

Py:   resp.json()
来源：http://dali.pycfn.com/Article/details/gtqmassxus.html

PHP:  json_decode($body, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqrjbgsbd.html

JS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gtzfyigpdb.html

TS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gtiidakyvu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gtzitvzudy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cashguo.top/Article/details/gtzgtkqyca.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cqqwz.cn/Article/details/gtlpqqfpgz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hysaishi.cn/Article/details/gttlfyqnhi.html

[L07] 处理 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gtkihwjpem.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cucudq.cn/Article/details/gtjbztngow.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhoulong.xyz/Article/details/gtpjrqodds.html

JS:   resp.ok;  resp.status
来源：http://dali.nanxinkj.top/Article/details/gtsxsajmoc.html

TS:   resp.ok;  resp.status
来源：http://dali.andypj.xyz/Article/details/gtyhbqyhky.html

Java: resp.statusCode()
来源：http://dali.yonumen.top/Article/details/gtrielajdi.html

Go:   resp.StatusCode
来源：http://dali.yj202588.top/Article/details/gtsncchutw.html

Ruby: resp.code.to_i
来源：http://dali.0kj1m.cn/Article/details/gtskjjxdhf.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gthbhjrpfg.html

[L08] 并发请求多个地址
来源：http://dali.xinyue.icu/Article/details/gtrbsgjali.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sysykeji.top/Article/details/gtnmqtbjta.html

PHP:  curl_multi_init() 系列
来源：http://dali.yuanzhike.top/Article/details/gtmxvuuydw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gtlkrxubyy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.quarkkingdee.top/Article/details/gtudsjubrq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yvedp.cn/Article/details/gtnukfujah.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shuidangran.top/Article/details/gtpmbccqcq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pycfn.com/Article/details/gtprguyfin.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yongpay.top/Article/details/gtjitvwnfa.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtkbkntgit.html

M. 命令行 / 进程 / 环境
来源：http://dali.jyoumei.cn/Article/details/gtgtluhqsd.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtakvdqsrf.html

[M01] 读取命令行参数
来源：http://dali.zycfv.cn/Article/details/gtcrmiiudq.html

Py:   sys.argv[1:]
来源：http://dali.nwbrower.top/Article/details/gtrsklmcwg.html

PHP:  $argv;  $argc;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqhcehxn.html

JS:   process.argv.slice(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamzwysmy.html

TS:   process.argv.slice(2)
来源：http://dali.hysaishi.cn/Article/details/gtrbblpiqj.html

Java: args 数组（main 方法参数）
来源：http://dali.havefunace.top/Article/details/gtvvbjojiu.html

Go:   os.Args[1:]
来源：http://dali.guowangkeji.top/Article/details/gtrlmmplud.html

Ruby: ARGV
来源：http://dali.cqqwz.cn/Article/details/gteyzobgpf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gogol.net.cn/Article/details/gtwukpsfsy.html

[M02] 读取环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfebeipu.html

Py:   os.environ.get("HOME")
来源：http://dali.yueranfly.top/Article/details/gttpfqwvfg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pycfn.com/Article/details/gtzoxvegwp.html

JS:   process.env.HOME
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftmpcqcg.html

TS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gtahwqxncp.html

Java: System.getenv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtkxoelakl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gtjkztufzy.html

Ruby: ENV["HOME"]
来源：http://dali.hnxiangtu.top/Article/details/gtaukwyzci.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hammf.cn/Article/details/gtspaaebjr.html

[M03] 执行外部命令
来源：http://dali.svipenyu.cn/Article/details/gtbaokqyot.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hongshengwenyu.top/Article/details/gtcfrwjyov.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.smart0.xyz/Article/details/gtkfwrqfsd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gogol.net.cn/Article/details/gtriuxrjgo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcfyweoal.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jyoumei.cn/Article/details/gtkphxnbri.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yuxming.cn/Article/details/gtqtnwoikm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.dianchejie.cn/Article/details/gtklqxvwlj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gzhubu.top/Article/details/gtoqrtwdtw.html

[M04] 获取当前工作目录
来源：http://dali.gaohongyu789.top/Article/details/gtrtoneprg.html

Py:   os.getcwd()
来源：http://dali.aizwys.cn/Article/details/gtuycpmdns.html

PHP:  getcwd();
来源：http://dali.feifeiyinyue.top/Article/details/gtsapqamon.html

JS:   process.cwd()
来源：http://dali.zhoulong.xyz/Article/details/gtpbfsablr.html

TS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gtukhqeedb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daxiang520.top/Article/details/gtmzdplopi.html

Go:   os.Getwd()
来源：http://dali.sxryk.cn/Article/details/gtbjxtombi.html

Ruby: Dir.pwd
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfzxusjox.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj20258888.top/Article/details/gtgsiovfks.html

[M05] 设置退出码
来源：http://dali.yuxming.cn/Article/details/gtwdtlqtfb.html

Py:   sys.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbebpnwzf.html

PHP:  exit(1);
来源：http://dali.xziqi.cn/Article/details/gthbbrtplg.html

JS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtmutprlgi.html

TS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtjaxmpopi.html

Java: System.exit(1)
来源：http://dali.yj20258.top/Article/details/gtahafydgl.html

Go:   os.Exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtzikenkir.html

Ruby: exit 1
来源：http://dali.hnxiangtu.top/Article/details/gtrqfufhqt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jyoumei.cn/Article/details/gtnapvshis.html

[M06] 向标准错误输出
来源：http://dali.redwolf501.top/Article/details/gtkmobtoxm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hysaishi.cn/Article/details/gtffqvyanj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinqigfzy.top/Article/details/gtyvxrbwdp.html

JS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gtyyqjyizt.html

TS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gtgrrbvzdj.html

Java: System.err.println("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrozkffk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.smart0.xyz/Article/details/gtkqnnceor.html

Ruby: warn "err"
来源：http://dali.meibo888.top/Article/details/gttwwuvomi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cashguo.top/Article/details/gtfundvrps.html

[M07] 判断是否为主入口
来源：http://dali.ppjwa.cn/Article/details/gttimmtnda.html

Py:   if __name__ == "__main__":
来源：http://dali.yangfankeji.com/Article/details/gtghelfskk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gttnyseohq.html

JS:   require.main === module
来源：http://dali.yanxiufei.cn/Article/details/gtbsndmxqt.html

TS:   require.main === module
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpgbqnkkk.html

Java: public static void main(String[] args)
来源：http://dali.xziqi.cn/Article/details/gtnahkmaey.html

Go:   func main()
来源：http://dali.jinqigfzy.top/Article/details/gtdzthckxw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jqgufenzy.top/Article/details/gtxhcbxmql.html

C#:   static void Main(string[] args)
来源：http://dali.cheryme.top/Article/details/gtxggcpmvq.html

[M08] 获取系统与运行时信息
来源：http://dali.pengpengdd.cyou/Article/details/gtxzefsgvy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jianghu66.top/Article/details/gtpsxkyddb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.quarkkingdee.top/Article/details/gtdhnexbbk.html

JS:   process.platform;  process.version
来源：http://dali.zhiwuduotai.top/Article/details/gtjsauohmt.html

TS:   process.platform;  process.version
来源：http://dali.ehwqpu.com/Article/details/gtqazooktx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.pycfn.com/Article/details/gtdtqvuweh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.0kj1m.cn/Article/details/gtymtvpito.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.aibaodan.cn/Article/details/gtflscjiho.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yonumen.top/Article/details/gtemfjaewy.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtgmjhmive.html

N. 数据结构与算法
来源：http://dali.jinqigufen.top/Article/details/gtnmdtqkpu.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtjjyttrtx.html


<!-- 参考信息 -->