代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.9152youxi.cn/Article/details/gtqgydgyxt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj202588.top/Article/details/gtuymgfdem.html

[F03] 写入文件（覆盖）
来源：http://dali.yuanzhike.top/Article/details/gtqzptzcwi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nwbrower.top/Article/details/gtqrhiyjle.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsmcxgptm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gtfsolrjqt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtoeuwhxfm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cashguo.top/Article/details/gttrvbrxrq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cheryme.top/Article/details/gttuidkbqr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.c1oappe.top/Article/details/gttjfxxjhf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yueranfly.top/Article/details/gtgpoixazb.html

[F04] 追加写入文件
来源：http://dali.dashuyun.cn/Article/details/gtxrfpenyn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sufxvd.cn/Article/details/gtsdmuraez.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gogol.net.cn/Article/details/gttsbtmbqq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gtsdpheyvv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hfpthk.cn/Article/details/gteoqsaiot.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.birdmap.top/Article/details/gthupwosup.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gotoacloud.top/Article/details/gtidmyjctq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.0kj1m.cn/Article/details/gtbuupenca.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinqigfzy.top/Article/details/gtxspqkeic.html

[F05] 判断文件或目录是否存在
来源：http://dali.svipenyu.cn/Article/details/gtxfvnchzq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtunykmump.html

PHP:  file_exists("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtrrcgdtxn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtbbhlpips.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtxhexkdrh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtmindtvou.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cqqwz.cn/Article/details/gtyegmsrtj.html

Ruby: File.exist?("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtngqromas.html

C#:   File.Exists("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtuyiprged.html

[F06] 删除文件
来源：http://dali.xinyue.icu/Article/details/gtlnqsxezg.html

Py:   os.remove("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtajbkdmjd.html

PHP:  unlink("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtrrzxhvry.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtejtuiszl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtvfewertz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gttbyybdzp.html

Go:   os.Remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtilsqbhii.html

Ruby: File.delete("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtgvxrtujl.html

C#:   File.Delete("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtbisoobzr.html

[F07] 创建目录（含多级）
来源：http://dali.zycfv.cn/Article/details/gtyrlmdjzg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.feifeiyinyue.top/Article/details/gtruerqjeo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.wangdashe.top/Article/details/gtgurfewyp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tianlin.xyz/Article/details/gtweyefdrq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.bjfxy.top/Article/details/gtpqeihvse.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hammf.cn/Article/details/gthlaedmri.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuetiantiany.cn/Article/details/gtgkntxtbr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiarojhjp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenjidiqi.icu/Article/details/gtfnltonqk.html

[F08] 遍历目录
来源：http://dali.wangshuangyany.cn/Article/details/gtxffdjqpn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj20258.top/Article/details/gtelkidsrw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pycfn.com/Article/details/gtqcserlus.html

JS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gtzuvcfxwx.html

TS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gttalrwncs.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gtdooujutw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ybcxt.top/Article/details/gtmjuhnnbp.html

Ruby: Dir.children("dir")
来源：http://dali.andypj.xyz/Article/details/gtozqgbxya.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zdqjudy.top/Article/details/gtzvnjzdva.html

[F09] 获取文件大小
来源：http://dali.0kj1m.cn/Article/details/gtxanaoslw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtcdwcgudm.html

PHP:  filesize("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtvcgonqup.html

JS:   fs.statSync("a.txt").size
来源：http://dali.redwolf501.top/Article/details/gtmqybteml.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvcibgfqm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gtimnigvrq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.svipenyu.cn/Article/details/gtwjvyliog.html

Ruby: File.size("a.txt")
来源：http://dali.hammf.cn/Article/details/gtufpubadu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shzxlz.cn/Article/details/gtcahoqamo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nwbrower.top/Article/details/gtvpigrfyq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtpivhzjyb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtejxxbfhx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtkgmnjitq.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtitwuegyl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ybcxt.top/Article/details/gtonnjytpr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtjgroazny.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtstlqtcoz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtwjgpwnao.html

[F11] 复制与移动文件
来源：http://dali.pengpengdd.cyou/Article/details/gtyuzvoyns.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtcmhlncfq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ppjwa.cn/Article/details/gtmjivwsuz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtehnkhxqs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtuarauopt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xziqi.cn/Article/details/gtftyryhoj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fengsongda.top/Article/details/gtaufddejc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtbceaiawr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.havefunace.top/Article/details/gtqsjdjdee.html

[F12] CSV 读写
来源：http://dali.xinyue.icu/Article/details/gtvmhzuffj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sysykeji.top/Article/details/gtcrsbiuox.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tianlin.xyz/Article/details/gtmjmsnqxl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gogol.net.cn/Article/details/gtiampgfix.html

TS:   // 同上
来源：http://dali.hnqzz.top/Article/details/gtoikpjxki.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xziqi.cn/Article/details/gtkexzdzvy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj202588.top/Article/details/gttprkifcj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zdqjudy.top/Article/details/gtwfzejdae.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nanxuanxn.top/Article/details/gtntakuffm.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtqxdphhkr.html

G. 面向对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmpfvkdk.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtdviyqqwi.html

[G01] 定义类
来源：http://dali.jianghu66.top/Article/details/gtlyxfwjkh.html

Py:   class User: pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbafpbiom.html

PHP:  class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtcyzwpmxg.html

JS:   class User {}
来源：http://dali.sxryk.cn/Article/details/gtrkiivzrd.html

TS:   class User { name: string = ""; }
来源：http://dali.xinyue.icu/Article/details/gtffwosauh.html

Java: class User {}
来源：http://dali.ehwqpu.com/Article/details/gtjdiweszj.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnpubwpkk.html

Ruby: class User; end
来源：http://dali.pengpengdd.cyou/Article/details/gtnagvfibr.html

C#:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gtcgeazmcy.html

[G02] 构造函数
来源：http://dali.c1oappe.top/Article/details/gtcboylucy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenjidiqi.icu/Article/details/gtvyqaoalb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.haohaochexian.top/Article/details/gtjklsdthe.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtefgmgwgr.html

TS:   constructor(public name: string) {}
来源：http://dali.tian-w.cn/Article/details/gtloawplgn.html

Java: User(String name) { this.name = name; }
来源：http://dali.cqqwz.cn/Article/details/gtbgwabops.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdwmkauzq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhoulong.xyz/Article/details/gticxrsapb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.iojbl.cn/Article/details/gtbdlwrfmu.html

[G03] 实例属性
来源：http://dali.jinqigfzy.top/Article/details/gtcbzrfkxv.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gtdhgxedif.html

PHP:  public string $name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtzrntuwed.html

JS:   this.name = "x";
来源：http://dali.hywenlv.cn/Article/details/gtfpbkxsws.html

TS:   name: string = "x";
来源：http://dali.sweek.top/Article/details/gtacuaujbp.html

Java: private String name;
来源：http://dali.cashguo.top/Article/details/gtgruaczfn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxgwsllr.html

Ruby: @name = "x"
来源：http://dali.zdqjudy.top/Article/details/gtvqcghour.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtgfcvrcqo.html

[G04] 定义方法
来源：http://dali.0kj1m.cn/Article/details/gtyqeonzsz.html

Py:   def greet(self): return self.name
来源：http://dali.cashguo.top/Article/details/gtiegehacb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gttorxevig.html

JS:   greet() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtcrhrcvge.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtxmvfzejb.html

Java: String greet() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtdifyjmjt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gttwkzzyqa.html

Ruby: def greet; @name; end
来源：http://dali.cdnleiting.top/Article/details/gtpdtiypzh.html

C#:   public string Greet() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdllwnfqo.html

[G05] 继承
来源：http://dali.0kj1m.cn/Article/details/gtjvnofjjk.html

Py:   class Admin(User): pass
来源：http://dali.yuxming.cn/Article/details/gtfycodqbe.html

PHP:  class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gthamoroxj.html

JS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtpqjvopsw.html

TS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtnikqohpj.html

Java: class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtxkizujjf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cqqwz.cn/Article/details/gtjfywxlwz.html

Ruby: class Admin < User; end
来源：http://dali.aizwys.cn/Article/details/gtzjboxlai.html

C#:   class Admin : User {}
来源：http://dali.chenlongwang.top/Article/details/gtengozvak.html

[G06] 重写方法
来源：http://dali.xylfe.cn/Article/details/gthvibkpnt.html

Py:   def greet(self): return "admin"
来源：http://dali.yongpay.top/Article/details/gtborvntuk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtbhtvhtqh.html

JS:   greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtlumpgpbw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gtbimponxn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gthqafnoqm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jianghu66.top/Article/details/gtxojfkeik.html

Ruby: def greet; "admin"; end
来源：http://dali.nanxinkj.top/Article/details/gtusjrfxza.html

C#:   public override string Greet() => "admin";
来源：http://dali.wangdashe.top/Article/details/gtsvshwckr.html

[G07] 调用父类方法
来源：http://dali.shzxlz.cn/Article/details/gtovxrrwia.html

Py:   super().greet()
来源：http://dali.tanke756.top/Article/details/gtjzyarloq.html

PHP:  parent::greet();
来源：http://dali.xinyue.icu/Article/details/gtwmerflpp.html

JS:   super.greet();
来源：http://dali.guowangkeji.top/Article/details/gtuxaxzssv.html

TS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gteuhbsmet.html

Java: super.greet();
来源：http://dali.hnqzz.top/Article/details/gtfytgchhi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hfpthk.cn/Article/details/gtmymawelm.html

Ruby: super
来源：http://dali.yanxiufei.cn/Article/details/gtcarnfjtl.html

C#:   base.Greet();
来源：http://dali.hfpthk.cn/Article/details/gthdrixwuv.html

[G08] 静态方法与属性
来源：http://dali.xuanzx.com/Article/details/gttgdffxmt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.9152youxi.cn/Article/details/gtzrporeqv.html

PHP:  public static function f() {}
来源：http://dali.ybcxt.top/Article/details/gtnwigdlos.html

JS:   static f() {}
来源：http://dali.guowangkeji.top/Article/details/gtrxhpaauq.html

TS:   static f(): void {}
来源：http://dali.jlsjyb.cn/Article/details/gtrocxywcw.html

Java: static void f() {}
来源：http://dali.yuxming.cn/Article/details/gtiugrwatq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hfpthk.cn/Article/details/gtrhrnnsyd.html

Ruby: def self.f; end
来源：http://dali.zhiwuduotai.top/Article/details/gtztltogmc.html

C#:   public static void F() {}
来源：http://dali.yueranfly.top/Article/details/gtpdlldekl.html

[G09] 接口 / 抽象类
来源：http://dali.gotoacloud.top/Article/details/gtrweqnfnj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xylfe.cn/Article/details/gtjtgjfhyn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.meibo888.top/Article/details/gtrbaplmfq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shzxlz.cn/Article/details/gtlghfnbxb.html

TS:   interface Shape { area(): number; }
来源：http://dali.guowangkeji.top/Article/details/gtasjzsghd.html

Java: interface Shape { double area(); }
来源：http://dali.yangfankeji.com/Article/details/gtrtxneivr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ivvv.top/Article/details/gtahcfpobr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenjidiqi.icu/Article/details/gtsdeobady.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlurkzila.html

[G10] 访问控制
来源：http://dali.xziqi.cn/Article/details/gtblptaref.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.0kj1m.cn/Article/details/gtnjkgckuj.html

PHP:  public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gtoljkmfoz.html

JS:   #private 字段；其余公开
来源：http://dali.iojbl.cn/Article/details/gtndemhxft.html

TS:   public / protected / private
来源：http://dali.316326.xyz/Article/details/gtdxxaoswv.html

Java: public / protected / private / 默认包级
来源：http://dali.nwbrower.top/Article/details/gtjnvgbjpb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenlongwang.top/Article/details/gtqbwcbszq.html

Ruby: public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gtlcsysemx.html

C#:   public / protected / private / internal
来源：http://dali.zhiwuduotai.top/Article/details/gtxpnmyqwl.html

[G11] getter / setter
来源：http://dali.hfpthk.cn/Article/details/gtwklwiryf.html

Py:   @property 与 @x.setter
来源：http://dali.shzxlz.cn/Article/details/gtelitvjrk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gtsnzomaru.html

JS:   get name() { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gtykrkypnb.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gtlksfspii.html

Java: public String getName() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtolkhbrrn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqkydjky.html

Ruby: attr_accessor :name
来源：http://dali.aibaodan.cn/Article/details/gtymptnwcn.html

C#:   public string Name { get; set; }
来源：http://dali.aibaodan.cn/Article/details/gtsgcloksl.html

[G12] 对象转字符串
来源：http://dali.yangfankeji.com/Article/details/gttpxzfoie.html

Py:   def __str__(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkllpjjtx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtvvnhriks.html

JS:   toString() { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtuqhzgnzs.html

TS:   toString(): string { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gtdoemjbnc.html

Java: @Override public String toString() { return name; }
来源：http://dali.ybcxt.top/Article/details/gtbzeksikk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtpwtylxxb.html

Ruby: def to_s; @name; end
来源：http://dali.yuanzhike.top/Article/details/gtytgebyhn.html

C#:   public override string ToString() => Name;
来源：http://dali.havefunace.top/Article/details/gtsckzdckh.html

[G13] 判断对象类型
来源：http://dali.ydzc1.top/Article/details/gtknpgfcle.html

Py:   isinstance(u, User)
来源：http://dali.aibaodan.cn/Article/details/gtfycmzbkt.html

PHP:  $u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtemtfpexg.html

JS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtwooofokv.html

TS:   u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtszarnepa.html

Java: u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtjjswmsoi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nwbrower.top/Article/details/gtiapnqwbp.html

Ruby: u.is_a?(User)
来源：http://dali.shzxlz.cn/Article/details/gthdtchqrb.html

C#:   u is User
来源：http://dali.pengpengdd.cyou/Article/details/gttkrddcav.html

[G14] 数据类 / record
来源：http://dali.zhongyouzk.top/Article/details/gtebynftkx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zycfv.cn/Article/details/gtoakbruhd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yanxiufei.cn/Article/details/gtaergpqfg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinqigfzy.top/Article/details/gtkthmneix.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenzaomai.com/Article/details/gtboabpptq.html

Java: record User(String name, int age) {}
来源：http://dali.yueranfly.top/Article/details/gteihhxybl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cucudq.cn/Article/details/gtyxoubzqi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.andypj.xyz/Article/details/gtytsomctv.html

C#:   record User(string Name, int Age);
来源：http://dali.pycfn.com/Article/details/gtjnjkfcqa.html

[G15] 枚举
来源：http://dali.yangfankeji.com/Article/details/gtjlbdtdqj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gtczdtynjb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.fzhhl.top/Article/details/gtflhuiznl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenjidiqi.icu/Article/details/gtpgfiblah.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.c1oappe.top/Article/details/gtfymzadpu.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj202588.top/Article/details/gtnekybsio.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenzaomai.com/Article/details/gtvsztcajz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.fzhhl.top/Article/details/gtsnhlowfu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shzxlz.cn/Article/details/gtcdpdsnyg.html

[G16] 对象转数组 / 字典
来源：http://dali.nanxuanxn.top/Article/details/gtvzhqhfsr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.redwolf501.top/Article/details/gtqifzwcos.html

PHP:  get_object_vars($obj);
来源：http://dali.tianlin.xyz/Article/details/gtqzxmjdas.html

JS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gtisexinho.html

TS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gttnhzlbot.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yonumen.top/Article/details/gtlskhhggo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.fengsongda.top/Article/details/gtsmuazbpm.html

Ruby: obj.instance_variables
来源：http://dali.haohaochexian.top/Article/details/gtvuxilswf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gtjstyhfkg.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtwfttwxvh.html

H. 异常与错误处理
来源：http://dali.quarkkingdee.top/Article/details/gttnjpakhv.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtbhafnokt.html

[H01] try / catch 基础
来源：http://dali.sweek.top/Article/details/gteuuraabk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zycfv.cn/Article/details/gtbzcpabui.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.mhx1999.top/Article/details/gtmlgggmpb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gtnzunfqed.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gtprygwzss.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258.top/Article/details/gtluryqern.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmpkbhqf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.iojbl.cn/Article/details/gtekxwtmnn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuanzx.com/Article/details/gtbkufcsuh.html

[H02] finally / ensure 收尾
来源：http://dali.9152youxi.cn/Article/details/gthcspmrzc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gogol.net.cn/Article/details/gtkwbwsbqz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtzclwhglh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtulmoscfz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttvwyjfre.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtuvnfzuyt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dashuyun.cn/Article/details/gtagblgmdc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jlsjyb.cn/Article/details/gtualobryp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtdrstnldv.html

[H03] 主动抛出异常
来源：http://dali.hnxiangtu.top/Article/details/gtytdjyewz.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevjvnfql.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtjyjoevlh.html

JS:   throw new Error("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gttqvaautw.html

TS:   throw new Error("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtmyafwvcs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtvixqvlxz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tian-w.cn/Article/details/gttzrngibc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.haohaochexian.top/Article/details/gtajbqkkqa.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtnshjuzhs.html

[H04] 自定义异常类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajzcxlpl.html

Py:   class MyError(Exception): pass
来源：http://dali.quarkkingdee.top/Article/details/gtkiyxeoac.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gthstzsnlk.html

JS:   class MyError extends Error {}
来源：http://dali.zhengqikj.top/Article/details/gtmipiryqm.html

TS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gtxotsaoub.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gtbsjexrch.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aibaodan.cn/Article/details/gthlkijino.html

Ruby: class MyError < StandardError; end
来源：http://dali.xylfe.cn/Article/details/gtrearmyzu.html

C#:   class MyException : Exception {}
来源：http://dali.cashguo.top/Article/details/gtphmsyodo.html

[H05] 捕获特定类型
来源：http://dali.shzxlz.cn/Article/details/gtigafiawj.html

Py:   except ValueError as e:
来源：http://dali.redwolf501.top/Article/details/gthpodnbei.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nanxuanxn.top/Article/details/gteltejqsi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.9152youxi.cn/Article/details/gtphuheexd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gtflbvelko.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.quarkkingdee.top/Article/details/gtwdafjbpc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.kuanghao11.cn/Article/details/gtjfmdptue.html

Ruby: rescue ArgumentError => e
来源：http://dali.yanxiufei.cn/Article/details/gtboihnssx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yangfankeji.com/Article/details/gtvywzsard.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cucudq.cn/Article/details/gtenmzxmbl.html

Py:   value = d.get("k") or default
来源：http://dali.sysykeji.top/Article/details/gtwkgnjkls.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gtbekriqxc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtukvxndag.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtokdowwfj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuxming.cn/Article/details/gtligmeyyv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cucudq.cn/Article/details/gtcemssjku.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrtutxhf.html

C#:   obj?.A?.B ?? default
来源：http://dali.fzhhl.top/Article/details/gtveypqlfg.html

[H07] 断言
来源：http://dali.iojbl.cn/Article/details/gtadigjdvj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwftlfdo.html

PHP:  assert($x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtbajdarsu.html

JS:   console.assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtmcnzmsla.html


<!-- 参考信息 -->