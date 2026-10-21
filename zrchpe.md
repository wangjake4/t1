代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gotoacloud.top/Article/details/gttaibiecd.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gthegpylsx.html

F. 文件与目录
来源：http://dali.ydzc1.top/Article/details/gtakxgswho.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtnugtzpmp.html

[F01] 读取整个文件
来源：http://dali.vqdsnc.cn/Article/details/gtfziptxkj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xuanzx.com/Article/details/gtjcjgaifa.html

PHP:  file_get_contents("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtdhlwgsgj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cqqwz.cn/Article/details/gtlczbtaxj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtqfxxjlxz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtmqmophst.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinghuilouyu.cn/Article/details/gtgscubojx.html

Ruby: File.read("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtnfcpbwyi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxntwkez.html

[F02] 逐行读取文件
来源：http://dali.yongpay.top/Article/details/gtkwghxovf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.svipenyu.cn/Article/details/gtxmxqgqkb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.fzhhl.top/Article/details/gtmuyfwmus.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtrrskbowa.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hammf.cn/Article/details/gtplulcenm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gtdvnpfgek.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.daxiang520.top/Article/details/gtabkxivpa.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xuetiantiany.cn/Article/details/gttantwtkn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yueranfly.top/Article/details/gtbvawggzy.html

[F03] 写入文件（覆盖）
来源：http://dali.hongshengwenyu.top/Article/details/gtouxocvch.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.316326.xyz/Article/details/gtlpclamum.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gtzracedxe.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gtmxyczumb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gtwstgndea.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gtloekiblr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gtbuhekdbf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuanzx.com/Article/details/gtxpdxkors.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gthnmmlyyo.html

[F04] 追加写入文件
来源：http://dali.andypj.xyz/Article/details/gtogyuuzou.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jiagoushi.top/Article/details/gtsdwmityc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cashguo.top/Article/details/gtqvzzmzkz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtlswtfhso.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zycfv.cn/Article/details/gtlqlkpjci.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shangyingyoupin.top/Article/details/gtsmvkfkcr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gthqltdnzl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhoulong.xyz/Article/details/gtuiftzqfn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzbrhysg.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxinkj.top/Article/details/gtkonqkara.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ppjwa.cn/Article/details/gtmgmkcmti.html

PHP:  file_exists("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtthcldrwl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtfsikawhf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtuznzftqr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtodvleepg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jlsjyb.cn/Article/details/gtcutjckrz.html

Ruby: File.exist?("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtkvzjtyjg.html

C#:   File.Exists("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtrkrmlgxi.html

[F06] 删除文件
来源：http://dali.bjfxy.top/Article/details/gtayknpkuu.html

Py:   os.remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtnasixlha.html

PHP:  unlink("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtumygyfnp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtonzsfdre.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtjvdrlndb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtoaqmroun.html

Go:   os.Remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtltxneidk.html

Ruby: File.delete("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtlhhxlnrw.html

C#:   File.Delete("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtotckmhhw.html

[F07] 创建目录（含多级）
来源：http://dali.haohaochexian.top/Article/details/gtiiztonzv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hysaishi.cn/Article/details/gtdozlxtrk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jianghu66.top/Article/details/gtvmwyibdn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gtaapjqpoz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhixingplan.top/Article/details/gtddkoisrd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sufxvd.cn/Article/details/gtlidtjzab.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yonumen.top/Article/details/gtaapiutoq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yangfankeji.com/Article/details/gtiyqncodx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shangyingyoupin.top/Article/details/gtradtvndz.html

[F08] 遍历目录
来源：http://dali.jiagoushi.top/Article/details/gtrrquujga.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenjidiqi.icu/Article/details/gtmlvyqudt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shangyingyoupin.top/Article/details/gtzspishvt.html

JS:   fs.readdirSync("dir")
来源：http://dali.dashuyun.cn/Article/details/gtgcmomjao.html

TS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gtsaowjpgy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthbtwvdrp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwubilfqn.html

Ruby: Dir.children("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtugxuonov.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jiagoushi.top/Article/details/gtvbzojxsg.html

[F09] 获取文件大小
来源：http://dali.pycfn.com/Article/details/gtaiprojng.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pycfn.com/Article/details/gtzhsylwbd.html

PHP:  filesize("a.txt");
来源：http://dali.tanke756.top/Article/details/gtuiniuptb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.vqdsnc.cn/Article/details/gtlgkvtqny.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aibaodan.cn/Article/details/gtqqcbskwg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtkmzglcfb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaldikfie.html

Ruby: File.size("a.txt")
来源：http://dali.xylfe.cn/Article/details/gthadqfhqz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cdnleiting.top/Article/details/gtrzvdljhl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xziqi.cn/Article/details/gtgilqeipk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtcywdaxmu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sysykeji.top/Article/details/gtfnkucvsq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtpdjnlsfe.html

TS:   path.extname("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtjxfwonep.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenlongwang.top/Article/details/gttjeflagu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtauasktfd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtroktlhyp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtyogscrcv.html

[F11] 复制与移动文件
来源：http://dali.sufxvd.cn/Article/details/gtcxcdaexc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtvfwrjyte.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.smart0.xyz/Article/details/gtemhrhtli.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gthixxzxea.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtvszqtdzq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tian-w.cn/Article/details/gtkusyeakp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yanxiufei.cn/Article/details/gtrlnytxxu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvqdchnj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shzxlz.cn/Article/details/gtiwtkovyc.html

[F12] CSV 读写
来源：http://dali.guowangkeji.top/Article/details/gtommluhpk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhengqikj.top/Article/details/gtpfogwvby.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sufxvd.cn/Article/details/gtbwexbpwi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.birdmap.top/Article/details/gtkjkmvgvw.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gtlmhcyfst.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.kuanghao11.cn/Article/details/gthtepidly.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.daxiang520.top/Article/details/gtspiqlpbl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yonumen.top/Article/details/gtrleyorje.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sweek.top/Article/details/gtefrprews.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtrlzqfikt.html

G. 面向对象
来源：http://dali.shanyushiyangtech.top/Article/details/gtvgkabgfz.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtnggzelsb.html

[G01] 定义类
来源：http://dali.haohaochexian.top/Article/details/gttpeyeobm.html

Py:   class User: pass
来源：http://dali.hywenlv.cn/Article/details/gtebesqppj.html

PHP:  class User {}
来源：http://dali.haohaochexian.top/Article/details/gtlkqwvbik.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gterjcouch.html

TS:   class User { name: string = ""; }
来源：http://dali.jinqigfzy.top/Article/details/gtahyafkmb.html

Java: class User {}
来源：http://dali.zhixingplan.top/Article/details/gtjpffprmk.html

Go:   type User struct { Name string }
来源：http://dali.tanke756.top/Article/details/gtaaulvyhh.html

Ruby: class User; end
来源：http://dali.jqgufenzy.top/Article/details/gtrlbfjons.html

C#:   class User {}
来源：http://dali.hywenlv.cn/Article/details/gtdtaigfkr.html

[G02] 构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gtqzgqrktt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yuanzhike.top/Article/details/gtjwuciubp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gaohongyu789.top/Article/details/gtdgwwafsm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gtaisduhcj.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gtxhdnuyup.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtzcpjwzhu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuanzhike.top/Article/details/gtohckweuv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.redwolf501.top/Article/details/gtpagzdkto.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xziqi.cn/Article/details/gtkdmqiuon.html

[G03] 实例属性
来源：http://dali.chenjidiqi.icu/Article/details/gtmjogqdrt.html

Py:   self.name = "x"
来源：http://dali.yueranfly.top/Article/details/gtbkqbdiho.html

PHP:  public string $name = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtpvlclnye.html

JS:   this.name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtjalnhcol.html

TS:   name: string = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtgkieessg.html

Java: private String name;
来源：http://dali.daxiang520.top/Article/details/gtzruawfen.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.meibo888.top/Article/details/gtiyubikjw.html

Ruby: @name = "x"
来源：http://dali.ppjwa.cn/Article/details/gtafacfxai.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj20258888.top/Article/details/gtdgxgdwhz.html

[G04] 定义方法
来源：http://dali.shzxlz.cn/Article/details/gtyvyntqbe.html

Py:   def greet(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gtxchpuzmh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtlpaiwfxr.html

JS:   greet() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtlaaxyrpg.html

TS:   greet(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtusblwunk.html

Java: String greet() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtgzwhtpqt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtdhjyqrey.html

Ruby: def greet; @name; end
来源：http://dali.yj20258888.top/Article/details/gtujbungaf.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258888.top/Article/details/gtifycfxxt.html

[G05] 继承
来源：http://dali.shangyingyoupin.top/Article/details/gtaopzohtw.html

Py:   class Admin(User): pass
来源：http://dali.cashguo.top/Article/details/gtsacvxrfy.html

PHP:  class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtywohxohn.html

JS:   class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gttzkvidpr.html

TS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gttcaxaxac.html

Java: class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtlqiqkzyq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pengpengdd.cyou/Article/details/gtucagolvw.html

Ruby: class Admin < User; end
来源：http://dali.zhiwuduotai.top/Article/details/gtcrrpiopv.html

C#:   class Admin : User {}
来源：http://dali.wangdashe.top/Article/details/gtnbehxhrj.html

[G06] 重写方法
来源：http://dali.shzxlz.cn/Article/details/gtalwzmdzc.html

Py:   def greet(self): return "admin"
来源：http://dali.mhx1999.top/Article/details/gtjgritzxh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtrlsgmvhr.html

JS:   greet() { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gttwrfwuna.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtukhyqmyy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxymbmyhm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.redwolf501.top/Article/details/gtnqkikdxv.html

Ruby: def greet; "admin"; end
来源：http://dali.xylfe.cn/Article/details/gtxzvyitls.html

C#:   public override string Greet() => "admin";
来源：http://dali.hfpthk.cn/Article/details/gtmcgeabck.html

[G07] 调用父类方法
来源：http://dali.sweek.top/Article/details/gtnqwedzva.html

Py:   super().greet()
来源：http://dali.gogol.net.cn/Article/details/gtuhpgalon.html

PHP:  parent::greet();
来源：http://dali.nanxinkj.top/Article/details/gtcizacsqv.html

JS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gtcxfbwfvx.html

TS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gtgxfzmxbf.html

Java: super.greet();
来源：http://dali.yuxming.cn/Article/details/gtpclbyvgu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hongshengwenyu.top/Article/details/gtookcetzu.html

Ruby: super
来源：http://dali.zhoulong.xyz/Article/details/gthwcohhby.html

C#:   base.Greet();
来源：http://dali.yongpay.top/Article/details/gthpokftzg.html

[G08] 静态方法与属性
来源：http://dali.fzhhl.top/Article/details/gtyxpbcobe.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.fzhhl.top/Article/details/gtuvymixkx.html

PHP:  public static function f() {}
来源：http://dali.cheryme.top/Article/details/gtyzjogeya.html

JS:   static f() {}
来源：http://dali.wangdashe.top/Article/details/gtqmwjraij.html

TS:   static f(): void {}
来源：http://dali.cucudq.cn/Article/details/gtearqaxla.html

Java: static void f() {}
来源：http://dali.cdnleiting.top/Article/details/gtwjtowfbo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gotoacloud.top/Article/details/gtcatcrvwj.html

Ruby: def self.f; end
来源：http://dali.nanxuanxn.top/Article/details/gtywrcdkyq.html

C#:   public static void F() {}
来源：http://dali.chenlongwang.top/Article/details/gttubpqwzj.html

[G09] 接口 / 抽象类
来源：http://dali.shuidangran.top/Article/details/gtcmyfkjcv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gogol.net.cn/Article/details/gtzkkwgrir.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nwbrower.top/Article/details/gtstvbvnss.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkqgzpjhv.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvcotzxtj.html

Java: interface Shape { double area(); }
来源：http://dali.c1oappe.top/Article/details/gtrhfydpqv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrzfazkgq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xylfe.cn/Article/details/gtkpxmlsln.html

C#:   interface IShape { double Area(); }
来源：http://dali.nwbrower.top/Article/details/gtgvjjskxd.html

[G10] 访问控制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjobmnzon.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.aibaodan.cn/Article/details/gtpjcbsduy.html

PHP:  public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gtddvgtbmb.html

JS:   #private 字段；其余公开
来源：http://dali.daxiang520.top/Article/details/gtpnnslntv.html

TS:   public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtizptkbpb.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvciadwtc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.snrcjt.cn/Article/details/gtqhbynfsd.html

Ruby: public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnpynnpd.html

C#:   public / protected / private / internal
来源：http://dali.gogol.net.cn/Article/details/gtbsqibwkx.html

[G11] getter / setter
来源：http://dali.zhiwuduotai.top/Article/details/gtajcrzqfq.html

Py:   @property 与 @x.setter
来源：http://dali.birdmap.top/Article/details/gtrexxwxpj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtvksygwsu.html

JS:   get name() { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gtfvjlnaje.html

TS:   get name(): string { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gtgoqlxzbh.html

Java: public String getName() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtotiqacun.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtntehzqmm.html

Ruby: attr_accessor :name
来源：http://dali.dianchejie.cn/Article/details/gtpasoxhag.html

C#:   public string Name { get; set; }
来源：http://dali.sysykeji.top/Article/details/gtlulethkc.html

[G12] 对象转字符串
来源：http://dali.chenzaomai.com/Article/details/gtwydkmhxd.html

Py:   def __str__(self): return self.name
来源：http://dali.ivvv.top/Article/details/gttjwovjfn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtriftivxr.html

JS:   toString() { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtytitmnmn.html

TS:   toString(): string { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtbcvxlbbi.html

Java: @Override public String toString() { return name; }
来源：http://dali.xylfe.cn/Article/details/gtivrirhac.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gtookevlyl.html

Ruby: def to_s; @name; end
来源：http://dali.yj202588.top/Article/details/gtrudqfaaj.html

C#:   public override string ToString() => Name;
来源：http://dali.gotoacloud.top/Article/details/gtdvzuxxtr.html

[G13] 判断对象类型
来源：http://dali.aibaodan.cn/Article/details/gtzfcwbbve.html

Py:   isinstance(u, User)
来源：http://dali.fengsongda.top/Article/details/gtpkorncji.html

PHP:  $u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtytjrxjjc.html

JS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gtndrpjsen.html

TS:   u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtvpwhryhq.html

Java: u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtcfywignt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yangfankeji.com/Article/details/gtandewxjw.html

Ruby: u.is_a?(User)
来源：http://dali.hywenlv.cn/Article/details/gtzeimsndf.html

C#:   u is User
来源：http://dali.hammf.cn/Article/details/gthbtsaozw.html

[G14] 数据类 / record
来源：http://dali.ydzc1.top/Article/details/gtfatjpbzs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sweek.top/Article/details/gtjlecaier.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.0kj1m.cn/Article/details/gtcusezrlg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.redwolf501.top/Article/details/gtxurzhahw.html

TS:   type User = { name: string; age: number };
来源：http://dali.yvedp.cn/Article/details/gtplbylqrl.html

Java: record User(String name, int age) {}
来源：http://dali.fzhhl.top/Article/details/gttrjavgpt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangdashe.top/Article/details/gtjhiizkbi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.0kj1m.cn/Article/details/gthiwnfcoq.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxuanxn.top/Article/details/gtswuaekuo.html

[G15] 枚举
来源：http://dali.zdqjudy.top/Article/details/gtoptwjyqj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gogol.net.cn/Article/details/gtirdjkhzg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.fzhhl.top/Article/details/gtjdeiiouk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcgfayrmo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gtxwxvdntv.html

Java: enum Color { RED, GREEN }
来源：http://dali.cashguo.top/Article/details/gtpojaidse.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cheryme.top/Article/details/gtgfabbiqj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hywenlv.cn/Article/details/gtlklhpfef.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.9152youxi.cn/Article/details/gthimqqyka.html

[G16] 对象转数组 / 字典
来源：http://dali.cqqwz.cn/Article/details/gtlmjzpfmi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cashguo.top/Article/details/gtdjbincpq.html

PHP:  get_object_vars($obj);
来源：http://dali.daria6918.cn/Article/details/gtzsfycghu.html

JS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonwcixzm.html

TS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gtzskgfbiq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.andypj.xyz/Article/details/gtxhwdcajv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hammf.cn/Article/details/gtywtevnir.html

Ruby: obj.instance_variables
来源：http://dali.jinqigfzy.top/Article/details/gtthdibrkf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tianlin.xyz/Article/details/gtwvugujmc.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gthodxsbho.html

H. 异常与错误处理
来源：http://dali.jyoumei.cn/Article/details/gtfrqzfwkm.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtmxbmanqr.html

[H01] try / catch 基础
来源：http://dali.jqgufenzy.top/Article/details/gtleollxkd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xuetiantiany.cn/Article/details/gtqfwivdjm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yongpay.top/Article/details/gtwycbiccf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gtekgwfasb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gtuicvnkuv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jiagoushi.top/Article/details/gtbhmboueo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.dashuyun.cn/Article/details/gtzfqagqav.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jianghu66.top/Article/details/gttghfqhyz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbydqpdp.html

[H02] finally / ensure 收尾
来源：http://dali.aibaodan.cn/Article/details/gtovtykowy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.bjfxy.top/Article/details/gthkkzdijq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtiqwgsxuu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtpotdxlsl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtbwjtakty.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtaohneaia.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.haohaochexian.top/Article/details/gtzlceeluq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xinyue.icu/Article/details/gtjmovkgxs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtytltgsal.html

[H03] 主动抛出异常
来源：http://dali.tianlin.xyz/Article/details/gtjtuntkmx.html

Py:   raise ValueError("错误信息")
来源：http://dali.xziqi.cn/Article/details/gtefmuwuvc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtgedecovl.html

JS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gteubhwuit.html

TS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtpcgioqkq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtpflhfwaw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.pycfn.com/Article/details/gtqwlomdrl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuxming.cn/Article/details/gtyialcfbj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gthqecknyj.html

[H04] 自定义异常类型
来源：http://dali.meibo888.top/Article/details/gtkkerkavw.html

Py:   class MyError(Exception): pass
来源：http://dali.zhixingplan.top/Article/details/gtmzjirxzl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.vqdsnc.cn/Article/details/gtfmyectga.html

JS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gtrciovxfv.html

TS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gtuibpjvzq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.0kj1m.cn/Article/details/gthycmdgoy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.bjfxy.top/Article/details/gthflvypld.html

Ruby: class MyError < StandardError; end
来源：http://dali.jyoumei.cn/Article/details/gtvyufztxo.html

C#:   class MyException : Exception {}
来源：http://dali.tianlin.xyz/Article/details/gthpkfydrm.html

[H05] 捕获特定类型
来源：http://dali.nwbrower.top/Article/details/gtjqtslqaa.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzwsvshl.html


<!-- 参考信息 -->