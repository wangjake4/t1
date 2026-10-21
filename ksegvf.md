代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shuidangran.top/Article/details/gtmjkdrwhy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gotoacloud.top/Article/details/gtzphokpmf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigufen.top/Article/details/gtuzcewbyw.html

[F04] 追加写入文件
来源：http://dali.guannengcc.top/Article/details/gtdvwgilpr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xziqi.cn/Article/details/gtuwdrbppp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.316326.xyz/Article/details/gtezieugnd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dashuyun.cn/Article/details/gtferbidrt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtbxxqnetf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.guannengcc.top/Article/details/gtmfseyddh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yuxming.cn/Article/details/gtyqahioti.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.aibaodan.cn/Article/details/gtdeyobuva.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.0kj1m.cn/Article/details/gtvoqtnnqg.html

[F05] 判断文件或目录是否存在
来源：http://dali.jqgfzy.top/Article/details/gtshgnyapd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.pycfn.com/Article/details/gtmskcbxuf.html

PHP:  file_exists("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtjbkvmjso.html

JS:   fs.existsSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtytxrjcrs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtylsyagnw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtallxthgc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nanxinkj.top/Article/details/gtbpselxdp.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtnxzmzfme.html

C#:   File.Exists("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtrbuydmql.html

[F06] 删除文件
来源：http://dali.dianchejie.cn/Article/details/gtddubzccz.html

Py:   os.remove("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtmwbncxej.html

PHP:  unlink("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtvahlcsuf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gttkvvwnwx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtgdslgnef.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtmowmuhxj.html

Go:   os.Remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtdxlgokxy.html

Ruby: File.delete("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtncyhfdka.html

C#:   File.Delete("a.txt");
来源：http://dali.ivvv.top/Article/details/gtymsgphxm.html

[F07] 创建目录（含多级）
来源：http://dali.tian-w.cn/Article/details/gtkwlluoqb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tanke756.top/Article/details/gtvyyltezd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tian-w.cn/Article/details/gtkllmzglg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gtkznwolpa.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenzaomai.com/Article/details/gttbkdbysd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.feifeiyinyue.top/Article/details/gttdgcdtsd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shangyingyoupin.top/Article/details/gtsnwqpvsa.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aibaodan.cn/Article/details/gtwsnqruhh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenzaomai.com/Article/details/gtmmfzoxwp.html

[F08] 遍历目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtqajvoecm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nanxinkj.top/Article/details/gtsjzzqmcw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xuetiantiany.cn/Article/details/gtmdbzdici.html

JS:   fs.readdirSync("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtppcczqdr.html

TS:   fs.readdirSync("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtgbyeeusq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shangyingyoupin.top/Article/details/gtedveepso.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tianlin.xyz/Article/details/gtbqqsrcuy.html

Ruby: Dir.children("dir")
来源：http://dali.haohaochexian.top/Article/details/gtbelxopfx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgfzy.top/Article/details/gtujolmnwb.html

[F09] 获取文件大小
来源：http://dali.gogol.net.cn/Article/details/gtpfeombqy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtdfgecool.html

PHP:  filesize("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtjrgnupid.html

JS:   fs.statSync("a.txt").size
来源：http://dali.vqdsnc.cn/Article/details/gtuzmdvuuu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yangfankeji.com/Article/details/gtzsyewewg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtfluawmfg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigfzy.top/Article/details/gtueutrbiw.html

Ruby: File.size("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtgvywbreg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ydzc1.top/Article/details/gtolxpqwud.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.dianchejie.cn/Article/details/gttgyqotes.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtihbcdvkq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtwyzsyupk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtedmcnyyd.html

TS:   path.extname("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtlxxrccsz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cheryme.top/Article/details/gttcazslux.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtmxjefbzs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtvrnskebn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtnqetrfcj.html

[F11] 复制与移动文件
来源：http://dali.zhoulong.xyz/Article/details/gtcircgmhq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtztkrjuuo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtbyyhycpq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtkmuzdbnf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtpoqxstuy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.birdmap.top/Article/details/gtjqhvtfpn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hywenlv.cn/Article/details/gtkpfwyuhd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtgqqukafd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daria6918.cn/Article/details/gtyeemixkc.html

[F12] CSV 读写
来源：http://dali.daxiang520.top/Article/details/gtixhgwbuw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jlsjyb.cn/Article/details/gtjursfkiv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jlsjyb.cn/Article/details/gtdzmfdhbe.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yonumen.top/Article/details/gtqiuzoilg.html

TS:   // 同上
来源：http://dali.kuanghao11.cn/Article/details/gthkrocooq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.iojbl.cn/Article/details/gthwzxpwbe.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hysaishi.cn/Article/details/gtkynfaspu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.daria6918.cn/Article/details/gtbgydgetc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xziqi.cn/Article/details/gtqwjvhahl.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtwbhtourl.html

G. 面向对象
来源：http://dali.pengpengdd.cyou/Article/details/gtjuuuxkkt.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrpyptjdr.html

[G01] 定义类
来源：http://dali.sufxvd.cn/Article/details/gtsalddpgh.html

Py:   class User: pass
来源：http://dali.smart0.xyz/Article/details/gttevlgfgj.html

PHP:  class User {}
来源：http://dali.tianlin.xyz/Article/details/gtsunqmbmy.html

JS:   class User {}
来源：http://dali.gzhubu.top/Article/details/gtasgwemej.html

TS:   class User { name: string = ""; }
来源：http://dali.zhixingplan.top/Article/details/gtodqevhtd.html

Java: class User {}
来源：http://dali.pycfn.com/Article/details/gttvsdkfpj.html

Go:   type User struct { Name string }
来源：http://dali.wangshuangyany.cn/Article/details/gtehwvvxve.html

Ruby: class User; end
来源：http://dali.iojbl.cn/Article/details/gttgwtxudj.html

C#:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtkbffbpgn.html

[G02] 构造函数
来源：http://dali.fzhhl.top/Article/details/gtofgrfouf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.316326.xyz/Article/details/gtgyqmeamh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.quarkkingdee.top/Article/details/gtmovpcsfr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gtfetohbtz.html

TS:   constructor(public name: string) {}
来源：http://dali.nwbrower.top/Article/details/gtjkpneclk.html

Java: User(String name) { this.name = name; }
来源：http://dali.cucudq.cn/Article/details/gtzrukydlg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhengqikj.top/Article/details/gtyxrlffru.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hongshengwenyu.top/Article/details/gtkkuishwl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenlongwang.top/Article/details/gtgliqrmur.html

[G03] 实例属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtzcdtmqyu.html

Py:   self.name = "x"
来源：http://dali.cqqwz.cn/Article/details/gtbltahibt.html

PHP:  public string $name = "x";
来源：http://dali.yongpay.top/Article/details/gtikozzfcn.html

JS:   this.name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtcnfbcruo.html

TS:   name: string = "x";
来源：http://dali.chenzaomai.com/Article/details/gtnucidvwn.html

Java: private String name;
来源：http://dali.9152youxi.cn/Article/details/gtkhtuzifq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.kuanghao11.cn/Article/details/gtdozowiod.html

Ruby: @name = "x"
来源：http://dali.mhx1999.top/Article/details/gtvatslzob.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtcmabcydb.html

[G04] 定义方法
来源：http://dali.smart0.xyz/Article/details/gtrarrocdt.html

Py:   def greet(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gtwcgzibfz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gtflbgxtpb.html

JS:   greet() { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gthajyupzf.html

TS:   greet(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtvrulkvlr.html

Java: String greet() { return name; }
来源：http://dali.fengsongda.top/Article/details/gtjilfhjtf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gtwfdlkkzi.html

Ruby: def greet; @name; end
来源：http://dali.yuanzhike.top/Article/details/gtpuyuwexj.html

C#:   public string Greet() => Name;
来源：http://dali.zdqjudy.top/Article/details/gtnofamcsq.html

[G05] 继承
来源：http://dali.ybcxt.top/Article/details/gtditapkiy.html

Py:   class Admin(User): pass
来源：http://dali.ydzc1.top/Article/details/gtkpzsobnc.html

PHP:  class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtvxqdmfhw.html

JS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtugywekpz.html

TS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtbpfmfwgu.html

Java: class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtishvmqxs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfcqpgqhb.html

Ruby: class Admin < User; end
来源：http://dali.pycfn.com/Article/details/gtjkygjqvy.html

C#:   class Admin : User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxvbftgt.html

[G06] 重写方法
来源：http://dali.wangdashe.top/Article/details/gtafrmccvm.html

Py:   def greet(self): return "admin"
来源：http://dali.wangdashe.top/Article/details/gtcprcaiyw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gttntcdclo.html

JS:   greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtlpooiozd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtbtbjwdbt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtpeqcrokp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.c1oappe.top/Article/details/gtrunqeuxg.html

Ruby: def greet; "admin"; end
来源：http://dali.gotoacloud.top/Article/details/gtmaqhymru.html

C#:   public override string Greet() => "admin";
来源：http://dali.hammf.cn/Article/details/gtsboyiitc.html

[G07] 调用父类方法
来源：http://dali.kuanghao11.cn/Article/details/gtebzvsozv.html

Py:   super().greet()
来源：http://dali.haohaochexian.top/Article/details/gtpiactgxv.html

PHP:  parent::greet();
来源：http://dali.snrcjt.cn/Article/details/gtelatxdsm.html

JS:   super.greet();
来源：http://dali.hnqzz.top/Article/details/gtbpljjrjx.html

TS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gtkjdsgsmz.html

Java: super.greet();
来源：http://dali.andypj.xyz/Article/details/gtikojywea.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.feifeiyinyue.top/Article/details/gtcngfomry.html

Ruby: super
来源：http://dali.sufxvd.cn/Article/details/gtzulfyhla.html

C#:   base.Greet();
来源：http://dali.ivvv.top/Article/details/gtltzpgsgl.html

[G08] 静态方法与属性
来源：http://dali.jyoumei.cn/Article/details/gtcfmzfmpo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hammf.cn/Article/details/gttimeoosz.html

PHP:  public static function f() {}
来源：http://dali.yonumen.top/Article/details/gtapmvfqey.html

JS:   static f() {}
来源：http://dali.gzhubu.top/Article/details/gtnqqpsdny.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdcbfwujg.html

Java: static void f() {}
来源：http://dali.ydzc1.top/Article/details/gtwnrtyydb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.haohaochexian.top/Article/details/gtewmoobje.html

Ruby: def self.f; end
来源：http://dali.shangyingyoupin.top/Article/details/gtgawkxlvb.html

C#:   public static void F() {}
来源：http://dali.nwbrower.top/Article/details/gtudsiwtdd.html

[G09] 接口 / 抽象类
来源：http://dali.yuxming.cn/Article/details/gtveylktkz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzmfhplla.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hammf.cn/Article/details/gtirkmpjhz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gtehpbnmhp.html

TS:   interface Shape { area(): number; }
来源：http://dali.pycfn.com/Article/details/gtcefpckbk.html

Java: interface Shape { double area(); }
来源：http://dali.yangfankeji.com/Article/details/gtcttcirzc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.feifeiyinyue.top/Article/details/gtjuhrgcbm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangshuangyany.cn/Article/details/gthxowkfrn.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gtlizjlsrn.html

[G10] 访问控制
来源：http://dali.tianlin.xyz/Article/details/gtirapfvau.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258.top/Article/details/gtydoselkj.html

PHP:  public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtqkezplac.html

JS:   #private 字段；其余公开
来源：http://dali.yuxming.cn/Article/details/gtukilgnra.html

TS:   public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtzuzjuwpn.html

Java: public / protected / private / 默认包级
来源：http://dali.cashguo.top/Article/details/gttowkvhrb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jyoumei.cn/Article/details/gtixdvnggu.html

Ruby: public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gteshushqv.html

C#:   public / protected / private / internal
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdhxjtnz.html

[G11] getter / setter
来源：http://dali.xinyue.icu/Article/details/gtwaqieruk.html

Py:   @property 与 @x.setter
来源：http://dali.cqqwz.cn/Article/details/gtzhslgfwa.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gtxdgvvepb.html

JS:   get name() { return this._name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxmovqyj.html

TS:   get name(): string { return this._name; }
来源：http://dali.ivvv.top/Article/details/gtqefzcfah.html

Java: public String getName() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtkbmakwug.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gtsgtrexhw.html

Ruby: attr_accessor :name
来源：http://dali.tian-w.cn/Article/details/gtvsgbbmjf.html

C#:   public string Name { get; set; }
来源：http://dali.jqgfzy.top/Article/details/gtqqfxyrrn.html

[G12] 对象转字符串
来源：http://dali.wangdashe.top/Article/details/gtdxviugmz.html

Py:   def __str__(self): return self.name
来源：http://dali.hnqzz.top/Article/details/gtzlcoyagq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtolysgdwe.html

JS:   toString() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtlrxzuivf.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtrwxqoxbo.html

Java: @Override public String toString() { return name; }
来源：http://dali.shuidangran.top/Article/details/gtswxutnkj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtnomvhewx.html

Ruby: def to_s; @name; end
来源：http://dali.316326.xyz/Article/details/gtkvbavhaf.html

C#:   public override string ToString() => Name;
来源：http://dali.daxiang520.top/Article/details/gtzrcmagke.html

[G13] 判断对象类型
来源：http://dali.andypj.xyz/Article/details/gtclaskbjt.html

Py:   isinstance(u, User)
来源：http://dali.jqgfzy.top/Article/details/gtzifcntse.html

PHP:  $u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gteuucetii.html

JS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtgzfchnwf.html

TS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtnhctrcgh.html

Java: u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gttstjdzzk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.kuanghao11.cn/Article/details/gtfamvlcpo.html

Ruby: u.is_a?(User)
来源：http://dali.sweek.top/Article/details/gtkmfwvnpj.html

C#:   u is User
来源：http://dali.guannengcc.top/Article/details/gtzhwlsqpm.html

[G14] 数据类 / record
来源：http://dali.ppjwa.cn/Article/details/gtvnmufkkf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuetiantiany.cn/Article/details/gthtzuyvzl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hysaishi.cn/Article/details/gtamlhiktr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtepegfdff.html

TS:   type User = { name: string; age: number };
来源：http://dali.hywenlv.cn/Article/details/gtqveiupmw.html

Java: record User(String name, int age) {}
来源：http://dali.yangfankeji.com/Article/details/gtlhegiwan.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhongyouzk.top/Article/details/gtkixsbuhg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xinyue.icu/Article/details/gterehnthg.html

C#:   record User(string Name, int Age);
来源：http://dali.svipenyu.cn/Article/details/gttqdyqozh.html

[G15] 枚举
来源：http://dali.wangdashe.top/Article/details/gttvwqbqvi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhongyouzk.top/Article/details/gtlybnjqeg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cheryme.top/Article/details/gtpyxierlz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daria6918.cn/Article/details/gtsjczlpxb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gthbuycgtg.html

Java: enum Color { RED, GREEN }
来源：http://dali.xinyue.icu/Article/details/gttuhyiwdl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dashuyun.cn/Article/details/gtayvbchoc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gzhubu.top/Article/details/gtmcaegyde.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jyoumei.cn/Article/details/gtritfjnuj.html

[G16] 对象转数组 / 字典
来源：http://dali.hongshengwenyu.top/Article/details/gtvelglpei.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258888.top/Article/details/gtevrejvli.html

PHP:  get_object_vars($obj);
来源：http://dali.hammf.cn/Article/details/gtqtxwusba.html

JS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gtbotwmfgc.html

TS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtnycmcbcb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daxiang520.top/Article/details/gturhokpyg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zycfv.cn/Article/details/gtgwsjcmcp.html

Ruby: obj.instance_variables
来源：http://dali.chenjidiqi.icu/Article/details/gtviecdshr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.c1oappe.top/Article/details/gtjczijayp.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtgcerllzk.html

H. 异常与错误处理
来源：http://dali.ybcxt.top/Article/details/gttvnguphp.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtyfwlgtqp.html

[H01] try / catch 基础
来源：http://dali.ppjwa.cn/Article/details/gtyqglefsu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aizwys.cn/Article/details/gtbbbuocle.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbdmdias.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gtvfkcwijm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gtezkjbfgc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gogol.net.cn/Article/details/gtutmkioof.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.feifeiyinyue.top/Article/details/gtalcvtzlz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hywenlv.cn/Article/details/gtiqaildqr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yangfankeji.com/Article/details/gtzsezlybm.html

[H02] finally / ensure 收尾
来源：http://dali.kuanghao11.cn/Article/details/gtihhzhfrn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gogol.net.cn/Article/details/gtzhonzofv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtzuxtdekc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtojsvrshh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtzuuplthc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtpeztdxns.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ivvv.top/Article/details/gtnowcfpaf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cheryme.top/Article/details/gtogzusfzk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtsjmwdjgr.html

[H03] 主动抛出异常
来源：http://dali.chenjidiqi.icu/Article/details/gtfalnpefw.html

Py:   raise ValueError("错误信息")
来源：http://dali.jianghu66.top/Article/details/gtkqclbjza.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtecxehegw.html

JS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gterqbaoyi.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtgcjhcfwm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtztvyxyke.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cqqwz.cn/Article/details/gtnpqhitui.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnqzz.top/Article/details/gtlhemrnyc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gthymkxhuv.html

[H04] 自定义异常类型
来源：http://dali.ybcxt.top/Article/details/gtraadkfwa.html

Py:   class MyError(Exception): pass
来源：http://dali.tianlin.xyz/Article/details/gthqvtgkrm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gtqxyvgsxx.html

JS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gtowqgqaln.html

TS:   class MyError extends Error {}
来源：http://dali.yj20258888.top/Article/details/gtcmtmflwr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zycfv.cn/Article/details/gtfflqlawk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shzxlz.cn/Article/details/gttpywzwcj.html

Ruby: class MyError < StandardError; end
来源：http://dali.sysykeji.top/Article/details/gtyzcikboj.html

C#:   class MyException : Exception {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttomlkynl.html

[H05] 捕获特定类型
来源：http://dali.xylfe.cn/Article/details/gtcnccmanp.html

Py:   except ValueError as e:
来源：http://dali.sxryk.cn/Article/details/gtiwkfldux.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.316326.xyz/Article/details/gtcjzzuado.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gtttabbrmz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gtjxppoaiq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinqigufen.top/Article/details/gtamznwtdd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxuanxn.top/Article/details/gtizvwqeac.html

Ruby: rescue ArgumentError => e
来源：http://dali.haohaochexian.top/Article/details/gtpgfvtzql.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gogol.net.cn/Article/details/gtqrwqlwli.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nwbrower.top/Article/details/gtlmrodruk.html

Py:   value = d.get("k") or default
来源：http://dali.cashguo.top/Article/details/gtwvkgvpds.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.dashuyun.cn/Article/details/gtngwchmzz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.havefunace.top/Article/details/gtcuradfot.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.kuanghao11.cn/Article/details/gtafrgnqwp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tian-w.cn/Article/details/gtypuqucfi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.316326.xyz/Article/details/gtlwxwsqir.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dashuyun.cn/Article/details/gtcbwhwkzp.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmielxhj.html

[H07] 断言
来源：http://dali.aibaodan.cn/Article/details/gtdnzuyqzy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.dashuyun.cn/Article/details/gtjgwpypuv.html

PHP:  assert($x > 0);
来源：http://dali.fzhhl.top/Article/details/gtbfbomxon.html

JS:   console.assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtsehftorh.html

TS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gtlwxxsonk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhoulong.xyz/Article/details/gtgwcvaiuc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gaohongyu789.top/Article/details/gtxzcdmqqd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.meibo888.top/Article/details/gtvzrgsaku.html

C#:   Debug.Assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtsegkyhdn.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangshuangyany.cn/Article/details/gtslrmrcsa.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yvedp.cn/Article/details/gtnyyoulpb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ivvv.top/Article/details/gtatkyibqy.html


<!-- 参考信息 -->