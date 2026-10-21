代发 wailian999

C#:   public / protected / private / internal
来源：http://dali.haohaochexian.top/Article/details/gtymvztikk.html

[G11] getter / setter
来源：http://dali.0kj1m.cn/Article/details/gtbknvkptn.html

Py:   @property 与 @x.setter
来源：http://dali.chenjidiqi.icu/Article/details/gtrwfhhtqx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtoxllkssl.html

JS:   get name() { return this._name; }
来源：http://dali.smart0.xyz/Article/details/gtpoamgndh.html

TS:   get name(): string { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gtvjrkvsyd.html

Java: public String getName() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtxfaokgii.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtpyfczwxe.html

Ruby: attr_accessor :name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkovvecp.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258888.top/Article/details/gtiasjusfn.html

[G12] 对象转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtzyxstell.html

Py:   def __str__(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gtwkcdfxlz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtlicjmkzc.html

JS:   toString() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtnzvpbsgy.html

TS:   toString(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtiuuankbf.html

Java: @Override public String toString() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtxyxowsdm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shuidangran.top/Article/details/gtgnrfsgxa.html

Ruby: def to_s; @name; end
来源：http://dali.cdnleiting.top/Article/details/gtrqpjzvwz.html

C#:   public override string ToString() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gtdhyyehun.html

[G13] 判断对象类型
来源：http://dali.zhixingplan.top/Article/details/gtwwlwuvop.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxeyywjk.html

PHP:  $u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gtvekwukoe.html

JS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtezywmhbo.html

TS:   u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtsripchgf.html

Java: u instanceof User
来源：http://dali.birdmap.top/Article/details/gtenglhpyc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhixingplan.top/Article/details/gtojcsgyyl.html

Ruby: u.is_a?(User)
来源：http://dali.ybcxt.top/Article/details/gtujukgzac.html

C#:   u is User
来源：http://dali.xuanzx.com/Article/details/gtatmghflo.html

[G14] 数据类 / record
来源：http://dali.ydzc1.top/Article/details/gtbbyegjle.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sysykeji.top/Article/details/gtppoywlii.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ybcxt.top/Article/details/gtdzuazoau.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sysykeji.top/Article/details/gtneizjvmx.html

TS:   type User = { name: string; age: number };
来源：http://dali.ybcxt.top/Article/details/gtrbjcgqwa.html

Java: record User(String name, int age) {}
来源：http://dali.jinqigfzy.top/Article/details/gtvsoglxzf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhongyouzk.top/Article/details/gtisextekm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.0kj1m.cn/Article/details/gtqkduugxv.html

C#:   record User(string Name, int Age);
来源：http://dali.hongshengwenyu.top/Article/details/gtkxqzwsev.html

[G15] 枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gtatpkwgvd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yuxming.cn/Article/details/gtuhtuiwyr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.meibo888.top/Article/details/gtkfpiqexk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zycfv.cn/Article/details/gtgkdoxzfy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.svipenyu.cn/Article/details/gtmvhgirbo.html

Java: enum Color { RED, GREEN }
来源：http://dali.haohaochexian.top/Article/details/gtdvmszebx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhiwuduotai.top/Article/details/gtukfdkvgj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlpvurzjq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtfeozrsdr.html

[G16] 对象转数组 / 字典
来源：http://dali.ydzc1.top/Article/details/gtzaqruxnc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hnqzz.top/Article/details/gtevhdjtvp.html

PHP:  get_object_vars($obj);
来源：http://dali.cdnleiting.top/Article/details/gtzjbmrouw.html

JS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gtuzwzybvc.html

TS:   Object.entries(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtabiwlmul.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdsdcarly.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.9152youxi.cn/Article/details/gtqhwbsyml.html

Ruby: obj.instance_variables
来源：http://dali.xuetiantiany.cn/Article/details/gtgrrnkwkc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gtefgahwav.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtcqcpiciy.html

H. 异常与错误处理
来源：http://dali.tanke756.top/Article/details/gtenqdcswc.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtanqbbujd.html

[H01] try / catch 基础
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxaarxnbp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhongyouzk.top/Article/details/gtpkxyqvtw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guannengcc.top/Article/details/gtwmmfjiix.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gtexutxqtf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gtygyrriug.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.meibo888.top/Article/details/gtgjchkflu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbbhiahce.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.quarkkingdee.top/Article/details/gtvkegledl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqqdlmri.html

[H02] finally / ensure 收尾
来源：http://dali.cdnleiting.top/Article/details/gtikanmkme.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgufenzy.top/Article/details/gtbysygark.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtjemlggdb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtpyaafpcd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtzdzhljwe.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtwrxraweb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenzaomai.com/Article/details/gtdldgeddk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangdashe.top/Article/details/gttyxvfboe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzidhimkx.html

[H03] 主动抛出异常
来源：http://dali.cashguo.top/Article/details/gtzfxcjufp.html

Py:   raise ValueError("错误信息")
来源：http://dali.guowangkeji.top/Article/details/gthxvzuwep.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtkutcegvx.html

JS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtjyrysjkk.html

TS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gtsgufgzkz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtmyjenaii.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sysykeji.top/Article/details/gtovdnkipl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ivvv.top/Article/details/gtzkleskou.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtwqddsrpa.html

[H04] 自定义异常类型
来源：http://dali.zhoulong.xyz/Article/details/gtcxevuopr.html

Py:   class MyError(Exception): pass
来源：http://dali.aibaodan.cn/Article/details/gtiyswzhxf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gtcibdhgpw.html

JS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gtbstqlmke.html

TS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gtympytzrf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gtvyastkbd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tanke756.top/Article/details/gtvccpkoxl.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenzaomai.com/Article/details/gtsfxmqbot.html

C#:   class MyException : Exception {}
来源：http://dali.ydzc1.top/Article/details/gtegzdpbrg.html

[H05] 捕获特定类型
来源：http://dali.xuanzx.com/Article/details/gtxvpvdjmo.html

Py:   except ValueError as e:
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqflgbhxo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzltvsbm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hnxiangtu.top/Article/details/gthxdlodil.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hfpthk.cn/Article/details/gtkhvcmpup.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gticjlktzk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gaohongyu789.top/Article/details/gtczcpurdf.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgufenzy.top/Article/details/gthhdrgmbn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhmtiihb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgfzy.top/Article/details/gtwogcwjsc.html

Py:   value = d.get("k") or default
来源：http://dali.xinyue.icu/Article/details/gtkmrompct.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangdashe.top/Article/details/gtcowurmtw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtdaeiftsv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gtwxsnjnat.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.meibo888.top/Article/details/gtaxixxnfm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ivvv.top/Article/details/gtnrsdddbp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sufxvd.cn/Article/details/gtmwbzrale.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgfzy.top/Article/details/gtiwdftkvn.html

[H07] 断言
来源：http://dali.yuanzhike.top/Article/details/gthklzqlzq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ppjwa.cn/Article/details/gtwuarssco.html

PHP:  assert($x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtrluqskhp.html

JS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtemhxwfwk.html

TS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gthljthfio.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nwbrower.top/Article/details/gtcrpwalhv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.fengsongda.top/Article/details/gtirotfmju.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xziqi.cn/Article/details/gtbszudzwp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtwafkfkfr.html

[H08] 获取错误信息与堆栈
来源：http://dali.hywenlv.cn/Article/details/gtotyqkpup.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hnxiangtu.top/Article/details/gtepyqiccb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258.top/Article/details/gtnfiqrdex.html

JS:   e.message;  e.stack
来源：http://dali.zhaomingkeji.xyz/Article/details/gthlalkvsq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zdqjudy.top/Article/details/gthjwndngr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jlsjyb.cn/Article/details/gtqwzsucvg.html

Go:   err.Error()
来源：http://dali.yj20258888.top/Article/details/gteknldych.html

Ruby: e.message;  e.backtrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvpylhntc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yvedp.cn/Article/details/gtgslpbncp.html

[H09] 带错误码的异常
来源：http://dali.chenlongwang.top/Article/details/gteuvjilds.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.daxiang520.top/Article/details/gtfoemzkbt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cheryme.top/Article/details/gtsveepdeu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yonumen.top/Article/details/gtxszhtfvb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenjidiqi.icu/Article/details/gtbhdwigoj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jianghu66.top/Article/details/gtbmricfbk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.havefunace.top/Article/details/gtvapqhfax.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hongshengwenyu.top/Article/details/gtkgbsxapk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuxming.cn/Article/details/gtslpdibzx.html

[H10] 资源自动释放
来源：http://dali.smart0.xyz/Article/details/gtmyccnahs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.bjfxy.top/Article/details/gtbkdzczcz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhongyouzk.top/Article/details/gtlwnazzsa.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.redwolf501.top/Article/details/gtqevkhqsg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnxiangtu.top/Article/details/gtgguicpbz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.redwolf501.top/Article/details/gtitoqnmva.html

Go:   defer f.Close()
来源：http://dali.0kj1m.cn/Article/details/gtcdoqinbf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hnxiangtu.top/Article/details/gtbfrxrgoc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtebuzicga.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtddsvqnoh.html

I. 正则表达式
来源：http://dali.quarkkingdee.top/Article/details/gtqltpyohg.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtledauvmo.html

[I01] 判断是否匹配
来源：http://dali.yuxming.cn/Article/details/gtczhpvyia.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gtzvycwrbd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gteyhsrhmp.html

JS:   /\d+/.test(s)
来源：http://dali.jqgfzy.top/Article/details/gtzysyxrmq.html

TS:   /\d+/.test(s)
来源：http://dali.yj20258.top/Article/details/gtirobeeri.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.mhx1999.top/Article/details/gtyjjvfmmc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hysaishi.cn/Article/details/gtbjsaukru.html

Ruby: s.match?(/\d+/)
来源：http://dali.hongshengwenyu.top/Article/details/gtyqduicxi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cucudq.cn/Article/details/gtkalcdabe.html

[I02] 提取所有匹配
来源：http://dali.yj20258888.top/Article/details/gtttmepzto.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yonumen.top/Article/details/gtgqphoedh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.c1oappe.top/Article/details/gtkfcbxzqy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hammf.cn/Article/details/gtqsklvzmo.html

TS:   s.match(/\d+/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgimlhxde.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258888.top/Article/details/gtmcctdewk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cucudq.cn/Article/details/gtojdceeri.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuhzdzval.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtenicdwet.html

[I03] 提取捕获分组
来源：http://dali.pengpengdd.cyou/Article/details/gtnxjqtagp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ydzc1.top/Article/details/gtvgyajdtf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj20258.top/Article/details/gthnejqrlb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtphigumtx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjibvfti.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cdnleiting.top/Article/details/gtltgjgirc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhoulong.xyz/Article/details/gtkwjanzue.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xinyue.icu/Article/details/gtivcyywiu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zycfv.cn/Article/details/gtixlxljko.html

[I04] 正则替换
来源：http://dali.fengsongda.top/Article/details/gtpbqrwygw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xylfe.cn/Article/details/gtnnjvdctq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shuidangran.top/Article/details/gtlrplystv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tanke756.top/Article/details/gtgkwyseim.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gtgfvdkqll.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cheryme.top/Article/details/gtshdewoth.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinqigufen.top/Article/details/gtevaxobrt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.havefunace.top/Article/details/gtyuomekfl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.9152youxi.cn/Article/details/gtjufbzihf.html

[I05] 按正则拆分
来源：http://dali.daxiang520.top/Article/details/gtmrgywlsw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cheryme.top/Article/details/gtlwvozooj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.smart0.xyz/Article/details/gtxtdgclfx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gthbujwjfm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gtpyvpeiye.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ehwqpu.com/Article/details/gtfyuxpjhz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gtevkrwzde.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gtlicvjato.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj20258.top/Article/details/gthfainkvq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zdqjudy.top/Article/details/gtsotqxkkb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gtbmvzgpap.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tanke756.top/Article/details/gtxoaisqpk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gtyldpgprc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgfzy.top/Article/details/gtgzbnsbck.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gtzwyydotc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cashguo.top/Article/details/gteiglkeym.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.0kj1m.cn/Article/details/gtjjywamcp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gthhxmkgtk.html

[I07] 忽略大小写与多行模式
来源：http://dali.hysaishi.cn/Article/details/gtabtjxzbo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhiwuduotai.top/Article/details/gtudugepbi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.meibo888.top/Article/details/gtmapxgoyo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hysaishi.cn/Article/details/gtosajohkk.html

TS:   /error/gim
来源：http://dali.daxiang520.top/Article/details/gtakmuhter.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nwbrower.top/Article/details/gtvuqgjghl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnxiangtu.top/Article/details/gtuvozqhfk.html

Ruby: s.scan(/error/i)
来源：http://dali.zhengqikj.top/Article/details/gtasobzdff.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hysaishi.cn/Article/details/gtaonfropq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shuidangran.top/Article/details/gtwqtxeqfb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jqgfzy.top/Article/details/gtqdyaqoof.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shangyingyoupin.top/Article/details/gtztsjyzym.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.birdmap.top/Article/details/gtmlkfaydi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gtbwtvrnjg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gtxquzxplt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.c1oappe.top/Article/details/gtrprqmjyj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdwvjprvl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhengqikj.top/Article/details/gtzxcjqtnx.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjyhwepg.html

J. 日期与时间
来源：http://dali.dianchejie.cn/Article/details/gtbllruwon.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtpcfmrcrp.html

[J01] 获取当前时间
来源：http://dali.cheryme.top/Article/details/gtuqrhrioh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.aizwys.cn/Article/details/gtjfqwmkxg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shanyushiyangtech.top/Article/details/gthbdmagyg.html

JS:   new Date();  Date.now()
来源：http://dali.dashuyun.cn/Article/details/gtkwsaxlkj.html

TS:   new Date();  Date.now()
来源：http://dali.aizwys.cn/Article/details/gtfzyaatfy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hongshengwenyu.top/Article/details/gtckcfdtku.html

Go:   time.Now()
来源：http://dali.bjfxy.top/Article/details/gtbfawvbud.html

Ruby: Time.now
来源：http://dali.zdqjudy.top/Article/details/gtxjhrhwgj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.iojbl.cn/Article/details/gtnfthsqkb.html

[J02] 格式化输出
来源：http://dali.cucudq.cn/Article/details/gtyidfiigo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gttimosbvw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfgdkqtva.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nanxuanxn.top/Article/details/gtkuxdttjt.html

TS:   d.toISOString()
来源：http://dali.yj20258.top/Article/details/gtcdmvzpwv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xinyue.icu/Article/details/gtavybesww.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jiagoushi.top/Article/details/gttcihmeyt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gtxibautij.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hammf.cn/Article/details/gtkmfjqyue.html

[J03] 字符串解析为日期
来源：http://dali.jinqigfzy.top/Article/details/gtyljvekor.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.mhx1999.top/Article/details/gtzfejsmap.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sweek.top/Article/details/gtxjgxezxe.html

JS:   new Date("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgaepzdpe.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gttakwbmpd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtmzwdtfaw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtyfdxrezz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtojdljtog.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.haohaochexian.top/Article/details/gtcdszamfk.html

[J04] 时间戳与日期互转
来源：http://dali.kuanghao11.cn/Article/details/gtypgpxpul.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cqqwz.cn/Article/details/gtotdvlevq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokchhujk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.dashuyun.cn/Article/details/gtqehegjjb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xziqi.cn/Article/details/gtrdsahsqm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tianlin.xyz/Article/details/gttycaqnsf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtrqwyvihk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xziqi.cn/Article/details/gtqqvbubay.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yongpay.top/Article/details/gtvqonuteq.html

[J05] 时间加减（加 7 天）
来源：http://dali.snrcjt.cn/Article/details/gtcxrgrksy.html

Py:   now + timedelta(days=7)
来源：http://dali.tanke756.top/Article/details/gtcahmwfyr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhiwuduotai.top/Article/details/gtuebtmyhz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yueranfly.top/Article/details/gtfjoauvhl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gtrmmudgmy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fengsongda.top/Article/details/gtzuatyxxf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tian-w.cn/Article/details/gtnwjkprrb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xylfe.cn/Article/details/gtcfgarfqy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinqigfzy.top/Article/details/gthilrroxg.html

[J06] 计算两时间之差
来源：http://dali.svipenyu.cn/Article/details/gtmqcvxxmn.html

Py:   (end - start).total_seconds()
来源：http://dali.sweek.top/Article/details/gtqcdfeetk.html

PHP:  $end->diff($start)->days;
来源：http://dali.0kj1m.cn/Article/details/gtvffxaxof.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xylfe.cn/Article/details/gtjlfttglo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gogol.net.cn/Article/details/gtcntqtobd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jqgufenzy.top/Article/details/gtsmewjqzt.html

Go:   end.Sub(start).Hours()
来源：http://dali.snrcjt.cn/Article/details/gtgxytrodx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.havefunace.top/Article/details/gtvodlujen.html

C#:   (end - start).TotalSeconds
来源：http://dali.cucudq.cn/Article/details/gtiskxtvzz.html

[J07] 比较两个日期
来源：http://dali.svipenyu.cn/Article/details/gtuloiblez.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gttooedsri.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxuanxn.top/Article/details/gteagzistp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cheryme.top/Article/details/gtdnwchhkj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gtilyyssqk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.9152youxi.cn/Article/details/gtxnuznwib.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtziivjwbv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gttothalos.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gtlgnmuoel.html

[J08] 提取年月日与星期
来源：http://dali.cashguo.top/Article/details/gtjgrvnlxt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.pycfn.com/Article/details/gtyspvzcjp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gaohongyu789.top/Article/details/gtslbpddbh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tianlin.xyz/Article/details/gttyjmmjrs.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cucudq.cn/Article/details/gtcirybgst.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sxryk.cn/Article/details/gtkmrgigyf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.daxiang520.top/Article/details/gtudozdrtn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.smart0.xyz/Article/details/gtroznnlri.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.svipenyu.cn/Article/details/gtowuuxwad.html

[J09] 时区处理
来源：http://dali.tian-w.cn/Article/details/gtycrkqaod.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hfpthk.cn/Article/details/gtwpnyzzak.html


<!-- 参考信息 -->