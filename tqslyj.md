代发 wailian999

Go:   if s == "" {}
来源：http://dali.mhx1999.top/Article/details/gtffxqayln.html

Ruby: if s.empty?
来源：http://dali.haohaochexian.top/Article/details/gtnxvakixh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtbmjhhwvl.html

[E21] 超长截断加省略号
来源：http://dali.dianchejie.cn/Article/details/gtzefsxkum.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gzhubu.top/Article/details/gtgxxbdytk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.316326.xyz/Article/details/gtusilkjcb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gtamrbzrbf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtoetiuzyg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtlgsdbwmu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj20258.top/Article/details/gthrjmwufy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtengqwfsq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtquuppbnd.html

[E22] 字节长度与字符长度
来源：http://dali.daxiang520.top/Article/details/gtnbwnzyih.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.c1oappe.top/Article/details/gtzimfxedo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtzacrwegh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gtfdbylxzs.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuanzx.com/Article/details/gtldqnssrv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.daxiang520.top/Article/details/gtuumgxzji.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tianlin.xyz/Article/details/gtdgkkgebp.html

Ruby: s.bytesize;  s.length
来源：http://dali.cqqwz.cn/Article/details/gtnnrnuiwm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yangfankeji.com/Article/details/gtivqtoqrm.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtegqeqeut.html

F. 文件与目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gtranglcrf.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtkirbzccx.html

[F01] 读取整个文件
来源：http://dali.cheryme.top/Article/details/gtjpaijnvq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yongpay.top/Article/details/gtedowmehg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtmuhcuzos.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fengsongda.top/Article/details/gtooctzqkp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.birdmap.top/Article/details/gthmrdlbvo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtdxforoyl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gaohongyu789.top/Article/details/gtmhjcjnao.html

Ruby: File.read("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtvjgddpbr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtjytdvicr.html

[F02] 逐行读取文件
来源：http://dali.ivvv.top/Article/details/gtdlqzudxy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ydzc1.top/Article/details/gtludglnrw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gogol.net.cn/Article/details/gtbmneksvv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gogol.net.cn/Article/details/gtqubhmmji.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.kuanghao11.cn/Article/details/gtllppoonx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tianlin.xyz/Article/details/gtfojvuezq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj20258.top/Article/details/gthdhmcorr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiydbdqvr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.feifeiyinyue.top/Article/details/gtqeanroap.html

[F03] 写入文件（覆盖）
来源：http://dali.sweek.top/Article/details/gtfiknwhaz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenzaomai.com/Article/details/gtwgaayxzr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.smart0.xyz/Article/details/gtcyvmurto.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtfhhjoanr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sweek.top/Article/details/gtegmczdzm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gtthyyxmbb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yueranfly.top/Article/details/gtdhvavqam.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tianlin.xyz/Article/details/gtewjinidn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gtjydwossb.html

[F04] 追加写入文件
来源：http://dali.quarkkingdee.top/Article/details/gtiurdyldi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.mhx1999.top/Article/details/gtvhpnejpj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.aibaodan.cn/Article/details/gtcmlymepk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gthoipwxnd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zycfv.cn/Article/details/gtmfhzfpwl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.dianchejie.cn/Article/details/gtgidjdzgp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hnqzz.top/Article/details/gtpjxjudoy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zycfv.cn/Article/details/gtjtxbknft.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.9152youxi.cn/Article/details/gttcydtmqq.html

[F05] 判断文件或目录是否存在
来源：http://dali.pycfn.com/Article/details/gtmuearwxz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jqgfzy.top/Article/details/gthotixvdi.html

PHP:  file_exists("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gthjcbweui.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtevnyqkxw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtanaqlbph.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gtzlquxclu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgobyrsmv.html

Ruby: File.exist?("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtsqejvgqk.html

C#:   File.Exists("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtsyjmlram.html

[F06] 删除文件
来源：http://dali.yvedp.cn/Article/details/gtcbqhuvhy.html

Py:   os.remove("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtaayatnen.html

PHP:  unlink("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtuuadfocj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtrbyfkvug.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtlexdxihb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtflmxukhj.html

Go:   os.Remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtqhlsjutd.html

Ruby: File.delete("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtrqqiflxu.html

C#:   File.Delete("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtugmxsnlf.html

[F07] 创建目录（含多级）
来源：http://dali.cheryme.top/Article/details/gtxvsxrawf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ydzc1.top/Article/details/gtvxtrkwhu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yueranfly.top/Article/details/gtiqagyple.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gtbzzqomcz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuanzhike.top/Article/details/gtrxszqcug.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.9152youxi.cn/Article/details/gtluauwjcc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shangyingyoupin.top/Article/details/gtofauqfxs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.kuanghao11.cn/Article/details/gtfhhydzla.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhongyouzk.top/Article/details/gtscbzobwu.html

[F08] 遍历目录
来源：http://dali.c1oappe.top/Article/details/gtnanvyovz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sufxvd.cn/Article/details/gtpjwlpbsq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfwovikun.html

JS:   fs.readdirSync("dir")
来源：http://dali.shuidangran.top/Article/details/gtrommksqb.html

TS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gttktkvrba.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gtucgoakll.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtgweqxofl.html

Ruby: Dir.children("dir")
来源：http://dali.haohaochexian.top/Article/details/gtmfaeqeww.html

C#:   Directory.GetFiles("dir")
来源：http://dali.meibo888.top/Article/details/gtpdlhnnrs.html

[F09] 获取文件大小
来源：http://dali.jyoumei.cn/Article/details/gtokzfdbzk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtkevntldp.html

PHP:  filesize("a.txt");
来源：http://dali.316326.xyz/Article/details/gtfusnedeg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.vqdsnc.cn/Article/details/gtblhdinlt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.mhx1999.top/Article/details/gtrowkelle.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtgmxvoree.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zdqjudy.top/Article/details/gtkqzazvpr.html

Ruby: File.size("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtbdojlynq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.aizwys.cn/Article/details/gtmrqxmnng.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigufen.top/Article/details/gthxzbhcpm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtgvvrwrie.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.havefunace.top/Article/details/gtwvukegul.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpvznyguz.html

TS:   path.extname("a.txt")
来源：http://dali.pycfn.com/Article/details/gtqauiygea.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guowangkeji.top/Article/details/gttyalvasn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtrjotuqfn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgyxkkdkz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtpzwisrbj.html

[F11] 复制与移动文件
来源：http://dali.yonumen.top/Article/details/gtqqahqvfy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtjitnodmd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yonumen.top/Article/details/gtlxovzlmg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlequvzvu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtlxlgehiu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cheryme.top/Article/details/gtlulxdlbu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhengqikj.top/Article/details/gtkiqcqfjq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtozobmuve.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.aibaodan.cn/Article/details/gtwwqbheet.html

[F12] CSV 读写
来源：http://dali.meibo888.top/Article/details/gtrpmiophr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tianlin.xyz/Article/details/gtkdkslgot.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shuidangran.top/Article/details/gtvirdfpeu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tanke756.top/Article/details/gtkjeieqvm.html

TS:   // 同上
来源：http://dali.ydzc1.top/Article/details/gtrnwcktqx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.haohaochexian.top/Article/details/gttagtzrqg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cqqwz.cn/Article/details/gtesqtwerx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yongpay.top/Article/details/gtdwmjfovk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.316326.xyz/Article/details/gthgsvxfvk.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtjugwpkxq.html

G. 面向对象
来源：http://dali.jyoumei.cn/Article/details/gtddoaedba.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtrzqyqgmf.html

[G01] 定义类
来源：http://dali.cdnleiting.top/Article/details/gtxrawrtfq.html

Py:   class User: pass
来源：http://dali.guannengcc.top/Article/details/gtgytmhsrz.html

PHP:  class User {}
来源：http://dali.dianchejie.cn/Article/details/gtrjuanobt.html

JS:   class User {}
来源：http://dali.yueranfly.top/Article/details/gtwdbqlcgo.html

TS:   class User { name: string = ""; }
来源：http://dali.quarkkingdee.top/Article/details/gtgrdzrnro.html

Java: class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvrlxvwe.html

Go:   type User struct { Name string }
来源：http://dali.hammf.cn/Article/details/gtlkkjrxwj.html

Ruby: class User; end
来源：http://dali.vqdsnc.cn/Article/details/gtlvxxwuga.html

C#:   class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrcqoiujc.html

[G02] 构造函数
来源：http://dali.tianlin.xyz/Article/details/gtawspqaja.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.snrcjt.cn/Article/details/gtmidxrmra.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenzaomai.com/Article/details/gtpnctyizs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gtfnldyjsa.html

TS:   constructor(public name: string) {}
来源：http://dali.bjfxy.top/Article/details/gtszqsrmfw.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhixingplan.top/Article/details/gtvsbfrskf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sweek.top/Article/details/gtqfznkuab.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hnqzz.top/Article/details/gtxvyadngi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.birdmap.top/Article/details/gtmtzgiypz.html

[G03] 实例属性
来源：http://dali.chenlongwang.top/Article/details/gtvqkodfrr.html

Py:   self.name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gtwshbcszs.html

PHP:  public string $name = "x";
来源：http://dali.xziqi.cn/Article/details/gtqtaybewg.html

JS:   this.name = "x";
来源：http://dali.fengsongda.top/Article/details/gtlqbdopob.html

TS:   name: string = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtwggvqjwy.html

Java: private String name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudaaxcvv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yuanzhike.top/Article/details/gtadkgvbme.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gtdfokwcfv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.svipenyu.cn/Article/details/gtyzbmqezy.html

[G04] 定义方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtdqdfxxsk.html

Py:   def greet(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gtlwswakax.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtwfhghrsn.html

JS:   greet() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtfomzzzvl.html

TS:   greet(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gtskdfghgv.html

Java: String greet() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtnqmmuehd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gtbtudnwlt.html

Ruby: def greet; @name; end
来源：http://dali.xuanzx.com/Article/details/gtqmaarejt.html

C#:   public string Greet() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtccdyihqw.html

[G05] 继承
来源：http://dali.guowangkeji.top/Article/details/gttdxyowth.html

Py:   class Admin(User): pass
来源：http://dali.wangshuangyany.cn/Article/details/gtdwpxxgvf.html

PHP:  class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gthwdsfnpg.html

JS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtqlnvibuu.html

TS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtwbdxpetk.html

Java: class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtzulrwagw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sufxvd.cn/Article/details/gtwpuaehfe.html

Ruby: class Admin < User; end
来源：http://dali.hammf.cn/Article/details/gtizferbng.html

C#:   class Admin : User {}
来源：http://dali.yj20258.top/Article/details/gtpiewbwkc.html

[G06] 重写方法
来源：http://dali.yangfankeji.com/Article/details/gtirpjrcuo.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigfzy.top/Article/details/gtbfqqnkzg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtreopzdqd.html

JS:   greet() { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtowodokzb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtqpkostst.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtaffznvoi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tanke756.top/Article/details/gtcrhykdrf.html

Ruby: def greet; "admin"; end
来源：http://dali.guowangkeji.top/Article/details/gthlxakjly.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuanzx.com/Article/details/gtkcptugdf.html

[G07] 调用父类方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcxrganbf.html

Py:   super().greet()
来源：http://dali.yangfankeji.com/Article/details/gtfpuilbvj.html

PHP:  parent::greet();
来源：http://dali.dianchejie.cn/Article/details/gtluheehgo.html

JS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gtloielbsm.html

TS:   super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljlbahqq.html

Java: super.greet();
来源：http://dali.andypj.xyz/Article/details/gtukjyshrq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.kuanghao11.cn/Article/details/gtzckorphm.html

Ruby: super
来源：http://dali.zhixingplan.top/Article/details/gtrgbbsywv.html

C#:   base.Greet();
来源：http://dali.hnqzz.top/Article/details/gtmcxynyei.html

[G08] 静态方法与属性
来源：http://dali.cheryme.top/Article/details/gtgynlusus.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangshuangyany.cn/Article/details/gtsxqzzbjo.html

PHP:  public static function f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtbiqjpgdq.html

JS:   static f() {}
来源：http://dali.jianghu66.top/Article/details/gthjzmikuf.html

TS:   static f(): void {}
来源：http://dali.iojbl.cn/Article/details/gtliygqdhm.html

Java: static void f() {}
来源：http://dali.sufxvd.cn/Article/details/gtigzgrdgc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sxryk.cn/Article/details/gtmthtqnne.html

Ruby: def self.f; end
来源：http://dali.jlsjyb.cn/Article/details/gtrebyzvzr.html

C#:   public static void F() {}
来源：http://dali.aibaodan.cn/Article/details/gtqswzrltd.html

[G09] 接口 / 抽象类
来源：http://dali.nanxinkj.top/Article/details/gtobogqhbp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hfpthk.cn/Article/details/gtxnayxlxk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guowangkeji.top/Article/details/gtbtcagrby.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhoulong.xyz/Article/details/gtouqyggmk.html

TS:   interface Shape { area(): number; }
来源：http://dali.hysaishi.cn/Article/details/gtkhoovpuj.html

Java: interface Shape { double area(); }
来源：http://dali.andypj.xyz/Article/details/gtaibgshrk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cqqwz.cn/Article/details/gtdtjntvtc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtnhdzowou.html

C#:   interface IShape { double Area(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwmkpaqo.html

[G10] 访问控制
来源：http://dali.guannengcc.top/Article/details/gtiofpbkua.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sysykeji.top/Article/details/gtzyrrdojs.html

PHP:  public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gtrsbxsdjz.html

JS:   #private 字段；其余公开
来源：http://dali.xuetiantiany.cn/Article/details/gtbewdimos.html

TS:   public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gtfaokoumv.html

Java: public / protected / private / 默认包级
来源：http://dali.jinghuilouyu.cn/Article/details/gtfctlysrh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xylfe.cn/Article/details/gtkjuliwpx.html

Ruby: public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtjstqkcri.html

C#:   public / protected / private / internal
来源：http://dali.svipenyu.cn/Article/details/gtevdywevd.html

[G11] getter / setter
来源：http://dali.ydzc1.top/Article/details/gtrxyhbayf.html

Py:   @property 与 @x.setter
来源：http://dali.svipenyu.cn/Article/details/gtkvvzfdco.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gthpnounyb.html

JS:   get name() { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gtscdrpitb.html

TS:   get name(): string { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gtfbqmwfzl.html

Java: public String getName() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtbrjzjosc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gtyffefpnm.html

Ruby: attr_accessor :name
来源：http://dali.cucudq.cn/Article/details/gtgvhstzvh.html

C#:   public string Name { get; set; }
来源：http://dali.jlsjyb.cn/Article/details/gtjfnxtlrf.html

[G12] 对象转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnwkvdxq.html

Py:   def __str__(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gtrmuaidix.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gtnxknacmp.html

JS:   toString() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtcxnmkwnp.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtgiotahoi.html

Java: @Override public String toString() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gthqzeluau.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbpairdz.html

Ruby: def to_s; @name; end
来源：http://dali.tanke756.top/Article/details/gtcqrseavo.html

C#:   public override string ToString() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gtgnqpchjf.html

[G13] 判断对象类型
来源：http://dali.tianlin.xyz/Article/details/gtdrykgqkh.html

Py:   isinstance(u, User)
来源：http://dali.kuanghao11.cn/Article/details/gtpalbavdw.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftrryovc.html

JS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gtuxzjblqz.html

TS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtralmngos.html

Java: u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtixblghvd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hongshengwenyu.top/Article/details/gtwiitvbwc.html

Ruby: u.is_a?(User)
来源：http://dali.hnxiangtu.top/Article/details/gtonhhyxny.html

C#:   u is User
来源：http://dali.smart0.xyz/Article/details/gtxyxoagye.html

[G14] 数据类 / record
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsbkovjll.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xinyue.icu/Article/details/gtjcbvwlyn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hysaishi.cn/Article/details/gtiffsmjii.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cheryme.top/Article/details/gtlgnvuaap.html

TS:   type User = { name: string; age: number };
来源：http://dali.aizwys.cn/Article/details/gtvgxlzied.html

Java: record User(String name, int age) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzlglsnhg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenlongwang.top/Article/details/gtefnzyrsl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jiagoushi.top/Article/details/gtgupgtiun.html

C#:   record User(string Name, int Age);
来源：http://dali.chenlongwang.top/Article/details/gtzekvwxaa.html

[G15] 枚举
来源：http://dali.quarkkingdee.top/Article/details/gtqdjpqxpj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yueranfly.top/Article/details/gtyxdexvey.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yanxiufei.cn/Article/details/gtubqbnajv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuanzx.com/Article/details/gtrovmgtlf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gtvzykjtbb.html

Java: enum Color { RED, GREEN }
来源：http://dali.kuanghao11.cn/Article/details/gtiidxhqvm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shzxlz.cn/Article/details/gtrordllfo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.daria6918.cn/Article/details/gtrphlbklh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjuqdzphz.html

[G16] 对象转数组 / 字典
来源：http://dali.hfpthk.cn/Article/details/gtuecgstdw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zdqjudy.top/Article/details/gtyuvhjpbg.html

PHP:  get_object_vars($obj);
来源：http://dali.jyoumei.cn/Article/details/gtufbrpahq.html

JS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gtvidqtaho.html

TS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gtdwptiuoa.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jiagoushi.top/Article/details/gtduppdyri.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.feifeiyinyue.top/Article/details/gtzdteapnd.html

Ruby: obj.instance_variables
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmsfwawxx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinghuilouyu.cn/Article/details/gtpfbvrhrq.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtvegcemhg.html

H. 异常与错误处理
来源：http://dali.mhx1999.top/Article/details/gtgulxpnpf.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtzakxwlzk.html

[H01] try / catch 基础
来源：http://dali.hywenlv.cn/Article/details/gtsfgwsroh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhixingplan.top/Article/details/gtlcijrlme.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xuanzx.com/Article/details/gtgohypyji.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gtntosggzp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gtxxmrseka.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnxiangtu.top/Article/details/gttohhwlvv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jqgufenzy.top/Article/details/gtuxvrpniy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hnxiangtu.top/Article/details/gtexhuqcnj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xinyue.icu/Article/details/gteksqhaxj.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258.top/Article/details/gtukzspqsh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jianghu66.top/Article/details/gtvhubpvvv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtmyfsgroq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtnupomihx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gthncmctxq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqrouliq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shangyingyoupin.top/Article/details/gtrqhchzfm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dianchejie.cn/Article/details/gtvnqoqeun.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtxvowshbt.html


<!-- 参考信息 -->