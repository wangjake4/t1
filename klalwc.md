代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtnptrftzb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenlongwang.top/Article/details/gtwavrqzul.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tanke756.top/Article/details/gtmaabfugt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtneryenag.html

[E22] 字节长度与字符长度
来源：http://dali.redwolf501.top/Article/details/gtxafogjar.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ehwqpu.com/Article/details/gtxlnbwqrj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gttzedpxjv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gtxrlffhbh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gthsfjjklm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsxusuqf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hammf.cn/Article/details/gtijeyphxl.html

Ruby: s.bytesize;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtnbynuwmn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tanke756.top/Article/details/gtasintgte.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtaqrpvotv.html

F. 文件与目录
来源：http://dali.shzxlz.cn/Article/details/gthxdjwapg.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtqmntymgz.html

[F01] 读取整个文件
来源：http://dali.jiagoushi.top/Article/details/gtzpdxbapx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xziqi.cn/Article/details/gtvporyqhw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtpusowwpe.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yangfankeji.com/Article/details/gtllkqwnix.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yvedp.cn/Article/details/gtrnqxmnfw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtqlaweerk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.havefunace.top/Article/details/gtknyaades.html

Ruby: File.read("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtfkgwtcjj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtrdfzxagb.html

[F02] 逐行读取文件
来源：http://dali.zhongyouzk.top/Article/details/gtotqvtgzw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dashuyun.cn/Article/details/gtioujiwfm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sysykeji.top/Article/details/gtkamcbdwm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gtwyllqywu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cucudq.cn/Article/details/gtonuadcti.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ywan-chungtsiang.top/Article/details/gterzjufne.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pengpengdd.cyou/Article/details/gtkcmwdfmt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jqgufenzy.top/Article/details/gtvmtfyjxz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gteuhphdfc.html

[F03] 写入文件（覆盖）
来源：http://dali.nwbrower.top/Article/details/gtpwjusmen.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ydzc1.top/Article/details/gtsmiifazb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nanxinkj.top/Article/details/gtzdvjxhmd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guannengcc.top/Article/details/gtwihkbycl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gtuihfwixq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hywenlv.cn/Article/details/gtpeksclyr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pengpengdd.cyou/Article/details/gtazcofpjl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuevqytdl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gtxynrlnzg.html

[F04] 追加写入文件
来源：http://dali.316326.xyz/Article/details/gtcziioywh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtufdrdhgp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hongshengwenyu.top/Article/details/gtdaahzrht.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gtdjgnmqog.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aibaodan.cn/Article/details/gtopdggmyr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hfpthk.cn/Article/details/gtmelyxypm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.birdmap.top/Article/details/gtpqwvccdf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gotoacloud.top/Article/details/gtujzoemsa.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sysykeji.top/Article/details/gttoamyoao.html

[F05] 判断文件或目录是否存在
来源：http://dali.snrcjt.cn/Article/details/gtsohheyny.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnxiangtu.top/Article/details/gtpuresqtg.html

PHP:  file_exists("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtyklhacwm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtffcirftv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtfrzjvqfe.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtmaajexti.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.dianchejie.cn/Article/details/gtlaztgnvd.html

Ruby: File.exist?("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtpsimcuae.html

C#:   File.Exists("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtzvjnmqye.html

[F06] 删除文件
来源：http://dali.birdmap.top/Article/details/gtxyydmdke.html

Py:   os.remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtwppxxyin.html

PHP:  unlink("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtkdtkusjr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtprpjnkjf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtxtxmvyqy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtcywsecwt.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtkhmevicj.html

Ruby: File.delete("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtxcftceui.html

C#:   File.Delete("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtljspsduz.html

[F07] 创建目录（含多级）
来源：http://dali.iojbl.cn/Article/details/gtwqbvnakt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhixingplan.top/Article/details/gtoomfnxsb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.birdmap.top/Article/details/gtgpsvesdb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dianchejie.cn/Article/details/gtkhzrvnkx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gtxouqkmrk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shuidangran.top/Article/details/gtllqigapi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yueranfly.top/Article/details/gtspigfavt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.havefunace.top/Article/details/gtlzdtvwtm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cashguo.top/Article/details/gtuwpekjac.html

[F08] 遍历目录
来源：http://dali.guowangkeji.top/Article/details/gtjbewygol.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hysaishi.cn/Article/details/gtlsbzkjnd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jlsjyb.cn/Article/details/gtksnddudh.html

JS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gtuvmkqzal.html

TS:   fs.readdirSync("dir")
来源：http://dali.xziqi.cn/Article/details/gtdowthhqq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhiwuduotai.top/Article/details/gtljrlgabe.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.redwolf501.top/Article/details/gtlpaewaig.html

Ruby: Dir.children("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtcbiinzah.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangdashe.top/Article/details/gtttymdjgz.html

[F09] 获取文件大小
来源：http://dali.cqqwz.cn/Article/details/gtdbmfplyl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtaildtfeb.html

PHP:  filesize("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtdxizxlmz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gtvfwzhzam.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gtdblnzsrm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtlsrshtxc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dashuyun.cn/Article/details/gtowdnhapd.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtdpsejcvw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.316326.xyz/Article/details/gteonjgufm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zdqjudy.top/Article/details/gtcfmidylt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtezryuxtq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtdhdngqvc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtcuahydty.html

TS:   path.extname("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtpkknrhoi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.andypj.xyz/Article/details/gtkueohfzx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtbqiavcxc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtokzjqkgr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtrtomzkgy.html

[F11] 复制与移动文件
来源：http://dali.daxiang520.top/Article/details/gttdxjgbxd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gthsjcfmuh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xinyue.icu/Article/details/gtuenkdltr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gthhxbiqbc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtestyapfr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gtffgvxhzc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yangfankeji.com/Article/details/gtgkvinbsa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtexelqnba.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnxiangtu.top/Article/details/gtmrjuskmv.html

[F12] CSV 读写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxvvxoje.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jqgufenzy.top/Article/details/gtwcznxpnx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nanxinkj.top/Article/details/gtxvbquubb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hywenlv.cn/Article/details/gtncpdzuhe.html

TS:   // 同上
来源：http://dali.gogol.net.cn/Article/details/gtkorgradh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdegjhhh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jlsjyb.cn/Article/details/gtlqvnidnx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yueranfly.top/Article/details/gtraqaavms.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.snrcjt.cn/Article/details/gtclffgqxb.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtbhcuawnh.html

G. 面向对象
来源：http://dali.9152youxi.cn/Article/details/gtzailtwuw.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtwzpxwgls.html

[G01] 定义类
来源：http://dali.iojbl.cn/Article/details/gtfxivfpwk.html

Py:   class User: pass
来源：http://dali.hongshengwenyu.top/Article/details/gtvkpvdqkm.html

PHP:  class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtalxmzjwu.html

JS:   class User {}
来源：http://dali.cashguo.top/Article/details/gteesbcjfk.html

TS:   class User { name: string = ""; }
来源：http://dali.iojbl.cn/Article/details/gtnnvgxiud.html

Java: class User {}
来源：http://dali.bjfxy.top/Article/details/gtwwsbwren.html

Go:   type User struct { Name string }
来源：http://dali.shzxlz.cn/Article/details/gtevpisixb.html

Ruby: class User; end
来源：http://dali.wangdashe.top/Article/details/gteetsykze.html

C#:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtvobanbky.html

[G02] 构造函数
来源：http://dali.yuxming.cn/Article/details/gtjskyybho.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenjidiqi.icu/Article/details/gtaydautfj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jyoumei.cn/Article/details/gtqezwsmhf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkaohpnwb.html

TS:   constructor(public name: string) {}
来源：http://dali.hnxiangtu.top/Article/details/gtedecxdjw.html

Java: User(String name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gtnkzprvfl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tianlin.xyz/Article/details/gtoltpaamk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenzaomai.com/Article/details/gtbgpnazbj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.9152youxi.cn/Article/details/gtwvechpgy.html

[G03] 实例属性
来源：http://dali.ivvv.top/Article/details/gtqtmoifep.html

Py:   self.name = "x"
来源：http://dali.ydzc1.top/Article/details/gtkamcqvhv.html

PHP:  public string $name = "x";
来源：http://dali.aibaodan.cn/Article/details/gtdemkrvsl.html

JS:   this.name = "x";
来源：http://dali.yvedp.cn/Article/details/gtciytzatk.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjkjizjp.html

Java: private String name;
来源：http://dali.fzhhl.top/Article/details/gtqggtzkml.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yueranfly.top/Article/details/gtureytkvo.html

Ruby: @name = "x"
来源：http://dali.chenlongwang.top/Article/details/gtmtcqsvla.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xinyue.icu/Article/details/gtjtmxcudh.html

[G04] 定义方法
来源：http://dali.shangyingyoupin.top/Article/details/gtlnacrzzb.html

Py:   def greet(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gtxusbxppg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtgaszedjm.html

JS:   greet() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gteyhfmmde.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtjwydxdox.html

Java: String greet() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtdhiirvln.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gtenxpmfob.html

Ruby: def greet; @name; end
来源：http://dali.jqgfzy.top/Article/details/gtoqokuvyz.html

C#:   public string Greet() => Name;
来源：http://dali.aizwys.cn/Article/details/gtgnfpeqpd.html

[G05] 继承
来源：http://dali.fengsongda.top/Article/details/gtwwufxmft.html

Py:   class Admin(User): pass
来源：http://dali.hnqzz.top/Article/details/gtnsqcvdpn.html

PHP:  class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtgvdpykcs.html

JS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtmwqkbcfe.html

TS:   class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtkmituwgd.html

Java: class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtoyyltlws.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zdqjudy.top/Article/details/gtcgvxyrmq.html

Ruby: class Admin < User; end
来源：http://dali.fengsongda.top/Article/details/gtklskviso.html

C#:   class Admin : User {}
来源：http://dali.chenzaomai.com/Article/details/gtcwnufhsl.html

[G06] 重写方法
来源：http://dali.mhx1999.top/Article/details/gteixrwhhg.html

Py:   def greet(self): return "admin"
来源：http://dali.ppjwa.cn/Article/details/gtmmqtqouw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtaraneoaq.html

JS:   greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtbtxejejw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtbrngjzif.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtputmiznd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.fzhhl.top/Article/details/gtayjjiuuk.html

Ruby: def greet; "admin"; end
来源：http://dali.nanxuanxn.top/Article/details/gtcmacnbao.html

C#:   public override string Greet() => "admin";
来源：http://dali.xinyue.icu/Article/details/gtskbfttgt.html

[G07] 调用父类方法
来源：http://dali.yuxming.cn/Article/details/gtddngyxze.html

Py:   super().greet()
来源：http://dali.hammf.cn/Article/details/gtgvyouzkq.html

PHP:  parent::greet();
来源：http://dali.hysaishi.cn/Article/details/gtpjuwcmox.html

JS:   super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gttehexjam.html

TS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gtneatnhel.html

Java: super.greet();
来源：http://dali.dianchejie.cn/Article/details/gtgbikgzlu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shuidangran.top/Article/details/gtigtpqeqo.html

Ruby: super
来源：http://dali.sufxvd.cn/Article/details/gttfkznovr.html

C#:   base.Greet();
来源：http://dali.zhoulong.xyz/Article/details/gtluxrobvv.html

[G08] 静态方法与属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoexkbsjb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hysaishi.cn/Article/details/gtdrsezbwd.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gthcsnbyvh.html

JS:   static f() {}
来源：http://dali.meibo888.top/Article/details/gtsrblurmi.html

TS:   static f(): void {}
来源：http://dali.wangdashe.top/Article/details/gtukhnyrgg.html

Java: static void f() {}
来源：http://dali.nanxinkj.top/Article/details/gtubdeyiby.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnqzz.top/Article/details/gtgeooopue.html

Ruby: def self.f; end
来源：http://dali.0kj1m.cn/Article/details/gtegwflore.html

C#:   public static void F() {}
来源：http://dali.tanke756.top/Article/details/gtiebgxuor.html

[G09] 接口 / 抽象类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkannprci.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hnxiangtu.top/Article/details/gtncylbyev.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xziqi.cn/Article/details/gtmmstoqzx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hammf.cn/Article/details/gtbssqmsoy.html

TS:   interface Shape { area(): number; }
来源：http://dali.cdnleiting.top/Article/details/gtzragdwys.html

Java: interface Shape { double area(); }
来源：http://dali.havefunace.top/Article/details/gtyknzskkz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hywenlv.cn/Article/details/gtpvpeaatw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gtzfgglzng.html

C#:   interface IShape { double Area(); }
来源：http://dali.ydzc1.top/Article/details/gtebgqgoyv.html

[G10] 访问控制
来源：http://dali.fengsongda.top/Article/details/gtcjvlzuwx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hysaishi.cn/Article/details/gtjalqjeef.html

PHP:  public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gtpyvhxizf.html

JS:   #private 字段；其余公开
来源：http://dali.ppjwa.cn/Article/details/gtyywwzbcd.html

TS:   public / protected / private
来源：http://dali.ydzc1.top/Article/details/gtmokwhuju.html

Java: public / protected / private / 默认包级
来源：http://dali.hfpthk.cn/Article/details/gtumvjdwoa.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nanxuanxn.top/Article/details/gtypyliahu.html

Ruby: public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtecoubnqu.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvzflrum.html

[G11] getter / setter
来源：http://dali.tanke756.top/Article/details/gtukqwcphy.html

Py:   @property 与 @x.setter
来源：http://dali.fzhhl.top/Article/details/gtdxfzycik.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtfadbcguv.html

JS:   get name() { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gtayjplwtg.html

TS:   get name(): string { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gtgbvmldge.html

Java: public String getName() { return name; }
来源：http://dali.cashguo.top/Article/details/gtmizcfnrw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gtuukrudob.html

Ruby: attr_accessor :name
来源：http://dali.fzhhl.top/Article/details/gtxvbztluc.html

C#:   public string Name { get; set; }
来源：http://dali.feifeiyinyue.top/Article/details/gtuuppwivb.html

[G12] 对象转字符串
来源：http://dali.c1oappe.top/Article/details/gtvyehoaoe.html

Py:   def __str__(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gtqxororvo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtuwwvwhwp.html

JS:   toString() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gthnumyswl.html

TS:   toString(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtxqzdzqff.html

Java: @Override public String toString() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsknqscki.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gtswxsxnuy.html

Ruby: def to_s; @name; end
来源：http://dali.fengsongda.top/Article/details/gtwumsbisk.html

C#:   public override string ToString() => Name;
来源：http://dali.yonumen.top/Article/details/gtjduktbue.html

[G13] 判断对象类型
来源：http://dali.jqgufenzy.top/Article/details/gtcqbpgcwl.html

Py:   isinstance(u, User)
来源：http://dali.hfpthk.cn/Article/details/gtkzdefgaq.html

PHP:  $u instanceof User
来源：http://dali.hammf.cn/Article/details/gtnfueqtpj.html

JS:   u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtboelzuko.html

TS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtfkofjthl.html

Java: u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtsdmorita.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.guowangkeji.top/Article/details/gthmojhjke.html

Ruby: u.is_a?(User)
来源：http://dali.xinyue.icu/Article/details/gtcfkzixex.html

C#:   u is User
来源：http://dali.birdmap.top/Article/details/gttuwfgefr.html

[G14] 数据类 / record
来源：http://dali.ehwqpu.com/Article/details/gtvuxmlhtu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gzhubu.top/Article/details/gtkclltkuo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jlsjyb.cn/Article/details/gtfzguvmdo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.andypj.xyz/Article/details/gtkyjfsfbr.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhongyouzk.top/Article/details/gtvsquhwfr.html

Java: record User(String name, int age) {}
来源：http://dali.redwolf501.top/Article/details/gtrxlchvnj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgufenzy.top/Article/details/gtecasiwye.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zdqjudy.top/Article/details/gtcaskvtcp.html

C#:   record User(string Name, int Age);
来源：http://dali.zhengqikj.top/Article/details/gtgrcqdrho.html

[G15] 枚举
来源：http://dali.pengpengdd.cyou/Article/details/gtvtklkdbc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shangyingyoupin.top/Article/details/gtrphrhsvh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.aibaodan.cn/Article/details/gtsvwfrlsj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinghuilouyu.cn/Article/details/gtupucsfty.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtukrcbgpw.html

Java: enum Color { RED, GREEN }
来源：http://dali.cqqwz.cn/Article/details/gtozxqdfly.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hfpthk.cn/Article/details/gtfvlwodvq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xuetiantiany.cn/Article/details/gtljvesbvj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtilpgtbme.html

[G16] 对象转数组 / 字典
来源：http://dali.xziqi.cn/Article/details/gtfylzfhlq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj202588.top/Article/details/gtijanmetj.html

PHP:  get_object_vars($obj);
来源：http://dali.nanxuanxn.top/Article/details/gtzsnhbfts.html

JS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gtpadxnqhf.html

TS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gtzoxylxdl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.9152youxi.cn/Article/details/gtlyapltkz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgfzy.top/Article/details/gtkyjigmsm.html

Ruby: obj.instance_variables
来源：http://dali.iojbl.cn/Article/details/gtcvvctcqu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhixingplan.top/Article/details/gtzahlxdfm.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtokrmdinz.html

H. 异常与错误处理
来源：http://dali.hywenlv.cn/Article/details/gtacxjwyay.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtdbbxwgbn.html

[H01] try / catch 基础
来源：http://dali.wangshuangyany.cn/Article/details/gtopivfccd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shzxlz.cn/Article/details/gtroskrqwq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gotoacloud.top/Article/details/gtxfjpszth.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gtcvpgysup.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gtepvndarq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.316326.xyz/Article/details/gtmbejlmhe.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yvedp.cn/Article/details/gtodatofnq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.guannengcc.top/Article/details/gtcnrjystt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.fzhhl.top/Article/details/gtqynhhtly.html

[H02] finally / ensure 收尾
来源：http://dali.ybcxt.top/Article/details/gtzxwpexep.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhoulong.xyz/Article/details/gtoeitwure.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcsavarbx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gttnshnstj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtniwnrfbl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtkwmetpxo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.wangshuangyany.cn/Article/details/gtticpfprj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.kuanghao11.cn/Article/details/gtcgvdqwcd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtayishhny.html

[H03] 主动抛出异常
来源：http://dali.shuidangran.top/Article/details/gtncsivgng.html

Py:   raise ValueError("错误信息")
来源：http://dali.quarkkingdee.top/Article/details/gtnqlokmxi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtirxfaybi.html

JS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwruxrxb.html

TS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtxdoyudfc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtkwwmbwpz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sweek.top/Article/details/gtwxiwidso.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258888.top/Article/details/gtpsrxlrku.html


<!-- 参考信息 -->