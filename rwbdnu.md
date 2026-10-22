代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtzkhgegav.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cqqwz.cn/Article/details/gtjpfgyrvy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtvqqbxzhy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtqspllcrd.html

[E22] 字节长度与字符长度
来源：http://dali.zhiwuduotai.top/Article/details/gtaxbduwwz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsexbxdda.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtetgisivk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gogol.net.cn/Article/details/gtpjfcxgzw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gteosjtuew.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.daria6918.cn/Article/details/gtfsxorncg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.dashuyun.cn/Article/details/gtohvbmgkb.html

Ruby: s.bytesize;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqkjknqp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.iojbl.cn/Article/details/gtrpnbrkpa.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gthaodsjct.html

F. 文件与目录
来源：http://dali.redwolf501.top/Article/details/gtkvkucvtt.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtsddzbgcj.html

[F01] 读取整个文件
来源：http://dali.yuanzhike.top/Article/details/gtggvuvaxp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hongshengwenyu.top/Article/details/gtalrftixy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gttnkmabyd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shzxlz.cn/Article/details/gttzzrfqer.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gtvagvqscv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtbaiupxra.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hammf.cn/Article/details/gttefcckdo.html

Ruby: File.read("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwsgcxzmm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtwxymkbbr.html

[F02] 逐行读取文件
来源：http://dali.c1oappe.top/Article/details/gtbetshcpe.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenlongwang.top/Article/details/gtrznkexod.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gaohongyu789.top/Article/details/gtkmspzmne.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gtnlecpfbs.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.meibo888.top/Article/details/gtxqgwgtfc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shangyingyoupin.top/Article/details/gtaixuupma.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenlongwang.top/Article/details/gtvhmsqsmt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.aibaodan.cn/Article/details/gtgdizjkec.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sxryk.cn/Article/details/gtzytfxkqk.html

[F03] 写入文件（覆盖）
来源：http://dali.pengpengdd.cyou/Article/details/gtveibwexl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tanke756.top/Article/details/gtvchaboxq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jlsjyb.cn/Article/details/gtkrzrchex.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gtxulovuxp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangdashe.top/Article/details/gtwhkpricz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shangyingyoupin.top/Article/details/gtubuajbny.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hnxiangtu.top/Article/details/gtmaoihrfw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenlongwang.top/Article/details/gtzpedarwd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cucudq.cn/Article/details/gtxpcgjrzw.html

[F04] 追加写入文件
来源：http://dali.cdnleiting.top/Article/details/gtntzmvyol.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtfcznwpvj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxyqqvtk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmaqmwop.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ppjwa.cn/Article/details/gtodwmtzop.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xinyue.icu/Article/details/gtfcpfqton.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.snrcjt.cn/Article/details/gtfrkxxgxz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cqqwz.cn/Article/details/gtkjtiwsus.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yanxiufei.cn/Article/details/gtliyfygql.html

[F05] 判断文件或目录是否存在
来源：http://dali.hfpthk.cn/Article/details/gtlvjiyfmh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zdqjudy.top/Article/details/gtzprcajjq.html

PHP:  file_exists("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtzsqjgygc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtfyhnvkin.html

TS:   fs.existsSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtozrkdhma.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gttpahskpz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ivvv.top/Article/details/gtkhrbgwuj.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbgrhwdwo.html

C#:   File.Exists("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtesvippye.html

[F06] 删除文件
来源：http://dali.zhixingplan.top/Article/details/gtiqgssmjp.html

Py:   os.remove("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtsnofcsiw.html

PHP:  unlink("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtqknzflul.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtqkiroibm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtupczwgwl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhkyendp.html

Go:   os.Remove("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtajiynxdq.html

Ruby: File.delete("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtpbbnloan.html

C#:   File.Delete("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtajyoamvv.html

[F07] 创建目录（含多级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwnzlutwo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenzaomai.com/Article/details/gtlcqxtiby.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hfpthk.cn/Article/details/gtlzetnaeo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gtscwjwbya.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gttbdebndv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhiwuduotai.top/Article/details/gtmaunjbjb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xziqi.cn/Article/details/gtjijkrize.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cashguo.top/Article/details/gtshmszake.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sxryk.cn/Article/details/gtycpnoham.html

[F08] 遍历目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtackhwfir.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cucudq.cn/Article/details/gtqvkawaab.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.daria6918.cn/Article/details/gtosuknhrv.html

JS:   fs.readdirSync("dir")
来源：http://dali.hywenlv.cn/Article/details/gtzmbjpxgi.html

TS:   fs.readdirSync("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqajizris.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fzhhl.top/Article/details/gtgmkihjpk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtvzwrsoro.html

Ruby: Dir.children("dir")
来源：http://dali.jiagoushi.top/Article/details/gtswjynkhs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tianlin.xyz/Article/details/gtpnkktbgw.html

[F09] 获取文件大小
来源：http://dali.zhengqikj.top/Article/details/gtsxmqfzdw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnqzz.top/Article/details/gttgqbgbmk.html

PHP:  filesize("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtbvczzrun.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zdqjudy.top/Article/details/gtsmdssusn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gtsgqvnqrq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtiggensgd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnqzz.top/Article/details/gtgmwzhwbj.html

Ruby: File.size("a.txt")
来源：http://dali.hammf.cn/Article/details/gtqnbeusdr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tian-w.cn/Article/details/gtlysfcgql.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sxryk.cn/Article/details/gtxksqjbrf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gthjstqbjw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtdxxnqdzy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtmrssxlhp.html

TS:   path.extname("a.txt")
来源：http://dali.c1oappe.top/Article/details/gthfejxera.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.vqdsnc.cn/Article/details/gtvkgsdtmo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtwctqhsze.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtbdbfgvsh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtrhkpqpmi.html

[F11] 复制与移动文件
来源：http://dali.daria6918.cn/Article/details/gtqejfafqg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtdwwrhjhm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yuanzhike.top/Article/details/gtkkrpiyoa.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtmqemxwyy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtfxhbsmnu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gtktehyzeq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yanxiufei.cn/Article/details/gthwjvkump.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtsluxavvr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shangyingyoupin.top/Article/details/gtpwrbvhxa.html

[F12] CSV 读写
来源：http://dali.jiagoushi.top/Article/details/gtbrdhftkq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenlongwang.top/Article/details/gtnapkzjbz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cheryme.top/Article/details/gtgwahdhxu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sysykeji.top/Article/details/gtiubhfihw.html

TS:   // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gtzyusaeeh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tian-w.cn/Article/details/gthznsnbgb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cashguo.top/Article/details/gtuhbqnaxe.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tanke756.top/Article/details/gthbdbeddm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gthhsjeuql.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtqfnpmsri.html

G. 面向对象
来源：http://dali.wangshuangyany.cn/Article/details/gtrpqylnjm.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtmuozetes.html

[G01] 定义类
来源：http://dali.hfpthk.cn/Article/details/gtxujkpszc.html

Py:   class User: pass
来源：http://dali.zhiwuduotai.top/Article/details/gtoxnmnmyu.html

PHP:  class User {}
来源：http://dali.xinyue.icu/Article/details/gtasfvohlq.html

JS:   class User {}
来源：http://dali.ydzc1.top/Article/details/gtwkznsrxj.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtugundwuw.html

Java: class User {}
来源：http://dali.0kj1m.cn/Article/details/gtvosjbeca.html

Go:   type User struct { Name string }
来源：http://dali.ppjwa.cn/Article/details/gtykndvdaj.html

Ruby: class User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgfuwwxtu.html

C#:   class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtamgspfjf.html

[G02] 构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gtpafctybi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinqigfzy.top/Article/details/gtjvzrtadl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258.top/Article/details/gtzgtnlnne.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yuanzhike.top/Article/details/gtfumzazfw.html

TS:   constructor(public name: string) {}
来源：http://dali.nanxuanxn.top/Article/details/gtesprmcjr.html

Java: User(String name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gtzmeigohv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhixingplan.top/Article/details/gtoluhkqmp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hnxiangtu.top/Article/details/gtwgsuywgz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zycfv.cn/Article/details/gtsryjgbos.html

[G03] 实例属性
来源：http://dali.xuanzx.com/Article/details/gtiyadopyb.html

Py:   self.name = "x"
来源：http://dali.ydzc1.top/Article/details/gtqbarpiaw.html

PHP:  public string $name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtfelebdnp.html

JS:   this.name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtqhpempwo.html

TS:   name: string = "x";
来源：http://dali.yj202588.top/Article/details/gtlmvlreoh.html

Java: private String name;
来源：http://dali.c1oappe.top/Article/details/gttrrvhxih.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.smart0.xyz/Article/details/gtldzweyyk.html

Ruby: @name = "x"
来源：http://dali.ydzc1.top/Article/details/gtmpreefwc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhengqikj.top/Article/details/gtelziymof.html

[G04] 定义方法
来源：http://dali.tianlin.xyz/Article/details/gtjgmuzdal.html

Py:   def greet(self): return self.name
来源：http://dali.xziqi.cn/Article/details/gtpitpqatc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzweyvkwt.html

JS:   greet() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gtgzofeymj.html

TS:   greet(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtixsijgud.html

Java: String greet() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvzqilyjn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtggvgyngk.html

Ruby: def greet; @name; end
来源：http://dali.jianghu66.top/Article/details/gtyoxfzbhn.html

C#:   public string Greet() => Name;
来源：http://dali.zdqjudy.top/Article/details/gtatrkwxgv.html

[G05] 继承
来源：http://dali.jlsjyb.cn/Article/details/gtixeavdhv.html

Py:   class Admin(User): pass
来源：http://dali.cqqwz.cn/Article/details/gtrspmpuud.html

PHP:  class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtkxgkkitg.html

JS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtrjbilfdz.html

TS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtbyaxjmfv.html

Java: class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtjhpgvmdm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ybcxt.top/Article/details/gtytznxshr.html

Ruby: class Admin < User; end
来源：http://dali.gotoacloud.top/Article/details/gtxekpsbvt.html

C#:   class Admin : User {}
来源：http://dali.zhoulong.xyz/Article/details/gttgporylv.html

[G06] 重写方法
来源：http://dali.sweek.top/Article/details/gtcgreawlo.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigufen.top/Article/details/gtfeqwwohq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtraiwghdn.html

JS:   greet() { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtpnahdcnb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtyhvheeoi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtriyjpkwt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gogol.net.cn/Article/details/gtoxrcujlv.html

Ruby: def greet; "admin"; end
来源：http://dali.yonumen.top/Article/details/gtywildyxs.html

C#:   public override string Greet() => "admin";
来源：http://dali.andypj.xyz/Article/details/gtylondojp.html

[G07] 调用父类方法
来源：http://dali.sxryk.cn/Article/details/gthxqzyxqm.html

Py:   super().greet()
来源：http://dali.0kj1m.cn/Article/details/gtmlearkxc.html

PHP:  parent::greet();
来源：http://dali.hammf.cn/Article/details/gtrlfzfwul.html

JS:   super.greet();
来源：http://dali.hfpthk.cn/Article/details/gtwgrpduku.html

TS:   super.greet();
来源：http://dali.yangfankeji.com/Article/details/gtcqarovha.html

Java: super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gtqokninqy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.quarkkingdee.top/Article/details/gtumuouxso.html

Ruby: super
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxebpmadt.html

C#:   base.Greet();
来源：http://dali.hysaishi.cn/Article/details/gtnyfxsmbn.html

[G08] 静态方法与属性
来源：http://dali.dianchejie.cn/Article/details/gtnsripkol.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tanke756.top/Article/details/gtrltfuwdf.html

PHP:  public static function f() {}
来源：http://dali.tianlin.xyz/Article/details/gtshlxohud.html

JS:   static f() {}
来源：http://dali.jqgfzy.top/Article/details/gtduepcidk.html

TS:   static f(): void {}
来源：http://dali.hywenlv.cn/Article/details/gtwpqsmbfp.html

Java: static void f() {}
来源：http://dali.tian-w.cn/Article/details/gtqgmyletj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gzhubu.top/Article/details/gtoebxuahx.html

Ruby: def self.f; end
来源：http://dali.daxiang520.top/Article/details/gtabczvgme.html

C#:   public static void F() {}
来源：http://dali.pycfn.com/Article/details/gtybnrpfwq.html

[G09] 接口 / 抽象类
来源：http://dali.zdqjudy.top/Article/details/gtajmqaemc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sweek.top/Article/details/gtdhzvelsf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.havefunace.top/Article/details/gtwlctmsnl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tian-w.cn/Article/details/gtjkjptxfg.html

TS:   interface Shape { area(): number; }
来源：http://dali.yanxiufei.cn/Article/details/gtzfisrqbd.html

Java: interface Shape { double area(); }
来源：http://dali.yongpay.top/Article/details/gtbivfiyyk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sxryk.cn/Article/details/gtqulzobqq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shangyingyoupin.top/Article/details/gtxzzskabi.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgufenzy.top/Article/details/gtglvcwrgn.html

[G10] 访问控制
来源：http://dali.ppjwa.cn/Article/details/gtgmnbpkar.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xuanzx.com/Article/details/gtyinmlbhi.html

PHP:  public / protected / private
来源：http://dali.xinyue.icu/Article/details/gtlrkmgotw.html

JS:   #private 字段；其余公开
来源：http://dali.aizwys.cn/Article/details/gtqyxbnnna.html

TS:   public / protected / private
来源：http://dali.daxiang520.top/Article/details/gtvbhdpgjp.html

Java: public / protected / private / 默认包级
来源：http://dali.jqgufenzy.top/Article/details/gttictuxgk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuetiantiany.cn/Article/details/gtycfottmg.html

Ruby: public / protected / private
来源：http://dali.sweek.top/Article/details/gtwuvwjped.html

C#:   public / protected / private / internal
来源：http://dali.xziqi.cn/Article/details/gtmmqpbfpj.html

[G11] getter / setter
来源：http://dali.snrcjt.cn/Article/details/gtjuumzaji.html

Py:   @property 与 @x.setter
来源：http://dali.smart0.xyz/Article/details/gtlycveohx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtycpdidvi.html

JS:   get name() { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gtusgvsemr.html

TS:   get name(): string { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gtmbmbpdrf.html

Java: public String getName() { return name; }
来源：http://dali.yvedp.cn/Article/details/gtciuazyfg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gtcjikjgcy.html

Ruby: attr_accessor :name
来源：http://dali.ydzc1.top/Article/details/gtbqebttiy.html

C#:   public string Name { get; set; }
来源：http://dali.chenzaomai.com/Article/details/gtngyzrrig.html

[G12] 对象转字符串
来源：http://dali.xuanzx.com/Article/details/gtasytangt.html

Py:   def __str__(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gtalvzvbil.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtjcgdgwez.html

JS:   toString() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gtewgasucw.html

TS:   toString(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtffdpcjsz.html

Java: @Override public String toString() { return name; }
来源：http://dali.redwolf501.top/Article/details/gtchbjqabu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtcksmtngj.html

Ruby: def to_s; @name; end
来源：http://dali.xuanzx.com/Article/details/gtmaweinjg.html

C#:   public override string ToString() => Name;
来源：http://dali.quarkkingdee.top/Article/details/gtbppruisd.html

[G13] 判断对象类型
来源：http://dali.iojbl.cn/Article/details/gtreklcymk.html

Py:   isinstance(u, User)
来源：http://dali.daxiang520.top/Article/details/gtjmaicjtd.html

PHP:  $u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtswentkxy.html

JS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtafciubqt.html

TS:   u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtqtlwmklh.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gtubokfiks.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yueranfly.top/Article/details/gtawyoyoiu.html

Ruby: u.is_a?(User)
来源：http://dali.jlsjyb.cn/Article/details/gtywutlhkj.html

C#:   u is User
来源：http://dali.jianghu66.top/Article/details/gtajwaosyk.html

[G14] 数据类 / record
来源：http://dali.zhengqikj.top/Article/details/gtinglknde.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gogol.net.cn/Article/details/gtkjeqogih.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.316326.xyz/Article/details/gtzkfzpfjz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cashguo.top/Article/details/gtrxdczkwo.html

TS:   type User = { name: string; age: number };
来源：http://dali.hongshengwenyu.top/Article/details/gtrahmrhfb.html

Java: record User(String name, int age) {}
来源：http://dali.yuanzhike.top/Article/details/gttbjmllzp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yueranfly.top/Article/details/gthzjmnozr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.9152youxi.cn/Article/details/gtuxksyuzr.html

C#:   record User(string Name, int Age);
来源：http://dali.snrcjt.cn/Article/details/gteghdirev.html

[G15] 枚举
来源：http://dali.hnxiangtu.top/Article/details/gtnkiluoew.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhiwuduotai.top/Article/details/gtkhmrubzj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guannengcc.top/Article/details/gtfkgfkveh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgfzy.top/Article/details/gtlqgkzkkb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jyoumei.cn/Article/details/gttxaxruuz.html

Java: enum Color { RED, GREEN }
来源：http://dali.meibo888.top/Article/details/gteoeuniyi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhixingplan.top/Article/details/gtsnamdyad.html

Ruby: Color = %i[red green].freeze
来源：http://dali.9152youxi.cn/Article/details/gtsmhwcvco.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxakgjhv.html

[G16] 对象转数组 / 字典
来源：http://dali.xuetiantiany.cn/Article/details/gtuikltlly.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ybcxt.top/Article/details/gtrbadapzf.html

PHP:  get_object_vars($obj);
来源：http://dali.xuetiantiany.cn/Article/details/gtcgngwqch.html

JS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gtgazlhsap.html

TS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gtrstofopk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.svipenyu.cn/Article/details/gtcckwqqpi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hnxiangtu.top/Article/details/gtpaujmsiq.html

Ruby: obj.instance_variables
来源：http://dali.haohaochexian.top/Article/details/gtjsyrudwd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.quarkkingdee.top/Article/details/gtvefpracy.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtrfjaikvj.html

H. 异常与错误处理
来源：http://dali.wangshuangyany.cn/Article/details/gtceyasnyg.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtftfujpol.html

[H01] try / catch 基础
来源：http://dali.quarkkingdee.top/Article/details/gtesduxfzr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jianghu66.top/Article/details/gtrvbhpqqe.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gtaxjdmlbe.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gtvxuvktuf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gtodnguiwd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenlongwang.top/Article/details/gtatagsudz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.bjfxy.top/Article/details/gtchnlyzzk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hammf.cn/Article/details/gtktgniuaz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xinyue.icu/Article/details/gteedabjmb.html

[H02] finally / ensure 收尾
来源：http://dali.yanxiufei.cn/Article/details/gteyjzpcwv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.9152youxi.cn/Article/details/gtkxousfka.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtlmgzidww.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtbdigdmbh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtdwveymui.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtiawgygoz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daxiang520.top/Article/details/gtvxbbskkg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gtblrawltl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtrffmkcoa.html

[H03] 主动抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gtzqryhcgb.html

Py:   raise ValueError("错误信息")
来源：http://dali.0kj1m.cn/Article/details/gthcfjzaxn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtrebsmamq.html

JS:   throw new Error("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtwgdtctfr.html

TS:   throw new Error("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtiytekrxe.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtgntswjeh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdpnuulj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jianghu66.top/Article/details/gtepfauuer.html


<!-- 参考信息 -->