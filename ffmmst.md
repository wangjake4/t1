代发 wailian999

Ruby: s.lines
来源：http://dali.jianghu66.top/Article/details/gtyiinguhc.html

C#:   s.Split('\n')
来源：http://dali.feifeiyinyue.top/Article/details/gtgnbwtxzm.html

[E20] 判断字符串是否为空
来源：http://dali.hfpthk.cn/Article/details/gtxtrbtgjr.html

Py:   if not s:
来源：http://dali.hfpthk.cn/Article/details/gtaetbbuta.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jlsjyb.cn/Article/details/gthguclnuu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yangfankeji.com/Article/details/gtquakalae.html

TS:   if (s === "") {}
来源：http://dali.hongshengwenyu.top/Article/details/gtbyaaghni.html

Java: if (s.isEmpty()) {}
来源：http://dali.aibaodan.cn/Article/details/gtlxfbjkjb.html

Go:   if s == "" {}
来源：http://dali.tanke756.top/Article/details/gtceftnucn.html

Ruby: if s.empty?
来源：http://dali.yj20258.top/Article/details/gtaueqssqc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.0kj1m.cn/Article/details/gtnnejpdyv.html

[E21] 超长截断加省略号
来源：http://dali.xylfe.cn/Article/details/gtrishiefg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yvedp.cn/Article/details/gtyskdodww.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtmorjgiff.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtoonvkbac.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gtbtubhuxi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtygufpfqb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zdqjudy.top/Article/details/gtfzjjucng.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtinoreyig.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwtzkkge.html

[E22] 字节长度与字符长度
来源：http://dali.shuidangran.top/Article/details/gtubryzmuw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ehwqpu.com/Article/details/gtpnaupfex.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtiflncmoj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuanzhike.top/Article/details/gtkqdehepi.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtweqdclaq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.redwolf501.top/Article/details/gtioeycwta.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pycfn.com/Article/details/gtjezwinbx.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gtovhrhmat.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.snrcjt.cn/Article/details/gtbuattldw.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtqvwpvbio.html

F. 文件与目录
来源：http://dali.cqqwz.cn/Article/details/gtckhngeau.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtigguikju.html

[F01] 读取整个文件
来源：http://dali.xuetiantiany.cn/Article/details/gtoclvxewx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shzxlz.cn/Article/details/gteqbksplh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtpnqmgion.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tianlin.xyz/Article/details/gtopiahdhm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gtwqarogao.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gtdxkjwyxj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.havefunace.top/Article/details/gtyqjmqjsf.html

Ruby: File.read("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtrxgifmqk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtvfqsrtxy.html

[F02] 逐行读取文件
来源：http://dali.sufxvd.cn/Article/details/gtwzxjsezj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ppjwa.cn/Article/details/gtumekxayl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hnqzz.top/Article/details/gtjyfuhmxx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gtdyrpbjcu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxejscwcf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gtignfdzfl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pycfn.com/Article/details/gtbjcakwuz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfciefba.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shuidangran.top/Article/details/gtmzdjkibn.html

[F03] 写入文件（覆盖）
来源：http://dali.yj202588.top/Article/details/gtxmnhcqcs.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhengqikj.top/Article/details/gtdwvtekkk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gtssaitkyo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cheryme.top/Article/details/gtmzbiaqck.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtmwsjtuge.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cheryme.top/Article/details/gtlnphczoz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.aibaodan.cn/Article/details/gtqjuakuog.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.vqdsnc.cn/Article/details/gtskmwscsa.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.daxiang520.top/Article/details/gtwafbzdto.html

[F04] 追加写入文件
来源：http://dali.gotoacloud.top/Article/details/gtboofaeek.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.andypj.xyz/Article/details/gtnvtklglj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxvihqnv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gtlvaacqwo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtymoyjide.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfzkjapzd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj202588.top/Article/details/gtzdvzhbrx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.fzhhl.top/Article/details/gtsvvhlqhq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinyuanbaomall.cn/Article/details/gthphezegi.html

[F05] 判断文件或目录是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxavflbu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gaohongyu789.top/Article/details/gthyvvrmoo.html

PHP:  file_exists("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtfugrelxz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtfwxlgiho.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtpmeaeyol.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtcoshggsr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.dianchejie.cn/Article/details/gtkfvghdbd.html

Ruby: File.exist?("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtamhbhzyi.html

C#:   File.Exists("a.txt")
来源：http://dali.yonumen.top/Article/details/gtlbxrfmmw.html

[F06] 删除文件
来源：http://dali.ivvv.top/Article/details/gtwhtsogzw.html

Py:   os.remove("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtscingils.html

PHP:  unlink("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtfgclkknq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtzletkelz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtvdsyiqpz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtwxdkximr.html

Go:   os.Remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtsoiksfeu.html

Ruby: File.delete("a.txt")
来源：http://dali.tanke756.top/Article/details/gttwvtqyxy.html

C#:   File.Delete("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtjrnfoxwb.html

[F07] 创建目录（含多级）
来源：http://dali.zdqjudy.top/Article/details/gtywebkmti.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nwbrower.top/Article/details/gtmzyojvjt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sysykeji.top/Article/details/gtwsqlgbya.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.c1oappe.top/Article/details/gtuvushyyj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dashuyun.cn/Article/details/gtnzuzoyyo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigfzy.top/Article/details/gtsmdqrwaf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.316326.xyz/Article/details/gtysybysdj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yueranfly.top/Article/details/gttqkmlmbb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhongyouzk.top/Article/details/gteuwwkbmy.html

[F08] 遍历目录
来源：http://dali.jinqigfzy.top/Article/details/gtervgoeti.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sysykeji.top/Article/details/gtksjtrugc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.andypj.xyz/Article/details/gtkuccjwfa.html

JS:   fs.readdirSync("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtxmiwdkmv.html

TS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gtfvxmgixt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gthnpkmvog.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hywenlv.cn/Article/details/gthezdwftz.html

Ruby: Dir.children("dir")
来源：http://dali.fzhhl.top/Article/details/gtucioqvmm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysvvqrgk.html

[F09] 获取文件大小
来源：http://dali.xinyue.icu/Article/details/gtxwpdejkp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnbsrqkt.html

PHP:  filesize("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtwbxbdvig.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yonumen.top/Article/details/gtwrxogojl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.haohaochexian.top/Article/details/gtzdqyocfx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnytbvydm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.aibaodan.cn/Article/details/gtqtoufsjl.html

Ruby: File.size("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtmtefxsdj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhoulong.xyz/Article/details/gtjmnrtfff.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgufenzy.top/Article/details/gtflzxukkf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gttrvtclei.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtdkkfoutg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gthfxoruqx.html

TS:   path.extname("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtmqonhxic.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cdnleiting.top/Article/details/gtvnupvmwc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtgztotwhn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtsbrshtsa.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqenycytl.html

[F11] 复制与移动文件
来源：http://dali.tian-w.cn/Article/details/gthqhfrwjk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtrqhzdwui.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daxiang520.top/Article/details/gtrkeepdbo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtvxgiyzhs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtixrjxitx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gtpirdcfut.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigufen.top/Article/details/gtzdycgnbb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtzumaovvf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cheryme.top/Article/details/gtncwauuwa.html

[F12] CSV 读写
来源：http://dali.zdqjudy.top/Article/details/gtwjmgbzlp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.haohaochexian.top/Article/details/gtfbgulydy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.havefunace.top/Article/details/gtcnezavbz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ivvv.top/Article/details/gtbeledvbz.html

TS:   // 同上
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnzywkjm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zdqjudy.top/Article/details/gtlrjyykzd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenjidiqi.icu/Article/details/gtswptzczv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yanxiufei.cn/Article/details/gttyvlbzlg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.smart0.xyz/Article/details/gthpuvfujh.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtggvjxvdj.html

G. 面向对象
来源：http://dali.daria6918.cn/Article/details/gturlbrjit.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtuwvmyrtt.html

[G01] 定义类
来源：http://dali.xziqi.cn/Article/details/gtanhcbmrq.html

Py:   class User: pass
来源：http://dali.0kj1m.cn/Article/details/gtfuxoqrwa.html

PHP:  class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrgrxcfaa.html

JS:   class User {}
来源：http://dali.mhx1999.top/Article/details/gtgmcxirqy.html

TS:   class User { name: string = ""; }
来源：http://dali.dianchejie.cn/Article/details/gtgqdjwcok.html

Java: class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtwyvsccap.html

Go:   type User struct { Name string }
来源：http://dali.guowangkeji.top/Article/details/gtogjcnwvv.html

Ruby: class User; end
来源：http://dali.nanxuanxn.top/Article/details/gtioymiryd.html

C#:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gtnpzrzcmh.html

[G02] 构造函数
来源：http://dali.jqgufenzy.top/Article/details/gtpvnefdzk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtobyckagj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nanxuanxn.top/Article/details/gtdfgxdtkm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtuoparuxa.html

TS:   constructor(public name: string) {}
来源：http://dali.yueranfly.top/Article/details/gtmhdnhxhn.html

Java: User(String name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmaqfvcbk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fzhhl.top/Article/details/gtgsknistt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aibaodan.cn/Article/details/gtilwhuqcf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtdevpydvu.html

[G03] 实例属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtokatjmtg.html

Py:   self.name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gtvsdrifyv.html

PHP:  public string $name = "x";
来源：http://dali.hywenlv.cn/Article/details/gttzxpzqtv.html

JS:   this.name = "x";
来源：http://dali.cheryme.top/Article/details/gtvncuyrns.html

TS:   name: string = "x";
来源：http://dali.yj20258888.top/Article/details/gtbiehvbwg.html

Java: private String name;
来源：http://dali.haohaochexian.top/Article/details/gteloiozsq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.feifeiyinyue.top/Article/details/gtutjrfsvm.html

Ruby: @name = "x"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvsvwifii.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jqgfzy.top/Article/details/gtpinqrqzc.html

[G04] 定义方法
来源：http://dali.yuanzhike.top/Article/details/gtsjxpmgni.html

Py:   def greet(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gtkrolmfhg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gtvbnykkdv.html

JS:   greet() { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtkckwwkiq.html

TS:   greet(): string { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtkjnwdbfz.html

Java: String greet() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtqdflvbjp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gtokktxmgr.html

Ruby: def greet; @name; end
来源：http://dali.hnqzz.top/Article/details/gtzkszsxoh.html

C#:   public string Greet() => Name;
来源：http://dali.fzhhl.top/Article/details/gtaaawvuvs.html

[G05] 继承
来源：http://dali.havefunace.top/Article/details/gthovmvoah.html

Py:   class Admin(User): pass
来源：http://dali.sxryk.cn/Article/details/gtuynhpiel.html

PHP:  class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtzldlwqwj.html

JS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtxxnedyjb.html

TS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtpytacfkm.html

Java: class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtjarrkbws.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.bjfxy.top/Article/details/gtuwwnacqe.html

Ruby: class Admin < User; end
来源：http://dali.bjfxy.top/Article/details/gtxpohenbr.html

C#:   class Admin : User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtufgdbvju.html

[G06] 重写方法
来源：http://dali.cashguo.top/Article/details/gtycpgtgzo.html

Py:   def greet(self): return "admin"
来源：http://dali.vqdsnc.cn/Article/details/gtzwnalgvd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtoquwmecm.html

JS:   greet() { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gtopzrddzj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtclhbcwrk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtxfxyybux.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnqzz.top/Article/details/gtwrbpzcen.html

Ruby: def greet; "admin"; end
来源：http://dali.zdqjudy.top/Article/details/gtvfpuzovx.html

C#:   public override string Greet() => "admin";
来源：http://dali.jyoumei.cn/Article/details/gtidprbjgn.html

[G07] 调用父类方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtefnipgrx.html

Py:   super().greet()
来源：http://dali.nwbrower.top/Article/details/gtbpkrrmql.html

PHP:  parent::greet();
来源：http://dali.zhoulong.xyz/Article/details/gtauxnquku.html

JS:   super.greet();
来源：http://dali.guowangkeji.top/Article/details/gtyqrbxndd.html

TS:   super.greet();
来源：http://dali.xziqi.cn/Article/details/gtxguzpadd.html

Java: super.greet();
来源：http://dali.yueranfly.top/Article/details/gteqgdebru.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.pycfn.com/Article/details/gtelcqzyba.html

Ruby: super
来源：http://dali.hysaishi.cn/Article/details/gtqfdzoaqg.html

C#:   base.Greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkmpxsuxa.html

[G08] 静态方法与属性
来源：http://dali.yj20258888.top/Article/details/gtbrvvhxkm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pycfn.com/Article/details/gtvtybeozj.html

PHP:  public static function f() {}
来源：http://dali.nanxinkj.top/Article/details/gtgliarlri.html

JS:   static f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtfsxsuiys.html

TS:   static f(): void {}
来源：http://dali.zdqjudy.top/Article/details/gthzyryzua.html

Java: static void f() {}
来源：http://dali.gotoacloud.top/Article/details/gtnfcxfxbe.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yvedp.cn/Article/details/gtwpsbkmle.html

Ruby: def self.f; end
来源：http://dali.pycfn.com/Article/details/gtppngexqp.html

C#:   public static void F() {}
来源：http://dali.vqdsnc.cn/Article/details/gtsyjjfrza.html

[G09] 接口 / 抽象类
来源：http://dali.bjfxy.top/Article/details/gtdksyjfbe.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgfzy.top/Article/details/gtsvoyippb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhongyouzk.top/Article/details/gtfcljjxty.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sysykeji.top/Article/details/gtonfftroh.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmjmwikb.html

Java: interface Shape { double area(); }
来源：http://dali.jiagoushi.top/Article/details/gtjejbxnis.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenlongwang.top/Article/details/gtldsbszns.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fengsongda.top/Article/details/gtnlbuyslw.html

C#:   interface IShape { double Area(); }
来源：http://dali.yonumen.top/Article/details/gtygizrhvx.html

[G10] 访问控制
来源：http://dali.shangyingyoupin.top/Article/details/gtvvnumnly.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.haohaochexian.top/Article/details/gtnjrecwrx.html

PHP:  public / protected / private
来源：http://dali.guannengcc.top/Article/details/gtvfmkjiat.html

JS:   #private 字段；其余公开
来源：http://dali.tanke756.top/Article/details/gtbjbgvhcz.html

TS:   public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gtptqdvxmk.html

Java: public / protected / private / 默认包级
来源：http://dali.fengsongda.top/Article/details/gthnbaacso.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.andypj.xyz/Article/details/gthoiqrkng.html

Ruby: public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtajdymeib.html

C#:   public / protected / private / internal
来源：http://dali.shzxlz.cn/Article/details/gtzpolmhpp.html

[G11] getter / setter
来源：http://dali.jqgfzy.top/Article/details/gtomilgokz.html

Py:   @property 与 @x.setter
来源：http://dali.nanxuanxn.top/Article/details/gtzmxqybqs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtsdjdvzdj.html

JS:   get name() { return this._name; }
来源：http://dali.cashguo.top/Article/details/gtdtpjmmwx.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtvgknoukx.html

Java: public String getName() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtmtyokxau.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtdsndsdzy.html

Ruby: attr_accessor :name
来源：http://dali.ppjwa.cn/Article/details/gtehkxqxpe.html

C#:   public string Name { get; set; }
来源：http://dali.havefunace.top/Article/details/gtuoirzsnp.html

[G12] 对象转字符串
来源：http://dali.iojbl.cn/Article/details/gtgnoiajnr.html

Py:   def __str__(self): return self.name
来源：http://dali.xziqi.cn/Article/details/gtjqqyzzir.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtuluwdbxd.html

JS:   toString() { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtraavqabm.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtupaguhkg.html

Java: @Override public String toString() { return name; }
来源：http://dali.meibo888.top/Article/details/gtjzubijnw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gtpcilsxtv.html

Ruby: def to_s; @name; end
来源：http://dali.gotoacloud.top/Article/details/gtmwmteaeg.html

C#:   public override string ToString() => Name;
来源：http://dali.dashuyun.cn/Article/details/gtkryxwrcq.html

[G13] 判断对象类型
来源：http://dali.guowangkeji.top/Article/details/gtpktyrtcm.html

Py:   isinstance(u, User)
来源：http://dali.daxiang520.top/Article/details/gtjpbaowae.html

PHP:  $u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtalfbhhyr.html

JS:   u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtblxzqplv.html

TS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtmnmbqdvi.html

Java: u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtuyyqfwvw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.daria6918.cn/Article/details/gttycnnfbm.html

Ruby: u.is_a?(User)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmndjnnep.html

C#:   u is User
来源：http://dali.jyoumei.cn/Article/details/gtmjfydzuj.html

[G14] 数据类 / record
来源：http://dali.yj20258888.top/Article/details/gtwjsgazsb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shanyushiyangtech.top/Article/details/gtodlyvkta.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yueranfly.top/Article/details/gtpvaaebhk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.316326.xyz/Article/details/gtqyntdwuq.html

TS:   type User = { name: string; age: number };
来源：http://dali.guannengcc.top/Article/details/gtakngwksm.html

Java: record User(String name, int age) {}
来源：http://dali.zhongyouzk.top/Article/details/gtyjhiuevd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tianlin.xyz/Article/details/gtukrqjsbw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnqzz.top/Article/details/gtgxtmtxbn.html

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvwuesrpj.html

[G15] 枚举
来源：http://dali.xinyue.icu/Article/details/gtzzwweqwa.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.quarkkingdee.top/Article/details/gtesnbvsza.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.0kj1m.cn/Article/details/gtrpeejigu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.snrcjt.cn/Article/details/gtmxmpouzh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmujzcgoh.html

Java: enum Color { RED, GREEN }
来源：http://dali.zycfv.cn/Article/details/gttasxptkf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.birdmap.top/Article/details/gtemcjwoza.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoptdlymj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fengsongda.top/Article/details/gtsphlzjdu.html

[G16] 对象转数组 / 字典
来源：http://dali.pycfn.com/Article/details/gtyofjiapd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cucudq.cn/Article/details/gttcuinmcy.html

PHP:  get_object_vars($obj);
来源：http://dali.chenlongwang.top/Article/details/gtrgrxjtiu.html

JS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gtfzeebhes.html

TS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gtjphvrzwn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fengsongda.top/Article/details/gtplxhvbqz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gzhubu.top/Article/details/gtafqhxdyv.html

Ruby: obj.instance_variables
来源：http://dali.cucudq.cn/Article/details/gtoxlmjhfq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gtzlpadytk.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtxlbzodxr.html

H. 异常与错误处理
来源：http://dali.aibaodan.cn/Article/details/gtvekxxsua.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtpbbgcuod.html

[H01] try / catch 基础
来源：http://dali.cdnleiting.top/Article/details/gtvtphzvja.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nanxuanxn.top/Article/details/gtxmoczzep.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.kuanghao11.cn/Article/details/gtlijfzyqi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gtxtujgcxn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtfcvovsmi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hywenlv.cn/Article/details/gtbpnyenbs.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aibaodan.cn/Article/details/gtmsskltye.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zdqjudy.top/Article/details/gtillnjnck.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gaohongyu789.top/Article/details/gtpzdkssde.html

[H02] finally / ensure 收尾
来源：http://dali.jinghuilouyu.cn/Article/details/gtqdyhgeev.html


<!-- 参考信息 -->