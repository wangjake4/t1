代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cashguo.top/Article/details/gt2pyxitisg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.feifeiyinyue.top/Article/details/gt2qzdybhwh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.quarkkingdee.top/Article/details/gt2pethoewj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cheryme.top/Article/details/gt2vncclyxs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cdnleiting.top/Article/details/gt2pwtnnwqb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sweek.top/Article/details/gt2rnzhxesf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenjidiqi.icu/Article/details/gt2itllslqa.html

[F08] 遍历目录
来源：http://dali.zhixingplan.top/Article/details/gt2fxplcyii.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zycfv.cn/Article/details/gt2azcphbcv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ppjwa.cn/Article/details/gt2bwwerwmh.html

JS:   fs.readdirSync("dir")
来源：http://dali.vqdsnc.cn/Article/details/gt2fgaoxpgi.html

TS:   fs.readdirSync("dir")
来源：http://dali.yonumen.top/Article/details/gt2jdgikjbn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dashuyun.cn/Article/details/gt2raddgqzx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhixingplan.top/Article/details/gt2qtgceydu.html

Ruby: Dir.children("dir")
来源：http://dali.birdmap.top/Article/details/gt2koapypuo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cdnleiting.top/Article/details/gt2oegwklpw.html

[F09] 获取文件大小
来源：http://dali.guowangkeji.top/Article/details/gt2qcpmjfcr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vgqfpikx.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yieiepkc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gt2yhzsvipq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxuanxn.top/Article/details/gt2bykqhpcg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gt2dzfknklk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cdnleiting.top/Article/details/gt2lxhzuieo.html

Ruby: File.size("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2ilryburk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.aibaodan.cn/Article/details/gt2xikjvawj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuetiantiany.cn/Article/details/gt2qndqwbee.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2wujyarac.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2qkawfwsg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2dywmlnbx.html

TS:   path.extname("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2yfxmcaux.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zdqjudy.top/Article/details/gt2cydsreje.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gt2yohjjeyv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2ylegowal.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2huqcdfug.html

[F11] 复制与移动文件
来源：http://dali.zhengqikj.top/Article/details/gt2nmoqvppx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2ewpikrkn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2egphvcvm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gt2ybdhmemb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkopzkur.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nwbrower.top/Article/details/gt2oiwandeu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mhxowchg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gt2shivpmma.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.meibo888.top/Article/details/gt2cfxszufb.html

[F12] CSV 读写
来源：http://dali.iojbl.cn/Article/details/gt2qnzsqoyk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tanke756.top/Article/details/gt2qoognhgi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.feifeiyinyue.top/Article/details/gt2niekzmzc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhengqikj.top/Article/details/gt2upapuxbn.html

TS:   // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gt2muycnamb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gaohongyu789.top/Article/details/gt2swxmsafb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sweek.top/Article/details/gt2wwxctjeh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dianchejie.cn/Article/details/gt2ffwtrrqk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.aizwys.cn/Article/details/gt2ysghdiiu.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2gdrhreoi.html

G. 面向对象
来源：http://dali.zhongyouzk.top/Article/details/gt2hdasrzkx.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2egttegrj.html

[G01] 定义类
来源：http://dali.jlsjyb.cn/Article/details/gt2kzbosxfs.html

Py:   class User: pass
来源：http://dali.sysykeji.top/Article/details/gt2rftlyyvj.html

PHP:  class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qggtscmr.html

JS:   class User {}
来源：http://dali.pycfn.com/Article/details/gt2uvockele.html

TS:   class User { name: string = ""; }
来源：http://dali.jyoumei.cn/Article/details/gt2fkyymygz.html

Java: class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2cwrkjqmi.html

Go:   type User struct { Name string }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fgdxqdml.html

Ruby: class User; end
来源：http://dali.guannengcc.top/Article/details/gt2hdttdldy.html

C#:   class User {}
来源：http://dali.daxiang520.top/Article/details/gt2jyuozbzy.html

[G02] 构造函数
来源：http://dali.jianghu66.top/Article/details/gt2khmatqqk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.feifeiyinyue.top/Article/details/gt2ubfcbdob.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuanzx.com/Article/details/gt2ufecdpab.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2dajlirju.html

TS:   constructor(public name: string) {}
来源：http://dali.hywenlv.cn/Article/details/gt2axsqhqwe.html

Java: User(String name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gt2agwbamwi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xylfe.cn/Article/details/gt2gftayosz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xinyue.icu/Article/details/gt2zudbakbm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guowangkeji.top/Article/details/gt2pfxengni.html

[G03] 实例属性
来源：http://dali.shangyingyoupin.top/Article/details/gt2bejlfxph.html

Py:   self.name = "x"
来源：http://dali.yvedp.cn/Article/details/gt2mnqqtage.html

PHP:  public string $name = "x";
来源：http://dali.gzhubu.top/Article/details/gt2ullpngye.html

JS:   this.name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gt2obhakimd.html

TS:   name: string = "x";
来源：http://dali.jyoumei.cn/Article/details/gt2pzttkgjr.html

Java: private String name;
来源：http://dali.jiagoushi.top/Article/details/gt2qesipzgo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.guannengcc.top/Article/details/gt2gxphhplj.html

Ruby: @name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gt2dnkhzvox.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dashuyun.cn/Article/details/gt2hlnmsfmu.html

[G04] 定义方法
来源：http://dali.redwolf501.top/Article/details/gt2jkbdpniy.html

Py:   def greet(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gt2kpwqjxfa.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gt2rnvesgpw.html

JS:   greet() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2jttryhpl.html

TS:   greet(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gt2domqcoou.html

Java: String greet() { return name; }
来源：http://dali.ybcxt.top/Article/details/gt2qcttugin.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gt2cgchuazz.html

Ruby: def greet; @name; end
来源：http://dali.pycfn.com/Article/details/gt2nsygcnhm.html

C#:   public string Greet() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ekyhplwi.html

[G05] 继承
来源：http://dali.yangfankeji.com/Article/details/gt2sylxfjcl.html

Py:   class Admin(User): pass
来源：http://dali.yj20258.top/Article/details/gt2feifyiyx.html

PHP:  class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2ktqclyfk.html

JS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gt2hetepamu.html

TS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gt2hkrikebg.html

Java: class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2visptiel.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuanzx.com/Article/details/gt2pzgfghye.html

Ruby: class Admin < User; end
来源：http://dali.yangfankeji.com/Article/details/gt2onwfwvii.html

C#:   class Admin : User {}
来源：http://dali.xuanzx.com/Article/details/gt2eogzsubt.html

[G06] 重写方法
来源：http://dali.zhixingplan.top/Article/details/gt2lxijgcvq.html

Py:   def greet(self): return "admin"
来源：http://dali.havefunace.top/Article/details/gt2mwlfxbmx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gt2eduwzqsf.html

JS:   greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gt2jcbdlvuu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gt2mhkhmedm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qcwddeig.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vvqnekfn.html

Ruby: def greet; "admin"; end
来源：http://dali.yj202588.top/Article/details/gt2pjpradvx.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenlongwang.top/Article/details/gt2pfbhvlep.html

[G07] 调用父类方法
来源：http://dali.yonumen.top/Article/details/gt2zrsbselt.html

Py:   super().greet()
来源：http://dali.xinyue.icu/Article/details/gt2evppvwob.html

PHP:  parent::greet();
来源：http://dali.hfpthk.cn/Article/details/gt2jdbjuwru.html

JS:   super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gt2lcxdofgs.html

TS:   super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gt2iezhdknj.html

Java: super.greet();
来源：http://dali.tianlin.xyz/Article/details/gt2rkdvhjyt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hysaishi.cn/Article/details/gt2iozgsoxt.html

Ruby: super
来源：http://dali.pengpengdd.cyou/Article/details/gt2ihjblarp.html

C#:   base.Greet();
来源：http://dali.aizwys.cn/Article/details/gt2lpgyplca.html

[G08] 静态方法与属性
来源：http://dali.shuidangran.top/Article/details/gt2ltmizrnj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cqqwz.cn/Article/details/gt2ichoqtlr.html

PHP:  public static function f() {}
来源：http://dali.gotoacloud.top/Article/details/gt2wdfduzhq.html

JS:   static f() {}
来源：http://dali.nanxinkj.top/Article/details/gt2zjaptrrw.html

TS:   static f(): void {}
来源：http://dali.316326.xyz/Article/details/gt2ecwdtxzo.html

Java: static void f() {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ivgheuag.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jlsjyb.cn/Article/details/gt2psudcvdk.html

Ruby: def self.f; end
来源：http://dali.9152youxi.cn/Article/details/gt2itywabnx.html

C#:   public static void F() {}
来源：http://dali.nanxuanxn.top/Article/details/gt2oymylmzc.html

[G09] 接口 / 抽象类
来源：http://dali.jiagoushi.top/Article/details/gt2wxvasgsb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ehwqpu.com/Article/details/gt2oltqqwat.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.redwolf501.top/Article/details/gt2cckmvtqf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jiagoushi.top/Article/details/gt2yszskner.html

TS:   interface Shape { area(): number; }
来源：http://dali.aizwys.cn/Article/details/gt2gmbohkwe.html

Java: interface Shape { double area(); }
来源：http://dali.redwolf501.top/Article/details/gt2nlvywocv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.bjfxy.top/Article/details/gt2okoxisaz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cashguo.top/Article/details/gt2kzhsdnvb.html

C#:   interface IShape { double Area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2umizpzpk.html

[G10] 访问控制
来源：http://dali.aizwys.cn/Article/details/gt2jetpixyw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenlongwang.top/Article/details/gt2ephrkskq.html

PHP:  public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gt2bixfskjv.html

JS:   #private 字段；其余公开
来源：http://dali.guannengcc.top/Article/details/gt2tnubzsas.html

TS:   public / protected / private
来源：http://dali.sysykeji.top/Article/details/gt2nlypaiul.html

Java: public / protected / private / 默认包级
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pbotlrvx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aibaodan.cn/Article/details/gt2wsktjwzc.html

Ruby: public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gt2arwtaoms.html

C#:   public / protected / private / internal
来源：http://dali.sysykeji.top/Article/details/gt2oxicugfb.html

[G11] getter / setter
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ebfqytli.html

Py:   @property 与 @x.setter
来源：http://dali.cheryme.top/Article/details/gt2heulwrom.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gt2gtnbotuo.html

JS:   get name() { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gt2yxbqlnov.html

TS:   get name(): string { return this._name; }
来源：http://dali.nwbrower.top/Article/details/gt2rtlkzlse.html

Java: public String getName() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2iyzgaydm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gt2aoxrwktk.html

Ruby: attr_accessor :name
来源：http://dali.iojbl.cn/Article/details/gt2buffhlde.html

C#:   public string Name { get; set; }
来源：http://dali.snrcjt.cn/Article/details/gt2iloqkehx.html

[G12] 对象转字符串
来源：http://dali.birdmap.top/Article/details/gt2zcrckfcz.html

Py:   def __str__(self): return self.name
来源：http://dali.pycfn.com/Article/details/gt2hnmpgpsi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gt2khgjyaki.html

JS:   toString() { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ehquthfy.html

TS:   toString(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gt2msbduwef.html

Java: @Override public String toString() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jhuwtjjn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gt2kcvwjqko.html

Ruby: def to_s; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gt2cgiiikni.html

C#:   public override string ToString() => Name;
来源：http://dali.zhengqikj.top/Article/details/gt2wdqzsfja.html

[G13] 判断对象类型
来源：http://dali.sweek.top/Article/details/gt2flnshasc.html

Py:   isinstance(u, User)
来源：http://dali.tanke756.top/Article/details/gt2eejmtnde.html

PHP:  $u instanceof User
来源：http://dali.hnqzz.top/Article/details/gt2ijrxfkyc.html

JS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gt2cxeyhyna.html

TS:   u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gt2qvmjbgto.html

Java: u instanceof User
来源：http://dali.yj20258.top/Article/details/gt2dharfwlz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jlsjyb.cn/Article/details/gt2qcfxspui.html

Ruby: u.is_a?(User)
来源：http://dali.cashguo.top/Article/details/gt2zkucynci.html

C#:   u is User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2feebbbgk.html

[G14] 数据类 / record
来源：http://dali.redwolf501.top/Article/details/gt2tnxfzmjd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yanxiufei.cn/Article/details/gt2rurjnwpn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnxiangtu.top/Article/details/gt2wxhwpmhq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sweek.top/Article/details/gt2fmrkfqsn.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj20258.top/Article/details/gt2ccejuksv.html

Java: record User(String name, int age) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2egnkeldf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sweek.top/Article/details/gt2rzlcgcjc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.mhx1999.top/Article/details/gt2dsmynbud.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxinkj.top/Article/details/gt2xqvnlzlr.html

[G15] 枚举
来源：http://dali.guannengcc.top/Article/details/gt2vkqwdquo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guowangkeji.top/Article/details/gt2wjemyzcy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yongpay.top/Article/details/gt2htfiiape.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.aizwys.cn/Article/details/gt2wotitkii.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yueranfly.top/Article/details/gt2guevflja.html

Java: enum Color { RED, GREEN }
来源：http://dali.xylfe.cn/Article/details/gt2qfqmqvwh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xussnucl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ybcxt.top/Article/details/gt2fnsbpntf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.haohaochexian.top/Article/details/gt2dzbemrhn.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258888.top/Article/details/gt2fbdhberu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigfzy.top/Article/details/gt2bgwiyfln.html

PHP:  get_object_vars($obj);
来源：http://dali.meibo888.top/Article/details/gt2cqseqjpe.html

JS:   Object.entries(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jksrabxx.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uevpubun.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ybcxt.top/Article/details/gt2akrzizer.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tian-w.cn/Article/details/gt2qzvxiyxr.html

Ruby: obj.instance_variables
来源：http://dali.yuxming.cn/Article/details/gt2trxbbwsa.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvgmpio.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2mvysgime.html

H. 异常与错误处理
来源：http://dali.hammf.cn/Article/details/gt2koaqmxev.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2jliuixmi.html

[H01] try / catch 基础
来源：http://dali.daxiang520.top/Article/details/gt2rgzzlfih.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hcqjclfj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yueranfly.top/Article/details/gt2oztsigee.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gt2nazaxjpw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daria6918.cn/Article/details/gt2kgjdjwia.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.dianchejie.cn/Article/details/gt2jtrwbljl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.guowangkeji.top/Article/details/gt2xkpbvsgz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hywenlv.cn/Article/details/gt2wxsmombu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2dhzmgwmz.html

[H02] finally / ensure 收尾
来源：http://dali.gogol.net.cn/Article/details/gt2dmvvsnxo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jyoumei.cn/Article/details/gt2uvwyixgs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gt2aytgigdx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gt2sjsmlgwf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gt2rqaqkymp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2rsvbisyw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ppjwa.cn/Article/details/gt2ondjeyfe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cheryme.top/Article/details/gt2tiypwkyt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gt2yzymxboe.html

[H03] 主动抛出异常
来源：http://dali.dianchejie.cn/Article/details/gt2ggikfoes.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinqigfzy.top/Article/details/gt2hsyasqxp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gt2lvmveglp.html

JS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gt2yummwdra.html

TS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gt2hhhzmanp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tzanakpi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258888.top/Article/details/gt2wcuhlnac.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenjidiqi.icu/Article/details/gt2gqpmfgnl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gt2fzhmvoxc.html

[H04] 自定义异常类型
来源：http://dali.xinyue.icu/Article/details/gt2uetiuysi.html

Py:   class MyError(Exception): pass
来源：http://dali.aizwys.cn/Article/details/gt2jyepdbgk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dianchejie.cn/Article/details/gt2igtiskco.html

JS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gt2ctmohvmg.html

TS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gt2atzvonpi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gt2estvpruw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guowangkeji.top/Article/details/gt2kcwemtea.html

Ruby: class MyError < StandardError; end
来源：http://dali.tianlin.xyz/Article/details/gt2xtzxqaxu.html

C#:   class MyException : Exception {}
来源：http://dali.zhengqikj.top/Article/details/gt2ofxwwxam.html

[H05] 捕获特定类型
来源：http://dali.quarkkingdee.top/Article/details/gt2mildigaf.html

Py:   except ValueError as e:
来源：http://dali.shzxlz.cn/Article/details/gt2yljglore.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2htbimgoe.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gt2fcgtiafm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.c1oappe.top/Article/details/gt2vdoppyst.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2ntglosze.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.iojbl.cn/Article/details/gt2ttturkmt.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangshuangyany.cn/Article/details/gt2mrzpocgn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2bfjisyje.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ehwqpu.com/Article/details/gt2jqbvfhbg.html

Py:   value = d.get("k") or default
来源：http://dali.hnxiangtu.top/Article/details/gt2ednzlooo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.aizwys.cn/Article/details/gt2hkqguclr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gt2jnsohejx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxuanxn.top/Article/details/gt2tpkcekci.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gzhubu.top/Article/details/gt2ddbesnwt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yongpay.top/Article/details/gt2dqwhriym.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ozdrksta.html

C#:   obj?.A?.B ?? default
来源：http://dali.hysaishi.cn/Article/details/gt2nqrnyfwj.html

[H07] 断言
来源：http://dali.gaohongyu789.top/Article/details/gt2lbexiros.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daria6918.cn/Article/details/gt2fhyocaqq.html

PHP:  assert($x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zwrcwfth.html

JS:   console.assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gt2vyckjukr.html

TS:   console.assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gt2qwsffnlh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yvedp.cn/Article/details/gt2vrqnthcl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mdsbxzdn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigufen.top/Article/details/gt2dgxuffik.html

C#:   Debug.Assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2oglrfkel.html

[H08] 获取错误信息与堆栈
来源：http://dali.yanxiufei.cn/Article/details/gt2fiwyhwiu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ybcxt.top/Article/details/gt2oonndvwj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zntbbxwd.html

JS:   e.message;  e.stack
来源：http://dali.9152youxi.cn/Article/details/gt2eocxdiyc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cqqwz.cn/Article/details/gt2jkezzzrw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cheryme.top/Article/details/gt2ifiwhnqg.html

Go:   err.Error()
来源：http://dali.hfpthk.cn/Article/details/gt2ztymhtrk.html

Ruby: e.message;  e.backtrace
来源：http://dali.tian-w.cn/Article/details/gt2ywsmkhef.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xziqi.cn/Article/details/gt2olmsbubu.html

[H09] 带错误码的异常
来源：http://dali.hnxiangtu.top/Article/details/gt2irzqimxj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pengpengdd.cyou/Article/details/gt2bxbjmvns.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zdqjudy.top/Article/details/gt2sxrhffzr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tian-w.cn/Article/details/gt2cxeprcvy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.guannengcc.top/Article/details/gt2kxpjjsyf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sufxvd.cn/Article/details/gt2eaxqzqkq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yimgpfei.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zhrmhxqo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zycfv.cn/Article/details/gt2rruwgpsj.html

[H10] 资源自动释放
来源：http://dali.smart0.xyz/Article/details/gt2tffgcwlo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zywspyas.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yonumen.top/Article/details/gt2tovqtrll.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gotoacloud.top/Article/details/gt2nobpoblu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gt2rbqjvxiz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2shcirhde.html

Go:   defer f.Close()
来源：http://dali.yj20258.top/Article/details/gt2infairjv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tianlin.xyz/Article/details/gt2scqogvqi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2kgyizbaq.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2dalnrcoa.html

I. 正则表达式
来源：http://dali.ppjwa.cn/Article/details/gt2ckizlwjj.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2ioizkmyc.html

[I01] 判断是否匹配
来源：http://dali.guannengcc.top/Article/details/gt2ypyzxzhw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gt2julfqgem.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.birdmap.top/Article/details/gt2jyhofiib.html

JS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gt2jtoxnjyy.html

TS:   /\d+/.test(s)
来源：http://dali.jyoumei.cn/Article/details/gt2xzhbvygu.html


<!-- 参考信息 -->