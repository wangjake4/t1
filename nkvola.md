代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj20258.top/Article/details/gt2garlrvem.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gt2yevddwxb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinqigfzy.top/Article/details/gt2boglmsrt.html

Ruby: File.read("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2wxgtgafc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2xcuivfia.html

[F02] 逐行读取文件
来源：http://dali.tanke756.top/Article/details/gt2tpacrfxy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.wangshuangyany.cn/Article/details/gt2zswswiwr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj20258888.top/Article/details/gt2jtekfdin.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhengqikj.top/Article/details/gt2zgvoensf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhrcepd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gt2robetqgd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.316326.xyz/Article/details/gt2womyszxa.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ybcxt.top/Article/details/gt2nrzynbox.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinqigufen.top/Article/details/gt2xjkfecqf.html

[F03] 写入文件（覆盖）
来源：http://dali.shuidangran.top/Article/details/gt2bwfglugd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yanxiufei.cn/Article/details/gt2eutwnlmc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhixingplan.top/Article/details/gt2ntffehrk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tanke756.top/Article/details/gt2rgpwbmyl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gt2jgfazyxn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cheryme.top/Article/details/gt2lgwfpbcn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.guannengcc.top/Article/details/gt2vcwgxprd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shzxlz.cn/Article/details/gt2newtmzrg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xylfe.cn/Article/details/gt2qobivhvg.html

[F04] 追加写入文件
来源：http://dali.haohaochexian.top/Article/details/gt2wnokgxix.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhengqikj.top/Article/details/gt2fabycwcd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xinyue.icu/Article/details/gt2kugfocho.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2amoqaonl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.316326.xyz/Article/details/gt2gssgbium.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.dianchejie.cn/Article/details/gt2lkuwsnxk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hywenlv.cn/Article/details/gt2vnckqtkq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangdashe.top/Article/details/gt2rrukelay.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xuanzx.com/Article/details/gt2ygjbxrwu.html

[F05] 判断文件或目录是否存在
来源：http://dali.hywenlv.cn/Article/details/gt2fhgecjmv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.iojbl.cn/Article/details/gt2zacoezan.html

PHP:  file_exists("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2bkcqzkdu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2wtobbonx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2bgekamwh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2rsyteamm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangdashe.top/Article/details/gt2hhqykour.html

Ruby: File.exist?("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2yxjnufjm.html

C#:   File.Exists("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2xspmkqff.html

[F06] 删除文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gmolbnij.html

Py:   os.remove("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2hoayzdkc.html

PHP:  unlink("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2sgfxmaaw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2xqyteubr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2eymceraj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gt2uziwupct.html

Go:   os.Remove("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2domxhydy.html

Ruby: File.delete("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2sucyrviv.html

C#:   File.Delete("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2drlwqtpe.html

[F07] 创建目录（含多级）
来源：http://dali.mhx1999.top/Article/details/gt2aundsbek.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ivvv.top/Article/details/gt2cdyfbtxt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cucudq.cn/Article/details/gt2okruxthn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.snrcjt.cn/Article/details/gt2opdxdtge.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gt2wxkmrbjj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tanke756.top/Article/details/gt2ixzylykl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.mhx1999.top/Article/details/gt2bcjcotwn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gzhubu.top/Article/details/gt2pnbjpjdr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhengqikj.top/Article/details/gt2nucnqnbx.html

[F08] 遍历目录
来源：http://dali.xuetiantiany.cn/Article/details/gt2xjzxxaud.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenzaomai.com/Article/details/gt2doxixyoi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.svipenyu.cn/Article/details/gt2terjtbtk.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinqigufen.top/Article/details/gt2ptbthndm.html

TS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gt2poqlquzr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.daria6918.cn/Article/details/gt2tcfkjuot.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yuanzhike.top/Article/details/gt2gxxwkdvq.html

Ruby: Dir.children("dir")
来源：http://dali.dashuyun.cn/Article/details/gt2whjbjorf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhongyouzk.top/Article/details/gt2zfbhogxi.html

[F09] 获取文件大小
来源：http://dali.jyoumei.cn/Article/details/gt2fycqdwsr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2fxdjcfws.html

PHP:  filesize("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2agsvytmc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.haohaochexian.top/Article/details/gt2tokshxim.html

TS:   fs.statSync("a.txt").size
来源：http://dali.daria6918.cn/Article/details/gt2fgxdtqiy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qtzobdbq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ivvv.top/Article/details/gt2hyosupnv.html

Ruby: File.size("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2ybnwctbs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sufxvd.cn/Article/details/gt2rmqeerds.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.birdmap.top/Article/details/gt2nppcwyhb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2ggqyjeem.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.havefunace.top/Article/details/gt2iznkhqru.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2ninljgul.html

TS:   path.extname("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2wbyxzxjb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jyoumei.cn/Article/details/gt2otdxzohr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2qzfegzvv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gt2usiskwdk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2vfaqppmr.html

[F11] 复制与移动文件
来源：http://dali.316326.xyz/Article/details/gt2jdbkjabf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gt2auugxomg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2vanzpifc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gt2sumnkveo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gt2czevbykh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenlongwang.top/Article/details/gt2bslwtdxf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hfpthk.cn/Article/details/gt2ocnjdezq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gt2fhptpsvp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.c1oappe.top/Article/details/gt2nnoyaucb.html

[F12] CSV 读写
来源：http://dali.zhiwuduotai.top/Article/details/gt2bvdehpib.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jiliafjw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsqdnip.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.bjfxy.top/Article/details/gt2ipxeshui.html

TS:   // 同上
来源：http://dali.sxryk.cn/Article/details/gt2gnpnamtm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.haohaochexian.top/Article/details/gt2fqobhfsl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj20258888.top/Article/details/gt2xatjwgyg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigfzy.top/Article/details/gt2kjojigpq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rwtfkkgo.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2oriqebri.html

G. 面向对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fwgbqkfv.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kkkjzbvn.html

[G01] 定义类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bnbxjmco.html

Py:   class User: pass
来源：http://dali.sxryk.cn/Article/details/gt2ybgjfgqm.html

PHP:  class User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2bhgrdcwd.html

JS:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2juymolml.html

TS:   class User { name: string = ""; }
来源：http://dali.kuanghao11.cn/Article/details/gt2roiepecr.html

Java: class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2oftimbcd.html

Go:   type User struct { Name string }
来源：http://dali.nwbrower.top/Article/details/gt2lksygwmr.html

Ruby: class User; end
来源：http://dali.guannengcc.top/Article/details/gt2rphtidhm.html

C#:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2wxtgtyyx.html

[G02] 构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jdakxpfi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yanxiufei.cn/Article/details/gt2takjermi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.birdmap.top/Article/details/gt2xyncvzth.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.bjfxy.top/Article/details/gt2jysugtgy.html

TS:   constructor(public name: string) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ivsyorui.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gt2zimserao.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj20258.top/Article/details/gt2ybbhekyf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cheryme.top/Article/details/gt2layhrddn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.birdmap.top/Article/details/gt2vydazrzh.html

[G03] 实例属性
来源：http://dali.316326.xyz/Article/details/gt2idiajzyu.html

Py:   self.name = "x"
来源：http://dali.sxryk.cn/Article/details/gt2jvtpzand.html

PHP:  public string $name = "x";
来源：http://dali.yanxiufei.cn/Article/details/gt2blxkqgvg.html

JS:   this.name = "x";
来源：http://dali.316326.xyz/Article/details/gt2caezkudz.html

TS:   name: string = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rpyyttqx.html

Java: private String name;
来源：http://dali.hywenlv.cn/Article/details/gt2ficzjooh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangshuangyany.cn/Article/details/gt2brfaeovr.html

Ruby: @name = "x"
来源：http://dali.yj20258888.top/Article/details/gt2biclylpi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jlsjyb.cn/Article/details/gt2tdsareuz.html

[G04] 定义方法
来源：http://dali.pycfn.com/Article/details/gt2gcvcygfr.html

Py:   def greet(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gt2ioxhqhci.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gt2ivhbsbjg.html

JS:   greet() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gt2ktnetjtk.html

TS:   greet(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gt2hxclmerz.html

Java: String greet() { return name; }
来源：http://dali.xinyue.icu/Article/details/gt2ixmtxpjl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gt2lwfhwqia.html

Ruby: def greet; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gt2vqeomruq.html

C#:   public string Greet() => Name;
来源：http://dali.hfpthk.cn/Article/details/gt2mleqbync.html

[G05] 继承
来源：http://dali.yj20258888.top/Article/details/gt2hgyfzbjk.html

Py:   class Admin(User): pass
来源：http://dali.kuanghao11.cn/Article/details/gt2ucdqsnsf.html

PHP:  class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gt2eoqqaeft.html

JS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gt2trocynyj.html

TS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gt2ovunofmz.html

Java: class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gt2zqhcopye.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.feifeiyinyue.top/Article/details/gt2owowibmh.html

Ruby: class Admin < User; end
来源：http://dali.aibaodan.cn/Article/details/gt2twlcsdsw.html

C#:   class Admin : User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2jhlaqjzq.html

[G06] 重写方法
来源：http://dali.jianghu66.top/Article/details/gt2ehdqiwaw.html

Py:   def greet(self): return "admin"
来源：http://dali.jlsjyb.cn/Article/details/gt2mdaqsdgw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2arigrsmp.html

JS:   greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gt2kqeykxpf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gt2aqehbvtg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gt2oyehstjr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.svipenyu.cn/Article/details/gt2rvxkzycv.html

Ruby: def greet; "admin"; end
来源：http://dali.yonumen.top/Article/details/gt2snvdxpzl.html

C#:   public override string Greet() => "admin";
来源：http://dali.hammf.cn/Article/details/gt2nvisggqc.html

[G07] 调用父类方法
来源：http://dali.chenjidiqi.icu/Article/details/gt2iioercqt.html

Py:   super().greet()
来源：http://dali.jlsjyb.cn/Article/details/gt2atsfsnzz.html

PHP:  parent::greet();
来源：http://dali.iojbl.cn/Article/details/gt2ibxznovm.html

JS:   super.greet();
来源：http://dali.dashuyun.cn/Article/details/gt2lgyirpey.html

TS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gt2vaggzoil.html

Java: super.greet();
来源：http://dali.tian-w.cn/Article/details/gt2yqrqnrhi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.andypj.xyz/Article/details/gt2xmefpopb.html

Ruby: super
来源：http://dali.xziqi.cn/Article/details/gt2uudqmteq.html

C#:   base.Greet();
来源：http://dali.fzhhl.top/Article/details/gt2tqxbbasq.html

[G08] 静态方法与属性
来源：http://dali.xziqi.cn/Article/details/gt2lbngbhix.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.316326.xyz/Article/details/gt2vbklclbf.html

PHP:  public static function f() {}
来源：http://dali.yj202588.top/Article/details/gt2wyebjhyo.html

JS:   static f() {}
来源：http://dali.dashuyun.cn/Article/details/gt2yravpeet.html

TS:   static f(): void {}
来源：http://dali.wangdashe.top/Article/details/gt2dloftwrq.html

Java: static void f() {}
来源：http://dali.tanke756.top/Article/details/gt2trqvumed.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guannengcc.top/Article/details/gt2myqkjxzf.html

Ruby: def self.f; end
来源：http://dali.fengsongda.top/Article/details/gt2robozbnt.html

C#:   public static void F() {}
来源：http://dali.xziqi.cn/Article/details/gt2azdrqrts.html

[G09] 接口 / 抽象类
来源：http://dali.hongshengwenyu.top/Article/details/gt2dqzeaatq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hnqzz.top/Article/details/gt2eoiwrrcd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.redwolf501.top/Article/details/gt2huaizcih.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.mhx1999.top/Article/details/gt2szsvvqar.html

TS:   interface Shape { area(): number; }
来源：http://dali.andypj.xyz/Article/details/gt2qtradfxi.html

Java: interface Shape { double area(); }
来源：http://dali.yonumen.top/Article/details/gt2ehbcpdxx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hammf.cn/Article/details/gt2zwsvprie.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gogol.net.cn/Article/details/gt2bjhxlyio.html

C#:   interface IShape { double Area(); }
来源：http://dali.ivvv.top/Article/details/gt2sgjzfffs.html

[G10] 访问控制
来源：http://dali.9152youxi.cn/Article/details/gt2uukrilht.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yongpay.top/Article/details/gt2wjgghwap.html

PHP:  public / protected / private
来源：http://dali.yuxming.cn/Article/details/gt2doslxvjv.html

JS:   #private 字段；其余公开
来源：http://dali.smart0.xyz/Article/details/gt2syevgibf.html

TS:   public / protected / private
来源：http://dali.tanke756.top/Article/details/gt2eloxgcuv.html

Java: public / protected / private / 默认包级
来源：http://dali.yvedp.cn/Article/details/gt2fbiejydy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigfzy.top/Article/details/gt2gmkyxscp.html

Ruby: public / protected / private
来源：http://dali.hammf.cn/Article/details/gt2drnrstqk.html

C#:   public / protected / private / internal
来源：http://dali.gzhubu.top/Article/details/gt2qdeuausi.html

[G11] getter / setter
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xhmaxjrh.html

Py:   @property 与 @x.setter
来源：http://dali.hfpthk.cn/Article/details/gt2lcgthfeq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjxjidf.html

JS:   get name() { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gt2gnilyufj.html

TS:   get name(): string { return this._name; }
来源：http://dali.gogol.net.cn/Article/details/gt2adlqcpnk.html

Java: public String getName() { return name; }
来源：http://dali.yonumen.top/Article/details/gt2mcawhggi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gt2dhrhdyxw.html

Ruby: attr_accessor :name
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dpjkcxix.html

C#:   public string Name { get; set; }
来源：http://dali.hysaishi.cn/Article/details/gt2cphjckvw.html

[G12] 对象转字符串
来源：http://dali.yuxming.cn/Article/details/gt2klovhftr.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258.top/Article/details/gt2phqwazjd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2vrljbpzd.html

JS:   toString() { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gt2gwkyulwi.html

TS:   toString(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gt2uwvbutab.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2rrijilqp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gt2jeuxymed.html

Ruby: def to_s; @name; end
来源：http://dali.daria6918.cn/Article/details/gt2mrivuwgl.html

C#:   public override string ToString() => Name;
来源：http://dali.ybcxt.top/Article/details/gt2chqdflhk.html

[G13] 判断对象类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gphuhpjf.html

Py:   isinstance(u, User)
来源：http://dali.gzhubu.top/Article/details/gt2rzrjcnsz.html

PHP:  $u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gt2bbqgbkic.html

JS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2bbgwvqde.html

TS:   u instanceof User
来源：http://dali.sysykeji.top/Article/details/gt2ffozqgyt.html

Java: u instanceof User
来源：http://dali.smart0.xyz/Article/details/gt2cgnoqbec.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cucudq.cn/Article/details/gt2fspmjwhi.html

Ruby: u.is_a?(User)
来源：http://dali.yuanzhike.top/Article/details/gt2bskvtiym.html

C#:   u is User
来源：http://dali.haohaochexian.top/Article/details/gt2pkolchox.html

[G14] 数据类 / record
来源：http://dali.dashuyun.cn/Article/details/gt2zazqdlsp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dianchejie.cn/Article/details/gt2pphrpocq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jianghu66.top/Article/details/gt2jqxqlprl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhengqikj.top/Article/details/gt2xkgfurbi.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj202588.top/Article/details/gt2xcthpipo.html

Java: record User(String name, int age) {}
来源：http://dali.jqgfzy.top/Article/details/gt2rfsiqjjm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnqzz.top/Article/details/gt2idpcjniw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.aibaodan.cn/Article/details/gt2riucfzwt.html

C#:   record User(string Name, int Age);
来源：http://dali.zhengqikj.top/Article/details/gt2ewmrltmj.html

[G15] 枚举
来源：http://dali.ehwqpu.com/Article/details/gt2ttwrslxk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hammf.cn/Article/details/gt2liisdfap.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tanke756.top/Article/details/gt2odyxpcpm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.vqdsnc.cn/Article/details/gt2pdypogjn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2iizgexrl.html

Java: enum Color { RED, GREEN }
来源：http://dali.xinyue.icu/Article/details/gt2brkhsxzx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuanzhike.top/Article/details/gt2lnkdsjfu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.bjfxy.top/Article/details/gt2iddvvklh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ybuzetff.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bfqpxpzi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.316326.xyz/Article/details/gt2xfllsxwu.html

PHP:  get_object_vars($obj);
来源：http://dali.haohaochexian.top/Article/details/gt2wauhstwc.html

JS:   Object.entries(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2naaycazc.html

TS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lexsrsjc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gzhubu.top/Article/details/gt2nlurezuf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhiwuduotai.top/Article/details/gt2tkspryvf.html

Ruby: obj.instance_variables
来源：http://dali.fengsongda.top/Article/details/gt2qlfkoeiy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.mhx1999.top/Article/details/gt2piivduzj.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2ebudikyc.html

H. 异常与错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vmvfrwmo.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2zwqglxtm.html

[H01] try / catch 基础
来源：http://dali.jqgfzy.top/Article/details/gt2tlfgtfyf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jqgufenzy.top/Article/details/gt2lqsmwlkf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pycfn.com/Article/details/gt2fnmhngbx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gt2okfeubyk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sufxvd.cn/Article/details/gt2wgbblffl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cashguo.top/Article/details/gt2dyucyilj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tanke756.top/Article/details/gt2mjawsmgx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yangfankeji.com/Article/details/gt2epssebhp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lyyqivzq.html

[H02] finally / ensure 收尾
来源：http://dali.nwbrower.top/Article/details/gt2ycrqvtly.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tanke756.top/Article/details/gt2ofkqjezs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gt2igfztlhv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qletpfhj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2acoqedye.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2jlhgwtdi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.havefunace.top/Article/details/gt2cnrzlpmf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aibaodan.cn/Article/details/gt2lpfhdgzq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2bfaekybm.html

[H03] 主动抛出异常
来源：http://dali.wangdashe.top/Article/details/gt2dgwvtwio.html

Py:   raise ValueError("错误信息")
来源：http://dali.havefunace.top/Article/details/gt2bwdggbsu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qhdvcfzl.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gt2kswrapzz.html

TS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gt2galszfgk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2dylariml.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.9152youxi.cn/Article/details/gt2gnjdviqy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnqzz.top/Article/details/gt2jjrsyvvc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gt2dmxzbjeh.html

[H04] 自定义异常类型
来源：http://dali.jinqigufen.top/Article/details/gt2utdnmdfc.html

Py:   class MyError(Exception): pass
来源：http://dali.yuanzhike.top/Article/details/gt2ilmzgxil.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gt2uwvwbory.html

JS:   class MyError extends Error {}
来源：http://dali.jqgfzy.top/Article/details/gt2bewrhwxq.html

TS:   class MyError extends Error {}
来源：http://dali.yj20258.top/Article/details/gt2quwqwmxq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gt2pcjwejqc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hnqzz.top/Article/details/gt2lkapqtyc.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258.top/Article/details/gt2aeuowqgf.html

C#:   class MyException : Exception {}
来源：http://dali.jiagoushi.top/Article/details/gt2pqiwqtus.html

[H05] 捕获特定类型
来源：http://dali.mhx1999.top/Article/details/gt2jqwldndd.html

Py:   except ValueError as e:
来源：http://dali.yj20258.top/Article/details/gt2fzyaplxn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sxryk.cn/Article/details/gt2suzhtqfk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gt2yrceilvx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.c1oappe.top/Article/details/gt2ovrnxqzh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sweek.top/Article/details/gt2tphawvih.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shuidangran.top/Article/details/gt2qswirsnk.html

Ruby: rescue ArgumentError => e
来源：http://dali.ydzc1.top/Article/details/gt2tszfvvrg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yvedp.cn/Article/details/gt2rhwdinva.html

[H06] 可选值 / 空值安全访问
来源：http://dali.bjfxy.top/Article/details/gt2xjdivjip.html


<!-- 参考信息 -->