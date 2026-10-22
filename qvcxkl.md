代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2ukdxrtzm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2sncdmeqh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gt2lpopebvq.html

Go:   os.Remove("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2ifazcsnw.html

Ruby: File.delete("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2xyrrqczs.html

C#:   File.Delete("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2upiljyqr.html

[F07] 创建目录（含多级）
来源：http://dali.zhengqikj.top/Article/details/gt2novlpnmg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jiagoushi.top/Article/details/gt2zbzpbxsv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aydawrxk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dashuyun.cn/Article/details/gt2mavsrrwx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gt2naoqmeku.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ipniovwv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.snrcjt.cn/Article/details/gt2xniqmrcg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ctdbiear.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.wangshuangyany.cn/Article/details/gt2hxpjkgkr.html

[F08] 遍历目录
来源：http://dali.xziqi.cn/Article/details/gt2mjdqmibd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.andypj.xyz/Article/details/gt2pgivqljd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jqgufenzy.top/Article/details/gt2bwsybyjl.html

JS:   fs.readdirSync("dir")
来源：http://dali.hysaishi.cn/Article/details/gt2ifoayomu.html

TS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2wcftidgd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.0kj1m.cn/Article/details/gt2fkibiyde.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gt2fhpvijxu.html

Ruby: Dir.children("dir")
来源：http://dali.chenzaomai.com/Article/details/gt2cbsgnkrr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgfzy.top/Article/details/gt2ehvjafme.html

[F09] 获取文件大小
来源：http://dali.andypj.xyz/Article/details/gt2hjjaweqg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2eurpcrdc.html

PHP:  filesize("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2mhlxkkah.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jianghu66.top/Article/details/gt2qhvcxmxb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.guannengcc.top/Article/details/gt2splxfkjp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gt2vxjxohdh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhengqikj.top/Article/details/gt2qfiiveeo.html

Ruby: File.size("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2lmynuaeg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sysykeji.top/Article/details/gt2sjgpkhox.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.dianchejie.cn/Article/details/gt2neplfmkt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2zspbrbpg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2htuhofsy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2ldpqnfrn.html

TS:   path.extname("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2gsiljgzo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hnxiangtu.top/Article/details/gt2ebiwxmxo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2crbdzbza.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2xspynkpe.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hnacbguv.html

[F11] 复制与移动文件
来源：http://dali.hnqzz.top/Article/details/gt2uairzfxd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gt2pqoyvwdt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hammf.cn/Article/details/gt2edcnmepy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gt2giveauih.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rgnlfhmg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aibaodan.cn/Article/details/gt2aleqdqjm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yanxiufei.cn/Article/details/gt2hlxacpsg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gt2ckdvovyz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yuxming.cn/Article/details/gt2vyrgnlly.html

[F12] CSV 读写
来源：http://dali.fengsongda.top/Article/details/gt2fzvgkyrk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhoulong.xyz/Article/details/gt2rdudyxoe.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.pengpengdd.cyou/Article/details/gt2ajmeznbv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jlsjyb.cn/Article/details/gt2crxebmpw.html

TS:   // 同上
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zguqkkac.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ydzc1.top/Article/details/gt2dnzxrivy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ybcxt.top/Article/details/gt2nkwdeoan.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuetiantiany.cn/Article/details/gt2hjaffpgx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhengqikj.top/Article/details/gt2rhjceirf.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2qamxipeu.html

G. 面向对象
来源：http://dali.zhiwuduotai.top/Article/details/gt2bkcnmise.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2rbjkgszd.html

[G01] 定义类
来源：http://dali.316326.xyz/Article/details/gt2iqjvtzqm.html

Py:   class User: pass
来源：http://dali.hnqzz.top/Article/details/gt2ycvglgys.html

PHP:  class User {}
来源：http://dali.chenzaomai.com/Article/details/gt2isnmwzjy.html

JS:   class User {}
来源：http://dali.mhx1999.top/Article/details/gt2pmflxzyh.html

TS:   class User { name: string = ""; }
来源：http://dali.hnxiangtu.top/Article/details/gt2eckqoorr.html

Java: class User {}
来源：http://dali.cqqwz.cn/Article/details/gt2dlgmwnqm.html

Go:   type User struct { Name string }
来源：http://dali.nanxuanxn.top/Article/details/gt2fsdzvalc.html

Ruby: class User; end
来源：http://dali.guannengcc.top/Article/details/gt2yljuiepb.html

C#:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gt2kyqrawtv.html

[G02] 构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2ztccazwk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xjsnmapo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.9152youxi.cn/Article/details/gt2psjpfyis.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zxhpmrhy.html

TS:   constructor(public name: string) {}
来源：http://dali.jyoumei.cn/Article/details/gt2qfkwalyw.html

Java: User(String name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gt2mwlddfip.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hysaishi.cn/Article/details/gt2tcvzjgxk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnaucsz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wbtutthv.html

[G03] 实例属性
来源：http://dali.sysykeji.top/Article/details/gt2pyoqxaic.html

Py:   self.name = "x"
来源：http://dali.0kj1m.cn/Article/details/gt2auxhrvvv.html

PHP:  public string $name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gt2akniufxt.html

JS:   this.name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gt2qsdbabql.html

TS:   name: string = "x";
来源：http://dali.xylfe.cn/Article/details/gt2pcxoxyhm.html

Java: private String name;
来源：http://dali.guowangkeji.top/Article/details/gt2effztcjh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenzaomai.com/Article/details/gt2ifjhfrot.html

Ruby: @name = "x"
来源：http://dali.svipenyu.cn/Article/details/gt2ohxxqyzh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hnxiangtu.top/Article/details/gt2eqrdyhhc.html

[G04] 定义方法
来源：http://dali.yj20258.top/Article/details/gt2mlimpqis.html

Py:   def greet(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gt2septbbyf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gt2tvxjrdhc.html

JS:   greet() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2qragoxkf.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2jppcpjca.html

Java: String greet() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2bgzyvuya.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gt2fyowqwjv.html

Ruby: def greet; @name; end
来源：http://dali.daria6918.cn/Article/details/gt2zdwyiehm.html

C#:   public string Greet() => Name;
来源：http://dali.hywenlv.cn/Article/details/gt2kuoaauzo.html

[G05] 继承
来源：http://dali.dashuyun.cn/Article/details/gt2lqzkkdya.html

Py:   class Admin(User): pass
来源：http://dali.shuidangran.top/Article/details/gt2upnyztax.html

PHP:  class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gt2xeueopio.html

JS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ncuzeawc.html

TS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gt2wegnqqet.html

Java: class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gt2eqacvlhd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.0kj1m.cn/Article/details/gt2fvxxstzk.html

Ruby: class Admin < User; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2grymomhi.html

C#:   class Admin : User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2hyrdhzna.html

[G06] 重写方法
来源：http://dali.snrcjt.cn/Article/details/gt2eybcaeqv.html

Py:   def greet(self): return "admin"
来源：http://dali.0kj1m.cn/Article/details/gt2xsuixnor.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbyfiyh.html

JS:   greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gt2okcbmgiz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gt2btwppgqr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gt2gxkxctfd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.svipenyu.cn/Article/details/gt2wlhpcxsk.html

Ruby: def greet; "admin"; end
来源：http://dali.gzhubu.top/Article/details/gt2sxcalkjx.html

C#:   public override string Greet() => "admin";
来源：http://dali.ybcxt.top/Article/details/gt2mgorrrtm.html

[G07] 调用父类方法
来源：http://dali.hysaishi.cn/Article/details/gt2hxrivinp.html

Py:   super().greet()
来源：http://dali.sysykeji.top/Article/details/gt2evbgygct.html

PHP:  parent::greet();
来源：http://dali.guannengcc.top/Article/details/gt2vedfbybh.html

JS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gt2tizbwlcf.html

TS:   super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gt2xitdmrcn.html

Java: super.greet();
来源：http://dali.jqgfzy.top/Article/details/gt2hgzxtrxp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yonumen.top/Article/details/gt2egqyvptz.html

Ruby: super
来源：http://dali.c1oappe.top/Article/details/gt2sjpqyken.html

C#:   base.Greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lzxhehsa.html

[G08] 静态方法与属性
来源：http://dali.aibaodan.cn/Article/details/gt2gremathr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hywenlv.cn/Article/details/gt2oammaaye.html

PHP:  public static function f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zibcqxgo.html

JS:   static f() {}
来源：http://dali.guannengcc.top/Article/details/gt2fxrwqgnb.html

TS:   static f(): void {}
来源：http://dali.gaohongyu789.top/Article/details/gt2pshxbdmm.html

Java: static void f() {}
来源：http://dali.0kj1m.cn/Article/details/gt2sqzoelgt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cashguo.top/Article/details/gt2whnkufev.html

Ruby: def self.f; end
来源：http://dali.dianchejie.cn/Article/details/gt2qvhprdja.html

C#:   public static void F() {}
来源：http://dali.nanxinkj.top/Article/details/gt2deeszxum.html

[G09] 接口 / 抽象类
来源：http://dali.jyoumei.cn/Article/details/gt2jvtzrllr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.svipenyu.cn/Article/details/gt2etxmtqph.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fengsongda.top/Article/details/gt2oqsgkosg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yonumen.top/Article/details/gt2zxaworqi.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258888.top/Article/details/gt2wllwvtyn.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258.top/Article/details/gt2tdoonfiq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guannengcc.top/Article/details/gt2ldwldkaz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fzhhl.top/Article/details/gt2iswhtqof.html

C#:   interface IShape { double Area(); }
来源：http://dali.yvedp.cn/Article/details/gt2uexhslfc.html

[G10] 访问控制
来源：http://dali.yongpay.top/Article/details/gt2tabwzlig.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hfpthk.cn/Article/details/gt2bziagwtl.html

PHP:  public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gt2eektljqe.html

JS:   #private 字段；其余公开
来源：http://dali.redwolf501.top/Article/details/gt2aycvuyys.html

TS:   public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gt2wljpmylt.html

Java: public / protected / private / 默认包级
来源：http://dali.9152youxi.cn/Article/details/gt2eldwfego.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.0kj1m.cn/Article/details/gt2nkpkeuyr.html

Ruby: public / protected / private
来源：http://dali.xinyue.icu/Article/details/gt2meqahqux.html

C#:   public / protected / private / internal
来源：http://dali.xuanzx.com/Article/details/gt2ondbkqsj.html

[G11] getter / setter
来源：http://dali.zhixingplan.top/Article/details/gt2wyrgpcbk.html

Py:   @property 与 @x.setter
来源：http://dali.kuanghao11.cn/Article/details/gt2fzpvmdyh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gt2mpxfdess.html

JS:   get name() { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gt2gtbocgac.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2qhdksagg.html

Java: public String getName() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gt2bzajccyj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gt2dgkdurvm.html

Ruby: attr_accessor :name
来源：http://dali.xylfe.cn/Article/details/gt2szfwvhih.html

C#:   public string Name { get; set; }
来源：http://dali.gzhubu.top/Article/details/gt2hfmzgbdp.html

[G12] 对象转字符串
来源：http://dali.xylfe.cn/Article/details/gt2obiqzjlv.html

Py:   def __str__(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gt2xalzjtyq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gt2ptejvuyg.html

JS:   toString() { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gt2mjcqqmuv.html

TS:   toString(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2bsfftlbg.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gt2gjjlhjzt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gt2usgtlwst.html

Ruby: def to_s; @name; end
来源：http://dali.nwbrower.top/Article/details/gt2cwaauwfz.html

C#:   public override string ToString() => Name;
来源：http://dali.xuanzx.com/Article/details/gt2fkbjkmqs.html

[G13] 判断对象类型
来源：http://dali.aibaodan.cn/Article/details/gt2cbhqsyvb.html

Py:   isinstance(u, User)
来源：http://dali.yj20258.top/Article/details/gt2osnbxvhd.html

PHP:  $u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gt2bupvbief.html

JS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gt2pqlargpz.html

TS:   u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gt2ctlwwqba.html

Java: u instanceof User
来源：http://dali.316326.xyz/Article/details/gt2rwrjgqri.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.9152youxi.cn/Article/details/gt2raozhzab.html

Ruby: u.is_a?(User)
来源：http://dali.9152youxi.cn/Article/details/gt2tlmilwtk.html

C#:   u is User
来源：http://dali.sweek.top/Article/details/gt2mjyezzmy.html

[G14] 数据类 / record
来源：http://dali.chenlongwang.top/Article/details/gt2yucoqxrp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.redwolf501.top/Article/details/gt2maggvzas.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.svipenyu.cn/Article/details/gt2tzsdxvzb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xylfe.cn/Article/details/gt2tozdqptg.html

TS:   type User = { name: string; age: number };
来源：http://dali.hysaishi.cn/Article/details/gt2srqzwccw.html

Java: record User(String name, int age) {}
来源：http://dali.gzhubu.top/Article/details/gt2mthpvxoy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yonumen.top/Article/details/gt2jbbrldfc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2azbemxmw.html

C#:   record User(string Name, int Age);
来源：http://dali.yonumen.top/Article/details/gt2bftovtjm.html

[G15] 枚举
来源：http://dali.cheryme.top/Article/details/gt2idhvdxlh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sysykeji.top/Article/details/gt2wkzyxldm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2fqpeesvn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.meibo888.top/Article/details/gt2kflpyvfr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fengsongda.top/Article/details/gt2pyjlwvqa.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhongyouzk.top/Article/details/gt2gvrjbeju.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daria6918.cn/Article/details/gt2rtayhysf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.c1oappe.top/Article/details/gt2sgcjeldp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gt2dodzvknr.html

[G16] 对象转数组 / 字典
来源：http://dali.andypj.xyz/Article/details/gt2xllohrox.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gaohongyu789.top/Article/details/gt2udkmcqzu.html

PHP:  get_object_vars($obj);
来源：http://dali.chenzaomai.com/Article/details/gt2oepsgcnz.html

JS:   Object.entries(obj)
来源：http://dali.nwbrower.top/Article/details/gt2achvflmj.html

TS:   Object.entries(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2rkeojjeo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sxryk.cn/Article/details/gt2nluenmid.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cucudq.cn/Article/details/gt2cazkznho.html

Ruby: obj.instance_variables
来源：http://dali.zhoulong.xyz/Article/details/gt2ircxrgya.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.haohaochexian.top/Article/details/gt2ntpswstv.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2ymgqykga.html

H. 异常与错误处理
来源：http://dali.xinyue.icu/Article/details/gt2yalopkfa.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2zkwudcoa.html

[H01] try / catch 基础
来源：http://dali.jlsjyb.cn/Article/details/gt2kjuyqmkf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.kuanghao11.cn/Article/details/gt2atdpywuw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.meibo888.top/Article/details/gt2fiwamsbf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gt2kqkfjoun.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gt2prjgymgl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hfpthk.cn/Article/details/gt2qumwrplz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.meibo888.top/Article/details/gt2ewkhhtzm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tanke756.top/Article/details/gt2zrpndftt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daria6918.cn/Article/details/gt2azajifvy.html

[H02] finally / ensure 收尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ycixcerp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gzhubu.top/Article/details/gt2skmxzqpa.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2wnbmehrh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gt2casemorn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gt2ryxefrbj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gt2nbjzedat.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2itvwcqni.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ehwqpu.com/Article/details/gt2yihsjmuz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gt2dzeubfnh.html

[H03] 主动抛出异常
来源：http://dali.dianchejie.cn/Article/details/gt2kgqsfymv.html

Py:   raise ValueError("错误信息")
来源：http://dali.gotoacloud.top/Article/details/gt2clhrabab.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2gjmtlkik.html

JS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gt2wnebcprf.html

TS:   throw new Error("错误信息");
来源：http://dali.cucudq.cn/Article/details/gt2rexlaxch.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gt2muzouxso.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.svipenyu.cn/Article/details/gt2wlnspsog.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sufxvd.cn/Article/details/gt2ibukrknx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gt2ygpuvkpd.html

[H04] 自定义异常类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2uitpmwbx.html

Py:   class MyError(Exception): pass
来源：http://dali.chenzaomai.com/Article/details/gt2tltsxxoh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gt2efiwtekm.html

JS:   class MyError extends Error {}
来源：http://dali.cucudq.cn/Article/details/gt2jnklnlfk.html

TS:   class MyError extends Error {}
来源：http://dali.havefunace.top/Article/details/gt2zlpiobdm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.meibo888.top/Article/details/gt2arhjbhto.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenjidiqi.icu/Article/details/gt2mpzzxotg.html

Ruby: class MyError < StandardError; end
来源：http://dali.hammf.cn/Article/details/gt2zqbmpqhx.html

C#:   class MyException : Exception {}
来源：http://dali.guannengcc.top/Article/details/gt2tqtdzeca.html

[H05] 捕获特定类型
来源：http://dali.zhoulong.xyz/Article/details/gt2vpyrjhsh.html

Py:   except ValueError as e:
来源：http://dali.aibaodan.cn/Article/details/gt2nuiftozb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shzxlz.cn/Article/details/gt2uiitqxkv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gt2nsbhglvt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gt2azguukyx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ydzc1.top/Article/details/gt2rfrokevz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.svipenyu.cn/Article/details/gt2uucmkkfy.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgfzy.top/Article/details/gt2xwmwizpv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2cblndrcy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gotoacloud.top/Article/details/gt2axhmelqj.html

Py:   value = d.get("k") or default
来源：http://dali.zhengqikj.top/Article/details/gt2ngqblrmv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gt2bkjxjdfh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gt2rhvkmdzp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.meibo888.top/Article/details/gt2mpexscla.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kqslawpm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tian-w.cn/Article/details/gt2uwshaatk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj202588.top/Article/details/gt2oooandkn.html

C#:   obj?.A?.B ?? default
来源：http://dali.yueranfly.top/Article/details/gt2owgwduxl.html

[H07] 断言
来源：http://dali.cashguo.top/Article/details/gt2psorbnln.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sufxvd.cn/Article/details/gt2lvclprvl.html

PHP:  assert($x > 0);
来源：http://dali.guowangkeji.top/Article/details/gt2mrpmkmkl.html

JS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ewnhrxhc.html

TS:   console.assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gt2rrjhnavt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shuidangran.top/Article/details/gt2rkfltooo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pycfn.com/Article/details/gt2lengatvt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenjidiqi.icu/Article/details/gt2irzmqslr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2pxyecqla.html

[H08] 获取错误信息与堆栈
来源：http://dali.jyoumei.cn/Article/details/gt2wokmcivu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sweek.top/Article/details/gt2eeppbhsr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuanzx.com/Article/details/gt2tpaphrfi.html

JS:   e.message;  e.stack
来源：http://dali.sweek.top/Article/details/gt2ehlungou.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sweek.top/Article/details/gt2qowxrqtj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.aibaodan.cn/Article/details/gt2qfrpqvie.html

Go:   err.Error()
来源：http://dali.birdmap.top/Article/details/gt2fovjltay.html

Ruby: e.message;  e.backtrace
来源：http://dali.dianchejie.cn/Article/details/gt2oophgjtw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sbzadquf.html

[H09] 带错误码的异常
来源：http://dali.shangyingyoupin.top/Article/details/gt2lfkpaboh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xinyue.icu/Article/details/gt2osufyizr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj202588.top/Article/details/gt2zriozxxy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cqqwz.cn/Article/details/gt2ffuouseg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daxiang520.top/Article/details/gt2nzpsfjxq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.haohaochexian.top/Article/details/gt2mnlyfoba.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.aibaodan.cn/Article/details/gt2lomwsuuc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.kuanghao11.cn/Article/details/gt2ilsntwih.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yvedp.cn/Article/details/gt2bufmirbr.html

[H10] 资源自动释放
来源：http://dali.tanke756.top/Article/details/gt2whhoytpq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenjidiqi.icu/Article/details/gt2bsswkeml.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.c1oappe.top/Article/details/gt2iubtvnwr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258.top/Article/details/gt2spxhaphr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.redwolf501.top/Article/details/gt2tbimpmit.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shuidangran.top/Article/details/gt2zwrgkhqn.html

Go:   defer f.Close()
来源：http://dali.cashguo.top/Article/details/gt2twcdfjcs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xinyue.icu/Article/details/gt2zrjczyun.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2omclnchi.html


<!-- 参考信息 -->