代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtlcaizwoh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gtuetfwqai.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jianghu66.top/Article/details/gtjyunmlef.html

Ruby: File.exist?("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtesevjmiq.html

C#:   File.Exists("a.txt")
来源：http://dali.yj20258.top/Article/details/gteeibcwxr.html

[F06] 删除文件
来源：http://dali.cheryme.top/Article/details/gtszwugdpb.html

Py:   os.remove("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gthjahqehh.html

PHP:  unlink("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtuuwvujwi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtlvuhocal.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqvzangus.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtcgyamjds.html

Go:   os.Remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtyrexoqdl.html

Ruby: File.delete("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtdtnlnmul.html

C#:   File.Delete("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtohknvyly.html

[F07] 创建目录（含多级）
来源：http://dali.gotoacloud.top/Article/details/gtbxulldzx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinqigufen.top/Article/details/gtynsapmob.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuanzx.com/Article/details/gtqjwmegjb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gthdwkozsd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gtcffcicsb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yangfankeji.com/Article/details/gtizrpqgub.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cashguo.top/Article/details/gtpvttqevj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ydzc1.top/Article/details/gtmyvevqsd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hnqzz.top/Article/details/gtycjaxdpc.html

[F08] 遍历目录
来源：http://dali.pycfn.com/Article/details/gtxwzgviql.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yangfankeji.com/Article/details/gtvqhxnahe.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yuxming.cn/Article/details/gtjaonfign.html

JS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gtslpbdggf.html

TS:   fs.readdirSync("dir")
来源：http://dali.zycfv.cn/Article/details/gtbcqqehom.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shuidangran.top/Article/details/gtwkhbgifa.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.mhx1999.top/Article/details/gtlmdhhgrx.html

Ruby: Dir.children("dir")
来源：http://dali.snrcjt.cn/Article/details/gtrdtuokia.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hfpthk.cn/Article/details/gtzkjdjslx.html

[F09] 获取文件大小
来源：http://dali.ivvv.top/Article/details/gtjrsutrgb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtmmssfddg.html

PHP:  filesize("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtxolttjnn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jianghu66.top/Article/details/gtcufeoyop.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gtglrdopfw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttpisezfa.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.c1oappe.top/Article/details/gtjkzgvkjc.html

Ruby: File.size("a.txt")
来源：http://dali.yonumen.top/Article/details/gtylgdplpp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangshuangyany.cn/Article/details/gtcmqhhfxe.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.pycfn.com/Article/details/gtcxdtjryo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gttvqyazjs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtwaizhsmj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtebmwsjvz.html

TS:   path.extname("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtckvowphi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.bjfxy.top/Article/details/gtrbschbsh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtdfpctvly.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtxtseijpn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtjqmaphiy.html

[F11] 复制与移动文件
来源：http://dali.fzhhl.top/Article/details/gtevhgqmnh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtnruqcxwe.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.0kj1m.cn/Article/details/gtoibkvtpr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtwdbmmawr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtzywqjmnu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hammf.cn/Article/details/gtaenesmxp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.smart0.xyz/Article/details/gtvhzkzlcm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtrmvhemsa.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hywenlv.cn/Article/details/gtynntsdyr.html

[F12] CSV 读写
来源：http://dali.hammf.cn/Article/details/gtafgvcbfk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.pengpengdd.cyou/Article/details/gtuwxbctjg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtduzzbhwi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnfbfilw.html

TS:   // 同上
来源：http://dali.sufxvd.cn/Article/details/gtuqopdfrm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.redwolf501.top/Article/details/gtegglcnhv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tian-w.cn/Article/details/gtorcsqxaa.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenzaomai.com/Article/details/gtetykqerj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangshuangyany.cn/Article/details/gtogbridwg.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtprkzstho.html

G. 面向对象
来源：http://dali.aibaodan.cn/Article/details/gtetmrqfqa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtawezzrre.html

[G01] 定义类
来源：http://dali.jiagoushi.top/Article/details/gtpsjzvvtt.html

Py:   class User: pass
来源：http://dali.xylfe.cn/Article/details/gtnfhinapa.html

PHP:  class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtczhulgge.html

JS:   class User {}
来源：http://dali.aizwys.cn/Article/details/gtpxgsmjwd.html

TS:   class User { name: string = ""; }
来源：http://dali.zycfv.cn/Article/details/gtycxeuazh.html

Java: class User {}
来源：http://dali.9152youxi.cn/Article/details/gtczoflbck.html

Go:   type User struct { Name string }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfckprawj.html

Ruby: class User; end
来源：http://dali.tian-w.cn/Article/details/gtqqrxctmi.html

C#:   class User {}
来源：http://dali.cashguo.top/Article/details/gttrpdnvsi.html

[G02] 构造函数
来源：http://dali.dashuyun.cn/Article/details/gtszyyrdxn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinghuilouyu.cn/Article/details/gtniftwuaf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.iojbl.cn/Article/details/gtbwbkwprj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtxskfefzs.html

TS:   constructor(public name: string) {}
来源：http://dali.smart0.xyz/Article/details/gtyxcsfdhu.html

Java: User(String name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtbsaxhqsk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cdnleiting.top/Article/details/gtornrwket.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jianghu66.top/Article/details/gtddcrrcpy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ydzc1.top/Article/details/gthrymzaaa.html

[G03] 实例属性
来源：http://dali.fengsongda.top/Article/details/gtsqoklcbp.html

Py:   self.name = "x"
来源：http://dali.xziqi.cn/Article/details/gtagkqwkcy.html

PHP:  public string $name = "x";
来源：http://dali.tanke756.top/Article/details/gtrkmairij.html

JS:   this.name = "x";
来源：http://dali.ydzc1.top/Article/details/gtnskzohgn.html

TS:   name: string = "x";
来源：http://dali.haohaochexian.top/Article/details/gtasnvzhcd.html

Java: private String name;
来源：http://dali.meibo888.top/Article/details/gtkozokdoq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sxryk.cn/Article/details/gtizfoaqbv.html

Ruby: @name = "x"
来源：http://dali.ppjwa.cn/Article/details/gttdviajmt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrytfuqaf.html

[G04] 定义方法
来源：http://dali.jiagoushi.top/Article/details/gtwutpkeqq.html

Py:   def greet(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gtmpkovuxl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gtvslnjxsm.html

JS:   greet() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtkxenglmm.html

TS:   greet(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtentvsqmc.html

Java: String greet() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtxxojrici.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gtnupegwkf.html

Ruby: def greet; @name; end
来源：http://dali.yuanzhike.top/Article/details/gtzkorrgfh.html

C#:   public string Greet() => Name;
来源：http://dali.ehwqpu.com/Article/details/gtmclzczgr.html

[G05] 继承
来源：http://dali.zhiwuduotai.top/Article/details/gtsxfinsiy.html

Py:   class Admin(User): pass
来源：http://dali.ehwqpu.com/Article/details/gtjgdhjqhg.html

PHP:  class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gttiuakrlk.html

JS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtuufbbljq.html

TS:   class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtyxhugocn.html

Java: class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtfkxmubuu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.daria6918.cn/Article/details/gtrwsdrkum.html

Ruby: class Admin < User; end
来源：http://dali.fzhhl.top/Article/details/gtcqjtdkfn.html

C#:   class Admin : User {}
来源：http://dali.jqgfzy.top/Article/details/gtvyoqfftn.html

[G06] 重写方法
来源：http://dali.yuxming.cn/Article/details/gtdtjyhyte.html

Py:   def greet(self): return "admin"
来源：http://dali.yj202588.top/Article/details/gtcrcspqnr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtbfitnskq.html

JS:   greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwesnxqs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gttdkxihoz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtfmdqhtgk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuetiantiany.cn/Article/details/gtvzcyaukl.html

Ruby: def greet; "admin"; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpauzgimu.html

C#:   public override string Greet() => "admin";
来源：http://dali.wangdashe.top/Article/details/gtzpcappgf.html

[G07] 调用父类方法
来源：http://dali.xuanzx.com/Article/details/gtrzhopxab.html

Py:   super().greet()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmtksgmbj.html

PHP:  parent::greet();
来源：http://dali.fzhhl.top/Article/details/gtedxrsnln.html

JS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gthuteanol.html

TS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gtgjeunzvq.html

Java: super.greet();
来源：http://dali.sxryk.cn/Article/details/gttdlspbdz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzyxrrcqn.html

Ruby: super
来源：http://dali.jqgfzy.top/Article/details/gtdfptesha.html

C#:   base.Greet();
来源：http://dali.zhixingplan.top/Article/details/gtemkygxbv.html

[G08] 静态方法与属性
来源：http://dali.zhengqikj.top/Article/details/gtmswiolsz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guowangkeji.top/Article/details/gtnvmlegmb.html

PHP:  public static function f() {}
来源：http://dali.yj20258.top/Article/details/gthesgbjfp.html

JS:   static f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtyjlwmcnz.html

TS:   static f(): void {}
来源：http://dali.zhoulong.xyz/Article/details/gtxjqcottt.html

Java: static void f() {}
来源：http://dali.redwolf501.top/Article/details/gtkeghfruw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hfpthk.cn/Article/details/gtybzdrclt.html

Ruby: def self.f; end
来源：http://dali.c1oappe.top/Article/details/gtzhzcesxv.html

C#:   public static void F() {}
来源：http://dali.yonumen.top/Article/details/gtthcutwwe.html

[G09] 接口 / 抽象类
来源：http://dali.cucudq.cn/Article/details/gtwkylijgx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gtzvjmcqgl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jqgufenzy.top/Article/details/gtqeqpbkvk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xinyue.icu/Article/details/gtemfclwxo.html

TS:   interface Shape { area(): number; }
来源：http://dali.jianghu66.top/Article/details/gtiidwfavh.html

Java: interface Shape { double area(); }
来源：http://dali.nwbrower.top/Article/details/gtmhtkjnhl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daria6918.cn/Article/details/gtneqtveul.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.316326.xyz/Article/details/gtszaqhwlt.html

C#:   interface IShape { double Area(); }
来源：http://dali.haohaochexian.top/Article/details/gtrzxcuhlu.html

[G10] 访问控制
来源：http://dali.hywenlv.cn/Article/details/gtkpjzajrj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hfpthk.cn/Article/details/gtrbehpwqt.html

PHP:  public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjnmfbezr.html

JS:   #private 字段；其余公开
来源：http://dali.chenlongwang.top/Article/details/gtvtbycdnt.html

TS:   public / protected / private
来源：http://dali.ybcxt.top/Article/details/gterbkcomm.html

Java: public / protected / private / 默认包级
来源：http://dali.gzhubu.top/Article/details/gtswwoqfaq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yvedp.cn/Article/details/gtqcjcaxrl.html

Ruby: public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtpvjybxnu.html

C#:   public / protected / private / internal
来源：http://dali.haohaochexian.top/Article/details/gtoifbqevb.html

[G11] getter / setter
来源：http://dali.shuidangran.top/Article/details/gtwkvcqhpd.html

Py:   @property 与 @x.setter
来源：http://dali.xuetiantiany.cn/Article/details/gtgetejlxl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gtgmilnpji.html

JS:   get name() { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gtniibxpvz.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gtpxmmxjje.html

Java: public String getName() { return name; }
来源：http://dali.sysykeji.top/Article/details/gtoxemhhpr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtrupjvumj.html

Ruby: attr_accessor :name
来源：http://dali.yonumen.top/Article/details/gtgowwbznh.html

C#:   public string Name { get; set; }
来源：http://dali.tian-w.cn/Article/details/gtcixngjdt.html

[G12] 对象转字符串
来源：http://dali.gogol.net.cn/Article/details/gtzvpjgmrh.html

Py:   def __str__(self): return self.name
来源：http://dali.cucudq.cn/Article/details/gtefsdbeir.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gthwnpyrva.html

JS:   toString() { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gthokntsdn.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtfiduxoec.html

Java: @Override public String toString() { return name; }
来源：http://dali.sysykeji.top/Article/details/gtqnusmtmt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtevbkkokf.html

Ruby: def to_s; @name; end
来源：http://dali.svipenyu.cn/Article/details/gtltqdstly.html

C#:   public override string ToString() => Name;
来源：http://dali.jqgfzy.top/Article/details/gtnjfxyoen.html

[G13] 判断对象类型
来源：http://dali.havefunace.top/Article/details/gtcjvbgmvw.html

Py:   isinstance(u, User)
来源：http://dali.gaohongyu789.top/Article/details/gtffeexuyb.html

PHP:  $u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtobngxlei.html

JS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtauksfgpr.html

TS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtrjombjzy.html

Java: u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtftzxbvxo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aibaodan.cn/Article/details/gtqgbxvbig.html

Ruby: u.is_a?(User)
来源：http://dali.wangshuangyany.cn/Article/details/gtdebjtrmj.html

C#:   u is User
来源：http://dali.sysykeji.top/Article/details/gtpjvwnhnp.html

[G14] 数据类 / record
来源：http://dali.shzxlz.cn/Article/details/gthfmbxcoh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.redwolf501.top/Article/details/gtvzqhcyem.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yueranfly.top/Article/details/gttpjkavap.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ivvv.top/Article/details/gtitxswepo.html

TS:   type User = { name: string; age: number };
来源：http://dali.xinyue.icu/Article/details/gtpbxlmulq.html

Java: record User(String name, int age) {}
来源：http://dali.0kj1m.cn/Article/details/gtmperpppv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shangyingyoupin.top/Article/details/gtoxzllydh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cqqwz.cn/Article/details/gtivqiqocp.html

C#:   record User(string Name, int Age);
来源：http://dali.jiagoushi.top/Article/details/gtkqxtvzcq.html

[G15] 枚举
来源：http://dali.aibaodan.cn/Article/details/gtmfvssknj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shuidangran.top/Article/details/gtcsbxvztb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.smart0.xyz/Article/details/gtgucmorxw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgufenzy.top/Article/details/gtvmugmblh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtemavdyhe.html

Java: enum Color { RED, GREEN }
来源：http://dali.cqqwz.cn/Article/details/gtfapekjwn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sweek.top/Article/details/gtjmxkugxh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hysaishi.cn/Article/details/gtfpjuguvj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gtupbsngjg.html

[G16] 对象转数组 / 字典
来源：http://dali.wangdashe.top/Article/details/gtjrcopdqo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xylfe.cn/Article/details/gtcsenmlek.html

PHP:  get_object_vars($obj);
来源：http://dali.jiagoushi.top/Article/details/gttxsqtrsh.html

JS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gtmciltkkr.html

TS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gtgrvetxhc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yanxiufei.cn/Article/details/gtclmsffme.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hfpthk.cn/Article/details/gtxpssgdfb.html

Ruby: obj.instance_variables
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlscvoksj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhixingplan.top/Article/details/gtvsgjwetf.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtowizlzez.html

H. 异常与错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszytilun.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gttlyyjsei.html

[H01] try / catch 基础
来源：http://dali.daxiang520.top/Article/details/gtoyyqpfnx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.andypj.xyz/Article/details/gthadktuwx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yongpay.top/Article/details/gtfjyfuvlk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gtcfhxjced.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gtmgcsfnzf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenjidiqi.icu/Article/details/gtpjavydyc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenzaomai.com/Article/details/gtugdvshtk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xuanzx.com/Article/details/gtfxmrsslp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nanxuanxn.top/Article/details/gtnwbbohpc.html

[H02] finally / ensure 收尾
来源：http://dali.gotoacloud.top/Article/details/gttrafqbgu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shzxlz.cn/Article/details/gtqenvwesc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gtwogpsszo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtuumokfsq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtsstnjfpz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtluzdbsjh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nanxinkj.top/Article/details/gtfbinsqro.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sysykeji.top/Article/details/gteylgnmks.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtlemhngyp.html

[H03] 主动抛出异常
来源：http://dali.hammf.cn/Article/details/gtaftuphvq.html

Py:   raise ValueError("错误信息")
来源：http://dali.daxiang520.top/Article/details/gtnewpciue.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gtxhkqpykm.html

JS:   throw new Error("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtqtunkitm.html

TS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtpowinjsl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gtduzmuagf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cucudq.cn/Article/details/gtvsncwume.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nanxuanxn.top/Article/details/gtbgfayjug.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtphfrqpjk.html

[H04] 自定义异常类型
来源：http://dali.jinqigfzy.top/Article/details/gtleuhreal.html

Py:   class MyError(Exception): pass
来源：http://dali.ydzc1.top/Article/details/gturkivzdq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aizwys.cn/Article/details/gtkflhutpa.html

JS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gtuwuzsioz.html

TS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gtqpiyrola.html

Java: class MyException extends RuntimeException {}
来源：http://dali.316326.xyz/Article/details/gtkhbnjmwr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigufen.top/Article/details/gtplmxprtj.html

Ruby: class MyError < StandardError; end
来源：http://dali.hnxiangtu.top/Article/details/gtjgnsffau.html

C#:   class MyException : Exception {}
来源：http://dali.hnxiangtu.top/Article/details/gtntpqofqj.html

[H05] 捕获特定类型
来源：http://dali.pengpengdd.cyou/Article/details/gtwbctijep.html

Py:   except ValueError as e:
来源：http://dali.c1oappe.top/Article/details/gtjtgoigwy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yanxiufei.cn/Article/details/gtynatqudc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gtxedvbytc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gtlfjbyfga.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.dianchejie.cn/Article/details/gtzhnkuvtx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hnqzz.top/Article/details/gtunjrgnai.html

Ruby: rescue ArgumentError => e
来源：http://dali.feifeiyinyue.top/Article/details/gtkbayhbsg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuanzhike.top/Article/details/gtvltkbswk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhaomingkeji.xyz/Article/details/gtczhxzgck.html

Py:   value = d.get("k") or default
来源：http://dali.xuetiantiany.cn/Article/details/gtekmaexwi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cdnleiting.top/Article/details/gtzihwtkyt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gotoacloud.top/Article/details/gtmacghsaa.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gtzdkdhuku.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xuanzx.com/Article/details/gtyjtyvmcu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.fengsongda.top/Article/details/gtndrhfpro.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nwbrower.top/Article/details/gtweltjbpx.html

C#:   obj?.A?.B ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gtqkzsfbgr.html

[H07] 断言
来源：http://dali.zdqjudy.top/Article/details/gtjoyozbay.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gaohongyu789.top/Article/details/gteqhbofux.html

PHP:  assert($x > 0);
来源：http://dali.c1oappe.top/Article/details/gtbxoiciuu.html

JS:   console.assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gtocnyezox.html

TS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtoxuwwwuo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ydzc1.top/Article/details/gttfluqqqc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gotoacloud.top/Article/details/gtstjhlkxn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yangfankeji.com/Article/details/gtcoftwnrw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gtkyaxvglb.html

[H08] 获取错误信息与堆栈
来源：http://dali.nanxuanxn.top/Article/details/gtmyvganme.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenlongwang.top/Article/details/gtvpylbkeo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258.top/Article/details/gtthwvkirr.html

JS:   e.message;  e.stack
来源：http://dali.jiagoushi.top/Article/details/gtnahmutlp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnczokdrz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.andypj.xyz/Article/details/gtzqoefnbq.html

Go:   err.Error()
来源：http://dali.jyoumei.cn/Article/details/gtvhdaqjqa.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhiwuduotai.top/Article/details/gtxahltpxy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhoulong.xyz/Article/details/gtrmlftfno.html

[H09] 带错误码的异常
来源：http://dali.0kj1m.cn/Article/details/gtmsunlely.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nanxinkj.top/Article/details/gtxqeignwu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gogol.net.cn/Article/details/gtfijcydup.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ivvv.top/Article/details/gtsjctmvlc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhengqikj.top/Article/details/gtuwssfvdz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gzhubu.top/Article/details/gtjpphtvxo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xuanzx.com/Article/details/gtkjwlbtqk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.havefunace.top/Article/details/gtdhmgmivo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hnxiangtu.top/Article/details/gtbacxsczs.html

[H10] 资源自动释放
来源：http://dali.kuanghao11.cn/Article/details/gtsaiuqgag.html


<!-- 参考信息 -->