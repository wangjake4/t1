代发 wailian999

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.quarkkingdee.top/Article/details/gt2yzkpcftt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.quarkkingdee.top/Article/details/gt2pphigfsg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhengqikj.top/Article/details/gt2tbsqtebr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tian-w.cn/Article/details/gt2jtbaylfc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ppjwa.cn/Article/details/gt2jgjkumnu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.dianchejie.cn/Article/details/gt2kdhykehk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pycfn.com/Article/details/gt2chlpgbqi.html

[H10] 资源自动释放
来源：http://dali.wangshuangyany.cn/Article/details/gt2bxvmkwlw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gzhubu.top/Article/details/gt2tfzuzwao.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.redwolf501.top/Article/details/gt2goppbpmp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hammf.cn/Article/details/gt2vxuyracw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenjidiqi.icu/Article/details/gt2ywytxpwq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guannengcc.top/Article/details/gt2wnixhtjk.html

Go:   defer f.Close()
来源：http://dali.sufxvd.cn/Article/details/gt2sibnbbtj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258.top/Article/details/gt2hpxdphul.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2grbcheqt.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2bxmtqzxq.html

I. 正则表达式
来源：http://dali.vqdsnc.cn/Article/details/gt2alavndra.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2tvzgicob.html

[I01] 判断是否匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2hbfqcsdb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yueranfly.top/Article/details/gt2zzbkunbs.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2wvecowis.html

JS:   /\d+/.test(s)
来源：http://dali.yvedp.cn/Article/details/gt2twcxpuhz.html

TS:   /\d+/.test(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gdisdlav.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgfzy.top/Article/details/gt2zubalili.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.smart0.xyz/Article/details/gt2pqjpxcad.html

Ruby: s.match?(/\d+/)
来源：http://dali.tanke756.top/Article/details/gt2wfhoeyck.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sweek.top/Article/details/gt2kixpoxxl.html

[I02] 提取所有匹配
来源：http://dali.yongpay.top/Article/details/gt2blygnjnm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.fzhhl.top/Article/details/gt2mhaadadb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xziqi.cn/Article/details/gt2nwymbkhx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nypirmpt.html

TS:   s.match(/\d+/g)
来源：http://dali.yangfankeji.com/Article/details/gt2kaimiqpm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ulabotnr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qrrghwuy.html

Ruby: s.scan(/\d+/)
来源：http://dali.cheryme.top/Article/details/gt2tmpyfaiw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.aizwys.cn/Article/details/gt2ilbbaqkh.html

[I03] 提取捕获分组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ioyhzmmj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tianlin.xyz/Article/details/gt2euntjlbz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gzhubu.top/Article/details/gt2tqtwosmc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.guowangkeji.top/Article/details/gt2ehmffcym.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tanke756.top/Article/details/gt2oyelqpbu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.316326.xyz/Article/details/gt2pxjdvcqf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hongshengwenyu.top/Article/details/gt2nmhkjhtx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hammf.cn/Article/details/gt2mwlmzddu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pycfn.com/Article/details/gt2sdeygnov.html

[I04] 正则替换
来源：http://dali.jinqigufen.top/Article/details/gt2pzvqfasc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hammf.cn/Article/details/gt2zchsiryn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xksdfvtn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258888.top/Article/details/gt2gpifyjms.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yuxming.cn/Article/details/gt2vwnoxpxx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.quarkkingdee.top/Article/details/gt2yrrfxuhl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xylfe.cn/Article/details/gt2ilmshaly.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhixingplan.top/Article/details/gt2hmcvcghg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gt2eotowkqz.html

[I05] 按正则拆分
来源：http://dali.xuetiantiany.cn/Article/details/gt2bmckjmqd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lpoiibgb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tdanpuja.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gt2lkiddcyt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gt2jievirxw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.kuanghao11.cn/Article/details/gt2tebvrlyq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinqigufen.top/Article/details/gt2espryhqq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gt2ksmvvpux.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yvedp.cn/Article/details/gt2enpzfghx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigfzy.top/Article/details/gt2wtxhdngr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gt2hvzskdxq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.daxiang520.top/Article/details/gt2lxtweavj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.havefunace.top/Article/details/gt2ggmiqogw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhiwuduotai.top/Article/details/gt2nzdusvhd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gt2rthefivx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gceaghaw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ivvv.top/Article/details/gt2burryvei.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gt2mgqtmkti.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinqigfzy.top/Article/details/gt2mjwzzztv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigfzy.top/Article/details/gt2lrdysqum.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.feifeiyinyue.top/Article/details/gt2drcnmjyj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cqqwz.cn/Article/details/gt2dfdinkjg.html

TS:   /error/gim
来源：http://dali.shuidangran.top/Article/details/gt2gqofbfns.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hammf.cn/Article/details/gt2dcuydsef.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.guowangkeji.top/Article/details/gt2sharjvdr.html

Ruby: s.scan(/error/i)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iwuatzdz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.kuanghao11.cn/Article/details/gt2iwvlnqhx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gluvizft.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zycfv.cn/Article/details/gt2bbyiqvcd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.daxiang520.top/Article/details/gt2vwbzehpf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ivvv.top/Article/details/gt2fxbglxaq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fzhhl.top/Article/details/gt2bcwrobkz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hammf.cn/Article/details/gt2mdhhujhc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cashguo.top/Article/details/gt2ehqlhlxp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2leutamrg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenjidiqi.icu/Article/details/gt2xummclko.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2snwrmhqd.html

J. 日期与时间
来源：http://dali.havefunace.top/Article/details/gt2ebyeftaq.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2pzcegjqc.html

[J01] 获取当前时间
来源：http://dali.yj20258.top/Article/details/gt2zxspougc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.andypj.xyz/Article/details/gt2ikbpxijt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gt2xjoptltf.html

JS:   new Date();  Date.now()
来源：http://dali.shzxlz.cn/Article/details/gt2venenetu.html

TS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gt2efdsqzwt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxinkj.top/Article/details/gt2apnkhgrv.html

Go:   time.Now()
来源：http://dali.dashuyun.cn/Article/details/gt2kmgelhzk.html

Ruby: Time.now
来源：http://dali.kuanghao11.cn/Article/details/gt2aveufvcv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zdqjudy.top/Article/details/gt2fsnacphg.html

[J02] 格式化输出
来源：http://dali.sweek.top/Article/details/gt2kcttiqfk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenzaomai.com/Article/details/gt2baixdqll.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.andypj.xyz/Article/details/gt2xjzdxpfm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.c1oappe.top/Article/details/gt2rnjasipj.html

TS:   d.toISOString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2jggexbun.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sufxvd.cn/Article/details/gt2malgapzs.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nanxinkj.top/Article/details/gt2bkkadqxd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yangfankeji.com/Article/details/gt2rlxnedtk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.mhx1999.top/Article/details/gt2ifmvseda.html

[J03] 字符串解析为日期
来源：http://dali.316326.xyz/Article/details/gt2xozewzod.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ybcxt.top/Article/details/gt2yegqhecs.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pycfn.com/Article/details/gt2nyvinyqe.html

JS:   new Date("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gt2zxyszwoo.html

TS:   new Date("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gt2dhcbyzml.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gt2gyxridmq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gt2mjqypqmr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gt2hxwbhpmk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigfzy.top/Article/details/gt2nhtbucjp.html

[J04] 时间戳与日期互转
来源：http://dali.gogol.net.cn/Article/details/gt2adzljrsh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xylfe.cn/Article/details/gt2jijdrllq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxinkj.top/Article/details/gt2jtzrhzdj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.mhx1999.top/Article/details/gt2fqwvvcsy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yonumen.top/Article/details/gt2kbewgxvu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sxryk.cn/Article/details/gt2anrlbjru.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2doqtkqua.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dweicfeq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.316326.xyz/Article/details/gt2llwxzsrh.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhixingplan.top/Article/details/gt2mwxvsqlo.html

Py:   now + timedelta(days=7)
来源：http://dali.zdqjudy.top/Article/details/gt2uqabuqcq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yongpay.top/Article/details/gt2myfplpcx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gt2faedopeo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.bjfxy.top/Article/details/gt2mpftwjux.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hammf.cn/Article/details/gt2jfosxfbw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jqgfzy.top/Article/details/gt2mwbffbjh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.wangshuangyany.cn/Article/details/gt2lvctvcwa.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ivvv.top/Article/details/gt2hfpwgxfw.html

[J06] 计算两时间之差
来源：http://dali.dashuyun.cn/Article/details/gt2qwxyxwci.html

Py:   (end - start).total_seconds()
来源：http://dali.iojbl.cn/Article/details/gt2mtmeaanm.html

PHP:  $end->diff($start)->days;
来源：http://dali.yonumen.top/Article/details/gt2mafpjpge.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.guowangkeji.top/Article/details/gt2fyenymea.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yonumen.top/Article/details/gt2xwxxnefn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.daria6918.cn/Article/details/gt2cnorukfc.html

Go:   end.Sub(start).Hours()
来源：http://dali.dianchejie.cn/Article/details/gt2xiwnkfob.html

Ruby: end - start                 # 返回秒数
来源：http://dali.svipenyu.cn/Article/details/gt2qtnbokna.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhoulong.xyz/Article/details/gt2atduzata.html

[J07] 比较两个日期
来源：http://dali.pengpengdd.cyou/Article/details/gt2pefeguyu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gt2zqkftaee.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenzaomai.com/Article/details/gt2mcwikrss.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yanxiufei.cn/Article/details/gt2osbfkmgo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jenfqcbg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.smart0.xyz/Article/details/gt2nmzvtvrh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cqqwz.cn/Article/details/gt2qacgkvym.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gt2uhtpfibz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gt2npebkeoa.html

[J08] 提取年月日与星期
来源：http://dali.sufxvd.cn/Article/details/gt2ucannkwl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tian-w.cn/Article/details/gt2hbygpate.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnxiangtu.top/Article/details/gt2tubudoow.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.c1oappe.top/Article/details/gt2mfqcfiig.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yuxming.cn/Article/details/gt2hhndbahs.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ivvv.top/Article/details/gt2qsymjvkr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sweek.top/Article/details/gt2hurrgaim.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.haohaochexian.top/Article/details/gt2jwbiggiw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hammf.cn/Article/details/gt2sfiafinb.html

[J09] 时区处理
来源：http://dali.xziqi.cn/Article/details/gt2lsbgysot.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hongshengwenyu.top/Article/details/gt2arigezgd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigfzy.top/Article/details/gt2umjvoqkd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gt2kfwohkhi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gt2ahdpsnux.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hammf.cn/Article/details/gt2qbxagypc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhoulong.xyz/Article/details/gt2tnjakldb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.316326.xyz/Article/details/gt2ndnpybsg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj202588.top/Article/details/gt2nohregsv.html

[J10] 取今天 / 本月第一天
来源：http://dali.feifeiyinyue.top/Article/details/gt2vtmvzihe.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jqgufenzy.top/Article/details/gt2hasdutyj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.aizwys.cn/Article/details/gt2rcwjmjdf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.birdmap.top/Article/details/gt2leahrgok.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.0kj1m.cn/Article/details/gt2yetfhdby.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2jnvqonky.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.feifeiyinyue.top/Article/details/gt2rzeyznkx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zycfv.cn/Article/details/gt2jrtvstac.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2nxmpqkqx.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cwpzwwvt.html

K. JSON 与序列化
来源：http://dali.yonumen.top/Article/details/gt2estfnifj.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2ujfwdcom.html

[K01] 对象转 JSON 字符串
来源：http://dali.9152youxi.cn/Article/details/gt2dwdpbyxi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gt2ylsmjwtn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ltwxdsek.html

JS:   JSON.stringify(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2kkmfjeuc.html

TS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2alvllvrr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.aibaodan.cn/Article/details/gt2vsnxinnz.html

Go:   json.Marshal(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gpkgahat.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zdqjudy.top/Article/details/gt2nlydnlfh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yonumen.top/Article/details/gt2elvmegux.html

[K02] JSON 字符串转对象
来源：http://dali.pengpengdd.cyou/Article/details/gt2nybebtyq.html

Py:   json.loads(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vpgwtnsq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.iojbl.cn/Article/details/gt2mjvculid.html

JS:   JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gt2gcmzduwr.html

TS:   JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gt2hwpxhnzh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xuanzx.com/Article/details/gt2bvkprwsy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gt2askezgzd.html

Ruby: JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jyiltqeh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fzhhl.top/Article/details/gt2ecobskui.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yangfankeji.com/Article/details/gt2tjfsbagb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gogol.net.cn/Article/details/gt2ynplcgmz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.redwolf501.top/Article/details/gt2zwjfcxuz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sweek.top/Article/details/gt2tyhqnhtv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xylfe.cn/Article/details/gt2rinadevv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuxming.cn/Article/details/gt2oivsyjsu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cqqwz.cn/Article/details/gt2ycqtpqvp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yvedp.cn/Article/details/gt2rhgapokg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xuetiantiany.cn/Article/details/gt2kjeauddg.html

[K04] 读取 JSON 文件
来源：http://dali.sysykeji.top/Article/details/gt2xhvqowks.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangdashe.top/Article/details/gt2weffqqbt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.feifeiyinyue.top/Article/details/gt2rmariika.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgfzy.top/Article/details/gt2ghyksmpf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gt2apxljlhs.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gt2auclxlgh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gt2nnyxptqr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2ykewoqvl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxuanxn.top/Article/details/gt2gwhguhgk.html

[K05] 深拷贝对象
来源：http://dali.cqqwz.cn/Article/details/gt2yzasjmbl.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2woreoduy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ehwqpu.com/Article/details/gt2ieyiitrw.html

JS:   structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2iefynrtp.html

TS:   structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2dxvcxlay.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gzhubu.top/Article/details/gt2xsarbfyq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinqigfzy.top/Article/details/gt2feownslx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hongshengwenyu.top/Article/details/gt2nibfoskb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cqqwz.cn/Article/details/gt2pzquxjvk.html

[K06] 解析 URL 查询串
来源：http://dali.pycfn.com/Article/details/gt2mtmrgxke.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sufxvd.cn/Article/details/gt2ilaxrbzu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ucctrdrv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gt2giexeogx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xylfe.cn/Article/details/gt2bsdbazlh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cashguo.top/Article/details/gt2duldbdwb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gt2ifznkfzb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gt2fbyykcxl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gt2fueziadu.html

[K07] 进制转换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zoassbnb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gt2nlsydhuu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.dianchejie.cn/Article/details/gt2ouesmata.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2cdbpvadd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mrhijzjr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gt2xvnwvlmp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuanzx.com/Article/details/gt2drezzkow.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daxiang520.top/Article/details/gt2sqtvdapt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gt2orwpdlfw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fengsongda.top/Article/details/gt2tsgjdnil.html

Py:   pickle.dumps(obj)
来源：http://dali.hnqzz.top/Article/details/gt2qwlxjeoo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xziqi.cn/Article/details/gt2cmktbyxa.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.pycfn.com/Article/details/gt2jtoaupad.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.redwolf501.top/Article/details/gt2cxkcrtqk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhiwuduotai.top/Article/details/gt2wfiwxiqd.html

Go:   encoding/gob
来源：http://dali.chenlongwang.top/Article/details/gt2ocucruyn.html

Ruby: Marshal.dump(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2mznoxuwu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhoulong.xyz/Article/details/gt2qffomxig.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2amkqwnrl.html

L. 网络请求
来源：http://dali.hysaishi.cn/Article/details/gt2iqlkxjsr.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2lkhfglej.html

[L01] 发送 GET 请求
来源：http://dali.dianchejie.cn/Article/details/gt2yfzibaho.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhixingplan.top/Article/details/gt2kjwroqkx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kukrghfo.html

JS:   await fetch(url)
来源：http://dali.aizwys.cn/Article/details/gt2katytgcm.html

TS:   await fetch(url)
来源：http://dali.andypj.xyz/Article/details/gt2ohqfxjjd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xuetiantiany.cn/Article/details/gt2xogoiogp.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigfzy.top/Article/details/gt2ietykdvq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.quarkkingdee.top/Article/details/gt2rkjdvrya.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ydzc1.top/Article/details/gt2ukloivli.html

[L02] 发送 POST JSON
来源：http://dali.jqgufenzy.top/Article/details/gt2jfplfydq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gt2xtknvntg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj202588.top/Article/details/gt2vtufdfwy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cucudq.cn/Article/details/gt2xwdqjgeu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hysaishi.cn/Article/details/gt2lfqdvqym.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenjidiqi.icu/Article/details/gt2rkvmeqjv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.wangdashe.top/Article/details/gt2tzznhjsa.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.svipenyu.cn/Article/details/gt2qtywxifi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cucudq.cn/Article/details/gt2duvixyvp.html

[L03] 设置自定义请求头
来源：http://dali.sufxvd.cn/Article/details/gt2yhcuimlv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.mhx1999.top/Article/details/gt2bddusegi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj20258888.top/Article/details/gt2xpmgbasp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ehwqpu.com/Article/details/gt2sybfatxz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guannengcc.top/Article/details/gt2gchzxqxl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hnqzz.top/Article/details/gt2kvtucncv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gt2pjqmfbfn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.guowangkeji.top/Article/details/gt2ytbfepnr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gt2uquomfvm.html

[L04] 设置超时
来源：http://dali.snrcjt.cn/Article/details/gt2gkzovlxy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nanxinkj.top/Article/details/gt2sewnlxji.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jyoumei.cn/Article/details/gt2fxodrdwl.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sysykeji.top/Article/details/gt2dqtgknef.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenjidiqi.icu/Article/details/gt2mnoscfhy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangdashe.top/Article/details/gt2gsqqntzy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jlsjyb.cn/Article/details/gt2jbqtdjkt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xinyue.icu/Article/details/gt2fpsnykns.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jiagoushi.top/Article/details/gt2quxylfvw.html

[L05] 上传文件（multipart）
来源：http://dali.hysaishi.cn/Article/details/gt2pgpehzww.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinqigfzy.top/Article/details/gt2jtibarpf.html


<!-- 参考信息 -->