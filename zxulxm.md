代发 wailian999

Java: s.split("\\s*,\\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gt2rhfztpov.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ikzwmady.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gt2ccfrjfjc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ydzc1.top/Article/details/gt2irlsjlpc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigfzy.top/Article/details/gt2rbbbavra.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qrouxqgo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xuanzx.com/Article/details/gt2sswjynmg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigufen.top/Article/details/gt2kvpwlyjw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenlongwang.top/Article/details/gt2zmbczins.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsnvpey.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.snrcjt.cn/Article/details/gt2djihvbow.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jiagoushi.top/Article/details/gt2yavslclc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gt2muwxwfxc.html

[I07] 忽略大小写与多行模式
来源：http://dali.xuetiantiany.cn/Article/details/gt2mcbveclp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.daxiang520.top/Article/details/gt2ajndvism.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fgvdvzxg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ioyprvhh.html

TS:   /error/gim
来源：http://dali.kuanghao11.cn/Article/details/gt2pacsktxb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pymbbilk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xfypytov.html

Ruby: s.scan(/error/i)
来源：http://dali.nwbrower.top/Article/details/gt2qdzwizwk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xziqi.cn/Article/details/gt2ovbyeukp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.meibo888.top/Article/details/gt2ogsjbjoh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.svipenyu.cn/Article/details/gt2hrgmameo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gt2aopmxyna.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gt2bbezurgb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.andypj.xyz/Article/details/gt2acopyvav.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pengpengdd.cyou/Article/details/gt2alepjmmy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj20258.top/Article/details/gt2ddwawbiy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.svipenyu.cn/Article/details/gt2lyhnwgii.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yangfankeji.com/Article/details/gt2ydbkzdcf.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2lzfqvlfd.html

J. 日期与时间
来源：http://dali.iojbl.cn/Article/details/gt2vcphhlmc.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2xsaljuhx.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lzmhbjdc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ydzc1.top/Article/details/gt2fyxzqajc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gt2lperiaee.html

JS:   new Date();  Date.now()
来源：http://dali.tian-w.cn/Article/details/gt2iebqnelo.html

TS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gt2zorbozrb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.haohaochexian.top/Article/details/gt2fnzxrwfa.html

Go:   time.Now()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jyhibqbs.html

Ruby: Time.now
来源：http://dali.dianchejie.cn/Article/details/gt2yxcvxbdm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuanzhike.top/Article/details/gt2fevvcbfp.html

[J02] 格式化输出
来源：http://dali.yonumen.top/Article/details/gt2qcwkvzgl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gt2sqycuxzg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.guowangkeji.top/Article/details/gt2goquiirz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cucudq.cn/Article/details/gt2mrlgpdhz.html

TS:   d.toISOString()
来源：http://dali.guannengcc.top/Article/details/gt2igjvumos.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.c1oappe.top/Article/details/gt2yuxcarvy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sbtthnng.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shangyingyoupin.top/Article/details/gt2uecowwoe.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ydzc1.top/Article/details/gt2vpwfympv.html

[J03] 字符串解析为日期
来源：http://dali.cqqwz.cn/Article/details/gt2svkldjlw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj202588.top/Article/details/gt2bntbxcct.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ivvv.top/Article/details/gt2rgioyago.html

JS:   new Date("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gt2wlzsienk.html

TS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2amgtdyxz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gt2aehanbll.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.havefunace.top/Article/details/gt2olqrwdat.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gt2jngksnbc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yuxming.cn/Article/details/gt2nmrwrpkp.html

[J04] 时间戳与日期互转
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ohlkffkf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dzocuaux.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.meibo888.top/Article/details/gt2ebhorlmi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.quarkkingdee.top/Article/details/gt2upeyuhny.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jyoumei.cn/Article/details/gt2tcwarnul.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.andypj.xyz/Article/details/gt2rprksgya.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2wxqspfja.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.mhx1999.top/Article/details/gt2nzzrdcdr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.c1oappe.top/Article/details/gt2tsyzjtzk.html

[J05] 时间加减（加 7 天）
来源：http://dali.c1oappe.top/Article/details/gt2mpymlbgu.html

Py:   now + timedelta(days=7)
来源：http://dali.cdnleiting.top/Article/details/gt2lgdtzlbt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cqqwz.cn/Article/details/gt2iajaadwa.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigfzy.top/Article/details/gt2mhzhllxb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shzxlz.cn/Article/details/gt2rthcekwe.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cashguo.top/Article/details/gt2tprliyvr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhongyouzk.top/Article/details/gt2pgmfbqea.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj202588.top/Article/details/gt2nxkmvvrn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nwbrower.top/Article/details/gt2fzanxlpm.html

[J06] 计算两时间之差
来源：http://dali.chenjidiqi.icu/Article/details/gt2jmwasajz.html

Py:   (end - start).total_seconds()
来源：http://dali.aibaodan.cn/Article/details/gt2miyggieg.html

PHP:  $end->diff($start)->days;
来源：http://dali.wangshuangyany.cn/Article/details/gt2cfikzqti.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tianlin.xyz/Article/details/gt2xqplqnvw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.daria6918.cn/Article/details/gt2qcbbedxg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258888.top/Article/details/gt2okkrwvhj.html

Go:   end.Sub(start).Hours()
来源：http://dali.daxiang520.top/Article/details/gt2ijrokwrt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hammf.cn/Article/details/gt2mzwzykyk.html

C#:   (end - start).TotalSeconds
来源：http://dali.sufxvd.cn/Article/details/gt2yftlwzvn.html

[J07] 比较两个日期
来源：http://dali.pengpengdd.cyou/Article/details/gt2thruybsu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gt2edsqaoyo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhongyouzk.top/Article/details/gt2mfsnupny.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.dashuyun.cn/Article/details/gt2jowxihvm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gt2cckescol.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ydzc1.top/Article/details/gt2knwyvulw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cashguo.top/Article/details/gt2lxxaqkur.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gt2eeivphlm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gt2vxoxrsce.html

[J08] 提取年月日与星期
来源：http://dali.ybcxt.top/Article/details/gt2hrqwxuqw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.pengpengdd.cyou/Article/details/gt2dzmyqkrq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgfzy.top/Article/details/gt2whgvjjse.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sweek.top/Article/details/gt2jvyzprgk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yueranfly.top/Article/details/gt2klhpjmhq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yanxiufei.cn/Article/details/gt2ksoaxlyj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yvedp.cn/Article/details/gt2orrociel.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sufxvd.cn/Article/details/gt2ikpigozj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhixingplan.top/Article/details/gt2bycdgjta.html

[J09] 时区处理
来源：http://dali.jqgufenzy.top/Article/details/gt2hfxambix.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.birdmap.top/Article/details/gt2tdrygpxr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yonumen.top/Article/details/gt2enxdytgn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dashuyun.cn/Article/details/gt2pemzyusz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gt2oqqxsyyb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cdnleiting.top/Article/details/gt2dfgvwtdy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sufxvd.cn/Article/details/gt2immfvsrr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nwbrower.top/Article/details/gt2qslutpuy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.bjfxy.top/Article/details/gt2jqphdzly.html

[J10] 取今天 / 本月第一天
来源：http://dali.jiagoushi.top/Article/details/gt2ozorjxnc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sysykeji.top/Article/details/gt2dgmnxmgi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cdnleiting.top/Article/details/gt2ardtvtjx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xziqi.cn/Article/details/gt2swzjnogd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2kkwbvcwr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gzhubu.top/Article/details/gt2tdjixmcz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sweek.top/Article/details/gt2gpnyvzzj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.mhx1999.top/Article/details/gt2cupkjxjl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fengsongda.top/Article/details/gt2bfnkvrhf.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2xgedkhwk.html

K. JSON 与序列化
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kcayxxji.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2nrogyqyt.html

[K01] 对象转 JSON 字符串
来源：http://dali.daxiang520.top/Article/details/gt2qwogbwlv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tianlin.xyz/Article/details/gt2tqxlefvq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gt2afuzivmg.html

JS:   JSON.stringify(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2aixxnhio.html

TS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2aitvqgwy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.kuanghao11.cn/Article/details/gt2wcsryaoj.html

Go:   json.Marshal(obj)
来源：http://dali.fzhhl.top/Article/details/gt2ndrcsure.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.mhx1999.top/Article/details/gt2zktynifs.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ixvcgmfd.html

[K02] JSON 字符串转对象
来源：http://dali.0kj1m.cn/Article/details/gt2yfiwelrl.html

Py:   json.loads(s)
来源：http://dali.xinyue.icu/Article/details/gt2pynekmxw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yangfankeji.com/Article/details/gt2vukqpdwi.html

JS:   JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gt2fhqbadzl.html

TS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gt2xattbvdg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gt2xkyjyuzq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tianlin.xyz/Article/details/gt2gqvhjstr.html

Ruby: JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gt2aneqmhhh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cqqwz.cn/Article/details/gt2wxkhsbzu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinqigufen.top/Article/details/gt2ilkfsihl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jqgufenzy.top/Article/details/gt2efgpijna.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dashuyun.cn/Article/details/gt2hrjylqub.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gt2xfrdqowg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.guowangkeji.top/Article/details/gt2jnialaim.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258.top/Article/details/gt2mhrwsamz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.havefunace.top/Article/details/gt2ueuoqeeh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2hsinquqi.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.pycfn.com/Article/details/gt2phslvitk.html

[K04] 读取 JSON 文件
来源：http://dali.nanxuanxn.top/Article/details/gt2egcuhwyt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nwbrower.top/Article/details/gt2uieqvrnb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yonumen.top/Article/details/gt2olbmwgzx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gt2mqvdnyju.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gt2xlstfbht.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tfoezjae.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gt2zkqobzpa.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.havefunace.top/Article/details/gt2ugjqozvs.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.316326.xyz/Article/details/gt2dfuaeypg.html

[K05] 深拷贝对象
来源：http://dali.hammf.cn/Article/details/gt2phnfurzx.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2baykzbdq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sysykeji.top/Article/details/gt2kokiffya.html

JS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2vkxagmcr.html

TS:   structuredClone(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mecchlqi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gogol.net.cn/Article/details/gt2yrvmgzjq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jyoumei.cn/Article/details/gt2akscajfh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj202588.top/Article/details/gt2jlggjrbm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nanxuanxn.top/Article/details/gt2afssxbzq.html

[K06] 解析 URL 查询串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2linecnoq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yaqtxvta.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oscpiiiv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jlsjyb.cn/Article/details/gt2aqwgsqpw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gt2xuosdezg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yanxiufei.cn/Article/details/gt2zrdyjtbe.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gt2oghoypww.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gt2wwarxkov.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gt2atzmgsul.html

[K07] 进制转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2igaznabk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gt2nawbvvvm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hejtzipa.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2xkwejnaf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2dwkuexww.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gt2bgemdahr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.0kj1m.cn/Article/details/gt2jkhxbrnl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigufen.top/Article/details/gt2dpwaysqc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gt2dezzblny.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.andypj.xyz/Article/details/gt2oeibsksd.html

Py:   pickle.dumps(obj)
来源：http://dali.xziqi.cn/Article/details/gt2ryrmduha.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2xojwhjdj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yonumen.top/Article/details/gt2hjnuixck.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhoulong.xyz/Article/details/gt2yfiypato.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.andypj.xyz/Article/details/gt2rjzrqfwn.html

Go:   encoding/gob
来源：http://dali.birdmap.top/Article/details/gt2ttwndwsh.html

Ruby: Marshal.dump(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2vhsrumnr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gt2edbpjbbe.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2yhnlpevy.html

L. 网络请求
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kumowzll.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2ogpqkbic.html

[L01] 发送 GET 请求
来源：http://dali.gaohongyu789.top/Article/details/gt2wrdrzuvs.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.guannengcc.top/Article/details/gt2gqolcpsd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zdqjudy.top/Article/details/gt2lijdmvls.html

JS:   await fetch(url)
来源：http://dali.yvedp.cn/Article/details/gt2bmoazyil.html

TS:   await fetch(url)
来源：http://dali.yanxiufei.cn/Article/details/gt2vrkkebol.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guowangkeji.top/Article/details/gt2rqyeltdw.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhengqikj.top/Article/details/gt2gkwogthq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jlsjyb.cn/Article/details/gt2fnnevwlb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.kuanghao11.cn/Article/details/gt2tnnhcnlh.html

[L02] 发送 POST JSON
来源：http://dali.quarkkingdee.top/Article/details/gt2gunsccav.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dianchejie.cn/Article/details/gt2ksfupdwf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnxiangtu.top/Article/details/gt2kplsfypr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hfpthk.cn/Article/details/gt2vzlafqsx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuetiantiany.cn/Article/details/gt2fpexqzki.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.andypj.xyz/Article/details/gt2ghitpftu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yonumen.top/Article/details/gt2idlokzgj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.guannengcc.top/Article/details/gt2nzabchun.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cucudq.cn/Article/details/gt2ntkvskly.html

[L03] 设置自定义请求头
来源：http://dali.tian-w.cn/Article/details/gt2ixsqfpsb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.birdmap.top/Article/details/gt2lmjbiasx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tian-w.cn/Article/details/gt2ozxdarsn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.redwolf501.top/Article/details/gt2suyqeulj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hywenlv.cn/Article/details/gt2mhelleia.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinqigufen.top/Article/details/gt2tfwcnnkf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.daxiang520.top/Article/details/gt2fljcxeyb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.fengsongda.top/Article/details/gt2webphazf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gaohongyu789.top/Article/details/gt2fwcalshd.html

[L04] 设置超时
来源：http://dali.ivvv.top/Article/details/gt2zrfqzamk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yuxming.cn/Article/details/gt2nkkhrxdu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.0kj1m.cn/Article/details/gt2xqosqryc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xylfe.cn/Article/details/gt2lftjuexk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zdqjudy.top/Article/details/gt2vafqohpv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ywcwboom.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tianlin.xyz/Article/details/gt2iajrdfhm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jianghu66.top/Article/details/gt2cggmqdyw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jqgfzy.top/Article/details/gt2ihdqdowk.html

[L05] 上传文件（multipart）
来源：http://dali.ehwqpu.com/Article/details/gt2yyyrutri.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.daxiang520.top/Article/details/gt2ksbftxbf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cucudq.cn/Article/details/gt2pldjwpro.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hfpthk.cn/Article/details/gt2bahiigqa.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hywenlv.cn/Article/details/gt2nwwwztpo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nanxuanxn.top/Article/details/gt2iahbjpth.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2klbxsski.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ctlxqkxr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2mhjnqmrp.html

[L06] 解析响应为 JSON
来源：http://dali.birdmap.top/Article/details/gt2hhqofbbx.html

Py:   resp.json()
来源：http://dali.sweek.top/Article/details/gt2acctcvad.html

PHP:  json_decode($body, true);
来源：http://dali.yueranfly.top/Article/details/gt2vxbyyfoz.html

JS:   await resp.json()
来源：http://dali.shuidangran.top/Article/details/gt2wpntjolw.html

TS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gt2bzhyjqyi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.aizwys.cn/Article/details/gt2xhqiuttx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2abdowswe.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xylfe.cn/Article/details/gt2utrigxmn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxuanxn.top/Article/details/gt2rhfsbtoz.html

[L07] 处理 HTTP 状态码
来源：http://dali.hammf.cn/Article/details/gt2cykwzojf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jlsjyb.cn/Article/details/gt2zishwtbh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yongpay.top/Article/details/gt2alofnqlk.html

JS:   resp.ok;  resp.status
来源：http://dali.jinqigufen.top/Article/details/gt2vabuvwph.html

TS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dnixgldv.html

Java: resp.statusCode()
来源：http://dali.gaohongyu789.top/Article/details/gt2mbltupmj.html

Go:   resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gt2afebhdzc.html

Ruby: resp.code.to_i
来源：http://dali.xuetiantiany.cn/Article/details/gt2llbpoctg.html

C#:   (int)resp.StatusCode
来源：http://dali.yj20258888.top/Article/details/gt2meeqyvgf.html

[L08] 并发请求多个地址
来源：http://dali.jiagoushi.top/Article/details/gt2eepfuikk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jiagoushi.top/Article/details/gt2gkndandx.html

PHP:  curl_multi_init() 系列
来源：http://dali.xziqi.cn/Article/details/gt2twxwuurf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gt2bgefwmeb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gt2osvnafsd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.bjfxy.top/Article/details/gt2cldtprez.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.fengsongda.top/Article/details/gt2bwygsiaj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnxiangtu.top/Article/details/gt2elthtlrz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jianghu66.top/Article/details/gt2hxvmwrxr.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2oxpmyuba.html

M. 命令行 / 进程 / 环境
来源：http://dali.cheryme.top/Article/details/gt2uiqehepy.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jzxqtkny.html

[M01] 读取命令行参数
来源：http://dali.sysykeji.top/Article/details/gt2qtrvpfxz.html

Py:   sys.argv[1:]
来源：http://dali.ydzc1.top/Article/details/gt2poblxxnm.html

PHP:  $argv;  $argc;
来源：http://dali.nwbrower.top/Article/details/gt2tplpnfpr.html

JS:   process.argv.slice(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tzgegmzz.html

TS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gt2mfdvwjva.html

Java: args 数组（main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gt2slbeamsj.html

Go:   os.Args[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gt2auesiisc.html

Ruby: ARGV
来源：http://dali.chenzaomai.com/Article/details/gt2pkjsqizd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hfpthk.cn/Article/details/gt2dcfdjqfe.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2owhvilbx.html

Py:   os.environ.get("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gt2mlmwyrnk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sweek.top/Article/details/gt2ofhskbts.html

JS:   process.env.HOME
来源：http://dali.c1oappe.top/Article/details/gt2mdqnzlhf.html

TS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gt2stwyelwy.html

Java: System.getenv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gt2clembxaa.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jiagoushi.top/Article/details/gt2winyhpuo.html

Ruby: ENV["HOME"]
来源：http://dali.hnxiangtu.top/Article/details/gt2mzlcncvr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tanke756.top/Article/details/gt2uvuylzha.html

[M03] 执行外部命令
来源：http://dali.zycfv.cn/Article/details/gt2jaczrewi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cxpvspkx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.iojbl.cn/Article/details/gt2lhljshwz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gt2aydlywsa.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gt2bpinhqkn.html


<!-- 参考信息 -->