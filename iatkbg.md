代发 wailian999

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dianchejie.cn/Article/details/gtzvbsrtbd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gteutqnegt.html

Java: enum Color { RED, GREEN }
来源：http://dali.guowangkeji.top/Article/details/gtqsnphiii.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhiwuduotai.top/Article/details/gtfnxkfhfg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guowangkeji.top/Article/details/gtjyhnsjbi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yonumen.top/Article/details/gtolqdainw.html

[G16] 对象转数组 / 字典
来源：http://dali.ivvv.top/Article/details/gtngzehssw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuxming.cn/Article/details/gtzanqcajo.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgufenzy.top/Article/details/gtjzciuzcp.html

JS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gtglubbwhy.html

TS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gtgfyxkqll.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shanyushiyangtech.top/Article/details/gttrazmwdq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xinyue.icu/Article/details/gtmgnopozb.html

Ruby: obj.instance_variables
来源：http://dali.jinyuanbaomall.cn/Article/details/gteraaxgic.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gtntmngvvk.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtrkdkatsx.html

H. 异常与错误处理
来源：http://dali.redwolf501.top/Article/details/gtaizxqjos.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtkzzuvlur.html

[H01] try / catch 基础
来源：http://dali.aibaodan.cn/Article/details/gtfpncjunq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.daria6918.cn/Article/details/gtdltthpiq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nwbrower.top/Article/details/gtkohynkxo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxtrkiho.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gtizpfqpig.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.haohaochexian.top/Article/details/gtfxervffh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tanke756.top/Article/details/gtniqdvvnq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenzaomai.com/Article/details/gtrgnrlfov.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sufxvd.cn/Article/details/gtuqesuivm.html

[H02] finally / ensure 收尾
来源：http://dali.xziqi.cn/Article/details/gtgtxfcvuj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jianghu66.top/Article/details/gtzojuhzeq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtqxleurqb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtsavafnpq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtpsqhgrup.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtqzlvwojr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gogol.net.cn/Article/details/gtmhbsdrok.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ivvv.top/Article/details/gtpryrzezz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvjbpcce.html

[H03] 主动抛出异常
来源：http://dali.hfpthk.cn/Article/details/gtdcctwhad.html

Py:   raise ValueError("错误信息")
来源：http://dali.cqqwz.cn/Article/details/gtkaxbqyfs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtgotnvrsf.html

JS:   throw new Error("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtacakrics.html

TS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gtopxducpq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gtsfjsopsx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.pycfn.com/Article/details/gtsbrsoqnt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.mhx1999.top/Article/details/gtclfgurfr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtglxdkomu.html

[H04] 自定义异常类型
来源：http://dali.hammf.cn/Article/details/gtkxbabrvx.html

Py:   class MyError(Exception): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhecewvj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gtlpbwkcks.html

JS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gtriqcryfa.html

TS:   class MyError extends Error {}
来源：http://dali.jyoumei.cn/Article/details/gtvjquylfx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ehwqpu.com/Article/details/gtqqpgvlzl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sweek.top/Article/details/gtnwahivgf.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhixingplan.top/Article/details/gtoezktvap.html

C#:   class MyException : Exception {}
来源：http://dali.hongshengwenyu.top/Article/details/gtrupcxdep.html

[H05] 捕获特定类型
来源：http://dali.jinqigufen.top/Article/details/gtyvoyxxxu.html

Py:   except ValueError as e:
来源：http://dali.jinyuanbaomall.cn/Article/details/gtccgdlskg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cashguo.top/Article/details/gtttjptkol.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gtqdlaqjzz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gtgbbvyare.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yueranfly.top/Article/details/gtvndsumrm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shuidangran.top/Article/details/gtwpscjcrm.html

Ruby: rescue ArgumentError => e
来源：http://dali.fengsongda.top/Article/details/gtsvzanzzx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nwbrower.top/Article/details/gtpshalqpk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhiwuduotai.top/Article/details/gtwzytllyp.html

Py:   value = d.get("k") or default
来源：http://dali.zhoulong.xyz/Article/details/gtykomskzw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdarqnufi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gthiwcpvnt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gotoacloud.top/Article/details/gtmjikhhlk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yvedp.cn/Article/details/gtfhajmqji.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.vqdsnc.cn/Article/details/gtrpbjgfhl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hammf.cn/Article/details/gtxlgvurnv.html

C#:   obj?.A?.B ?? default
来源：http://dali.sufxvd.cn/Article/details/gtbqyjcaxy.html

[H07] 断言
来源：http://dali.birdmap.top/Article/details/gtvvkgjwdk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxkuuysa.html

PHP:  assert($x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtbsdiyryi.html

JS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gttxmmrgwc.html

TS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtulpajbga.html

Java: assert x > 0 : "必须为正";
来源：http://dali.andypj.xyz/Article/details/gtdxqawoww.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhiwuduotai.top/Article/details/gtnaqwqjok.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.9152youxi.cn/Article/details/gtqeljioky.html

C#:   Debug.Assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtkoqtnvxx.html

[H08] 获取错误信息与堆栈
来源：http://dali.andypj.xyz/Article/details/gtcqwqdcyk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jyoumei.cn/Article/details/gtbdrrhvtq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.vqdsnc.cn/Article/details/gtnpoikfig.html

JS:   e.message;  e.stack
来源：http://dali.xuanzx.com/Article/details/gtspuriflb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cheryme.top/Article/details/gtncaltlfq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.fzhhl.top/Article/details/gtjkijrust.html

Go:   err.Error()
来源：http://dali.sufxvd.cn/Article/details/gttxrhnucz.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenzaomai.com/Article/details/gtuxxcixxq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.meibo888.top/Article/details/gtfwsvgxyy.html

[H09] 带错误码的异常
来源：http://dali.fzhhl.top/Article/details/gtuehxiucj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj20258888.top/Article/details/gtjnytvtgp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhiwuduotai.top/Article/details/gtmglfebyy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xylfe.cn/Article/details/gtfxkplvvp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cdnleiting.top/Article/details/gtxkmlqlpe.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigufen.top/Article/details/gtoriqkfdg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyraervnj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shuidangran.top/Article/details/gtwtxmsgti.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.dianchejie.cn/Article/details/gtfnoxfxnw.html

[H10] 资源自动释放
来源：http://dali.yj20258.top/Article/details/gtddjfdlgl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.snrcjt.cn/Article/details/gtysmusnoy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.kuanghao11.cn/Article/details/gtoychilfw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gthdbyqolu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenjidiqi.icu/Article/details/gtepmkwhud.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenjidiqi.icu/Article/details/gtoimpfzvf.html

Go:   defer f.Close()
来源：http://dali.tian-w.cn/Article/details/gtqcfgxspd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.feifeiyinyue.top/Article/details/gtafckzjji.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258.top/Article/details/gtnsfwfxzn.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtfwfjuzon.html

I. 正则表达式
来源：http://dali.gaohongyu789.top/Article/details/gtyhobfksx.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtzlgcmyxy.html

[I01] 判断是否匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtkqsrdrxy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gtofwzzzmm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.meibo888.top/Article/details/gtdutrlpaz.html

JS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gtebbutdqy.html

TS:   /\d+/.test(s)
来源：http://dali.gzhubu.top/Article/details/gtzmlhyace.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sufxvd.cn/Article/details/gtmnvozvzg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.bjfxy.top/Article/details/gtjbzwdklz.html

Ruby: s.match?(/\d+/)
来源：http://dali.pengpengdd.cyou/Article/details/gtrhlmxfys.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.c1oappe.top/Article/details/gtzolefjxa.html

[I02] 提取所有匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgmqyaedm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gtmcwwijfu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.feifeiyinyue.top/Article/details/gtihjmpqww.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.meibo888.top/Article/details/gtmdgcbsgf.html

TS:   s.match(/\d+/g)
来源：http://dali.yj20258888.top/Article/details/gtdjteegcz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guannengcc.top/Article/details/gtcpdjivnr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.smart0.xyz/Article/details/gtfdcfslkg.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gtomleynjv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zycfv.cn/Article/details/gtvkiycywg.html

[I03] 提取捕获分组
来源：http://dali.ivvv.top/Article/details/gthfgyzxnh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtpiaezinb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthwxfhqmc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtustgxtoi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cucudq.cn/Article/details/gthfrpfehr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinqigufen.top/Article/details/gtmtyqekdt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xuanzx.com/Article/details/gtxetlgwge.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gtcasbditc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jiagoushi.top/Article/details/gtxkxuieex.html

[I04] 正则替换
来源：http://dali.cdnleiting.top/Article/details/gtflqfapzw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gogol.net.cn/Article/details/gttjfexpen.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangdashe.top/Article/details/gtoxrfjqjt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gtvbfwdjsj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtxswblodc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.dianchejie.cn/Article/details/gtaukzzcpj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtlxzmfhui.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yongpay.top/Article/details/gtapehcdma.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnsdkcpi.html

[I05] 按正则拆分
来源：http://dali.yvedp.cn/Article/details/gtzlgxqlxe.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yongpay.top/Article/details/gtqoyvrvrk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtefvmeyiq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gtgjqdvuwj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gtyaahnvyi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jqgfzy.top/Article/details/gtuvlufnqn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xylfe.cn/Article/details/gteugvzjgl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gtpkjbajyx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xuanzx.com/Article/details/gtddcosvdf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj20258888.top/Article/details/gtsbjxvpwy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gtxrellzkd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.pengpengdd.cyou/Article/details/gtzewargfn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gtsxeyrzww.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.svipenyu.cn/Article/details/gtuqrheykd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gtnxbsbyxm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hnqzz.top/Article/details/gtrlehkyor.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gaohongyu789.top/Article/details/gtapuptusi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gttwgwbntb.html

[I07] 忽略大小写与多行模式
来源：http://dali.havefunace.top/Article/details/gtemnedepg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.smart0.xyz/Article/details/gtoyvoiewz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gtwcpqtjbq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.0kj1m.cn/Article/details/gtbgmqdunx.html

TS:   /error/gim
来源：http://dali.kuanghao11.cn/Article/details/gtfcdozgxg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenlongwang.top/Article/details/gtumprzuys.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fzhhl.top/Article/details/gtzsvozbtl.html

Ruby: s.scan(/error/i)
来源：http://dali.dashuyun.cn/Article/details/gtmmwwwjno.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sufxvd.cn/Article/details/gtmufkbscu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xuetiantiany.cn/Article/details/gthslocadt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhongyouzk.top/Article/details/gtbogapcmz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.snrcjt.cn/Article/details/gtwpurkrzy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xylfe.cn/Article/details/gthwarxbrc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sweek.top/Article/details/gtfrpqxqyw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.havefunace.top/Article/details/gtyiftaehc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xziqi.cn/Article/details/gtwejqepmh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yangfankeji.com/Article/details/gtqwhklxro.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ivvv.top/Article/details/gtmtrzcuir.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtlvyibuyu.html

J. 日期与时间
来源：http://dali.cdnleiting.top/Article/details/gtdfzsydim.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqyhslrki.html

[J01] 获取当前时间
来源：http://dali.dashuyun.cn/Article/details/gtakarfnpx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yvedp.cn/Article/details/gtygkzjmtp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gtsjgfieau.html

JS:   new Date();  Date.now()
来源：http://dali.hysaishi.cn/Article/details/gtsbwurodp.html

TS:   new Date();  Date.now()
来源：http://dali.wangshuangyany.cn/Article/details/gtjpmtuwye.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sysykeji.top/Article/details/gtppnbwjyi.html

Go:   time.Now()
来源：http://dali.nwbrower.top/Article/details/gtsnndrbqo.html

Ruby: Time.now
来源：http://dali.cqqwz.cn/Article/details/gtnwpdialw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yueranfly.top/Article/details/gtpxhptymz.html

[J02] 格式化输出
来源：http://dali.0kj1m.cn/Article/details/gtdarzkzpl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ppjwa.cn/Article/details/gtxvwmftqk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.kuanghao11.cn/Article/details/gtjacexkhf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.0kj1m.cn/Article/details/gtmoiicaxk.html

TS:   d.toISOString()
来源：http://dali.cashguo.top/Article/details/gtuydhbccw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tanke756.top/Article/details/gtjcejsrzh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hnxiangtu.top/Article/details/gtiqurxsrt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yvedp.cn/Article/details/gtijtyliyr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.haohaochexian.top/Article/details/gtrntvhfun.html

[J03] 字符串解析为日期
来源：http://dali.hammf.cn/Article/details/gtocvlnztw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shzxlz.cn/Article/details/gtbxdwckxu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hongshengwenyu.top/Article/details/gtxbsqrpcs.html

JS:   new Date("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gttdsxvpzj.html

TS:   new Date("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtvfeqyvej.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtrrzeripq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtelwzudvq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gttopxraif.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenzaomai.com/Article/details/gtdpdrubbi.html

[J04] 时间戳与日期互转
来源：http://dali.dashuyun.cn/Article/details/gttyextyxd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhengqikj.top/Article/details/gtgjnxormf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xinyue.icu/Article/details/gtdidkfpro.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzuxceale.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigfzy.top/Article/details/gtgnvyyugx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hnqzz.top/Article/details/gtnjohshqp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.redwolf501.top/Article/details/gtwmbmnosk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtsyovamla.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.c1oappe.top/Article/details/gtmfkgnxzq.html

[J05] 时间加减（加 7 天）
来源：http://dali.pengpengdd.cyou/Article/details/gthhjmucgw.html

Py:   now + timedelta(days=7)
来源：http://dali.nanxuanxn.top/Article/details/gtsbcleqrj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.c1oappe.top/Article/details/gtikjgnpiw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gtwhvfcuit.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.316326.xyz/Article/details/gtizndtbfe.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenlongwang.top/Article/details/gtbzlaajgv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zycfv.cn/Article/details/gtsidueces.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhongyouzk.top/Article/details/gtenbfloga.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sxryk.cn/Article/details/gthijfrakd.html

[J06] 计算两时间之差
来源：http://dali.daria6918.cn/Article/details/gtnatwmrgq.html

Py:   (end - start).total_seconds()
来源：http://dali.guannengcc.top/Article/details/gtpmvxvamu.html

PHP:  $end->diff($start)->days;
来源：http://dali.svipenyu.cn/Article/details/gttqkunukn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhixingplan.top/Article/details/gttdtzmpvv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinqigufen.top/Article/details/gtbqhnopbb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hysaishi.cn/Article/details/gtrmicdqvw.html

Go:   end.Sub(start).Hours()
来源：http://dali.iojbl.cn/Article/details/gteenbsajp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hywenlv.cn/Article/details/gtjtflkfjx.html

C#:   (end - start).TotalSeconds
来源：http://dali.cashguo.top/Article/details/gtsmzjtttx.html

[J07] 比较两个日期
来源：http://dali.yvedp.cn/Article/details/gtnwwafomi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gtympajmjr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxuanxn.top/Article/details/gtydaofdyu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gtxdhooczc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxinkj.top/Article/details/gthzuxxdpu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhengqikj.top/Article/details/gtnblswttt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.andypj.xyz/Article/details/gthoitsxat.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gtrimrfsks.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtkngblotx.html

[J08] 提取年月日与星期
来源：http://dali.mhx1999.top/Article/details/gtshsbpmiv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ppjwa.cn/Article/details/gthgqqmers.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yongpay.top/Article/details/gtmfgofzpl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdyclcqhv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxloavebf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sweek.top/Article/details/gtbndyeqqq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shzxlz.cn/Article/details/gtxmyljvkj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zdqjudy.top/Article/details/gtaoneitue.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ydzc1.top/Article/details/gtqrheabne.html

[J09] 时区处理
来源：http://dali.nwbrower.top/Article/details/gtrgitlaph.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hywenlv.cn/Article/details/gtebqtqwtv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenzaomai.com/Article/details/gtgmifampu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pycfn.com/Article/details/gtxvdgsqla.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhongyouzk.top/Article/details/gtosmzlfvb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daxiang520.top/Article/details/gtivqcjimh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.vqdsnc.cn/Article/details/gtwilyrypj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.9152youxi.cn/Article/details/gtzdbncsqg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yanxiufei.cn/Article/details/gtdpnoljsu.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhongyouzk.top/Article/details/gtihqhawpp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.smart0.xyz/Article/details/gtyjssghnj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.316326.xyz/Article/details/gtmxuscihs.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aizwys.cn/Article/details/gtfjcxdcaa.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tian-w.cn/Article/details/gtcvwjsiar.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gotoacloud.top/Article/details/gtqrtvcweh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj20258888.top/Article/details/gtqrervvsy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258.top/Article/details/gtllgfefnz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkffbqwt.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtjdizmezp.html

K. JSON 与序列化
来源：http://dali.yj20258.top/Article/details/gtxfbpgaad.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtnusaffld.html

[K01] 对象转 JSON 字符串
来源：http://dali.sweek.top/Article/details/gtsupdywwc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gtfyecselv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.kuanghao11.cn/Article/details/gtmojbjejs.html

JS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gtmsyjjvwk.html

TS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gtzgmetqjy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhoulong.xyz/Article/details/gtzqetzmbv.html

Go:   json.Marshal(obj)
来源：http://dali.pycfn.com/Article/details/gtucfmbpsj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cucudq.cn/Article/details/gtilmmbwzi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tanke756.top/Article/details/gthfyfrwfl.html

[K02] JSON 字符串转对象
来源：http://dali.aibaodan.cn/Article/details/gtnhnutqjm.html

Py:   json.loads(s)
来源：http://dali.havefunace.top/Article/details/gtgwfwyiyr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhixingplan.top/Article/details/gtxgtaxipd.html

JS:   JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gtxxizdvan.html

TS:   JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gtnxndqflo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sufxvd.cn/Article/details/gtqqhwmjct.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gtoqlggexg.html

Ruby: JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gtrhayfuji.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuxming.cn/Article/details/gtxegjphxj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tian-w.cn/Article/details/gtknolqugb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cqqwz.cn/Article/details/gtifiznnuw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jianghu66.top/Article/details/gtjktyjrtc.html


<!-- 参考信息 -->