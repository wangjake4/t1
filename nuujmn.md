代发 wailian999

Java: try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtyhhhygmh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sysykeji.top/Article/details/gtsdrayhvm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenjidiqi.icu/Article/details/gtfypinzqd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtqxfitnjr.html

[H03] 主动抛出异常
来源：http://dali.iojbl.cn/Article/details/gtmdcrxukt.html

Py:   raise ValueError("错误信息")
来源：http://dali.kuanghao11.cn/Article/details/gtpxhevnva.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gttlmgfpor.html

JS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtnfwxmiwl.html

TS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtzfbxcwgr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtfmwxcewy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yangfankeji.com/Article/details/gtjzmaurfm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhixingplan.top/Article/details/gtzixzdvex.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtuonezsfz.html

[H04] 自定义异常类型
来源：http://dali.gogol.net.cn/Article/details/gtpjsdwepe.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258.top/Article/details/gtrzbrrhlu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gttvecesry.html

JS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gtjufahseo.html

TS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gtjdjtcszf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zdqjudy.top/Article/details/gtwnvrvtyt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuxming.cn/Article/details/gtwdgfzahl.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuxming.cn/Article/details/gtwahgfiac.html

C#:   class MyException : Exception {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbxyhivlz.html

[H05] 捕获特定类型
来源：http://dali.0kj1m.cn/Article/details/gtaaxbzgkj.html

Py:   except ValueError as e:
来源：http://dali.xuanzx.com/Article/details/gtaqggnjvv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gterjzvxji.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gttxmnvfzl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gtldtbztss.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jianghu66.top/Article/details/gtlniuonqn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cdnleiting.top/Article/details/gtvumtluwj.html

Ruby: rescue ArgumentError => e
来源：http://dali.hfpthk.cn/Article/details/gtakmlcevz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shuidangran.top/Article/details/gtnbuiggld.html

[H06] 可选值 / 空值安全访问
来源：http://dali.bjfxy.top/Article/details/gtvsuyxnjf.html

Py:   value = d.get("k") or default
来源：http://dali.chenjidiqi.icu/Article/details/gtlzkvdyxu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yongpay.top/Article/details/gtwlwixpvv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gtswnqeusf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gtsrzqtrcd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yangfankeji.com/Article/details/gtpqwgdcox.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jlsjyb.cn/Article/details/gtqarocfab.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuanzx.com/Article/details/gttcrhdcnf.html

C#:   obj?.A?.B ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtjtkuwyxn.html

[H07] 断言
来源：http://dali.sufxvd.cn/Article/details/gthjizowtk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zycfv.cn/Article/details/gtqisuyegt.html

PHP:  assert($x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gtsescvwls.html

JS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gttqzhhgga.html

TS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtrqcbgwms.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ppjwa.cn/Article/details/gtywpouzwg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.bjfxy.top/Article/details/gthsyikqcl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxuanxn.top/Article/details/gtbsrdcdjb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtoybhfarf.html

[H08] 获取错误信息与堆栈
来源：http://dali.cqqwz.cn/Article/details/gtpwbocqge.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngiqoddl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.haohaochexian.top/Article/details/gtihbyxnqs.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvkngbra.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xuanzx.com/Article/details/gtrcnlflqm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zdqjudy.top/Article/details/gtepmrztof.html

Go:   err.Error()
来源：http://dali.havefunace.top/Article/details/gtfsdazmiy.html

Ruby: e.message;  e.backtrace
来源：http://dali.havefunace.top/Article/details/gtqktcxnau.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuetiantiany.cn/Article/details/gtcoqqbuwr.html

[H09] 带错误码的异常
来源：http://dali.hammf.cn/Article/details/gthxyzotdc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zycfv.cn/Article/details/gtqrtukarv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xylfe.cn/Article/details/gtbjmlaacb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj202588.top/Article/details/gtwpbsgsok.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhengqikj.top/Article/details/gtvofwljgd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hfpthk.cn/Article/details/gtlptupgwp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.meibo888.top/Article/details/gtbzxjoppo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.vqdsnc.cn/Article/details/gtxpfieahb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cheryme.top/Article/details/gtjzvzafje.html

[H10] 资源自动释放
来源：http://dali.dianchejie.cn/Article/details/gtsasstrgl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuanzhike.top/Article/details/gthdenmkhe.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.316326.xyz/Article/details/gtdqtoomwz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangshuangyany.cn/Article/details/gthrnppkrd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gtyqhbkpkt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sysykeji.top/Article/details/gtidizrjxt.html

Go:   defer f.Close()
来源：http://dali.hnxiangtu.top/Article/details/gtvucoxsvs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yueranfly.top/Article/details/gtdsxtmpcs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtlcufguvr.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtopxydojc.html

I. 正则表达式
来源：http://dali.zhoulong.xyz/Article/details/gtzpdhauix.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtgcrdwfdy.html

[I01] 判断是否匹配
来源：http://dali.xziqi.cn/Article/details/gtoutdvftu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shzxlz.cn/Article/details/gtzxbnqjme.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.birdmap.top/Article/details/gtbswonsds.html

JS:   /\d+/.test(s)
来源：http://dali.sysykeji.top/Article/details/gtxdwyatmz.html

TS:   /\d+/.test(s)
来源：http://dali.pycfn.com/Article/details/gtxcooijfj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhixingplan.top/Article/details/gtrhivmbtn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zdqjudy.top/Article/details/gtowbuprtp.html

Ruby: s.match?(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gtgmfkdodl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xylfe.cn/Article/details/gttwreuwfh.html

[I02] 提取所有匹配
来源：http://dali.yueranfly.top/Article/details/gtzrllhpzo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gtfyvphxab.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gogol.net.cn/Article/details/gtopbmgfsx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhoulong.xyz/Article/details/gtffotlwon.html

TS:   s.match(/\d+/g)
来源：http://dali.yj202588.top/Article/details/gtqtvounuy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yangfankeji.com/Article/details/gtdfuqfjvn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gtvjxvehiq.html

Ruby: s.scan(/\d+/)
来源：http://dali.feifeiyinyue.top/Article/details/gtkqemlkzt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtfsrgvfem.html

[I03] 提取捕获分组
来源：http://dali.zhixingplan.top/Article/details/gtjdkxmmki.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxuanxn.top/Article/details/gtddzcublh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cheryme.top/Article/details/gtgpfgnyoa.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.kuanghao11.cn/Article/details/gtnuofntfz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hongshengwenyu.top/Article/details/gtzivphgiv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gaohongyu789.top/Article/details/gtqfvvdsnt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.feifeiyinyue.top/Article/details/gtcyywjbbr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gttcenwbgn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sysykeji.top/Article/details/gtrjnblkmv.html

[I04] 正则替换
来源：http://dali.smart0.xyz/Article/details/gtnvkgrcak.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj20258888.top/Article/details/gtlozpfwmv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxfdoqxl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.smart0.xyz/Article/details/gtqouaqkon.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gtdonzqjee.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xuanzx.com/Article/details/gtteejxikh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenzaomai.com/Article/details/gtzcmwdqpf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.316326.xyz/Article/details/gtipgsourw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cashguo.top/Article/details/gtccemnwaj.html

[I05] 按正则拆分
来源：http://dali.yj20258888.top/Article/details/gtkbjykada.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.9152youxi.cn/Article/details/gtuzxvseny.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtxbvtytjt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gtdtntbtpm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwolddiyp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ehwqpu.com/Article/details/gtwrdwwcej.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.c1oappe.top/Article/details/gtvdhxjkki.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gtqbtnvhfa.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtccyaalgd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.iojbl.cn/Article/details/gtirpzssbj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gtntqguend.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.daxiang520.top/Article/details/gtxwamsgyi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gtniwjsqkx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbyhjgwvl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gtarsywwpq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cheryme.top/Article/details/gtcfyruydj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.guannengcc.top/Article/details/gttwsoxoxs.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gtuyusjmrl.html

[I07] 忽略大小写与多行模式
来源：http://dali.cashguo.top/Article/details/gtyarqqjtv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fengsongda.top/Article/details/gtergfnews.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvfzdzyhx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ppjwa.cn/Article/details/gtwpbyjrxt.html

TS:   /error/gim
来源：http://dali.gzhubu.top/Article/details/gtpissknhr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.bjfxy.top/Article/details/gtiuhahlpu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gaohongyu789.top/Article/details/gtusspwzfx.html

Ruby: s.scan(/error/i)
来源：http://dali.havefunace.top/Article/details/gtlemjwgim.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.redwolf501.top/Article/details/gtzsnmfxkb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.iojbl.cn/Article/details/gthffdrxkx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.haohaochexian.top/Article/details/gtxuucfrkr.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gtypnpokxu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gtqwlxqewg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gtorfopqfj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnqzz.top/Article/details/gtfnbbdntm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jianghu66.top/Article/details/gtdexqzzlk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yongpay.top/Article/details/gtnasliezt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gtsaaoinmu.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtneeuccbc.html

J. 日期与时间
来源：http://dali.9152youxi.cn/Article/details/gtkhqjftla.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtrtvnefxm.html

[J01] 获取当前时间
来源：http://dali.quarkkingdee.top/Article/details/gtepphxste.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jianghu66.top/Article/details/gtfyezntcn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenzaomai.com/Article/details/gtbgzcstzh.html

JS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gtbaxuwtuz.html

TS:   new Date();  Date.now()
来源：http://dali.xuetiantiany.cn/Article/details/gteubjsevg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.andypj.xyz/Article/details/gtbrtvxkuv.html

Go:   time.Now()
来源：http://dali.wangdashe.top/Article/details/gtkgdtjpse.html

Ruby: Time.now
来源：http://dali.sxryk.cn/Article/details/gthbezbyyz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.haohaochexian.top/Article/details/gttakujyyt.html

[J02] 格式化输出
来源：http://dali.zycfv.cn/Article/details/gtairgwyhu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.316326.xyz/Article/details/gtvrhatcls.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sysykeji.top/Article/details/gtftzoxpnv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cqqwz.cn/Article/details/gtbhxglucj.html

TS:   d.toISOString()
来源：http://dali.hywenlv.cn/Article/details/gtnfgrptpl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hfpthk.cn/Article/details/gtxbafvgqu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gaohongyu789.top/Article/details/gterkphbkm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gtkgmaayxn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daxiang520.top/Article/details/gthlqjxnvg.html

[J03] 字符串解析为日期
来源：http://dali.nanxuanxn.top/Article/details/gtwmakyesp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sysykeji.top/Article/details/gtrtpoghal.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shzxlz.cn/Article/details/gtixsovoqg.html

JS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtfdoqxiya.html

TS:   new Date("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtnrjcvxjx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtoiaecrgf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkfoegvhp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtdakkeozt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigufen.top/Article/details/gtdsdlvify.html

[J04] 时间戳与日期互转
来源：http://dali.hammf.cn/Article/details/gtrvvgvvpp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xziqi.cn/Article/details/gtpwpjzzep.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxuanxn.top/Article/details/gtrmwjlzex.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj20258.top/Article/details/gtzrhcpdeb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.andypj.xyz/Article/details/gtvpkqkjpd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sweek.top/Article/details/gtbfncirog.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmmwyneq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cdnleiting.top/Article/details/gtugooyows.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xziqi.cn/Article/details/gtzhalaadp.html

[J05] 时间加减（加 7 天）
来源：http://dali.0kj1m.cn/Article/details/gtxkngzprb.html

Py:   now + timedelta(days=7)
来源：http://dali.hfpthk.cn/Article/details/gtcponvjdu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xylfe.cn/Article/details/gtpazeqecw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gtdqehtpxm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gtgnwmngjc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jiagoushi.top/Article/details/gthokidrew.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ehwqpu.com/Article/details/gtpoeylrws.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yanxiufei.cn/Article/details/gtqsqkhygb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shzxlz.cn/Article/details/gtzrpktbhb.html

[J06] 计算两时间之差
来源：http://dali.0kj1m.cn/Article/details/gtkducdyod.html

Py:   (end - start).total_seconds()
来源：http://dali.feifeiyinyue.top/Article/details/gtsoxvehot.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhoulong.xyz/Article/details/gtfbtczilw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.aizwys.cn/Article/details/gtgpkdlneh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.9152youxi.cn/Article/details/gthbkggjet.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenzaomai.com/Article/details/gtuphxesvg.html

Go:   end.Sub(start).Hours()
来源：http://dali.dianchejie.cn/Article/details/gtmdodwaqz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.snrcjt.cn/Article/details/gtitlvwjoy.html

C#:   (end - start).TotalSeconds
来源：http://dali.feifeiyinyue.top/Article/details/gtglakdkmg.html

[J07] 比较两个日期
来源：http://dali.andypj.xyz/Article/details/gtcfqmndzz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gttpixbqcu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhengqikj.top/Article/details/gtredwwhnp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.pycfn.com/Article/details/gtqmahyolj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gtmwpvosrk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cashguo.top/Article/details/gthppcefaz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yonumen.top/Article/details/gtdipcxzau.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gthdrmggmj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gtkovrhvbk.html

[J08] 提取年月日与星期
来源：http://dali.hnqzz.top/Article/details/gttbvuyfpe.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hnqzz.top/Article/details/gtaqmltput.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj202588.top/Article/details/gtnzqclizy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhengqikj.top/Article/details/gtprakejva.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.wangshuangyany.cn/Article/details/gtvtqydgvu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.iojbl.cn/Article/details/gtdumagoiu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nwbrower.top/Article/details/gtnefqehud.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jiagoushi.top/Article/details/gtlpxuiidd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gzhubu.top/Article/details/gtmmybfeag.html

[J09] 时区处理
来源：http://dali.zdqjudy.top/Article/details/gtgnlazojw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsgfjrxni.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhiwuduotai.top/Article/details/gtdrcykvrh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnblrbsrd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fengsongda.top/Article/details/gtzaicvxbb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jqgufenzy.top/Article/details/gtfpsiaubi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nwbrower.top/Article/details/gtflagqoqy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.redwolf501.top/Article/details/gtcmlfztqz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jiagoushi.top/Article/details/gtqwhafpyd.html

[J10] 取今天 / 本月第一天
来源：http://dali.aibaodan.cn/Article/details/gtiiddwfle.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yongpay.top/Article/details/gtojdbrhml.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.havefunace.top/Article/details/gtfdglrooz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xziqi.cn/Article/details/gtowdwbxeg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxufwhmrc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cheryme.top/Article/details/gtzogioklv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.dianchejie.cn/Article/details/gtczjzhpnd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jyoumei.cn/Article/details/gtomhnzavy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.9152youxi.cn/Article/details/gtnzbigpbw.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtcldmectw.html

K. JSON 与序列化
来源：http://dali.meibo888.top/Article/details/gtxljuilme.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtczykjhim.html

[K01] 对象转 JSON 字符串
来源：http://dali.nwbrower.top/Article/details/gtohdlizuy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hysaishi.cn/Article/details/gtsvepwnff.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtssnixfcu.html

JS:   JSON.stringify(obj)
来源：http://dali.andypj.xyz/Article/details/gtacfwtkyf.html

TS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gtyxuzkpzl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj20258.top/Article/details/gtzwaotaqh.html

Go:   json.Marshal(obj)
来源：http://dali.ivvv.top/Article/details/gthhnzlreq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xinyue.icu/Article/details/gtowyaojrs.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hysaishi.cn/Article/details/gtfftrjlrp.html

[K02] JSON 字符串转对象
来源：http://dali.316326.xyz/Article/details/gtvtsdgqpx.html

Py:   json.loads(s)
来源：http://dali.9152youxi.cn/Article/details/gtgkckjkct.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigfzy.top/Article/details/gtdkpwdlxf.html

JS:   JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gtasjucbld.html

TS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gtwfgwewhp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.havefunace.top/Article/details/gtwhxqqkrj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sxryk.cn/Article/details/gtmrqqhiot.html

Ruby: JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gtocsmjwkq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenjidiqi.icu/Article/details/gthrcgcapy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cqqwz.cn/Article/details/gtiegyaewg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dianchejie.cn/Article/details/gtegznxmav.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sufxvd.cn/Article/details/gtwsfpjgzj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtplkfhdmp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtscjtflfi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtsyhzmcbo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.316326.xyz/Article/details/gtrvhsgcmw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cucudq.cn/Article/details/gthixrjbdf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yonumen.top/Article/details/gtsprtwurm.html

[K04] 读取 JSON 文件
来源：http://dali.jinqigfzy.top/Article/details/gtveyihnzk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gogol.net.cn/Article/details/gteuislwty.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cashguo.top/Article/details/gtdwlwrhsz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gotoacloud.top/Article/details/gtmqddnaec.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.andypj.xyz/Article/details/gtkbiubcct.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xinyue.icu/Article/details/gteultmrop.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.havefunace.top/Article/details/gtloqyvecn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zycfv.cn/Article/details/gtsqkuoydb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tanke756.top/Article/details/gtjmhbyfbt.html

[K05] 深拷贝对象
来源：http://dali.jinqigfzy.top/Article/details/gtkdidplee.html

Py:   copy.deepcopy(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtpkiwlxlo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhongyouzk.top/Article/details/gtujzgrnxg.html

JS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gtaobfkqcc.html

TS:   structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gtqgyxjlqz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258.top/Article/details/gtjidoyemd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhongyouzk.top/Article/details/gtwynbuwoi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.svipenyu.cn/Article/details/gteqoxsngs.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hongshengwenyu.top/Article/details/gtdtnbtyuo.html

[K06] 解析 URL 查询串
来源：http://dali.hfpthk.cn/Article/details/gtxmscnvtd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yangfankeji.com/Article/details/gtgahdvehe.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.redwolf501.top/Article/details/gtpjsbwqcf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hywenlv.cn/Article/details/gtaxxxiuqr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgufenzy.top/Article/details/gtaspzklpt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hnqzz.top/Article/details/gttdyjuubd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gtwvlnunym.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthmzgbomo.html


<!-- 参考信息 -->