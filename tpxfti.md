代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtxllzeewa.html

[F06] 删除文件
来源：http://dali.sufxvd.cn/Article/details/gtetegudeh.html

Py:   os.remove("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtzbwioydt.html

PHP:  unlink("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtgivyqave.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtrttwueva.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtjybluwpy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gtrmukjuss.html

Go:   os.Remove("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtmrbgqetv.html

Ruby: File.delete("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtpprxaslj.html

C#:   File.Delete("a.txt");
来源：http://dali.hammf.cn/Article/details/gtdofkvgij.html

[F07] 创建目录（含多级）
来源：http://dali.xinyue.icu/Article/details/gtmgplcajq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.9152youxi.cn/Article/details/gtcpuchwls.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tian-w.cn/Article/details/gtlkaatrwz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258888.top/Article/details/gtdgfimoie.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxfafmoz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pycfn.com/Article/details/gtnokcwbuu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.c1oappe.top/Article/details/gtufjfhxie.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yanxiufei.cn/Article/details/gtvmysxhiv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj20258888.top/Article/details/gtvgczmgax.html

[F08] 遍历目录
来源：http://dali.ivvv.top/Article/details/gtvatojuno.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.kuanghao11.cn/Article/details/gtvehvcfss.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gotoacloud.top/Article/details/gttvnxsnrk.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtbpdzwehq.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinqigufen.top/Article/details/gtzqhzcqwf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jlsjyb.cn/Article/details/gtwaphrswu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtpduymvya.html

Ruby: Dir.children("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtclstuijt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ehwqpu.com/Article/details/gtijcsbkbk.html

[F09] 获取文件大小
来源：http://dali.sxryk.cn/Article/details/gtgpeivczx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtgjxhbhnz.html

PHP:  filesize("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtlhfbjcke.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gtgpuhgbou.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gtqihioqwi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtlppzanje.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cashguo.top/Article/details/gtunducvnj.html

Ruby: File.size("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtklcrrxyq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenlongwang.top/Article/details/gtqnqlvrlx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ppjwa.cn/Article/details/gtrifjbbsr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtelllwauh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258.top/Article/details/gtntrhtwja.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtttipimyq.html

TS:   path.extname("a.txt")
来源：http://dali.pycfn.com/Article/details/gtulaovhbo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258.top/Article/details/gtsifgwulj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtrdafxqnt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtxyazwbat.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtxblboxve.html

[F11] 复制与移动文件
来源：http://dali.tian-w.cn/Article/details/gtfofdbjzz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtljphdeai.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfvkdckt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtyzoieukk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtcdiftjgn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pycfn.com/Article/details/gtbioseiqo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhengqikj.top/Article/details/gtlufsatkd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxdnmoae.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.vqdsnc.cn/Article/details/gtnhzdcyza.html

[F12] CSV 读写
来源：http://dali.hammf.cn/Article/details/gtoobsywve.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xylfe.cn/Article/details/gtthdatvia.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.316326.xyz/Article/details/gthvzfzslu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sufxvd.cn/Article/details/gtcbbosrje.html

TS:   // 同上
来源：http://dali.birdmap.top/Article/details/gtjoyececq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.kuanghao11.cn/Article/details/gtgjxnnxjp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.9152youxi.cn/Article/details/gtzwnpljfy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.iojbl.cn/Article/details/gtdgxythcj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nanxinkj.top/Article/details/gtrtgsebcr.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gthacxwuet.html

G. 面向对象
来源：http://dali.guowangkeji.top/Article/details/gtfueemoot.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtgjseonki.html

[G01] 定义类
来源：http://dali.yuxming.cn/Article/details/gtxcetmvlo.html

Py:   class User: pass
来源：http://dali.gzhubu.top/Article/details/gtqlqrtnur.html

PHP:  class User {}
来源：http://dali.yuxming.cn/Article/details/gtgarvmsdd.html

JS:   class User {}
来源：http://dali.havefunace.top/Article/details/gtfzwzfvvg.html

TS:   class User { name: string = ""; }
来源：http://dali.fzhhl.top/Article/details/gtuwkmbcxa.html

Java: class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmccclrt.html

Go:   type User struct { Name string }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtojvaxmxt.html

Ruby: class User; end
来源：http://dali.xuanzx.com/Article/details/gtrhkobmef.html

C#:   class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gterznasbx.html

[G02] 构造函数
来源：http://dali.nwbrower.top/Article/details/gtumkprhwf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqqqocdk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jiagoushi.top/Article/details/gtuvbdnkwz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gtvhopkdhe.html

TS:   constructor(public name: string) {}
来源：http://dali.birdmap.top/Article/details/gtrxncmcwv.html

Java: User(String name) { this.name = name; }
来源：http://dali.316326.xyz/Article/details/gtthabrsdu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cqqwz.cn/Article/details/gttsnwvstg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ppjwa.cn/Article/details/gtthsuahhx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtrlyltibf.html

[G03] 实例属性
来源：http://dali.hammf.cn/Article/details/gthawimslu.html

Py:   self.name = "x"
来源：http://dali.xylfe.cn/Article/details/gtinfbmlzp.html

PHP:  public string $name = "x";
来源：http://dali.nwbrower.top/Article/details/gtbecytydb.html

JS:   this.name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtompsknpi.html

TS:   name: string = "x";
来源：http://dali.sxryk.cn/Article/details/gtlcbajbvk.html

Java: private String name;
来源：http://dali.yj20258.top/Article/details/gtlvdnlfwf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.iojbl.cn/Article/details/gtemgcgrch.html

Ruby: @name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gtvshhwqqw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxwtqiga.html

[G04] 定义方法
来源：http://dali.quarkkingdee.top/Article/details/gtwnszosot.html

Py:   def greet(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gtsemtcqtp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gtscliwqan.html

JS:   greet() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtiyvrrgnk.html

TS:   greet(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtwumwizbe.html

Java: String greet() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtccpcibre.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtrhwdculc.html

Ruby: def greet; @name; end
来源：http://dali.quarkkingdee.top/Article/details/gtavexdejk.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtlraqaumc.html

[G05] 继承
来源：http://dali.yvedp.cn/Article/details/gtbmnitihj.html

Py:   class Admin(User): pass
来源：http://dali.hnqzz.top/Article/details/gtoylpgskr.html

PHP:  class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtxlxuovlx.html

JS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtoqgbqeqt.html

TS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtoheguffi.html

Java: class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gtcdryiowk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenlongwang.top/Article/details/gtkrevngyp.html

Ruby: class Admin < User; end
来源：http://dali.ybcxt.top/Article/details/gtwefuhyjn.html

C#:   class Admin : User {}
来源：http://dali.sxryk.cn/Article/details/gthiqtnlqm.html

[G06] 重写方法
来源：http://dali.zhengqikj.top/Article/details/gtbntmgxci.html

Py:   def greet(self): return "admin"
来源：http://dali.jiagoushi.top/Article/details/gtafbbeubn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtodbnzdls.html

JS:   greet() { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtgmztblik.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhoqcbub.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtulshoupl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xinyue.icu/Article/details/gtvdgvhmqq.html

Ruby: def greet; "admin"; end
来源：http://dali.yangfankeji.com/Article/details/gthmvvzkpe.html

C#:   public override string Greet() => "admin";
来源：http://dali.jlsjyb.cn/Article/details/gtglhkzzgl.html

[G07] 调用父类方法
来源：http://dali.zhixingplan.top/Article/details/gtyoywmhdk.html

Py:   super().greet()
来源：http://dali.redwolf501.top/Article/details/gtgacewzod.html

PHP:  parent::greet();
来源：http://dali.chenlongwang.top/Article/details/gtqvbdcfdx.html

JS:   super.greet();
来源：http://dali.redwolf501.top/Article/details/gtpyeeryjj.html

TS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gtxstsncjh.html

Java: super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtrqiattfe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hysaishi.cn/Article/details/gtjbxvpdfx.html

Ruby: super
来源：http://dali.yj20258888.top/Article/details/gtedvxeyse.html

C#:   base.Greet();
来源：http://dali.nwbrower.top/Article/details/gtbeisowjv.html

[G08] 静态方法与属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbnzdqxp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gogol.net.cn/Article/details/gtkqshebby.html

PHP:  public static function f() {}
来源：http://dali.dashuyun.cn/Article/details/gtkwjxsvfg.html

JS:   static f() {}
来源：http://dali.yongpay.top/Article/details/gtosphspoe.html

TS:   static f(): void {}
来源：http://dali.gaohongyu789.top/Article/details/gtbaybhadq.html

Java: static void f() {}
来源：http://dali.jiagoushi.top/Article/details/gtpobrmlxf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.snrcjt.cn/Article/details/gtqvvypfsd.html

Ruby: def self.f; end
来源：http://dali.tanke756.top/Article/details/gtvrpogesg.html

C#:   public static void F() {}
来源：http://dali.jqgfzy.top/Article/details/gtegkxjepi.html

[G09] 接口 / 抽象类
来源：http://dali.vqdsnc.cn/Article/details/gtmvocsovh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.guannengcc.top/Article/details/gtomcuhsct.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yueranfly.top/Article/details/gttkprguad.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tianlin.xyz/Article/details/gtrtaxrxjc.html

TS:   interface Shape { area(): number; }
来源：http://dali.jiagoushi.top/Article/details/gthjbuktcd.html

Java: interface Shape { double area(); }
来源：http://dali.xuanzx.com/Article/details/gtdlhwzsfe.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jlsjyb.cn/Article/details/gtlvaqlexi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hfpthk.cn/Article/details/gtuloaatfv.html

C#:   interface IShape { double Area(); }
来源：http://dali.aibaodan.cn/Article/details/gthbpmevbk.html

[G10] 访问控制
来源：http://dali.aizwys.cn/Article/details/gtmhaszmye.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.pengpengdd.cyou/Article/details/gtogsmqgot.html

PHP:  public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtbcukqucs.html

JS:   #private 字段；其余公开
来源：http://dali.cheryme.top/Article/details/gthhqmvbdo.html

TS:   public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtuawhunay.html

Java: public / protected / private / 默认包级
来源：http://dali.iojbl.cn/Article/details/gtagwijhdm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jyoumei.cn/Article/details/gtwgumgabl.html

Ruby: public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtfqqfyhhu.html

C#:   public / protected / private / internal
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjtjareqt.html

[G11] getter / setter
来源：http://dali.hfpthk.cn/Article/details/gtdbjthavb.html

Py:   @property 与 @x.setter
来源：http://dali.cucudq.cn/Article/details/gtammlmmez.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsakyogiq.html

JS:   get name() { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gtxahdyxgv.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gtfctekvou.html

Java: public String getName() { return name; }
来源：http://dali.fengsongda.top/Article/details/gtykzlqqgy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtaqqmactx.html

Ruby: attr_accessor :name
来源：http://dali.yueranfly.top/Article/details/gtojchrusl.html

C#:   public string Name { get; set; }
来源：http://dali.haohaochexian.top/Article/details/gtdefwfdyn.html

[G12] 对象转字符串
来源：http://dali.sysykeji.top/Article/details/gttmudsdwo.html

Py:   def __str__(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gteaxpgyja.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtrksixdkg.html

JS:   toString() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtipscemcz.html

TS:   toString(): string { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtjigvmgfm.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gtesrbgzsr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gtenwosecl.html

Ruby: def to_s; @name; end
来源：http://dali.316326.xyz/Article/details/gtuclgikzn.html

C#:   public override string ToString() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gtveopypbd.html

[G13] 判断对象类型
来源：http://dali.yanxiufei.cn/Article/details/gtxbzupcel.html

Py:   isinstance(u, User)
来源：http://dali.pycfn.com/Article/details/gtapnncopk.html

PHP:  $u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtfkgotlse.html

JS:   u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtdfqhctzk.html

TS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtcosmyore.html

Java: u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtawipukmh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jlsjyb.cn/Article/details/gtsqbrjwrl.html

Ruby: u.is_a?(User)
来源：http://dali.pengpengdd.cyou/Article/details/gtusuitapq.html

C#:   u is User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqsdwffcn.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwjwcogq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.haohaochexian.top/Article/details/gttpnpeipa.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hfpthk.cn/Article/details/gtmppjmkwc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hammf.cn/Article/details/gtpolvuwmr.html

TS:   type User = { name: string; age: number };
来源：http://dali.hammf.cn/Article/details/gtzhlunzuj.html

Java: record User(String name, int age) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtdbznnjym.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ybcxt.top/Article/details/gtuscujrjb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.feifeiyinyue.top/Article/details/gtazfhroex.html

C#:   record User(string Name, int Age);
来源：http://dali.gaohongyu789.top/Article/details/gthsvshrgz.html

[G15] 枚举
来源：http://dali.yangfankeji.com/Article/details/gtggtmheyj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.vqdsnc.cn/Article/details/gtowlnotxs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tian-w.cn/Article/details/gttbrusjwh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.haohaochexian.top/Article/details/gtijwnqmnt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gtgvcxpwxv.html

Java: enum Color { RED, GREEN }
来源：http://dali.kuanghao11.cn/Article/details/gtnrhwodyn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.snrcjt.cn/Article/details/gtbrtpumyx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.havefunace.top/Article/details/gtyqnvtjtu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gtljragvxj.html

[G16] 对象转数组 / 字典
来源：http://dali.zhongyouzk.top/Article/details/gtgnylkmox.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigufen.top/Article/details/gthhbuaprb.html

PHP:  get_object_vars($obj);
来源：http://dali.snrcjt.cn/Article/details/gtxyskgwdu.html

JS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gtkrwydgoh.html

TS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtmehwjhiq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.birdmap.top/Article/details/gtfacerpgl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nanxinkj.top/Article/details/gtgrhbeypr.html

Ruby: obj.instance_variables
来源：http://dali.xuetiantiany.cn/Article/details/gtlzjfyzji.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gtimkdzuwz.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtlcezlfzo.html

H. 异常与错误处理
来源：http://dali.shangyingyoupin.top/Article/details/gtbovuofaq.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtzqyxumwo.html

[H01] try / catch 基础
来源：http://dali.andypj.xyz/Article/details/gtsfoxdtks.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jlsjyb.cn/Article/details/gteidkcotp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shuidangran.top/Article/details/gtlbxpqhlt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gttbcundgq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gtgrvhrvnu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258.top/Article/details/gtvwbzexci.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.mhx1999.top/Article/details/gtewxcsrtp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghlcxowf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnxiangtu.top/Article/details/gtiffvlnxm.html

[H02] finally / ensure 收尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxgrhgbkb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tianlin.xyz/Article/details/gtwaudgvlx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtadpwwjpu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtwxxulume.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtyftfczyl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtswmyjhgk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shuidangran.top/Article/details/gtsfilqnmy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.pycfn.com/Article/details/gtuaxojnlp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtqlshcmar.html

[H03] 主动抛出异常
来源：http://dali.smart0.xyz/Article/details/gtfcseltpl.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gtihbuvptp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtphmljqwz.html

JS:   throw new Error("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtocodnein.html

TS:   throw new Error("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtbfpimgiq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtbevphldz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jyoumei.cn/Article/details/gttgprripw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.smart0.xyz/Article/details/gtxoadcill.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtjsxgiqso.html

[H04] 自定义异常类型
来源：http://dali.aibaodan.cn/Article/details/gtfwhhsful.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258.top/Article/details/gtoexfpsai.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gtxdnkbasq.html

JS:   class MyError extends Error {}
来源：http://dali.dianchejie.cn/Article/details/gtxojiyroq.html

TS:   class MyError extends Error {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtburcvspj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gtdvcwlzzw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.9152youxi.cn/Article/details/gtfkfgsvru.html

Ruby: class MyError < StandardError; end
来源：http://dali.meibo888.top/Article/details/gtldqksjjo.html

C#:   class MyException : Exception {}
来源：http://dali.jqgufenzy.top/Article/details/gtcxnjkmrd.html

[H05] 捕获特定类型
来源：http://dali.wangshuangyany.cn/Article/details/gtfqrlvkmm.html

Py:   except ValueError as e:
来源：http://dali.sweek.top/Article/details/gtvutxdhou.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gaohongyu789.top/Article/details/gtnwpnvgek.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tanke756.top/Article/details/gtvrnnuwal.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jqgufenzy.top/Article/details/gtfixzwwiv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.9152youxi.cn/Article/details/gthimcvsam.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yangfankeji.com/Article/details/gtzkfavxpi.html

Ruby: rescue ArgumentError => e
来源：http://dali.zdqjudy.top/Article/details/gtmihbdkfc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.andypj.xyz/Article/details/gtpyoqupfm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hongshengwenyu.top/Article/details/gtusiiaepr.html

Py:   value = d.get("k") or default
来源：http://dali.tanke756.top/Article/details/gtezgbpzzh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gtuxeueqgl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gaohongyu789.top/Article/details/gterkgfdkb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gtbweudows.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hywenlv.cn/Article/details/gtklbppbxs.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yvedp.cn/Article/details/gtmacrgmxj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ybcxt.top/Article/details/gtknpqjlsy.html

C#:   obj?.A?.B ?? default
来源：http://dali.daxiang520.top/Article/details/gtvcecxnxa.html

[H07] 断言
来源：http://dali.quarkkingdee.top/Article/details/gtmkwfcpwg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jyoumei.cn/Article/details/gtbnfarshr.html

PHP:  assert($x > 0);
来源：http://dali.ydzc1.top/Article/details/gtoofjmxoc.html

JS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gtdiysciei.html

TS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtbzmaoaxl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xuanzx.com/Article/details/gtszgieknc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nwbrower.top/Article/details/gtosgadely.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pycfn.com/Article/details/gtupszvott.html

C#:   Debug.Assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gtffdqwajo.html

[H08] 获取错误信息与堆栈
来源：http://dali.svipenyu.cn/Article/details/gtxzcnaacv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.c1oappe.top/Article/details/gtvdzokmgl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jiagoushi.top/Article/details/gtaatdilyl.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gtuzcwkwqf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ivvv.top/Article/details/gtksytjerp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnqzz.top/Article/details/gtvyiilduh.html

Go:   err.Error()
来源：http://dali.jianghu66.top/Article/details/gtxrwyoznf.html

Ruby: e.message;  e.backtrace
来源：http://dali.ivvv.top/Article/details/gtgsfcemwk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fengsongda.top/Article/details/gtptjhgzvp.html

[H09] 带错误码的异常
来源：http://dali.mhx1999.top/Article/details/gtzzrvfsri.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guannengcc.top/Article/details/gtidpzwgpn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuxming.cn/Article/details/gthsdwsspt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aizwys.cn/Article/details/gtasihdobt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zdqjudy.top/Article/details/gtcizzvora.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenjidiqi.icu/Article/details/gttojneihs.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jiagoushi.top/Article/details/gtpdgyzaqh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sysykeji.top/Article/details/gtgylneslt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zycfv.cn/Article/details/gtybdhuylk.html

[H10] 资源自动释放
来源：http://dali.birdmap.top/Article/details/gtawhjzfxt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daria6918.cn/Article/details/gtejdkerwx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.vqdsnc.cn/Article/details/gtpvkigutl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yvedp.cn/Article/details/gtxzjnwucv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gtpahgiduh.html


<!-- 参考信息 -->