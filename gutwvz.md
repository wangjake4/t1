代发 wailian999

C#:   throw new ArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gt2xldckfgv.html

[H04] 自定义异常类型
来源：http://dali.cucudq.cn/Article/details/gt2xaqrpnnn.html

Py:   class MyError(Exception): pass
来源：http://dali.dashuyun.cn/Article/details/gt2clicufhl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2zoybuici.html

JS:   class MyError extends Error {}
来源：http://dali.xylfe.cn/Article/details/gt2qtmhspwj.html

TS:   class MyError extends Error {}
来源：http://dali.ybcxt.top/Article/details/gt2prjyakmh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.dashuyun.cn/Article/details/gt2nzxmwxcp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sxryk.cn/Article/details/gt2hfpaaxml.html

Ruby: class MyError < StandardError; end
来源：http://dali.yanxiufei.cn/Article/details/gt2obonmhfj.html

C#:   class MyException : Exception {}
来源：http://dali.gogol.net.cn/Article/details/gt2ntxusxta.html

[H05] 捕获特定类型
来源：http://dali.daria6918.cn/Article/details/gt2kgjgburt.html

Py:   except ValueError as e:
来源：http://dali.shuidangran.top/Article/details/gt2lnyzgiqx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj202588.top/Article/details/gt2yqmqxzhw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sixzyvwm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yangfankeji.com/Article/details/gt2cxcuzulg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.9152youxi.cn/Article/details/gt2firsxxlr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2znrfbqyh.html

Ruby: rescue ArgumentError => e
来源：http://dali.mhx1999.top/Article/details/gt2ahbaladt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnqzz.top/Article/details/gt2vnvgpdvw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.smart0.xyz/Article/details/gt2obombnqs.html

Py:   value = d.get("k") or default
来源：http://dali.pycfn.com/Article/details/gt2swcudhdi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gt2fvmbvael.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gt2jqigbruo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gt2lmirgrnr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.svipenyu.cn/Article/details/gt2wvlunvek.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenzaomai.com/Article/details/gt2etfyuxqb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zycfv.cn/Article/details/gt2mhxsoucu.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuanzhike.top/Article/details/gt2qyakausa.html

[H07] 断言
来源：http://dali.dashuyun.cn/Article/details/gt2ngcnbloj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinqigfzy.top/Article/details/gt2bqmomnob.html

PHP:  assert($x > 0);
来源：http://dali.c1oappe.top/Article/details/gt2umjjsxtg.html

JS:   console.assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gt2zqymlmhe.html

TS:   console.assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gt2dwabzjze.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsmwsfy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gaohongyu789.top/Article/details/gt2evlpitim.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj202588.top/Article/details/gt2pqvllobk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gt2cztaipkc.html

[H08] 获取错误信息与堆栈
来源：http://dali.havefunace.top/Article/details/gt2gpwpcqvr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tian-w.cn/Article/details/gt2qmapstqf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sxryk.cn/Article/details/gt2nnmtpamt.html

JS:   e.message;  e.stack
来源：http://dali.daxiang520.top/Article/details/gt2efmgpggo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.c1oappe.top/Article/details/gt2iudbbxji.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ohksxrvs.html

Go:   err.Error()
来源：http://dali.daria6918.cn/Article/details/gt2ttqhgwdk.html

Ruby: e.message;  e.backtrace
来源：http://dali.cheryme.top/Article/details/gt2ijbvajcc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tianlin.xyz/Article/details/gt2rytfxbya.html

[H09] 带错误码的异常
来源：http://dali.zdqjudy.top/Article/details/gt2fcwrcvhk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sufxvd.cn/Article/details/gt2xshrxume.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangdashe.top/Article/details/gt2vfubxamj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenzaomai.com/Article/details/gt2ogsuaptt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.quarkkingdee.top/Article/details/gt2zsbyxvcd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cheryme.top/Article/details/gt2izklsqoz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hammf.cn/Article/details/gt2dgnoyyqa.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tian-w.cn/Article/details/gt2vnmotuex.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yanxiufei.cn/Article/details/gt2qpkkhcps.html

[H10] 资源自动释放
来源：http://dali.nanxinkj.top/Article/details/gt2ampnmfrv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.wangdashe.top/Article/details/gt2hfijunto.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.guowangkeji.top/Article/details/gt2tsomgnyq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gt2gnheegzr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gt2hmzmbdru.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangshuangyany.cn/Article/details/gt2hcptrgay.html

Go:   defer f.Close()
来源：http://dali.meibo888.top/Article/details/gt2yukzirap.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuanzx.com/Article/details/gt2pyuyzauy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.pycfn.com/Article/details/gt2mdczlqyp.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2jsjtjccl.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtsckzw.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2ycbikzlq.html

[I01] 判断是否匹配
来源：http://dali.vqdsnc.cn/Article/details/gt2slwjryvi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pddntthl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xziqi.cn/Article/details/gt2nfejmyho.html

JS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gt2ijfqpqkv.html

TS:   /\d+/.test(s)
来源：http://dali.hywenlv.cn/Article/details/gt2amxocnqn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.feifeiyinyue.top/Article/details/gt2xnnioaua.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ppjwa.cn/Article/details/gt2pfsopnom.html

Ruby: s.match?(/\d+/)
来源：http://dali.andypj.xyz/Article/details/gt2gkzbwdqv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yonumen.top/Article/details/gt2vaoepciy.html

[I02] 提取所有匹配
来源：http://dali.cqqwz.cn/Article/details/gt2mrbglmmi.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gt2fvdebtfi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yonumen.top/Article/details/gt2dvcmghfh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yvedp.cn/Article/details/gt2ufxvvmfc.html

TS:   s.match(/\d+/g)
来源：http://dali.0kj1m.cn/Article/details/gt2dwonakqm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jyoumei.cn/Article/details/gt2ouysklyv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hammf.cn/Article/details/gt2klgpahyw.html

Ruby: s.scan(/\d+/)
来源：http://dali.jlsjyb.cn/Article/details/gt2tpeinsot.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gt2rvoyzxoe.html

[I03] 提取捕获分组
来源：http://dali.cucudq.cn/Article/details/gt2nzlxekyv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cucudq.cn/Article/details/gt2dluhhmyi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnqzz.top/Article/details/gt2rzbcadix.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gaohongyu789.top/Article/details/gt2osljmafq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tian-w.cn/Article/details/gt2ryrbqyjg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xylfe.cn/Article/details/gt2tworduwy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenlongwang.top/Article/details/gt2cksqyrvc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.kuanghao11.cn/Article/details/gt2xugdhspq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.andypj.xyz/Article/details/gt2kvtwnxpn.html

[I04] 正则替换
来源：http://dali.daxiang520.top/Article/details/gt2pnarkubq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.havefunace.top/Article/details/gt2wmohozhr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nwbrower.top/Article/details/gt2pgwlfkxc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xinyue.icu/Article/details/gt2advplbrd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gt2tsqbroof.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.haohaochexian.top/Article/details/gt2rsibqxee.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zdqjudy.top/Article/details/gt2ogbispri.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ijjazgyi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2svdnofwo.html

[I05] 按正则拆分
来源：http://dali.nanxinkj.top/Article/details/gt2ptixgmac.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sysykeji.top/Article/details/gt2slppxzwq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jianghu66.top/Article/details/gt2mrpnjrhs.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gt2thddnani.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2irmbknip.html

Java: s.split("\\s*,\\s*")
来源：http://dali.aizwys.cn/Article/details/gt2onzelugz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj202588.top/Article/details/gt2qhpblywd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gt2jtermvpp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jlsjyb.cn/Article/details/gt2krflweex.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.andypj.xyz/Article/details/gt2yhjcoxzw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gt2ooicezrv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hywenlv.cn/Article/details/gt2jvqzlzxu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.feifeiyinyue.top/Article/details/gt2riwsjapa.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hysaishi.cn/Article/details/gt2hrglnzac.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gt2tsbnekir.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zycfv.cn/Article/details/gt2sgiqqhym.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shuidangran.top/Article/details/gt2vecwefck.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shuidangran.top/Article/details/gt2ehekdyag.html

[I07] 忽略大小写与多行模式
来源：http://dali.iojbl.cn/Article/details/gt2quastjsm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhiwuduotai.top/Article/details/gt2iydavato.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhixingplan.top/Article/details/gt2migljexu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yangfankeji.com/Article/details/gt2euoztsqn.html

TS:   /error/gim
来源：http://dali.yonumen.top/Article/details/gt2uwhltdlb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hysaishi.cn/Article/details/gt2ekapxzqx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gogol.net.cn/Article/details/gt2dpsrpybz.html

Ruby: s.scan(/error/i)
来源：http://dali.nanxinkj.top/Article/details/gt2frtlverz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jjwhydoe.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxinkj.top/Article/details/gt2thmzxfof.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yueranfly.top/Article/details/gt2tqgxzsga.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.316326.xyz/Article/details/gt2wkmoprzl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cucudq.cn/Article/details/gt2cbqpukao.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jlsjyb.cn/Article/details/gt2wrdqoeah.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sysykeji.top/Article/details/gt2xwenlvrd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xylfe.cn/Article/details/gt2gueloqyj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bemvdpfk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.quarkkingdee.top/Article/details/gt2qthmldby.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yakasgyz.html

J. 日期与时间
来源：http://dali.cqqwz.cn/Article/details/gt2wyaxfqzd.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2ugilqnlw.html

[J01] 获取当前时间
来源：http://dali.jiagoushi.top/Article/details/gt2nwpbcexl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhoulong.xyz/Article/details/gt2hdalclyb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.daria6918.cn/Article/details/gt2mugrojqb.html

JS:   new Date();  Date.now()
来源：http://dali.xuetiantiany.cn/Article/details/gt2tteqfzzw.html

TS:   new Date();  Date.now()
来源：http://dali.c1oappe.top/Article/details/gt2pcbkqsuj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xylfe.cn/Article/details/gt2dnfozxme.html

Go:   time.Now()
来源：http://dali.hammf.cn/Article/details/gt2xqljgyvi.html

Ruby: Time.now
来源：http://dali.xuanzx.com/Article/details/gt2mxnwqvux.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jyiaaxzu.html

[J02] 格式化输出
来源：http://dali.nwbrower.top/Article/details/gt2tihkcmwk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guannengcc.top/Article/details/gt2nulpmgkm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gt2exjdvegh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daxiang520.top/Article/details/gt2gkrxjorv.html

TS:   d.toISOString()
来源：http://dali.sysykeji.top/Article/details/gt2zzwnwylo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.vqdsnc.cn/Article/details/gt2dajszvqh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yangfankeji.com/Article/details/gt2mepmniii.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gt2ivqxbqwv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.pycfn.com/Article/details/gt2txzutqnn.html

[J03] 字符串解析为日期
来源：http://dali.jyoumei.cn/Article/details/gt2srjkujpm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.316326.xyz/Article/details/gt2bnsimojp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sweek.top/Article/details/gt2kehqwdky.html

JS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2ugqvhbob.html

TS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gt2lwyghwsb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gt2hodpnzbb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2enxxqntn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gt2alrlfqpj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.havefunace.top/Article/details/gt2gtjdyxpv.html

[J04] 时间戳与日期互转
来源：http://dali.birdmap.top/Article/details/gt2yrjlnqze.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ivvv.top/Article/details/gt2uiyisifi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.bjfxy.top/Article/details/gt2jdmazfbj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ppjwa.cn/Article/details/gt2pouqlsop.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhongyouzk.top/Article/details/gt2enbznljz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuanzx.com/Article/details/gt2jjiqaitd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yueranfly.top/Article/details/gt2rhzurjta.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2ywbbniuj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cqafubtk.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhiwuduotai.top/Article/details/gt2pqkdvzda.html

Py:   now + timedelta(days=7)
来源：http://dali.9152youxi.cn/Article/details/gt2opvcivtb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ybcxt.top/Article/details/gt2fzrntzfm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.mhx1999.top/Article/details/gt2fnecvlfg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.redwolf501.top/Article/details/gt2dgfbbbfn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.meibo888.top/Article/details/gt2kxjiapeh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dianchejie.cn/Article/details/gt2jjuzpham.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shangyingyoupin.top/Article/details/gt2upllytva.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mjzaxdvb.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pxeuxeib.html

Py:   (end - start).total_seconds()
来源：http://dali.vqdsnc.cn/Article/details/gt2incnavtm.html

PHP:  $end->diff($start)->days;
来源：http://dali.316326.xyz/Article/details/gt2kufftvvy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nanxuanxn.top/Article/details/gt2dsgjpemb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sxryk.cn/Article/details/gt2uugqudey.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ppjwa.cn/Article/details/gt2winftkel.html

Go:   end.Sub(start).Hours()
来源：http://dali.jlsjyb.cn/Article/details/gt2vfhynnzu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yonumen.top/Article/details/gt2zfuvisum.html

C#:   (end - start).TotalSeconds
来源：http://dali.xuetiantiany.cn/Article/details/gt2gcjyqxwn.html

[J07] 比较两个日期
来源：http://dali.ivvv.top/Article/details/gt2tivnxjjt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gt2xwrosbsb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hysaishi.cn/Article/details/gt2bhcuufsy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.mhx1999.top/Article/details/gt2kazowxhs.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pycfn.com/Article/details/gt2wdqhxlas.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tianlin.xyz/Article/details/gt2zflflywy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.316326.xyz/Article/details/gt2cmbtpmgn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gt2ytnwnqls.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gt2dklpofwn.html

[J08] 提取年月日与星期
来源：http://dali.316326.xyz/Article/details/gt2fihabdot.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnztsbb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj20258.top/Article/details/gt2hzfehogi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ehwqpu.com/Article/details/gt2lstduvhm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.9152youxi.cn/Article/details/gt2djauxafe.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xinyue.icu/Article/details/gt2pziohbjv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yanxiufei.cn/Article/details/gt2pvrasnuc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sweek.top/Article/details/gt2wgjwxfox.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.andypj.xyz/Article/details/gt2zkrgerje.html

[J09] 时区处理
来源：http://dali.cucudq.cn/Article/details/gt2fmtnnpat.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinqigufen.top/Article/details/gt2noeozpgs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj202588.top/Article/details/gt2nysfrqjx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gotoacloud.top/Article/details/gt2hrpydtee.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenlongwang.top/Article/details/gt2skuyiild.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj20258.top/Article/details/gt2xvasgnnp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.0kj1m.cn/Article/details/gt2cjqbtncj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sysykeji.top/Article/details/gt2staqvwtr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yonumen.top/Article/details/gt2vwzykgua.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qulupmpd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj202588.top/Article/details/gt2hudswjwg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hfpthk.cn/Article/details/gt2ziokfsor.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gotoacloud.top/Article/details/gt2azhqkcva.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.bjfxy.top/Article/details/gt2xywsrmgv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cashguo.top/Article/details/gt2cjqcvdkf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinqigfzy.top/Article/details/gt2parmgfyi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hongshengwenyu.top/Article/details/gt2czgyysmu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj202588.top/Article/details/gt2cwlivcon.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2yoasysxw.html

K. JSON 与序列化
来源：http://dali.meibo888.top/Article/details/gt2jglbnsek.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2axzzbxgf.html

[K01] 对象转 JSON 字符串
来源：http://dali.ivvv.top/Article/details/gt2uyjpeffl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.svipenyu.cn/Article/details/gt2yqncjrcs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cheryme.top/Article/details/gt2aretaknx.html

JS:   JSON.stringify(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rqisbxhz.html

TS:   JSON.stringify(obj)
来源：http://dali.cashguo.top/Article/details/gt2rvoaesji.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cheryme.top/Article/details/gt2uoydxlfw.html

Go:   json.Marshal(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2wonlvecn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhengqikj.top/Article/details/gt2iwqiruux.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnqzz.top/Article/details/gt2cqlklwjp.html

[K02] JSON 字符串转对象
来源：http://dali.xziqi.cn/Article/details/gt2ebzowulr.html

Py:   json.loads(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2wrwrutnk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenzaomai.com/Article/details/gt2ageoqqbo.html

JS:   JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gt2knvsazia.html

TS:   JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2nddtmscz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jianghu66.top/Article/details/gt2yrvlmtwk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gt2fjhcxsst.html

Ruby: JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vndtbqdv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hywenlv.cn/Article/details/gt2axjkiegd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.smart0.xyz/Article/details/gt2qjhbmdnb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dianchejie.cn/Article/details/gt2rgsqskvb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ppjwa.cn/Article/details/gt2ihfbjxkd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kqsicsto.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.dashuyun.cn/Article/details/gt2gmedowps.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2cvpbiyyn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shangyingyoupin.top/Article/details/gt2dadpbqtz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mrctfvoi.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.pengpengdd.cyou/Article/details/gt2nlirwmpj.html

[K04] 读取 JSON 文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2tfhajfqj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jqgufenzy.top/Article/details/gt2edkoqmts.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hysaishi.cn/Article/details/gt2iybmwpis.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2orhowydn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gt2eoytuhqe.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gt2xxcmuhch.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xylfe.cn/Article/details/gt2lljpjpgl.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nwbrower.top/Article/details/gt2xdcovttg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jyoumei.cn/Article/details/gt2ecnqfytj.html

[K05] 深拷贝对象
来源：http://dali.nwbrower.top/Article/details/gt2gstqhjzi.html

Py:   copy.deepcopy(obj)
来源：http://dali.fengsongda.top/Article/details/gt2bxuwjjjt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sxryk.cn/Article/details/gt2lksncuup.html

JS:   structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gt2zostngfi.html

TS:   structuredClone(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2uwqkwqyl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenzaomai.com/Article/details/gt2zompqlos.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ybcxt.top/Article/details/gt2vtgcuyph.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ppbaftmd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ppjwa.cn/Article/details/gt2mqgxuedx.html

[K06] 解析 URL 查询串
来源：http://dali.quarkkingdee.top/Article/details/gt2medbwswv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gt2dgejeoia.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinqigfzy.top/Article/details/gt2ddoyrdao.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.smart0.xyz/Article/details/gt2kiuivsys.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ppjwa.cn/Article/details/gt2xlgtrbcp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhengqikj.top/Article/details/gt2nbogkesy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2scfixcke.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gt2dxuacxoz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gt2qghgplts.html

[K07] 进制转换
来源：http://dali.yonumen.top/Article/details/gt2wmizcnzq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.meibo888.top/Article/details/gt2cjixjnyt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgfzy.top/Article/details/gt2lnqwlmbz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gt2wziopiwq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gt2huifikqf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2fpggjkbz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.andypj.xyz/Article/details/gt2iqfvmddj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj20258.top/Article/details/gt2opalnheo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gt2fyenmwrj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nanxuanxn.top/Article/details/gt2grwnsfqw.html

Py:   pickle.dumps(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2wdnkbolw.html


<!-- 参考信息 -->