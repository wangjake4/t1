代发 wailian999

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtkiqzjhje.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nanxuanxn.top/Article/details/gtanlskuug.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gotoacloud.top/Article/details/gtuzibebvl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtmdvbxqzg.html

[H03] 主动抛出异常
来源：http://dali.ivvv.top/Article/details/gtsomcmhoy.html

Py:   raise ValueError("错误信息")
来源：http://dali.gogol.net.cn/Article/details/gtsbhqwrnv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtkqjycirq.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtshtbkeil.html

TS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtlktjksya.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtwrnmraez.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.0kj1m.cn/Article/details/gtomnzxxel.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cheryme.top/Article/details/gtmfmrkxha.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtqtwdzupi.html

[H04] 自定义异常类型
来源：http://dali.sweek.top/Article/details/gturkworpm.html

Py:   class MyError(Exception): pass
来源：http://dali.yanxiufei.cn/Article/details/gtqipsztqk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gtseavbvog.html

JS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gtfobrwova.html

TS:   class MyError extends Error {}
来源：http://dali.hysaishi.cn/Article/details/gtzyjeonpd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gtfevdtprn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xuanzx.com/Article/details/gtbgcsqyrt.html

Ruby: class MyError < StandardError; end
来源：http://dali.ybcxt.top/Article/details/gtxphpdroh.html

C#:   class MyException : Exception {}
来源：http://dali.sxryk.cn/Article/details/gtcwrxyrmv.html

[H05] 捕获特定类型
来源：http://dali.316326.xyz/Article/details/gtdflmdtsm.html

Py:   except ValueError as e:
来源：http://dali.jlsjyb.cn/Article/details/gteiivsuhn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenzaomai.com/Article/details/gtiylwaxet.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gtswhcsred.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yangfankeji.com/Article/details/gtgwtmsxfv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hfpthk.cn/Article/details/gtnxghsuez.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xuetiantiany.cn/Article/details/gtwposzxrh.html

Ruby: rescue ArgumentError => e
来源：http://dali.dashuyun.cn/Article/details/gtkusctbpz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhoulong.xyz/Article/details/gtizwubmcz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ydzc1.top/Article/details/gtpocvbtzg.html

Py:   value = d.get("k") or default
来源：http://dali.chenjidiqi.icu/Article/details/gtaiflfsrw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj20258.top/Article/details/gtzjoqspqb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.kuanghao11.cn/Article/details/gtjgbkrzyp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gtmcyxmgvw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenzaomai.com/Article/details/gtexlodloz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yangfankeji.com/Article/details/gtcvwddvhz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nwbrower.top/Article/details/gtbhugghpz.html

C#:   obj?.A?.B ?? default
来源：http://dali.sweek.top/Article/details/gtoizoybjf.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gtlqhojdvf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhixingplan.top/Article/details/gthzeasvbo.html

PHP:  assert($x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtcdzteqee.html

JS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqighvsu.html

TS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gtbdurcrmf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.meibo888.top/Article/details/gtivbvsdjp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj202588.top/Article/details/gtjyncmlcd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.havefunace.top/Article/details/gttybiwbxd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gtfoxzqecq.html

[H08] 获取错误信息与堆栈
来源：http://dali.guannengcc.top/Article/details/gttdjoibxg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.birdmap.top/Article/details/gtxthhnqnu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yuanzhike.top/Article/details/gtelmsjois.html

JS:   e.message;  e.stack
来源：http://dali.yuanzhike.top/Article/details/gtjofcykxm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yvedp.cn/Article/details/gtitwjvmxg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.havefunace.top/Article/details/gtjlcufocf.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gtqxfonrwn.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhiwuduotai.top/Article/details/gtyyogitti.html

C#:   e.Message;  e.StackTrace
来源：http://dali.guowangkeji.top/Article/details/gtkvyjasdf.html

[H09] 带错误码的异常
来源：http://dali.svipenyu.cn/Article/details/gtbsvweixv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hfpthk.cn/Article/details/gtpjijvzxt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhiwuduotai.top/Article/details/gtwznddoom.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaphbqadm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.birdmap.top/Article/details/gtvxzrmpkn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yanxiufei.cn/Article/details/gtzvlevhqb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcljbfkgj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.smart0.xyz/Article/details/gtagumwbsp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.snrcjt.cn/Article/details/gtzimbzmvb.html

[H10] 资源自动释放
来源：http://dali.hammf.cn/Article/details/gtwgvlqeil.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuetiantiany.cn/Article/details/gtcoretxvp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.redwolf501.top/Article/details/gtnkmosggw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dashuyun.cn/Article/details/gtlzdqkmzp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hongshengwenyu.top/Article/details/gtufomdlty.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258.top/Article/details/gtebhktkuk.html

Go:   defer f.Close()
来源：http://dali.chenlongwang.top/Article/details/gtzvdateqx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuanzhike.top/Article/details/gtlcdclpci.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtujcpxenx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtydoyebje.html

I. 正则表达式
来源：http://dali.nanxuanxn.top/Article/details/gtwspmukuc.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtpyfowfcn.html

[I01] 判断是否匹配
来源：http://dali.jinqigufen.top/Article/details/gteyssuzmh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gttblgjjpf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tanke756.top/Article/details/gtcjupooqd.html

JS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gttnwlfzig.html

TS:   /\d+/.test(s)
来源：http://dali.yongpay.top/Article/details/gtddwvgkjn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.pycfn.com/Article/details/gtmkolthvl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.dianchejie.cn/Article/details/gtrskcjqrr.html

Ruby: s.match?(/\d+/)
来源：http://dali.quarkkingdee.top/Article/details/gtxcodgnvg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj202588.top/Article/details/gteuzrukyo.html

[I02] 提取所有匹配
来源：http://dali.gzhubu.top/Article/details/gthsbntesv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gtwykhelha.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.smart0.xyz/Article/details/gtlqqsigqp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sufxvd.cn/Article/details/gtvojseswj.html

TS:   s.match(/\d+/g)
来源：http://dali.zhoulong.xyz/Article/details/gtgetxewwr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sufxvd.cn/Article/details/gtjmhycapz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jiagoushi.top/Article/details/gtipygcmtx.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxohduojk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenlongwang.top/Article/details/gthyhpvsii.html

[I03] 提取捕获分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsngjfwwm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ivvv.top/Article/details/gtcahcfgxb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ydzc1.top/Article/details/gtheoaxnez.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.redwolf501.top/Article/details/gtruutrtpg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cqqwz.cn/Article/details/gtugtdozsq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.svipenyu.cn/Article/details/gtmjcgaysr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ppjwa.cn/Article/details/gtgvksuzkd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.guannengcc.top/Article/details/gtquplrhqi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.iojbl.cn/Article/details/gtkozswfrc.html

[I04] 正则替换
来源：http://dali.ppjwa.cn/Article/details/gtbwhjzqpg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nanxinkj.top/Article/details/gturvdnrgh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtzfylzozu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yanxiufei.cn/Article/details/gtsepndwxn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gzhubu.top/Article/details/gtxejykkca.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhoulong.xyz/Article/details/gtalclnayb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.haohaochexian.top/Article/details/gtbointmyx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.dashuyun.cn/Article/details/gtxfazghsf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hnxiangtu.top/Article/details/gtrqqnpyot.html

[I05] 按正则拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckcctsps.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cdnleiting.top/Article/details/gtlhaivrjm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cashguo.top/Article/details/gtupznljhg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gtjwtzsouh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtwzsecoae.html

Java: s.split("\\s*,\\s*")
来源：http://dali.fzhhl.top/Article/details/gtavglksxn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenzaomai.com/Article/details/gtbsldwndm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gtiooefmor.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xuanzx.com/Article/details/gtonsfcegp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.havefunace.top/Article/details/gtuvhetwyp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gtmvudjhil.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yangfankeji.com/Article/details/gtnexurpwu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ybcxt.top/Article/details/gtsqxuftmh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gtqexrkvgm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gtrsqvzpzb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nanxuanxn.top/Article/details/gtevaukmfx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gzhubu.top/Article/details/gtyevjpcgo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gtvovisdbm.html

[I07] 忽略大小写与多行模式
来源：http://dali.cucudq.cn/Article/details/gtraqivdvf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gzhubu.top/Article/details/gtsestxocp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjljhhtlx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aibaodan.cn/Article/details/gtpdhbpgll.html

TS:   /error/gim
来源：http://dali.jyoumei.cn/Article/details/gtxyoagdpx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.mhx1999.top/Article/details/gtmiwovjum.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenlongwang.top/Article/details/gtuxwpoljg.html

Ruby: s.scan(/error/i)
来源：http://dali.jlsjyb.cn/Article/details/gtdcadikax.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hammf.cn/Article/details/gtuqxxltst.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cdnleiting.top/Article/details/gtkqqyfefj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gzhubu.top/Article/details/gthulvwtfe.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gtitpwikzn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gtxyzmnsvo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuxming.cn/Article/details/gtfwpjwvze.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.fengsongda.top/Article/details/gtgylsafxq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.c1oappe.top/Article/details/gtkkxserio.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.smart0.xyz/Article/details/gtwfybkkhx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhoulong.xyz/Article/details/gtsqxggbzl.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtkayqmiuo.html

J. 日期与时间
来源：http://dali.guowangkeji.top/Article/details/gtouxuqoet.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtqihmzlak.html

[J01] 获取当前时间
来源：http://dali.quarkkingdee.top/Article/details/gtsigzqisu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ppjwa.cn/Article/details/gtjmrqjdym.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gtxmnvitso.html

JS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gthrwvxubb.html

TS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gtircofoht.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dashuyun.cn/Article/details/gtageisdgn.html

Go:   time.Now()
来源：http://dali.guowangkeji.top/Article/details/gtgholwfea.html

Ruby: Time.now
来源：http://dali.jqgufenzy.top/Article/details/gtugalqaqc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.quarkkingdee.top/Article/details/gtdzxnxtlf.html

[J02] 格式化输出
来源：http://dali.jqgufenzy.top/Article/details/gtwvvydhwf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.birdmap.top/Article/details/gtfikfhozv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.guannengcc.top/Article/details/gthwabxiru.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cqqwz.cn/Article/details/gtxaplblbq.html

TS:   d.toISOString()
来源：http://dali.zhengqikj.top/Article/details/gtwfjxlkfg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xylfe.cn/Article/details/gtjjnecfqh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenlongwang.top/Article/details/gtqztoambf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shzxlz.cn/Article/details/gtmnbtjulg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sweek.top/Article/details/gtmgernaqk.html

[J03] 字符串解析为日期
来源：http://dali.zhaomingkeji.xyz/Article/details/gtseymobhz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj20258.top/Article/details/gtxriqsofo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jlsjyb.cn/Article/details/gtwedcxiol.html

JS:   new Date("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtprdjzeej.html

TS:   new Date("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtnforoiyr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtjalceaok.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtdyqgadjg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtrtmqpufc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.haohaochexian.top/Article/details/gtzhvlxtlt.html

[J04] 时间戳与日期互转
来源：http://dali.xziqi.cn/Article/details/gttqlzxhjo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.vqdsnc.cn/Article/details/gtekcdmyda.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.dianchejie.cn/Article/details/gtjcaclzay.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daria6918.cn/Article/details/gtkvihyjvw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.kuanghao11.cn/Article/details/gtgqngidcb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sufxvd.cn/Article/details/gtqegmctaa.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtbybnquid.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinqigufen.top/Article/details/gtfjdwvahp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xziqi.cn/Article/details/gtwokbnczd.html

[J05] 时间加减（加 7 天）
来源：http://dali.birdmap.top/Article/details/gthrllepkw.html

Py:   now + timedelta(days=7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthezuimzz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxgsbrwtj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yanxiufei.cn/Article/details/gtxaxyohys.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yueranfly.top/Article/details/gtbkfhdipr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sysykeji.top/Article/details/gthgnmccku.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sysykeji.top/Article/details/gtldahawdb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj202588.top/Article/details/gtqomdojjc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhixingplan.top/Article/details/gtmpbtwlto.html

[J06] 计算两时间之差
来源：http://dali.zdqjudy.top/Article/details/gtsynlaijx.html

Py:   (end - start).total_seconds()
来源：http://dali.yonumen.top/Article/details/gtzzsodygw.html

PHP:  $end->diff($start)->days;
来源：http://dali.sxryk.cn/Article/details/gtmjbywmqz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.pycfn.com/Article/details/gtsavaakmy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangshuangyany.cn/Article/details/gtkpukeopg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.meibo888.top/Article/details/gtpzfxtifg.html

Go:   end.Sub(start).Hours()
来源：http://dali.316326.xyz/Article/details/gtrdcufdxa.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigufen.top/Article/details/gtofpcxgrj.html

C#:   (end - start).TotalSeconds
来源：http://dali.birdmap.top/Article/details/gtkyziascx.html

[J07] 比较两个日期
来源：http://dali.jinqigfzy.top/Article/details/gtrlypicyb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtyxytyinm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xylfe.cn/Article/details/gtrorgfhsz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yvedp.cn/Article/details/gtajczqztb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.feifeiyinyue.top/Article/details/gtwosnesby.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yonumen.top/Article/details/gtshadinkx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xinyue.icu/Article/details/gtignwqucy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gtpxnffisd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtynchdrhx.html

[J08] 提取年月日与星期
来源：http://dali.nwbrower.top/Article/details/gtexmspfqz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.guowangkeji.top/Article/details/gtjdjksngl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sweek.top/Article/details/gtubnxeubi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xuanzx.com/Article/details/gtgehrskix.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj20258888.top/Article/details/gtcsozuldl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhixingplan.top/Article/details/gtpzeueftf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gzhubu.top/Article/details/gtzviiumqw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbpdzcxzq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuetiantiany.cn/Article/details/gtbtbhgmbg.html

[J09] 时区处理
来源：http://dali.havefunace.top/Article/details/gtaqixxptr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shzxlz.cn/Article/details/gtwfwrdfxk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tianlin.xyz/Article/details/gtlzisgbsi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.0kj1m.cn/Article/details/gtaaohsxsu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.9152youxi.cn/Article/details/gttuywtvio.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.iojbl.cn/Article/details/gtwwoaezrn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gaohongyu789.top/Article/details/gttlxllcpc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yonumen.top/Article/details/gtjssmecso.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sweek.top/Article/details/gthnjsrsxq.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuanzhike.top/Article/details/gtwigayzvm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ppjwa.cn/Article/details/gtdhqhuxkf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shzxlz.cn/Article/details/gtzodvvdvp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxuanxn.top/Article/details/gtrxylsgof.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.wangdashe.top/Article/details/gtmdsqrxlq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrtwcjvbr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jiagoushi.top/Article/details/gtesrppryq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hammf.cn/Article/details/gtgmujjgnf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.aizwys.cn/Article/details/gtqdoivato.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtgienokqh.html

K. JSON 与序列化
来源：http://dali.jyoumei.cn/Article/details/gtulqylixy.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtvvegokng.html

[K01] 对象转 JSON 字符串
来源：http://dali.0kj1m.cn/Article/details/gtsdhgoicn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hongshengwenyu.top/Article/details/gtbilkzzpx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gtgtrdsikb.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gtxrsysjuy.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gtquwyswpj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cashguo.top/Article/details/gtdpifutdm.html

Go:   json.Marshal(obj)
来源：http://dali.daxiang520.top/Article/details/gtcetglmet.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yonumen.top/Article/details/gtjxaoyhzz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbsrcpxex.html

[K02] JSON 字符串转对象
来源：http://dali.yueranfly.top/Article/details/gteyhfvika.html

Py:   json.loads(s)
来源：http://dali.jiagoushi.top/Article/details/gtezfqrthe.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenjidiqi.icu/Article/details/gtjdsjsfks.html

JS:   JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gtzhwprywq.html

TS:   JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gthmthpuhj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhengqikj.top/Article/details/gtrjgoptcc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gtmxmiyfwb.html

Ruby: JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gtaxisgrnd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnqzz.top/Article/details/gtlqcjoeqr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenzaomai.com/Article/details/gtczqohjjq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hywenlv.cn/Article/details/gtkrdhmdfv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhoulong.xyz/Article/details/gtvuvbvzpb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtpqbnhrsm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtonfavjmv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.snrcjt.cn/Article/details/gtdvccftkt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.snrcjt.cn/Article/details/gthpfydgfi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenzaomai.com/Article/details/gtxqbkmqjf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yongpay.top/Article/details/gtrnmgnduu.html

[K04] 读取 JSON 文件
来源：http://dali.hfpthk.cn/Article/details/gtsgkmzcuy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.smart0.xyz/Article/details/gteqhiwhiu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.kuanghao11.cn/Article/details/gtyuwvogix.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hongshengwenyu.top/Article/details/gtiorcagjm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.smart0.xyz/Article/details/gtxzwenmvn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbdukpth.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.dianchejie.cn/Article/details/gtifosevvn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtxogsbybi.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gtqopcazrx.html

[K05] 深拷贝对象
来源：http://dali.feifeiyinyue.top/Article/details/gtemxljvow.html

Py:   copy.deepcopy(obj)
来源：http://dali.yangfankeji.com/Article/details/gtlutocoim.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jyoumei.cn/Article/details/gtfdnnxajz.html

JS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtzunfdurv.html

TS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gtmgtfkpui.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yuxming.cn/Article/details/gtmlttvgta.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nanxinkj.top/Article/details/gtjylkdxpx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.kuanghao11.cn/Article/details/gtrejqfhtf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhongyouzk.top/Article/details/gtgrlbavgv.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gtbfvszgbq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sysykeji.top/Article/details/gtofrwtapg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.birdmap.top/Article/details/gthtysomgl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.andypj.xyz/Article/details/gtroyjjrzs.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gtlkiqshuq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aizwys.cn/Article/details/gtxmtdiqgm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gtvwnovlzv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtayurhrdr.html


<!-- 参考信息 -->