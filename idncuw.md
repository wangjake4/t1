代发 wailian999

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenlongwang.top/Article/details/gtomrwhclt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtuoqwetcq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtthumdflo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtviscxamx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtcjxgxchd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shuidangran.top/Article/details/gthfyytwxm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.316326.xyz/Article/details/gtbzqbdyhq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtcvddvpwk.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtddhdmxpz.html

Py:   raise ValueError("错误信息")
来源：http://dali.gotoacloud.top/Article/details/gtvbuyddrr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqrapvswq.html

JS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpnuedkcb.html

TS:   throw new Error("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtmahvempy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtqwlgrjbf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.andypj.xyz/Article/details/gtfpmvvtcx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.kuanghao11.cn/Article/details/gtuacujspt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtdbiqrota.html

[H04] 自定义异常类型
来源：http://dali.guowangkeji.top/Article/details/gtwgubtgyx.html

Py:   class MyError(Exception): pass
来源：http://dali.cheryme.top/Article/details/gtxvfqcbny.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gtoefgtgtb.html

JS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gtoewjsnss.html

TS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gtwlcjfvnd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aizwys.cn/Article/details/gtyxfcbnsm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfxywnjo.html

Ruby: class MyError < StandardError; end
来源：http://dali.xuanzx.com/Article/details/gtqjuiyrfr.html

C#:   class MyException : Exception {}
来源：http://dali.gogol.net.cn/Article/details/gtuumzlbcy.html

[H05] 捕获特定类型
来源：http://dali.yueranfly.top/Article/details/gtzpnhirse.html

Py:   except ValueError as e:
来源：http://dali.hnxiangtu.top/Article/details/gtkcrkithd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.316326.xyz/Article/details/gtwvwesjvm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gtnwuvgcay.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jqgufenzy.top/Article/details/gtehejjsfb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cheryme.top/Article/details/gtyubvnnrz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ybcxt.top/Article/details/gteekyrvzo.html

Ruby: rescue ArgumentError => e
来源：http://dali.aibaodan.cn/Article/details/gthsfkucjb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtmibbaowg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yvedp.cn/Article/details/gtardvkovc.html

Py:   value = d.get("k") or default
来源：http://dali.hongshengwenyu.top/Article/details/gtrmsovyjo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkadpexzr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cashguo.top/Article/details/gtqmvhlgyq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tianlin.xyz/Article/details/gtdkjgdzgl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zycfv.cn/Article/details/gtrysybajf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.snrcjt.cn/Article/details/gtatibbmay.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenzaomai.com/Article/details/gtdtqfidfz.html

C#:   obj?.A?.B ?? default
来源：http://dali.jianghu66.top/Article/details/gtabnwtduv.html

[H07] 断言
来源：http://dali.316326.xyz/Article/details/gtwjmpfejt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuanzx.com/Article/details/gtosxmpzhf.html

PHP:  assert($x > 0);
来源：http://dali.guannengcc.top/Article/details/gtnxzfmxgx.html

JS:   console.assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtwpxavtkf.html

TS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtftlslshh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigfzy.top/Article/details/gtwjchmjcq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yvedp.cn/Article/details/gtamrlxmgm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shuidangran.top/Article/details/gtuaidsrjw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtjnlgbfyu.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangtech.top/Article/details/gthedybhhi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ybcxt.top/Article/details/gthziizvtd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.meibo888.top/Article/details/gtinmwaykr.html

JS:   e.message;  e.stack
来源：http://dali.nanxinkj.top/Article/details/gtvjlvjadn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.9152youxi.cn/Article/details/gtbgymipva.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nanxinkj.top/Article/details/gtberraehy.html

Go:   err.Error()
来源：http://dali.yonumen.top/Article/details/gtbkbxwvsm.html

Ruby: e.message;  e.backtrace
来源：http://dali.ydzc1.top/Article/details/gtjhqodrus.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fzhhl.top/Article/details/gtxlxphynn.html

[H09] 带错误码的异常
来源：http://dali.birdmap.top/Article/details/gtedpxfttx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yvedp.cn/Article/details/gtyojbbwya.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sxryk.cn/Article/details/gtfggroxud.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fengsongda.top/Article/details/gtktcrfnxa.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangshuangyany.cn/Article/details/gtqmcpwwcl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.vqdsnc.cn/Article/details/gtuwytegkf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.dashuyun.cn/Article/details/gtcxwwaceg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hfpthk.cn/Article/details/gtnxdgushg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj20258888.top/Article/details/gtvanuatxf.html

[H10] 资源自动释放
来源：http://dali.fengsongda.top/Article/details/gtedzxvbzn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cdnleiting.top/Article/details/gthxbvpuir.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangtech.top/Article/details/gtkocuacxi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gtgwechmrp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gtsbqfctac.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yueranfly.top/Article/details/gtjnmvemjr.html

Go:   defer f.Close()
来源：http://dali.xuetiantiany.cn/Article/details/gtycmngzbi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.pengpengdd.cyou/Article/details/gtdgywcedt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.pycfn.com/Article/details/gtyjxfrxxh.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtetszmycl.html

I. 正则表达式
来源：http://dali.hongshengwenyu.top/Article/details/gtpvenwdcv.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtetnpdouh.html

[I01] 判断是否匹配
来源：http://dali.cashguo.top/Article/details/gteeaflpoz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.haohaochexian.top/Article/details/gtkkkcgaas.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sxryk.cn/Article/details/gtzgytuluc.html

JS:   /\d+/.test(s)
来源：http://dali.xinyue.icu/Article/details/gtubohocfn.html

TS:   /\d+/.test(s)
来源：http://dali.pycfn.com/Article/details/gtstlkroug.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenzaomai.com/Article/details/gtxohgzcvh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenzaomai.com/Article/details/gtcxgievsf.html

Ruby: s.match?(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gtmdmfpboe.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xinyue.icu/Article/details/gtaiixyunp.html

[I02] 提取所有匹配
来源：http://dali.chenzaomai.com/Article/details/gtcfvmifxq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenlongwang.top/Article/details/gtzlrditkz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgufenzy.top/Article/details/gtgzbgeeur.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sweek.top/Article/details/gtkhivjdmn.html

TS:   s.match(/\d+/g)
来源：http://dali.hywenlv.cn/Article/details/gtdyilbpfw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cqqwz.cn/Article/details/gtfuvpuqkb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nwbrower.top/Article/details/gtkfswgzsd.html

Ruby: s.scan(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gtpyikarlx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtvpbhxjct.html

[I03] 提取捕获分组
来源：http://dali.chenlongwang.top/Article/details/gtyqndnpkj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tianlin.xyz/Article/details/gtgorodliq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfkxrznug.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nanxinkj.top/Article/details/gtpwoiynlz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenlongwang.top/Article/details/gthszcjjgd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.dianchejie.cn/Article/details/gtlfkykxhg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jianghu66.top/Article/details/gtexqaiaew.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj20258888.top/Article/details/gthutgtyhb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.meibo888.top/Article/details/gttaukopxn.html

[I04] 正则替换
来源：http://dali.redwolf501.top/Article/details/gtvyivbjpn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuanzx.com/Article/details/gtgikjwouy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtflhaiwcn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtgkyyuehk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gtpfoawvjd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.smart0.xyz/Article/details/gtuicfhlci.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nanxinkj.top/Article/details/gtmmefjvuv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinqigufen.top/Article/details/gtowbgjphe.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ydzc1.top/Article/details/gtqylqgxtc.html

[I05] 按正则拆分
来源：http://dali.jiagoushi.top/Article/details/gtrjtinvkj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtgavygtiu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtxaaqufxf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gthtlksxdm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gtzeasuweq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cashguo.top/Article/details/gtvpqsvloe.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hammf.cn/Article/details/gtfdifvggd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gttovzihti.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yangfankeji.com/Article/details/gtjrtzmtyj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.aibaodan.cn/Article/details/gtezzpqydc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gtbrscheyj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cqqwz.cn/Article/details/gtgyajpsxm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cqqwz.cn/Article/details/gtbrewoagk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhoulong.xyz/Article/details/gtbjwgdzrv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gtjanhippn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.fzhhl.top/Article/details/gtmremzedu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ydzc1.top/Article/details/gtpjfzrilb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yonumen.top/Article/details/gtqfqkwpnk.html

[I07] 忽略大小写与多行模式
来源：http://dali.daria6918.cn/Article/details/gtllwthqax.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yanxiufei.cn/Article/details/gtpgwuzxvv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gtaccfhkym.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ppjwa.cn/Article/details/gtessgenai.html

TS:   /error/gim
来源：http://dali.hysaishi.cn/Article/details/gtkvbrcdzf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xinyue.icu/Article/details/gtlpdzyjte.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhiwuduotai.top/Article/details/gthjsuzljn.html

Ruby: s.scan(/error/i)
来源：http://dali.andypj.xyz/Article/details/gtjpebkbwk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenlongwang.top/Article/details/gtlwozzdms.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinqigfzy.top/Article/details/gtorwbtzsv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gogol.net.cn/Article/details/gtkiniyyrp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtriluxwsz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gtclwopowb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xinyue.icu/Article/details/gtpoysllyb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.quarkkingdee.top/Article/details/gthzyahjxo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sxryk.cn/Article/details/gtzgtqdpep.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tian-w.cn/Article/details/gtwjuobtdz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ehwqpu.com/Article/details/gtoxccqwpb.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhmmxlpy.html

J. 日期与时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotiijogx.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtpwldpito.html

[J01] 获取当前时间
来源：http://dali.fengsongda.top/Article/details/gtuvioddfk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tianlin.xyz/Article/details/gtikulnydn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuxming.cn/Article/details/gtltarpemx.html

JS:   new Date();  Date.now()
来源：http://dali.jiagoushi.top/Article/details/gtegroynoo.html

TS:   new Date();  Date.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpruflas.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenzaomai.com/Article/details/gtahdjgnsp.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gtxjaknxpc.html

Ruby: Time.now
来源：http://dali.jqgufenzy.top/Article/details/gtmksetnka.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhixingplan.top/Article/details/gtucktwpwv.html

[J02] 格式化输出
来源：http://dali.sxryk.cn/Article/details/gtbclsjbim.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gtkpqtwpnw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gtmbubjxwt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shzxlz.cn/Article/details/gtuiaktanq.html

TS:   d.toISOString()
来源：http://dali.feifeiyinyue.top/Article/details/gtwkwwtoqb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shzxlz.cn/Article/details/gtgefuegnx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nanxuanxn.top/Article/details/gtljgtquzt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gtucftvwhg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenjidiqi.icu/Article/details/gtnccozbyl.html

[J03] 字符串解析为日期
来源：http://dali.yangfankeji.com/Article/details/gtpckxidoy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.kuanghao11.cn/Article/details/gtenhfwwek.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nwbrower.top/Article/details/gtrbzriygu.html

JS:   new Date("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gttzueiwsl.html

TS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsihxpxki.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtphdytdjw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtwnincarn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtjlcpwnmo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.vqdsnc.cn/Article/details/gtbrkcfzer.html

[J04] 时间戳与日期互转
来源：http://dali.c1oappe.top/Article/details/gtugbuvaqm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jianghu66.top/Article/details/gtekporzhu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.svipenyu.cn/Article/details/gttdwcrwha.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jqgufenzy.top/Article/details/gtxkqnlvnw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.bjfxy.top/Article/details/gtqfpgtrwo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.dashuyun.cn/Article/details/gtqipdmppv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hywenlv.cn/Article/details/gtjuzihlhc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.c1oappe.top/Article/details/gtxkatkhxn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hfpthk.cn/Article/details/gtidpnnsbc.html

[J05] 时间加减（加 7 天）
来源：http://dali.yonumen.top/Article/details/gtoovnqmqj.html

Py:   now + timedelta(days=7)
来源：http://dali.iojbl.cn/Article/details/gtvplzjlvd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tanke756.top/Article/details/gtktsfzgxp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jlsjyb.cn/Article/details/gtyfqlbfcl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cheryme.top/Article/details/gtdmodmtbf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj202588.top/Article/details/gtxkycigzy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yongpay.top/Article/details/gtfhdqnezl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhixingplan.top/Article/details/gtqiphqmkz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shangyingyoupin.top/Article/details/gtrxpoyxzk.html

[J06] 计算两时间之差
来源：http://dali.zhixingplan.top/Article/details/gtscwauqdf.html

Py:   (end - start).total_seconds()
来源：http://dali.zhongyouzk.top/Article/details/gtalnpyukx.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigfzy.top/Article/details/gtymmzxvnx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ppjwa.cn/Article/details/gtjcmlpucs.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrpockgct.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.daria6918.cn/Article/details/gttjfxpjzg.html

Go:   end.Sub(start).Hours()
来源：http://dali.pycfn.com/Article/details/gthbdkdfmn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ydzc1.top/Article/details/gtnhkxajvu.html

C#:   (end - start).TotalSeconds
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddfbrgwf.html

[J07] 比较两个日期
来源：http://dali.yanxiufei.cn/Article/details/gttjswiupq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gthsptxtbz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.mhx1999.top/Article/details/gtvdwfxtyn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.316326.xyz/Article/details/gtnihdzhxl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gtrzqmzrdm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tian-w.cn/Article/details/gtgstzrbal.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zdqjudy.top/Article/details/gtmppfxbkg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gtrfhijiis.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gtggoeptwf.html

[J08] 提取年月日与星期
来源：http://dali.aizwys.cn/Article/details/gtpqrnacgc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tian-w.cn/Article/details/gtpfasttqq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqejnfetr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sxryk.cn/Article/details/gtamqkxrdk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhiwuduotai.top/Article/details/gtudqtqvas.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenlongwang.top/Article/details/gtldpdwkdw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yuxming.cn/Article/details/gtjdekpksc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj20258.top/Article/details/gtltmqmpen.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yangfankeji.com/Article/details/gtfisxrhdp.html

[J09] 时区处理
来源：http://dali.cdnleiting.top/Article/details/gtyyvnwxfh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.havefunace.top/Article/details/gtkjuubfkk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sysykeji.top/Article/details/gtilcptdrr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gtwsopgwtw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gtoswjalso.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xylfe.cn/Article/details/gthextrpmb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.daxiang520.top/Article/details/gtwlwkotrg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.bjfxy.top/Article/details/gtdsyhbbwm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.316326.xyz/Article/details/gtauoqhaus.html

[J10] 取今天 / 本月第一天
来源：http://dali.gotoacloud.top/Article/details/gtrxphqxnw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhongyouzk.top/Article/details/gtapqhcqqc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gaohongyu789.top/Article/details/gtnahwtmoj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuxming.cn/Article/details/gtflqgchhw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhixingplan.top/Article/details/gtthgimjvf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.snrcjt.cn/Article/details/gtrnvsrywu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.9152youxi.cn/Article/details/gtxtngzkse.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.0kj1m.cn/Article/details/gtocrvkueq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xylfe.cn/Article/details/gtcsowhwbt.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtslxemmfe.html

K. JSON 与序列化
来源：http://dali.sweek.top/Article/details/gtgkisuklu.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtdwffkxpa.html

[K01] 对象转 JSON 字符串
来源：http://dali.andypj.xyz/Article/details/gtegyfbigy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gthtbfppue.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gtttnrduls.html

JS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gtbqqlxftf.html

TS:   JSON.stringify(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtauafoizj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.iojbl.cn/Article/details/gtbvzfpfwr.html

Go:   json.Marshal(obj)
来源：http://dali.cdnleiting.top/Article/details/gtfleqlnqv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhixingplan.top/Article/details/gtreevjeul.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gttrbbfvfk.html

[K02] JSON 字符串转对象
来源：http://dali.cashguo.top/Article/details/gtddbjghxe.html

Py:   json.loads(s)
来源：http://dali.0kj1m.cn/Article/details/gteaixyrtv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yuanzhike.top/Article/details/gtfyrzmltu.html

JS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gtogmmuftn.html

TS:   JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtjvmwgady.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zdqjudy.top/Article/details/gtnxtgyltd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ivvv.top/Article/details/gtudxajxow.html

Ruby: JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gtesthiwug.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.daxiang520.top/Article/details/gtrlxywlls.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sxryk.cn/Article/details/gtuyichppf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gaohongyu789.top/Article/details/gtxgffvfmt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqammyla.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tanke756.top/Article/details/gteazvpepj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gtdnmkslsm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zdqjudy.top/Article/details/gtqxagfanz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.daxiang520.top/Article/details/gtqkwnhybd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtlnjzcbpy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jqgufenzy.top/Article/details/gtlfpebrpt.html

[K04] 读取 JSON 文件
来源：http://dali.snrcjt.cn/Article/details/gttwomvtge.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuetiantiany.cn/Article/details/gtfddilorc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.kuanghao11.cn/Article/details/gtdujtfpyj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gtilibnglf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.0kj1m.cn/Article/details/gtzvgwykaa.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.birdmap.top/Article/details/gtxudjmynf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gtvseojmmf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gtdjhvoskm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj20258888.top/Article/details/gtcxqjxvvd.html

[K05] 深拷贝对象
来源：http://dali.jlsjyb.cn/Article/details/gtttybskou.html

Py:   copy.deepcopy(obj)
来源：http://dali.0kj1m.cn/Article/details/gtbbttjhnh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenjidiqi.icu/Article/details/gtfaiturdg.html

JS:   structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gtmjzlenzr.html

TS:   structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gthbgslaaq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.aibaodan.cn/Article/details/gtwmhmiyrv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xinyue.icu/Article/details/gtssoyiccn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jqgfzy.top/Article/details/gtkokhmlai.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhiwuduotai.top/Article/details/gtapkbbhth.html

[K06] 解析 URL 查询串
来源：http://dali.hysaishi.cn/Article/details/gtrhvbewpv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hongshengwenyu.top/Article/details/gtgsmiucyx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.pycfn.com/Article/details/gtpjgpgltf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yanxiufei.cn/Article/details/gthpfksdpm.html


<!-- 参考信息 -->