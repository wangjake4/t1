代发 wailian999

[F01] 读取整个文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjfekyst.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xylfe.cn/Article/details/gtortapbdt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtttkrldpy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hammf.cn/Article/details/gtozkfvjwp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.fengsongda.top/Article/details/gtvhpekoao.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtcumnrvbx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.kuanghao11.cn/Article/details/gthgwvsdvx.html

Ruby: File.read("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtncoufpka.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gticsslito.html

[F02] 逐行读取文件
来源：http://dali.sxryk.cn/Article/details/gtcvfgyudj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvppskxzb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhixingplan.top/Article/details/gtzzcceppp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtxejgjwmi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daria6918.cn/Article/details/gtglqahivc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gtdcftqgtk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cashguo.top/Article/details/gteyxxtvkd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gthliaqkxg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jlsjyb.cn/Article/details/gtajvmzyyn.html

[F03] 写入文件（覆盖）
来源：http://dali.nanxinkj.top/Article/details/gtftgqlxlo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jiagoushi.top/Article/details/gtzvlybnyi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj20258888.top/Article/details/gtvotgssli.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gtdockglsc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gtgwhmvton.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.birdmap.top/Article/details/gtihrtfdto.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sxryk.cn/Article/details/gtpynxxlja.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yonumen.top/Article/details/gtghekijrv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guannengcc.top/Article/details/gtcmfzjxgg.html

[F04] 追加写入文件
来源：http://dali.xuanzx.com/Article/details/gtrvzrfmax.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.svipenyu.cn/Article/details/gtjlfnjebh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yongpay.top/Article/details/gtfrgckndp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtznvcaohn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtopjwzwwk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangshuangyany.cn/Article/details/gtcnlqvjii.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ydzc1.top/Article/details/gtcwjcnlal.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shzxlz.cn/Article/details/gtfhtpkkdq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nwbrower.top/Article/details/gtntinoqtp.html

[F05] 判断文件或目录是否存在
来源：http://dali.redwolf501.top/Article/details/gtdlyktbcv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhiwuduotai.top/Article/details/gtjuckswuj.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtdbwnagml.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtnmzjwcoo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtflppyzbj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtvmoxrdqx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shangyingyoupin.top/Article/details/gthqwybrsq.html

Ruby: File.exist?("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtmnusuafh.html

C#:   File.Exists("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtnxuufqiu.html

[F06] 删除文件
来源：http://dali.cheryme.top/Article/details/gtzoxufcjr.html

Py:   os.remove("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtinsvcmpn.html

PHP:  unlink("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtynpsejri.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtatqkqtph.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gthcejwggl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gtjwivimav.html

Go:   os.Remove("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtnpwdepuu.html

Ruby: File.delete("a.txt")
来源：http://dali.yonumen.top/Article/details/gtxkwjjzhx.html

C#:   File.Delete("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtwfcobsag.html

[F07] 创建目录（含多级）
来源：http://dali.shuidangran.top/Article/details/gtlfzbuika.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.mhx1999.top/Article/details/gtoyzonpth.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zycfv.cn/Article/details/gtrjzfcdxy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gtuhmnrmts.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gtiqevbiwh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jiagoushi.top/Article/details/gtpncfqsio.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuanzx.com/Article/details/gtttducnxg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.snrcjt.cn/Article/details/gtcngqomqm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tanke756.top/Article/details/gtlcnixvfb.html

[F08] 遍历目录
来源：http://dali.yueranfly.top/Article/details/gtvbshfazl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.meibo888.top/Article/details/gtlcvrvugh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvsjtmjfb.html

JS:   fs.readdirSync("dir")
来源：http://dali.cdnleiting.top/Article/details/gtewhycaqa.html

TS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gtqwdeclnm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jqgfzy.top/Article/details/gtpodkedpi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.iojbl.cn/Article/details/gtmgoxsdkm.html

Ruby: Dir.children("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtpgybowqy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aizwys.cn/Article/details/gtixwgvejl.html

[F09] 获取文件大小
来源：http://dali.cucudq.cn/Article/details/gtjswyhgfs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtxcvkjcyq.html

PHP:  filesize("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gthluwnapj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gttxfnxoml.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gtmtidyuxc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtwwduiemj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhongyouzk.top/Article/details/gtqbpakykm.html

Ruby: File.size("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtzokdvmvc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ydzc1.top/Article/details/gtnvbisxgj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxinkj.top/Article/details/gtfkzehusj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtibungyrw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.316326.xyz/Article/details/gtxfdqltnr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtaslysjlj.html

TS:   path.extname("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gttdvkiigp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cashguo.top/Article/details/gtymizqtfq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtiniomltq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtdpltlkek.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtesnnccvy.html

[F11] 复制与移动文件
来源：http://dali.cashguo.top/Article/details/gtoaoliyll.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtmrxdrmzj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yuanzhike.top/Article/details/gtwafzhbfd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtzxfmryci.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxhvcxqa.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtekvioxej.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shangyingyoupin.top/Article/details/gtsfgflhyf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gthjvlmfxh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258888.top/Article/details/gtdlprbdvl.html

[F12] CSV 读写
来源：http://dali.feifeiyinyue.top/Article/details/gtetuntlrh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.birdmap.top/Article/details/gtwbyebuws.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.haohaochexian.top/Article/details/gthpxnodvm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jianghu66.top/Article/details/gtajrhoguc.html

TS:   // 同上
来源：http://dali.quarkkingdee.top/Article/details/gtuigpxpvu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ivvv.top/Article/details/gtazgstawo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cucudq.cn/Article/details/gtfhzwjlsy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuttrcnet.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.aizwys.cn/Article/details/gtbbdfapve.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtavwzjiua.html

G. 面向对象
来源：http://dali.smart0.xyz/Article/details/gtpjldjztn.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtokdddtcc.html

[G01] 定义类
来源：http://dali.xinyue.icu/Article/details/gtwkbvvuwt.html

Py:   class User: pass
来源：http://dali.jqgufenzy.top/Article/details/gtijnqgrue.html

PHP:  class User {}
来源：http://dali.smart0.xyz/Article/details/gtkeryilgl.html

JS:   class User {}
来源：http://dali.jqgfzy.top/Article/details/gtrkbbkbsj.html

TS:   class User { name: string = ""; }
来源：http://dali.daxiang520.top/Article/details/gtgbhqpioc.html

Java: class User {}
来源：http://dali.jqgufenzy.top/Article/details/gtncstnmfe.html

Go:   type User struct { Name string }
来源：http://dali.cdnleiting.top/Article/details/gtcznozzez.html

Ruby: class User; end
来源：http://dali.cucudq.cn/Article/details/gtayizlmyt.html

C#:   class User {}
来源：http://dali.fzhhl.top/Article/details/gtqluzhmsg.html

[G02] 构造函数
来源：http://dali.cheryme.top/Article/details/gtxviwhufs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yuxming.cn/Article/details/gtusgshbeg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jlsjyb.cn/Article/details/gtlzitupgr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sxryk.cn/Article/details/gtcmgaswdf.html

TS:   constructor(public name: string) {}
来源：http://dali.yj202588.top/Article/details/gtjemxfozw.html

Java: User(String name) { this.name = name; }
来源：http://dali.tianlin.xyz/Article/details/gtpvvvogsn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuxming.cn/Article/details/gtvirucdda.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fengsongda.top/Article/details/gtbptpqscy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gthmaffqak.html

[G03] 实例属性
来源：http://dali.tianlin.xyz/Article/details/gtulqpbhnp.html

Py:   self.name = "x"
来源：http://dali.gotoacloud.top/Article/details/gtddgmflxx.html

PHP:  public string $name = "x";
来源：http://dali.yj20258.top/Article/details/gtwqrvpnmg.html

JS:   this.name = "x";
来源：http://dali.hfpthk.cn/Article/details/gtecollcgl.html

TS:   name: string = "x";
来源：http://dali.gogol.net.cn/Article/details/gtdycvycoo.html

Java: private String name;
来源：http://dali.jlsjyb.cn/Article/details/gtnojwlbfx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.c1oappe.top/Article/details/gtmavemguh.html

Ruby: @name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gtvjzyhftw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtalvwbbam.html

[G04] 定义方法
来源：http://dali.shzxlz.cn/Article/details/gtlkdmjwjh.html

Py:   def greet(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gtsstrbbvh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtbllfavyu.html

JS:   greet() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtvippjmbl.html

TS:   greet(): string { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtmwiklbwm.html

Java: String greet() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtgjpwekau.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtquydcyzk.html

Ruby: def greet; @name; end
来源：http://dali.zhengqikj.top/Article/details/gtvsoldypn.html

C#:   public string Greet() => Name;
来源：http://dali.yvedp.cn/Article/details/gtxajaixjg.html

[G05] 继承
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlzvjdqvc.html

Py:   class Admin(User): pass
来源：http://dali.aizwys.cn/Article/details/gtgkjahywp.html

PHP:  class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtdlliygfa.html

JS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtaevoltlp.html

TS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtfsixelbc.html

Java: class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtjghpgzxn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.svipenyu.cn/Article/details/gtvwvsiwrf.html

Ruby: class Admin < User; end
来源：http://dali.wangdashe.top/Article/details/gtbqswelzd.html

C#:   class Admin : User {}
来源：http://dali.hywenlv.cn/Article/details/gtonixphou.html

[G06] 重写方法
来源：http://dali.smart0.xyz/Article/details/gteqrpwtbn.html

Py:   def greet(self): return "admin"
来源：http://dali.dianchejie.cn/Article/details/gtkeqayokp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqhgwati.html

JS:   greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtgdhdqzhe.html

TS:   greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtrzlthfvx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtixllivgd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.smart0.xyz/Article/details/gtimsljggj.html

Ruby: def greet; "admin"; end
来源：http://dali.hfpthk.cn/Article/details/gtsorhegel.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenzaomai.com/Article/details/gthnjgzmdd.html

[G07] 调用父类方法
来源：http://dali.zhiwuduotai.top/Article/details/gtbeitqusj.html

Py:   super().greet()
来源：http://dali.cheryme.top/Article/details/gthbugbstb.html

PHP:  parent::greet();
来源：http://dali.gogol.net.cn/Article/details/gthsfuoxwg.html

JS:   super.greet();
来源：http://dali.hfpthk.cn/Article/details/gtqnjenrqm.html

TS:   super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gtqbrammwb.html

Java: super.greet();
来源：http://dali.xziqi.cn/Article/details/gtepmcpftd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.kuanghao11.cn/Article/details/gtvpjnbslg.html

Ruby: super
来源：http://dali.jinghuilouyu.cn/Article/details/gtauojfazf.html

C#:   base.Greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjbsxutn.html

[G08] 静态方法与属性
来源：http://dali.hysaishi.cn/Article/details/gttznjdyqk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuetiantiany.cn/Article/details/gtwvhkopqi.html

PHP:  public static function f() {}
来源：http://dali.ppjwa.cn/Article/details/gtkijhhneu.html

JS:   static f() {}
来源：http://dali.sweek.top/Article/details/gtqkmscyrt.html

TS:   static f(): void {}
来源：http://dali.hnxiangtu.top/Article/details/gtobvnfvvm.html

Java: static void f() {}
来源：http://dali.redwolf501.top/Article/details/gtojzdklzh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fzhhl.top/Article/details/gtzfynydhn.html

Ruby: def self.f; end
来源：http://dali.svipenyu.cn/Article/details/gtthlykjhe.html

C#:   public static void F() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtqkxkxdox.html

[G09] 接口 / 抽象类
来源：http://dali.tianlin.xyz/Article/details/gtlhalmaxl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqrxmwdy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.andypj.xyz/Article/details/gticcevyhn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xuetiantiany.cn/Article/details/gtqrsdjwlh.html

TS:   interface Shape { area(): number; }
来源：http://dali.vqdsnc.cn/Article/details/gtbhpqaxwn.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258.top/Article/details/gtxmocjnly.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.kuanghao11.cn/Article/details/gtjrcbhbhi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gotoacloud.top/Article/details/gteppujcpd.html

C#:   interface IShape { double Area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtzqxqtmct.html

[G10] 访问控制
来源：http://dali.shanyushiyangtech.top/Article/details/gtustxgnzb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.aibaodan.cn/Article/details/gtrecepguh.html

PHP:  public / protected / private
来源：http://dali.redwolf501.top/Article/details/gtfqyfvslf.html

JS:   #private 字段；其余公开
来源：http://dali.yanxiufei.cn/Article/details/gtjcsuyiri.html

TS:   public / protected / private
来源：http://dali.birdmap.top/Article/details/gtxrpkvrfc.html

Java: public / protected / private / 默认包级
来源：http://dali.zhoulong.xyz/Article/details/gtqoyrpkei.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xinyue.icu/Article/details/gttcsjzuca.html

Ruby: public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gtkhvvjndi.html

C#:   public / protected / private / internal
来源：http://dali.0kj1m.cn/Article/details/gtdmbdaolh.html

[G11] getter / setter
来源：http://dali.c1oappe.top/Article/details/gtlhyopanh.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258.top/Article/details/gttyyztfjs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtwzlybfhv.html

JS:   get name() { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtvnfqcirs.html

TS:   get name(): string { return this._name; }
来源：http://dali.yonumen.top/Article/details/gtmdfbzfaj.html

Java: public String getName() { return name; }
来源：http://dali.yvedp.cn/Article/details/gtyrjlqwrw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gtzkwjwbhi.html

Ruby: attr_accessor :name
来源：http://dali.ivvv.top/Article/details/gtjltdopgm.html

C#:   public string Name { get; set; }
来源：http://dali.cdnleiting.top/Article/details/gtxrambvmm.html

[G12] 对象转字符串
来源：http://dali.sxryk.cn/Article/details/gtsfdcptuv.html

Py:   def __str__(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gtuhnyeguf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtrlestuoi.html

JS:   toString() { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtodmdlmyh.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtblnvydjn.html

Java: @Override public String toString() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtgdyosfxq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtdjdtatjz.html

Ruby: def to_s; @name; end
来源：http://dali.daria6918.cn/Article/details/gtsbmidytz.html

C#:   public override string ToString() => Name;
来源：http://dali.hysaishi.cn/Article/details/gtqhwqsxyx.html

[G13] 判断对象类型
来源：http://dali.quarkkingdee.top/Article/details/gtjledomjl.html

Py:   isinstance(u, User)
来源：http://dali.zdqjudy.top/Article/details/gtqktsuomb.html

PHP:  $u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtigvsobiq.html

JS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtktxhwowx.html

TS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtxbuevdpn.html

Java: u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtptvhparf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cheryme.top/Article/details/gtxkftiojo.html

Ruby: u.is_a?(User)
来源：http://dali.xylfe.cn/Article/details/gtxlfebvsq.html

C#:   u is User
来源：http://dali.pengpengdd.cyou/Article/details/gtzrvyitym.html

[G14] 数据类 / record
来源：http://dali.guannengcc.top/Article/details/gtajumotmg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dashuyun.cn/Article/details/gtvosoofdx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.havefunace.top/Article/details/gtwgjugnqt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhoulong.xyz/Article/details/gtwikobbgk.html

TS:   type User = { name: string; age: number };
来源：http://dali.yueranfly.top/Article/details/gtjgzpvpxr.html

Java: record User(String name, int age) {}
来源：http://dali.yonumen.top/Article/details/gtxixwhyaz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.birdmap.top/Article/details/gtzbtizzmn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hfpthk.cn/Article/details/gtwpabujsn.html

C#:   record User(string Name, int Age);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjthohnkk.html

[G15] 枚举
来源：http://dali.gaohongyu789.top/Article/details/gtopfsuphj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jlsjyb.cn/Article/details/gtjsbwxwra.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guannengcc.top/Article/details/gtrsyhxjac.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yonumen.top/Article/details/gtoryrtund.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gtcakquwcq.html

Java: enum Color { RED, GREEN }
来源：http://dali.xylfe.cn/Article/details/gtlbmviwaj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbnzsdyfn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.pycfn.com/Article/details/gtubtrfwva.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtdjrjqdyv.html

[G16] 对象转数组 / 字典
来源：http://dali.chenlongwang.top/Article/details/gtctutybfv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hongshengwenyu.top/Article/details/gteutkclyr.html

PHP:  get_object_vars($obj);
来源：http://dali.chenlongwang.top/Article/details/gtfzlnmnnp.html

JS:   Object.entries(obj)
来源：http://dali.redwolf501.top/Article/details/gtpjmwizbk.html

TS:   Object.entries(obj)
来源：http://dali.cqqwz.cn/Article/details/gtaowpgmpm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzblutrft.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hnxiangtu.top/Article/details/gtlfbldpcb.html

Ruby: obj.instance_variables
来源：http://dali.nanxuanxn.top/Article/details/gtrkxqiatr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hammf.cn/Article/details/gtnijiusoa.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtqpfwwwcb.html

H. 异常与错误处理
来源：http://dali.hnxiangtu.top/Article/details/gtzgnbnsyf.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gthycjyimh.html

[H01] try / catch 基础
来源：http://dali.daxiang520.top/Article/details/gtmvrrdgvx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cqqwz.cn/Article/details/gtafoumkjd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sxryk.cn/Article/details/gtryxivlqk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gtguouooye.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gtlanivgkp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmklxeys.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nwbrower.top/Article/details/gtixcfetyy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj202588.top/Article/details/gtcgoalvlt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.vqdsnc.cn/Article/details/gthehimtfr.html

[H02] finally / ensure 收尾
来源：http://dali.mhx1999.top/Article/details/gtksxfippc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtureixmgj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtqqwvlglw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtkxvbtyhx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtoeakhvpb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtbkszhmyf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.smart0.xyz/Article/details/gtycnqyigl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guowangkeji.top/Article/details/gtsjbtkkpk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtijdmtkof.html

[H03] 主动抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gtdakygtub.html

Py:   raise ValueError("错误信息")
来源：http://dali.hywenlv.cn/Article/details/gtmiumvixd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtcoxwsgwy.html

JS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtpvtarvjb.html

TS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gtgglvnbxw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtlydloguw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.9152youxi.cn/Article/details/gtzmwlagyk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.quarkkingdee.top/Article/details/gtudcqjpby.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtqsoundwf.html

[H04] 自定义异常类型
来源：http://dali.pycfn.com/Article/details/gtafdrotjj.html

Py:   class MyError(Exception): pass
来源：http://dali.shangyingyoupin.top/Article/details/gtifncwyvf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gtdedfwojt.html

JS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gtflaqjpew.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnankqrfm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gtdgqhgmxq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shzxlz.cn/Article/details/gtxshgepao.html

Ruby: class MyError < StandardError; end
来源：http://dali.haohaochexian.top/Article/details/gtgiivahgz.html

C#:   class MyException : Exception {}
来源：http://dali.xuetiantiany.cn/Article/details/gtmsnvsmhe.html

[H05] 捕获特定类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcceelklv.html

Py:   except ValueError as e:
来源：http://dali.xinyue.icu/Article/details/gtmlgzttgb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nanxinkj.top/Article/details/gtlssojlwt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gtuxilbsxb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangdashe.top/Article/details/gtbvfgqdok.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jlsjyb.cn/Article/details/gtwvtenzbg.html


<!-- 参考信息 -->