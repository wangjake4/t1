代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtchyaydgu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtfaeqrjhg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.9152youxi.cn/Article/details/gtdngdidse.html

Ruby: File.exist?("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtrzhalihx.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtywkztcqg.html

[F06] 删除文件
来源：http://dali.yonumen.top/Article/details/gtybmgdgpk.html

Py:   os.remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtgzwnsusd.html

PHP:  unlink("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtdclflqer.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtqvnhwnes.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtwsaesupe.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsktwkmfl.html

Go:   os.Remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtlpdocgbr.html

Ruby: File.delete("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtjnlmriao.html

C#:   File.Delete("a.txt");
来源：http://dali.pycfn.com/Article/details/gtzaagrroy.html

[F07] 创建目录（含多级）
来源：http://dali.chenlongwang.top/Article/details/gthdvmdetr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhengqikj.top/Article/details/gtnamdmqbh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.smart0.xyz/Article/details/gttonotmli.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258888.top/Article/details/gtertfcgba.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.birdmap.top/Article/details/gtprabqzwa.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.fengsongda.top/Article/details/gtsvyulbeu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hammf.cn/Article/details/gtszfeotgv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aizwys.cn/Article/details/gtmfesjeyl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daxiang520.top/Article/details/gtuxvfvcwf.html

[F08] 遍历目录
来源：http://dali.chenlongwang.top/Article/details/gtnjhallai.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhiwuduotai.top/Article/details/gthoybatvf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pengpengdd.cyou/Article/details/gtqoeqqwkj.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtqfervrgv.html

TS:   fs.readdirSync("dir")
来源：http://dali.gzhubu.top/Article/details/gtoodvbeqh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gtkvgzoqga.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cashguo.top/Article/details/gtnirjskmf.html

Ruby: Dir.children("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtreqgyxvx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtccfeisji.html

[F09] 获取文件大小
来源：http://dali.jinqigfzy.top/Article/details/gtvxsrryeg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtddiralkk.html

PHP:  filesize("a.txt");
来源：http://dali.havefunace.top/Article/details/gtwbtqwzbh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.mhx1999.top/Article/details/gthlrvgirs.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shuidangran.top/Article/details/gtqxbcodwf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtpsfcmbcz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.feifeiyinyue.top/Article/details/gtkmtzpibv.html

Ruby: File.size("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtfoqnueoo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xinyue.icu/Article/details/gtobdknacx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfupcufj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtthczffgx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtiuszbyid.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtcxsgzuox.html

TS:   path.extname("a.txt")
来源：http://dali.meibo888.top/Article/details/gtkupoxygn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.andypj.xyz/Article/details/gtnyfydbpu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtawqkbmny.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtqvtvbygi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtucisoyxr.html

[F11] 复制与移动文件
来源：http://dali.jyoumei.cn/Article/details/gtvdjbygsb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtwrutfdle.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhengqikj.top/Article/details/gtfaxkmwgw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtufkdmfbb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtmkeeiyjp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.c1oappe.top/Article/details/gtnwypkbrt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.dianchejie.cn/Article/details/gttkxjmyes.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtpvtehstu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cheryme.top/Article/details/gtwudrdijq.html

[F12] CSV 读写
来源：http://dali.dashuyun.cn/Article/details/gtkhajdlxt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhixingplan.top/Article/details/gthhoyktas.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.svipenyu.cn/Article/details/gtyqceyikf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gtifwvsgex.html

TS:   // 同上
来源：http://dali.jianghu66.top/Article/details/gtolusuyys.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.guannengcc.top/Article/details/gtmgvnzzlm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.316326.xyz/Article/details/gtlmneozlx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.daria6918.cn/Article/details/gtwarbeidb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zdqjudy.top/Article/details/gtljlrtzjb.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtakhctvte.html

G. 面向对象
来源：http://dali.zhongyouzk.top/Article/details/gtxqjmrkwa.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtccuwqxkt.html

[G01] 定义类
来源：http://dali.jianghu66.top/Article/details/gtyzjzwheq.html

Py:   class User: pass
来源：http://dali.aibaodan.cn/Article/details/gtmtoqmcin.html

PHP:  class User {}
来源：http://dali.daria6918.cn/Article/details/gtjdujwuaf.html

JS:   class User {}
来源：http://dali.havefunace.top/Article/details/gthagsnjef.html

TS:   class User { name: string = ""; }
来源：http://dali.c1oappe.top/Article/details/gtonsocuzb.html

Java: class User {}
来源：http://dali.yuxming.cn/Article/details/gtojjanuvv.html

Go:   type User struct { Name string }
来源：http://dali.xinyue.icu/Article/details/gtaxhahwkg.html

Ruby: class User; end
来源：http://dali.wangdashe.top/Article/details/gtgiuqepbh.html

C#:   class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtphsljiat.html

[G02] 构造函数
来源：http://dali.svipenyu.cn/Article/details/gtspprvgfq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hfpthk.cn/Article/details/gtkqwkhstt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shzxlz.cn/Article/details/gtxkdjwyit.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gttptdigcp.html

TS:   constructor(public name: string) {}
来源：http://dali.daria6918.cn/Article/details/gtprcaimup.html

Java: User(String name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtzdisaqfm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpuuimonx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shzxlz.cn/Article/details/gtxuhhwsym.html

C#:   public User(string name) { Name = name; }
来源：http://dali.daxiang520.top/Article/details/gtqohaxbdu.html

[G03] 实例属性
来源：http://dali.gaohongyu789.top/Article/details/gthbwxnfmr.html

Py:   self.name = "x"
来源：http://dali.xuanzx.com/Article/details/gtghvnckvt.html

PHP:  public string $name = "x";
来源：http://dali.cucudq.cn/Article/details/gteuttheld.html

JS:   this.name = "x";
来源：http://dali.hammf.cn/Article/details/gtdmzpvtyt.html

TS:   name: string = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtmvduvbve.html

Java: private String name;
来源：http://dali.0kj1m.cn/Article/details/gtbaqnpker.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tian-w.cn/Article/details/gtfitgafgg.html

Ruby: @name = "x"
来源：http://dali.redwolf501.top/Article/details/gthvllxtwr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hysaishi.cn/Article/details/gtltdwxzzj.html

[G04] 定义方法
来源：http://dali.hnxiangtu.top/Article/details/gtayoonumq.html

Py:   def greet(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gtpznsrfkp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgzvruudg.html

JS:   greet() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtsxpqvsqd.html

TS:   greet(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gtgmsrwafb.html

Java: String greet() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtvpadvzad.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gtrjuojpge.html

Ruby: def greet; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gtcnrkufwv.html

C#:   public string Greet() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gttalqrisi.html

[G05] 继承
来源：http://dali.gotoacloud.top/Article/details/gtqypcwfij.html

Py:   class Admin(User): pass
来源：http://dali.ehwqpu.com/Article/details/gttlzmhpne.html

PHP:  class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtlijmpkqj.html

JS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtoloyvnul.html

TS:   class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtmnenqary.html

Java: class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtesdlcjvs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tanke756.top/Article/details/gtmaoyjkro.html

Ruby: class Admin < User; end
来源：http://dali.ppjwa.cn/Article/details/gtxdmjlrtx.html

C#:   class Admin : User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtwvthnipf.html

[G06] 重写方法
来源：http://dali.nanxuanxn.top/Article/details/gtjfatnjho.html

Py:   def greet(self): return "admin"
来源：http://dali.fzhhl.top/Article/details/gtllwbofla.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtuayonhdr.html

JS:   greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtjcnldhdz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gttvbqtaeq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtwparvcxc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cashguo.top/Article/details/gtkrmwvrly.html

Ruby: def greet; "admin"; end
来源：http://dali.shzxlz.cn/Article/details/gtinzyeezh.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovkvmmac.html

[G07] 调用父类方法
来源：http://dali.yonumen.top/Article/details/gtiaponpbe.html

Py:   super().greet()
来源：http://dali.vqdsnc.cn/Article/details/gtcegrgqst.html

PHP:  parent::greet();
来源：http://dali.cqqwz.cn/Article/details/gtnajlzdkx.html

JS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gtdafworwj.html

TS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtitetvsil.html

Java: super.greet();
来源：http://dali.cucudq.cn/Article/details/gtraxkpndn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.vqdsnc.cn/Article/details/gtimyntnjs.html

Ruby: super
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomncuqpo.html

C#:   base.Greet();
来源：http://dali.zdqjudy.top/Article/details/gtwozeuqxx.html

[G08] 静态方法与属性
来源：http://dali.yonumen.top/Article/details/gtgemkwzcf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.redwolf501.top/Article/details/gtouzitvmp.html

PHP:  public static function f() {}
来源：http://dali.zdqjudy.top/Article/details/gtdurmqtge.html

JS:   static f() {}
来源：http://dali.aizwys.cn/Article/details/gtuxhlhusm.html

TS:   static f(): void {}
来源：http://dali.ppjwa.cn/Article/details/gtrbhaxyur.html

Java: static void f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyqzyhrcx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yueranfly.top/Article/details/gtsaytlfkp.html

Ruby: def self.f; end
来源：http://dali.cdnleiting.top/Article/details/gtclerciec.html

C#:   public static void F() {}
来源：http://dali.yj202588.top/Article/details/gtdlrbrloe.html

[G09] 接口 / 抽象类
来源：http://dali.zhixingplan.top/Article/details/gtwjjrxwfn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinqigufen.top/Article/details/gtuhxxpnmk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aizwys.cn/Article/details/gtvisnglul.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pycfn.com/Article/details/gtcghrzkga.html

TS:   interface Shape { area(): number; }
来源：http://dali.shangyingyoupin.top/Article/details/gtrohjfvhh.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigufen.top/Article/details/gtzfhwgwvl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhongyouzk.top/Article/details/gtladdpuau.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuanzx.com/Article/details/gtohfzcljz.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgfzy.top/Article/details/gtrfxznyqp.html

[G10] 访问控制
来源：http://dali.fengsongda.top/Article/details/gtkawmwjmc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jyoumei.cn/Article/details/gtkviidhtz.html

PHP:  public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtjmwklelo.html

JS:   #private 字段；其余公开
来源：http://dali.kuanghao11.cn/Article/details/gtqvvmzlyx.html

TS:   public / protected / private
来源：http://dali.redwolf501.top/Article/details/gtpruzbhrl.html

Java: public / protected / private / 默认包级
来源：http://dali.cheryme.top/Article/details/gtsfonrjvz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guowangkeji.top/Article/details/gthucuaxnm.html

Ruby: public / protected / private
来源：http://dali.wangdashe.top/Article/details/gtmgpouwag.html

C#:   public / protected / private / internal
来源：http://dali.fengsongda.top/Article/details/gtqpnvzewf.html

[G11] getter / setter
来源：http://dali.kuanghao11.cn/Article/details/gtfauumzik.html

Py:   @property 与 @x.setter
来源：http://dali.gzhubu.top/Article/details/gtefndknfb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtkzmlorux.html

JS:   get name() { return this._name; }
来源：http://dali.guowangkeji.top/Article/details/gtewyhkjba.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbooqjcrq.html

Java: public String getName() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtqbmraxwe.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gtjgreptxd.html

Ruby: attr_accessor :name
来源：http://dali.yj20258.top/Article/details/gtqgggxyag.html

C#:   public string Name { get; set; }
来源：http://dali.smart0.xyz/Article/details/gtmfhjfldz.html

[G12] 对象转字符串
来源：http://dali.cucudq.cn/Article/details/gtttunecrv.html

Py:   def __str__(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gtgnzuwqms.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gteekxtwns.html

JS:   toString() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtdonyorqv.html

TS:   toString(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gttcubkoqb.html

Java: @Override public String toString() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtqfylqldl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtwvlhziol.html

Ruby: def to_s; @name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjamiogq.html

C#:   public override string ToString() => Name;
来源：http://dali.chenlongwang.top/Article/details/gtcpijwoag.html

[G13] 判断对象类型
来源：http://dali.ydzc1.top/Article/details/gtqwdmsxwq.html

Py:   isinstance(u, User)
来源：http://dali.tianlin.xyz/Article/details/gtceiisgwj.html

PHP:  $u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtmejnnbhw.html

JS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtuupqzkzu.html

TS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtbfphpfso.html

Java: u instanceof User
来源：http://dali.ybcxt.top/Article/details/gtpbjybezj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ydzc1.top/Article/details/gtatjhupmd.html

Ruby: u.is_a?(User)
来源：http://dali.dashuyun.cn/Article/details/gtsocoqjdw.html

C#:   u is User
来源：http://dali.cashguo.top/Article/details/gtfhmhlemr.html

[G14] 数据类 / record
来源：http://dali.ydzc1.top/Article/details/gtpthaswns.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.feifeiyinyue.top/Article/details/gtlfzehxgo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tian-w.cn/Article/details/gtfcnsyhbb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenlongwang.top/Article/details/gtyadduvjm.html

TS:   type User = { name: string; age: number };
来源：http://dali.smart0.xyz/Article/details/gtpewjvutr.html

Java: record User(String name, int age) {}
来源：http://dali.haohaochexian.top/Article/details/gtwuibjjrg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj20258888.top/Article/details/gtiiiqvvoj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenzaomai.com/Article/details/gtdlbqebwz.html

C#:   record User(string Name, int Age);
来源：http://dali.daxiang520.top/Article/details/gtgnihewln.html

[G15] 枚举
来源：http://dali.chenlongwang.top/Article/details/gttvswfkyb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj20258.top/Article/details/gtfjbwcnog.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.birdmap.top/Article/details/gtpqazyhwk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxinkj.top/Article/details/gtlptjoblu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.iojbl.cn/Article/details/gtibmherkn.html

Java: enum Color { RED, GREEN }
来源：http://dali.xziqi.cn/Article/details/gtpokfwcai.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.vqdsnc.cn/Article/details/gtiqkdrokc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yongpay.top/Article/details/gtnwdtdpva.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gteyxxwbmq.html

[G16] 对象转数组 / 字典
来源：http://dali.cdnleiting.top/Article/details/gttfteqswv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhiwuduotai.top/Article/details/gtxcbqwavg.html

PHP:  get_object_vars($obj);
来源：http://dali.zhiwuduotai.top/Article/details/gtiyitnqyj.html

JS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gttlifciqd.html

TS:   Object.entries(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtdotgjazy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangdashe.top/Article/details/gtzkaviiyz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.snrcjt.cn/Article/details/gtrxsujyia.html

Ruby: obj.instance_variables
来源：http://dali.nwbrower.top/Article/details/gtvxlajexv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhoulong.xyz/Article/details/gtxerqakdf.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtewietmxz.html

H. 异常与错误处理
来源：http://dali.tian-w.cn/Article/details/gtaozlauzj.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtanzisfdm.html

[H01] try / catch 基础
来源：http://dali.zhiwuduotai.top/Article/details/gtybskmabx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.kuanghao11.cn/Article/details/gtlzvpdaem.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yueranfly.top/Article/details/gtofmscjuq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gtuddurvph.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gtnnjzlubg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xylfe.cn/Article/details/gtlathwffs.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zdqjudy.top/Article/details/gtqmdbrrok.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jiagoushi.top/Article/details/gtlnleosfl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nwbrower.top/Article/details/gtlimxdcvu.html

[H02] finally / ensure 收尾
来源：http://dali.birdmap.top/Article/details/gtjinlzzql.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gogol.net.cn/Article/details/gtkastfayl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtjajiymgv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtqdwhbzka.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtsdexlbjq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtjmxhlvnf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.snrcjt.cn/Article/details/gtvvescikd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangshuangyany.cn/Article/details/gtcenrlzpf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmmbtdav.html

[H03] 主动抛出异常
来源：http://dali.birdmap.top/Article/details/gtnnxslrkb.html

Py:   raise ValueError("错误信息")
来源：http://dali.pycfn.com/Article/details/gtlvsxwjxi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtbdcadwqa.html

JS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gtbusqvpsj.html

TS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtdrqfobyd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtbjqkxrsy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hysaishi.cn/Article/details/gtdnabxqlc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nanxinkj.top/Article/details/gtyqddsznp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtqkgxpcjf.html

[H04] 自定义异常类型
来源：http://dali.yangfankeji.com/Article/details/gtgncfnqee.html

Py:   class MyError(Exception): pass
来源：http://dali.birdmap.top/Article/details/gtqtguhqiw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gteheeglif.html

JS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gtdpojfykz.html

TS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gtvoabmqif.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gterwfkkpu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xuanzx.com/Article/details/gtswmmmqsg.html

Ruby: class MyError < StandardError; end
来源：http://dali.xinyue.icu/Article/details/gtflddhjse.html

C#:   class MyException : Exception {}
来源：http://dali.xziqi.cn/Article/details/gtuuswxnhc.html

[H05] 捕获特定类型
来源：http://dali.hongshengwenyu.top/Article/details/gtckxhtnoq.html

Py:   except ValueError as e:
来源：http://dali.tianlin.xyz/Article/details/gtvlqmyimw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gotoacloud.top/Article/details/gtngmwsqap.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtdyscaadl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gtptxvnute.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yanxiufei.cn/Article/details/gttzzcyvax.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrciplhnb.html

Ruby: rescue ArgumentError => e
来源：http://dali.xuetiantiany.cn/Article/details/gtwztslmlv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.haohaochexian.top/Article/details/gtwcsldvbr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhiwuduotai.top/Article/details/gttbtamhfq.html

Py:   value = d.get("k") or default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkeznqtjh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gtrmkhoain.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gtivymchgt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jianghu66.top/Article/details/gthhwfiybj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnxiangtu.top/Article/details/gtvdugkcbl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gzhubu.top/Article/details/gtnfzbguop.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xinyue.icu/Article/details/gtojqilsgv.html

C#:   obj?.A?.B ?? default
来源：http://dali.andypj.xyz/Article/details/gtriwwwctk.html

[H07] 断言
来源：http://dali.wangshuangyany.cn/Article/details/gtjzrqywhh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhixingplan.top/Article/details/gtrmkgkblf.html

PHP:  assert($x > 0);
来源：http://dali.chenzaomai.com/Article/details/gtwshktpzm.html

JS:   console.assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gtlphjuedv.html

TS:   console.assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gtdjgsfppf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258888.top/Article/details/gttzpsocrq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gotoacloud.top/Article/details/gtnufjkysp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yvedp.cn/Article/details/gtzxowigvn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtvlsgjddl.html

[H08] 获取错误信息与堆栈
来源：http://dali.pengpengdd.cyou/Article/details/gtepyxhbsh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zycfv.cn/Article/details/gthrcipwbw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.meibo888.top/Article/details/gtyqdxxxhx.html

JS:   e.message;  e.stack
来源：http://dali.kuanghao11.cn/Article/details/gtjdfcfsio.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.haohaochexian.top/Article/details/gtfeqgfzmo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuanzhike.top/Article/details/gtzjqpsrrj.html

Go:   err.Error()
来源：http://dali.yj20258.top/Article/details/gtkzmxyebk.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhixingplan.top/Article/details/gtytivrewk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jqgufenzy.top/Article/details/gtdcbozlsk.html

[H09] 带错误码的异常
来源：http://dali.jiagoushi.top/Article/details/gtkjmwedbm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhixingplan.top/Article/details/gtllyzeuxg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcxphkis.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hammf.cn/Article/details/gtbpyanefs.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yangfankeji.com/Article/details/gtpclsehya.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigfzy.top/Article/details/gtopklowbc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jqgfzy.top/Article/details/gtjpmpvqpy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gtmbiogolt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yangfankeji.com/Article/details/gtamkrszqu.html

[H10] 资源自动释放
来源：http://dali.yuxming.cn/Article/details/gtosqakeju.html


<!-- 参考信息 -->