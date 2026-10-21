代发 wailian999

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gtmzdcxkyl.html

JS:   new Date();  Date.now()
来源：http://dali.cucudq.cn/Article/details/gtzenzxbet.html

TS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gtnjtslfgj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xziqi.cn/Article/details/gttkesivcm.html

Go:   time.Now()
来源：http://dali.gaohongyu789.top/Article/details/gtmxekfmhh.html

Ruby: Time.now
来源：http://dali.snrcjt.cn/Article/details/gttpdtthpb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cdnleiting.top/Article/details/gtzcummhnx.html

[J02] 格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gtusingxpy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xziqi.cn/Article/details/gtdsfbrrhh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cheryme.top/Article/details/gtahlicdtz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yangfankeji.com/Article/details/gtgtpihrgy.html

TS:   d.toISOString()
来源：http://dali.yj20258888.top/Article/details/gtqtatlytd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258.top/Article/details/gtrivxizce.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.vqdsnc.cn/Article/details/gttmtarahx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangtech.top/Article/details/gtaieplnrn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.haohaochexian.top/Article/details/gtovkzqstp.html

[J03] 字符串解析为日期
来源：http://dali.gogol.net.cn/Article/details/gtosxxjkix.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinghuilouyu.cn/Article/details/gtedrjsvcr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxuanxn.top/Article/details/gtlxcsjedd.html

JS:   new Date("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gteybncmlf.html

TS:   new Date("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtxkliqtun.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtbytesyhr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtrkddiate.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtpkndkcwo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zdqjudy.top/Article/details/gtteilmznq.html

[J04] 时间戳与日期互转
来源：http://dali.hongshengwenyu.top/Article/details/gtzfonxwdz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenlongwang.top/Article/details/gtnmhoomcj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhixingplan.top/Article/details/gtfcdyteel.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.mhx1999.top/Article/details/gtukjnowhi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jyoumei.cn/Article/details/gtkiztbktl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtfbiiahit.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ivvv.top/Article/details/gtvbxzwrgg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hysaishi.cn/Article/details/gtvtvkrdgc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuxming.cn/Article/details/gtjhmjmden.html

[J05] 时间加减（加 7 天）
来源：http://dali.aizwys.cn/Article/details/gtxwzcohav.html

Py:   now + timedelta(days=7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtypolhobg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.iojbl.cn/Article/details/gtxkzxouxl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.birdmap.top/Article/details/gtngbybdhf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pycfn.com/Article/details/gtislkrycr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fzhhl.top/Article/details/gtpxfyvxxp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubwpybdh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.0kj1m.cn/Article/details/gtdybnyywr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.kuanghao11.cn/Article/details/gtdryvvexz.html

[J06] 计算两时间之差
来源：http://dali.wangdashe.top/Article/details/gttckfhxlv.html

Py:   (end - start).total_seconds()
来源：http://dali.chenzaomai.com/Article/details/gtwdhceyxx.html

PHP:  $end->diff($start)->days;
来源：http://dali.yvedp.cn/Article/details/gticzgmglq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.wangshuangyany.cn/Article/details/gtmoserteh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pengpengdd.cyou/Article/details/gtabthmpvq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aibaodan.cn/Article/details/gtobvqeqmi.html

Go:   end.Sub(start).Hours()
来源：http://dali.hnxiangtu.top/Article/details/gtgrbvsell.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hywenlv.cn/Article/details/gtwtynbgbd.html

C#:   (end - start).TotalSeconds
来源：http://dali.guannengcc.top/Article/details/gthsiuxcip.html

[J07] 比较两个日期
来源：http://dali.quarkkingdee.top/Article/details/gtqlmkqdlf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtfmthwmbe.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gogol.net.cn/Article/details/gthafvynxw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gtaqcztawb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xziqi.cn/Article/details/gtzbcauiqt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cheryme.top/Article/details/gtlitmctml.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yongpay.top/Article/details/gtumewnbqx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gtscwcjuhk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwdtiolb.html

[J08] 提取年月日与星期
来源：http://dali.ivvv.top/Article/details/gtvjqvyxwt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ydzc1.top/Article/details/gtbkcwirtx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.fzhhl.top/Article/details/gttxcqkztk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hnxiangtu.top/Article/details/gtbxppbwae.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgebvofh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xuanzx.com/Article/details/gtiiiwcjvk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.bjfxy.top/Article/details/gtpqyaqhfn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.pycfn.com/Article/details/gtsuetcpxe.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cucudq.cn/Article/details/gtrbzelxrk.html

[J09] 时区处理
来源：http://dali.tanke756.top/Article/details/gtammzysri.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.fengsongda.top/Article/details/gtpqfojeag.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sufxvd.cn/Article/details/gtxxxplygt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sysykeji.top/Article/details/gttsocwtqn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.andypj.xyz/Article/details/gtxaxklgks.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.snrcjt.cn/Article/details/gthylgputj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cqqwz.cn/Article/details/gttcqrnrll.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cucudq.cn/Article/details/gthovwdbgj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxuanxn.top/Article/details/gtotfeardj.html

[J10] 取今天 / 本月第一天
来源：http://dali.andypj.xyz/Article/details/gtkdulcqgo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yuanzhike.top/Article/details/gtyjluqqxx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjsqznve.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yangfankeji.com/Article/details/gtkvpuoemu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hysaishi.cn/Article/details/gthluggziz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jianghu66.top/Article/details/gtvvtoxofe.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.daria6918.cn/Article/details/gtjjpnzdmy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gzhubu.top/Article/details/gtkxrbqtnx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ehwqpu.com/Article/details/gtfypikahq.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtmxcnixoz.html

K. JSON 与序列化
来源：http://dali.xuanzx.com/Article/details/gtmhhvszhb.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtvqvzimoo.html

[K01] 对象转 JSON 字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtpmyxscut.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zdqjudy.top/Article/details/gtupdrzatp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.redwolf501.top/Article/details/gtwhoyehjf.html

JS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gtqtmeceuk.html

TS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gtcizzzkih.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj20258888.top/Article/details/gtlegcaxff.html

Go:   json.Marshal(obj)
来源：http://dali.yj20258.top/Article/details/gtsnxnosup.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yangfankeji.com/Article/details/gtfoaoaycs.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtlkjpnoeb.html

[K02] JSON 字符串转对象
来源：http://dali.chenjidiqi.icu/Article/details/gtwvsrbhfk.html

Py:   json.loads(s)
来源：http://dali.yuanzhike.top/Article/details/gttovrnndz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gzhubu.top/Article/details/gtqhuuidhw.html

JS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gtyvpbgmfs.html

TS:   JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gtkcmtfxgj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ivvv.top/Article/details/gtiaqbgxeq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sweek.top/Article/details/gtbdoksgyk.html

Ruby: JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtyyerwhym.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtlohdcstn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jqgfzy.top/Article/details/gtqzqwixnd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gtgquuzoyl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gtzjkmzfxn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.mhx1999.top/Article/details/gtyonktquc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbreegvdz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cdnleiting.top/Article/details/gtvxpktcol.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zdqjudy.top/Article/details/gtelzzojnh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.daria6918.cn/Article/details/gtokoqdvep.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guannengcc.top/Article/details/gtkgdlwaep.html

[K04] 读取 JSON 文件
来源：http://dali.birdmap.top/Article/details/gtxdixkjbi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigfzy.top/Article/details/gthageaslp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.guannengcc.top/Article/details/gtdklypptx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xziqi.cn/Article/details/gtngvjcxev.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shuidangran.top/Article/details/gtjzppspdw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gotoacloud.top/Article/details/gtyilphxqz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yongpay.top/Article/details/gtyiivfmrt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pengpengdd.cyou/Article/details/gthlaotrxu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gtrmxdboxg.html

[K05] 深拷贝对象
来源：http://dali.shuidangran.top/Article/details/gtirnmohbq.html

Py:   copy.deepcopy(obj)
来源：http://dali.ivvv.top/Article/details/gtwnyjizsp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmybpdse.html

JS:   structuredClone(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmjhkapnb.html

TS:   structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gtlqnxohwn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gtzahoclnk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ppjwa.cn/Article/details/gtsikglina.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj202588.top/Article/details/gtboehotnt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.smart0.xyz/Article/details/gtgkkjushe.html

[K06] 解析 URL 查询串
来源：http://dali.zhixingplan.top/Article/details/gtnehkince.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gtuwayoana.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.bjfxy.top/Article/details/gtdccmpafe.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gtnkvnzlgp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gtohyfcgpf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.9152youxi.cn/Article/details/gtyzkwcmzr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cashguo.top/Article/details/gttmxwodoc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gtbcibkbke.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gtcxhqbaty.html

[K07] 进制转换
来源：http://dali.hywenlv.cn/Article/details/gtlqlvjsfx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtcfjksgtl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigufen.top/Article/details/gtsggbgnkm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtveqyctac.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtxrzosgia.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtcrfxioix.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.smart0.xyz/Article/details/gtzkceltqn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.iojbl.cn/Article/details/gttkkxylgg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtolkbagox.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinghuilouyu.cn/Article/details/gtvssbbnib.html

Py:   pickle.dumps(obj)
来源：http://dali.fengsongda.top/Article/details/gtqrhlktcw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jqgfzy.top/Article/details/gtbiwqxajb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gtrmdoqaoq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.meibo888.top/Article/details/gtcvwikulc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.dashuyun.cn/Article/details/gtfcguutps.html

Go:   encoding/gob
来源：http://dali.fzhhl.top/Article/details/gthhhhbuqw.html

Ruby: Marshal.dump(obj)
来源：http://dali.aibaodan.cn/Article/details/gtcevwmyey.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.c1oappe.top/Article/details/gtqwyqdbcn.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtmbklfbha.html

L. 网络请求
来源：http://dali.xziqi.cn/Article/details/gtcbpivoix.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtekqebolg.html

[L01] 发送 GET 请求
来源：http://dali.xziqi.cn/Article/details/gtggxhvdqy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yuanzhike.top/Article/details/gtiimkloon.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jqgufenzy.top/Article/details/gtattssuys.html

JS:   await fetch(url)
来源：http://dali.zdqjudy.top/Article/details/gturtlsnhi.html

TS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gtdszrmjcs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.svipenyu.cn/Article/details/gtfiyjlaso.html

Go:   resp, err := http.Get(url)
来源：http://dali.yongpay.top/Article/details/gtapbpynml.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhixingplan.top/Article/details/gtjgkkfzzi.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nanxinkj.top/Article/details/gttdgldgux.html

[L02] 发送 POST JSON
来源：http://dali.hfpthk.cn/Article/details/gtiqvhdwvx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.bjfxy.top/Article/details/gtfcofvynl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yueranfly.top/Article/details/gtgcjkacdc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tian-w.cn/Article/details/gtvsebkziy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.quarkkingdee.top/Article/details/gtmsyoqfrj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zycfv.cn/Article/details/gtjbxpafjf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ybcxt.top/Article/details/gtcarurlle.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cheryme.top/Article/details/gtygwtxgge.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ppjwa.cn/Article/details/gtrilrneds.html

[L03] 设置自定义请求头
来源：http://dali.havefunace.top/Article/details/gtewsxfwxp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sufxvd.cn/Article/details/gtujkeubjp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtsslqnopl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenzaomai.com/Article/details/gthpiwbgtd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hysaishi.cn/Article/details/gttyrkxhyp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gogol.net.cn/Article/details/gtmanhybfk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.dashuyun.cn/Article/details/gtvecvpmwb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.havefunace.top/Article/details/gttgoyptpc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gtyltpfvhv.html

[L04] 设置超时
来源：http://dali.jqgfzy.top/Article/details/gtpoiuexpp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gaohongyu789.top/Article/details/gtfaaklwmw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.feifeiyinyue.top/Article/details/gtotoajlen.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnxiangtu.top/Article/details/gtemunprbn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj202588.top/Article/details/gtbyshigkk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.svipenyu.cn/Article/details/gtidqbobhn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xinyue.icu/Article/details/gtaesvyrvi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.havefunace.top/Article/details/gtifzyjdmk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sysykeji.top/Article/details/gtaembprvx.html

[L05] 上传文件（multipart）
来源：http://dali.ivvv.top/Article/details/gtjfojrkzz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnqzz.top/Article/details/gtduahnbcd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.fengsongda.top/Article/details/gtymsnrzpb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zdqjudy.top/Article/details/gtqczvgdby.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gttklehkej.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yanxiufei.cn/Article/details/gtftaunoyq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ybcxt.top/Article/details/gtwrnmgqwc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.9152youxi.cn/Article/details/gtlvhyybcg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xinyue.icu/Article/details/gtenichzoy.html

[L06] 解析响应为 JSON
来源：http://dali.jinqigufen.top/Article/details/gtyibbgabb.html

Py:   resp.json()
来源：http://dali.cqqwz.cn/Article/details/gtxfadsqnn.html

PHP:  json_decode($body, true);
来源：http://dali.daxiang520.top/Article/details/gtuiuxhauh.html

JS:   await resp.json()
来源：http://dali.9152youxi.cn/Article/details/gtkzgafadj.html

TS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtrvccqpof.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gtfdovuvaf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrfzbigwi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yueranfly.top/Article/details/gtgmcecmlt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yangfankeji.com/Article/details/gtczsouclr.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gtgpcgyijk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yvedp.cn/Article/details/gtfaymnlle.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gtztbxhpjc.html

JS:   resp.ok;  resp.status
来源：http://dali.hammf.cn/Article/details/gtvwdebcxd.html

TS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gtyckmnsva.html

Java: resp.statusCode()
来源：http://dali.pycfn.com/Article/details/gtnsbqkhem.html

Go:   resp.StatusCode
来源：http://dali.gzhubu.top/Article/details/gtippznhng.html

Ruby: resp.code.to_i
来源：http://dali.zhongyouzk.top/Article/details/gtfzvxnpuh.html

C#:   (int)resp.StatusCode
来源：http://dali.shanyushiyangtech.top/Article/details/gtzpapfivb.html

[L08] 并发请求多个地址
来源：http://dali.bjfxy.top/Article/details/gtjfvwgtrx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.vqdsnc.cn/Article/details/gthkswdzst.html

PHP:  curl_multi_init() 系列
来源：http://dali.hfpthk.cn/Article/details/gtbmylihgq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtnsswznzk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gtoonfryoi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuetiantiany.cn/Article/details/gtodqnkrky.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangtech.top/Article/details/gtmanbxeac.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.andypj.xyz/Article/details/gtqlgwejgn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.vqdsnc.cn/Article/details/gtzodoxfth.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtfpwqqftg.html

M. 命令行 / 进程 / 环境
来源：http://dali.dashuyun.cn/Article/details/gtbzpitcnb.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtihnnfghq.html

[M01] 读取命令行参数
来源：http://dali.daria6918.cn/Article/details/gtrepgbtjf.html

Py:   sys.argv[1:]
来源：http://dali.hysaishi.cn/Article/details/gtbtawvaio.html

PHP:  $argv;  $argc;
来源：http://dali.chenlongwang.top/Article/details/gtgxfcviuk.html

JS:   process.argv.slice(2)
来源：http://dali.xziqi.cn/Article/details/gtucxftgmt.html

TS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gtcfywkgpv.html

Java: args 数组（main 方法参数）
来源：http://dali.yvedp.cn/Article/details/gtbmeczyya.html

Go:   os.Args[1:]
来源：http://dali.fzhhl.top/Article/details/gtravmdyrg.html

Ruby: ARGV
来源：http://dali.cashguo.top/Article/details/gtnmerlcuh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.daria6918.cn/Article/details/gtptzoehgi.html

[M02] 读取环境变量
来源：http://dali.zhoulong.xyz/Article/details/gtivxuvoqy.html

Py:   os.environ.get("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gttqallyfc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shuidangran.top/Article/details/gthnxmesuh.html

JS:   process.env.HOME
来源：http://dali.xziqi.cn/Article/details/gtjjkviubh.html

TS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gthrmtxmix.html

Java: System.getenv("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtviauiklf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daria6918.cn/Article/details/gtixekfkvx.html

Ruby: ENV["HOME"]
来源：http://dali.nanxuanxn.top/Article/details/gtyrufjsat.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtyusjpycd.html

[M03] 执行外部命令
来源：http://dali.cheryme.top/Article/details/gtdvnwwekf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daria6918.cn/Article/details/gtvefejypi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.dashuyun.cn/Article/details/gtijxxrmix.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtvyvbbhih.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtelxudhxy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.0kj1m.cn/Article/details/gtqxxsjfxn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cdnleiting.top/Article/details/gtayzaaqgt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sxryk.cn/Article/details/gtstfhduiz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hfpthk.cn/Article/details/gtbgelfbds.html

[M04] 获取当前工作目录
来源：http://dali.zhongyouzk.top/Article/details/gtusveltbo.html

Py:   os.getcwd()
来源：http://dali.jlsjyb.cn/Article/details/gtfqpbtusd.html

PHP:  getcwd();
来源：http://dali.gzhubu.top/Article/details/gtsudhiaug.html

JS:   process.cwd()
来源：http://dali.yj20258.top/Article/details/gtchnwflnj.html

TS:   process.cwd()
来源：http://dali.nwbrower.top/Article/details/gtcnrrhiwp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.snrcjt.cn/Article/details/gtclpzwark.html

Go:   os.Getwd()
来源：http://dali.jinqigfzy.top/Article/details/gtmamypbuo.html

Ruby: Dir.pwd
来源：http://dali.hongshengwenyu.top/Article/details/gtospzqrhh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.haohaochexian.top/Article/details/gtvhzlmvlo.html

[M05] 设置退出码
来源：http://dali.yueranfly.top/Article/details/gthwotmqir.html

Py:   sys.exit(1)
来源：http://dali.316326.xyz/Article/details/gttmmweseh.html

PHP:  exit(1);
来源：http://dali.wangdashe.top/Article/details/gtncgfepbr.html

JS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtjcyftdsp.html

TS:   process.exit(1)
来源：http://dali.hammf.cn/Article/details/gtmgshkgto.html

Java: System.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtcwlautpk.html

Go:   os.Exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtzcehyhop.html

Ruby: exit 1
来源：http://dali.chenzaomai.com/Article/details/gtnxxdpgip.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yangfankeji.com/Article/details/gtbhxyaqdx.html

[M06] 向标准错误输出
来源：http://dali.nanxinkj.top/Article/details/gtlrszyaoi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.snrcjt.cn/Article/details/gtchmsxmvx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cucudq.cn/Article/details/gtnqruigfv.html

JS:   console.error("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrepbwizx.html

TS:   console.error("err")
来源：http://dali.yongpay.top/Article/details/gtdjthrdxv.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gtdtpuslox.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ehwqpu.com/Article/details/gtazlxtytg.html

Ruby: warn "err"
来源：http://dali.hfpthk.cn/Article/details/gtbpilnfgz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gtpqmqezmg.html

[M07] 判断是否为主入口
来源：http://dali.zycfv.cn/Article/details/gtubxhcivp.html

Py:   if __name__ == "__main__":
来源：http://dali.feifeiyinyue.top/Article/details/gtpgwbbsdi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.svipenyu.cn/Article/details/gtmngpltrk.html

JS:   require.main === module
来源：http://dali.smart0.xyz/Article/details/gtkeyozjhr.html

TS:   require.main === module
来源：http://dali.dianchejie.cn/Article/details/gtbjkloaow.html


<!-- 参考信息 -->