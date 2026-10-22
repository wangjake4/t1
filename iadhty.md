代发 wailian999

Ruby: super
来源：http://dali.jianghu66.top/Article/details/gtrfqkprau.html

C#:   base.Greet();
来源：http://dali.zhongyouzk.top/Article/details/gtpflonnwb.html

[G08] 静态方法与属性
来源：http://dali.fengsongda.top/Article/details/gtvaxiyuyt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.quarkkingdee.top/Article/details/gtkipsnhsp.html

PHP:  public static function f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtdmnmxvaf.html

JS:   static f() {}
来源：http://dali.smart0.xyz/Article/details/gtapwttace.html

TS:   static f(): void {}
来源：http://dali.0kj1m.cn/Article/details/gtbausteln.html

Java: static void f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyavjcaak.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.c1oappe.top/Article/details/gtogqegaet.html

Ruby: def self.f; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmmndjxm.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtawcauiov.html

[G09] 接口 / 抽象类
来源：http://dali.yangfankeji.com/Article/details/gtnnztbboa.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jianghu66.top/Article/details/gtolcdvycn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhiwuduotai.top/Article/details/gtrvrxkljv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hongshengwenyu.top/Article/details/gtreqmbtck.html

TS:   interface Shape { area(): number; }
来源：http://dali.gotoacloud.top/Article/details/gtnnkhpufq.html

Java: interface Shape { double area(); }
来源：http://dali.cheryme.top/Article/details/gtngnniogl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jianghu66.top/Article/details/gtqzpggtfa.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gtttdatmal.html

C#:   interface IShape { double Area(); }
来源：http://dali.daxiang520.top/Article/details/gtonfhupbk.html

[G10] 访问控制
来源：http://dali.iojbl.cn/Article/details/gtdpifbddr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.havefunace.top/Article/details/gtjzxpuodh.html

PHP:  public / protected / private
来源：http://dali.cashguo.top/Article/details/gtwcokxcax.html

JS:   #private 字段；其余公开
来源：http://dali.daria6918.cn/Article/details/gtnikkeyrq.html

TS:   public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gtkarpiitq.html

Java: public / protected / private / 默认包级
来源：http://dali.hysaishi.cn/Article/details/gtrxtrqmhl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fengsongda.top/Article/details/gtupgnhriv.html

Ruby: public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtgybbqnbq.html

C#:   public / protected / private / internal
来源：http://dali.hywenlv.cn/Article/details/gtrsyvazjx.html

[G11] getter / setter
来源：http://dali.redwolf501.top/Article/details/gtorqeigib.html

Py:   @property 与 @x.setter
来源：http://dali.vqdsnc.cn/Article/details/gtbilsmmta.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gtsvujvbnj.html

JS:   get name() { return this._name; }
来源：http://dali.meibo888.top/Article/details/gtzybccaam.html

TS:   get name(): string { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gtozyaxatf.html

Java: public String getName() { return name; }
来源：http://dali.aizwys.cn/Article/details/gtmmesrwlm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gtzdrcaahc.html

Ruby: attr_accessor :name
来源：http://dali.hfpthk.cn/Article/details/gtgubbudxx.html

C#:   public string Name { get; set; }
来源：http://dali.tanke756.top/Article/details/gtcckfxlmr.html

[G12] 对象转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gthorswudk.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gtgskvrjfn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gtklmgqwpi.html

JS:   toString() { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtznbcypkn.html

TS:   toString(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtjbnqlcox.html

Java: @Override public String toString() { return name; }
来源：http://dali.daria6918.cn/Article/details/gtewizfgjf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtdjzvqyfv.html

Ruby: def to_s; @name; end
来源：http://dali.nanxinkj.top/Article/details/gtmhspricp.html

C#:   public override string ToString() => Name;
来源：http://dali.yj202588.top/Article/details/gtqukuybeq.html

[G13] 判断对象类型
来源：http://dali.yueranfly.top/Article/details/gtqcjkevph.html

Py:   isinstance(u, User)
来源：http://dali.zdqjudy.top/Article/details/gtmilplmyp.html

PHP:  $u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtnxbuxjia.html

JS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtdgqcngvs.html

TS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtthpdlnpo.html

Java: u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtdvzrkoam.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zdqjudy.top/Article/details/gtonhklhod.html

Ruby: u.is_a?(User)
来源：http://dali.hnxiangtu.top/Article/details/gtvardceir.html

C#:   u is User
来源：http://dali.shangyingyoupin.top/Article/details/gtqqdbwoml.html

[G14] 数据类 / record
来源：http://dali.gogol.net.cn/Article/details/gtvuzaxqim.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nwbrower.top/Article/details/gtftheneri.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuetiantiany.cn/Article/details/gthodyuqvj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shuidangran.top/Article/details/gtmdhizmtg.html

TS:   type User = { name: string; age: number };
来源：http://dali.shzxlz.cn/Article/details/gtiubkwrbc.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258888.top/Article/details/gtffmnzuas.html

Go:   type User struct { Name string; Age int }
来源：http://dali.redwolf501.top/Article/details/gtpiujmveh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvbqvfhwx.html

C#:   record User(string Name, int Age);
来源：http://dali.gotoacloud.top/Article/details/gtmfhdjhyn.html

[G15] 枚举
来源：http://dali.andypj.xyz/Article/details/gtqukubaex.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenjidiqi.icu/Article/details/gtcscwpxjl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtttmovfwr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jiagoushi.top/Article/details/gtxjqhfcwm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yongpay.top/Article/details/gtacymyjws.html

Java: enum Color { RED, GREEN }
来源：http://dali.nwbrower.top/Article/details/gtmbplikdm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.c1oappe.top/Article/details/gtdshkavfb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aizwys.cn/Article/details/gtnajtxryc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtlzefaupn.html

[G16] 对象转数组 / 字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhewdgpz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xuetiantiany.cn/Article/details/gtrbhoyatx.html

PHP:  get_object_vars($obj);
来源：http://dali.vqdsnc.cn/Article/details/gtddswxgve.html

JS:   Object.entries(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtdvawmmps.html

TS:   Object.entries(obj)
来源：http://dali.zhoulong.xyz/Article/details/gthvhaszsx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xziqi.cn/Article/details/gtlsghenhw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xylfe.cn/Article/details/gtounpaudu.html

Ruby: obj.instance_variables
来源：http://dali.shangyingyoupin.top/Article/details/gtyxuknzyi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gzhubu.top/Article/details/gtbxygeexn.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtrxtdofjh.html

H. 异常与错误处理
来源：http://dali.yongpay.top/Article/details/gtpdhtzlpi.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtxaojxqzg.html

[H01] try / catch 基础
来源：http://dali.ivvv.top/Article/details/gtegewltwz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.daxiang520.top/Article/details/gtxtzapxye.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yvedp.cn/Article/details/gtafaklxut.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gtdcpjtbmp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gtoauwhmvz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.316326.xyz/Article/details/gtkkykxzcm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.guowangkeji.top/Article/details/gtmlhibjvq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ybcxt.top/Article/details/gtuanbyezz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.dianchejie.cn/Article/details/gtdkwqaikm.html

[H02] finally / ensure 收尾
来源：http://dali.ehwqpu.com/Article/details/gteuyiozqd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hfpthk.cn/Article/details/gtjreaqijw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtkgulsets.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtzblkjwvh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtxehzrzeh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtqwgbzmyi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shzxlz.cn/Article/details/gtpnyjquon.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sysykeji.top/Article/details/gtrxoxiuly.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwmpyijei.html

[H03] 主动抛出异常
来源：http://dali.jinqigufen.top/Article/details/gtcyaqbjxd.html

Py:   raise ValueError("错误信息")
来源：http://dali.pengpengdd.cyou/Article/details/gtofvzdwas.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtpztoucjg.html

JS:   throw new Error("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtpduzlezo.html

TS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtbxgjgjdk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtwkcbedpv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhongyouzk.top/Article/details/gtfvuszxxe.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sweek.top/Article/details/gtairbmfyq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtpiiewrfa.html

[H04] 自定义异常类型
来源：http://dali.ybcxt.top/Article/details/gttlsbpums.html

Py:   class MyError(Exception): pass
来源：http://dali.xuetiantiany.cn/Article/details/gtswfblfxc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gtlkprzkdr.html

JS:   class MyError extends Error {}
来源：http://dali.hysaishi.cn/Article/details/gtqlebitac.html

TS:   class MyError extends Error {}
来源：http://dali.daxiang520.top/Article/details/gttqzpjjwz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gtknaslgau.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgfzy.top/Article/details/gtjixvavea.html

Ruby: class MyError < StandardError; end
来源：http://dali.c1oappe.top/Article/details/gtoqeoupec.html

C#:   class MyException : Exception {}
来源：http://dali.shzxlz.cn/Article/details/gtcggarfih.html

[H05] 捕获特定类型
来源：http://dali.0kj1m.cn/Article/details/gtefujotpc.html

Py:   except ValueError as e:
来源：http://dali.sxryk.cn/Article/details/gtjvlbufda.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gaohongyu789.top/Article/details/gtlrfrbjsf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyygwuymp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gthlmltwmy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yangfankeji.com/Article/details/gtaoeeqyrn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sweek.top/Article/details/gtdbyetptz.html

Ruby: rescue ArgumentError => e
来源：http://dali.havefunace.top/Article/details/gtspznjmsq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.haohaochexian.top/Article/details/gthwsdtuwe.html

[H06] 可选值 / 空值安全访问
来源：http://dali.iojbl.cn/Article/details/gtwsrkgveq.html

Py:   value = d.get("k") or default
来源：http://dali.9152youxi.cn/Article/details/gtwnylypfv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gtepngvcjt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuxming.cn/Article/details/gttgsikdny.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gtjojjxfto.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ydzc1.top/Article/details/gtrnhmzznw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgufenzy.top/Article/details/gtterryhub.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ivvv.top/Article/details/gtagxhhdqy.html

C#:   obj?.A?.B ?? default
来源：http://dali.sweek.top/Article/details/gtmpidppsz.html

[H07] 断言
来源：http://dali.nwbrower.top/Article/details/gtekgbilnm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jlsjyb.cn/Article/details/gtixdlzjvs.html

PHP:  assert($x > 0);
来源：http://dali.gzhubu.top/Article/details/gtghdastqs.html

JS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtbkugzdsf.html

TS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtfmujkide.html

Java: assert x > 0 : "必须为正";
来源：http://dali.daria6918.cn/Article/details/gtvbnwvcfq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shangyingyoupin.top/Article/details/gtaombsote.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cashguo.top/Article/details/gtgvyfkxqo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gtnctnyfed.html

[H08] 获取错误信息与堆栈
来源：http://dali.zycfv.cn/Article/details/gtjwozpxmr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xylfe.cn/Article/details/gtxecjwhkp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenzaomai.com/Article/details/gtdpputmns.html

JS:   e.message;  e.stack
来源：http://dali.xinyue.icu/Article/details/gtyyudsgkd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgfzy.top/Article/details/gtudnshszp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnxiangtu.top/Article/details/gtoxejohjh.html

Go:   err.Error()
来源：http://dali.dianchejie.cn/Article/details/gtnrlpwxol.html

Ruby: e.message;  e.backtrace
来源：http://dali.aibaodan.cn/Article/details/gtfikmdjeg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jlsjyb.cn/Article/details/gtjuwpumii.html

[H09] 带错误码的异常
来源：http://dali.hfpthk.cn/Article/details/gtcnxltbbz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ppjwa.cn/Article/details/gtxtrcomnz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbacysmg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yongpay.top/Article/details/gthfnerhuk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.haohaochexian.top/Article/details/gtqgffigua.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.guannengcc.top/Article/details/gtjkweoydr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hysaishi.cn/Article/details/gtcmglcopx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zdqjudy.top/Article/details/gtwwimjavj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pengpengdd.cyou/Article/details/gtjpxikgrk.html

[H10] 资源自动释放
来源：http://dali.fzhhl.top/Article/details/gtwieiavqz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthroxydyk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yvedp.cn/Article/details/gtlzmgfbnz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gtrcndfrzj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ivvv.top/Article/details/gtegcmzwnn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ivvv.top/Article/details/gtqgmiwaia.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gtcjnzgefs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhixingplan.top/Article/details/gthtebjptl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtcmfmdovc.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtasngrdjr.html

I. 正则表达式
来源：http://dali.hnqzz.top/Article/details/gtbfjnzaht.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtclcyixal.html

[I01] 判断是否匹配
来源：http://dali.tian-w.cn/Article/details/gthyazqkjy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.mhx1999.top/Article/details/gtxxrjtirh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.havefunace.top/Article/details/gtrfrrbtqp.html

JS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gthietylmo.html

TS:   /\d+/.test(s)
来源：http://dali.ehwqpu.com/Article/details/gtleghekgm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gotoacloud.top/Article/details/gtdzrtlhov.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.9152youxi.cn/Article/details/gtpncpklqo.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gttuguckmu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258.top/Article/details/gtmislxrmn.html

[I02] 提取所有匹配
来源：http://dali.nanxinkj.top/Article/details/gtrrhxlgpz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xylfe.cn/Article/details/gtcrrqbfvy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jiagoushi.top/Article/details/gtcaupitux.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinghuilouyu.cn/Article/details/gtxfggyzvh.html

TS:   s.match(/\d+/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxquntvpu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gaohongyu789.top/Article/details/gtievlrbmb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hfpthk.cn/Article/details/gtgodntnxk.html

Ruby: s.scan(/\d+/)
来源：http://dali.kuanghao11.cn/Article/details/gtqyfvdfvu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tanke756.top/Article/details/gtpdwatdmu.html

[I03] 提取捕获分组
来源：http://dali.yj202588.top/Article/details/gtjblgbfdb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cdnleiting.top/Article/details/gtbdlsrihr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sufxvd.cn/Article/details/gteezqbqll.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tian-w.cn/Article/details/gtcjawpoin.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.bjfxy.top/Article/details/gtgabdzkqf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hfpthk.cn/Article/details/gtxtjzedcj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.fengsongda.top/Article/details/gtbmzqttxn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhengqikj.top/Article/details/gtafqkpxmk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hnqzz.top/Article/details/gtetbhyack.html

[I04] 正则替换
来源：http://dali.jiagoushi.top/Article/details/gtjctulhla.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.pycfn.com/Article/details/gtqnuhlhvr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guowangkeji.top/Article/details/gtrdjzscuf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtrwoagdbo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daria6918.cn/Article/details/gtczfmqrly.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ppjwa.cn/Article/details/gtaciswzzo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimxhmsjx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinqigufen.top/Article/details/gtepegwotp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gtwlxpihmo.html

[I05] 按正则拆分
来源：http://dali.zycfv.cn/Article/details/gtwbhnjaar.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.mhx1999.top/Article/details/gtwzesnzwh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xziqi.cn/Article/details/gttcyznkxe.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gtwvhkfore.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gtmozsrmpi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfcqaujgi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqwhzxpb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gtyiyfmsyd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.vqdsnc.cn/Article/details/gtmmwacpom.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shanyushiyangtech.top/Article/details/gtxsynfnob.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj202588.top/Article/details/gtfqsnakjn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.0kj1m.cn/Article/details/gtpqzqowdw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.316326.xyz/Article/details/gtohmequfz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258888.top/Article/details/gtycewmmpu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtkxntyzfq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.feifeiyinyue.top/Article/details/gtcnpspowv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.pycfn.com/Article/details/gtuldmduio.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gtpjuvdxxh.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinqigufen.top/Article/details/gtuhaolsau.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenlongwang.top/Article/details/gtxcwkpdri.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhixingplan.top/Article/details/gtoffriwro.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hywenlv.cn/Article/details/gttoxmenvt.html

TS:   /error/gim
来源：http://dali.zhiwuduotai.top/Article/details/gtzxjjpukb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.c1oappe.top/Article/details/gtcofqnnfl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jlsjyb.cn/Article/details/gtpxqzjnfv.html

Ruby: s.scan(/error/i)
来源：http://dali.pengpengdd.cyou/Article/details/gtidodrarv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xylfe.cn/Article/details/gtadolrsyj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gotoacloud.top/Article/details/gtywxnxwwy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fzhhl.top/Article/details/gtgfgobjkn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cucudq.cn/Article/details/gtnxbtjtle.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gtcrnfnopv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gtqsoqxkfu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthiwchoag.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ppjwa.cn/Article/details/gtruoxcebi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.316326.xyz/Article/details/gtiowxrykb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sweek.top/Article/details/gtkdugvwsn.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtgpqcmvbj.html

J. 日期与时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtaalzdaux.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtbnceqhid.html

[J01] 获取当前时间
来源：http://dali.c1oappe.top/Article/details/gttgqnnyca.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.fengsongda.top/Article/details/gtmjzmpzzz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gtjvjccwew.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gtayjeyjhj.html

TS:   new Date();  Date.now()
来源：http://dali.tianlin.xyz/Article/details/gtcnwcecoo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jiagoushi.top/Article/details/gtuvbiquyd.html

Go:   time.Now()
来源：http://dali.chenlongwang.top/Article/details/gtsygvbdbi.html

Ruby: Time.now
来源：http://dali.zhiwuduotai.top/Article/details/gtogkhuphn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaluwtqdg.html

[J02] 格式化输出
来源：http://dali.hammf.cn/Article/details/gtmgrlfpal.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sweek.top/Article/details/gtnmcodkvt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gtgsykdgdy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhongyouzk.top/Article/details/gtvyysoule.html

TS:   d.toISOString()
来源：http://dali.316326.xyz/Article/details/gtuspanbkx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxuanxn.top/Article/details/gtznajicfu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gogol.net.cn/Article/details/gtkztvnkef.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gtfmarsfdc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenjidiqi.icu/Article/details/gtmrvbdkaf.html

[J03] 字符串解析为日期
来源：http://dali.quarkkingdee.top/Article/details/gtyhcujmtl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shangyingyoupin.top/Article/details/gtuidgjvfs.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hywenlv.cn/Article/details/gtiarazbcg.html

JS:   new Date("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtgkgdnfmd.html

TS:   new Date("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtwwnfvrdj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtsjryrzqa.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtggegqnvc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtjxvutkup.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nwbrower.top/Article/details/gtwcdqbndz.html

[J04] 时间戳与日期互转
来源：http://dali.shzxlz.cn/Article/details/gtzytvbqzh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hammf.cn/Article/details/gtneluuvww.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.haohaochexian.top/Article/details/gtfmmzmpcs.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gogol.net.cn/Article/details/gtfuakakht.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gaohongyu789.top/Article/details/gtqibxciwf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtsosjxaeq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yangfankeji.com/Article/details/gtykrkhgap.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aibaodan.cn/Article/details/gtltsfczck.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cashguo.top/Article/details/gtjexmzhxc.html

[J05] 时间加减（加 7 天）
来源：http://dali.quarkkingdee.top/Article/details/gtsjmbcdwg.html

Py:   now + timedelta(days=7)
来源：http://dali.yanxiufei.cn/Article/details/gtajsqtxtq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sweek.top/Article/details/gtijgttnki.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jianghu66.top/Article/details/gtflywmwut.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.birdmap.top/Article/details/gtwiscaaci.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cdnleiting.top/Article/details/gtdundcokk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jyoumei.cn/Article/details/gtmmuzuuml.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yangfankeji.com/Article/details/gtzyfvtaxc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ybcxt.top/Article/details/gtqxudhznf.html

[J06] 计算两时间之差
来源：http://dali.fengsongda.top/Article/details/gtxtzjyofz.html


<!-- 参考信息 -->