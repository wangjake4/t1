代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.ivvv.top/Article/details/gtjzrhlfxv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.pycfn.com/Article/details/gtkegeqnse.html

PHP:  file_exists("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtewqnjxod.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtszwtujyp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gtbxellmhk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gtrrmyutvk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jlsjyb.cn/Article/details/gtulipwksr.html

Ruby: File.exist?("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtbxiocjcb.html

C#:   File.Exists("a.txt")
来源：http://dali.316326.xyz/Article/details/gttfruxzyu.html

[F06] 删除文件
来源：http://dali.yj20258.top/Article/details/gttjfyjool.html

Py:   os.remove("a.txt")
来源：http://dali.hammf.cn/Article/details/gtlwktresg.html

PHP:  unlink("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtjxzsjfej.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtdmewkahs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gterfkvipz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtqbdbwcmb.html

Go:   os.Remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtnsbodmsm.html

Ruby: File.delete("a.txt")
来源：http://dali.yonumen.top/Article/details/gtaiddsfvh.html

C#:   File.Delete("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtkjzevpcm.html

[F07] 创建目录（含多级）
来源：http://dali.jinqigufen.top/Article/details/gtrosnkryp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.316326.xyz/Article/details/gtbcfmylcm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtwhjtrggn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258888.top/Article/details/gtwpwagtcx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnqzz.top/Article/details/gtykcbsbva.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgfzy.top/Article/details/gtpprewaua.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hammf.cn/Article/details/gtbmsslgfm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.dashuyun.cn/Article/details/gtgmujhrlf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daria6918.cn/Article/details/gtuduuvcvu.html

[F08] 遍历目录
来源：http://dali.hammf.cn/Article/details/gtirztrwlk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ppjwa.cn/Article/details/gttrgbomuy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.316326.xyz/Article/details/gtidxhejnb.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenzaomai.com/Article/details/gtuoaqikzb.html

TS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gtykpxtcat.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinqigfzy.top/Article/details/gtnapkxils.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.9152youxi.cn/Article/details/gtlkpfrjkc.html

Ruby: Dir.children("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtgwrlzfdo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cqqwz.cn/Article/details/gtoaghqcue.html

[F09] 获取文件大小
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhnxnlwq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtdphjthsv.html

PHP:  filesize("a.txt");
来源：http://dali.sweek.top/Article/details/gtbntffjdi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gttjuygicg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sxryk.cn/Article/details/gtopzuflbz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtcxxlxlgw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hysaishi.cn/Article/details/gtglpcnqcl.html

Ruby: File.size("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gttfdgxpmd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenlongwang.top/Article/details/gtubahwaza.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.kuanghao11.cn/Article/details/gtrnyaqhbm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtgxxlacsa.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.mhx1999.top/Article/details/gtyorjmylr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtfblnfvqh.html

TS:   path.extname("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtwwubduvg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cheryme.top/Article/details/gtihdikrot.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtszfqsjiy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtaopcjgwl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtpoviszda.html

[F11] 复制与移动文件
来源：http://dali.haohaochexian.top/Article/details/gtbjjvekrd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtxbdthgrv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ybcxt.top/Article/details/gtxgqbfbpb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtyahoqrgk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtodqpzuia.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hywenlv.cn/Article/details/gtbpelozxq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhcfcgrs.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdxiahkch.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shangyingyoupin.top/Article/details/gtzsmfpqwd.html

[F12] CSV 读写
来源：http://dali.xuanzx.com/Article/details/gtmedgcqtt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj20258888.top/Article/details/gtvgwaizpy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangdashe.top/Article/details/gtnafvghun.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258888.top/Article/details/gtuwqbwtxv.html

TS:   // 同上
来源：http://dali.yuxming.cn/Article/details/gtmbaejkyy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yangfankeji.com/Article/details/gtdddxilzr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hfpthk.cn/Article/details/gtvjnmitpr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuanzx.com/Article/details/gtfftukzkl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.kuanghao11.cn/Article/details/gtbswhtjgr.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtaclcbclo.html

G. 面向对象
来源：http://dali.gotoacloud.top/Article/details/gtohmlogob.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtridgszjv.html

[G01] 定义类
来源：http://dali.cqqwz.cn/Article/details/gtaxvydhrq.html

Py:   class User: pass
来源：http://dali.haohaochexian.top/Article/details/gtdtetyvhq.html

PHP:  class User {}
来源：http://dali.wangdashe.top/Article/details/gthyjqxtzg.html

JS:   class User {}
来源：http://dali.xylfe.cn/Article/details/gtcnysoigx.html

TS:   class User { name: string = ""; }
来源：http://dali.nwbrower.top/Article/details/gtyqhqqije.html

Java: class User {}
来源：http://dali.cucudq.cn/Article/details/gtvcdvemrl.html

Go:   type User struct { Name string }
来源：http://dali.gaohongyu789.top/Article/details/gtndryngjq.html

Ruby: class User; end
来源：http://dali.hfpthk.cn/Article/details/gtuyinofyo.html

C#:   class User {}
来源：http://dali.316326.xyz/Article/details/gtebmjrvml.html

[G02] 构造函数
来源：http://dali.zhengqikj.top/Article/details/gtsmlowovu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.iojbl.cn/Article/details/gtgxbixcmv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqspjzor.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gtgksrfsap.html

TS:   constructor(public name: string) {}
来源：http://dali.hywenlv.cn/Article/details/gtnytujhce.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnwrpqsv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cdnleiting.top/Article/details/gteoruacip.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuanzhike.top/Article/details/gthqfgeegg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtmwcumsiy.html

[G03] 实例属性
来源：http://dali.gotoacloud.top/Article/details/gtqkgmbsmc.html

Py:   self.name = "x"
来源：http://dali.jqgfzy.top/Article/details/gtetbifhhv.html

PHP:  public string $name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtjqqjtifo.html

JS:   this.name = "x";
来源：http://dali.hfpthk.cn/Article/details/gticiwndcz.html

TS:   name: string = "x";
来源：http://dali.sweek.top/Article/details/gtflrfgsbx.html

Java: private String name;
来源：http://dali.tian-w.cn/Article/details/gtafrslrnn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xziqi.cn/Article/details/gtavxghfgj.html

Ruby: @name = "x"
来源：http://dali.cucudq.cn/Article/details/gtpvvaqyus.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guowangkeji.top/Article/details/gtiiokqndh.html

[G04] 定义方法
来源：http://dali.nanxuanxn.top/Article/details/gtoutsfell.html

Py:   def greet(self): return self.name
来源：http://dali.haohaochexian.top/Article/details/gtiwrizegg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gtvwsdidlm.html

JS:   greet() { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtzrzhddlt.html

TS:   greet(): string { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtcmkxkfxw.html

Java: String greet() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtwannfsir.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtlhhhqega.html

Ruby: def greet; @name; end
来源：http://dali.feifeiyinyue.top/Article/details/gtoneuqejn.html

C#:   public string Greet() => Name;
来源：http://dali.zhiwuduotai.top/Article/details/gtcfsauqng.html

[G05] 继承
来源：http://dali.cqqwz.cn/Article/details/gtgbtzvuwb.html

Py:   class Admin(User): pass
来源：http://dali.shuidangran.top/Article/details/gtgqnuwhtn.html

PHP:  class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtecjnybod.html

JS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtavhevsbk.html

TS:   class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtmvbodgrj.html

Java: class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtqcndttgp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hammf.cn/Article/details/gteplzkvfj.html

Ruby: class Admin < User; end
来源：http://dali.sweek.top/Article/details/gtdozuiyzk.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gtsmltgalq.html

[G06] 重写方法
来源：http://dali.dashuyun.cn/Article/details/gtmbpboibh.html

Py:   def greet(self): return "admin"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtghgyfpfa.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtsjhejpml.html

JS:   greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtrjqktlte.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtblnxixcu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtfrqzjmku.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xinyue.icu/Article/details/gtwmouiebv.html

Ruby: def greet; "admin"; end
来源：http://dali.aibaodan.cn/Article/details/gtwwvxnfhr.html

C#:   public override string Greet() => "admin";
来源：http://dali.yueranfly.top/Article/details/gtqafawvta.html

[G07] 调用父类方法
来源：http://dali.jqgufenzy.top/Article/details/gtqxdxuuwv.html

Py:   super().greet()
来源：http://dali.shangyingyoupin.top/Article/details/gtqptqwpnc.html

PHP:  parent::greet();
来源：http://dali.smart0.xyz/Article/details/gtgrdsrljx.html

JS:   super.greet();
来源：http://dali.haohaochexian.top/Article/details/gtpbfawfvr.html

TS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gtimsynmzr.html

Java: super.greet();
来源：http://dali.smart0.xyz/Article/details/gtlwwhlkyg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhongyouzk.top/Article/details/gtjfkebjsu.html

Ruby: super
来源：http://dali.tanke756.top/Article/details/gtccxxuzqp.html

C#:   base.Greet();
来源：http://dali.guannengcc.top/Article/details/gthjxsjjrm.html

[G08] 静态方法与属性
来源：http://dali.c1oappe.top/Article/details/gtunshgpwe.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.kuanghao11.cn/Article/details/gtllbdzdco.html

PHP:  public static function f() {}
来源：http://dali.cqqwz.cn/Article/details/gtbjdcomxz.html

JS:   static f() {}
来源：http://dali.zycfv.cn/Article/details/gtuxjmipcz.html

TS:   static f(): void {}
来源：http://dali.mhx1999.top/Article/details/gthputhitc.html

Java: static void f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpztqiyil.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yongpay.top/Article/details/gtkpqfunyg.html

Ruby: def self.f; end
来源：http://dali.birdmap.top/Article/details/gtbwemuzpx.html

C#:   public static void F() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtlbcfhedr.html

[G09] 接口 / 抽象类
来源：http://dali.vqdsnc.cn/Article/details/gtscfqhual.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.havefunace.top/Article/details/gthuofyedl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.birdmap.top/Article/details/gtmeuveejk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gotoacloud.top/Article/details/gtddnxaiec.html

TS:   interface Shape { area(): number; }
来源：http://dali.aibaodan.cn/Article/details/gtgoylzmti.html

Java: interface Shape { double area(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsyvsryei.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shangyingyoupin.top/Article/details/gtrnqsrrzk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ivvv.top/Article/details/gtzqdpllwx.html

C#:   interface IShape { double Area(); }
来源：http://dali.mhx1999.top/Article/details/gtrdginewh.html

[G10] 访问控制
来源：http://dali.cucudq.cn/Article/details/gtvndvnnxt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hfpthk.cn/Article/details/gtlqafojtc.html

PHP:  public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gtrgvarqls.html

JS:   #private 字段；其余公开
来源：http://dali.bjfxy.top/Article/details/gtiqzraoci.html

TS:   public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtcvlvztlu.html

Java: public / protected / private / 默认包级
来源：http://dali.gogol.net.cn/Article/details/gtvlvexjeg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zycfv.cn/Article/details/gtdrwbpfir.html

Ruby: public / protected / private
来源：http://dali.316326.xyz/Article/details/gtylkuifun.html

C#:   public / protected / private / internal
来源：http://dali.yuxming.cn/Article/details/gtumymwqsk.html

[G11] getter / setter
来源：http://dali.zhongyouzk.top/Article/details/gtaptaokcz.html

Py:   @property 与 @x.setter
来源：http://dali.xuetiantiany.cn/Article/details/gtoirnazsq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gtczhaqbib.html

JS:   get name() { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gtxkysabay.html

TS:   get name(): string { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gtcbtijnwt.html

Java: public String getName() { return name; }
来源：http://dali.yueranfly.top/Article/details/gtqykysgwc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gtybhrvhdm.html

Ruby: attr_accessor :name
来源：http://dali.hongshengwenyu.top/Article/details/gtbdunhiqr.html

C#:   public string Name { get; set; }
来源：http://dali.pengpengdd.cyou/Article/details/gtqjhfkpab.html

[G12] 对象转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtaqyhbrrq.html

Py:   def __str__(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gtmujaznjd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtyetzslae.html

JS:   toString() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtzozfqtxn.html

TS:   toString(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtmmcbuifg.html

Java: @Override public String toString() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtaqtmfxvz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gtqenhxvaq.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258.top/Article/details/gtcgbfmssp.html

C#:   public override string ToString() => Name;
来源：http://dali.daria6918.cn/Article/details/gtothsgdmw.html

[G13] 判断对象类型
来源：http://dali.shzxlz.cn/Article/details/gtofgqzntb.html

Py:   isinstance(u, User)
来源：http://dali.aizwys.cn/Article/details/gtiqwdzett.html

PHP:  $u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtauxqgcvr.html

JS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtzcxatlkn.html

TS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtyjbqcujk.html

Java: u instanceof User
来源：http://dali.ybcxt.top/Article/details/gtraduwvcc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yanxiufei.cn/Article/details/gtdpjvqzyj.html

Ruby: u.is_a?(User)
来源：http://dali.sufxvd.cn/Article/details/gtlhoskdil.html

C#:   u is User
来源：http://dali.yonumen.top/Article/details/gtyijguxof.html

[G14] 数据类 / record
来源：http://dali.ppjwa.cn/Article/details/gtditfhcow.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.vqdsnc.cn/Article/details/gtrkxisrwr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cucudq.cn/Article/details/gtjhtkxvft.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinqigfzy.top/Article/details/gtjhppebur.html

TS:   type User = { name: string; age: number };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnvlneag.html

Java: record User(String name, int age) {}
来源：http://dali.yuanzhike.top/Article/details/gtaughpiky.html

Go:   type User struct { Name string; Age int }
来源：http://dali.daria6918.cn/Article/details/gthqwlkeyw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlzyuvpdp.html

C#:   record User(string Name, int Age);
来源：http://dali.gogol.net.cn/Article/details/gthkjwohng.html

[G15] 枚举
来源：http://dali.nwbrower.top/Article/details/gtykvmnpsu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tian-w.cn/Article/details/gtbptqjqis.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.snrcjt.cn/Article/details/gtjyrejafo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.birdmap.top/Article/details/gtifqhbjon.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gtfdobaaec.html

Java: enum Color { RED, GREEN }
来源：http://dali.nanxinkj.top/Article/details/gtxjrjidig.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nwbrower.top/Article/details/gtuilbpqtn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhixingplan.top/Article/details/gtjcmoqulw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gtcsshipbw.html

[G16] 对象转数组 / 字典
来源：http://dali.cqqwz.cn/Article/details/gtfvhotfwi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ppjwa.cn/Article/details/gtgsugnghs.html

PHP:  get_object_vars($obj);
来源：http://dali.zycfv.cn/Article/details/gtyrumipvb.html

JS:   Object.entries(obj)
来源：http://dali.gzhubu.top/Article/details/gtqhaxqksp.html

TS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gtgaombigu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sufxvd.cn/Article/details/gtylwhyloi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tianlin.xyz/Article/details/gtlebgdpog.html

Ruby: obj.instance_variables
来源：http://dali.sweek.top/Article/details/gtpmbniyjs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gtzzjfduyx.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtpzmghuos.html

H. 异常与错误处理
来源：http://dali.shangyingyoupin.top/Article/details/gtuykfhluj.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtbryxsztv.html

[H01] try / catch 基础
来源：http://dali.gaohongyu789.top/Article/details/gtgihmwcfm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cashguo.top/Article/details/gtlxdpkcju.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hywenlv.cn/Article/details/gtmsmcqtir.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gtbycjrxnr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gtmsdnjgwx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxgqwzri.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xuetiantiany.cn/Article/details/gtunybvdlv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.andypj.xyz/Article/details/gteihrzjhw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.birdmap.top/Article/details/gtrnjliqbn.html

[H02] finally / ensure 收尾
来源：http://dali.andypj.xyz/Article/details/gttvmzcwka.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.9152youxi.cn/Article/details/gtaxwtnfkl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtiaautewt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtydjdgztb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtsxvzmsvw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtlknuacoj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ybcxt.top/Article/details/gtjzrkbmvc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sufxvd.cn/Article/details/gtxquonldn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtsnqvzxig.html

[H03] 主动抛出异常
来源：http://dali.cheryme.top/Article/details/gtajtlqtec.html

Py:   raise ValueError("错误信息")
来源：http://dali.birdmap.top/Article/details/gtawmpwmov.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtpbhfxpug.html

JS:   throw new Error("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gttjtppgcl.html

TS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gthqbzjtzs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gtbqbigmao.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenlongwang.top/Article/details/gtwauxtixk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.0kj1m.cn/Article/details/gtxeiparmm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtfnyrbuzp.html

[H04] 自定义异常类型
来源：http://dali.jyoumei.cn/Article/details/gtrxhmixfs.html

Py:   class MyError(Exception): pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gthslerdyz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.quarkkingdee.top/Article/details/gtpzdnzhpo.html

JS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gtxmszwumf.html

TS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gtxupggesf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gtucrsfefq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgfzy.top/Article/details/gtufoadxmn.html

Ruby: class MyError < StandardError; end
来源：http://dali.shzxlz.cn/Article/details/gthhovtxff.html

C#:   class MyException : Exception {}
来源：http://dali.jiagoushi.top/Article/details/gtvhlhscmv.html

[H05] 捕获特定类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtvglbey.html

Py:   except ValueError as e:
来源：http://dali.jyoumei.cn/Article/details/gtwwwvlhlu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hfpthk.cn/Article/details/gtqkxvopbp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yangfankeji.com/Article/details/gtsjjwaddw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tian-w.cn/Article/details/gtvfpsjeja.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cheryme.top/Article/details/gtfkklfeke.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yangfankeji.com/Article/details/gthwpcvcax.html

Ruby: rescue ArgumentError => e
来源：http://dali.jiagoushi.top/Article/details/gtabjotrxa.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nwbrower.top/Article/details/gtaxheogfv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.andypj.xyz/Article/details/gtxlxapuxq.html

Py:   value = d.get("k") or default
来源：http://dali.daxiang520.top/Article/details/gtkguvaiuy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.9152youxi.cn/Article/details/gtyxqvnmzr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gtokflysva.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gtklukisbz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrpeymzhi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shangyingyoupin.top/Article/details/gtikjenass.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cashguo.top/Article/details/gtdrtwobih.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuanzhike.top/Article/details/gtschjaujn.html

[H07] 断言
来源：http://dali.aibaodan.cn/Article/details/gtxnxtmhnp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.quarkkingdee.top/Article/details/gtdburhucx.html

PHP:  assert($x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtbqwlssmj.html

JS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtrsfrgxar.html

TS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbfsxnfbc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgfzy.top/Article/details/gtdrrkzwfq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zycfv.cn/Article/details/gtbipjmhzj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.316326.xyz/Article/details/gtoqsztazh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtqpofkely.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuanzx.com/Article/details/gtkrybcrsa.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.haohaochexian.top/Article/details/gtwnybnoex.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sufxvd.cn/Article/details/gtzcttpjre.html

JS:   e.message;  e.stack
来源：http://dali.jlsjyb.cn/Article/details/gtqclsrsht.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pycfn.com/Article/details/gtbngfrbxc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.snrcjt.cn/Article/details/gtdpkzngjl.html

Go:   err.Error()
来源：http://dali.xinyue.icu/Article/details/gtvaulkriq.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgufenzy.top/Article/details/gtippalzdi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hfpthk.cn/Article/details/gtkgknrwpb.html

[H09] 带错误码的异常
来源：http://dali.cucudq.cn/Article/details/gtuqxghlzy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shangyingyoupin.top/Article/details/gtodkllmbc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.snrcjt.cn/Article/details/gtixkpnokh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.bjfxy.top/Article/details/gtyjmwmjni.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hnxiangtu.top/Article/details/gtevulaszm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigfzy.top/Article/details/gtakdrwafg.html


<!-- 参考信息 -->