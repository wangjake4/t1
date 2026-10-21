代发 wailian999

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtbbanqvst.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtvbwybeka.html

[F11] 复制与移动文件
来源：http://dali.9152youxi.cn/Article/details/gttgsxkrbq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtvqkdcoku.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xuanzx.com/Article/details/gtditugttp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtehmjkysb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtmvmiobte.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ybcxt.top/Article/details/gtzyosqsnk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjgdbxtgo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtleeiiysk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jianghu66.top/Article/details/gthnluipgh.html

[F12] CSV 读写
来源：http://dali.cucudq.cn/Article/details/gtaucuirso.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.pycfn.com/Article/details/gttrqnzwsa.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhixingplan.top/Article/details/gtxxwwqrfy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxinkj.top/Article/details/gtkgtoonnt.html

TS:   // 同上
来源：http://dali.ppjwa.cn/Article/details/gtcsdbagnr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwcwvjjp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yueranfly.top/Article/details/gtksccfzpg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhiwuduotai.top/Article/details/gtxuexixhq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gzhubu.top/Article/details/gtsatltmil.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtmxhrbwsc.html

G. 面向对象
来源：http://dali.hnqzz.top/Article/details/gtpnqcgxdv.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtbnxtvpye.html

[G01] 定义类
来源：http://dali.xylfe.cn/Article/details/gtkdkjplpq.html

Py:   class User: pass
来源：http://dali.zhixingplan.top/Article/details/gtzkatsfch.html

PHP:  class User {}
来源：http://dali.shuidangran.top/Article/details/gtklkwohjr.html

JS:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtbyaatabq.html

TS:   class User { name: string = ""; }
来源：http://dali.zhongyouzk.top/Article/details/gtlqzqnkte.html

Java: class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtyzhkhnpy.html

Go:   type User struct { Name string }
来源：http://dali.sufxvd.cn/Article/details/gtftoyqglo.html

Ruby: class User; end
来源：http://dali.316326.xyz/Article/details/gtpserwnxk.html

C#:   class User {}
来源：http://dali.ppjwa.cn/Article/details/gtvgwpnulm.html

[G02] 构造函数
来源：http://dali.wangdashe.top/Article/details/gtdmragjim.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yueranfly.top/Article/details/gtavblnfdz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jianghu66.top/Article/details/gthqbmsvda.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gtqqftcoxt.html

TS:   constructor(public name: string) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtagndmusl.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtyejpsino.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigufen.top/Article/details/gtduacgakj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yvedp.cn/Article/details/gtaayrandq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sufxvd.cn/Article/details/gtigwmtens.html

[G03] 实例属性
来源：http://dali.hfpthk.cn/Article/details/gtxpelxocj.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gthognerco.html

PHP:  public string $name = "x";
来源：http://dali.yueranfly.top/Article/details/gtfoylrqys.html

JS:   this.name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtkghhautd.html

TS:   name: string = "x";
来源：http://dali.cucudq.cn/Article/details/gtlnplchjl.html

Java: private String name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdetzzzpe.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhoulong.xyz/Article/details/gtnohuzakq.html

Ruby: @name = "x"
来源：http://dali.yonumen.top/Article/details/gtnlpzpwpx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbcwzdbz.html

[G04] 定义方法
来源：http://dali.zhongyouzk.top/Article/details/gtjngvduei.html

Py:   def greet(self): return self.name
来源：http://dali.zdqjudy.top/Article/details/gthedpgsxg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gtiftmtabh.html

JS:   greet() { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfxlaxmrj.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gtmjrdcofa.html

Java: String greet() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtpiflikpk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gtcobppwnf.html

Ruby: def greet; @name; end
来源：http://dali.pengpengdd.cyou/Article/details/gtqirqueux.html

C#:   public string Greet() => Name;
来源：http://dali.shuidangran.top/Article/details/gtxfftjoyp.html

[G05] 继承
来源：http://dali.yanxiufei.cn/Article/details/gtnmhgohgp.html

Py:   class Admin(User): pass
来源：http://dali.cqqwz.cn/Article/details/gtuvldxqot.html

PHP:  class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtcbsokabb.html

JS:   class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtniwvfdtl.html

TS:   class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtezxezcil.html

Java: class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtvvhbuznm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xylfe.cn/Article/details/gtxmqaybti.html

Ruby: class Admin < User; end
来源：http://dali.meibo888.top/Article/details/gtforfvuiz.html

C#:   class Admin : User {}
来源：http://dali.guowangkeji.top/Article/details/gtvdwgweof.html

[G06] 重写方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtixuzqtwc.html

Py:   def greet(self): return "admin"
来源：http://dali.316326.xyz/Article/details/gtyngxsaoi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtzaluombx.html

JS:   greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtssqackmq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtrjbdlhky.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gttoeeksvq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yongpay.top/Article/details/gtojqdxhsv.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblavixdx.html

C#:   public override string Greet() => "admin";
来源：http://dali.hysaishi.cn/Article/details/gtwpctzfpm.html

[G07] 调用父类方法
来源：http://dali.chenlongwang.top/Article/details/gtgukicgww.html

Py:   super().greet()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthkdxosdm.html

PHP:  parent::greet();
来源：http://dali.cucudq.cn/Article/details/gtbhqaoeaz.html

JS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtmbztvrpq.html

TS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtnvfzxeqh.html

Java: super.greet();
来源：http://dali.ehwqpu.com/Article/details/gtshawkrbe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.bjfxy.top/Article/details/gtxprkasec.html

Ruby: super
来源：http://dali.andypj.xyz/Article/details/gtsqwcblej.html

C#:   base.Greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gthtckrtsa.html

[G08] 静态方法与属性
来源：http://dali.xinyue.icu/Article/details/gtzqglrjkq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuanzx.com/Article/details/gtidgoooke.html

PHP:  public static function f() {}
来源：http://dali.shzxlz.cn/Article/details/gtscmqalwd.html

JS:   static f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtdrymkvpf.html

TS:   static f(): void {}
来源：http://dali.tanke756.top/Article/details/gtilycydtu.html

Java: static void f() {}
来源：http://dali.redwolf501.top/Article/details/gtplfjgczj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xziqi.cn/Article/details/gtbltbmgtn.html

Ruby: def self.f; end
来源：http://dali.yj20258888.top/Article/details/gtjbngcakg.html

C#:   public static void F() {}
来源：http://dali.xylfe.cn/Article/details/gtzcshwhqu.html

[G09] 接口 / 抽象类
来源：http://dali.yangfankeji.com/Article/details/gtrysfflaj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sufxvd.cn/Article/details/gtdveyjcsc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fzhhl.top/Article/details/gtbqdtxrdc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shuidangran.top/Article/details/gtgxwjvbrx.html

TS:   interface Shape { area(): number; }
来源：http://dali.yvedp.cn/Article/details/gtjzshieho.html

Java: interface Shape { double area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtpwirhveb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.havefunace.top/Article/details/gtrccqmslf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.feifeiyinyue.top/Article/details/gtwcgcrkjk.html

C#:   interface IShape { double Area(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpgagujgg.html

[G10] 访问控制
来源：http://dali.nanxinkj.top/Article/details/gtljxhkwwo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgdjturj.html

PHP:  public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtnckphpmy.html

JS:   #private 字段；其余公开
来源：http://dali.xylfe.cn/Article/details/gtcrlvwoxs.html

TS:   public / protected / private
来源：http://dali.mhx1999.top/Article/details/gttdkwmjot.html

Java: public / protected / private / 默认包级
来源：http://dali.daxiang520.top/Article/details/gtfgdmhunq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jiagoushi.top/Article/details/gtqthunbcu.html

Ruby: public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtebxaotxi.html

C#:   public / protected / private / internal
来源：http://dali.xylfe.cn/Article/details/gtcfnlxqjr.html

[G11] getter / setter
来源：http://dali.chenzaomai.com/Article/details/gtnfjferrb.html

Py:   @property 与 @x.setter
来源：http://dali.shangyingyoupin.top/Article/details/gtgcfvtqoc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtjhzsijpn.html

JS:   get name() { return this._name; }
来源：http://dali.gaohongyu789.top/Article/details/gttxxvirnt.html

TS:   get name(): string { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gtsvzigahd.html

Java: public String getName() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtaieqfmek.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gttylymdgv.html

Ruby: attr_accessor :name
来源：http://dali.cashguo.top/Article/details/gtdxftelld.html

C#:   public string Name { get; set; }
来源：http://dali.vqdsnc.cn/Article/details/gtbekqefzw.html

[G12] 对象转字符串
来源：http://dali.jqgfzy.top/Article/details/gtthkastrt.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gtdalzdgzd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gtkvwufvrm.html

JS:   toString() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtycqvvhpg.html

TS:   toString(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtktzrmfqd.html

Java: @Override public String toString() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gteodkaotq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gtycbggelf.html

Ruby: def to_s; @name; end
来源：http://dali.9152youxi.cn/Article/details/gtwnrhwnmg.html

C#:   public override string ToString() => Name;
来源：http://dali.zdqjudy.top/Article/details/gtevnbqbjk.html

[G13] 判断对象类型
来源：http://dali.hfpthk.cn/Article/details/gtrmxywaop.html

Py:   isinstance(u, User)
来源：http://dali.cqqwz.cn/Article/details/gtcrggcdnj.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfsvtdya.html

JS:   u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtvehtewpa.html

TS:   u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtxkernhrp.html

Java: u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gtjkjqvysa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.birdmap.top/Article/details/gtuzzbqgpw.html

Ruby: u.is_a?(User)
来源：http://dali.chenjidiqi.icu/Article/details/gttcnmpvly.html

C#:   u is User
来源：http://dali.9152youxi.cn/Article/details/gtdtrrausz.html

[G14] 数据类 / record
来源：http://dali.wangshuangyany.cn/Article/details/gtqhpknpfg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sysykeji.top/Article/details/gtpenzplmu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.guowangkeji.top/Article/details/gtlaqgdhgh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangshuangyany.cn/Article/details/gtunfpikdv.html

TS:   type User = { name: string; age: number };
来源：http://dali.dianchejie.cn/Article/details/gtditxoxly.html

Java: record User(String name, int age) {}
来源：http://dali.jqgfzy.top/Article/details/gtrtesvoon.html

Go:   type User struct { Name string; Age int }
来源：http://dali.fzhhl.top/Article/details/gtfhmaanxr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shangyingyoupin.top/Article/details/gtjyrlessv.html

C#:   record User(string Name, int Age);
来源：http://dali.redwolf501.top/Article/details/gtbprkresm.html

[G15] 枚举
来源：http://dali.yj20258888.top/Article/details/gtprvzwchc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj20258888.top/Article/details/gtowlqhrzx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cqqwz.cn/Article/details/gtnnivozmi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dashuyun.cn/Article/details/gttpgumukq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gtilpqpbbb.html

Java: enum Color { RED, GREEN }
来源：http://dali.birdmap.top/Article/details/gtzxoinluo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sysykeji.top/Article/details/gtdgrsdawf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gogol.net.cn/Article/details/gtnugxaghm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258888.top/Article/details/gtyjvsrpdk.html

[G16] 对象转数组 / 字典
来源：http://dali.pycfn.com/Article/details/gtefqzchbk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.wangdashe.top/Article/details/gtrlerzqjc.html

PHP:  get_object_vars($obj);
来源：http://dali.xinyue.icu/Article/details/gtrsoznbnn.html

JS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gtzdmrvtig.html

TS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gtnjqfitui.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.havefunace.top/Article/details/gtzkvsitwo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhongyouzk.top/Article/details/gtppnckkhr.html

Ruby: obj.instance_variables
来源：http://dali.yvedp.cn/Article/details/gtdqjuqqvk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zdqjudy.top/Article/details/gtoaumjjqe.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtsltxyvqn.html

H. 异常与错误处理
来源：http://dali.pycfn.com/Article/details/gtmsfzckjb.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtcfvzbbhl.html

[H01] try / catch 基础
来源：http://dali.feifeiyinyue.top/Article/details/gtdkgndbwu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gotoacloud.top/Article/details/gtuvggowvo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.iojbl.cn/Article/details/gtmopniozt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.daria6918.cn/Article/details/gtykvumlrr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gtjeczcjdo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xziqi.cn/Article/details/gtozzztuvr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zdqjudy.top/Article/details/gtvkzpofjz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cqqwz.cn/Article/details/gtlrantmgl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfixubibq.html

[H02] finally / ensure 收尾
来源：http://dali.meibo888.top/Article/details/gtaovfzsts.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tanke756.top/Article/details/gtrmvgypdl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtowfffmtg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtytbpqfws.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtadwbqkth.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtqzdmfnrn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.9152youxi.cn/Article/details/gtpufzlitq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hfpthk.cn/Article/details/gtybuxldmc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtwrlmelzt.html

[H03] 主动抛出异常
来源：http://dali.zdqjudy.top/Article/details/gtykeclblm.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgfzy.top/Article/details/gthfgyyxpl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtpmonwidm.html

JS:   throw new Error("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtoocilxzu.html

TS:   throw new Error("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtzscdgmau.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtrsuwmmjd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zdqjudy.top/Article/details/gtlmuctdvf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnxiangtu.top/Article/details/gtzvgisufs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gttxenayih.html

[H04] 自定义异常类型
来源：http://dali.shuidangran.top/Article/details/gtncugcozz.html

Py:   class MyError(Exception): pass
来源：http://dali.snrcjt.cn/Article/details/gtnfdnhptz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gteixuknwv.html

JS:   class MyError extends Error {}
来源：http://dali.yj20258888.top/Article/details/gttmjnbmkb.html

TS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gtbhgbuica.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ppjwa.cn/Article/details/gtkvsumbyw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcrrvjxwf.html

Ruby: class MyError < StandardError; end
来源：http://dali.316326.xyz/Article/details/gthmyamlow.html

C#:   class MyException : Exception {}
来源：http://dali.shzxlz.cn/Article/details/gtezbsfehh.html

[H05] 捕获特定类型
来源：http://dali.yj20258888.top/Article/details/gtwqdemcek.html

Py:   except ValueError as e:
来源：http://dali.gogol.net.cn/Article/details/gtrwabulfx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hongshengwenyu.top/Article/details/gtwvlzwbky.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gzhubu.top/Article/details/gtlpzgzepq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gtgihbihix.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.andypj.xyz/Article/details/gtlcoctlns.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tanke756.top/Article/details/gtmeqmmafs.html

Ruby: rescue ArgumentError => e
来源：http://dali.tian-w.cn/Article/details/gtfsjrkhwn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cashguo.top/Article/details/gtjvrwkkrs.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zycfv.cn/Article/details/gtgehceift.html

Py:   value = d.get("k") or default
来源：http://dali.havefunace.top/Article/details/gtvgmqllun.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gtrglffivk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gtuacdxdtr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gtpgcfhitt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ybcxt.top/Article/details/gtomdeelux.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.feifeiyinyue.top/Article/details/gtshkmktiy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cheryme.top/Article/details/gtxqzhffrz.html

C#:   obj?.A?.B ?? default
来源：http://dali.ehwqpu.com/Article/details/gtlfpvpzlh.html

[H07] 断言
来源：http://dali.zhoulong.xyz/Article/details/gtluttrejb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shuidangran.top/Article/details/gtyvpcxlci.html

PHP:  assert($x > 0);
来源：http://dali.ivvv.top/Article/details/gtupalfrxu.html

JS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gtkzlnorsc.html

TS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtqidqrspk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ehwqpu.com/Article/details/gtbtyoaavv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ydzc1.top/Article/details/gtqemfwbic.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenlongwang.top/Article/details/gtmqyxdrlj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtxizskphf.html

[H08] 获取错误信息与堆栈
来源：http://dali.birdmap.top/Article/details/gtgdszbaak.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.vqdsnc.cn/Article/details/gtndkiwijc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sysykeji.top/Article/details/gtzkopcecf.html

JS:   e.message;  e.stack
来源：http://dali.jianghu66.top/Article/details/gtqkojgsue.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.daxiang520.top/Article/details/gtuazwynxv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagfcbunf.html

Go:   err.Error()
来源：http://dali.nanxinkj.top/Article/details/gtzegdtjrc.html

Ruby: e.message;  e.backtrace
来源：http://dali.xinyue.icu/Article/details/gthtyzkoyp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnqzz.top/Article/details/gtmtshyohw.html

[H09] 带错误码的异常
来源：http://dali.hnqzz.top/Article/details/gttelphwoc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gaohongyu789.top/Article/details/gtlhtzhzor.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.haohaochexian.top/Article/details/gtadfbfoct.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xuanzx.com/Article/details/gtirpcztud.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shangyingyoupin.top/Article/details/gtatitbxmg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqbzcixi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yangfankeji.com/Article/details/gtagrtzlqe.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnxiangtu.top/Article/details/gtpxzzjjuv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nanxinkj.top/Article/details/gtjtdunkvg.html

[H10] 资源自动释放
来源：http://dali.ppjwa.cn/Article/details/gtlrearnmx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jianghu66.top/Article/details/gthszenjgp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.andypj.xyz/Article/details/gtgajykgqb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gtjdxcvgyt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daria6918.cn/Article/details/gtwtkxbldb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shangyingyoupin.top/Article/details/gtdpnpmeod.html

Go:   defer f.Close()
来源：http://dali.shangyingyoupin.top/Article/details/gtxihbneec.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gthflmiwiw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtlawpusrl.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtqzbmirxe.html

I. 正则表达式
来源：http://dali.wangshuangyany.cn/Article/details/gttjkchhxf.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtxgzvjhto.html

[I01] 判断是否匹配
来源：http://dali.hnqzz.top/Article/details/gtqsqadnny.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtykaceifv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtizjbismg.html

JS:   /\d+/.test(s)
来源：http://dali.jlsjyb.cn/Article/details/gtmliwzjta.html

TS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gtycqldhqo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.316326.xyz/Article/details/gtbeizaafd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tanke756.top/Article/details/gtcjcizajw.html

Ruby: s.match?(/\d+/)
来源：http://dali.yangfankeji.com/Article/details/gtgwccsyzb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangshuangyany.cn/Article/details/gtyhawdvjb.html

[I02] 提取所有匹配
来源：http://dali.dashuyun.cn/Article/details/gtwzidvqme.html

Py:   re.findall(r"\d+", s)
来源：http://dali.aizwys.cn/Article/details/gtenhparua.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shzxlz.cn/Article/details/gthjdplkqk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.vqdsnc.cn/Article/details/gtrdfhbfnc.html

TS:   s.match(/\d+/g)
来源：http://dali.xuetiantiany.cn/Article/details/gtoyarxtzv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.dashuyun.cn/Article/details/gtnnvkejtb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.aibaodan.cn/Article/details/gthnvqhvya.html

Ruby: s.scan(/\d+/)
来源：http://dali.hfpthk.cn/Article/details/gtpjjkcigj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yvedp.cn/Article/details/gtezsvnsvc.html

[I03] 提取捕获分组
来源：http://dali.sysykeji.top/Article/details/gtklddllck.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xinyue.icu/Article/details/gtdeffrxrn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yuxming.cn/Article/details/gtsshafpry.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.daria6918.cn/Article/details/gtefmhqoza.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.fengsongda.top/Article/details/gteuurirlj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yuanzhike.top/Article/details/gtecmllmel.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.andypj.xyz/Article/details/gtcnampwrq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ppjwa.cn/Article/details/gtivhrwivz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pycfn.com/Article/details/gtyacnzlix.html

[I04] 正则替换
来源：http://dali.vqdsnc.cn/Article/details/gtydzcpcda.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.iojbl.cn/Article/details/gtouujgcgg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gteehyjolm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhixingplan.top/Article/details/gtzdawzhdm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daria6918.cn/Article/details/gtxwfnnyrn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsmtwzsmy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.316326.xyz/Article/details/gtgeciglzh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cashguo.top/Article/details/gtsffbenlo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.aizwys.cn/Article/details/gtkvuwkqqw.html

[I05] 按正则拆分
来源：http://dali.hongshengwenyu.top/Article/details/gtiafkglhy.html


<!-- 参考信息 -->