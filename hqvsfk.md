代发 wailian999

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gt2pczrpjqz.html

JS:   new Date();  Date.now()
来源：http://dali.jqgfzy.top/Article/details/gt2noysfron.html

TS:   new Date();  Date.now()
来源：http://dali.hammf.cn/Article/details/gt2lploiwna.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.meibo888.top/Article/details/gt2hacrizbz.html

Go:   time.Now()
来源：http://dali.tian-w.cn/Article/details/gt2avrnqvys.html

Ruby: Time.now
来源：http://dali.jyoumei.cn/Article/details/gt2abrpycxc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.9152youxi.cn/Article/details/gt2realgzia.html

[J02] 格式化输出
来源：http://dali.smart0.xyz/Article/details/gt2ytzyrpww.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fengsongda.top/Article/details/gt2yhoczjtv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hongshengwenyu.top/Article/details/gt2oqqbfxsu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.fengsongda.top/Article/details/gt2fjwgolqi.html

TS:   d.toISOString()
来源：http://dali.xylfe.cn/Article/details/gt2iweikxld.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenjidiqi.icu/Article/details/gt2gdesszxv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yangfankeji.com/Article/details/gt2iuikbvay.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ppjwa.cn/Article/details/gt2ekvwmejz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.dashuyun.cn/Article/details/gt2wyjdstad.html

[J03] 字符串解析为日期
来源：http://dali.nanxuanxn.top/Article/details/gt2igsztfwn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nblqkpst.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jqgufenzy.top/Article/details/gt2tchvavqr.html

JS:   new Date("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gt2cbshivfu.html

TS:   new Date("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gt2bceegzhk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nclavlhm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gt2aidxibut.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gt2ryomatlr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ivvv.top/Article/details/gt2dgdilhnq.html

[J04] 时间戳与日期互转
来源：http://dali.meibo888.top/Article/details/gt2jsdnrntw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cashguo.top/Article/details/gt2haefhenm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.andypj.xyz/Article/details/gt2qmhehtqh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jyoumei.cn/Article/details/gt2ekcmzhue.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenlongwang.top/Article/details/gt2bgytfldn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cldqzkfc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2frstltos.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wjaeahub.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yongpay.top/Article/details/gt2bsuokfpn.html

[J05] 时间加减（加 7 天）
来源：http://dali.aibaodan.cn/Article/details/gt2skedqife.html

Py:   now + timedelta(days=7)
来源：http://dali.haohaochexian.top/Article/details/gt2tedzojsw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sxryk.cn/Article/details/gt2gtfqbnzs.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.316326.xyz/Article/details/gt2twunauth.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daxiang520.top/Article/details/gt2xasnphfm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.smart0.xyz/Article/details/gt2ywytpkps.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.smart0.xyz/Article/details/gt2zuplmyot.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sysykeji.top/Article/details/gt2kzlrtcsj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jqgfzy.top/Article/details/gt2sgxxvdqz.html

[J06] 计算两时间之差
来源：http://dali.yongpay.top/Article/details/gt2ejtenzyd.html

Py:   (end - start).total_seconds()
来源：http://dali.9152youxi.cn/Article/details/gt2gjtcpjqt.html

PHP:  $end->diff($start)->days;
来源：http://dali.jqgfzy.top/Article/details/gt2yqzdvblr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sweek.top/Article/details/gt2lmkzsind.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xylfe.cn/Article/details/gt2cbycomeu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258888.top/Article/details/gt2nboxqyry.html

Go:   end.Sub(start).Hours()
来源：http://dali.tian-w.cn/Article/details/gt2btqogezh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nwbrower.top/Article/details/gt2kkbcqtoi.html

C#:   (end - start).TotalSeconds
来源：http://dali.yanxiufei.cn/Article/details/gt2bvfuvsya.html

[J07] 比较两个日期
来源：http://dali.jianghu66.top/Article/details/gt2lhnyklco.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gt2gdllbtfl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.vqdsnc.cn/Article/details/gt2udwebvgm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gt2wyosrqqv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rqepzspd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ybcxt.top/Article/details/gt2yzxnjacl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hfpthk.cn/Article/details/gt2uhwjbhkc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gt2iatxiuey.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gt2drrrulsy.html

[J08] 提取年月日与星期
来源：http://dali.hnqzz.top/Article/details/gt2ladquxsp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.pycfn.com/Article/details/gt2qaqmoqqd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnxiangtu.top/Article/details/gt2conkwatd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nanxinkj.top/Article/details/gt2shfqworh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tianlin.xyz/Article/details/gt2miuesogy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gogol.net.cn/Article/details/gt2hrdcffeo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cdnleiting.top/Article/details/gt2iggmojpl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sxryk.cn/Article/details/gt2yshybaaj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.meibo888.top/Article/details/gt2aqdfzykp.html

[J09] 时区处理
来源：http://dali.iojbl.cn/Article/details/gt2klwljkpv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sysykeji.top/Article/details/gt2vyinykjs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gt2maxrwlby.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yvedp.cn/Article/details/gt2nnxmyzqr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gt2yrtrrpdc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.0kj1m.cn/Article/details/gt2qbmikntu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.havefunace.top/Article/details/gt2ffgfmjvy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.haohaochexian.top/Article/details/gt2plgealaf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ssptpecv.html

[J10] 取今天 / 本月第一天
来源：http://dali.cqqwz.cn/Article/details/gt2cflrgypp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yuanzhike.top/Article/details/gt2ehzrrhzd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yueranfly.top/Article/details/gt2zpazodno.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhengqikj.top/Article/details/gt2xkfymqup.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vlbwaxil.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2ritcxdlh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cucudq.cn/Article/details/gt2sfmvzpml.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenjidiqi.icu/Article/details/gt2pyhcgllx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhongyouzk.top/Article/details/gt2aphnoskg.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2wvzexrme.html

K. JSON 与序列化
来源：http://dali.xylfe.cn/Article/details/gt2qozfostq.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2hnkiflfj.html

[K01] 对象转 JSON 字符串
来源：http://dali.fengsongda.top/Article/details/gt2pmxpnmfn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gt2zdsgrcax.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hammf.cn/Article/details/gt2lltpqgox.html

JS:   JSON.stringify(obj)
来源：http://dali.yueranfly.top/Article/details/gt2kemtncih.html

TS:   JSON.stringify(obj)
来源：http://dali.cucudq.cn/Article/details/gt2gqnlxrby.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gotoacloud.top/Article/details/gt2hknosmvd.html

Go:   json.Marshal(obj)
来源：http://dali.tanke756.top/Article/details/gt2qlivonob.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2blihxhec.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2mhcxhqfp.html

[K02] JSON 字符串转对象
来源：http://dali.birdmap.top/Article/details/gt2kpmkuohk.html

Py:   json.loads(s)
来源：http://dali.jinqigufen.top/Article/details/gt2ktxvhtec.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.vqdsnc.cn/Article/details/gt2xjdunfgr.html

JS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gt2cbmdwout.html

TS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gt2uoevcopp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yangfankeji.com/Article/details/gt2fnarocyt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bfmshbne.html

Ruby: JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gt2kibfnsww.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xylfe.cn/Article/details/gt2gxkpvoyt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.haohaochexian.top/Article/details/gt2zcjkwfcn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gt2gcxxgrsi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shzxlz.cn/Article/details/gt2flyxpybt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zycfv.cn/Article/details/gt2yljbsems.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gt2etwnahez.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uponjbap.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zdqjudy.top/Article/details/gt2mahddyra.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nwbrower.top/Article/details/gt2hokzkdyp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nwbrower.top/Article/details/gt2zezxuirc.html

[K04] 读取 JSON 文件
来源：http://dali.ivvv.top/Article/details/gt2pjxiwufs.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigufen.top/Article/details/gt2sxlysdiw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.redwolf501.top/Article/details/gt2esjphaxo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.haohaochexian.top/Article/details/gt2wisgtdvi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gt2soaiynew.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj202588.top/Article/details/gt2ugmjjjhy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gt2xyaqhgqf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2swzbinbh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jlsjyb.cn/Article/details/gt2yvgwlxwp.html

[K05] 深拷贝对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kdbfghxj.html

Py:   copy.deepcopy(obj)
来源：http://dali.daria6918.cn/Article/details/gt2pglwqzwe.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sufxvd.cn/Article/details/gt2rexjcvnn.html

JS:   structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2amkowqsj.html

TS:   structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gt2quvhvgcu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.guowangkeji.top/Article/details/gt2vurjezkt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.iojbl.cn/Article/details/gt2txuugzvs.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.redwolf501.top/Article/details/gt2nvmroyih.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhiwuduotai.top/Article/details/gt2mnbkiocg.html

[K06] 解析 URL 查询串
来源：http://dali.shzxlz.cn/Article/details/gt2qorlbyve.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xylfe.cn/Article/details/gt2zrxbnxhr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cashguo.top/Article/details/gt2bzdjaxye.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eflnanwa.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wuptdhck.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhiwuduotai.top/Article/details/gt2uymclbfc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gt2gvcfjinu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gt2tsafudmg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gt2uaoeycsr.html

[K07] 进制转换
来源：http://dali.yanxiufei.cn/Article/details/gt2wauncwqg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gt2jphpjqxv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cashguo.top/Article/details/gt2cusonahp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gt2xdurdmpf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qsykqozc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gt2jydbenbb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.snrcjt.cn/Article/details/gt2uecjtkiw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pycfn.com/Article/details/gt2egbkkuyf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2osxjsbhl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hfpthk.cn/Article/details/gt2scmrfnuf.html

Py:   pickle.dumps(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2gubwwbst.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ixfkeybv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gt2qdnjbzou.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gt2nkzcklwk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gzhubu.top/Article/details/gt2alqwsxxb.html

Go:   encoding/gob
来源：http://dali.wangdashe.top/Article/details/gt2tlltzeqq.html

Ruby: Marshal.dump(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2qnmfvalt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gt2ohxxyiub.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2styjzbja.html

L. 网络请求
来源：http://dali.mhx1999.top/Article/details/gt2yuwxgbkx.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2xilhfkax.html

[L01] 发送 GET 请求
来源：http://dali.cucudq.cn/Article/details/gt2wrxgxwry.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.aizwys.cn/Article/details/gt2ncuxbbtj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yanxiufei.cn/Article/details/gt2eghtvawu.html

JS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gt2bwzuzaoj.html

TS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gt2fzhxoian.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shangyingyoupin.top/Article/details/gt2pyxbfpou.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhixingplan.top/Article/details/gt2ckbomkvx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ivvv.top/Article/details/gt2iybhjygj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenzaomai.com/Article/details/gt2gtvhlnhw.html

[L02] 发送 POST JSON
来源：http://dali.yj202588.top/Article/details/gt2skjiwzuh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.0kj1m.cn/Article/details/gt2wayatwii.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenzaomai.com/Article/details/gt2irmdxabc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gt2ttfmqsff.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2kellvenc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.smart0.xyz/Article/details/gt2skwjgzbk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.daria6918.cn/Article/details/gt2hyqpdhhr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shzxlz.cn/Article/details/gt2wpicaelc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tian-w.cn/Article/details/gt2micicuhg.html

[L03] 设置自定义请求头
来源：http://dali.zhoulong.xyz/Article/details/gt2ipzoiqvy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhengqikj.top/Article/details/gt2uqrhedll.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hysaishi.cn/Article/details/gt2xnlnvhao.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gt2sfgxdbzt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gt2opctzcfw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jqgufenzy.top/Article/details/gt2nldfmbps.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.guannengcc.top/Article/details/gt2mhyyflwh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ehwqpu.com/Article/details/gt2kuaqqoxw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gt2mdehpcxg.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjbfnmx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jlsjyb.cn/Article/details/gt2ojqydkfw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj202588.top/Article/details/gt2pllnglhh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gt2uqujmdru.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.feifeiyinyue.top/Article/details/gt2vcznkgmt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.havefunace.top/Article/details/gt2yxcrgsdj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yueranfly.top/Article/details/gt2wlwjvkch.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.316326.xyz/Article/details/gt2idkaieyd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhongyouzk.top/Article/details/gt2oldxqguy.html

[L05] 上传文件（multipart）
来源：http://dali.sweek.top/Article/details/gt2hoavgjyd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yuanzhike.top/Article/details/gt2qzopaulv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258.top/Article/details/gt2jekyzqpl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.dashuyun.cn/Article/details/gt2jkjojlgk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yvedp.cn/Article/details/gt2wwnpsbzn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xuetiantiany.cn/Article/details/gt2mfmpcrww.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xylfe.cn/Article/details/gt2blcjming.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eohjdzqd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2asxmchne.html

[L06] 解析响应为 JSON
来源：http://dali.shzxlz.cn/Article/details/gt2quzijtzh.html

Py:   resp.json()
来源：http://dali.meibo888.top/Article/details/gt2pqynmkez.html

PHP:  json_decode($body, true);
来源：http://dali.gotoacloud.top/Article/details/gt2rgcnccdm.html

JS:   await resp.json()
来源：http://dali.chenlongwang.top/Article/details/gt2awfpxpck.html

TS:   await resp.json()
来源：http://dali.hfpthk.cn/Article/details/gt2xbxpmxij.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nwbrower.top/Article/details/gt2jpttqdyg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.dashuyun.cn/Article/details/gt2bouihrvh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jyoumei.cn/Article/details/gt2disyofts.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cucudq.cn/Article/details/gt2vxmdgcrl.html

[L07] 处理 HTTP 状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wgngwgna.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2amttqrxs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jqgfzy.top/Article/details/gt2xventxmk.html

JS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gt2ezrkxysq.html

TS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gt2qvpkpiwm.html

Java: resp.statusCode()
来源：http://dali.iojbl.cn/Article/details/gt2shiivjkx.html

Go:   resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gt2tyueecpq.html

Ruby: resp.code.to_i
来源：http://dali.meibo888.top/Article/details/gt2atgnxfhi.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxuanxn.top/Article/details/gt2aaihnfks.html

[L08] 并发请求多个地址
来源：http://dali.fengsongda.top/Article/details/gt2zqpkjwor.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ydzc1.top/Article/details/gt2jupcpwec.html

PHP:  curl_multi_init() 系列
来源：http://dali.shangyingyoupin.top/Article/details/gt2efgpasxk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gt2jgjtsiho.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnqzz.top/Article/details/gt2qvbvcyjn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.andypj.xyz/Article/details/gt2yjeenpzs.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hammf.cn/Article/details/gt2wbhmmpnt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.316326.xyz/Article/details/gt2uqhdxjvd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhongyouzk.top/Article/details/gt2sigblnqs.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ldyneyzk.html

M. 命令行 / 进程 / 环境
来源：http://dali.hammf.cn/Article/details/gt2nqfovjns.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2fxqwfyed.html

[M01] 读取命令行参数
来源：http://dali.sysykeji.top/Article/details/gt2natidxjr.html

Py:   sys.argv[1:]
来源：http://dali.mhx1999.top/Article/details/gt2efmjaeoh.html

PHP:  $argv;  $argc;
来源：http://dali.vqdsnc.cn/Article/details/gt2czuivfwb.html

JS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ybpvkduq.html

TS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gt2jzyuorbr.html

Java: args 数组（main 方法参数）
来源：http://dali.xuetiantiany.cn/Article/details/gt2lkdcvmmw.html

Go:   os.Args[1:]
来源：http://dali.sufxvd.cn/Article/details/gt2nxomodly.html

Ruby: ARGV
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tnivemsj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.fengsongda.top/Article/details/gt2udlavejf.html

[M02] 读取环境变量
来源：http://dali.zdqjudy.top/Article/details/gt2qvprxdsm.html

Py:   os.environ.get("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gt2yczivghc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gt2xloygmzx.html

JS:   process.env.HOME
来源：http://dali.jinqigufen.top/Article/details/gt2gpvewvcw.html

TS:   process.env.HOME
来源：http://dali.dashuyun.cn/Article/details/gt2rqiipiar.html

Java: System.getenv("HOME")
来源：http://dali.c1oappe.top/Article/details/gt2kvqmmxvi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kbgrdyxx.html

Ruby: ENV["HOME"]
来源：http://dali.havefunace.top/Article/details/gt2eqldqsza.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gt2ydhzzxlc.html

[M03] 执行外部命令
来源：http://dali.yangfankeji.com/Article/details/gt2yzrzfsrz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yonumen.top/Article/details/gt2hcsitqcx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.wangdashe.top/Article/details/gt2owwasmkz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gt2ydtaybtt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sufxvd.cn/Article/details/gt2euqfuxko.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nanxinkj.top/Article/details/gt2oicsltze.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.fzhhl.top/Article/details/gt2nivsswju.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.andypj.xyz/Article/details/gt2kzrdeubd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cqqwz.cn/Article/details/gt2ouayzccm.html

[M04] 获取当前工作目录
来源：http://dali.daria6918.cn/Article/details/gt2ountvlbv.html

Py:   os.getcwd()
来源：http://dali.jinqigufen.top/Article/details/gt2gpmugxtr.html

PHP:  getcwd();
来源：http://dali.ybcxt.top/Article/details/gt2ypvgiaom.html

JS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gt2dahrigyu.html

TS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gt2ghfhivmg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ybcxt.top/Article/details/gt2yvumtsyf.html

Go:   os.Getwd()
来源：http://dali.daxiang520.top/Article/details/gt2fcvnguvd.html

Ruby: Dir.pwd
来源：http://dali.redwolf501.top/Article/details/gt2lornmzby.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sweek.top/Article/details/gt2xwraheak.html

[M05] 设置退出码
来源：http://dali.jyoumei.cn/Article/details/gt2gkzokfyv.html

Py:   sys.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gt2joexxkef.html

PHP:  exit(1);
来源：http://dali.sufxvd.cn/Article/details/gt2xtywobar.html

JS:   process.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ktoxfgqz.html

TS:   process.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gt2bnwxczyt.html

Java: System.exit(1)
来源：http://dali.daria6918.cn/Article/details/gt2cjzvpkxr.html

Go:   os.Exit(1)
来源：http://dali.shuidangran.top/Article/details/gt2maynrkyn.html

Ruby: exit 1
来源：http://dali.jinqigfzy.top/Article/details/gt2nbbxoqwl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dtslugvk.html

[M06] 向标准错误输出
来源：http://dali.dianchejie.cn/Article/details/gt2tgrfrbin.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sweek.top/Article/details/gt2ibziomxz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cheryme.top/Article/details/gt2ceuboubv.html

JS:   console.error("err")
来源：http://dali.fengsongda.top/Article/details/gt2ztzmkdue.html

TS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gt2ocmoqlyj.html

Java: System.err.println("err")
来源：http://dali.tianlin.xyz/Article/details/gt2aefnicxz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgufenzy.top/Article/details/gt2etogloiv.html

Ruby: warn "err"
来源：http://dali.hnxiangtu.top/Article/details/gt2enbehubh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenlongwang.top/Article/details/gt2hnklheof.html

[M07] 判断是否为主入口
来源：http://dali.zhiwuduotai.top/Article/details/gt2zvsrpdfw.html

Py:   if __name__ == "__main__":
来源：http://dali.iojbl.cn/Article/details/gt2fxxcgxsw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.svipenyu.cn/Article/details/gt2komnlxhr.html

JS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gt2emkndoch.html

TS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2juytmzkv.html


<!-- 参考信息 -->