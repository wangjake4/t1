代发 wailian999

Java: s.split("\\s*,\\s*")
来源：http://dali.cucudq.cn/Article/details/gt2vwcrrzkd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.snrcjt.cn/Article/details/gt2jxeibqsx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gt2kaqocdqd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nanxinkj.top/Article/details/gt2fhbiojuc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.feifeiyinyue.top/Article/details/gt2rszkirot.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gt2xltwzlxs.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhengqikj.top/Article/details/gt2tumklvtt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuanzx.com/Article/details/gt2lrkayotk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gt2fzbqzntq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gt2qonlmadg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hongshengwenyu.top/Article/details/gt2yeayliqt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.9152youxi.cn/Article/details/gt2xkiepxik.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gt2mvrqogla.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinqigfzy.top/Article/details/gt2matfooce.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cnaiyyzd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.daria6918.cn/Article/details/gt2sdktyiqh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gzhubu.top/Article/details/gt2zdebanto.html

TS:   /error/gim
来源：http://dali.sufxvd.cn/Article/details/gt2umtfkpix.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cucudq.cn/Article/details/gt2bwvhuamp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sweek.top/Article/details/gt2qcncpyjs.html

Ruby: s.scan(/error/i)
来源：http://dali.guannengcc.top/Article/details/gt2xwzenaug.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ouidvysx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj20258.top/Article/details/gt2bldlrjds.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zycfv.cn/Article/details/gt2hfitfnpg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gt2thdsxjpt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnqzz.top/Article/details/gt2snzkhquk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.birdmap.top/Article/details/gt2kxfgcmrf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gt2ezdhhwsc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sxryk.cn/Article/details/gt2xjgfxcbm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zycfv.cn/Article/details/gt2norjxgrr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenzaomai.com/Article/details/gt2ahsressb.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2yjvwygpp.html

J. 日期与时间
来源：http://dali.jiagoushi.top/Article/details/gt2tkqqyqbp.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ubwdujuq.html

[J01] 获取当前时间
来源：http://dali.ehwqpu.com/Article/details/gt2wbsvxpol.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ehwqpu.com/Article/details/gt2btqkgdjh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gt2iwleeorl.html

JS:   new Date();  Date.now()
来源：http://dali.ehwqpu.com/Article/details/gt2unphfjjt.html

TS:   new Date();  Date.now()
来源：http://dali.cashguo.top/Article/details/gt2bwumsozf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gogol.net.cn/Article/details/gt2fhrbvoin.html

Go:   time.Now()
来源：http://dali.yuxming.cn/Article/details/gt2uluzayhw.html

Ruby: Time.now
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bjkpduva.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sweek.top/Article/details/gt2gnpagkdg.html

[J02] 格式化输出
来源：http://dali.yueranfly.top/Article/details/gt2vmqvtxwj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hfpthk.cn/Article/details/gt2jsfeutev.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.316326.xyz/Article/details/gt2ffktqzzz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.andypj.xyz/Article/details/gt2pgalotzk.html

TS:   d.toISOString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2tjujiwts.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.pengpengdd.cyou/Article/details/gt2ihxtoqcl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.havefunace.top/Article/details/gt2igoekjdo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gt2iuxwtuvi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2llrkpaas.html

[J03] 字符串解析为日期
来源：http://dali.cqqwz.cn/Article/details/gt2gshzlrdv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigfzy.top/Article/details/gt2eqgundxy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pycfn.com/Article/details/gt2qdyqxakk.html

JS:   new Date("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gt2efonrksc.html

TS:   new Date("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gt2ihddyurn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gt2ocdhwrqg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gt2sinfbmsb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gt2umevarrh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xziqi.cn/Article/details/gt2gdjealel.html

[J04] 时间戳与日期互转
来源：http://dali.guannengcc.top/Article/details/gt2unconvjm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hammf.cn/Article/details/gt2udllzgay.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mrfaztsb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gzhubu.top/Article/details/gt2idommszq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2aehrtklx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yvedp.cn/Article/details/gt2heylphof.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2thenjebi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hvmyogso.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnxiangtu.top/Article/details/gt2immsyixs.html

[J05] 时间加减（加 7 天）
来源：http://dali.hammf.cn/Article/details/gt2ltxaxigt.html

Py:   now + timedelta(days=7)
来源：http://dali.yuxming.cn/Article/details/gt2bvofoffg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.wangshuangyany.cn/Article/details/gt2dktbpdfc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gaoldwdf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenzaomai.com/Article/details/gt2jbvhfias.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xyfcuoaq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.havefunace.top/Article/details/gt2zmulnwtn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jianghu66.top/Article/details/gt2wryssqjq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nqkumxzy.html

[J06] 计算两时间之差
来源：http://dali.kuanghao11.cn/Article/details/gt2sepelwhr.html

Py:   (end - start).total_seconds()
来源：http://dali.hywenlv.cn/Article/details/gt2litehoqx.html

PHP:  $end->diff($start)->days;
来源：http://dali.aizwys.cn/Article/details/gt2nyjpewes.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xziqi.cn/Article/details/gt2ighnzouw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nwbrower.top/Article/details/gt2ameiwelf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xylfe.cn/Article/details/gt2vplllose.html

Go:   end.Sub(start).Hours()
来源：http://dali.jqgfzy.top/Article/details/gt2nixhafqf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.mhx1999.top/Article/details/gt2lhgsbqeo.html

C#:   (end - start).TotalSeconds
来源：http://dali.yonumen.top/Article/details/gt2uexrqmlg.html

[J07] 比较两个日期
来源：http://dali.nanxuanxn.top/Article/details/gt2txbyplaw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gt2tfvcigna.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.birdmap.top/Article/details/gt2psroakoh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xinyue.icu/Article/details/gt2qwxdqwpt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.bjfxy.top/Article/details/gt2ombpuijm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgfzy.top/Article/details/gt2myknlfwb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yangfankeji.com/Article/details/gt2pophfkes.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gt2utatjryx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gt2idgjnmmj.html

[J08] 提取年月日与星期
来源：http://dali.guannengcc.top/Article/details/gt2knzwjqax.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yvedp.cn/Article/details/gt2xfxtprqc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhongyouzk.top/Article/details/gt2himjqwkf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qnfidugy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hywenlv.cn/Article/details/gt2rcuxwfvc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.wangshuangyany.cn/Article/details/gt2hesifwuj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tianlin.xyz/Article/details/gt2ckdqtbrl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ivvv.top/Article/details/gt2ieirpwya.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gotoacloud.top/Article/details/gt2srjbtxze.html

[J09] 时区处理
来源：http://dali.pycfn.com/Article/details/gt2hduywdoy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qvtvbmkz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.redwolf501.top/Article/details/gt2zonhjzjr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gt2lyqypqme.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gt2aarnozcf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.svipenyu.cn/Article/details/gt2wfvqftaz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hammf.cn/Article/details/gt2aerbxbct.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sweek.top/Article/details/gt2jaqxqhdi.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xziqi.cn/Article/details/gt2higolell.html

[J10] 取今天 / 本月第一天
来源：http://dali.yueranfly.top/Article/details/gt2jpymcory.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nanxuanxn.top/Article/details/gt2iwxtgiyi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gogol.net.cn/Article/details/gt2pccboiob.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bprmzcal.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daria6918.cn/Article/details/gt2dqvnzmwf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jqgfzy.top/Article/details/gt2blqqwlin.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxuanxn.top/Article/details/gt2akgypisw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yanxiufei.cn/Article/details/gt2cgsqwjzq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sweek.top/Article/details/gt2umtxtivz.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2kyebmdsg.html

K. JSON 与序列化
来源：http://dali.sweek.top/Article/details/gt2gulshbuu.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2gaxgncya.html

[K01] 对象转 JSON 字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2zsjlattd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gt2kvwyfgzv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zycfv.cn/Article/details/gt2yhzfvlhz.html

JS:   JSON.stringify(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2oxeqbskk.html

TS:   JSON.stringify(obj)
来源：http://dali.c1oappe.top/Article/details/gt2qwotepyx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tanke756.top/Article/details/gt2glwpqkrd.html

Go:   json.Marshal(obj)
来源：http://dali.yongpay.top/Article/details/gt2dgzehvfr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.kuanghao11.cn/Article/details/gt2qdvstjav.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2pqzohoox.html

[K02] JSON 字符串转对象
来源：http://dali.zhongyouzk.top/Article/details/gt2opmpvosp.html

Py:   json.loads(s)
来源：http://dali.gzhubu.top/Article/details/gt2ihhswdkr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jiagoushi.top/Article/details/gt2somdggoc.html

JS:   JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gt2szhadtqh.html

TS:   JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gt2osrjunpn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fzhhl.top/Article/details/gt2ypfujfay.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gt2icbzthjz.html

Ruby: JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gt2dgytpaae.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tianlin.xyz/Article/details/gt2fvaglnxq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sweek.top/Article/details/gt2hizuidde.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2epkxulrp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gt2lwvhlvfx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjutqels.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gt2ccqqnkrm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2xppvbszo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gaohongyu789.top/Article/details/gt2gmdvcxoz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2sfmolvow.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.meibo888.top/Article/details/gt2atvccjqr.html

[K04] 读取 JSON 文件
来源：http://dali.ppjwa.cn/Article/details/gt2rxmuyxcb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vlegcmal.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.fengsongda.top/Article/details/gt2nvcvrifo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daxiang520.top/Article/details/gt2jiizbceh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.quarkkingdee.top/Article/details/gt2sqijrcqx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sufxvd.cn/Article/details/gt2pazpxhth.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yonumen.top/Article/details/gt2nvynssan.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2tlpjkeqy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj202588.top/Article/details/gt2pqgeddqx.html

[K05] 深拷贝对象
来源：http://dali.yj20258.top/Article/details/gt2omnkfexe.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2haoxjmoo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinqigufen.top/Article/details/gt2kxtihykj.html

JS:   structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2heyoneyf.html

TS:   structuredClone(obj)
来源：http://dali.mhx1999.top/Article/details/gt2cbosjdbx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhoulong.xyz/Article/details/gt2fqhehhox.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangshuangyany.cn/Article/details/gt2jrwpiwoo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.pengpengdd.cyou/Article/details/gt2silkhhuz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xuanzx.com/Article/details/gt2mvuyvggm.html

[K06] 解析 URL 查询串
来源：http://dali.yangfankeji.com/Article/details/gt2zprofijr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zpktkcrp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cheryme.top/Article/details/gt2zckvsvtv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aibaodan.cn/Article/details/gt2iwoemfij.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gt2zlfhimig.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhongyouzk.top/Article/details/gt2ynktjwwj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gt2pgyxgyep.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gt2dzyyhjid.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gt2dtupymri.html

[K07] 进制转换
来源：http://dali.yongpay.top/Article/details/gt2cowggxjt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yongpay.top/Article/details/gt2rkhgieoq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shangyingyoupin.top/Article/details/gt2uecgsuhw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2fycbreyk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2opfyyzpx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gt2auagllpt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yongpay.top/Article/details/gt2lckdmapm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigufen.top/Article/details/gt2ojcjhefe.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2zchyrkuz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fzhhl.top/Article/details/gt2eygzdvtm.html

Py:   pickle.dumps(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2dpozbbph.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xylfe.cn/Article/details/gt2jtsqtbmo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gt2ovqypufz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.c1oappe.top/Article/details/gt2kzzpeaao.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sxryk.cn/Article/details/gt2dowvpfbe.html

Go:   encoding/gob
来源：http://dali.aibaodan.cn/Article/details/gt2postgyrx.html

Ruby: Marshal.dump(obj)
来源：http://dali.daria6918.cn/Article/details/gt2ciathcaz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sxryk.cn/Article/details/gt2kignzklt.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2lybynzae.html

L. 网络请求
来源：http://dali.zdqjudy.top/Article/details/gt2skyvmdqb.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bfvtajjt.html

[L01] 发送 GET 请求
来源：http://dali.nanxuanxn.top/Article/details/gt2cinaztqh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jqgufenzy.top/Article/details/gt2stjaztjz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xuetiantiany.cn/Article/details/gt2tsadurtb.html

JS:   await fetch(url)
来源：http://dali.zhongyouzk.top/Article/details/gt2kcyvgyrn.html

TS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gt2uidajtkl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gotoacloud.top/Article/details/gt2okbyjtmj.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenzaomai.com/Article/details/gt2bexdnkyw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ppjwa.cn/Article/details/gt2blsavjdj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.316326.xyz/Article/details/gt2fbhlwsox.html

[L02] 发送 POST JSON
来源：http://dali.jinqigufen.top/Article/details/gt2logdmdfz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hnxiangtu.top/Article/details/gt2hfwfvwqn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.iojbl.cn/Article/details/gt2xlukmggb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.iojbl.cn/Article/details/gt2wdyhsjta.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cqqwz.cn/Article/details/gt2sqdrosaz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hammf.cn/Article/details/gt2icsctpis.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.birdmap.top/Article/details/gt2ljsqowno.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.wangshuangyany.cn/Article/details/gt2czylocpa.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guowangkeji.top/Article/details/gt2veiqsatw.html

[L03] 设置自定义请求头
来源：http://dali.xinyue.icu/Article/details/gt2tdkuhmuc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gzhubu.top/Article/details/gt2dnpamvur.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ehwqpu.com/Article/details/gt2lqluqylm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.haohaochexian.top/Article/details/gt2vuklzgqb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxinkj.top/Article/details/gt2aijgdygx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.redwolf501.top/Article/details/gt2iyujxerw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gt2miclerih.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2emwpcwcn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ehwqpu.com/Article/details/gt2hyvmykbl.html

[L04] 设置超时
来源：http://dali.hammf.cn/Article/details/gt2hciklrck.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj20258888.top/Article/details/gt2ieidxveo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.birdmap.top/Article/details/gt2qnsbxaoh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenjidiqi.icu/Article/details/gt2choamszk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tianlin.xyz/Article/details/gt2lbnxhlgv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.fzhhl.top/Article/details/gt2cyfalday.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hnxiangtu.top/Article/details/gt2oeautdlj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuanzx.com/Article/details/gt2nvihebep.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.meibo888.top/Article/details/gt2mpgbbvoe.html

[L05] 上传文件（multipart）
来源：http://dali.ydzc1.top/Article/details/gt2oznsqvcr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yangfankeji.com/Article/details/gt2tkjkyhxi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.birdmap.top/Article/details/gt2xknrgedv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pengpengdd.cyou/Article/details/gt2coujcvbu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sufxvd.cn/Article/details/gt2xbtvildm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zdqjudy.top/Article/details/gt2ctpfcxxs.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aibaodan.cn/Article/details/gt2gbsrvifa.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jqgfzy.top/Article/details/gt2tslafzbo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2lgmwkbbg.html

[L06] 解析响应为 JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mqbbpbut.html

Py:   resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gt2fogopbad.html

PHP:  json_decode($body, true);
来源：http://dali.cucudq.cn/Article/details/gt2oxezrzcf.html

JS:   await resp.json()
来源：http://dali.jqgfzy.top/Article/details/gt2wlqvesie.html

TS:   await resp.json()
来源：http://dali.cqqwz.cn/Article/details/gt2milpjsge.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ybcxt.top/Article/details/gt2yimhyjsx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guowangkeji.top/Article/details/gt2dqyqvxlk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.snrcjt.cn/Article/details/gt2kbmhwnor.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hywenlv.cn/Article/details/gt2sysbfxil.html

[L07] 处理 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gt2fnlfvrve.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yueranfly.top/Article/details/gt2dtjqwvdi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sysykeji.top/Article/details/gt2jpnaiofc.html

JS:   resp.ok;  resp.status
来源：http://dali.gaohongyu789.top/Article/details/gt2rzfpmjau.html

TS:   resp.ok;  resp.status
来源：http://dali.ppjwa.cn/Article/details/gt2jnfbqggu.html

Java: resp.statusCode()
来源：http://dali.tanke756.top/Article/details/gt2xzeevjar.html

Go:   resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gt2llkocttq.html

Ruby: resp.code.to_i
来源：http://dali.hnxiangtu.top/Article/details/gt2azzlfnet.html

C#:   (int)resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gt2cswwhcym.html

[L08] 并发请求多个地址
来源：http://dali.yuxming.cn/Article/details/gt2drwohlus.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.meibo888.top/Article/details/gt2tyhtlpdu.html

PHP:  curl_multi_init() 系列
来源：http://dali.pengpengdd.cyou/Article/details/gt2cmzdqqek.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gt2qegqiedo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ozaizpqg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigfzy.top/Article/details/gt2knlwagqo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.mhx1999.top/Article/details/gt2aoqfyirz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.birdmap.top/Article/details/gt2iayeuisg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhengqikj.top/Article/details/gt2aojzojec.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2qeqbgqzk.html

M. 命令行 / 进程 / 环境
来源：http://dali.gogol.net.cn/Article/details/gt2tqkwjvhd.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2xmdtloab.html

[M01] 读取命令行参数
来源：http://dali.snrcjt.cn/Article/details/gt2bsayzxwc.html

Py:   sys.argv[1:]
来源：http://dali.quarkkingdee.top/Article/details/gt2xhxmnuag.html

PHP:  $argv;  $argc;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wzcztkii.html

JS:   process.argv.slice(2)
来源：http://dali.shzxlz.cn/Article/details/gt2bxofmhtl.html

TS:   process.argv.slice(2)
来源：http://dali.daxiang520.top/Article/details/gt2ukmntwze.html

Java: args 数组（main 方法参数）
来源：http://dali.tianlin.xyz/Article/details/gt2iuuebyit.html

Go:   os.Args[1:]
来源：http://dali.xziqi.cn/Article/details/gt2aaboqudw.html

Ruby: ARGV
来源：http://dali.cucudq.cn/Article/details/gt2rjkvuecf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.birdmap.top/Article/details/gt2uiqzkxkz.html

[M02] 读取环境变量
来源：http://dali.bjfxy.top/Article/details/gt2xaybacxo.html

Py:   os.environ.get("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gt2ucnlgwwe.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gt2zqoloyfo.html

JS:   process.env.HOME
来源：http://dali.cdnleiting.top/Article/details/gt2qxkshgmr.html

TS:   process.env.HOME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2chfkhoam.html

Java: System.getenv("HOME")
来源：http://dali.iojbl.cn/Article/details/gt2llxdioiu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2cfibxblg.html

Ruby: ENV["HOME"]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kibhbqjd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sufxvd.cn/Article/details/gt2ipcuamyj.html

[M03] 执行外部命令
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ojpdgoih.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xziqi.cn/Article/details/gt2erulpkcf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guannengcc.top/Article/details/gt2ktkcsrzw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gbrssbmo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gt2gsiuszqm.html


<!-- 参考信息 -->