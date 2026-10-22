代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.tanke756.top/Article/details/gthbypjymh.html

C#:   File.Delete("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtiuhfzekk.html

[F07] 创建目录（含多级）
来源：http://dali.0kj1m.cn/Article/details/gtttsoeztg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinqigufen.top/Article/details/gtjvrvciux.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yueranfly.top/Article/details/gtnpmhpbam.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gtawsyzqmp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cucudq.cn/Article/details/gtifueteuj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ydzc1.top/Article/details/gtqhfwlsiu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ivvv.top/Article/details/gtiyiekkbt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cucudq.cn/Article/details/gthhtuklmf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zycfv.cn/Article/details/gtoaxhantp.html

[F08] 遍历目录
来源：http://dali.316326.xyz/Article/details/gtvlvldazv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shzxlz.cn/Article/details/gtgryjlqip.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sufxvd.cn/Article/details/gtnlhkzcfb.html

JS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqapljiim.html

TS:   fs.readdirSync("dir")
来源：http://dali.xuanzx.com/Article/details/gtxkbqzngl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdccqevr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenlongwang.top/Article/details/gtyvkkftwr.html

Ruby: Dir.children("dir")
来源：http://dali.yj202588.top/Article/details/gtjkcowyce.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guowangkeji.top/Article/details/gtplihmuam.html

[F09] 获取文件大小
来源：http://dali.aibaodan.cn/Article/details/gtcabzegeg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtymjwglvr.html

PHP:  filesize("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtiqcxymti.html

JS:   fs.statSync("a.txt").size
来源：http://dali.feifeiyinyue.top/Article/details/gtjzaxgexj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhongyouzk.top/Article/details/gtnvyoupbg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtlfuiosam.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.svipenyu.cn/Article/details/gtwwvwexsi.html

Ruby: File.size("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtwekdgmmd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhiwuduotai.top/Article/details/gtabjhouru.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hfpthk.cn/Article/details/gtygcweobb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtmgklbmpx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtajryrisr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtmhhwmkcr.html

TS:   path.extname("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtdvwylgdf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ydzc1.top/Article/details/gtlsikkzuu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtsubnbkhw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gthvpxqhwl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtxpswuzpt.html

[F11] 复制与移动文件
来源：http://dali.cheryme.top/Article/details/gtrtizivgh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtupqfydcg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yangfankeji.com/Article/details/gtmnxswuvl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtusgktfkx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtclmernnz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnqzz.top/Article/details/gtrkohjniz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cdnleiting.top/Article/details/gtqqugcnel.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtgndpxawf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdmcyrgfe.html

[F12] CSV 读写
来源：http://dali.tianlin.xyz/Article/details/gtlkwhvxth.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cucudq.cn/Article/details/gtdlzjunor.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenlongwang.top/Article/details/gtwkjymnyp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtslpgvcrk.html

TS:   // 同上
来源：http://dali.yj202588.top/Article/details/gtlcwaxilw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.andypj.xyz/Article/details/gtrgocuwdi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.smart0.xyz/Article/details/gttldkjgxl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gaohongyu789.top/Article/details/gtincbpiym.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuxming.cn/Article/details/gthxmspqra.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gttidoerom.html

G. 面向对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfnteujy.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtspyrvcnq.html

[G01] 定义类
来源：http://dali.vqdsnc.cn/Article/details/gtzkaobjgc.html

Py:   class User: pass
来源：http://dali.yueranfly.top/Article/details/gtuxynsggu.html

PHP:  class User {}
来源：http://dali.xuanzx.com/Article/details/gtlxphucxc.html

JS:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtoyolfpxd.html

TS:   class User { name: string = ""; }
来源：http://dali.redwolf501.top/Article/details/gtjuywkdzl.html

Java: class User {}
来源：http://dali.zhengqikj.top/Article/details/gtxblkiwgc.html

Go:   type User struct { Name string }
来源：http://dali.guannengcc.top/Article/details/gtxopzsplv.html

Ruby: class User; end
来源：http://dali.zhixingplan.top/Article/details/gtqsouutck.html

C#:   class User {}
来源：http://dali.cheryme.top/Article/details/gtjvzywblv.html

[G02] 构造函数
来源：http://dali.sysykeji.top/Article/details/gtinvhjedf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhiwuduotai.top/Article/details/gtkbenyuvw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtxlxcudiw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtemjsjmdm.html

TS:   constructor(public name: string) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxpuggkgk.html

Java: User(String name) { this.name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gtgqtcxxce.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenlongwang.top/Article/details/gtsffqnlsc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.redwolf501.top/Article/details/gtifowloar.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gtflomyydb.html

[G03] 实例属性
来源：http://dali.cheryme.top/Article/details/gtizurlcsv.html

Py:   self.name = "x"
来源：http://dali.chenlongwang.top/Article/details/gtwyuehrcq.html

PHP:  public string $name = "x";
来源：http://dali.yuxming.cn/Article/details/gtmapuorsl.html

JS:   this.name = "x";
来源：http://dali.hnqzz.top/Article/details/gtmfoqgejw.html

TS:   name: string = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtotnweszv.html

Java: private String name;
来源：http://dali.zycfv.cn/Article/details/gtbbgwfuor.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenzaomai.com/Article/details/gtfyernish.html

Ruby: @name = "x"
来源：http://dali.andypj.xyz/Article/details/gtygflleqd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcusdjkgk.html

[G04] 定义方法
来源：http://dali.redwolf501.top/Article/details/gthhjxdhfk.html

Py:   def greet(self): return self.name
来源：http://dali.vqdsnc.cn/Article/details/gtabfmuqfo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtnrphqkkn.html

JS:   greet() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtbmbdfpco.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtouybmxpk.html

Java: String greet() { return name; }
来源：http://dali.daria6918.cn/Article/details/gtawmxwkmb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtwokwdqnk.html

Ruby: def greet; @name; end
来源：http://dali.yj202588.top/Article/details/gtpkfwetwh.html

C#:   public string Greet() => Name;
来源：http://dali.yuxming.cn/Article/details/gtgbruogud.html

[G05] 继承
来源：http://dali.nanxuanxn.top/Article/details/gtfuztlgep.html

Py:   class Admin(User): pass
来源：http://dali.chenzaomai.com/Article/details/gtjinjnukj.html

PHP:  class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtjbaqkyau.html

JS:   class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtohvdcevk.html

TS:   class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtaimbijwr.html

Java: class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtbopizqmy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yangfankeji.com/Article/details/gtrrlrigyk.html

Ruby: class Admin < User; end
来源：http://dali.tianlin.xyz/Article/details/gtxoukinoo.html

C#:   class Admin : User {}
来源：http://dali.yj20258888.top/Article/details/gtpuhzvrcw.html

[G06] 重写方法
来源：http://dali.sweek.top/Article/details/gtzndqibxk.html

Py:   def greet(self): return "admin"
来源：http://dali.yuxming.cn/Article/details/gtxazgnjsu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gthpubjdqb.html

JS:   greet() { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtbodibqli.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxqsyajgu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtlewwosrm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigfzy.top/Article/details/gtjuvfqffd.html

Ruby: def greet; "admin"; end
来源：http://dali.ybcxt.top/Article/details/gtyfwlwuna.html

C#:   public override string Greet() => "admin";
来源：http://dali.pengpengdd.cyou/Article/details/gtjbcetccx.html

[G07] 调用父类方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfxjgkqrh.html

Py:   super().greet()
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpjxgjeq.html

PHP:  parent::greet();
来源：http://dali.vqdsnc.cn/Article/details/gtclapzvmy.html

JS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gtizpxmkvk.html

TS:   super.greet();
来源：http://dali.daxiang520.top/Article/details/gtvsxvdxud.html

Java: super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gtlmzbwxwc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.redwolf501.top/Article/details/gtvdiglizn.html

Ruby: super
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjuuityao.html

C#:   base.Greet();
来源：http://dali.cucudq.cn/Article/details/gtvckqgqfd.html

[G08] 静态方法与属性
来源：http://dali.daria6918.cn/Article/details/gtsxxxhqzs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tanke756.top/Article/details/gtqpgbrrga.html

PHP:  public static function f() {}
来源：http://dali.ybcxt.top/Article/details/gtypclmzad.html

JS:   static f() {}
来源：http://dali.yueranfly.top/Article/details/gtjcjbaizg.html

TS:   static f(): void {}
来源：http://dali.meibo888.top/Article/details/gtfcyzbbpw.html

Java: static void f() {}
来源：http://dali.quarkkingdee.top/Article/details/gtvjogksuv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gzhubu.top/Article/details/gtdwyugiry.html

Ruby: def self.f; end
来源：http://dali.yongpay.top/Article/details/gtpcrkjimu.html

C#:   public static void F() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtwnvvrprb.html

[G09] 接口 / 抽象类
来源：http://dali.c1oappe.top/Article/details/gtvysrufcv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejptibdq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.mhx1999.top/Article/details/gtgswobjdk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sufxvd.cn/Article/details/gtgndfegnp.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj202588.top/Article/details/gtfcbshvhn.html

Java: interface Shape { double area(); }
来源：http://dali.daxiang520.top/Article/details/gtewhjzvtg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.c1oappe.top/Article/details/gtijgyalbo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.vqdsnc.cn/Article/details/gtjsulmekk.html

C#:   interface IShape { double Area(); }
来源：http://dali.yongpay.top/Article/details/gtudfsbtve.html

[G10] 访问控制
来源：http://dali.nwbrower.top/Article/details/gtmotjnpmw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hongshengwenyu.top/Article/details/gttbjvpmxc.html

PHP:  public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtrbkqnzlq.html

JS:   #private 字段；其余公开
来源：http://dali.ydzc1.top/Article/details/gtzfovxotg.html

TS:   public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtnrxsqpqt.html

Java: public / protected / private / 默认包级
来源：http://dali.cdnleiting.top/Article/details/gtbbuwmwld.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daria6918.cn/Article/details/gtqmrytlhg.html

Ruby: public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtjpszcpfs.html

C#:   public / protected / private / internal
来源：http://dali.nanxuanxn.top/Article/details/gtstnppepw.html

[G11] getter / setter
来源：http://dali.yuanzhike.top/Article/details/gticqzrnjq.html

Py:   @property 与 @x.setter
来源：http://dali.nanxuanxn.top/Article/details/gthiclofqd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtlcgiwhha.html

JS:   get name() { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gtcdingxmb.html

TS:   get name(): string { return this._name; }
来源：http://dali.yonumen.top/Article/details/gtkcxnqnge.html

Java: public String getName() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gtmkhihpnh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtawykhfzs.html

Ruby: attr_accessor :name
来源：http://dali.yuxming.cn/Article/details/gtpqtyemys.html

C#:   public string Name { get; set; }
来源：http://dali.shuidangran.top/Article/details/gttvnqhhlm.html

[G12] 对象转字符串
来源：http://dali.meibo888.top/Article/details/gtpqtvqahe.html

Py:   def __str__(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gtmnidrobp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtfbphgmzx.html

JS:   toString() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtfcoyohnq.html

TS:   toString(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gteobblfuo.html

Java: @Override public String toString() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtoftnyerw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtjnigrsic.html

Ruby: def to_s; @name; end
来源：http://dali.tianlin.xyz/Article/details/gttdnplqgw.html

C#:   public override string ToString() => Name;
来源：http://dali.hfpthk.cn/Article/details/gtnffeaprt.html

[G13] 判断对象类型
来源：http://dali.ivvv.top/Article/details/gtzuweuxwt.html

Py:   isinstance(u, User)
来源：http://dali.iojbl.cn/Article/details/gtiqmptzof.html

PHP:  $u instanceof User
来源：http://dali.xziqi.cn/Article/details/gthtyidwdh.html

JS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtcfwoknas.html

TS:   u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtlbmkotee.html

Java: u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtvkyshrfk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj202588.top/Article/details/gtrycxgpso.html

Ruby: u.is_a?(User)
来源：http://dali.yuanzhike.top/Article/details/gtqqrxrbmu.html

C#:   u is User
来源：http://dali.hongshengwenyu.top/Article/details/gthnrngylu.html

[G14] 数据类 / record
来源：http://dali.cucudq.cn/Article/details/gtjsnqkvpg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.andypj.xyz/Article/details/gtlenqemid.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jiagoushi.top/Article/details/gtkcnkzgfp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nwbrower.top/Article/details/gtobmpvkhz.html

TS:   type User = { name: string; age: number };
来源：http://dali.pycfn.com/Article/details/gtfjygadjr.html

Java: record User(String name, int age) {}
来源：http://dali.ydzc1.top/Article/details/gttpzpvnjh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxugvrbf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hywenlv.cn/Article/details/gtuszszdem.html

C#:   record User(string Name, int Age);
来源：http://dali.yongpay.top/Article/details/gtbnkferhq.html

[G15] 枚举
来源：http://dali.yuxming.cn/Article/details/gtmqrwpxap.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shzxlz.cn/Article/details/gtvwircsvd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.fzhhl.top/Article/details/gtaxsnjfyi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jyoumei.cn/Article/details/gtjbcsrydk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gtoyfzhdft.html

Java: enum Color { RED, GREEN }
来源：http://dali.feifeiyinyue.top/Article/details/gtdmfzijdk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.meibo888.top/Article/details/gtiyzkdrsi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangdashe.top/Article/details/gtdkcovjwr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.9152youxi.cn/Article/details/gtusuorixt.html

[G16] 对象转数组 / 字典
来源：http://dali.xinyue.icu/Article/details/gtcoakvkza.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.snrcjt.cn/Article/details/gtwmoytdzr.html

PHP:  get_object_vars($obj);
来源：http://dali.yuanzhike.top/Article/details/gtuedpfrjv.html

JS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtwtdhxjjg.html

TS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gtdecoarwt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sysykeji.top/Article/details/gtiarsjmyx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.havefunace.top/Article/details/gtgeqpefik.html

Ruby: obj.instance_variables
来源：http://dali.zhoulong.xyz/Article/details/gtltmvgxtd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gtfgprrjvu.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtlunkqmjg.html

H. 异常与错误处理
来源：http://dali.zhengqikj.top/Article/details/gtxzwggwxg.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtmukvateg.html

[H01] try / catch 基础
来源：http://dali.gzhubu.top/Article/details/gtorrqvvld.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hywenlv.cn/Article/details/gtterwxahv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hysaishi.cn/Article/details/gtmhdumhjj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhongyouzk.top/Article/details/gtyodkmxmq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrtbrplvi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.havefunace.top/Article/details/gtewvdlxut.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.c1oappe.top/Article/details/gtabveoafy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.vqdsnc.cn/Article/details/gtiuynjpkp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gaohongyu789.top/Article/details/gtygokiumw.html

[H02] finally / ensure 收尾
来源：http://dali.nanxinkj.top/Article/details/gtktqvfmrr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenjidiqi.icu/Article/details/gtoxnqjsgg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtpxktovap.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtvberiths.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtxubovcqu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtngzoxjxh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yangfankeji.com/Article/details/gtgeeuqkvc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnqzz.top/Article/details/gtzxydczec.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtrswptzpt.html

[H03] 主动抛出异常
来源：http://dali.fengsongda.top/Article/details/gtrjnswmzq.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsunrsmio.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtgzhpemnh.html

JS:   throw new Error("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtekhegksw.html

TS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtemzpkmbo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtwasktwpe.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.svipenyu.cn/Article/details/gtthyuyssv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenjidiqi.icu/Article/details/gtykgguubg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtjvgpvlee.html

[H04] 自定义异常类型
来源：http://dali.svipenyu.cn/Article/details/gtqxjljhlc.html

Py:   class MyError(Exception): pass
来源：http://dali.ybcxt.top/Article/details/gtikzxuvdh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinqigfzy.top/Article/details/gtmpdilwme.html

JS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gtvzolonpj.html

TS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gtizmmogde.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhiwuduotai.top/Article/details/gtcnobklzf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gogol.net.cn/Article/details/gtqrqmitau.html

Ruby: class MyError < StandardError; end
来源：http://dali.xziqi.cn/Article/details/gtfytoyvvp.html

C#:   class MyException : Exception {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdjzbkfl.html

[H05] 捕获特定类型
来源：http://dali.jiagoushi.top/Article/details/gtbkbcurtu.html

Py:   except ValueError as e:
来源：http://dali.yanxiufei.cn/Article/details/gtuxcstnmf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.fengsongda.top/Article/details/gtfzdugizx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtyqtctxst.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gttaggyqck.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ehwqpu.com/Article/details/gtbstcuwwy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gaohongyu789.top/Article/details/gtwtstwftm.html

Ruby: rescue ArgumentError => e
来源：http://dali.tian-w.cn/Article/details/gtrqwuehoe.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.0kj1m.cn/Article/details/gtrwovvsgo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.redwolf501.top/Article/details/gtxlvlqbqs.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigufen.top/Article/details/gthosapvgg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuanzx.com/Article/details/gtibaoueju.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.aizwys.cn/Article/details/gthdqhndgk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gthsgtpcbo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gotoacloud.top/Article/details/gtlmpvhtet.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shangyingyoupin.top/Article/details/gtmqxxyhug.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yueranfly.top/Article/details/gtqryldava.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenlongwang.top/Article/details/gtbqysxkur.html

[H07] 断言
来源：http://dali.havefunace.top/Article/details/gtbqjmhpjx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenzaomai.com/Article/details/gtqwxnybnx.html

PHP:  assert($x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtlxwjnydi.html

JS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtpojkocpm.html

TS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtrxtesrco.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenjidiqi.icu/Article/details/gtwvkhgpbl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sweek.top/Article/details/gttwjzcatz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.redwolf501.top/Article/details/gtbyjaibyz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gtaphkwewj.html

[H08] 获取错误信息与堆栈
来源：http://dali.bjfxy.top/Article/details/gttcvecxoz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangdashe.top/Article/details/gtfwrmcsvh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258888.top/Article/details/gtwahlicub.html

JS:   e.message;  e.stack
来源：http://dali.redwolf501.top/Article/details/gtryaovfsn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjnjopejm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenzaomai.com/Article/details/gtttfwjpit.html

Go:   err.Error()
来源：http://dali.cheryme.top/Article/details/gtluzhpdks.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgfzy.top/Article/details/gtvdsitlya.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hammf.cn/Article/details/gtzqjwqpdu.html

[H09] 带错误码的异常
来源：http://dali.pycfn.com/Article/details/gtobggdmkq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sysykeji.top/Article/details/gtvmeibnlm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dashuyun.cn/Article/details/gtgpvyoufg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pycfn.com/Article/details/gtqwyazppu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ydzc1.top/Article/details/gtcgftqvfu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xylfe.cn/Article/details/gtevmiougr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daria6918.cn/Article/details/gtnybpsnbh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.snrcjt.cn/Article/details/gtxhqooaea.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.316326.xyz/Article/details/gthwhjyctg.html

[H10] 资源自动释放
来源：http://dali.yueranfly.top/Article/details/gtmgvpsbjg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hnqzz.top/Article/details/gtoucvxzce.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cheryme.top/Article/details/gteipudpjp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gaohongyu789.top/Article/details/gtaxlokprt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sxryk.cn/Article/details/gtuxhbqqnt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangshuangyany.cn/Article/details/gtycobjmvn.html

Go:   defer f.Close()
来源：http://dali.snrcjt.cn/Article/details/gtfmkpichs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jyoumei.cn/Article/details/gtczdlyggh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtroawtyoh.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gttdnpazph.html

I. 正则表达式
来源：http://dali.hnxiangtu.top/Article/details/gtagovdmvb.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtkiemecyw.html

[I01] 判断是否匹配
来源：http://dali.tian-w.cn/Article/details/gtjzhjkhtv.html


<!-- 参考信息 -->