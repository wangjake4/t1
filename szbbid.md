代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sufxvd.cn/Article/details/gt2jtilfzkt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gt2kkgwiccf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gt2sljvtosp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.quarkkingdee.top/Article/details/gt2oblnevvp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhixingplan.top/Article/details/gt2zxgfaefe.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sxryk.cn/Article/details/gt2wrjptnfe.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.9152youxi.cn/Article/details/gt2phfggacc.html

[F08] 遍历目录
来源：http://dali.redwolf501.top/Article/details/gt2ytcchago.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cuwfnuov.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xziqi.cn/Article/details/gt2bovsfvuu.html

JS:   fs.readdirSync("dir")
来源：http://dali.hammf.cn/Article/details/gt2ejymiwjx.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhoulong.xyz/Article/details/gt2ksafrzsa.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gt2uzasnenn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kwvsddhf.html

Ruby: Dir.children("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2esfzxnyr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgfzy.top/Article/details/gt2hayxhimw.html

[F09] 获取文件大小
来源：http://dali.andypj.xyz/Article/details/gt2rtqannwk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2lhpddejy.html

PHP:  filesize("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2badgatsn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2taheyhxa.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gt2jboffgag.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gt2peknvipz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangshuangyany.cn/Article/details/gt2pifdvkzn.html

Ruby: File.size("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2abqrqimn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jiagoushi.top/Article/details/gt2nodinvji.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.daxiang520.top/Article/details/gt2hqtonmxw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2wljtlozh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2wxpdnorm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2layiemav.html

TS:   path.extname("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2dlgjredi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guowangkeji.top/Article/details/gt2quxhlyjb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2ojucpfhq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tobnmdjv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gt2ydfqlwed.html

[F11] 复制与移动文件
来源：http://dali.ybcxt.top/Article/details/gt2lconodiq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xxifsuyv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.iojbl.cn/Article/details/gt2imzlvpel.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gt2kmltvquw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gt2ukocysvn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shzxlz.cn/Article/details/gt2eljenogh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ydzc1.top/Article/details/gt2sywdbnnd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2lcieahgp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jiagoushi.top/Article/details/gt2ofukaebw.html

[F12] CSV 读写
来源：http://dali.nanxuanxn.top/Article/details/gt2durhkljq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xftaolge.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gogol.net.cn/Article/details/gt2ezqpvjup.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cucudq.cn/Article/details/gt2bvcvrbjg.html

TS:   // 同上
来源：http://dali.jinqigufen.top/Article/details/gt2noeufnyt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhiwuduotai.top/Article/details/gt2ljmoihbi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xinyue.icu/Article/details/gt2vaatyfwr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cdnleiting.top/Article/details/gt2xyfigrws.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.pengpengdd.cyou/Article/details/gt2xlctrfyr.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2ckectjfn.html

G. 面向对象
来源：http://dali.pengpengdd.cyou/Article/details/gt2mlrwbewm.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2xnsvpvxg.html

[G01] 定义类
来源：http://dali.guowangkeji.top/Article/details/gt2dynzgmbp.html

Py:   class User: pass
来源：http://dali.yj202588.top/Article/details/gt2nyalloxi.html

PHP:  class User {}
来源：http://dali.snrcjt.cn/Article/details/gt2xylvcixr.html

JS:   class User {}
来源：http://dali.sysykeji.top/Article/details/gt2tmhihmyj.html

TS:   class User { name: string = ""; }
来源：http://dali.havefunace.top/Article/details/gt2krbvfpop.html

Java: class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2oviulgdd.html

Go:   type User struct { Name string }
来源：http://dali.feifeiyinyue.top/Article/details/gt2dmtmdnya.html

Ruby: class User; end
来源：http://dali.jiagoushi.top/Article/details/gt2yhqjpktx.html

C#:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gt2nlsxjqnq.html

[G02] 构造函数
来源：http://dali.fengsongda.top/Article/details/gt2ufaykcoq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xziqi.cn/Article/details/gt2skkwghex.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bnpamxqr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gt2tgxmbhxd.html

TS:   constructor(public name: string) {}
来源：http://dali.yuanzhike.top/Article/details/gt2gnsbbljb.html

Java: User(String name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gt2wkcxtbyt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigfzy.top/Article/details/gt2gjuqksec.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinqigufen.top/Article/details/gt2epjzmhic.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gzhubu.top/Article/details/gt2vjuwkmne.html

[G03] 实例属性
来源：http://dali.nanxuanxn.top/Article/details/gt2sprhuzrl.html

Py:   self.name = "x"
来源：http://dali.haohaochexian.top/Article/details/gt2cnfjmlzp.html

PHP:  public string $name = "x";
来源：http://dali.hysaishi.cn/Article/details/gt2anjgovsk.html

JS:   this.name = "x";
来源：http://dali.sysykeji.top/Article/details/gt2gzpgbwvy.html

TS:   name: string = "x";
来源：http://dali.ydzc1.top/Article/details/gt2obyatpxu.html

Java: private String name;
来源：http://dali.hammf.cn/Article/details/gt2wppvzrmv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jlsjyb.cn/Article/details/gt2ucazjsau.html

Ruby: @name = "x"
来源：http://dali.andypj.xyz/Article/details/gt2wvibboux.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zycfv.cn/Article/details/gt2bcfiokmm.html

[G04] 定义方法
来源：http://dali.jqgfzy.top/Article/details/gt2uvbdhvnf.html

Py:   def greet(self): return self.name
来源：http://dali.cucudq.cn/Article/details/gt2akfkanvy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gt2dfpslgyw.html

JS:   greet() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gt2xaybyvtn.html

TS:   greet(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gt2qqpnqhjw.html

Java: String greet() { return name; }
来源：http://dali.yuxming.cn/Article/details/gt2rqpjrlmf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gt2itxgcawk.html

Ruby: def greet; @name; end
来源：http://dali.vqdsnc.cn/Article/details/gt2jefuvygu.html

C#:   public string Greet() => Name;
来源：http://dali.sysykeji.top/Article/details/gt2akdfzajp.html

[G05] 继承
来源：http://dali.xuetiantiany.cn/Article/details/gt2vvqhxuih.html

Py:   class Admin(User): pass
来源：http://dali.xuetiantiany.cn/Article/details/gt2bkssapwi.html

PHP:  class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2nmytqzhs.html

JS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gt2adyngdjp.html

TS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gt2fydhnfiw.html

Java: class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gt2mzeollyv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aizwys.cn/Article/details/gt2pynjfrsj.html

Ruby: class Admin < User; end
来源：http://dali.pycfn.com/Article/details/gt2rfxemmdh.html

C#:   class Admin : User {}
来源：http://dali.ehwqpu.com/Article/details/gt2rssdnjrx.html

[G06] 重写方法
来源：http://dali.yj20258888.top/Article/details/gt2nhooursb.html

Py:   def greet(self): return "admin"
来源：http://dali.zdqjudy.top/Article/details/gt2rtibeenh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gt2lmvzidze.html

JS:   greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2simudpau.html

TS:   greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gt2aleopssg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gt2yqwysqvy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jyoumei.cn/Article/details/gt2mmiwndwr.html

Ruby: def greet; "admin"; end
来源：http://dali.xziqi.cn/Article/details/gt2feocuphk.html

C#:   public override string Greet() => "admin";
来源：http://dali.ppjwa.cn/Article/details/gt2mkbedlio.html

[G07] 调用父类方法
来源：http://dali.smart0.xyz/Article/details/gt2pnzfttez.html

Py:   super().greet()
来源：http://dali.ivvv.top/Article/details/gt2btdrrsco.html

PHP:  parent::greet();
来源：http://dali.xuetiantiany.cn/Article/details/gt2haeskelk.html

JS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gt2ugxqmiyj.html

TS:   super.greet();
来源：http://dali.sysykeji.top/Article/details/gt2ztfzvoqs.html

Java: super.greet();
来源：http://dali.yj20258888.top/Article/details/gt2flnqqcyc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aibaodan.cn/Article/details/gt2mddxlpst.html

Ruby: super
来源：http://dali.ydzc1.top/Article/details/gt2rnoxcfok.html

C#:   base.Greet();
来源：http://dali.yuxming.cn/Article/details/gt2zhigasby.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gstudzmk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zdqjudy.top/Article/details/gt2vtlgayrp.html

PHP:  public static function f() {}
来源：http://dali.zhoulong.xyz/Article/details/gt2rowwxyjo.html

JS:   static f() {}
来源：http://dali.cdnleiting.top/Article/details/gt2yzpyswqi.html

TS:   static f(): void {}
来源：http://dali.zhengqikj.top/Article/details/gt2iungbsnr.html

Java: static void f() {}
来源：http://dali.haohaochexian.top/Article/details/gt2ecibjrwy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenlongwang.top/Article/details/gt2tnphfhub.html

Ruby: def self.f; end
来源：http://dali.dianchejie.cn/Article/details/gt2tbtgsekr.html

C#:   public static void F() {}
来源：http://dali.sxryk.cn/Article/details/gt2blgdzqsd.html

[G09] 接口 / 抽象类
来源：http://dali.hammf.cn/Article/details/gt2aqnkvrez.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hfpthk.cn/Article/details/gt2ceksbeap.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tanke756.top/Article/details/gt2rizitybi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.svipenyu.cn/Article/details/gt2ayzxxkqw.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnytfto.html

Java: interface Shape { double area(); }
来源：http://dali.sysykeji.top/Article/details/gt2srhexbfj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.havefunace.top/Article/details/gt2chevzssp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnqzz.top/Article/details/gt2jebodnjx.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhixingplan.top/Article/details/gt2gssdumzj.html

[G10] 访问控制
来源：http://dali.sufxvd.cn/Article/details/gt2fnlrszqf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hnxiangtu.top/Article/details/gt2pfkbnnvg.html

PHP:  public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gt2grwbrkno.html

JS:   #private 字段；其余公开
来源：http://dali.sysykeji.top/Article/details/gt2lvgrcqyz.html

TS:   public / protected / private
来源：http://dali.bjfxy.top/Article/details/gt2uczzrxxh.html

Java: public / protected / private / 默认包级
来源：http://dali.quarkkingdee.top/Article/details/gt2kqjiorbm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nanxuanxn.top/Article/details/gt2vswfdcxz.html

Ruby: public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gt2ulffblgv.html

C#:   public / protected / private / internal
来源：http://dali.sxryk.cn/Article/details/gt2qxgibudv.html

[G11] getter / setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gngkwyyn.html

Py:   @property 与 @x.setter
来源：http://dali.ybcxt.top/Article/details/gt2tchyyjmj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wijccldo.html

JS:   get name() { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gt2oeyppajm.html

TS:   get name(): string { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2hmlyfqvh.html

Java: public String getName() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hijvlqvf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gt2fydkmyqc.html

Ruby: attr_accessor :name
来源：http://dali.hysaishi.cn/Article/details/gt2mbrbbhkc.html

C#:   public string Name { get; set; }
来源：http://dali.snrcjt.cn/Article/details/gt2knaaddio.html

[G12] 对象转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2rkirrmhx.html

Py:   def __str__(self): return self.name
来源：http://dali.bjfxy.top/Article/details/gt2jqrujzju.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gt2hfjlgkyd.html

JS:   toString() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gt2ascxbigb.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gt2ooqtbuyj.html

Java: @Override public String toString() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gt2xwfjbtpr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gt2bkurvnsp.html

Ruby: def to_s; @name; end
来源：http://dali.yonumen.top/Article/details/gt2haavhtdy.html

C#:   public override string ToString() => Name;
来源：http://dali.cqqwz.cn/Article/details/gt2veqhhyxw.html

[G13] 判断对象类型
来源：http://dali.ehwqpu.com/Article/details/gt2sykbwdlh.html

Py:   isinstance(u, User)
来源：http://dali.daxiang520.top/Article/details/gt2wkcmuedc.html

PHP:  $u instanceof User
来源：http://dali.shuidangran.top/Article/details/gt2qqdowhgu.html

JS:   u instanceof User
来源：http://dali.sxryk.cn/Article/details/gt2adfgrzty.html

TS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gt2mskysfwe.html

Java: u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sagqlvkt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ydzc1.top/Article/details/gt2yzgrfcpb.html

Ruby: u.is_a?(User)
来源：http://dali.jqgufenzy.top/Article/details/gt2pfzolole.html

C#:   u is User
来源：http://dali.jinqigufen.top/Article/details/gt2afpnnsox.html

[G14] 数据类 / record
来源：http://dali.guannengcc.top/Article/details/gt2uamdrkzo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cdnleiting.top/Article/details/gt2lgtpskms.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.snrcjt.cn/Article/details/gt2xjjxkxwk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yonumen.top/Article/details/gt2pyfrlfcb.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2mytvmdok.html

Java: record User(String name, int age) {}
来源：http://dali.zdqjudy.top/Article/details/gt2zljfwqkq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.vqdsnc.cn/Article/details/gt2zjefjaqc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cdnleiting.top/Article/details/gt2tfjkznyt.html

C#:   record User(string Name, int Age);
来源：http://dali.vqdsnc.cn/Article/details/gt2elvuzixl.html

[G15] 枚举
来源：http://dali.gogol.net.cn/Article/details/gt2fjxtajwu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cheryme.top/Article/details/gt2ufntvgzk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.aizwys.cn/Article/details/gt2nivltkhq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2usqvckoy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cdnleiting.top/Article/details/gt2pxfjswld.html

Java: enum Color { RED, GREEN }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2plbczuho.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.bjfxy.top/Article/details/gt2aijagaul.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhixingplan.top/Article/details/gt2gueeglfi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gt2kitmnkcd.html

[G16] 对象转数组 / 字典
来源：http://dali.smart0.xyz/Article/details/gt2gkfkdfwv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yonumen.top/Article/details/gt2rvulynhe.html

PHP:  get_object_vars($obj);
来源：http://dali.daria6918.cn/Article/details/gt2uegtpclk.html

JS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gt2oqkysrgy.html

TS:   Object.entries(obj)
来源：http://dali.birdmap.top/Article/details/gt2plrqrtac.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj202588.top/Article/details/gt2xzhczlik.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nanxinkj.top/Article/details/gt2nzvrxtcb.html

Ruby: obj.instance_variables
来源：http://dali.jqgfzy.top/Article/details/gt2frxfbchm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sufxvd.cn/Article/details/gt2vrrjgvql.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2hzpkxuwc.html

H. 异常与错误处理
来源：http://dali.mhx1999.top/Article/details/gt2ptmxxenx.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2rlvjpbvn.html

[H01] try / catch 基础
来源：http://dali.nanxuanxn.top/Article/details/gt2embxvhzl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.c1oappe.top/Article/details/gt2loeazeqy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ehwqpu.com/Article/details/gt2hylkesto.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gt2vwkciamf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2pcddsbcs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.mhx1999.top/Article/details/gt2ayjblkci.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jqgfzy.top/Article/details/gt2awrbrzim.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yneknhgn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hfpthk.cn/Article/details/gt2szxovqtq.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigfzy.top/Article/details/gt2fzlujqxq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xziqi.cn/Article/details/gt2ijrycrie.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2iohpzhfw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gt2qbrvyoiw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gt2eqxzjzen.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gt2hmczsupp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gzhubu.top/Article/details/gt2zpagofbk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj20258.top/Article/details/gt2mytkdkzz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ertbakwr.html

[H03] 主动抛出异常
来源：http://dali.jianghu66.top/Article/details/gt2rgajxico.html

Py:   raise ValueError("错误信息")
来源：http://dali.ybcxt.top/Article/details/gt2hilhidwb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gt2clminbgp.html

JS:   throw new Error("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gt2pkdueond.html

TS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2bxzbuzfz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gt2lrbjjvpb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zdqjudy.top/Article/details/gt2atwylhtm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cashguo.top/Article/details/gt2gmobekzs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gt2pdpwgfvd.html

[H04] 自定义异常类型
来源：http://dali.xinyue.icu/Article/details/gt2cwlbzdfu.html

Py:   class MyError(Exception): pass
来源：http://dali.guowangkeji.top/Article/details/gt2hjctwile.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gt2cmvipvnm.html

JS:   class MyError extends Error {}
来源：http://dali.haohaochexian.top/Article/details/gt2nyugnwmt.html

TS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gt2fespvrlr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gt2vuovrjsv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxinkj.top/Article/details/gt2jligtphb.html

Ruby: class MyError < StandardError; end
来源：http://dali.kuanghao11.cn/Article/details/gt2pmviaeiq.html

C#:   class MyException : Exception {}
来源：http://dali.ybcxt.top/Article/details/gt2bgipqoof.html

[H05] 捕获特定类型
来源：http://dali.xinyue.icu/Article/details/gt2lserfhqg.html

Py:   except ValueError as e:
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xugqiakg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.svipenyu.cn/Article/details/gt2tplhpsea.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ybcxt.top/Article/details/gt2zejwnevx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cashguo.top/Article/details/gt2hhbyholn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nanxinkj.top/Article/details/gt2ofcqside.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yonumen.top/Article/details/gt2hyvkbheu.html

Ruby: rescue ArgumentError => e
来源：http://dali.sxryk.cn/Article/details/gt2kcovkjog.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gzhubu.top/Article/details/gt2nsmkgsof.html

[H06] 可选值 / 空值安全访问
来源：http://dali.smart0.xyz/Article/details/gt2jvgqdgnb.html

Py:   value = d.get("k") or default
来源：http://dali.nanxuanxn.top/Article/details/gt2efyotgyq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gt2ahbapbvs.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gt2dvocfuzz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gt2rqgbzmmz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hfpthk.cn/Article/details/gt2tdnidvku.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigfzy.top/Article/details/gt2olmxrqfv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnxiangtu.top/Article/details/gt2zknruznz.html

C#:   obj?.A?.B ?? default
来源：http://dali.ybcxt.top/Article/details/gt2mugndyic.html

[H07] 断言
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tgqimxpd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenlongwang.top/Article/details/gt2qqdsiago.html

PHP:  assert($x > 0);
来源：http://dali.yangfankeji.com/Article/details/gt2xqpyzyil.html

JS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gt2dtrutkei.html

TS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gt2ewrzsgck.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxinkj.top/Article/details/gt2gqvtqwhh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gzhubu.top/Article/details/gt2yiabdzoq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jqgufenzy.top/Article/details/gt2ndoifpmg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gt2pqtjamja.html

[H08] 获取错误信息与堆栈
来源：http://dali.yangfankeji.com/Article/details/gt2pymlfgvu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guannengcc.top/Article/details/gt2qrfgkcxb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.daria6918.cn/Article/details/gt2nfuyfyyh.html

JS:   e.message;  e.stack
来源：http://dali.jqgfzy.top/Article/details/gt2xlxvfcun.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.316326.xyz/Article/details/gt2nhjqsyms.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gogol.net.cn/Article/details/gt2bkpfmgpc.html

Go:   err.Error()
来源：http://dali.sufxvd.cn/Article/details/gt2aymjexhn.html

Ruby: e.message;  e.backtrace
来源：http://dali.xuetiantiany.cn/Article/details/gt2wtgkasve.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cucudq.cn/Article/details/gt2fpsyznfq.html

[H09] 带错误码的异常
来源：http://dali.pycfn.com/Article/details/gt2znfwppqh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cqqwz.cn/Article/details/gt2rzlwwivf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj202588.top/Article/details/gt2cbyvkoqr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.kuanghao11.cn/Article/details/gt2dpykttwd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.meibo888.top/Article/details/gt2kwulqjmo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sysykeji.top/Article/details/gt2chfzthcr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shzxlz.cn/Article/details/gt2qjxnxwae.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.mhx1999.top/Article/details/gt2phzwydir.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.c1oappe.top/Article/details/gt2ikvnferz.html

[H10] 资源自动释放
来源：http://dali.haohaochexian.top/Article/details/gt2dbwwvlsp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sufxvd.cn/Article/details/gt2mpuhhxrf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.meibo888.top/Article/details/gt2zhqddrtx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gt2wrbhgemz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gt2ruskppxg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tianlin.xyz/Article/details/gt2jyhmqllo.html

Go:   defer f.Close()
来源：http://dali.chenzaomai.com/Article/details/gt2osnhxvbc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cucudq.cn/Article/details/gt2wnlxauee.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2rumxefwj.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2muwvmjaq.html

I. 正则表达式
来源：http://dali.c1oappe.top/Article/details/gt2wpoplukt.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2xvgfvoaq.html

[I01] 判断是否匹配
来源：http://dali.zhiwuduotai.top/Article/details/gt2oxrromse.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gt2xevodjjy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gt2mfeqwdsy.html

JS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gt2kznmcsas.html

TS:   /\d+/.test(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2ujrqqmql.html


<!-- 参考信息 -->