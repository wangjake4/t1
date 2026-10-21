代发 wailian999

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cheryme.top/Article/details/gtgpzjpfjh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gtkjiniahf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj20258.top/Article/details/gtbekatcox.html

TS:   d.toISOString()
来源：http://dali.yj202588.top/Article/details/gtqbnzewcp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tanke756.top/Article/details/gtcohcjkmu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenzaomai.com/Article/details/gtathgpccy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwcklhqdt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cheryme.top/Article/details/gtxzornfeq.html

[J03] 字符串解析为日期
来源：http://dali.xziqi.cn/Article/details/gtuwzcktdf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jyoumei.cn/Article/details/gtnkprqenh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sysykeji.top/Article/details/gtsqfdwomb.html

JS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtvgkxmzxh.html

TS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtsrymqfar.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtnkkeddut.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtaiuzuhcl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gttkfszmsd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nanxuanxn.top/Article/details/gtyvavnkln.html

[J04] 时间戳与日期互转
来源：http://dali.pengpengdd.cyou/Article/details/gtvbkvukud.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtfkqeqmdl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jiagoushi.top/Article/details/gtjfgvzagk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shuidangran.top/Article/details/gtroncbuev.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xylfe.cn/Article/details/gtiwnexqco.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.daxiang520.top/Article/details/gtcglodlyu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zdqjudy.top/Article/details/gtfjyfesdj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xziqi.cn/Article/details/gtudobptod.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.aizwys.cn/Article/details/gtrpdnybel.html

[J05] 时间加减（加 7 天）
来源：http://dali.iojbl.cn/Article/details/gtiggkrwrm.html

Py:   now + timedelta(days=7)
来源：http://dali.xylfe.cn/Article/details/gtvjvjgwdo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xuanzx.com/Article/details/gtyvdvgtut.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guowangkeji.top/Article/details/gtdqiabolo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigfzy.top/Article/details/gtcbxggwuo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yuxming.cn/Article/details/gtwjzjufzi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.quarkkingdee.top/Article/details/gtutcuqhoh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hfpthk.cn/Article/details/gtpornjkkn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xylfe.cn/Article/details/gtrrqcovfq.html

[J06] 计算两时间之差
来源：http://dali.gotoacloud.top/Article/details/gthjfxkmyq.html

Py:   (end - start).total_seconds()
来源：http://dali.ppjwa.cn/Article/details/gtmxhqlmij.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnqzz.top/Article/details/gteqlesjjb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhongyouzk.top/Article/details/gthqfazqff.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenzaomai.com/Article/details/gtkugvzyoz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aibaodan.cn/Article/details/gttyupkrzl.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuanzx.com/Article/details/gtzwyuidlz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gogol.net.cn/Article/details/gtugzkxate.html

C#:   (end - start).TotalSeconds
来源：http://dali.andypj.xyz/Article/details/gtkbiopcyu.html

[J07] 比较两个日期
来源：http://dali.zycfv.cn/Article/details/gtxcmvduca.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gturylrzxq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hysaishi.cn/Article/details/gtiscezbyh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cqqwz.cn/Article/details/gtqthpkgju.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gtfgwtvljh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cdnleiting.top/Article/details/gtkkatiboz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pycfn.com/Article/details/gtggpsnlmx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gtfrpcgrfj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gtpfencjwc.html

[J08] 提取年月日与星期
来源：http://dali.zhoulong.xyz/Article/details/gtnzcjmsmy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sweek.top/Article/details/gthxwkezpc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.vqdsnc.cn/Article/details/gtwddaledi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.iojbl.cn/Article/details/gtqhhaxvkf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cdnleiting.top/Article/details/gtgmidmxfd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cdnleiting.top/Article/details/gtngdaihkg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yvedp.cn/Article/details/gtvulfwmus.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.pycfn.com/Article/details/gtmvmdpusi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj20258888.top/Article/details/gtkfmvmmvl.html

[J09] 时区处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkuzagrob.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jqgfzy.top/Article/details/gttcakcwcj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrrxkodd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gtnmgdjond.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sysykeji.top/Article/details/gtsfxmtomq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jqgfzy.top/Article/details/gttkruhpik.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258888.top/Article/details/gtiesllzrt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dashuyun.cn/Article/details/gtsguoxeze.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gogol.net.cn/Article/details/gtmkifspzi.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuanzhike.top/Article/details/gttxwrnepp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hammf.cn/Article/details/gtbhzumtbj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuxming.cn/Article/details/gthnebthij.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gzhubu.top/Article/details/gtyawvzexw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xziqi.cn/Article/details/gtsvzqrqeq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhoulong.xyz/Article/details/gtkdzkfgud.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.bjfxy.top/Article/details/gtezneoumz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fzhhl.top/Article/details/gtlkchpgiw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cucudq.cn/Article/details/gtwizmwvqa.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtuhmerahv.html

K. JSON 与序列化
来源：http://dali.svipenyu.cn/Article/details/gtfjidpals.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtleaouhgs.html

[K01] 对象转 JSON 字符串
来源：http://dali.cqqwz.cn/Article/details/gtwnhomlpk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nwbrower.top/Article/details/gtlhinfvjn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xinyue.icu/Article/details/gtphxppnfx.html

JS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfwcccys.html

TS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gtdyyfpgvy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shzxlz.cn/Article/details/gtjwekiqjf.html

Go:   json.Marshal(obj)
来源：http://dali.yongpay.top/Article/details/gtsolyvpxu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xylfe.cn/Article/details/gtivlomtwx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ydzc1.top/Article/details/gtdtpoldvg.html

[K02] JSON 字符串转对象
来源：http://dali.meibo888.top/Article/details/gtwrvmuzhb.html

Py:   json.loads(s)
来源：http://dali.iojbl.cn/Article/details/gtogdoktjp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonbdsqpg.html

JS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtvltallpd.html

TS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gtuzyjpbjb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.andypj.xyz/Article/details/gtenywtqcw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sweek.top/Article/details/gtvhrqhwhd.html

Ruby: JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gtjzzscviu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ppjwa.cn/Article/details/gtqfclifci.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xuetiantiany.cn/Article/details/gthbltbwfi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gtnavysczp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.vqdsnc.cn/Article/details/gtdkxrlkkm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtdicysoxs.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ybcxt.top/Article/details/gtusnphbcz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.dashuyun.cn/Article/details/gtyqpwliyt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cashguo.top/Article/details/gtdxvzpfjc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cqqwz.cn/Article/details/gtalyjrmzm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhengqikj.top/Article/details/gttetjtqvj.html

[K04] 读取 JSON 文件
来源：http://dali.hfpthk.cn/Article/details/gtfgflyugz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiofpyovg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aibaodan.cn/Article/details/gtvelbsofo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jiagoushi.top/Article/details/gtsfpuhylp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtebguem.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tian-w.cn/Article/details/gtyeghjnus.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nanxuanxn.top/Article/details/gtrppqdbzv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.smart0.xyz/Article/details/gtyzsjzhxq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yvedp.cn/Article/details/gtdavemwjm.html

[K05] 深拷贝对象
来源：http://dali.zhixingplan.top/Article/details/gtycfwhnrf.html

Py:   copy.deepcopy(obj)
来源：http://dali.yonumen.top/Article/details/gtjsyetpfu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.c1oappe.top/Article/details/gtrqjmzmky.html

JS:   structuredClone(obj)
来源：http://dali.yuanzhike.top/Article/details/gtxvlwgvea.html

TS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gtbcjfzvvn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sxryk.cn/Article/details/gtazouzwvi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.dashuyun.cn/Article/details/gtiycwjfzw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sufxvd.cn/Article/details/gtgusgwhsb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.c1oappe.top/Article/details/gtkxjfausi.html

[K06] 解析 URL 查询串
来源：http://dali.jinqigufen.top/Article/details/gtxuzdgqzo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.snrcjt.cn/Article/details/gtqpvdiort.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxinkj.top/Article/details/gtajqcacno.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258.top/Article/details/gtisstiwfv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fzhhl.top/Article/details/gtucchpqil.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.mhx1999.top/Article/details/gtjzealexz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gtrjgmjqoj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gtzzumiwix.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hfpthk.cn/Article/details/gtyzuimmbi.html

[K07] 进制转换
来源：http://dali.aibaodan.cn/Article/details/gtiupxhzzi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtcledounf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhongyouzk.top/Article/details/gtzjpnlwmy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtolgztnjd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtgoiwhbpb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgosaqig.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shzxlz.cn/Article/details/gtbrnqkqen.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hysaishi.cn/Article/details/gteililarr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtlfggatio.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pycfn.com/Article/details/gtmwfoutau.html

Py:   pickle.dumps(obj)
来源：http://dali.yongpay.top/Article/details/gthkelopfc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yuanzhike.top/Article/details/gtyuyubzdf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtkmndrxqw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.kuanghao11.cn/Article/details/gtfwawwffw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgfzy.top/Article/details/gtifdlfgdz.html

Go:   encoding/gob
来源：http://dali.cashguo.top/Article/details/gtajqqyomu.html

Ruby: Marshal.dump(obj)
来源：http://dali.yangfankeji.com/Article/details/gthaikssff.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gtgxudfycc.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtawcfqrmb.html

L. 网络请求
来源：http://dali.zhoulong.xyz/Article/details/gtrwpxuxzu.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkxhppitw.html

[L01] 发送 GET 请求
来源：http://dali.ydzc1.top/Article/details/gtpwmpyreg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinqigfzy.top/Article/details/gtosbhufcb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yangfankeji.com/Article/details/gtehtblljj.html

JS:   await fetch(url)
来源：http://dali.yanxiufei.cn/Article/details/gtcosmzrly.html

TS:   await fetch(url)
来源：http://dali.chenzaomai.com/Article/details/gtindtbumd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj20258888.top/Article/details/gtjoebqvwu.html

Go:   resp, err := http.Get(url)
来源：http://dali.jlsjyb.cn/Article/details/gtyloqatej.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.snrcjt.cn/Article/details/gtghibxtam.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cashguo.top/Article/details/gtqdxuhkkb.html

[L02] 发送 POST JSON
来源：http://dali.fzhhl.top/Article/details/gtmzwdhowb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenlongwang.top/Article/details/gtlvlsahxq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwbvsdia.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.316326.xyz/Article/details/gtslmuyyrs.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gaohongyu789.top/Article/details/gtgqobncjk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.guannengcc.top/Article/details/gtijlzwwus.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yvedp.cn/Article/details/gtkfgnocmw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hfpthk.cn/Article/details/gtsgcifjsh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.bjfxy.top/Article/details/gtkhigngxm.html

[L03] 设置自定义请求头
来源：http://dali.0kj1m.cn/Article/details/gtubpjnyze.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ydzc1.top/Article/details/gtggbaagcv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.andypj.xyz/Article/details/gtsafxalnt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gtbpizqnkd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xziqi.cn/Article/details/gtzuaaqnbm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.vqdsnc.cn/Article/details/gtknjrceac.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.snrcjt.cn/Article/details/gtkgjgncff.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gotoacloud.top/Article/details/gtqxstdryw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gtffzbokbs.html

[L04] 设置超时
来源：http://dali.smart0.xyz/Article/details/gtawkmuain.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gaohongyu789.top/Article/details/gtgrwrkzaq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fengsongda.top/Article/details/gtkrgpyorf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxinkj.top/Article/details/gtfhpiswxs.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gtguglabzv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.haohaochexian.top/Article/details/gterpmoftp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhixingplan.top/Article/details/gtwllkojte.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jqgufenzy.top/Article/details/gtfjczbgqz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ybcxt.top/Article/details/gtszopgpgr.html

[L05] 上传文件（multipart）
来源：http://dali.ybcxt.top/Article/details/gtrcfcpufu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnxiangtu.top/Article/details/gtljkhwock.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzimjadrj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gtielskily.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxuanxn.top/Article/details/gtiusaynxu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hysaishi.cn/Article/details/gtegbhznix.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jlsjyb.cn/Article/details/gtroygwusj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yanxiufei.cn/Article/details/gtcctfnorm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.c1oappe.top/Article/details/gtghsqmbcx.html

[L06] 解析响应为 JSON
来源：http://dali.jlsjyb.cn/Article/details/gtcvbcrpog.html

Py:   resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gtfcgmgtpq.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gtqdixkvai.html

JS:   await resp.json()
来源：http://dali.sufxvd.cn/Article/details/gtctdbeisn.html

TS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gtycqqtjyw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gtcotvajqv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hysaishi.cn/Article/details/gtavwyqzba.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hongshengwenyu.top/Article/details/gtrqdcovyd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhixingplan.top/Article/details/gtlwikziso.html

[L07] 处理 HTTP 状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrksgvahn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shuidangran.top/Article/details/gttgjlwccm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zycfv.cn/Article/details/gtmmvqegkt.html

JS:   resp.ok;  resp.status
来源：http://dali.vqdsnc.cn/Article/details/gtwahfsflk.html

TS:   resp.ok;  resp.status
来源：http://dali.daria6918.cn/Article/details/gtpkuqtjej.html

Java: resp.statusCode()
来源：http://dali.birdmap.top/Article/details/gtrqelhbvq.html

Go:   resp.StatusCode
来源：http://dali.ybcxt.top/Article/details/gtjxeneauo.html

Ruby: resp.code.to_i
来源：http://dali.xziqi.cn/Article/details/gtyuscsrcx.html

C#:   (int)resp.StatusCode
来源：http://dali.jinyuanbaomall.cn/Article/details/gtagiunpjx.html

[L08] 并发请求多个地址
来源：http://dali.yj20258.top/Article/details/gtvacysthv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhiwuduotai.top/Article/details/gtatcbcsfl.html

PHP:  curl_multi_init() 系列
来源：http://dali.quarkkingdee.top/Article/details/gtuuogxlqx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtmncuizuz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yueranfly.top/Article/details/gtricbigbr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.0kj1m.cn/Article/details/gtfrtpkvnu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yonumen.top/Article/details/gttkbillod.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.aizwys.cn/Article/details/gtocgnpadm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cucudq.cn/Article/details/gtzwntczbb.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtntomnovj.html

M. 命令行 / 进程 / 环境
来源：http://dali.birdmap.top/Article/details/gtpdwuujwe.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtowkqsviw.html

[M01] 读取命令行参数
来源：http://dali.iojbl.cn/Article/details/gtikvwnvmg.html

Py:   sys.argv[1:]
来源：http://dali.haohaochexian.top/Article/details/gtxcmjzlhl.html

PHP:  $argv;  $argc;
来源：http://dali.jlsjyb.cn/Article/details/gtqtvdfxfk.html

JS:   process.argv.slice(2)
来源：http://dali.jyoumei.cn/Article/details/gtcaiwaffj.html

TS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gttofusqoj.html

Java: args 数组（main 方法参数）
来源：http://dali.c1oappe.top/Article/details/gtrixfxnzw.html

Go:   os.Args[1:]
来源：http://dali.316326.xyz/Article/details/gtqqwmhbeq.html

Ruby: ARGV
来源：http://dali.yongpay.top/Article/details/gtlwtrqrof.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258.top/Article/details/gtlkrzypdf.html

[M02] 读取环境变量
来源：http://dali.sxryk.cn/Article/details/gtzxaeqtto.html

Py:   os.environ.get("HOME")
来源：http://dali.hammf.cn/Article/details/gtnetuairw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzlvnlvo.html

JS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gtauxvescf.html

TS:   process.env.HOME
来源：http://dali.dianchejie.cn/Article/details/gtupubibwq.html

Java: System.getenv("HOME")
来源：http://dali.xuanzx.com/Article/details/gtfscoxjgm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xziqi.cn/Article/details/gtlwnjgqsn.html

Ruby: ENV["HOME"]
来源：http://dali.iojbl.cn/Article/details/gtpwpmhvyz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtryhffxtg.html

[M03] 执行外部命令
来源：http://dali.yangfankeji.com/Article/details/gtjjgphaij.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.svipenyu.cn/Article/details/gttjlmwhgm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.redwolf501.top/Article/details/gtlzxsammk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdxixxwa.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgfzy.top/Article/details/gtjcjaggwz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.fzhhl.top/Article/details/gtxiybcupj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.snrcjt.cn/Article/details/gtkkqxbpnb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hongshengwenyu.top/Article/details/gtjcbhjbwt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cqqwz.cn/Article/details/gtjsycuall.html

[M04] 获取当前工作目录
来源：http://dali.yuanzhike.top/Article/details/gtjrhvcvag.html

Py:   os.getcwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtlgoklrea.html

PHP:  getcwd();
来源：http://dali.jlsjyb.cn/Article/details/gtynzkdyck.html

JS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gtiiiectek.html

TS:   process.cwd()
来源：http://dali.ehwqpu.com/Article/details/gtbdwbglae.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.svipenyu.cn/Article/details/gtifdamohn.html

Go:   os.Getwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvedzaxhm.html

Ruby: Dir.pwd
来源：http://dali.nanxinkj.top/Article/details/gtaoqrayyw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.dashuyun.cn/Article/details/gtqsiyvoeo.html

[M05] 设置退出码
来源：http://dali.nanxuanxn.top/Article/details/gtvagqxmhm.html

Py:   sys.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gturvyqblo.html

PHP:  exit(1);
来源：http://dali.meibo888.top/Article/details/gtijfrciwt.html

JS:   process.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrzeasxi.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtzaypmvkf.html

Java: System.exit(1)
来源：http://dali.hammf.cn/Article/details/gtryfirjgo.html

Go:   os.Exit(1)
来源：http://dali.xuanzx.com/Article/details/gtrimzqaed.html

Ruby: exit 1
来源：http://dali.nanxinkj.top/Article/details/gtfemqcpce.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xuetiantiany.cn/Article/details/gtnevyzhaq.html

[M06] 向标准错误输出
来源：http://dali.yj20258888.top/Article/details/gtjhrpofoo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.feifeiyinyue.top/Article/details/gtnuvjuipj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenlongwang.top/Article/details/gtlbdwgnph.html

JS:   console.error("err")
来源：http://dali.yuanzhike.top/Article/details/gtopekrpsv.html

TS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtgvzllfxn.html

Java: System.err.println("err")
来源：http://dali.jianghu66.top/Article/details/gtvxdqcfpf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yongpay.top/Article/details/gtaujqcxxf.html

Ruby: warn "err"
来源：http://dali.guowangkeji.top/Article/details/gttrpewgru.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigfzy.top/Article/details/gtryjqfqni.html

[M07] 判断是否为主入口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwliqtfl.html

Py:   if __name__ == "__main__":
来源：http://dali.mhx1999.top/Article/details/gtlbdapand.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuanzx.com/Article/details/gthjbjbvxq.html

JS:   require.main === module
来源：http://dali.haohaochexian.top/Article/details/gtivzsalyp.html

TS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gttgbybygz.html

Java: public static void main(String[] args)
来源：http://dali.xylfe.cn/Article/details/gtplhijfum.html

Go:   func main()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewvuyrce.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmagbbxre.html

C#:   static void Main(string[] args)
来源：http://dali.yj202588.top/Article/details/gthqrzujka.html

[M08] 获取系统与运行时信息
来源：http://dali.daria6918.cn/Article/details/gtdqoajpnt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.guannengcc.top/Article/details/gtauatkmwa.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtifcodh.html

JS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gtroovydcz.html


<!-- 参考信息 -->