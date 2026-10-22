代发 wailian999

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shzxlz.cn/Article/details/gt2gmyrwqtz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.guowangkeji.top/Article/details/gt2kiratmyv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xinyue.icu/Article/details/gt2hlrvrphe.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tian-w.cn/Article/details/gt2apxsaoof.html

[J03] 字符串解析为日期
来源：http://dali.yj20258888.top/Article/details/gt2gfvkudna.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hnqzz.top/Article/details/gt2mrhqhejj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ivvv.top/Article/details/gt2bwgumlks.html

JS:   new Date("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gt2imbuepml.html

TS:   new Date("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gt2uxkrbaiz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gt2xfetwvml.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gt2erphpwgw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gt2vmwrgttu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ivvv.top/Article/details/gt2wgqlrrsc.html

[J04] 时间戳与日期互转
来源：http://dali.smart0.xyz/Article/details/gt2fdgezsnr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.aibaodan.cn/Article/details/gt2jvdqsvpd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.vqdsnc.cn/Article/details/gt2lsuuajlx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.iojbl.cn/Article/details/gt2meqirkow.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tqfuqvhn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.smart0.xyz/Article/details/gt2ybfpzcgy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hammf.cn/Article/details/gt2debjkjhv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hnxiangtu.top/Article/details/gt2ouiziuko.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhengqikj.top/Article/details/gt2dnozlnlk.html

[J05] 时间加减（加 7 天）
来源：http://dali.redwolf501.top/Article/details/gt2vpqlhijs.html

Py:   now + timedelta(days=7)
来源：http://dali.ehwqpu.com/Article/details/gt2rxxvrchk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xuanzx.com/Article/details/gt2ccazpxhj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gt2jstufhfq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gt2gnabfcnp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.wangdashe.top/Article/details/gt2mfenabde.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenzaomai.com/Article/details/gt2gqpjuzdn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xziqi.cn/Article/details/gt2mykuhlny.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xuanzx.com/Article/details/gt2ougfhjgh.html

[J06] 计算两时间之差
来源：http://dali.tian-w.cn/Article/details/gt2egmnnszz.html

Py:   (end - start).total_seconds()
来源：http://dali.fzhhl.top/Article/details/gt2zzjzopcw.html

PHP:  $end->diff($start)->days;
来源：http://dali.pengpengdd.cyou/Article/details/gt2jizeieyf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dsanmsbd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yongpay.top/Article/details/gt2rifmaifa.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sxryk.cn/Article/details/gt2bcqwvcrp.html

Go:   end.Sub(start).Hours()
来源：http://dali.guannengcc.top/Article/details/gt2sgxmmqgn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shangyingyoupin.top/Article/details/gt2gibnagcx.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhiwuduotai.top/Article/details/gt2uqchtlhq.html

[J07] 比较两个日期
来源：http://dali.meibo888.top/Article/details/gt2vxloypwt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gt2ffbupxdf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jiagoushi.top/Article/details/gt2rvixmufv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gt2hvroonkr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gt2pymidbuc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sysykeji.top/Article/details/gt2frovmdug.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yangfankeji.com/Article/details/gt2awmrcxom.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gt2aygyqnur.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gt2ftktmeno.html

[J08] 提取年月日与星期
来源：http://dali.hongshengwenyu.top/Article/details/gt2kktrmyxx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xziqi.cn/Article/details/gt2muraivjh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.316326.xyz/Article/details/gt2haqsynlw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hammf.cn/Article/details/gt2gkllxwib.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nwbrower.top/Article/details/gt2rtebhrxu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yonumen.top/Article/details/gt2llawezgy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.iojbl.cn/Article/details/gt2mvwbizha.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.smart0.xyz/Article/details/gt2zdmhyjcn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gpajhxuc.html

[J09] 时区处理
来源：http://dali.zdqjudy.top/Article/details/gt2ajiffhfn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shuidangran.top/Article/details/gt2bckfknug.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.quarkkingdee.top/Article/details/gt2gvslhfao.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dujopion.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gt2bilzkiki.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hrcqsxou.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.daria6918.cn/Article/details/gt2ltrxwrtd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jiagoushi.top/Article/details/gt2figqalrs.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jyoumei.cn/Article/details/gt2iydkidgw.html

[J10] 取今天 / 本月第一天
来源：http://dali.bjfxy.top/Article/details/gt2qksvpuzq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cheryme.top/Article/details/gt2stzkvrti.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.9152youxi.cn/Article/details/gt2vmqjcjok.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mdlhipqo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fengsongda.top/Article/details/gt2zbdtavlm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.iojbl.cn/Article/details/gt2gpzaqpak.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj202588.top/Article/details/gt2yrjytjsm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.smart0.xyz/Article/details/gt2vnrgknff.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ybcxt.top/Article/details/gt2sgmcfqym.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2nyvxnbgd.html

K. JSON 与序列化
来源：http://dali.jianghu66.top/Article/details/gt2knezjtbl.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2bglrwfph.html

[K01] 对象转 JSON 字符串
来源：http://dali.redwolf501.top/Article/details/gt2aplxclgr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gt2jsuntojg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gt2vujbzbrb.html

JS:   JSON.stringify(obj)
来源：http://dali.c1oappe.top/Article/details/gt2qcxbrdbh.html

TS:   JSON.stringify(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2apmesehf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cucudq.cn/Article/details/gt2ebzlhxhb.html

Go:   json.Marshal(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2dlhifigu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenjidiqi.icu/Article/details/gt2fiwjpflg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sysykeji.top/Article/details/gt2jngkeoxd.html

[K02] JSON 字符串转对象
来源：http://dali.zhoulong.xyz/Article/details/gt2guavrboh.html

Py:   json.loads(s)
来源：http://dali.jyoumei.cn/Article/details/gt2oswetktu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hammf.cn/Article/details/gt2ysrwxquh.html

JS:   JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gt2nenrnxzf.html

TS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2rjbtpuku.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.snrcjt.cn/Article/details/gt2txexqakx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ybcxt.top/Article/details/gt2zlkljkht.html

Ruby: JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2agbhvifn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yonumen.top/Article/details/gt2qxqdbpqg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hnxiangtu.top/Article/details/gt2dbafalfz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jqgufenzy.top/Article/details/gt2xoemecjg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.meibo888.top/Article/details/gt2yeorqfan.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258.top/Article/details/gt2kijgvtpp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gt2umfqibaf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2haqukqwq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhoulong.xyz/Article/details/gt2kspxbweb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.bjfxy.top/Article/details/gt2avtecbui.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuanzhike.top/Article/details/gt2loognahz.html

[K04] 读取 JSON 文件
来源：http://dali.ppjwa.cn/Article/details/gt2vpgszvyg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2neaykurt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hnqzz.top/Article/details/gt2uleqoxws.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tian-w.cn/Article/details/gt2llrrcane.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gt2pmbjncgi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gt2yullyteu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hysaishi.cn/Article/details/gt2pfmjdlyd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2tdtsbojt.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2attoapar.html

[K05] 深拷贝对象
来源：http://dali.ybcxt.top/Article/details/gt2ybhkqkrf.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2obqujzfv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ydzc1.top/Article/details/gt2lpdhqiyx.html

JS:   structuredClone(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2plbsuahx.html

TS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ogiifxrf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tian-w.cn/Article/details/gt2cjmdviiy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gogol.net.cn/Article/details/gt2mmfgiuou.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tanke756.top/Article/details/gt2bofddwtb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ydzc1.top/Article/details/gt2khqqskdh.html

[K06] 解析 URL 查询串
来源：http://dali.hongshengwenyu.top/Article/details/gt2yhiwyhpq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.iojbl.cn/Article/details/gt2ktlfdlrz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.0kj1m.cn/Article/details/gt2zubeopcr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnqzz.top/Article/details/gt2mdpmqctb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ybcxt.top/Article/details/gt2thcrnvrr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.kuanghao11.cn/Article/details/gt2hajskuhj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gt2zectfoja.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gt2tdrjlcmd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gt2oslyvqus.html

[K07] 进制转换
来源：http://dali.c1oappe.top/Article/details/gt2gprqcrlj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gt2xfhamejp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aizwys.cn/Article/details/gt2vjthpdsb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gt2yjkgulkb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gt2jpwnmdxe.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gt2tzvpcuqf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgufenzy.top/Article/details/gt2xknpkajc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.9152youxi.cn/Article/details/gt2jyrblade.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gt2gyxgcojl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shuidangran.top/Article/details/gt2nnhhqyuc.html

Py:   pickle.dumps(obj)
来源：http://dali.nwbrower.top/Article/details/gt2rllwvukh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2nueqfdxa.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gt2dwkxhsch.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jyoumei.cn/Article/details/gt2jotgwech.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenjidiqi.icu/Article/details/gt2kkvlalzs.html

Go:   encoding/gob
来源：http://dali.yanxiufei.cn/Article/details/gt2droatgol.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj202588.top/Article/details/gt2whimfkyk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nxcaioel.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2jfhijoxu.html

L. 网络请求
来源：http://dali.mhx1999.top/Article/details/gt2uaqbzhdt.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2zfnjwhza.html

[L01] 发送 GET 请求
来源：http://dali.xuetiantiany.cn/Article/details/gt2hvmrqdzr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.wangdashe.top/Article/details/gt2cytklieg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ppjwa.cn/Article/details/gt2hqgkscpz.html

JS:   await fetch(url)
来源：http://dali.yuxming.cn/Article/details/gt2dlhilycd.html

TS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gt2ubszfibl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.mhx1999.top/Article/details/gt2clxzbpyn.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigfzy.top/Article/details/gt2uefwnoaf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.haohaochexian.top/Article/details/gt2sopysnpz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.aibaodan.cn/Article/details/gt2nfbkjnel.html

[L02] 发送 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2muftdmsy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jianghu66.top/Article/details/gt2oxmnrgkz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gotoacloud.top/Article/details/gt2ivohoagw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jiagoushi.top/Article/details/gt2fcijvgqa.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangdashe.top/Article/details/gt2mctiycen.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cqqwz.cn/Article/details/gt2devhyhqp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenzaomai.com/Article/details/gt2zhnlbhdw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ehwqpu.com/Article/details/gt2gzysrmch.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guowangkeji.top/Article/details/gt2wkmbljpi.html

[L03] 设置自定义请求头
来源：http://dali.tian-w.cn/Article/details/gt2kiwkkeal.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zdqjudy.top/Article/details/gt2izbpuxim.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sysykeji.top/Article/details/gt2zanfgfny.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tanke756.top/Article/details/gt2dqyrvpbs.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigfzy.top/Article/details/gt2nhmkgppc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.9152youxi.cn/Article/details/gt2eenmolie.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.guannengcc.top/Article/details/gt2aqarldea.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xziqi.cn/Article/details/gt2mfpneymt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cashguo.top/Article/details/gt2aiumhnzs.html

[L04] 设置超时
来源：http://dali.meibo888.top/Article/details/gt2ozlxxojm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yangfankeji.com/Article/details/gt2rzjcckmc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cashguo.top/Article/details/gt2etvrlmfz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgufenzy.top/Article/details/gt2ltimkswr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.feifeiyinyue.top/Article/details/gt2harvgyht.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ydzc1.top/Article/details/gt2wwiyfdop.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cucudq.cn/Article/details/gt2dcxalzzj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sxryk.cn/Article/details/gt2epnwukfz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hywenlv.cn/Article/details/gt2mfkraemb.html

[L05] 上传文件（multipart）
来源：http://dali.xziqi.cn/Article/details/gt2ikuevjen.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yongpay.top/Article/details/gt2mqbfsazi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jyoumei.cn/Article/details/gt2dloaligo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gt2qoluanao.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.mhx1999.top/Article/details/gt2gkuueliu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.mhx1999.top/Article/details/gt2icxybdzs.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fcsvdaof.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.pycfn.com/Article/details/gt2osjxryae.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2evrveoet.html

[L06] 解析响应为 JSON
来源：http://dali.hfpthk.cn/Article/details/gt2qwuldqvo.html

Py:   resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ciqnsuhg.html

PHP:  json_decode($body, true);
来源：http://dali.gzhubu.top/Article/details/gt2azqfhcxc.html

JS:   await resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gt2athivyqp.html

TS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bzxyxppz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenzaomai.com/Article/details/gt2bkpdncgq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.c1oappe.top/Article/details/gt2lxpovguw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ybcxt.top/Article/details/gt2pmsgkyhx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.andypj.xyz/Article/details/gt2wxdtzegi.html

[L07] 处理 HTTP 状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2calmvqka.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ybcxt.top/Article/details/gt2uyqqagis.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.quarkkingdee.top/Article/details/gt2ralgzomy.html

JS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gt2fptjtmkv.html

TS:   resp.ok;  resp.status
来源：http://dali.cdnleiting.top/Article/details/gt2hbnvmcss.html

Java: resp.statusCode()
来源：http://dali.316326.xyz/Article/details/gt2odrylgzz.html

Go:   resp.StatusCode
来源：http://dali.jlsjyb.cn/Article/details/gt2yfkpqzdw.html

Ruby: resp.code.to_i
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2corbindx.html

C#:   (int)resp.StatusCode
来源：http://dali.svipenyu.cn/Article/details/gt2yogjsivy.html

[L08] 并发请求多个地址
来源：http://dali.vqdsnc.cn/Article/details/gt2oibjznvd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iiultuhh.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2occprxtu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gt2dzsxdbme.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gt2rzfadema.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuxming.cn/Article/details/gt2pmmnnpoi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ppjwa.cn/Article/details/gt2bbfdiovu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.aizwys.cn/Article/details/gt2ityhvvkg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jyoumei.cn/Article/details/gt2dxnxkoyv.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2zunapvti.html

M. 命令行 / 进程 / 环境
来源：http://dali.shuidangran.top/Article/details/gt2iqfzgplz.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2wdfweiie.html

[M01] 读取命令行参数
来源：http://dali.meibo888.top/Article/details/gt2bnbgtrci.html

Py:   sys.argv[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gt2ndxtanah.html

PHP:  $argv;  $argc;
来源：http://dali.jlsjyb.cn/Article/details/gt2lbeezrhc.html

JS:   process.argv.slice(2)
来源：http://dali.sxryk.cn/Article/details/gt2thhqpumo.html

TS:   process.argv.slice(2)
来源：http://dali.yangfankeji.com/Article/details/gt2ljbzoxig.html

Java: args 数组（main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sympdflk.html

Go:   os.Args[1:]
来源：http://dali.mhx1999.top/Article/details/gt2tlrsdhrd.html

Ruby: ARGV
来源：http://dali.yj20258.top/Article/details/gt2qotvoceq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sweek.top/Article/details/gt2wjcolhzf.html

[M02] 读取环境变量
来源：http://dali.snrcjt.cn/Article/details/gt2dbzfswat.html

Py:   os.environ.get("HOME")
来源：http://dali.hfpthk.cn/Article/details/gt2uorqnmxq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pycfn.com/Article/details/gt2edyjjtxq.html

JS:   process.env.HOME
来源：http://dali.cqqwz.cn/Article/details/gt2ovlorrau.html

TS:   process.env.HOME
来源：http://dali.jiagoushi.top/Article/details/gt2pazmjfdh.html

Java: System.getenv("HOME")
来源：http://dali.guowangkeji.top/Article/details/gt2ttkesimq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jyoumei.cn/Article/details/gt2zbsdecad.html

Ruby: ENV["HOME"]
来源：http://dali.ppjwa.cn/Article/details/gt2zsjyhvck.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gt2rprgmvfj.html

[M03] 执行外部命令
来源：http://dali.ybcxt.top/Article/details/gt2wryurhyp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rgwcohxz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.dianchejie.cn/Article/details/gt2emifdbsi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2izboirls.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gt2vlypaqhh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.daxiang520.top/Article/details/gt2jbxiiogu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gogol.net.cn/Article/details/gt2heouifvi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.fzhhl.top/Article/details/gt2oinrdyvp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.fengsongda.top/Article/details/gt2ggfnuexo.html

[M04] 获取当前工作目录
来源：http://dali.xylfe.cn/Article/details/gt2cwkgzqbd.html

Py:   os.getcwd()
来源：http://dali.snrcjt.cn/Article/details/gt2ypirrzvq.html

PHP:  getcwd();
来源：http://dali.andypj.xyz/Article/details/gt2dbvgshcb.html

JS:   process.cwd()
来源：http://dali.redwolf501.top/Article/details/gt2lwigjthw.html

TS:   process.cwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cfgqlzff.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.svipenyu.cn/Article/details/gt2dngqnhxt.html

Go:   os.Getwd()
来源：http://dali.kuanghao11.cn/Article/details/gt2dzzzibgp.html

Ruby: Dir.pwd
来源：http://dali.zhongyouzk.top/Article/details/gt2slltqfdi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj20258.top/Article/details/gt2vrchfigf.html

[M05] 设置退出码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uzvwbote.html

Py:   sys.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rqgegvfb.html

PHP:  exit(1);
来源：http://dali.zhengqikj.top/Article/details/gt2xlrrpypl.html

JS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2llwdsmho.html

TS:   process.exit(1)
来源：http://dali.wangdashe.top/Article/details/gt2ogivaurx.html

Java: System.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2jujnlciz.html

Go:   os.Exit(1)
来源：http://dali.tianlin.xyz/Article/details/gt2jwoioyth.html

Ruby: exit 1
来源：http://dali.smart0.xyz/Article/details/gt2tmurndxw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fzhhl.top/Article/details/gt2xftwsugq.html

[M06] 向标准错误输出
来源：http://dali.xylfe.cn/Article/details/gt2usirslsy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2evtcgmpp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hywenlv.cn/Article/details/gt2njxqrqvs.html

JS:   console.error("err")
来源：http://dali.cucudq.cn/Article/details/gt2yiczkpgp.html

TS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gt2pkvpmxzs.html

Java: System.err.println("err")
来源：http://dali.smart0.xyz/Article/details/gt2mmnmttwz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.bjfxy.top/Article/details/gt2bswwoalf.html

Ruby: warn "err"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hokgsrek.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.daria6918.cn/Article/details/gt2mgfsrebw.html

[M07] 判断是否为主入口
来源：http://dali.chenjidiqi.icu/Article/details/gt2hzsgkmdk.html

Py:   if __name__ == "__main__":
来源：http://dali.hongshengwenyu.top/Article/details/gt2sxmhpyxn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gaohongyu789.top/Article/details/gt2wnieeckf.html

JS:   require.main === module
来源：http://dali.yueranfly.top/Article/details/gt2kaofoqrk.html

TS:   require.main === module
来源：http://dali.shzxlz.cn/Article/details/gt2reqzijbb.html

Java: public static void main(String[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kuhpegyb.html

Go:   func main()
来源：http://dali.yongpay.top/Article/details/gt2aavqywmj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ydzc1.top/Article/details/gt2fobiwhnx.html

C#:   static void Main(string[] args)
来源：http://dali.wangdashe.top/Article/details/gt2cjhqbjwe.html

[M08] 获取系统与运行时信息
来源：http://dali.quarkkingdee.top/Article/details/gt2rcghspam.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sxryk.cn/Article/details/gt2nnnzcvhf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgufenzy.top/Article/details/gt2lxtspkai.html

JS:   process.platform;  process.version
来源：http://dali.ydzc1.top/Article/details/gt2htfceeux.html

TS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gt2oboizegy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hfpthk.cn/Article/details/gt2sktfogid.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yuanzhike.top/Article/details/gt2lxndukuq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuxming.cn/Article/details/gt2zfkfhxmm.html


<!-- 参考信息 -->