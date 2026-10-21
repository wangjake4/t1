代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yanxiufei.cn/Article/details/gtlmbnbiub.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cucudq.cn/Article/details/gtukcwqaho.html

Ruby: Dir.children("dir")
来源：http://dali.tian-w.cn/Article/details/gtydhyilya.html

C#:   Directory.GetFiles("dir")
来源：http://dali.daria6918.cn/Article/details/gtmyogbnmn.html

[F09] 获取文件大小
来源：http://dali.ybcxt.top/Article/details/gtljfkhrye.html

Py:   os.path.getsize("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gttmtovkdy.html

PHP:  filesize("a.txt");
来源：http://dali.yongpay.top/Article/details/gtsyfaatga.html

JS:   fs.statSync("a.txt").size
来源：http://dali.guowangkeji.top/Article/details/gtwbefggdu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gtctueocax.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtpjnsnbik.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jlsjyb.cn/Article/details/gtfzadbzxm.html

Ruby: File.size("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkamocpuc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.bjfxy.top/Article/details/gtqclksryw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigufen.top/Article/details/gtllucgikw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtdblwxfwz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.daxiang520.top/Article/details/gtghducuoa.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtvvfcyyop.html

TS:   path.extname("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtsjesmbmj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tanke756.top/Article/details/gtpuoflanm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtajdntoct.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtomtpofil.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtvqvhjrmk.html

[F11] 复制与移动文件
来源：http://dali.nwbrower.top/Article/details/gtffmnkdrj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtbpjjawwr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.guowangkeji.top/Article/details/gtqzzmrbkc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtyomwduwu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtmkkggkhq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinqigufen.top/Article/details/gtwfhhhbyf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gotoacloud.top/Article/details/gtmsypfdrv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtvnlzbuyu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cqqwz.cn/Article/details/gtlhrjqqup.html

[F12] CSV 读写
来源：http://dali.redwolf501.top/Article/details/gtuhfpqoux.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shangyingyoupin.top/Article/details/gtbkdzlcml.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhiwuduotai.top/Article/details/gtgpmiipwx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gogol.net.cn/Article/details/gtarpoeyop.html

TS:   // 同上
来源：http://dali.jqgufenzy.top/Article/details/gtqjrhshhs.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jiagoushi.top/Article/details/gtlefrpaqi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tian-w.cn/Article/details/gtuokezgxi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gzhubu.top/Article/details/gtelgwonsq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yueranfly.top/Article/details/gtccpclrxb.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtcjjmalnl.html

G. 面向对象
来源：http://dali.haohaochexian.top/Article/details/gtemcohmqs.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gthxeecyya.html

[G01] 定义类
来源：http://dali.zhiwuduotai.top/Article/details/gtjyklisij.html

Py:   class User: pass
来源：http://dali.zdqjudy.top/Article/details/gthulshvap.html

PHP:  class User {}
来源：http://dali.ppjwa.cn/Article/details/gtjwedpfez.html

JS:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtmwuturuz.html

TS:   class User { name: string = ""; }
来源：http://dali.guowangkeji.top/Article/details/gtustpbtra.html

Java: class User {}
来源：http://dali.hnqzz.top/Article/details/gtjzqnjaqt.html

Go:   type User struct { Name string }
来源：http://dali.xylfe.cn/Article/details/gtfrmnrutu.html

Ruby: class User; end
来源：http://dali.cdnleiting.top/Article/details/gtdjwehjql.html

C#:   class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqnggdfp.html

[G02] 构造函数
来源：http://dali.xylfe.cn/Article/details/gtkghgrfjr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tianlin.xyz/Article/details/gtvgbhrypm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yanxiufei.cn/Article/details/gtzysdnrll.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gteneehkjs.html

TS:   constructor(public name: string) {}
来源：http://dali.redwolf501.top/Article/details/gthdugqxrv.html

Java: User(String name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtgblcdfmz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigufen.top/Article/details/gtiyfrqbcl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yvedp.cn/Article/details/gtxowvnlyo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ivvv.top/Article/details/gtytlkncmq.html

[G03] 实例属性
来源：http://dali.hammf.cn/Article/details/gtnketscdb.html

Py:   self.name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfohcbud.html

PHP:  public string $name = "x";
来源：http://dali.yonumen.top/Article/details/gtkurbawlf.html

JS:   this.name = "x";
来源：http://dali.jqgfzy.top/Article/details/gtxkbxjzxd.html

TS:   name: string = "x";
来源：http://dali.gogol.net.cn/Article/details/gtbdawvkdb.html

Java: private String name;
来源：http://dali.pycfn.com/Article/details/gtfwtgjrvc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.andypj.xyz/Article/details/gtlltvwdcm.html

Ruby: @name = "x"
来源：http://dali.tianlin.xyz/Article/details/gtljpxohap.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtzyugnnbx.html

[G04] 定义方法
来源：http://dali.ybcxt.top/Article/details/gtzfpasxoy.html

Py:   def greet(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gtwkzpbiku.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtejfmyudl.html

JS:   greet() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtolyuaatr.html

TS:   greet(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtljhysyfm.html

Java: String greet() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtdpooolbo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtwdsxetgn.html

Ruby: def greet; @name; end
来源：http://dali.quarkkingdee.top/Article/details/gteyvnvsxk.html

C#:   public string Greet() => Name;
来源：http://dali.xziqi.cn/Article/details/gtcqeizrje.html

[G05] 继承
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwpfqlqs.html

Py:   class Admin(User): pass
来源：http://dali.shuidangran.top/Article/details/gtqtfhogzd.html

PHP:  class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtmjdturiv.html

JS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtkicrakeo.html

TS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtdkulbwns.html

Java: class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtercljqjf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuanzx.com/Article/details/gtdnlplyse.html

Ruby: class Admin < User; end
来源：http://dali.316326.xyz/Article/details/gtacjjdxfy.html

C#:   class Admin : User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtwakywogf.html

[G06] 重写方法
来源：http://dali.birdmap.top/Article/details/gtxhomxydi.html

Py:   def greet(self): return "admin"
来源：http://dali.xylfe.cn/Article/details/gtdlpvsrep.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtexuswfiu.html

JS:   greet() { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gthrnufzuu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtmdioptoh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtycjdrsem.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hfpthk.cn/Article/details/gtjnkgqoco.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gtpurpwocy.html

C#:   public override string Greet() => "admin";
来源：http://dali.yongpay.top/Article/details/gtvktpucfy.html

[G07] 调用父类方法
来源：http://dali.hnqzz.top/Article/details/gtffruinwv.html

Py:   super().greet()
来源：http://dali.gaohongyu789.top/Article/details/gtorzlkpzj.html

PHP:  parent::greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtfiklifox.html

JS:   super.greet();
来源：http://dali.dianchejie.cn/Article/details/gtwsuluuio.html

TS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtioadghph.html

Java: super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gtzxwvqdgj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.smart0.xyz/Article/details/gtgnknqhzx.html

Ruby: super
来源：http://dali.ehwqpu.com/Article/details/gtbrphfgeh.html

C#:   base.Greet();
来源：http://dali.ivvv.top/Article/details/gtpzcgvyyv.html

[G08] 静态方法与属性
来源：http://dali.chenlongwang.top/Article/details/gtmrtgacod.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhoulong.xyz/Article/details/gtphbvwvsk.html

PHP:  public static function f() {}
来源：http://dali.fengsongda.top/Article/details/gtzouzhebv.html

JS:   static f() {}
来源：http://dali.tianlin.xyz/Article/details/gtwjlplryt.html

TS:   static f(): void {}
来源：http://dali.yvedp.cn/Article/details/gtgridguzm.html

Java: static void f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtineluogk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.birdmap.top/Article/details/gtajneoxke.html

Ruby: def self.f; end
来源：http://dali.yuxming.cn/Article/details/gtikembrmk.html

C#:   public static void F() {}
来源：http://dali.ydzc1.top/Article/details/gtngqmcgid.html

[G09] 接口 / 抽象类
来源：http://dali.mhx1999.top/Article/details/gtjewgsllh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ppjwa.cn/Article/details/gtvmttrwpo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cqqwz.cn/Article/details/gtoygrcsbt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hfpthk.cn/Article/details/gtquqyidzg.html

TS:   interface Shape { area(): number; }
来源：http://dali.redwolf501.top/Article/details/gtqtncxodx.html

Java: interface Shape { double area(); }
来源：http://dali.smart0.xyz/Article/details/gtbbwcqjra.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.havefunace.top/Article/details/gtkheaposq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.pycfn.com/Article/details/gtlclpsmte.html

C#:   interface IShape { double Area(); }
来源：http://dali.smart0.xyz/Article/details/gtjqxyvgnx.html

[G10] 访问控制
来源：http://dali.ybcxt.top/Article/details/gtktolcpmk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nwbrower.top/Article/details/gtcxdumuhz.html

PHP:  public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gtyhajwaej.html

JS:   #private 字段；其余公开
来源：http://dali.cheryme.top/Article/details/gtoejpttnh.html

TS:   public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gtkqqsquta.html

Java: public / protected / private / 默认包级
来源：http://dali.pycfn.com/Article/details/gtpxgoflag.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.kuanghao11.cn/Article/details/gtgnvxvhxd.html

Ruby: public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gtxarstupx.html

C#:   public / protected / private / internal
来源：http://dali.ehwqpu.com/Article/details/gtnbiupugd.html

[G11] getter / setter
来源：http://dali.zhiwuduotai.top/Article/details/gtabsrrjaw.html

Py:   @property 与 @x.setter
来源：http://dali.yvedp.cn/Article/details/gtfpcltzuu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtulcxfopf.html

JS:   get name() { return this._name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtptzshpno.html

TS:   get name(): string { return this._name; }
来源：http://dali.cheryme.top/Article/details/gtylqhfdsc.html

Java: public String getName() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtwnosrdwx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gtogohratv.html

Ruby: attr_accessor :name
来源：http://dali.sufxvd.cn/Article/details/gtbhjqldjn.html

C#:   public string Name { get; set; }
来源：http://dali.hammf.cn/Article/details/gtkhgsczvf.html

[G12] 对象转字符串
来源：http://dali.cucudq.cn/Article/details/gtslnwlccr.html

Py:   def __str__(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gtaaryweml.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gtrhjaxnze.html

JS:   toString() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtyrjukxjp.html

TS:   toString(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtmqvdwasw.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtsqjkdvcl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtwxrtcvjj.html

Ruby: def to_s; @name; end
来源：http://dali.hywenlv.cn/Article/details/gtlalsdzwl.html

C#:   public override string ToString() => Name;
来源：http://dali.guowangkeji.top/Article/details/gtlwoxulee.html

[G13] 判断对象类型
来源：http://dali.yanxiufei.cn/Article/details/gtngmmdzbg.html

Py:   isinstance(u, User)
来源：http://dali.ivvv.top/Article/details/gtpodmfjbl.html

PHP:  $u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtmkxyjxrr.html

JS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gteqnycnda.html

TS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtyayzklze.html

Java: u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtvhvqivqr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuxming.cn/Article/details/gtkhwsbenl.html

Ruby: u.is_a?(User)
来源：http://dali.zdqjudy.top/Article/details/gtfmqriunf.html

C#:   u is User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaordzsma.html

[G14] 数据类 / record
来源：http://dali.wangdashe.top/Article/details/gtkxmejhha.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.birdmap.top/Article/details/gtlxlszllx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cashguo.top/Article/details/gtiexlkjnd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shuidangran.top/Article/details/gtdrpalvrf.html

TS:   type User = { name: string; age: number };
来源：http://dali.sweek.top/Article/details/gtzwldqttx.html

Java: record User(String name, int age) {}
来源：http://dali.cqqwz.cn/Article/details/gtkzipqrlh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xinyue.icu/Article/details/gtkxezgyct.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xziqi.cn/Article/details/gtojworgym.html

C#:   record User(string Name, int Age);
来源：http://dali.cucudq.cn/Article/details/gttyozvlof.html

[G15] 枚举
来源：http://dali.yanxiufei.cn/Article/details/gtnexdoyqg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cucudq.cn/Article/details/gtlbnxzskn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.dashuyun.cn/Article/details/gtyqgvfnnl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pycfn.com/Article/details/gtmiqqsmhn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gtxxakkvvx.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhiwuduotai.top/Article/details/gtjrgozzeb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xylfe.cn/Article/details/gtvbpowvrx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jianghu66.top/Article/details/gtihtfrkxt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gtggdzijmo.html

[G16] 对象转数组 / 字典
来源：http://dali.yongpay.top/Article/details/gttshzhxkz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guowangkeji.top/Article/details/gtnhovcabg.html

PHP:  get_object_vars($obj);
来源：http://dali.xziqi.cn/Article/details/gtyekyhdzv.html

JS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtgxfmqqtv.html

TS:   Object.entries(obj)
来源：http://dali.yangfankeji.com/Article/details/gtjpxxptkh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgxbgbrsb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.feifeiyinyue.top/Article/details/gtjchszfrj.html

Ruby: obj.instance_variables
来源：http://dali.havefunace.top/Article/details/gtcajrklpq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gtajgywtyr.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gthkzyvdbe.html

H. 异常与错误处理
来源：http://dali.ydzc1.top/Article/details/gtayirmxgu.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtkssxeapf.html

[H01] try / catch 基础
来源：http://dali.yvedp.cn/Article/details/gtcfrbiftu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gogol.net.cn/Article/details/gtaiqyhnpx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgvtudfx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gtcytabrlb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gtrvlbwjdi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sxryk.cn/Article/details/gtlxtearkd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xziqi.cn/Article/details/gtbsxrcdhu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.iojbl.cn/Article/details/gtkqtuewjm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cashguo.top/Article/details/gtuchqisde.html

[H02] finally / ensure 收尾
来源：http://dali.zhongyouzk.top/Article/details/gtqvdijfkr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258.top/Article/details/gtfpdbmzoa.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxppgxxjs.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtjddndeuq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtsymzelfa.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtwtycitux.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.bjfxy.top/Article/details/gtbfcpgodf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tanke756.top/Article/details/gteuqnhktq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtekzjgsmm.html

[H03] 主动抛出异常
来源：http://dali.meibo888.top/Article/details/gtkgxbboyz.html

Py:   raise ValueError("错误信息")
来源：http://dali.aizwys.cn/Article/details/gtjhzbukpa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtalpgidyh.html

JS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gtiicuqwyr.html

TS:   throw new Error("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtmofzhbrh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtygsmzozq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.smart0.xyz/Article/details/gtezzkaops.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ppjwa.cn/Article/details/gtzgduvitw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtfcjvsvlr.html

[H04] 自定义异常类型
来源：http://dali.xinyue.icu/Article/details/gtsjqwafum.html

Py:   class MyError(Exception): pass
来源：http://dali.pycfn.com/Article/details/gtbpkwoevf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aizwys.cn/Article/details/gtrbhkomwp.html

JS:   class MyError extends Error {}
来源：http://dali.yueranfly.top/Article/details/gtwenhycfg.html

TS:   class MyError extends Error {}
来源：http://dali.havefunace.top/Article/details/gtkuyryxea.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gtgravzkob.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.birdmap.top/Article/details/gtsfwaiwen.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangshuangyany.cn/Article/details/gtfpalwfpo.html

C#:   class MyException : Exception {}
来源：http://dali.nanxuanxn.top/Article/details/gtcrgddbuj.html

[H05] 捕获特定类型
来源：http://dali.sxryk.cn/Article/details/gthivtzrkc.html

Py:   except ValueError as e:
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwluwgtx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.kuanghao11.cn/Article/details/gtsfijixno.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gtpqkmhxst.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gtebmwbroc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjhtmess.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.daxiang520.top/Article/details/gtdfcxntyd.html

Ruby: rescue ArgumentError => e
来源：http://dali.ppjwa.cn/Article/details/gtfvfifxgp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tianlin.xyz/Article/details/gtamvbwtom.html

[H06] 可选值 / 空值安全访问
来源：http://dali.birdmap.top/Article/details/gtwrcoxkux.html

Py:   value = d.get("k") or default
来源：http://dali.kuanghao11.cn/Article/details/gtrkcgbmrh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gthfbwuxec.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gturczlugt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigufen.top/Article/details/gthnsccdst.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yongpay.top/Article/details/gtiycxfwnr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhixingplan.top/Article/details/gtfurwflfl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sysykeji.top/Article/details/gteqzbzexy.html

C#:   obj?.A?.B ?? default
来源：http://dali.shzxlz.cn/Article/details/gtrpcontil.html

[H07] 断言
来源：http://dali.daria6918.cn/Article/details/gtjujygnzi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aibaodan.cn/Article/details/gtypuojosr.html

PHP:  assert($x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gteutnalbw.html

JS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtpsjfwavm.html

TS:   console.assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtwbjqpxpe.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gogol.net.cn/Article/details/gtphynskou.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.iojbl.cn/Article/details/gtcocxmjqo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hnxiangtu.top/Article/details/gtkwafwmeg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtaapbjyjc.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangshuangyany.cn/Article/details/gtbmrmvezq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jianghu66.top/Article/details/gtehgjbdaa.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jianghu66.top/Article/details/gtsdgmtcco.html

JS:   e.message;  e.stack
来源：http://dali.hammf.cn/Article/details/gtkzuadeel.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.birdmap.top/Article/details/gtsceptiqd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yvedp.cn/Article/details/gtdcfjegen.html

Go:   err.Error()
来源：http://dali.sxryk.cn/Article/details/gtsbyygyze.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigufen.top/Article/details/gtlztzrdpw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.vqdsnc.cn/Article/details/gtygfbbtrk.html

[H09] 带错误码的异常
来源：http://dali.c1oappe.top/Article/details/gtpsgyxltv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hammf.cn/Article/details/gtfsoisizn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shuidangran.top/Article/details/gtqmqkecyo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yonumen.top/Article/details/gtkoiyftmf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yueranfly.top/Article/details/gtnutwbknc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sufxvd.cn/Article/details/gteqgizyvw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpgylvdfq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.smart0.xyz/Article/details/gtblcxesuo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hammf.cn/Article/details/gtmgvrtqiv.html

[H10] 资源自动释放
来源：http://dali.redwolf501.top/Article/details/gtocyvcpip.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.dashuyun.cn/Article/details/gtqozazkkf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hywenlv.cn/Article/details/gtyvwmnfgx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ybcxt.top/Article/details/gtbflheyby.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tanke756.top/Article/details/gtkijxndpu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.vqdsnc.cn/Article/details/gtoxzltjqv.html

Go:   defer f.Close()
来源：http://dali.nanxinkj.top/Article/details/gtklksyesn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jqgufenzy.top/Article/details/gtqvhikmaq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtiiacaaun.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtkqzlzxhj.html

I. 正则表达式
来源：http://dali.zhongyouzk.top/Article/details/gtsoivxwzt.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gthwvhfmzb.html

[I01] 判断是否匹配
来源：http://dali.zhengqikj.top/Article/details/gtdlqnerry.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtwtrndegp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtnetikhpk.html

JS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gtebqxsgkm.html

TS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gtdenqtvvu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tian-w.cn/Article/details/gtthnvmdmc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ivvv.top/Article/details/gtzfbvdnud.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gtggolbqot.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hfpthk.cn/Article/details/gthinextdv.html

[I02] 提取所有匹配
来源：http://dali.jiagoushi.top/Article/details/gtpqbwoban.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sufxvd.cn/Article/details/gtrmqcawzt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nwbrower.top/Article/details/gtorfvqwtq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hnqzz.top/Article/details/gtermcmbzt.html

TS:   s.match(/\d+/g)
来源：http://dali.daria6918.cn/Article/details/gtohgarith.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ppjwa.cn/Article/details/gtltkjchdk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gtvafrvhfz.html

Ruby: s.scan(/\d+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfzfyhrs.html


<!-- 参考信息 -->