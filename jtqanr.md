代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.dianchejie.cn/Article/details/gtmqutnbeo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtfcqykxru.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtvynedgky.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtadgescly.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtksdvahrz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xziqi.cn/Article/details/gtvncjworq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtgtrdcbxw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtbjetaxzp.html

[E22] 字节长度与字符长度
来源：http://dali.xuanzx.com/Article/details/gthibavqho.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sufxvd.cn/Article/details/gtfwhzghsd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyfgnxdtg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gtaplxbeml.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cqqwz.cn/Article/details/gtjwkprkcq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xylfe.cn/Article/details/gtnidyuzcb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jqgufenzy.top/Article/details/gtqdwriicj.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtmzltayrl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yvedp.cn/Article/details/gtidfjfxfy.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtlbwydzie.html

F. 文件与目录
来源：http://dali.chenzaomai.com/Article/details/gtrcyamecy.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtfzlbemuc.html

[F01] 读取整个文件
来源：http://dali.kuanghao11.cn/Article/details/gtaduwysge.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj20258.top/Article/details/gtosrmvjpq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tanke756.top/Article/details/gtziprqomy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yongpay.top/Article/details/gtspexrdyq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gtnklfvbvm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtemcqbrhj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.vqdsnc.cn/Article/details/gtgwcmgczc.html

Ruby: File.read("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtabhrskto.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.pycfn.com/Article/details/gtmcmkipvi.html

[F02] 逐行读取文件
来源：http://dali.gotoacloud.top/Article/details/gtmqapxftc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxinkj.top/Article/details/gtppakzxcm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.316326.xyz/Article/details/gtznqyxxge.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jyoumei.cn/Article/details/gtaqsdqvqs.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gaohongyu789.top/Article/details/gtzlaffwjj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gtmczbezix.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.fengsongda.top/Article/details/gtixqaufhf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinqigfzy.top/Article/details/gturqvrffv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhixingplan.top/Article/details/gtlufleihv.html

[F03] 写入文件（覆盖）
来源：http://dali.tianlin.xyz/Article/details/gteetpfslm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.iojbl.cn/Article/details/gtylpnyekp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xylfe.cn/Article/details/gtwmnlvkdd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqozqudd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjpfrmtbr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.havefunace.top/Article/details/gtmyeysaxt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sweek.top/Article/details/gtkivyvhhw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hongshengwenyu.top/Article/details/gtqoxeuwpb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gotoacloud.top/Article/details/gtcrrlgjyi.html

[F04] 追加写入文件
来源：http://dali.snrcjt.cn/Article/details/gthzrgfjhf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtenckjlvu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gtcufcazix.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuanzx.com/Article/details/gtomoxstmx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gtzfhwlymw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.pycfn.com/Article/details/gtqardxhxb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yongpay.top/Article/details/gtaqplblxx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nanxinkj.top/Article/details/gtvuldanei.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hammf.cn/Article/details/gtjjubckbs.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfryodsu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fengsongda.top/Article/details/gtzzonmdhp.html

PHP:  file_exists("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtvhghqjka.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtgwpsdiwb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gthmrqdjsa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gteskqitza.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenjidiqi.icu/Article/details/gtizqgiydk.html

Ruby: File.exist?("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtxcjobywk.html

C#:   File.Exists("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtsowfmdmh.html

[F06] 删除文件
来源：http://dali.jiagoushi.top/Article/details/gtxftenxpi.html

Py:   os.remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtzgtjhdbr.html

PHP:  unlink("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtqxazqbbw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtturvdjhn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtaoztfpkv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtysibeflp.html

Go:   os.Remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtjjkasjij.html

Ruby: File.delete("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtnglqpiyo.html

C#:   File.Delete("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtkhpsqmac.html

[F07] 创建目录（含多级）
来源：http://dali.cashguo.top/Article/details/gttputrdas.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sxryk.cn/Article/details/gthzcyoaex.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtkfwlivli.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gogol.net.cn/Article/details/gtyupbiwsl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pycfn.com/Article/details/gtqtdfkrer.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhoulong.xyz/Article/details/gtjomziqhi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ivvv.top/Article/details/gtqgpjzexe.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.bjfxy.top/Article/details/gtwuqfkkmq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tanke756.top/Article/details/gthuykjcyj.html

[F08] 遍历目录
来源：http://dali.jinqigufen.top/Article/details/gtnyjzptit.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shangyingyoupin.top/Article/details/gtarnmyhae.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.wangdashe.top/Article/details/gtpkvdkjhw.html

JS:   fs.readdirSync("dir")
来源：http://dali.xuanzx.com/Article/details/gteyqkovar.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gtdfnueqah.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenzaomai.com/Article/details/gtaaabodzx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ehwqpu.com/Article/details/gtcqedojdk.html

Ruby: Dir.children("dir")
来源：http://dali.yangfankeji.com/Article/details/gtebgchtmr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.c1oappe.top/Article/details/gtekmkscjp.html

[F09] 获取文件大小
来源：http://dali.nanxuanxn.top/Article/details/gtliuwhmgl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cheryme.top/Article/details/gtocgbmwdk.html

PHP:  filesize("a.txt");
来源：http://dali.birdmap.top/Article/details/gtpeujljwf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pengpengdd.cyou/Article/details/gtupajiaaw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yanxiufei.cn/Article/details/gtuzeiuiro.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtyebkjbbi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zycfv.cn/Article/details/gtzruxeinz.html

Ruby: File.size("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtfuslgszc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.smart0.xyz/Article/details/gtbuzsllds.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.andypj.xyz/Article/details/gtrbrjjwge.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtskqpwjom.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258888.top/Article/details/gtozxbdgsm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtfhdejmdr.html

TS:   path.extname("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtoswcotfy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hfpthk.cn/Article/details/gtlnwgpfqd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvgjkpgol.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gttwzvprqx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtcuyjwzhf.html

[F11] 复制与移动文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtletrligq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtwncngqzs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cashguo.top/Article/details/gtqcovdnfr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gttvwpmcpl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtsyndvhze.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yuxming.cn/Article/details/gtxcracems.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhongyouzk.top/Article/details/gtncftvlxb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gtipxakzul.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtderajeqt.html

[F12] CSV 读写
来源：http://dali.svipenyu.cn/Article/details/gtqevhkqnh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zycfv.cn/Article/details/gtqgcxkpih.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yueranfly.top/Article/details/gtmfpplfzz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jianghu66.top/Article/details/gtbeshwmye.html

TS:   // 同上
来源：http://dali.hfpthk.cn/Article/details/gtxgopaevh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnqzz.top/Article/details/gtffbhvgkg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.haohaochexian.top/Article/details/gtnlcdauja.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhixingplan.top/Article/details/gtsvdexfmv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj202588.top/Article/details/gtuegnzttk.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtegrvrbbg.html

G. 面向对象
来源：http://dali.hnxiangtu.top/Article/details/gtomipvvuu.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtflhoawho.html

[G01] 定义类
来源：http://dali.jinqigufen.top/Article/details/gtitfnjevs.html

Py:   class User: pass
来源：http://dali.sweek.top/Article/details/gtxwuwccgu.html

PHP:  class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtdugffqob.html

JS:   class User {}
来源：http://dali.cheryme.top/Article/details/gtgpwmddhv.html

TS:   class User { name: string = ""; }
来源：http://dali.tianlin.xyz/Article/details/gtkqdacjnz.html

Java: class User {}
来源：http://dali.yangfankeji.com/Article/details/gtnjuhcnig.html

Go:   type User struct { Name string }
来源：http://dali.zhixingplan.top/Article/details/gtxlassujs.html

Ruby: class User; end
来源：http://dali.pengpengdd.cyou/Article/details/gtuogzblkx.html

C#:   class User {}
来源：http://dali.jqgfzy.top/Article/details/gtdywekenx.html

[G02] 构造函数
来源：http://dali.ppjwa.cn/Article/details/gtjsidrjnf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenzaomai.com/Article/details/gtrsckvxew.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dashuyun.cn/Article/details/gtoitqnglw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gtzeugfvtm.html

TS:   constructor(public name: string) {}
来源：http://dali.bjfxy.top/Article/details/gtlqedklpl.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gtvuszmfya.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hysaishi.cn/Article/details/gteojxnvwt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cheryme.top/Article/details/gtfqwlllqg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigufen.top/Article/details/gtmgccqfvo.html

[G03] 实例属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjbobofsb.html

Py:   self.name = "x"
来源：http://dali.hongshengwenyu.top/Article/details/gtyacmullj.html

PHP:  public string $name = "x";
来源：http://dali.ybcxt.top/Article/details/gtaxuzyyym.html

JS:   this.name = "x";
来源：http://dali.smart0.xyz/Article/details/gtwqdfkhan.html

TS:   name: string = "x";
来源：http://dali.tian-w.cn/Article/details/gtceelqvzy.html

Java: private String name;
来源：http://dali.wangdashe.top/Article/details/gtodqcnteh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigufen.top/Article/details/gtdnvrnvub.html

Ruby: @name = "x"
来源：http://dali.yj20258.top/Article/details/gtijtufwhy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nwbrower.top/Article/details/gtpedutaor.html

[G04] 定义方法
来源：http://dali.zhongyouzk.top/Article/details/gtwkkredki.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangtech.top/Article/details/gtelcqfvor.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gtnsipbifv.html

JS:   greet() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtkjwghdtu.html

TS:   greet(): string { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtuklcvbsx.html

Java: String greet() { return name; }
来源：http://dali.yj20258888.top/Article/details/gtkfztgfgr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gttnyyfohy.html

Ruby: def greet; @name; end
来源：http://dali.zhengqikj.top/Article/details/gtqlkvqzhr.html

C#:   public string Greet() => Name;
来源：http://dali.smart0.xyz/Article/details/gtqwiciror.html

[G05] 继承
来源：http://dali.yanxiufei.cn/Article/details/gtndxlmviy.html

Py:   class Admin(User): pass
来源：http://dali.chenlongwang.top/Article/details/gtazaaesqt.html

PHP:  class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtpptqivjz.html

JS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtmswkkpkp.html

TS:   class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtfpxuqifn.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gthwtcizaf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.smart0.xyz/Article/details/gtxvjnftkf.html

Ruby: class Admin < User; end
来源：http://dali.pengpengdd.cyou/Article/details/gtgahlgkpg.html

C#:   class Admin : User {}
来源：http://dali.jiagoushi.top/Article/details/gtkbxjxakj.html

[G06] 重写方法
来源：http://dali.zycfv.cn/Article/details/gtehthyail.html

Py:   def greet(self): return "admin"
来源：http://dali.jlsjyb.cn/Article/details/gtntyuepzr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gthiuwohkj.html

JS:   greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtbktvceqt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtocojygff.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtliznongg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cdnleiting.top/Article/details/gtjlrhatfk.html

Ruby: def greet; "admin"; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtpsrfowmi.html

C#:   public override string Greet() => "admin";
来源：http://dali.wangshuangyany.cn/Article/details/gtscaccdom.html

[G07] 调用父类方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxojblvmw.html

Py:   super().greet()
来源：http://dali.quarkkingdee.top/Article/details/gtotdrzwae.html

PHP:  parent::greet();
来源：http://dali.yonumen.top/Article/details/gtowdzdrzg.html

JS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gtmoydpxgv.html

TS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtyjivvhju.html

Java: super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gtiapgfbcs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tianlin.xyz/Article/details/gtcmgdmtyt.html

Ruby: super
来源：http://dali.yueranfly.top/Article/details/gtqljskbok.html

C#:   base.Greet();
来源：http://dali.yongpay.top/Article/details/gtzuhbwpzt.html

[G08] 静态方法与属性
来源：http://dali.sysykeji.top/Article/details/gtrctfmfiy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangdashe.top/Article/details/gtrmcesxlh.html

PHP:  public static function f() {}
来源：http://dali.quarkkingdee.top/Article/details/gtfiuzysck.html

JS:   static f() {}
来源：http://dali.yuxming.cn/Article/details/gtzvbfptnh.html

TS:   static f(): void {}
来源：http://dali.kuanghao11.cn/Article/details/gttewweqyn.html

Java: static void f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtmtytrvdz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nanxuanxn.top/Article/details/gtggfanjtj.html

Ruby: def self.f; end
来源：http://dali.hongshengwenyu.top/Article/details/gtogznnioh.html

C#:   public static void F() {}
来源：http://dali.jqgfzy.top/Article/details/gtispnzjik.html

[G09] 接口 / 抽象类
来源：http://dali.svipenyu.cn/Article/details/gtxctjlydv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sysykeji.top/Article/details/gtmnaqsfdk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ehwqpu.com/Article/details/gtqxzvsxrx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cashguo.top/Article/details/gtlflddgge.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhongyouzk.top/Article/details/gtpuhupoir.html

Java: interface Shape { double area(); }
来源：http://dali.zhixingplan.top/Article/details/gtxddnxojk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tian-w.cn/Article/details/gtbddfqwhp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenlongwang.top/Article/details/gtpvgatpir.html

C#:   interface IShape { double Area(); }
来源：http://dali.gogol.net.cn/Article/details/gtcnpqdctn.html

[G10] 访问控制
来源：http://dali.jqgfzy.top/Article/details/gtgbuvsnrm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nanxinkj.top/Article/details/gtqqyjvgoz.html

PHP:  public / protected / private
来源：http://dali.daxiang520.top/Article/details/gtfxazjofg.html

JS:   #private 字段；其余公开
来源：http://dali.0kj1m.cn/Article/details/gtmpmtfnsx.html

TS:   public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtoqqyfyyk.html

Java: public / protected / private / 默认包级
来源：http://dali.ydzc1.top/Article/details/gtlqhoffeu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xinyue.icu/Article/details/gtyshwzqjl.html

Ruby: public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gtiyjjcuwn.html

C#:   public / protected / private / internal
来源：http://dali.quarkkingdee.top/Article/details/gtzfhbzweu.html

[G11] getter / setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gtobgbxzat.html

Py:   @property 与 @x.setter
来源：http://dali.wangshuangyany.cn/Article/details/gtbdsphnhp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gtcileahjx.html

JS:   get name() { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gtmtgpihri.html

TS:   get name(): string { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gtcvzozuwk.html

Java: public String getName() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtsmzstbef.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtvetmxyvi.html

Ruby: attr_accessor :name
来源：http://dali.hnxiangtu.top/Article/details/gtpcjeopzf.html

C#:   public string Name { get; set; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gteeerohzd.html

[G12] 对象转字符串
来源：http://dali.zdqjudy.top/Article/details/gtcdjfwzhk.html

Py:   def __str__(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gtgtwjfgvs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtoeoxnhwg.html

JS:   toString() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtlecgvnrd.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtmuxknxzz.html

Java: @Override public String toString() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gtyrefyyav.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcidjyeya.html

Ruby: def to_s; @name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxuwiuik.html

C#:   public override string ToString() => Name;
来源：http://dali.yanxiufei.cn/Article/details/gtsxjkpxdb.html

[G13] 判断对象类型
来源：http://dali.wangshuangyany.cn/Article/details/gtwbcsymbo.html

Py:   isinstance(u, User)
来源：http://dali.yuxming.cn/Article/details/gtyjishmwn.html

PHP:  $u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtlacesktv.html

JS:   u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtlyqgyqli.html

TS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtuzojvhfe.html

Java: u instanceof User
来源：http://dali.sysykeji.top/Article/details/gthunuwjcs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tanke756.top/Article/details/gtohzvkrak.html

Ruby: u.is_a?(User)
来源：http://dali.chenjidiqi.icu/Article/details/gtmyoediml.html

C#:   u is User
来源：http://dali.9152youxi.cn/Article/details/gtiofsmmig.html

[G14] 数据类 / record
来源：http://dali.mhx1999.top/Article/details/gthmfilvah.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sysykeji.top/Article/details/gtpervshlv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenzaomai.com/Article/details/gtdenovcfl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gtkydqgkwn.html

TS:   type User = { name: string; age: number };
来源：http://dali.xinyue.icu/Article/details/gtkpbenrpe.html

Java: record User(String name, int age) {}
来源：http://dali.chenlongwang.top/Article/details/gtrmfpzika.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangdashe.top/Article/details/gtoqmcacxs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.smart0.xyz/Article/details/gthpyiclvc.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258.top/Article/details/gtmxrkejvp.html

[G15] 枚举
来源：http://dali.chenjidiqi.icu/Article/details/gtsxmwlvke.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.kuanghao11.cn/Article/details/gtjtatkaki.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yangfankeji.com/Article/details/gtrgivxjod.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hammf.cn/Article/details/gtpaitdjjv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gttsoubaly.html

Java: enum Color { RED, GREEN }
来源：http://dali.yonumen.top/Article/details/gttkgqxpzb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sweek.top/Article/details/gtqxmjkddl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ppjwa.cn/Article/details/gtmogllxwe.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gtvvfexjuv.html

[G16] 对象转数组 / 字典
来源：http://dali.sysykeji.top/Article/details/gtqcgbzrng.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj202588.top/Article/details/gtodieitqm.html

PHP:  get_object_vars($obj);
来源：http://dali.xuanzx.com/Article/details/gtpoxbgmpz.html

JS:   Object.entries(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtlahwonjn.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtxagmgubg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cashguo.top/Article/details/gtuqkofuab.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hongshengwenyu.top/Article/details/gtymqgjqjo.html

Ruby: obj.instance_variables
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcdlpykl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj202588.top/Article/details/gtboxmfuyk.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gthqqyxldj.html

H. 异常与错误处理
来源：http://dali.wangdashe.top/Article/details/gtptcejltv.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtvienxaqw.html

[H01] try / catch 基础
来源：http://dali.meibo888.top/Article/details/gtjoesgyys.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gtodckarfl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cqqwz.cn/Article/details/gtqpsphmtt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gtbxcmntwu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gtbteoslpz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecftcicx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gotoacloud.top/Article/details/gtfkwpzfme.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtglwpzart.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gthwennsgx.html

[H02] finally / ensure 收尾
来源：http://dali.hnqzz.top/Article/details/gtdrpllppi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhixingplan.top/Article/details/gtveuldgyq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtzerrjdpy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtrwxuavla.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtntpxoawz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtioghkwzu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtllwrzkca.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.9152youxi.cn/Article/details/gtlxkkiefl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtnwonbifj.html

[H03] 主动抛出异常
来源：http://dali.xinyue.icu/Article/details/gtyxshmoez.html

Py:   raise ValueError("错误信息")
来源：http://dali.cashguo.top/Article/details/gtcmogfojp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtdnaeyhwl.html

JS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtuvafeihf.html


<!-- 参考信息 -->