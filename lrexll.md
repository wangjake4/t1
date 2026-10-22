代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gt2mxhcfsgg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dianchejie.cn/Article/details/gt2cjjieknc.html

Ruby: Dir.children("dir")
来源：http://dali.xinyue.icu/Article/details/gt2ghseybjr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhixingplan.top/Article/details/gt2ynctogbk.html

[F09] 获取文件大小
来源：http://dali.dashuyun.cn/Article/details/gt2cafverug.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2wmmhyopf.html

PHP:  filesize("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2peuoacmh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gt2qzeispvt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.meibo888.top/Article/details/gt2znzgdegx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gt2dsmkgonh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.haohaochexian.top/Article/details/gt2ypayndqs.html

Ruby: File.size("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2bflkujib.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gogol.net.cn/Article/details/gt2xsrxgegv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gzhubu.top/Article/details/gt2oykddnxh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jeghqhjk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2fvgctkvx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2oghlhwpw.html

TS:   path.extname("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2mosuuwqv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cheryme.top/Article/details/gt2iylljksp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gt2ycbbvkdi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2vhvmmonz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2sbqqzbnd.html

[F11] 复制与移动文件
来源：http://dali.ybcxt.top/Article/details/gt2xtpetmuk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2jhziewdw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fzhhl.top/Article/details/gt2isybwsey.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2jftfsrpk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gt2zrobvtuu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.mhx1999.top/Article/details/gt2lbyfhjri.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xinyue.icu/Article/details/gt2yqklgbrd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2scoywaob.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gzhubu.top/Article/details/gt2afkffsru.html

[F12] CSV 读写
来源：http://dali.yueranfly.top/Article/details/gt2pnhafiwx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jyoumei.cn/Article/details/gt2ihjhdsiq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yangfankeji.com/Article/details/gt2xojxogkr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jyoumei.cn/Article/details/gt2unmdlwhj.html

TS:   // 同上
来源：http://dali.quarkkingdee.top/Article/details/gt2njpzvkch.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yongpay.top/Article/details/gt2lttnxwch.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gvpfxiuy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.aibaodan.cn/Article/details/gt2kbulhwuc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aombwixw.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2qqyofjrd.html

G. 面向对象
来源：http://dali.shangyingyoupin.top/Article/details/gt2qcqdvann.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2seifhhnf.html

[G01] 定义类
来源：http://dali.zhixingplan.top/Article/details/gt2rkzhmzxi.html

Py:   class User: pass
来源：http://dali.bjfxy.top/Article/details/gt2dfaqwjgl.html

PHP:  class User {}
来源：http://dali.sufxvd.cn/Article/details/gt2bftgxjxc.html

JS:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2vcvlpize.html

TS:   class User { name: string = ""; }
来源：http://dali.ivvv.top/Article/details/gt2uwsmjjup.html

Java: class User {}
来源：http://dali.zhengqikj.top/Article/details/gt2jtfdrwao.html

Go:   type User struct { Name string }
来源：http://dali.snrcjt.cn/Article/details/gt2bmkqvdpm.html

Ruby: class User; end
来源：http://dali.svipenyu.cn/Article/details/gt2duzctwai.html

C#:   class User {}
来源：http://dali.nwbrower.top/Article/details/gt2uptjcpot.html

[G02] 构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2ozcalnqz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yongpay.top/Article/details/gt2qpgbtvkj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hfpthk.cn/Article/details/gt2zgogvpvv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.svipenyu.cn/Article/details/gt2yofymryb.html

TS:   constructor(public name: string) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2gkrlfowm.html

Java: User(String name) { this.name = name; }
来源：http://dali.yuanzhike.top/Article/details/gt2qvkjvbmk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.snrcjt.cn/Article/details/gt2tqajwcxf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fdybxblq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.birdmap.top/Article/details/gt2ouaeyxvi.html

[G03] 实例属性
来源：http://dali.ybcxt.top/Article/details/gt2ltikmams.html

Py:   self.name = "x"
来源：http://dali.zycfv.cn/Article/details/gt2ozprmpti.html

PHP:  public string $name = "x";
来源：http://dali.aibaodan.cn/Article/details/gt2bvgxinah.html

JS:   this.name = "x";
来源：http://dali.svipenyu.cn/Article/details/gt2lpgbhted.html

TS:   name: string = "x";
来源：http://dali.cdnleiting.top/Article/details/gt2fqzgvrhc.html

Java: private String name;
来源：http://dali.xinyue.icu/Article/details/gt2geecarmp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sufxvd.cn/Article/details/gt2hjqxuwfi.html

Ruby: @name = "x"
来源：http://dali.ehwqpu.com/Article/details/gt2tcugenje.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daria6918.cn/Article/details/gt2biotrweq.html

[G04] 定义方法
来源：http://dali.jinqigfzy.top/Article/details/gt2ecxfvfie.html

Py:   def greet(self): return self.name
来源：http://dali.9152youxi.cn/Article/details/gt2posrztwe.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gt2sdslbgwm.html

JS:   greet() { return this.name; }
来源：http://dali.yj202588.top/Article/details/gt2cjtypvnt.html

TS:   greet(): string { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gt2ulhcohfu.html

Java: String greet() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2bhuzjymt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gt2fcsghrbd.html

Ruby: def greet; @name; end
来源：http://dali.zhongyouzk.top/Article/details/gt2ppmzbzje.html

C#:   public string Greet() => Name;
来源：http://dali.bjfxy.top/Article/details/gt2dhgkeffn.html

[G05] 继承
来源：http://dali.sweek.top/Article/details/gt2fsgyotun.html

Py:   class Admin(User): pass
来源：http://dali.9152youxi.cn/Article/details/gt2kvreeucr.html

PHP:  class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gt2mywyrkde.html

JS:   class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gt2btuqrofe.html

TS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2xsfgegpb.html

Java: class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kzblaxwt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.wangshuangyany.cn/Article/details/gt2zipmxymr.html

Ruby: class Admin < User; end
来源：http://dali.cashguo.top/Article/details/gt2ydnngppy.html

C#:   class Admin : User {}
来源：http://dali.guowangkeji.top/Article/details/gt2pgnposaf.html

[G06] 重写方法
来源：http://dali.gzhubu.top/Article/details/gt2eqoejigp.html

Py:   def greet(self): return "admin"
来源：http://dali.dianchejie.cn/Article/details/gt2oxzyiplr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2dnpvbtew.html

JS:   greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gt2jlqqmhef.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2pkndrpff.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gt2xpewzdjf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yuxming.cn/Article/details/gt2kdyrzavq.html

Ruby: def greet; "admin"; end
来源：http://dali.smart0.xyz/Article/details/gt2gapdefxo.html

C#:   public override string Greet() => "admin";
来源：http://dali.daxiang520.top/Article/details/gt2fijrcyoz.html

[G07] 调用父类方法
来源：http://dali.yvedp.cn/Article/details/gt2jjyxxqlh.html

Py:   super().greet()
来源：http://dali.zhongyouzk.top/Article/details/gt2anxirtnu.html

PHP:  parent::greet();
来源：http://dali.xylfe.cn/Article/details/gt2dwudvezm.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvntyod.html

TS:   super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cocwiwkg.html

Java: super.greet();
来源：http://dali.daxiang520.top/Article/details/gt2wfaazosx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgufenzy.top/Article/details/gt2gbtjkvym.html

Ruby: super
来源：http://dali.hfpthk.cn/Article/details/gt2rbqzlrfw.html

C#:   base.Greet();
来源：http://dali.zhongyouzk.top/Article/details/gt2ewadnczo.html

[G08] 静态方法与属性
来源：http://dali.hywenlv.cn/Article/details/gt2vrubdlvf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.316326.xyz/Article/details/gt2elkpadbi.html

PHP:  public static function f() {}
来源：http://dali.zdqjudy.top/Article/details/gt2ktiiwlkk.html

JS:   static f() {}
来源：http://dali.ydzc1.top/Article/details/gt2dcixgxzk.html

TS:   static f(): void {}
来源：http://dali.ivvv.top/Article/details/gt2mnmpukyf.html

Java: static void f() {}
来源：http://dali.quarkkingdee.top/Article/details/gt2whyjuqhv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2scmynbkk.html

Ruby: def self.f; end
来源：http://dali.cqqwz.cn/Article/details/gt2affauhdl.html

C#:   public static void F() {}
来源：http://dali.hysaishi.cn/Article/details/gt2spishkqs.html

[G09] 接口 / 抽象类
来源：http://dali.chenzaomai.com/Article/details/gt2nimnbpjf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.haohaochexian.top/Article/details/gt2kwdnzard.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yueranfly.top/Article/details/gt2ztcayjky.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.havefunace.top/Article/details/gt2jqyxnfma.html

TS:   interface Shape { area(): number; }
来源：http://dali.tianlin.xyz/Article/details/gt2xjxzyqct.html

Java: interface Shape { double area(); }
来源：http://dali.9152youxi.cn/Article/details/gt2ukspdiuq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yanxiufei.cn/Article/details/gt2tixnhypt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nanxuanxn.top/Article/details/gt2bubpwyvp.html

C#:   interface IShape { double Area(); }
来源：http://dali.sxryk.cn/Article/details/gt2ywpohjnh.html

[G10] 访问控制
来源：http://dali.xuetiantiany.cn/Article/details/gt2pdplziug.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yanxiufei.cn/Article/details/gt2ylbwpoxr.html

PHP:  public / protected / private
来源：http://dali.cashguo.top/Article/details/gt2hktnjseb.html

JS:   #private 字段；其余公开
来源：http://dali.guowangkeji.top/Article/details/gt2qmgooiee.html

TS:   public / protected / private
来源：http://dali.316326.xyz/Article/details/gt2jxuerokk.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ssibpykc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj202588.top/Article/details/gt2olksqier.html

Ruby: public / protected / private
来源：http://dali.andypj.xyz/Article/details/gt2cufkpild.html

C#:   public / protected / private / internal
来源：http://dali.xuetiantiany.cn/Article/details/gt2izygjmwz.html

[G11] getter / setter
来源：http://dali.mhx1999.top/Article/details/gt2zjnadzqk.html

Py:   @property 与 @x.setter
来源：http://dali.nanxinkj.top/Article/details/gt2turwtdvl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gt2uvqbqvbu.html

JS:   get name() { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gt2ihfkbwyt.html

TS:   get name(): string { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ftconumo.html

Java: public String getName() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gt2kehxtkjc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gt2aszscbyg.html

Ruby: attr_accessor :name
来源：http://dali.yuxming.cn/Article/details/gt2eimgvjnj.html

C#:   public string Name { get; set; }
来源：http://dali.andypj.xyz/Article/details/gt2enbthgfa.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2glwticje.html

Py:   def __str__(self): return self.name
来源：http://dali.shuidangran.top/Article/details/gt2galecpka.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gt2kxrdfzye.html

JS:   toString() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gt2uyzeaqqw.html

TS:   toString(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2urilpzdr.html

Java: @Override public String toString() { return name; }
来源：http://dali.mhx1999.top/Article/details/gt2geithlac.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gt2ozatbkvb.html

Ruby: def to_s; @name; end
来源：http://dali.xinyue.icu/Article/details/gt2cvulwvky.html

C#:   public override string ToString() => Name;
来源：http://dali.pycfn.com/Article/details/gt2aidvjhhb.html

[G13] 判断对象类型
来源：http://dali.gaohongyu789.top/Article/details/gt2umpfctop.html

Py:   isinstance(u, User)
来源：http://dali.tianlin.xyz/Article/details/gt2doaootlm.html

PHP:  $u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gt2ibvabtqc.html

JS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rtaxjcwl.html

TS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gt2xsyqrhbt.html

Java: u instanceof User
来源：http://dali.xinyue.icu/Article/details/gt2rtinivgu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zdqjudy.top/Article/details/gt2rihnpajc.html

Ruby: u.is_a?(User)
来源：http://dali.yj20258.top/Article/details/gt2rmfqqssz.html

C#:   u is User
来源：http://dali.svipenyu.cn/Article/details/gt2wxiclbwa.html

[G14] 数据类 / record
来源：http://dali.smart0.xyz/Article/details/gt2ywjvxvnc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.bjfxy.top/Article/details/gt2dearupod.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenzaomai.com/Article/details/gt2zibxntab.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.feifeiyinyue.top/Article/details/gt2ciwyovze.html

TS:   type User = { name: string; age: number };
来源：http://dali.sxryk.cn/Article/details/gt2quukbfww.html

Java: record User(String name, int age) {}
来源：http://dali.jqgfzy.top/Article/details/gt2tayteneg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenzaomai.com/Article/details/gt2wvtopkrk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cheryme.top/Article/details/gt2nnasykhg.html

C#:   record User(string Name, int Age);
来源：http://dali.chenlongwang.top/Article/details/gt2lmmwpgbf.html

[G15] 枚举
来源：http://dali.chenzaomai.com/Article/details/gt2ewiauspn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gaohongyu789.top/Article/details/gt2syghmbbt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jqgfzy.top/Article/details/gt2hdjsowhj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxinkj.top/Article/details/gt2bboyedaw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gt2odqliqqy.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhixingplan.top/Article/details/gt2ssctaily.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yanxiufei.cn/Article/details/gt2ypkxssrr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgfzy.top/Article/details/gt2rjjobowu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gt2ntpqvljd.html

[G16] 对象转数组 / 字典
来源：http://dali.nanxuanxn.top/Article/details/gt2wkggdiry.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sufxvd.cn/Article/details/gt2gvhwoteo.html

PHP:  get_object_vars($obj);
来源：http://dali.birdmap.top/Article/details/gt2yxqazkcp.html

JS:   Object.entries(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2wciruwcp.html

TS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bjufiacz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hysaishi.cn/Article/details/gt2bskpdnub.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhiwuduotai.top/Article/details/gt2afjijipp.html

Ruby: obj.instance_variables
来源：http://dali.yvedp.cn/Article/details/gt2fkjjgppo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gt2sucndcne.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2tjbepamc.html

H. 异常与错误处理
来源：http://dali.tianlin.xyz/Article/details/gt2qskleesc.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2kbmcjqgf.html

[H01] try / catch 基础
来源：http://dali.andypj.xyz/Article/details/gt2pvfalysy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ehwqpu.com/Article/details/gt2toirecpi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dlszruem.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gt2jxozhqax.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gt2cqaftoyf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.9152youxi.cn/Article/details/gt2ekkxzikz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.andypj.xyz/Article/details/gt2gkegedcu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenzaomai.com/Article/details/gt2znznzmva.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.redwolf501.top/Article/details/gt2qzmtvaqn.html

[H02] finally / ensure 收尾
来源：http://dali.birdmap.top/Article/details/gt2nouudbiv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nwbrower.top/Article/details/gt2qwyruvev.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2nkeaiqcf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gt2iifbnjzt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gt2cexuntlk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gt2vurafxxy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sweek.top/Article/details/gt2fbtgaoxt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aizwys.cn/Article/details/gt2duvxbuil.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2ihdibrzx.html

[H03] 主动抛出异常
来源：http://dali.0kj1m.cn/Article/details/gt2swhlhmfz.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhengqikj.top/Article/details/gt2rediatyr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gt2zhxrqcjr.html

JS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gt2synppnqn.html

TS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gt2rrqwilsn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gt2ttqvmuiq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.9152youxi.cn/Article/details/gt2wpwznfzj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.redwolf501.top/Article/details/gt2jueemwzg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gt2vhpfpwfk.html

[H04] 自定义异常类型
来源：http://dali.zycfv.cn/Article/details/gt2ebwkbusb.html

Py:   class MyError(Exception): pass
来源：http://dali.hysaishi.cn/Article/details/gt2fsytomyo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gt2qgntmcvy.html

JS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gt2fqbtbnxm.html

TS:   class MyError extends Error {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2hvdxmrjw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2rqughurp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gzhubu.top/Article/details/gt2wkehbnaj.html

Ruby: class MyError < StandardError; end
来源：http://dali.ppjwa.cn/Article/details/gt2wbtavkhv.html

C#:   class MyException : Exception {}
来源：http://dali.smart0.xyz/Article/details/gt2sfdnndas.html

[H05] 捕获特定类型
来源：http://dali.bjfxy.top/Article/details/gt2ssvjnhji.html

Py:   except ValueError as e:
来源：http://dali.mhx1999.top/Article/details/gt2rnsbxdgs.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuanzhike.top/Article/details/gt2rhvmairt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2psxevbaz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuanzhike.top/Article/details/gt2gxtrtwxa.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jqgfzy.top/Article/details/gt2srvlglsw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hnxiangtu.top/Article/details/gt2mqvvyhdy.html

Ruby: rescue ArgumentError => e
来源：http://dali.nanxuanxn.top/Article/details/gt2koqduaqi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenlongwang.top/Article/details/gt2zqvbmahg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258.top/Article/details/gt2snwlqtkm.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigufen.top/Article/details/gt2owclifjw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenjidiqi.icu/Article/details/gt2jljdsrjq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenlongwang.top/Article/details/gt2suipmoye.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigufen.top/Article/details/gt2mgpqlmfq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yvedp.cn/Article/details/gt2hslnkmru.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hoqtytax.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xziqi.cn/Article/details/gt2dbiydtou.html

C#:   obj?.A?.B ?? default
来源：http://dali.cqqwz.cn/Article/details/gt2lypnazmh.html

[H07] 断言
来源：http://dali.jianghu66.top/Article/details/gt2jtrbceaz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shangyingyoupin.top/Article/details/gt2eatqrjgo.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ginngfpi.html

JS:   console.assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gt2ykcdfboj.html

TS:   console.assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gt2ijxalxtp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuanzhike.top/Article/details/gt2qiashilq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hammf.cn/Article/details/gt2ihrhjbgb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xylfe.cn/Article/details/gt2oorrpwbi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gt2zojrjhcs.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhiwuduotai.top/Article/details/gt2upxobluv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yonumen.top/Article/details/gt2nsbhyjqf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.0kj1m.cn/Article/details/gt2nbfmwdav.html

JS:   e.message;  e.stack
来源：http://dali.nanxinkj.top/Article/details/gt2cehpcayh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.quarkkingdee.top/Article/details/gt2pivdorfi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnimbpw.html

Go:   err.Error()
来源：http://dali.nanxuanxn.top/Article/details/gt2kpjuumso.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kiavrggb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xylfe.cn/Article/details/gt2uvaolnse.html

[H09] 带错误码的异常
来源：http://dali.nwbrower.top/Article/details/gt2hhrpzdwt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xylfe.cn/Article/details/gt2skfetjis.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hnxiangtu.top/Article/details/gt2burtpzgj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xinyue.icu/Article/details/gt2loywgrun.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cucudq.cn/Article/details/gt2ogbqvzml.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigfzy.top/Article/details/gt2rljbzcvw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.c1oappe.top/Article/details/gt2jczfjzyf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vfgyxbqx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ivvv.top/Article/details/gt2ljtsepxl.html

[H10] 资源自动释放
来源：http://dali.wangdashe.top/Article/details/gt2odihuidu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgfzy.top/Article/details/gt2bxgrqrtz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bxtgrxyw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gt2kvahtlbw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gt2ohzmzvox.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hywenlv.cn/Article/details/gt2uyrszzth.html

Go:   defer f.Close()
来源：http://dali.tanke756.top/Article/details/gt2kufkacis.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhongyouzk.top/Article/details/gt2cevixwlc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2bkwbvued.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2kjfsdwmj.html

I. 正则表达式
来源：http://dali.svipenyu.cn/Article/details/gt2ueylviuj.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2egoyxken.html

[I01] 判断是否匹配
来源：http://dali.cheryme.top/Article/details/gt2ankrbaas.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hnxiangtu.top/Article/details/gt2ledgyels.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.pycfn.com/Article/details/gt2stwlkyoc.html

JS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gt2ubqnbvzl.html

TS:   /\d+/.test(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jdwwlpvd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shuidangran.top/Article/details/gt2rhqrlmkc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qzsaveqq.html

Ruby: s.match?(/\d+/)
来源：http://dali.gzhubu.top/Article/details/gt2xyepabxj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cashguo.top/Article/details/gt2lbfyxyer.html

[I02] 提取所有匹配
来源：http://dali.smart0.xyz/Article/details/gt2klwjugpv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gt2cehtquzi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zdqjudy.top/Article/details/gt2fwqmkdki.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.dashuyun.cn/Article/details/gt2nthhduzf.html

TS:   s.match(/\d+/g)
来源：http://dali.yueranfly.top/Article/details/gt2kbcfplxs.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2snuhdgst.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.snrcjt.cn/Article/details/gt2lhepaicb.html

Ruby: s.scan(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gt2wtsvejva.html


<!-- 参考信息 -->