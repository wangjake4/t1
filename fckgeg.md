代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daxiang520.top/Article/details/gt2ybpwettd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gt2xfqtrzpz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.quarkkingdee.top/Article/details/gt2vqfqqotw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dhqptdtq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yueranfly.top/Article/details/gt2uvuotchj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.meibo888.top/Article/details/gt2phdzkqfa.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hysaishi.cn/Article/details/gt2rqevfrke.html

[F08] 遍历目录
来源：http://dali.gotoacloud.top/Article/details/gt2iysebmde.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xhlauvmc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yvedp.cn/Article/details/gt2qskeiceo.html

JS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gt2goxgkiot.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gt2jrewxhda.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gt2aybamqjk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhengqikj.top/Article/details/gt2qrijdmsh.html

Ruby: Dir.children("dir")
来源：http://dali.yj202588.top/Article/details/gt2pwbequgq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gt2flgejqnv.html

[F09] 获取文件大小
来源：http://dali.gotoacloud.top/Article/details/gt2wzoyqaae.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2fznseyzu.html

PHP:  filesize("a.txt");
来源：http://dali.sweek.top/Article/details/gt2fksyadgd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhongyouzk.top/Article/details/gt2oyfxsqmy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gt2ktbirnvu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dgayrwhq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guannengcc.top/Article/details/gt2yiugimoy.html

Ruby: File.size("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2qfmtstpp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.0kj1m.cn/Article/details/gt2gwtudjtu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cashguo.top/Article/details/gt2wmfotpmm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2oggvicgh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2faovtvcm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2kggnqoft.html

TS:   path.extname("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2drcxpnmc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.feifeiyinyue.top/Article/details/gt2zwbeyrqe.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2fnkbxbbg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2wxczplho.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2jhpqokgp.html

[F11] 复制与移动文件
来源：http://dali.jqgufenzy.top/Article/details/gt2ktokflie.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gt2podtrroy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2tkdzdnrt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gt2qpzyibby.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2hlqusuvi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tanke756.top/Article/details/gt2ifothiem.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenzaomai.com/Article/details/gt2vsgwedib.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gt2rpzsjxee.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.dashuyun.cn/Article/details/gt2nyzevhip.html

[F12] CSV 读写
来源：http://dali.yueranfly.top/Article/details/gt2ykejmmzl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vyqikrsz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuetiantiany.cn/Article/details/gt2ucabzsbb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yongpay.top/Article/details/gt2kxwajsrw.html

TS:   // 同上
来源：http://dali.yonumen.top/Article/details/gt2chogjafl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenzaomai.com/Article/details/gt2tnshwzuj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.bjfxy.top/Article/details/gt2vsraixmn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sufxvd.cn/Article/details/gt2pctpkiyw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dashuyun.cn/Article/details/gt2xujquknf.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2fkclhmmb.html

G. 面向对象
来源：http://dali.cqqwz.cn/Article/details/gt2blwjivdp.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2ppjjwxvd.html

[G01] 定义类
来源：http://dali.0kj1m.cn/Article/details/gt2swzgdcuq.html

Py:   class User: pass
来源：http://dali.tianlin.xyz/Article/details/gt2mzvbtzxv.html

PHP:  class User {}
来源：http://dali.xinyue.icu/Article/details/gt2uqqhnyyo.html

JS:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gt2zffjryuk.html

TS:   class User { name: string = ""; }
来源：http://dali.jqgufenzy.top/Article/details/gt2wnjtufkh.html

Java: class User {}
来源：http://dali.yongpay.top/Article/details/gt2vluzodgg.html

Go:   type User struct { Name string }
来源：http://dali.cqqwz.cn/Article/details/gt2nuejoown.html

Ruby: class User; end
来源：http://dali.havefunace.top/Article/details/gt2euncosfv.html

C#:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yrifnjji.html

[G02] 构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbernhmv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jztssjsv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tian-w.cn/Article/details/gt2idfstfpk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhixingplan.top/Article/details/gt2ntcamqft.html

TS:   constructor(public name: string) {}
来源：http://dali.dianchejie.cn/Article/details/gt2gacsgroh.html

Java: User(String name) { this.name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2tvprbxgv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnxiangtu.top/Article/details/gt2nqhugmko.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sxryk.cn/Article/details/gt2vduppnxy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.smart0.xyz/Article/details/gt2gjmysetu.html

[G03] 实例属性
来源：http://dali.aizwys.cn/Article/details/gt2hvrpxheq.html

Py:   self.name = "x"
来源：http://dali.hongshengwenyu.top/Article/details/gt2lhxjnmrb.html

PHP:  public string $name = "x";
来源：http://dali.yongpay.top/Article/details/gt2wicufmxt.html

JS:   this.name = "x";
来源：http://dali.yueranfly.top/Article/details/gt2jbzbifho.html

TS:   name: string = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gt2wxlcglib.html

Java: private String name;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ukvdxouy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cdnleiting.top/Article/details/gt2bsgrtwrh.html

Ruby: @name = "x"
来源：http://dali.hammf.cn/Article/details/gt2aliaqkjj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sysykeji.top/Article/details/gt2ggrdymjp.html

[G04] 定义方法
来源：http://dali.birdmap.top/Article/details/gt2xgrubiri.html

Py:   def greet(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gt2rjhnnqwn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gt2yheidgvm.html

JS:   greet() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gt2mpxatykt.html

TS:   greet(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gt2twimywgf.html

Java: String greet() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gt2kmzmoqnd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gt2niphekxa.html

Ruby: def greet; @name; end
来源：http://dali.cucudq.cn/Article/details/gt2otmfkkve.html

C#:   public string Greet() => Name;
来源：http://dali.sweek.top/Article/details/gt2zirckysp.html

[G05] 继承
来源：http://dali.yueranfly.top/Article/details/gt2bdybnang.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xnetqzvo.html

PHP:  class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2ahunnhuh.html

JS:   class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2ugzxewvc.html

TS:   class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gt2gwsbnniv.html

Java: class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gt2yiixuvap.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ppjwa.cn/Article/details/gt2kyyjwmrp.html

Ruby: class Admin < User; end
来源：http://dali.cdnleiting.top/Article/details/gt2uhrnhmnv.html

C#:   class Admin : User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2mpegduzo.html

[G06] 重写方法
来源：http://dali.xuanzx.com/Article/details/gt2ejuwurir.html

Py:   def greet(self): return "admin"
来源：http://dali.jiagoushi.top/Article/details/gt2xzktfgvk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gt2ybahbphr.html

JS:   greet() { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gt2qxbvrsfw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gt2eqznybtk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gt2waldtrnu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2beyrzxgi.html

Ruby: def greet; "admin"; end
来源：http://dali.nanxinkj.top/Article/details/gt2cppprmtx.html

C#:   public override string Greet() => "admin";
来源：http://dali.pycfn.com/Article/details/gt2cppyyxql.html

[G07] 调用父类方法
来源：http://dali.bjfxy.top/Article/details/gt2zkrzopfn.html

Py:   super().greet()
来源：http://dali.sxryk.cn/Article/details/gt2fstlyjss.html

PHP:  parent::greet();
来源：http://dali.ivvv.top/Article/details/gt2tcvofzii.html

JS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gt2rrurjgsj.html

TS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gt2gsihxhmm.html

Java: super.greet();
来源：http://dali.chenlongwang.top/Article/details/gt2xkukqrky.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xinyue.icu/Article/details/gt2xtnnbkan.html

Ruby: super
来源：http://dali.xziqi.cn/Article/details/gt2jdxkixkz.html

C#:   base.Greet();
来源：http://dali.ydzc1.top/Article/details/gt2hstgcudl.html

[G08] 静态方法与属性
来源：http://dali.ybcxt.top/Article/details/gt2mrthanex.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.havefunace.top/Article/details/gt2mocdpudm.html

PHP:  public static function f() {}
来源：http://dali.daria6918.cn/Article/details/gt2ovcuycxr.html

JS:   static f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rwurfpxx.html

TS:   static f(): void {}
来源：http://dali.ybcxt.top/Article/details/gt2norkufyf.html

Java: static void f() {}
来源：http://dali.xinyue.icu/Article/details/gt2evspfwjw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ivvv.top/Article/details/gt2audlqaho.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eeysjifn.html

C#:   public static void F() {}
来源：http://dali.yueranfly.top/Article/details/gt2wwrpnqbc.html

[G09] 接口 / 抽象类
来源：http://dali.chenjidiqi.icu/Article/details/gt2ixkruxqg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinqigfzy.top/Article/details/gt2sdbctsio.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cqqwz.cn/Article/details/gt2kbrduvmt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hammf.cn/Article/details/gt2humlafdz.html

TS:   interface Shape { area(): number; }
来源：http://dali.shzxlz.cn/Article/details/gt2zinzvktc.html

Java: interface Shape { double area(); }
来源：http://dali.jianghu66.top/Article/details/gt2qekpyakb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hnqzz.top/Article/details/gt2mumudxuj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj202588.top/Article/details/gt2cfakhfpr.html

C#:   interface IShape { double Area(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xfipwbma.html

[G10] 访问控制
来源：http://dali.fzhhl.top/Article/details/gt2svdchfhl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tianlin.xyz/Article/details/gt2wzbnlizc.html

PHP:  public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gt2rznotqls.html

JS:   #private 字段；其余公开
来源：http://dali.havefunace.top/Article/details/gt2juxmymtn.html

TS:   public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gt2afewhiig.html

Java: public / protected / private / 默认包级
来源：http://dali.sysykeji.top/Article/details/gt2dildzhce.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cashguo.top/Article/details/gt2cgkekprw.html

Ruby: public / protected / private
来源：http://dali.ydzc1.top/Article/details/gt2cnxnxxgk.html

C#:   public / protected / private / internal
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aasxxvnb.html

[G11] getter / setter
来源：http://dali.smart0.xyz/Article/details/gt2ldmspvgo.html

Py:   @property 与 @x.setter
来源：http://dali.zhixingplan.top/Article/details/gt2mrtbplhy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qzohoips.html

JS:   get name() { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qcykclvy.html

TS:   get name(): string { return this._name; }
来源：http://dali.smart0.xyz/Article/details/gt2egtzfuym.html

Java: public String getName() { return name; }
来源：http://dali.sysykeji.top/Article/details/gt2geckmnas.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gt2jgdoscrm.html

Ruby: attr_accessor :name
来源：http://dali.jqgufenzy.top/Article/details/gt2igeusour.html

C#:   public string Name { get; set; }
来源：http://dali.xinyue.icu/Article/details/gt2yolxzrgs.html

[G12] 对象转字符串
来源：http://dali.chenlongwang.top/Article/details/gt2dufpyozm.html

Py:   def __str__(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gt2mjsvmgli.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gt2qgrphxta.html

JS:   toString() { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gt2tfeugfyw.html

TS:   toString(): string { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gt2mmpbjvgt.html

Java: @Override public String toString() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xilbsqed.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gt2wnasqccx.html

Ruby: def to_s; @name; end
来源：http://dali.gotoacloud.top/Article/details/gt2axhmskzo.html

C#:   public override string ToString() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gt2wwniinvx.html

[G13] 判断对象类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2obutogsd.html

Py:   isinstance(u, User)
来源：http://dali.0kj1m.cn/Article/details/gt2vwdrhcyy.html

PHP:  $u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gt2erjonsvx.html

JS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gt2lyvybwka.html

TS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gt2wuaoogep.html

Java: u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gt2ftmvwflr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dashuyun.cn/Article/details/gt2scdluqzr.html

Ruby: u.is_a?(User)
来源：http://dali.gogol.net.cn/Article/details/gt2sanyvkgg.html

C#:   u is User
来源：http://dali.haohaochexian.top/Article/details/gt2mgpkiagf.html

[G14] 数据类 / record
来源：http://dali.xuanzx.com/Article/details/gt2mrrcttgq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxinkj.top/Article/details/gt2suonozld.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wxjoluqc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.fzhhl.top/Article/details/gt2jbkdqpua.html

TS:   type User = { name: string; age: number };
来源：http://dali.nwbrower.top/Article/details/gt2rxeynvzj.html

Java: record User(String name, int age) {}
来源：http://dali.yuanzhike.top/Article/details/gt2msmriacv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jlsjyb.cn/Article/details/gt2wkveicvh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.0kj1m.cn/Article/details/gt2pzjilwsk.html

C#:   record User(string Name, int Age);
来源：http://dali.zdqjudy.top/Article/details/gt2fixuymki.html

[G15] 枚举
来源：http://dali.gogol.net.cn/Article/details/gt2fyhsryqo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yuxming.cn/Article/details/gt2nfhpssjr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj202588.top/Article/details/gt2nxvexgpw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj202588.top/Article/details/gt2vpjojsvk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2kknhhcea.html

Java: enum Color { RED, GREEN }
来源：http://dali.feifeiyinyue.top/Article/details/gt2pvgalhtq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jiagoushi.top/Article/details/gt2dbiuxlep.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcgdwjq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgufenzy.top/Article/details/gt2hbfzlzgj.html

[G16] 对象转数组 / 字典
来源：http://dali.fzhhl.top/Article/details/gt2fgwicwrl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.meibo888.top/Article/details/gt2hnbgyjal.html

PHP:  get_object_vars($obj);
来源：http://dali.yongpay.top/Article/details/gt2eaygldco.html

JS:   Object.entries(obj)
来源：http://dali.birdmap.top/Article/details/gt2huxvpyiv.html

TS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gt2gbrarifb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.bjfxy.top/Article/details/gt2vxvjonbh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xinyue.icu/Article/details/gt2svforlya.html

Ruby: obj.instance_variables
来源：http://dali.shzxlz.cn/Article/details/gt2fepgkjgn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gt2xblebhky.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2rtpsvpxc.html

H. 异常与错误处理
来源：http://dali.jqgfzy.top/Article/details/gt2wzdrkbwa.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2wsdcucit.html

[H01] try / catch 基础
来源：http://dali.tianlin.xyz/Article/details/gt2pgshqeyv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuanzhike.top/Article/details/gt2ssmehajh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2prfoaxzh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gt2mrjducex.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gt2ewutvesl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuanzx.com/Article/details/gt2emxppwit.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gaohongyu789.top/Article/details/gt2xtepyvkb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jlsjyb.cn/Article/details/gt2fmnjouoj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shzxlz.cn/Article/details/gt2ajsplkzr.html

[H02] finally / ensure 收尾
来源：http://dali.xziqi.cn/Article/details/gt2pmgxoycy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sysykeji.top/Article/details/gt2xkzjozmj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pznsikqk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gt2cmpuysjr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gt2mugbjssf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2hphkelzz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yongpay.top/Article/details/gt2nesydrgv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sqclzgjf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gt2gpvwdtxq.html

[H03] 主动抛出异常
来源：http://dali.mhx1999.top/Article/details/gt2krrrtwsh.html

Py:   raise ValueError("错误信息")
来源：http://dali.jyoumei.cn/Article/details/gt2lxsleqrb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gt2iurkcwcr.html

JS:   throw new Error("错误信息");
来源：http://dali.daxiang520.top/Article/details/gt2hrozvutj.html

TS:   throw new Error("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gt2dntuhhtm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gt2odrtawsy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zycfv.cn/Article/details/gt2zmwpncwu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cqqwz.cn/Article/details/gt2zhijrtqk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gt2rksncisu.html

[H04] 自定义异常类型
来源：http://dali.hnqzz.top/Article/details/gt2xbfyfhug.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jtssmlkx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2wtilqikp.html

JS:   class MyError extends Error {}
来源：http://dali.aibaodan.cn/Article/details/gt2wxlxevpu.html

TS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gt2jbhinjqi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gt2nlgribcp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.havefunace.top/Article/details/gt2idptgwnk.html

Ruby: class MyError < StandardError; end
来源：http://dali.yanxiufei.cn/Article/details/gt2mddxfkqy.html

C#:   class MyException : Exception {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2lrzlyqhu.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrdlucz.html

Py:   except ValueError as e:
来源：http://dali.chenzaomai.com/Article/details/gt2wdtoxmxl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.c1oappe.top/Article/details/gt2uvluoqyf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2cjjtqazr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2gmsrhhrz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sufxvd.cn/Article/details/gt2islbweoy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yueranfly.top/Article/details/gt2bfcdlnuw.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258888.top/Article/details/gt2wskjvbyh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.daxiang520.top/Article/details/gt2tellvsrw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yangfankeji.com/Article/details/gt2ggaplhze.html

Py:   value = d.get("k") or default
来源：http://dali.nwbrower.top/Article/details/gt2yhtxywuy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj20258888.top/Article/details/gt2ocjbixud.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jyoumei.cn/Article/details/gt2ezclioig.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jmsixmcg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xuetiantiany.cn/Article/details/gt2trqkcglr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nixfjzoq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jqgfzy.top/Article/details/gt2xkxhyqiw.html

C#:   obj?.A?.B ?? default
来源：http://dali.yonumen.top/Article/details/gt2yuxzogoh.html

[H07] 断言
来源：http://dali.daria6918.cn/Article/details/gt2zrakjudg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jjtwzoar.html

PHP:  assert($x > 0);
来源：http://dali.316326.xyz/Article/details/gt2ufblvzud.html

JS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gt2edolunmc.html

TS:   console.assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2dstcmyun.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gaohongyu789.top/Article/details/gt2teljclyc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tianlin.xyz/Article/details/gt2fmqvrmij.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangshuangyany.cn/Article/details/gt2cvfjifvp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gt2hmfxgrfi.html

[H08] 获取错误信息与堆栈
来源：http://dali.tianlin.xyz/Article/details/gt2ttdcriup.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ppjwa.cn/Article/details/gt2giqqjjfe.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2tbyncxoq.html

JS:   e.message;  e.stack
来源：http://dali.wangshuangyany.cn/Article/details/gt2jootraty.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xziqi.cn/Article/details/gt2crvtgbqr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hammf.cn/Article/details/gt2bpmzhels.html

Go:   err.Error()
来源：http://dali.hongshengwenyu.top/Article/details/gt2udxnkxru.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhengqikj.top/Article/details/gt2jwhdskso.html

C#:   e.Message;  e.StackTrace
来源：http://dali.redwolf501.top/Article/details/gt2nagbvkgc.html

[H09] 带错误码的异常
来源：http://dali.jinqigfzy.top/Article/details/gt2hizoenjm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.andypj.xyz/Article/details/gt2gvovraix.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oixjscez.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.316326.xyz/Article/details/gt2kuqksxou.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.mhx1999.top/Article/details/gt2ykarehdn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.kuanghao11.cn/Article/details/gt2qflguusn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhoulong.xyz/Article/details/gt2lyzydniv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.quarkkingdee.top/Article/details/gt2vffwfcjm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ybcxt.top/Article/details/gt2omglinsa.html

[H10] 资源自动释放
来源：http://dali.guowangkeji.top/Article/details/gt2uxwpxmsr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.redwolf501.top/Article/details/gt2spjkfpeg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cheryme.top/Article/details/gt2ohyjvdbi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gt2gphreckm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.redwolf501.top/Article/details/gt2ktghfyxv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenlongwang.top/Article/details/gt2bubwjfqz.html

Go:   defer f.Close()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pbvtnbje.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tanke756.top/Article/details/gt2obztncww.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2tytkekfr.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2eyuhltbq.html

I. 正则表达式
来源：http://dali.hnxiangtu.top/Article/details/gt2phqboipz.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2yzopgdcp.html

[I01] 判断是否匹配
来源：http://dali.9152youxi.cn/Article/details/gt2ddaumaob.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gt2ifafgsjk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ybcxt.top/Article/details/gt2ehsxadsu.html

JS:   /\d+/.test(s)
来源：http://dali.zhengqikj.top/Article/details/gt2powegcnu.html

TS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gt2xaqusgyj.html


<!-- 参考信息 -->