代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ndkbnsch.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258888.top/Article/details/gt2fovtctqt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.c1oappe.top/Article/details/gt2qtlqdpvc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgfzy.top/Article/details/gt2bumfkroq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gaohongyu789.top/Article/details/gt2favdpzzy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yuxming.cn/Article/details/gt2nnoepnpt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gotoacloud.top/Article/details/gt2useuemlb.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2exqaiudb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xylfe.cn/Article/details/gt2vsgzyrir.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oimyejip.html

JS:   fs.readdirSync("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gt2fhpcdmae.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gt2qidbqmju.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gt2tvjmibkx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.aizwys.cn/Article/details/gt2jguzunng.html

Ruby: Dir.children("dir")
来源：http://dali.pycfn.com/Article/details/gt2seafqfom.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fzhhl.top/Article/details/gt2mjiqghjz.html

[F09] 获取文件大小
来源：http://dali.sufxvd.cn/Article/details/gt2wvomofmd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2wcdygjyr.html

PHP:  filesize("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2vmjfnhqn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.c1oappe.top/Article/details/gt2jvrfzgcl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.bjfxy.top/Article/details/gt2ulpvjski.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dkugzlji.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ehwqpu.com/Article/details/gt2ehxdbiyr.html

Ruby: File.size("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2bsktrtdp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj20258.top/Article/details/gt2rbepetal.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xylfe.cn/Article/details/gt2kljbitdr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2zzetedar.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2hpznmvgx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gt2lokdcwxj.html

TS:   path.extname("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2dylrpidy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hongshengwenyu.top/Article/details/gt2oasqgecb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2xcbftxns.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2dhgmbbue.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2igwvwjsc.html

[F11] 复制与移动文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2houxuzup.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gt2ykfrkdeu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2waxssefb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gt2rxtojsxk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gt2wuoaerqs.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hfpthk.cn/Article/details/gt2asgabbuz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.andypj.xyz/Article/details/gt2ebijqten.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2igojkrky.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258.top/Article/details/gt2klgnhzds.html

[F12] CSV 读写
来源：http://dali.feifeiyinyue.top/Article/details/gt2arzumdgd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yuanzhike.top/Article/details/gt2xkuwkhuy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.dashuyun.cn/Article/details/gt2xrakujvw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ehwqpu.com/Article/details/gt2ibnrfizq.html

TS:   // 同上
来源：http://dali.cashguo.top/Article/details/gt2ghmwmoee.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.aizwys.cn/Article/details/gt2pqmmkwtu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pycfn.com/Article/details/gt2kopgjccz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pycfn.com/Article/details/gt2ovofvlvp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yanxiufei.cn/Article/details/gt2dbtbblyj.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2avmhvwuj.html

G. 面向对象
来源：http://dali.nanxinkj.top/Article/details/gt2uaswolbn.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2zznezhtk.html

[G01] 定义类
来源：http://dali.gaohongyu789.top/Article/details/gt2sdxkhize.html

Py:   class User: pass
来源：http://dali.xylfe.cn/Article/details/gt2ajoquefg.html

PHP:  class User {}
来源：http://dali.jianghu66.top/Article/details/gt2ijsopmjb.html

JS:   class User {}
来源：http://dali.fengsongda.top/Article/details/gt2qdsnnspz.html

TS:   class User { name: string = ""; }
来源：http://dali.ydzc1.top/Article/details/gt2icsebciq.html

Java: class User {}
来源：http://dali.tanke756.top/Article/details/gt2ixoozskk.html

Go:   type User struct { Name string }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bftbojna.html

Ruby: class User; end
来源：http://dali.sufxvd.cn/Article/details/gt2hlitvpvf.html

C#:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gt2aljlqirv.html

[G02] 构造函数
来源：http://dali.birdmap.top/Article/details/gt2xwplxdsk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.pengpengdd.cyou/Article/details/gt2fbgjasta.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cdnleiting.top/Article/details/gt2waniibpz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gt2jrzrdkpk.html

TS:   constructor(public name: string) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2gbadknnh.html

Java: User(String name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gt2xbnsftjd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ehwqpu.com/Article/details/gt2eqdrqxix.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gaohongyu789.top/Article/details/gt2pblykwgu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aibaodan.cn/Article/details/gt2qyddrbyy.html

[G03] 实例属性
来源：http://dali.jyoumei.cn/Article/details/gt2trecwfln.html

Py:   self.name = "x"
来源：http://dali.yuxming.cn/Article/details/gt2ifeusomq.html

PHP:  public string $name = "x";
来源：http://dali.tian-w.cn/Article/details/gt2cfuxwlio.html

JS:   this.name = "x";
来源：http://dali.redwolf501.top/Article/details/gt2rwzscaho.html

TS:   name: string = "x";
来源：http://dali.yanxiufei.cn/Article/details/gt2qbsdgmwb.html

Java: private String name;
来源：http://dali.nwbrower.top/Article/details/gt2omofntsb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnxiangtu.top/Article/details/gt2kyxwxyts.html

Ruby: @name = "x"
来源：http://dali.tian-w.cn/Article/details/gt2poyavvah.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shzxlz.cn/Article/details/gt2wlbwsqgm.html

[G04] 定义方法
来源：http://dali.yanxiufei.cn/Article/details/gt2cpaxhwgv.html

Py:   def greet(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gt2alongara.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gt2qdflnejz.html

JS:   greet() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gt2pdjwdqgi.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gt2zjdmeyqg.html

Java: String greet() { return name; }
来源：http://dali.daxiang520.top/Article/details/gt2bktayapv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wlrqqcje.html

Ruby: def greet; @name; end
来源：http://dali.yongpay.top/Article/details/gt2njuweuzb.html

C#:   public string Greet() => Name;
来源：http://dali.tian-w.cn/Article/details/gt2ejgbdpoy.html

[G05] 继承
来源：http://dali.snrcjt.cn/Article/details/gt2qmiugcjs.html

Py:   class Admin(User): pass
来源：http://dali.kuanghao11.cn/Article/details/gt2vahctwwf.html

PHP:  class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gt2yfyhsibh.html

JS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kbpjqeta.html

TS:   class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gecwtsxh.html

Java: class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gt2zjifmbyf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj202588.top/Article/details/gt2fghkofkk.html

Ruby: class Admin < User; end
来源：http://dali.nwbrower.top/Article/details/gt2gmwhahet.html

C#:   class Admin : User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cblngpup.html

[G06] 重写方法
来源：http://dali.0kj1m.cn/Article/details/gt2licyumrk.html

Py:   def greet(self): return "admin"
来源：http://dali.jqgfzy.top/Article/details/gt2djurlwki.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gt2ggldcgdj.html

JS:   greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gt2chfsfhvo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gt2ryqxgurj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iihphnce.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ppjwa.cn/Article/details/gt2ovkzrrlg.html

Ruby: def greet; "admin"; end
来源：http://dali.yonumen.top/Article/details/gt2kfutgtzt.html

C#:   public override string Greet() => "admin";
来源：http://dali.cashguo.top/Article/details/gt2ihpfwuaf.html

[G07] 调用父类方法
来源：http://dali.zhengqikj.top/Article/details/gt2jsjydeos.html

Py:   super().greet()
来源：http://dali.hfpthk.cn/Article/details/gt2ttlbakzx.html

PHP:  parent::greet();
来源：http://dali.sysykeji.top/Article/details/gt2islhvhaz.html

JS:   super.greet();
来源：http://dali.zycfv.cn/Article/details/gt2wllirgtn.html

TS:   super.greet();
来源：http://dali.hfpthk.cn/Article/details/gt2lfsoriav.html

Java: super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gt2nymrhsxp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jyoumei.cn/Article/details/gt2lnksmahw.html

Ruby: super
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ecxakrda.html

C#:   base.Greet();
来源：http://dali.sysykeji.top/Article/details/gt2jioawjeq.html

[G08] 静态方法与属性
来源：http://dali.zhiwuduotai.top/Article/details/gt2fnikmmhl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guannengcc.top/Article/details/gt2iiwbxdub.html

PHP:  public static function f() {}
来源：http://dali.yuxming.cn/Article/details/gt2xkztlafr.html

JS:   static f() {}
来源：http://dali.sufxvd.cn/Article/details/gt2zzkotzpm.html

TS:   static f(): void {}
来源：http://dali.hywenlv.cn/Article/details/gt2vhduyipk.html

Java: static void f() {}
来源：http://dali.cashguo.top/Article/details/gt2dlhkgvjn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj202588.top/Article/details/gt2muurfmck.html

Ruby: def self.f; end
来源：http://dali.aibaodan.cn/Article/details/gt2gkjghfol.html

C#:   public static void F() {}
来源：http://dali.yvedp.cn/Article/details/gt2xiwryjsx.html

[G09] 接口 / 抽象类
来源：http://dali.guannengcc.top/Article/details/gt2ifshcjgi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gotoacloud.top/Article/details/gt2tlromryy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnqzz.top/Article/details/gt2uyvphvka.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daria6918.cn/Article/details/gt2krltczlv.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangdashe.top/Article/details/gt2wttftzia.html

Java: interface Shape { double area(); }
来源：http://dali.ybcxt.top/Article/details/gt2openkbmw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.snrcjt.cn/Article/details/gt2tvhofcww.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xylfe.cn/Article/details/gt2vgsttqqc.html

C#:   interface IShape { double Area(); }
来源：http://dali.smart0.xyz/Article/details/gt2gprpiavk.html

[G10] 访问控制
来源：http://dali.xylfe.cn/Article/details/gt2gilrfvcl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zycfv.cn/Article/details/gt2xwzpdgwt.html

PHP:  public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gt2pqjmcpfv.html

JS:   #private 字段；其余公开
来源：http://dali.cheryme.top/Article/details/gt2roncapyr.html

TS:   public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gt2ouzrycrc.html

Java: public / protected / private / 默认包级
来源：http://dali.c1oappe.top/Article/details/gt2fddacyvw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zycfv.cn/Article/details/gt2gjuqtsrm.html

Ruby: public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gt2pvgyopje.html

C#:   public / protected / private / internal
来源：http://dali.tian-w.cn/Article/details/gt2egqopepz.html

[G11] getter / setter
来源：http://dali.yvedp.cn/Article/details/gt2garxwewl.html

Py:   @property 与 @x.setter
来源：http://dali.yj202588.top/Article/details/gt2niwngmwf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gt2jglhtsoe.html

JS:   get name() { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xcnrtkhp.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcmvfaw.html

Java: public String getName() { return name; }
来源：http://dali.pycfn.com/Article/details/gt2gketgsqg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gt2gcbmbwmd.html

Ruby: attr_accessor :name
来源：http://dali.iojbl.cn/Article/details/gt2wdevkfpr.html

C#:   public string Name { get; set; }
来源：http://dali.aibaodan.cn/Article/details/gt2ndyshgft.html

[G12] 对象转字符串
来源：http://dali.yangfankeji.com/Article/details/gt2cqcpeyxe.html

Py:   def __str__(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gt2rjbwzfic.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2pmfmlnlf.html

JS:   toString() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gt2zrareshn.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gt2mewwfttl.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gt2bbkouduu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gt2knmjjgog.html

Ruby: def to_s; @name; end
来源：http://dali.gogol.net.cn/Article/details/gt2xlwpavul.html

C#:   public override string ToString() => Name;
来源：http://dali.yj202588.top/Article/details/gt2vsopzxeg.html

[G13] 判断对象类型
来源：http://dali.sysykeji.top/Article/details/gt2urakffvy.html

Py:   isinstance(u, User)
来源：http://dali.wangdashe.top/Article/details/gt2ynqxmfnd.html

PHP:  $u instanceof User
来源：http://dali.tanke756.top/Article/details/gt2mfwoptxa.html

JS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gt2ytsqqlok.html

TS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gt2oyrdcxui.html

Java: u instanceof User
来源：http://dali.pycfn.com/Article/details/gt2vcztkyya.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.iojbl.cn/Article/details/gt2nbkoanub.html

Ruby: u.is_a?(User)
来源：http://dali.quarkkingdee.top/Article/details/gt2hykxpnoh.html

C#:   u is User
来源：http://dali.shzxlz.cn/Article/details/gt2lfzqvruy.html

[G14] 数据类 / record
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sntigjrk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tianlin.xyz/Article/details/gt2lasnybed.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhengqikj.top/Article/details/gt2oefdumxa.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hnqzz.top/Article/details/gt2kkabmrzs.html

TS:   type User = { name: string; age: number };
来源：http://dali.xylfe.cn/Article/details/gt2eobjorvc.html

Java: record User(String name, int age) {}
来源：http://dali.xinyue.icu/Article/details/gt2kioxljup.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shzxlz.cn/Article/details/gt2xrtszmgf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.dianchejie.cn/Article/details/gt2qqrvulqa.html

C#:   record User(string Name, int Age);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vxtasjyf.html

[G15] 枚举
来源：http://dali.yvedp.cn/Article/details/gt2bkhqoqzh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinqigfzy.top/Article/details/gt2lhynavyn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tianlin.xyz/Article/details/gt2fovmcuss.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gzhubu.top/Article/details/gt2fnbaojbs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gt2oxwapayg.html

Java: enum Color { RED, GREEN }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fvwmmlrl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guannengcc.top/Article/details/gt2agvzghcn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.havefunace.top/Article/details/gt2lrnzzmwo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yxiqnoja.html

[G16] 对象转数组 / 字典
来源：http://dali.xuetiantiany.cn/Article/details/gt2arhxprde.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nwbrower.top/Article/details/gt2ciydnlmu.html

PHP:  get_object_vars($obj);
来源：http://dali.xinyue.icu/Article/details/gt2empxkrwi.html

JS:   Object.entries(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2kzcsejwb.html

TS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2tsxpoxnz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigfzy.top/Article/details/gt2ygqzrrxt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinqigfzy.top/Article/details/gt2pjkaznvz.html

Ruby: obj.instance_variables
来源：http://dali.jianghu66.top/Article/details/gt2uhfllybs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gt2awfxizik.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2zipygxrt.html

H. 异常与错误处理
来源：http://dali.kuanghao11.cn/Article/details/gt2fbneodgd.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2geyalrvu.html

[H01] try / catch 基础
来源：http://dali.jyoumei.cn/Article/details/gt2clnrasxm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aiknbccr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2fzcharej.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gt2nttmdoog.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gt2octesfgt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yangfankeji.com/Article/details/gt2dxnpuovx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangdashe.top/Article/details/gt2kywpvhdi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gaohongyu789.top/Article/details/gt2ohwxcyxg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.vqdsnc.cn/Article/details/gt2vvxnyucz.html

[H02] finally / ensure 收尾
来源：http://dali.xziqi.cn/Article/details/gt2uanbsouq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.svipenyu.cn/Article/details/gt2nfjjktok.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gt2hvqoanyq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gt2awbuzrpu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gt2ecptxxxb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gt2gnaplqru.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgufenzy.top/Article/details/gt2otvwsjoc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yarjspks.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gt2nhwsbooj.html

[H03] 主动抛出异常
来源：http://dali.yonumen.top/Article/details/gt2mthvwujx.html

Py:   raise ValueError("错误信息")
来源：http://dali.0kj1m.cn/Article/details/gt2lgalsmwt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gt2vbcieuln.html

JS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gt2vleqtyfv.html

TS:   throw new Error("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fnxdggxe.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2tneixhlj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gaohongyu789.top/Article/details/gt2yajcxuum.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xylfe.cn/Article/details/gt2uitzctlq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gt2rmmdoahf.html

[H04] 自定义异常类型
来源：http://dali.cdnleiting.top/Article/details/gt2qqypsfcj.html

Py:   class MyError(Exception): pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eyzrywho.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gt2raeptgpl.html

JS:   class MyError extends Error {}
来源：http://dali.0kj1m.cn/Article/details/gt2hrdpoppr.html

TS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gt2djlywegt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gt2eaisxyti.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zycfv.cn/Article/details/gt2zkrercog.html

Ruby: class MyError < StandardError; end
来源：http://dali.yongpay.top/Article/details/gt2xeqcgzxc.html

C#:   class MyException : Exception {}
来源：http://dali.yueranfly.top/Article/details/gt2ftounzkz.html

[H05] 捕获特定类型
来源：http://dali.daria6918.cn/Article/details/gt2czqdtghz.html

Py:   except ValueError as e:
来源：http://dali.tanke756.top/Article/details/gt2opcmhrry.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gotoacloud.top/Article/details/gt2ukrqqnkk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gt2tiapwmll.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gt2ikgffmrf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2pxgpyhih.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jiagoushi.top/Article/details/gt2viybuprl.html

Ruby: rescue ArgumentError => e
来源：http://dali.xinyue.icu/Article/details/gt2gbutmeli.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yangfankeji.com/Article/details/gt2iflrsekk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhongyouzk.top/Article/details/gt2rwdgjwrz.html

Py:   value = d.get("k") or default
来源：http://dali.shuidangran.top/Article/details/gt2wuhbguri.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.havefunace.top/Article/details/gt2rhukerkr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gt2maiqnyao.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gt2cpztiiyn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tianlin.xyz/Article/details/gt2dxzjqbai.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhongyouzk.top/Article/details/gt2mundeqie.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zouonjwj.html

C#:   obj?.A?.B ?? default
来源：http://dali.xinyue.icu/Article/details/gt2jpehbzcn.html

[H07] 断言
来源：http://dali.xuetiantiany.cn/Article/details/gt2yeftnzup.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mefhtxzg.html

PHP:  assert($x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2gqxosdog.html

JS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qhfqnzto.html

TS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gt2bsigykgz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.pengpengdd.cyou/Article/details/gt2wgcbufpa.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.haohaochexian.top/Article/details/gt2momyqjct.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.c1oappe.top/Article/details/gt2fttqzwnn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vnvxcprw.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangdashe.top/Article/details/gt2sbocshxj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.vqdsnc.cn/Article/details/gt2hstpeuxb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hywenlv.cn/Article/details/gt2ygnopxyj.html

JS:   e.message;  e.stack
来源：http://dali.zycfv.cn/Article/details/gt2alszkmjz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ppjwa.cn/Article/details/gt2mwngayyn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yonumen.top/Article/details/gt2szqhvlxh.html

Go:   err.Error()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ibiwysiw.html

Ruby: e.message;  e.backtrace
来源：http://dali.birdmap.top/Article/details/gt2yfpbbjjs.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ejluwiuu.html

[H09] 带错误码的异常
来源：http://dali.jyoumei.cn/Article/details/gt2jlrpttvj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangshuangyany.cn/Article/details/gt2cpltwheb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ehwqpu.com/Article/details/gt2uautrbgq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aibaodan.cn/Article/details/gt2yahuamei.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.9152youxi.cn/Article/details/gt2lahumdxo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj20258.top/Article/details/gt2qdqzzssm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yueranfly.top/Article/details/gt2fzlmiyzu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tian-w.cn/Article/details/gt2nslzpjmd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.quarkkingdee.top/Article/details/gt2ixzfamxk.html

[H10] 资源自动释放
来源：http://dali.sxryk.cn/Article/details/gt2hagagtul.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.vqdsnc.cn/Article/details/gt2rrifozbp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zdqjudy.top/Article/details/gt2czfujgrc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gt2yklfivml.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gt2rlgsllce.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gogol.net.cn/Article/details/gt2rvgtukcp.html

Go:   defer f.Close()
来源：http://dali.chenlongwang.top/Article/details/gt2nhsrwgco.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cucudq.cn/Article/details/gt2ddgnmzzd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2xzfqjgcj.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2erzeuxtn.html

I. 正则表达式
来源：http://dali.ehwqpu.com/Article/details/gt2eshcmibb.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2bwafojow.html

[I01] 判断是否匹配
来源：http://dali.havefunace.top/Article/details/gt2zjocqemc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shuidangran.top/Article/details/gt2swyeijgt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2drfewrlq.html

JS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gt2dusweazu.html

TS:   /\d+/.test(s)
来源：http://dali.sufxvd.cn/Article/details/gt2zcpuxjyk.html


<!-- 参考信息 -->