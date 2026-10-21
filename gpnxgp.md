代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gttvafksug.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtsuwwtcev.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtdumyskvw.html

Go:   os.Remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpenubnf.html

Ruby: File.delete("a.txt")
来源：http://dali.tanke756.top/Article/details/gtljwatroe.html

C#:   File.Delete("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwtnthnym.html

[F07] 创建目录（含多级）
来源：http://dali.daxiang520.top/Article/details/gtirzmczgl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gogol.net.cn/Article/details/gtnlmceifg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxuanxn.top/Article/details/gtjdwdglza.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gtfxrpyeoy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gotoacloud.top/Article/details/gtbfkbrsel.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pengpengdd.cyou/Article/details/gtijolzdyz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jlsjyb.cn/Article/details/gtxccouakl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gotoacloud.top/Article/details/gtdqtcthru.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.meibo888.top/Article/details/gtpvllilya.html

[F08] 遍历目录
来源：http://dali.jqgfzy.top/Article/details/gtbykknrhd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jlsjyb.cn/Article/details/gtdnukieen.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.daxiang520.top/Article/details/gttkhtpfdn.html

JS:   fs.readdirSync("dir")
来源：http://dali.yuanzhike.top/Article/details/gtliuuwgwq.html

TS:   fs.readdirSync("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtrkjbxaxg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sweek.top/Article/details/gtontwttsi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtaszrzeqw.html

Ruby: Dir.children("dir")
来源：http://dali.snrcjt.cn/Article/details/gtbgjqrckl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cucudq.cn/Article/details/gtkrpiuipx.html

[F09] 获取文件大小
来源：http://dali.gaohongyu789.top/Article/details/gtajydpklh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtovajwqie.html

PHP:  filesize("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtmyzohyuh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gtsynfrbqn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zdqjudy.top/Article/details/gtyiaudgml.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtbnceukgb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.aizwys.cn/Article/details/gtaibyqoml.html

Ruby: File.size("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtrcgxpxyl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenlongwang.top/Article/details/gttzwaysrm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hywenlv.cn/Article/details/gtbfhhzkel.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtupfgnkcm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtmjifbltp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtizopxcmo.html

TS:   path.extname("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtqiqmzqri.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenjidiqi.icu/Article/details/gtidsmobht.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtchmycfgv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtjibgozhq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gttweicxqa.html

[F11] 复制与移动文件
来源：http://dali.hammf.cn/Article/details/gtzliynqva.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtazyvgski.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daria6918.cn/Article/details/gtgeriaurf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gttnfjjdfw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gturlojtgr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.c1oappe.top/Article/details/gtmhbgngth.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tianlin.xyz/Article/details/gtzuhbghps.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtqbgmglex.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yanxiufei.cn/Article/details/gtqlmpkepg.html

[F12] CSV 读写
来源：http://dali.jinqigufen.top/Article/details/gtfdggulpd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sysykeji.top/Article/details/gtqxpgzvop.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jqgufenzy.top/Article/details/gtnxmfxgsz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cucudq.cn/Article/details/gtlwxnvtxv.html

TS:   // 同上
来源：http://dali.nanxinkj.top/Article/details/gtoskpzwlc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.0kj1m.cn/Article/details/gtxnzszuhh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgufenzy.top/Article/details/gtnjwzqgfp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xziqi.cn/Article/details/gtknqtghfv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gtsbiiiasi.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtiwuypemo.html

G. 面向对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzxgcxvif.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtrxyabfkm.html

[G01] 定义类
来源：http://dali.zhiwuduotai.top/Article/details/gtgpivsfeo.html

Py:   class User: pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gtngneezxw.html

PHP:  class User {}
来源：http://dali.fengsongda.top/Article/details/gthgjanwas.html

JS:   class User {}
来源：http://dali.316326.xyz/Article/details/gttwlibjty.html

TS:   class User { name: string = ""; }
来源：http://dali.aibaodan.cn/Article/details/gthsnedmcy.html

Java: class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtgajmkelb.html

Go:   type User struct { Name string }
来源：http://dali.gaohongyu789.top/Article/details/gtzwmhpray.html

Ruby: class User; end
来源：http://dali.jinghuilouyu.cn/Article/details/gteapqwkso.html

C#:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gtmihxdvtr.html

[G02] 构造函数
来源：http://dali.daxiang520.top/Article/details/gtbawwcvdq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenlongwang.top/Article/details/gttrhuqart.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtgvimtmbu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gtsnmmwiiw.html

TS:   constructor(public name: string) {}
来源：http://dali.0kj1m.cn/Article/details/gtnqbgeshl.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtnqaqwvif.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.haohaochexian.top/Article/details/gthzgkcuch.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtysozmjgg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cdnleiting.top/Article/details/gtujalggog.html

[G03] 实例属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbpofopw.html

Py:   self.name = "x"
来源：http://dali.snrcjt.cn/Article/details/gtvkgpoipq.html

PHP:  public string $name = "x";
来源：http://dali.xinyue.icu/Article/details/gtnczanimw.html

JS:   this.name = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwxdyvix.html

TS:   name: string = "x";
来源：http://dali.tian-w.cn/Article/details/gtpuignfvn.html

Java: private String name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgfwlkfk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.snrcjt.cn/Article/details/gthmmlhhhx.html

Ruby: @name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gtumabqsiv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.iojbl.cn/Article/details/gtcmrrelyb.html

[G04] 定义方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrnxgopvy.html

Py:   def greet(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gtcxevqmmd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gteqghsehk.html

JS:   greet() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtpqipbfnu.html

TS:   greet(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtkfvllrtm.html

Java: String greet() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtwnfurlir.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtabcarjxg.html

Ruby: def greet; @name; end
来源：http://dali.tianlin.xyz/Article/details/gttayydmyc.html

C#:   public string Greet() => Name;
来源：http://dali.fengsongda.top/Article/details/gtestwejqb.html

[G05] 继承
来源：http://dali.redwolf501.top/Article/details/gtxcfijhcd.html

Py:   class Admin(User): pass
来源：http://dali.wangshuangyany.cn/Article/details/gtjyoruimh.html

PHP:  class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtcgkbvxnf.html

JS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtymdksecg.html

TS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgkeqcdsg.html

Java: class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtswflxzkg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.daria6918.cn/Article/details/gtkeyhwmle.html

Ruby: class Admin < User; end
来源：http://dali.pycfn.com/Article/details/gtyrzuknhq.html

C#:   class Admin : User {}
来源：http://dali.mhx1999.top/Article/details/gtbslnzvwg.html

[G06] 重写方法
来源：http://dali.yonumen.top/Article/details/gtutbelpea.html

Py:   def greet(self): return "admin"
来源：http://dali.yangfankeji.com/Article/details/gtshcwabbt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtrazpijav.html

JS:   greet() { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtfmpphjmo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtybtnlkhy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsolowrss.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guowangkeji.top/Article/details/gtvejalafw.html

Ruby: def greet; "admin"; end
来源：http://dali.aibaodan.cn/Article/details/gtgwawxjfb.html

C#:   public override string Greet() => "admin";
来源：http://dali.shangyingyoupin.top/Article/details/gtmuqxpxdt.html

[G07] 调用父类方法
来源：http://dali.zhoulong.xyz/Article/details/gtvmqotdje.html

Py:   super().greet()
来源：http://dali.pengpengdd.cyou/Article/details/gtkidmupya.html

PHP:  parent::greet();
来源：http://dali.jinqigufen.top/Article/details/gtoixnuiex.html

JS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtxmjacykp.html

TS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gtszivqovi.html

Java: super.greet();
来源：http://dali.cqqwz.cn/Article/details/gtshyhbtgt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cheryme.top/Article/details/gthsanbhaj.html

Ruby: super
来源：http://dali.xziqi.cn/Article/details/gtplhcuzfp.html

C#:   base.Greet();
来源：http://dali.gzhubu.top/Article/details/gtxhhugxiq.html

[G08] 静态方法与属性
来源：http://dali.chenzaomai.com/Article/details/gtkyljphjo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nanxinkj.top/Article/details/gtpozbxzop.html

PHP:  public static function f() {}
来源：http://dali.sysykeji.top/Article/details/gtrliizxnr.html

JS:   static f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfxegfic.html

TS:   static f(): void {}
来源：http://dali.fengsongda.top/Article/details/gttwegkrda.html

Java: static void f() {}
来源：http://dali.sysykeji.top/Article/details/gtcaxpkepe.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.haohaochexian.top/Article/details/gtlxvgwjxp.html

Ruby: def self.f; end
来源：http://dali.wangshuangyany.cn/Article/details/gtiogeqmut.html

C#:   public static void F() {}
来源：http://dali.zhongyouzk.top/Article/details/gtwrtvqcsl.html

[G09] 接口 / 抽象类
来源：http://dali.yuxming.cn/Article/details/gtsciwcluc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.iojbl.cn/Article/details/gtzsnftdgq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuetiantiany.cn/Article/details/gttkruxxsi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daxiang520.top/Article/details/gttnnncyuc.html

TS:   interface Shape { area(): number; }
来源：http://dali.shangyingyoupin.top/Article/details/gtdpamzubm.html

Java: interface Shape { double area(); }
来源：http://dali.chenlongwang.top/Article/details/gtgwfeqdht.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cashguo.top/Article/details/gtfhhthoic.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdfttrhe.html

C#:   interface IShape { double Area(); }
来源：http://dali.yuxming.cn/Article/details/gtiamshmhi.html

[G10] 访问控制
来源：http://dali.sufxvd.cn/Article/details/gtsvpubwhs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.pycfn.com/Article/details/gtjebcwvhe.html

PHP:  public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gtlhfknraj.html

JS:   #private 字段；其余公开
来源：http://dali.gzhubu.top/Article/details/gtrrmascwt.html

TS:   public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnuxbycpu.html

Java: public / protected / private / 默认包级
来源：http://dali.tian-w.cn/Article/details/gttxqoslbv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zdqjudy.top/Article/details/gtroatiokm.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtarzdiwry.html

C#:   public / protected / private / internal
来源：http://dali.sufxvd.cn/Article/details/gtwqskyhxg.html

[G11] getter / setter
来源：http://dali.0kj1m.cn/Article/details/gtjayuvyzn.html

Py:   @property 与 @x.setter
来源：http://dali.c1oappe.top/Article/details/gtufxdtsbq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gtrzbjxxfl.html

JS:   get name() { return this._name; }
来源：http://dali.daria6918.cn/Article/details/gtljldrrpq.html

TS:   get name(): string { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gtexqfvgep.html

Java: public String getName() { return name; }
来源：http://dali.gzhubu.top/Article/details/gteydhezvv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gthmxklmvs.html

Ruby: attr_accessor :name
来源：http://dali.wangshuangyany.cn/Article/details/gtsjqbjipu.html

C#:   public string Name { get; set; }
来源：http://dali.hongshengwenyu.top/Article/details/gttbuljrga.html

[G12] 对象转字符串
来源：http://dali.jiagoushi.top/Article/details/gtvtmpaslw.html

Py:   def __str__(self): return self.name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfxwdcjpq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtctnkqpgz.html

JS:   toString() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtbwiibmgp.html

TS:   toString(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtnhcjdtdv.html

Java: @Override public String toString() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtjwzgtajo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtjdvimyff.html

Ruby: def to_s; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gtyyswjwqa.html

C#:   public override string ToString() => Name;
来源：http://dali.yueranfly.top/Article/details/gtuiuqiots.html

[G13] 判断对象类型
来源：http://dali.nanxinkj.top/Article/details/gtzhallllb.html

Py:   isinstance(u, User)
来源：http://dali.bjfxy.top/Article/details/gtoyfrnsoz.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtvpkbhfto.html

JS:   u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtoatfzhnj.html

TS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtkpfcvxcb.html

Java: u instanceof User
来源：http://dali.xylfe.cn/Article/details/gteyiadqec.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yanxiufei.cn/Article/details/gtlalzvgbu.html

Ruby: u.is_a?(User)
来源：http://dali.tian-w.cn/Article/details/gtthfvawwj.html

C#:   u is User
来源：http://dali.wangshuangyany.cn/Article/details/gtuiugeirg.html

[G14] 数据类 / record
来源：http://dali.jlsjyb.cn/Article/details/gthreownsw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xziqi.cn/Article/details/gtowdswrni.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hammf.cn/Article/details/gtlbsprtss.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xinyue.icu/Article/details/gtdvjhksrd.html

TS:   type User = { name: string; age: number };
来源：http://dali.nanxinkj.top/Article/details/gtfwpudmql.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtetwvtfwy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.havefunace.top/Article/details/gtbybkrxkf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.wangdashe.top/Article/details/gtntlyekgr.html

C#:   record User(string Name, int Age);
来源：http://dali.jianghu66.top/Article/details/gtasuwqbop.html

[G15] 枚举
来源：http://dali.ehwqpu.com/Article/details/gtndxmkfun.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.aibaodan.cn/Article/details/gtxfxpsrfk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ppjwa.cn/Article/details/gtzvzsynzb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gogol.net.cn/Article/details/gtdlrftknu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtbbkgwiqd.html

Java: enum Color { RED, GREEN }
来源：http://dali.daria6918.cn/Article/details/gtusrurlfz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ivvv.top/Article/details/gtcpjlupev.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gaohongyu789.top/Article/details/gtsqyxxtsf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ehwqpu.com/Article/details/gtjqejjkfl.html

[G16] 对象转数组 / 字典
来源：http://dali.cdnleiting.top/Article/details/gtaaycsokp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenzaomai.com/Article/details/gtpnunnmls.html

PHP:  get_object_vars($obj);
来源：http://dali.xziqi.cn/Article/details/gtxbedoxcd.html

JS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gtyxwxltmd.html

TS:   Object.entries(obj)
来源：http://dali.aizwys.cn/Article/details/gtojagqrpa.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dashuyun.cn/Article/details/gtssinmavn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guannengcc.top/Article/details/gtzltwifok.html

Ruby: obj.instance_variables
来源：http://dali.gzhubu.top/Article/details/gtxsvqcisg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gtbjaegkhl.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtyxgxhlur.html

H. 异常与错误处理
来源：http://dali.hfpthk.cn/Article/details/gtlghvazgq.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtdsjgedit.html

[H01] try / catch 基础
来源：http://dali.pycfn.com/Article/details/gtiofifvqs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jiagoushi.top/Article/details/gtzolczxip.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sweek.top/Article/details/gtdmaoucyq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gttsomtciv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gtzakadzwa.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuzacudew.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.quarkkingdee.top/Article/details/gtxvrzsxem.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gogol.net.cn/Article/details/gtknysboej.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.meibo888.top/Article/details/gtmgrhoclq.html

[H02] finally / ensure 收尾
来源：http://dali.yueranfly.top/Article/details/gtzhvkrtnp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sweek.top/Article/details/gttkzocgqa.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtixxwzkfw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtowlokrso.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtolfkgczs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtqjhzshly.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yongpay.top/Article/details/gtwacubbkq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gogol.net.cn/Article/details/gtsivolswf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtlocxqrqj.html

[H03] 主动抛出异常
来源：http://dali.hnxiangtu.top/Article/details/gtzfdudkli.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenjidiqi.icu/Article/details/gtppapjzdv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtuhyrodxl.html

JS:   throw new Error("错误信息");
来源：http://dali.yongpay.top/Article/details/gtknopsika.html

TS:   throw new Error("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtgceuuoug.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gthlmwaoan.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxuanxn.top/Article/details/gthdqtspay.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.316326.xyz/Article/details/gtyuysqvaw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtisfdofbf.html

[H04] 自定义异常类型
来源：http://dali.guannengcc.top/Article/details/gtrbajkstl.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258.top/Article/details/gtsenromfv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gtwtnjyrqi.html

JS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gtcexukifm.html

TS:   class MyError extends Error {}
来源：http://dali.hysaishi.cn/Article/details/gttfzmxskz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gtpoummcnl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guowangkeji.top/Article/details/gtwecbciey.html

Ruby: class MyError < StandardError; end
来源：http://dali.sxryk.cn/Article/details/gtaaovumdk.html

C#:   class MyException : Exception {}
来源：http://dali.tian-w.cn/Article/details/gtrmiattxv.html

[H05] 捕获特定类型
来源：http://dali.hfpthk.cn/Article/details/gtgwzegwyj.html

Py:   except ValueError as e:
来源：http://dali.jyoumei.cn/Article/details/gtgfcrrqzi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.kuanghao11.cn/Article/details/gtgktkgvpq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuanzhike.top/Article/details/gtrijszoxf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gtshixlpvf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnqzz.top/Article/details/gtvzxpruyg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.quarkkingdee.top/Article/details/gtzuszhpzo.html

Ruby: rescue ArgumentError => e
来源：http://dali.zdqjudy.top/Article/details/gtleuqmfhk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tian-w.cn/Article/details/gtmwsckdha.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yanxiufei.cn/Article/details/gtgcfteqdm.html

Py:   value = d.get("k") or default
来源：http://dali.meibo888.top/Article/details/gtcgyebfnc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gtxlfzcqvn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gtkiafevmu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sysykeji.top/Article/details/gtmmdnqeyp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shzxlz.cn/Article/details/gtmyggnfkp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.9152youxi.cn/Article/details/gtacluonbd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyxggdbzw.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigfzy.top/Article/details/gtcruqwvaa.html

[H07] 断言
来源：http://dali.hywenlv.cn/Article/details/gtnczinptn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.pengpengdd.cyou/Article/details/gtiufpshpd.html

PHP:  assert($x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtwmvgpvjz.html

JS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtlsdxhrnp.html

TS:   console.assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtvzrfhsot.html

Java: assert x > 0 : "必须为正";
来源：http://dali.c1oappe.top/Article/details/gtnrixztxc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aizwys.cn/Article/details/gtomlffrnk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohxcbfdt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gthflskldv.html

[H08] 获取错误信息与堆栈
来源：http://dali.sxryk.cn/Article/details/gtbiighgoy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pycfn.com/Article/details/gtiezlzsdm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jiagoushi.top/Article/details/gtlzphjkny.html

JS:   e.message;  e.stack
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsthsewua.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sysykeji.top/Article/details/gtaztjrdfh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tian-w.cn/Article/details/gtwjdycqpq.html

Go:   err.Error()
来源：http://dali.shanyushiyangtech.top/Article/details/gtssdfrjur.html

Ruby: e.message;  e.backtrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuizqqpff.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrqyklwcl.html

[H09] 带错误码的异常
来源：http://dali.tanke756.top/Article/details/gtllpuvexl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cheryme.top/Article/details/gtsgklwzyb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvvmfbpfg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xinyue.icu/Article/details/gtzaqmmsps.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.aibaodan.cn/Article/details/gteoxteprt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuxming.cn/Article/details/gtqcujdheu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daria6918.cn/Article/details/gtfdykivcz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cqqwz.cn/Article/details/gtuqvsigre.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cqqwz.cn/Article/details/gtrhgzeigt.html

[H10] 资源自动释放
来源：http://dali.fzhhl.top/Article/details/gtoljchlsy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.guowangkeji.top/Article/details/gtuzmfdhxk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cashguo.top/Article/details/gterezexmh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cheryme.top/Article/details/gtyfictmll.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.haohaochexian.top/Article/details/gtlmeleswn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.smart0.xyz/Article/details/gtvjuxbpuj.html

Go:   defer f.Close()
来源：http://dali.hnxiangtu.top/Article/details/gtyubsxlzx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.feifeiyinyue.top/Article/details/gtanzrutrj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtuxgdxtjb.html


<!-- 参考信息 -->