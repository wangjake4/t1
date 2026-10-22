代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2qqetdlby.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2novsxssn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gt2hsrmjufh.html

Go:   os.Remove("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2dmyumiqh.html

Ruby: File.delete("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zelbckii.html

C#:   File.Delete("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2czzwaium.html

[F07] 创建目录（含多级）
来源：http://dali.nwbrower.top/Article/details/gt2duorqqjz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cqqwz.cn/Article/details/gt2qovbzzbj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258888.top/Article/details/gt2ibzhkhtb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.vqdsnc.cn/Article/details/gt2ewunryiv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenlongwang.top/Article/details/gt2sqnuirrw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dashuyun.cn/Article/details/gt2tqmcthgm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.vqdsnc.cn/Article/details/gt2zgpkjxzb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yuxming.cn/Article/details/gt2bdhkjmum.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yonumen.top/Article/details/gt2xsvmnlvi.html

[F08] 遍历目录
来源：http://dali.snrcjt.cn/Article/details/gt2xbpwyrhr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nwbrower.top/Article/details/gt2xlswpbnx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.bjfxy.top/Article/details/gt2bguhrbcf.html

JS:   fs.readdirSync("dir")
来源：http://dali.shuidangran.top/Article/details/gt2hatdvrwi.html

TS:   fs.readdirSync("dir")
来源：http://dali.hysaishi.cn/Article/details/gt2qlywvijh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kjmosepa.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hywenlv.cn/Article/details/gt2tilylbdr.html

Ruby: Dir.children("dir")
来源：http://dali.hfpthk.cn/Article/details/gt2nqeeetcq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gt2wkkpwvrj.html

[F09] 获取文件大小
来源：http://dali.chenjidiqi.icu/Article/details/gt2yxhcnjqf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2uflpkhts.html

PHP:  filesize("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2qtlgryge.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zdqjudy.top/Article/details/gt2heqchvdk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hnxiangtu.top/Article/details/gt2obejqrve.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gt2burtsqdk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ivvv.top/Article/details/gt2qajrhgbh.html

Ruby: File.size("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2vtlarbxc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sxryk.cn/Article/details/gt2cbjneozx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuanzx.com/Article/details/gt2wtoizgpv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2uuoyvrbn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2fedwlamq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gt2ycmtsqia.html

TS:   path.extname("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2xmfshjwx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jqgfzy.top/Article/details/gt2lehenmnt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2agznmrui.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2ozuwlxfn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2wkrzwpjj.html

[F11] 复制与移动文件
来源：http://dali.yonumen.top/Article/details/gt2nxzhqyyy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2xkfscgme.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj202588.top/Article/details/gt2xszlhvhy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gt2azxjodby.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2nibxlggg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shuidangran.top/Article/details/gt2ymlojryg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guannengcc.top/Article/details/gt2jiicpisg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2cykqboop.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.wangdashe.top/Article/details/gt2lfyxcoev.html

[F12] CSV 读写
来源：http://dali.nanxinkj.top/Article/details/gt2wootxxid.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tianlin.xyz/Article/details/gt2dvmnoumg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.pycfn.com/Article/details/gt2rvenhjla.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.snrcjt.cn/Article/details/gt2nrqfdvtx.html

TS:   // 同上
来源：http://dali.jqgfzy.top/Article/details/gt2mmmkiliv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sysykeji.top/Article/details/gt2qjglqusq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhengqikj.top/Article/details/gt2ernaegrz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pycfn.com/Article/details/gt2snhwrcky.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bzthgzmn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sosawlan.html

G. 面向对象
来源：http://dali.smart0.xyz/Article/details/gt2qctbnrvv.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2nllylkcs.html

[G01] 定义类
来源：http://dali.cashguo.top/Article/details/gt2dyglfcub.html

Py:   class User: pass
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pozzowls.html

PHP:  class User {}
来源：http://dali.hysaishi.cn/Article/details/gt2nawjedqn.html

JS:   class User {}
来源：http://dali.zycfv.cn/Article/details/gt2jhwgxwxz.html

TS:   class User { name: string = ""; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rtrweezq.html

Java: class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vmswtung.html

Go:   type User struct { Name string }
来源：http://dali.yonumen.top/Article/details/gt2wkbvuvmp.html

Ruby: class User; end
来源：http://dali.9152youxi.cn/Article/details/gt2aegejkbt.html

C#:   class User {}
来源：http://dali.316326.xyz/Article/details/gt2gksrxxcv.html

[G02] 构造函数
来源：http://dali.aizwys.cn/Article/details/gt2kfxsrpzw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.iojbl.cn/Article/details/gt2ytkhgvsy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.guannengcc.top/Article/details/gt2olppbczi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gt2bxakvksx.html

TS:   constructor(public name: string) {}
来源：http://dali.jyoumei.cn/Article/details/gt2vajlexnf.html

Java: User(String name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gt2utjtuuki.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.iojbl.cn/Article/details/gt2ndutdsbr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zycfv.cn/Article/details/gt2bdjkshiw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xuanzx.com/Article/details/gt2orgvaagz.html

[G03] 实例属性
来源：http://dali.cqqwz.cn/Article/details/gt2frgqjdld.html

Py:   self.name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gt2xaoyleqn.html

PHP:  public string $name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2sdjbekmu.html

JS:   this.name = "x";
来源：http://dali.jqgfzy.top/Article/details/gt2loblupfh.html

TS:   name: string = "x";
来源：http://dali.ybcxt.top/Article/details/gt2sezyjsvr.html

Java: private String name;
来源：http://dali.hfpthk.cn/Article/details/gt2bkdlkhtu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yuanzhike.top/Article/details/gt2dikhralu.html

Ruby: @name = "x"
来源：http://dali.smart0.xyz/Article/details/gt2vzssases.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuanzhike.top/Article/details/gt2ubnekorj.html

[G04] 定义方法
来源：http://dali.xziqi.cn/Article/details/gt2oahssfty.html

Py:   def greet(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gt2dvvcjewi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gt2wzgauddd.html

JS:   greet() { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gt2mftweycq.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2cblsjops.html

Java: String greet() { return name; }
来源：http://dali.sysykeji.top/Article/details/gt2fenrjrsv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gt2ffdhqucu.html

Ruby: def greet; @name; end
来源：http://dali.yuxming.cn/Article/details/gt2yysvhccp.html

C#:   public string Greet() => Name;
来源：http://dali.gotoacloud.top/Article/details/gt2fudfdqqu.html

[G05] 继承
来源：http://dali.pengpengdd.cyou/Article/details/gt2qqraforh.html

Py:   class Admin(User): pass
来源：http://dali.xylfe.cn/Article/details/gt2zelmahbt.html

PHP:  class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gt2vgthztxu.html

JS:   class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gt2arxsuqjd.html

TS:   class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ynjiifxo.html

Java: class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gt2tsxraqaj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.feifeiyinyue.top/Article/details/gt2gpsviwha.html

Ruby: class Admin < User; end
来源：http://dali.hnxiangtu.top/Article/details/gt2trtnotpk.html

C#:   class Admin : User {}
来源：http://dali.chenzaomai.com/Article/details/gt2zlmwgrvy.html

[G06] 重写方法
来源：http://dali.daxiang520.top/Article/details/gt2wvoezjea.html

Py:   def greet(self): return "admin"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fuuxarvf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gt2udhmvxut.html

JS:   greet() { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gt2rpxdyubm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2pswvwlzd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2buhapcnt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2gordboox.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigufen.top/Article/details/gt2iarymemz.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhixingplan.top/Article/details/gt2uecfcuop.html

[G07] 调用父类方法
来源：http://dali.pycfn.com/Article/details/gt2pvqbkqkw.html

Py:   super().greet()
来源：http://dali.dashuyun.cn/Article/details/gt2lwgcidke.html

PHP:  parent::greet();
来源：http://dali.jlsjyb.cn/Article/details/gt2avdjzvdb.html

JS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gt2ijpyhbtk.html

TS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gt2bikgvyvd.html

Java: super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gt2bdbdcexr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ydzc1.top/Article/details/gt2bwuwzovp.html

Ruby: super
来源：http://dali.cucudq.cn/Article/details/gt2aztbgwgc.html

C#:   base.Greet();
来源：http://dali.shangyingyoupin.top/Article/details/gt2gprqkcum.html

[G08] 静态方法与属性
来源：http://dali.yvedp.cn/Article/details/gt2jaddfaat.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuanzhike.top/Article/details/gt2ckejgcpk.html

PHP:  public static function f() {}
来源：http://dali.gzhubu.top/Article/details/gt2syeciqqj.html

JS:   static f() {}
来源：http://dali.yongpay.top/Article/details/gt2bnarxray.html

TS:   static f(): void {}
来源：http://dali.ppjwa.cn/Article/details/gt2ohxmniad.html

Java: static void f() {}
来源：http://dali.sufxvd.cn/Article/details/gt2clddyvsg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.smart0.xyz/Article/details/gt2pllkvbxv.html

Ruby: def self.f; end
来源：http://dali.chenzaomai.com/Article/details/gt2fbbfyufi.html

C#:   public static void F() {}
来源：http://dali.hywenlv.cn/Article/details/gt2rzgrvede.html

[G09] 接口 / 抽象类
来源：http://dali.cucudq.cn/Article/details/gt2bvjmrifk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xylfe.cn/Article/details/gt2ozcltadf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fzhhl.top/Article/details/gt2kaohmpdg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tanke756.top/Article/details/gt2nsyjyyaa.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj202588.top/Article/details/gt2snnnrcwn.html

Java: interface Shape { double area(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2pfjgjczk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hfpthk.cn/Article/details/gt2zeeostgl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fengsongda.top/Article/details/gt2zwimjmej.html

C#:   interface IShape { double Area(); }
来源：http://dali.yuanzhike.top/Article/details/gt2poyehgwf.html

[G10] 访问控制
来源：http://dali.quarkkingdee.top/Article/details/gt2ruypgmen.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xinyue.icu/Article/details/gt2vtafbiqt.html

PHP:  public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gt2upukfrtz.html

JS:   #private 字段；其余公开
来源：http://dali.daria6918.cn/Article/details/gt2wpwdppxo.html

TS:   public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gt2lrtdhsoc.html

Java: public / protected / private / 默认包级
来源：http://dali.jiagoushi.top/Article/details/gt2zvcyzfpx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rijhohzv.html

Ruby: public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gt2ontyvwbj.html

C#:   public / protected / private / internal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jccdneoh.html

[G11] getter / setter
来源：http://dali.dianchejie.cn/Article/details/gt2nwxuuunw.html

Py:   @property 与 @x.setter
来源：http://dali.yangfankeji.com/Article/details/gt2skariyip.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gt2scstbwrz.html

JS:   get name() { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gt2rxivcdvx.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxinkj.top/Article/details/gt2ftheytou.html

Java: public String getName() { return name; }
来源：http://dali.meibo888.top/Article/details/gt2whkpvpms.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gt2cjwngfph.html

Ruby: attr_accessor :name
来源：http://dali.jyoumei.cn/Article/details/gt2ucjoerlx.html

C#:   public string Name { get; set; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2joswhknt.html

[G12] 对象转字符串
来源：http://dali.yangfankeji.com/Article/details/gt2esuaucdp.html

Py:   def __str__(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ankxlezi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gt2daqwfvgv.html

JS:   toString() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gt2jjlxdvnz.html

TS:   toString(): string { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gt2cqfvqdaq.html

Java: @Override public String toString() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gt2fkljnzkx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gt2wuzoymug.html

Ruby: def to_s; @name; end
来源：http://dali.zhongyouzk.top/Article/details/gt2ryzrhnda.html

C#:   public override string ToString() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gt2fnhirhjz.html

[G13] 判断对象类型
来源：http://dali.jlsjyb.cn/Article/details/gt2ofacihos.html

Py:   isinstance(u, User)
来源：http://dali.tianlin.xyz/Article/details/gt2mprybiyc.html

PHP:  $u instanceof User
来源：http://dali.mhx1999.top/Article/details/gt2usglirvi.html

JS:   u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gt2vhzgilfd.html

TS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gt2zuhzlykn.html

Java: u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gt2dybdbkme.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.fengsongda.top/Article/details/gt2pfupoffd.html

Ruby: u.is_a?(User)
来源：http://dali.nanxinkj.top/Article/details/gt2ddkhhyia.html

C#:   u is User
来源：http://dali.ivvv.top/Article/details/gt2bpfhmnjv.html

[G14] 数据类 / record
来源：http://dali.vqdsnc.cn/Article/details/gt2rxehuoun.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.birdmap.top/Article/details/gt2bdpsjjbl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.vqdsnc.cn/Article/details/gt2nsnkpoqr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yvedp.cn/Article/details/gt2empktbap.html

TS:   type User = { name: string; age: number };
来源：http://dali.dianchejie.cn/Article/details/gt2cuxnttgm.html

Java: record User(String name, int age) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2bquczevd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pengpengdd.cyou/Article/details/gt2lnhwkpcn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuanzhike.top/Article/details/gt2qdzdufcg.html

C#:   record User(string Name, int Age);
来源：http://dali.yongpay.top/Article/details/gt2gwcjkiot.html

[G15] 枚举
来源：http://dali.yj20258888.top/Article/details/gt2jbfhyxlt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bpubdlqf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jjasvwkl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.meibo888.top/Article/details/gt2eneduvqu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gotoacloud.top/Article/details/gt2fagsxebv.html

Java: enum Color { RED, GREEN }
来源：http://dali.zdqjudy.top/Article/details/gt2npvkfrzo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gzhubu.top/Article/details/gt2wcgrkqew.html

Ruby: Color = %i[red green].freeze
来源：http://dali.fengsongda.top/Article/details/gt2lsigdkpn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hammf.cn/Article/details/gt2ewzullek.html

[G16] 对象转数组 / 字典
来源：http://dali.kuanghao11.cn/Article/details/gt2wkahbggc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.316326.xyz/Article/details/gt2tpfbfguo.html

PHP:  get_object_vars($obj);
来源：http://dali.chenjidiqi.icu/Article/details/gt2yamhwztv.html

JS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gt2kskmlgri.html

TS:   Object.entries(obj)
来源：http://dali.cucudq.cn/Article/details/gt2hbdihksd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dashuyun.cn/Article/details/gt2ddtimgoy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hammf.cn/Article/details/gt2mnjgzpzx.html

Ruby: obj.instance_variables
来源：http://dali.tian-w.cn/Article/details/gt2pxxdkgpu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gt2molfcpvo.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2pxnhxpdu.html

H. 异常与错误处理
来源：http://dali.zycfv.cn/Article/details/gt2hxfrsqcx.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2pnpqoaui.html

[H01] try / catch 基础
来源：http://dali.hfpthk.cn/Article/details/gt2vtejblfa.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.birdmap.top/Article/details/gt2mvvhcanw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yonumen.top/Article/details/gt2qboylnkx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2gydldlje.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gt2uusmrvig.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tian-w.cn/Article/details/gt2ldryivsx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xinyue.icu/Article/details/gt2llavegip.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.haohaochexian.top/Article/details/gt2woubaayu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sxryk.cn/Article/details/gt2xbulbvor.html

[H02] finally / ensure 收尾
来源：http://dali.0kj1m.cn/Article/details/gt2efevpuzu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cqqwz.cn/Article/details/gt2vksuwxhk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2gfyvgdgc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2rpanszan.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bcmmvgaz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gt2cstidedz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yuanzhike.top/Article/details/gt2ljsfjuss.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2khacjzqh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gt2ycllifho.html

[H03] 主动抛出异常
来源：http://dali.tanke756.top/Article/details/gt2vnfyjxnb.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenzaomai.com/Article/details/gt2ilxkoawt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vyehgzei.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2bbqfiamh.html

TS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gt2uzudmjvb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2bxmpwelg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.smart0.xyz/Article/details/gt2omawhlbu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jfpeawlx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gt2lrlsehqw.html

[H04] 自定义异常类型
来源：http://dali.yonumen.top/Article/details/gt2bvmhpqme.html

Py:   class MyError(Exception): pass
来源：http://dali.hnqzz.top/Article/details/gt2mgjmfiqu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2lkkvhuhi.html

JS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gt2lijldjnb.html

TS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2eazbcgpt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yuxming.cn/Article/details/gt2intqdguh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hysaishi.cn/Article/details/gt2ntunyups.html

Ruby: class MyError < StandardError; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2edpmmlcf.html

C#:   class MyException : Exception {}
来源：http://dali.jianghu66.top/Article/details/gt2abmavqmz.html

[H05] 捕获特定类型
来源：http://dali.yj202588.top/Article/details/gt2jahozjhh.html

Py:   except ValueError as e:
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ojnhettf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nwbrower.top/Article/details/gt2flbmrwag.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gt2ejrrdawp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gt2idwidhib.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hywenlv.cn/Article/details/gt2jcbsdbwl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258.top/Article/details/gt2wziqcobq.html

Ruby: rescue ArgumentError => e
来源：http://dali.kuanghao11.cn/Article/details/gt2acsmfxvu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cbmqgaep.html

[H06] 可选值 / 空值安全访问
来源：http://dali.svipenyu.cn/Article/details/gt2qwmxskax.html

Py:   value = d.get("k") or default
来源：http://dali.aibaodan.cn/Article/details/gt2ahhbgsmc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenjidiqi.icu/Article/details/gt2hiikymed.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gt2cjrqtmkg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.birdmap.top/Article/details/gt2plionmww.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yonumen.top/Article/details/gt2bgkwjcet.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.svipenyu.cn/Article/details/gt2iaoafgfi.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258.top/Article/details/gt2nsahzsis.html

C#:   obj?.A?.B ?? default
来源：http://dali.cashguo.top/Article/details/gt2rfxjedod.html

[H07] 断言
来源：http://dali.yuxming.cn/Article/details/gt2jvxfybek.html

Py:   assert x > 0, "必须为正"
来源：http://dali.birdmap.top/Article/details/gt2ewkgdaox.html

PHP:  assert($x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2odcxokpc.html

JS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gt2agjayuna.html

TS:   console.assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gt2wcdztnvq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cqqwz.cn/Article/details/gt2uhxfaist.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenzaomai.com/Article/details/gt2vanavekt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pengpengdd.cyou/Article/details/gt2xkllzsss.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gt2liytatbx.html

[H08] 获取错误信息与堆栈
来源：http://dali.dianchejie.cn/Article/details/gt2kwhrbjjc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2izyfchgr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.c1oappe.top/Article/details/gt2rqapybtv.html

JS:   e.message;  e.stack
来源：http://dali.zdqjudy.top/Article/details/gt2nxwrgkts.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hminiwqv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shuidangran.top/Article/details/gt2rqpkqmrq.html

Go:   err.Error()
来源：http://dali.kuanghao11.cn/Article/details/gt2cuqnkkue.html

Ruby: e.message;  e.backtrace
来源：http://dali.snrcjt.cn/Article/details/gt2npyrpxso.html

C#:   e.Message;  e.StackTrace
来源：http://dali.andypj.xyz/Article/details/gt2ynywitab.html

[H09] 带错误码的异常
来源：http://dali.yuanzhike.top/Article/details/gt2njqtyjqk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhiwuduotai.top/Article/details/gt2mnkellch.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mrcnjbgo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenzaomai.com/Article/details/gt2pwwoeldc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fengsongda.top/Article/details/gt2kzdpdwju.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mmstggjr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhongyouzk.top/Article/details/gt2txsaoncu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.9152youxi.cn/Article/details/gt2stxofwla.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.guowangkeji.top/Article/details/gt2oqikpakk.html

[H10] 资源自动释放
来源：http://dali.fengsongda.top/Article/details/gt2klbztrwq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shuidangran.top/Article/details/gt2qvonbrll.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.svipenyu.cn/Article/details/gt2stxleccc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gt2wixbgbqn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.kuanghao11.cn/Article/details/gt2ozqcvwec.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigufen.top/Article/details/gt2eorcectj.html

Go:   defer f.Close()
来源：http://dali.tian-w.cn/Article/details/gt2ejvqgqzo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jianghu66.top/Article/details/gt2mmxcqgrx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sivotkrr.html


<!-- 参考信息 -->