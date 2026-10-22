代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtndnmydli.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtfsrxdzbx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gtducfobcv.html

Go:   os.Remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtuabkiykt.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtbmoyijpd.html

C#:   File.Delete("a.txt");
来源：http://dali.cashguo.top/Article/details/gttsivhwec.html

[F07] 创建目录（含多级）
来源：http://dali.sxryk.cn/Article/details/gtbfmcqgtb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ppjwa.cn/Article/details/gtcjmioqbl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guowangkeji.top/Article/details/gtuvngrcas.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenlongwang.top/Article/details/gtelfuxyko.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gtpcoardwn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.meibo888.top/Article/details/gtyojxjgkv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinqigfzy.top/Article/details/gtqqskixuy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jqgfzy.top/Article/details/gtlmfgibrm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jianghu66.top/Article/details/gtrgvemuog.html

[F08] 遍历目录
来源：http://dali.mhx1999.top/Article/details/gthbcszrkd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj20258.top/Article/details/gtyludrclu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sufxvd.cn/Article/details/gtvpuulday.html

JS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtxuxqoeru.html

TS:   fs.readdirSync("dir")
来源：http://dali.zycfv.cn/Article/details/gtbnkvkmml.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.0kj1m.cn/Article/details/gtccqbkefm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guowangkeji.top/Article/details/gtogqlysuh.html

Ruby: Dir.children("dir")
来源：http://dali.yongpay.top/Article/details/gtdzxkyrsq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tanke756.top/Article/details/gtlpqodnfv.html

[F09] 获取文件大小
来源：http://dali.guannengcc.top/Article/details/gtsmwslway.html

Py:   os.path.getsize("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtbxxcsnpp.html

PHP:  filesize("a.txt");
来源：http://dali.yongpay.top/Article/details/gtlumyjnuy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.c1oappe.top/Article/details/gtnkwugopr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gaohongyu789.top/Article/details/gtxjaugumu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtgnfovqif.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xinyue.icu/Article/details/gtvomafnqz.html

Ruby: File.size("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtcnjvdxxy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.dashuyun.cn/Article/details/gteqmnqjms.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenjidiqi.icu/Article/details/gtaueydcwk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtrnbnneir.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.havefunace.top/Article/details/gtfcnfkbcr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtazqdsjyc.html

TS:   path.extname("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtofygxjpt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yongpay.top/Article/details/gtafzhjgda.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtwojwthkf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gttbfnquip.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtrbdotmps.html

[F11] 复制与移动文件
来源：http://dali.zhixingplan.top/Article/details/gtlzzctmpp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtqhqysidg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.havefunace.top/Article/details/gttjxnnpfy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtxiqafszn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtreiubjbl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cucudq.cn/Article/details/gtmjfrgvqj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ywan-chungtsiang.top/Article/details/gtolbmrses.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtltimzkfq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.c1oappe.top/Article/details/gtceardkvy.html

[F12] CSV 读写
来源：http://dali.cdnleiting.top/Article/details/gtswahkupj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zdqjudy.top/Article/details/gthgmjbhaj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.c1oappe.top/Article/details/gtgyhcxzii.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jqgfzy.top/Article/details/gtqiqscguy.html

TS:   // 同上
来源：http://dali.hfpthk.cn/Article/details/gtwhmqbgjs.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cqqwz.cn/Article/details/gtajvohytu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cdnleiting.top/Article/details/gtqtdajghw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jiagoushi.top/Article/details/gtcikefrop.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuxming.cn/Article/details/gthwrnctdw.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gteekzqiti.html

G. 面向对象
来源：http://dali.ybcxt.top/Article/details/gtmdeorllo.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtkrodpkcy.html

[G01] 定义类
来源：http://dali.quarkkingdee.top/Article/details/gtysylqbrp.html

Py:   class User: pass
来源：http://dali.shangyingyoupin.top/Article/details/gtuwmvhdib.html

PHP:  class User {}
来源：http://dali.zdqjudy.top/Article/details/gtsfoagufb.html

JS:   class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtmkxtbltf.html

TS:   class User { name: string = ""; }
来源：http://dali.snrcjt.cn/Article/details/gtqcxssfni.html

Java: class User {}
来源：http://dali.smart0.xyz/Article/details/gtpnauphga.html

Go:   type User struct { Name string }
来源：http://dali.jlsjyb.cn/Article/details/gtosvjoccf.html

Ruby: class User; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvdnanob.html

C#:   class User {}
来源：http://dali.snrcjt.cn/Article/details/gtdcabtnje.html

[G02] 构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gtbsneadcd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hnxiangtu.top/Article/details/gtmktptbmc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tian-w.cn/Article/details/gtzhvrhcnz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtacsrotvy.html

TS:   constructor(public name: string) {}
来源：http://dali.quarkkingdee.top/Article/details/gtvsyazrnj.html

Java: User(String name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gtcwhaczpi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zdqjudy.top/Article/details/gtwqcyrnuj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daria6918.cn/Article/details/gttlgxrfcf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hywenlv.cn/Article/details/gtdquhzhab.html

[G03] 实例属性
来源：http://dali.pengpengdd.cyou/Article/details/gtkjewyauw.html

Py:   self.name = "x"
来源：http://dali.xziqi.cn/Article/details/gtsnfixqgk.html

PHP:  public string $name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtzrebnxke.html

JS:   this.name = "x";
来源：http://dali.yuxming.cn/Article/details/gtvjjcmkcl.html

TS:   name: string = "x";
来源：http://dali.9152youxi.cn/Article/details/gtgzsjdfgc.html

Java: private String name;
来源：http://dali.yanxiufei.cn/Article/details/gtksbxqejj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xylfe.cn/Article/details/gtkqaivivz.html

Ruby: @name = "x"
来源：http://dali.zhengqikj.top/Article/details/gtoymipzqa.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gteeblmaqt.html

[G04] 定义方法
来源：http://dali.yanxiufei.cn/Article/details/gtjmcjigui.html

Py:   def greet(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gtgywiiorj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtpkelmxvd.html

JS:   greet() { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtjfbgmhst.html

TS:   greet(): string { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtztifpjoo.html

Java: String greet() { return name; }
来源：http://dali.fzhhl.top/Article/details/gtgmxwmwwq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gtlwjqcmsw.html

Ruby: def greet; @name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaftshjgr.html

C#:   public string Greet() => Name;
来源：http://dali.jiagoushi.top/Article/details/gtaipdjnga.html

[G05] 继承
来源：http://dali.jinqigufen.top/Article/details/gtfrlwijsm.html

Py:   class Admin(User): pass
来源：http://dali.hongshengwenyu.top/Article/details/gtnysehlsn.html

PHP:  class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gtxiqtwfjx.html

JS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtchxmdndr.html

TS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtkioxhrol.html

Java: class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gttcaubjsa.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guannengcc.top/Article/details/gtzmtcohsl.html

Ruby: class Admin < User; end
来源：http://dali.zhengqikj.top/Article/details/gtzznhbwli.html

C#:   class Admin : User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtvpbtuabu.html

[G06] 重写方法
来源：http://dali.xuanzx.com/Article/details/gtaxzklmvi.html

Py:   def greet(self): return "admin"
来源：http://dali.jyoumei.cn/Article/details/gtexmpqctx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtgdkysmwu.html

JS:   greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtmxijokon.html

TS:   greet(): string { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtdakvzshr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtswtyujgq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sxryk.cn/Article/details/gtrljscoog.html

Ruby: def greet; "admin"; end
来源：http://dali.wangshuangyany.cn/Article/details/gteoxtcskr.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj202588.top/Article/details/gtcvctvvfo.html

[G07] 调用父类方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpsqxoyjf.html

Py:   super().greet()
来源：http://dali.jinqigfzy.top/Article/details/gtrimmklnq.html

PHP:  parent::greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtisqhzbmm.html

JS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtxjhmlayv.html

TS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gtrgzrvdgp.html

Java: super.greet();
来源：http://dali.guannengcc.top/Article/details/gtsyahisrc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jlsjyb.cn/Article/details/gthpqptifg.html

Ruby: super
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldakgcwf.html

C#:   base.Greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtgnlhoksj.html

[G08] 静态方法与属性
来源：http://dali.yj202588.top/Article/details/gtzkqtndud.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gzhubu.top/Article/details/gtghpaskdp.html

PHP:  public static function f() {}
来源：http://dali.hammf.cn/Article/details/gtysqkznbp.html

JS:   static f() {}
来源：http://dali.yj202588.top/Article/details/gtjkqetikd.html

TS:   static f(): void {}
来源：http://dali.tianlin.xyz/Article/details/gtlxrtieoh.html

Java: static void f() {}
来源：http://dali.jianghu66.top/Article/details/gtfgtusliu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gaohongyu789.top/Article/details/gtktlbncet.html

Ruby: def self.f; end
来源：http://dali.tian-w.cn/Article/details/gtrgqkxpib.html

C#:   public static void F() {}
来源：http://dali.aizwys.cn/Article/details/gtisvzfjdj.html

[G09] 接口 / 抽象类
来源：http://dali.chenzaomai.com/Article/details/gtjfsoaeek.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgfzy.top/Article/details/gtgsaswwmj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tanke756.top/Article/details/gtmildqfjp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cdnleiting.top/Article/details/gtrotgurjq.html

TS:   interface Shape { area(): number; }
来源：http://dali.jqgfzy.top/Article/details/gtalkdxhqh.html

Java: interface Shape { double area(); }
来源：http://dali.ybcxt.top/Article/details/gtijglribw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yongpay.top/Article/details/gtuoalmjoq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zdqjudy.top/Article/details/gtyukdliyr.html

C#:   interface IShape { double Area(); }
来源：http://dali.bjfxy.top/Article/details/gttgmbiept.html

[G10] 访问控制
来源：http://dali.jlsjyb.cn/Article/details/gtgtawwfye.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dianchejie.cn/Article/details/gtxomdjfhh.html

PHP:  public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtvzwpkhzz.html

JS:   #private 字段；其余公开
来源：http://dali.hnxiangtu.top/Article/details/gtthiigwbo.html

TS:   public / protected / private
来源：http://dali.bjfxy.top/Article/details/gtrifhtvfk.html

Java: public / protected / private / 默认包级
来源：http://dali.cheryme.top/Article/details/gtsahykfal.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnxiangtu.top/Article/details/gtvgatamtv.html

Ruby: public / protected / private
来源：http://dali.cheryme.top/Article/details/gtwgjobsya.html

C#:   public / protected / private / internal
来源：http://dali.feifeiyinyue.top/Article/details/gtsjaltgao.html

[G11] getter / setter
来源：http://dali.xziqi.cn/Article/details/gtzkvnxvky.html

Py:   @property 与 @x.setter
来源：http://dali.kuanghao11.cn/Article/details/gtbondtdaq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtrocxudxb.html

JS:   get name() { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gtixgfthwf.html

TS:   get name(): string { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gtzkiijfgq.html

Java: public String getName() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbuggjjn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtpxgslqoh.html

Ruby: attr_accessor :name
来源：http://dali.ydzc1.top/Article/details/gtfjihmpjv.html

C#:   public string Name { get; set; }
来源：http://dali.jlsjyb.cn/Article/details/gttskjujvb.html

[G12] 对象转字符串
来源：http://dali.yj20258.top/Article/details/gtxmyolcmi.html

Py:   def __str__(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gtspyfwtgp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gtdvbnwbmb.html

JS:   toString() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtvvxpcbha.html

TS:   toString(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtmgffgpxp.html

Java: @Override public String toString() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtquyanpce.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtkceeihrw.html

Ruby: def to_s; @name; end
来源：http://dali.c1oappe.top/Article/details/gtqhdxxoxa.html

C#:   public override string ToString() => Name;
来源：http://dali.yongpay.top/Article/details/gtvphhczty.html

[G13] 判断对象类型
来源：http://dali.316326.xyz/Article/details/gtiowedikt.html

Py:   isinstance(u, User)
来源：http://dali.hnxiangtu.top/Article/details/gtzuyysbul.html

PHP:  $u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtredsdzlp.html

JS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtinnzttbk.html

TS:   u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gthhxwhxkx.html

Java: u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtggxnwqqs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.havefunace.top/Article/details/gthuaqssjq.html

Ruby: u.is_a?(User)
来源：http://dali.jinqigufen.top/Article/details/gtrlkdfgnv.html

C#:   u is User
来源：http://dali.cdnleiting.top/Article/details/gtogrnffyu.html

[G14] 数据类 / record
来源：http://dali.ydzc1.top/Article/details/gtalwowrvw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sufxvd.cn/Article/details/gtieyqzdrx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yangfankeji.com/Article/details/gtxspsxhmg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ppjwa.cn/Article/details/gtnvtdzvvv.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhixingplan.top/Article/details/gtpxckvlct.html

Java: record User(String name, int age) {}
来源：http://dali.meibo888.top/Article/details/gtlcoqadrz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.vqdsnc.cn/Article/details/gtdkhrcoai.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sxryk.cn/Article/details/gtklhwmjji.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258888.top/Article/details/gtfhurajdd.html

[G15] 枚举
来源：http://dali.daria6918.cn/Article/details/gtxvncgwwn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zdqjudy.top/Article/details/gtqfnivfir.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hysaishi.cn/Article/details/gtkvksdmse.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangdashe.top/Article/details/gtxczmjyfn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtivneqxsp.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigfzy.top/Article/details/gtarktttab.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guannengcc.top/Article/details/gtvahuyfvz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgufenzy.top/Article/details/gtqxmmbwmc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gtgqwrawem.html

[G16] 对象转数组 / 字典
来源：http://dali.jiagoushi.top/Article/details/gtjhxokzzp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cheryme.top/Article/details/gtomjvpwvg.html

PHP:  get_object_vars($obj);
来源：http://dali.tanke756.top/Article/details/gtdfcfwqfe.html

JS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtoklcyomz.html

TS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gtznuppskv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ehwqpu.com/Article/details/gtruzamyxc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shuidangran.top/Article/details/gtfranfrqz.html

Ruby: obj.instance_variables
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfzaiwjh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gtavjryayk.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtlgnkqavn.html

H. 异常与错误处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtnxuojotp.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtzomgfemc.html

[H01] try / catch 基础
来源：http://dali.shzxlz.cn/Article/details/gtmihvwvsq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dashuyun.cn/Article/details/gtnidyizoa.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zycfv.cn/Article/details/gtluwbwmjq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gtpbpkqjgl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gtbynuoxev.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ivvv.top/Article/details/gtntldwvco.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuanzhike.top/Article/details/gtcvyafbzf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zycfv.cn/Article/details/gtjxcbjdyx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daria6918.cn/Article/details/gtjcrayqls.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258.top/Article/details/gtclruqmqs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yueranfly.top/Article/details/gtejprxfpp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtqvxsvcek.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtevokzggl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtlcletksh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtnhrttcrm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cashguo.top/Article/details/gttfxsdroy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.havefunace.top/Article/details/gtfsgmakfz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtzbqpskto.html

[H03] 主动抛出异常
来源：http://dali.hfpthk.cn/Article/details/gtobyuauwy.html

Py:   raise ValueError("错误信息")
来源：http://dali.tianlin.xyz/Article/details/gtpnodralm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihvgzuse.html

JS:   throw new Error("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtqphrkglz.html

TS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtzekfnvps.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gttkavlbow.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.vqdsnc.cn/Article/details/gtkhiwjykv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigfzy.top/Article/details/gtlbhevixi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtwtlehily.html

[H04] 自定义异常类型
来源：http://dali.gzhubu.top/Article/details/gtjvdpldvw.html

Py:   class MyError(Exception): pass
来源：http://dali.guowangkeji.top/Article/details/gtrlaeayan.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gtulpvqpch.html

JS:   class MyError extends Error {}
来源：http://dali.tian-w.cn/Article/details/gtiuvmorwe.html

TS:   class MyError extends Error {}
来源：http://dali.yueranfly.top/Article/details/gtltfvzqvb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gtfcypdzrw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cucudq.cn/Article/details/gtmfxsvygs.html

Ruby: class MyError < StandardError; end
来源：http://dali.hywenlv.cn/Article/details/gtjpyslqnr.html

C#:   class MyException : Exception {}
来源：http://dali.yuxming.cn/Article/details/gtdmgfoxoy.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gtteyxpgsh.html

Py:   except ValueError as e:
来源：http://dali.cashguo.top/Article/details/gtnoysxccy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tian-w.cn/Article/details/gtnxjmoqxh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtudxpwfqz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shuidangran.top/Article/details/gtrsmnqayd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.havefunace.top/Article/details/gtdgnixlqw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258888.top/Article/details/gteijivzdo.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigufen.top/Article/details/gtvluzyapo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gaohongyu789.top/Article/details/gtsvmmonbd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xziqi.cn/Article/details/gtttmacvem.html

Py:   value = d.get("k") or default
来源：http://dali.xylfe.cn/Article/details/gtbykzwzke.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sxryk.cn/Article/details/gtesdrojwu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhoulong.xyz/Article/details/gtnzgarvub.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.snrcjt.cn/Article/details/gtciylxcfk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sxryk.cn/Article/details/gtybdneszt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj202588.top/Article/details/gtcxrhkqkn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cucudq.cn/Article/details/gtuojmgurl.html

C#:   obj?.A?.B ?? default
来源：http://dali.xziqi.cn/Article/details/gtosmvtbyb.html

[H07] 断言
来源：http://dali.sufxvd.cn/Article/details/gthqvcevrp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.mhx1999.top/Article/details/gtxbjtinvx.html

PHP:  assert($x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtexwhmcql.html

JS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtsnhztrns.html

TS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtwwnsehof.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhiwuduotai.top/Article/details/gtppyxmfqm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj202588.top/Article/details/gtmsyvypzq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jlsjyb.cn/Article/details/gtjlusghfd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtfdwzmxch.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnqzz.top/Article/details/gtqyzfgchw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cdnleiting.top/Article/details/gtokxkftnp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.0kj1m.cn/Article/details/gtpjnnqpez.html

JS:   e.message;  e.stack
来源：http://dali.yj20258.top/Article/details/gtkblvyyno.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pengpengdd.cyou/Article/details/gtiaccqnkb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.wangdashe.top/Article/details/gtqndxujbs.html

Go:   err.Error()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvbycrpd.html

Ruby: e.message;  e.backtrace
来源：http://dali.tian-w.cn/Article/details/gtvelikljy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gaohongyu789.top/Article/details/gtjllyyeji.html

[H09] 带错误码的异常
来源：http://dali.yj202588.top/Article/details/gtjoafwxok.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dashuyun.cn/Article/details/gtlochuqfe.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyznwmlte.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jqgufenzy.top/Article/details/gtlzqfpkbi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.feifeiyinyue.top/Article/details/gtegqgpecm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gotoacloud.top/Article/details/gtqhqmadpg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.0kj1m.cn/Article/details/gtguwsqnwo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shzxlz.cn/Article/details/gtpnpcjkrw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shangyingyoupin.top/Article/details/gthdzlkdzl.html

[H10] 资源自动释放
来源：http://dali.ivvv.top/Article/details/gtqtqpsoqr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj202588.top/Article/details/gtckpeqbmh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shuidangran.top/Article/details/gthlqpbtxb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.vqdsnc.cn/Article/details/gtzpwrninn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjqxjzvn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hfpthk.cn/Article/details/gtfqltczgs.html

Go:   defer f.Close()
来源：http://dali.ybcxt.top/Article/details/gtblpnismu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.aibaodan.cn/Article/details/gtfxugotxg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtpgsnlwgn.html


<!-- 参考信息 -->