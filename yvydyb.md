代发 wailian999

Go:   func (u User) String() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gtzkwdybha.html

Ruby: def to_s; @name; end
来源：http://dali.fengsongda.top/Article/details/gtwzxymptm.html

C#:   public override string ToString() => Name;
来源：http://dali.ybcxt.top/Article/details/gtjvtpjupm.html

[G13] 判断对象类型
来源：http://dali.hysaishi.cn/Article/details/gttrhrdrxt.html

Py:   isinstance(u, User)
来源：http://dali.ppjwa.cn/Article/details/gtpkcwjcua.html

PHP:  $u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtxkgvfwrr.html

JS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtgerzqjfn.html

TS:   u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtjfcgoyab.html

Java: u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtiyhjxcmn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenzaomai.com/Article/details/gtqcswkcyj.html

Ruby: u.is_a?(User)
来源：http://dali.tian-w.cn/Article/details/gtlarcwzst.html

C#:   u is User
来源：http://dali.meibo888.top/Article/details/gttnvhmyyo.html

[G14] 数据类 / record
来源：http://dali.jinghuilouyu.cn/Article/details/gtgzcfnqty.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258888.top/Article/details/gtccltbnui.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cheryme.top/Article/details/gtcmxezzpr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sufxvd.cn/Article/details/gtxlnguswo.html

TS:   type User = { name: string; age: number };
来源：http://dali.fengsongda.top/Article/details/gtxzhrjbrq.html

Java: record User(String name, int age) {}
来源：http://dali.tian-w.cn/Article/details/gtyyxffdeu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhongyouzk.top/Article/details/gtcrxfhabf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.smart0.xyz/Article/details/gtapqyzspj.html

C#:   record User(string Name, int Age);
来源：http://dali.shzxlz.cn/Article/details/gtonjqckyo.html

[G15] 枚举
来源：http://dali.gaohongyu789.top/Article/details/gtzvxwqfvr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.daria6918.cn/Article/details/gtdouuchcn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.316326.xyz/Article/details/gtptwvyfuf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ivvv.top/Article/details/gtdzishcoa.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gtegoiirbi.html

Java: enum Color { RED, GREEN }
来源：http://dali.iojbl.cn/Article/details/gtvmkgmivh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj202588.top/Article/details/gtnkhujngf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jyoumei.cn/Article/details/gteryqipkl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gterqrqbuh.html

[G16] 对象转数组 / 字典
来源：http://dali.feifeiyinyue.top/Article/details/gtdopzsxqx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.smart0.xyz/Article/details/gtgdstbvwv.html

PHP:  get_object_vars($obj);
来源：http://dali.yuxming.cn/Article/details/gtjaamtitq.html

JS:   Object.entries(obj)
来源：http://dali.jyoumei.cn/Article/details/gtqmofrfsg.html

TS:   Object.entries(obj)
来源：http://dali.aizwys.cn/Article/details/gtzcwhfips.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daria6918.cn/Article/details/gtfdbwtgjv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinqigfzy.top/Article/details/gtztzbzcyt.html

Ruby: obj.instance_variables
来源：http://dali.jqgfzy.top/Article/details/gtcotmbgql.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gtwyiplgau.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkspyvzs.html

H. 异常与错误处理
来源：http://dali.hongshengwenyu.top/Article/details/gtwbjfrtdu.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtnmxspctl.html

[H01] try / catch 基础
来源：http://dali.jyoumei.cn/Article/details/gtxtiqtupi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shangyingyoupin.top/Article/details/gtfqwxqpwe.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shuidangran.top/Article/details/gtcyldkhhd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gteotwkako.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gtjciaeslu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yuanzhike.top/Article/details/gtjwaqontc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yangfankeji.com/Article/details/gtcyainwhc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yangfankeji.com/Article/details/gtfdfrcmgu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.svipenyu.cn/Article/details/gttwjvsets.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigfzy.top/Article/details/gtsprbuuuf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pycfn.com/Article/details/gtalabcmga.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtsatxypfo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtfjsealcp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gthylmdtqn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gterycqbmp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yonumen.top/Article/details/gthpuyfwkf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.pengpengdd.cyou/Article/details/gtbwfjwmsc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gttofitvnf.html

[H03] 主动抛出异常
来源：http://dali.jinqigufen.top/Article/details/gtycbcjquw.html

Py:   raise ValueError("错误信息")
来源：http://dali.shangyingyoupin.top/Article/details/gtebalqwrx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtxvweorlq.html

JS:   throw new Error("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtqncvldsy.html

TS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtdwsrtplb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gtcvbzdjym.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigfzy.top/Article/details/gtlcvpdzzu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuanzhike.top/Article/details/gtmjbpgjot.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gttknhtwxd.html

[H04] 自定义异常类型
来源：http://dali.jinqigfzy.top/Article/details/gtoluzrqbx.html

Py:   class MyError(Exception): pass
来源：http://dali.bjfxy.top/Article/details/gtousqacgj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gtuipkpibu.html

JS:   class MyError extends Error {}
来源：http://dali.sweek.top/Article/details/gtvdlqqwpl.html

TS:   class MyError extends Error {}
来源：http://dali.sweek.top/Article/details/gthtedjehh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gtqsiqwakg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jyoumei.cn/Article/details/gtkvrdplew.html

Ruby: class MyError < StandardError; end
来源：http://dali.gogol.net.cn/Article/details/gturzkuikq.html

C#:   class MyException : Exception {}
来源：http://dali.c1oappe.top/Article/details/gtqrlaqumt.html

[H05] 捕获特定类型
来源：http://dali.zhengqikj.top/Article/details/gttkijhliz.html

Py:   except ValueError as e:
来源：http://dali.sysykeji.top/Article/details/gtcmmayrxk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj20258888.top/Article/details/gtkumzytrl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yueranfly.top/Article/details/gtrkapqwsp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gtcffhgyzh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sufxvd.cn/Article/details/gtumxjvicb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cashguo.top/Article/details/gtabcgedul.html

Ruby: rescue ArgumentError => e
来源：http://dali.ehwqpu.com/Article/details/gtcdgfucvh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.kuanghao11.cn/Article/details/gtyibwjhlo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shuidangran.top/Article/details/gtsoypjeit.html

Py:   value = d.get("k") or default
来源：http://dali.0kj1m.cn/Article/details/gtppwatfwx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gtejstjali.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gotoacloud.top/Article/details/gtzvicsakm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgufenzy.top/Article/details/gtwiqyvjlm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zdqjudy.top/Article/details/gtljtpwgpg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zycfv.cn/Article/details/gthldjqdif.html

Ruby: d&.dig(:a, :b)
来源：http://dali.birdmap.top/Article/details/gtsqjmefjp.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtcbzoneth.html

[H07] 断言
来源：http://dali.zhongyouzk.top/Article/details/gtnmueesqn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.birdmap.top/Article/details/gtkmrifgyl.html

PHP:  assert($x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtasiitjml.html

JS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtbaudrysm.html

TS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtsrzhmtds.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhoulong.xyz/Article/details/gtjfzeevfu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnqzz.top/Article/details/gtvqmmfplv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aibaodan.cn/Article/details/gtcydjmcya.html

C#:   Debug.Assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtxzoylcja.html

[H08] 获取错误信息与堆栈
来源：http://dali.cucudq.cn/Article/details/gtzbdgsxot.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shuidangran.top/Article/details/gtxgzbyumb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenzaomai.com/Article/details/gthourlbld.html

JS:   e.message;  e.stack
来源：http://dali.sysykeji.top/Article/details/gttbobbfsp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258888.top/Article/details/gtnqpgmpkv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cucudq.cn/Article/details/gtpwrlnziq.html

Go:   err.Error()
来源：http://dali.ybcxt.top/Article/details/gtumnfstka.html

Ruby: e.message;  e.backtrace
来源：http://dali.yangfankeji.com/Article/details/gtzytewpfm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shangyingyoupin.top/Article/details/gtdeuzvoch.html

[H09] 带错误码的异常
来源：http://dali.jqgfzy.top/Article/details/gtprbyuvza.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj202588.top/Article/details/gteaxyuonh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.c1oappe.top/Article/details/gtefootwzj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xinyue.icu/Article/details/gtydbghxag.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gogol.net.cn/Article/details/gtiyjxzssr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.quarkkingdee.top/Article/details/gtuopptejn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nanxinkj.top/Article/details/gtkqarddmq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnbdywnex.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hysaishi.cn/Article/details/gtzvtullmv.html

[H10] 资源自动释放
来源：http://dali.ybcxt.top/Article/details/gtbdfbzuca.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.guowangkeji.top/Article/details/gtbzppueoe.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.andypj.xyz/Article/details/gtbdyczwrp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenzaomai.com/Article/details/gtjluypopc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gtoqfnhwtb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cucudq.cn/Article/details/gtqfeipgyy.html

Go:   defer f.Close()
来源：http://dali.pengpengdd.cyou/Article/details/gtdfgrlntv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.guowangkeji.top/Article/details/gtfzujkbvy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj202588.top/Article/details/gtzugppypi.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtmwkwgopx.html

I. 正则表达式
来源：http://dali.gzhubu.top/Article/details/gtwwhuzhtt.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtcuociyod.html

[I01] 判断是否匹配
来源：http://dali.cucudq.cn/Article/details/gtsfqphnwl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gtwjizjcwh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.redwolf501.top/Article/details/gtcennljhf.html

JS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gtrshguiqs.html

TS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gtjqnewfjw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tian-w.cn/Article/details/gtxcqaonne.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nanxinkj.top/Article/details/gtmaegjpib.html

Ruby: s.match?(/\d+/)
来源：http://dali.yongpay.top/Article/details/gtjgaydzpj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jyoumei.cn/Article/details/gtqdnwjabr.html

[I02] 提取所有匹配
来源：http://dali.meibo888.top/Article/details/gtxwacstps.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtffwtcjnq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.pengpengdd.cyou/Article/details/gtergnazgg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmyuvbcdy.html

TS:   s.match(/\d+/g)
来源：http://dali.wangshuangyany.cn/Article/details/gtdeheycni.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258.top/Article/details/gtxzdyqjqw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gtgwjulmnt.html

Ruby: s.scan(/\d+/)
来源：http://dali.andypj.xyz/Article/details/gtwcvfzaid.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.bjfxy.top/Article/details/gtkfessngm.html

[I03] 提取捕获分组
来源：http://dali.9152youxi.cn/Article/details/gtugnaovua.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.9152youxi.cn/Article/details/gtmnumxuug.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sysykeji.top/Article/details/gtsplywobp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cheryme.top/Article/details/gteucmrpfz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.vqdsnc.cn/Article/details/gthwtrjpkm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhiwuduotai.top/Article/details/gtwsypgoiq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cucudq.cn/Article/details/gtvoljwzgv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zycfv.cn/Article/details/gtxxagozul.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.9152youxi.cn/Article/details/gtgkawkqtt.html

[I04] 正则替换
来源：http://dali.daria6918.cn/Article/details/gtjsqdqokg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.snrcjt.cn/Article/details/gtbkyleujz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zycfv.cn/Article/details/gtcrflgbmu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxinkj.top/Article/details/gtuqvitgig.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtqvfbflfe.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zycfv.cn/Article/details/gtsfqifloc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.andypj.xyz/Article/details/gttbzxnwlb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.mhx1999.top/Article/details/gtyhfiywnn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtojbepvtv.html

[I05] 按正则拆分
来源：http://dali.smart0.xyz/Article/details/gtkpnxecbg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.havefunace.top/Article/details/gtiybdpbmk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtptbnzzte.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gtpaiujzga.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gtqddbnalg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.daria6918.cn/Article/details/gtcdfaaxrn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.redwolf501.top/Article/details/gtnjfhpmfw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gtdgocurci.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigufen.top/Article/details/gtfhefrocj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sufxvd.cn/Article/details/gtyxfpdlgf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gtkugtbqwq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aibaodan.cn/Article/details/gtajwptchj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqlcotqo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gogol.net.cn/Article/details/gtiyobnago.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gtjburdpkr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ivvv.top/Article/details/gtuegckuqf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.svipenyu.cn/Article/details/gthmeioryv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gtbiyyhjwi.html

[I07] 忽略大小写与多行模式
来源：http://dali.yonumen.top/Article/details/gtqhumndmq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jlsjyb.cn/Article/details/gtlzoilzut.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gttptbrert.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yuanzhike.top/Article/details/gtcjhurccb.html

TS:   /error/gim
来源：http://dali.shanyushiyangtech.top/Article/details/gthlrehxky.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xuanzx.com/Article/details/gtqteqvqkt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yangfankeji.com/Article/details/gtyubvqyoe.html

Ruby: s.scan(/error/i)
来源：http://dali.birdmap.top/Article/details/gtxajvsnqj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gaohongyu789.top/Article/details/gtwetwjilk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangdashe.top/Article/details/gtkjtywrzp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.iojbl.cn/Article/details/gturzrprfl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xinyue.icu/Article/details/gtczfgetvm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jianghu66.top/Article/details/gthxaeuuog.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhixingplan.top/Article/details/gtarrdaigh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj20258.top/Article/details/gtkhanguky.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.dashuyun.cn/Article/details/gtvnsqbnas.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.vqdsnc.cn/Article/details/gtwghwoocw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gtchltntbn.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtnxipbvbw.html

J. 日期与时间
来源：http://dali.kuanghao11.cn/Article/details/gtpjoaeysh.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrwuufahs.html

[J01] 获取当前时间
来源：http://dali.birdmap.top/Article/details/gtyuabhzji.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtniaarysv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gtaiiuzlnt.html

JS:   new Date();  Date.now()
来源：http://dali.ydzc1.top/Article/details/gtclgizmfv.html

TS:   new Date();  Date.now()
来源：http://dali.cdnleiting.top/Article/details/gtkxyzlvli.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jqgufenzy.top/Article/details/gttjkmcoub.html

Go:   time.Now()
来源：http://dali.jiagoushi.top/Article/details/gttpoiffcg.html

Ruby: Time.now
来源：http://dali.yuanzhike.top/Article/details/gtjkarobbb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shangyingyoupin.top/Article/details/gtlshwunvu.html

[J02] 格式化输出
来源：http://dali.hysaishi.cn/Article/details/gtmbftbsvx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daxiang520.top/Article/details/gtkrzqpspi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinghuilouyu.cn/Article/details/gtliznubdq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xziqi.cn/Article/details/gtlyjosiny.html

TS:   d.toISOString()
来源：http://dali.zhixingplan.top/Article/details/gtmqmfgsiz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.316326.xyz/Article/details/gtgfosjerj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.iojbl.cn/Article/details/gtvxxduxtc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cucudq.cn/Article/details/gtbxyxzekd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.wangdashe.top/Article/details/gtqmnarrzq.html

[J03] 字符串解析为日期
来源：http://dali.haohaochexian.top/Article/details/gtrtmcljfo.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yuxming.cn/Article/details/gtecgwlajd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xinyue.icu/Article/details/gturtsywmh.html

JS:   new Date("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtzjuohaig.html

TS:   new Date("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtnxjusuky.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtevdruimm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtkmidutqn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtnzbwvisi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhixingplan.top/Article/details/gtdruldjlk.html

[J04] 时间戳与日期互转
来源：http://dali.cashguo.top/Article/details/gtqpjvqvzx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gogol.net.cn/Article/details/gtnjuibidc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jianghu66.top/Article/details/gtpreabawz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqhibadp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jyoumei.cn/Article/details/gtmeixjopl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yuxming.cn/Article/details/gtzdvefbrc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sufxvd.cn/Article/details/gtcncjyufa.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtkevbdgqm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gzhubu.top/Article/details/gtrvbnkeqb.html

[J05] 时间加减（加 7 天）
来源：http://dali.iojbl.cn/Article/details/gtjvchuiaa.html

Py:   now + timedelta(days=7)
来源：http://dali.gogol.net.cn/Article/details/gtsbxkvvyq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj20258888.top/Article/details/gtatrvxbyc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zdqjudy.top/Article/details/gtxixcrsia.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.bjfxy.top/Article/details/gtqmddowsa.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nanxuanxn.top/Article/details/gthxhayjvb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xylfe.cn/Article/details/gtfqunaxid.html

Ruby: Time.now + 7 * 86400
来源：http://dali.wangshuangyany.cn/Article/details/gtsgnfjqlj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.redwolf501.top/Article/details/gtohjjiitq.html

[J06] 计算两时间之差
来源：http://dali.yanxiufei.cn/Article/details/gtswnqcool.html

Py:   (end - start).total_seconds()
来源：http://dali.cashguo.top/Article/details/gtvignypex.html

PHP:  $end->diff($start)->days;
来源：http://dali.hywenlv.cn/Article/details/gtddnybamr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.andypj.xyz/Article/details/gtmbykcbyg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.birdmap.top/Article/details/gtbkxrltrg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yuxming.cn/Article/details/gttmfaymkc.html

Go:   end.Sub(start).Hours()
来源：http://dali.jqgfzy.top/Article/details/gtbwukwwwj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hammf.cn/Article/details/gtzvkhtyvl.html

C#:   (end - start).TotalSeconds
来源：http://dali.yvedp.cn/Article/details/gtmqdtanuh.html

[J07] 比较两个日期
来源：http://dali.wangshuangyany.cn/Article/details/gtfnfjhvgd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtorthiwcj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenlongwang.top/Article/details/gtptrihrfq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gtduikseao.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gtrektthcs.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yvedp.cn/Article/details/gtptshfiyw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cashguo.top/Article/details/gtkgswvhrb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gtlilzlolx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gtomjgppnz.html

[J08] 提取年月日与星期
来源：http://dali.yuanzhike.top/Article/details/gtbrhbdnku.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sysykeji.top/Article/details/gthjpfauso.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gotoacloud.top/Article/details/gtjjrjrjrj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aizwys.cn/Article/details/gtnpvrhsny.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ehwqpu.com/Article/details/gtqbdmzsgc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuanzhike.top/Article/details/gtblofuboo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj20258888.top/Article/details/gtnpksgigu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gaohongyu789.top/Article/details/gtbkadoicg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yanxiufei.cn/Article/details/gtyvnlrllc.html

[J09] 时区处理
来源：http://dali.kuanghao11.cn/Article/details/gtvpkxdjaz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.0kj1m.cn/Article/details/gtdwbantei.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovriidbs.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gtsuasegni.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.feifeiyinyue.top/Article/details/gtjqbpjkop.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gzhubu.top/Article/details/gtnngtfeqt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nwbrower.top/Article/details/gtonkcfkzs.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.bjfxy.top/Article/details/gtecgchewr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gtgatqnnli.html

[J10] 取今天 / 本月第一天
来源：http://dali.cashguo.top/Article/details/gtsnwjajvv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xylfe.cn/Article/details/gtnwrgiifz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.bjfxy.top/Article/details/gtmrvannqi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hammf.cn/Article/details/gtoilhjqmn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xziqi.cn/Article/details/gtlckwdrnc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jiagoushi.top/Article/details/gthewsttwp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.kuanghao11.cn/Article/details/gtvjcpchnx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cheryme.top/Article/details/gtqixeuiry.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gogol.net.cn/Article/details/gtrotwnkkx.html


<!-- 参考信息 -->