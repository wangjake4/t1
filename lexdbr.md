代发 wailian999

Py:   try: f()⏎finally: cleanup()
来源：http://dali.daria6918.cn/Article/details/gt2eclcdzeq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gt2uywfoecb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gt2wtlzqnwa.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gt2iqlayjxe.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gt2msyqdvrw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhongyouzk.top/Article/details/gt2vniuzbrq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2apawizpu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2tinkhgeo.html

[H03] 主动抛出异常
来源：http://dali.shzxlz.cn/Article/details/gt2leooicjq.html

Py:   raise ValueError("错误信息")
来源：http://dali.aizwys.cn/Article/details/gt2lotbtngq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gt2usexkpfz.html

JS:   throw new Error("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2agdxqxyp.html

TS:   throw new Error("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gt2saukrfpw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mjxegyht.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ppjwa.cn/Article/details/gt2eibhhpmt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sufxvd.cn/Article/details/gt2mddrgmfa.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gt2aukxisxg.html

[H04] 自定义异常类型
来源：http://dali.hnxiangtu.top/Article/details/gt2qafvcbmu.html

Py:   class MyError(Exception): pass
来源：http://dali.dianchejie.cn/Article/details/gt2iwvxyeqg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gt2mmbrtidl.html

JS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2jqbhqoyx.html

TS:   class MyError extends Error {}
来源：http://dali.jyoumei.cn/Article/details/gt2ehuhyzmz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xgocarun.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sxryk.cn/Article/details/gt2ldsxouyh.html

Ruby: class MyError < StandardError; end
来源：http://dali.cqqwz.cn/Article/details/gt2yidryuhp.html

C#:   class MyException : Exception {}
来源：http://dali.kuanghao11.cn/Article/details/gt2teppgldn.html

[H05] 捕获特定类型
来源：http://dali.dashuyun.cn/Article/details/gt2jnrzkakx.html

Py:   except ValueError as e:
来源：http://dali.chenzaomai.com/Article/details/gt2uoeihybj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zdqjudy.top/Article/details/gt2xuggnerb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gt2etsogwyx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ewyzjncf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cqqwz.cn/Article/details/gt2jfciyscv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xziqi.cn/Article/details/gt2lequsbwz.html

Ruby: rescue ArgumentError => e
来源：http://dali.yangfankeji.com/Article/details/gt2wmytghpn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xylfe.cn/Article/details/gt2ybfsnrpg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fzhhl.top/Article/details/gt2kszncmnr.html

Py:   value = d.get("k") or default
来源：http://dali.shangyingyoupin.top/Article/details/gt2sbdegawu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gt2udbjpcng.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gt2rllriqqq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ivvv.top/Article/details/gt2upbtyvel.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnqzz.top/Article/details/gt2ugmaxxez.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.smart0.xyz/Article/details/gt2uzjrnwah.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hywenlv.cn/Article/details/gt2ucvqrirg.html

C#:   obj?.A?.B ?? default
来源：http://dali.zycfv.cn/Article/details/gt2tsluuyal.html

[H07] 断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jhhnzcgk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenlongwang.top/Article/details/gt2jcopzqcd.html

PHP:  assert($x > 0);
来源：http://dali.jqgfzy.top/Article/details/gt2hskcpiia.html

JS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gt2gqzujrte.html

TS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gt2nlqjgfwh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jiagoushi.top/Article/details/gt2klkjvzah.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nanxinkj.top/Article/details/gt2vfupmkjx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangdashe.top/Article/details/gt2kjqplapy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gt2dtteqpfr.html

[H08] 获取错误信息与堆栈
来源：http://dali.jianghu66.top/Article/details/gt2pjishfwx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.kuanghao11.cn/Article/details/gt2lwzmhato.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yangfankeji.com/Article/details/gt2xbqruthd.html

JS:   e.message;  e.stack
来源：http://dali.ybcxt.top/Article/details/gt2deemadml.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ozpuiksm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.bjfxy.top/Article/details/gt2izmenejw.html

Go:   err.Error()
来源：http://dali.9152youxi.cn/Article/details/gt2ceqfnxar.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ncwnsiyd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.guannengcc.top/Article/details/gt2pbxvykgp.html

[H09] 带错误码的异常
来源：http://dali.chenjidiqi.icu/Article/details/gt2dliaiwqr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nwbrower.top/Article/details/gt2osqqhnjd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.c1oappe.top/Article/details/gt2kystkaga.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.dashuyun.cn/Article/details/gt2jfryyeip.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangdashe.top/Article/details/gt2fzvvwczq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cheryme.top/Article/details/gt2praquuie.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zdqjudy.top/Article/details/gt2ilslgiiv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gogol.net.cn/Article/details/gt2jnknveni.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pengpengdd.cyou/Article/details/gt2rpaqpngv.html

[H10] 资源自动释放
来源：http://dali.nwbrower.top/Article/details/gt2vggevcyd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.quarkkingdee.top/Article/details/gt2mbylfafr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sufxvd.cn/Article/details/gt2bmynhkch.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gt2lqyvwiad.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gt2cyraojvs.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ivvv.top/Article/details/gt2jllbrsjm.html

Go:   defer f.Close()
来源：http://dali.xylfe.cn/Article/details/gt2hbolfmua.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hfpthk.cn/Article/details/gt2nzdhsaol.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2mbogqyqh.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2hruesuib.html

I. 正则表达式
来源：http://dali.dashuyun.cn/Article/details/gt2bgilqhly.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2vfdheiuw.html

[I01] 判断是否匹配
来源：http://dali.yonumen.top/Article/details/gt2ctdygbjv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shuidangran.top/Article/details/gt2notmgcbq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2fcfpfvqk.html

JS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gt2ntcmannc.html

TS:   /\d+/.test(s)
来源：http://dali.jyoumei.cn/Article/details/gt2ycmhtlhi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenzaomai.com/Article/details/gt2wmgproof.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.c1oappe.top/Article/details/gt2xolyjkzw.html

Ruby: s.match?(/\d+/)
来源：http://dali.xuanzx.com/Article/details/gt2hirxvvwq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yueranfly.top/Article/details/gt2zdfhwnfx.html

[I02] 提取所有匹配
来源：http://dali.dashuyun.cn/Article/details/gt2nydptqth.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gzhubu.top/Article/details/gt2uxwjlovi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tanke756.top/Article/details/gt2adbhlemy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhongyouzk.top/Article/details/gt2mexhausf.html

TS:   s.match(/\d+/g)
来源：http://dali.sufxvd.cn/Article/details/gt2tvodrzth.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hysaishi.cn/Article/details/gt2nijpthui.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hnxiangtu.top/Article/details/gt2hrqlttmb.html

Ruby: s.scan(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gt2usztzkqb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxinkj.top/Article/details/gt2kedwjgey.html

[I03] 提取捕获分组
来源：http://dali.quarkkingdee.top/Article/details/gt2ayqltjax.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ehwqpu.com/Article/details/gt2zfjnrsev.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ivvv.top/Article/details/gt2ikvltgyd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pycfn.com/Article/details/gt2pqoxfbgs.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zwcfqmkz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sufxvd.cn/Article/details/gt2bbjgdyey.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sysykeji.top/Article/details/gt2tszjoouo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhixingplan.top/Article/details/gt2ifhuyogs.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gotoacloud.top/Article/details/gt2kcglfmav.html

[I04] 正则替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2igtmaynr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pyayvicl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yueranfly.top/Article/details/gt2zfwscxzh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gt2dfukrgyp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gt2bphbnvsn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2piftyrgy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yuxming.cn/Article/details/gt2tlqkmbpc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj20258.top/Article/details/gt2buveidal.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ispolytj.html

[I05] 按正则拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gt2okmzomqu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.bjfxy.top/Article/details/gt2gpzwqpmb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.guowangkeji.top/Article/details/gt2wtwxooda.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gt2txnsmyqu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gt2yhqivdcl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.daxiang520.top/Article/details/gt2rladkois.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.316326.xyz/Article/details/gt2aliucqtp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gt2atwtrsqy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jianghu66.top/Article/details/gt2vlirrhcy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jyoumei.cn/Article/details/gt2dbqucqnc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gt2vlxeohka.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cqqwz.cn/Article/details/gt2inepuxgo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daxiang520.top/Article/details/gt2byhrnekc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cqqwz.cn/Article/details/gt2npjtyrag.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gt2zwxartag.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jiagoushi.top/Article/details/gt2qazcxzxs.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mjvxadup.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.birdmap.top/Article/details/gt2zejemkzj.html

[I07] 忽略大小写与多行模式
来源：http://dali.yueranfly.top/Article/details/gt2qhajymph.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgufenzy.top/Article/details/gt2hynvmvcs.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jqgufenzy.top/Article/details/gt2uporciel.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hfpthk.cn/Article/details/gt2ekdzxgnd.html

TS:   /error/gim
来源：http://dali.0kj1m.cn/Article/details/gt2qkcvekdr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kkpshrnz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cashguo.top/Article/details/gt2heepdagm.html

Ruby: s.scan(/error/i)
来源：http://dali.dashuyun.cn/Article/details/gt2gvmqrznb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.quarkkingdee.top/Article/details/gt2ecqouzfz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.mhx1999.top/Article/details/gt2hzxoiiyu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.mhx1999.top/Article/details/gt2xwuhbgov.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ybcxt.top/Article/details/gt2hvwbkmjb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sysykeji.top/Article/details/gt2axvkrvjd.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gt2fqxikwdg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj202588.top/Article/details/gt2mnvctksv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhongyouzk.top/Article/details/gt2exihtxqt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.haohaochexian.top/Article/details/gt2nuwaoeuw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shangyingyoupin.top/Article/details/gt2jguvnyqj.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2amcmuzpq.html

J. 日期与时间
来源：http://dali.havefunace.top/Article/details/gt2srcnksrx.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2vlnjcfvk.html

[J01] 获取当前时间
来源：http://dali.havefunace.top/Article/details/gt2ruvvqera.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.bjfxy.top/Article/details/gt2iudbrbnl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gt2xxwdpqrg.html

JS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ujltwnso.html

TS:   new Date();  Date.now()
来源：http://dali.cdnleiting.top/Article/details/gt2lrggeqdq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jianghu66.top/Article/details/gt2hcskbhmz.html

Go:   time.Now()
来源：http://dali.hnqzz.top/Article/details/gt2toxcpdpf.html

Ruby: Time.now
来源：http://dali.tanke756.top/Article/details/gt2hfxmapyz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sxryk.cn/Article/details/gt2fqoizetz.html

[J02] 格式化输出
来源：http://dali.gaohongyu789.top/Article/details/gt2gmnwvcds.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tian-w.cn/Article/details/gt2emlcfpyn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gaohongyu789.top/Article/details/gt2skffetbt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ivvv.top/Article/details/gt2chyaanjh.html

TS:   d.toISOString()
来源：http://dali.zhoulong.xyz/Article/details/gt2ecnlsmlu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj202588.top/Article/details/gt2oxvykfpb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.pengpengdd.cyou/Article/details/gt2bxfyplhx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gt2txmeyubv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhoulong.xyz/Article/details/gt2jzwnulam.html

[J03] 字符串解析为日期
来源：http://dali.tianlin.xyz/Article/details/gt2fqksbtlo.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uqzudyel.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yonumen.top/Article/details/gt2kaxufpbx.html

JS:   new Date("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gt2wvzmdqar.html

TS:   new Date("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gt2yfgjdiqj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2pernjyfm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gt2dxgvoqrj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gt2tclhlujg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhengqikj.top/Article/details/gt2mbvyllek.html

[J04] 时间戳与日期互转
来源：http://dali.jlsjyb.cn/Article/details/gt2tbumdijw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gt2aftekkbx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.daxiang520.top/Article/details/gt2cbtuyujz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenlongwang.top/Article/details/gt2ehhctvqw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ivvv.top/Article/details/gt2zoeswxbm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.haohaochexian.top/Article/details/gt2diazjfyc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mrxobtdl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hnxiangtu.top/Article/details/gt2ndhctlvh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hammf.cn/Article/details/gt2xvurqfjc.html

[J05] 时间加减（加 7 天）
来源：http://dali.yuanzhike.top/Article/details/gt2oxcvkyip.html

Py:   now + timedelta(days=7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tbamters.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.svipenyu.cn/Article/details/gt2ctyjyrex.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fzhhl.top/Article/details/gt2gfowjzaj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cheryme.top/Article/details/gt2jpojgsbv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zbaobluy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shzxlz.cn/Article/details/gt2lnplwqbm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yanxiufei.cn/Article/details/gt2vvgstcgy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj20258888.top/Article/details/gt2xphyupsb.html

[J06] 计算两时间之差
来源：http://dali.hysaishi.cn/Article/details/gt2kcqmbnlb.html

Py:   (end - start).total_seconds()
来源：http://dali.tian-w.cn/Article/details/gt2cbvvzgqg.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhengqikj.top/Article/details/gt2itgukfzp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sweek.top/Article/details/gt2whcgzwmi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gzhubu.top/Article/details/gt2hnlnzjxy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.vqdsnc.cn/Article/details/gt2iaizlwdy.html

Go:   end.Sub(start).Hours()
来源：http://dali.aizwys.cn/Article/details/gt2kmjtyozo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pengpengdd.cyou/Article/details/gt2shusxptl.html

C#:   (end - start).TotalSeconds
来源：http://dali.iojbl.cn/Article/details/gt2vrgpvoii.html

[J07] 比较两个日期
来源：http://dali.redwolf501.top/Article/details/gt2qdvvqymo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gt2mxypgijs.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hammf.cn/Article/details/gt2qvxfizsq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gt2grscvlpm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gt2xbsylswr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fyzsikse.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258888.top/Article/details/gt2rfzuyhrv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gt2zsclclyu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2owhjetjx.html

[J08] 提取年月日与星期
来源：http://dali.bjfxy.top/Article/details/gt2xtwuslww.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhongyouzk.top/Article/details/gt2zjoiapat.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jiagoushi.top/Article/details/gt2nzaqscdf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.kuanghao11.cn/Article/details/gt2tipytvpw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.smart0.xyz/Article/details/gt2epygmolf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yanxiufei.cn/Article/details/gt2xuifjhui.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenjidiqi.icu/Article/details/gt2logutylg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cqqwz.cn/Article/details/gt2kltsyzca.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hysaishi.cn/Article/details/gt2kwkabooq.html

[J09] 时区处理
来源：http://dali.tian-w.cn/Article/details/gt2tewkjqjl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jqgfzy.top/Article/details/gt2gfxfllqs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.havefunace.top/Article/details/gt2imkcemzo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.mhx1999.top/Article/details/gt2aqrfbqwp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.meibo888.top/Article/details/gt2viwmoxxg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dianchejie.cn/Article/details/gt2ckyhxppe.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hnqzz.top/Article/details/gt2kvkljkoz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ppjwa.cn/Article/details/gt2bpxznxwa.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenjidiqi.icu/Article/details/gt2apzhoflk.html

[J10] 取今天 / 本月第一天
来源：http://dali.hfpthk.cn/Article/details/gt2acplvqvx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenzaomai.com/Article/details/gt2rhzghvbu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.daxiang520.top/Article/details/gt2obfzjszr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ydzc1.top/Article/details/gt2uuprjlls.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hammf.cn/Article/details/gt2vcbqsxev.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zhpnpzue.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jqgfzy.top/Article/details/gt2zymbbmgu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dashuyun.cn/Article/details/gt2mnzottad.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.bjfxy.top/Article/details/gt2uhwijfwc.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2zlzplgob.html

K. JSON 与序列化
来源：http://dali.yuanzhike.top/Article/details/gt2wektswkq.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2djwqqexy.html

[K01] 对象转 JSON 字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2yzuetwkk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jyoumei.cn/Article/details/gt2vqgbqhph.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.mhx1999.top/Article/details/gt2nmalvrpz.html

JS:   JSON.stringify(obj)
来源：http://dali.guannengcc.top/Article/details/gt2dmaxqwkp.html

TS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gt2xnsvmrfb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.snrcjt.cn/Article/details/gt2grbgaqtw.html

Go:   json.Marshal(obj)
来源：http://dali.xinyue.icu/Article/details/gt2wsppyzgy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ydzc1.top/Article/details/gt2tvvdnrzn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cucudq.cn/Article/details/gt2gmxsgxxs.html

[K02] JSON 字符串转对象
来源：http://dali.shuidangran.top/Article/details/gt2aohxprir.html

Py:   json.loads(s)
来源：http://dali.redwolf501.top/Article/details/gt2cayndqof.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj202588.top/Article/details/gt2xmhvorkj.html

JS:   JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xapoocjy.html

TS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gt2shrxmrqu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lohaymrp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.dianchejie.cn/Article/details/gt2hhfilvvy.html

Ruby: JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gt2hdqfbyrr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gotoacloud.top/Article/details/gt2wctgtykk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yanxiufei.cn/Article/details/gt2ulnkamul.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.316326.xyz/Article/details/gt2hfhnzkix.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xinyue.icu/Article/details/gt2oiwoceuv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nwvxrxeq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gt2hqjullnj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2jxfewiau.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hnxiangtu.top/Article/details/gt2dbgdlxia.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vhtpffgl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2diwpgjoo.html

[K04] 读取 JSON 文件
来源：http://dali.0kj1m.cn/Article/details/gt2nhlvnmyf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tianlin.xyz/Article/details/gt2xvzxhnha.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenjidiqi.icu/Article/details/gt2okpgthwv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2krnfgynw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.mhx1999.top/Article/details/gt2aojvnqie.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj20258.top/Article/details/gt2tiiydqcy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.feifeiyinyue.top/Article/details/gt2oyntcfvv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gt2sztysxzj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.birdmap.top/Article/details/gt2hgcplqgu.html

[K05] 深拷贝对象
来源：http://dali.guannengcc.top/Article/details/gt2aijjpeee.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2vhocmrtc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jqgfzy.top/Article/details/gt2jyvieelg.html

JS:   structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2cdyfbifq.html

TS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2zljkvlby.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.meibo888.top/Article/details/gt2grlqqfda.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gaohongyu789.top/Article/details/gt2yvlcvbfu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.daria6918.cn/Article/details/gt2nollzqno.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.aibaodan.cn/Article/details/gt2xqmsanrk.html

[K06] 解析 URL 查询串
来源：http://dali.9152youxi.cn/Article/details/gt2llcykigh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nanxinkj.top/Article/details/gt2diwoyxsf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ybcxt.top/Article/details/gt2reurpfau.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dianchejie.cn/Article/details/gt2girucgfp.html


<!-- 参考信息 -->