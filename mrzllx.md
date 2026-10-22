代发 wailian999

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhongyouzk.top/Article/details/gt2gulbwfnw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bhxzgrjm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xinyue.icu/Article/details/gt2djkabcmo.html

TS:   d.toISOString()
来源：http://dali.cheryme.top/Article/details/gt2kkuuogds.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yonumen.top/Article/details/gt2xybfjnmz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hywenlv.cn/Article/details/gt2apjygtwt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.redwolf501.top/Article/details/gt2ugxydxwx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xuetiantiany.cn/Article/details/gt2dirxpkxs.html

[J03] 字符串解析为日期
来源：http://dali.zdqjudy.top/Article/details/gt2ogrtdkms.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zycfv.cn/Article/details/gt2ugdeugsd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xuanzx.com/Article/details/gt2bdkeiapw.html

JS:   new Date("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gt2mlnnsdks.html

TS:   new Date("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gt2aqdxnssx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gt2uahxvire.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ytldhhnu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gt2awvaibuj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gaohongyu789.top/Article/details/gt2hgqwjwoy.html

[J04] 时间戳与日期互转
来源：http://dali.cqqwz.cn/Article/details/gt2xtgdmoqk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gt2cfkugwzm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnqzz.top/Article/details/gt2omvqtmth.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.mhx1999.top/Article/details/gt2tuhtfdrb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yuanzhike.top/Article/details/gt2juoiuiym.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.dashuyun.cn/Article/details/gt2lwhzupco.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gzhubu.top/Article/details/gt2najrrccp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.smart0.xyz/Article/details/gt2zhavwkpw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxinkj.top/Article/details/gt2zgfvpidc.html

[J05] 时间加减（加 7 天）
来源：http://dali.xuetiantiany.cn/Article/details/gt2upbkwxbk.html

Py:   now + timedelta(days=7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfgwkxw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.pengpengdd.cyou/Article/details/gt2yiovbujd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pycfn.com/Article/details/gt2lmrnrypy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2osqkkrnc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cheryme.top/Article/details/gt2vverbnqh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yongpay.top/Article/details/gt2cxjgioii.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenjidiqi.icu/Article/details/gt2pjzsukyc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhixingplan.top/Article/details/gt2vifptoqe.html

[J06] 计算两时间之差
来源：http://dali.ybcxt.top/Article/details/gt2lstvuvcz.html

Py:   (end - start).total_seconds()
来源：http://dali.ydzc1.top/Article/details/gt2jdyhhpsb.html

PHP:  $end->diff($start)->days;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2leoffuzp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhongyouzk.top/Article/details/gt2zkvxedbm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guannengcc.top/Article/details/gt2eixwcfak.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bvulkuuj.html

Go:   end.Sub(start).Hours()
来源：http://dali.bjfxy.top/Article/details/gt2iddnjnjg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.bjfxy.top/Article/details/gt2bfjxflmf.html

C#:   (end - start).TotalSeconds
来源：http://dali.xuetiantiany.cn/Article/details/gt2wuasqwid.html

[J07] 比较两个日期
来源：http://dali.guannengcc.top/Article/details/gt2ytvgmrsd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gt2uvqgiwdt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xinyue.icu/Article/details/gt2cbdcaedq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.mhx1999.top/Article/details/gt2trcugcsz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuxming.cn/Article/details/gt2cracrhdx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hammf.cn/Article/details/gt2kurvhbjt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.guowangkeji.top/Article/details/gt2ryzxbylj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbipeca.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gt2trzczlhc.html

[J08] 提取年月日与星期
来源：http://dali.daria6918.cn/Article/details/gt2glcrgkfe.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gt2kkahvici.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gotoacloud.top/Article/details/gt2mbtpwjmj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ehwqpu.com/Article/details/gt2jwrlxfck.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xuetiantiany.cn/Article/details/gt2hgqzqfix.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jlsjyb.cn/Article/details/gt2obqddqje.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xylfe.cn/Article/details/gt2ycadftsu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zdqjudy.top/Article/details/gt2hxwfvoog.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuxming.cn/Article/details/gt2emwjgkqu.html

[J09] 时区处理
来源：http://dali.yj20258.top/Article/details/gt2brfikbet.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ksoyaqbk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.birdmap.top/Article/details/gt2cnzjodxg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gt2ysajoqqn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gt2glfljlhr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.iojbl.cn/Article/details/gt2ytboayzp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zycfv.cn/Article/details/gt2hnyzwzbk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yanxiufei.cn/Article/details/gt2nucuoyok.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.9152youxi.cn/Article/details/gt2lehjlxlu.html

[J10] 取今天 / 本月第一天
来源：http://dali.316326.xyz/Article/details/gt2qxgljivp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ybcxt.top/Article/details/gt2xzbxohbp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenjidiqi.icu/Article/details/gt2dgwresed.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj20258888.top/Article/details/gt2nqktuamg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2nixwyiww.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.daria6918.cn/Article/details/gt2jfrhsyru.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sweek.top/Article/details/gt2sfslqrmj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nanxinkj.top/Article/details/gt2lonkhpry.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.snrcjt.cn/Article/details/gt2noapywqu.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2jutxfetj.html

K. JSON 与序列化
来源：http://dali.aizwys.cn/Article/details/gt2gvffzbpg.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2jetsuizj.html

[K01] 对象转 JSON 字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2ivgbmodb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.svipenyu.cn/Article/details/gt2jksevxbw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yanxiufei.cn/Article/details/gt2nllljwvl.html

JS:   JSON.stringify(obj)
来源：http://dali.tian-w.cn/Article/details/gt2drvfdtts.html

TS:   JSON.stringify(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2knbkafza.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jiagoushi.top/Article/details/gt2oamknuvc.html

Go:   json.Marshal(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2xtdscyub.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenzaomai.com/Article/details/gt2yojczbpy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2lzhcrtwc.html

[K02] JSON 字符串转对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jsqudlbm.html

Py:   json.loads(s)
来源：http://dali.hywenlv.cn/Article/details/gt2tfkfokyp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jiagoushi.top/Article/details/gt2ougfvkcz.html

JS:   JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gt2aknjaddy.html

TS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gt2kocodgvk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jianghu66.top/Article/details/gt2hryhopgw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gt2mqvlcbdx.html

Ruby: JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gt2ccdihcxs.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2idbqqacn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yuxming.cn/Article/details/gt2zmrwvzri.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj20258.top/Article/details/gt2xhthttfn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gt2ouikwjud.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2evpcrvoe.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ohwxwikd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2tkybeood.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sgxinzcv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.bjfxy.top/Article/details/gt2aimzhsvp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.wangdashe.top/Article/details/gt2ptwfhjpy.html

[K04] 读取 JSON 文件
来源：http://dali.xuanzx.com/Article/details/gt2cuomybmr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.mhx1999.top/Article/details/gt2ntinuwqr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gzhubu.top/Article/details/gt2vtqlhktw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jianghu66.top/Article/details/gt2bzskdjis.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gt2vagfeadv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sufxvd.cn/Article/details/gt2vrcouxdl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kcfldoex.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pycfn.com/Article/details/gt2bsxegvxf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2ezaczeoa.html

[K05] 深拷贝对象
来源：http://dali.gotoacloud.top/Article/details/gt2eyrnfncy.html

Py:   copy.deepcopy(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2ervegvqb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhoulong.xyz/Article/details/gt2akxzeruq.html

JS:   structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2rhqwjdqs.html

TS:   structuredClone(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cntmmekx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangdashe.top/Article/details/gt2ixoybzgv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhongyouzk.top/Article/details/gt2tqnwjmqe.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shangyingyoupin.top/Article/details/gt2skzgikkv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yonumen.top/Article/details/gt2zgvwqhjd.html

[K06] 解析 URL 查询串
来源：http://dali.zhiwuduotai.top/Article/details/gt2sneliobr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqxcphv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jiagoushi.top/Article/details/gt2jasbkbwo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jyoumei.cn/Article/details/gt2ukpiujjz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gt2ekyxecat.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nwbrower.top/Article/details/gt2ovggfcdt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gt2wnjknksa.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gt2hvgfszmz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gt2sywmhxpv.html

[K07] 进制转换
来源：http://dali.fzhhl.top/Article/details/gt2hmvsfuqx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gt2tmwhymjc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.bjfxy.top/Article/details/gt2rpdjrefr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gt2moxlhlyu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gt2eaqdvvqa.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gt2shmxlicf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.fengsongda.top/Article/details/gt2mtxxegfn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daria6918.cn/Article/details/gt2zhcbujka.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hdianydz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.aizwys.cn/Article/details/gt2kgnveqos.html

Py:   pickle.dumps(obj)
来源：http://dali.tanke756.top/Article/details/gt2lgyvynvk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sufxvd.cn/Article/details/gt2qnfsyxqx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gt2bfyhivoi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xuanzx.com/Article/details/gt2pcghwdfn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhoulong.xyz/Article/details/gt2xamolgzr.html

Go:   encoding/gob
来源：http://dali.cqqwz.cn/Article/details/gt2tgmoahyd.html

Ruby: Marshal.dump(obj)
来源：http://dali.316326.xyz/Article/details/gt2xsqgcvpz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gt2fyphmpnu.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2veadljni.html

L. 网络请求
来源：http://dali.ybcxt.top/Article/details/gt2snxyxddu.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2vjfqmaxv.html

[L01] 发送 GET 请求
来源：http://dali.jlsjyb.cn/Article/details/gt2wvldrepk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nwbrower.top/Article/details/gt2wvmnonyg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gaohongyu789.top/Article/details/gt2sehbtoyg.html

JS:   await fetch(url)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tappupwy.html

TS:   await fetch(url)
来源：http://dali.tian-w.cn/Article/details/gt2yrnbnyjq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj20258888.top/Article/details/gt2lexgjkqw.html

Go:   resp, err := http.Get(url)
来源：http://dali.sxryk.cn/Article/details/gt2rtxqaoch.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.aibaodan.cn/Article/details/gt2rcnxnbpc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhongyouzk.top/Article/details/gt2sffropkn.html

[L02] 发送 POST JSON
来源：http://dali.aizwys.cn/Article/details/gt2xpcrgaii.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jlsjyb.cn/Article/details/gt2dfzzxvox.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gzhubu.top/Article/details/gt2ftewltyc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258.top/Article/details/gt2zpzpqnwh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuanzhike.top/Article/details/gt2qbiiycbd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.feifeiyinyue.top/Article/details/gt2nxsedezl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shuidangran.top/Article/details/gt2mzztpxdn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uewpivbm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhongyouzk.top/Article/details/gt2uyfxycon.html

[L03] 设置自定义请求头
来源：http://dali.zhoulong.xyz/Article/details/gt2xljihrhb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.smart0.xyz/Article/details/gt2rprnvdto.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xziqi.cn/Article/details/gt2wniuaziy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gt2dyjiobjv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.316326.xyz/Article/details/gt2ozhkmfyi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.kuanghao11.cn/Article/details/gt2gssfgrki.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gt2pfkefzad.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gaohongyu789.top/Article/details/gt2jbvcwqtq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.wangdashe.top/Article/details/gt2rrirumfz.html

[L04] 设置超时
来源：http://dali.dashuyun.cn/Article/details/gt2jpxdclqv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.fzhhl.top/Article/details/gt2inyoxest.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nanxuanxn.top/Article/details/gt2svwledkn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tianlin.xyz/Article/details/gt2zmojzunf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zycfv.cn/Article/details/gt2ctwzirfk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.mhx1999.top/Article/details/gt2jqorubcs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gaohongyu789.top/Article/details/gt2wwgznjwi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dqgvsola.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ivvv.top/Article/details/gt2hshkpbtb.html

[L05] 上传文件（multipart）
来源：http://dali.jinqigfzy.top/Article/details/gt2auhovulx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hongshengwenyu.top/Article/details/gt2vhwbstne.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.fzhhl.top/Article/details/gt2auevmxsj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gt2jkmrbybo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.dianchejie.cn/Article/details/gt2ugtltwfz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.andypj.xyz/Article/details/gt2pfgnfmaf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nanxuanxn.top/Article/details/gt2mxmbuwcu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yonumen.top/Article/details/gt2yhriruij.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2bxgaggvw.html

[L06] 解析响应为 JSON
来源：http://dali.cheryme.top/Article/details/gt2nntyzffr.html

Py:   resp.json()
来源：http://dali.havefunace.top/Article/details/gt2wemirmvy.html

PHP:  json_decode($body, true);
来源：http://dali.snrcjt.cn/Article/details/gt2aqfnnssa.html

JS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gt2ujkbdacj.html

TS:   await resp.json()
来源：http://dali.yj20258.top/Article/details/gt2lgjpxapt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tjzuvfxc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2celvhdxl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xziqi.cn/Article/details/gt2epjhvonh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.haohaochexian.top/Article/details/gt2jvuqgspn.html

[L07] 处理 HTTP 状态码
来源：http://dali.cqqwz.cn/Article/details/gt2nxyndrgk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hysaishi.cn/Article/details/gt2dhnzvxkx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hfpthk.cn/Article/details/gt2ojizwhzl.html

JS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gt2xpiqtcek.html

TS:   resp.ok;  resp.status
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bgesfsmk.html

Java: resp.statusCode()
来源：http://dali.yj20258888.top/Article/details/gt2gfhjqylb.html

Go:   resp.StatusCode
来源：http://dali.andypj.xyz/Article/details/gt2nsjaefzk.html

Ruby: resp.code.to_i
来源：http://dali.zdqjudy.top/Article/details/gt2funvjdqp.html

C#:   (int)resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gt2tswjvkoo.html

[L08] 并发请求多个地址
来源：http://dali.ppjwa.cn/Article/details/gt2pzvkwtmz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hnqzz.top/Article/details/gt2vucuzvha.html

PHP:  curl_multi_init() 系列
来源：http://dali.dianchejie.cn/Article/details/gt2msobbnpy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cucudq.cn/Article/details/gt2xkrfjryn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gt2xdpdvadn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigufen.top/Article/details/gt2sexmrtay.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yongpay.top/Article/details/gt2wjgmavky.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.aizwys.cn/Article/details/gt2vclojzpv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gt2mnmwvbvf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfzltgh.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhixingplan.top/Article/details/gt2cfsthdis.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2glgnuehw.html

[M01] 读取命令行参数
来源：http://dali.xinyue.icu/Article/details/gt2qsaarcuj.html

Py:   sys.argv[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gt2mfpotsiv.html

PHP:  $argv;  $argc;
来源：http://dali.jlsjyb.cn/Article/details/gt2wxgmockd.html

JS:   process.argv.slice(2)
来源：http://dali.guowangkeji.top/Article/details/gt2ilpejfnc.html

TS:   process.argv.slice(2)
来源：http://dali.yj202588.top/Article/details/gt2dwtilhro.html

Java: args 数组（main 方法参数）
来源：http://dali.sysykeji.top/Article/details/gt2xauilfvx.html

Go:   os.Args[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gt2ekexcwag.html

Ruby: ARGV
来源：http://dali.xziqi.cn/Article/details/gt2ortcvqtd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2klzmpwsz.html

[M02] 读取环境变量
来源：http://dali.cqqwz.cn/Article/details/gt2gxzioqnw.html

Py:   os.environ.get("HOME")
来源：http://dali.cheryme.top/Article/details/gt2sbddregg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tianlin.xyz/Article/details/gt2wrekczho.html

JS:   process.env.HOME
来源：http://dali.jlsjyb.cn/Article/details/gt2uetuyiet.html

TS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xqsaxbvd.html

Java: System.getenv("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2nsnimzzu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gwgqlmvm.html

Ruby: ENV["HOME"]
来源：http://dali.yangfankeji.com/Article/details/gt2hvfqvwvk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yongpay.top/Article/details/gt2tuzghnbk.html

[M03] 执行外部命令
来源：http://dali.zhiwuduotai.top/Article/details/gt2vxuagyjt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cheryme.top/Article/details/gt2gojkafih.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinqigufen.top/Article/details/gt2xclrfwps.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cucudq.cn/Article/details/gt2zcdnzrzq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxinkj.top/Article/details/gt2sxoekcdo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dashuyun.cn/Article/details/gt2guimoflj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ybcxt.top/Article/details/gt2lqkdkyuz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.guannengcc.top/Article/details/gt2wzoouxln.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hnxiangtu.top/Article/details/gt2gazpmtvp.html

[M04] 获取当前工作目录
来源：http://dali.haohaochexian.top/Article/details/gt2forrjotr.html

Py:   os.getcwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xeysuvvb.html

PHP:  getcwd();
来源：http://dali.shzxlz.cn/Article/details/gt2fboneany.html

JS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gt2dpxfwbxr.html

TS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gt2iaestpgw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.kuanghao11.cn/Article/details/gt2wpxroaly.html

Go:   os.Getwd()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ehkmqnxj.html

Ruby: Dir.pwd
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ndwufsqx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.dashuyun.cn/Article/details/gt2aghmeofn.html

[M05] 设置退出码
来源：http://dali.aibaodan.cn/Article/details/gt2jmzrewqk.html

Py:   sys.exit(1)
来源：http://dali.xziqi.cn/Article/details/gt2fdydghee.html

PHP:  exit(1);
来源：http://dali.snrcjt.cn/Article/details/gt2qfryyfpb.html

JS:   process.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gt2ocfepzgi.html

TS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gt2cjayqgry.html

Java: System.exit(1)
来源：http://dali.yj20258888.top/Article/details/gt2handhwio.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wdsykchd.html

Ruby: exit 1
来源：http://dali.cdnleiting.top/Article/details/gt2ldhorcsb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenlongwang.top/Article/details/gt2foazrage.html

[M06] 向标准错误输出
来源：http://dali.xinyue.icu/Article/details/gt2dceicdko.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gaohongyu789.top/Article/details/gt2fybvcsox.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gotoacloud.top/Article/details/gt2qnrbuqfa.html

JS:   console.error("err")
来源：http://dali.snrcjt.cn/Article/details/gt2ponjwtyh.html

TS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gt2vvwcpgcd.html

Java: System.err.println("err")
来源：http://dali.c1oappe.top/Article/details/gt2migwlkhd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenzaomai.com/Article/details/gt2xoyxtxne.html

Ruby: warn "err"
来源：http://dali.hnxiangtu.top/Article/details/gt2ekvkpoxy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.dashuyun.cn/Article/details/gt2nwtxkazh.html

[M07] 判断是否为主入口
来源：http://dali.xuanzx.com/Article/details/gt2jhvblovd.html

Py:   if __name__ == "__main__":
来源：http://dali.xuetiantiany.cn/Article/details/gt2xbrhorkb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.c1oappe.top/Article/details/gt2pssgitel.html

JS:   require.main === module
来源：http://dali.bjfxy.top/Article/details/gt2fxwytcrb.html

TS:   require.main === module
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sqgtswry.html

Java: public static void main(String[] args)
来源：http://dali.tanke756.top/Article/details/gt2xulrrtna.html

Go:   func main()
来源：http://dali.tian-w.cn/Article/details/gt2pkatrbjj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ybcxt.top/Article/details/gt2fmtwihrs.html

C#:   static void Main(string[] args)
来源：http://dali.chenlongwang.top/Article/details/gt2xtdvfdey.html

[M08] 获取系统与运行时信息
来源：http://dali.ppjwa.cn/Article/details/gt2cgrzgkhz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tianlin.xyz/Article/details/gt2qcpvmudb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.redwolf501.top/Article/details/gt2lywrwcsx.html

JS:   process.platform;  process.version
来源：http://dali.0kj1m.cn/Article/details/gt2daomogvc.html


<!-- 参考信息 -->