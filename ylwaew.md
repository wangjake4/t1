代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shuidangran.top/Article/details/gtmtkvsuid.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hongshengwenyu.top/Article/details/gttuhrlbcp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.daria6918.cn/Article/details/gtrgijhsln.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtazrjtwod.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hammf.cn/Article/details/gtqpignasb.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gttfkzpsar.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gtfetmwknh.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtmnwbxilc.html

[F01] 读取整个文件
来源：http://dali.chenlongwang.top/Article/details/gtbsrkhkts.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sysykeji.top/Article/details/gtymksznjq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.pycfn.com/Article/details/gtfilqcdos.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.kuanghao11.cn/Article/details/gtmqfcnazl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gtsmjompbb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtklabcslo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.snrcjt.cn/Article/details/gtsimldpps.html

Ruby: File.read("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtvjdmaeyh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtyyddvxfu.html

[F02] 逐行读取文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtickkboig.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.c1oappe.top/Article/details/gtmgjnupbm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.svipenyu.cn/Article/details/gtoemvmocv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtchhnethn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aizwys.cn/Article/details/gthqxalfwc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.316326.xyz/Article/details/gtevuwhqyl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj20258.top/Article/details/gttrtivyyw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hysaishi.cn/Article/details/gtchexjhts.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnxiangtu.top/Article/details/gtrcgpefvb.html

[F03] 写入文件（覆盖）
来源：http://dali.jinqigfzy.top/Article/details/gtngrvgvjp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.bjfxy.top/Article/details/gtfrtmgyhp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zdqjudy.top/Article/details/gtcwkjfgdl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtytfrccxk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yongpay.top/Article/details/gtqtltpvkv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtomexsbrl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.0kj1m.cn/Article/details/gtpfeqhaok.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sysykeji.top/Article/details/gtyqclqsgl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gttakmruef.html

[F04] 追加写入文件
来源：http://dali.meibo888.top/Article/details/gtvkdbraqq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenlongwang.top/Article/details/gtqtfqvfaa.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jiagoushi.top/Article/details/gtzqwkutkp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigufen.top/Article/details/gttrcwlkho.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gtifmpozea.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jlsjyb.cn/Article/details/gtcwdckoop.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.fzhhl.top/Article/details/gtquaepjkl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.pengpengdd.cyou/Article/details/gtciieobaa.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzcqrnhij.html

[F05] 判断文件或目录是否存在
来源：http://dali.hammf.cn/Article/details/gtxmfnseap.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.daxiang520.top/Article/details/gtulfomilv.html

PHP:  file_exists("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnpezwrif.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklbyeesu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtxwrhlzcd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjenkedt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttncdnxtv.html

Ruby: File.exist?("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtfjojynho.html

C#:   File.Exists("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtogfpenup.html

[F06] 删除文件
来源：http://dali.xuanzx.com/Article/details/gtnalkgdmw.html

Py:   os.remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gtngebpbct.html

PHP:  unlink("a.txt");
来源：http://dali.xuanzx.com/Article/details/gthpmvnteo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gttoicnczv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtyasosivt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtutasenyt.html

Go:   os.Remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtwdsizezu.html

Ruby: File.delete("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtucizntxs.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxsgwwwuw.html

[F07] 创建目录（含多级）
来源：http://dali.aizwys.cn/Article/details/gtvsqasjkk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hammf.cn/Article/details/gttgxkdzlt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.fengsongda.top/Article/details/gtowsxfytl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.9152youxi.cn/Article/details/gtitoiacla.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.andypj.xyz/Article/details/gtewlobfom.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tianlin.xyz/Article/details/gtlglxglgh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jlsjyb.cn/Article/details/gtfgcjkbyq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yueranfly.top/Article/details/gtveenaild.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jlsjyb.cn/Article/details/gtqhgbfkhp.html

[F08] 遍历目录
来源：http://dali.shuidangran.top/Article/details/gtnqbbdeft.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.0kj1m.cn/Article/details/gtsexvkxny.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.smart0.xyz/Article/details/gtjhyzhsgz.html

JS:   fs.readdirSync("dir")
来源：http://dali.yangfankeji.com/Article/details/gthkcdlpul.html

TS:   fs.readdirSync("dir")
来源：http://dali.ivvv.top/Article/details/gtnmqclqwb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gtbdolgktl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.redwolf501.top/Article/details/gtbgbihume.html

Ruby: Dir.children("dir")
来源：http://dali.jiagoushi.top/Article/details/gtjsdgkydn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gotoacloud.top/Article/details/gtxrlqbpdo.html

[F09] 获取文件大小
来源：http://dali.gotoacloud.top/Article/details/gtkdutrozp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtfesbcvau.html

PHP:  filesize("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtrsetsanc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pengpengdd.cyou/Article/details/gteexrktsb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.guowangkeji.top/Article/details/gtvasqsfcr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtosbgpegj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gotoacloud.top/Article/details/gtojhhgoyc.html

Ruby: File.size("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtobzngkmo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yvedp.cn/Article/details/gtgkoxlpbs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yueranfly.top/Article/details/gtwjncphgz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtqvidjfrm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtvsrnchwn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtnzyrceac.html

TS:   path.extname("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gttkwtlzaf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cashguo.top/Article/details/gtaenloydo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtvoeuhubj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtpskfrezw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gteznolhpu.html

[F11] 复制与移动文件
来源：http://dali.snrcjt.cn/Article/details/gtfwepushk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtyaenbgvq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinqigfzy.top/Article/details/gttldhhfgt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gthizinjne.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gttptipive.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hywenlv.cn/Article/details/gtqocxrygk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj20258888.top/Article/details/gtjmrrufnz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtysdenoff.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jianghu66.top/Article/details/gtgaxlfvbe.html

[F12] CSV 读写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkizbeblx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.guannengcc.top/Article/details/gtrszbgtfl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guannengcc.top/Article/details/gtbvqkdpkj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbtmhimrx.html

TS:   // 同上
来源：http://dali.cdnleiting.top/Article/details/gtclqditzt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuxming.cn/Article/details/gtjsvkwphk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.guowangkeji.top/Article/details/gtqmnqsbxv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yueranfly.top/Article/details/gtlklzsjyu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zycfv.cn/Article/details/gtfhlqjmjh.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtepqfekfb.html

G. 面向对象
来源：http://dali.jiagoushi.top/Article/details/gtkdqywpvi.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtepympcie.html

[G01] 定义类
来源：http://dali.haohaochexian.top/Article/details/gtfzjhcgxo.html

Py:   class User: pass
来源：http://dali.ppjwa.cn/Article/details/gthqwrrydq.html

PHP:  class User {}
来源：http://dali.iojbl.cn/Article/details/gtbdhnnpzc.html

JS:   class User {}
来源：http://dali.svipenyu.cn/Article/details/gtlgtldjym.html

TS:   class User { name: string = ""; }
来源：http://dali.gzhubu.top/Article/details/gthtexblqk.html

Java: class User {}
来源：http://dali.chenlongwang.top/Article/details/gtyulqcnjb.html

Go:   type User struct { Name string }
来源：http://dali.pengpengdd.cyou/Article/details/gtuaifjvop.html

Ruby: class User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwljbxgsn.html

C#:   class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtpslwbare.html

[G02] 构造函数
来源：http://dali.chenlongwang.top/Article/details/gtmokhcgie.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cdnleiting.top/Article/details/gtipvrtptu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yueranfly.top/Article/details/gttjqxveel.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.316326.xyz/Article/details/gtzuzrgfnp.html

TS:   constructor(public name: string) {}
来源：http://dali.pengpengdd.cyou/Article/details/gthwtramhv.html

Java: User(String name) { this.name = name; }
来源：http://dali.pycfn.com/Article/details/gtbkgizeff.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sweek.top/Article/details/gtflknepst.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cqqwz.cn/Article/details/gtgqjcfpgr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.mhx1999.top/Article/details/gtxcmglalk.html

[G03] 实例属性
来源：http://dali.fengsongda.top/Article/details/gtagqmaruw.html

Py:   self.name = "x"
来源：http://dali.yongpay.top/Article/details/gtonjdfdss.html

PHP:  public string $name = "x";
来源：http://dali.sufxvd.cn/Article/details/gttmvcpnwj.html

JS:   this.name = "x";
来源：http://dali.zycfv.cn/Article/details/gtcguhwjyl.html

TS:   name: string = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqdfcqlp.html

Java: private String name;
来源：http://dali.quarkkingdee.top/Article/details/gtsfnxupro.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hfpthk.cn/Article/details/gtgtdymizb.html

Ruby: @name = "x"
来源：http://dali.yuxming.cn/Article/details/gtehpgjxiu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aibaodan.cn/Article/details/gtrqcjtmxk.html

[G04] 定义方法
来源：http://dali.yanxiufei.cn/Article/details/gtcwveoddo.html

Py:   def greet(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gtrpdkrcmd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gtspeidedq.html

JS:   greet() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtfgmcvkqp.html

TS:   greet(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtcaraqibh.html

Java: String greet() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtmdxuxqpu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gteoovfzbx.html

Ruby: def greet; @name; end
来源：http://dali.havefunace.top/Article/details/gttpbbtuss.html

C#:   public string Greet() => Name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsebxpfyg.html

[G05] 继承
来源：http://dali.yonumen.top/Article/details/gthvsuijgh.html

Py:   class Admin(User): pass
来源：http://dali.kuanghao11.cn/Article/details/gtfmemfctn.html

PHP:  class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtzqnnbjph.html

JS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtltegnihu.html

TS:   class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gturbmlaoa.html

Java: class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtvwsdzndg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ppjwa.cn/Article/details/gthgifmqza.html

Ruby: class Admin < User; end
来源：http://dali.bjfxy.top/Article/details/gtmqyyeyuo.html

C#:   class Admin : User {}
来源：http://dali.xylfe.cn/Article/details/gtrtndmkqu.html

[G06] 重写方法
来源：http://dali.smart0.xyz/Article/details/gtycyicupk.html

Py:   def greet(self): return "admin"
来源：http://dali.zycfv.cn/Article/details/gtyoloberp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtlvrvtiyx.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtjzkbdypx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtegjdvjea.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtsjlfacyd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenjidiqi.icu/Article/details/gtdlgjjqrc.html

Ruby: def greet; "admin"; end
来源：http://dali.cucudq.cn/Article/details/gtljfrpjsx.html

C#:   public override string Greet() => "admin";
来源：http://dali.tanke756.top/Article/details/gtpvxtnfxn.html

[G07] 调用父类方法
来源：http://dali.zhengqikj.top/Article/details/gtdcvacsfj.html

Py:   super().greet()
来源：http://dali.sweek.top/Article/details/gtipnakqbo.html

PHP:  parent::greet();
来源：http://dali.jlsjyb.cn/Article/details/gtcuzpcyrm.html

JS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gtblmvhmte.html

TS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gtwhepgnva.html

Java: super.greet();
来源：http://dali.jiagoushi.top/Article/details/gtgirhmojm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xuanzx.com/Article/details/gtoulhnqxx.html

Ruby: super
来源：http://dali.fengsongda.top/Article/details/gtjxivlbdf.html

C#:   base.Greet();
来源：http://dali.jinqigufen.top/Article/details/gtmuzsxpwp.html

[G08] 静态方法与属性
来源：http://dali.zhoulong.xyz/Article/details/gtahfvoihw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhengqikj.top/Article/details/gtpswrpkme.html

PHP:  public static function f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtgwwllznl.html

JS:   static f() {}
来源：http://dali.hysaishi.cn/Article/details/gtquvzcfbv.html

TS:   static f(): void {}
来源：http://dali.daxiang520.top/Article/details/gtcupygkja.html

Java: static void f() {}
来源：http://dali.kuanghao11.cn/Article/details/gtqdvtwnro.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nanxuanxn.top/Article/details/gtqgtjhixc.html

Ruby: def self.f; end
来源：http://dali.jianghu66.top/Article/details/gtmdthfpzv.html

C#:   public static void F() {}
来源：http://dali.wangdashe.top/Article/details/gtlmmzghwz.html

[G09] 接口 / 抽象类
来源：http://dali.smart0.xyz/Article/details/gtbzkttqbf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gzhubu.top/Article/details/gtfcqvvxzq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.0kj1m.cn/Article/details/gtrrgopjrm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sxryk.cn/Article/details/gtuqpzmtns.html

TS:   interface Shape { area(): number; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgitgbpuu.html

Java: interface Shape { double area(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfwqfrklk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258.top/Article/details/gtbhqqtpez.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tianlin.xyz/Article/details/gtdomtoenz.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhengqikj.top/Article/details/gtsdmmxwhq.html

[G10] 访问控制
来源：http://dali.pengpengdd.cyou/Article/details/gteqxeckve.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tianlin.xyz/Article/details/gtexybpnqj.html

PHP:  public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtudfzbmxi.html

JS:   #private 字段；其余公开
来源：http://dali.xuetiantiany.cn/Article/details/gtsuidytur.html

TS:   public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gtdgdvmvfv.html

Java: public / protected / private / 默认包级
来源：http://dali.quarkkingdee.top/Article/details/gtykottfme.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yangfankeji.com/Article/details/gtluthppof.html

Ruby: public / protected / private
来源：http://dali.redwolf501.top/Article/details/gtuaogwqmq.html

C#:   public / protected / private / internal
来源：http://dali.vqdsnc.cn/Article/details/gtpyedibdu.html

[G11] getter / setter
来源：http://dali.zhongyouzk.top/Article/details/gtujrwukln.html

Py:   @property 与 @x.setter
来源：http://dali.fzhhl.top/Article/details/gtxpjgnrlj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gtwkzwrhoz.html

JS:   get name() { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gtnjchbxhx.html

TS:   get name(): string { return this._name; }
来源：http://dali.jqgfzy.top/Article/details/gtziwlzuzk.html

Java: public String getName() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtkynmxacr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gtoqcphaya.html

Ruby: attr_accessor :name
来源：http://dali.zhongyouzk.top/Article/details/gtujukwadf.html

C#:   public string Name { get; set; }
来源：http://dali.daria6918.cn/Article/details/gtgnvmenvy.html

[G12] 对象转字符串
来源：http://dali.nanxinkj.top/Article/details/gtudtxluzl.html

Py:   def __str__(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gtqgdarjyz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gtaibsokpg.html

JS:   toString() { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtnxoxcrkb.html

TS:   toString(): string { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtuemkzmpu.html

Java: @Override public String toString() { return name; }
来源：http://dali.ivvv.top/Article/details/gtgcxkbjuj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gtamakxyti.html

Ruby: def to_s; @name; end
来源：http://dali.meibo888.top/Article/details/gtdxcxbypi.html

C#:   public override string ToString() => Name;
来源：http://dali.daria6918.cn/Article/details/gtuorlpbra.html

[G13] 判断对象类型
来源：http://dali.meibo888.top/Article/details/gtflsmiqzt.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxiemyfc.html

PHP:  $u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtjrnyguhl.html

JS:   u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gtwwthdkjs.html

TS:   u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gthcdfcven.html

Java: u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtftzzfugt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.haohaochexian.top/Article/details/gtgnbxyntn.html

Ruby: u.is_a?(User)
来源：http://dali.smart0.xyz/Article/details/gtwkyikfsb.html

C#:   u is User
来源：http://dali.yueranfly.top/Article/details/gtwqbttddq.html

[G14] 数据类 / record
来源：http://dali.ehwqpu.com/Article/details/gtqkualsah.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuanzx.com/Article/details/gtirjdedbi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sysykeji.top/Article/details/gtbbhrtrts.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yongpay.top/Article/details/gtechmqcpv.html

TS:   type User = { name: string; age: number };
来源：http://dali.hammf.cn/Article/details/gtneczjgtg.html

Java: record User(String name, int age) {}
来源：http://dali.jqgfzy.top/Article/details/gtzkagcoen.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cashguo.top/Article/details/gtxlafqshu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ehwqpu.com/Article/details/gtzmpxgaiq.html

C#:   record User(string Name, int Age);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdmfcbti.html

[G15] 枚举
来源：http://dali.jlsjyb.cn/Article/details/gtvenuwibl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.haohaochexian.top/Article/details/gtxrnlrgkc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cashguo.top/Article/details/gtighxxxoo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yueranfly.top/Article/details/gtczxlpltm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gtujpcpnky.html

Java: enum Color { RED, GREEN }
来源：http://dali.gaohongyu789.top/Article/details/gtnjexqlri.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zdqjudy.top/Article/details/gtjjciqmht.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzsmgjdwf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gtufdaiohq.html

[G16] 对象转数组 / 字典
来源：http://dali.gzhubu.top/Article/details/gtjiiltnpv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgufenzy.top/Article/details/gtcqemqlzo.html

PHP:  get_object_vars($obj);
来源：http://dali.jyoumei.cn/Article/details/gtmevbxzik.html

JS:   Object.entries(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtpzxifmff.html

TS:   Object.entries(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtulkoqfuc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.haohaochexian.top/Article/details/gtqjsxiyyz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangshuangyany.cn/Article/details/gtgowmabzo.html

Ruby: obj.instance_variables
来源：http://dali.shzxlz.cn/Article/details/gtfhgluutr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gtmzlpobhp.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtdpczkoki.html

H. 异常与错误处理
来源：http://dali.yuanzhike.top/Article/details/gtrnwkgeip.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtvfyvgfgf.html

[H01] try / catch 基础
来源：http://dali.yongpay.top/Article/details/gtfsqpcgoc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.meibo888.top/Article/details/gtvxqarlqk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sufxvd.cn/Article/details/gtrvtsypcv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gtxewvffek.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gtacmtukoq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gtgvryabdb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jqgfzy.top/Article/details/gtmipteffl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinqigufen.top/Article/details/gtazyartml.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhixingplan.top/Article/details/gteykcfknf.html

[H02] finally / ensure 收尾
来源：http://dali.yonumen.top/Article/details/gtgyllvprd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shangyingyoupin.top/Article/details/gtfvxqzlsi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gteugmcgbn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtrizmeqpb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gttqyedkhe.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtdflijhpm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258888.top/Article/details/gtykzyoroi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.birdmap.top/Article/details/gtircdsjlb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtaxngupqp.html

[H03] 主动抛出异常
来源：http://dali.iojbl.cn/Article/details/gtrsxhcsnr.html

Py:   raise ValueError("错误信息")
来源：http://dali.cashguo.top/Article/details/gtnwdrlqxx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtpoynvahs.html

JS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtkrzzrgoi.html

TS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtbaqejlnl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtdcovcnxb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.pengpengdd.cyou/Article/details/gtuycdbdhq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuetiantiany.cn/Article/details/gtuudqjixm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtlrsqbgtz.html

[H04] 自定义异常类型
来源：http://dali.cashguo.top/Article/details/gtxcsaadqn.html

Py:   class MyError(Exception): pass
来源：http://dali.cucudq.cn/Article/details/gtuedhgdrt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.vqdsnc.cn/Article/details/gtpqtehjhr.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gtqsvwenmp.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjuhqkrpf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gtwfauoove.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jyoumei.cn/Article/details/gtdvmrgvlb.html


<!-- 参考信息 -->