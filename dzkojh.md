代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jqgfzy.top/Article/details/gtnthafkuv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sufxvd.cn/Article/details/gtpshryjta.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xylfe.cn/Article/details/gtawtouzyc.html

[F08] 遍历目录
来源：http://dali.ivvv.top/Article/details/gtyxngrcxx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shuidangran.top/Article/details/gtqduuffdu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yuxming.cn/Article/details/gtwpskkpjv.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gtnesflfke.html

TS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gtlnkhfble.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gtiodjuvgs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yvedp.cn/Article/details/gtphgyiqxo.html

Ruby: Dir.children("dir")
来源：http://dali.meibo888.top/Article/details/gtbyxfwkin.html

C#:   Directory.GetFiles("dir")
来源：http://dali.birdmap.top/Article/details/gtwbzejdmi.html

[F09] 获取文件大小
来源：http://dali.cashguo.top/Article/details/gtvzplrxyj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tanke756.top/Article/details/gtoqjjfurk.html

PHP:  filesize("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtwgvlukgu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gtukpemzle.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxuanxn.top/Article/details/gtexbfhlqe.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtbwlvbvvj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xziqi.cn/Article/details/gtlovkfxfr.html

Ruby: File.size("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtefzugscz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jianghu66.top/Article/details/gtmgvidbyx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yvedp.cn/Article/details/gtzknpyhin.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gthstbnbov.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cucudq.cn/Article/details/gtozuornae.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtwedkrknl.html

TS:   path.extname("a.txt")
来源：http://dali.meibo888.top/Article/details/gtalhvtfnq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yongpay.top/Article/details/gtboajipch.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtrllkryzi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtlzucmlkv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtncernczv.html

[F11] 复制与移动文件
来源：http://dali.sufxvd.cn/Article/details/gtbpsqydjj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvtyhqrmw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.0kj1m.cn/Article/details/gtnrnqkkta.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtabpupric.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtfjjdynwx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tianlin.xyz/Article/details/gthtyygwab.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jqgfzy.top/Article/details/gtsdsdyioi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtkyakrpej.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hongshengwenyu.top/Article/details/gthnqeaext.html

[F12] CSV 读写
来源：http://dali.jlsjyb.cn/Article/details/gtndieokmv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.redwolf501.top/Article/details/gtyxnzccoj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zycfv.cn/Article/details/gttvkuocxj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gzhubu.top/Article/details/gtwqzlbovq.html

TS:   // 同上
来源：http://dali.chenjidiqi.icu/Article/details/gtobtpmenj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.pengpengdd.cyou/Article/details/gtsdtjbqhl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xinyue.icu/Article/details/gtvlovszmq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.c1oappe.top/Article/details/gtcnbtwdiy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gogol.net.cn/Article/details/gtuudvovvm.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtejnkgalx.html

G. 面向对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaisuzluz.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gttronuopi.html

[G01] 定义类
来源：http://dali.jqgfzy.top/Article/details/gtlxmibgds.html

Py:   class User: pass
来源：http://dali.smart0.xyz/Article/details/gtnyugnfuy.html

PHP:  class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtacrzqlfm.html

JS:   class User {}
来源：http://dali.yonumen.top/Article/details/gtwnlxirvt.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258.top/Article/details/gtqeiiijwm.html

Java: class User {}
来源：http://dali.xinyue.icu/Article/details/gtfmturfqu.html

Go:   type User struct { Name string }
来源：http://dali.cucudq.cn/Article/details/gtbfnzmyux.html

Ruby: class User; end
来源：http://dali.xinyue.icu/Article/details/gtymygkdne.html

C#:   class User {}
来源：http://dali.sweek.top/Article/details/gtreuckgis.html

[G02] 构造函数
来源：http://dali.zhixingplan.top/Article/details/gtzgiecmom.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cdnleiting.top/Article/details/gtjkcfhrta.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dianchejie.cn/Article/details/gtcdegltpw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gtmitznbuj.html

TS:   constructor(public name: string) {}
来源：http://dali.zycfv.cn/Article/details/gtdryauvay.html

Java: User(String name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtjvbveskw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ybcxt.top/Article/details/gtstbudvkz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ppjwa.cn/Article/details/gtlndubobg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.birdmap.top/Article/details/gtgcgnxggk.html

[G03] 实例属性
来源：http://dali.guowangkeji.top/Article/details/gtjpuexdql.html

Py:   self.name = "x"
来源：http://dali.c1oappe.top/Article/details/gtngnvwthg.html

PHP:  public string $name = "x";
来源：http://dali.cashguo.top/Article/details/gtcpboupdp.html

JS:   this.name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtmcshnlwg.html

TS:   name: string = "x";
来源：http://dali.yj20258888.top/Article/details/gtauewamjf.html

Java: private String name;
来源：http://dali.cashguo.top/Article/details/gtscvbzlwa.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gaohongyu789.top/Article/details/gtcilwnjyu.html

Ruby: @name = "x"
来源：http://dali.redwolf501.top/Article/details/gtppvtswid.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ppjwa.cn/Article/details/gtljhxzcns.html

[G04] 定义方法
来源：http://dali.yj20258888.top/Article/details/gthjdnhdgn.html

Py:   def greet(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gtdmjoplrr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtqumfzomu.html

JS:   greet() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtsrveljbc.html

TS:   greet(): string { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtuklvmrad.html

Java: String greet() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtjkzpxgak.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtteoegiju.html

Ruby: def greet; @name; end
来源：http://dali.yongpay.top/Article/details/gtjotnjxyb.html

C#:   public string Greet() => Name;
来源：http://dali.birdmap.top/Article/details/gtrkqcaeiz.html

[G05] 继承
来源：http://dali.sysykeji.top/Article/details/gtdjmnmkvx.html

Py:   class Admin(User): pass
来源：http://dali.hammf.cn/Article/details/gtqyyumagn.html

PHP:  class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmmedxnce.html

JS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gteaanoveh.html

TS:   class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gttavfywrn.html

Java: class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtftuhhmyn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.vqdsnc.cn/Article/details/gtljivkxar.html

Ruby: class Admin < User; end
来源：http://dali.yj20258.top/Article/details/gtgeypeybr.html

C#:   class Admin : User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtixbrehbw.html

[G06] 重写方法
来源：http://dali.feifeiyinyue.top/Article/details/gthmqfhmav.html

Py:   def greet(self): return "admin"
来源：http://dali.zdqjudy.top/Article/details/gtwrspvjok.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtsnxhfazl.html

JS:   greet() { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gtcedhnbgm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtlkedtyrw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvwtnlwbj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yanxiufei.cn/Article/details/gtesnnemqg.html

Ruby: def greet; "admin"; end
来源：http://dali.ydzc1.top/Article/details/gtvtoktxhj.html

C#:   public override string Greet() => "admin";
来源：http://dali.redwolf501.top/Article/details/gtbpxppjro.html

[G07] 调用父类方法
来源：http://dali.sweek.top/Article/details/gtuufkzvlq.html

Py:   super().greet()
来源：http://dali.tanke756.top/Article/details/gttomhgfzo.html

PHP:  parent::greet();
来源：http://dali.zhongyouzk.top/Article/details/gtqarcqrkm.html

JS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtdawfiyjd.html

TS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtqjvxaykt.html

Java: super.greet();
来源：http://dali.shuidangran.top/Article/details/gterproboo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gthmdjzfew.html

Ruby: super
来源：http://dali.fengsongda.top/Article/details/gtzngyhltl.html

C#:   base.Greet();
来源：http://dali.yuanzhike.top/Article/details/gtambbnsed.html

[G08] 静态方法与属性
来源：http://dali.dianchejie.cn/Article/details/gtaerbsfeh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cucudq.cn/Article/details/gtarwbnqmx.html

PHP:  public static function f() {}
来源：http://dali.guannengcc.top/Article/details/gtdhcicucc.html

JS:   static f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtymtpkzmt.html

TS:   static f(): void {}
来源：http://dali.pycfn.com/Article/details/gtwhnglqog.html

Java: static void f() {}
来源：http://dali.wangdashe.top/Article/details/gtwjbafhfi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.mhx1999.top/Article/details/gtimacdmcu.html

Ruby: def self.f; end
来源：http://dali.ivvv.top/Article/details/gtripjxzrt.html

C#:   public static void F() {}
来源：http://dali.yanxiufei.cn/Article/details/gtnzniqono.html

[G09] 接口 / 抽象类
来源：http://dali.zhixingplan.top/Article/details/gtvehertyo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hammf.cn/Article/details/gtvqqjxwgw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aibaodan.cn/Article/details/gthsqmximg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.kuanghao11.cn/Article/details/gtkyrfcbtx.html

TS:   interface Shape { area(): number; }
来源：http://dali.yanxiufei.cn/Article/details/gtqtorlwsk.html

Java: interface Shape { double area(); }
来源：http://dali.hnxiangtu.top/Article/details/gtdmylyxkw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.aizwys.cn/Article/details/gtvcjylhyc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shangyingyoupin.top/Article/details/gtmhsflkni.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtodjlchxl.html

[G10] 访问控制
来源：http://dali.andypj.xyz/Article/details/gtxdlwudvb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yanxiufei.cn/Article/details/gtbilxfbre.html

PHP:  public / protected / private
来源：http://dali.yongpay.top/Article/details/gtiaxlxsxa.html

JS:   #private 字段；其余公开
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnlpxjbcw.html

TS:   public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtumisuuox.html

Java: public / protected / private / 默认包级
来源：http://dali.bjfxy.top/Article/details/gtufvjyfrv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sxryk.cn/Article/details/gtwwoldcvn.html

Ruby: public / protected / private
来源：http://dali.bjfxy.top/Article/details/gtiljymuye.html

C#:   public / protected / private / internal
来源：http://dali.hongshengwenyu.top/Article/details/gteoxluhvc.html

[G11] getter / setter
来源：http://dali.kuanghao11.cn/Article/details/gtixgwwykd.html

Py:   @property 与 @x.setter
来源：http://dali.jqgufenzy.top/Article/details/gtbaigjuxy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gtfvpowtxo.html

JS:   get name() { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gtwzevhdfs.html

TS:   get name(): string { return this._name; }
来源：http://dali.ivvv.top/Article/details/gthvqdnvdc.html

Java: public String getName() { return name; }
来源：http://dali.pycfn.com/Article/details/gtqbfirdnw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gtppszfokb.html

Ruby: attr_accessor :name
来源：http://dali.yj20258.top/Article/details/gtwmzvstog.html

C#:   public string Name { get; set; }
来源：http://dali.yvedp.cn/Article/details/gtwlmkpiyp.html

[G12] 对象转字符串
来源：http://dali.sysykeji.top/Article/details/gtiircpjkf.html

Py:   def __str__(self): return self.name
来源：http://dali.meibo888.top/Article/details/gtjghdgunb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtdahvaluj.html

JS:   toString() { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtkobzijab.html

TS:   toString(): string { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtctrtdtmh.html

Java: @Override public String toString() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtrprbcdlb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gtvvngwcks.html

Ruby: def to_s; @name; end
来源：http://dali.zhengqikj.top/Article/details/gtqngiyxft.html

C#:   public override string ToString() => Name;
来源：http://dali.jinghuilouyu.cn/Article/details/gthxigaedm.html

[G13] 判断对象类型
来源：http://dali.c1oappe.top/Article/details/gtgrfvtmnc.html

Py:   isinstance(u, User)
来源：http://dali.wangdashe.top/Article/details/gthsfzykux.html

PHP:  $u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtxtrhknua.html

JS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtkbpqfung.html

TS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtswerowbw.html

Java: u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtgpickynl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zycfv.cn/Article/details/gtpfozflul.html

Ruby: u.is_a?(User)
来源：http://dali.yonumen.top/Article/details/gthmtsruvv.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gtnigagvaf.html

[G14] 数据类 / record
来源：http://dali.wangshuangyany.cn/Article/details/gttjlxanhk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.316326.xyz/Article/details/gtyrolmfkx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cashguo.top/Article/details/gtszxwjivg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jiagoushi.top/Article/details/gtvmmekjhr.html

TS:   type User = { name: string; age: number };
来源：http://dali.nwbrower.top/Article/details/gtzgkromuo.html

Java: record User(String name, int age) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtzueyxamf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xylfe.cn/Article/details/gtfakomvda.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sweek.top/Article/details/gtygydutoi.html

C#:   record User(string Name, int Age);
来源：http://dali.yonumen.top/Article/details/gtelknngwm.html

[G15] 枚举
来源：http://dali.gzhubu.top/Article/details/gttaebvwhc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cheryme.top/Article/details/gtxeedfgxz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.smart0.xyz/Article/details/gtgztshwka.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yongpay.top/Article/details/gtzqfpudyv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtbfdkdezw.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigufen.top/Article/details/gtedjmiezc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tian-w.cn/Article/details/gtgyouesru.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenjidiqi.icu/Article/details/gtyhoszjqb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gtvzzzaali.html

[G16] 对象转数组 / 字典
来源：http://dali.dashuyun.cn/Article/details/gtawyhpwxl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258.top/Article/details/gtocqfsmgh.html

PHP:  get_object_vars($obj);
来源：http://dali.jiagoushi.top/Article/details/gttzfalmdz.html

JS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gtyghydfrc.html

TS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gtzlrngrev.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenlongwang.top/Article/details/gtnkklovyz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sysykeji.top/Article/details/gtwfeebzei.html

Ruby: obj.instance_variables
来源：http://dali.feifeiyinyue.top/Article/details/gtwuoydabk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gthyvmjjjn.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gttygxcazw.html

H. 异常与错误处理
来源：http://dali.jyoumei.cn/Article/details/gtpdmpibfw.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtbaszufzf.html

[H01] try / catch 基础
来源：http://dali.chenjidiqi.icu/Article/details/gtsgpyknte.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cdnleiting.top/Article/details/gtmidgjztq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtoahajkct.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gtxmcnsotk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daria6918.cn/Article/details/gtkrimnenz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gtwoivwshr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangshuangyany.cn/Article/details/gtmqpwlbgg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhongyouzk.top/Article/details/gtlzlcweam.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aizwys.cn/Article/details/gtmevexslc.html

[H02] finally / ensure 收尾
来源：http://dali.jyoumei.cn/Article/details/gtoatlvdei.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zdqjudy.top/Article/details/gtgiifvqrh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtmbpeaugw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gthkewolcj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtogjlpduo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtonulvtum.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hongshengwenyu.top/Article/details/gtvffjqcqv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cucudq.cn/Article/details/gtremurail.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtfhpvddpj.html

[H03] 主动抛出异常
来源：http://dali.guannengcc.top/Article/details/gtevhqgpnu.html

Py:   raise ValueError("错误信息")
来源：http://dali.316326.xyz/Article/details/gtkpnqztte.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtcaemkzlc.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtfhyjccov.html

TS:   throw new Error("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtzgiaoeex.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtbcwyyxhe.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jiagoushi.top/Article/details/gtqytjapsv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tian-w.cn/Article/details/gtalipojir.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtmwucprib.html

[H04] 自定义异常类型
来源：http://dali.guowangkeji.top/Article/details/gtrjawzaal.html

Py:   class MyError(Exception): pass
来源：http://dali.hfpthk.cn/Article/details/gthdltrrad.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gtmfbqtquk.html

JS:   class MyError extends Error {}
来源：http://dali.vqdsnc.cn/Article/details/gtqnxaynus.html

TS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtprvfag.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gtdodneijk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yonumen.top/Article/details/gtdmrxhacp.html

Ruby: class MyError < StandardError; end
来源：http://dali.dashuyun.cn/Article/details/gtbdeblvkk.html

C#:   class MyException : Exception {}
来源：http://dali.chenzaomai.com/Article/details/gtofljpuqs.html

[H05] 捕获特定类型
来源：http://dali.shangyingyoupin.top/Article/details/gtynzyitmi.html

Py:   except ValueError as e:
来源：http://dali.snrcjt.cn/Article/details/gtkndrxlbi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aibaodan.cn/Article/details/gthxrerrfx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgfzy.top/Article/details/gtyoehylwn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gtziunnxuh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ppjwa.cn/Article/details/gtawevvcty.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sysykeji.top/Article/details/gtdwukdslu.html

Ruby: rescue ArgumentError => e
来源：http://dali.feifeiyinyue.top/Article/details/gtdxazxajv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shzxlz.cn/Article/details/gtzradjrly.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fzhhl.top/Article/details/gthfnfgzql.html

Py:   value = d.get("k") or default
来源：http://dali.c1oappe.top/Article/details/gtshdjcfot.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jyoumei.cn/Article/details/gtodttplrc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gtdwhwlxen.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gttmtzsdks.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinghuilouyu.cn/Article/details/gtautgmcxc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj20258888.top/Article/details/gtonvakpxv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.haohaochexian.top/Article/details/gtfapqrqmz.html

C#:   obj?.A?.B ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtslonrjdo.html

[H07] 断言
来源：http://dali.hysaishi.cn/Article/details/gtrmhsvtxx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinghuilouyu.cn/Article/details/gttgbkdbxg.html

PHP:  assert($x > 0);
来源：http://dali.redwolf501.top/Article/details/gtdrrkpiib.html

JS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtujortequ.html

TS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtmyncyhhx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xinyue.icu/Article/details/gthmkhztah.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pengpengdd.cyou/Article/details/gtembubyqk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tian-w.cn/Article/details/gtnnrupgdw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtulnqrmyd.html

[H08] 获取错误信息与堆栈
来源：http://dali.mhx1999.top/Article/details/gtopfwoqot.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.andypj.xyz/Article/details/gtjhtvpsyn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gzhubu.top/Article/details/gtxehcknww.html

JS:   e.message;  e.stack
来源：http://dali.jinqigfzy.top/Article/details/gtrmpkvskz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.wangdashe.top/Article/details/gtrvlwbzmx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gotoacloud.top/Article/details/gtctrwkedx.html

Go:   err.Error()
来源：http://dali.fzhhl.top/Article/details/gtrbvcgzfk.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenlongwang.top/Article/details/gtxnpoehzr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gotoacloud.top/Article/details/gtdvqgdour.html

[H09] 带错误码的异常
来源：http://dali.jqgfzy.top/Article/details/gtamwzsmdx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sweek.top/Article/details/gtfbzddasd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yangfankeji.com/Article/details/gtgdmjsryt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.iojbl.cn/Article/details/gtbwxofqxg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jianghu66.top/Article/details/gtvbouinwq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.iojbl.cn/Article/details/gtbrxyomgc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.dianchejie.cn/Article/details/gtkinjlbui.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigfzy.top/Article/details/gtstkwugzr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yueranfly.top/Article/details/gtkxrphqug.html

[H10] 资源自动释放
来源：http://dali.jyoumei.cn/Article/details/gtxprwwiej.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sysykeji.top/Article/details/gtgpmxmkjm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.dashuyun.cn/Article/details/gteaqmfnmw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gtfksymyet.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gtfsjwoxxh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shanyushiyangtech.top/Article/details/gtkxakbikz.html

Go:   defer f.Close()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrcdiytpo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.c1oappe.top/Article/details/gtkmwzkyzx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtrjmmwfbz.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtfvjiauoy.html

I. 正则表达式
来源：http://dali.guannengcc.top/Article/details/gtttfemiwa.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtjiahitiz.html

[I01] 判断是否匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtkoafegns.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jqgfzy.top/Article/details/gtyltllmhb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtxqobimtv.html

JS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gtbcshrytw.html

TS:   /\d+/.test(s)
来源：http://dali.cdnleiting.top/Article/details/gtqswhhwnb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgufenzy.top/Article/details/gtibuweekn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258888.top/Article/details/gtoolzroub.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenlongwang.top/Article/details/gtmkrirtnp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuanzhike.top/Article/details/gtnspmeafj.html


<!-- 参考信息 -->