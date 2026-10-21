代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.fzhhl.top/Article/details/gtxfehbejg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jqgfzy.top/Article/details/gtjovxfpqa.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gthzkpnhnc.html

[F04] 追加写入文件
来源：http://dali.cdnleiting.top/Article/details/gtjxxnzmzj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.0kj1m.cn/Article/details/gtywjvbjkx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nanxuanxn.top/Article/details/gtknbiadqw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xziqi.cn/Article/details/gtrtaxngzx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gtcuqzcdjw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.0kj1m.cn/Article/details/gthudvuyzf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenlongwang.top/Article/details/gtyrrwswbw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenlongwang.top/Article/details/gtizwtxqph.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.dianchejie.cn/Article/details/gtlcucyabf.html

[F05] 判断文件或目录是否存在
来源：http://dali.guowangkeji.top/Article/details/gtqlwjvbtg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jiagoushi.top/Article/details/gtfqscxous.html

PHP:  file_exists("a.txt");
来源：http://dali.havefunace.top/Article/details/gtmtzdlcgc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdkxxkwn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtduzorkli.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gttgbkgsdi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangdashe.top/Article/details/gtctpxlqko.html

Ruby: File.exist?("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtzczpbxpb.html

C#:   File.Exists("a.txt")
来源：http://dali.tanke756.top/Article/details/gtwyzzaeya.html

[F06] 删除文件
来源：http://dali.hywenlv.cn/Article/details/gtzsjknxbd.html

Py:   os.remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtsncdtmqe.html

PHP:  unlink("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtrxdbjtge.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtxvzqmzks.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gthadqdavz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtnmxraaiu.html

Go:   os.Remove("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtwmvxmwiu.html

Ruby: File.delete("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtxwsxddpv.html

C#:   File.Delete("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtvuqijnsl.html

[F07] 创建目录（含多级）
来源：http://dali.gaohongyu789.top/Article/details/gtwxaspcbw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daxiang520.top/Article/details/gtsakxdwpy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xziqi.cn/Article/details/gtsogufqcy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.feifeiyinyue.top/Article/details/gtmkcbopvl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gogol.net.cn/Article/details/gtpbuoksjl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dashuyun.cn/Article/details/gtwyjsaepk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.wangdashe.top/Article/details/gtgcbzcjem.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gogol.net.cn/Article/details/gtrztykbaz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guowangkeji.top/Article/details/gtrkpgkpil.html

[F08] 遍历目录
来源：http://dali.cdnleiting.top/Article/details/gtlucxnewm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhiwuduotai.top/Article/details/gtpjbrfmdy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shuidangran.top/Article/details/gtpwlzbcyf.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gtpkgerfnh.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gtqewivmhg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.vqdsnc.cn/Article/details/gtgnzsidyq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yvedp.cn/Article/details/gtsavdmiov.html

Ruby: Dir.children("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtbygmaqbi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuxming.cn/Article/details/gtzgjnflhp.html

[F09] 获取文件大小
来源：http://dali.jyoumei.cn/Article/details/gtxawsmshy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbyqgbotf.html

PHP:  filesize("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtrazxqmzx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.c1oappe.top/Article/details/gtjyhrcdda.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yuanzhike.top/Article/details/gtaxevvfef.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gtfwqhkgji.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shanyushiyangtech.top/Article/details/gtecbcjdlo.html

Ruby: File.size("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtfnhxkhxu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hysaishi.cn/Article/details/gtaksbonfw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.meibo888.top/Article/details/gtirbkedpt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtqopedlfi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtgdbcytcs.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtmaevpdop.html

TS:   path.extname("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtfdxqphhl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hammf.cn/Article/details/gtcnbtcydl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtltkcpotm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtljeohwmt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtdobnlxgx.html

[F11] 复制与移动文件
来源：http://dali.gzhubu.top/Article/details/gttbiiivkd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtjypbsfur.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtjgsbrtnm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtafrjfzjt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtevgkgsqd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guannengcc.top/Article/details/gtjzazlpgs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.birdmap.top/Article/details/gtgagvgdqj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtlgqdsohp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yueranfly.top/Article/details/gtlwuogzlq.html

[F12] CSV 读写
来源：http://dali.snrcjt.cn/Article/details/gtafbvxnov.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nwbrower.top/Article/details/gtokrknlgl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangtech.top/Article/details/gttvtvkokz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.feifeiyinyue.top/Article/details/gtgmmzbgvy.html

TS:   // 同上
来源：http://dali.yuanzhike.top/Article/details/gtrhaedspg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dashuyun.cn/Article/details/gtaixaudiu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shuidangran.top/Article/details/gtqzopeuuj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.daria6918.cn/Article/details/gtqpgwfwhq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gotoacloud.top/Article/details/gtezqnkhyd.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gthnzwnkwe.html

G. 面向对象
来源：http://dali.fzhhl.top/Article/details/gtgxzrhelm.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gteovtmxku.html

[G01] 定义类
来源：http://dali.c1oappe.top/Article/details/gtftywbukn.html

Py:   class User: pass
来源：http://dali.gzhubu.top/Article/details/gtaxmqtkom.html

PHP:  class User {}
来源：http://dali.aizwys.cn/Article/details/gtkrhgqblw.html

JS:   class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtkmuvqtvg.html

TS:   class User { name: string = ""; }
来源：http://dali.sxryk.cn/Article/details/gthdrvlyrv.html

Java: class User {}
来源：http://dali.xylfe.cn/Article/details/gtyzfdmswx.html

Go:   type User struct { Name string }
来源：http://dali.hammf.cn/Article/details/gtcirgzfum.html

Ruby: class User; end
来源：http://dali.sysykeji.top/Article/details/gthuwqtszs.html

C#:   class User {}
来源：http://dali.sweek.top/Article/details/gtmcoxhdqy.html

[G02] 构造函数
来源：http://dali.daria6918.cn/Article/details/gttpifobuu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gogol.net.cn/Article/details/gtkvvgvqmu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.birdmap.top/Article/details/gtysgnnqkj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gtrsvsugbo.html

TS:   constructor(public name: string) {}
来源：http://dali.aizwys.cn/Article/details/gtpqeqoqol.html

Java: User(String name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gtayyokifx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zycfv.cn/Article/details/gtqkwbblzr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yongpay.top/Article/details/gtupfeguyz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqolyloyw.html

[G03] 实例属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtypicfxcn.html

Py:   self.name = "x"
来源：http://dali.gogol.net.cn/Article/details/gtufuleijp.html

PHP:  public string $name = "x";
来源：http://dali.pycfn.com/Article/details/gtprormnsu.html

JS:   this.name = "x";
来源：http://dali.ehwqpu.com/Article/details/gtgsofplpq.html

TS:   name: string = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtxgyloefn.html

Java: private String name;
来源：http://dali.wangdashe.top/Article/details/gtdoghryfx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.0kj1m.cn/Article/details/gtcbnflplj.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gtgkhdfedn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.c1oappe.top/Article/details/gtlwdceijo.html

[G04] 定义方法
来源：http://dali.hongshengwenyu.top/Article/details/gtgxyvlemu.html

Py:   def greet(self): return self.name
来源：http://dali.cucudq.cn/Article/details/gtmmlgmixw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtvsctcabp.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtmgghanlq.html

TS:   greet(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtdipncjye.html

Java: String greet() { return name; }
来源：http://dali.wangdashe.top/Article/details/gthfkwtfpo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gtmuigkloe.html

Ruby: def greet; @name; end
来源：http://dali.zhiwuduotai.top/Article/details/gtbzqjdtro.html

C#:   public string Greet() => Name;
来源：http://dali.316326.xyz/Article/details/gtmknujhxh.html

[G05] 继承
来源：http://dali.havefunace.top/Article/details/gtbxwnawbp.html

Py:   class Admin(User): pass
来源：http://dali.c1oappe.top/Article/details/gticpbbmql.html

PHP:  class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtzhxiquxr.html

JS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gthwcipsdl.html

TS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtltlvrntb.html

Java: class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtvhlyxewf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.daria6918.cn/Article/details/gtinmrozao.html

Ruby: class Admin < User; end
来源：http://dali.zdqjudy.top/Article/details/gtaeulcdhb.html

C#:   class Admin : User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajkqnrht.html

[G06] 重写方法
来源：http://dali.andypj.xyz/Article/details/gtezlmjkrs.html

Py:   def greet(self): return "admin"
来源：http://dali.dashuyun.cn/Article/details/gtsocbaqrt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtircrtiun.html

JS:   greet() { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gturfusqca.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtxgtpftey.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtjjfikrjm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ivvv.top/Article/details/gtpzjgrbmm.html

Ruby: def greet; "admin"; end
来源：http://dali.shangyingyoupin.top/Article/details/gtazvidyxa.html

C#:   public override string Greet() => "admin";
来源：http://dali.0kj1m.cn/Article/details/gtftvronyk.html

[G07] 调用父类方法
来源：http://dali.gaohongyu789.top/Article/details/gtdqqdswzr.html

Py:   super().greet()
来源：http://dali.zhengqikj.top/Article/details/gteguuwqjx.html

PHP:  parent::greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtuganafnd.html

JS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gtedgbzhjq.html

TS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gtuzkxhxaw.html

Java: super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtfpfpjlow.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.meibo888.top/Article/details/gtfcrdzhfn.html

Ruby: super
来源：http://dali.jinqigfzy.top/Article/details/gtciqsqwxz.html

C#:   base.Greet();
来源：http://dali.guannengcc.top/Article/details/gthzgwwwjv.html

[G08] 静态方法与属性
来源：http://dali.hysaishi.cn/Article/details/gtulrkliyi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hongshengwenyu.top/Article/details/gthaopmfqh.html

PHP:  public static function f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtfibyyjzb.html

JS:   static f() {}
来源：http://dali.dashuyun.cn/Article/details/gtwdteyumf.html

TS:   static f(): void {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwivbkyjt.html

Java: static void f() {}
来源：http://dali.redwolf501.top/Article/details/gtmdgvzxzd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gaohongyu789.top/Article/details/gtqebrifxq.html

Ruby: def self.f; end
来源：http://dali.xuetiantiany.cn/Article/details/gtzktinxgq.html

C#:   public static void F() {}
来源：http://dali.yonumen.top/Article/details/gtiolttebf.html

[G09] 接口 / 抽象类
来源：http://dali.yj20258888.top/Article/details/gtldxxxujh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangtech.top/Article/details/gtulgeogjn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgsmkdqjg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwbyaaczn.html

TS:   interface Shape { area(): number; }
来源：http://dali.pengpengdd.cyou/Article/details/gtncklipuh.html

Java: interface Shape { double area(); }
来源：http://dali.aibaodan.cn/Article/details/gtspshflfl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cheryme.top/Article/details/gtofnjmxvg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tian-w.cn/Article/details/gthyuopdmk.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtsmdidgso.html

[G10] 访问控制
来源：http://dali.birdmap.top/Article/details/gtboteponw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.mhx1999.top/Article/details/gtenmhwnne.html

PHP:  public / protected / private
来源：http://dali.redwolf501.top/Article/details/gtppwxbsqi.html

JS:   #private 字段；其余公开
来源：http://dali.ivvv.top/Article/details/gtdwxlfbsz.html

TS:   public / protected / private
来源：http://dali.fengsongda.top/Article/details/gtqpjqwixk.html

Java: public / protected / private / 默认包级
来源：http://dali.dianchejie.cn/Article/details/gtvjjgnekn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sufxvd.cn/Article/details/gtgsimqflt.html

Ruby: public / protected / private
来源：http://dali.ivvv.top/Article/details/gtbwuhjpwh.html

C#:   public / protected / private / internal
来源：http://dali.yangfankeji.com/Article/details/gtyilzupvt.html

[G11] getter / setter
来源：http://dali.yonumen.top/Article/details/gtnkbhqxfu.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258.top/Article/details/gtcvneqnlk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqynhpuqe.html

JS:   get name() { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gthwpkocqc.html

TS:   get name(): string { return this._name; }
来源：http://dali.hammf.cn/Article/details/gtsohcvmce.html

Java: public String getName() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtergxokpq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtntptuqoi.html

Ruby: attr_accessor :name
来源：http://dali.vqdsnc.cn/Article/details/gtneuvjmua.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258888.top/Article/details/gtkfwllvbc.html

[G12] 对象转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtxxygcozm.html

Py:   def __str__(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gtyxtandmm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtkgpkvshk.html

JS:   toString() { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtbjvepzjo.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbzswjcn.html

Java: @Override public String toString() { return name; }
来源：http://dali.ivvv.top/Article/details/gtoghyuejt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gtgqjmajym.html

Ruby: def to_s; @name; end
来源：http://dali.xuanzx.com/Article/details/gtdelwiutj.html

C#:   public override string ToString() => Name;
来源：http://dali.yonumen.top/Article/details/gtmfkricye.html

[G13] 判断对象类型
来源：http://dali.0kj1m.cn/Article/details/gtuadaifxc.html

Py:   isinstance(u, User)
来源：http://dali.andypj.xyz/Article/details/gtaexbvbtz.html

PHP:  $u instanceof User
来源：http://dali.316326.xyz/Article/details/gtymbjfyxq.html

JS:   u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtekagtceh.html

TS:   u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtwqcknjay.html

Java: u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gtwxijboyi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.svipenyu.cn/Article/details/gtsxlqpclc.html

Ruby: u.is_a?(User)
来源：http://dali.hnqzz.top/Article/details/gtsixmlonl.html

C#:   u is User
来源：http://dali.sufxvd.cn/Article/details/gtgkpeviri.html

[G14] 数据类 / record
来源：http://dali.ydzc1.top/Article/details/gtxbdxxjde.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgfzy.top/Article/details/gtxqdiyguf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shangyingyoupin.top/Article/details/gtqxftvfww.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinqigufen.top/Article/details/gtviakxbov.html

TS:   type User = { name: string; age: number };
来源：http://dali.nanxinkj.top/Article/details/gtskjdcdfa.html

Java: record User(String name, int age) {}
来源：http://dali.cheryme.top/Article/details/gtfixibcpu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangdashe.top/Article/details/gtgvciubxv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.c1oappe.top/Article/details/gtpuytoxpx.html

C#:   record User(string Name, int Age);
来源：http://dali.yueranfly.top/Article/details/gtkiwjvzyl.html

[G15] 枚举
来源：http://dali.jlsjyb.cn/Article/details/gtgewdyqlw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shzxlz.cn/Article/details/gtvlmqeulu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gotoacloud.top/Article/details/gtmsptldmg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.0kj1m.cn/Article/details/gtofglxqhq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shzxlz.cn/Article/details/gtuzqimmri.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuxming.cn/Article/details/gtfgrhhneb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xziqi.cn/Article/details/gtmfvshrim.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgfzy.top/Article/details/gtfihkkhyy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shzxlz.cn/Article/details/gtuzijqbip.html

[G16] 对象转数组 / 字典
来源：http://dali.tian-w.cn/Article/details/gtvzsfgjcc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aizwys.cn/Article/details/gtnuvfbacx.html

PHP:  get_object_vars($obj);
来源：http://dali.yanxiufei.cn/Article/details/gtnbkdztzb.html

JS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gtvoluhokm.html

TS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gtkrdzcokk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmokkckee.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.snrcjt.cn/Article/details/gtjoywfvbz.html

Ruby: obj.instance_variables
来源：http://dali.sufxvd.cn/Article/details/gtbebvvtyk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gtscdrwhsp.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtybymplzx.html

H. 异常与错误处理
来源：http://dali.shuidangran.top/Article/details/gtmggsiygf.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtydolwybp.html

[H01] try / catch 基础
来源：http://dali.xylfe.cn/Article/details/gtlnarkqso.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sysykeji.top/Article/details/gtfhthijvh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangdashe.top/Article/details/gtfygmkmew.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gttymlewnr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cdnleiting.top/Article/details/gtrwpnhppk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtziarkgio.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ppjwa.cn/Article/details/gtkbkvnbrl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aibaodan.cn/Article/details/gtyurunsea.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shzxlz.cn/Article/details/gtybiudsjh.html

[H02] finally / ensure 收尾
来源：http://dali.316326.xyz/Article/details/gtmnxspitf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nwbrower.top/Article/details/gtgvbytrnq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtlmienres.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtytueesha.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtwkazspzv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gttseezamp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigufen.top/Article/details/gtrmlnqdat.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xylfe.cn/Article/details/gttzehyyxv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtvrwzkbga.html

[H03] 主动抛出异常
来源：http://dali.dashuyun.cn/Article/details/gtbgcmbspp.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzggskwu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtjzlbhtsm.html

JS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtibrojsgd.html

TS:   throw new Error("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtdglllwby.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtvuqawuqr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenlongwang.top/Article/details/gtwraezpzm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.mhx1999.top/Article/details/gtghdhttti.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtzxiejudb.html

[H04] 自定义异常类型
来源：http://dali.fengsongda.top/Article/details/gtwlyqhhum.html

Py:   class MyError(Exception): pass
来源：http://dali.mhx1999.top/Article/details/gttwjttiyh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gtqfddtbpq.html

JS:   class MyError extends Error {}
来源：http://dali.dianchejie.cn/Article/details/gtfysqzavc.html

TS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gtisslzfxe.html

Java: class MyException extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gtrbmyuxbp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgufenzy.top/Article/details/gtampygwge.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmziqume.html

C#:   class MyException : Exception {}
来源：http://dali.vqdsnc.cn/Article/details/gtcmrffjfi.html

[H05] 捕获特定类型
来源：http://dali.aizwys.cn/Article/details/gteeawwbpi.html

Py:   except ValueError as e:
来源：http://dali.hnqzz.top/Article/details/gtbgdgfoty.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jlsjyb.cn/Article/details/gtdzqnzgzt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shuidangran.top/Article/details/gtobeipiea.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gtknnupdlr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtjskhbpev.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.fengsongda.top/Article/details/gtgowtwjse.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenlongwang.top/Article/details/gtplphppbv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sufxvd.cn/Article/details/gthrnjirtw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgufenzy.top/Article/details/gtspgxcyxg.html

Py:   value = d.get("k") or default
来源：http://dali.shanyushiyangtech.top/Article/details/gteajsochb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hfpthk.cn/Article/details/gteynhmzzu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gtvpnslqip.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gtwpskqcqh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzzmklrl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shangyingyoupin.top/Article/details/gtnclrwpxd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuanzx.com/Article/details/gtrrjgaoua.html

C#:   obj?.A?.B ?? default
来源：http://dali.vqdsnc.cn/Article/details/gtocawmoei.html

[H07] 断言
来源：http://dali.nwbrower.top/Article/details/gtnccyroge.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258888.top/Article/details/gtqciovuxz.html

PHP:  assert($x > 0);
来源：http://dali.gzhubu.top/Article/details/gtzznhspbo.html

JS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gthxqjqsky.html

TS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtsbvsfnwm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.birdmap.top/Article/details/gtaxngsobf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yuanzhike.top/Article/details/gtrayribjf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhoulong.xyz/Article/details/gtrwwrdala.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtpohahxgi.html

[H08] 获取错误信息与堆栈
来源：http://dali.yuanzhike.top/Article/details/gtghcsnawc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cucudq.cn/Article/details/gtohpollcv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cucudq.cn/Article/details/gtujtjblca.html


<!-- 参考信息 -->