代发 wailian999

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guowangkeji.top/Article/details/gtbpxsiyns.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzndqxrmp.html

JS:   fs.readdirSync("dir")
来源：http://dali.gogol.net.cn/Article/details/gtlyktxnpi.html

TS:   fs.readdirSync("dir")
来源：http://dali.9152youxi.cn/Article/details/gtahmotgic.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhiwuduotai.top/Article/details/gtezajwjdd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gotoacloud.top/Article/details/gtwygwdyon.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtlknmraja.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangdashe.top/Article/details/gtvifirdfo.html

[F09] 获取文件大小
来源：http://dali.jlsjyb.cn/Article/details/gttyoivukg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xylfe.cn/Article/details/gthaoslyin.html

PHP:  filesize("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtzihmfizz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtofxtqkvb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenjidiqi.icu/Article/details/gtwxhonapd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtuwwxmmvx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenzaomai.com/Article/details/gtponwtgwd.html

Ruby: File.size("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtlrtnyprf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jianghu66.top/Article/details/gtvlmqzxaa.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cucudq.cn/Article/details/gtcjhsxsxm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtiwgvitlm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.smart0.xyz/Article/details/gttvwzkwaw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtpqepshrj.html

TS:   path.extname("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtvizcqxfg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sufxvd.cn/Article/details/gtxgmzavgr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtxkntotlo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtizvmhven.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrwpireeu.html

[F11] 复制与移动文件
来源：http://dali.haohaochexian.top/Article/details/gtgyndcfhv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtdbkermmi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.iojbl.cn/Article/details/gtehbropju.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gteihfnscc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtycbmdwsd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj20258888.top/Article/details/gtmxwnjtxw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.mhx1999.top/Article/details/gtlnrnjkbd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtayljgvsq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenzaomai.com/Article/details/gtnnktlcoy.html

[F12] CSV 读写
来源：http://dali.xuetiantiany.cn/Article/details/gtmhoarejp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gogol.net.cn/Article/details/gtbgyassef.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tian-w.cn/Article/details/gtvwuqwxan.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ydzc1.top/Article/details/gtxpxhckft.html

TS:   // 同上
来源：http://dali.gotoacloud.top/Article/details/gtbissiacp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhiwuduotai.top/Article/details/gtwoipqwmv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuanzhike.top/Article/details/gtevogfcgk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tanke756.top/Article/details/gthrojbllw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.c1oappe.top/Article/details/gtqlopjjms.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtasvzfryp.html

G. 面向对象
来源：http://dali.pycfn.com/Article/details/gtrsibbraj.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtpkuemnms.html

[G01] 定义类
来源：http://dali.jinqigfzy.top/Article/details/gtbfzqtqtq.html

Py:   class User: pass
来源：http://dali.hongshengwenyu.top/Article/details/gtrpnbdmvo.html

PHP:  class User {}
来源：http://dali.mhx1999.top/Article/details/gtsjggotwb.html

JS:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gtzbwzgwib.html

TS:   class User { name: string = ""; }
来源：http://dali.fzhhl.top/Article/details/gtsadtvycd.html

Java: class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtkbnnjiyl.html

Go:   type User struct { Name string }
来源：http://dali.yj20258.top/Article/details/gtohxqtsdk.html

Ruby: class User; end
来源：http://dali.hfpthk.cn/Article/details/gtnfqdnunc.html

C#:   class User {}
来源：http://dali.cashguo.top/Article/details/gtkacmhmtt.html

[G02] 构造函数
来源：http://dali.zhoulong.xyz/Article/details/gtfzmowkto.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yangfankeji.com/Article/details/gtgtyonprh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258888.top/Article/details/gtyzlhjfcp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gttapqjhsv.html

TS:   constructor(public name: string) {}
来源：http://dali.sysykeji.top/Article/details/gtwjzmnvxt.html

Java: User(String name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gtcjjcuijq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxinkj.top/Article/details/gtdcksozps.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zdqjudy.top/Article/details/gtircabxgv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtbysvnfjk.html

[G03] 实例属性
来源：http://dali.fengsongda.top/Article/details/gtgxrywako.html

Py:   self.name = "x"
来源：http://dali.yj202588.top/Article/details/gtwvwoeare.html

PHP:  public string $name = "x";
来源：http://dali.havefunace.top/Article/details/gtjomwltkw.html

JS:   this.name = "x";
来源：http://dali.xylfe.cn/Article/details/gtqphxogua.html

TS:   name: string = "x";
来源：http://dali.yangfankeji.com/Article/details/gtjmxcudbt.html

Java: private String name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjsdlzsd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yonumen.top/Article/details/gtxfnqszcq.html

Ruby: @name = "x"
来源：http://dali.yuanzhike.top/Article/details/gtuxybukih.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gogol.net.cn/Article/details/gtnklrqurk.html

[G04] 定义方法
来源：http://dali.ehwqpu.com/Article/details/gttfaujmns.html

Py:   def greet(self): return self.name
来源：http://dali.iojbl.cn/Article/details/gtryahspbk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gtzxrboflk.html

JS:   greet() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtudtgtdzj.html

TS:   greet(): string { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtmdszhifx.html

Java: String greet() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtarcoakxf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gtxzmvtotb.html

Ruby: def greet; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gturyfnpcy.html

C#:   public string Greet() => Name;
来源：http://dali.nanxinkj.top/Article/details/gtjyvptlkw.html

[G05] 继承
来源：http://dali.sweek.top/Article/details/gtialbsuuu.html

Py:   class Admin(User): pass
来源：http://dali.hnqzz.top/Article/details/gtmvhzsxtj.html

PHP:  class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtgvnyispx.html

JS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtxrhrpaqe.html

TS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtchdkpjwg.html

Java: class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtdbqsczvr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.bjfxy.top/Article/details/gtcvbmhntx.html

Ruby: class Admin < User; end
来源：http://dali.yuanzhike.top/Article/details/gttsvzpdec.html

C#:   class Admin : User {}
来源：http://dali.xylfe.cn/Article/details/gthctykjrp.html

[G06] 重写方法
来源：http://dali.0kj1m.cn/Article/details/gtpnhnwaet.html

Py:   def greet(self): return "admin"
来源：http://dali.xuetiantiany.cn/Article/details/gtchulwjij.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtxskbnspl.html

JS:   greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gteoatiyvc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtsoucgtmy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtsttjwbtf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cqqwz.cn/Article/details/gtzieoypmm.html

Ruby: def greet; "admin"; end
来源：http://dali.feifeiyinyue.top/Article/details/gtmqvtfmtj.html

C#:   public override string Greet() => "admin";
来源：http://dali.haohaochexian.top/Article/details/gtyjguhcle.html

[G07] 调用父类方法
来源：http://dali.jyoumei.cn/Article/details/gtvsdxalrx.html

Py:   super().greet()
来源：http://dali.jianghu66.top/Article/details/gtgsdblvag.html

PHP:  parent::greet();
来源：http://dali.hammf.cn/Article/details/gtcxhceqka.html

JS:   super.greet();
来源：http://dali.yj20258.top/Article/details/gttlcmclkb.html

TS:   super.greet();
来源：http://dali.hysaishi.cn/Article/details/gtdjxprjzl.html

Java: super.greet();
来源：http://dali.daria6918.cn/Article/details/gthhwdrqqi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jyoumei.cn/Article/details/gtbyeyfmfp.html

Ruby: super
来源：http://dali.aizwys.cn/Article/details/gthusfauhf.html

C#:   base.Greet();
来源：http://dali.yongpay.top/Article/details/gtcfnzlhcr.html

[G08] 静态方法与属性
来源：http://dali.hammf.cn/Article/details/gtkjluqqin.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daria6918.cn/Article/details/gtfrzbtykc.html

PHP:  public static function f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtvhrbksjz.html

JS:   static f() {}
来源：http://dali.hfpthk.cn/Article/details/gtkqftrsco.html

TS:   static f(): void {}
来源：http://dali.ivvv.top/Article/details/gtwdwxgwwb.html

Java: static void f() {}
来源：http://dali.hywenlv.cn/Article/details/gtgbqotdle.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gotoacloud.top/Article/details/gtxtnjofit.html

Ruby: def self.f; end
来源：http://dali.sufxvd.cn/Article/details/gttavwuijn.html

C#:   public static void F() {}
来源：http://dali.hysaishi.cn/Article/details/gtokmamkcz.html

[G09] 接口 / 抽象类
来源：http://dali.316326.xyz/Article/details/gtcxnbfwam.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenjidiqi.icu/Article/details/gtlbbiywlo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ehwqpu.com/Article/details/gtvkuzanap.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhiwuduotai.top/Article/details/gtjbacnfsx.html

TS:   interface Shape { area(): number; }
来源：http://dali.redwolf501.top/Article/details/gtquxhguby.html

Java: interface Shape { double area(); }
来源：http://dali.zdqjudy.top/Article/details/gtyyufrtsq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxinkj.top/Article/details/gtgezcytul.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.mhx1999.top/Article/details/gtbgukrsnr.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjdlhcrno.html

[G10] 访问控制
来源：http://dali.gaohongyu789.top/Article/details/gtibatbtti.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.iojbl.cn/Article/details/gtectftkjh.html

PHP:  public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmlcctyng.html

JS:   #private 字段；其余公开
来源：http://dali.jiagoushi.top/Article/details/gtnphccyaw.html

TS:   public / protected / private
来源：http://dali.sxryk.cn/Article/details/gtffplhhmn.html

Java: public / protected / private / 默认包级
来源：http://dali.yuanzhike.top/Article/details/gtdnngouhj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nanxinkj.top/Article/details/gtfyfszxrg.html

Ruby: public / protected / private
来源：http://dali.yonumen.top/Article/details/gtwxcauxdb.html

C#:   public / protected / private / internal
来源：http://dali.sufxvd.cn/Article/details/gtjxcsrnom.html

[G11] getter / setter
来源：http://dali.havefunace.top/Article/details/gtwqxxoodz.html

Py:   @property 与 @x.setter
来源：http://dali.yuanzhike.top/Article/details/gtwktadbav.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtymjkqzhm.html

JS:   get name() { return this._name; }
来源：http://dali.dianchejie.cn/Article/details/gtmfcbkdvd.html

TS:   get name(): string { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gtvvlvtrwy.html

Java: public String getName() { return name; }
来源：http://dali.yongpay.top/Article/details/gtjlqzdfuy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gtphgvydjh.html

Ruby: attr_accessor :name
来源：http://dali.quarkkingdee.top/Article/details/gttjdjwvsr.html

C#:   public string Name { get; set; }
来源：http://dali.zhoulong.xyz/Article/details/gtsnrxaxvj.html

[G12] 对象转字符串
来源：http://dali.sweek.top/Article/details/gthljzuogu.html

Py:   def __str__(self): return self.name
来源：http://dali.hnqzz.top/Article/details/gtxqjuhzog.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gtkdvhoraz.html

JS:   toString() { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtqzuhjrdb.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnzfdppqy.html

Java: @Override public String toString() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzbakdsjm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gthqbvyrri.html

Ruby: def to_s; @name; end
来源：http://dali.cdnleiting.top/Article/details/gtnuwkeafd.html

C#:   public override string ToString() => Name;
来源：http://dali.andypj.xyz/Article/details/gtykvfxfgk.html

[G13] 判断对象类型
来源：http://dali.hysaishi.cn/Article/details/gtdmozevvv.html

Py:   isinstance(u, User)
来源：http://dali.gaohongyu789.top/Article/details/gtrkoryrmf.html

PHP:  $u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtoowdboti.html

JS:   u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtqxwfffop.html

TS:   u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtixminkeg.html

Java: u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtdgovjpsh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.andypj.xyz/Article/details/gtlhdqmfhm.html

Ruby: u.is_a?(User)
来源：http://dali.cucudq.cn/Article/details/gtijexsnal.html

C#:   u is User
来源：http://dali.jinqigfzy.top/Article/details/gtcbhiscrc.html

[G14] 数据类 / record
来源：http://dali.shzxlz.cn/Article/details/gtsalnkrpc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.9152youxi.cn/Article/details/gtpuomuhuh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxuanxn.top/Article/details/gtvevqrenh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.iojbl.cn/Article/details/gtqhcwofzj.html

TS:   type User = { name: string; age: number };
来源：http://dali.jlsjyb.cn/Article/details/gtwhlquzho.html

Java: record User(String name, int age) {}
来源：http://dali.yongpay.top/Article/details/gtjdtpqnot.html

Go:   type User struct { Name string; Age int }
来源：http://dali.havefunace.top/Article/details/gtadymkyid.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xziqi.cn/Article/details/gtytdlbhxu.html

C#:   record User(string Name, int Age);
来源：http://dali.zhoulong.xyz/Article/details/gtultjiogp.html

[G15] 枚举
来源：http://dali.aibaodan.cn/Article/details/gtmmnojman.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhiwuduotai.top/Article/details/gtypoloeag.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.vqdsnc.cn/Article/details/gttznvcljc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ivvv.top/Article/details/gtssebpnnq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gtoahlyqni.html

Java: enum Color { RED, GREEN }
来源：http://dali.yangfankeji.com/Article/details/gtnanqmizi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zycfv.cn/Article/details/gtteigfvfw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xuetiantiany.cn/Article/details/gtqvbxcndb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gtemvutvpr.html

[G16] 对象转数组 / 字典
来源：http://dali.yonumen.top/Article/details/gtkgsztyxj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxinkj.top/Article/details/gtmirgxatx.html

PHP:  get_object_vars($obj);
来源：http://dali.xuetiantiany.cn/Article/details/gtmrraerpw.html

JS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gtyqsbclzm.html

TS:   Object.entries(obj)
来源：http://dali.tianlin.xyz/Article/details/gtakdrwiph.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yangfankeji.com/Article/details/gtivtfvldu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nwbrower.top/Article/details/gtxhqdjrtw.html

Ruby: obj.instance_variables
来源：http://dali.andypj.xyz/Article/details/gtyqbpwrma.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gtluvwbtnu.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gthtcimeuo.html

H. 异常与错误处理
来源：http://dali.chenjidiqi.icu/Article/details/gthmjjtfab.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtehcqwjpb.html

[H01] try / catch 基础
来源：http://dali.zhengqikj.top/Article/details/gtzmtglrmh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.birdmap.top/Article/details/gtydspwflp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gogol.net.cn/Article/details/gtrtkdmhyw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gtcezlddoj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gtqicgzgaj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhixingplan.top/Article/details/gtjtopsjpu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yongpay.top/Article/details/gtckutpgck.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sweek.top/Article/details/gtrukiwtxz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.dianchejie.cn/Article/details/gtpbfcstmf.html

[H02] finally / ensure 收尾
来源：http://dali.yj202588.top/Article/details/gtuqrvizgl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.redwolf501.top/Article/details/gtwbgbdjxc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtdykqmsuz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtwstomfsg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gthcqvbsku.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtscmghkfj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zdqjudy.top/Article/details/gtmmmapjsx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tian-w.cn/Article/details/gtpsoxzmin.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtdsuyoaxu.html

[H03] 主动抛出异常
来源：http://dali.gotoacloud.top/Article/details/gtfgrcfrxt.html

Py:   raise ValueError("错误信息")
来源：http://dali.shuidangran.top/Article/details/gtzqljhahk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtjoayxinc.html

JS:   throw new Error("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtlveqroxm.html

TS:   throw new Error("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtmyuskaqm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtjfrqiofh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tanke756.top/Article/details/gtxepidyax.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nwbrower.top/Article/details/gtgvrpdhrc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtpsytzzrj.html

[H04] 自定义异常类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtespkutjo.html

Py:   class MyError(Exception): pass
来源：http://dali.yvedp.cn/Article/details/gtlgsmdwua.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.redwolf501.top/Article/details/gtaxpsoljw.html

JS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gtenpfauao.html

TS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrzilhnx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj20258.top/Article/details/gtqrhvkfev.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xuetiantiany.cn/Article/details/gtoxfelrxo.html

Ruby: class MyError < StandardError; end
来源：http://dali.fengsongda.top/Article/details/gtzozadvkc.html

C#:   class MyException : Exception {}
来源：http://dali.9152youxi.cn/Article/details/gtrknoewho.html

[H05] 捕获特定类型
来源：http://dali.havefunace.top/Article/details/gttjyppfnm.html

Py:   except ValueError as e:
来源：http://dali.yuxming.cn/Article/details/gttkrkyglk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.andypj.xyz/Article/details/gtomsfjyja.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhoulong.xyz/Article/details/gtwrszchvf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tanke756.top/Article/details/gtsixudvgg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.mhx1999.top/Article/details/gtyekcataw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.snrcjt.cn/Article/details/gtzlmtiexh.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangshuangyany.cn/Article/details/gtvusltotm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tian-w.cn/Article/details/gttbtjwxap.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shzxlz.cn/Article/details/gtokrzyudx.html

Py:   value = d.get("k") or default
来源：http://dali.meibo888.top/Article/details/gtjyirdapr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gaohongyu789.top/Article/details/gtfrxtyjtt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgfzy.top/Article/details/gtbowbbrfs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gtqyuhbgmk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hongshengwenyu.top/Article/details/gtszqacocx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjciimybp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdzenipea.html

C#:   obj?.A?.B ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtulciypls.html

[H07] 断言
来源：http://dali.xinyue.icu/Article/details/gtwujyksyi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fzhhl.top/Article/details/gtzvjzsvtb.html

PHP:  assert($x > 0);
来源：http://dali.nwbrower.top/Article/details/gtsopgapye.html

JS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtxfvqmcyq.html

TS:   console.assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtwvfqhfru.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gzhubu.top/Article/details/gthgenjiuw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hfpthk.cn/Article/details/gtprkptkck.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cheryme.top/Article/details/gtgealnodr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtjehlemlh.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenjidiqi.icu/Article/details/gtctpypbji.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gogol.net.cn/Article/details/gthawayfvs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cqqwz.cn/Article/details/gtkrsijpqw.html

JS:   e.message;  e.stack
来源：http://dali.aibaodan.cn/Article/details/gtktqlwakr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.feifeiyinyue.top/Article/details/gtapusqmpx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yongpay.top/Article/details/gtjxothfgp.html

Go:   err.Error()
来源：http://dali.yvedp.cn/Article/details/gtolaxsucq.html

Ruby: e.message;  e.backtrace
来源：http://dali.quarkkingdee.top/Article/details/gtgbxpdqzb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxuanxn.top/Article/details/gtiljalviv.html

[H09] 带错误码的异常
来源：http://dali.daxiang520.top/Article/details/gtaqsefcsx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ehwqpu.com/Article/details/gtohjyanny.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zycfv.cn/Article/details/gtgksmxxwn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.316326.xyz/Article/details/gtzedsncrx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yuanzhike.top/Article/details/gtjxcdlxpv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pengpengdd.cyou/Article/details/gtzwaamard.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tian-w.cn/Article/details/gtqmonabzi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nanxuanxn.top/Article/details/gtqpicknts.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ehwqpu.com/Article/details/gtzsowdlub.html

[H10] 资源自动释放
来源：http://dali.nanxinkj.top/Article/details/gtgzxuandw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.fzhhl.top/Article/details/gtabdqfioe.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shangyingyoupin.top/Article/details/gtnuedamqc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gtdxgbddrb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gtfenqtndx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.9152youxi.cn/Article/details/gtbqsjgoro.html

Go:   defer f.Close()
来源：http://dali.hfpthk.cn/Article/details/gtqscpjsuu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cashguo.top/Article/details/gtpsndxbem.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtznwlhxgn.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtouiyybph.html

I. 正则表达式
来源：http://dali.mhx1999.top/Article/details/gtzrxztach.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtdmtslnlq.html

[I01] 判断是否匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtannvqjdd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cucudq.cn/Article/details/gtiavqlonj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.smart0.xyz/Article/details/gtmrxaoqhb.html

JS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gtvukqsbwt.html

TS:   /\d+/.test(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtyceybxsj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jlsjyb.cn/Article/details/gtfikodmbj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.pycfn.com/Article/details/gtfsbqsrir.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhiwuduotai.top/Article/details/gtllkcjbwc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.snrcjt.cn/Article/details/gtfhziyrop.html

[I02] 提取所有匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgmpxwzpo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.aibaodan.cn/Article/details/gttetpebvu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yangfankeji.com/Article/details/gtkmwydzah.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gaohongyu789.top/Article/details/gtapejojew.html


<!-- 参考信息 -->