代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gttjisgjcz.html

[F06] 删除文件
来源：http://dali.hywenlv.cn/Article/details/gtgbfufxlm.html

Py:   os.remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gtywphekci.html

PHP:  unlink("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtfyifvdbt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtkyetjgyj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtrphejhhn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtrvoagpjy.html

Go:   os.Remove("a.txt")
来源：http://dali.tian-w.cn/Article/details/gthuitcycl.html

Ruby: File.delete("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtcmaqbljn.html

C#:   File.Delete("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtadnboxek.html

[F07] 创建目录（含多级）
来源：http://dali.yj20258888.top/Article/details/gtojtrtjfx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shuidangran.top/Article/details/gtzouuxzjg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gotoacloud.top/Article/details/gthweqeslh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhengqikj.top/Article/details/gtbzdyammp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gtiztngude.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zycfv.cn/Article/details/gtbvwyjmlz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuetiantiany.cn/Article/details/gtikuqvrqn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cucudq.cn/Article/details/gtlxlpxxjd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.bjfxy.top/Article/details/gtwjolnpgx.html

[F08] 遍历目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpypwawko.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cheryme.top/Article/details/gtmjsisyhr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shangyingyoupin.top/Article/details/gtrcpuvoem.html

JS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gtqgpzgyzd.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gtvqyjxewc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlfwmxucd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nwbrower.top/Article/details/gtowsmnanr.html

Ruby: Dir.children("dir")
来源：http://dali.svipenyu.cn/Article/details/gtdtjfguep.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jianghu66.top/Article/details/gtgrkusjkp.html

[F09] 获取文件大小
来源：http://dali.cdnleiting.top/Article/details/gtprjsgldk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gthazbifqd.html

PHP:  filesize("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtlextutxf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gtqcattoqw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gtgjgsuxxv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtrmydtheg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xuetiantiany.cn/Article/details/gtgaxoiaqc.html

Ruby: File.size("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtcmvsztje.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yanxiufei.cn/Article/details/gtaurtenif.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhsbahmo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtiojdbmrl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yueranfly.top/Article/details/gtjdoqdajy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtzjcmfevp.html

TS:   path.extname("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtswmrutrs.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jiagoushi.top/Article/details/gtkeoaujhn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtmaorbzct.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtjkdjjtxn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtxtjjrqih.html

[F11] 复制与移动文件
来源：http://dali.ppjwa.cn/Article/details/gthvrwsyly.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtbhmvqqbh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dianchejie.cn/Article/details/gtrexxeyuf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtgabsjegt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtamcriiov.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sweek.top/Article/details/gtrpqrewxi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuetiantiany.cn/Article/details/gtdfyberfh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtonsthztr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.aibaodan.cn/Article/details/gtuzelvjpk.html

[F12] CSV 读写
来源：http://dali.birdmap.top/Article/details/gtambcklyx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxuanxn.top/Article/details/gtithsobyu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tian-w.cn/Article/details/gtmhcuxxjv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zycfv.cn/Article/details/gtyjiixyjv.html

TS:   // 同上
来源：http://dali.yuanzhike.top/Article/details/gtgvjmviph.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigfzy.top/Article/details/gtpenieofz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.havefunace.top/Article/details/gtkzonfkad.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cqqwz.cn/Article/details/gtvxxaxjyw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.smart0.xyz/Article/details/gtlqfuvmro.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtabscatxs.html

G. 面向对象
来源：http://dali.cheryme.top/Article/details/gtmqamnihy.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtayxqzpyw.html

[G01] 定义类
来源：http://dali.kuanghao11.cn/Article/details/gtdhguhmom.html

Py:   class User: pass
来源：http://dali.shanyushiyangtech.top/Article/details/gtpsnecxtz.html

PHP:  class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtymeqvnfq.html

JS:   class User {}
来源：http://dali.daria6918.cn/Article/details/gtdzltonht.html

TS:   class User { name: string = ""; }
来源：http://dali.hnxiangtu.top/Article/details/gtszrbaszw.html

Java: class User {}
来源：http://dali.tian-w.cn/Article/details/gtcitvowih.html

Go:   type User struct { Name string }
来源：http://dali.sysykeji.top/Article/details/gtcwlaeyiq.html

Ruby: class User; end
来源：http://dali.nanxinkj.top/Article/details/gtfnfwlenb.html

C#:   class User {}
来源：http://dali.ydzc1.top/Article/details/gtllizjcma.html

[G02] 构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gtiscsnvue.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhongyouzk.top/Article/details/gtwomforjn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.quarkkingdee.top/Article/details/gtqzczohiu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtirwjkrfy.html

TS:   constructor(public name: string) {}
来源：http://dali.xinyue.icu/Article/details/gtculxsgry.html

Java: User(String name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gtrhpxuqbd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yongpay.top/Article/details/gtdhqikdqt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guannengcc.top/Article/details/gttddthrog.html

C#:   public User(string name) { Name = name; }
来源：http://dali.smart0.xyz/Article/details/gtpzzjqaar.html

[G03] 实例属性
来源：http://dali.gotoacloud.top/Article/details/gteydfdfib.html

Py:   self.name = "x"
来源：http://dali.yongpay.top/Article/details/gtqnpegxoc.html

PHP:  public string $name = "x";
来源：http://dali.birdmap.top/Article/details/gtirbwtobt.html

JS:   this.name = "x";
来源：http://dali.sysykeji.top/Article/details/gtwgtvwjcd.html

TS:   name: string = "x";
来源：http://dali.nwbrower.top/Article/details/gttjfijizu.html

Java: private String name;
来源：http://dali.yueranfly.top/Article/details/gttdgwqmav.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnqzz.top/Article/details/gtrggpfrgf.html

Ruby: @name = "x"
来源：http://dali.guowangkeji.top/Article/details/gtuhalarpv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zycfv.cn/Article/details/gtbooqfauk.html

[G04] 定义方法
来源：http://dali.hongshengwenyu.top/Article/details/gtcrlaqsgy.html

Py:   def greet(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gtxngtyimb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gteqeyitup.html

JS:   greet() { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtlusooccd.html

TS:   greet(): string { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtgrtrgsrn.html

Java: String greet() { return name; }
来源：http://dali.hnqzz.top/Article/details/gtrqwutsui.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtetjtyiqr.html

Ruby: def greet; @name; end
来源：http://dali.gogol.net.cn/Article/details/gtdsyogwvb.html

C#:   public string Greet() => Name;
来源：http://dali.yangfankeji.com/Article/details/gtrlmpjena.html

[G05] 继承
来源：http://dali.sxryk.cn/Article/details/gtgptdvfqf.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqwinkmwh.html

PHP:  class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtdjlbclzw.html

JS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtebqlbbas.html

TS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtrjsppliy.html

Java: class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtcslnhvtf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cucudq.cn/Article/details/gthtvofxyq.html

Ruby: class Admin < User; end
来源：http://dali.wangshuangyany.cn/Article/details/gtyxzisgqf.html

C#:   class Admin : User {}
来源：http://dali.gaohongyu789.top/Article/details/gtfbywcxhv.html

[G06] 重写方法
来源：http://dali.pycfn.com/Article/details/gtiivoucct.html

Py:   def greet(self): return "admin"
来源：http://dali.jianghu66.top/Article/details/gtwuotiwip.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtfimyguvz.html

JS:   greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtibogsmsn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtjdvpldeq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgjuncmbc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.316326.xyz/Article/details/gtbcbmzzgg.html

Ruby: def greet; "admin"; end
来源：http://dali.pycfn.com/Article/details/gtrbybcerw.html

C#:   public override string Greet() => "admin";
来源：http://dali.yongpay.top/Article/details/gtiajfmzgk.html

[G07] 调用父类方法
来源：http://dali.aizwys.cn/Article/details/gtzqtrvcbz.html

Py:   super().greet()
来源：http://dali.tianlin.xyz/Article/details/gtbmuoqmtg.html

PHP:  parent::greet();
来源：http://dali.zhoulong.xyz/Article/details/gtbmwdqdac.html

JS:   super.greet();
来源：http://dali.ydzc1.top/Article/details/gtplbiweys.html

TS:   super.greet();
来源：http://dali.redwolf501.top/Article/details/gtmnhkcrqh.html

Java: super.greet();
来源：http://dali.dianchejie.cn/Article/details/gtdwyniulm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yvedp.cn/Article/details/gtwinkslsl.html

Ruby: super
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnkzwoks.html

C#:   base.Greet();
来源：http://dali.wangshuangyany.cn/Article/details/gthivhctqy.html

[G08] 静态方法与属性
来源：http://dali.cashguo.top/Article/details/gtjakpfqug.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jyoumei.cn/Article/details/gtbdvszdjc.html

PHP:  public static function f() {}
来源：http://dali.yj202588.top/Article/details/gthbgtareo.html

JS:   static f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtjdkqwcxl.html

TS:   static f(): void {}
来源：http://dali.iojbl.cn/Article/details/gtlpdyhlwx.html

Java: static void f() {}
来源：http://dali.c1oappe.top/Article/details/gtwucxwdic.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenzaomai.com/Article/details/gtyrwjwkac.html

Ruby: def self.f; end
来源：http://dali.birdmap.top/Article/details/gtxiqttakf.html

C#:   public static void F() {}
来源：http://dali.bjfxy.top/Article/details/gtlrrsrwmb.html

[G09] 接口 / 抽象类
来源：http://dali.xinyue.icu/Article/details/gtdqunkzgm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yangfankeji.com/Article/details/gtdstmafam.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gaohongyu789.top/Article/details/gtlvjnozbl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigfzy.top/Article/details/gtdwqrlppl.html

TS:   interface Shape { area(): number; }
来源：http://dali.zycfv.cn/Article/details/gtggxnqyvl.html

Java: interface Shape { double area(); }
来源：http://dali.jqgfzy.top/Article/details/gtkjfxlpid.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.bjfxy.top/Article/details/gtldnvptld.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.iojbl.cn/Article/details/gtjuybhtfv.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxuanxn.top/Article/details/gtgpatohhf.html

[G10] 访问控制
来源：http://dali.zhongyouzk.top/Article/details/gtqbxrozyb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jyoumei.cn/Article/details/gticrhjtdr.html

PHP:  public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtctadiafk.html

JS:   #private 字段；其余公开
来源：http://dali.gzhubu.top/Article/details/gtplbgwddr.html

TS:   public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlojqndkk.html

Java: public / protected / private / 默认包级
来源：http://dali.ybcxt.top/Article/details/gtupaapjlv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhixingplan.top/Article/details/gtuhszgnut.html

Ruby: public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gtihxswafq.html

C#:   public / protected / private / internal
来源：http://dali.meibo888.top/Article/details/gtkuzrwiii.html

[G11] getter / setter
来源：http://dali.yj20258.top/Article/details/gtzajlyyzm.html

Py:   @property 与 @x.setter
来源：http://dali.yuxming.cn/Article/details/gtqdzpuxxi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtttejtzap.html

JS:   get name() { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gtuckztdpp.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gtpiwwfocp.html

Java: public String getName() { return name; }
来源：http://dali.shuidangran.top/Article/details/gtahpxfobt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gteefbxnfg.html

Ruby: attr_accessor :name
来源：http://dali.ppjwa.cn/Article/details/gtegjyfqtt.html

C#:   public string Name { get; set; }
来源：http://dali.bjfxy.top/Article/details/gtyznrxovq.html

[G12] 对象转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtvqolvtul.html

Py:   def __str__(self): return self.name
来源：http://dali.hywenlv.cn/Article/details/gtsicqicjf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gtouewkmia.html

JS:   toString() { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtsdyhbees.html

TS:   toString(): string { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtcojbqajd.html

Java: @Override public String toString() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtifsnqcox.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gttiwozxie.html

Ruby: def to_s; @name; end
来源：http://dali.0kj1m.cn/Article/details/gtyehftkib.html

C#:   public override string ToString() => Name;
来源：http://dali.chenzaomai.com/Article/details/gtvtlzgwui.html

[G13] 判断对象类型
来源：http://dali.aizwys.cn/Article/details/gtsebiyaol.html

Py:   isinstance(u, User)
来源：http://dali.yangfankeji.com/Article/details/gtqxuduqol.html

PHP:  $u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtywvmrljb.html

JS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtzjvqsxgr.html

TS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gtlfdpdbeg.html

Java: u instanceof User
来源：http://dali.birdmap.top/Article/details/gtssprxaxd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhoulong.xyz/Article/details/gtfygoeand.html

Ruby: u.is_a?(User)
来源：http://dali.xuetiantiany.cn/Article/details/gtrqmkdbez.html

C#:   u is User
来源：http://dali.zdqjudy.top/Article/details/gtfyizuyat.html

[G14] 数据类 / record
来源：http://dali.wangdashe.top/Article/details/gtriydmhyx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.feifeiyinyue.top/Article/details/gtridgutxx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenjidiqi.icu/Article/details/gtnvtodwlr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shangyingyoupin.top/Article/details/gtqecwwwum.html

TS:   type User = { name: string; age: number };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxqcmtsho.html

Java: record User(String name, int age) {}
来源：http://dali.jinqigfzy.top/Article/details/gtciqipcnt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yvedp.cn/Article/details/gthokrczbb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.snrcjt.cn/Article/details/gtljshmurl.html

C#:   record User(string Name, int Age);
来源：http://dali.yj202588.top/Article/details/gtdgvaivzd.html

[G15] 枚举
来源：http://dali.feifeiyinyue.top/Article/details/gtgsutliat.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jiagoushi.top/Article/details/gtkwetqnua.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.svipenyu.cn/Article/details/gtjtaoqpkv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenjidiqi.icu/Article/details/gtmuyypatr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tian-w.cn/Article/details/gtautwggzk.html

Java: enum Color { RED, GREEN }
来源：http://dali.pycfn.com/Article/details/gtdrjxecyh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpqboypoa.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhixingplan.top/Article/details/gtoabkwpye.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtomdhrkoj.html

[G16] 对象转数组 / 字典
来源：http://dali.316326.xyz/Article/details/gtthntetuc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258888.top/Article/details/gtznhzxzig.html

PHP:  get_object_vars($obj);
来源：http://dali.yvedp.cn/Article/details/gtscukfkyz.html

JS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gtvizwkfbs.html

TS:   Object.entries(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzehzkewz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.birdmap.top/Article/details/gtjtjxifhz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ehwqpu.com/Article/details/gtxxxfaewm.html

Ruby: obj.instance_variables
来源：http://dali.jinghuilouyu.cn/Article/details/gtohblsnbf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gtkqxbnfqk.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtpvpivgej.html

H. 异常与错误处理
来源：http://dali.andypj.xyz/Article/details/gtilsgrqvt.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gttcbmwqbh.html

[H01] try / catch 基础
来源：http://dali.zdqjudy.top/Article/details/gtezssikns.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sxryk.cn/Article/details/gtuopgtvay.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xylfe.cn/Article/details/gtxmjuzsfl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gtqcmnfswb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtpnzawyyg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yanxiufei.cn/Article/details/gtglyhsjtb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangshuangyany.cn/Article/details/gtbstpuxvx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.haohaochexian.top/Article/details/gtfqbvspgt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tanke756.top/Article/details/gtlpayxbvy.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangtech.top/Article/details/gtmpokevol.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.c1oappe.top/Article/details/gtaeftjyls.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gttcjqxyhw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtympdsjtz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtwrlryfaf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtmosbsmak.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenlongwang.top/Article/details/gtmhrfxokh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hongshengwenyu.top/Article/details/gtdgvggzoj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtsxtjbfho.html

[H03] 主动抛出异常
来源：http://dali.nwbrower.top/Article/details/gtohfncpki.html

Py:   raise ValueError("错误信息")
来源：http://dali.birdmap.top/Article/details/gtvxiyxglg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtuytamnba.html

JS:   throw new Error("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtpavilrnv.html

TS:   throw new Error("错误信息");
来源：http://dali.fengsongda.top/Article/details/gthhflbexj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtzyoldety.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgfzy.top/Article/details/gtcyzvbmlg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkpchecpd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gtvlvrnmhx.html

[H04] 自定义异常类型
来源：http://dali.mhx1999.top/Article/details/gtwcvmogqi.html

Py:   class MyError(Exception): pass
来源：http://dali.hongshengwenyu.top/Article/details/gtfqewisgl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gtuoajbhrp.html

JS:   class MyError extends Error {}
来源：http://dali.daria6918.cn/Article/details/gtkfahprwd.html

TS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gtzbyxtygy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gtxeeyxnkm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.9152youxi.cn/Article/details/gttezchgeq.html

Ruby: class MyError < StandardError; end
来源：http://dali.xuanzx.com/Article/details/gtxplnfils.html

C#:   class MyException : Exception {}
来源：http://dali.yonumen.top/Article/details/gtqwymzfjz.html

[H05] 捕获特定类型
来源：http://dali.jinqigufen.top/Article/details/gtbkpunhlp.html

Py:   except ValueError as e:
来源：http://dali.zhoulong.xyz/Article/details/gtcmctdbtt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sxryk.cn/Article/details/gtrnlbubtr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gthcvwemtr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gtmgyvouli.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sysykeji.top/Article/details/gtbvyccvve.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gzhubu.top/Article/details/gtkrjtajjg.html

Ruby: rescue ArgumentError => e
来源：http://dali.cqqwz.cn/Article/details/gthogitycq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrocufcmj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuetiantiany.cn/Article/details/gtotmssohe.html

Py:   value = d.get("k") or default
来源：http://dali.quarkkingdee.top/Article/details/gtckktnalq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangdashe.top/Article/details/gtmsvaczni.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gtcvvnyyyl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gtallikbno.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtajztdyrl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ybcxt.top/Article/details/gtpctskxvf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shzxlz.cn/Article/details/gtddiundvi.html

C#:   obj?.A?.B ?? default
来源：http://dali.cqqwz.cn/Article/details/gtmwgbivff.html

[H07] 断言
来源：http://dali.andypj.xyz/Article/details/gtjwbfrepx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sysykeji.top/Article/details/gtlmxavkpc.html

PHP:  assert($x > 0);
来源：http://dali.fzhhl.top/Article/details/gttxoadrnf.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtsjszffoz.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtsjaaashc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuxming.cn/Article/details/gtqinqayky.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pycfn.com/Article/details/gtoeblnwtu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yvedp.cn/Article/details/gtihvzfvon.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gtkkwcnfzm.html

[H08] 获取错误信息与堆栈
来源：http://dali.tian-w.cn/Article/details/gtwucairbe.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xuetiantiany.cn/Article/details/gtkevxlomy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.fengsongda.top/Article/details/gtzqgbkakt.html

JS:   e.message;  e.stack
来源：http://dali.mhx1999.top/Article/details/gtysjpdmyi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gotoacloud.top/Article/details/gtohykfihy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.haohaochexian.top/Article/details/gtuyysdgyv.html

Go:   err.Error()
来源：http://dali.kuanghao11.cn/Article/details/gtiexlahes.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangshuangyany.cn/Article/details/gtihysfbmn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.birdmap.top/Article/details/gtkxrntcys.html

[H09] 带错误码的异常
来源：http://dali.gaohongyu789.top/Article/details/gtmrjwenfg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xziqi.cn/Article/details/gtdfjysfah.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.aibaodan.cn/Article/details/gtfwrrrizi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sxryk.cn/Article/details/gtsufcdjov.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangshuangyany.cn/Article/details/gtoyviiiap.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tianlin.xyz/Article/details/gtohwhwwqv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jianghu66.top/Article/details/gtnobixmik.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pycfn.com/Article/details/gtisrnwzgv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenzaomai.com/Article/details/gtacgrrrat.html

[H10] 资源自动释放
来源：http://dali.yuxming.cn/Article/details/gtukaaecfr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nanxuanxn.top/Article/details/gtlyflkjqp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hfpthk.cn/Article/details/gtzmfoqnke.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gtzfakktzd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gtynhvpqvs.html


<!-- 参考信息 -->