代发 wailian999

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.quarkkingdee.top/Article/details/gtusbsygue.html

Ruby: obj.instance_variables
来源：http://dali.sxryk.cn/Article/details/gtuaphiqhk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gzhubu.top/Article/details/gtarwimhgy.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtdaobbdtx.html

H. 异常与错误处理
来源：http://dali.snrcjt.cn/Article/details/gtuwwejnpf.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtixcoyoss.html

[H01] try / catch 基础
来源：http://dali.hywenlv.cn/Article/details/gtrsmijrjx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jqgfzy.top/Article/details/gtaxghmhll.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.kuanghao11.cn/Article/details/gtuhexylxc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gtjkvdqqog.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gtbakfgrco.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgfzy.top/Article/details/gtuaywakmt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cucudq.cn/Article/details/gtknigcttu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cdnleiting.top/Article/details/gtlvcueqeq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hysaishi.cn/Article/details/gtozpllcgr.html

[H02] finally / ensure 收尾
来源：http://dali.316326.xyz/Article/details/gtmcfwnuij.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhoulong.xyz/Article/details/gtnunktjnp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtkfxogljs.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtgkabexif.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtgmkhamdp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtfnpsrkvm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.wangdashe.top/Article/details/gtohustiyw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cqqwz.cn/Article/details/gtjpfualkq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtyllfopsj.html

[H03] 主动抛出异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtijtxoway.html

Py:   raise ValueError("错误信息")
来源：http://dali.zycfv.cn/Article/details/gtjmmcwztk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gtvwawlqgt.html

JS:   throw new Error("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtcerwwnge.html

TS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtivjkbedq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gteaadleet.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.vqdsnc.cn/Article/details/gtjstvdsgp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.andypj.xyz/Article/details/gttbgeygwu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtkgdufciy.html

[H04] 自定义异常类型
来源：http://dali.smart0.xyz/Article/details/gtlalhnpln.html

Py:   class MyError(Exception): pass
来源：http://dali.jiagoushi.top/Article/details/gtpdmflgtl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqrpsakb.html

JS:   class MyError extends Error {}
来源：http://dali.hywenlv.cn/Article/details/gtpftbmvwn.html

TS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gtfxcrbrkv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yvedp.cn/Article/details/gtbciwvabj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cqqwz.cn/Article/details/gtkyozgrbg.html

Ruby: class MyError < StandardError; end
来源：http://dali.shuidangran.top/Article/details/gthfbeioek.html

C#:   class MyException : Exception {}
来源：http://dali.tian-w.cn/Article/details/gtibadnjgw.html

[H05] 捕获特定类型
来源：http://dali.birdmap.top/Article/details/gtdjpebkut.html

Py:   except ValueError as e:
来源：http://dali.sufxvd.cn/Article/details/gthltkwpti.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.mhx1999.top/Article/details/gtixckhbyt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gtfwpntpng.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtrapxseqa.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtwwcbypws.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.iojbl.cn/Article/details/gtvqjvgylh.html

Ruby: rescue ArgumentError => e
来源：http://dali.jianghu66.top/Article/details/gtnjdkcwmr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cqqwz.cn/Article/details/gtrudvegbt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sxryk.cn/Article/details/gtdkaffnws.html

Py:   value = d.get("k") or default
来源：http://dali.zhixingplan.top/Article/details/gtkfgxjzpr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gzhubu.top/Article/details/gtmeuvgqth.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuxming.cn/Article/details/gtafbgbbze.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yueranfly.top/Article/details/gtmvpdhoiv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.fengsongda.top/Article/details/gtleurtxxx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenjidiqi.icu/Article/details/gtzzmmujnf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.mhx1999.top/Article/details/gtrietpmds.html

C#:   obj?.A?.B ?? default
来源：http://dali.jlsjyb.cn/Article/details/gtujnoafmd.html

[H07] 断言
来源：http://dali.xinyue.icu/Article/details/gtbljatrwo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqqwrfluc.html

PHP:  assert($x > 0);
来源：http://dali.andypj.xyz/Article/details/gttfkpfhna.html

JS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwtyeafq.html

TS:   console.assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gthqwkrfsi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shangyingyoupin.top/Article/details/gtlxklnipb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sxryk.cn/Article/details/gtqxqiipzu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gaohongyu789.top/Article/details/gttbfapymd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtsdddvvbo.html

[H08] 获取错误信息与堆栈
来源：http://dali.sysykeji.top/Article/details/gtasxweiur.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ivvv.top/Article/details/gtyvoingns.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yuxming.cn/Article/details/gtrbhfvkwg.html

JS:   e.message;  e.stack
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjbkuymc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhongyouzk.top/Article/details/gtolfsvxua.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxwvtyjd.html

Go:   err.Error()
来源：http://dali.xinyue.icu/Article/details/gtjaeravjf.html

Ruby: e.message;  e.backtrace
来源：http://dali.pycfn.com/Article/details/gtbukrdxhf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.guannengcc.top/Article/details/gtvqvrtbyv.html

[H09] 带错误码的异常
来源：http://dali.hammf.cn/Article/details/gtmdayfzry.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gaohongyu789.top/Article/details/gtiryeyxlh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hnqzz.top/Article/details/gthvhuepyx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yvedp.cn/Article/details/gtnsquoqsj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cucudq.cn/Article/details/gtklsgtjux.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenzaomai.com/Article/details/gtqohcnpan.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnqzz.top/Article/details/gtyxlajyho.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.fzhhl.top/Article/details/gtsnigizwt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.daxiang520.top/Article/details/gtjjzwktiq.html

[H10] 资源自动释放
来源：http://dali.shzxlz.cn/Article/details/gtiyhmwuqm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cucudq.cn/Article/details/gtwyoppdgr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ehwqpu.com/Article/details/gtercgkuno.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sxryk.cn/Article/details/gtmzioxnrf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tianlin.xyz/Article/details/gtrjpnnzow.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yongpay.top/Article/details/gtkokuxtiu.html

Go:   defer f.Close()
来源：http://dali.cheryme.top/Article/details/gtwhevcdev.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gaohongyu789.top/Article/details/gtzutxmniw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtmxfopvge.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtddcslljj.html

I. 正则表达式
来源：http://dali.zhongyouzk.top/Article/details/gtxmtsdlwc.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtgkrnruzv.html

[I01] 判断是否匹配
来源：http://dali.pycfn.com/Article/details/gtehvahuyh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.redwolf501.top/Article/details/gthkjeliec.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sweek.top/Article/details/gtqdvavvxh.html

JS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gtmfetbuxh.html

TS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gtrfybordk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hammf.cn/Article/details/gtzzdbcixx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtakhgogjk.html

Ruby: s.match?(/\d+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxmtxqomf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.guowangkeji.top/Article/details/gtirdqdgyd.html

[I02] 提取所有匹配
来源：http://dali.smart0.xyz/Article/details/gtznfwxwas.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtrpnteqon.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.fengsongda.top/Article/details/gtghzfswex.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbwkbedl.html

TS:   s.match(/\d+/g)
来源：http://dali.ivvv.top/Article/details/gtpgosusas.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuhjqlswl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jiagoushi.top/Article/details/gtrzjqnyjl.html

Ruby: s.scan(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gtivawythq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtdfifurup.html

[I03] 提取捕获分组
来源：http://dali.jianghu66.top/Article/details/gtcervelbo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sweek.top/Article/details/gtsssmjmth.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daxiang520.top/Article/details/gtcmcghxfw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gotoacloud.top/Article/details/gtjgdzwjol.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.andypj.xyz/Article/details/gtahbaetbt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaoqdwwdw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenjidiqi.icu/Article/details/gtcnzarkmr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zdqjudy.top/Article/details/gtyokwxgke.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zycfv.cn/Article/details/gtphgmhemr.html

[I04] 正则替换
来源：http://dali.meibo888.top/Article/details/gtmwbkpkqo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.aibaodan.cn/Article/details/gtxqjiescp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtqssqhbuh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtuzfbrwwu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.dianchejie.cn/Article/details/gtvoonnrqj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yueranfly.top/Article/details/gtyxmzijfh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gotoacloud.top/Article/details/gtshknverj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daria6918.cn/Article/details/gtmdfrblmu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nanxinkj.top/Article/details/gtjwpvkfhp.html

[I05] 按正则拆分
来源：http://dali.daria6918.cn/Article/details/gtenvwdjab.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nwbrower.top/Article/details/gtidixlrqa.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.snrcjt.cn/Article/details/gthrzcujri.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gtghumrnhy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtyjhoykeh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.iojbl.cn/Article/details/gtaczrwywd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gtljaawogu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gtoyyfdayb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gtmcwrundq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hnqzz.top/Article/details/gtxliutqpi.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gtysxzkvsf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfeoqdkt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.havefunace.top/Article/details/gtuiyioohw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.c1oappe.top/Article/details/gtvywggicp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gtofewbqpx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cheryme.top/Article/details/gtdbkrkfwb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sysykeji.top/Article/details/gtndvcmwhf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gtyuxhmhyd.html

[I07] 忽略大小写与多行模式
来源：http://dali.ehwqpu.com/Article/details/gtfumzrhro.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.daria6918.cn/Article/details/gtcjebjylg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hysaishi.cn/Article/details/gtlcboaqse.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnxiangtu.top/Article/details/gtpmninirt.html

TS:   /error/gim
来源：http://dali.xuetiantiany.cn/Article/details/gtfsphdill.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zycfv.cn/Article/details/gtcuitnpzd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xuanzx.com/Article/details/gtwhypebeq.html

Ruby: s.scan(/error/i)
来源：http://dali.jlsjyb.cn/Article/details/gtuckjknmo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jyoumei.cn/Article/details/gtfcbxudfh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tanke756.top/Article/details/gtjjgyafkq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nanxuanxn.top/Article/details/gtyuyuxkku.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gtwcnuccns.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xinyue.icu/Article/details/gtrrsikmsa.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gtwhjqjcpv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hongshengwenyu.top/Article/details/gtwtigesty.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkybtofno.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenlongwang.top/Article/details/gtipnsjqqx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zycfv.cn/Article/details/gtbtvgmrfl.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtlgviixnl.html

J. 日期与时间
来源：http://dali.jiagoushi.top/Article/details/gtjcikyqzl.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtplylcemd.html

[J01] 获取当前时间
来源：http://dali.zycfv.cn/Article/details/gtgbwvfutw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yanxiufei.cn/Article/details/gteonufbhx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gtspnpoklr.html

JS:   new Date();  Date.now()
来源：http://dali.wangdashe.top/Article/details/gtdrfbvkvo.html

TS:   new Date();  Date.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtlojjpeqf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinqigfzy.top/Article/details/gtoemghewe.html

Go:   time.Now()
来源：http://dali.cucudq.cn/Article/details/gtqbplgkqj.html

Ruby: Time.now
来源：http://dali.vqdsnc.cn/Article/details/gtgxaubgvk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ivvv.top/Article/details/gtqtrgjgwr.html

[J02] 格式化输出
来源：http://dali.chenzaomai.com/Article/details/gtauyemosr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtolryzbns.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gaohongyu789.top/Article/details/gtjjqmzztu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.andypj.xyz/Article/details/gtnayahocs.html

TS:   d.toISOString()
来源：http://dali.haohaochexian.top/Article/details/gtzhfdjomc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yvedp.cn/Article/details/gtjzbilisi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yongpay.top/Article/details/gtjyiuusbi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gtrarmwjne.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.havefunace.top/Article/details/gtrgpnelrb.html

[J03] 字符串解析为日期
来源：http://dali.yanxiufei.cn/Article/details/gthndgiigx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.iojbl.cn/Article/details/gtxsaxutav.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fengsongda.top/Article/details/gtudqicfkn.html

JS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtlqngltgd.html

TS:   new Date("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtnpvnkedr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtojmztudl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtvgujanjk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtiurqumfe.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cashguo.top/Article/details/gtibkcfxzo.html

[J04] 时间戳与日期互转
来源：http://dali.gotoacloud.top/Article/details/gtpzvwpozv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.c1oappe.top/Article/details/gtzwueubek.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtluvhovyf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj202588.top/Article/details/gtnumodmei.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigfzy.top/Article/details/gtwkovrtbt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenlongwang.top/Article/details/gtuhvdzxdi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.mhx1999.top/Article/details/gtlgwhgbbu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daria6918.cn/Article/details/gtruitwerc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xylfe.cn/Article/details/gtcvvalxkc.html

[J05] 时间加减（加 7 天）
来源：http://dali.xziqi.cn/Article/details/gtwfckioxc.html

Py:   now + timedelta(days=7)
来源：http://dali.gogol.net.cn/Article/details/gtzzuqarlh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.redwolf501.top/Article/details/gtujlcripv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gtprgdjtuz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jianghu66.top/Article/details/gtmfkzbazx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fengsongda.top/Article/details/gtguenzhjl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.quarkkingdee.top/Article/details/gtmvjzypml.html

Ruby: Time.now + 7 * 86400
来源：http://dali.bjfxy.top/Article/details/gtwgwvayun.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ehwqpu.com/Article/details/gtljinwyos.html

[J06] 计算两时间之差
来源：http://dali.gzhubu.top/Article/details/gtbsewncbn.html

Py:   (end - start).total_seconds()
来源：http://dali.shzxlz.cn/Article/details/gtfdhsiwzk.html

PHP:  $end->diff($start)->days;
来源：http://dali.hysaishi.cn/Article/details/gtchafqtgc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shanyushiyangkeji.top/Article/details/gtenofggbw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.redwolf501.top/Article/details/gtzjckuemc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yangfankeji.com/Article/details/gtjhgaodyw.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj20258888.top/Article/details/gtgujndyol.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhongyouzk.top/Article/details/gtutqcwiiy.html

C#:   (end - start).TotalSeconds
来源：http://dali.yuxming.cn/Article/details/gtmnbsukwn.html

[J07] 比较两个日期
来源：http://dali.yueranfly.top/Article/details/gtwjhubpnv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gtsjahrpva.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.c1oappe.top/Article/details/gtrgznzend.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gtzaguzzaj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hnxiangtu.top/Article/details/gtdqgmgbiv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.snrcjt.cn/Article/details/gtgqhfupgp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pycfn.com/Article/details/gtzhhyuznw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gtjjxhgguj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gtvvkjpmhg.html

[J08] 提取年月日与星期
来源：http://dali.yj202588.top/Article/details/gtachltlky.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.smart0.xyz/Article/details/gtzpnjzhxg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yueranfly.top/Article/details/gtahljlljy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jyoumei.cn/Article/details/gtqsxscikb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.havefunace.top/Article/details/gtbjzlklqh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xinyue.icu/Article/details/gtuinlsaxu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shuidangran.top/Article/details/gtyeahtpji.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ppjwa.cn/Article/details/gtfwurwgya.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hnxiangtu.top/Article/details/gtbzevljjw.html

[J09] 时区处理
来源：http://dali.hnxiangtu.top/Article/details/gtkfjftfow.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.mhx1999.top/Article/details/gtyqwbejzi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hnqzz.top/Article/details/gtujmybmxn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gtamxkmymu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gtlnugcvra.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sxryk.cn/Article/details/gtiypmgvgo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shuidangran.top/Article/details/gtrlayxxdo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.kuanghao11.cn/Article/details/gtahbkurww.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.mhx1999.top/Article/details/gtvtxmhufx.html

[J10] 取今天 / 本月第一天
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbomjszhm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tianlin.xyz/Article/details/gtkayzdwai.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.pengpengdd.cyou/Article/details/gtkpstdzyn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.wangdashe.top/Article/details/gtevgbsxfn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gotoacloud.top/Article/details/gtvbthlnag.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ppjwa.cn/Article/details/gtxpubedfc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yangfankeji.com/Article/details/gtjjuubthc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sxryk.cn/Article/details/gtimprcldk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ybcxt.top/Article/details/gtsribymld.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtgmkogbaj.html

K. JSON 与序列化
来源：http://dali.cheryme.top/Article/details/gtzmcolqhc.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtnckbzuog.html

[K01] 对象转 JSON 字符串
来源：http://dali.xinyue.icu/Article/details/gtzfgrpxuf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gtxtgygxrz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gtstinmppp.html

JS:   JSON.stringify(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtmqkoavcb.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gtzhkshwht.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhixingplan.top/Article/details/gtwswausyu.html

Go:   json.Marshal(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxrpnpktv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.dianchejie.cn/Article/details/gtirgygirw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoohmyopm.html

[K02] JSON 字符串转对象
来源：http://dali.yanxiufei.cn/Article/details/gtznmkqvez.html

Py:   json.loads(s)
来源：http://dali.chenlongwang.top/Article/details/gtyzpcptrp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sufxvd.cn/Article/details/gtlbucphlo.html

JS:   JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gtdaencyhg.html

TS:   JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gtznhavwgg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.dashuyun.cn/Article/details/gtgfkuylgm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ppjwa.cn/Article/details/gtyypwgwfc.html

Ruby: JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gtyidirpkt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuxming.cn/Article/details/gtcgsuvpqg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jiagoushi.top/Article/details/gtbjvaljhd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gtpyxnufix.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gtgqxktbgl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tanke756.top/Article/details/gtnxstknjq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbhhfhkzj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtprtklnuu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xziqi.cn/Article/details/gtlftuibkt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinqigufen.top/Article/details/gtymiaymku.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tian-w.cn/Article/details/gtklarfkmh.html

[K04] 读取 JSON 文件
来源：http://dali.meibo888.top/Article/details/gtzoijahnr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.0kj1m.cn/Article/details/gtlwqmcggz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yanxiufei.cn/Article/details/gtepzkcxvz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrokbkmsm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gtxsqytwqw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gttehficzt.html


<!-- 参考信息 -->