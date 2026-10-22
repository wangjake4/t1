代发 wailian999

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhovjwr.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gt2dihfxksk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gt2orybyguy.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kznzvmvs.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2odmbqlai.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2mybshmrl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gt2rguabhzq.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mydbvtpk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gt2mpaxxaet.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfhnixd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2hygfgmvh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhijiandao.cn/Article/details/gt2gezorliy.html

[J03] 字符串解析为日期
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhtfqyq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcahdmw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhijiandao.cn/Article/details/gt2txnaezlb.html

JS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmlrqjo.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2uclpzotx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgvberp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2relwfsvl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrarpzh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyycpndp.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gt2aqoletee.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpuejsbu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhijiandao.cn/Article/details/gt2vosqceao.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxixnbq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbzgxxw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwceozu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2sconicyg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvcjour.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbqotyi.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gt2enacttxj.html

Py:   now + timedelta(days=7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxnqizd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxpolfj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2inzsefdu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvegsmym.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivaxjpzm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2tiuyhron.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gt2livnnbla.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2copbpial.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gt2otfqyrvg.html

Py:   (end - start).total_seconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwpzueb.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkijtuz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdbwucl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gt2wpziozom.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2abrjtjbn.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gt2uahlfuug.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxcpfmk.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhijiandao.cn/Article/details/gt2sszwyfrg.html

[J07] 比较两个日期
来源：http://dali.zhijiandao.cn/Article/details/gt2qforwttc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2dugpqyaf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktexbidc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdrcfpg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2joczezho.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jorxlemi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2omtivelb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2npfmutqf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmzceyh.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gt2awqycxjh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnzsalw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwtkxdk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gt2wywqijqq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfibkvo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gt2oymhysec.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gt2izafismb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnjbahh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhijiandao.cn/Article/details/gt2rumkttup.html

[J09] 时区处理
来源：http://dali.zhijiandao.cn/Article/details/gt2koaxipuz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzvkeld.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gt2ugaujgwt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmtpzux.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2yelkueyh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjlpwazl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngukpfwn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gt2zllbwoxk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjfpzlp.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gt2nmewxhao.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzafvsd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlmjybt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjiqpcr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzggexny.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2npkxvgic.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmknmir.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhxucbj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2abobojou.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsvzyru.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtxgtfg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qpefghux.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwrjrtw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrtvnpd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2awyeduqg.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2btmewdlm.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fulnggau.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2oikofzlf.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzidihwm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpnmirt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkiramrj.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnmxdmh.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtyvpflz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2inmomkqb.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2koaqravk.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjkdwrs.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2telfqkfa.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2nunbzvfj.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pazwftud.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2obzcegni.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbcqaey.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkmvpvh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcaxadzh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdqumao.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkygeklm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2covfpvho.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfhklib.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2abvoxnme.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2kucrhnji.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcosysv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rczschtp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2uriyrvfl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdudgdw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mwomqxwh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2myxusbme.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2endmhymx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jelzhbih.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gohqptnt.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2mthkytwz.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmmkitz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2leenialf.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cplibxzr.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpaxbog.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbbncmt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2oproayfh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwpqmhn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2aaeoiqrs.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2gqugwuqq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmdzbfw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgiwrlag.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbiffyql.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnkctdt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvymbvh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsegjmnx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ropkihcb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2gphwioke.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eleoktqz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqjnodo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2rxripjtz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2cehcgruy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2afjilfwo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2agfinwxm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlnigxf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qukrxtzw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2odgdpteh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfsuvae.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqktcpx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdclsnz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2lexqcsan.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmzfiek.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxsizzc.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2usyftycy.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbpjzmj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ekimhxtr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dllncilq.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbwbjkk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpituka.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2iwouyjvh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqnzhmn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2dlminseg.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqobmln.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcrmmlx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2xxchlujv.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2pivqlmvl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2ladqfdhw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2qldslumj.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqrzmrg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhxzcti.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2evmjyqjf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bjazxsko.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2prweurnn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2sralmlab.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2rmelkjjq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2glgbwhzi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lzerprkj.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2miwumfnq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2twrbujqo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvakcku.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2uugsfwpf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2dftpbstp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrptyzv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2trbsnmbf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmuhnuj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2avsjmqdb.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsgvbrt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2fncgjddd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2myvljwya.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ircxzjgc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbvokli.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxwosru.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2plrggbbk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpuumxy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2iocflvsy.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2oeuhchvy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2ugndziox.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uowcyznd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2kvszivmt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2rgppsjji.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnjbofj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2efamutln.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2lipjzqru.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2orqfmxmf.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhhjcuq.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2kibapvqp.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgqjeep.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2epcdaybv.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqeffniy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvwslxi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihaloece.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvwwivq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ynottawz.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2aaibzgfm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjekgpjp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2iacixbfi.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2soxhsqwx.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2yblmoupr.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkghikbg.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvzlumx.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtkjoya.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyoilek.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2authuajk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2kovkabuy.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2zcotngnn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2uxaotyok.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfmsnez.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdtxdct.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2bthwymwb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2znmkhaem.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhlqzen.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qxyypnqx.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvawops.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vhntqwrg.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wchkdicz.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2tymwqjao.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2xiouetkv.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxrirff.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mneslsby.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2nlapvoyc.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2pofvzgac.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwgyvst.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2nodnvbrn.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pehhjwyu.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzfspkf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbieoas.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmtiegr.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvgmihr.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2quxgaqkn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2sexflips.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2xobbralj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqusqyrr.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qysweqba.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfemocdw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbwgklq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2masquxgx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qijbbytt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2prsekpnm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmghzmdm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtzpzqi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2pelncjjb.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkxjujg.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xducrtke.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzsbfsm.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2bymkcbol.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxwccsw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2hztcopmk.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2bywmzpvx.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2tseuwaqw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2uonlizrm.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjktfdb.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2etarvaac.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvphvvpm.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbqozpn.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbegpihv.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xshmalti.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkkwctgu.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlizqxo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2jueivvsb.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dhludovk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2agsawnvy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwcvrjy.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgetvghm.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2htbtxhnc.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wlukqgan.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2riazteuk.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwptzue.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2owmyledi.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2xizfdywy.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2stcqmebg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lmophext.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2oudbdxnv.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkjjqjb.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2swdzcaua.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjittczt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2paojiwup.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhctqqoh.html


<!-- 参考信息 -->