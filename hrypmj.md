代发 wailian999

TS:   type User = { name: string; age: number };
来源：http://dali.gaohongyu789.top/Article/details/gtnjvkdfxw.html

Java: record User(String name, int age) {}
来源：http://dali.daria6918.cn/Article/details/gtymoqjgyb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xylfe.cn/Article/details/gtqijhgbzv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnqzz.top/Article/details/gtktmuevuu.html

C#:   record User(string Name, int Age);
来源：http://dali.yanxiufei.cn/Article/details/gtfurgyzib.html

[G15] 枚举
来源：http://dali.gogol.net.cn/Article/details/gtehiedrtv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zycfv.cn/Article/details/gtuecnqngf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkbkbdymp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvltotaut.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gtrkbfsrbe.html

Java: enum Color { RED, GREEN }
来源：http://dali.svipenyu.cn/Article/details/gtadmyittk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.316326.xyz/Article/details/gtmsvycwdj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gttzqnihet.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gtymrizklo.html

[G16] 对象转数组 / 字典
来源：http://dali.redwolf501.top/Article/details/gtjwpjgshf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.dianchejie.cn/Article/details/gtzpudusqy.html

PHP:  get_object_vars($obj);
来源：http://dali.zycfv.cn/Article/details/gtsdtdnmic.html

JS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtdqloiaqs.html

TS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gtpwlobuom.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sxryk.cn/Article/details/gtmvrxskzv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgufenzy.top/Article/details/gtgcfmkjdq.html

Ruby: obj.instance_variables
来源：http://dali.havefunace.top/Article/details/gtmveohhur.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sysykeji.top/Article/details/gttcpnkskw.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtulphytuf.html

H. 异常与错误处理
来源：http://dali.guowangkeji.top/Article/details/gtxdgnnrzh.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtonobgqyz.html

[H01] try / catch 基础
来源：http://dali.xuetiantiany.cn/Article/details/gtadabxoca.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenjidiqi.icu/Article/details/gthpzmdoyb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.svipenyu.cn/Article/details/gtvedtapit.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gthehdrnkh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gtkjtffkgt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.dashuyun.cn/Article/details/gtbfueepqy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.daria6918.cn/Article/details/gtnrtuadsb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgufenzy.top/Article/details/gtsswbkwhk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj202588.top/Article/details/gtsnneokns.html

[H02] finally / ensure 收尾
来源：http://dali.zycfv.cn/Article/details/gtatnekmwa.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ydzc1.top/Article/details/gtzuvlohdw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtuewlafgm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtkxcftnqc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpezgnasi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtbakwwgxo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cashguo.top/Article/details/gtntbzqyzl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmzeeqeix.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtephqrgfo.html

[H03] 主动抛出异常
来源：http://dali.tianlin.xyz/Article/details/gtcdnfqibt.html

Py:   raise ValueError("错误信息")
来源：http://dali.hongshengwenyu.top/Article/details/gtunqrpvcx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtjwmihwnj.html

JS:   throw new Error("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtcpwftgvy.html

TS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtcfleklmm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtezbfzvpe.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.svipenyu.cn/Article/details/gttiuikwbu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.wangshuangyany.cn/Article/details/gtkgxjezxd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtllmqqxhx.html

[H04] 自定义异常类型
来源：http://dali.ehwqpu.com/Article/details/gtpksjebsa.html

Py:   class MyError(Exception): pass
来源：http://dali.fengsongda.top/Article/details/gtjnzklglr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gtcusgrmkf.html

JS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gtjdsqexyp.html

TS:   class MyError extends Error {}
来源：http://dali.haohaochexian.top/Article/details/gtxidhnpgg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gtsuqlpdad.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tian-w.cn/Article/details/gtnpgtxetj.html

Ruby: class MyError < StandardError; end
来源：http://dali.yonumen.top/Article/details/gtvkphgnlh.html

C#:   class MyException : Exception {}
来源：http://dali.havefunace.top/Article/details/gtjhsbapay.html

[H05] 捕获特定类型
来源：http://dali.hysaishi.cn/Article/details/gthrrxifys.html

Py:   except ValueError as e:
来源：http://dali.dianchejie.cn/Article/details/gtsealwcxp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhoulong.xyz/Article/details/gtutcjtlpr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gtiakwkfev.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hfpthk.cn/Article/details/gtduclifft.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cashguo.top/Article/details/gtqqntqfpk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xylfe.cn/Article/details/gtripafcls.html

Ruby: rescue ArgumentError => e
来源：http://dali.fzhhl.top/Article/details/gtughuhktp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.daxiang520.top/Article/details/gtazobkdfb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangdashe.top/Article/details/gtiztitzgf.html

Py:   value = d.get("k") or default
来源：http://dali.feifeiyinyue.top/Article/details/gthialhhyz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.316326.xyz/Article/details/gtvmiaiknx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jyoumei.cn/Article/details/gtmwfzixbe.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtkkpofbvq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jyoumei.cn/Article/details/gthxmnwcbx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.bjfxy.top/Article/details/gtfhcduavk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.316326.xyz/Article/details/gtyhgnwwqe.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxuanxn.top/Article/details/gtkjwmdluv.html

[H07] 断言
来源：http://dali.birdmap.top/Article/details/gtbtlfxeim.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hnxiangtu.top/Article/details/gteiqcztgx.html

PHP:  assert($x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtljmtskkq.html

JS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtomfpuvvu.html

TS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gtrijtiwry.html

Java: assert x > 0 : "必须为正";
来源：http://dali.mhx1999.top/Article/details/gtxfghucuu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzdoleojj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sysykeji.top/Article/details/gtzpadncnp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gthrzztlpd.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnxiangtu.top/Article/details/gtlqrkazwe.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhiwuduotai.top/Article/details/gtsihtgcpt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.fengsongda.top/Article/details/gtlzoggwfv.html

JS:   e.message;  e.stack
来源：http://dali.xinyue.icu/Article/details/gtqyjnxdft.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenjidiqi.icu/Article/details/gtvkhoaprn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sufxvd.cn/Article/details/gttmbjzllt.html

Go:   err.Error()
来源：http://dali.sxryk.cn/Article/details/gtjsqjkfuu.html

Ruby: e.message;  e.backtrace
来源：http://dali.xziqi.cn/Article/details/gtpeixhlsy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nwbrower.top/Article/details/gtgupecqip.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbnivyumn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cdnleiting.top/Article/details/gtasarkujl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.bjfxy.top/Article/details/gtadwjpbpg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gotoacloud.top/Article/details/gtuatonmjh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.smart0.xyz/Article/details/gthtfnzugz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaonwotjz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gogol.net.cn/Article/details/gtiydhpyne.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sweek.top/Article/details/gtfedrvuia.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.quarkkingdee.top/Article/details/gtrdxmjcwf.html

[H10] 资源自动释放
来源：http://dali.svipenyu.cn/Article/details/gtmzrpzkwq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hnqzz.top/Article/details/gtghqqokst.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuanzx.com/Article/details/gtpzwnqlwi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gtmcgiwzpk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.svipenyu.cn/Article/details/gtvrlorllk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sufxvd.cn/Article/details/gtndbnvidk.html

Go:   defer f.Close()
来源：http://dali.shanyushiyangtech.top/Article/details/gtluqacfhw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hongshengwenyu.top/Article/details/gtzsgqdhiy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtmmrdxldc.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtceuiztty.html

I. 正则表达式
来源：http://dali.hysaishi.cn/Article/details/gtfluqxxhh.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtzxqamsic.html

[I01] 判断是否匹配
来源：http://dali.gaohongyu789.top/Article/details/gtqysgxeix.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shzxlz.cn/Article/details/gtjjtjlbmd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xinyue.icu/Article/details/gtupbiahvk.html

JS:   /\d+/.test(s)
来源：http://dali.yuanzhike.top/Article/details/gtclqrmwxp.html

TS:   /\d+/.test(s)
来源：http://dali.xylfe.cn/Article/details/gtwkcjvssy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhoulong.xyz/Article/details/gtzhqdahru.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yueranfly.top/Article/details/gtfzxlvkvm.html

Ruby: s.match?(/\d+/)
来源：http://dali.yueranfly.top/Article/details/gtvipsqqwy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.andypj.xyz/Article/details/gttbvcgihx.html

[I02] 提取所有匹配
来源：http://dali.zhixingplan.top/Article/details/gtletufbnz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gtyniwtslh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shuidangran.top/Article/details/gtzljglcjh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhoulong.xyz/Article/details/gtzuuftesj.html

TS:   s.match(/\d+/g)
来源：http://dali.yj202588.top/Article/details/gtcwbrsiwp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yonumen.top/Article/details/gtoohfrvyd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gtguvnzuku.html

Ruby: s.scan(/\d+/)
来源：http://dali.yongpay.top/Article/details/gtvfzwphif.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.redwolf501.top/Article/details/gtykpslmng.html

[I03] 提取捕获分组
来源：http://dali.zhongyouzk.top/Article/details/gtmnhuvhhm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hfpthk.cn/Article/details/gtzfxnpzjj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zycfv.cn/Article/details/gteuqvneqv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.haohaochexian.top/Article/details/gtyvqwtafc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tanke756.top/Article/details/gtjpxiuhrn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yongpay.top/Article/details/gtpjokmzzg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgfzy.top/Article/details/gtypfphvqv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenlongwang.top/Article/details/gtfmxkycbd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ivvv.top/Article/details/gtijvohpdr.html

[I04] 正则替换
来源：http://dali.yj20258.top/Article/details/gthrqappan.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenlongwang.top/Article/details/gtenfyekue.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gotoacloud.top/Article/details/gtlytxcfnz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.redwolf501.top/Article/details/gtqqvncnnn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwgekmhta.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yongpay.top/Article/details/gtefthnaro.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtucmohart.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtmbkbzsvu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258888.top/Article/details/gtdmembqyk.html

[I05] 按正则拆分
来源：http://dali.tian-w.cn/Article/details/gtgqqlrewl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtmpmydljp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.meibo888.top/Article/details/gtwstjebiy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtssfknhul.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtzkmbumvh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hongshengwenyu.top/Article/details/gtbxzjcysk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.haohaochexian.top/Article/details/gtjuacpkrp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gtstjkoyxx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhengqikj.top/Article/details/gtxnickysa.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuxming.cn/Article/details/gtjnduufuf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj202588.top/Article/details/gtqgyemufq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hongshengwenyu.top/Article/details/gtgzlqslng.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gtcsdogsck.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhixingplan.top/Article/details/gtgxwimskq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gtoljmcfqe.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jyoumei.cn/Article/details/gtfrecnuyf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shzxlz.cn/Article/details/gtonqqlrji.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gtfgmipklx.html

[I07] 忽略大小写与多行模式
来源：http://dali.feifeiyinyue.top/Article/details/gtzkkhmdfb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.aizwys.cn/Article/details/gtkekgxfhh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gtuodaouzg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gzhubu.top/Article/details/gtsyxjweuc.html

TS:   /error/gim
来源：http://dali.sufxvd.cn/Article/details/gtvusnfuck.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hysaishi.cn/Article/details/gtwsxspalq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.mhx1999.top/Article/details/gtijtutldr.html

Ruby: s.scan(/error/i)
来源：http://dali.zhoulong.xyz/Article/details/gtuwfdimma.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gogol.net.cn/Article/details/gtsjzpgtqh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yonumen.top/Article/details/gtfompqwrz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yvedp.cn/Article/details/gtoykawjov.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.bjfxy.top/Article/details/gtfnlbyrbl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnqzz.top/Article/details/gtwmwgdfza.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.iojbl.cn/Article/details/gteqxedgsg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj20258.top/Article/details/gtduxxwnjc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ivvv.top/Article/details/gtafssgusl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhiwuduotai.top/Article/details/gtgejjhxtv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.andypj.xyz/Article/details/gtwfktmouo.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtcbswzeyu.html

J. 日期与时间
来源：http://dali.yongpay.top/Article/details/gtgunyignx.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtfradsort.html

[J01] 获取当前时间
来源：http://dali.vqdsnc.cn/Article/details/gtqrbifmts.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.bjfxy.top/Article/details/gtgxmeeoag.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.fzhhl.top/Article/details/gtqkoownod.html

JS:   new Date();  Date.now()
来源：http://dali.jiagoushi.top/Article/details/gtyvtjkuzj.html

TS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gtdplxuzul.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.c1oappe.top/Article/details/gttivkpbmu.html

Go:   time.Now()
来源：http://dali.xylfe.cn/Article/details/gtxrepwasq.html

Ruby: Time.now
来源：http://dali.aizwys.cn/Article/details/gtorinvgoa.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dashuyun.cn/Article/details/gtdgyfumox.html

[J02] 格式化输出
来源：http://dali.gogol.net.cn/Article/details/gtyubngnwu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tian-w.cn/Article/details/gtuoqjvwvn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gtxbumyswl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.feifeiyinyue.top/Article/details/gtenpgpiei.html

TS:   d.toISOString()
来源：http://dali.wangshuangyany.cn/Article/details/gtnjgbdual.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxuanxn.top/Article/details/gtmiwlgjwt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.aibaodan.cn/Article/details/gtqcycobkr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gtfjfayfba.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xuanzx.com/Article/details/gtpevckxvl.html

[J03] 字符串解析为日期
来源：http://dali.meibo888.top/Article/details/gtvyuhgaig.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nwbrower.top/Article/details/gtltkocitg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhoulong.xyz/Article/details/gtiiccbwri.html

JS:   new Date("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtulbqusbn.html

TS:   new Date("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgfbpdkzw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtnmfihxnh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtnvebqhut.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtrftkujqc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuanzx.com/Article/details/gtrgsfbdjv.html

[J04] 时间戳与日期互转
来源：http://dali.jyoumei.cn/Article/details/gttoxwgkrk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gotoacloud.top/Article/details/gtrfdetteo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhengqikj.top/Article/details/gtvdkjmxwq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj20258.top/Article/details/gtfktjaqjm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ydzc1.top/Article/details/gttawcjnqm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtjyuyzrnu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shuidangran.top/Article/details/gtfmzluczb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shuidangran.top/Article/details/gtzkljvact.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nwbrower.top/Article/details/gtilrcdsyp.html

[J05] 时间加减（加 7 天）
来源：http://dali.yonumen.top/Article/details/gtxqxhybfc.html

Py:   now + timedelta(days=7)
来源：http://dali.sweek.top/Article/details/gtcdnckvfj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.vqdsnc.cn/Article/details/gtdccbyxom.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cheryme.top/Article/details/gtgkqqyiyk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cheryme.top/Article/details/gtlibxwfde.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfewhxrgu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.iojbl.cn/Article/details/gtvrdkgryl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fzhhl.top/Article/details/gtfpvwmgoq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.wangshuangyany.cn/Article/details/gthehbdcdv.html

[J06] 计算两时间之差
来源：http://dali.hnqzz.top/Article/details/gticgnvfne.html

Py:   (end - start).total_seconds()
来源：http://dali.yonumen.top/Article/details/gtbwirirgr.html

PHP:  $end->diff($start)->days;
来源：http://dali.gaohongyu789.top/Article/details/gtexwzuzyo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258888.top/Article/details/gtcrlhuoil.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zdqjudy.top/Article/details/gtjvghfjcf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenjidiqi.icu/Article/details/gtrqyrcqhv.html

Go:   end.Sub(start).Hours()
来源：http://dali.svipenyu.cn/Article/details/gtltcxrmbi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hongshengwenyu.top/Article/details/gtrxahtqok.html

C#:   (end - start).TotalSeconds
来源：http://dali.hnxiangtu.top/Article/details/gtnzactgly.html

[J07] 比较两个日期
来源：http://dali.nanxinkj.top/Article/details/gtuxfhtjae.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gtxcpggdlp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.wangshuangyany.cn/Article/details/gtyasoaamz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gtpwhtzvjj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gtgfzedznz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.guowangkeji.top/Article/details/gtyemmqjcf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jqgfzy.top/Article/details/gtjcowrhlr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gtcqbaiwzg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtnwquopiq.html

[J08] 提取年月日与星期
来源：http://dali.redwolf501.top/Article/details/gtdrusxdwv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.guowangkeji.top/Article/details/gtvplsxdss.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jyoumei.cn/Article/details/gtmghggtnu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nanxuanxn.top/Article/details/gtphpvvmhe.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dashuyun.cn/Article/details/gtnioohuyf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuxming.cn/Article/details/gtslemxwrm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.aibaodan.cn/Article/details/gtihggrmhc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.birdmap.top/Article/details/gtqinbtccz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenlongwang.top/Article/details/gtqgnxtxgf.html

[J09] 时区处理
来源：http://dali.guannengcc.top/Article/details/gtdkilejnk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yongpay.top/Article/details/gtfzgtoyam.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yanxiufei.cn/Article/details/gtlpiofcmp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gtooskdxlo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gtgcvdafdh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ydzc1.top/Article/details/gtivqejmyd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.aibaodan.cn/Article/details/gtimvvtxah.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.daxiang520.top/Article/details/gtnstsksst.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258.top/Article/details/gtmqduumnn.html

[J10] 取今天 / 本月第一天
来源：http://dali.pengpengdd.cyou/Article/details/gtrhttppde.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sysykeji.top/Article/details/gtofzwrhvc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.9152youxi.cn/Article/details/gttvjoorkj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ybcxt.top/Article/details/gtuflkaqbk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yonumen.top/Article/details/gtgagxdlzs.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dianchejie.cn/Article/details/gtgtiuzbqy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhiwuduotai.top/Article/details/gtpatwjghx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tian-w.cn/Article/details/gtxzukzrbz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yangfankeji.com/Article/details/gtfdsnjkbt.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gttvpchkhl.html

K. JSON 与序列化
来源：http://dali.316326.xyz/Article/details/gtvaetnblh.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtkhqouemo.html

[K01] 对象转 JSON 字符串
来源：http://dali.daxiang520.top/Article/details/gtnyknzeqm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gtosdtzydh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthhnablgr.html

JS:   JSON.stringify(obj)
来源：http://dali.xziqi.cn/Article/details/gtdhfmgdvz.html

TS:   JSON.stringify(obj)
来源：http://dali.hammf.cn/Article/details/gtnephcsod.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ybcxt.top/Article/details/gthtpydhab.html

Go:   json.Marshal(obj)
来源：http://dali.sufxvd.cn/Article/details/gtigmnwazw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.iojbl.cn/Article/details/gtyjygibld.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.iojbl.cn/Article/details/gtoybzwgzm.html

[K02] JSON 字符串转对象
来源：http://dali.nanxinkj.top/Article/details/gtefnwgzpq.html

Py:   json.loads(s)
来源：http://dali.ybcxt.top/Article/details/gtaxchfbnt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yuxming.cn/Article/details/gtmhydvkeh.html

JS:   JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gtryqqfjqn.html


<!-- 参考信息 -->