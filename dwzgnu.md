代发 wailian999

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtacomdinv.html

TS:   path.extname("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtgatrkubp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.haohaochexian.top/Article/details/gtcdcehgtw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtxkstbzcf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtmpufvmgu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtnayugvnu.html

[F11] 复制与移动文件
来源：http://dali.haohaochexian.top/Article/details/gtfaycxfae.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtwnuptdwe.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.birdmap.top/Article/details/gtxrmastlr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtcxdwibfc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtkllqaujw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yueranfly.top/Article/details/gtjinbnveh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jqgufenzy.top/Article/details/gtbhyvsoad.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtuzvitcng.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nwbrower.top/Article/details/gtxzzqcdlk.html

[F12] CSV 读写
来源：http://dali.havefunace.top/Article/details/gttbkmriar.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuanzx.com/Article/details/gtuikpidiq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nanxinkj.top/Article/details/gtepskmqsh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gogol.net.cn/Article/details/gtygczhszo.html

TS:   // 同上
来源：http://dali.yuxming.cn/Article/details/gtcdjgurjg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hywenlv.cn/Article/details/gtqwhzaxcv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sweek.top/Article/details/gtleuzlsty.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fengsongda.top/Article/details/gtclbdyrrf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangshuangyany.cn/Article/details/gtfzmvfwwc.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gthvsvxbbp.html

G. 面向对象
来源：http://dali.daria6918.cn/Article/details/gtlqbhbuhg.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtftscqhqp.html

[G01] 定义类
来源：http://dali.jianghu66.top/Article/details/gtuskoinqh.html

Py:   class User: pass
来源：http://dali.svipenyu.cn/Article/details/gtwkvkcwor.html

PHP:  class User {}
来源：http://dali.yj20258.top/Article/details/gtchcdcjmm.html

JS:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gtcqmskfdy.html

TS:   class User { name: string = ""; }
来源：http://dali.zycfv.cn/Article/details/gtobthlgma.html

Java: class User {}
来源：http://dali.yonumen.top/Article/details/gtamhqrlgx.html

Go:   type User struct { Name string }
来源：http://dali.nanxuanxn.top/Article/details/gtvyfvwsnc.html

Ruby: class User; end
来源：http://dali.bjfxy.top/Article/details/gtodrstgdr.html

C#:   class User {}
来源：http://dali.nwbrower.top/Article/details/gtrqfannrj.html

[G02] 构造函数
来源：http://dali.birdmap.top/Article/details/gtyvhnsyau.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hongshengwenyu.top/Article/details/gtyksqfvdz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sweek.top/Article/details/gtbzakuaok.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gtapgrdjad.html

TS:   constructor(public name: string) {}
来源：http://dali.shuidangran.top/Article/details/gtsdepabgd.html

Java: User(String name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gtjmswbvdo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.smart0.xyz/Article/details/gtsmycvipx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.kuanghao11.cn/Article/details/gtmvefwwaw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtzxjmluot.html

[G03] 实例属性
来源：http://dali.zhengqikj.top/Article/details/gtprqfdjlx.html

Py:   self.name = "x"
来源：http://dali.haohaochexian.top/Article/details/gtiiuctrik.html

PHP:  public string $name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtjsxxvkgu.html

JS:   this.name = "x";
来源：http://dali.hammf.cn/Article/details/gttddhwoeu.html

TS:   name: string = "x";
来源：http://dali.yueranfly.top/Article/details/gtanxweuen.html

Java: private String name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrjcnsqk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnqzz.top/Article/details/gtlcebfghi.html

Ruby: @name = "x"
来源：http://dali.yuanzhike.top/Article/details/gtmyguuaut.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yonumen.top/Article/details/gtmuljwsjh.html

[G04] 定义方法
来源：http://dali.c1oappe.top/Article/details/gtjptyochc.html

Py:   def greet(self): return self.name
来源：http://dali.sysykeji.top/Article/details/gtktevqflv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtgzpkxdsn.html

JS:   greet() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtwkghippt.html

TS:   greet(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtthbwrhmy.html

Java: String greet() { return name; }
来源：http://dali.andypj.xyz/Article/details/gtavdzthnr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gtgvqqldve.html

Ruby: def greet; @name; end
来源：http://dali.chenzaomai.com/Article/details/gteswpudzq.html

C#:   public string Greet() => Name;
来源：http://dali.ydzc1.top/Article/details/gtsepyoqwx.html

[G05] 继承
来源：http://dali.havefunace.top/Article/details/gtkpakdgmw.html

Py:   class Admin(User): pass
来源：http://dali.mhx1999.top/Article/details/gtmibgrodt.html

PHP:  class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gteevxflaw.html

JS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtumuognzb.html

TS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtbkpeiaqh.html

Java: class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtrnsbzwae.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xziqi.cn/Article/details/gtgpcyztpz.html

Ruby: class Admin < User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrvlnimp.html

C#:   class Admin : User {}
来源：http://dali.jinqigufen.top/Article/details/gterxjzers.html

[G06] 重写方法
来源：http://dali.fengsongda.top/Article/details/gtofnohbqh.html

Py:   def greet(self): return "admin"
来源：http://dali.fengsongda.top/Article/details/gttbplsvfn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtmyovzcgz.html

JS:   greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtisakqdqj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gthkrxvkrb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtqpmazdqh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhiwuduotai.top/Article/details/gtxxigfpds.html

Ruby: def greet; "admin"; end
来源：http://dali.wangshuangyany.cn/Article/details/gtxxfhyclg.html

C#:   public override string Greet() => "admin";
来源：http://dali.mhx1999.top/Article/details/gtkpvrlkfo.html

[G07] 调用父类方法
来源：http://dali.yuxming.cn/Article/details/gtpznzplyq.html

Py:   super().greet()
来源：http://dali.cqqwz.cn/Article/details/gtupwxghor.html

PHP:  parent::greet();
来源：http://dali.cashguo.top/Article/details/gtqjuqzhna.html

JS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gtfpsiztrs.html

TS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gtmaesycuu.html

Java: super.greet();
来源：http://dali.mhx1999.top/Article/details/gtlhtlgslm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxtxlcvf.html

Ruby: super
来源：http://dali.yonumen.top/Article/details/gthayabuqr.html

C#:   base.Greet();
来源：http://dali.tianlin.xyz/Article/details/gttjcgywvk.html

[G08] 静态方法与属性
来源：http://dali.tianlin.xyz/Article/details/gtohbkayui.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.snrcjt.cn/Article/details/gtrqrtfmlk.html

PHP:  public static function f() {}
来源：http://dali.daria6918.cn/Article/details/gtszffewpp.html

JS:   static f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbvvdpoi.html

TS:   static f(): void {}
来源：http://dali.daxiang520.top/Article/details/gtqiznfyio.html

Java: static void f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtikxcpmof.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.redwolf501.top/Article/details/gtsicrzbbq.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhjalyki.html

C#:   public static void F() {}
来源：http://dali.meibo888.top/Article/details/gtwkikfxyh.html

[G09] 接口 / 抽象类
来源：http://dali.sweek.top/Article/details/gtktvybrwu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sysykeji.top/Article/details/gtstnkifqe.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.smart0.xyz/Article/details/gttnhsjsnd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shzxlz.cn/Article/details/gthkndwajs.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxinkj.top/Article/details/gtneolrehk.html

Java: interface Shape { double area(); }
来源：http://dali.ydzc1.top/Article/details/gtjzdymyhy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jqgufenzy.top/Article/details/gttmuqmfac.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxytxgrbg.html

C#:   interface IShape { double Area(); }
来源：http://dali.daxiang520.top/Article/details/gtexlmxtlf.html

[G10] 访问控制
来源：http://dali.kuanghao11.cn/Article/details/gtsuvhzdqh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xuetiantiany.cn/Article/details/gtzwkwqcgl.html

PHP:  public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbcvwgcj.html

JS:   #private 字段；其余公开
来源：http://dali.iojbl.cn/Article/details/gtcvwdtxws.html

TS:   public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtrkazxahl.html

Java: public / protected / private / 默认包级
来源：http://dali.hysaishi.cn/Article/details/gtbucardbi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenjidiqi.icu/Article/details/gtwouzqvqz.html

Ruby: public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsojkzdvl.html

C#:   public / protected / private / internal
来源：http://dali.yuxming.cn/Article/details/gtfsdqshhb.html

[G11] getter / setter
来源：http://dali.feifeiyinyue.top/Article/details/gthpduicaz.html

Py:   @property 与 @x.setter
来源：http://dali.wangshuangyany.cn/Article/details/gtygeflsxq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gtovbjvwjy.html

JS:   get name() { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gtrcoyqbca.html

TS:   get name(): string { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gtlctrrdfv.html

Java: public String getName() { return name; }
来源：http://dali.xylfe.cn/Article/details/gtrsusfxal.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gtmjsfndfn.html

Ruby: attr_accessor :name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtekxnlhdm.html

C#:   public string Name { get; set; }
来源：http://dali.xuetiantiany.cn/Article/details/gtfnlfarjb.html

[G12] 对象转字符串
来源：http://dali.vqdsnc.cn/Article/details/gtopenoesi.html

Py:   def __str__(self): return self.name
来源：http://dali.9152youxi.cn/Article/details/gtiflowesk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gtbnfidohi.html

JS:   toString() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtdvlgikym.html

TS:   toString(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtadskxxpl.html

Java: @Override public String toString() { return name; }
来源：http://dali.yueranfly.top/Article/details/gtbsdpyngt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtyahmxbpj.html

Ruby: def to_s; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gteafxrrnw.html

C#:   public override string ToString() => Name;
来源：http://dali.zhixingplan.top/Article/details/gtzbfavala.html

[G13] 判断对象类型
来源：http://dali.zycfv.cn/Article/details/gtlkincxnp.html

Py:   isinstance(u, User)
来源：http://dali.ybcxt.top/Article/details/gtmwyrwxhe.html

PHP:  $u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtondtguwd.html

JS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtgwvwcnab.html

TS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gthozuqnzj.html

Java: u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtsxucprmv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.daxiang520.top/Article/details/gtbykgjzae.html

Ruby: u.is_a?(User)
来源：http://dali.shuidangran.top/Article/details/gtxemuymri.html

C#:   u is User
来源：http://dali.ydzc1.top/Article/details/gtirnfkzht.html

[G14] 数据类 / record
来源：http://dali.guannengcc.top/Article/details/gtgehliijg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhengqikj.top/Article/details/gtptsmedeg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shuidangran.top/Article/details/gtawxgmixi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.haohaochexian.top/Article/details/gtfrqmahhm.html

TS:   type User = { name: string; age: number };
来源：http://dali.yonumen.top/Article/details/gtmbxybfwe.html

Java: record User(String name, int age) {}
来源：http://dali.hywenlv.cn/Article/details/gtliqksxnq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenlongwang.top/Article/details/gtqgcguksu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yongpay.top/Article/details/gtkshlupkt.html

C#:   record User(string Name, int Age);
来源：http://dali.jqgfzy.top/Article/details/gthemfpfdx.html

[G15] 枚举
来源：http://dali.cucudq.cn/Article/details/gtqhtdxudz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhiwuduotai.top/Article/details/gtrpuqzuee.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ehwqpu.com/Article/details/gtsgeyhnpe.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.9152youxi.cn/Article/details/gtfaydhdjx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gtvajqrlxg.html

Java: enum Color { RED, GREEN }
来源：http://dali.dashuyun.cn/Article/details/gtrkxockao.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dianchejie.cn/Article/details/gtkopnjijw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yangfankeji.com/Article/details/gtprrgnpji.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.mhx1999.top/Article/details/gtcnzgbgjg.html

[G16] 对象转数组 / 字典
来源：http://dali.zhongyouzk.top/Article/details/gtgyhtcjwy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hywenlv.cn/Article/details/gtjyxtapab.html

PHP:  get_object_vars($obj);
来源：http://dali.hysaishi.cn/Article/details/gtkxpofgyz.html

JS:   Object.entries(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtsurqwtrr.html

TS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gtxbymgmvh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.haohaochexian.top/Article/details/gtuctogsii.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.9152youxi.cn/Article/details/gttspkhskx.html

Ruby: obj.instance_variables
来源：http://dali.yueranfly.top/Article/details/gtersjclbb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gtongmhxla.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtrwetnplh.html

H. 异常与错误处理
来源：http://dali.yj202588.top/Article/details/gtqrohkgsw.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtagkcenwj.html

[H01] try / catch 基础
来源：http://dali.shuidangran.top/Article/details/gtzfciigtr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tianlin.xyz/Article/details/gtnpfoztyh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhixingplan.top/Article/details/gtlcectgdk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gtpbzcegxa.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gtxoccpipq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nanxinkj.top/Article/details/gtndoywbkx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxinkj.top/Article/details/gtyqshncyc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xuetiantiany.cn/Article/details/gtaxbflnid.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.vqdsnc.cn/Article/details/gtgaxqotzp.html

[H02] finally / ensure 收尾
来源：http://dali.daria6918.cn/Article/details/gttnlexidz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xziqi.cn/Article/details/gtyhbejbnu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtdtkurtoe.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtcnjepdld.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtthzhmnrh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtrlhfkmui.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.vqdsnc.cn/Article/details/gtajayywoe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cashguo.top/Article/details/gtwzbrdjsd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtujyjdgwl.html

[H03] 主动抛出异常
来源：http://dali.gotoacloud.top/Article/details/gtjqhtprcp.html

Py:   raise ValueError("错误信息")
来源：http://dali.yueranfly.top/Article/details/gtrkmjajes.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtqllukqai.html

JS:   throw new Error("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtxhjvrdev.html

TS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtecixeotf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtrguobhzf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhongyouzk.top/Article/details/gtnralsiyq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.mhx1999.top/Article/details/gthkimoqit.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtevihxqfd.html

[H04] 自定义异常类型
来源：http://dali.hywenlv.cn/Article/details/gtuokitchy.html

Py:   class MyError(Exception): pass
来源：http://dali.pycfn.com/Article/details/gttaejflew.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.c1oappe.top/Article/details/gtaskrhtku.html

JS:   class MyError extends Error {}
来源：http://dali.aizwys.cn/Article/details/gtnfpozzxc.html

TS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gtenmpnvyg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gtgfjiemvd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xuetiantiany.cn/Article/details/gtlspqqjsx.html

Ruby: class MyError < StandardError; end
来源：http://dali.yongpay.top/Article/details/gtoqvcxlzv.html

C#:   class MyException : Exception {}
来源：http://dali.yongpay.top/Article/details/gtagcyootp.html

[H05] 捕获特定类型
来源：http://dali.sxryk.cn/Article/details/gtseszfqsk.html

Py:   except ValueError as e:
来源：http://dali.yonumen.top/Article/details/gtdgccssys.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sweek.top/Article/details/gtvowwdxsc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tian-w.cn/Article/details/gtnnpwezus.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gtmdgkvrfr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenjidiqi.icu/Article/details/gteykodyic.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgfzy.top/Article/details/gtemyelclz.html

Ruby: rescue ArgumentError => e
来源：http://dali.sysykeji.top/Article/details/gtjjolypwo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ppjwa.cn/Article/details/gtwnwgfysh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fengsongda.top/Article/details/gtliqrifmd.html

Py:   value = d.get("k") or default
来源：http://dali.yvedp.cn/Article/details/gttvojfgbd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hongshengwenyu.top/Article/details/gtkmxfkabc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gtkwbslogd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgfzy.top/Article/details/gtgdadzzyc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.svipenyu.cn/Article/details/gtvddactdz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hysaishi.cn/Article/details/gtjjvtenws.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hywenlv.cn/Article/details/gtupaladsa.html

C#:   obj?.A?.B ?? default
来源：http://dali.andypj.xyz/Article/details/gtjgyapcli.html

[H07] 断言
来源：http://dali.fengsongda.top/Article/details/gtvtenyyae.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aizwys.cn/Article/details/gtlqaclxgu.html

PHP:  assert($x > 0);
来源：http://dali.yongpay.top/Article/details/gtrwvtzjws.html

JS:   console.assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gtcjyweneh.html

TS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gtqykzdxdc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jianghu66.top/Article/details/gtrqhrcdrs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daria6918.cn/Article/details/gtnocyqxqm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hammf.cn/Article/details/gtrmxuhmdz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gtazamoste.html

[H08] 获取错误信息与堆栈
来源：http://dali.birdmap.top/Article/details/gtprbryqro.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuxming.cn/Article/details/gtaqpfmabk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhixingplan.top/Article/details/gtysjgvpuh.html

JS:   e.message;  e.stack
来源：http://dali.chenlongwang.top/Article/details/gtmviesdcl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tanke756.top/Article/details/gtgdlvrcne.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.iojbl.cn/Article/details/gtgbchjzdb.html

Go:   err.Error()
来源：http://dali.xuanzx.com/Article/details/gtztjasavj.html

Ruby: e.message;  e.backtrace
来源：http://dali.hammf.cn/Article/details/gtbreyfwwa.html

C#:   e.Message;  e.StackTrace
来源：http://dali.andypj.xyz/Article/details/gtvziualak.html

[H09] 带错误码的异常
来源：http://dali.jinqigufen.top/Article/details/gtsftbcugm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hongshengwenyu.top/Article/details/gtxwvelizl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.316326.xyz/Article/details/gtbdfdvjch.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shangyingyoupin.top/Article/details/gtodllubau.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yangfankeji.com/Article/details/gtbqrvefnl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hfpthk.cn/Article/details/gtwxlnvmyo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyitmhsjz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shzxlz.cn/Article/details/gtswmghrrs.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ivvv.top/Article/details/gtwkfrwctx.html

[H10] 资源自动释放
来源：http://dali.guowangkeji.top/Article/details/gtcppusnje.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daxiang520.top/Article/details/gtxxrboqqi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tianlin.xyz/Article/details/gtgsrzwxad.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shuidangran.top/Article/details/gtelmqdwpw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.quarkkingdee.top/Article/details/gtkmzduxqd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.haohaochexian.top/Article/details/gtmqvjpnvf.html

Go:   defer f.Close()
来源：http://dali.jqgfzy.top/Article/details/gtibbwdhya.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.guannengcc.top/Article/details/gtjddljzgj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sweek.top/Article/details/gtsllkgiie.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtuweqgazv.html

I. 正则表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtmkzjruwf.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtcbzodygp.html

[I01] 判断是否匹配
来源：http://dali.smart0.xyz/Article/details/gtcltcalgz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cucudq.cn/Article/details/gttlaicemu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hammf.cn/Article/details/gteprzwhvy.html

JS:   /\d+/.test(s)
来源：http://dali.xinyue.icu/Article/details/gtprndophb.html

TS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gtjphokyih.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhixingplan.top/Article/details/gtrowkkjet.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtpubmlkxh.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj20258888.top/Article/details/gtjwjgatvf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhoulong.xyz/Article/details/gtqibddmiy.html

[I02] 提取所有匹配
来源：http://dali.hfpthk.cn/Article/details/gtkhqmbsjb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj202588.top/Article/details/gtgpqcwtnh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cashguo.top/Article/details/gtkqgchcdx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.316326.xyz/Article/details/gtucvxhsas.html

TS:   s.match(/\d+/g)
来源：http://dali.jinqigfzy.top/Article/details/gtacueqfbk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.fengsongda.top/Article/details/gtgdusucvc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ybcxt.top/Article/details/gtntyulotp.html

Ruby: s.scan(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gtxiqtzmwk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtbktethne.html

[I03] 提取捕获分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgtohggcg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sxryk.cn/Article/details/gtvajvzorc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinqigufen.top/Article/details/gtiuzkpatu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.mhx1999.top/Article/details/gtjhbugddr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.haohaochexian.top/Article/details/gtedqdfvcg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258.top/Article/details/gtgzmkarar.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinqigufen.top/Article/details/gtfndeutbo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinqigfzy.top/Article/details/gtftdpceax.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.kuanghao11.cn/Article/details/gtgqgriuyx.html

[I04] 正则替换
来源：http://dali.hnqzz.top/Article/details/gtcfjrpiiw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sxryk.cn/Article/details/gtlsputvjp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zycfv.cn/Article/details/gtksvlsynr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtcfohpjdo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shuidangran.top/Article/details/gtjhddxytp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gtldedpdii.html


<!-- 参考信息 -->