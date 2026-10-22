代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2dmqwekwm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uklyjacu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gt2zlplamrv.html

Go:   os.Remove("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ryiianvz.html

Ruby: File.delete("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2gufpqtfm.html

C#:   File.Delete("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2qzvvqhjc.html

[F07] 创建目录（含多级）
来源：http://dali.chenlongwang.top/Article/details/gt2phakkhye.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hammf.cn/Article/details/gt2nepqtwte.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gzhubu.top/Article/details/gt2yktzxsrp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gt2bluklgjz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gt2jhhtskci.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xylfe.cn/Article/details/gt2vctgyoga.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cheryme.top/Article/details/gt2qgpvzcnc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhongyouzk.top/Article/details/gt2fkyydzve.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xinyue.icu/Article/details/gt2jpwrplqk.html

[F08] 遍历目录
来源：http://dali.redwolf501.top/Article/details/gt2zuutlbky.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jianghu66.top/Article/details/gt2nvxihzcd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.havefunace.top/Article/details/gt2tibudarw.html

JS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gt2oejqfngm.html

TS:   fs.readdirSync("dir")
来源：http://dali.shuidangran.top/Article/details/gt2dmtwfwfv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jqgfzy.top/Article/details/gt2ytrdifbc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhengqikj.top/Article/details/gt2hjydazux.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbdyfau.html

C#:   Directory.GetFiles("dir")
来源：http://dali.bjfxy.top/Article/details/gt2hrjkzcqi.html

[F09] 获取文件大小
来源：http://dali.yvedp.cn/Article/details/gt2qdwijdph.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2nlkqfbnp.html

PHP:  filesize("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2gsvwoaej.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gt2duptjmtg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gt2solnmvxu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gt2wobtiykk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hysaishi.cn/Article/details/gt2vmxltsia.html

Ruby: File.size("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2rykpwbjx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nanxinkj.top/Article/details/gt2rcabwjdo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.aibaodan.cn/Article/details/gt2tzinujuo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gt2trkqxkad.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2jywoxtdz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2bifzlesx.html

TS:   path.extname("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ahubhuob.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.birdmap.top/Article/details/gt2xvuxgwjd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2djfxhnul.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gt2dqhoryir.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2rvczrxwi.html

[F11] 复制与移动文件
来源：http://dali.nanxinkj.top/Article/details/gt2vqdxuxgb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2omjabyco.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangdashe.top/Article/details/gt2djzdhorz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2azghddsw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2muvyjrtc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jiagoushi.top/Article/details/gt2lamxqtxo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guannengcc.top/Article/details/gt2pqvcsifq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gt2nduipbmu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yuxming.cn/Article/details/gt2bzmjncud.html

[F12] CSV 读写
来源：http://dali.tanke756.top/Article/details/gt2xosmnyyv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jqgfzy.top/Article/details/gt2xxstfeum.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhongyouzk.top/Article/details/gt2nouhwnae.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jianghu66.top/Article/details/gt2rbsopyvt.html

TS:   // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gt2kzhikcfi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vkhwwtdw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.316326.xyz/Article/details/gt2lvdrrkoh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.meibo888.top/Article/details/gt2usdwtnrt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.bjfxy.top/Article/details/gt2xgylevft.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2owrmltkf.html

G. 面向对象
来源：http://dali.jinqigfzy.top/Article/details/gt2abiummtq.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2dxbmiygt.html

[G01] 定义类
来源：http://dali.yuanzhike.top/Article/details/gt2fsgvtozv.html

Py:   class User: pass
来源：http://dali.tianlin.xyz/Article/details/gt2ryfzlzzb.html

PHP:  class User {}
来源：http://dali.birdmap.top/Article/details/gt2hlfyowqp.html

JS:   class User {}
来源：http://dali.iojbl.cn/Article/details/gt2vyinaumi.html

TS:   class User { name: string = ""; }
来源：http://dali.yangfankeji.com/Article/details/gt2doaidoio.html

Java: class User {}
来源：http://dali.yueranfly.top/Article/details/gt2shuhlwje.html

Go:   type User struct { Name string }
来源：http://dali.xuetiantiany.cn/Article/details/gt2jkeiazar.html

Ruby: class User; end
来源：http://dali.jqgufenzy.top/Article/details/gt2jwufpddq.html

C#:   class User {}
来源：http://dali.yj20258888.top/Article/details/gt2sbdpjibw.html

[G02] 构造函数
来源：http://dali.cucudq.cn/Article/details/gt2sqobqjcw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cucudq.cn/Article/details/gt2fvydiuwj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cucudq.cn/Article/details/gt2utafmmry.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2wteianxj.html

TS:   constructor(public name: string) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2zifkpgod.html

Java: User(String name) { this.name = name; }
来源：http://dali.cashguo.top/Article/details/gt2wryspdda.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhongyouzk.top/Article/details/gt2pqbnupfy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hnxiangtu.top/Article/details/gt2cxbbxgzl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2tjuaimyy.html

[G03] 实例属性
来源：http://dali.gaohongyu789.top/Article/details/gt2ftzamrsd.html

Py:   self.name = "x"
来源：http://dali.svipenyu.cn/Article/details/gt2auwloeqg.html

PHP:  public string $name = "x";
来源：http://dali.sysykeji.top/Article/details/gt2fceobzxs.html

JS:   this.name = "x";
来源：http://dali.hfpthk.cn/Article/details/gt2lppdjzje.html

TS:   name: string = "x";
来源：http://dali.ivvv.top/Article/details/gt2teqowmbp.html

Java: private String name;
来源：http://dali.nanxinkj.top/Article/details/gt2ltzhaqaf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ppjwa.cn/Article/details/gt2jrcmodpn.html

Ruby: @name = "x"
来源：http://dali.yangfankeji.com/Article/details/gt2nxdayapo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ivvv.top/Article/details/gt2xulkcdcs.html

[G04] 定义方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pndaylhn.html

Py:   def greet(self): return self.name
来源：http://dali.haohaochexian.top/Article/details/gt2dtvfbdwx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gt2sciudzaz.html

JS:   greet() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gt2iqxbgzbd.html

TS:   greet(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gt2kexmeinv.html

Java: String greet() { return name; }
来源：http://dali.shuidangran.top/Article/details/gt2vjmahhqp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gt2artgmqgi.html

Ruby: def greet; @name; end
来源：http://dali.snrcjt.cn/Article/details/gt2agbyugjq.html

C#:   public string Greet() => Name;
来源：http://dali.nwbrower.top/Article/details/gt2nuflqeap.html

[G05] 继承
来源：http://dali.fzhhl.top/Article/details/gt2fuluuovx.html

Py:   class Admin(User): pass
来源：http://dali.hnqzz.top/Article/details/gt2exahtnqa.html

PHP:  class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gt2hqqevnle.html

JS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2qrxocelc.html

TS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2mmtjtaur.html

Java: class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gt2oommvofm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.9152youxi.cn/Article/details/gt2wnhordyo.html

Ruby: class Admin < User; end
来源：http://dali.nwbrower.top/Article/details/gt2ukonjlzu.html

C#:   class Admin : User {}
来源：http://dali.bjfxy.top/Article/details/gt2timhdlti.html

[G06] 重写方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qzxecfjd.html

Py:   def greet(self): return "admin"
来源：http://dali.redwolf501.top/Article/details/gt2vyiguxei.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gt2iolaurev.html

JS:   greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gt2cacojjhn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gt2nakvhfen.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gt2offolsmq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgufenzy.top/Article/details/gt2klofjeso.html

Ruby: def greet; "admin"; end
来源：http://dali.fengsongda.top/Article/details/gt2vijjgvjd.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhiwuduotai.top/Article/details/gt2bgqkvyzt.html

[G07] 调用父类方法
来源：http://dali.zhengqikj.top/Article/details/gt2griyfwqq.html

Py:   super().greet()
来源：http://dali.316326.xyz/Article/details/gt2kycqspub.html

PHP:  parent::greet();
来源：http://dali.gzhubu.top/Article/details/gt2vwopsbzq.html

JS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gt2ooqteiaf.html

TS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gt2nokzmgeq.html

Java: super.greet();
来源：http://dali.snrcjt.cn/Article/details/gt2ygmdvcwn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ydzc1.top/Article/details/gt2dwtcipcj.html

Ruby: super
来源：http://dali.xziqi.cn/Article/details/gt2wsvryigz.html

C#:   base.Greet();
来源：http://dali.gogol.net.cn/Article/details/gt2hwnpsaqv.html

[G08] 静态方法与属性
来源：http://dali.quarkkingdee.top/Article/details/gt2hokvgcxw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2tlyzbxtr.html

PHP:  public static function f() {}
来源：http://dali.wangdashe.top/Article/details/gt2kqygxdfy.html

JS:   static f() {}
来源：http://dali.ivvv.top/Article/details/gt2kyyfohen.html

TS:   static f(): void {}
来源：http://dali.meibo888.top/Article/details/gt2qhwvhaxx.html

Java: static void f() {}
来源：http://dali.ivvv.top/Article/details/gt2xjjuucej.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.daria6918.cn/Article/details/gt2qjjqyszk.html

Ruby: def self.f; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aysciljn.html

C#:   public static void F() {}
来源：http://dali.redwolf501.top/Article/details/gt2nttcfuxn.html

[G09] 接口 / 抽象类
来源：http://dali.cdnleiting.top/Article/details/gt2hexpspia.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gogol.net.cn/Article/details/gt2lwsnhiud.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zayxiibt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xziqi.cn/Article/details/gt2hmzzijva.html

TS:   interface Shape { area(): number; }
来源：http://dali.havefunace.top/Article/details/gt2wvzmomom.html

Java: interface Shape { double area(); }
来源：http://dali.cqqwz.cn/Article/details/gt2ciivhbrt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.redwolf501.top/Article/details/gt2grslycbw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnxiangtu.top/Article/details/gt2wtjsclcs.html

C#:   interface IShape { double Area(); }
来源：http://dali.xylfe.cn/Article/details/gt2vdyypatu.html

[G10] 访问控制
来源：http://dali.yuanzhike.top/Article/details/gt2bsuicwnc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jlsjyb.cn/Article/details/gt2piutcruv.html

PHP:  public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gt2wcmloymd.html

JS:   #private 字段；其余公开
来源：http://dali.ppjwa.cn/Article/details/gt2prvhtarr.html

TS:   public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gt2xuuycfdg.html

Java: public / protected / private / 默认包级
来源：http://dali.316326.xyz/Article/details/gt2kopxclsm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tian-w.cn/Article/details/gt2aysvpoau.html

Ruby: public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gt2jvifwxge.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqdbzhh.html

[G11] getter / setter
来源：http://dali.cheryme.top/Article/details/gt2gupeoytv.html

Py:   @property 与 @x.setter
来源：http://dali.gzhubu.top/Article/details/gt2ngtwyecn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gt2vcuqelnn.html

JS:   get name() { return this._name; }
来源：http://dali.havefunace.top/Article/details/gt2nbsjqpyg.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2bxqyqaac.html

Java: public String getName() { return name; }
来源：http://dali.andypj.xyz/Article/details/gt2zdmaiwap.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gt2ujemvnqp.html

Ruby: attr_accessor :name
来源：http://dali.jqgufenzy.top/Article/details/gt2wglyvztr.html

C#:   public string Name { get; set; }
来源：http://dali.gogol.net.cn/Article/details/gt2ewgobajk.html

[G12] 对象转字符串
来源：http://dali.ivvv.top/Article/details/gt2qmxwsyys.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258888.top/Article/details/gt2zwltcwsq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2icsseqzn.html

JS:   toString() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gt2qwqrmbtq.html

TS:   toString(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lgjfkvij.html

Java: @Override public String toString() { return name; }
来源：http://dali.daxiang520.top/Article/details/gt2jwkotoqs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cnyrnssj.html

Ruby: def to_s; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nrdkbmpo.html

C#:   public override string ToString() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gt2wwcyspui.html

[G13] 判断对象类型
来源：http://dali.yj202588.top/Article/details/gt2cxfcmpiq.html

Py:   isinstance(u, User)
来源：http://dali.hnxiangtu.top/Article/details/gt2tfefzwrw.html

PHP:  $u instanceof User
来源：http://dali.tanke756.top/Article/details/gt2sanadfeh.html

JS:   u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gt2mvfnbewe.html

TS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gt2aypctyxr.html

Java: u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qvyhnzdc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pengpengdd.cyou/Article/details/gt2afxttmrk.html

Ruby: u.is_a?(User)
来源：http://dali.redwolf501.top/Article/details/gt2ojknhplt.html

C#:   u is User
来源：http://dali.iojbl.cn/Article/details/gt2rluivleg.html

[G14] 数据类 / record
来源：http://dali.xuanzx.com/Article/details/gt2gednydww.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.kuanghao11.cn/Article/details/gt2ywlxzdxf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenzaomai.com/Article/details/gt2ysetfcbb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2umzurcnh.html

TS:   type User = { name: string; age: number };
来源：http://dali.gaohongyu789.top/Article/details/gt2npsfygeq.html

Java: record User(String name, int age) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2clazhgvm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hammf.cn/Article/details/gt2btwzpwjs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnqzz.top/Article/details/gt2igldymgx.html

C#:   record User(string Name, int Age);
来源：http://dali.chenzaomai.com/Article/details/gt2hzexxjhv.html

[G15] 枚举
来源：http://dali.ivvv.top/Article/details/gt2msgduzcm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2szkcqzmj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.aibaodan.cn/Article/details/gt2uxdwbcjb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuanzx.com/Article/details/gt2ltgemnhu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gt2eevummqi.html

Java: enum Color { RED, GREEN }
来源：http://dali.shuidangran.top/Article/details/gt2fgdpjquc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cqqwz.cn/Article/details/gt2dlpsjqts.html

Ruby: Color = %i[red green].freeze
来源：http://dali.316326.xyz/Article/details/gt2aupltddw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2wqrmerje.html

[G16] 对象转数组 / 字典
来源：http://dali.zhengqikj.top/Article/details/gt2irpwwugl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sweek.top/Article/details/gt2uldqkgsg.html

PHP:  get_object_vars($obj);
来源：http://dali.shzxlz.cn/Article/details/gt2rhvttmba.html

JS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2motizrcl.html

TS:   Object.entries(obj)
来源：http://dali.birdmap.top/Article/details/gt2ualzwvee.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jlsjyb.cn/Article/details/gt2yhmwtkdx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.bjfxy.top/Article/details/gt2dslvmuof.html

Ruby: obj.instance_variables
来源：http://dali.jiagoushi.top/Article/details/gt2vexzqrhb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gt2jhqkmurq.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2wwxykafd.html

H. 异常与错误处理
来源：http://dali.xylfe.cn/Article/details/gt2wqhxwuwu.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2tllayyho.html

[H01] try / catch 基础
来源：http://dali.meibo888.top/Article/details/gt2bknyemfs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dkhxtczf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cdnleiting.top/Article/details/gt2tbgmsobl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gt2zpkjhbrf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nypkmizk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wlhreida.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenzaomai.com/Article/details/gt2rfmhykgr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aizwys.cn/Article/details/gt2btxnkoff.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cashguo.top/Article/details/gt2baetaazu.html

[H02] finally / ensure 收尾
来源：http://dali.dianchejie.cn/Article/details/gt2tjuuqfpl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cashguo.top/Article/details/gt2hxitlpye.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2vcjgozyr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gt2odzviibb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gt2zkugxahk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2tjekewsj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xziqi.cn/Article/details/gt2njedrzbu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxinkj.top/Article/details/gt2xhypedwo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsibdmdx.html

[H03] 主动抛出异常
来源：http://dali.kuanghao11.cn/Article/details/gt2jtlobcnf.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgfzy.top/Article/details/gt2wnpdizct.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gt2pyihogwb.html

JS:   throw new Error("错误信息");
来源：http://dali.aizwys.cn/Article/details/gt2kidsszhi.html

TS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gt2gabesbkt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gt2zgkniwiw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xziqi.cn/Article/details/gt2jfyuegjv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hysaishi.cn/Article/details/gt2zrdirnny.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2utqpizpz.html

[H04] 自定义异常类型
来源：http://dali.svipenyu.cn/Article/details/gt2bjirrsdf.html

Py:   class MyError(Exception): pass
来源：http://dali.hnqzz.top/Article/details/gt2wbjwipxo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gt2luycwwbh.html

JS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2eohitzly.html

TS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gt2munsucui.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gt2imgwdtmj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenlongwang.top/Article/details/gt2jxvchwdw.html

Ruby: class MyError < StandardError; end
来源：http://dali.aibaodan.cn/Article/details/gt2tqiitgfj.html

C#:   class MyException : Exception {}
来源：http://dali.cashguo.top/Article/details/gt2fckzlqmb.html

[H05] 捕获特定类型
来源：http://dali.xylfe.cn/Article/details/gt2eeorfuqb.html

Py:   except ValueError as e:
来源：http://dali.feifeiyinyue.top/Article/details/gt2dtvgaqrc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.snrcjt.cn/Article/details/gt2spuedsnd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gt2siqjmidg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gt2kknadyma.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.9152youxi.cn/Article/details/gt2pnszhciu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shuidangran.top/Article/details/gt2yuknavwi.html

Ruby: rescue ArgumentError => e
来源：http://dali.jiagoushi.top/Article/details/gt2hqnnonoo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2jdkulyih.html

[H06] 可选值 / 空值安全访问
来源：http://dali.0kj1m.cn/Article/details/gt2hjskqgai.html

Py:   value = d.get("k") or default
来源：http://dali.svipenyu.cn/Article/details/gt2smwrxfyf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gt2abpnhlad.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xuanzx.com/Article/details/gt2arjjrreo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gt2nfyudrpj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daria6918.cn/Article/details/gt2iskvqeps.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhongyouzk.top/Article/details/gt2wmnscfsx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tian-w.cn/Article/details/gt2icbaasha.html

C#:   obj?.A?.B ?? default
来源：http://dali.jyoumei.cn/Article/details/gt2vrwpexyp.html

[H07] 断言
来源：http://dali.yonumen.top/Article/details/gt2lbktilgx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ftkpejsr.html

PHP:  assert($x > 0);
来源：http://dali.pycfn.com/Article/details/gt2kghieypg.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2juhkpxda.html

TS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gt2bjuczuum.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cucudq.cn/Article/details/gt2vbgphrcj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhongyouzk.top/Article/details/gt2scymmgyw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ehwqpu.com/Article/details/gt2rvkjwwzz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gt2trlcehdt.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhixingplan.top/Article/details/gt2dpkiwyyb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinqigufen.top/Article/details/gt2cqfsiskm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhixingplan.top/Article/details/gt2fjjoyccc.html

JS:   e.message;  e.stack
来源：http://dali.fzhhl.top/Article/details/gt2nnoxtroe.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tianlin.xyz/Article/details/gt2umdcqvfv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2regxokxo.html

Go:   err.Error()
来源：http://dali.yj202588.top/Article/details/gt2zfwqcsmg.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj20258888.top/Article/details/gt2olvxpjml.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cashguo.top/Article/details/gt2ygcqeijf.html

[H09] 带错误码的异常
来源：http://dali.xuanzx.com/Article/details/gt2wnfxwaif.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.andypj.xyz/Article/details/gt2wbwhlmqc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.andypj.xyz/Article/details/gt2xkxipmyz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shzxlz.cn/Article/details/gt2gwugtszn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2buymqjci.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenzaomai.com/Article/details/gt2znbjhkzh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj20258.top/Article/details/gt2vvoxicoh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2suplswok.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.snrcjt.cn/Article/details/gt2xiutuzcb.html

[H10] 资源自动释放
来源：http://dali.havefunace.top/Article/details/gt2vcvbhjvr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xylfe.cn/Article/details/gt2uzgjmjws.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhoulong.xyz/Article/details/gt2kdnlxjdp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gzhubu.top/Article/details/gt2zwaszhqn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gt2jtgrocqs.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ehwqpu.com/Article/details/gt2ujebrsnu.html

Go:   defer f.Close()
来源：http://dali.guannengcc.top/Article/details/gt2rcgjpprh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gotoacloud.top/Article/details/gt2akrlrgbb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2hmoxbfjl.html


<!-- 参考信息 -->