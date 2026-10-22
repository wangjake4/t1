代发 wailian999

Py:   class Admin(User): pass
来源：http://dali.hnqzz.top/Article/details/gtftufigmq.html

PHP:  class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtqtaebxxe.html

JS:   class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtbgmlezva.html

TS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtisfnbweu.html

Java: class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtatojjdyv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cucudq.cn/Article/details/gtfzxsxrhv.html

Ruby: class Admin < User; end
来源：http://dali.quarkkingdee.top/Article/details/gtwljxayyk.html

C#:   class Admin : User {}
来源：http://dali.daria6918.cn/Article/details/gtawftehcl.html

[G06] 重写方法
来源：http://dali.sysykeji.top/Article/details/gtppeflnux.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigufen.top/Article/details/gtmbulzgqt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtjztlgitj.html

JS:   greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtojowsmfw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtqrdhlqud.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtmacsbbqa.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shanyushiyangtech.top/Article/details/gtmawfmazy.html

Ruby: def greet; "admin"; end
来源：http://dali.zhoulong.xyz/Article/details/gtkavwzasa.html

C#:   public override string Greet() => "admin";
来源：http://dali.pycfn.com/Article/details/gtjkoodzvx.html

[G07] 调用父类方法
来源：http://dali.iojbl.cn/Article/details/gtjqeimojp.html

Py:   super().greet()
来源：http://dali.gaohongyu789.top/Article/details/gtzifcjwgu.html

PHP:  parent::greet();
来源：http://dali.vqdsnc.cn/Article/details/gtaxvpvjhm.html

JS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtqorqgxmu.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtumjjsmyd.html

Java: super.greet();
来源：http://dali.jianghu66.top/Article/details/gtgloxjfsd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenzaomai.com/Article/details/gtdnshivji.html

Ruby: super
来源：http://dali.kuanghao11.cn/Article/details/gtztenqhkc.html

C#:   base.Greet();
来源：http://dali.dianchejie.cn/Article/details/gtckajlzjr.html

[G08] 静态方法与属性
来源：http://dali.hnxiangtu.top/Article/details/gtzdcfujej.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpfmohjh.html

PHP:  public static function f() {}
来源：http://dali.cashguo.top/Article/details/gtbdkjzxob.html

JS:   static f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gttcttxkhi.html

TS:   static f(): void {}
来源：http://dali.nanxinkj.top/Article/details/gtbavqalul.html

Java: static void f() {}
来源：http://dali.zycfv.cn/Article/details/gtyhgakwyu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tianlin.xyz/Article/details/gtetheywio.html

Ruby: def self.f; end
来源：http://dali.yuanzhike.top/Article/details/gtsructzwk.html

C#:   public static void F() {}
来源：http://dali.zhixingplan.top/Article/details/gtzggtuxyb.html

[G09] 接口 / 抽象类
来源：http://dali.havefunace.top/Article/details/gtvehcgwnk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gotoacloud.top/Article/details/gtxqsbezuf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sweek.top/Article/details/gtitiraqsb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cheryme.top/Article/details/gtpsxfznwh.html

TS:   interface Shape { area(): number; }
来源：http://dali.gzhubu.top/Article/details/gttpzuhbxa.html

Java: interface Shape { double area(); }
来源：http://dali.zhoulong.xyz/Article/details/gtxkohvjws.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gtdslykndh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenzaomai.com/Article/details/gtaikmrlzf.html

C#:   interface IShape { double Area(); }
来源：http://dali.shzxlz.cn/Article/details/gtrcxxnlqn.html

[G10] 访问控制
来源：http://dali.0kj1m.cn/Article/details/gtxhohvthm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.snrcjt.cn/Article/details/gterkdedex.html

PHP:  public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtwcowamgg.html

JS:   #private 字段；其余公开
来源：http://dali.ybcxt.top/Article/details/gtpcnjmrfa.html

TS:   public / protected / private
来源：http://dali.fengsongda.top/Article/details/gtmoceijss.html

Java: public / protected / private / 默认包级
来源：http://dali.cdnleiting.top/Article/details/gtydugerwl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.vqdsnc.cn/Article/details/gtzujzsbor.html

Ruby: public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtxzsulwpb.html

C#:   public / protected / private / internal
来源：http://dali.yongpay.top/Article/details/gtbxrcqisl.html

[G11] getter / setter
来源：http://dali.redwolf501.top/Article/details/gtwifhxnxc.html

Py:   @property 与 @x.setter
来源：http://dali.zhoulong.xyz/Article/details/gtgufbboji.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gtbsroftvw.html

JS:   get name() { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gtvtdckiud.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenzaomai.com/Article/details/gtcwoefohv.html

Java: public String getName() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtmlgxpcer.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtepmsknvr.html

Ruby: attr_accessor :name
来源：http://dali.xylfe.cn/Article/details/gtofqoxmpb.html

C#:   public string Name { get; set; }
来源：http://dali.quarkkingdee.top/Article/details/gtbbaxdumy.html

[G12] 对象转字符串
来源：http://dali.nanxinkj.top/Article/details/gtwfslkhve.html

Py:   def __str__(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gtkxybxjat.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtqkhswdfn.html

JS:   toString() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtulrtkmmp.html

TS:   toString(): string { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtawwxtzln.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtihlqngeg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtcokeeria.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gtepbtqskc.html

C#:   public override string ToString() => Name;
来源：http://dali.birdmap.top/Article/details/gtvqlasojd.html

[G13] 判断对象类型
来源：http://dali.aibaodan.cn/Article/details/gtnoqflvsz.html

Py:   isinstance(u, User)
来源：http://dali.guowangkeji.top/Article/details/gtyjoxqoeo.html

PHP:  $u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtcvpbmrtr.html

JS:   u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtabjvpnnk.html

TS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvztaqhm.html

Java: u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtzhifjyjh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jiagoushi.top/Article/details/gtzzaqhdcy.html

Ruby: u.is_a?(User)
来源：http://dali.yj202588.top/Article/details/gtmxaenewu.html

C#:   u is User
来源：http://dali.pengpengdd.cyou/Article/details/gtkjldcxvr.html

[G14] 数据类 / record
来源：http://dali.0kj1m.cn/Article/details/gtmhanrncr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dashuyun.cn/Article/details/gtvmgyxkzm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.haohaochexian.top/Article/details/gtzcufaesf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjzzmgoif.html

TS:   type User = { name: string; age: number };
来源：http://dali.xylfe.cn/Article/details/gtqigvsihu.html

Java: record User(String name, int age) {}
来源：http://dali.hysaishi.cn/Article/details/gtomkwpdem.html

Go:   type User struct { Name string; Age int }
来源：http://dali.fzhhl.top/Article/details/gtlapyyfrb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gzhubu.top/Article/details/gtvnbwuono.html

C#:   record User(string Name, int Age);
来源：http://dali.bjfxy.top/Article/details/gtjfawvbwn.html

[G15] 枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqitaoxla.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.bjfxy.top/Article/details/gtupxlckcm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nwbrower.top/Article/details/gtfkqaxiip.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gaohongyu789.top/Article/details/gtvdstyssw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gtezucaimt.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhongyouzk.top/Article/details/gtrwsmmgyz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hnxiangtu.top/Article/details/gtdkgybvws.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sweek.top/Article/details/gttdqvxsxa.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnqzz.top/Article/details/gtzmhjnuyf.html

[G16] 对象转数组 / 字典
来源：http://dali.yanxiufei.cn/Article/details/gtvscpzkqk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gzhubu.top/Article/details/gtbohqajxh.html

PHP:  get_object_vars($obj);
来源：http://dali.guowangkeji.top/Article/details/gtsvfalnmp.html

JS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gtsckbkwoi.html

TS:   Object.entries(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtonvachlq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258888.top/Article/details/gtqzspkmbb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhixingplan.top/Article/details/gtyfrjgyaf.html

Ruby: obj.instance_variables
来源：http://dali.jianghu66.top/Article/details/gtyruoekdl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gtorisyqav.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbhnevbs.html

H. 异常与错误处理
来源：http://dali.chenlongwang.top/Article/details/gthaofrjrg.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtfgehectf.html

[H01] try / catch 基础
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcxlyugw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.316326.xyz/Article/details/gtnqularrm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtsqkdvchx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gtwlrvcykp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtbioemjem.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxvhsthq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.daxiang520.top/Article/details/gtugcqagoc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yanxiufei.cn/Article/details/gtzwcunaau.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj202588.top/Article/details/gtmqpmfjee.html

[H02] finally / ensure 收尾
来源：http://dali.hnqzz.top/Article/details/gtvkokpnso.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tanke756.top/Article/details/gtufrtentd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtnwgctpdi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtzmpcxavl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gthxdlxeda.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtoavxmupc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.kuanghao11.cn/Article/details/gtxcvnfmmm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hywenlv.cn/Article/details/gtasaegnwq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtrvifyfiv.html

[H03] 主动抛出异常
来源：http://dali.havefunace.top/Article/details/gtadnwnamo.html

Py:   raise ValueError("错误信息")
来源：http://dali.yvedp.cn/Article/details/gtbrdhidkz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtdmsdjigd.html

JS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtxxsfhvtl.html

TS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gtozjgyvdd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtaiwrtlld.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.pengpengdd.cyou/Article/details/gtcuuugtis.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangtech.top/Article/details/gthuectzlp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtlxlhwgyy.html

[H04] 自定义异常类型
来源：http://dali.yvedp.cn/Article/details/gtfjxrnmhx.html

Py:   class MyError(Exception): pass
来源：http://dali.yanxiufei.cn/Article/details/gtyzpcllfz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.feifeiyinyue.top/Article/details/gtdsfuygfi.html

JS:   class MyError extends Error {}
来源：http://dali.hywenlv.cn/Article/details/gtvgjmtpkf.html

TS:   class MyError extends Error {}
来源：http://dali.aizwys.cn/Article/details/gtaegeufjl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gthtuozqsv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aibaodan.cn/Article/details/gtwibdcfwe.html

Ruby: class MyError < StandardError; end
来源：http://dali.shzxlz.cn/Article/details/gtaeiikatb.html

C#:   class MyException : Exception {}
来源：http://dali.gaohongyu789.top/Article/details/gtrspsqcmq.html

[H05] 捕获特定类型
来源：http://dali.cheryme.top/Article/details/gthlchkmup.html

Py:   except ValueError as e:
来源：http://dali.zhengqikj.top/Article/details/gtqemhuorx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cucudq.cn/Article/details/gtphecwthy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.vqdsnc.cn/Article/details/gtvhngxzct.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gtcykcqvcy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtrksfkxfx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.quarkkingdee.top/Article/details/gtqhwcsqrb.html

Ruby: rescue ArgumentError => e
来源：http://dali.guowangkeji.top/Article/details/gtaynnrgff.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258888.top/Article/details/gtjvsoboxe.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ybcxt.top/Article/details/gtsvkhkeho.html

Py:   value = d.get("k") or default
来源：http://dali.sufxvd.cn/Article/details/gtyaggtgba.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gtmytvgibo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlupmetbw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yueranfly.top/Article/details/gtnvgsjkmr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.fzhhl.top/Article/details/gtrbrrebub.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.guowangkeji.top/Article/details/gtghvoppwi.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ydzc1.top/Article/details/gtazqwstoi.html

C#:   obj?.A?.B ?? default
来源：http://dali.birdmap.top/Article/details/gtobmxemdc.html

[H07] 断言
来源：http://dali.chenzaomai.com/Article/details/gtuambgziz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gotoacloud.top/Article/details/gtkfgvrfdv.html

PHP:  assert($x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtvjdghbgt.html

JS:   console.assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtvdvfzayk.html

TS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtvggdgxoz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhengqikj.top/Article/details/gtticngrug.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258.top/Article/details/gtmtqcfexc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sxryk.cn/Article/details/gtbfwzcfsq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtovtyhbbg.html

[H08] 获取错误信息与堆栈
来源：http://dali.nanxinkj.top/Article/details/gthsspqgdv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gotoacloud.top/Article/details/gtnjyejnph.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jiagoushi.top/Article/details/gtnycsjzsf.html

JS:   e.message;  e.stack
来源：http://dali.aibaodan.cn/Article/details/gtpjwmmzln.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ivvv.top/Article/details/gteqrosgqb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tanke756.top/Article/details/gtcuprcolc.html

Go:   err.Error()
来源：http://dali.yuanzhike.top/Article/details/gtkiitzzge.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenlongwang.top/Article/details/gtjkuukegc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.9152youxi.cn/Article/details/gtkaimjtcq.html

[H09] 带错误码的异常
来源：http://dali.feifeiyinyue.top/Article/details/gtstxjomko.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xuetiantiany.cn/Article/details/gtajvzqbhc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shzxlz.cn/Article/details/gtgoseonpo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cashguo.top/Article/details/gtypddzfxx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fzhhl.top/Article/details/gtuepxygbt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zycfv.cn/Article/details/gtolnxnjfz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj20258888.top/Article/details/gtpzpkxzpy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhixingplan.top/Article/details/gtvhexbuqy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangshuangyany.cn/Article/details/gtygljaafo.html

[H10] 资源自动释放
来源：http://dali.smart0.xyz/Article/details/gtflyxmijn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiqlwydhv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.guannengcc.top/Article/details/gtmhjjzwuv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gtrjwkyakd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gtnciyfynu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.fengsongda.top/Article/details/gtztrtojvm.html

Go:   defer f.Close()
来源：http://dali.yj202588.top/Article/details/gtjakygoca.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.meibo888.top/Article/details/gtstnddtdz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtojkrvdst.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtxtgzrvuo.html

I. 正则表达式
来源：http://dali.shangyingyoupin.top/Article/details/gtyozfknjs.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtmsxsxbhr.html

[I01] 判断是否匹配
来源：http://dali.yanxiufei.cn/Article/details/gtrnwsphvq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhixingplan.top/Article/details/gtdxqchgnd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.redwolf501.top/Article/details/gtkglisuzh.html

JS:   /\d+/.test(s)
来源：http://dali.xylfe.cn/Article/details/gtvyhlwstg.html

TS:   /\d+/.test(s)
来源：http://dali.nwbrower.top/Article/details/gtezyakeua.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.snrcjt.cn/Article/details/gtwlcyxdqc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtyrhodcdh.html

Ruby: s.match?(/\d+/)
来源：http://dali.9152youxi.cn/Article/details/gtbnczuvda.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tianlin.xyz/Article/details/gtwnxbaarp.html

[I02] 提取所有匹配
来源：http://dali.hywenlv.cn/Article/details/gtrdgxyyle.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yonumen.top/Article/details/gterthqffr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hysaishi.cn/Article/details/gtiyzwcyio.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zycfv.cn/Article/details/gtmtflcmlr.html

TS:   s.match(/\d+/g)
来源：http://dali.shuidangran.top/Article/details/gtewkxazat.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.kuanghao11.cn/Article/details/gtoxmicrrz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gtystecpex.html

Ruby: s.scan(/\d+/)
来源：http://dali.hnxiangtu.top/Article/details/gtizmhafcc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shuidangran.top/Article/details/gtxcmljpyg.html

[I03] 提取捕获分组
来源：http://dali.gaohongyu789.top/Article/details/gtztuzllpb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xinyue.icu/Article/details/gtcyelnusi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daria6918.cn/Article/details/gtwxgbgiii.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.fengsongda.top/Article/details/gtxmjjpybz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ybcxt.top/Article/details/gtcnrzeswy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiqwhplug.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuxming.cn/Article/details/gtbhbczrls.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.iojbl.cn/Article/details/gtdcwxazky.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zycfv.cn/Article/details/gttddpowuy.html

[I04] 正则替换
来源：http://dali.gogol.net.cn/Article/details/gtwizherjb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sweek.top/Article/details/gtzvqzvosv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtpmrjshvg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cashguo.top/Article/details/gtczgrzdqo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhixingplan.top/Article/details/gtvtdydvbz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jyoumei.cn/Article/details/gtlsipzfzz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hammf.cn/Article/details/gtpcpvblpg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenlongwang.top/Article/details/gtzerqgzkh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yonumen.top/Article/details/gtlsoubrjg.html

[I05] 按正则拆分
来源：http://dali.tianlin.xyz/Article/details/gtzrxzbdlw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtriydlgwg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtaharbqtb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gtyjhdcugz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gtepadcskc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.wangdashe.top/Article/details/gtjicfydxl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.havefunace.top/Article/details/gtzfmdfmgl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gtyhdjoxmf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.0kj1m.cn/Article/details/gthsljfcsn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cdnleiting.top/Article/details/gthzwkdmvi.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gtnwrrzdxl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xylfe.cn/Article/details/gtvvgvuapd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258888.top/Article/details/gtzkvogldo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenzaomai.com/Article/details/gtsgndfxjg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gtgaakgcha.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.bjfxy.top/Article/details/gtdiswpual.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenzaomai.com/Article/details/gtnlteyjua.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtsjviotcq.html

[I07] 忽略大小写与多行模式
来源：http://dali.nanxuanxn.top/Article/details/gtwbcmhqyh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.feifeiyinyue.top/Article/details/gtilspwccr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gtggczzmcy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xylfe.cn/Article/details/gtzpnmuwgt.html

TS:   /error/gim
来源：http://dali.cucudq.cn/Article/details/gtfmfetyye.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenzaomai.com/Article/details/gtcgugibzv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.redwolf501.top/Article/details/gtvpkghzte.html

Ruby: s.scan(/error/i)
来源：http://dali.tianlin.xyz/Article/details/gtjjaucbjg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinghuilouyu.cn/Article/details/gtehvtiorb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xziqi.cn/Article/details/gtcmzxqftj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yueranfly.top/Article/details/gtgjjzxdxk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gtbzklvdss.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daria6918.cn/Article/details/gtihteugvt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuanzhike.top/Article/details/gtuykfjgcu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hysaishi.cn/Article/details/gttanvtbye.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtppoxahuy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.havefunace.top/Article/details/gtuialugdw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gtuimkhajk.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtmuoflkwb.html

J. 日期与时间
来源：http://dali.vqdsnc.cn/Article/details/gtawbyhpdf.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtgxjzefcg.html

[J01] 获取当前时间
来源：http://dali.cashguo.top/Article/details/gtrpgsvrov.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.aibaodan.cn/Article/details/gtgbpibucf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gtmgdkoidt.html

JS:   new Date();  Date.now()
来源：http://dali.cdnleiting.top/Article/details/gtiutfzdob.html

TS:   new Date();  Date.now()
来源：http://dali.zdqjudy.top/Article/details/gtwqxbprxi.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dashuyun.cn/Article/details/gtdrgekjmj.html

Go:   time.Now()
来源：http://dali.pengpengdd.cyou/Article/details/gtnwivsprk.html

Ruby: Time.now
来源：http://dali.guannengcc.top/Article/details/gtstqsyreb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tanke756.top/Article/details/gtzmkfbzhf.html

[J02] 格式化输出
来源：http://dali.hywenlv.cn/Article/details/gtjubvnywj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtncmzgjku.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenlongwang.top/Article/details/gtdaofwtrj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwmkoryo.html

TS:   d.toISOString()
来源：http://dali.jqgfzy.top/Article/details/gtdamqnrbl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cashguo.top/Article/details/gtcelgqsdy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yvedp.cn/Article/details/gtyvtxxzqm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gtcxwjdclu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.guannengcc.top/Article/details/gtcqmtqnjg.html

[J03] 字符串解析为日期
来源：http://dali.gaohongyu789.top/Article/details/gthxjjuyke.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yuxming.cn/Article/details/gtaefqrjjs.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sufxvd.cn/Article/details/gtzlhorhxd.html

JS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtshdeuasl.html


<!-- 参考信息 -->