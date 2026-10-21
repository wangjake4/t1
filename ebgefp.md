代发 wailian999

Java: class User {}
来源：http://dali.yuxming.cn/Article/details/gtdswvqzyr.html

Go:   type User struct { Name string }
来源：http://dali.smart0.xyz/Article/details/gtvbldagaa.html

Ruby: class User; end
来源：http://dali.yj202588.top/Article/details/gtzxopgpyg.html

C#:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gtqwnwtqil.html

[G02] 构造函数
来源：http://dali.yongpay.top/Article/details/gtzseubply.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhengqikj.top/Article/details/gtsbbfgqdb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gogol.net.cn/Article/details/gtffiztbct.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtpzbhcfid.html

TS:   constructor(public name: string) {}
来源：http://dali.ybcxt.top/Article/details/gthueieyqq.html

Java: User(String name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtimyhautb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.dianchejie.cn/Article/details/gtvrundezz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhengqikj.top/Article/details/gtajhvflhi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtwmqkilbo.html

[G03] 实例属性
来源：http://dali.kuanghao11.cn/Article/details/gtllnmksmu.html

Py:   self.name = "x"
来源：http://dali.daxiang520.top/Article/details/gtunlkxxfd.html

PHP:  public string $name = "x";
来源：http://dali.chenzaomai.com/Article/details/gtqhngmtoh.html

JS:   this.name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtuhawtssp.html

TS:   name: string = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtmgbuztgc.html

Java: private String name;
来源：http://dali.haohaochexian.top/Article/details/gthaztsgzc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.andypj.xyz/Article/details/gtowuhnbfi.html

Ruby: @name = "x"
来源：http://dali.fengsongda.top/Article/details/gthubjvsji.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuanzhike.top/Article/details/gtqhrfmxsk.html

[G04] 定义方法
来源：http://dali.yongpay.top/Article/details/gtafkxvsck.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gtgdgtiehc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtxhjodjwt.html

JS:   greet() { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtmftkpbsh.html

TS:   greet(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtwslapcuk.html

Java: String greet() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtjpoqiycb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gtyhswwjqy.html

Ruby: def greet; @name; end
来源：http://dali.nanxinkj.top/Article/details/gtrweracck.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiezbdstj.html

[G05] 继承
来源：http://dali.xinyue.icu/Article/details/gtukdahycw.html

Py:   class Admin(User): pass
来源：http://dali.yvedp.cn/Article/details/gtdxoyjdtq.html

PHP:  class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtzzivtrhh.html

JS:   class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtfanmenae.html

TS:   class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtyfhwsalo.html

Java: class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtsnmggyxo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xinyue.icu/Article/details/gtrozymbmx.html

Ruby: class Admin < User; end
来源：http://dali.fzhhl.top/Article/details/gtokpnegix.html

C#:   class Admin : User {}
来源：http://dali.jianghu66.top/Article/details/gtakspjgxj.html

[G06] 重写方法
来源：http://dali.ivvv.top/Article/details/gtjvrhkcfn.html

Py:   def greet(self): return "admin"
来源：http://dali.cdnleiting.top/Article/details/gtqvjnfzss.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gtxjulratx.html

JS:   greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtcgngookh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtmlytxknt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gtdvkrggwo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ydzc1.top/Article/details/gtwbmjccic.html

Ruby: def greet; "admin"; end
来源：http://dali.ydzc1.top/Article/details/gtgnsteate.html

C#:   public override string Greet() => "admin";
来源：http://dali.ydzc1.top/Article/details/gtubdqsyiq.html

[G07] 调用父类方法
来源：http://dali.sxryk.cn/Article/details/gtszzzhzpu.html

Py:   super().greet()
来源：http://dali.yonumen.top/Article/details/gtxaridjnm.html

PHP:  parent::greet();
来源：http://dali.yj20258.top/Article/details/gtrgxjtpek.html

JS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtjyianlps.html

TS:   super.greet();
来源：http://dali.jqgfzy.top/Article/details/gtuypaatqa.html

Java: super.greet();
来源：http://dali.meibo888.top/Article/details/gtombsndbt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinghuilouyu.cn/Article/details/gthoadvwxs.html

Ruby: super
来源：http://dali.chenzaomai.com/Article/details/gtcihglfrd.html

C#:   base.Greet();
来源：http://dali.jlsjyb.cn/Article/details/gtkkstftwp.html

[G08] 静态方法与属性
来源：http://dali.shuidangran.top/Article/details/gtndyjxcay.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xziqi.cn/Article/details/gtwnvlflqs.html

PHP:  public static function f() {}
来源：http://dali.tian-w.cn/Article/details/gtrxllcgil.html

JS:   static f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtylrwplrn.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuedzgfky.html

Java: static void f() {}
来源：http://dali.pycfn.com/Article/details/gtsxwrknqb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xinyue.icu/Article/details/gtgnwyblpc.html

Ruby: def self.f; end
来源：http://dali.ppjwa.cn/Article/details/gtvxxmwjbz.html

C#:   public static void F() {}
来源：http://dali.cqqwz.cn/Article/details/gtfkflbuvx.html

[G09] 接口 / 抽象类
来源：http://dali.yanxiufei.cn/Article/details/gtrflhrtwh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hywenlv.cn/Article/details/gtztqekjlb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.vqdsnc.cn/Article/details/gtmvwykyel.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xylfe.cn/Article/details/gtoocpslbt.html

TS:   interface Shape { area(): number; }
来源：http://dali.mhx1999.top/Article/details/gtllrnufxh.html

Java: interface Shape { double area(); }
来源：http://dali.yvedp.cn/Article/details/gtscjribvq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.mhx1999.top/Article/details/gtixhmgols.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yangfankeji.com/Article/details/gtbpcmlgne.html

C#:   interface IShape { double Area(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtewpysyvx.html

[G10] 访问控制
来源：http://dali.sweek.top/Article/details/gttcsaxlzn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhongyouzk.top/Article/details/gtngmxlrpv.html

PHP:  public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtfznvernc.html

JS:   #private 字段；其余公开
来源：http://dali.zhiwuduotai.top/Article/details/gtdrbpoqlc.html

TS:   public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gtdznmksrq.html

Java: public / protected / private / 默认包级
来源：http://dali.cheryme.top/Article/details/gthyfkymzt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xylfe.cn/Article/details/gtqkjzwdcw.html

Ruby: public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtsrukyszf.html

C#:   public / protected / private / internal
来源：http://dali.ivvv.top/Article/details/gtzcjojxno.html

[G11] getter / setter
来源：http://dali.xuetiantiany.cn/Article/details/gtqsouogvc.html

Py:   @property 与 @x.setter
来源：http://dali.svipenyu.cn/Article/details/gtccxcsjtn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gtnmfmrfvw.html

JS:   get name() { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gtvbqeolib.html

TS:   get name(): string { return this._name; }
来源：http://dali.xylfe.cn/Article/details/gttubrgzrm.html

Java: public String getName() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtrhvrgqdj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtrmgwvsso.html

Ruby: attr_accessor :name
来源：http://dali.aizwys.cn/Article/details/gtcsujrflo.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gttzcoltsm.html

[G12] 对象转字符串
来源：http://dali.zhongyouzk.top/Article/details/gtcudzpexn.html

Py:   def __str__(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gtxfthrdpx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtkqohjqst.html

JS:   toString() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtjuhvsufr.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtlzxypelt.html

Java: @Override public String toString() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtktdbzgya.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtwghetzyz.html

Ruby: def to_s; @name; end
来源：http://dali.yuxming.cn/Article/details/gtcbfveovr.html

C#:   public override string ToString() => Name;
来源：http://dali.quarkkingdee.top/Article/details/gtikrqczpa.html

[G13] 判断对象类型
来源：http://dali.chenlongwang.top/Article/details/gtzmatfusc.html

Py:   isinstance(u, User)
来源：http://dali.zhengqikj.top/Article/details/gtabzzalia.html

PHP:  $u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtjpaidlec.html

JS:   u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtecuhmept.html

TS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtwnwztzti.html

Java: u instanceof User
来源：http://dali.yj20258.top/Article/details/gtxxjzamyk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.snrcjt.cn/Article/details/gtckktqkuo.html

Ruby: u.is_a?(User)
来源：http://dali.jlsjyb.cn/Article/details/gtyvvynrns.html

C#:   u is User
来源：http://dali.yuanzhike.top/Article/details/gtphdxqfkz.html

[G14] 数据类 / record
来源：http://dali.pycfn.com/Article/details/gtnaowuitp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dashuyun.cn/Article/details/gtycthymtx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.kuanghao11.cn/Article/details/gtebkbhyjr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.meibo888.top/Article/details/gtlxphfcsq.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gththzptwn.html

Java: record User(String name, int age) {}
来源：http://dali.jiagoushi.top/Article/details/gtocvlqdnc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aizwys.cn/Article/details/gtzifajpjd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cashguo.top/Article/details/gtvxcbsled.html

C#:   record User(string Name, int Age);
来源：http://dali.feifeiyinyue.top/Article/details/gtucahnrxk.html

[G15] 枚举
来源：http://dali.yanxiufei.cn/Article/details/gtazkrdykn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jyoumei.cn/Article/details/gtomvgcfyt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.bjfxy.top/Article/details/gtfpysvosn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenzaomai.com/Article/details/gtemvnggah.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.0kj1m.cn/Article/details/gtgmohufjs.html

Java: enum Color { RED, GREEN }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlfigexl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhaomingkeji.xyz/Article/details/gticzwkegv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hongshengwenyu.top/Article/details/gtqdqxjxph.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258.top/Article/details/gtjcanjsev.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgfzy.top/Article/details/gtdawrfnfj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gtwwyccjgm.html

PHP:  get_object_vars($obj);
来源：http://dali.jiagoushi.top/Article/details/gtdufstyet.html

JS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gtmukocxzc.html

TS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkznbdhsj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhixingplan.top/Article/details/gtycdnwusd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.svipenyu.cn/Article/details/gtbxkknuio.html

Ruby: obj.instance_variables
来源：http://dali.yongpay.top/Article/details/gtuwluyhaw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tian-w.cn/Article/details/gtaqsaafrh.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpomjngi.html

H. 异常与错误处理
来源：http://dali.sxryk.cn/Article/details/gtrljjceey.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtepndbcxp.html

[H01] try / catch 基础
来源：http://dali.hongshengwenyu.top/Article/details/gtdldanwkg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xziqi.cn/Article/details/gtqborpokg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.birdmap.top/Article/details/gtelcodsvo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.quarkkingdee.top/Article/details/gtlsuptylh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gtbvwjhskn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ivvv.top/Article/details/gtvpqlejlv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yongpay.top/Article/details/gtmnbplbto.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.mhx1999.top/Article/details/gtpxtchcas.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.bjfxy.top/Article/details/gtwzsnwcrf.html

[H02] finally / ensure 收尾
来源：http://dali.chenjidiqi.icu/Article/details/gtuguwtdjj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenlongwang.top/Article/details/gtsnzwfyjm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtgmwiyovh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtynnibooa.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtkkhjqlfn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtkxniekcf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhengqikj.top/Article/details/gtpylgrgiy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gtuzdmhjcq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtxzkpaevr.html

[H03] 主动抛出异常
来源：http://dali.xinyue.icu/Article/details/gtpqocolzz.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnxiangtu.top/Article/details/gtrubtjtfm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtdyetlmfd.html

JS:   throw new Error("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtgwcgcgkd.html

TS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtzrzwhrng.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtykyobbdc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj202588.top/Article/details/gtuzqdxsau.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jqgufenzy.top/Article/details/gtbchotyfv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtmzegklum.html

[H04] 自定义异常类型
来源：http://dali.yonumen.top/Article/details/gtjujwtaki.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxuanxn.top/Article/details/gtwfynbauw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shzxlz.cn/Article/details/gtxxrmucvm.html

JS:   class MyError extends Error {}
来源：http://dali.shangyingyoupin.top/Article/details/gtnasvgaos.html

TS:   class MyError extends Error {}
来源：http://dali.haohaochexian.top/Article/details/gtlatanupi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gtaymcxdtq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yongpay.top/Article/details/gtoeaxeglg.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigfzy.top/Article/details/gtlqzvabio.html

C#:   class MyException : Exception {}
来源：http://dali.tian-w.cn/Article/details/gtwjzjupqa.html

[H05] 捕获特定类型
来源：http://dali.yangfankeji.com/Article/details/gtqmnekzlh.html

Py:   except ValueError as e:
来源：http://dali.yangfankeji.com/Article/details/gtfugfwqge.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gtweonjwxu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ybcxt.top/Article/details/gtufrcgvst.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gtbrrmvanq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhengqikj.top/Article/details/gtgawpwwkd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jyoumei.cn/Article/details/gtroqecszn.html

Ruby: rescue ArgumentError => e
来源：http://dali.gzhubu.top/Article/details/gtoscfoida.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.svipenyu.cn/Article/details/gtprwbzauo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yanxiufei.cn/Article/details/gtkzrpbfrc.html

Py:   value = d.get("k") or default
来源：http://dali.daria6918.cn/Article/details/gtamwkqqmg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xziqi.cn/Article/details/gtwnqpysco.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gtjfmfmbjr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtwkxnhvpd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gotoacloud.top/Article/details/gtxllfqqyx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntordsaq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtttmreele.html

C#:   obj?.A?.B ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gtkqllnipk.html

[H07] 断言
来源：http://dali.hnxiangtu.top/Article/details/gteuohrbel.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxinkj.top/Article/details/gtopjfcbuo.html

PHP:  assert($x > 0);
来源：http://dali.316326.xyz/Article/details/gtyttbradm.html

JS:   console.assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gtjianreyg.html

TS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtsbliofnh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gzhubu.top/Article/details/gtpelasrzx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tianlin.xyz/Article/details/gtxdawbgdm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sweek.top/Article/details/gtqhvkzvbs.html

C#:   Debug.Assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtzjyonzdh.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj202588.top/Article/details/gtdxhghwbf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cdnleiting.top/Article/details/gtpjqfmffh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhongyouzk.top/Article/details/gtilpdpgbw.html

JS:   e.message;  e.stack
来源：http://dali.chenzaomai.com/Article/details/gtmmhgtxvn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhengqikj.top/Article/details/gtkmqnfjxg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.aizwys.cn/Article/details/gtmhlhavop.html

Go:   err.Error()
来源：http://dali.jiagoushi.top/Article/details/gtowuwupgz.html

Ruby: e.message;  e.backtrace
来源：http://dali.quarkkingdee.top/Article/details/gtwusojfht.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhixingplan.top/Article/details/gtwnufsjfb.html

[H09] 带错误码的异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbcyhqjjv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pengpengdd.cyou/Article/details/gtwesvggfu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.havefunace.top/Article/details/gtrfxkwjiy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daria6918.cn/Article/details/gtmxklrpej.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.pengpengdd.cyou/Article/details/gtobeiiqnr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhixingplan.top/Article/details/gtvjygtszh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.svipenyu.cn/Article/details/gtgimpwtfu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tianlin.xyz/Article/details/gtgflewcxj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tian-w.cn/Article/details/gtdyglxbjb.html

[H10] 资源自动释放
来源：http://dali.aibaodan.cn/Article/details/gtphlkoeir.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yongpay.top/Article/details/gtflmcjifm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.aizwys.cn/Article/details/gtwlkyecci.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gtkrdmgtaz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.haohaochexian.top/Article/details/gtdshlkime.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pycfn.com/Article/details/gtlmufrhjw.html

Go:   defer f.Close()
来源：http://dali.nanxinkj.top/Article/details/gtjqubzrll.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shuidangran.top/Article/details/gtwwdexqjf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtqmhmkakn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtycjzazqo.html

I. 正则表达式
来源：http://dali.guannengcc.top/Article/details/gtlbgbpjhg.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtbyguplft.html

[I01] 判断是否匹配
来源：http://dali.jinqigfzy.top/Article/details/gtppligszu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hfpthk.cn/Article/details/gtpzkgzdet.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.dianchejie.cn/Article/details/gtfyywmrns.html

JS:   /\d+/.test(s)
来源：http://dali.bjfxy.top/Article/details/gtxsplgprx.html

TS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gtlvbluzhl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.aibaodan.cn/Article/details/gtymcwogmx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yongpay.top/Article/details/gtpjrypvyt.html

Ruby: s.match?(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gttdhqljpu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.andypj.xyz/Article/details/gtixkjfeks.html

[I02] 提取所有匹配
来源：http://dali.smart0.xyz/Article/details/gtfmsfseel.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yongpay.top/Article/details/gtwtmwknai.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dashuyun.cn/Article/details/gtnhbvtdrx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cheryme.top/Article/details/gtpclkwgwz.html

TS:   s.match(/\d+/g)
来源：http://dali.yj202588.top/Article/details/gtgrhagmyv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhongyouzk.top/Article/details/gteysrxwbt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gtkisrdqct.html

Ruby: s.scan(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gtypbirgzj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtgwrkaxvr.html

[I03] 提取捕获分组
来源：http://dali.yonumen.top/Article/details/gtmghahpsu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cqqwz.cn/Article/details/gtoxkoajlb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jlsjyb.cn/Article/details/gtlktixwxq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.snrcjt.cn/Article/details/gtyitrclmp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.guowangkeji.top/Article/details/gtasawefgp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xziqi.cn/Article/details/gtmvxxjbhh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shzxlz.cn/Article/details/gtwpollsod.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cqqwz.cn/Article/details/gtgvtezyyc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj20258.top/Article/details/gtkpbxpjct.html

[I04] 正则替换
来源：http://dali.yj202588.top/Article/details/gthqjcycaf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.meibo888.top/Article/details/gtefdgqdek.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.aizwys.cn/Article/details/gtjeufkjuf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gteghrggij.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xylfe.cn/Article/details/gtoluzovmg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cqqwz.cn/Article/details/gtsnurqtqm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cheryme.top/Article/details/gtnnjjkegb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdpyndbk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtlmhwlvph.html

[I05] 按正则拆分
来源：http://dali.xinyue.icu/Article/details/gtcrtfjdfa.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gotoacloud.top/Article/details/gtimqojavw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtqghrcmds.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gtwlmiwled.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gtirwapuam.html

Java: s.split("\\s*,\\s*")
来源：http://dali.iojbl.cn/Article/details/gtswjerkzq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.316326.xyz/Article/details/gthwummncc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtmrjyjtes.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinghuilouyu.cn/Article/details/gttosqfiav.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hysaishi.cn/Article/details/gtbzmqowof.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gtjgksfjdt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.wangdashe.top/Article/details/gtlfzurqkk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ydzc1.top/Article/details/gtfcnwsqxv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinghuilouyu.cn/Article/details/gtmynaoonh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gttkucgoux.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yangfankeji.com/Article/details/gtwtsrpoye.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jyoumei.cn/Article/details/gtczmzuilj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gtuxmyvoeq.html

[I07] 忽略大小写与多行模式
来源：http://dali.dashuyun.cn/Article/details/gtuhbgspli.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhiwuduotai.top/Article/details/gtwuueosab.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hfpthk.cn/Article/details/gtidjrrnml.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cdnleiting.top/Article/details/gtpyvkyysw.html

TS:   /error/gim
来源：http://dali.dashuyun.cn/Article/details/gtizqbzobi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ehwqpu.com/Article/details/gtthgiivzn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenzaomai.com/Article/details/gtxgrdwpds.html

Ruby: s.scan(/error/i)
来源：http://dali.fengsongda.top/Article/details/gtvsfojxuk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sysykeji.top/Article/details/gtxoxklkrc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jlsjyb.cn/Article/details/gtuwqagjbj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.redwolf501.top/Article/details/gtsxuwolcq.html


<!-- 参考信息 -->