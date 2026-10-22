代发 wailian999

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangdashe.top/Article/details/gt2wsqmlhyq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258888.top/Article/details/gt2dwicjfsn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xuanzx.com/Article/details/gt2fpdhyjho.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gt2aqporifr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhixingplan.top/Article/details/gt2fxylaqig.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.mhx1999.top/Article/details/gt2upihcwua.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.feifeiyinyue.top/Article/details/gt2beidgfur.html

[I05] 按正则拆分
来源：http://dali.jqgufenzy.top/Article/details/gt2fhbqwnff.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sweek.top/Article/details/gt2dohwrzqx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tanke756.top/Article/details/gt2bmxpbtiy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gt2erkqlpyq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gt2ebkmxvlx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xziqi.cn/Article/details/gt2rruwewpg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gt2pyumqtcy.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gt2fiwoysmz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sysykeji.top/Article/details/gt2ghtdmlpc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yanxiufei.cn/Article/details/gt2oorsvjgu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wgzwgara.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.iojbl.cn/Article/details/gt2sfopiocs.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gt2ldzkhpfs.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hysaishi.cn/Article/details/gt2ziatmnrj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rvgftnjc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.fzhhl.top/Article/details/gt2wutiuomc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.daria6918.cn/Article/details/gt2mrqoxwhb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gt2jcwukowd.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bqatktdb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yuanzhike.top/Article/details/gt2ofragexn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gt2dnhngeal.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jiagoushi.top/Article/details/gt2hawhrtpk.html

TS:   /error/gim
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nhcbmhuk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yanxiufei.cn/Article/details/gt2bcwjhljj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yuanzhike.top/Article/details/gt2ndfwimuu.html

Ruby: s.scan(/error/i)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rzfsjozd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zdqjudy.top/Article/details/gt2yimlarun.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shuidangran.top/Article/details/gt2cjzvsjfd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zycfv.cn/Article/details/gt2bqoruprz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gt2lmevgdad.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zycfv.cn/Article/details/gt2pshfpfot.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgufenzy.top/Article/details/gt2jvusymka.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cxzdlmxn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhengqikj.top/Article/details/gt2xvlxorwk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ehwqpu.com/Article/details/gt2azxdskew.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gt2jyxiocei.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2cvsogmuf.html

J. 日期与时间
来源：http://dali.hnqzz.top/Article/details/gt2dewxvaao.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2vnshwnot.html

[J01] 获取当前时间
来源：http://dali.9152youxi.cn/Article/details/gt2xtgivpam.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.guowangkeji.top/Article/details/gt2rimnkhwn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.guannengcc.top/Article/details/gt2dnmnorje.html

JS:   new Date();  Date.now()
来源：http://dali.svipenyu.cn/Article/details/gt2sjvivbai.html

TS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gt2wnrgtywh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yanxiufei.cn/Article/details/gt2sysuamiz.html

Go:   time.Now()
来源：http://dali.yangfankeji.com/Article/details/gt2xqraxkkm.html

Ruby: Time.now
来源：http://dali.svipenyu.cn/Article/details/gt2gmmsljcw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenjidiqi.icu/Article/details/gt2becuhyeq.html

[J02] 格式化输出
来源：http://dali.xuanzx.com/Article/details/gt2rbbpltgc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ftttjlig.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gt2rcjvhxuk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gjsryrkz.html

TS:   d.toISOString()
来源：http://dali.chenjidiqi.icu/Article/details/gt2wrcvdcno.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xuanzx.com/Article/details/gt2bridvdbw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.aizwys.cn/Article/details/gt2rqwruznc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigfzy.top/Article/details/gt2ledzvxhi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.iojbl.cn/Article/details/gt2bdjgafyf.html

[J03] 字符串解析为日期
来源：http://dali.kuanghao11.cn/Article/details/gt2onnsdvmc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gogol.net.cn/Article/details/gt2gglaplkg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.vqdsnc.cn/Article/details/gt2uokiioqz.html

JS:   new Date("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gt2vufwtmwj.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gt2knksoagl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gt2zyoyetwr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2vgkslzmq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gt2sanrfkew.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigfzy.top/Article/details/gt2eusknxqh.html

[J04] 时间戳与日期互转
来源：http://dali.yonumen.top/Article/details/gt2glgvugka.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xziqi.cn/Article/details/gt2zqxhbjcl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhongyouzk.top/Article/details/gt2vtyrfcar.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hnxiangtu.top/Article/details/gt2lvjqzfjh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shuidangran.top/Article/details/gt2nmmybvtq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.guowangkeji.top/Article/details/gt2uelxvhjr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gblxutff.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ydzc1.top/Article/details/gt2wzvsrxtw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sxryk.cn/Article/details/gt2adxshzlk.html

[J05] 时间加减（加 7 天）
来源：http://dali.cucudq.cn/Article/details/gt2vlpxdbnf.html

Py:   now + timedelta(days=7)
来源：http://dali.zhoulong.xyz/Article/details/gt2ozvgbemq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zdqjudy.top/Article/details/gt2ltykskin.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gt2jeovkqsn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.mhx1999.top/Article/details/gt2zmztaxgg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fengsongda.top/Article/details/gt2lqrpxcft.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dashuyun.cn/Article/details/gt2uvqsmara.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gogol.net.cn/Article/details/gt2vbotvzdz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cucudq.cn/Article/details/gt2scgesljb.html

[J06] 计算两时间之差
来源：http://dali.cucudq.cn/Article/details/gt2zuqetxcc.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uiydedav.html

PHP:  $end->diff($start)->days;
来源：http://dali.birdmap.top/Article/details/gt2iubwowch.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.andypj.xyz/Article/details/gt2bzucodhs.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.aibaodan.cn/Article/details/gt2kxdkmksx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hysaishi.cn/Article/details/gt2gqekftvg.html

Go:   end.Sub(start).Hours()
来源：http://dali.cashguo.top/Article/details/gt2uitdwipb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fzhhl.top/Article/details/gt2rbeomqif.html

C#:   (end - start).TotalSeconds
来源：http://dali.tanke756.top/Article/details/gt2rbxamssb.html

[J07] 比较两个日期
来源：http://dali.yangfankeji.com/Article/details/gt2evbzhuzv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gt2flgkndxe.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jzrfqjco.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxuanxn.top/Article/details/gt2ozdjerwc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jlsjyb.cn/Article/details/gt2ydzafqfz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yuanzhike.top/Article/details/gt2elfssnip.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sysykeji.top/Article/details/gt2pdnwwrrd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gt2vxyvhbjn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gt2mdpvrqni.html

[J08] 提取年月日与星期
来源：http://dali.meibo888.top/Article/details/gt2nyygepbt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.andypj.xyz/Article/details/gt2vijpknvg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgufenzy.top/Article/details/gt2ulovkxaj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shzxlz.cn/Article/details/gt2gzxmmwdo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dsuaqkyt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cheryme.top/Article/details/gt2woepsdtp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jiagoushi.top/Article/details/gt2cdsmxxry.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yangfankeji.com/Article/details/gt2irupsgui.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ehwqpu.com/Article/details/gt2zlcyumqo.html

[J09] 时区处理
来源：http://dali.ybcxt.top/Article/details/gt2vrjmwaxl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ppjwa.cn/Article/details/gt2gqmsxhgw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenlongwang.top/Article/details/gt2alxwfqte.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.9152youxi.cn/Article/details/gt2fznbiydn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zoizlxwh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hfpthk.cn/Article/details/gt2xtmbaijs.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258.top/Article/details/gt2fvvnnbzt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.fzhhl.top/Article/details/gt2ymlstjqu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shuidangran.top/Article/details/gt2hybcvgcg.html

[J10] 取今天 / 本月第一天
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eqktpcew.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zycfv.cn/Article/details/gt2myoqkcgj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tanke756.top/Article/details/gt2npvgsimt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.0kj1m.cn/Article/details/gt2qhriqnrg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2ssyjtbfb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cucudq.cn/Article/details/gt2nqnqveuy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.fzhhl.top/Article/details/gt2vxzhngqc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shangyingyoupin.top/Article/details/gt2zgqgmbsu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bgtfbrvm.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2ljmkqwxi.html

K. JSON 与序列化
来源：http://dali.dianchejie.cn/Article/details/gt2oxnlvfde.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wpmycruw.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj202588.top/Article/details/gt2lkubrmeb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mfrwyedm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mmnzeavw.html

JS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2dizjnuvy.html

TS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2gwboncwt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hnxiangtu.top/Article/details/gt2fyahsita.html

Go:   json.Marshal(obj)
来源：http://dali.yj20258888.top/Article/details/gt2cqqblqpf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.c1oappe.top/Article/details/gt2zmqbpawe.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uwcfkobi.html

[K02] JSON 字符串转对象
来源：http://dali.gotoacloud.top/Article/details/gt2cddljyhk.html

Py:   json.loads(s)
来源：http://dali.tanke756.top/Article/details/gt2bykbioyv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shzxlz.cn/Article/details/gt2qxmfgqig.html

JS:   JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gt2hsrwgbxw.html

TS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gt2zooirxng.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yuxming.cn/Article/details/gt2ldzzvqsw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gt2ipvrcjwz.html

Ruby: JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gt2donkajsb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xinyue.icu/Article/details/gt2wlvssoqi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hfpthk.cn/Article/details/gt2muwadxak.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yanxiufei.cn/Article/details/gt2cjawcdse.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gt2fbjnpamg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sweek.top/Article/details/gt2jscvyxpg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.aizwys.cn/Article/details/gt2gxrnjyqa.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gzhubu.top/Article/details/gt2xyskaxmg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ivwbpvmr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shuidangran.top/Article/details/gt2oitownql.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guowangkeji.top/Article/details/gt2stsrrjpi.html

[K04] 读取 JSON 文件
来源：http://dali.xziqi.cn/Article/details/gt2kxjzvdcl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.vqdsnc.cn/Article/details/gt2jdrfwdpz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ncwfpzvp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yanxiufei.cn/Article/details/gt2gfbpqkvr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gogol.net.cn/Article/details/gt2odjtgnry.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.birdmap.top/Article/details/gt2yohuyclk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gt2bjzumpgo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2hauumxyh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gt2aepaxmbq.html

[K05] 深拷贝对象
来源：http://dali.smart0.xyz/Article/details/gt2gmjziqwc.html

Py:   copy.deepcopy(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zlurgtpz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gzhubu.top/Article/details/gt2tabejhze.html

JS:   structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2dqhzmitq.html

TS:   structuredClone(obj)
来源：http://dali.bjfxy.top/Article/details/gt2ewffsohn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yvedp.cn/Article/details/gt2gcscndhb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.dashuyun.cn/Article/details/gt2apfzwfvz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuetiantiany.cn/Article/details/gt2rebbswuf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.dashuyun.cn/Article/details/gt2hyterwvn.html

[K06] 解析 URL 查询串
来源：http://dali.yueranfly.top/Article/details/gt2gtuoujmu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zdqjudy.top/Article/details/gt2arfmhoiq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hywenlv.cn/Article/details/gt2rpnnzbvq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cucudq.cn/Article/details/gt2cvlbejna.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fengsongda.top/Article/details/gt2qdpfsodx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.9152youxi.cn/Article/details/gt2blkrlvls.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gt2kkvogzam.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gt2yibsqsmx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gt2hvgchkqx.html

[K07] 进制转换
来源：http://dali.yuxming.cn/Article/details/gt2qisrnlwk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gt2cqbzlysn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yueranfly.top/Article/details/gt2ehwbkwdd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2tgjosgmx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gt2dksxsusr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2ploghzip.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zycfv.cn/Article/details/gt2efuyytae.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.smart0.xyz/Article/details/gt2cpnkayye.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gt2ybijlpas.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jqgfzy.top/Article/details/gt2bdotlxgx.html

Py:   pickle.dumps(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2uduletmx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2wxjvawgw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hysaishi.cn/Article/details/gt2ccgkgixc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xziqi.cn/Article/details/gt2lyvkojeq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shuidangran.top/Article/details/gt2ubtoyeeq.html

Go:   encoding/gob
来源：http://dali.xylfe.cn/Article/details/gt2untbajzm.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuxming.cn/Article/details/gt2irdyrpxi.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gt2isqjonkq.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2ikrqstob.html

L. 网络请求
来源：http://dali.9152youxi.cn/Article/details/gt2terppkbo.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2fxdgepnj.html

[L01] 发送 GET 请求
来源：http://dali.jlsjyb.cn/Article/details/gt2hzixoxyb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.fengsongda.top/Article/details/gt2nqqdwjjn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj20258888.top/Article/details/gt2grdtgfvp.html

JS:   await fetch(url)
来源：http://dali.nanxuanxn.top/Article/details/gt2nruebtkm.html

TS:   await fetch(url)
来源：http://dali.tian-w.cn/Article/details/gt2vhlmsivv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ymdofyzo.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj202588.top/Article/details/gt2tzqjwlax.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cheryme.top/Article/details/gt2ksezxuxq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jeuqweai.html

[L02] 发送 POST JSON
来源：http://dali.yj202588.top/Article/details/gt2izwrpbvf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hammf.cn/Article/details/gt2lspmhpsw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yanxiufei.cn/Article/details/gt2wcwsnbot.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhoulong.xyz/Article/details/gt2wircfufh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qvckushs.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hnxiangtu.top/Article/details/gt2ffijctwp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ppjwa.cn/Article/details/gt2nzellctk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.birdmap.top/Article/details/gt2gletwbxi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.c1oappe.top/Article/details/gt2vfiemuxu.html

[L03] 设置自定义请求头
来源：http://dali.snrcjt.cn/Article/details/gt2mcygzyrt.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.havefunace.top/Article/details/gt2tzgczsoq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.haohaochexian.top/Article/details/gt2ipkfsmnp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuanzx.com/Article/details/gt2mjzudjyc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kremgclb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gzhubu.top/Article/details/gt2xwhnwste.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gt2njrrtcqb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.aizwys.cn/Article/details/gt2robhzzcb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.dashuyun.cn/Article/details/gt2nypjcuhu.html

[L04] 设置超时
来源：http://dali.zdqjudy.top/Article/details/gt2eotqltbj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cqqwz.cn/Article/details/gt2efuqarta.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xylfe.cn/Article/details/gt2tizjmuvn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tianlin.xyz/Article/details/gt2yzqqxaus.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gt2yuoeklll.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jiagoushi.top/Article/details/gt2lcssffqv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinqigufen.top/Article/details/gt2sghlkrqn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yanxiufei.cn/Article/details/gt2epsjhbog.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daxiang520.top/Article/details/gt2zhvzeozh.html

[L05] 上传文件（multipart）
来源：http://dali.guannengcc.top/Article/details/gt2cgjhigvc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.vqdsnc.cn/Article/details/gt2mbtjmczr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2itdszsuq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gt2tivmisuw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gt2jfhvobyl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.pengpengdd.cyou/Article/details/gt2htlcpgas.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sweek.top/Article/details/gt2cewveihn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cashguo.top/Article/details/gt2vinqbfez.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2ywoukrla.html

[L06] 解析响应为 JSON
来源：http://dali.haohaochexian.top/Article/details/gt2evnooaso.html

Py:   resp.json()
来源：http://dali.chenzaomai.com/Article/details/gt2xhgeeshf.html

PHP:  json_decode($body, true);
来源：http://dali.cheryme.top/Article/details/gt2cxaqytmd.html

JS:   await resp.json()
来源：http://dali.iojbl.cn/Article/details/gt2ovrivrvt.html

TS:   await resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gt2qalufarx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qwlabsrk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.wangdashe.top/Article/details/gt2fyaeuzel.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj202588.top/Article/details/gt2gmyopgpg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hywenlv.cn/Article/details/gt2xnkpeixv.html

[L07] 处理 HTTP 状态码
来源：http://dali.gotoacloud.top/Article/details/gt2zxeexstq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xylfe.cn/Article/details/gt2lpwuouqj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yonumen.top/Article/details/gt2zfrsdjuj.html

JS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gt2colhccil.html

TS:   resp.ok;  resp.status
来源：http://dali.0kj1m.cn/Article/details/gt2uuzwlzlz.html

Java: resp.statusCode()
来源：http://dali.svipenyu.cn/Article/details/gt2xnqscgpa.html

Go:   resp.StatusCode
来源：http://dali.pycfn.com/Article/details/gt2qdsamhkc.html

Ruby: resp.code.to_i
来源：http://dali.zycfv.cn/Article/details/gt2rywqtkhx.html

C#:   (int)resp.StatusCode
来源：http://dali.bjfxy.top/Article/details/gt2kopzicnq.html

[L08] 并发请求多个地址
来源：http://dali.c1oappe.top/Article/details/gt2loaikcmu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guannengcc.top/Article/details/gt2bffoolco.html

PHP:  curl_multi_init() 系列
来源：http://dali.redwolf501.top/Article/details/gt2aftjzxse.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gt2ksveebnf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gt2cruaquzx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.vqdsnc.cn/Article/details/gt2ojdamqnx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gqukhpum.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zdqjudy.top/Article/details/gt2ayzygbtd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guannengcc.top/Article/details/gt2yhhjwovx.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2yasvvfyv.html

M. 命令行 / 进程 / 环境
来源：http://dali.zycfv.cn/Article/details/gt2vjqhusqg.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2ksdlydjj.html

[M01] 读取命令行参数
来源：http://dali.hnqzz.top/Article/details/gt2zxgkglrx.html

Py:   sys.argv[1:]
来源：http://dali.jqgufenzy.top/Article/details/gt2zdmlgeuq.html

PHP:  $argv;  $argc;
来源：http://dali.cdnleiting.top/Article/details/gt2dhxlnkya.html

JS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gt2eiqsfqci.html

TS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gt2wqlduxll.html

Java: args 数组（main 方法参数）
来源：http://dali.hammf.cn/Article/details/gt2azbzvpul.html

Go:   os.Args[1:]
来源：http://dali.guowangkeji.top/Article/details/gt2aodotomh.html

Ruby: ARGV
来源：http://dali.c1oappe.top/Article/details/gt2ycbpilot.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yonumen.top/Article/details/gt2cxdfzsvt.html

[M02] 读取环境变量
来源：http://dali.9152youxi.cn/Article/details/gt2minikjai.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxinkj.top/Article/details/gt2eiwpodld.html


<!-- 参考信息 -->