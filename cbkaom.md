代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtcbiztqbx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtyhmqcmow.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtgtufmxpz.html

Go:   os.Remove("a.txt")
来源：http://dali.tian-w.cn/Article/details/gttiykeyrj.html

Ruby: File.delete("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtudibqxix.html

C#:   File.Delete("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtueibeqkk.html

[F07] 创建目录（含多级）
来源：http://dali.dianchejie.cn/Article/details/gtxmygomlz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shuidangran.top/Article/details/gtzhbyyypf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gaohongyu789.top/Article/details/gtfbllsean.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gtsybfwwgy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.9152youxi.cn/Article/details/gtzlmoomlw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhengqikj.top/Article/details/gtbvndvqbd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daria6918.cn/Article/details/gtlznolmcw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jianghu66.top/Article/details/gtjqcwcigz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daxiang520.top/Article/details/gtomrdtjfs.html

[F08] 遍历目录
来源：http://dali.jinqigfzy.top/Article/details/gtloanujvp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daria6918.cn/Article/details/gtrdqzvbho.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jlsjyb.cn/Article/details/gtuumfxnrz.html

JS:   fs.readdirSync("dir")
来源：http://dali.c1oappe.top/Article/details/gtxhlxwkph.html

TS:   fs.readdirSync("dir")
来源：http://dali.dashuyun.cn/Article/details/gtsfxuztcg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yvedp.cn/Article/details/gtvhyavvik.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.andypj.xyz/Article/details/gtadtdozao.html

Ruby: Dir.children("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgqmxufkz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.mhx1999.top/Article/details/gtunzghabu.html

[F09] 获取文件大小
来源：http://dali.hammf.cn/Article/details/gtmjgrdkfs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtnfghzknl.html

PHP:  filesize("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtwjojhhdx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gtfgxqiuvd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gtgcqoemvt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtmaaftobh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yuxming.cn/Article/details/gtakoqvuod.html

Ruby: File.size("a.txt")
来源：http://dali.ivvv.top/Article/details/gtvxsrvcbw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinqigufen.top/Article/details/gttnaypfcw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yangfankeji.com/Article/details/gtdjfwzlff.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtjeqhocdh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtztiislyn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtiubpeizy.html

TS:   path.extname("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtajmiherl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hywenlv.cn/Article/details/gthycrpfag.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gttomuvfzj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtsoykwkri.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtblhmnoop.html

[F11] 复制与移动文件
来源：http://dali.ppjwa.cn/Article/details/gtqthfofpl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtjcyfyvmx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fengsongda.top/Article/details/gtmhifwgbx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtwvxutgql.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gttcrhkzol.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cheryme.top/Article/details/gtvaugoean.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zdqjudy.top/Article/details/gteryrfkkt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtuusvsmqe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pengpengdd.cyou/Article/details/gtmoiheehi.html

[F12] CSV 读写
来源：http://dali.yj20258.top/Article/details/gthwafnakd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.daria6918.cn/Article/details/gtccfxlpln.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jyoumei.cn/Article/details/gtmyvkhapr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pycfn.com/Article/details/gtthinjety.html

TS:   // 同上
来源：http://dali.svipenyu.cn/Article/details/gtkjvatmoo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenzaomai.com/Article/details/gteoekhoyb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hongshengwenyu.top/Article/details/gtwunicmfi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.iojbl.cn/Article/details/gtolgxayux.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.aibaodan.cn/Article/details/gtriqqivjb.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtjnjtxrbp.html

G. 面向对象
来源：http://dali.sweek.top/Article/details/gtcvijjkgd.html

================================================================================
来源：http://dali.sweek.top/Article/details/gttwnabugr.html

[G01] 定义类
来源：http://dali.hongshengwenyu.top/Article/details/gtnpgpaypt.html

Py:   class User: pass
来源：http://dali.iojbl.cn/Article/details/gtejjudabz.html

PHP:  class User {}
来源：http://dali.hysaishi.cn/Article/details/gtevvzfoqm.html

JS:   class User {}
来源：http://dali.tanke756.top/Article/details/gtsyzmemjr.html

TS:   class User { name: string = ""; }
来源：http://dali.xinyue.icu/Article/details/gtidgfbnkt.html

Java: class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtzrleifyo.html

Go:   type User struct { Name string }
来源：http://dali.jinqigufen.top/Article/details/gtmmmlbciq.html

Ruby: class User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdmrobxrs.html

C#:   class User {}
来源：http://dali.tanke756.top/Article/details/gtiglspclb.html

[G02] 构造函数
来源：http://dali.cashguo.top/Article/details/gtndddidhr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.iojbl.cn/Article/details/gtvlcivbqs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gogol.net.cn/Article/details/gtelqbhsot.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gtsuykkiwg.html

TS:   constructor(public name: string) {}
来源：http://dali.quarkkingdee.top/Article/details/gtjitgrwgq.html

Java: User(String name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtmkrjirqm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigfzy.top/Article/details/gtmnzclefo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hfpthk.cn/Article/details/gtbpjglpab.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yuanzhike.top/Article/details/gtlszfahqn.html

[G03] 实例属性
来源：http://dali.havefunace.top/Article/details/gtwhqegrkc.html

Py:   self.name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gtwnflkdxy.html

PHP:  public string $name = "x";
来源：http://dali.shzxlz.cn/Article/details/gtldoaqceu.html

JS:   this.name = "x";
来源：http://dali.sweek.top/Article/details/gtivaivryt.html

TS:   name: string = "x";
来源：http://dali.daria6918.cn/Article/details/gtkxcvjwsq.html

Java: private String name;
来源：http://dali.tanke756.top/Article/details/gtjvopdeew.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yvedp.cn/Article/details/gtlbhgskhs.html

Ruby: @name = "x"
来源：http://dali.cashguo.top/Article/details/gtiuevrkpx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tian-w.cn/Article/details/gtrckfehrl.html

[G04] 定义方法
来源：http://dali.yonumen.top/Article/details/gtexpunakb.html

Py:   def greet(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gttlkkhmbw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gtirumwkxw.html

JS:   greet() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtrymaenay.html

TS:   greet(): string { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtzixgfwuf.html

Java: String greet() { return name; }
来源：http://dali.pycfn.com/Article/details/gtiorfjldy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gtutzuiykl.html

Ruby: def greet; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gtnlshyojk.html

C#:   public string Greet() => Name;
来源：http://dali.zhixingplan.top/Article/details/gtptrjesqk.html

[G05] 继承
来源：http://dali.haohaochexian.top/Article/details/gtideuzptr.html

Py:   class Admin(User): pass
来源：http://dali.nanxinkj.top/Article/details/gtwauwiibi.html

PHP:  class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtjmfvlevf.html

JS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtxacnerqk.html

TS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtnoylilyt.html

Java: class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtjoodwxqa.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.svipenyu.cn/Article/details/gtesaejptf.html

Ruby: class Admin < User; end
来源：http://dali.smart0.xyz/Article/details/gtjglmtcjk.html

C#:   class Admin : User {}
来源：http://dali.daria6918.cn/Article/details/gtmmxdaysd.html

[G06] 重写方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqlzuagie.html

Py:   def greet(self): return "admin"
来源：http://dali.nwbrower.top/Article/details/gtmattpusb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtcucpktdc.html

JS:   greet() { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtslqobtel.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgmpknzn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrofjbbdu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.svipenyu.cn/Article/details/gtmywovtvc.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigufen.top/Article/details/gtkvtntwxd.html

C#:   public override string Greet() => "admin";
来源：http://dali.316326.xyz/Article/details/gtidqwihac.html

[G07] 调用父类方法
来源：http://dali.wangdashe.top/Article/details/gtdajkrqpy.html

Py:   super().greet()
来源：http://dali.ppjwa.cn/Article/details/gtlyaqtzcy.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gticzpecno.html

JS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfsezvler.html

TS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gtcicrgrta.html

Java: super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gthrltxjyt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.0kj1m.cn/Article/details/gtwzequtsm.html

Ruby: super
来源：http://dali.yuanzhike.top/Article/details/gthvlukimq.html

C#:   base.Greet();
来源：http://dali.nanxinkj.top/Article/details/gtnwqqkaxv.html

[G08] 静态方法与属性
来源：http://dali.havefunace.top/Article/details/gtwyqaiuix.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.bjfxy.top/Article/details/gtsqsfdlcs.html

PHP:  public static function f() {}
来源：http://dali.smart0.xyz/Article/details/gtagcniamd.html

JS:   static f() {}
来源：http://dali.fzhhl.top/Article/details/gtmlmpelsm.html

TS:   static f(): void {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtueqppfyh.html

Java: static void f() {}
来源：http://dali.tianlin.xyz/Article/details/gtrxghfvzi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sysykeji.top/Article/details/gtgdcemixm.html

Ruby: def self.f; end
来源：http://dali.jyoumei.cn/Article/details/gtbpunebxx.html

C#:   public static void F() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbfwpxslo.html

[G09] 接口 / 抽象类
来源：http://dali.feifeiyinyue.top/Article/details/gtyuiggabq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zdqjudy.top/Article/details/gtxhnpsufy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenzaomai.com/Article/details/gtixuhwvnr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nwbrower.top/Article/details/gtxpxdlmhb.html

TS:   interface Shape { area(): number; }
来源：http://dali.yonumen.top/Article/details/gtzgnjpiac.html

Java: interface Shape { double area(); }
来源：http://dali.shzxlz.cn/Article/details/gtsbixbkvz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ybcxt.top/Article/details/gtzjpxetbs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gaohongyu789.top/Article/details/gthceemezx.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxuanxn.top/Article/details/gtszyqjsev.html

[G10] 访问控制
来源：http://dali.shangyingyoupin.top/Article/details/gtxzvjpmbk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangdashe.top/Article/details/gtvyxikxoj.html

PHP:  public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtbzxudbsz.html

JS:   #private 字段；其余公开
来源：http://dali.jqgfzy.top/Article/details/gtjlantjoa.html

TS:   public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtxcikfqme.html

Java: public / protected / private / 默认包级
来源：http://dali.fengsongda.top/Article/details/gtxfvsqviu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yangfankeji.com/Article/details/gtrbokuqak.html

Ruby: public / protected / private
来源：http://dali.yvedp.cn/Article/details/gtwbyuwhnq.html

C#:   public / protected / private / internal
来源：http://dali.zhengqikj.top/Article/details/gtdnjxivik.html

[G11] getter / setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfkifgcyf.html

Py:   @property 与 @x.setter
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbaitqsp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtbjsokwow.html

JS:   get name() { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gtoilrhcqx.html

TS:   get name(): string { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gtmuhnprpe.html

Java: public String getName() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtohqmyilv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gtzvgytmzs.html

Ruby: attr_accessor :name
来源：http://dali.316326.xyz/Article/details/gtewjqfepk.html

C#:   public string Name { get; set; }
来源：http://dali.redwolf501.top/Article/details/gtraqnuzef.html

[G12] 对象转字符串
来源：http://dali.jqgufenzy.top/Article/details/gtzdlfppgw.html

Py:   def __str__(self): return self.name
来源：http://dali.iojbl.cn/Article/details/gtwofuodbf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtijmbfneh.html

JS:   toString() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtcjobyyea.html

TS:   toString(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtyrgyllzq.html

Java: @Override public String toString() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtqvsthpnh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gtyghtetne.html

Ruby: def to_s; @name; end
来源：http://dali.sufxvd.cn/Article/details/gtgcixuqsp.html

C#:   public override string ToString() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gtnyuzgroj.html

[G13] 判断对象类型
来源：http://dali.zhongyouzk.top/Article/details/gtvdscefze.html

Py:   isinstance(u, User)
来源：http://dali.ehwqpu.com/Article/details/gtxskwidru.html

PHP:  $u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtwawxhhfw.html

JS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtyxddvkrk.html

TS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtoocajtyj.html

Java: u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtmjefcmhm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuetiantiany.cn/Article/details/gtgzvedtkb.html

Ruby: u.is_a?(User)
来源：http://dali.jlsjyb.cn/Article/details/gtpzekkxkd.html

C#:   u is User
来源：http://dali.bjfxy.top/Article/details/gtnpycghzf.html

[G14] 数据类 / record
来源：http://dali.yvedp.cn/Article/details/gtsexdufds.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinghuilouyu.cn/Article/details/gtaztipaqo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.smart0.xyz/Article/details/gtfavnsmas.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yongpay.top/Article/details/gtfzphlzhn.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj20258888.top/Article/details/gtlpkejzjo.html

Java: record User(String name, int age) {}
来源：http://dali.yongpay.top/Article/details/gtzwrzawzm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sweek.top/Article/details/gtmsvhzspp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xylfe.cn/Article/details/gtvypjgkgm.html

C#:   record User(string Name, int Age);
来源：http://dali.gzhubu.top/Article/details/gtqfuqevux.html

[G15] 枚举
来源：http://dali.guannengcc.top/Article/details/gtrpqovpyy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhoulong.xyz/Article/details/gtlnfudsga.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ivvv.top/Article/details/gtxxstiynt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gaohongyu789.top/Article/details/gtzrnlvgrv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ybcxt.top/Article/details/gtpcpnwndn.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhongyouzk.top/Article/details/gthihpaglv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jiagoushi.top/Article/details/gtacbunveg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.birdmap.top/Article/details/gtiewswvnn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtslbrumxc.html

[G16] 对象转数组 / 字典
来源：http://dali.meibo888.top/Article/details/gthwzkalfj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sysykeji.top/Article/details/gtjwuvnirh.html

PHP:  get_object_vars($obj);
来源：http://dali.yuanzhike.top/Article/details/gtwbhomwov.html

JS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtwyqyqmxw.html

TS:   Object.entries(obj)
来源：http://dali.aizwys.cn/Article/details/gtxidkgrzo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xziqi.cn/Article/details/gtnwlxmhqb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.feifeiyinyue.top/Article/details/gtqbikhgob.html

Ruby: obj.instance_variables
来源：http://dali.havefunace.top/Article/details/gtffkylutj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yongpay.top/Article/details/gtyifjnglk.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtnxkmybqj.html

H. 异常与错误处理
来源：http://dali.shangyingyoupin.top/Article/details/gtoeifrtlq.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtskbpsjmm.html

[H01] try / catch 基础
来源：http://dali.shanyushiyangtech.top/Article/details/gtcqdikhus.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ybcxt.top/Article/details/gtsqixjwmj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.aibaodan.cn/Article/details/gtfpsugilb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gthhxfwlxx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gtlgfkvass.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.316326.xyz/Article/details/gtjwyutuwa.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.meibo888.top/Article/details/gtvlpzujit.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gzhubu.top/Article/details/gttghbbmmj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnqzz.top/Article/details/gtnatawhbc.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258888.top/Article/details/gtokjmzttd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhiwuduotai.top/Article/details/gtdnyzrdgs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtsmbvmr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtbkllqdnp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtbctjuwnw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtayjoqnwc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cdnleiting.top/Article/details/gtzfdrwnle.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.pengpengdd.cyou/Article/details/gtmptfmzec.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtoynlzkse.html

[H03] 主动抛出异常
来源：http://dali.jyoumei.cn/Article/details/gtceuaaeas.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinqigfzy.top/Article/details/gthkhekvwa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gtpxbtkuel.html

JS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtcrvwgdhr.html

TS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtfuegfqyo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtrmyawtzo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.svipenyu.cn/Article/details/gtffswwupb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.haohaochexian.top/Article/details/gtsifjjfib.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtzmpytraw.html

[H04] 自定义异常类型
来源：http://dali.tianlin.xyz/Article/details/gtyzuaxmxh.html

Py:   class MyError(Exception): pass
来源：http://dali.chenlongwang.top/Article/details/gtymozqgpk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjfejxgb.html

JS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gtomwndqyv.html

TS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gtqsirddjy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj20258.top/Article/details/gtkxunfqqz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.316326.xyz/Article/details/gtvwoiwjlt.html

Ruby: class MyError < StandardError; end
来源：http://dali.jianghu66.top/Article/details/gtaswuozuh.html

C#:   class MyException : Exception {}
来源：http://dali.cashguo.top/Article/details/gtcoqsueog.html

[H05] 捕获特定类型
来源：http://dali.jlsjyb.cn/Article/details/gtxrkglwvl.html

Py:   except ValueError as e:
来源：http://dali.sufxvd.cn/Article/details/gteycjsunc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj202588.top/Article/details/gtthdlgldw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvifugsxn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ydzc1.top/Article/details/gtryiglhqb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.mhx1999.top/Article/details/gtycwzrhsf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yonumen.top/Article/details/gtmbipujoh.html

Ruby: rescue ArgumentError => e
来源：http://dali.mhx1999.top/Article/details/gtxkfeuxis.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sysykeji.top/Article/details/gtcsovbabk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.iojbl.cn/Article/details/gtrjtasrek.html

Py:   value = d.get("k") or default
来源：http://dali.nanxuanxn.top/Article/details/gtakrvhfcw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gtlqiubccg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gtuudkvmjr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tianlin.xyz/Article/details/gtlpeiybxj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhongyouzk.top/Article/details/gtvlbplowa.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.snrcjt.cn/Article/details/gtouuytmgs.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nwbrower.top/Article/details/gtngmnzyyj.html

C#:   obj?.A?.B ?? default
来源：http://dali.aibaodan.cn/Article/details/gtyjndixra.html

[H07] 断言
来源：http://dali.tian-w.cn/Article/details/gtkaebnfmg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxinkj.top/Article/details/gteyslrmgj.html

PHP:  assert($x > 0);
来源：http://dali.mhx1999.top/Article/details/gtuuxgliza.html

JS:   console.assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gtezwvspzy.html

TS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtkppyznrh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258888.top/Article/details/gtiszivfuy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hongshengwenyu.top/Article/details/gtlwpmlggz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aibaodan.cn/Article/details/gtvfuwbmft.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtsndzynly.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhongyouzk.top/Article/details/gtaznlgsiq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.snrcjt.cn/Article/details/gtnaqbsiug.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.316326.xyz/Article/details/gtjyaspkkc.html

JS:   e.message;  e.stack
来源：http://dali.shzxlz.cn/Article/details/gtdbszjtzd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhongyouzk.top/Article/details/gtanebblca.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhoulong.xyz/Article/details/gtgyjjdrck.html

Go:   err.Error()
来源：http://dali.sufxvd.cn/Article/details/gtzupwznpy.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj202588.top/Article/details/gtpwfwpecs.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sxryk.cn/Article/details/gtufiivbpl.html

[H09] 带错误码的异常
来源：http://dali.yj20258.top/Article/details/gttjsiaihv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jyoumei.cn/Article/details/gtjpyxdclo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.meibo888.top/Article/details/gtrerkducj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hywenlv.cn/Article/details/gthnhkbexg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zdqjudy.top/Article/details/gtmmyiykyf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yonumen.top/Article/details/gtrtfwnqsl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gogol.net.cn/Article/details/gtnxakzchl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yueranfly.top/Article/details/gtjcpdodva.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenzaomai.com/Article/details/gtdurfjrbu.html

[H10] 资源自动释放
来源：http://dali.jyoumei.cn/Article/details/gtnwwwkzwj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sxryk.cn/Article/details/gtivezdxiq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.kuanghao11.cn/Article/details/gtgqgaylsm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gtprkzlznu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnxiangtu.top/Article/details/gtmyemvoov.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.haohaochexian.top/Article/details/gtmxtbmake.html

Go:   defer f.Close()
来源：http://dali.gogol.net.cn/Article/details/gtccisybyi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.aizwys.cn/Article/details/gtjdfzgrhg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yongpay.top/Article/details/gtmlokfoqv.html


<!-- 参考信息 -->