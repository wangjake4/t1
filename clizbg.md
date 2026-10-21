代发 wailian999

TS:   constructor(public name: string) {}
来源：http://dali.yuxming.cn/Article/details/gtsbeldbaa.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gtisygogyz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.kuanghao11.cn/Article/details/gttaqaqbkv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.smart0.xyz/Article/details/gtdmvadccc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtvgyschqz.html

[G03] 实例属性
来源：http://dali.sxryk.cn/Article/details/gtpcbnyixp.html

Py:   self.name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gtbekijmmr.html

PHP:  public string $name = "x";
来源：http://dali.yuanzhike.top/Article/details/gtuyrgalxl.html

JS:   this.name = "x";
来源：http://dali.daria6918.cn/Article/details/gtslaizzyw.html

TS:   name: string = "x";
来源：http://dali.zdqjudy.top/Article/details/gtaiinuoja.html

Java: private String name;
来源：http://dali.andypj.xyz/Article/details/gtzggrnnfe.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aibaodan.cn/Article/details/gtaxdcuyjo.html

Ruby: @name = "x"
来源：http://dali.nwbrower.top/Article/details/gtnuiwvwln.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jianghu66.top/Article/details/gtuzulsnec.html

[G04] 定义方法
来源：http://dali.yueranfly.top/Article/details/gtoynurius.html

Py:   def greet(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gtftlovnmc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtfxjcvgfy.html

JS:   greet() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtrtmoxalv.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtxobukkar.html

Java: String greet() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtlndzggla.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtbnrrvxzy.html

Ruby: def greet; @name; end
来源：http://dali.guannengcc.top/Article/details/gtbeqmmdau.html

C#:   public string Greet() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gtdjnyzmwi.html

[G05] 继承
来源：http://dali.ydzc1.top/Article/details/gtkiiqlcgs.html

Py:   class Admin(User): pass
来源：http://dali.shzxlz.cn/Article/details/gtsifbwjng.html

PHP:  class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtmsyvvqez.html

JS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtxfexezot.html

TS:   class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtkwshtzvz.html

Java: class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtbiqqilhh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.9152youxi.cn/Article/details/gtsjmbjyfv.html

Ruby: class Admin < User; end
来源：http://dali.zhengqikj.top/Article/details/gtpbxfxhwj.html

C#:   class Admin : User {}
来源：http://dali.chenlongwang.top/Article/details/gtkbkihpun.html

[G06] 重写方法
来源：http://dali.daria6918.cn/Article/details/gtsvwuciqp.html

Py:   def greet(self): return "admin"
来源：http://dali.gzhubu.top/Article/details/gtubnmgjcb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gttsseaere.html

JS:   greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtcyihpqyo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtytknfgpx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtadumozav.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tian-w.cn/Article/details/gtkyuhdpqi.html

Ruby: def greet; "admin"; end
来源：http://dali.yj202588.top/Article/details/gtxtgroafz.html

C#:   public override string Greet() => "admin";
来源：http://dali.ppjwa.cn/Article/details/gtipmoccra.html

[G07] 调用父类方法
来源：http://dali.jinqigfzy.top/Article/details/gtbqixwuoo.html

Py:   super().greet()
来源：http://dali.gogol.net.cn/Article/details/gtyrecpyge.html

PHP:  parent::greet();
来源：http://dali.hfpthk.cn/Article/details/gtdznqjfoc.html

JS:   super.greet();
来源：http://dali.andypj.xyz/Article/details/gtbpfdjuql.html

TS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gtjaaakrfb.html

Java: super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtvobbduuu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shuidangran.top/Article/details/gtecjdxgwh.html

Ruby: super
来源：http://dali.ehwqpu.com/Article/details/gtgedcohlo.html

C#:   base.Greet();
来源：http://dali.mhx1999.top/Article/details/gtsncxqrvh.html

[G08] 静态方法与属性
来源：http://dali.sysykeji.top/Article/details/gtvnoewiym.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sxryk.cn/Article/details/gtgynqzdxc.html

PHP:  public static function f() {}
来源：http://dali.birdmap.top/Article/details/gtjxeijnyz.html

JS:   static f() {}
来源：http://dali.guowangkeji.top/Article/details/gthqddnsjn.html

TS:   static f(): void {}
来源：http://dali.hysaishi.cn/Article/details/gteylnmmus.html

Java: static void f() {}
来源：http://dali.316326.xyz/Article/details/gtzklnfyfh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fengsongda.top/Article/details/gthrbzoxfb.html

Ruby: def self.f; end
来源：http://dali.iojbl.cn/Article/details/gtzuggqjqm.html

C#:   public static void F() {}
来源：http://dali.zycfv.cn/Article/details/gtqxxoxvqx.html

[G09] 接口 / 抽象类
来源：http://dali.havefunace.top/Article/details/gtqzclazww.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinghuilouyu.cn/Article/details/gttagcytqg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqizbaexe.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guowangkeji.top/Article/details/gtivlzaogc.html

TS:   interface Shape { area(): number; }
来源：http://dali.aibaodan.cn/Article/details/gtvzhwowek.html

Java: interface Shape { double area(); }
来源：http://dali.xuanzx.com/Article/details/gtlnblanxl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gotoacloud.top/Article/details/gtoyaszfyv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.birdmap.top/Article/details/gtozkvixia.html

C#:   interface IShape { double Area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtufmvtrsv.html

[G10] 访问控制
来源：http://dali.feifeiyinyue.top/Article/details/gtlguatjrm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ybcxt.top/Article/details/gtedqwcund.html

PHP:  public / protected / private
来源：http://dali.yvedp.cn/Article/details/gtpgtplhqg.html

JS:   #private 字段；其余公开
来源：http://dali.316326.xyz/Article/details/gtrmexiuji.html

TS:   public / protected / private
来源：http://dali.yonumen.top/Article/details/gtgpyeokbb.html

Java: public / protected / private / 默认包级
来源：http://dali.zhoulong.xyz/Article/details/gtlswgogtc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yangfankeji.com/Article/details/gtwvbggvai.html

Ruby: public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gttqmhyntb.html

C#:   public / protected / private / internal
来源：http://dali.jinghuilouyu.cn/Article/details/gtrltdnadn.html

[G11] getter / setter
来源：http://dali.zhiwuduotai.top/Article/details/gtselijrwn.html

Py:   @property 与 @x.setter
来源：http://dali.dashuyun.cn/Article/details/gtgiugrarc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gtfqqmwwot.html

JS:   get name() { return this._name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtkdtrkron.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gtwmmvlgxs.html

Java: public String getName() { return name; }
来源：http://dali.sxryk.cn/Article/details/gtkltbdlxv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gtnraxwdiu.html

Ruby: attr_accessor :name
来源：http://dali.yanxiufei.cn/Article/details/gtddihqyen.html

C#:   public string Name { get; set; }
来源：http://dali.dashuyun.cn/Article/details/gtyyrowuhi.html

[G12] 对象转字符串
来源：http://dali.kuanghao11.cn/Article/details/gtvzaiokrj.html

Py:   def __str__(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gtqerpsafi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gtheajsadt.html

JS:   toString() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtecdwrtbw.html

TS:   toString(): string { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtgbeudvtd.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj20258.top/Article/details/gtxvvkegjq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtlabwkqrs.html

Ruby: def to_s; @name; end
来源：http://dali.yangfankeji.com/Article/details/gtoranjltz.html

C#:   public override string ToString() => Name;
来源：http://dali.smart0.xyz/Article/details/gtluckmlbe.html

[G13] 判断对象类型
来源：http://dali.ivvv.top/Article/details/gtcepjmyuh.html

Py:   isinstance(u, User)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtajflopef.html

PHP:  $u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtbvmooqlg.html

JS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtsvyiocub.html

TS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtpjrdxniq.html

Java: u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtboxhnjmd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jyoumei.cn/Article/details/gtllgajows.html

Ruby: u.is_a?(User)
来源：http://dali.cheryme.top/Article/details/gtmnfgxxpf.html

C#:   u is User
来源：http://dali.jinqigufen.top/Article/details/gtuiyybdor.html

[G14] 数据类 / record
来源：http://dali.tian-w.cn/Article/details/gtdbyirefk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jyoumei.cn/Article/details/gtjdpdfisi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yongpay.top/Article/details/gtnrznphdt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.feifeiyinyue.top/Article/details/gtwgynraha.html

TS:   type User = { name: string; age: number };
来源：http://dali.ehwqpu.com/Article/details/gtglyvdifm.html

Java: record User(String name, int age) {}
来源：http://dali.daria6918.cn/Article/details/gtputebhqx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yangfankeji.com/Article/details/gtimjtsvfa.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.feifeiyinyue.top/Article/details/gtuwxejldl.html

C#:   record User(string Name, int Age);
来源：http://dali.xinyue.icu/Article/details/gtwywmhlmr.html

[G15] 枚举
来源：http://dali.snrcjt.cn/Article/details/gtthzkrsgi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvgvjlutl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuanzx.com/Article/details/gthagjmjyx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daria6918.cn/Article/details/gtvbrjhloy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gtlvusdsbj.html

Java: enum Color { RED, GREEN }
来源：http://dali.xuetiantiany.cn/Article/details/gtwzgcazcl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dashuyun.cn/Article/details/gtppvklnbq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shuidangran.top/Article/details/gtwquhxzsf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yonumen.top/Article/details/gtpuszkutj.html

[G16] 对象转数组 / 字典
来源：http://dali.sweek.top/Article/details/gtohcjaivo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ybcxt.top/Article/details/gtoujgpfjt.html

PHP:  get_object_vars($obj);
来源：http://dali.9152youxi.cn/Article/details/gtuwrfunxw.html

JS:   Object.entries(obj)
来源：http://dali.tanke756.top/Article/details/gtgcdjgzdc.html

TS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtiunomlgp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.quarkkingdee.top/Article/details/gtidmskzur.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jyoumei.cn/Article/details/gttufplidp.html

Ruby: obj.instance_variables
来源：http://dali.xylfe.cn/Article/details/gtvxyxzavp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gtazajequt.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gthxtjfvnw.html

H. 异常与错误处理
来源：http://dali.tian-w.cn/Article/details/gtboirfsvz.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtbidxdmrw.html

[H01] try / catch 基础
来源：http://dali.svipenyu.cn/Article/details/gtjxascjtu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sweek.top/Article/details/gtwrxejsth.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxinkj.top/Article/details/gtqkuzsqvu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gtxvxqeykm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gtpcibtwmx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.c1oappe.top/Article/details/gtdrlkoaut.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aizwys.cn/Article/details/gttvlgkcmp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xziqi.cn/Article/details/gtzagzvbkg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cashguo.top/Article/details/gtjhhjsldp.html

[H02] finally / ensure 收尾
来源：http://dali.yvedp.cn/Article/details/gtqhsjhxlj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dashuyun.cn/Article/details/gtdmhalgxs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtdltrvubk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtfvebarlt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gttupkjdrl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtggttyjfm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.aibaodan.cn/Article/details/gtifnbrryi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hfpthk.cn/Article/details/gtcoqaqwpm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtkkygfscn.html

[H03] 主动抛出异常
来源：http://dali.hywenlv.cn/Article/details/gttfsiaqed.html

Py:   raise ValueError("错误信息")
来源：http://dali.guowangkeji.top/Article/details/gtqqihbrha.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtgmxfarjj.html

JS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfreoywz.html

TS:   throw new Error("错误信息");
来源：http://dali.aizwys.cn/Article/details/gttqnebhaj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtfivjxhsv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnxiangtu.top/Article/details/gtpktzclkp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daxiang520.top/Article/details/gtfviauzul.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gthjuhxbcm.html

[H04] 自定义异常类型
来源：http://dali.hnqzz.top/Article/details/gtdhpvbkqw.html

Py:   class MyError(Exception): pass
来源：http://dali.xinyue.icu/Article/details/gtjuzackcd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hnxiangtu.top/Article/details/gtjcnmcuhc.html

JS:   class MyError extends Error {}
来源：http://dali.havefunace.top/Article/details/gtbhixgdqt.html

TS:   class MyError extends Error {}
来源：http://dali.aibaodan.cn/Article/details/gtywwtwmhz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shangyingyoupin.top/Article/details/gtmhgkusgn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gotoacloud.top/Article/details/gtpkajjxvr.html

Ruby: class MyError < StandardError; end
来源：http://dali.yongpay.top/Article/details/gtioralkwd.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gtnuljjqgd.html

[H05] 捕获特定类型
来源：http://dali.sxryk.cn/Article/details/gtvuuprwpb.html

Py:   except ValueError as e:
来源：http://dali.jianghu66.top/Article/details/gtxvbabmev.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hysaishi.cn/Article/details/gtinggerar.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gthuodcncj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gtjaepingx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aizwys.cn/Article/details/gtageqtucg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuiflpmzz.html

Ruby: rescue ArgumentError => e
来源：http://dali.meibo888.top/Article/details/gtmcvuhnvb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yangfankeji.com/Article/details/gtuucsbieo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cashguo.top/Article/details/gtnwjrcugy.html

Py:   value = d.get("k") or default
来源：http://dali.ydzc1.top/Article/details/gtarbzlxtn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jyoumei.cn/Article/details/gtafxhwvhg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ehwqpu.com/Article/details/gtgcbrzbam.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzvdjzen.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tanke756.top/Article/details/gtruykniuw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hammf.cn/Article/details/gtfmboyyyq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuetiantiany.cn/Article/details/gtubbwmakp.html

C#:   obj?.A?.B ?? default
来源：http://dali.shuidangran.top/Article/details/gtlkrvatsj.html

[H07] 断言
来源：http://dali.yvedp.cn/Article/details/gtyfiixtci.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zycfv.cn/Article/details/gtjwplkhta.html

PHP:  assert($x > 0);
来源：http://dali.yj202588.top/Article/details/gtnviokwnm.html

JS:   console.assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gtbzzldayh.html

TS:   console.assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtfvycrqkz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigfzy.top/Article/details/gtwhiwyxem.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ybcxt.top/Article/details/gtorvoaaot.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yanxiufei.cn/Article/details/gtvnfxlggr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gthdakevas.html

[H08] 获取错误信息与堆栈
来源：http://dali.hywenlv.cn/Article/details/gtpflppfzo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guannengcc.top/Article/details/gtfttiwtrw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shangyingyoupin.top/Article/details/gtmvnpglhc.html

JS:   e.message;  e.stack
来源：http://dali.aizwys.cn/Article/details/gtdlitgydv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxzjrbrmx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yueranfly.top/Article/details/gtqbspebiw.html

Go:   err.Error()
来源：http://dali.yuxming.cn/Article/details/gtzqiyxxpk.html

Ruby: e.message;  e.backtrace
来源：http://dali.zdqjudy.top/Article/details/gtdtcerlow.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hfpthk.cn/Article/details/gtlgzfxvmu.html

[H09] 带错误码的异常
来源：http://dali.redwolf501.top/Article/details/gtwlffzpjc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yangfankeji.com/Article/details/gtbkvehasd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nanxuanxn.top/Article/details/gtegqcyrsj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.havefunace.top/Article/details/gtdnotjsiq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cdnleiting.top/Article/details/gtiutdytfb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhixingplan.top/Article/details/gtjrjvybjr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.pycfn.com/Article/details/gtfkolurlm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.9152youxi.cn/Article/details/gtutkvvxca.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sweek.top/Article/details/gtvdwyulrd.html

[H10] 资源自动释放
来源：http://dali.9152youxi.cn/Article/details/gtqgwdftnk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.guowangkeji.top/Article/details/gtzokmgfpx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ybcxt.top/Article/details/gtayrllvpg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yangfankeji.com/Article/details/gtztlkmkqq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gtusoppuut.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.andypj.xyz/Article/details/gthckhkokn.html

Go:   defer f.Close()
来源：http://dali.jiagoushi.top/Article/details/gtfaovnnxt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xylfe.cn/Article/details/gtgustemsp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gthqhcarqt.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtkgivetyu.html

I. 正则表达式
来源：http://dali.yj20258.top/Article/details/gtkfcfegou.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtihmnlxrz.html

[I01] 判断是否匹配
来源：http://dali.yonumen.top/Article/details/gtnapqojrs.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gtrofcxlgz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zdqjudy.top/Article/details/gtlxlfyook.html

JS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gttevukchl.html

TS:   /\d+/.test(s)
来源：http://dali.cdnleiting.top/Article/details/gtklhzecvm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgufenzy.top/Article/details/gtddlkiukq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.vqdsnc.cn/Article/details/gtgyhyqaps.html

Ruby: s.match?(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gtezfdukjd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcopjtpgd.html

[I02] 提取所有匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtbxkbochg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gtnfehpmzu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yonumen.top/Article/details/gtlpomgkrd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.kuanghao11.cn/Article/details/gtawkhuwcg.html

TS:   s.match(/\d+/g)
来源：http://dali.hnqzz.top/Article/details/gtioepgdib.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.redwolf501.top/Article/details/gtpkoufowb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.smart0.xyz/Article/details/gtvpmudlnk.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gtmttyvkyf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtgeqaplkl.html

[I03] 提取捕获分组
来源：http://dali.havefunace.top/Article/details/gthidmtjbi.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jlsjyb.cn/Article/details/gtpncbcbvn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ppjwa.cn/Article/details/gtvazdlmkh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nanxinkj.top/Article/details/gtvxslqcdl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhongyouzk.top/Article/details/gtopebzcbr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtanxvjuwk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.316326.xyz/Article/details/gtqjbbkgse.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gturvrsmmt.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.iojbl.cn/Article/details/gtbcaasucp.html

[I04] 正则替换
来源：http://dali.ydzc1.top/Article/details/gtsypmgdnm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj202588.top/Article/details/gtoyygqbcj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ybcxt.top/Article/details/gtwsyxtlxx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.316326.xyz/Article/details/gtjemtlkct.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hywenlv.cn/Article/details/gtgkaydxlk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.dashuyun.cn/Article/details/gtxkjygxcn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.9152youxi.cn/Article/details/gtxswdrget.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daxiang520.top/Article/details/gtblzxlfzz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtduhlrjoy.html

[I05] 按正则拆分
来源：http://dali.zhongyouzk.top/Article/details/gtnysobhuw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtckfgqgsa.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.andypj.xyz/Article/details/gtggaxjrej.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gtbovrzian.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gtahssvrpj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tianlin.xyz/Article/details/gtybvsfcly.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gtllfqaicb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gtocrwsaeg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.svipenyu.cn/Article/details/gtksqzgzhi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.iojbl.cn/Article/details/gtvuuklsih.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gtfbugsxvq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shuidangran.top/Article/details/gtnnmvmmyc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfuptjjh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gtoecniyrz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gtgpiezigb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shuidangran.top/Article/details/gtjsxhextn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.guowangkeji.top/Article/details/gtjfsjwrhp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gtegahcexk.html

[I07] 忽略大小写与多行模式
来源：http://dali.yongpay.top/Article/details/gtxpkhikrg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.redwolf501.top/Article/details/gtslyjkvbj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ivvv.top/Article/details/gtndhzxkcg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shangyingyoupin.top/Article/details/gtsofdpwux.html

TS:   /error/gim
来源：http://dali.hammf.cn/Article/details/gtwhvbreiw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hfpthk.cn/Article/details/gthtmuhvtl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gtiyabxijj.html

Ruby: s.scan(/error/i)
来源：http://dali.snrcjt.cn/Article/details/gtsusmczzq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sxryk.cn/Article/details/gtpffaerey.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cdnleiting.top/Article/details/gtizbhryra.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nwbrower.top/Article/details/gtbgzrtjoi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gtadtkhral.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gtjgilmdqi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fengsongda.top/Article/details/gtxxugnftv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jiagoushi.top/Article/details/gtlfmfsbkc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.redwolf501.top/Article/details/gtxuilzqpr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhixingplan.top/Article/details/gtnejwuxxx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ydzc1.top/Article/details/gttbhyucgj.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtgvomlxnf.html


<!-- 参考信息 -->