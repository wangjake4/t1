代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.andypj.xyz/Article/details/gt2teagwqks.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigfzy.top/Article/details/gt2imemgzmn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gt2kibskwvs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.vqdsnc.cn/Article/details/gt2etctbuxy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.haohaochexian.top/Article/details/gt2ngdjspky.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.svipenyu.cn/Article/details/gt2hmulxgqu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guowangkeji.top/Article/details/gt2ywhwmmow.html

[F08] 遍历目录
来源：http://dali.guannengcc.top/Article/details/gt2rpqqnoph.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daria6918.cn/Article/details/gt2vnqakzit.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2tnfniqjs.html

JS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gt2zxyvrfdu.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnxiangtu.top/Article/details/gt2agzzvjil.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sxryk.cn/Article/details/gt2xwdjopfh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ybcxt.top/Article/details/gt2mxiafipz.html

Ruby: Dir.children("dir")
来源：http://dali.haohaochexian.top/Article/details/gt2laizuhga.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nwbrower.top/Article/details/gt2xjcxrvma.html

[F09] 获取文件大小
来源：http://dali.yueranfly.top/Article/details/gt2gxpexuvr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2ticxokew.html

PHP:  filesize("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2cpgtwyfh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gt2nacxmkij.html

TS:   fs.statSync("a.txt").size
来源：http://dali.wangshuangyany.cn/Article/details/gt2qinffwyu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gt2mrycuqgz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.fengsongda.top/Article/details/gt2vtgxmdyi.html

Ruby: File.size("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2jtnztraz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yanxiufei.cn/Article/details/gt2qqjtphvb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hammf.cn/Article/details/gt2nazkjflo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2wwsthqca.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2yybwfyqt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2tzsjssqu.html

TS:   path.extname("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2okwhozrt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jyoumei.cn/Article/details/gt2bifiswib.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2fjdqaclx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2bsslavhk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gt2rdloiuxc.html

[F11] 复制与移动文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2hlwfcjin.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ufzrkmdl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.iojbl.cn/Article/details/gt2mnvktvqr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gt2ofqmzzhh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2qcoawixw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nwbrower.top/Article/details/gt2gowirayx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ybcxt.top/Article/details/gt2itkmgaic.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2upmswooa.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zaznzwdr.html

[F12] CSV 读写
来源：http://dali.c1oappe.top/Article/details/gt2raybnboe.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jiagoushi.top/Article/details/gt2ynsofref.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.quarkkingdee.top/Article/details/gt2sojnnvdt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jlsjyb.cn/Article/details/gt2lkspaesh.html

TS:   // 同上
来源：http://dali.yueranfly.top/Article/details/gt2vhyhrudb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jianghu66.top/Article/details/gt2hmazzyjn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.fzhhl.top/Article/details/gt2zdagtcex.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhixingplan.top/Article/details/gt2odamjrpl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cdnleiting.top/Article/details/gt2njsaoqyu.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2sigkbfuz.html

G. 面向对象
来源：http://dali.pycfn.com/Article/details/gt2wcjfqrgb.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2mkcuaetu.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ghejzuya.html

Py:   class User: pass
来源：http://dali.meibo888.top/Article/details/gt2pcwfjenq.html

PHP:  class User {}
来源：http://dali.birdmap.top/Article/details/gt2tegtpbmp.html

JS:   class User {}
来源：http://dali.aibaodan.cn/Article/details/gt2hhnsnydb.html

TS:   class User { name: string = ""; }
来源：http://dali.0kj1m.cn/Article/details/gt2mwmveoyt.html

Java: class User {}
来源：http://dali.haohaochexian.top/Article/details/gt2qujhbltt.html

Go:   type User struct { Name string }
来源：http://dali.jqgufenzy.top/Article/details/gt2yqaqqbkc.html

Ruby: class User; end
来源：http://dali.pycfn.com/Article/details/gt2lettjttj.html

C#:   class User {}
来源：http://dali.sweek.top/Article/details/gt2qbxxijru.html

[G02] 构造函数
来源：http://dali.316326.xyz/Article/details/gt2gshycgjt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hywenlv.cn/Article/details/gt2azqwaqxa.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258888.top/Article/details/gt2zmbdmhjz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.pycfn.com/Article/details/gt2nrglutai.html

TS:   constructor(public name: string) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2ptjagrle.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2byosjwtd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2udtzthja.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.svipenyu.cn/Article/details/gt2gginmsqm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gogol.net.cn/Article/details/gt2bngzwuen.html

[G03] 实例属性
来源：http://dali.chenlongwang.top/Article/details/gt2tqsgsyje.html

Py:   self.name = "x"
来源：http://dali.hammf.cn/Article/details/gt2fznoxljr.html

PHP:  public string $name = "x";
来源：http://dali.jiagoushi.top/Article/details/gt2gyjxwbpn.html

JS:   this.name = "x";
来源：http://dali.cashguo.top/Article/details/gt2hxnbzjcn.html

TS:   name: string = "x";
来源：http://dali.yangfankeji.com/Article/details/gt2lllfxgwg.html

Java: private String name;
来源：http://dali.yangfankeji.com/Article/details/gt2bchycchk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.smart0.xyz/Article/details/gt2qsjmwbxh.html

Ruby: @name = "x"
来源：http://dali.zhongyouzk.top/Article/details/gt2hvbgtxkp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.bjfxy.top/Article/details/gt2bevosqaf.html

[G04] 定义方法
来源：http://dali.sweek.top/Article/details/gt2tiwnledj.html

Py:   def greet(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gt2vtelmyhw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gt2czuqlyoh.html

JS:   greet() { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gt2vnmlaxci.html

TS:   greet(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2siavongt.html

Java: String greet() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2nczqwkzd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gt2qqfkkdya.html

Ruby: def greet; @name; end
来源：http://dali.daxiang520.top/Article/details/gt2uielhqch.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigufen.top/Article/details/gt2fuwswaqd.html

[G05] 继承
来源：http://dali.kuanghao11.cn/Article/details/gt2wvkyizto.html

Py:   class Admin(User): pass
来源：http://dali.yongpay.top/Article/details/gt2zfwdnkts.html

PHP:  class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gt2swewgayh.html

JS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2vuetxpdx.html

TS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gt2xeubvyqs.html

Java: class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2pfwcnhch.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.dashuyun.cn/Article/details/gt2mcnfbyvi.html

Ruby: class Admin < User; end
来源：http://dali.andypj.xyz/Article/details/gt2hmfoalty.html

C#:   class Admin : User {}
来源：http://dali.sysykeji.top/Article/details/gt2wjksgkad.html

[G06] 重写方法
来源：http://dali.yuanzhike.top/Article/details/gt2mbbhcrfh.html

Py:   def greet(self): return "admin"
来源：http://dali.havefunace.top/Article/details/gt2zgfvyuga.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gt2ovnkblgd.html

JS:   greet() { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gt2bihvyrhv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gt2zioebpbr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gt2msyimsvd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhixingplan.top/Article/details/gt2zkxzxrsk.html

Ruby: def greet; "admin"; end
来源：http://dali.daxiang520.top/Article/details/gt2izhqtguc.html

C#:   public override string Greet() => "admin";
来源：http://dali.pengpengdd.cyou/Article/details/gt2glfhuika.html

[G07] 调用父类方法
来源：http://dali.yj20258.top/Article/details/gt2kbtivwts.html

Py:   super().greet()
来源：http://dali.jiagoushi.top/Article/details/gt2vxwkulsv.html

PHP:  parent::greet();
来源：http://dali.sysykeji.top/Article/details/gt2dlotlpla.html

JS:   super.greet();
来源：http://dali.yonumen.top/Article/details/gt2xpyeewjz.html

TS:   super.greet();
来源：http://dali.dashuyun.cn/Article/details/gt2rkshzwii.html

Java: super.greet();
来源：http://dali.nwbrower.top/Article/details/gt2csoclfne.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cheryme.top/Article/details/gt2apwbiqps.html

Ruby: super
来源：http://dali.daria6918.cn/Article/details/gt2ocfxmzvl.html

C#:   base.Greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dxpfhjsa.html

[G08] 静态方法与属性
来源：http://dali.shuidangran.top/Article/details/gt2skzzbbou.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nanxinkj.top/Article/details/gt2hioqqsgh.html

PHP:  public static function f() {}
来源：http://dali.wangdashe.top/Article/details/gt2hkvitkno.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tgaeubqe.html

TS:   static f(): void {}
来源：http://dali.andypj.xyz/Article/details/gt2nejiongn.html

Java: static void f() {}
来源：http://dali.iojbl.cn/Article/details/gt2uwokesdt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.iojbl.cn/Article/details/gt2umjvybgp.html

Ruby: def self.f; end
来源：http://dali.zhixingplan.top/Article/details/gt2athponrd.html

C#:   public static void F() {}
来源：http://dali.svipenyu.cn/Article/details/gt2piiepqsw.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigufen.top/Article/details/gt2xxujpvmb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.fzhhl.top/Article/details/gt2yztffkbw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tanke756.top/Article/details/gt2jtgwluxu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhengqikj.top/Article/details/gt2hhwrvory.html

TS:   interface Shape { area(): number; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ebxygjef.html

Java: interface Shape { double area(); }
来源：http://dali.daxiang520.top/Article/details/gt2mzlmaxmk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.bjfxy.top/Article/details/gt2zhluqekg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jyoumei.cn/Article/details/gt2iyjajlry.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgfzy.top/Article/details/gt2shpaucdh.html

[G10] 访问控制
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cicutzep.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.snrcjt.cn/Article/details/gt2gyvkjexq.html

PHP:  public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gt2wulhucba.html

JS:   #private 字段；其余公开
来源：http://dali.jiagoushi.top/Article/details/gt2tepgyvpm.html

TS:   public / protected / private
来源：http://dali.mhx1999.top/Article/details/gt2ymfiysxr.html

Java: public / protected / private / 默认包级
来源：http://dali.redwolf501.top/Article/details/gt2jmoedjdo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tmfjjlur.html

Ruby: public / protected / private
来源：http://dali.iojbl.cn/Article/details/gt2iiefwxon.html

C#:   public / protected / private / internal
来源：http://dali.yongpay.top/Article/details/gt2mikzmepg.html

[G11] getter / setter
来源：http://dali.xylfe.cn/Article/details/gt2pzjirzda.html

Py:   @property 与 @x.setter
来源：http://dali.sufxvd.cn/Article/details/gt2lajvjvdw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gt2uulvtlbm.html

JS:   get name() { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gt2dlojhhqj.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuanzx.com/Article/details/gt2lasmligc.html

Java: public String getName() { return name; }
来源：http://dali.xylfe.cn/Article/details/gt2lfgpjupn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gt2ebqxgnkk.html

Ruby: attr_accessor :name
来源：http://dali.c1oappe.top/Article/details/gt2tanewvdn.html

C#:   public string Name { get; set; }
来源：http://dali.tanke756.top/Article/details/gt2xkmmzfcx.html

[G12] 对象转字符串
来源：http://dali.hammf.cn/Article/details/gt2flbzovqd.html

Py:   def __str__(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gt2oxkfatcl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gt2geonmrdh.html

JS:   toString() { return this.name; }
来源：http://dali.tanke756.top/Article/details/gt2lscdwznn.html

TS:   toString(): string { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gt2pjrrcvrc.html

Java: @Override public String toString() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gt2oxkrdjfl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gt2gawfkwlj.html

Ruby: def to_s; @name; end
来源：http://dali.hammf.cn/Article/details/gt2tbpkdpuq.html

C#:   public override string ToString() => Name;
来源：http://dali.svipenyu.cn/Article/details/gt2ryyolnth.html

[G13] 判断对象类型
来源：http://dali.aibaodan.cn/Article/details/gt2lbgpcgtg.html

Py:   isinstance(u, User)
来源：http://dali.guowangkeji.top/Article/details/gt2fvcxbmzm.html

PHP:  $u instanceof User
来源：http://dali.yongpay.top/Article/details/gt2wtlpjbsg.html

JS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gt2zvapsyke.html

TS:   u instanceof User
来源：http://dali.xuanzx.com/Article/details/gt2rqbufxuf.html

Java: u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gt2drctahez.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yangfankeji.com/Article/details/gt2zbkjdrys.html

Ruby: u.is_a?(User)
来源：http://dali.xinyue.icu/Article/details/gt2ftgyotbo.html

C#:   u is User
来源：http://dali.tianlin.xyz/Article/details/gt2uiwlhpzf.html

[G14] 数据类 / record
来源：http://dali.cdnleiting.top/Article/details/gt2jiyxswxn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhiwuduotai.top/Article/details/gt2mkvulqoj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dianchejie.cn/Article/details/gt2bywtnxgg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinqigfzy.top/Article/details/gt2gkcmijaz.html

TS:   type User = { name: string; age: number };
来源：http://dali.sweek.top/Article/details/gt2obyltddy.html

Java: record User(String name, int age) {}
来源：http://dali.xuanzx.com/Article/details/gt2elgotixl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xziqi.cn/Article/details/gt2kprempmz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yonumen.top/Article/details/gt2lsrbatsh.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258888.top/Article/details/gt2hlsmywbm.html

[G15] 枚举
来源：http://dali.hfpthk.cn/Article/details/gt2ykmkpdxw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.daria6918.cn/Article/details/gt2focypria.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2mtwwxsju.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gaohongyu789.top/Article/details/gt2ilydpmld.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cdnleiting.top/Article/details/gt2ckldtcxm.html

Java: enum Color { RED, GREEN }
来源：http://dali.tanke756.top/Article/details/gt2uukevkqh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuanzx.com/Article/details/gt2aagzszge.html

Ruby: Color = %i[red green].freeze
来源：http://dali.c1oappe.top/Article/details/gt2yipafdrk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tian-w.cn/Article/details/gt2wlwwskqh.html

[G16] 对象转数组 / 字典
来源：http://dali.mhx1999.top/Article/details/gt2axoaoarm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxinkj.top/Article/details/gt2buwavtua.html

PHP:  get_object_vars($obj);
来源：http://dali.wangshuangyany.cn/Article/details/gt2wawiumna.html

JS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gsdsmsxe.html

TS:   Object.entries(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2qrrgjdth.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.svipenyu.cn/Article/details/gt2hmvpjaxe.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mguprzyg.html

Ruby: obj.instance_variables
来源：http://dali.cqqwz.cn/Article/details/gt2vwryztpb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gt2nbyeaowo.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2dtnccwlm.html

H. 异常与错误处理
来源：http://dali.xinyue.icu/Article/details/gt2vzjzqqtf.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2jbvbbyjd.html

[H01] try / catch 基础
来源：http://dali.dashuyun.cn/Article/details/gt2qqpxkjwk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.wangshuangyany.cn/Article/details/gt2alfslqud.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gzhubu.top/Article/details/gt2mwibvmoj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gt2exghvpsc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gt2zsqgovab.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenzaomai.com/Article/details/gt2tlxafift.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.havefunace.top/Article/details/gt2rcycqque.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.0kj1m.cn/Article/details/gt2agdzmtfs.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cqqwz.cn/Article/details/gt2whgxbqhx.html

[H02] finally / ensure 收尾
来源：http://dali.jyoumei.cn/Article/details/gt2zhmqthsp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fhmfgrwo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2oiyguejf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2mrwbutst.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gt2ptdzxofj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gt2iefoloio.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.9152youxi.cn/Article/details/gt2ijkeiyiu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yangfankeji.com/Article/details/gt2dvdidfeg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yongpay.top/Article/details/gt2jpzscywl.html

[H03] 主动抛出异常
来源：http://dali.cheryme.top/Article/details/gt2clurivwj.html

Py:   raise ValueError("错误信息")
来源：http://dali.aizwys.cn/Article/details/gt2nmdzllog.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2yyqsazpj.html

JS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gt2rjmzfegh.html

TS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2mycresre.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gt2bpyhvykc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yueranfly.top/Article/details/gt2unlzkghd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sysykeji.top/Article/details/gt2zomgvkut.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2htrpzqyh.html

[H04] 自定义异常类型
来源：http://dali.wangdashe.top/Article/details/gt2oobqkhof.html

Py:   class MyError(Exception): pass
来源：http://dali.zhixingplan.top/Article/details/gt2gqodhkpx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2qpylaawj.html

JS:   class MyError extends Error {}
来源：http://dali.aibaodan.cn/Article/details/gt2msnthzjx.html

TS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mgqdzsel.html

Java: class MyException extends RuntimeException {}
来源：http://dali.0kj1m.cn/Article/details/gt2pbpcskrl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fzhhl.top/Article/details/gt2kgbkaguc.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eyjapypj.html

C#:   class MyException : Exception {}
来源：http://dali.9152youxi.cn/Article/details/gt2odcqkxlo.html

[H05] 捕获特定类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2ryvcjeek.html

Py:   except ValueError as e:
来源：http://dali.gogol.net.cn/Article/details/gt2ywoyzmtz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hywenlv.cn/Article/details/gt2saensvyx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gt2oirlihlg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gogol.net.cn/Article/details/gt2qumcwqpr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hywenlv.cn/Article/details/gt2zknrnxle.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigufen.top/Article/details/gt2twkunzct.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhoulong.xyz/Article/details/gt2dbzumvpx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cucudq.cn/Article/details/gt2gwaznlue.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guowangkeji.top/Article/details/gt2edtqenlk.html

Py:   value = d.get("k") or default
来源：http://dali.mhx1999.top/Article/details/gt2bkxttfla.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fengsongda.top/Article/details/gt2egydviae.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pmmfvgcn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gt2xcgonngn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hysaishi.cn/Article/details/gt2bcuwdloo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sxryk.cn/Article/details/gt2njcrsgfh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tianlin.xyz/Article/details/gt2shdrqdvd.html

C#:   obj?.A?.B ?? default
来源：http://dali.9152youxi.cn/Article/details/gt2philysrt.html

[H07] 断言
来源：http://dali.shuidangran.top/Article/details/gt2ixzepuyk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.haohaochexian.top/Article/details/gt2msqvzljx.html

PHP:  assert($x > 0);
来源：http://dali.tian-w.cn/Article/details/gt2ffuaknrt.html

JS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gt2qoxxyaqz.html

TS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gt2qiucyhmj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigufen.top/Article/details/gt2gdujhpca.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinqigfzy.top/Article/details/gt2ortvmqpz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2phcbjkkw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2dzsjpmqv.html

[H08] 获取错误信息与堆栈
来源：http://dali.gaohongyu789.top/Article/details/gt2qbeakual.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenlongwang.top/Article/details/gt2dmoakgeb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jyoumei.cn/Article/details/gt2dsaboevd.html

JS:   e.message;  e.stack
来源：http://dali.aibaodan.cn/Article/details/gt2ogbpuwbb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxinkj.top/Article/details/gt2nvrntyql.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenzaomai.com/Article/details/gt2kjmvzqyh.html

Go:   err.Error()
来源：http://dali.bjfxy.top/Article/details/gt2nlvoezzj.html

Ruby: e.message;  e.backtrace
来源：http://dali.smart0.xyz/Article/details/gt2mrfuxrpv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cucudq.cn/Article/details/gt2xdvwsfow.html

[H09] 带错误码的异常
来源：http://dali.hammf.cn/Article/details/gt2mvoxhxvv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cqqwz.cn/Article/details/gt2babvanow.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hfpthk.cn/Article/details/gt2fderibrt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gogol.net.cn/Article/details/gt2patwglxx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2racdkuux.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jiagoushi.top/Article/details/gt2hpgmkpgo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sysykeji.top/Article/details/gt2jjdrdqja.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yueranfly.top/Article/details/gt2asljqsqz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yanxiufei.cn/Article/details/gt2tktibgpn.html

[H10] 资源自动释放
来源：http://dali.zhengqikj.top/Article/details/gt2cioapunr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ppjwa.cn/Article/details/gt2ozppekrh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj20258.top/Article/details/gt2vcaxmvnr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gt2kxbjlwti.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gt2nttnaptd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgufenzy.top/Article/details/gt2atoeebon.html

Go:   defer f.Close()
来源：http://dali.tianlin.xyz/Article/details/gt2rgmzioxn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hammf.cn/Article/details/gt2bmxxzzdb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2prqaxdmo.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2jmqwvssx.html

I. 正则表达式
来源：http://dali.hysaishi.cn/Article/details/gt2uvyvfhzy.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2lduseuba.html

[I01] 判断是否匹配
来源：http://dali.yonumen.top/Article/details/gt2okrpkhtr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2arbbvpjv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yueranfly.top/Article/details/gt2cewwabyy.html

JS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gt2kjhmaxte.html

TS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gt2upbndmka.html


<!-- 参考信息 -->