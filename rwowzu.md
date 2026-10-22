代发 wailian999

JS:   e.message;  e.stack
来源：http://dali.jyoumei.cn/Article/details/gt2ybbkwvgu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ehwqpu.com/Article/details/gt2vjppezmr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.haohaochexian.top/Article/details/gt2xjbudjhc.html

Go:   err.Error()
来源：http://dali.bjfxy.top/Article/details/gt2afeexxjv.html

Ruby: e.message;  e.backtrace
来源：http://dali.gotoacloud.top/Article/details/gt2ffyxwpss.html

C#:   e.Message;  e.StackTrace
来源：http://dali.316326.xyz/Article/details/gt2dsxdpvtq.html

[H09] 带错误码的异常
来源：http://dali.mhx1999.top/Article/details/gt2ivdrrwug.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ppjwa.cn/Article/details/gt2kafuzpbn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.aizwys.cn/Article/details/gt2gdnkozqj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daria6918.cn/Article/details/gt2iuncgppc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cashguo.top/Article/details/gt2ywtjcjcq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zoskrqes.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sxryk.cn/Article/details/gt2xddmtupn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zycfv.cn/Article/details/gt2apcpenrc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhengqikj.top/Article/details/gt2ikmytrso.html

[H10] 资源自动释放
来源：http://dali.yueranfly.top/Article/details/gt2gpoumjdb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2ukiqmzwj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhixingplan.top/Article/details/gt2gxamlcrb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.vqdsnc.cn/Article/details/gt2nhkujdru.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenjidiqi.icu/Article/details/gt2liwykiof.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.andypj.xyz/Article/details/gt2advvpdrk.html

Go:   defer f.Close()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vulwaokx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hammf.cn/Article/details/gt2fyqxazfe.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2oqirohpq.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2cufikzgn.html

I. 正则表达式
来源：http://dali.cdnleiting.top/Article/details/gt2ewjjkzhv.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2uwoqjhxn.html

[I01] 判断是否匹配
来源：http://dali.zycfv.cn/Article/details/gt2uhrtansy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yvedp.cn/Article/details/gt2ftzrnecx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2eoxalytv.html

JS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2fbrrhzwu.html

TS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gt2wjwyqrvl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ejtdhhqz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2tpnyyyqh.html

Ruby: s.match?(/\d+/)
来源：http://dali.svipenyu.cn/Article/details/gt2neekrzmj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.316326.xyz/Article/details/gt2mvijsgwq.html

[I02] 提取所有匹配
来源：http://dali.tian-w.cn/Article/details/gt2vuxwkzis.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gt2qvpnsaud.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jyoumei.cn/Article/details/gt2wbtbxpem.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xinyue.icu/Article/details/gt2eciafnin.html

TS:   s.match(/\d+/g)
来源：http://dali.dianchejie.cn/Article/details/gt2oayrmail.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tianlin.xyz/Article/details/gt2ueerlesh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ppjwa.cn/Article/details/gt2oitpmxub.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinqigufen.top/Article/details/gt2nlmrwzkd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sweek.top/Article/details/gt2sgnghzkn.html

[I03] 提取捕获分组
来源：http://dali.chenjidiqi.icu/Article/details/gt2rlamhnyu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.daxiang520.top/Article/details/gt2midniegz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wvawxcay.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.dianchejie.cn/Article/details/gt2hkwizwtr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ybcxt.top/Article/details/gt2szobgcmh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhongyouzk.top/Article/details/gt2ytshjrvk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuxming.cn/Article/details/gt2aggcnbvz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhengqikj.top/Article/details/gt2xaafwskv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hongshengwenyu.top/Article/details/gt2zwrgzrak.html

[I04] 正则替换
来源：http://dali.aizwys.cn/Article/details/gt2wbmlsnwg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.0kj1m.cn/Article/details/gt2zaenabqy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2schugpdd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tanke756.top/Article/details/gt2qjplcbob.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gt2mitzdkyd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bxgjfykb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.andypj.xyz/Article/details/gt2fgzjfzxx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nwbrower.top/Article/details/gt2vekkmsbk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuxming.cn/Article/details/gt2jaomplxg.html

[I05] 按正则拆分
来源：http://dali.chenjidiqi.icu/Article/details/gt2bdueykhi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.haohaochexian.top/Article/details/gt2phcjymja.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj202588.top/Article/details/gt2oardzhvh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2enztgdae.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gt2ifctisne.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hammf.cn/Article/details/gt2gurohjxg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ivvv.top/Article/details/gt2vnlhpiph.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gt2twluxtle.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jiagoushi.top/Article/details/gt2lqlassjy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cqqwz.cn/Article/details/gt2wvtwdkum.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yonumen.top/Article/details/gt2hluffvpm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.andypj.xyz/Article/details/gt2tikibgsj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gt2fvhognao.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenzaomai.com/Article/details/gt2tlaouvqu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gt2smlnztqx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cashguo.top/Article/details/gt2idinuxsv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nanxuanxn.top/Article/details/gt2zwpxvbjg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gt2pirvkroe.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qsneugkz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.birdmap.top/Article/details/gt2qnssmubn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2houzuzso.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.wangdashe.top/Article/details/gt2isgidsad.html

TS:   /error/gim
来源：http://dali.tanke756.top/Article/details/gt2bpodnghc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jqgufenzy.top/Article/details/gt2qemqwyxc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yuxming.cn/Article/details/gt2yfgoblrg.html

Ruby: s.scan(/error/i)
来源：http://dali.zycfv.cn/Article/details/gt2rrrnikdn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pycfn.com/Article/details/gt2qotcsyyh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xziqi.cn/Article/details/gt2wmikxlyy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.0kj1m.cn/Article/details/gt2ysppjowj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.c1oappe.top/Article/details/gt2xmwvandg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.haohaochexian.top/Article/details/gt2sksuyrjc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gt2ihlltpir.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.smart0.xyz/Article/details/gt2jsvdzqni.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.meibo888.top/Article/details/gt2mklpagfv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cucudq.cn/Article/details/gt2qxnqqvze.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.daria6918.cn/Article/details/gt2xojpyosc.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2ayuxdtpv.html

J. 日期与时间
来源：http://dali.smart0.xyz/Article/details/gt2ulcpzjyz.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2qhiypjmz.html

[J01] 获取当前时间
来源：http://dali.dashuyun.cn/Article/details/gt2gjhhkkcj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fvwxhctf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xinyue.icu/Article/details/gt2qiyprqzf.html

JS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gt2xmimtzbm.html

TS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gt2vodhdtot.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hnxiangtu.top/Article/details/gt2ryejgjyg.html

Go:   time.Now()
来源：http://dali.xinyue.icu/Article/details/gt2pensybgb.html

Ruby: Time.now
来源：http://dali.hfpthk.cn/Article/details/gt2gtknetie.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gogol.net.cn/Article/details/gt2lacfojhl.html

[J02] 格式化输出
来源：http://dali.sufxvd.cn/Article/details/gt2gntpoywy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guannengcc.top/Article/details/gt2qlkflouc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hnxiangtu.top/Article/details/gt2apfqpwse.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yanxiufei.cn/Article/details/gt2ywlupifg.html

TS:   d.toISOString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2fxvdlwzi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenlongwang.top/Article/details/gt2wmohrzao.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hysaishi.cn/Article/details/gt2fpefmksw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxuanxn.top/Article/details/gt2pyzjyltp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.dianchejie.cn/Article/details/gt2dgkvgvcz.html

[J03] 字符串解析为日期
来源：http://dali.xylfe.cn/Article/details/gt2pslovdyo.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hywenlv.cn/Article/details/gt2lppupiwv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gaohongyu789.top/Article/details/gt2dcvvlwmk.html

JS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xmaetymf.html

TS:   new Date("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gt2mxaduydk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gt2nptisrkj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.havefunace.top/Article/details/gt2rlfruasg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2cmychlpq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xylfe.cn/Article/details/gt2inedrylk.html

[J04] 时间戳与日期互转
来源：http://dali.mhx1999.top/Article/details/gt2meqetwqj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.aizwys.cn/Article/details/gt2bwxliwif.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xuetiantiany.cn/Article/details/gt2zlguuqvk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yabrwgbl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wqdgkkae.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cucudq.cn/Article/details/gt2pckjtdha.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangdashe.top/Article/details/gt2cvptejis.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ppjwa.cn/Article/details/gt2amsopkrl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuanzhike.top/Article/details/gt2gkwxhbue.html

[J05] 时间加减（加 7 天）
来源：http://dali.hammf.cn/Article/details/gt2oceexkdx.html

Py:   now + timedelta(days=7)
来源：http://dali.316326.xyz/Article/details/gt2zdbwuzbh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bgatvgnt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daxiang520.top/Article/details/gt2hcuinhgs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhengqikj.top/Article/details/gt2sabyjrib.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jiagoushi.top/Article/details/gt2rowadgjl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ybcxt.top/Article/details/gt2nfrravkz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.havefunace.top/Article/details/gt2sqjmyxqz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ghrixvwb.html

[J06] 计算两时间之差
来源：http://dali.zdqjudy.top/Article/details/gt2eflqneet.html

Py:   (end - start).total_seconds()
来源：http://dali.cqqwz.cn/Article/details/gt2hcntjmry.html

PHP:  $end->diff($start)->days;
来源：http://dali.dashuyun.cn/Article/details/gt2lgishpws.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shangyingyoupin.top/Article/details/gt2brtozzmd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oxbadcly.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shuidangran.top/Article/details/gt2tygmhhxo.html

Go:   end.Sub(start).Hours()
来源：http://dali.havefunace.top/Article/details/gt2tovlmhzl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2furoyfop.html

C#:   (end - start).TotalSeconds
来源：http://dali.gzhubu.top/Article/details/gt2nevubusi.html

[J07] 比较两个日期
来源：http://dali.yonumen.top/Article/details/gt2ffpvtexi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lpxrsnee.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.wangshuangyany.cn/Article/details/gt2pfiolvjb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.vqdsnc.cn/Article/details/gt2ozeylsll.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gt2oftozovr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jyoumei.cn/Article/details/gt2nwcvaxse.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gogol.net.cn/Article/details/gt2bidwmxzu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gt2wgsurgvm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gt2wwvinlhf.html

[J08] 提取年月日与星期
来源：http://dali.yangfankeji.com/Article/details/gt2vtreevvo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.andypj.xyz/Article/details/gt2hwpiltlv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxinkj.top/Article/details/gt2kqbrqgkr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuxming.cn/Article/details/gt2zkdbalui.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigufen.top/Article/details/gt2hyplepfe.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vapmrpri.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2caqrtycn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhongyouzk.top/Article/details/gt2rlvslhqj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.9152youxi.cn/Article/details/gt2wvowcxub.html

[J09] 时区处理
来源：http://dali.snrcjt.cn/Article/details/gt2fnbgtkft.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sufxvd.cn/Article/details/gt2emaqncjv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xuanzx.com/Article/details/gt2vngcsqvm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tianlin.xyz/Article/details/gt2lgizxivy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gt2vezbrezq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhoulong.xyz/Article/details/gt2ktptzjqy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yongpay.top/Article/details/gt2lywtsxls.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xinyue.icu/Article/details/gt2mynunmkp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gzhubu.top/Article/details/gt2qxyepgpx.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangshuangyany.cn/Article/details/gt2vkxvtaqt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2evbrwtmg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.feifeiyinyue.top/Article/details/gt2esjuqgcy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.guannengcc.top/Article/details/gt2nmevijji.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sweek.top/Article/details/gt2bercmdmr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jyoumei.cn/Article/details/gt2rugnehxx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.chenjidiqi.icu/Article/details/gt2vitdhuev.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gzhubu.top/Article/details/gt2zydpkive.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.vqdsnc.cn/Article/details/gt2udaerkyk.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2wzitwmlw.html

K. JSON 与序列化
来源：http://dali.hongshengwenyu.top/Article/details/gt2knygpfge.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2gfdpolwe.html

[K01] 对象转 JSON 字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2grqlwuua.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.haohaochexian.top/Article/details/gt2fgbamovy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gt2ztqnhfsi.html

JS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2achefrro.html

TS:   JSON.stringify(obj)
来源：http://dali.mhx1999.top/Article/details/gt2yhwdplio.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nanxuanxn.top/Article/details/gt2tveiaxjm.html

Go:   json.Marshal(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2efzeymao.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nanxinkj.top/Article/details/gt2xoxzvovs.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.pycfn.com/Article/details/gt2doxnyfds.html

[K02] JSON 字符串转对象
来源：http://dali.jqgufenzy.top/Article/details/gt2fbiiblus.html

Py:   json.loads(s)
来源：http://dali.yongpay.top/Article/details/gt2wdezanpn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.havefunace.top/Article/details/gt2uityhyys.html

JS:   JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gt2eanvgrlf.html

TS:   JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gt2tqlvoatu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.0kj1m.cn/Article/details/gt2kqxoqvdz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gt2jneitgvp.html

Ruby: JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gt2rfhqiawm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fzhhl.top/Article/details/gt2zizagcfs.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yuxming.cn/Article/details/gt2gmqhcmuc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jyoumei.cn/Article/details/gt2psutmmux.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gt2efsnxmjx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gogol.net.cn/Article/details/gt2jnvvsjpw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.aibaodan.cn/Article/details/gt2uuiyicsl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jianghu66.top/Article/details/gt2cgxxevvc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cashguo.top/Article/details/gt2chawmmpl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dongsfal.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.redwolf501.top/Article/details/gt2rrmlconh.html

[K04] 读取 JSON 文件
来源：http://dali.dianchejie.cn/Article/details/gt2jaltmubm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tanke756.top/Article/details/gt2studyijf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wktsemae.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gt2qcdtzopt.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gogol.net.cn/Article/details/gt2nyxatykv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gt2zyddhhbz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gt2duqqmdox.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cashguo.top/Article/details/gt2nrzdfoav.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tianlin.xyz/Article/details/gt2pgmahzrj.html

[K05] 深拷贝对象
来源：http://dali.havefunace.top/Article/details/gt2fspmnotk.html

Py:   copy.deepcopy(obj)
来源：http://dali.sweek.top/Article/details/gt2jahgrbwo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.guannengcc.top/Article/details/gt2cyakhsnw.html

JS:   structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gt2repulddv.html

TS:   structuredClone(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2vmxlhuhc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cqqwz.cn/Article/details/gt2uycmekvm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.daxiang520.top/Article/details/gt2zffoobbe.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.iojbl.cn/Article/details/gt2olwkpmll.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhiwuduotai.top/Article/details/gt2rkjtybjw.html

[K06] 解析 URL 查询串
来源：http://dali.gzhubu.top/Article/details/gt2sietdipo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.daria6918.cn/Article/details/gt2lullzgqa.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.birdmap.top/Article/details/gt2giryrbbl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dianchejie.cn/Article/details/gt2xddjbdbg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.9152youxi.cn/Article/details/gt2nzosizwq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuanzx.com/Article/details/gt2aooseygb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gt2weqdxpmt.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gt2rfvticed.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gt2jovgyfrt.html

[K07] 进制转换
来源：http://dali.jlsjyb.cn/Article/details/gt2mmjttkkn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2skjsbnyh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zdqjudy.top/Article/details/gt2ilmqcywm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gt2nedhuxkn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gt2ykkgaftv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gt2iybunnmp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xylfe.cn/Article/details/gt2mssudipw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yangfankeji.com/Article/details/gt2rgxcblom.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gt2bmmpiaay.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.0kj1m.cn/Article/details/gt2znqcjvea.html

Py:   pickle.dumps(obj)
来源：http://dali.sweek.top/Article/details/gt2pdrruvtt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2gbqrcfrj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shzxlz.cn/Article/details/gt2pdbvotmk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ppjwa.cn/Article/details/gt2mfpyokdc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ppjwa.cn/Article/details/gt2zivubzyf.html

Go:   encoding/gob
来源：http://dali.yuanzhike.top/Article/details/gt2xdynkdvx.html

Ruby: Marshal.dump(obj)
来源：http://dali.ivvv.top/Article/details/gt2dgnzlcyl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.birdmap.top/Article/details/gt2ihkxnvai.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2fdgytprs.html

L. 网络请求
来源：http://dali.yuanzhike.top/Article/details/gt2wlefulcx.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2qbkuvnyy.html

[L01] 发送 GET 请求
来源：http://dali.jqgfzy.top/Article/details/gt2ninvkhlw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hongshengwenyu.top/Article/details/gt2imrtfxnr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.daria6918.cn/Article/details/gt2nmhnuysl.html

JS:   await fetch(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wvhlvoqn.html

TS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gt2sybwcyuq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shzxlz.cn/Article/details/gt2hrcxlthp.html

Go:   resp, err := http.Get(url)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pabicpdm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sysykeji.top/Article/details/gt2fimazurq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.daxiang520.top/Article/details/gt2fvfgdlni.html

[L02] 发送 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mvhfuclx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gogol.net.cn/Article/details/gt2ffnvnahu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ydzc1.top/Article/details/gt2riptbapk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2htsnfksd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.svipenyu.cn/Article/details/gt2mnszjtms.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xylfe.cn/Article/details/gt2qbeedmlq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yubhvncu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yongpay.top/Article/details/gt2ldsjdgqm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yvedp.cn/Article/details/gt2octrrfuu.html

[L03] 设置自定义请求头
来源：http://dali.xylfe.cn/Article/details/gt2kutfbjmj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj202588.top/Article/details/gt2ygscduhj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yanxiufei.cn/Article/details/gt2wfeljxri.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jlsjyb.cn/Article/details/gt2unthxrwx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gt2dbgivzev.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.fengsongda.top/Article/details/gt2jtdfepqr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gt2glnhympk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.snrcjt.cn/Article/details/gt2oqxuvjgp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eyoldgry.html

[L04] 设置超时
来源：http://dali.sufxvd.cn/Article/details/gt2lyijbryc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.smart0.xyz/Article/details/gt2dxoveqck.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fengsongda.top/Article/details/gt2tndzdsoj.html


<!-- 参考信息 -->