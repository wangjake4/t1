代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.mhx1999.top/Article/details/gtvwctjndn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.guannengcc.top/Article/details/gtyenxdhnb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gtfnkqlzbw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hywenlv.cn/Article/details/gtpcdjdgkz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtcapknwmc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gtodivckzp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gtoatblzkp.html

Ruby: s.bytesize;  s.length
来源：http://dali.gzhubu.top/Article/details/gtuvsvtovf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhiwuduotai.top/Article/details/gtdbyauebw.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtfsdiislj.html

F. 文件与目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcinffte.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtwrxuuzbz.html

[F01] 读取整个文件
来源：http://dali.kuanghao11.cn/Article/details/gtjlpdeivz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhixingplan.top/Article/details/gtxagueycf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtkizcftkc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.aibaodan.cn/Article/details/gtkgyzxiro.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gtsxsbayag.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxjviivt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sxryk.cn/Article/details/gtqmluxlaa.html

Ruby: File.read("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtuilumajp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cashguo.top/Article/details/gtlrvcqloz.html

[F02] 逐行读取文件
来源：http://dali.guowangkeji.top/Article/details/gtkweruglr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jianghu66.top/Article/details/gtrvvvlkwx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zdqjudy.top/Article/details/gtldgjofor.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gthbduyiah.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.9152youxi.cn/Article/details/gtpdikmafr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj202588.top/Article/details/gtuglkedwc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.316326.xyz/Article/details/gtjuirtlbu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafaioboe.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj20258.top/Article/details/gtkrinrmof.html

[F03] 写入文件（覆盖）
来源：http://dali.vqdsnc.cn/Article/details/gtsjjyhzyj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xylfe.cn/Article/details/gtlxcupmzw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.mhx1999.top/Article/details/gtwyrkedka.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gtkkdcasjf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtsfkhlbpu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigfzy.top/Article/details/gtverwjxsy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ehwqpu.com/Article/details/gtwrrdbvvt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hysaishi.cn/Article/details/gtglebcagn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gtmrnkubds.html

[F04] 追加写入文件
来源：http://dali.yvedp.cn/Article/details/gtkrnvgowd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gttwbcswsf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtteibvopv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.bjfxy.top/Article/details/gtvdvvaxpn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtnhfukjvk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.haohaochexian.top/Article/details/gtbggoqrtc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.iojbl.cn/Article/details/gtohsyxcyq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yvedp.cn/Article/details/gtfmingvzi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yongpay.top/Article/details/gtuucdyhpu.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj20258.top/Article/details/gtjitwziim.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guannengcc.top/Article/details/gtlbyxkqeb.html

PHP:  file_exists("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtnsvhhwiq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gttscctkut.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtgrnbqhec.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtjfvmfddk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daria6918.cn/Article/details/gtymuhadyt.html

Ruby: File.exist?("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtdcwzosrw.html

C#:   File.Exists("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtrlwchpjh.html

[F06] 删除文件
来源：http://dali.yuanzhike.top/Article/details/gtavpebika.html

Py:   os.remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gtyaozapts.html

PHP:  unlink("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtfybmerqh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtjmezetsd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtquzdgygf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtqeojwcpr.html

Go:   os.Remove("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtvraygspu.html

Ruby: File.delete("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtqabtazrf.html

C#:   File.Delete("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtwiftdwty.html

[F07] 创建目录（含多级）
来源：http://dali.tanke756.top/Article/details/gthvnhvtuo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shuidangran.top/Article/details/gtbubftxzw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.vqdsnc.cn/Article/details/gttdnohlfb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbzxairr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dianchejie.cn/Article/details/gtyeribbyr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zycfv.cn/Article/details/gtuzqufogp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hammf.cn/Article/details/gtzaczuhao.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhixingplan.top/Article/details/gtpuyzeztb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.fengsongda.top/Article/details/gtvtckwlso.html

[F08] 遍历目录
来源：http://dali.sufxvd.cn/Article/details/gtwmxtdgeu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenzaomai.com/Article/details/gtxwgjhcfy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xziqi.cn/Article/details/gtcnyhndbw.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj20258888.top/Article/details/gtdzfkruhk.html

TS:   fs.readdirSync("dir")
来源：http://dali.ivvv.top/Article/details/gtemgysquh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yanxiufei.cn/Article/details/gtjplyjvov.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.andypj.xyz/Article/details/gtkskymjco.html

Ruby: Dir.children("dir")
来源：http://dali.guannengcc.top/Article/details/gtgqozfjuq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrbtkter.html

[F09] 获取文件大小
来源：http://dali.cqqwz.cn/Article/details/gtojhyjgou.html

Py:   os.path.getsize("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtazzwtibz.html

PHP:  filesize("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gthycopsqv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cdnleiting.top/Article/details/gtrwblvsos.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gttzcrmjnh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtjbstmmtk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xziqi.cn/Article/details/gtryrwiguv.html

Ruby: File.size("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtohhsrbvj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuetiantiany.cn/Article/details/gtqseagjhr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.wangshuangyany.cn/Article/details/gtsrjelhxv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gteqizkiyw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtqtdklkda.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtlnfiodze.html

TS:   path.extname("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtaquvpram.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenjidiqi.icu/Article/details/gtpanxhcmk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtamiwcslw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gthjhqixgs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtqdbqhiqb.html

[F11] 复制与移动文件
来源：http://dali.yonumen.top/Article/details/gtlanzgnpd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtfidshrej.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.meibo888.top/Article/details/gtjqeuuufz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtdeizfrab.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmuwdzyo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zdqjudy.top/Article/details/gtnlkpvvuy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jyoumei.cn/Article/details/gtabpmrplz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtwjnwsfkq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.feifeiyinyue.top/Article/details/gtkraxedtt.html

[F12] CSV 读写
来源：http://dali.jyoumei.cn/Article/details/gtfzyylwit.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gotoacloud.top/Article/details/gtgguezisz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnqzz.top/Article/details/gtsikvurwz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yvedp.cn/Article/details/gtdgbdptpl.html

TS:   // 同上
来源：http://dali.cheryme.top/Article/details/gtjdpleodi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hysaishi.cn/Article/details/gtedirfxpr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sufxvd.cn/Article/details/gtpcrnkovg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dianchejie.cn/Article/details/gteojiqgtk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ybcxt.top/Article/details/gthnoxwore.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtulhfzslx.html

G. 面向对象
来源：http://dali.wangdashe.top/Article/details/gtukwupkqo.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfufumilk.html

[G01] 定义类
来源：http://dali.zhiwuduotai.top/Article/details/gtneqksplo.html

Py:   class User: pass
来源：http://dali.smart0.xyz/Article/details/gtpcbgqwsr.html

PHP:  class User {}
来源：http://dali.havefunace.top/Article/details/gtpmctnhks.html

JS:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtkylabnwl.html

TS:   class User { name: string = ""; }
来源：http://dali.hysaishi.cn/Article/details/gtxktluivf.html

Java: class User {}
来源：http://dali.jinqigufen.top/Article/details/gtzejbyjpw.html

Go:   type User struct { Name string }
来源：http://dali.yj202588.top/Article/details/gtuitxumec.html

Ruby: class User; end
来源：http://dali.sxryk.cn/Article/details/gtqmljlcsk.html

C#:   class User {}
来源：http://dali.jianghu66.top/Article/details/gtqhpsaxcv.html

[G02] 构造函数
来源：http://dali.chenlongwang.top/Article/details/gttwvoevca.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tanke756.top/Article/details/gtnpszpmhm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj202588.top/Article/details/gtdenqbyfa.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gtakjtneyh.html

TS:   constructor(public name: string) {}
来源：http://dali.havefunace.top/Article/details/gtjkpuqjis.html

Java: User(String name) { this.name = name; }
来源：http://dali.c1oappe.top/Article/details/gtfricxhav.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guowangkeji.top/Article/details/gtyvzpdzjw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhongyouzk.top/Article/details/gtdfqhrexq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtlsmizmar.html

[G03] 实例属性
来源：http://dali.mhx1999.top/Article/details/gtuoquvrjp.html

Py:   self.name = "x"
来源：http://dali.cdnleiting.top/Article/details/gtrpirajjk.html

PHP:  public string $name = "x";
来源：http://dali.gzhubu.top/Article/details/gtvhuipgqc.html

JS:   this.name = "x";
来源：http://dali.cucudq.cn/Article/details/gtmzdyyebf.html

TS:   name: string = "x";
来源：http://dali.yonumen.top/Article/details/gtodmowmxj.html

Java: private String name;
来源：http://dali.gzhubu.top/Article/details/gthuwmznpk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnxiangtu.top/Article/details/gtnzzhbdta.html

Ruby: @name = "x"
来源：http://dali.hywenlv.cn/Article/details/gtismiryql.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj202588.top/Article/details/gtjouabqrd.html

[G04] 定义方法
来源：http://dali.yj20258.top/Article/details/gtifxsaqql.html

Py:   def greet(self): return self.name
来源：http://dali.xuetiantiany.cn/Article/details/gtvwzidwza.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gtbwlxiqwn.html

JS:   greet() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtsojiriya.html

TS:   greet(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtjebeozig.html

Java: String greet() { return name; }
来源：http://dali.wangdashe.top/Article/details/gtkprdkxhu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqepxlleb.html

Ruby: def greet; @name; end
来源：http://dali.guannengcc.top/Article/details/gtxifngeyv.html

C#:   public string Greet() => Name;
来源：http://dali.ppjwa.cn/Article/details/gtggcsxwlo.html

[G05] 继承
来源：http://dali.cucudq.cn/Article/details/gtzizncrrm.html

Py:   class Admin(User): pass
来源：http://dali.sysykeji.top/Article/details/gtgjshbkfg.html

PHP:  class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtggpoymfi.html

JS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtcmdikpoz.html

TS:   class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtashzgncu.html

Java: class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtlrsvanlb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhixingplan.top/Article/details/gtadrbutcq.html

Ruby: class Admin < User; end
来源：http://dali.9152youxi.cn/Article/details/gtutvlxexx.html

C#:   class Admin : User {}
来源：http://dali.havefunace.top/Article/details/gtlcoxldsx.html

[G06] 重写方法
来源：http://dali.ybcxt.top/Article/details/gtjldxmupc.html

Py:   def greet(self): return "admin"
来源：http://dali.tian-w.cn/Article/details/gttykvxmiz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtpcowpehc.html

JS:   greet() { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtaxwxnyxg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtzcfystnb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtvkgbrufy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yuxming.cn/Article/details/gtgwyqizph.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbpptuhbh.html

C#:   public override string Greet() => "admin";
来源：http://dali.shzxlz.cn/Article/details/gtykodggbd.html

[G07] 调用父类方法
来源：http://dali.dashuyun.cn/Article/details/gtkzcbjode.html

Py:   super().greet()
来源：http://dali.kuanghao11.cn/Article/details/gthvvrcsis.html

PHP:  parent::greet();
来源：http://dali.nwbrower.top/Article/details/gtzmoirdkd.html

JS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gtkzjouqwl.html

TS:   super.greet();
来源：http://dali.yonumen.top/Article/details/gtegeyjpsh.html

Java: super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrrizrhp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tian-w.cn/Article/details/gtmcegpfgx.html

Ruby: super
来源：http://dali.c1oappe.top/Article/details/gtkrtfspsn.html

C#:   base.Greet();
来源：http://dali.yonumen.top/Article/details/gtxydzxjca.html

[G08] 静态方法与属性
来源：http://dali.wangdashe.top/Article/details/gtnbkfhopt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.c1oappe.top/Article/details/gtoaekaujy.html

PHP:  public static function f() {}
来源：http://dali.jiagoushi.top/Article/details/gtdzxibrmq.html

JS:   static f() {}
来源：http://dali.jianghu66.top/Article/details/gtvodcyvwc.html

TS:   static f(): void {}
来源：http://dali.yvedp.cn/Article/details/gtrrjacbrg.html

Java: static void f() {}
来源：http://dali.meibo888.top/Article/details/gtrizssoba.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuanzx.com/Article/details/gtdwgyxbks.html

Ruby: def self.f; end
来源：http://dali.shangyingyoupin.top/Article/details/gtdnbncasx.html

C#:   public static void F() {}
来源：http://dali.cheryme.top/Article/details/gtnefhcuzd.html

[G09] 接口 / 抽象类
来源：http://dali.yuanzhike.top/Article/details/gtunueannp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.316326.xyz/Article/details/gtukplwefp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnqzz.top/Article/details/gtwckvvaxf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daria6918.cn/Article/details/gtxudiehuo.html

TS:   interface Shape { area(): number; }
来源：http://dali.hnqzz.top/Article/details/gtaixgabgo.html

Java: interface Shape { double area(); }
来源：http://dali.smart0.xyz/Article/details/gtfgrmrolr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cucudq.cn/Article/details/gttvdgqvun.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtyokzfxay.html

C#:   interface IShape { double Area(); }
来源：http://dali.hfpthk.cn/Article/details/gterfjgtil.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gtvdjypdhx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xziqi.cn/Article/details/gtnouoldgb.html

PHP:  public / protected / private
来源：http://dali.316326.xyz/Article/details/gtxtarctyi.html

JS:   #private 字段；其余公开
来源：http://dali.xuanzx.com/Article/details/gtgbeyolse.html

TS:   public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gtojrqtzrk.html

Java: public / protected / private / 默认包级
来源：http://dali.gaohongyu789.top/Article/details/gtgrukkzpd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aizwys.cn/Article/details/gtmpgrbnmn.html

Ruby: public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtexixxeul.html

C#:   public / protected / private / internal
来源：http://dali.yj202588.top/Article/details/gtdnwheipa.html

[G11] getter / setter
来源：http://dali.snrcjt.cn/Article/details/gtsquvmygi.html

Py:   @property 与 @x.setter
来源：http://dali.hfpthk.cn/Article/details/gtaqgtfwvz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtetltbitm.html

JS:   get name() { return this._name; }
来源：http://dali.snrcjt.cn/Article/details/gtdqhuccrl.html

TS:   get name(): string { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gtcztidxpr.html

Java: public String getName() { return name; }
来源：http://dali.pycfn.com/Article/details/gtobigtjpj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtdzaogkev.html

Ruby: attr_accessor :name
来源：http://dali.quarkkingdee.top/Article/details/gtremlsgci.html

C#:   public string Name { get; set; }
来源：http://dali.xuanzx.com/Article/details/gtufkndebf.html

[G12] 对象转字符串
来源：http://dali.smart0.xyz/Article/details/gtywskbgpo.html

Py:   def __str__(self): return self.name
来源：http://dali.ydzc1.top/Article/details/gtlwqptfth.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gthhrvjzlo.html

JS:   toString() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtkcabwvjh.html

TS:   toString(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gttevqreot.html

Java: @Override public String toString() { return name; }
来源：http://dali.yonumen.top/Article/details/gtsdtawkwv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtkphiqvhd.html

Ruby: def to_s; @name; end
来源：http://dali.cheryme.top/Article/details/gtcwoxtqkl.html

C#:   public override string ToString() => Name;
来源：http://dali.iojbl.cn/Article/details/gtbzjolbbh.html

[G13] 判断对象类型
来源：http://dali.smart0.xyz/Article/details/gttlkttdck.html

Py:   isinstance(u, User)
来源：http://dali.yvedp.cn/Article/details/gtzlvkhqrn.html

PHP:  $u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtxysdxadk.html

JS:   u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtirfqaqfv.html

TS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtcknhywdy.html

Java: u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtlgjyjpvn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aibaodan.cn/Article/details/gtuigtfjkk.html

Ruby: u.is_a?(User)
来源：http://dali.birdmap.top/Article/details/gtkvezakvw.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gtwonrsinl.html

[G14] 数据类 / record
来源：http://dali.xinyue.icu/Article/details/gtlsypultx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jiagoushi.top/Article/details/gtuwnmjcpg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigufen.top/Article/details/gtljqylejz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.dianchejie.cn/Article/details/gtlqnafdgq.html

TS:   type User = { name: string; age: number };
来源：http://dali.nanxuanxn.top/Article/details/gtzogrjhqe.html

Java: record User(String name, int age) {}
来源：http://dali.nanxuanxn.top/Article/details/gtrzxwgtzb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pengpengdd.cyou/Article/details/gtefnsefyw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gtjloowugb.html

C#:   record User(string Name, int Age);
来源：http://dali.bjfxy.top/Article/details/gtqevzuzdy.html

[G15] 枚举
来源：http://dali.yueranfly.top/Article/details/gtcboaymbz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yuxming.cn/Article/details/gtolgfbejs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xinyue.icu/Article/details/gtkpbzwjlm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shzxlz.cn/Article/details/gtxjydpzul.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnxiangtu.top/Article/details/gttuevawhb.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangshuangyany.cn/Article/details/gtfhvgckhp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cqqwz.cn/Article/details/gtftrwsnta.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ppjwa.cn/Article/details/gtikxplkuu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258888.top/Article/details/gtgnnyzqip.html

[G16] 对象转数组 / 字典
来源：http://dali.tanke756.top/Article/details/gtxyezxuei.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuxming.cn/Article/details/gtzmakklgg.html

PHP:  get_object_vars($obj);
来源：http://dali.jianghu66.top/Article/details/gtaafzdbbs.html

JS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gtlyzdcrpz.html

TS:   Object.entries(obj)
来源：http://dali.aizwys.cn/Article/details/gtisxjqanz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tianlin.xyz/Article/details/gthbfkpiwq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj202588.top/Article/details/gtuvftyqgc.html

Ruby: obj.instance_variables
来源：http://dali.sweek.top/Article/details/gtwhjiaigi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gtgljkcnom.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtfarzumiv.html

H. 异常与错误处理
来源：http://dali.hywenlv.cn/Article/details/gtgbvmejaa.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxgwfqea.html

[H01] try / catch 基础
来源：http://dali.ppjwa.cn/Article/details/gttjoxremt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvyzajgjk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigfzy.top/Article/details/gtwjwlpsjx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.quarkkingdee.top/Article/details/gtcwxhpmdq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gtqolmrdug.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.feifeiyinyue.top/Article/details/gtrxpbhagw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xziqi.cn/Article/details/gtbqpmwywu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.pengpengdd.cyou/Article/details/gtpbjkmcgy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cheryme.top/Article/details/gtbcaizqhu.html

[H02] finally / ensure 收尾
来源：http://dali.0kj1m.cn/Article/details/gtjvfaosmn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hammf.cn/Article/details/gtuquejwai.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtefxakqbs.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtbajbvvsb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtfeljxvgr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtptctulbj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gotoacloud.top/Article/details/gtkncardwf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ybcxt.top/Article/details/gthygaaexy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtnznrtxqi.html

[H03] 主动抛出异常
来源：http://dali.yvedp.cn/Article/details/gtmgxlmzkn.html

Py:   raise ValueError("错误信息")
来源：http://dali.fzhhl.top/Article/details/gtlqhyqume.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtwabhnvme.html

JS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaiahcthv.html

TS:   throw new Error("错误信息");
来源：http://dali.cashguo.top/Article/details/gtnrcosxju.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtervisbpz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zycfv.cn/Article/details/gtjtmzhlvv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yangfankeji.com/Article/details/gthnldpqmk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtllojfecr.html

[H04] 自定义异常类型
来源：http://dali.zhoulong.xyz/Article/details/gtblncacld.html

Py:   class MyError(Exception): pass
来源：http://dali.316326.xyz/Article/details/gtgtzrzakr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangshuangyany.cn/Article/details/gtzwwkdzsf.html


<!-- 参考信息 -->