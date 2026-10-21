代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.havefunace.top/Article/details/gtpjzqghzr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtlicprmwf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtxgdiofnj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtxiqqgpew.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtsktxzsau.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.redwolf501.top/Article/details/gtehbyoxhy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtsknyvnlg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtveftbtzh.html

[E22] 字节长度与字符长度
来源：http://dali.jyoumei.cn/Article/details/gtklcknfxu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj202588.top/Article/details/gtykubjiye.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gtdinezhwd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gtlqivljyh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtiiuynqzb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenlongwang.top/Article/details/gtpkgzahyv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aibaodan.cn/Article/details/gtbfiouvvv.html

Ruby: s.bytesize;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gtdyhcgjrc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xziqi.cn/Article/details/gtwltsyrjl.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtksqtmkbb.html

F. 文件与目录
来源：http://dali.haohaochexian.top/Article/details/gtsrlrusfr.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtfhhqeasq.html

[F01] 读取整个文件
来源：http://dali.redwolf501.top/Article/details/gtkncsgqyr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xziqi.cn/Article/details/gtejykrrsl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtmftcuser.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.wangshuangyany.cn/Article/details/gtbftryojv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gtbiweooga.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfvybmwh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ehwqpu.com/Article/details/gtkrstncio.html

Ruby: File.read("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtbnzdejxl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtioasgtwj.html

[F02] 逐行读取文件
来源：http://dali.cashguo.top/Article/details/gtpxsqnsrk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sweek.top/Article/details/gtdqczqvul.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthnzkmfkm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.snrcjt.cn/Article/details/gthqukzkap.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sxryk.cn/Article/details/gthfeklenx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.aizwys.cn/Article/details/gtubndwblp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.dashuyun.cn/Article/details/gtfgezvrlq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.guannengcc.top/Article/details/gtylgslcgj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.andypj.xyz/Article/details/gtcvkjlmhu.html

[F03] 写入文件（覆盖）
来源：http://dali.redwolf501.top/Article/details/gtpywykrei.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nanxuanxn.top/Article/details/gttalofikk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hammf.cn/Article/details/gtuqsmadyz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yvedp.cn/Article/details/gtbywzfejl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrwnmujts.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.vqdsnc.cn/Article/details/gtxkxftbsl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tianlin.xyz/Article/details/gtfaafpoit.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuanzhike.top/Article/details/gtctxtumis.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gtvgxrmcxh.html

[F04] 追加写入文件
来源：http://dali.ehwqpu.com/Article/details/gtqrvsixpt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxinkj.top/Article/details/gtoeqmzklf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.fengsongda.top/Article/details/gtqfmokriu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dashuyun.cn/Article/details/gtdaupeiet.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xylfe.cn/Article/details/gtloiietjc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.mhx1999.top/Article/details/gthvsifdhq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtjvbnuxep.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yongpay.top/Article/details/gttbgftjvn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sufxvd.cn/Article/details/gtcropmbox.html

[F05] 判断文件或目录是否存在
来源：http://dali.yangfankeji.com/Article/details/gtpnlvjdaf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhgwytgh.html

PHP:  file_exists("a.txt");
来源：http://dali.cashguo.top/Article/details/gtqyjiiotf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtdmctytun.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtcycpwzgt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gttacthisb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daria6918.cn/Article/details/gtnawckwmn.html

Ruby: File.exist?("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtrmjtdgth.html

C#:   File.Exists("a.txt")
来源：http://dali.hammf.cn/Article/details/gtuujbtrca.html

[F06] 删除文件
来源：http://dali.sxryk.cn/Article/details/gtmpjtkmtl.html

Py:   os.remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtmsbnmbfm.html

PHP:  unlink("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtdaskchvx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjxqvsgf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtexqgbmpm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtjkcqolad.html

Go:   os.Remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gtfjwgmzjl.html

Ruby: File.delete("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtlinmygjz.html

C#:   File.Delete("a.txt");
来源：http://dali.yongpay.top/Article/details/gtqyyhwaru.html

[F07] 创建目录（含多级）
来源：http://dali.zdqjudy.top/Article/details/gtehzciwoo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hfpthk.cn/Article/details/gttsbaarkz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.snrcjt.cn/Article/details/gtnptvlpup.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shangyingyoupin.top/Article/details/gtybvtwsdk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dianchejie.cn/Article/details/gtzydpnyeq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ivvv.top/Article/details/gtnfnbcksj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shzxlz.cn/Article/details/gtvvajaoim.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yongpay.top/Article/details/gtvltqqgrx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shangyingyoupin.top/Article/details/gtefzanqqa.html

[F08] 遍历目录
来源：http://dali.yanxiufei.cn/Article/details/gtnopodtks.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.smart0.xyz/Article/details/gtuwgiubyz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nwbrower.top/Article/details/gtxppljozu.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtqvcwpmxl.html

TS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gtczqkcbti.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hywenlv.cn/Article/details/gtfabgwnhs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.mhx1999.top/Article/details/gtlqwkcbql.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtisomaczw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.smart0.xyz/Article/details/gtlzgibtcs.html

[F09] 获取文件大小
来源：http://dali.chenlongwang.top/Article/details/gtjdivpirs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtovgsyelo.html

PHP:  filesize("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtzcmylxqt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gtxsporssa.html

TS:   fs.statSync("a.txt").size
来源：http://dali.redwolf501.top/Article/details/gtpfukifeo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtvtozojre.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tian-w.cn/Article/details/gtijgcevld.html

Ruby: File.size("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtqvhyxfmf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.guannengcc.top/Article/details/gtdprpwtud.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangtech.top/Article/details/gtfahuvvpo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtcslbhtng.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtnymcvuov.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtppotejtn.html

TS:   path.extname("a.txt")
来源：http://dali.fzhhl.top/Article/details/gthycoswot.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shangyingyoupin.top/Article/details/gtvkjaaakb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtdvlcezbz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtbexebzou.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtoglnojms.html

[F11] 复制与移动文件
来源：http://dali.hongshengwenyu.top/Article/details/gtrrhcddwz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gttmuxarse.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.iojbl.cn/Article/details/gtyvtlvdus.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtnjhnivvi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlbwmhopx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.havefunace.top/Article/details/gtdptenzkr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guowangkeji.top/Article/details/gtgchqolhv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtufjowuhm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.mhx1999.top/Article/details/gtcotptesp.html

[F12] CSV 读写
来源：http://dali.zhixingplan.top/Article/details/gtiyqdoggy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cashguo.top/Article/details/gtgfyztgnu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shzxlz.cn/Article/details/gteknpqgtz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jiagoushi.top/Article/details/gtrijrvrot.html

TS:   // 同上
来源：http://dali.chenjidiqi.icu/Article/details/gtpvbdhydl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yonumen.top/Article/details/gtboogrord.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cucudq.cn/Article/details/gtngoqubns.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.guannengcc.top/Article/details/gttbpjiwwx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nanxuanxn.top/Article/details/gtqkojncjj.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtjvoitdhf.html

G. 面向对象
来源：http://dali.bjfxy.top/Article/details/gttevfbelo.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtugroarzp.html

[G01] 定义类
来源：http://dali.yj202588.top/Article/details/gtsqzponnn.html

Py:   class User: pass
来源：http://dali.ybcxt.top/Article/details/gtebbcaitb.html

PHP:  class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtvkqwhbuk.html

JS:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gtmzpnsqqv.html

TS:   class User { name: string = ""; }
来源：http://dali.daxiang520.top/Article/details/gtqgdpuzyi.html

Java: class User {}
来源：http://dali.cashguo.top/Article/details/gtwajfvxme.html

Go:   type User struct { Name string }
来源：http://dali.yj20258.top/Article/details/gtcvqcrukn.html

Ruby: class User; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gttuyyleda.html

C#:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtueblhpgx.html

[G02] 构造函数
来源：http://dali.hammf.cn/Article/details/gtftogxdgp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nanxuanxn.top/Article/details/gtyvjpuzyd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgfzy.top/Article/details/gtxzrlbvpl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hysaishi.cn/Article/details/gtmfmehrms.html

TS:   constructor(public name: string) {}
来源：http://dali.gaohongyu789.top/Article/details/gtmdhggirm.html

Java: User(String name) { this.name = name; }
来源：http://dali.yvedp.cn/Article/details/gtickuyong.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yangfankeji.com/Article/details/gtescztrcp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangdashe.top/Article/details/gtszxzkyey.html

C#:   public User(string name) { Name = name; }
来源：http://dali.snrcjt.cn/Article/details/gthbkzekwo.html

[G03] 实例属性
来源：http://dali.aibaodan.cn/Article/details/gtymtsnigw.html

Py:   self.name = "x"
来源：http://dali.iojbl.cn/Article/details/gtepteghdf.html

PHP:  public string $name = "x";
来源：http://dali.zycfv.cn/Article/details/gtnpartose.html

JS:   this.name = "x";
来源：http://dali.hfpthk.cn/Article/details/gtqycashee.html

TS:   name: string = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gttnkorctd.html

Java: private String name;
来源：http://dali.zhoulong.xyz/Article/details/gtmpbuobsj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvxqvrjzn.html

Ruby: @name = "x"
来源：http://dali.ehwqpu.com/Article/details/gtqroywzah.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shuidangran.top/Article/details/gtazyxdxzy.html

[G04] 定义方法
来源：http://dali.fengsongda.top/Article/details/gtrmjvcegn.html

Py:   def greet(self): return self.name
来源：http://dali.xuetiantiany.cn/Article/details/gtjbvryqlw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gtqbwqxwdu.html

JS:   greet() { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtdeyzlqta.html

TS:   greet(): string { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtvvgmiapi.html

Java: String greet() { return name; }
来源：http://dali.tanke756.top/Article/details/gtgfelhcas.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gtyjwhanna.html

Ruby: def greet; @name; end
来源：http://dali.quarkkingdee.top/Article/details/gtlfdnjnsh.html

C#:   public string Greet() => Name;
来源：http://dali.cheryme.top/Article/details/gtpcotqhmw.html

[G05] 继承
来源：http://dali.sufxvd.cn/Article/details/gtjivfgvxu.html

Py:   class Admin(User): pass
来源：http://dali.guowangkeji.top/Article/details/gtxlnccxqe.html

PHP:  class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtahliprsi.html

JS:   class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtvzbdbjmi.html

TS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtviklzwih.html

Java: class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gthzsvpnfg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.bjfxy.top/Article/details/gtmvxtktrr.html

Ruby: class Admin < User; end
来源：http://dali.fzhhl.top/Article/details/gtmakxcuil.html

C#:   class Admin : User {}
来源：http://dali.zhoulong.xyz/Article/details/gtkktpbszd.html

[G06] 重写方法
来源：http://dali.zhongyouzk.top/Article/details/gtzidxleoa.html

Py:   def greet(self): return "admin"
来源：http://dali.zhongyouzk.top/Article/details/gtbvzlaans.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtlrqldblw.html

JS:   greet() { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtuhzozvnv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtwjufbark.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtgigvycag.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgumpmtpe.html

Ruby: def greet; "admin"; end
来源：http://dali.zdqjudy.top/Article/details/gtgadypxlk.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxuanxn.top/Article/details/gthbdmxfba.html

[G07] 调用父类方法
来源：http://dali.fzhhl.top/Article/details/gtpwivfhcc.html

Py:   super().greet()
来源：http://dali.c1oappe.top/Article/details/gtmlkvgdwq.html

PHP:  parent::greet();
来源：http://dali.cqqwz.cn/Article/details/gtyvzqngaw.html

JS:   super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gthufngdkl.html

TS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gtpqxzpkvp.html

Java: super.greet();
来源：http://dali.ivvv.top/Article/details/gtkkmythjf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jyoumei.cn/Article/details/gtfdndtohf.html

Ruby: super
来源：http://dali.chenjidiqi.icu/Article/details/gtleqzrcyk.html

C#:   base.Greet();
来源：http://dali.pycfn.com/Article/details/gtzioqibwc.html

[G08] 静态方法与属性
来源：http://dali.xuanzx.com/Article/details/gtdvlqxczj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnvpuady.html

PHP:  public static function f() {}
来源：http://dali.jiagoushi.top/Article/details/gtdpwhhnhc.html

JS:   static f() {}
来源：http://dali.daria6918.cn/Article/details/gtuekgaerx.html

TS:   static f(): void {}
来源：http://dali.ybcxt.top/Article/details/gtlfunbsvu.html

Java: static void f() {}
来源：http://dali.cqqwz.cn/Article/details/gtewtctukz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangdashe.top/Article/details/gtprxtkvgr.html

Ruby: def self.f; end
来源：http://dali.yvedp.cn/Article/details/gtyukhfzxa.html

C#:   public static void F() {}
来源：http://dali.sysykeji.top/Article/details/gtjxplqmzo.html

[G09] 接口 / 抽象类
来源：http://dali.quarkkingdee.top/Article/details/gtmbvlvxed.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jiagoushi.top/Article/details/gtvzfugvol.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.andypj.xyz/Article/details/gtnuewgobk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xinyue.icu/Article/details/gtioscjhun.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhiwuduotai.top/Article/details/gtixsrrgjk.html

Java: interface Shape { double area(); }
来源：http://dali.aibaodan.cn/Article/details/gtiggscrue.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yanxiufei.cn/Article/details/gtjffcpsaz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xziqi.cn/Article/details/gtbpejahzi.html

C#:   interface IShape { double Area(); }
来源：http://dali.shzxlz.cn/Article/details/gtrjrrozri.html

[G10] 访问控制
来源：http://dali.fzhhl.top/Article/details/gtjlmbyvtd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dashuyun.cn/Article/details/gtifycfdqn.html

PHP:  public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gttnthjydi.html

JS:   #private 字段；其余公开
来源：http://dali.smart0.xyz/Article/details/gtsvgmhuvt.html

TS:   public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtfjbhrlrj.html

Java: public / protected / private / 默认包级
来源：http://dali.birdmap.top/Article/details/gtmssxyoto.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gaohongyu789.top/Article/details/gtlqszhpve.html

Ruby: public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtocqjqjax.html

C#:   public / protected / private / internal
来源：http://dali.meibo888.top/Article/details/gtwmtoneax.html

[G11] getter / setter
来源：http://dali.kuanghao11.cn/Article/details/gtbkrdcekn.html

Py:   @property 与 @x.setter
来源：http://dali.xylfe.cn/Article/details/gtuyovsuwl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtgibldcex.html

JS:   get name() { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gtoyejbiku.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenzaomai.com/Article/details/gtcysnauga.html

Java: public String getName() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtzjllphvf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gtkuurgsua.html

Ruby: attr_accessor :name
来源：http://dali.havefunace.top/Article/details/gtznpaamtw.html

C#:   public string Name { get; set; }
来源：http://dali.xylfe.cn/Article/details/gtebbrwqyn.html

[G12] 对象转字符串
来源：http://dali.jqgfzy.top/Article/details/gtbzpcsnml.html

Py:   def __str__(self): return self.name
来源：http://dali.cheryme.top/Article/details/gtiqfjrmrk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtaxumcyjq.html

JS:   toString() { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gteaabriuj.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtapwwhbiu.html

Java: @Override public String toString() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gthzdrxklq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gtinyxuamb.html

Ruby: def to_s; @name; end
来源：http://dali.smart0.xyz/Article/details/gtponjjsfk.html

C#:   public override string ToString() => Name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfuxjonp.html

[G13] 判断对象类型
来源：http://dali.mhx1999.top/Article/details/gtuzozrjix.html

Py:   isinstance(u, User)
来源：http://dali.snrcjt.cn/Article/details/gtlwokifxu.html

PHP:  $u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtkqtqqdzu.html

JS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtkbzlgxst.html

TS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gtmdxxcaar.html

Java: u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtcmuyrdcc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dianchejie.cn/Article/details/gtekwxhgrf.html

Ruby: u.is_a?(User)
来源：http://dali.zhengqikj.top/Article/details/gtggajymka.html

C#:   u is User
来源：http://dali.fengsongda.top/Article/details/gtgsfikulc.html

[G14] 数据类 / record
来源：http://dali.c1oappe.top/Article/details/gtjwpgfdsc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zdqjudy.top/Article/details/gtitpmugii.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yuxming.cn/Article/details/gtuyksmzvk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zdqjudy.top/Article/details/gtuvulmajt.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigfzy.top/Article/details/gtqfwnrksf.html

Java: record User(String name, int age) {}
来源：http://dali.sysykeji.top/Article/details/gtxlcmcjkn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.mhx1999.top/Article/details/gttgessprc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yangfankeji.com/Article/details/gtgtxdgmxf.html

C#:   record User(string Name, int Age);
来源：http://dali.vqdsnc.cn/Article/details/gthgrnyobb.html

[G15] 枚举
来源：http://dali.ybcxt.top/Article/details/gtsbxkzjbv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuanzx.com/Article/details/gtmqrhsrzl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cdnleiting.top/Article/details/gtcbnymjvk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.birdmap.top/Article/details/gttvqlhswu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ehwqpu.com/Article/details/gtepqhwqgc.html

Java: enum Color { RED, GREEN }
来源：http://dali.daria6918.cn/Article/details/gtjkslpzya.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkvdkacv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhxffcan.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gtzcrkwjcp.html

[G16] 对象转数组 / 字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gtketlftpx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zdqjudy.top/Article/details/gtctmmdmyk.html

PHP:  get_object_vars($obj);
来源：http://dali.dianchejie.cn/Article/details/gtxbqalajq.html

JS:   Object.entries(obj)
来源：http://dali.yongpay.top/Article/details/gtsgcnkkyx.html

TS:   Object.entries(obj)
来源：http://dali.gzhubu.top/Article/details/gtombwyzfx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtilpirmrb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.meibo888.top/Article/details/gtmzttddtw.html

Ruby: obj.instance_variables
来源：http://dali.gotoacloud.top/Article/details/gtymvljvgu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gtzfupqlbp.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtdfgwootn.html

H. 异常与错误处理
来源：http://dali.tanke756.top/Article/details/gtnfowrtmm.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtoygjdfsh.html

[H01] try / catch 基础
来源：http://dali.quarkkingdee.top/Article/details/gtdoftkdev.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.vqdsnc.cn/Article/details/gtlsgspxnh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tanke756.top/Article/details/gtltpqxkxx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gtchpahfbw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gtlqxumkhc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj202588.top/Article/details/gtbmfnwakm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhixingplan.top/Article/details/gtacrvrjek.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yanxiufei.cn/Article/details/gtbjuexcwn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhixingplan.top/Article/details/gtsdixvdir.html

[H02] finally / ensure 收尾
来源：http://dali.cashguo.top/Article/details/gtvslhdsel.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sweek.top/Article/details/gtfkimdobs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtyqwhdtyo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybaiihho.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtxfsqsogu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtbxurqnlk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258888.top/Article/details/gturigiycw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xylfe.cn/Article/details/gtiivninjs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gteartdxik.html

[H03] 主动抛出异常
来源：http://dali.sufxvd.cn/Article/details/gtdzknqgkf.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxinkj.top/Article/details/gteunhayie.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtlqjcnfzr.html

JS:   throw new Error("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrddmjgm.html


<!-- 参考信息 -->