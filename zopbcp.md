代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gtqvstomrx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sufxvd.cn/Article/details/gtesbyuifa.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.fzhhl.top/Article/details/gtxzxlkodo.html

Ruby: s.bytesize;  s.length
来源：http://dali.zycfv.cn/Article/details/gtgdjnkafx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gtnpflgfeh.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzparnelc.html

F. 文件与目录
来源：http://dali.jqgfzy.top/Article/details/gtkfvgxymw.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtbnkbhctm.html

[F01] 读取整个文件
来源：http://dali.jianghu66.top/Article/details/gtvmugquld.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigfzy.top/Article/details/gtjqtdcbaa.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtfmtkzpns.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ehwqpu.com/Article/details/gtllztkaco.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gttdgvmmra.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtcobemhbm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ydzc1.top/Article/details/gtckbsswko.html

Ruby: File.read("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtujyeckil.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtisexdvrg.html

[F02] 逐行读取文件
来源：http://dali.316326.xyz/Article/details/gtucvencnh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ybcxt.top/Article/details/gtnvwuwnsk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sufxvd.cn/Article/details/gtovjhwqjs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yangfankeji.com/Article/details/gtrrrwvhbq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gaohongyu789.top/Article/details/gttbshzhjh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqqfozpl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhoulong.xyz/Article/details/gtprplhgvq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdykywdg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dianchejie.cn/Article/details/gtlqxmkudx.html

[F03] 写入文件（覆盖）
来源：http://dali.kuanghao11.cn/Article/details/gtwocyqrof.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hywenlv.cn/Article/details/gtigtngbes.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gtvtloqhhp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gtplygbbwi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gtsprqonxq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.meibo888.top/Article/details/gtafuhzxny.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.daxiang520.top/Article/details/gtpqntaxrg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj20258.top/Article/details/gtavvwmuhl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gtfubwdelq.html

[F04] 追加写入文件
来源：http://dali.9152youxi.cn/Article/details/gtcwfaseay.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzypcxrwx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yonumen.top/Article/details/gtzgmevlac.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhengqikj.top/Article/details/gtxmauqvsd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pycfn.com/Article/details/gtpliclfrb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtemzdurkb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cdnleiting.top/Article/details/gtbzvjzaie.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xuanzx.com/Article/details/gtulzzvrbi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yangfankeji.com/Article/details/gtqrvnjwci.html

[F05] 判断文件或目录是否存在
来源：http://dali.shzxlz.cn/Article/details/gtdcokxkaq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gaohongyu789.top/Article/details/gtnfrgxngo.html

PHP:  file_exists("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtdtsbtbwf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtwzmdhtsv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtemzcbchm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtxcsmolqd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jyoumei.cn/Article/details/gtpbugsowy.html

Ruby: File.exist?("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtxfzxgoxr.html

C#:   File.Exists("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtzoyveigk.html

[F06] 删除文件
来源：http://dali.yanxiufei.cn/Article/details/gtfwzpvypy.html

Py:   os.remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gtigusdmld.html

PHP:  unlink("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gthadsvoye.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtufrvvulb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtmyhtcuyu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtmhjvjgjq.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdsntesxq.html

Ruby: File.delete("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtqlzmawlb.html

C#:   File.Delete("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtnjueyets.html

[F07] 创建目录（含多级）
来源：http://dali.jlsjyb.cn/Article/details/gtciffiywe.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xylfe.cn/Article/details/gteoqdupar.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.c1oappe.top/Article/details/gtpttivhdu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.feifeiyinyue.top/Article/details/gtnhazjitr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gtbfaliepz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gtiufrniib.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenlongwang.top/Article/details/gtxfovdglq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.0kj1m.cn/Article/details/gtbzbclkyl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvosjefnl.html

[F08] 遍历目录
来源：http://dali.jqgufenzy.top/Article/details/gtqoplgaqs.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.redwolf501.top/Article/details/gtnubijhgg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gtpbnvppet.html

JS:   fs.readdirSync("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtycuppqbx.html

TS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtxudhdton.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dashuyun.cn/Article/details/gttzdlqpqv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cheryme.top/Article/details/gtbqcamcio.html

Ruby: Dir.children("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtmlsbcsjj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhixingplan.top/Article/details/gtqhzzjkha.html

[F09] 获取文件大小
来源：http://dali.316326.xyz/Article/details/gtagjsvjif.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtdicrtqsf.html

PHP:  filesize("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gterqghxkm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tanke756.top/Article/details/gtcmlffnlt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jianghu66.top/Article/details/gtendmbssu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gthltglnle.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.redwolf501.top/Article/details/gtumzuztch.html

Ruby: File.size("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtlpxqageg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gotoacloud.top/Article/details/gtewpeoszt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sxryk.cn/Article/details/gteckxcbsg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtkneltrcl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hammf.cn/Article/details/gtuljsfxpi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtcnkpeygr.html

TS:   path.extname("a.txt")
来源：http://dali.daxiang520.top/Article/details/gthpmcuitf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hywenlv.cn/Article/details/gtilhwuwqx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtlzqnvwwl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtdbgtiliq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtjxcdqjsj.html

[F11] 复制与移动文件
来源：http://dali.snrcjt.cn/Article/details/gtyxbjvwbc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtftbazijl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhixingplan.top/Article/details/gttrvkofol.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtlyxyvcqf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtrdjntoke.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dashuyun.cn/Article/details/gtwopawruh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gaohongyu789.top/Article/details/gtpvxpispl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gtqkfnzdbb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shuidangran.top/Article/details/gtvqcavdpx.html

[F12] CSV 读写
来源：http://dali.sxryk.cn/Article/details/gtssdpchiz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nwbrower.top/Article/details/gtrsauizdo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.daxiang520.top/Article/details/gtrookurbw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.aibaodan.cn/Article/details/gtlontsqxt.html

TS:   // 同上
来源：http://dali.mhx1999.top/Article/details/gtmeoodzxw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuanzx.com/Article/details/gtlctjysjf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hongshengwenyu.top/Article/details/gtkzdgsqlw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.feifeiyinyue.top/Article/details/gtztskamdv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xziqi.cn/Article/details/gtahawqzxn.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtxzxojoow.html

G. 面向对象
来源：http://dali.fzhhl.top/Article/details/gtttvuronu.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtnuziohtd.html

[G01] 定义类
来源：http://dali.yuxming.cn/Article/details/gtkbtjeyah.html

Py:   class User: pass
来源：http://dali.yj20258.top/Article/details/gtgbpxzavo.html

PHP:  class User {}
来源：http://dali.sysykeji.top/Article/details/gtqgjjaxak.html

JS:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gtvnbcajhk.html

TS:   class User { name: string = ""; }
来源：http://dali.sufxvd.cn/Article/details/gtwynmhpuy.html

Java: class User {}
来源：http://dali.nwbrower.top/Article/details/gtkbfahawg.html

Go:   type User struct { Name string }
来源：http://dali.jqgufenzy.top/Article/details/gtayodbjgh.html

Ruby: class User; end
来源：http://dali.chenzaomai.com/Article/details/gtlzhsonlg.html

C#:   class User {}
来源：http://dali.cashguo.top/Article/details/gtfpzrdgnm.html

[G02] 构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtamraxzmq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hywenlv.cn/Article/details/gthygtqkwr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cucudq.cn/Article/details/gtesrefgfr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtdauadcjh.html

TS:   constructor(public name: string) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtmvhabxrf.html

Java: User(String name) { this.name = name; }
来源：http://dali.gotoacloud.top/Article/details/gtfwcblbth.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sweek.top/Article/details/gtsibvkskz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aizwys.cn/Article/details/gtadzrjkhq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xziqi.cn/Article/details/gtpqqlpdjf.html

[G03] 实例属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtogwksvwg.html

Py:   self.name = "x"
来源：http://dali.ydzc1.top/Article/details/gtvlqzcmfq.html

PHP:  public string $name = "x";
来源：http://dali.haohaochexian.top/Article/details/gtssdjoiof.html

JS:   this.name = "x";
来源：http://dali.snrcjt.cn/Article/details/gtcgnojsna.html

TS:   name: string = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjuboyaki.html

Java: private String name;
来源：http://dali.sweek.top/Article/details/gtgaomsuev.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sweek.top/Article/details/gtxalfytlz.html

Ruby: @name = "x"
来源：http://dali.vqdsnc.cn/Article/details/gtsdldodnq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.bjfxy.top/Article/details/gtcphkuinj.html

[G04] 定义方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbiwdlws.html

Py:   def greet(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gtdwwmhpmf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gtpaigcjht.html

JS:   greet() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gtbagoykqr.html

TS:   greet(): string { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtkmfalhvy.html

Java: String greet() { return name; }
来源：http://dali.hammf.cn/Article/details/gtdgsxkifz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtlqodmern.html

Ruby: def greet; @name; end
来源：http://dali.nanxinkj.top/Article/details/gtsdixbuqe.html

C#:   public string Greet() => Name;
来源：http://dali.bjfxy.top/Article/details/gtcrxnfabv.html

[G05] 继承
来源：http://dali.yueranfly.top/Article/details/gtzksufvba.html

Py:   class Admin(User): pass
来源：http://dali.feifeiyinyue.top/Article/details/gthsghzzlq.html

PHP:  class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtrpupnqej.html

JS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtghbbcgmh.html

TS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtqnoyrgdc.html

Java: class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtsundwkvg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hnqzz.top/Article/details/gttumdhcok.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gtdeukswld.html

C#:   class Admin : User {}
来源：http://dali.guowangkeji.top/Article/details/gtqjbztykw.html

[G06] 重写方法
来源：http://dali.yonumen.top/Article/details/gtwzijzzhq.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258888.top/Article/details/gtzptxaoqa.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtviizqfjh.html

JS:   greet() { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gteakggwbp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtmcuhlozf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtuabviolh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.haohaochexian.top/Article/details/gtzgyrgdko.html

Ruby: def greet; "admin"; end
来源：http://dali.0kj1m.cn/Article/details/gtzfyhetnh.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenlongwang.top/Article/details/gtzyjjjlre.html

[G07] 调用父类方法
来源：http://dali.ppjwa.cn/Article/details/gtnfkfbcpo.html

Py:   super().greet()
来源：http://dali.shuidangran.top/Article/details/gtdhcmerdz.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdnotihtu.html

JS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gthwyhgggh.html

TS:   super.greet();
来源：http://dali.hysaishi.cn/Article/details/gtkjgmhejz.html

Java: super.greet();
来源：http://dali.tianlin.xyz/Article/details/gtmixazxkx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.kuanghao11.cn/Article/details/gtupohxbrq.html

Ruby: super
来源：http://dali.haohaochexian.top/Article/details/gtwejkryzp.html

C#:   base.Greet();
来源：http://dali.sweek.top/Article/details/gtgmxslupm.html

[G08] 静态方法与属性
来源：http://dali.smart0.xyz/Article/details/gtiwswwoqi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jlsjyb.cn/Article/details/gtqtpvzzcv.html

PHP:  public static function f() {}
来源：http://dali.quarkkingdee.top/Article/details/gtwedecvmp.html

JS:   static f() {}
来源：http://dali.c1oappe.top/Article/details/gtqbvbcmhe.html

TS:   static f(): void {}
来源：http://dali.hfpthk.cn/Article/details/gtrqhkrnmf.html

Java: static void f() {}
来源：http://dali.sufxvd.cn/Article/details/gtpjydlbwd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cdnleiting.top/Article/details/gtgvubzxfr.html

Ruby: def self.f; end
来源：http://dali.shzxlz.cn/Article/details/gtuzzgtotf.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpptjyqo.html

[G09] 接口 / 抽象类
来源：http://dali.snrcjt.cn/Article/details/gtqjfxvnui.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgufenzy.top/Article/details/gtewnxdzoz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ydzc1.top/Article/details/gtemrfkhdh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yvedp.cn/Article/details/gtrhdimsjk.html

TS:   interface Shape { area(): number; }
来源：http://dali.xinyue.icu/Article/details/gtlxmdiyyf.html

Java: interface Shape { double area(); }
来源：http://dali.jqgfzy.top/Article/details/gtzbifqpub.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daria6918.cn/Article/details/gtdduprvgj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sufxvd.cn/Article/details/gtuuinrlyj.html

C#:   interface IShape { double Area(); }
来源：http://dali.sxryk.cn/Article/details/gtaxtatuxv.html

[G10] 访问控制
来源：http://dali.wangshuangyany.cn/Article/details/gtohlfcvlq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangtech.top/Article/details/gtjlyiwkig.html

PHP:  public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gtclvbhlnw.html

JS:   #private 字段；其余公开
来源：http://dali.yuanzhike.top/Article/details/gtgikaxste.html

TS:   public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gtseozvjwk.html

Java: public / protected / private / 默认包级
来源：http://dali.kuanghao11.cn/Article/details/gttzgkrgwy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.iojbl.cn/Article/details/gtrhxqltfz.html

Ruby: public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gtmnkpyuiw.html

C#:   public / protected / private / internal
来源：http://dali.xinyue.icu/Article/details/gtakkvjktl.html

[G11] getter / setter
来源：http://dali.nanxuanxn.top/Article/details/gtftybbnwh.html

Py:   @property 与 @x.setter
来源：http://dali.pengpengdd.cyou/Article/details/gtirlhjkky.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqmdmavaw.html

JS:   get name() { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gtlsqevxxd.html

TS:   get name(): string { return this._name; }
来源：http://dali.yvedp.cn/Article/details/gthksscqnq.html

Java: public String getName() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtktnzwvhx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtcpxmetom.html

Ruby: attr_accessor :name
来源：http://dali.jinghuilouyu.cn/Article/details/gtgiyxhfvp.html

C#:   public string Name { get; set; }
来源：http://dali.316326.xyz/Article/details/gtwxuiehwf.html

[G12] 对象转字符串
来源：http://dali.yueranfly.top/Article/details/gtvwytcqbq.html

Py:   def __str__(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gtuhgyykqm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtymzlwkff.html

JS:   toString() { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtytkvqrkr.html

TS:   toString(): string { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtqmqhzsbl.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtbsyvuhxd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gtfwszbano.html

Ruby: def to_s; @name; end
来源：http://dali.yj202588.top/Article/details/gtozlkgyyc.html

C#:   public override string ToString() => Name;
来源：http://dali.guannengcc.top/Article/details/gtevdxaqxw.html

[G13] 判断对象类型
来源：http://dali.birdmap.top/Article/details/gtqevtakiq.html

Py:   isinstance(u, User)
来源：http://dali.zhixingplan.top/Article/details/gtlimfqiqx.html

PHP:  $u instanceof User
来源：http://dali.yonumen.top/Article/details/gtzbietxnk.html

JS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtwqkjkvpk.html

TS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtpbvxwify.html

Java: u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtlupucvnv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.feifeiyinyue.top/Article/details/gtyowwmwhx.html

Ruby: u.is_a?(User)
来源：http://dali.shangyingyoupin.top/Article/details/gtdqdcjvnl.html

C#:   u is User
来源：http://dali.gzhubu.top/Article/details/gtowgccpdl.html

[G14] 数据类 / record
来源：http://dali.gaohongyu789.top/Article/details/gtogmrrvit.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xziqi.cn/Article/details/gthrepyjqu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenzaomai.com/Article/details/gtlkpabsva.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tianlin.xyz/Article/details/gtfqlfqacb.html

TS:   type User = { name: string; age: number };
来源：http://dali.mhx1999.top/Article/details/gtkfzqlxiq.html

Java: record User(String name, int age) {}
来源：http://dali.chenzaomai.com/Article/details/gthkapjblu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenzaomai.com/Article/details/gtpslboozl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nanxinkj.top/Article/details/gttviezdyn.html

C#:   record User(string Name, int Age);
来源：http://dali.yonumen.top/Article/details/gtghqamdxk.html

[G15] 枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvlrwlrn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiyxojeis.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.dianchejie.cn/Article/details/gtqftbjizl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.birdmap.top/Article/details/gtghsbbewr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtjafgiidk.html

Java: enum Color { RED, GREEN }
来源：http://dali.ehwqpu.com/Article/details/gtqjazicxc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shuidangran.top/Article/details/gtltfwyauk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shuidangran.top/Article/details/gtemdcuusp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gtnmnhowdr.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigufen.top/Article/details/gtqdpdpfyl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigufen.top/Article/details/gtfiwbrxsk.html

PHP:  get_object_vars($obj);
来源：http://dali.wangdashe.top/Article/details/gtdosyvdwf.html

JS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gtdkwqjfjs.html

TS:   Object.entries(obj)
来源：http://dali.redwolf501.top/Article/details/gtzmxyvvpo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.haohaochexian.top/Article/details/gtgforuiat.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenlongwang.top/Article/details/gtydzayojc.html

Ruby: obj.instance_variables
来源：http://dali.hfpthk.cn/Article/details/gtcukqplhg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gtwmtkrxbj.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtggknhpui.html

H. 异常与错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gtkczzbqlm.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtqzabzbpd.html

[H01] try / catch 基础
来源：http://dali.cucudq.cn/Article/details/gtsnasprsq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.wangdashe.top/Article/details/gtgztfnyyp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ppjwa.cn/Article/details/gtbzshxlmi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gtzchvgpuk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gtdbhmsyud.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aizwys.cn/Article/details/gttskxodoz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhongyouzk.top/Article/details/gtmofvrpgk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.c1oappe.top/Article/details/gtltwfblpi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.birdmap.top/Article/details/gtzdzgekjo.html

[H02] finally / ensure 收尾
来源：http://dali.jiagoushi.top/Article/details/gtgrnygwbb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shuidangran.top/Article/details/gtwtbyzovq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gthyrerksr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtegjgcpxp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtuhpqrczk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtrurmyelo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yueranfly.top/Article/details/gtxhfwlcvt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.316326.xyz/Article/details/gtpowommub.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtqmonqmov.html

[H03] 主动抛出异常
来源：http://dali.hysaishi.cn/Article/details/gtbzntogkm.html

Py:   raise ValueError("错误信息")
来源：http://dali.pengpengdd.cyou/Article/details/gtzihgnzic.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtxigwfsuy.html

JS:   throw new Error("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gthxfdgesp.html

TS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtfdcxyasn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtcrziemzn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sxryk.cn/Article/details/gtqwajhkil.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hywenlv.cn/Article/details/gtgdxdimvh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtkddvlewx.html

[H04] 自定义异常类型
来源：http://dali.yj202588.top/Article/details/gtdaoxtdtg.html

Py:   class MyError(Exception): pass
来源：http://dali.birdmap.top/Article/details/gtjxsvnuys.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gtmcutotiw.html

JS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtgxmmjw.html

TS:   class MyError extends Error {}
来源：http://dali.zhixingplan.top/Article/details/gtafuxgyob.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gtyhzlcugk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.feifeiyinyue.top/Article/details/gtsrbbbpoq.html


<!-- 参考信息 -->