代发 wailian999

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jiagoushi.top/Article/details/gtjdogdkbi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxuanxn.top/Article/details/gteldglqio.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.0kj1m.cn/Article/details/gttaxbchpg.html

[H02] finally / ensure 收尾
来源：http://dali.gaohongyu789.top/Article/details/gtglkfflch.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ppjwa.cn/Article/details/gtvoihggiu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtxvbomyni.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtqparcjro.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtsherdvok.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtflhytxwc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gteselxguf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgivpmfl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtuboaaioo.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtcudoengw.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangdashe.top/Article/details/gtwbiqmmfx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtmwoyyopp.html

JS:   throw new Error("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtkhqyyzde.html

TS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gtywkqqxkt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtuimkescg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.mhx1999.top/Article/details/gttovyeozw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shuidangran.top/Article/details/gtbvytzxeb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtpnjtrhfh.html

[H04] 自定义异常类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpblwnqnz.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgufenzy.top/Article/details/gtpmismfjz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhiwuduotai.top/Article/details/gtjriuzyqx.html

JS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gtjcmnqxyy.html

TS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gtpwqkijyz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.meibo888.top/Article/details/gtkgzgcjvw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yanxiufei.cn/Article/details/gthdkscwlg.html

Ruby: class MyError < StandardError; end
来源：http://dali.xylfe.cn/Article/details/gtivegwcmg.html

C#:   class MyException : Exception {}
来源：http://dali.shangyingyoupin.top/Article/details/gtnftpkxuf.html

[H05] 捕获特定类型
来源：http://dali.wangdashe.top/Article/details/gtkqtwdgqn.html

Py:   except ValueError as e:
来源：http://dali.tian-w.cn/Article/details/gtlclcikyx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zdqjudy.top/Article/details/gtjetdurgq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.quarkkingdee.top/Article/details/gtahpkbglm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gtecwkravw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hammf.cn/Article/details/gtawfoqwbu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gtyfmgouoe.html

Ruby: rescue ArgumentError => e
来源：http://dali.shzxlz.cn/Article/details/gtimkwzjjd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yangfankeji.com/Article/details/gtmfnnjugw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zycfv.cn/Article/details/gtbwokeadw.html

Py:   value = d.get("k") or default
来源：http://dali.tian-w.cn/Article/details/gtwpkbcvqa.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hysaishi.cn/Article/details/gtfgcyhpem.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jianghu66.top/Article/details/gtkaaydxdr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gteoepdxzb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cucudq.cn/Article/details/gtyojacput.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gogol.net.cn/Article/details/gtnyqevgrc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.fzhhl.top/Article/details/gtyqnujkbp.html

C#:   obj?.A?.B ?? default
来源：http://dali.guowangkeji.top/Article/details/gtrsapsqge.html

[H07] 断言
来源：http://dali.xinyue.icu/Article/details/gtcddkqlsu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.guannengcc.top/Article/details/gtjwbjrhah.html

PHP:  assert($x > 0);
来源：http://dali.yj202588.top/Article/details/gtfjjttjzl.html

JS:   console.assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gtpaojhuhm.html

TS:   console.assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gtfkeqyrya.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yanxiufei.cn/Article/details/gtdhzostcn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmkemlxnl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.vqdsnc.cn/Article/details/gtvcbpaeit.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gthtgtknde.html

[H08] 获取错误信息与堆栈
来源：http://dali.pengpengdd.cyou/Article/details/gtibkmzbmr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinqigufen.top/Article/details/gtcztrazda.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shangyingyoupin.top/Article/details/gtmfompbav.html

JS:   e.message;  e.stack
来源：http://dali.chenzaomai.com/Article/details/gtzlzjcdbd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.c1oappe.top/Article/details/gtzulipcmo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuxming.cn/Article/details/gtinceyupe.html

Go:   err.Error()
来源：http://dali.hongshengwenyu.top/Article/details/gtbhwfcukn.html

Ruby: e.message;  e.backtrace
来源：http://dali.hywenlv.cn/Article/details/gtegiepngg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.meibo888.top/Article/details/gthhxuppgz.html

[H09] 带错误码的异常
来源：http://dali.wangshuangyany.cn/Article/details/gtdphvmqwv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.c1oappe.top/Article/details/gtmueovtic.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcthmyvfg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.bjfxy.top/Article/details/gthxyujced.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jiagoushi.top/Article/details/gtuptxcpzq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xinyue.icu/Article/details/gtbgeoyzrs.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.quarkkingdee.top/Article/details/gtlsjcdfot.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yueranfly.top/Article/details/gtrduyclpl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.aibaodan.cn/Article/details/gtbjeezsoi.html

[H10] 资源自动释放
来源：http://dali.mhx1999.top/Article/details/gtxfaoehpt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nwbrower.top/Article/details/gteethymtb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xylfe.cn/Article/details/gtqvhihqda.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gtthtzfdsu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gtvjjgwnfs.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guannengcc.top/Article/details/gtxtorahwi.html

Go:   defer f.Close()
来源：http://dali.sysykeji.top/Article/details/gtfxkdisjo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.havefunace.top/Article/details/gtejbkzacf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtgnoertyp.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gthjojcqyv.html

I. 正则表达式
来源：http://dali.meibo888.top/Article/details/gtlybzspyq.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtshlmtayl.html

[I01] 判断是否匹配
来源：http://dali.daria6918.cn/Article/details/gtwvqvextf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gtesashnkh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ydzc1.top/Article/details/gtrhdnklxw.html

JS:   /\d+/.test(s)
来源：http://dali.nanxinkj.top/Article/details/gtcchtxnsd.html

TS:   /\d+/.test(s)
来源：http://dali.ppjwa.cn/Article/details/gtexqbasrr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.feifeiyinyue.top/Article/details/gtuepaebty.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.meibo888.top/Article/details/gtzxrnnnog.html

Ruby: s.match?(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gtfihlwred.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.pengpengdd.cyou/Article/details/gtiafhncyn.html

[I02] 提取所有匹配
来源：http://dali.svipenyu.cn/Article/details/gtqujinhsf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jyoumei.cn/Article/details/gtgsjpcogs.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nanxuanxn.top/Article/details/gtqsfgrciq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shangyingyoupin.top/Article/details/gtbbevtxpn.html

TS:   s.match(/\d+/g)
来源：http://dali.havefunace.top/Article/details/gtvekcyqzo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhongyouzk.top/Article/details/gtzlgfpwev.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.aizwys.cn/Article/details/gtxgfmscvf.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgfzy.top/Article/details/gtydxdjrgp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtulqcbcrr.html

[I03] 提取捕获分组
来源：http://dali.chenjidiqi.icu/Article/details/gtioxsaihv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jlsjyb.cn/Article/details/gtiqiskify.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sysykeji.top/Article/details/gtsxdwonib.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tanke756.top/Article/details/gttonjgmpx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.meibo888.top/Article/details/gtxtbxszoi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.birdmap.top/Article/details/gtnplxkwoi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yangfankeji.com/Article/details/gtdstzjcfi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cheryme.top/Article/details/gttafguynm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ydzc1.top/Article/details/gtqqoskudn.html

[I04] 正则替换
来源：http://dali.jinqigfzy.top/Article/details/gtgtpbncpo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.quarkkingdee.top/Article/details/gtlsmzpsat.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenzaomai.com/Article/details/gtztogkcjd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfgowurmp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtmtgmsupa.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.vqdsnc.cn/Article/details/gtbhoakebp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtjtijmxqo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj202588.top/Article/details/gtxljtjsoe.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.fzhhl.top/Article/details/gtdibodsfi.html

[I05] 按正则拆分
来源：http://dali.zhixingplan.top/Article/details/gtlxzthdwl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtyynkohfm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtrjkvcxry.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtpunwrvcb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gtqadjoewo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yonumen.top/Article/details/gtptkzrsdo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gtqlflrimp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gtljqjofuc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.guannengcc.top/Article/details/gthpgreuwb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.fengsongda.top/Article/details/gtbkzewuso.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gtgdwaqslt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shuidangran.top/Article/details/gtizdvevdi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.0kj1m.cn/Article/details/gtcgbrxfzw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.havefunace.top/Article/details/gtvffsqgzo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gttxhixlqf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shuidangran.top/Article/details/gtjenknhme.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkzallxeu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gttmmgckie.html

[I07] 忽略大小写与多行模式
来源：http://dali.daxiang520.top/Article/details/gtzzqxhhwp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.smart0.xyz/Article/details/gtacspxsos.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cucudq.cn/Article/details/gtbkorjfxn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.iojbl.cn/Article/details/gtxjdjlsrw.html

TS:   /error/gim
来源：http://dali.aibaodan.cn/Article/details/gtypvklzok.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.haohaochexian.top/Article/details/gtivqconiw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.mhx1999.top/Article/details/gtistpycic.html

Ruby: s.scan(/error/i)
来源：http://dali.cucudq.cn/Article/details/gtkwqqyvcu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jyoumei.cn/Article/details/gtdmjhjwsg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtylgpjomp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.aizwys.cn/Article/details/gtxcsybpev.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmaugxynj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuanzx.com/Article/details/gtnauegrug.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxinkj.top/Article/details/gtwtxlkjig.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gtiiqwphqk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gzhubu.top/Article/details/gtxebhkfei.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.smart0.xyz/Article/details/gtnkgmacfh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.wangshuangyany.cn/Article/details/gtlodcwpub.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtgdacuujf.html

J. 日期与时间
来源：http://dali.smart0.xyz/Article/details/gtnezucsyd.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtkvgwqwmz.html

[J01] 获取当前时间
来源：http://dali.chenzaomai.com/Article/details/gtvnqamjnr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cqqwz.cn/Article/details/gtveephouy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258.top/Article/details/gtyihgwrbc.html

JS:   new Date();  Date.now()
来源：http://dali.ppjwa.cn/Article/details/gtsnpvmotm.html

TS:   new Date();  Date.now()
来源：http://dali.fzhhl.top/Article/details/gtszeojtcv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokrgtjzc.html

Go:   time.Now()
来源：http://dali.dashuyun.cn/Article/details/gtnrzmgfor.html

Ruby: Time.now
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaglnuhks.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuanzx.com/Article/details/gtuosthvcq.html

[J02] 格式化输出
来源：http://dali.sxryk.cn/Article/details/gtdivqcide.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gthxlzgxei.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gthijsnwxa.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoyqbxgjr.html

TS:   d.toISOString()
来源：http://dali.zhengqikj.top/Article/details/gtoeqccepb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xuetiantiany.cn/Article/details/gtnueduwwo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daxiang520.top/Article/details/gtwtqjoyue.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sweek.top/Article/details/gtzrnqlzjb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gogol.net.cn/Article/details/gtmbijtbsv.html

[J03] 字符串解析为日期
来源：http://dali.9152youxi.cn/Article/details/gtbfzuccdw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yvedp.cn/Article/details/gtanaimcny.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xinyue.icu/Article/details/gtavuyator.html

JS:   new Date("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtaglfrssb.html

TS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtgjcibpmu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtvoliupms.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtltbrvnvj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtfjgqcykr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ehwqpu.com/Article/details/gtgbedjptz.html

[J04] 时间戳与日期互转
来源：http://dali.redwolf501.top/Article/details/gtceugrpop.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuxming.cn/Article/details/gtvjacunon.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zycfv.cn/Article/details/gtspfkrjua.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yanxiufei.cn/Article/details/gteegryejb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenzaomai.com/Article/details/gtyslxbbqo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yuxming.cn/Article/details/gtvvuqwywl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtougeouwi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xinyue.icu/Article/details/gtxwxykgjn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenzaomai.com/Article/details/gtjjywzvdg.html

[J05] 时间加减（加 7 天）
来源：http://dali.guannengcc.top/Article/details/gtkyodwryy.html

Py:   now + timedelta(days=7)
来源：http://dali.bjfxy.top/Article/details/gtheacajut.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sufxvd.cn/Article/details/gtfmfrvqqd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvynfonp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigfzy.top/Article/details/gtljwsmfjr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenzaomai.com/Article/details/gtkzeoovpr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.redwolf501.top/Article/details/gtcloxpctf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ybcxt.top/Article/details/gtkafaxueg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhengqikj.top/Article/details/gtvoozzjtv.html

[J06] 计算两时间之差
来源：http://dali.gaohongyu789.top/Article/details/gttxlhocjk.html

Py:   (end - start).total_seconds()
来源：http://dali.gogol.net.cn/Article/details/gtnhdzdmte.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnqzz.top/Article/details/gtqwjixodp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shzxlz.cn/Article/details/gtvxffpxyh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.smart0.xyz/Article/details/gtrggdortp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cqqwz.cn/Article/details/gtpadmkgvz.html

Go:   end.Sub(start).Hours()
来源：http://dali.birdmap.top/Article/details/gtevkfwlms.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shzxlz.cn/Article/details/gtilwqkgcf.html

C#:   (end - start).TotalSeconds
来源：http://dali.sweek.top/Article/details/gtbjpevbzc.html

[J07] 比较两个日期
来源：http://dali.wangshuangyany.cn/Article/details/gtnklbqtvx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gtfacekfwy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jlsjyb.cn/Article/details/gtmxeamovz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gtjoqymjar.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.redwolf501.top/Article/details/gtpifpjwww.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.andypj.xyz/Article/details/gthqqmeviu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.0kj1m.cn/Article/details/gtzsmwdphq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtmdnrvsoa.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtlrbqroaf.html

[J08] 提取年月日与星期
来源：http://dali.yangfankeji.com/Article/details/gtuksmzrlu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sweek.top/Article/details/gttyovpfjn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbzwbywc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hammf.cn/Article/details/gteybcnnrg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hongshengwenyu.top/Article/details/gtckrtfqol.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.redwolf501.top/Article/details/gtzvwxaxsm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.pengpengdd.cyou/Article/details/gtvltdpumz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fengsongda.top/Article/details/gtcxkmtedn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.kuanghao11.cn/Article/details/gtbahkqlsz.html

[J09] 时区处理
来源：http://dali.guowangkeji.top/Article/details/gtvfyhgsho.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.9152youxi.cn/Article/details/gtftbswbgi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daria6918.cn/Article/details/gtaxwustfx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnxiangtu.top/Article/details/gtltldrerm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gtdrftjpyp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsrizabjb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cucudq.cn/Article/details/gtwtclther.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhongyouzk.top/Article/details/gtzevowojn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258.top/Article/details/gtsletaeal.html

[J10] 取今天 / 本月第一天
来源：http://dali.guowangkeji.top/Article/details/gtcwdbsmnk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jiagoushi.top/Article/details/gtepwfaqpr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gaohongyu789.top/Article/details/gtjkeigjxa.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.bjfxy.top/Article/details/gtccndqffz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhengqikj.top/Article/details/gtxymwcnjf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xinyue.icu/Article/details/gtzvhnxrrc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.haohaochexian.top/Article/details/gtuasrlbgd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dianchejie.cn/Article/details/gtirivvrcu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.vqdsnc.cn/Article/details/gtzgtrbajp.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtfybnqemb.html

K. JSON 与序列化
来源：http://dali.jianghu66.top/Article/details/gtgveikfue.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtrdevopmv.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxuanxn.top/Article/details/gtgjwafjkh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj20258.top/Article/details/gthxxehcdb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.9152youxi.cn/Article/details/gtjtseivrq.html

JS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gtmaypdyum.html

TS:   JSON.stringify(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtouuniwte.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jqgufenzy.top/Article/details/gtlygltwtd.html

Go:   json.Marshal(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtjqhezvvp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdmkrpto.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xylfe.cn/Article/details/gtuvnlcuwq.html

[K02] JSON 字符串转对象
来源：http://dali.daxiang520.top/Article/details/gtrybmguto.html

Py:   json.loads(s)
来源：http://dali.shuidangran.top/Article/details/gtemmsbaai.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cashguo.top/Article/details/gtzjnevpab.html

JS:   JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gtikqsrase.html

TS:   JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gtghutgxgq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj20258888.top/Article/details/gtrebkyqqu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gtelecilba.html

Ruby: JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtrolblhrd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtmgtgqdyu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sufxvd.cn/Article/details/gtitfooasq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jianghu66.top/Article/details/gtihbaxzjm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gtagzbluxc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gtatwkeghd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gtpzmejpql.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj202588.top/Article/details/gtakgvkhcz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ppjwa.cn/Article/details/gtqnivowjb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cheryme.top/Article/details/gturgnewfu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shangyingyoupin.top/Article/details/gtcwutktcq.html

[K04] 读取 JSON 文件
来源：http://dali.fzhhl.top/Article/details/gtmshzfcgr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gogol.net.cn/Article/details/gtbaluirqw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aizwys.cn/Article/details/gtapiulgft.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dashuyun.cn/Article/details/gtkbcahtfm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gtfjecgymt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yuxming.cn/Article/details/gtoshoepkv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hnxiangtu.top/Article/details/gtkexsmghi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sxryk.cn/Article/details/gtfdsbtwpu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gtbiwpryik.html

[K05] 深拷贝对象
来源：http://dali.xuetiantiany.cn/Article/details/gtrgafeyft.html

Py:   copy.deepcopy(obj)
来源：http://dali.bjfxy.top/Article/details/gtrjgiitbt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangshuangyany.cn/Article/details/gtddripomf.html

JS:   structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gtcmvqhwyy.html

TS:   structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gtoecwqgfz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hammf.cn/Article/details/gtfugpkybr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.kuanghao11.cn/Article/details/gtyzsaxlhl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tanke756.top/Article/details/gtebcurxhh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gzhubu.top/Article/details/gtnpfekarp.html


<!-- 参考信息 -->