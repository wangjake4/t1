代发 wailian999

Go:   if s == "" {}
来源：http://dali.zdqjudy.top/Article/details/gttcjtkimr.html

Ruby: if s.empty?
来源：http://dali.jlsjyb.cn/Article/details/gtlnthgvja.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhoulong.xyz/Article/details/gthdtuuxvt.html

[E21] 超长截断加省略号
来源：http://dali.jqgfzy.top/Article/details/gtbqwlhesz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gogol.net.cn/Article/details/gtabivpgut.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtctaakmmv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtkoutmqui.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gterxmvayz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtmbzyscjr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hysaishi.cn/Article/details/gtvznrioos.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtsusacnjb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gthnqdvgtf.html

[E22] 字节长度与字符长度
来源：http://dali.xylfe.cn/Article/details/gtgrxjiwvq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtwzvwcueo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gtibmjxubi.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.snrcjt.cn/Article/details/gtwkpmpdbq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjaxkcvw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gogol.net.cn/Article/details/gtglwterkg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.wangdashe.top/Article/details/gtajzdajfh.html

Ruby: s.bytesize;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtvmlqssbi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xinyue.icu/Article/details/gtkuhsgwpi.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtanydppnu.html

F. 文件与目录
来源：http://dali.yangfankeji.com/Article/details/gtfcwrzdcw.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtojsimyrr.html

[F01] 读取整个文件
来源：http://dali.chenlongwang.top/Article/details/gtrkmedfkh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yuxming.cn/Article/details/gtbzzjhntj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtjumrojpm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj202588.top/Article/details/gtynrxpajx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gtijqvxjkc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagfrhunn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yonumen.top/Article/details/gtnboujpgd.html

Ruby: File.read("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtpqwfbjhz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gthrdoqebf.html

[F02] 逐行读取文件
来源：http://dali.zhongyouzk.top/Article/details/gtydkrrcwx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hfpthk.cn/Article/details/gtkcdkvctq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.pycfn.com/Article/details/gtjyhdkqbq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xinyue.icu/Article/details/gtvjqagkhm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnqzz.top/Article/details/gtcxquyqyk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sufxvd.cn/Article/details/gtszgrxoux.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sxryk.cn/Article/details/gtibocokyc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jianghu66.top/Article/details/gtnjodwasj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sysykeji.top/Article/details/gtsqawblax.html

[F03] 写入文件（覆盖）
来源：http://dali.jinqigufen.top/Article/details/gtdsjjxcgc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.redwolf501.top/Article/details/gtohrftqlw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhhtxlxa.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zycfv.cn/Article/details/gtjhjygtfg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gtsburyxks.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gtpkaptpix.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yanxiufei.cn/Article/details/gtahgscmaj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guannengcc.top/Article/details/gtnxazlrvt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gtbjqygljf.html

[F04] 追加写入文件
来源：http://dali.guowangkeji.top/Article/details/gtqekzjcma.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.daxiang520.top/Article/details/gtrmhuarll.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgufenzy.top/Article/details/gthuysdvkr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shzxlz.cn/Article/details/gteszlykyz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtfnthbwto.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.mhx1999.top/Article/details/gtnlasfgnk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj20258888.top/Article/details/gtewqyfmcr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.haohaochexian.top/Article/details/gtsldkrjcj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gogol.net.cn/Article/details/gtoznukpfu.html

[F05] 判断文件或目录是否存在
来源：http://dali.xylfe.cn/Article/details/gtrlamujjr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrfmonxzi.html

PHP:  file_exists("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtqkwsnyze.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtohifelme.html

TS:   fs.existsSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtrmrykxsa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gtmukqmzgx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.c1oappe.top/Article/details/gtchgyqxwm.html

Ruby: File.exist?("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtxrmwqecv.html

C#:   File.Exists("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtxztfpklf.html

[F06] 删除文件
来源：http://dali.guowangkeji.top/Article/details/gtaeibvctz.html

Py:   os.remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtnqazjaiz.html

PHP:  unlink("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtrqxkgvxu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtvwffmdzk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtxhqiposw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtjguuzydy.html

Go:   os.Remove("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtqdpogjfw.html

Ruby: File.delete("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtizikpdpy.html

C#:   File.Delete("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtmeleouwn.html

[F07] 创建目录（含多级）
来源：http://dali.xuetiantiany.cn/Article/details/gtmwiueswa.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cqqwz.cn/Article/details/gtoqkojrzv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ydzc1.top/Article/details/gtqqkcjati.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgufenzy.top/Article/details/gtyfhrsmbj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigufen.top/Article/details/gtqohliuxj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xziqi.cn/Article/details/gtyvxprcft.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jianghu66.top/Article/details/gtnbupawwb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhiwuduotai.top/Article/details/gtaxvvgbwh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hongshengwenyu.top/Article/details/gtkkhofwyh.html

[F08] 遍历目录
来源：http://dali.xylfe.cn/Article/details/gttzlkffew.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqyzyvky.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.havefunace.top/Article/details/gtdwtvojby.html

JS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gtiawfujsy.html

TS:   fs.readdirSync("dir")
来源：http://dali.c1oappe.top/Article/details/gtrsemzeup.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dianchejie.cn/Article/details/gtujymtbkv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtlupwwxac.html

Ruby: Dir.children("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbynxttcb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yangfankeji.com/Article/details/gtlymkoeaf.html

[F09] 获取文件大小
来源：http://dali.yj202588.top/Article/details/gtatstfayj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtqnvwkgvr.html

PHP:  filesize("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gterhhixjx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnxiangtu.top/Article/details/gtdaaboumg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gturpfakgf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtycztifia.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj202588.top/Article/details/gtjiitsyqz.html

Ruby: File.size("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtucxbsyha.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shuidangran.top/Article/details/gtztzwswhv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.snrcjt.cn/Article/details/gtlqojkpyy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtmvjqiaui.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xinyue.icu/Article/details/gtulupmyga.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtxllrpins.html

TS:   path.extname("a.txt")
来源：http://dali.cucudq.cn/Article/details/gttkgectmy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.daria6918.cn/Article/details/gtvujpoyro.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtpighvkuo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtmuorbgiv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtyxislcao.html

[F11] 复制与移动文件
来源：http://dali.dashuyun.cn/Article/details/gtovaapvpp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtodvfzyvu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.haohaochexian.top/Article/details/gtbtnccemq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtehhvbtvz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtqnegblhi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gtgkeyxljc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.bjfxy.top/Article/details/gtnvuotrcr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtxetvrpyp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yangfankeji.com/Article/details/gtnqfyvohp.html

[F12] CSV 读写
来源：http://dali.dianchejie.cn/Article/details/gtnqdttkcd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.fengsongda.top/Article/details/gtumayipox.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhengqikj.top/Article/details/gtlfmevfpd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.dashuyun.cn/Article/details/gthdqwuyhy.html

TS:   // 同上
来源：http://dali.yvedp.cn/Article/details/gtazolfwaz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hysaishi.cn/Article/details/gtvcqjnaxe.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.fzhhl.top/Article/details/gtseicvwyd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pycfn.com/Article/details/gteyanzdoa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hywenlv.cn/Article/details/gttpazjceu.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtsqllfkok.html

G. 面向对象
来源：http://dali.chenlongwang.top/Article/details/gtcrzdfovj.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtsilcrybd.html

[G01] 定义类
来源：http://dali.c1oappe.top/Article/details/gtylfqghba.html

Py:   class User: pass
来源：http://dali.svipenyu.cn/Article/details/gtetgirbes.html

PHP:  class User {}
来源：http://dali.guannengcc.top/Article/details/gtxrgyubev.html

JS:   class User {}
来源：http://dali.cheryme.top/Article/details/gtzbvyaiby.html

TS:   class User { name: string = ""; }
来源：http://dali.sxryk.cn/Article/details/gtlvzjvpub.html

Java: class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtmmojmdio.html

Go:   type User struct { Name string }
来源：http://dali.bjfxy.top/Article/details/gtuxzxspzt.html

Ruby: class User; end
来源：http://dali.mhx1999.top/Article/details/gtllxejoht.html

C#:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtpfrxqgxy.html

[G02] 构造函数
来源：http://dali.aibaodan.cn/Article/details/gtqlpbuhmn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258.top/Article/details/gtlyfbaewi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhongyouzk.top/Article/details/gtyapsiryx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gtrafjejaa.html

TS:   constructor(public name: string) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvxoskim.html

Java: User(String name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gtzfluqnvs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sufxvd.cn/Article/details/gtzirbqxgv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fzhhl.top/Article/details/gtdhaowqsk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvlyaqgz.html

[G03] 实例属性
来源：http://dali.tanke756.top/Article/details/gtofhamzey.html

Py:   self.name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwleumwu.html

PHP:  public string $name = "x";
来源：http://dali.chenlongwang.top/Article/details/gtcdrlcfvl.html

JS:   this.name = "x";
来源：http://dali.ivvv.top/Article/details/gtoglurffg.html

TS:   name: string = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtkijlrdvq.html

Java: private String name;
来源：http://dali.sufxvd.cn/Article/details/gtapmucaqr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.9152youxi.cn/Article/details/gtyoonvzba.html

Ruby: @name = "x"
来源：http://dali.chenlongwang.top/Article/details/gtrbadfysf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hfpthk.cn/Article/details/gtcpbhanva.html

[G04] 定义方法
来源：http://dali.xuanzx.com/Article/details/gtfrvaxmdn.html

Py:   def greet(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gtkeldkzfi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gttjkaqdef.html

JS:   greet() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtzczwcklu.html

TS:   greet(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gticqbivfw.html

Java: String greet() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtjvppqdrp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtjorhyzhf.html

Ruby: def greet; @name; end
来源：http://dali.aibaodan.cn/Article/details/gtxqzrovdz.html

C#:   public string Greet() => Name;
来源：http://dali.gzhubu.top/Article/details/gtplayqdhm.html

[G05] 继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfkvayftw.html

Py:   class Admin(User): pass
来源：http://dali.aibaodan.cn/Article/details/gtrrvkkhqf.html

PHP:  class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtqzhllgmt.html

JS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtbsbjdisg.html

TS:   class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtkqevidfq.html

Java: class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtpgbjgrss.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guannengcc.top/Article/details/gtqzvbmseh.html

Ruby: class Admin < User; end
来源：http://dali.hnqzz.top/Article/details/gtdznhwdac.html

C#:   class Admin : User {}
来源：http://dali.daxiang520.top/Article/details/gtjnhmgzef.html

[G06] 重写方法
来源：http://dali.dashuyun.cn/Article/details/gtwioxvnze.html

Py:   def greet(self): return "admin"
来源：http://dali.yj202588.top/Article/details/gtkswmaiwp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtzcifzyte.html

JS:   greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtlggcatsa.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtftcooodh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtttcorkjl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.dianchejie.cn/Article/details/gtowxmrlmn.html

Ruby: def greet; "admin"; end
来源：http://dali.hnqzz.top/Article/details/gtzmpwivww.html

C#:   public override string Greet() => "admin";
来源：http://dali.yvedp.cn/Article/details/gtyxtmaphh.html

[G07] 调用父类方法
来源：http://dali.wangshuangyany.cn/Article/details/gtkbefvrhs.html

Py:   super().greet()
来源：http://dali.hnqzz.top/Article/details/gtmgsibjzj.html

PHP:  parent::greet();
来源：http://dali.cheryme.top/Article/details/gtlubevbyu.html

JS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtywhihrom.html

TS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gtxbjwjcpd.html

Java: super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtuabdcpwf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gzhubu.top/Article/details/gtsrhpeksc.html

Ruby: super
来源：http://dali.zhixingplan.top/Article/details/gtjpxemdcs.html

C#:   base.Greet();
来源：http://dali.zhengqikj.top/Article/details/gthnytprua.html

[G08] 静态方法与属性
来源：http://dali.hnqzz.top/Article/details/gtlzdvfjpu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.redwolf501.top/Article/details/gtqlruegaz.html

PHP:  public static function f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtirghazkv.html

JS:   static f() {}
来源：http://dali.cdnleiting.top/Article/details/gtdbaehvsi.html

TS:   static f(): void {}
来源：http://dali.yonumen.top/Article/details/gthhrxflwg.html

Java: static void f() {}
来源：http://dali.jqgfzy.top/Article/details/gtdkszfaox.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guowangkeji.top/Article/details/gtlwuoqfhs.html

Ruby: def self.f; end
来源：http://dali.hywenlv.cn/Article/details/gtgkeadmdf.html

C#:   public static void F() {}
来源：http://dali.snrcjt.cn/Article/details/gtreujtzcb.html

[G09] 接口 / 抽象类
来源：http://dali.jqgufenzy.top/Article/details/gtltpvszui.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.havefunace.top/Article/details/gtugkueupn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.havefunace.top/Article/details/gtwnrqgeig.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxtufruop.html

TS:   interface Shape { area(): number; }
来源：http://dali.yonumen.top/Article/details/gtgpugwbfk.html

Java: interface Shape { double area(); }
来源：http://dali.hnqzz.top/Article/details/gtxmqsdvee.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pengpengdd.cyou/Article/details/gtqvrzgdqp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.quarkkingdee.top/Article/details/gtqykkvkix.html

C#:   interface IShape { double Area(); }
来源：http://dali.smart0.xyz/Article/details/gtdkohoxft.html

[G10] 访问控制
来源：http://dali.redwolf501.top/Article/details/gtiwghwpzl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.pengpengdd.cyou/Article/details/gtroinogto.html

PHP:  public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtryqlwvdk.html

JS:   #private 字段；其余公开
来源：http://dali.fzhhl.top/Article/details/gtwkocfkvi.html

TS:   public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtfjknoike.html

Java: public / protected / private / 默认包级
来源：http://dali.hnqzz.top/Article/details/gthsuimmla.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hammf.cn/Article/details/gtrrjkujvn.html

Ruby: public / protected / private
来源：http://dali.yj202588.top/Article/details/gtbztkokdd.html

C#:   public / protected / private / internal
来源：http://dali.quarkkingdee.top/Article/details/gtnhbwbjrt.html

[G11] getter / setter
来源：http://dali.gzhubu.top/Article/details/gtuvndrjya.html

Py:   @property 与 @x.setter
来源：http://dali.cucudq.cn/Article/details/gtijunscpr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtbouynfri.html

JS:   get name() { return this._name; }
来源：http://dali.meibo888.top/Article/details/gtwkylwvtf.html

TS:   get name(): string { return this._name; }
来源：http://dali.cheryme.top/Article/details/gtaqsbrevu.html

Java: public String getName() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtahdjhmke.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gtdhzupnly.html

Ruby: attr_accessor :name
来源：http://dali.quarkkingdee.top/Article/details/gtwvazsvgi.html

C#:   public string Name { get; set; }
来源：http://dali.0kj1m.cn/Article/details/gtsrwyldaa.html

[G12] 对象转字符串
来源：http://dali.ydzc1.top/Article/details/gtggzywvff.html

Py:   def __str__(self): return self.name
来源：http://dali.dianchejie.cn/Article/details/gtqgkoxxhj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gtugunsjmp.html

JS:   toString() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtgqxpjljv.html

TS:   toString(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtpkkeqkti.html

Java: @Override public String toString() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gttgjgbjxu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtngvgpdzw.html

Ruby: def to_s; @name; end
来源：http://dali.ybcxt.top/Article/details/gtuehzxmlp.html

C#:   public override string ToString() => Name;
来源：http://dali.quarkkingdee.top/Article/details/gtvhlaxuwx.html

[G13] 判断对象类型
来源：http://dali.jianghu66.top/Article/details/gtpziduwjb.html

Py:   isinstance(u, User)
来源：http://dali.meibo888.top/Article/details/gteznmgejk.html

PHP:  $u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtzulsqrqv.html

JS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gtpdfljngn.html

TS:   u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtnrcrlqpd.html

Java: u instanceof User
来源：http://dali.havefunace.top/Article/details/gtotobmuau.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sweek.top/Article/details/gtbflxatxb.html

Ruby: u.is_a?(User)
来源：http://dali.kuanghao11.cn/Article/details/gtsbpwjswe.html

C#:   u is User
来源：http://dali.zhiwuduotai.top/Article/details/gteukwyenb.html

[G14] 数据类 / record
来源：http://dali.zhiwuduotai.top/Article/details/gtrdgchdga.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yanxiufei.cn/Article/details/gtbgwhijcc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xylfe.cn/Article/details/gtjgbqhtjc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.bjfxy.top/Article/details/gtmjhhnnnk.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhixingplan.top/Article/details/gtwthnoyyi.html

Java: record User(String name, int age) {}
来源：http://dali.nanxuanxn.top/Article/details/gtstvgblku.html

Go:   type User struct { Name string; Age int }
来源：http://dali.c1oappe.top/Article/details/gtcpcbljff.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shzxlz.cn/Article/details/gtkqqzgsye.html

C#:   record User(string Name, int Age);
来源：http://dali.zhoulong.xyz/Article/details/gtwlezrddb.html

[G15] 枚举
来源：http://dali.yj202588.top/Article/details/gtxialnzya.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.haohaochexian.top/Article/details/gtnajfxuod.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.c1oappe.top/Article/details/gtstoyxjsl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.birdmap.top/Article/details/gtnssgwxqr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gthnbmakzw.html

Java: enum Color { RED, GREEN }
来源：http://dali.ybcxt.top/Article/details/gtpxghoeaz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhoulong.xyz/Article/details/gtfhpiboqf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangkeji.top/Article/details/gthodwohex.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtbywvolks.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gtlsqfrrki.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fzhhl.top/Article/details/gtedgcnypt.html

PHP:  get_object_vars($obj);
来源：http://dali.wangdashe.top/Article/details/gtmjgurvqz.html

JS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsciifzza.html

TS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gtezsbhrat.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jiagoushi.top/Article/details/gtfptbjdfm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jiagoushi.top/Article/details/gtszmytmtp.html

Ruby: obj.instance_variables
来源：http://dali.haohaochexian.top/Article/details/gtiotmtbqq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hammf.cn/Article/details/gteaejyohv.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtzdkdeixu.html

H. 异常与错误处理
来源：http://dali.jinghuilouyu.cn/Article/details/gteoyrasok.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtbyfidlvk.html

[H01] try / catch 基础
来源：http://dali.c1oappe.top/Article/details/gtvcjjnone.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.birdmap.top/Article/details/gtylesqyej.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cucudq.cn/Article/details/gtpcipidtz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gtqqowzxec.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gtedrzhvlb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.guannengcc.top/Article/details/gtjoyvtjuv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aizwys.cn/Article/details/gtsxpbcxoa.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.guowangkeji.top/Article/details/gtkfsxqlsg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.pengpengdd.cyou/Article/details/gtphsvpipb.html

[H02] finally / ensure 收尾
来源：http://dali.bjfxy.top/Article/details/gtywmqazqz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.bjfxy.top/Article/details/gtjsvuxdal.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gttfkiabhb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtumfwzlgw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gteylvfpcp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtfkunguuc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ehwqpu.com/Article/details/gtghebedep.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hfpthk.cn/Article/details/gtuxgupezy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hammf.cn/Article/details/gttabrchbm.html


<!-- 参考信息 -->