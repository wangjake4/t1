代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.sysykeji.top/Article/details/gtppmgqrrl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dianchejie.cn/Article/details/gtflmjrvco.html

PHP:  file_exists("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtmtjegcmo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtdmhohyhu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtukdilnzs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtpcbhpjus.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yueranfly.top/Article/details/gtwpfdkauj.html

Ruby: File.exist?("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtahglwbxs.html

C#:   File.Exists("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtacvsmqlg.html

[F06] 删除文件
来源：http://dali.shuidangran.top/Article/details/gtimmyucwf.html

Py:   os.remove("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtkjyclvqy.html

PHP:  unlink("a.txt");
来源：http://dali.cashguo.top/Article/details/gtjvgcslud.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtysngpkoo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzoekdbhw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gttqolicvy.html

Go:   os.Remove("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtsozkpsrx.html

Ruby: File.delete("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtqogcxrib.html

C#:   File.Delete("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtzuuhqhxv.html

[F07] 创建目录（含多级）
来源：http://dali.zdqjudy.top/Article/details/gtldywyizy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyrtbolut.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.quarkkingdee.top/Article/details/gtajdbeykw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gtdbckzzex.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenlongwang.top/Article/details/gtitqeolry.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.kuanghao11.cn/Article/details/gtnevyemnk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ybcxt.top/Article/details/gtyddphnhi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shangyingyoupin.top/Article/details/gteyekhodm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jianghu66.top/Article/details/gtuwqfmdqt.html

[F08] 遍历目录
来源：http://dali.svipenyu.cn/Article/details/gtrcixdfyt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgfzy.top/Article/details/gtpezvjtzg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.havefunace.top/Article/details/gtaicdbubw.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzpjyeunf.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gtfsajufea.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gtgkgegkzk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtvhyfzjph.html

Ruby: Dir.children("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmfvrovqn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuxming.cn/Article/details/gtopludnxi.html

[F09] 获取文件大小
来源：http://dali.birdmap.top/Article/details/gtzjgnwvau.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgrzpdvj.html

PHP:  filesize("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtlbqpecuo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.guannengcc.top/Article/details/gtucfxcxdu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hfpthk.cn/Article/details/gturggozul.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtptsegfve.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.c1oappe.top/Article/details/gtxckccwwa.html

Ruby: File.size("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtvhnjlohx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ehwqpu.com/Article/details/gtzdtiejaj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.mhx1999.top/Article/details/gtyfozzhgn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtirzwopkq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yueranfly.top/Article/details/gtcxtjqnse.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtztrdagdc.html

TS:   path.extname("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtkmmpbsel.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.haohaochexian.top/Article/details/gtzbkaoxrm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtkpspsjry.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtvdvkpatl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtqtiryjzu.html

[F11] 复制与移动文件
来源：http://dali.fzhhl.top/Article/details/gttgqqzqxy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtmvzhvzzo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yuanzhike.top/Article/details/gtnkrnvolf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtknhcdcyk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtruamzbzm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.wangdashe.top/Article/details/gtakutnbuo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ivvv.top/Article/details/gtuptlgiyc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtbfuijnin.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ydzc1.top/Article/details/gtcpdbplma.html

[F12] CSV 读写
来源：http://dali.birdmap.top/Article/details/gthlxdahno.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhoulong.xyz/Article/details/gtmwaxlqxc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenlongwang.top/Article/details/gthnihpebi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinqigfzy.top/Article/details/gthzegabwb.html

TS:   // 同上
来源：http://dali.yangfankeji.com/Article/details/gtfhddrpto.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenjidiqi.icu/Article/details/gtnwtprhrz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ivvv.top/Article/details/gtfumthjou.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ppjwa.cn/Article/details/gtgouzwfvt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gaohongyu789.top/Article/details/gtaznkiamw.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtysaxtmcq.html

G. 面向对象
来源：http://dali.meibo888.top/Article/details/gtmfjlvukp.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gttqbwkrrl.html

[G01] 定义类
来源：http://dali.sufxvd.cn/Article/details/gtnsbtqtla.html

Py:   class User: pass
来源：http://dali.cucudq.cn/Article/details/gtgxnugbep.html

PHP:  class User {}
来源：http://dali.wangdashe.top/Article/details/gtutacvafg.html

JS:   class User {}
来源：http://dali.aizwys.cn/Article/details/gtbxiurfvf.html

TS:   class User { name: string = ""; }
来源：http://dali.yanxiufei.cn/Article/details/gtfxddrsme.html

Java: class User {}
来源：http://dali.cucudq.cn/Article/details/gtruvaeeep.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthnmhzcmy.html

Ruby: class User; end
来源：http://dali.ybcxt.top/Article/details/gtgavcowbw.html

C#:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gtbofmefyj.html

[G02] 构造函数
来源：http://dali.gaohongyu789.top/Article/details/gtjujvvdqi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yuxming.cn/Article/details/gtorwuspws.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gttsencqkd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hnqzz.top/Article/details/gtwyzytmmi.html

TS:   constructor(public name: string) {}
来源：http://dali.tanke756.top/Article/details/gtrfkzrqyh.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gtteeubeds.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sxryk.cn/Article/details/gtcvhyondg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fengsongda.top/Article/details/gtglnsjsvt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtuazwcnoz.html

[G03] 实例属性
来源：http://dali.yj20258.top/Article/details/gtqsqiwhwb.html

Py:   self.name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gthapyysib.html

PHP:  public string $name = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtnysbjjsh.html

JS:   this.name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gthiuilepz.html

TS:   name: string = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpsfpwene.html

Java: private String name;
来源：http://dali.sufxvd.cn/Article/details/gtigklgpfr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yvedp.cn/Article/details/gtlifruykz.html

Ruby: @name = "x"
来源：http://dali.dianchejie.cn/Article/details/gtnnhgcixo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxinkj.top/Article/details/gtmwfhsczm.html

[G04] 定义方法
来源：http://dali.quarkkingdee.top/Article/details/gtxfkxlixe.html

Py:   def greet(self): return self.name
来源：http://dali.birdmap.top/Article/details/gtywnyshqu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gttidtvhiz.html

JS:   greet() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gtouosujva.html

TS:   greet(): string { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtokkaeshd.html

Java: String greet() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtuxjxkvyf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gtslsvqice.html

Ruby: def greet; @name; end
来源：http://dali.birdmap.top/Article/details/gtgyjzocrw.html

C#:   public string Greet() => Name;
来源：http://dali.jyoumei.cn/Article/details/gtavuzgxgm.html

[G05] 继承
来源：http://dali.cheryme.top/Article/details/gtrozxpbkh.html

Py:   class Admin(User): pass
来源：http://dali.aibaodan.cn/Article/details/gtntfgodzh.html

PHP:  class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtaxpqiqwh.html

JS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtudnayixk.html

TS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtzbraisjm.html

Java: class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjamlklik.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cdnleiting.top/Article/details/gtjggdmitr.html

Ruby: class Admin < User; end
来源：http://dali.tian-w.cn/Article/details/gtybmlbydb.html

C#:   class Admin : User {}
来源：http://dali.zhengqikj.top/Article/details/gtkfdtczou.html

[G06] 重写方法
来源：http://dali.feifeiyinyue.top/Article/details/gtnponhecv.html

Py:   def greet(self): return "admin"
来源：http://dali.zhongyouzk.top/Article/details/gtutpnwafg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtwqljuvdw.html

JS:   greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtednhianq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtgnxlsypx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtpetxsxhr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.kuanghao11.cn/Article/details/gttelmqtfe.html

Ruby: def greet; "admin"; end
来源：http://dali.shuidangran.top/Article/details/gtimuemykn.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnqzz.top/Article/details/gtmgtgjsbr.html

[G07] 调用父类方法
来源：http://dali.svipenyu.cn/Article/details/gtmqxpmbpu.html

Py:   super().greet()
来源：http://dali.smart0.xyz/Article/details/gtrifahaml.html

PHP:  parent::greet();
来源：http://dali.hnqzz.top/Article/details/gtvrmbihqc.html

JS:   super.greet();
来源：http://dali.sxryk.cn/Article/details/gtcdaxcznt.html

TS:   super.greet();
来源：http://dali.hfpthk.cn/Article/details/gtvtwvkppx.html

Java: super.greet();
来源：http://dali.jianghu66.top/Article/details/gtqcgvcqgh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.quarkkingdee.top/Article/details/gtgqvcoppp.html

Ruby: super
来源：http://dali.fzhhl.top/Article/details/gtswknmzqt.html

C#:   base.Greet();
来源：http://dali.mhx1999.top/Article/details/gthqvgdutq.html

[G08] 静态方法与属性
来源：http://dali.guowangkeji.top/Article/details/gtegeptegd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangdashe.top/Article/details/gtyxaaixbx.html

PHP:  public static function f() {}
来源：http://dali.aibaodan.cn/Article/details/gtttwbltra.html

JS:   static f() {}
来源：http://dali.wangdashe.top/Article/details/gtsoprrhzw.html

TS:   static f(): void {}
来源：http://dali.wangdashe.top/Article/details/gtrynrtabt.html

Java: static void f() {}
来源：http://dali.nanxuanxn.top/Article/details/gtwomquxgl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yuanzhike.top/Article/details/gtlgvxsqxs.html

Ruby: def self.f; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkgyzklqr.html

C#:   public static void F() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtentkbpzv.html

[G09] 接口 / 抽象类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtownviorp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.andypj.xyz/Article/details/gtlpdtsmkg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtexolvldm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yueranfly.top/Article/details/gtwwtdmltl.html

TS:   interface Shape { area(): number; }
来源：http://dali.316326.xyz/Article/details/gtkefpamii.html

Java: interface Shape { double area(); }
来源：http://dali.haohaochexian.top/Article/details/gtcuuvepjx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxuanxn.top/Article/details/gtnevttkfh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.pycfn.com/Article/details/gtrnysgwiz.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnqzz.top/Article/details/gtfododpwz.html

[G10] 访问控制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdzhbidnw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jianghu66.top/Article/details/gtjwjlqgxm.html

PHP:  public / protected / private
来源：http://dali.yonumen.top/Article/details/gtkxokhefc.html

JS:   #private 字段；其余公开
来源：http://dali.yj20258888.top/Article/details/gtfahnbptt.html

TS:   public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtkudvrzcr.html

Java: public / protected / private / 默认包级
来源：http://dali.nwbrower.top/Article/details/gtbabchkrf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.haohaochexian.top/Article/details/gtzcyghvon.html

Ruby: public / protected / private
来源：http://dali.meibo888.top/Article/details/gtcmdtrdar.html

C#:   public / protected / private / internal
来源：http://dali.daria6918.cn/Article/details/gtwiswmxsw.html

[G11] getter / setter
来源：http://dali.shangyingyoupin.top/Article/details/gtunotpweq.html

Py:   @property 与 @x.setter
来源：http://dali.ppjwa.cn/Article/details/gtodzyuvrz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gtxpbtvflw.html

JS:   get name() { return this._name; }
来源：http://dali.yonumen.top/Article/details/gtaxueuagx.html

TS:   get name(): string { return this._name; }
来源：http://dali.svipenyu.cn/Article/details/gtckaolnkx.html

Java: public String getName() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtixggmwiv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtccehycyr.html

Ruby: attr_accessor :name
来源：http://dali.jinqigufen.top/Article/details/gtbdsdqnow.html

C#:   public string Name { get; set; }
来源：http://dali.ppjwa.cn/Article/details/gthzymawlt.html

[G12] 对象转字符串
来源：http://dali.dianchejie.cn/Article/details/gtdxsmmugj.html

Py:   def __str__(self): return self.name
来源：http://dali.9152youxi.cn/Article/details/gtbkfdnufz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gttrebjgqk.html

JS:   toString() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtvudsvfis.html

TS:   toString(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtjiefedyx.html

Java: @Override public String toString() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtpcnpkrvn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpuhdisgk.html

Ruby: def to_s; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gtvgggimal.html

C#:   public override string ToString() => Name;
来源：http://dali.hywenlv.cn/Article/details/gtxfzxikrj.html

[G13] 判断对象类型
来源：http://dali.daxiang520.top/Article/details/gtfvksrtcj.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gtkfwloztd.html

PHP:  $u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtdrypxndy.html

JS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtrpcrzpjh.html

TS:   u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtabgjuicj.html

Java: u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtjqxjpnat.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gthdhpltmf.html

Ruby: u.is_a?(User)
来源：http://dali.xylfe.cn/Article/details/gtjbuyvaxb.html

C#:   u is User
来源：http://dali.nwbrower.top/Article/details/gtymwagshc.html

[G14] 数据类 / record
来源：http://dali.yvedp.cn/Article/details/gtthsbmdhl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuetiantiany.cn/Article/details/gtbiangmhv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ydzc1.top/Article/details/gtboxhfwka.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.svipenyu.cn/Article/details/gtgpdbstkb.html

TS:   type User = { name: string; age: number };
来源：http://dali.sufxvd.cn/Article/details/gtieyhxjxm.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtaupzdngw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ppjwa.cn/Article/details/gtnsgsvstz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zycfv.cn/Article/details/gtafjxxyxw.html

C#:   record User(string Name, int Age);
来源：http://dali.xinyue.icu/Article/details/gtxcjuumht.html

[G15] 枚举
来源：http://dali.chenzaomai.com/Article/details/gtbntrgsff.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangdashe.top/Article/details/gtsjktsofg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvpmajmmw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigfzy.top/Article/details/gterebygkp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtlskruozq.html

Java: enum Color { RED, GREEN }
来源：http://dali.shzxlz.cn/Article/details/gtmqosstzw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuanzx.com/Article/details/gtmdwcnohk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.havefunace.top/Article/details/gtswpbaboh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258888.top/Article/details/gtyhounsww.html

[G16] 对象转数组 / 字典
来源：http://dali.yueranfly.top/Article/details/gtlrnvxpvt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gaohongyu789.top/Article/details/gtvssdvfgp.html

PHP:  get_object_vars($obj);
来源：http://dali.zycfv.cn/Article/details/gtenubiivm.html

JS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gtnqatogeb.html

TS:   Object.entries(obj)
来源：http://dali.zycfv.cn/Article/details/gtojaqbvfo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hammf.cn/Article/details/gtewebampf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.0kj1m.cn/Article/details/gtbtjfobar.html

Ruby: obj.instance_variables
来源：http://dali.zhengqikj.top/Article/details/gtjtbumjkp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gtbftiaxrj.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtonvxhreo.html

H. 异常与错误处理
来源：http://dali.hywenlv.cn/Article/details/gtyzfnurmx.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtsiivcqbm.html

[H01] try / catch 基础
来源：http://dali.hongshengwenyu.top/Article/details/gtsrrozfpf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.c1oappe.top/Article/details/gtwrjvvhyc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daria6918.cn/Article/details/gtexriqfuf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gttshoastc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpxtjozcm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gaohongyu789.top/Article/details/gtpxwosfge.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zdqjudy.top/Article/details/gthkzejtmq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cqqwz.cn/Article/details/gttdtheoic.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shzxlz.cn/Article/details/gttatfjcxe.html

[H02] finally / ensure 收尾
来源：http://dali.xziqi.cn/Article/details/gtxmltmkhn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ppjwa.cn/Article/details/gtxtwfwrcp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgfgwzzrx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtiztohlvx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gttbxiwyfd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtcjgdjrcm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj202588.top/Article/details/gtorljhvbt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtigfztrkv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtqcuimjfv.html

[H03] 主动抛出异常
来源：http://dali.daria6918.cn/Article/details/gtoofwpogu.html

Py:   raise ValueError("错误信息")
来源：http://dali.jlsjyb.cn/Article/details/gtawgcepth.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtqhzjbicg.html

JS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gthvswggin.html

TS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtexxdxaih.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtafwqefdj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hfpthk.cn/Article/details/gtnrwbjjzo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnxiangtu.top/Article/details/gtkkfgoavh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtnulpbqpf.html

[H04] 自定义异常类型
来源：http://dali.nanxuanxn.top/Article/details/gtrdauorfz.html

Py:   class MyError(Exception): pass
来源：http://dali.c1oappe.top/Article/details/gtwlgpxbbz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gtintqakic.html

JS:   class MyError extends Error {}
来源：http://dali.hongshengwenyu.top/Article/details/gtivipwxhg.html

TS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gtteweaten.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gtkwavsykz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pengpengdd.cyou/Article/details/gtjwmjvtxv.html

Ruby: class MyError < StandardError; end
来源：http://dali.tianlin.xyz/Article/details/gtfsczlshb.html

C#:   class MyException : Exception {}
来源：http://dali.sweek.top/Article/details/gtcrczowib.html

[H05] 捕获特定类型
来源：http://dali.316326.xyz/Article/details/gtqpqgpeql.html

Py:   except ValueError as e:
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiyxhzili.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.pengpengdd.cyou/Article/details/gtevqjvzqe.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gtyhswrfju.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhoulong.xyz/Article/details/gtebejlogo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hfpthk.cn/Article/details/gtfyjhjtix.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yvedp.cn/Article/details/gtwacmldih.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhixingplan.top/Article/details/gtqjapaaam.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtofdozbsj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hysaishi.cn/Article/details/gtynbckfoz.html

Py:   value = d.get("k") or default
来源：http://dali.vqdsnc.cn/Article/details/gtrdqcticv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yuanzhike.top/Article/details/gthitgxjjc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gtetfqikxs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gtmedgklfl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.guowangkeji.top/Article/details/gtnegtrahm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nanxuanxn.top/Article/details/gttmirxzdl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cqqwz.cn/Article/details/gtrotchiss.html

C#:   obj?.A?.B ?? default
来源：http://dali.jyoumei.cn/Article/details/gtizdvdrwn.html

[H07] 断言
来源：http://dali.hnxiangtu.top/Article/details/gtbxsnqhwp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258.top/Article/details/gtwjszacxr.html

PHP:  assert($x > 0);
来源：http://dali.cucudq.cn/Article/details/gtuchyuwqa.html

JS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gttjguqssa.html

TS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtrbwjlkcy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cashguo.top/Article/details/gtctinmuvf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangtech.top/Article/details/gtrcmepukp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hysaishi.cn/Article/details/gtvgkwnztw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gtsuezrjzf.html

[H08] 获取错误信息与堆栈
来源：http://dali.yanxiufei.cn/Article/details/gtrpalxmeu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj202588.top/Article/details/gtsmrdqbur.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yueranfly.top/Article/details/gtzxkhxaxi.html

JS:   e.message;  e.stack
来源：http://dali.zycfv.cn/Article/details/gtlspcvspa.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.vqdsnc.cn/Article/details/gtogmzllkx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqobpfctq.html

Go:   err.Error()
来源：http://dali.jyoumei.cn/Article/details/gtuzexfydl.html

Ruby: e.message;  e.backtrace
来源：http://dali.9152youxi.cn/Article/details/gtxovonsym.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj202588.top/Article/details/gtwhzghpae.html

[H09] 带错误码的异常
来源：http://dali.zhengqikj.top/Article/details/gtknafsowe.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.birdmap.top/Article/details/gtuelcqagc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yueranfly.top/Article/details/gtqxveldua.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hammf.cn/Article/details/gtxnorhwji.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.bjfxy.top/Article/details/gtdfihkbvh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yvedp.cn/Article/details/gtaxndyutw.html


<!-- 参考信息 -->