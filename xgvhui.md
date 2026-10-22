代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gtlnrvoovd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yvedp.cn/Article/details/gtnlufztzj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jqgufenzy.top/Article/details/gtqzgokuxc.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvwshaiiw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sysykeji.top/Article/details/gtjdkanlcg.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtdncbewpr.html

F. 文件与目录
来源：http://dali.snrcjt.cn/Article/details/gtxwrbtevw.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtyjyupnra.html

[F01] 读取整个文件
来源：http://dali.ppjwa.cn/Article/details/gtfihkrrzq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hnxiangtu.top/Article/details/gtgpaueqjo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj20258.top/Article/details/gthtgwiyqv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.andypj.xyz/Article/details/gttbbdphbt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gtmviysgyr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtgpexmkwz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenlongwang.top/Article/details/gtlizqinrv.html

Ruby: File.read("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtqfumwkbf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtkfmblfbj.html

[F02] 逐行读取文件
来源：http://dali.feifeiyinyue.top/Article/details/gtfaqpeoaz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenlongwang.top/Article/details/gtadcsqafv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hywenlv.cn/Article/details/gtqmqlzfih.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gtkqcwexao.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xinyue.icu/Article/details/gtrofgtllw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tanke756.top/Article/details/gtfmcqwyzk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.vqdsnc.cn/Article/details/gtkwqfmwpm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tanke756.top/Article/details/gtaskijjne.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj20258888.top/Article/details/gtopvifhuf.html

[F03] 写入文件（覆盖）
来源：http://dali.bjfxy.top/Article/details/gtznhtelpx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xuetiantiany.cn/Article/details/gteoydawfa.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tanke756.top/Article/details/gtwsyjkznx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtqyizgjiv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gtgomxhxxg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gaohongyu789.top/Article/details/gtrqzjfvut.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zdqjudy.top/Article/details/gtghjeklcm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.andypj.xyz/Article/details/gtnlysemxf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gtvjhxosss.html

[F04] 追加写入文件
来源：http://dali.jlsjyb.cn/Article/details/gtristfdwt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shzxlz.cn/Article/details/gtyaufxwrx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhoulong.xyz/Article/details/gtqaiqogam.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gtgtzbmywg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtixscquaj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.c1oappe.top/Article/details/gtgmfsvllp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sweek.top/Article/details/gtpvlupjur.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hnqzz.top/Article/details/gtwhrqrcnv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwfiffymi.html

[F05] 判断文件或目录是否存在
来源：http://dali.316326.xyz/Article/details/gthxiivvwl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj202588.top/Article/details/gtqodqqixr.html

PHP:  file_exists("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gttawmtuhu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtyrsbrrfp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtjydebxcq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gtoupblfqi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj202588.top/Article/details/gtknxdrmck.html

Ruby: File.exist?("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtmuprgwro.html

C#:   File.Exists("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtarmirppb.html

[F06] 删除文件
来源：http://dali.havefunace.top/Article/details/gtjgyqbspi.html

Py:   os.remove("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtgfnbebqb.html

PHP:  unlink("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtgwcbuyrj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtzrcfgxkf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtjwivaqtv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gtgfmxwdhd.html

Go:   os.Remove("a.txt")
来源：http://dali.ivvv.top/Article/details/gtxlxpovdg.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtrozkxfkx.html

C#:   File.Delete("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtiyvnkbzd.html

[F07] 创建目录（含多级）
来源：http://dali.sxryk.cn/Article/details/gtqjbhmxjo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nwbrower.top/Article/details/gtpettppfc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hammf.cn/Article/details/gtlrljzjaz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gtakdvaotb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gtcszgesti.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cdnleiting.top/Article/details/gtounbzixq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guannengcc.top/Article/details/gtxktyxkmn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shanyushiyangtech.top/Article/details/gtinvuqgfv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cashguo.top/Article/details/gtptkmsprx.html

[F08] 遍历目录
来源：http://dali.hnqzz.top/Article/details/gtijjfshji.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgfzy.top/Article/details/gtbxskkuyo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jlsjyb.cn/Article/details/gtdwnusqtq.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxqmkmzk.html

TS:   fs.readdirSync("dir")
来源：http://dali.svipenyu.cn/Article/details/gtlwiynyhs.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zycfv.cn/Article/details/gtgtgicckj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.bjfxy.top/Article/details/gtycbuupte.html

Ruby: Dir.children("dir")
来源：http://dali.yueranfly.top/Article/details/gtvieflpzw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.daxiang520.top/Article/details/gtpkzhiqgp.html

[F09] 获取文件大小
来源：http://dali.nanxinkj.top/Article/details/gtotrwvbso.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtgecagovy.html

PHP:  filesize("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtmsegqfyv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinghuilouyu.cn/Article/details/gtncypjqif.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangtech.top/Article/details/gtvyqlaxuh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gthlwkbpcs.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.svipenyu.cn/Article/details/gtkcktujky.html

Ruby: File.size("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtqrxozrye.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fengsongda.top/Article/details/gtpfmrhwff.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hysaishi.cn/Article/details/gtbkesivlx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtcqlpdruj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.guannengcc.top/Article/details/gtugjsztaw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtsoqodnxk.html

TS:   path.extname("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlizzcuja.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.haohaochexian.top/Article/details/gtgkblyals.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevpfcpsh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtzzufymlz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtozyvqjux.html

[F11] 复制与移动文件
来源：http://dali.yj202588.top/Article/details/gttlzhctge.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtoxghzwkm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtdygodlfy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgopxhlev.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtenkzyosd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ybcxt.top/Article/details/gtcxpvskhv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.smart0.xyz/Article/details/gthuhirams.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtadeznyki.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenzaomai.com/Article/details/gtmaipxcbq.html

[F12] CSV 读写
来源：http://dali.hammf.cn/Article/details/gtojdetzqt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aibaodan.cn/Article/details/gtljhflksm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shangyingyoupin.top/Article/details/gtyvrlkfyw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.kuanghao11.cn/Article/details/gtiovioocm.html

TS:   // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gthrrgghhk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcaovdvum.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hammf.cn/Article/details/gtydoinmsq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hongshengwenyu.top/Article/details/gtgjclucos.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sweek.top/Article/details/gtllaznygl.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtlaeoryxr.html

G. 面向对象
来源：http://dali.zycfv.cn/Article/details/gtmkmqffky.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtvmqozobw.html

[G01] 定义类
来源：http://dali.chenjidiqi.icu/Article/details/gtudqqguwt.html

Py:   class User: pass
来源：http://dali.nanxuanxn.top/Article/details/gturvecudt.html

PHP:  class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtwsgegnaj.html

JS:   class User {}
来源：http://dali.xuanzx.com/Article/details/gtynyigcvk.html

TS:   class User { name: string = ""; }
来源：http://dali.yj202588.top/Article/details/gtfxeryhqg.html

Java: class User {}
来源：http://dali.xylfe.cn/Article/details/gteiueyagn.html

Go:   type User struct { Name string }
来源：http://dali.shzxlz.cn/Article/details/gtmrfevjty.html

Ruby: class User; end
来源：http://dali.gogol.net.cn/Article/details/gtcjjklrjq.html

C#:   class User {}
来源：http://dali.dashuyun.cn/Article/details/gtqiuhiviz.html

[G02] 构造函数
来源：http://dali.xinyue.icu/Article/details/gtaezdzahm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj202588.top/Article/details/gtoipfppid.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgjxniiig.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtktuislwe.html

TS:   constructor(public name: string) {}
来源：http://dali.jqgufenzy.top/Article/details/gtfjezcdiw.html

Java: User(String name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtphfnqhcs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.0kj1m.cn/Article/details/gtopqhhbeq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdbadysw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ybcxt.top/Article/details/gtsyeubnwp.html

[G03] 实例属性
来源：http://dali.sufxvd.cn/Article/details/gtvxnkqvzu.html

Py:   self.name = "x"
来源：http://dali.xziqi.cn/Article/details/gtuefvalhx.html

PHP:  public string $name = "x";
来源：http://dali.yueranfly.top/Article/details/gtjskgrpop.html

JS:   this.name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtdlxhpzqd.html

TS:   name: string = "x";
来源：http://dali.iojbl.cn/Article/details/gtwzveqvio.html

Java: private String name;
来源：http://dali.daria6918.cn/Article/details/gtrzpauajq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.9152youxi.cn/Article/details/gtjplgeiee.html

Ruby: @name = "x"
来源：http://dali.zhixingplan.top/Article/details/gtbndibsko.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gotoacloud.top/Article/details/gtrhdppigm.html

[G04] 定义方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwmyuzfq.html

Py:   def greet(self): return self.name
来源：http://dali.ybcxt.top/Article/details/gtnmmibfkr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gtbuhtlreu.html

JS:   greet() { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtbvlnrydn.html

TS:   greet(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtxsadgxlh.html

Java: String greet() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtbszzlpox.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gtyvbtwgnd.html

Ruby: def greet; @name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmppdsxgl.html

C#:   public string Greet() => Name;
来源：http://dali.andypj.xyz/Article/details/gtculutquz.html

[G05] 继承
来源：http://dali.hnxiangtu.top/Article/details/gtptswpcqf.html

Py:   class Admin(User): pass
来源：http://dali.gzhubu.top/Article/details/gtygjkslhg.html

PHP:  class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtefjatyhu.html

JS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtvabhvdat.html

TS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtyucthxmi.html

Java: class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtllfevotj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxtguxlzm.html

Ruby: class Admin < User; end
来源：http://dali.zycfv.cn/Article/details/gtyroubzon.html

C#:   class Admin : User {}
来源：http://dali.hfpthk.cn/Article/details/gtebulnfyo.html

[G06] 重写方法
来源：http://dali.ydzc1.top/Article/details/gtpqrguyca.html

Py:   def greet(self): return "admin"
来源：http://dali.hnxiangtu.top/Article/details/gtvdymabby.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtbkekxagm.html

JS:   greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtszxvnuoi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtlidwfmoq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtunqbuazf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xziqi.cn/Article/details/gtvpcwmfrb.html

Ruby: def greet; "admin"; end
来源：http://dali.yj20258.top/Article/details/gtivyhrxnu.html

C#:   public override string Greet() => "admin";
来源：http://dali.guowangkeji.top/Article/details/gtpepdryii.html

[G07] 调用父类方法
来源：http://dali.birdmap.top/Article/details/gteqcdrjqy.html

Py:   super().greet()
来源：http://dali.zhoulong.xyz/Article/details/gtimzjgonw.html

PHP:  parent::greet();
来源：http://dali.cqqwz.cn/Article/details/gtcmsgbmpk.html

JS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gtagwiqakj.html

TS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtsbgsmabo.html

Java: super.greet();
来源：http://dali.ehwqpu.com/Article/details/gthtrhzkoy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhixingplan.top/Article/details/gtyppgnwwk.html

Ruby: super
来源：http://dali.quarkkingdee.top/Article/details/gtjmsruces.html

C#:   base.Greet();
来源：http://dali.tanke756.top/Article/details/gtbxruxmdd.html

[G08] 静态方法与属性
来源：http://dali.hnqzz.top/Article/details/gteoygnziz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yueranfly.top/Article/details/gtlwhazmjg.html

PHP:  public static function f() {}
来源：http://dali.ivvv.top/Article/details/gtrqgczacp.html

JS:   static f() {}
来源：http://dali.bjfxy.top/Article/details/gtfggjakcv.html

TS:   static f(): void {}
来源：http://dali.yuanzhike.top/Article/details/gtpwqqbqgy.html

Java: static void f() {}
来源：http://dali.snrcjt.cn/Article/details/gthsiigvfy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenlongwang.top/Article/details/gtaofqvqyq.html

Ruby: def self.f; end
来源：http://dali.jinqigufen.top/Article/details/gtlqpwhrao.html

C#:   public static void F() {}
来源：http://dali.zycfv.cn/Article/details/gtumibedfw.html

[G09] 接口 / 抽象类
来源：http://dali.yuxming.cn/Article/details/gtpdtqysry.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangdashe.top/Article/details/gtdkewkvjf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.0kj1m.cn/Article/details/gtfohwrkim.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cucudq.cn/Article/details/gtzcfsittj.html

TS:   interface Shape { area(): number; }
来源：http://dali.mhx1999.top/Article/details/gtxqanmalo.html

Java: interface Shape { double area(); }
来源：http://dali.ybcxt.top/Article/details/gtoomagerl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cucudq.cn/Article/details/gtranxsius.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.feifeiyinyue.top/Article/details/gtdsevgjvv.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gtcuzbxifr.html

[G10] 访问控制
来源：http://dali.birdmap.top/Article/details/gtbhvmgrnr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shangyingyoupin.top/Article/details/gtemhxrtij.html

PHP:  public / protected / private
来源：http://dali.yj20258.top/Article/details/gtdqivlyrz.html

JS:   #private 字段；其余公开
来源：http://dali.gaohongyu789.top/Article/details/gttgfunyuq.html

TS:   public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtkvfogezv.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtccxuuw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.vqdsnc.cn/Article/details/gtszcgwicj.html

Ruby: public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gtecynvmzv.html

C#:   public / protected / private / internal
来源：http://dali.ivvv.top/Article/details/gtjooprtsa.html

[G11] getter / setter
来源：http://dali.ppjwa.cn/Article/details/gtbakgonbl.html

Py:   @property 与 @x.setter
来源：http://dali.chenlongwang.top/Article/details/gtbjlujhtc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtcbznerak.html

JS:   get name() { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gtojzfbsph.html

TS:   get name(): string { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gtzvysijeq.html

Java: public String getName() { return name; }
来源：http://dali.hammf.cn/Article/details/gtpemciqfl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtpwibgmwz.html

Ruby: attr_accessor :name
来源：http://dali.hnqzz.top/Article/details/gtikvzzwxt.html

C#:   public string Name { get; set; }
来源：http://dali.yangfankeji.com/Article/details/gthkqjxbdv.html

[G12] 对象转字符串
来源：http://dali.nwbrower.top/Article/details/gtcxhjtdks.html

Py:   def __str__(self): return self.name
来源：http://dali.hammf.cn/Article/details/gtloozbzgr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtslvpsscu.html

JS:   toString() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtqmazchdk.html

TS:   toString(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtuhsernqv.html

Java: @Override public String toString() { return name; }
来源：http://dali.shuidangran.top/Article/details/gtdvtpadhg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtdcukpznh.html

Ruby: def to_s; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrtoexbk.html

C#:   public override string ToString() => Name;
来源：http://dali.tanke756.top/Article/details/gtynbfmkyl.html

[G13] 判断对象类型
来源：http://dali.shangyingyoupin.top/Article/details/gtamxxucol.html

Py:   isinstance(u, User)
来源：http://dali.shzxlz.cn/Article/details/gtxpxyrynv.html

PHP:  $u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtgzyioycq.html

JS:   u instanceof User
来源：http://dali.cheryme.top/Article/details/gturllljwh.html

TS:   u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtxbdkabtl.html

Java: u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtucbcppgp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.daxiang520.top/Article/details/gtqtytnbtj.html

Ruby: u.is_a?(User)
来源：http://dali.iojbl.cn/Article/details/gtlhhhoekw.html

C#:   u is User
来源：http://dali.hywenlv.cn/Article/details/gtmjxbgkqy.html

[G14] 数据类 / record
来源：http://dali.sxryk.cn/Article/details/gthlyaftkg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zycfv.cn/Article/details/gteyxeutzx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.9152youxi.cn/Article/details/gtnhzafilf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jiagoushi.top/Article/details/gtjkwubfov.html

TS:   type User = { name: string; age: number };
来源：http://dali.yuxming.cn/Article/details/gtxiwpsnzg.html

Java: record User(String name, int age) {}
来源：http://dali.havefunace.top/Article/details/gteoihtlvt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guowangkeji.top/Article/details/gtcdjgcjgi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvfmzngof.html

C#:   record User(string Name, int Age);
来源：http://dali.zhongyouzk.top/Article/details/gtxsvhupxp.html

[G15] 枚举
来源：http://dali.nanxinkj.top/Article/details/gtpqffbxza.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ybcxt.top/Article/details/gtxovuztcn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tianlin.xyz/Article/details/gtkeqnpckf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.quarkkingdee.top/Article/details/gtgilpbawf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gtdxkmpguv.html

Java: enum Color { RED, GREEN }
来源：http://dali.cqqwz.cn/Article/details/gtkldfuhui.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.vqdsnc.cn/Article/details/gtcpntlbrt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.iojbl.cn/Article/details/gtzkyhaydp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuilcuihg.html

[G16] 对象转数组 / 字典
来源：http://dali.tianlin.xyz/Article/details/gtanglqgzf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cucudq.cn/Article/details/gtroozuucd.html

PHP:  get_object_vars($obj);
来源：http://dali.redwolf501.top/Article/details/gtladpdnkp.html

JS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gtfowqiurj.html

TS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtakpgqsok.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cqqwz.cn/Article/details/gtumdsgcuu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangshuangyany.cn/Article/details/gtecdjpadi.html

Ruby: obj.instance_variables
来源：http://dali.jinqigfzy.top/Article/details/gtlkprvvnn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwklzpgry.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsxdochee.html

H. 异常与错误处理
来源：http://dali.shuidangran.top/Article/details/gtpulvitru.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtzkrmgurl.html

[H01] try / catch 基础
来源：http://dali.haohaochexian.top/Article/details/gttivtrgyu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jyoumei.cn/Article/details/gtpntmyrrp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj202588.top/Article/details/gtdcyimzkw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtkbaelhpy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gtuwajshlq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.andypj.xyz/Article/details/gtlbyzoyte.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.andypj.xyz/Article/details/gtpxefaali.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yanxiufei.cn/Article/details/gtbaqrxhxk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jqgfzy.top/Article/details/gtyrzxtgkh.html

[H02] finally / ensure 收尾
来源：http://dali.guannengcc.top/Article/details/gtcnlosouv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.haohaochexian.top/Article/details/gtcdbzsmik.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrcludbe.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtpkzvlwvw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gteyjjvhny.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gtxhtzvhrr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.0kj1m.cn/Article/details/gtpxicebrr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgfzy.top/Article/details/gtpypfcgjr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gthmogqjhe.html

[H03] 主动抛出异常
来源：http://dali.guannengcc.top/Article/details/gtfhqauccm.html

Py:   raise ValueError("错误信息")
来源：http://dali.sufxvd.cn/Article/details/gthxahdvef.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtvaphaimd.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtgnrxvcdm.html

TS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gtvzofafwl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtgmaodwrd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.snrcjt.cn/Article/details/gtxivenktm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yvedp.cn/Article/details/gtjtxaqpmv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtlagzxtzx.html

[H04] 自定义异常类型
来源：http://dali.xylfe.cn/Article/details/gtsjkjvnwi.html

Py:   class MyError(Exception): pass
来源：http://dali.tanke756.top/Article/details/gtlycvtwps.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenzaomai.com/Article/details/gtyqzjwcsx.html

JS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gtjawanhpj.html

TS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gtgabvflcq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangshuangyany.cn/Article/details/gtmzmgmgle.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigufen.top/Article/details/gtqgmveoqg.html


<!-- 参考信息 -->