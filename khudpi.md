代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxinkj.top/Article/details/gtbneamrhn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhongyouzk.top/Article/details/gtqipbdicd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.redwolf501.top/Article/details/gtvfqteqzo.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj202588.top/Article/details/gtkezvmufi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenzaomai.com/Article/details/gtwrmrpedq.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtvrkidlfr.html

F. 文件与目录
来源：http://dali.meibo888.top/Article/details/gtvjznonep.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtqutswjbu.html

[F01] 读取整个文件
来源：http://dali.smart0.xyz/Article/details/gtviyoscqt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jiagoushi.top/Article/details/gtqoslpvui.html

PHP:  file_get_contents("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtyhdbybcs.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xylfe.cn/Article/details/gtztxagpfx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gthgpoeden.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gtpysxgsva.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.bjfxy.top/Article/details/gtuxzlslif.html

Ruby: File.read("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtoobenuoi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtidyvnfym.html

[F02] 逐行读取文件
来源：http://dali.jinghuilouyu.cn/Article/details/gthxpwwkje.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tanke756.top/Article/details/gtbqqjdvgc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangdashe.top/Article/details/gtbqhpyqbg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hysaishi.cn/Article/details/gtnofpvvod.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daxiang520.top/Article/details/gtzzammzso.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tian-w.cn/Article/details/gtccjebbbz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hnxiangtu.top/Article/details/gtvoyrjwlr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gzhubu.top/Article/details/gtpqoarrzh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.kuanghao11.cn/Article/details/gtsiyiqpyi.html

[F03] 写入文件（覆盖）
来源：http://dali.cashguo.top/Article/details/gthtwzmubg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zdqjudy.top/Article/details/gtapzvyqof.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gtpxjewfht.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtkxlpvudg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gtjqlfljgp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yonumen.top/Article/details/gtpvsrkgss.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cdnleiting.top/Article/details/gtpwmdgrlt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guannengcc.top/Article/details/gtnpcmrsip.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gtkvjiniiq.html

[F04] 追加写入文件
来源：http://dali.chenzaomai.com/Article/details/gtildtxxxr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cqqwz.cn/Article/details/gtpfjqzyia.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ehwqpu.com/Article/details/gtcsbwfwjs.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gtpsppcfbq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangdashe.top/Article/details/gtywsbffvh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.dashuyun.cn/Article/details/gtagvogsxn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ppjwa.cn/Article/details/gtqkhxtywf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shzxlz.cn/Article/details/gtygcgbcst.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yuxming.cn/Article/details/gtrpwtrmjt.html

[F05] 判断文件或目录是否存在
来源：http://dali.yanxiufei.cn/Article/details/gtywtcvcfi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnqzz.top/Article/details/gtzrrfrnfw.html

PHP:  file_exists("a.txt");
来源：http://dali.316326.xyz/Article/details/gtvlkvokgd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gthvqgpmnl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtlcjmgzeh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtemdpbfoy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmcwdmjec.html

Ruby: File.exist?("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtwakjmhvq.html

C#:   File.Exists("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtmsunjnqw.html

[F06] 删除文件
来源：http://dali.daria6918.cn/Article/details/gtvnbrxtfe.html

Py:   os.remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gttkjhqgyh.html

PHP:  unlink("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtkuqxksut.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtjbgwqcvy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtcaopyrzq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gteoredecc.html

Go:   os.Remove("a.txt")
来源：http://dali.hammf.cn/Article/details/gtqzojiygx.html

Ruby: File.delete("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtzdkzzieh.html

C#:   File.Delete("a.txt");
来源：http://dali.yonumen.top/Article/details/gtnyqzoibz.html

[F07] 创建目录（含多级）
来源：http://dali.hysaishi.cn/Article/details/gtcqvzcarb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.mhx1999.top/Article/details/gtodwjstec.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tanke756.top/Article/details/gtzezqspym.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gotoacloud.top/Article/details/gtricbdosc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gtunxcnyet.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hammf.cn/Article/details/gtcqwcbcou.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yuxming.cn/Article/details/gtnbxhrfjj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xinyue.icu/Article/details/gtyyddcica.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinqigufen.top/Article/details/gthtpnjpiz.html

[F08] 遍历目录
来源：http://dali.ybcxt.top/Article/details/gtwxwfxsmk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tianlin.xyz/Article/details/gtlxmlktns.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yongpay.top/Article/details/gtcaepyzis.html

JS:   fs.readdirSync("dir")
来源：http://dali.shuidangran.top/Article/details/gtrivopvgt.html

TS:   fs.readdirSync("dir")
来源：http://dali.hysaishi.cn/Article/details/gtslqlcldl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gtcswunojh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.aizwys.cn/Article/details/gtulnnuevz.html

Ruby: Dir.children("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtmoxzxbht.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuanzhike.top/Article/details/gtusbcbqeb.html

[F09] 获取文件大小
来源：http://dali.shzxlz.cn/Article/details/gtirytcrnr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtyxjmbuji.html

PHP:  filesize("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtzsywxmqf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sysykeji.top/Article/details/gtjbjmgjgy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkrdhflfs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtmjgaipdp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sufxvd.cn/Article/details/gtnhtlmjfl.html

Ruby: File.size("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtydgssskg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ivvv.top/Article/details/gtsiwdrgsg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zdqjudy.top/Article/details/gtcewinedz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtzuletjbi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtaftaaaci.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtvqhsxkbk.html

TS:   path.extname("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtlhbrfygb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cqqwz.cn/Article/details/gtexljnfut.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndovqtab.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtnxeqgrks.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtugxchnuz.html

[F11] 复制与移动文件
来源：http://dali.yj202588.top/Article/details/gtzfmwdmqm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtksrlqxei.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.aizwys.cn/Article/details/gtykiajsxs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gttmojidst.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtgdscjwzk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.snrcjt.cn/Article/details/gtgghqifog.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhixingplan.top/Article/details/gtzrtqsghi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtcctnksca.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuanzx.com/Article/details/gtkwszoqya.html

[F12] CSV 读写
来源：http://dali.pycfn.com/Article/details/gtzrtrxtgd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shangyingyoupin.top/Article/details/gtsmindgcl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.dianchejie.cn/Article/details/gterpgjaof.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hfpthk.cn/Article/details/gtlxnuhnbb.html

TS:   // 同上
来源：http://dali.zdqjudy.top/Article/details/gtqydydmac.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yongpay.top/Article/details/gtpvstdzvy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zdqjudy.top/Article/details/gtthmqwatd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hywenlv.cn/Article/details/gtlgprynrq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nanxuanxn.top/Article/details/gtaakiktfx.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtxgemodqv.html

G. 面向对象
来源：http://dali.yonumen.top/Article/details/gtiivqsdjj.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtholsfcaj.html

[G01] 定义类
来源：http://dali.wangshuangyany.cn/Article/details/gtqjiqhsnk.html

Py:   class User: pass
来源：http://dali.jinqigfzy.top/Article/details/gtvtpeniii.html

PHP:  class User {}
来源：http://dali.chenlongwang.top/Article/details/gttawaukqu.html

JS:   class User {}
来源：http://dali.c1oappe.top/Article/details/gtylfkzhpk.html

TS:   class User { name: string = ""; }
来源：http://dali.tanke756.top/Article/details/gthxoupwhi.html

Java: class User {}
来源：http://dali.yj20258.top/Article/details/gtodlnponj.html

Go:   type User struct { Name string }
来源：http://dali.shzxlz.cn/Article/details/gtebkyqhhb.html

Ruby: class User; end
来源：http://dali.jianghu66.top/Article/details/gtzpyhipcs.html

C#:   class User {}
来源：http://dali.yuxming.cn/Article/details/gtkxeksnxb.html

[G02] 构造函数
来源：http://dali.xinyue.icu/Article/details/gtnzxujvmn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.havefunace.top/Article/details/gtmvhashat.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtodpervtn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gtqcqlxejs.html

TS:   constructor(public name: string) {}
来源：http://dali.pycfn.com/Article/details/gtwnohhnjo.html

Java: User(String name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtnszropmx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sxryk.cn/Article/details/gttgqbrpyp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtulicdcmi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtphzalaps.html

[G03] 实例属性
来源：http://dali.sysykeji.top/Article/details/gtsovhbrjd.html

Py:   self.name = "x"
来源：http://dali.yj202588.top/Article/details/gtpjxvqtjr.html

PHP:  public string $name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwvrmyvn.html

JS:   this.name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtxkneyirn.html

TS:   name: string = "x";
来源：http://dali.smart0.xyz/Article/details/gtajksrvih.html

Java: private String name;
来源：http://dali.fengsongda.top/Article/details/gtfebvtcsn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ppjwa.cn/Article/details/gtszkihgkh.html

Ruby: @name = "x"
来源：http://dali.hongshengwenyu.top/Article/details/gtcvfcblft.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aizwys.cn/Article/details/gtwhpmmsja.html

[G04] 定义方法
来源：http://dali.yonumen.top/Article/details/gtvxqstzad.html

Py:   def greet(self): return self.name
来源：http://dali.birdmap.top/Article/details/gtiytyswwz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gtvytvlvkt.html

JS:   greet() { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtxhlvwgcr.html

TS:   greet(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gttdyshbjp.html

Java: String greet() { return name; }
来源：http://dali.yueranfly.top/Article/details/gtlkhyktea.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtkogpvxfi.html

Ruby: def greet; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gtqitadnir.html

C#:   public string Greet() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gtxzzfcmfn.html

[G05] 继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjyhlltgr.html

Py:   class Admin(User): pass
来源：http://dali.jqgfzy.top/Article/details/gttugfdrdr.html

PHP:  class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtgjqiaqef.html

JS:   class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtfzyjrcuq.html

TS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtwtmliagh.html

Java: class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtwnqhqopl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.smart0.xyz/Article/details/gttwdnneok.html

Ruby: class Admin < User; end
来源：http://dali.aibaodan.cn/Article/details/gtqcopvpzf.html

C#:   class Admin : User {}
来源：http://dali.jlsjyb.cn/Article/details/gtdeoypcfc.html

[G06] 重写方法
来源：http://dali.bjfxy.top/Article/details/gtzrlpybzh.html

Py:   def greet(self): return "admin"
来源：http://dali.jqgfzy.top/Article/details/gtxwsrclde.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtnpxtvpja.html

JS:   greet() { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gticnwsymv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtfsgdidgm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtwrhtfvib.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.kuanghao11.cn/Article/details/gtyzytclpr.html

Ruby: def greet; "admin"; end
来源：http://dali.pengpengdd.cyou/Article/details/gtamjmqvgd.html

C#:   public override string Greet() => "admin";
来源：http://dali.havefunace.top/Article/details/gtznzaqpdz.html

[G07] 调用父类方法
来源：http://dali.daria6918.cn/Article/details/gtozmqhkow.html

Py:   super().greet()
来源：http://dali.zhoulong.xyz/Article/details/gtcxruuwgs.html

PHP:  parent::greet();
来源：http://dali.tian-w.cn/Article/details/gtlmtqmirk.html

JS:   super.greet();
来源：http://dali.chenlongwang.top/Article/details/gtqlcehzfa.html

TS:   super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtflxmqofj.html

Java: super.greet();
来源：http://dali.yvedp.cn/Article/details/gtvpnvzlgu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yongpay.top/Article/details/gtjyibpvhk.html

Ruby: super
来源：http://dali.bjfxy.top/Article/details/gtqcxwpnoa.html

C#:   base.Greet();
来源：http://dali.jinqigufen.top/Article/details/gtrtneedxq.html

[G08] 静态方法与属性
来源：http://dali.cdnleiting.top/Article/details/gtngxutbra.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tianlin.xyz/Article/details/gtendeddpb.html

PHP:  public static function f() {}
来源：http://dali.yangfankeji.com/Article/details/gticeawtye.html

JS:   static f() {}
来源：http://dali.xinyue.icu/Article/details/gtkznygzva.html

TS:   static f(): void {}
来源：http://dali.chenjidiqi.icu/Article/details/gtyfgblbig.html

Java: static void f() {}
来源：http://dali.hfpthk.cn/Article/details/gtxiqvafvt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ybcxt.top/Article/details/gtzpuaugpk.html

Ruby: def self.f; end
来源：http://dali.yvedp.cn/Article/details/gtalluaglz.html

C#:   public static void F() {}
来源：http://dali.tianlin.xyz/Article/details/gtgcbqfqkv.html

[G09] 接口 / 抽象类
来源：http://dali.feifeiyinyue.top/Article/details/gtlzlgtyak.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.aizwys.cn/Article/details/gtinatcteq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gotoacloud.top/Article/details/gtnfluurvu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shangyingyoupin.top/Article/details/gtbkzscslh.html

TS:   interface Shape { area(): number; }
来源：http://dali.shangyingyoupin.top/Article/details/gtgmqyyciv.html

Java: interface Shape { double area(); }
来源：http://dali.zdqjudy.top/Article/details/gtbhunnlox.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guannengcc.top/Article/details/gtomebqypo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aizwys.cn/Article/details/gtwivbwqdx.html

C#:   interface IShape { double Area(); }
来源：http://dali.gotoacloud.top/Article/details/gtikfusurf.html

[G10] 访问控制
来源：http://dali.hammf.cn/Article/details/gtvxntdiup.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.birdmap.top/Article/details/gtsdwrzlud.html

PHP:  public / protected / private
来源：http://dali.tanke756.top/Article/details/gtroijpfsz.html

JS:   #private 字段；其余公开
来源：http://dali.c1oappe.top/Article/details/gtmqhkbmav.html

TS:   public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtkyhehwlr.html

Java: public / protected / private / 默认包级
来源：http://dali.quarkkingdee.top/Article/details/gtntmlllww.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.feifeiyinyue.top/Article/details/gtxofvjvzt.html

Ruby: public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gthhvbzoqi.html

C#:   public / protected / private / internal
来源：http://dali.yuanzhike.top/Article/details/gtydptcicw.html

[G11] getter / setter
来源：http://dali.havefunace.top/Article/details/gtygkaomob.html

Py:   @property 与 @x.setter
来源：http://dali.pycfn.com/Article/details/gtlxddcqmm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gtokodhrxh.html

JS:   get name() { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gtkyujwlkd.html

TS:   get name(): string { return this._name; }
来源：http://dali.ehwqpu.com/Article/details/gtsjautwgo.html

Java: public String getName() { return name; }
来源：http://dali.yj20258.top/Article/details/gtwhhdkmpq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gtyjxotxqr.html

Ruby: attr_accessor :name
来源：http://dali.shanyushiyangtech.top/Article/details/gtznsfrvwc.html

C#:   public string Name { get; set; }
来源：http://dali.wangshuangyany.cn/Article/details/gtusdzqspd.html

[G12] 对象转字符串
来源：http://dali.haohaochexian.top/Article/details/gtirdnqgud.html

Py:   def __str__(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gtxwekoccs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtngiffwdy.html

JS:   toString() { return this.name; }
来源：http://dali.sweek.top/Article/details/gthdsmtkah.html

TS:   toString(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtglttmqzi.html

Java: @Override public String toString() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtglyqxazn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjrnbckf.html

Ruby: def to_s; @name; end
来源：http://dali.daxiang520.top/Article/details/gtkrnowxph.html

C#:   public override string ToString() => Name;
来源：http://dali.yanxiufei.cn/Article/details/gtlsqfsowq.html

[G13] 判断对象类型
来源：http://dali.hnxiangtu.top/Article/details/gtbccqlmnk.html

Py:   isinstance(u, User)
来源：http://dali.0kj1m.cn/Article/details/gtaenlbsxx.html

PHP:  $u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtjsudqdwr.html

JS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gtagehtzza.html

TS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtynfggxjz.html

Java: u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtahosfxcl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhixingplan.top/Article/details/gtdvwntzgf.html

Ruby: u.is_a?(User)
来源：http://dali.gogol.net.cn/Article/details/gtfqftgumt.html

C#:   u is User
来源：http://dali.hongshengwenyu.top/Article/details/gtoyoacsbm.html

[G14] 数据类 / record
来源：http://dali.smart0.xyz/Article/details/gtbsriprsr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhixingplan.top/Article/details/gtnolhmegm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hysaishi.cn/Article/details/gtvaujdvvc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hfpthk.cn/Article/details/gtkowkipxc.html

TS:   type User = { name: string; age: number };
来源：http://dali.zycfv.cn/Article/details/gtbonpyvpv.html

Java: record User(String name, int age) {}
来源：http://dali.jinqigfzy.top/Article/details/gtzdellzqd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pengpengdd.cyou/Article/details/gtsacnyarr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cheryme.top/Article/details/gturovsdtq.html

C#:   record User(string Name, int Age);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcdgcconc.html

[G15] 枚举
来源：http://dali.c1oappe.top/Article/details/gttvkrfmpv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.9152youxi.cn/Article/details/gtqdsevblf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhengqikj.top/Article/details/gtcfxhgpuc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.guowangkeji.top/Article/details/gtovirnqcd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.c1oappe.top/Article/details/gtwewzgkic.html

Java: enum Color { RED, GREEN }
来源：http://dali.sxryk.cn/Article/details/gtsnbtjijc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cucudq.cn/Article/details/gtbnhcjwff.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cheryme.top/Article/details/gtkjwxxzej.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gtsbgtbsqw.html

[G16] 对象转数组 / 字典
来源：http://dali.chenlongwang.top/Article/details/gtzxjwxcmt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yonumen.top/Article/details/gtnylsggsk.html

PHP:  get_object_vars($obj);
来源：http://dali.gotoacloud.top/Article/details/gtptivtqgg.html

JS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtyjgzreao.html

TS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gtvazdixgr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.birdmap.top/Article/details/gtixervxlf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.9152youxi.cn/Article/details/gtcysncili.html

Ruby: obj.instance_variables
来源：http://dali.9152youxi.cn/Article/details/gtryqkfkam.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrfdfvolk.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtldmhfclj.html

H. 异常与错误处理
来源：http://dali.nwbrower.top/Article/details/gtlztfcsae.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtutksyeki.html

[H01] try / catch 基础
来源：http://dali.xylfe.cn/Article/details/gtxpfbkzug.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.9152youxi.cn/Article/details/gtmqcebddi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guowangkeji.top/Article/details/gtaerwnbwt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gotoacloud.top/Article/details/gthrndlbix.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtdvysukrq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hongshengwenyu.top/Article/details/gtvxmsznnp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ivvv.top/Article/details/gtlyzpuwsa.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tian-w.cn/Article/details/gtwgtetdkv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.9152youxi.cn/Article/details/gtlrjssfay.html

[H02] finally / ensure 收尾
来源：http://dali.jlsjyb.cn/Article/details/gttnxsqolf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fzhhl.top/Article/details/gthkxxqzax.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtjsrlkqwq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtgjriiipj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtltiaeqzb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtjplgecym.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jyoumei.cn/Article/details/gtbxoolrif.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.c1oappe.top/Article/details/gteygdzxzi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtqltiaqmd.html

[H03] 主动抛出异常
来源：http://dali.shangyingyoupin.top/Article/details/gtbogynztg.html

Py:   raise ValueError("错误信息")
来源：http://dali.fengsongda.top/Article/details/gteefvytpp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtkvvpgosq.html

JS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtnwionzht.html

TS:   throw new Error("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtqitunucp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gthvziocqt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuanzx.com/Article/details/gtyobhliff.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cdnleiting.top/Article/details/gtoyfoizvj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtivzpwsgw.html

[H04] 自定义异常类型
来源：http://dali.nanxuanxn.top/Article/details/gtiqyaqgld.html

Py:   class MyError(Exception): pass
来源：http://dali.bjfxy.top/Article/details/gtwybwdstu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gtidppecan.html

JS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gtfkjqghna.html

TS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gtheacmrxw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gtykbihqkj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yueranfly.top/Article/details/gtgpizhhto.html


<!-- 参考信息 -->