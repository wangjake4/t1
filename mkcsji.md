代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtaznzgcgz.html

[F06] 删除文件
来源：http://dali.nwbrower.top/Article/details/gtgqnogggc.html

Py:   os.remove("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtnxpzmhjs.html

PHP:  unlink("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gttfbxsyrj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtazeitidg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtlhpiphpi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtpxltrrev.html

Go:   os.Remove("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtcaeogzbv.html

Ruby: File.delete("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtpncehluz.html

C#:   File.Delete("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtwzofeuis.html

[F07] 创建目录（含多级）
来源：http://dali.wangdashe.top/Article/details/gtbckrrexh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xylfe.cn/Article/details/gtzhibopli.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtleimnmxw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigufen.top/Article/details/gtmjjqatio.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guowangkeji.top/Article/details/gttksycmwh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.c1oappe.top/Article/details/gtnlvmcwpx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.andypj.xyz/Article/details/gtduveeola.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ivvv.top/Article/details/gtopdfybrm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gaohongyu789.top/Article/details/gtvfvhkera.html

[F08] 遍历目录
来源：http://dali.tian-w.cn/Article/details/gtvbipxedq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.mhx1999.top/Article/details/gtcxrtjmsj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hfpthk.cn/Article/details/gtjeuuqtfy.html

JS:   fs.readdirSync("dir")
来源：http://dali.hammf.cn/Article/details/gtigzxqlfj.html

TS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gtfhbkrhma.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gtouqtmfpn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.snrcjt.cn/Article/details/gtcgkdmupc.html

Ruby: Dir.children("dir")
来源：http://dali.chenlongwang.top/Article/details/gtniawyhrf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ybcxt.top/Article/details/gtyvbmtcjn.html

[F09] 获取文件大小
来源：http://dali.guowangkeji.top/Article/details/gtjojlmllq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtfbjltrhf.html

PHP:  filesize("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtwyuqzhjr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hfpthk.cn/Article/details/gtzfijomgy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shuidangran.top/Article/details/gtuzsppppq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtyjlyzpxg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dashuyun.cn/Article/details/gtqtnqgbyd.html

Ruby: File.size("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtkmnpmzyg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinqigfzy.top/Article/details/gthbmqxswm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ppjwa.cn/Article/details/gtfidkvqby.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtoxykqvcn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtdfmybcwq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gthtfefqos.html

TS:   path.extname("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtemyzvubz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tanke756.top/Article/details/gtfpexagzo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtxnewwccp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtcylxemrw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtmlnvebsr.html

[F11] 复制与移动文件
来源：http://dali.ppjwa.cn/Article/details/gtdpyvegma.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtggptraqd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinqigufen.top/Article/details/gtptrpkooa.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtnquzqlxa.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtdueegyxw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guannengcc.top/Article/details/gtynhpkpsj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.9152youxi.cn/Article/details/gtmzobcqfx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtcydapaue.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hongshengwenyu.top/Article/details/gthnfwqxbs.html

[F12] CSV 读写
来源：http://dali.hammf.cn/Article/details/gtncxxcdek.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhengqikj.top/Article/details/gtjpkcrjpp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zycfv.cn/Article/details/gtozpbferp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ehwqpu.com/Article/details/gtzlxxjayo.html

TS:   // 同上
来源：http://dali.sufxvd.cn/Article/details/gtuqwfbxqk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.c1oappe.top/Article/details/gtxdkfgyie.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigufen.top/Article/details/gtzbqqhrgk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hysaishi.cn/Article/details/gtvymcmyan.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.iojbl.cn/Article/details/gtmecbivzc.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtyjsabsqy.html

G. 面向对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjqycjnrb.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtryhqfnmp.html

[G01] 定义类
来源：http://dali.jinqigfzy.top/Article/details/gtgnpnsypx.html

Py:   class User: pass
来源：http://dali.shangyingyoupin.top/Article/details/gtmlmevtjc.html

PHP:  class User {}
来源：http://dali.316326.xyz/Article/details/gtlimdesip.html

JS:   class User {}
来源：http://dali.xylfe.cn/Article/details/gtubwovcfa.html

TS:   class User { name: string = ""; }
来源：http://dali.hongshengwenyu.top/Article/details/gterefmyja.html

Java: class User {}
来源：http://dali.redwolf501.top/Article/details/gtgkxvevck.html

Go:   type User struct { Name string }
来源：http://dali.yj20258888.top/Article/details/gtmvjlvicg.html

Ruby: class User; end
来源：http://dali.gogol.net.cn/Article/details/gtlpjqawyb.html

C#:   class User {}
来源：http://dali.yonumen.top/Article/details/gtflaiwjij.html

[G02] 构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gtjcycloyt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.havefunace.top/Article/details/gtiipkcxtg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xziqi.cn/Article/details/gtnoarlxvr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tian-w.cn/Article/details/gtmvhsiadd.html

TS:   constructor(public name: string) {}
来源：http://dali.jyoumei.cn/Article/details/gtrrbkbfuu.html

Java: User(String name) { this.name = name; }
来源：http://dali.guannengcc.top/Article/details/gtyjurqgwn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuanzhike.top/Article/details/gtmzfytygn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ehwqpu.com/Article/details/gtavmyshii.html

C#:   public User(string name) { Name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtazwsrkai.html

[G03] 实例属性
来源：http://dali.fengsongda.top/Article/details/gtjusnufed.html

Py:   self.name = "x"
来源：http://dali.zdqjudy.top/Article/details/gtgbwwyjmh.html

PHP:  public string $name = "x";
来源：http://dali.havefunace.top/Article/details/gtfbipupyj.html

JS:   this.name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtoaulrblp.html

TS:   name: string = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtkevjghjn.html

Java: private String name;
来源：http://dali.shzxlz.cn/Article/details/gtzulnbhoo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj202588.top/Article/details/gtutkrcbrd.html

Ruby: @name = "x"
来源：http://dali.yongpay.top/Article/details/gthbcqfqep.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtpyimpvjo.html

[G04] 定义方法
来源：http://dali.gzhubu.top/Article/details/gtirdcjwsy.html

Py:   def greet(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gtvgrotyeq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gtygwxmikp.html

JS:   greet() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtftjvtlis.html

TS:   greet(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtvfyrqatw.html

Java: String greet() { return name; }
来源：http://dali.yj20258888.top/Article/details/gtwjnwzkin.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gthrsufawf.html

Ruby: def greet; @name; end
来源：http://dali.xylfe.cn/Article/details/gtatavkwrs.html

C#:   public string Greet() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gtbgxfzjgd.html

[G05] 继承
来源：http://dali.dashuyun.cn/Article/details/gtfahfbsyv.html

Py:   class Admin(User): pass
来源：http://dali.chenlongwang.top/Article/details/gthduejmcs.html

PHP:  class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtdgwetbet.html

JS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtejphmujk.html

TS:   class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtzxhnjweo.html

Java: class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gthahuywji.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ehwqpu.com/Article/details/gthgcvcklg.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtlboxnggn.html

C#:   class Admin : User {}
来源：http://dali.redwolf501.top/Article/details/gtcmsiijsg.html

[G06] 重写方法
来源：http://dali.shangyingyoupin.top/Article/details/gtvlbslazh.html

Py:   def greet(self): return "admin"
来源：http://dali.gaohongyu789.top/Article/details/gteuqchedw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtjcmuwrdy.html

JS:   greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtqmhiltri.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gttavvudga.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtnigjarxs.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jianghu66.top/Article/details/gtfzuwtazg.html

Ruby: def greet; "admin"; end
来源：http://dali.chenzaomai.com/Article/details/gtkhuxvygq.html

C#:   public override string Greet() => "admin";
来源：http://dali.smart0.xyz/Article/details/gtydwookdi.html

[G07] 调用父类方法
来源：http://dali.quarkkingdee.top/Article/details/gtvjhhxvyt.html

Py:   super().greet()
来源：http://dali.jiagoushi.top/Article/details/gtunyevogu.html

PHP:  parent::greet();
来源：http://dali.daria6918.cn/Article/details/gtugngpjcg.html

JS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gtnmuurdmt.html

TS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtojfhwljj.html

Java: super.greet();
来源：http://dali.zhengqikj.top/Article/details/gtzqtwtbol.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnxiangtu.top/Article/details/gtkmtfbkpq.html

Ruby: super
来源：http://dali.sweek.top/Article/details/gthdjcqren.html

C#:   base.Greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtbuijfnsm.html

[G08] 静态方法与属性
来源：http://dali.jianghu66.top/Article/details/gtftfxxwgm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hammf.cn/Article/details/gtjdzewjrw.html

PHP:  public static function f() {}
来源：http://dali.yangfankeji.com/Article/details/gteonjvwtw.html

JS:   static f() {}
来源：http://dali.yuxming.cn/Article/details/gtqjmohflc.html

TS:   static f(): void {}
来源：http://dali.redwolf501.top/Article/details/gtvzjkwxqv.html

Java: static void f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpegubugk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guannengcc.top/Article/details/gttjmxuhjw.html

Ruby: def self.f; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfrihfopi.html

C#:   public static void F() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtfggyyozf.html

[G09] 接口 / 抽象类
来源：http://dali.ybcxt.top/Article/details/gtvnswhdja.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.quarkkingdee.top/Article/details/gtzseegtiz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.iojbl.cn/Article/details/gtefvpfarx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xylfe.cn/Article/details/gthxjfndya.html

TS:   interface Shape { area(): number; }
来源：http://dali.yanxiufei.cn/Article/details/gtjxygadhu.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigfzy.top/Article/details/gtpcxudpgt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.meibo888.top/Article/details/gttfbnoksr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yangfankeji.com/Article/details/gtuqprxlqp.html

C#:   interface IShape { double Area(); }
来源：http://dali.fzhhl.top/Article/details/gtukehpdmi.html

[G10] 访问控制
来源：http://dali.jqgfzy.top/Article/details/gtgpvzgnbx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ppjwa.cn/Article/details/gtjfkyfwfu.html

PHP:  public / protected / private
来源：http://dali.yuxming.cn/Article/details/gtpsugeswl.html

JS:   #private 字段；其余公开
来源：http://dali.fzhhl.top/Article/details/gtltysrquu.html

TS:   public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtejweifzn.html

Java: public / protected / private / 默认包级
来源：http://dali.jqgfzy.top/Article/details/gtynpbpche.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.smart0.xyz/Article/details/gtrurxedow.html

Ruby: public / protected / private
来源：http://dali.ybcxt.top/Article/details/gtexjlqosa.html

C#:   public / protected / private / internal
来源：http://dali.fzhhl.top/Article/details/gtxyhjrnck.html

[G11] getter / setter
来源：http://dali.aizwys.cn/Article/details/gtcufzgcsf.html

Py:   @property 与 @x.setter
来源：http://dali.pengpengdd.cyou/Article/details/gtqdfueuda.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtnhacgopu.html

JS:   get name() { return this._name; }
来源：http://dali.yongpay.top/Article/details/gtxwhclick.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gtreuilvvx.html

Java: public String getName() { return name; }
来源：http://dali.sweek.top/Article/details/gtntshtlxk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gttugnnhzs.html

Ruby: attr_accessor :name
来源：http://dali.ivvv.top/Article/details/gtjsqochme.html

C#:   public string Name { get; set; }
来源：http://dali.wangshuangyany.cn/Article/details/gtikcfvusb.html

[G12] 对象转字符串
来源：http://dali.mhx1999.top/Article/details/gtpzdkwbap.html

Py:   def __str__(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gtrqctkiyd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtxpeqtxge.html

JS:   toString() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtpwbzlmjl.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gthokxvpcd.html

Java: @Override public String toString() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gthokabuba.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtstypmjan.html

Ruby: def to_s; @name; end
来源：http://dali.cucudq.cn/Article/details/gtzrsiiuqi.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258.top/Article/details/gtuctkwpcm.html

[G13] 判断对象类型
来源：http://dali.9152youxi.cn/Article/details/gtwcghhuee.html

Py:   isinstance(u, User)
来源：http://dali.yonumen.top/Article/details/gtpdliohpp.html

PHP:  $u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtuvyvrvnr.html

JS:   u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtlnjmyrrr.html

TS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtnscoddej.html

Java: u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtyrbrnycx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sysykeji.top/Article/details/gtfmeufxdh.html

Ruby: u.is_a?(User)
来源：http://dali.hysaishi.cn/Article/details/gtpzffmspw.html

C#:   u is User
来源：http://dali.smart0.xyz/Article/details/gtmfsrfcjg.html

[G14] 数据类 / record
来源：http://dali.gaohongyu789.top/Article/details/gtmjuvyabb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgfzy.top/Article/details/gtrgimutld.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.quarkkingdee.top/Article/details/gtejysfozg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shanyushiyangtech.top/Article/details/gttfybvudk.html

TS:   type User = { name: string; age: number };
来源：http://dali.xinyue.icu/Article/details/gtscojfemu.html

Java: record User(String name, int age) {}
来源：http://dali.zhongyouzk.top/Article/details/gtwqwqwoqn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhixingplan.top/Article/details/gtznqvyvsf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hfpthk.cn/Article/details/gtzwicuinv.html

C#:   record User(string Name, int Age);
来源：http://dali.bjfxy.top/Article/details/gtrooplraj.html

[G15] 枚举
来源：http://dali.gotoacloud.top/Article/details/gtwvfennxh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgufenzy.top/Article/details/gtesbzmlrk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gtdrhvmwve.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenlongwang.top/Article/details/gthfjtjsxo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.andypj.xyz/Article/details/gtfucbyyki.html

Java: enum Color { RED, GREEN }
来源：http://dali.jianghu66.top/Article/details/gtbntnobuh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ppjwa.cn/Article/details/gtwxydwmxq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.havefunace.top/Article/details/gtfxcbifar.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yangfankeji.com/Article/details/gteycxbgpc.html

[G16] 对象转数组 / 字典
来源：http://dali.0kj1m.cn/Article/details/gtlyedmeio.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gzhubu.top/Article/details/gtqmryzjeu.html

PHP:  get_object_vars($obj);
来源：http://dali.ppjwa.cn/Article/details/gtihxgqcpt.html

JS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gtuctzoaky.html

TS:   Object.entries(obj)
来源：http://dali.ppjwa.cn/Article/details/gtpfluvouz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gotoacloud.top/Article/details/gtkuwwhpsx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ehwqpu.com/Article/details/gtimddbffy.html

Ruby: obj.instance_variables
来源：http://dali.jyoumei.cn/Article/details/gtpmtmaxvq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.quarkkingdee.top/Article/details/gteafrbuzf.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtzjvasjqi.html

H. 异常与错误处理
来源：http://dali.shuidangran.top/Article/details/gtiumcdawr.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtmredxyfh.html

[H01] try / catch 基础
来源：http://dali.guowangkeji.top/Article/details/gtckzhkxvo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.wangdashe.top/Article/details/gtzhhebgwn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhixingplan.top/Article/details/gtvquaizko.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gtumomrtik.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gtcjolymnw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttnwpmanb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cashguo.top/Article/details/gtjdsjuvah.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.iojbl.cn/Article/details/gtoorrwubu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnxiangtu.top/Article/details/gthlkuirmk.html

[H02] finally / ensure 收尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gtksljygjs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tanke756.top/Article/details/gtlmwlkjbl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtkhmjzkve.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtenzmeheq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtlstdiwsl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtlyptslxk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guowangkeji.top/Article/details/gtiizkizxj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.haohaochexian.top/Article/details/gtnnlqqlgy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtjybxlrdf.html

[H03] 主动抛出异常
来源：http://dali.cheryme.top/Article/details/gtubtedjgh.html

Py:   raise ValueError("错误信息")
来源：http://dali.cheryme.top/Article/details/gtgabpdrlm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtrrteenrz.html

JS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtqifwavnx.html

TS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtxifqatde.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtcldlktis.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xylfe.cn/Article/details/gtmwgduijv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hammf.cn/Article/details/gtdfbtveuo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtqxyhgbfx.html

[H04] 自定义异常类型
来源：http://dali.shzxlz.cn/Article/details/gtbrlpeklw.html

Py:   class MyError(Exception): pass
来源：http://dali.cheryme.top/Article/details/gthakrnmqb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gtnvmnajgy.html

JS:   class MyError extends Error {}
来源：http://dali.yueranfly.top/Article/details/gtotmowqpz.html

TS:   class MyError extends Error {}
来源：http://dali.tian-w.cn/Article/details/gtnssojgnk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gtoburwjjf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sweek.top/Article/details/gtfojvnguv.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258.top/Article/details/gtqulfxjhh.html

C#:   class MyException : Exception {}
来源：http://dali.jyoumei.cn/Article/details/gtixkxzkqh.html

[H05] 捕获特定类型
来源：http://dali.zycfv.cn/Article/details/gtkfkvdgve.html

Py:   except ValueError as e:
来源：http://dali.bjfxy.top/Article/details/gtmhfyhpoz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.bjfxy.top/Article/details/gtkcvdryjk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgufenzy.top/Article/details/gtrianpkqi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtncxlsdxk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.andypj.xyz/Article/details/gtduekdzuh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenlongwang.top/Article/details/gtrebodzxh.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgufenzy.top/Article/details/gtkztkpagy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowwshabj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xziqi.cn/Article/details/gtqiiobahv.html

Py:   value = d.get("k") or default
来源：http://dali.daria6918.cn/Article/details/gtgpwekyvd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gtmfwvhivb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jyoumei.cn/Article/details/gtbdpvksvx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gtnicicimo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xylfe.cn/Article/details/gtkonzqudd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenlongwang.top/Article/details/gtugbcurov.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhiwuduotai.top/Article/details/gtcpoikpmu.html

C#:   obj?.A?.B ?? default
来源：http://dali.smart0.xyz/Article/details/gtdostivgh.html

[H07] 断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gtolbxcpjf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhongyouzk.top/Article/details/gtaeextfbg.html

PHP:  assert($x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtmsiaoqpy.html

JS:   console.assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gtxruoninw.html

TS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtdbkunuzf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.316326.xyz/Article/details/gtbyaxvmux.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hammf.cn/Article/details/gtkqiyazzv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigfzy.top/Article/details/gtouknioss.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gtlbucwjxq.html

[H08] 获取错误信息与堆栈
来源：http://dali.dianchejie.cn/Article/details/gtxlevbdsm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.kuanghao11.cn/Article/details/gtvqmuiafi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.fzhhl.top/Article/details/gtglhmsmma.html

JS:   e.message;  e.stack
来源：http://dali.aibaodan.cn/Article/details/gtrfktoxxj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yueranfly.top/Article/details/gteqjwtved.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ydzc1.top/Article/details/gtjavcossz.html

Go:   err.Error()
来源：http://dali.9152youxi.cn/Article/details/gtoeneouwv.html

Ruby: e.message;  e.backtrace
来源：http://dali.jianghu66.top/Article/details/gtwlwfodtk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenlongwang.top/Article/details/gtapxgyzfu.html

[H09] 带错误码的异常
来源：http://dali.nanxinkj.top/Article/details/gtljrfqihe.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zdqjudy.top/Article/details/gtxmjsijwq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yvedp.cn/Article/details/gtmuvigkrh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tian-w.cn/Article/details/gtxhgvjhdr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.iojbl.cn/Article/details/gtfepjjimh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.dianchejie.cn/Article/details/gtncjmutjo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.wangshuangyany.cn/Article/details/gtccdgwfuh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xziqi.cn/Article/details/gtvlsizguw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pengpengdd.cyou/Article/details/gtnitciqdl.html

[H10] 资源自动释放
来源：http://dali.cashguo.top/Article/details/gtabmaikwr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shanyushiyangtech.top/Article/details/gthzvyrtez.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shuidangran.top/Article/details/gtuaeqkzek.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gtqobvjnho.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gtovfqehfk.html


<!-- 参考信息 -->