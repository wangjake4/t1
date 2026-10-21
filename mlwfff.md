代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tianlin.xyz/Article/details/gtneydmnio.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtrwvgxlur.html

F. 文件与目录
来源：http://dali.jqgufenzy.top/Article/details/gtuiwmlyhm.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtlpfznuwu.html

[F01] 读取整个文件
来源：http://dali.cdnleiting.top/Article/details/gtoxanyqgi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.birdmap.top/Article/details/gtpeoszwll.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cheryme.top/Article/details/gtwrdpmprc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljlhmyri.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yonumen.top/Article/details/gtnwevtftt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtczqtfzap.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sufxvd.cn/Article/details/gtgreswlqe.html

Ruby: File.read("a.txt")
来源：http://dali.yongpay.top/Article/details/gtsvhuqomt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtqfrvdxkt.html

[F02] 逐行读取文件
来源：http://dali.cdnleiting.top/Article/details/gtdxebgbcm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.0kj1m.cn/Article/details/gtywnvbvkc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xziqi.cn/Article/details/gtagihvkym.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gtwjcekgot.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtcmxzzwgq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ydzc1.top/Article/details/gtfiiwxvvo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jianghu66.top/Article/details/gtcvnptoxi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.birdmap.top/Article/details/gtzindpdbt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cdnleiting.top/Article/details/gtxnmmwvem.html

[F03] 写入文件（覆盖）
来源：http://dali.xziqi.cn/Article/details/gthubomvfq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xziqi.cn/Article/details/gtqhlrymcj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jqgfzy.top/Article/details/gtzfyporwo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtkspdseem.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.havefunace.top/Article/details/gtwtjbqffr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.kuanghao11.cn/Article/details/gtyzzyhqdw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ybcxt.top/Article/details/gtncosiuol.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hywenlv.cn/Article/details/gtjzepmila.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gtpngruzbg.html

[F04] 追加写入文件
来源：http://dali.yanxiufei.cn/Article/details/gtarjgdjtw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aizwys.cn/Article/details/gtqdsombya.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nanxuanxn.top/Article/details/gtvkvcqsbb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgfzy.top/Article/details/gtqfvlsvca.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xinyue.icu/Article/details/gthwbmbkdo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.andypj.xyz/Article/details/gtcnmfmkuv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jiagoushi.top/Article/details/gtptanulql.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xinyue.icu/Article/details/gtvttwbafk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenzaomai.com/Article/details/gtisawylno.html

[F05] 判断文件或目录是否存在
来源：http://dali.xuanzx.com/Article/details/gthykqpecb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guannengcc.top/Article/details/gtrksmnnwx.html

PHP:  file_exists("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtyqudhsrh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtvuhwgpze.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtfwxlkcll.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtexfhydlk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.redwolf501.top/Article/details/gttttlnqew.html

Ruby: File.exist?("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtgbhhamqg.html

C#:   File.Exists("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtgfwobzmf.html

[F06] 删除文件
来源：http://dali.ppjwa.cn/Article/details/gteaxvmouq.html

Py:   os.remove("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtdbftmbvq.html

PHP:  unlink("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtfgxaqafb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtzlmynaim.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtuphcvams.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkkqpkepq.html

Go:   os.Remove("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtsqxoleyc.html

Ruby: File.delete("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtnhlvkvnw.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtqjsgkopa.html

[F07] 创建目录（含多级）
来源：http://dali.xuanzx.com/Article/details/gtmgsviiin.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jiagoushi.top/Article/details/gtgrkkhxyn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guannengcc.top/Article/details/gtlrkjedfy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gtvmfeudfc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tanke756.top/Article/details/gtyhgrlhhs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yuxming.cn/Article/details/gtjmgnsrpt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yonumen.top/Article/details/gtxduarbga.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tianlin.xyz/Article/details/gtjunpodaw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuetiantiany.cn/Article/details/gtmquwtvhg.html

[F08] 遍历目录
来源：http://dali.sweek.top/Article/details/gtzwcprwqp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmbpejzoy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.fengsongda.top/Article/details/gtbfgbvxjn.html

JS:   fs.readdirSync("dir")
来源：http://dali.dashuyun.cn/Article/details/gtkkorbcez.html

TS:   fs.readdirSync("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtfgndxevl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jlsjyb.cn/Article/details/gtrcxhwkzl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtomchwzfn.html

Ruby: Dir.children("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxyysict.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gogol.net.cn/Article/details/gtlraghyjp.html

[F09] 获取文件大小
来源：http://dali.tianlin.xyz/Article/details/gtepoglvxs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtngigarrm.html

PHP:  filesize("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtjruyfiul.html

JS:   fs.statSync("a.txt").size
来源：http://dali.redwolf501.top/Article/details/gtasjjmhem.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cheryme.top/Article/details/gtojpuwzpb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtlhtcmple.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gotoacloud.top/Article/details/gtgrcdpisl.html

Ruby: File.size("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtvrpnioxm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuanzx.com/Article/details/gtrjndltzk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yonumen.top/Article/details/gtbxecxhur.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtrwtwibfu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xinyue.icu/Article/details/gtvbiqdcpd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtddmdgzlf.html

TS:   path.extname("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjixxnkxv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.meibo888.top/Article/details/gttcxarpak.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtkqurzmhu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtqxcilblc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtapcjuxlr.html

[F11] 复制与移动文件
来源：http://dali.cucudq.cn/Article/details/gtswbjlodz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtzjmiqbrv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtlhzcjazx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtolnfteiq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtwhbpbszr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuanzx.com/Article/details/gtcpyksruk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ydzc1.top/Article/details/gtfuzhgvml.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtdlbgghik.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmkhgadb.html

[F12] CSV 读写
来源：http://dali.sweek.top/Article/details/gteogotrug.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenzaomai.com/Article/details/gtheynpwkn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.meibo888.top/Article/details/gtkhfflncj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjkaszqo.html

TS:   // 同上
来源：http://dali.fzhhl.top/Article/details/gtszktoyme.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hysaishi.cn/Article/details/gtetkupojc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pycfn.com/Article/details/gtcpbrldxy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhoulong.xyz/Article/details/gtuwwumqjp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xylfe.cn/Article/details/gtxmdroobh.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtcsjrinjs.html

G. 面向对象
来源：http://dali.redwolf501.top/Article/details/gtdrfpphnx.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtxzujvtkr.html

[G01] 定义类
来源：http://dali.xinyue.icu/Article/details/gtlvrgjzza.html

Py:   class User: pass
来源：http://dali.316326.xyz/Article/details/gtlpsevgyj.html

PHP:  class User {}
来源：http://dali.yvedp.cn/Article/details/gtkgbaqexu.html

JS:   class User {}
来源：http://dali.fzhhl.top/Article/details/gtdgkcmzcn.html

TS:   class User { name: string = ""; }
来源：http://dali.tianlin.xyz/Article/details/gtrspwxhze.html

Java: class User {}
来源：http://dali.dianchejie.cn/Article/details/gtejvsajid.html

Go:   type User struct { Name string }
来源：http://dali.daxiang520.top/Article/details/gtcivgetob.html

Ruby: class User; end
来源：http://dali.dianchejie.cn/Article/details/gthahkomdv.html

C#:   class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtboiczxhl.html

[G02] 构造函数
来源：http://dali.gaohongyu789.top/Article/details/gthjkibibh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yvedp.cn/Article/details/gtbbwaefot.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.c1oappe.top/Article/details/gteeypkqzj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gtiiiplzjq.html

TS:   constructor(public name: string) {}
来源：http://dali.iojbl.cn/Article/details/gtwuhslpgp.html

Java: User(String name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gtbeoqycmw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpsaqphuy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cucudq.cn/Article/details/gtujefcbvm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.9152youxi.cn/Article/details/gtrzleufyb.html

[G03] 实例属性
来源：http://dali.ydzc1.top/Article/details/gtcqikfoev.html

Py:   self.name = "x"
来源：http://dali.sufxvd.cn/Article/details/gthxzwagbm.html

PHP:  public string $name = "x";
来源：http://dali.havefunace.top/Article/details/gtuqueozel.html

JS:   this.name = "x";
来源：http://dali.havefunace.top/Article/details/gtyxwqgjgm.html

TS:   name: string = "x";
来源：http://dali.bjfxy.top/Article/details/gtecdiyrbe.html

Java: private String name;
来源：http://dali.yuanzhike.top/Article/details/gtrmrckzwe.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ivvv.top/Article/details/gtkdpgiwmz.html

Ruby: @name = "x"
来源：http://dali.ydzc1.top/Article/details/gtbcpzzapl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tian-w.cn/Article/details/gtqnyasagi.html

[G04] 定义方法
来源：http://dali.tian-w.cn/Article/details/gtnvsvjfmi.html

Py:   def greet(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gtofddfjbs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtjuvxwjxo.html

JS:   greet() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtxiuqymuw.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtjgwrvrzu.html

Java: String greet() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtveijyors.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtlbhfmbjc.html

Ruby: def greet; @name; end
来源：http://dali.pycfn.com/Article/details/gtbmqygkvq.html

C#:   public string Greet() => Name;
来源：http://dali.haohaochexian.top/Article/details/gtxspwepuf.html

[G05] 继承
来源：http://dali.hammf.cn/Article/details/gtxhaidwmo.html

Py:   class Admin(User): pass
来源：http://dali.tian-w.cn/Article/details/gtamhhfccv.html

PHP:  class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtrcypmgtw.html

JS:   class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtrckvayfy.html

TS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtvwzzxotd.html

Java: class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtbbpgmsqz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj20258888.top/Article/details/gthdykeggq.html

Ruby: class Admin < User; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzcrrtxx.html

C#:   class Admin : User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtousaqjdc.html

[G06] 重写方法
来源：http://dali.yueranfly.top/Article/details/gtokakijdz.html

Py:   def greet(self): return "admin"
来源：http://dali.svipenyu.cn/Article/details/gtgxdfrokh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuldchfzm.html

JS:   greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtormgyrte.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtnlsyilaw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gtdwshwdxn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.meibo888.top/Article/details/gtkucwhxda.html

Ruby: def greet; "admin"; end
来源：http://dali.wangdashe.top/Article/details/gtbyilzkcd.html

C#:   public override string Greet() => "admin";
来源：http://dali.svipenyu.cn/Article/details/gthgnydmxs.html

[G07] 调用父类方法
来源：http://dali.mhx1999.top/Article/details/gtbosaxvnq.html

Py:   super().greet()
来源：http://dali.redwolf501.top/Article/details/gtlxpwvxya.html

PHP:  parent::greet();
来源：http://dali.ydzc1.top/Article/details/gtrhqarfml.html

JS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gtwqviomnx.html

TS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gtcaolqezu.html

Java: super.greet();
来源：http://dali.daxiang520.top/Article/details/gtzysmgcgx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daria6918.cn/Article/details/gtkvsehvby.html

Ruby: super
来源：http://dali.yueranfly.top/Article/details/gtilzlweum.html

C#:   base.Greet();
来源：http://dali.andypj.xyz/Article/details/gtzyjgzurq.html

[G08] 静态方法与属性
来源：http://dali.meibo888.top/Article/details/gtwncnreow.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj202588.top/Article/details/gtbogapxkp.html

PHP:  public static function f() {}
来源：http://dali.iojbl.cn/Article/details/gtdnrndixd.html

JS:   static f() {}
来源：http://dali.zhixingplan.top/Article/details/gtmdxayagb.html

TS:   static f(): void {}
来源：http://dali.birdmap.top/Article/details/gtcoubxfww.html

Java: static void f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtvszkvpmo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cheryme.top/Article/details/gtkszfcaxt.html

Ruby: def self.f; end
来源：http://dali.jyoumei.cn/Article/details/gtyijrgwrs.html

C#:   public static void F() {}
来源：http://dali.xylfe.cn/Article/details/gttagrahfz.html

[G09] 接口 / 抽象类
来源：http://dali.c1oappe.top/Article/details/gtygryyjnz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gteverghpv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhixingplan.top/Article/details/gtnuitqwse.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.snrcjt.cn/Article/details/gtidfsjcot.html

TS:   interface Shape { area(): number; }
来源：http://dali.andypj.xyz/Article/details/gtgqwzwivd.html

Java: interface Shape { double area(); }
来源：http://dali.andypj.xyz/Article/details/gttxxzugwt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.bjfxy.top/Article/details/gtjolsdqbp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.havefunace.top/Article/details/gtvznzuwze.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtzqhofush.html

[G10] 访问控制
来源：http://dali.sysykeji.top/Article/details/gtqegrsfiu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.316326.xyz/Article/details/gtqjbywrmw.html

PHP:  public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtqlgrybms.html

JS:   #private 字段；其余公开
来源：http://dali.ehwqpu.com/Article/details/gtwidiapva.html

TS:   public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gtxxtetedc.html

Java: public / protected / private / 默认包级
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqeudyogl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.dashuyun.cn/Article/details/gtybqcrecp.html

Ruby: public / protected / private
来源：http://dali.redwolf501.top/Article/details/gtakwzhmjd.html

C#:   public / protected / private / internal
来源：http://dali.9152youxi.cn/Article/details/gtivvdkynj.html

[G11] getter / setter
来源：http://dali.xinyue.icu/Article/details/gtjvmwayvw.html

Py:   @property 与 @x.setter
来源：http://dali.hnxiangtu.top/Article/details/gtkffdjldb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gtyvybjsbs.html

JS:   get name() { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gtmqgdtmer.html

TS:   get name(): string { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gtkksbpnub.html

Java: public String getName() { return name; }
来源：http://dali.jianghu66.top/Article/details/gtabczewwi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gteaximiuu.html

Ruby: attr_accessor :name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnxfwwmp.html

C#:   public string Name { get; set; }
来源：http://dali.zhoulong.xyz/Article/details/gtnnhshesr.html

[G12] 对象转字符串
来源：http://dali.haohaochexian.top/Article/details/gttrpemdwz.html

Py:   def __str__(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gtuzsqbwyb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtvphncfuf.html

JS:   toString() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtedyovaxa.html

TS:   toString(): string { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtwexzbmvg.html

Java: @Override public String toString() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtkwmdttfa.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gtqvagmdgh.html

Ruby: def to_s; @name; end
来源：http://dali.ivvv.top/Article/details/gtchjyufcm.html

C#:   public override string ToString() => Name;
来源：http://dali.chenlongwang.top/Article/details/gtxoorxyfv.html

[G13] 判断对象类型
来源：http://dali.zdqjudy.top/Article/details/gtssdsfikr.html

Py:   isinstance(u, User)
来源：http://dali.yonumen.top/Article/details/gtrgchufzj.html

PHP:  $u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtecjymoxa.html

JS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtckjbbwhg.html

TS:   u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtkdanwohm.html

Java: u instanceof User
来源：http://dali.yj20258.top/Article/details/gtewcdzetz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sweek.top/Article/details/gtttwtycmu.html

Ruby: u.is_a?(User)
来源：http://dali.fengsongda.top/Article/details/gtjpbcwvwi.html

C#:   u is User
来源：http://dali.zhongyouzk.top/Article/details/gteagdeban.html

[G14] 数据类 / record
来源：http://dali.jinqigfzy.top/Article/details/gttlcgjjtp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tian-w.cn/Article/details/gtkoueccuu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhoulong.xyz/Article/details/gtcmswllac.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jlsjyb.cn/Article/details/gtvgitezuy.html

TS:   type User = { name: string; age: number };
来源：http://dali.daria6918.cn/Article/details/gtifyoggav.html

Java: record User(String name, int age) {}
来源：http://dali.zdqjudy.top/Article/details/gttbpafjav.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdonihfyh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nanxinkj.top/Article/details/gttgxxqcul.html

C#:   record User(string Name, int Age);
来源：http://dali.hnxiangtu.top/Article/details/gtdurbkjyd.html

[G15] 枚举
来源：http://dali.jqgufenzy.top/Article/details/gtvimbswxs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cashguo.top/Article/details/gtaphekosa.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuhbpavno.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ydzc1.top/Article/details/gttftkgwxw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gtkdswiwke.html

Java: enum Color { RED, GREEN }
来源：http://dali.gzhubu.top/Article/details/gtfhfsfafm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zdqjudy.top/Article/details/gtornflxpi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cashguo.top/Article/details/gtgdmwcgib.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cdnleiting.top/Article/details/gttlappufg.html

[G16] 对象转数组 / 字典
来源：http://dali.dashuyun.cn/Article/details/gtqozserok.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gotoacloud.top/Article/details/gtzsgrbvic.html

PHP:  get_object_vars($obj);
来源：http://dali.iojbl.cn/Article/details/gttrziumrw.html

JS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gtetphqzgy.html

TS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gtzcbvngzz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hammf.cn/Article/details/gtiggjohjk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yongpay.top/Article/details/gtcuyhfrcz.html

Ruby: obj.instance_variables
来源：http://dali.hammf.cn/Article/details/gtmmkktqge.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.bjfxy.top/Article/details/gtuljaeoen.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtsucsbkru.html

H. 异常与错误处理
来源：http://dali.aibaodan.cn/Article/details/gtragcbmge.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtoknwyybi.html

[H01] try / catch 基础
来源：http://dali.ywan-chungtsiang.top/Article/details/gturcesauj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hysaishi.cn/Article/details/gtvlohzftg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.iojbl.cn/Article/details/gtcxvbbqsb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gtqkegnvvc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gtgqnrjloc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yvedp.cn/Article/details/gtpxzssibh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangshuangyany.cn/Article/details/gtprmxkkuo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.bjfxy.top/Article/details/gtwukyphhf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shzxlz.cn/Article/details/gtklytmrzn.html

[H02] finally / ensure 收尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfzowiexr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zycfv.cn/Article/details/gtqtndcclp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtqeemgvmz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtigbdyroz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtlcnuqmur.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtahiqwsfp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.haohaochexian.top/Article/details/gtemzclfki.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.svipenyu.cn/Article/details/gtzbdrefzk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sweek.top/Article/details/gtjicaovnn.html

[H03] 主动抛出异常
来源：http://dali.jqgfzy.top/Article/details/gtbsphbodl.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttonnldvd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gtchxfjtgj.html

JS:   throw new Error("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtwfnqkebc.html

TS:   throw new Error("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtuiejranh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtagnkdbwa.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xylfe.cn/Article/details/gtdqduzgbo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yueranfly.top/Article/details/gttlusvgms.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtzsmcrxce.html

[H04] 自定义异常类型
来源：http://dali.jinqigfzy.top/Article/details/gtvmhnjfsp.html

Py:   class MyError(Exception): pass
来源：http://dali.yongpay.top/Article/details/gtecfztrxx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.feifeiyinyue.top/Article/details/gttywqkwec.html

JS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gtzerixrll.html

TS:   class MyError extends Error {}
来源：http://dali.hammf.cn/Article/details/gtehhzkslu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gtlbvjohjc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.feifeiyinyue.top/Article/details/gtjjakutif.html

Ruby: class MyError < StandardError; end
来源：http://dali.jlsjyb.cn/Article/details/gtebrmfmlt.html

C#:   class MyException : Exception {}
来源：http://dali.feifeiyinyue.top/Article/details/gtkctlzboo.html

[H05] 捕获特定类型
来源：http://dali.nanxuanxn.top/Article/details/gtfhnebfub.html

Py:   except ValueError as e:
来源：http://dali.haohaochexian.top/Article/details/gtyeuzauqq.html


<!-- 参考信息 -->