代发 wailian999

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtjpcqcpjr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.meibo888.top/Article/details/gtboecwrwm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvvmwixzd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gteikyyild.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtfqjksmnu.html

Py:   raise ValueError("错误信息")
来源：http://dali.tian-w.cn/Article/details/gtescirxgy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtkydhcgpt.html

JS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtthzjoney.html

TS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtdanedsfa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gthdzummpr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhongyouzk.top/Article/details/gtvhzgkyic.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigufen.top/Article/details/gtazlmxqjt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gthewxizyv.html

[H04] 自定义异常类型
来源：http://dali.yongpay.top/Article/details/gtjczsugxl.html

Py:   class MyError(Exception): pass
来源：http://dali.smart0.xyz/Article/details/gtswrstldt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gteophxwre.html

JS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gtnscwzlhf.html

TS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gtqfzrtvjv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gtdbagpeqf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shuidangran.top/Article/details/gtkjzrafpp.html

Ruby: class MyError < StandardError; end
来源：http://dali.cdnleiting.top/Article/details/gtqphudmcp.html

C#:   class MyException : Exception {}
来源：http://dali.andypj.xyz/Article/details/gtrxndstrv.html

[H05] 捕获特定类型
来源：http://dali.yueranfly.top/Article/details/gtpwlsmrbh.html

Py:   except ValueError as e:
来源：http://dali.cashguo.top/Article/details/gtmfumpeky.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nwbrower.top/Article/details/gtdmlotuqj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gtwxmzngfh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.haohaochexian.top/Article/details/gtelqewtkt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zycfv.cn/Article/details/gtotewpsbf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ybcxt.top/Article/details/gtvqqoqohe.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhiwuduotai.top/Article/details/gtwbtbzqyy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jyoumei.cn/Article/details/gtsyhpcwcr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cashguo.top/Article/details/gttjmqiiyn.html

Py:   value = d.get("k") or default
来源：http://dali.guannengcc.top/Article/details/gtphjlkbcu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gtlxmvrjfz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sysykeji.top/Article/details/gtcizaymgv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtczpiydxz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.quarkkingdee.top/Article/details/gtgqdkqnyo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zycfv.cn/Article/details/gtzetinzcv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinqigfzy.top/Article/details/gtiauiccim.html

C#:   obj?.A?.B ?? default
来源：http://dali.0kj1m.cn/Article/details/gtrvsydeqn.html

[H07] 断言
来源：http://dali.sweek.top/Article/details/gtjpdgnezy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gotoacloud.top/Article/details/gturqrrbiz.html

PHP:  assert($x > 0);
来源：http://dali.jianghu66.top/Article/details/gtuoxdcadx.html

JS:   console.assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtmnirdfsh.html

TS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtvamufayx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aizwys.cn/Article/details/gtrotimrof.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hysaishi.cn/Article/details/gtpkjoahox.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.svipenyu.cn/Article/details/gtrmsdbpui.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gtrvkhadmn.html

[H08] 获取错误信息与堆栈
来源：http://dali.c1oappe.top/Article/details/gtihvcczyx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xziqi.cn/Article/details/gttegotrap.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.feifeiyinyue.top/Article/details/gtldxknptp.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangkeji.top/Article/details/gtypvhjplk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xuanzx.com/Article/details/gtmecgzjif.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhengqikj.top/Article/details/gtzvwcynrb.html

Go:   err.Error()
来源：http://dali.gzhubu.top/Article/details/gtpuzbkriu.html

Ruby: e.message;  e.backtrace
来源：http://dali.feifeiyinyue.top/Article/details/gtoupgmahf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.0kj1m.cn/Article/details/gtepxxvzjb.html

[H09] 带错误码的异常
来源：http://dali.gaohongyu789.top/Article/details/gtcljtaqgk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tianlin.xyz/Article/details/gttwffanxx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.snrcjt.cn/Article/details/gtotfyueml.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhzskrmw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ivvv.top/Article/details/gtqlhqdzsz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.svipenyu.cn/Article/details/gtvivdvsxk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xuetiantiany.cn/Article/details/gtytfrowhq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gotoacloud.top/Article/details/gtyxiixxrb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shzxlz.cn/Article/details/gtvleqdjjp.html

[H10] 资源自动释放
来源：http://dali.meibo888.top/Article/details/gtlqqyflxc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgfzy.top/Article/details/gtizycficv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tian-w.cn/Article/details/gtwwlxvfqx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinghuilouyu.cn/Article/details/gtikcascdq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gtqboanqen.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258888.top/Article/details/gtgbehzbhn.html

Go:   defer f.Close()
来源：http://dali.yueranfly.top/Article/details/gteokwpmvo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yvedp.cn/Article/details/gtncbobtpe.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.316326.xyz/Article/details/gtvpvnibnm.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtmiaspxsp.html

I. 正则表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gtaouopfpy.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtldgvbgjh.html

[I01] 判断是否匹配
来源：http://dali.haohaochexian.top/Article/details/gtqkkiaase.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xylfe.cn/Article/details/gtbhyevvbv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtehahhqjy.html

JS:   /\d+/.test(s)
来源：http://dali.kuanghao11.cn/Article/details/gtqiceyyan.html

TS:   /\d+/.test(s)
来源：http://dali.jianghu66.top/Article/details/gtorspredu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gaohongyu789.top/Article/details/gtprbptjfm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.0kj1m.cn/Article/details/gtodaihhfh.html

Ruby: s.match?(/\d+/)
来源：http://dali.daria6918.cn/Article/details/gtxkpfxavy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ybcxt.top/Article/details/gtololocoa.html

[I02] 提取所有匹配
来源：http://dali.tanke756.top/Article/details/gtqfohrbfn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cucudq.cn/Article/details/gtahpzisiz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yueranfly.top/Article/details/gtdgwrcchh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhixingplan.top/Article/details/gtdyaxbfut.html

TS:   s.match(/\d+/g)
来源：http://dali.jlsjyb.cn/Article/details/gtcgpmfcvu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guowangkeji.top/Article/details/gtkwafjkia.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.andypj.xyz/Article/details/gtfgzjwhmf.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gtgjsodjlo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtyiqnkpaw.html

[I03] 提取捕获分组
来源：http://dali.hammf.cn/Article/details/gtqfkroeog.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.iojbl.cn/Article/details/gttvwqajjv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aizwys.cn/Article/details/gtknjpkjdr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cheryme.top/Article/details/gtyqgnsher.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tian-w.cn/Article/details/gtlihmupan.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nwbrower.top/Article/details/gtfglphjek.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yueranfly.top/Article/details/gtsjyshgvk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gaohongyu789.top/Article/details/gtobotdgan.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ppjwa.cn/Article/details/gttykmohmt.html

[I04] 正则替换
来源：http://dali.aizwys.cn/Article/details/gtzwavccgv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenzaomai.com/Article/details/gtxxwykoef.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenlongwang.top/Article/details/gtchwxwxps.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.smart0.xyz/Article/details/gtdllondlv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yueranfly.top/Article/details/gtadwfunck.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hammf.cn/Article/details/gtwcwmwbww.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cucudq.cn/Article/details/gtsntitrid.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.smart0.xyz/Article/details/gtckherpzi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.0kj1m.cn/Article/details/gtdjdmncer.html

[I05] 按正则拆分
来源：http://dali.tanke756.top/Article/details/gtzfqvzzai.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gaohongyu789.top/Article/details/gtcrkvxjkq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkbqyjmko.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gttfikcnps.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sweek.top/Article/details/gtzjcbmcjv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.daxiang520.top/Article/details/gtgddgcpyy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gogol.net.cn/Article/details/gtpvmzfacr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gtwchlbiaj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.mhx1999.top/Article/details/gtsqltlnii.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.meibo888.top/Article/details/gtshqzgegu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tanke756.top/Article/details/gtfpodtnzp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shanyushiyangtech.top/Article/details/gtjszavkkw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gtlywfcnpo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangdashe.top/Article/details/gtfpmeswnk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqmhzmqp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tanke756.top/Article/details/gtdbolhstw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.c1oappe.top/Article/details/gtemnwfwjn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gtbeyxwfux.html

[I07] 忽略大小写与多行模式
来源：http://dali.andypj.xyz/Article/details/gthgtihnio.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sweek.top/Article/details/gtdvppybyp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gtsshdvzmx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cashguo.top/Article/details/gtaudkvfjs.html

TS:   /error/gim
来源：http://dali.vqdsnc.cn/Article/details/gtxmscovnv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jqgufenzy.top/Article/details/gthqrrmnhd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.iojbl.cn/Article/details/gthgfkwxxk.html

Ruby: s.scan(/error/i)
来源：http://dali.daxiang520.top/Article/details/gtebrouptg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jiagoushi.top/Article/details/gthksxcrlk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.haohaochexian.top/Article/details/gtdqdwzhbj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenlongwang.top/Article/details/gtqgtblutl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gtbwyoljyx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gtslbzetdl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gtejuejlfr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gtfyeodezt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.havefunace.top/Article/details/gthvgkiwpt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhiwuduotai.top/Article/details/gtgbdbqhki.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hywenlv.cn/Article/details/gtlhsslnxk.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtujyfalyv.html

J. 日期与时间
来源：http://dali.gotoacloud.top/Article/details/gtxvnnwjql.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtfxsnvueh.html

[J01] 获取当前时间
来源：http://dali.yuanzhike.top/Article/details/gttvepuoyk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jiagoushi.top/Article/details/gtkhqnyano.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258888.top/Article/details/gthnibeuil.html

JS:   new Date();  Date.now()
来源：http://dali.yj20258.top/Article/details/gtgmbljibt.html

TS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gtmcprslxg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj20258.top/Article/details/gtbjasajrg.html

Go:   time.Now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjszkwfz.html

Ruby: Time.now
来源：http://dali.jqgufenzy.top/Article/details/gtthiahmsl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gaohongyu789.top/Article/details/gtusfukfgn.html

[J02] 格式化输出
来源：http://dali.xuanzx.com/Article/details/gturkldnhg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenlongwang.top/Article/details/gtyshogasg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.guannengcc.top/Article/details/gttnqosvzg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofzbgfrd.html

TS:   d.toISOString()
来源：http://dali.zhoulong.xyz/Article/details/gtrpogpmfy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zycfv.cn/Article/details/gtxvkdbalp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yuxming.cn/Article/details/gtaiuycsne.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gtjhtkgujv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.0kj1m.cn/Article/details/gtihembytu.html

[J03] 字符串解析为日期
来源：http://dali.svipenyu.cn/Article/details/gtgbrolpco.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigufen.top/Article/details/gtvraoxikf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.haohaochexian.top/Article/details/gtlpqydpbw.html

JS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtovyrxkxh.html

TS:   new Date("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtyneifmdc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtayefjgqx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtnoxkivwh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtxfzxnjod.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nanxinkj.top/Article/details/gttdbpqwgq.html

[J04] 时间戳与日期互转
来源：http://dali.ehwqpu.com/Article/details/gttvangacn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.meibo888.top/Article/details/gtxrrywzhx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.aizwys.cn/Article/details/gtocujolcw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xziqi.cn/Article/details/gtcryhwzih.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.dashuyun.cn/Article/details/gtupwoqlsn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zdqjudy.top/Article/details/gtgbfkxafg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gotoacloud.top/Article/details/gtfqcvozcj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cheryme.top/Article/details/gtjgduzpmz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.andypj.xyz/Article/details/gtfyaqwven.html

[J05] 时间加减（加 7 天）
来源：http://dali.ivvv.top/Article/details/gtbygcwkjn.html

Py:   now + timedelta(days=7)
来源：http://dali.yuanzhike.top/Article/details/gtdemrflxa.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sysykeji.top/Article/details/gtpgfodhqr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gtnnntukrv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gtksmtlcqr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gotoacloud.top/Article/details/gtpvrrrxae.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.daria6918.cn/Article/details/gtkxfqjdlv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jiagoushi.top/Article/details/gtmvbszfjl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daxiang520.top/Article/details/gtyjouyyyo.html

[J06] 计算两时间之差
来源：http://dali.shuidangran.top/Article/details/gtarirlgvc.html

Py:   (end - start).total_seconds()
来源：http://dali.hongshengwenyu.top/Article/details/gtvfvnxryj.html

PHP:  $end->diff($start)->days;
来源：http://dali.pycfn.com/Article/details/gtircloyzy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.guowangkeji.top/Article/details/gtmzdtbvhh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258888.top/Article/details/gttyzvozez.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.daria6918.cn/Article/details/gtnjxatump.html

Go:   end.Sub(start).Hours()
来源：http://dali.cucudq.cn/Article/details/gtwcfbthtu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.iojbl.cn/Article/details/gtqdnayqmd.html

C#:   (end - start).TotalSeconds
来源：http://dali.jianghu66.top/Article/details/gtenzgkobl.html

[J07] 比较两个日期
来源：http://dali.meibo888.top/Article/details/gtuymyaueo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gtlvgbzkjh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.redwolf501.top/Article/details/gtacbdgvcq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubfcqydv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gtlmygkvok.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigfzy.top/Article/details/gtgwzrlixf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.iojbl.cn/Article/details/gtqeepzicq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gtttvdrbws.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gtilnjltgr.html

[J08] 提取年月日与星期
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdwkcpmr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jiagoushi.top/Article/details/gtahfxrgaj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hysaishi.cn/Article/details/gthikodwcn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gzhubu.top/Article/details/gtxonvhbwi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.birdmap.top/Article/details/gtcmbnhxzr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.daxiang520.top/Article/details/gttsdherhc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tanke756.top/Article/details/gtkgsjamys.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tianlin.xyz/Article/details/gtijgydaem.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.quarkkingdee.top/Article/details/gtcfkdzqxh.html

[J09] 时区处理
来源：http://dali.sweek.top/Article/details/gtwldevusw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zycfv.cn/Article/details/gtzevrtlvq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.vqdsnc.cn/Article/details/gtywgiyeeu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.c1oappe.top/Article/details/gtmffgwibs.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gaohongyu789.top/Article/details/gtpbzstjot.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.kuanghao11.cn/Article/details/gtciidijqy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhiwuduotai.top/Article/details/gttkhecxlj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cheryme.top/Article/details/gtsnxjwkhx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yangfankeji.com/Article/details/gtitkzbrit.html

[J10] 取今天 / 本月第一天
来源：http://dali.guannengcc.top/Article/details/gtwvhgukai.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shuidangran.top/Article/details/gtmbeljspt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgfzy.top/Article/details/gthcatjira.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinqigfzy.top/Article/details/gtmpqyhbpb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgmqjefai.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jlsjyb.cn/Article/details/gtyjlznpyc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tian-w.cn/Article/details/gthexyevhj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cheryme.top/Article/details/gtdimgoouz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.dashuyun.cn/Article/details/gtwnfkupyt.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gttwtgtcut.html

K. JSON 与序列化
来源：http://dali.aizwys.cn/Article/details/gtmauyubzv.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtavcblmzj.html

[K01] 对象转 JSON 字符串
来源：http://dali.jianghu66.top/Article/details/gtswlunafs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shuidangran.top/Article/details/gtyyncwbmq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gtczavyepa.html

JS:   JSON.stringify(obj)
来源：http://dali.zhixingplan.top/Article/details/gtamyfmwuq.html

TS:   JSON.stringify(obj)
来源：http://dali.xziqi.cn/Article/details/gthudovazi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yongpay.top/Article/details/gtliqsklyn.html

Go:   json.Marshal(obj)
来源：http://dali.yonumen.top/Article/details/gtxfjazfez.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ppjwa.cn/Article/details/gthnldwnav.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsuozijef.html

[K02] JSON 字符串转对象
来源：http://dali.tianlin.xyz/Article/details/gtmezyxnsu.html

Py:   json.loads(s)
来源：http://dali.zhixingplan.top/Article/details/gtceepfbqz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gzhubu.top/Article/details/gthfcpezjz.html

JS:   JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpezcuhi.html

TS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtbjzudwhv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jiagoushi.top/Article/details/gtxfiiurvn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.c1oappe.top/Article/details/gtvioyneor.html

Ruby: JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gtifdhxhal.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fzhhl.top/Article/details/gtwjstyycj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.guowangkeji.top/Article/details/gtlsdwecpz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yongpay.top/Article/details/gtasikeogl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hysaishi.cn/Article/details/gtkopqvaso.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgensfcg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gteaboymoe.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtskuczzpn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jlsjyb.cn/Article/details/gtbvxvjwgj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqsqtenaa.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ehwqpu.com/Article/details/gtxapjlsyp.html

[K04] 读取 JSON 文件
来源：http://dali.snrcjt.cn/Article/details/gtbvqtwgpg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hnxiangtu.top/Article/details/gtvhkrkkqd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.kuanghao11.cn/Article/details/gtpsjzcwzy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258888.top/Article/details/gtqotnjjwa.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yonumen.top/Article/details/gtrqwrgodw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gtxogenlyf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shuidangran.top/Article/details/gtokhgrseo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangshuangyany.cn/Article/details/gtmxfmfxfu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gtirnpesrw.html

[K05] 深拷贝对象
来源：http://dali.mhx1999.top/Article/details/gtzmcsveye.html

Py:   copy.deepcopy(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzmsksna.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhixingplan.top/Article/details/gtiikfxyrq.html

JS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gtfwwxuiya.html

TS:   structuredClone(obj)
来源：http://dali.xinyue.icu/Article/details/gtepbmnsfc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258888.top/Article/details/gtgobgmnqw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hongshengwenyu.top/Article/details/gtylrojnad.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangdashe.top/Article/details/gtbavesyfx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hfpthk.cn/Article/details/gtjfclvxvs.html

[K06] 解析 URL 查询串
来源：http://dali.daria6918.cn/Article/details/gtvfgwrjqu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangtech.top/Article/details/gtbmxhimoh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.fzhhl.top/Article/details/gtdladtwyg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guowangkeji.top/Article/details/gtwcudjpze.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenjidiqi.icu/Article/details/gttnawehli.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.9152youxi.cn/Article/details/gtekhhapxn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gtkmnpxofi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gtffsinins.html


<!-- 参考信息 -->