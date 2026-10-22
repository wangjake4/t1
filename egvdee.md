代发 wailian999

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnqzz.top/Article/details/gtfglldtvm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhengqikj.top/Article/details/gtraqkwfeh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenlongwang.top/Article/details/gtbysguwby.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gaohongyu789.top/Article/details/gtzzlzpnmn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sweek.top/Article/details/gtqdlctobz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hammf.cn/Article/details/gtbyaxsokb.html

[F03] 写入文件（覆盖）
来源：http://dali.jqgfzy.top/Article/details/gtkruxzdlb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ppjwa.cn/Article/details/gtjlrazgbt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gtkrvrqpkk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gtsbhsncqt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gtwyrjmtmw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.316326.xyz/Article/details/gtfbykimbx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gogol.net.cn/Article/details/gtyqtkzxwa.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guowangkeji.top/Article/details/gtupyynijn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gtgcyepbvg.html

[F04] 追加写入文件
来源：http://dali.ppjwa.cn/Article/details/gtsqncitnl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.dianchejie.cn/Article/details/gtfvcrduxs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj202588.top/Article/details/gtdytletbb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.mhx1999.top/Article/details/gtbppyubps.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigufen.top/Article/details/gteoqmvior.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nanxinkj.top/Article/details/gtdblxkywi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yonumen.top/Article/details/gtipprcxqm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dashuyun.cn/Article/details/gtcoosmmfc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yueranfly.top/Article/details/gtpobvwudn.html

[F05] 判断文件或目录是否存在
来源：http://dali.c1oappe.top/Article/details/gtxqxhekuc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cashguo.top/Article/details/gtqopqncud.html

PHP:  file_exists("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtnmaxvvvb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtfyxoimne.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtdfalwiyb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gtwcilvfdb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jiagoushi.top/Article/details/gtxtevmrhu.html

Ruby: File.exist?("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtmqzjgmxg.html

C#:   File.Exists("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtibqpnant.html

[F06] 删除文件
来源：http://dali.jinqigufen.top/Article/details/gturdgifbl.html

Py:   os.remove("a.txt")
来源：http://dali.yongpay.top/Article/details/gtnthdzgaa.html

PHP:  unlink("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtzhbfuseu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtfbfvgqya.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtrhnodlux.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtetwokstr.html

Go:   os.Remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gtzcranjib.html

Ruby: File.delete("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtxadnhzuc.html

C#:   File.Delete("a.txt");
来源：http://dali.hammf.cn/Article/details/gtcakmmahf.html

[F07] 创建目录（含多级）
来源：http://dali.iojbl.cn/Article/details/gtjbuqjcsr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhoulong.xyz/Article/details/gtczmgfeey.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cdnleiting.top/Article/details/gtufkgfnqx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuanzhike.top/Article/details/gtalqzmvzi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangdashe.top/Article/details/gtvnikyvhb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pycfn.com/Article/details/gtpkkjsqaq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.dashuyun.cn/Article/details/gtzojsqczf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhoulong.xyz/Article/details/gtlnahrhod.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jyoumei.cn/Article/details/gtexaxrbih.html

[F08] 遍历目录
来源：http://dali.yj20258.top/Article/details/gtgccdexsi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigfzy.top/Article/details/gtaiyajilf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.feifeiyinyue.top/Article/details/gtanvynrxo.html

JS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gtxolijilv.html

TS:   fs.readdirSync("dir")
来源：http://dali.sweek.top/Article/details/gtrxomughi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gtrejqhtki.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtmnwidfow.html

Ruby: Dir.children("dir")
来源：http://dali.xuanzx.com/Article/details/gttczeqnpq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xziqi.cn/Article/details/gtqmjgomnt.html

[F09] 获取文件大小
来源：http://dali.guowangkeji.top/Article/details/gtdsdzghzm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ivvv.top/Article/details/gtmcizeskb.html

PHP:  filesize("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtzcyruhnw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jianghu66.top/Article/details/gtithrqvob.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gtrglnvzbv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtsfqsfppy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.svipenyu.cn/Article/details/gtwdmxoenj.html

Ruby: File.size("a.txt")
来源：http://dali.yj20258.top/Article/details/gtkzsympqd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenlongwang.top/Article/details/gtseehwmwv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.guannengcc.top/Article/details/gtktuvfdpe.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtfcpnrkle.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xuanzx.com/Article/details/gtwamyoclz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtxoiiyyad.html

TS:   path.extname("a.txt")
来源：http://dali.sweek.top/Article/details/gtlggvopef.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cdnleiting.top/Article/details/gtxiuhsejx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtynmjwyrq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtvsvjford.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtpqzjxlki.html

[F11] 复制与移动文件
来源：http://dali.zycfv.cn/Article/details/gtmrmadtgb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtduerzdsi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinqigufen.top/Article/details/gtwijkvudo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtxjcljgvc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtbnrdkdjb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zdqjudy.top/Article/details/gtlwaaxdrb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.vqdsnc.cn/Article/details/gtcfcjyqua.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtljowatwd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.0kj1m.cn/Article/details/gttrsfnhvd.html

[F12] CSV 读写
来源：http://dali.chenjidiqi.icu/Article/details/gtjqqmjvlb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinghuilouyu.cn/Article/details/gtooqnlfrd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tianlin.xyz/Article/details/gtcpsxapzy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hammf.cn/Article/details/gtceccdkfk.html

TS:   // 同上
来源：http://dali.vqdsnc.cn/Article/details/gtcrcqflcl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cucudq.cn/Article/details/gtcqyjezbm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hammf.cn/Article/details/gtnvjzpkif.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuetiantiany.cn/Article/details/gtpzksipxg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nwbrower.top/Article/details/gtbhfuwroo.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtetzivjjl.html

G. 面向对象
来源：http://dali.havefunace.top/Article/details/gtczboszap.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtjdmszagk.html

[G01] 定义类
来源：http://dali.c1oappe.top/Article/details/gtrjpwsieb.html

Py:   class User: pass
来源：http://dali.nwbrower.top/Article/details/gtxqjlcyyn.html

PHP:  class User {}
来源：http://dali.jqgfzy.top/Article/details/gtvnmfukhg.html

JS:   class User {}
来源：http://dali.iojbl.cn/Article/details/gtnriyftzq.html

TS:   class User { name: string = ""; }
来源：http://dali.gaohongyu789.top/Article/details/gttejhavmf.html

Java: class User {}
来源：http://dali.yangfankeji.com/Article/details/gtgawgvpmd.html

Go:   type User struct { Name string }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhzmzfet.html

Ruby: class User; end
来源：http://dali.hysaishi.cn/Article/details/gteubdjofz.html

C#:   class User {}
来源：http://dali.ivvv.top/Article/details/gtklezhqvy.html

[G02] 构造函数
来源：http://dali.bjfxy.top/Article/details/gtksgunlfm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yanxiufei.cn/Article/details/gtlzumialb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnxiangtu.top/Article/details/gtkclgqfkb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtluierolq.html

TS:   constructor(public name: string) {}
来源：http://dali.daria6918.cn/Article/details/gtovogigpk.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gtqwaozmzl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.snrcjt.cn/Article/details/gtywhpnknr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangdashe.top/Article/details/gtjoijpmcv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtdhslwtpo.html

[G03] 实例属性
来源：http://dali.jiagoushi.top/Article/details/gtxakaowoi.html

Py:   self.name = "x"
来源：http://dali.shuidangran.top/Article/details/gtmopzdhdb.html

PHP:  public string $name = "x";
来源：http://dali.wangdashe.top/Article/details/gtfjxxrion.html

JS:   this.name = "x";
来源：http://dali.meibo888.top/Article/details/gthhzxyjcz.html

TS:   name: string = "x";
来源：http://dali.zycfv.cn/Article/details/gttqsuwfnd.html

Java: private String name;
来源：http://dali.9152youxi.cn/Article/details/gtlffllwxb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ivvv.top/Article/details/gtyzphcxfy.html

Ruby: @name = "x"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrpwofvaz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ppjwa.cn/Article/details/gtcwjwkzuf.html

[G04] 定义方法
来源：http://dali.daria6918.cn/Article/details/gtummgmutb.html

Py:   def greet(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gttwpwmqyd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtwwnfgroz.html

JS:   greet() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtyxegoyva.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtytbxeufh.html

Java: String greet() { return name; }
来源：http://dali.316326.xyz/Article/details/gtijobsqbo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gtfnzveoxe.html

Ruby: def greet; @name; end
来源：http://dali.dianchejie.cn/Article/details/gtghgxonrr.html

C#:   public string Greet() => Name;
来源：http://dali.yongpay.top/Article/details/gtpvestphs.html

[G05] 继承
来源：http://dali.yj20258888.top/Article/details/gtnqsmvncb.html

Py:   class Admin(User): pass
来源：http://dali.hammf.cn/Article/details/gtbqwvuwyy.html

PHP:  class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtzpylkzzt.html

JS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gtulnloljy.html

TS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtxydqpkyk.html

Java: class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtggnqhzak.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jyoumei.cn/Article/details/gthyrxiznp.html

Ruby: class Admin < User; end
来源：http://dali.bjfxy.top/Article/details/gtktfqlrqm.html

C#:   class Admin : User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtondvskdb.html

[G06] 重写方法
来源：http://dali.gzhubu.top/Article/details/gtpyrcyciq.html

Py:   def greet(self): return "admin"
来源：http://dali.zhixingplan.top/Article/details/gtukbynyiz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gtyztdxpfk.html

JS:   greet() { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gthdlsjjoo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfjnckuxe.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gtyqagaqkl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ehwqpu.com/Article/details/gthtqpbwvj.html

Ruby: def greet; "admin"; end
来源：http://dali.ybcxt.top/Article/details/gtybmeckkp.html

C#:   public override string Greet() => "admin";
来源：http://dali.316326.xyz/Article/details/gtxqpnmwzn.html

[G07] 调用父类方法
来源：http://dali.yuxming.cn/Article/details/gtropdxwff.html

Py:   super().greet()
来源：http://dali.vqdsnc.cn/Article/details/gtvucwceju.html

PHP:  parent::greet();
来源：http://dali.aizwys.cn/Article/details/gtwwnxscnu.html

JS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gtbjldxyib.html

TS:   super.greet();
来源：http://dali.birdmap.top/Article/details/gtxsizhssf.html

Java: super.greet();
来源：http://dali.cashguo.top/Article/details/gtozchqmwf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gogol.net.cn/Article/details/gtmvnjjbpb.html

Ruby: super
来源：http://dali.daria6918.cn/Article/details/gtfdjpfnnv.html

C#:   base.Greet();
来源：http://dali.yuxming.cn/Article/details/gtxtstvzma.html

[G08] 静态方法与属性
来源：http://dali.guowangkeji.top/Article/details/gtfzgntvzp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj20258888.top/Article/details/gttetulpdr.html

PHP:  public static function f() {}
来源：http://dali.quarkkingdee.top/Article/details/gtijplpdfq.html

JS:   static f() {}
来源：http://dali.xziqi.cn/Article/details/gtvsmkcayx.html

TS:   static f(): void {}
来源：http://dali.wangdashe.top/Article/details/gtduczwlcq.html

Java: static void f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtjtpgeies.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cheryme.top/Article/details/gtdpeadrpg.html

Ruby: def self.f; end
来源：http://dali.iojbl.cn/Article/details/gtfjhnuhhz.html

C#:   public static void F() {}
来源：http://dali.yj20258.top/Article/details/gtbxvooapu.html

[G09] 接口 / 抽象类
来源：http://dali.yj20258888.top/Article/details/gtwkcbhqjy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cdnleiting.top/Article/details/gtfzqcsdwx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hywenlv.cn/Article/details/gtojkfvhan.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hammf.cn/Article/details/gthalmhtlf.html

TS:   interface Shape { area(): number; }
来源：http://dali.xuanzx.com/Article/details/gtodnxjpth.html

Java: interface Shape { double area(); }
来源：http://dali.daxiang520.top/Article/details/gtstkjwtfc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tianlin.xyz/Article/details/gtadpyuvxg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tanke756.top/Article/details/gtfsecjyoo.html

C#:   interface IShape { double Area(); }
来源：http://dali.9152youxi.cn/Article/details/gtxobrikrd.html

[G10] 访问控制
来源：http://dali.jianghu66.top/Article/details/gthpbekvnk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtogxziyoy.html

PHP:  public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gtxkmgwvlj.html

JS:   #private 字段；其余公开
来源：http://dali.zhixingplan.top/Article/details/gtzkxdsqiq.html

TS:   public / protected / private
来源：http://dali.wangdashe.top/Article/details/gtbomyzlpc.html

Java: public / protected / private / 默认包级
来源：http://dali.jianghu66.top/Article/details/gtouvxnkio.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hfpthk.cn/Article/details/gtsnesozqm.html

Ruby: public / protected / private
来源：http://dali.shuidangran.top/Article/details/gtliktlvqx.html

C#:   public / protected / private / internal
来源：http://dali.tianlin.xyz/Article/details/gtktlefcwh.html

[G11] getter / setter
来源：http://dali.mhx1999.top/Article/details/gtczbqkkdd.html

Py:   @property 与 @x.setter
来源：http://dali.yongpay.top/Article/details/gtgtxbqfnh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtswptucnk.html

JS:   get name() { return this._name; }
来源：http://dali.tanke756.top/Article/details/gtdsaeixbw.html

TS:   get name(): string { return this._name; }
来源：http://dali.ehwqpu.com/Article/details/gtwyndjyas.html

Java: public String getName() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gttukfhddg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gtryijdxyj.html

Ruby: attr_accessor :name
来源：http://dali.cucudq.cn/Article/details/gtpexrcncv.html

C#:   public string Name { get; set; }
来源：http://dali.cdnleiting.top/Article/details/gtmlwbkkyv.html

[G12] 对象转字符串
来源：http://dali.yuxming.cn/Article/details/gtgueajggb.html

Py:   def __str__(self): return self.name
来源：http://dali.xuetiantiany.cn/Article/details/gtemnrtcmy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfyjovrkh.html

JS:   toString() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtttwpciqf.html

TS:   toString(): string { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gturrakgxz.html

Java: @Override public String toString() { return name; }
来源：http://dali.shuidangran.top/Article/details/gtfpmzsliu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gthyzskgwj.html

Ruby: def to_s; @name; end
来源：http://dali.hnqzz.top/Article/details/gtibgjjsqk.html

C#:   public override string ToString() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gtpvgtatym.html

[G13] 判断对象类型
来源：http://dali.ehwqpu.com/Article/details/gteonumizp.html

Py:   isinstance(u, User)
来源：http://dali.zhoulong.xyz/Article/details/gtvjoaimjo.html

PHP:  $u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtddwuxrcd.html

JS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtovikitax.html

TS:   u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gtkboxdflg.html

Java: u instanceof User
来源：http://dali.yj20258.top/Article/details/gtyqeoecwu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hnqzz.top/Article/details/gtiwwckwna.html

Ruby: u.is_a?(User)
来源：http://dali.zhixingplan.top/Article/details/gtwjramuuk.html

C#:   u is User
来源：http://dali.gzhubu.top/Article/details/gtroqqhkpa.html

[G14] 数据类 / record
来源：http://dali.kuanghao11.cn/Article/details/gtzczadoyo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.9152youxi.cn/Article/details/gttogpuqht.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.kuanghao11.cn/Article/details/gttcjfvaga.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nwbrower.top/Article/details/gtezarufmw.html

TS:   type User = { name: string; age: number };
来源：http://dali.ppjwa.cn/Article/details/gtoyebnrif.html

Java: record User(String name, int age) {}
来源：http://dali.ppjwa.cn/Article/details/gtzmsfuljr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgfzy.top/Article/details/gtvuiwfhor.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenzaomai.com/Article/details/gtkcwuylud.html

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangtech.top/Article/details/gtadlpngtu.html

[G15] 枚举
来源：http://dali.hnqzz.top/Article/details/gtimubiuny.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.havefunace.top/Article/details/gtbtwtpbdv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tianlin.xyz/Article/details/gtvpfkvsjm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ybcxt.top/Article/details/gtlgjoudze.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.0kj1m.cn/Article/details/gtqidjlxgt.html

Java: enum Color { RED, GREEN }
来源：http://dali.birdmap.top/Article/details/gtliorjkyz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ivvv.top/Article/details/gtjemwqkhq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj20258.top/Article/details/gtzejmnxyf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtotffdoxo.html

[G16] 对象转数组 / 字典
来源：http://dali.ydzc1.top/Article/details/gttwhccuoo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aizwys.cn/Article/details/gtqfxhcwhw.html

PHP:  get_object_vars($obj);
来源：http://dali.ybcxt.top/Article/details/gtmnwgmvse.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtgvztropx.html

TS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtffolynkx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tianlin.xyz/Article/details/gtmzcqwtpv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.fzhhl.top/Article/details/gthpxzwqhg.html

Ruby: obj.instance_variables
来源：http://dali.andypj.xyz/Article/details/gtpqxhhsuc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gtvvmwpnbm.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtyuwjbxmy.html

H. 异常与错误处理
来源：http://dali.birdmap.top/Article/details/gtjwcqirac.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtxfcnkjup.html

[H01] try / catch 基础
来源：http://dali.guannengcc.top/Article/details/gtpooeljvw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.vqdsnc.cn/Article/details/gtavsaivde.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sweek.top/Article/details/gtdrzxqbii.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gtmpxghblm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gttsqxlspl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.feifeiyinyue.top/Article/details/gtgrwldfia.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.smart0.xyz/Article/details/gthfzuozoh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shangyingyoupin.top/Article/details/gtyiyjnfvv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenlongwang.top/Article/details/gtelexwlyd.html

[H02] finally / ensure 收尾
来源：http://dali.haohaochexian.top/Article/details/gtuvnsousd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcythkydx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtottgiudb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtnuhidqaf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtnzfcqeav.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtpurwzcit.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.wangdashe.top/Article/details/gtuycfsqtq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhoulong.xyz/Article/details/gttwqqfiry.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtdcdkeeou.html

[H03] 主动抛出异常
来源：http://dali.ydzc1.top/Article/details/gtqitdiqik.html

Py:   raise ValueError("错误信息")
来源：http://dali.jyoumei.cn/Article/details/gtwebmrbxq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtoxmjgefo.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtzzdgnihl.html

TS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gtngfnyxsr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtwtjzvouy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtasqwhbyw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenlongwang.top/Article/details/gtvmatohpp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtqdrjvygr.html

[H04] 自定义异常类型
来源：http://dali.svipenyu.cn/Article/details/gtnnfjkxsj.html

Py:   class MyError(Exception): pass
来源：http://dali.wangshuangyany.cn/Article/details/gtqwfrjaar.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gtuyeohljr.html

JS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gtjtbcupwx.html

TS:   class MyError extends Error {}
来源：http://dali.0kj1m.cn/Article/details/gtfxllblwm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gtaixnodvm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cucudq.cn/Article/details/gtpvojqyhp.html

Ruby: class MyError < StandardError; end
来源：http://dali.pengpengdd.cyou/Article/details/gtohpjtajx.html

C#:   class MyException : Exception {}
来源：http://dali.daxiang520.top/Article/details/gtumutxfyg.html

[H05] 捕获特定类型
来源：http://dali.cdnleiting.top/Article/details/gtfveognxe.html

Py:   except ValueError as e:
来源：http://dali.yj202588.top/Article/details/gtbppfdsft.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuetiantiany.cn/Article/details/gtljlhtwme.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.birdmap.top/Article/details/gteqtvnlch.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gtjejkqgot.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.snrcjt.cn/Article/details/gtvezvjvef.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guannengcc.top/Article/details/gteojelsff.html

Ruby: rescue ArgumentError => e
来源：http://dali.mhx1999.top/Article/details/gtkbspnpuh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yanxiufei.cn/Article/details/gtnbrudtqz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.aibaodan.cn/Article/details/gtimbvoeah.html

Py:   value = d.get("k") or default
来源：http://dali.guannengcc.top/Article/details/gtyiielizt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cashguo.top/Article/details/gtfdvphkic.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cashguo.top/Article/details/gtftjxhyae.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gtramnwyzd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangdashe.top/Article/details/gtdxsyrmhb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.fengsongda.top/Article/details/gtsbrapsvq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.kuanghao11.cn/Article/details/gtyfummavp.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxinkj.top/Article/details/gtinayimvh.html


<!-- 参考信息 -->