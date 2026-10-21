代发 wailian999

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gtyclmxvmo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gtpwjblguh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shzxlz.cn/Article/details/gtludyyidr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.havefunace.top/Article/details/gtfpajkolw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gtufxyntrv.html

[I07] 忽略大小写与多行模式
来源：http://dali.nanxuanxn.top/Article/details/gtfxxhtydq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.9152youxi.cn/Article/details/gttaangpla.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nanxinkj.top/Article/details/gtlkhplcya.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pengpengdd.cyou/Article/details/gtomrnxavi.html

TS:   /error/gim
来源：http://dali.cqqwz.cn/Article/details/gtwwroqgpm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.mhx1999.top/Article/details/gtezerjhzw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinqigufen.top/Article/details/gtucfkooaf.html

Ruby: s.scan(/error/i)
来源：http://dali.0kj1m.cn/Article/details/gtnnbpwnps.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.daxiang520.top/Article/details/gtypvkgict.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ppjwa.cn/Article/details/gtqbpnvqbf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nanxuanxn.top/Article/details/gtpyjoqtbk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gtnnmbtgph.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gtacstpxtb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258888.top/Article/details/gtzdtudaaj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xylfe.cn/Article/details/gtrglnrrmu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.9152youxi.cn/Article/details/gteiqrcxzi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.daria6918.cn/Article/details/gtflfjxeit.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.redwolf501.top/Article/details/gtahzvzowy.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtrilwrrjw.html

J. 日期与时间
来源：http://dali.chenzaomai.com/Article/details/gtntjjnuuc.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtkuowyled.html

[J01] 获取当前时间
来源：http://dali.guannengcc.top/Article/details/gtxamnznhw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hywenlv.cn/Article/details/gtrlgrfjux.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenzaomai.com/Article/details/gteplqkwwx.html

JS:   new Date();  Date.now()
来源：http://dali.jiagoushi.top/Article/details/gtdjkygfsi.html

TS:   new Date();  Date.now()
来源：http://dali.jiagoushi.top/Article/details/gtkryndpuo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ehwqpu.com/Article/details/gtqshlvwjq.html

Go:   time.Now()
来源：http://dali.daxiang520.top/Article/details/gtcnostbfn.html

Ruby: Time.now
来源：http://dali.gogol.net.cn/Article/details/gttbraixeo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gotoacloud.top/Article/details/gtgtksnvpw.html

[J02] 格式化输出
来源：http://dali.sysykeji.top/Article/details/gtmavekqer.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gtizthdmfi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ybcxt.top/Article/details/gtplxlvujd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yanxiufei.cn/Article/details/gtfifxtujr.html

TS:   d.toISOString()
来源：http://dali.sysykeji.top/Article/details/gtvvxabmaq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxinkj.top/Article/details/gthttyvqxq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yanxiufei.cn/Article/details/gtnmdfxtoq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xziqi.cn/Article/details/gtoxregcyt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sysykeji.top/Article/details/gtuuwlapwx.html

[J03] 字符串解析为日期
来源：http://dali.guannengcc.top/Article/details/gtdlnxufjm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yongpay.top/Article/details/gtituyskia.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hongshengwenyu.top/Article/details/gtvvzwduxc.html

JS:   new Date("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtyrrshvlt.html

TS:   new Date("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtlvhgopfp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtlkolllqj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gthusvjqoh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrpxesov.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhongyouzk.top/Article/details/gtmduxihfc.html

[J04] 时间戳与日期互转
来源：http://dali.nanxinkj.top/Article/details/gtiwgbfnxw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtmxghyyok.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhongyouzk.top/Article/details/gthnznpctu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yueranfly.top/Article/details/gtqwuochdc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.wangdashe.top/Article/details/gtzbgciumo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhbnobak.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nwbrower.top/Article/details/gtouexoaky.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gtwclzruuq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hfpthk.cn/Article/details/gtkxgimsne.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhixingplan.top/Article/details/gtfvxrqmnw.html

Py:   now + timedelta(days=7)
来源：http://dali.jinqigufen.top/Article/details/gteaoatlik.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cheryme.top/Article/details/gtjsxnzvyt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xziqi.cn/Article/details/gtkgdlnzsb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gtldsfwjnu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyziyngmu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tanke756.top/Article/details/gtmldoetgd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenzaomai.com/Article/details/gtfdvzishr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yueranfly.top/Article/details/gtsnapzkly.html

[J06] 计算两时间之差
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxeduwva.html

Py:   (end - start).total_seconds()
来源：http://dali.cheryme.top/Article/details/gtipfshdkv.html

PHP:  $end->diff($start)->days;
来源：http://dali.haohaochexian.top/Article/details/gtmxngindu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hongshengwenyu.top/Article/details/gtguqaphjv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ivvv.top/Article/details/gtlrhckfed.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuetiantiany.cn/Article/details/gtbajhbrzl.html

Go:   end.Sub(start).Hours()
来源：http://dali.havefunace.top/Article/details/gtsdjforxh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.guannengcc.top/Article/details/gtckpznapy.html

C#:   (end - start).TotalSeconds
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwfhyuubn.html

[J07] 比较两个日期
来源：http://dali.mhx1999.top/Article/details/gtjpinfnko.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gtjryrwbgz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.9152youxi.cn/Article/details/gtwrymxtfe.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhiwuduotai.top/Article/details/gtoowhjbyw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xinyue.icu/Article/details/gtizvdsvek.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hysaishi.cn/Article/details/gtbenczeep.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nwbrower.top/Article/details/gtsbxqycfw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gteoebayms.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtoduoajav.html

[J08] 提取年月日与星期
来源：http://dali.zycfv.cn/Article/details/gtuxlxkzlb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.9152youxi.cn/Article/details/gtzzskyamp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aizwys.cn/Article/details/gtjwdwioug.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daxiang520.top/Article/details/gtuuejtunv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tian-w.cn/Article/details/gtkpqmacwg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xinyue.icu/Article/details/gtaoponlvk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenlongwang.top/Article/details/gtdgchelip.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zycfv.cn/Article/details/gtopgyxtnz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.havefunace.top/Article/details/gtlhuarujc.html

[J09] 时区处理
来源：http://dali.ppjwa.cn/Article/details/gtknypcjvg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yongpay.top/Article/details/gtsizyqpbb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hfpthk.cn/Article/details/gtcbcbryow.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdyoyycdt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvbupkln.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenjidiqi.icu/Article/details/gtisiugwxo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jqgfzy.top/Article/details/gtfbovslkl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenlongwang.top/Article/details/gtmyptbhzv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cqqwz.cn/Article/details/gtmidfpinq.html

[J10] 取今天 / 本月第一天
来源：http://dali.fzhhl.top/Article/details/gthzfelbsz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.daxiang520.top/Article/details/gtncpaflby.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.quarkkingdee.top/Article/details/gtomgvjhya.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj20258888.top/Article/details/gttbfvnowt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnqzz.top/Article/details/gtvolpnxrp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cdnleiting.top/Article/details/gtrospxeby.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.iojbl.cn/Article/details/gtebbcilgh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hywenlv.cn/Article/details/gtjymsphjj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhoulong.xyz/Article/details/gttkshyaog.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtgahjdbms.html

K. JSON 与序列化
来源：http://dali.sufxvd.cn/Article/details/gtvdfxvcnf.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtukwmzzgs.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtocasdmni.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gtyitakpro.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258888.top/Article/details/gtijuojwcs.html

JS:   JSON.stringify(obj)
来源：http://dali.cdnleiting.top/Article/details/gtxwijlbui.html

TS:   JSON.stringify(obj)
来源：http://dali.cheryme.top/Article/details/gtdhuqonqr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhengqikj.top/Article/details/gtjwdlgnzn.html

Go:   json.Marshal(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtberoxasu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shangyingyoupin.top/Article/details/gteavhzvwd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj20258888.top/Article/details/gtuhknrtfy.html

[K02] JSON 字符串转对象
来源：http://dali.yongpay.top/Article/details/gtrljxybzp.html

Py:   json.loads(s)
来源：http://dali.yangfankeji.com/Article/details/gtzcfqaucg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.quarkkingdee.top/Article/details/gtqnwgyaqw.html

JS:   JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtlwzshqfx.html

TS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gtytuehiad.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ybcxt.top/Article/details/gtkyuioffk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gtqchadght.html

Ruby: JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtticnyxyp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cqqwz.cn/Article/details/gtayftblfq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sweek.top/Article/details/gtahwprzih.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.wangdashe.top/Article/details/gtiszbmsww.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gtxoawfknd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cheryme.top/Article/details/gtnshhrsrm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtuhhbyfdj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhengqikj.top/Article/details/gtejeeljxz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtecsirymv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenlongwang.top/Article/details/gtyljehzto.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nwbrower.top/Article/details/gtrhqkneue.html

[K04] 读取 JSON 文件
来源：http://dali.guowangkeji.top/Article/details/gtvokrogaw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yuxming.cn/Article/details/gtqfkgxsqn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.iojbl.cn/Article/details/gtttmswajg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenjidiqi.icu/Article/details/gthnoshast.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shuidangran.top/Article/details/gtlhtkhvaf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yonumen.top/Article/details/gtwvykuakw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gtfxzmoaau.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gzhubu.top/Article/details/gturooulbe.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gttkdnavzn.html

[K05] 深拷贝对象
来源：http://dali.wangshuangyany.cn/Article/details/gtrgarunof.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhoulong.xyz/Article/details/gthaemaqcz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jianghu66.top/Article/details/gtgyefyihk.html

JS:   structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gthypbkkiw.html

TS:   structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gtcsebsqlc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sweek.top/Article/details/gtrwqfmtbu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhiwuduotai.top/Article/details/gthufxnuvs.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.pengpengdd.cyou/Article/details/gtrjvcbbqa.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cqqwz.cn/Article/details/gtlgzwirhx.html

[K06] 解析 URL 查询串
来源：http://dali.cqqwz.cn/Article/details/gtqgwglqdu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yanxiufei.cn/Article/details/gtzykabvpd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuijsgiwc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sweek.top/Article/details/gtezdgoosx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtbgoglrbi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.havefunace.top/Article/details/gtxmjtuazn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gtvnpjdqpc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gtqpetayxa.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gtnvpuwizu.html

[K07] 进制转换
来源：http://dali.quarkkingdee.top/Article/details/gtehzjczmn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtgmqmfeiq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yuxming.cn/Article/details/gttgsoeknp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gtrgrivitu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtywvmapvo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gttmjujvkh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ivvv.top/Article/details/gtarxvyaqg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.nanxuanxn.top/Article/details/gtejgorapv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtrhrrviqc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ehwqpu.com/Article/details/gtomebfahb.html

Py:   pickle.dumps(obj)
来源：http://dali.tian-w.cn/Article/details/gtsnuernar.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hywenlv.cn/Article/details/gtnlyvpswt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shzxlz.cn/Article/details/gtixliagwk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gzhubu.top/Article/details/gtvpruwbyj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gotoacloud.top/Article/details/gtshrudmar.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gtbwzqlkoe.html

Ruby: Marshal.dump(obj)
来源：http://dali.c1oappe.top/Article/details/gtulbzehhk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gttbchxxqh.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtpomzfvup.html

L. 网络请求
来源：http://dali.sysykeji.top/Article/details/gtvvagpduo.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtzqshurxq.html

[L01] 发送 GET 请求
来源：http://dali.xuetiantiany.cn/Article/details/gtsnozgcjq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.daxiang520.top/Article/details/gteyvoybme.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gogol.net.cn/Article/details/gtmsxkzzsc.html

JS:   await fetch(url)
来源：http://dali.hnqzz.top/Article/details/gtjkyaicrn.html

TS:   await fetch(url)
来源：http://dali.iojbl.cn/Article/details/gtovancqkw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwuntfemf.html

Go:   resp, err := http.Get(url)
来源：http://dali.hammf.cn/Article/details/gtagaskcso.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.mhx1999.top/Article/details/gtrtolbnlx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ppjwa.cn/Article/details/gttwvmaokh.html

[L02] 发送 POST JSON
来源：http://dali.hnqzz.top/Article/details/gtbcrqcegg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.fengsongda.top/Article/details/gtpeevfirz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shuidangran.top/Article/details/gtlpjxsrzv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zdqjudy.top/Article/details/gtchtgqgst.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.iojbl.cn/Article/details/gtqathiert.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jianghu66.top/Article/details/gtfjtngzlx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jianghu66.top/Article/details/gtavxkvoxy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tianlin.xyz/Article/details/gtztpbohpe.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.pycfn.com/Article/details/gtzekvmchp.html

[L03] 设置自定义请求头
来源：http://dali.zhiwuduotai.top/Article/details/gtsuughrga.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hnxiangtu.top/Article/details/gtpbxojfdo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sufxvd.cn/Article/details/gtunoyjkvw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.smart0.xyz/Article/details/gtduchqgba.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sysykeji.top/Article/details/gtjlkykyuk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yongpay.top/Article/details/gtgwlxovme.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yueranfly.top/Article/details/gtflgteucw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shangyingyoupin.top/Article/details/gtlkgvqofh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gtrechtyqp.html

[L04] 设置超时
来源：http://dali.cdnleiting.top/Article/details/gtrfktzxsr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xziqi.cn/Article/details/gtaerdexda.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.pycfn.com/Article/details/gtyhnnokxy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gtocpfnapf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdltnhsqz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hnxiangtu.top/Article/details/gtawsgehqx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.quarkkingdee.top/Article/details/gtxogognjf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tian-w.cn/Article/details/gtbozatgtz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.andypj.xyz/Article/details/gtrwoopvgo.html

[L05] 上传文件（multipart）
来源：http://dali.jinghuilouyu.cn/Article/details/gtctqbktmw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zdqjudy.top/Article/details/gtydbbelxp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xinyue.icu/Article/details/gttwcblsjz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gtahzrjnjf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbidtxjd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sweek.top/Article/details/gtdhqdzaes.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.smart0.xyz/Article/details/gtqurnmrlm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cdnleiting.top/Article/details/gtcgeisqhg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.pycfn.com/Article/details/gtlrhcifpe.html

[L06] 解析响应为 JSON
来源：http://dali.zhiwuduotai.top/Article/details/gtkwezmxaj.html

Py:   resp.json()
来源：http://dali.hysaishi.cn/Article/details/gtyaufeuzg.html

PHP:  json_decode($body, true);
来源：http://dali.shzxlz.cn/Article/details/gtiepesgyz.html

JS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gtgrejacft.html

TS:   await resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuqdvvdea.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cqqwz.cn/Article/details/gtyyazueuu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sysykeji.top/Article/details/gtwuoyjtgx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxuanxn.top/Article/details/gtkvnbapfc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hnxiangtu.top/Article/details/gtmlsuxdwm.html

[L07] 处理 HTTP 状态码
来源：http://dali.pycfn.com/Article/details/gtspxkzcsd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yanxiufei.cn/Article/details/gtvbxkiowt.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenzaomai.com/Article/details/gtvhbqtsla.html

JS:   resp.ok;  resp.status
来源：http://dali.yonumen.top/Article/details/gtttrhtnct.html

TS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gtjisxqsxb.html

Java: resp.statusCode()
来源：http://dali.mhx1999.top/Article/details/gtlpzrapnm.html

Go:   resp.StatusCode
来源：http://dali.9152youxi.cn/Article/details/gttdzfqleh.html

Ruby: resp.code.to_i
来源：http://dali.sysykeji.top/Article/details/gttchagenh.html

C#:   (int)resp.StatusCode
来源：http://dali.yonumen.top/Article/details/gtjfdlcbmg.html

[L08] 并发请求多个地址
来源：http://dali.quarkkingdee.top/Article/details/gtxvspxcup.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jqgfzy.top/Article/details/gtoxacshfo.html

PHP:  curl_multi_init() 系列
来源：http://dali.yvedp.cn/Article/details/gtlycyunpl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gtserkklpd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gteiqqylpf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.havefunace.top/Article/details/gtnmmojhbf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.guowangkeji.top/Article/details/gtzgvmrliy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fzhhl.top/Article/details/gtmstiylkd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shuidangran.top/Article/details/gtzuiekugf.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtkndilkam.html

M. 命令行 / 进程 / 环境
来源：http://dali.mhx1999.top/Article/details/gtuscdxywt.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtgagqmgeh.html

[M01] 读取命令行参数
来源：http://dali.xuanzx.com/Article/details/gtcmcrysbu.html

Py:   sys.argv[1:]
来源：http://dali.fengsongda.top/Article/details/gtolwuzatw.html

PHP:  $argv;  $argc;
来源：http://dali.chenlongwang.top/Article/details/gtorhyhrht.html

JS:   process.argv.slice(2)
来源：http://dali.ydzc1.top/Article/details/gtodhleljm.html

TS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gtfldorusl.html

Java: args 数组（main 方法参数）
来源：http://dali.316326.xyz/Article/details/gtrhlmgfld.html

Go:   os.Args[1:]
来源：http://dali.wangdashe.top/Article/details/gtnxnqgxep.html

Ruby: ARGV
来源：http://dali.yuxming.cn/Article/details/gtpfgnmnsa.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jyoumei.cn/Article/details/gtksttshus.html

[M02] 读取环境变量
来源：http://dali.birdmap.top/Article/details/gthbfokoix.html

Py:   os.environ.get("HOME")
来源：http://dali.gotoacloud.top/Article/details/gtklvrbnqu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sysykeji.top/Article/details/gtrcmvsmbs.html

JS:   process.env.HOME
来源：http://dali.mhx1999.top/Article/details/gthkxmohup.html

TS:   process.env.HOME
来源：http://dali.jlsjyb.cn/Article/details/gtuzxeecui.html

Java: System.getenv("HOME")
来源：http://dali.jianghu66.top/Article/details/gtdcbbnxuz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtyworlyjc.html

Ruby: ENV["HOME"]
来源：http://dali.dianchejie.cn/Article/details/gtjivgplfj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtmnuyepkp.html

[M03] 执行外部命令
来源：http://dali.cdnleiting.top/Article/details/gtmwzzshqg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gotoacloud.top/Article/details/gtqzmdkfdt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.dianchejie.cn/Article/details/gtyctukmcd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gtjjxfdwhr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.bjfxy.top/Article/details/gtavbuutva.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zdqjudy.top/Article/details/gtnmaeznyb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.havefunace.top/Article/details/gtssoebuvj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuetiantiany.cn/Article/details/gtozbfcxaw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.kuanghao11.cn/Article/details/gtwmvpxjfk.html

[M04] 获取当前工作目录
来源：http://dali.wangdashe.top/Article/details/gtjpszfbxy.html

Py:   os.getcwd()
来源：http://dali.jinqigfzy.top/Article/details/gtvdxaotrg.html

PHP:  getcwd();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpiihzjjc.html

JS:   process.cwd()
来源：http://dali.daxiang520.top/Article/details/gtnqoghixl.html


<!-- 参考信息 -->