代发 wailian999

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtazzffwzf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtrngjblsf.html

[F11] 复制与移动文件
来源：http://dali.fzhhl.top/Article/details/gtnwthjkhd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gttbipjmmc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gogol.net.cn/Article/details/gtbajxufhr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtbpbmhuxe.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtdhffxfsg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ivvv.top/Article/details/gtuwpdksek.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangtech.top/Article/details/gtvphsvnep.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtxrpesqxz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhixingplan.top/Article/details/gtdtjvqzri.html

[F12] CSV 读写
来源：http://dali.xuanzx.com/Article/details/gtilclqcyf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nwbrower.top/Article/details/gtaksssjej.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tian-w.cn/Article/details/gtdfcyccpe.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xziqi.cn/Article/details/gtiouwadqd.html

TS:   // 同上
来源：http://dali.cashguo.top/Article/details/gtlemhnunp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ivvv.top/Article/details/gtykunrkzp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sufxvd.cn/Article/details/gtnhqldwhi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jiagoushi.top/Article/details/gtuyahtiov.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tianlin.xyz/Article/details/gtdfreuhcj.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtybnighee.html

G. 面向对象
来源：http://dali.havefunace.top/Article/details/gtbunpqdwm.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtpijnfkdv.html

[G01] 定义类
来源：http://dali.ppjwa.cn/Article/details/gtuayhqszo.html

Py:   class User: pass
来源：http://dali.ehwqpu.com/Article/details/gtoqdlmrmo.html

PHP:  class User {}
来源：http://dali.zdqjudy.top/Article/details/gtyhtmysfh.html

JS:   class User {}
来源：http://dali.havefunace.top/Article/details/gtjtfwdtxv.html

TS:   class User { name: string = ""; }
来源：http://dali.hfpthk.cn/Article/details/gtyvwdiuhh.html

Java: class User {}
来源：http://dali.gotoacloud.top/Article/details/gtvmpsuuxa.html

Go:   type User struct { Name string }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdipeinbp.html

Ruby: class User; end
来源：http://dali.pengpengdd.cyou/Article/details/gttkzwfmby.html

C#:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gtenfikopc.html

[G02] 构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gtxiptvwnw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuetiantiany.cn/Article/details/gtetkugaav.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnqzz.top/Article/details/gtjsvrssnm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sufxvd.cn/Article/details/gtlkhjkmpl.html

TS:   constructor(public name: string) {}
来源：http://dali.yvedp.cn/Article/details/gtcszbfmti.html

Java: User(String name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtignvuytx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yongpay.top/Article/details/gtnkdblnxz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxuanxn.top/Article/details/gtmszfnxvq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gtkrovexfw.html

[G03] 实例属性
来源：http://dali.dianchejie.cn/Article/details/gtsvuncksh.html

Py:   self.name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gtiznhwxkn.html

PHP:  public string $name = "x";
来源：http://dali.snrcjt.cn/Article/details/gticujfqzo.html

JS:   this.name = "x";
来源：http://dali.mhx1999.top/Article/details/gtybczqrzz.html

TS:   name: string = "x";
来源：http://dali.iojbl.cn/Article/details/gtyincrtcc.html

Java: private String name;
来源：http://dali.andypj.xyz/Article/details/gtqbheljdr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.andypj.xyz/Article/details/gtlqdrqrwp.html

Ruby: @name = "x"
来源：http://dali.gogol.net.cn/Article/details/gtegcwxkif.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zycfv.cn/Article/details/gtyxnfeaeh.html

[G04] 定义方法
来源：http://dali.yj20258888.top/Article/details/gtzfblvltj.html

Py:   def greet(self): return self.name
来源：http://dali.chenlongwang.top/Article/details/gtiwbzltfa.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtngtgmblk.html

JS:   greet() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtynvhemoe.html

TS:   greet(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gttovzxgjh.html

Java: String greet() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtlrbovhjw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gttnzfjnha.html

Ruby: def greet; @name; end
来源：http://dali.ivvv.top/Article/details/gtoteggfvs.html

C#:   public string Greet() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gthgransnm.html

[G05] 继承
来源：http://dali.tanke756.top/Article/details/gtleiepwhb.html

Py:   class Admin(User): pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuflxzqho.html

PHP:  class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtdrbwmzoo.html

JS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtfgijzkus.html

TS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtzudlhvmk.html

Java: class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtdvdqtdcl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guannengcc.top/Article/details/gtoazotvmh.html

Ruby: class Admin < User; end
来源：http://dali.jqgfzy.top/Article/details/gtlobepcdk.html

C#:   class Admin : User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtafnbcjet.html

[G06] 重写方法
来源：http://dali.shuidangran.top/Article/details/gteiofafjd.html

Py:   def greet(self): return "admin"
来源：http://dali.fzhhl.top/Article/details/gtxdftepmm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtveuudcnz.html

JS:   greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtprbdsbvl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtcadxncig.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtrfyknqky.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tianlin.xyz/Article/details/gtjhdcjexj.html

Ruby: def greet; "admin"; end
来源：http://dali.bjfxy.top/Article/details/gtwipqmkgy.html

C#:   public override string Greet() => "admin";
来源：http://dali.pycfn.com/Article/details/gtrosjtjgj.html

[G07] 调用父类方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzatnkfwp.html

Py:   super().greet()
来源：http://dali.zycfv.cn/Article/details/gtpkpuetol.html

PHP:  parent::greet();
来源：http://dali.hnxiangtu.top/Article/details/gtvarpswie.html

JS:   super.greet();
来源：http://dali.dashuyun.cn/Article/details/gtbnulzvhi.html

TS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gtxaejzhld.html

Java: super.greet();
来源：http://dali.tian-w.cn/Article/details/gtughfroxy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ivvv.top/Article/details/gtgjjmnbti.html

Ruby: super
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxbjrtrca.html

C#:   base.Greet();
来源：http://dali.xinyue.icu/Article/details/gtzrjxdgve.html

[G08] 静态方法与属性
来源：http://dali.jianghu66.top/Article/details/gtvfhexzsq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daxiang520.top/Article/details/gtimqrhdmg.html

PHP:  public static function f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtgruqtsij.html

JS:   static f() {}
来源：http://dali.cashguo.top/Article/details/gtluhzqsfi.html

TS:   static f(): void {}
来源：http://dali.daria6918.cn/Article/details/gtkyhydfhj.html

Java: static void f() {}
来源：http://dali.tanke756.top/Article/details/gtydcgvyfo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ybcxt.top/Article/details/gtqvxkjxqx.html

Ruby: def self.f; end
来源：http://dali.svipenyu.cn/Article/details/gtieipktnr.html

C#:   public static void F() {}
来源：http://dali.ppjwa.cn/Article/details/gtpbixsatz.html

[G09] 接口 / 抽象类
来源：http://dali.yonumen.top/Article/details/gtlcwpwkmi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258888.top/Article/details/gtkijvfwbj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxinkj.top/Article/details/gtkqorybow.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.316326.xyz/Article/details/gtbybspyrp.html

TS:   interface Shape { area(): number; }
来源：http://dali.hysaishi.cn/Article/details/gtfynqnwrg.html

Java: interface Shape { double area(); }
来源：http://dali.c1oappe.top/Article/details/gtzdmepqmx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.vqdsnc.cn/Article/details/gttlyglgpv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yongpay.top/Article/details/gtualtgvoq.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgufenzy.top/Article/details/gtnqjuxcia.html

[G10] 访问控制
来源：http://dali.shzxlz.cn/Article/details/gtdyqqzrpx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jlsjyb.cn/Article/details/gtmlawxuqy.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gteloabcgy.html

JS:   #private 字段；其余公开
来源：http://dali.xuanzx.com/Article/details/gtdgipjkqn.html

TS:   public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gtlagbkcxg.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigufen.top/Article/details/gtwegaylzx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258888.top/Article/details/gtvyqnuhyt.html

Ruby: public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gtfyroelfd.html

C#:   public / protected / private / internal
来源：http://dali.fzhhl.top/Article/details/gtfhplmwii.html

[G11] getter / setter
来源：http://dali.xinyue.icu/Article/details/gtvneovyjn.html

Py:   @property 与 @x.setter
来源：http://dali.ydzc1.top/Article/details/gtmkdfreyw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtazpniqod.html

JS:   get name() { return this._name; }
来源：http://dali.yongpay.top/Article/details/gtxbqdasdn.html

TS:   get name(): string { return this._name; }
来源：http://dali.pycfn.com/Article/details/gttybpzego.html

Java: public String getName() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtadzidjxw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtvublqell.html

Ruby: attr_accessor :name
来源：http://dali.dashuyun.cn/Article/details/gttkyxcxru.html

C#:   public string Name { get; set; }
来源：http://dali.haohaochexian.top/Article/details/gtnsxvgknh.html

[G12] 对象转字符串
来源：http://dali.guowangkeji.top/Article/details/gtiqlftliv.html

Py:   def __str__(self): return self.name
来源：http://dali.xziqi.cn/Article/details/gtmvdnavcz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gtjpucikio.html

JS:   toString() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtqpgrilnf.html

TS:   toString(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtfwzslvxn.html

Java: @Override public String toString() { return name; }
来源：http://dali.cashguo.top/Article/details/gttnxhatsv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gthiqlpjdp.html

Ruby: def to_s; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtoembcwtj.html

C#:   public override string ToString() => Name;
来源：http://dali.ydzc1.top/Article/details/gtlfnyzymz.html

[G13] 判断对象类型
来源：http://dali.gogol.net.cn/Article/details/gtbvrtfqat.html

Py:   isinstance(u, User)
来源：http://dali.gzhubu.top/Article/details/gtuwqykgop.html

PHP:  $u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtfdrqhknp.html

JS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gtjkezazrd.html

TS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gttsjyrkbr.html

Java: u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtimhhloyn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxuanxn.top/Article/details/gtqlxnrmrv.html

Ruby: u.is_a?(User)
来源：http://dali.tanke756.top/Article/details/gtvpccswri.html

C#:   u is User
来源：http://dali.tianlin.xyz/Article/details/gtkeevlkdu.html

[G14] 数据类 / record
来源：http://dali.daxiang520.top/Article/details/gtylamzmwy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guowangkeji.top/Article/details/gtfxwmcoue.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.wangdashe.top/Article/details/gtxqgxjpdg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.c1oappe.top/Article/details/gtfsyjdowx.html

TS:   type User = { name: string; age: number };
来源：http://dali.iojbl.cn/Article/details/gtqdpchequ.html

Java: record User(String name, int age) {}
来源：http://dali.mhx1999.top/Article/details/gtcpnyphpc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hongshengwenyu.top/Article/details/gtxnuxqztb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jlsjyb.cn/Article/details/gtuuvtnrkk.html

C#:   record User(string Name, int Age);
来源：http://dali.yanxiufei.cn/Article/details/gtunyabywm.html

[G15] 枚举
来源：http://dali.yueranfly.top/Article/details/gtfsszkrdu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yangfankeji.com/Article/details/gtyuuuvnya.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.haohaochexian.top/Article/details/gtyrgxjmcz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.snrcjt.cn/Article/details/gtjqulmspm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gtvvufrldy.html

Java: enum Color { RED, GREEN }
来源：http://dali.shanyushiyangtech.top/Article/details/gtswcoemmy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.andypj.xyz/Article/details/gtfrsqprqq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yueranfly.top/Article/details/gtaxdqvzto.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yonumen.top/Article/details/gtezximurg.html

[G16] 对象转数组 / 字典
来源：http://dali.zdqjudy.top/Article/details/gtxknclqvj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.smart0.xyz/Article/details/gtbneosxob.html

PHP:  get_object_vars($obj);
来源：http://dali.zhixingplan.top/Article/details/gtbeuamjvg.html

JS:   Object.entries(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtpugcrscg.html

TS:   Object.entries(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnvudfyv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.havefunace.top/Article/details/gthkffqefz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hnqzz.top/Article/details/gtmnfqjtsz.html

Ruby: obj.instance_variables
来源：http://dali.chenjidiqi.icu/Article/details/gtlgrqtpvv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ehwqpu.com/Article/details/gttolprwwr.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtqdbiqfbw.html

H. 异常与错误处理
来源：http://dali.ybcxt.top/Article/details/gtwixvccgl.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgmorcccd.html

[H01] try / catch 基础
来源：http://dali.sysykeji.top/Article/details/gtckwcftsp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.0kj1m.cn/Article/details/gtmrhdcwpu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cashguo.top/Article/details/gtvqihrfuj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gtwooxmpnu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydrphozo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gtvxfycruz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jyoumei.cn/Article/details/gtwaydwofq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jianghu66.top/Article/details/gtpywppmlb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daria6918.cn/Article/details/gtqlrnnamd.html

[H02] finally / ensure 收尾
来源：http://dali.daria6918.cn/Article/details/gtwttukblu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jiagoushi.top/Article/details/gtmkcdkrdw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtnnrhdwtc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtvbmiunxh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtebomqocx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtpcmmtnbb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.wangshuangyany.cn/Article/details/gtilakxbfe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sysykeji.top/Article/details/gtrqzsflnr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtzilatjam.html

[H03] 主动抛出异常
来源：http://dali.yongpay.top/Article/details/gtolmzbjio.html

Py:   raise ValueError("错误信息")
来源：http://dali.havefunace.top/Article/details/gtbcspiwns.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtqjgumcwv.html

JS:   throw new Error("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtjpqqybom.html

TS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gttuxmqqqu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtxzmwiuao.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gzhubu.top/Article/details/gtdcvxfdxn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jlsjyb.cn/Article/details/gtdbwopklm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtqygcwvoy.html

[H04] 自定义异常类型
来源：http://dali.zhengqikj.top/Article/details/gthkliouho.html

Py:   class MyError(Exception): pass
来源：http://dali.guowangkeji.top/Article/details/gtieuoewbn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hammf.cn/Article/details/gtkexuqqxx.html

JS:   class MyError extends Error {}
来源：http://dali.hnxiangtu.top/Article/details/gtzljbvbuz.html

TS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gtihxvicjb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gtdeylghad.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdipsefpl.html

Ruby: class MyError < StandardError; end
来源：http://dali.sysykeji.top/Article/details/gtqaxaprye.html

C#:   class MyException : Exception {}
来源：http://dali.dashuyun.cn/Article/details/gtvuahhmwu.html

[H05] 捕获特定类型
来源：http://dali.jqgufenzy.top/Article/details/gtidocekga.html

Py:   except ValueError as e:
来源：http://dali.nanxuanxn.top/Article/details/gtpqqzkzvw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sxryk.cn/Article/details/gtrivvlobh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtkulqwxjo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.haohaochexian.top/Article/details/gtlffhepgy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhongyouzk.top/Article/details/gtpurjbmrl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xziqi.cn/Article/details/gtzhmjayhw.html

Ruby: rescue ArgumentError => e
来源：http://dali.yuxming.cn/Article/details/gtjbkznncu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.quarkkingdee.top/Article/details/gtjsftzwrt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.mhx1999.top/Article/details/gtqecgzgnk.html

Py:   value = d.get("k") or default
来源：http://dali.0kj1m.cn/Article/details/gtjyfczvzo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gtmxwrxnxb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gthntquueu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtggjawpey.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.dianchejie.cn/Article/details/gtfhsgjwsd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sysykeji.top/Article/details/gtixmloeol.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tanke756.top/Article/details/gtalpsqidt.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj202588.top/Article/details/gtwjudgctx.html

[H07] 断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gttkpvkhgu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258.top/Article/details/gtlejmpwet.html

PHP:  assert($x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtptubdrky.html

JS:   console.assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gtrtbcdozk.html

TS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gtzgvmwmcw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.0kj1m.cn/Article/details/gtmgpekhbe.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jyoumei.cn/Article/details/gtrhdmrqbt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tianlin.xyz/Article/details/gtzwzmchrr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtufbixbnd.html

[H08] 获取错误信息与堆栈
来源：http://dali.hywenlv.cn/Article/details/gtjayxpkkx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxinkj.top/Article/details/gtdzdruqjl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.birdmap.top/Article/details/gtqshtmgzp.html

JS:   e.message;  e.stack
来源：http://dali.jinqigfzy.top/Article/details/gtonbdozxe.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.0kj1m.cn/Article/details/gtsxrwbdtq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ehwqpu.com/Article/details/gtmukgfteh.html

Go:   err.Error()
来源：http://dali.cdnleiting.top/Article/details/gtjtmmmcnn.html

Ruby: e.message;  e.backtrace
来源：http://dali.yueranfly.top/Article/details/gtzuyciwvq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdiyjyoe.html

[H09] 带错误码的异常
来源：http://dali.yuxming.cn/Article/details/gtheibgief.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinghuilouyu.cn/Article/details/gthekbswlt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tanke756.top/Article/details/gttqorkehn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aizwys.cn/Article/details/gtnplkbahl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sweek.top/Article/details/gtaafvvpko.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hongshengwenyu.top/Article/details/gtgjrvklov.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhengqikj.top/Article/details/gtbyzerixv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tanke756.top/Article/details/gtamokyyji.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.bjfxy.top/Article/details/gtewhnkvvs.html

[H10] 资源自动释放
来源：http://dali.yj202588.top/Article/details/gtlcdxgayk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpefsidep.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.wangshuangyany.cn/Article/details/gtdagdnzrh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzvxgcwkb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gaohongyu789.top/Article/details/gtdcltcddh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj202588.top/Article/details/gtkaxrmarc.html

Go:   defer f.Close()
来源：http://dali.yongpay.top/Article/details/gtsbwympbl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zycfv.cn/Article/details/gtnurlqyki.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtiuxunlet.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gttdwtjbhy.html

I. 正则表达式
来源：http://dali.yuxming.cn/Article/details/gtocqqjlhr.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtuxbnkosv.html

[I01] 判断是否匹配
来源：http://dali.fengsongda.top/Article/details/gtzzcquwzu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jiagoushi.top/Article/details/gttgdntymp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtkhywqxnb.html

JS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gtmbksllsd.html

TS:   /\d+/.test(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtlitszkwv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cdnleiting.top/Article/details/gtkahlmlgy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.quarkkingdee.top/Article/details/gtlrtovlsn.html

Ruby: s.match?(/\d+/)
来源：http://dali.sxryk.cn/Article/details/gtcviuzlhy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yueranfly.top/Article/details/gtbrwpzonp.html

[I02] 提取所有匹配
来源：http://dali.jinqigufen.top/Article/details/gtrzhjrtiw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gzhubu.top/Article/details/gtmszxkttz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tanke756.top/Article/details/gtqtbjxdmh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tian-w.cn/Article/details/gtturavvai.html

TS:   s.match(/\d+/g)
来源：http://dali.gaohongyu789.top/Article/details/gthsnrtycy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yonumen.top/Article/details/gttrdtlzka.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gttivyglsq.html

Ruby: s.scan(/\d+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyckzicig.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtalnvxyqv.html

[I03] 提取捕获分组
来源：http://dali.xziqi.cn/Article/details/gtjyxtabsx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtnikoftwa.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jianghu66.top/Article/details/gtcsfgisol.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.guannengcc.top/Article/details/gtvpfxoxuc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shzxlz.cn/Article/details/gtthfqehmz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenzaomai.com/Article/details/gtfmxnbqmx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.meibo888.top/Article/details/gtnctitoew.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sxryk.cn/Article/details/gtpdkaiyxm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangshuangyany.cn/Article/details/gtaiwvsabw.html

[I04] 正则替换
来源：http://dali.sxryk.cn/Article/details/gtwqsoaqkg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jianghu66.top/Article/details/gtlufugeos.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtrtgkrbau.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.guannengcc.top/Article/details/gtlkftdlrc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guannengcc.top/Article/details/gtujwxtvzf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gtrzqmoyxi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gtwqtamrtk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ybcxt.top/Article/details/gtrdxqgtws.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuanzhike.top/Article/details/gtlljtjpkg.html

[I05] 按正则拆分
来源：http://dali.xylfe.cn/Article/details/gtkhhxtwov.html


<!-- 参考信息 -->