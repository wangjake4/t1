代发 wailian999

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenzaomai.com/Article/details/gtnhxgbcka.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xuetiantiany.cn/Article/details/gtkoarvccl.html

JS:   fs.readdirSync("dir")
来源：http://dali.cashguo.top/Article/details/gtityhednp.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gtpjjwavhu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gtboqjjmpu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.fzhhl.top/Article/details/gttsoxioxp.html

Ruby: Dir.children("dir")
来源：http://dali.redwolf501.top/Article/details/gthorqiqvj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.snrcjt.cn/Article/details/gtprpziaqy.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gtkiardlqy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.havefunace.top/Article/details/gtpiplqqnt.html

PHP:  filesize("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtnmajknco.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jianghu66.top/Article/details/gttiuoqzxx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gtrzexhtxj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtmcehzkla.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhiwuduotai.top/Article/details/gtcuvihrjx.html

Ruby: File.size("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtwucocqjj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tanke756.top/Article/details/gtnwftfcwx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.iojbl.cn/Article/details/gtipywhlra.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtuqgnbflp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyxeibalu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gttkgvgrra.html

TS:   path.extname("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtmnwpydfn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shangyingyoupin.top/Article/details/gtglnpmoox.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtlwrzyjxm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtsdqyxhab.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gthtlghbpb.html

[F11] 复制与移动文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtytwlbsqy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtagametci.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.mhx1999.top/Article/details/gtvsdmcprp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtceoqwebm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtzmcydqor.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtiwxufpgm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jyoumei.cn/Article/details/gtwhfiqipq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtvtgkqfmv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.meibo888.top/Article/details/gtoktofjcv.html

[F12] CSV 读写
来源：http://dali.316326.xyz/Article/details/gtvyskfgjc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jiagoushi.top/Article/details/gtfkifnsjq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhoulong.xyz/Article/details/gteueauwdi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.haohaochexian.top/Article/details/gttbsyzlnb.html

TS:   // 同上
来源：http://dali.guowangkeji.top/Article/details/gtdjbnfnlz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nanxuanxn.top/Article/details/gtzughzcij.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.9152youxi.cn/Article/details/gtlgzggiyg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tianlin.xyz/Article/details/gthdzfjzhn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hammf.cn/Article/details/gtgmzxngne.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtntpgbyzd.html

G. 面向对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjakdojqe.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtfufkpptq.html

[G01] 定义类
来源：http://dali.aibaodan.cn/Article/details/gtgqrewtwk.html

Py:   class User: pass
来源：http://dali.sweek.top/Article/details/gttbdiwptj.html

PHP:  class User {}
来源：http://dali.guannengcc.top/Article/details/gtbrynjddf.html

JS:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtnzvqmlbn.html

TS:   class User { name: string = ""; }
来源：http://dali.9152youxi.cn/Article/details/gtwtkwhcqq.html

Java: class User {}
来源：http://dali.ehwqpu.com/Article/details/gtvlzybijd.html

Go:   type User struct { Name string }
来源：http://dali.cashguo.top/Article/details/gtukzstemn.html

Ruby: class User; end
来源：http://dali.tian-w.cn/Article/details/gtzfzmqens.html

C#:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtfhrrizsk.html

[G02] 构造函数
来源：http://dali.ybcxt.top/Article/details/gtwgcvbfut.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jiagoushi.top/Article/details/gtddmxfyzf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jianghu66.top/Article/details/gtyhiwcywb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gttjglyhle.html

TS:   constructor(public name: string) {}
来源：http://dali.chenlongwang.top/Article/details/gtxcdpamtb.html

Java: User(String name) { this.name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtnmlqhujx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.meibo888.top/Article/details/gtwcbidxgu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ehwqpu.com/Article/details/gtvpdtijsm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yongpay.top/Article/details/gtgwhtlzbp.html

[G03] 实例属性
来源：http://dali.wangdashe.top/Article/details/gtvdxezqdv.html

Py:   self.name = "x"
来源：http://dali.yangfankeji.com/Article/details/gtdgvruzrt.html

PHP:  public string $name = "x";
来源：http://dali.aibaodan.cn/Article/details/gtafxyyyyp.html

JS:   this.name = "x";
来源：http://dali.yonumen.top/Article/details/gtapqrvfxp.html

TS:   name: string = "x";
来源：http://dali.yvedp.cn/Article/details/gtosyvdewi.html

Java: private String name;
来源：http://dali.cdnleiting.top/Article/details/gtlocutfdb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenjidiqi.icu/Article/details/gtkqmflmpp.html

Ruby: @name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gtqmbaokkr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.mhx1999.top/Article/details/gtbrtnwwns.html

[G04] 定义方法
来源：http://dali.gotoacloud.top/Article/details/gtiunvhnqp.html

Py:   def greet(self): return self.name
来源：http://dali.havefunace.top/Article/details/gthfktekuz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gtercbgctb.html

JS:   greet() { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gtyddnmomk.html

TS:   greet(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gttbxdqbtf.html

Java: String greet() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtboblejll.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gtesnybuuy.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfjgmgwwu.html

C#:   public string Greet() => Name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkzmqzwnw.html

[G05] 继承
来源：http://dali.jqgufenzy.top/Article/details/gtygnjcbsf.html

Py:   class Admin(User): pass
来源：http://dali.daxiang520.top/Article/details/gtqmtpxrxw.html

PHP:  class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtralzswnq.html

JS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gteepikacd.html

TS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtkjbkuxyz.html

Java: class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtvrfcqryg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cqqwz.cn/Article/details/gtgrlqngce.html

Ruby: class Admin < User; end
来源：http://dali.hnqzz.top/Article/details/gtwzniupsz.html

C#:   class Admin : User {}
来源：http://dali.hnqzz.top/Article/details/gtncayodhy.html

[G06] 重写方法
来源：http://dali.zycfv.cn/Article/details/gtejvgqcge.html

Py:   def greet(self): return "admin"
来源：http://dali.aizwys.cn/Article/details/gtcmubqpdd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtrlrpmqde.html

JS:   greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtkedbqpoz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gtxoryuskl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtoroizecx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yanxiufei.cn/Article/details/gtkkpeptnf.html

Ruby: def greet; "admin"; end
来源：http://dali.c1oappe.top/Article/details/gtebcljyjz.html

C#:   public override string Greet() => "admin";
来源：http://dali.havefunace.top/Article/details/gtqdzrjneo.html

[G07] 调用父类方法
来源：http://dali.yuxming.cn/Article/details/gthzsmuwim.html

Py:   super().greet()
来源：http://dali.shuidangran.top/Article/details/gtqlkujiqs.html

PHP:  parent::greet();
来源：http://dali.yanxiufei.cn/Article/details/gtjrodxnsi.html

JS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gtcondrjwx.html

TS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtvmrqaopf.html

Java: super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gtjxqvuaxv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yonumen.top/Article/details/gtzwvykorb.html

Ruby: super
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjokapcyf.html

C#:   base.Greet();
来源：http://dali.zycfv.cn/Article/details/gtveuhuvle.html

[G08] 静态方法与属性
来源：http://dali.fzhhl.top/Article/details/gtkgurhlrw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hysaishi.cn/Article/details/gtyccufupk.html

PHP:  public static function f() {}
来源：http://dali.sysykeji.top/Article/details/gtsgxqmmuj.html

JS:   static f() {}
来源：http://dali.cucudq.cn/Article/details/gtldyotycs.html

TS:   static f(): void {}
来源：http://dali.c1oappe.top/Article/details/gtlcdnebjr.html

Java: static void f() {}
来源：http://dali.yongpay.top/Article/details/gthhqhyhqk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258.top/Article/details/gtruytxpmi.html

Ruby: def self.f; end
来源：http://dali.andypj.xyz/Article/details/gtjrshvoqk.html

C#:   public static void F() {}
来源：http://dali.tanke756.top/Article/details/gtsiuatpti.html

[G09] 接口 / 抽象类
来源：http://dali.nanxinkj.top/Article/details/gttnwrmpzb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cqqwz.cn/Article/details/gtwdtfopyd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhixingplan.top/Article/details/gtmzqloewz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnqzz.top/Article/details/gtnodonyaj.html

TS:   interface Shape { area(): number; }
来源：http://dali.jlsjyb.cn/Article/details/gtxisfvhjf.html

Java: interface Shape { double area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdojhpxg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hnqzz.top/Article/details/gtluygjxge.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuanzx.com/Article/details/gtwhklakct.html

C#:   interface IShape { double Area(); }
来源：http://dali.316326.xyz/Article/details/gtxvnjzubn.html

[G10] 访问控制
来源：http://dali.havefunace.top/Article/details/gtwenqiegp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hywenlv.cn/Article/details/gtpcbfhjkc.html

PHP:  public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtidzzktrb.html

JS:   #private 字段；其余公开
来源：http://dali.wangshuangyany.cn/Article/details/gtajngdvcc.html

TS:   public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gtwrwsvilq.html

Java: public / protected / private / 默认包级
来源：http://dali.sysykeji.top/Article/details/gtjxmjjzkl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xziqi.cn/Article/details/gtnkwwwgzd.html

Ruby: public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtdjgplcqq.html

C#:   public / protected / private / internal
来源：http://dali.kuanghao11.cn/Article/details/gtbqyaeyyc.html

[G11] getter / setter
来源：http://dali.zhongyouzk.top/Article/details/gtnpzvhmsg.html

Py:   @property 与 @x.setter
来源：http://dali.wangdashe.top/Article/details/gtqgofwwqk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtptcsvmkl.html

JS:   get name() { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtlnbrmjfj.html

TS:   get name(): string { return this._name; }
来源：http://dali.tian-w.cn/Article/details/gtbwcreabf.html

Java: public String getName() { return name; }
来源：http://dali.hnqzz.top/Article/details/gtgrjuoxey.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gtjspilekp.html

Ruby: attr_accessor :name
来源：http://dali.nanxinkj.top/Article/details/gtmitdlblt.html

C#:   public string Name { get; set; }
来源：http://dali.smart0.xyz/Article/details/gtcvdjczup.html

[G12] 对象转字符串
来源：http://dali.gotoacloud.top/Article/details/gtjztkouxy.html

Py:   def __str__(self): return self.name
来源：http://dali.gotoacloud.top/Article/details/gtdehlehtf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtjqhrkkzl.html

JS:   toString() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtdsgbteqh.html

TS:   toString(): string { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtfrnskbna.html

Java: @Override public String toString() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtndifbjtb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gttoxjupya.html

Ruby: def to_s; @name; end
来源：http://dali.hywenlv.cn/Article/details/gtdtiijemd.html

C#:   public override string ToString() => Name;
来源：http://dali.9152youxi.cn/Article/details/gtyccaycnj.html

[G13] 判断对象类型
来源：http://dali.andypj.xyz/Article/details/gtfaqhbnrw.html

Py:   isinstance(u, User)
来源：http://dali.dianchejie.cn/Article/details/gtsmsxnmau.html

PHP:  $u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtirnjigln.html

JS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtnwbqqlwg.html

TS:   u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtpdvqbokr.html

Java: u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtbdmgijzx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.vqdsnc.cn/Article/details/gtnzhhheul.html

Ruby: u.is_a?(User)
来源：http://dali.ydzc1.top/Article/details/gtjkosrvxs.html

C#:   u is User
来源：http://dali.yvedp.cn/Article/details/gtfxtpkvxc.html

[G14] 数据类 / record
来源：http://dali.xinyue.icu/Article/details/gtbonrxuqh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj202588.top/Article/details/gttwyonkct.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hongshengwenyu.top/Article/details/gtxjzxfxcb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgufenzy.top/Article/details/gtesfgbtgk.html

TS:   type User = { name: string; age: number };
来源：http://dali.yuanzhike.top/Article/details/gtymvcmdgp.html

Java: record User(String name, int age) {}
来源：http://dali.jqgfzy.top/Article/details/gtkodjqgxb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jianghu66.top/Article/details/gtargodrtm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.dianchejie.cn/Article/details/gtilwiuzgr.html

C#:   record User(string Name, int Age);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzmzhgtsp.html

[G15] 枚举
来源：http://dali.guowangkeji.top/Article/details/gtwopkgdli.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gtveljvtfu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tian-w.cn/Article/details/gtlvvofuob.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tian-w.cn/Article/details/gtcyhdnnhr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.svipenyu.cn/Article/details/gtmvdxrdde.html

Java: enum Color { RED, GREEN }
来源：http://dali.ybcxt.top/Article/details/gtflcqolhs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangdashe.top/Article/details/gtydejpqfn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gogol.net.cn/Article/details/gtxgaqawut.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gtyiepougt.html

[G16] 对象转数组 / 字典
来源：http://dali.daxiang520.top/Article/details/gtixnzixcm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxinkj.top/Article/details/gthufarrmb.html

PHP:  get_object_vars($obj);
来源：http://dali.birdmap.top/Article/details/gtrfjodgih.html

JS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gtcwtrqrjy.html

TS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gtxsfesvaz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yonumen.top/Article/details/gtjqojhjdj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gotoacloud.top/Article/details/gtztxghlrx.html

Ruby: obj.instance_variables
来源：http://dali.jiagoushi.top/Article/details/gtvqglbbcn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.bjfxy.top/Article/details/gtdvceztuv.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtmlnxldkk.html

H. 异常与错误处理
来源：http://dali.xylfe.cn/Article/details/gtqbyetpip.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtmmjvxdab.html

[H01] try / catch 基础
来源：http://dali.cdnleiting.top/Article/details/gttctxtylo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.c1oappe.top/Article/details/gtrpcanlky.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cqqwz.cn/Article/details/gtasvehmei.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gtmetpkhpx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtkgbvhjxp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinqigfzy.top/Article/details/gtukrpqkdy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hammf.cn/Article/details/gtwqmdodmn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.9152youxi.cn/Article/details/gtmgjswbwd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.snrcjt.cn/Article/details/gtliojdsus.html

[H02] finally / ensure 收尾
来源：http://dali.yanxiufei.cn/Article/details/gtxixsndga.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sufxvd.cn/Article/details/gtcxiphdiv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtcluetcfa.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtxhivjqfr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtwbmwbzbu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtcvweyrml.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jiagoushi.top/Article/details/gtyycntlyf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenzaomai.com/Article/details/gtncweufri.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtjhcledrx.html

[H03] 主动抛出异常
来源：http://dali.gzhubu.top/Article/details/gtymhxozid.html

Py:   raise ValueError("错误信息")
来源：http://dali.sweek.top/Article/details/gtkxxxauha.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtphrxtwcl.html

JS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtgyeqcqrr.html

TS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtfczghukf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtztmzwjwq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnxiangtu.top/Article/details/gtgwncxvuu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yvedp.cn/Article/details/gtcbjubjxq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gttizkecnc.html

[H04] 自定义异常类型
来源：http://dali.xuanzx.com/Article/details/gtytnwfzms.html

Py:   class MyError(Exception): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuprhwkvi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zdqjudy.top/Article/details/gtpjhmmfbf.html

JS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gthsdnrlzh.html

TS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gtyxybdnoi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenzaomai.com/Article/details/gtcnnbjyme.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hammf.cn/Article/details/gtsbaeyhyt.html

Ruby: class MyError < StandardError; end
来源：http://dali.fengsongda.top/Article/details/gtdkqgrrzi.html

C#:   class MyException : Exception {}
来源：http://dali.zdqjudy.top/Article/details/gtbfjqyyde.html

[H05] 捕获特定类型
来源：http://dali.hywenlv.cn/Article/details/gtgcwmflar.html

Py:   except ValueError as e:
来源：http://dali.gzhubu.top/Article/details/gtaopqircn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yueranfly.top/Article/details/gtiexfqrmb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtlixcfmdb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gtprincpgm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cucudq.cn/Article/details/gtoiulitty.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xinyue.icu/Article/details/gtqiqnnctm.html

Ruby: rescue ArgumentError => e
来源：http://dali.mhx1999.top/Article/details/gtiqboioko.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtgmgzpylj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zycfv.cn/Article/details/gtiuvthjxh.html

Py:   value = d.get("k") or default
来源：http://dali.sxryk.cn/Article/details/gtxlhsdyti.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gtqdmmrggq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yvedp.cn/Article/details/gtzhssxdzr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.havefunace.top/Article/details/gtgsyflzth.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tian-w.cn/Article/details/gtcqvbhxfg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtohifanuo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guowangkeji.top/Article/details/gtctprgmfg.html

C#:   obj?.A?.B ?? default
来源：http://dali.smart0.xyz/Article/details/gtpahlwcdm.html

[H07] 断言
来源：http://dali.sxryk.cn/Article/details/gtlshvgegi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gotoacloud.top/Article/details/gtopqidwju.html

PHP:  assert($x > 0);
来源：http://dali.ydzc1.top/Article/details/gtynxmuqfz.html

JS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gthzzrgyum.html

TS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtpxwuxlmx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhiwuduotai.top/Article/details/gtdynsqjge.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnxiangtu.top/Article/details/gtsbjkfljb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangdashe.top/Article/details/gtgnljbreq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtgyddwzpn.html

[H08] 获取错误信息与堆栈
来源：http://dali.guannengcc.top/Article/details/gtihnsnoyy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zycfv.cn/Article/details/gtgzdqtwyu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shuidangran.top/Article/details/gtdbmmcinb.html

JS:   e.message;  e.stack
来源：http://dali.nanxinkj.top/Article/details/gtzipmrjtq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.c1oappe.top/Article/details/gtgxjvipvb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tanke756.top/Article/details/gtgprbdzgq.html

Go:   err.Error()
来源：http://dali.birdmap.top/Article/details/gtzjmzqwez.html

Ruby: e.message;  e.backtrace
来源：http://dali.snrcjt.cn/Article/details/gtczgmnjti.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnxiangtu.top/Article/details/gtxjbpeuql.html

[H09] 带错误码的异常
来源：http://dali.daxiang520.top/Article/details/gtplybqyha.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhongyouzk.top/Article/details/gtxosschgi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinqigfzy.top/Article/details/gtvbonoxvc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinghuilouyu.cn/Article/details/gtrjoofftf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.meibo888.top/Article/details/gtghfejsdy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.9152youxi.cn/Article/details/gtwdrbxzyv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.316326.xyz/Article/details/gtuhgwfeob.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.fengsongda.top/Article/details/gtlsaryoul.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sysykeji.top/Article/details/gtiztfqyjt.html

[H10] 资源自动释放
来源：http://dali.zhongyouzk.top/Article/details/gtpocgiqcm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.mhx1999.top/Article/details/gtonyvwanv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cashguo.top/Article/details/gttnkvqbcc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gttxpihubp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yonumen.top/Article/details/gtkbilljsh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnidsxtva.html

Go:   defer f.Close()
来源：http://dali.ydzc1.top/Article/details/gtgntrandl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.haohaochexian.top/Article/details/gtszqduuhs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtunonpwzr.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtsbeiussw.html

I. 正则表达式
来源：http://dali.kuanghao11.cn/Article/details/gteevyoana.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtwuqliotx.html

[I01] 判断是否匹配
来源：http://dali.chenlongwang.top/Article/details/gtutvbrjpr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtuiympwzr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cucudq.cn/Article/details/gtazqqaqjv.html

JS:   /\d+/.test(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtgcoaixwb.html

TS:   /\d+/.test(s)
来源：http://dali.nwbrower.top/Article/details/gtymmgmmxt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hfpthk.cn/Article/details/gtilgjknuj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shuidangran.top/Article/details/gtdzfrclxq.html

Ruby: s.match?(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gtogoetesd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258888.top/Article/details/gtqcslxzot.html

[I02] 提取所有匹配
来源：http://dali.gzhubu.top/Article/details/gthcihwqxc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gturiykqlu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hongshengwenyu.top/Article/details/gtjecwxguk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jyoumei.cn/Article/details/gtdmmftagf.html


<!-- 参考信息 -->