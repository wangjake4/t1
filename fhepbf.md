代发 wailian999

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guannengcc.top/Article/details/gtlzgiofjj.html

TS:   /error/gim
来源：http://dali.cqqwz.cn/Article/details/gtbklxsxkk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj20258888.top/Article/details/gtkwmohdtp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cqqwz.cn/Article/details/gtnykpzmej.html

Ruby: s.scan(/error/i)
来源：http://dali.mhx1999.top/Article/details/gtddyibyml.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hysaishi.cn/Article/details/gtbhmizhbf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jiagoushi.top/Article/details/gtajrrreqz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cdnleiting.top/Article/details/gtqjbgcirt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gtwmenkkjj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgfzy.top/Article/details/gthblumerm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sweek.top/Article/details/gtmprebgeu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.redwolf501.top/Article/details/gtyfgeixuu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xylfe.cn/Article/details/gtllczwhkt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shzxlz.cn/Article/details/gtojdyasth.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sweek.top/Article/details/gtbxowwqtv.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtlqazceme.html

J. 日期与时间
来源：http://dali.yueranfly.top/Article/details/gtmxmhuikq.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gteaeijolo.html

[J01] 获取当前时间
来源：http://dali.redwolf501.top/Article/details/gtvimndget.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.snrcjt.cn/Article/details/gtoxcazlfl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tanke756.top/Article/details/gtrwevcibd.html

JS:   new Date();  Date.now()
来源：http://dali.tian-w.cn/Article/details/gtatqmfyum.html

TS:   new Date();  Date.now()
来源：http://dali.kuanghao11.cn/Article/details/gteaqupgfs.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenlongwang.top/Article/details/gtwimpcobv.html

Go:   time.Now()
来源：http://dali.sweek.top/Article/details/gtwqakcbov.html

Ruby: Time.now
来源：http://dali.yueranfly.top/Article/details/gtlxkcmhan.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinghuilouyu.cn/Article/details/gtislpywbv.html

[J02] 格式化输出
来源：http://dali.9152youxi.cn/Article/details/gtemqnewen.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gtpvrtvvdm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nanxuanxn.top/Article/details/gttzikpqnp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daxiang520.top/Article/details/gtobnhjghl.html

TS:   d.toISOString()
来源：http://dali.yj202588.top/Article/details/gtpqrcgbgj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj202588.top/Article/details/gtbkkakwak.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhoulong.xyz/Article/details/gtdhsgrxca.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sufxvd.cn/Article/details/gtwyvpsfso.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cashguo.top/Article/details/gtfuwszotq.html

[J03] 字符串解析为日期
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkslnpmqj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hfpthk.cn/Article/details/gtxznlurhm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sweek.top/Article/details/gtzouciene.html

JS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtesudkamu.html

TS:   new Date("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtjkrepzlv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtmticbohf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtsaggdtvz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtescaivbt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hnqzz.top/Article/details/gtjnmywapq.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gtcddtbnmm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hnqzz.top/Article/details/gtajcwkekv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.aibaodan.cn/Article/details/gtmkktsfvl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbxtimydq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gtzgfqwjuk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yuxming.cn/Article/details/gtvfbccjab.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.dianchejie.cn/Article/details/gtaecwmtrc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nwbrower.top/Article/details/gtqigwreho.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnysrdmta.html

[J05] 时间加减（加 7 天）
来源：http://dali.yueranfly.top/Article/details/gtjxsmqukj.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgfzy.top/Article/details/gtudymzkxj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.andypj.xyz/Article/details/gtycoznmyp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangdashe.top/Article/details/gtyvnsabcz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gttcnzkvma.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.aibaodan.cn/Article/details/gtjcitiqqk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.redwolf501.top/Article/details/gtfdrsyjbc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinqigufen.top/Article/details/gtabtyngam.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jianghu66.top/Article/details/gtwimsbpfo.html

[J06] 计算两时间之差
来源：http://dali.yonumen.top/Article/details/gtbdmopkgy.html

Py:   (end - start).total_seconds()
来源：http://dali.zhengqikj.top/Article/details/gtbvlqiizs.html

PHP:  $end->diff($start)->days;
来源：http://dali.tian-w.cn/Article/details/gtjhhzihbq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258.top/Article/details/gtcxrpuhdt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nanxinkj.top/Article/details/gtyvpianqb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.iojbl.cn/Article/details/gtcxrovzff.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzoxrbgw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.redwolf501.top/Article/details/gtrprvtusk.html

C#:   (end - start).TotalSeconds
来源：http://dali.jqgufenzy.top/Article/details/gtocophzfg.html

[J07] 比较两个日期
来源：http://dali.hongshengwenyu.top/Article/details/gtrypuwogi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtmwwocxdb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.daria6918.cn/Article/details/gtopltdkun.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.meibo888.top/Article/details/gteutnlfcc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuanzx.com/Article/details/gtgdunywis.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pycfn.com/Article/details/gthafncoun.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.wangdashe.top/Article/details/gtclydwqfu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gtzlikhrdl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gtgkxrslez.html

[J08] 提取年月日与星期
来源：http://dali.mhx1999.top/Article/details/gtxosehlov.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.dianchejie.cn/Article/details/gtzobxsgxt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yuxming.cn/Article/details/gtnhafcwqt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.iojbl.cn/Article/details/gtdcqxbtqo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhiwuduotai.top/Article/details/gtsdwsacjq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuxming.cn/Article/details/gtjkkwrvhd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yueranfly.top/Article/details/gtaqjxaolp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.haohaochexian.top/Article/details/gtsrolcicc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj202588.top/Article/details/gthtrvycws.html

[J09] 时区处理
来源：http://dali.jyoumei.cn/Article/details/gtdbrokltw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.pycfn.com/Article/details/gtwcklegpg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yuanzhike.top/Article/details/gtfbeeasxa.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gtsipwkksk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gtfwcrrykv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yangfankeji.com/Article/details/gtmhskwsml.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tanke756.top/Article/details/gticvtsmbt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jiagoushi.top/Article/details/gtuxhyaawy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sufxvd.cn/Article/details/gtssccukkr.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangshuangyany.cn/Article/details/gtkiuxywep.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zdqjudy.top/Article/details/gtlgyvxouo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zycfv.cn/Article/details/gtcdqeezwh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxinkj.top/Article/details/gtobzrmwyp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.meibo888.top/Article/details/gtlphyrzgm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sysykeji.top/Article/details/gtgpkjjotb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gogol.net.cn/Article/details/gtsaxgpsuj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gogol.net.cn/Article/details/gtcffnqggd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gotoacloud.top/Article/details/gtkbnuynrf.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtgzdbtwlw.html

K. JSON 与序列化
来源：http://dali.guannengcc.top/Article/details/gtvtkgdrlc.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtezmsrfbn.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuanzx.com/Article/details/gtjbvmmhkw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gthatyzkeo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gtjxclxrsl.html

JS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gtsdecsftt.html

TS:   JSON.stringify(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtrptxndfe.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shzxlz.cn/Article/details/gtbqpgsosl.html

Go:   json.Marshal(obj)
来源：http://dali.aibaodan.cn/Article/details/gtviigkngm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yueranfly.top/Article/details/gtvnhqskip.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtrmmyeczo.html

[K02] JSON 字符串转对象
来源：http://dali.pycfn.com/Article/details/gtwhplfwie.html

Py:   json.loads(s)
来源：http://dali.fzhhl.top/Article/details/gtlpxjkchv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nanxinkj.top/Article/details/gtgztdmein.html

JS:   JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqarcqbn.html

TS:   JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gtxvheunfp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gtzqjjpcme.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmhwjqjbk.html

Ruby: JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gtvozldtec.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gotoacloud.top/Article/details/gtwsznlkzg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xinyue.icu/Article/details/gtdiogtjzz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xuetiantiany.cn/Article/details/gtrjwkbncu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cashguo.top/Article/details/gtmicwjtiu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gthfwsolyi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.birdmap.top/Article/details/gtfjjuisww.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.0kj1m.cn/Article/details/gtkzeoepvo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.vqdsnc.cn/Article/details/gtzcnmtbfo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gzhubu.top/Article/details/gtdrfkoacr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.daria6918.cn/Article/details/gtkfakbqxv.html

[K04] 读取 JSON 文件
来源：http://dali.havefunace.top/Article/details/gtsmcljtro.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shangyingyoupin.top/Article/details/gteprkftyr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.daxiang520.top/Article/details/gtmpziuvni.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.havefunace.top/Article/details/gtsakbxamb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gthgwieeni.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yongpay.top/Article/details/gtrgfahims.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqlbdkqf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.316326.xyz/Article/details/gtcbvchmac.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zycfv.cn/Article/details/gtrhrvfshh.html

[K05] 深拷贝对象
来源：http://dali.cdnleiting.top/Article/details/gtstjhkeub.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtjezwtcwm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gaohongyu789.top/Article/details/gtxjtnrnai.html

JS:   structuredClone(obj)
来源：http://dali.fengsongda.top/Article/details/gtsibjnlkm.html

TS:   structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gtngjvrntu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj202588.top/Article/details/gtkdfaabhn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sxryk.cn/Article/details/gtfcmzgyqs.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj20258888.top/Article/details/gtttpjbkhc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.mhx1999.top/Article/details/gtafjrgwfj.html

[K06] 解析 URL 查询串
来源：http://dali.cqqwz.cn/Article/details/gtuxtoecia.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yueranfly.top/Article/details/gtufltoxbk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj202588.top/Article/details/gtndmacwhb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gtcpdwmtxo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aibaodan.cn/Article/details/gtbsmijvsd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tanke756.top/Article/details/gtjuwajzbm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gtnpvysrie.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzekyobu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.dashuyun.cn/Article/details/gthhccreey.html

[K07] 进制转换
来源：http://dali.wangshuangyany.cn/Article/details/gtdbycdfod.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtxvjqbejk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hongshengwenyu.top/Article/details/gtklyaoobz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtzqxjpbpm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gttlcbyydt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtpozyuhrr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yongpay.top/Article/details/gtgjvizbds.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmlwvmqdv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtknyhtidn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.0kj1m.cn/Article/details/gtblfldcnb.html

Py:   pickle.dumps(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwuktvake.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtspkalige.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmuwlsujr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ehwqpu.com/Article/details/gtitaybiuc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.iojbl.cn/Article/details/gthloccrth.html

Go:   encoding/gob
来源：http://dali.yuxming.cn/Article/details/gthpaobwtq.html

Ruby: Marshal.dump(obj)
来源：http://dali.hnxiangtu.top/Article/details/gteyjrnliy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ywan-chungtsiang.top/Article/details/gtueqfyiew.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtrhczbakc.html

L. 网络请求
来源：http://dali.jqgufenzy.top/Article/details/gtvjiayrku.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtiisauncx.html

[L01] 发送 GET 请求
来源：http://dali.pengpengdd.cyou/Article/details/gtttigppmt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinyuanbaomall.cn/Article/details/gtauukrbyf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shzxlz.cn/Article/details/gtnjmegfjs.html

JS:   await fetch(url)
来源：http://dali.shuidangran.top/Article/details/gtilzahoix.html

TS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gtnjcwbavy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhongyouzk.top/Article/details/gtwbbxzvlp.html

Go:   resp, err := http.Get(url)
来源：http://dali.zdqjudy.top/Article/details/gtcpwpdkco.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hongshengwenyu.top/Article/details/gtwcthwfyw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jyoumei.cn/Article/details/gtngcqiwzl.html

[L02] 发送 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gttsejmpdc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xziqi.cn/Article/details/gtjcretkau.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yanxiufei.cn/Article/details/gtipmcvrib.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.snrcjt.cn/Article/details/gtbgntnfvo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gtmmwnpdwr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.guowangkeji.top/Article/details/gtdmeaajpl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gtjeoohqhn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhengqikj.top/Article/details/gtwjngrqjc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daria6918.cn/Article/details/gtswzwyeaf.html

[L03] 设置自定义请求头
来源：http://dali.nwbrower.top/Article/details/gtyidsqpdn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.svipenyu.cn/Article/details/gtnebinvrh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtvssninxq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.haohaochexian.top/Article/details/gtfsuqftez.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgfzy.top/Article/details/gthztvnuro.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.daxiang520.top/Article/details/gtaejkqtel.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrnpdpsm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nwbrower.top/Article/details/gtgdslibpt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sxryk.cn/Article/details/gthlwalldp.html

[L04] 设置超时
来源：http://dali.xuetiantiany.cn/Article/details/gtastvchld.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ydzc1.top/Article/details/gtowbzguyx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yueranfly.top/Article/details/gtmnzyjzys.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.9152youxi.cn/Article/details/gtgxwyhict.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gtiojqskyi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.kuanghao11.cn/Article/details/gtdqtxwmcc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hfpthk.cn/Article/details/gtbcxnplgp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.birdmap.top/Article/details/gthaihqliy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tanke756.top/Article/details/gtyrozmdvo.html

[L05] 上传文件（multipart）
来源：http://dali.jiagoushi.top/Article/details/gtzdajbmve.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.wangshuangyany.cn/Article/details/gtkzbaczdy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hysaishi.cn/Article/details/gtwrersqyh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hywenlv.cn/Article/details/gturdzdbil.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zycfv.cn/Article/details/gtyigwlijb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xinyue.icu/Article/details/gtuqqgbyso.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hywenlv.cn/Article/details/gtbnzwmman.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.snrcjt.cn/Article/details/gtnzpstdbr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yvedp.cn/Article/details/gtsbrgapic.html

[L06] 解析响应为 JSON
来源：http://dali.guowangkeji.top/Article/details/gtyoegtyoz.html

Py:   resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gteivpgpei.html

PHP:  json_decode($body, true);
来源：http://dali.hnxiangtu.top/Article/details/gtsayqvmzy.html

JS:   await resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gtodakzsin.html

TS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gtgwsqyzqk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqoubqxj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqhwfegd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yonumen.top/Article/details/gtyrghbvrf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.havefunace.top/Article/details/gtwywnbiwh.html

[L07] 处理 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gthqmbcbin.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hfpthk.cn/Article/details/gtxwzsgfkj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmedttxi.html

JS:   resp.ok;  resp.status
来源：http://dali.xuanzx.com/Article/details/gtviimrefm.html

TS:   resp.ok;  resp.status
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxgjxtxys.html

Java: resp.statusCode()
来源：http://dali.gotoacloud.top/Article/details/gtnxlivhua.html

Go:   resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gthqmlsyql.html

Ruby: resp.code.to_i
来源：http://dali.iojbl.cn/Article/details/gtsmdhvbww.html

C#:   (int)resp.StatusCode
来源：http://dali.redwolf501.top/Article/details/gtpfawbcox.html

[L08] 并发请求多个地址
来源：http://dali.zhengqikj.top/Article/details/gtcvipqxhi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gaohongyu789.top/Article/details/gtpcifccpt.html

PHP:  curl_multi_init() 系列
来源：http://dali.aizwys.cn/Article/details/gtcgoquphc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gtfevwsthg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gtlzcdwbin.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cqqwz.cn/Article/details/gtqckeouyq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinghuilouyu.cn/Article/details/gtoribtrkv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigufen.top/Article/details/gtmkpltwji.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtecdzgxdo.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gthfmemlie.html

M. 命令行 / 进程 / 环境
来源：http://dali.fengsongda.top/Article/details/gtzdjnfkfb.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtqvmquzep.html

[M01] 读取命令行参数
来源：http://dali.sufxvd.cn/Article/details/gtjrovlgvq.html

Py:   sys.argv[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtgcebzmvy.html

PHP:  $argv;  $argc;
来源：http://dali.jiagoushi.top/Article/details/gtbubfzrhw.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gtptegtfip.html

TS:   process.argv.slice(2)
来源：http://dali.daria6918.cn/Article/details/gtitdkswml.html

Java: args 数组（main 方法参数）
来源：http://dali.tian-w.cn/Article/details/gtghhysmqz.html

Go:   os.Args[1:]
来源：http://dali.jiagoushi.top/Article/details/gtohusswni.html

Ruby: ARGV
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrlqorylx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gtuharjbrl.html

[M02] 读取环境变量
来源：http://dali.quarkkingdee.top/Article/details/gtjavkilfm.html

Py:   os.environ.get("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtjasvdnvz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sxryk.cn/Article/details/gtbuqpmmge.html

JS:   process.env.HOME
来源：http://dali.sufxvd.cn/Article/details/gtdgctephh.html

TS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gtuiyljixh.html

Java: System.getenv("HOME")
来源：http://dali.aizwys.cn/Article/details/gtirlvzrcz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.c1oappe.top/Article/details/gtyytmdbfi.html

Ruby: ENV["HOME"]
来源：http://dali.tanke756.top/Article/details/gthusbwxmj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fzhhl.top/Article/details/gtozzvzteg.html

[M03] 执行外部命令
来源：http://dali.vqdsnc.cn/Article/details/gtlljoiphz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jiagoushi.top/Article/details/gtserqmacj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tian-w.cn/Article/details/gtcsodpkys.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yanxiufei.cn/Article/details/gtvqrmffug.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.snrcjt.cn/Article/details/gtafgblkkq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.vqdsnc.cn/Article/details/gtjeiaavyi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tian-w.cn/Article/details/gtpjrsspfw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuetiantiany.cn/Article/details/gtncmlqwqw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yuanzhike.top/Article/details/gtwrpkuhuu.html

[M04] 获取当前工作目录
来源：http://dali.chenlongwang.top/Article/details/gthbpewhjk.html

Py:   os.getcwd()
来源：http://dali.quarkkingdee.top/Article/details/gtqdjorptg.html

PHP:  getcwd();
来源：http://dali.sweek.top/Article/details/gtpmchdvzw.html

JS:   process.cwd()
来源：http://dali.9152youxi.cn/Article/details/gtmoteiorl.html

TS:   process.cwd()
来源：http://dali.daxiang520.top/Article/details/gtocnewpxf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.smart0.xyz/Article/details/gtjqwvgcxe.html

Go:   os.Getwd()
来源：http://dali.ppjwa.cn/Article/details/gtgtfxztkv.html

Ruby: Dir.pwd
来源：http://dali.pycfn.com/Article/details/gtunaikuja.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shzxlz.cn/Article/details/gtpedrisog.html

[M05] 设置退出码
来源：http://dali.hywenlv.cn/Article/details/gtvryhespc.html

Py:   sys.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtsxuhdvbw.html

PHP:  exit(1);
来源：http://dali.daria6918.cn/Article/details/gtofpwwxyh.html


<!-- 参考信息 -->