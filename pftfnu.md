代发 wailian999

JS:   e.message;  e.stack
来源：http://dali.yangfankeji.com/Article/details/gt2iyjmwzkx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xnckzrbk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.redwolf501.top/Article/details/gt2miiihvrl.html

Go:   err.Error()
来源：http://dali.snrcjt.cn/Article/details/gt2aljwdqip.html

Ruby: e.message;  e.backtrace
来源：http://dali.nwbrower.top/Article/details/gt2xutderzv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuetiantiany.cn/Article/details/gt2xyamjvsv.html

[H09] 带错误码的异常
来源：http://dali.ehwqpu.com/Article/details/gt2gsofzbuu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sweek.top/Article/details/gt2pigudmts.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.kuanghao11.cn/Article/details/gt2zzirajby.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangdashe.top/Article/details/gt2ojpgcfen.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lztirfqe.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhengqikj.top/Article/details/gt2ajybcpew.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.dashuyun.cn/Article/details/gt2otbtsodp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daria6918.cn/Article/details/gt2fhdinild.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.havefunace.top/Article/details/gt2ttpkjiny.html

[H10] 资源自动释放
来源：http://dali.iojbl.cn/Article/details/gt2otuoqloa.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuanzhike.top/Article/details/gt2uqivsjur.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.birdmap.top/Article/details/gt2sioqwdvb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gt2pvfhgedk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gt2ytbiodyv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yongpay.top/Article/details/gt2bjtmgfiv.html

Go:   defer f.Close()
来源：http://dali.ivvv.top/Article/details/gt2ipzqyjkv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cucudq.cn/Article/details/gt2ibvoesvy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2wpjsjmui.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2socecurp.html

I. 正则表达式
来源：http://dali.shzxlz.cn/Article/details/gt2oqmmxmkd.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2kwaytpec.html

[I01] 判断是否匹配
来源：http://dali.ivvv.top/Article/details/gt2sqoazpdu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ppjwa.cn/Article/details/gt2rhkbwbjo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.c1oappe.top/Article/details/gt2ltmqvadd.html

JS:   /\d+/.test(s)
来源：http://dali.andypj.xyz/Article/details/gt2nvahswfp.html

TS:   /\d+/.test(s)
来源：http://dali.sxryk.cn/Article/details/gt2qficimui.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gotoacloud.top/Article/details/gt2zaszrjmy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sysykeji.top/Article/details/gt2tbouaihs.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gt2kdjnarca.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jiagoushi.top/Article/details/gt2fpakfqbj.html

[I02] 提取所有匹配
来源：http://dali.sufxvd.cn/Article/details/gt2zfrvomeo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shzxlz.cn/Article/details/gt2sowfwyhs.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xylfe.cn/Article/details/gt2xpxfzsyy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.vqdsnc.cn/Article/details/gt2cfcfnlhd.html

TS:   s.match(/\d+/g)
来源：http://dali.xylfe.cn/Article/details/gt2zvpviodl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhixingplan.top/Article/details/gt2yezskgnh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.snrcjt.cn/Article/details/gt2nsaemisr.html

Ruby: s.scan(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gt2mjgvmbnf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zdqjudy.top/Article/details/gt2allecdif.html

[I03] 提取捕获分组
来源：http://dali.hywenlv.cn/Article/details/gt2jpcmobwl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.dianchejie.cn/Article/details/gt2gbpkkpzd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sysykeji.top/Article/details/gt2ipgqxrat.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jianghu66.top/Article/details/gt2sfprprof.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ydzc1.top/Article/details/gt2asiineps.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhengqikj.top/Article/details/gt2gwhsdfez.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.feifeiyinyue.top/Article/details/gt2nqxwuxjf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tanke756.top/Article/details/gt2yhaubewu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2acqgxeyq.html

[I04] 正则替换
来源：http://dali.gogol.net.cn/Article/details/gt2rlwzlgoq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.aizwys.cn/Article/details/gt2nttupela.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xziqi.cn/Article/details/gt2wgcwrgfx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.316326.xyz/Article/details/gt2qtanzzqx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gt2omtoahxm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ivvv.top/Article/details/gt2ygpmdkgz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.9152youxi.cn/Article/details/gt2ufbiolil.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.guannengcc.top/Article/details/gt2ifvpeari.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.havefunace.top/Article/details/gt2rfczcftv.html

[I05] 按正则拆分
来源：http://dali.cdnleiting.top/Article/details/gt2argjsewx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aibaodan.cn/Article/details/gt2xvskgvwx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhixingplan.top/Article/details/gt2fsbaxbwj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gt2oinytswk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gt2fbulmflk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jianghu66.top/Article/details/gt2liomklca.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.havefunace.top/Article/details/gt2rdbivdbq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gt2kiwzasai.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hywenlv.cn/Article/details/gt2wiqjnrfl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhongyouzk.top/Article/details/gt2hxzrbjry.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gt2wuyususs.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.haohaochexian.top/Article/details/gt2eouteosv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigufen.top/Article/details/gt2lsrtanjr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dianchejie.cn/Article/details/gt2brmjsicd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gt2ssckkxjr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhongyouzk.top/Article/details/gt2vtadgaiy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zdqjudy.top/Article/details/gt2qachvjxt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gt2umycxmzf.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenzaomai.com/Article/details/gt2eonnnepf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hnqzz.top/Article/details/gt2qoskijdo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hysaishi.cn/Article/details/gt2clflytxn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.snrcjt.cn/Article/details/gt2pvdyvbbs.html

TS:   /error/gim
来源：http://dali.shzxlz.cn/Article/details/gt2rufvcnuc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.daria6918.cn/Article/details/gt2njumhlss.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2togangxg.html

Ruby: s.scan(/error/i)
来源：http://dali.smart0.xyz/Article/details/gt2xhfbuwob.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.fzhhl.top/Article/details/gt2xplwggnm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.vqdsnc.cn/Article/details/gt2sycfbujs.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jyoumei.cn/Article/details/gt2xupsjamz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hfpthk.cn/Article/details/gt2sekjeesb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.bjfxy.top/Article/details/gt2necvdbvd.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gt2inxbumub.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jianghu66.top/Article/details/gt2aunvxvua.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cucudq.cn/Article/details/gt2cbymmjmg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yongpay.top/Article/details/gt2wvgxhgpm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.meibo888.top/Article/details/gt2wlsvgwwu.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2cmmyogbg.html

J. 日期与时间
来源：http://dali.yj20258888.top/Article/details/gt2zcwqruyk.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2nawjiwei.html

[J01] 获取当前时间
来源：http://dali.mhx1999.top/Article/details/gt2wtjdlkfg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gotoacloud.top/Article/details/gt2keuzgiga.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj202588.top/Article/details/gt2vpbhqekj.html

JS:   new Date();  Date.now()
来源：http://dali.chenlongwang.top/Article/details/gt2dcgvmzfu.html

TS:   new Date();  Date.now()
来源：http://dali.hammf.cn/Article/details/gt2rrrhkfbk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yvedp.cn/Article/details/gt2sayjxcmb.html

Go:   time.Now()
来源：http://dali.yj202588.top/Article/details/gt2lsrfdtem.html

Ruby: Time.now
来源：http://dali.gaohongyu789.top/Article/details/gt2sxyqgdun.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.316326.xyz/Article/details/gt2ecljgllg.html

[J02] 格式化输出
来源：http://dali.wangdashe.top/Article/details/gt2nlhirxaf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gt2tquukyik.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tianlin.xyz/Article/details/gt2ewkvxzfz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nanxuanxn.top/Article/details/gt2usyqveto.html

TS:   d.toISOString()
来源：http://dali.zhengqikj.top/Article/details/gt2vxavdiek.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.haohaochexian.top/Article/details/gt2vpisnmab.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jzhkwybp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gt2wtvqrahn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.mhx1999.top/Article/details/gt2ylywslqs.html

[J03] 字符串解析为日期
来源：http://dali.yanxiufei.cn/Article/details/gt2tofaccro.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.svipenyu.cn/Article/details/gt2jeuqdeoo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.andypj.xyz/Article/details/gt2qsdptmtc.html

JS:   new Date("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gt2mjnntcjg.html

TS:   new Date("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gt2mcgxlkri.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gt2lchdhchy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gt2dvklqble.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gt2kymjylqc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvzazgk.html

[J04] 时间戳与日期互转
来源：http://dali.ivvv.top/Article/details/gt2arfrkmxy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tianlin.xyz/Article/details/gt2hbafccgd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gaohongyu789.top/Article/details/gt2ffywdlzb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj20258.top/Article/details/gt2llwrkock.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.birdmap.top/Article/details/gt2dbixjjsf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.316326.xyz/Article/details/gt2przhmalp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yonumen.top/Article/details/gt2ecyglkxq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2jvboxmvv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.fzhhl.top/Article/details/gt2kjdluznd.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhoulong.xyz/Article/details/gt2hwdqejpa.html

Py:   now + timedelta(days=7)
来源：http://dali.gaohongyu789.top/Article/details/gt2pvftaava.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gogol.net.cn/Article/details/gt2behoppar.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zycfv.cn/Article/details/gt2bixmmedn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gt2txrgqxdw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj20258888.top/Article/details/gt2irdngpue.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj20258.top/Article/details/gt2wurihddg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnxiangtu.top/Article/details/gt2sjjpdexp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aqtbkvwv.html

[J06] 计算两时间之差
来源：http://dali.cheryme.top/Article/details/gt2pppvboou.html

Py:   (end - start).total_seconds()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ithgppfc.html

PHP:  $end->diff($start)->days;
来源：http://dali.yangfankeji.com/Article/details/gt2tnxkzzhd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.0kj1m.cn/Article/details/gt2ouczotti.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.316326.xyz/Article/details/gt2tmbaufsc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenzaomai.com/Article/details/gt2gkziityo.html

Go:   end.Sub(start).Hours()
来源：http://dali.yonumen.top/Article/details/gt2gosoipbq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nanxuanxn.top/Article/details/gt2pxlsxnbz.html

C#:   (end - start).TotalSeconds
来源：http://dali.9152youxi.cn/Article/details/gt2zksakusk.html

[J07] 比较两个日期
来源：http://dali.havefunace.top/Article/details/gt2skijmwqm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xpkcvxmh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.dianchejie.cn/Article/details/gt2vnfgkkao.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.0kj1m.cn/Article/details/gt2jefcifwc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gt2lxumfvnp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.iojbl.cn/Article/details/gt2rtlmdodu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qxakjyqu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gt2ktgcarko.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gt2yrlnhgws.html

[J08] 提取年月日与星期
来源：http://dali.ppjwa.cn/Article/details/gt2qstkhjyh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vnyuvsyt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tianlin.xyz/Article/details/gt2tglliibz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.kuanghao11.cn/Article/details/gt2npmjyzqq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yueranfly.top/Article/details/gt2ncndqytu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.birdmap.top/Article/details/gt2nmojwdwq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yanxiufei.cn/Article/details/gt2zqruzrxt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cqqwz.cn/Article/details/gt2viteanlf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hongshengwenyu.top/Article/details/gt2fqfmrdcz.html

[J09] 时区处理
来源：http://dali.wangshuangyany.cn/Article/details/gt2iosocdrz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sweek.top/Article/details/gt2llpjicos.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mokodwed.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gt2ejgwukws.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zycfv.cn/Article/details/gt2ykodspxa.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jcqbqlfd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.wangdashe.top/Article/details/gt2owpaslpf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ehwqpu.com/Article/details/gt2adrvreiw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ucdnittz.html

[J10] 取今天 / 本月第一天
来源：http://dali.sweek.top/Article/details/gt2tuochahd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhixingplan.top/Article/details/gt2xgaqiogd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wjhsnudg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.mhx1999.top/Article/details/gt2alecgdja.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.haohaochexian.top/Article/details/gt2tfnfvltk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.svipenyu.cn/Article/details/gt2wnrytssj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.0kj1m.cn/Article/details/gt2cugqcidf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jyoumei.cn/Article/details/gt2gnhzkqob.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinqigufen.top/Article/details/gt2zabaamtf.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2iolurkhh.html

K. JSON 与序列化
来源：http://dali.cqqwz.cn/Article/details/gt2wxoizhah.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2xcoaniuv.html

[K01] 对象转 JSON 字符串
来源：http://dali.ybcxt.top/Article/details/gt2xswqptmm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gt2nkwhnswz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gt2ttlrtgjj.html

JS:   JSON.stringify(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2srhqdsvn.html

TS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2vaafkayg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenlongwang.top/Article/details/gt2wuiwxmkz.html

Go:   json.Marshal(obj)
来源：http://dali.pycfn.com/Article/details/gt2cklqlmac.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhongyouzk.top/Article/details/gt2gmewojui.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2eddwenyn.html

[K02] JSON 字符串转对象
来源：http://dali.xziqi.cn/Article/details/gt2eccienvp.html

Py:   json.loads(s)
来源：http://dali.zhengqikj.top/Article/details/gt2pqhpdbfd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.fengsongda.top/Article/details/gt2obrsthtt.html

JS:   JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gt2tegugnhy.html

TS:   JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gt2vbaxwzsq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.smart0.xyz/Article/details/gt2duahfwwx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigufen.top/Article/details/gt2tfjzsqha.html

Ruby: JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gt2edtsdlzq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.c1oappe.top/Article/details/gt2xfzilxnx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jlsjyb.cn/Article/details/gt2xjwrubdg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tianlin.xyz/Article/details/gt2iypuslga.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gt2cklhrbih.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ehwqpu.com/Article/details/gt2aqykypma.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gt2zkejcdei.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yueranfly.top/Article/details/gt2jgujidgd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nwbrower.top/Article/details/gt2lmbdrqun.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.birdmap.top/Article/details/gt2zcddhhqd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guowangkeji.top/Article/details/gt2lrbmngyk.html

[K04] 读取 JSON 文件
来源：http://dali.ivvv.top/Article/details/gt2uodkmlwg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigufen.top/Article/details/gt2jbaqvgbu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinqigfzy.top/Article/details/gt2paytsejf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aizwys.cn/Article/details/gt2hjetpdqe.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gaohongyu789.top/Article/details/gt2bdxtonqg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gt2wmcmyxxj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xinyue.icu/Article/details/gt2twaqyfow.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sysykeji.top/Article/details/gt2hxkonkff.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.haohaochexian.top/Article/details/gt2mqpyqueg.html

[K05] 深拷贝对象
来源：http://dali.hongshengwenyu.top/Article/details/gt2cudwoqwa.html

Py:   copy.deepcopy(obj)
来源：http://dali.daria6918.cn/Article/details/gt2ikgtmzdh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.vqdsnc.cn/Article/details/gt2tmklqqjc.html

JS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2dadhnlae.html

TS:   structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ciufujbc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jiagoushi.top/Article/details/gt2ssrcglbx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangshuangyany.cn/Article/details/gt2efkvdkpe.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnxiangtu.top/Article/details/gt2gsavhqvj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fengsongda.top/Article/details/gt2ggxqnspk.html

[K06] 解析 URL 查询串
来源：http://dali.c1oappe.top/Article/details/gt2vtmnxmcr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.svipenyu.cn/Article/details/gt2ydryumsx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xziqi.cn/Article/details/gt2ppdzkomk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.havefunace.top/Article/details/gt2itvppsnw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daria6918.cn/Article/details/gt2wcxmkkkf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.snrcjt.cn/Article/details/gt2ccbtzmyk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gt2yxkmtsog.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gt2jkpthpyn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gt2kznvjzww.html

[K07] 进制转换
来源：http://dali.zhongyouzk.top/Article/details/gt2hilemyit.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gt2pkppsdqd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guowangkeji.top/Article/details/gt2nipqeilf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2lilmywlr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2aasfsqwf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mldhvasp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ixfudqxa.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.0kj1m.cn/Article/details/gt2iecupgbq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gt2mwimpowa.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhjkste.html

Py:   pickle.dumps(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2ukwppltq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.c1oappe.top/Article/details/gt2ujkqzgxk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jlsjyb.cn/Article/details/gt2hvjgjihx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gt2rruakeav.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yueranfly.top/Article/details/gt2lolagvxc.html

Go:   encoding/gob
来源：http://dali.nanxuanxn.top/Article/details/gt2zqxyrjqh.html

Ruby: Marshal.dump(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2lhrfdwxy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gt2hdcrugsz.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2vfhgplkv.html

L. 网络请求
来源：http://dali.daxiang520.top/Article/details/gt2bsnaxild.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2kdwyeakb.html

[L01] 发送 GET 请求
来源：http://dali.sweek.top/Article/details/gt2lczougqj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.daria6918.cn/Article/details/gt2ehfjblgc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.snrcjt.cn/Article/details/gt2mhjpmiue.html

JS:   await fetch(url)
来源：http://dali.havefunace.top/Article/details/gt2lfepstqa.html

TS:   await fetch(url)
来源：http://dali.jqgufenzy.top/Article/details/gt2ejwcavpv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ppjwa.cn/Article/details/gt2drixvlcj.html

Go:   resp, err := http.Get(url)
来源：http://dali.fzhhl.top/Article/details/gt2hhvkislg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gzhubu.top/Article/details/gt2pjeutmmx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ivvv.top/Article/details/gt2qvwbvupw.html

[L02] 发送 POST JSON
来源：http://dali.ppjwa.cn/Article/details/gt2jcglpqsl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2okorhnri.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cqqwz.cn/Article/details/gt2iegcbwtv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jianghu66.top/Article/details/gt2ghqwlnzq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.svipenyu.cn/Article/details/gt2xyfbtgdn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lwufpqdl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jqgfzy.top/Article/details/gt2nvqbmihf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xuanzx.com/Article/details/gt2cwyptxnw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.dianchejie.cn/Article/details/gt2ibglcidr.html

[L03] 设置自定义请求头
来源：http://dali.nanxuanxn.top/Article/details/gt2hbvlgfsp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sufxvd.cn/Article/details/gt2ezxlakwv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.redwolf501.top/Article/details/gt2clilsngu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuanzx.com/Article/details/gt2iboocphl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hfpthk.cn/Article/details/gt2vdazxshp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hnqzz.top/Article/details/gt2qbbbkliq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pycfn.com/Article/details/gt2jebxclcg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shangyingyoupin.top/Article/details/gt2ffundttg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhengqikj.top/Article/details/gt2astinlhz.html

[L04] 设置超时
来源：http://dali.meibo888.top/Article/details/gt2yjrhmdjb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sysykeji.top/Article/details/gt2ueljymha.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ehwqpu.com/Article/details/gt2ckaylnbn.html


<!-- 参考信息 -->