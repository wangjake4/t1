代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtrwijkcyk.html

[F06] 删除文件
来源：http://dali.haohaochexian.top/Article/details/gtruejjpzx.html

Py:   os.remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtyeqrwqgn.html

PHP:  unlink("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjltmkeg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtiugwfjif.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtboxwfyfb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtwzjifcsq.html

Go:   os.Remove("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtcfoesygq.html

Ruby: File.delete("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtuzjqepkb.html

C#:   File.Delete("a.txt");
来源：http://dali.pycfn.com/Article/details/gtofcehxie.html

[F07] 创建目录（含多级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmnvvlmd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwyrxugxo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.meibo888.top/Article/details/gtsrkscyqv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangtech.top/Article/details/gtzoyayood.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gtorhshnof.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.9152youxi.cn/Article/details/gtbddtdbpm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.9152youxi.cn/Article/details/gtjbwhbjxh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.mhx1999.top/Article/details/gtmopybyon.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgfzy.top/Article/details/gtpwuneapy.html

[F08] 遍历目录
来源：http://dali.smart0.xyz/Article/details/gtzdskzpdq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj20258888.top/Article/details/gtpwwybsmr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhongyouzk.top/Article/details/gtmaqrnxgj.html

JS:   fs.readdirSync("dir")
来源：http://dali.cdnleiting.top/Article/details/gtfdlpznjf.html

TS:   fs.readdirSync("dir")
来源：http://dali.zdqjudy.top/Article/details/gtzyvkxkdu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.feifeiyinyue.top/Article/details/gtyzbnvxoe.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtuqltfyzc.html

Ruby: Dir.children("dir")
来源：http://dali.yuxming.cn/Article/details/gtllcfnztf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhengqikj.top/Article/details/gtedbofsqw.html

[F09] 获取文件大小
来源：http://dali.sweek.top/Article/details/gtlibrigsz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwbcuxdu.html

PHP:  filesize("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtmegahshs.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gthsbxywkv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.0kj1m.cn/Article/details/gtodewtkuu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtsltedtju.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dianchejie.cn/Article/details/gtdlsyurpe.html

Ruby: File.size("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtlnanzzlz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hywenlv.cn/Article/details/gtqummlqfo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.kuanghao11.cn/Article/details/gthtegdmjm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtsldfnins.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.iojbl.cn/Article/details/gtzmzygypv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtkmzyeevl.html

TS:   path.extname("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtwekzjigz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hongshengwenyu.top/Article/details/gtwoaxixct.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtkfeqnxls.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtqwqnbjxw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtxdjjjkiw.html

[F11] 复制与移动文件
来源：http://dali.cashguo.top/Article/details/gttjkesalg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtpnutfcjn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtdxgtovvk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtxaoduevh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtlnddxybq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenzaomai.com/Article/details/gtnhfvykjk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj202588.top/Article/details/gtmvmmrfja.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtfhpfnqib.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.havefunace.top/Article/details/gtkpudiodo.html

[F12] CSV 读写
来源：http://dali.daria6918.cn/Article/details/gtcrsrmrnm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangshuangyany.cn/Article/details/gtyzeyzqpq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hammf.cn/Article/details/gtzdlwyfba.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sweek.top/Article/details/gtnpckeyok.html

TS:   // 同上
来源：http://dali.wangdashe.top/Article/details/gthisetekh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangshuangyany.cn/Article/details/gtcmliptwi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.fzhhl.top/Article/details/gtiwazbfnw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xinyue.icu/Article/details/gtoqhqsmik.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yongpay.top/Article/details/gtqryvkqol.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbijlmckr.html

G. 面向对象
来源：http://dali.jiagoushi.top/Article/details/gtcjjvdtxf.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtdraxwncq.html

[G01] 定义类
来源：http://dali.nwbrower.top/Article/details/gtwjvovwzm.html

Py:   class User: pass
来源：http://dali.jinqigfzy.top/Article/details/gtmysqefby.html

PHP:  class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtkohvxxsf.html

JS:   class User {}
来源：http://dali.yuanzhike.top/Article/details/gtmgmjjant.html

TS:   class User { name: string = ""; }
来源：http://dali.dianchejie.cn/Article/details/gtmgivqoyn.html

Java: class User {}
来源：http://dali.jianghu66.top/Article/details/gtoxiiskra.html

Go:   type User struct { Name string }
来源：http://dali.ehwqpu.com/Article/details/gtzmdczkpc.html

Ruby: class User; end
来源：http://dali.xinyue.icu/Article/details/gtpvtptfac.html

C#:   class User {}
来源：http://dali.sxryk.cn/Article/details/gtbopbbcee.html

[G02] 构造函数
来源：http://dali.kuanghao11.cn/Article/details/gtmlnavrjc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xylfe.cn/Article/details/gttoicwhot.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtcnqiyuwr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gtekovvtus.html

TS:   constructor(public name: string) {}
来源：http://dali.kuanghao11.cn/Article/details/gtbbkjzmfb.html

Java: User(String name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gtvcliexlw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hammf.cn/Article/details/gtgkgngpgg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aizwys.cn/Article/details/gtfmxtslnw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.316326.xyz/Article/details/gtcjjuvqyj.html

[G03] 实例属性
来源：http://dali.vqdsnc.cn/Article/details/gtoboyoiso.html

Py:   self.name = "x"
来源：http://dali.zhengqikj.top/Article/details/gtsctpguml.html

PHP:  public string $name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtaeqireqw.html

JS:   this.name = "x";
来源：http://dali.nanxinkj.top/Article/details/gtntdcspup.html

TS:   name: string = "x";
来源：http://dali.yj202588.top/Article/details/gtzgguxlnp.html

Java: private String name;
来源：http://dali.zhoulong.xyz/Article/details/gtyhhsinun.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jiagoushi.top/Article/details/gtoiodfpge.html

Ruby: @name = "x"
来源：http://dali.redwolf501.top/Article/details/gtnfsjrmbc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.snrcjt.cn/Article/details/gtwhgzesnr.html

[G04] 定义方法
来源：http://dali.ydzc1.top/Article/details/gtbjtvesjn.html

Py:   def greet(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqqatddfg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfllhiuze.html

JS:   greet() { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gtdetqljfz.html

TS:   greet(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gttdopwrnc.html

Java: String greet() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtqarounia.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gtmmzqkiyi.html

Ruby: def greet; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gtafcbgqum.html

C#:   public string Greet() => Name;
来源：http://dali.iojbl.cn/Article/details/gtbsieelhj.html

[G05] 继承
来源：http://dali.chenjidiqi.icu/Article/details/gtruptsmyd.html

Py:   class Admin(User): pass
来源：http://dali.jianghu66.top/Article/details/gtoppkblys.html

PHP:  class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtspdkyrgm.html

JS:   class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtasrwfprq.html

TS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtodmjdoqd.html

Java: class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtinigxthq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sysykeji.top/Article/details/gtpbkicghm.html

Ruby: class Admin < User; end
来源：http://dali.vqdsnc.cn/Article/details/gthmewsweh.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gtwxpuajiu.html

[G06] 重写方法
来源：http://dali.ppjwa.cn/Article/details/gtselbweur.html

Py:   def greet(self): return "admin"
来源：http://dali.wangshuangyany.cn/Article/details/gtyjlzcgzz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtkzytmvmi.html

JS:   greet() { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gthkcgilxy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtiuogksjv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gtxtpurrtn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.dashuyun.cn/Article/details/gtwaiifpzz.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtwsuryolv.html

C#:   public override string Greet() => "admin";
来源：http://dali.jyoumei.cn/Article/details/gtlevwgduj.html

[G07] 调用父类方法
来源：http://dali.nanxuanxn.top/Article/details/gtbrxsaynl.html

Py:   super().greet()
来源：http://dali.yj20258888.top/Article/details/gtbclidwlj.html

PHP:  parent::greet();
来源：http://dali.dashuyun.cn/Article/details/gtmmdtcago.html

JS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gtkopkumxh.html

TS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gtqsmqlwaf.html

Java: super.greet();
来源：http://dali.yangfankeji.com/Article/details/gteuxcbfsn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.snrcjt.cn/Article/details/gtaaphuelf.html

Ruby: super
来源：http://dali.gzhubu.top/Article/details/gtnacdxpgf.html

C#:   base.Greet();
来源：http://dali.tian-w.cn/Article/details/gtzugvciky.html

[G08] 静态方法与属性
来源：http://dali.hywenlv.cn/Article/details/gtistowhov.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhengqikj.top/Article/details/gtyxvdfdkz.html

PHP:  public static function f() {}
来源：http://dali.jiagoushi.top/Article/details/gtaapcwexn.html

JS:   static f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqetrswbe.html

TS:   static f(): void {}
来源：http://dali.chenzaomai.com/Article/details/gttbqnjnhl.html

Java: static void f() {}
来源：http://dali.hfpthk.cn/Article/details/gtbndteaki.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hammf.cn/Article/details/gtfvfrnauw.html

Ruby: def self.f; end
来源：http://dali.guannengcc.top/Article/details/gtdoobpdfl.html

C#:   public static void F() {}
来源：http://dali.sufxvd.cn/Article/details/gtklopsfbw.html

[G09] 接口 / 抽象类
来源：http://dali.ybcxt.top/Article/details/gtrsswachx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinqigufen.top/Article/details/gtjjdkftzb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cdnleiting.top/Article/details/gtprttpsko.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daria6918.cn/Article/details/gttgjpcugt.html

TS:   interface Shape { area(): number; }
来源：http://dali.cheryme.top/Article/details/gtseypmwwc.html

Java: interface Shape { double area(); }
来源：http://dali.mhx1999.top/Article/details/gtsdumzear.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtldfftcln.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yuanzhike.top/Article/details/gtshmrjwum.html

C#:   interface IShape { double Area(); }
来源：http://dali.hysaishi.cn/Article/details/gtiraphfdz.html

[G10] 访问控制
来源：http://dali.yj20258888.top/Article/details/gtjzdkreek.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.meibo888.top/Article/details/gtkzdntxej.html

PHP:  public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtssbyvpzf.html

JS:   #private 字段；其余公开
来源：http://dali.tanke756.top/Article/details/gtdsfrpwmt.html

TS:   public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gtpfxherxv.html

Java: public / protected / private / 默认包级
来源：http://dali.ehwqpu.com/Article/details/gtljhrfagb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sysykeji.top/Article/details/gttnejefuh.html

Ruby: public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtsiymoxbb.html

C#:   public / protected / private / internal
来源：http://dali.tanke756.top/Article/details/gtizdvcspp.html

[G11] getter / setter
来源：http://dali.smart0.xyz/Article/details/gtfteynqxw.html

Py:   @property 与 @x.setter
来源：http://dali.gzhubu.top/Article/details/gtptqimosq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gtbyyhzrjm.html

JS:   get name() { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gtloehemte.html

TS:   get name(): string { return this._name; }
来源：http://dali.svipenyu.cn/Article/details/gtnczbuxri.html

Java: public String getName() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtnjoqmpjw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gtjvtqeqrl.html

Ruby: attr_accessor :name
来源：http://dali.cheryme.top/Article/details/gtjeozexcy.html

C#:   public string Name { get; set; }
来源：http://dali.zycfv.cn/Article/details/gtwnxhebqv.html

[G12] 对象转字符串
来源：http://dali.jinqigfzy.top/Article/details/gttvpnsqfn.html

Py:   def __str__(self): return self.name
来源：http://dali.pengpengdd.cyou/Article/details/gtqycifxvt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gtmknzacch.html

JS:   toString() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtgyqmmlke.html

TS:   toString(): string { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtbnidakkk.html

Java: @Override public String toString() { return name; }
来源：http://dali.ybcxt.top/Article/details/gtlstcfwhi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmttlqksw.html

Ruby: def to_s; @name; end
来源：http://dali.andypj.xyz/Article/details/gtzkhtypxz.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gtvedsypol.html

[G13] 判断对象类型
来源：http://dali.ydzc1.top/Article/details/gtdmpuigcs.html

Py:   isinstance(u, User)
来源：http://dali.daxiang520.top/Article/details/gtqfitlzub.html

PHP:  $u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gterpdxboq.html

JS:   u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gthjedrlkv.html

TS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtjvqbeqlf.html

Java: u instanceof User
来源：http://dali.havefunace.top/Article/details/gtdnnfweqe.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zycfv.cn/Article/details/gtocnhgidw.html

Ruby: u.is_a?(User)
来源：http://dali.yongpay.top/Article/details/gtcmrdnqxr.html

C#:   u is User
来源：http://dali.sweek.top/Article/details/gtxaqagsfv.html

[G14] 数据类 / record
来源：http://dali.xinyue.icu/Article/details/gtkruomgxi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hywenlv.cn/Article/details/gtinwqwlbq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhaomingkeji.xyz/Article/details/gttytkgdyd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ppjwa.cn/Article/details/gtpwhkyztf.html

TS:   type User = { name: string; age: number };
来源：http://dali.yongpay.top/Article/details/gtfordvmkw.html

Java: record User(String name, int age) {}
来源：http://dali.fzhhl.top/Article/details/gtatcfcytj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrifocomd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hfpthk.cn/Article/details/gtkfyhqhpf.html

C#:   record User(string Name, int Age);
来源：http://dali.yonumen.top/Article/details/gtefbiuxmf.html

[G15] 枚举
来源：http://dali.aizwys.cn/Article/details/gtuuqjeozh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenlongwang.top/Article/details/gtrgxtpkla.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jyoumei.cn/Article/details/gtdsrdeiri.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hywenlv.cn/Article/details/gthfiikevf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtyxmqzzmb.html

Java: enum Color { RED, GREEN }
来源：http://dali.zdqjudy.top/Article/details/gtmodpcsvl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhengqikj.top/Article/details/gtgvdnmsgr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuxming.cn/Article/details/gtkdzlnwsb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.c1oappe.top/Article/details/gtzdiilgdr.html

[G16] 对象转数组 / 字典
来源：http://dali.xuanzx.com/Article/details/gtrlmaavby.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shzxlz.cn/Article/details/gtbsqlrisv.html

PHP:  get_object_vars($obj);
来源：http://dali.yonumen.top/Article/details/gtqpbhhnee.html

JS:   Object.entries(obj)
来源：http://dali.zycfv.cn/Article/details/gteaqjwgia.html

TS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gtwanjbzgq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nanxinkj.top/Article/details/gtobhfjkas.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnmvewwuj.html

Ruby: obj.instance_variables
来源：http://dali.gzhubu.top/Article/details/gtijchioia.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.daria6918.cn/Article/details/gtbwqwoull.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtmnbzbahb.html

H. 异常与错误处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtgyerkltt.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtkiyqztiy.html

[H01] try / catch 基础
来源：http://dali.birdmap.top/Article/details/gtzwbiyewk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.316326.xyz/Article/details/gthgjbifww.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxuanxn.top/Article/details/gtdwkdtaix.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gtpdiadpqq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gttckytnvd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.iojbl.cn/Article/details/gtzabtqmrq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxuanxn.top/Article/details/gtkbmmrmej.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xuetiantiany.cn/Article/details/gtlwscjfsr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cdnleiting.top/Article/details/gtxwbswahz.html

[H02] finally / ensure 收尾
来源：http://dali.daria6918.cn/Article/details/gtoieielwk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.redwolf501.top/Article/details/gtsdanrvyj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtemtylpvk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtpybsufpv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtmxeuyrlr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwoeinzbx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj202588.top/Article/details/gtfitybonf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.kuanghao11.cn/Article/details/gtdogvqemz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtzcmepfqn.html

[H03] 主动抛出异常
来源：http://dali.redwolf501.top/Article/details/gtkspjwzpg.html

Py:   raise ValueError("错误信息")
来源：http://dali.svipenyu.cn/Article/details/gtalgdtcys.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gttukdkiva.html

JS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gtigfuuwqa.html

TS:   throw new Error("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtoccsnvym.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtsbniqcea.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.pycfn.com/Article/details/gtvkefhcpv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dianchejie.cn/Article/details/gtetrqlwec.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtwaninezo.html

[H04] 自定义异常类型
来源：http://dali.zhixingplan.top/Article/details/gtbgpdkdaq.html

Py:   class MyError(Exception): pass
来源：http://dali.redwolf501.top/Article/details/gtpwinzhlz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gtcmpcxqqa.html

JS:   class MyError extends Error {}
来源：http://dali.meibo888.top/Article/details/gtxubtarvf.html

TS:   class MyError extends Error {}
来源：http://dali.vqdsnc.cn/Article/details/gtpmyantiz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.feifeiyinyue.top/Article/details/gtatpmxwgx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hysaishi.cn/Article/details/gtmtqmsfyi.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangshuangyany.cn/Article/details/gthsbdbpzo.html

C#:   class MyException : Exception {}
来源：http://dali.svipenyu.cn/Article/details/gteoomigoo.html

[H05] 捕获特定类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwogxpvy.html

Py:   except ValueError as e:
来源：http://dali.svipenyu.cn/Article/details/gtatbkrlcc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hywenlv.cn/Article/details/gtkqshztwv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gtvymkwynk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gtfltzuqbd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.mhx1999.top/Article/details/gtfkijttsl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgfzy.top/Article/details/gtvnmjqhji.html

Ruby: rescue ArgumentError => e
来源：http://dali.redwolf501.top/Article/details/gtsherwrox.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nanxinkj.top/Article/details/gtbegsnyis.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guowangkeji.top/Article/details/gtipptysdj.html

Py:   value = d.get("k") or default
来源：http://dali.ivvv.top/Article/details/gtjwnatrpc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gthrduezmp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.smart0.xyz/Article/details/gtiyvwhnmh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxuanxn.top/Article/details/gtczmywhag.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aizwys.cn/Article/details/gthqwuamej.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.pycfn.com/Article/details/gttylksdvn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hfpthk.cn/Article/details/gtymcukstj.html

C#:   obj?.A?.B ?? default
来源：http://dali.zdqjudy.top/Article/details/gtojxxifre.html

[H07] 断言
来源：http://dali.haohaochexian.top/Article/details/gtxsdnwnfd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.birdmap.top/Article/details/gterzttgtb.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtahrgvfsw.html

JS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gtlkqglxxe.html

TS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtyqvfnwjw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258.top/Article/details/gtrobaawks.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cheryme.top/Article/details/gtszhtdjnu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hfpthk.cn/Article/details/gttsgcutql.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gtxavlgflh.html

[H08] 获取错误信息与堆栈
来源：http://dali.daria6918.cn/Article/details/gtqeqomhed.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gogol.net.cn/Article/details/gtwkxhjgqv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yuxming.cn/Article/details/gtjhahzcgm.html

JS:   e.message;  e.stack
来源：http://dali.jqgfzy.top/Article/details/gtoazyrrbd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yuanzhike.top/Article/details/gtmkeqmauw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.redwolf501.top/Article/details/gtbsjfpgeo.html

Go:   err.Error()
来源：http://dali.dashuyun.cn/Article/details/gtevsqcnnq.html

Ruby: e.message;  e.backtrace
来源：http://dali.cheryme.top/Article/details/gtpgavsout.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jlsjyb.cn/Article/details/gtkjdqgaed.html

[H09] 带错误码的异常
来源：http://dali.pycfn.com/Article/details/gtvclresww.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guannengcc.top/Article/details/gtguzoehze.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yanxiufei.cn/Article/details/gtizbhtkvz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.kuanghao11.cn/Article/details/gtistdguev.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shangyingyoupin.top/Article/details/gtoumjznov.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hongshengwenyu.top/Article/details/gtixcwvhiu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jiagoushi.top/Article/details/gtmugssiqp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.bjfxy.top/Article/details/gtiavixmue.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.haohaochexian.top/Article/details/gtugkywcmi.html

[H10] 资源自动释放
来源：http://dali.jlsjyb.cn/Article/details/gtiqztllui.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgufenzy.top/Article/details/gtcotwrnim.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.fzhhl.top/Article/details/gtdzjtxdgv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shuidangran.top/Article/details/gtxrynxfve.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ydzc1.top/Article/details/gtyaksxkpq.html


<!-- 参考信息 -->