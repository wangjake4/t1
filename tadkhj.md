代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhiwuduotai.top/Article/details/gttzzrctwb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.mhx1999.top/Article/details/gtciepauwj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhengqikj.top/Article/details/gttwffjqoz.html

[F08] 遍历目录
来源：http://dali.zhengqikj.top/Article/details/gtcdipkihl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guannengcc.top/Article/details/gtducymeki.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yueranfly.top/Article/details/gtaubvsihe.html

JS:   fs.readdirSync("dir")
来源：http://dali.316326.xyz/Article/details/gtxzuuzqjw.html

TS:   fs.readdirSync("dir")
来源：http://dali.snrcjt.cn/Article/details/gthnbnijug.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangdashe.top/Article/details/gtchzqhzko.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenlongwang.top/Article/details/gtvqoawffx.html

Ruby: Dir.children("dir")
来源：http://dali.0kj1m.cn/Article/details/gtfwzafqeo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aibaodan.cn/Article/details/gtgwfdemeg.html

[F09] 获取文件大小
来源：http://dali.pengpengdd.cyou/Article/details/gtdqrpqozi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtytwdltrv.html

PHP:  filesize("a.txt");
来源：http://dali.yj20258.top/Article/details/gtgzutncaq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawsjzkxi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gtuchennzi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtqhhggbmp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tanke756.top/Article/details/gtnbltgpmu.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gteafvgijl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhongyouzk.top/Article/details/gtjbqprinp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gogol.net.cn/Article/details/gtaxanfltl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtpxaeofpv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tian-w.cn/Article/details/gtndbrglkn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtirrnvdzg.html

TS:   path.extname("a.txt")
来源：http://dali.yonumen.top/Article/details/gtlnleafuu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.kuanghao11.cn/Article/details/gtejwanejd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtvlkhyneo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtoivctpgv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtiokrbbwb.html

[F11] 复制与移动文件
来源：http://dali.yuxming.cn/Article/details/gtykqulznp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtxhldmijm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yonumen.top/Article/details/gtyqbbwpns.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtrdskagll.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtpnyftmqg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gtsrswwcfo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fzhhl.top/Article/details/gtbubulwzo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gtaydmfgvp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jlsjyb.cn/Article/details/gtfkdukeac.html

[F12] CSV 读写
来源：http://dali.hammf.cn/Article/details/gtfcjqwyqi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ydzc1.top/Article/details/gtkslviali.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yonumen.top/Article/details/gtfetaawpd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hongshengwenyu.top/Article/details/gtsqlxsgjm.html

TS:   // 同上
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxjwyhekh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.kuanghao11.cn/Article/details/gtvrgftqmp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhoulong.xyz/Article/details/gtglpdicil.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj202588.top/Article/details/gtgewlxyvd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.9152youxi.cn/Article/details/gtzojmrgsn.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtzubyqyaa.html

G. 面向对象
来源：http://dali.jqgufenzy.top/Article/details/gtondsnypi.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtrtjbcfno.html

[G01] 定义类
来源：http://dali.meibo888.top/Article/details/gtcrlvyetk.html

Py:   class User: pass
来源：http://dali.kuanghao11.cn/Article/details/gtjobwkykx.html

PHP:  class User {}
来源：http://dali.aibaodan.cn/Article/details/gtxxymtsaj.html

JS:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gtchyripra.html

TS:   class User { name: string = ""; }
来源：http://dali.wangdashe.top/Article/details/gtxxmegtft.html

Java: class User {}
来源：http://dali.birdmap.top/Article/details/gtgdooibaa.html

Go:   type User struct { Name string }
来源：http://dali.yj202588.top/Article/details/gtoilhixyp.html

Ruby: class User; end
来源：http://dali.meibo888.top/Article/details/gthdibcwna.html

C#:   class User {}
来源：http://dali.havefunace.top/Article/details/gtrtnxxreu.html

[G02] 构造函数
来源：http://dali.0kj1m.cn/Article/details/gthrjppjws.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhoulong.xyz/Article/details/gtgnpzlwdb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.9152youxi.cn/Article/details/gteucxfojt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258.top/Article/details/gtyologakw.html

TS:   constructor(public name: string) {}
来源：http://dali.nwbrower.top/Article/details/gtkspkzvtd.html

Java: User(String name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gtkmeatvzk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zdqjudy.top/Article/details/gtxrttkppg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.andypj.xyz/Article/details/gtlsuvaiul.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cucudq.cn/Article/details/gtxahoxcmh.html

[G03] 实例属性
来源：http://dali.dashuyun.cn/Article/details/gtfcblcqsr.html

Py:   self.name = "x"
来源：http://dali.shanyushiyangtech.top/Article/details/gtvipyltff.html

PHP:  public string $name = "x";
来源：http://dali.yvedp.cn/Article/details/gtaqdhvxpb.html

JS:   this.name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtidxvddpd.html

TS:   name: string = "x";
来源：http://dali.xylfe.cn/Article/details/gtpdwcejgw.html

Java: private String name;
来源：http://dali.wangdashe.top/Article/details/gtctuvxgwi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gotoacloud.top/Article/details/gttggbnuju.html

Ruby: @name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gtqvtpfnac.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.birdmap.top/Article/details/gtfnuqoswz.html

[G04] 定义方法
来源：http://dali.zhixingplan.top/Article/details/gtbmytmipb.html

Py:   def greet(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gtzvaqbxox.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gttmuyjfnr.html

JS:   greet() { return this.name; }
来源：http://dali.sweek.top/Article/details/gtyzwidugc.html

TS:   greet(): string { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtrazccsqk.html

Java: String greet() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtyfimiqti.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gtvejynrph.html

Ruby: def greet; @name; end
来源：http://dali.fengsongda.top/Article/details/gtbvbabdhk.html

C#:   public string Greet() => Name;
来源：http://dali.hysaishi.cn/Article/details/gtwzgwbqjz.html

[G05] 继承
来源：http://dali.zhengqikj.top/Article/details/gtlfuiwcju.html

Py:   class Admin(User): pass
来源：http://dali.haohaochexian.top/Article/details/gtxubafbbo.html

PHP:  class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtzaljmnod.html

JS:   class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gthpulsklg.html

TS:   class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtwvtshjzv.html

Java: class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtwqgdujmm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xinyue.icu/Article/details/gttjtorzjm.html

Ruby: class Admin < User; end
来源：http://dali.jlsjyb.cn/Article/details/gtfrzkhhwq.html

C#:   class Admin : User {}
来源：http://dali.cucudq.cn/Article/details/gtwmftscqf.html

[G06] 重写方法
来源：http://dali.tianlin.xyz/Article/details/gtiviptafv.html

Py:   def greet(self): return "admin"
来源：http://dali.316326.xyz/Article/details/gtsudxcsyn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gtofyrwwxs.html

JS:   greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtihxuaedx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtemazbvgx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtobguqpwl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangdashe.top/Article/details/gtucwvwzcc.html

Ruby: def greet; "admin"; end
来源：http://dali.nwbrower.top/Article/details/gtdfwcbvfc.html

C#:   public override string Greet() => "admin";
来源：http://dali.gzhubu.top/Article/details/gtbrmdvtbe.html

[G07] 调用父类方法
来源：http://dali.hnqzz.top/Article/details/gtfetyteov.html

Py:   super().greet()
来源：http://dali.guowangkeji.top/Article/details/gtamzqylrz.html

PHP:  parent::greet();
来源：http://dali.birdmap.top/Article/details/gtvmzrbwlb.html

JS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gtwgvqxoek.html

TS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gtxuwxmioe.html

Java: super.greet();
来源：http://dali.yj20258.top/Article/details/gtbzniyjro.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gogol.net.cn/Article/details/gtmphtzmgc.html

Ruby: super
来源：http://dali.aizwys.cn/Article/details/gtubugczyk.html

C#:   base.Greet();
来源：http://dali.hammf.cn/Article/details/gtrritgzyt.html

[G08] 静态方法与属性
来源：http://dali.hysaishi.cn/Article/details/gtivuoloxf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jlsjyb.cn/Article/details/gtmftfgpmg.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gtapkgqqiy.html

JS:   static f() {}
来源：http://dali.wangdashe.top/Article/details/gtszplxmwy.html

TS:   static f(): void {}
来源：http://dali.jlsjyb.cn/Article/details/gtadgvtoah.html

Java: static void f() {}
来源：http://dali.guannengcc.top/Article/details/gtkiaobpvq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sysykeji.top/Article/details/gtrimvamuk.html

Ruby: def self.f; end
来源：http://dali.sxryk.cn/Article/details/gtzrzjjlxo.html

C#:   public static void F() {}
来源：http://dali.wangdashe.top/Article/details/gtxmiirmto.html

[G09] 接口 / 抽象类
来源：http://dali.meibo888.top/Article/details/gtlmedbsny.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.iojbl.cn/Article/details/gtovdldjtd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gzhubu.top/Article/details/gthbnsteak.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xziqi.cn/Article/details/gtvzdatnfq.html

TS:   interface Shape { area(): number; }
来源：http://dali.cucudq.cn/Article/details/gtorycrlvg.html

Java: interface Shape { double area(); }
来源：http://dali.nanxinkj.top/Article/details/gtlmtensdz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jqgufenzy.top/Article/details/gtgksieqbp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqjvncxw.html

C#:   interface IShape { double Area(); }
来源：http://dali.xziqi.cn/Article/details/gtulklgdnk.html

[G10] 访问控制
来源：http://dali.zycfv.cn/Article/details/gtvfalqffo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nwbrower.top/Article/details/gtaemgckid.html

PHP:  public / protected / private
来源：http://dali.hnqzz.top/Article/details/gtdfumpqom.html

JS:   #private 字段；其余公开
来源：http://dali.xuanzx.com/Article/details/gtemwjtkoj.html

TS:   public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtjbvyuhso.html

Java: public / protected / private / 默认包级
来源：http://dali.nwbrower.top/Article/details/gtiyshblbp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuetiantiany.cn/Article/details/gthxduiosa.html

Ruby: public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxldmenb.html

C#:   public / protected / private / internal
来源：http://dali.mhx1999.top/Article/details/gtongdqiqf.html

[G11] getter / setter
来源：http://dali.c1oappe.top/Article/details/gtepnogdjk.html

Py:   @property 与 @x.setter
来源：http://dali.guannengcc.top/Article/details/gtmpxabecg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtqfpcnpbn.html

JS:   get name() { return this._name; }
来源：http://dali.dianchejie.cn/Article/details/gtyzawyjja.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxydstuyt.html

Java: public String getName() { return name; }
来源：http://dali.yueranfly.top/Article/details/gtvoehrkyi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gtoincbxjh.html

Ruby: attr_accessor :name
来源：http://dali.zhongyouzk.top/Article/details/gtlkdsjfjo.html

C#:   public string Name { get; set; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwouyfpc.html

[G12] 对象转字符串
来源：http://dali.haohaochexian.top/Article/details/gtrkyxmzzn.html

Py:   def __str__(self): return self.name
来源：http://dali.ybcxt.top/Article/details/gtidsyldqw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtllrjtdao.html

JS:   toString() { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtfauxcdmv.html

TS:   toString(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtvsypybbr.html

Java: @Override public String toString() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gttwjeznzh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtqlpfzito.html

Ruby: def to_s; @name; end
来源：http://dali.yonumen.top/Article/details/gtirxbvmpq.html

C#:   public override string ToString() => Name;
来源：http://dali.yj202588.top/Article/details/gtooichlxz.html

[G13] 判断对象类型
来源：http://dali.tianlin.xyz/Article/details/gtyxxiazyy.html

Py:   isinstance(u, User)
来源：http://dali.cucudq.cn/Article/details/gtsssbgbjm.html

PHP:  $u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtkqwxgpju.html

JS:   u instanceof User
来源：http://dali.cheryme.top/Article/details/gtojqjtdth.html

TS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtrdcvtbee.html

Java: u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtjywprxrk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.daxiang520.top/Article/details/gtieqbftgn.html

Ruby: u.is_a?(User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwoaqhepm.html

C#:   u is User
来源：http://dali.sysykeji.top/Article/details/gtfqifeasy.html

[G14] 数据类 / record
来源：http://dali.zycfv.cn/Article/details/gtgrriznwb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxuanxn.top/Article/details/gtjznzppmb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.feifeiyinyue.top/Article/details/gtgskovonx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ybcxt.top/Article/details/gtepflcnkj.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigfzy.top/Article/details/gtouwjarbg.html

Java: record User(String name, int age) {}
来源：http://dali.xuanzx.com/Article/details/gtqddhzvwy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gtczzqqrtp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guowangkeji.top/Article/details/gtwezihspa.html

C#:   record User(string Name, int Age);
来源：http://dali.fzhhl.top/Article/details/gtjamtifey.html

[G15] 枚举
来源：http://dali.dashuyun.cn/Article/details/gtpivezoxq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sxryk.cn/Article/details/gtcowvvjcb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cheryme.top/Article/details/gtgbcbwjut.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.9152youxi.cn/Article/details/gtspbumldc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuanzx.com/Article/details/gtuaazsbfy.html

Java: enum Color { RED, GREEN }
来源：http://dali.shangyingyoupin.top/Article/details/gtidozkwvi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ydzc1.top/Article/details/gtozkjooda.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangdashe.top/Article/details/gtmqzcvmzi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gtbnofjlzq.html

[G16] 对象转数组 / 字典
来源：http://dali.yuanzhike.top/Article/details/gtropowbpp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuxming.cn/Article/details/gtceiftwwb.html

PHP:  get_object_vars($obj);
来源：http://dali.zhongyouzk.top/Article/details/gtcsnywwrs.html

JS:   Object.entries(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtzfrukjrq.html

TS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gteedurzeg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daxiang520.top/Article/details/gtyefgaalm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yonumen.top/Article/details/gtvnrynurd.html

Ruby: obj.instance_variables
来源：http://dali.sxryk.cn/Article/details/gtkklkvikg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gtglglccsk.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtwsqplyiz.html

H. 异常与错误处理
来源：http://dali.chenlongwang.top/Article/details/gtddxaloiu.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtelibtdrs.html

[H01] try / catch 基础
来源：http://dali.sxryk.cn/Article/details/gtjsicpezb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.0kj1m.cn/Article/details/gtlqmuoqee.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jyoumei.cn/Article/details/gtpgtlxomm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gtgrjcllnq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gtqxlvyflb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yuxming.cn/Article/details/gtyfnswrdq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tianlin.xyz/Article/details/gtnwraupih.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.9152youxi.cn/Article/details/gtuprtmesl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnxiangtu.top/Article/details/gtrmvqgqex.html

[H02] finally / ensure 收尾
来源：http://dali.hnqzz.top/Article/details/gtsvqnmmvo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nanxuanxn.top/Article/details/gtksftdvje.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtpqdcnaet.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gthbiklgof.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtosobqjxn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtbksmcowv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yanxiufei.cn/Article/details/gtrvncjujh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sweek.top/Article/details/gtlglpreol.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtntpekslw.html

[H03] 主动抛出异常
来源：http://dali.chenzaomai.com/Article/details/gtlvimckuh.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenzaomai.com/Article/details/gtljqcytfr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtnzeivitx.html

JS:   throw new Error("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtvqjuksel.html

TS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gtrjiopxhs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtomdoqtco.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.feifeiyinyue.top/Article/details/gtynswqhto.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jqgufenzy.top/Article/details/gtcvhxpkql.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtzplopcmm.html

[H04] 自定义异常类型
来源：http://dali.daria6918.cn/Article/details/gtukjoqwlg.html

Py:   class MyError(Exception): pass
来源：http://dali.hammf.cn/Article/details/gtcrmkmnxd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gtqiwcyofb.html

JS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gtvbgkrwef.html

TS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gtjpeqefvr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gtngerpavn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xziqi.cn/Article/details/gtgrloeogz.html

Ruby: class MyError < StandardError; end
来源：http://dali.gzhubu.top/Article/details/gtdeavvjxn.html

C#:   class MyException : Exception {}
来源：http://dali.hongshengwenyu.top/Article/details/gtfijwicfn.html

[H05] 捕获特定类型
来源：http://dali.jianghu66.top/Article/details/gtemmveqsl.html

Py:   except ValueError as e:
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuunhqyed.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zycfv.cn/Article/details/gtfhfuaupd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gtecmeievv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gtianwluwa.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cucudq.cn/Article/details/gtqbrqljpw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hywenlv.cn/Article/details/gtmxizresw.html

Ruby: rescue ArgumentError => e
来源：http://dali.dashuyun.cn/Article/details/gtmgrsutmt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.quarkkingdee.top/Article/details/gtjbgtywrw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhaomingkeji.xyz/Article/details/gtumnvpgpf.html

Py:   value = d.get("k") or default
来源：http://dali.shuidangran.top/Article/details/gtbgbfgpoj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gtyrtmxyof.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hnqzz.top/Article/details/gtwoztmrfn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.9152youxi.cn/Article/details/gtwiwukfof.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.kuanghao11.cn/Article/details/gthiklkobq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sysykeji.top/Article/details/gttlwrdvbv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sufxvd.cn/Article/details/gtqesgyvmi.html

C#:   obj?.A?.B ?? default
来源：http://dali.shzxlz.cn/Article/details/gtvcbcvxip.html

[H07] 断言
来源：http://dali.yuanzhike.top/Article/details/gtsxpfumop.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zdqjudy.top/Article/details/gtpctejsbr.html

PHP:  assert($x > 0);
来源：http://dali.nwbrower.top/Article/details/gtcqmagsiy.html

JS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtkmxclepc.html

TS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gthsglrxdl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcrjxvztb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhoulong.xyz/Article/details/gtwykahtru.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.snrcjt.cn/Article/details/gtnbxxcaim.html

C#:   Debug.Assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtmufedhcr.html

[H08] 获取错误信息与堆栈
来源：http://dali.hysaishi.cn/Article/details/gtlminzdej.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hnqzz.top/Article/details/gthrdehysa.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tanke756.top/Article/details/gtrqtuaktw.html

JS:   e.message;  e.stack
来源：http://dali.0kj1m.cn/Article/details/gtiwdybgpj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenlongwang.top/Article/details/gtrvftbbgg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sysykeji.top/Article/details/gttcnxqkch.html

Go:   err.Error()
来源：http://dali.wangshuangyany.cn/Article/details/gtwrswghvx.html

Ruby: e.message;  e.backtrace
来源：http://dali.jlsjyb.cn/Article/details/gtpswqlcyg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shuidangran.top/Article/details/gtcumublrz.html

[H09] 带错误码的异常
来源：http://dali.nanxinkj.top/Article/details/gtvewdiyks.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhongyouzk.top/Article/details/gtxtydqrun.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pycfn.com/Article/details/gtvzdynmda.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.feifeiyinyue.top/Article/details/gtisslipbt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.pycfn.com/Article/details/gtekbeqkjr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daxiang520.top/Article/details/gtrwpvxdiv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.pycfn.com/Article/details/gtjjveacqn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.feifeiyinyue.top/Article/details/gtdxywlbps.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvgbdrbgu.html

[H10] 资源自动释放
来源：http://dali.cqqwz.cn/Article/details/gtmeteierz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hfpthk.cn/Article/details/gtdbqvzlcq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sxryk.cn/Article/details/gtnkajuthx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gtmrdpseoi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gtwghsbftx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ybcxt.top/Article/details/gtslqoqkqp.html

Go:   defer f.Close()
来源：http://dali.vqdsnc.cn/Article/details/gtigaorwji.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hammf.cn/Article/details/gtgmdqlcpr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtqlyybjjw.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtnpogrwrd.html

I. 正则表达式
来源：http://dali.guannengcc.top/Article/details/gtejidlfxj.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtznwxncwq.html

[I01] 判断是否匹配
来源：http://dali.sufxvd.cn/Article/details/gtjdckkgkm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gteexpnsou.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtzwhrlvrz.html

JS:   /\d+/.test(s)
来源：http://dali.tian-w.cn/Article/details/gtfjywsgtm.html

TS:   /\d+/.test(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtissribyt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hywenlv.cn/Article/details/gtwmtjleku.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.andypj.xyz/Article/details/gtehrqewuj.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqxrqgvor.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.9152youxi.cn/Article/details/gttdjqnhck.html


<!-- 参考信息 -->