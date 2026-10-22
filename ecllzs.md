代发 wailian999

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.vqdsnc.cn/Article/details/gt2xnhnouih.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.guannengcc.top/Article/details/gt2apjzvjhm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.smart0.xyz/Article/details/gt2xagivxov.html

TS:   d.toISOString()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vikapzsl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.9152youxi.cn/Article/details/gt2iatdjbsl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2emonpwgt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gzhubu.top/Article/details/gt2irvoalcx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gogol.net.cn/Article/details/gt2wzijpxuk.html

[J03] 字符串解析为日期
来源：http://dali.daxiang520.top/Article/details/gt2qvxzaudj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jyoumei.cn/Article/details/gt2dqorfgwu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.9152youxi.cn/Article/details/gt2cfyejcyl.html

JS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2iimrfpge.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gt2vzwbttjf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hzpjhlut.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gt2cajlqkho.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gt2nlcugpmi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ybcxt.top/Article/details/gt2lejsiaek.html

[J04] 时间戳与日期互转
来源：http://dali.nwbrower.top/Article/details/gt2kkeyusjp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.quarkkingdee.top/Article/details/gt2etmkhjyg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.quarkkingdee.top/Article/details/gt2akbvnnww.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yueranfly.top/Article/details/gt2wbvxuugr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ajiphsrk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.quarkkingdee.top/Article/details/gt2ycyygqgz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2lvqkiqau.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zdqjudy.top/Article/details/gt2itkcjqiy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yanxiufei.cn/Article/details/gt2rkvduolw.html

[J05] 时间加减（加 7 天）
来源：http://dali.yvedp.cn/Article/details/gt2fahivcck.html

Py:   now + timedelta(days=7)
来源：http://dali.yj20258888.top/Article/details/gt2svrcqhwg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ysjtnhto.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gt2msxnxgls.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gt2lruzkrbf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnqzz.top/Article/details/gt2enrajtht.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenlongwang.top/Article/details/gt2rlnwgwud.html

Ruby: Time.now + 7 * 86400
来源：http://dali.havefunace.top/Article/details/gt2zeuauryd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jqgfzy.top/Article/details/gt2egkqiapp.html

[J06] 计算两时间之差
来源：http://dali.zdqjudy.top/Article/details/gt2utzwjpdk.html

Py:   (end - start).total_seconds()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2giulsxdo.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2awnzbjyd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.fzhhl.top/Article/details/gt2rvysbfrn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258888.top/Article/details/gt2jjqhvuwo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258888.top/Article/details/gt2zkbjfpzm.html

Go:   end.Sub(start).Hours()
来源：http://dali.nanxuanxn.top/Article/details/gt2wnbydkci.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj202588.top/Article/details/gt2fomsixlh.html

C#:   (end - start).TotalSeconds
来源：http://dali.jqgfzy.top/Article/details/gt2zipvtvym.html

[J07] 比较两个日期
来源：http://dali.tian-w.cn/Article/details/gt2xbafonnx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eadqldab.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gotoacloud.top/Article/details/gt2hqtdbfsz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gt2jyeivmta.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gt2iwzwlrkf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cheryme.top/Article/details/gt2rngujscb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xsgbfsrb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gt2kmdiwjdd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gt2ulhygrhc.html

[J08] 提取年月日与星期
来源：http://dali.yueranfly.top/Article/details/gt2olirmzpn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cdnleiting.top/Article/details/gt2tbpsolzc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zycfv.cn/Article/details/gt2ghlwffww.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daria6918.cn/Article/details/gt2qsklujni.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigufen.top/Article/details/gt2pjodixiy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.pycfn.com/Article/details/gt2kzntgkof.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.mhx1999.top/Article/details/gt2siqajemm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yuanzhike.top/Article/details/gt2qearcetx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinqigfzy.top/Article/details/gt2mrbikvuy.html

[J09] 时区处理
来源：http://dali.wangshuangyany.cn/Article/details/gt2iwvguvuj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yonumen.top/Article/details/gt2tqaqpehs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aibaodan.cn/Article/details/gt2cjbddxgb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.mhx1999.top/Article/details/gt2ciomvqlm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fprkikym.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.birdmap.top/Article/details/gt2yndopgdp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.andypj.xyz/Article/details/gt2zlmxwulg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ziaixajp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yuanzhike.top/Article/details/gt2rrnhcjxg.html

[J10] 取今天 / 本月第一天
来源：http://dali.hnqzz.top/Article/details/gt2vexmjzrh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cucudq.cn/Article/details/gt2mdwceafd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.feifeiyinyue.top/Article/details/gt2lyoyphne.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jianghu66.top/Article/details/gt2ihkibbdk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2rexbzjnd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ehwqpu.com/Article/details/gt2sfhknozj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pycfn.com/Article/details/gt2nerywfbe.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.c1oappe.top/Article/details/gt2zurpsaol.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2joznzuvw.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gyazqwgw.html

K. JSON 与序列化
来源：http://dali.ppjwa.cn/Article/details/gt2zxmtsacn.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2tdtyghhb.html

[K01] 对象转 JSON 字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2gmmkrccv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ehwqpu.com/Article/details/gt2upzsgtqs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.316326.xyz/Article/details/gt2dmjjtqsw.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2yjatgqqn.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmhpfvg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.svipenyu.cn/Article/details/gt2chtsadza.html

Go:   json.Marshal(obj)
来源：http://dali.hnqzz.top/Article/details/gt2asxiylpt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tian-w.cn/Article/details/gt2trbzisfk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2cwkxyziv.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jvawkayr.html

Py:   json.loads(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2imvuxeio.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sufxvd.cn/Article/details/gt2eyparhgg.html

JS:   JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yxbwxymu.html

TS:   JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gt2kcjlebzu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yvedp.cn/Article/details/gt2tuwffxco.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.daxiang520.top/Article/details/gt2opnkupct.html

Ruby: JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gt2iutsfmsk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuanzx.com/Article/details/gt2sbkjobfh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shangyingyoupin.top/Article/details/gt2wnorriew.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.meibo888.top/Article/details/gt2bmmxpgfn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.guowangkeji.top/Article/details/gt2khqnsrwy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gt2civqeata.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.tanke756.top/Article/details/gt2yhjonzjm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2gkunangj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.bjfxy.top/Article/details/gt2nvuvpjtm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2tnragjym.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cdnleiting.top/Article/details/gt2mtsgabjl.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cuiwegmo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.redwolf501.top/Article/details/gt2uxsxqezg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.iojbl.cn/Article/details/gt2xoicvtfu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenlongwang.top/Article/details/gt2fajlqihf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2cwmmoeuy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jianghu66.top/Article/details/gt2ymngazge.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.kuanghao11.cn/Article/details/gt2nwvudyih.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ppjwa.cn/Article/details/gt2auhtvrrr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gt2tylpemzj.html

[K05] 深拷贝对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dloareqf.html

Py:   copy.deepcopy(obj)
来源：http://dali.daria6918.cn/Article/details/gt2mrmcrdxz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinqigfzy.top/Article/details/gt2yvxzmlbx.html

JS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gt2rslltwkv.html

TS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gt2lgaqvcyf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258.top/Article/details/gt2anhkiboe.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.0kj1m.cn/Article/details/gt2czdvtefe.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuanzx.com/Article/details/gt2kmhaqzmr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ivvv.top/Article/details/gt2noofqzax.html

[K06] 解析 URL 查询串
来源：http://dali.zhiwuduotai.top/Article/details/gt2pvdtbgfu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yanxiufei.cn/Article/details/gt2jwbcffqt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangdashe.top/Article/details/gt2xhqqzcat.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hywenlv.cn/Article/details/gt2viniovsp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhoulong.xyz/Article/details/gt2bmtdxczg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.daria6918.cn/Article/details/gt2cpwqzpfg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gt2qutefrsb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gt2posybssr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gt2gluxokmg.html

[K07] 进制转换
来源：http://dali.bjfxy.top/Article/details/gt2gnefhney.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.havefunace.top/Article/details/gt2tizufcxw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.quarkkingdee.top/Article/details/gt2uwqkezau.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gt2baahdbrp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gt2tlacncem.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gt2dlcxwbve.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.andypj.xyz/Article/details/gt2csdxgkoh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daria6918.cn/Article/details/gt2icabdglf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gt2djnqlqto.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gaohongyu789.top/Article/details/gt2ovzgaere.html

Py:   pickle.dumps(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2ojdehxxg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sysykeji.top/Article/details/gt2gcqfcsne.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gt2eawcvybc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.316326.xyz/Article/details/gt2inxtelap.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2yogohzhb.html

Go:   encoding/gob
来源：http://dali.jinghuilouyu.cn/Article/details/gt2blbylxew.html

Ruby: Marshal.dump(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2iumkvopf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gt2qhrxoovw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmivwcn.html

L. 网络请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zqmqdnkn.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2ticckviu.html

[L01] 发送 GET 请求
来源：http://dali.gogol.net.cn/Article/details/gt2uclhnxhv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jyoumei.cn/Article/details/gt2ocmowntr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.havefunace.top/Article/details/gt2fqbquhzk.html

JS:   await fetch(url)
来源：http://dali.jyoumei.cn/Article/details/gt2hyarlpxn.html

TS:   await fetch(url)
来源：http://dali.zdqjudy.top/Article/details/gt2tqnokywn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pxhzcggt.html

Go:   resp, err := http.Get(url)
来源：http://dali.jyoumei.cn/Article/details/gt2wqmawcdd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.aibaodan.cn/Article/details/gt2pnsbryzm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dykcxubm.html

[L02] 发送 POST JSON
来源：http://dali.snrcjt.cn/Article/details/gt2blptrnrb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.havefunace.top/Article/details/gt2cxgkqyjy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shangyingyoupin.top/Article/details/gt2tpxujvio.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gt2oxmipiga.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guowangkeji.top/Article/details/gt2syneqfjm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2owvkgmng.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tanke756.top/Article/details/gt2tdyiyzmn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.guannengcc.top/Article/details/gt2zjzeiple.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cucudq.cn/Article/details/gt2pstxkwbn.html

[L03] 设置自定义请求头
来源：http://dali.cqqwz.cn/Article/details/gt2msxzxhfk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yueranfly.top/Article/details/gt2bfxvboqg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2fkpxptci.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gt2nmfvuwjr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fzhhl.top/Article/details/gt2jjbxpexx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.pengpengdd.cyou/Article/details/gt2sbkdrybn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hongshengwenyu.top/Article/details/gt2nooykzrd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lplaczrj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gt2gqmvmcqs.html

[L04] 设置超时
来源：http://dali.hongshengwenyu.top/Article/details/gt2xzefgiwy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hysaishi.cn/Article/details/gt2edbdjgwy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ouctuzwh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.birdmap.top/Article/details/gt2hpduoagl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gt2nbhlsfhv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ivvv.top/Article/details/gt2blxzlwfj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pycfn.com/Article/details/gt2ynqntwgw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenzaomai.com/Article/details/gt2plobvsdz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.fzhhl.top/Article/details/gt2stjwjiah.html

[L05] 上传文件（multipart）
来源：http://dali.daxiang520.top/Article/details/gt2msjzdwtr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cucudq.cn/Article/details/gt2gxfuclxr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cucudq.cn/Article/details/gt2yetsmmnu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hysaishi.cn/Article/details/gt2bnbousgp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hysaishi.cn/Article/details/gt2onwinsjd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinqigufen.top/Article/details/gt2emzxamsx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xuanzx.com/Article/details/gt2tvkzdfxj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shuidangran.top/Article/details/gt2bnwegcwi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2xxbpoqka.html

[L06] 解析响应为 JSON
来源：http://dali.meibo888.top/Article/details/gt2iixajcag.html

Py:   resp.json()
来源：http://dali.ppjwa.cn/Article/details/gt2bprjccaz.html

PHP:  json_decode($body, true);
来源：http://dali.zhongyouzk.top/Article/details/gt2kvhmqhkj.html

JS:   await resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jsavnptm.html

TS:   await resp.json()
来源：http://dali.iojbl.cn/Article/details/gt2dununubk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vgxrbkmw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nwbrower.top/Article/details/gt2cyqwknpy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ktwvixxz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangshuangyany.cn/Article/details/gt2toazfjdv.html

[L07] 处理 HTTP 状态码
来源：http://dali.yvedp.cn/Article/details/gt2zclhsjka.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.daria6918.cn/Article/details/gt2zquxbbaw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hnxiangtu.top/Article/details/gt2ocdlyfwh.html

JS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wreslfsg.html

TS:   resp.ok;  resp.status
来源：http://dali.havefunace.top/Article/details/gt2ktrntakl.html

Java: resp.statusCode()
来源：http://dali.fengsongda.top/Article/details/gt2lvbqqxar.html

Go:   resp.StatusCode
来源：http://dali.andypj.xyz/Article/details/gt2aacuzfeb.html

Ruby: resp.code.to_i
来源：http://dali.9152youxi.cn/Article/details/gt2xiydfymw.html

C#:   (int)resp.StatusCode
来源：http://dali.yangfankeji.com/Article/details/gt2qhnepkqg.html

[L08] 并发请求多个地址
来源：http://dali.hywenlv.cn/Article/details/gt2vzohxber.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.bjfxy.top/Article/details/gt2zmdihhbc.html

PHP:  curl_multi_init() 系列
来源：http://dali.yanxiufei.cn/Article/details/gt2hyozmmqz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gt2kpuchgqs.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gt2cnanxuvs.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.aizwys.cn/Article/details/gt2twjwjsgh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpubszo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cqqwz.cn/Article/details/gt2uhtmjeth.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yongpay.top/Article/details/gt2lmwxfncf.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2bqrmqyxg.html

M. 命令行 / 进程 / 环境
来源：http://dali.tian-w.cn/Article/details/gt2xinypeys.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2pinjmhjm.html

[M01] 读取命令行参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2ouajlnht.html

Py:   sys.argv[1:]
来源：http://dali.dianchejie.cn/Article/details/gt2weocyqrt.html

PHP:  $argv;  $argc;
来源：http://dali.zycfv.cn/Article/details/gt2xzaawywz.html

JS:   process.argv.slice(2)
来源：http://dali.fzhhl.top/Article/details/gt2lpobquuk.html

TS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gt2vnatbzfz.html

Java: args 数组（main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gt2gugeeifj.html

Go:   os.Args[1:]
来源：http://dali.havefunace.top/Article/details/gt2qhvkgyjn.html

Ruby: ARGV
来源：http://dali.cucudq.cn/Article/details/gt2uiupiofh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ybcxt.top/Article/details/gt2tlmelyhd.html

[M02] 读取环境变量
来源：http://dali.316326.xyz/Article/details/gt2iqaanuhh.html

Py:   os.environ.get("HOME")
来源：http://dali.havefunace.top/Article/details/gt2lhtwhgta.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gt2ypxcream.html

JS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gt2uklqyaou.html

TS:   process.env.HOME
来源：http://dali.zhixingplan.top/Article/details/gt2zhejsiak.html

Java: System.getenv("HOME")
来源：http://dali.316326.xyz/Article/details/gt2jvaqzftv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gxclptpp.html

Ruby: ENV["HOME"]
来源：http://dali.snrcjt.cn/Article/details/gt2kctwtvlq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sweek.top/Article/details/gt2accazcwb.html

[M03] 执行外部命令
来源：http://dali.yongpay.top/Article/details/gt2kzmcrkrv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgufenzy.top/Article/details/gt2pacbkrjm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhongyouzk.top/Article/details/gt2nembhysc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gt2ybqbntsy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gt2isdlkuvd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zwpugsrq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dashuyun.cn/Article/details/gt2itwmjzpz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhongyouzk.top/Article/details/gt2ijcraoui.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yangfankeji.com/Article/details/gt2wkdoqtqh.html

[M04] 获取当前工作目录
来源：http://dali.jqgufenzy.top/Article/details/gt2mifodbrf.html

Py:   os.getcwd()
来源：http://dali.hongshengwenyu.top/Article/details/gt2pgfhtwrb.html

PHP:  getcwd();
来源：http://dali.iojbl.cn/Article/details/gt2xppiytyh.html

JS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dvjyfubc.html

TS:   process.cwd()
来源：http://dali.cashguo.top/Article/details/gt2lqjythou.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cheryme.top/Article/details/gt2nuyzbtef.html

Go:   os.Getwd()
来源：http://dali.chenlongwang.top/Article/details/gt2hcxjummk.html

Ruby: Dir.pwd
来源：http://dali.yanxiufei.cn/Article/details/gt2lzlnehkq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yanxiufei.cn/Article/details/gt2ltxntpst.html

[M05] 设置退出码
来源：http://dali.jlsjyb.cn/Article/details/gt2ijyqedea.html

Py:   sys.exit(1)
来源：http://dali.guannengcc.top/Article/details/gt2bufaxfyl.html

PHP:  exit(1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ijqghyhi.html

JS:   process.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gt2pdewgyie.html

TS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2abbcjbqa.html

Java: System.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gt2bxdmwghj.html

Go:   os.Exit(1)
来源：http://dali.zycfv.cn/Article/details/gt2eftqvelq.html

Ruby: exit 1
来源：http://dali.jyoumei.cn/Article/details/gt2elpqvqfu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.316326.xyz/Article/details/gt2vjjvetnr.html

[M06] 向标准错误输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kjxajeeo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.meibo888.top/Article/details/gt2thxyyxtu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jianghu66.top/Article/details/gt2jvgogkwh.html

JS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gt2rtblwtpp.html

TS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dfbfxmfi.html

Java: System.err.println("err")
来源：http://dali.dashuyun.cn/Article/details/gt2mpavdokm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2qgrihsjr.html

Ruby: warn "err"
来源：http://dali.svipenyu.cn/Article/details/gt2yfcoqcne.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.dashuyun.cn/Article/details/gt2niwjopwu.html

[M07] 判断是否为主入口
来源：http://dali.xziqi.cn/Article/details/gt2pjcnjbza.html

Py:   if __name__ == "__main__":
来源：http://dali.quarkkingdee.top/Article/details/gt2kukgaxnk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aizwys.cn/Article/details/gt2zawenkfs.html

JS:   require.main === module
来源：http://dali.iojbl.cn/Article/details/gt2iloqakdl.html

TS:   require.main === module
来源：http://dali.haohaochexian.top/Article/details/gt2rjwvxxtb.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jtpwxmpr.html

Go:   func main()
来源：http://dali.meibo888.top/Article/details/gt2ymczaidy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yttndckc.html

C#:   static void Main(string[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gt2leyyqsyh.html

[M08] 获取系统与运行时信息
来源：http://dali.fzhhl.top/Article/details/gt2krbrsqza.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jiagoushi.top/Article/details/gt2olmdsbit.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gaohongyu789.top/Article/details/gt2hvwipyee.html

JS:   process.platform;  process.version
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ktrxsbvw.html


<!-- 参考信息 -->