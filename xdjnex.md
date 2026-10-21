代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtouywshoi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtnyujwotv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sweek.top/Article/details/gttdepwaor.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzznukdnn.html

C#:   File.Exists("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtbhukmdls.html

[F06] 删除文件
来源：http://dali.9152youxi.cn/Article/details/gtiayhlmer.html

Py:   os.remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtggbiaram.html

PHP:  unlink("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtccxgqwge.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtyaygepgw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtauarbcdu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtbckhuszc.html

Go:   os.Remove("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtccbdzvig.html

Ruby: File.delete("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtgyoqwxby.html

C#:   File.Delete("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtpgcgdzoa.html

[F07] 创建目录（含多级）
来源：http://dali.birdmap.top/Article/details/gtwavtijkz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gtbuekcbhr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yueranfly.top/Article/details/gtsmoqaadj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.birdmap.top/Article/details/gtftgqjcrv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.0kj1m.cn/Article/details/gtytcutdqs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigfzy.top/Article/details/gtnomljxyb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.svipenyu.cn/Article/details/gtvrncsnxe.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gtebetjrff.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhluotpu.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gtjnxonplx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.feifeiyinyue.top/Article/details/gtucxwitza.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yongpay.top/Article/details/gtbkkrsrji.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gtysgziagl.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtsxecagxq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.316326.xyz/Article/details/gtljfvjzok.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cheryme.top/Article/details/gtgofqkzmq.html

Ruby: Dir.children("dir")
来源：http://dali.guowangkeji.top/Article/details/gtxftwvaeo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.havefunace.top/Article/details/gtaddvosgb.html

[F09] 获取文件大小
来源：http://dali.cheryme.top/Article/details/gtqwmpcqvx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtoswtqhhi.html

PHP:  filesize("a.txt");
来源：http://dali.havefunace.top/Article/details/gtlltuaajr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gtvpniashj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gtuloyabce.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtcdhunkug.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.quarkkingdee.top/Article/details/gtaaiurpph.html

Ruby: File.size("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtryxxuovq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhoulong.xyz/Article/details/gthbaenjmc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.svipenyu.cn/Article/details/gthgxaseih.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtpbdltjdw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcnhieotd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtlfjdklxr.html

TS:   path.extname("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtjzkwftep.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangshuangyany.cn/Article/details/gtswkqmvli.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtixwyexhv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtxmqdrumh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtopzkawxv.html

[F11] 复制与移动文件
来源：http://dali.wangdashe.top/Article/details/gtfikptmyq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsszunfka.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tanke756.top/Article/details/gtuazmnvkr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtwvhxjzvr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtqhkucszp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jyoumei.cn/Article/details/gtirycsnvs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj202588.top/Article/details/gtyibtplxa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtjukdltcb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cqqwz.cn/Article/details/gtjkkpiiwo.html

[F12] CSV 读写
来源：http://dali.havefunace.top/Article/details/gtsggfyoxd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.redwolf501.top/Article/details/gtgdqsqbyd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsigyztbl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yanxiufei.cn/Article/details/gtqikktryo.html

TS:   // 同上
来源：http://dali.havefunace.top/Article/details/gtlqffdfnt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fengsongda.top/Article/details/gtaazgdylh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhongyouzk.top/Article/details/gtzdtoxvqu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangshuangyany.cn/Article/details/gtxbgixvpy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.guowangkeji.top/Article/details/gtnkvyrzze.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtyexhdkwn.html

G. 面向对象
来源：http://dali.hongshengwenyu.top/Article/details/gtzlfnegyb.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtxlunwzep.html

[G01] 定义类
来源：http://dali.yj202588.top/Article/details/gtziotoufy.html

Py:   class User: pass
来源：http://dali.xuanzx.com/Article/details/gtrmxcqsot.html

PHP:  class User {}
来源：http://dali.ybcxt.top/Article/details/gtjbqbedgn.html

JS:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gtshsbwfmo.html

TS:   class User { name: string = ""; }
来源：http://dali.dianchejie.cn/Article/details/gtfankziuh.html

Java: class User {}
来源：http://dali.c1oappe.top/Article/details/gtqwvcitht.html

Go:   type User struct { Name string }
来源：http://dali.jyoumei.cn/Article/details/gtdpoconsk.html

Ruby: class User; end
来源：http://dali.feifeiyinyue.top/Article/details/gtkxvhhzdh.html

C#:   class User {}
来源：http://dali.meibo888.top/Article/details/gtuvrsmjnf.html

[G02] 构造函数
来源：http://dali.redwolf501.top/Article/details/gthplgarsx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258.top/Article/details/gtalwobrmr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuanzx.com/Article/details/gthsreygwg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gtfqbiphsx.html

TS:   constructor(public name: string) {}
来源：http://dali.guannengcc.top/Article/details/gtnuybjsir.html

Java: User(String name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gtuysjzwft.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.meibo888.top/Article/details/gttoueceqy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shuidangran.top/Article/details/gtpwsoechz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.mhx1999.top/Article/details/gtbtkipjwu.html

[G03] 实例属性
来源：http://dali.redwolf501.top/Article/details/gtksubgdxq.html

Py:   self.name = "x"
来源：http://dali.tianlin.xyz/Article/details/gtwplwpeox.html

PHP:  public string $name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtbxmsxuxt.html

JS:   this.name = "x";
来源：http://dali.havefunace.top/Article/details/gtfgvqopop.html

TS:   name: string = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtblqqzukt.html

Java: private String name;
来源：http://dali.mhx1999.top/Article/details/gteebxipml.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gaohongyu789.top/Article/details/gtyhsybdtf.html

Ruby: @name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gttajqbpln.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cashguo.top/Article/details/gtjzxaktmy.html

[G04] 定义方法
来源：http://dali.hywenlv.cn/Article/details/gtxfbgolob.html

Py:   def greet(self): return self.name
来源：http://dali.hysaishi.cn/Article/details/gtuhovzjik.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqrskipw.html

JS:   greet() { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjpokqmrq.html

TS:   greet(): string { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtpsyegnbe.html

Java: String greet() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtyndenikk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gtdrvyzlsr.html

Ruby: def greet; @name; end
来源：http://dali.bjfxy.top/Article/details/gtgxskbarq.html

C#:   public string Greet() => Name;
来源：http://dali.cashguo.top/Article/details/gtmhkcyfnu.html

[G05] 继承
来源：http://dali.0kj1m.cn/Article/details/gtivvdzclh.html

Py:   class Admin(User): pass
来源：http://dali.cdnleiting.top/Article/details/gtevyntmhy.html

PHP:  class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtyydbbgde.html

JS:   class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtcijwwjxr.html

TS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtbxilqlkd.html

Java: class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gtmjqjxlfm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hnqzz.top/Article/details/gtssbknoay.html

Ruby: class Admin < User; end
来源：http://dali.zhiwuduotai.top/Article/details/gthncecowb.html

C#:   class Admin : User {}
来源：http://dali.meibo888.top/Article/details/gtaubowfmc.html

[G06] 重写方法
来源：http://dali.yj202588.top/Article/details/gtsxjtfqpf.html

Py:   def greet(self): return "admin"
来源：http://dali.xinyue.icu/Article/details/gtkzcvrxle.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtfxdebcdj.html

JS:   greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtbckxhekp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtdrhwrwkt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtezgyhodk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ydzc1.top/Article/details/gtqjussriw.html

Ruby: def greet; "admin"; end
来源：http://dali.hongshengwenyu.top/Article/details/gtetnicswg.html

C#:   public override string Greet() => "admin";
来源：http://dali.c1oappe.top/Article/details/gtpfwkgmin.html

[G07] 调用父类方法
来源：http://dali.chenlongwang.top/Article/details/gtyaehmqae.html

Py:   super().greet()
来源：http://dali.andypj.xyz/Article/details/gtmvdfffxl.html

PHP:  parent::greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtsmzkaceq.html

JS:   super.greet();
来源：http://dali.daxiang520.top/Article/details/gtbwvtziak.html

TS:   super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtyqjdqtqi.html

Java: super.greet();
来源：http://dali.yangfankeji.com/Article/details/gtfvxofigi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aizwys.cn/Article/details/gtzvojsdre.html

Ruby: super
来源：http://dali.smart0.xyz/Article/details/gtamemeukh.html

C#:   base.Greet();
来源：http://dali.hysaishi.cn/Article/details/gtcabhcsfr.html

[G08] 静态方法与属性
来源：http://dali.zhixingplan.top/Article/details/gtyivxxsys.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nanxinkj.top/Article/details/gtrgxtnunm.html

PHP:  public static function f() {}
来源：http://dali.zhixingplan.top/Article/details/gtecuisqax.html

JS:   static f() {}
来源：http://dali.fengsongda.top/Article/details/gteoofxjmd.html

TS:   static f(): void {}
来源：http://dali.wangdashe.top/Article/details/gtlytdjifq.html

Java: static void f() {}
来源：http://dali.snrcjt.cn/Article/details/gtzneaoiro.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cqqwz.cn/Article/details/gtfbkezkhq.html

Ruby: def self.f; end
来源：http://dali.jqgfzy.top/Article/details/gtersqhfyt.html

C#:   public static void F() {}
来源：http://dali.hnxiangtu.top/Article/details/gtvgmmdhkg.html

[G09] 接口 / 抽象类
来源：http://dali.sxryk.cn/Article/details/gtiafqudfb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gotoacloud.top/Article/details/gtjgwaccpp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shzxlz.cn/Article/details/gtuqzcfcpl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hfpthk.cn/Article/details/gttyalxrja.html

TS:   interface Shape { area(): number; }
来源：http://dali.cdnleiting.top/Article/details/gttznoqdzx.html

Java: interface Shape { double area(); }
来源：http://dali.gotoacloud.top/Article/details/gtksecsgbp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.aizwys.cn/Article/details/gtrymkvgwz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.smart0.xyz/Article/details/gtnuvqmtoc.html

C#:   interface IShape { double Area(); }
来源：http://dali.andypj.xyz/Article/details/gtvsacjogh.html

[G10] 访问控制
来源：http://dali.tianlin.xyz/Article/details/gtdcyovcif.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhengqikj.top/Article/details/gtpednfolh.html

PHP:  public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtumxswlqw.html

JS:   #private 字段；其余公开
来源：http://dali.wangdashe.top/Article/details/gtbxkjofkg.html

TS:   public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtvsjueynf.html

Java: public / protected / private / 默认包级
来源：http://dali.xylfe.cn/Article/details/gtauwusspu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xinyue.icu/Article/details/gtrfexcfjp.html

Ruby: public / protected / private
来源：http://dali.cucudq.cn/Article/details/gthlsurmvt.html

C#:   public / protected / private / internal
来源：http://dali.zdqjudy.top/Article/details/gtvluphymu.html

[G11] getter / setter
来源：http://dali.cashguo.top/Article/details/gtwzkgdyzt.html

Py:   @property 与 @x.setter
来源：http://dali.fzhhl.top/Article/details/gtqwczfcvb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gtmrjznymn.html

JS:   get name() { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gtzmbnvfze.html

TS:   get name(): string { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gtwpnbwaih.html

Java: public String getName() { return name; }
来源：http://dali.havefunace.top/Article/details/gtshdohmhn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gtisakosmf.html

Ruby: attr_accessor :name
来源：http://dali.gotoacloud.top/Article/details/gtlvghzfkk.html

C#:   public string Name { get; set; }
来源：http://dali.daxiang520.top/Article/details/gtckjvnhhu.html

[G12] 对象转字符串
来源：http://dali.jinqigfzy.top/Article/details/gtpdloabpr.html

Py:   def __str__(self): return self.name
来源：http://dali.birdmap.top/Article/details/gtpqyolcoa.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtrjixtxpz.html

JS:   toString() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gtsziphxdi.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtqfoscqwi.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtuicdpgra.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gtbzrkgwbj.html

Ruby: def to_s; @name; end
来源：http://dali.iojbl.cn/Article/details/gtwifapjst.html

C#:   public override string ToString() => Name;
来源：http://dali.bjfxy.top/Article/details/gttnyzsyis.html

[G13] 判断对象类型
来源：http://dali.hammf.cn/Article/details/gtinyrumyt.html

Py:   isinstance(u, User)
来源：http://dali.fengsongda.top/Article/details/gtpujftebm.html

PHP:  $u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtparoablq.html

JS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtaolkwkdd.html

TS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gtlanjxeme.html

Java: u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtumygoeoq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yueranfly.top/Article/details/gtraqhwlbe.html

Ruby: u.is_a?(User)
来源：http://dali.svipenyu.cn/Article/details/gtnruxzdnc.html

C#:   u is User
来源：http://dali.0kj1m.cn/Article/details/gtueluundg.html

[G14] 数据类 / record
来源：http://dali.pycfn.com/Article/details/gtrgnehzub.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ywan-chungtsiang.top/Article/details/gteofzdvun.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jqgfzy.top/Article/details/gtdjgcqmnh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tian-w.cn/Article/details/gtytokskcr.html

TS:   type User = { name: string; age: number };
来源：http://dali.xziqi.cn/Article/details/gtaoxiyrgj.html

Java: record User(String name, int age) {}
来源：http://dali.yj202588.top/Article/details/gtoozgzlfx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guannengcc.top/Article/details/gtkrnelwpb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenjidiqi.icu/Article/details/gtwljuloez.html

C#:   record User(string Name, int Age);
来源：http://dali.dashuyun.cn/Article/details/gtredwjvrf.html

[G15] 枚举
来源：http://dali.hnxiangtu.top/Article/details/gtjhgrvfjj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgufenzy.top/Article/details/gtxjgrebxi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yanxiufei.cn/Article/details/gtwbcjshpq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hnqzz.top/Article/details/gtiymicrja.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfgxsujxs.html

Java: enum Color { RED, GREEN }
来源：http://dali.hywenlv.cn/Article/details/gtdrusspus.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yangfankeji.com/Article/details/gtxzavzfuh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnqzz.top/Article/details/gtfmbltlsq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tanke756.top/Article/details/gtbdxgshtz.html

[G16] 对象转数组 / 字典
来源：http://dali.smart0.xyz/Article/details/gtzaiccztn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xuanzx.com/Article/details/gtohoraaoy.html

PHP:  get_object_vars($obj);
来源：http://dali.wangdashe.top/Article/details/gtqvwlzscs.html

JS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gtyeaxkfsq.html

TS:   Object.entries(obj)
来源：http://dali.yj202588.top/Article/details/gtthxhrtyk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aibaodan.cn/Article/details/gtgmhjvife.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangdashe.top/Article/details/gtehxrzyhn.html

Ruby: obj.instance_variables
来源：http://dali.chenzaomai.com/Article/details/gtawkeggxb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hammf.cn/Article/details/gtzkvfvdcc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtnbimqtln.html

H. 异常与错误处理
来源：http://dali.jinqigufen.top/Article/details/gtqklqzzxl.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtbdzmlxly.html

[H01] try / catch 基础
来源：http://dali.yangfankeji.com/Article/details/gtmqtcazpf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhongyouzk.top/Article/details/gtjldbbphv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yangfankeji.com/Article/details/gtvcfnasep.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gtqvwwzrpw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gtztoyjvoo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258888.top/Article/details/gtmsdhctmw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sxryk.cn/Article/details/gtfppgbcva.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxinkj.top/Article/details/gtpbpbggmg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xziqi.cn/Article/details/gtriskbzyu.html

[H02] finally / ensure 收尾
来源：http://dali.ppjwa.cn/Article/details/gtxwwsjpel.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.feifeiyinyue.top/Article/details/gtfdpzvllk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gttqtgfuwd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gttwaufnyw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtkqzwxcjc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtjqjxrhpv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.meibo888.top/Article/details/gtdpoomwut.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.feifeiyinyue.top/Article/details/gtdavakqfc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtuepushay.html

[H03] 主动抛出异常
来源：http://dali.tian-w.cn/Article/details/gtbigfpezm.html

Py:   raise ValueError("错误信息")
来源：http://dali.hammf.cn/Article/details/gtovmldkyi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtbzhorbad.html

JS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtwwrkupmn.html

TS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkijurqsn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtusmzuwlg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.birdmap.top/Article/details/gtraawbuya.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhiwuduotai.top/Article/details/gtlnidrczm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtqruwqgqh.html

[H04] 自定义异常类型
来源：http://dali.zdqjudy.top/Article/details/gtktgjxchl.html

Py:   class MyError(Exception): pass
来源：http://dali.yangfankeji.com/Article/details/gtlpwyyjjb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gtdoqoyhne.html

JS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gtcyrhkmhs.html

TS:   class MyError extends Error {}
来源：http://dali.fzhhl.top/Article/details/gtrjoctzle.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gtwjlevguj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxuanxn.top/Article/details/gtrliywwwn.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigufen.top/Article/details/gtvrfjodai.html

C#:   class MyException : Exception {}
来源：http://dali.zhengqikj.top/Article/details/gtjanlwkfk.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gtvnurddqo.html

Py:   except ValueError as e:
来源：http://dali.yonumen.top/Article/details/gtayhlavia.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jlsjyb.cn/Article/details/gtfssbsvkx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yvedp.cn/Article/details/gtmmszhihi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.havefunace.top/Article/details/gtjdhrbapv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yvedp.cn/Article/details/gtckoglnnr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xinyue.icu/Article/details/gtpdtmnnxc.html

Ruby: rescue ArgumentError => e
来源：http://dali.fengsongda.top/Article/details/gtpqoaizfu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hammf.cn/Article/details/gtykfdxxuf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xylfe.cn/Article/details/gtebhizbtb.html

Py:   value = d.get("k") or default
来源：http://dali.yueranfly.top/Article/details/gtnszzjgfm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xylfe.cn/Article/details/gtkeioyvqq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gthusxpvvp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuxming.cn/Article/details/gtslrsthwq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxinkj.top/Article/details/gtmcnnatlu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cucudq.cn/Article/details/gtcjemzums.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shangyingyoupin.top/Article/details/gtxkdkyprc.html

C#:   obj?.A?.B ?? default
来源：http://dali.sysykeji.top/Article/details/gtqvoqxflh.html

[H07] 断言
来源：http://dali.yvedp.cn/Article/details/gtmihtekzp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jlsjyb.cn/Article/details/gtlvsbfhyt.html

PHP:  assert($x > 0);
来源：http://dali.316326.xyz/Article/details/gtnovveuxr.html

JS:   console.assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtwaitsobb.html

TS:   console.assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtudmwmzao.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hfpthk.cn/Article/details/gtaijaxiwt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.svipenyu.cn/Article/details/gtuhjauwwm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shanyushiyangtech.top/Article/details/gtqipzbkdr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gttfuxusri.html

[H08] 获取错误信息与堆栈
来源：http://dali.cqqwz.cn/Article/details/gtjpdmuhrj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.316326.xyz/Article/details/gtjyhwmopd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gzhubu.top/Article/details/gtkyqqnlyh.html

JS:   e.message;  e.stack
来源：http://dali.nanxinkj.top/Article/details/gtwldvazvv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.mhx1999.top/Article/details/gtunjtvdyl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhixingplan.top/Article/details/gtkzeyiurs.html

Go:   err.Error()
来源：http://dali.jianghu66.top/Article/details/gtrtmuqcdc.html

Ruby: e.message;  e.backtrace
来源：http://dali.daxiang520.top/Article/details/gtxyyjbcnm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sufxvd.cn/Article/details/gtulwjyqdd.html

[H09] 带错误码的异常
来源：http://dali.cashguo.top/Article/details/gtymmbdspy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sufxvd.cn/Article/details/gtrnwfdyls.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuxming.cn/Article/details/gtacxqgckb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhengqikj.top/Article/details/gtoiuekmiy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daria6918.cn/Article/details/gtjtkyspgu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.dianchejie.cn/Article/details/gtdvpugzlw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ehwqpu.com/Article/details/gtrhyuouxn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.c1oappe.top/Article/details/gttteoyzzd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gtogoogjmh.html

[H10] 资源自动释放
来源：http://dali.jyoumei.cn/Article/details/gtsxqabbzu.html


<!-- 参考信息 -->