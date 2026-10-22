代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuetiantiany.cn/Article/details/gt2pxyqzefr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.mhx1999.top/Article/details/gt2usquztsq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dashuyun.cn/Article/details/gt2ooykbffp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cheryme.top/Article/details/gt2proxccuf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cdnleiting.top/Article/details/gt2uuclixrl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jyoumei.cn/Article/details/gt2eialitei.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.meibo888.top/Article/details/gt2gwrsgihu.html

[F08] 遍历目录
来源：http://dali.nanxinkj.top/Article/details/gt2anczpzmz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ivvv.top/Article/details/gt2bxlleiim.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ppjwa.cn/Article/details/gt2rtjkpivj.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gt2adnjpdpm.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2shrzhwra.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gt2bdeiljlf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.haohaochexian.top/Article/details/gt2pqforokx.html

Ruby: Dir.children("dir")
来源：http://dali.yuanzhike.top/Article/details/gt2yigmmuai.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cdnleiting.top/Article/details/gt2jssborxd.html

[F09] 获取文件大小
来源：http://dali.gogol.net.cn/Article/details/gt2balwkrpz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2oaqmnzgm.html

PHP:  filesize("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2crqxyosr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.aizwys.cn/Article/details/gt2uayqzoeq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gt2azkqziad.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2gykrntxw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.316326.xyz/Article/details/gt2cwjqztrh.html

Ruby: File.size("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2yoobjpvr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.vqdsnc.cn/Article/details/gt2mpozeaym.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yanxiufei.cn/Article/details/gt2fipyjovv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2zcytsiib.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qqzxhlrk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2mbdbeskn.html

TS:   path.extname("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2oujnfcnk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sxryk.cn/Article/details/gt2kwhjadhz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2ebxrodzv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2tcgiufkv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2vnthekjg.html

[F11] 复制与移动文件
来源：http://dali.ehwqpu.com/Article/details/gt2ngixyrui.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gt2eykeyfnu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2kumukqjl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gt2ycnbgpte.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gt2futswuoo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tanke756.top/Article/details/gt2lxtkbqvo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.aibaodan.cn/Article/details/gt2iazywvvl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gt2wlxcakvc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zdqjudy.top/Article/details/gt2ctgqcpja.html

[F12] CSV 读写
来源：http://dali.yj20258888.top/Article/details/gt2mcaucknu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hfpthk.cn/Article/details/gt2ydevkiyx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuanzx.com/Article/details/gt2ghqaauwl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zycfv.cn/Article/details/gt2qaazxuoy.html

TS:   // 同上
来源：http://dali.ivvv.top/Article/details/gt2zavnjceq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhixingplan.top/Article/details/gt2qguabijb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.andypj.xyz/Article/details/gt2ljbcqppu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jiagoushi.top/Article/details/gt2eufrfzyy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hnqzz.top/Article/details/gt2bqqgbgox.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2gxyuyzim.html

G. 面向对象
来源：http://dali.fengsongda.top/Article/details/gt2qcdafzpk.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2zdmfnmtp.html

[G01] 定义类
来源：http://dali.kuanghao11.cn/Article/details/gt2ffchojch.html

Py:   class User: pass
来源：http://dali.pycfn.com/Article/details/gt2fjulbtbw.html

PHP:  class User {}
来源：http://dali.sufxvd.cn/Article/details/gt2wojghvua.html

JS:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gt2vpvwkxom.html

TS:   class User { name: string = ""; }
来源：http://dali.jqgfzy.top/Article/details/gt2fuupvynz.html

Java: class User {}
来源：http://dali.fzhhl.top/Article/details/gt2izvtimyd.html

Go:   type User struct { Name string }
来源：http://dali.ivvv.top/Article/details/gt2gpvcvyeh.html

Ruby: class User; end
来源：http://dali.snrcjt.cn/Article/details/gt2tbfgnpwz.html

C#:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gt2svhqvatb.html

[G02] 构造函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jenqetjo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gzhubu.top/Article/details/gt2ybjlbldt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.iojbl.cn/Article/details/gt2roizlwue.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258.top/Article/details/gt2rstxrgfp.html

TS:   constructor(public name: string) {}
来源：http://dali.dashuyun.cn/Article/details/gt2cqrjyifd.html

Java: User(String name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2adqlrwji.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.haohaochexian.top/Article/details/gt2vshxuaxi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sweek.top/Article/details/gt2ejokhwfp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhixingplan.top/Article/details/gt2uchqozkb.html

[G03] 实例属性
来源：http://dali.shzxlz.cn/Article/details/gt2rvocjump.html

Py:   self.name = "x"
来源：http://dali.wangdashe.top/Article/details/gt2mtufbeqw.html

PHP:  public string $name = "x";
来源：http://dali.hywenlv.cn/Article/details/gt2ubvemkex.html

JS:   this.name = "x";
来源：http://dali.andypj.xyz/Article/details/gt2dwmvemqj.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2prvfgutu.html

Java: private String name;
来源：http://dali.fzhhl.top/Article/details/gt2ekiiztub.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gzhubu.top/Article/details/gt2ygjydhmo.html

Ruby: @name = "x"
来源：http://dali.yonumen.top/Article/details/gt2seygsvqe.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gotoacloud.top/Article/details/gt2syibzyuw.html

[G04] 定义方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2awgcupcb.html

Py:   def greet(self): return self.name
来源：http://dali.jinqigfzy.top/Article/details/gt2xrjbmwti.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2lydaafbl.html

JS:   greet() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gt2sqygbnkt.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tfgusdof.html

Java: String greet() { return name; }
来源：http://dali.hnqzz.top/Article/details/gt2rnkhpznw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gt2dvkdalug.html

Ruby: def greet; @name; end
来源：http://dali.chenzaomai.com/Article/details/gt2yhubaxle.html

C#:   public string Greet() => Name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zpxyixpr.html

[G05] 继承
来源：http://dali.guowangkeji.top/Article/details/gt2xuwtpeap.html

Py:   class Admin(User): pass
来源：http://dali.fzhhl.top/Article/details/gt2trvqnjyq.html

PHP:  class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2wlzrapfm.html

JS:   class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gt2mzcdbiye.html

TS:   class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2inoxkjnb.html

Java: class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gt2ngrwkvtd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kxglmivh.html

Ruby: class Admin < User; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2xdxaxklk.html

C#:   class Admin : User {}
来源：http://dali.havefunace.top/Article/details/gt2zikhatxp.html

[G06] 重写方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dekhxesc.html

Py:   def greet(self): return "admin"
来源：http://dali.bjfxy.top/Article/details/gt2lwfhztxh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gt2oerjotsc.html

JS:   greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2paysoazy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gt2dmsteoeo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gt2jkqhcdec.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yueranfly.top/Article/details/gt2qzbbvslv.html

Ruby: def greet; "admin"; end
来源：http://dali.shzxlz.cn/Article/details/gt2umcevgeu.html

C#:   public override string Greet() => "admin";
来源：http://dali.mhx1999.top/Article/details/gt2vtyhayhz.html

[G07] 调用父类方法
来源：http://dali.hongshengwenyu.top/Article/details/gt2wlnzduys.html

Py:   super().greet()
来源：http://dali.yvedp.cn/Article/details/gt2swrmiyxu.html

PHP:  parent::greet();
来源：http://dali.guannengcc.top/Article/details/gt2pwcimcwo.html

JS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gt2qxxkncvg.html

TS:   super.greet();
来源：http://dali.xziqi.cn/Article/details/gt2kctuscla.html

Java: super.greet();
来源：http://dali.xinyue.icu/Article/details/gt2nonwvcej.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.wangshuangyany.cn/Article/details/gt2cirvbjqf.html

Ruby: super
来源：http://dali.zycfv.cn/Article/details/gt2hbiwtdzu.html

C#:   base.Greet();
来源：http://dali.gzhubu.top/Article/details/gt2hibosnau.html

[G08] 静态方法与属性
来源：http://dali.jinqigufen.top/Article/details/gt2stoejdda.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.mhx1999.top/Article/details/gt2uughrqzi.html

PHP:  public static function f() {}
来源：http://dali.daria6918.cn/Article/details/gt2iioxeaap.html

JS:   static f() {}
来源：http://dali.yanxiufei.cn/Article/details/gt2rdyescde.html

TS:   static f(): void {}
来源：http://dali.ydzc1.top/Article/details/gt2dgmevzcn.html

Java: static void f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2vairdtge.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cucudq.cn/Article/details/gt2aargproj.html

Ruby: def self.f; end
来源：http://dali.guannengcc.top/Article/details/gt2hnnpumtg.html

C#:   public static void F() {}
来源：http://dali.nwbrower.top/Article/details/gt2smsifevl.html

[G09] 接口 / 抽象类
来源：http://dali.svipenyu.cn/Article/details/gt2hwumdswj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhiwuduotai.top/Article/details/gt2jadylzoj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnqzz.top/Article/details/gt2xijhkdwz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gogol.net.cn/Article/details/gt2wbdaagap.html

TS:   interface Shape { area(): number; }
来源：http://dali.gogol.net.cn/Article/details/gt2fjvexuxy.html

Java: interface Shape { double area(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2nsevxdxf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxinkj.top/Article/details/gt2fonamlrd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.iojbl.cn/Article/details/gt2zysvluwm.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2kapytfue.html

[G10] 访问控制
来源：http://dali.yuanzhike.top/Article/details/gt2nhgzcnry.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.pengpengdd.cyou/Article/details/gt2penzwfci.html

PHP:  public / protected / private
来源：http://dali.meibo888.top/Article/details/gt2vgmosovg.html

JS:   #private 字段；其余公开
来源：http://dali.jyoumei.cn/Article/details/gt2pegzjopr.html

TS:   public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gt2ewhlmuta.html

Java: public / protected / private / 默认包级
来源：http://dali.cucudq.cn/Article/details/gt2perxoaqi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ehwqpu.com/Article/details/gt2dldlzpmr.html

Ruby: public / protected / private
来源：http://dali.tanke756.top/Article/details/gt2bonhxqps.html

C#:   public / protected / private / internal
来源：http://dali.iojbl.cn/Article/details/gt2fjkupaox.html

[G11] getter / setter
来源：http://dali.shangyingyoupin.top/Article/details/gt2zsnhqqiv.html

Py:   @property 与 @x.setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vozcvfpo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gt2tipcuclm.html

JS:   get name() { return this._name; }
来源：http://dali.yvedp.cn/Article/details/gt2ybrnuvzs.html

TS:   get name(): string { return this._name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2itprhktb.html

Java: public String getName() { return name; }
来源：http://dali.havefunace.top/Article/details/gt2sxzogqjk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gt2hrvkffwc.html

Ruby: attr_accessor :name
来源：http://dali.gzhubu.top/Article/details/gt2bnqrucpj.html

C#:   public string Name { get; set; }
来源：http://dali.quarkkingdee.top/Article/details/gt2rdsqmuws.html

[G12] 对象转字符串
来源：http://dali.zdqjudy.top/Article/details/gt2alorydjq.html

Py:   def __str__(self): return self.name
来源：http://dali.iojbl.cn/Article/details/gt2zebakpzu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gt2vakxmsab.html

JS:   toString() { return this.name; }
来源：http://dali.ivvv.top/Article/details/gt2zfnlcyxr.html

TS:   toString(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ttkdvdvh.html

Java: @Override public String toString() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gt2eqxdbnyb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gt2myxqakcz.html

Ruby: def to_s; @name; end
来源：http://dali.iojbl.cn/Article/details/gt2ehiltczx.html

C#:   public override string ToString() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gt2djmaifal.html

[G13] 判断对象类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2wnffpusv.html

Py:   isinstance(u, User)
来源：http://dali.cqqwz.cn/Article/details/gt2weksmkpu.html

PHP:  $u instanceof User
来源：http://dali.andypj.xyz/Article/details/gt2revcgckx.html

JS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gt2kwnrnbhl.html

TS:   u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gt2oecdbjsb.html

Java: u instanceof User
来源：http://dali.meibo888.top/Article/details/gt2pvnygvcz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cqqwz.cn/Article/details/gt2zzaobqjv.html

Ruby: u.is_a?(User)
来源：http://dali.0kj1m.cn/Article/details/gt2zvhhvztc.html

C#:   u is User
来源：http://dali.pycfn.com/Article/details/gt2zqvixazv.html

[G14] 数据类 / record
来源：http://dali.chenjidiqi.icu/Article/details/gt2ajbzapph.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yongpay.top/Article/details/gt2qnzjkmvh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jlsjyb.cn/Article/details/gt2flvndtkb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lprpysbj.html

TS:   type User = { name: string; age: number };
来源：http://dali.hnxiangtu.top/Article/details/gt2onapywfv.html

Java: record User(String name, int age) {}
来源：http://dali.zhengqikj.top/Article/details/gt2pmyfdfoy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xziqi.cn/Article/details/gt2eyairvro.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gaohongyu789.top/Article/details/gt2furnqzxm.html

C#:   record User(string Name, int Age);
来源：http://dali.jianghu66.top/Article/details/gt2eujfgqqy.html

[G15] 枚举
来源：http://dali.feifeiyinyue.top/Article/details/gt2rwlatyfs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.birdmap.top/Article/details/gt2yxxwcjur.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj202588.top/Article/details/gt2inytunlk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gotoacloud.top/Article/details/gt2oltozkyv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fengsongda.top/Article/details/gt2razpnbzy.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vxwwvlov.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.svipenyu.cn/Article/details/gt2vszmnxoq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sysykeji.top/Article/details/gt2dgmbywrx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gt2zoycxslm.html

[G16] 对象转数组 / 字典
来源：http://dali.zhengqikj.top/Article/details/gt2gijfgpex.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2awazugfc.html

PHP:  get_object_vars($obj);
来源：http://dali.gogol.net.cn/Article/details/gt2yidymxph.html

JS:   Object.entries(obj)
来源：http://dali.nwbrower.top/Article/details/gt2bnjrojsh.html

TS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2zjnuhhft.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shzxlz.cn/Article/details/gt2gvmprind.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daria6918.cn/Article/details/gt2vextfloj.html

Ruby: obj.instance_variables
来源：http://dali.cheryme.top/Article/details/gt2axescwyw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhixingplan.top/Article/details/gt2ipmqgffk.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zcgtpxsy.html

H. 异常与错误处理
来源：http://dali.shzxlz.cn/Article/details/gt2kutdvpis.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtqmvhj.html

[H01] try / catch 基础
来源：http://dali.zdqjudy.top/Article/details/gt2obzlqqed.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.haohaochexian.top/Article/details/gt2nqlyqoam.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2mpoonmml.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gt2iwskwomi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gt2ojmsarqr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cnzhcvmy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.meibo888.top/Article/details/gt2irffqtrg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgufenzy.top/Article/details/gt2kecqzyok.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jianghu66.top/Article/details/gt2oydisesi.html

[H02] finally / ensure 收尾
来源：http://dali.meibo888.top/Article/details/gt2guokpxmu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhengqikj.top/Article/details/gt2xrbhcpgq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dwrxudxd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2iulrgbdo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gt2oqkbfgfg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tpwvajjz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.quarkkingdee.top/Article/details/gt2rwsnwavh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.9152youxi.cn/Article/details/gt2mgydjwry.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gt2zyzyaike.html

[H03] 主动抛出异常
来源：http://dali.yj202588.top/Article/details/gt2jnldewxi.html

Py:   raise ValueError("错误信息")
来源：http://dali.kuanghao11.cn/Article/details/gt2aheeqwjp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2arwtyvlr.html

JS:   throw new Error("错误信息");
来源：http://dali.aizwys.cn/Article/details/gt2ysdzrihf.html

TS:   throw new Error("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gt2qbgpzjvt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gt2gzvdbtds.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.vqdsnc.cn/Article/details/gt2nxwmcknx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj202588.top/Article/details/gt2wpopxrfd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gt2eabihpwh.html

[H04] 自定义异常类型
来源：http://dali.dianchejie.cn/Article/details/gt2kfbdmmdm.html

Py:   class MyError(Exception): pass
来源：http://dali.xuanzx.com/Article/details/gt2daauzrdc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2mdnfzxkt.html

JS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gt2jnyqtrtk.html

TS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gt2mjzqdent.html

Java: class MyException extends RuntimeException {}
来源：http://dali.316326.xyz/Article/details/gt2veiggrxd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqssmkp.html

Ruby: class MyError < StandardError; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ypijgwlt.html

C#:   class MyException : Exception {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2akclpraq.html

[H05] 捕获特定类型
来源：http://dali.yonumen.top/Article/details/gt2qwggkwiu.html

Py:   except ValueError as e:
来源：http://dali.yongpay.top/Article/details/gt2nelukqgw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yvedp.cn/Article/details/gt2etlxjtnr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ployukaf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.haohaochexian.top/Article/details/gt2cbigmhef.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sxryk.cn/Article/details/gt2veqmlaxg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hywenlv.cn/Article/details/gt2jhbtybut.html

Ruby: rescue ArgumentError => e
来源：http://dali.yueranfly.top/Article/details/gt2raozbdhk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2wzdszqjd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rnrbcdhn.html

Py:   value = d.get("k") or default
来源：http://dali.xinyue.icu/Article/details/gt2sorvkntw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ohqcrtpw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhoulong.xyz/Article/details/gt2mdpfntjs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gt2mtewtohb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xuetiantiany.cn/Article/details/gt2aoxbocfz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.aizwys.cn/Article/details/gt2sqokzsfi.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dashuyun.cn/Article/details/gt2iovwitvo.html

C#:   obj?.A?.B ?? default
来源：http://dali.xylfe.cn/Article/details/gt2kgxxqinm.html

[H07] 断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pwitcgcj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aibaodan.cn/Article/details/gt2ikgxfgkf.html

PHP:  assert($x > 0);
来源：http://dali.gogol.net.cn/Article/details/gt2fljaynao.html

JS:   console.assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gt2fzhbvure.html

TS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gt2chfwuslr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zycfv.cn/Article/details/gt2jbujjrcd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kwwqbapa.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuxming.cn/Article/details/gt2rizcahcg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gt2xesicerz.html

[H08] 获取错误信息与堆栈
来源：http://dali.cheryme.top/Article/details/gt2jrasdfus.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhengqikj.top/Article/details/gt2szrouxlb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.haohaochexian.top/Article/details/gt2vmxzphlm.html

JS:   e.message;  e.stack
来源：http://dali.tian-w.cn/Article/details/gt2rrbzzwzc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tanke756.top/Article/details/gt2wnqdxrvn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.fzhhl.top/Article/details/gt2zrmrviup.html

Go:   err.Error()
来源：http://dali.nanxinkj.top/Article/details/gt2njfradev.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgufenzy.top/Article/details/gt2kodbwzmm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuetiantiany.cn/Article/details/gt2mcrsfpud.html

[H09] 带错误码的异常
来源：http://dali.ehwqpu.com/Article/details/gt2gurtdpau.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gotoacloud.top/Article/details/gt2jkxcujlr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xylfe.cn/Article/details/gt2xpogdlqt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aibaodan.cn/Article/details/gt2rfgfitpd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yanxiufei.cn/Article/details/gt2cxwzrhuj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.iojbl.cn/Article/details/gt2jknnwelp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jlsjyb.cn/Article/details/gt2dazwqoyy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fnhfrtln.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sweek.top/Article/details/gt2ciqnitsl.html

[H10] 资源自动释放
来源：http://dali.jinqigfzy.top/Article/details/gt2jilqfffu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qyhfkqev.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ybcxt.top/Article/details/gt2afywezcw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gt2rbuqxxfi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.kuanghao11.cn/Article/details/gt2mnufeqal.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.dianchejie.cn/Article/details/gt2bvvcbyfq.html

Go:   defer f.Close()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pificzwg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.pycfn.com/Article/details/gt2mzshvryi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2rxvyxjlq.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2zjeggknc.html

I. 正则表达式
来源：http://dali.ybcxt.top/Article/details/gt2qqtlonih.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2pjmliwvs.html

[I01] 判断是否匹配
来源：http://dali.jianghu66.top/Article/details/gt2qavmeamy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.svipenyu.cn/Article/details/gt2xbgqaxhf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gt2zuovcboy.html

JS:   /\d+/.test(s)
来源：http://dali.xziqi.cn/Article/details/gt2dtditizv.html

TS:   /\d+/.test(s)
来源：http://dali.gzhubu.top/Article/details/gt2odvowmze.html


<!-- 参考信息 -->