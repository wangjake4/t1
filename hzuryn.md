代发 wailian999

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2xugekqut.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zworsfip.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzisfah.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qssjjysz.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqlcrbr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yaefmber.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tplbzvrh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqkthzt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2zylgbpiy.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2gquwrytp.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvnvtml.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2dsweftne.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtzwsrk.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gt2zbuuhxwu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwjpewb.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxghhoj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtozwoig.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrslgle.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqkemuq.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gt2azbjnyqw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvmjsyk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gt2wivwjyno.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpcvtbi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhijiandao.cn/Article/details/gt2uynnmqxe.html

[J03] 字符串解析为日期
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhkgwqn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gt2azzpseuf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzpaoqq.html

JS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbuaozfa.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtyfyvu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhdvrks.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2sryflefc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlifsbw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhijiandao.cn/Article/details/gt2nikllsjn.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gt2smaaleqr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2fydsbehz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhijiandao.cn/Article/details/gt2vexknviq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtvagfs.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxbhvnv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2kducfrek.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxymepwj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2spmvvhwk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxvnfqe.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzxrxso.html

Py:   now + timedelta(days=7)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrxedjd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqcvktg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdooaeik.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2dejvjsjh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2gchkxiux.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2rikhmjit.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyohhvl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2hthqnjww.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkeamzk.html

Py:   (end - start).total_seconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2utavxiee.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhijiandao.cn/Article/details/gt2tihztceb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gt2aonfjysz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvvaqpi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2aacwbknc.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvasywx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhijiandao.cn/Article/details/gt2pborlqab.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnlcojj.html

[J07] 比较两个日期
来源：http://dali.zhijiandao.cn/Article/details/gt2cutrxxpm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmswvzr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpuitxc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmftret.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkmdrgc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnruqqst.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qarolelt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfhipri.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2ceumcvfl.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gt2plgfcuas.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxksvfn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqbpcxd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjqiqvm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfpwbxy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwwtyuh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gt2eoesvkgg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvtuncd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzrxfqp.html

[J09] 时区处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxuyfpp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewshrnui.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gt2agancvfe.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwucznwx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2telabpai.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhijiandao.cn/Article/details/gt2nppruwxw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsirivmg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjwsxwa.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcypekb.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gt2rybypqiu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwlsfxh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gt2nraqibgv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyokwekx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlchpgdy.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsegnhjt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhvxbnf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gt2yzngeteg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgdopqx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwzhzlw.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gt2admlkynp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2elwrnups.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfxdpqo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyidqivh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpemzeux.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlonqyop.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmxzrxs.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2xefbtfpp.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhrymul.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2pxszxaon.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmwbjxk.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkmpcub.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2omqmoezq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2odhmqstb.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2txjotqds.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfhiyxf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxijmcf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfeivng.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmnpbyi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmpuksi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlzhawr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcooaojj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2blbdpwsh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxceazj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmyemuxb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lefyeqlx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmxeghh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2abcccddf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2nmplwlmr.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zmukrlnj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqifnlt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzyuwbxq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dobobbph.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqpxcpg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2arwqmeya.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2vliibsvg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqypphk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzypqwl.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxzjtuq.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrceisz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2zydupytj.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvppseao.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnvcgxm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjkrgyd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxrevzi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2dxssajhf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2cvenjzqo.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmnqeit.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2bmiybeuj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmoahqw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcndlun.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2nticfwpm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrlspaf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocekctzr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2yduslued.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlaranpb.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jkodxmec.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvrvitk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2jeklaaag.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcxrlpx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxverrf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2thescjyy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2drnsmhxs.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2atjooljd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2slqpdahw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2rnawhafe.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2sztlphxx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuaegrdv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2yskemivc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2gddhvgpl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjkgmnc.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2vezryjrv.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2voofdfwx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxforxh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkqtdrw.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2nnejonfw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtnnwvx.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrbvecz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdtnyvd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2nsppicrr.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqqzzxc.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffyzwtto.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2tstgypxz.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfhtovw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyzyboy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2hinbqtgs.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqmxain.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2klsegkke.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2irqgzuux.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2balxfxzp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbjqcrl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvprwab.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2divoaaue.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkwbhkd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kkusfbyr.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzcgdcc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2tonemgcz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuebqusu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjkkvny.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnemmyx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfjgjzi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2aizbldum.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvchvhe.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmlczcy.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkqyuun.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifczwvbh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmegouvj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrzaxyi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2iegvamjk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2ismokfmj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2qajuflcx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2thdhxhdm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2durfvcqv.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2efpsytqf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbxausr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pchfehay.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbuusii.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsktqsl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2rsulzsqt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfmcprp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2nguhycxq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjxohql.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2farmspdw.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsbojri.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2viwnprag.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzaitkw.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2kubqetbt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcblkkea.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2uszpnego.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2akfmomva.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2twlanygv.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2psrhohnd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2avqbwnuy.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvwhmha.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqnhsel.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2nvoduscx.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcwvlsf.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgvgzcq.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsadipu.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtvzxqp.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2daxaifuk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2qvktnjpm.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwmjhtm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hllklblc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2izxmaxlg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2wavnosur.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2mxynqtqa.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2pidnddtm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvxnagv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mzadczqf.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tktzgbpf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgxdlnd.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zspbcwaa.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2borhojdl.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwgfqwe.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfvchoq.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vswxbfwz.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2etstudmv.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2gntgyyos.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2prdmljnx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtxydlu.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcxhcie.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxzwtlb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhsmjpj.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2gektdnhe.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2fynxrbci.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgbzbwl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2betltobf.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2oywpfshj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2dblqhivi.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvphyjy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tiawvwss.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwqeyqz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qrirsoju.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvdcxvy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjptszxq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsvwfbo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2zypykfcs.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnnjabs.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mmsakfxn.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdfsjcy.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzgzhpw.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmtutql.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xaflqmkw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrrbdvi.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2oaybsvoq.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhnncdy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2amvuodtk.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzkuimw.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvufvzi.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdkzerh.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pojwmxht.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzewhrj.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xobgidmi.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2djpmzppu.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmalanz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2cbosifmq.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhytuyo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhdhqcw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2xdeaupcu.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2djzuaxix.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzbgjws.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjxuaun.html


<!-- 参考信息 -->