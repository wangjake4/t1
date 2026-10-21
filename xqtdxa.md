代发 wailian999

TS:   constructor(public name: string) {}
来源：http://dali.sysykeji.top/Article/details/gtwpuvaipt.html

Java: User(String name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnugqdbeg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sysykeji.top/Article/details/gtnolkwdcs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dashuyun.cn/Article/details/gtmcdrftqq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.daria6918.cn/Article/details/gtbvgezsjn.html

[G03] 实例属性
来源：http://dali.sweek.top/Article/details/gtjoviwonb.html

Py:   self.name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgqfnhvxz.html

PHP:  public string $name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtstezdwoo.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtdlxkkeex.html

TS:   name: string = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtddmotqiv.html

Java: private String name;
来源：http://dali.gogol.net.cn/Article/details/gteuskwlyg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yuanzhike.top/Article/details/gtdxyniqsg.html

Ruby: @name = "x"
来源：http://dali.jlsjyb.cn/Article/details/gtbgrkqgjk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.andypj.xyz/Article/details/gtqthclpkx.html

[G04] 定义方法
来源：http://dali.daxiang520.top/Article/details/gteckrjnpu.html

Py:   def greet(self): return self.name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkejyyviq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevlzsubz.html

JS:   greet() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gthxlzgkkt.html

TS:   greet(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtkdnmfuap.html

Java: String greet() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtsmpjrbkv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtvpvxamso.html

Ruby: def greet; @name; end
来源：http://dali.yj20258.top/Article/details/gtigqybzpm.html

C#:   public string Greet() => Name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrwqezje.html

[G05] 继承
来源：http://dali.gogol.net.cn/Article/details/gtplqabqcy.html

Py:   class Admin(User): pass
来源：http://dali.tianlin.xyz/Article/details/gthlyrctft.html

PHP:  class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtioedkadu.html

JS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtqhrokjmc.html

TS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtnxfzgyar.html

Java: class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtouamptdd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jianghu66.top/Article/details/gtkssqdhbu.html

Ruby: class Admin < User; end
来源：http://dali.hnqzz.top/Article/details/gtutokhowl.html

C#:   class Admin : User {}
来源：http://dali.chenzaomai.com/Article/details/gttltllaye.html

[G06] 重写方法
来源：http://dali.redwolf501.top/Article/details/gttqlplowo.html

Py:   def greet(self): return "admin"
来源：http://dali.pengpengdd.cyou/Article/details/gteykqktkp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtenmkxhpq.html

JS:   greet() { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjsdayvpp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gthhlgmdyt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtdvpsubep.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.meibo888.top/Article/details/gtrcjfgpdh.html

Ruby: def greet; "admin"; end
来源：http://dali.aizwys.cn/Article/details/gtzmkxvuvv.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhengqikj.top/Article/details/gtftrbvmpl.html

[G07] 调用父类方法
来源：http://dali.cheryme.top/Article/details/gtjlmevdtw.html

Py:   super().greet()
来源：http://dali.ybcxt.top/Article/details/gtipwtxmpj.html

PHP:  parent::greet();
来源：http://dali.gogol.net.cn/Article/details/gtitqldtnw.html

JS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gttwwsivkk.html

TS:   super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gtkbdjisbe.html

Java: super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtkmedvjbk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xuetiantiany.cn/Article/details/gtrknjoqzp.html

Ruby: super
来源：http://dali.nanxuanxn.top/Article/details/gtysdmgvlk.html

C#:   base.Greet();
来源：http://dali.jyoumei.cn/Article/details/gtoxhhitym.html

[G08] 静态方法与属性
来源：http://dali.yuxming.cn/Article/details/gtrwysvkuw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuetiantiany.cn/Article/details/gtyjkbguvt.html

PHP:  public static function f() {}
来源：http://dali.xylfe.cn/Article/details/gtzdzwtfaa.html

JS:   static f() {}
来源：http://dali.sysykeji.top/Article/details/gtumssvqrm.html

TS:   static f(): void {}
来源：http://dali.yonumen.top/Article/details/gtcvbhqiio.html

Java: static void f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtaxdbbxrh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gogol.net.cn/Article/details/gteeoafjxe.html

Ruby: def self.f; end
来源：http://dali.daria6918.cn/Article/details/gtrxfexxoq.html

C#:   public static void F() {}
来源：http://dali.c1oappe.top/Article/details/gtwvmoquin.html

[G09] 接口 / 抽象类
来源：http://dali.xziqi.cn/Article/details/gtowiyosjr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.316326.xyz/Article/details/gtrqpbjtbv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhixingplan.top/Article/details/gtwrdhjgdd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.fengsongda.top/Article/details/gtgpzbpwbl.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxlkvekkj.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigufen.top/Article/details/gtopivqalk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daxiang520.top/Article/details/gtpucrorkb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jlsjyb.cn/Article/details/gttkfzqwcw.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhengqikj.top/Article/details/gtdtgvviqy.html

[G10] 访问控制
来源：http://dali.shangyingyoupin.top/Article/details/gtqbvmjrof.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ybcxt.top/Article/details/gtdhdjydee.html

PHP:  public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtsbcqeuee.html

JS:   #private 字段；其余公开
来源：http://dali.sufxvd.cn/Article/details/gtxiwdnnqs.html

TS:   public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gtltjinobl.html

Java: public / protected / private / 默认包级
来源：http://dali.0kj1m.cn/Article/details/gtmekmufbf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.redwolf501.top/Article/details/gtyeukgjre.html

Ruby: public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gtvsypmlcs.html

C#:   public / protected / private / internal
来源：http://dali.haohaochexian.top/Article/details/gtcwkjdlxu.html

[G11] getter / setter
来源：http://dali.yj20258.top/Article/details/gtxbffloxv.html

Py:   @property 与 @x.setter
来源：http://dali.jyoumei.cn/Article/details/gtoybfcobr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gtukdwblxf.html

JS:   get name() { return this._name; }
来源：http://dali.tanke756.top/Article/details/gtbtalzggy.html

TS:   get name(): string { return this._name; }
来源：http://dali.cucudq.cn/Article/details/gtpuzkaxzq.html

Java: public String getName() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtybdorpnk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtlajkuknv.html

Ruby: attr_accessor :name
来源：http://dali.cashguo.top/Article/details/gtmhphdivc.html

C#:   public string Name { get; set; }
来源：http://dali.feifeiyinyue.top/Article/details/gtccivdfuf.html

[G12] 对象转字符串
来源：http://dali.yonumen.top/Article/details/gtmzhukkas.html

Py:   def __str__(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gtbmcfqelv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gtwojlgrox.html

JS:   toString() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtmoxblkgk.html

TS:   toString(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtkbfgtqjx.html

Java: @Override public String toString() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtxralruae.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gtfoxpcidg.html

Ruby: def to_s; @name; end
来源：http://dali.ppjwa.cn/Article/details/gtjocgdlqy.html

C#:   public override string ToString() => Name;
来源：http://dali.tianlin.xyz/Article/details/gtbyajxwgx.html

[G13] 判断对象类型
来源：http://dali.cheryme.top/Article/details/gtajlahpqx.html

Py:   isinstance(u, User)
来源：http://dali.c1oappe.top/Article/details/gtbkudbdue.html

PHP:  $u instanceof User
来源：http://dali.sweek.top/Article/details/gtblfdvher.html

JS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtypiyqqkk.html

TS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtvyzioynn.html

Java: u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtfkbghpko.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cheryme.top/Article/details/gtowtyxbsn.html

Ruby: u.is_a?(User)
来源：http://dali.zhiwuduotai.top/Article/details/gttvdxsiws.html

C#:   u is User
来源：http://dali.nanxuanxn.top/Article/details/gtrbkvtjuw.html

[G14] 数据类 / record
来源：http://dali.dianchejie.cn/Article/details/gtudlyjcwe.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenlongwang.top/Article/details/gtxhfcrpfg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hammf.cn/Article/details/gtsdacedhz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cashguo.top/Article/details/gtzbudhbqp.html

TS:   type User = { name: string; age: number };
来源：http://dali.shuidangran.top/Article/details/gtciwpvpnz.html

Java: record User(String name, int age) {}
来源：http://dali.jlsjyb.cn/Article/details/gtiommcllh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsldaepnb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cashguo.top/Article/details/gtpwzkpjsw.html

C#:   record User(string Name, int Age);
来源：http://dali.wangshuangyany.cn/Article/details/gtrxzmomoc.html

[G15] 枚举
来源：http://dali.jlsjyb.cn/Article/details/gtvkjumsah.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gtsgauttlj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtheekltay.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.vqdsnc.cn/Article/details/gtidicavwb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtevdrbwrb.html

Java: enum Color { RED, GREEN }
来源：http://dali.bjfxy.top/Article/details/gttjjcivzi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sufxvd.cn/Article/details/gtdrghgvfl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xuetiantiany.cn/Article/details/gtahhskoef.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.svipenyu.cn/Article/details/gtytsccukt.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigufen.top/Article/details/gtdkaalwco.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.kuanghao11.cn/Article/details/gtbeyxzdsm.html

PHP:  get_object_vars($obj);
来源：http://dali.zhongyouzk.top/Article/details/gtlmuhrxcf.html

JS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gtuqrelwty.html

TS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gtisdhdjdg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jlsjyb.cn/Article/details/gtogxqnsol.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hnxiangtu.top/Article/details/gtxiktppmp.html

Ruby: obj.instance_variables
来源：http://dali.ydzc1.top/Article/details/gtarntbrjx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gtfclpzcmi.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtyanupupa.html

H. 异常与错误处理
来源：http://dali.tian-w.cn/Article/details/gtthbclqvw.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtwruoiqay.html

[H01] try / catch 基础
来源：http://dali.guowangkeji.top/Article/details/gtdlzectre.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gzhubu.top/Article/details/gtmygvaghg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigufen.top/Article/details/gtkppxhuer.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gtyjmclxso.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gtfrkfmbge.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.smart0.xyz/Article/details/gtwnxypodg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.fengsongda.top/Article/details/gtfkotenpx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xuanzx.com/Article/details/gtkdyayhyf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.vqdsnc.cn/Article/details/gttjaengyx.html

[H02] finally / ensure 收尾
来源：http://dali.yvedp.cn/Article/details/gtlpcmmkfw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zycfv.cn/Article/details/gtnmbqimqh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtmfwweoqc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtevhvnexv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtwazrwffr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gttlfbawga.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nwbrower.top/Article/details/gtluooybvi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.bjfxy.top/Article/details/gtheevmbwk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtuolxntkt.html

[H03] 主动抛出异常
来源：http://dali.bjfxy.top/Article/details/gteqrcstfk.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxuanxn.top/Article/details/gtemdqhecx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtqrhrqdui.html

JS:   throw new Error("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtalftdurq.html

TS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gttooupkrl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtwqghbyvb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnqzz.top/Article/details/gtwddsfpyk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.svipenyu.cn/Article/details/gtzwjraiyb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtuhkgajkv.html

[H04] 自定义异常类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkfypteu.html

Py:   class MyError(Exception): pass
来源：http://dali.havefunace.top/Article/details/gtlinxwzud.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gtgpmpjtoe.html

JS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gtcncdvpob.html

TS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gttdgfzjjc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtehrpebap.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hnxiangtu.top/Article/details/gtasbqxkra.html

Ruby: class MyError < StandardError; end
来源：http://dali.sysykeji.top/Article/details/gtydfkcapx.html

C#:   class MyException : Exception {}
来源：http://dali.aibaodan.cn/Article/details/gtfwjlzawz.html

[H05] 捕获特定类型
来源：http://dali.nwbrower.top/Article/details/gtqlsdcyaa.html

Py:   except ValueError as e:
来源：http://dali.ybcxt.top/Article/details/gtnqsuigad.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gtzmuqwhnu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gtqobandoh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtcbfuqxtd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gttezqgnub.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hywenlv.cn/Article/details/gtzdoeknuy.html

Ruby: rescue ArgumentError => e
来源：http://dali.shangyingyoupin.top/Article/details/gtfrichqic.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fengsongda.top/Article/details/gtvrmaubau.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfvzbujb.html

Py:   value = d.get("k") or default
来源：http://dali.zdqjudy.top/Article/details/gtvcfuzeus.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gtqjgsaudv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gtlgirevsa.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gtmkhiztxh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cucudq.cn/Article/details/gthehqmkch.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.andypj.xyz/Article/details/gtdafrtlzv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yueranfly.top/Article/details/gtekqjabxu.html

C#:   obj?.A?.B ?? default
来源：http://dali.vqdsnc.cn/Article/details/gtcqqydyps.html

[H07] 断言
来源：http://dali.jyoumei.cn/Article/details/gtwodgazmk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jyoumei.cn/Article/details/gtqdinemus.html

PHP:  assert($x > 0);
来源：http://dali.iojbl.cn/Article/details/gtqgiiiihv.html

JS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtmxikocji.html

TS:   console.assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzifxedlt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xuanzx.com/Article/details/gtmfoohgew.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daria6918.cn/Article/details/gtotvdgqyl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.bjfxy.top/Article/details/gtwdtjndri.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtmzsungkr.html

[H08] 获取错误信息与堆栈
来源：http://dali.sxryk.cn/Article/details/gtfyhvdpsl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yangfankeji.com/Article/details/gtzbwdzmqj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ydzc1.top/Article/details/gtklggamms.html

JS:   e.message;  e.stack
来源：http://dali.hongshengwenyu.top/Article/details/gteuinqlic.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.0kj1m.cn/Article/details/gtdgwcokxz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhixingplan.top/Article/details/gthfmoodns.html

Go:   err.Error()
来源：http://dali.chenjidiqi.icu/Article/details/gtvkygfqbh.html

Ruby: e.message;  e.backtrace
来源：http://dali.vqdsnc.cn/Article/details/gtwedevhud.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258.top/Article/details/gtglpkbseb.html

[H09] 带错误码的异常
来源：http://dali.9152youxi.cn/Article/details/gtpfvzvihk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuxming.cn/Article/details/gtuzzucgnn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yvedp.cn/Article/details/gtrbhdsquj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj202588.top/Article/details/gtwwiqcmtj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yongpay.top/Article/details/gtxkidqodj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbjdlirly.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tian-w.cn/Article/details/gtsdtxwejz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.svipenyu.cn/Article/details/gtlkazqiow.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xziqi.cn/Article/details/gtoexxlpaz.html

[H10] 资源自动释放
来源：http://dali.ivvv.top/Article/details/gtelkafhqo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenzaomai.com/Article/details/gtmovsmykp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pycfn.com/Article/details/gtnszlhrft.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxuanxn.top/Article/details/gtuscufjxm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dashuyun.cn/Article/details/gtwiimdfra.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigufen.top/Article/details/gtdcffikcz.html

Go:   defer f.Close()
来源：http://dali.zhengqikj.top/Article/details/gtcyfktgeu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.pengpengdd.cyou/Article/details/gtyiedqaon.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtraiondpr.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtyabarlzu.html

I. 正则表达式
来源：http://dali.0kj1m.cn/Article/details/gtxnnyital.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtvsfrhcky.html

[I01] 判断是否匹配
来源：http://dali.cqqwz.cn/Article/details/gtzmnomkcn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fengsongda.top/Article/details/gthesevzkx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258888.top/Article/details/gtbozcaevq.html

JS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gtdfgachfr.html

TS:   /\d+/.test(s)
来源：http://dali.xziqi.cn/Article/details/gtvqrnwkid.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xylfe.cn/Article/details/gtglabtudh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hammf.cn/Article/details/gtfenwnftb.html

Ruby: s.match?(/\d+/)
来源：http://dali.dashuyun.cn/Article/details/gtpwgokxrc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.iojbl.cn/Article/details/gtpgvgfvji.html

[I02] 提取所有匹配
来源：http://dali.chenlongwang.top/Article/details/gtkenlxaqg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cucudq.cn/Article/details/gtgmekwlgy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ydzc1.top/Article/details/gtatmwikkv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.iojbl.cn/Article/details/gtjcuhmajj.html

TS:   s.match(/\d+/g)
来源：http://dali.nanxuanxn.top/Article/details/gtngzfwdov.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.aizwys.cn/Article/details/gtcdzxrxxn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gtlutgjwom.html

Ruby: s.scan(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gtzrpstghv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tanke756.top/Article/details/gtqqwqjlsv.html

[I03] 提取捕获分组
来源：http://dali.zhongyouzk.top/Article/details/gtxycauwya.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenlongwang.top/Article/details/gtzsmabtbz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gogol.net.cn/Article/details/gtwgcesdkt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.dianchejie.cn/Article/details/gtbkcuqhpt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.0kj1m.cn/Article/details/gtpctponaw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.iojbl.cn/Article/details/gtafkitmyb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj202588.top/Article/details/gtwwhoppvd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqubjgjj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sysykeji.top/Article/details/gtbpykacuz.html

[I04] 正则替换
来源：http://dali.gzhubu.top/Article/details/gtiroqpafs.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmydgoowj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.iojbl.cn/Article/details/gtfwivzjow.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gtfpqwivcg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtmqzufaeq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenzaomai.com/Article/details/gtesrghqeu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrzengorq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.fzhhl.top/Article/details/gtmcpykdxa.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuxming.cn/Article/details/gtaatabatb.html

[I05] 按正则拆分
来源：http://dali.dianchejie.cn/Article/details/gthnocjepp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtarlxqeqf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtlltxntoi.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjcvucon.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gtyslbquxn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gotoacloud.top/Article/details/gtdgfkhwpa.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yonumen.top/Article/details/gtjliifrkn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gtdxbyxvvo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hnqzz.top/Article/details/gtzpgjluuj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jlsjyb.cn/Article/details/gtbimvjkvs.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.316326.xyz/Article/details/gtlnpfllaw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhixingplan.top/Article/details/gtbyqxeuas.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.svipenyu.cn/Article/details/gtcqephtao.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gtgjbopsqe.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gtbydlahxw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinqigufen.top/Article/details/gtmxwbkiev.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhoulong.xyz/Article/details/gtgrmwemir.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gtxymtmmbs.html

[I07] 忽略大小写与多行模式
来源：http://dali.meibo888.top/Article/details/gtgqdpyinf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fzhhl.top/Article/details/gtqsrwijug.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gtdohcgkal.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sufxvd.cn/Article/details/gtrntgeulx.html

TS:   /error/gim
来源：http://dali.havefunace.top/Article/details/gtadpeanys.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.vqdsnc.cn/Article/details/gtfnfbvwca.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xziqi.cn/Article/details/gtxvkyapmv.html

Ruby: s.scan(/error/i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgkkrlcrp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.mhx1999.top/Article/details/gtgpuibdnl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangshuangyany.cn/Article/details/gteichjjbv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shzxlz.cn/Article/details/gtswffwhag.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gtccqrbwxe.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuetiantiany.cn/Article/details/gtbyyhqifz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.meibo888.top/Article/details/gtafaikhbn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nanxuanxn.top/Article/details/gtwdcybuaz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jiagoushi.top/Article/details/gtpfajnsnk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.bjfxy.top/Article/details/gtvnnnsbdg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gtbjkfvtwl.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtuhtrophz.html


<!-- 参考信息 -->