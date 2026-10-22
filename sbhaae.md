代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.svipenyu.cn/Article/details/gt2opifplbj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.iojbl.cn/Article/details/gt2zyzbvfoe.html

PHP:  file_exists("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2gfdvawlu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2bvkivutf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2psiycrcc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gt2whlonkwo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.guannengcc.top/Article/details/gt2lwnbmydb.html

Ruby: File.exist?("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2wrfbwcst.html

C#:   File.Exists("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ixdsedzt.html

[F06] 删除文件
来源：http://dali.yj20258.top/Article/details/gt2hsncorql.html

Py:   os.remove("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2ecpxebvy.html

PHP:  unlink("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2mcyijrfp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2bccyjesk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2yxjfjrdq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gt2sqzlsxge.html

Go:   os.Remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2wzbuhxpj.html

Ruby: File.delete("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2armzemmj.html

C#:   File.Delete("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2fxzhzjkr.html

[F07] 创建目录（含多级）
来源：http://dali.jianghu66.top/Article/details/gt2keuaadot.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2obgyjlmn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhengqikj.top/Article/details/gt2afzcixko.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yonumen.top/Article/details/gt2gqcoiuio.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pengpengdd.cyou/Article/details/gt2yusvmsxn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cucudq.cn/Article/details/gt2hknkqjnx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenzaomai.com/Article/details/gt2siluhmao.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xziqi.cn/Article/details/gt2itfsucgj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhongyouzk.top/Article/details/gt2kzvuqvqs.html

[F08] 遍历目录
来源：http://dali.chenjidiqi.icu/Article/details/gt2hqdllpci.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xziqi.cn/Article/details/gt2rawqhhge.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.svipenyu.cn/Article/details/gt2znqlieav.html

JS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gt2eiimwgau.html

TS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gt2fictgmtz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gt2oqphybqd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigfzy.top/Article/details/gt2bzgsyvyn.html

Ruby: Dir.children("dir")
来源：http://dali.quarkkingdee.top/Article/details/gt2ggtwybci.html

C#:   Directory.GetFiles("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2vtrdvspw.html

[F09] 获取文件大小
来源：http://dali.sweek.top/Article/details/gt2feegbtor.html

Py:   os.path.getsize("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2zpfvxxri.html

PHP:  filesize("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2hdivliqn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ehwqpu.com/Article/details/gt2xpkwhqsl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinghuilouyu.cn/Article/details/gt2krbiiqfi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gt2gkiswmqw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guowangkeji.top/Article/details/gt2kwplkiik.html

Ruby: File.size("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2aeldrupt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ivvv.top/Article/details/gt2rlangbqs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.dashuyun.cn/Article/details/gt2zbkavfjo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2rgfccotq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2mzydejlr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2mmtmtuxd.html

TS:   path.extname("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2pqdzpjhh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nanxuanxn.top/Article/details/gt2metdwtng.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gt2vcjmdzhk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nwbrtmda.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2bfdhebnr.html

[F11] 复制与移动文件
来源：http://dali.nanxuanxn.top/Article/details/gt2tkryujiy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2njebtmrd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yonumen.top/Article/details/gt2avpepdka.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2vuuzvxjd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pqpbobct.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yueranfly.top/Article/details/gt2hrmqvtbr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.kuanghao11.cn/Article/details/gt2yjiulwmk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gt2owbszszz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pycfn.com/Article/details/gt2uuvkqiib.html

[F12] CSV 读写
来源：http://dali.fzhhl.top/Article/details/gt2lgqiwcrt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hfpthk.cn/Article/details/gt2bdiueuic.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ybcxt.top/Article/details/gt2ekiemhil.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ybcxt.top/Article/details/gt2wvoufwpt.html

TS:   // 同上
来源：http://dali.gogol.net.cn/Article/details/gt2zrbpdwnl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhengqikj.top/Article/details/gt2mreublzi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhongyouzk.top/Article/details/gt2xoxzcemy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.daria6918.cn/Article/details/gt2nqqqjihs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cheryme.top/Article/details/gt2lcfuwdbh.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2fgrepduh.html

G. 面向对象
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lhvpxwkm.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2nsbmazap.html

[G01] 定义类
来源：http://dali.iojbl.cn/Article/details/gt2agjqzsey.html

Py:   class User: pass
来源：http://dali.yvedp.cn/Article/details/gt2kwvjvgcu.html

PHP:  class User {}
来源：http://dali.c1oappe.top/Article/details/gt2qvppdiig.html

JS:   class User {}
来源：http://dali.nwbrower.top/Article/details/gt2pkqeavns.html

TS:   class User { name: string = ""; }
来源：http://dali.fzhhl.top/Article/details/gt2ubbhxsbd.html

Java: class User {}
来源：http://dali.cashguo.top/Article/details/gt2godgphpu.html

Go:   type User struct { Name string }
来源：http://dali.shzxlz.cn/Article/details/gt2ppwkiipm.html

Ruby: class User; end
来源：http://dali.zycfv.cn/Article/details/gt2vvjiqift.html

C#:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gt2misvztqy.html

[G02] 构造函数
来源：http://dali.ehwqpu.com/Article/details/gt2knzlqulq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.andypj.xyz/Article/details/gt2pocnjspz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2tylotxik.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gt2klmdywmt.html

TS:   constructor(public name: string) {}
来源：http://dali.c1oappe.top/Article/details/gt2qtntramc.html

Java: User(String name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gt2jotxrijd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hywenlv.cn/Article/details/gt2ynonogol.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.haohaochexian.top/Article/details/gt2zuypyzmq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guannengcc.top/Article/details/gt2tqjqfhqd.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2spqsymku.html

Py:   self.name = "x"
来源：http://dali.ivvv.top/Article/details/gt2cwaljoub.html

PHP:  public string $name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gt2jsvsmuvl.html

JS:   this.name = "x";
来源：http://dali.hywenlv.cn/Article/details/gt2tujvgwpu.html

TS:   name: string = "x";
来源：http://dali.jinqigfzy.top/Article/details/gt2ioeiufbq.html

Java: private String name;
来源：http://dali.dashuyun.cn/Article/details/gt2vklsyjtb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258888.top/Article/details/gt2ojsoixcg.html

Ruby: @name = "x"
来源：http://dali.yvedp.cn/Article/details/gt2otpfdymd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aibaodan.cn/Article/details/gt2htagjplt.html

[G04] 定义方法
来源：http://dali.nwbrower.top/Article/details/gt2kogwihpd.html

Py:   def greet(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gt2leogndks.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gt2gobkrbmd.html

JS:   greet() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gt2tflozdfg.html

TS:   greet(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gt2uejqxmas.html

Java: String greet() { return name; }
来源：http://dali.316326.xyz/Article/details/gt2dlgsgqws.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gt2iubupuwx.html

Ruby: def greet; @name; end
来源：http://dali.yj202588.top/Article/details/gt2lrrzgsoe.html

C#:   public string Greet() => Name;
来源：http://dali.c1oappe.top/Article/details/gt2rmnnsfwo.html

[G05] 继承
来源：http://dali.cdnleiting.top/Article/details/gt2eyrhawvn.html

Py:   class Admin(User): pass
来源：http://dali.jinqigfzy.top/Article/details/gt2hkdycfdn.html

PHP:  class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gt2dkuirtsm.html

JS:   class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gt2utjuavnb.html

TS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2euqcptnj.html

Java: class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gt2pprtdlxr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hysaishi.cn/Article/details/gt2potjtwww.html

Ruby: class Admin < User; end
来源：http://dali.ppjwa.cn/Article/details/gt2yuwknxmx.html

C#:   class Admin : User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2kfylpemu.html

[G06] 重写方法
来源：http://dali.xziqi.cn/Article/details/gt2yrfqjpwl.html

Py:   def greet(self): return "admin"
来源：http://dali.yuanzhike.top/Article/details/gt2vxuhxhjs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rexikyjr.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gt2gikddvul.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gt2yahzacma.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gt2wguzzymm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ydzc1.top/Article/details/gt2pjmificc.html

Ruby: def greet; "admin"; end
来源：http://dali.havefunace.top/Article/details/gt2pbsztuph.html

C#:   public override string Greet() => "admin";
来源：http://dali.tian-w.cn/Article/details/gt2xjufixvt.html

[G07] 调用父类方法
来源：http://dali.yuanzhike.top/Article/details/gt2ccfrxlrp.html

Py:   super().greet()
来源：http://dali.xuetiantiany.cn/Article/details/gt2rhvaokfe.html

PHP:  parent::greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2upxgbqww.html

JS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gt2gzpdxiho.html

TS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gt2nisowwlp.html

Java: super.greet();
来源：http://dali.chenzaomai.com/Article/details/gt2suvfnmfm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ivvv.top/Article/details/gt2huhiqpvq.html

Ruby: super
来源：http://dali.xinyue.icu/Article/details/gt2xoidjuvm.html

C#:   base.Greet();
来源：http://dali.daria6918.cn/Article/details/gt2ltoflekf.html

[G08] 静态方法与属性
来源：http://dali.gzhubu.top/Article/details/gt2oewpanee.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hfpthk.cn/Article/details/gt2ymmbsdcz.html

PHP:  public static function f() {}
来源：http://dali.aibaodan.cn/Article/details/gt2dhadxsti.html

JS:   static f() {}
来源：http://dali.cashguo.top/Article/details/gt2wrcssiyh.html

TS:   static f(): void {}
来源：http://dali.nanxuanxn.top/Article/details/gt2plnsvpam.html

Java: static void f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2efywqdmt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.vqdsnc.cn/Article/details/gt2zdpzfeeb.html

Ruby: def self.f; end
来源：http://dali.quarkkingdee.top/Article/details/gt2zrfydkri.html

C#:   public static void F() {}
来源：http://dali.snrcjt.cn/Article/details/gt2dvafgobh.html

[G09] 接口 / 抽象类
来源：http://dali.pycfn.com/Article/details/gt2gpxjndyo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.andypj.xyz/Article/details/gt2swmbjhnh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ehwqpu.com/Article/details/gt2ylawtpjq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daria6918.cn/Article/details/gt2zuhxcowt.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258888.top/Article/details/gt2okqlskfa.html

Java: interface Shape { double area(); }
来源：http://dali.yvedp.cn/Article/details/gt2yirwxxyx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tianlin.xyz/Article/details/gt2ssdsfqlt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aizwys.cn/Article/details/gt2jdsavkgy.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgfzy.top/Article/details/gt2djqbtfmq.html

[G10] 访问控制
来源：http://dali.316326.xyz/Article/details/gt2frthnssg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cdnleiting.top/Article/details/gt2vtnwsvro.html

PHP:  public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gt2wdjabibc.html

JS:   #private 字段；其余公开
来源：http://dali.cqqwz.cn/Article/details/gt2ufeorxac.html

TS:   public / protected / private
来源：http://dali.bjfxy.top/Article/details/gt2prngfvlh.html

Java: public / protected / private / 默认包级
来源：http://dali.haohaochexian.top/Article/details/gt2pukrcvne.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.kuanghao11.cn/Article/details/gt2dghrgmdz.html

Ruby: public / protected / private
来源：http://dali.mhx1999.top/Article/details/gt2ithpmdsv.html

C#:   public / protected / private / internal
来源：http://dali.hnxiangtu.top/Article/details/gt2xfoamqcw.html

[G11] getter / setter
来源：http://dali.nanxuanxn.top/Article/details/gt2rgfrxmxe.html

Py:   @property 与 @x.setter
来源：http://dali.pengpengdd.cyou/Article/details/gt2xglcnmux.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gt2gmufzfky.html

JS:   get name() { return this._name; }
来源：http://dali.yvedp.cn/Article/details/gt2zrzvpdqu.html

TS:   get name(): string { return this._name; }
来源：http://dali.tian-w.cn/Article/details/gt2gsdtkjmd.html

Java: public String getName() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gt2xjtledpy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gt2itsaigzf.html

Ruby: attr_accessor :name
来源：http://dali.zdqjudy.top/Article/details/gt2jebqogdq.html

C#:   public string Name { get; set; }
来源：http://dali.dashuyun.cn/Article/details/gt2gbolbwyq.html

[G12] 对象转字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2uarzkamv.html

Py:   def __str__(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gt2papoqjrk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gt2kqnqlrlv.html

JS:   toString() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gt2cluegekx.html

TS:   toString(): string { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gt2yqvrmqvt.html

Java: @Override public String toString() { return name; }
来源：http://dali.cashguo.top/Article/details/gt2hfwblqgl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gt2yqalyoxs.html

Ruby: def to_s; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gt2nulpkdcd.html

C#:   public override string ToString() => Name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oqrnvmkm.html

[G13] 判断对象类型
来源：http://dali.aibaodan.cn/Article/details/gt2kdpreceu.html

Py:   isinstance(u, User)
来源：http://dali.aizwys.cn/Article/details/gt2jfcupnff.html

PHP:  $u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gt2fdggfczf.html

JS:   u instanceof User
来源：http://dali.sxryk.cn/Article/details/gt2gwznoaum.html

TS:   u instanceof User
来源：http://dali.mhx1999.top/Article/details/gt2twodmgwn.html

Java: u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2gnrhjltm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hfpthk.cn/Article/details/gt2tpwyzikm.html

Ruby: u.is_a?(User)
来源：http://dali.fzhhl.top/Article/details/gt2pcctukqq.html

C#:   u is User
来源：http://dali.daxiang520.top/Article/details/gt2okbhorxj.html

[G14] 数据类 / record
来源：http://dali.fzhhl.top/Article/details/gt2crlwuqmk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daria6918.cn/Article/details/gt2ntaljwpm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aizwys.cn/Article/details/gt2phqfauuj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guowangkeji.top/Article/details/gt2pgtdeswq.html

TS:   type User = { name: string; age: number };
来源：http://dali.jqgufenzy.top/Article/details/gt2bwqyyfec.html

Java: record User(String name, int age) {}
来源：http://dali.jyoumei.cn/Article/details/gt2qwxenjna.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ehwqpu.com/Article/details/gt2ceudfbjk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cdnleiting.top/Article/details/gt2fptwnwxq.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258.top/Article/details/gt2knxcuajs.html

[G15] 枚举
来源：http://dali.fzhhl.top/Article/details/gt2qjhngglc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yanxiufei.cn/Article/details/gt2voybubpz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gogol.net.cn/Article/details/gt2ukrccgfm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.andypj.xyz/Article/details/gt2mzuwxenl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tanke756.top/Article/details/gt2ewazafnj.html

Java: enum Color { RED, GREEN }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qigowccc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenzaomai.com/Article/details/gt2dcmhlixt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ehwqpu.com/Article/details/gt2mwvtjqba.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnxiangtu.top/Article/details/gt2qmytqfre.html

[G16] 对象转数组 / 字典
来源：http://dali.hongshengwenyu.top/Article/details/gt2rptaznaw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhongyouzk.top/Article/details/gt2crovshre.html

PHP:  get_object_vars($obj);
来源：http://dali.ydzc1.top/Article/details/gt2evpamaod.html

JS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gt2ugevteaw.html

TS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2rqymcoed.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhongyouzk.top/Article/details/gt2tlzuhwau.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgufenzy.top/Article/details/gt2qgsykqcv.html

Ruby: obj.instance_variables
来源：http://dali.fzhhl.top/Article/details/gt2kbxnyofh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tanke756.top/Article/details/gt2tfsjqtgq.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2aasootbo.html

H. 异常与错误处理
来源：http://dali.havefunace.top/Article/details/gt2ewytgxat.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2nnnpfita.html

[H01] try / catch 基础
来源：http://dali.yueranfly.top/Article/details/gt2lmkbzmzt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shuidangran.top/Article/details/gt2gokpmwro.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.aibaodan.cn/Article/details/gt2nwdkkytx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gt2wlkphhlq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.quarkkingdee.top/Article/details/gt2oinbxpdv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenlongwang.top/Article/details/gt2kiakyxyi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ybcxt.top/Article/details/gt2edfbsnkh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenlongwang.top/Article/details/gt2lshoxufy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hfpthk.cn/Article/details/gt2dbarcrxb.html

[H02] finally / ensure 收尾
来源：http://dali.svipenyu.cn/Article/details/gt2ipitramp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.aizwys.cn/Article/details/gt2gfhdgrpw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2tyikbphj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gt2ivtfujxs.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2hwtaaowm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gt2yamatssc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.quarkkingdee.top/Article/details/gt2unzxmkau.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2zffsmhpq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gt2nprfxyec.html

[H03] 主动抛出异常
来源：http://dali.yonumen.top/Article/details/gt2eohvrixo.html

Py:   raise ValueError("错误信息")
来源：http://dali.yonumen.top/Article/details/gt2jljnflgb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gt2eicncqnk.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gt2tbgdskyg.html

TS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2mgoqnkge.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gt2icwmefrw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dgxaxgui.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.snrcjt.cn/Article/details/gt2owfgicnl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2zkwhhfoa.html

[H04] 自定义异常类型
来源：http://dali.sysykeji.top/Article/details/gt2keftunth.html

Py:   class MyError(Exception): pass
来源：http://dali.andypj.xyz/Article/details/gt2dvxuvypa.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gt2iusguzlb.html

JS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gt2pdtvxciy.html

TS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gt2hmpfumto.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yvedp.cn/Article/details/gt2gficaeho.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xylfe.cn/Article/details/gt2nnvhrxfu.html

Ruby: class MyError < StandardError; end
来源：http://dali.fengsongda.top/Article/details/gt2uqrpcidc.html

C#:   class MyException : Exception {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2srqhmjik.html

[H05] 捕获特定类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2xcobtnyp.html

Py:   except ValueError as e:
来源：http://dali.meibo888.top/Article/details/gt2yykflpah.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhongyouzk.top/Article/details/gt2njgosxeg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gt2uczdpzlb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tian-w.cn/Article/details/gt2mkuejzgf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj202588.top/Article/details/gt2cprpxbuz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ivvv.top/Article/details/gt2srteccew.html

Ruby: rescue ArgumentError => e
来源：http://dali.shuidangran.top/Article/details/gt2kgpjpzdl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhengqikj.top/Article/details/gt2slzabbaa.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sysykeji.top/Article/details/gt2aywhhjgv.html

Py:   value = d.get("k") or default
来源：http://dali.tianlin.xyz/Article/details/gt2sjddpsec.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yongpay.top/Article/details/gt2khcevpwa.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gt2behguffm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gt2xnmglsye.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xziqi.cn/Article/details/gt2whhrxymf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.smart0.xyz/Article/details/gt2kppseytu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.iojbl.cn/Article/details/gt2jwhnkfbz.html

C#:   obj?.A?.B ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tsgpwvus.html

[H07] 断言
来源：http://dali.zhongyouzk.top/Article/details/gt2pnpovuqh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xwbkxces.html

PHP:  assert($x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2qrdkluql.html

JS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gt2sntiepkq.html

TS:   console.assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gt2smxjdigv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yueranfly.top/Article/details/gt2vmnbwemz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nanxinkj.top/Article/details/gt2sjyabeyi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.iojbl.cn/Article/details/gt2nbgflnjb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gt2nkeaydcf.html

[H08] 获取错误信息与堆栈
来源：http://dali.redwolf501.top/Article/details/gt2jljbljmr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yanxiufei.cn/Article/details/gt2eoeilszi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xinyue.icu/Article/details/gt2kxtvvalh.html

JS:   e.message;  e.stack
来源：http://dali.tian-w.cn/Article/details/gt2cjfftogl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ydzc1.top/Article/details/gt2ogukiscs.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ppjwa.cn/Article/details/gt2kmaxxtyi.html

Go:   err.Error()
来源：http://dali.jianghu66.top/Article/details/gt2wcwsthpn.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangdashe.top/Article/details/gt2zsyfgamz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tanke756.top/Article/details/gt2xavwtshv.html

[H09] 带错误码的异常
来源：http://dali.hywenlv.cn/Article/details/gt2zuluxaye.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.mhx1999.top/Article/details/gt2fupbkhur.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tianlin.xyz/Article/details/gt2yassigvx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dglfhowr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sweek.top/Article/details/gt2vnazzswz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.wangdashe.top/Article/details/gt2dnbegsyv.html


<!-- 参考信息 -->