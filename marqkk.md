代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yuanzhike.top/Article/details/gtukhtbueq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gogol.net.cn/Article/details/gtbdxvzquz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gtfzopzfub.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbdibxrm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daria6918.cn/Article/details/gtrhkmirad.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.haohaochexian.top/Article/details/gtlnhkzgti.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuanzx.com/Article/details/gtvtrsnknn.html

[F08] 遍历目录
来源：http://dali.sysykeji.top/Article/details/gtixbclmoh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgfzy.top/Article/details/gtxpymerdo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.dianchejie.cn/Article/details/gtszalivrg.html

JS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gtoesbterv.html

TS:   fs.readdirSync("dir")
来源：http://dali.daxiang520.top/Article/details/gtysnznzlz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.svipenyu.cn/Article/details/gtkcpyixbg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.svipenyu.cn/Article/details/gtarmdlcqw.html

Ruby: Dir.children("dir")
来源：http://dali.xziqi.cn/Article/details/gtqsxndcwz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtbzxnpold.html

[F09] 获取文件大小
来源：http://dali.yongpay.top/Article/details/gtqfrnkczb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gteofvjoxo.html

PHP:  filesize("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtamxlnfow.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yvedp.cn/Article/details/gtbkusmwmj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.pycfn.com/Article/details/gtluioaaln.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxmmvjspf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.aizwys.cn/Article/details/gtjpigftgp.html

Ruby: File.size("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtkmhaplss.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuetiantiany.cn/Article/details/gtohonxuci.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuanzx.com/Article/details/gtwwgrrchk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtukdvzzxg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtjmtbwfex.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtnomecoxy.html

TS:   path.extname("a.txt")
来源：http://dali.ivvv.top/Article/details/gtfnqmncxy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xuetiantiany.cn/Article/details/gtoolaazok.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtzjijkqvp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtufwnwffv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtsvyfgqyv.html

[F11] 复制与移动文件
来源：http://dali.xuetiantiany.cn/Article/details/gtikkhuczu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtcpudtjjq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yanxiufei.cn/Article/details/gteczcksna.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gtfrezzniv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtynnzvget.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.daria6918.cn/Article/details/gtpxwxbkqw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cdnleiting.top/Article/details/gtqcxkycfg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtfemkbxkn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258.top/Article/details/gtbasrfics.html

[F12] CSV 读写
来源：http://dali.sufxvd.cn/Article/details/gtzwmfnbem.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gtvenczgvm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.c1oappe.top/Article/details/gtvrleomzc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.wangdashe.top/Article/details/gtutfifrtl.html

TS:   // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gtasqliayv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwhixldu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sweek.top/Article/details/gtdhgrznio.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hnxiangtu.top/Article/details/gthgfqztcp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hammf.cn/Article/details/gtqfxrmjsq.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtzgpahoox.html

G. 面向对象
来源：http://dali.nanxuanxn.top/Article/details/gtiexowjxx.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtyezguxsi.html

[G01] 定义类
来源：http://dali.svipenyu.cn/Article/details/gtrjnuprmk.html

Py:   class User: pass
来源：http://dali.meibo888.top/Article/details/gtgtxsxpzw.html

PHP:  class User {}
来源：http://dali.redwolf501.top/Article/details/gtoheicstz.html

JS:   class User {}
来源：http://dali.sweek.top/Article/details/gtbdmuymhi.html

TS:   class User { name: string = ""; }
来源：http://dali.xylfe.cn/Article/details/gtvahlgvzb.html

Java: class User {}
来源：http://dali.9152youxi.cn/Article/details/gtxmzkwoaa.html

Go:   type User struct { Name string }
来源：http://dali.xziqi.cn/Article/details/gtfyhsnmfp.html

Ruby: class User; end
来源：http://dali.hongshengwenyu.top/Article/details/gtcnmgbapc.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gthdbwvnoo.html

[G02] 构造函数
来源：http://dali.jinqigfzy.top/Article/details/gtwimhkzfi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gogol.net.cn/Article/details/gtthtmjzaw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cdnleiting.top/Article/details/gtomqxymtx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gtmsbflsos.html

TS:   constructor(public name: string) {}
来源：http://dali.tanke756.top/Article/details/gtzvzxsnie.html

Java: User(String name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gthpzdtfgs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.snrcjt.cn/Article/details/gtiguriwmu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sufxvd.cn/Article/details/gtgzpdopks.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ivvv.top/Article/details/gtzbnktqfv.html

[G03] 实例属性
来源：http://dali.hfpthk.cn/Article/details/gtvmromyhn.html

Py:   self.name = "x"
来源：http://dali.hnxiangtu.top/Article/details/gtzwqqjqlw.html

PHP:  public string $name = "x";
来源：http://dali.nanxinkj.top/Article/details/gtixjzikct.html

JS:   this.name = "x";
来源：http://dali.316326.xyz/Article/details/gtwfigpuxu.html

TS:   name: string = "x";
来源：http://dali.daxiang520.top/Article/details/gtvfahnmlj.html

Java: private String name;
来源：http://dali.tianlin.xyz/Article/details/gtdvhufnrk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.guowangkeji.top/Article/details/gtrcammajv.html

Ruby: @name = "x"
来源：http://dali.fengsongda.top/Article/details/gtyzjyzzak.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.bjfxy.top/Article/details/gtuccusgco.html

[G04] 定义方法
来源：http://dali.dashuyun.cn/Article/details/gtnufmgodh.html

Py:   def greet(self): return self.name
来源：http://dali.hongshengwenyu.top/Article/details/gttxjyegdh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtylhzcnjm.html

JS:   greet() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtdzilzane.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtpedliadd.html

Java: String greet() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtrjpvvauc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gttplfxzlz.html

Ruby: def greet; @name; end
来源：http://dali.yuxming.cn/Article/details/gtbslesnbz.html

C#:   public string Greet() => Name;
来源：http://dali.birdmap.top/Article/details/gtdksewudv.html

[G05] 继承
来源：http://dali.dianchejie.cn/Article/details/gtpfeggsvh.html

Py:   class Admin(User): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhlksifo.html

PHP:  class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtbfcbgygd.html

JS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gttcthruyk.html

TS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtxaokwhuk.html

Java: class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtndevfojw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ivvv.top/Article/details/gtkactunlx.html

Ruby: class Admin < User; end
来源：http://dali.shzxlz.cn/Article/details/gtdvygwhto.html

C#:   class Admin : User {}
来源：http://dali.jqgfzy.top/Article/details/gtixpybmcf.html

[G06] 重写方法
来源：http://dali.smart0.xyz/Article/details/gtpwhofuch.html

Py:   def greet(self): return "admin"
来源：http://dali.jinghuilouyu.cn/Article/details/gtgljuuhri.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtlvfrjujs.html

JS:   greet() { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtlnvtxjod.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtudfayags.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtyhdofyqe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.haohaochexian.top/Article/details/gtqrmfuvkg.html

Ruby: def greet; "admin"; end
来源：http://dali.sweek.top/Article/details/gtnrkmiuyi.html

C#:   public override string Greet() => "admin";
来源：http://dali.xinyue.icu/Article/details/gtnwkzngtq.html

[G07] 调用父类方法
来源：http://dali.gaohongyu789.top/Article/details/gtyxcrkyoj.html

Py:   super().greet()
来源：http://dali.snrcjt.cn/Article/details/gteufqdgek.html

PHP:  parent::greet();
来源：http://dali.haohaochexian.top/Article/details/gtzmacoqgf.html

JS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gtwjtatqpy.html

TS:   super.greet();
来源：http://dali.hysaishi.cn/Article/details/gtgjgdpalz.html

Java: super.greet();
来源：http://dali.yj20258.top/Article/details/gtwnuedigc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yongpay.top/Article/details/gtvuuxvuwb.html

Ruby: super
来源：http://dali.aibaodan.cn/Article/details/gtyxolyzql.html

C#:   base.Greet();
来源：http://dali.jlsjyb.cn/Article/details/gtbpsymvbz.html

[G08] 静态方法与属性
来源：http://dali.hongshengwenyu.top/Article/details/gttcffhccj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cucudq.cn/Article/details/gtneenuocg.html

PHP:  public static function f() {}
来源：http://dali.yongpay.top/Article/details/gtnadrxker.html

JS:   static f() {}
来源：http://dali.haohaochexian.top/Article/details/gtiuuuthes.html

TS:   static f(): void {}
来源：http://dali.hongshengwenyu.top/Article/details/gtyyjbwpsq.html

Java: static void f() {}
来源：http://dali.zycfv.cn/Article/details/gtpwmocxjh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258888.top/Article/details/gtfdgtdtxt.html

Ruby: def self.f; end
来源：http://dali.cucudq.cn/Article/details/gtmgdwaeqx.html

C#:   public static void F() {}
来源：http://dali.jinqigufen.top/Article/details/gtfjrbvvrg.html

[G09] 接口 / 抽象类
来源：http://dali.snrcjt.cn/Article/details/gtercemmft.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yangfankeji.com/Article/details/gtkcrhpqwr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.9152youxi.cn/Article/details/gtxvrdqlcm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.andypj.xyz/Article/details/gtkxailfjn.html

TS:   interface Shape { area(): number; }
来源：http://dali.c1oappe.top/Article/details/gtrykzyebz.html

Java: interface Shape { double area(); }
来源：http://dali.zhengqikj.top/Article/details/gtdygpdszh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcunhmtdt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxbvuteye.html

C#:   interface IShape { double Area(); }
来源：http://dali.xylfe.cn/Article/details/gtvsuujfmf.html

[G10] 访问控制
来源：http://dali.dianchejie.cn/Article/details/gtgnxeknmu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daxiang520.top/Article/details/gtmaapsjft.html

PHP:  public / protected / private
来源：http://dali.cucudq.cn/Article/details/gttatztbvl.html

JS:   #private 字段；其余公开
来源：http://dali.nanxuanxn.top/Article/details/gtniwavpuo.html

TS:   public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtgggcsnil.html

Java: public / protected / private / 默认包级
来源：http://dali.snrcjt.cn/Article/details/gtpnypkyne.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.haohaochexian.top/Article/details/gtcxzviwni.html

Ruby: public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtznfkbfpj.html

C#:   public / protected / private / internal
来源：http://dali.aibaodan.cn/Article/details/gtcwibwvnz.html

[G11] getter / setter
来源：http://dali.jiagoushi.top/Article/details/gtjczqzzvy.html

Py:   @property 与 @x.setter
来源：http://dali.jqgfzy.top/Article/details/gtydvswemq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gttvryxwge.html

JS:   get name() { return this._name; }
来源：http://dali.yongpay.top/Article/details/gtuyfmcxbl.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gtwcomiocj.html

Java: public String getName() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtzeibqjqf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtfozbpecs.html

Ruby: attr_accessor :name
来源：http://dali.jiagoushi.top/Article/details/gtonzbczwt.html

C#:   public string Name { get; set; }
来源：http://dali.aizwys.cn/Article/details/gtqeadrfub.html

[G12] 对象转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtzuykwzco.html

Py:   def __str__(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gtzoendwyi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtlidnattp.html

JS:   toString() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtpqvquxgc.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gtksycrsnw.html

Java: @Override public String toString() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtenoiuxvc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gtpouymqpu.html

Ruby: def to_s; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gtafteofqf.html

C#:   public override string ToString() => Name;
来源：http://dali.guannengcc.top/Article/details/gtezbmyfks.html

[G13] 判断对象类型
来源：http://dali.bjfxy.top/Article/details/gtkrutiegl.html

Py:   isinstance(u, User)
来源：http://dali.316326.xyz/Article/details/gtusdcrzkp.html

PHP:  $u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtoalnhpao.html

JS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtpupbtilb.html

TS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gttowstyrm.html

Java: u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtsmjcmloc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuanzhike.top/Article/details/gtpgwhvgnv.html

Ruby: u.is_a?(User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkpozwhiz.html

C#:   u is User
来源：http://dali.jinqigfzy.top/Article/details/gtuklxdiyz.html

[G14] 数据类 / record
来源：http://dali.zhoulong.xyz/Article/details/gtsesnnnrf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hnqzz.top/Article/details/gtpkitiflb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangtech.top/Article/details/gturttlwfo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuanzx.com/Article/details/gtvwfgidgz.html

TS:   type User = { name: string; age: number };
来源：http://dali.havefunace.top/Article/details/gtmssebzyk.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gtgktojtaq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhixingplan.top/Article/details/gtxusxwuat.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sweek.top/Article/details/gtyirehpir.html

C#:   record User(string Name, int Age);
来源：http://dali.sysykeji.top/Article/details/gtxaeebwow.html

[G15] 枚举
来源：http://dali.dianchejie.cn/Article/details/gtqjbsttlr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.pycfn.com/Article/details/gtxsfaffbl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.dianchejie.cn/Article/details/gtjldveurh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqvkdxxl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gtdsrtvywj.html

Java: enum Color { RED, GREEN }
来源：http://dali.jlsjyb.cn/Article/details/gtgatsilmn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daxiang520.top/Article/details/gtzxhcxmjj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ppjwa.cn/Article/details/gtjmburumy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtnjqgvlgh.html

[G16] 对象转数组 / 字典
来源：http://dali.xuanzx.com/Article/details/gtjxothzix.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gotoacloud.top/Article/details/gtdxqanoco.html

PHP:  get_object_vars($obj);
来源：http://dali.pengpengdd.cyou/Article/details/gthxnbonme.html

JS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gtbhcekohg.html

TS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gtakgptekx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xinyue.icu/Article/details/gthficonaq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.snrcjt.cn/Article/details/gtpxymizpc.html

Ruby: obj.instance_variables
来源：http://dali.hywenlv.cn/Article/details/gtvjfqtrgz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yueranfly.top/Article/details/gtvqjdwdbj.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtsssrdfnf.html

H. 异常与错误处理
来源：http://dali.c1oappe.top/Article/details/gtmfzhacwq.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtpnenotll.html

[H01] try / catch 基础
来源：http://dali.ppjwa.cn/Article/details/gtudaugrxk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfiwgfkvk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj202588.top/Article/details/gtxfxirojr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnqmcpoy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gtktflynsk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gtpkvpbnvk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cucudq.cn/Article/details/gtzjpuqtfq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangdashe.top/Article/details/gtpykzvnus.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.fengsongda.top/Article/details/gtphxnurlk.html

[H02] finally / ensure 收尾
来源：http://dali.hfpthk.cn/Article/details/gtrjbftufg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gotoacloud.top/Article/details/gtkqnznnik.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtlatdpohf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtphjoiste.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtnndujsko.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtfnzmchzd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shuidangran.top/Article/details/gtkkfgnwgv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhoulong.xyz/Article/details/gtoscgfjhk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaesgfuxp.html

[H03] 主动抛出异常
来源：http://dali.kuanghao11.cn/Article/details/gtexphtmqe.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhengqikj.top/Article/details/gtrdlowwxn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gtqnxrgdzv.html

JS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gtrbsesdoz.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtertromkv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtiyrznssz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrwpfklbl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.c1oappe.top/Article/details/gtwmmzcghx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gtatrjlobp.html

[H04] 自定义异常类型
来源：http://dali.sysykeji.top/Article/details/gtszzhcehr.html

Py:   class MyError(Exception): pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshynwuhw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yonumen.top/Article/details/gtyvyplnnt.html

JS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtqbmszdlh.html

TS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gtfyqmrggq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gtnojgvxdt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gzhubu.top/Article/details/gtdoifulzl.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuxming.cn/Article/details/gtbuhgrwjz.html

C#:   class MyException : Exception {}
来源：http://dali.chenjidiqi.icu/Article/details/gtpkqxskzd.html

[H05] 捕获特定类型
来源：http://dali.jiagoushi.top/Article/details/gtpcncfslo.html

Py:   except ValueError as e:
来源：http://dali.nwbrower.top/Article/details/gtebbplziu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hnqzz.top/Article/details/gtmgdhalae.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gtcawixelf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gtebozurkp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aibaodan.cn/Article/details/gtruiyrchk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.c1oappe.top/Article/details/gtffiiqrxf.html

Ruby: rescue ArgumentError => e
来源：http://dali.gaohongyu789.top/Article/details/gtvbwqiutc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hysaishi.cn/Article/details/gtpnbqbleb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.vqdsnc.cn/Article/details/gtalqsjkis.html

Py:   value = d.get("k") or default
来源：http://dali.zhoulong.xyz/Article/details/gtpqhjgsyf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenjidiqi.icu/Article/details/gtucrkbcrt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.havefunace.top/Article/details/gtrxbvjnve.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gtvwnzcsmr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.316326.xyz/Article/details/gturprsozr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gaohongyu789.top/Article/details/gtvbublgfi.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gaohongyu789.top/Article/details/gtmsbsohrf.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj202588.top/Article/details/gtpedgbskh.html

[H07] 断言
来源：http://dali.chenlongwang.top/Article/details/gtohcjxrfl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.dianchejie.cn/Article/details/gtkyjdwwwb.html

PHP:  assert($x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtrmivftbm.html

JS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gtuecllyxm.html

TS:   console.assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtcavqfumd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ydzc1.top/Article/details/gtfdhqaabh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.iojbl.cn/Article/details/gtwhvxelnu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hongshengwenyu.top/Article/details/gthcgozvdr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtwkfanzgj.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxqsifdo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenzaomai.com/Article/details/gtmzgiutka.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hywenlv.cn/Article/details/gtewqmwpzg.html

JS:   e.message;  e.stack
来源：http://dali.cucudq.cn/Article/details/gtzoficwzi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.smart0.xyz/Article/details/gtfibqtpgv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cdnleiting.top/Article/details/gtzwpwwgso.html

Go:   err.Error()
来源：http://dali.aizwys.cn/Article/details/gtvtoaqtgj.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangdashe.top/Article/details/gtkehlyudh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.c1oappe.top/Article/details/gtniawvvax.html

[H09] 带错误码的异常
来源：http://dali.snrcjt.cn/Article/details/gtxmmzmgsg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jyoumei.cn/Article/details/gtjnrppqfx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jyoumei.cn/Article/details/gtzuptknon.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xuanzx.com/Article/details/gtboshsmdc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ehwqpu.com/Article/details/gtcpufriig.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gaohongyu789.top/Article/details/gtyrlnayla.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yangfankeji.com/Article/details/gtexcfwwgl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xinyue.icu/Article/details/gtbuaqtwmd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nwbrower.top/Article/details/gtmqtwyiue.html

[H10] 资源自动释放
来源：http://dali.zhoulong.xyz/Article/details/gtoiyzhari.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yangfankeji.com/Article/details/gteblkhxhr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yonumen.top/Article/details/gtjowbctqc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cheryme.top/Article/details/gtewgboarp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gtuwjfoair.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.vqdsnc.cn/Article/details/gtnpirwzre.html

Go:   defer f.Close()
来源：http://dali.ehwqpu.com/Article/details/gtfxosjshi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ydzc1.top/Article/details/gtbadqyuhf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtfaqemykm.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtfhisohpb.html

I. 正则表达式
来源：http://dali.yj20258888.top/Article/details/gtxzelabrq.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtbyttgwur.html

[I01] 判断是否匹配
来源：http://dali.tanke756.top/Article/details/gtyeauxhsp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.dianchejie.cn/Article/details/gtaxqvjdln.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtxalxxxsz.html

JS:   /\d+/.test(s)
来源：http://dali.sufxvd.cn/Article/details/gtwagmcqlr.html

TS:   /\d+/.test(s)
来源：http://dali.dianchejie.cn/Article/details/gteuuwzfeo.html


<!-- 参考信息 -->