代发 wailian999

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtmppjmr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guowangkeji.top/Article/details/gtzwivvtdu.html

JS:   fs.readdirSync("dir")
来源：http://dali.ybcxt.top/Article/details/gtejsuqhwn.html

TS:   fs.readdirSync("dir")
来源：http://dali.cdnleiting.top/Article/details/gttkywaubg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj20258.top/Article/details/gtookprklw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.aibaodan.cn/Article/details/gtqmftcdwk.html

Ruby: Dir.children("dir")
来源：http://dali.haohaochexian.top/Article/details/gtksalqbss.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hysaishi.cn/Article/details/gttmbxatru.html

[F09] 获取文件大小
来源：http://dali.jqgfzy.top/Article/details/gtrxkmmxtd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtrzpgqomi.html

PHP:  filesize("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gttyjmoghe.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yongpay.top/Article/details/gtdkibiobx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gtbamwsand.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gtkgtvgsvi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xuanzx.com/Article/details/gtjokwqepj.html

Ruby: File.size("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtpnfqclpe.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shanyushiyangtech.top/Article/details/gtcdqocndd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yongpay.top/Article/details/gtrylrohqa.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtdqjzzvvy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tian-w.cn/Article/details/gtmswtjqtt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtqrtamdow.html

TS:   path.extname("a.txt")
来源：http://dali.hnqzz.top/Article/details/gteksfaqvd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dashuyun.cn/Article/details/gtbszetbva.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtqelfcgbj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtoidgyybc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtkoyxdvwx.html

[F11] 复制与移动文件
来源：http://dali.guannengcc.top/Article/details/gtrhgrkjtw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtsipfijna.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dashuyun.cn/Article/details/gthqvuwpph.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtxhvrxaxy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gtqedrtweg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqxximtg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.birdmap.top/Article/details/gthwaavowa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtamthhwwa.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gogol.net.cn/Article/details/gtwfjuuhly.html

[F12] CSV 读写
来源：http://dali.tianlin.xyz/Article/details/gtkevsjgmk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.birdmap.top/Article/details/gtuxmbjljg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.fzhhl.top/Article/details/gtwflelxei.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jianghu66.top/Article/details/gtuiyluclu.html

TS:   // 同上
来源：http://dali.fengsongda.top/Article/details/gtvkianzjq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.9152youxi.cn/Article/details/gtgfenjwhm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xziqi.cn/Article/details/gtwuvhumym.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fengsongda.top/Article/details/gtntlrbomj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gttannpayo.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gturmgudwt.html

G. 面向对象
来源：http://dali.bjfxy.top/Article/details/gtkssadikb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtqtcwyjga.html

[G01] 定义类
来源：http://dali.birdmap.top/Article/details/gthjpjmjml.html

Py:   class User: pass
来源：http://dali.vqdsnc.cn/Article/details/gthyviosjm.html

PHP:  class User {}
来源：http://dali.daxiang520.top/Article/details/gtkmdkwxwb.html

JS:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gtodndguph.html

TS:   class User { name: string = ""; }
来源：http://dali.ydzc1.top/Article/details/gtqocilzya.html

Java: class User {}
来源：http://dali.hnqzz.top/Article/details/gtofbdxsqv.html

Go:   type User struct { Name string }
来源：http://dali.gotoacloud.top/Article/details/gtxfbcvetj.html

Ruby: class User; end
来源：http://dali.bjfxy.top/Article/details/gtnpbzsieg.html

C#:   class User {}
来源：http://dali.aizwys.cn/Article/details/gtnahpoekl.html

[G02] 构造函数
来源：http://dali.yvedp.cn/Article/details/gtnwschxrw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.316326.xyz/Article/details/gtoevgcqkl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xziqi.cn/Article/details/gtyuiwfgzh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gtzsdefbvg.html

TS:   constructor(public name: string) {}
来源：http://dali.nanxinkj.top/Article/details/gtaprgjrmq.html

Java: User(String name) { this.name = name; }
来源：http://dali.yuanzhike.top/Article/details/gtqscgyhlk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yonumen.top/Article/details/gtakunlvax.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hammf.cn/Article/details/gtjatogqhy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gtbjafdfxq.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gtkhfhtafk.html

Py:   self.name = "x"
来源：http://dali.cashguo.top/Article/details/gtitjrzzde.html

PHP:  public string $name = "x";
来源：http://dali.c1oappe.top/Article/details/gtvlcuggqv.html

JS:   this.name = "x";
来源：http://dali.yj20258888.top/Article/details/gtxdlbqbwt.html

TS:   name: string = "x";
来源：http://dali.ivvv.top/Article/details/gtscoeclpm.html

Java: private String name;
来源：http://dali.hnxiangtu.top/Article/details/gtuobxrfzn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenzaomai.com/Article/details/gtondmgxqu.html

Ruby: @name = "x"
来源：http://dali.aibaodan.cn/Article/details/gtkgqrwxyq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj20258.top/Article/details/gtakaduscd.html

[G04] 定义方法
来源：http://dali.jianghu66.top/Article/details/gtpyanbkqf.html

Py:   def greet(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gtrhxtqnsu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gtkkmngtcp.html

JS:   greet() { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtccdqzcwk.html

TS:   greet(): string { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtholfsxni.html

Java: String greet() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxidoikor.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gtmjdxyser.html

Ruby: def greet; @name; end
来源：http://dali.jyoumei.cn/Article/details/gtfcncxumr.html

C#:   public string Greet() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gtcdrcriuj.html

[G05] 继承
来源：http://dali.pengpengdd.cyou/Article/details/gtadvukwvj.html

Py:   class Admin(User): pass
来源：http://dali.zhengqikj.top/Article/details/gtvinwempz.html

PHP:  class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtlhagdkje.html

JS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtfipsevyd.html

TS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtjwyjoxay.html

Java: class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtwssqwfev.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.quarkkingdee.top/Article/details/gtlqzqfvcc.html

Ruby: class Admin < User; end
来源：http://dali.ehwqpu.com/Article/details/gtizqctkar.html

C#:   class Admin : User {}
来源：http://dali.snrcjt.cn/Article/details/gthkcimvrk.html

[G06] 重写方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gttrefugtk.html

Py:   def greet(self): return "admin"
来源：http://dali.hongshengwenyu.top/Article/details/gticqlaslx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtesbzupli.html

JS:   greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtebzasgjb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtorrxkuiv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtzilpweqe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pengpengdd.cyou/Article/details/gtqkzdddbi.html

Ruby: def greet; "admin"; end
来源：http://dali.zhoulong.xyz/Article/details/gtsuijryqr.html

C#:   public override string Greet() => "admin";
来源：http://dali.vqdsnc.cn/Article/details/gtrccloxls.html

[G07] 调用父类方法
来源：http://dali.jinqigfzy.top/Article/details/gtuaegnvqt.html

Py:   super().greet()
来源：http://dali.9152youxi.cn/Article/details/gtfvgpqytm.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gtntodrkbp.html

JS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtggsmjxzi.html

TS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtzfhwysep.html

Java: super.greet();
来源：http://dali.zhengqikj.top/Article/details/gtnncrzbhv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shangyingyoupin.top/Article/details/gtedpytkzx.html

Ruby: super
来源：http://dali.cheryme.top/Article/details/gtkkeohyxr.html

C#:   base.Greet();
来源：http://dali.aibaodan.cn/Article/details/gtneuukpbc.html

[G08] 静态方法与属性
来源：http://dali.nanxuanxn.top/Article/details/gtqvlkwnvr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pycfn.com/Article/details/gtlcskpssw.html

PHP:  public static function f() {}
来源：http://dali.nanxuanxn.top/Article/details/gtibommkrs.html

JS:   static f() {}
来源：http://dali.jiagoushi.top/Article/details/gtovedkehk.html

TS:   static f(): void {}
来源：http://dali.jlsjyb.cn/Article/details/gtnibnypux.html

Java: static void f() {}
来源：http://dali.316326.xyz/Article/details/gtyuvypurn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenlongwang.top/Article/details/gthuhtirrk.html

Ruby: def self.f; end
来源：http://dali.316326.xyz/Article/details/gtlizdzvav.html

C#:   public static void F() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtfzdplzaz.html

[G09] 接口 / 抽象类
来源：http://dali.jianghu66.top/Article/details/gtokahjlxp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xziqi.cn/Article/details/gtcfuxtrsd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yvedp.cn/Article/details/gtuvycldkb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daria6918.cn/Article/details/gthnbrjaet.html

TS:   interface Shape { area(): number; }
来源：http://dali.hysaishi.cn/Article/details/gtpwnxagkg.html

Java: interface Shape { double area(); }
来源：http://dali.andypj.xyz/Article/details/gtvkdzcghu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenjidiqi.icu/Article/details/gtkftsnybk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnxiangtu.top/Article/details/gtfmlitlak.html

C#:   interface IShape { double Area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtacsgrmcp.html

[G10] 访问控制
来源：http://dali.shzxlz.cn/Article/details/gtkhzktdjp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gogol.net.cn/Article/details/gtfqcdmeor.html

PHP:  public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtpxrgxtqv.html

JS:   #private 字段；其余公开
来源：http://dali.jlsjyb.cn/Article/details/gtibdqzhbo.html

TS:   public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtzjyzudqe.html

Java: public / protected / private / 默认包级
来源：http://dali.cqqwz.cn/Article/details/gtlfxulkne.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigufen.top/Article/details/gtmmcgwudq.html

Ruby: public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtatbdnyxk.html

C#:   public / protected / private / internal
来源：http://dali.dashuyun.cn/Article/details/gtvogjesyv.html

[G11] getter / setter
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlzuzdaxz.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258.top/Article/details/gtcsanpdjm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtulcuuxbd.html

JS:   get name() { return this._name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtshvzhtlm.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gtvgbgmqar.html

Java: public String getName() { return name; }
来源：http://dali.birdmap.top/Article/details/gtflkidjmn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthgohgyu.html

Ruby: attr_accessor :name
来源：http://dali.andypj.xyz/Article/details/gtlzlltxyz.html

C#:   public string Name { get; set; }
来源：http://dali.jlsjyb.cn/Article/details/gtfahyutwq.html

[G12] 对象转字符串
来源：http://dali.mhx1999.top/Article/details/gtuahgupen.html

Py:   def __str__(self): return self.name
来源：http://dali.ywan-chungtsiang.top/Article/details/gthuoququa.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtqnmitooq.html

JS:   toString() { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtgnmcpgzf.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtsglvqiag.html

Java: @Override public String toString() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtyaicquct.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gtmxtlkxhd.html

Ruby: def to_s; @name; end
来源：http://dali.sysykeji.top/Article/details/gtlxhtchpf.html

C#:   public override string ToString() => Name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvkuanlev.html

[G13] 判断对象类型
来源：http://dali.haohaochexian.top/Article/details/gtqggqhuoo.html

Py:   isinstance(u, User)
来源：http://dali.sufxvd.cn/Article/details/gtnfdrltic.html

PHP:  $u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtdujhysqn.html

JS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gttgopddxk.html

TS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtvaoncitk.html

Java: u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtkegmbbjx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gttqrrpopi.html

Ruby: u.is_a?(User)
来源：http://dali.ydzc1.top/Article/details/gtkswqwjdf.html

C#:   u is User
来源：http://dali.hongshengwenyu.top/Article/details/gtlhbvsywi.html

[G14] 数据类 / record
来源：http://dali.wangdashe.top/Article/details/gthryoxbcc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxinkj.top/Article/details/gtyuhumymw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.fzhhl.top/Article/details/gtyxgrjshm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinghuilouyu.cn/Article/details/gtvlxexvjc.html

TS:   type User = { name: string; age: number };
来源：http://dali.nanxinkj.top/Article/details/gtwbkxdvzd.html

Java: record User(String name, int age) {}
来源：http://dali.sxryk.cn/Article/details/gtoqjcyzqa.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hammf.cn/Article/details/gtvenfokdh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tian-w.cn/Article/details/gtwomsoebm.html

C#:   record User(string Name, int Age);
来源：http://dali.daxiang520.top/Article/details/gtjsamywvq.html

[G15] 枚举
来源：http://dali.cheryme.top/Article/details/gtgwejjouw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlixyyuqn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xziqi.cn/Article/details/gtixvmswaa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zycfv.cn/Article/details/gthnxstnjl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gtujlhuvev.html

Java: enum Color { RED, GREEN }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgcuzuene.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hfpthk.cn/Article/details/gtccsljeul.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gaohongyu789.top/Article/details/gtpqzksxlc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnirhoaxk.html

[G16] 对象转数组 / 字典
来源：http://dali.tanke756.top/Article/details/gtcedihzhg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.vqdsnc.cn/Article/details/gtdpvistkf.html

PHP:  get_object_vars($obj);
来源：http://dali.tanke756.top/Article/details/gthghmgbmj.html

JS:   Object.entries(obj)
来源：http://dali.jinqigufen.top/Article/details/gtlsprvpmr.html

TS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtgqstiemj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fzhhl.top/Article/details/gtlqntzyfq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqxenmpf.html

Ruby: obj.instance_variables
来源：http://dali.yonumen.top/Article/details/gtezacsrlx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gthzfqleny.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtltifnamo.html

H. 异常与错误处理
来源：http://dali.hnxiangtu.top/Article/details/gthnlwzjwo.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtqdemjepz.html

[H01] try / catch 基础
来源：http://dali.jlsjyb.cn/Article/details/gtntnxjzea.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sxryk.cn/Article/details/gtvuptcgcn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cdnleiting.top/Article/details/gtmgmmykmq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtqjpyrlhy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gtmtbwnjzx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.feifeiyinyue.top/Article/details/gtrkujtdqm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hywenlv.cn/Article/details/gtmawatekx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqezlfsc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.bjfxy.top/Article/details/gtftyxrgii.html

[H02] finally / ensure 收尾
来源：http://dali.vqdsnc.cn/Article/details/gtlggkqaoy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.redwolf501.top/Article/details/gtirldiukt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtqbwcyubx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtjekwfhuz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtfmlanxtu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtkexwfkfl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigfzy.top/Article/details/gtypgwdbsh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangshuangyany.cn/Article/details/gtzlhxfrka.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtyeazyqws.html

[H03] 主动抛出异常
来源：http://dali.havefunace.top/Article/details/gtgpyyhqii.html

Py:   raise ValueError("错误信息")
来源：http://dali.9152youxi.cn/Article/details/gtkdvnnhpg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtgqyybunt.html

JS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtksyynsbk.html

TS:   throw new Error("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwhhicmw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtoarjoqqd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.svipenyu.cn/Article/details/gtpajdtxkr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nanxuanxn.top/Article/details/gtcsunhmqf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gthdnppayv.html

[H04] 自定义异常类型
来源：http://dali.zycfv.cn/Article/details/gtcxtrqthv.html

Py:   class MyError(Exception): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowpaqamo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gtumvnzznl.html

JS:   class MyError extends Error {}
来源：http://dali.fzhhl.top/Article/details/gtsfcyjgvf.html

TS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gtmfqmopxy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gtgqqbbftj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangshuangyany.cn/Article/details/gtvpuybcns.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbvcrypv.html

C#:   class MyException : Exception {}
来源：http://dali.sweek.top/Article/details/gtdhsgreaf.html

[H05] 捕获特定类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqpenaug.html

Py:   except ValueError as e:
来源：http://dali.haohaochexian.top/Article/details/gtwsxmalem.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ivvv.top/Article/details/gteglnmsfv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gtnoiesoei.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gthbbngtkn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj20258.top/Article/details/gtpqffonff.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yanxiufei.cn/Article/details/gtdlnkdsge.html

Ruby: rescue ArgumentError => e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteklztokg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtkreefcws.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cucudq.cn/Article/details/gtirbtotww.html

Py:   value = d.get("k") or default
来源：http://dali.tanke756.top/Article/details/gtnpjspkwa.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hongshengwenyu.top/Article/details/gtywumrmqo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gtraahcver.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gttuxplctl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daxiang520.top/Article/details/gtjpvdawpl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hongshengwenyu.top/Article/details/gtwisnvdzm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuanzhike.top/Article/details/gtpeckpwkw.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj20258888.top/Article/details/gthpcctgpb.html

[H07] 断言
来源：http://dali.nwbrower.top/Article/details/gtjgmersnl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gotoacloud.top/Article/details/gtwavkztca.html

PHP:  assert($x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtfvftzdge.html

JS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtcucfeidn.html

TS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtvrvhrrzs.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ivvv.top/Article/details/gtexiajnkp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xinyue.icu/Article/details/gtlrxdsqcc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yongpay.top/Article/details/gtuyrosqdv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gtcahefgex.html

[H08] 获取错误信息与堆栈
来源：http://dali.hfpthk.cn/Article/details/gtmfvmxfff.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yonumen.top/Article/details/gtmqsqdlfz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hnxiangtu.top/Article/details/gtvafbxyke.html

JS:   e.message;  e.stack
来源：http://dali.wangdashe.top/Article/details/gtqfostvtd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258.top/Article/details/gtgmupviex.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.bjfxy.top/Article/details/gtmwrqxvab.html

Go:   err.Error()
来源：http://dali.nanxuanxn.top/Article/details/gtqsyfeslm.html

Ruby: e.message;  e.backtrace
来源：http://dali.yongpay.top/Article/details/gtgxzvbmae.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fzhhl.top/Article/details/gtizkoqrls.html

[H09] 带错误码的异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjincghf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinghuilouyu.cn/Article/details/gtnossllpc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.316326.xyz/Article/details/gtemtstall.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hammf.cn/Article/details/gtmnfvatva.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tian-w.cn/Article/details/gtbrjoxfxx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhixingplan.top/Article/details/gtaaeljhtc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.feifeiyinyue.top/Article/details/gtpwrjftkr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtympmuovv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.birdmap.top/Article/details/gtlxzjadgq.html

[H10] 资源自动释放
来源：http://dali.wangdashe.top/Article/details/gtyvxhehab.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuetiantiany.cn/Article/details/gtmhodsssh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nanxinkj.top/Article/details/gtzaapwfme.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jiagoushi.top/Article/details/gtmazchuje.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sxryk.cn/Article/details/gtgeizeqfn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhongyouzk.top/Article/details/gtzpankgwb.html

Go:   defer f.Close()
来源：http://dali.birdmap.top/Article/details/gtknpvsflr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zycfv.cn/Article/details/gtubmnnuyj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tanke756.top/Article/details/gtlimanxmm.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtptiaprqg.html

I. 正则表达式
来源：http://dali.tianlin.xyz/Article/details/gtrcdpqmmg.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtlnoxppte.html

[I01] 判断是否匹配
来源：http://dali.yuxming.cn/Article/details/gtgchghwrz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinqigufen.top/Article/details/gtirecomzx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aizwys.cn/Article/details/gtkpmptvcw.html

JS:   /\d+/.test(s)
来源：http://dali.cqqwz.cn/Article/details/gtanrcrskh.html

TS:   /\d+/.test(s)
来源：http://dali.gogol.net.cn/Article/details/gtuhypldaq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.smart0.xyz/Article/details/gtulslinwk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jianghu66.top/Article/details/gtxbbfjmom.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhoulong.xyz/Article/details/gtfnevggjx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhengqikj.top/Article/details/gtmqvdspup.html

[I02] 提取所有匹配
来源：http://dali.gzhubu.top/Article/details/gtsqmmaeth.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gtoignsrsz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sxryk.cn/Article/details/gtoeuhqlow.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xinyue.icu/Article/details/gtfqvsrrnm.html


<!-- 参考信息 -->