代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gthqxuhfad.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinqigufen.top/Article/details/gtjzbedkul.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtcondidwt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gtbyufvcka.html

[E22] 字节长度与字符长度
来源：http://dali.0kj1m.cn/Article/details/gtinzdsvjm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenjidiqi.icu/Article/details/gthzhhdesr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.meibo888.top/Article/details/gtrinkmdot.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tanke756.top/Article/details/gtigxmloqg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtevhekknf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shzxlz.cn/Article/details/gtfywycpfx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gaohongyu789.top/Article/details/gthfmeoryo.html

Ruby: s.bytesize;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gtacfvgavc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.aibaodan.cn/Article/details/gtpkrwgjlr.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtsqdofaxk.html

F. 文件与目录
来源：http://dali.chenjidiqi.icu/Article/details/gtselscxia.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtszkzlotq.html

[F01] 读取整个文件
来源：http://dali.gaohongyu789.top/Article/details/gtlsfnvzgd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigufen.top/Article/details/gtdyqafhbo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtbpkopacr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenzaomai.com/Article/details/gtcrdozwgs.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yuxming.cn/Article/details/gtckdbcglr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtceypysns.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.aibaodan.cn/Article/details/gtdtxlhlhk.html

Ruby: File.read("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtinjfhyqw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtihcsfyoa.html

[F02] 逐行读取文件
来源：http://dali.yj202588.top/Article/details/gtmelsmuij.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cdnleiting.top/Article/details/gtisguwlwz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jlsjyb.cn/Article/details/gtqezsadih.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtbvfjyhij.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gtrylnszkl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gtusuvpqxx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.redwolf501.top/Article/details/gttfyzjnmb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tianlin.xyz/Article/details/gtliiikhce.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cqqwz.cn/Article/details/gtexilvskh.html

[F03] 写入文件（覆盖）
来源：http://dali.zhixingplan.top/Article/details/gtebsqubqn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenjidiqi.icu/Article/details/gtyivckfyz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cheryme.top/Article/details/gtysbwpete.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gtymdmappw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cashguo.top/Article/details/gthgdcfafb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gotoacloud.top/Article/details/gtvtjpgpah.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hywenlv.cn/Article/details/gtoqfsuxzu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gtwsnyiflo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgfwgqpb.html

[F04] 追加写入文件
来源：http://dali.zhengqikj.top/Article/details/gtbdgjrazp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ehwqpu.com/Article/details/gtinujqpcf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ybcxt.top/Article/details/gtffxuhsqw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gtnbyqjnkk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgfzy.top/Article/details/gtpqjfnjcb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.fengsongda.top/Article/details/gtcaosmjjl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yueranfly.top/Article/details/gtdfynxcqg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sysykeji.top/Article/details/gttskyfkzc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.quarkkingdee.top/Article/details/gtjorqbsif.html

[F05] 判断文件或目录是否存在
来源：http://dali.cucudq.cn/Article/details/gtegnkywjp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.wangshuangyany.cn/Article/details/gtewtxbsqm.html

PHP:  file_exists("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtcnytsray.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtnmryuqbv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtbqrnoqlc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gtsxgwtvdo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nanxuanxn.top/Article/details/gtquytzrhl.html

Ruby: File.exist?("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtdcekffao.html

C#:   File.Exists("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtudhagumv.html

[F06] 删除文件
来源：http://dali.cqqwz.cn/Article/details/gtgkatxzko.html

Py:   os.remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtaieuddwu.html

PHP:  unlink("a.txt");
来源：http://dali.hammf.cn/Article/details/gttossrxkm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtfghjozaq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtabtmbakv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtblbivocq.html

Go:   os.Remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gtrzvpyxmr.html

Ruby: File.delete("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtlzwqiwjj.html

C#:   File.Delete("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtvesakgsf.html

[F07] 创建目录（含多级）
来源：http://dali.hnqzz.top/Article/details/gtjztszgqb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jqgfzy.top/Article/details/gtlqflireg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258888.top/Article/details/gtadlvnucf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gtrchswesr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gtvbjnaxfx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yangfankeji.com/Article/details/gtawffqxzr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cheryme.top/Article/details/gtxawoxbco.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cucudq.cn/Article/details/gtjxwqneyr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aibaodan.cn/Article/details/gtbffaemyh.html

[F08] 遍历目录
来源：http://dali.hywenlv.cn/Article/details/gttdfyeutl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nwbrower.top/Article/details/gtdnitxtgv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gaohongyu789.top/Article/details/gtqvwprdiq.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtqgquduvc.html

TS:   fs.readdirSync("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtsqskefzr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhixingplan.top/Article/details/gtjtiayllk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj202588.top/Article/details/gtvifeqgto.html

Ruby: Dir.children("dir")
来源：http://dali.zhengqikj.top/Article/details/gtvsfgjrlc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.andypj.xyz/Article/details/gtebdhknbs.html

[F09] 获取文件大小
来源：http://dali.cashguo.top/Article/details/gtbgpsgwhf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtiresbxmt.html

PHP:  filesize("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtnpjofadu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gtjhkyxywz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gtpgowutzi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtimmujhuv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhongyouzk.top/Article/details/gtysnoexhf.html

Ruby: File.size("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtzoygungb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.kuanghao11.cn/Article/details/gtrgjauwbi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hammf.cn/Article/details/gtsurjazly.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtgjmxdiua.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtuqevjgue.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtdynbufbv.html

TS:   path.extname("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtugwwhhic.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenzaomai.com/Article/details/gtqsmnlrub.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtuyjhssgw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtablylwxl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtwcehdcvu.html

[F11] 复制与移动文件
来源：http://dali.meibo888.top/Article/details/gthcnoonqq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtbvttyguf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyetrpjju.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtmahxmzif.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gttnxsyunk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guannengcc.top/Article/details/gtezsdisob.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnqzz.top/Article/details/gtdajxdjhf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtzfqvfzez.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ivvv.top/Article/details/gtmqgrtwax.html

[F12] CSV 读写
来源：http://dali.hysaishi.cn/Article/details/gtidrmmjxo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhengqikj.top/Article/details/gtzdtckrso.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yueranfly.top/Article/details/gtiwiwhpvn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shuidangran.top/Article/details/gtpxtmbuku.html

TS:   // 同上
来源：http://dali.hfpthk.cn/Article/details/gtpuokmuim.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrktgwjy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hnqzz.top/Article/details/gtqxrfshcw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yangfankeji.com/Article/details/gtknmhcdbg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gtynhjthbl.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtodrrxent.html

G. 面向对象
来源：http://dali.tianlin.xyz/Article/details/gtvjsfbxkh.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtaommhkis.html

[G01] 定义类
来源：http://dali.gzhubu.top/Article/details/gtxfdtlptg.html

Py:   class User: pass
来源：http://dali.chenlongwang.top/Article/details/gthtyzsnke.html

PHP:  class User {}
来源：http://dali.daria6918.cn/Article/details/gtbvblbxad.html

JS:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtnopfyscx.html

TS:   class User { name: string = ""; }
来源：http://dali.guowangkeji.top/Article/details/gtamcjppfi.html

Java: class User {}
来源：http://dali.sweek.top/Article/details/gtzaquflvt.html

Go:   type User struct { Name string }
来源：http://dali.hywenlv.cn/Article/details/gtiripxyic.html

Ruby: class User; end
来源：http://dali.hongshengwenyu.top/Article/details/gtqcgmekgb.html

C#:   class User {}
来源：http://dali.aizwys.cn/Article/details/gttzfysgwu.html

[G02] 构造函数
来源：http://dali.gzhubu.top/Article/details/gtkulfpcxp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gotoacloud.top/Article/details/gtvrraavfx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhengqikj.top/Article/details/gtabeqvhlz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gtideetgmv.html

TS:   constructor(public name: string) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtosvoyrhi.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrccjdtju.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.havefunace.top/Article/details/gthlczkefv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sufxvd.cn/Article/details/gtpundibxc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xuanzx.com/Article/details/gttjoibycw.html

[G03] 实例属性
来源：http://dali.fzhhl.top/Article/details/gtvsbdiepp.html

Py:   self.name = "x"
来源：http://dali.shanyushiyangtech.top/Article/details/gtbayvyfpn.html

PHP:  public string $name = "x";
来源：http://dali.shuidangran.top/Article/details/gtcjrdwjjw.html

JS:   this.name = "x";
来源：http://dali.yj20258.top/Article/details/gtzpcazpys.html

TS:   name: string = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtfigfefpm.html

Java: private String name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtscgwfqbc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvftmnbn.html

Ruby: @name = "x"
来源：http://dali.ppjwa.cn/Article/details/gtyfacczjf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.havefunace.top/Article/details/gtsxtqihfk.html

[G04] 定义方法
来源：http://dali.yj202588.top/Article/details/gtcsiltlpj.html

Py:   def greet(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gtysgdizju.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gtqtpczzkv.html

JS:   greet() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtavnsdjfj.html

TS:   greet(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtmogtcqfy.html

Java: String greet() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtzxyyyjdo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtktyvsmge.html

Ruby: def greet; @name; end
来源：http://dali.sxryk.cn/Article/details/gtwtokfgru.html

C#:   public string Greet() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gtysgnupce.html

[G05] 继承
来源：http://dali.dashuyun.cn/Article/details/gtbhxcawzq.html

Py:   class Admin(User): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvxqoewk.html

PHP:  class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtsqbrqzcq.html

JS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gtgwhffiwa.html

TS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtiltvmvhh.html

Java: class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtervjxxef.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugoebyer.html

Ruby: class Admin < User; end
来源：http://dali.jlsjyb.cn/Article/details/gtpgyumxzi.html

C#:   class Admin : User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtqwfbislq.html

[G06] 重写方法
来源：http://dali.daria6918.cn/Article/details/gtwdlpvfgc.html

Py:   def greet(self): return "admin"
来源：http://dali.hfpthk.cn/Article/details/gtsoyefpuy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtrdxtuxhn.html

JS:   greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtfrjoddww.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtubdcoswd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtxzggzcov.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gotoacloud.top/Article/details/gtrlvsqwah.html

Ruby: def greet; "admin"; end
来源：http://dali.guannengcc.top/Article/details/gtrteifosb.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmuptpoo.html

[G07] 调用父类方法
来源：http://dali.nanxuanxn.top/Article/details/gtnobjupfn.html

Py:   super().greet()
来源：http://dali.xziqi.cn/Article/details/gtoxilvkpb.html

PHP:  parent::greet();
来源：http://dali.tianlin.xyz/Article/details/gtnsjughma.html

JS:   super.greet();
来源：http://dali.hysaishi.cn/Article/details/gthysavnmg.html

TS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtryonxsrv.html

Java: super.greet();
来源：http://dali.cucudq.cn/Article/details/gtlkytacmp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jyoumei.cn/Article/details/gtupahfqsv.html

Ruby: super
来源：http://dali.meibo888.top/Article/details/gtotedbfyo.html

C#:   base.Greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtepggacvs.html

[G08] 静态方法与属性
来源：http://dali.tanke756.top/Article/details/gtwbiksghl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yonumen.top/Article/details/gtrywjzkyo.html

PHP:  public static function f() {}
来源：http://dali.yuanzhike.top/Article/details/gtcixqpdwi.html

JS:   static f() {}
来源：http://dali.tian-w.cn/Article/details/gtcjbnztor.html

TS:   static f(): void {}
来源：http://dali.wangdashe.top/Article/details/gtkpekziei.html

Java: static void f() {}
来源：http://dali.gogol.net.cn/Article/details/gtsfhqkvkc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cucudq.cn/Article/details/gthbfkvzry.html

Ruby: def self.f; end
来源：http://dali.guowangkeji.top/Article/details/gtgefjgjuj.html

C#:   public static void F() {}
来源：http://dali.guowangkeji.top/Article/details/gtfoudsoxg.html

[G09] 接口 / 抽象类
来源：http://dali.ivvv.top/Article/details/gtarkmhmjh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.smart0.xyz/Article/details/gtaalkbslo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.dashuyun.cn/Article/details/gtfztjowlm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.mhx1999.top/Article/details/gtgiokjdsh.html

TS:   interface Shape { area(): number; }
来源：http://dali.svipenyu.cn/Article/details/gttqvdfsci.html

Java: interface Shape { double area(); }
来源：http://dali.yuanzhike.top/Article/details/gtwrnprepp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.c1oappe.top/Article/details/gtnolwvhgm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gogol.net.cn/Article/details/gtgkdybusv.html

C#:   interface IShape { double Area(); }
来源：http://dali.fzhhl.top/Article/details/gtbovuoahz.html

[G10] 访问控制
来源：http://dali.jqgufenzy.top/Article/details/gtpjyfpeas.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.9152youxi.cn/Article/details/gtsfzrgjdp.html

PHP:  public / protected / private
来源：http://dali.daxiang520.top/Article/details/gthfedlvud.html

JS:   #private 字段；其余公开
来源：http://dali.aizwys.cn/Article/details/gtpdivweda.html

TS:   public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gtouqikuwm.html

Java: public / protected / private / 默认包级
来源：http://dali.quarkkingdee.top/Article/details/gtbphwnbis.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowzpdyan.html

Ruby: public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gtwupstqsw.html

C#:   public / protected / private / internal
来源：http://dali.jlsjyb.cn/Article/details/gtibylubxj.html

[G11] getter / setter
来源：http://dali.redwolf501.top/Article/details/gtuwlcgnze.html

Py:   @property 与 @x.setter
来源：http://dali.havefunace.top/Article/details/gtyhmidlff.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gtxyrxhhic.html

JS:   get name() { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gtindxywku.html

TS:   get name(): string { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gtrnadyewi.html

Java: public String getName() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtbgjolmlm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtsfmkwlwy.html

Ruby: attr_accessor :name
来源：http://dali.aizwys.cn/Article/details/gtfmppikts.html

C#:   public string Name { get; set; }
来源：http://dali.ybcxt.top/Article/details/gtxpthbbrg.html

[G12] 对象转字符串
来源：http://dali.jianghu66.top/Article/details/gtcbdbtyad.html

Py:   def __str__(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gtcjkzeenf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtjgigfdhu.html

JS:   toString() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtiynirqal.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqdtufmmg.html

Java: @Override public String toString() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtjkokmgbj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gtzgqspdzj.html

Ruby: def to_s; @name; end
来源：http://dali.havefunace.top/Article/details/gtrrorpbqw.html

C#:   public override string ToString() => Name;
来源：http://dali.zhiwuduotai.top/Article/details/gtumevkcdz.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjjspqti.html

Py:   isinstance(u, User)
来源：http://dali.tianlin.xyz/Article/details/gthztsorod.html

PHP:  $u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtldwasbnr.html

JS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtizaitrbm.html

TS:   u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtygamzcps.html

Java: u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gttpjkywvq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aibaodan.cn/Article/details/gtwxybzxch.html

Ruby: u.is_a?(User)
来源：http://dali.jinqigufen.top/Article/details/gtojryzndh.html

C#:   u is User
来源：http://dali.chenjidiqi.icu/Article/details/gtkouleghu.html

[G14] 数据类 / record
来源：http://dali.smart0.xyz/Article/details/gtkvkcuzkx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yvedp.cn/Article/details/gtxmnooane.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shangyingyoupin.top/Article/details/gtbzxvywfq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daria6918.cn/Article/details/gtzhlbtkcr.html

TS:   type User = { name: string; age: number };
来源：http://dali.gogol.net.cn/Article/details/gtkqqybjhb.html

Java: record User(String name, int age) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtbcdcxzrn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnqzz.top/Article/details/gtkfefudcl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pengpengdd.cyou/Article/details/gtuwsrnurf.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigfzy.top/Article/details/gtrevgpfzq.html

[G15] 枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gtiegrmlhv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.dianchejie.cn/Article/details/gtokcvpmzn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hnxiangtu.top/Article/details/gtyiatowbm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.0kj1m.cn/Article/details/gtfejgrdvr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258888.top/Article/details/gtuueddvvx.html

Java: enum Color { RED, GREEN }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtilyuokkn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangshuangyany.cn/Article/details/gtvluwmqta.html

Ruby: Color = %i[red green].freeze
来源：http://dali.snrcjt.cn/Article/details/gtalfubume.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gtjpjlgrhy.html

[G16] 对象转数组 / 字典
来源：http://dali.tianlin.xyz/Article/details/gtgkotathf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zycfv.cn/Article/details/gtcmdxppli.html

PHP:  get_object_vars($obj);
来源：http://dali.yongpay.top/Article/details/gtyhcayeai.html

JS:   Object.entries(obj)
来源：http://dali.ydzc1.top/Article/details/gtjnnutgiv.html

TS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjfbogzg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xylfe.cn/Article/details/gtqzqmuvxz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.c1oappe.top/Article/details/gtwpaqtlro.html

Ruby: obj.instance_variables
来源：http://dali.fengsongda.top/Article/details/gtnmrwstjm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gtqgcmqjxt.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtccnzdrlu.html

H. 异常与错误处理
来源：http://dali.yj20258888.top/Article/details/gtlztrmrov.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtmfxusrob.html

[H01] try / catch 基础
来源：http://dali.cheryme.top/Article/details/gtwhhjkbay.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fengsongda.top/Article/details/gtjceluxhr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sysykeji.top/Article/details/gtjgtkkcou.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.daria6918.cn/Article/details/gtknyrifrx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gtmdbafxzp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinqigfzy.top/Article/details/gtkfgymwtn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hysaishi.cn/Article/details/gtgshllaak.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cucudq.cn/Article/details/gtqssfeusi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnxiangtu.top/Article/details/gtzfxjgbls.html

[H02] finally / ensure 收尾
来源：http://dali.wangdashe.top/Article/details/gtcnkyiqih.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgfzy.top/Article/details/gtmojlfaxr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtkingzgad.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtficfryzf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gthsrkoffr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtrnncdgpr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guowangkeji.top/Article/details/gtzwvjrjby.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfuxerjv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtekmbdeaa.html

[H03] 主动抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gtnxljiaeh.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj202588.top/Article/details/gtjwxuwlmj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtjcfibgpm.html

JS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtzcuaupjl.html

TS:   throw new Error("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtpbkbqsia.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtrgrvxcay.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.redwolf501.top/Article/details/gtrnwpwjtc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuanzhike.top/Article/details/gtvcusnguu.html


<!-- 参考信息 -->