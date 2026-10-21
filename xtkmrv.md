代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyemsgwvd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.9152youxi.cn/Article/details/gtjwoyqumc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gtddvcjitz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tanke756.top/Article/details/gttqqynrcw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gzhubu.top/Article/details/gtbifxujyg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.quarkkingdee.top/Article/details/gtzyouwdts.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.0kj1m.cn/Article/details/gtecgibell.html

[F08] 遍历目录
来源：http://dali.daxiang520.top/Article/details/gtcuynuavr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sweek.top/Article/details/gtuuwnyqzw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shangyingyoupin.top/Article/details/gtspiwnuhf.html

JS:   fs.readdirSync("dir")
来源：http://dali.meibo888.top/Article/details/gtnsxxeoob.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtlbweoxfe.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gtxfxktoza.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.snrcjt.cn/Article/details/gtizrrofeb.html

Ruby: Dir.children("dir")
来源：http://dali.sufxvd.cn/Article/details/gtikafktpi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjrduedl.html

[F09] 获取文件大小
来源：http://dali.smart0.xyz/Article/details/gtclntueni.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtkgsvfitl.html

PHP:  filesize("a.txt");
来源：http://dali.havefunace.top/Article/details/gtappqryhv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.vqdsnc.cn/Article/details/gtmrfszbll.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gtbfuyzwqm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gthqkoqvla.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.vqdsnc.cn/Article/details/gttthvdqxt.html

Ruby: File.size("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtxfhqlsmu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gzhubu.top/Article/details/gtopgvreat.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fengsongda.top/Article/details/gtcduojxyc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtiucdvgiq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hysaishi.cn/Article/details/gthzccwvak.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtrseoopym.html

TS:   path.extname("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtsezavmhr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.snrcjt.cn/Article/details/gtcaznkmfr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtxokbcuoz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtfridtlor.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtdlodnwnw.html

[F11] 复制与移动文件
来源：http://dali.c1oappe.top/Article/details/gtymxokqtf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtwbjedoke.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtwlwnupjo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtbddtnifm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtlfqcuyls.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sxryk.cn/Article/details/gtgqodmgiu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.bjfxy.top/Article/details/gtranjlzrz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtwlusyjdv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhengqikj.top/Article/details/gtrooxtqse.html

[F12] CSV 读写
来源：http://dali.ivvv.top/Article/details/gtcjuevang.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.9152youxi.cn/Article/details/gtrikkjrqz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.kuanghao11.cn/Article/details/gtviyardkd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daxiang520.top/Article/details/gtmrarwuzm.html

TS:   // 同上
来源：http://dali.nanxuanxn.top/Article/details/gtgwvebnkx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jiagoushi.top/Article/details/gtyhhuxjzt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.haohaochexian.top/Article/details/gtwzhdjstg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jlsjyb.cn/Article/details/gtzxzvelux.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhengqikj.top/Article/details/gtzpocewiz.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdyedvrbh.html

G. 面向对象
来源：http://dali.wangshuangyany.cn/Article/details/gtabkopyra.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtgunjoyoq.html

[G01] 定义类
来源：http://dali.yueranfly.top/Article/details/gtwezcutee.html

Py:   class User: pass
来源：http://dali.hywenlv.cn/Article/details/gtddzsuxby.html

PHP:  class User {}
来源：http://dali.aibaodan.cn/Article/details/gtlhxzzmzc.html

JS:   class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtmwfolw.html

TS:   class User { name: string = ""; }
来源：http://dali.snrcjt.cn/Article/details/gteblhrurr.html

Java: class User {}
来源：http://dali.cucudq.cn/Article/details/gtjmdtlaqw.html

Go:   type User struct { Name string }
来源：http://dali.cqqwz.cn/Article/details/gtnesmohti.html

Ruby: class User; end
来源：http://dali.yonumen.top/Article/details/gtyqqrluyd.html

C#:   class User {}
来源：http://dali.sweek.top/Article/details/gtpythlltd.html

[G02] 构造函数
来源：http://dali.zhongyouzk.top/Article/details/gtfhaxofgj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hywenlv.cn/Article/details/gtqrqwoamt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nanxuanxn.top/Article/details/gtgjterlks.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sxryk.cn/Article/details/gtwtagpzbg.html

TS:   constructor(public name: string) {}
来源：http://dali.jqgufenzy.top/Article/details/gtixdyemsz.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtsjllgvvx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shzxlz.cn/Article/details/gtpvepesyc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daria6918.cn/Article/details/gtpmdxebed.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aizwys.cn/Article/details/gtkbrqlauh.html

[G03] 实例属性
来源：http://dali.sxryk.cn/Article/details/gtkopuuikg.html

Py:   self.name = "x"
来源：http://dali.havefunace.top/Article/details/gttkrtkjzl.html

PHP:  public string $name = "x";
来源：http://dali.ybcxt.top/Article/details/gtffjgkdre.html

JS:   this.name = "x";
来源：http://dali.hammf.cn/Article/details/gtzhsiiezc.html

TS:   name: string = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvorrkxz.html

Java: private String name;
来源：http://dali.c1oappe.top/Article/details/gtbzxxutqp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gotoacloud.top/Article/details/gterxzcnwz.html

Ruby: @name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gtefztoccz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jiagoushi.top/Article/details/gtohakjqiz.html

[G04] 定义方法
来源：http://dali.shuidangran.top/Article/details/gtdxjfzevj.html

Py:   def greet(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gttnyskjqt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtraehgksy.html

JS:   greet() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtymdixszq.html

TS:   greet(): string { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtmopwipsg.html

Java: String greet() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnsmcyab.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gtsoeukeyp.html

Ruby: def greet; @name; end
来源：http://dali.0kj1m.cn/Article/details/gttkasvpfo.html

C#:   public string Greet() => Name;
来源：http://dali.wangdashe.top/Article/details/gtdpockdvt.html

[G05] 继承
来源：http://dali.nanxinkj.top/Article/details/gtuktqetcb.html

Py:   class Admin(User): pass
来源：http://dali.zhixingplan.top/Article/details/gtvdlkjadl.html

PHP:  class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtshginrgy.html

JS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtphjrazqa.html

TS:   class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtjiqhrysq.html

Java: class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtqmtginuk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ivvv.top/Article/details/gtkwqnpejk.html

Ruby: class Admin < User; end
来源：http://dali.ydzc1.top/Article/details/gtxqxvrbyt.html

C#:   class Admin : User {}
来源：http://dali.ybcxt.top/Article/details/gtxkyekavd.html

[G06] 重写方法
来源：http://dali.shzxlz.cn/Article/details/gtwblrzuay.html

Py:   def greet(self): return "admin"
来源：http://dali.shanyushiyangtech.top/Article/details/gttzmlydam.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtzgcyxtuk.html

JS:   greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtnwzkzdwd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gtnmjewbqz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtipblftti.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.c1oappe.top/Article/details/gtztaneumj.html

Ruby: def greet; "admin"; end
来源：http://dali.birdmap.top/Article/details/gtvzmyzcfg.html

C#:   public override string Greet() => "admin";
来源：http://dali.hysaishi.cn/Article/details/gtklvmxiet.html

[G07] 调用父类方法
来源：http://dali.jiagoushi.top/Article/details/gtayxlgfio.html

Py:   super().greet()
来源：http://dali.chenzaomai.com/Article/details/gtgmwzdeue.html

PHP:  parent::greet();
来源：http://dali.svipenyu.cn/Article/details/gtumqyverb.html

JS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gtxaxfpfni.html

TS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gtczpwdmfe.html

Java: super.greet();
来源：http://dali.xylfe.cn/Article/details/gttvfjbwdz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenzaomai.com/Article/details/gtacaqmjfd.html

Ruby: super
来源：http://dali.9152youxi.cn/Article/details/gtxjonigaw.html

C#:   base.Greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gthxpmgyml.html

[G08] 静态方法与属性
来源：http://dali.nanxinkj.top/Article/details/gtrotvphui.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnxiangtu.top/Article/details/gtugcwkrrg.html

PHP:  public static function f() {}
来源：http://dali.xylfe.cn/Article/details/gtfvzyqrza.html

JS:   static f() {}
来源：http://dali.bjfxy.top/Article/details/gthzijwtjc.html

TS:   static f(): void {}
来源：http://dali.yangfankeji.com/Article/details/gtixowytls.html

Java: static void f() {}
来源：http://dali.zhengqikj.top/Article/details/gttcgwhtal.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nwbrower.top/Article/details/gtigepbcqx.html

Ruby: def self.f; end
来源：http://dali.shzxlz.cn/Article/details/gtrqbdknhs.html

C#:   public static void F() {}
来源：http://dali.cqqwz.cn/Article/details/gtdhxjebaf.html

[G09] 接口 / 抽象类
来源：http://dali.jiagoushi.top/Article/details/gtcfnkavbc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tianlin.xyz/Article/details/gtqsiuifjr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daxiang520.top/Article/details/gthmoamocl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cqqwz.cn/Article/details/gttmevypih.html

TS:   interface Shape { area(): number; }
来源：http://dali.aibaodan.cn/Article/details/gtvteidoyq.html

Java: interface Shape { double area(); }
来源：http://dali.sxryk.cn/Article/details/gtmyzzdglr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttaugezmy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nwbrower.top/Article/details/gtiwlixbzh.html

C#:   interface IShape { double Area(); }
来源：http://dali.gotoacloud.top/Article/details/gtgczmxyzp.html

[G10] 访问控制
来源：http://dali.aibaodan.cn/Article/details/gtlppggavi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangshuangyany.cn/Article/details/gtczkzsmvj.html

PHP:  public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlpstczxo.html

JS:   #private 字段；其余公开
来源：http://dali.guowangkeji.top/Article/details/gtjhpoijpo.html

TS:   public / protected / private
来源：http://dali.cheryme.top/Article/details/gtumhujgsy.html

Java: public / protected / private / 默认包级
来源：http://dali.c1oappe.top/Article/details/gtwrflmazs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.andypj.xyz/Article/details/gttbswlqia.html

Ruby: public / protected / private
来源：http://dali.redwolf501.top/Article/details/gtamrcxiih.html

C#:   public / protected / private / internal
来源：http://dali.yj20258888.top/Article/details/gtdbalwqjj.html

[G11] getter / setter
来源：http://dali.smart0.xyz/Article/details/gtpthozhzv.html

Py:   @property 与 @x.setter
来源：http://dali.zhiwuduotai.top/Article/details/gtiitrumsx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gtyzjyhcok.html

JS:   get name() { return this._name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrvayuzay.html

TS:   get name(): string { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gthigqotzn.html

Java: public String getName() { return name; }
来源：http://dali.ivvv.top/Article/details/gtoukjgtdu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gttkvogoso.html

Ruby: attr_accessor :name
来源：http://dali.yanxiufei.cn/Article/details/gtrjepynce.html

C#:   public string Name { get; set; }
来源：http://dali.gotoacloud.top/Article/details/gtdvyincvs.html

[G12] 对象转字符串
来源：http://dali.c1oappe.top/Article/details/gtkxulfdkz.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258888.top/Article/details/gtcwqhjivs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuaiulpmi.html

JS:   toString() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtbuhbbdae.html

TS:   toString(): string { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtnysdvuhx.html

Java: @Override public String toString() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtrdmcxnuz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gthwvbwhaa.html

Ruby: def to_s; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gtotnfpotw.html

C#:   public override string ToString() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gtpdiwkyjm.html

[G13] 判断对象类型
来源：http://dali.yangfankeji.com/Article/details/gtoinxjsys.html

Py:   isinstance(u, User)
来源：http://dali.sxryk.cn/Article/details/gtgwsinjkw.html

PHP:  $u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtirajejtu.html

JS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtgfkprolt.html

TS:   u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gtqtwdsgxo.html

Java: u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtnsivhhtq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cucudq.cn/Article/details/gtobnhkmrb.html

Ruby: u.is_a?(User)
来源：http://dali.fzhhl.top/Article/details/gtezypsfmt.html

C#:   u is User
来源：http://dali.yongpay.top/Article/details/gtkfgfafdt.html

[G14] 数据类 / record
来源：http://dali.jlsjyb.cn/Article/details/gtcjazxmej.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sxryk.cn/Article/details/gtsemwjoaw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.daria6918.cn/Article/details/gtbowxtpkt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.fengsongda.top/Article/details/gtvnjkxhij.html

TS:   type User = { name: string; age: number };
来源：http://dali.yongpay.top/Article/details/gtrljqgioc.html

Java: record User(String name, int age) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxrmwbncd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.havefunace.top/Article/details/gtwnmwemwh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.iojbl.cn/Article/details/gtfluzodcx.html

C#:   record User(string Name, int Age);
来源：http://dali.pycfn.com/Article/details/gtztdwbchi.html

[G15] 枚举
来源：http://dali.guowangkeji.top/Article/details/gtxxgfoeqv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shangyingyoupin.top/Article/details/gtaopvuoch.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jiagoushi.top/Article/details/gtivjopglc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gaohongyu789.top/Article/details/gtfwcszfyk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmyahuznm.html

Java: enum Color { RED, GREEN }
来源：http://dali.andypj.xyz/Article/details/gtqpsuqhji.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangdashe.top/Article/details/gtpqsifkph.html

Ruby: Color = %i[red green].freeze
来源：http://dali.daxiang520.top/Article/details/gtljndlszn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gthgnmmixq.html

[G16] 对象转数组 / 字典
来源：http://dali.xziqi.cn/Article/details/gtwedqguva.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yvedp.cn/Article/details/gtbxgjvoul.html

PHP:  get_object_vars($obj);
来源：http://dali.cucudq.cn/Article/details/gtuelrfxov.html

JS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gtwzerhobk.html

TS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gtzloxzsig.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.smart0.xyz/Article/details/gtiplhhahc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cucudq.cn/Article/details/gtswsnldsq.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gtbysxktmz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbtztpiy.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtczhxqjqc.html

H. 异常与错误处理
来源：http://dali.shangyingyoupin.top/Article/details/gttejsgevh.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtzismyefo.html

[H01] try / catch 基础
来源：http://dali.meibo888.top/Article/details/gtvpiuwlyy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.wangdashe.top/Article/details/gtmxyfwrfg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ybcxt.top/Article/details/gtdqshadfj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gtoswibcuj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyerhofhs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cheryme.top/Article/details/gtuweutmbg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.feifeiyinyue.top/Article/details/gtzjoqxldp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ydzc1.top/Article/details/gtobilvfhj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ppjwa.cn/Article/details/gtkkytcjdt.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258888.top/Article/details/gtepksrrry.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.birdmap.top/Article/details/gtasaypglx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtdqkqjnoy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtytcgiamg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtmniezoni.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtpvozgfav.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ivvv.top/Article/details/gtpgtnaqbs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.vqdsnc.cn/Article/details/gtadkcbxld.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ivvv.top/Article/details/gthjhpkcva.html

[H03] 主动抛出异常
来源：http://dali.jlsjyb.cn/Article/details/gtmypyhyux.html

Py:   raise ValueError("错误信息")
来源：http://dali.sxryk.cn/Article/details/gtnnjdfjrq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmlulmrgj.html

JS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtcqnizddu.html

TS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtoknhjmiq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtiiaaqxnr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shangyingyoupin.top/Article/details/gtqikdvygx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuanzhike.top/Article/details/gtsmujlvkm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gttcporffw.html

[H04] 自定义异常类型
来源：http://dali.zhixingplan.top/Article/details/gtqxprswat.html

Py:   class MyError(Exception): pass
来源：http://dali.sxryk.cn/Article/details/gtgzualnke.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gtmfhjcnrf.html

JS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gteazjkdvf.html

TS:   class MyError extends Error {}
来源：http://dali.aizwys.cn/Article/details/gtlavzawej.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtksmqwdvl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhoulong.xyz/Article/details/gtjwkfzdgt.html

Ruby: class MyError < StandardError; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxdeftlw.html

C#:   class MyException : Exception {}
来源：http://dali.9152youxi.cn/Article/details/gtbbkonxno.html

[H05] 捕获特定类型
来源：http://dali.aizwys.cn/Article/details/gtwvrgvfsg.html

Py:   except ValueError as e:
来源：http://dali.yongpay.top/Article/details/gtahxmwudt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gaohongyu789.top/Article/details/gthtwroewb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gtdjdemgsg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gtunnjsueq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tian-w.cn/Article/details/gtzyzboobc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.9152youxi.cn/Article/details/gtoftlisuj.html

Ruby: rescue ArgumentError => e
来源：http://dali.shzxlz.cn/Article/details/gtmxecelpe.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fengsongda.top/Article/details/gtlnfqhydp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cheryme.top/Article/details/gtlcupwrkd.html

Py:   value = d.get("k") or default
来源：http://dali.xuanzx.com/Article/details/gtynutznnn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangdashe.top/Article/details/gtwiprdmyu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hysaishi.cn/Article/details/gtzzumhwda.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gtxubxyfzm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jyoumei.cn/Article/details/gtciqdwusy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.svipenyu.cn/Article/details/gtgackjhke.html

Ruby: d&.dig(:a, :b)
来源：http://dali.0kj1m.cn/Article/details/gtnekutqup.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gticfdszub.html

[H07] 断言
来源：http://dali.yongpay.top/Article/details/gtzyhlfmrn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.bjfxy.top/Article/details/gtrjzfyuqf.html

PHP:  assert($x > 0);
来源：http://dali.yj20258.top/Article/details/gtngtlekda.html

JS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gtlzeslsiz.html

TS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtsbffnxjo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jlsjyb.cn/Article/details/gtknfqimwc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guowangkeji.top/Article/details/gttaiwkpoj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cqqwz.cn/Article/details/gtsooigebt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gtfzhxwuwm.html

[H08] 获取错误信息与堆栈
来源：http://dali.0kj1m.cn/Article/details/gtmjqeznje.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhengqikj.top/Article/details/gtqwprhjuc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.daria6918.cn/Article/details/gtjjgzberp.html

JS:   e.message;  e.stack
来源：http://dali.daxiang520.top/Article/details/gtfkikonoq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxinkj.top/Article/details/gtcyiscgpl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.aizwys.cn/Article/details/gtvxcfhvch.html

Go:   err.Error()
来源：http://dali.jqgufenzy.top/Article/details/gtjbtottea.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigufen.top/Article/details/gtvqneylmp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ppjwa.cn/Article/details/gtajqtocyr.html

[H09] 带错误码的异常
来源：http://dali.yj20258.top/Article/details/gtzmfltvwr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.316326.xyz/Article/details/gtbhbbcovh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jyoumei.cn/Article/details/gtjctplyyc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenlongwang.top/Article/details/gtoteuihid.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ehwqpu.com/Article/details/gtpberuvio.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sysykeji.top/Article/details/gtglafigyd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.pengpengdd.cyou/Article/details/gtyowfccom.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jlsjyb.cn/Article/details/gtobkdtuac.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinqigufen.top/Article/details/gtoyqtlgty.html

[H10] 资源自动释放
来源：http://dali.zhongyouzk.top/Article/details/gtxvlnurdy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yvedp.cn/Article/details/gtzahghhop.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yvedp.cn/Article/details/gtatmeegnj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gtsqesfdrg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gthwrzrkvv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnqzz.top/Article/details/gtlbzfxisx.html

Go:   defer f.Close()
来源：http://dali.andypj.xyz/Article/details/gtvafxuwfl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ehwqpu.com/Article/details/gtlavardnr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtmzudayli.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtrikwbzzn.html

I. 正则表达式
来源：http://dali.shzxlz.cn/Article/details/gtpakruyan.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtxwwscism.html

[I01] 判断是否匹配
来源：http://dali.nanxinkj.top/Article/details/gtwneufszd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.birdmap.top/Article/details/gtpkrqdeaz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.bjfxy.top/Article/details/gtnwfcuaev.html

JS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gtaexvzhwi.html

TS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gtchzqpent.html


<!-- 参考信息 -->