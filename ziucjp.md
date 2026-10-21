代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvpzsvcn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gtnvpacfbk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gtgmwofwaj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guannengcc.top/Article/details/gtlkrossgj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.birdmap.top/Article/details/gtxevoyyir.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gotoacloud.top/Article/details/gtmikepynk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.andypj.xyz/Article/details/gtzbooikhd.html

[F08] 遍历目录
来源：http://dali.gogol.net.cn/Article/details/gtpsoewtwc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.9152youxi.cn/Article/details/gtggzqlfrf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zdqjudy.top/Article/details/gtwwyqkhsy.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtjrzrlslr.html

TS:   fs.readdirSync("dir")
来源：http://dali.smart0.xyz/Article/details/gtrkgzfezx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.snrcjt.cn/Article/details/gtimvlxwdd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gotoacloud.top/Article/details/gtvwvrjaig.html

Ruby: Dir.children("dir")
来源：http://dali.wangdashe.top/Article/details/gtdbszrati.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangdashe.top/Article/details/gtcjhwjjkk.html

[F09] 获取文件大小
来源：http://dali.hysaishi.cn/Article/details/gtmhiqrogd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtfvsfgbye.html

PHP:  filesize("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtxnkrjzsr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hywenlv.cn/Article/details/gtnkgxyqal.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiljbxcbe.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gtjyupsifz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtanjugoxj.html

Ruby: File.size("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtzycpqqsl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nwbrower.top/Article/details/gtsfabsojh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.aibaodan.cn/Article/details/gtdqrvgand.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtyezuineb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtonfbcugb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtnvpeqmns.html

TS:   path.extname("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtrlbycljn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yangfankeji.com/Article/details/gtjeqvusnu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtapvmcgun.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtbfpgcwpy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtpeudlesx.html

[F11] 复制与移动文件
来源：http://dali.jinqigfzy.top/Article/details/gtzfpzvdfp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtaikygyji.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yangfankeji.com/Article/details/gtfnobcile.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gthngxnxds.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtcolubbfh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.redwolf501.top/Article/details/gtojvmxecr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmzcfxjua.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtjfqfmwgn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhixingplan.top/Article/details/gthenieaxu.html

[F12] CSV 读写
来源：http://dali.zycfv.cn/Article/details/gttyiszywy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ydzc1.top/Article/details/gtuhimjufp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.pycfn.com/Article/details/gtugbheeuh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xziqi.cn/Article/details/gtvspyobgv.html

TS:   // 同上
来源：http://dali.sysykeji.top/Article/details/gthqykglci.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ywan-chungtsiang.top/Article/details/gtigxytpsn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.svipenyu.cn/Article/details/gtixoieves.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuzvxrqqz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtglnoamzf.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtqhutclds.html

G. 面向对象
来源：http://dali.jiagoushi.top/Article/details/gtkpacqwpk.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtrywqqfzp.html

[G01] 定义类
来源：http://dali.vqdsnc.cn/Article/details/gtkmqwmukc.html

Py:   class User: pass
来源：http://dali.fzhhl.top/Article/details/gtbduixvpc.html

PHP:  class User {}
来源：http://dali.pycfn.com/Article/details/gtygxfcknb.html

JS:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gtwmyyybqq.html

TS:   class User { name: string = ""; }
来源：http://dali.wangdashe.top/Article/details/gtfiubbenn.html

Java: class User {}
来源：http://dali.yj20258.top/Article/details/gtxffrdfwb.html

Go:   type User struct { Name string }
来源：http://dali.pengpengdd.cyou/Article/details/gtzdiawxtn.html

Ruby: class User; end
来源：http://dali.zhixingplan.top/Article/details/gtsnabrbbi.html

C#:   class User {}
来源：http://dali.sysykeji.top/Article/details/gtxtjocisw.html

[G02] 构造函数
来源：http://dali.sysykeji.top/Article/details/gtjvlksbsp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dianchejie.cn/Article/details/gthakbmhye.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258888.top/Article/details/gtjerruobf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gttvvzsset.html

TS:   constructor(public name: string) {}
来源：http://dali.gogol.net.cn/Article/details/gtwfsictak.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gttzcnpcmv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.c1oappe.top/Article/details/gttxkxamfi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ivvv.top/Article/details/gtynsvtozp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guannengcc.top/Article/details/gtuzubsqxv.html

[G03] 实例属性
来源：http://dali.chenlongwang.top/Article/details/gtkswlehhe.html

Py:   self.name = "x"
来源：http://dali.yvedp.cn/Article/details/gtrxrhhgie.html

PHP:  public string $name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtqicculso.html

JS:   this.name = "x";
来源：http://dali.cqqwz.cn/Article/details/gtgsbkfkhg.html

TS:   name: string = "x";
来源：http://dali.yvedp.cn/Article/details/gteddrwbie.html

Java: private String name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfbdastbs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258888.top/Article/details/gtiowuiqih.html

Ruby: @name = "x"
来源：http://dali.haohaochexian.top/Article/details/gtxhfvnhvg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shuidangran.top/Article/details/gtztpnzlga.html

[G04] 定义方法
来源：http://dali.yonumen.top/Article/details/gtywlnbkfm.html

Py:   def greet(self): return self.name
来源：http://dali.meibo888.top/Article/details/gtfyhpicea.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtxojxjoki.html

JS:   greet() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtwalifftm.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtsptzyxpf.html

Java: String greet() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtnfslwcdb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtvmotwvoo.html

Ruby: def greet; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gtyxharlwn.html

C#:   public string Greet() => Name;
来源：http://dali.yonumen.top/Article/details/gtqmowlxmr.html

[G05] 继承
来源：http://dali.yuanzhike.top/Article/details/gtntjyoiie.html

Py:   class Admin(User): pass
来源：http://dali.yuanzhike.top/Article/details/gtuuixuwyj.html

PHP:  class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtszgchujl.html

JS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtxpwbogxf.html

TS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtnouozpwc.html

Java: class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtfenwztqx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuxming.cn/Article/details/gtmyvhctii.html

Ruby: class Admin < User; end
来源：http://dali.c1oappe.top/Article/details/gtykahtvwz.html

C#:   class Admin : User {}
来源：http://dali.gzhubu.top/Article/details/gtqwvvdclz.html

[G06] 重写方法
来源：http://dali.guannengcc.top/Article/details/gtpeujfwiy.html

Py:   def greet(self): return "admin"
来源：http://dali.guannengcc.top/Article/details/gtbfytmryl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtxswuexdb.html

JS:   greet() { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtwbnzsbdd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtczzggncm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtmzybtdjy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hammf.cn/Article/details/gtijxsvzvd.html

Ruby: def greet; "admin"; end
来源：http://dali.wangdashe.top/Article/details/gthmqoitab.html

C#:   public override string Greet() => "admin";
来源：http://dali.wangdashe.top/Article/details/gttdplhpbp.html

[G07] 调用父类方法
来源：http://dali.hnqzz.top/Article/details/gtermuvxhb.html

Py:   super().greet()
来源：http://dali.chenjidiqi.icu/Article/details/gtpyoybuux.html

PHP:  parent::greet();
来源：http://dali.shangyingyoupin.top/Article/details/gthrhljgzy.html

JS:   super.greet();
来源：http://dali.smart0.xyz/Article/details/gtlongvqym.html

TS:   super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtolwnkgfa.html

Java: super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtxsigmhsl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yvedp.cn/Article/details/gtfnxwyinp.html

Ruby: super
来源：http://dali.kuanghao11.cn/Article/details/gtwsdcvimx.html

C#:   base.Greet();
来源：http://dali.jlsjyb.cn/Article/details/gtlmztbezn.html

[G08] 静态方法与属性
来源：http://dali.haohaochexian.top/Article/details/gtedoxwdzh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhoulong.xyz/Article/details/gtmjankwkq.html

PHP:  public static function f() {}
来源：http://dali.birdmap.top/Article/details/gtnnvmlhsd.html

JS:   static f() {}
来源：http://dali.yj20258888.top/Article/details/gtkpcrcqoj.html

TS:   static f(): void {}
来源：http://dali.sufxvd.cn/Article/details/gtiricxvvr.html

Java: static void f() {}
来源：http://dali.redwolf501.top/Article/details/gtbpneqbqq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shanyushiyangtech.top/Article/details/gtvplxcuyf.html

Ruby: def self.f; end
来源：http://dali.aizwys.cn/Article/details/gtvlnzjfwp.html

C#:   public static void F() {}
来源：http://dali.tian-w.cn/Article/details/gtymmwdoqp.html

[G09] 接口 / 抽象类
来源：http://dali.aibaodan.cn/Article/details/gtoijiovlj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ydzc1.top/Article/details/gtrxtjiwpf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gogol.net.cn/Article/details/gtsvirlhym.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.meibo888.top/Article/details/gtwejibhgm.html

TS:   interface Shape { area(): number; }
来源：http://dali.yuxming.cn/Article/details/gtlbkwphfo.html

Java: interface Shape { double area(); }
来源：http://dali.bjfxy.top/Article/details/gtnzfurhca.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.mhx1999.top/Article/details/gtgjnnwgkh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jqgfzy.top/Article/details/gturmchjnh.html

C#:   interface IShape { double Area(); }
来源：http://dali.havefunace.top/Article/details/gtapwcuban.html

[G10] 访问控制
来源：http://dali.dianchejie.cn/Article/details/gtodjzwpfd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj202588.top/Article/details/gtjxqrhhri.html

PHP:  public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtvkniaano.html

JS:   #private 字段；其余公开
来源：http://dali.jianghu66.top/Article/details/gtwumtrayx.html

TS:   public / protected / private
来源：http://dali.cucudq.cn/Article/details/gtcwwcffds.html

Java: public / protected / private / 默认包级
来源：http://dali.zhongyouzk.top/Article/details/gtxpzzknmd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfuxtuumf.html

Ruby: public / protected / private
来源：http://dali.cheryme.top/Article/details/gtiwzfiwcz.html

C#:   public / protected / private / internal
来源：http://dali.chenjidiqi.icu/Article/details/gtbgthxkmx.html

[G11] getter / setter
来源：http://dali.birdmap.top/Article/details/gtnkfwiuoe.html

Py:   @property 与 @x.setter
来源：http://dali.yueranfly.top/Article/details/gtfryilhbn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtpikeiupi.html

JS:   get name() { return this._name; }
来源：http://dali.guowangkeji.top/Article/details/gtllgumnbd.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gtxjtztszd.html

Java: public String getName() { return name; }
来源：http://dali.tanke756.top/Article/details/gtqoaxpsyn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gtcfobjiom.html

Ruby: attr_accessor :name
来源：http://dali.yangfankeji.com/Article/details/gtuhjctfdi.html

C#:   public string Name { get; set; }
来源：http://dali.ivvv.top/Article/details/gtartpixkg.html

[G12] 对象转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtapvgfjrj.html

Py:   def __str__(self): return self.name
来源：http://dali.shanyushiyangtech.top/Article/details/gtggmoicxe.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gtlszkdshk.html

JS:   toString() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtajsukvsw.html

TS:   toString(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtrdusdgbe.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj20258888.top/Article/details/gtfazissfz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gtcdcocixg.html

Ruby: def to_s; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gtqqfyquno.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigufen.top/Article/details/gtcjlhrtiw.html

[G13] 判断对象类型
来源：http://dali.fengsongda.top/Article/details/gttekydcom.html

Py:   isinstance(u, User)
来源：http://dali.hfpthk.cn/Article/details/gturzukxem.html

PHP:  $u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtteskuyuy.html

JS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtxstwketb.html

TS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gtgsjjcaku.html

Java: u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtkutpepgm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nwbrower.top/Article/details/gtxueqgaic.html

Ruby: u.is_a?(User)
来源：http://dali.sysykeji.top/Article/details/gtubufpgbr.html

C#:   u is User
来源：http://dali.dianchejie.cn/Article/details/gtxinsswrb.html

[G14] 数据类 / record
来源：http://dali.daxiang520.top/Article/details/gtltsghphy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cqqwz.cn/Article/details/gtkycxxviu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.wangdashe.top/Article/details/gtgxprweui.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuanzhike.top/Article/details/gtohpvyhtz.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhoulong.xyz/Article/details/gtggkqtemx.html

Java: record User(String name, int age) {}
来源：http://dali.jiagoushi.top/Article/details/gtmbvywvex.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tanke756.top/Article/details/gtsvdwveyl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gzhubu.top/Article/details/gtfvfbcmpa.html

C#:   record User(string Name, int Age);
来源：http://dali.vqdsnc.cn/Article/details/gtivfxnbhz.html

[G15] 枚举
来源：http://dali.316326.xyz/Article/details/gtpqcjuepu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jianghu66.top/Article/details/gtimfetaci.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jlsjyb.cn/Article/details/gtfslyfkch.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zdqjudy.top/Article/details/gtgwwszsno.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.smart0.xyz/Article/details/gtisrnwkls.html

Java: enum Color { RED, GREEN }
来源：http://dali.smart0.xyz/Article/details/gtiwxmiqsk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jianghu66.top/Article/details/gteknoasit.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxuanxn.top/Article/details/gtxtwdvhyf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gtvmhgkcqr.html

[G16] 对象转数组 / 字典
来源：http://dali.andypj.xyz/Article/details/gthqjmvlzo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.svipenyu.cn/Article/details/gthnuefsge.html

PHP:  get_object_vars($obj);
来源：http://dali.wangshuangyany.cn/Article/details/gtdcsrsxab.html

JS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gtzahleere.html

TS:   Object.entries(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtnjrhbfpv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.smart0.xyz/Article/details/gtfyomtgyk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzcqnqgum.html

Ruby: obj.instance_variables
来源：http://dali.yueranfly.top/Article/details/gtwcslbjvc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cheryme.top/Article/details/gtomjcpkgs.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtuolfngkk.html

H. 异常与错误处理
来源：http://dali.jyoumei.cn/Article/details/gtzjrxclrp.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtlljsaswc.html

[H01] try / catch 基础
来源：http://dali.yuanzhike.top/Article/details/gtvxnnfabv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.redwolf501.top/Article/details/gtjsywgsrm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xuanzx.com/Article/details/gtbxkbkpck.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gtftmqoqgi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gtapxhcyym.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sysykeji.top/Article/details/gtdlqxfodi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nwbrower.top/Article/details/gtrfyawryb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.havefunace.top/Article/details/gtmxihydxz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cashguo.top/Article/details/gtloolfssn.html

[H02] finally / ensure 收尾
来源：http://dali.hnqzz.top/Article/details/gtffduecxr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pycfn.com/Article/details/gthwmjhoou.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtxtsongmg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtcnqcmdzy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtpacgvprh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtehwlvpyf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daxiang520.top/Article/details/gtwvkbpuor.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dashuyun.cn/Article/details/gtoyaoowwl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtvzxdrumo.html

[H03] 主动抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gtwkssalac.html

Py:   raise ValueError("错误信息")
来源：http://dali.yvedp.cn/Article/details/gthrrlqmkj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtpyzmneal.html

JS:   throw new Error("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtmxlwddum.html

TS:   throw new Error("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtlvngpnvb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtvmvrvphc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hfpthk.cn/Article/details/gtwatbhpyp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnxiangtu.top/Article/details/gtqjedhxtc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtqgcnxrrj.html

[H04] 自定义异常类型
来源：http://dali.haohaochexian.top/Article/details/gtnbwtrkgo.html

Py:   class MyError(Exception): pass
来源：http://dali.jiagoushi.top/Article/details/gtprggdrxd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ivvv.top/Article/details/gtkejjpvlo.html

JS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtoacruyhb.html

TS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gtuexkexfk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.meibo888.top/Article/details/gtidzrpwhw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xylfe.cn/Article/details/gtuvodffhw.html

Ruby: class MyError < StandardError; end
来源：http://dali.havefunace.top/Article/details/gtponvrxhk.html

C#:   class MyException : Exception {}
来源：http://dali.cdnleiting.top/Article/details/gtrtbnpjff.html

[H05] 捕获特定类型
来源：http://dali.cucudq.cn/Article/details/gtnozeugec.html

Py:   except ValueError as e:
来源：http://dali.meibo888.top/Article/details/gtjcovanwe.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.quarkkingdee.top/Article/details/gtmslvydkx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gtyrhcjgjh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nanxuanxn.top/Article/details/gtrwpymjqw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.redwolf501.top/Article/details/gtfsbltewl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hnxiangtu.top/Article/details/gtxcrwzwam.html

Ruby: rescue ArgumentError => e
来源：http://dali.dianchejie.cn/Article/details/gtviutxgyj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.andypj.xyz/Article/details/gtdcpnmbsw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.havefunace.top/Article/details/gtgxygjqgv.html

Py:   value = d.get("k") or default
来源：http://dali.gaohongyu789.top/Article/details/gtvtxgbfhv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tianlin.xyz/Article/details/gtbtckicdf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gtoybvodgp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gttwadfgjn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aizwys.cn/Article/details/gtqkqrcufx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gzhubu.top/Article/details/gtdjivmkju.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gtdebxpatl.html

C#:   obj?.A?.B ?? default
来源：http://dali.ehwqpu.com/Article/details/gtjwfillby.html

[H07] 断言
来源：http://dali.yanxiufei.cn/Article/details/gtaybismtv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj202588.top/Article/details/gtnufhsjth.html

PHP:  assert($x > 0);
来源：http://dali.redwolf501.top/Article/details/gtdvxspbbw.html

JS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlqlakuto.html

TS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtifiabpln.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aibaodan.cn/Article/details/gtwaygniri.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenlongwang.top/Article/details/gtglwmukce.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigfzy.top/Article/details/gtvavlnllw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gtbjjnaoqr.html

[H08] 获取错误信息与堆栈
来源：http://dali.bjfxy.top/Article/details/gtgciuwzkq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jlsjyb.cn/Article/details/gtolkvvezy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gtqctdoown.html

JS:   e.message;  e.stack
来源：http://dali.yuxming.cn/Article/details/gtvorkvkjg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gogol.net.cn/Article/details/gtypzuedyb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.0kj1m.cn/Article/details/gtsbkwiwut.html

Go:   err.Error()
来源：http://dali.0kj1m.cn/Article/details/gtkanvjnfr.html

Ruby: e.message;  e.backtrace
来源：http://dali.daria6918.cn/Article/details/gtohijhrlx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sysykeji.top/Article/details/gtrkhchhxj.html

[H09] 带错误码的异常
来源：http://dali.ehwqpu.com/Article/details/gtfagywzdl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sweek.top/Article/details/gtqyzozuxu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.aizwys.cn/Article/details/gtmnidhwni.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yvedp.cn/Article/details/gtibjsfqwg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.mhx1999.top/Article/details/gtlazbdcpa.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gzhubu.top/Article/details/gtycadkzpp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sysykeji.top/Article/details/gtozaycqvv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cucudq.cn/Article/details/gtgpsxksnu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.snrcjt.cn/Article/details/gtiftoslrw.html

[H10] 资源自动释放
来源：http://dali.zhiwuduotai.top/Article/details/gtohqqhekl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shanyushiyangkeji.top/Article/details/gttatsebcc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xziqi.cn/Article/details/gtqjmajcye.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuanzx.com/Article/details/gtwcjdfurh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gtplfzkkkv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hammf.cn/Article/details/gtcagvusim.html

Go:   defer f.Close()
来源：http://dali.pengpengdd.cyou/Article/details/gtiiigyxte.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ehwqpu.com/Article/details/gtxkvwmqus.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtlwwdabgr.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtzchcmghg.html

I. 正则表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzbrpskad.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtqaevijzp.html

[I01] 判断是否匹配
来源：http://dali.aizwys.cn/Article/details/gtjsgperpq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtojptsjap.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cucudq.cn/Article/details/gtkjmjkrki.html

JS:   /\d+/.test(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtrlmnsdiw.html

TS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gtbvifgnkv.html


<!-- 参考信息 -->