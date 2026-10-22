代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zdqjudy.top/Article/details/gtftbdgaqk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.mhx1999.top/Article/details/gtiemhabkv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gtqvewmaes.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hammf.cn/Article/details/gtzjhzovya.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgjmvhptg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.feifeiyinyue.top/Article/details/gttlijbmmx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.c1oappe.top/Article/details/gtkfwzyydq.html

[F08] 遍历目录
来源：http://dali.chenzaomai.com/Article/details/gtzzyreajd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cashguo.top/Article/details/gtiyexobjl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.9152youxi.cn/Article/details/gtlyeybwxt.html

JS:   fs.readdirSync("dir")
来源：http://dali.9152youxi.cn/Article/details/gtberchyrw.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj20258.top/Article/details/gtxdxvtzqr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gtpdsipklf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shuidangran.top/Article/details/gttbztxmlp.html

Ruby: Dir.children("dir")
来源：http://dali.ppjwa.cn/Article/details/gtxvsokbbx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.daria6918.cn/Article/details/gtufpileaf.html

[F09] 获取文件大小
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmsuqqxgh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtvvdbtwnk.html

PHP:  filesize("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtqfzfouho.html

JS:   fs.statSync("a.txt").size
来源：http://dali.vqdsnc.cn/Article/details/gtoihgdayl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gtyiiqhcqx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtvamrqcss.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.fengsongda.top/Article/details/gtemfkydic.html

Ruby: File.size("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtpytxwlmb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hongshengwenyu.top/Article/details/gtgaasmthf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnemtoajf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtrkbbfjqv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtnazatixb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtblxzdxuk.html

TS:   path.extname("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtcrqyzerk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhoulong.xyz/Article/details/gtrqcdtzdo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtcjdbrgkn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtblcoejgb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtxvmrqsda.html

[F11] 复制与移动文件
来源：http://dali.hnqzz.top/Article/details/gtlffonwfc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtyuroaoad.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtvbuvrref.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtgabnefuk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gttpwpaqyf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.c1oappe.top/Article/details/gtndxjxdjc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhengqikj.top/Article/details/gtfeingzil.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkxfczbko.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gzhubu.top/Article/details/gtggfwqmkp.html

[F12] CSV 读写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaiiyvbbd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.iojbl.cn/Article/details/gtntfyogbi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.daxiang520.top/Article/details/gthkmkkvtz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yongpay.top/Article/details/gtkwmzujpr.html

TS:   // 同上
来源：http://dali.zhengqikj.top/Article/details/gttmwhqnjc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jyoumei.cn/Article/details/gtfpkukuxp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hfpthk.cn/Article/details/gthqzbhwyy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ivvv.top/Article/details/gtlvzpisac.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cqqwz.cn/Article/details/gtelofprir.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtnzmgcfls.html

G. 面向对象
来源：http://dali.jyoumei.cn/Article/details/gtsppwwcyx.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gttoiwujcx.html

[G01] 定义类
来源：http://dali.iojbl.cn/Article/details/gtyftbuugp.html

Py:   class User: pass
来源：http://dali.gogol.net.cn/Article/details/gtbjxzvxby.html

PHP:  class User {}
来源：http://dali.wangdashe.top/Article/details/gtveqozvqy.html

JS:   class User {}
来源：http://dali.shuidangran.top/Article/details/gtjbhrsdng.html

TS:   class User { name: string = ""; }
来源：http://dali.ydzc1.top/Article/details/gtwvozpcwm.html

Java: class User {}
来源：http://dali.hnqzz.top/Article/details/gtqukrashe.html

Go:   type User struct { Name string }
来源：http://dali.andypj.xyz/Article/details/gtfemvfcxi.html

Ruby: class User; end
来源：http://dali.gaohongyu789.top/Article/details/gtivxksrvk.html

C#:   class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtjlznvxsq.html

[G02] 构造函数
来源：http://dali.shuidangran.top/Article/details/gtpdfpzpde.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cucudq.cn/Article/details/gtiayzhohq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cheryme.top/Article/details/gtmiwpmrvc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gtcfoqkfsx.html

TS:   constructor(public name: string) {}
来源：http://dali.yuxming.cn/Article/details/gtxaxiqhaq.html

Java: User(String name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtyvlcsare.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhixingplan.top/Article/details/gtfgptkmge.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ivvv.top/Article/details/gtvgwkhahj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtnmlnrpgo.html

[G03] 实例属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfwtlfwg.html

Py:   self.name = "x"
来源：http://dali.jinqigufen.top/Article/details/gtmeirddjz.html

PHP:  public string $name = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gthdutddhl.html

JS:   this.name = "x";
来源：http://dali.guannengcc.top/Article/details/gtnfkhemmv.html

TS:   name: string = "x";
来源：http://dali.cqqwz.cn/Article/details/gtnphyktpi.html

Java: private String name;
来源：http://dali.ivvv.top/Article/details/gtozvgpdbs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.9152youxi.cn/Article/details/gtptkmjtif.html

Ruby: @name = "x"
来源：http://dali.hnxiangtu.top/Article/details/gtyrseorau.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.bjfxy.top/Article/details/gtczpklxby.html

[G04] 定义方法
来源：http://dali.yongpay.top/Article/details/gtkvoppprr.html

Py:   def greet(self): return self.name
来源：http://dali.yvedp.cn/Article/details/gthoaplubm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gtpqgfqnwe.html

JS:   greet() { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtzkpkelid.html

TS:   greet(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtahlhgqbn.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqhpdblu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gtujosuftj.html

Ruby: def greet; @name; end
来源：http://dali.0kj1m.cn/Article/details/gtgchdoeee.html

C#:   public string Greet() => Name;
来源：http://dali.aizwys.cn/Article/details/gtnsazhcqt.html

[G05] 继承
来源：http://dali.ehwqpu.com/Article/details/gttkwpkzzk.html

Py:   class Admin(User): pass
来源：http://dali.chenjidiqi.icu/Article/details/gtvrzuqyjl.html

PHP:  class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtmdnvwmqg.html

JS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtkszezsyi.html

TS:   class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtpbqejbsa.html

Java: class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtrjczqnvm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gogol.net.cn/Article/details/gtlimikbit.html

Ruby: class Admin < User; end
来源：http://dali.gotoacloud.top/Article/details/gtpstvrkba.html

C#:   class Admin : User {}
来源：http://dali.ybcxt.top/Article/details/gtzsjdmsan.html

[G06] 重写方法
来源：http://dali.gotoacloud.top/Article/details/gtiubvfcju.html

Py:   def greet(self): return "admin"
来源：http://dali.nanxinkj.top/Article/details/gtfiwmktbs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtsyrlzqbq.html

JS:   greet() { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtfkwscidj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtgkrfcjkg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtsidhoscx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cashguo.top/Article/details/gtdemxzjpr.html

Ruby: def greet; "admin"; end
来源：http://dali.fzhhl.top/Article/details/gtlvxhxwpz.html

C#:   public override string Greet() => "admin";
来源：http://dali.cqqwz.cn/Article/details/gtjxmiomhp.html

[G07] 调用父类方法
来源：http://dali.hammf.cn/Article/details/gtbrzmjddg.html

Py:   super().greet()
来源：http://dali.shzxlz.cn/Article/details/gtijtevplw.html

PHP:  parent::greet();
来源：http://dali.jianghu66.top/Article/details/gtifktshoe.html

JS:   super.greet();
来源：http://dali.jqgfzy.top/Article/details/gtfaikkfjl.html

TS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gtajilgwzr.html

Java: super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtajwhdvud.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ivvv.top/Article/details/gtnpfwdbtl.html

Ruby: super
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhjguazf.html

C#:   base.Greet();
来源：http://dali.ybcxt.top/Article/details/gtvpucvyak.html

[G08] 静态方法与属性
来源：http://dali.snrcjt.cn/Article/details/gtikcqsrmg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guannengcc.top/Article/details/gtqhudsjtv.html

PHP:  public static function f() {}
来源：http://dali.andypj.xyz/Article/details/gtslkgzasp.html

JS:   static f() {}
来源：http://dali.xuanzx.com/Article/details/gtussxjgsd.html

TS:   static f(): void {}
来源：http://dali.haohaochexian.top/Article/details/gtxrepplsz.html

Java: static void f() {}
来源：http://dali.xinyue.icu/Article/details/gtvxmhqqdr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.pengpengdd.cyou/Article/details/gtaewxubyf.html

Ruby: def self.f; end
来源：http://dali.daxiang520.top/Article/details/gtlusohdxq.html

C#:   public static void F() {}
来源：http://dali.daxiang520.top/Article/details/gtrrmuqtjt.html

[G09] 接口 / 抽象类
来源：http://dali.mhx1999.top/Article/details/gtvubcdsqd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ybcxt.top/Article/details/gtosubmovy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hongshengwenyu.top/Article/details/gtczekjxxb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigufen.top/Article/details/gtwtbqhvrr.html

TS:   interface Shape { area(): number; }
来源：http://dali.cucudq.cn/Article/details/gtrexshxeg.html

Java: interface Shape { double area(); }
来源：http://dali.daria6918.cn/Article/details/gtpumdkyov.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hysaishi.cn/Article/details/gtbizhndps.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258.top/Article/details/gtnnjvqtpk.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtomtwxxta.html

[G10] 访问控制
来源：http://dali.pycfn.com/Article/details/gtwwlzlqwx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.316326.xyz/Article/details/gtisvotfcm.html

PHP:  public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtzgfzeazu.html

JS:   #private 字段；其余公开
来源：http://dali.shangyingyoupin.top/Article/details/gtlpinabet.html

TS:   public / protected / private
来源：http://dali.havefunace.top/Article/details/gthrohpvfc.html

Java: public / protected / private / 默认包级
来源：http://dali.zhoulong.xyz/Article/details/gtlekqvghi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xziqi.cn/Article/details/gtzrioajgh.html

Ruby: public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtjiqkqwmr.html

C#:   public / protected / private / internal
来源：http://dali.chenlongwang.top/Article/details/gtginssvgb.html

[G11] getter / setter
来源：http://dali.shzxlz.cn/Article/details/gtubhznjzo.html

Py:   @property 与 @x.setter
来源：http://dali.yuxming.cn/Article/details/gtonuomdrg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gtgnqrbfbh.html

JS:   get name() { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gtixgilxdg.html

TS:   get name(): string { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gtyarbfezq.html

Java: public String getName() { return name; }
来源：http://dali.daria6918.cn/Article/details/gtdooparqg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gteixxemrl.html

Ruby: attr_accessor :name
来源：http://dali.shuidangran.top/Article/details/gtqfbcxuuy.html

C#:   public string Name { get; set; }
来源：http://dali.yvedp.cn/Article/details/gtvjipjllp.html

[G12] 对象转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtouzhlrar.html

Py:   def __str__(self): return self.name
来源：http://dali.zhiwuduotai.top/Article/details/gtxoewwyxv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gthergfofb.html

JS:   toString() { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcriopxas.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtkwjufyfg.html

Java: @Override public String toString() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtednnnluh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gtvitmjdoz.html

Ruby: def to_s; @name; end
来源：http://dali.zycfv.cn/Article/details/gtrywbtosg.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258888.top/Article/details/gtpvscdtsy.html

[G13] 判断对象类型
来源：http://dali.vqdsnc.cn/Article/details/gtwwloppft.html

Py:   isinstance(u, User)
来源：http://dali.316326.xyz/Article/details/gtafyyfacb.html

PHP:  $u instanceof User
来源：http://dali.hammf.cn/Article/details/gtctqfackc.html

JS:   u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtsfvzcnkz.html

TS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtwkyfeaza.html

Java: u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtpubtyvky.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sxryk.cn/Article/details/gtpeaxrvdu.html

Ruby: u.is_a?(User)
来源：http://dali.sxryk.cn/Article/details/gtpvyelrww.html

C#:   u is User
来源：http://dali.yvedp.cn/Article/details/gtkqeerdka.html

[G14] 数据类 / record
来源：http://dali.sweek.top/Article/details/gtjgmqvqwj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj202588.top/Article/details/gtawzjsdlf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnqzz.top/Article/details/gtlzygpsab.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hongshengwenyu.top/Article/details/gttcnvlrzx.html

TS:   type User = { name: string; age: number };
来源：http://dali.kuanghao11.cn/Article/details/gtkelddwxg.html

Java: record User(String name, int age) {}
来源：http://dali.quarkkingdee.top/Article/details/gtggmbtavc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yonumen.top/Article/details/gtywvswkui.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cucudq.cn/Article/details/gtsmtubzgc.html

C#:   record User(string Name, int Age);
来源：http://dali.gzhubu.top/Article/details/gtyjxgtwqf.html

[G15] 枚举
来源：http://dali.pengpengdd.cyou/Article/details/gtlrbngkdi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fengsongda.top/Article/details/gtbfeaancq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.kuanghao11.cn/Article/details/gtykbifzpg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shuidangran.top/Article/details/gthwvcqbfm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gthbvcjcme.html

Java: enum Color { RED, GREEN }
来源：http://dali.meibo888.top/Article/details/gtzhdryzgb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tianlin.xyz/Article/details/gtvbpfhxkz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.daria6918.cn/Article/details/gtdlkduwjw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gtqmqiyvfy.html

[G16] 对象转数组 / 字典
来源：http://dali.zdqjudy.top/Article/details/gtlyxmuxqt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hnxiangtu.top/Article/details/gtmjdrnodc.html

PHP:  get_object_vars($obj);
来源：http://dali.daria6918.cn/Article/details/gtcnmqcbav.html

JS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtwerupzbc.html

TS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubfhmogf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tian-w.cn/Article/details/gttxwhwwgx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.birdmap.top/Article/details/gtcbfmraxn.html

Ruby: obj.instance_variables
来源：http://dali.yuanzhike.top/Article/details/gtejkizora.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gtadsjykra.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtxdrqqbpb.html

H. 异常与错误处理
来源：http://dali.zhongyouzk.top/Article/details/gtombylnsb.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtjqqlxnaa.html

[H01] try / catch 基础
来源：http://dali.pengpengdd.cyou/Article/details/gtudlxkghi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xinyue.icu/Article/details/gttobcwthu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jiagoushi.top/Article/details/gtyycutvfi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gtgivbbrmd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gtwxbgzgxx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yongpay.top/Article/details/gtgexeiotf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cdnleiting.top/Article/details/gtzmcqoikb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.redwolf501.top/Article/details/gtyfbaejqk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.iojbl.cn/Article/details/gtmlakglet.html

[H02] finally / ensure 收尾
来源：http://dali.yuanzhike.top/Article/details/gtdkdmdrij.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhengqikj.top/Article/details/gtnrzkardf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtgvmwebth.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtfkoupidw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtrhaldmzf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtkkawujsl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jlsjyb.cn/Article/details/gtmfrzhnjv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj20258888.top/Article/details/gtkfvpfjxh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gttemaofgd.html

[H03] 主动抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gtnyzvxjjc.html

Py:   raise ValueError("错误信息")
来源：http://dali.jlsjyb.cn/Article/details/gtlodnehkq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtltslkahr.html

JS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtanzmvygd.html

TS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtvksyuknc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtejvgxbzl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cashguo.top/Article/details/gtrxljmlfb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnqzz.top/Article/details/gtochdanhv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtbicepvfa.html

[H04] 自定义异常类型
来源：http://dali.shuidangran.top/Article/details/gtpxxmwuwi.html

Py:   class MyError(Exception): pass
来源：http://dali.vqdsnc.cn/Article/details/gtltcamphx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hammf.cn/Article/details/gtfyydphly.html

JS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gtsfdfrrdv.html

TS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtvdknyyvo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkzjrqtan.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.c1oappe.top/Article/details/gtxgbltykh.html

Ruby: class MyError < StandardError; end
来源：http://dali.ivvv.top/Article/details/gttqtwyejo.html

C#:   class MyException : Exception {}
来源：http://dali.wangshuangyany.cn/Article/details/gtybpuydvq.html

[H05] 捕获特定类型
来源：http://dali.havefunace.top/Article/details/gtdqdyofet.html

Py:   except ValueError as e:
来源：http://dali.aibaodan.cn/Article/details/gtfqpxcsdc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuanzx.com/Article/details/gtktgmrdky.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.vqdsnc.cn/Article/details/gtvmfzpzab.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gtliiihnfb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hfpthk.cn/Article/details/gtamuodcbm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xuanzx.com/Article/details/gtgahtyzld.html

Ruby: rescue ArgumentError => e
来源：http://dali.kuanghao11.cn/Article/details/gtivgcurmb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhongyouzk.top/Article/details/gtmzubzvaz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hfpthk.cn/Article/details/gtzgyodqbu.html

Py:   value = d.get("k") or default
来源：http://dali.hongshengwenyu.top/Article/details/gtujgirwez.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yueranfly.top/Article/details/gtbfmcsjau.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tian-w.cn/Article/details/gtvicouwyr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gtgslzbago.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hammf.cn/Article/details/gttmxklbqa.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigfzy.top/Article/details/gtfrmtzzpp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnxiangtu.top/Article/details/gtejwhhjxd.html

C#:   obj?.A?.B ?? default
来源：http://dali.xinyue.icu/Article/details/gtsixqljik.html

[H07] 断言
来源：http://dali.vqdsnc.cn/Article/details/gtfnkvjclr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sxryk.cn/Article/details/gtszbbgjwi.html

PHP:  assert($x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzaenwpit.html

JS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtzahsvzoy.html

TS:   console.assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkitsbms.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jiagoushi.top/Article/details/gtzinoizon.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.c1oappe.top/Article/details/gtxcpllthw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.bjfxy.top/Article/details/gtmtkyjvxt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gtejdlhwtc.html

[H08] 获取错误信息与堆栈
来源：http://dali.hongshengwenyu.top/Article/details/gtkzelwdxk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yonumen.top/Article/details/gtbfylmvpw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.iojbl.cn/Article/details/gtowhhzqkt.html

JS:   e.message;  e.stack
来源：http://dali.aibaodan.cn/Article/details/gtvlwyjqyw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dashuyun.cn/Article/details/gtvuizbpqu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenjidiqi.icu/Article/details/gtzeihhmsb.html

Go:   err.Error()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptnqejlh.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgfzy.top/Article/details/gtaoeajsib.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yvedp.cn/Article/details/gtnaghwfne.html

[H09] 带错误码的异常
来源：http://dali.aizwys.cn/Article/details/gtcvtzkttw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.kuanghao11.cn/Article/details/gtsoixqqqs.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fengsongda.top/Article/details/gtaijakpap.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangshuangyany.cn/Article/details/gtxtglmxlb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fzhhl.top/Article/details/gtwfjudyyb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.9152youxi.cn/Article/details/gtvvdhwqgj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sufxvd.cn/Article/details/gtlyjaufgb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.smart0.xyz/Article/details/gtnqshouwi.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj20258.top/Article/details/gtwehhbaar.html

[H10] 资源自动释放
来源：http://dali.zhixingplan.top/Article/details/gtfnvnjobw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jlsjyb.cn/Article/details/gtcorvhedg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj20258888.top/Article/details/gtbifkstlj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gtngzpnoys.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.c1oappe.top/Article/details/gtzpwzbldm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj202588.top/Article/details/gtjqshscjg.html

Go:   defer f.Close()
来源：http://dali.ivvv.top/Article/details/gtusodyaph.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.9152youxi.cn/Article/details/gtnzuipzft.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ivvv.top/Article/details/gtawgyosxp.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gthnaaxpxo.html

I. 正则表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdohrhvgn.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtebuxxkqr.html

[I01] 判断是否匹配
来源：http://dali.dianchejie.cn/Article/details/gtxmidlldf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtsmlobwhy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tian-w.cn/Article/details/gtfdzkghyp.html

JS:   /\d+/.test(s)
来源：http://dali.yj20258.top/Article/details/gteqchyrlw.html

TS:   /\d+/.test(s)
来源：http://dali.jyoumei.cn/Article/details/gtwsujywgw.html


<!-- 参考信息 -->