代发 wailian999

Go:   if s == "" {}
来源：http://dali.0kj1m.cn/Article/details/gtudjilcom.html

Ruby: if s.empty?
来源：http://dali.yueranfly.top/Article/details/gtjihmfqtn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.redwolf501.top/Article/details/gtwojarczi.html

[E21] 超长截断加省略号
来源：http://dali.meibo888.top/Article/details/gtweehcmln.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nanxuanxn.top/Article/details/gthipttjry.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gtaonwbppj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxyilguj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtnevthbxf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtrjjeqqei.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yanxiufei.cn/Article/details/gtcnypdfqj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtldwvtubn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtzxgjhjmn.html

[E22] 字节长度与字符长度
来源：http://dali.vqdsnc.cn/Article/details/gtgzhaevgu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cashguo.top/Article/details/gtsxttdcjt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sweek.top/Article/details/gttnxpmyiv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daria6918.cn/Article/details/gtjcfxieyw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.haohaochexian.top/Article/details/gtyclkhrdr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cqqwz.cn/Article/details/gtoddugmwp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj20258888.top/Article/details/gthpwvxjcj.html

Ruby: s.bytesize;  s.length
来源：http://dali.aibaodan.cn/Article/details/gtcvevnfbz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gzhubu.top/Article/details/gtszrimjfd.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtzkyokhft.html

F. 文件与目录
来源：http://dali.quarkkingdee.top/Article/details/gtbaqozymc.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtuqyirfwk.html

[F01] 读取整个文件
来源：http://dali.redwolf501.top/Article/details/gtjamyxuqg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nanxinkj.top/Article/details/gtnlibuhoy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tanke756.top/Article/details/gtbtcwmers.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nanxuanxn.top/Article/details/gtojfzcadx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.andypj.xyz/Article/details/gthxbenxsd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gtwdhszagb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sufxvd.cn/Article/details/gtlycmiqdg.html

Ruby: File.read("a.txt")
来源：http://dali.cashguo.top/Article/details/gtrjskaiem.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtyrjrftez.html

[F02] 逐行读取文件
来源：http://dali.gotoacloud.top/Article/details/gtaoaejxyl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.redwolf501.top/Article/details/gtlgyxlyju.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.redwolf501.top/Article/details/gterdznlxx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gtrdqzednd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gttoxlfczg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shangyingyoupin.top/Article/details/gtmmieczdr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthpikixll.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinqigufen.top/Article/details/gtkvbfvxhp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zdqjudy.top/Article/details/gtuvescfri.html

[F03] 写入文件（覆盖）
来源：http://dali.chenzaomai.com/Article/details/gtstwrgkvb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ivvv.top/Article/details/gtqjegbkrv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gtdckayfkz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gtldelzslk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gtkpwlkyjp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gogol.net.cn/Article/details/gtepoyeasn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xziqi.cn/Article/details/gtvernrtwv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj20258888.top/Article/details/gtzlmoryls.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nanxinkj.top/Article/details/gtgpwbzdck.html

[F04] 追加写入文件
来源：http://dali.nwbrower.top/Article/details/gtxugegoxc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cdnleiting.top/Article/details/gtzaxegbfp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhiwuduotai.top/Article/details/gtrrimpuzo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnvczdldu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dashuyun.cn/Article/details/gtcbwwcmse.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gaohongyu789.top/Article/details/gtubgfgkcc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yangfankeji.com/Article/details/gtjmgrevct.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ehwqpu.com/Article/details/gtpaeskkjn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlnjaytgw.html

[F05] 判断文件或目录是否存在
来源：http://dali.mhx1999.top/Article/details/gtzmexctxz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ybcxt.top/Article/details/gtqdrxarhr.html

PHP:  file_exists("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtgvqydksx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtqslwzuyy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtdjwgwhqq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtucxjgsmd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cqqwz.cn/Article/details/gtvaptqaio.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258888.top/Article/details/gttjumwkgo.html

C#:   File.Exists("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtljxkhklh.html

[F06] 删除文件
来源：http://dali.sweek.top/Article/details/gtbrwirnys.html

Py:   os.remove("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtafsohvft.html

PHP:  unlink("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtsdztnuwf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtrxqjkhkf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtjjskthdg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtmnboiimv.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzfxkefmr.html

Ruby: File.delete("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtbfmfmfxa.html

C#:   File.Delete("a.txt");
来源：http://dali.yj20258.top/Article/details/gtvmldglky.html

[F07] 创建目录（含多级）
来源：http://dali.dianchejie.cn/Article/details/gtixcigudm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtftxmdaes.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.havefunace.top/Article/details/gtvtvlevxp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dianchejie.cn/Article/details/gtsqmxyywy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.0kj1m.cn/Article/details/gtfkokhuuo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.kuanghao11.cn/Article/details/gtafcupmkf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.svipenyu.cn/Article/details/gtdisdlkre.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.wangdashe.top/Article/details/gtorlzoaas.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhengqikj.top/Article/details/gtxfhxzzws.html

[F08] 遍历目录
来源：http://dali.xziqi.cn/Article/details/gtsiwdxpiz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxdrbxez.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsgoqfyxv.html

JS:   fs.readdirSync("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtaridludd.html

TS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gtijfbifvy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shangyingyoupin.top/Article/details/gtnihxyxbs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtwwvhbm.html

Ruby: Dir.children("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwuekvgt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtrvnfddsg.html

[F09] 获取文件大小
来源：http://dali.yj20258.top/Article/details/gtftryyege.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtmrxkbdkw.html

PHP:  filesize("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtpgcximei.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gtjpdkools.html

TS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gtqzpfwhju.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtcqoccbrm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hongshengwenyu.top/Article/details/gtwnzuwxuj.html

Ruby: File.size("a.txt")
来源：http://dali.yonumen.top/Article/details/gtogejrefe.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.guannengcc.top/Article/details/gtwpdfhgzf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yonumen.top/Article/details/gtcezwbanc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtcyhlhmxv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtsxirfcwm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtgcimiabt.html

TS:   path.extname("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtezocglhc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yonumen.top/Article/details/gtroaeeqfl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtywaacwuc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtbekeemus.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtsispgeqc.html

[F11] 复制与移动文件
来源：http://dali.nwbrower.top/Article/details/gtwxgqnwwh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtckvbeumz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cashguo.top/Article/details/gtquneihcg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtdsvaqrud.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtlvwltmee.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj20258.top/Article/details/gtidyhpbbk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkkqjjdp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtohbuahxt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shangyingyoupin.top/Article/details/gtexrrtlqf.html

[F12] CSV 读写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiauclfae.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhoulong.xyz/Article/details/gtrsldadvs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.0kj1m.cn/Article/details/gtbylbkstu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gzhubu.top/Article/details/gtmftqfvdy.html

TS:   // 同上
来源：http://dali.316326.xyz/Article/details/gthrfkulot.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhengqikj.top/Article/details/gtvftmprar.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cqqwz.cn/Article/details/gtdlczovch.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.feifeiyinyue.top/Article/details/gtfrbndudn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hywenlv.cn/Article/details/gttsdsmakj.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtjspehnes.html

G. 面向对象
来源：http://dali.feifeiyinyue.top/Article/details/gtckirkljm.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtqjzzudsp.html

[G01] 定义类
来源：http://dali.chenzaomai.com/Article/details/gtekhbglya.html

Py:   class User: pass
来源：http://dali.sufxvd.cn/Article/details/gtgnhtbrqk.html

PHP:  class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtkpglsavp.html

JS:   class User {}
来源：http://dali.redwolf501.top/Article/details/gtupuehogw.html

TS:   class User { name: string = ""; }
来源：http://dali.zhongyouzk.top/Article/details/gtaeynlxgk.html

Java: class User {}
来源：http://dali.yueranfly.top/Article/details/gtgpjkzljc.html

Go:   type User struct { Name string }
来源：http://dali.0kj1m.cn/Article/details/gtoibhwopv.html

Ruby: class User; end
来源：http://dali.tian-w.cn/Article/details/gteuvligsj.html

C#:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtfwucmhzl.html

[G02] 构造函数
来源：http://dali.ehwqpu.com/Article/details/gttbjjmglh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldexlfav.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.andypj.xyz/Article/details/gtaeeyvpxe.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gtiqdhfigm.html

TS:   constructor(public name: string) {}
来源：http://dali.cashguo.top/Article/details/gtsxsqgrnk.html

Java: User(String name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gtfxzzvjdn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ppjwa.cn/Article/details/gtifwlytjw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sufxvd.cn/Article/details/gtooneaxuf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tanke756.top/Article/details/gtwgpbeade.html

[G03] 实例属性
来源：http://dali.yj20258.top/Article/details/gthvkehznk.html

Py:   self.name = "x"
来源：http://dali.hnxiangtu.top/Article/details/gtmvzetkpg.html

PHP:  public string $name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gteqanufun.html

JS:   this.name = "x";
来源：http://dali.zhengqikj.top/Article/details/gtkohuawsd.html

TS:   name: string = "x";
来源：http://dali.yuxming.cn/Article/details/gtykvsjdsu.html

Java: private String name;
来源：http://dali.hywenlv.cn/Article/details/gtczjwxnhm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhvoniwc.html

Ruby: @name = "x"
来源：http://dali.tianlin.xyz/Article/details/gthxrizrzv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtcluwmgdh.html

[G04] 定义方法
来源：http://dali.jyoumei.cn/Article/details/gtwdazfffg.html

Py:   def greet(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gtgcsytpfa.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gtdghaxrqv.html

JS:   greet() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtqrqpfcqr.html

TS:   greet(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtvobcjmls.html

Java: String greet() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtfemgteck.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gtlyvfyfei.html

Ruby: def greet; @name; end
来源：http://dali.yueranfly.top/Article/details/gtsfjfffta.html

C#:   public string Greet() => Name;
来源：http://dali.dashuyun.cn/Article/details/gtmnizlsjp.html

[G05] 继承
来源：http://dali.hfpthk.cn/Article/details/gtcnhjnafz.html

Py:   class Admin(User): pass
来源：http://dali.jianghu66.top/Article/details/gtauehmvrx.html

PHP:  class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gttaisadoc.html

JS:   class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gttssyzbze.html

TS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtbmdzwqcl.html

Java: class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtjoldqjmo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.wangshuangyany.cn/Article/details/gtzfxltmsu.html

Ruby: class Admin < User; end
来源：http://dali.hfpthk.cn/Article/details/gtwlyrmbtw.html

C#:   class Admin : User {}
来源：http://dali.havefunace.top/Article/details/gtmogccffm.html

[G06] 重写方法
来源：http://dali.zhengqikj.top/Article/details/gtzyjvcsts.html

Py:   def greet(self): return "admin"
来源：http://dali.sufxvd.cn/Article/details/gtmqhpqnxk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtskgpuhrs.html

JS:   greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtwunorbph.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtnsayumam.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gttnwggdkd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shangyingyoupin.top/Article/details/gtngvhmsxh.html

Ruby: def greet; "admin"; end
来源：http://dali.chenzaomai.com/Article/details/gtxwbucmuc.html

C#:   public override string Greet() => "admin";
来源：http://dali.gzhubu.top/Article/details/gtxuspgtvi.html

[G07] 调用父类方法
来源：http://dali.iojbl.cn/Article/details/gtykzdybdk.html

Py:   super().greet()
来源：http://dali.jyoumei.cn/Article/details/gthutowyng.html

PHP:  parent::greet();
来源：http://dali.xuanzx.com/Article/details/gtdgrifjqn.html

JS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gtgikilymn.html

TS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtfcpjfqzh.html

Java: super.greet();
来源：http://dali.yuxming.cn/Article/details/gtqhmnvdkr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.fzhhl.top/Article/details/gttxkdtmjp.html

Ruby: super
来源：http://dali.jqgufenzy.top/Article/details/gtrrucftsi.html

C#:   base.Greet();
来源：http://dali.zhengqikj.top/Article/details/gtbbtxvfne.html

[G08] 静态方法与属性
来源：http://dali.ehwqpu.com/Article/details/gtgtbqfdau.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenlongwang.top/Article/details/gtfsmswuro.html

PHP:  public static function f() {}
来源：http://dali.aibaodan.cn/Article/details/gtpdpvjpet.html

JS:   static f() {}
来源：http://dali.daria6918.cn/Article/details/gtqiwvcqcb.html

TS:   static f(): void {}
来源：http://dali.yj202588.top/Article/details/gtepsckeko.html

Java: static void f() {}
来源：http://dali.sweek.top/Article/details/gtweltftff.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhengqikj.top/Article/details/gtkivgehyi.html

Ruby: def self.f; end
来源：http://dali.jinqigufen.top/Article/details/gtbzadsacc.html

C#:   public static void F() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtgycchnrn.html

[G09] 接口 / 抽象类
来源：http://dali.fzhhl.top/Article/details/gtksaebnkj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.andypj.xyz/Article/details/gtfwfdwtgw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258.top/Article/details/gtlmzsvihh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkjqoxkoe.html

TS:   interface Shape { area(): number; }
来源：http://dali.guowangkeji.top/Article/details/gtvivfllvh.html

Java: interface Shape { double area(); }
来源：http://dali.pycfn.com/Article/details/gtlgcrvoxo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yvedp.cn/Article/details/gtufitimfx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xylfe.cn/Article/details/gtfribygbe.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigufen.top/Article/details/gtvoeewfhw.html

[G10] 访问控制
来源：http://dali.fengsongda.top/Article/details/gtkpdlwpgk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.smart0.xyz/Article/details/gtgrnqqosw.html

PHP:  public / protected / private
来源：http://dali.sweek.top/Article/details/gtxgkovobg.html

JS:   #private 字段；其余公开
来源：http://dali.jqgfzy.top/Article/details/gtosdcqlhz.html

TS:   public / protected / private
来源：http://dali.tanke756.top/Article/details/gtjagfcmlg.html

Java: public / protected / private / 默认包级
来源：http://dali.shangyingyoupin.top/Article/details/gtprhupavm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cucudq.cn/Article/details/gtrjbxahrk.html

Ruby: public / protected / private
来源：http://dali.hnqzz.top/Article/details/gtofodretz.html

C#:   public / protected / private / internal
来源：http://dali.xinyue.icu/Article/details/gtrfvsuxyz.html

[G11] getter / setter
来源：http://dali.yuanzhike.top/Article/details/gtsmcyrgxw.html

Py:   @property 与 @x.setter
来源：http://dali.bjfxy.top/Article/details/gtsbjyvbhp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gtflkmswrq.html

JS:   get name() { return this._name; }
来源：http://dali.xziqi.cn/Article/details/gtpmwsropv.html

TS:   get name(): string { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gtrheheunb.html

Java: public String getName() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpeoppies.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gtnaorqvhc.html

Ruby: attr_accessor :name
来源：http://dali.sxryk.cn/Article/details/gtvpwfokww.html

C#:   public string Name { get; set; }
来源：http://dali.cqqwz.cn/Article/details/gtkfrngyfz.html

[G12] 对象转字符串
来源：http://dali.meibo888.top/Article/details/gthbtntetf.html

Py:   def __str__(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gtsnzvbnbo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gtuoifmjst.html

JS:   toString() { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtgznhkzex.html

TS:   toString(): string { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtychewxop.html

Java: @Override public String toString() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtgtjjguus.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtkldnzuvg.html

Ruby: def to_s; @name; end
来源：http://dali.sufxvd.cn/Article/details/gtspicycxc.html

C#:   public override string ToString() => Name;
来源：http://dali.quarkkingdee.top/Article/details/gtebyepkjc.html

[G13] 判断对象类型
来源：http://dali.guannengcc.top/Article/details/gtsecvnvek.html

Py:   isinstance(u, User)
来源：http://dali.meibo888.top/Article/details/gtbpynxsak.html

PHP:  $u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtetvnxeyy.html

JS:   u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtdgfanqza.html

TS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtlvxmkftq.html

Java: u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtqofocjlr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yongpay.top/Article/details/gtofcqjlgw.html

Ruby: u.is_a?(User)
来源：http://dali.tanke756.top/Article/details/gtvtdlsbqk.html

C#:   u is User
来源：http://dali.xziqi.cn/Article/details/gtmshzcsbk.html

[G14] 数据类 / record
来源：http://dali.nanxuanxn.top/Article/details/gtsualzkuu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.svipenyu.cn/Article/details/gtkfgwopyp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pycfn.com/Article/details/gtyzwrzoxm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.c1oappe.top/Article/details/gtykbpwtbh.html

TS:   type User = { name: string; age: number };
来源：http://dali.yuanzhike.top/Article/details/gtrpmgnvov.html

Java: record User(String name, int age) {}
来源：http://dali.smart0.xyz/Article/details/gtytdujuui.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sufxvd.cn/Article/details/gtduydmhub.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shanyushiyangkeji.top/Article/details/gthfqaglbh.html

C#:   record User(string Name, int Age);
来源：http://dali.tian-w.cn/Article/details/gttjlfxsyh.html

[G15] 枚举
来源：http://dali.gzhubu.top/Article/details/gtlnadegpz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinqigufen.top/Article/details/gtdigxeqcw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xylfe.cn/Article/details/gtgbwcvhtl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.fzhhl.top/Article/details/gtlefecvnd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtirbxbmst.html

Java: enum Color { RED, GREEN }
来源：http://dali.mhx1999.top/Article/details/gthghqxicv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jianghu66.top/Article/details/gtmlainvti.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ivvv.top/Article/details/gtcarqmxsm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jyoumei.cn/Article/details/gtqtobihkk.html

[G16] 对象转数组 / 字典
来源：http://dali.smart0.xyz/Article/details/gtmcjqkgjx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jlsjyb.cn/Article/details/gtpzevwgdf.html

PHP:  get_object_vars($obj);
来源：http://dali.quarkkingdee.top/Article/details/gteknotbdw.html

JS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gtvwqnznxn.html

TS:   Object.entries(obj)
来源：http://dali.cdnleiting.top/Article/details/gttalhaohb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.c1oappe.top/Article/details/gtjxjpplkb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnslnwdhz.html

Ruby: obj.instance_variables
来源：http://dali.sweek.top/Article/details/gtghdbygbf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.birdmap.top/Article/details/gtnzqpwsbe.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtneuzdcik.html

H. 异常与错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gtxbfzscag.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtfjmbreyz.html

[H01] try / catch 基础
来源：http://dali.wangdashe.top/Article/details/gtdubhxykk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.daxiang520.top/Article/details/gtooseaujk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jianghu66.top/Article/details/gtbtdiyohm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gtuybmkexp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtditvzfxp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tanke756.top/Article/details/gtfwhbessm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ybcxt.top/Article/details/gtnbgcpmpf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yuxming.cn/Article/details/gtowbrerjz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hongshengwenyu.top/Article/details/gtfpyhmqge.html

[H02] finally / ensure 收尾
来源：http://dali.cashguo.top/Article/details/gttwbajdgd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.redwolf501.top/Article/details/gtpqonipjx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtyiuociqg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtxuafjfgo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjyszcwcl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtgpkaplhm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yongpay.top/Article/details/gtrctfyqkx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.redwolf501.top/Article/details/gttwoezhhj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtxiicmazz.html


<!-- 参考信息 -->