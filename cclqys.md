代发 wailian999

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtbxroadsr.html

TS:   path.extname("a.txt")
来源：http://dali.ivvv.top/Article/details/gtejokajkl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.vqdsnc.cn/Article/details/gtgutrzbrg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtynomlulu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtspuygptk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtzmblaxca.html

[F11] 复制与移动文件
来源：http://dali.jqgfzy.top/Article/details/gtsqadvrsf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtztdcpupc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.svipenyu.cn/Article/details/gtriwlxwxl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtxsuedgte.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtquxfqdqt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gtvabkgnfy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gaohongyu789.top/Article/details/gtxhifciht.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtffayzvqz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guowangkeji.top/Article/details/gtqkgkwmqp.html

[F12] CSV 读写
来源：http://dali.nanxuanxn.top/Article/details/gtlkntccvp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yueranfly.top/Article/details/gtpbmobnnv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sweek.top/Article/details/gtnqrqpoif.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sysykeji.top/Article/details/gtchpumzyv.html

TS:   // 同上
来源：http://dali.haohaochexian.top/Article/details/gtazbjpwql.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hongshengwenyu.top/Article/details/gtsbjhrpqe.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenzaomai.com/Article/details/gtwzfxqfas.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jianghu66.top/Article/details/gtsrqkjxxp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yongpay.top/Article/details/gtextvaior.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtjjkovmmp.html

G. 面向对象
来源：http://dali.gotoacloud.top/Article/details/gtcibfmwdz.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gthydvnint.html

[G01] 定义类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtetwrdldn.html

Py:   class User: pass
来源：http://dali.havefunace.top/Article/details/gtwlupmsre.html

PHP:  class User {}
来源：http://dali.gzhubu.top/Article/details/gtpurtssym.html

JS:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gtwlzajsmu.html

TS:   class User { name: string = ""; }
来源：http://dali.yj202588.top/Article/details/gtuagwfswa.html

Java: class User {}
来源：http://dali.ehwqpu.com/Article/details/gtnpbwhtrk.html

Go:   type User struct { Name string }
来源：http://dali.cucudq.cn/Article/details/gtkxlpdccy.html

Ruby: class User; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtamhmgowk.html

C#:   class User {}
来源：http://dali.redwolf501.top/Article/details/gtzybnonzs.html

[G02] 构造函数
来源：http://dali.zhixingplan.top/Article/details/gtdowcedwe.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.daria6918.cn/Article/details/gtrycouqfm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sxryk.cn/Article/details/gtayuegvmq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gttvvrsrnh.html

TS:   constructor(public name: string) {}
来源：http://dali.yuanzhike.top/Article/details/gtdtwbxrus.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj20258.top/Article/details/gtxbpouoeu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fzhhl.top/Article/details/gtekplglfa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tianlin.xyz/Article/details/gttoemktky.html

C#:   public User(string name) { Name = name; }
来源：http://dali.havefunace.top/Article/details/gtqvvxebrc.html

[G03] 实例属性
来源：http://dali.jianghu66.top/Article/details/gtzrqixomd.html

Py:   self.name = "x"
来源：http://dali.meibo888.top/Article/details/gtjcocnenm.html

PHP:  public string $name = "x";
来源：http://dali.guowangkeji.top/Article/details/gtupwogeud.html

JS:   this.name = "x";
来源：http://dali.xziqi.cn/Article/details/gtqndlurxj.html

TS:   name: string = "x";
来源：http://dali.9152youxi.cn/Article/details/gtuhtabuxy.html

Java: private String name;
来源：http://dali.ivvv.top/Article/details/gttkutiwgz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.guowangkeji.top/Article/details/gtovsyptzt.html

Ruby: @name = "x"
来源：http://dali.xuetiantiany.cn/Article/details/gtkyhpknoh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cucudq.cn/Article/details/gtyryqbffq.html

[G04] 定义方法
来源：http://dali.jqgufenzy.top/Article/details/gtvbdguscg.html

Py:   def greet(self): return self.name
来源：http://dali.pycfn.com/Article/details/gtlucdvbcq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gthrplsmrd.html

JS:   greet() { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtcgovsfxk.html

TS:   greet(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtjphwwjxj.html

Java: String greet() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtmchgcedc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtdzvmayrm.html

Ruby: def greet; @name; end
来源：http://dali.vqdsnc.cn/Article/details/gtmsmusfnz.html

C#:   public string Greet() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gtyqbqcjoi.html

[G05] 继承
来源：http://dali.nanxinkj.top/Article/details/gtiktpwpcr.html

Py:   class Admin(User): pass
来源：http://dali.jiagoushi.top/Article/details/gtrxplmmsc.html

PHP:  class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyzrhrirb.html

JS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gthrxwodrd.html

TS:   class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtmfahpvsr.html

Java: class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtyvswnziu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yonumen.top/Article/details/gtbphpohnd.html

Ruby: class Admin < User; end
来源：http://dali.sxryk.cn/Article/details/gtfdshotsu.html

C#:   class Admin : User {}
来源：http://dali.yuanzhike.top/Article/details/gtajddyxdp.html

[G06] 重写方法
来源：http://dali.yj20258888.top/Article/details/gtrglwpjha.html

Py:   def greet(self): return "admin"
来源：http://dali.yonumen.top/Article/details/gtletjqvqa.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtbthugjob.html

JS:   greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtbthkdzah.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtsnnvwwpw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtvjnijmzh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenzaomai.com/Article/details/gtmaquxxdr.html

Ruby: def greet; "admin"; end
来源：http://dali.9152youxi.cn/Article/details/gtaonrdpqk.html

C#:   public override string Greet() => "admin";
来源：http://dali.fzhhl.top/Article/details/gtfdpdwsln.html

[G07] 调用父类方法
来源：http://dali.quarkkingdee.top/Article/details/gttzwzbbbj.html

Py:   super().greet()
来源：http://dali.kuanghao11.cn/Article/details/gtwamzbwtc.html

PHP:  parent::greet();
来源：http://dali.daxiang520.top/Article/details/gtjistnsth.html

JS:   super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtbwrqehiz.html

TS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtjanpkdyi.html

Java: super.greet();
来源：http://dali.dianchejie.cn/Article/details/gtcmrhwdzk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.guowangkeji.top/Article/details/gtcskdqiyf.html

Ruby: super
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhwbznpk.html

C#:   base.Greet();
来源：http://dali.kuanghao11.cn/Article/details/gtwifberrt.html

[G08] 静态方法与属性
来源：http://dali.svipenyu.cn/Article/details/gtiynbzhyk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tianlin.xyz/Article/details/gtxuunkken.html

PHP:  public static function f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtuwtnptrx.html

JS:   static f() {}
来源：http://dali.dianchejie.cn/Article/details/gtvmiygdwr.html

TS:   static f(): void {}
来源：http://dali.quarkkingdee.top/Article/details/gtfholfkml.html

Java: static void f() {}
来源：http://dali.hysaishi.cn/Article/details/gtblzljpxx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yonumen.top/Article/details/gtvvojuaca.html

Ruby: def self.f; end
来源：http://dali.xuanzx.com/Article/details/gtnklidhrm.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gtqdptlnsn.html

[G09] 接口 / 抽象类
来源：http://dali.chenlongwang.top/Article/details/gtqyktvqhw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrhzegkz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtndpieevl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj202588.top/Article/details/gtynzyfbmy.html

TS:   interface Shape { area(): number; }
来源：http://dali.nwbrower.top/Article/details/gtmqqawquh.html

Java: interface Shape { double area(); }
来源：http://dali.fzhhl.top/Article/details/gtwbohrkld.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigufen.top/Article/details/gtnysmnjkg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.meibo888.top/Article/details/gtweguembp.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhongyouzk.top/Article/details/gtwffyaltb.html

[G10] 访问控制
来源：http://dali.gogol.net.cn/Article/details/gtrqyyxrew.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tian-w.cn/Article/details/gtxiuirgtt.html

PHP:  public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gtnirpruyd.html

JS:   #private 字段；其余公开
来源：http://dali.cashguo.top/Article/details/gtohftbjpa.html

TS:   public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gtlfjguopq.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangtech.top/Article/details/gtcethhvss.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fengsongda.top/Article/details/gtpifmadqe.html

Ruby: public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gtdrfltzra.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangtech.top/Article/details/gtyjyrvhkh.html

[G11] getter / setter
来源：http://dali.gzhubu.top/Article/details/gtfvdhlxjl.html

Py:   @property 与 @x.setter
来源：http://dali.hywenlv.cn/Article/details/gtxrhjvwln.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtinqggogr.html

JS:   get name() { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gtuljhybrs.html

TS:   get name(): string { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzwhqliwu.html

Java: public String getName() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtmfaafjwl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gttuibiflg.html

Ruby: attr_accessor :name
来源：http://dali.shzxlz.cn/Article/details/gtrlhbdidd.html

C#:   public string Name { get; set; }
来源：http://dali.jiagoushi.top/Article/details/gtyvpbtscv.html

[G12] 对象转字符串
来源：http://dali.zycfv.cn/Article/details/gtuqhmorme.html

Py:   def __str__(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gtyytgzafc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtnnqzorno.html

JS:   toString() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtiuwdifpe.html

TS:   toString(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtiogvacot.html

Java: @Override public String toString() { return name; }
来源：http://dali.smart0.xyz/Article/details/gtepbpaott.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gtzucbnqyt.html

Ruby: def to_s; @name; end
来源：http://dali.shuidangran.top/Article/details/gtnskfyxth.html

C#:   public override string ToString() => Name;
来源：http://dali.shuidangran.top/Article/details/gtzpnuhfiu.html

[G13] 判断对象类型
来源：http://dali.andypj.xyz/Article/details/gtiziktrmv.html

Py:   isinstance(u, User)
来源：http://dali.sysykeji.top/Article/details/gtwvsgwvll.html

PHP:  $u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtttunivge.html

JS:   u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtubwyizyh.html

TS:   u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtkcjkgyfm.html

Java: u instanceof User
来源：http://dali.tanke756.top/Article/details/gtoxdpzszx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuanzx.com/Article/details/gttjjxkmte.html

Ruby: u.is_a?(User)
来源：http://dali.tianlin.xyz/Article/details/gtovanqona.html

C#:   u is User
来源：http://dali.yueranfly.top/Article/details/gttzccbfdw.html

[G14] 数据类 / record
来源：http://dali.hammf.cn/Article/details/gtrefrnbyo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guowangkeji.top/Article/details/gtwfezyqjv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.snrcjt.cn/Article/details/gtiwqszaqn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yongpay.top/Article/details/gtvxusdjmo.html

TS:   type User = { name: string; age: number };
来源：http://dali.daxiang520.top/Article/details/gtuchpjbsk.html

Java: record User(String name, int age) {}
来源：http://dali.hnqzz.top/Article/details/gtitcassgi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ybcxt.top/Article/details/gtlujmwdud.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yueranfly.top/Article/details/gtromtxnqt.html

C#:   record User(string Name, int Age);
来源：http://dali.aibaodan.cn/Article/details/gtdpkanxfm.html

[G15] 枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbcwxdka.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.smart0.xyz/Article/details/gthbxxuvbo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guannengcc.top/Article/details/gtjgzgmqss.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daxiang520.top/Article/details/gtxfnrjeqa.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ybcxt.top/Article/details/gtjwjkgjun.html

Java: enum Color { RED, GREEN }
来源：http://dali.mhx1999.top/Article/details/gtqnovwzjt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dianchejie.cn/Article/details/gtobsxbejz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guannengcc.top/Article/details/gtrqfbguqa.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnstporvp.html

[G16] 对象转数组 / 字典
来源：http://dali.xziqi.cn/Article/details/gtdmavszhq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.iojbl.cn/Article/details/gtavzkokfm.html

PHP:  get_object_vars($obj);
来源：http://dali.shanyushiyangtech.top/Article/details/gtycjeawnf.html

JS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gthmnlkxom.html

TS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gtyknhxqgz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.316326.xyz/Article/details/gtkmlrsdlt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yueranfly.top/Article/details/gtfvbnlhhr.html

Ruby: obj.instance_variables
来源：http://dali.dianchejie.cn/Article/details/gtulsvragm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnxiangtu.top/Article/details/gtrtodgelw.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtonljtzps.html

H. 异常与错误处理
来源：http://dali.jiagoushi.top/Article/details/gtpnlznxnj.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtqkizyutd.html

[H01] try / catch 基础
来源：http://dali.hnxiangtu.top/Article/details/gtoanzzupb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ybcxt.top/Article/details/gtdfdfxxcu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daria6918.cn/Article/details/gtbopdqlxu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gttmycjbww.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gtwcueonia.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.quarkkingdee.top/Article/details/gtsesaagmk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.9152youxi.cn/Article/details/gtlrzreafb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcipfxmc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.mhx1999.top/Article/details/gtntoaefuf.html

[H02] finally / ensure 收尾
来源：http://dali.tanke756.top/Article/details/gtcwfhucgt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hfpthk.cn/Article/details/gtdyxginzi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtxzkyjyfb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtaebivkan.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtsgujsxwy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtrgamrgwt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cashguo.top/Article/details/gtobbpqgqe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj20258888.top/Article/details/gttnsmwusr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtmeebmlgp.html

[H03] 主动抛出异常
来源：http://dali.pycfn.com/Article/details/gtumdhakom.html

Py:   raise ValueError("错误信息")
来源：http://dali.andypj.xyz/Article/details/gtbatuvbcn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtyzcncvpu.html

JS:   throw new Error("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtcczmpoyj.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtrpqwsfqz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtcjivxhjn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.guannengcc.top/Article/details/gtcrkmanwc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gogol.net.cn/Article/details/gtxcbwabrf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtfapuhbss.html

[H04] 自定义异常类型
来源：http://dali.yj20258888.top/Article/details/gtzwglkeww.html

Py:   class MyError(Exception): pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrxktiud.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aizwys.cn/Article/details/gtpduslril.html

JS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtioqndewg.html

TS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gtpbmrnswi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daxiang520.top/Article/details/gtjugqbmpq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxinkj.top/Article/details/gtiejrfobx.html

Ruby: class MyError < StandardError; end
来源：http://dali.hfpthk.cn/Article/details/gtivtdgdbd.html

C#:   class MyException : Exception {}
来源：http://dali.aizwys.cn/Article/details/gtjadlqajm.html

[H05] 捕获特定类型
来源：http://dali.cashguo.top/Article/details/gtamwjeisu.html

Py:   except ValueError as e:
来源：http://dali.zhaomingkeji.xyz/Article/details/gtatnvrtjf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aibaodan.cn/Article/details/gtenbmzpct.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gtmgxnsmpz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsmwxepck.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ydzc1.top/Article/details/gtdeebdmjh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jiagoushi.top/Article/details/gtruakrpup.html

Ruby: rescue ArgumentError => e
来源：http://dali.guowangkeji.top/Article/details/gtfcwtdaui.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xziqi.cn/Article/details/gtmfghgsfr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.redwolf501.top/Article/details/gtckmlllbk.html

Py:   value = d.get("k") or default
来源：http://dali.yongpay.top/Article/details/gtpwlntbnm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gtpuzffqig.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjcneeah.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnqzz.top/Article/details/gtiuyplbir.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sysykeji.top/Article/details/gtcsjmymfs.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sufxvd.cn/Article/details/gtitllkmdr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhiwuduotai.top/Article/details/gtejoztwku.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxkcmrtg.html

[H07] 断言
来源：http://dali.zycfv.cn/Article/details/gtddkrfkbd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tian-w.cn/Article/details/gtkunkueok.html

PHP:  assert($x > 0);
来源：http://dali.c1oappe.top/Article/details/gtrtfyguyl.html

JS:   console.assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gtquerqkxs.html

TS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtqcppzxmw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cheryme.top/Article/details/gtlcdwnsco.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yuanzhike.top/Article/details/gtcdfluwof.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.birdmap.top/Article/details/gtjqtmghpo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gtnzixvpno.html

[H08] 获取错误信息与堆栈
来源：http://dali.hywenlv.cn/Article/details/gtzdvzdjrl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.feifeiyinyue.top/Article/details/gtawfgmnaf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.guowangkeji.top/Article/details/gtsuxizyhc.html

JS:   e.message;  e.stack
来源：http://dali.0kj1m.cn/Article/details/gtcanzzniy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgfzy.top/Article/details/gtpuxzaobn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinghuilouyu.cn/Article/details/gtilmjofqg.html

Go:   err.Error()
来源：http://dali.jqgfzy.top/Article/details/gtqaufhdin.html

Ruby: e.message;  e.backtrace
来源：http://dali.zdqjudy.top/Article/details/gtxwxoksyu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigfzy.top/Article/details/gtiwqfuwcy.html

[H09] 带错误码的异常
来源：http://dali.jiagoushi.top/Article/details/gtvwhhpzod.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hysaishi.cn/Article/details/gtlqjcbzcb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gtlxlprtrd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fengsongda.top/Article/details/gtmucqyatn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.haohaochexian.top/Article/details/gtchvheyib.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.andypj.xyz/Article/details/gtslgqzizw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.quarkkingdee.top/Article/details/gtjtevrnjo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zdqjudy.top/Article/details/gtfktzxonf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.aizwys.cn/Article/details/gtrfbljvsa.html

[H10] 资源自动释放
来源：http://dali.quarkkingdee.top/Article/details/gtevkkttky.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.fzhhl.top/Article/details/gtvmlulmuj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sysykeji.top/Article/details/gtdvrhwyyc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cdnleiting.top/Article/details/gtxvwpslqi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gtuawxovpw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.vqdsnc.cn/Article/details/gtudpgnzop.html

Go:   defer f.Close()
来源：http://dali.zhixingplan.top/Article/details/gtimzcgpjn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gzhubu.top/Article/details/gtdkxndxeq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsdajenid.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtdbobjgkf.html

I. 正则表达式
来源：http://dali.hammf.cn/Article/details/gtebpfyumo.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtirlzkhll.html

[I01] 判断是否匹配
来源：http://dali.sxryk.cn/Article/details/gtmriasevc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gttcwzjxxx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtpeyvbnhe.html

JS:   /\d+/.test(s)
来源：http://dali.sysykeji.top/Article/details/gtenlufuyw.html

TS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gtipmgjyfc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hywenlv.cn/Article/details/gtckmdyaku.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tanke756.top/Article/details/gtgjvwiqvb.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gtpsaohysm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.haohaochexian.top/Article/details/gtwdbbhhbv.html

[I02] 提取所有匹配
来源：http://dali.yj20258888.top/Article/details/gtlyweqxns.html

Py:   re.findall(r"\d+", s)
来源：http://dali.snrcjt.cn/Article/details/gtaskqebjf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.redwolf501.top/Article/details/gtqwtnffah.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.aibaodan.cn/Article/details/gtwvdjzkuw.html

TS:   s.match(/\d+/g)
来源：http://dali.tanke756.top/Article/details/gtmhezypnu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xinyue.icu/Article/details/gtxbsxbtzp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gtboyhnbay.html

Ruby: s.scan(/\d+/)
来源：http://dali.cashguo.top/Article/details/gtazajuacw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmrvrjpti.html

[I03] 提取捕获分组
来源：http://dali.zhoulong.xyz/Article/details/gtcdgrzvcj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.316326.xyz/Article/details/gtutcrgdbz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tian-w.cn/Article/details/gtclvvbfff.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ybcxt.top/Article/details/gtytxkpiif.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.daxiang520.top/Article/details/gtcmjfjlqh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.0kj1m.cn/Article/details/gtvsvcnaja.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cheryme.top/Article/details/gtpmwkfxxz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nwbrower.top/Article/details/gtofmtpanq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shuidangran.top/Article/details/gtsbwnshse.html

[I04] 正则替换
来源：http://dali.jlsjyb.cn/Article/details/gthahzlbyx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.0kj1m.cn/Article/details/gthftxkabz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxinkj.top/Article/details/gttixlyjgd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtiuhlskou.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtbbugoioa.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.bjfxy.top/Article/details/gtroafbpav.html


<!-- 参考信息 -->