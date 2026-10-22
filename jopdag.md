代发 wailian999

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.0kj1m.cn/Article/details/gtpsgkevgq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gtkrwbqtju.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ybcxt.top/Article/details/gtjmhockva.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zdqjudy.top/Article/details/gtafcittbr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gtmikutqfg.html

[I07] 忽略大小写与多行模式
来源：http://dali.guowangkeji.top/Article/details/gtzarahwyg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nanxuanxn.top/Article/details/gtxusrkpzo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tanke756.top/Article/details/gtpjomfkdv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.fengsongda.top/Article/details/gtnpncylfy.html

TS:   /error/gim
来源：http://dali.ywan-chungtsiang.top/Article/details/gtakzxxlhb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.dashuyun.cn/Article/details/gtextioarc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xuanzx.com/Article/details/gthzhdemvw.html

Ruby: s.scan(/error/i)
来源：http://dali.hywenlv.cn/Article/details/gthtlbxybt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdyowuvr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.guowangkeji.top/Article/details/gtdynnbjdi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.c1oappe.top/Article/details/gtnhqfazxu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gtaqqaumpb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xinyue.icu/Article/details/gtnejsmyph.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.smart0.xyz/Article/details/gtsrzzoixj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xinyue.icu/Article/details/gtiikwzmuk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shangyingyoupin.top/Article/details/gtfbmlmhdw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ydzc1.top/Article/details/gtqxbtmzbh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gthoijnhva.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtyipzhvkd.html

J. 日期与时间
来源：http://dali.hongshengwenyu.top/Article/details/gtgniqldag.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtrwqtimrh.html

[J01] 获取当前时间
来源：http://dali.jqgufenzy.top/Article/details/gtpcxoubde.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jyoumei.cn/Article/details/gtpaxbkbdq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sweek.top/Article/details/gtgnyyykgq.html

JS:   new Date();  Date.now()
来源：http://dali.cashguo.top/Article/details/gtpqlgomis.html

TS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gtldiselor.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.pengpengdd.cyou/Article/details/gtiggygwge.html

Go:   time.Now()
来源：http://dali.xylfe.cn/Article/details/gtejgbkkyx.html

Ruby: Time.now
来源：http://dali.ehwqpu.com/Article/details/gtgmwzrbbz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangdashe.top/Article/details/gtoolrtgic.html

[J02] 格式化输出
来源：http://dali.hnqzz.top/Article/details/gtlmwfiuxn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tanke756.top/Article/details/gtazyrledm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhixingplan.top/Article/details/gtldoykfoh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zycfv.cn/Article/details/gtqvolognr.html

TS:   d.toISOString()
来源：http://dali.hfpthk.cn/Article/details/gtrlhawcht.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggfrfxrt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gogol.net.cn/Article/details/gtdcweyuds.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gtexsosycr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daxiang520.top/Article/details/gttzkmzbve.html

[J03] 字符串解析为日期
来源：http://dali.aibaodan.cn/Article/details/gtuwlrbebs.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cqqwz.cn/Article/details/gttxmaufjn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jyoumei.cn/Article/details/gtaqopwywv.html

JS:   new Date("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtdzwcdiuk.html

TS:   new Date("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtliogaskj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtvmuhgcbd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtciktucyl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtfyfqxdgf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.fzhhl.top/Article/details/gtdizuvlhs.html

[J04] 时间戳与日期互转
来源：http://dali.nwbrower.top/Article/details/gtaeeuhafj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gtqgwnbdvd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.pengpengdd.cyou/Article/details/gtowfrhhhq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zycfv.cn/Article/details/gtjwquyemw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hammf.cn/Article/details/gtfvdvvtxc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xylfe.cn/Article/details/gtllsgfqiu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jianghu66.top/Article/details/gtrqqkipga.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hammf.cn/Article/details/gtzpffurwe.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.0kj1m.cn/Article/details/gtazdhydep.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgfzy.top/Article/details/gtrcfvmzir.html

Py:   now + timedelta(days=7)
来源：http://dali.hnqzz.top/Article/details/gtasqtxked.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shuidangran.top/Article/details/gtslugjipd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrtjqcdhv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.havefunace.top/Article/details/gtwakpqysf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.9152youxi.cn/Article/details/gtdplreqhh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ybcxt.top/Article/details/gtbkttscbs.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tianlin.xyz/Article/details/gtsecbztdu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.bjfxy.top/Article/details/gtpbnkjnjt.html

[J06] 计算两时间之差
来源：http://dali.jianghu66.top/Article/details/gtutkrcwtr.html

Py:   (end - start).total_seconds()
来源：http://dali.wangshuangyany.cn/Article/details/gtvtzhtsbg.html

PHP:  $end->diff($start)->days;
来源：http://dali.cashguo.top/Article/details/gtjoyvxfuu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.haohaochexian.top/Article/details/gtuqogfjte.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ybcxt.top/Article/details/gtphndmtrw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.daxiang520.top/Article/details/gtakamuwaw.html

Go:   end.Sub(start).Hours()
来源：http://dali.svipenyu.cn/Article/details/gtsmxxfuvt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hammf.cn/Article/details/gtcjtmtvhz.html

C#:   (end - start).TotalSeconds
来源：http://dali.meibo888.top/Article/details/gtvisobfcy.html

[J07] 比较两个日期
来源：http://dali.zhijiandao.cn/Article/details/gtiwvqqzwp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gtvkzffcjo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinqigufen.top/Article/details/gtrkftnera.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cdnleiting.top/Article/details/gtyfpfesoq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhixingplan.top/Article/details/gtisxzsfda.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxinkj.top/Article/details/gtnmphdkag.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yonumen.top/Article/details/gtqhiaaiir.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gtejksxoau.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gtysjoascu.html

[J08] 提取年月日与星期
来源：http://dali.ybcxt.top/Article/details/gtsvaweala.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tianlin.xyz/Article/details/gtcexzwlbt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dashuyun.cn/Article/details/gtftermdia.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqvfgvxt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jiagoushi.top/Article/details/gtnlaplity.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.svipenyu.cn/Article/details/gtowyovnvd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cqqwz.cn/Article/details/gtbszqcfqt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.andypj.xyz/Article/details/gtubrmbuli.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuanzx.com/Article/details/gtfxkblvrw.html

[J09] 时区处理
来源：http://dali.chenjidiqi.icu/Article/details/gtyeyvqywz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.c1oappe.top/Article/details/gtzxfkomgo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jiagoushi.top/Article/details/gtycfzwcsl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ybcxt.top/Article/details/gtltsxwtqr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gtqhlypcpq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.haohaochexian.top/Article/details/gtsatbtgeq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jyoumei.cn/Article/details/gtbrrsscgq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yangfankeji.com/Article/details/gtradmjnup.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hfpthk.cn/Article/details/gtagnfwbfu.html

[J10] 取今天 / 本月第一天
来源：http://dali.svipenyu.cn/Article/details/gtjddxtdwk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenlongwang.top/Article/details/gttnjzzjfy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuanzhike.top/Article/details/gtiqkbswtv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xinyue.icu/Article/details/gtmjycjifw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tianlin.xyz/Article/details/gthajztwgo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtjbpraukq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.iojbl.cn/Article/details/gtilrltyrt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.daxiang520.top/Article/details/gtzloitixl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sufxvd.cn/Article/details/gtniopexsd.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtoqvcsunc.html

K. JSON 与序列化
来源：http://dali.nanxuanxn.top/Article/details/gtdrzxkqlc.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtrlvjkrgh.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqodezuur.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gthlbsqrnh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.haohaochexian.top/Article/details/gtmfgzftln.html

JS:   JSON.stringify(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtcyiskmlj.html

TS:   JSON.stringify(obj)
来源：http://dali.cqqwz.cn/Article/details/gtilnehvfy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.bjfxy.top/Article/details/gtobfiowjg.html

Go:   json.Marshal(obj)
来源：http://dali.ppjwa.cn/Article/details/gtmdxhdhxu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.iojbl.cn/Article/details/gtckcvmzez.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cqqwz.cn/Article/details/gtyetzvqjp.html

[K02] JSON 字符串转对象
来源：http://dali.gzhubu.top/Article/details/gtpssorfaz.html

Py:   json.loads(s)
来源：http://dali.cucudq.cn/Article/details/gtxgjwlebn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cashguo.top/Article/details/gthbrzdfdt.html

JS:   JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gtzjjeqbhl.html

TS:   JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gtgwalppwp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenlongwang.top/Article/details/gthnkquarn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.haohaochexian.top/Article/details/gtztgtkypj.html

Ruby: JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gtquqasrtm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.aibaodan.cn/Article/details/gtqtjyilqs.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hammf.cn/Article/details/gtyzcsariy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlhffrpod.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zycfv.cn/Article/details/gtlvlcpkzi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gtiwxqdshz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gzhubu.top/Article/details/gtafnogkcu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.c1oappe.top/Article/details/gticuveobt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jlsjyb.cn/Article/details/gtzxyasxcq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.svipenyu.cn/Article/details/gtfblsnmib.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sysykeji.top/Article/details/gtfrndpdyu.html

[K04] 读取 JSON 文件
来源：http://dali.yanxiufei.cn/Article/details/gtryqwxoxq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.kuanghao11.cn/Article/details/gtjmpbwtqa.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gogol.net.cn/Article/details/gtftoturhh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gtsieaomsf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jiagoushi.top/Article/details/gtyumzkqzm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.iojbl.cn/Article/details/gtbwedtssy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.aibaodan.cn/Article/details/gtibrguuny.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.iojbl.cn/Article/details/gtglnestlr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xylfe.cn/Article/details/gtymkvdewi.html

[K05] 深拷贝对象
来源：http://dali.cucudq.cn/Article/details/gtfgzwlujs.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtugijlnzs.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jlsjyb.cn/Article/details/gtckyxhpww.html

JS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gtkhqomegs.html

TS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gtuyskedvc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shanyushiyangtech.top/Article/details/gtnpmblrij.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.bjfxy.top/Article/details/gtysdqajdb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.guowangkeji.top/Article/details/gtgdwfpeui.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daxiang520.top/Article/details/gtuxuwycjp.html

[K06] 解析 URL 查询串
来源：http://dali.sufxvd.cn/Article/details/gtgtnhxdoo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jianghu66.top/Article/details/gtpudmqpnn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.kuanghao11.cn/Article/details/gtkvmicaxu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gtyggedbrd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aizwys.cn/Article/details/gtzezuuhzd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tanke756.top/Article/details/gtkwfzrkbm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gthrapqxku.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gttmpztuyg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gtriwujpvy.html

[K07] 进制转换
来源：http://dali.kuanghao11.cn/Article/details/gthrlltwxb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswsovekw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.bjfxy.top/Article/details/gtqynkyeon.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtuehyutrp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyigngoxz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtpyniacmf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgfzy.top/Article/details/gtbstiwntb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszmddnzt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtkkficzne.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.svipenyu.cn/Article/details/gtbohmxryq.html

Py:   pickle.dumps(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkscondzj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.9152youxi.cn/Article/details/gtuglmoarn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gtlgveggeb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jiagoushi.top/Article/details/gtbjefqpdg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.meibo888.top/Article/details/gtiaikruja.html

Go:   encoding/gob
来源：http://dali.yangfankeji.com/Article/details/gtfdlvdwyu.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtkpvmtkww.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gtwipqbqbl.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gthbzoxzcp.html

L. 网络请求
来源：http://dali.gotoacloud.top/Article/details/gtvczrrdtr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtxzxhefse.html

[L01] 发送 GET 请求
来源：http://dali.yueranfly.top/Article/details/gtqurrerfv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdchoilr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgxmipsi.html

JS:   await fetch(url)
来源：http://dali.tian-w.cn/Article/details/gtngmzsvlj.html

TS:   await fetch(url)
来源：http://dali.yvedp.cn/Article/details/gtwtisqtrk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sufxvd.cn/Article/details/gtfttmtlcd.html

Go:   resp, err := http.Get(url)
来源：http://dali.snrcjt.cn/Article/details/gtkuiwaapv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenlongwang.top/Article/details/gtpvodgere.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jlsjyb.cn/Article/details/gtjbdglxba.html

[L02] 发送 POST JSON
来源：http://dali.guannengcc.top/Article/details/gtsgtdrioh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.smart0.xyz/Article/details/gtijkgjmzw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.aizwys.cn/Article/details/gtdhpvzcrs.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gthumptjlo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxpootne.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xuanzx.com/Article/details/gtxhyvglbs.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenzaomai.com/Article/details/gtgnmqrbic.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.c1oappe.top/Article/details/gtnjkpbdfy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ivvv.top/Article/details/gtgeqofgwf.html

[L03] 设置自定义请求头
来源：http://dali.kuanghao11.cn/Article/details/gtpfwyrvuh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.redwolf501.top/Article/details/gtzpvdhntp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.snrcjt.cn/Article/details/gtrsugeypr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.kuanghao11.cn/Article/details/gtnooebzxi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnxiangtu.top/Article/details/gtzalnofph.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.mhx1999.top/Article/details/gttwrmdvsy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yongpay.top/Article/details/gtdlhzlapo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.pengpengdd.cyou/Article/details/gtxrjaacfc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tian-w.cn/Article/details/gtnfysnsjn.html

[L04] 设置超时
来源：http://dali.gzhubu.top/Article/details/gtillrrbnj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ppjwa.cn/Article/details/gtkmaxdxhw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.mhx1999.top/Article/details/gtlhxrlahe.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gtgvjrpdlh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gtgqxnybev.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ppjwa.cn/Article/details/gtyiqyancz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.9152youxi.cn/Article/details/gtklanfvke.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shzxlz.cn/Article/details/gtvwnagnji.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwhsukky.html

[L05] 上传文件（multipart）
来源：http://dali.gotoacloud.top/Article/details/gtnffgumtc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yuanzhike.top/Article/details/gtbjeerzhw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shuidangran.top/Article/details/gtwpygfzrn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tanke756.top/Article/details/gtyotxgmpm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.aibaodan.cn/Article/details/gtmfknoswm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yvedp.cn/Article/details/gtvkxjectm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yongpay.top/Article/details/gtrefufkry.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.pycfn.com/Article/details/gtlhfgxvrf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.meibo888.top/Article/details/gtkggljsun.html

[L06] 解析响应为 JSON
来源：http://dali.chenlongwang.top/Article/details/gtyfxswhqa.html

Py:   resp.json()
来源：http://dali.yj20258.top/Article/details/gteteukbnq.html

PHP:  json_decode($body, true);
来源：http://dali.bjfxy.top/Article/details/gtpnrutnim.html

JS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gtdcbpsbfw.html

TS:   await resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcawwilpd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj202588.top/Article/details/gtgaeeslpe.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.redwolf501.top/Article/details/gtzxgxdztd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezerjykq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sysykeji.top/Article/details/gtubnmmpbm.html

[L07] 处理 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gthtzqzewd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ivvv.top/Article/details/gtpikfxzmr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.wangdashe.top/Article/details/gttlhizebx.html

JS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gtzodyrgus.html

TS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxmegzck.html

Java: resp.statusCode()
来源：http://dali.c1oappe.top/Article/details/gtohaavnea.html

Go:   resp.StatusCode
来源：http://dali.ydzc1.top/Article/details/gtnpkccvkz.html

Ruby: resp.code.to_i
来源：http://dali.shangyingyoupin.top/Article/details/gtpcnggjmv.html

C#:   (int)resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gtrjxvlbve.html

[L08] 并发请求多个地址
来源：http://dali.quarkkingdee.top/Article/details/gthcsnmpoz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yueranfly.top/Article/details/gtnuyztqhb.html

PHP:  curl_multi_init() 系列
来源：http://dali.yanxiufei.cn/Article/details/gteqsofgvb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gtbgifnyew.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gtxlzofybi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xinyue.icu/Article/details/gtxufldgwy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.snrcjt.cn/Article/details/gtqfvjngax.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nwbrower.top/Article/details/gtdrlvcvzk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guannengcc.top/Article/details/gtnmcdlcnq.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gthfkfcphw.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gthrbdatdy.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtofygolhy.html

[M01] 读取命令行参数
来源：http://dali.guowangkeji.top/Article/details/gtnfmmjayc.html

Py:   sys.argv[1:]
来源：http://dali.yueranfly.top/Article/details/gtwnxzmzlz.html

PHP:  $argv;  $argc;
来源：http://dali.mhx1999.top/Article/details/gtqkjljxlr.html

JS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gtyxowotka.html

TS:   process.argv.slice(2)
来源：http://dali.cdnleiting.top/Article/details/gtfwuenkmn.html

Java: args 数组（main 方法参数）
来源：http://dali.dashuyun.cn/Article/details/gtpstsbvtl.html

Go:   os.Args[1:]
来源：http://dali.nwbrower.top/Article/details/gtclqtbykt.html

Ruby: ARGV
来源：http://dali.ehwqpu.com/Article/details/gtmhczxjkp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gotoacloud.top/Article/details/gtwhsebnaf.html

[M02] 读取环境变量
来源：http://dali.yj202588.top/Article/details/gtrmrebjim.html

Py:   os.environ.get("HOME")
来源：http://dali.aizwys.cn/Article/details/gthsmxltsc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ivvv.top/Article/details/gtxiwqveij.html

JS:   process.env.HOME
来源：http://dali.hongshengwenyu.top/Article/details/gtuppwxewx.html

TS:   process.env.HOME
来源：http://dali.hywenlv.cn/Article/details/gtfekaotab.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtafmizytr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.andypj.xyz/Article/details/gthpjtfxyc.html

Ruby: ENV["HOME"]
来源：http://dali.tianlin.xyz/Article/details/gtnfmtdbnz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zdqjudy.top/Article/details/gtestjjxvc.html

[M03] 执行外部命令
来源：http://dali.daria6918.cn/Article/details/gtufkortyp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ivvv.top/Article/details/gtcsmhovxk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hnqzz.top/Article/details/gtmrjljldx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigufen.top/Article/details/gtzaoaaqnr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtuqrfsrug.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tanke756.top/Article/details/gtlthikarf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhoulong.xyz/Article/details/gtdwcbhtbi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hysaishi.cn/Article/details/gtdvkbznhg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cashguo.top/Article/details/gthdposhbq.html

[M04] 获取当前工作目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedbgmunt.html

Py:   os.getcwd()
来源：http://dali.yanxiufei.cn/Article/details/gtctihszvc.html

PHP:  getcwd();
来源：http://dali.ivvv.top/Article/details/gtezzsfdrr.html

JS:   process.cwd()
来源：http://dali.xinyue.icu/Article/details/gtiephlggs.html


<!-- 参考信息 -->