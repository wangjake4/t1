代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2ggvqlcyu.html

C#:   File.Delete("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gurbhgrk.html

[F07] 创建目录（含多级）
来源：http://dali.hywenlv.cn/Article/details/gt2jdsxiykp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.snrcjt.cn/Article/details/gt2jdfkvjny.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuetiantiany.cn/Article/details/gt2tcjxifir.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cashguo.top/Article/details/gt2isvwncma.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gt2kybkfmrt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ybcxt.top/Article/details/gt2tzltkndo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xylfe.cn/Article/details/gt2myupgwkn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gotoacloud.top/Article/details/gt2zccpavbr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gotoacloud.top/Article/details/gt2nvepvonz.html

[F08] 遍历目录
来源：http://dali.fengsongda.top/Article/details/gt2zithhsty.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yongpay.top/Article/details/gt2scszftfk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tanke756.top/Article/details/gt2phzhhqdz.html

JS:   fs.readdirSync("dir")
来源：http://dali.kuanghao11.cn/Article/details/gt2mgnyxqiu.html

TS:   fs.readdirSync("dir")
来源：http://dali.ivvv.top/Article/details/gt2xvsaxuoo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sufxvd.cn/Article/details/gt2acopseez.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.c1oappe.top/Article/details/gt2vrhhcavo.html

Ruby: Dir.children("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ixaxnsld.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ewsclkyl.html

[F09] 获取文件大小
来源：http://dali.hammf.cn/Article/details/gt2rgumuubr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2micofncf.html

PHP:  filesize("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2rgcgdwfg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xuetiantiany.cn/Article/details/gt2gplmthch.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pnkbzbsn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gt2jgcknahz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.c1oappe.top/Article/details/gt2ewrjmmey.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2lvxmlkbb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zycfv.cn/Article/details/gt2kquqhxtk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhixingplan.top/Article/details/gt2xxfdbkhf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2eavbhaml.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.316326.xyz/Article/details/gt2oicoeexr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2unxoknhm.html

TS:   path.extname("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2glpzsjdx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yuanzhike.top/Article/details/gt2uzjhzgvm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gt2ratenmyg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2jmgiqsox.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2oedlfcyq.html

[F11] 复制与移动文件
来源：http://dali.vqdsnc.cn/Article/details/gt2cdkcqebp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gt2tomdthxf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2kjbwrgal.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2optlitdz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gt2boslkwfa.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gt2ztjnhblc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhixingplan.top/Article/details/gt2pjcsnldw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2frulvosb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yanxiufei.cn/Article/details/gt2axnxtcly.html

[F12] CSV 读写
来源：http://dali.ydzc1.top/Article/details/gt2mrataefc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jianghu66.top/Article/details/gt2ygmlbasm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.fengsongda.top/Article/details/gt2aptfvuhe.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xinyue.icu/Article/details/gt2wwelrkxy.html

TS:   // 同上
来源：http://dali.dashuyun.cn/Article/details/gt2gdkdbpgn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhoulong.xyz/Article/details/gt2lqrjbxse.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.daxiang520.top/Article/details/gt2apmuqcdu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.bjfxy.top/Article/details/gt2mjpofmov.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.fzhhl.top/Article/details/gt2hqcsjikf.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2lguuvuub.html

G. 面向对象
来源：http://dali.gogol.net.cn/Article/details/gt2reatunkl.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2hqsldbsc.html

[G01] 定义类
来源：http://dali.xuanzx.com/Article/details/gt2mtjfpahq.html

Py:   class User: pass
来源：http://dali.sysykeji.top/Article/details/gt2rdkdbqrq.html

PHP:  class User {}
来源：http://dali.hysaishi.cn/Article/details/gt2qlwclkxw.html

JS:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gt2yxcarumx.html

TS:   class User { name: string = ""; }
来源：http://dali.shuidangran.top/Article/details/gt2fnypjmje.html

Java: class User {}
来源：http://dali.hysaishi.cn/Article/details/gt2zkgnebrw.html

Go:   type User struct { Name string }
来源：http://dali.bjfxy.top/Article/details/gt2zcczocto.html

Ruby: class User; end
来源：http://dali.zdqjudy.top/Article/details/gt2zotzkemm.html

C#:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gt2gzidodjt.html

[G02] 构造函数
来源：http://dali.daria6918.cn/Article/details/gt2lehhkltt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hysaishi.cn/Article/details/gt2cpmjeaip.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cdnleiting.top/Article/details/gt2lbcixgde.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2aacpwzsp.html

TS:   constructor(public name: string) {}
来源：http://dali.dianchejie.cn/Article/details/gt2nhbpkzae.html

Java: User(String name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gt2emisbrrg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.316326.xyz/Article/details/gt2jwglomxl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuxming.cn/Article/details/gt2hdnnbkmg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.9152youxi.cn/Article/details/gt2voepxupv.html

[G03] 实例属性
来源：http://dali.vqdsnc.cn/Article/details/gt2azuisvwx.html

Py:   self.name = "x"
来源：http://dali.ehwqpu.com/Article/details/gt2nxhzumys.html

PHP:  public string $name = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2frlsuuir.html

JS:   this.name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gt2hrpjvkix.html

TS:   name: string = "x";
来源：http://dali.gotoacloud.top/Article/details/gt2fznlviqf.html

Java: private String name;
来源：http://dali.dianchejie.cn/Article/details/gt2mupgwdbe.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigufen.top/Article/details/gt2kbucpbvf.html

Ruby: @name = "x"
来源：http://dali.yvedp.cn/Article/details/gt2kfpmxxso.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.meibo888.top/Article/details/gt2grkldodb.html

[G04] 定义方法
来源：http://dali.hongshengwenyu.top/Article/details/gt2pcfdnczf.html

Py:   def greet(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gt2csrbcmwn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2asvhwdnd.html

JS:   greet() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gt2pljlslnp.html

TS:   greet(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gt2ryamrvoa.html

Java: String greet() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gt2xlhwixst.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shuidangran.top/Article/details/gt2faptogwz.html

Ruby: def greet; @name; end
来源：http://dali.haohaochexian.top/Article/details/gt2uuuejpgx.html

C#:   public string Greet() => Name;
来源：http://dali.xinyue.icu/Article/details/gt2ivzrceik.html

[G05] 继承
来源：http://dali.jqgufenzy.top/Article/details/gt2pefqnnba.html

Py:   class Admin(User): pass
来源：http://dali.shzxlz.cn/Article/details/gt2vtwxyfdz.html

PHP:  class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gt2iirpvxkl.html

JS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gt2fbsjrkke.html

TS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gt2qzjlqmkz.html

Java: class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2iwoyhabs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jyoumei.cn/Article/details/gt2hhprvram.html

Ruby: class Admin < User; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2uvxlttuh.html

C#:   class Admin : User {}
来源：http://dali.9152youxi.cn/Article/details/gt2jhbffnwi.html

[G06] 重写方法
来源：http://dali.hfpthk.cn/Article/details/gt2ibhmixgl.html

Py:   def greet(self): return "admin"
来源：http://dali.pycfn.com/Article/details/gt2rvtbgnve.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gt2xfiqhfzm.html

JS:   greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2suaibzys.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gt2ficwdcjf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gt2bpohcckt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.andypj.xyz/Article/details/gt2zlnjbgbs.html

Ruby: def greet; "admin"; end
来源：http://dali.yonumen.top/Article/details/gt2qumekllw.html

C#:   public override string Greet() => "admin";
来源：http://dali.daxiang520.top/Article/details/gt2afcwrqfo.html

[G07] 调用父类方法
来源：http://dali.mhx1999.top/Article/details/gt2grkxeyuu.html

Py:   super().greet()
来源：http://dali.yangfankeji.com/Article/details/gt2iczriamp.html

PHP:  parent::greet();
来源：http://dali.shzxlz.cn/Article/details/gt2aohtzyyj.html

JS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gt2dqqabnzn.html

TS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gt2pfimcdvg.html

Java: super.greet();
来源：http://dali.shzxlz.cn/Article/details/gt2yzonxuvh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.fengsongda.top/Article/details/gt2zoopduhf.html

Ruby: super
来源：http://dali.cucudq.cn/Article/details/gt2moyrerzr.html

C#:   base.Greet();
来源：http://dali.jqgfzy.top/Article/details/gt2qvdejpsy.html

[G08] 静态方法与属性
来源：http://dali.daxiang520.top/Article/details/gt2mredmkkw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ivvv.top/Article/details/gt2ezwpkqva.html

PHP:  public static function f() {}
来源：http://dali.smart0.xyz/Article/details/gt2ivadgzxy.html

JS:   static f() {}
来源：http://dali.pycfn.com/Article/details/gt2xhqrjljz.html

TS:   static f(): void {}
来源：http://dali.hammf.cn/Article/details/gt2tssqhvqe.html

Java: static void f() {}
来源：http://dali.jyoumei.cn/Article/details/gt2sbfajbqx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qnamvkzi.html

Ruby: def self.f; end
来源：http://dali.fengsongda.top/Article/details/gt2diheibhg.html

C#:   public static void F() {}
来源：http://dali.jqgfzy.top/Article/details/gt2pqtpyogd.html

[G09] 接口 / 抽象类
来源：http://dali.jqgufenzy.top/Article/details/gt2euavembk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hywenlv.cn/Article/details/gt2lpgqwmtn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojonxnzn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.wangshuangyany.cn/Article/details/gt2ivbvfuyp.html

TS:   interface Shape { area(): number; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bououlkn.html

Java: interface Shape { double area(); }
来源：http://dali.gotoacloud.top/Article/details/gt2ioxztuep.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hysaishi.cn/Article/details/gt2zgevzbpm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yueranfly.top/Article/details/gt2gnlkztmw.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenzaomai.com/Article/details/gt2kdhdmsrx.html

[G10] 访问控制
来源：http://dali.guannengcc.top/Article/details/gt2yycqspic.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shzxlz.cn/Article/details/gt2ghggtkqo.html

PHP:  public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gt2wleliyqq.html

JS:   #private 字段；其余公开
来源：http://dali.hammf.cn/Article/details/gt2hetstbis.html

TS:   public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gt2kntycaid.html

Java: public / protected / private / 默认包级
来源：http://dali.hywenlv.cn/Article/details/gt2uzgnjwpf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yueranfly.top/Article/details/gt2htqbcguy.html

Ruby: public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gt2mrgvwbwe.html

C#:   public / protected / private / internal
来源：http://dali.ivvv.top/Article/details/gt2zxpxmbml.html

[G11] getter / setter
来源：http://dali.smart0.xyz/Article/details/gt2xnpvyndf.html

Py:   @property 与 @x.setter
来源：http://dali.jinqigufen.top/Article/details/gt2szvjggjz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gt2zzcujquz.html

JS:   get name() { return this._name; }
来源：http://dali.yongpay.top/Article/details/gt2vnnbxayt.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj20258.top/Article/details/gt2kowrfcew.html

Java: public String getName() { return name; }
来源：http://dali.yvedp.cn/Article/details/gt2efkurddm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gt2pxuetazl.html

Ruby: attr_accessor :name
来源：http://dali.daxiang520.top/Article/details/gt2fiutffut.html

C#:   public string Name { get; set; }
来源：http://dali.ybcxt.top/Article/details/gt2ctuutsan.html

[G12] 对象转字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2cdkphshb.html

Py:   def __str__(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gt2twpxbell.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gt2iidhsolz.html

JS:   toString() { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gt2pavnjyen.html

TS:   toString(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gt2yrbhpuur.html

Java: @Override public String toString() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dtdezdju.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gt2rcqoxexi.html

Ruby: def to_s; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gt2hihtmlpz.html

C#:   public override string ToString() => Name;
来源：http://dali.xziqi.cn/Article/details/gt2hxhpzjks.html

[G13] 判断对象类型
来源：http://dali.vqdsnc.cn/Article/details/gt2oxliuqrq.html

Py:   isinstance(u, User)
来源：http://dali.aibaodan.cn/Article/details/gt2sejdkhpe.html

PHP:  $u instanceof User
来源：http://dali.ybcxt.top/Article/details/gt2wdaaydcw.html

JS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gt2qeoecsnl.html

TS:   u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gt2tcelogwu.html

Java: u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2xozajurz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.smart0.xyz/Article/details/gt2jnkoeqjq.html

Ruby: u.is_a?(User)
来源：http://dali.hysaishi.cn/Article/details/gt2vzvdvxuk.html

C#:   u is User
来源：http://dali.cheryme.top/Article/details/gt2gzaskiaf.html

[G14] 数据类 / record
来源：http://dali.tian-w.cn/Article/details/gt2wcovzcxi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.havefunace.top/Article/details/gt2whlafxis.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yuanzhike.top/Article/details/gt2ctszyfao.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yvedp.cn/Article/details/gt2ocxcpwpn.html

TS:   type User = { name: string; age: number };
来源：http://dali.daxiang520.top/Article/details/gt2rytyltzt.html

Java: record User(String name, int age) {}
来源：http://dali.dianchejie.cn/Article/details/gt2jpuvwauu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vofbgevv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cashguo.top/Article/details/gt2sqqxgzxr.html

C#:   record User(string Name, int Age);
来源：http://dali.shzxlz.cn/Article/details/gt2tesnmzop.html

[G15] 枚举
来源：http://dali.tianlin.xyz/Article/details/gt2sbycasfs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yuxming.cn/Article/details/gt2rxqibfgz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.c1oappe.top/Article/details/gt2dkjsfpuv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.andypj.xyz/Article/details/gt2kygyfdhx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hfpthk.cn/Article/details/gt2whrwgjov.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangshuangyany.cn/Article/details/gt2cyepdsyg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vwahbbwc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2trqmdsfj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.c1oappe.top/Article/details/gt2ziskvfir.html

[G16] 对象转数组 / 字典
来源：http://dali.shangyingyoupin.top/Article/details/gt2qjedkolj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ybcxt.top/Article/details/gt2craehleh.html

PHP:  get_object_vars($obj);
来源：http://dali.gzhubu.top/Article/details/gt2jvkwqfhv.html

JS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gt2linvguwf.html

TS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gt2kmbmgmcg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gzhubu.top/Article/details/gt2calcphhr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.iojbl.cn/Article/details/gt2gkhotcxj.html

Ruby: obj.instance_variables
来源：http://dali.zycfv.cn/Article/details/gt2nzlgromg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gt2jurtsdvj.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2jsyylfsi.html

H. 异常与错误处理
来源：http://dali.jlsjyb.cn/Article/details/gt2zymstvyc.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2akmsijly.html

[H01] try / catch 基础
来源：http://dali.svipenyu.cn/Article/details/gt2aexwbcdj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhengqikj.top/Article/details/gt2gbyalwcv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cucudq.cn/Article/details/gt2oiwnihjg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gt2jfqppjwh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gt2azjjujdk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2avvhpoil.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xylfe.cn/Article/details/gt2tluubeiy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinqigfzy.top/Article/details/gt2djijqbrk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cucudq.cn/Article/details/gt2etuyjtcl.html

[H02] finally / ensure 收尾
来源：http://dali.cheryme.top/Article/details/gt2rhopeezw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sysykeji.top/Article/details/gt2zqdjsuqj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2czykxfgt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gt2hhdkpjny.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2pxfwtzzg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gt2ytelybkd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daxiang520.top/Article/details/gt2fuznyyyd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guowangkeji.top/Article/details/gt2xnobvaiw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gt2oqkekygy.html

[H03] 主动抛出异常
来源：http://dali.haohaochexian.top/Article/details/gt2xocfdmjp.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kxmxvbsq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gt2vyivgesd.html

JS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2fivcjiqq.html

TS:   throw new Error("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rsaaqrsj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gt2zjxflkij.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ydzc1.top/Article/details/gt2vfqeuiyp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shzxlz.cn/Article/details/gt2djbpuviy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gt2cwxuidii.html

[H04] 自定义异常类型
来源：http://dali.pycfn.com/Article/details/gt2qdzykqtt.html

Py:   class MyError(Exception): pass
来源：http://dali.cucudq.cn/Article/details/gt2czrwzhqy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gt2uvztkeyj.html

JS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2rflufnwp.html

TS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gt2aifvqvzf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2fegjvybs.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.quarkkingdee.top/Article/details/gt2lfnslxvx.html

Ruby: class MyError < StandardError; end
来源：http://dali.daxiang520.top/Article/details/gt2omixluir.html

C#:   class MyException : Exception {}
来源：http://dali.yuxming.cn/Article/details/gt2pksndenn.html

[H05] 捕获特定类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gjdzunad.html

Py:   except ValueError as e:
来源：http://dali.316326.xyz/Article/details/gt2cotspcnw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daria6918.cn/Article/details/gt2dclmcelu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2szrwyxtp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gt2grbptlyn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aizwys.cn/Article/details/gt2srzvilvg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj202588.top/Article/details/gt2zmaomeht.html

Ruby: rescue ArgumentError => e
来源：http://dali.9152youxi.cn/Article/details/gt2viribroc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xuanzx.com/Article/details/gt2czjzxbtd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gaohongyu789.top/Article/details/gt2npczircz.html

Py:   value = d.get("k") or default
来源：http://dali.hywenlv.cn/Article/details/gt2pxqottgp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cashguo.top/Article/details/gt2ohhllboo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gt2mqkkivru.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gt2gwmwbbce.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wdntpnhd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.andypj.xyz/Article/details/gt2bomnlrjg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.aibaodan.cn/Article/details/gt2mxmeqagf.html

C#:   obj?.A?.B ?? default
来源：http://dali.svipenyu.cn/Article/details/gt2sdvebtcs.html

[H07] 断言
来源：http://dali.tanke756.top/Article/details/gt2pzfsqfzx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenjidiqi.icu/Article/details/gt2izfgveef.html

PHP:  assert($x > 0);
来源：http://dali.hfpthk.cn/Article/details/gt2olfbzoiy.html

JS:   console.assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2otboglrx.html

TS:   console.assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jhfzyobk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sweek.top/Article/details/gt2loarqsuq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258888.top/Article/details/gt2labppypl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigfzy.top/Article/details/gt2faajjubn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gt2udsagkzn.html

[H08] 获取错误信息与堆栈
来源：http://dali.cqqwz.cn/Article/details/gt2vzcmsbbz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hfpthk.cn/Article/details/gt2pxaamzum.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gotoacloud.top/Article/details/gt2igaolqla.html

JS:   e.message;  e.stack
来源：http://dali.nanxinkj.top/Article/details/gt2hhjpoxvy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.daxiang520.top/Article/details/gt2ocipjuuc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daria6918.cn/Article/details/gt2kqdjulvl.html

Go:   err.Error()
来源：http://dali.yangfankeji.com/Article/details/gt2yaaffdot.html

Ruby: e.message;  e.backtrace
来源：http://dali.bjfxy.top/Article/details/gt2tjnuzjcw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenlongwang.top/Article/details/gt2bubjgsga.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uopqqdcs.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zdqjudy.top/Article/details/gt2zmaizedy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jqgufenzy.top/Article/details/gt2hkthizth.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.guowangkeji.top/Article/details/gt2fgawpwoq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ijobtigs.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhongyouzk.top/Article/details/gt2bhhisevx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.pycfn.com/Article/details/gt2kheitvqz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gogol.net.cn/Article/details/gt2bqvooazk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gzhubu.top/Article/details/gt2tilxhtfd.html

[H10] 资源自动释放
来源：http://dali.sxryk.cn/Article/details/gt2jxvakuff.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tanke756.top/Article/details/gt2hkukciql.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.quarkkingdee.top/Article/details/gt2closldrs.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gt2bbgmxzav.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daxiang520.top/Article/details/gt2bigistit.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhiwuduotai.top/Article/details/gt2yfcckypq.html

Go:   defer f.Close()
来源：http://dali.jqgfzy.top/Article/details/gt2meruuknn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenjidiqi.icu/Article/details/gt2xhnzgplt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2dxnhlceh.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2fyvxyyxr.html

I. 正则表达式
来源：http://dali.fzhhl.top/Article/details/gt2qhmnkktq.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2zpxbiiik.html

[I01] 判断是否匹配
来源：http://dali.hnxiangtu.top/Article/details/gt2httfepvp.html


<!-- 参考信息 -->