代发 wailian999

[F09] 获取文件大小
来源：http://dali.gaohongyu789.top/Article/details/gtlwuwpqul.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtqyzjqbvq.html

PHP:  filesize("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfrranvki.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gtnekncwli.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sufxvd.cn/Article/details/gtzmvnshsy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtoxpjkvud.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.bjfxy.top/Article/details/gtyaipkhat.html

Ruby: File.size("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtwjmrislz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shuidangran.top/Article/details/gtwijuvqxi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.aibaodan.cn/Article/details/gtgyhbfnbk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcnwgneoy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtgmbvpkdk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtymydtrxd.html

TS:   path.extname("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtylwbjrbz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pengpengdd.cyou/Article/details/gtfdlaflyy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtlorbsxus.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtmohovkxc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtstlwpsut.html

[F11] 复制与移动文件
来源：http://dali.yangfankeji.com/Article/details/gtohzyoimo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtqcbirgbw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cashguo.top/Article/details/gtsgjkjgep.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtjrcfxvtg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtmzjmgtnq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.haohaochexian.top/Article/details/gtfbnbwgjx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.iojbl.cn/Article/details/gtjxrtireq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gthgngqgoc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.feifeiyinyue.top/Article/details/gtnnxmoymr.html

[F12] CSV 读写
来源：http://dali.dashuyun.cn/Article/details/gtcoiwhvxr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhixingplan.top/Article/details/gtptjxmboq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jianghu66.top/Article/details/gtmrquiavk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daxiang520.top/Article/details/gtdzuudswz.html

TS:   // 同上
来源：http://dali.cheryme.top/Article/details/gtylkvrtzk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fengsongda.top/Article/details/gtdvhvleal.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.wangdashe.top/Article/details/gtqzzpgsoa.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gtsgckpfmo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cdnleiting.top/Article/details/gtfixuqnby.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtlfovgaps.html

G. 面向对象
来源：http://dali.shanyushiyangtech.top/Article/details/gtvgepzznn.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtobmxzjop.html

[G01] 定义类
来源：http://dali.vqdsnc.cn/Article/details/gtzotzlelq.html

Py:   class User: pass
来源：http://dali.hammf.cn/Article/details/gtreimigfk.html

PHP:  class User {}
来源：http://dali.wangdashe.top/Article/details/gtcbgqgdhk.html

JS:   class User {}
来源：http://dali.zycfv.cn/Article/details/gtyftooyhp.html

TS:   class User { name: string = ""; }
来源：http://dali.kuanghao11.cn/Article/details/gtxcohwyxn.html

Java: class User {}
来源：http://dali.zdqjudy.top/Article/details/gtpnrxmhph.html

Go:   type User struct { Name string }
来源：http://dali.zhixingplan.top/Article/details/gtvlhssdrj.html

Ruby: class User; end
来源：http://dali.sufxvd.cn/Article/details/gtbvhflena.html

C#:   class User {}
来源：http://dali.yuxming.cn/Article/details/gtshbldkdn.html

[G02] 构造函数
来源：http://dali.shzxlz.cn/Article/details/gtcyqpakbs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtupeghyct.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dashuyun.cn/Article/details/gtqiichdkn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtwmctdhqv.html

TS:   constructor(public name: string) {}
来源：http://dali.zycfv.cn/Article/details/gtwwabsvbt.html

Java: User(String name) { this.name = name; }
来源：http://dali.gotoacloud.top/Article/details/gtancjpxqa.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxlhbxyef.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hammf.cn/Article/details/gtkgbmmnug.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xinyue.icu/Article/details/gtczsbaqko.html

[G03] 实例属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcekeryzh.html

Py:   self.name = "x"
来源：http://dali.hnxiangtu.top/Article/details/gtqmfxvlqe.html

PHP:  public string $name = "x";
来源：http://dali.nwbrower.top/Article/details/gtemvcmlag.html

JS:   this.name = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqapohzzp.html

TS:   name: string = "x";
来源：http://dali.9152youxi.cn/Article/details/gtyzlpzvhq.html

Java: private String name;
来源：http://dali.hfpthk.cn/Article/details/gtzwzdsvwn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhoulong.xyz/Article/details/gtmxdcypub.html

Ruby: @name = "x"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtndguesuj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jyoumei.cn/Article/details/gtyskfbslj.html

[G04] 定义方法
来源：http://dali.xziqi.cn/Article/details/gtngsuivor.html

Py:   def greet(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gtzgroadol.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gtovcjbymi.html

JS:   greet() { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtssrcyfzx.html

TS:   greet(): string { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtfmqkailv.html

Java: String greet() { return name; }
来源：http://dali.sweek.top/Article/details/gtqgbohpls.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gtbharbkew.html

Ruby: def greet; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gtauowxmbc.html

C#:   public string Greet() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gtahvxnhie.html

[G05] 继承
来源：http://dali.nanxuanxn.top/Article/details/gtegieitjp.html

Py:   class Admin(User): pass
来源：http://dali.pycfn.com/Article/details/gtjvhugmjf.html

PHP:  class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtsqllxnen.html

JS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtxuheohut.html

TS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtdbxzdwwj.html

Java: class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtltqjrlpg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhengqikj.top/Article/details/gtkaazqcrp.html

Ruby: class Admin < User; end
来源：http://dali.xziqi.cn/Article/details/gtpxnclfeb.html

C#:   class Admin : User {}
来源：http://dali.9152youxi.cn/Article/details/gtnisnuvir.html

[G06] 重写方法
来源：http://dali.mhx1999.top/Article/details/gtmjucrplu.html

Py:   def greet(self): return "admin"
来源：http://dali.iojbl.cn/Article/details/gtptkopncd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtvfhnkewz.html

JS:   greet() { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtnsnbsaar.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtdjxsxotn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gttzafdpgv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nanxuanxn.top/Article/details/gtkeqqkktq.html

Ruby: def greet; "admin"; end
来源：http://dali.jianghu66.top/Article/details/gtlnfmechq.html

C#:   public override string Greet() => "admin";
来源：http://dali.xylfe.cn/Article/details/gtjtuxkcyo.html

[G07] 调用父类方法
来源：http://dali.nanxinkj.top/Article/details/gtikkwuqrb.html

Py:   super().greet()
来源：http://dali.chenjidiqi.icu/Article/details/gtlshseaoh.html

PHP:  parent::greet();
来源：http://dali.zhengqikj.top/Article/details/gtgvredswr.html

JS:   super.greet();
来源：http://dali.andypj.xyz/Article/details/gtretdslek.html

TS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gtsenusuaa.html

Java: super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqfsuhtwx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.guowangkeji.top/Article/details/gtfkgpdskh.html

Ruby: super
来源：http://dali.yueranfly.top/Article/details/gtfiekoiyk.html

C#:   base.Greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtwbnpjhbw.html

[G08] 静态方法与属性
来源：http://dali.yuxming.cn/Article/details/gtunjrkuay.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangdashe.top/Article/details/gtngrocdvi.html

PHP:  public static function f() {}
来源：http://dali.yvedp.cn/Article/details/gtptpghzyg.html

JS:   static f() {}
来源：http://dali.sweek.top/Article/details/gtwhanflup.html

TS:   static f(): void {}
来源：http://dali.hnxiangtu.top/Article/details/gttojqrabd.html

Java: static void f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtxeatotad.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.9152youxi.cn/Article/details/gtsssnqjpz.html

Ruby: def self.f; end
来源：http://dali.feifeiyinyue.top/Article/details/gtgridrivj.html

C#:   public static void F() {}
来源：http://dali.aibaodan.cn/Article/details/gtngnwgluk.html

[G09] 接口 / 抽象类
来源：http://dali.9152youxi.cn/Article/details/gtwbvqchoj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.316326.xyz/Article/details/gtbsnsebkc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gotoacloud.top/Article/details/gthzyipefh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yonumen.top/Article/details/gtateksifn.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gtyuaqkazc.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258.top/Article/details/gtcdalhlxv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.wangshuangyany.cn/Article/details/gtibzmioet.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jqgfzy.top/Article/details/gtfzgesfzv.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtuszwevwl.html

[G10] 访问控制
来源：http://dali.sysykeji.top/Article/details/gtfvkehwzx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.birdmap.top/Article/details/gtupddckty.html

PHP:  public / protected / private
来源：http://dali.bjfxy.top/Article/details/gtmsovafng.html

JS:   #private 字段；其余公开
来源：http://dali.fzhhl.top/Article/details/gtxyouajbx.html

TS:   public / protected / private
来源：http://dali.hammf.cn/Article/details/gtyjlstvxi.html

Java: public / protected / private / 默认包级
来源：http://dali.sweek.top/Article/details/gthvyjtywq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daxiang520.top/Article/details/gtpvtkhbbw.html

Ruby: public / protected / private
来源：http://dali.xylfe.cn/Article/details/gttbllovgs.html

C#:   public / protected / private / internal
来源：http://dali.jinqigufen.top/Article/details/gttiwoyuip.html

[G11] getter / setter
来源：http://dali.jianghu66.top/Article/details/gtdelehiro.html

Py:   @property 与 @x.setter
来源：http://dali.pengpengdd.cyou/Article/details/gtohuorass.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gtnnyvauae.html

JS:   get name() { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gtritaslvw.html

TS:   get name(): string { return this._name; }
来源：http://dali.gaohongyu789.top/Article/details/gtbnlrkclb.html

Java: public String getName() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtavjyjhrg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gthnvkoihj.html

Ruby: attr_accessor :name
来源：http://dali.jiagoushi.top/Article/details/gtwrclqhnz.html

C#:   public string Name { get; set; }
来源：http://dali.tianlin.xyz/Article/details/gtldlvriso.html

[G12] 对象转字符串
来源：http://dali.svipenyu.cn/Article/details/gtikawbfim.html

Py:   def __str__(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gtayhikotu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtcbiucbwn.html

JS:   toString() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtncqgqrfj.html

TS:   toString(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtiluermxd.html

Java: @Override public String toString() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtlcroxhrp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtzqcwaiey.html

Ruby: def to_s; @name; end
来源：http://dali.yongpay.top/Article/details/gtboobipnl.html

C#:   public override string ToString() => Name;
来源：http://dali.yuxming.cn/Article/details/gtugszixrv.html

[G13] 判断对象类型
来源：http://dali.yvedp.cn/Article/details/gtknohpxgc.html

Py:   isinstance(u, User)
来源：http://dali.jiagoushi.top/Article/details/gtklzfboxx.html

PHP:  $u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gttnoyilxs.html

JS:   u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtycigebng.html

TS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtwujmepyj.html

Java: u instanceof User
来源：http://dali.yj202588.top/Article/details/gtoazerhcb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.snrcjt.cn/Article/details/gtvqfpyynq.html

Ruby: u.is_a?(User)
来源：http://dali.tianlin.xyz/Article/details/gtxllmadja.html

C#:   u is User
来源：http://dali.jiagoushi.top/Article/details/gtclvzcqfg.html

[G14] 数据类 / record
来源：http://dali.zhongyouzk.top/Article/details/gtgcqtwezs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuanzx.com/Article/details/gtprfftyfv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dashuyun.cn/Article/details/gtwojqvnvs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenlongwang.top/Article/details/gthqdqzfjd.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gtkbaxhnlr.html

Java: record User(String name, int age) {}
来源：http://dali.dashuyun.cn/Article/details/gtlsrryafi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ppjwa.cn/Article/details/gtywegqwmw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmbhqbtq.html

C#:   record User(string Name, int Age);
来源：http://dali.feifeiyinyue.top/Article/details/gtsplwycsu.html

[G15] 枚举
来源：http://dali.yonumen.top/Article/details/gtrqrfssoq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ehwqpu.com/Article/details/gtjtrghzxc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.316326.xyz/Article/details/gtewoisjtd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hnqzz.top/Article/details/gtgsxgjqwn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.9152youxi.cn/Article/details/gtnhruobhj.html

Java: enum Color { RED, GREEN }
来源：http://dali.0kj1m.cn/Article/details/gthzvhmyfi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenjidiqi.icu/Article/details/gtbrhlpxtb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigfzy.top/Article/details/gtqedukmlv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtqvngdzdx.html

[G16] 对象转数组 / 字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gthmoneyci.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhixingplan.top/Article/details/gtehvcqdze.html

PHP:  get_object_vars($obj);
来源：http://dali.xziqi.cn/Article/details/gtmvxyrojj.html

JS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gtihaonjie.html

TS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gtxfdzfmxs.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwnzikrd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gzhubu.top/Article/details/gtvxggqdcy.html

Ruby: obj.instance_variables
来源：http://dali.nanxuanxn.top/Article/details/gtdwvtybrt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gtpvuwjsug.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtftckquqg.html

H. 异常与错误处理
来源：http://dali.gogol.net.cn/Article/details/gtouvhxpzd.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gthaxnbpkn.html

[H01] try / catch 基础
来源：http://dali.fzhhl.top/Article/details/gtbjgvnrnk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuxming.cn/Article/details/gtkeuqmcch.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yangfankeji.com/Article/details/gtxxqdjdmb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gttlllhlux.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gttotvzhvo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gzhubu.top/Article/details/gtiymmjxln.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sweek.top/Article/details/gtbegujmlc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dianchejie.cn/Article/details/gtbslviyjq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.kuanghao11.cn/Article/details/gtcstksptk.html

[H02] finally / ensure 收尾
来源：http://dali.andypj.xyz/Article/details/gtqcfbcgev.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hysaishi.cn/Article/details/gtzohpvhiy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtmubswprl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtzyzutiuk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtyoibkhpv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtlfdsiarm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yvedp.cn/Article/details/gtqtcwznpt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgfzy.top/Article/details/gttkokafgh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtxkmdihox.html

[H03] 主动抛出异常
来源：http://dali.sysykeji.top/Article/details/gtjjtyvhym.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnqzz.top/Article/details/gtkxwlcten.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gteueauqbc.html

JS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gtruezaxpk.html

TS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtgrwvsens.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtwbhdgvtc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.snrcjt.cn/Article/details/gtrunxcknp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.quarkkingdee.top/Article/details/gtwlcxrzxp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtxjukfefx.html

[H04] 自定义异常类型
来源：http://dali.pengpengdd.cyou/Article/details/gtgpfqqbwr.html

Py:   class MyError(Exception): pass
来源：http://dali.hnqzz.top/Article/details/gtvsmhlweg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gtluskexpf.html

JS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gtwzbigcph.html

TS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gtwpttunub.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gteraeipbj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sxryk.cn/Article/details/gtogidcskp.html

Ruby: class MyError < StandardError; end
来源：http://dali.ydzc1.top/Article/details/gtmmcvorcy.html

C#:   class MyException : Exception {}
来源：http://dali.chenjidiqi.icu/Article/details/gtmsevlldj.html

[H05] 捕获特定类型
来源：http://dali.9152youxi.cn/Article/details/gtqocczjci.html

Py:   except ValueError as e:
来源：http://dali.svipenyu.cn/Article/details/gtjmrvgncc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ybcxt.top/Article/details/gtdzlkcktf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gtsehxzwnt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gtlkaqhzon.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zycfv.cn/Article/details/gtxlzzwtkv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ydzc1.top/Article/details/gtaqhnizrf.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhiwuduotai.top/Article/details/gtyxhdenjk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenlongwang.top/Article/details/gtvwtldjer.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigufen.top/Article/details/gtcoqopdon.html

Py:   value = d.get("k") or default
来源：http://dali.316326.xyz/Article/details/gtorguuqon.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.birdmap.top/Article/details/gtwdvyqjcp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gtuzoexscg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gtfghcjlnl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxuanxn.top/Article/details/gtfsbsjxng.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.c1oappe.top/Article/details/gtybmrzgrt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenjidiqi.icu/Article/details/gtzhlokahh.html

C#:   obj?.A?.B ?? default
来源：http://dali.pycfn.com/Article/details/gtxihmxehx.html

[H07] 断言
来源：http://dali.zhoulong.xyz/Article/details/gtjozmstgy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangtech.top/Article/details/gtevhycvvm.html

PHP:  assert($x > 0);
来源：http://dali.jianghu66.top/Article/details/gtbcdpszsr.html

JS:   console.assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtdquniisw.html

TS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtipfgagwp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhxqxpkr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhengqikj.top/Article/details/gtlguinjok.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jqgufenzy.top/Article/details/gtbobnqcje.html

C#:   Debug.Assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gticutxkxw.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigufen.top/Article/details/gtxpuvgoik.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.havefunace.top/Article/details/gtorhgcuui.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangdashe.top/Article/details/gtkjlkybdf.html

JS:   e.message;  e.stack
来源：http://dali.smart0.xyz/Article/details/gtjdtteodl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258888.top/Article/details/gtwbpotafs.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ppjwa.cn/Article/details/gtogkpghrd.html

Go:   err.Error()
来源：http://dali.316326.xyz/Article/details/gtocyrnmko.html

Ruby: e.message;  e.backtrace
来源：http://dali.gogol.net.cn/Article/details/gtjqajwtou.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxuanxn.top/Article/details/gtjbfexumh.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtroegqmnx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.andypj.xyz/Article/details/gtogcpyqxb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgwzitwmu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yueranfly.top/Article/details/gttiiwycol.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ppjwa.cn/Article/details/gtvmziexcx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.dianchejie.cn/Article/details/gtpdxrgqum.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.havefunace.top/Article/details/gtovcibpmk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zycfv.cn/Article/details/gtfxzovewd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xziqi.cn/Article/details/gthpmmpgst.html

[H10] 资源自动释放
来源：http://dali.zhengqikj.top/Article/details/gtqcnxcseq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.iojbl.cn/Article/details/gteiyotqch.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.kuanghao11.cn/Article/details/gtqgvpqczs.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gtzangiygt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ivvv.top/Article/details/gtgmxpghfp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.havefunace.top/Article/details/gtcdlmjkoo.html

Go:   defer f.Close()
来源：http://dali.jyoumei.cn/Article/details/gtffryyica.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cucudq.cn/Article/details/gtlrubgbyw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtdjovsmrs.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthlrqexfs.html

I. 正则表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwsvhtvca.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtldhmxlta.html

[I01] 判断是否匹配
来源：http://dali.sufxvd.cn/Article/details/gtaabtjtws.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gthxmpbhjc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtmepzsomc.html

JS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gteuhitjid.html

TS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gttqkensbn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sysykeji.top/Article/details/gtswqocfhw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.bjfxy.top/Article/details/gtxvxfvaiz.html

Ruby: s.match?(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gtadywbmrr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadmesdrf.html

[I02] 提取所有匹配
来源：http://dali.cdnleiting.top/Article/details/gtatfxkqbs.html

Py:   re.findall(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gthldzwrbw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.wangshuangyany.cn/Article/details/gtnhgmvlcu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xuetiantiany.cn/Article/details/gtshrtvmbz.html

TS:   s.match(/\d+/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuyjbiclf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jlsjyb.cn/Article/details/gtcmsyezgp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ppjwa.cn/Article/details/gtebuuifaa.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangshuangyany.cn/Article/details/gtoaemdrhu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.redwolf501.top/Article/details/gtrhjyottm.html

[I03] 提取捕获分组
来源：http://dali.vqdsnc.cn/Article/details/gtjhzwiaje.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sufxvd.cn/Article/details/gtyerjtmld.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jqgfzy.top/Article/details/gtliqysnyv.html


<!-- 参考信息 -->