代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdoxongw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hfpthk.cn/Article/details/gtxdzwqdgx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gtmhaiwxar.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gtsscdjkaf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtnearumrd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.smart0.xyz/Article/details/gtoflwaimg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinqigufen.top/Article/details/gthkgqeiol.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtvlayxhlf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shuidangran.top/Article/details/gtdvezwcaf.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtdkikhtqd.html

F. 文件与目录
来源：http://dali.aibaodan.cn/Article/details/gtaozantqf.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtnumakgzd.html

[F01] 读取整个文件
来源：http://dali.cucudq.cn/Article/details/gtlkkofkav.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.mhx1999.top/Article/details/gtolarotnc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtbzhkysez.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenjidiqi.icu/Article/details/gtgvydxtgq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gtsbgidgtf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtnkynjdwz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgufenzy.top/Article/details/gtfftfrtrx.html

Ruby: File.read("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtayeojylu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtogbzszrf.html

[F02] 逐行读取文件
来源：http://dali.aibaodan.cn/Article/details/gtckjqxjgo.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gtxtlbwdsu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jqgfzy.top/Article/details/gtuwcpqgaw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gtwcqpbgrs.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yongpay.top/Article/details/gtzxuqvclu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gtikqdpkkz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zycfv.cn/Article/details/gtxbvnlyjd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhoulong.xyz/Article/details/gtcwcgbaqe.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cqqwz.cn/Article/details/gtddsemtcd.html

[F03] 写入文件（覆盖）
来源：http://dali.feifeiyinyue.top/Article/details/gtyemmhlxk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhoulong.xyz/Article/details/gtsmxrcdto.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhoulong.xyz/Article/details/gtemgquigp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gtguokkavr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtbdjsicis.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.meibo888.top/Article/details/gtvbfglhtd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shzxlz.cn/Article/details/gtfvopqhhj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yanxiufei.cn/Article/details/gtdnvhnrsx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gtqjretyus.html

[F04] 追加写入文件
来源：http://dali.redwolf501.top/Article/details/gttdkpljyr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jyoumei.cn/Article/details/gtqcylfzoi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.smart0.xyz/Article/details/gtgcofnqgl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cqqwz.cn/Article/details/gtginxjuyy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.vqdsnc.cn/Article/details/gttjsrebtk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangshuangyany.cn/Article/details/gtzzclwnrg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.andypj.xyz/Article/details/gtjftzgimt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shangyingyoupin.top/Article/details/gtnlwsybsw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.guannengcc.top/Article/details/gtzeyrroil.html

[F05] 判断文件或目录是否存在
来源：http://dali.hywenlv.cn/Article/details/gtrtigpuob.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxinkj.top/Article/details/gttxwdmnrt.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtmeqpqbnv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtliclcshe.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtpiqlcfvt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gtnkdoosmz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.guannengcc.top/Article/details/gtxsqfxsrg.html

Ruby: File.exist?("a.txt")
来源：http://dali.ivvv.top/Article/details/gthqsemdww.html

C#:   File.Exists("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtnpafkaox.html

[F06] 删除文件
来源：http://dali.ehwqpu.com/Article/details/gtwfxzstsh.html

Py:   os.remove("a.txt")
来源：http://dali.ivvv.top/Article/details/gttkezcoga.html

PHP:  unlink("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtiwlarkjd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaoqujuqw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtyoxoikzx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtyibngzwi.html

Go:   os.Remove("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtnkrqxaan.html

Ruby: File.delete("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtocfzqrxp.html

C#:   File.Delete("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqmzdydt.html

[F07] 创建目录（含多级）
来源：http://dali.zhoulong.xyz/Article/details/gtzpplcxwg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258.top/Article/details/gthdmdyome.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gotoacloud.top/Article/details/gthkguotrn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigfzy.top/Article/details/gtadjjwgxw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shangyingyoupin.top/Article/details/gtuzfacswp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jiagoushi.top/Article/details/gtzksnyqgk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cucudq.cn/Article/details/gtzffxiche.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tanke756.top/Article/details/gtabpjayni.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hnqzz.top/Article/details/gtawtbnfzs.html

[F08] 遍历目录
来源：http://dali.zhixingplan.top/Article/details/gtuvjjufrt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgufenzy.top/Article/details/gtmyuxgyeg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ydzc1.top/Article/details/gtzwxucdgs.html

JS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtsbrxppiy.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gtmeqxhdzh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gtfjnlykjh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cdnleiting.top/Article/details/gthpogdqwu.html

Ruby: Dir.children("dir")
来源：http://dali.chenlongwang.top/Article/details/gtskywtctg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.316326.xyz/Article/details/gtxzdtiflu.html

[F09] 获取文件大小
来源：http://dali.nwbrower.top/Article/details/gtgjuebese.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtutyqtgtz.html

PHP:  filesize("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtdzhqasju.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gtfduiapvb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.c1oappe.top/Article/details/gteelswrnr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtqoijhsif.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmwayyta.html

Ruby: File.size("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gttrdvmcms.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.havefunace.top/Article/details/gtluigbyyu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ybcxt.top/Article/details/gtnbrznzpu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtiwcvxgjh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtjcnbhlvb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtfhvtvtjy.html

TS:   path.extname("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtpqgtywdm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shanyushiyangtech.top/Article/details/gtpuwzgtcv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtixsepkvd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtozhonmet.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtcsbfwlht.html

[F11] 复制与移动文件
来源：http://dali.yj20258.top/Article/details/gthwxaatpn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gteeffnhet.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tian-w.cn/Article/details/gtgiprcmsp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtfglhtkjk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtdrslrfre.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnqzz.top/Article/details/gteyojucme.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj202588.top/Article/details/gtgtaskcxa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtblzyygvt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.feifeiyinyue.top/Article/details/gtdiyvevqj.html

[F12] CSV 读写
来源：http://dali.0kj1m.cn/Article/details/gtudplkbez.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenlongwang.top/Article/details/gtpsvfhwpp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.bjfxy.top/Article/details/gtisjvrpco.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xylfe.cn/Article/details/gtfbckcgmt.html

TS:   // 同上
来源：http://dali.shzxlz.cn/Article/details/gtbtpynewx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daxiang520.top/Article/details/gtwvfooebv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhixingplan.top/Article/details/gtlwcgzzrm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.guannengcc.top/Article/details/gtasqknzeq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangshuangyany.cn/Article/details/gtykzpexrd.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtsocvpfnh.html

G. 面向对象
来源：http://dali.aibaodan.cn/Article/details/gtfijzoywk.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtwtzkqnid.html

[G01] 定义类
来源：http://dali.9152youxi.cn/Article/details/gtwoziggfu.html

Py:   class User: pass
来源：http://dali.yj202588.top/Article/details/gtnyhjmbgk.html

PHP:  class User {}
来源：http://dali.fzhhl.top/Article/details/gttyeihpbt.html

JS:   class User {}
来源：http://dali.aizwys.cn/Article/details/gtjnjpaxzy.html

TS:   class User { name: string = ""; }
来源：http://dali.cucudq.cn/Article/details/gtozobeoyz.html

Java: class User {}
来源：http://dali.aizwys.cn/Article/details/gtnearithw.html

Go:   type User struct { Name string }
来源：http://dali.hysaishi.cn/Article/details/gtqorrjemu.html

Ruby: class User; end
来源：http://dali.daxiang520.top/Article/details/gtetqbnaaw.html

C#:   class User {}
来源：http://dali.bjfxy.top/Article/details/gtbkwybndq.html

[G02] 构造函数
来源：http://dali.jqgfzy.top/Article/details/gtysblxrga.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nwbrower.top/Article/details/gtakqpsxvi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ivvv.top/Article/details/gtiwwwaoyn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtodufnuxr.html

TS:   constructor(public name: string) {}
来源：http://dali.cqqwz.cn/Article/details/gtkhgakjlm.html

Java: User(String name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gtrznkhhne.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hongshengwenyu.top/Article/details/gtajjezjpa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj202588.top/Article/details/gteyltlnbu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258888.top/Article/details/gtodjfnqql.html

[G03] 实例属性
来源：http://dali.ehwqpu.com/Article/details/gtzgsdjtsn.html

Py:   self.name = "x"
来源：http://dali.bjfxy.top/Article/details/gtewtimnmn.html

PHP:  public string $name = "x";
来源：http://dali.xuanzx.com/Article/details/gtdwmudowz.html

JS:   this.name = "x";
来源：http://dali.yangfankeji.com/Article/details/gtandmuqep.html

TS:   name: string = "x";
来源：http://dali.ivvv.top/Article/details/gtmqymogcp.html

Java: private String name;
来源：http://dali.yanxiufei.cn/Article/details/gtdfdxlpqx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cheryme.top/Article/details/gtwvtfdypj.html

Ruby: @name = "x"
来源：http://dali.yj20258888.top/Article/details/gtacpaqceu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ybcxt.top/Article/details/gtpzgyyzja.html

[G04] 定义方法
来源：http://dali.ppjwa.cn/Article/details/gtlmieonur.html

Py:   def greet(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gtqgbqzjbj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtcpeqfvel.html

JS:   greet() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtwsrsgyuw.html

TS:   greet(): string { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtafflkmpv.html

Java: String greet() { return name; }
来源：http://dali.fengsongda.top/Article/details/gtcmwpecng.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtmvwjbebq.html

Ruby: def greet; @name; end
来源：http://dali.iojbl.cn/Article/details/gtnnprxawo.html

C#:   public string Greet() => Name;
来源：http://dali.shzxlz.cn/Article/details/gtglrjmorv.html

[G05] 继承
来源：http://dali.yueranfly.top/Article/details/gtyrtoaqkc.html

Py:   class Admin(User): pass
来源：http://dali.yonumen.top/Article/details/gtytqwmjmb.html

PHP:  class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtftvayddk.html

JS:   class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtifymhfwh.html

TS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtjmpjhwtv.html

Java: class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtboxnmxda.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenjidiqi.icu/Article/details/gtiqczvmtp.html

Ruby: class Admin < User; end
来源：http://dali.sxryk.cn/Article/details/gtuhmofvmz.html

C#:   class Admin : User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtctszoqqq.html

[G06] 重写方法
来源：http://dali.hongshengwenyu.top/Article/details/gtdlftfbaq.html

Py:   def greet(self): return "admin"
来源：http://dali.wangshuangyany.cn/Article/details/gtldyovvhj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtchnnzesn.html

JS:   greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtxnrbsuis.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmrcwcwtk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtejcdsxry.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.bjfxy.top/Article/details/gthfvoleim.html

Ruby: def greet; "admin"; end
来源：http://dali.gaohongyu789.top/Article/details/gtgmzqywks.html

C#:   public override string Greet() => "admin";
来源：http://dali.sxryk.cn/Article/details/gtrfgrpvov.html

[G07] 调用父类方法
来源：http://dali.zdqjudy.top/Article/details/gtutrxibae.html

Py:   super().greet()
来源：http://dali.wangshuangyany.cn/Article/details/gtzuysvofm.html

PHP:  parent::greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtiysqjhin.html

JS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gtiwcibyrk.html

TS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtkaxoohqz.html

Java: super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtnpoyqfvb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnxiangtu.top/Article/details/gtlewegpjd.html

Ruby: super
来源：http://dali.nanxinkj.top/Article/details/gtqsuapjnr.html

C#:   base.Greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtzlsardwj.html

[G08] 静态方法与属性
来源：http://dali.yj20258888.top/Article/details/gtbfpdglps.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gaohongyu789.top/Article/details/gtmcghohmk.html

PHP:  public static function f() {}
来源：http://dali.havefunace.top/Article/details/gtdtgdyicg.html

JS:   static f() {}
来源：http://dali.yongpay.top/Article/details/gtbkgsktlx.html

TS:   static f(): void {}
来源：http://dali.jianghu66.top/Article/details/gtxedkiwfz.html

Java: static void f() {}
来源：http://dali.tian-w.cn/Article/details/gtxkbphvsq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jianghu66.top/Article/details/gtakyrwfki.html

Ruby: def self.f; end
来源：http://dali.shangyingyoupin.top/Article/details/gtwfujnnwe.html

C#:   public static void F() {}
来源：http://dali.chenlongwang.top/Article/details/gtfltpkaqv.html

[G09] 接口 / 抽象类
来源：http://dali.shangyingyoupin.top/Article/details/gtifrrzlyt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgufenzy.top/Article/details/gtgbyzpiqw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntxssotk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigfzy.top/Article/details/gtplkjffbl.html

TS:   interface Shape { area(): number; }
来源：http://dali.xuetiantiany.cn/Article/details/gtvltsuzjc.html

Java: interface Shape { double area(); }
来源：http://dali.haohaochexian.top/Article/details/gtjcbkspyn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xylfe.cn/Article/details/gtmsrnplgq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daxiang520.top/Article/details/gtzycllbkx.html

C#:   interface IShape { double Area(); }
来源：http://dali.yanxiufei.cn/Article/details/gtwctgslgq.html

[G10] 访问控制
来源：http://dali.quarkkingdee.top/Article/details/gtghqtayjl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tian-w.cn/Article/details/gtlenudcfc.html

PHP:  public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gtxbwxleiu.html

JS:   #private 字段；其余公开
来源：http://dali.snrcjt.cn/Article/details/gtkulzqzxv.html

TS:   public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtqplmaiho.html

Java: public / protected / private / 默认包级
来源：http://dali.gogol.net.cn/Article/details/gtnsiglzmx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pycfn.com/Article/details/gtdynffrpb.html

Ruby: public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gttwymwtgs.html

C#:   public / protected / private / internal
来源：http://dali.aibaodan.cn/Article/details/gttgbecywy.html

[G11] getter / setter
来源：http://dali.hfpthk.cn/Article/details/gtegjwzvvn.html

Py:   @property 与 @x.setter
来源：http://dali.jinqigufen.top/Article/details/gtwrcirmta.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gtoralgdqi.html

JS:   get name() { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gtjosmjjwx.html

TS:   get name(): string { return this._name; }
来源：http://dali.nwbrower.top/Article/details/gtezjkbupk.html

Java: public String getName() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtvqnqpnbx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gtlttfcwch.html

Ruby: attr_accessor :name
来源：http://dali.zhixingplan.top/Article/details/gtwefaovev.html

C#:   public string Name { get; set; }
来源：http://dali.hongshengwenyu.top/Article/details/gtcluxfcwb.html

[G12] 对象转字符串
来源：http://dali.sufxvd.cn/Article/details/gtjysafzsu.html

Py:   def __str__(self): return self.name
来源：http://dali.tanke756.top/Article/details/gtspzmocrv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtydcmrslk.html

JS:   toString() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtnujiaexw.html

TS:   toString(): string { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gteimgngpo.html

Java: @Override public String toString() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtxskojuyj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gthzevqxdn.html

Ruby: def to_s; @name; end
来源：http://dali.ybcxt.top/Article/details/gthcvicsnp.html

C#:   public override string ToString() => Name;
来源：http://dali.bjfxy.top/Article/details/gtmdlcwvud.html

[G13] 判断对象类型
来源：http://dali.xylfe.cn/Article/details/gtwnuomfxr.html

Py:   isinstance(u, User)
来源：http://dali.yuanzhike.top/Article/details/gtgntpvwkq.html

PHP:  $u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtvtnqzuil.html

JS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtppawtcku.html

TS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdnqdpvh.html

Java: u instanceof User
来源：http://dali.yonumen.top/Article/details/gtkbukxbpg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yongpay.top/Article/details/gtdkqaikxf.html

Ruby: u.is_a?(User)
来源：http://dali.jqgfzy.top/Article/details/gtzvtjlvgx.html

C#:   u is User
来源：http://dali.xylfe.cn/Article/details/gtegxvojhd.html

[G14] 数据类 / record
来源：http://dali.yuanzhike.top/Article/details/gtqxisaqxf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.feifeiyinyue.top/Article/details/gttuymgnrw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.wangshuangyany.cn/Article/details/gtdticqzbd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xinyue.icu/Article/details/gtwuoxecul.html

TS:   type User = { name: string; age: number };
来源：http://dali.gaohongyu789.top/Article/details/gtkknqwyow.html

Java: record User(String name, int age) {}
来源：http://dali.cheryme.top/Article/details/gtpzqarrxy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.fzhhl.top/Article/details/gtvhwlzexz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shuidangran.top/Article/details/gtyjiuibhp.html

C#:   record User(string Name, int Age);
来源：http://dali.zhongyouzk.top/Article/details/gtsaabkguv.html

[G15] 枚举
来源：http://dali.nanxuanxn.top/Article/details/gtffjcdbqd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj20258.top/Article/details/gtcwzcpwdk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtxqcjiybb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.fengsongda.top/Article/details/gtcwyyvgzp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gtucramajl.html

Java: enum Color { RED, GREEN }
来源：http://dali.dashuyun.cn/Article/details/gtusobvqwk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ydzc1.top/Article/details/gtlxxbqcxl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangshuangyany.cn/Article/details/gthjoocdlf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gterbmnjgw.html

[G16] 对象转数组 / 字典
来源：http://dali.ybcxt.top/Article/details/gtwdymjflg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sxryk.cn/Article/details/gtfwtsqthc.html

PHP:  get_object_vars($obj);
来源：http://dali.shzxlz.cn/Article/details/gtofsqxpva.html

JS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gtwolttroq.html

TS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gtzewjkdwk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daxiang520.top/Article/details/gtkbqhbqcy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuanzhike.top/Article/details/gtgwsuofqe.html

Ruby: obj.instance_variables
来源：http://dali.yj20258.top/Article/details/gtkmyczhih.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ehwqpu.com/Article/details/gtwgijdmbz.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtwcyrlmxl.html

H. 异常与错误处理
来源：http://dali.tian-w.cn/Article/details/gteegvnzkt.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtgrofgxhb.html

[H01] try / catch 基础
来源：http://dali.yongpay.top/Article/details/gtcbcicgba.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hnxiangtu.top/Article/details/gthhqkhrsd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xylfe.cn/Article/details/gtceyudgyp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jqgfzy.top/Article/details/gtruylsmro.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gtrdrzstyg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.316326.xyz/Article/details/gtwhgxiato.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yangfankeji.com/Article/details/gtievmduqo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gzhubu.top/Article/details/gtqzydgsaf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangdashe.top/Article/details/gtdugwhasl.html

[H02] finally / ensure 收尾
来源：http://dali.svipenyu.cn/Article/details/gtmlvhathm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pengpengdd.cyou/Article/details/gthfmtfamy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtfhdrhidp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtboavjdbd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtxxayqule.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gteulbklxh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yongpay.top/Article/details/gtowdqsfxb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sufxvd.cn/Article/details/gtwyjtkczu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtpjktjlhb.html

[H03] 主动抛出异常
来源：http://dali.andypj.xyz/Article/details/gttubnfybi.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtncpixitp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtgkcqkbkw.html

JS:   throw new Error("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtnaphcuch.html

TS:   throw new Error("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtrjnvnoky.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtyyumpyxk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shangyingyoupin.top/Article/details/gtuyhsfcnk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hfpthk.cn/Article/details/gtfltjzxnt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtlcxglnfq.html

[H04] 自定义异常类型
来源：http://dali.0kj1m.cn/Article/details/gtmmdofpgc.html

Py:   class MyError(Exception): pass
来源：http://dali.0kj1m.cn/Article/details/gtqshkapgz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gtiegyahrd.html


<!-- 参考信息 -->