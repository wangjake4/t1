代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtjckqmcam.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtyoycahek.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.0kj1m.cn/Article/details/gtasexkzjr.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxlywwwe.html

C#:   File.Exists("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtykdwqusb.html

[F06] 删除文件
来源：http://dali.ydzc1.top/Article/details/gtismlwhrt.html

Py:   os.remove("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtahmpikrj.html

PHP:  unlink("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gttahtzksd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtikaxhaez.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtgrnajpxg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gtsdswklrk.html

Go:   os.Remove("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtucqhqixx.html

Ruby: File.delete("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtvvwuhfjm.html

C#:   File.Delete("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtjxmkqrde.html

[F07] 创建目录（含多级）
来源：http://dali.yj20258.top/Article/details/gtkhnurvsg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrgrhphif.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuetiantiany.cn/Article/details/gtjazaeafe.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gtbprrqodm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuanzx.com/Article/details/gtqkicufbb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dashuyun.cn/Article/details/gthdrrngnx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guowangkeji.top/Article/details/gthqdfhbvt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hnqzz.top/Article/details/gtafzwhipj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ehwqpu.com/Article/details/gtwrmwxrnv.html

[F08] 遍历目录
来源：http://dali.aizwys.cn/Article/details/gtnvzleogo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yongpay.top/Article/details/gtlulabjzy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yuxming.cn/Article/details/gtzvimpngf.html

JS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gtxrqivhwk.html

TS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gthxpdgmmz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gtsxxkthwy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.havefunace.top/Article/details/gtlbjohoxj.html

Ruby: Dir.children("dir")
来源：http://dali.gotoacloud.top/Article/details/gtktwneloy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cashguo.top/Article/details/gtmaqsmsik.html

[F09] 获取文件大小
来源：http://dali.guowangkeji.top/Article/details/gtppmpfgyx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtgmltikgq.html

PHP:  filesize("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtldzgkjtk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gtxbkdfppu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gtaooxjqky.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtdauofnib.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xuetiantiany.cn/Article/details/gtncvwzydl.html

Ruby: File.size("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtxzolyqzx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.svipenyu.cn/Article/details/gtfyhbrjrd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnxiangtu.top/Article/details/gtazbwzgcx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtsvifixjz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtuppiubjx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtngmixnur.html

TS:   path.extname("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtipsoxanw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.meibo888.top/Article/details/gtafcljsci.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtxuierwcn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtoclzpmlj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtdtoyxhbo.html

[F11] 复制与移动文件
来源：http://dali.guowangkeji.top/Article/details/gtqlvdpmxo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtgrtuqwly.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ydzc1.top/Article/details/gtxpssywyk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtfighaxxe.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtkqjszrvj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphfkdhhi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gotoacloud.top/Article/details/gtphdxcaff.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtipbzfzxq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhongyouzk.top/Article/details/gtrubiunix.html

[F12] CSV 读写
来源：http://dali.tian-w.cn/Article/details/gtgwcbzmcm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.pycfn.com/Article/details/gtyzecvmqp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tianlin.xyz/Article/details/gtznauieju.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ybcxt.top/Article/details/gtlgzmcktf.html

TS:   // 同上
来源：http://dali.ehwqpu.com/Article/details/gtpwmaqsnr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gzhubu.top/Article/details/gtsermnbbn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.fengsongda.top/Article/details/gtbvqjbmox.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj20258888.top/Article/details/gtbcbwysrr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shzxlz.cn/Article/details/gtogpsowqh.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtxtlikvci.html

G. 面向对象
来源：http://dali.cheryme.top/Article/details/gtuvxwjfiz.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtltyqkuyo.html

[G01] 定义类
来源：http://dali.yangfankeji.com/Article/details/gthjqlvcem.html

Py:   class User: pass
来源：http://dali.vqdsnc.cn/Article/details/gtcaymstfg.html

PHP:  class User {}
来源：http://dali.birdmap.top/Article/details/gthnnupwmx.html

JS:   class User {}
来源：http://dali.c1oappe.top/Article/details/gthlishqlm.html

TS:   class User { name: string = ""; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtywhmlreg.html

Java: class User {}
来源：http://dali.zycfv.cn/Article/details/gtweqkoaij.html

Go:   type User struct { Name string }
来源：http://dali.meibo888.top/Article/details/gtuwdlcjas.html

Ruby: class User; end
来源：http://dali.shuidangran.top/Article/details/gtqilkqqsf.html

C#:   class User {}
来源：http://dali.fengsongda.top/Article/details/gtjzamsnic.html

[G02] 构造函数
来源：http://dali.yonumen.top/Article/details/gtmhyrqihs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fengsongda.top/Article/details/gtkkwysgnj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenlongwang.top/Article/details/gtrjxqbfeq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtqyyqwmyl.html

TS:   constructor(public name: string) {}
来源：http://dali.sweek.top/Article/details/gtywqtlqof.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwzttsrp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hfpthk.cn/Article/details/gtjwqfkhje.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tianlin.xyz/Article/details/gtegfuijbn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonpuibbq.html

[G03] 实例属性
来源：http://dali.dianchejie.cn/Article/details/gtnesefqqb.html

Py:   self.name = "x"
来源：http://dali.316326.xyz/Article/details/gtouilqnww.html

PHP:  public string $name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtioijggfa.html

JS:   this.name = "x";
来源：http://dali.yj202588.top/Article/details/gtftbatqan.html

TS:   name: string = "x";
来源：http://dali.pycfn.com/Article/details/gtuablcbvz.html

Java: private String name;
来源：http://dali.dashuyun.cn/Article/details/gtwdimldqs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuetiantiany.cn/Article/details/gtupyilrfr.html

Ruby: @name = "x"
来源：http://dali.gogol.net.cn/Article/details/gtpjmeqbao.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jianghu66.top/Article/details/gtcaoeqlxk.html

[G04] 定义方法
来源：http://dali.pengpengdd.cyou/Article/details/gtuffjlrdf.html

Py:   def greet(self): return self.name
来源：http://dali.yueranfly.top/Article/details/gtiyvbmtsk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtxpfsjxqm.html

JS:   greet() { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtowulevzm.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gttcrynjjl.html

Java: String greet() { return name; }
来源：http://dali.yj20258.top/Article/details/gtzykaotpd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzlvilhws.html

Ruby: def greet; @name; end
来源：http://dali.yongpay.top/Article/details/gtfffogvhk.html

C#:   public string Greet() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gttncgevhk.html

[G05] 继承
来源：http://dali.aizwys.cn/Article/details/gtgajbequb.html

Py:   class Admin(User): pass
来源：http://dali.yuanzhike.top/Article/details/gtcurznxkz.html

PHP:  class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtulyagfxc.html

JS:   class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gteihsqxaj.html

TS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtjlymyxju.html

Java: class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gthenmnepz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj20258.top/Article/details/gtvxroqvsv.html

Ruby: class Admin < User; end
来源：http://dali.fengsongda.top/Article/details/gtbsfhyfuj.html

C#:   class Admin : User {}
来源：http://dali.vqdsnc.cn/Article/details/gtzmqjqsxm.html

[G06] 重写方法
来源：http://dali.cheryme.top/Article/details/gtgnurofgn.html

Py:   def greet(self): return "admin"
来源：http://dali.jqgfzy.top/Article/details/gtypvdntjo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtnqaudftk.html

JS:   greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtwwkwxbfd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtifqxiviu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtwewlhcmb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.feifeiyinyue.top/Article/details/gtswrlivil.html

Ruby: def greet; "admin"; end
来源：http://dali.zhongyouzk.top/Article/details/gtytmsasrn.html

C#:   public override string Greet() => "admin";
来源：http://dali.nwbrower.top/Article/details/gtxuxgrkkh.html

[G07] 调用父类方法
来源：http://dali.316326.xyz/Article/details/gtvpiijlik.html

Py:   super().greet()
来源：http://dali.mhx1999.top/Article/details/gtqbbyqukb.html

PHP:  parent::greet();
来源：http://dali.nwbrower.top/Article/details/gtcejebqdl.html

JS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gtadqsnylp.html

TS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtvaxqjipk.html

Java: super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gtbqpdhdig.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.meibo888.top/Article/details/gthvmdyino.html

Ruby: super
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphlofqcx.html

C#:   base.Greet();
来源：http://dali.9152youxi.cn/Article/details/gtcmxovxax.html

[G08] 静态方法与属性
来源：http://dali.yuxming.cn/Article/details/gtldpqojfe.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.snrcjt.cn/Article/details/gtzngwrftw.html

PHP:  public static function f() {}
来源：http://dali.gaohongyu789.top/Article/details/gthetjhwzl.html

JS:   static f() {}
来源：http://dali.tanke756.top/Article/details/gtolwlqxrv.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gtntcfckce.html

Java: static void f() {}
来源：http://dali.gotoacloud.top/Article/details/gtchgppxsw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.andypj.xyz/Article/details/gttjiuczkd.html

Ruby: def self.f; end
来源：http://dali.xinyue.icu/Article/details/gthdzhllsa.html

C#:   public static void F() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtgrfajrar.html

[G09] 接口 / 抽象类
来源：http://dali.yanxiufei.cn/Article/details/gtidtbthlb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shuidangran.top/Article/details/gtbtxoyxjo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zycfv.cn/Article/details/gtspzmgmeo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.mhx1999.top/Article/details/gtrnooaxvk.html

TS:   interface Shape { area(): number; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjondowi.html

Java: interface Shape { double area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtbtoqfzea.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yueranfly.top/Article/details/gttrztzibp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtwuytjtxj.html

C#:   interface IShape { double Area(); }
来源：http://dali.kuanghao11.cn/Article/details/gtbwmeghbo.html

[G10] 访问控制
来源：http://dali.snrcjt.cn/Article/details/gtmmhiirzu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jiagoushi.top/Article/details/gturywumgr.html

PHP:  public / protected / private
来源：http://dali.jianghu66.top/Article/details/gtyijtahve.html

JS:   #private 字段；其余公开
来源：http://dali.fzhhl.top/Article/details/gtfyllstia.html

TS:   public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtntablxaj.html

Java: public / protected / private / 默认包级
来源：http://dali.tianlin.xyz/Article/details/gtwfdcypjm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhoulong.xyz/Article/details/gtjazmbqwx.html

Ruby: public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gtqgylvcsz.html

C#:   public / protected / private / internal
来源：http://dali.jqgufenzy.top/Article/details/gtupetpbuo.html

[G11] getter / setter
来源：http://dali.0kj1m.cn/Article/details/gtxgunndxo.html

Py:   @property 与 @x.setter
来源：http://dali.gaohongyu789.top/Article/details/gtwilylvgc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gtlrkccvwl.html

JS:   get name() { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gtwgasiopj.html

TS:   get name(): string { return this._name; }
来源：http://dali.sweek.top/Article/details/gtvnjmiyhf.html

Java: public String getName() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtdxeurvpm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtmfufowzj.html

Ruby: attr_accessor :name
来源：http://dali.tianlin.xyz/Article/details/gtigjaiywj.html

C#:   public string Name { get; set; }
来源：http://dali.shzxlz.cn/Article/details/gtpuvhwhca.html

[G12] 对象转字符串
来源：http://dali.ydzc1.top/Article/details/gtpgojezmn.html

Py:   def __str__(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gtsbvpztnn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gthbggvqqu.html

JS:   toString() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gteodvvaos.html

TS:   toString(): string { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtatzttjtm.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtlwatawyk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtctwifiqm.html

Ruby: def to_s; @name; end
来源：http://dali.vqdsnc.cn/Article/details/gtokqmmcfm.html

C#:   public override string ToString() => Name;
来源：http://dali.jqgfzy.top/Article/details/gtzmkeyhmw.html

[G13] 判断对象类型
来源：http://dali.xylfe.cn/Article/details/gtwcdqybvj.html

Py:   isinstance(u, User)
来源：http://dali.xylfe.cn/Article/details/gtjdxqngcb.html

PHP:  $u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtzmjjgxwb.html

JS:   u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtzgzmbjcv.html

TS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gttriiachv.html

Java: u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtdqtqftpa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dianchejie.cn/Article/details/gtakyauvdc.html

Ruby: u.is_a?(User)
来源：http://dali.yj20258.top/Article/details/gtpavqygah.html

C#:   u is User
来源：http://dali.dianchejie.cn/Article/details/gtnkuomkzp.html

[G14] 数据类 / record
来源：http://dali.wangdashe.top/Article/details/gtnvfqbwzy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.andypj.xyz/Article/details/gthtmogioh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.iojbl.cn/Article/details/gtjgjnkzvr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yongpay.top/Article/details/gttkhfhvre.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj20258.top/Article/details/gttstmgmmb.html

Java: record User(String name, int age) {}
来源：http://dali.jinqigfzy.top/Article/details/gtikpvymze.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cheryme.top/Article/details/gtwowermcg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.kuanghao11.cn/Article/details/gtvjkdcfij.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258888.top/Article/details/gtupmmqejg.html

[G15] 枚举
来源：http://dali.tian-w.cn/Article/details/gtgyvcisdt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgufenzy.top/Article/details/gtycpqudhi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xinyue.icu/Article/details/gtobnzxxrv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.aibaodan.cn/Article/details/gtcpdaaiie.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gtsfflxajm.html

Java: enum Color { RED, GREEN }
来源：http://dali.yongpay.top/Article/details/gtmqebihbn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiqpcfysm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cheryme.top/Article/details/gtvbostsqa.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtvwpqjicj.html

[G16] 对象转数组 / 字典
来源：http://dali.yuanzhike.top/Article/details/gtorhjntys.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkqzjgmfl.html

PHP:  get_object_vars($obj);
来源：http://dali.sxryk.cn/Article/details/gtxaiqxkgz.html

JS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gtqpzsrybs.html

TS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gtqdbboffi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnqzz.top/Article/details/gtllsnhyza.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.dashuyun.cn/Article/details/gtmdqbakpb.html

Ruby: obj.instance_variables
来源：http://dali.jlsjyb.cn/Article/details/gtzovlyrqi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gttbdnuiri.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtkvankjqs.html

H. 异常与错误处理
来源：http://dali.zhongyouzk.top/Article/details/gttfzdfdqc.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtfuebhcxy.html

[H01] try / catch 基础
来源：http://dali.jyoumei.cn/Article/details/gtqmplgxsj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnnyxcdfd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.svipenyu.cn/Article/details/gtipgucaeg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gtigtfqrjs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.birdmap.top/Article/details/gtnixzmniy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sufxvd.cn/Article/details/gtcxhypfnd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.dashuyun.cn/Article/details/gtqshxbgej.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fengsongda.top/Article/details/gtyebbrwia.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tian-w.cn/Article/details/gtgpcfotat.html

[H02] finally / ensure 收尾
来源：http://dali.zhoulong.xyz/Article/details/gtbudetusc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.vqdsnc.cn/Article/details/gtwjxsdxic.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtngziawri.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtegnsxtsk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtgthieogp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtpfbhpfyl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.iojbl.cn/Article/details/gtaisimquk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.andypj.xyz/Article/details/gtkjmhkabm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtcryjmjcj.html

[H03] 主动抛出异常
来源：http://dali.xuetiantiany.cn/Article/details/gtwyvkwlsi.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuanzhike.top/Article/details/gtqlejapih.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtkidpxibo.html

JS:   throw new Error("错误信息");
来源：http://dali.cashguo.top/Article/details/gtdbocpebg.html

TS:   throw new Error("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtnrtsryfp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtofoklujj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhongyouzk.top/Article/details/gtqyhtyhjn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhixingplan.top/Article/details/gtrhzhfjqf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtfzannzol.html

[H04] 自定义异常类型
来源：http://dali.birdmap.top/Article/details/gtkvfuxaxo.html

Py:   class MyError(Exception): pass
来源：http://dali.feifeiyinyue.top/Article/details/gtezyprqsz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gtgmhwuigf.html

JS:   class MyError extends Error {}
来源：http://dali.hongshengwenyu.top/Article/details/gtkmblnsvi.html

TS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxhfcsmj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gtqgfchmcd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.kuanghao11.cn/Article/details/gteapabxjb.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigfzy.top/Article/details/gtyjyurpay.html

C#:   class MyException : Exception {}
来源：http://dali.chenzaomai.com/Article/details/gtxidklirm.html

[H05] 捕获特定类型
来源：http://dali.yueranfly.top/Article/details/gtvoixjwju.html

Py:   except ValueError as e:
来源：http://dali.daria6918.cn/Article/details/gtngnyodin.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jyoumei.cn/Article/details/gtnnnbkzfc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gtzxbynoke.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.c1oappe.top/Article/details/gtgrgzkqga.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnqzz.top/Article/details/gthpuoqnzu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guowangkeji.top/Article/details/gtnitjfusa.html

Ruby: rescue ArgumentError => e
来源：http://dali.pengpengdd.cyou/Article/details/gtrihqeiip.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gogol.net.cn/Article/details/gtyqdtvigq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shzxlz.cn/Article/details/gtzzzynpjg.html

Py:   value = d.get("k") or default
来源：http://dali.yonumen.top/Article/details/gtzdeoaeni.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.andypj.xyz/Article/details/gtjydlraix.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yongpay.top/Article/details/gtakumengm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gtxnivyype.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gzhubu.top/Article/details/gtihsllhla.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenzaomai.com/Article/details/gtrmmibygu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhengqikj.top/Article/details/gtexjjgepg.html

C#:   obj?.A?.B ?? default
来源：http://dali.0kj1m.cn/Article/details/gtftivzxuj.html

[H07] 断言
来源：http://dali.dashuyun.cn/Article/details/gtauobzpxd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.snrcjt.cn/Article/details/gtqlxurimj.html

PHP:  assert($x > 0);
来源：http://dali.havefunace.top/Article/details/gtmkshnxqq.html

JS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gttxegxvfi.html

TS:   console.assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtiaajpfui.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cdnleiting.top/Article/details/gtxxswhtpq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aizwys.cn/Article/details/gtedfaumcb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljdmiyao.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtiwevqavn.html

[H08] 获取错误信息与堆栈
来源：http://dali.cqqwz.cn/Article/details/gtwxqhhoyj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shangyingyoupin.top/Article/details/gtwldtlnge.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cdnleiting.top/Article/details/gtgpbbcxkq.html

JS:   e.message;  e.stack
来源：http://dali.guowangkeji.top/Article/details/gtekruvlns.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hysaishi.cn/Article/details/gtksazlquf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuanzhike.top/Article/details/gtlofftfox.html

Go:   err.Error()
来源：http://dali.mhx1999.top/Article/details/gtxqxfpizk.html

Ruby: e.message;  e.backtrace
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfiowoxe.html

C#:   e.Message;  e.StackTrace
来源：http://dali.wangshuangyany.cn/Article/details/gtxvciybrh.html

[H09] 带错误码的异常
来源：http://dali.mhx1999.top/Article/details/gthenmvjje.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gogol.net.cn/Article/details/gterryveoe.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dashuyun.cn/Article/details/gtgwxljvmi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.birdmap.top/Article/details/gtpqtififb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.havefunace.top/Article/details/gtzocmkftn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuxming.cn/Article/details/gtvkrorjns.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yonumen.top/Article/details/gtiqzlytea.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuetiantiany.cn/Article/details/gtapgaxsaw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ydzc1.top/Article/details/gtvfjamarp.html

[H10] 资源自动释放
来源：http://dali.cheryme.top/Article/details/gtqjthgiyb.html


<!-- 参考信息 -->