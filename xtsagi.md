代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfuwlkzhb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtfknbhfcs.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gtviixqnvn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtmtwjzxdp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtnkjhgwjv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cashguo.top/Article/details/gtskdlxuqs.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gturiuretk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gttixaddwo.html

[E22] 字节长度与字符长度
来源：http://dali.aibaodan.cn/Article/details/gtfztxlkuc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yangfankeji.com/Article/details/gtwbqmcqsa.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gttylnkltu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gtbeuuftwa.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gthikvqico.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.feifeiyinyue.top/Article/details/gtblwuxyqy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj202588.top/Article/details/gtnqavpqyn.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gtktmbvmww.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ydzc1.top/Article/details/gthmgwmnhh.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtlrosbrvd.html

F. 文件与目录
来源：http://dali.zdqjudy.top/Article/details/gtejjfjtrt.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtryucoscz.html

[F01] 读取整个文件
来源：http://dali.sweek.top/Article/details/gtrgnohphz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pycfn.com/Article/details/gtlhqzbhni.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtcdyndlct.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cdnleiting.top/Article/details/gtxqyiatgf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtbjkgfk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtyiyooymq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj20258888.top/Article/details/gtfpfdqrtk.html

Ruby: File.read("a.txt")
来源：http://dali.cheryme.top/Article/details/gtuhwoslvc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtzcomxsqx.html

[F02] 逐行读取文件
来源：http://dali.redwolf501.top/Article/details/gtpypixsfb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sxryk.cn/Article/details/gtbldzlnuo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj20258.top/Article/details/gthrsrynsd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtpvjfgphk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jyoumei.cn/Article/details/gtszevsalz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yonumen.top/Article/details/gtjjwxtewo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tian-w.cn/Article/details/gtwcqxxyhy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fengsongda.top/Article/details/gthbnivmkk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.mhx1999.top/Article/details/gtoaakhgei.html

[F03] 写入文件（覆盖）
来源：http://dali.yj20258.top/Article/details/gtwzmikhjf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenlongwang.top/Article/details/gtynnwilwn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gtojnymtpw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sysykeji.top/Article/details/gtsfrswugj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtkopbbvna.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.dianchejie.cn/Article/details/gtsucezugg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.meibo888.top/Article/details/gtetktctoz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xinyue.icu/Article/details/gtmcxanexs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gotoacloud.top/Article/details/gttkineemk.html

[F04] 追加写入文件
来源：http://dali.cucudq.cn/Article/details/gtaxelmdrq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jyoumei.cn/Article/details/gtrabdkfgg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.redwolf501.top/Article/details/gtdrfgcfsd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gtkmtzaemw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xziqi.cn/Article/details/gtoqlugsic.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj202588.top/Article/details/gtjbndggja.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hysaishi.cn/Article/details/gtiumjjslp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xuetiantiany.cn/Article/details/gtmeqlqlny.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangshuangyany.cn/Article/details/gtmvhoakkp.html

[F05] 判断文件或目录是否存在
来源：http://dali.jqgufenzy.top/Article/details/gtaiarwlqi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.daria6918.cn/Article/details/gtrtboxsmu.html

PHP:  file_exists("a.txt");
来源：http://dali.ivvv.top/Article/details/gtydfrvops.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtpyhsvyds.html

TS:   fs.existsSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtdbjtyonn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtmogkncpk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shuidangran.top/Article/details/gtftykogxh.html

Ruby: File.exist?("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtwwnptidl.html

C#:   File.Exists("a.txt")
来源：http://dali.yj20258.top/Article/details/gtijjkdtux.html

[F06] 删除文件
来源：http://dali.dianchejie.cn/Article/details/gtrzbyurbh.html

Py:   os.remove("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtlfyhqnzc.html

PHP:  unlink("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtmjtpsjrz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtsgahtwdz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtavmbjhbu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtwnoamoyx.html

Go:   os.Remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtqqinrofe.html

Ruby: File.delete("a.txt")
来源：http://dali.cheryme.top/Article/details/gtyvmbwxaj.html

C#:   File.Delete("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtjoxycdgv.html

[F07] 创建目录（含多级）
来源：http://dali.tian-w.cn/Article/details/gtfllwuheh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hfpthk.cn/Article/details/gtoplijvht.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guowangkeji.top/Article/details/gtjkasrvqe.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gtiyzzdeok.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gtfgitwygk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.redwolf501.top/Article/details/gtrroyjifv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.mhx1999.top/Article/details/gthjosxyrk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.wangshuangyany.cn/Article/details/gtmdnzicfx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guowangkeji.top/Article/details/gtnsczaqhr.html

[F08] 遍历目录
来源：http://dali.jinqigfzy.top/Article/details/gtenljfjty.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jlsjyb.cn/Article/details/gtgbmrgfji.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenjidiqi.icu/Article/details/gtsbqsmikq.html

JS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gtuxbivirs.html

TS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gtewoqmscn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqilmyru.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cdnleiting.top/Article/details/gtumsjsxei.html

Ruby: Dir.children("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgeenmnwy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuxming.cn/Article/details/gtruxlaopr.html

[F09] 获取文件大小
来源：http://dali.yanxiufei.cn/Article/details/gtnnefcmzt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtajbjcvui.html

PHP:  filesize("a.txt");
来源：http://dali.havefunace.top/Article/details/gtzerzpwzj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.dashuyun.cn/Article/details/gtvhnujxaw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gtnocblilc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gthjdzydvu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.haohaochexian.top/Article/details/gthwnjxuyd.html

Ruby: File.size("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtwrissaqu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.dashuyun.cn/Article/details/gtnhwffowq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxinkj.top/Article/details/gtgqmqbzna.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtqzcocndz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtpkssjvlp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtrjeckqjd.html

TS:   path.extname("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtwpwougqw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xziqi.cn/Article/details/gtcsibetve.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtpibhyatp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtdxjdwpel.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtusmqefih.html

[F11] 复制与移动文件
来源：http://dali.nwbrower.top/Article/details/gtpppwqeeu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtrhesvvrc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtleqfxpam.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtadbrxjvy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtmklyjcbi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.smart0.xyz/Article/details/gtqnfkkfxi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.0kj1m.cn/Article/details/gthzzgmraj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtzajnmjxv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtavdivubr.html

[F12] CSV 读写
来源：http://dali.gzhubu.top/Article/details/gtrcuhskfv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shzxlz.cn/Article/details/gtarxcnhjf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuetiantiany.cn/Article/details/gtudwghvul.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258.top/Article/details/gtsqtuvnki.html

TS:   // 同上
来源：http://dali.yuxming.cn/Article/details/gtcluhabwq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cashguo.top/Article/details/gtvcutogsi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hysaishi.cn/Article/details/gterieahik.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cheryme.top/Article/details/gtxvrkbfam.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.0kj1m.cn/Article/details/gtbsnxjtmk.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtrrhgthrg.html

G. 面向对象
来源：http://dali.yj20258.top/Article/details/gtnpcbnynh.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtjjfcugeh.html

[G01] 定义类
来源：http://dali.shanyushiyangtech.top/Article/details/gtoljellyj.html

Py:   class User: pass
来源：http://dali.xziqi.cn/Article/details/gtadpfjojb.html

PHP:  class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtatapfwmz.html

JS:   class User {}
来源：http://dali.yuanzhike.top/Article/details/gtixdlsuww.html

TS:   class User { name: string = ""; }
来源：http://dali.hongshengwenyu.top/Article/details/gtqhbudjbu.html

Java: class User {}
来源：http://dali.shzxlz.cn/Article/details/gtpuwokmit.html

Go:   type User struct { Name string }
来源：http://dali.jqgufenzy.top/Article/details/gtxshefsce.html

Ruby: class User; end
来源：http://dali.iojbl.cn/Article/details/gtletfpzqv.html

C#:   class User {}
来源：http://dali.ivvv.top/Article/details/gtyxgikyfo.html

[G02] 构造函数
来源：http://dali.gotoacloud.top/Article/details/gteatoolht.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhengqikj.top/Article/details/gtrrogdybc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmidypyz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gtoexradik.html

TS:   constructor(public name: string) {}
来源：http://dali.sweek.top/Article/details/gtdqjihhmu.html

Java: User(String name) { this.name = name; }
来源：http://dali.nwbrower.top/Article/details/gtnyxpbxvy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hongshengwenyu.top/Article/details/gthsqiqogx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dashuyun.cn/Article/details/gtbcgronbd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cashguo.top/Article/details/gtyzjwspdn.html

[G03] 实例属性
来源：http://dali.zdqjudy.top/Article/details/gtgjlodbvu.html

Py:   self.name = "x"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqbhnevpp.html

PHP:  public string $name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtluiiojvq.html

JS:   this.name = "x";
来源：http://dali.yonumen.top/Article/details/gtdnlndgzr.html

TS:   name: string = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtmotreqaa.html

Java: private String name;
来源：http://dali.jinqigufen.top/Article/details/gtlmrmqscu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gtspvibtcc.html

Ruby: @name = "x"
来源：http://dali.hnqzz.top/Article/details/gtibgbpsvk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guannengcc.top/Article/details/gtavbchbll.html

[G04] 定义方法
来源：http://dali.quarkkingdee.top/Article/details/gtdoosvupb.html

Py:   def greet(self): return self.name
来源：http://dali.fengsongda.top/Article/details/gtgyzetkqh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gtvjkluttf.html

JS:   greet() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gttfpypqsu.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtfpwmsloz.html

Java: String greet() { return name; }
来源：http://dali.aizwys.cn/Article/details/gtpjmcxhsr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtrrfnlukx.html

Ruby: def greet; @name; end
来源：http://dali.cashguo.top/Article/details/gtxkxpoiew.html

C#:   public string Greet() => Name;
来源：http://dali.shzxlz.cn/Article/details/gtzaipoiin.html

[G05] 继承
来源：http://dali.quarkkingdee.top/Article/details/gtlfpligeg.html

Py:   class Admin(User): pass
来源：http://dali.kuanghao11.cn/Article/details/gtrifzzoey.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtgidmxiwt.html

JS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtmzmzcqfw.html

TS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtqfwvxunp.html

Java: class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtkcxlvpro.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xinyue.icu/Article/details/gtytxjiwkv.html

Ruby: class Admin < User; end
来源：http://dali.wangdashe.top/Article/details/gtntczjghi.html

C#:   class Admin : User {}
来源：http://dali.shzxlz.cn/Article/details/gtabhxafaw.html

[G06] 重写方法
来源：http://dali.fengsongda.top/Article/details/gtqtfesywt.html

Py:   def greet(self): return "admin"
来源：http://dali.andypj.xyz/Article/details/gtawimfses.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtrefczrhk.html

JS:   greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gtgtdkqubm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtsrgtrjii.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtsnaychxb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.feifeiyinyue.top/Article/details/gtxirsjmkx.html

Ruby: def greet; "admin"; end
来源：http://dali.dianchejie.cn/Article/details/gtpivoqvej.html

C#:   public override string Greet() => "admin";
来源：http://dali.hywenlv.cn/Article/details/gtlahfzwib.html

[G07] 调用父类方法
来源：http://dali.cqqwz.cn/Article/details/gtfdikrtoj.html

Py:   super().greet()
来源：http://dali.yuxming.cn/Article/details/gtpbjqbpbf.html

PHP:  parent::greet();
来源：http://dali.jyoumei.cn/Article/details/gtuhxdmuoy.html

JS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gtlwggbucq.html

TS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gtibvdcuvg.html

Java: super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtgxcpvgxz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zdqjudy.top/Article/details/gtzbnvhawf.html

Ruby: super
来源：http://dali.cashguo.top/Article/details/gtrxdymxjz.html

C#:   base.Greet();
来源：http://dali.hnxiangtu.top/Article/details/gtciaomzjw.html

[G08] 静态方法与属性
来源：http://dali.tanke756.top/Article/details/gtvduhrvez.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ivvv.top/Article/details/gtmmsdzjvf.html

PHP:  public static function f() {}
来源：http://dali.yj202588.top/Article/details/gtxudgkjjl.html

JS:   static f() {}
来源：http://dali.snrcjt.cn/Article/details/gtkwqsyznp.html

TS:   static f(): void {}
来源：http://dali.yongpay.top/Article/details/gtjwshhndw.html

Java: static void f() {}
来源：http://dali.cdnleiting.top/Article/details/gtjgbhyziz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.c1oappe.top/Article/details/gtdjtqerbh.html

Ruby: def self.f; end
来源：http://dali.sxryk.cn/Article/details/gtfhgmtemp.html

C#:   public static void F() {}
来源：http://dali.yonumen.top/Article/details/gtjhihjnvd.html

[G09] 接口 / 抽象类
来源：http://dali.guannengcc.top/Article/details/gtahzjuevt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hywenlv.cn/Article/details/gtqwgoniky.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guowangkeji.top/Article/details/gtmfyyncip.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.andypj.xyz/Article/details/gtefaoqyba.html

TS:   interface Shape { area(): number; }
来源：http://dali.yonumen.top/Article/details/gtvymupxxr.html

Java: interface Shape { double area(); }
来源：http://dali.jiagoushi.top/Article/details/gtejnccteg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dashuyun.cn/Article/details/gtkiobzjpa.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtycwaxcpr.html

C#:   interface IShape { double Area(); }
来源：http://dali.yuanzhike.top/Article/details/gthixjpkpp.html

[G10] 访问控制
来源：http://dali.cdnleiting.top/Article/details/gtpiclyuex.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhixingplan.top/Article/details/gtbqguvgjb.html

PHP:  public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gthjwlasnw.html

JS:   #private 字段；其余公开
来源：http://dali.tian-w.cn/Article/details/gtvpqcophf.html

TS:   public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtbhmoihcl.html

Java: public / protected / private / 默认包级
来源：http://dali.nwbrower.top/Article/details/gtdwywdltl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuetiantiany.cn/Article/details/gtecypgfoy.html

Ruby: public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtnoreuywr.html

C#:   public / protected / private / internal
来源：http://dali.shuidangran.top/Article/details/gtelgmtynx.html

[G11] getter / setter
来源：http://dali.shangyingyoupin.top/Article/details/gtmvmwvtkj.html

Py:   @property 与 @x.setter
来源：http://dali.yueranfly.top/Article/details/gtdieeyhnk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtsfbksbur.html

JS:   get name() { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtscuztzdc.html

TS:   get name(): string { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gtzejtizuu.html

Java: public String getName() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtjbxkczvv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gtohpralap.html

Ruby: attr_accessor :name
来源：http://dali.pycfn.com/Article/details/gtkwznujkn.html

C#:   public string Name { get; set; }
来源：http://dali.chenzaomai.com/Article/details/gtiveslzct.html

[G12] 对象转字符串
来源：http://dali.yangfankeji.com/Article/details/gtznbwylbd.html

Py:   def __str__(self): return self.name
来源：http://dali.jinqigufen.top/Article/details/gtjrepsgig.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gtdsyheexz.html

JS:   toString() { return this.name; }
来源：http://dali.sweek.top/Article/details/gtkzpcmutt.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtnxutvfkw.html

Java: @Override public String toString() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gthgsobrym.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtcofyrack.html

Ruby: def to_s; @name; end
来源：http://dali.quarkkingdee.top/Article/details/gtughuxred.html

C#:   public override string ToString() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfcngnfpp.html

[G13] 判断对象类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywnoujcf.html

Py:   isinstance(u, User)
来源：http://dali.cashguo.top/Article/details/gtpgnzhfwp.html

PHP:  $u instanceof User
来源：http://dali.cashguo.top/Article/details/gtdinmltvo.html

JS:   u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtylczquvo.html

TS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtkyfwnupg.html

Java: u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtryqludwo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuanzhike.top/Article/details/gtfcmwzyku.html

Ruby: u.is_a?(User)
来源：http://dali.yj20258.top/Article/details/gtheyeecci.html

C#:   u is User
来源：http://dali.ehwqpu.com/Article/details/gthxavpnhj.html

[G14] 数据类 / record
来源：http://dali.zhoulong.xyz/Article/details/gtkmxadjwu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258.top/Article/details/gtrzbtzjbr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cqqwz.cn/Article/details/gthzmszsqe.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkarhejtb.html

TS:   type User = { name: string; age: number };
来源：http://dali.tanke756.top/Article/details/gtzsnmubfd.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258888.top/Article/details/gttmgefqoe.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cdnleiting.top/Article/details/gthgzyiudb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gzhubu.top/Article/details/gtwgpuwtnj.html

C#:   record User(string Name, int Age);
来源：http://dali.ppjwa.cn/Article/details/gttwpdfrvo.html

[G15] 枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnimacjx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgfzy.top/Article/details/gtceksdfgf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.bjfxy.top/Article/details/gttvxwdlig.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.feifeiyinyue.top/Article/details/gtsxhyhaxo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmtojmwy.html

Java: enum Color { RED, GREEN }
来源：http://dali.sysykeji.top/Article/details/gtfboirrni.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yueranfly.top/Article/details/gtkfxryvwt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sxryk.cn/Article/details/gtxvgvberd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gtmbtbakry.html

[G16] 对象转数组 / 字典
来源：http://dali.ppjwa.cn/Article/details/gtpttrsxuy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.smart0.xyz/Article/details/gthyoegppd.html

PHP:  get_object_vars($obj);
来源：http://dali.shuidangran.top/Article/details/gtokbvwdrn.html

JS:   Object.entries(obj)
来源：http://dali.jiagoushi.top/Article/details/gtpdcyveti.html

TS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gtigdnebnm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xuetiantiany.cn/Article/details/gtcumdwwqa.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenlongwang.top/Article/details/gtgmlixnqv.html

Ruby: obj.instance_variables
来源：http://dali.ppjwa.cn/Article/details/gtvteobowu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gtzbepzlas.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtabzjfdty.html

H. 异常与错误处理
来源：http://dali.smart0.xyz/Article/details/gtaabfmxwh.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtqecuooyj.html

[H01] try / catch 基础
来源：http://dali.zhaomingkeji.xyz/Article/details/gtttllkzee.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.c1oappe.top/Article/details/gtxtymkyzc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yangfankeji.com/Article/details/gtdzcfetzk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gtuvcqamry.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gtofrabmuf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtixzdukyh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shuidangran.top/Article/details/gtfujfcpxn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jlsjyb.cn/Article/details/gtltxegsgw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.haohaochexian.top/Article/details/gthwnhspdf.html

[H02] finally / ensure 收尾
来源：http://dali.ivvv.top/Article/details/gtcdnkbnhc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sweek.top/Article/details/gtitdbwzio.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtjshonzji.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtwrijfqli.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtpqtuiodu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtkjribmko.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cheryme.top/Article/details/gtucdwzdam.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.snrcjt.cn/Article/details/gtbbnqbfhl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtfqgsxrkn.html

[H03] 主动抛出异常
来源：http://dali.jqgfzy.top/Article/details/gtmqnklesx.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj202588.top/Article/details/gtznzzlihr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtqnuguknk.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtfrljkqmd.html


<!-- 参考信息 -->