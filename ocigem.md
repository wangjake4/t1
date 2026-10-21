代发 wailian999

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtdpzxtebs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtgswwcmxu.html

[F11] 复制与移动文件
来源：http://dali.daxiang520.top/Article/details/gtillqoxhq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtcazeybsu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.andypj.xyz/Article/details/gtarmjaxhw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gtdkxfxyrq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtsgjahuqr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tianlin.xyz/Article/details/gtbpdqrosn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhengqikj.top/Article/details/gtuciqrnve.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtzmhrevcj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.vqdsnc.cn/Article/details/gtqkbxvnvh.html

[F12] CSV 读写
来源：http://dali.jiagoushi.top/Article/details/gtbcetxlhs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sxryk.cn/Article/details/gtuembifjc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.redwolf501.top/Article/details/gtgvblnibu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xuanzx.com/Article/details/gtkexkpjed.html

TS:   // 同上
来源：http://dali.ydzc1.top/Article/details/gtsvhbwrda.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.bjfxy.top/Article/details/gtonmqkkos.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gthpbokhbg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gaohongyu789.top/Article/details/gthjmfysnt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shangyingyoupin.top/Article/details/gtehamcppn.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtiurrbfby.html

G. 面向对象
来源：http://dali.yanxiufei.cn/Article/details/gtaethnzwa.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtifrsqiog.html

[G01] 定义类
来源：http://dali.tanke756.top/Article/details/gtrnoproxv.html

Py:   class User: pass
来源：http://dali.shangyingyoupin.top/Article/details/gtgjbinffr.html

PHP:  class User {}
来源：http://dali.nanxuanxn.top/Article/details/gttlenozdt.html

JS:   class User {}
来源：http://dali.hnqzz.top/Article/details/gthzjdkobi.html

TS:   class User { name: string = ""; }
来源：http://dali.wangshuangyany.cn/Article/details/gtojsbgajq.html

Java: class User {}
来源：http://dali.gotoacloud.top/Article/details/gttypfexqz.html

Go:   type User struct { Name string }
来源：http://dali.9152youxi.cn/Article/details/gtkmmhfsvp.html

Ruby: class User; end
来源：http://dali.daria6918.cn/Article/details/gtetyvhjte.html

C#:   class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtaifqdvxz.html

[G02] 构造函数
来源：http://dali.jlsjyb.cn/Article/details/gtxchdzvbb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xinyue.icu/Article/details/gtewvknubl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhixingplan.top/Article/details/gtjbbjlkbo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtvijbfufm.html

TS:   constructor(public name: string) {}
来源：http://dali.xuanzx.com/Article/details/gtmndhjdht.html

Java: User(String name) { this.name = name; }
来源：http://dali.tianlin.xyz/Article/details/gtkwxblrie.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jqgfzy.top/Article/details/gtccowwkpj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zycfv.cn/Article/details/gtntobubqn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tianlin.xyz/Article/details/gtdsalojzr.html

[G03] 实例属性
来源：http://dali.sysykeji.top/Article/details/gtyradpnrv.html

Py:   self.name = "x"
来源：http://dali.pycfn.com/Article/details/gtbpsanftx.html

PHP:  public string $name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtmyaposwx.html

JS:   this.name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtbvcbysdu.html

TS:   name: string = "x";
来源：http://dali.yj20258.top/Article/details/gtvgezpkny.html

Java: private String name;
来源：http://dali.cucudq.cn/Article/details/gtcloemqfh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jlsjyb.cn/Article/details/gtqxnphyen.html

Ruby: @name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gtkwbsqyby.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ehwqpu.com/Article/details/gtbtyxilxw.html

[G04] 定义方法
来源：http://dali.yuanzhike.top/Article/details/gtsihcieko.html

Py:   def greet(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gtwynttglm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gttnqdljhw.html

JS:   greet() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtrblesyej.html

TS:   greet(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtedbhyvdn.html

Java: String greet() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtzmgtzevl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gtbnqqnfes.html

Ruby: def greet; @name; end
来源：http://dali.jiagoushi.top/Article/details/gtfmapuhpb.html

C#:   public string Greet() => Name;
来源：http://dali.shzxlz.cn/Article/details/gtowctzhrv.html

[G05] 继承
来源：http://dali.dianchejie.cn/Article/details/gtpxdmbwze.html

Py:   class Admin(User): pass
来源：http://dali.xziqi.cn/Article/details/gtuhvmxuds.html

PHP:  class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuprchqxs.html

JS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtruxgrdpz.html

TS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtgmkbceft.html

Java: class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtrnejplms.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.9152youxi.cn/Article/details/gtheofbrsh.html

Ruby: class Admin < User; end
来源：http://dali.cucudq.cn/Article/details/gtymkijary.html

C#:   class Admin : User {}
来源：http://dali.aizwys.cn/Article/details/gtqrxbuorm.html

[G06] 重写方法
来源：http://dali.gaohongyu789.top/Article/details/gtnlpxelfs.html

Py:   def greet(self): return "admin"
来源：http://dali.haohaochexian.top/Article/details/gtzsytzdjw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbhwyurxr.html

JS:   greet() { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gtbnvmmxoj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtjtbsmyoh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtpylmudfl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hywenlv.cn/Article/details/gtptsmzbos.html

Ruby: def greet; "admin"; end
来源：http://dali.hnxiangtu.top/Article/details/gtqidmzqjn.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinghuilouyu.cn/Article/details/gtbgpburdy.html

[G07] 调用父类方法
来源：http://dali.daria6918.cn/Article/details/gtvmjcpuif.html

Py:   super().greet()
来源：http://dali.shuidangran.top/Article/details/gtkrpylwwb.html

PHP:  parent::greet();
来源：http://dali.cucudq.cn/Article/details/gtsotottig.html

JS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtshobqsoc.html

TS:   super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtglpocpog.html

Java: super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gthszqfjjl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.iojbl.cn/Article/details/gtxcmkwvvh.html

Ruby: super
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmrhscxn.html

C#:   base.Greet();
来源：http://dali.cheryme.top/Article/details/gtqlbtxsap.html

[G08] 静态方法与属性
来源：http://dali.ydzc1.top/Article/details/gtaitndqve.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hfpthk.cn/Article/details/gttnvtthrq.html

PHP:  public static function f() {}
来源：http://dali.jianghu66.top/Article/details/gtnwhxplyw.html

JS:   static f() {}
来源：http://dali.ydzc1.top/Article/details/gtwrwnwiyn.html

TS:   static f(): void {}
来源：http://dali.haohaochexian.top/Article/details/gtogvwcngv.html

Java: static void f() {}
来源：http://dali.guowangkeji.top/Article/details/gtvquiykmv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsjcxwilq.html

Ruby: def self.f; end
来源：http://dali.hammf.cn/Article/details/gtdvhsezpt.html

C#:   public static void F() {}
来源：http://dali.zhongyouzk.top/Article/details/gteybjclgu.html

[G09] 接口 / 抽象类
来源：http://dali.cucudq.cn/Article/details/gturcllxlh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daria6918.cn/Article/details/gtshylypxm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.meibo888.top/Article/details/gtazqisrjy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxuanxn.top/Article/details/gtxmwxqvsv.html

TS:   interface Shape { area(): number; }
来源：http://dali.shzxlz.cn/Article/details/gtoeqncryc.html

Java: interface Shape { double area(); }
来源：http://dali.xuanzx.com/Article/details/gtxfrpeafb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.quarkkingdee.top/Article/details/gtsepjslaf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidvsqkxl.html

C#:   interface IShape { double Area(); }
来源：http://dali.kuanghao11.cn/Article/details/gtheyicrdm.html

[G10] 访问控制
来源：http://dali.jianghu66.top/Article/details/gttpgwhdkz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangshuangyany.cn/Article/details/gtfkykqasw.html

PHP:  public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gtiulbzztw.html

JS:   #private 字段；其余公开
来源：http://dali.dashuyun.cn/Article/details/gtgilqsxjv.html

TS:   public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gtdrzprqlz.html

Java: public / protected / private / 默认包级
来源：http://dali.zycfv.cn/Article/details/gtvlfgwdtf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.vqdsnc.cn/Article/details/gtsdymkufu.html

Ruby: public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtucjxhibb.html

C#:   public / protected / private / internal
来源：http://dali.jinqigfzy.top/Article/details/gtbkkmrtel.html

[G11] getter / setter
来源：http://dali.gotoacloud.top/Article/details/gtijkhgziq.html

Py:   @property 与 @x.setter
来源：http://dali.cashguo.top/Article/details/gtkopqlofa.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gtdboeeuew.html

JS:   get name() { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtdzmrejuy.html

TS:   get name(): string { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gtgmlvbkhw.html

Java: public String getName() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtceqklbuz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gtlzgnwyff.html

Ruby: attr_accessor :name
来源：http://dali.jlsjyb.cn/Article/details/gtjtduzfxj.html

C#:   public string Name { get; set; }
来源：http://dali.pengpengdd.cyou/Article/details/gtosfhfktl.html

[G12] 对象转字符串
来源：http://dali.cucudq.cn/Article/details/gtoyufgwcy.html

Py:   def __str__(self): return self.name
来源：http://dali.yueranfly.top/Article/details/gtsdjfzykr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gttyzeveqz.html

JS:   toString() { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtxhsfvuza.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtukinucjj.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gthgdoiymj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gtqdfljyns.html

Ruby: def to_s; @name; end
来源：http://dali.pengpengdd.cyou/Article/details/gtaqwublkb.html

C#:   public override string ToString() => Name;
来源：http://dali.jiagoushi.top/Article/details/gtemvseiql.html

[G13] 判断对象类型
来源：http://dali.xylfe.cn/Article/details/gtrvxygyrz.html

Py:   isinstance(u, User)
来源：http://dali.haohaochexian.top/Article/details/gtzlotrohe.html

PHP:  $u instanceof User
来源：http://dali.316326.xyz/Article/details/gtfefaiqvi.html

JS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtctziozlv.html

TS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtxvzplsuj.html

Java: u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtvmspdacg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tianlin.xyz/Article/details/gtyazsytbk.html

Ruby: u.is_a?(User)
来源：http://dali.sxryk.cn/Article/details/gtrsfeksud.html

C#:   u is User
来源：http://dali.havefunace.top/Article/details/gtbufchraa.html

[G14] 数据类 / record
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuvjhroly.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zdqjudy.top/Article/details/gtthcxntiu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sweek.top/Article/details/gtpthmsqbf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.aizwys.cn/Article/details/gtvbcvoyuw.html

TS:   type User = { name: string; age: number };
来源：http://dali.tanke756.top/Article/details/gtvfvtpfzn.html

Java: record User(String name, int age) {}
来源：http://dali.yangfankeji.com/Article/details/gtuzykedxn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tianlin.xyz/Article/details/gtqvouvadj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guannengcc.top/Article/details/gtoddypjdu.html

C#:   record User(string Name, int Age);
来源：http://dali.chenlongwang.top/Article/details/gthpqwjpul.html

[G15] 枚举
来源：http://dali.hysaishi.cn/Article/details/gtptmcrexh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.smart0.xyz/Article/details/gttzefupac.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangshuangyany.cn/Article/details/gteidpqgzg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.bjfxy.top/Article/details/gtrrbarowp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cdnleiting.top/Article/details/gthtiedpuj.html

Java: enum Color { RED, GREEN }
来源：http://dali.iojbl.cn/Article/details/gtusclkulf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.feifeiyinyue.top/Article/details/gtobndgfny.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj202588.top/Article/details/gtaiotdobc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258888.top/Article/details/gtpiwncdex.html

[G16] 对象转数组 / 字典
来源：http://dali.hongshengwenyu.top/Article/details/gtnhuqjswl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.redwolf501.top/Article/details/gtozhfdqnh.html

PHP:  get_object_vars($obj);
来源：http://dali.xinyue.icu/Article/details/gtudtskakz.html

JS:   Object.entries(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtfllnvqul.html

TS:   Object.entries(obj)
来源：http://dali.yangfankeji.com/Article/details/gtfqilhnkm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenlongwang.top/Article/details/gtctzwfwpw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guowangkeji.top/Article/details/gtsuyqwdjo.html

Ruby: obj.instance_variables
来源：http://dali.sysykeji.top/Article/details/gtentnsauw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gtmfwisqpq.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtxobfgxvk.html

H. 异常与错误处理
来源：http://dali.nanxinkj.top/Article/details/gtnctlhnxz.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtlezapsgj.html

[H01] try / catch 基础
来源：http://dali.jinqigufen.top/Article/details/gtnlzawzho.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tian-w.cn/Article/details/gtwcbbyuyx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtdjiiatwf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gtkwxdeopg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gtnbestalw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zdqjudy.top/Article/details/gtcvgorhac.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtldzojlqe.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cashguo.top/Article/details/gtucnsdrii.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shangyingyoupin.top/Article/details/gtqwlclalx.html

[H02] finally / ensure 收尾
来源：http://dali.snrcjt.cn/Article/details/gtrtoendsj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nanxinkj.top/Article/details/gtvoufumxn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtjxgwyukm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gtzzjomknt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtfxffwyfp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdocnrhdn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sweek.top/Article/details/gtxpdbfqvq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xylfe.cn/Article/details/gtjmlneaml.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtnijhwncc.html

[H03] 主动抛出异常
来源：http://dali.gotoacloud.top/Article/details/gtfekdijwk.html

Py:   raise ValueError("错误信息")
来源：http://dali.kuanghao11.cn/Article/details/gtnpeihora.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtfegbgcss.html

JS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtxxfxafhr.html

TS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtrcwgcnfp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtaqzdjost.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigfzy.top/Article/details/gtnrkrsflw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.smart0.xyz/Article/details/gtbbbpqqri.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtpmavjhas.html

[H04] 自定义异常类型
来源：http://dali.ybcxt.top/Article/details/gtfbtpfajo.html

Py:   class MyError(Exception): pass
来源：http://dali.0kj1m.cn/Article/details/gtplpnaxsv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.quarkkingdee.top/Article/details/gtcrllxyva.html

JS:   class MyError extends Error {}
来源：http://dali.hywenlv.cn/Article/details/gtyvhdlmgy.html

TS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gtkfsccgkh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gthgrctenh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.0kj1m.cn/Article/details/gtuccyiudo.html

Ruby: class MyError < StandardError; end
来源：http://dali.dianchejie.cn/Article/details/gtadacfnwx.html

C#:   class MyException : Exception {}
来源：http://dali.svipenyu.cn/Article/details/gtnwiotolq.html

[H05] 捕获特定类型
来源：http://dali.zycfv.cn/Article/details/gtqcyfcmof.html

Py:   except ValueError as e:
来源：http://dali.zhoulong.xyz/Article/details/gtmguqwnmo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.fzhhl.top/Article/details/gtprgiebgq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cheryme.top/Article/details/gtvplasawb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gtmvpzvzdb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.dianchejie.cn/Article/details/gtjosnqekt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.iojbl.cn/Article/details/gtizitgmyz.html

Ruby: rescue ArgumentError => e
来源：http://dali.daria6918.cn/Article/details/gtdctzirhw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cucudq.cn/Article/details/gtnvzmcqmt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxinkj.top/Article/details/gtyxguwcyo.html

Py:   value = d.get("k") or default
来源：http://dali.tianlin.xyz/Article/details/gtuyxeiuwx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hfpthk.cn/Article/details/gtdkppjwkl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gtkyvmueuz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtbmmdwpyn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhongyouzk.top/Article/details/gtapitleea.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hywenlv.cn/Article/details/gtribqfhkh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinqigufen.top/Article/details/gtdcpyeyuz.html

C#:   obj?.A?.B ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtyuvojhwj.html

[H07] 断言
来源：http://dali.smart0.xyz/Article/details/gtvklcvupi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.birdmap.top/Article/details/gtaehfdgwu.html

PHP:  assert($x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtlzdfvckh.html

JS:   console.assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gtedbycyuz.html

TS:   console.assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdvcmhpm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sweek.top/Article/details/gthmmgthya.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zycfv.cn/Article/details/gttravoikq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cheryme.top/Article/details/gtpinoulio.html

C#:   Debug.Assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtoapbxlhf.html

[H08] 获取错误信息与堆栈
来源：http://dali.tian-w.cn/Article/details/gtosvlufln.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjycrhtap.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tianlin.xyz/Article/details/gtjwqlutir.html

JS:   e.message;  e.stack
来源：http://dali.yuanzhike.top/Article/details/gtqnynibix.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xuanzx.com/Article/details/gtdqkvrujw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.redwolf501.top/Article/details/gtmiussdqj.html

Go:   err.Error()
来源：http://dali.daxiang520.top/Article/details/gtoxkbylzu.html

Ruby: e.message;  e.backtrace
来源：http://dali.c1oappe.top/Article/details/gtbwlyecaq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenlongwang.top/Article/details/gtxohhtsfi.html

[H09] 带错误码的异常
来源：http://dali.hysaishi.cn/Article/details/gtoxoiitpv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnsiysnz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xylfe.cn/Article/details/gtgoxljdcw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sweek.top/Article/details/gtecjogsqo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.kuanghao11.cn/Article/details/gtebpvnhsk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.havefunace.top/Article/details/gtrozzxhgq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daxiang520.top/Article/details/gtncqkoilz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yuanzhike.top/Article/details/gthfcgoosg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gtridxvgpo.html

[H10] 资源自动释放
来源：http://dali.jqgufenzy.top/Article/details/gtvactlxjv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.havefunace.top/Article/details/gttzdtaapc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ybcxt.top/Article/details/gtdqgqnjsv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gtcvglqnlc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.redwolf501.top/Article/details/gtlsuvxnoi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigfzy.top/Article/details/gtdzwfufuv.html

Go:   defer f.Close()
来源：http://dali.tianlin.xyz/Article/details/gteqsuzzpi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.havefunace.top/Article/details/gtikkckmuv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtzmazznux.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtlswgmsdb.html

I. 正则表达式
来源：http://dali.redwolf501.top/Article/details/gtkfxeucml.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtvwqkzssh.html

[I01] 判断是否匹配
来源：http://dali.havefunace.top/Article/details/gtxzcxsdkn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jqgufenzy.top/Article/details/gtlltcktqb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.andypj.xyz/Article/details/gtxkwnidrw.html

JS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gtzzeumpxj.html

TS:   /\d+/.test(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtbnolygdi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrldzkqja.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.bjfxy.top/Article/details/gtgmxrswtl.html

Ruby: s.match?(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gtzecfflwb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hysaishi.cn/Article/details/gtomjqkuog.html

[I02] 提取所有匹配
来源：http://dali.yongpay.top/Article/details/gtzbrnogud.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gtnxuvejmh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzomnukmq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinghuilouyu.cn/Article/details/gtvylhtybo.html

TS:   s.match(/\d+/g)
来源：http://dali.zdqjudy.top/Article/details/gtktjeupii.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258888.top/Article/details/gtnqrnrnjj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sweek.top/Article/details/gtinqhegry.html

Ruby: s.scan(/\d+/)
来源：http://dali.sxryk.cn/Article/details/gttxymrqks.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtrarkwlxq.html

[I03] 提取捕获分组
来源：http://dali.yonumen.top/Article/details/gtjselftlh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtmnkxmkrb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fzhhl.top/Article/details/gtivomflkg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.smart0.xyz/Article/details/gtdibbhmhz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.iojbl.cn/Article/details/gtrdnunima.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yuanzhike.top/Article/details/gtovsqxqys.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guowangkeji.top/Article/details/gtepkfqixd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gzhubu.top/Article/details/gtjzhlnrxp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.mhx1999.top/Article/details/gtdlmscens.html

[I04] 正则替换
来源：http://dali.tianlin.xyz/Article/details/gttizaatfc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xziqi.cn/Article/details/gtauwywtpq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ppjwa.cn/Article/details/gtcwbqnhqk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtnjpkvywu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gogol.net.cn/Article/details/gtvrmrpiyc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xylfe.cn/Article/details/gtprrnqwgp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.dianchejie.cn/Article/details/gtxuoxjoqk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gzhubu.top/Article/details/gtdmwxlaae.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.c1oappe.top/Article/details/gtgwwxezgb.html

[I05] 按正则拆分
来源：http://dali.zhiwuduotai.top/Article/details/gtpinvkeam.html


<!-- 参考信息 -->