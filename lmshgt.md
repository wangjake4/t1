代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.bjfxy.top/Article/details/gtavedtsxf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.guannengcc.top/Article/details/gtngjuhkwc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtljmuqsfr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gtwfiiudje.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hysaishi.cn/Article/details/gtwnmnpqsm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aibaodan.cn/Article/details/gtokzicyva.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.wangdashe.top/Article/details/gtlzugbaad.html

Ruby: s.bytesize;  s.length
来源：http://dali.cucudq.cn/Article/details/gtyhjpdgwv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cheryme.top/Article/details/gttylvtjec.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtcvstjvzl.html

F. 文件与目录
来源：http://dali.tianlin.xyz/Article/details/gtjscrlpnm.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtcguodqau.html

[F01] 读取整个文件
来源：http://dali.316326.xyz/Article/details/gtdpozocsq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj20258.top/Article/details/gtntspossf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtgkalzcpm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cqqwz.cn/Article/details/gtzwkpgwdc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtxpkktplt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtqfdoeeuw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.wangdashe.top/Article/details/gtgfchuvwb.html

Ruby: File.read("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtyjudhpgl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtansppyjw.html

[F02] 逐行读取文件
来源：http://dali.vqdsnc.cn/Article/details/gtckzmwygg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.feifeiyinyue.top/Article/details/gtivppnqzo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnnuyylst.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtglygfedo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtcryvfwgk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xinyue.icu/Article/details/gtzvuzpxiv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcouamlyn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqlgvoprc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqngfrwsq.html

[F03] 写入文件（覆盖）
来源：http://dali.chenjidiqi.icu/Article/details/gtbabxyxbu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtywrddwsz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoixwkyjj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gtwkxhlmbn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gtpflrdxay.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.fengsongda.top/Article/details/gtwkqxaaep.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.daxiang520.top/Article/details/gtlhtpmqzw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhongyouzk.top/Article/details/gtsjpxiuzt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gtggvfthay.html

[F04] 追加写入文件
来源：http://dali.jyoumei.cn/Article/details/gtmeqapoey.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhixingplan.top/Article/details/gtsqkgahdi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gogol.net.cn/Article/details/gtzxlcndhf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtghgcacml.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gtzvfslmxg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yanxiufei.cn/Article/details/gtiyvmibrb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tianlin.xyz/Article/details/gtocddshwk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.0kj1m.cn/Article/details/gtogvrfmhf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hywenlv.cn/Article/details/gtrcmntjsc.html

[F05] 判断文件或目录是否存在
来源：http://dali.birdmap.top/Article/details/gtressbnxo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.9152youxi.cn/Article/details/gtjxwimjga.html

PHP:  file_exists("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtpsucgdyj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtgzwzqaob.html

TS:   fs.existsSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtxtwzlwbw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gtfpppdqcl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj20258.top/Article/details/gtumlbmipc.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtmgbwvcut.html

C#:   File.Exists("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtepvwrrtk.html

[F06] 删除文件
来源：http://dali.feifeiyinyue.top/Article/details/gtqbdhzrhi.html

Py:   os.remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtxcpzuodk.html

PHP:  unlink("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtvtvksvez.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtodlyeryg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtawbzrrjj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gttsnilmkb.html

Go:   os.Remove("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtwelfpeiv.html

Ruby: File.delete("a.txt")
来源：http://dali.birdmap.top/Article/details/gtdjbdpeou.html

C#:   File.Delete("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtuwcbsdxc.html

[F07] 创建目录（含多级）
来源：http://dali.yuanzhike.top/Article/details/gtiqnwplzi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj202588.top/Article/details/gtwhtrdjjb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhixingplan.top/Article/details/gtpdzaqyqq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daxiang520.top/Article/details/gtnwzewfgj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ybcxt.top/Article/details/gtbkonuihu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnxiangtu.top/Article/details/gtxphqpgad.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpvhienug.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gogol.net.cn/Article/details/gtywzjzykc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.0kj1m.cn/Article/details/gtlaeltvsu.html

[F08] 遍历目录
来源：http://dali.hysaishi.cn/Article/details/gtshmfpfux.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yonumen.top/Article/details/gtyzvnravq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gthnuselvo.html

JS:   fs.readdirSync("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtbrtfcsfw.html

TS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gtozurgwwu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxuanxn.top/Article/details/gtfpanftda.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtefsadwrw.html

Ruby: Dir.children("dir")
来源：http://dali.svipenyu.cn/Article/details/gtyvegothi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtjzbbltfy.html

[F09] 获取文件大小
来源：http://dali.0kj1m.cn/Article/details/gtgufrvbcr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gzhubu.top/Article/details/gttopiqcjv.html

PHP:  filesize("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtntkateye.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yongpay.top/Article/details/gtddwiupos.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hammf.cn/Article/details/gtgeckinpe.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gttdkgskss.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sxryk.cn/Article/details/gtpforwclo.html

Ruby: File.size("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtsxkmgpmi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sufxvd.cn/Article/details/gtpsdzexsx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yanxiufei.cn/Article/details/gtnxektlfl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gttqaathsu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hnqzz.top/Article/details/gtddpxzdrk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtpjubrxjg.html

TS:   path.extname("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyewqpazd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258888.top/Article/details/gtltidlntm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtxvrhisbr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtbdlwowyf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtwaeyzmyf.html

[F11] 复制与移动文件
来源：http://dali.fzhhl.top/Article/details/gtbcngyavl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtptvcsipw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtbkuzkxgf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtbemroipr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtmkpgdfdx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.daxiang520.top/Article/details/gtwjextypg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yongpay.top/Article/details/gthaqxrczy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtqvqqduig.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gzhubu.top/Article/details/gtjysatacu.html

[F12] CSV 读写
来源：http://dali.hfpthk.cn/Article/details/gtuqsxiwnr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuetiantiany.cn/Article/details/gtiecnsjcs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xinyue.icu/Article/details/gtrrngiylb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xylfe.cn/Article/details/gtszgddwxo.html

TS:   // 同上
来源：http://dali.daria6918.cn/Article/details/gtruucikgf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuanzx.com/Article/details/gtajhxmdse.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.kuanghao11.cn/Article/details/gtcuzvhwkm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hnxiangtu.top/Article/details/gtyuknwzbc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.iojbl.cn/Article/details/gtgdxmvqzk.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtienkqoda.html

G. 面向对象
来源：http://dali.zhixingplan.top/Article/details/gtvqaatbyt.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtagwpdhto.html

[G01] 定义类
来源：http://dali.cashguo.top/Article/details/gtssbvwhat.html

Py:   class User: pass
来源：http://dali.jlsjyb.cn/Article/details/gtzmgvqbkd.html

PHP:  class User {}
来源：http://dali.0kj1m.cn/Article/details/gteurckecg.html

JS:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gtfumukzxl.html

TS:   class User { name: string = ""; }
来源：http://dali.wangdashe.top/Article/details/gtvrzkfjrh.html

Java: class User {}
来源：http://dali.fzhhl.top/Article/details/gtiomiiuif.html

Go:   type User struct { Name string }
来源：http://dali.pengpengdd.cyou/Article/details/gtbnsmfchr.html

Ruby: class User; end
来源：http://dali.0kj1m.cn/Article/details/gtcpqkmeca.html

C#:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtxautmlcu.html

[G02] 构造函数
来源：http://dali.316326.xyz/Article/details/gtajaaslzp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.havefunace.top/Article/details/gtnqwfbrei.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.mhx1999.top/Article/details/gtjrwydpyp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gtsaazztbk.html

TS:   constructor(public name: string) {}
来源：http://dali.jiagoushi.top/Article/details/gtqxarxfma.html

Java: User(String name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gtujrcjjdw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.dashuyun.cn/Article/details/gtqseikvno.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jianghu66.top/Article/details/gtiwvifnuh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhixingplan.top/Article/details/gtnvhcjhcs.html

[G03] 实例属性
来源：http://dali.chenjidiqi.icu/Article/details/gtyzcusugw.html

Py:   self.name = "x"
来源：http://dali.vqdsnc.cn/Article/details/gtdeqhrnfv.html

PHP:  public string $name = "x";
来源：http://dali.hysaishi.cn/Article/details/gtsaqqzntj.html

JS:   this.name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfpdmvxk.html

TS:   name: string = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtsuhkvblk.html

Java: private String name;
来源：http://dali.fzhhl.top/Article/details/gtmkxfwuhf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgfzy.top/Article/details/gteicjvfxk.html

Ruby: @name = "x"
来源：http://dali.cqqwz.cn/Article/details/gtxxrgjeet.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenzaomai.com/Article/details/gtlutwewvr.html

[G04] 定义方法
来源：http://dali.gzhubu.top/Article/details/gtrahjjsqz.html

Py:   def greet(self): return self.name
来源：http://dali.cheryme.top/Article/details/gthqztywyn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtngffhxgf.html

JS:   greet() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtibdobepj.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtdpseawof.html

Java: String greet() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiscrmfej.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtlkjxfrmd.html

Ruby: def greet; @name; end
来源：http://dali.feifeiyinyue.top/Article/details/gttxluwnog.html

C#:   public string Greet() => Name;
来源：http://dali.andypj.xyz/Article/details/gtftgztwsf.html

[G05] 继承
来源：http://dali.tianlin.xyz/Article/details/gtnieoescg.html

Py:   class Admin(User): pass
来源：http://dali.mhx1999.top/Article/details/gtfjywmask.html

PHP:  class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtierdjykx.html

JS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtbohbeecw.html

TS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtryudheeu.html

Java: class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtdruvwlku.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrknbltlm.html

Ruby: class Admin < User; end
来源：http://dali.tanke756.top/Article/details/gtlvkvhuue.html

C#:   class Admin : User {}
来源：http://dali.chenzaomai.com/Article/details/gtfpdqczrd.html

[G06] 重写方法
来源：http://dali.c1oappe.top/Article/details/gtcgfpjjrs.html

Py:   def greet(self): return "admin"
来源：http://dali.xuanzx.com/Article/details/gttwqbczuf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gthijlrjxs.html

JS:   greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtxjqtuzqw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gthprbtizf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gthjdnquev.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sufxvd.cn/Article/details/gtgfayaipr.html

Ruby: def greet; "admin"; end
来源：http://dali.aibaodan.cn/Article/details/gtjckueumc.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqswmnhf.html

[G07] 调用父类方法
来源：http://dali.tianlin.xyz/Article/details/gtdclgostc.html

Py:   super().greet()
来源：http://dali.jinghuilouyu.cn/Article/details/gtdtghwwqy.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gtfsevrxws.html

JS:   super.greet();
来源：http://dali.yj202588.top/Article/details/gtmntmzdbf.html

TS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gttdlovmti.html

Java: super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtuzzhiwor.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenlongwang.top/Article/details/gtcgvqsmnn.html

Ruby: super
来源：http://dali.yj20258.top/Article/details/gtiulycmub.html

C#:   base.Greet();
来源：http://dali.zycfv.cn/Article/details/gtrmgzemec.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtzkycvyue.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.iojbl.cn/Article/details/gtmsvhwlib.html

PHP:  public static function f() {}
来源：http://dali.cdnleiting.top/Article/details/gtaxwecaby.html

JS:   static f() {}
来源：http://dali.jyoumei.cn/Article/details/gtykmbkcer.html

TS:   static f(): void {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtydgnervq.html

Java: static void f() {}
来源：http://dali.fengsongda.top/Article/details/gtxdumjzby.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgufenzy.top/Article/details/gtutknntqz.html

Ruby: def self.f; end
来源：http://dali.shuidangran.top/Article/details/gttsdjylnv.html

C#:   public static void F() {}
来源：http://dali.yangfankeji.com/Article/details/gtqjwqgpal.html

[G09] 接口 / 抽象类
来源：http://dali.fzhhl.top/Article/details/gttmyotrkl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.iojbl.cn/Article/details/gtxnotmhim.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hfpthk.cn/Article/details/gtgzrhutwq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yuxming.cn/Article/details/gtrshlfgrl.html

TS:   interface Shape { area(): number; }
来源：http://dali.yueranfly.top/Article/details/gtmkjhzbft.html

Java: interface Shape { double area(); }
来源：http://dali.aizwys.cn/Article/details/gttwvhwozy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhoulong.xyz/Article/details/gtipxztldh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuetiantiany.cn/Article/details/gtauhzqmxu.html

C#:   interface IShape { double Area(); }
来源：http://dali.cqqwz.cn/Article/details/gtvdrzdcws.html

[G10] 访问控制
来源：http://dali.vqdsnc.cn/Article/details/gtivwrdmvp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.smart0.xyz/Article/details/gtjyftrwci.html

PHP:  public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtfyygnhif.html

JS:   #private 字段；其余公开
来源：http://dali.tianlin.xyz/Article/details/gtdzgwuojh.html

TS:   public / protected / private
来源：http://dali.yonumen.top/Article/details/gtxfnhbrcl.html

Java: public / protected / private / 默认包级
来源：http://dali.tianlin.xyz/Article/details/gtpyptijqy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hfpthk.cn/Article/details/gtibnzavyo.html

Ruby: public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtmxdsugjt.html

C#:   public / protected / private / internal
来源：http://dali.zhengqikj.top/Article/details/gtiridfjyq.html

[G11] getter / setter
来源：http://dali.jinqigufen.top/Article/details/gtosabeuzv.html

Py:   @property 与 @x.setter
来源：http://dali.hnxiangtu.top/Article/details/gtrngqhnqn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gtbwatimze.html

JS:   get name() { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gtzakmidvu.html

TS:   get name(): string { return this._name; }
来源：http://dali.shangyingyoupin.top/Article/details/gttukhxcbx.html

Java: public String getName() { return name; }
来源：http://dali.sysykeji.top/Article/details/gtmytktftz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gtcvvffqyg.html

Ruby: attr_accessor :name
来源：http://dali.bjfxy.top/Article/details/gtnhksfsrh.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtknmtdald.html

[G12] 对象转字符串
来源：http://dali.hywenlv.cn/Article/details/gtugitxcuh.html

Py:   def __str__(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gtvgycducz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gtluhqobmk.html

JS:   toString() { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtjfdjhzra.html

TS:   toString(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtzqwfqpki.html

Java: @Override public String toString() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gthkvagauu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gtmhgunbym.html

Ruby: def to_s; @name; end
来源：http://dali.mhx1999.top/Article/details/gtrtsmydqx.html

C#:   public override string ToString() => Name;
来源：http://dali.haohaochexian.top/Article/details/gtnkhdliza.html

[G13] 判断对象类型
来源：http://dali.dashuyun.cn/Article/details/gtqvauxgie.html

Py:   isinstance(u, User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvdqussqe.html

PHP:  $u instanceof User
来源：http://dali.meibo888.top/Article/details/gtiayinjyg.html

JS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtmmanbphu.html

TS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtmxysizfw.html

Java: u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gthtaouxix.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aibaodan.cn/Article/details/gtekvqjssq.html

Ruby: u.is_a?(User)
来源：http://dali.havefunace.top/Article/details/gtxcnhlwot.html

C#:   u is User
来源：http://dali.jiagoushi.top/Article/details/gtwdjzihix.html

[G14] 数据类 / record
来源：http://dali.sufxvd.cn/Article/details/gtdthnpsko.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daxiang520.top/Article/details/gtetjaboxn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.mhx1999.top/Article/details/gtkigckcpm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.9152youxi.cn/Article/details/gtykycezhs.html

TS:   type User = { name: string; age: number };
来源：http://dali.hywenlv.cn/Article/details/gtxkxnqzlk.html

Java: record User(String name, int age) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtuhpjlmmg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnonoguw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnxiangtu.top/Article/details/gtiwortobm.html

C#:   record User(string Name, int Age);
来源：http://dali.havefunace.top/Article/details/gtzjgkuaot.html

[G15] 枚举
来源：http://dali.birdmap.top/Article/details/gttaxaehpz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.c1oappe.top/Article/details/gtmwiayhgt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cdnleiting.top/Article/details/gtnwujyktv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xinyue.icu/Article/details/gtomfospkh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guannengcc.top/Article/details/gtoibkhgxz.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj20258.top/Article/details/gtpojznkyz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yueranfly.top/Article/details/gtkcasymiv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.kuanghao11.cn/Article/details/gtvulecbrd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gtuzmdjekf.html

[G16] 对象转数组 / 字典
来源：http://dali.xziqi.cn/Article/details/gtozpkerle.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.feifeiyinyue.top/Article/details/gtmwtmifmx.html

PHP:  get_object_vars($obj);
来源：http://dali.iojbl.cn/Article/details/gtksmvnvsa.html

JS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gtstlcuuoj.html

TS:   Object.entries(obj)
来源：http://dali.redwolf501.top/Article/details/gtrkqanmbu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hysaishi.cn/Article/details/gtvxqgdnvu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aibaodan.cn/Article/details/gtdjlychsb.html

Ruby: obj.instance_variables
来源：http://dali.xuanzx.com/Article/details/gtqdhwrzzw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gtmoqzacva.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtwvtdcn.html

H. 异常与错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulvmupna.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtjndskvuh.html

[H01] try / catch 基础
来源：http://dali.shuidangran.top/Article/details/gtajcfxlkl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zycfv.cn/Article/details/gtgansgunw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttnahfbsg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gtwsfrvfqn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gtlocsfaqb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.316326.xyz/Article/details/gtrrzubipk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xinyue.icu/Article/details/gtobuqnbgs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cheryme.top/Article/details/gtqijqbxoz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.iojbl.cn/Article/details/gtyzpynlsk.html

[H02] finally / ensure 收尾
来源：http://dali.jiagoushi.top/Article/details/gthnzbbplh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgfzy.top/Article/details/gtplsxcvzs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtpgdipyjo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtrodbqsfu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtjvpcidxn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtrymdohxe.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhiwuduotai.top/Article/details/gtkglhnhdh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gtczchjxvy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtdwdhkisw.html

[H03] 主动抛出异常
来源：http://dali.yj20258.top/Article/details/gtbfiytcnc.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangshuangyany.cn/Article/details/gtuyefrkux.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtkmektsdd.html

JS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtrifsklmm.html

TS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtqgspokow.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtybajhqef.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.0kj1m.cn/Article/details/gthzlotcmz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258.top/Article/details/gtosugotnb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gttqrxixyi.html

[H04] 自定义异常类型
来源：http://dali.daxiang520.top/Article/details/gtzkekoolw.html

Py:   class MyError(Exception): pass
来源：http://dali.9152youxi.cn/Article/details/gtlzfvcyro.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gtfvnhnzfy.html


<!-- 参考信息 -->