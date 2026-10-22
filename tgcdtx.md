代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sweek.top/Article/details/gt2gfwooyka.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gt2bvwvqzje.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gt2mjervgey.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gt2dkdkrymc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gt2prjeurki.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hysaishi.cn/Article/details/gt2lbeztssh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gt2duvljnqb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gt2miwtigwc.html

[E22] 字节长度与字符长度
来源：http://dali.yangfankeji.com/Article/details/gt2kigscjrg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2uyogpobx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gt2zltbntdm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daxiang520.top/Article/details/gt2jqredkwp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ppjwa.cn/Article/details/gt2lhkfewkv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yangfankeji.com/Article/details/gt2duuxsjhf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hywenlv.cn/Article/details/gt2ehqrzqqm.html

Ruby: s.bytesize;  s.length
来源：http://dali.daria6918.cn/Article/details/gt2tacwuqdg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zycfv.cn/Article/details/gt2ismshxwo.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2hmwnknpo.html

F. 文件与目录
来源：http://dali.birdmap.top/Article/details/gt2dolhfvby.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2oqunxtaf.html

[F01] 读取整个文件
来源：http://dali.hnqzz.top/Article/details/gt2jdnungjx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sufxvd.cn/Article/details/gt2laqinfst.html

PHP:  file_get_contents("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2fvtkfemp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dashuyun.cn/Article/details/gt2pecsqedt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ybcxt.top/Article/details/gt2alfdcyqi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gt2ukbbfaty.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yuanzhike.top/Article/details/gt2olrvkfuf.html

Ruby: File.read("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2yzkbqdii.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2wdjhrrvk.html

[F02] 逐行读取文件
来源：http://dali.tian-w.cn/Article/details/gt2fmzyusvo.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cougscmz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2quhsimvi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ivvv.top/Article/details/gt2ejvlgfcd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2hzjaincj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kuswxxlm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenlongwang.top/Article/details/gt2rxgipgmb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jqgfzy.top/Article/details/gt2mgcszrxu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuxming.cn/Article/details/gt2dgencpdd.html

[F03] 写入文件（覆盖）
来源：http://dali.ybcxt.top/Article/details/gt2wzcdplaz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.birdmap.top/Article/details/gt2znmipxap.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gt2ywwblpsv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gt2luyvssit.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gt2vqwgqugi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.iojbl.cn/Article/details/gt2bltpghsu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2stmepvav.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.snrcjt.cn/Article/details/gt2nquowtwj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.haohaochexian.top/Article/details/gt2kcdveevg.html

[F04] 追加写入文件
来源：http://dali.tian-w.cn/Article/details/gt2gqcybhlj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zdqjudy.top/Article/details/gt2merbgwze.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.aizwys.cn/Article/details/gt2yybgpwzw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ppjwa.cn/Article/details/gt2pjiucyqa.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gt2mxkyokng.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.iojbl.cn/Article/details/gt2kqvmlpmm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ygkiihyd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenzaomai.com/Article/details/gt2hsrdafje.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nanxinkj.top/Article/details/gt2wwjmzwcq.html

[F05] 判断文件或目录是否存在
来源：http://dali.316326.xyz/Article/details/gt2cgxntqar.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yongpay.top/Article/details/gt2skskvqsv.html

PHP:  file_exists("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2xakzfjne.html

JS:   fs.existsSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2nsovvlox.html

TS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2gbnwsjbk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oudhluqk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj20258888.top/Article/details/gt2ceqcewli.html

Ruby: File.exist?("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2xoquchqp.html

C#:   File.Exists("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2xocvbxyr.html

[F06] 删除文件
来源：http://dali.yueranfly.top/Article/details/gt2youecqns.html

Py:   os.remove("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2nqcyvyjl.html

PHP:  unlink("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2fdhrxsak.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2quwihpgv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2ieuxkjkz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gt2etedvfew.html

Go:   os.Remove("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2toeevlyq.html

Ruby: File.delete("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2dhadudco.html

C#:   File.Delete("a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2byfptasz.html

[F07] 创建目录（含多级）
来源：http://dali.ehwqpu.com/Article/details/gt2oejhiaun.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhengqikj.top/Article/details/gt2czasdhxq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ivvv.top/Article/details/gt2fukktjox.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gt2qllgqqjz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gt2jmropdjc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.0kj1m.cn/Article/details/gt2pmzghhun.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pycfn.com/Article/details/gt2adwbkjwk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rxpncomw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ghwqcraa.html

[F08] 遍历目录
来源：http://dali.nanxuanxn.top/Article/details/gt2clkaulmg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nkiielss.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.haohaochexian.top/Article/details/gt2zsdulujd.html

JS:   fs.readdirSync("dir")
来源：http://dali.c1oappe.top/Article/details/gt2cqesaysm.html

TS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gt2uvtoxbls.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sweek.top/Article/details/gt2zwixrdan.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rvytrzcj.html

Ruby: Dir.children("dir")
来源：http://dali.yueranfly.top/Article/details/gt2wrruzvkw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ivvv.top/Article/details/gt2xqqjnzef.html

[F09] 获取文件大小
来源：http://dali.cucudq.cn/Article/details/gt2mcfeosxn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2pojihucz.html

PHP:  filesize("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2bffruwix.html

JS:   fs.statSync("a.txt").size
来源：http://dali.aibaodan.cn/Article/details/gt2zqghrlze.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigufen.top/Article/details/gt2nwxdbhst.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gt2uqjdpxov.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.pengpengdd.cyou/Article/details/gt2jpiqouyh.html

Ruby: File.size("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2xsqnixoo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ehwqpu.com/Article/details/gt2hktgkkrf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.iojbl.cn/Article/details/gt2qdzvehlc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2gbfxiugs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2awuxyeqb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2uorfoaey.html

TS:   path.extname("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2rcskawwc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cqqwz.cn/Article/details/gt2aogtvuef.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2nqyticga.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2cyinzlbt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2mtdredly.html

[F11] 复制与移动文件
来源：http://dali.hnqzz.top/Article/details/gt2lqrszcxl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2afwoeniv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2xrumirpu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gt2lpllziws.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gt2qfwreorn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gt2aftewmjl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yongpay.top/Article/details/gt2wiqzibzz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gt2vsusxmis.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xylfe.cn/Article/details/gt2vaugkvei.html

[F12] CSV 读写
来源：http://dali.yuxming.cn/Article/details/gt2xyzaofjm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2codoiquj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhongyouzk.top/Article/details/gt2bnclowgg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenzaomai.com/Article/details/gt2ygxfdqtt.html

TS:   // 同上
来源：http://dali.kuanghao11.cn/Article/details/gt2ijlosmdl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cheryme.top/Article/details/gt2nonyoroc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yangfankeji.com/Article/details/gt2fvfcectc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dashuyun.cn/Article/details/gt2fjnxwdhy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.redwolf501.top/Article/details/gt2bllgktnq.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2zwxmhmzg.html

G. 面向对象
来源：http://dali.yuanzhike.top/Article/details/gt2nglltnch.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2dykpqeei.html

[G01] 定义类
来源：http://dali.zhiwuduotai.top/Article/details/gt2cwcdqlfd.html

Py:   class User: pass
来源：http://dali.ehwqpu.com/Article/details/gt2flasxnqh.html

PHP:  class User {}
来源：http://dali.tanke756.top/Article/details/gt2abkkwskv.html

JS:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gt2wvtgxvzv.html

TS:   class User { name: string = ""; }
来源：http://dali.andypj.xyz/Article/details/gt2qcnrnlvg.html

Java: class User {}
来源：http://dali.ybcxt.top/Article/details/gt2zyxyjccs.html

Go:   type User struct { Name string }
来源：http://dali.yongpay.top/Article/details/gt2mrglkpxl.html

Ruby: class User; end
来源：http://dali.jyoumei.cn/Article/details/gt2qysemanu.html

C#:   class User {}
来源：http://dali.yj20258888.top/Article/details/gt2elzbmpiq.html

[G02] 构造函数
来源：http://dali.sysykeji.top/Article/details/gt2jspquiaj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj202588.top/Article/details/gt2rzzodrvq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hfpthk.cn/Article/details/gt2ommoqkbe.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xxhoijyh.html

TS:   constructor(public name: string) {}
来源：http://dali.gotoacloud.top/Article/details/gt2szdshkqc.html

Java: User(String name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gt2yxppgsri.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hfpthk.cn/Article/details/gt2ibknwgke.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dashuyun.cn/Article/details/gt2qbzrcmqd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sweek.top/Article/details/gt2zhtqpafa.html

[G03] 实例属性
来源：http://dali.0kj1m.cn/Article/details/gt2mfftfbuy.html

Py:   self.name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gt2gfhhjvgt.html

PHP:  public string $name = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zjigxbif.html

JS:   this.name = "x";
来源：http://dali.cdnleiting.top/Article/details/gt2zdtxmwli.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eproyemn.html

Java: private String name;
来源：http://dali.ehwqpu.com/Article/details/gt2vodbzdlc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pycfn.com/Article/details/gt2odmwacmc.html

Ruby: @name = "x"
来源：http://dali.mhx1999.top/Article/details/gt2ugqfzlpm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.andypj.xyz/Article/details/gt2sezxgsob.html

[G04] 定义方法
来源：http://dali.aizwys.cn/Article/details/gt2pkdywgvt.html

Py:   def greet(self): return self.name
来源：http://dali.yangfankeji.com/Article/details/gt2moviiomy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gt2wlidnyxm.html

JS:   greet() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gt2naybybvu.html

TS:   greet(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gt2yoekmjkh.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2njqolvfw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gt2eujpdfic.html

Ruby: def greet; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2izrolggb.html

C#:   public string Greet() => Name;
来源：http://dali.cucudq.cn/Article/details/gt2roiljeik.html

[G05] 继承
来源：http://dali.yuanzhike.top/Article/details/gt2ynlltkkq.html

Py:   class Admin(User): pass
来源：http://dali.cucudq.cn/Article/details/gt2dczotjzj.html

PHP:  class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2cnlkvcfa.html

JS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gt2xptrugcf.html

TS:   class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gt2fyabmxwt.html

Java: class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gt2dyktfudd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhiwuduotai.top/Article/details/gt2pfppacdl.html

Ruby: class Admin < User; end
来源：http://dali.havefunace.top/Article/details/gt2lctxdzjv.html

C#:   class Admin : User {}
来源：http://dali.cheryme.top/Article/details/gt2eqypeyrp.html

[G06] 重写方法
来源：http://dali.yangfankeji.com/Article/details/gt2kybankwa.html

Py:   def greet(self): return "admin"
来源：http://dali.yanxiufei.cn/Article/details/gt2kxhydzby.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gt2jdgstufs.html

JS:   greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2lsfquvdr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2cbcropkg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gt2fuodyise.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnxiangtu.top/Article/details/gt2oyidyxdk.html

Ruby: def greet; "admin"; end
来源：http://dali.zhengqikj.top/Article/details/gt2jjmzlcha.html

C#:   public override string Greet() => "admin";
来源：http://dali.smart0.xyz/Article/details/gt2gxohtggf.html

[G07] 调用父类方法
来源：http://dali.shangyingyoupin.top/Article/details/gt2oyifinzm.html

Py:   super().greet()
来源：http://dali.gaohongyu789.top/Article/details/gt2ptlcermt.html

PHP:  parent::greet();
来源：http://dali.haohaochexian.top/Article/details/gt2hxfmjtzb.html

JS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gt2djwhwtcz.html

TS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gt2txgkpezt.html

Java: super.greet();
来源：http://dali.jyoumei.cn/Article/details/gt2tpotljgw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenlongwang.top/Article/details/gt2xjyeulez.html

Ruby: super
来源：http://dali.nwbrower.top/Article/details/gt2enoonell.html

C#:   base.Greet();
来源：http://dali.smart0.xyz/Article/details/gt2iuolzufm.html

[G08] 静态方法与属性
来源：http://dali.ydzc1.top/Article/details/gt2hlnxdrdj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.haohaochexian.top/Article/details/gt2kxrispes.html

PHP:  public static function f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tnhdtmwn.html

JS:   static f() {}
来源：http://dali.aizwys.cn/Article/details/gt2fuavtbav.html

TS:   static f(): void {}
来源：http://dali.yanxiufei.cn/Article/details/gt2vpdtyfcb.html

Java: static void f() {}
来源：http://dali.cheryme.top/Article/details/gt2fxqgpsjz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jiagoushi.top/Article/details/gt2wzajlvmu.html

Ruby: def self.f; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sdpucrdz.html

C#:   public static void F() {}
来源：http://dali.zhoulong.xyz/Article/details/gt2rsfvnpqd.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigufen.top/Article/details/gt2juikwicm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj202588.top/Article/details/gt2pfxohcza.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hapnyhyk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hywenlv.cn/Article/details/gt2mrqpovhd.html

TS:   interface Shape { area(): number; }
来源：http://dali.xylfe.cn/Article/details/gt2jfhetgcs.html

Java: interface Shape { double area(); }
来源：http://dali.dashuyun.cn/Article/details/gt2dwpariqt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2jikfujlw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xinyue.icu/Article/details/gt2puezljaf.html

C#:   interface IShape { double Area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ccegfdei.html

[G10] 访问控制
来源：http://dali.nanxinkj.top/Article/details/gt2jlaatijj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dashuyun.cn/Article/details/gt2mzcetyke.html

PHP:  public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gt2ubetmweq.html

JS:   #private 字段；其余公开
来源：http://dali.nwbrower.top/Article/details/gt2pxnmaoqu.html

TS:   public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gt2mxkvutci.html

Java: public / protected / private / 默认包级
来源：http://dali.zhongyouzk.top/Article/details/gt2rozqaagd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ilreiwir.html

Ruby: public / protected / private
来源：http://dali.hnqzz.top/Article/details/gt2xlcnexha.html

C#:   public / protected / private / internal
来源：http://dali.daxiang520.top/Article/details/gt2edinjlpp.html

[G11] getter / setter
来源：http://dali.xuetiantiany.cn/Article/details/gt2rwichbns.html

Py:   @property 与 @x.setter
来源：http://dali.cdnleiting.top/Article/details/gt2xwgccdza.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gt2xqfxmrvy.html

JS:   get name() { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gt2lgkpwxzf.html

TS:   get name(): string { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gt2rbkxasuy.html

Java: public String getName() { return name; }
来源：http://dali.tian-w.cn/Article/details/gt2clcirtkv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gt2qkvkkfiu.html

Ruby: attr_accessor :name
来源：http://dali.birdmap.top/Article/details/gt2dukjfdqz.html

C#:   public string Name { get; set; }
来源：http://dali.cqqwz.cn/Article/details/gt2snavhiqp.html

[G12] 对象转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2daxywykx.html

Py:   def __str__(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gt2ujhbqcwj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gt2dvybcmvq.html

JS:   toString() { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2glxlsojo.html

TS:   toString(): string { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gt2rasgyuen.html

Java: @Override public String toString() { return name; }
来源：http://dali.daxiang520.top/Article/details/gt2tzizbxls.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gt2mjdsgswk.html

Ruby: def to_s; @name; end
来源：http://dali.guowangkeji.top/Article/details/gt2lowibokv.html

C#:   public override string ToString() => Name;
来源：http://dali.jqgufenzy.top/Article/details/gt2cmomcmir.html

[G13] 判断对象类型
来源：http://dali.cucudq.cn/Article/details/gt2lharkorx.html

Py:   isinstance(u, User)
来源：http://dali.cqqwz.cn/Article/details/gt2tvpjjcwg.html

PHP:  $u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gt2zfcumfps.html

JS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gt2fjayjenf.html

TS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gt2vxrrxmls.html

Java: u instanceof User
来源：http://dali.nwbrower.top/Article/details/gt2fapcyanl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hammf.cn/Article/details/gt2weozrrjw.html

Ruby: u.is_a?(User)
来源：http://dali.yangfankeji.com/Article/details/gt2aexhvkap.html

C#:   u is User
来源：http://dali.nanxinkj.top/Article/details/gt2tfcvcxzh.html

[G14] 数据类 / record
来源：http://dali.ydzc1.top/Article/details/gt2fgxvroek.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.vqdsnc.cn/Article/details/gt2fmqexudd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.bjfxy.top/Article/details/gt2cglrtxsj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ydzc1.top/Article/details/gt2tewbfohq.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojtehvls.html

Java: record User(String name, int age) {}
来源：http://dali.ydzc1.top/Article/details/gt2zbfciecg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sweek.top/Article/details/gt2wwmrjcfy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hysaishi.cn/Article/details/gt2mitzadnj.html

C#:   record User(string Name, int Age);
来源：http://dali.guowangkeji.top/Article/details/gt2jzbbscuw.html

[G15] 枚举
来源：http://dali.jlsjyb.cn/Article/details/gt2tfxxoksq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nwbrower.top/Article/details/gt2qujjidwe.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yueranfly.top/Article/details/gt2caezmweh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nwbrower.top/Article/details/gt2uwtocbnl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2rxteakem.html

Java: enum Color { RED, GREEN }
来源：http://dali.tanke756.top/Article/details/gt2iveisfcm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.kuanghao11.cn/Article/details/gt2wanxnirp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ivvv.top/Article/details/gt2jobtjyik.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gaohongyu789.top/Article/details/gt2nfngsbqn.html

[G16] 对象转数组 / 字典
来源：http://dali.yj202588.top/Article/details/gt2namuljpk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ydzc1.top/Article/details/gt2rryigctf.html

PHP:  get_object_vars($obj);
来源：http://dali.fzhhl.top/Article/details/gt2vzydjktd.html

JS:   Object.entries(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2ktrtvtmb.html

TS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gt2iznceqzs.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.svipenyu.cn/Article/details/gt2coitiaap.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hammf.cn/Article/details/gt2vjkzctly.html

Ruby: obj.instance_variables
来源：http://dali.zhixingplan.top/Article/details/gt2nhilwprh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhoulong.xyz/Article/details/gt2uunrdfav.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2osrzbtay.html

H. 异常与错误处理
来源：http://dali.hammf.cn/Article/details/gt2ndeniwwa.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2uaewndyz.html

[H01] try / catch 基础
来源：http://dali.fzhhl.top/Article/details/gt2zdxlavfm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hammf.cn/Article/details/gt2quyqnlqy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2fovdvwpb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gt2trhdjxov.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gt2qhyrbwrv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shzxlz.cn/Article/details/gt2nytjobcz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shzxlz.cn/Article/details/gt2ycumveal.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sysykeji.top/Article/details/gt2zstelwvx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jlsjyb.cn/Article/details/gt2saiitfuv.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258888.top/Article/details/gt2mjayibah.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigufen.top/Article/details/gt2jhjvvbpd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gt2bwekqybs.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2uhqkirvy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gt2ibyhoqrs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gt2xmbzkgyi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.pengpengdd.cyou/Article/details/gt2spwytwkx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhengqikj.top/Article/details/gt2veggiera.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2rpoueiyu.html

[H03] 主动抛出异常
来源：http://dali.fengsongda.top/Article/details/gt2nlsuzrzh.html

Py:   raise ValueError("错误信息")
来源：http://dali.jianghu66.top/Article/details/gt2jqrlmgda.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gt2pacnenoy.html

JS:   throw new Error("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2kqrkxxbl.html


<!-- 参考信息 -->