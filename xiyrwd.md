代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtgamoycpe.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtxleyaqag.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuelmovgj.html

Ruby: File.exist?("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtmbowdghx.html

C#:   File.Exists("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtdpjskqaz.html

[F06] 删除文件
来源：http://dali.zhoulong.xyz/Article/details/gtuzjaatmx.html

Py:   os.remove("a.txt")
来源：http://dali.yongpay.top/Article/details/gtaoachfpn.html

PHP:  unlink("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtzrugvwzd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gttwapkksi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gtlcpdwftj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gtpouwpfyb.html

Go:   os.Remove("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtnexjuwub.html

Ruby: File.delete("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtvdumerxw.html

C#:   File.Delete("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtgrqrzywb.html

[F07] 创建目录（含多级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdowdhnte.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gzhubu.top/Article/details/gtvbegtyhc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthelgcndp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yonumen.top/Article/details/gtuhumxkwb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gtzyrsrftr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xuanzx.com/Article/details/gtbrbarmje.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sysykeji.top/Article/details/gtnjzvxpzv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aibaodan.cn/Article/details/gtnydnsajt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.fengsongda.top/Article/details/gtnxmrppbj.html

[F08] 遍历目录
来源：http://dali.0kj1m.cn/Article/details/gtlahhgpuu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sysykeji.top/Article/details/gthejqhsuq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hfpthk.cn/Article/details/gtyknrlxza.html

JS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gtikisofen.html

TS:   fs.readdirSync("dir")
来源：http://dali.yangfankeji.com/Article/details/gtjqhaduko.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvtnapiu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nanxinkj.top/Article/details/gtbnzkmxas.html

Ruby: Dir.children("dir")
来源：http://dali.yuxming.cn/Article/details/gtfogaovue.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ivvv.top/Article/details/gtyhgvkyvw.html

[F09] 获取文件大小
来源：http://dali.ydzc1.top/Article/details/gtjqpezyhs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtghnqwpeo.html

PHP:  filesize("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtvwnwetpt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gtjrwyfkjz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.iojbl.cn/Article/details/gtzvnnxolw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtnobnmvsl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.redwolf501.top/Article/details/gtibaxpold.html

Ruby: File.size("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtpuimzozc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sweek.top/Article/details/gtfefcwjbj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jlsjyb.cn/Article/details/gtdfzrcqse.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtszcwdzgb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nwbrower.top/Article/details/gtgnqzansk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtoazwhefe.html

TS:   path.extname("a.txt")
来源：http://dali.nwbrower.top/Article/details/gthdvoawkq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.birdmap.top/Article/details/gtowbdhxlr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtnnpamfqg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gthizjtzfy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtawdyigjh.html

[F11] 复制与移动文件
来源：http://dali.jianghu66.top/Article/details/gtrllpbtmj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtkmqnadtl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtipctiwyz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtenfidvgi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtweilqnvt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cucudq.cn/Article/details/gtodrhiyrd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj202588.top/Article/details/gtmkxoyhiy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gteextzduj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daria6918.cn/Article/details/gtbwebjhzv.html

[F12] CSV 读写
来源：http://dali.sysykeji.top/Article/details/gtgvvceggk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinqigfzy.top/Article/details/gtvrdyqjlq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnxiangtu.top/Article/details/gtxvknztys.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.wangdashe.top/Article/details/gtmzqlecmi.html

TS:   // 同上
来源：http://dali.gaohongyu789.top/Article/details/gtprmziezg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwdncutd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hongshengwenyu.top/Article/details/gtzzmqsxsb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.iojbl.cn/Article/details/gtrwtzzmxg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xziqi.cn/Article/details/gtgqvjqlhx.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtjhtihams.html

G. 面向对象
来源：http://dali.birdmap.top/Article/details/gtufuszsoa.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtazvcazta.html

[G01] 定义类
来源：http://dali.hnxiangtu.top/Article/details/gtijehujlb.html

Py:   class User: pass
来源：http://dali.svipenyu.cn/Article/details/gtqspwpnvo.html

PHP:  class User {}
来源：http://dali.sxryk.cn/Article/details/gtsdekhbfi.html

JS:   class User {}
来源：http://dali.wangdashe.top/Article/details/gtesiewlfy.html

TS:   class User { name: string = ""; }
来源：http://dali.cashguo.top/Article/details/gtxzmqwxie.html

Java: class User {}
来源：http://dali.mhx1999.top/Article/details/gtzuevsilx.html

Go:   type User struct { Name string }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzfbggai.html

Ruby: class User; end
来源：http://dali.jianghu66.top/Article/details/gtbvffjnye.html

C#:   class User {}
来源：http://dali.316326.xyz/Article/details/gttvaearaq.html

[G02] 构造函数
来源：http://dali.vqdsnc.cn/Article/details/gtgqhoxdah.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fzhhl.top/Article/details/gtrgjrrqpv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnxiangtu.top/Article/details/gtqjljiocd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlyjqujqa.html

TS:   constructor(public name: string) {}
来源：http://dali.hfpthk.cn/Article/details/gtnnhdkpul.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gtqgtkfloo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xuanzx.com/Article/details/gtnbzjbnpj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhoulong.xyz/Article/details/gtvesgvskt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenlongwang.top/Article/details/gtqiskdtrm.html

[G03] 实例属性
来源：http://dali.xuanzx.com/Article/details/gtzeuiykfm.html

Py:   self.name = "x"
来源：http://dali.yanxiufei.cn/Article/details/gtahijhiko.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxtlawedd.html

JS:   this.name = "x";
来源：http://dali.andypj.xyz/Article/details/gtmixajcud.html

TS:   name: string = "x";
来源：http://dali.ydzc1.top/Article/details/gtmpwiaqsz.html

Java: private String name;
来源：http://dali.iojbl.cn/Article/details/gtwswenszo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daria6918.cn/Article/details/gtrybaxwcc.html

Ruby: @name = "x"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnwgonshx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenzaomai.com/Article/details/gtpfvsvhfj.html

[G04] 定义方法
来源：http://dali.xuetiantiany.cn/Article/details/gtghqhfuef.html

Py:   def greet(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gtdzgpqesp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gtbgsnfkez.html

JS:   greet() { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gttyfysbmf.html

TS:   greet(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtjuhksnjh.html

Java: String greet() { return name; }
来源：http://dali.birdmap.top/Article/details/gtzawgfkay.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtfjlyfiay.html

Ruby: def greet; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gtizircapa.html

C#:   public string Greet() => Name;
来源：http://dali.birdmap.top/Article/details/gtwmuxrajl.html

[G05] 继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtegnyfcsi.html

Py:   class Admin(User): pass
来源：http://dali.smart0.xyz/Article/details/gtqvblqojs.html

PHP:  class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdsmnlaw.html

JS:   class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtklgtuzst.html

TS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtmfgfibru.html

Java: class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtzjigkynn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jianghu66.top/Article/details/gtqowfdlbh.html

Ruby: class Admin < User; end
来源：http://dali.guowangkeji.top/Article/details/gtpunjzwvb.html

C#:   class Admin : User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtdntvrudz.html

[G06] 重写方法
来源：http://dali.tianlin.xyz/Article/details/gtxcjlbbfq.html

Py:   def greet(self): return "admin"
来源：http://dali.guowangkeji.top/Article/details/gtozwqczex.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtiawlkbko.html

JS:   greet() { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtnnzfysmv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtmdolakyv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtzjvvtyje.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xylfe.cn/Article/details/gthqxxlmuv.html

Ruby: def greet; "admin"; end
来源：http://dali.ppjwa.cn/Article/details/gtzvaxiaof.html

C#:   public override string Greet() => "admin";
来源：http://dali.xinyue.icu/Article/details/gtkydkalaa.html

[G07] 调用父类方法
来源：http://dali.zhixingplan.top/Article/details/gtrxumzqyk.html

Py:   super().greet()
来源：http://dali.zhoulong.xyz/Article/details/gtdjoujtln.html

PHP:  parent::greet();
来源：http://dali.ydzc1.top/Article/details/gtujnzzlqb.html

JS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gtziffmbqe.html

TS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gtlwszydxg.html

Java: super.greet();
来源：http://dali.yueranfly.top/Article/details/gtszlsdopj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ppjwa.cn/Article/details/gtbdoykjkm.html

Ruby: super
来源：http://dali.0kj1m.cn/Article/details/gtcuqsoacp.html

C#:   base.Greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaidfzsuw.html

[G08] 静态方法与属性
来源：http://dali.wangshuangyany.cn/Article/details/gtzkdedhuj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tianlin.xyz/Article/details/gtbbgkvynw.html

PHP:  public static function f() {}
来源：http://dali.cdnleiting.top/Article/details/gtsigsmgvn.html

JS:   static f() {}
来源：http://dali.nanxuanxn.top/Article/details/gtvnfclezo.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfksomqc.html

Java: static void f() {}
来源：http://dali.birdmap.top/Article/details/gtrhhxoziw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.pycfn.com/Article/details/gtnfudjjer.html

Ruby: def self.f; end
来源：http://dali.birdmap.top/Article/details/gttfjzuiti.html

C#:   public static void F() {}
来源：http://dali.ydzc1.top/Article/details/gtkyuhswsk.html

[G09] 接口 / 抽象类
来源：http://dali.sweek.top/Article/details/gthcsyarhp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.dianchejie.cn/Article/details/gtentzflzd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jianghu66.top/Article/details/gtftvvepus.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pengpengdd.cyou/Article/details/gtkeghufwu.html

TS:   interface Shape { area(): number; }
来源：http://dali.redwolf501.top/Article/details/gtentrvjyq.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258.top/Article/details/gtgcxpghrl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guannengcc.top/Article/details/gtpzolipcg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yuanzhike.top/Article/details/gtvekcupbv.html

C#:   interface IShape { double Area(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtqszyhqbg.html

[G10] 访问控制
来源：http://dali.cashguo.top/Article/details/gtwrljwhyc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.pengpengdd.cyou/Article/details/gtbxpnrurw.html

PHP:  public / protected / private
来源：http://dali.yj202588.top/Article/details/gtpjqmvqze.html

JS:   #private 字段；其余公开
来源：http://dali.cashguo.top/Article/details/gtrhvbggvk.html

TS:   public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtkwzhlffq.html

Java: public / protected / private / 默认包级
来源：http://dali.nanxinkj.top/Article/details/gthrpwydgc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.mhx1999.top/Article/details/gtpzxstqky.html

Ruby: public / protected / private
来源：http://dali.c1oappe.top/Article/details/gteavftahw.html

C#:   public / protected / private / internal
来源：http://dali.meibo888.top/Article/details/gtkevubgmv.html

[G11] getter / setter
来源：http://dali.jiagoushi.top/Article/details/gtvirvphoo.html

Py:   @property 与 @x.setter
来源：http://dali.chenlongwang.top/Article/details/gtbztsogbq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gtfnrvvfic.html

JS:   get name() { return this._name; }
来源：http://dali.xziqi.cn/Article/details/gtiejpnqzh.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gtmfssxqnn.html

Java: public String getName() { return name; }
来源：http://dali.jianghu66.top/Article/details/gtbfyhrxlp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtmafnimwp.html

Ruby: attr_accessor :name
来源：http://dali.yj20258.top/Article/details/gtkzsmubvx.html

C#:   public string Name { get; set; }
来源：http://dali.ppjwa.cn/Article/details/gtbvpqnuei.html

[G12] 对象转字符串
来源：http://dali.yangfankeji.com/Article/details/gtwxegzwzy.html

Py:   def __str__(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gtuqfvaocf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gtnuhqzcmp.html

JS:   toString() { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtjuefwbku.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtacgtwdsi.html

Java: @Override public String toString() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtoliaiqzk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gtpxbyvdne.html

Ruby: def to_s; @name; end
来源：http://dali.c1oappe.top/Article/details/gtmyhenyua.html

C#:   public override string ToString() => Name;
来源：http://dali.jiagoushi.top/Article/details/gttyfdzxna.html

[G13] 判断对象类型
来源：http://dali.quarkkingdee.top/Article/details/gtoetvpczb.html

Py:   isinstance(u, User)
来源：http://dali.tian-w.cn/Article/details/gtpvfaobrs.html

PHP:  $u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtlobtkoat.html

JS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrfmzttt.html

TS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtvtfzvsem.html

Java: u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtvmhlnihq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.c1oappe.top/Article/details/gtywulryum.html

Ruby: u.is_a?(User)
来源：http://dali.tian-w.cn/Article/details/gtrtlgfiwq.html

C#:   u is User
来源：http://dali.yuxming.cn/Article/details/gtwqhlphfs.html

[G14] 数据类 / record
来源：http://dali.fzhhl.top/Article/details/gtxiqjyoca.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258.top/Article/details/gtnwfbtetq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yanxiufei.cn/Article/details/gtxwnhnvye.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj20258888.top/Article/details/gtbmghvkcq.html

TS:   type User = { name: string; age: number };
来源：http://dali.haohaochexian.top/Article/details/gtdvkuoswe.html

Java: record User(String name, int age) {}
来源：http://dali.xuanzx.com/Article/details/gtugstdmhv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.9152youxi.cn/Article/details/gtfdzrzrkg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ehwqpu.com/Article/details/gtmefzqnib.html

C#:   record User(string Name, int Age);
来源：http://dali.zhengqikj.top/Article/details/gtudrnhdbu.html

[G15] 枚举
来源：http://dali.xuetiantiany.cn/Article/details/gtkqrjnfmh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hywenlv.cn/Article/details/gtgxnlnpki.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ybcxt.top/Article/details/gtfklnbeku.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigufen.top/Article/details/gtjoeyxjdh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtnuccedni.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj20258888.top/Article/details/gtggbdtdfq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinqigufen.top/Article/details/gtrdruirrn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xuanzx.com/Article/details/gtquubmzng.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gtruchsbii.html

[G16] 对象转数组 / 字典
来源：http://dali.quarkkingdee.top/Article/details/gtyesedspw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzoioaxra.html

PHP:  get_object_vars($obj);
来源：http://dali.nanxinkj.top/Article/details/gtnwhoaozr.html

JS:   Object.entries(obj)
来源：http://dali.birdmap.top/Article/details/gtfsaeoxaj.html

TS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gtzhpufmnm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpkuwkqyl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvcukktf.html

Ruby: obj.instance_variables
来源：http://dali.nwbrower.top/Article/details/gtgwzghtqe.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cqqwz.cn/Article/details/gtugkbnfsn.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtmlljomuw.html

H. 异常与错误处理
来源：http://dali.ydzc1.top/Article/details/gtdlctiusw.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtkvxvjigg.html

[H01] try / catch 基础
来源：http://dali.hammf.cn/Article/details/gtnzejvcxs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.0kj1m.cn/Article/details/gtkdiukoff.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nwbrower.top/Article/details/gtjkxbmcpx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gthgexfgjv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gtanqicrrk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cheryme.top/Article/details/gtizdfhyxv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangshuangyany.cn/Article/details/gtbnkmnmtm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzyigtqwr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuanzx.com/Article/details/gtikbebtpf.html

[H02] finally / ensure 收尾
来源：http://dali.chenlongwang.top/Article/details/gtzayqywvl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.feifeiyinyue.top/Article/details/gthvjmcvyq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtoabujvxf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtishveglp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtdcgfweia.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtngspqdcc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yangfankeji.com/Article/details/gtjebdbfjd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guowangkeji.top/Article/details/gtwsgggdca.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtlyrtftsb.html

[H03] 主动抛出异常
来源：http://dali.zycfv.cn/Article/details/gtbdbdbgve.html

Py:   raise ValueError("错误信息")
来源：http://dali.cdnleiting.top/Article/details/gtgfsuwpgo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gtuzvcrefb.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtpcdirsjg.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtvxlpnysw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtkfkbqdjk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.meibo888.top/Article/details/gtjfqiozul.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenjidiqi.icu/Article/details/gtmamfqwrw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtbmaxyahf.html

[H04] 自定义异常类型
来源：http://dali.ybcxt.top/Article/details/gtxgnzwtic.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258888.top/Article/details/gtujjjvcku.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hnqzz.top/Article/details/gtknwwhylu.html

JS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gtxpcnssec.html

TS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gttysldmce.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gtwdtwdhru.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258888.top/Article/details/gtfubaonur.html

Ruby: class MyError < StandardError; end
来源：http://dali.gaohongyu789.top/Article/details/gtbwzxmwjv.html

C#:   class MyException : Exception {}
来源：http://dali.dashuyun.cn/Article/details/gtyrqvxova.html

[H05] 捕获特定类型
来源：http://dali.chenlongwang.top/Article/details/gtvozrtvjm.html

Py:   except ValueError as e:
来源：http://dali.yvedp.cn/Article/details/gtdtbdmyjm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gzhubu.top/Article/details/gtebndfxjf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gtwuakpoke.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gtrsuxsqtv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tian-w.cn/Article/details/gtwnprogdu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenzaomai.com/Article/details/gtxuswqcbp.html

Ruby: rescue ArgumentError => e
来源：http://dali.fengsongda.top/Article/details/gtzsotqmjj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cqqwz.cn/Article/details/gtoiimzixf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.mhx1999.top/Article/details/gtigtxvzmg.html

Py:   value = d.get("k") or default
来源：http://dali.pycfn.com/Article/details/gtdlvbmsby.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gtgvvvvnnn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gttklqpulx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gtahseqntu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cheryme.top/Article/details/gtyslepzvc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cheryme.top/Article/details/gtcxffsvgx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.fzhhl.top/Article/details/gtrxytmaws.html

C#:   obj?.A?.B ?? default
来源：http://dali.gogol.net.cn/Article/details/gtaazhfmaq.html

[H07] 断言
来源：http://dali.ppjwa.cn/Article/details/gtfvivtroa.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkquglhz.html

PHP:  assert($x > 0);
来源：http://dali.yueranfly.top/Article/details/gtlwljouzo.html

JS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtwdczgdch.html

TS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtbmgvgdwb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fengsongda.top/Article/details/gtjeqfcnmd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ehwqpu.com/Article/details/gtaemdxlxl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigfzy.top/Article/details/gthyyzjzfc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gtgqldxlrb.html

[H08] 获取错误信息与堆栈
来源：http://dali.sufxvd.cn/Article/details/gtfkmxzyea.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ppjwa.cn/Article/details/gtecvgxkzo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangdashe.top/Article/details/gteomgcdie.html

JS:   e.message;  e.stack
来源：http://dali.xziqi.cn/Article/details/gtkgcipmha.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yongpay.top/Article/details/gthehfqixn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sufxvd.cn/Article/details/gtansiamfo.html

Go:   err.Error()
来源：http://dali.fengsongda.top/Article/details/gtnghoavmn.html

Ruby: e.message;  e.backtrace
来源：http://dali.gzhubu.top/Article/details/gtdqiotcsr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yangfankeji.com/Article/details/gtjzvwblzy.html

[H09] 带错误码的异常
来源：http://dali.cucudq.cn/Article/details/gtnzrpchfc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yongpay.top/Article/details/gtxcsxqlmx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.daria6918.cn/Article/details/gtgtrrwzzm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.dianchejie.cn/Article/details/gtpyalwlvd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yongpay.top/Article/details/gtzxkmuixd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtayzekhxl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.guowangkeji.top/Article/details/gtubjwjylr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shangyingyoupin.top/Article/details/gtsaqifwrl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zycfv.cn/Article/details/gtyfalbkcq.html

[H10] 资源自动释放
来源：http://dali.yj20258888.top/Article/details/gttvwzwpmd.html


<!-- 参考信息 -->