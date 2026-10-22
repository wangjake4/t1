代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2thaxywpi.html

C#:   File.Delete("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2cfbhxqzz.html

[F07] 创建目录（含多级）
来源：http://dali.wangdashe.top/Article/details/gt2xbznwmxf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.pengpengdd.cyou/Article/details/gt2feotxtsq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2spxcqjlk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuanzx.com/Article/details/gt2qbygevmo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gt2txelyqci.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yuanzhike.top/Article/details/gt2hpzajadn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.redwolf501.top/Article/details/gt2lvfnutyu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2seofddsr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgfzy.top/Article/details/gt2qhfpwicv.html

[F08] 遍历目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pjxjemhc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xinyue.icu/Article/details/gt2xddvsgjs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zdqjudy.top/Article/details/gt2moukmkoh.html

JS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gt2jenkukpv.html

TS:   fs.readdirSync("dir")
来源：http://dali.ybcxt.top/Article/details/gt2ynbsdcrn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aibaodan.cn/Article/details/gt2haqzzukp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bhpjalsy.html

Ruby: Dir.children("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lgtklobn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gt2rtpylqwv.html

[F09] 获取文件大小
来源：http://dali.vqdsnc.cn/Article/details/gt2qrgzvyfv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2qmxjgvyn.html

PHP:  filesize("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2fkuqbvuu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.iojbl.cn/Article/details/gt2kurhnlvi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gt2qbuvtxvr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gt2flgtodwb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cheryme.top/Article/details/gt2vdswydvi.html

Ruby: File.size("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2sfryhvsb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yonumen.top/Article/details/gt2dwixkjbn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258888.top/Article/details/gt2jjvfeogy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2utlzopcy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2olvoywpt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2tmibgnet.html

TS:   path.extname("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2hnubiaqq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shzxlz.cn/Article/details/gt2mwcqvqsu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2scedxqap.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2zrprrejv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ypymsqcb.html

[F11] 复制与移动文件
来源：http://dali.hywenlv.cn/Article/details/gt2rllytcno.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2eojmmqmi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mhygxwtd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gt2ygftcckz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gt2hcxrowkj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gt2kydyoqvr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guannengcc.top/Article/details/gt2qrpawpnl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2avoibsbg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daxiang520.top/Article/details/gt2gaxqphkp.html

[F12] CSV 读写
来源：http://dali.cheryme.top/Article/details/gt2kphypfgd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangdashe.top/Article/details/gt2qjskblvs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xinyue.icu/Article/details/gt2jfyfpwgh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhiwuduotai.top/Article/details/gt2ogpjdwby.html

TS:   // 同上
来源：http://dali.jinqigfzy.top/Article/details/gt2aybubmcu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gaohongyu789.top/Article/details/gt2ouhyvhki.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.snrcjt.cn/Article/details/gt2kixfjamr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cucudq.cn/Article/details/gt2wikljzte.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hnxiangtu.top/Article/details/gt2fuhpujms.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2oeoacnfh.html

G. 面向对象
来源：http://dali.yvedp.cn/Article/details/gt2smdtpjjc.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2sojdseao.html

[G01] 定义类
来源：http://dali.hnqzz.top/Article/details/gt2naafcigd.html

Py:   class User: pass
来源：http://dali.0kj1m.cn/Article/details/gt2pfszhzdp.html

PHP:  class User {}
来源：http://dali.fengsongda.top/Article/details/gt2ptxdokrj.html

JS:   class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xjxlppea.html

TS:   class User { name: string = ""; }
来源：http://dali.vqdsnc.cn/Article/details/gt2edtbybwq.html

Java: class User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2huxphque.html

Go:   type User struct { Name string }
来源：http://dali.xziqi.cn/Article/details/gt2belrkmte.html

Ruby: class User; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2efilhgco.html

C#:   class User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2rcvqvyom.html

[G02] 构造函数
来源：http://dali.tian-w.cn/Article/details/gt2bhahdcvw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hnqzz.top/Article/details/gt2qmiujkgc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.mhx1999.top/Article/details/gt2ydshkfnp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gt2xsfrbvtg.html

TS:   constructor(public name: string) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2iorbmvhm.html

Java: User(String name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gt2zroamblh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.bjfxy.top/Article/details/gt2qaxaaslx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jqgfzy.top/Article/details/gt2tjaenxeo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenlongwang.top/Article/details/gt2zzkjzgld.html

[G03] 实例属性
来源：http://dali.jiagoushi.top/Article/details/gt2mjtesbqh.html

Py:   self.name = "x"
来源：http://dali.birdmap.top/Article/details/gt2xjpgaxfl.html

PHP:  public string $name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gt2rthldhoh.html

JS:   this.name = "x";
来源：http://dali.birdmap.top/Article/details/gt2ibiffrno.html

TS:   name: string = "x";
来源：http://dali.yvedp.cn/Article/details/gt2hybtlwvu.html

Java: private String name;
来源：http://dali.cqqwz.cn/Article/details/gt2zvntyufv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xylfe.cn/Article/details/gt2ayjiumen.html

Ruby: @name = "x"
来源：http://dali.zhixingplan.top/Article/details/gt2kbdjefpr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tian-w.cn/Article/details/gt2madywleo.html

[G04] 定义方法
来源：http://dali.tian-w.cn/Article/details/gt2jokdngbu.html

Py:   def greet(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gt2vnfzisct.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gt2czspkcsr.html

JS:   greet() { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gt2fdvqgljg.html

TS:   greet(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gt2mtficadw.html

Java: String greet() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2wgkncrbe.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gt2bymopbbm.html

Ruby: def greet; @name; end
来源：http://dali.zhixingplan.top/Article/details/gt2htawyxgu.html

C#:   public string Greet() => Name;
来源：http://dali.fengsongda.top/Article/details/gt2flzgskja.html

[G05] 继承
来源：http://dali.jlsjyb.cn/Article/details/gt2qeqgxmel.html

Py:   class Admin(User): pass
来源：http://dali.svipenyu.cn/Article/details/gt2xscsgvje.html

PHP:  class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2xtvrccpa.html

JS:   class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gt2umqgkaah.html

TS:   class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gt2xhivlyrm.html

Java: class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gt2vyumclvp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guowangkeji.top/Article/details/gt2heaicjfm.html

Ruby: class Admin < User; end
来源：http://dali.snrcjt.cn/Article/details/gt2cishsnpo.html

C#:   class Admin : User {}
来源：http://dali.hnqzz.top/Article/details/gt2penxgqsh.html

[G06] 重写方法
来源：http://dali.aibaodan.cn/Article/details/gt2pfrdemnz.html

Py:   def greet(self): return "admin"
来源：http://dali.jqgfzy.top/Article/details/gt2dxtbxrpw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gt2dchatlge.html

JS:   greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gt2pqtntybh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gt2beenutcj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2uplktmvt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.kuanghao11.cn/Article/details/gt2mxltuqdt.html

Ruby: def greet; "admin"; end
来源：http://dali.birdmap.top/Article/details/gt2wsxazthl.html

C#:   public override string Greet() => "admin";
来源：http://dali.mhx1999.top/Article/details/gt2dtqbuovu.html

[G07] 调用父类方法
来源：http://dali.shangyingyoupin.top/Article/details/gt2xzdqgdze.html

Py:   super().greet()
来源：http://dali.aibaodan.cn/Article/details/gt2nvqlfdye.html

PHP:  parent::greet();
来源：http://dali.xuetiantiany.cn/Article/details/gt2egcqnbss.html

JS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gt2zlbtewhj.html

TS:   super.greet();
来源：http://dali.sweek.top/Article/details/gt2ksmnapdc.html

Java: super.greet();
来源：http://dali.jianghu66.top/Article/details/gt2cnwopxmj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.smart0.xyz/Article/details/gt2sjlawqyf.html

Ruby: super
来源：http://dali.yj20258888.top/Article/details/gt2tfweibic.html

C#:   base.Greet();
来源：http://dali.yonumen.top/Article/details/gt2ycopsbwp.html

[G08] 静态方法与属性
来源：http://dali.guannengcc.top/Article/details/gt2xhtrkybx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yongpay.top/Article/details/gt2kmxysole.html

PHP:  public static function f() {}
来源：http://dali.sufxvd.cn/Article/details/gt2lokczdjk.html

JS:   static f() {}
来源：http://dali.snrcjt.cn/Article/details/gt2zifeysed.html

TS:   static f(): void {}
来源：http://dali.smart0.xyz/Article/details/gt2hshmkibb.html

Java: static void f() {}
来源：http://dali.yangfankeji.com/Article/details/gt2hvjbkxen.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cheryme.top/Article/details/gt2uqyqxzts.html

Ruby: def self.f; end
来源：http://dali.sweek.top/Article/details/gt2dtpasqud.html

C#:   public static void F() {}
来源：http://dali.nwbrower.top/Article/details/gt2multxjla.html

[G09] 接口 / 抽象类
来源：http://dali.pengpengdd.cyou/Article/details/gt2louhytws.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258.top/Article/details/gt2nbqihngh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigfzy.top/Article/details/gt2vhsusjqr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hongshengwenyu.top/Article/details/gt2mwgsjunh.html

TS:   interface Shape { area(): number; }
来源：http://dali.ybcxt.top/Article/details/gt2cjvrxuri.html

Java: interface Shape { double area(); }
来源：http://dali.cucudq.cn/Article/details/gt2kepukhgq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jqgufenzy.top/Article/details/gt2wftejset.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.meibo888.top/Article/details/gt2svhypadq.html

C#:   interface IShape { double Area(); }
来源：http://dali.daxiang520.top/Article/details/gt2eignvhoh.html

[G10] 访问控制
来源：http://dali.yvedp.cn/Article/details/gt2emgdypkf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yanxiufei.cn/Article/details/gt2ukdsckzm.html

PHP:  public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jzprtnfe.html

JS:   #private 字段；其余公开
来源：http://dali.pycfn.com/Article/details/gt2rtqrmqpy.html

TS:   public / protected / private
来源：http://dali.cheryme.top/Article/details/gt2aoseuswm.html

Java: public / protected / private / 默认包级
来源：http://dali.quarkkingdee.top/Article/details/gt2tiqbfnqh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yvedp.cn/Article/details/gt2hdragwsf.html

Ruby: public / protected / private
来源：http://dali.sysykeji.top/Article/details/gt2jnazykms.html

C#:   public / protected / private / internal
来源：http://dali.hywenlv.cn/Article/details/gt2ozzefutg.html

[G11] getter / setter
来源：http://dali.hysaishi.cn/Article/details/gt2gkfxhgpc.html

Py:   @property 与 @x.setter
来源：http://dali.ivvv.top/Article/details/gt2umbgdgri.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2egsjtzhl.html

JS:   get name() { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gt2ekzddalu.html

TS:   get name(): string { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2muotlrsp.html

Java: public String getName() { return name; }
来源：http://dali.cheryme.top/Article/details/gt2gflkzvof.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gt2xurjumcd.html

Ruby: attr_accessor :name
来源：http://dali.jiagoushi.top/Article/details/gt2kygkteap.html

C#:   public string Name { get; set; }
来源：http://dali.kuanghao11.cn/Article/details/gt2dogvtjkt.html

[G12] 对象转字符串
来源：http://dali.c1oappe.top/Article/details/gt2psonjdhc.html

Py:   def __str__(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gt2kacivtao.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwhabum.html

JS:   toString() { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2gkrxcxsw.html

TS:   toString(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gt2efambkcz.html

Java: @Override public String toString() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ozgqlnzo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gt2kfiogldx.html

Ruby: def to_s; @name; end
来源：http://dali.xziqi.cn/Article/details/gt2uvpdafjg.html

C#:   public override string ToString() => Name;
来源：http://dali.yongpay.top/Article/details/gt2zawlpxkn.html

[G13] 判断对象类型
来源：http://dali.yueranfly.top/Article/details/gt2qsfngcki.html

Py:   isinstance(u, User)
来源：http://dali.chenlongwang.top/Article/details/gt2wfoieksw.html

PHP:  $u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jhdlxsix.html

JS:   u instanceof User
来源：http://dali.daxiang520.top/Article/details/gt2uimwofnx.html

TS:   u instanceof User
来源：http://dali.cheryme.top/Article/details/gt2krtpbdqp.html

Java: u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gt2dnwvkemg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhixingplan.top/Article/details/gt2fnjekabx.html

Ruby: u.is_a?(User)
来源：http://dali.nwbrower.top/Article/details/gt2owcmscqn.html

C#:   u is User
来源：http://dali.cqqwz.cn/Article/details/gt2miefcbso.html

[G14] 数据类 / record
来源：http://dali.xziqi.cn/Article/details/gt2fsdebygw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.feifeiyinyue.top/Article/details/gt2eneqookw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yongpay.top/Article/details/gt2gcjhhwuw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gzhubu.top/Article/details/gt2kdgvmpfn.html

TS:   type User = { name: string; age: number };
来源：http://dali.ppjwa.cn/Article/details/gt2kjxvpgcb.html

Java: record User(String name, int age) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rzmoxpzk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tianlin.xyz/Article/details/gt2vjsmmhvm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258.top/Article/details/gt2udalhdmj.html

C#:   record User(string Name, int Age);
来源：http://dali.cdnleiting.top/Article/details/gt2ksvmthiy.html

[G15] 枚举
来源：http://dali.xuetiantiany.cn/Article/details/gt2qvisfhrw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhoulong.xyz/Article/details/gt2bksbeeyd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gogol.net.cn/Article/details/gt2quilntrh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuxming.cn/Article/details/gt2hdycnjen.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hywenlv.cn/Article/details/gt2vfmnymap.html

Java: enum Color { RED, GREEN }
来源：http://dali.pycfn.com/Article/details/gt2spluygei.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.havefunace.top/Article/details/gt2zjwwpqvz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ydzc1.top/Article/details/gt2sasneqrz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2sdoqzpqz.html

[G16] 对象转数组 / 字典
来源：http://dali.yj202588.top/Article/details/gt2ukqkpgzl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhoulong.xyz/Article/details/gt2lsqincct.html

PHP:  get_object_vars($obj);
来源：http://dali.shuidangran.top/Article/details/gt2owrncjrx.html

JS:   Object.entries(obj)
来源：http://dali.nwbrower.top/Article/details/gt2rdpqlojv.html

TS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gt2gchlaeih.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sufxvd.cn/Article/details/gt2sdqayxcs.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tian-w.cn/Article/details/gt2qolfdcgj.html

Ruby: obj.instance_variables
来源：http://dali.ydzc1.top/Article/details/gt2ouoammqx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tian-w.cn/Article/details/gt2lnkhiutw.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2yrmgbwll.html

H. 异常与错误处理
来源：http://dali.xziqi.cn/Article/details/gt2lkqrwnff.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2xigxzfgp.html

[H01] try / catch 基础
来源：http://dali.cheryme.top/Article/details/gt2mxgfaisg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xylfe.cn/Article/details/gt2fzqxvdbs.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2nxrkivcr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gt2qudjxnda.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gt2laxhswnz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhongyouzk.top/Article/details/gt2yfgqysiu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuxming.cn/Article/details/gt2nbdpemdv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangdashe.top/Article/details/gt2aqftisho.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.svipenyu.cn/Article/details/gt2compwuvc.html

[H02] finally / ensure 收尾
来源：http://dali.sufxvd.cn/Article/details/gt2cwtccota.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yonumen.top/Article/details/gt2pssjtoep.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gt2aepevcey.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gt2kksolpah.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gt2ufftmbxd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gt2uxylaebx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shuidangran.top/Article/details/gt2skwwozsu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yuxming.cn/Article/details/gt2xsrnhqyh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2osnetfzj.html

[H03] 主动抛出异常
来源：http://dali.316326.xyz/Article/details/gt2mnvpieph.html

Py:   raise ValueError("错误信息")
来源：http://dali.cucudq.cn/Article/details/gt2klouresv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gt2zapcjecy.html

JS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gt2nxjfplws.html

TS:   throw new Error("错误信息");
来源：http://dali.aizwys.cn/Article/details/gt2morabhqm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gt2nmwgqnct.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jlsjyb.cn/Article/details/gt2xbhlhbep.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.pycfn.com/Article/details/gt2dcyzjbrr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gt2lbsrkyfp.html

[H04] 自定义异常类型
来源：http://dali.bjfxy.top/Article/details/gt2aoacaeta.html

Py:   class MyError(Exception): pass
来源：http://dali.guannengcc.top/Article/details/gt2zoffnblf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhoulong.xyz/Article/details/gt2zvcpwoze.html

JS:   class MyError extends Error {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jbpsbdmv.html

TS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gt2rhxzbhwg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shuidangran.top/Article/details/gt2emcnbsor.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.quarkkingdee.top/Article/details/gt2qgmtheqv.html

Ruby: class MyError < StandardError; end
来源：http://dali.birdmap.top/Article/details/gt2mesomhvd.html

C#:   class MyException : Exception {}
来源：http://dali.tian-w.cn/Article/details/gt2fgbnwkcs.html

[H05] 捕获特定类型
来源：http://dali.zdqjudy.top/Article/details/gt2cptsygre.html

Py:   except ValueError as e:
来源：http://dali.zdqjudy.top/Article/details/gt2uztuxhiv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.9152youxi.cn/Article/details/gt2ypjndpdh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gt2vppxkitx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gt2leurboci.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lrkxtmcf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhixingplan.top/Article/details/gt2abdvqjct.html

Ruby: rescue ArgumentError => e
来源：http://dali.hywenlv.cn/Article/details/gt2ttzuvyiu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2okduxkks.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jiagoushi.top/Article/details/gt2tcgnvngl.html

Py:   value = d.get("k") or default
来源：http://dali.yonumen.top/Article/details/gt2djuuwxjx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gt2szpzwzbu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gt2jpbdaolq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hitegudx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jyoumei.cn/Article/details/gt2fybbzote.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nwbrower.top/Article/details/gt2vluoymoz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.daxiang520.top/Article/details/gt2cfyztnjy.html

C#:   obj?.A?.B ?? default
来源：http://dali.yanxiufei.cn/Article/details/gt2jhbajznu.html

[H07] 断言
来源：http://dali.hongshengwenyu.top/Article/details/gt2dlgnguch.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhengqikj.top/Article/details/gt2oebbzdza.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lczkqlcr.html

JS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gt2zzhcczkr.html

TS:   console.assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gt2uapjqttu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gotoacloud.top/Article/details/gt2mzjdjiqc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.0kj1m.cn/Article/details/gt2nkvewpbg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guannengcc.top/Article/details/gt2olckaudv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gt2wmmdhyee.html

[H08] 获取错误信息与堆栈
来源：http://dali.sysykeji.top/Article/details/gt2kxeaxzns.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shangyingyoupin.top/Article/details/gt2kcfbnnzx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ydzc1.top/Article/details/gt2hbfxcegi.html

JS:   e.message;  e.stack
来源：http://dali.0kj1m.cn/Article/details/gt2etlzaqum.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.guowangkeji.top/Article/details/gt2myzaokqb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj20258.top/Article/details/gt2illnyycd.html

Go:   err.Error()
来源：http://dali.yj20258.top/Article/details/gt2rnblseqf.html

Ruby: e.message;  e.backtrace
来源：http://dali.bjfxy.top/Article/details/gt2tnazgmsf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zdqjudy.top/Article/details/gt2pjgwemzd.html

[H09] 带错误码的异常
来源：http://dali.guowangkeji.top/Article/details/gt2kejzdxdp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jeigyedq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vnofilfm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nanxuanxn.top/Article/details/gt2twyhzqjo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ejnwmmnp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gbacwtrq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ivvv.top/Article/details/gt2yiamqejb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yueranfly.top/Article/details/gt2nxrnholh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sweek.top/Article/details/gt2udvqxtin.html

[H10] 资源自动释放
来源：http://dali.aibaodan.cn/Article/details/gt2rrielkli.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfkxpzb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhoulong.xyz/Article/details/gt2cqektrvo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gt2sojvoqcu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gt2zbompyok.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guowangkeji.top/Article/details/gt2dyjoyshh.html

Go:   defer f.Close()
来源：http://dali.hfpthk.cn/Article/details/gt2clcpjoql.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zkbjsfib.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2quluhamb.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2ujaulrqh.html

I. 正则表达式
来源：http://dali.hysaishi.cn/Article/details/gt2unosrhzh.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2repbrtit.html

[I01] 判断是否匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2xrjmescm.html


<!-- 参考信息 -->