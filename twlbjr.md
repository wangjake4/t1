代发 wailian999

[H03] 主动抛出异常
来源：http://dali.zhongyouzk.top/Article/details/gthnonpvph.html

Py:   raise ValueError("错误信息")
来源：http://dali.cucudq.cn/Article/details/gtagepaigm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtqwnlqyll.html

JS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtkeytthfq.html

TS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtryufrkhb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gtssuradvt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuanzx.com/Article/details/gtsbpfbszr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gtyntjwtev.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtckmozfuf.html

[H04] 自定义异常类型
来源：http://dali.tianlin.xyz/Article/details/gtfrilelfa.html

Py:   class MyError(Exception): pass
来源：http://dali.cqqwz.cn/Article/details/gtrypruzuv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.meibo888.top/Article/details/gtljsvaxky.html

JS:   class MyError extends Error {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjteebfgv.html

TS:   class MyError extends Error {}
来源：http://dali.hnxiangtu.top/Article/details/gtlhswdmpt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gthxgnmcwf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigfzy.top/Article/details/gtbuzggigw.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258.top/Article/details/gtvjrfxbca.html

C#:   class MyException : Exception {}
来源：http://dali.hysaishi.cn/Article/details/gtxsudnhwi.html

[H05] 捕获特定类型
来源：http://dali.kuanghao11.cn/Article/details/gtshdkrtaw.html

Py:   except ValueError as e:
来源：http://dali.cucudq.cn/Article/details/gtwlqyujry.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuanzhike.top/Article/details/gtzfcsqkgk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gtwwdqpuvn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqsriiui.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.haohaochexian.top/Article/details/gtyqduprvo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sysykeji.top/Article/details/gtsmcwbavh.html

Ruby: rescue ArgumentError => e
来源：http://dali.cashguo.top/Article/details/gticjtoybu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtmyhmtztb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sweek.top/Article/details/gtyjcajffw.html

Py:   value = d.get("k") or default
来源：http://dali.cucudq.cn/Article/details/gtehfgfgxn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gtvmmboaey.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shuidangran.top/Article/details/gtjrvcvrrf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuanzx.com/Article/details/gtfxqtwjii.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhengqikj.top/Article/details/gtgsggpwkl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nanxinkj.top/Article/details/gtwaqvxlhm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenlongwang.top/Article/details/gtwcwgmmbi.html

C#:   obj?.A?.B ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebsztspe.html

[H07] 断言
来源：http://dali.zhoulong.xyz/Article/details/gtgmxckkus.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yangfankeji.com/Article/details/gtzkztdnfh.html

PHP:  assert($x > 0);
来源：http://dali.jianghu66.top/Article/details/gtykalgwhw.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gtmndfyhjo.html

TS:   console.assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtjdxanemh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guannengcc.top/Article/details/gthtnatdbm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nwbrower.top/Article/details/gtfodkopwx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yonumen.top/Article/details/gtpcthjywq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtrqodnhpu.html

[H08] 获取错误信息与堆栈
来源：http://dali.yanxiufei.cn/Article/details/gtwffwockz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yangfankeji.com/Article/details/gtumpvtrtv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.dashuyun.cn/Article/details/gtvzifysmi.html

JS:   e.message;  e.stack
来源：http://dali.cashguo.top/Article/details/gtgcspwihy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yuanzhike.top/Article/details/gtdilmoylw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtarhqwpgh.html

Go:   err.Error()
来源：http://dali.hnxiangtu.top/Article/details/gtjxdvpzmr.html

Ruby: e.message;  e.backtrace
来源：http://dali.sysykeji.top/Article/details/gtscrhtrbq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yongpay.top/Article/details/gtvnwnujng.html

[H09] 带错误码的异常
来源：http://dali.hfpthk.cn/Article/details/gtoinpdhbl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.c1oappe.top/Article/details/gtdubkwzya.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258888.top/Article/details/gtrewzjfmd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangshuangyany.cn/Article/details/gtwofguqdd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvrydjss.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gogol.net.cn/Article/details/gtdyputhpn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.0kj1m.cn/Article/details/gtluzliryu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.snrcjt.cn/Article/details/gtekopvwqq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhengqikj.top/Article/details/gtzxiqowlv.html

[H10] 资源自动释放
来源：http://dali.yuanzhike.top/Article/details/gtxgofwrzd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.aizwys.cn/Article/details/gtolrlubmf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gotoacloud.top/Article/details/gtddarjdpw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xylfe.cn/Article/details/gtsqruilqk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gtfpepezua.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guowangkeji.top/Article/details/gtgabmjuut.html

Go:   defer f.Close()
来源：http://dali.zhoulong.xyz/Article/details/gtbnwyokub.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shzxlz.cn/Article/details/gtmsydyklf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yvedp.cn/Article/details/gttotjdpto.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtzbdoosbi.html

I. 正则表达式
来源：http://dali.hammf.cn/Article/details/gtylwizycv.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtoqigoehm.html

[I01] 判断是否匹配
来源：http://dali.daria6918.cn/Article/details/gtbfdxbmae.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jyoumei.cn/Article/details/gtspiaaqgg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.havefunace.top/Article/details/gtrnmuswxy.html

JS:   /\d+/.test(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwtwxuehs.html

TS:   /\d+/.test(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtndmxhfjv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.wangdashe.top/Article/details/gtrijjlzbe.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xinyue.icu/Article/details/gtfafvitnq.html

Ruby: s.match?(/\d+/)
来源：http://dali.zdqjudy.top/Article/details/gthqblfjrp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yueranfly.top/Article/details/gtegcagkfs.html

[I02] 提取所有匹配
来源：http://dali.dashuyun.cn/Article/details/gtsegmavvu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.bjfxy.top/Article/details/gtidpthaef.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sxryk.cn/Article/details/gtyzeenncz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ybcxt.top/Article/details/gtitwqpmlm.html

TS:   s.match(/\d+/g)
来源：http://dali.ehwqpu.com/Article/details/gtnwwkgdvd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yonumen.top/Article/details/gtfkltzlda.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gtavhvklwn.html

Ruby: s.scan(/\d+/)
来源：http://dali.jlsjyb.cn/Article/details/gtqjdcwucb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtyhqtxhlm.html

[I03] 提取捕获分组
来源：http://dali.quarkkingdee.top/Article/details/gtqkozfcbh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yonumen.top/Article/details/gthsafrzvy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aizwys.cn/Article/details/gtpqsfesyz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.c1oappe.top/Article/details/gtfuilrpue.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sxryk.cn/Article/details/gthhmijeam.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yueranfly.top/Article/details/gthwgicdhu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zdqjudy.top/Article/details/gtsgolvugy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinqigufen.top/Article/details/gtcatjvrcr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nanxuanxn.top/Article/details/gtpfhbeftq.html

[I04] 正则替换
来源：http://dali.shuidangran.top/Article/details/gtcilbkrnl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjaukobwn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqepcakb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ydzc1.top/Article/details/gtokruiiuk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yongpay.top/Article/details/gtgopbvabl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj20258888.top/Article/details/gthuganfhc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daxiang520.top/Article/details/gtcraxprbt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtsdciowpw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.bjfxy.top/Article/details/gtuzykgnhh.html

[I05] 按正则拆分
来源：http://dali.yongpay.top/Article/details/gtqxbvpnlz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hammf.cn/Article/details/gtxxmunsdr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqgvinyyy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gtoedvkrsb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gtwtkbuilc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hfpthk.cn/Article/details/gtoihbtzmc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gtorwvvbbj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gthhywdsos.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aibaodan.cn/Article/details/gtxjppinoq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jianghu66.top/Article/details/gtspjjjpws.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gtgfbqxaja.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuanzhike.top/Article/details/gtoiezliwm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sxryk.cn/Article/details/gtqtuecuxj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gtoisywsoo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.meibo888.top/Article/details/gtldjdilnz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.andypj.xyz/Article/details/gtxjlifyjd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.aizwys.cn/Article/details/gtaklbfdmt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gtthoxfqom.html

[I07] 忽略大小写与多行模式
来源：http://dali.zycfv.cn/Article/details/gtmnswuusy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shzxlz.cn/Article/details/gtqzmeqrmj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yangfankeji.com/Article/details/gtkzqehmqb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.9152youxi.cn/Article/details/gtemoyvfkp.html

TS:   /error/gim
来源：http://dali.hywenlv.cn/Article/details/gtjfndkbrb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.fengsongda.top/Article/details/gtxrtssqnl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.guowangkeji.top/Article/details/gtedigwoed.html

Ruby: s.scan(/error/i)
来源：http://dali.haohaochexian.top/Article/details/gtodxwxkxt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.svipenyu.cn/Article/details/gtlzkskhfk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.svipenyu.cn/Article/details/gtfftdrnty.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ywan-chungtsiang.top/Article/details/gtojydlles.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.316326.xyz/Article/details/gtblxeokza.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zdqjudy.top/Article/details/gtweyvbdyk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dianchejie.cn/Article/details/gtgkfjrffe.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gtgwrygcjl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hysaishi.cn/Article/details/gtmgrfykli.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cqqwz.cn/Article/details/gtvfwlkchp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.guannengcc.top/Article/details/gtuctblpep.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtutbouhdt.html

J. 日期与时间
来源：http://dali.cucudq.cn/Article/details/gtvgipjkgt.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gteaczfowi.html

[J01] 获取当前时间
来源：http://dali.smart0.xyz/Article/details/gtgspigqvo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.havefunace.top/Article/details/gtucwsadop.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cdnleiting.top/Article/details/gtiwndrkwy.html

JS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gtlpvdcbar.html

TS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gtroinmtew.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxinkj.top/Article/details/gtpivkbeeb.html

Go:   time.Now()
来源：http://dali.mhx1999.top/Article/details/gtwjofffhx.html

Ruby: Time.now
来源：http://dali.shzxlz.cn/Article/details/gteyxphdrw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjihgoti.html

[J02] 格式化输出
来源：http://dali.wangshuangyany.cn/Article/details/gtkwrfbaza.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gtwqrrhocr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenzaomai.com/Article/details/gtzumoegyk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yvedp.cn/Article/details/gtobwdqqwt.html

TS:   d.toISOString()
来源：http://dali.9152youxi.cn/Article/details/gtzafwqfye.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hfpthk.cn/Article/details/gtaorwnlzt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.wangdashe.top/Article/details/gtjfywosfk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gtkuipvbpi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shangyingyoupin.top/Article/details/gtnwrvsswu.html

[J03] 字符串解析为日期
来源：http://dali.feifeiyinyue.top/Article/details/gtudaluwxr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenjidiqi.icu/Article/details/gtlgtuiltf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnqzz.top/Article/details/gtgsygrwmm.html

JS:   new Date("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtzpyxqsbo.html

TS:   new Date("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtqfotenfo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtmtfxbxiw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtnmedyert.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtyvepxmnj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhongyouzk.top/Article/details/gtcqqrgsxk.html

[J04] 时间戳与日期互转
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrllyhoe.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtjoqgtltw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cdnleiting.top/Article/details/gtvljgpbsw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jlsjyb.cn/Article/details/gtazjljrcb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hongshengwenyu.top/Article/details/gtdtjxfgxr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gtkynwdksn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtbuwbeinn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aizwys.cn/Article/details/gtpoisvjlw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrkwliixr.html

[J05] 时间加减（加 7 天）
来源：http://dali.yangfankeji.com/Article/details/gtjyczetiu.html

Py:   now + timedelta(days=7)
来源：http://dali.xuanzx.com/Article/details/gtriukrehd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.quarkkingdee.top/Article/details/gtickxnhso.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbcsesjp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gtkpakqbti.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dianchejie.cn/Article/details/gtzafqasyy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlcaldtmo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yvedp.cn/Article/details/gtnrswasih.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zycfv.cn/Article/details/gtepezlbxe.html

[J06] 计算两时间之差
来源：http://dali.ehwqpu.com/Article/details/gtxnigehgj.html

Py:   (end - start).total_seconds()
来源：http://dali.gotoacloud.top/Article/details/gtgwjcmyoz.html

PHP:  $end->diff($start)->days;
来源：http://dali.gzhubu.top/Article/details/gtanoeofrx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shuidangran.top/Article/details/gtteqaqpeo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xylfe.cn/Article/details/gtmcxcylnw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ppjwa.cn/Article/details/gtelucidhr.html

Go:   end.Sub(start).Hours()
来源：http://dali.pengpengdd.cyou/Article/details/gtmvpfqmta.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj20258888.top/Article/details/gtujguinrz.html

C#:   (end - start).TotalSeconds
来源：http://dali.yonumen.top/Article/details/gtinkumura.html

[J07] 比较两个日期
来源：http://dali.sysykeji.top/Article/details/gtuykjatqf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gtdwzbdccj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.bjfxy.top/Article/details/gtidgfbmmt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.316326.xyz/Article/details/gteswewfkv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gogol.net.cn/Article/details/gtrthlelsn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xuetiantiany.cn/Article/details/gtogfvhond.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dianchejie.cn/Article/details/gtjtjemuid.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gtuxqkdnmn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtaesfdxib.html

[J08] 提取年月日与星期
来源：http://dali.bjfxy.top/Article/details/gtfhpyddgj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cqqwz.cn/Article/details/gtupyofakj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sweek.top/Article/details/gtcwjycoob.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.wangshuangyany.cn/Article/details/gtawtqmxxv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dashuyun.cn/Article/details/gtvlnhjmfz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinqigfzy.top/Article/details/gtzfbvtpxu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticlgcqnk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinghuilouyu.cn/Article/details/gtoufwwsiw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj20258.top/Article/details/gtimlahjit.html

[J09] 时区处理
来源：http://dali.cheryme.top/Article/details/gttntpqwlp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj202588.top/Article/details/gtjvknjmbl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hfpthk.cn/Article/details/gtswijgtmr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgfzy.top/Article/details/gtjggxreae.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gtqysyowcb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhoulong.xyz/Article/details/gtihzgrfls.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jyoumei.cn/Article/details/gtdfijtefg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.fengsongda.top/Article/details/gtmzijqckx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jiagoushi.top/Article/details/gthyjapzbb.html

[J10] 取今天 / 本月第一天
来源：http://dali.guannengcc.top/Article/details/gtndcmhjod.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpfsuztwb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhoulong.xyz/Article/details/gtlealatea.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgfzy.top/Article/details/gtmzjtdsxf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shzxlz.cn/Article/details/gtsldofoav.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shuidangran.top/Article/details/gtrniljzpu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sweek.top/Article/details/gtjlxojdgf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhengqikj.top/Article/details/gtopwqglom.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zdqjudy.top/Article/details/gtqnmjpbez.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtyksyxuaf.html

K. JSON 与序列化
来源：http://dali.jinghuilouyu.cn/Article/details/gtmerikqwe.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtuskymfat.html

[K01] 对象转 JSON 字符串
来源：http://dali.gaohongyu789.top/Article/details/gtxbkreqcm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.dianchejie.cn/Article/details/gtrhjtzprk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gtgcmczghm.html

JS:   JSON.stringify(obj)
来源：http://dali.zhixingplan.top/Article/details/gtwhmuvrlb.html

TS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gtetsylrby.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.daria6918.cn/Article/details/gtzfjmcaxf.html

Go:   json.Marshal(obj)
来源：http://dali.pycfn.com/Article/details/gtuixofvdj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.dashuyun.cn/Article/details/gtyqpfafgp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthaodkqn.html

[K02] JSON 字符串转对象
来源：http://dali.zhongyouzk.top/Article/details/gtswsucfnu.html

Py:   json.loads(s)
来源：http://dali.daxiang520.top/Article/details/gtxlryzkti.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.guowangkeji.top/Article/details/gtzhgoshaq.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gtiksedokt.html

TS:   JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gtzxtnrdmu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gotoacloud.top/Article/details/gtswmweskx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gtptpkhctg.html

Ruby: JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gthwuykbol.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.guannengcc.top/Article/details/gtfpapdjpl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hammf.cn/Article/details/gtvugrtxfd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gtiqhcehxd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hysaishi.cn/Article/details/gtdgtztzgl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gtfbigojvh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxinkj.top/Article/details/gtcqyyawrc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.0kj1m.cn/Article/details/gtwqoiovmx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.mhx1999.top/Article/details/gtssvjojga.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj20258888.top/Article/details/gtdhopdnul.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.dashuyun.cn/Article/details/gttzvsgsyk.html

[K04] 读取 JSON 文件
来源：http://dali.hywenlv.cn/Article/details/gtihdeutsq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jiagoushi.top/Article/details/gtlhyavkjd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenlongwang.top/Article/details/gtitotyivt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.quarkkingdee.top/Article/details/gtlfmkufrl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gtcjeaweyd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gtsazkplvo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yanxiufei.cn/Article/details/gtnttujqze.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gtndavfdbj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxuanxn.top/Article/details/gtlhgrzwdw.html

[K05] 深拷贝对象
来源：http://dali.bjfxy.top/Article/details/gtvdokyjmm.html

Py:   copy.deepcopy(obj)
来源：http://dali.yuanzhike.top/Article/details/gtcihyvzfy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yvedp.cn/Article/details/gtqzvelxsd.html

JS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtgtnqqoto.html

TS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gtmpclyrlj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hammf.cn/Article/details/gtkghqojqp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jqgfzy.top/Article/details/gtjnchknsh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nwbrower.top/Article/details/gtsuyysfqn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnxiangtu.top/Article/details/gtklotrhlo.html

[K06] 解析 URL 查询串
来源：http://dali.zhengqikj.top/Article/details/gtawhavmuk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tian-w.cn/Article/details/gtlgsgiedf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.snrcjt.cn/Article/details/gtzziflzci.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gtamnjarzn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ppjwa.cn/Article/details/gtnatueirk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.snrcjt.cn/Article/details/gtfznmgihi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cashguo.top/Article/details/gtzllblfea.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gtfpxkzkrt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gtomihdjae.html

[K07] 进制转换
来源：http://dali.cucudq.cn/Article/details/gteoiwicyy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gttihvhsex.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jyoumei.cn/Article/details/gtrjnxeuac.html


<!-- 参考信息 -->