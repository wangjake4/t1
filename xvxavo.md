代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.andypj.xyz/Article/details/gtwzklvrkl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhiwuduotai.top/Article/details/gtaflatvqn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxinkj.top/Article/details/gtzdjfjnii.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pycfn.com/Article/details/gtyhscaxzx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhixingplan.top/Article/details/gtvcvmqqvw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jyoumei.cn/Article/details/gtidpfvomc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtarahvbaw.html

[F08] 遍历目录
来源：http://dali.havefunace.top/Article/details/gttaxcjmfx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cdnleiting.top/Article/details/gtfldesaal.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.fengsongda.top/Article/details/gtzcwsslel.html

JS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gtiorxkpmg.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtcgyfcpru.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenjidiqi.icu/Article/details/gtcoubsmyt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhengqikj.top/Article/details/gtxujccpqa.html

Ruby: Dir.children("dir")
来源：http://dali.xylfe.cn/Article/details/gtukkxfduo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.daria6918.cn/Article/details/gtmoaawmvr.html

[F09] 获取文件大小
来源：http://dali.xinyue.icu/Article/details/gtqzaakbug.html

Py:   os.path.getsize("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtgapkbtnq.html

PHP:  filesize("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtgnluszkm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cheryme.top/Article/details/gtgrpwofag.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gotoacloud.top/Article/details/gtbbcacwoq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtlvjycpik.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.svipenyu.cn/Article/details/gtqhtchvac.html

Ruby: File.size("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtyjwuvfux.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.9152youxi.cn/Article/details/gtilnsnvqp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.birdmap.top/Article/details/gthqvcokkq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtxxxfxhdb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yvedp.cn/Article/details/gtaohaomtd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtcahtubxe.html

TS:   path.extname("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtiqndelgj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.haohaochexian.top/Article/details/gtphxxmyku.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gthutzgnmp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtmxvqcnjz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtcbgilcea.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtloenouwb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtkedjmhte.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yvedp.cn/Article/details/gtypykbsgz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtuqcnemlv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gthajerwzo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.wangdashe.top/Article/details/gtefbnjwbo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nanxinkj.top/Article/details/gtlgedckbp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtkuexpijb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.wangshuangyany.cn/Article/details/gtjowwnlzm.html

[F12] CSV 读写
来源：http://dali.svipenyu.cn/Article/details/gttorcmtqf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.iojbl.cn/Article/details/gtsngskrpx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.c1oappe.top/Article/details/gthgfylilh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nwbrower.top/Article/details/gtgtozzdse.html

TS:   // 同上
来源：http://dali.yj202588.top/Article/details/gtbmpievtd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangshuangyany.cn/Article/details/gtnftwoxel.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhoulong.xyz/Article/details/gtxeozkqqd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.c1oappe.top/Article/details/gtwskcnxkh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yanxiufei.cn/Article/details/gtuacqnced.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtxufgbbzy.html

G. 面向对象
来源：http://dali.cqqwz.cn/Article/details/gttgfaceoc.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtxzanodnv.html

[G01] 定义类
来源：http://dali.jqgufenzy.top/Article/details/gtedpmjuey.html

Py:   class User: pass
来源：http://dali.hammf.cn/Article/details/gtwfcobjtn.html

PHP:  class User {}
来源：http://dali.daria6918.cn/Article/details/gttbbrfwwb.html

JS:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gtwpwyzemj.html

TS:   class User { name: string = ""; }
来源：http://dali.svipenyu.cn/Article/details/gtmehyjgmo.html

Java: class User {}
来源：http://dali.ybcxt.top/Article/details/gtnmyrpcfj.html

Go:   type User struct { Name string }
来源：http://dali.gotoacloud.top/Article/details/gtqddlszqj.html

Ruby: class User; end
来源：http://dali.vqdsnc.cn/Article/details/gtztyjehbx.html

C#:   class User {}
来源：http://dali.xziqi.cn/Article/details/gttjhtdroi.html

[G02] 构造函数
来源：http://dali.nanxinkj.top/Article/details/gtxvunrmib.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xziqi.cn/Article/details/gtsieqzkbs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnqzz.top/Article/details/gtrvavvuoc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqirbthzr.html

TS:   constructor(public name: string) {}
来源：http://dali.zhixingplan.top/Article/details/gtgcwvuncz.html

Java: User(String name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gtmfrxrfco.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jlsjyb.cn/Article/details/gtllvdngqd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hnxiangtu.top/Article/details/gthvzvapsj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258.top/Article/details/gtjwzfazsk.html

[G03] 实例属性
来源：http://dali.svipenyu.cn/Article/details/gtkazmwlai.html

Py:   self.name = "x"
来源：http://dali.hammf.cn/Article/details/gtwdostkxm.html

PHP:  public string $name = "x";
来源：http://dali.aizwys.cn/Article/details/gtdtowvmsc.html

JS:   this.name = "x";
来源：http://dali.yj20258.top/Article/details/gtfhimksvx.html

TS:   name: string = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtzuswevkl.html

Java: private String name;
来源：http://dali.cdnleiting.top/Article/details/gtnzdzbfjz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hfpthk.cn/Article/details/gtmasmxzpu.html

Ruby: @name = "x"
来源：http://dali.c1oappe.top/Article/details/gtvkfvinwt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guannengcc.top/Article/details/gtftnzjfmj.html

[G04] 定义方法
来源：http://dali.cashguo.top/Article/details/gttdlnbrvg.html

Py:   def greet(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gtliqcnfto.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhdgpefr.html

JS:   greet() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtpgafrixt.html

TS:   greet(): string { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtjdbgcvzg.html

Java: String greet() { return name; }
来源：http://dali.cashguo.top/Article/details/gtqalmlhas.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtjymplrsn.html

Ruby: def greet; @name; end
来源：http://dali.sxryk.cn/Article/details/gtfywssmpy.html

C#:   public string Greet() => Name;
来源：http://dali.jyoumei.cn/Article/details/gtctbfavkm.html

[G05] 继承
来源：http://dali.gotoacloud.top/Article/details/gtkatkwfez.html

Py:   class Admin(User): pass
来源：http://dali.havefunace.top/Article/details/gtgsmjccbv.html

PHP:  class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtizoevgnr.html

JS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtiaxtaonv.html

TS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtwqwrzuef.html

Java: class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtdayqubdy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.dianchejie.cn/Article/details/gtglbozuup.html

Ruby: class Admin < User; end
来源：http://dali.cdnleiting.top/Article/details/gtxhbvebxu.html

C#:   class Admin : User {}
来源：http://dali.dashuyun.cn/Article/details/gtxphiqeuu.html

[G06] 重写方法
来源：http://dali.jianghu66.top/Article/details/gtinlqrqdq.html

Py:   def greet(self): return "admin"
来源：http://dali.zhongyouzk.top/Article/details/gtjwekztbu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtcykvwaow.html

JS:   greet() { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtlediiqkh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gthlsadivt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtwhvkeqhv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.dashuyun.cn/Article/details/gtgwjfwcfw.html

Ruby: def greet; "admin"; end
来源：http://dali.snrcjt.cn/Article/details/gtcgxnmant.html

C#:   public override string Greet() => "admin";
来源：http://dali.yanxiufei.cn/Article/details/gtrlxwswci.html

[G07] 调用父类方法
来源：http://dali.shuidangran.top/Article/details/gtqjqkvsyi.html

Py:   super().greet()
来源：http://dali.hysaishi.cn/Article/details/gtmiqmwvqr.html

PHP:  parent::greet();
来源：http://dali.tanke756.top/Article/details/gtagxsusym.html

JS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtkhbdznra.html

TS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gtjsvqnnqf.html

Java: super.greet();
来源：http://dali.aibaodan.cn/Article/details/gtpkxfnqab.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.fzhhl.top/Article/details/gtjrbqtkds.html

Ruby: super
来源：http://dali.wangshuangyany.cn/Article/details/gtvwbxjijm.html

C#:   base.Greet();
来源：http://dali.cdnleiting.top/Article/details/gtdbgbcorg.html

[G08] 静态方法与属性
来源：http://dali.haohaochexian.top/Article/details/gtxdrxhhgj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.0kj1m.cn/Article/details/gtqsspnrfo.html

PHP:  public static function f() {}
来源：http://dali.hammf.cn/Article/details/gtwrtemcbv.html

JS:   static f() {}
来源：http://dali.316326.xyz/Article/details/gtjevpnnuy.html

TS:   static f(): void {}
来源：http://dali.chenzaomai.com/Article/details/gtxaypbhvc.html

Java: static void f() {}
来源：http://dali.andypj.xyz/Article/details/gtrybpypwj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dianchejie.cn/Article/details/gtaqcvzrdl.html

Ruby: def self.f; end
来源：http://dali.cucudq.cn/Article/details/gtdipswmzh.html

C#:   public static void F() {}
来源：http://dali.yvedp.cn/Article/details/gtkoajtpvw.html

[G09] 接口 / 抽象类
来源：http://dali.gaohongyu789.top/Article/details/gtielrhwdu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jyoumei.cn/Article/details/gtnoqxpazf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gotoacloud.top/Article/details/gtddtduike.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj202588.top/Article/details/gtmrqpngev.html

TS:   interface Shape { area(): number; }
来源：http://dali.cheryme.top/Article/details/gtljzykroq.html

Java: interface Shape { double area(); }
来源：http://dali.snrcjt.cn/Article/details/gtleobsrzs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yuanzhike.top/Article/details/gtsgatxsrr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cqqwz.cn/Article/details/gtpidjcflr.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenlongwang.top/Article/details/gtrzylcmaj.html

[G10] 访问控制
来源：http://dali.gaohongyu789.top/Article/details/gtfifpflxf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.havefunace.top/Article/details/gthyhkqjmg.html

PHP:  public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gtqrrzzyxj.html

JS:   #private 字段；其余公开
来源：http://dali.shzxlz.cn/Article/details/gtankoslaj.html

TS:   public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gttgiugvcn.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigfzy.top/Article/details/gtzlaebjlz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jqgufenzy.top/Article/details/gtimawsncj.html

Ruby: public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtvegoqqrj.html

C#:   public / protected / private / internal
来源：http://dali.dashuyun.cn/Article/details/gtlqqhpwww.html

[G11] getter / setter
来源：http://dali.wangshuangyany.cn/Article/details/gtgruuflwe.html

Py:   @property 与 @x.setter
来源：http://dali.nanxuanxn.top/Article/details/gtzdbpfyrs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtccptbtir.html

JS:   get name() { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtjtpxqtuv.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxinkj.top/Article/details/gtvsjwlqjn.html

Java: public String getName() { return name; }
来源：http://dali.smart0.xyz/Article/details/gtunlhppnq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gteavwbxgh.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gtpsgqidah.html

C#:   public string Name { get; set; }
来源：http://dali.hnqzz.top/Article/details/gtswgxknzn.html

[G12] 对象转字符串
来源：http://dali.svipenyu.cn/Article/details/gtcclkfgmx.html

Py:   def __str__(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gtarujekrf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gttierrhcb.html

JS:   toString() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtyhbigovf.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtpoytqdyi.html

Java: @Override public String toString() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtntfqkqjd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gtngyutawu.html

Ruby: def to_s; @name; end
来源：http://dali.vqdsnc.cn/Article/details/gtrqowflfz.html

C#:   public override string ToString() => Name;
来源：http://dali.hywenlv.cn/Article/details/gtadackrhm.html

[G13] 判断对象类型
来源：http://dali.pengpengdd.cyou/Article/details/gtgcgxxjwt.html

Py:   isinstance(u, User)
来源：http://dali.yonumen.top/Article/details/gtjwyvkwfz.html

PHP:  $u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtaokcgkky.html

JS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gttopfbydx.html

TS:   u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtolsnvgrz.html

Java: u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtcksovgxk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cucudq.cn/Article/details/gtqghmgucf.html

Ruby: u.is_a?(User)
来源：http://dali.guannengcc.top/Article/details/gtrufqaxve.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gturngmshs.html

[G14] 数据类 / record
来源：http://dali.wangdashe.top/Article/details/gtybwuyfpk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgfzy.top/Article/details/gtapwimfyi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yueranfly.top/Article/details/gtqnbaopqj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zycfv.cn/Article/details/gtjnwgcfhk.html

TS:   type User = { name: string; age: number };
来源：http://dali.fengsongda.top/Article/details/gtnustmcqw.html

Java: record User(String name, int age) {}
来源：http://dali.bjfxy.top/Article/details/gthxkpbdpk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aizwys.cn/Article/details/gtwpnmozex.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jianghu66.top/Article/details/gtxukfnkvd.html

C#:   record User(string Name, int Age);
来源：http://dali.tian-w.cn/Article/details/gtivdhohmz.html

[G15] 枚举
来源：http://dali.c1oappe.top/Article/details/gtnfizxxry.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ppjwa.cn/Article/details/gtcfncrdpf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hfpthk.cn/Article/details/gtibsengcn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.guowangkeji.top/Article/details/gtfgfvhtly.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shzxlz.cn/Article/details/gtbbnersga.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhoulong.xyz/Article/details/gtycfzefic.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258888.top/Article/details/gtaoqekkwn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xinyue.icu/Article/details/gtnczhxojz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xylfe.cn/Article/details/gtmvrqqsfj.html

[G16] 对象转数组 / 字典
来源：http://dali.aizwys.cn/Article/details/gtvdyvqakv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zdqjudy.top/Article/details/gtxwpmanqc.html

PHP:  get_object_vars($obj);
来源：http://dali.yuxming.cn/Article/details/gtwdaajxnw.html

JS:   Object.entries(obj)
来源：http://dali.pycfn.com/Article/details/gtjvbrwqmk.html

TS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmzmbsgza.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.svipenyu.cn/Article/details/gttjzlrmcj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jlsjyb.cn/Article/details/gtdvkxwjmn.html

Ruby: obj.instance_variables
来源：http://dali.hywenlv.cn/Article/details/gtrsidxius.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.havefunace.top/Article/details/gtsicabcwf.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtelmixlha.html

H. 异常与错误处理
来源：http://dali.fengsongda.top/Article/details/gtwtlpawri.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtfaljcaoq.html

[H01] try / catch 基础
来源：http://dali.jqgufenzy.top/Article/details/gtdttezzok.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.316326.xyz/Article/details/gtzxpssvln.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxuanxn.top/Article/details/gtmxyvuoeq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtyvjgteut.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gtmfnqhade.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.mhx1999.top/Article/details/gtxkskhbbk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hfpthk.cn/Article/details/gtifvodbtt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shzxlz.cn/Article/details/gtaohhouts.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhixingplan.top/Article/details/gtwhkfugfa.html

[H02] finally / ensure 收尾
来源：http://dali.yangfankeji.com/Article/details/gttabrlzhq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nanxinkj.top/Article/details/gtopiwyyxk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtazriaaed.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gteavyiarx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtbvumnlra.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gthcifaymo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.haohaochexian.top/Article/details/gtnrtelsxd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aibaodan.cn/Article/details/gtubgrwauf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtvlecumfw.html

[H03] 主动抛出异常
来源：http://dali.dianchejie.cn/Article/details/gtwubtgjdz.html

Py:   raise ValueError("错误信息")
来源：http://dali.yvedp.cn/Article/details/gtfpfjkyed.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtgchbyblw.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtvfodbsoc.html

TS:   throw new Error("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtpirubdbb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtrtquacsi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daria6918.cn/Article/details/gtjzsrvnhu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.redwolf501.top/Article/details/gtmfntgubh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gtphaqweox.html

[H04] 自定义异常类型
来源：http://dali.zhiwuduotai.top/Article/details/gtjsyvjwsl.html

Py:   class MyError(Exception): pass
来源：http://dali.dashuyun.cn/Article/details/gttpasslgq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gtjzyguxkn.html

JS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gtjgjgngma.html

TS:   class MyError extends Error {}
来源：http://dali.yj20258.top/Article/details/gtcyeyufwd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guowangkeji.top/Article/details/gtjcogamvy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gzhubu.top/Article/details/gtytaukymg.html

Ruby: class MyError < StandardError; end
来源：http://dali.vqdsnc.cn/Article/details/gtjptqsiwq.html

C#:   class MyException : Exception {}
来源：http://dali.zhoulong.xyz/Article/details/gtzabobquq.html

[H05] 捕获特定类型
来源：http://dali.zhixingplan.top/Article/details/gtnfydkwbn.html

Py:   except ValueError as e:
来源：http://dali.dashuyun.cn/Article/details/gtnxhmksxb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.smart0.xyz/Article/details/gtbuuicdye.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gtdpoaxlai.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gtzpmgbkqh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jiagoushi.top/Article/details/gtblbvhmlp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sufxvd.cn/Article/details/gtombsilse.html

Ruby: rescue ArgumentError => e
来源：http://dali.gzhubu.top/Article/details/gtphriqoyv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinqigfzy.top/Article/details/gtvqdyghun.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhiwuduotai.top/Article/details/gtymzgynln.html

Py:   value = d.get("k") or default
来源：http://dali.ivvv.top/Article/details/gtvozzcnlt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shzxlz.cn/Article/details/gtllwxpvas.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gtpchyenyu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gtfafjuwxb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aibaodan.cn/Article/details/gtwseeautu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.meibo888.top/Article/details/gtfrkdadlq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuanzhike.top/Article/details/gtucletqux.html

C#:   obj?.A?.B ?? default
来源：http://dali.havefunace.top/Article/details/gtndfxiqkk.html

[H07] 断言
来源：http://dali.hongshengwenyu.top/Article/details/gtsoyjhfsj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daxiang520.top/Article/details/gtemlrzybw.html

PHP:  assert($x > 0);
来源：http://dali.havefunace.top/Article/details/gtloggqutf.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gtaxrorghn.html

TS:   console.assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtjrkwmksu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258.top/Article/details/gtwhmjhvul.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.kuanghao11.cn/Article/details/gtmhaxcvhz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigufen.top/Article/details/gtmwmhypfc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtuofeojvh.html

[H08] 获取错误信息与堆栈
来源：http://dali.hysaishi.cn/Article/details/gtwnuojehw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinqigfzy.top/Article/details/gtogjfevai.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zdqjudy.top/Article/details/gteisxkbkh.html

JS:   e.message;  e.stack
来源：http://dali.redwolf501.top/Article/details/gtyvkvsbnf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvtastse.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhengqikj.top/Article/details/gtrwhcyhti.html

Go:   err.Error()
来源：http://dali.cucudq.cn/Article/details/gtjpcgyass.html

Ruby: e.message;  e.backtrace
来源：http://dali.cqqwz.cn/Article/details/gtdbvoigma.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shangyingyoupin.top/Article/details/gthrxbycom.html

[H09] 带错误码的异常
来源：http://dali.fengsongda.top/Article/details/gthqeczxog.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cucudq.cn/Article/details/gtosdyucaj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jianghu66.top/Article/details/gtemziallz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sweek.top/Article/details/gtoigusksn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gtcxluocve.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.0kj1m.cn/Article/details/gtydpsiyzl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.mhx1999.top/Article/details/gtriuyufcu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sweek.top/Article/details/gtgfetmpzx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fengsongda.top/Article/details/gtzkpmdxeo.html

[H10] 资源自动释放
来源：http://dali.aizwys.cn/Article/details/gtmkpwqubj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tian-w.cn/Article/details/gtnyaavyoy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.quarkkingdee.top/Article/details/gtgjlymsrf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gtfjyxfrzk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xylfe.cn/Article/details/gtbeqtgboh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.mhx1999.top/Article/details/gtuhhynqdt.html

Go:   defer f.Close()
来源：http://dali.tian-w.cn/Article/details/gtrxnglzht.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nwbrower.top/Article/details/gtazbhbsbq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtoxewjgqj.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtdadfzudm.html

I. 正则表达式
来源：http://dali.ivvv.top/Article/details/gtwoveiqtv.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtxdvhwhgz.html

[I01] 判断是否匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbsxwwhhg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.svipenyu.cn/Article/details/gtefhyfgad.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jianghu66.top/Article/details/gtjkhkxmgt.html

JS:   /\d+/.test(s)
来源：http://dali.yj202588.top/Article/details/gtnvyodmdb.html

TS:   /\d+/.test(s)
来源：http://dali.cucudq.cn/Article/details/gtugalxvus.html


<!-- 参考信息 -->