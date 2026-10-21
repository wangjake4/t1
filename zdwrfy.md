代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.quarkkingdee.top/Article/details/gteovjyhwr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyxtasiyz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hnqzz.top/Article/details/gtxzwzwjun.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xuanzx.com/Article/details/gtsjqqjoxw.html

[F05] 判断文件或目录是否存在
来源：http://dali.tian-w.cn/Article/details/gtxnbmahbx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guowangkeji.top/Article/details/gthlduxffr.html

PHP:  file_exists("a.txt");
来源：http://dali.hammf.cn/Article/details/gtjpunkfpg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhwjxtdo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtrcpniybx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtbfarghgr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sxryk.cn/Article/details/gttzvjcvdi.html

Ruby: File.exist?("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtertbxdtt.html

C#:   File.Exists("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtmtftbkjm.html

[F06] 删除文件
来源：http://dali.wangshuangyany.cn/Article/details/gtdiljdpse.html

Py:   os.remove("a.txt")
来源：http://dali.tian-w.cn/Article/details/gttwgpzclz.html

PHP:  unlink("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtlkhyxswc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtdaxyffxm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtyslxzjxj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtncenxxuz.html

Go:   os.Remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtuuiqsomi.html

Ruby: File.delete("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtoupufabm.html

C#:   File.Delete("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gteoeozkmk.html

[F07] 创建目录（含多级）
来源：http://dali.smart0.xyz/Article/details/gtntjerrto.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nwbrower.top/Article/details/gtlmjgqspp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cheryme.top/Article/details/gtihzgtzss.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gtkbklowub.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gtqwvshths.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.daria6918.cn/Article/details/gtxiqjoeaz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyakpvbvx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ivvv.top/Article/details/gtsovofwnd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.316326.xyz/Article/details/gtjxaywryc.html

[F08] 遍历目录
来源：http://dali.xinyue.icu/Article/details/gtndonmtvt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xziqi.cn/Article/details/gtmjvsutim.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xziqi.cn/Article/details/gtivqxjgju.html

JS:   fs.readdirSync("dir")
来源：http://dali.0kj1m.cn/Article/details/gtmpjqaomz.html

TS:   fs.readdirSync("dir")
来源：http://dali.yuxming.cn/Article/details/gtqjvdgtxs.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj20258888.top/Article/details/gtxickpyqw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtdlwtokot.html

Ruby: Dir.children("dir")
来源：http://dali.guowangkeji.top/Article/details/gtufrugdjq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.9152youxi.cn/Article/details/gtnhhauuox.html

[F09] 获取文件大小
来源：http://dali.pycfn.com/Article/details/gtrkkqgnwr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtnavbuefp.html

PHP:  filesize("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtyizfbwmw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gtcfyxvjsz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbsjowup.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtsmdflyem.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guowangkeji.top/Article/details/gtqllfrfnn.html

Ruby: File.size("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtovyjdujp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pycfn.com/Article/details/gtnxvqiuwg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yueranfly.top/Article/details/gtnvrjvtic.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtdafpcnel.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtxkvhpenu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtakqvwlyc.html

TS:   path.extname("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtkylrepxp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.quarkkingdee.top/Article/details/gtuiuidogr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtdbquowgb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtkuvzlglr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtyiujwdwp.html

[F11] 复制与移动文件
来源：http://dali.wangdashe.top/Article/details/gtfgdygjkd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtazvtjyei.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yuanzhike.top/Article/details/gtxibephxh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtqmaseuvv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtqzrvpadq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gtpexosbmw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nwbrower.top/Article/details/gtsoqesgdm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtrwqjuiks.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnxiangtu.top/Article/details/gtahruqjyx.html

[F12] CSV 读写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnonagqc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnvicczyi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cucudq.cn/Article/details/gtmlhjfyzb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gogol.net.cn/Article/details/gtwzdgflnr.html

TS:   // 同上
来源：http://dali.fengsongda.top/Article/details/gtckfhghgl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yanxiufei.cn/Article/details/gtbfpjuknb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cheryme.top/Article/details/gtncdfytfz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.quarkkingdee.top/Article/details/gtacgaojmu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xziqi.cn/Article/details/gteuzkvmod.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gteiwgnpul.html

G. 面向对象
来源：http://dali.wangshuangyany.cn/Article/details/gtlxbvycpn.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtdvpuouoc.html

[G01] 定义类
来源：http://dali.cqqwz.cn/Article/details/gtjcldiuoy.html

Py:   class User: pass
来源：http://dali.aibaodan.cn/Article/details/gtwvoscthm.html

PHP:  class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtnnzdvqjb.html

JS:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gtafabtnjj.html

TS:   class User { name: string = ""; }
来源：http://dali.xuetiantiany.cn/Article/details/gtnxodwcck.html

Java: class User {}
来源：http://dali.redwolf501.top/Article/details/gtbesfnzku.html

Go:   type User struct { Name string }
来源：http://dali.xuanzx.com/Article/details/gthhcqcerq.html

Ruby: class User; end
来源：http://dali.0kj1m.cn/Article/details/gtnkepbvtq.html

C#:   class User {}
来源：http://dali.c1oappe.top/Article/details/gtaqubdxvp.html

[G02] 构造函数
来源：http://dali.yvedp.cn/Article/details/gtgcbvkadk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nanxuanxn.top/Article/details/gtwzmjkocq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sufxvd.cn/Article/details/gtjgoahllc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gtecjfjmpv.html

TS:   constructor(public name: string) {}
来源：http://dali.birdmap.top/Article/details/gtcgnsbhdm.html

Java: User(String name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gtvkjximde.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.c1oappe.top/Article/details/gthudjpsmz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ivvv.top/Article/details/gtwvvajwdp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenlongwang.top/Article/details/gtttyurmls.html

[G03] 实例属性
来源：http://dali.meibo888.top/Article/details/gtjtkxznop.html

Py:   self.name = "x"
来源：http://dali.quarkkingdee.top/Article/details/gtttewdksd.html

PHP:  public string $name = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtcgkwfuuo.html

JS:   this.name = "x";
来源：http://dali.sufxvd.cn/Article/details/gtukradvbf.html

TS:   name: string = "x";
来源：http://dali.zdqjudy.top/Article/details/gtiundvyoa.html

Java: private String name;
来源：http://dali.yj20258.top/Article/details/gtvrgvltjq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.guannengcc.top/Article/details/gtgtuldzyc.html

Ruby: @name = "x"
来源：http://dali.chenzaomai.com/Article/details/gtamzldzjb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.316326.xyz/Article/details/gtpnclqxwc.html

[G04] 定义方法
来源：http://dali.aibaodan.cn/Article/details/gtnjyuqtkw.html

Py:   def greet(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gtwdgxdfzq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtfxaiiiki.html

JS:   greet() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtrsbbqewp.html

TS:   greet(): string { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtkhkxctrp.html

Java: String greet() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtnecbjpug.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gtuexadsqr.html

Ruby: def greet; @name; end
来源：http://dali.nanxinkj.top/Article/details/gtpgnycubb.html

C#:   public string Greet() => Name;
来源：http://dali.cqqwz.cn/Article/details/gtfhuovlye.html

[G05] 继承
来源：http://dali.yueranfly.top/Article/details/gtkyjeoqbl.html

Py:   class Admin(User): pass
来源：http://dali.sufxvd.cn/Article/details/gtvjzexcxd.html

PHP:  class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtojupsyny.html

JS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtpybufozj.html

TS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gteyoditys.html

Java: class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtskvcwkuo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jlsjyb.cn/Article/details/gtsnbatszr.html

Ruby: class Admin < User; end
来源：http://dali.meibo888.top/Article/details/gtwqgxfxih.html

C#:   class Admin : User {}
来源：http://dali.jianghu66.top/Article/details/gtnlgnbyqw.html

[G06] 重写方法
来源：http://dali.9152youxi.cn/Article/details/gtrirfenvw.html

Py:   def greet(self): return "admin"
来源：http://dali.redwolf501.top/Article/details/gtklparvkf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtyrrhepxm.html

JS:   greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtgyoqnzvg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtpxwbcxfj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtuhfxjgte.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvmnwatu.html

Ruby: def greet; "admin"; end
来源：http://dali.zhixingplan.top/Article/details/gtvdissmxr.html

C#:   public override string Greet() => "admin";
来源：http://dali.xinyue.icu/Article/details/gttphjigyj.html

[G07] 调用父类方法
来源：http://dali.hfpthk.cn/Article/details/gtsxynhamn.html

Py:   super().greet()
来源：http://dali.jqgfzy.top/Article/details/gtdmcbmict.html

PHP:  parent::greet();
来源：http://dali.yueranfly.top/Article/details/gtaztwxddp.html

JS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gtzyvlmupo.html

TS:   super.greet();
来源：http://dali.daxiang520.top/Article/details/gtmkakdwjw.html

Java: super.greet();
来源：http://dali.guannengcc.top/Article/details/gthyqznfwr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daria6918.cn/Article/details/gtuascctpq.html

Ruby: super
来源：http://dali.zhixingplan.top/Article/details/gtfdklgkpx.html

C#:   base.Greet();
来源：http://dali.zhengqikj.top/Article/details/gtyvmplwcp.html

[G08] 静态方法与属性
来源：http://dali.yj20258888.top/Article/details/gtpbsergfi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yvedp.cn/Article/details/gtxxcbfbeu.html

PHP:  public static function f() {}
来源：http://dali.cashguo.top/Article/details/gtmimzsgye.html

JS:   static f() {}
来源：http://dali.jinqigufen.top/Article/details/gtogtnhmqg.html

TS:   static f(): void {}
来源：http://dali.shangyingyoupin.top/Article/details/gtofckjucn.html

Java: static void f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtawkhwdmp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.feifeiyinyue.top/Article/details/gtamdnepol.html

Ruby: def self.f; end
来源：http://dali.zdqjudy.top/Article/details/gtnmakmyiq.html

C#:   public static void F() {}
来源：http://dali.ybcxt.top/Article/details/gtowarihsh.html

[G09] 接口 / 抽象类
来源：http://dali.tanke756.top/Article/details/gtxinikpdp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhixingplan.top/Article/details/gtitifnxlj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhongyouzk.top/Article/details/gtzmgrmaeh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.9152youxi.cn/Article/details/gtezcotdbq.html

TS:   interface Shape { area(): number; }
来源：http://dali.shangyingyoupin.top/Article/details/gtfbmetdki.html

Java: interface Shape { double area(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtwrmcipjq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yanxiufei.cn/Article/details/gtaszfqcyx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yonumen.top/Article/details/gtylymnywx.html

C#:   interface IShape { double Area(); }
来源：http://dali.shzxlz.cn/Article/details/gttxxvpdcp.html

[G10] 访问控制
来源：http://dali.sysykeji.top/Article/details/gtbllwfads.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenjidiqi.icu/Article/details/gtyqfjigop.html

PHP:  public / protected / private
来源：http://dali.jianghu66.top/Article/details/gtkshbwauh.html

JS:   #private 字段；其余公开
来源：http://dali.ppjwa.cn/Article/details/gtnbolwcsq.html

TS:   public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtencfwacx.html

Java: public / protected / private / 默认包级
来源：http://dali.tian-w.cn/Article/details/gtlrhmsygv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.snrcjt.cn/Article/details/gtgsneoyow.html

Ruby: public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gttchjmnvs.html

C#:   public / protected / private / internal
来源：http://dali.smart0.xyz/Article/details/gtttxzsrqe.html

[G11] getter / setter
来源：http://dali.hywenlv.cn/Article/details/gtesahfusq.html

Py:   @property 与 @x.setter
来源：http://dali.cqqwz.cn/Article/details/gtrlwqmqeu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtovjqevmb.html

JS:   get name() { return this._name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjdlexrck.html

TS:   get name(): string { return this._name; }
来源：http://dali.tianlin.xyz/Article/details/gtzbrebopi.html

Java: public String getName() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtddocdset.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gttngqhidg.html

Ruby: attr_accessor :name
来源：http://dali.zdqjudy.top/Article/details/gtoliyvhxf.html

C#:   public string Name { get; set; }
来源：http://dali.zhiwuduotai.top/Article/details/gtealxkuju.html

[G12] 对象转字符串
来源：http://dali.sweek.top/Article/details/gtrfltkkfh.html

Py:   def __str__(self): return self.name
来源：http://dali.shuidangran.top/Article/details/gtvmkctruy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gtdiwzahvh.html

JS:   toString() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtmgapfqhr.html

TS:   toString(): string { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtisehccpe.html

Java: @Override public String toString() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtkmrbdcnl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gtldkbhcau.html

Ruby: def to_s; @name; end
来源：http://dali.kuanghao11.cn/Article/details/gthspampfc.html

C#:   public override string ToString() => Name;
来源：http://dali.mhx1999.top/Article/details/gtnfjrpgcj.html

[G13] 判断对象类型
来源：http://dali.jyoumei.cn/Article/details/gtzvrumfcv.html

Py:   isinstance(u, User)
来源：http://dali.tanke756.top/Article/details/gtcgbbctid.html

PHP:  $u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtnlyyypdg.html

JS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtbbukoenr.html

TS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtwlyemqql.html

Java: u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtcthzlgfv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aibaodan.cn/Article/details/gtsejvewfl.html

Ruby: u.is_a?(User)
来源：http://dali.smart0.xyz/Article/details/gtqoegkuml.html

C#:   u is User
来源：http://dali.shzxlz.cn/Article/details/gtgatygvbq.html

[G14] 数据类 / record
来源：http://dali.ehwqpu.com/Article/details/gtkgforilv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ydzc1.top/Article/details/gtpripnhdv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuetiantiany.cn/Article/details/gtxfeylvza.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.c1oappe.top/Article/details/gtswekxqal.html

TS:   type User = { name: string; age: number };
来源：http://dali.0kj1m.cn/Article/details/gtmncizcfq.html

Java: record User(String name, int age) {}
来源：http://dali.9152youxi.cn/Article/details/gtbezkkhkc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.snrcjt.cn/Article/details/gtfwtxpxtm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.dianchejie.cn/Article/details/gtblavysxq.html

C#:   record User(string Name, int Age);
来源：http://dali.c1oappe.top/Article/details/gtvwlzjwhx.html

[G15] 枚举
来源：http://dali.yvedp.cn/Article/details/gtphxqwlse.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.haohaochexian.top/Article/details/gtfhcdjaym.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cheryme.top/Article/details/gtixjjpbco.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenjidiqi.icu/Article/details/gtjqgqkack.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gtklkvjevq.html

Java: enum Color { RED, GREEN }
来源：http://dali.smart0.xyz/Article/details/gtmzvqlbaa.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tianlin.xyz/Article/details/gtplvbnpcu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxuanxn.top/Article/details/gtleflmgww.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xylfe.cn/Article/details/gthavnseiy.html

[G16] 对象转数组 / 字典
来源：http://dali.zhixingplan.top/Article/details/gtmnzjzeqk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gogol.net.cn/Article/details/gtaumhwatq.html

PHP:  get_object_vars($obj);
来源：http://dali.jinghuilouyu.cn/Article/details/gtajggcrkb.html

JS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gtvzxpudvy.html

TS:   Object.entries(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtapazhqwv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xylfe.cn/Article/details/gtcjlvoycz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.birdmap.top/Article/details/gtnaoonjiz.html

Ruby: obj.instance_variables
来源：http://dali.gaohongyu789.top/Article/details/gtjugagogi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gtbsiqhzxs.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtolrsjbic.html

H. 异常与错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gtjzyamtur.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtwgpuuiyg.html

[H01] try / catch 基础
来源：http://dali.9152youxi.cn/Article/details/gtifyzgnnr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xziqi.cn/Article/details/gtntinyzkn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jiagoushi.top/Article/details/gtszlljrmw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gtlxjvusjg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gtzzaegnkj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cucudq.cn/Article/details/gtfvmfmjvp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenzaomai.com/Article/details/gttzrddhpr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shzxlz.cn/Article/details/gtxyryzedq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daria6918.cn/Article/details/gtgwxulqyy.html

[H02] finally / ensure 收尾
来源：http://dali.gaohongyu789.top/Article/details/gtwhozjscs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258888.top/Article/details/gtuekvatuh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtfgmupbiq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtwrzrdqoc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtvdlgdqdw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gthfmemgza.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.c1oappe.top/Article/details/gtdvtwxeje.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.andypj.xyz/Article/details/gtrsyunouk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtosbjpwyt.html

[H03] 主动抛出异常
来源：http://dali.jyoumei.cn/Article/details/gtymfcpuhk.html

Py:   raise ValueError("错误信息")
来源：http://dali.redwolf501.top/Article/details/gtsctvtkvj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtjgrntqyz.html

JS:   throw new Error("错误信息");
来源：http://dali.cashguo.top/Article/details/gtizsjmigl.html

TS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtixzyptiv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtioptkdko.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.bjfxy.top/Article/details/gtuzsiyfew.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dashuyun.cn/Article/details/gtxgkthwxh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtttwhuhok.html

[H04] 自定义异常类型
来源：http://dali.zhoulong.xyz/Article/details/gtulemoqup.html

Py:   class MyError(Exception): pass
来源：http://dali.cqqwz.cn/Article/details/gtfwdqjdke.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gtxajxxgyl.html

JS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gtijduoosg.html

TS:   class MyError extends Error {}
来源：http://dali.hongshengwenyu.top/Article/details/gtdbsndlnu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daxiang520.top/Article/details/gtxdtpcddd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hysaishi.cn/Article/details/gtshlqchhi.html

Ruby: class MyError < StandardError; end
来源：http://dali.316326.xyz/Article/details/gteqvozdnd.html

C#:   class MyException : Exception {}
来源：http://dali.gotoacloud.top/Article/details/gtlbctxwmp.html

[H05] 捕获特定类型
来源：http://dali.zycfv.cn/Article/details/gtrvlruqnq.html

Py:   except ValueError as e:
来源：http://dali.hnxiangtu.top/Article/details/gtqqfawvuj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.fzhhl.top/Article/details/gtygxdgdiq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xziqi.cn/Article/details/gtzuuomuxz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gtckvhrgdc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sysykeji.top/Article/details/gtghrmkoxh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hongshengwenyu.top/Article/details/gttlhpoeov.html

Ruby: rescue ArgumentError => e
来源：http://dali.9152youxi.cn/Article/details/gthutrgafl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.svipenyu.cn/Article/details/gtepuhekrt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xinyue.icu/Article/details/gtwpaxdlom.html

Py:   value = d.get("k") or default
来源：http://dali.snrcjt.cn/Article/details/gtvczzkrfg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yuanzhike.top/Article/details/gtrglgkvwk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ivvv.top/Article/details/gtlkqogdei.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tianlin.xyz/Article/details/gtuoxvllsv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cqqwz.cn/Article/details/gttcbfglqn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.vqdsnc.cn/Article/details/gtxzywxhdr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnqzz.top/Article/details/gttaiaxmfc.html

C#:   obj?.A?.B ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtklkrygpt.html

[H07] 断言
来源：http://dali.birdmap.top/Article/details/gtbahcgawa.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gtfngnthgw.html

PHP:  assert($x > 0);
来源：http://dali.jianghu66.top/Article/details/gtysdyqfzq.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtddbakbjl.html

TS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtrtxbudsk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yueranfly.top/Article/details/gtbvsjurgh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnxiangtu.top/Article/details/gthmjvgzeq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tianlin.xyz/Article/details/gtkdpwymzm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtmeslwnhs.html

[H08] 获取错误信息与堆栈
来源：http://dali.yueranfly.top/Article/details/gtxxdfqdgh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.redwolf501.top/Article/details/gtcfoamzmp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ehwqpu.com/Article/details/gtuqjskama.html

JS:   e.message;  e.stack
来源：http://dali.shangyingyoupin.top/Article/details/gtwoopfmzi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cheryme.top/Article/details/gtsjwcduwj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cucudq.cn/Article/details/gtqumrfgel.html

Go:   err.Error()
来源：http://dali.yongpay.top/Article/details/gtomryxyfq.html

Ruby: e.message;  e.backtrace
来源：http://dali.cheryme.top/Article/details/gtfzmkplym.html

C#:   e.Message;  e.StackTrace
来源：http://dali.c1oappe.top/Article/details/gtvaljbcgz.html

[H09] 带错误码的异常
来源：http://dali.feifeiyinyue.top/Article/details/gttsmmgahp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guannengcc.top/Article/details/gtylahbuww.html


<!-- 参考信息 -->