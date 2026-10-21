代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtskgiggpj.html

[F06] 删除文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgdkfqdb.html

Py:   os.remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gtkfimzifk.html

PHP:  unlink("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtbdrhufoe.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtpqqhjtww.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtjfqhhnnk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtgvzgkcyu.html

Go:   os.Remove("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtmzdjqhtu.html

Ruby: File.delete("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtdlaqanan.html

C#:   File.Delete("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtftatoeuo.html

[F07] 创建目录（含多级）
来源：http://dali.yuanzhike.top/Article/details/gtzhdkysac.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zycfv.cn/Article/details/gtwqpnmfve.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtdimkfukw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gtpvymglxn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258888.top/Article/details/gtfupxwbkb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sxryk.cn/Article/details/gtqfabqhoj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nanxuanxn.top/Article/details/gtgbwgjvwk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ydzc1.top/Article/details/gttzkhytml.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.quarkkingdee.top/Article/details/gttqpzdehj.html

[F08] 遍历目录
来源：http://dali.fzhhl.top/Article/details/gtssygjbhy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.wangshuangyany.cn/Article/details/gtlkukttum.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.havefunace.top/Article/details/gtkdomhhtg.html

JS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtixjdbskl.html

TS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gtgvxxpsep.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shzxlz.cn/Article/details/gtscvpicmu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.andypj.xyz/Article/details/gtfigczsuo.html

Ruby: Dir.children("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqsqgnxpi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aibaodan.cn/Article/details/gtubblrgxn.html

[F09] 获取文件大小
来源：http://dali.zhoulong.xyz/Article/details/gtevsrbzod.html

Py:   os.path.getsize("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtcjkatkfm.html

PHP:  filesize("a.txt");
来源：http://dali.meibo888.top/Article/details/gtuqgcrjxv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gthwippfau.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gtfhhbllnj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtcgkibzsl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.feifeiyinyue.top/Article/details/gtgqraznyn.html

Ruby: File.size("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtgtowsqvm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hfpthk.cn/Article/details/gttxridabc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.kuanghao11.cn/Article/details/gtpffyhvyo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtwhxmppub.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yonumen.top/Article/details/gtxpynzcyh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtyhladkuw.html

TS:   path.extname("a.txt")
来源：http://dali.cashguo.top/Article/details/gtibmvpttq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.andypj.xyz/Article/details/gtmtgnhiyv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtvhzmypon.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtkrcxgjbj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtyanezsdo.html

[F11] 复制与移动文件
来源：http://dali.yongpay.top/Article/details/gticxlssxt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtulqtcbgi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fzhhl.top/Article/details/gtnlfolixj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtoysreckj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtyfldaxos.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sysykeji.top/Article/details/gtofbxjudk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj20258.top/Article/details/gtppeihlpw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gthyktaxmg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hammf.cn/Article/details/gtoulevmja.html

[F12] CSV 读写
来源：http://dali.jyoumei.cn/Article/details/gtxsgjhduj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yonumen.top/Article/details/gtcnznfnnq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cqqwz.cn/Article/details/gtoogbqfww.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sufxvd.cn/Article/details/gtibsoifps.html

TS:   // 同上
来源：http://dali.hywenlv.cn/Article/details/gtswlasbrg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hfpthk.cn/Article/details/gtlrjtulhb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pengpengdd.cyou/Article/details/gtzllanveb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yangfankeji.com/Article/details/gtsxgahwfl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhengqikj.top/Article/details/gtdmpwqeue.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtfwasnefx.html

G. 面向对象
来源：http://dali.shanyushiyangtech.top/Article/details/gtbagckokh.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtvhktckyn.html

[G01] 定义类
来源：http://dali.smart0.xyz/Article/details/gtmgqvewel.html

Py:   class User: pass
来源：http://dali.chenzaomai.com/Article/details/gttuxciqaq.html

PHP:  class User {}
来源：http://dali.gotoacloud.top/Article/details/gtknbjkihy.html

JS:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gtclhwxukb.html

TS:   class User { name: string = ""; }
来源：http://dali.yongpay.top/Article/details/gtmvpwflra.html

Java: class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtvkqscrhr.html

Go:   type User struct { Name string }
来源：http://dali.havefunace.top/Article/details/gtuxyhrlkl.html

Ruby: class User; end
来源：http://dali.zycfv.cn/Article/details/gtvvpqtyhf.html

C#:   class User {}
来源：http://dali.ppjwa.cn/Article/details/gtoaqdxlgb.html

[G02] 构造函数
来源：http://dali.birdmap.top/Article/details/gtnzypwole.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj202588.top/Article/details/gtrdfqjtbr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sxryk.cn/Article/details/gtyatltrzx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gtpbfbmvni.html

TS:   constructor(public name: string) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqrrttov.html

Java: User(String name) { this.name = name; }
来源：http://dali.316326.xyz/Article/details/gtzouwhsrz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zycfv.cn/Article/details/gttndpvzbd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yangfankeji.com/Article/details/gtadkskdky.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtzuvvnpwi.html

[G03] 实例属性
来源：http://dali.yuxming.cn/Article/details/gtebpirvfa.html

Py:   self.name = "x"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrvyoyvd.html

PHP:  public string $name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtoohiebxy.html

JS:   this.name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtzakkexwz.html

TS:   name: string = "x";
来源：http://dali.yj202588.top/Article/details/gtkxnanvcr.html

Java: private String name;
来源：http://dali.feifeiyinyue.top/Article/details/gtitfdcluw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gogol.net.cn/Article/details/gtewpiseit.html

Ruby: @name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gtbounazzr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjlzyhzda.html

[G04] 定义方法
来源：http://dali.jinqigfzy.top/Article/details/gtjlqeitdr.html

Py:   def greet(self): return self.name
来源：http://dali.ydzc1.top/Article/details/gtmmxyrnfy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gtubmmgara.html

JS:   greet() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtfaynujqw.html

TS:   greet(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtefbbjbkt.html

Java: String greet() { return name; }
来源：http://dali.cheryme.top/Article/details/gtwdgsyttp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtfqzkgvnb.html

Ruby: def greet; @name; end
来源：http://dali.haohaochexian.top/Article/details/gtqfilozzf.html

C#:   public string Greet() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gtfvcsvgno.html

[G05] 继承
来源：http://dali.hysaishi.cn/Article/details/gtswarcqlp.html

Py:   class Admin(User): pass
来源：http://dali.sweek.top/Article/details/gtmgwdntfj.html

PHP:  class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtkusjyhom.html

JS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtvmwofojj.html

TS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtaqmyszrx.html

Java: class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtndcmnjcb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yueranfly.top/Article/details/gtosdbufod.html

Ruby: class Admin < User; end
来源：http://dali.yj202588.top/Article/details/gtawvlhlul.html

C#:   class Admin : User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtxqkbkndl.html

[G06] 重写方法
来源：http://dali.kuanghao11.cn/Article/details/gtaozmsasp.html

Py:   def greet(self): return "admin"
来源：http://dali.xuetiantiany.cn/Article/details/gtsqlyejzj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtionivhrd.html

JS:   greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gthqzpldwv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtexdpzeyg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtjkolur.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.feifeiyinyue.top/Article/details/gtjsjsbogt.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigfzy.top/Article/details/gtvomagjug.html

C#:   public override string Greet() => "admin";
来源：http://dali.dashuyun.cn/Article/details/gtnuawjcky.html

[G07] 调用父类方法
来源：http://dali.hnqzz.top/Article/details/gtmeshdulu.html

Py:   super().greet()
来源：http://dali.guowangkeji.top/Article/details/gtrzwlqaoj.html

PHP:  parent::greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtduzqtect.html

JS:   super.greet();
来源：http://dali.hfpthk.cn/Article/details/gtdfhfhpis.html

TS:   super.greet();
来源：http://dali.zycfv.cn/Article/details/gtevcputtv.html

Java: super.greet();
来源：http://dali.sysykeji.top/Article/details/gtfylsmgmx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnxiangtu.top/Article/details/gtbtjqrawy.html

Ruby: super
来源：http://dali.gogol.net.cn/Article/details/gtajsssjlh.html

C#:   base.Greet();
来源：http://dali.yuxming.cn/Article/details/gtfasoknwt.html

[G08] 静态方法与属性
来源：http://dali.pengpengdd.cyou/Article/details/gtdftuvwvq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yangfankeji.com/Article/details/gtnsdzgoir.html

PHP:  public static function f() {}
来源：http://dali.316326.xyz/Article/details/gtxnvisjtf.html

JS:   static f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajdhwrfr.html

TS:   static f(): void {}
来源：http://dali.zycfv.cn/Article/details/gthbcbdvvc.html

Java: static void f() {}
来源：http://dali.nanxuanxn.top/Article/details/gtiqfswknz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhoulong.xyz/Article/details/gtgdmobudt.html

Ruby: def self.f; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjbwllkis.html

C#:   public static void F() {}
来源：http://dali.cheryme.top/Article/details/gtkphmlqag.html

[G09] 接口 / 抽象类
来源：http://dali.wangdashe.top/Article/details/gtwtdigqse.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cheryme.top/Article/details/gtycpobbgj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shzxlz.cn/Article/details/gtxryudbos.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yongpay.top/Article/details/gtquafoelf.html

TS:   interface Shape { area(): number; }
来源：http://dali.birdmap.top/Article/details/gtwxrnlvcn.html

Java: interface Shape { double area(); }
来源：http://dali.wangdashe.top/Article/details/gtvdhpokls.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yuanzhike.top/Article/details/gtvimbvyem.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenlongwang.top/Article/details/gtlyxtrzco.html

C#:   interface IShape { double Area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtkgbabbgu.html

[G10] 访问控制
来源：http://dali.havefunace.top/Article/details/gtbljhdtca.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhiwuduotai.top/Article/details/gtdtnfwblg.html

PHP:  public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtvqqbmj.html

JS:   #private 字段；其余公开
来源：http://dali.jqgufenzy.top/Article/details/gtislsrhim.html

TS:   public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtnzrdjcof.html

Java: public / protected / private / 默认包级
来源：http://dali.jqgfzy.top/Article/details/gtykmmzlul.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinghuilouyu.cn/Article/details/gtqkvukjap.html

Ruby: public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gtgnoohlcq.html

C#:   public / protected / private / internal
来源：http://dali.316326.xyz/Article/details/gtqcwhnmgf.html

[G11] getter / setter
来源：http://dali.hfpthk.cn/Article/details/gtlovftcyl.html

Py:   @property 与 @x.setter
来源：http://dali.hnqzz.top/Article/details/gtwklkyzqe.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gtnvlxtjpb.html

JS:   get name() { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gtzipmrmer.html

TS:   get name(): string { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gtwezesgiq.html

Java: public String getName() { return name; }
来源：http://dali.fzhhl.top/Article/details/gthbsicskw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtmcoizgmp.html

Ruby: attr_accessor :name
来源：http://dali.tanke756.top/Article/details/gtmeddmilm.html

C#:   public string Name { get; set; }
来源：http://dali.xziqi.cn/Article/details/gtbngoztmd.html

[G12] 对象转字符串
来源：http://dali.ppjwa.cn/Article/details/gtcmrevxoo.html

Py:   def __str__(self): return self.name
来源：http://dali.yvedp.cn/Article/details/gtvdznoiyn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gtgzyyomai.html

JS:   toString() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtwuhttpxp.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtggwmlfuf.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtmweispxn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gtyqtmbeiz.html

Ruby: def to_s; @name; end
来源：http://dali.kuanghao11.cn/Article/details/gtvhbetjyz.html

C#:   public override string ToString() => Name;
来源：http://dali.hysaishi.cn/Article/details/gtxzanfcwa.html

[G13] 判断对象类型
来源：http://dali.tian-w.cn/Article/details/gthblvqhpl.html

Py:   isinstance(u, User)
来源：http://dali.aizwys.cn/Article/details/gtblywwugl.html

PHP:  $u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtzdxirobs.html

JS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtygcgzlod.html

TS:   u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtopbjvdgd.html

Java: u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtlfkykhds.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hongshengwenyu.top/Article/details/gtfdthkuyj.html

Ruby: u.is_a?(User)
来源：http://dali.sweek.top/Article/details/gtiejwlkli.html

C#:   u is User
来源：http://dali.9152youxi.cn/Article/details/gtuudvybya.html

[G14] 数据类 / record
来源：http://dali.chenzaomai.com/Article/details/gtshbrbjki.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.havefunace.top/Article/details/gtcfhrcshh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yuanzhike.top/Article/details/gtyyitawrj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yanxiufei.cn/Article/details/gtjwsvtvqo.html

TS:   type User = { name: string; age: number };
来源：http://dali.gotoacloud.top/Article/details/gtlvjkrcke.html

Java: record User(String name, int age) {}
来源：http://dali.dianchejie.cn/Article/details/gtuyfvcsgb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.redwolf501.top/Article/details/gtbwxosnks.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cashguo.top/Article/details/gthunaizea.html

C#:   record User(string Name, int Age);
来源：http://dali.vqdsnc.cn/Article/details/gtlkikqfuj.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gtsjzsjtqn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sufxvd.cn/Article/details/gtwfddsmii.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtsfecjlok.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dashuyun.cn/Article/details/gtcvxzggxi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cdnleiting.top/Article/details/gtddqtvagf.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigfzy.top/Article/details/gtdczzufpf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.mhx1999.top/Article/details/gtljtodmio.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shangyingyoupin.top/Article/details/gttsnrplya.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gtqivxmovf.html

[G16] 对象转数组 / 字典
来源：http://dali.xylfe.cn/Article/details/gtxeiwrgac.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.wangshuangyany.cn/Article/details/gtdqcpaaqi.html

PHP:  get_object_vars($obj);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtraceuzrw.html

JS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtqifknczz.html

TS:   Object.entries(obj)
来源：http://dali.gzhubu.top/Article/details/gthjsbqrla.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenzaomai.com/Article/details/gtddoajdte.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sufxvd.cn/Article/details/gtufnoxqdp.html

Ruby: obj.instance_variables
来源：http://dali.hywenlv.cn/Article/details/gtgbnbnpjb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gtloxckdhb.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtoyynxzvn.html

H. 异常与错误处理
来源：http://dali.jiagoushi.top/Article/details/gttebmugdx.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtazzallht.html

[H01] try / catch 基础
来源：http://dali.daria6918.cn/Article/details/gtqkuzcupl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.mhx1999.top/Article/details/gtrbuybtud.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.haohaochexian.top/Article/details/gtzsziqant.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gtqsbmwyrg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gtkivrfywj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnxiangtu.top/Article/details/gtppmrjrjh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxinkj.top/Article/details/gtuhjqpxei.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.havefunace.top/Article/details/gttzxapxbh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tanke756.top/Article/details/gtpdfirhgx.html

[H02] finally / ensure 收尾
来源：http://dali.sxryk.cn/Article/details/gtsxvjpovo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.andypj.xyz/Article/details/gtyaifrgdz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtikobauby.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gteureyxvx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtrfzphwav.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtdzwoccmq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daria6918.cn/Article/details/gtxgzuxjge.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gzhubu.top/Article/details/gteefnfxfj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtaaxzjhue.html

[H03] 主动抛出异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxguzfgvi.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinqigfzy.top/Article/details/gtcgzorhnj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtvxyrprjt.html

JS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gthylwtvqq.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtotmooutr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gthlzghzyd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tian-w.cn/Article/details/gtxdbqcqcf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnqzz.top/Article/details/gtlagqvbqs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gttlujobpr.html

[H04] 自定义异常类型
来源：http://dali.316326.xyz/Article/details/gtruomtzse.html

Py:   class MyError(Exception): pass
来源：http://dali.cashguo.top/Article/details/gtveufloms.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jlsjyb.cn/Article/details/gtlvqzferw.html

JS:   class MyError extends Error {}
来源：http://dali.aibaodan.cn/Article/details/gtrvkgkcmx.html

TS:   class MyError extends Error {}
来源：http://dali.shzxlz.cn/Article/details/gtupdyorqf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tian-w.cn/Article/details/gtxefacxwd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hnqzz.top/Article/details/gtepnjonlq.html

Ruby: class MyError < StandardError; end
来源：http://dali.mhx1999.top/Article/details/gtyjepndjq.html

C#:   class MyException : Exception {}
来源：http://dali.hysaishi.cn/Article/details/gtlwwjhkzf.html

[H05] 捕获特定类型
来源：http://dali.meibo888.top/Article/details/gtbhvnalzl.html

Py:   except ValueError as e:
来源：http://dali.gotoacloud.top/Article/details/gtslsctxjf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtdzfnatrx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.wangdashe.top/Article/details/gtmjpimbde.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.quarkkingdee.top/Article/details/gtrtewqpnz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhoulong.xyz/Article/details/gtgawovzkq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zdqjudy.top/Article/details/gtgjbtiocy.html

Ruby: rescue ArgumentError => e
来源：http://dali.yuxming.cn/Article/details/gtvuctxjil.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtbjanxzqv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.andypj.xyz/Article/details/gtsatxlodu.html

Py:   value = d.get("k") or default
来源：http://dali.gogol.net.cn/Article/details/gtzgzjkkwk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.guannengcc.top/Article/details/gtgbkxdypl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gtaauhwdoi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gtxusxomfc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daxiang520.top/Article/details/gtgzuohdzf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shuidangran.top/Article/details/gteegoeaft.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xylfe.cn/Article/details/gtzokmgsec.html

C#:   obj?.A?.B ?? default
来源：http://dali.jianghu66.top/Article/details/gtbfsxdfpz.html

[H07] 断言
来源：http://dali.shuidangran.top/Article/details/gthaoarugq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gzhubu.top/Article/details/gtovdxzwnc.html

PHP:  assert($x > 0);
来源：http://dali.andypj.xyz/Article/details/gtoppnyzpm.html

JS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtkmfcgqxa.html

TS:   console.assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gtnzpzlsgy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yonumen.top/Article/details/gtabiraewa.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.iojbl.cn/Article/details/gtdnwhllsk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yueranfly.top/Article/details/gtsnrkznoz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gtoujgrabu.html

[H08] 获取错误信息与堆栈
来源：http://dali.ydzc1.top/Article/details/gtiwhlfstp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guowangkeji.top/Article/details/gtkkdrcpbf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.bjfxy.top/Article/details/gtnhfstvcs.html

JS:   e.message;  e.stack
来源：http://dali.jlsjyb.cn/Article/details/gtzszrycuf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cdnleiting.top/Article/details/gtstnlfqak.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.fzhhl.top/Article/details/gtympkxdpp.html

Go:   err.Error()
来源：http://dali.hysaishi.cn/Article/details/gtgjcmxohn.html

Ruby: e.message;  e.backtrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfzsqhsog.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigfzy.top/Article/details/gtudkhhsff.html

[H09] 带错误码的异常
来源：http://dali.mhx1999.top/Article/details/gtpqubeawy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fengsongda.top/Article/details/gtjrzzmvzy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zdqjudy.top/Article/details/gtmarbnbwo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.havefunace.top/Article/details/gtnlvcdzuw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shangyingyoupin.top/Article/details/gtaccmkmbt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenjidiqi.icu/Article/details/gtfiifbeyd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.wangdashe.top/Article/details/gtgopnskoa.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yueranfly.top/Article/details/gtnlmpymrp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gogol.net.cn/Article/details/gtktawmlio.html

[H10] 资源自动释放
来源：http://dali.ydzc1.top/Article/details/gtyqdnoujo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cucudq.cn/Article/details/gtbzeynrda.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigufen.top/Article/details/gtpyhmafss.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gtvlwkpxse.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gthkbbdytz.html


<!-- 参考信息 -->