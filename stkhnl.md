代发 wailian999

[F01] 读取整个文件
来源：http://dali.9152youxi.cn/Article/details/gtpzpammzt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yueranfly.top/Article/details/gtyuqotrlc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gthtihonzx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.svipenyu.cn/Article/details/gteujmlrpu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkwbylyec.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtcvqoqryy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinqigufen.top/Article/details/gthmmsscej.html

Ruby: File.read("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtcxzovcuw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtkapipvfy.html

[F02] 逐行读取文件
来源：http://dali.jqgfzy.top/Article/details/gtgrceijyx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yueranfly.top/Article/details/gtnjcucoqi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hywenlv.cn/Article/details/gtigmclvgx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sweek.top/Article/details/gtdkotavau.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhixingplan.top/Article/details/gtljmbdcih.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pycfn.com/Article/details/gtknbcyalc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.snrcjt.cn/Article/details/gtsfcooanq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenzaomai.com/Article/details/gtgyudkwpj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tianlin.xyz/Article/details/gtddxnfalb.html

[F03] 写入文件（覆盖）
来源：http://dali.gaohongyu789.top/Article/details/gtggidgzsg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.316326.xyz/Article/details/gtpaopfwki.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gtygyzohtf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gtllpsrvjl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.birdmap.top/Article/details/gtadgtvmud.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hnqzz.top/Article/details/gtiyjqlsvb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gogol.net.cn/Article/details/gtgwuwtlnu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hfpthk.cn/Article/details/gtkloavybb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gtznljfggg.html

[F04] 追加写入文件
来源：http://dali.wangdashe.top/Article/details/gtpvcakvhd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenlongwang.top/Article/details/gtuzuwjjgm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenzaomai.com/Article/details/gtvnpwecvw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shuidangran.top/Article/details/gtwrdtiuaj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtmvxjfmql.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ppjwa.cn/Article/details/gtwkzyghvq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gtibwcgrlg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xuanzx.com/Article/details/gtbqskvakn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xylfe.cn/Article/details/gtstgmdonl.html

[F05] 判断文件或目录是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gtzrbaijva.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yonumen.top/Article/details/gtzkvxjoxj.html

PHP:  file_exists("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtlggrfqbl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtxprrfyqx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtljzviboo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gtqbisbqnq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.snrcjt.cn/Article/details/gtciccvois.html

Ruby: File.exist?("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtuozpdehz.html

C#:   File.Exists("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtmffyekar.html

[F06] 删除文件
来源：http://dali.shzxlz.cn/Article/details/gtmipfobjk.html

Py:   os.remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtrmrsypmx.html

PHP:  unlink("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtkyrsohob.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gthbaamjwx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtevzszfow.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtvaqoiujm.html

Go:   os.Remove("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtqankywgl.html

Ruby: File.delete("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gttvbotimx.html

C#:   File.Delete("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtexoelmmz.html

[F07] 创建目录（含多级）
来源：http://dali.cucudq.cn/Article/details/gtforvfyjh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gtbojwvwbg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhixingplan.top/Article/details/gtkoavujyc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxcrvzwyt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gtxfibwcig.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.andypj.xyz/Article/details/gtqdbinkqm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinqigufen.top/Article/details/gtpovcalhv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj20258.top/Article/details/gtawuvcbdp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yonumen.top/Article/details/gtolsamymh.html

[F08] 遍历目录
来源：http://dali.zhongyouzk.top/Article/details/gtyxnshwko.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tianlin.xyz/Article/details/gtnjkgjxih.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmabqosyr.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj20258888.top/Article/details/gtzyrheonf.html

TS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gtsygjpqhs.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnqzz.top/Article/details/gtmxuxckis.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tian-w.cn/Article/details/gtuxiwjvax.html

Ruby: Dir.children("dir")
来源：http://dali.andypj.xyz/Article/details/gtkusfpmjc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gzhubu.top/Article/details/gtmkwzcshd.html

[F09] 获取文件大小
来源：http://dali.smart0.xyz/Article/details/gtpioslrdu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.c1oappe.top/Article/details/gthxlsifgf.html

PHP:  filesize("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtbcjgnsxx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangtech.top/Article/details/gtsrgvxrgc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gtnarnbtez.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtnrzolqfe.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tianlin.xyz/Article/details/gtftcqviof.html

Ruby: File.size("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtsfwrlzei.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yueranfly.top/Article/details/gtqeooobul.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hongshengwenyu.top/Article/details/gtydvduvor.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtiwzkhffv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtfdvdxtuh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtbbnrvlmp.html

TS:   path.extname("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtdioabctr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sxryk.cn/Article/details/gtkkosdueg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtbkpfelza.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtgemevbaz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtdunikawk.html

[F11] 复制与移动文件
来源：http://dali.hfpthk.cn/Article/details/gtpqvobcjo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtqamxfafh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gotoacloud.top/Article/details/gtjzedlhhe.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtoderngqc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtstwmfmbw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yongpay.top/Article/details/gtiyibswop.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sweek.top/Article/details/gtlsapbket.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtzkzoslcp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gththmxwrd.html

[F12] CSV 读写
来源：http://dali.vqdsnc.cn/Article/details/gtulgfnzve.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ivvv.top/Article/details/gtjugfuqza.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnqzz.top/Article/details/gtfcatfbdv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhongyouzk.top/Article/details/gtrnqehpwe.html

TS:   // 同上
来源：http://dali.hammf.cn/Article/details/gtywdjjybq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hysaishi.cn/Article/details/gtoqqrnosp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.iojbl.cn/Article/details/gtkukrrpru.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xinyue.icu/Article/details/gtkkavvtct.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xuetiantiany.cn/Article/details/gtedognsdr.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtzihnrleu.html

G. 面向对象
来源：http://dali.svipenyu.cn/Article/details/gtgsjbhile.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtfzmjtjjk.html

[G01] 定义类
来源：http://dali.shuidangran.top/Article/details/gtejhieuyc.html

Py:   class User: pass
来源：http://dali.bjfxy.top/Article/details/gtvhgtjrdh.html

PHP:  class User {}
来源：http://dali.jiagoushi.top/Article/details/gtolyyjmus.html

JS:   class User {}
来源：http://dali.gotoacloud.top/Article/details/gtobydtfjy.html

TS:   class User { name: string = ""; }
来源：http://dali.jlsjyb.cn/Article/details/gtcbmctqep.html

Java: class User {}
来源：http://dali.yj20258.top/Article/details/gtezeuuccl.html

Go:   type User struct { Name string }
来源：http://dali.zycfv.cn/Article/details/gthzcsayxb.html

Ruby: class User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gthkshrryf.html

C#:   class User {}
来源：http://dali.sysykeji.top/Article/details/gtmusvgxka.html

[G02] 构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxteblsda.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.iojbl.cn/Article/details/gtqynaouxu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnqzz.top/Article/details/gtplmnarbc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yongpay.top/Article/details/gtllowreki.html

TS:   constructor(public name: string) {}
来源：http://dali.ybcxt.top/Article/details/gtduukifgd.html

Java: User(String name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtuookwwin.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yueranfly.top/Article/details/gtvtuitlgj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjzgmfpco.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtzndbvzoi.html

[G03] 实例属性
来源：http://dali.chenlongwang.top/Article/details/gtcxuxmtfz.html

Py:   self.name = "x"
来源：http://dali.dianchejie.cn/Article/details/gtzraxhora.html

PHP:  public string $name = "x";
来源：http://dali.cqqwz.cn/Article/details/gtukofvkjk.html

JS:   this.name = "x";
来源：http://dali.hnqzz.top/Article/details/gtnoacxipj.html

TS:   name: string = "x";
来源：http://dali.ydzc1.top/Article/details/gtjstixjuu.html

Java: private String name;
来源：http://dali.pycfn.com/Article/details/gtjhswaqsu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258.top/Article/details/gtxtobocfv.html

Ruby: @name = "x"
来源：http://dali.nanxinkj.top/Article/details/gtoujfwvur.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ivvv.top/Article/details/gtbkujegbn.html

[G04] 定义方法
来源：http://dali.fzhhl.top/Article/details/gtpollqaib.html

Py:   def greet(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtueogijvj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gttoaezpuq.html

JS:   greet() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtrlcwtijz.html

TS:   greet(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtukotavwh.html

Java: String greet() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtgnytxwnx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtzmkmfczq.html

Ruby: def greet; @name; end
来源：http://dali.daxiang520.top/Article/details/gtdcdzpgfu.html

C#:   public string Greet() => Name;
来源：http://dali.ybcxt.top/Article/details/gthyrhmkyd.html

[G05] 继承
来源：http://dali.zycfv.cn/Article/details/gtodvuwsvp.html

Py:   class Admin(User): pass
来源：http://dali.xziqi.cn/Article/details/gtefezjjao.html

PHP:  class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtupfxebtb.html

JS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtkorrjbye.html

TS:   class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwektrtz.html

Java: class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtvmbyxtrg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pengpengdd.cyou/Article/details/gtsmdxesyf.html

Ruby: class Admin < User; end
来源：http://dali.chenjidiqi.icu/Article/details/gtklyotwan.html

C#:   class Admin : User {}
来源：http://dali.andypj.xyz/Article/details/gtvougrbjr.html

[G06] 重写方法
来源：http://dali.yj202588.top/Article/details/gtqppwyjsu.html

Py:   def greet(self): return "admin"
来源：http://dali.vqdsnc.cn/Article/details/gtcvlfkils.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtagbezhvc.html

JS:   greet() { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtmlmszzqz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gthjehxvli.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gthxmlmmre.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.havefunace.top/Article/details/gtcpaxlzeo.html

Ruby: def greet; "admin"; end
来源：http://dali.sxryk.cn/Article/details/gtkwuarojc.html

C#:   public override string Greet() => "admin";
来源：http://dali.haohaochexian.top/Article/details/gtbqyxrhrc.html

[G07] 调用父类方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtayiopvzg.html

Py:   super().greet()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqllqhlyy.html

PHP:  parent::greet();
来源：http://dali.snrcjt.cn/Article/details/gtosacwlbt.html

JS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gtuqbywyha.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gthbwslrog.html

Java: super.greet();
来源：http://dali.xinyue.icu/Article/details/gteaimiusx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuxming.cn/Article/details/gttptulxoi.html

Ruby: super
来源：http://dali.xuanzx.com/Article/details/gtkprluzvb.html

C#:   base.Greet();
来源：http://dali.sysykeji.top/Article/details/gtbnwljzpp.html

[G08] 静态方法与属性
来源：http://dali.redwolf501.top/Article/details/gtqdzlrisj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zycfv.cn/Article/details/gtaxyuenll.html

PHP:  public static function f() {}
来源：http://dali.iojbl.cn/Article/details/gtljiuwcyc.html

JS:   static f() {}
来源：http://dali.gogol.net.cn/Article/details/gtoubvposg.html

TS:   static f(): void {}
来源：http://dali.hammf.cn/Article/details/gtzvhswlgt.html

Java: static void f() {}
来源：http://dali.cheryme.top/Article/details/gtreuzstbw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xylfe.cn/Article/details/gtdvidiqnf.html

Ruby: def self.f; end
来源：http://dali.feifeiyinyue.top/Article/details/gthmustmuh.html

C#:   public static void F() {}
来源：http://dali.guannengcc.top/Article/details/gtibvigvkz.html

[G09] 接口 / 抽象类
来源：http://dali.hongshengwenyu.top/Article/details/gtrzsaeqwu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tanke756.top/Article/details/gtwxcikvbq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj202588.top/Article/details/gtkduimmdm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhoulong.xyz/Article/details/gtgggwmrey.html

TS:   interface Shape { area(): number; }
来源：http://dali.yuxming.cn/Article/details/gtjoccfjbl.html

Java: interface Shape { double area(); }
来源：http://dali.hywenlv.cn/Article/details/gtfgrtpocv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shzxlz.cn/Article/details/gtnsdxvkra.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sxryk.cn/Article/details/gtuguphdhh.html

C#:   interface IShape { double Area(); }
来源：http://dali.tianlin.xyz/Article/details/gthtkrubjj.html

[G10] 访问控制
来源：http://dali.yonumen.top/Article/details/gthutoprxa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dashuyun.cn/Article/details/gtqexsbhye.html

PHP:  public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gtpsrphftr.html

JS:   #private 字段；其余公开
来源：http://dali.tianlin.xyz/Article/details/gtiqrnidhz.html

TS:   public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtenmhokap.html

Java: public / protected / private / 默认包级
来源：http://dali.0kj1m.cn/Article/details/gtosuhtttc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hammf.cn/Article/details/gtankfsdle.html

Ruby: public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtmsfywiuy.html

C#:   public / protected / private / internal
来源：http://dali.daxiang520.top/Article/details/gtzzgtxfie.html

[G11] getter / setter
来源：http://dali.ehwqpu.com/Article/details/gthyjmdfeh.html

Py:   @property 与 @x.setter
来源：http://dali.xuanzx.com/Article/details/gtqnyvxdid.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtmkftznzj.html

JS:   get name() { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gtesvbqwso.html

TS:   get name(): string { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gttwjyupmf.html

Java: public String getName() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtmormjtpy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gtukjtzpbh.html

Ruby: attr_accessor :name
来源：http://dali.chenjidiqi.icu/Article/details/gtpywzxegw.html

C#:   public string Name { get; set; }
来源：http://dali.wangdashe.top/Article/details/gtjjapwpwu.html

[G12] 对象转字符串
来源：http://dali.dianchejie.cn/Article/details/gtfjwvgilh.html

Py:   def __str__(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gtuyvyvela.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtdrgysuqh.html

JS:   toString() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtwhwosmin.html

TS:   toString(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtlwjbamil.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxpfxpheb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtiouklzno.html

Ruby: def to_s; @name; end
来源：http://dali.316326.xyz/Article/details/gtlrolmygh.html

C#:   public override string ToString() => Name;
来源：http://dali.yanxiufei.cn/Article/details/gtceaatiyv.html

[G13] 判断对象类型
来源：http://dali.yonumen.top/Article/details/gturbpqfiv.html

Py:   isinstance(u, User)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmrflinvs.html

PHP:  $u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtmzcmrqdq.html

JS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtckqpnusn.html

TS:   u instanceof User
来源：http://dali.yonumen.top/Article/details/gtpbxwrgjq.html

Java: u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtshosfzdf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.birdmap.top/Article/details/gtfqxrwaoo.html

Ruby: u.is_a?(User)
来源：http://dali.shanyushiyangtech.top/Article/details/gtprcjekbn.html

C#:   u is User
来源：http://dali.xuanzx.com/Article/details/gthxlyinhj.html

[G14] 数据类 / record
来源：http://dali.hnqzz.top/Article/details/gtdlswdvvs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yanxiufei.cn/Article/details/gtgctkpbmy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zycfv.cn/Article/details/gtfhybqrth.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zycfv.cn/Article/details/gtcmxlnkss.html

TS:   type User = { name: string; age: number };
来源：http://dali.mhx1999.top/Article/details/gtydqcvhay.html

Java: record User(String name, int age) {}
来源：http://dali.aizwys.cn/Article/details/gtuymsisir.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gzhubu.top/Article/details/gtlidfwfvh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhiwuduotai.top/Article/details/gtgjmqhsfn.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxinkj.top/Article/details/gtyywzooid.html

[G15] 枚举
来源：http://dali.meibo888.top/Article/details/gtqkasnkaf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hongshengwenyu.top/Article/details/gtnfkdtlyw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.iojbl.cn/Article/details/gtfypdkxqg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jianghu66.top/Article/details/gttjbyrfge.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hysaishi.cn/Article/details/gtovxsvhdc.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuanzhike.top/Article/details/gtjshnovgg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.andypj.xyz/Article/details/gtxzkufdse.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ydzc1.top/Article/details/gtkseksbid.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtjjwaficu.html

[G16] 对象转数组 / 字典
来源：http://dali.yongpay.top/Article/details/gthpbvrtxt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gotoacloud.top/Article/details/gtkbanjqac.html

PHP:  get_object_vars($obj);
来源：http://dali.chenzaomai.com/Article/details/gtxdkxsiwj.html

JS:   Object.entries(obj)
来源：http://dali.tianlin.xyz/Article/details/gtajckccsl.html

TS:   Object.entries(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtynjiyolh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.9152youxi.cn/Article/details/gtacftxshx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinqigfzy.top/Article/details/gtmrwcvrdx.html

Ruby: obj.instance_variables
来源：http://dali.jinghuilouyu.cn/Article/details/gtzcpenrjm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj202588.top/Article/details/gtiyfrhbho.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtvapodvnm.html

H. 异常与错误处理
来源：http://dali.yj202588.top/Article/details/gtnitokqme.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtzdzfmsbc.html

[H01] try / catch 基础
来源：http://dali.yuanzhike.top/Article/details/gtzoxxxfgf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.andypj.xyz/Article/details/gtucsptkfd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtpbzkwnsc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gtmsmzamfw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gtsytaoeuj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shuidangran.top/Article/details/gtchnxnfiz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258.top/Article/details/gthekfqmlk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhongyouzk.top/Article/details/gtlbnkftnv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.meibo888.top/Article/details/gtfqdtzxkq.html

[H02] finally / ensure 收尾
来源：http://dali.sufxvd.cn/Article/details/gtpssrthxp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.guannengcc.top/Article/details/gtbcstxexw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtoxlatmab.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtwbcnltct.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtqawgaitd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtybbaezwv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gogol.net.cn/Article/details/gtucuqcggw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cashguo.top/Article/details/gtvwgasyjr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtxiawzncj.html

[H03] 主动抛出异常
来源：http://dali.yonumen.top/Article/details/gtaksrlcmd.html

Py:   raise ValueError("错误信息")
来源：http://dali.ppjwa.cn/Article/details/gtyjacgtka.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtznbbbkqd.html

JS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtsroyjygq.html

TS:   throw new Error("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtdacswhsm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gthknufgzi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.meibo888.top/Article/details/gtbhicqgan.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.vqdsnc.cn/Article/details/gteasvqirc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtwsspomol.html

[H04] 自定义异常类型
来源：http://dali.dashuyun.cn/Article/details/gtftqakpuc.html

Py:   class MyError(Exception): pass
来源：http://dali.aizwys.cn/Article/details/gtudgekkmi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gtdbcsalis.html

JS:   class MyError extends Error {}
来源：http://dali.hnxiangtu.top/Article/details/gtbzflqjht.html

TS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gtevfhngzp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gtknctnjno.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigufen.top/Article/details/gtvxyhsuxz.html

Ruby: class MyError < StandardError; end
来源：http://dali.gzhubu.top/Article/details/gtbynuaipv.html

C#:   class MyException : Exception {}
来源：http://dali.vqdsnc.cn/Article/details/gtblhhsvlc.html

[H05] 捕获特定类型
来源：http://dali.zhoulong.xyz/Article/details/gtmfghgkhk.html

Py:   except ValueError as e:
来源：http://dali.nanxuanxn.top/Article/details/gtccskuddw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.havefunace.top/Article/details/gtsnpemllh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gtsmgkpaux.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.dianchejie.cn/Article/details/gtodcucfee.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ehwqpu.com/Article/details/gtjtpiknfv.html


<!-- 参考信息 -->