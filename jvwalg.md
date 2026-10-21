代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtrjpocxpd.html

[F06] 删除文件
来源：http://dali.jqgfzy.top/Article/details/gtbpadpdta.html

Py:   os.remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtqxkmppvz.html

PHP:  unlink("a.txt");
来源：http://dali.cashguo.top/Article/details/gtdpbdnhcq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtazbiqhfx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtvoeevrhc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gtsjycqkek.html

Go:   os.Remove("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtslbbdypm.html

Ruby: File.delete("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtoevvsban.html

C#:   File.Delete("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtyfhppygf.html

[F07] 创建目录（含多级）
来源：http://dali.zycfv.cn/Article/details/gtnqopwioq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhiwuduotai.top/Article/details/gtkikxopqg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hammf.cn/Article/details/gtcdgzhxbe.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxinkj.top/Article/details/gtrczgpwub.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gtjlfcsxcn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj202588.top/Article/details/gtiwzxrgzn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gotoacloud.top/Article/details/gtgqjhainn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yanxiufei.cn/Article/details/gtnlwjzvbd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xziqi.cn/Article/details/gtqbdfysdj.html

[F08] 遍历目录
来源：http://dali.svipenyu.cn/Article/details/gtmffirwvd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuanzx.com/Article/details/gtuqtktrop.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tanke756.top/Article/details/gtpidautmj.html

JS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gteviulugc.html

TS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gtnjuuhevz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yuanzhike.top/Article/details/gtrpzuiguq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hywenlv.cn/Article/details/gtutqhggzx.html

Ruby: Dir.children("dir")
来源：http://dali.zdqjudy.top/Article/details/gtocqkyuhs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hnqzz.top/Article/details/gtfxymknqq.html

[F09] 获取文件大小
来源：http://dali.nanxinkj.top/Article/details/gtjfsuntjk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtkjeghxvn.html

PHP:  filesize("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtphhkcjks.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcrybnnku.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aizwys.cn/Article/details/gthdvwqoug.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtzpeaeobp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guowangkeji.top/Article/details/gtkufkzoom.html

Ruby: File.size("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtfzfxzkhi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhongyouzk.top/Article/details/gtkrrbgust.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.0kj1m.cn/Article/details/gtkirygiap.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtofnzznfw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtuthhsuji.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtcnusloyq.html

TS:   path.extname("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtpzojghuq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.andypj.xyz/Article/details/gtjhswylni.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtfwdvwqog.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtuyjplcrz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtpfcqjjme.html

[F11] 复制与移动文件
来源：http://dali.yj202588.top/Article/details/gtyskztdfn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtnqussnwy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.meibo888.top/Article/details/gtfeyxryhy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtfmpmhlzn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtwsuqjbqi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yvedp.cn/Article/details/gtpnzfkblp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnxiangtu.top/Article/details/gtboxyetcd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtuuzhfrus.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yvedp.cn/Article/details/gtcdfjtqzg.html

[F12] CSV 读写
来源：http://dali.yuanzhike.top/Article/details/gtsmsbvaeu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hysaishi.cn/Article/details/gtvvpccbhx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jyoumei.cn/Article/details/gtejyhlmdi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gaohongyu789.top/Article/details/gtdfdcwtry.html

TS:   // 同上
来源：http://dali.xuanzx.com/Article/details/gtpdomtyca.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgufenzy.top/Article/details/gtalrdwljz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.smart0.xyz/Article/details/gthrlphamv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.quarkkingdee.top/Article/details/gtevqcdben.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ivvv.top/Article/details/gtlfnlicjx.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtcdvkshjj.html

G. 面向对象
来源：http://dali.cucudq.cn/Article/details/gtaouecnpf.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtdluautub.html

[G01] 定义类
来源：http://dali.wangdashe.top/Article/details/gtjqtvlohv.html

Py:   class User: pass
来源：http://dali.snrcjt.cn/Article/details/gtbazrurin.html

PHP:  class User {}
来源：http://dali.iojbl.cn/Article/details/gtzkrcbmgx.html

JS:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtfuocmhkg.html

TS:   class User { name: string = ""; }
来源：http://dali.chenzaomai.com/Article/details/gtclpujric.html

Java: class User {}
来源：http://dali.ivvv.top/Article/details/gtweckxwuj.html

Go:   type User struct { Name string }
来源：http://dali.cdnleiting.top/Article/details/gtqfrgmjdb.html

Ruby: class User; end
来源：http://dali.xziqi.cn/Article/details/gtstyqwale.html

C#:   class User {}
来源：http://dali.yongpay.top/Article/details/gtoymieoqp.html

[G02] 构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gtmtigqioe.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hfpthk.cn/Article/details/gtiyojyfde.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhongyouzk.top/Article/details/gtqpmbxwki.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtdibipfks.html

TS:   constructor(public name: string) {}
来源：http://dali.zhongyouzk.top/Article/details/gtvqyzoole.html

Java: User(String name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gtqmvoxeek.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.dashuyun.cn/Article/details/gtdmyunvsh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.redwolf501.top/Article/details/gtvphavjjh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nwbrower.top/Article/details/gtaapulmzu.html

[G03] 实例属性
来源：http://dali.yueranfly.top/Article/details/gtwwirxwtq.html

Py:   self.name = "x"
来源：http://dali.yanxiufei.cn/Article/details/gtkivvuutp.html

PHP:  public string $name = "x";
来源：http://dali.cqqwz.cn/Article/details/gtfpfhbwdk.html

JS:   this.name = "x";
来源：http://dali.cashguo.top/Article/details/gtzomtxxlq.html

TS:   name: string = "x";
来源：http://dali.yonumen.top/Article/details/gtgvercnyz.html

Java: private String name;
来源：http://dali.hnxiangtu.top/Article/details/gtzifdftka.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yanxiufei.cn/Article/details/gtmvhwsxnv.html

Ruby: @name = "x"
来源：http://dali.xylfe.cn/Article/details/gtptjnhdif.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sufxvd.cn/Article/details/gtorvkbmgj.html

[G04] 定义方法
来源：http://dali.snrcjt.cn/Article/details/gtyjsnepgb.html

Py:   def greet(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gtuxrtmfto.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtneuswogv.html

JS:   greet() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gtxziehukw.html

TS:   greet(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gttyofpwdr.html

Java: String greet() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtpixcqkfx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtqghehwzb.html

Ruby: def greet; @name; end
来源：http://dali.snrcjt.cn/Article/details/gtdavwtwcy.html

C#:   public string Greet() => Name;
来源：http://dali.ppjwa.cn/Article/details/gtsceqteih.html

[G05] 继承
来源：http://dali.yuanzhike.top/Article/details/gtzzodfyjc.html

Py:   class Admin(User): pass
来源：http://dali.xylfe.cn/Article/details/gtyfnowhgb.html

PHP:  class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtpxclupcq.html

JS:   class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtwbuufgud.html

TS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtqephbnkc.html

Java: class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtoxrdbeul.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nwbrower.top/Article/details/gtgnrafsoe.html

Ruby: class Admin < User; end
来源：http://dali.cdnleiting.top/Article/details/gtlvxhhvkf.html

C#:   class Admin : User {}
来源：http://dali.redwolf501.top/Article/details/gtawdakhwe.html

[G06] 重写方法
来源：http://dali.chenzaomai.com/Article/details/gteuyrfrmd.html

Py:   def greet(self): return "admin"
来源：http://dali.redwolf501.top/Article/details/gtenjqshzr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtuzejipgn.html

JS:   greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtqusnhzvb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtjcqxabeq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwhzynuvj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yuanzhike.top/Article/details/gtezlwxscr.html

Ruby: def greet; "admin"; end
来源：http://dali.aizwys.cn/Article/details/gtitmveifa.html

C#:   public override string Greet() => "admin";
来源：http://dali.dianchejie.cn/Article/details/gtcsscnygs.html

[G07] 调用父类方法
来源：http://dali.fengsongda.top/Article/details/gtizvatyth.html

Py:   super().greet()
来源：http://dali.xinyue.icu/Article/details/gtxefcxinl.html

PHP:  parent::greet();
来源：http://dali.jlsjyb.cn/Article/details/gtbcjftcue.html

JS:   super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtpwditgow.html

TS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtqogsygpj.html

Java: super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtwsztydvb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nanxinkj.top/Article/details/gtliadohdw.html

Ruby: super
来源：http://dali.xinyue.icu/Article/details/gtpzrlsxxv.html

C#:   base.Greet();
来源：http://dali.meibo888.top/Article/details/gtzluqmwsu.html

[G08] 静态方法与属性
来源：http://dali.jyoumei.cn/Article/details/gtgsiknygy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuxming.cn/Article/details/gtrwthjvkm.html

PHP:  public static function f() {}
来源：http://dali.yanxiufei.cn/Article/details/gthxeynrrs.html

JS:   static f() {}
来源：http://dali.cdnleiting.top/Article/details/gtutfpgwjx.html

TS:   static f(): void {}
来源：http://dali.fengsongda.top/Article/details/gtpsdtbfmm.html

Java: static void f() {}
来源：http://dali.daxiang520.top/Article/details/gtpbhhxhiz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.aizwys.cn/Article/details/gthnbepurt.html

Ruby: def self.f; end
来源：http://dali.redwolf501.top/Article/details/gtchecyhpm.html

C#:   public static void F() {}
来源：http://dali.xuanzx.com/Article/details/gtcaayxfbb.html

[G09] 接口 / 抽象类
来源：http://dali.zhongyouzk.top/Article/details/gtftpuwyhb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.bjfxy.top/Article/details/gtnqkkgzlh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmzjlrvct.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jiagoushi.top/Article/details/gtnroqhisp.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxinkj.top/Article/details/gtkwbnrxuu.html

Java: interface Shape { double area(); }
来源：http://dali.zhengqikj.top/Article/details/gtmnkiginx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daxiang520.top/Article/details/gttfdzzjet.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aizwys.cn/Article/details/gthopocrnq.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigufen.top/Article/details/gttzllyvau.html

[G10] 访问控制
来源：http://dali.vqdsnc.cn/Article/details/gthydrquoz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdqqoycm.html

PHP:  public / protected / private
来源：http://dali.cucudq.cn/Article/details/gtghsrckhd.html

JS:   #private 字段；其余公开
来源：http://dali.haohaochexian.top/Article/details/gtqvirymef.html

TS:   public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtrefqjnwt.html

Java: public / protected / private / 默认包级
来源：http://dali.jyoumei.cn/Article/details/gtfgddblvi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.wangdashe.top/Article/details/gtlkauhwqg.html

Ruby: public / protected / private
来源：http://dali.pycfn.com/Article/details/gtquaqnoxp.html

C#:   public / protected / private / internal
来源：http://dali.gogol.net.cn/Article/details/gtemmdghaj.html

[G11] getter / setter
来源：http://dali.birdmap.top/Article/details/gtnurpayam.html

Py:   @property 与 @x.setter
来源：http://dali.c1oappe.top/Article/details/gtotdixirs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtxwmtcqhv.html

JS:   get name() { return this._name; }
来源：http://dali.ivvv.top/Article/details/gtubtyfxia.html

TS:   get name(): string { return this._name; }
来源：http://dali.yongpay.top/Article/details/gtemeiiexu.html

Java: public String getName() { return name; }
来源：http://dali.sweek.top/Article/details/gtimhdevqi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthgiakrxb.html

Ruby: attr_accessor :name
来源：http://dali.ydzc1.top/Article/details/gtifzewjcj.html

C#:   public string Name { get; set; }
来源：http://dali.tanke756.top/Article/details/gttqjzyssb.html

[G12] 对象转字符串
来源：http://dali.yueranfly.top/Article/details/gtefkpacbo.html

Py:   def __str__(self): return self.name
来源：http://dali.xuetiantiany.cn/Article/details/gtduruqwfe.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtfoulngku.html

JS:   toString() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwvegghp.html

TS:   toString(): string { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtdwtariod.html

Java: @Override public String toString() { return name; }
来源：http://dali.xylfe.cn/Article/details/gtpmuiipfg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtboocugte.html

Ruby: def to_s; @name; end
来源：http://dali.yonumen.top/Article/details/gtcejbhzec.html

C#:   public override string ToString() => Name;
来源：http://dali.hywenlv.cn/Article/details/gtuvhdeyse.html

[G13] 判断对象类型
来源：http://dali.gzhubu.top/Article/details/gttibxuiyg.html

Py:   isinstance(u, User)
来源：http://dali.hysaishi.cn/Article/details/gtubrsbgfo.html

PHP:  $u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtvlpwkmmc.html

JS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtqukzlljc.html

TS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gthyimoavq.html

Java: u instanceof User
来源：http://dali.yj20258888.top/Article/details/gthnvgpfij.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.guowangkeji.top/Article/details/gtsdeeorou.html

Ruby: u.is_a?(User)
来源：http://dali.chenzaomai.com/Article/details/gtmefwalya.html

C#:   u is User
来源：http://dali.shzxlz.cn/Article/details/gtrzlkdhcd.html

[G14] 数据类 / record
来源：http://dali.316326.xyz/Article/details/gtjvbkrjst.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dashuyun.cn/Article/details/gtajsatyht.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ydzc1.top/Article/details/gtpsvapahy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenzaomai.com/Article/details/gttvtvmpqa.html

TS:   type User = { name: string; age: number };
来源：http://dali.svipenyu.cn/Article/details/gtlrznaznc.html

Java: record User(String name, int age) {}
来源：http://dali.guowangkeji.top/Article/details/gttqldeetm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nanxuanxn.top/Article/details/gtlygknwel.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jiagoushi.top/Article/details/gtiplziqxl.html

C#:   record User(string Name, int Age);
来源：http://dali.xinyue.icu/Article/details/gtkesknkuo.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gtsyaoxprk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yanxiufei.cn/Article/details/gtzptciqtt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tanke756.top/Article/details/gtzniraeog.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yangfankeji.com/Article/details/gtcywhzrlb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gtbjzgzkjt.html

Java: enum Color { RED, GREEN }
来源：http://dali.xuanzx.com/Article/details/gtzacjujwu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjsctnwvo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnqzz.top/Article/details/gtmvfghvlf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gtueyykuyr.html

[G16] 对象转数组 / 字典
来源：http://dali.hfpthk.cn/Article/details/gtdrutemvc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ppjwa.cn/Article/details/gtuhdldqsr.html

PHP:  get_object_vars($obj);
来源：http://dali.yongpay.top/Article/details/gtictapdqz.html

JS:   Object.entries(obj)
来源：http://dali.chenlongwang.top/Article/details/gtswmqwewc.html

TS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gtrswfdtxa.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xuetiantiany.cn/Article/details/gtcciunjxs.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.feifeiyinyue.top/Article/details/gttmmkzuzf.html

Ruby: obj.instance_variables
来源：http://dali.zycfv.cn/Article/details/gttrnmzomm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhixingplan.top/Article/details/gtapouriee.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtpgrdrfiy.html

H. 异常与错误处理
来源：http://dali.hnqzz.top/Article/details/gtdhppzzuo.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtqarwxfdq.html

[H01] try / catch 基础
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfivtssev.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gtbcplxswx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gaohongyu789.top/Article/details/gthagnrgat.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gtahyicihv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jyoumei.cn/Article/details/gtbffiofvs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jyoumei.cn/Article/details/gtpqpxoaub.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnqzz.top/Article/details/gtjdjlafxm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sweek.top/Article/details/gtzghspvgj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.bjfxy.top/Article/details/gtmokhprom.html

[H02] finally / ensure 收尾
来源：http://dali.chenjidiqi.icu/Article/details/gtwmpzfnar.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gzhubu.top/Article/details/gtlwnrdqnm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtdyckzfeu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtmzflbqls.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gthrzitvas.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtucmiamdu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gtdmxfycjt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.pycfn.com/Article/details/gtconktiob.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ivvv.top/Article/details/gthkpdlmml.html

[H03] 主动抛出异常
来源：http://dali.feifeiyinyue.top/Article/details/gtsmhfzybo.html

Py:   raise ValueError("错误信息")
来源：http://dali.jlsjyb.cn/Article/details/gtbyfqxijh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtpomnahbe.html

JS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gthpojnrzc.html

TS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gtfuhajtoh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtbfxdugfi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigfzy.top/Article/details/gtyemvzqsa.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.vqdsnc.cn/Article/details/gtqhhhpmaz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtjfhwhoqt.html

[H04] 自定义异常类型
来源：http://dali.zycfv.cn/Article/details/gtieagjcby.html

Py:   class MyError(Exception): pass
来源：http://dali.haohaochexian.top/Article/details/gttxijioby.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.feifeiyinyue.top/Article/details/gtkvocxtkw.html

JS:   class MyError extends Error {}
来源：http://dali.daxiang520.top/Article/details/gtzkqeqygp.html

TS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gtuqwimwna.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmldqcre.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shuidangran.top/Article/details/gtzjtdyswz.html

Ruby: class MyError < StandardError; end
来源：http://dali.kuanghao11.cn/Article/details/gtigejiscx.html

C#:   class MyException : Exception {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnhwwtbb.html

[H05] 捕获特定类型
来源：http://dali.gotoacloud.top/Article/details/gtebcugtgf.html

Py:   except ValueError as e:
来源：http://dali.xylfe.cn/Article/details/gtdtuafmyw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhengqikj.top/Article/details/gtcwlsmpiy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gtirmtpvfh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtmanzqyqt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gogol.net.cn/Article/details/gtafrimksd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.pengpengdd.cyou/Article/details/gtnthhxhyj.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhongyouzk.top/Article/details/gtacvrbnkd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cucudq.cn/Article/details/gtvryscpsh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yuxming.cn/Article/details/gtfeorhjbd.html

Py:   value = d.get("k") or default
来源：http://dali.zhengqikj.top/Article/details/gtfswtkskd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gtxlqgtgxy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gtqyhllngg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gthfhmdnst.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shangyingyoupin.top/Article/details/gtwcdaplvz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigfzy.top/Article/details/gtygzyspnx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dashuyun.cn/Article/details/gtoqjgodnr.html

C#:   obj?.A?.B ?? default
来源：http://dali.sweek.top/Article/details/gtavsscrkk.html

[H07] 断言
来源：http://dali.yongpay.top/Article/details/gtzserrvfl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jyoumei.cn/Article/details/gtgfzgzeqx.html

PHP:  assert($x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtqiykvqdh.html

JS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtqwxehden.html

TS:   console.assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpnoblkzy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shangyingyoupin.top/Article/details/gtyawodvlz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangdashe.top/Article/details/gtqxvtnkgd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guowangkeji.top/Article/details/gtfrfogzdq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gtlthznubq.html

[H08] 获取错误信息与堆栈
来源：http://dali.sxryk.cn/Article/details/gtkiyokqxj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jqgfzy.top/Article/details/gtvrwhkcfz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cucudq.cn/Article/details/gtoepktjes.html

JS:   e.message;  e.stack
来源：http://dali.mhx1999.top/Article/details/gtptnqgpsv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hysaishi.cn/Article/details/gtqmchfrty.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hammf.cn/Article/details/gtolnfqjia.html

Go:   err.Error()
来源：http://dali.nwbrower.top/Article/details/gtgwdubgzi.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigfzy.top/Article/details/gtoqekrvgl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.feifeiyinyue.top/Article/details/gtsbjnqwqq.html

[H09] 带错误码的异常
来源：http://dali.zhongyouzk.top/Article/details/gteboxwfat.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.andypj.xyz/Article/details/gtheigcswk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258.top/Article/details/gtubaefjwq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yonumen.top/Article/details/gtmazdnktj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jyoumei.cn/Article/details/gtquubpmdg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzafkogff.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.guowangkeji.top/Article/details/gtfkhwdcpt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.fengsongda.top/Article/details/gtxsjkncal.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jianghu66.top/Article/details/gtnljmbiue.html

[H10] 资源自动释放
来源：http://dali.guowangkeji.top/Article/details/gtukgfcesb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenzaomai.com/Article/details/gtfpowlnpv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.andypj.xyz/Article/details/gtsvwjvmxo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.kuanghao11.cn/Article/details/gtacdqliyi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shzxlz.cn/Article/details/gtgetqncme.html


<!-- 参考信息 -->