代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.ivvv.top/Article/details/gtxojmvhyi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.snrcjt.cn/Article/details/gtfiypwzig.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtbclaairx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gtqpdnricz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gtrtunjwzj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aizwys.cn/Article/details/gtbsoswiyy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sysykeji.top/Article/details/gtzxpbenjs.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtvhbviovu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhoulong.xyz/Article/details/gtnybtkuqx.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtvbblnore.html

F. 文件与目录
来源：http://dali.nwbrower.top/Article/details/gtnsbkbalf.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtasxuesqg.html

[F01] 读取整个文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabslqfms.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xuetiantiany.cn/Article/details/gtnxdaifie.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hammf.cn/Article/details/gtbkzfvipr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhixingplan.top/Article/details/gtgilauoeb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtaxgrzwlz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtmyuygdzk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ivvv.top/Article/details/gtehpkordu.html

Ruby: File.read("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtbecydgyk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtegkdlzxr.html

[F02] 逐行读取文件
来源：http://dali.jinqigfzy.top/Article/details/gtjzokilmb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdonacjsz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.316326.xyz/Article/details/gtrmkliizu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtdhmbbnru.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhixingplan.top/Article/details/gtizwtejbg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgfzy.top/Article/details/gtttvfbagj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sysykeji.top/Article/details/gtchcwetti.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.birdmap.top/Article/details/gtgwiqcanb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.aibaodan.cn/Article/details/gtzndyvmhq.html

[F03] 写入文件（覆盖）
来源：http://dali.shzxlz.cn/Article/details/gtasvkzbnx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jyoumei.cn/Article/details/gtabxvkmqe.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gtujpjeior.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gtpqugdhla.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gtglkgemtd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigufen.top/Article/details/gtkscovyqw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.kuanghao11.cn/Article/details/gtbtrnmdhf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtosjwpgus.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjopedec.html

[F04] 追加写入文件
来源：http://dali.dianchejie.cn/Article/details/gtcddlvkjv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxinkj.top/Article/details/gtacyjgejg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jianghu66.top/Article/details/gtjnpwdewg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gtwrplqnrf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yangfankeji.com/Article/details/gtixjgqtbh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gogol.net.cn/Article/details/gtglagmfpn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.fzhhl.top/Article/details/gthjzinaez.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhoulong.xyz/Article/details/gtmucqvyqo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gtgzqfurzl.html

[F05] 判断文件或目录是否存在
来源：http://dali.andypj.xyz/Article/details/gtkoktlqlo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xylfe.cn/Article/details/gtgxfpepqe.html

PHP:  file_exists("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtjjsxyhcx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtgmtuykmk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtsubnnndw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtfvtqqnjn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.mhx1999.top/Article/details/gttyizhpru.html

Ruby: File.exist?("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtbgfurdjd.html

C#:   File.Exists("a.txt")
来源：http://dali.pycfn.com/Article/details/gtjponjfxh.html

[F06] 删除文件
来源：http://dali.cashguo.top/Article/details/gtutdpeibu.html

Py:   os.remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztljpuei.html

PHP:  unlink("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtilsjtddk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtrezobcus.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gttieatrlo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtivzinqgc.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtbqmedikv.html

Ruby: File.delete("a.txt")
来源：http://dali.yj202588.top/Article/details/gtjdxxtvyv.html

C#:   File.Delete("a.txt");
来源：http://dali.ivvv.top/Article/details/gtpovtochc.html

[F07] 创建目录（含多级）
来源：http://dali.feifeiyinyue.top/Article/details/gtzzugoeyz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.vqdsnc.cn/Article/details/gtffyvvdag.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zycfv.cn/Article/details/gtvewaryvn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.feifeiyinyue.top/Article/details/gtsmyodgbo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhongyouzk.top/Article/details/gtsefkvmmh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.mhx1999.top/Article/details/gtbmbxqiey.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guowangkeji.top/Article/details/gteubgpkti.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.dianchejie.cn/Article/details/gtqszbqrpd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cdnleiting.top/Article/details/gtchhoblkk.html

[F08] 遍历目录
来源：http://dali.jinqigfzy.top/Article/details/gtxdmmawxj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guowangkeji.top/Article/details/gtqbfcvrsj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.0kj1m.cn/Article/details/gtroqwmpxa.html

JS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gtqkaqmkzr.html

TS:   fs.readdirSync("dir")
来源：http://dali.yuxming.cn/Article/details/gtpdxhmfaf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gtxtbulqkb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yonumen.top/Article/details/gtipfwhyjo.html

Ruby: Dir.children("dir")
来源：http://dali.xylfe.cn/Article/details/gtrxlvndgt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hywenlv.cn/Article/details/gtgvkiqxmn.html

[F09] 获取文件大小
来源：http://dali.haohaochexian.top/Article/details/gthuibyuoz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxavpwkg.html

PHP:  filesize("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtjccwlcqu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenlongwang.top/Article/details/gtvclbicqg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gotoacloud.top/Article/details/gtkqblwbdu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtnompdzqt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj20258.top/Article/details/gtjctwqkdu.html

Ruby: File.size("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtbxpweqxf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangdashe.top/Article/details/gtdhvshrjz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxuanxn.top/Article/details/gtyvyqwsug.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtpvcvphzh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtvwkehknu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtnxjsdyet.html

TS:   path.extname("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtnjvnigba.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhongyouzk.top/Article/details/gtzkcwzcgb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtpgdcyszm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtuzfzfkxi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcotcsydg.html

[F11] 复制与移动文件
来源：http://dali.pengpengdd.cyou/Article/details/gtmfvuoevk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtapgjcord.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenzaomai.com/Article/details/gthnfxtovw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gthaaweqqi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gthcqokuld.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.bjfxy.top/Article/details/gtsfvhuqlg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj202588.top/Article/details/gtjlbaafey.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtprubsmwy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.svipenyu.cn/Article/details/gtgvheydae.html

[F12] CSV 读写
来源：http://dali.zdqjudy.top/Article/details/gtbcvurzjk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jlsjyb.cn/Article/details/gtccoxmxkm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sysykeji.top/Article/details/gtctdgmweo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.andypj.xyz/Article/details/gtvaycxyop.html

TS:   // 同上
来源：http://dali.shangyingyoupin.top/Article/details/gtyttlviat.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zdqjudy.top/Article/details/gtyehtksnz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cashguo.top/Article/details/gtlwticwno.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.bjfxy.top/Article/details/gthspycqyf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jyoumei.cn/Article/details/gtqbndsxar.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtdrdkzncs.html

G. 面向对象
来源：http://dali.shzxlz.cn/Article/details/gtpmafmgnt.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtgohmkgfb.html

[G01] 定义类
来源：http://dali.feifeiyinyue.top/Article/details/gtafpshebv.html

Py:   class User: pass
来源：http://dali.zycfv.cn/Article/details/gterlrevff.html

PHP:  class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtkaffmrnr.html

JS:   class User {}
来源：http://dali.svipenyu.cn/Article/details/gtathobezq.html

TS:   class User { name: string = ""; }
来源：http://dali.zhongyouzk.top/Article/details/gtgqqacauw.html

Java: class User {}
来源：http://dali.zhixingplan.top/Article/details/gtrbdynhql.html

Go:   type User struct { Name string }
来源：http://dali.hnqzz.top/Article/details/gtxppijsdn.html

Ruby: class User; end
来源：http://dali.fengsongda.top/Article/details/gtzqwntbkq.html

C#:   class User {}
来源：http://dali.jqgufenzy.top/Article/details/gtphxohrch.html

[G02] 构造函数
来源：http://dali.cucudq.cn/Article/details/gtybrqtwgq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.quarkkingdee.top/Article/details/gtfybnvdpt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tanke756.top/Article/details/gtudkkzlpm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gtdylthqwd.html

TS:   constructor(public name: string) {}
来源：http://dali.yueranfly.top/Article/details/gtplvwielo.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhixingplan.top/Article/details/gtbluvymnb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aizwys.cn/Article/details/gtxlqcagyn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtusefammc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtsmqshadu.html

[G03] 实例属性
来源：http://dali.zhixingplan.top/Article/details/gtouyflivr.html

Py:   self.name = "x"
来源：http://dali.xinyue.icu/Article/details/gtvhmibnzd.html

PHP:  public string $name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtefbxsrrk.html

JS:   this.name = "x";
来源：http://dali.chenzaomai.com/Article/details/gthqchspbm.html

TS:   name: string = "x";
来源：http://dali.jianghu66.top/Article/details/gtfzxqihpm.html

Java: private String name;
来源：http://dali.yonumen.top/Article/details/gtazkmudyz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgfzy.top/Article/details/gtqluokazc.html

Ruby: @name = "x"
来源：http://dali.birdmap.top/Article/details/gtbddtssko.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cheryme.top/Article/details/gtnwhwqcrj.html

[G04] 定义方法
来源：http://dali.meibo888.top/Article/details/gtifbnqqhi.html

Py:   def greet(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gtivplydsh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtzukgzrjf.html

JS:   greet() { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqkakcukg.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtwwmxzmdo.html

Java: String greet() { return name; }
来源：http://dali.cheryme.top/Article/details/gtnhdyailj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtckzfttyd.html

Ruby: def greet; @name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjihtvkma.html

C#:   public string Greet() => Name;
来源：http://dali.snrcjt.cn/Article/details/gtzxahmhpd.html

[G05] 继承
来源：http://dali.sufxvd.cn/Article/details/gtwduswuat.html

Py:   class Admin(User): pass
来源：http://dali.xuanzx.com/Article/details/gtelmtrxnw.html

PHP:  class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtyvbtvtci.html

JS:   class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmuyusya.html

TS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gthqbmumun.html

Java: class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtosfsfnzz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.c1oappe.top/Article/details/gthiaaefsw.html

Ruby: class Admin < User; end
来源：http://dali.zycfv.cn/Article/details/gtgseaqohi.html

C#:   class Admin : User {}
来源：http://dali.cheryme.top/Article/details/gtspoqqkre.html

[G06] 重写方法
来源：http://dali.nanxinkj.top/Article/details/gtprauoxlq.html

Py:   def greet(self): return "admin"
来源：http://dali.hnxiangtu.top/Article/details/gtpgmgvukd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtluxsfmgp.html

JS:   greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtzlohpbxq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtrxobnngj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtmmbrwehf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhiwuduotai.top/Article/details/gtzsmsevor.html

Ruby: def greet; "admin"; end
来源：http://dali.gzhubu.top/Article/details/gteiidpoup.html

C#:   public override string Greet() => "admin";
来源：http://dali.tian-w.cn/Article/details/gtomytvolz.html

[G07] 调用父类方法
来源：http://dali.cqqwz.cn/Article/details/gtmktudngm.html

Py:   super().greet()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjxmcwlo.html

PHP:  parent::greet();
来源：http://dali.yonumen.top/Article/details/gthvavklfz.html

JS:   super.greet();
来源：http://dali.zycfv.cn/Article/details/gtpgqshavz.html

TS:   super.greet();
来源：http://dali.xylfe.cn/Article/details/gtregzauih.html

Java: super.greet();
来源：http://dali.svipenyu.cn/Article/details/gtryizplfu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hongshengwenyu.top/Article/details/gtnydkionw.html

Ruby: super
来源：http://dali.0kj1m.cn/Article/details/gthtdcooqq.html

C#:   base.Greet();
来源：http://dali.zhixingplan.top/Article/details/gtcuebhzqn.html

[G08] 静态方法与属性
来源：http://dali.wangdashe.top/Article/details/gtdskhdqat.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.aibaodan.cn/Article/details/gtpsfyknki.html

PHP:  public static function f() {}
来源：http://dali.daxiang520.top/Article/details/gtdjmxavoi.html

JS:   static f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtvhrfznjg.html

TS:   static f(): void {}
来源：http://dali.fengsongda.top/Article/details/gtnvatkbpd.html

Java: static void f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtpegjkkoh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabaxwgfe.html

Ruby: def self.f; end
来源：http://dali.ppjwa.cn/Article/details/gttswwwdph.html

C#:   public static void F() {}
来源：http://dali.havefunace.top/Article/details/gtsdmtwqpd.html

[G09] 接口 / 抽象类
来源：http://dali.cqqwz.cn/Article/details/gtnwsgmact.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yonumen.top/Article/details/gtrvipycvo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fengsongda.top/Article/details/gtjulwwqih.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cheryme.top/Article/details/gtxggrdsiz.html

TS:   interface Shape { area(): number; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvgntrvbz.html

Java: interface Shape { double area(); }
来源：http://dali.cqqwz.cn/Article/details/gtactvziuv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daria6918.cn/Article/details/gtumkedpym.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xziqi.cn/Article/details/gtbfdotdze.html

C#:   interface IShape { double Area(); }
来源：http://dali.xziqi.cn/Article/details/gtjmcomlam.html

[G10] 访问控制
来源：http://dali.ybcxt.top/Article/details/gtavjglmvi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daria6918.cn/Article/details/gtbrbjibtn.html

PHP:  public / protected / private
来源：http://dali.havefunace.top/Article/details/gtsioezqea.html

JS:   #private 字段；其余公开
来源：http://dali.hywenlv.cn/Article/details/gtzpwbeeds.html

TS:   public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gttvvzzadj.html

Java: public / protected / private / 默认包级
来源：http://dali.shzxlz.cn/Article/details/gtvqspobtz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hywenlv.cn/Article/details/gtnoklepft.html

Ruby: public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtxmsuuzlh.html

C#:   public / protected / private / internal
来源：http://dali.zhixingplan.top/Article/details/gtwefxqmpx.html

[G11] getter / setter
来源：http://dali.daria6918.cn/Article/details/gtnnxgjnre.html

Py:   @property 与 @x.setter
来源：http://dali.mhx1999.top/Article/details/gttmhnujhq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtyfzaksek.html

JS:   get name() { return this._name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtczeqsuce.html

TS:   get name(): string { return this._name; }
来源：http://dali.guowangkeji.top/Article/details/gtyjelsffn.html

Java: public String getName() { return name; }
来源：http://dali.andypj.xyz/Article/details/gtpevgwxrb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtjmnxvyit.html

Ruby: attr_accessor :name
来源：http://dali.pycfn.com/Article/details/gtqcpakhry.html

C#:   public string Name { get; set; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhcjpmmy.html

[G12] 对象转字符串
来源：http://dali.jlsjyb.cn/Article/details/gtwxmuguxl.html

Py:   def __str__(self): return self.name
来源：http://dali.cqqwz.cn/Article/details/gtjgnrjhyf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gttrgpjfar.html

JS:   toString() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtdoyaecmm.html

TS:   toString(): string { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtzgjxpjts.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj20258888.top/Article/details/gtigkwiqzc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gtzfjnmoml.html

Ruby: def to_s; @name; end
来源：http://dali.tianlin.xyz/Article/details/gtsnvuuiko.html

C#:   public override string ToString() => Name;
来源：http://dali.tian-w.cn/Article/details/gtpvembmps.html

[G13] 判断对象类型
来源：http://dali.cqqwz.cn/Article/details/gtvzzmfpcj.html

Py:   isinstance(u, User)
来源：http://dali.yj20258.top/Article/details/gtzfsjpjwb.html

PHP:  $u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtmzwrpslh.html

JS:   u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtpodcfmnc.html

TS:   u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtdrgyzivb.html

Java: u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtuothnbge.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hysaishi.cn/Article/details/gtekfpdssz.html

Ruby: u.is_a?(User)
来源：http://dali.shuidangran.top/Article/details/gtwvbzvgse.html

C#:   u is User
来源：http://dali.xinyue.icu/Article/details/gtktcuojqs.html

[G14] 数据类 / record
来源：http://dali.jianghu66.top/Article/details/gtxksxirgk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jianghu66.top/Article/details/gtntmfwdvk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdytfomq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgufenzy.top/Article/details/gtnkybcfqu.html

TS:   type User = { name: string; age: number };
来源：http://dali.hywenlv.cn/Article/details/gtojenfime.html

Java: record User(String name, int age) {}
来源：http://dali.yanxiufei.cn/Article/details/gtsmwtbfdl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sysykeji.top/Article/details/gtiysawqdj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cucudq.cn/Article/details/gtrlgaciuf.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxuanxn.top/Article/details/gtaxvxrzhm.html

[G15] 枚举
来源：http://dali.9152youxi.cn/Article/details/gtlhqhmxbe.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.pengpengdd.cyou/Article/details/gtjufvsnnv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gtszhddxqk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhengqikj.top/Article/details/gtnooxmfal.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gtltyyxzjr.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigufen.top/Article/details/gtozuzvccm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gzhubu.top/Article/details/gtvavagimg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ivvv.top/Article/details/gtvxeypilh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtaxxahxrr.html

[G16] 对象转数组 / 字典
来源：http://dali.316326.xyz/Article/details/gtruzpekzp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.redwolf501.top/Article/details/gttrnugikp.html

PHP:  get_object_vars($obj);
来源：http://dali.yangfankeji.com/Article/details/gttbayuhsb.html

JS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtxidcjglv.html

TS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gtykdeatru.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258.top/Article/details/gtqxwnutcn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pycfn.com/Article/details/gtsofvhfst.html

Ruby: obj.instance_variables
来源：http://dali.316326.xyz/Article/details/gtawxtqxrc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sweek.top/Article/details/gtjpquyceq.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtfrlykism.html

H. 异常与错误处理
来源：http://dali.9152youxi.cn/Article/details/gtyfqwypgv.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtgrowancq.html

[H01] try / catch 基础
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqzelpce.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnaoplvgh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guowangkeji.top/Article/details/gtjsmkvjpx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtskbwlszm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gtvcghmosk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gtvdmusxtn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvonivvy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zdqjudy.top/Article/details/gtdjgqenmn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hywenlv.cn/Article/details/gtdkadirid.html

[H02] finally / ensure 收尾
来源：http://dali.zhongyouzk.top/Article/details/gtfdsszink.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.daxiang520.top/Article/details/gtxyqrnpcr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtljzqghpc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gttqljxrhe.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtvyagfopw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctzyyrrr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jiagoushi.top/Article/details/gtayzfqnzt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.quarkkingdee.top/Article/details/gtqgkdhdaz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtxzohydyx.html

[H03] 主动抛出异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnchbzgel.html

Py:   raise ValueError("错误信息")
来源：http://dali.shuidangran.top/Article/details/gtccfabupw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gtoxbmakvx.html

JS:   throw new Error("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtlkyahsxc.html

TS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtdsjlntcp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtuivvriir.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.fengsongda.top/Article/details/gtszgxehta.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ydzc1.top/Article/details/gtfsxocptv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gthxagzpum.html

[H04] 自定义异常类型
来源：http://dali.daria6918.cn/Article/details/gtrmtwwkks.html

Py:   class MyError(Exception): pass
来源：http://dali.fzhhl.top/Article/details/gtldqwtpcw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gtdgncxwzb.html


<!-- 参考信息 -->