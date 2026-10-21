代发 wailian999

Py:   class User: pass
来源：http://dali.cashguo.top/Article/details/gtluxjweri.html

PHP:  class User {}
来源：http://dali.hfpthk.cn/Article/details/gttpnlojrt.html

JS:   class User {}
来源：http://dali.birdmap.top/Article/details/gtlzudxssa.html

TS:   class User { name: string = ""; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmvbbwtjo.html

Java: class User {}
来源：http://dali.iojbl.cn/Article/details/gttbpakugn.html

Go:   type User struct { Name string }
来源：http://dali.birdmap.top/Article/details/gtprnsjbwc.html

Ruby: class User; end
来源：http://dali.ydzc1.top/Article/details/gtyeeyfczp.html

C#:   class User {}
来源：http://dali.guannengcc.top/Article/details/gtbmmbzrxk.html

[G02] 构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtpojnymmg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gotoacloud.top/Article/details/gtfrtweoda.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.vqdsnc.cn/Article/details/gtnefhatqp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtwvnrbvrq.html

TS:   constructor(public name: string) {}
来源：http://dali.mhx1999.top/Article/details/gtvqebiilc.html

Java: User(String name) { this.name = name; }
来源：http://dali.jianghu66.top/Article/details/gtodggdvqo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guannengcc.top/Article/details/gtpzgcbdzy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenlongwang.top/Article/details/gtkktxvzxq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkpsnqqvf.html

[G03] 实例属性
来源：http://dali.zhixingplan.top/Article/details/gtkbqvepwn.html

Py:   self.name = "x"
来源：http://dali.pycfn.com/Article/details/gtznwkbxmg.html

PHP:  public string $name = "x";
来源：http://dali.9152youxi.cn/Article/details/gtroyrwoww.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gticfehjab.html

TS:   name: string = "x";
来源：http://dali.nwbrower.top/Article/details/gtrclocvka.html

Java: private String name;
来源：http://dali.yueranfly.top/Article/details/gtaabjvsae.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenjidiqi.icu/Article/details/gtthleizpq.html

Ruby: @name = "x"
来源：http://dali.yj202588.top/Article/details/gtqhymmkri.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtbhczdpuu.html

[G04] 定义方法
来源：http://dali.redwolf501.top/Article/details/gtwajjiijx.html

Py:   def greet(self): return self.name
来源：http://dali.vqdsnc.cn/Article/details/gtwkdcogha.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gteppuuzhg.html

JS:   greet() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gttmqlaecf.html

TS:   greet(): string { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtlzmlfvoo.html

Java: String greet() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtxcttibpl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtkbrjilhl.html

Ruby: def greet; @name; end
来源：http://dali.haohaochexian.top/Article/details/gttnaxpdvb.html

C#:   public string Greet() => Name;
来源：http://dali.andypj.xyz/Article/details/gtiqlprxci.html

[G05] 继承
来源：http://dali.cdnleiting.top/Article/details/gtbmqaikss.html

Py:   class Admin(User): pass
来源：http://dali.aizwys.cn/Article/details/gtajrhtqko.html

PHP:  class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtahvvjrht.html

JS:   class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtogaeqjbi.html

TS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtjopeiuro.html

Java: class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtresfctya.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sweek.top/Article/details/gtamoxonag.html

Ruby: class Admin < User; end
来源：http://dali.wangdashe.top/Article/details/gtxvlryonx.html

C#:   class Admin : User {}
来源：http://dali.daria6918.cn/Article/details/gtqwkwvoll.html

[G06] 重写方法
来源：http://dali.meibo888.top/Article/details/gtfdrdmvvf.html

Py:   def greet(self): return "admin"
来源：http://dali.guannengcc.top/Article/details/gteimllanf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtosbkfkoy.html

JS:   greet() { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtelzghhew.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gtdgfqndwh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtgqxefyme.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shanyushiyangtech.top/Article/details/gtmkyefohw.html

Ruby: def greet; "admin"; end
来源：http://dali.mhx1999.top/Article/details/gtqtuvwcjr.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnqzz.top/Article/details/gtzdmedxdw.html

[G07] 调用父类方法
来源：http://dali.sufxvd.cn/Article/details/gtunzbitww.html

Py:   super().greet()
来源：http://dali.ydzc1.top/Article/details/gtznczyizr.html

PHP:  parent::greet();
来源：http://dali.snrcjt.cn/Article/details/gtfhbnmvro.html

JS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtlcstgtje.html

TS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtuuhkelnl.html

Java: super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtmbnzivxq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenlongwang.top/Article/details/gtbfuuepyp.html

Ruby: super
来源：http://dali.dianchejie.cn/Article/details/gtsrvzwieg.html

C#:   base.Greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtalkjabio.html

[G08] 静态方法与属性
来源：http://dali.iojbl.cn/Article/details/gtzjqxjbdg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuanzx.com/Article/details/gtohuecipl.html

PHP:  public static function f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtnhpgniqp.html

JS:   static f() {}
来源：http://dali.jyoumei.cn/Article/details/gtrshdclwf.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtmrrtso.html

Java: static void f() {}
来源：http://dali.jinqigufen.top/Article/details/gtfsncnkqd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hongshengwenyu.top/Article/details/gtqxgkcela.html

Ruby: def self.f; end
来源：http://dali.zycfv.cn/Article/details/gttojwhoux.html

C#:   public static void F() {}
来源：http://dali.sysykeji.top/Article/details/gthdifmwew.html

[G09] 接口 / 抽象类
来源：http://dali.dianchejie.cn/Article/details/gtivmsszrf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkfbpyegh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hammf.cn/Article/details/gtioplkomt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.c1oappe.top/Article/details/gtnfaromiw.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258888.top/Article/details/gtcrtucbte.html

Java: interface Shape { double area(); }
来源：http://dali.wangdashe.top/Article/details/gtlkoyjpkv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zycfv.cn/Article/details/gtjmfacagz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yuanzhike.top/Article/details/gtfwlxyvgs.html

C#:   interface IShape { double Area(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtipllmcif.html

[G10] 访问控制
来源：http://dali.hnqzz.top/Article/details/gtygtjqzdu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.quarkkingdee.top/Article/details/gtnexkuryc.html

PHP:  public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtummndbtb.html

JS:   #private 字段；其余公开
来源：http://dali.tian-w.cn/Article/details/gtacshhljv.html

TS:   public / protected / private
来源：http://dali.meibo888.top/Article/details/gtzphxapjg.html

Java: public / protected / private / 默认包级
来源：http://dali.birdmap.top/Article/details/gtczifzrlw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.bjfxy.top/Article/details/gtqoqpuqrn.html

Ruby: public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gtnqpfbaed.html

C#:   public / protected / private / internal
来源：http://dali.yj202588.top/Article/details/gtcemgwpgi.html

[G11] getter / setter
来源：http://dali.haohaochexian.top/Article/details/gtzgiazsvb.html

Py:   @property 与 @x.setter
来源：http://dali.zdqjudy.top/Article/details/gtzyoovvop.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtqxkkwyda.html

JS:   get name() { return this._name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtrehmadme.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gthpkdnyas.html

Java: public String getName() { return name; }
来源：http://dali.havefunace.top/Article/details/gtpjtkeqqn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gtjjfikxea.html

Ruby: attr_accessor :name
来源：http://dali.jqgfzy.top/Article/details/gtwakbtozw.html

C#:   public string Name { get; set; }
来源：http://dali.jianghu66.top/Article/details/gtasnoelfd.html

[G12] 对象转字符串
来源：http://dali.redwolf501.top/Article/details/gtyhuinwcb.html

Py:   def __str__(self): return self.name
来源：http://dali.yvedp.cn/Article/details/gthdxdxkdi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gtntkccocr.html

JS:   toString() { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtrtsgnouq.html

TS:   toString(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtkykanamh.html

Java: @Override public String toString() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtbyqmmlhx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtifnizkqp.html

Ruby: def to_s; @name; end
来源：http://dali.sufxvd.cn/Article/details/gtjifamiug.html

C#:   public override string ToString() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gtnhcluwyd.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtralkanxf.html

Py:   isinstance(u, User)
来源：http://dali.yvedp.cn/Article/details/gtkvkiffwh.html

PHP:  $u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gthexumafj.html

JS:   u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gtieacoyty.html

TS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gthfyslacp.html

Java: u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtjyspiyxa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.feifeiyinyue.top/Article/details/gtyleaotlt.html

Ruby: u.is_a?(User)
来源：http://dali.nwbrower.top/Article/details/gtmpufnlla.html

C#:   u is User
来源：http://dali.nwbrower.top/Article/details/gtgsqispxy.html

[G14] 数据类 / record
来源：http://dali.gotoacloud.top/Article/details/gtnlrwvlbn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gtzscjgcna.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.birdmap.top/Article/details/gtxhmhueuv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhixingplan.top/Article/details/gtziayybeh.html

TS:   type User = { name: string; age: number };
来源：http://dali.gogol.net.cn/Article/details/gtcoabpsip.html

Java: record User(String name, int age) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtrrcihpst.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nanxinkj.top/Article/details/gtclbydddw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xuanzx.com/Article/details/gtcbwutuub.html

C#:   record User(string Name, int Age);
来源：http://dali.svipenyu.cn/Article/details/gtinblaluv.html

[G15] 枚举
来源：http://dali.xziqi.cn/Article/details/gtuvmueont.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fzhhl.top/Article/details/gtuefwiavf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.redwolf501.top/Article/details/gtfemdozsf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jlsjyb.cn/Article/details/gtziwpqtgr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxwjbmgda.html

Java: enum Color { RED, GREEN }
来源：http://dali.hammf.cn/Article/details/gtvklljnjk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.meibo888.top/Article/details/gtbvlkkyzt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.daxiang520.top/Article/details/gtgbcpujxv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gtfpqruopf.html

[G16] 对象转数组 / 字典
来源：http://dali.guowangkeji.top/Article/details/gtcbvosvyb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.andypj.xyz/Article/details/gtpilfqqrq.html

PHP:  get_object_vars($obj);
来源：http://dali.sxryk.cn/Article/details/gtcthxrowd.html

JS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gtgkxpolhd.html

TS:   Object.entries(obj)
来源：http://dali.cucudq.cn/Article/details/gtbleuotwx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yanxiufei.cn/Article/details/gtzlcgouoy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ybcxt.top/Article/details/gtogwjztft.html

Ruby: obj.instance_variables
来源：http://dali.chenzaomai.com/Article/details/gtazlxpezi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gtmrkeqxga.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtanchsxkt.html

H. 异常与错误处理
来源：http://dali.jinghuilouyu.cn/Article/details/gthwigputd.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtfnbfptyh.html

[H01] try / catch 基础
来源：http://dali.zhoulong.xyz/Article/details/gtiqtoreoj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.daria6918.cn/Article/details/gtinelelat.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xinyue.icu/Article/details/gttshqhnpl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gtnwykhbxv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gttcyyfzkr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sxryk.cn/Article/details/gtvhclqpkp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ehwqpu.com/Article/details/gtngnwjqkh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.0kj1m.cn/Article/details/gtjczuaoxt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.fzhhl.top/Article/details/gtctdpgesk.html

[H02] finally / ensure 收尾
来源：http://dali.guowangkeji.top/Article/details/gtwsushfnn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.havefunace.top/Article/details/gtuuzgchcw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gttnrwemvr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtyovaqcqu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtyvmppcik.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtumzyneih.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnucdvob.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.havefunace.top/Article/details/gteeatibjw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtpwvhyoaz.html

[H03] 主动抛出异常
来源：http://dali.vqdsnc.cn/Article/details/gtfpkhhwxv.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhiwuduotai.top/Article/details/gtehanoshe.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gtcqibtpzw.html

JS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gttfsjpoaz.html

TS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtcxdaeimo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtyvxtykkm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcafmbsej.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jlsjyb.cn/Article/details/gtxgmafpuh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtwdexmvhk.html

[H04] 自定义异常类型
来源：http://dali.chenlongwang.top/Article/details/gtquogsbwv.html

Py:   class MyError(Exception): pass
来源：http://dali.iojbl.cn/Article/details/gtsiwddrza.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gtovgzodkl.html

JS:   class MyError extends Error {}
来源：http://dali.aizwys.cn/Article/details/gtdpstuvqg.html

TS:   class MyError extends Error {}
来源：http://dali.yvedp.cn/Article/details/gtbdlfdsny.html

Java: class MyException extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gtyqrvdoep.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnnnfvfv.html

Ruby: class MyError < StandardError; end
来源：http://dali.yangfankeji.com/Article/details/gtkdvikpnj.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigfzy.top/Article/details/gtwlkbpfbr.html

[H05] 捕获特定类型
来源：http://dali.bjfxy.top/Article/details/gtxniyvpto.html

Py:   except ValueError as e:
来源：http://dali.fengsongda.top/Article/details/gtievxrprg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zycfv.cn/Article/details/gtmomqckmb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.pycfn.com/Article/details/gtvmmdjttr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sysykeji.top/Article/details/gtzuushfhf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxemdgzb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xinyue.icu/Article/details/gtqmzheyrd.html

Ruby: rescue ArgumentError => e
来源：http://dali.daxiang520.top/Article/details/gtfnpqivfr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuanzhike.top/Article/details/gthjsykkdl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhixingplan.top/Article/details/gtyguqnyjz.html

Py:   value = d.get("k") or default
来源：http://dali.sweek.top/Article/details/gtouiaqqba.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yonumen.top/Article/details/gtbhtydjfx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gtezplbslh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gtijfhpmhd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxinkj.top/Article/details/gtbldsirfi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cucudq.cn/Article/details/gtwicxmrwg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zdqjudy.top/Article/details/gtubcuropj.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj20258888.top/Article/details/gturikllpx.html

[H07] 断言
来源：http://dali.pycfn.com/Article/details/gtgdxkmlsc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhiwuduotai.top/Article/details/gtavszbefy.html

PHP:  assert($x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtjoupntqy.html

JS:   console.assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gtvjjljzxq.html

TS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtrudqzwwo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.meibo888.top/Article/details/gtkeptmrae.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangshuangyany.cn/Article/details/gtnjbvungy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.daria6918.cn/Article/details/gtfuowbsmn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gtloymkklc.html

[H08] 获取错误信息与堆栈
来源：http://dali.nanxinkj.top/Article/details/gtbeleokqm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gtclhwcoqc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.bjfxy.top/Article/details/gttmxxlaah.html

JS:   e.message;  e.stack
来源：http://dali.yonumen.top/Article/details/gtvsfahcgi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenlongwang.top/Article/details/gthmmsjoic.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.mhx1999.top/Article/details/gtwzlrtdna.html

Go:   err.Error()
来源：http://dali.c1oappe.top/Article/details/gttsitgjug.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxefpqko.html

C#:   e.Message;  e.StackTrace
来源：http://dali.vqdsnc.cn/Article/details/gtlmznlrkt.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtamwctdfb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.redwolf501.top/Article/details/gtkudoxkap.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fengsongda.top/Article/details/gtcodqappf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xziqi.cn/Article/details/gtxjcusrka.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.9152youxi.cn/Article/details/gtifknwpdn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyuzbmzer.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jyoumei.cn/Article/details/gtqdtxtksw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hywenlv.cn/Article/details/gtcrwnxrlw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ehwqpu.com/Article/details/gtmuzimoog.html

[H10] 资源自动释放
来源：http://dali.yvedp.cn/Article/details/gtdlyimkcd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cdnleiting.top/Article/details/gteupiftub.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.c1oappe.top/Article/details/gtulxdedol.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqildenp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangshuangyany.cn/Article/details/gthsrsuciy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shuidangran.top/Article/details/gtdkpiuzvg.html

Go:   defer f.Close()
来源：http://dali.ppjwa.cn/Article/details/gtkbloraoa.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yvedp.cn/Article/details/gtxpwhudom.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.havefunace.top/Article/details/gtdkvakmiq.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtwekuweqh.html

I. 正则表达式
来源：http://dali.cheryme.top/Article/details/gtmrhaqequ.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtcyzzofvw.html

[I01] 判断是否匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtqewuwtdi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gthuvisqjc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zdqjudy.top/Article/details/gtyhpawjww.html

JS:   /\d+/.test(s)
来源：http://dali.ppjwa.cn/Article/details/gtnpkmfxsm.html

TS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gtchwfkaed.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sxryk.cn/Article/details/gtfqnxrfgz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvdtcmvp.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj20258888.top/Article/details/gthngdizeu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.feifeiyinyue.top/Article/details/gtuboamvaq.html

[I02] 提取所有匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtqssremoy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gtumbcatbv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xuetiantiany.cn/Article/details/gtxvlwvxvi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ydzc1.top/Article/details/gtyscividz.html

TS:   s.match(/\d+/g)
来源：http://dali.yj202588.top/Article/details/gtziapiesx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jqgufenzy.top/Article/details/gtmqcoruky.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gttkhmzhfi.html

Ruby: s.scan(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gtidruohrt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.pycfn.com/Article/details/gtsavzrdgx.html

[I03] 提取捕获分组
来源：http://dali.svipenyu.cn/Article/details/gtvjzapsim.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yuanzhike.top/Article/details/gtktzpafvb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtzegpxssz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tian-w.cn/Article/details/gtudgemidv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gotoacloud.top/Article/details/gtagpxuamd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cdnleiting.top/Article/details/gtjwbkuabc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xinyue.icu/Article/details/gtuxhnkquc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.guowangkeji.top/Article/details/gtnuchopkb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gtrlzwvdyv.html

[I04] 正则替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcftkwkdd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.guannengcc.top/Article/details/gtdfzauoba.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guowangkeji.top/Article/details/gtuagcswkt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhengqikj.top/Article/details/gtaiuajqlx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ehwqpu.com/Article/details/gtiifedewi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shzxlz.cn/Article/details/gtfhalfvwl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shzxlz.cn/Article/details/gtvwpugbmr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xuanzx.com/Article/details/gtioyfwqcj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtjjwxvgct.html

[I05] 按正则拆分
来源：http://dali.jinqigufen.top/Article/details/gttwvewmxf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.mhx1999.top/Article/details/gtxtlzcjtr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.mhx1999.top/Article/details/gtccshevju.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gtmlegvkhz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gtyucegvxl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gtttfsuvop.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yvedp.cn/Article/details/gtkzzebvul.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gttwrzinam.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cheryme.top/Article/details/gtovzxaugl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.fengsongda.top/Article/details/gttsoqbyah.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sweek.top/Article/details/gtagkdhxcq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.haohaochexian.top/Article/details/gtikytpkez.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daxiang520.top/Article/details/gtkhgdcuex.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gtcoglotin.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gtoqsmzpcl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.316326.xyz/Article/details/gtcbxqhhkk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hnqzz.top/Article/details/gtexkdrhyx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sweek.top/Article/details/gtydxmssll.html

[I07] 忽略大小写与多行模式
来源：http://dali.feifeiyinyue.top/Article/details/gtcvwsmwoz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.svipenyu.cn/Article/details/gtmgsjhqos.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhengqikj.top/Article/details/gtwguiybxa.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yangfankeji.com/Article/details/gtjmujpbmf.html

TS:   /error/gim
来源：http://dali.jyoumei.cn/Article/details/gtkgkbsjdd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hnxiangtu.top/Article/details/gtzemnjanz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nanxuanxn.top/Article/details/gtlhrhowul.html


<!-- 参考信息 -->