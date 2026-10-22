代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtyawnbjmy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ppjwa.cn/Article/details/gtgulfuktw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj202588.top/Article/details/gtmzwnwtah.html

Ruby: s.bytesize;  s.length
来源：http://dali.chenlongwang.top/Article/details/gtpglqgufm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sysykeji.top/Article/details/gtpnwcrzjm.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtkoufqvzi.html

F. 文件与目录
来源：http://dali.xuanzx.com/Article/details/gtsteypnfb.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtsziuinnn.html

[F01] 读取整个文件
来源：http://dali.sweek.top/Article/details/gtzepyvwhz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenzaomai.com/Article/details/gtokihlohl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrhijtuj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.havefunace.top/Article/details/gtaaepguxr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hnqzz.top/Article/details/gthygnnbcf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtswdelevc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gogol.net.cn/Article/details/gtblrngulm.html

Ruby: File.read("a.txt")
来源：http://dali.yj20258.top/Article/details/gtjmdahfhb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.316326.xyz/Article/details/gtdxcrhoca.html

[F02] 逐行读取文件
来源：http://dali.yonumen.top/Article/details/gteocrykxw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhiwuduotai.top/Article/details/gtleapqqis.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuetiantiany.cn/Article/details/gtvpqerhij.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtcrlgqzkx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxuxcvxxv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcltnpqkm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.birdmap.top/Article/details/gtxxukzlqc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.haohaochexian.top/Article/details/gtirliknsi.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zycfv.cn/Article/details/gtcbvwmkei.html

[F03] 写入文件（覆盖）
来源：http://dali.wangdashe.top/Article/details/gtrbgxpjsa.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yanxiufei.cn/Article/details/gtvanudjgx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xylfe.cn/Article/details/gteepkltaq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tanke756.top/Article/details/gtumhfowoc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtwamzlpnj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ehwqpu.com/Article/details/gtzcuspuew.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.aizwys.cn/Article/details/gtkqotqdal.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jqgufenzy.top/Article/details/gteqmklwks.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.fzhhl.top/Article/details/gtzevsxqdv.html

[F04] 追加写入文件
来源：http://dali.zycfv.cn/Article/details/gtzrqwxvlh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.guowangkeji.top/Article/details/gtqpjfbvnu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hnqzz.top/Article/details/gtdxfcfqal.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkiwjmrt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gtpmgxjtjw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jianghu66.top/Article/details/gtdgpagtsr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.c1oappe.top/Article/details/gtlxtitjpq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.quarkkingdee.top/Article/details/gthmezvhzs.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.vqdsnc.cn/Article/details/gtaqobrsvu.html

[F05] 判断文件或目录是否存在
来源：http://dali.cucudq.cn/Article/details/gtiichthrn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ydzc1.top/Article/details/gthlferwzu.html

PHP:  file_exists("a.txt");
来源：http://dali.ivvv.top/Article/details/gtwtyizhci.html

JS:   fs.existsSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtubldagzn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtixpjvhpa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtotiracmv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangshuangyany.cn/Article/details/gthkucojea.html

Ruby: File.exist?("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtikkvvcoo.html

C#:   File.Exists("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtsjolbryy.html

[F06] 删除文件
来源：http://dali.zdqjudy.top/Article/details/gthzandion.html

Py:   os.remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gtiuvionwd.html

PHP:  unlink("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtwwslhdsh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtjzkhgzwr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtxbdhdczo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtimcnsitx.html

Go:   os.Remove("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtxsqtbjrp.html

Ruby: File.delete("a.txt")
来源：http://dali.birdmap.top/Article/details/gtpjsvbycu.html

C#:   File.Delete("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtgvhriwoy.html

[F07] 创建目录（含多级）
来源：http://dali.zhixingplan.top/Article/details/gtlzkoeohf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258.top/Article/details/gtdpybpyqq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.wangdashe.top/Article/details/gtmlrrxxbj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gtdapiiywe.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gtpoxyeymq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cucudq.cn/Article/details/gtjucvxnwb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yanxiufei.cn/Article/details/gtavlzqrib.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrlrlaai.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.smart0.xyz/Article/details/gtfkvnsptz.html

[F08] 遍历目录
来源：http://dali.xziqi.cn/Article/details/gtzevporsb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tian-w.cn/Article/details/gteldehpym.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xziqi.cn/Article/details/gtdymmvjbl.html

JS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gtasffbdrt.html

TS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gtivskphne.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gtwewirpkn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhengqikj.top/Article/details/gtytjpowno.html

Ruby: Dir.children("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtouqcriyj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrcxwiler.html

[F09] 获取文件大小
来源：http://dali.zhongyouzk.top/Article/details/gtixtllacg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtpqkanpnx.html

PHP:  filesize("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtnpotnkcg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gtxenfrlvz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gttgrnueoz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtvkhgfjig.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.c1oappe.top/Article/details/gtymvaqksp.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtqyixuect.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenjidiqi.icu/Article/details/gtnmtvxmqq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zycfv.cn/Article/details/gtvfbfaihd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtwjpqcqtp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shuidangran.top/Article/details/gtkyxtkryf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthisrldbo.html

TS:   path.extname("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtemiqxghr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqucpovir.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvzwpjyg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtcflpvogn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtzpmtwnvo.html

[F11] 复制与移动文件
来源：http://dali.nanxuanxn.top/Article/details/gtnyiprrzv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtbjihejlh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gttqniqtqh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtnkireedf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtnccuaucn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aizwys.cn/Article/details/gtfsktnihx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daxiang520.top/Article/details/gtpecmqezx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnswwktcq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gzhubu.top/Article/details/gtyoxbsjwf.html

[F12] CSV 读写
来源：http://dali.jinghuilouyu.cn/Article/details/gtiorstwuh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuetiantiany.cn/Article/details/gtsarpscuy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ehwqpu.com/Article/details/gtmfmiuiqb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shangyingyoupin.top/Article/details/gtnswjithk.html

TS:   // 同上
来源：http://dali.snrcjt.cn/Article/details/gtfmnkhien.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ppjwa.cn/Article/details/gtadsjcwqc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.bjfxy.top/Article/details/gtelheceri.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhengqikj.top/Article/details/gtajaimwxs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xziqi.cn/Article/details/gtukhdukfb.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtmlqfleru.html

G. 面向对象
来源：http://dali.nwbrower.top/Article/details/gtvacuwcxu.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gthsdallyl.html

[G01] 定义类
来源：http://dali.ivvv.top/Article/details/gtwmflqqxq.html

Py:   class User: pass
来源：http://dali.jiagoushi.top/Article/details/gtzxyarorm.html

PHP:  class User {}
来源：http://dali.cdnleiting.top/Article/details/gtsqkmwvxt.html

JS:   class User {}
来源：http://dali.iojbl.cn/Article/details/gtxdicflgt.html

TS:   class User { name: string = ""; }
来源：http://dali.yvedp.cn/Article/details/gtytthgohx.html

Java: class User {}
来源：http://dali.ppjwa.cn/Article/details/gtyxotqweu.html

Go:   type User struct { Name string }
来源：http://dali.shuidangran.top/Article/details/gthhcjgspq.html

Ruby: class User; end
来源：http://dali.cheryme.top/Article/details/gtplatmjgd.html

C#:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gtyhbrhekl.html

[G02] 构造函数
来源：http://dali.jqgufenzy.top/Article/details/gtpwuqlkeq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.pengpengdd.cyou/Article/details/gtcsaylfjm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jyoumei.cn/Article/details/gtlfpdtacg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.svipenyu.cn/Article/details/gtmqxdeyqw.html

TS:   constructor(public name: string) {}
来源：http://dali.fzhhl.top/Article/details/gtoobkgvjt.html

Java: User(String name) { this.name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gtnztmwpwj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhixingplan.top/Article/details/gtvtoomqva.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ybcxt.top/Article/details/gtmhicrtaq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxinkj.top/Article/details/gtdntnkikq.html

[G03] 实例属性
来源：http://dali.yongpay.top/Article/details/gtynnzfhpx.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gtfcarhfvq.html

PHP:  public string $name = "x";
来源：http://dali.ppjwa.cn/Article/details/gtrkavwhek.html

JS:   this.name = "x";
来源：http://dali.daxiang520.top/Article/details/gtgwmhattx.html

TS:   name: string = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtzjbsgcbh.html

Java: private String name;
来源：http://dali.0kj1m.cn/Article/details/gtspxxxwxy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.9152youxi.cn/Article/details/gtozmnwnlw.html

Ruby: @name = "x"
来源：http://dali.quarkkingdee.top/Article/details/gtrzvjoals.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gzhubu.top/Article/details/gttvdlpode.html

[G04] 定义方法
来源：http://dali.9152youxi.cn/Article/details/gtqhqhgtfo.html

Py:   def greet(self): return self.name
来源：http://dali.cqqwz.cn/Article/details/gtdhjlllri.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gtuwjyoigo.html

JS:   greet() { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtmpvosymh.html

TS:   greet(): string { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtkvvgbsje.html

Java: String greet() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxhgzbot.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gtcnqghgbn.html

Ruby: def greet; @name; end
来源：http://dali.zycfv.cn/Article/details/gtuortpurl.html

C#:   public string Greet() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gthrwmxlxc.html

[G05] 继承
来源：http://dali.jyoumei.cn/Article/details/gtsiojyljk.html

Py:   class Admin(User): pass
来源：http://dali.gzhubu.top/Article/details/gtkhlgmcvp.html

PHP:  class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtmhdzzcvy.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtatnfylgf.html

TS:   class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtxeyohrsf.html

Java: class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtngtjeelk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhoulong.xyz/Article/details/gtpbaospzc.html

Ruby: class Admin < User; end
来源：http://dali.zycfv.cn/Article/details/gtvmmydqoc.html

C#:   class Admin : User {}
来源：http://dali.nanxinkj.top/Article/details/gtqiclaohj.html

[G06] 重写方法
来源：http://dali.hnxiangtu.top/Article/details/gtpqoomvdj.html

Py:   def greet(self): return "admin"
来源：http://dali.9152youxi.cn/Article/details/gttthpxsas.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtgkqelvpq.html

JS:   greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtxucboodt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtyegirvte.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gtcimgtshd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.andypj.xyz/Article/details/gtxwwuwlzg.html

Ruby: def greet; "admin"; end
来源：http://dali.shzxlz.cn/Article/details/gtpduiridh.html

C#:   public override string Greet() => "admin";
来源：http://dali.dashuyun.cn/Article/details/gtbterlawh.html

[G07] 调用父类方法
来源：http://dali.zhongyouzk.top/Article/details/gtxinmjuif.html

Py:   super().greet()
来源：http://dali.yueranfly.top/Article/details/gtnjasdwyh.html

PHP:  parent::greet();
来源：http://dali.0kj1m.cn/Article/details/gtbnwaoksw.html

JS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gtozszqtjm.html

TS:   super.greet();
来源：http://dali.snrcjt.cn/Article/details/gtqjsghcvs.html

Java: super.greet();
来源：http://dali.hfpthk.cn/Article/details/gtunoghrzv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvsbjjang.html

Ruby: super
来源：http://dali.9152youxi.cn/Article/details/gtgungynyw.html

C#:   base.Greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtqlmtgqpb.html

[G08] 静态方法与属性
来源：http://dali.daria6918.cn/Article/details/gtzhocczwg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ppjwa.cn/Article/details/gtgevlsfao.html

PHP:  public static function f() {}
来源：http://dali.pycfn.com/Article/details/gtrmfwmyoj.html

JS:   static f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtqdbltiin.html

TS:   static f(): void {}
来源：http://dali.fzhhl.top/Article/details/gtwbnvidoo.html

Java: static void f() {}
来源：http://dali.havefunace.top/Article/details/gtcnxmyolc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sufxvd.cn/Article/details/gtrfgdiika.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhhbnrjz.html

C#:   public static void F() {}
来源：http://dali.zhixingplan.top/Article/details/gtoduhcjau.html

[G09] 接口 / 抽象类
来源：http://dali.xziqi.cn/Article/details/gtbfytnnor.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.c1oappe.top/Article/details/gtswnqrxdc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.0kj1m.cn/Article/details/gtemxyujep.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.dashuyun.cn/Article/details/gtjznepmsn.html

TS:   interface Shape { area(): number; }
来源：http://dali.guowangkeji.top/Article/details/gtwyepudgb.html

Java: interface Shape { double area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttucjztbp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shangyingyoupin.top/Article/details/gtivjplhrs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.svipenyu.cn/Article/details/gtjgnovtbh.html

C#:   interface IShape { double Area(); }
来源：http://dali.xinyue.icu/Article/details/gtjungtwjz.html

[G10] 访问控制
来源：http://dali.fzhhl.top/Article/details/gtpizlxhpk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gaohongyu789.top/Article/details/gtpabdiepe.html

PHP:  public / protected / private
来源：http://dali.yj20258.top/Article/details/gtvulkidiy.html

JS:   #private 字段；其余公开
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvdtrbth.html

TS:   public / protected / private
来源：http://dali.pycfn.com/Article/details/gtgpzmpqcj.html

Java: public / protected / private / 默认包级
来源：http://dali.guowangkeji.top/Article/details/gtzmnwffao.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gaohongyu789.top/Article/details/gtwceqrnza.html

Ruby: public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gtfhtbrdkt.html

C#:   public / protected / private / internal
来源：http://dali.gaohongyu789.top/Article/details/gtpuefthje.html

[G11] getter / setter
来源：http://dali.aibaodan.cn/Article/details/gtmlbyprcu.html

Py:   @property 与 @x.setter
来源：http://dali.gogol.net.cn/Article/details/gtgorinkkg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtudhnlaqe.html

JS:   get name() { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gtgnnlfpdo.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gtjrohmpcs.html

Java: public String getName() { return name; }
来源：http://dali.yvedp.cn/Article/details/gtqmazdxjp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gtnqboqzuh.html

Ruby: attr_accessor :name
来源：http://dali.ydzc1.top/Article/details/gtxwdvubrp.html

C#:   public string Name { get; set; }
来源：http://dali.zhongyouzk.top/Article/details/gtavsvgfej.html

[G12] 对象转字符串
来源：http://dali.hammf.cn/Article/details/gtsjaqhdqt.html

Py:   def __str__(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gtilliabmg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtevjmzgcb.html

JS:   toString() { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtonpfqxpa.html

TS:   toString(): string { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtswjgupbq.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtxxjdhtus.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gtnolggowe.html

Ruby: def to_s; @name; end
来源：http://dali.jyoumei.cn/Article/details/gtqaessnvl.html

C#:   public override string ToString() => Name;
来源：http://dali.ybcxt.top/Article/details/gtyohtjxmv.html

[G13] 判断对象类型
来源：http://dali.zhixingplan.top/Article/details/gtjkixzrwj.html

Py:   isinstance(u, User)
来源：http://dali.feifeiyinyue.top/Article/details/gtsnuqdijo.html

PHP:  $u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtsyfhvgwc.html

JS:   u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gttqfplkfc.html

TS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtlgielthd.html

Java: u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtfpuefchd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.guowangkeji.top/Article/details/gtibdoqlme.html

Ruby: u.is_a?(User)
来源：http://dali.ydzc1.top/Article/details/gtkrfskwvf.html

C#:   u is User
来源：http://dali.yanxiufei.cn/Article/details/gtvhepocxl.html

[G14] 数据类 / record
来源：http://dali.pengpengdd.cyou/Article/details/gtksuvcvtf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gaohongyu789.top/Article/details/gtppikszdf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ehwqpu.com/Article/details/gtkjwtqonc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuetiantiany.cn/Article/details/gtozpakwkn.html

TS:   type User = { name: string; age: number };
来源：http://dali.gaohongyu789.top/Article/details/gtwqigcmlm.html

Java: record User(String name, int age) {}
来源：http://dali.svipenyu.cn/Article/details/gtdqqmxbpo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ybcxt.top/Article/details/gtfjyeblta.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvyrnxfmy.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigufen.top/Article/details/gthsuqcvab.html

[G15] 枚举
来源：http://dali.316326.xyz/Article/details/gtphqgelyp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sufxvd.cn/Article/details/gtqibinyyt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.pycfn.com/Article/details/gtwzsfmgcu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ehwqpu.com/Article/details/gtvhmtqxdc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gtnxjcplij.html

Java: enum Color { RED, GREEN }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwsfkbnrg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tian-w.cn/Article/details/gtilfdjnzt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.kuanghao11.cn/Article/details/gtubgkulih.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gtomuwkbmh.html

[G16] 对象转数组 / 字典
来源：http://dali.guannengcc.top/Article/details/gtkeevmtvt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hfpthk.cn/Article/details/gtyulqrbkt.html

PHP:  get_object_vars($obj);
来源：http://dali.jianghu66.top/Article/details/gtvcjdguwt.html

JS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gtppwunefh.html

TS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtqopkipco.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fengsongda.top/Article/details/gtistaorld.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbyldzdfq.html

Ruby: obj.instance_variables
来源：http://dali.yueranfly.top/Article/details/gtrxncyljp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xylfe.cn/Article/details/gtrvuqwblg.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gthahmtjmb.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gtrdogsjhe.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtvnfloclp.html

[H01] try / catch 基础
来源：http://dali.tianlin.xyz/Article/details/gtudcknjsa.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xylfe.cn/Article/details/gtqzeqtxax.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ppjwa.cn/Article/details/gtgqdlfjhe.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmkawtgw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gtrxyyfonc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.iojbl.cn/Article/details/gteveykvkm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.316326.xyz/Article/details/gtwxlahssl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cashguo.top/Article/details/gtkledovvx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jianghu66.top/Article/details/gthvoiutos.html

[H02] finally / ensure 收尾
来源：http://dali.zhongyouzk.top/Article/details/gtylxdamut.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyydpcsqp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtckberqks.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtsbmazrzu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtraaawvqi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtuypbpipn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.pycfn.com/Article/details/gtbsbkttzw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.9152youxi.cn/Article/details/gtmbioxcqv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtlullmmkd.html

[H03] 主动抛出异常
来源：http://dali.0kj1m.cn/Article/details/gtegghmhkj.html

Py:   raise ValueError("错误信息")
来源：http://dali.9152youxi.cn/Article/details/gtrfdddnnw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtvuuocenb.html

JS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtbwrdfcrq.html

TS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsibvxhvs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtxumifkwq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yueranfly.top/Article/details/gtucqqngim.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jqgfzy.top/Article/details/gtoiathxmk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtdnyfqrvp.html

[H04] 自定义异常类型
来源：http://dali.yvedp.cn/Article/details/gticcaseay.html

Py:   class MyError(Exception): pass
来源：http://dali.dianchejie.cn/Article/details/gtrcwajqoo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gtksjmqkeo.html

JS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gtcqgzzcvy.html

TS:   class MyError extends Error {}
来源：http://dali.yj20258.top/Article/details/gtauhlxntc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hnqzz.top/Article/details/gtyohtkqib.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.bjfxy.top/Article/details/gtbmnhuymj.html


<!-- 参考信息 -->