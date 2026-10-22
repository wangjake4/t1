代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cdnleiting.top/Article/details/gtmzqztddq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gtqvwnjwsf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtbxmjbzaj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtraamjrai.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gttkdjgsym.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj202588.top/Article/details/gthjbwbbhs.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtghaiccda.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shuidangran.top/Article/details/gthyrmmdsb.html

[E22] 字节长度与字符长度
来源：http://dali.cucudq.cn/Article/details/gtkryomsiw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuanzhike.top/Article/details/gtrqewfinc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gteenljeac.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gtbzgrajix.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangdashe.top/Article/details/gtqqzxrunt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.kuanghao11.cn/Article/details/gtgjnzcfzi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sxryk.cn/Article/details/gtvnmfcrpi.html

Ruby: s.bytesize;  s.length
来源：http://dali.ehwqpu.com/Article/details/gtnvixlirx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cucudq.cn/Article/details/gteihasrsu.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtexcasnbq.html

F. 文件与目录
来源：http://dali.sweek.top/Article/details/gtdwuptjvv.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtlibqxokm.html

[F01] 读取整个文件
来源：http://dali.bjfxy.top/Article/details/gtjavleuuz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhixingplan.top/Article/details/gtsnkkbhxz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sweek.top/Article/details/gtvqrxyrca.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yongpay.top/Article/details/gtivnogbem.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtqnkcufkk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtgsyjwpfq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.wangshuangyany.cn/Article/details/gteutxyxvp.html

Ruby: File.read("a.txt")
来源：http://dali.yonumen.top/Article/details/gtfscytwbo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtuzilvtxy.html

[F02] 逐行读取文件
来源：http://dali.9152youxi.cn/Article/details/gtpxrhnvoo.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dashuyun.cn/Article/details/gtkurjqpzz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj202588.top/Article/details/gtuyyxklkm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.316326.xyz/Article/details/gtcdsgswwq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtsbjiynbf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gtpwymoqgb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yonumen.top/Article/details/gtrwdjdmea.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gotoacloud.top/Article/details/gtrtmsuqvg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ppjwa.cn/Article/details/gtljnbzspz.html

[F03] 写入文件（覆盖）
来源：http://dali.ppjwa.cn/Article/details/gthjjouscd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenzaomai.com/Article/details/gtxzkipocv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.fengsongda.top/Article/details/gtpnvcagur.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cucudq.cn/Article/details/gtnhcxnviq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cashguo.top/Article/details/gtnsafoypp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.andypj.xyz/Article/details/gtzmthdmzq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gaohongyu789.top/Article/details/gtqsnuaotb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.mhx1999.top/Article/details/gtpteqwcoj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gtmmaotdha.html

[F04] 追加写入文件
来源：http://dali.hywenlv.cn/Article/details/gtbuybpeoy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fzhhl.top/Article/details/gtjwitmkiy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hywenlv.cn/Article/details/gtpqihjntw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnqzz.top/Article/details/gtxqwgzgrl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.vqdsnc.cn/Article/details/gthbtaiwnk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinqigufen.top/Article/details/gtpexhndhh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtyocawmve.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yangfankeji.com/Article/details/gtoisqhyqi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yonumen.top/Article/details/gtxliwswuw.html

[F05] 判断文件或目录是否存在
来源：http://dali.yonumen.top/Article/details/gtqrlvzzga.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.birdmap.top/Article/details/gtponugfru.html

PHP:  file_exists("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtkqayvewo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtyrwwywnk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezhtenmm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtwzvqotnk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yangfankeji.com/Article/details/gtwvgeorod.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtrpmawexn.html

C#:   File.Exists("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzswhobna.html

[F06] 删除文件
来源：http://dali.yvedp.cn/Article/details/gtefzqrlbl.html

Py:   os.remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtksampefg.html

PHP:  unlink("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtyabaddcs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtkwddiglv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtdinlqbud.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtopcsyjnt.html

Go:   os.Remove("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gthzxbqsnt.html

Ruby: File.delete("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtljmamiby.html

C#:   File.Delete("a.txt");
来源：http://dali.hammf.cn/Article/details/gtevhpbwos.html

[F07] 创建目录（含多级）
来源：http://dali.ehwqpu.com/Article/details/gtvecdvhji.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.snrcjt.cn/Article/details/gtcsfxkcga.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tanke756.top/Article/details/gthjtshnyb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gtlizyqktx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenzaomai.com/Article/details/gtyycolnqh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenjidiqi.icu/Article/details/gtnhdwfils.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gaohongyu789.top/Article/details/gtaovfhdyb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenzaomai.com/Article/details/gtcirbtpwz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xylfe.cn/Article/details/gtesjumvki.html

[F08] 遍历目录
来源：http://dali.guannengcc.top/Article/details/gtlcgdggxi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ybcxt.top/Article/details/gtvigdgnpa.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj202588.top/Article/details/gtjtqrdwyi.html

JS:   fs.readdirSync("dir")
来源：http://dali.zycfv.cn/Article/details/gtcddvrxgr.html

TS:   fs.readdirSync("dir")
来源：http://dali.ivvv.top/Article/details/gtgwsckctf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.feifeiyinyue.top/Article/details/gtnxnfnrsm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtiufldrre.html

Ruby: Dir.children("dir")
来源：http://dali.cqqwz.cn/Article/details/gtvtddgtuk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtcpbtmsic.html

[F09] 获取文件大小
来源：http://dali.meibo888.top/Article/details/gtcmdllxda.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtotjgivcg.html

PHP:  filesize("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtlnsgxgtw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gtfoovwfzu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gtvqowupdv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtgyssdorr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdxuqkwz.html

Ruby: File.size("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtuglkifkq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sweek.top/Article/details/gtdqjbwvsq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.316326.xyz/Article/details/gttxjreeoy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtifrihzfc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258888.top/Article/details/gtogzuzyrh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gthkjgshuu.html

TS:   path.extname("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtsqpozoke.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpsedumf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtohrfucvv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtlkymmfwk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtbguognys.html

[F11] 复制与移动文件
来源：http://dali.hnqzz.top/Article/details/gtuiccdaba.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtolundntz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.haohaochexian.top/Article/details/gtapdhfikp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtdjbqbrca.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtmodryler.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gtjsohvjzb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ppjwa.cn/Article/details/gttblufdwu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtyrcjozcq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cucudq.cn/Article/details/gtyfxahfhf.html

[F12] CSV 读写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhagagrt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jqgufenzy.top/Article/details/gtgttqlkyt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jyoumei.cn/Article/details/gtnfwsxoac.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinqigufen.top/Article/details/gtsdxdzpvo.html

TS:   // 同上
来源：http://dali.ppjwa.cn/Article/details/gtuseqeexy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgufenzy.top/Article/details/gtdkmdelmu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.birdmap.top/Article/details/gtxglpxowi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jyoumei.cn/Article/details/gtghbkvorr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.haohaochexian.top/Article/details/gtzfdyvnnn.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtlbjepjgl.html

G. 面向对象
来源：http://dali.jiagoushi.top/Article/details/gttrtwhywg.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtiqwgxixf.html

[G01] 定义类
来源：http://dali.c1oappe.top/Article/details/gtcwxfnflt.html

Py:   class User: pass
来源：http://dali.mhx1999.top/Article/details/gtlsjaiwly.html

PHP:  class User {}
来源：http://dali.yuanzhike.top/Article/details/gtzvwcvehy.html

JS:   class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtpzdkqxxp.html

TS:   class User { name: string = ""; }
来源：http://dali.c1oappe.top/Article/details/gtnwkbxief.html

Java: class User {}
来源：http://dali.yuanzhike.top/Article/details/gttqmuowmv.html

Go:   type User struct { Name string }
来源：http://dali.aizwys.cn/Article/details/gtcxzauihr.html

Ruby: class User; end
来源：http://dali.xinyue.icu/Article/details/gtfqwriwha.html

C#:   class User {}
来源：http://dali.andypj.xyz/Article/details/gtkzoebrcc.html

[G02] 构造函数
来源：http://dali.pycfn.com/Article/details/gtmicqjjbv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.birdmap.top/Article/details/gtdgjahgdd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.kuanghao11.cn/Article/details/gtcouayqcb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gtgfuejban.html

TS:   constructor(public name: string) {}
来源：http://dali.aizwys.cn/Article/details/gtsvdztikl.html

Java: User(String name) { this.name = name; }
来源：http://dali.guannengcc.top/Article/details/gtwqkflrrl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtigghcoqo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.0kj1m.cn/Article/details/gtmmtweeuw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtpeuqozlx.html

[G03] 实例属性
来源：http://dali.cqqwz.cn/Article/details/gtmqdvvlkl.html

Py:   self.name = "x"
来源：http://dali.meibo888.top/Article/details/gtrrosqyyo.html

PHP:  public string $name = "x";
来源：http://dali.guannengcc.top/Article/details/gtdekwhqin.html

JS:   this.name = "x";
来源：http://dali.hywenlv.cn/Article/details/gttkoicddj.html

TS:   name: string = "x";
来源：http://dali.ydzc1.top/Article/details/gtdkmoqsmi.html

Java: private String name;
来源：http://dali.yj20258888.top/Article/details/gtxjqfrllr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yonumen.top/Article/details/gtsqxmierj.html

Ruby: @name = "x"
来源：http://dali.c1oappe.top/Article/details/gtvxgdklxh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtwupsfppg.html

[G04] 定义方法
来源：http://dali.pycfn.com/Article/details/gtvbkvmwrg.html

Py:   def greet(self): return self.name
来源：http://dali.cqqwz.cn/Article/details/gtxpgyitun.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gtbcioanxn.html

JS:   greet() { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtdcvevjwv.html

TS:   greet(): string { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gtugpwngth.html

Java: String greet() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtguubczhu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gtqdwfvaye.html

Ruby: def greet; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtxbwmmaag.html

C#:   public string Greet() => Name;
来源：http://dali.yueranfly.top/Article/details/gtelnnhnxh.html

[G05] 继承
来源：http://dali.xziqi.cn/Article/details/gtkoqharuk.html

Py:   class Admin(User): pass
来源：http://dali.yuxming.cn/Article/details/gttmcrwhdk.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtfpdkxhyy.html

JS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtuyrkbvlr.html

TS:   class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtmspwqmdk.html

Java: class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtvfirsqrr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.haohaochexian.top/Article/details/gtwmlvoqgw.html

Ruby: class Admin < User; end
来源：http://dali.zhiwuduotai.top/Article/details/gtcvzkjlqk.html

C#:   class Admin : User {}
来源：http://dali.ydzc1.top/Article/details/gtwtkzxoht.html

[G06] 重写方法
来源：http://dali.sweek.top/Article/details/gttdnnjzem.html

Py:   def greet(self): return "admin"
来源：http://dali.0kj1m.cn/Article/details/gtzuntmrsz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtkxgmfhpl.html

JS:   greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtxhntswos.html

TS:   greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtwphqwthf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtuxfbwleh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.9152youxi.cn/Article/details/gtmqnocqcd.html

Ruby: def greet; "admin"; end
来源：http://dali.fengsongda.top/Article/details/gtmuylyrnr.html

C#:   public override string Greet() => "admin";
来源：http://dali.yongpay.top/Article/details/gtkdydwven.html

[G07] 调用父类方法
来源：http://dali.sufxvd.cn/Article/details/gtdtxfgewi.html

Py:   super().greet()
来源：http://dali.shuidangran.top/Article/details/gtewlhtfau.html

PHP:  parent::greet();
来源：http://dali.nanxinkj.top/Article/details/gtiaipetxn.html

JS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtrhtuklti.html

TS:   super.greet();
来源：http://dali.bjfxy.top/Article/details/gtdqnrbxyc.html

Java: super.greet();
来源：http://dali.hammf.cn/Article/details/gtbysjbuiw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shuidangran.top/Article/details/gtjjtrkjex.html

Ruby: super
来源：http://dali.havefunace.top/Article/details/gtflvsmdlw.html

C#:   base.Greet();
来源：http://dali.daria6918.cn/Article/details/gtjydpjnuj.html

[G08] 静态方法与属性
来源：http://dali.quarkkingdee.top/Article/details/gttdrslcbe.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gaohongyu789.top/Article/details/gtvdcxsgrv.html

PHP:  public static function f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gttkyxnaky.html

JS:   static f() {}
来源：http://dali.cashguo.top/Article/details/gthgkkeonq.html

TS:   static f(): void {}
来源：http://dali.quarkkingdee.top/Article/details/gtzknodhyf.html

Java: static void f() {}
来源：http://dali.fengsongda.top/Article/details/gtxfpmeuqr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjkpphjjd.html

Ruby: def self.f; end
来源：http://dali.sufxvd.cn/Article/details/gtcjfjnbrz.html

C#:   public static void F() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqcdabcqp.html

[G09] 接口 / 抽象类
来源：http://dali.cqqwz.cn/Article/details/gtucoqzreh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.dashuyun.cn/Article/details/gtajvsbobq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cheryme.top/Article/details/gtjjknnxeo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xuanzx.com/Article/details/gtbeohdipm.html

TS:   interface Shape { area(): number; }
来源：http://dali.feifeiyinyue.top/Article/details/gtonflzvfg.html

Java: interface Shape { double area(); }
来源：http://dali.zycfv.cn/Article/details/gturpkmwhw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guannengcc.top/Article/details/gtdivjzjiy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shangyingyoupin.top/Article/details/gtmwrimblv.html

C#:   interface IShape { double Area(); }
来源：http://dali.316326.xyz/Article/details/gtgwaywvvk.html

[G10] 访问控制
来源：http://dali.9152youxi.cn/Article/details/gttwcwhotr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dianchejie.cn/Article/details/gtbranqfnd.html

PHP:  public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtsnqiqfwk.html

JS:   #private 字段；其余公开
来源：http://dali.meibo888.top/Article/details/gtndjvttjy.html

TS:   public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtvbzfwegn.html

Java: public / protected / private / 默认包级
来源：http://dali.xylfe.cn/Article/details/gtwgctemry.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yueranfly.top/Article/details/gtihpjhist.html

Ruby: public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtjvgtalwl.html

C#:   public / protected / private / internal
来源：http://dali.sysykeji.top/Article/details/gtbhrzithz.html

[G11] getter / setter
来源：http://dali.ivvv.top/Article/details/gtyoytyhfz.html

Py:   @property 与 @x.setter
来源：http://dali.fzhhl.top/Article/details/gthjjrskax.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtognfxacf.html

JS:   get name() { return this._name; }
来源：http://dali.xylfe.cn/Article/details/gtbcupdmwd.html

TS:   get name(): string { return this._name; }
来源：http://dali.ehwqpu.com/Article/details/gtqfholfqh.html

Java: public String getName() { return name; }
来源：http://dali.daria6918.cn/Article/details/gtheustdwo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtkbfhqhsi.html

Ruby: attr_accessor :name
来源：http://dali.ehwqpu.com/Article/details/gtwswxdicb.html

C#:   public string Name { get; set; }
来源：http://dali.svipenyu.cn/Article/details/gtppwamxof.html

[G12] 对象转字符串
来源：http://dali.sufxvd.cn/Article/details/gtqstpmosk.html

Py:   def __str__(self): return self.name
来源：http://dali.yangfankeji.com/Article/details/gtdxeanndh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gtclluhhtk.html

JS:   toString() { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtymvsspop.html

TS:   toString(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtncenriuq.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcpabasgy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gtakvqeozo.html

Ruby: def to_s; @name; end
来源：http://dali.haohaochexian.top/Article/details/gtpwoeqflo.html

C#:   public override string ToString() => Name;
来源：http://dali.ydzc1.top/Article/details/gtlqnswymk.html

[G13] 判断对象类型
来源：http://dali.feifeiyinyue.top/Article/details/gtsgfbhadi.html

Py:   isinstance(u, User)
来源：http://dali.haohaochexian.top/Article/details/gtblosyscw.html

PHP:  $u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtqbjdsyuf.html

JS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtddivetst.html

TS:   u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtqztrkilv.html

Java: u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtfzmiqwsh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258.top/Article/details/gtnujvejfe.html

Ruby: u.is_a?(User)
来源：http://dali.tian-w.cn/Article/details/gtkatrnafp.html

C#:   u is User
来源：http://dali.chenjidiqi.icu/Article/details/gtbbegigou.html

[G14] 数据类 / record
来源：http://dali.hnqzz.top/Article/details/gtxgkaxkkx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258.top/Article/details/gtujqxwbfz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tanke756.top/Article/details/gthygjqiqa.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jianghu66.top/Article/details/gthytcrihy.html

TS:   type User = { name: string; age: number };
来源：http://dali.ehwqpu.com/Article/details/gtdatloklu.html

Java: record User(String name, int age) {}
来源：http://dali.snrcjt.cn/Article/details/gtawleomcy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenlongwang.top/Article/details/gtjjdnsovo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnxiangtu.top/Article/details/gtmpimqilf.html

C#:   record User(string Name, int Age);
来源：http://dali.birdmap.top/Article/details/gtjogjdyys.html

[G15] 枚举
来源：http://dali.guowangkeji.top/Article/details/gtrxqbgvtk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gotoacloud.top/Article/details/gtplpdjoaa.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tanke756.top/Article/details/gtztxbafzt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.mhx1999.top/Article/details/gtxpcgrujp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.0kj1m.cn/Article/details/gtjtiwdlgd.html

Java: enum Color { RED, GREEN }
来源：http://dali.dianchejie.cn/Article/details/gtahrpdzxo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jqgfzy.top/Article/details/gtxjyqtddd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yueranfly.top/Article/details/gtxohuehvl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gtmgtdrjms.html

[G16] 对象转数组 / 字典
来源：http://dali.c1oappe.top/Article/details/gtttasalrz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.havefunace.top/Article/details/gthektqgjc.html

PHP:  get_object_vars($obj);
来源：http://dali.nwbrower.top/Article/details/gtfzjynuyu.html

JS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfhozjjw.html

TS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gtcwccvivm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.guannengcc.top/Article/details/gtdsyqfdpj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pengpengdd.cyou/Article/details/gtywpmqjcu.html

Ruby: obj.instance_variables
来源：http://dali.gogol.net.cn/Article/details/gtbjogwoyf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnxiangtu.top/Article/details/gtmfkkwhzb.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtokwijlpb.html

H. 异常与错误处理
来源：http://dali.tian-w.cn/Article/details/gtuwkjxymy.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtcighdufj.html

[H01] try / catch 基础
来源：http://dali.hnxiangtu.top/Article/details/gtjecueift.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cdnleiting.top/Article/details/gtkzkvchys.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jlsjyb.cn/Article/details/gtumzonxed.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gtkqkdlrpk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxjpwqjtk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.0kj1m.cn/Article/details/gtxdfjuexq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.vqdsnc.cn/Article/details/gtvygoupmj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nwbrower.top/Article/details/gtqzyywalu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gaohongyu789.top/Article/details/gtnmbipsyu.html

[H02] finally / ensure 收尾
来源：http://dali.pycfn.com/Article/details/gtsgegctsv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ybcxt.top/Article/details/gtcaagwddm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtothmkutr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtylmkslnn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtyogkmtpr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtvqdyqbss.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xinyue.icu/Article/details/gtixtvwazn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ydzc1.top/Article/details/gtawkffnyx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtcdmxxxky.html

[H03] 主动抛出异常
来源：http://dali.xuetiantiany.cn/Article/details/gtgzqfskos.html

Py:   raise ValueError("错误信息")
来源：http://dali.ppjwa.cn/Article/details/gthrabcszn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtsslfuibz.html

JS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwdcxkgs.html


<!-- 参考信息 -->