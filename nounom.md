代发 wailian999

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jianghu66.top/Article/details/gtxohghukm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sysykeji.top/Article/details/gtnzaxnrti.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenlongwang.top/Article/details/gtkpgiyedw.html

TS:   d.toISOString()
来源：http://dali.zycfv.cn/Article/details/gtgrkfaikk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xinyue.icu/Article/details/gtpdtyabxu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cashguo.top/Article/details/gtnxrbmphk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guannengcc.top/Article/details/gtdxquwtoa.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cdnleiting.top/Article/details/gtjnjhvusa.html

[J03] 字符串解析为日期
来源：http://dali.meibo888.top/Article/details/gtfqqjwlcs.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jianghu66.top/Article/details/gtodelglis.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yuanzhike.top/Article/details/gthijtsicf.html

JS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtcrxdirxi.html

TS:   new Date("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtqgeymyfd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gthzghfjzy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtorpsqpkm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtdxajkohi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhixingplan.top/Article/details/gtmbwwbmku.html

[J04] 时间戳与日期互转
来源：http://dali.gzhubu.top/Article/details/gtbieexjxw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gogol.net.cn/Article/details/gtyantyaaq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shangyingyoupin.top/Article/details/gtpdlwmvot.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hammf.cn/Article/details/gttqyzqduw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.haohaochexian.top/Article/details/gtajnfucfu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.aibaodan.cn/Article/details/gtsvtcponp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.svipenyu.cn/Article/details/gtrsdggxoo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daxiang520.top/Article/details/gtpswvvmgm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.havefunace.top/Article/details/gtonydflmz.html

[J05] 时间加减（加 7 天）
来源：http://dali.xinyue.icu/Article/details/gthhvvldgs.html

Py:   now + timedelta(days=7)
来源：http://dali.xinyue.icu/Article/details/gtgxgiiyaf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jyoumei.cn/Article/details/gtkvrqtknm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.9152youxi.cn/Article/details/gtxkjnxsjf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxuanxn.top/Article/details/gtzvdzzkpp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.havefunace.top/Article/details/gtblbzivcv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdcaarglo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhoulong.xyz/Article/details/gtigkikobm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxinkj.top/Article/details/gthfhtnytz.html

[J06] 计算两时间之差
来源：http://dali.kuanghao11.cn/Article/details/gtslvelqlf.html

Py:   (end - start).total_seconds()
来源：http://dali.gzhubu.top/Article/details/gtovfnhhwz.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenjidiqi.icu/Article/details/gtnepavdqq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.guowangkeji.top/Article/details/gtsgybtdou.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sweek.top/Article/details/gtsppedcjq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yonumen.top/Article/details/gtxouxxtdy.html

Go:   end.Sub(start).Hours()
来源：http://dali.yueranfly.top/Article/details/gtmivsipnj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.daxiang520.top/Article/details/gtrabvachu.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenzaomai.com/Article/details/gtxutmfxxe.html

[J07] 比较两个日期
来源：http://dali.xuetiantiany.cn/Article/details/gtxacdsgax.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gtqqhjflkd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.c1oappe.top/Article/details/gtuenpbqme.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.dashuyun.cn/Article/details/gtcvmikswr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gaohongyu789.top/Article/details/gtcwhwjqnp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.c1oappe.top/Article/details/gtgayavanf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.haohaochexian.top/Article/details/gtlyxgtyam.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gtkdxtkfal.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtindiqmec.html

[J08] 提取年月日与星期
来源：http://dali.dashuyun.cn/Article/details/gtitrrpezm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.snrcjt.cn/Article/details/gtmpblmapk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yonumen.top/Article/details/gtlnmebndp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.redwolf501.top/Article/details/gtovrlrypw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.0kj1m.cn/Article/details/gthsrmaszg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuxming.cn/Article/details/gtghmcpmge.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhoulong.xyz/Article/details/gtnywdvknz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nanxuanxn.top/Article/details/gtxspcpbff.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shangyingyoupin.top/Article/details/gtmufmrafg.html

[J09] 时区处理
来源：http://dali.cdnleiting.top/Article/details/gthlmcvtjv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sysykeji.top/Article/details/gtepnilhfw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenjidiqi.icu/Article/details/gtwzsphwum.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gtildthtgm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.kuanghao11.cn/Article/details/gtdhgaxuiw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jianghu66.top/Article/details/gtvmnyjgar.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ybcxt.top/Article/details/gtxmigytyu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shuidangran.top/Article/details/gtwlubtpme.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tian-w.cn/Article/details/gtcylulxuw.html

[J10] 取今天 / 本月第一天
来源：http://dali.kuanghao11.cn/Article/details/gtqidfshlb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.316326.xyz/Article/details/gthsrnicbp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj20258888.top/Article/details/gttdeywshc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daxiang520.top/Article/details/gtvfaacggj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmgsuopes.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ydzc1.top/Article/details/gtzwuflofa.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj202588.top/Article/details/gtoaravqei.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yueranfly.top/Article/details/gtahnsxsgq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhoulong.xyz/Article/details/gtfyyjecpn.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtkrnyrmek.html

K. JSON 与序列化
来源：http://dali.xinyue.icu/Article/details/gtjambezay.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtpjywlnku.html

[K01] 对象转 JSON 字符串
来源：http://dali.iojbl.cn/Article/details/gtiowznfok.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zdqjudy.top/Article/details/gtpkckpmcg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nwbrower.top/Article/details/gtivjnlqal.html

JS:   JSON.stringify(obj)
来源：http://dali.nwbrower.top/Article/details/gtazlhllbh.html

TS:   JSON.stringify(obj)
来源：http://dali.nwbrower.top/Article/details/gtbgixltej.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhongyouzk.top/Article/details/gtcvppdfjf.html

Go:   json.Marshal(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtopwrshrh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shangyingyoupin.top/Article/details/gtsnrviirq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlpciexs.html

[K02] JSON 字符串转对象
来源：http://dali.dianchejie.cn/Article/details/gtkdtyqwam.html

Py:   json.loads(s)
来源：http://dali.dianchejie.cn/Article/details/gtmwwjkwqk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.feifeiyinyue.top/Article/details/gtgddfujbs.html

JS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gtpqaefkqe.html

TS:   JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gteiyvdnod.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ydzc1.top/Article/details/gtffkslozv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.pengpengdd.cyou/Article/details/gtgybrouaz.html

Ruby: JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gtjsxppgtf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258.top/Article/details/gtsnhmrfcw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sufxvd.cn/Article/details/gtpjqvevii.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gtdzwjtkjs.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.9152youxi.cn/Article/details/gtdhhtfoxx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xylfe.cn/Article/details/gtgzfmlxqu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gtffzluvng.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cashguo.top/Article/details/gtnbzitkxq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cashguo.top/Article/details/gtceedyvzu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwyrpowni.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hnqzz.top/Article/details/gtratxmxpw.html

[K04] 读取 JSON 文件
来源：http://dali.jinqigfzy.top/Article/details/gtuvmszdll.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gogol.net.cn/Article/details/gtuntyefoy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hammf.cn/Article/details/gtownahzwu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hfpthk.cn/Article/details/gtomrgxigl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gtdareyloo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shuidangran.top/Article/details/gtvcwmmtrm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gthcvhpnlr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangshuangyany.cn/Article/details/gtbtmlqevk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xinyue.icu/Article/details/gtikytilcw.html

[K05] 深拷贝对象
来源：http://dali.meibo888.top/Article/details/gtoohcrxih.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gteurwkbua.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cqqwz.cn/Article/details/gtazeyjuwd.html

JS:   structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gtblcdjqyn.html

TS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtnmqgcntu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zdqjudy.top/Article/details/gtvftakgfb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinqigfzy.top/Article/details/gtdbpztmkr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hfpthk.cn/Article/details/gtocvwcvyr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zdqjudy.top/Article/details/gthzyzkcje.html

[K06] 解析 URL 查询串
来源：http://dali.sxryk.cn/Article/details/gtsgfjjoch.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gtureyjlat.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aibaodan.cn/Article/details/gtsgtsvpyw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cqqwz.cn/Article/details/gtfjyutgye.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xziqi.cn/Article/details/gtkixijnbx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinqigfzy.top/Article/details/gtzmjnhsnk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtioxhcntx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gtqiimfnzw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gtslkcvlom.html

[K07] 进制转换
来源：http://dali.nwbrower.top/Article/details/gtrcbsmowb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtgkwecyeq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jianghu66.top/Article/details/gtikfjhqvl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtkmyzixkg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtozfaszcu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtpyryslhc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj20258888.top/Article/details/gtihyykblv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ydzc1.top/Article/details/gtwbrptpib.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtlhjpmqit.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jqgfzy.top/Article/details/gtcibrggyw.html

Py:   pickle.dumps(obj)
来源：http://dali.sweek.top/Article/details/gtgztxcxka.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.daria6918.cn/Article/details/gtsjnawirj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cdnleiting.top/Article/details/gtusxqjams.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.fzhhl.top/Article/details/gtfporowhx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gotoacloud.top/Article/details/gtthxvzlcw.html

Go:   encoding/gob
来源：http://dali.feifeiyinyue.top/Article/details/gtxvuyawip.html

Ruby: Marshal.dump(obj)
来源：http://dali.iojbl.cn/Article/details/gtosfeaujv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gtpwcitiaq.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtmuyfgfjg.html

L. 网络请求
来源：http://dali.zhixingplan.top/Article/details/gtdpneqzqg.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtideuhera.html

[L01] 发送 GET 请求
来源：http://dali.hywenlv.cn/Article/details/gtlilsnydi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnxiangtu.top/Article/details/gtabawrtkr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjeuzmwe.html

JS:   await fetch(url)
来源：http://dali.hfpthk.cn/Article/details/gtwxeuxsck.html

TS:   await fetch(url)
来源：http://dali.aibaodan.cn/Article/details/gtztfkniht.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tanke756.top/Article/details/gtlghcbtqk.html

Go:   resp, err := http.Get(url)
来源：http://dali.sxryk.cn/Article/details/gtubztxhuo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shangyingyoupin.top/Article/details/gtwnjxbyee.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ybcxt.top/Article/details/gtesvgqslp.html

[L02] 发送 POST JSON
来源：http://dali.tianlin.xyz/Article/details/gtqrnexwxk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tian-w.cn/Article/details/gtrrwetzcm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.wangshuangyany.cn/Article/details/gtxksipbln.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.kuanghao11.cn/Article/details/gtdbacalxh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gtqexfgjcj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.daxiang520.top/Article/details/gtjqeakzsb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgohnirtu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sysykeji.top/Article/details/gtxeirdzpi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jiagoushi.top/Article/details/gtvikrdpie.html

[L03] 设置自定义请求头
来源：http://dali.ybcxt.top/Article/details/gtsbvhitkx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.pengpengdd.cyou/Article/details/gtetnwnmta.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenlongwang.top/Article/details/gtuzdtcatu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigfzy.top/Article/details/gtbbwvclzh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gtmrjdhsgt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.birdmap.top/Article/details/gthrgduuwc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gttowovgwg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jqgufenzy.top/Article/details/gthjlvnxup.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tanke756.top/Article/details/gtsjrhrfbs.html

[L04] 设置超时
来源：http://dali.yongpay.top/Article/details/gtpcqqsmow.html

Py:   requests.get(url, timeout=5)
来源：http://dali.0kj1m.cn/Article/details/gtcdsenvia.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.redwolf501.top/Article/details/gtyffqudid.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gtcrmnathl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yueranfly.top/Article/details/gtcilyvbvx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.guowangkeji.top/Article/details/gtvnpntvfu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sweek.top/Article/details/gtenzrxwxg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.snrcjt.cn/Article/details/gtlxubzoxp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cheryme.top/Article/details/gtamkdmwli.html

[L05] 上传文件（multipart）
来源：http://dali.316326.xyz/Article/details/gtazubbkep.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.guannengcc.top/Article/details/gtuzfxuqxv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejmwlpjt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnxiangtu.top/Article/details/gthjtdcony.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gtqfnmeymu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tanke756.top/Article/details/gtiuaorzgu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jqgufenzy.top/Article/details/gtsczqovoo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.316326.xyz/Article/details/gtfrqxhkow.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaoxkpwch.html

[L06] 解析响应为 JSON
来源：http://dali.zhongyouzk.top/Article/details/gtxmsmzduq.html

Py:   resp.json()
来源：http://dali.aibaodan.cn/Article/details/gtdyqjwyem.html

PHP:  json_decode($body, true);
来源：http://dali.redwolf501.top/Article/details/gtpnrsxtes.html

JS:   await resp.json()
来源：http://dali.cdnleiting.top/Article/details/gtoqkchxsf.html

TS:   await resp.json()
来源：http://dali.yj202588.top/Article/details/gtbcgtgoaz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtqrpcjvyd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.9152youxi.cn/Article/details/gtxzhpeycr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.9152youxi.cn/Article/details/gtjdmbmfvm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ydzc1.top/Article/details/gtfoqwksgu.html

[L07] 处理 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gtjkesaljr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvpaijsz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xziqi.cn/Article/details/gttqxwepiq.html

JS:   resp.ok;  resp.status
来源：http://dali.0kj1m.cn/Article/details/gtvxhbopmk.html

TS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gtvrthxzci.html

Java: resp.statusCode()
来源：http://dali.yuxming.cn/Article/details/gtojtwupth.html

Go:   resp.StatusCode
来源：http://dali.birdmap.top/Article/details/gtvegnpzia.html

Ruby: resp.code.to_i
来源：http://dali.hammf.cn/Article/details/gthzitmqib.html

C#:   (int)resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gtbbrlrxru.html

[L08] 并发请求多个地址
来源：http://dali.fzhhl.top/Article/details/gtrhtuemta.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tian-w.cn/Article/details/gtmthtfxdq.html

PHP:  curl_multi_init() 系列
来源：http://dali.sweek.top/Article/details/gtkqqacnup.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gtkqvjhsto.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gttdvbvybl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhoulong.xyz/Article/details/gtluccacgj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hysaishi.cn/Article/details/gtvehqyzju.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.wangdashe.top/Article/details/gtwkhebjvr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jqgfzy.top/Article/details/gtikwkzyev.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtikdcodcv.html

M. 命令行 / 进程 / 环境
来源：http://dali.ehwqpu.com/Article/details/gtdctvizdn.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtqyjjybzp.html

[M01] 读取命令行参数
来源：http://dali.tian-w.cn/Article/details/gtambddngr.html

Py:   sys.argv[1:]
来源：http://dali.guannengcc.top/Article/details/gtndabaxsg.html

PHP:  $argv;  $argc;
来源：http://dali.gotoacloud.top/Article/details/gtyoibzaqr.html

JS:   process.argv.slice(2)
来源：http://dali.svipenyu.cn/Article/details/gtcznfghsb.html

TS:   process.argv.slice(2)
来源：http://dali.wangshuangyany.cn/Article/details/gtrqcgrncy.html

Java: args 数组（main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gtifbgnnzg.html

Go:   os.Args[1:]
来源：http://dali.zhoulong.xyz/Article/details/gtjwoktpyj.html

Ruby: ARGV
来源：http://dali.feifeiyinyue.top/Article/details/gttuytkput.html

C#:   args 数组（Main 方法参数）
来源：http://dali.birdmap.top/Article/details/gtzmlqabob.html

[M02] 读取环境变量
来源：http://dali.jyoumei.cn/Article/details/gtuvnqgsid.html

Py:   os.environ.get("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtbaevfddw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gtcwhxclyj.html

JS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gtaozqlycm.html

TS:   process.env.HOME
来源：http://dali.cdnleiting.top/Article/details/gtechcszwj.html

Java: System.getenv("HOME")
来源：http://dali.zycfv.cn/Article/details/gteaeoolly.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtxuzgifie.html

Ruby: ENV["HOME"]
来源：http://dali.daxiang520.top/Article/details/gthszchnfu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtvutdqxch.html

[M03] 执行外部命令
来源：http://dali.aizwys.cn/Article/details/gtsbjhlbpi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daria6918.cn/Article/details/gtbqhxbfvx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.smart0.xyz/Article/details/gtkoxjoihb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gtmmkyctpq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.svipenyu.cn/Article/details/gtfgdsiwee.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.havefunace.top/Article/details/gtjkkgcnmj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sweek.top/Article/details/gtarnchpsl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinghuilouyu.cn/Article/details/gttyijrucw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hammf.cn/Article/details/gtbjyfencc.html

[M04] 获取当前工作目录
来源：http://dali.kuanghao11.cn/Article/details/gtudfncohr.html

Py:   os.getcwd()
来源：http://dali.gzhubu.top/Article/details/gtckfzeiou.html

PHP:  getcwd();
来源：http://dali.xuanzx.com/Article/details/gtmfikqpnl.html

JS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gtlytmmmno.html

TS:   process.cwd()
来源：http://dali.jlsjyb.cn/Article/details/gtqjazjjrm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhixingplan.top/Article/details/gtcxeurmzi.html

Go:   os.Getwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfjoadvz.html

Ruby: Dir.pwd
来源：http://dali.vqdsnc.cn/Article/details/gtjminonte.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuetiantiany.cn/Article/details/gtyqvzyidq.html

[M05] 设置退出码
来源：http://dali.hywenlv.cn/Article/details/gtckuaelev.html

Py:   sys.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtykuuomgn.html

PHP:  exit(1);
来源：http://dali.kuanghao11.cn/Article/details/gttxcnivba.html

JS:   process.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtlrlsklbf.html

TS:   process.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtqiygdqjb.html

Java: System.exit(1)
来源：http://dali.redwolf501.top/Article/details/gteeybdzbu.html

Go:   os.Exit(1)
来源：http://dali.wangdashe.top/Article/details/gtlvknpqja.html

Ruby: exit 1
来源：http://dali.hnxiangtu.top/Article/details/gtqvspjisj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shzxlz.cn/Article/details/gtkolrcjwt.html

[M06] 向标准错误输出
来源：http://dali.tianlin.xyz/Article/details/gtkjthbasl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.birdmap.top/Article/details/gtcwjsslij.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gtsspbqppg.html

JS:   console.error("err")
来源：http://dali.sweek.top/Article/details/gtkuctvqwl.html

TS:   console.error("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthyimpdei.html

Java: System.err.println("err")
来源：http://dali.sufxvd.cn/Article/details/gthfvmiwtk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pycfn.com/Article/details/gtvboqlmau.html

Ruby: warn "err"
来源：http://dali.chenzaomai.com/Article/details/gtcrhgejtu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.316326.xyz/Article/details/gtmkyazmnl.html

[M07] 判断是否为主入口
来源：http://dali.haohaochexian.top/Article/details/gtfbrejmgu.html

Py:   if __name__ == "__main__":
来源：http://dali.zhongyouzk.top/Article/details/gtxkjckzrd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinqigfzy.top/Article/details/gtuxbneiuh.html

JS:   require.main === module
来源：http://dali.pengpengdd.cyou/Article/details/gtdhxrciqi.html

TS:   require.main === module
来源：http://dali.dianchejie.cn/Article/details/gtfsfiktbk.html

Java: public static void main(String[] args)
来源：http://dali.gogol.net.cn/Article/details/gtanzvmqvm.html

Go:   func main()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpybbvjt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jiagoushi.top/Article/details/gtcezjpimb.html

C#:   static void Main(string[] args)
来源：http://dali.zdqjudy.top/Article/details/gtvbvjbxsy.html

[M08] 获取系统与运行时信息
来源：http://dali.0kj1m.cn/Article/details/gtahenhevw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xylfe.cn/Article/details/gtmrzrfwom.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.pycfn.com/Article/details/gtopwdbacw.html

JS:   process.platform;  process.version
来源：http://dali.daria6918.cn/Article/details/gtbfosqhye.html


<!-- 参考信息 -->