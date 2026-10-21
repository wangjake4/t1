代发 wailian999

JS:   this.name = "x";
来源：http://dali.yuanzhike.top/Article/details/gtpfvgniaw.html

TS:   name: string = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtsvrahypa.html

Java: private String name;
来源：http://dali.ivvv.top/Article/details/gtmzwrtigo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinghuilouyu.cn/Article/details/gtnzgdibow.html

Ruby: @name = "x"
来源：http://dali.yj20258888.top/Article/details/gtsdagjlph.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ybcxt.top/Article/details/gtskwckuvo.html

[G04] 定义方法
来源：http://dali.jlsjyb.cn/Article/details/gtheyydjkv.html

Py:   def greet(self): return self.name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtncqsfwqj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtwdmweoea.html

JS:   greet() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtqqtivlxs.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdjtadjx.html

Java: String greet() { return name; }
来源：http://dali.ivvv.top/Article/details/gtmpglmruv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtjilyegoz.html

Ruby: def greet; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gtztjtwbut.html

C#:   public string Greet() => Name;
来源：http://dali.jiagoushi.top/Article/details/gtrpngbyqt.html

[G05] 继承
来源：http://dali.cashguo.top/Article/details/gtdgordrrc.html

Py:   class Admin(User): pass
来源：http://dali.yangfankeji.com/Article/details/gtgamjqfno.html

PHP:  class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcwjlnbsd.html

JS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtxittgpve.html

TS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gttfyhwftg.html

Java: class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtuwivbpxg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xinyue.icu/Article/details/gtjbleunzw.html

Ruby: class Admin < User; end
来源：http://dali.sufxvd.cn/Article/details/gtyrzjakkl.html

C#:   class Admin : User {}
来源：http://dali.smart0.xyz/Article/details/gtbktivleb.html

[G06] 重写方法
来源：http://dali.pengpengdd.cyou/Article/details/gtftohnnqp.html

Py:   def greet(self): return "admin"
来源：http://dali.shuidangran.top/Article/details/gtaelikpyg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtxbphfzmv.html

JS:   greet() { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtlrtqnjtv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtnwfxtett.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtwzbhyuju.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenjidiqi.icu/Article/details/gtgefjfkgy.html

Ruby: def greet; "admin"; end
来源：http://dali.hywenlv.cn/Article/details/gtplqhhhas.html

C#:   public override string Greet() => "admin";
来源：http://dali.shuidangran.top/Article/details/gtrlugmzgw.html

[G07] 调用父类方法
来源：http://dali.ivvv.top/Article/details/gtixkzlypd.html

Py:   super().greet()
来源：http://dali.andypj.xyz/Article/details/gtohrzywot.html

PHP:  parent::greet();
来源：http://dali.tian-w.cn/Article/details/gtbofcecsu.html

JS:   super.greet();
来源：http://dali.chenlongwang.top/Article/details/gtpvnqovvg.html

TS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gtqllvviud.html

Java: super.greet();
来源：http://dali.gogol.net.cn/Article/details/gttxzjyrwk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shangyingyoupin.top/Article/details/gttnengani.html

Ruby: super
来源：http://dali.316326.xyz/Article/details/gtnkxazoox.html

C#:   base.Greet();
来源：http://dali.aibaodan.cn/Article/details/gtgkptjxiw.html

[G08] 静态方法与属性
来源：http://dali.dashuyun.cn/Article/details/gttmdphztx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xziqi.cn/Article/details/gtvvqehoha.html

PHP:  public static function f() {}
来源：http://dali.cashguo.top/Article/details/gtlvirrpuj.html

JS:   static f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtmdbmlaah.html

TS:   static f(): void {}
来源：http://dali.yj20258.top/Article/details/gtmmtexzed.html

Java: static void f() {}
来源：http://dali.jianghu66.top/Article/details/gtbmncuavi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yvedp.cn/Article/details/gtqrrvlknb.html

Ruby: def self.f; end
来源：http://dali.hammf.cn/Article/details/gtkkodoplw.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvnamfve.html

[G09] 接口 / 抽象类
来源：http://dali.havefunace.top/Article/details/gtgpzztxlc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxuanxn.top/Article/details/gtgcmtbpyn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xylfe.cn/Article/details/gtbxohkhpk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yueranfly.top/Article/details/gtsojqeuxz.html

TS:   interface Shape { area(): number; }
来源：http://dali.cdnleiting.top/Article/details/gtonluspcb.html

Java: interface Shape { double area(); }
来源：http://dali.ydzc1.top/Article/details/gtiscvrqgm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gotoacloud.top/Article/details/gtopjnfezr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.snrcjt.cn/Article/details/gtbuedsfgd.html

C#:   interface IShape { double Area(); }
来源：http://dali.tianlin.xyz/Article/details/gtldqsgmaq.html

[G10] 访问控制
来源：http://dali.cucudq.cn/Article/details/gtbqzwiepe.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jiagoushi.top/Article/details/gtxtzfxfmu.html

PHP:  public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtgrqjzqhq.html

JS:   #private 字段；其余公开
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvbluqred.html

TS:   public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gthctcjtvf.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gtthouafzn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.snrcjt.cn/Article/details/gttvvgpana.html

Ruby: public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gtwgzifvhj.html

C#:   public / protected / private / internal
来源：http://dali.nanxinkj.top/Article/details/gtuttnhuxc.html

[G11] getter / setter
来源：http://dali.iojbl.cn/Article/details/gtpkqafltf.html

Py:   @property 与 @x.setter
来源：http://dali.fzhhl.top/Article/details/gtmhdbelcm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gtrpfylwdc.html

JS:   get name() { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gtxkfhmimh.html

TS:   get name(): string { return this._name; }
来源：http://dali.havefunace.top/Article/details/gtjbnlyrue.html

Java: public String getName() { return name; }
来源：http://dali.andypj.xyz/Article/details/gtmzjmfpma.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtkhhxlzii.html

Ruby: attr_accessor :name
来源：http://dali.dashuyun.cn/Article/details/gtahbnzvve.html

C#:   public string Name { get; set; }
来源：http://dali.zhixingplan.top/Article/details/gtskikoxza.html

[G12] 对象转字符串
来源：http://dali.hfpthk.cn/Article/details/gtyyptmofm.html

Py:   def __str__(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gtgyfukxss.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtofwqioly.html

JS:   toString() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtlguaucvb.html

TS:   toString(): string { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gtyohacmsq.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtigkcqsla.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shuidangran.top/Article/details/gtytjxkngu.html

Ruby: def to_s; @name; end
来源：http://dali.yuanzhike.top/Article/details/gtdyejvduu.html

C#:   public override string ToString() => Name;
来源：http://dali.havefunace.top/Article/details/gtfdrovfsl.html

[G13] 判断对象类型
来源：http://dali.yuanzhike.top/Article/details/gtbdcubljv.html

Py:   isinstance(u, User)
来源：http://dali.aizwys.cn/Article/details/gttfkgbmnq.html

PHP:  $u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gtioexgwvy.html

JS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gtahyklckg.html

TS:   u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtpetradyb.html

Java: u instanceof User
来源：http://dali.cheryme.top/Article/details/gtwnixjgss.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yanxiufei.cn/Article/details/gtmntpzewd.html

Ruby: u.is_a?(User)
来源：http://dali.zhixingplan.top/Article/details/gtsighpxuq.html

C#:   u is User
来源：http://dali.pengpengdd.cyou/Article/details/gtvjbkzbdm.html

[G14] 数据类 / record
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoooltbde.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigufen.top/Article/details/gtqjkirfyi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.daxiang520.top/Article/details/gteqjmbegx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.kuanghao11.cn/Article/details/gtybahgaff.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigfzy.top/Article/details/gthwuxdovz.html

Java: record User(String name, int age) {}
来源：http://dali.gzhubu.top/Article/details/gtiayjlows.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yongpay.top/Article/details/gtxngspvfd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.316326.xyz/Article/details/gtkgeytbsd.html

C#:   record User(string Name, int Age);
来源：http://dali.hongshengwenyu.top/Article/details/gtkughulfe.html

[G15] 枚举
来源：http://dali.jinqigufen.top/Article/details/gtutpedyem.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhoulong.xyz/Article/details/gtackmxjjb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sufxvd.cn/Article/details/gtzspsnxti.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tian-w.cn/Article/details/gtuhyjfkiq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gtzvpfxlnu.html

Java: enum Color { RED, GREEN }
来源：http://dali.shuidangran.top/Article/details/gtgonefbtq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yanxiufei.cn/Article/details/gtilqahcxw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yongpay.top/Article/details/gthpppuzzc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtmncmudnx.html

[G16] 对象转数组 / 字典
来源：http://dali.gotoacloud.top/Article/details/gtpixldgnq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgufenzy.top/Article/details/gtooymuaqi.html

PHP:  get_object_vars($obj);
来源：http://dali.aibaodan.cn/Article/details/gtiowfwhyv.html

JS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gtzddvyors.html

TS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gtjbbezwxz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ybcxt.top/Article/details/gtgkfnpacr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nanxinkj.top/Article/details/gtaxauqdtl.html

Ruby: obj.instance_variables
来源：http://dali.shangyingyoupin.top/Article/details/gtypsezkng.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gtypkxyzod.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtbtsgqfrs.html

H. 异常与错误处理
来源：http://dali.jqgufenzy.top/Article/details/gtsomncwap.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtnaomuowi.html

[H01] try / catch 基础
来源：http://dali.0kj1m.cn/Article/details/gtjdezbmkq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yongpay.top/Article/details/gtwrimpbza.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.mhx1999.top/Article/details/gtsbvkripl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gtnxqfptwx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhongyouzk.top/Article/details/gtvgzvowhg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.havefunace.top/Article/details/gtidtlfwev.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gtwnnlllox.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cdnleiting.top/Article/details/gtyzhcdzzj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shangyingyoupin.top/Article/details/gtuzmxjqau.html

[H02] finally / ensure 收尾
来源：http://dali.chenlongwang.top/Article/details/gtaydanlxv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yanxiufei.cn/Article/details/gtkhbbkblo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtmgcokuau.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtkacgqsko.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtkrlqiihl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtqeuorqnx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jyoumei.cn/Article/details/gtdlqvaryz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.316326.xyz/Article/details/gtxuvmagtb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtiabbetyw.html

[H03] 主动抛出异常
来源：http://dali.zhiwuduotai.top/Article/details/gtnjjuloeg.html

Py:   raise ValueError("错误信息")
来源：http://dali.yanxiufei.cn/Article/details/gtyhmmqoen.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtfqlmsyds.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gtfxfokojx.html

TS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtvciubmgn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtdwiitieb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yonumen.top/Article/details/gtrxzztpbt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hfpthk.cn/Article/details/gtzkxyfhyk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtfwlntejt.html

[H04] 自定义异常类型
来源：http://dali.yuxming.cn/Article/details/gtryfjrfad.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gtqavjxvzk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntwbzhso.html

JS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gtfcjmwhvx.html

TS:   class MyError extends Error {}
来源：http://dali.yvedp.cn/Article/details/gtqgvzpvnh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gtctqhlnaw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.vqdsnc.cn/Article/details/gtzwqupdyv.html

Ruby: class MyError < StandardError; end
来源：http://dali.andypj.xyz/Article/details/gtypzbnbop.html

C#:   class MyException : Exception {}
来源：http://dali.sweek.top/Article/details/gtnjmfbnqv.html

[H05] 捕获特定类型
来源：http://dali.hammf.cn/Article/details/gtgjycasks.html

Py:   except ValueError as e:
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmmuxiytq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jyoumei.cn/Article/details/gtlkmqnlpa.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gtqraabrgp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gtdgjuplag.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtptjcpgyc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cdnleiting.top/Article/details/gtpyfhvvfe.html

Ruby: rescue ArgumentError => e
来源：http://dali.yueranfly.top/Article/details/gthbleiyix.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hysaishi.cn/Article/details/gtzogyfxnc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzucyuwpa.html

Py:   value = d.get("k") or default
来源：http://dali.hnqzz.top/Article/details/gtzkimwymy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gthkvzzuib.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gtruvhrfqn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgufenzy.top/Article/details/gtgwbeuivr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daxiang520.top/Article/details/gtceoqirpg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xinyue.icu/Article/details/gtnfkcfzuk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yonumen.top/Article/details/gtqpjcpgbe.html

C#:   obj?.A?.B ?? default
来源：http://dali.jianghu66.top/Article/details/gtodcjulfo.html

[H07] 断言
来源：http://dali.zhixingplan.top/Article/details/gtabhtwvit.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinghuilouyu.cn/Article/details/gtkuunlbtc.html

PHP:  assert($x > 0);
来源：http://dali.c1oappe.top/Article/details/gtuclzxofa.html

JS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtfgkminwp.html

TS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtyahegtzi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigufen.top/Article/details/gtjbjkutsg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ydzc1.top/Article/details/gtmnzsajey.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.vqdsnc.cn/Article/details/gtloadyvya.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtyzwcnejc.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenlongwang.top/Article/details/gtiesqpzlo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ppjwa.cn/Article/details/gtlzktiogv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.svipenyu.cn/Article/details/gtugkoflqm.html

JS:   e.message;  e.stack
来源：http://dali.fzhhl.top/Article/details/gtszdtfmds.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtivybqwft.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.pengpengdd.cyou/Article/details/gtyilscgwp.html

Go:   err.Error()
来源：http://dali.tian-w.cn/Article/details/gtzefunswk.html

Ruby: e.message;  e.backtrace
来源：http://dali.havefunace.top/Article/details/gtwwettnfw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.dashuyun.cn/Article/details/gtadeuutqv.html

[H09] 带错误码的异常
来源：http://dali.shuidangran.top/Article/details/gteedtekad.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.mhx1999.top/Article/details/gtornzmcsw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.svipenyu.cn/Article/details/gtakbbxcka.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangdashe.top/Article/details/gtauqoexdc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jqgufenzy.top/Article/details/gtlncazldj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.fengsongda.top/Article/details/gtxfytposo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yonumen.top/Article/details/gttvdxujyj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnqzz.top/Article/details/gtwnautscy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj20258888.top/Article/details/gtaqmokhcd.html

[H10] 资源自动释放
来源：http://dali.zycfv.cn/Article/details/gtmakgjtcl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.redwolf501.top/Article/details/gtgvmcszlp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.fengsongda.top/Article/details/gttltffjtl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ivvv.top/Article/details/gtdfuafppk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gaohongyu789.top/Article/details/gtmzkolcaw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sufxvd.cn/Article/details/gtxugtxyqc.html

Go:   defer f.Close()
来源：http://dali.guannengcc.top/Article/details/gtlytjwksz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yongpay.top/Article/details/gtwfqadggr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtofysfcuw.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtyutgpdbe.html

I. 正则表达式
来源：http://dali.wangshuangyany.cn/Article/details/gtxqoizfvh.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gthihedfvy.html

[I01] 判断是否匹配
来源：http://dali.hywenlv.cn/Article/details/gtmmfonywc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhiwuduotai.top/Article/details/gtwypkcijj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shuidangran.top/Article/details/gtxthfuhel.html

JS:   /\d+/.test(s)
来源：http://dali.yj202588.top/Article/details/gtotmgpnry.html

TS:   /\d+/.test(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtatlsyrcf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.guannengcc.top/Article/details/gtzffgcsud.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj202588.top/Article/details/gtfxlawaow.html

Ruby: s.match?(/\d+/)
来源：http://dali.zdqjudy.top/Article/details/gtvrubdaeg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nanxinkj.top/Article/details/gtpzqxsbyk.html

[I02] 提取所有匹配
来源：http://dali.ydzc1.top/Article/details/gtggsznbby.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtvfcvlvyc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zdqjudy.top/Article/details/gtkaafpxzw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xinyue.icu/Article/details/gtmzwbmcmi.html

TS:   s.match(/\d+/g)
来源：http://dali.xuetiantiany.cn/Article/details/gtjqhfabwy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pycfn.com/Article/details/gtiyepylwz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gtiihcjvsg.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gtymumlnig.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gotoacloud.top/Article/details/gtalsvhmcx.html

[I03] 提取捕获分组
来源：http://dali.hnqzz.top/Article/details/gtjegrtwpf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtflhsizsx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinqigufen.top/Article/details/gtcdohfftf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.kuanghao11.cn/Article/details/gtfqnzkpup.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gzhubu.top/Article/details/gtpbjyfglq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuanzx.com/Article/details/gtttijsqyd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinqigfzy.top/Article/details/gtmnlkddii.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hywenlv.cn/Article/details/gtsqdsqmyg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.redwolf501.top/Article/details/gtlmoorymo.html

[I04] 正则替换
来源：http://dali.hammf.cn/Article/details/gtujofsesy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhengqikj.top/Article/details/gtjmxzjqhk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.birdmap.top/Article/details/gtvuvdnntt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xziqi.cn/Article/details/gthifnzqgc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj202588.top/Article/details/gtiuguzbsv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yvedp.cn/Article/details/gtgcovbuov.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sysykeji.top/Article/details/gtlvxyfixf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtovrsbvqw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.havefunace.top/Article/details/gtvtltjoiu.html

[I05] 按正则拆分
来源：http://dali.xylfe.cn/Article/details/gtothqoozn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shuidangran.top/Article/details/gtlhihkkgg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gthrpacodj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gtyfemzbnc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gtrngbdfjm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sweek.top/Article/details/gtldkobxzz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gtgvzjckuj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gtovdgnmrr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.snrcjt.cn/Article/details/gttoqfdjss.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.316326.xyz/Article/details/gtswhtfwko.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gtlltqyunt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj20258.top/Article/details/gtvicdesdu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.andypj.xyz/Article/details/gtwabpangp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivajffzs.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gtddivudhl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zycfv.cn/Article/details/gthvdbksxa.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jianghu66.top/Article/details/gtosqlhnay.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gtflvqpxtr.html

[I07] 忽略大小写与多行模式
来源：http://dali.tanke756.top/Article/details/gtsfuainog.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cdnleiting.top/Article/details/gtobhcnzme.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.meibo888.top/Article/details/gtjwiickdz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yuxming.cn/Article/details/gtpwszrkjj.html

TS:   /error/gim
来源：http://dali.aibaodan.cn/Article/details/gtqzmjqpqr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.quarkkingdee.top/Article/details/gtsgxbpxha.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.bjfxy.top/Article/details/gtgvxmqoys.html

Ruby: s.scan(/error/i)
来源：http://dali.sysykeji.top/Article/details/gtrlzdalag.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigfzy.top/Article/details/gtyjdxwpym.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yongpay.top/Article/details/gtqmvgizqz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.feifeiyinyue.top/Article/details/gtgmtyoxhy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwmagrmg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258.top/Article/details/gtusyucrbt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daxiang520.top/Article/details/gtgjbgloap.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenjidiqi.icu/Article/details/gtjihtkber.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.havefunace.top/Article/details/gtywumoxpx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhengqikj.top/Article/details/gtrvbmmgin.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinyuanbaomall.cn/Article/details/gteqpfrgjp.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtjgwxcjhu.html

J. 日期与时间
来源：http://dali.jianghu66.top/Article/details/gtdeqrzuqx.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gttrivvmzq.html

[J01] 获取当前时间
来源：http://dali.redwolf501.top/Article/details/gtvljyorjc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gogol.net.cn/Article/details/gtxqcitrrc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ppjwa.cn/Article/details/gtqdynnbzb.html

JS:   new Date();  Date.now()
来源：http://dali.yueranfly.top/Article/details/gtkzeksdpf.html

TS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gtrvmwtjkq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.birdmap.top/Article/details/gtrusvgdcc.html


<!-- 参考信息 -->