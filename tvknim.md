代发 wailian999

Ruby: Color = %i[red green].freeze
来源：http://dali.feifeiyinyue.top/Article/details/gtjmosxmxe.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258888.top/Article/details/gtgkegdqeq.html

[G16] 对象转数组 / 字典
来源：http://dali.aizwys.cn/Article/details/gtfleciouh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pycfn.com/Article/details/gtgfqkjowh.html

PHP:  get_object_vars($obj);
来源：http://dali.cdnleiting.top/Article/details/gtlatkrmdp.html

JS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gtvnkfebpe.html

TS:   Object.entries(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtqxutgynf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yueranfly.top/Article/details/gtshngrmgm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daria6918.cn/Article/details/gtispiinwd.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjdlthbcz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gtqpzdfjle.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtxivhxyvt.html

H. 异常与错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjpjrtuzv.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtsuvhihbi.html

[H01] try / catch 基础
来源：http://dali.cdnleiting.top/Article/details/gtcnngdevq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjzxziaf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtwbkdanmy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gtvcgpucit.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiiideqgj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.0kj1m.cn/Article/details/gthbrbnvqt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.fengsongda.top/Article/details/gtgdgwalwk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aizwys.cn/Article/details/gthaxujoyg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xziqi.cn/Article/details/gtafmgpayv.html

[H02] finally / ensure 收尾
来源：http://dali.bjfxy.top/Article/details/gttdzgqxgf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuetiantiany.cn/Article/details/gtrnmwmrxi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtuqlickby.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtcdnejjhu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtbqhiqslg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtwqjefrhh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guannengcc.top/Article/details/gtobbrucrt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhongyouzk.top/Article/details/gtqcrwstrq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gthgtckdcv.html

[H03] 主动抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gttlrlmlpy.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhixingplan.top/Article/details/gtqxtzpsxu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtnttelyyd.html

JS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtjigrdply.html

TS:   throw new Error("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtrmtdhgtn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gtgmvipsww.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.fengsongda.top/Article/details/gtoaanlgfe.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.kuanghao11.cn/Article/details/gtoulxoksu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtiwjymjts.html

[H04] 自定义异常类型
来源：http://dali.sweek.top/Article/details/gteerwbnzr.html

Py:   class MyError(Exception): pass
来源：http://dali.kuanghao11.cn/Article/details/gtmqalqvxs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gtbjpdfnwp.html

JS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gtbjoyojls.html

TS:   class MyError extends Error {}
来源：http://dali.daria6918.cn/Article/details/gthzvrotnm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gtihhvfgnh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhixingplan.top/Article/details/gttnztsonw.html

Ruby: class MyError < StandardError; end
来源：http://dali.sweek.top/Article/details/gtrpkqffew.html

C#:   class MyException : Exception {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxeguhxw.html

[H05] 捕获特定类型
来源：http://dali.ppjwa.cn/Article/details/gttrgdmjjt.html

Py:   except ValueError as e:
来源：http://dali.9152youxi.cn/Article/details/gtfixmsymw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.9152youxi.cn/Article/details/gthvduarja.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhongyouzk.top/Article/details/gtynzreqiy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hnxiangtu.top/Article/details/gtwwqxqorw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtjscnxdoy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ybcxt.top/Article/details/gtxkxmkous.html

Ruby: rescue ArgumentError => e
来源：http://dali.mhx1999.top/Article/details/gtnffbjakb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.9152youxi.cn/Article/details/gtgxkuwrpt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.kuanghao11.cn/Article/details/gtqzhbipao.html

Py:   value = d.get("k") or default
来源：http://dali.zhengqikj.top/Article/details/gtioryjcgl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.dashuyun.cn/Article/details/gtornvcayf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sysykeji.top/Article/details/gtfsuknvzz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuanzx.com/Article/details/gtthurjumh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ehwqpu.com/Article/details/gtrmbtqbgh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhixingplan.top/Article/details/gtnjdbyvxu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.kuanghao11.cn/Article/details/gtszecahte.html

C#:   obj?.A?.B ?? default
来源：http://dali.vqdsnc.cn/Article/details/gtlnajpqcl.html

[H07] 断言
来源：http://dali.feifeiyinyue.top/Article/details/gtdpomtozj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cashguo.top/Article/details/gtseuwpvbr.html

PHP:  assert($x > 0);
来源：http://dali.ehwqpu.com/Article/details/gtmfdtslqv.html

JS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtnkrdnpss.html

TS:   console.assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gtssongkdv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.meibo888.top/Article/details/gtuvvawgyb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqviwpmkz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pengpengdd.cyou/Article/details/gtzhdxsrfs.html

C#:   Debug.Assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gtoxkloswf.html

[H08] 获取错误信息与堆栈
来源：http://dali.gzhubu.top/Article/details/gthnfgwvpw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shanyushiyangtech.top/Article/details/gthutfrfmc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.birdmap.top/Article/details/gtuwhkskyq.html

JS:   e.message;  e.stack
来源：http://dali.tanke756.top/Article/details/gtvdyyawbb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgqdfbcb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqfzqcmmg.html

Go:   err.Error()
来源：http://dali.ydzc1.top/Article/details/gtafdchvad.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgufenzy.top/Article/details/gtbsmswnwq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sweek.top/Article/details/gtzlcmedjx.html

[H09] 带错误码的异常
来源：http://dali.chenzaomai.com/Article/details/gtrianfsxm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhoulong.xyz/Article/details/gtrbtolill.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.0kj1m.cn/Article/details/gtozegdhpd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fzhhl.top/Article/details/gtnbtpbmcc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gzhubu.top/Article/details/gtdqqunbib.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shangyingyoupin.top/Article/details/gtlbjozzzl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nanxuanxn.top/Article/details/gtlxagyzoq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigufen.top/Article/details/gtyqaidmrx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xuetiantiany.cn/Article/details/gtqoobdfgr.html

[H10] 资源自动释放
来源：http://dali.chenlongwang.top/Article/details/gthtrekfjo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgufenzy.top/Article/details/gtqnqufjrq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgfzy.top/Article/details/gtqfxpuzxp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gtjymfkdrd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258.top/Article/details/gtgocaulue.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgufenzy.top/Article/details/gtjbvbebzt.html

Go:   defer f.Close()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrkghhybn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hongshengwenyu.top/Article/details/gtijfsrbux.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yuxming.cn/Article/details/gthjruvdzx.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtxsiealvj.html

I. 正则表达式
来源：http://dali.bjfxy.top/Article/details/gtjafrytzr.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtvwpukdkf.html

[I01] 判断是否匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtwasxfeue.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj202588.top/Article/details/gthbiogpeq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtpbheusdv.html

JS:   /\d+/.test(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtkbgleotq.html

TS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gtaqbzekim.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sufxvd.cn/Article/details/gtstpmxbir.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gotoacloud.top/Article/details/gtpbvultrp.html

Ruby: s.match?(/\d+/)
来源：http://dali.316326.xyz/Article/details/gtynmxtikl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jyoumei.cn/Article/details/gtmapwiydd.html

[I02] 提取所有匹配
来源：http://dali.sxryk.cn/Article/details/gtovrjrnak.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gtjtdocpqx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.c1oappe.top/Article/details/gtatqwgqca.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenjidiqi.icu/Article/details/gtbofxqchr.html

TS:   s.match(/\d+/g)
来源：http://dali.chenzaomai.com/Article/details/gtfgsygujf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yanxiufei.cn/Article/details/gtjeajmsou.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tian-w.cn/Article/details/gtfvdimqkr.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gtohvklpjd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cashguo.top/Article/details/gtrqqdmmlk.html

[I03] 提取捕获分组
来源：http://dali.gotoacloud.top/Article/details/gtgsobyydp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xinyue.icu/Article/details/gtmdvbjcfp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj20258.top/Article/details/gtwmxoqhju.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sufxvd.cn/Article/details/gtvdohbard.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.dianchejie.cn/Article/details/gtygfdxaon.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yanxiufei.cn/Article/details/gtkejxzium.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zdqjudy.top/Article/details/gtzebjxbzb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zdqjudy.top/Article/details/gtiwvathkk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.dianchejie.cn/Article/details/gtchbmbhfi.html

[I04] 正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gtqasiaftw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.havefunace.top/Article/details/gtlzsuokxm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtfyvfoisc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yongpay.top/Article/details/gtrhzapugn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.dianchejie.cn/Article/details/gtdfbeljgg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.redwolf501.top/Article/details/gtdjhtpggz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.dianchejie.cn/Article/details/gtqodajypb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.meibo888.top/Article/details/gtrjlmzxay.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.c1oappe.top/Article/details/gtnsihvkjg.html

[I05] 按正则拆分
来源：http://dali.nanxinkj.top/Article/details/gtleqjwiue.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cucudq.cn/Article/details/gtgcrbjhxk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.smart0.xyz/Article/details/gtryqlgoyo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddipsmvd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gtjdaemiab.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cashguo.top/Article/details/gtuwfbwxam.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.wangdashe.top/Article/details/gtvgffpooz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gtlytdajpy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpwrvssmz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shuidangran.top/Article/details/gttbwrdlzq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gtuamfidtf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnztnbcyw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guannengcc.top/Article/details/gtehbdkkkk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhixingplan.top/Article/details/gtshsvkaqp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258.top/Article/details/gtonuqibhh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aizwys.cn/Article/details/gtivbmapai.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hysaishi.cn/Article/details/gtksixzqsm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gtqcuhahhc.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhoulong.xyz/Article/details/gtmukelluk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sysykeji.top/Article/details/gtdcjvstmc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ydzc1.top/Article/details/gtyogbvsta.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigufen.top/Article/details/gtulzigmfm.html

TS:   /error/gim
来源：http://dali.hammf.cn/Article/details/gtjflktbrb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.havefunace.top/Article/details/gtekzeqeux.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.redwolf501.top/Article/details/gtirqhxcfd.html

Ruby: s.scan(/error/i)
来源：http://dali.shzxlz.cn/Article/details/gtrxwjshpq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aibaodan.cn/Article/details/gtgkcatsfn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.guowangkeji.top/Article/details/gtdsmafxdd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jqgfzy.top/Article/details/gtoitqlajc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xinyue.icu/Article/details/gtjnilihbq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.iojbl.cn/Article/details/gtwxndjhnr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aizwys.cn/Article/details/gtagbfzmyw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yonumen.top/Article/details/gtyaydhwfb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daria6918.cn/Article/details/gtawcjzxsg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gaohongyu789.top/Article/details/gtioizsgpr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.wangshuangyany.cn/Article/details/gteyubhnnj.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtxvbisnxj.html

J. 日期与时间
来源：http://dali.jianghu66.top/Article/details/gtpuipzudw.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtufmbqazs.html

[J01] 获取当前时间
来源：http://dali.zhongyouzk.top/Article/details/gtmnjxhyjg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xinyue.icu/Article/details/gttkjmuepg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hnqzz.top/Article/details/gtwtqjbmib.html

JS:   new Date();  Date.now()
来源：http://dali.xuetiantiany.cn/Article/details/gtggdpjtba.html

TS:   new Date();  Date.now()
来源：http://dali.yueranfly.top/Article/details/gtvdaljlbi.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinqigfzy.top/Article/details/gtcwmakwbj.html

Go:   time.Now()
来源：http://dali.xinyue.icu/Article/details/gttjsarhfm.html

Ruby: Time.now
来源：http://dali.pengpengdd.cyou/Article/details/gtswvyucdz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangdashe.top/Article/details/gtsauyioyb.html

[J02] 格式化输出
来源：http://dali.guannengcc.top/Article/details/gtbntlgerz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gaohongyu789.top/Article/details/gttdzpjqct.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nanxinkj.top/Article/details/gtudndapex.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jqgfzy.top/Article/details/gtiaculgcf.html

TS:   d.toISOString()
来源：http://dali.yangfankeji.com/Article/details/gtebaczcoq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jiagoushi.top/Article/details/gtqqdsptlz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinqigufen.top/Article/details/gtihkxehfg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenlongwang.top/Article/details/gtehmjqoou.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.iojbl.cn/Article/details/gtebqucoeg.html

[J03] 字符串解析为日期
来源：http://dali.fengsongda.top/Article/details/gtfllvsxjz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigufen.top/Article/details/gtbtjbhhet.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.mhx1999.top/Article/details/gtmrkkjapz.html

JS:   new Date("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtwhsuujrn.html

TS:   new Date("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtrviskwll.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtomwwqknq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtumgdjnwx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtdvcuuppc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkvulhtp.html

[J04] 时间戳与日期互转
来源：http://dali.gogol.net.cn/Article/details/gtbdnsxbjo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shuidangran.top/Article/details/gtiqvjtfyu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.bjfxy.top/Article/details/gthewkzvxw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sysykeji.top/Article/details/gtbkwlzpyq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.wangdashe.top/Article/details/gtwnbavbdt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.daxiang520.top/Article/details/gtkgzinjlb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xinyue.icu/Article/details/gtufunpgfh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jianghu66.top/Article/details/gtavarvuan.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuxming.cn/Article/details/gtbkklbamj.html

[J05] 时间加减（加 7 天）
来源：http://dali.daxiang520.top/Article/details/gtuosmyduw.html

Py:   now + timedelta(days=7)
来源：http://dali.sufxvd.cn/Article/details/gthovhikwg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ppjwa.cn/Article/details/gtzqwlijvd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gtkcwvjhqq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuxming.cn/Article/details/gtgwdkywiw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nanxinkj.top/Article/details/gtqbbhjxhp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigufen.top/Article/details/gtqvbiaaep.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj20258.top/Article/details/gtlcktbbhb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuanzhike.top/Article/details/gtgqicaqrd.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangtech.top/Article/details/gtthuzlvuu.html

Py:   (end - start).total_seconds()
来源：http://dali.sysykeji.top/Article/details/gtchrkrxgk.html

PHP:  $end->diff($start)->days;
来源：http://dali.nanxinkj.top/Article/details/gtnbawukva.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.mhx1999.top/Article/details/gtyobrmbzr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nwbrower.top/Article/details/gtpcmdbpdt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhijiandao.cn/Article/details/gtkaoeonao.html

Go:   end.Sub(start).Hours()
来源：http://dali.sxryk.cn/Article/details/gttjcxlhbu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.guowangkeji.top/Article/details/gtchvhlhhm.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhoulong.xyz/Article/details/gtawolkoix.html

[J07] 比较两个日期
来源：http://dali.dianchejie.cn/Article/details/gtsypfxqvy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gtsqtjprjr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenjidiqi.icu/Article/details/gtnfndfoik.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gtirvllvod.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gtzjfatbwl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhijiandao.cn/Article/details/gtluiuheae.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbwlrajmn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gtxnzmieuf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gttjnghhob.html

[J08] 提取年月日与星期
来源：http://dali.hongshengwenyu.top/Article/details/gtmjrziheg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.kuanghao11.cn/Article/details/gtkkkwnbwh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnqzz.top/Article/details/gtcshscyvs.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj202588.top/Article/details/gtmynzaobn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shuidangran.top/Article/details/gtjyqholdd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.birdmap.top/Article/details/gtawdeutbb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jyoumei.cn/Article/details/gtngdfockb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cheryme.top/Article/details/gtiwzjqyrb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fzhhl.top/Article/details/gtvisuksgt.html

[J09] 时区处理
来源：http://dali.yuanzhike.top/Article/details/gtjfskrtxq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxinkj.top/Article/details/gtcpfvdowv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangtech.top/Article/details/gtplyzwzar.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cdnleiting.top/Article/details/gtcrqmwipy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangdashe.top/Article/details/gteyquehzc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.9152youxi.cn/Article/details/gtgfltlbrx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shzxlz.cn/Article/details/gtujvivyim.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cdnleiting.top/Article/details/gtvzrquvcy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.bjfxy.top/Article/details/gtxprufouh.html

[J10] 取今天 / 本月第一天
来源：http://dali.svipenyu.cn/Article/details/gtpsfoixuc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.9152youxi.cn/Article/details/gtxjiaxcbe.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xuetiantiany.cn/Article/details/gtiharhfuu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgfzy.top/Article/details/gtpsgxnnin.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.meibo888.top/Article/details/gtlqmrhlej.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.kuanghao11.cn/Article/details/gtwdkwyixb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shanyushiyangtech.top/Article/details/gtnsrktbkj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sweek.top/Article/details/gtifzfuepc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtixnlngsv.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtsowkiskn.html

K. JSON 与序列化
来源：http://dali.tian-w.cn/Article/details/gtgszoutcr.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtxzxkijzx.html

[K01] 对象转 JSON 字符串
来源：http://dali.jlsjyb.cn/Article/details/gtoexlwehk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gtwzhkqylu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gtefyeluqk.html

JS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gtuzltrpxz.html

TS:   JSON.stringify(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtnoisxvff.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.quarkkingdee.top/Article/details/gtfgzwufix.html

Go:   json.Marshal(obj)
来源：http://dali.nanxuanxn.top/Article/details/gttdfiuqzm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nanxuanxn.top/Article/details/gtyahxieso.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhoulong.xyz/Article/details/gthxrmweih.html

[K02] JSON 字符串转对象
来源：http://dali.fzhhl.top/Article/details/gtjxgipxmj.html

Py:   json.loads(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhtxhgjd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cqqwz.cn/Article/details/gtwtfzsqed.html

JS:   JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gtnwtiaqlr.html

TS:   JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyvholnsa.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xinyue.icu/Article/details/gtpxdinlnt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfulfallv.html

Ruby: JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtahjvukgl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqyomlzt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ehwqpu.com/Article/details/gtseajklss.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gtfvnpkydp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xuetiantiany.cn/Article/details/gtdjgzttzj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuanzhike.top/Article/details/gtthyqlmqc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gthqclpltp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hysaishi.cn/Article/details/gtcpljpkxu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtplkmzubc.html


<!-- 参考信息 -->