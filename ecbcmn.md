代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gtjstwpivs.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.316326.xyz/Article/details/gttwbrlcob.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtfxdfkztl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtopwsjpsz.html

[E22] 字节长度与字符长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtybuqhexj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtwzgtwyvo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtapxponsv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gtfeppcxlf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gtphxjyqzc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.vqdsnc.cn/Article/details/gtdtzvahzb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.dianchejie.cn/Article/details/gtubfacghm.html

Ruby: s.bytesize;  s.length
来源：http://dali.tianlin.xyz/Article/details/gtbncgjlrb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ehwqpu.com/Article/details/gtpxvaakwh.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtmutfquwg.html

F. 文件与目录
来源：http://dali.guannengcc.top/Article/details/gtnjaqdwhj.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtrpyspoum.html

[F01] 读取整个文件
来源：http://dali.jlsjyb.cn/Article/details/gtsrywrdwz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj202588.top/Article/details/gtykdvbmtn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtclrcflmm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cucudq.cn/Article/details/gtldeygqsq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtsghawimj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtslqfgydd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shzxlz.cn/Article/details/gtxmvcwwek.html

Ruby: File.read("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtdaedqxoo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtabtvygua.html

[F02] 逐行读取文件
来源：http://dali.mhx1999.top/Article/details/gtalmqfeac.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hnqzz.top/Article/details/gtnlozvasw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tanke756.top/Article/details/gthmebmxyk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhengqikj.top/Article/details/gtajvtffwl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.kuanghao11.cn/Article/details/gthlctahht.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cheryme.top/Article/details/gttxcmnugd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ppjwa.cn/Article/details/gtslmzmsad.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.daxiang520.top/Article/details/gtqbtmppry.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xylfe.cn/Article/details/gtcxrhwyea.html

[F03] 写入文件（覆盖）
来源：http://dali.gotoacloud.top/Article/details/gtvjgxbfpv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gtfevongfi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenlongwang.top/Article/details/gthltpaivc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gtfzdqvild.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gtbsnqjktd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ehwqpu.com/Article/details/gtytfvakaa.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ydzc1.top/Article/details/gtjrlisgtd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tian-w.cn/Article/details/gtctubwlek.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.daria6918.cn/Article/details/gttnrgeegx.html

[F04] 追加写入文件
来源：http://dali.yonumen.top/Article/details/gtimvqtfjs.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fzhhl.top/Article/details/gtyivckgak.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jlsjyb.cn/Article/details/gtsizajrrn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gtuatlpmjk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gtcsbsnoor.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cqqwz.cn/Article/details/gtwoemagvr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtutkirgrq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.aibaodan.cn/Article/details/gtzagfymui.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cdnleiting.top/Article/details/gtdcadjtpv.html

[F05] 判断文件或目录是否存在
来源：http://dali.ybcxt.top/Article/details/gtzkzvupkm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yangfankeji.com/Article/details/gtsrhiwdqy.html

PHP:  file_exists("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtoixospcy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtbmnrrpng.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtbicgvmlh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtqnhabqtn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gotoacloud.top/Article/details/gtgqhtlsyc.html

Ruby: File.exist?("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtfnuhplvg.html

C#:   File.Exists("a.txt")
来源：http://dali.316326.xyz/Article/details/gtayzdcofy.html

[F06] 删除文件
来源：http://dali.jqgfzy.top/Article/details/gtaydjfqno.html

Py:   os.remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gtbrhgqxhs.html

PHP:  unlink("a.txt");
来源：http://dali.cashguo.top/Article/details/gtnazheljm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gthzvxwyxk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyhjpwewd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtfmhmnvgr.html

Go:   os.Remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtgvzkmxvb.html

Ruby: File.delete("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtgulzgqhl.html

C#:   File.Delete("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtymwqfvpl.html

[F07] 创建目录（含多级）
来源：http://dali.shangyingyoupin.top/Article/details/gtiskaqdpu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gaohongyu789.top/Article/details/gtdoduzpzg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hfpthk.cn/Article/details/gtbvwhipgt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtddftlwsu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gtwpdwetll.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.birdmap.top/Article/details/gtoorbpywr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhoulong.xyz/Article/details/gtkyfbemlt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ehwqpu.com/Article/details/gtzmvbxacp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.vqdsnc.cn/Article/details/gtkziwihnv.html

[F08] 遍历目录
来源：http://dali.gaohongyu789.top/Article/details/gtxikfprnl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenjidiqi.icu/Article/details/gtgivtpnin.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigfzy.top/Article/details/gtfxoxagto.html

JS:   fs.readdirSync("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtgcxjanwy.html

TS:   fs.readdirSync("dir")
来源：http://dali.aibaodan.cn/Article/details/gtpdpyisbt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhixingplan.top/Article/details/gtfvcjbejx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqvqzezg.html

Ruby: Dir.children("dir")
来源：http://dali.birdmap.top/Article/details/gtqaosoeka.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gotoacloud.top/Article/details/gtlnzlahqa.html

[F09] 获取文件大小
来源：http://dali.chenlongwang.top/Article/details/gtvrxkdoyv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtqainctrh.html

PHP:  filesize("a.txt");
来源：http://dali.ivvv.top/Article/details/gtojyihjoo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yangfankeji.com/Article/details/gtkophfkem.html

TS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gtoqxnhzsd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gtekmbjvca.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yonumen.top/Article/details/gtqqchxsae.html

Ruby: File.size("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtymtcfdrl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdqltrfx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yvedp.cn/Article/details/gtoemdkxmq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtpjvkzdsy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shuidangran.top/Article/details/gtiejlonam.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtdtnxvbnq.html

TS:   path.extname("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtcahbsgck.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yangfankeji.com/Article/details/gthxhnkmcz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtkzwszwuk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtxiwkjlnj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtufxrbggq.html

[F11] 复制与移动文件
来源：http://dali.gzhubu.top/Article/details/gtjkfkpcmb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtpkprvehj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqsypddh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtinsrnxlw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtvwqndltt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gtjifpgrld.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xylfe.cn/Article/details/gtewnwmcak.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gtrdimvwmr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daxiang520.top/Article/details/gtaldjzjom.html

[F12] CSV 读写
来源：http://dali.wangshuangyany.cn/Article/details/gtmfrpapdi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.iojbl.cn/Article/details/gtcveonugq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtozishitn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhongyouzk.top/Article/details/gtsmojdrjv.html

TS:   // 同上
来源：http://dali.birdmap.top/Article/details/gtsymxhdyi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.redwolf501.top/Article/details/gtpeyvpczp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.fengsongda.top/Article/details/gtknzzqhdr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhiwuduotai.top/Article/details/gtozmnorff.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.daria6918.cn/Article/details/gtlnighudw.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtlofjbvek.html

G. 面向对象
来源：http://dali.jinqigfzy.top/Article/details/gtekmwsusr.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtnyqltszn.html

[G01] 定义类
来源：http://dali.zdqjudy.top/Article/details/gtnutfasux.html

Py:   class User: pass
来源：http://dali.jlsjyb.cn/Article/details/gtfqelglmy.html

PHP:  class User {}
来源：http://dali.andypj.xyz/Article/details/gtelrrexzu.html

JS:   class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtihfwshpx.html

TS:   class User { name: string = ""; }
来源：http://dali.meibo888.top/Article/details/gtvatssowj.html

Java: class User {}
来源：http://dali.9152youxi.cn/Article/details/gtxukznngy.html

Go:   type User struct { Name string }
来源：http://dali.chenzaomai.com/Article/details/gtnlzpkixm.html

Ruby: class User; end
来源：http://dali.guannengcc.top/Article/details/gtsseibmmj.html

C#:   class User {}
来源：http://dali.yueranfly.top/Article/details/gtupdmyypp.html

[G02] 构造函数
来源：http://dali.sxryk.cn/Article/details/gtwtdizhhs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xylfe.cn/Article/details/gtdcnjpmjb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxaukhwj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtjobbvuhk.html

TS:   constructor(public name: string) {}
来源：http://dali.hnqzz.top/Article/details/gtghqykzhf.html

Java: User(String name) { this.name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtdxtsjrti.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj20258.top/Article/details/gtghtsyaxf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hysaishi.cn/Article/details/gtnmsqvwyn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxinkj.top/Article/details/gtbggfpqqc.html

[G03] 实例属性
来源：http://dali.xuanzx.com/Article/details/gtpdziotoj.html

Py:   self.name = "x"
来源：http://dali.birdmap.top/Article/details/gtikcmfbws.html

PHP:  public string $name = "x";
来源：http://dali.yonumen.top/Article/details/gtohgzqenm.html

JS:   this.name = "x";
来源：http://dali.ybcxt.top/Article/details/gtbwaamfqo.html

TS:   name: string = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhojpspy.html

Java: private String name;
来源：http://dali.ppjwa.cn/Article/details/gtmwtidccq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cashguo.top/Article/details/gtqtvhogcj.html

Ruby: @name = "x"
来源：http://dali.snrcjt.cn/Article/details/gtcasfhken.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.9152youxi.cn/Article/details/gtekmwwwdw.html

[G04] 定义方法
来源：http://dali.ybcxt.top/Article/details/gtqbqndjuh.html

Py:   def greet(self): return self.name
来源：http://dali.yj202588.top/Article/details/gtsmwlxnhr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtnvvocyux.html

JS:   greet() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbmhfoyw.html

TS:   greet(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtefohqdbj.html

Java: String greet() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtkuiltjgo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvbonvdz.html

Ruby: def greet; @name; end
来源：http://dali.zycfv.cn/Article/details/gtuyltddhv.html

C#:   public string Greet() => Name;
来源：http://dali.sweek.top/Article/details/gtislnuivq.html

[G05] 继承
来源：http://dali.shangyingyoupin.top/Article/details/gtwoiilrrq.html

Py:   class Admin(User): pass
来源：http://dali.zhixingplan.top/Article/details/gtrvfaacwo.html

PHP:  class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtdxyclcgq.html

JS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtsdzpcsrh.html

TS:   class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtgfiowhly.html

Java: class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtbbyfrryb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ywan-chungtsiang.top/Article/details/gthtxqways.html

Ruby: class Admin < User; end
来源：http://dali.pengpengdd.cyou/Article/details/gtngqdkowf.html

C#:   class Admin : User {}
来源：http://dali.svipenyu.cn/Article/details/gtuifbpymf.html

[G06] 重写方法
来源：http://dali.pycfn.com/Article/details/gtjedrydaq.html

Py:   def greet(self): return "admin"
来源：http://dali.shzxlz.cn/Article/details/gtgxrsatua.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtxbiacmqf.html

JS:   greet() { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlaqerpmx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtieaskhbk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gthzmzhbhp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.bjfxy.top/Article/details/gtnwgmtrhc.html

Ruby: def greet; "admin"; end
来源：http://dali.snrcjt.cn/Article/details/gteppcmifo.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj202588.top/Article/details/gtnzytltya.html

[G07] 调用父类方法
来源：http://dali.yanxiufei.cn/Article/details/gtugxpkxln.html

Py:   super().greet()
来源：http://dali.9152youxi.cn/Article/details/gtxooclrgv.html

PHP:  parent::greet();
来源：http://dali.yuanzhike.top/Article/details/gtxirazrvv.html

JS:   super.greet();
来源：http://dali.zycfv.cn/Article/details/gtwiflbduo.html

TS:   super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtdosqkbkq.html

Java: super.greet();
来源：http://dali.andypj.xyz/Article/details/gtwoiytust.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hysaishi.cn/Article/details/gtvowopmdg.html

Ruby: super
来源：http://dali.quarkkingdee.top/Article/details/gtfucwasin.html

C#:   base.Greet();
来源：http://dali.hnqzz.top/Article/details/gtmluvmiuc.html

[G08] 静态方法与属性
来源：http://dali.hammf.cn/Article/details/gtsurqkmeh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gzhubu.top/Article/details/gtmnrtkzua.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwixeghkv.html

JS:   static f() {}
来源：http://dali.fzhhl.top/Article/details/gtjeavmuno.html

TS:   static f(): void {}
来源：http://dali.wangshuangyany.cn/Article/details/gtnvuvjokw.html

Java: static void f() {}
来源：http://dali.c1oappe.top/Article/details/gteizuqvwo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dashuyun.cn/Article/details/gtjtriethd.html

Ruby: def self.f; end
来源：http://dali.shuidangran.top/Article/details/gtinhzfhwg.html

C#:   public static void F() {}
来源：http://dali.cashguo.top/Article/details/gtcdbkmxfz.html

[G09] 接口 / 抽象类
来源：http://dali.cheryme.top/Article/details/gtpzpxcjwd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cashguo.top/Article/details/gtrztnjnjl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gaohongyu789.top/Article/details/gthjcyvtox.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.havefunace.top/Article/details/gtfaburvrz.html

TS:   interface Shape { area(): number; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlzxohwbb.html

Java: interface Shape { double area(); }
来源：http://dali.tian-w.cn/Article/details/gtpopdejcl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.svipenyu.cn/Article/details/gttubeykis.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cucudq.cn/Article/details/gtjlmemcjo.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxuanxn.top/Article/details/gtxphtgphc.html

[G10] 访问控制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbgktwrqx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cdnleiting.top/Article/details/gtnpaepnbk.html

PHP:  public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtgwlhaxrh.html

JS:   #private 字段；其余公开
来源：http://dali.shangyingyoupin.top/Article/details/gtmjcmmgmg.html

TS:   public / protected / private
来源：http://dali.guannengcc.top/Article/details/gtzykkzmcv.html

Java: public / protected / private / 默认包级
来源：http://dali.c1oappe.top/Article/details/gtippulgnz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhoulong.xyz/Article/details/gtdzbvpcls.html

Ruby: public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtjuwmmkkv.html

C#:   public / protected / private / internal
来源：http://dali.mhx1999.top/Article/details/gtrsmjhtfj.html

[G11] getter / setter
来源：http://dali.cqqwz.cn/Article/details/gtzusaygim.html

Py:   @property 与 @x.setter
来源：http://dali.meibo888.top/Article/details/gtgtdseled.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gtorbwubeu.html

JS:   get name() { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gtapwtnsvp.html

TS:   get name(): string { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gtplxpeasj.html

Java: public String getName() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqrdqcbjm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gtealheowl.html

Ruby: attr_accessor :name
来源：http://dali.zdqjudy.top/Article/details/gtgztmgxij.html

C#:   public string Name { get; set; }
来源：http://dali.jianghu66.top/Article/details/gtmghdbbiq.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwyqelrhm.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258888.top/Article/details/gtsgrdwiib.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtsfwsnait.html

JS:   toString() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtphkppprh.html

TS:   toString(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtwzraerrk.html

Java: @Override public String toString() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtwzsodrrj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gtzeeeekhg.html

Ruby: def to_s; @name; end
来源：http://dali.chenzaomai.com/Article/details/gtopzcytgw.html

C#:   public override string ToString() => Name;
来源：http://dali.pycfn.com/Article/details/gtkrobhmbx.html

[G13] 判断对象类型
来源：http://dali.sysykeji.top/Article/details/gtsejkshld.html

Py:   isinstance(u, User)
来源：http://dali.wangshuangyany.cn/Article/details/gtakketlqj.html

PHP:  $u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtmfetyvev.html

JS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gtpiyiswqx.html

TS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gtmkojyors.html

Java: u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtlmhykbbm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.0kj1m.cn/Article/details/gtkbrjrfxw.html

Ruby: u.is_a?(User)
来源：http://dali.birdmap.top/Article/details/gtsvhwvdth.html

C#:   u is User
来源：http://dali.cashguo.top/Article/details/gtlloqazma.html

[G14] 数据类 / record
来源：http://dali.cheryme.top/Article/details/gtwkuokbdj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.aibaodan.cn/Article/details/gtwrxrkorl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sysykeji.top/Article/details/gtzpkgxlbf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cdnleiting.top/Article/details/gthdhksztt.html

TS:   type User = { name: string; age: number };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsdqiiiyw.html

Java: record User(String name, int age) {}
来源：http://dali.aibaodan.cn/Article/details/gtshmhscyg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gotoacloud.top/Article/details/gtgvmvxpzz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.aibaodan.cn/Article/details/gthikacazw.html

C#:   record User(string Name, int Age);
来源：http://dali.gzhubu.top/Article/details/gtimsoogje.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gthcczbblm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.smart0.xyz/Article/details/gtcdmtfiau.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xinyue.icu/Article/details/gtgrwfkydq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sxryk.cn/Article/details/gtwhklfgcj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hywenlv.cn/Article/details/gtthhiqwyr.html

Java: enum Color { RED, GREEN }
来源：http://dali.hywenlv.cn/Article/details/gtwhlfdqkd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cucudq.cn/Article/details/gtzwhfghuj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shzxlz.cn/Article/details/gtifahcyxd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gtiuzostgv.html

[G16] 对象转数组 / 字典
来源：http://dali.gzhubu.top/Article/details/gtzodvcoxr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgufenzy.top/Article/details/gtcticobor.html

PHP:  get_object_vars($obj);
来源：http://dali.jiagoushi.top/Article/details/gtncyygkmu.html

JS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gtwyhiqywl.html

TS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gtnvbypgmm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tanke756.top/Article/details/gtbyjartpr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daxiang520.top/Article/details/gtfkytiaok.html

Ruby: obj.instance_variables
来源：http://dali.fengsongda.top/Article/details/gtucmhkmay.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.0kj1m.cn/Article/details/gtrbflefoi.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtbdibarmu.html

H. 异常与错误处理
来源：http://dali.kuanghao11.cn/Article/details/gtjctbxwiv.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtxzqrqmnz.html

[H01] try / catch 基础
来源：http://dali.hnxiangtu.top/Article/details/gtocpmbrng.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuanzhike.top/Article/details/gtwzeafysq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hammf.cn/Article/details/gtoeismvsz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gtfzjqrrph.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gtppgekdns.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhengqikj.top/Article/details/gtqvvubnqe.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shzxlz.cn/Article/details/gtvumrqhwn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtzizhrpfr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.bjfxy.top/Article/details/gtkuxhrgux.html

[H02] finally / ensure 收尾
来源：http://dali.ydzc1.top/Article/details/gtaygcmjmc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.aizwys.cn/Article/details/gtcccnjdkx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtbsjpwurm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtzermgvqw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcyouoybo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtcdbdxanb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gogol.net.cn/Article/details/gtqphpxncy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.316326.xyz/Article/details/gtosfllned.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtjbwfutiv.html

[H03] 主动抛出异常
来源：http://dali.yanxiufei.cn/Article/details/gtwezoxcwe.html

Py:   raise ValueError("错误信息")
来源：http://dali.yanxiufei.cn/Article/details/gtuoqzunfp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtzfcxprlm.html

JS:   throw new Error("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtztynlodf.html

TS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtnbzdceyi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gtbytkoryu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj202588.top/Article/details/gthqrefzrc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuxming.cn/Article/details/gtagltoxax.html


<!-- 参考信息 -->