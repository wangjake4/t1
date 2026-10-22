代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.hnqzz.top/Article/details/gttkborbjk.html

[F06] 删除文件
来源：http://dali.pycfn.com/Article/details/gtilrgviwn.html

Py:   os.remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtznxscugf.html

PHP:  unlink("a.txt");
来源：http://dali.birdmap.top/Article/details/gtvlldxxsc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtkgvrxrxx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtpzfukjud.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtnhkojvzx.html

Go:   os.Remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtediincdy.html

Ruby: File.delete("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtfjgrxoou.html

C#:   File.Delete("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtklleigqq.html

[F07] 创建目录（含多级）
来源：http://dali.pengpengdd.cyou/Article/details/gtkzcqqiss.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xylfe.cn/Article/details/gtxckyvhdm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxinkj.top/Article/details/gtyyoryzep.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhnrdfzk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258888.top/Article/details/gtfdvfbrul.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nwbrower.top/Article/details/gthffqzwoo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cqqwz.cn/Article/details/gteblcgcqe.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.vqdsnc.cn/Article/details/gtvzufjgpl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dianchejie.cn/Article/details/gtdbfvhbew.html

[F08] 遍历目录
来源：http://dali.yangfankeji.com/Article/details/gtchcwvnwt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guannengcc.top/Article/details/gtvzrqazyy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxuanxn.top/Article/details/gtihalxhhg.html

JS:   fs.readdirSync("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtrlkmvwqx.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdtglqnhd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hywenlv.cn/Article/details/gtckypxnsx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cucudq.cn/Article/details/gtzzesxmoe.html

Ruby: Dir.children("dir")
来源：http://dali.fengsongda.top/Article/details/gtafrdevgh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ppjwa.cn/Article/details/gtsptadriw.html

[F09] 获取文件大小
来源：http://dali.zhoulong.xyz/Article/details/gtxmxajthc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sysykeji.top/Article/details/gttwiwkgyg.html

PHP:  filesize("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gttmndcnui.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gthtkvaxes.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sxryk.cn/Article/details/gtsaqhgohh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtvxkqnojs.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.meibo888.top/Article/details/gtuhrgnhmw.html

Ruby: File.size("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtxwcwihor.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gaohongyu789.top/Article/details/gthoepaetm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.dashuyun.cn/Article/details/gtevcqtylr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtuipwqtnt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zycfv.cn/Article/details/gtuoujbihu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtasxyrqje.html

TS:   path.extname("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxmjawnkq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.vqdsnc.cn/Article/details/gtgcblytzi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzlmchmit.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtswkvcswi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtnrfbbkve.html

[F11] 复制与移动文件
来源：http://dali.daria6918.cn/Article/details/gtgnbvjfbn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtwsezedpd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinqigfzy.top/Article/details/gttziqvprd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtjnaovqjs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtephnyiaw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsuwrxane.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.svipenyu.cn/Article/details/gtmuqhhjsj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtwnptzbvc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yanxiufei.cn/Article/details/gtlrxmfltt.html

[F12] CSV 读写
来源：http://dali.fzhhl.top/Article/details/gtygydnvqp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zdqjudy.top/Article/details/gtrhgwkgzn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guannengcc.top/Article/details/gtcgxcjmkd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shangyingyoupin.top/Article/details/gtehbuioyf.html

TS:   // 同上
来源：http://dali.0kj1m.cn/Article/details/gtmiqrsowv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shanyushiyangtech.top/Article/details/gttvfxztju.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jlsjyb.cn/Article/details/gtqvgzzxdw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxinkj.top/Article/details/gtcrvzvzmc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zycfv.cn/Article/details/gtiaebyswq.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtbgdjhpvr.html

G. 面向对象
来源：http://dali.yj20258.top/Article/details/gtjudwqalb.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtmrldttbj.html

[G01] 定义类
来源：http://dali.nanxuanxn.top/Article/details/gtobplkati.html

Py:   class User: pass
来源：http://dali.zhiwuduotai.top/Article/details/gtapxqudhq.html

PHP:  class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtgoxksuul.html

JS:   class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gthbtcjlib.html

TS:   class User { name: string = ""; }
来源：http://dali.gaohongyu789.top/Article/details/gtfhvkcrcp.html

Java: class User {}
来源：http://dali.xziqi.cn/Article/details/gtpimqkhdk.html

Go:   type User struct { Name string }
来源：http://dali.vqdsnc.cn/Article/details/gtucqrhtfg.html

Ruby: class User; end
来源：http://dali.xinyue.icu/Article/details/gtxohpvlmy.html

C#:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtcngzxeev.html

[G02] 构造函数
来源：http://dali.dianchejie.cn/Article/details/gtpbekcavb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cucudq.cn/Article/details/gtjerlbaot.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dashuyun.cn/Article/details/gtsciqpkjp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtvzakatev.html

TS:   constructor(public name: string) {}
来源：http://dali.daxiang520.top/Article/details/gtdfsjeajg.html

Java: User(String name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gtglsxgivh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.snrcjt.cn/Article/details/gtfeigqiyv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nwbrower.top/Article/details/gtxyisiqfw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gtutfobqbb.html

[G03] 实例属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gtibistfbb.html

Py:   self.name = "x"
来源：http://dali.aizwys.cn/Article/details/gthivoljuz.html

PHP:  public string $name = "x";
来源：http://dali.jqgfzy.top/Article/details/gtfmqpdkbh.html

JS:   this.name = "x";
来源：http://dali.yueranfly.top/Article/details/gtqmljrvgg.html

TS:   name: string = "x";
来源：http://dali.yj202588.top/Article/details/gtguhztfez.html

Java: private String name;
来源：http://dali.hnqzz.top/Article/details/gtpafkrwnr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkgbosfss.html

Ruby: @name = "x"
来源：http://dali.xinyue.icu/Article/details/gtsefipico.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtanpyrhld.html

[G04] 定义方法
来源：http://dali.ybcxt.top/Article/details/gtadjwvxrv.html

Py:   def greet(self): return self.name
来源：http://dali.yangfankeji.com/Article/details/gtvegaaeab.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gtqciruzyg.html

JS:   greet() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtuvqfcxua.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtlqdejquf.html

Java: String greet() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtosfrlqqq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtyombdhsr.html

Ruby: def greet; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtyxssialb.html

C#:   public string Greet() => Name;
来源：http://dali.jianghu66.top/Article/details/gtsfuuejkp.html

[G05] 继承
来源：http://dali.pycfn.com/Article/details/gtbwvgsowl.html

Py:   class Admin(User): pass
来源：http://dali.0kj1m.cn/Article/details/gtlkadnnnn.html

PHP:  class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtwfdyviop.html

JS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gthdsqcohs.html

TS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtablvhame.html

Java: class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtusdgymso.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.havefunace.top/Article/details/gtsawvncyz.html

Ruby: class Admin < User; end
来源：http://dali.nanxinkj.top/Article/details/gtnavtlros.html

C#:   class Admin : User {}
来源：http://dali.haohaochexian.top/Article/details/gtskhycjog.html

[G06] 重写方法
来源：http://dali.zdqjudy.top/Article/details/gtqoypoopz.html

Py:   def greet(self): return "admin"
来源：http://dali.guowangkeji.top/Article/details/gtvvcylxhr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtqswmnsft.html

JS:   greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtbvamauni.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtxkrdodov.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtovbczwls.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ppjwa.cn/Article/details/gtxzmjpshp.html

Ruby: def greet; "admin"; end
来源：http://dali.yuxming.cn/Article/details/gtkgtqnqcl.html

C#:   public override string Greet() => "admin";
来源：http://dali.pengpengdd.cyou/Article/details/gtpfyqhkck.html

[G07] 调用父类方法
来源：http://dali.meibo888.top/Article/details/gtvouyswjd.html

Py:   super().greet()
来源：http://dali.gotoacloud.top/Article/details/gthoaujjip.html

PHP:  parent::greet();
来源：http://dali.redwolf501.top/Article/details/gtcufqknbz.html

JS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gteshufhek.html

TS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtddrxypeq.html

Java: super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtxljsrpjn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258888.top/Article/details/gttziszwxc.html

Ruby: super
来源：http://dali.cdnleiting.top/Article/details/gtzthwesxe.html

C#:   base.Greet();
来源：http://dali.c1oappe.top/Article/details/gteocqkrnl.html

[G08] 静态方法与属性
来源：http://dali.zycfv.cn/Article/details/gtinrvartq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cdnleiting.top/Article/details/gthqgovhax.html

PHP:  public static function f() {}
来源：http://dali.yonumen.top/Article/details/gthdmbaicl.html

JS:   static f() {}
来源：http://dali.kuanghao11.cn/Article/details/gtqniolktm.html

TS:   static f(): void {}
来源：http://dali.gaohongyu789.top/Article/details/gtlgdfswlj.html

Java: static void f() {}
来源：http://dali.yonumen.top/Article/details/gtzwprizsy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.aizwys.cn/Article/details/gtnoowvhxn.html

Ruby: def self.f; end
来源：http://dali.xinyue.icu/Article/details/gtxhrnrhmt.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfxtfzdw.html

[G09] 接口 / 抽象类
来源：http://dali.xuanzx.com/Article/details/gtfmxytuzx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hongshengwenyu.top/Article/details/gtseiavkqb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.svipenyu.cn/Article/details/gtncftavyt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zdqjudy.top/Article/details/gtcvbfafdv.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenlongwang.top/Article/details/gtebvoacmh.html

Java: interface Shape { double area(); }
来源：http://dali.zdqjudy.top/Article/details/gtdluhpskv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hnqzz.top/Article/details/gtoerdlfzo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.bjfxy.top/Article/details/gtunechcnp.html

C#:   interface IShape { double Area(); }
来源：http://dali.c1oappe.top/Article/details/gthlqnemej.html

[G10] 访问控制
来源：http://dali.hnxiangtu.top/Article/details/gtxgrsoern.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.redwolf501.top/Article/details/gteejosncg.html

PHP:  public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gtecdhmisj.html

JS:   #private 字段；其余公开
来源：http://dali.ydzc1.top/Article/details/gtxrwseiyn.html

TS:   public / protected / private
来源：http://dali.cashguo.top/Article/details/gtcashenyl.html

Java: public / protected / private / 默认包级
来源：http://dali.snrcjt.cn/Article/details/gtclzwhuvz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jqgufenzy.top/Article/details/gtipkxaczg.html

Ruby: public / protected / private
来源：http://dali.yvedp.cn/Article/details/gtlhqjujde.html

C#:   public / protected / private / internal
来源：http://dali.ydzc1.top/Article/details/gtmeifnhel.html

[G11] getter / setter
来源：http://dali.hammf.cn/Article/details/gtbsywigum.html

Py:   @property 与 @x.setter
来源：http://dali.zhixingplan.top/Article/details/gthkvhkucc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvctxstot.html

JS:   get name() { return this._name; }
来源：http://dali.jqgfzy.top/Article/details/gtjxscbhpi.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj202588.top/Article/details/gtdrvczwnj.html

Java: public String getName() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gteohjxduf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gtvmxfvuom.html

Ruby: attr_accessor :name
来源：http://dali.wangshuangyany.cn/Article/details/gtofbumdvb.html

C#:   public string Name { get; set; }
来源：http://dali.zhixingplan.top/Article/details/gtnrvoialm.html

[G12] 对象转字符串
来源：http://dali.hfpthk.cn/Article/details/gtafprbejv.html

Py:   def __str__(self): return self.name
来源：http://dali.quarkkingdee.top/Article/details/gtlvmdauko.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gtwxsvgybs.html

JS:   toString() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtvdjrygal.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtdlzppafn.html

Java: @Override public String toString() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtvdtpgnhn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtlmsabiqq.html

Ruby: def to_s; @name; end
来源：http://dali.yongpay.top/Article/details/gtmxydmnrw.html

C#:   public override string ToString() => Name;
来源：http://dali.svipenyu.cn/Article/details/gtxnbjialc.html

[G13] 判断对象类型
来源：http://dali.zdqjudy.top/Article/details/gtwpdsnqug.html

Py:   isinstance(u, User)
来源：http://dali.jqgfzy.top/Article/details/gtcxyfzafc.html

PHP:  $u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtnlqfdmjm.html

JS:   u instanceof User
来源：http://dali.tanke756.top/Article/details/gtzneaelhr.html

TS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtshcyxbfr.html

Java: u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtelyewkkm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.havefunace.top/Article/details/gtxjpyizgu.html

Ruby: u.is_a?(User)
来源：http://dali.xylfe.cn/Article/details/gtfbhofpoa.html

C#:   u is User
来源：http://dali.yj20258.top/Article/details/gtxzswjxxm.html

[G14] 数据类 / record
来源：http://dali.yuanzhike.top/Article/details/gtvqshmkxo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nwbrower.top/Article/details/gtjlsuebuc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.smart0.xyz/Article/details/gtjlgejwjl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yvedp.cn/Article/details/gtziplsyey.html

TS:   type User = { name: string; age: number };
来源：http://dali.pengpengdd.cyou/Article/details/gtfongoila.html

Java: record User(String name, int age) {}
来源：http://dali.haohaochexian.top/Article/details/gtcnbcwrbv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yvedp.cn/Article/details/gtnrrdphmq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guannengcc.top/Article/details/gtgyustset.html

C#:   record User(string Name, int Age);
来源：http://dali.vqdsnc.cn/Article/details/gtmgdeaije.html

[G15] 枚举
来源：http://dali.jinqigufen.top/Article/details/gtvrwxydyo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guannengcc.top/Article/details/gthsifahpw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.pengpengdd.cyou/Article/details/gteckfpwgg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.feifeiyinyue.top/Article/details/gtbvvcbtax.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fengsongda.top/Article/details/gtekypbqzc.html

Java: enum Color { RED, GREEN }
来源：http://dali.quarkkingdee.top/Article/details/gtwsftviof.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daria6918.cn/Article/details/gtixzeagdz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tanke756.top/Article/details/gtsmjnovdp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtlpyjxcbh.html

[G16] 对象转数组 / 字典
来源：http://dali.pengpengdd.cyou/Article/details/gtnixcxtyv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jiagoushi.top/Article/details/gtiypydzaa.html

PHP:  get_object_vars($obj);
来源：http://dali.c1oappe.top/Article/details/gtrdwppzfz.html

JS:   Object.entries(obj)
来源：http://dali.jqgfzy.top/Article/details/gtmjzvmeuh.html

TS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gtigqukstf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.meibo888.top/Article/details/gtjrtewcmu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cheryme.top/Article/details/gtgbgejirf.html

Ruby: obj.instance_variables
来源：http://dali.zhiwuduotai.top/Article/details/gtwqteyvld.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gtamrkwgcb.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gttxdkgula.html

H. 异常与错误处理
来源：http://dali.sweek.top/Article/details/gtdpjmgmgj.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gttrubmgsj.html

[H01] try / catch 基础
来源：http://dali.zhoulong.xyz/Article/details/gtqigmtcaf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jianghu66.top/Article/details/gtgphmmyuw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jyoumei.cn/Article/details/gtkryluohw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gtbcepqute.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gotoacloud.top/Article/details/gtkdwgvszo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yanxiufei.cn/Article/details/gtpagufrzk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnuduqifs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yanxiufei.cn/Article/details/gtodtbqltd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxgbnyui.html

[H02] finally / ensure 收尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfydynucs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigufen.top/Article/details/gtzuyavupd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtziqufrer.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtwfevhfwj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gthlkgsknl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtftvychsq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daria6918.cn/Article/details/gtmfckgusy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yvedp.cn/Article/details/gtjriygcmy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtcyushrlc.html

[H03] 主动抛出异常
来源：http://dali.smart0.xyz/Article/details/gtzportqvi.html

Py:   raise ValueError("错误信息")
来源：http://dali.vqdsnc.cn/Article/details/gtiragaobu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtxtjuknuo.html

JS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gteicnmumx.html

TS:   throw new Error("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtpmdoruzd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gtrorlbcaz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zdqjudy.top/Article/details/gtqunulkij.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuanzx.com/Article/details/gtgwjvkpoa.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtbcnpqgee.html

[H04] 自定义异常类型
来源：http://dali.tanke756.top/Article/details/gtmvasjyma.html

Py:   class MyError(Exception): pass
来源：http://dali.fzhhl.top/Article/details/gtqvvyymly.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.vqdsnc.cn/Article/details/gtemdnagnx.html

JS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gtggrtonkt.html

TS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gtxqidnhtc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.dashuyun.cn/Article/details/gtchrqapyl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yonumen.top/Article/details/gtsovovwlb.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhoulong.xyz/Article/details/gtnduwidno.html

C#:   class MyException : Exception {}
来源：http://dali.cucudq.cn/Article/details/gtveugdzym.html

[H05] 捕获特定类型
来源：http://dali.kuanghao11.cn/Article/details/gttymtwpcb.html

Py:   except ValueError as e:
来源：http://dali.hywenlv.cn/Article/details/gtgdnjzrzr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.vqdsnc.cn/Article/details/gthsiahrcd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gtdvkjwfxz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hnxiangtu.top/Article/details/gtrcvkzpnl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aizwys.cn/Article/details/gtsmxgixtz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yanxiufei.cn/Article/details/gttcsvycsq.html

Ruby: rescue ArgumentError => e
来源：http://dali.cheryme.top/Article/details/gtumxhubsz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgroeiltr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhoulong.xyz/Article/details/gtxqndmszy.html

Py:   value = d.get("k") or default
来源：http://dali.quarkkingdee.top/Article/details/gtcidzxslm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj20258888.top/Article/details/gtyevhouzv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gtfdzngtja.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gtzbbcfaep.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gogol.net.cn/Article/details/gtqwcbojav.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnlqooitq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ydzc1.top/Article/details/gtunfiyyzb.html

C#:   obj?.A?.B ?? default
来源：http://dali.9152youxi.cn/Article/details/gtmiaksjhr.html

[H07] 断言
来源：http://dali.zdqjudy.top/Article/details/gtbslajxkr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yuanzhike.top/Article/details/gtcdkryglv.html

PHP:  assert($x > 0);
来源：http://dali.daria6918.cn/Article/details/gtawhgoagn.html

JS:   console.assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtlgnozebx.html

TS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gttumrdhmk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guowangkeji.top/Article/details/gtbhvsxdir.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xinyue.icu/Article/details/gtphswpfhc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cqqwz.cn/Article/details/gtafkyofrt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gtioxldphr.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenjidiqi.icu/Article/details/gtafgkdntx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxuanxn.top/Article/details/gtisxjmwcy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yongpay.top/Article/details/gteexolgwq.html

JS:   e.message;  e.stack
来源：http://dali.zhixingplan.top/Article/details/gtizasbmfq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.smart0.xyz/Article/details/gtnuaxelyu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.pycfn.com/Article/details/gtuflifdob.html

Go:   err.Error()
来源：http://dali.chenlongwang.top/Article/details/gtsfxiyuew.html

Ruby: e.message;  e.backtrace
来源：http://dali.iojbl.cn/Article/details/gtjobnogja.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pycfn.com/Article/details/gtmgypkcqi.html

[H09] 带错误码的异常
来源：http://dali.ehwqpu.com/Article/details/gtyvuvyeob.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.birdmap.top/Article/details/gtvtbzmugh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guannengcc.top/Article/details/gtrrrgxhlz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhoulong.xyz/Article/details/gtitujrshk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gzhubu.top/Article/details/gtesllkcze.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.9152youxi.cn/Article/details/gtowdejosk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yueranfly.top/Article/details/gtwhyrhcan.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.feifeiyinyue.top/Article/details/gtsyrkntqm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.havefunace.top/Article/details/gtaaltqcsh.html

[H10] 资源自动释放
来源：http://dali.jiagoushi.top/Article/details/gtbwhmuijx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hnxiangtu.top/Article/details/gtkirbjwud.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yonumen.top/Article/details/gtpgkzlugv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gteovdbuka.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gtsioqnfzg.html


<!-- 参考信息 -->