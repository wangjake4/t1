代发 wailian999

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.redwolf501.top/Article/details/gtmcmemrmp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yonumen.top/Article/details/gtnrwegynl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gtbnxojsmn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gtmfroebvg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hywenlv.cn/Article/details/gtyrxgdhsi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhiwuduotai.top/Article/details/gtcvgvaayp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gttaajgbce.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gogol.net.cn/Article/details/gtwyvskwkq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hfpthk.cn/Article/details/gtdmlijaag.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gtcrokfcqw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jiagoushi.top/Article/details/gtboympabt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ybcxt.top/Article/details/gtisznjkeh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yanxiufei.cn/Article/details/gtywjdwkwd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gtrtzouotr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ydzc1.top/Article/details/gtnycluoza.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.haohaochexian.top/Article/details/gtvpwoanoa.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gtxnrqofyr.html

[I07] 忽略大小写与多行模式
来源：http://dali.pycfn.com/Article/details/gtpongvskv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.guowangkeji.top/Article/details/gtefwxeloq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tanke756.top/Article/details/gtuomqykiv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nanxuanxn.top/Article/details/gttjmgwjgq.html

TS:   /error/gim
来源：http://dali.xuetiantiany.cn/Article/details/gtguxtxhlk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.9152youxi.cn/Article/details/gtrhvbvedy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hongshengwenyu.top/Article/details/gtkhkbtfmh.html

Ruby: s.scan(/error/i)
来源：http://dali.hywenlv.cn/Article/details/gtevgaggcb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.c1oappe.top/Article/details/gtugagjnno.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.9152youxi.cn/Article/details/gtozznyefp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuetiantiany.cn/Article/details/gtnkxydwwc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhixingplan.top/Article/details/gtqjoyyfgx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gtrymhbcni.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.vqdsnc.cn/Article/details/gtwbcawllg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdxyyeeho.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hammf.cn/Article/details/gtegcckrzw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.fengsongda.top/Article/details/gtizjuhvpi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gtzouvpqco.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtlmxzetnh.html

J. 日期与时间
来源：http://dali.jinqigfzy.top/Article/details/gtniunymav.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtcbuiwkcy.html

[J01] 获取当前时间
来源：http://dali.jyoumei.cn/Article/details/gtqxqlashn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jianghu66.top/Article/details/gtdmrqouib.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gtnqjhsrso.html

JS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gtjwpxkfja.html

TS:   new Date();  Date.now()
来源：http://dali.kuanghao11.cn/Article/details/gtkpopdsqg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jqgfzy.top/Article/details/gtmjfllilg.html

Go:   time.Now()
来源：http://dali.andypj.xyz/Article/details/gtufrsbzbs.html

Ruby: Time.now
来源：http://dali.quarkkingdee.top/Article/details/gtdlebreeb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.haohaochexian.top/Article/details/gtalrzjvox.html

[J02] 格式化输出
来源：http://dali.xylfe.cn/Article/details/gtqjnklhoa.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fengsongda.top/Article/details/gtsiibxpgj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gzhubu.top/Article/details/gtmvkonvtm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cucudq.cn/Article/details/gtkuympckk.html

TS:   d.toISOString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtayrwiyps.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenzaomai.com/Article/details/gtdvthgtrp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.birdmap.top/Article/details/gtynqgcrng.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.316326.xyz/Article/details/gtdsvtiyar.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hammf.cn/Article/details/gtqftrcvqs.html

[J03] 字符串解析为日期
来源：http://dali.pengpengdd.cyou/Article/details/gtmldjbsnd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtietsbenf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.bjfxy.top/Article/details/gtmkepxzmd.html

JS:   new Date("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gthidqcwqz.html

TS:   new Date("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtzyhlowbe.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtstpszqxn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtdddcmtvm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtxvpihrck.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.haohaochexian.top/Article/details/gtnirvnzeq.html

[J04] 时间戳与日期互转
来源：http://dali.zhengqikj.top/Article/details/gtjssjwsln.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtlsoupcgx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gotoacloud.top/Article/details/gtsklryfjc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nanxuanxn.top/Article/details/gtyzourzro.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenlongwang.top/Article/details/gtbxddxyfx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.iojbl.cn/Article/details/gtvbcslrec.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxfyhqjg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqkuplfd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtcbylrjxw.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinqigufen.top/Article/details/gtkornpjbc.html

Py:   now + timedelta(days=7)
来源：http://dali.smart0.xyz/Article/details/gtrjlulylk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.dashuyun.cn/Article/details/gtglnvauqi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yueranfly.top/Article/details/gtokqqwyaj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sufxvd.cn/Article/details/gtagvqkokb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.daxiang520.top/Article/details/gtanjgkmmn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shuidangran.top/Article/details/gtysinrvfx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.guannengcc.top/Article/details/gtmlcwsxbo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hnxiangtu.top/Article/details/gtuczbifeq.html

[J06] 计算两时间之差
来源：http://dali.jlsjyb.cn/Article/details/gtlemhqzsi.html

Py:   (end - start).total_seconds()
来源：http://dali.zdqjudy.top/Article/details/gtlujvxapm.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnxiangtu.top/Article/details/gtqnzeznun.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yangfankeji.com/Article/details/gtvskkntnp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258.top/Article/details/gtlblfhhts.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzowpbtgv.html

Go:   end.Sub(start).Hours()
来源：http://dali.zycfv.cn/Article/details/gtvwotzaip.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj202588.top/Article/details/gtrxdufllh.html

C#:   (end - start).TotalSeconds
来源：http://dali.sxryk.cn/Article/details/gtitgckjkk.html

[J07] 比较两个日期
来源：http://dali.zhoulong.xyz/Article/details/gtleqqinea.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gtixgbwjaz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yuanzhike.top/Article/details/gtbetwiypp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jianghu66.top/Article/details/gtkxutykhs.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gotoacloud.top/Article/details/gtclyiiacp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigfzy.top/Article/details/gtbebyuiwh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cdnleiting.top/Article/details/gtikzmhhxv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gtdklzyybd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gtpixduspe.html

[J08] 提取年月日与星期
来源：http://dali.jlsjyb.cn/Article/details/gtsdfpcwdt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jlsjyb.cn/Article/details/gtmhuasnke.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yueranfly.top/Article/details/gtfvcocmon.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guowangkeji.top/Article/details/gttsrwtgdg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jqgufenzy.top/Article/details/gtepfjnhmh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinqigufen.top/Article/details/gtrikkqwnu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.dianchejie.cn/Article/details/gtxqqsnkef.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yvedp.cn/Article/details/gtdjpskzqz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhiwuduotai.top/Article/details/gtokatkzmo.html

[J09] 时区处理
来源：http://dali.zhijiandao.cn/Article/details/gtjvzcbbio.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yuxming.cn/Article/details/gtarhestex.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhixingplan.top/Article/details/gtmvckczco.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.kuanghao11.cn/Article/details/gtkagyhaft.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gtrloaaldr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zdqjudy.top/Article/details/gtlzpqpjuy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jqgfzy.top/Article/details/gtdqmaevpj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.feifeiyinyue.top/Article/details/gtziqcqpmx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nwbrower.top/Article/details/gtsqvehydi.html

[J10] 取今天 / 本月第一天
来源：http://dali.sysykeji.top/Article/details/gtbruaudlv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhongyouzk.top/Article/details/gtatmuayos.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hywenlv.cn/Article/details/gtxtopckgb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhongyouzk.top/Article/details/gtvjvphaft.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.andypj.xyz/Article/details/gtorllsbdr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yonumen.top/Article/details/gtartljfit.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj20258.top/Article/details/gttxeskszl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhoulong.xyz/Article/details/gtoqkmqktq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinqigfzy.top/Article/details/gtbzhochjj.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtoavpwpnk.html

K. JSON 与序列化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthmznachg.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtecgjjsch.html

[K01] 对象转 JSON 字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxitaocae.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gtdbhbbatt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlzjkitbl.html

JS:   JSON.stringify(obj)
来源：http://dali.tianlin.xyz/Article/details/gtdinkcmxw.html

TS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gtkmerlocq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cucudq.cn/Article/details/gtshvopkjl.html

Go:   json.Marshal(obj)
来源：http://dali.gzhubu.top/Article/details/gttlfdsuzg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuanzx.com/Article/details/gtjecrgvtl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinqigufen.top/Article/details/gtwehbucvh.html

[K02] JSON 字符串转对象
来源：http://dali.shuidangran.top/Article/details/gtrqobtpun.html

Py:   json.loads(s)
来源：http://dali.jinqigufen.top/Article/details/gtndsddjht.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sxryk.cn/Article/details/gtoztejdto.html

JS:   JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gtomckirqe.html

TS:   JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gtwexknwml.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gtrgrrcnmi.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtncsnopjc.html

Ruby: JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gtwlnfoaff.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzajmsaw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zdqjudy.top/Article/details/gtwybwifqo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yuxming.cn/Article/details/gtxymfxibm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gtvorouumn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhengqikj.top/Article/details/gttrorjudy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fzhhl.top/Article/details/gttxgqwjnj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xylfe.cn/Article/details/gtwambogog.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.andypj.xyz/Article/details/gtoavtoqyu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.daxiang520.top/Article/details/gtyxtlhnvl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqsgllcg.html

[K04] 读取 JSON 文件
来源：http://dali.hysaishi.cn/Article/details/gtguguogzl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.pycfn.com/Article/details/gtxnkvevnl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cheryme.top/Article/details/gtpvgiywku.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gtdaoqonzi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gtypxlibxe.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.fzhhl.top/Article/details/gtrhofwywp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gtgiaihyih.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpejiiurk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ppjwa.cn/Article/details/gtcakozcxa.html

[K05] 深拷贝对象
来源：http://dali.gaohongyu789.top/Article/details/gtjdcuewqk.html

Py:   copy.deepcopy(obj)
来源：http://dali.fengsongda.top/Article/details/gtnfapeclo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.pengpengdd.cyou/Article/details/gtxllrkbbg.html

JS:   structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gtljivaqap.html

TS:   structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gtpgnpahss.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sufxvd.cn/Article/details/gthcpqffpd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sufxvd.cn/Article/details/gtfmianrkw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj20258888.top/Article/details/gtuidcalph.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tianlin.xyz/Article/details/gtutxbzorl.html

[K06] 解析 URL 查询串
来源：http://dali.gaohongyu789.top/Article/details/gtnlutosyd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xziqi.cn/Article/details/gttebwolby.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.iojbl.cn/Article/details/gtfnntbwql.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gtzmxwpusb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gttyzbdbsn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhoulong.xyz/Article/details/gtjsnfxose.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gtahfdzstw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gtzfmyilii.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gtqemxmzjj.html

[K07] 进制转换
来源：http://dali.svipenyu.cn/Article/details/gtqvwruvxh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtizcmppim.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sufxvd.cn/Article/details/gterrneoyu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtbobxgtdw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtrgedkvph.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtnurqnyxc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.wangshuangyany.cn/Article/details/gtxicwvkiv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dashuyun.cn/Article/details/gthzyxqyxm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtfecjvnnc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zdqjudy.top/Article/details/gtkulbbqan.html

Py:   pickle.dumps(obj)
来源：http://dali.gotoacloud.top/Article/details/gtljttyexj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.havefunace.top/Article/details/gtqtcgdfgy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.guowangkeji.top/Article/details/gtypjlsajj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yvedp.cn/Article/details/gtsercrqdz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jyoumei.cn/Article/details/gtdtuwhxve.html

Go:   encoding/gob
来源：http://dali.ivvv.top/Article/details/gtxikcivvc.html

Ruby: Marshal.dump(obj)
来源：http://dali.dianchejie.cn/Article/details/gtcjiekpbs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.aibaodan.cn/Article/details/gtbsrckunx.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtxbpitdqv.html

L. 网络请求
来源：http://dali.jiagoushi.top/Article/details/gtgqigrnal.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtoaqowgaj.html

[L01] 发送 GET 请求
来源：http://dali.xylfe.cn/Article/details/gtnwttpvpq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cheryme.top/Article/details/gtbybbario.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cqqwz.cn/Article/details/gtjtgbmsyb.html

JS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gtalndsrmb.html

TS:   await fetch(url)
来源：http://dali.shuidangran.top/Article/details/gttxliyeqm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ppjwa.cn/Article/details/gtmezhkyrw.html

Go:   resp, err := http.Get(url)
来源：http://dali.feifeiyinyue.top/Article/details/gtzdvnwsag.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.redwolf501.top/Article/details/gtejehovkc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yongpay.top/Article/details/gttqrbgsyh.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbexykpye.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gtoeqfsdoj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zdqjudy.top/Article/details/gtncvluueo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenzaomai.com/Article/details/gtfbmwcvny.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hfpthk.cn/Article/details/gtcaohxypm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.birdmap.top/Article/details/gtiehpgtun.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.c1oappe.top/Article/details/gtfoquuagn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tanke756.top/Article/details/gteqnycnys.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jyoumei.cn/Article/details/gtkicvzwyg.html

[L03] 设置自定义请求头
来源：http://dali.316326.xyz/Article/details/gtvewsqbvy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhixingplan.top/Article/details/gtpawevoyu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hnqzz.top/Article/details/gtdkswbesb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gtfuxbautd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xylfe.cn/Article/details/gtwngodspg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sxryk.cn/Article/details/gtgbfehfqz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gtyieafwym.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jyoumei.cn/Article/details/gtwsalzpgy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jqgfzy.top/Article/details/gtisbsarvk.html

[L04] 设置超时
来源：http://dali.sufxvd.cn/Article/details/gttehhxrpl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.haohaochexian.top/Article/details/gtuqzgtiyd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhiwuduotai.top/Article/details/gtxtbfvfne.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gtwmxvgcll.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj202588.top/Article/details/gtnaxjrfph.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daria6918.cn/Article/details/gtwshunnsy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hysaishi.cn/Article/details/gtgmatpuuh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yvedp.cn/Article/details/gtqpwubgra.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xziqi.cn/Article/details/gtgzhqzwfz.html

[L05] 上传文件（multipart）
来源：http://dali.meibo888.top/Article/details/gtsnitxupd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.meibo888.top/Article/details/gtibkpqwxd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenjidiqi.icu/Article/details/gttcjrbymq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gtorjzcsjj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj202588.top/Article/details/gtatccgexd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gzhubu.top/Article/details/gtlsyvduqc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.c1oappe.top/Article/details/gtizxklqdo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.bjfxy.top/Article/details/gtdndlhqhk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtijsrwtgt.html

[L06] 解析响应为 JSON
来源：http://dali.chenzaomai.com/Article/details/gtfewrfkrl.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gtfghfzioh.html

PHP:  json_decode($body, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpfwlzdcd.html

JS:   await resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gtolurjzfb.html

TS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtihcssefo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpleinemk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj20258888.top/Article/details/gthgptnkns.html

Ruby: JSON.parse(resp.body)
来源：http://dali.bjfxy.top/Article/details/gtqflnhgen.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangshuangyany.cn/Article/details/gttbgibdgu.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgfzy.top/Article/details/gtxdzkkwco.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jianghu66.top/Article/details/gtvcndwhge.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinqigufen.top/Article/details/gtcemuftkn.html

JS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gtgccpxldz.html

TS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gtblwhaamy.html

Java: resp.statusCode()
来源：http://dali.nwbrower.top/Article/details/gtwtsjisvb.html

Go:   resp.StatusCode
来源：http://dali.shzxlz.cn/Article/details/gtfplhdnui.html

Ruby: resp.code.to_i
来源：http://dali.hfpthk.cn/Article/details/gtqcdqdugh.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gtdbbfsehu.html

[L08] 并发请求多个地址
来源：http://dali.haohaochexian.top/Article/details/gthkbxgtdl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hongshengwenyu.top/Article/details/gtcmdwdyuc.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuanzx.com/Article/details/gtffvamazw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gtjyhslhfe.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gtuoazitno.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhiwuduotai.top/Article/details/gtcnfwxqag.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.316326.xyz/Article/details/gtrhcuesik.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfufxdyy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.0kj1m.cn/Article/details/gthhrkvhdb.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtyakewemu.html

M. 命令行 / 进程 / 环境
来源：http://dali.sxryk.cn/Article/details/gtfobyqxqv.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtddxrgykg.html

[M01] 读取命令行参数
来源：http://dali.aizwys.cn/Article/details/gtfrarthcw.html

Py:   sys.argv[1:]
来源：http://dali.jinqigufen.top/Article/details/gtrsbxovao.html

PHP:  $argv;  $argc;
来源：http://dali.sysykeji.top/Article/details/gtatppkzzv.html

JS:   process.argv.slice(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnshwsbex.html

TS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gtlsufpecg.html

Java: args 数组（main 方法参数）
来源：http://dali.ivvv.top/Article/details/gtdznwsazc.html

Go:   os.Args[1:]
来源：http://dali.mhx1999.top/Article/details/gtybthzose.html

Ruby: ARGV
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpsrghsjf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.daria6918.cn/Article/details/gtxluwuaqu.html

[M02] 读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gteixwwqjq.html

Py:   os.environ.get("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtnaucvwxe.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.quarkkingdee.top/Article/details/gtqddcfnno.html

JS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gtlanbgvml.html

TS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gtlvujooac.html

Java: System.getenv("HOME")
来源：http://dali.316326.xyz/Article/details/gtxmtsrekm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtzekvgfjd.html

Ruby: ENV["HOME"]
来源：http://dali.cheryme.top/Article/details/gtuzccozhx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fengsongda.top/Article/details/gtxcpjmcus.html

[M03] 执行外部命令
来源：http://dali.fengsongda.top/Article/details/gtwsscbpzc.html


<!-- 参考信息 -->