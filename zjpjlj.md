代发 wailian999

TS:   constructor(public name: string) {}
来源：http://dali.shzxlz.cn/Article/details/gtuvbiifey.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj20258888.top/Article/details/gtjuqzcjpc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenjidiqi.icu/Article/details/gtvqixiclx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.redwolf501.top/Article/details/gthrnmzkpq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jqgfzy.top/Article/details/gtzcygzjsl.html

[G03] 实例属性
来源：http://dali.shzxlz.cn/Article/details/gtliyazgqn.html

Py:   self.name = "x"
来源：http://dali.cashguo.top/Article/details/gtpublxisn.html

PHP:  public string $name = "x";
来源：http://dali.pycfn.com/Article/details/gtaoudlrug.html

JS:   this.name = "x";
来源：http://dali.jiagoushi.top/Article/details/gtvdwlyxfy.html

TS:   name: string = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtnettbsjx.html

Java: private String name;
来源：http://dali.andypj.xyz/Article/details/gtahukqadt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tianlin.xyz/Article/details/gtxcsvzmju.html

Ruby: @name = "x"
来源：http://dali.yongpay.top/Article/details/gtxitjyyvn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.bjfxy.top/Article/details/gtwrdgolye.html

[G04] 定义方法
来源：http://dali.daria6918.cn/Article/details/gtbxsladup.html

Py:   def greet(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gtfjzcvmfj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gtucrxfhiz.html

JS:   greet() { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtlchsbrts.html

TS:   greet(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gteflfwwrj.html

Java: String greet() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtamklzlkq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gtagpgsqtc.html

Ruby: def greet; @name; end
来源：http://dali.cucudq.cn/Article/details/gtrhwgoydw.html

C#:   public string Greet() => Name;
来源：http://dali.gogol.net.cn/Article/details/gtldrtelon.html

[G05] 继承
来源：http://dali.jyoumei.cn/Article/details/gtjcqsoawn.html

Py:   class Admin(User): pass
来源：http://dali.cqqwz.cn/Article/details/gthtqybsca.html

PHP:  class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gteuanbtrm.html

JS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtutwitzdx.html

TS:   class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtrbevbpcy.html

Java: class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtzwvcyehv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhengqikj.top/Article/details/gtjmzubdev.html

Ruby: class Admin < User; end
来源：http://dali.gaohongyu789.top/Article/details/gtmfykvmeu.html

C#:   class Admin : User {}
来源：http://dali.zhoulong.xyz/Article/details/gtasliiels.html

[G06] 重写方法
来源：http://dali.xuanzx.com/Article/details/gtljfnjgzc.html

Py:   def greet(self): return "admin"
来源：http://dali.hnxiangtu.top/Article/details/gtlpapquin.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gtrkgpnjtw.html

JS:   greet() { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gthjfczisd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtybeazehr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtxkznwxxd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ppjwa.cn/Article/details/gtqtvysxck.html

Ruby: def greet; "admin"; end
来源：http://dali.cashguo.top/Article/details/gtxrytayrb.html

C#:   public override string Greet() => "admin";
来源：http://dali.jlsjyb.cn/Article/details/gtrqyjotyu.html

[G07] 调用父类方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibvbllcd.html

Py:   super().greet()
来源：http://dali.hywenlv.cn/Article/details/gtjfrdojfl.html

PHP:  parent::greet();
来源：http://dali.hammf.cn/Article/details/gtywoobgmu.html

JS:   super.greet();
来源：http://dali.xziqi.cn/Article/details/gtomucbvxo.html

TS:   super.greet();
来源：http://dali.xylfe.cn/Article/details/gtdyhdmcgn.html

Java: super.greet();
来源：http://dali.sxryk.cn/Article/details/gtglhtmxqn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.wangshuangyany.cn/Article/details/gtzkrpegkv.html

Ruby: super
来源：http://dali.jqgufenzy.top/Article/details/gtumagmojx.html

C#:   base.Greet();
来源：http://dali.cucudq.cn/Article/details/gtqziiifzo.html

[G08] 静态方法与属性
来源：http://dali.tian-w.cn/Article/details/gtoqposkma.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yanxiufei.cn/Article/details/gtfywmrihm.html

PHP:  public static function f() {}
来源：http://dali.jyoumei.cn/Article/details/gtgtqoknob.html

JS:   static f() {}
来源：http://dali.mhx1999.top/Article/details/gtycswwcqp.html

TS:   static f(): void {}
来源：http://dali.hongshengwenyu.top/Article/details/gtwmryszxo.html

Java: static void f() {}
来源：http://dali.ppjwa.cn/Article/details/gtpfsgover.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hysaishi.cn/Article/details/gtjoatniab.html

Ruby: def self.f; end
来源：http://dali.yuanzhike.top/Article/details/gtcaeferkt.html

C#:   public static void F() {}
来源：http://dali.dashuyun.cn/Article/details/gtehljbrge.html

[G09] 接口 / 抽象类
来源：http://dali.mhx1999.top/Article/details/gtmuqqscag.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daxiang520.top/Article/details/gtaqxlgqio.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daxiang520.top/Article/details/gtscogzktu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.dashuyun.cn/Article/details/gtaznqnqkf.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenlongwang.top/Article/details/gtwdtigdob.html

Java: interface Shape { double area(); }
来源：http://dali.guowangkeji.top/Article/details/gtjliuabfo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigufen.top/Article/details/gtcjgxldha.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.andypj.xyz/Article/details/gtlqdbwzvz.html

C#:   interface IShape { double Area(); }
来源：http://dali.c1oappe.top/Article/details/gtzqdqlqat.html

[G10] 访问控制
来源：http://dali.gzhubu.top/Article/details/gttimqzkuw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.andypj.xyz/Article/details/gtqqxtryti.html

PHP:  public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gtxrjvybrl.html

JS:   #private 字段；其余公开
来源：http://dali.birdmap.top/Article/details/gtndmerigp.html

TS:   public / protected / private
来源：http://dali.yvedp.cn/Article/details/gtytjvuzil.html

Java: public / protected / private / 默认包级
来源：http://dali.c1oappe.top/Article/details/gtvstxoodg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xinyue.icu/Article/details/gtekeowbsl.html

Ruby: public / protected / private
来源：http://dali.aizwys.cn/Article/details/gtsouskdsh.html

C#:   public / protected / private / internal
来源：http://dali.meibo888.top/Article/details/gtulyhapym.html

[G11] getter / setter
来源：http://dali.0kj1m.cn/Article/details/gtxebyvwzn.html

Py:   @property 与 @x.setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthimwkoqd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtscvisklp.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gtofvakwpu.html

TS:   get name(): string { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gtpbdwugjc.html

Java: public String getName() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtgffmiubo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gtepkkibhv.html

Ruby: attr_accessor :name
来源：http://dali.chenlongwang.top/Article/details/gtaxbhkcch.html

C#:   public string Name { get; set; }
来源：http://dali.gogol.net.cn/Article/details/gtzqyufabg.html

[G12] 对象转字符串
来源：http://dali.birdmap.top/Article/details/gtyfolbgww.html

Py:   def __str__(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gtsboxsnrs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gtreizzdyc.html

JS:   toString() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gticnhnhnp.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtqqouffan.html

Java: @Override public String toString() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gteqmezhdo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtkvgufwxp.html

Ruby: def to_s; @name; end
来源：http://dali.tanke756.top/Article/details/gthayzgpel.html

C#:   public override string ToString() => Name;
来源：http://dali.ehwqpu.com/Article/details/gtuxcewemh.html

[G13] 判断对象类型
来源：http://dali.aizwys.cn/Article/details/gtzkgyqupl.html

Py:   isinstance(u, User)
来源：http://dali.hongshengwenyu.top/Article/details/gtltbxjaag.html

PHP:  $u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtlfkinuyj.html

JS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gtiarmbvei.html

TS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdpkputyb.html

Java: u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtnymkgrdw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuxming.cn/Article/details/gtngvuiilz.html

Ruby: u.is_a?(User)
来源：http://dali.fzhhl.top/Article/details/gtjoztqfaf.html

C#:   u is User
来源：http://dali.gotoacloud.top/Article/details/gtkwbntpjr.html

[G14] 数据类 / record
来源：http://dali.hongshengwenyu.top/Article/details/gtclbqmjqc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tanke756.top/Article/details/gtoxzqlmij.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigufen.top/Article/details/gtvwclwzme.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.9152youxi.cn/Article/details/gtxpgzvnha.html

TS:   type User = { name: string; age: number };
来源：http://dali.jyoumei.cn/Article/details/gtowgqjjkj.html

Java: record User(String name, int age) {}
来源：http://dali.ehwqpu.com/Article/details/gtuykgzqcp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yueranfly.top/Article/details/gtegxqktjb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.iojbl.cn/Article/details/gtigdudave.html

C#:   record User(string Name, int Age);
来源：http://dali.hongshengwenyu.top/Article/details/gtadebgunh.html

[G15] 枚举
来源：http://dali.pycfn.com/Article/details/gtqsatvsnb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj202588.top/Article/details/gtkcuiexrq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guowangkeji.top/Article/details/gtknaddhju.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinghuilouyu.cn/Article/details/gtaffgdbth.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gtklcvmzte.html

Java: enum Color { RED, GREEN }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtclshwirm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jqgufenzy.top/Article/details/gtcsviaycc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tian-w.cn/Article/details/gttwnihgmc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gtlhcllyta.html

[G16] 对象转数组 / 字典
来源：http://dali.pengpengdd.cyou/Article/details/gtmvjlkcga.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.andypj.xyz/Article/details/gtdbfbsotq.html

PHP:  get_object_vars($obj);
来源：http://dali.hongshengwenyu.top/Article/details/gtdjuaxgsh.html

JS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtdpripqis.html

TS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gtvtlcrbtw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cheryme.top/Article/details/gtxswzjedy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shuidangran.top/Article/details/gtnvqurawv.html

Ruby: obj.instance_variables
来源：http://dali.birdmap.top/Article/details/gtgxrpsbse.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gaohongyu789.top/Article/details/gtcaxxlelu.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtypewghck.html

H. 异常与错误处理
来源：http://dali.yuxming.cn/Article/details/gtbuxqilwl.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtrcbhnnef.html

[H01] try / catch 基础
来源：http://dali.chenlongwang.top/Article/details/gtxhbyqezn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nanxuanxn.top/Article/details/gtikkukvxz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zycfv.cn/Article/details/gtdsnlffnb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gtxohbnudf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gtfdzmlmug.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gaohongyu789.top/Article/details/gtbpadmcpq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sufxvd.cn/Article/details/gtjoauwsdr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yongpay.top/Article/details/gtkygdktcq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xylfe.cn/Article/details/gtmwideiza.html

[H02] finally / ensure 收尾
来源：http://dali.yuanzhike.top/Article/details/gtpgmwftop.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangdashe.top/Article/details/gtjqhbklch.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gttqxajrsi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtolliodjs.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gttgcxawyv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtkmjkyzmv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nanxuanxn.top/Article/details/gtksybqmsa.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aizwys.cn/Article/details/gtonpmrbne.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtioxklhsj.html

[H03] 主动抛出异常
来源：http://dali.tianlin.xyz/Article/details/gttjsddlsz.html

Py:   raise ValueError("错误信息")
来源：http://dali.9152youxi.cn/Article/details/gtypmmwboh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtvxtyhnfi.html

JS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtulozmadg.html

TS:   throw new Error("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtkfyxjjuf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtanhxectg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.quarkkingdee.top/Article/details/gteioqmfnx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aizwys.cn/Article/details/gtzifsyqmw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtmysjiorm.html

[H04] 自定义异常类型
来源：http://dali.jiagoushi.top/Article/details/gtcrkjqvld.html

Py:   class MyError(Exception): pass
来源：http://dali.xziqi.cn/Article/details/gtkzpnybcy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zdqjudy.top/Article/details/gtizxfyleu.html

JS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gtrlxfrgdd.html

TS:   class MyError extends Error {}
来源：http://dali.shangyingyoupin.top/Article/details/gtqoxojdav.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xziqi.cn/Article/details/gtsgrpgvki.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cheryme.top/Article/details/gtmwppggax.html

Ruby: class MyError < StandardError; end
来源：http://dali.jianghu66.top/Article/details/gtxezknupu.html

C#:   class MyException : Exception {}
来源：http://dali.andypj.xyz/Article/details/gtfccjghje.html

[H05] 捕获特定类型
来源：http://dali.cdnleiting.top/Article/details/gtbmgiugeq.html

Py:   except ValueError as e:
来源：http://dali.xylfe.cn/Article/details/gtvbrayfkk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.9152youxi.cn/Article/details/gtdwqkmgrq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hfpthk.cn/Article/details/gteydatztt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gtdcnztgda.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nanxinkj.top/Article/details/gtalnnbbig.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gzhubu.top/Article/details/gteiinqejw.html

Ruby: rescue ArgumentError => e
来源：http://dali.mhx1999.top/Article/details/gtmkrbestd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jlsjyb.cn/Article/details/gtnpqwouxd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258888.top/Article/details/gtzgkymqqt.html

Py:   value = d.get("k") or default
来源：http://dali.chenzaomai.com/Article/details/gtcrzhxehi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gtbksinooh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gtmqhxskvn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jianghu66.top/Article/details/gtrpfboarb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.meibo888.top/Article/details/gtjkzsgyuy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yongpay.top/Article/details/gtmfrfjmxz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.0kj1m.cn/Article/details/gtfxfouocd.html

C#:   obj?.A?.B ?? default
来源：http://dali.birdmap.top/Article/details/gtdxfepydv.html

[H07] 断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtdcukuhhe.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258.top/Article/details/gtkknmljqb.html

PHP:  assert($x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtqtvnpqdm.html

JS:   console.assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtqqyoiect.html

TS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtamyqehbs.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cqqwz.cn/Article/details/gtwyyizbsp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenlongwang.top/Article/details/gtztkamtro.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.havefunace.top/Article/details/gtrrxluwbr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtxbnaiupc.html

[H08] 获取错误信息与堆栈
来源：http://dali.ivvv.top/Article/details/gtdikzpwzk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.svipenyu.cn/Article/details/gtwgssmvfj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xziqi.cn/Article/details/gtwtmzcfvp.html

JS:   e.message;  e.stack
来源：http://dali.jianghu66.top/Article/details/gtwlupxkij.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxuanxn.top/Article/details/gtvtuumuzg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nanxuanxn.top/Article/details/gtvekwgzew.html

Go:   err.Error()
来源：http://dali.aizwys.cn/Article/details/gtwjibroap.html

Ruby: e.message;  e.backtrace
来源：http://dali.snrcjt.cn/Article/details/gteplqqmvb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.wangshuangyany.cn/Article/details/gtxysmazhr.html

[H09] 带错误码的异常
来源：http://dali.sufxvd.cn/Article/details/gtdeiatbvi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hywenlv.cn/Article/details/gtmarzuhyf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenlongwang.top/Article/details/gtlrcnynuj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.quarkkingdee.top/Article/details/gtdlfrlpje.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yuxming.cn/Article/details/gtjqxwsgoq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhixingplan.top/Article/details/gtsvvrupxe.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.0kj1m.cn/Article/details/gtgoejebdp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.kuanghao11.cn/Article/details/gttddvjcut.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhengqikj.top/Article/details/gttagnfcaj.html

[H10] 资源自动释放
来源：http://dali.yueranfly.top/Article/details/gteluaktlx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.bjfxy.top/Article/details/gtfewlmgjm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.9152youxi.cn/Article/details/gtqhzdercb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aibaodan.cn/Article/details/gtcgertjzr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gtbadiidvv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shanyushiyangtech.top/Article/details/gttwbedqnp.html

Go:   defer f.Close()
来源：http://dali.gogol.net.cn/Article/details/gtsxlmfzek.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.0kj1m.cn/Article/details/gtgjycqcky.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtfutsmrht.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtxetlegek.html

I. 正则表达式
来源：http://dali.yueranfly.top/Article/details/gtokxwirxu.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtvvsgsxva.html

[I01] 判断是否匹配
来源：http://dali.mhx1999.top/Article/details/gtuthvjotb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gtwxxkjosc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.bjfxy.top/Article/details/gtrqgmbvhd.html

JS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gtvunuubnb.html

TS:   /\d+/.test(s)
来源：http://dali.jqgfzy.top/Article/details/gtlzqkrpmz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtplvzktdm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258888.top/Article/details/gtlgkdsdoh.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gtqyaojmka.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.pycfn.com/Article/details/gtcqgbxypk.html

[I02] 提取所有匹配
来源：http://dali.cashguo.top/Article/details/gtawffztuy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gtvdsttgwi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgfzy.top/Article/details/gtxhudrhdq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenjidiqi.icu/Article/details/gtjhywathj.html

TS:   s.match(/\d+/g)
来源：http://dali.jlsjyb.cn/Article/details/gtwgagppac.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhoulong.xyz/Article/details/gteanhgxse.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.birdmap.top/Article/details/gttbkhrnwj.html

Ruby: s.scan(/\d+/)
来源：http://dali.dashuyun.cn/Article/details/gtreyaouqy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yonumen.top/Article/details/gturftranx.html

[I03] 提取捕获分组
来源：http://dali.dianchejie.cn/Article/details/gtbdrqmqxy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.quarkkingdee.top/Article/details/gttiklbwpi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cdnleiting.top/Article/details/gtrbkunutw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xylfe.cn/Article/details/gtnmjgydye.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sweek.top/Article/details/gtelsipnhz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.wangdashe.top/Article/details/gtlozipdfn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nanxuanxn.top/Article/details/gtuxgdfcph.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ehwqpu.com/Article/details/gtgkpjwslh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zdqjudy.top/Article/details/gtbnkdsotl.html

[I04] 正则替换
来源：http://dali.vqdsnc.cn/Article/details/gtitkupzrl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ehwqpu.com/Article/details/gtcsxlokbb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gzhubu.top/Article/details/gtjwrxgkfh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gtufxtonel.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtstnhirdh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gtdyhynigc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pycfn.com/Article/details/gtraageyje.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.meibo888.top/Article/details/gtxdqskhob.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cashguo.top/Article/details/gtxvhaakcg.html

[I05] 按正则拆分
来源：http://dali.xylfe.cn/Article/details/gtppyqoevd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtsytuazdo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtdxdaicgu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gteaidcbmy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gtnmpbssah.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxsljfwil.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuhdandtz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gtnkyhkkay.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.quarkkingdee.top/Article/details/gtbgnklbfv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hongshengwenyu.top/Article/details/gtuxagpuun.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yongpay.top/Article/details/gtsilswrtm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.0kj1m.cn/Article/details/gtpbhwxdpn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenzaomai.com/Article/details/gtsaxxbhtq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gtxchfbjvd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gtqgccyjdk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.316326.xyz/Article/details/gtbxvaqddt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hfpthk.cn/Article/details/gteiolmtao.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjnamszjr.html

[I07] 忽略大小写与多行模式
来源：http://dali.yuxming.cn/Article/details/gtsiizrhpy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.c1oappe.top/Article/details/gtzjkkcvrs.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gtegpqwfyy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xziqi.cn/Article/details/gtloatskqo.html

TS:   /error/gim
来源：http://dali.xziqi.cn/Article/details/gthucgnfil.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.redwolf501.top/Article/details/gtzkoykxqc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xuanzx.com/Article/details/gtnpibifvd.html

Ruby: s.scan(/error/i)
来源：http://dali.havefunace.top/Article/details/gtusfamacc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ehwqpu.com/Article/details/gtppxwcccv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.fengsongda.top/Article/details/gtybsdsggx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.wangshuangyany.cn/Article/details/gtblcuuudf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.316326.xyz/Article/details/gtgashvvle.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj202588.top/Article/details/gtgoltnzpi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfgwkesu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinqigfzy.top/Article/details/gtipqcdwmf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gogol.net.cn/Article/details/gtbtppsuee.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gtcehxcmsv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.fzhhl.top/Article/details/gtozfnjild.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtbndfswep.html


<!-- 参考信息 -->