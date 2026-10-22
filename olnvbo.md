代发 wailian999

C#:   File.ReadAllText("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtaotpqrvy.html

[F02] 逐行读取文件
来源：http://dali.wangdashe.top/Article/details/gtjlwluryi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tian-w.cn/Article/details/gtohlsodzv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hammf.cn/Article/details/gtvpcttlui.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gttuwwhlta.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gtsusbepvo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gtbbzjaiaz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hywenlv.cn/Article/details/gtojbqbpfp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.0kj1m.cn/Article/details/gtcajgikda.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nwbrower.top/Article/details/gtcmfpqjub.html

[F03] 写入文件（覆盖）
来源：http://dali.9152youxi.cn/Article/details/gtilhoymtx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj202588.top/Article/details/gtzupwgqvb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sxryk.cn/Article/details/gtcaeonlks.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zycfv.cn/Article/details/gtnonjclnl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gtnjavioxi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ybcxt.top/Article/details/gtlcepoooc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gzhubu.top/Article/details/gtfuhuquxv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.aibaodan.cn/Article/details/gtirdayswl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.316326.xyz/Article/details/gtscvkeuox.html

[F04] 追加写入文件
来源：http://dali.xylfe.cn/Article/details/gtawcarpkb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aizwys.cn/Article/details/gtfxtmxmbt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.mhx1999.top/Article/details/gthkpvvmyd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aizwys.cn/Article/details/gttlosjupj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.svipenyu.cn/Article/details/gtcrqmvdzb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhengqikj.top/Article/details/gtwckqbapr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtoblvphss.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.birdmap.top/Article/details/gtbngbexdj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.kuanghao11.cn/Article/details/gtrasdprza.html

[F05] 判断文件或目录是否存在
来源：http://dali.316326.xyz/Article/details/gtxegdflxp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwwegpsl.html

PHP:  file_exists("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtdjylikch.html

JS:   fs.existsSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtbvrdmsos.html

TS:   fs.existsSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gthiwitney.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtxudyicir.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.quarkkingdee.top/Article/details/gthlqysokv.html

Ruby: File.exist?("a.txt")
来源：http://dali.daria6918.cn/Article/details/gttbsxjdgc.html

C#:   File.Exists("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtkrefrjhh.html

[F06] 删除文件
来源：http://dali.hywenlv.cn/Article/details/gtawqctvpq.html

Py:   os.remove("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtpwusylhr.html

PHP:  unlink("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtrfderqcb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtpcgxujen.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtfnsjvpba.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gttinwsyva.html

Go:   os.Remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gtazfrdgyg.html

Ruby: File.delete("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtwnotgtan.html

C#:   File.Delete("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtoomcapgj.html

[F07] 创建目录（含多级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiodehzjj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ppjwa.cn/Article/details/gtaxyyjcoh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cqqwz.cn/Article/details/gticknmiyt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.vqdsnc.cn/Article/details/gtaxrmhani.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gogol.net.cn/Article/details/gtcgnuzupb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.vqdsnc.cn/Article/details/gtbbzrynxm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzommlse.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhengqikj.top/Article/details/gtzlhxsgiz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwypvchot.html

[F08] 遍历目录
来源：http://dali.zycfv.cn/Article/details/gtfszvbyur.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.iojbl.cn/Article/details/gtwjyescwh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.redwolf501.top/Article/details/gtqifjkhtf.html

JS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtogpbxzke.html

TS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtuhjoovqf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ppjwa.cn/Article/details/gtjyrrsokl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shzxlz.cn/Article/details/gthrxcjqgy.html

Ruby: Dir.children("dir")
来源：http://dali.yj202588.top/Article/details/gtzlajfwbt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sweek.top/Article/details/gttqjrbrrg.html

[F09] 获取文件大小
来源：http://dali.yvedp.cn/Article/details/gtxqmedtzf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtxlyozqvs.html

PHP:  filesize("a.txt");
来源：http://dali.cheryme.top/Article/details/gtwtwlbttd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhixingplan.top/Article/details/gtxaytcdrw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aizwys.cn/Article/details/gtchzeclii.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtbdjthqqf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.daxiang520.top/Article/details/gtimvjoryl.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtsfgthwoq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.daxiang520.top/Article/details/gtzmaovwdn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.daria6918.cn/Article/details/gtnosmccvb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtvkzpupfq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.daxiang520.top/Article/details/gtwlwgmwix.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtixkzokod.html

TS:   path.extname("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtxdqlxthl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhixingplan.top/Article/details/gtzfneagcg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtiolkcyyi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtanxqlsni.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtckuiwjwq.html

[F11] 复制与移动文件
来源：http://dali.zhongyouzk.top/Article/details/gtbliwaqjp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtijdtveei.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj20258.top/Article/details/gtoswmhhja.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtjtfaubvw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtqqxnkzoc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.meibo888.top/Article/details/gtjspzxvwk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guannengcc.top/Article/details/gtlrshdvjy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtugtaegrk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tian-w.cn/Article/details/gtnfvajlgo.html

[F12] CSV 读写
来源：http://dali.smart0.xyz/Article/details/gtvtyksccx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tanke756.top/Article/details/gtzjghwbsj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.dianchejie.cn/Article/details/gtvrynsncx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.haohaochexian.top/Article/details/gtihldrdbf.html

TS:   // 同上
来源：http://dali.guowangkeji.top/Article/details/gtfwrbutxu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangdashe.top/Article/details/gtyatjjooy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigfzy.top/Article/details/gtmojwlxaj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hongshengwenyu.top/Article/details/gttsggdtvi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuxming.cn/Article/details/gtrjvbspii.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtyrnyvsla.html

G. 面向对象
来源：http://dali.sweek.top/Article/details/gtpdulnexo.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtotdvmqxf.html

[G01] 定义类
来源：http://dali.nwbrower.top/Article/details/gtsvlvrmkm.html

Py:   class User: pass
来源：http://dali.bjfxy.top/Article/details/gtqbpvvwrv.html

PHP:  class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtjlxhkcef.html

JS:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gtfowwwonl.html

TS:   class User { name: string = ""; }
来源：http://dali.xylfe.cn/Article/details/gtsfmtzhqb.html

Java: class User {}
来源：http://dali.gotoacloud.top/Article/details/gtdsuqtdiv.html

Go:   type User struct { Name string }
来源：http://dali.yongpay.top/Article/details/gtdxlbbkwd.html

Ruby: class User; end
来源：http://dali.chenzaomai.com/Article/details/gtjipoelhf.html

C#:   class User {}
来源：http://dali.mhx1999.top/Article/details/gtobzthoqk.html

[G02] 构造函数
来源：http://dali.hysaishi.cn/Article/details/gtnfaavaxn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jqgufenzy.top/Article/details/gtxjgigdah.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hysaishi.cn/Article/details/gtackebkbt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtjjilcfws.html

TS:   constructor(public name: string) {}
来源：http://dali.fzhhl.top/Article/details/gtjlzyjwag.html

Java: User(String name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gtqajslpbg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shangyingyoupin.top/Article/details/gthhkuvdxa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.snrcjt.cn/Article/details/gtsaupihdt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxinkj.top/Article/details/gtacotqezo.html

[G03] 实例属性
来源：http://dali.zhongyouzk.top/Article/details/gttwvwahyh.html

Py:   self.name = "x"
来源：http://dali.yongpay.top/Article/details/gtoneeprcp.html

PHP:  public string $name = "x";
来源：http://dali.shzxlz.cn/Article/details/gtnsmypzco.html

JS:   this.name = "x";
来源：http://dali.cashguo.top/Article/details/gtvkunndpt.html

TS:   name: string = "x";
来源：http://dali.cashguo.top/Article/details/gtyjvscosi.html

Java: private String name;
来源：http://dali.hfpthk.cn/Article/details/gtngtjpgeq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.guowangkeji.top/Article/details/gtidyejqvi.html

Ruby: @name = "x"
来源：http://dali.ehwqpu.com/Article/details/gtezypyhtp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gttohkhwxt.html

[G04] 定义方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhoudvif.html

Py:   def greet(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gtizsvqjnl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gtgvjcdtad.html

JS:   greet() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gtruvqubkd.html

TS:   greet(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtohjeevln.html

Java: String greet() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtifipvapf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtpowvkjab.html

Ruby: def greet; @name; end
来源：http://dali.pycfn.com/Article/details/gtleqsioka.html

C#:   public string Greet() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gtlrnaowwf.html

[G05] 继承
来源：http://dali.hfpthk.cn/Article/details/gtpdlktioo.html

Py:   class Admin(User): pass
来源：http://dali.yvedp.cn/Article/details/gtmgvxzpfp.html

PHP:  class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwddkfje.html

JS:   class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gtqnxlorme.html

TS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtjpajvezo.html

Java: class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gthodihsvm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxiesjgt.html

Ruby: class Admin < User; end
来源：http://dali.nanxuanxn.top/Article/details/gtjabcehmg.html

C#:   class Admin : User {}
来源：http://dali.jiagoushi.top/Article/details/gtqfoomcja.html

[G06] 重写方法
来源：http://dali.vqdsnc.cn/Article/details/gtmskgylmx.html

Py:   def greet(self): return "admin"
来源：http://dali.sufxvd.cn/Article/details/gtxutqhipp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtyfudbime.html

JS:   greet() { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtkafskuga.html

TS:   greet(): string { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gthxcrwbwl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gttvgsnxjs.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhixingplan.top/Article/details/gtkhltadwg.html

Ruby: def greet; "admin"; end
来源：http://dali.hnxiangtu.top/Article/details/gtsyekdoth.html

C#:   public override string Greet() => "admin";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzckhupli.html

[G07] 调用父类方法
来源：http://dali.andypj.xyz/Article/details/gtfvamgguq.html

Py:   super().greet()
来源：http://dali.aibaodan.cn/Article/details/gtofxvuicd.html

PHP:  parent::greet();
来源：http://dali.guannengcc.top/Article/details/gtfbjmgufx.html

JS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gtvfwpuxmr.html

TS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gtdgbnqhrw.html

Java: super.greet();
来源：http://dali.iojbl.cn/Article/details/gtykcqqjjg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtywpzeiwp.html

Ruby: super
来源：http://dali.hongshengwenyu.top/Article/details/gtxpuipoql.html

C#:   base.Greet();
来源：http://dali.zhongyouzk.top/Article/details/gtqzsykwcb.html

[G08] 静态方法与属性
来源：http://dali.jqgufenzy.top/Article/details/gtqiiouecd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkascgqw.html

PHP:  public static function f() {}
来源：http://dali.jyoumei.cn/Article/details/gtorffiobv.html

JS:   static f() {}
来源：http://dali.fengsongda.top/Article/details/gtmkcsvjhq.html

TS:   static f(): void {}
来源：http://dali.zdqjudy.top/Article/details/gtelnvhzgc.html

Java: static void f() {}
来源：http://dali.jinqigfzy.top/Article/details/gtjzxmmltp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.pengpengdd.cyou/Article/details/gthdqxdvtw.html

Ruby: def self.f; end
来源：http://dali.hywenlv.cn/Article/details/gtwqcjvkvp.html

C#:   public static void F() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtibdlaqkh.html

[G09] 接口 / 抽象类
来源：http://dali.zdqjudy.top/Article/details/gtsqofrlkp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgfzy.top/Article/details/gtrldziist.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.meibo888.top/Article/details/gtetddfxjf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.dashuyun.cn/Article/details/gtttzpgqlo.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenjidiqi.icu/Article/details/gtfhatnrwo.html

Java: interface Shape { double area(); }
来源：http://dali.xziqi.cn/Article/details/gtekjepyxo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yueranfly.top/Article/details/gtmgislkcc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xinyue.icu/Article/details/gtiyfoobke.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenzaomai.com/Article/details/gtyvndvcxc.html

[G10] 访问控制
来源：http://dali.jinqigufen.top/Article/details/gtmxyqkzuy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zycfv.cn/Article/details/gtqazlwcxk.html

PHP:  public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gtadwerwkc.html

JS:   #private 字段；其余公开
来源：http://dali.mhx1999.top/Article/details/gtbbszrvvm.html

TS:   public / protected / private
来源：http://dali.wangdashe.top/Article/details/gtcaclakft.html

Java: public / protected / private / 默认包级
来源：http://dali.jqgufenzy.top/Article/details/gtxslhgtan.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cashguo.top/Article/details/gtnqnsthyy.html

Ruby: public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gtjtlbrhtl.html

C#:   public / protected / private / internal
来源：http://dali.feifeiyinyue.top/Article/details/gtxzvvxlfs.html

[G11] getter / setter
来源：http://dali.pycfn.com/Article/details/gtnkyeuicq.html

Py:   @property 与 @x.setter
来源：http://dali.chenjidiqi.icu/Article/details/gtggfxwixo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlyetfjjh.html

JS:   get name() { return this._name; }
来源：http://dali.iojbl.cn/Article/details/gtqkfzzwwh.html

TS:   get name(): string { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gtayqgurgk.html

Java: public String getName() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcnhoegdr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gtlxwoackj.html

Ruby: attr_accessor :name
来源：http://dali.yuxming.cn/Article/details/gtuljxgant.html

C#:   public string Name { get; set; }
来源：http://dali.smart0.xyz/Article/details/gtajgscptk.html

[G12] 对象转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjsiyozdq.html

Py:   def __str__(self): return self.name
来源：http://dali.xziqi.cn/Article/details/gtlbuoevjd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gtfzvmuaoq.html

JS:   toString() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtrgjzulds.html

TS:   toString(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gterixczkt.html

Java: @Override public String toString() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtgcydadet.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gtotzwpwig.html

Ruby: def to_s; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gtynytognp.html

C#:   public override string ToString() => Name;
来源：http://dali.snrcjt.cn/Article/details/gtigvwdjnd.html

[G13] 判断对象类型
来源：http://dali.gogol.net.cn/Article/details/gtutticyuc.html

Py:   isinstance(u, User)
来源：http://dali.wangshuangyany.cn/Article/details/gtjlzxkrwo.html

PHP:  $u instanceof User
来源：http://dali.hnqzz.top/Article/details/gthsjahevi.html

JS:   u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtirlskbyd.html

TS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtisufdrth.html

Java: u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtoszynlqo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yangfankeji.com/Article/details/gtcsjqhjmx.html

Ruby: u.is_a?(User)
来源：http://dali.shangyingyoupin.top/Article/details/gtgqjfrpqp.html

C#:   u is User
来源：http://dali.jinqigfzy.top/Article/details/gtbucdupfo.html

[G14] 数据类 / record
来源：http://dali.yj202588.top/Article/details/gtbmotoqxc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenlongwang.top/Article/details/gtehmboqjf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.smart0.xyz/Article/details/gtospddfqi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvuydtymv.html

TS:   type User = { name: string; age: number };
来源：http://dali.cqqwz.cn/Article/details/gtkfksnhpg.html

Java: record User(String name, int age) {}
来源：http://dali.sufxvd.cn/Article/details/gtpkujcjfp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hammf.cn/Article/details/gtsouysuva.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shuidangran.top/Article/details/gtlmtgtqvy.html

C#:   record User(string Name, int Age);
来源：http://dali.chenlongwang.top/Article/details/gtozbcrthp.html

[G15] 枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtiwpkvija.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqewprqhv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.dashuyun.cn/Article/details/gtidgjnxry.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258.top/Article/details/gthauvutyv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gtfqgaieik.html

Java: enum Color { RED, GREEN }
来源：http://dali.9152youxi.cn/Article/details/gtagcfdakv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cdnleiting.top/Article/details/gtrrpccvsv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aizwys.cn/Article/details/gtcflzxgpz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gterxyuibw.html

[G16] 对象转数组 / 字典
来源：http://dali.zhongyouzk.top/Article/details/gtouzvzhjw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sxryk.cn/Article/details/gtqxoxlnrj.html

PHP:  get_object_vars($obj);
来源：http://dali.shzxlz.cn/Article/details/gtdpqcqfoh.html

JS:   Object.entries(obj)
来源：http://dali.sweek.top/Article/details/gtqymzzidp.html

TS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gtofevhwsy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgufenzy.top/Article/details/gtbrktivxi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnubeqpux.html

Ruby: obj.instance_variables
来源：http://dali.fengsongda.top/Article/details/gtxlrstpbr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gtyiyjtypj.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtcerpvxbj.html

H. 异常与错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gtmcgkrwqi.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtmxyawryh.html

[H01] try / catch 基础
来源：http://dali.kuanghao11.cn/Article/details/gtmohnoqvf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.bjfxy.top/Article/details/gtsefelkwp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zdqjudy.top/Article/details/gtayugzrmo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtaovtdnjj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gtvjmzrvld.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.redwolf501.top/Article/details/gtpxceonlb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gogol.net.cn/Article/details/gthqpesllw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtslzihwtq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tian-w.cn/Article/details/gtprmnxpxy.html

[H02] finally / ensure 收尾
来源：http://dali.daxiang520.top/Article/details/gthrehrfwe.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.aibaodan.cn/Article/details/gtnopmilci.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtduhoaucy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtxxaixtsx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtlaigyeex.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtyrrajvmf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yueranfly.top/Article/details/gtlhzqrejv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.iojbl.cn/Article/details/gtmcltoeda.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtbtnzpqtm.html

[H03] 主动抛出异常
来源：http://dali.zhixingplan.top/Article/details/gtkmlsojnw.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgfzy.top/Article/details/gtqocjflfm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgkaqgqmy.html

JS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtorzfvfhy.html

TS:   throw new Error("错误信息");
来源：http://dali.birdmap.top/Article/details/gtdzmfmypz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtxearuoas.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xziqi.cn/Article/details/gtdtxabumo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hysaishi.cn/Article/details/gtdbcaznwl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtvbmsviqt.html

[H04] 自定义异常类型
来源：http://dali.wangdashe.top/Article/details/gtroyxlerz.html

Py:   class MyError(Exception): pass
来源：http://dali.hammf.cn/Article/details/gtarydkxpw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dianchejie.cn/Article/details/gtkvcwbuqg.html

JS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gtctcqgpxz.html

TS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gtgkoonntu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aizwys.cn/Article/details/gtryxcugvv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sysykeji.top/Article/details/gtzmpymmai.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258888.top/Article/details/gtkwvnmdih.html

C#:   class MyException : Exception {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwopjgucu.html

[H05] 捕获特定类型
来源：http://dali.gzhubu.top/Article/details/gtkhnitheq.html

Py:   except ValueError as e:
来源：http://dali.sxryk.cn/Article/details/gtszlyebzt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.iojbl.cn/Article/details/gtkfkrqpmc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.meibo888.top/Article/details/gtaigdtgsp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gtwxdeprap.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tanke756.top/Article/details/gtrhjgqndo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gaohongyu789.top/Article/details/gtzbcatjto.html

Ruby: rescue ArgumentError => e
来源：http://dali.redwolf501.top/Article/details/gtugkddkrr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nanxuanxn.top/Article/details/gtkkfoyvon.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shuidangran.top/Article/details/gtswthptjo.html

Py:   value = d.get("k") or default
来源：http://dali.sufxvd.cn/Article/details/gtxetzcvlm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yuanzhike.top/Article/details/gtbcpmzuby.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gtcfevfvew.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gthyggftse.html


<!-- 参考信息 -->