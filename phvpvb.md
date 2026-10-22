代发 wailian999

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gt2oulbyque.html

[H04] 自定义异常类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ftsavkup.html

Py:   class MyError(Exception): pass
来源：http://dali.shzxlz.cn/Article/details/gt2vgeaevpx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gt2apexzthc.html

JS:   class MyError extends Error {}
来源：http://dali.cqqwz.cn/Article/details/gt2mkgsbgyb.html

TS:   class MyError extends Error {}
来源：http://dali.sweek.top/Article/details/gt2lkoofpvf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gt2affhddar.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jianghu66.top/Article/details/gt2uexzdipt.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pinlgszm.html

C#:   class MyException : Exception {}
来源：http://dali.jyoumei.cn/Article/details/gt2cpwkflxc.html

[H05] 捕获特定类型
来源：http://dali.cashguo.top/Article/details/gt2ocbgxtab.html

Py:   except ValueError as e:
来源：http://dali.zhiwuduotai.top/Article/details/gt2vyxeaiqw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cucudq.cn/Article/details/gt2scybtqch.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sysykeji.top/Article/details/gt2tmeqedef.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shzxlz.cn/Article/details/gt2erdyvjpg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2rodbdcsy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gotoacloud.top/Article/details/gt2okusashb.html

Ruby: rescue ArgumentError => e
来源：http://dali.hnqzz.top/Article/details/gt2fayrohpd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hammf.cn/Article/details/gt2faepcbek.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dashuyun.cn/Article/details/gt2etnfjuoe.html

Py:   value = d.get("k") or default
来源：http://dali.bjfxy.top/Article/details/gt2vdogdrpl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sweek.top/Article/details/gt2thkgamyj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gt2axvrvxcc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gt2dsvkactk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ppjwa.cn/Article/details/gt2kaunpbwk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ayrarrfh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenlongwang.top/Article/details/gt2rqpmrhqy.html

C#:   obj?.A?.B ?? default
来源：http://dali.hywenlv.cn/Article/details/gt2lvnnhzbv.html

[H07] 断言
来源：http://dali.yj20258888.top/Article/details/gt2kqgstbpe.html

Py:   assert x > 0, "必须为正"
来源：http://dali.316326.xyz/Article/details/gt2oaysiemg.html

PHP:  assert($x > 0);
来源：http://dali.pycfn.com/Article/details/gt2atoumcgv.html

JS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gt2ztpyoyrb.html

TS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lxilejlf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gotoacloud.top/Article/details/gt2slgwqoba.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yongpay.top/Article/details/gt2cphjzbmt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yongpay.top/Article/details/gt2qshhnvab.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jnhvzvko.html

[H08] 获取错误信息与堆栈
来源：http://dali.yvedp.cn/Article/details/gt2unjztxsi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cheryme.top/Article/details/gt2zefildob.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.mhx1999.top/Article/details/gt2adihnhkw.html

JS:   e.message;  e.stack
来源：http://dali.cqqwz.cn/Article/details/gt2zmefhmiw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yuxming.cn/Article/details/gt2eldqleco.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xinyue.icu/Article/details/gt2vqgfjjly.html

Go:   err.Error()
来源：http://dali.gaohongyu789.top/Article/details/gt2ifthfzhm.html

Ruby: e.message;  e.backtrace
来源：http://dali.xuetiantiany.cn/Article/details/gt2xcvibfur.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj202588.top/Article/details/gt2cbqfweij.html

[H09] 带错误码的异常
来源：http://dali.mhx1999.top/Article/details/gt2drudtprm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ppjwa.cn/Article/details/gt2agrvdiiz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangshuangyany.cn/Article/details/gt2xvxcqxzb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pengpengdd.cyou/Article/details/gt2zothtrma.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jyoumei.cn/Article/details/gt2hedxaray.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.fzhhl.top/Article/details/gt2ueqrissw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yongpay.top/Article/details/gt2asgmcwnc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.andypj.xyz/Article/details/gt2pmexsvmr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hywenlv.cn/Article/details/gt2aohgbhcj.html

[H10] 资源自动释放
来源：http://dali.daria6918.cn/Article/details/gt2rlbsywya.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.havefunace.top/Article/details/gt2mtbpvlcc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.guowangkeji.top/Article/details/gt2wudmrnmp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenjidiqi.icu/Article/details/gt2notfwtki.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pycfn.com/Article/details/gt2ppizlnjr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenlongwang.top/Article/details/gt2fsooilfr.html

Go:   defer f.Close()
来源：http://dali.cashguo.top/Article/details/gt2zdidipzg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.svipenyu.cn/Article/details/gt2lkroksqj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2zlksewjd.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2cuqvceup.html

I. 正则表达式
来源：http://dali.aibaodan.cn/Article/details/gt2kkxzttnu.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2odgjbezc.html

[I01] 判断是否匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2nuoazrqt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gt2rwhawges.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2oqcrzgdm.html

JS:   /\d+/.test(s)
来源：http://dali.yangfankeji.com/Article/details/gt2kdszfcac.html

TS:   /\d+/.test(s)
来源：http://dali.zycfv.cn/Article/details/gt2gddwspgw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.bjfxy.top/Article/details/gt2luxjkguw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vmfkknru.html

Ruby: s.match?(/\d+/)
来源：http://dali.cashguo.top/Article/details/gt2lvkfmvlu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenjidiqi.icu/Article/details/gt2vygsqwoi.html

[I02] 提取所有匹配
来源：http://dali.iojbl.cn/Article/details/gt2ykrxptjv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gt2wgjzxldb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sxryk.cn/Article/details/gt2podyllhz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zdqjudy.top/Article/details/gt2etkkwkjk.html

TS:   s.match(/\d+/g)
来源：http://dali.xylfe.cn/Article/details/gt2vkxrxoni.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ppjwa.cn/Article/details/gt2hbnyzecz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gt2qwnepwea.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2iggshjks.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.mhx1999.top/Article/details/gt2opoyplxx.html

[I03] 提取捕获分组
来源：http://dali.ehwqpu.com/Article/details/gt2cxwmveyy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenzaomai.com/Article/details/gt2cbiltlvt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.kuanghao11.cn/Article/details/gt2vfjlzzpn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yuxming.cn/Article/details/gt2qhehlozp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigufen.top/Article/details/gt2fmikyxpm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinqigufen.top/Article/details/gt2cyjfaipp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinqigufen.top/Article/details/gt2yxjynhke.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sysykeji.top/Article/details/gt2jhkhzgtl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xvqrxoei.html

[I04] 正则替换
来源：http://dali.daria6918.cn/Article/details/gt2ofpihwkn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2efdzyvul.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2ouwczlsk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gt2ktthjjby.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ttpmwmpc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.dashuyun.cn/Article/details/gt2beoojbjl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xylfe.cn/Article/details/gt2ojkxwarl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cashguo.top/Article/details/gt2esbuygwp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yangfankeji.com/Article/details/gt2eqjpqwtw.html

[I05] 按正则拆分
来源：http://dali.jlsjyb.cn/Article/details/gt2jjmzlizt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gaohongyu789.top/Article/details/gt2cenntahr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2uwyjwudz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gt2nqnfevaz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wnchwdiu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yueranfly.top/Article/details/gt2obqkygbd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ivvv.top/Article/details/gt2hokopyje.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gt2agugvydb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cashguo.top/Article/details/gt2cuisanee.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pycfn.com/Article/details/gt2xhddiqkg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gt2qspukiij.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nlivxvmv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gt2xbfavmdq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangshuangyany.cn/Article/details/gt2jkkkonsr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.meibo888.top/Article/details/gt2rdlbuqxj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daria6918.cn/Article/details/gt2qvqyvipc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.aibaodan.cn/Article/details/gt2otzywiyp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sweek.top/Article/details/gt2jntzsxbz.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhongyouzk.top/Article/details/gt2qtscvewh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hfpthk.cn/Article/details/gt2nmpxtysn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kepsafsj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gaohongyu789.top/Article/details/gt2mupzufzn.html

TS:   /error/gim
来源：http://dali.sufxvd.cn/Article/details/gt2rolpvbgt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.dashuyun.cn/Article/details/gt2zdrzkxrf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ehwqpu.com/Article/details/gt2xzwgmxsq.html

Ruby: s.scan(/error/i)
来源：http://dali.fengsongda.top/Article/details/gt2qrisguej.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.daria6918.cn/Article/details/gt2omtqymmh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cjgvxvyq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.aizwys.cn/Article/details/gt2amciaond.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gt2hnatctak.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nwbrower.top/Article/details/gt2lgbuqrzh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gt2lelmdsvj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sysykeji.top/Article/details/gt2riunugzy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhongyouzk.top/Article/details/gt2bnrxplxl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mslffqya.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gt2efkovyob.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fxqnjoll.html

J. 日期与时间
来源：http://dali.316326.xyz/Article/details/gt2cgzohjra.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2ppebiugu.html

[J01] 获取当前时间
来源：http://dali.xinyue.icu/Article/details/gt2mzdnyiku.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.c1oappe.top/Article/details/gt2cwrcawvm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gt2kzdmqlec.html

JS:   new Date();  Date.now()
来源：http://dali.c1oappe.top/Article/details/gt2hlewedla.html

TS:   new Date();  Date.now()
来源：http://dali.hnqzz.top/Article/details/gt2xdrnpiyx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenzaomai.com/Article/details/gt2vmkoakrv.html

Go:   time.Now()
来源：http://dali.jqgfzy.top/Article/details/gt2rloqgkqq.html

Ruby: Time.now
来源：http://dali.cucudq.cn/Article/details/gt2qxmcaduq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigufen.top/Article/details/gt2gwtoviyg.html

[J02] 格式化输出
来源：http://dali.yj202588.top/Article/details/gt2gmjvjkhw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gt2sdhedkds.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jiagoushi.top/Article/details/gt2tzttptoe.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2afjsqobo.html

TS:   d.toISOString()
来源：http://dali.316326.xyz/Article/details/gt2rkpcljbw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.wangdashe.top/Article/details/gt2okqyfoth.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nanxinkj.top/Article/details/gt2qjxcojwk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tanke756.top/Article/details/gt2efnrhivl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nmqtrhcb.html

[J03] 字符串解析为日期
来源：http://dali.guannengcc.top/Article/details/gt2djxuxyew.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xylfe.cn/Article/details/gt2vlptiwsb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sufxvd.cn/Article/details/gt2znbczjor.html

JS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gt2tgxzhoza.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gt2bgqwcqkl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gt2onzkqygq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gt2dheqziqo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gt2vgaiwbmp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.snrcjt.cn/Article/details/gt2kdaggyjv.html

[J04] 时间戳与日期互转
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vaewdoja.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yangfankeji.com/Article/details/gt2dkeermph.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.havefunace.top/Article/details/gt2zsasullp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigfzy.top/Article/details/gt2jlhunujt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.316326.xyz/Article/details/gt2bvsaiweb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yonumen.top/Article/details/gt2gjdthzvi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2unygdccb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cashguo.top/Article/details/gt2fyqnilkg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258.top/Article/details/gt2dbjivsmf.html

[J05] 时间加减（加 7 天）
来源：http://dali.gogol.net.cn/Article/details/gt2njoovlzk.html

Py:   now + timedelta(days=7)
来源：http://dali.fzhhl.top/Article/details/gt2tmadsjok.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.feifeiyinyue.top/Article/details/gt2dyyhnpvf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zycfv.cn/Article/details/gt2dcsrtigv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cashguo.top/Article/details/gt2wikmprcn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gt2lblakbay.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xmwvcsag.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ydzc1.top/Article/details/gt2kmhenihq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.redwolf501.top/Article/details/gt2ghjbeyaz.html

[J06] 计算两时间之差
来源：http://dali.yj20258888.top/Article/details/gt2qdyuugcb.html

Py:   (end - start).total_seconds()
来源：http://dali.pengpengdd.cyou/Article/details/gt2vheqyutf.html

PHP:  $end->diff($start)->days;
来源：http://dali.aibaodan.cn/Article/details/gt2fxgnwnkb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgufenzy.top/Article/details/gt2kcbljvbc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ehwqpu.com/Article/details/gt2aagqjijk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hnqzz.top/Article/details/gt2ithucwpf.html

Go:   end.Sub(start).Hours()
来源：http://dali.meibo888.top/Article/details/gt2mkeerhve.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ehwqpu.com/Article/details/gt2wmmqwmyk.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinqigfzy.top/Article/details/gt2szwnlgra.html

[J07] 比较两个日期
来源：http://dali.ppjwa.cn/Article/details/gt2foajvdcv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gt2ivjcjvse.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ynhqbgwf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cucudq.cn/Article/details/gt2sotjtark.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.redwolf501.top/Article/details/gt2ilrroyqy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shuidangran.top/Article/details/gt2bcgicfhp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jztvqska.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gt2lyxbevdb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gt2faqufafl.html

[J08] 提取年月日与星期
来源：http://dali.aizwys.cn/Article/details/gt2zaibumrf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.daria6918.cn/Article/details/gt2yfnvxdhi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.svipenyu.cn/Article/details/gt2onqzpjai.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.quarkkingdee.top/Article/details/gt2xtbbcqbq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.kuanghao11.cn/Article/details/gt2xusxothy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cashguo.top/Article/details/gt2kvvsfkon.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.wangshuangyany.cn/Article/details/gt2zetuueah.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgfzy.top/Article/details/gt2njqahjeq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ikwzfktk.html

[J09] 时区处理
来源：http://dali.dashuyun.cn/Article/details/gt2tyulynij.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxuanxn.top/Article/details/gt2gosmeyxg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shzxlz.cn/Article/details/gt2griszzqu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gjsrqvvz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gt2wzpaimha.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xinyue.icu/Article/details/gt2abazxmzo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigufen.top/Article/details/gt2ifhviqun.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gdvquwfq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jianghu66.top/Article/details/gt2wlvxopmr.html

[J10] 取今天 / 本月第一天
来源：http://dali.cheryme.top/Article/details/gt2tvoydqmb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.smart0.xyz/Article/details/gt2cgnfpuaw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xuetiantiany.cn/Article/details/gt2jitxyjrj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xuanzx.com/Article/details/gt2cjoeoqrt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2plqweqqe.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.smart0.xyz/Article/details/gt2ycmbaldm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xziqi.cn/Article/details/gt2rknyomef.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jqgufenzy.top/Article/details/gt2aqykcurt.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hfpthk.cn/Article/details/gt2zthxnupa.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2mscfdttv.html

K. JSON 与序列化
来源：http://dali.yvedp.cn/Article/details/gt2tuwhksbf.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2pagqwbzl.html

[K01] 对象转 JSON 字符串
来源：http://dali.shzxlz.cn/Article/details/gt2qvckcdtg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ehwqpu.com/Article/details/gt2jorfoheh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.daria6918.cn/Article/details/gt2tkpnxyuk.html

JS:   JSON.stringify(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2tpkzwqus.html

TS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2urxslfwt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.meibo888.top/Article/details/gt2guyiprec.html

Go:   json.Marshal(obj)
来源：http://dali.sweek.top/Article/details/gt2hkohjqyq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sweek.top/Article/details/gt2bwgvqefn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2aanenegw.html

[K02] JSON 字符串转对象
来源：http://dali.hfpthk.cn/Article/details/gt2ejfspnpr.html

Py:   json.loads(s)
来源：http://dali.aibaodan.cn/Article/details/gt2beofuvan.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cheryme.top/Article/details/gt2ajcuricu.html

JS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gt2tixheufw.html

TS:   JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gt2dgcmvdeb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.meibo888.top/Article/details/gt2kogupmkg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wxgpvpgx.html

Ruby: JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qmjiguhu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pycfn.com/Article/details/gt2qylrroun.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dtrzxwnq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gt2gzkenhof.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gt2buokafbu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gt2tnxfpplh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258.top/Article/details/gt2owluglru.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fengsongda.top/Article/details/gt2mbzyxvfe.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ycukesad.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.316326.xyz/Article/details/gt2ugdgqkul.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ppjwa.cn/Article/details/gt2fowpmtmw.html

[K04] 读取 JSON 文件
来源：http://dali.cheryme.top/Article/details/gt2wdmrgols.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangdashe.top/Article/details/gt2trftompj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.daxiang520.top/Article/details/gt2xehkxvip.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nwbrower.top/Article/details/gt2jvudjied.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2limywfhy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gt2znnuriua.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jqgufenzy.top/Article/details/gt2htiubmqi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.iojbl.cn/Article/details/gt2ocacuarh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.mhx1999.top/Article/details/gt2wuzcpfvg.html

[K05] 深拷贝对象
来源：http://dali.jiagoushi.top/Article/details/gt2vsovkbru.html

Py:   copy.deepcopy(obj)
来源：http://dali.iojbl.cn/Article/details/gt2ljvspvxo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.pycfn.com/Article/details/gt2uvclqgbd.html

JS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2uqemmwso.html

TS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2faaokloa.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenzaomai.com/Article/details/gt2btkxcnbr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tanke756.top/Article/details/gt2tctvxcan.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhixingplan.top/Article/details/gt2gitafflc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ehwqpu.com/Article/details/gt2oocjuzbx.html

[K06] 解析 URL 查询串
来源：http://dali.kuanghao11.cn/Article/details/gt2iojjxamj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ogthnwik.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.haohaochexian.top/Article/details/gt2gkwafcup.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gt2gokheprv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jyoumei.cn/Article/details/gt2ntwzypit.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ppjwa.cn/Article/details/gt2kpgokfyf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gt2ackfauxr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gt2kuvsvejf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gt2lpmdbaor.html

[K07] 进制转换
来源：http://dali.yonumen.top/Article/details/gt2yhkbeelt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gt2culomsii.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hysaishi.cn/Article/details/gt2vaqbujqm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gt2ouyymrew.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gt2eyabfouu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gt2fnnlzcpt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hnxiangtu.top/Article/details/gt2hnbvlome.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daria6918.cn/Article/details/gt2xlwpbxmr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2qreslxbb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.haohaochexian.top/Article/details/gt2misewxjq.html

Py:   pickle.dumps(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2atzqwehl.html


<!-- 参考信息 -->