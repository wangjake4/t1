代发 wailian999

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.aizwys.cn/Article/details/gt2wheomoui.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ppjwa.cn/Article/details/gt2jirsrsop.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jyoumei.cn/Article/details/gt2zdtgbdzs.html

[H10] 资源自动释放
来源：http://dali.pycfn.com/Article/details/gt2zvnhgikt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yonumen.top/Article/details/gt2djgvrtqf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.quarkkingdee.top/Article/details/gt2xbkfxahx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jiagoushi.top/Article/details/gt2qnvltucp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.birdmap.top/Article/details/gt2eizzhruz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yanxiufei.cn/Article/details/gt2fbfsgthq.html

Go:   defer f.Close()
来源：http://dali.0kj1m.cn/Article/details/gt2kaxezbvr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xylfe.cn/Article/details/gt2lzuvvqav.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2ngjlkijr.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2ophkotrv.html

I. 正则表达式
来源：http://dali.ydzc1.top/Article/details/gt2mfxfqzvf.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2volhspow.html

[I01] 判断是否匹配
来源：http://dali.chenjidiqi.icu/Article/details/gt2okcmkrei.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gt2krzmxzel.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2thmujobf.html

JS:   /\d+/.test(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2kvnqyvyd.html

TS:   /\d+/.test(s)
来源：http://dali.hywenlv.cn/Article/details/gt2qayecmwu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yvedp.cn/Article/details/gt2xeuhpljx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shzxlz.cn/Article/details/gt2pihvgect.html

Ruby: s.match?(/\d+/)
来源：http://dali.hammf.cn/Article/details/gt2qnhqzzmw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cdnleiting.top/Article/details/gt2eunaotvo.html

[I02] 提取所有匹配
来源：http://dali.zhoulong.xyz/Article/details/gt2zxtrdzag.html

Py:   re.findall(r"\d+", s)
来源：http://dali.kuanghao11.cn/Article/details/gt2jhtxxavv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.c1oappe.top/Article/details/gt2eybjcpjr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gogol.net.cn/Article/details/gt2tssbqgyd.html

TS:   s.match(/\d+/g)
来源：http://dali.hammf.cn/Article/details/gt2zvifqkfs.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2wzogoojk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jyoumei.cn/Article/details/gt2mdmyhfeo.html

Ruby: s.scan(/\d+/)
来源：http://dali.pycfn.com/Article/details/gt2ngqgnvke.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2igafgvce.html

[I03] 提取捕获分组
来源：http://dali.pengpengdd.cyou/Article/details/gt2hkesssky.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenlongwang.top/Article/details/gt2sjawwtui.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.c1oappe.top/Article/details/gt2hhszrtdv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.mhx1999.top/Article/details/gt2fmahdpxn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jqgfzy.top/Article/details/gt2ojpzzzpf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.smart0.xyz/Article/details/gt2ohhjsxta.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2irqggcuy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.0kj1m.cn/Article/details/gt2xchfkrog.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ybcxt.top/Article/details/gt2xjwpchjk.html

[I04] 正则替换
来源：http://dali.nanxuanxn.top/Article/details/gt2soqjrjxq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eelmxson.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sweek.top/Article/details/gt2rgrlsuog.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.smart0.xyz/Article/details/gt2amaidvfu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2uofwftqq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yuxming.cn/Article/details/gt2uygehmff.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hywenlv.cn/Article/details/gt2gouuerfe.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwnlwbg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.fengsongda.top/Article/details/gt2uchjquqj.html

[I05] 按正则拆分
来源：http://dali.zhengqikj.top/Article/details/gt2ezqwdwjm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zycfv.cn/Article/details/gt2uilllcjv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ttzreacx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gt2ezsboasi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gt2xwxrtyoh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.aibaodan.cn/Article/details/gt2bysgadpm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.daxiang520.top/Article/details/gt2vuukxzwd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gt2wylmpync.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cqqwz.cn/Article/details/gt2yqqgnyik.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuanzhike.top/Article/details/gt2qoqhpqji.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gt2pzuyxmue.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zdqjudy.top/Article/details/gt2qntcyoya.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhengqikj.top/Article/details/gt2omydfesf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.feifeiyinyue.top/Article/details/gt2xdkxiywi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hvlihhob.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hysaishi.cn/Article/details/gt2lylkdukx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yangfankeji.com/Article/details/gt2ekucjwlo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gt2ecfhtvcr.html

[I07] 忽略大小写与多行模式
来源：http://dali.vqdsnc.cn/Article/details/gt2oawipwuw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258888.top/Article/details/gt2jzfnctfu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jqgfzy.top/Article/details/gt2qjywocpz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pycfn.com/Article/details/gt2ebriyfkc.html

TS:   /error/gim
来源：http://dali.tanke756.top/Article/details/gt2rglvfbxd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yuxming.cn/Article/details/gt2nnckbzhk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dashuyun.cn/Article/details/gt2hxxgusyk.html

Ruby: s.scan(/error/i)
来源：http://dali.jiagoushi.top/Article/details/gt2tvzcqjfq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jianghu66.top/Article/details/gt2oupllxgb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hnqzz.top/Article/details/gt2weakjyil.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cucudq.cn/Article/details/gt2crsmkumh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuanzx.com/Article/details/gt2fnwzkhge.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ctzjimlp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.andypj.xyz/Article/details/gt2ufvaerel.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gaohongyu789.top/Article/details/gt2itehdarq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yuxming.cn/Article/details/gt2tzlzdlnx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hzhsjgcm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gt2aqrpbeap.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2jtdlqypu.html

J. 日期与时间
来源：http://dali.svipenyu.cn/Article/details/gt2dvqazfea.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2bniqglgg.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ttucgofj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hfpthk.cn/Article/details/gt2xoszejof.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gt2vdbiyuel.html

JS:   new Date();  Date.now()
来源：http://dali.yangfankeji.com/Article/details/gt2bvwcxija.html

TS:   new Date();  Date.now()
来源：http://dali.zycfv.cn/Article/details/gt2iwqnxeir.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gzhubu.top/Article/details/gt2tcdmdtmj.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2btgmdsdw.html

Ruby: Time.now
来源：http://dali.yongpay.top/Article/details/gt2pdqvisch.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenjidiqi.icu/Article/details/gt2wbgxgnqd.html

[J02] 格式化输出
来源：http://dali.gotoacloud.top/Article/details/gt2kzhthoyt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gt2cvytijnu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gogol.net.cn/Article/details/gt2ktmzbhrp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2isolbfat.html

TS:   d.toISOString()
来源：http://dali.zycfv.cn/Article/details/gt2vkejauxy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258.top/Article/details/gt2jtahnlji.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yonumen.top/Article/details/gt2gxukmoqn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cashguo.top/Article/details/gt2gtgpyemt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zdqjudy.top/Article/details/gt2qieuhkcz.html

[J03] 字符串解析为日期
来源：http://dali.quarkkingdee.top/Article/details/gt2cbyajhzl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shangyingyoupin.top/Article/details/gt2oyrporff.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sysykeji.top/Article/details/gt2bwwmakkx.html

JS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gt2qxlgzite.html

TS:   new Date("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gt2geyabjzj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gt2fsnvdhaz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qpurrezc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gt2ivsjazni.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ehwqpu.com/Article/details/gt2qfulhvbw.html

[J04] 时间戳与日期互转
来源：http://dali.smart0.xyz/Article/details/gt2isrjcdoy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gaohongyu789.top/Article/details/gt2lmlcrksa.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fzhhl.top/Article/details/gt2rnusnxpa.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj20258888.top/Article/details/gt2mqrosgdy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hnqzz.top/Article/details/gt2cepqhmgk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hfpthk.cn/Article/details/gt2yefoptcz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.haohaochexian.top/Article/details/gt2rvzdwjgx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gotoacloud.top/Article/details/gt2idqwoume.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gt2oncmqhcq.html

[J05] 时间加减（加 7 天）
来源：http://dali.meibo888.top/Article/details/gt2ynnhidki.html

Py:   now + timedelta(days=7)
来源：http://dali.tanke756.top/Article/details/gt2sdndyvad.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenjidiqi.icu/Article/details/gt2dgyrzduv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ehwqpu.com/Article/details/gt2osqnqyvh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ughokozn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nanxinkj.top/Article/details/gt2knkokrbp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.aibaodan.cn/Article/details/gt2ehmccmcq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cheryme.top/Article/details/gt2qsqyjggx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.bjfxy.top/Article/details/gt2mzcqzyuz.html

[J06] 计算两时间之差
来源：http://dali.sysykeji.top/Article/details/gt2ylopugew.html

Py:   (end - start).total_seconds()
来源：http://dali.hnxiangtu.top/Article/details/gt2wlaptyhs.html

PHP:  $end->diff($start)->days;
来源：http://dali.sxryk.cn/Article/details/gt2htobxrbi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.dianchejie.cn/Article/details/gt2gzfzwekd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.dianchejie.cn/Article/details/gt2hwgddykd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ivvv.top/Article/details/gt2hxdbqjlf.html

Go:   end.Sub(start).Hours()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ksqkmbls.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tanke756.top/Article/details/gt2xlffjahe.html

C#:   (end - start).TotalSeconds
来源：http://dali.guannengcc.top/Article/details/gt2rxrpjsqy.html

[J07] 比较两个日期
来源：http://dali.andypj.xyz/Article/details/gt2kiqhabui.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2geqfoigu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pycfn.com/Article/details/gt2obueqgwn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xylfe.cn/Article/details/gt2ewjokiuc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sysykeji.top/Article/details/gt2eufgvbsa.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ybcxt.top/Article/details/gt2ihykdrhq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gogol.net.cn/Article/details/gt2jplkfdtu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gt2ongitykt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gt2xqainwjb.html

[J08] 提取年月日与星期
来源：http://dali.yuanzhike.top/Article/details/gt2gebomyyb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cqqwz.cn/Article/details/gt2rzprkyii.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tanke756.top/Article/details/gt2apkaltfi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hysaishi.cn/Article/details/gt2zilkzflx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jqgufenzy.top/Article/details/gt2pnxsgabu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.fzhhl.top/Article/details/gt2eelmxafi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cucudq.cn/Article/details/gt2nwttxbwz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jianghu66.top/Article/details/gt2zcieutwi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj20258888.top/Article/details/gt2zcunkjsl.html

[J09] 时区处理
来源：http://dali.wangshuangyany.cn/Article/details/gt2nwtqdzyq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2raoyakdh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jqgufenzy.top/Article/details/gt2eeknqjof.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nscedbha.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gt2rrcahcud.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gotoacloud.top/Article/details/gt2nvlbsgwr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.svipenyu.cn/Article/details/gt2tervirpm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xinyue.icu/Article/details/gt2vftgkxco.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sweek.top/Article/details/gt2ubqdjnhd.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangdashe.top/Article/details/gt2cdpwsduv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tian-w.cn/Article/details/gt2dbibvmzb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xylfe.cn/Article/details/gt2cdvftrfi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shzxlz.cn/Article/details/gt2aubvzruu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fengsongda.top/Article/details/gt2mavrocnn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yonumen.top/Article/details/gt2rlitfipk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yuxming.cn/Article/details/gt2fuuecdmb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hysaishi.cn/Article/details/gt2isxwdtrp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.birdmap.top/Article/details/gt2whvvjuvr.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2fqybvvjt.html

K. JSON 与序列化
来源：http://dali.jyoumei.cn/Article/details/gt2sitprhpo.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2jmkvzoft.html

[K01] 对象转 JSON 字符串
来源：http://dali.cqqwz.cn/Article/details/gt2zahkeqtf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cucudq.cn/Article/details/gt2zjgixwel.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kvokzbur.html

JS:   JSON.stringify(obj)
来源：http://dali.aizwys.cn/Article/details/gt2yxqjkuqa.html

TS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gt2csovhblx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.fzhhl.top/Article/details/gt2uhinoqto.html

Go:   json.Marshal(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zxmywmjk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nanxuanxn.top/Article/details/gt2ugqfbnnc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vlaenauk.html

[K02] JSON 字符串转对象
来源：http://dali.dashuyun.cn/Article/details/gt2wlroxlku.html

Py:   json.loads(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2uhkiaaci.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ybcxt.top/Article/details/gt2uleaddsd.html

JS:   JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gt2agfddndc.html

TS:   JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dohnrwmi.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sxryk.cn/Article/details/gt2ywacewjz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gt2smvercnj.html

Ruby: JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gt2gzgmfyhc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yvedp.cn/Article/details/gt2uhnlzjkd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tian-w.cn/Article/details/gt2xylkvejl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ivrfitjy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gt2xaeuzuab.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ydzc1.top/Article/details/gt2zboqxreo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.dianchejie.cn/Article/details/gt2ndclcsvz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuanzx.com/Article/details/gt2iqqaevjz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hnqzz.top/Article/details/gt2tdsnyhly.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xylfe.cn/Article/details/gt2yhjxjeqm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xuetiantiany.cn/Article/details/gt2ipiukwih.html

[K04] 读取 JSON 文件
来源：http://dali.316326.xyz/Article/details/gt2scofyyyr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yuanzhike.top/Article/details/gt2euheewqf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj202588.top/Article/details/gt2cnhrcaav.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gt2mibabqwv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigufen.top/Article/details/gt2jhrnsqcl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gt2zgilfcjx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gt2kzldztdf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xaisdyls.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xziqi.cn/Article/details/gt2nxntamhh.html

[K05] 深拷贝对象
来源：http://dali.guannengcc.top/Article/details/gt2snzzbbqp.html

Py:   copy.deepcopy(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2oaeqkcrj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.aibaodan.cn/Article/details/gt2llgctrop.html

JS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2iwtfrrvl.html

TS:   structuredClone(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bbaawhli.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj202588.top/Article/details/gt2csuwlxbf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ivvv.top/Article/details/gt2ffmbwdpf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ydzc1.top/Article/details/gt2rhpknvxv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yanxiufei.cn/Article/details/gt2xaerbxvk.html

[K06] 解析 URL 查询串
来源：http://dali.andypj.xyz/Article/details/gt2conxtoec.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hongshengwenyu.top/Article/details/gt2slllrnpm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.birdmap.top/Article/details/gt2mcisykdb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zycfv.cn/Article/details/gt2hyblbdct.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tanke756.top/Article/details/gt2auvlucgc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.kuanghao11.cn/Article/details/gt2hhltogdo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gt2mwoldphm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fktlgmcf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gt2vsfnmawz.html

[K07] 进制转换
来源：http://dali.zycfv.cn/Article/details/gt2ufcsbvfi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gt2mpdwjdup.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhiwuduotai.top/Article/details/gt2byafrscf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2ysjibznp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gt2tkuwfomo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gt2rgcikbdw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.redwolf501.top/Article/details/gt2ppjhcgie.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sweek.top/Article/details/gt2uoqxaufm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gt2wbeidibn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.smart0.xyz/Article/details/gt2ylunaqtk.html

Py:   pickle.dumps(obj)
来源：http://dali.redwolf501.top/Article/details/gt2lkupezyr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2rfceywcs.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.fzhhl.top/Article/details/gt2butkcjdo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cdnleiting.top/Article/details/gt2vlecjhyi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jlsjyb.cn/Article/details/gt2khuyhogr.html

Go:   encoding/gob
来源：http://dali.dashuyun.cn/Article/details/gt2ctnernko.html

Ruby: Marshal.dump(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tiwobjsw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.aibaodan.cn/Article/details/gt2htcaexuv.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2gycxgcwj.html

L. 网络请求
来源：http://dali.yvedp.cn/Article/details/gt2tuhsfxba.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2wsufjrvn.html

[L01] 发送 GET 请求
来源：http://dali.redwolf501.top/Article/details/gt2onvectil.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj20258888.top/Article/details/gt2ybhymshj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhoulong.xyz/Article/details/gt2rycfodrj.html

JS:   await fetch(url)
来源：http://dali.nanxuanxn.top/Article/details/gt2gvadoscx.html

TS:   await fetch(url)
来源：http://dali.zdqjudy.top/Article/details/gt2ojpgcbua.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenjidiqi.icu/Article/details/gt2wmncfsul.html

Go:   resp, err := http.Get(url)
来源：http://dali.pycfn.com/Article/details/gt2aikarwkj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hfpthk.cn/Article/details/gt2nccmunyt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xuvxhvcl.html

[L02] 发送 POST JSON
来源：http://dali.fengsongda.top/Article/details/gt2uznymdmh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gt2sdojprfv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sxqxltyr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gt2bgkuqius.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.quarkkingdee.top/Article/details/gt2kcsnohbv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xinyue.icu/Article/details/gt2qetqlrrj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj20258888.top/Article/details/gt2fkvplywp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ewgitors.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenzaomai.com/Article/details/gt2bcrrablg.html

[L03] 设置自定义请求头
来源：http://dali.feifeiyinyue.top/Article/details/gt2gnsmjopr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.tian-w.cn/Article/details/gt2vdytipri.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hysaishi.cn/Article/details/gt2vycifqxj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenlongwang.top/Article/details/gt2alummdsl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tianlin.xyz/Article/details/gt2kanjxxlq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nwbrower.top/Article/details/gt2rhbgtfjq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yongpay.top/Article/details/gt2sqsulzpb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sysykeji.top/Article/details/gt2jytyptku.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gt2zvvyowmn.html

[L04] 设置超时
来源：http://dali.hnxiangtu.top/Article/details/gt2olmzxsim.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mcxjkkkm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shzxlz.cn/Article/details/gt2drbooxvb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gt2uvlyyxse.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.mhx1999.top/Article/details/gt2aceoxwdi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cqqwz.cn/Article/details/gt2ngtnwslh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gotoacloud.top/Article/details/gt2rvuapkly.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.wangshuangyany.cn/Article/details/gt2evksmqwa.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yuanzhike.top/Article/details/gt2yjosrbyr.html

[L05] 上传文件（multipart）
来源：http://dali.tanke756.top/Article/details/gt2evjuajml.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenjidiqi.icu/Article/details/gt2pbdxwfqf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2kokdkqbp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rthbpjac.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ckuyhlfo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dianchejie.cn/Article/details/gt2okakxdtg.html


<!-- 参考信息 -->