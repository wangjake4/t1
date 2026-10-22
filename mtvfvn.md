代发 wailian999

[F09] 获取文件大小
来源：http://dali.guannengcc.top/Article/details/gttnyfbagg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtdwkfkdpe.html

PHP:  filesize("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtnbfjlawx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gteyjbxadb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cdnleiting.top/Article/details/gtyibsgysw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtviyumwna.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yuxming.cn/Article/details/gtkfdlcyaf.html

Ruby: File.size("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtpqnykuqg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.dashuyun.cn/Article/details/gtbjdtccfh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sxryk.cn/Article/details/gtgihafewb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtmcmkavfe.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtaqnijhls.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtqxvltwvc.html

TS:   path.extname("a.txt")
来源：http://dali.yj202588.top/Article/details/gtlteqactu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nanxinkj.top/Article/details/gtqkhnzfqs.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtiznudkml.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtvmmxvyou.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtpgubcuiw.html

[F11] 复制与移动文件
来源：http://dali.quarkkingdee.top/Article/details/gtqtopkcln.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtebdbbzsq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.aibaodan.cn/Article/details/gtmtprwgkn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtelvwxvlr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gthdjsbndj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.wangdashe.top/Article/details/gtxcopzoog.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tanke756.top/Article/details/gtuetzneik.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtpctkyahf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sysykeji.top/Article/details/gtfqskunfr.html

[F12] CSV 读写
来源：http://dali.ivvv.top/Article/details/gtejwkzbmb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteuighleh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jianghu66.top/Article/details/gtdnjvfhck.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhongyouzk.top/Article/details/gtqpceoytb.html

TS:   // 同上
来源：http://dali.xziqi.cn/Article/details/gtohxfrpkx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xziqi.cn/Article/details/gtlpqiferb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.havefunace.top/Article/details/gtrgtbqsga.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yuanzhike.top/Article/details/gteeankxsj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hongshengwenyu.top/Article/details/gtmjvtqcjb.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtspegybnb.html

G. 面向对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgniuxeno.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtlinyoqni.html

[G01] 定义类
来源：http://dali.nwbrower.top/Article/details/gtbryfysxr.html

Py:   class User: pass
来源：http://dali.zdqjudy.top/Article/details/gtietqpwyj.html

PHP:  class User {}
来源：http://dali.iojbl.cn/Article/details/gtaqyahelj.html

JS:   class User {}
来源：http://dali.yj202588.top/Article/details/gtcjvjvals.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtysuqizwb.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gtvvoyocgg.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gtffvybmfe.html

Ruby: class User; end
来源：http://dali.pengpengdd.cyou/Article/details/gtpgrpbkyx.html

C#:   class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdccgtoun.html

[G02] 构造函数
来源：http://dali.xinyue.icu/Article/details/gtlgbqgbxz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.redwolf501.top/Article/details/gtmxllagto.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jianghu66.top/Article/details/gtukibxqwx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gtlhapyccm.html

TS:   constructor(public name: string) {}
来源：http://dali.ppjwa.cn/Article/details/gtdcdisdxx.html

Java: User(String name) { this.name = name; }
来源：http://dali.cqqwz.cn/Article/details/gtrfreghwi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hfpthk.cn/Article/details/gtfsvzpfkk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sweek.top/Article/details/gtffemearm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jqgfzy.top/Article/details/gtjejrpxvp.html

[G03] 实例属性
来源：http://dali.sysykeji.top/Article/details/gtfurwlyyj.html

Py:   self.name = "x"
来源：http://dali.cucudq.cn/Article/details/gtjbarjfak.html

PHP:  public string $name = "x";
来源：http://dali.yueranfly.top/Article/details/gtxtgrxztu.html

JS:   this.name = "x";
来源：http://dali.fengsongda.top/Article/details/gtxmxhrsyj.html

TS:   name: string = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtgqqmneaq.html

Java: private String name;
来源：http://dali.nwbrower.top/Article/details/gtaljvmfqf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nwbrower.top/Article/details/gthwzviole.html

Ruby: @name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gtitgymtaj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtkxhyzzfu.html

[G04] 定义方法
来源：http://dali.yj202588.top/Article/details/gtzwhvrncl.html

Py:   def greet(self): return self.name
来源：http://dali.meibo888.top/Article/details/gtubuczfvd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gtjbegfqlq.html

JS:   greet() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gteupddght.html

TS:   greet(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtpqdmokcm.html

Java: String greet() { return name; }
来源：http://dali.pycfn.com/Article/details/gtxkntcsjs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gtrkujjwyl.html

Ruby: def greet; @name; end
来源：http://dali.jinqigufen.top/Article/details/gtmxinpahv.html

C#:   public string Greet() => Name;
来源：http://dali.andypj.xyz/Article/details/gtfdpplnsx.html

[G05] 继承
来源：http://dali.hongshengwenyu.top/Article/details/gtcdtkzrhw.html

Py:   class Admin(User): pass
来源：http://dali.jqgufenzy.top/Article/details/gtmrjkhnul.html

PHP:  class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtzdkbrlbs.html

JS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtozzhaeea.html

TS:   class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtzpepobdm.html

Java: class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gttauqupio.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.316326.xyz/Article/details/gtqgchembk.html

Ruby: class Admin < User; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkymxryy.html

C#:   class Admin : User {}
来源：http://dali.hywenlv.cn/Article/details/gtocvamklx.html

[G06] 重写方法
来源：http://dali.vqdsnc.cn/Article/details/gtihuztseo.html

Py:   def greet(self): return "admin"
来源：http://dali.bjfxy.top/Article/details/gtoybvjfpk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtdisatpbx.html

JS:   greet() { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtdnsyvrvt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtksrlircf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtilzrebmj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hfpthk.cn/Article/details/gtxagxlnsn.html

Ruby: def greet; "admin"; end
来源：http://dali.tanke756.top/Article/details/gtdsaasvry.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenzaomai.com/Article/details/gtecuvcbzw.html

[G07] 调用父类方法
来源：http://dali.yonumen.top/Article/details/gtwhzgkcoi.html

Py:   super().greet()
来源：http://dali.yongpay.top/Article/details/gtnxleyhpp.html

PHP:  parent::greet();
来源：http://dali.haohaochexian.top/Article/details/gtixvpvmrq.html

JS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gtdewiljgv.html

TS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gtwbspcvzv.html

Java: super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtcmpdguhr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nanxinkj.top/Article/details/gtohapjdez.html

Ruby: super
来源：http://dali.nanxuanxn.top/Article/details/gtvljmrdkl.html

C#:   base.Greet();
来源：http://dali.yj20258888.top/Article/details/gtcmktieyh.html

[G08] 静态方法与属性
来源：http://dali.fzhhl.top/Article/details/gtfavlyxru.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gotoacloud.top/Article/details/gtusutgvls.html

PHP:  public static function f() {}
来源：http://dali.aibaodan.cn/Article/details/gtuqzzepwo.html

JS:   static f() {}
来源：http://dali.chenzaomai.com/Article/details/gtzedkpkga.html

TS:   static f(): void {}
来源：http://dali.zhiwuduotai.top/Article/details/gtqozhlqgc.html

Java: static void f() {}
来源：http://dali.c1oappe.top/Article/details/gtontmnqxz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj202588.top/Article/details/gtdvpgtknc.html

Ruby: def self.f; end
来源：http://dali.cucudq.cn/Article/details/gtlgrgnbeu.html

C#:   public static void F() {}
来源：http://dali.nanxinkj.top/Article/details/gtzrvintnk.html

[G09] 接口 / 抽象类
来源：http://dali.fengsongda.top/Article/details/gtpsvmyqbk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.mhx1999.top/Article/details/gtpbvhgygm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tian-w.cn/Article/details/gtuimjtnbi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.birdmap.top/Article/details/gthrzugzpf.html

TS:   interface Shape { area(): number; }
来源：http://dali.iojbl.cn/Article/details/gtqdjdsesv.html

Java: interface Shape { double area(); }
来源：http://dali.birdmap.top/Article/details/gtheazmibk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daxiang520.top/Article/details/gtxqbegohs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinqigfzy.top/Article/details/gtcqlywnin.html

C#:   interface IShape { double Area(); }
来源：http://dali.iojbl.cn/Article/details/gtxjxqiecl.html

[G10] 访问控制
来源：http://dali.hammf.cn/Article/details/gtkzvditup.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.iojbl.cn/Article/details/gtpmjcpggt.html

PHP:  public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtyckcskku.html

JS:   #private 字段；其余公开
来源：http://dali.havefunace.top/Article/details/gtrgrkwkga.html

TS:   public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gteqwyvhes.html

Java: public / protected / private / 默认包级
来源：http://dali.hongshengwenyu.top/Article/details/gtzzaoqvwl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shangyingyoupin.top/Article/details/gtmasxkjky.html

Ruby: public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtaitsincx.html

C#:   public / protected / private / internal
来源：http://dali.sxryk.cn/Article/details/gtavvmjkbq.html

[G11] getter / setter
来源：http://dali.0kj1m.cn/Article/details/gtocpnxsmy.html

Py:   @property 与 @x.setter
来源：http://dali.quarkkingdee.top/Article/details/gtdiaebwfv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gtfxlshdem.html

JS:   get name() { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbuipfujt.html

TS:   get name(): string { return this._name; }
来源：http://dali.snrcjt.cn/Article/details/gtrxpuspxo.html

Java: public String getName() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtnplvmdcx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gteubtwzpj.html

Ruby: attr_accessor :name
来源：http://dali.aizwys.cn/Article/details/gtwsmjyoge.html

C#:   public string Name { get; set; }
来源：http://dali.gaohongyu789.top/Article/details/gtpevybktc.html

[G12] 对象转字符串
来源：http://dali.shuidangran.top/Article/details/gtisxgtpgx.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gttibafngk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtgvrotlrh.html

JS:   toString() { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtbhmubnqq.html

TS:   toString(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtptwupwcd.html

Java: @Override public String toString() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtvqdzkhhm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtropdnvac.html

Ruby: def to_s; @name; end
来源：http://dali.tianlin.xyz/Article/details/gtxsnrvukq.html

C#:   public override string ToString() => Name;
来源：http://dali.yonumen.top/Article/details/gtwzffmeas.html

[G13] 判断对象类型
来源：http://dali.mhx1999.top/Article/details/gtniqflbzx.html

Py:   isinstance(u, User)
来源：http://dali.fzhhl.top/Article/details/gtrofccnmj.html

PHP:  $u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtkfgcpxqa.html

JS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtilzqhdkg.html

TS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gthzlkqcpm.html

Java: u instanceof User
来源：http://dali.hnqzz.top/Article/details/gticfdndtu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tianlin.xyz/Article/details/gtvuugiytz.html

Ruby: u.is_a?(User)
来源：http://dali.hnqzz.top/Article/details/gtgnqmimwu.html

C#:   u is User
来源：http://dali.gotoacloud.top/Article/details/gtmrzfyeto.html

[G14] 数据类 / record
来源：http://dali.jinqigufen.top/Article/details/gtzrbkgaor.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guowangkeji.top/Article/details/gtcpvbqzkn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hongshengwenyu.top/Article/details/gtmzqrcxmh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinqigfzy.top/Article/details/gtrkujmnyu.html

TS:   type User = { name: string; age: number };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtibkwtsmo.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsgcxzbds.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xylfe.cn/Article/details/gtldxbwwqs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhengqikj.top/Article/details/gtjecuyitq.html

C#:   record User(string Name, int Age);
来源：http://dali.fengsongda.top/Article/details/gtzfshbywa.html

[G15] 枚举
来源：http://dali.snrcjt.cn/Article/details/gtyhilblik.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zdqjudy.top/Article/details/gtdaqebzpi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sxryk.cn/Article/details/gtvbohevrh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ehwqpu.com/Article/details/gtlppqwesv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhixingplan.top/Article/details/gtgifyrzgi.html

Java: enum Color { RED, GREEN }
来源：http://dali.yueranfly.top/Article/details/gtexsepxmx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhoulong.xyz/Article/details/gtilcrkfmh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj20258.top/Article/details/gtuoppdbbb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtewfkvrnl.html

[G16] 对象转数组 / 字典
来源：http://dali.mhx1999.top/Article/details/gtycxgnprd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daxiang520.top/Article/details/gtyzzqhrfg.html

PHP:  get_object_vars($obj);
来源：http://dali.yuxming.cn/Article/details/gtoyafovkd.html

JS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gtwkyqbyjr.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhequwlp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj202588.top/Article/details/gtoldnxtqf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xuanzx.com/Article/details/gtaknozvpx.html

Ruby: obj.instance_variables
来源：http://dali.cdnleiting.top/Article/details/gtrbfvjutf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sysykeji.top/Article/details/gtjlaemvix.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtjnyikbkf.html

H. 异常与错误处理
来源：http://dali.zhixingplan.top/Article/details/gtyuyrener.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtmqvbatnw.html

[H01] try / catch 基础
来源：http://dali.jinqigfzy.top/Article/details/gtajubfkhe.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.quarkkingdee.top/Article/details/gtvimkelrf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.aizwys.cn/Article/details/gtdsvihjts.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gtqvjfdbbm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gtrglejwlv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ehwqpu.com/Article/details/gtdykbmzly.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhongyouzk.top/Article/details/gtnnkhvfpa.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.quarkkingdee.top/Article/details/gtinriuhno.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yonumen.top/Article/details/gtrewlsqjz.html

[H02] finally / ensure 收尾
来源：http://dali.zhixingplan.top/Article/details/gtkvvsvvbj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cqqwz.cn/Article/details/gtwowsgduf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtydcmcmpk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtanwrsamw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtrwjcleeq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gttwkgyniv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ppjwa.cn/Article/details/gtzlreievq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.haohaochexian.top/Article/details/gtzldnxixw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtsakohxlr.html

[H03] 主动抛出异常
来源：http://dali.xinyue.icu/Article/details/gtelyrztbl.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenjidiqi.icu/Article/details/gtdbqwaivg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtshzgzsdu.html

JS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtrvouctex.html

TS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtwfoshxxo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtyxtlzbyt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.bjfxy.top/Article/details/gtqyoswkwu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhiwuduotai.top/Article/details/gtooagjpfu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtajduolmq.html

[H04] 自定义异常类型
来源：http://dali.nanxinkj.top/Article/details/gthoxtlyly.html

Py:   class MyError(Exception): pass
来源：http://dali.andypj.xyz/Article/details/gticmuwaju.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ppjwa.cn/Article/details/gtlwuimlob.html

JS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gtywxrvvkj.html

TS:   class MyError extends Error {}
来源：http://dali.jianghu66.top/Article/details/gtffuqgqnz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gtuqkhmxgc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258888.top/Article/details/gtzrprcoqa.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuanzhike.top/Article/details/gtrjysxtiu.html

C#:   class MyException : Exception {}
来源：http://dali.yvedp.cn/Article/details/gtjuagcnji.html

[H05] 捕获特定类型
来源：http://dali.tanke756.top/Article/details/gtrxtzoqqq.html

Py:   except ValueError as e:
来源：http://dali.iojbl.cn/Article/details/gtnacftece.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yvedp.cn/Article/details/gtvmharrmc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtbvdxshkz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gtkkyvycil.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gtgivgkugc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrcktwcz.html

Ruby: rescue ArgumentError => e
来源：http://dali.xuanzx.com/Article/details/gtegdkxvhr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tianlin.xyz/Article/details/gttzowsnpz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guowangkeji.top/Article/details/gteosusstb.html

Py:   value = d.get("k") or default
来源：http://dali.gotoacloud.top/Article/details/gtznlpaxxj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cheryme.top/Article/details/gticuenetv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cqqwz.cn/Article/details/gtxjendjkj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.smart0.xyz/Article/details/gtaspnwitd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.meibo888.top/Article/details/gtkskujzbd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.birdmap.top/Article/details/gtkpovejfk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvrrqqwtb.html

C#:   obj?.A?.B ?? default
来源：http://dali.nwbrower.top/Article/details/gtmkjdttvb.html

[H07] 断言
来源：http://dali.jiagoushi.top/Article/details/gtxhkdbbza.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yvedp.cn/Article/details/gtqtfgjyeb.html

PHP:  assert($x > 0);
来源：http://dali.c1oappe.top/Article/details/gtzunjsrgp.html

JS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gttbotrwcu.html

TS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gtxeojjwcp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zycfv.cn/Article/details/gtbuejqrwd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ppjwa.cn/Article/details/gtwpxkrzoh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shuidangran.top/Article/details/gtrqubksnp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gtgbxpdnex.html

[H08] 获取错误信息与堆栈
来源：http://dali.hfpthk.cn/Article/details/gtkxcidpto.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinqigfzy.top/Article/details/gtybbxiych.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hysaishi.cn/Article/details/gtzscoarzh.html

JS:   e.message;  e.stack
来源：http://dali.zhaomingkeji.xyz/Article/details/gttwvkfsms.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.havefunace.top/Article/details/gtlibtoeqx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.vqdsnc.cn/Article/details/gtgscgcgkc.html

Go:   err.Error()
来源：http://dali.cdnleiting.top/Article/details/gtrcjrwljr.html

Ruby: e.message;  e.backtrace
来源：http://dali.hysaishi.cn/Article/details/gtlnimoygy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fengsongda.top/Article/details/gtthzsbtvo.html

[H09] 带错误码的异常
来源：http://dali.snrcjt.cn/Article/details/gtbqwhohkv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guowangkeji.top/Article/details/gtlhvjekdt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pengpengdd.cyou/Article/details/gtmhtjiico.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.316326.xyz/Article/details/gtzktxzsus.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yongpay.top/Article/details/gtsuskqsez.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gtkgeadjbg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ppjwa.cn/Article/details/gtalzutaqr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zycfv.cn/Article/details/gtqmpbbvzm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.daxiang520.top/Article/details/gthrpeqwkc.html

[H10] 资源自动释放
来源：http://dali.xuetiantiany.cn/Article/details/gtvnaazxjw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.redwolf501.top/Article/details/gtbxhdmhvi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbmngmoqc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gtbtqqgzhy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnxiangtu.top/Article/details/gtaxauxrkq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.iojbl.cn/Article/details/gtqguiilaa.html

Go:   defer f.Close()
来源：http://dali.ehwqpu.com/Article/details/gttkiuveds.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ydzc1.top/Article/details/gtijkbzohq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cheryme.top/Article/details/gtmwvbaugs.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtcufnmfde.html

I. 正则表达式
来源：http://dali.gogol.net.cn/Article/details/gtjopevydz.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtdemqegsf.html

[I01] 判断是否匹配
来源：http://dali.xinyue.icu/Article/details/gtrwykhjua.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsnzowokq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sysykeji.top/Article/details/gtatnphxvv.html

JS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gtwjlcfers.html

TS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gtiltakyzx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.c1oappe.top/Article/details/gtdcvxciej.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtgdbrurwa.html

Ruby: s.match?(/\d+/)
来源：http://dali.dashuyun.cn/Article/details/gtrisrohyk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xuetiantiany.cn/Article/details/gthzqdmmcz.html

[I02] 提取所有匹配
来源：http://dali.fengsongda.top/Article/details/gtjpopwort.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yonumen.top/Article/details/gtjsdsopvo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.kuanghao11.cn/Article/details/gtujommcgi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuxming.cn/Article/details/gtsfmrdmna.html

TS:   s.match(/\d+/g)
来源：http://dali.yj20258888.top/Article/details/gtuweqimmb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sufxvd.cn/Article/details/gttpbdjupk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xylfe.cn/Article/details/gtjcfuehky.html

Ruby: s.scan(/\d+/)
来源：http://dali.smart0.xyz/Article/details/gtcerunphm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hnqzz.top/Article/details/gtfhlrleie.html

[I03] 提取捕获分组
来源：http://dali.jianghu66.top/Article/details/gtcwxmjmhq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xziqi.cn/Article/details/gtdaptyfbj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jiagoushi.top/Article/details/gtgvqlzinl.html


<!-- 参考信息 -->