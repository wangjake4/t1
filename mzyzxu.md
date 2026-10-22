代发 wailian999

Go:   time.Now()
来源：http://dali.meibo888.top/Article/details/gt2zqtnwwsa.html

Ruby: Time.now
来源：http://dali.kuanghao11.cn/Article/details/gt2iimopwkz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cqqwz.cn/Article/details/gt2jouvglyf.html

[J02] 格式化输出
来源：http://dali.mhx1999.top/Article/details/gt2lylaleqv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tanke756.top/Article/details/gt2yhqpkczj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sysykeji.top/Article/details/gt2jjsdzhjw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bjbyrjao.html

TS:   d.toISOString()
来源：http://dali.zhixingplan.top/Article/details/gt2cpjopyhr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.c1oappe.top/Article/details/gt2rmcxplcc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cqeiyamt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ppjwa.cn/Article/details/gt2fneprsyq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daxiang520.top/Article/details/gt2ltxndeyh.html

[J03] 字符串解析为日期
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vuiemioe.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhiwuduotai.top/Article/details/gt2fgapqyef.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hammf.cn/Article/details/gt2jjgsbmrr.html

JS:   new Date("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gt2phrvbfkk.html

TS:   new Date("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gt2syjxgilf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rlanpotz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2mtsghefy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gt2yaogmevm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gogol.net.cn/Article/details/gt2etggbvfr.html

[J04] 时间戳与日期互转
来源：http://dali.xuanzx.com/Article/details/gt2ffkoqdlx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mjfehpnn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jiagoushi.top/Article/details/gt2uomchwlf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tpjlywbg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gotoacloud.top/Article/details/gt2qaqtmmpb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenlongwang.top/Article/details/gt2drwrenap.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yvedp.cn/Article/details/gt2xeeyqodv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgfzy.top/Article/details/gt2yedinaru.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nwbrower.top/Article/details/gt2uxxrbjpw.html

[J05] 时间加减（加 7 天）
来源：http://dali.gaohongyu789.top/Article/details/gt2uxmzjauw.html

Py:   now + timedelta(days=7)
来源：http://dali.vqdsnc.cn/Article/details/gt2sqodyejr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.dianchejie.cn/Article/details/gt2nekwbbsy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sysykeji.top/Article/details/gt2idolowan.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cdnleiting.top/Article/details/gt2vwrbuzve.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gzhubu.top/Article/details/gt2heyltzbb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ydzc1.top/Article/details/gt2rfaofvev.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hammf.cn/Article/details/gt2srteiofj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.aibaodan.cn/Article/details/gt2zbbpkjfs.html

[J06] 计算两时间之差
来源：http://dali.svipenyu.cn/Article/details/gt2antjqiva.html

Py:   (end - start).total_seconds()
来源：http://dali.ybcxt.top/Article/details/gt2drgxmkvj.html

PHP:  $end->diff($start)->days;
来源：http://dali.jqgfzy.top/Article/details/gt2djxqveby.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuanzhike.top/Article/details/gt2yxythapa.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sweek.top/Article/details/gt2euwhmkzx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hnxiangtu.top/Article/details/gt2gctodcxg.html

Go:   end.Sub(start).Hours()
来源：http://dali.havefunace.top/Article/details/gt2noxldcip.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jqgfzy.top/Article/details/gt2ivouwwqb.html

C#:   (end - start).TotalSeconds
来源：http://dali.aibaodan.cn/Article/details/gt2czgzbjkz.html

[J07] 比较两个日期
来源：http://dali.zhiwuduotai.top/Article/details/gt2matlciix.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gt2xwjctfcz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zycfv.cn/Article/details/gt2pxzyhpye.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sweek.top/Article/details/gt2vsnbywoz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yanxiufei.cn/Article/details/gt2wwwxswjc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj20258.top/Article/details/gt2zwvdsqnq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.wangdashe.top/Article/details/gt2sutxwuvn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gt2nqegbont.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gt2jaozpvwk.html

[J08] 提取年月日与星期
来源：http://dali.andypj.xyz/Article/details/gt2dktazjtz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sweek.top/Article/details/gt2tenafwpp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenzaomai.com/Article/details/gt2snrawmqj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuanzhike.top/Article/details/gt2deukvadr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ppjwa.cn/Article/details/gt2voeveopm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj202588.top/Article/details/gt2ejvktsli.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.wangdashe.top/Article/details/gt2ejctvshv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.feifeiyinyue.top/Article/details/gt2olfsizui.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fengsongda.top/Article/details/gt2isqbbrky.html

[J09] 时区处理
来源：http://dali.aizwys.cn/Article/details/gt2kjzimchg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hysaishi.cn/Article/details/gt2nvjxkjzy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zycfv.cn/Article/details/gt2vmzwotzs.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mcgorgeg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fengsongda.top/Article/details/gt2sktgfgxu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.c1oappe.top/Article/details/gt2jdwcamea.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.c1oappe.top/Article/details/gt2ajiyhaex.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenzaomai.com/Article/details/gt2xojthnxm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sxryk.cn/Article/details/gt2htzaybxd.html

[J10] 取今天 / 本月第一天
来源：http://dali.smart0.xyz/Article/details/gt2hhsvsedi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zgqziltw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jlsjyb.cn/Article/details/gt2djcdwiuu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2iqzisfrx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2xhaqyfrg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.c1oappe.top/Article/details/gt2edgmpnmy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxinkj.top/Article/details/gt2dmogvgkp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hywenlv.cn/Article/details/gt2cfwfmvli.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ydzc1.top/Article/details/gt2rrucixhy.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2ooybbavs.html

K. JSON 与序列化
来源：http://dali.jinqigufen.top/Article/details/gt2jhzdqgdw.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2tfsccnmy.html

[K01] 对象转 JSON 字符串
来源：http://dali.c1oappe.top/Article/details/gt2iohcuxem.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.pycfn.com/Article/details/gt2lveyvvzd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hywenlv.cn/Article/details/gt2hrvqsyan.html

JS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2xmrnpsdv.html

TS:   JSON.stringify(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hijjtnzr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shzxlz.cn/Article/details/gt2bbykplrf.html

Go:   json.Marshal(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2aluyxhoq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yueranfly.top/Article/details/gt2wwkdjxos.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eobztsju.html

[K02] JSON 字符串转对象
来源：http://dali.yvedp.cn/Article/details/gt2dtseurvh.html

Py:   json.loads(s)
来源：http://dali.hnqzz.top/Article/details/gt2ojqmtysm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jyoumei.cn/Article/details/gt2mmbdssll.html

JS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gt2knohvxeq.html

TS:   JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gt2hloakzkq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.svipenyu.cn/Article/details/gt2ipzlwosa.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.andypj.xyz/Article/details/gt2rjcmqemw.html

Ruby: JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gt2qsobvvqp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cdnleiting.top/Article/details/gt2owcpsfdf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kxdnxjff.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.kuanghao11.cn/Article/details/gt2lcdssinh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gt2mtcrphxz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gt2dyoxqosd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gt2ultzfspt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.andypj.xyz/Article/details/gt2wrdflxkf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.aizwys.cn/Article/details/gt2hvkusmhm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.mhx1999.top/Article/details/gt2bcmvmidh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yongpay.top/Article/details/gt2ynyozttu.html

[K04] 读取 JSON 文件
来源：http://dali.shzxlz.cn/Article/details/gt2tyhmgwvm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kwuefofa.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lkjdsnxb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gt2xzjfxpfl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gt2egjtvylb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.daxiang520.top/Article/details/gt2rmdjhrgd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.mhx1999.top/Article/details/gt2hyttuwbz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gt2wtpkslei.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2kclybsks.html

[K05] 深拷贝对象
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yhshqfay.html

Py:   copy.deepcopy(obj)
来源：http://dali.aizwys.cn/Article/details/gt2manebidv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xuetiantiany.cn/Article/details/gt2fszbhepl.html

JS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gt2ahbkxbdg.html

TS:   structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lstzxqbg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ydzc1.top/Article/details/gt2fgjwevhu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.fzhhl.top/Article/details/gt2fegyiedm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhixingplan.top/Article/details/gt2frwylasc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.snrcjt.cn/Article/details/gt2ceamokyh.html

[K06] 解析 URL 查询串
来源：http://dali.gaohongyu789.top/Article/details/gt2bonqwntt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xziqi.cn/Article/details/gt2uopuinlg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hnxiangtu.top/Article/details/gt2awmtwtof.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhixingplan.top/Article/details/gt2cmcwkuxl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2pvkrdvvy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenjidiqi.icu/Article/details/gt2apdqawkz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.dashuyun.cn/Article/details/gt2zaaiypfr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gt2fstfnmej.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gt2jklftdnd.html

[K07] 进制转换
来源：http://dali.zdqjudy.top/Article/details/gt2eseynjxf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gt2egwvqitw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cucudq.cn/Article/details/gt2xlznbckq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gt2djidxoyj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gt2vnfhnpbz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gt2ykljvapf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.dashuyun.cn/Article/details/gt2fflvywwi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daria6918.cn/Article/details/gt2blzjxcyz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2fxzrvena.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sxryk.cn/Article/details/gt2nmrdrbqh.html

Py:   pickle.dumps(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2mkcttrjg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2eyomluev.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shangyingyoupin.top/Article/details/gt2kdcyfgsm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jianghu66.top/Article/details/gt2tqadrdog.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.316326.xyz/Article/details/gt2aecdudnp.html

Go:   encoding/gob
来源：http://dali.haohaochexian.top/Article/details/gt2zwxrhkgj.html

Ruby: Marshal.dump(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2pubgwisq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cdnleiting.top/Article/details/gt2szijdjlm.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2relknsqj.html

L. 网络请求
来源：http://dali.fengsongda.top/Article/details/gt2phodcbjm.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2znakzwdd.html

[L01] 发送 GET 请求
来源：http://dali.tanke756.top/Article/details/gt2kcepxbye.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shangyingyoupin.top/Article/details/gt2bimezpho.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.wangshuangyany.cn/Article/details/gt2wgifstsm.html

JS:   await fetch(url)
来源：http://dali.guowangkeji.top/Article/details/gt2ncttwkyz.html

TS:   await fetch(url)
来源：http://dali.hysaishi.cn/Article/details/gt2fripexub.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ybcxt.top/Article/details/gt2derpyzhc.html

Go:   resp, err := http.Get(url)
来源：http://dali.yangfankeji.com/Article/details/gt2tdjexvqq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hammf.cn/Article/details/gt2imbguimx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yongpay.top/Article/details/gt2dhrjrfbt.html

[L02] 发送 POST JSON
来源：http://dali.hfpthk.cn/Article/details/gt2wausthxw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hammf.cn/Article/details/gt2cnnxqskr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sysykeji.top/Article/details/gt2xtbsvznz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnxiangtu.top/Article/details/gt2tebtmels.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gzhubu.top/Article/details/gt2fxukegaw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.dashuyun.cn/Article/details/gt2kkzpefkw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yonumen.top/Article/details/gt2vhphblhs.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zycfv.cn/Article/details/gt2rqyuauwb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jianghu66.top/Article/details/gt2kcuogvbw.html

[L03] 设置自定义请求头
来源：http://dali.tanke756.top/Article/details/gt2ijwgebuw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.pycfn.com/Article/details/gt2yopntnnm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gaohongyu789.top/Article/details/gt2ynhzcwsr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guowangkeji.top/Article/details/gt2gdxbpgdh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gt2rfzuqpoh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yanxiufei.cn/Article/details/gt2mrlscdmx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gt2xyawzgmm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnxiangtu.top/Article/details/gt2nbxumulz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nwbrower.top/Article/details/gt2untywjyl.html

[L04] 设置超时
来源：http://dali.svipenyu.cn/Article/details/gt2awcmouxa.html

Py:   requests.get(url, timeout=5)
来源：http://dali.fengsongda.top/Article/details/gt2gobncxoc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jyoumei.cn/Article/details/gt2nkuiauoh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gt2hfkskxcx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gt2qkowigyc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.pengpengdd.cyou/Article/details/gt2zvnlgwkc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zdqjudy.top/Article/details/gt2uzkqqulo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hnqzz.top/Article/details/gt2yuaqzjkk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sysykeji.top/Article/details/gt2zexbpgur.html

[L05] 上传文件（multipart）
来源：http://dali.dianchejie.cn/Article/details/gt2oqzckchb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sufxvd.cn/Article/details/gt2ogazmkgh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.fengsongda.top/Article/details/gt2uwkfmujd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258.top/Article/details/gt2zytobvqy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.havefunace.top/Article/details/gt2oaxxjfag.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.0kj1m.cn/Article/details/gt2asgbsvyj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xylfe.cn/Article/details/gt2lwbtgsbf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shuidangran.top/Article/details/gt2cjkcgxub.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2oghskxeo.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jadzlmme.html

Py:   resp.json()
来源：http://dali.cucudq.cn/Article/details/gt2tkhtwzkp.html

PHP:  json_decode($body, true);
来源：http://dali.tianlin.xyz/Article/details/gt2qjbytmah.html

JS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gt2ysutlpeo.html

TS:   await resp.json()
来源：http://dali.sweek.top/Article/details/gt2tquzytwh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jiagoushi.top/Article/details/gt2yoykajge.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.mhx1999.top/Article/details/gt2qltzpzny.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnqzz.top/Article/details/gt2jaonhcgq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yueranfly.top/Article/details/gt2wtlziisx.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigfzy.top/Article/details/gt2xgxvfnqb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.meibo888.top/Article/details/gt2gyjgrvwl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cucudq.cn/Article/details/gt2urtbibxi.html

JS:   resp.ok;  resp.status
来源：http://dali.cheryme.top/Article/details/gt2jjncmaqs.html

TS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gt2jwtcgcwm.html

Java: resp.statusCode()
来源：http://dali.tian-w.cn/Article/details/gt2kzahlxph.html

Go:   resp.StatusCode
来源：http://dali.haohaochexian.top/Article/details/gt2ctmjigib.html

Ruby: resp.code.to_i
来源：http://dali.xylfe.cn/Article/details/gt2ddzyunjk.html

C#:   (int)resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gt2gqzgyiwq.html

[L08] 并发请求多个地址
来源：http://dali.chenlongwang.top/Article/details/gt2wwyclady.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.316326.xyz/Article/details/gt2lkkeosqt.html

PHP:  curl_multi_init() 系列
来源：http://dali.meibo888.top/Article/details/gt2urmuczox.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gt2rytogdwt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gt2jobsarng.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gzhubu.top/Article/details/gt2iaxlhxjh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.c1oappe.top/Article/details/gt2bzwfusyb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.aibaodan.cn/Article/details/gt2fovtvdap.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.redwolf501.top/Article/details/gt2atgmgpws.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2icrgmaib.html

M. 命令行 / 进程 / 环境
来源：http://dali.quarkkingdee.top/Article/details/gt2mkexvmrb.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2wbdnhsot.html

[M01] 读取命令行参数
来源：http://dali.cdnleiting.top/Article/details/gt2mskimfhy.html

Py:   sys.argv[1:]
来源：http://dali.shuidangran.top/Article/details/gt2ekstbtnq.html

PHP:  $argv;  $argc;
来源：http://dali.hywenlv.cn/Article/details/gt2ncqztxku.html

JS:   process.argv.slice(2)
来源：http://dali.quarkkingdee.top/Article/details/gt2snkqzxna.html

TS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gt2cjpdiqjp.html

Java: args 数组（main 方法参数）
来源：http://dali.sweek.top/Article/details/gt2cauihrnn.html

Go:   os.Args[1:]
来源：http://dali.iojbl.cn/Article/details/gt2crlukmic.html

Ruby: ARGV
来源：http://dali.cqqwz.cn/Article/details/gt2zbtngvqm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ydzc1.top/Article/details/gt2ltgggcpe.html

[M02] 读取环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2mkrrboik.html

Py:   os.environ.get("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gt2txenceiw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gt2defnqfmj.html

JS:   process.env.HOME
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jfvesaco.html

TS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gt2drqkmbee.html

Java: System.getenv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gt2nfcgwawo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gt2wichnlyi.html

Ruby: ENV["HOME"]
来源：http://dali.sweek.top/Article/details/gt2ogcgzpau.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.316326.xyz/Article/details/gt2qcsezkbm.html

[M03] 执行外部命令
来源：http://dali.jiagoushi.top/Article/details/gt2cvmrtubq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xylfe.cn/Article/details/gt2ikgamjrx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.feifeiyinyue.top/Article/details/gt2iyjkomgj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gt2bxtgmzor.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.0kj1m.cn/Article/details/gt2houabaky.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.c1oappe.top/Article/details/gt2cvusilxb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sysykeji.top/Article/details/gt2afblyhyz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hongshengwenyu.top/Article/details/gt2zzwywukv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gogol.net.cn/Article/details/gt2qpeerilk.html

[M04] 获取当前工作目录
来源：http://dali.gogol.net.cn/Article/details/gt2wpfjffyl.html

Py:   os.getcwd()
来源：http://dali.snrcjt.cn/Article/details/gt2sihajavi.html

PHP:  getcwd();
来源：http://dali.wangshuangyany.cn/Article/details/gt2nuovsmuc.html

JS:   process.cwd()
来源：http://dali.ehwqpu.com/Article/details/gt2ksmvwtde.html

TS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gt2uunxohto.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sxryk.cn/Article/details/gt2vqtwztpm.html

Go:   os.Getwd()
来源：http://dali.aibaodan.cn/Article/details/gt2vpjdtjpp.html

Ruby: Dir.pwd
来源：http://dali.meibo888.top/Article/details/gt2alglvjwx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.guowangkeji.top/Article/details/gt2epghpsbp.html

[M05] 设置退出码
来源：http://dali.sxryk.cn/Article/details/gt2dvpiqvlz.html

Py:   sys.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2alqsbikt.html

PHP:  exit(1);
来源：http://dali.hywenlv.cn/Article/details/gt2gjvduigx.html

JS:   process.exit(1)
来源：http://dali.xuanzx.com/Article/details/gt2cimhqjbu.html

TS:   process.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gt2xqswswjy.html

Java: System.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2rpsrmiej.html

Go:   os.Exit(1)
来源：http://dali.bjfxy.top/Article/details/gt2qcnzpkqz.html

Ruby: exit 1
来源：http://dali.havefunace.top/Article/details/gt2gixwoukq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhengqikj.top/Article/details/gt2ngzhhdrd.html

[M06] 向标准错误输出
来源：http://dali.fengsongda.top/Article/details/gt2szqvanbd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.bjfxy.top/Article/details/gt2niriqnny.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jyoumei.cn/Article/details/gt2sqeefiqi.html

JS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gt2tvzpxqen.html

TS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gt2fxpsgmcn.html

Java: System.err.println("err")
来源：http://dali.chenzaomai.com/Article/details/gt2bphjgagk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wyazcrsc.html

Ruby: warn "err"
来源：http://dali.shzxlz.cn/Article/details/gt2hwigczyf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zdqjudy.top/Article/details/gt2gpidxrlh.html

[M07] 判断是否为主入口
来源：http://dali.chenlongwang.top/Article/details/gt2dqdtjcdh.html

Py:   if __name__ == "__main__":
来源：http://dali.daxiang520.top/Article/details/gt2pbbvbufo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ehwqpu.com/Article/details/gt2cltyibxu.html

JS:   require.main === module
来源：http://dali.gotoacloud.top/Article/details/gt2almvovaq.html

TS:   require.main === module
来源：http://dali.pengpengdd.cyou/Article/details/gt2tarxwszl.html

Java: public static void main(String[] args)
来源：http://dali.kuanghao11.cn/Article/details/gt2wyuutwdt.html

Go:   func main()
来源：http://dali.nwbrower.top/Article/details/gt2ailcthpa.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.aizwys.cn/Article/details/gt2rsygsnon.html

C#:   static void Main(string[] args)
来源：http://dali.zhoulong.xyz/Article/details/gt2zxhtfemb.html


<!-- 参考信息 -->