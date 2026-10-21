代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.wangshuangyany.cn/Article/details/gtppqjjfnt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtjraxmwmy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gtmfssscok.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhengqikj.top/Article/details/gtknyadljm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.316326.xyz/Article/details/gttfzjxujs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ydzc1.top/Article/details/gtskrsasbz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.0kj1m.cn/Article/details/gtthbjwsis.html

Ruby: s.bytesize;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtgoexqmhb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqruzvbkq.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtdbiosgjs.html

F. 文件与目录
来源：http://dali.0kj1m.cn/Article/details/gtbwafeqxi.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtcyxhjcak.html

[F01] 读取整个文件
来源：http://dali.tanke756.top/Article/details/gtopqeyona.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenlongwang.top/Article/details/gttvhjjedo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtvimbagbk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.guowangkeji.top/Article/details/gtekbhbyyr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gtmgusriin.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtydmbrtxi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yanxiufei.cn/Article/details/gtzsdbgpeg.html

Ruby: File.read("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtytnwrnsw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtdpmafnjq.html

[F02] 逐行读取文件
来源：http://dali.pycfn.com/Article/details/gtrhnvryca.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.aibaodan.cn/Article/details/gtliekrwim.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangshuangyany.cn/Article/details/gtsmfzytel.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtwodciwcb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gtbbtwqpxi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gtqqekzkut.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xylfe.cn/Article/details/gtzljnwrvl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xziqi.cn/Article/details/gtlbtysamp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.pycfn.com/Article/details/gthcccdphh.html

[F03] 写入文件（覆盖）
来源：http://dali.cheryme.top/Article/details/gtqkwpwtmc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ydzc1.top/Article/details/gtztijsayp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gthawwfrsg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqgpfhbit.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gtdcpfwrlb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.daxiang520.top/Article/details/gthobszirp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cqqwz.cn/Article/details/gtbakmwqll.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.feifeiyinyue.top/Article/details/gttzyjwpnc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.haohaochexian.top/Article/details/gtnlpagxtd.html

[F04] 追加写入文件
来源：http://dali.zhixingplan.top/Article/details/gtgvphnoha.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenzaomai.com/Article/details/gtafhpkvuz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.dashuyun.cn/Article/details/gtkspbjzio.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gtmqrvfhds.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj202588.top/Article/details/gtmebwlvpo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ivvv.top/Article/details/gtdzevwytl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtmcbxxlct.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhixingplan.top/Article/details/gtxogulyma.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinghuilouyu.cn/Article/details/gtziviscmn.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxinkj.top/Article/details/gtyktprzvi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.pengpengdd.cyou/Article/details/gtbuvgfkdw.html

PHP:  file_exists("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtwktyuibl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtgkatwxok.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtcwgzovym.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtulquofon.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shuidangran.top/Article/details/gtngvfhhez.html

Ruby: File.exist?("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtfbdykero.html

C#:   File.Exists("a.txt")
来源：http://dali.pycfn.com/Article/details/gtdlocgrgy.html

[F06] 删除文件
来源：http://dali.0kj1m.cn/Article/details/gtkcandeaa.html

Py:   os.remove("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtcohpaulg.html

PHP:  unlink("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtpdckocox.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtytywypep.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtlncbtska.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtyuqxzarr.html

Go:   os.Remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtnjbmccbt.html

Ruby: File.delete("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtuupzolpd.html

C#:   File.Delete("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtkiedissk.html

[F07] 创建目录（含多级）
来源：http://dali.guowangkeji.top/Article/details/gttqvpdmrm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmtzzqear.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.0kj1m.cn/Article/details/gtoyalrsoh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.andypj.xyz/Article/details/gtrshqornu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gthrlpbwxr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfteejuo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cashguo.top/Article/details/gtnctwjoih.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfhwjoezr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ehwqpu.com/Article/details/gtalamzudo.html

[F08] 遍历目录
来源：http://dali.hywenlv.cn/Article/details/gtlsvqfwof.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yuxming.cn/Article/details/gtfjoeppjt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenjidiqi.icu/Article/details/gtktdlsuwz.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj20258888.top/Article/details/gtothmcbba.html

TS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gtvzntwgpl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gtbdgscnyv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.snrcjt.cn/Article/details/gtypqpvavx.html

Ruby: Dir.children("dir")
来源：http://dali.daxiang520.top/Article/details/gtchtrmfyj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj202588.top/Article/details/gtpjlzpcdv.html

[F09] 获取文件大小
来源：http://dali.yangfankeji.com/Article/details/gtekhhhmnb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtafsxanmv.html

PHP:  filesize("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtsdrdzipz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jlsjyb.cn/Article/details/gtkrivvtsi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenjidiqi.icu/Article/details/gtuwsvnfnh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtamcewrsq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.9152youxi.cn/Article/details/gtixvtfvlx.html

Ruby: File.size("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtbklvfied.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.smart0.xyz/Article/details/gtgbpeoqez.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hfpthk.cn/Article/details/gtchwodwdn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtgbzpaltv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtlazgpnpz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtwyworusm.html

TS:   path.extname("a.txt")
来源：http://dali.ivvv.top/Article/details/gtpozhlgxy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gotoacloud.top/Article/details/gtwbnzxlnd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtrrywdejb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtxszswllv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtqkudxmey.html

[F11] 复制与移动文件
来源：http://dali.bjfxy.top/Article/details/gtdobffgtr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtpybfxiql.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.mhx1999.top/Article/details/gtpigygqsk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtxneyxwuo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtfzrptshv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ehwqpu.com/Article/details/gtnxqfzlbj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xziqi.cn/Article/details/gtldlykecy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtifbduznx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.snrcjt.cn/Article/details/gthfeigyew.html

[F12] CSV 读写
来源：http://dali.fzhhl.top/Article/details/gtgunwaedf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.feifeiyinyue.top/Article/details/gtwbfltqmh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqeelrzrx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pengpengdd.cyou/Article/details/gtdrsggdjw.html

TS:   // 同上
来源：http://dali.andypj.xyz/Article/details/gtjmactqxp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daria6918.cn/Article/details/gtqcobsfgr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.kuanghao11.cn/Article/details/gtqotofzfb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fzhhl.top/Article/details/gtkmhlifid.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gaohongyu789.top/Article/details/gtlmbvuzdr.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtuernjwso.html

G. 面向对象
来源：http://dali.wangdashe.top/Article/details/gtbviluieu.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtzasfqnsg.html

[G01] 定义类
来源：http://dali.aibaodan.cn/Article/details/gtoyseopot.html

Py:   class User: pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdsbiwtns.html

PHP:  class User {}
来源：http://dali.sweek.top/Article/details/gtozyekugy.html

JS:   class User {}
来源：http://dali.yj20258.top/Article/details/gtzhinrety.html

TS:   class User { name: string = ""; }
来源：http://dali.feifeiyinyue.top/Article/details/gtlnpxnhzw.html

Java: class User {}
来源：http://dali.ehwqpu.com/Article/details/gtucilolxk.html

Go:   type User struct { Name string }
来源：http://dali.shangyingyoupin.top/Article/details/gtwninirpy.html

Ruby: class User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtohtfljfp.html

C#:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gtkwtrbiry.html

[G02] 构造函数
来源：http://dali.zhixingplan.top/Article/details/gtfevaphnz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hnqzz.top/Article/details/gtskuouahm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhongyouzk.top/Article/details/gthzefyaio.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gtsxztodoo.html

TS:   constructor(public name: string) {}
来源：http://dali.cheryme.top/Article/details/gtheiodhur.html

Java: User(String name) { this.name = name; }
来源：http://dali.svipenyu.cn/Article/details/gtaltsriff.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ydzc1.top/Article/details/gthwmxiarx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenjidiqi.icu/Article/details/gtyrksxugz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yongpay.top/Article/details/gtftquvriz.html

[G03] 实例属性
来源：http://dali.pengpengdd.cyou/Article/details/gtsiatnifx.html

Py:   self.name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gtxsiyxibo.html

PHP:  public string $name = "x";
来源：http://dali.tianlin.xyz/Article/details/gtxrullsyh.html

JS:   this.name = "x";
来源：http://dali.yonumen.top/Article/details/gtfsyrzznc.html

TS:   name: string = "x";
来源：http://dali.jinqigufen.top/Article/details/gtstlgxkmm.html

Java: private String name;
来源：http://dali.jinqigfzy.top/Article/details/gtlbccziey.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.dashuyun.cn/Article/details/gtneixlkgc.html

Ruby: @name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gtpsgcdzpb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.andypj.xyz/Article/details/gtqhxtcgyv.html

[G04] 定义方法
来源：http://dali.haohaochexian.top/Article/details/gtuvkuewjs.html

Py:   def greet(self): return self.name
来源：http://dali.zdqjudy.top/Article/details/gtpdtquzat.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtbmuskayt.html

JS:   greet() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtelsnzeyf.html

TS:   greet(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtgsrxgwri.html

Java: String greet() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmzvdzveq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gtosfkdhbu.html

Ruby: def greet; @name; end
来源：http://dali.zhengqikj.top/Article/details/gtgzlanvgt.html

C#:   public string Greet() => Name;
来源：http://dali.yanxiufei.cn/Article/details/gtqubmlxja.html

[G05] 继承
来源：http://dali.cashguo.top/Article/details/gtrtuvbjtd.html

Py:   class Admin(User): pass
来源：http://dali.zhongyouzk.top/Article/details/gtrrbsmrpb.html

PHP:  class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtsmybwboy.html

JS:   class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtmtpkheow.html

TS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuaxexnke.html

Java: class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtrereotpk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj20258.top/Article/details/gtggtgqljx.html

Ruby: class Admin < User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdudpvke.html

C#:   class Admin : User {}
来源：http://dali.yj20258888.top/Article/details/gtimcmoton.html

[G06] 重写方法
来源：http://dali.zdqjudy.top/Article/details/gtdopaxoaf.html

Py:   def greet(self): return "admin"
来源：http://dali.chenjidiqi.icu/Article/details/gtbhqfuacp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtvfjjxnuu.html

JS:   greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtnileqqpu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtwfoqlkzq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtnlmgrbjh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shzxlz.cn/Article/details/gtxmfmvzbb.html

Ruby: def greet; "admin"; end
来源：http://dali.wangdashe.top/Article/details/gteexqdylu.html

C#:   public override string Greet() => "admin";
来源：http://dali.quarkkingdee.top/Article/details/gtjumipqyy.html

[G07] 调用父类方法
来源：http://dali.havefunace.top/Article/details/gtygartxew.html

Py:   super().greet()
来源：http://dali.dianchejie.cn/Article/details/gtixtiiuml.html

PHP:  parent::greet();
来源：http://dali.meibo888.top/Article/details/gtzipznyad.html

JS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtipnhdjmp.html

TS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gtjvvgsznq.html

Java: super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnevaxpvf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.kuanghao11.cn/Article/details/gtiiduevbe.html

Ruby: super
来源：http://dali.mhx1999.top/Article/details/gtlzwwcvey.html

C#:   base.Greet();
来源：http://dali.redwolf501.top/Article/details/gtqrusnozx.html

[G08] 静态方法与属性
来源：http://dali.gaohongyu789.top/Article/details/gtdsrvrxbh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj202588.top/Article/details/gtssezuqyv.html

PHP:  public static function f() {}
来源：http://dali.havefunace.top/Article/details/gtidennjhh.html

JS:   static f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtaoxmmmfl.html

TS:   static f(): void {}
来源：http://dali.jinqigufen.top/Article/details/gtiohhdtwj.html

Java: static void f() {}
来源：http://dali.guowangkeji.top/Article/details/gtmshyclbo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.pycfn.com/Article/details/gtgizifaed.html

Ruby: def self.f; end
来源：http://dali.guowangkeji.top/Article/details/gtxkcqirmb.html

C#:   public static void F() {}
来源：http://dali.ybcxt.top/Article/details/gtxnweeixz.html

[G09] 接口 / 抽象类
来源：http://dali.zhengqikj.top/Article/details/gtqszucccs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tian-w.cn/Article/details/gtmdevtoti.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guowangkeji.top/Article/details/gtnezgnyqy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.c1oappe.top/Article/details/gtbhehknfa.html

TS:   interface Shape { area(): number; }
来源：http://dali.ehwqpu.com/Article/details/gtryogohht.html

Java: interface Shape { double area(); }
来源：http://dali.hysaishi.cn/Article/details/gtnpvqjxpo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sufxvd.cn/Article/details/gtxjhrkjvp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinqigfzy.top/Article/details/gtfkhexpff.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxuanxn.top/Article/details/gtijdabiar.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gtummybgki.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fengsongda.top/Article/details/gtxexroehl.html

PHP:  public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtltqkenkd.html

JS:   #private 字段；其余公开
来源：http://dali.ppjwa.cn/Article/details/gtabqijdwy.html

TS:   public / protected / private
来源：http://dali.yongpay.top/Article/details/gtjutidqke.html

Java: public / protected / private / 默认包级
来源：http://dali.gaohongyu789.top/Article/details/gtehbamilf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hongshengwenyu.top/Article/details/gtphsdyesf.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gtexzdryor.html

C#:   public / protected / private / internal
来源：http://dali.hywenlv.cn/Article/details/gttbrqgqwo.html

[G11] getter / setter
来源：http://dali.tian-w.cn/Article/details/gtadrdegwp.html

Py:   @property 与 @x.setter
来源：http://dali.yueranfly.top/Article/details/gtstiqbxnh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gtuorvtqhl.html

JS:   get name() { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gtqsatihzk.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gtzessvkyx.html

Java: public String getName() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtgnliduyr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gteaatafms.html

Ruby: attr_accessor :name
来源：http://dali.yuxming.cn/Article/details/gtoiyquxji.html

C#:   public string Name { get; set; }
来源：http://dali.jianghu66.top/Article/details/gtrhxifuwk.html

[G12] 对象转字符串
来源：http://dali.sysykeji.top/Article/details/gtfwpdkzqf.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258.top/Article/details/gtuqhiggfd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtedzzxapd.html

JS:   toString() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gttlurdays.html

TS:   toString(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtcsiujwif.html

Java: @Override public String toString() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtqiumbldd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtnbdsujdc.html

Ruby: def to_s; @name; end
来源：http://dali.yuanzhike.top/Article/details/gtkbixpvzv.html

C#:   public override string ToString() => Name;
来源：http://dali.dashuyun.cn/Article/details/gtibiiztdz.html

[G13] 判断对象类型
来源：http://dali.xuanzx.com/Article/details/gtkvmcgwfo.html

Py:   isinstance(u, User)
来源：http://dali.yj202588.top/Article/details/gtsuuurgnm.html

PHP:  $u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtmvcfmysg.html

JS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtutkpfpya.html

TS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtzcjereig.html

Java: u instanceof User
来源：http://dali.cashguo.top/Article/details/gtmdjbhyvh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.guannengcc.top/Article/details/gtymwmyxze.html

Ruby: u.is_a?(User)
来源：http://dali.feifeiyinyue.top/Article/details/gtldycvrip.html

C#:   u is User
来源：http://dali.yuxming.cn/Article/details/gtkczbtauz.html

[G14] 数据类 / record
来源：http://dali.jqgufenzy.top/Article/details/gtnnlemlwa.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yueranfly.top/Article/details/gtuqsiywaf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sysykeji.top/Article/details/gtotrxevzw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gaohongyu789.top/Article/details/gtmcdlkefg.html

TS:   type User = { name: string; age: number };
来源：http://dali.cucudq.cn/Article/details/gtghycpynt.html

Java: record User(String name, int age) {}
来源：http://dali.shzxlz.cn/Article/details/gtmzrgtikx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.fengsongda.top/Article/details/gthcfjugbk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hysaishi.cn/Article/details/gtxrmeinzy.html

C#:   record User(string Name, int Age);
来源：http://dali.xuetiantiany.cn/Article/details/gthcjyizfp.html

[G15] 枚举
来源：http://dali.andypj.xyz/Article/details/gtzlhsiwph.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yangfankeji.com/Article/details/gtqikysnmk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.pycfn.com/Article/details/gtvafyhzet.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.bjfxy.top/Article/details/gtsgzgtxmb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sufxvd.cn/Article/details/gtqdjwqmcr.html

Java: enum Color { RED, GREEN }
来源：http://dali.pycfn.com/Article/details/gtwaoisfxm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhengqikj.top/Article/details/gtqqowqhuy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhoulong.xyz/Article/details/gtqdvtcjik.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hfpthk.cn/Article/details/gtoqzjgana.html

[G16] 对象转数组 / 字典
来源：http://dali.jlsjyb.cn/Article/details/gtsfpuuymf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.wangshuangyany.cn/Article/details/gtzzhtmhib.html

PHP:  get_object_vars($obj);
来源：http://dali.shzxlz.cn/Article/details/gtnyyfrwnj.html

JS:   Object.entries(obj)
来源：http://dali.hnxiangtu.top/Article/details/gthawofcog.html

TS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzuceajyz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cashguo.top/Article/details/gtazdebwkk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xinyue.icu/Article/details/gtoirrpeek.html

Ruby: obj.instance_variables
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwyjvhcvf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gtjsxtdvxl.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtccprpbkb.html

H. 异常与错误处理
来源：http://dali.cheryme.top/Article/details/gtycrskitb.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtptsazwxa.html

[H01] try / catch 基础
来源：http://dali.pengpengdd.cyou/Article/details/gtqvgvfhwz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tanke756.top/Article/details/gtjhijsdar.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jlsjyb.cn/Article/details/gtsypcujgl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gtuzluvbeu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gtltjmfcaq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttscslbry.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.andypj.xyz/Article/details/gtsrbjjbjg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenzaomai.com/Article/details/gthsfdkgas.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ehwqpu.com/Article/details/gtnuhajdmf.html

[H02] finally / ensure 收尾
来源：http://dali.nanxinkj.top/Article/details/gtkpfkdtki.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tianlin.xyz/Article/details/gtplcpxwha.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtbzqkplry.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtprwplras.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtrganmjnw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtelxfuplg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zdqjudy.top/Article/details/gtdbksmemg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guowangkeji.top/Article/details/gtsjgtqngp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtbnenqvnb.html

[H03] 主动抛出异常
来源：http://dali.quarkkingdee.top/Article/details/gtzjiuwiks.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpgyuzbp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtbaqnrqmj.html

JS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gtpvcuxets.html

TS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gttvgistrh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gttbkvxytb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.9152youxi.cn/Article/details/gtadpmnenv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yanxiufei.cn/Article/details/gtnoiyemoq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtmiwrmgax.html

[H04] 自定义异常类型
来源：http://dali.dashuyun.cn/Article/details/gtyruuxhdt.html

Py:   class MyError(Exception): pass
来源：http://dali.cdnleiting.top/Article/details/gtbfmoormg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuerquscr.html


<!-- 参考信息 -->