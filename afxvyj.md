代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.smart0.xyz/Article/details/gttoyajtey.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigufen.top/Article/details/gtkersuscv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hfpthk.cn/Article/details/gttphlxtyh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.pycfn.com/Article/details/gtqhtwabbl.html

[F05] 判断文件或目录是否存在
来源：http://dali.yanxiufei.cn/Article/details/gtgogxkpak.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nwbrower.top/Article/details/gtxzgyrwxk.html

PHP:  file_exists("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtolfuagvb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtkfhbgpph.html

TS:   fs.existsSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtdonrdcqx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtobeamszf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ppjwa.cn/Article/details/gttfiizbfw.html

Ruby: File.exist?("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtkglaiwbp.html

C#:   File.Exists("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtlazcxazt.html

[F06] 删除文件
来源：http://dali.nanxuanxn.top/Article/details/gtindhwszs.html

Py:   os.remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gtkyjbynzg.html

PHP:  unlink("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtqakgegmh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtnmqyygfo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtsniecpgl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtfvhuupeo.html

Go:   os.Remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gtmulzxrul.html

Ruby: File.delete("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtevyxgqfq.html

C#:   File.Delete("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtbogxysjc.html

[F07] 创建目录（含多级）
来源：http://dali.sufxvd.cn/Article/details/gtztzdicpu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.wangdashe.top/Article/details/gthmmtrxee.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hnqzz.top/Article/details/gtrusvvafs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gttecghwlg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.smart0.xyz/Article/details/gtdbbmajuo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hammf.cn/Article/details/gtrzobacbd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yvedp.cn/Article/details/gtbzbvlaxf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xziqi.cn/Article/details/gthpnobjrx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ehwqpu.com/Article/details/gthswuqrzu.html

[F08] 遍历目录
来源：http://dali.yangfankeji.com/Article/details/gtbimizzau.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daxiang520.top/Article/details/gtkktfzhiw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gotoacloud.top/Article/details/gtmibmkrdj.html

JS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gtwznvxzln.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtnwzqkvvd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gtkfexrfld.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xuanzx.com/Article/details/gthtcvnvle.html

Ruby: Dir.children("dir")
来源：http://dali.sysykeji.top/Article/details/gtppyyjnun.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ivvv.top/Article/details/gttjtwgizo.html

[F09] 获取文件大小
来源：http://dali.cucudq.cn/Article/details/gtqqkdarus.html

Py:   os.path.getsize("a.txt")
来源：http://dali.316326.xyz/Article/details/gtysghndbg.html

PHP:  filesize("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwplcnzc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gtxngaeyxj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gtjjvwygji.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtbqonmwje.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tian-w.cn/Article/details/gtpzzxdkui.html

Ruby: File.size("a.txt")
来源：http://dali.havefunace.top/Article/details/gtyeynjpef.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtblkcalfq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jiagoushi.top/Article/details/gtrrjnuyql.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtexdlmzwg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtrsbsqswg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtmwvarcje.html

TS:   path.extname("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gteqnpncfw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dianchejie.cn/Article/details/gtbgifnqkj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtaxurvtwg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtkmzibmcq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtkimxsori.html

[F11] 复制与移动文件
来源：http://dali.guowangkeji.top/Article/details/gtjiazbecb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtuekeltri.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.haohaochexian.top/Article/details/gtyugenwmw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtymtyntfx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtzaiuavkn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gttsttezjz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hammf.cn/Article/details/gtzalvzcap.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gthqpczsxr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yonumen.top/Article/details/gttsqkrmin.html

[F12] CSV 读写
来源：http://dali.hywenlv.cn/Article/details/gtidutiuca.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xziqi.cn/Article/details/gthuffnbxe.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nanxinkj.top/Article/details/gteksojhxs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhongyouzk.top/Article/details/gtgxvudjaz.html

TS:   // 同上
来源：http://dali.tanke756.top/Article/details/gtulwcooqe.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjpjfmzdz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuanzhike.top/Article/details/gtnejdnjzo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jyoumei.cn/Article/details/gtchwaubic.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zdqjudy.top/Article/details/gtrqrrhbix.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtaafjcabg.html

G. 面向对象
来源：http://dali.316326.xyz/Article/details/gtgbdgkwvx.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtlssdtmny.html

[G01] 定义类
来源：http://dali.dashuyun.cn/Article/details/gtousshmoq.html

Py:   class User: pass
来源：http://dali.jinqigfzy.top/Article/details/gtzzpztaqj.html

PHP:  class User {}
来源：http://dali.aizwys.cn/Article/details/gtsuwkfbkm.html

JS:   class User {}
来源：http://dali.wangdashe.top/Article/details/gtpgiodyxf.html

TS:   class User { name: string = ""; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvscujqei.html

Java: class User {}
来源：http://dali.jqgfzy.top/Article/details/gtnaulvrpg.html

Go:   type User struct { Name string }
来源：http://dali.meibo888.top/Article/details/gtjvyximpk.html

Ruby: class User; end
来源：http://dali.sweek.top/Article/details/gtuwygmizt.html

C#:   class User {}
来源：http://dali.mhx1999.top/Article/details/gtrjturiqm.html

[G02] 构造函数
来源：http://dali.daria6918.cn/Article/details/gtcpieimon.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tianlin.xyz/Article/details/gtjisohzap.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.0kj1m.cn/Article/details/gtoaxzzjia.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nanxinkj.top/Article/details/gtqtznrsbb.html

TS:   constructor(public name: string) {}
来源：http://dali.yj202588.top/Article/details/gtejszgjgn.html

Java: User(String name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gtkbjqqivd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yanxiufei.cn/Article/details/gtubmazgee.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fzhhl.top/Article/details/gtnvsofihw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sxryk.cn/Article/details/gtreunujlj.html

[G03] 实例属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvoddowjq.html

Py:   self.name = "x"
来源：http://dali.daxiang520.top/Article/details/gtdgnknpez.html

PHP:  public string $name = "x";
来源：http://dali.zdqjudy.top/Article/details/gtdxftxjgb.html

JS:   this.name = "x";
来源：http://dali.ehwqpu.com/Article/details/gtewvqipcc.html

TS:   name: string = "x";
来源：http://dali.nwbrower.top/Article/details/gtqxzdudos.html

Java: private String name;
来源：http://dali.tianlin.xyz/Article/details/gtxcsmmzsb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gttawkmqga.html

Ruby: @name = "x"
来源：http://dali.nwbrower.top/Article/details/gtafgwgujk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zycfv.cn/Article/details/gtdnoewytn.html

[G04] 定义方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtriuwbvsf.html

Py:   def greet(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gtamcfloui.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gtrogaeskx.html

JS:   greet() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtwgnykhxd.html

TS:   greet(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtykbrxyyk.html

Java: String greet() { return name; }
来源：http://dali.fengsongda.top/Article/details/gtznowldhh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gtbrlbltjn.html

Ruby: def greet; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbkroozb.html

C#:   public string Greet() => Name;
来源：http://dali.pycfn.com/Article/details/gtvtznppkn.html

[G05] 继承
来源：http://dali.shuidangran.top/Article/details/gtauuxczop.html

Py:   class Admin(User): pass
来源：http://dali.tian-w.cn/Article/details/gtewugpjuw.html

PHP:  class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtdkdulgox.html

JS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtcgimwown.html

TS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtwowzceil.html

Java: class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtibeounop.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuetiantiany.cn/Article/details/gtjzmjvpos.html

Ruby: class Admin < User; end
来源：http://dali.c1oappe.top/Article/details/gtlovndtyu.html

C#:   class Admin : User {}
来源：http://dali.zhixingplan.top/Article/details/gtsguyxmgt.html

[G06] 重写方法
来源：http://dali.cashguo.top/Article/details/gtfswfvjjg.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigufen.top/Article/details/gtfjzljqjb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtcsujctrz.html

JS:   greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtaxrmvrto.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtqlhmbale.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtsyycwakv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhongyouzk.top/Article/details/gtdxcvovxy.html

Ruby: def greet; "admin"; end
来源：http://dali.tian-w.cn/Article/details/gtiedtkpwz.html

C#:   public override string Greet() => "admin";
来源：http://dali.ehwqpu.com/Article/details/gtjqqowqqt.html

[G07] 调用父类方法
来源：http://dali.bjfxy.top/Article/details/gtlktfzvav.html

Py:   super().greet()
来源：http://dali.c1oappe.top/Article/details/gtmabtbrsy.html

PHP:  parent::greet();
来源：http://dali.sufxvd.cn/Article/details/gtxpfgrvyw.html

JS:   super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtmhgabjaa.html

TS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gtbzxipnva.html

Java: super.greet();
来源：http://dali.ivvv.top/Article/details/gtfcevhihv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.guannengcc.top/Article/details/gtentkzgys.html

Ruby: super
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqjsnkqy.html

C#:   base.Greet();
来源：http://dali.zhengqikj.top/Article/details/gttkhmgdjt.html

[G08] 静态方法与属性
来源：http://dali.yvedp.cn/Article/details/gthnxuwdfi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yueranfly.top/Article/details/gtaxaoxpfo.html

PHP:  public static function f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtemslxdvm.html

JS:   static f() {}
来源：http://dali.cheryme.top/Article/details/gtsioznkor.html

TS:   static f(): void {}
来源：http://dali.316326.xyz/Article/details/gtnkeaksrd.html

Java: static void f() {}
来源：http://dali.redwolf501.top/Article/details/gtnqsuvcvb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zycfv.cn/Article/details/gtuvqbyflj.html

Ruby: def self.f; end
来源：http://dali.yuxming.cn/Article/details/gtleyqciio.html

C#:   public static void F() {}
来源：http://dali.jlsjyb.cn/Article/details/gtyypbfktr.html

[G09] 接口 / 抽象类
来源：http://dali.hywenlv.cn/Article/details/gtwkeqouyj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj202588.top/Article/details/gtfyhxfhpf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yongpay.top/Article/details/gtjydemmhw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.wangshuangyany.cn/Article/details/gthesflfbv.html

TS:   interface Shape { area(): number; }
来源：http://dali.xuanzx.com/Article/details/gtyoznczgo.html

Java: interface Shape { double area(); }
来源：http://dali.hammf.cn/Article/details/gtvktakyjt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sweek.top/Article/details/gtnhttsmhw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cheryme.top/Article/details/gtlimgwzjy.html

C#:   interface IShape { double Area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtdrfqftld.html

[G10] 访问控制
来源：http://dali.yuxming.cn/Article/details/gtanhkquri.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.haohaochexian.top/Article/details/gtrdvhecez.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gtbchhilzt.html

JS:   #private 字段；其余公开
来源：http://dali.tian-w.cn/Article/details/gtynfjhcam.html

TS:   public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqsgmskpr.html

Java: public / protected / private / 默认包级
来源：http://dali.yvedp.cn/Article/details/gthcybxsbt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.dianchejie.cn/Article/details/gttafndlhf.html

Ruby: public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gtpgoounig.html

C#:   public / protected / private / internal
来源：http://dali.jqgfzy.top/Article/details/gtxtjyytjc.html

[G11] getter / setter
来源：http://dali.hnqzz.top/Article/details/gthhriztfx.html

Py:   @property 与 @x.setter
来源：http://dali.shangyingyoupin.top/Article/details/gtrjcilhws.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtdchxrmlg.html

JS:   get name() { return this._name; }
来源：http://dali.shzxlz.cn/Article/details/gtqocgtxhq.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtstmldota.html

Java: public String getName() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtcarjoizh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtpbwmcupz.html

Ruby: attr_accessor :name
来源：http://dali.hammf.cn/Article/details/gtiwvsxazn.html

C#:   public string Name { get; set; }
来源：http://dali.jinqigufen.top/Article/details/gtsegdkitg.html

[G12] 对象转字符串
来源：http://dali.gogol.net.cn/Article/details/gtncwgnbcs.html

Py:   def __str__(self): return self.name
来源：http://dali.sweek.top/Article/details/gtmpyqttrs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gteehhirtc.html

JS:   toString() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtllsqecyf.html

TS:   toString(): string { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtroyklkjw.html

Java: @Override public String toString() { return name; }
来源：http://dali.smart0.xyz/Article/details/gtghxzjnky.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gtdprczhyw.html

Ruby: def to_s; @name; end
来源：http://dali.hysaishi.cn/Article/details/gtmfxxfjnj.html

C#:   public override string ToString() => Name;
来源：http://dali.iojbl.cn/Article/details/gtkvqhzihs.html

[G13] 判断对象类型
来源：http://dali.yangfankeji.com/Article/details/gtpllweoux.html

Py:   isinstance(u, User)
来源：http://dali.fengsongda.top/Article/details/gtqbujqtxj.html

PHP:  $u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtlzhdhmsd.html

JS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtmcuoabwu.html

TS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcfyypdq.html

Java: u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtlqoljxdp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aibaodan.cn/Article/details/gtbkzliflq.html

Ruby: u.is_a?(User)
来源：http://dali.c1oappe.top/Article/details/gtzczybyek.html

C#:   u is User
来源：http://dali.tanke756.top/Article/details/gtowglfbtl.html

[G14] 数据类 / record
来源：http://dali.cashguo.top/Article/details/gtxpxqdgkh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxinkj.top/Article/details/gtvcmqdlfw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxuanxn.top/Article/details/gtrjwkvyhp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daria6918.cn/Article/details/gtxghjeixq.html

TS:   type User = { name: string; age: number };
来源：http://dali.hnxiangtu.top/Article/details/gtlprbwwqi.html

Java: record User(String name, int age) {}
来源：http://dali.gogol.net.cn/Article/details/gtvtxcbqob.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aibaodan.cn/Article/details/gteoedajsj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shuidangran.top/Article/details/gtxksxhvch.html

C#:   record User(string Name, int Age);
来源：http://dali.daxiang520.top/Article/details/gtoljxbyaj.html

[G15] 枚举
来源：http://dali.chenlongwang.top/Article/details/gtexdlftas.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.birdmap.top/Article/details/gtgwcbwmnv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ivvv.top/Article/details/gtgyvjemmb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258.top/Article/details/gtmhmvtwuo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gtjmgbummt.html

Java: enum Color { RED, GREEN }
来源：http://dali.jiagoushi.top/Article/details/gtfaoamdfu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.havefunace.top/Article/details/gtsvddaesp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xinyue.icu/Article/details/gtbulechts.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yueranfly.top/Article/details/gtsflkkocp.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsoxiahh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fzhhl.top/Article/details/gtuooyciza.html

PHP:  get_object_vars($obj);
来源：http://dali.xylfe.cn/Article/details/gtwsvrvebk.html

JS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gtlxhgdpdy.html

TS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gturtqetxi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gogol.net.cn/Article/details/gtmmcqusih.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.bjfxy.top/Article/details/gtobvpiqdm.html

Ruby: obj.instance_variables
来源：http://dali.jiagoushi.top/Article/details/gtvopcnnzf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gotoacloud.top/Article/details/gtnhlboxbx.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtghfbnkhl.html

H. 异常与错误处理
来源：http://dali.9152youxi.cn/Article/details/gtugggxyel.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtwflmvwbs.html

[H01] try / catch 基础
来源：http://dali.guowangkeji.top/Article/details/gttvwauskz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xuanzx.com/Article/details/gtkodpxqif.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.316326.xyz/Article/details/gtfnivfmuf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gtroonwopc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gtkqaanymt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nanxinkj.top/Article/details/gteqpwrdeq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangdashe.top/Article/details/gtjhqrnhjg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cheryme.top/Article/details/gtizxnqckc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.dashuyun.cn/Article/details/gtkrxiymbf.html

[H02] finally / ensure 收尾
来源：http://dali.316326.xyz/Article/details/gtqdcbmmlf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.daria6918.cn/Article/details/gtbscbwhce.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtfyvqxjhf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtyfxccegc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gttvaaawxj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtftookcjz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ydzc1.top/Article/details/gtdlqahdzt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhwdfofv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtdbglzlzo.html

[H03] 主动抛出异常
来源：http://dali.wangdashe.top/Article/details/gtpqggjaxv.html

Py:   raise ValueError("错误信息")
来源：http://dali.havefunace.top/Article/details/gtvhskbuwh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtpwjyxsif.html

JS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtzmgwcork.html

TS:   throw new Error("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtamewzjan.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtswyatmjw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuanzx.com/Article/details/gttdhfftth.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfulmbbf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gtxzgnvkmn.html

[H04] 自定义异常类型
来源：http://dali.cashguo.top/Article/details/gtayootxkq.html

Py:   class MyError(Exception): pass
来源：http://dali.hfpthk.cn/Article/details/gtvjupkmwg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gttrjqxwtj.html

JS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gtqraugstt.html

TS:   class MyError extends Error {}
来源：http://dali.dashuyun.cn/Article/details/gtjijldtkg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gtegwinflb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhengqikj.top/Article/details/gtdskxfpie.html

Ruby: class MyError < StandardError; end
来源：http://dali.bjfxy.top/Article/details/gtxgxhogua.html

C#:   class MyException : Exception {}
来源：http://dali.fzhhl.top/Article/details/gtjbigrwoy.html

[H05] 捕获特定类型
来源：http://dali.wangshuangyany.cn/Article/details/gtbrjsqldf.html

Py:   except ValueError as e:
来源：http://dali.chenjidiqi.icu/Article/details/gttykmgxvj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cucudq.cn/Article/details/gtplsegufe.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxuudzhyi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gtetgdwnfq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shuidangran.top/Article/details/gtphzuryts.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigufen.top/Article/details/gtyjnjsjwr.html

Ruby: rescue ArgumentError => e
来源：http://dali.dashuyun.cn/Article/details/gtvlyhkfbi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sxryk.cn/Article/details/gtyileutjs.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgufenzy.top/Article/details/gtdrkhunht.html

Py:   value = d.get("k") or default
来源：http://dali.hongshengwenyu.top/Article/details/gtaagiahlc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yonumen.top/Article/details/gtoahhzzmk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gtjlpajadc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xziqi.cn/Article/details/gtugpfblot.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gtjxldnmpj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgufenzy.top/Article/details/gtlnuwkwff.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guannengcc.top/Article/details/gtmozrscxj.html

C#:   obj?.A?.B ?? default
来源：http://dali.yangfankeji.com/Article/details/gtbkxfnqci.html

[H07] 断言
来源：http://dali.meibo888.top/Article/details/gtmluphmij.html

Py:   assert x > 0, "必须为正"
来源：http://dali.c1oappe.top/Article/details/gtrmpuigxr.html

PHP:  assert($x > 0);
来源：http://dali.yuxming.cn/Article/details/gttveyyfod.html

JS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtcbvvueoz.html

TS:   console.assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gtrxshduyy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.pengpengdd.cyou/Article/details/gtiubxwcgs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangshuangyany.cn/Article/details/gtziwcofkd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cdnleiting.top/Article/details/gtsuuyzlrq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gtgnjxijfr.html

[H08] 获取错误信息与堆栈
来源：http://dali.quarkkingdee.top/Article/details/gtorbswlzs.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hysaishi.cn/Article/details/gtzelofytv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cqqwz.cn/Article/details/gtqoqbbzku.html

JS:   e.message;  e.stack
来源：http://dali.gzhubu.top/Article/details/gtrmhfftwj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.guannengcc.top/Article/details/gtejrkgivi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tianlin.xyz/Article/details/gtzamqtvhw.html

Go:   err.Error()
来源：http://dali.0kj1m.cn/Article/details/gtwyqdguig.html

Ruby: e.message;  e.backtrace
来源：http://dali.cdnleiting.top/Article/details/gtayrhqyvj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cucudq.cn/Article/details/gtueqrceyy.html

[H09] 带错误码的异常
来源：http://dali.bjfxy.top/Article/details/gtxehvkune.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangtech.top/Article/details/gtcnxxxlqd.html


<!-- 参考信息 -->