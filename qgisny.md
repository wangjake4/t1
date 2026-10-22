代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtyrqzrwnq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cucudq.cn/Article/details/gthfgomzkn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gteqlwljoj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gttaxvpent.html

[E22] 字节长度与字符长度
来源：http://dali.sysykeji.top/Article/details/gttfugipuc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinqigufen.top/Article/details/gtbavnqfzi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtqdoyhyvf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenlongwang.top/Article/details/gtjayhwkmq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daxiang520.top/Article/details/gttjrbpmnk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jqgufenzy.top/Article/details/gtmmzwnswj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrrgezvc.html

Ruby: s.bytesize;  s.length
来源：http://dali.9152youxi.cn/Article/details/gtdettkquq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yonumen.top/Article/details/gttqhsvije.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtgckxspae.html

F. 文件与目录
来源：http://dali.yuanzhike.top/Article/details/gtbsveorwa.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtrdwffujy.html

[F01] 读取整个文件
来源：http://dali.cheryme.top/Article/details/gteialwryx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gogol.net.cn/Article/details/gtdclfreqo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ivvv.top/Article/details/gtxayekydm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cheryme.top/Article/details/gtyzdmelys.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.guannengcc.top/Article/details/gtaalozdwf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtlbvkerjq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvqxujhtu.html

Ruby: File.read("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtihhfwaej.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkywhmliy.html

[F02] 逐行读取文件
来源：http://dali.haohaochexian.top/Article/details/gtlajzirsu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenjidiqi.icu/Article/details/gtvybkrxme.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.daxiang520.top/Article/details/gtxbhcdyte.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cqqwz.cn/Article/details/gtptpcxrck.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhongyouzk.top/Article/details/gtxpdxlefq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj20258888.top/Article/details/gtzmoiteht.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.dianchejie.cn/Article/details/gtglocmgvi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.snrcjt.cn/Article/details/gtmaicqpkx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhoulong.xyz/Article/details/gtolbmsmrg.html

[F03] 写入文件（覆盖）
来源：http://dali.nanxinkj.top/Article/details/gtbmmeassa.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hywenlv.cn/Article/details/gtcfzknuwa.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gtyoaybbyk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gtqylcwopo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtguebbpdf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tanke756.top/Article/details/gtupqvlrjb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xylfe.cn/Article/details/gtqawycxlr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jyoumei.cn/Article/details/gtkkphoddv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hnxiangtu.top/Article/details/gttuyptlkx.html

[F04] 追加写入文件
来源：http://dali.vqdsnc.cn/Article/details/gtyusexiwe.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sysykeji.top/Article/details/gtkxjbffwp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zdqjudy.top/Article/details/gtylgvyzlr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gtbytnkhcw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hfpthk.cn/Article/details/gtswuyvnkm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ivvv.top/Article/details/gtuhueowfn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.havefunace.top/Article/details/gtkdsfseag.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.smart0.xyz/Article/details/gtypgfwxbd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tianlin.xyz/Article/details/gtnzciuxnj.html

[F05] 判断文件或目录是否存在
来源：http://dali.havefunace.top/Article/details/gtynmrurfz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gotoacloud.top/Article/details/gtlhqkptom.html

PHP:  file_exists("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtiskrbksx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdcudswaw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtzyqprcdj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtsvyipnln.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.quarkkingdee.top/Article/details/gtormdefjp.html

Ruby: File.exist?("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtvdjolxwo.html

C#:   File.Exists("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtwibpkdgw.html

[F06] 删除文件
来源：http://dali.birdmap.top/Article/details/gtumrjxpje.html

Py:   os.remove("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtedaxrmqc.html

PHP:  unlink("a.txt");
来源：http://dali.316326.xyz/Article/details/gtlgcvxbcl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtsgrtchri.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gthvcocpyf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtgahtfwup.html

Go:   os.Remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gtqwlabyjd.html

Ruby: File.delete("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtwwmbzzyq.html

C#:   File.Delete("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gterkylqrm.html

[F07] 创建目录（含多级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwadufatt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tian-w.cn/Article/details/gtpseslcnl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxinkj.top/Article/details/gtgnhurzmd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.birdmap.top/Article/details/gtiljgntsj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guannengcc.top/Article/details/gtowzusygq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yongpay.top/Article/details/gtjugrxhej.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yvedp.cn/Article/details/gthruoykxz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cheryme.top/Article/details/gtgutplaiq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gzhubu.top/Article/details/gtizslbgjh.html

[F08] 遍历目录
来源：http://dali.haohaochexian.top/Article/details/gtrekmfamq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jyoumei.cn/Article/details/gthrrnddow.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.birdmap.top/Article/details/gthhlcizfq.html

JS:   fs.readdirSync("dir")
来源：http://dali.pycfn.com/Article/details/gtqxvdxaut.html

TS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtopeoehnz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhixingplan.top/Article/details/gtzvncpvxu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gzhubu.top/Article/details/gtcnuhnkyk.html

Ruby: Dir.children("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhvgrwpt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tanke756.top/Article/details/gtqnwoqljf.html

[F09] 获取文件大小
来源：http://dali.yuanzhike.top/Article/details/gthnqkrtfs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtvhalaxpw.html

PHP:  filesize("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gthygsgrfo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.guowangkeji.top/Article/details/gtiycqdxoq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gtyfqfnxgw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtnuhabzly.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.havefunace.top/Article/details/gtqnghzgcc.html

Ruby: File.size("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gttltppfkf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nanxuanxn.top/Article/details/gtcmfaozji.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ywan-chungtsiang.top/Article/details/gtatljlqzv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gthyrgfuqi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cucudq.cn/Article/details/gtvlfpdbbi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtqdgiawbb.html

TS:   path.extname("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtvfvulurd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aizwys.cn/Article/details/gtrpcavdzb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtwnjigshg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtylyoquug.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtfdbnaqtm.html

[F11] 复制与移动文件
来源：http://dali.aibaodan.cn/Article/details/gtvunswsdc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtcfmtjnzw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhengqikj.top/Article/details/gtpwzimzll.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtiyfojfzg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtdivgonqi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jiagoushi.top/Article/details/gtkejhmapn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cucudq.cn/Article/details/gtsrvnefef.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtpxxkzpzr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cashguo.top/Article/details/gtvyxyztox.html

[F12] CSV 读写
来源：http://dali.cheryme.top/Article/details/gthmbdejct.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.havefunace.top/Article/details/gtqedcrzlw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guowangkeji.top/Article/details/gtvslxzomg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.svipenyu.cn/Article/details/gtzltnqgjw.html

TS:   // 同上
来源：http://dali.fzhhl.top/Article/details/gtqbdgrfud.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.bjfxy.top/Article/details/gtihykstlq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenjidiqi.icu/Article/details/gtcafbvczh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhengqikj.top/Article/details/gtxyuvykuh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gogol.net.cn/Article/details/gtslvjrxrn.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtxybahlhh.html

G. 面向对象
来源：http://dali.xziqi.cn/Article/details/gtyqehmwwz.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtrxuvtcob.html

[G01] 定义类
来源：http://dali.kuanghao11.cn/Article/details/gtqxzcxofx.html

Py:   class User: pass
来源：http://dali.sxryk.cn/Article/details/gtpspojsaz.html

PHP:  class User {}
来源：http://dali.guowangkeji.top/Article/details/gtvoemfusr.html

JS:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gtstmwkwxk.html

TS:   class User { name: string = ""; }
来源：http://dali.aizwys.cn/Article/details/gtoswewctl.html

Java: class User {}
来源：http://dali.xylfe.cn/Article/details/gttgqbzdjc.html

Go:   type User struct { Name string }
来源：http://dali.jlsjyb.cn/Article/details/gtyiqqyins.html

Ruby: class User; end
来源：http://dali.jinqigfzy.top/Article/details/gtqkoeupsw.html

C#:   class User {}
来源：http://dali.yvedp.cn/Article/details/gtlxvvljkb.html

[G02] 构造函数
来源：http://dali.hnqzz.top/Article/details/gtahsrbnnj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhengqikj.top/Article/details/gtnbjmnzqr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fengsongda.top/Article/details/gtzxmflxky.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtejuplrqv.html

TS:   constructor(public name: string) {}
来源：http://dali.hnxiangtu.top/Article/details/gtngkqjfnf.html

Java: User(String name) { this.name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtxaayltca.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnxiangtu.top/Article/details/gtenfimkza.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dianchejie.cn/Article/details/gtlqhakqsq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtydqxmcvs.html

[G03] 实例属性
来源：http://dali.jinqigfzy.top/Article/details/gtsgeacsyt.html

Py:   self.name = "x"
来源：http://dali.chenzaomai.com/Article/details/gtrzadmfay.html

PHP:  public string $name = "x";
来源：http://dali.birdmap.top/Article/details/gtxrqmhmls.html

JS:   this.name = "x";
来源：http://dali.guowangkeji.top/Article/details/gtogjnsjju.html

TS:   name: string = "x";
来源：http://dali.yueranfly.top/Article/details/gttmryuvsb.html

Java: private String name;
来源：http://dali.daria6918.cn/Article/details/gtxzeyxsga.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.0kj1m.cn/Article/details/gtbkzkiord.html

Ruby: @name = "x"
来源：http://dali.dianchejie.cn/Article/details/gtblfuwoai.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtrltwocos.html

[G04] 定义方法
来源：http://dali.zhengqikj.top/Article/details/gthxjzkoes.html

Py:   def greet(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gtfgpycfoh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gtyiryiqip.html

JS:   greet() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtxobeveyo.html

TS:   greet(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtfjpbsdtv.html

Java: String greet() { return name; }
来源：http://dali.yvedp.cn/Article/details/gtpwpioylq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gtkdotnofq.html

Ruby: def greet; @name; end
来源：http://dali.c1oappe.top/Article/details/gtpchyrlqo.html

C#:   public string Greet() => Name;
来源：http://dali.pycfn.com/Article/details/gteqdhpgeb.html

[G05] 继承
来源：http://dali.yj20258.top/Article/details/gtkglrstdd.html

Py:   class Admin(User): pass
来源：http://dali.chenlongwang.top/Article/details/gtqmilkxbv.html

PHP:  class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtwqsrvmlm.html

JS:   class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtuthorlhb.html

TS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtkdnlnvld.html

Java: class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtbihswutq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.fengsongda.top/Article/details/gtboqnjqtp.html

Ruby: class Admin < User; end
来源：http://dali.pycfn.com/Article/details/gttcnobjwo.html

C#:   class Admin : User {}
来源：http://dali.cashguo.top/Article/details/gtogonupxd.html

[G06] 重写方法
来源：http://dali.shangyingyoupin.top/Article/details/gtfbejunsb.html

Py:   def greet(self): return "admin"
来源：http://dali.redwolf501.top/Article/details/gtbupwpikv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtqslodoks.html

JS:   greet() { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtxvtelmkw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtlcqtjosq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtelkrgivc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cheryme.top/Article/details/gtrlnngyyq.html

Ruby: def greet; "admin"; end
来源：http://dali.jqgfzy.top/Article/details/gtovczloqd.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhoulong.xyz/Article/details/gtpquerbrs.html

[G07] 调用父类方法
来源：http://dali.yongpay.top/Article/details/gtliajoyvp.html

Py:   super().greet()
来源：http://dali.sufxvd.cn/Article/details/gttcywpkdy.html

PHP:  parent::greet();
来源：http://dali.ybcxt.top/Article/details/gtjucrrdwx.html

JS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gtnztckpwp.html

TS:   super.greet();
来源：http://dali.yj20258.top/Article/details/gtxlgnfvcx.html

Java: super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtayqcixpe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cheryme.top/Article/details/gtnoldrwzo.html

Ruby: super
来源：http://dali.hongshengwenyu.top/Article/details/gtwpprtlle.html

C#:   base.Greet();
来源：http://dali.smart0.xyz/Article/details/gtagujdjbe.html

[G08] 静态方法与属性
来源：http://dali.hammf.cn/Article/details/gtesbwcbak.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sxryk.cn/Article/details/gtwpcqiwxm.html

PHP:  public static function f() {}
来源：http://dali.ehwqpu.com/Article/details/gtdplpuimu.html

JS:   static f() {}
来源：http://dali.yangfankeji.com/Article/details/gtahlzjcey.html

TS:   static f(): void {}
来源：http://dali.andypj.xyz/Article/details/gtvcqxdjzi.html

Java: static void f() {}
来源：http://dali.xylfe.cn/Article/details/gteeekjako.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dashuyun.cn/Article/details/gtvnwgzaam.html

Ruby: def self.f; end
来源：http://dali.tian-w.cn/Article/details/gtibvnjnyx.html

C#:   public static void F() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtadfrikgb.html

[G09] 接口 / 抽象类
来源：http://dali.andypj.xyz/Article/details/gtfvrjopwe.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yongpay.top/Article/details/gtegrphsrk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxuanxn.top/Article/details/gtaakdnetj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhoulong.xyz/Article/details/gtoqwyjgbp.html

TS:   interface Shape { area(): number; }
来源：http://dali.pycfn.com/Article/details/gtmonpgkbd.html

Java: interface Shape { double area(); }
来源：http://dali.jqgfzy.top/Article/details/gtlrgobcaa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zycfv.cn/Article/details/gtlgxuzuhu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ydzc1.top/Article/details/gtyunkqeza.html

C#:   interface IShape { double Area(); }
来源：http://dali.andypj.xyz/Article/details/gtegwaqnzv.html

[G10] 访问控制
来源：http://dali.gogol.net.cn/Article/details/gtimjnniuy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zdqjudy.top/Article/details/gtakrojddy.html

PHP:  public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtnoniypmw.html

JS:   #private 字段；其余公开
来源：http://dali.dianchejie.cn/Article/details/gtfstggnpl.html

TS:   public / protected / private
来源：http://dali.ydzc1.top/Article/details/gticoixmzm.html

Java: public / protected / private / 默认包级
来源：http://dali.hywenlv.cn/Article/details/gtuanmbsaz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.haohaochexian.top/Article/details/gtokeivzfm.html

Ruby: public / protected / private
来源：http://dali.tanke756.top/Article/details/gtqoblqyoe.html

C#:   public / protected / private / internal
来源：http://dali.dianchejie.cn/Article/details/gtqbybjkcd.html

[G11] getter / setter
来源：http://dali.shzxlz.cn/Article/details/gtupawigyt.html

Py:   @property 与 @x.setter
来源：http://dali.hongshengwenyu.top/Article/details/gteyhsjoes.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gthfniujqc.html

JS:   get name() { return this._name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gttowzmgqd.html

TS:   get name(): string { return this._name; }
来源：http://dali.316326.xyz/Article/details/gtfuiblnjm.html

Java: public String getName() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtowrxvima.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gtpvlutkff.html

Ruby: attr_accessor :name
来源：http://dali.cucudq.cn/Article/details/gtoutuzgnx.html

C#:   public string Name { get; set; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvtbydaj.html

[G12] 对象转字符串
来源：http://dali.jyoumei.cn/Article/details/gttznybxmc.html

Py:   def __str__(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gtdhnlqblq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtagmlpmyt.html

JS:   toString() { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtlxizliky.html

TS:   toString(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtswythngv.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj20258888.top/Article/details/gtbqlfocrw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtjrekczey.html

Ruby: def to_s; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtjbepsdih.html

C#:   public override string ToString() => Name;
来源：http://dali.yuanzhike.top/Article/details/gtjscyokgl.html

[G13] 判断对象类型
来源：http://dali.aizwys.cn/Article/details/gtfwpkcldk.html

Py:   isinstance(u, User)
来源：http://dali.chenjidiqi.icu/Article/details/gtcqpknbqf.html

PHP:  $u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtpxoeuzlr.html

JS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gtlnqtrvnd.html

TS:   u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtwemzhzaq.html

Java: u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtawuqfpoy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.9152youxi.cn/Article/details/gtfmkzkjzr.html

Ruby: u.is_a?(User)
来源：http://dali.daxiang520.top/Article/details/gtkxtiesol.html

C#:   u is User
来源：http://dali.sxryk.cn/Article/details/gtwjqacevf.html

[G14] 数据类 / record
来源：http://dali.hfpthk.cn/Article/details/gtnamneuny.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhixingplan.top/Article/details/gtupmwvdxf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pycfn.com/Article/details/gtlpmtlvpt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenjidiqi.icu/Article/details/gtnachsoco.html

TS:   type User = { name: string; age: number };
来源：http://dali.hammf.cn/Article/details/gtycnsvsfe.html

Java: record User(String name, int age) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtmljaecen.html

Go:   type User struct { Name string; Age int }
来源：http://dali.fzhhl.top/Article/details/gtqmbadnwf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhoulong.xyz/Article/details/gtegetdslx.html

C#:   record User(string Name, int Age);
来源：http://dali.fengsongda.top/Article/details/gtpixoumbt.html

[G15] 枚举
来源：http://dali.aizwys.cn/Article/details/gtyzyvsern.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fengsongda.top/Article/details/gtqjirfwfq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jyoumei.cn/Article/details/gtnqzvojzx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.guannengcc.top/Article/details/gteafrrztk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.9152youxi.cn/Article/details/gtdstgfukv.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgfzy.top/Article/details/gtonkywlmz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yonumen.top/Article/details/gtlnrfuwjy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ybcxt.top/Article/details/gtbmnhrema.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gthtkopwtu.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbrcwwpv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zdqjudy.top/Article/details/gtcitpyerk.html

PHP:  get_object_vars($obj);
来源：http://dali.guannengcc.top/Article/details/gthgnbghji.html

JS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gtbocktdxw.html

TS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gtsppdptrg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.c1oappe.top/Article/details/gtzlxvggwn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.quarkkingdee.top/Article/details/gtymhmhzhf.html

Ruby: obj.instance_variables
来源：http://dali.gaohongyu789.top/Article/details/gtuewfvkdh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hywenlv.cn/Article/details/gtfadivcxu.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtzxqdzqph.html

H. 异常与错误处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlanzmsno.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtozpukrzm.html

[H01] try / catch 基础
来源：http://dali.sysykeji.top/Article/details/gtipfsbwdu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yangfankeji.com/Article/details/gtqgvdfjqy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hfpthk.cn/Article/details/gtikvpakoa.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sufxvd.cn/Article/details/gtqwsnfiye.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gtruuqxfiw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daria6918.cn/Article/details/gtadscabsq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gogol.net.cn/Article/details/gtdfygzprv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hammf.cn/Article/details/gtokggqpgb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtekgkbxjt.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrjcapky.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.svipenyu.cn/Article/details/gtitwrkvej.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtgrhwruah.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtibqodyzp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtlapavtds.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtsslmohhx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fengsongda.top/Article/details/gtkqghyvxk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daxiang520.top/Article/details/gtfasbnnpc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtrfgihcfg.html

[H03] 主动抛出异常
来源：http://dali.sweek.top/Article/details/gtrvvxizwk.html

Py:   raise ValueError("错误信息")
来源：http://dali.xinyue.icu/Article/details/gtusvbkjsp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtqfxrjqzm.html

JS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtulrpwycf.html

TS:   throw new Error("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtnwsjeekf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtwuarsxuz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gotoacloud.top/Article/details/gtmytowadj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.havefunace.top/Article/details/gtuxndkhoi.html


<!-- 参考信息 -->