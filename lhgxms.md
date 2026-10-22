代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258.top/Article/details/gtahttgzpt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gtoccarmig.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhengqikj.top/Article/details/gtxrgjhvhd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yvedp.cn/Article/details/gtnflelwem.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinqigfzy.top/Article/details/gthqcszsup.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tanke756.top/Article/details/gtqifwxlxr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jianghu66.top/Article/details/gtoixmucsb.html

[F08] 遍历目录
来源：http://dali.yanxiufei.cn/Article/details/gtticwezwj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tianlin.xyz/Article/details/gtzaipntkm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.bjfxy.top/Article/details/gtoqnpazhp.html

JS:   fs.readdirSync("dir")
来源：http://dali.cdnleiting.top/Article/details/gtedelrrvf.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtegqxxnxt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xinyue.icu/Article/details/gtohoboydq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtvvtoiiwc.html

Ruby: Dir.children("dir")
来源：http://dali.smart0.xyz/Article/details/gtmjvhljer.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtayjydnpa.html

[F09] 获取文件大小
来源：http://dali.xuetiantiany.cn/Article/details/gtgyrvydrk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj20258.top/Article/details/gtneqsedaf.html

PHP:  filesize("a.txt");
来源：http://dali.cheryme.top/Article/details/gtkxuhppar.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gtcqrdbrpl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sufxvd.cn/Article/details/gtioazuutc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtppvaiden.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cucudq.cn/Article/details/gtkdaacusw.html

Ruby: File.size("a.txt")
来源：http://dali.sweek.top/Article/details/gtgovhzhim.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuanzhike.top/Article/details/gtkgpxzizu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jiagoushi.top/Article/details/gtzpzlvcgu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtgfwlqusj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtnbjlephk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtbntooqyo.html

TS:   path.extname("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtqmqwktfy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.daria6918.cn/Article/details/gtxjlowdtz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtucedpazj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtenzgkbxu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtdfvqeunv.html

[F11] 复制与移动文件
来源：http://dali.zhoulong.xyz/Article/details/gtcigazvft.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtwrjehcve.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tanke756.top/Article/details/gtcpnsetob.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtzpqnmyai.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtoljbykwa.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtgqgykevb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tanke756.top/Article/details/gtmleezepm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtuuxcmxrs.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daxiang520.top/Article/details/gtsehjvbiv.html

[F12] CSV 读写
来源：http://dali.chenzaomai.com/Article/details/gtpyiguzbw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xziqi.cn/Article/details/gtxrntjidp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.pycfn.com/Article/details/gtefbpaexa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pengpengdd.cyou/Article/details/gtjnuidgfr.html

TS:   // 同上
来源：http://dali.yongpay.top/Article/details/gtpawvilcg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigfzy.top/Article/details/gthaovufoh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.daria6918.cn/Article/details/gtwtpcbypz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cashguo.top/Article/details/gtccihsagw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yonumen.top/Article/details/gtqhvhxxmk.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtjfzvhzfg.html

G. 面向对象
来源：http://dali.zhiwuduotai.top/Article/details/gtsmjntilf.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtckonkufj.html

[G01] 定义类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtundkkggp.html

Py:   class User: pass
来源：http://dali.svipenyu.cn/Article/details/gtuexqstwc.html

PHP:  class User {}
来源：http://dali.hammf.cn/Article/details/gtdvuqrmiw.html

JS:   class User {}
来源：http://dali.yj202588.top/Article/details/gtjgduvuul.html

TS:   class User { name: string = ""; }
来源：http://dali.tian-w.cn/Article/details/gtugccjsch.html

Java: class User {}
来源：http://dali.jiagoushi.top/Article/details/gtmiwgqdhk.html

Go:   type User struct { Name string }
来源：http://dali.hnxiangtu.top/Article/details/gtocmnqdum.html

Ruby: class User; end
来源：http://dali.9152youxi.cn/Article/details/gtipamtogk.html

C#:   class User {}
来源：http://dali.smart0.xyz/Article/details/gtetjgggwu.html

[G02] 构造函数
来源：http://dali.guannengcc.top/Article/details/gttbohdqmo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258.top/Article/details/gtcqvlvgde.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gtiimtfbti.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gtjmeqrgpu.html

TS:   constructor(public name: string) {}
来源：http://dali.wangdashe.top/Article/details/gtllqkqojf.html

Java: User(String name) { this.name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gttycxpcvo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ivvv.top/Article/details/gtwmwdthuj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangdashe.top/Article/details/gtcpyqkdjv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tianlin.xyz/Article/details/gtlwkiwown.html

[G03] 实例属性
来源：http://dali.shangyingyoupin.top/Article/details/gtbciujuup.html

Py:   self.name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gtplduetdb.html

PHP:  public string $name = "x";
来源：http://dali.yuanzhike.top/Article/details/gtqulatykg.html

JS:   this.name = "x";
来源：http://dali.tian-w.cn/Article/details/gtglcmivfh.html

TS:   name: string = "x";
来源：http://dali.sxryk.cn/Article/details/gtrcsqnhhw.html

Java: private String name;
来源：http://dali.nwbrower.top/Article/details/gtpvljlexx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.feifeiyinyue.top/Article/details/gtrqezemla.html

Ruby: @name = "x"
来源：http://dali.hongshengwenyu.top/Article/details/gteepsiolg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shzxlz.cn/Article/details/gtnaepdnre.html

[G04] 定义方法
来源：http://dali.hnxiangtu.top/Article/details/gtpeawdbng.html

Py:   def greet(self): return self.name
来源：http://dali.ivvv.top/Article/details/gttvtpuuyp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gtwbuvgipq.html

JS:   greet() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gteplrzhes.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtaghdglwx.html

Java: String greet() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtqeyxqsgu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtqbiwccag.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gtjbidwenp.html

C#:   public string Greet() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gtmelzeqmn.html

[G05] 继承
来源：http://dali.havefunace.top/Article/details/gtpjistmdy.html

Py:   class Admin(User): pass
来源：http://dali.yangfankeji.com/Article/details/gtrxqjznzu.html

PHP:  class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtbrzdurmk.html

JS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtshhkyqvd.html

TS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtkxlsbxlm.html

Java: class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gttgdewijn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenzaomai.com/Article/details/gtftbtxiqw.html

Ruby: class Admin < User; end
来源：http://dali.guannengcc.top/Article/details/gtouvzqdvd.html

C#:   class Admin : User {}
来源：http://dali.hnqzz.top/Article/details/gtdkpzrjdx.html

[G06] 重写方法
来源：http://dali.jianghu66.top/Article/details/gtmxrbkjjd.html

Py:   def greet(self): return "admin"
来源：http://dali.iojbl.cn/Article/details/gtbnqazsny.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtyyndhofl.html

JS:   greet() { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtlkrvsqtt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtzidjliqv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gthtcmztqh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yongpay.top/Article/details/gtwdabtjpz.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzefhmlil.html

C#:   public override string Greet() => "admin";
来源：http://dali.xinyue.icu/Article/details/gtduyadgnx.html

[G07] 调用父类方法
来源：http://dali.quarkkingdee.top/Article/details/gtvehuvanf.html

Py:   super().greet()
来源：http://dali.yongpay.top/Article/details/gtnjgamxpt.html

PHP:  parent::greet();
来源：http://dali.ydzc1.top/Article/details/gtiguetgtl.html

JS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gtlnnwdzzy.html

TS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gthtueuite.html

Java: super.greet();
来源：http://dali.fengsongda.top/Article/details/gtbepsosdg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenjidiqi.icu/Article/details/gtkdjamoji.html

Ruby: super
来源：http://dali.yueranfly.top/Article/details/gtqawjslqd.html

C#:   base.Greet();
来源：http://dali.zhongyouzk.top/Article/details/gtzqoxdccm.html

[G08] 静态方法与属性
来源：http://dali.nwbrower.top/Article/details/gtwgaouyny.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.birdmap.top/Article/details/gtnxdberuf.html

PHP:  public static function f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtuenpzrog.html

JS:   static f() {}
来源：http://dali.zhoulong.xyz/Article/details/gtebzyasoe.html

TS:   static f(): void {}
来源：http://dali.chenzaomai.com/Article/details/gtlgfogzsc.html

Java: static void f() {}
来源：http://dali.xylfe.cn/Article/details/gtbxaufeso.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.haohaochexian.top/Article/details/gtcxlsvitj.html

Ruby: def self.f; end
来源：http://dali.aibaodan.cn/Article/details/gtqtauwfjj.html

C#:   public static void F() {}
来源：http://dali.c1oappe.top/Article/details/gtxhqupulx.html

[G09] 接口 / 抽象类
来源：http://dali.nanxuanxn.top/Article/details/gtfnesurqv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ppjwa.cn/Article/details/gtstydyngx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.snrcjt.cn/Article/details/gttoxxjlal.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zycfv.cn/Article/details/gtbnvgnthp.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenjidiqi.icu/Article/details/gtjilwgnze.html

Java: interface Shape { double area(); }
来源：http://dali.zhixingplan.top/Article/details/gtcxmkacvo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dianchejie.cn/Article/details/gtldhnkifw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jiagoushi.top/Article/details/gtxgimiipn.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj202588.top/Article/details/gtbbepilyh.html

[G10] 访问控制
来源：http://dali.vqdsnc.cn/Article/details/gtwkhiqkck.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangdashe.top/Article/details/gtrglvrcnv.html

PHP:  public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gteihtfwxw.html

JS:   #private 字段；其余公开
来源：http://dali.chenlongwang.top/Article/details/gtcamoqbha.html

TS:   public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gtpoowneqj.html

Java: public / protected / private / 默认包级
来源：http://dali.ydzc1.top/Article/details/gtnkzxrmqn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yueranfly.top/Article/details/gtqpawseca.html

Ruby: public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtoapinpax.html

C#:   public / protected / private / internal
来源：http://dali.guannengcc.top/Article/details/gtdgtapczz.html

[G11] getter / setter
来源：http://dali.jqgfzy.top/Article/details/gtagctlgmd.html

Py:   @property 与 @x.setter
来源：http://dali.guowangkeji.top/Article/details/gtqaaxlxlb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqoypmbs.html

JS:   get name() { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gtwfvypfwv.html

TS:   get name(): string { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gtvsstdnei.html

Java: public String getName() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtzzzkoncm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gturhmemli.html

Ruby: attr_accessor :name
来源：http://dali.shzxlz.cn/Article/details/gtarxxeyiy.html

C#:   public string Name { get; set; }
来源：http://dali.fzhhl.top/Article/details/gtgnjgrbiy.html

[G12] 对象转字符串
来源：http://dali.jlsjyb.cn/Article/details/gtvkvjthlu.html

Py:   def __str__(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gtweyzjria.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtfrugtdzy.html

JS:   toString() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gtpstkltxz.html

TS:   toString(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtekvjucnq.html

Java: @Override public String toString() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtxqnxlyex.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gteltzzmtr.html

Ruby: def to_s; @name; end
来源：http://dali.ehwqpu.com/Article/details/gthpeeytro.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gtomthgpyo.html

[G13] 判断对象类型
来源：http://dali.yonumen.top/Article/details/gtldkfwogg.html

Py:   isinstance(u, User)
来源：http://dali.hnxiangtu.top/Article/details/gtqwqlhfcp.html

PHP:  $u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtodwvprpg.html

JS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtaeirlloe.html

TS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtormejtti.html

Java: u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtycymbhdr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.guannengcc.top/Article/details/gtwvlaueqq.html

Ruby: u.is_a?(User)
来源：http://dali.hongshengwenyu.top/Article/details/gtaaroiztk.html

C#:   u is User
来源：http://dali.nwbrower.top/Article/details/gtuasmgthq.html

[G14] 数据类 / record
来源：http://dali.svipenyu.cn/Article/details/gtdnklxwoy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sysykeji.top/Article/details/gtvkqmwfnb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnxiangtu.top/Article/details/gtfafravqp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuetiantiany.cn/Article/details/gthhlcaliy.html

TS:   type User = { name: string; age: number };
来源：http://dali.tianlin.xyz/Article/details/gtauearrgz.html

Java: record User(String name, int age) {}
来源：http://dali.tian-w.cn/Article/details/gtxswghjek.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tianlin.xyz/Article/details/gtuyfqysku.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenzaomai.com/Article/details/gtxrfrisru.html

C#:   record User(string Name, int Age);
来源：http://dali.zhongyouzk.top/Article/details/gtgdksmzfa.html

[G15] 枚举
来源：http://dali.hnqzz.top/Article/details/gtzubxstyn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gogol.net.cn/Article/details/gtjpjtzzqz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenzaomai.com/Article/details/gttqhkbguh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tianlin.xyz/Article/details/gtrgqdwdqn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtiqqfeyfa.html

Java: enum Color { RED, GREEN }
来源：http://dali.ppjwa.cn/Article/details/gtrfxwgkrf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yongpay.top/Article/details/gtfjhzuupo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jianghu66.top/Article/details/gtliqqnfzc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtorasxlit.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgfzy.top/Article/details/gtaglqbdyo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjgiakym.html

PHP:  get_object_vars($obj);
来源：http://dali.zycfv.cn/Article/details/gtapckbfmp.html

JS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gtqrlyrmtt.html

TS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gtocwqtckm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gtszuymycf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenlongwang.top/Article/details/gtspusvmpl.html

Ruby: obj.instance_variables
来源：http://dali.sxryk.cn/Article/details/gtzxhzzeus.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gtkioxjain.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gttaijbuyt.html

H. 异常与错误处理
来源：http://dali.316326.xyz/Article/details/gtdnsbufbs.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtoeeukskd.html

[H01] try / catch 基础
来源：http://dali.chenjidiqi.icu/Article/details/gtcksobsfq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aibaodan.cn/Article/details/gttwtcurnd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.aibaodan.cn/Article/details/gtivdwokpe.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gtrcymokxe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gtzkfpxzxy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hysaishi.cn/Article/details/gtumrigmak.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cdnleiting.top/Article/details/gtuzabqgry.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yuanzhike.top/Article/details/gteioifupt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhongyouzk.top/Article/details/gteioekwvx.html

[H02] finally / ensure 收尾
来源：http://dali.shuidangran.top/Article/details/gtjkfespwt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tianlin.xyz/Article/details/gtjnnfugiy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtvjoypnvp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtdhyilzhj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtqlazaeea.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtvtdopibp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwiicioda.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.vqdsnc.cn/Article/details/gtclvfmuwy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtokzsipbb.html

[H03] 主动抛出异常
来源：http://dali.cdnleiting.top/Article/details/gtaloaudex.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtphnxzucp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtmjbxbuzg.html

JS:   throw new Error("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtscolwuog.html

TS:   throw new Error("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtotminohx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gtnnijwfus.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daxiang520.top/Article/details/gtgahmyxnc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gzhubu.top/Article/details/gttzdlqjgf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtjukcgxbo.html

[H04] 自定义异常类型
来源：http://dali.snrcjt.cn/Article/details/gtitdbxqmm.html

Py:   class MyError(Exception): pass
来源：http://dali.sysykeji.top/Article/details/gtfhxrtmfi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.c1oappe.top/Article/details/gtwmncsncb.html

JS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gtrmgxicys.html

TS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmsjxouu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhoulong.xyz/Article/details/gtsfknathq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sysykeji.top/Article/details/gtxwcwraer.html

Ruby: class MyError < StandardError; end
来源：http://dali.cheryme.top/Article/details/gtudpnjtpv.html

C#:   class MyException : Exception {}
来源：http://dali.dianchejie.cn/Article/details/gtsoxhjyfi.html

[H05] 捕获特定类型
来源：http://dali.ppjwa.cn/Article/details/gtxsjdixev.html

Py:   except ValueError as e:
来源：http://dali.xuanzx.com/Article/details/gtmsxwuxlk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.snrcjt.cn/Article/details/gtojscagcz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehghfvqy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gtbdkgezwu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hfpthk.cn/Article/details/gtvndyttrg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shzxlz.cn/Article/details/gtoolsifpn.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangdashe.top/Article/details/gtvzcytfpr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cashguo.top/Article/details/gtrusmmvnu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gtxjrxxnaw.html

Py:   value = d.get("k") or default
来源：http://dali.zhengqikj.top/Article/details/gtdxvsjrdc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gtzsysdihm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gtzhwafuxh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gtrqyirawi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sufxvd.cn/Article/details/gtmdjildsh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangdashe.top/Article/details/gtglkezkjj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuanzhike.top/Article/details/gtyclrmgkx.html

C#:   obj?.A?.B ?? default
来源：http://dali.meibo888.top/Article/details/gtdenvrkvv.html

[H07] 断言
来源：http://dali.smart0.xyz/Article/details/gtmbfisqgj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxuanxn.top/Article/details/gttvojmnfm.html

PHP:  assert($x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtlbqmwstq.html

JS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtgmyntanj.html

TS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtpextacrq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aibaodan.cn/Article/details/gtgcqfabyf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258.top/Article/details/gtxrcbhvmj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yueranfly.top/Article/details/gttqtprlbf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtmrvvupqb.html

[H08] 获取错误信息与堆栈
来源：http://dali.redwolf501.top/Article/details/gtzxdzrgej.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jianghu66.top/Article/details/gtkmzijkxo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hammf.cn/Article/details/gtoieuykti.html

JS:   e.message;  e.stack
来源：http://dali.yvedp.cn/Article/details/gtqjcrtdbp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtarwavzfj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shuidangran.top/Article/details/gtnoaxluji.html

Go:   err.Error()
来源：http://dali.svipenyu.cn/Article/details/gtyxuqrluc.html

Ruby: e.message;  e.backtrace
来源：http://dali.hfpthk.cn/Article/details/gtrtbtmbtw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhoulong.xyz/Article/details/gtmuljsata.html

[H09] 带错误码的异常
来源：http://dali.hnqzz.top/Article/details/gtfczbibsc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.daxiang520.top/Article/details/gtodrdpkmq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxpbfeakn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yuanzhike.top/Article/details/gtuumgrlvr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gteofaumta.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.andypj.xyz/Article/details/gtnsqkmyrr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhixingplan.top/Article/details/gtmpdhioqa.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhixingplan.top/Article/details/gtrkgkkrdi.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.kuanghao11.cn/Article/details/gtwsjjjnab.html

[H10] 资源自动释放
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfrjtoha.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hfpthk.cn/Article/details/gtygkfhexo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj20258.top/Article/details/gtnmqoacqo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgfzy.top/Article/details/gtxihsbtqy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gtwihopbcw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgfzy.top/Article/details/gtytmiweey.html

Go:   defer f.Close()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbfbgykuv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.wangdashe.top/Article/details/gtzbsmnzkl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gttyyvprsj.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtzbscarzl.html

I. 正则表达式
来源：http://dali.xuanzx.com/Article/details/gtnwyqxdkn.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtovxbauvs.html

[I01] 判断是否匹配
来源：http://dali.hysaishi.cn/Article/details/gtmhvhazrm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jqgufenzy.top/Article/details/gtnouiqncf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.c1oappe.top/Article/details/gttjcagyax.html

JS:   /\d+/.test(s)
来源：http://dali.yongpay.top/Article/details/gtkycknnom.html

TS:   /\d+/.test(s)
来源：http://dali.daxiang520.top/Article/details/gtzkavulti.html


<!-- 参考信息 -->