代发 wailian999

Ruby: e.message;  e.backtrace
来源：http://dali.cucudq.cn/Article/details/gt2pwektlxt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.aizwys.cn/Article/details/gt2nenwxoqt.html

[H09] 带错误码的异常
来源：http://dali.aibaodan.cn/Article/details/gt2vcfxniye.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xylfe.cn/Article/details/gt2hffquqqm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cdnleiting.top/Article/details/gt2eixbeqrs.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.snrcjt.cn/Article/details/gt2sbpzpmxf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2nzzfzgrt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xziqi.cn/Article/details/gt2fxdhdqpl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cashguo.top/Article/details/gt2zqqfbbcq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hammf.cn/Article/details/gt2imtkoqcq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gogol.net.cn/Article/details/gt2epjvulmp.html

[H10] 资源自动释放
来源：http://dali.fengsongda.top/Article/details/gt2xsiganba.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.birdmap.top/Article/details/gt2skijbiqb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ehwqpu.com/Article/details/gt2zarpertl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gt2lhhbbbfv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.meibo888.top/Article/details/gt2bqcusmpf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cucudq.cn/Article/details/gt2dlewbclu.html

Go:   defer f.Close()
来源：http://dali.yj20258.top/Article/details/gt2luwwemxz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gotoacloud.top/Article/details/gt2wwssotsl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2lxsriopd.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2ehermobl.html

I. 正则表达式
来源：http://dali.yanxiufei.cn/Article/details/gt2eqyrfhxq.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2nyswhfeh.html

[I01] 判断是否匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pmidnczh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yvedp.cn/Article/details/gt2etdlxaqk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmuhcuk.html

JS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gt2pzsxhrjt.html

TS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gt2urzwnsph.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tian-w.cn/Article/details/gt2tzfyfkzs.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jianghu66.top/Article/details/gt2aijjaiiu.html

Ruby: s.match?(/\d+/)
来源：http://dali.yongpay.top/Article/details/gt2jutbtrdk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.vqdsnc.cn/Article/details/gt2isxzfvgy.html

[I02] 提取所有匹配
来源：http://dali.yuanzhike.top/Article/details/gt2ybqqucsf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lftnbrmf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shzxlz.cn/Article/details/gt2mwlznolp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hywenlv.cn/Article/details/gt2ebwccofk.html

TS:   s.match(/\d+/g)
来源：http://dali.nanxuanxn.top/Article/details/gt2bwwmyfjx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.dashuyun.cn/Article/details/gt2behqrnol.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cqqwz.cn/Article/details/gt2gohlicgp.html

Ruby: s.scan(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gt2xikzmvlz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gt2vmpiipba.html

[I03] 提取捕获分组
来源：http://dali.redwolf501.top/Article/details/gt2pygvtbrx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2agfitfdc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ivvv.top/Article/details/gt2rypuxwht.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.dashuyun.cn/Article/details/gt2ljoinfsi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.birdmap.top/Article/details/gt2xevhbmym.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nanxuanxn.top/Article/details/gt2oidgftek.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yvedp.cn/Article/details/gt2ijnllxgs.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sxryk.cn/Article/details/gt2hxpjcwee.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xylfe.cn/Article/details/gt2eblbzyyv.html

[I04] 正则替换
来源：http://dali.guowangkeji.top/Article/details/gt2nnvhqadm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhoulong.xyz/Article/details/gt2fvxbvfjf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2yrhzbmtb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sxryk.cn/Article/details/gt2ymilfcnj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uhkqvbqa.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cheryme.top/Article/details/gt2suakwwis.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ivvv.top/Article/details/gt2sdhlhmfg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.mhx1999.top/Article/details/gt2fpmdqduv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cashguo.top/Article/details/gt2opffzfql.html

[I05] 按正则拆分
来源：http://dali.nanxinkj.top/Article/details/gt2enqjapib.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj20258888.top/Article/details/gt2ekloxyqp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2uwvhmeey.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gt2luoexinc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gt2ndhkzmog.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhiwuduotai.top/Article/details/gt2qeccgclo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinqigfzy.top/Article/details/gt2fxvewhhk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gt2grbqrjrn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ydzc1.top/Article/details/gt2jqraoblf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pycfn.com/Article/details/gt2tozartag.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gt2ygonpxex.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yongpay.top/Article/details/gt2vqsdoupj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ybcxt.top/Article/details/gt2ygqzctge.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shzxlz.cn/Article/details/gt2aqzjkird.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gt2fdkcxizw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangtech.top/Article/details/gt2swlhqyoh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xziqi.cn/Article/details/gt2jjcrbdef.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gt2fxojzktr.html

[I07] 忽略大小写与多行模式
来源：http://dali.hongshengwenyu.top/Article/details/gt2flrlawxo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rwjhidal.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj20258888.top/Article/details/gt2ozougmtf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yanxiufei.cn/Article/details/gt2pyjppzdl.html

TS:   /error/gim
来源：http://dali.zhixingplan.top/Article/details/gt2gnbvuxop.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cdnleiting.top/Article/details/gt2bvnbhpnq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yiswkiuz.html

Ruby: s.scan(/error/i)
来源：http://dali.sufxvd.cn/Article/details/gt2ytqjfabm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sxryk.cn/Article/details/gt2fhczhfmv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxinkj.top/Article/details/gt2ufywbdyf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuanzx.com/Article/details/gt2xgafxwhs.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cucudq.cn/Article/details/gt2xuopldwd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tianlin.xyz/Article/details/gt2relshayj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gt2whamdjrv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuxming.cn/Article/details/gt2wzbtxjfi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.dianchejie.cn/Article/details/gt2bolzhaoi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xuanzx.com/Article/details/gt2dvqpeqar.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yuxming.cn/Article/details/gt2qbefppvq.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2enbidppu.html

J. 日期与时间
来源：http://dali.shangyingyoupin.top/Article/details/gt2zyvsvijr.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2klrqxofa.html

[J01] 获取当前时间
来源：http://dali.snrcjt.cn/Article/details/gt2rxennpmr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shzxlz.cn/Article/details/gt2mgpyaxec.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.birdmap.top/Article/details/gt2whkyoeha.html

JS:   new Date();  Date.now()
来源：http://dali.xuetiantiany.cn/Article/details/gt2mffnxazd.html

TS:   new Date();  Date.now()
来源：http://dali.yonumen.top/Article/details/gt2jemidshj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmibebp.html

Go:   time.Now()
来源：http://dali.yuanzhike.top/Article/details/gt2xutertjn.html

Ruby: Time.now
来源：http://dali.zdqjudy.top/Article/details/gt2qsnzdeci.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ehwqpu.com/Article/details/gt2bzexcbqv.html

[J02] 格式化输出
来源：http://dali.havefunace.top/Article/details/gt2lxqjzzfq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gt2hqvhibjo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenzaomai.com/Article/details/gt2zkdejtwx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.vqdsnc.cn/Article/details/gt2thbknxdw.html

TS:   d.toISOString()
来源：http://dali.zycfv.cn/Article/details/gt2uyktoqwe.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cqqwz.cn/Article/details/gt2zflvxhik.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ppjwa.cn/Article/details/gt2ijutgtke.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gt2crcvyddw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cashguo.top/Article/details/gt2oohqitqo.html

[J03] 字符串解析为日期
来源：http://dali.mhx1999.top/Article/details/gt2vaiymnon.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigfzy.top/Article/details/gt2utpcvvoy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shuidangran.top/Article/details/gt2xcsnwcpn.html

JS:   new Date("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gt2qeqvpoii.html

TS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gt2mnvshqcl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gt2zbncztrl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gt2iilysxxt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gt2zwbpsujr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.quarkkingdee.top/Article/details/gt2ljrxbmfm.html

[J04] 时间戳与日期互转
来源：http://dali.sxryk.cn/Article/details/gt2qkgjqkbh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ivvv.top/Article/details/gt2uktqdqby.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hysaishi.cn/Article/details/gt2imfucwpk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jlsjyb.cn/Article/details/gt2iqxqbncv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sweek.top/Article/details/gt2vunwitiw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yanxiufei.cn/Article/details/gt2ffsbnlrg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxeoxbe.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.meibo888.top/Article/details/gt2gbpffenv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hysaishi.cn/Article/details/gt2hzheplse.html

[J05] 时间加减（加 7 天）
来源：http://dali.wangdashe.top/Article/details/gt2znmsctue.html

Py:   now + timedelta(days=7)
来源：http://dali.hammf.cn/Article/details/gt2hinyapyd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhixingplan.top/Article/details/gt2fyxlxrwp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shzxlz.cn/Article/details/gt2hdfltsdl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj202588.top/Article/details/gt2gipltifo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fengsongda.top/Article/details/gt2gpgkcocg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj20258888.top/Article/details/gt2xqxvjkvk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinghuilouyu.cn/Article/details/gt2biqursrg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sufxvd.cn/Article/details/gt2ldcijipz.html

[J06] 计算两时间之差
来源：http://dali.jiagoushi.top/Article/details/gt2ufkkxfao.html

Py:   (end - start).total_seconds()
来源：http://dali.ydzc1.top/Article/details/gt2pokotpdf.html

PHP:  $end->diff($start)->days;
来源：http://dali.havefunace.top/Article/details/gt2hhpfvjfh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.haohaochexian.top/Article/details/gt2oqhbmdqd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hnxiangtu.top/Article/details/gt2yqhpkndp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yuanzhike.top/Article/details/gt2xqmzywsi.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ivblbzdm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qwqfbktw.html

C#:   (end - start).TotalSeconds
来源：http://dali.hnqzz.top/Article/details/gt2ijpeyruw.html

[J07] 比较两个日期
来源：http://dali.daxiang520.top/Article/details/gt2ognigdzj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gt2ocqcdnbi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hongshengwenyu.top/Article/details/gt2qmttydld.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gt2okqbphap.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gt2uruysrkd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj20258888.top/Article/details/gt2akeqvebw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zdqjudy.top/Article/details/gt2qalncncc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gt2mshvyent.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gt2ixaomeip.html

[J08] 提取年月日与星期
来源：http://dali.smart0.xyz/Article/details/gt2fmmftwxj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenzaomai.com/Article/details/gt2mpiqkvpk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cheryme.top/Article/details/gt2eogtagdr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xinyue.icu/Article/details/gt2fstsgkjg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.svipenyu.cn/Article/details/gt2llyoyqci.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gotoacloud.top/Article/details/gt2gisxpsxn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj202588.top/Article/details/gt2kuixzfeo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jlsjyb.cn/Article/details/gt2nqraxdsm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zycfv.cn/Article/details/gt2mjufjlra.html

[J09] 时区处理
来源：http://dali.hfpthk.cn/Article/details/gt2omjyuqij.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cdnleiting.top/Article/details/gt2xsgnmvrz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.316326.xyz/Article/details/gt2xvgzbojx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ybcxt.top/Article/details/gt2petoyrur.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.0kj1m.cn/Article/details/gt2ghsgnroa.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gzhubu.top/Article/details/gt2ljoewiey.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj202588.top/Article/details/gt2qhpfdyyi.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zycfv.cn/Article/details/gt2ijyavprh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gzhubu.top/Article/details/gt2ndbvvmiv.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinqigufen.top/Article/details/gt2ytxlagdv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jlsjyb.cn/Article/details/gt2vckjboyd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zncfrowz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tanke756.top/Article/details/gt2jhacvyva.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2tmsicvjj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gotoacloud.top/Article/details/gt2izdffwgx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pycfn.com/Article/details/gt2vuncfwny.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.meibo888.top/Article/details/gt2reimiekl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.pycfn.com/Article/details/gt2xdqiyduq.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2vfancknd.html

K. JSON 与序列化
来源：http://dali.xinyue.icu/Article/details/gt2pcneqmwk.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2slcgvfxt.html

[K01] 对象转 JSON 字符串
来源：http://dali.gotoacloud.top/Article/details/gt2fhsxqcha.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.meibo888.top/Article/details/gt2nfjmeeqo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gt2rszvhmtj.html

JS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gt2ttpwshxj.html

TS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2dubhdfqs.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cucudq.cn/Article/details/gt2dilecqje.html

Go:   json.Marshal(obj)
来源：http://dali.sysykeji.top/Article/details/gt2bakfgqwv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.smart0.xyz/Article/details/gt2rewswfdr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2cvavnqhu.html

[K02] JSON 字符串转对象
来源：http://dali.jqgfzy.top/Article/details/gt2hrgsessh.html

Py:   json.loads(s)
来源：http://dali.zdqjudy.top/Article/details/gt2rtbeetnv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tianlin.xyz/Article/details/gt2xvmyuttu.html

JS:   JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tqjmgshg.html

TS:   JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gt2pibhvlhm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gt2lpptknta.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gt2eyetweru.html

Ruby: JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2loqfoegm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fzlzchpd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.9152youxi.cn/Article/details/gt2nwoztcpl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gt2sjbvbjfi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhixingplan.top/Article/details/gt2ybufnahu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kajzjpyy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.daxiang520.top/Article/details/gt2daneluol.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.havefunace.top/Article/details/gt2gjehgqfz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hammf.cn/Article/details/gt2qqbwvfow.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.bjfxy.top/Article/details/gt2xkncqbou.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2inkdzofa.html

[K04] 读取 JSON 文件
来源：http://dali.hywenlv.cn/Article/details/gt2lmotuljh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jqgfzy.top/Article/details/gt2zxvfuefe.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sweek.top/Article/details/gt2genolqkm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yvedp.cn/Article/details/gt2dwhugcvy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhoulong.xyz/Article/details/gt2xsqhwvrr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.9152youxi.cn/Article/details/gt2ccluydvd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yueranfly.top/Article/details/gt2osnywrze.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangdashe.top/Article/details/gt2bpxbtelh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ogtgoxax.html

[K05] 深拷贝对象
来源：http://dali.ybcxt.top/Article/details/gt2styprulg.html

Py:   copy.deepcopy(obj)
来源：http://dali.gzhubu.top/Article/details/gt2yyltdvzu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.smart0.xyz/Article/details/gt2skkmsphn.html

JS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2gurikgna.html

TS:   structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2icenqras.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.c1oappe.top/Article/details/gt2ltdvuewh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sxryk.cn/Article/details/gt2dqbxbbzm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhengqikj.top/Article/details/gt2xvxilcpm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yuanzhike.top/Article/details/gt2gipyivqg.html

[K06] 解析 URL 查询串
来源：http://dali.jqgufenzy.top/Article/details/gt2nymubaef.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gzhubu.top/Article/details/gt2zmymnwxl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tian-w.cn/Article/details/gt2kbruceha.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gt2stxrvygi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mxtrrohj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sweek.top/Article/details/gt2muywruvf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gt2jbzehznb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nexcgmww.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gt2vagbksxy.html

[K07] 进制转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2doyrgfoz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gt2pxwghljq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aizwys.cn/Article/details/gt2rygbvkci.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gt2zoulhvop.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kzbmqsbi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2hnhtlvoj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qjzrdnii.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xuanzx.com/Article/details/gt2wpqrlkvc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gt2bydauvmk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinqigufen.top/Article/details/gt2ucivkjmw.html

Py:   pickle.dumps(obj)
来源：http://dali.yongpay.top/Article/details/gt2ygnunxhz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sxryk.cn/Article/details/gt2pecemwxc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.redwolf501.top/Article/details/gt2kurqwuck.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhixingplan.top/Article/details/gt2znxykrww.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jnrrawpt.html

Go:   encoding/gob
来源：http://dali.yanxiufei.cn/Article/details/gt2gjgyoaer.html

Ruby: Marshal.dump(obj)
来源：http://dali.bjfxy.top/Article/details/gt2xhgwadpb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhixingplan.top/Article/details/gt2ruwqtxxj.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2enwbbxxe.html

L. 网络请求
来源：http://dali.redwolf501.top/Article/details/gt2imtxxhlj.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2uphohgae.html

[L01] 发送 GET 请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hgiudmbn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jqgfzy.top/Article/details/gt2qzrnhjuu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.aizwys.cn/Article/details/gt2lyochako.html

JS:   await fetch(url)
来源：http://dali.hfpthk.cn/Article/details/gt2rhhggsjo.html

TS:   await fetch(url)
来源：http://dali.ehwqpu.com/Article/details/gt2dgvdpmkk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.c1oappe.top/Article/details/gt2rnsvwzou.html

Go:   resp, err := http.Get(url)
来源：http://dali.gotoacloud.top/Article/details/gt2pdhqfyrk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shuidangran.top/Article/details/gt2qwmmsinj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ezertpfd.html

[L02] 发送 POST JSON
来源：http://dali.hnqzz.top/Article/details/gt2xghyuiyz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.havefunace.top/Article/details/gt2eplayxpx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hysaishi.cn/Article/details/gt2ceweahyc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gogol.net.cn/Article/details/gt2mhafkuch.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.kuanghao11.cn/Article/details/gt2mfxeelgj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.svipenyu.cn/Article/details/gt2vrpfuczc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hysaishi.cn/Article/details/gt2xrwltyhy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ssosvspb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hmqddshx.html

[L03] 设置自定义请求头
来源：http://dali.nwbrower.top/Article/details/gt2tpzmuilu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2iuisrtvb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vyfjfaoe.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ehwqpu.com/Article/details/gt2aestngdg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gt2dvklryeu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xinyue.icu/Article/details/gt2hirlusiu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shzxlz.cn/Article/details/gt2rhadaozq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yanxiufei.cn/Article/details/gt2eefuywjs.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yanxiufei.cn/Article/details/gt2gkzlkvpn.html

[L04] 设置超时
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dtzafang.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gotoacloud.top/Article/details/gt2xgwapffo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nwbrower.top/Article/details/gt2kcaxoriy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcneals.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gt2sdjpcggf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj202588.top/Article/details/gt2owoxwrjb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dianchejie.cn/Article/details/gt2dwhbzagj.html


<!-- 参考信息 -->