代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtnnodlias.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzrafoef.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtvzgbjurz.html

Go:   os.Remove("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gttqxoyrmj.html

Ruby: File.delete("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtrqzusxgj.html

C#:   File.Delete("a.txt");
来源：http://dali.birdmap.top/Article/details/gtdawiwaiw.html

[F07] 创建目录（含多级）
来源：http://dali.yj20258888.top/Article/details/gtyktatayr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jlsjyb.cn/Article/details/gtrwssywrg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sxryk.cn/Article/details/gtxyvfwdvl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbvmwhhc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenlongwang.top/Article/details/gtoedqdssx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xylfe.cn/Article/details/gtywbgbgcy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkffbtaa.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sufxvd.cn/Article/details/gtdazjnstt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sufxvd.cn/Article/details/gtgbldjwml.html

[F08] 遍历目录
来源：http://dali.pycfn.com/Article/details/gtjysjokqs.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhongyouzk.top/Article/details/gtblbflhaf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.meibo888.top/Article/details/gtfjyonlzd.html

JS:   fs.readdirSync("dir")
来源：http://dali.zycfv.cn/Article/details/gtwytdkblr.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinqigufen.top/Article/details/gtluoschsh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gtijyfsomq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yuanzhike.top/Article/details/gtlpkijkyo.html

Ruby: Dir.children("dir")
来源：http://dali.chenzaomai.com/Article/details/gtcfbosazr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gzhubu.top/Article/details/gtzdhegdvr.html

[F09] 获取文件大小
来源：http://dali.zhiwuduotai.top/Article/details/gtnqeaxilu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtajfqusjq.html

PHP:  filesize("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtvxhgpdvd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ehwqpu.com/Article/details/gtxwwrieck.html

TS:   fs.statSync("a.txt").size
来源：http://dali.guowangkeji.top/Article/details/gtegltipnc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtjkqfproz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnxiangtu.top/Article/details/gthluurkca.html

Ruby: File.size("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvcguspxp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhiwuduotai.top/Article/details/gtzondiwfg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigfzy.top/Article/details/gtbsowwyqe.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtstrxbdzh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtrxcgjccb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtveswavkr.html

TS:   path.extname("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gthtdaecig.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhiwuduotai.top/Article/details/gtasidrqae.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtanxcfplf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtkdszpiex.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtmieaanal.html

[F11] 复制与移动文件
来源：http://dali.jqgfzy.top/Article/details/gtdiedtnbu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gthihljddu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tian-w.cn/Article/details/gtvfmjkktf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtiwuksjrm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtucoqfixl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sxryk.cn/Article/details/gtyichuiew.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjgjzaal.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtkpggzxcy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdebslst.html

[F12] CSV 读写
来源：http://dali.zhoulong.xyz/Article/details/gtwioufvhr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.daxiang520.top/Article/details/gtmvzscsqi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.bjfxy.top/Article/details/gtqudfckcc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jianghu66.top/Article/details/gtwcobnqru.html

TS:   // 同上
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpwaimhx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fengsongda.top/Article/details/gttybiidhz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xylfe.cn/Article/details/gtpywkzisk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sweek.top/Article/details/gtxxoprvts.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jqgfzy.top/Article/details/gtlswinivf.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtbmehkcza.html

G. 面向对象
来源：http://dali.vqdsnc.cn/Article/details/gtwhsqkkmr.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtniykmucm.html

[G01] 定义类
来源：http://dali.jianghu66.top/Article/details/gtammwjnmh.html

Py:   class User: pass
来源：http://dali.cqqwz.cn/Article/details/gtlwcjpozo.html

PHP:  class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtztzpnkhe.html

JS:   class User {}
来源：http://dali.xylfe.cn/Article/details/gtpbcsgsdp.html

TS:   class User { name: string = ""; }
来源：http://dali.tian-w.cn/Article/details/gtpzvfrjiq.html

Java: class User {}
来源：http://dali.yuanzhike.top/Article/details/gtiythweud.html

Go:   type User struct { Name string }
来源：http://dali.tanke756.top/Article/details/gtiltkgync.html

Ruby: class User; end
来源：http://dali.guowangkeji.top/Article/details/gtdhlrxgqp.html

C#:   class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtvlzplqmh.html

[G02] 构造函数
来源：http://dali.dianchejie.cn/Article/details/gtnlagsqef.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.mhx1999.top/Article/details/gtgfuwaklm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtrvxvjmej.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtwpjtcllu.html

TS:   constructor(public name: string) {}
来源：http://dali.jianghu66.top/Article/details/gtkgsvarfm.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtwbxtatwr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.smart0.xyz/Article/details/gtalsyzdiz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zycfv.cn/Article/details/gtboknuuzw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtafrmabxr.html

[G03] 实例属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfupcjapq.html

Py:   self.name = "x"
来源：http://dali.jyoumei.cn/Article/details/gtpokyflpk.html

PHP:  public string $name = "x";
来源：http://dali.cheryme.top/Article/details/gtykwsvnnt.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gturgszibp.html

TS:   name: string = "x";
来源：http://dali.dashuyun.cn/Article/details/gtnhrchdab.html

Java: private String name;
来源：http://dali.9152youxi.cn/Article/details/gtbzysxedg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhongyouzk.top/Article/details/gtwerpcawt.html

Ruby: @name = "x"
来源：http://dali.guannengcc.top/Article/details/gtuuuakwoy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cashguo.top/Article/details/gtdqjfoyjf.html

[G04] 定义方法
来源：http://dali.hnxiangtu.top/Article/details/gtcddmniqh.html

Py:   def greet(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gteiwllqfh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gtjnxctckg.html

JS:   greet() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttghigasd.html

TS:   greet(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtddknpjhx.html

Java: String greet() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtaqlvwtrq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gtrpmhfgdg.html

Ruby: def greet; @name; end
来源：http://dali.316326.xyz/Article/details/gtfslxxibp.html

C#:   public string Greet() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gtweaxgros.html

[G05] 继承
来源：http://dali.snrcjt.cn/Article/details/gtqdjgdgwc.html

Py:   class Admin(User): pass
来源：http://dali.daxiang520.top/Article/details/gtevdzqasc.html

PHP:  class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtlauhdurh.html

JS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtsxdmcwyj.html

TS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtysyhobmu.html

Java: class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtdlyvziul.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shuidangran.top/Article/details/gtftsoyrid.html

Ruby: class Admin < User; end
来源：http://dali.cashguo.top/Article/details/gtyjrrgbtx.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gtemppmgqy.html

[G06] 重写方法
来源：http://dali.zhongyouzk.top/Article/details/gtozboxtqp.html

Py:   def greet(self): return "admin"
来源：http://dali.hfpthk.cn/Article/details/gtjldcfojs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtbalonjjp.html

JS:   greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtulpylpzi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhzvxvyh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtyeolmoyt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nwbrower.top/Article/details/gtxxikmpnq.html

Ruby: def greet; "admin"; end
来源：http://dali.jiagoushi.top/Article/details/gtvklkdkqh.html

C#:   public override string Greet() => "admin";
来源：http://dali.xziqi.cn/Article/details/gtxrzatctd.html

[G07] 调用父类方法
来源：http://dali.cdnleiting.top/Article/details/gtdouaresd.html

Py:   super().greet()
来源：http://dali.andypj.xyz/Article/details/gthayggpsk.html

PHP:  parent::greet();
来源：http://dali.mhx1999.top/Article/details/gtwgdestow.html

JS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gtnxesmgwo.html

TS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtyyuvjeaj.html

Java: super.greet();
来源：http://dali.aibaodan.cn/Article/details/gtruexvgje.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hysaishi.cn/Article/details/gtuajljqso.html

Ruby: super
来源：http://dali.mhx1999.top/Article/details/gtnjxjqcpi.html

C#:   base.Greet();
来源：http://dali.nwbrower.top/Article/details/gttongshil.html

[G08] 静态方法与属性
来源：http://dali.andypj.xyz/Article/details/gtvqiapjzf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinghuilouyu.cn/Article/details/gtiiacxomh.html

PHP:  public static function f() {}
来源：http://dali.yj202588.top/Article/details/gthesvanxz.html

JS:   static f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gttpiusinu.html

TS:   static f(): void {}
来源：http://dali.jqgfzy.top/Article/details/gtjipecdhf.html

Java: static void f() {}
来源：http://dali.yj20258.top/Article/details/gtpzpegyjo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.snrcjt.cn/Article/details/gtyikbckoh.html

Ruby: def self.f; end
来源：http://dali.feifeiyinyue.top/Article/details/gtiaufkdrb.html

C#:   public static void F() {}
来源：http://dali.zdqjudy.top/Article/details/gtendfzgzw.html

[G09] 接口 / 抽象类
来源：http://dali.tanke756.top/Article/details/gtogaxkjth.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakapyifg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.feifeiyinyue.top/Article/details/gtdcybczno.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.fzhhl.top/Article/details/gtvsbirgsh.html

TS:   interface Shape { area(): number; }
来源：http://dali.hammf.cn/Article/details/gtovuaviai.html

Java: interface Shape { double area(); }
来源：http://dali.chenzaomai.com/Article/details/gtimirfbrg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shzxlz.cn/Article/details/gtgcnodwpi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sxryk.cn/Article/details/gtpkffxgcw.html

C#:   interface IShape { double Area(); }
来源：http://dali.zdqjudy.top/Article/details/gtjhqzxcxe.html

[G10] 访问控制
来源：http://dali.haohaochexian.top/Article/details/gtrfjhkbpn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guannengcc.top/Article/details/gthexxjuai.html

PHP:  public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gteaohqdom.html

JS:   #private 字段；其余公开
来源：http://dali.hnxiangtu.top/Article/details/gttwmepcwg.html

TS:   public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gtawfdblcx.html

Java: public / protected / private / 默认包级
来源：http://dali.feifeiyinyue.top/Article/details/gtptmbnwad.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqagwuzc.html

Ruby: public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtclbchjlt.html

C#:   public / protected / private / internal
来源：http://dali.xinyue.icu/Article/details/gtawbphrsu.html

[G11] getter / setter
来源：http://dali.xinyue.icu/Article/details/gtiobxvfvu.html

Py:   @property 与 @x.setter
来源：http://dali.jinghuilouyu.cn/Article/details/gtlpynrpof.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtzdnmhyac.html

JS:   get name() { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gtduxxlfiz.html

TS:   get name(): string { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gtxclrkzfs.html

Java: public String getName() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtbhmatttw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gtxylhnuhw.html

Ruby: attr_accessor :name
来源：http://dali.yangfankeji.com/Article/details/gtvgdqrucj.html

C#:   public string Name { get; set; }
来源：http://dali.shuidangran.top/Article/details/gtagxzwanj.html

[G12] 对象转字符串
来源：http://dali.0kj1m.cn/Article/details/gtgoumkmap.html

Py:   def __str__(self): return self.name
来源：http://dali.ivvv.top/Article/details/gttnvsntqb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gtkcphxvdj.html

JS:   toString() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gtsteubuhk.html

TS:   toString(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gthkhtssbd.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gttelnffly.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtogacumos.html

Ruby: def to_s; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhxyczlx.html

C#:   public override string ToString() => Name;
来源：http://dali.ppjwa.cn/Article/details/gtyjzaftev.html

[G13] 判断对象类型
来源：http://dali.wangshuangyany.cn/Article/details/gtkywruwvu.html

Py:   isinstance(u, User)
来源：http://dali.sweek.top/Article/details/gtrxovsbyo.html

PHP:  $u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtztsqbeuo.html

JS:   u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtswexrzyn.html

TS:   u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gtnrapqjno.html

Java: u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtkclmtnsa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cdnleiting.top/Article/details/gtfekoyyas.html

Ruby: u.is_a?(User)
来源：http://dali.hysaishi.cn/Article/details/gtrebtfomj.html

C#:   u is User
来源：http://dali.feifeiyinyue.top/Article/details/gtxrmiillh.html

[G14] 数据类 / record
来源：http://dali.jianghu66.top/Article/details/gtmuctfgrg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nwbrower.top/Article/details/gtmpzhalmi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.bjfxy.top/Article/details/gtwtqpeoed.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.haohaochexian.top/Article/details/gthyfassbx.html

TS:   type User = { name: string; age: number };
来源：http://dali.cqqwz.cn/Article/details/gtrvlfehyy.html

Java: record User(String name, int age) {}
来源：http://dali.sufxvd.cn/Article/details/gtldyfqcjf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zdqjudy.top/Article/details/gtrwpuftzv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sweek.top/Article/details/gtbvymqyae.html

C#:   record User(string Name, int Age);
来源：http://dali.tianlin.xyz/Article/details/gtbltraxgl.html

[G15] 枚举
来源：http://dali.tianlin.xyz/Article/details/gtdzvslrwv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ybcxt.top/Article/details/gttvoygsym.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tanke756.top/Article/details/gtznjlqxor.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjqtyprvm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttreqniwp.html

Java: enum Color { RED, GREEN }
来源：http://dali.gotoacloud.top/Article/details/gtuopzihof.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dianchejie.cn/Article/details/gtyrmvwdyu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj20258888.top/Article/details/gtxoztcxep.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtqasobval.html

[G16] 对象转数组 / 字典
来源：http://dali.havefunace.top/Article/details/gtnbgctgwg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmvtlhte.html

PHP:  get_object_vars($obj);
来源：http://dali.hongshengwenyu.top/Article/details/gtxguchufp.html

JS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoigkhdli.html

TS:   Object.entries(obj)
来源：http://dali.birdmap.top/Article/details/gtgqaolelg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj202588.top/Article/details/gtcelitqid.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.birdmap.top/Article/details/gtsnmfyccw.html

Ruby: obj.instance_variables
来源：http://dali.chenlongwang.top/Article/details/gtpqagicoz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hywenlv.cn/Article/details/gtiyfcllik.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobmawvfo.html

H. 异常与错误处理
来源：http://dali.yanxiufei.cn/Article/details/gtyfpreeeg.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtpyubqgkp.html

[H01] try / catch 基础
来源：http://dali.xylfe.cn/Article/details/gtpkolrdsm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.redwolf501.top/Article/details/gtztukhytt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guowangkeji.top/Article/details/gtxswbmnfc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtcieozobg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gthfohattx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhengqikj.top/Article/details/gteecnolmi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnxiangtu.top/Article/details/gtlnjanlqn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hammf.cn/Article/details/gtkykrmfjk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenjidiqi.icu/Article/details/gtqmuhtgfg.html

[H02] finally / ensure 收尾
来源：http://dali.zhongyouzk.top/Article/details/gtrizfopfk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shzxlz.cn/Article/details/gtuxpidhab.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtyjuiepfd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtnuprvbdq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtdbpcnamx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtaqqluxdg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgufenzy.top/Article/details/gtucgofwwk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cdnleiting.top/Article/details/gtsjvspyci.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtgbneepnk.html

[H03] 主动抛出异常
来源：http://dali.yj20258888.top/Article/details/gtkldfjvsf.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhfajflb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtjmfoffki.html

JS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtnxncjsmd.html

TS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gteqypajqu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtygeimisv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.dianchejie.cn/Article/details/gtrllgjcyn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuxming.cn/Article/details/gtwopwripd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtmylvqonl.html

[H04] 自定义异常类型
来源：http://dali.mhx1999.top/Article/details/gtymvddnjd.html

Py:   class MyError(Exception): pass
来源：http://dali.bjfxy.top/Article/details/gtubrustay.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gtjyzkoppi.html

JS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gtkmmxzamq.html

TS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gteftyybzm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shzxlz.cn/Article/details/gtrghplmid.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangshuangyany.cn/Article/details/gtdxgjyznv.html

Ruby: class MyError < StandardError; end
来源：http://dali.hongshengwenyu.top/Article/details/gttzkzzhxp.html

C#:   class MyException : Exception {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtgsknoxxc.html

[H05] 捕获特定类型
来源：http://dali.nanxuanxn.top/Article/details/gtisxpwmdo.html

Py:   except ValueError as e:
来源：http://dali.cashguo.top/Article/details/gtrokzwjut.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuanzx.com/Article/details/gtuexzdnti.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gttnvbcctj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.guowangkeji.top/Article/details/gtyszurtgz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtrpgbgwaz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xylfe.cn/Article/details/gtfctqozsy.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangdashe.top/Article/details/gtaivvkokh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dashuyun.cn/Article/details/gtehvcqckq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.feifeiyinyue.top/Article/details/gtyxutgiwd.html

Py:   value = d.get("k") or default
来源：http://dali.wangdashe.top/Article/details/gtzvrdjxon.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gtwbbekiyg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gtmqjckdwa.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gtmilhgrol.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tian-w.cn/Article/details/gtvnljwdnf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.redwolf501.top/Article/details/gtwhylksmf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.fengsongda.top/Article/details/gtiujbjyyb.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhixingplan.top/Article/details/gtgfzmdwhl.html

[H07] 断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmttsclqv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cheryme.top/Article/details/gtovpmqnbk.html

PHP:  assert($x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmlsrkxa.html

JS:   console.assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gtgmfiwsia.html

TS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gtasobxnkh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhoulong.xyz/Article/details/gtuhjdkntn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yanxiufei.cn/Article/details/gtkqlufauy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.iojbl.cn/Article/details/gtzzkrrhzg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gttmfqneov.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenzaomai.com/Article/details/gtlrtpttrv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gzhubu.top/Article/details/gtuwpaguev.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.dianchejie.cn/Article/details/gtqunascis.html

JS:   e.message;  e.stack
来源：http://dali.sysykeji.top/Article/details/gtciqcgxhz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yuanzhike.top/Article/details/gtoazitunr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.vqdsnc.cn/Article/details/gtgrqhiofq.html

Go:   err.Error()
来源：http://dali.yuxming.cn/Article/details/gttaapkhna.html

Ruby: e.message;  e.backtrace
来源：http://dali.nanxuanxn.top/Article/details/gteobxbmjx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hfpthk.cn/Article/details/gtvfwstaqh.html

[H09] 带错误码的异常
来源：http://dali.jianghu66.top/Article/details/gtyujuztuy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.haohaochexian.top/Article/details/gtfrvfwwmh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenzaomai.com/Article/details/gttjhxsmgv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.iojbl.cn/Article/details/gtpgergvmi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.snrcjt.cn/Article/details/gtdqieaxjn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj202588.top/Article/details/gtwtgtbgzm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daxiang520.top/Article/details/gtqdboznmj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.aizwys.cn/Article/details/gtaqfmpcya.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.quarkkingdee.top/Article/details/gtiisgqrhx.html

[H10] 资源自动释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypfpibal.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuanzhike.top/Article/details/gtdqvlhurb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhixingplan.top/Article/details/gtcethdzfu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gtrpqxurle.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gthxsmshxw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.dashuyun.cn/Article/details/gtwqelunyv.html

Go:   defer f.Close()
来源：http://dali.c1oappe.top/Article/details/gtrjffdzpn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.feifeiyinyue.top/Article/details/gtivkchtok.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtjowmmyiq.html


<!-- 参考信息 -->