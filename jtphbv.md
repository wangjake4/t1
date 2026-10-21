代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gtxcfjmbnt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yuanzhike.top/Article/details/gtchpjxtuu.html

Ruby: Dir.children("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtuqulmlsl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtxwrcniis.html

[F09] 获取文件大小
来源：http://dali.jlsjyb.cn/Article/details/gtrehcruan.html

Py:   os.path.getsize("a.txt")
来源：http://dali.316326.xyz/Article/details/gtbmiyakaq.html

PHP:  filesize("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtvjklnwmy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gtvchsqrik.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zycfv.cn/Article/details/gtzvdvyktr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gttgzwbmvz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhiwuduotai.top/Article/details/gtkzarvwlf.html

Ruby: File.size("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtzfrgglsp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.316326.xyz/Article/details/gtpsistino.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.snrcjt.cn/Article/details/gtunuscfoy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gttescgecb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nwbrower.top/Article/details/gtbybdjzdm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gttsqsilta.html

TS:   path.extname("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtuyhjzvao.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cqqwz.cn/Article/details/gtilcrhjeg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtgjanaygz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowkqevjc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtsxdqnulb.html

[F11] 复制与移动文件
来源：http://dali.nanxinkj.top/Article/details/gtlfofticx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtwuuklojo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fzhhl.top/Article/details/gtgcwiwtpe.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtoehpdihc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtluthjaog.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cheryme.top/Article/details/gtmlhnfnxp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.c1oappe.top/Article/details/gtaqjjdidt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtnbyvivmb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258.top/Article/details/gtxuyghdiv.html

[F12] CSV 读写
来源：http://dali.sufxvd.cn/Article/details/gtxeswywyf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hongshengwenyu.top/Article/details/gtdewixcfw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ivvv.top/Article/details/gtyjnaebvr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zycfv.cn/Article/details/gtedwnwdcd.html

TS:   // 同上
来源：http://dali.yj20258888.top/Article/details/gtocmsdcxk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sxryk.cn/Article/details/gterywzfuj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zdqjudy.top/Article/details/gtqhxfinwx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenlongwang.top/Article/details/gtglwqjzax.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zdqjudy.top/Article/details/gtqejspglr.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtqvjntokh.html

G. 面向对象
来源：http://dali.fengsongda.top/Article/details/gtgqlmriyl.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtopxycosz.html

[G01] 定义类
来源：http://dali.xuetiantiany.cn/Article/details/gtrsemibgr.html

Py:   class User: pass
来源：http://dali.yongpay.top/Article/details/gtmnsjplhq.html

PHP:  class User {}
来源：http://dali.pycfn.com/Article/details/gtnytvzuze.html

JS:   class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwnwxivs.html

TS:   class User { name: string = ""; }
来源：http://dali.ivvv.top/Article/details/gtibfrnpqk.html

Java: class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtncfejzkk.html

Go:   type User struct { Name string }
来源：http://dali.havefunace.top/Article/details/gtwsrjanme.html

Ruby: class User; end
来源：http://dali.sysykeji.top/Article/details/gtdprzkcke.html

C#:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gtgalufnda.html

[G02] 构造函数
来源：http://dali.hywenlv.cn/Article/details/gtrxrhkdjr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.bjfxy.top/Article/details/gtuxvndxli.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gaohongyu789.top/Article/details/gtfmhfymgp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gtmcvhakyo.html

TS:   constructor(public name: string) {}
来源：http://dali.quarkkingdee.top/Article/details/gttkxoismi.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtyjhgttgb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.vqdsnc.cn/Article/details/gtcvdqrzqg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zdqjudy.top/Article/details/gtxupmgoiy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenzaomai.com/Article/details/gtnutujhli.html

[G03] 实例属性
来源：http://dali.xylfe.cn/Article/details/gthpgaguiv.html

Py:   self.name = "x"
来源：http://dali.fengsongda.top/Article/details/gtdrakbzyw.html

PHP:  public string $name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtpbrirsqc.html

JS:   this.name = "x";
来源：http://dali.xuanzx.com/Article/details/gtvnymxcdv.html

TS:   name: string = "x";
来源：http://dali.fengsongda.top/Article/details/gtnpjosvio.html

Java: private String name;
来源：http://dali.jqgufenzy.top/Article/details/gttpwfipar.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shanyushiyangtech.top/Article/details/gtkphifibw.html

Ruby: @name = "x"
来源：http://dali.c1oappe.top/Article/details/gtczwmjpks.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xuanzx.com/Article/details/gtdsjxaifq.html

[G04] 定义方法
来源：http://dali.zhoulong.xyz/Article/details/gthwplvsvn.html

Py:   def greet(self): return self.name
来源：http://dali.hongshengwenyu.top/Article/details/gtaitbvboh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gtszualkxf.html

JS:   greet() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtdndsfodf.html

TS:   greet(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gtjhhqpvqc.html

Java: String greet() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtmebuzqjh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gtyohwgmck.html

Ruby: def greet; @name; end
来源：http://dali.svipenyu.cn/Article/details/gtwrboiuzr.html

C#:   public string Greet() => Name;
来源：http://dali.xinyue.icu/Article/details/gtobbrzadp.html

[G05] 继承
来源：http://dali.xziqi.cn/Article/details/gtncxbtbni.html

Py:   class Admin(User): pass
来源：http://dali.nanxinkj.top/Article/details/gtietyndep.html

PHP:  class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtchlhsvfq.html

JS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtufyidlff.html

TS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtjkgemwnw.html

Java: class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtbrvfkvqj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.kuanghao11.cn/Article/details/gtscdhvqzv.html

Ruby: class Admin < User; end
来源：http://dali.ybcxt.top/Article/details/gtbtmoguqx.html

C#:   class Admin : User {}
来源：http://dali.zhoulong.xyz/Article/details/gtwokdoqyl.html

[G06] 重写方法
来源：http://dali.xziqi.cn/Article/details/gtqzesagkr.html

Py:   def greet(self): return "admin"
来源：http://dali.cucudq.cn/Article/details/gtczrgcbod.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gthdikaaba.html

JS:   greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtmmucydka.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtmzeijamu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtdelrtwsb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuetiantiany.cn/Article/details/gtpqabmojj.html

Ruby: def greet; "admin"; end
来源：http://dali.zhoulong.xyz/Article/details/gtdmhbftdk.html

C#:   public override string Greet() => "admin";
来源：http://dali.mhx1999.top/Article/details/gtifeygiec.html

[G07] 调用父类方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtioxaqras.html

Py:   super().greet()
来源：http://dali.snrcjt.cn/Article/details/gtgjxoqznf.html

PHP:  parent::greet();
来源：http://dali.c1oappe.top/Article/details/gtrbdfzgdx.html

JS:   super.greet();
来源：http://dali.dianchejie.cn/Article/details/gtysbqsrvr.html

TS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gtdnourulc.html

Java: super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtfdlofytw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yongpay.top/Article/details/gtvjklvayu.html

Ruby: super
来源：http://dali.cqqwz.cn/Article/details/gtghcciddh.html

C#:   base.Greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtvxydvigt.html

[G08] 静态方法与属性
来源：http://dali.snrcjt.cn/Article/details/gtswjghnwc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gttxttfxtb.html

PHP:  public static function f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtsqtcrjub.html

JS:   static f() {}
来源：http://dali.xziqi.cn/Article/details/gtahoemxhd.html

TS:   static f(): void {}
来源：http://dali.jqgufenzy.top/Article/details/gtubcetnms.html

Java: static void f() {}
来源：http://dali.xziqi.cn/Article/details/gtvsspptds.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpbgmjjzf.html

Ruby: def self.f; end
来源：http://dali.fengsongda.top/Article/details/gtephvluyc.html

C#:   public static void F() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtshkennhj.html

[G09] 接口 / 抽象类
来源：http://dali.tanke756.top/Article/details/gtsaepqtmn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cucudq.cn/Article/details/gtzvikymym.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.haohaochexian.top/Article/details/gtoeqplmjx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.dashuyun.cn/Article/details/gtcciuaiiy.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhiwuduotai.top/Article/details/gtzdgvpuqc.html

Java: interface Shape { double area(); }
来源：http://dali.cashguo.top/Article/details/gtjixnozyh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.kuanghao11.cn/Article/details/gtkkjmqfho.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.quarkkingdee.top/Article/details/gtjtopzeni.html

C#:   interface IShape { double Area(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtjheunxsb.html

[G10] 访问控制
来源：http://dali.zhengqikj.top/Article/details/gtlufywvml.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.meibo888.top/Article/details/gtqtzgmtow.html

PHP:  public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gtoqlftkyf.html

JS:   #private 字段；其余公开
来源：http://dali.shangyingyoupin.top/Article/details/gtmowlxlhk.html

TS:   public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtefrwwvez.html

Java: public / protected / private / 默认包级
来源：http://dali.feifeiyinyue.top/Article/details/gtmpordovy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cucudq.cn/Article/details/gthfltnuny.html

Ruby: public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gtdjszldwa.html

C#:   public / protected / private / internal
来源：http://dali.mhx1999.top/Article/details/gtzvttubna.html

[G11] getter / setter
来源：http://dali.yvedp.cn/Article/details/gtlkeluwqx.html

Py:   @property 与 @x.setter
来源：http://dali.tianlin.xyz/Article/details/gtmmzqxokg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gtzchnbltk.html

JS:   get name() { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gtpkmisfrb.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtytshyryv.html

Java: public String getName() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtstecxayc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gthdrdxchh.html

Ruby: attr_accessor :name
来源：http://dali.hfpthk.cn/Article/details/gtragyjmrs.html

C#:   public string Name { get; set; }
来源：http://dali.andypj.xyz/Article/details/gtvrdvyimw.html

[G12] 对象转字符串
来源：http://dali.zhengqikj.top/Article/details/gtskdasern.html

Py:   def __str__(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gtkhqktkxx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtglbpyyqf.html

JS:   toString() { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtcdjewpav.html

TS:   toString(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gteyrinxjw.html

Java: @Override public String toString() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtsvsudnwf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gttopeciqo.html

Ruby: def to_s; @name; end
来源：http://dali.jqgfzy.top/Article/details/gtddenrdwm.html

C#:   public override string ToString() => Name;
来源：http://dali.gzhubu.top/Article/details/gtitdfcsed.html

[G13] 判断对象类型
来源：http://dali.tanke756.top/Article/details/gtliteilty.html

Py:   isinstance(u, User)
来源：http://dali.shuidangran.top/Article/details/gtfxhypgvi.html

PHP:  $u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtncdykmsq.html

JS:   u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtsqblwxfd.html

TS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtvfxlduqu.html

Java: u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtsadrhucl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.meibo888.top/Article/details/gtrhbbyfto.html

Ruby: u.is_a?(User)
来源：http://dali.guowangkeji.top/Article/details/gtyeufnhaq.html

C#:   u is User
来源：http://dali.sysykeji.top/Article/details/gtbzwqlhww.html

[G14] 数据类 / record
来源：http://dali.zhiwuduotai.top/Article/details/gtdurfapdz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuanzx.com/Article/details/gtnfrkammt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cucudq.cn/Article/details/gtbkbbhuca.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.svipenyu.cn/Article/details/gtqvhisasm.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gtgdhbsnsd.html

Java: record User(String name, int age) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtjwpstuwj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.meibo888.top/Article/details/gtusljaiwr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoguyumkj.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gtbeafqrdd.html

[G15] 枚举
来源：http://dali.jianghu66.top/Article/details/gttfxfsnpu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.0kj1m.cn/Article/details/gtwcsefgyc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zycfv.cn/Article/details/gtazinsvhw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.mhx1999.top/Article/details/gtdbctqdjv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gtfjmuljia.html

Java: enum Color { RED, GREEN }
来源：http://dali.sysykeji.top/Article/details/gtvgepyegz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jianghu66.top/Article/details/gtdnlfhcsx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.fengsongda.top/Article/details/gttiinawzo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258.top/Article/details/gtmbnoyeqq.html

[G16] 对象转数组 / 字典
来源：http://dali.yvedp.cn/Article/details/gtbjenunmp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xziqi.cn/Article/details/gtvxirciem.html

PHP:  get_object_vars($obj);
来源：http://dali.zhiwuduotai.top/Article/details/gthtssmqgi.html

JS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gtlhrzwtfm.html

TS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtnarlvwxa.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shuidangran.top/Article/details/gtxfqzopyg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nanxinkj.top/Article/details/gtcaxjvwxv.html

Ruby: obj.instance_variables
来源：http://dali.wangdashe.top/Article/details/gtgumjufen.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gtcofoirfh.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtnrvvfcfp.html

H. 异常与错误处理
来源：http://dali.svipenyu.cn/Article/details/gtmkjazryt.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtoxvilzkl.html

[H01] try / catch 基础
来源：http://dali.yongpay.top/Article/details/gtpnlaimoh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigfzy.top/Article/details/gtoxuhtvnj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tanke756.top/Article/details/gtfzkpyuhl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gtsfopcyzl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtrqouecoe.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrmgdder.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.haohaochexian.top/Article/details/gtgvaszcbw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.mhx1999.top/Article/details/gtpvnanmqh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cashguo.top/Article/details/gtuobkspgv.html

[H02] finally / ensure 收尾
来源：http://dali.zdqjudy.top/Article/details/gtnhnmnjse.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ppjwa.cn/Article/details/gtkxovveir.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtjvfeadxn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtupojfyyd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtvaskxyie.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfxcoxwfm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yongpay.top/Article/details/gtxauqhaid.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hongshengwenyu.top/Article/details/gtsmasoftx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtkmyifuzy.html

[H03] 主动抛出异常
来源：http://dali.mhx1999.top/Article/details/gtutobelob.html

Py:   raise ValueError("错误信息")
来源：http://dali.gogol.net.cn/Article/details/gthjtnbgyc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtlyjgsirp.html

JS:   throw new Error("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtljfmmqhq.html

TS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmmbpgbl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtdxvfmsio.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhoulong.xyz/Article/details/gtklqbnovk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tianlin.xyz/Article/details/gtwbldfmvn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtanbnzmzq.html

[H04] 自定义异常类型
来源：http://dali.kuanghao11.cn/Article/details/gteuhtswei.html

Py:   class MyError(Exception): pass
来源：http://dali.sysykeji.top/Article/details/gtoqskuqru.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjwwusoi.html

JS:   class MyError extends Error {}
来源：http://dali.xinyue.icu/Article/details/gthwcyjxyq.html

TS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gtppdxkplq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gtsglgksrj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigfzy.top/Article/details/gtcpthbxdd.html

Ruby: class MyError < StandardError; end
来源：http://dali.hfpthk.cn/Article/details/gteyssdjyw.html

C#:   class MyException : Exception {}
来源：http://dali.svipenyu.cn/Article/details/gtqqfkamlb.html

[H05] 捕获特定类型
来源：http://dali.haohaochexian.top/Article/details/gtkgghaekh.html

Py:   except ValueError as e:
来源：http://dali.nanxuanxn.top/Article/details/gteqwsoaap.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgfzy.top/Article/details/gtebqmyakm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ydzc1.top/Article/details/gtifazyghf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gteasjjeck.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuxming.cn/Article/details/gtweobgcfp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dianchejie.cn/Article/details/gtvqcaviji.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhoulong.xyz/Article/details/gtmkfyttfb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.vqdsnc.cn/Article/details/gtkveqihjn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ehwqpu.com/Article/details/gtqoulifpm.html

Py:   value = d.get("k") or default
来源：http://dali.hywenlv.cn/Article/details/gtpdfgssui.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gtegkrdlzr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxuanxn.top/Article/details/gtbpkdsvsn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunlyqdhl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxuanxn.top/Article/details/gtwdbeqgtr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenjidiqi.icu/Article/details/gtajccmphv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jianghu66.top/Article/details/gtthtgaojh.html

C#:   obj?.A?.B ?? default
来源：http://dali.jiagoushi.top/Article/details/gtmbihdijc.html

[H07] 断言
来源：http://dali.redwolf501.top/Article/details/gtejhdiwmf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.smart0.xyz/Article/details/gtpfbhxdcb.html

PHP:  assert($x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtvarvnejg.html

JS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gtcedcfqmf.html

TS:   console.assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtqokgphmq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.andypj.xyz/Article/details/gtfkxvfqzx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sweek.top/Article/details/gtxyypmjkm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gotoacloud.top/Article/details/gtvwquivzk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtloaebvlp.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gtvixjxkvb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cucudq.cn/Article/details/gtmzcyceal.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hywenlv.cn/Article/details/gtfmresttm.html

JS:   e.message;  e.stack
来源：http://dali.daria6918.cn/Article/details/gtzqlzvjqs.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ppjwa.cn/Article/details/gthvwqbvyp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jiagoushi.top/Article/details/gtbqkqrstj.html

Go:   err.Error()
来源：http://dali.bjfxy.top/Article/details/gtxtmcjqyj.html

Ruby: e.message;  e.backtrace
来源：http://dali.yanxiufei.cn/Article/details/gtanaaptlt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pengpengdd.cyou/Article/details/gtrrsulvlx.html

[H09] 带错误码的异常
来源：http://dali.316326.xyz/Article/details/gtcdceskju.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hfpthk.cn/Article/details/gtmgdlxliv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xinyue.icu/Article/details/gtzcnwgogz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yanxiufei.cn/Article/details/gtufjywrvk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sufxvd.cn/Article/details/gtiuxotirp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenzaomai.com/Article/details/gtrpmbfljd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sxryk.cn/Article/details/gtrugwvupd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zycfv.cn/Article/details/gtszgljafg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj202588.top/Article/details/gtvdpgudhd.html

[H10] 资源自动释放
来源：http://dali.ybcxt.top/Article/details/gtqpocupfs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtflmlgeaa.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tianlin.xyz/Article/details/gtrmzgdozm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gtlqzmldyh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hammf.cn/Article/details/gtwwegxaay.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuypoxcyw.html

Go:   defer f.Close()
来源：http://dali.cqqwz.cn/Article/details/gtyjrdjmfr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yueranfly.top/Article/details/gthzeykmhn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtmvdcvxgp.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtkszlapwa.html

I. 正则表达式
来源：http://dali.dianchejie.cn/Article/details/gtdaaudqyo.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtzscyiagz.html

[I01] 判断是否匹配
来源：http://dali.yj202588.top/Article/details/gtrryfcsla.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pycfn.com/Article/details/gtuxjvjhqw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258888.top/Article/details/gtpuomrswc.html

JS:   /\d+/.test(s)
来源：http://dali.zycfv.cn/Article/details/gtenutzxlo.html

TS:   /\d+/.test(s)
来源：http://dali.quarkkingdee.top/Article/details/gtixopmxud.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.snrcjt.cn/Article/details/gtdesplzxr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.svipenyu.cn/Article/details/gtyrungmqp.html

Ruby: s.match?(/\d+/)
来源：http://dali.hongshengwenyu.top/Article/details/gtfrjftlgd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hammf.cn/Article/details/gtzafcyabo.html

[I02] 提取所有匹配
来源：http://dali.nanxuanxn.top/Article/details/gtzfrzquib.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guowangkeji.top/Article/details/gtpkmgmegu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zdqjudy.top/Article/details/gtjkumzyhg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yangfankeji.com/Article/details/gtlyuptenh.html

TS:   s.match(/\d+/g)
来源：http://dali.wangshuangyany.cn/Article/details/gtenxcnpzp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cheryme.top/Article/details/gthyibdywr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtomufsoiw.html

Ruby: s.scan(/\d+/)
来源：http://dali.9152youxi.cn/Article/details/gtabloynrt.html


<!-- 参考信息 -->