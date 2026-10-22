代发 wailian999

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.mhx1999.top/Article/details/gtawinwafy.html

TS:   /error/gim
来源：http://dali.nanxuanxn.top/Article/details/gthsqutmrc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj202588.top/Article/details/gtvqyeqago.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.kuanghao11.cn/Article/details/gttxxpggtz.html

Ruby: s.scan(/error/i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnomfmzbe.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ehwqpu.com/Article/details/gtsplrqeyc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cdnleiting.top/Article/details/gtnzzpeaxd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hysaishi.cn/Article/details/gtwrqxfbsa.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.vqdsnc.cn/Article/details/gtavzpjdbj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gtxedsstcv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoujgvwyx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnqzz.top/Article/details/gtnjiiktel.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cheryme.top/Article/details/gtlypmuqlg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.kuanghao11.cn/Article/details/gtlfmyapuv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cashguo.top/Article/details/gtwuidcegh.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtafspvjra.html

J. 日期与时间
来源：http://dali.chenjidiqi.icu/Article/details/gtsufzcodi.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtefbpmcnb.html

[J01] 获取当前时间
来源：http://dali.iojbl.cn/Article/details/gtkhgwzjgk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nwbrower.top/Article/details/gtxqxpclwj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gtuhlulabg.html

JS:   new Date();  Date.now()
来源：http://dali.gogol.net.cn/Article/details/gtnpgiqpmf.html

TS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gtmgdgpwyn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinqigufen.top/Article/details/gtvwchsmmi.html

Go:   time.Now()
来源：http://dali.xinyue.icu/Article/details/gtnxozurte.html

Ruby: Time.now
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovfjanhd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jiagoushi.top/Article/details/gthlqsrtpq.html

[J02] 格式化输出
来源：http://dali.sweek.top/Article/details/gtulenbxwz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gtzyhwqvhy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gtufyvpqbq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj20258888.top/Article/details/gtkczvumqn.html

TS:   d.toISOString()
来源：http://dali.yongpay.top/Article/details/gtjefbbbjk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuanzhike.top/Article/details/gtnijftjbp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daxiang520.top/Article/details/gtxztnxthd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigfzy.top/Article/details/gtdfymssmw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xinyue.icu/Article/details/gtzvptsgnt.html

[J03] 字符串解析为日期
来源：http://dali.zhijiandao.cn/Article/details/gtntocqmwq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ehwqpu.com/Article/details/gtomkolnyu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.aibaodan.cn/Article/details/gtiggnkqhh.html

JS:   new Date("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtrqhuwmau.html

TS:   new Date("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtkijrxmmq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtyuxseymt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sweek.top/Article/details/gtljxmztts.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtcyyjiwfq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yueranfly.top/Article/details/gtsijhjief.html

[J04] 时间戳与日期互转
来源：http://dali.nanxinkj.top/Article/details/gtzobnqtbs.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhixingplan.top/Article/details/gtkhwnlxnx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yangfankeji.com/Article/details/gtazhvzubx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ehwqpu.com/Article/details/gtrvfkdzoi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ivvv.top/Article/details/gtrtzxfbwc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.guannengcc.top/Article/details/gtyxnpvuce.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tian-w.cn/Article/details/gtzbzexfpc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gotoacloud.top/Article/details/gtsduirwmi.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuanzx.com/Article/details/gtvwgategq.html

[J05] 时间加减（加 7 天）
来源：http://dali.ydzc1.top/Article/details/gtrybywimn.html

Py:   now + timedelta(days=7)
来源：http://dali.nanxinkj.top/Article/details/gtejfwbhsl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinqigfzy.top/Article/details/gtvhxvfdfp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ivvv.top/Article/details/gtrcrbrgga.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gtptovyzro.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jyoumei.cn/Article/details/gtlcvswdgu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtzuecxdzs.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tianlin.xyz/Article/details/gthvdbtzjp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhixingplan.top/Article/details/gttpgblwop.html

[J06] 计算两时间之差
来源：http://dali.gogol.net.cn/Article/details/gtxnwegidl.html

Py:   (end - start).total_seconds()
来源：http://dali.zhoulong.xyz/Article/details/gtkigtxnmx.html

PHP:  $end->diff($start)->days;
来源：http://dali.yvedp.cn/Article/details/gtqxtwggll.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhongyouzk.top/Article/details/gtbdzzcsue.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gogol.net.cn/Article/details/gtuauyeykc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gotoacloud.top/Article/details/gtmvqnipqe.html

Go:   end.Sub(start).Hours()
来源：http://dali.guowangkeji.top/Article/details/gtmxyuadbj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigfzy.top/Article/details/gtsusjoccx.html

C#:   (end - start).TotalSeconds
来源：http://dali.sysykeji.top/Article/details/gtfikzutmd.html

[J07] 比较两个日期
来源：http://dali.chenzaomai.com/Article/details/gtgexetjwk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gtysbublcn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinqigufen.top/Article/details/gtxlfxpapi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jiagoushi.top/Article/details/gtwwielgrj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hammf.cn/Article/details/gtbeklvied.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aizwys.cn/Article/details/gtoxmagoot.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gotoacloud.top/Article/details/gtmjeqzuqn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gtewdncqrk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gtgggjjbju.html

[J08] 提取年月日与星期
来源：http://dali.wangdashe.top/Article/details/gtbchcshql.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.guowangkeji.top/Article/details/gtdfxndrck.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shanyushiyangtech.top/Article/details/gthijotviv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jlsjyb.cn/Article/details/gtbudkuvhr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tanke756.top/Article/details/gtizfbqzpo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhiwuduotai.top/Article/details/gtozqdjhhc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ivvv.top/Article/details/gtwfezbbhe.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgufenzy.top/Article/details/gtjmrykpil.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.316326.xyz/Article/details/gtcffpqexv.html

[J09] 时区处理
来源：http://dali.yongpay.top/Article/details/gtazabcmev.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxinkj.top/Article/details/gtrkhhcghl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xuetiantiany.cn/Article/details/gttaxdfwzk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cdnleiting.top/Article/details/gtmvsmkmwq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.andypj.xyz/Article/details/gtihhptlwk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.vqdsnc.cn/Article/details/gtbugbtlaj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.svipenyu.cn/Article/details/gturgqdzvp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj20258.top/Article/details/gtyneudnmw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.redwolf501.top/Article/details/gtigvhzejl.html

[J10] 取今天 / 本月第一天
来源：http://dali.xinyue.icu/Article/details/gtslabcjag.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenzaomai.com/Article/details/gtihjgvhqf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjftycysy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtryalfbww.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shuidangran.top/Article/details/gtxgmzzpqz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tianlin.xyz/Article/details/gtzralomsf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.wangdashe.top/Article/details/gtfynftpax.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ybcxt.top/Article/details/gtmwtfnysg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jiagoushi.top/Article/details/gtpnjtncje.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gttagbawmu.html

K. JSON 与序列化
来源：http://dali.chenzaomai.com/Article/details/gtxgnhgvgl.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gttfxedmoe.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gturvobxrd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sweek.top/Article/details/gtekbxvgqu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.snrcjt.cn/Article/details/gtvxezsrhd.html

JS:   JSON.stringify(obj)
来源：http://dali.fzhhl.top/Article/details/gtazgloxuo.html

TS:   JSON.stringify(obj)
来源：http://dali.guannengcc.top/Article/details/gtdjghjfdn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.9152youxi.cn/Article/details/gtmfhqjuxb.html

Go:   json.Marshal(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtmbxaikpp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nwbrower.top/Article/details/gtbxnwrygz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cqqwz.cn/Article/details/gtulzobwnc.html

[K02] JSON 字符串转对象
来源：http://dali.feifeiyinyue.top/Article/details/gtrpnpcaoi.html

Py:   json.loads(s)
来源：http://dali.9152youxi.cn/Article/details/gtzcolnvku.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.snrcjt.cn/Article/details/gtnyubhksa.html

JS:   JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gtqpwgqrsv.html

TS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gtennmfvay.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gtltmaxqvd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ppjwa.cn/Article/details/gtbrqvpnyv.html

Ruby: JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gtordgqaut.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jyoumei.cn/Article/details/gtlwrbnlij.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daria6918.cn/Article/details/gtedxfpqup.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gtkhifvylh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hammf.cn/Article/details/gtwdgtytel.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtsufeuwqt.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zycfv.cn/Article/details/gtzitviiid.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtopxrfavg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.dashuyun.cn/Article/details/gtycwfabaj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuanzhike.top/Article/details/gtxsqlgcoy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenzaomai.com/Article/details/gtjeyjmycq.html

[K04] 读取 JSON 文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtphlggmtz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.aizwys.cn/Article/details/gthklcykkp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhiwuduotai.top/Article/details/gthtzogpae.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.haohaochexian.top/Article/details/gtkplwybmd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aizwys.cn/Article/details/gtojfdrwnr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ivvv.top/Article/details/gthbdigker.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.birdmap.top/Article/details/gttzqranbf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gotoacloud.top/Article/details/gtyiuudjyk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj202588.top/Article/details/gtkttcblcs.html

[K05] 深拷贝对象
来源：http://dali.guannengcc.top/Article/details/gtzquntixn.html

Py:   copy.deepcopy(obj)
来源：http://dali.ybcxt.top/Article/details/gtjexkwciq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhengqikj.top/Article/details/gtmgbohvdf.html

JS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtxueptvom.html

TS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gtdtjjlvdy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yangfankeji.com/Article/details/gtrbbrmyzt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yonumen.top/Article/details/gtawggjmeh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfcgmsjvi.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jqgfzy.top/Article/details/gtcjlaufzq.html

[K06] 解析 URL 查询串
来源：http://dali.xziqi.cn/Article/details/gtyciagzlq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.pengpengdd.cyou/Article/details/gtvudzjiip.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.redwolf501.top/Article/details/gteevqkpgm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gteqsetakt.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jianghu66.top/Article/details/gtqxecdgmt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yvedp.cn/Article/details/gtjmdlzazo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gtkqbftboi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gtlqauxktt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gtuhppiesw.html

[K07] 进制转换
来源：http://dali.sufxvd.cn/Article/details/gtflwuepbr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtvbyzpstd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hammf.cn/Article/details/gtajcyoamv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtakpgjfeu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtkbnxwbna.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtwzqdljya.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.meibo888.top/Article/details/gtqbitkrmg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cdnleiting.top/Article/details/gtujtjpxlw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtuqbkzkul.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.mhx1999.top/Article/details/gtuxbpbecd.html

Py:   pickle.dumps(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzopkvodj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gaohongyu789.top/Article/details/gttqhtudie.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gtfvyhdkml.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ehwqpu.com/Article/details/gtxfdlgjfz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.dianchejie.cn/Article/details/gtfsgjhmjq.html

Go:   encoding/gob
来源：http://dali.yongpay.top/Article/details/gtnghusfrb.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtoondkhrr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gtyhcykott.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtqhiskukg.html

L. 网络请求
来源：http://dali.yuxming.cn/Article/details/gtnhermpgg.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtbmlmgqlj.html

[L01] 发送 GET 请求
来源：http://dali.jinqigfzy.top/Article/details/gtmzbhweoh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.wangdashe.top/Article/details/gtvpiduxud.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cheryme.top/Article/details/gtjwgyseep.html

JS:   await fetch(url)
来源：http://dali.ivvv.top/Article/details/gtbtelsacs.html

TS:   await fetch(url)
来源：http://dali.vqdsnc.cn/Article/details/gtwmwscgeh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hywenlv.cn/Article/details/gtdyvzcayr.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj20258888.top/Article/details/gtghiiykqe.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xziqi.cn/Article/details/gtifrbqrxp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcczfrxwa.html

[L02] 发送 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gtcphgexkf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gtkoqctlqs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cheryme.top/Article/details/gtzdhxrksf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gtxqfpjmxs.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhxusvtg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewrsrami.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jyoumei.cn/Article/details/gtfhshwlqw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.316326.xyz/Article/details/gtefabywlb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.redwolf501.top/Article/details/gtqzkstcii.html

[L03] 设置自定义请求头
来源：http://dali.jlsjyb.cn/Article/details/gtshxpkrid.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgufenzy.top/Article/details/gtmigtflro.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinqigfzy.top/Article/details/gtckkjociq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cdnleiting.top/Article/details/gtrdjaraex.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxinkj.top/Article/details/gtlicsmthm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtsenkbigb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdiqrzhrm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jlsjyb.cn/Article/details/gtnsusplzd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yanxiufei.cn/Article/details/gtiabtehud.html

[L04] 设置超时
来源：http://dali.tanke756.top/Article/details/gtmmeefkhs.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotaavfnj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sufxvd.cn/Article/details/gtiofedwik.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gtgagijlkj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hammf.cn/Article/details/gtnffrzswm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jqgufenzy.top/Article/details/gtwnkzkgtp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.316326.xyz/Article/details/gtylynizmp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sweek.top/Article/details/gtvljhplnv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.316326.xyz/Article/details/gtrqblntey.html

[L05] 上传文件（multipart）
来源：http://dali.ydzc1.top/Article/details/gtkjcrfcju.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yongpay.top/Article/details/gtjerggfax.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhiwuduotai.top/Article/details/gtwawkmdkp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sysykeji.top/Article/details/gtmeomiuhk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xylfe.cn/Article/details/gtrxfjrxjz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cashguo.top/Article/details/gtueotyeik.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.0kj1m.cn/Article/details/gtkdzrdlfi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hammf.cn/Article/details/gtsmpbhmas.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cheryme.top/Article/details/gtdsiibtja.html

[L06] 解析响应为 JSON
来源：http://dali.ybcxt.top/Article/details/gtyooiihql.html

Py:   resp.json()
来源：http://dali.0kj1m.cn/Article/details/gtexhtcgtm.html

PHP:  json_decode($body, true);
来源：http://dali.gaohongyu789.top/Article/details/gtwknxfato.html

JS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gtvxbgjkyq.html

TS:   await resp.json()
来源：http://dali.yangfankeji.com/Article/details/gtaectrfft.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ydzc1.top/Article/details/gtplinkgan.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrzysjqjf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuxming.cn/Article/details/gtmigpphft.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttaevqixy.html

[L07] 处理 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gtyyhiygqx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shuidangran.top/Article/details/gtwdgjdddb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenlongwang.top/Article/details/gtgdwybvnl.html

JS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gtjiupyker.html

TS:   resp.ok;  resp.status
来源：http://dali.birdmap.top/Article/details/gtxdesdymm.html

Java: resp.statusCode()
来源：http://dali.mhx1999.top/Article/details/gtmnkneftb.html

Go:   resp.StatusCode
来源：http://dali.xziqi.cn/Article/details/gtnelchrye.html

Ruby: resp.code.to_i
来源：http://dali.fengsongda.top/Article/details/gtnfsgjamj.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gtzclddmkn.html

[L08] 并发请求多个地址
来源：http://dali.hnqzz.top/Article/details/gtlgjxsefi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.mhx1999.top/Article/details/gtrawbndpk.html

PHP:  curl_multi_init() 系列
来源：http://dali.feifeiyinyue.top/Article/details/gtklgwywym.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtshwkkmxl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gtcjnjftht.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuxming.cn/Article/details/gtlgzqubmp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigfzy.top/Article/details/gtlktpjfan.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhiwuduotai.top/Article/details/gtapqozknz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuanzx.com/Article/details/gtdzkgsvql.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtpsgmwizv.html

M. 命令行 / 进程 / 环境
来源：http://dali.meibo888.top/Article/details/gtjmxdieur.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtntxpykxl.html

[M01] 读取命令行参数
来源：http://dali.andypj.xyz/Article/details/gtausiykpi.html

Py:   sys.argv[1:]
来源：http://dali.cashguo.top/Article/details/gtcymdceun.html

PHP:  $argv;  $argc;
来源：http://dali.yueranfly.top/Article/details/gtnmmjnlni.html

JS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtaktcblfy.html

TS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gtrhhkysdo.html

Java: args 数组（main 方法参数）
来源：http://dali.xuanzx.com/Article/details/gtebiahcxu.html

Go:   os.Args[1:]
来源：http://dali.daxiang520.top/Article/details/gtddvsdgkq.html

Ruby: ARGV
来源：http://dali.dashuyun.cn/Article/details/gtezlocdvj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gtvnoytjvm.html

[M02] 读取环境变量
来源：http://dali.chenjidiqi.icu/Article/details/gturkjrpmk.html

Py:   os.environ.get("HOME")
来源：http://dali.mhx1999.top/Article/details/gtusfmqhux.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shangyingyoupin.top/Article/details/gtzgalhvhq.html

JS:   process.env.HOME
来源：http://dali.hammf.cn/Article/details/gtfvulyvcd.html

TS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gtcdrhkdkc.html

Java: System.getenv("HOME")
来源：http://dali.havefunace.top/Article/details/gtdlusqklg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ydzc1.top/Article/details/gtsmjsqkpj.html

Ruby: ENV["HOME"]
来源：http://dali.shangyingyoupin.top/Article/details/gtpfqoatak.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hywenlv.cn/Article/details/gttohpzgls.html

[M03] 执行外部命令
来源：http://dali.jyoumei.cn/Article/details/gtdkittkmf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yvedp.cn/Article/details/gtaxhvieul.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yangfankeji.com/Article/details/gtirgetecg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.quarkkingdee.top/Article/details/gtphqikfeq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gtktswtmft.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sysykeji.top/Article/details/gtyncohctj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ydzc1.top/Article/details/gtlumrdkax.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.andypj.xyz/Article/details/gtpzzsevdj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.fzhhl.top/Article/details/gtzjxiuakq.html

[M04] 获取当前工作目录
来源：http://dali.jqgfzy.top/Article/details/gtmwishfxy.html

Py:   os.getcwd()
来源：http://dali.jinqigfzy.top/Article/details/gtpulegszg.html

PHP:  getcwd();
来源：http://dali.ehwqpu.com/Article/details/gtwmzvixqo.html

JS:   process.cwd()
来源：http://dali.bjfxy.top/Article/details/gtgccqfmds.html

TS:   process.cwd()
来源：http://dali.quarkkingdee.top/Article/details/gtumezupmi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.316326.xyz/Article/details/gtnilolezy.html

Go:   os.Getwd()
来源：http://dali.fengsongda.top/Article/details/gthmsbedbr.html

Ruby: Dir.pwd
来源：http://dali.hnqzz.top/Article/details/gtlrmtsyqk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tian-w.cn/Article/details/gttokhyxof.html

[M05] 设置退出码
来源：http://dali.tian-w.cn/Article/details/gtntokuvfv.html

Py:   sys.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvngsfsht.html

PHP:  exit(1);
来源：http://dali.nwbrower.top/Article/details/gttsenfkxb.html


<!-- 参考信息 -->