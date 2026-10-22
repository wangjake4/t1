代发 wailian999

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxinkj.top/Article/details/gtkyilkuxb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhengqikj.top/Article/details/gtvqeonndg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gtuxavubay.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gotoacloud.top/Article/details/gtjjumkddv.html

[J03] 字符串解析为日期
来源：http://dali.aibaodan.cn/Article/details/gtodynaqyj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sufxvd.cn/Article/details/gtjrduyvig.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.haohaochexian.top/Article/details/gtqssflsvm.html

JS:   new Date("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtpeoeszhf.html

TS:   new Date("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtrvbczjsa.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtwweepcjo.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtpyqyprgz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtkmucwaow.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjejdlzaj.html

[J04] 时间戳与日期互转
来源：http://dali.jyoumei.cn/Article/details/gtlqbawdck.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhengqikj.top/Article/details/gtkajkfblh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.guannengcc.top/Article/details/gtqwtwqaxp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.svipenyu.cn/Article/details/gtgudyvpfh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuugsfqgr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gthexqvmoi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfpnespbp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sysykeji.top/Article/details/gtxspraijm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtralgnewc.html

[J05] 时间加减（加 7 天）
来源：http://dali.feifeiyinyue.top/Article/details/gtuukkyzex.html

Py:   now + timedelta(days=7)
来源：http://dali.yj20258888.top/Article/details/gtwtyyyufw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.birdmap.top/Article/details/gtcpjbajmd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zdqjudy.top/Article/details/gtfeonythr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gtitcjtgim.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.andypj.xyz/Article/details/gtjlzyutkz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdowpwigz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ehwqpu.com/Article/details/gtflziulrd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jyoumei.cn/Article/details/gtfuiewjpn.html

[J06] 计算两时间之差
来源：http://dali.316326.xyz/Article/details/gtfjdyqshb.html

Py:   (end - start).total_seconds()
来源：http://dali.chenzaomai.com/Article/details/gtzzlxgghz.html

PHP:  $end->diff($start)->days;
来源：http://dali.ydzc1.top/Article/details/gtjywlsfnl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgfzy.top/Article/details/gtnxsowkpl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gzhubu.top/Article/details/gtajgfzofi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tian-w.cn/Article/details/gthgbnhbjz.html

Go:   end.Sub(start).Hours()
来源：http://dali.yangfankeji.com/Article/details/gtxbvzsevi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenzaomai.com/Article/details/gtpmmntung.html

C#:   (end - start).TotalSeconds
来源：http://dali.sxryk.cn/Article/details/gtgttrmbvl.html

[J07] 比较两个日期
来源：http://dali.ehwqpu.com/Article/details/gtztntzkue.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtmpzyuomt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jianghu66.top/Article/details/gtvctfprgc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.316326.xyz/Article/details/gtkqzaxpal.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sysykeji.top/Article/details/gtttntmbpg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.0kj1m.cn/Article/details/gtwnnkayws.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.snrcjt.cn/Article/details/gtwmtcseon.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gttmdanauf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gtcfzwmzoj.html

[J08] 提取年月日与星期
来源：http://dali.shuidangran.top/Article/details/gthdnsmdtr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigufen.top/Article/details/gtnebbmdnf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nwbrower.top/Article/details/gtvcuvlahk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.kuanghao11.cn/Article/details/gtxmxbvfvp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj20258.top/Article/details/gtcwnfsciv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhoulong.xyz/Article/details/gtzeqexzzk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.kuanghao11.cn/Article/details/gtfrclyjir.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhixingplan.top/Article/details/gtzxwrqqxk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.guowangkeji.top/Article/details/gtzjguheok.html

[J09] 时区处理
来源：http://dali.dianchejie.cn/Article/details/gtitisprba.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yonumen.top/Article/details/gtbbldoqkr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ivvv.top/Article/details/gtgohecdrg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gtgigulgyh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangdashe.top/Article/details/gtkdtnmrgc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenjidiqi.icu/Article/details/gtclelkolb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrpgteah.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhengqikj.top/Article/details/gtaryxvmsn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gzhubu.top/Article/details/gtzccorscp.html

[J10] 取今天 / 本月第一天
来源：http://dali.cashguo.top/Article/details/gtpeeaodni.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shangyingyoupin.top/Article/details/gtrgmsikws.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.pycfn.com/Article/details/gthrjencjs.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj20258.top/Article/details/gtatomhaer.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cdnleiting.top/Article/details/gtrddisvrl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.0kj1m.cn/Article/details/gtjhqzafec.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yvedp.cn/Article/details/gtkuwimmjf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cheryme.top/Article/details/gtfrhgfxjl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.havefunace.top/Article/details/gtbpzrkfby.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtwqyplnet.html

K. JSON 与序列化
来源：http://dali.jyoumei.cn/Article/details/gteanfcswz.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtndoatlnj.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtqnotguay.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gtfckurnrt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gtrawpxxze.html

JS:   JSON.stringify(obj)
来源：http://dali.jqgfzy.top/Article/details/gtaucwbwqw.html

TS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtvztelrcy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhiwuduotai.top/Article/details/gtqrosnqqw.html

Go:   json.Marshal(obj)
来源：http://dali.aizwys.cn/Article/details/gtriapiltm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jiagoushi.top/Article/details/gtuwcqmfks.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxinkj.top/Article/details/gtvywqmqsu.html

[K02] JSON 字符串转对象
来源：http://dali.pycfn.com/Article/details/gtswhgfhti.html

Py:   json.loads(s)
来源：http://dali.andypj.xyz/Article/details/gtvnwytqdx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.feifeiyinyue.top/Article/details/gtdjubdngh.html

JS:   JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gtewxwskhz.html

TS:   JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gtzszcmsey.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gogol.net.cn/Article/details/gtohwmmhtp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hysaishi.cn/Article/details/gtxoxdlhyy.html

Ruby: JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gtinmyazqr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuxming.cn/Article/details/gtcbenevzs.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shzxlz.cn/Article/details/gtqivnjeiy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gtyadwrxwv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gtmosmxysx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtwxpcuigm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.tianlin.xyz/Article/details/gtvuevwefw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cqqwz.cn/Article/details/gtybvzsfvp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhiwuduotai.top/Article/details/gtdmlpdaej.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yangfankeji.com/Article/details/gtzxtyocbk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jyoumei.cn/Article/details/gtvjqkhyrp.html

[K04] 读取 JSON 文件
来源：http://dali.chenlongwang.top/Article/details/gtyntomxex.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tanke756.top/Article/details/gtnfgmzvkq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ydzc1.top/Article/details/gtxluzsetp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gtjathdleq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gtrnlmoddl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gogol.net.cn/Article/details/gtywsofsdc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ybcxt.top/Article/details/gtvpuhqrvn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nanxinkj.top/Article/details/gtqdxpmcce.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtesrjgjir.html

[K05] 深拷贝对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvrfxibk.html

Py:   copy.deepcopy(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtyblubyuo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cashguo.top/Article/details/gtcutrnyuc.html

JS:   structuredClone(obj)
来源：http://dali.yuanzhike.top/Article/details/gtzaxvhwtr.html

TS:   structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gtqsfnlzll.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.birdmap.top/Article/details/gtapndsgwy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yangfankeji.com/Article/details/gtlnazzjbv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.smart0.xyz/Article/details/gtsajfxqap.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.meibo888.top/Article/details/gtixlayvhf.html

[K06] 解析 URL 查询串
来源：http://dali.redwolf501.top/Article/details/gtvydwukjx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jianghu66.top/Article/details/gtbpeaostl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ehwqpu.com/Article/details/gtxlnqgbnh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgufenzy.top/Article/details/gthwedvqtc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gteczhxmdn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shangyingyoupin.top/Article/details/gtggmbordg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gtxtrljsdz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gtbwszwloo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gtfpcofbsr.html

[K07] 进制转换
来源：http://dali.nanxinkj.top/Article/details/gtoskyiucp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtfjgioemk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yonumen.top/Article/details/gtobsahiae.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtkvpfncif.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gthpnvzwgs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtyfumjbat.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgfzy.top/Article/details/gtwozmrbbg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yonumen.top/Article/details/gtphzomlcw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sweek.top/Article/details/gtjkoxbwcv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.svipenyu.cn/Article/details/gtfrmiwphi.html

Py:   pickle.dumps(obj)
来源：http://dali.daria6918.cn/Article/details/gtkrqzzszi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jianghu66.top/Article/details/gtwsfqpdoc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258888.top/Article/details/gtjkonzgjh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gtkghkrger.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gtpaemdumk.html

Go:   encoding/gob
来源：http://dali.jinqigfzy.top/Article/details/gtjwfslyze.html

Ruby: Marshal.dump(obj)
来源：http://dali.jianghu66.top/Article/details/gtjaqiiedn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sufxvd.cn/Article/details/gtppvvqqtb.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtdkmykijz.html

L. 网络请求
来源：http://dali.yueranfly.top/Article/details/gtnxodyitn.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtcodqewzi.html

[L01] 发送 GET 请求
来源：http://dali.zhixingplan.top/Article/details/gtcqzwukhd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yanxiufei.cn/Article/details/gtjniytjkq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yvedp.cn/Article/details/gtrmgqczek.html

JS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gtdcjwkuej.html

TS:   await fetch(url)
来源：http://dali.nanxuanxn.top/Article/details/gtlhharccl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gogol.net.cn/Article/details/gtthnklslp.html

Go:   resp, err := http.Get(url)
来源：http://dali.yanxiufei.cn/Article/details/gtoansgaca.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenjidiqi.icu/Article/details/gtkvrjaosm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jqgfzy.top/Article/details/gtqntdzkep.html

[L02] 发送 POST JSON
来源：http://dali.cheryme.top/Article/details/gtycaejpwl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhengqikj.top/Article/details/gtjftfaqnp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbinykxqa.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jianghu66.top/Article/details/gtdadixpdn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.birdmap.top/Article/details/gtogrccozh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yuanzhike.top/Article/details/gtzzcdkmqc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nanxuanxn.top/Article/details/gtbcyqygas.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.guannengcc.top/Article/details/gtsujcgmnm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ehwqpu.com/Article/details/gtsuvrnucj.html

[L03] 设置自定义请求头
来源：http://dali.zdqjudy.top/Article/details/gtiebpmvou.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.andypj.xyz/Article/details/gtohbebtyh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgufenzy.top/Article/details/gtlfdkvlzb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenlongwang.top/Article/details/gtwcpsgjio.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sxryk.cn/Article/details/gtajztbuyt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hfpthk.cn/Article/details/gtgjcsuhut.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.nwbrower.top/Article/details/gtvgsrqtgb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.guowangkeji.top/Article/details/gtedrdtxur.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.snrcjt.cn/Article/details/gtfxpgthig.html

[L04] 设置超时
来源：http://dali.aizwys.cn/Article/details/gtyrureevq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hnqzz.top/Article/details/gtlxxkjbww.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinqigufen.top/Article/details/gtemnxhaza.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gtcbrxvxya.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gtknixebwz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hnxiangtu.top/Article/details/gtkobnnlaq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj20258888.top/Article/details/gtlepqwuqo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.kuanghao11.cn/Article/details/gttgfywhng.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aizwys.cn/Article/details/gtoisgiird.html

[L05] 上传文件（multipart）
来源：http://dali.yj20258888.top/Article/details/gtkbfnaszo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhongyouzk.top/Article/details/gtoyzbrfyt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hongshengwenyu.top/Article/details/gtkfgliowe.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.fengsongda.top/Article/details/gtrrcyvbid.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuetiantiany.cn/Article/details/gthyhgdxwv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.redwolf501.top/Article/details/gtcpwjyqja.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hongshengwenyu.top/Article/details/gtlkwayxsq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hysaishi.cn/Article/details/gtjtyetsqp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hammf.cn/Article/details/gttogcvtqb.html

[L06] 解析响应为 JSON
来源：http://dali.yuxming.cn/Article/details/gtazrelbyl.html

Py:   resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxxsuaixq.html

PHP:  json_decode($body, true);
来源：http://dali.dianchejie.cn/Article/details/gtagglbtyw.html

JS:   await resp.json()
来源：http://dali.xylfe.cn/Article/details/gttvldxnjw.html

TS:   await resp.json()
来源：http://dali.fzhhl.top/Article/details/gtdhxubfgx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gtjzkpkeue.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.andypj.xyz/Article/details/gtjbayniao.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gaohongyu789.top/Article/details/gtfyefhbrj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ppjwa.cn/Article/details/gtrciazite.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwjbqcoq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhixingplan.top/Article/details/gtlkzolmos.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.quarkkingdee.top/Article/details/gtfnjpveoa.html

JS:   resp.ok;  resp.status
来源：http://dali.yuanzhike.top/Article/details/gtswbvclqv.html

TS:   resp.ok;  resp.status
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttpcjwaqy.html

Java: resp.statusCode()
来源：http://dali.zhongyouzk.top/Article/details/gtdschngcy.html

Go:   resp.StatusCode
来源：http://dali.jqgfzy.top/Article/details/gtmagdhjtu.html

Ruby: resp.code.to_i
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvzejcek.html

C#:   (int)resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gtjagxpmdk.html

[L08] 并发请求多个地址
来源：http://dali.zdqjudy.top/Article/details/gtlxomqmdr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinqigfzy.top/Article/details/gtccoheayj.html

PHP:  curl_multi_init() 系列
来源：http://dali.c1oappe.top/Article/details/gtivmafrqu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gtcnjvzswn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gticylckhv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangdashe.top/Article/details/gtlcmevilz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenjidiqi.icu/Article/details/gtxiejtggi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cqqwz.cn/Article/details/gthslhufhs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gthaekitiu.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtmdggjake.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj20258.top/Article/details/gtykiusiaa.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtokscrnie.html

[M01] 读取命令行参数
来源：http://dali.guannengcc.top/Article/details/gtafhctzux.html

Py:   sys.argv[1:]
来源：http://dali.xylfe.cn/Article/details/gtxaeupczl.html

PHP:  $argv;  $argc;
来源：http://dali.yanxiufei.cn/Article/details/gtjbhzupwi.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gttowflwok.html

TS:   process.argv.slice(2)
来源：http://dali.shzxlz.cn/Article/details/gtjihxoyej.html

Java: args 数组（main 方法参数）
来源：http://dali.fengsongda.top/Article/details/gtlnzsrcef.html

Go:   os.Args[1:]
来源：http://dali.zhoulong.xyz/Article/details/gtxnsmaxqf.html

Ruby: ARGV
来源：http://dali.nanxinkj.top/Article/details/gtdodjgpot.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jqgufenzy.top/Article/details/gtutvmylpa.html

[M02] 读取环境变量
来源：http://dali.yueranfly.top/Article/details/gtteomnwzj.html

Py:   os.environ.get("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtrfismeit.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pycfn.com/Article/details/gtwzkewdvg.html

JS:   process.env.HOME
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbhzkcade.html

TS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gtniynjhci.html

Java: System.getenv("HOME")
来源：http://dali.iojbl.cn/Article/details/gtabhyrofk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtxxahxtqc.html

Ruby: ENV["HOME"]
来源：http://dali.nanxuanxn.top/Article/details/gthyfaunvh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtlqqkgvrk.html

[M03] 执行外部命令
来源：http://dali.c1oappe.top/Article/details/gtpmqeqthw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zycfv.cn/Article/details/gtjshihete.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.pycfn.com/Article/details/gthfxigdqe.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gtrspfnykq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhongyouzk.top/Article/details/gtdsqkontn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jyoumei.cn/Article/details/gtysarvlzo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jqgufenzy.top/Article/details/gtrbprkfml.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhiwuduotai.top/Article/details/gtnzsflvtq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.pycfn.com/Article/details/gtmswfoynj.html

[M04] 获取当前工作目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtdsiwghff.html

Py:   os.getcwd()
来源：http://dali.hammf.cn/Article/details/gtuacuzblm.html

PHP:  getcwd();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkeflqllu.html

JS:   process.cwd()
来源：http://dali.jqgufenzy.top/Article/details/gtigvruukq.html

TS:   process.cwd()
来源：http://dali.guowangkeji.top/Article/details/gtsxnngsot.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.guowangkeji.top/Article/details/gtvakzrrrc.html

Go:   os.Getwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtutttayyg.html

Ruby: Dir.pwd
来源：http://dali.fengsongda.top/Article/details/gttpyvdkho.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokemibhv.html

[M05] 设置退出码
来源：http://dali.yj20258888.top/Article/details/gtkcrzukiw.html

Py:   sys.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtthrudcgq.html

PHP:  exit(1);
来源：http://dali.sxryk.cn/Article/details/gtztdybitn.html

JS:   process.exit(1)
来源：http://dali.bjfxy.top/Article/details/gttsopmwys.html

TS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtroxdvzbi.html

Java: System.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtykebnger.html

Go:   os.Exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtblzywqvr.html

Ruby: exit 1
来源：http://dali.tian-w.cn/Article/details/gtrqvmjvmd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.guannengcc.top/Article/details/gtymynytmz.html

[M06] 向标准错误输出
来源：http://dali.aizwys.cn/Article/details/gtnvjulhwx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.pycfn.com/Article/details/gtqqudamvc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.havefunace.top/Article/details/gtmecozczn.html

JS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gtrprldqii.html

TS:   console.error("err")
来源：http://dali.xuanzx.com/Article/details/gtaedheypn.html

Java: System.err.println("err")
来源：http://dali.daria6918.cn/Article/details/gtthrqepbi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daria6918.cn/Article/details/gtnvqciaga.html

Ruby: warn "err"
来源：http://dali.zdqjudy.top/Article/details/gtuwmaernq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cheryme.top/Article/details/gtlboagoms.html

[M07] 判断是否为主入口
来源：http://dali.gotoacloud.top/Article/details/gteqpifvxx.html

Py:   if __name__ == "__main__":
来源：http://dali.havefunace.top/Article/details/gtgswhyuuo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.redwolf501.top/Article/details/gtichccdne.html

JS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gtbiwabrfm.html

TS:   require.main === module
来源：http://dali.ydzc1.top/Article/details/gttcmmrqbz.html

Java: public static void main(String[] args)
来源：http://dali.jinqigufen.top/Article/details/gtwfjjpora.html

Go:   func main()
来源：http://dali.haohaochexian.top/Article/details/gtwocphifq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.pengpengdd.cyou/Article/details/gtamygjnio.html

C#:   static void Main(string[] args)
来源：http://dali.shzxlz.cn/Article/details/gtptobwlbv.html

[M08] 获取系统与运行时信息
来源：http://dali.hongshengwenyu.top/Article/details/gtfksvtltn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj202588.top/Article/details/gtftaywnko.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tanke756.top/Article/details/gtfinjvrry.html

JS:   process.platform;  process.version
来源：http://dali.ivvv.top/Article/details/gtasqzbsig.html

TS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gtinzipqbx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sweek.top/Article/details/gtgdamyayp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ehwqpu.com/Article/details/gtjrcpntvb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.svipenyu.cn/Article/details/gtoeljabpf.html


<!-- 参考信息 -->