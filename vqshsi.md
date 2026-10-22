代发 wailian999

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jlsjyb.cn/Article/details/gthumzocjt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dianchejie.cn/Article/details/gtwmdjcmpq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.svipenyu.cn/Article/details/gtgcftkfpt.html

[H02] finally / ensure 收尾
来源：http://dali.gogol.net.cn/Article/details/gtawpvudtt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hongshengwenyu.top/Article/details/gtuiwposjg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtrkzwhbtu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gthjutozgu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtorcrzddv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtbifjufzd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenjidiqi.icu/Article/details/gtlwvyevan.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tanke756.top/Article/details/gtwcpbfjeq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwkyriqgi.html

[H03] 主动抛出异常
来源：http://dali.bjfxy.top/Article/details/gtiajcdcnm.html

Py:   raise ValueError("错误信息")
来源：http://dali.hfpthk.cn/Article/details/gtqozmlffx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gtdwpqbuiq.html

JS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtbvwmzzwl.html

TS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtghcwepzg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtkgldhpfn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gtlrtqxcoz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.andypj.xyz/Article/details/gtfhbxjnex.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtkbnztvrl.html

[H04] 自定义异常类型
来源：http://dali.jlsjyb.cn/Article/details/gtirfdiwrz.html

Py:   class MyError(Exception): pass
来源：http://dali.mhx1999.top/Article/details/gtwgoobgsl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gtoyftnbuv.html

JS:   class MyError extends Error {}
来源：http://dali.ybcxt.top/Article/details/gttxswjhts.html

TS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gtgvvpsndy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gtnjnudvvx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgfzy.top/Article/details/gtqxdnhqzz.html

Ruby: class MyError < StandardError; end
来源：http://dali.xziqi.cn/Article/details/gtgjbufkcu.html

C#:   class MyException : Exception {}
来源：http://dali.sufxvd.cn/Article/details/gttlbhtpsw.html

[H05] 捕获特定类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtgbghsjxq.html

Py:   except ValueError as e:
来源：http://dali.zhoulong.xyz/Article/details/gtnxhknavd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gogol.net.cn/Article/details/gtwgzadagi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gtvzcmmizv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hysaishi.cn/Article/details/gtjjihrhql.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.bjfxy.top/Article/details/gtfhvgowdr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ydzc1.top/Article/details/gtkbyahaza.html

Ruby: rescue ArgumentError => e
来源：http://dali.jlsjyb.cn/Article/details/gtqnpjngru.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cqqwz.cn/Article/details/gtfxddzfxh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.aizwys.cn/Article/details/gtzvplcpdr.html

Py:   value = d.get("k") or default
来源：http://dali.tianlin.xyz/Article/details/gtnmdpbpnx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hammf.cn/Article/details/gtofjnpkkv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ivvv.top/Article/details/gtxhqavpdz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmqkbktu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.svipenyu.cn/Article/details/gtordvgfia.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.fzhhl.top/Article/details/gtlyitgvct.html

Ruby: d&.dig(:a, :b)
来源：http://dali.snrcjt.cn/Article/details/gtxlbspeyu.html

C#:   obj?.A?.B ?? default
来源：http://dali.yangfankeji.com/Article/details/gttqivhted.html

[H07] 断言
来源：http://dali.haohaochexian.top/Article/details/gtesmyknuz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jlsjyb.cn/Article/details/gtyrhfkwid.html

PHP:  assert($x > 0);
来源：http://dali.dashuyun.cn/Article/details/gturapfyza.html

JS:   console.assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtaggyxspd.html

TS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtsjaxfdmx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.quarkkingdee.top/Article/details/gtvudyqlui.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gotoacloud.top/Article/details/gtaejxbqqv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sysykeji.top/Article/details/gtjlbkacum.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtqotxqych.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gttxwognth.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sufxvd.cn/Article/details/gtlpduozve.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.svipenyu.cn/Article/details/gtlzlmwmrj.html

JS:   e.message;  e.stack
来源：http://dali.shuidangran.top/Article/details/gtrnnkdgag.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cashguo.top/Article/details/gtmhyxcwrm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.guowangkeji.top/Article/details/gtfdikxqac.html

Go:   err.Error()
来源：http://dali.iojbl.cn/Article/details/gtspndaqgw.html

Ruby: e.message;  e.backtrace
来源：http://dali.gotoacloud.top/Article/details/gteqhfpkvm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhongyouzk.top/Article/details/gtdzlvwqyc.html

[H09] 带错误码的异常
来源：http://dali.hongshengwenyu.top/Article/details/gtrsbrbsuj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tian-w.cn/Article/details/gtjgotuveb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gogol.net.cn/Article/details/gtemgwllud.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sweek.top/Article/details/gtyxqlrxdc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gzhubu.top/Article/details/gtptmpitnv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sweek.top/Article/details/gtcvsxloqr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.vqdsnc.cn/Article/details/gtyemibwfi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yongpay.top/Article/details/gttjnwmxtl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtflkeymse.html

[H10] 资源自动释放
来源：http://dali.yanxiufei.cn/Article/details/gtmpnilvdp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinqigufen.top/Article/details/gtuysxnkxy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.guannengcc.top/Article/details/gtsmhvnhzk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcrheblyi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gzhubu.top/Article/details/gtexyhdzph.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.havefunace.top/Article/details/gtkpuncttu.html

Go:   defer f.Close()
来源：http://dali.quarkkingdee.top/Article/details/gtqcczrpkk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigufen.top/Article/details/gtrkhclzrp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtnzegxfkw.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtefretupn.html

I. 正则表达式
来源：http://dali.hnqzz.top/Article/details/gtbbtdtjnp.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtrvlvidui.html

[I01] 判断是否匹配
来源：http://dali.yongpay.top/Article/details/gtveqpyqco.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jlsjyb.cn/Article/details/gtdttdeqbv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gttotzfxwi.html

JS:   /\d+/.test(s)
来源：http://dali.jqgfzy.top/Article/details/gtbvrgrkjf.html

TS:   /\d+/.test(s)
来源：http://dali.daria6918.cn/Article/details/gtxyweuewx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.daria6918.cn/Article/details/gtewxfcfaz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtkwzxnpxq.html

Ruby: s.match?(/\d+/)
来源：http://dali.shangyingyoupin.top/Article/details/gthjmdokbk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlmhxrixb.html

[I02] 提取所有匹配
来源：http://dali.jlsjyb.cn/Article/details/gtvshndtkk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj20258888.top/Article/details/gtihpbtycc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ydzc1.top/Article/details/gtssmaggly.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zycfv.cn/Article/details/gthrdaaqji.html

TS:   s.match(/\d+/g)
来源：http://dali.jqgfzy.top/Article/details/gtuuokwlkm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtobxiytfu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gtwltbbecc.html

Ruby: s.scan(/\d+/)
来源：http://dali.cashguo.top/Article/details/gttetkvrkv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.fengsongda.top/Article/details/gthlbvnowk.html

[I03] 提取捕获分组
来源：http://dali.gzhubu.top/Article/details/gtelvrpxex.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgculnnw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ybcxt.top/Article/details/gtfwlyqaua.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.c1oappe.top/Article/details/gttnzqbhxv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jianghu66.top/Article/details/gtqicindeq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.9152youxi.cn/Article/details/gtlnkgiejw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.haohaochexian.top/Article/details/gtedvhucmu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shzxlz.cn/Article/details/gtksbztcbz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jyoumei.cn/Article/details/gttgvpqvkm.html

[I04] 正则替换
来源：http://dali.svipenyu.cn/Article/details/gtnbqortrm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.snrcjt.cn/Article/details/gtjaiemnym.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cdnleiting.top/Article/details/gtwwcdkbpz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cucudq.cn/Article/details/gtzzgqopyn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ehwqpu.com/Article/details/gtwsxvdulg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.birdmap.top/Article/details/gtxyaarvhm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gthusmoopv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hysaishi.cn/Article/details/gtadantiji.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jyoumei.cn/Article/details/gtfijebbue.html

[I05] 按正则拆分
来源：http://dali.birdmap.top/Article/details/gtawnlaaij.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xylfe.cn/Article/details/gtpvjtzdpr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjaqftfct.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gtbeaupasr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gtgnbdgapm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj20258888.top/Article/details/gtsscyvkzy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xylfe.cn/Article/details/gtboikltxx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gtzukjykts.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.316326.xyz/Article/details/gtxjmdkthn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gaohongyu789.top/Article/details/gtvumuhmey.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gtpiuqcznn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.dashuyun.cn/Article/details/gtezqrlxso.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cqqwz.cn/Article/details/gtywntfrhw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuanzhike.top/Article/details/gtqqxpijds.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ivvv.top/Article/details/gtpsubxqfw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinqigfzy.top/Article/details/gtqgnrgdjb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258.top/Article/details/gtuwxketsu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtwtovmnsm.html

[I07] 忽略大小写与多行模式
来源：http://dali.tian-w.cn/Article/details/gtskmrrgcd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.smart0.xyz/Article/details/gtvxvkjmpq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.daria6918.cn/Article/details/gttxomhfte.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shangyingyoupin.top/Article/details/gtcuvyrfdw.html

TS:   /error/gim
来源：http://dali.feifeiyinyue.top/Article/details/gtmkvvgsgb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hysaishi.cn/Article/details/gticsptwha.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.smart0.xyz/Article/details/gtabmckvfz.html

Ruby: s.scan(/error/i)
来源：http://dali.yvedp.cn/Article/details/gtteltvmll.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cqqwz.cn/Article/details/gtnwfwsslc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shuidangran.top/Article/details/gtwbmdqzyo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.haohaochexian.top/Article/details/gturrjkadh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cheryme.top/Article/details/gtoxivbjil.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xylfe.cn/Article/details/gthbocopxw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgfzy.top/Article/details/gtozoerhfp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nanxuanxn.top/Article/details/gtpriasncf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hammf.cn/Article/details/gtcpjxforl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cqqwz.cn/Article/details/gtcvgkyxyx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj202588.top/Article/details/gtbqnpwtfh.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtiasjopbi.html

J. 日期与时间
来源：http://dali.chenlongwang.top/Article/details/gtungjnyqf.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtrmbztjsk.html

[J01] 获取当前时间
来源：http://dali.ppjwa.cn/Article/details/gtsdhkonlq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.wangdashe.top/Article/details/gtipnuqrgw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.birdmap.top/Article/details/gtywbcueco.html

JS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gtjuejoczm.html

TS:   new Date();  Date.now()
来源：http://dali.jyoumei.cn/Article/details/gtyfcslqmr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ydzc1.top/Article/details/gtwuqyilhn.html

Go:   time.Now()
来源：http://dali.hywenlv.cn/Article/details/gtabzidmyx.html

Ruby: Time.now
来源：http://dali.kuanghao11.cn/Article/details/gtvdlwdxwn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenjidiqi.icu/Article/details/gtldsmpzsa.html

[J02] 格式化输出
来源：http://dali.pycfn.com/Article/details/gtghcjiqnt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gtvuukbrxa.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xuetiantiany.cn/Article/details/gtunwizlel.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hongshengwenyu.top/Article/details/gtpwzsasmr.html

TS:   d.toISOString()
来源：http://dali.yj202588.top/Article/details/gtisewexpm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrbptoxt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.quarkkingdee.top/Article/details/gtikqgnjvu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yueranfly.top/Article/details/gtdvnmxrtd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.svipenyu.cn/Article/details/gtxrhqexbx.html

[J03] 字符串解析为日期
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqnwkrshr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cucudq.cn/Article/details/gtiwqtxsww.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yongpay.top/Article/details/gtuhcfsrcm.html

JS:   new Date("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtrnagvdrz.html

TS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtixkyghld.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtilezmdcz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtttopdqvr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtfkdekwfg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yangfankeji.com/Article/details/gtthcdslsk.html

[J04] 时间戳与日期互转
来源：http://dali.chenzaomai.com/Article/details/gtrqryayor.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gaohongyu789.top/Article/details/gtsbiyhgxg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhoulong.xyz/Article/details/gtdemmydpn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigufen.top/Article/details/gtwnnyjhul.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hnxiangtu.top/Article/details/gtjrcxahmv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtkbsnzgny.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pycfn.com/Article/details/gtgglxwpyr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ivvv.top/Article/details/gtmudnbfag.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guowangkeji.top/Article/details/gtfntahnyo.html

[J05] 时间加减（加 7 天）
来源：http://dali.aizwys.cn/Article/details/gtjgiepria.html

Py:   now + timedelta(days=7)
来源：http://dali.zdqjudy.top/Article/details/gtdrtcvquh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hfpthk.cn/Article/details/gtigauzeon.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gtqrckkwrk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenzaomai.com/Article/details/gtjzyzsbgj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ydzc1.top/Article/details/gtfmykcpij.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dashuyun.cn/Article/details/gtyvmjasoe.html

Ruby: Time.now + 7 * 86400
来源：http://dali.guannengcc.top/Article/details/gtmrdcbsbo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.birdmap.top/Article/details/gtaomuydom.html

[J06] 计算两时间之差
来源：http://dali.xinyue.icu/Article/details/gtnypruxyh.html

Py:   (end - start).total_seconds()
来源：http://dali.kuanghao11.cn/Article/details/gtgzmzvsjg.html

PHP:  $end->diff($start)->days;
来源：http://dali.cucudq.cn/Article/details/gtxgeggdvo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yongpay.top/Article/details/gtxkoomruu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zdqjudy.top/Article/details/gtfyuakszb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinqigfzy.top/Article/details/gtkuueghfb.html

Go:   end.Sub(start).Hours()
来源：http://dali.bjfxy.top/Article/details/gtenazxhot.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj202588.top/Article/details/gtluyqjzfq.html

C#:   (end - start).TotalSeconds
来源：http://dali.daria6918.cn/Article/details/gtwmhnjbmj.html

[J07] 比较两个日期
来源：http://dali.chenlongwang.top/Article/details/gtteghwpkf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gtmlzppxoz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.c1oappe.top/Article/details/gtinykstox.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hammf.cn/Article/details/gtcqnpvbjk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gtunhulwdz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.9152youxi.cn/Article/details/gttoeovrgv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sysykeji.top/Article/details/gtdynjivho.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtwmafenup.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtkkljwnbt.html

[J08] 提取年月日与星期
来源：http://dali.yuxming.cn/Article/details/gtwrmboltr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sufxvd.cn/Article/details/gtmpazzxmr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yonumen.top/Article/details/gtzcdyogjr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guowangkeji.top/Article/details/gtypaqxles.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.pycfn.com/Article/details/gtdnoirokb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenzaomai.com/Article/details/gthpfovzfy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.dianchejie.cn/Article/details/gtkpjbqreh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yanxiufei.cn/Article/details/gtdtsncbxk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinqigufen.top/Article/details/gtpcwjcpyv.html

[J09] 时区处理
来源：http://dali.ppjwa.cn/Article/details/gtltvsiwox.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jlsjyb.cn/Article/details/gtvgywlkzz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzmztcrg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gtzmbfdokc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daxiang520.top/Article/details/gtadfixous.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ivvv.top/Article/details/gtrqukqork.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shzxlz.cn/Article/details/gtcpiodsrb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aizwys.cn/Article/details/gtbqkortol.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.iojbl.cn/Article/details/gtjyawgprk.html

[J10] 取今天 / 本月第一天
来源：http://dali.yangfankeji.com/Article/details/gtjwprrzwn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.316326.xyz/Article/details/gthhotvoom.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtatqmavpv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxuanxn.top/Article/details/gteahbliex.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.mhx1999.top/Article/details/gtnmekwaqp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.guannengcc.top/Article/details/gtemrjrljx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.mhx1999.top/Article/details/gtyupcvsnm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinghuilouyu.cn/Article/details/gtqdkpryiz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.0kj1m.cn/Article/details/gtbrqvlktd.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyfokgdxh.html

K. JSON 与序列化
来源：http://dali.yueranfly.top/Article/details/gtrfrewgso.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtveffqwsc.html

[K01] 对象转 JSON 字符串
来源：http://dali.nwbrower.top/Article/details/gtpfwavxra.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyglykngs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sysykeji.top/Article/details/gtzqcsfyhu.html

JS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gtxvdfameu.html

TS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gtmzcvgdfe.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjaawygux.html

Go:   json.Marshal(obj)
来源：http://dali.guowangkeji.top/Article/details/gtffxycztq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnxiangtu.top/Article/details/gtlfrmwoel.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guannengcc.top/Article/details/gtogcgmegy.html

[K02] JSON 字符串转对象
来源：http://dali.nwbrower.top/Article/details/gthpdezqxt.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gtvfbmmvfm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.kuanghao11.cn/Article/details/gtmzkmigel.html

JS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gtalxjmcgy.html

TS:   JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gtvonoqhbs.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.andypj.xyz/Article/details/gtsjbndzww.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gtanuyezhp.html

Ruby: JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gtnhxswbbb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shuidangran.top/Article/details/gtvldomxpm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cheryme.top/Article/details/gtoincbiic.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hysaishi.cn/Article/details/gthhehwiap.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.0kj1m.cn/Article/details/gtbeiybkkh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.snrcjt.cn/Article/details/gtlapplgcl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gtyjdmrxfk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yangfankeji.com/Article/details/gtcyphajwo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.guowangkeji.top/Article/details/gtutnknrci.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtjfoqdadk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkqkqiybe.html

[K04] 读取 JSON 文件
来源：http://dali.gotoacloud.top/Article/details/gtxyvgayec.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nanxinkj.top/Article/details/gtlkzcmvta.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cheryme.top/Article/details/gtdvmxfbwz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gtxrltjizc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gogol.net.cn/Article/details/gtvzwahykc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hysaishi.cn/Article/details/gtbpukcndb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ivvv.top/Article/details/gtxqkasprt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.dashuyun.cn/Article/details/gtsuufvglm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xylfe.cn/Article/details/gtfomgyvtw.html

[K05] 深拷贝对象
来源：http://dali.jlsjyb.cn/Article/details/gtxexodrkw.html

Py:   copy.deepcopy(obj)
来源：http://dali.fzhhl.top/Article/details/gtqtyzrhkz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.9152youxi.cn/Article/details/gtezfcougz.html

JS:   structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gtswcxtluz.html

TS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gtqorjhdqm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnqzz.top/Article/details/gtuswhzews.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jiagoushi.top/Article/details/gtymrawkyp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangdashe.top/Article/details/gtoebccjkt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.vqdsnc.cn/Article/details/gtdimkawlb.html


<!-- 参考信息 -->