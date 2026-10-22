代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.jqgfzy.top/Article/details/gtflnxuzsk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shangyingyoupin.top/Article/details/gtrlasdcuq.html

PHP:  file_exists("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtfbdlpnyp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtfltbpfyp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtklknpolt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtmsbqonbf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhoulong.xyz/Article/details/gtyinzwgyw.html

Ruby: File.exist?("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtewwwbmvf.html

C#:   File.Exists("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtzoggvavf.html

[F06] 删除文件
来源：http://dali.wangshuangyany.cn/Article/details/gtjruztbyq.html

Py:   os.remove("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtwiensnjj.html

PHP:  unlink("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gttlskfoxx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtzjacxyxa.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtqpbnnudp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtbrdzhgoa.html

Go:   os.Remove("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtbjozrhgv.html

Ruby: File.delete("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtipuxoqdu.html

C#:   File.Delete("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gttthawtpg.html

[F07] 创建目录（含多级）
来源：http://dali.yangfankeji.com/Article/details/gthsicwalg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhoulong.xyz/Article/details/gttljspjni.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.dianchejie.cn/Article/details/gtfcvcnbka.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.bjfxy.top/Article/details/gtyexbseuc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gtxmecuqry.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.mhx1999.top/Article/details/gtkmbehlmj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ehwqpu.com/Article/details/gturnbkwvm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.quarkkingdee.top/Article/details/gtptxmhejm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hnqzz.top/Article/details/gttxyvlbst.html

[F08] 遍历目录
来源：http://dali.aibaodan.cn/Article/details/gtugkupusp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhixingplan.top/Article/details/gtfcokvklh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.havefunace.top/Article/details/gtudrtkuek.html

JS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gtvtwcuhjb.html

TS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gttqcgnmlf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.snrcjt.cn/Article/details/gtbvdfliec.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.havefunace.top/Article/details/gthcwpdwwn.html

Ruby: Dir.children("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtguudfpyk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuanzhike.top/Article/details/gtgncmculg.html

[F09] 获取文件大小
来源：http://dali.yanxiufei.cn/Article/details/gtccfgcuge.html

Py:   os.path.getsize("a.txt")
来源：http://dali.meibo888.top/Article/details/gtkiyjjgwy.html

PHP:  filesize("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtvnkrwlam.html

JS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gtrauycgzk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gtfebjpyxc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtylinwmzq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigfzy.top/Article/details/gtvcyvtwhk.html

Ruby: File.size("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtnbpfsnuw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shangyingyoupin.top/Article/details/gtlilgnexp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jiagoushi.top/Article/details/gtdslukghr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtukaxkfqe.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258.top/Article/details/gtaxshumev.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtlzzafphq.html

TS:   path.extname("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtbnmuugtc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenlongwang.top/Article/details/gtvzebpfvx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtzbtdehax.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtsvloygoq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtqvigurlw.html

[F11] 复制与移动文件
来源：http://dali.xuanzx.com/Article/details/gtieccwxlp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtwcptinvf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtmlnsbgdw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtskytaayb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtocpnbkid.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.c1oappe.top/Article/details/gtdahiawra.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.svipenyu.cn/Article/details/gtmqhglmeo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtfmahzlbo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.fengsongda.top/Article/details/gtvgqusoor.html

[F12] CSV 读写
来源：http://dali.yongpay.top/Article/details/gtiizwmwgh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shuidangran.top/Article/details/gtzekkjewa.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yangfankeji.com/Article/details/gtlwqplkzl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.iojbl.cn/Article/details/gtkozwwcbg.html

TS:   // 同上
来源：http://dali.tanke756.top/Article/details/gtnxuhlhgt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.birdmap.top/Article/details/gttzvpengc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.guannengcc.top/Article/details/gtkjqpuzjr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hongshengwenyu.top/Article/details/gtuhiwazuk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.daria6918.cn/Article/details/gtbnqepben.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtjygjfowb.html

G. 面向对象
来源：http://dali.ivvv.top/Article/details/gtktclbcsq.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gttcesjofr.html

[G01] 定义类
来源：http://dali.yanxiufei.cn/Article/details/gtxoywwvby.html

Py:   class User: pass
来源：http://dali.cucudq.cn/Article/details/gtafemwips.html

PHP:  class User {}
来源：http://dali.gogol.net.cn/Article/details/gtxvpxmyvd.html

JS:   class User {}
来源：http://dali.haohaochexian.top/Article/details/gtlnbqgkhe.html

TS:   class User { name: string = ""; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnkcnvdcw.html

Java: class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtfbluekyi.html

Go:   type User struct { Name string }
来源：http://dali.hnxiangtu.top/Article/details/gtcneefkly.html

Ruby: class User; end
来源：http://dali.yj20258.top/Article/details/gtgpakryyx.html

C#:   class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtbypyicay.html

[G02] 构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoopirimf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhongyouzk.top/Article/details/gteyveselh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sufxvd.cn/Article/details/gttfpjjsnq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zycfv.cn/Article/details/gtppzjcadt.html

TS:   constructor(public name: string) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtowvkbtny.html

Java: User(String name) { this.name = name; }
来源：http://dali.cqqwz.cn/Article/details/gtgzdbitac.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthtzpbzgj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aibaodan.cn/Article/details/gtsvabhbhv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.havefunace.top/Article/details/gtxswstusx.html

[G03] 实例属性
来源：http://dali.yanxiufei.cn/Article/details/gtajppkhft.html

Py:   self.name = "x"
来源：http://dali.zhongyouzk.top/Article/details/gtrmxlqqxu.html

PHP:  public string $name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtglbtwsmv.html

JS:   this.name = "x";
来源：http://dali.hammf.cn/Article/details/gtrqmdfcnh.html

TS:   name: string = "x";
来源：http://dali.c1oappe.top/Article/details/gtluaztizs.html

Java: private String name;
来源：http://dali.tianlin.xyz/Article/details/gtbazuusbt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aibaodan.cn/Article/details/gtjodetixc.html

Ruby: @name = "x"
来源：http://dali.xinyue.icu/Article/details/gtpculvvto.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guowangkeji.top/Article/details/gtxauczxtr.html

[G04] 定义方法
来源：http://dali.yongpay.top/Article/details/gtjpgkjraw.html

Py:   def greet(self): return self.name
来源：http://dali.havefunace.top/Article/details/gtbqkhjkiw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gtyaqayzab.html

JS:   greet() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtrmoerhtm.html

TS:   greet(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gtcwuqcoru.html

Java: String greet() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtnnkmwdat.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gtnenoaacb.html

Ruby: def greet; @name; end
来源：http://dali.yuxming.cn/Article/details/gtphktkibw.html

C#:   public string Greet() => Name;
来源：http://dali.chenzaomai.com/Article/details/gtzwknadtx.html

[G05] 继承
来源：http://dali.snrcjt.cn/Article/details/gtcraevuci.html

Py:   class Admin(User): pass
来源：http://dali.ydzc1.top/Article/details/gtahqaflgy.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gttdoceeym.html

JS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gthopzykkm.html

TS:   class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtojuqnosz.html

Java: class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtxtempsfo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.fengsongda.top/Article/details/gtrfhsgvae.html

Ruby: class Admin < User; end
来源：http://dali.jinqigfzy.top/Article/details/gtimiirqkv.html

C#:   class Admin : User {}
来源：http://dali.jianghu66.top/Article/details/gtsljcrivz.html

[G06] 重写方法
来源：http://dali.cashguo.top/Article/details/gtqpmxvfrc.html

Py:   def greet(self): return "admin"
来源：http://dali.yueranfly.top/Article/details/gtybpjfkwu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtomakximq.html

JS:   greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gthfcvfmsp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtaskqnrbb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtuzhnviif.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zdqjudy.top/Article/details/gtomjmgaje.html

Ruby: def greet; "admin"; end
来源：http://dali.cdnleiting.top/Article/details/gtugxijfxw.html

C#:   public override string Greet() => "admin";
来源：http://dali.cdnleiting.top/Article/details/gtplyclqxf.html

[G07] 调用父类方法
来源：http://dali.hysaishi.cn/Article/details/gtqpehtrrv.html

Py:   super().greet()
来源：http://dali.jinqigufen.top/Article/details/gtebcbvfpd.html

PHP:  parent::greet();
来源：http://dali.yanxiufei.cn/Article/details/gtevhrnbwn.html

JS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtwbqzrapw.html

TS:   super.greet();
来源：http://dali.hfpthk.cn/Article/details/gtmcvapczm.html

Java: super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtzhpwaxuf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ehwqpu.com/Article/details/gtlzlzdbzv.html

Ruby: super
来源：http://dali.chenzaomai.com/Article/details/gtroanlxws.html

C#:   base.Greet();
来源：http://dali.daxiang520.top/Article/details/gteoihbiid.html

[G08] 静态方法与属性
来源：http://dali.ppjwa.cn/Article/details/gtdkuslqku.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgfzy.top/Article/details/gtzmnowygv.html

PHP:  public static function f() {}
来源：http://dali.tanke756.top/Article/details/gtlcaspdfh.html

JS:   static f() {}
来源：http://dali.yongpay.top/Article/details/gttmwxdptk.html

TS:   static f(): void {}
来源：http://dali.daxiang520.top/Article/details/gtyyzxzmuz.html

Java: static void f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtjdixoutm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhoulong.xyz/Article/details/gttthhiytw.html

Ruby: def self.f; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtporxqkmq.html

C#:   public static void F() {}
来源：http://dali.fzhhl.top/Article/details/gtwtepavcu.html

[G09] 接口 / 抽象类
来源：http://dali.chenzaomai.com/Article/details/gtxwvqjgex.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhengqikj.top/Article/details/gtoufketwf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuetiantiany.cn/Article/details/gtzivuwekg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xuetiantiany.cn/Article/details/gtvvnkunae.html

TS:   interface Shape { area(): number; }
来源：http://dali.sxryk.cn/Article/details/gtgxvnakqb.html

Java: interface Shape { double area(); }
来源：http://dali.guowangkeji.top/Article/details/gtuzxjwfrd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.vqdsnc.cn/Article/details/gtjsfiqotq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj202588.top/Article/details/gtshbwkgli.html

C#:   interface IShape { double Area(); }
来源：http://dali.shuidangran.top/Article/details/gtxojtikmw.html

[G10] 访问控制
来源：http://dali.vqdsnc.cn/Article/details/gtjrjqgvpy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tianlin.xyz/Article/details/gtcnykurhi.html

PHP:  public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtpfqpejmb.html

JS:   #private 字段；其余公开
来源：http://dali.jianghu66.top/Article/details/gthnjctkbr.html

TS:   public / protected / private
来源：http://dali.yj20258888.top/Article/details/gthzwpomfg.html

Java: public / protected / private / 默认包级
来源：http://dali.jinghuilouyu.cn/Article/details/gtytdmauhx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daria6918.cn/Article/details/gtkbsffcaa.html

Ruby: public / protected / private
来源：http://dali.ivvv.top/Article/details/gtgtnbthuu.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gtybqppgwb.html

[G11] getter / setter
来源：http://dali.ydzc1.top/Article/details/gttwxkyvta.html

Py:   @property 与 @x.setter
来源：http://dali.hnxiangtu.top/Article/details/gtojqukcxd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gthzhshaul.html

JS:   get name() { return this._name; }
来源：http://dali.yonumen.top/Article/details/gtqgysnjtb.html

TS:   get name(): string { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gtvwqomokw.html

Java: public String getName() { return name; }
来源：http://dali.jianghu66.top/Article/details/gtlnqgbpry.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvsatbvr.html

Ruby: attr_accessor :name
来源：http://dali.yj20258.top/Article/details/gtvtslboci.html

C#:   public string Name { get; set; }
来源：http://dali.fengsongda.top/Article/details/gtvzpftasg.html

[G12] 对象转字符串
来源：http://dali.vqdsnc.cn/Article/details/gtsmdtiqal.html

Py:   def __str__(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gtlmazwusj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtjdnhkyki.html

JS:   toString() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtwjsbphtb.html

TS:   toString(): string { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtnsyjybzt.html

Java: @Override public String toString() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtocswdsfu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gtplggbeoq.html

Ruby: def to_s; @name; end
来源：http://dali.jianghu66.top/Article/details/gttnxyrwas.html

C#:   public override string ToString() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gtlguybziu.html

[G13] 判断对象类型
来源：http://dali.jinqigfzy.top/Article/details/gttpdubriz.html

Py:   isinstance(u, User)
来源：http://dali.fzhhl.top/Article/details/gtuusbyeqm.html

PHP:  $u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtgiqegcsw.html

JS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtzbikbzlc.html

TS:   u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtyyzytdbn.html

Java: u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtozoczvjj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.redwolf501.top/Article/details/gtmndcwpfy.html

Ruby: u.is_a?(User)
来源：http://dali.dianchejie.cn/Article/details/gtuzsydsef.html

C#:   u is User
来源：http://dali.jianghu66.top/Article/details/gtsioezuhw.html

[G14] 数据类 / record
来源：http://dali.yangfankeji.com/Article/details/gtdntksygv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hammf.cn/Article/details/gtuvblnzhp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yonumen.top/Article/details/gtdtrfwela.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shzxlz.cn/Article/details/gtqxxigyza.html

TS:   type User = { name: string; age: number };
来源：http://dali.redwolf501.top/Article/details/gtqhxxbnqc.html

Java: record User(String name, int age) {}
来源：http://dali.0kj1m.cn/Article/details/gtkapedtxv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ybcxt.top/Article/details/gttxnyscmr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.smart0.xyz/Article/details/gtcclnplqr.html

C#:   record User(string Name, int Age);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrgdhtqj.html

[G15] 枚举
来源：http://dali.tanke756.top/Article/details/gtxkcvpuzg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.haohaochexian.top/Article/details/gtvwmlezkz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.svipenyu.cn/Article/details/gtzkefgxoi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tianlin.xyz/Article/details/gtdtckpqwh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gtvglcrakk.html

Java: enum Color { RED, GREEN }
来源：http://dali.ehwqpu.com/Article/details/gtfxafrqrd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zdqjudy.top/Article/details/gtzemcklkn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aizwys.cn/Article/details/gtzztrffyh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gtgwedshiq.html

[G16] 对象转数组 / 字典
来源：http://dali.shuidangran.top/Article/details/gtunbslovt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shuidangran.top/Article/details/gtztsnavpb.html

PHP:  get_object_vars($obj);
来源：http://dali.cqqwz.cn/Article/details/gtbpbsdirq.html

JS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gtiplenxtx.html

TS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gtnbooqmnv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cashguo.top/Article/details/gttmhdnxib.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhongyouzk.top/Article/details/gtjjsqfrkd.html

Ruby: obj.instance_variables
来源：http://dali.gaohongyu789.top/Article/details/gtlqoownbe.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.316326.xyz/Article/details/gtsbnaqumf.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtzopdphlm.html

H. 异常与错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gtwxbkyahv.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gteuuaxjcy.html

[H01] try / catch 基础
来源：http://dali.xylfe.cn/Article/details/gthcccvglu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj20258.top/Article/details/gttctdlypa.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hammf.cn/Article/details/gtjtxnmanf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gtccvrmwxi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gtzmlfeksh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.bjfxy.top/Article/details/gtbgrpsxgw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangdashe.top/Article/details/gtnsngeujx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hnxiangtu.top/Article/details/gtgwysmtsg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ydzc1.top/Article/details/gtldnanncg.html

[H02] finally / ensure 收尾
来源：http://dali.yuanzhike.top/Article/details/gtndzrpkld.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tanke756.top/Article/details/gtlcuxiutm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtzungnwxn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtgebaktyv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtrclxocpo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotqbeqop.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.smart0.xyz/Article/details/gtrvnvgehs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.kuanghao11.cn/Article/details/gtptmokomm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtbimyqmuq.html

[H03] 主动抛出异常
来源：http://dali.ydzc1.top/Article/details/gtiadqwwug.html

Py:   raise ValueError("错误信息")
来源：http://dali.meibo888.top/Article/details/gthgznrlob.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtxecbdvqw.html

JS:   throw new Error("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtkhfvtiow.html

TS:   throw new Error("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtzoyqqexu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtdzsinfyn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnqzz.top/Article/details/gtlhdhwlxw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gaohongyu789.top/Article/details/gteduyjnuz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtzjjphbpw.html

[H04] 自定义异常类型
来源：http://dali.gotoacloud.top/Article/details/gtucmsrqsc.html

Py:   class MyError(Exception): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqiytugq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tian-w.cn/Article/details/gtcrigjqqu.html

JS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gtrwysvsjj.html

TS:   class MyError extends Error {}
来源：http://dali.yvedp.cn/Article/details/gtlcxwoojz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ehwqpu.com/Article/details/gteqblxojv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.andypj.xyz/Article/details/gtixdczsrq.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangdashe.top/Article/details/gtydtlaotc.html

C#:   class MyException : Exception {}
来源：http://dali.c1oappe.top/Article/details/gtiocnyklz.html

[H05] 捕获特定类型
来源：http://dali.fengsongda.top/Article/details/gthlqonvwg.html

Py:   except ValueError as e:
来源：http://dali.wangdashe.top/Article/details/gtozybqtzg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.mhx1999.top/Article/details/gtwoohexon.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gtvmlohoha.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gtnhziinbu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtlkmpxgpy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.svipenyu.cn/Article/details/gtkcaakkwr.html

Ruby: rescue ArgumentError => e
来源：http://dali.xuetiantiany.cn/Article/details/gtrahahlsr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnxiangtu.top/Article/details/gtpxylocdp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cheryme.top/Article/details/gtsdpzxktd.html

Py:   value = d.get("k") or default
来源：http://dali.zhongyouzk.top/Article/details/gtciotafgh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yongpay.top/Article/details/gtfuxvncuw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sxryk.cn/Article/details/gtypierfhe.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gtbiugeytc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxuanxn.top/Article/details/gtyiipxxtl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.aizwys.cn/Article/details/gtecqjfefl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cheryme.top/Article/details/gtqzidehes.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj20258.top/Article/details/gtjhzvjdwg.html

[H07] 断言
来源：http://dali.xuanzx.com/Article/details/gticmedmim.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xylfe.cn/Article/details/gtvdiaqaro.html

PHP:  assert($x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtlfqzefdy.html

JS:   console.assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtjjicjkgj.html

TS:   console.assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtkpmpuxch.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gaohongyu789.top/Article/details/gtrrafqvlc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangkeji.top/Article/details/gtziskvzyv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.mhx1999.top/Article/details/gtjswrqwpq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtmxiipdjp.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinghuilouyu.cn/Article/details/gtyqpeibfq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfbpwmzlb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ehwqpu.com/Article/details/gtaczhrnyr.html

JS:   e.message;  e.stack
来源：http://dali.ydzc1.top/Article/details/gtneurztbo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhiwuduotai.top/Article/details/gtqruvkbth.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.wangshuangyany.cn/Article/details/gtwmungsgs.html

Go:   err.Error()
来源：http://dali.zhengqikj.top/Article/details/gtnwlllhot.html

Ruby: e.message;  e.backtrace
来源：http://dali.xuanzx.com/Article/details/gtqtbriysf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zdqjudy.top/Article/details/gtmibojbqu.html

[H09] 带错误码的异常
来源：http://dali.daria6918.cn/Article/details/gtnbxepqhv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxuoacps.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.meibo888.top/Article/details/gtuodkhyuy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.smart0.xyz/Article/details/gtgcipkczj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.mhx1999.top/Article/details/gtxbkvxjol.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.wangshuangyany.cn/Article/details/gtsfeffhro.html


<!-- 参考信息 -->