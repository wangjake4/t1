代发 wailian999

Go:   time.Now()
来源：http://dali.yj20258888.top/Article/details/gt2nipuyaom.html

Ruby: Time.now
来源：http://dali.sufxvd.cn/Article/details/gt2lnnznjnu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gt2kevfocqi.html

[J02] 格式化输出
来源：http://dali.jqgufenzy.top/Article/details/gt2yudqjlxw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gt2armjkzfj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gt2cvcbgbew.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yonumen.top/Article/details/gt2uxztiltj.html

TS:   d.toISOString()
来源：http://dali.ybcxt.top/Article/details/gt2lomqdxmh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.feifeiyinyue.top/Article/details/gt2ouvvdaaj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gotoacloud.top/Article/details/gt2ncmpgnox.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shangyingyoupin.top/Article/details/gt2wtqmltgx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnxiangtu.top/Article/details/gt2nyppkmhv.html

[J03] 字符串解析为日期
来源：http://dali.haohaochexian.top/Article/details/gt2lghttstd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hnxiangtu.top/Article/details/gt2rzutgknq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenlongwang.top/Article/details/gt2bbdjkgli.html

JS:   new Date("2024-01-02")
来源：http://dali.sweek.top/Article/details/gt2cnwaexka.html

TS:   new Date("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gt2ulgfpstl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gt2dchmvyuf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2lfismsaf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gt2jlkqeydc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vzviggeu.html

[J04] 时间戳与日期互转
来源：http://dali.meibo888.top/Article/details/gt2igixsapl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinqigfzy.top/Article/details/gt2vsxtnnjr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.haohaochexian.top/Article/details/gt2mpcmimqa.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sysykeji.top/Article/details/gt2melxqdha.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.bjfxy.top/Article/details/gt2golhvyax.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tanke756.top/Article/details/gt2nvlvoiwq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sysykeji.top/Article/details/gt2ipufokrg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xziqi.cn/Article/details/gt2bjhfsdgs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jlsjyb.cn/Article/details/gt2oxczuprs.html

[J05] 时间加减（加 7 天）
来源：http://dali.xziqi.cn/Article/details/gt2nyhwvacp.html

Py:   now + timedelta(days=7)
来源：http://dali.zhiwuduotai.top/Article/details/gt2owiqzbhy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.vqdsnc.cn/Article/details/gt2wrzmlapl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangdashe.top/Article/details/gt2gecjgazj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangshuangyany.cn/Article/details/gt2smgkgngh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nanxuanxn.top/Article/details/gt2dctcfbsb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dianchejie.cn/Article/details/gt2hkxkicjd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinqigufen.top/Article/details/gt2custcwqb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ybcxt.top/Article/details/gt2fljhzrqq.html

[J06] 计算两时间之差
来源：http://dali.yvedp.cn/Article/details/gt2jdiuuquy.html

Py:   (end - start).total_seconds()
来源：http://dali.zhixingplan.top/Article/details/gt2qsqycqhz.html

PHP:  $end->diff($start)->days;
来源：http://dali.havefunace.top/Article/details/gt2wapatmzw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.svipenyu.cn/Article/details/gt2ctscdpko.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yongpay.top/Article/details/gt2weiairwi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yongpay.top/Article/details/gt2qpcftcfb.html

Go:   end.Sub(start).Hours()
来源：http://dali.fengsongda.top/Article/details/gt2cowwmcld.html

Ruby: end - start                 # 返回秒数
来源：http://dali.smart0.xyz/Article/details/gt2oyrbjauo.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhongyouzk.top/Article/details/gt2gxgephtg.html

[J07] 比较两个日期
来源：http://dali.hywenlv.cn/Article/details/gt2ukpexogz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gt2szrjmvkr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gotoacloud.top/Article/details/gt2xozovcki.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.vqdsnc.cn/Article/details/gt2yveietht.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cucudq.cn/Article/details/gt2aqvmunsv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sysykeji.top/Article/details/gt2sgjfsxpe.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dashuyun.cn/Article/details/gt2dlemdobq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2araatbke.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gt2tcwpapge.html

[J08] 提取年月日与星期
来源：http://dali.c1oappe.top/Article/details/gt2falslful.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jlsjyb.cn/Article/details/gt2jlabhmts.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhixingplan.top/Article/details/gt2pddytgsj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.0kj1m.cn/Article/details/gt2llnlzfoe.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.wangshuangyany.cn/Article/details/gt2fimoxenq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yonumen.top/Article/details/gt2nogdjtmy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.birdmap.top/Article/details/gt2sjacwbnn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yangfankeji.com/Article/details/gt2tvapslbi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cheryme.top/Article/details/gt2sfvonwya.html

[J09] 时区处理
来源：http://dali.dashuyun.cn/Article/details/gt2arhstyon.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jlsjyb.cn/Article/details/gt2tkypekwd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj20258888.top/Article/details/gt2llrfxdth.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cucudq.cn/Article/details/gt2fikxxbdf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gt2ifzcblys.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ppjwa.cn/Article/details/gt2pkhxbqjg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zycfv.cn/Article/details/gt2tngxosct.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gzjtuvqc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.wangdashe.top/Article/details/gt2weamexiz.html

[J10] 取今天 / 本月第一天
来源：http://dali.ppjwa.cn/Article/details/gt2pvuakdac.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tianlin.xyz/Article/details/gt2uezmyejm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gotoacloud.top/Article/details/gt2bloihgbh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yanxiufei.cn/Article/details/gt2tomquatp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xbrihjvu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cqqwz.cn/Article/details/gt2rgftvszi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sufxvd.cn/Article/details/gt2xwfchmii.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinqigfzy.top/Article/details/gt2afjhrvuk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.andypj.xyz/Article/details/gt2yqmqbxqj.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2iybbhoeb.html

K. JSON 与序列化
来源：http://dali.meibo888.top/Article/details/gt2xzyrnmaj.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2amcawljx.html

[K01] 对象转 JSON 字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cphbeuea.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yongpay.top/Article/details/gt2hpizuszy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258888.top/Article/details/gt2objczveq.html

JS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2fyxclbwx.html

TS:   JSON.stringify(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2rzhhcyrg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yonumen.top/Article/details/gt2bunrbcir.html

Go:   json.Marshal(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2gmumwqvt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.smart0.xyz/Article/details/gt2tlkbpqcm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2bcrwbnbn.html

[K02] JSON 字符串转对象
来源：http://dali.sweek.top/Article/details/gt2csonyupr.html

Py:   json.loads(s)
来源：http://dali.andypj.xyz/Article/details/gt2zxsnvtoq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gotoacloud.top/Article/details/gt2bmzbecns.html

JS:   JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gt2vefsmwmd.html

TS:   JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gt2dvgwdbqm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxinkj.top/Article/details/gt2mmbdllul.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gt2paafnequ.html

Ruby: JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gt2ykrovoiu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vjcpwkrg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.vqdsnc.cn/Article/details/gt2kytdxnjy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gt2lyevwohz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigfzy.top/Article/details/gt2drfsupdu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xylfe.cn/Article/details/gt2gvrrxubb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hammf.cn/Article/details/gt2yutmfipx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zbhzwnws.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tajcbbao.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2wkjdgtci.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.wangshuangyany.cn/Article/details/gt2bkszriku.html

[K04] 读取 JSON 文件
来源：http://dali.redwolf501.top/Article/details/gt2vwauvpwn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tian-w.cn/Article/details/gt2duvbzfku.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shuidangran.top/Article/details/gt2ncihfwve.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gt2gzoojwlq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tianlin.xyz/Article/details/gt2qbsmxlmt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.aizwys.cn/Article/details/gt2uqxtekpi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hysaishi.cn/Article/details/gt2ebfqujln.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.redwolf501.top/Article/details/gt2hozlbcol.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gt2nzevulgx.html

[K05] 深拷贝对象
来源：http://dali.ehwqpu.com/Article/details/gt2qqkdhsbb.html

Py:   copy.deepcopy(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2zfoqgnwh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jyoumei.cn/Article/details/gt2mpxqovun.html

JS:   structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gt2jnhvmtqk.html

TS:   structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2zzijholq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigufen.top/Article/details/gt2kbyhryzk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2enypwxke.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.daxiang520.top/Article/details/gt2adtxbsfl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.wangdashe.top/Article/details/gt2fuwucwsd.html

[K06] 解析 URL 查询串
来源：http://dali.sysykeji.top/Article/details/gt2ztclffxg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.haohaochexian.top/Article/details/gt2xurogmkv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.smart0.xyz/Article/details/gt2bofgnpzd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.iojbl.cn/Article/details/gt2usjboews.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.9152youxi.cn/Article/details/gt2jyzyrsps.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ehwqpu.com/Article/details/gt2lrvygsqb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gt2mwfzgjbc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gt2rrmcbumo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gt2afxifreb.html

[K07] 进制转换
来源：http://dali.ydzc1.top/Article/details/gt2qxswvvli.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2anxtuxwm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yonumen.top/Article/details/gt2pcqmjzcl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gt2cfoupwkm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2bqtclwma.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gt2dwiwyrip.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daxiang520.top/Article/details/gt2czjplcjj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhoulong.xyz/Article/details/gt2hhekajwp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gt2nhcwbafg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yongpay.top/Article/details/gt2qgjcjktx.html

Py:   pickle.dumps(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2phcwemdw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zwbkrhkv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gt2iztsiygi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gt2kbvkgtfe.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.0kj1m.cn/Article/details/gt2ftykumyq.html

Go:   encoding/gob
来源：http://dali.guowangkeji.top/Article/details/gt2vvhmfudn.html

Ruby: Marshal.dump(obj)
来源：http://dali.redwolf501.top/Article/details/gt2hwoffqyl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gt2estpdibh.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2coqvduqt.html

L. 网络请求
来源：http://dali.hnxiangtu.top/Article/details/gt2qfogirqf.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zmsnafbr.html

[L01] 发送 GET 请求
来源：http://dali.guowangkeji.top/Article/details/gt2suoigkno.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2duxhzkqv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ehwqpu.com/Article/details/gt2tiwvzkxw.html

JS:   await fetch(url)
来源：http://dali.jlsjyb.cn/Article/details/gt2gokodbpz.html

TS:   await fetch(url)
来源：http://dali.hywenlv.cn/Article/details/gt2xnyjxgkq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhoulong.xyz/Article/details/gt2vqnoredp.html

Go:   resp, err := http.Get(url)
来源：http://dali.pycfn.com/Article/details/gt2wikwaein.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fatzhkzl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.kuanghao11.cn/Article/details/gt2jdfqcprd.html

[L02] 发送 POST JSON
来源：http://dali.0kj1m.cn/Article/details/gt2wrudnwhz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenjidiqi.icu/Article/details/gt2klgtaakc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenjidiqi.icu/Article/details/gt2btcgquue.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gt2esxhnpda.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gt2mupbnkky.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.aibaodan.cn/Article/details/gt2eozogqvs.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2olbeipjl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2evcekvnl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ivvv.top/Article/details/gt2uaerwijw.html

[L03] 设置自定义请求头
来源：http://dali.guowangkeji.top/Article/details/gt2mmerwgmm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hongshengwenyu.top/Article/details/gt2rgrhitqx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dianchejie.cn/Article/details/gt2wpcsoviq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gt2ipfanzoz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gt2kzjizoie.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2ykapbbeh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sufxvd.cn/Article/details/gt2dyxslfpb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yiydpokb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.quarkkingdee.top/Article/details/gt2irvgrata.html

[L04] 设置超时
来源：http://dali.chenlongwang.top/Article/details/gt2yzlwzpye.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gotoacloud.top/Article/details/gt2oiaqtqjm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.birdmap.top/Article/details/gt2vmrodids.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shangyingyoupin.top/Article/details/gt2ymwftloe.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gt2xfejkxbe.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jqgfzy.top/Article/details/gt2twlesnwo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj202588.top/Article/details/gt2iimkmwfo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zdqjudy.top/Article/details/gt2dshhfycd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.fzhhl.top/Article/details/gt2ehbshxii.html

[L05] 上传文件（multipart）
来源：http://dali.chenzaomai.com/Article/details/gt2xrbspxoj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cqqwz.cn/Article/details/gt2efhdeemi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2jxyfckza.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuxming.cn/Article/details/gt2kwdizmds.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigufen.top/Article/details/gt2jloufurm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.svipenyu.cn/Article/details/gt2dmhdvxdj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2nelkvrcl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigfzy.top/Article/details/gt2nscmqogg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2ihnbizui.html

[L06] 解析响应为 JSON
来源：http://dali.nwbrower.top/Article/details/gt2gtavktao.html

Py:   resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gt2rpqgmblj.html

PHP:  json_decode($body, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fjoxmbht.html

JS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nogaxmxk.html

TS:   await resp.json()
来源：http://dali.nanxinkj.top/Article/details/gt2wgxqgvvv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guannengcc.top/Article/details/gt2akahdumd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.havefunace.top/Article/details/gt2hntfpgko.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sweek.top/Article/details/gt2wgffdana.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xuetiantiany.cn/Article/details/gt2yvtxvlpd.html

[L07] 处理 HTTP 状态码
来源：http://dali.gotoacloud.top/Article/details/gt2mvdwhuwv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hongshengwenyu.top/Article/details/gt2pdcobkxn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhongyouzk.top/Article/details/gt2zvodhzlz.html

JS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gt2rhpwqzta.html

TS:   resp.ok;  resp.status
来源：http://dali.shzxlz.cn/Article/details/gt2zefiuuzy.html

Java: resp.statusCode()
来源：http://dali.ydzc1.top/Article/details/gt2whnjfors.html

Go:   resp.StatusCode
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vhdsuqoh.html

Ruby: resp.code.to_i
来源：http://dali.fengsongda.top/Article/details/gt2noenwjiv.html

C#:   (int)resp.StatusCode
来源：http://dali.yuxming.cn/Article/details/gt2oxjbxftd.html

[L08] 并发请求多个地址
来源：http://dali.svipenyu.cn/Article/details/gt2zdalbzwo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258888.top/Article/details/gt2xwhpwpxq.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangshuangyany.cn/Article/details/gt2rluylnvh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gt2yibtfvel.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guannengcc.top/Article/details/gt2gqrzryxu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nwbrower.top/Article/details/gt2nxdomdbo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hywenlv.cn/Article/details/gt2lstuxpcx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.daria6918.cn/Article/details/gt2nfiqlitd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.smart0.xyz/Article/details/gt2cuskkvgd.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2mpdomolc.html

M. 命令行 / 进程 / 环境
来源：http://dali.hnqzz.top/Article/details/gt2qlrlkalh.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2amvmbuiq.html

[M01] 读取命令行参数
来源：http://dali.ehwqpu.com/Article/details/gt2gsomhtxq.html

Py:   sys.argv[1:]
来源：http://dali.dashuyun.cn/Article/details/gt2kxxocdtj.html

PHP:  $argv;  $argc;
来源：http://dali.shuidangran.top/Article/details/gt2xjbbtexx.html

JS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2alvsfaih.html

TS:   process.argv.slice(2)
来源：http://dali.birdmap.top/Article/details/gt2tzwsatbo.html

Java: args 数组（main 方法参数）
来源：http://dali.nanxinkj.top/Article/details/gt2rvhftqkz.html

Go:   os.Args[1:]
来源：http://dali.9152youxi.cn/Article/details/gt2masnpjqr.html

Ruby: ARGV
来源：http://dali.shangyingyoupin.top/Article/details/gt2bgggpmgf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gt2jpqdtyma.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sqolrqud.html

Py:   os.environ.get("HOME")
来源：http://dali.yj202588.top/Article/details/gt2nrzvhems.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gt2zyuoxisj.html

JS:   process.env.HOME
来源：http://dali.iojbl.cn/Article/details/gt2jipnvelt.html

TS:   process.env.HOME
来源：http://dali.jlsjyb.cn/Article/details/gt2viuvsuzz.html

Java: System.getenv("HOME")
来源：http://dali.tianlin.xyz/Article/details/gt2jgiaoefz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nanxinkj.top/Article/details/gt2tahdvpuv.html

Ruby: ENV["HOME"]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dzzajedo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.mhx1999.top/Article/details/gt2iigkzzvy.html

[M03] 执行外部命令
来源：http://dali.hnqzz.top/Article/details/gt2cevwscld.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tian-w.cn/Article/details/gt2gezjchzp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuetiantiany.cn/Article/details/gt2gofbyitz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gt2biuhulrj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yongpay.top/Article/details/gt2gbmtpzhg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.havefunace.top/Article/details/gt2zrtebfvi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tian-w.cn/Article/details/gt2tbwnrkzj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.havefunace.top/Article/details/gt2wpjvxznn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.fengsongda.top/Article/details/gt2sxlviupq.html

[M04] 获取当前工作目录
来源：http://dali.cdnleiting.top/Article/details/gt2zmpcbjev.html

Py:   os.getcwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fxmsooat.html

PHP:  getcwd();
来源：http://dali.xinyue.icu/Article/details/gt2kiaxgcxt.html

JS:   process.cwd()
来源：http://dali.jqgufenzy.top/Article/details/gt2yhnjicmc.html

TS:   process.cwd()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ttqyxevy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xylfe.cn/Article/details/gt2vthiuvmp.html

Go:   os.Getwd()
来源：http://dali.xylfe.cn/Article/details/gt2emdazycu.html

Ruby: Dir.pwd
来源：http://dali.tian-w.cn/Article/details/gt2gugepjig.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rhlcpxji.html

[M05] 设置退出码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mdlvvjti.html

Py:   sys.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2vckwmryw.html

PHP:  exit(1);
来源：http://dali.hysaishi.cn/Article/details/gt2ewlvmxrx.html

JS:   process.exit(1)
来源：http://dali.yongpay.top/Article/details/gt2johcgqpn.html

TS:   process.exit(1)
来源：http://dali.havefunace.top/Article/details/gt2lzlektuh.html

Java: System.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gt2gkhiblkn.html

Go:   os.Exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2gcnisiyi.html

Ruby: exit 1
来源：http://dali.gzhubu.top/Article/details/gt2cueevauz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cqqwz.cn/Article/details/gt2qckdiyyq.html

[M06] 向标准错误输出
来源：http://dali.shzxlz.cn/Article/details/gt2holplbjh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.aibaodan.cn/Article/details/gt2yvfkwogp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.quarkkingdee.top/Article/details/gt2zknykrtu.html

JS:   console.error("err")
来源：http://dali.sxryk.cn/Article/details/gt2uhxoabiq.html

TS:   console.error("err")
来源：http://dali.fzhhl.top/Article/details/gt2tvlzcvmz.html

Java: System.err.println("err")
来源：http://dali.zdqjudy.top/Article/details/gt2yhtvpfim.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xylfe.cn/Article/details/gt2fzdxauhy.html

Ruby: warn "err"
来源：http://dali.pengpengdd.cyou/Article/details/gt2qwkgxwkr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gaohongyu789.top/Article/details/gt2ssoghufv.html

[M07] 判断是否为主入口
来源：http://dali.havefunace.top/Article/details/gt2lizcjzbl.html

Py:   if __name__ == "__main__":
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2owbtubnm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.haohaochexian.top/Article/details/gt2oyymdppk.html

JS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gt2fpywrarw.html

TS:   require.main === module
来源：http://dali.pycfn.com/Article/details/gt2vkvficyx.html

Java: public static void main(String[] args)
来源：http://dali.nwbrower.top/Article/details/gt2uvohuqzd.html

Go:   func main()
来源：http://dali.feifeiyinyue.top/Article/details/gt2igpardhm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuanzx.com/Article/details/gt2tgihxkcp.html

C#:   static void Main(string[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xpvshqww.html


<!-- 参考信息 -->