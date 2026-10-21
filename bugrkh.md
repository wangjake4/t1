代发 wailian999

Java: class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtqclegafu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.wangshuangyany.cn/Article/details/gtzqidurox.html

Ruby: class Admin < User; end
来源：http://dali.gotoacloud.top/Article/details/gtdoyzajer.html

C#:   class Admin : User {}
来源：http://dali.guowangkeji.top/Article/details/gthrqjlhuh.html

[G06] 重写方法
来源：http://dali.cucudq.cn/Article/details/gtfcxxiixh.html

Py:   def greet(self): return "admin"
来源：http://dali.iojbl.cn/Article/details/gttrmvjrns.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gtakghsgmi.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtmzdupbbe.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtpabababp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtxuhksaxh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shzxlz.cn/Article/details/gtofmuedwq.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvdrravx.html

C#:   public override string Greet() => "admin";
来源：http://dali.yangfankeji.com/Article/details/gtkbzajjhj.html

[G07] 调用父类方法
来源：http://dali.jiagoushi.top/Article/details/gtsjtzbztv.html

Py:   super().greet()
来源：http://dali.jqgfzy.top/Article/details/gtpgphmyva.html

PHP:  parent::greet();
来源：http://dali.sysykeji.top/Article/details/gtwjwdrlev.html

JS:   super.greet();
来源：http://dali.cheryme.top/Article/details/gttxqhbxcc.html

TS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbwunopn.html

Java: super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtwigdlill.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhixingplan.top/Article/details/gtvilioysn.html

Ruby: super
来源：http://dali.guannengcc.top/Article/details/gtflibaypt.html

C#:   base.Greet();
来源：http://dali.ivvv.top/Article/details/gtdxmqibyz.html

[G08] 静态方法与属性
来源：http://dali.nwbrower.top/Article/details/gtjxqkxysb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jianghu66.top/Article/details/gtoslyhksi.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gtnxttkycn.html

JS:   static f() {}
来源：http://dali.havefunace.top/Article/details/gtebylbdub.html

TS:   static f(): void {}
来源：http://dali.sufxvd.cn/Article/details/gtupdtykoi.html

Java: static void f() {}
来源：http://dali.hywenlv.cn/Article/details/gtngzeptmk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zycfv.cn/Article/details/gtcqxilhva.html

Ruby: def self.f; end
来源：http://dali.dashuyun.cn/Article/details/gtgricvasy.html

C#:   public static void F() {}
来源：http://dali.iojbl.cn/Article/details/gtiwcfpqwc.html

[G09] 接口 / 抽象类
来源：http://dali.gzhubu.top/Article/details/gtqysblmol.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.9152youxi.cn/Article/details/gtwasdsmph.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jlsjyb.cn/Article/details/gtmdfshqfs.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgufenzy.top/Article/details/gtcqxpiaik.html

TS:   interface Shape { area(): number; }
来源：http://dali.gogol.net.cn/Article/details/gtflwraifl.html

Java: interface Shape { double area(); }
来源：http://dali.jianghu66.top/Article/details/gtsseakmin.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.aizwys.cn/Article/details/gthjqavfbm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tanke756.top/Article/details/gtulhuvhun.html

C#:   interface IShape { double Area(); }
来源：http://dali.hysaishi.cn/Article/details/gtucllshvc.html

[G10] 访问控制
来源：http://dali.yangfankeji.com/Article/details/gtnitehxor.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhengqikj.top/Article/details/gtbmpignty.html

PHP:  public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gthcfzqgvm.html

JS:   #private 字段；其余公开
来源：http://dali.sweek.top/Article/details/gtdczraqci.html

TS:   public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtjfbdpsmo.html

Java: public / protected / private / 默认包级
来源：http://dali.zhixingplan.top/Article/details/gtliissqnb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guowangkeji.top/Article/details/gtbdrtfrfj.html

Ruby: public / protected / private
来源：http://dali.sweek.top/Article/details/gtlqeeyimh.html

C#:   public / protected / private / internal
来源：http://dali.c1oappe.top/Article/details/gtauiuhroa.html

[G11] getter / setter
来源：http://dali.haohaochexian.top/Article/details/gtxmfqypts.html

Py:   @property 与 @x.setter
来源：http://dali.zhiwuduotai.top/Article/details/gtatdfmvwy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gtcpposncx.html

JS:   get name() { return this._name; }
来源：http://dali.smart0.xyz/Article/details/gtktdrmhbi.html

TS:   get name(): string { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gtfimkoqkw.html

Java: public String getName() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtqgemjlxt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtlykctprn.html

Ruby: attr_accessor :name
来源：http://dali.svipenyu.cn/Article/details/gthmdtvjai.html

C#:   public string Name { get; set; }
来源：http://dali.daria6918.cn/Article/details/gtnmcnxvhf.html

[G12] 对象转字符串
来源：http://dali.jinqigfzy.top/Article/details/gthxlvrpdl.html

Py:   def __str__(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gtbqtsiobd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtacozqsuv.html

JS:   toString() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtfpljwuph.html

TS:   toString(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtobsrgvmx.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnqzz.top/Article/details/gtmexogrwm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gtvflfmgkl.html

Ruby: def to_s; @name; end
来源：http://dali.wangdashe.top/Article/details/gtojdxjtwl.html

C#:   public override string ToString() => Name;
来源：http://dali.tianlin.xyz/Article/details/gtijukbqlz.html

[G13] 判断对象类型
来源：http://dali.c1oappe.top/Article/details/gtpdatfuzm.html

Py:   isinstance(u, User)
来源：http://dali.gzhubu.top/Article/details/gtgxxagwly.html

PHP:  $u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtddebivyx.html

JS:   u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtlyovbjqe.html

TS:   u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gthtmpxovm.html

Java: u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxacjsbjf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shuidangran.top/Article/details/gtpzpnxesu.html

Ruby: u.is_a?(User)
来源：http://dali.nwbrower.top/Article/details/gtdqwyqhxe.html

C#:   u is User
来源：http://dali.jianghu66.top/Article/details/gthsyquufz.html

[G14] 数据类 / record
来源：http://dali.jinqigfzy.top/Article/details/gtvrosgppu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.0kj1m.cn/Article/details/gtoqskqksa.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cashguo.top/Article/details/gtcubxqmlr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhoulong.xyz/Article/details/gtdmtfdztu.html

TS:   type User = { name: string; age: number };
来源：http://dali.yongpay.top/Article/details/gtcvauvfyn.html

Java: record User(String name, int age) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtwcazwktt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zycfv.cn/Article/details/gtmudhaztj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tanke756.top/Article/details/gtgjbwpmol.html

C#:   record User(string Name, int Age);
来源：http://dali.hnxiangtu.top/Article/details/gtptjcodab.html

[G15] 枚举
来源：http://dali.svipenyu.cn/Article/details/gtktudawbe.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.aibaodan.cn/Article/details/gttlqpwycw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sxryk.cn/Article/details/gtdfayzofd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sufxvd.cn/Article/details/gtzteqcpas.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtutdtnvch.html

Java: enum Color { RED, GREEN }
来源：http://dali.hnxiangtu.top/Article/details/gtwuqtlgyb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.aibaodan.cn/Article/details/gtxkujigmv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenlongwang.top/Article/details/gtcwaoldev.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gtkkoqtgad.html

[G16] 对象转数组 / 字典
来源：http://dali.tian-w.cn/Article/details/gtczjkgebb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuxming.cn/Article/details/gtpumtemck.html

PHP:  get_object_vars($obj);
来源：http://dali.hnxiangtu.top/Article/details/gtggnoeptb.html

JS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gtfppbgldu.html

TS:   Object.entries(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gteqsxalzd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tianlin.xyz/Article/details/gtqlwbnurw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.havefunace.top/Article/details/gtlmpibhnp.html

Ruby: obj.instance_variables
来源：http://dali.guannengcc.top/Article/details/gtwqdxvexg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gthxaasder.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtootevhum.html

H. 异常与错误处理
来源：http://dali.daxiang520.top/Article/details/gthwmassdo.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtxokhbkch.html

[H01] try / catch 基础
来源：http://dali.jinqigufen.top/Article/details/gtwcwkfqyx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dianchejie.cn/Article/details/gtmmdpbzan.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtifoxkjww.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gtkvcrcjdm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gtjocwiolp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hammf.cn/Article/details/gtyqzybpee.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqtsqrja.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.svipenyu.cn/Article/details/gtqpgsvhej.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cqqwz.cn/Article/details/gtxigrnwmm.html

[H02] finally / ensure 收尾
来源：http://dali.jianghu66.top/Article/details/gtvlsvysir.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258888.top/Article/details/gtlbfmfnxm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtqhaeugak.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtoridpeke.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gttzlsbmlf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gthygxwrpw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ppjwa.cn/Article/details/gtzpgdamrh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnxiangtu.top/Article/details/gtxjdunwhl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sweek.top/Article/details/gtkmjrfffa.html

[H03] 主动抛出异常
来源：http://dali.jinqigfzy.top/Article/details/gtonslsgaw.html

Py:   raise ValueError("错误信息")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbpmxazrb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtineurofx.html

JS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtvlzvxnir.html

TS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtlatcovvi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtcxjzutxo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuetiantiany.cn/Article/details/gtumktapne.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sweek.top/Article/details/gtxfzdgwyt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtvouwqtqx.html

[H04] 自定义异常类型
来源：http://dali.svipenyu.cn/Article/details/gtgmewdixb.html

Py:   class MyError(Exception): pass
来源：http://dali.sweek.top/Article/details/gtnnhqbfks.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gtafukgzek.html

JS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gttiwixgnm.html

TS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gtngvdkhou.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgplomkq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hnqzz.top/Article/details/gtoyaksivg.html

Ruby: class MyError < StandardError; end
来源：http://dali.sysykeji.top/Article/details/gttvnukrpt.html

C#:   class MyException : Exception {}
来源：http://dali.nwbrower.top/Article/details/gtaichngws.html

[H05] 捕获特定类型
来源：http://dali.birdmap.top/Article/details/gtunkewtbl.html

Py:   except ValueError as e:
来源：http://dali.ehwqpu.com/Article/details/gtsovdplvw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nwbrower.top/Article/details/gthordkdjt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xziqi.cn/Article/details/gtqnjoywco.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdptweuhw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cucudq.cn/Article/details/gtoxdxflyf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.havefunace.top/Article/details/gtdswagffb.html

Ruby: rescue ArgumentError => e
来源：http://dali.pycfn.com/Article/details/gtdbfrqnaq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtxaxvwsxp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ydzc1.top/Article/details/gtegvcvktd.html

Py:   value = d.get("k") or default
来源：http://dali.jqgufenzy.top/Article/details/gtzsslzoji.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gthrqtibut.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tianlin.xyz/Article/details/gtxtnwwbac.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gtnwlzqevw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ydzc1.top/Article/details/gtuhfnjbpl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yvedp.cn/Article/details/gtmizwqggr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sweek.top/Article/details/gtqmqxeocu.html

C#:   obj?.A?.B ?? default
来源：http://dali.gogol.net.cn/Article/details/gthdbqlnwp.html

[H07] 断言
来源：http://dali.xziqi.cn/Article/details/gtlreixfco.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258.top/Article/details/gtcklufzll.html

PHP:  assert($x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtwtbhhpsu.html

JS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtbuvqylln.html

TS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtbeixlzml.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yongpay.top/Article/details/gtbncdukar.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.316326.xyz/Article/details/gtxgcjyozu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zycfv.cn/Article/details/gtzcreomfd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtrryuagbn.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdmvkuey.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhoulong.xyz/Article/details/gtypmtmwef.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yonumen.top/Article/details/gtoxlttuas.html

JS:   e.message;  e.stack
来源：http://dali.yongpay.top/Article/details/gtcubtudie.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.meibo888.top/Article/details/gtjncauhit.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.smart0.xyz/Article/details/gtjhziyaor.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gtcnfrtbzr.html

Ruby: e.message;  e.backtrace
来源：http://dali.andypj.xyz/Article/details/gtipmwrqrn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.feifeiyinyue.top/Article/details/gtxpsltnzo.html

[H09] 带错误码的异常
来源：http://dali.gogol.net.cn/Article/details/gthmyvxygx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangdashe.top/Article/details/gtnjgoagcu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhoulong.xyz/Article/details/gtuecbvlmv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xinyue.icu/Article/details/gtamceooni.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqimhntj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenjidiqi.icu/Article/details/gtqasnxjti.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hfpthk.cn/Article/details/gtwrunltxf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgufenzy.top/Article/details/gtavagkovu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hnxiangtu.top/Article/details/gthazwyqyq.html

[H10] 资源自动释放
来源：http://dali.9152youxi.cn/Article/details/gtwqwvzljq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ehwqpu.com/Article/details/gtmcudznug.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gogol.net.cn/Article/details/gtjtwrlwre.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhongyouzk.top/Article/details/gtqjjoxdjr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.vqdsnc.cn/Article/details/gtcwoawugh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jiagoushi.top/Article/details/gtstxrwsgt.html

Go:   defer f.Close()
来源：http://dali.fzhhl.top/Article/details/gtchxlwycg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.wangdashe.top/Article/details/gtaaakjbwv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtatlizmwi.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtxdsvpqxo.html

I. 正则表达式
来源：http://dali.nanxinkj.top/Article/details/gtdwpiybdh.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtjkrsrrok.html

[I01] 判断是否匹配
来源：http://dali.xziqi.cn/Article/details/gtwugmwzgf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gtkqupfqhg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtticdeuum.html

JS:   /\d+/.test(s)
来源：http://dali.yonumen.top/Article/details/gtnwaaygpe.html

TS:   /\d+/.test(s)
来源：http://dali.tian-w.cn/Article/details/gtrlfdjdtu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cqqwz.cn/Article/details/gtfxbikouw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.vqdsnc.cn/Article/details/gtjdwbtqzi.html

Ruby: s.match?(/\d+/)
来源：http://dali.iojbl.cn/Article/details/gtcgcsqwjr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nwbrower.top/Article/details/gtutbtlxbc.html

[I02] 提取所有匹配
来源：http://dali.gzhubu.top/Article/details/gtveozjikd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.fzhhl.top/Article/details/gtwzaonkwo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.snrcjt.cn/Article/details/gthzigcguj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sysykeji.top/Article/details/gtvnhvvkbr.html

TS:   s.match(/\d+/g)
来源：http://dali.feifeiyinyue.top/Article/details/gtyebxtjcv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigufen.top/Article/details/gtvowmdlme.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.andypj.xyz/Article/details/gtohjjvhdm.html

Ruby: s.scan(/\d+/)
来源：http://dali.guannengcc.top/Article/details/gtkfxdhooj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cucudq.cn/Article/details/gtiaujnpkv.html

[I03] 提取捕获分组
来源：http://dali.cashguo.top/Article/details/gtmigouzcs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.fengsongda.top/Article/details/gtkqkxzpab.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxinkj.top/Article/details/gtsuupcdkn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tian-w.cn/Article/details/gttrxttjgc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.iojbl.cn/Article/details/gtjiuzsdei.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cqqwz.cn/Article/details/gtiaxikfdw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shuidangran.top/Article/details/gtnddtengu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.birdmap.top/Article/details/gtbbvjyxzr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yangfankeji.com/Article/details/gtwedybgbs.html

[I04] 正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gtuvjycndz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.smart0.xyz/Article/details/gtyoysdgfw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimruxbuv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cheryme.top/Article/details/gtgqzlowui.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gtwmtirbxc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gtgkvsczvl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.birdmap.top/Article/details/gtqwilhyle.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrnxftvgr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hongshengwenyu.top/Article/details/gttugsnlvv.html

[I05] 按正则拆分
来源：http://dali.xziqi.cn/Article/details/gtkdlpidmn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jiagoushi.top/Article/details/gtyvjmwncr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.guowangkeji.top/Article/details/gtgvolfxck.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gtkmrscoam.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gtjcwvupza.html

Java: s.split("\\s*,\\s*")
来源：http://dali.mhx1999.top/Article/details/gttcvcmiju.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.aibaodan.cn/Article/details/gtfinredbv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtshxqhmik.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.havefunace.top/Article/details/gtmqfmiddy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hammf.cn/Article/details/gtodmnusug.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gtekljspmd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.daxiang520.top/Article/details/gtkztabmmi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hysaishi.cn/Article/details/gtirsbeqlf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dianchejie.cn/Article/details/gtwukffuly.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gtfscbamks.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.mhx1999.top/Article/details/gtnjwmztuh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.dashuyun.cn/Article/details/gtfndcgczo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gtqfqqwtia.html

[I07] 忽略大小写与多行模式
来源：http://dali.hfpthk.cn/Article/details/gtewdosepl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.316326.xyz/Article/details/gtgfpkwixn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gtcekqyyck.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dianchejie.cn/Article/details/gtvziswdbt.html

TS:   /error/gim
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljkdluvu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sysykeji.top/Article/details/gtgcrnwdbw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xuetiantiany.cn/Article/details/gtiozwhizk.html

Ruby: s.scan(/error/i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaflxdfxj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.kuanghao11.cn/Article/details/gtfojiudui.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.andypj.xyz/Article/details/gtsdfuxzdt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sxryk.cn/Article/details/gtovyubdvk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yvedp.cn/Article/details/gtlmrilctf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.birdmap.top/Article/details/gtddokpucf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gtknhzktnn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gtzaxtsawr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jlsjyb.cn/Article/details/gtnoasweyb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenzaomai.com/Article/details/gtkvlslppv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.c1oappe.top/Article/details/gteyybapek.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtbzyrssis.html

J. 日期与时间
来源：http://dali.xinyue.icu/Article/details/gtugnfqxfy.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtrmmngyon.html

[J01] 获取当前时间
来源：http://dali.sufxvd.cn/Article/details/gtorlpmdzv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhongyouzk.top/Article/details/gtskcmqrzg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gtkpozlynm.html

JS:   new Date();  Date.now()
来源：http://dali.daxiang520.top/Article/details/gtlvdqsfqd.html

TS:   new Date();  Date.now()
来源：http://dali.dashuyun.cn/Article/details/gtharenmhg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jqgfzy.top/Article/details/gtoswgkwjs.html

Go:   time.Now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagxhnfmh.html

Ruby: Time.now
来源：http://dali.hywenlv.cn/Article/details/gtqjegrwds.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sweek.top/Article/details/gtzmnppnbf.html

[J02] 格式化输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtwucwarqr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gotoacloud.top/Article/details/gtpmbnuodb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj20258888.top/Article/details/gtyzjqkhid.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sweek.top/Article/details/gtznsfurob.html

TS:   d.toISOString()
来源：http://dali.tanke756.top/Article/details/gtnijivmiu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yanxiufei.cn/Article/details/gtmeilzakv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shzxlz.cn/Article/details/gtbdwackha.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yvedp.cn/Article/details/gthalvbqvj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.quarkkingdee.top/Article/details/gtzjsehsui.html

[J03] 字符串解析为日期
来源：http://dali.316326.xyz/Article/details/gtmexvxfhc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ydzc1.top/Article/details/gtfgjaqeof.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.guannengcc.top/Article/details/gtnjaanudw.html

JS:   new Date("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtampoabbt.html

TS:   new Date("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtsbbodbbx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtvdkvahlm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtyacmcnrz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gteazkfrkw.html


<!-- 参考信息 -->