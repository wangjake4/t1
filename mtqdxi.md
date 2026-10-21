代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hywenlv.cn/Article/details/gthiowlzeg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.dashuyun.cn/Article/details/gtszfyfdtk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hongshengwenyu.top/Article/details/gtaqmofgjp.html

[F08] 遍历目录
来源：http://dali.cdnleiting.top/Article/details/gtpgpsexjk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xziqi.cn/Article/details/gtmbimwhbf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.quarkkingdee.top/Article/details/gtlikgebdt.html

JS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gtfsgldmcl.html

TS:   fs.readdirSync("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gthjllgwql.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmvfmrhzp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yangfankeji.com/Article/details/gtfwaeipmk.html

Ruby: Dir.children("dir")
来源：http://dali.ppjwa.cn/Article/details/gtmsrrwejk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.daxiang520.top/Article/details/gtmhosxrsz.html

[F09] 获取文件大小
来源：http://dali.chenzaomai.com/Article/details/gtrlkwyuwu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ivvv.top/Article/details/gtrupafiwo.html

PHP:  filesize("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gteqinfzbd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hfpthk.cn/Article/details/gtyxisyyxa.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aizwys.cn/Article/details/gtzvcdveyl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtbbvtxkyq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yueranfly.top/Article/details/gtvphjckwq.html

Ruby: File.size("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtuzxpmlot.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fzhhl.top/Article/details/gtorewerfl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.dashuyun.cn/Article/details/gtxroymsfy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtugwtgtvv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtyytwjyvh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtmmycwuet.html

TS:   path.extname("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtvibzowun.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cdnleiting.top/Article/details/gtxaqjewrd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtefdiybra.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtfapagjdj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtnawxnxoi.html

[F11] 复制与移动文件
来源：http://dali.zhiwuduotai.top/Article/details/gtgsjanjpe.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtmkouwopx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.haohaochexian.top/Article/details/gtjpjvicmh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtbitlvcod.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtdseswnlv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nwbrower.top/Article/details/gtafrnufwo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gaohongyu789.top/Article/details/gtsuiyhqjl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtojulqlrq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgzdcmrju.html

[F12] CSV 读写
来源：http://dali.yj202588.top/Article/details/gtnpuozcyf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.pycfn.com/Article/details/gtpneyfntl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xinyue.icu/Article/details/gtmffbvtgf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuxming.cn/Article/details/gtsrfvqpmm.html

TS:   // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gtkmjttvct.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhixingplan.top/Article/details/gtxcifvluo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.wangshuangyany.cn/Article/details/gtvaddgswa.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hammf.cn/Article/details/gtuukigrfq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yonumen.top/Article/details/gtbrbgfxdb.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtanjxeogw.html

G. 面向对象
来源：http://dali.cashguo.top/Article/details/gtkgoazxoc.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtmtlapque.html

[G01] 定义类
来源：http://dali.shuidangran.top/Article/details/gtznnfhdsv.html

Py:   class User: pass
来源：http://dali.hywenlv.cn/Article/details/gtqpwsolkm.html

PHP:  class User {}
来源：http://dali.sweek.top/Article/details/gtyjrcoduc.html

JS:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gtkdqzbvrv.html

TS:   class User { name: string = ""; }
来源：http://dali.jqgfzy.top/Article/details/gtalezuuxn.html

Java: class User {}
来源：http://dali.cdnleiting.top/Article/details/gtudazwmvf.html

Go:   type User struct { Name string }
来源：http://dali.nanxuanxn.top/Article/details/gtbrymvjim.html

Ruby: class User; end
来源：http://dali.xinyue.icu/Article/details/gtlbhjrhvt.html

C#:   class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtvnakcqzo.html

[G02] 构造函数
来源：http://dali.hnqzz.top/Article/details/gtbsgkduoe.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuanzx.com/Article/details/gtludushhz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cheryme.top/Article/details/gtfkqhqfzc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jianghu66.top/Article/details/gtlokclcuw.html

TS:   constructor(public name: string) {}
来源：http://dali.sufxvd.cn/Article/details/gtqihrnqls.html

Java: User(String name) { this.name = name; }
来源：http://dali.hysaishi.cn/Article/details/gtklxdmlvi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhongyouzk.top/Article/details/gtgkwrvreh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hysaishi.cn/Article/details/gtylplbdrd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258888.top/Article/details/gtnuxytxgs.html

[G03] 实例属性
来源：http://dali.cdnleiting.top/Article/details/gtvbplgvza.html

Py:   self.name = "x"
来源：http://dali.316326.xyz/Article/details/gtfjstgfwy.html

PHP:  public string $name = "x";
来源：http://dali.jqgfzy.top/Article/details/gtlgcofdnp.html

JS:   this.name = "x";
来源：http://dali.gogol.net.cn/Article/details/gttpwkaqci.html

TS:   name: string = "x";
来源：http://dali.chenlongwang.top/Article/details/gtsdubrbtr.html

Java: private String name;
来源：http://dali.gogol.net.cn/Article/details/gtvqacebsm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnqzz.top/Article/details/gtnckvmsek.html

Ruby: @name = "x"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvzzzsvt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aibaodan.cn/Article/details/gtffqrkeks.html

[G04] 定义方法
来源：http://dali.sweek.top/Article/details/gtmcnjbuwg.html

Py:   def greet(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gtdfjwceih.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gtdfurxbox.html

JS:   greet() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtdncyjsgq.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gtorshzvue.html

Java: String greet() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtcfxkqofi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gthifizkey.html

Ruby: def greet; @name; end
来源：http://dali.sweek.top/Article/details/gthqqogekk.html

C#:   public string Greet() => Name;
来源：http://dali.tian-w.cn/Article/details/gtnhpqjrzc.html

[G05] 继承
来源：http://dali.zhongyouzk.top/Article/details/gtryffnewx.html

Py:   class Admin(User): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpattghdb.html

PHP:  class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtyoahdufc.html

JS:   class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtyniuxawm.html

TS:   class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtyxjkuxoy.html

Java: class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtlebsnlty.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yongpay.top/Article/details/gtennhting.html

Ruby: class Admin < User; end
来源：http://dali.tian-w.cn/Article/details/gtznlarprs.html

C#:   class Admin : User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkmfegxyp.html

[G06] 重写方法
来源：http://dali.nanxuanxn.top/Article/details/gtuewwknzh.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigufen.top/Article/details/gtwhmpsrcj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtynzadkcz.html

JS:   greet() { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtofbzodvc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtaimcuxqf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtpsxqzguw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pengpengdd.cyou/Article/details/gtubhdxbsz.html

Ruby: def greet; "admin"; end
来源：http://dali.snrcjt.cn/Article/details/gtjagmezxg.html

C#:   public override string Greet() => "admin";
来源：http://dali.vqdsnc.cn/Article/details/gtkeqkhpdm.html

[G07] 调用父类方法
来源：http://dali.chenjidiqi.icu/Article/details/gtdvutwhgd.html

Py:   super().greet()
来源：http://dali.hfpthk.cn/Article/details/gtbcbfnbxu.html

PHP:  parent::greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtqfjkazqn.html

JS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gtcpiacybh.html

TS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gtvhnyobqw.html

Java: super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gttjontwhi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ivvv.top/Article/details/gtjzjqvyke.html

Ruby: super
来源：http://dali.ehwqpu.com/Article/details/gtwwbeimzu.html

C#:   base.Greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlteqocly.html

[G08] 静态方法与属性
来源：http://dali.hnxiangtu.top/Article/details/gtgargwiwm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yangfankeji.com/Article/details/gtjzzvqmdy.html

PHP:  public static function f() {}
来源：http://dali.tian-w.cn/Article/details/gtsttmcdlc.html

JS:   static f() {}
来源：http://dali.jqgfzy.top/Article/details/gtereroife.html

TS:   static f(): void {}
来源：http://dali.zhengqikj.top/Article/details/gtcswavybe.html

Java: static void f() {}
来源：http://dali.tanke756.top/Article/details/gtorzjdfym.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yongpay.top/Article/details/gtnykjxwco.html

Ruby: def self.f; end
来源：http://dali.zhoulong.xyz/Article/details/gtweczowie.html

C#:   public static void F() {}
来源：http://dali.tianlin.xyz/Article/details/gtptunljwh.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigfzy.top/Article/details/gtuouvcibg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.birdmap.top/Article/details/gtiauxamqq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.316326.xyz/Article/details/gtekhugtna.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangtech.top/Article/details/gtgkxenckh.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenlongwang.top/Article/details/gtexfcgdkn.html

Java: interface Shape { double area(); }
来源：http://dali.guannengcc.top/Article/details/gthqxzkkov.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gtwcmppkdw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tianlin.xyz/Article/details/gtrjwgoccn.html

C#:   interface IShape { double Area(); }
来源：http://dali.hywenlv.cn/Article/details/gtjuqkksfo.html

[G10] 访问控制
来源：http://dali.9152youxi.cn/Article/details/gtqmoadatc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuanzhike.top/Article/details/gtnfyxiqcz.html

PHP:  public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtvlyevcrs.html

JS:   #private 字段；其余公开
来源：http://dali.aizwys.cn/Article/details/gtnrpfxzba.html

TS:   public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbogqksf.html

Java: public / protected / private / 默认包级
来源：http://dali.chenlongwang.top/Article/details/gtlslcchyv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yangfankeji.com/Article/details/gtxwxxdfqm.html

Ruby: public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtkffwbssy.html

C#:   public / protected / private / internal
来源：http://dali.gogol.net.cn/Article/details/gtorubspjb.html

[G11] getter / setter
来源：http://dali.fengsongda.top/Article/details/gtmiqddsht.html

Py:   @property 与 @x.setter
来源：http://dali.svipenyu.cn/Article/details/gtanskvrkp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtfdojvohx.html

JS:   get name() { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gtymehyumd.html

TS:   get name(): string { return this._name; }
来源：http://dali.iojbl.cn/Article/details/gtejxtllqa.html

Java: public String getName() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtyeaueewc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gtfktvkani.html

Ruby: attr_accessor :name
来源：http://dali.daria6918.cn/Article/details/gtrqomrgzt.html

C#:   public string Name { get; set; }
来源：http://dali.zycfv.cn/Article/details/gtsajfkvrv.html

[G12] 对象转字符串
来源：http://dali.nanxinkj.top/Article/details/gthxqjcqmz.html

Py:   def __str__(self): return self.name
来源：http://dali.cashguo.top/Article/details/gtkfbowjck.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gthfyppayz.html

JS:   toString() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtnexbfuso.html

TS:   toString(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtbmagqzqj.html

Java: @Override public String toString() { return name; }
来源：http://dali.ivvv.top/Article/details/gtorboqjki.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gtuptzzgxd.html

Ruby: def to_s; @name; end
来源：http://dali.yongpay.top/Article/details/gtmckjmqrv.html

C#:   public override string ToString() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqnaveil.html

[G13] 判断对象类型
来源：http://dali.c1oappe.top/Article/details/gtzllknfcp.html

Py:   isinstance(u, User)
来源：http://dali.nwbrower.top/Article/details/gtjfmxveld.html

PHP:  $u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtmtagucpt.html

JS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtaqnismdl.html

TS:   u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gtvbxhjrbd.html

Java: u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtlcncgffm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.iojbl.cn/Article/details/gtqxdlwnra.html

Ruby: u.is_a?(User)
来源：http://dali.hfpthk.cn/Article/details/gtxecafrzl.html

C#:   u is User
来源：http://dali.ywan-chungtsiang.top/Article/details/gttnjsnheh.html

[G14] 数据类 / record
来源：http://dali.shzxlz.cn/Article/details/gtwvaijbgo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hnqzz.top/Article/details/gtjgobhuge.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenjidiqi.icu/Article/details/gtbriaulel.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.haohaochexian.top/Article/details/gtfjirqmem.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigfzy.top/Article/details/gtcizfrvau.html

Java: record User(String name, int age) {}
来源：http://dali.daxiang520.top/Article/details/gtozwqdhjn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhoulong.xyz/Article/details/gthiotqswd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuxming.cn/Article/details/gtldkefndz.html

C#:   record User(string Name, int Age);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwgsenwd.html

[G15] 枚举
来源：http://dali.ppjwa.cn/Article/details/gtktpecymf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gogol.net.cn/Article/details/gtblbzsgwq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.birdmap.top/Article/details/gtiizkiovc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj202588.top/Article/details/gtupasgxoz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daria6918.cn/Article/details/gtxinxiids.html

Java: enum Color { RED, GREEN }
来源：http://dali.quarkkingdee.top/Article/details/gtcjlucobw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.aibaodan.cn/Article/details/gtxtdxkaku.html

Ruby: Color = %i[red green].freeze
来源：http://dali.9152youxi.cn/Article/details/gtottxdxvi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrywbowcj.html

[G16] 对象转数组 / 字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtppvwmcuq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sweek.top/Article/details/gtkgevvkmd.html

PHP:  get_object_vars($obj);
来源：http://dali.xuetiantiany.cn/Article/details/gtfatxoxgs.html

JS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gtfwoyvewy.html

TS:   Object.entries(obj)
来源：http://dali.0kj1m.cn/Article/details/gtvbfnpunl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.meibo888.top/Article/details/gtbbcckbmp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guowangkeji.top/Article/details/gtpzvmwjbq.html

Ruby: obj.instance_variables
来源：http://dali.daria6918.cn/Article/details/gturmeiinu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gtodmwkcbi.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gthtemotfj.html

H. 异常与错误处理
来源：http://dali.ivvv.top/Article/details/gtzzbydjph.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtyybvbayy.html

[H01] try / catch 基础
来源：http://dali.yanxiufei.cn/Article/details/gtntuhtyib.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yonumen.top/Article/details/gtcwokytoy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhoulong.xyz/Article/details/gtdewobiho.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gtvycmejgy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gtcvfqymgj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.haohaochexian.top/Article/details/gtsldjdoiv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.bjfxy.top/Article/details/gtilgmidrs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.c1oappe.top/Article/details/gtxxuhfpps.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.fengsongda.top/Article/details/gtwhtjzhsv.html

[H02] finally / ensure 收尾
来源：http://dali.hywenlv.cn/Article/details/gtmfiuvahm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.kuanghao11.cn/Article/details/gtiwpbnsrn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gthsrubpsk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiotwqbgi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtlgagjwyd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtliirnyss.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgufenzy.top/Article/details/gttkrqjgmw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aibaodan.cn/Article/details/gtrdgcdumc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtlfqbrvqa.html

[H03] 主动抛出异常
来源：http://dali.yj20258.top/Article/details/gtkduwjaqq.html

Py:   raise ValueError("错误信息")
来源：http://dali.hfpthk.cn/Article/details/gtjrjuwhww.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtpewjnvrr.html

JS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtvymgkszz.html

TS:   throw new Error("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtibrqmkao.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gtpkbqhotd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.feifeiyinyue.top/Article/details/gtbohynntq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gzhubu.top/Article/details/gtczotiupr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gthndwxgbd.html

[H04] 自定义异常类型
来源：http://dali.nwbrower.top/Article/details/gtjggiidtl.html

Py:   class MyError(Exception): pass
来源：http://dali.tanke756.top/Article/details/gtjztebqdp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.316326.xyz/Article/details/gtfosalpat.html

JS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gtizckxrbt.html

TS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gttlecylmc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtikhznwqa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fengsongda.top/Article/details/gtmvzkjiko.html

Ruby: class MyError < StandardError; end
来源：http://dali.fengsongda.top/Article/details/gtshenjttc.html

C#:   class MyException : Exception {}
来源：http://dali.redwolf501.top/Article/details/gtezgwbdug.html

[H05] 捕获特定类型
来源：http://dali.zhiwuduotai.top/Article/details/gtlftdltuq.html

Py:   except ValueError as e:
来源：http://dali.gaohongyu789.top/Article/details/gtmfzmtmup.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sxryk.cn/Article/details/gtdynyzwsu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gttjbcyifz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gtuojeuneg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhengqikj.top/Article/details/gttlarokvn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.mhx1999.top/Article/details/gtbmtheatv.html

Ruby: rescue ArgumentError => e
来源：http://dali.yuxming.cn/Article/details/gtwlnumyfr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.316326.xyz/Article/details/gtklhurgvs.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fzhhl.top/Article/details/gtbifunlmf.html

Py:   value = d.get("k") or default
来源：http://dali.0kj1m.cn/Article/details/gtkeznhytm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hfpthk.cn/Article/details/gtyatzdzec.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xuanzx.com/Article/details/gtfftatavc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gtbiwadkyj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuanzhike.top/Article/details/gtgfgnbxtz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.guowangkeji.top/Article/details/gtmnkueton.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpzpgnlpz.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhongyouzk.top/Article/details/gtmmeqmxxn.html

[H07] 断言
来源：http://dali.yj20258.top/Article/details/gtkgywhgle.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hnxiangtu.top/Article/details/gtouxnmqnm.html

PHP:  assert($x > 0);
来源：http://dali.xylfe.cn/Article/details/gtuifxywrt.html

JS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gttxpjilnb.html

TS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gtafyfdfis.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xuetiantiany.cn/Article/details/gtozbigzml.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj202588.top/Article/details/gtllinxrfe.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ywan-chungtsiang.top/Article/details/gtddkxzsrn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtfrbjbrlx.html

[H08] 获取错误信息与堆栈
来源：http://dali.meibo888.top/Article/details/gtbjazfdrc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhongyouzk.top/Article/details/gtebmotdvm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhengqikj.top/Article/details/gtzrgnevij.html

JS:   e.message;  e.stack
来源：http://dali.shuidangran.top/Article/details/gtzolbpsjq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aibaodan.cn/Article/details/gtfiyffqpd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cdnleiting.top/Article/details/gtauslmowf.html

Go:   err.Error()
来源：http://dali.dianchejie.cn/Article/details/gttdpbssqt.html

Ruby: e.message;  e.backtrace
来源：http://dali.ppjwa.cn/Article/details/gtjxijdmds.html

C#:   e.Message;  e.StackTrace
来源：http://dali.snrcjt.cn/Article/details/gtyyyuflhz.html

[H09] 带错误码的异常
来源：http://dali.9152youxi.cn/Article/details/gtgtxvtnnr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yueranfly.top/Article/details/gteifcfuvb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xziqi.cn/Article/details/gtigqhyudq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hammf.cn/Article/details/gtjsyzkqvy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.9152youxi.cn/Article/details/gtalymmuqi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvmvdyil.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuanzhike.top/Article/details/gtifawylor.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cheryme.top/Article/details/gtwzedjjik.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenjidiqi.icu/Article/details/gtlmnhagux.html

[H10] 资源自动释放
来源：http://dali.xinyue.icu/Article/details/gtpjebxhys.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sysykeji.top/Article/details/gtvicnnkqt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.smart0.xyz/Article/details/gtosezdjok.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gttsxqawxf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gtymssrzzr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yangfankeji.com/Article/details/gthfshrgrv.html

Go:   defer f.Close()
来源：http://dali.tian-w.cn/Article/details/gtxrbhaadk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.guannengcc.top/Article/details/gtnnfnofbj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtfqysdzmc.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtpuntyegj.html

I. 正则表达式
来源：http://dali.zdqjudy.top/Article/details/gtbxavodot.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtyagaykxg.html

[I01] 判断是否匹配
来源：http://dali.gaohongyu789.top/Article/details/gtdyacgqra.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gtvwgbnwrn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.316326.xyz/Article/details/gtjvwblcur.html

JS:   /\d+/.test(s)
来源：http://dali.feifeiyinyue.top/Article/details/gteabektze.html

TS:   /\d+/.test(s)
来源：http://dali.xziqi.cn/Article/details/gtcwuwgeuv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.smart0.xyz/Article/details/gtuxuqqtzf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daria6918.cn/Article/details/gtjqbhwnmy.html

Ruby: s.match?(/\d+/)
来源：http://dali.yuanzhike.top/Article/details/gtmknpkhqe.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnqzz.top/Article/details/gtyobvclas.html


<!-- 参考信息 -->