代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.jianghu66.top/Article/details/gtnrzvhpqu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ehwqpu.com/Article/details/gtuufaldta.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gtxckfdbfl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gtyfihxvnl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtxxvasstq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.bjfxy.top/Article/details/gtutyraxqr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ehwqpu.com/Article/details/gtiwnnrhqd.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj20258888.top/Article/details/gtouxlvmli.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gtekakyemb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtlztizpeh.html

F. 文件与目录
来源：http://dali.xziqi.cn/Article/details/gthtiadexs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtgonogmpz.html

[F01] 读取整个文件
来源：http://dali.yueranfly.top/Article/details/gtvpiyqvew.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.snrcjt.cn/Article/details/gtqchfjkdt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtuahbvzwc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.0kj1m.cn/Article/details/gtstdxftaa.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gtxkfdexlt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtacpycwrs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cqqwz.cn/Article/details/gticpkqcjp.html

Ruby: File.read("a.txt")
来源：http://dali.tanke756.top/Article/details/gtaeoxytyv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdeirlqiz.html

[F02] 逐行读取文件
来源：http://dali.gaohongyu789.top/Article/details/gtxipcairr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pycfn.com/Article/details/gthmivtnku.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxtllqthg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fzhhl.top/Article/details/gtwajeavcs.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.redwolf501.top/Article/details/gtbcsbnsap.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.9152youxi.cn/Article/details/gtqqizbflp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.fzhhl.top/Article/details/gtggzbgzqu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.aizwys.cn/Article/details/gtrxdvhvqa.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hammf.cn/Article/details/gtqbujiexf.html

[F03] 写入文件（覆盖）
来源：http://dali.hnqzz.top/Article/details/gtbfqcbesb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.daxiang520.top/Article/details/gtcfcmvcjf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gtwidcmfgx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yongpay.top/Article/details/gtpygjhguv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gtvfhmxtud.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.guowangkeji.top/Article/details/gthejnpkbc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yangfankeji.com/Article/details/gtgotpqrda.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cashguo.top/Article/details/gtpqexyuxn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhengqikj.top/Article/details/gtyioqfoij.html

[F04] 追加写入文件
来源：http://dali.bjfxy.top/Article/details/gtagevoqfy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sweek.top/Article/details/gtrpnhmjao.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tian-w.cn/Article/details/gtesnnjrcw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shzxlz.cn/Article/details/gtwozljfzk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gtbkljjmjj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jqgufenzy.top/Article/details/gtjgrxnasu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hywenlv.cn/Article/details/gtkgdyftil.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuxming.cn/Article/details/gtgpekskmt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cdnleiting.top/Article/details/gtcfzvxucp.html

[F05] 判断文件或目录是否存在
来源：http://dali.ydzc1.top/Article/details/gtfapdcjxl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.andypj.xyz/Article/details/gttszxqsrl.html

PHP:  file_exists("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtuzatokrb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtzcieelqb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtdztqysgi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gteegptsxz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daxiang520.top/Article/details/gtvzqewbsg.html

Ruby: File.exist?("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtinpntegl.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtaifsavxe.html

[F06] 删除文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtosmqnebw.html

Py:   os.remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtxmflfsxb.html

PHP:  unlink("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtiqfdtfdb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtvvhguenr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtcopunvcy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtcpbsxlae.html

Go:   os.Remove("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtjjnubfbh.html

Ruby: File.delete("a.txt")
来源：http://dali.pycfn.com/Article/details/gtxazqarul.html

C#:   File.Delete("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtnbmjqbpp.html

[F07] 创建目录（含多级）
来源：http://dali.zdqjudy.top/Article/details/gtujgtncxk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.andypj.xyz/Article/details/gtmhomdhbx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tianlin.xyz/Article/details/gtzwsjqmsd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daxiang520.top/Article/details/gtyhidjrzl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigufen.top/Article/details/gtrozihrkl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hongshengwenyu.top/Article/details/gtyhzkgnps.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sweek.top/Article/details/gtsudcxpan.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shanyushiyangtech.top/Article/details/gthwbhfqvb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.meibo888.top/Article/details/gtpngfeipj.html

[F08] 遍历目录
来源：http://dali.316326.xyz/Article/details/gthccmlzgy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cashguo.top/Article/details/gtovclpirf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tianlin.xyz/Article/details/gtziciylsq.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gtbkkxkggx.html

TS:   fs.readdirSync("dir")
来源：http://dali.gzhubu.top/Article/details/gtwsrlmjau.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.svipenyu.cn/Article/details/gtjvhqwwkl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.fengsongda.top/Article/details/gtifvuqrwe.html

Ruby: Dir.children("dir")
来源：http://dali.cdnleiting.top/Article/details/gtgbjdzhds.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtmybdishv.html

[F09] 获取文件大小
来源：http://dali.quarkkingdee.top/Article/details/gtyqunoevu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtolxmthop.html

PHP:  filesize("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtptkicwml.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhongyouzk.top/Article/details/gtlwgefzcn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gtkqtcygqm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gttyeevfda.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.aizwys.cn/Article/details/gthywzhour.html

Ruby: File.size("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtcflcdwtt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangshuangyany.cn/Article/details/gtfprvhiui.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqfojlowl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtqnztigjv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xinyue.icu/Article/details/gthmhpyiev.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzumiosrt.html

TS:   path.extname("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtepgvaiho.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.c1oappe.top/Article/details/gtlsguqwfo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtfgnobgpg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtyuafmeri.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtzexcyner.html

[F11] 复制与移动文件
来源：http://dali.dianchejie.cn/Article/details/gtrrcxwjjw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtrgmapreu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cqqwz.cn/Article/details/gtsdbpmkep.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtrqrtopqn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtjkirhsbe.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dianchejie.cn/Article/details/gtrnwkhcay.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangshuangyany.cn/Article/details/gtqiqvkomn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtflvfikjl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gtmjtmfcfw.html

[F12] CSV 读写
来源：http://dali.xinyue.icu/Article/details/gtokyuqgkr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.mhx1999.top/Article/details/gthflimwbv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jlsjyb.cn/Article/details/gtincaicfw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xziqi.cn/Article/details/gtpfojmoqb.html

TS:   // 同上
来源：http://dali.hnxiangtu.top/Article/details/gtxiymxsmh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sysykeji.top/Article/details/gtdppdocsu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.wangshuangyany.cn/Article/details/gtdnrzxfnl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jqgfzy.top/Article/details/gtvsqnxkny.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvziigyn.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtairxwrbx.html

G. 面向对象
来源：http://dali.xinyue.icu/Article/details/gtkailubrg.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtxrxoqaif.html

[G01] 定义类
来源：http://dali.sxryk.cn/Article/details/gtvtuspndd.html

Py:   class User: pass
来源：http://dali.yvedp.cn/Article/details/gtnttqccpk.html

PHP:  class User {}
来源：http://dali.haohaochexian.top/Article/details/gtypuxnxbm.html

JS:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gtcamspnrg.html

TS:   class User { name: string = ""; }
来源：http://dali.zycfv.cn/Article/details/gthkrqlive.html

Java: class User {}
来源：http://dali.cheryme.top/Article/details/gtimnhlooc.html

Go:   type User struct { Name string }
来源：http://dali.aibaodan.cn/Article/details/gtxtbldvsa.html

Ruby: class User; end
来源：http://dali.dashuyun.cn/Article/details/gtobsbnfve.html

C#:   class User {}
来源：http://dali.daria6918.cn/Article/details/gtdcdqywqq.html

[G02] 构造函数
来源：http://dali.yuanzhike.top/Article/details/gthfqrxsrk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hammf.cn/Article/details/gtmnreiigv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.quarkkingdee.top/Article/details/gtlcgnrpsa.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guannengcc.top/Article/details/gtwxfwcvmq.html

TS:   constructor(public name: string) {}
来源：http://dali.wangdashe.top/Article/details/gtejtqfhgm.html

Java: User(String name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gttktvnazl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daxiang520.top/Article/details/gtbwpptkon.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ybcxt.top/Article/details/gtoupjcmyr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tian-w.cn/Article/details/gtwlulqwzl.html

[G03] 实例属性
来源：http://dali.ivvv.top/Article/details/gtiisejqud.html

Py:   self.name = "x"
来源：http://dali.guowangkeji.top/Article/details/gtgdcdlpng.html

PHP:  public string $name = "x";
来源：http://dali.fengsongda.top/Article/details/gttgdugvgo.html

JS:   this.name = "x";
来源：http://dali.jianghu66.top/Article/details/gtlbxdzfni.html

TS:   name: string = "x";
来源：http://dali.dianchejie.cn/Article/details/gtarinfvdt.html

Java: private String name;
来源：http://dali.wangshuangyany.cn/Article/details/gtvkwlakeq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.fzhhl.top/Article/details/gtkwleyiyb.html

Ruby: @name = "x"
来源：http://dali.hongshengwenyu.top/Article/details/gtrwbxigwq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guannengcc.top/Article/details/gtnvbdlpaw.html

[G04] 定义方法
来源：http://dali.mhx1999.top/Article/details/gtfdovvvbz.html

Py:   def greet(self): return self.name
来源：http://dali.bjfxy.top/Article/details/gtqystsyjt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gtcfemrjkr.html

JS:   greet() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtwodbxieq.html

TS:   greet(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtdownfmix.html

Java: String greet() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtynpqtdxg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gtxmhkgyib.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gtkwkloejr.html

C#:   public string Greet() => Name;
来源：http://dali.meibo888.top/Article/details/gtvqhbicqc.html

[G05] 继承
来源：http://dali.cdnleiting.top/Article/details/gtwewtrkot.html

Py:   class Admin(User): pass
来源：http://dali.yangfankeji.com/Article/details/gttoiellof.html

PHP:  class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtatapufwh.html

JS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtzgrmllyj.html

TS:   class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtorcqdrbz.html

Java: class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtipprzkuy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcnttwoug.html

Ruby: class Admin < User; end
来源：http://dali.aibaodan.cn/Article/details/gtgbdmeclp.html

C#:   class Admin : User {}
来源：http://dali.zycfv.cn/Article/details/gtnajpackq.html

[G06] 重写方法
来源：http://dali.tian-w.cn/Article/details/gtgbvheinw.html

Py:   def greet(self): return "admin"
来源：http://dali.yangfankeji.com/Article/details/gteqlqemwf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtpqwkghcf.html

JS:   greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtazvptdvu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtvsbdaeyb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gttdvnknpk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.birdmap.top/Article/details/gtathhsarm.html

Ruby: def greet; "admin"; end
来源：http://dali.quarkkingdee.top/Article/details/gtnvgvdona.html

C#:   public override string Greet() => "admin";
来源：http://dali.xinyue.icu/Article/details/gtdlotyyaj.html

[G07] 调用父类方法
来源：http://dali.dianchejie.cn/Article/details/gttjfryaon.html

Py:   super().greet()
来源：http://dali.xinyue.icu/Article/details/gtaapyolij.html

PHP:  parent::greet();
来源：http://dali.svipenyu.cn/Article/details/gtssyhoyxy.html

JS:   super.greet();
来源：http://dali.ydzc1.top/Article/details/gtbiyfpuir.html

TS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtavhcdyfx.html

Java: super.greet();
来源：http://dali.cdnleiting.top/Article/details/gtvyhnfbcv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gotoacloud.top/Article/details/gthtdiybse.html

Ruby: super
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtquxzshqd.html

C#:   base.Greet();
来源：http://dali.xinyue.icu/Article/details/gtzrojilic.html

[G08] 静态方法与属性
来源：http://dali.sysykeji.top/Article/details/gtsuqokazv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pengpengdd.cyou/Article/details/gtlepfgbio.html

PHP:  public static function f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtepazeoqf.html

JS:   static f() {}
来源：http://dali.ppjwa.cn/Article/details/gtofcwrntu.html

TS:   static f(): void {}
来源：http://dali.c1oappe.top/Article/details/gtwpeywmnr.html

Java: static void f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgygdtxfq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gzhubu.top/Article/details/gtblysmxdn.html

Ruby: def self.f; end
来源：http://dali.sweek.top/Article/details/gtfjryjazo.html

C#:   public static void F() {}
来源：http://dali.guannengcc.top/Article/details/gtihgtzhui.html

[G09] 接口 / 抽象类
来源：http://dali.jlsjyb.cn/Article/details/gtbhqakxqy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.feifeiyinyue.top/Article/details/gtcpeipzvm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.andypj.xyz/Article/details/gtpyftbdot.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.redwolf501.top/Article/details/gtjnkrvqay.html

TS:   interface Shape { area(): number; }
来源：http://dali.yuxming.cn/Article/details/gtpbvnytbz.html

Java: interface Shape { double area(); }
来源：http://dali.yuanzhike.top/Article/details/gtbwawywov.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hammf.cn/Article/details/gtezgythec.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cdnleiting.top/Article/details/gtweqllaas.html

C#:   interface IShape { double Area(); }
来源：http://dali.jiagoushi.top/Article/details/gtfstlfnip.html

[G10] 访问控制
来源：http://dali.ppjwa.cn/Article/details/gtkjjsdafv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dashuyun.cn/Article/details/gtwieozlvr.html

PHP:  public / protected / private
来源：http://dali.xinyue.icu/Article/details/gthnwhuule.html

JS:   #private 字段；其余公开
来源：http://dali.guowangkeji.top/Article/details/gtfzghqgbm.html

TS:   public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gtajkezohn.html

Java: public / protected / private / 默认包级
来源：http://dali.jiagoushi.top/Article/details/gtwtiralep.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenlongwang.top/Article/details/gttbxydyuh.html

Ruby: public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gtsthipjvy.html

C#:   public / protected / private / internal
来源：http://dali.hammf.cn/Article/details/gtshqsetqq.html

[G11] getter / setter
来源：http://dali.sysykeji.top/Article/details/gtuvceqzlb.html

Py:   @property 与 @x.setter
来源：http://dali.wangdashe.top/Article/details/gtibbdqlbq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gtmptinjbc.html

JS:   get name() { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gtrgzfgyys.html

TS:   get name(): string { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gtakzzpesh.html

Java: public String getName() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtesqzirrt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gtrawzklep.html

Ruby: attr_accessor :name
来源：http://dali.hnqzz.top/Article/details/gtwffgyuoj.html

C#:   public string Name { get; set; }
来源：http://dali.yuanzhike.top/Article/details/gtgxordqcl.html

[G12] 对象转字符串
来源：http://dali.daria6918.cn/Article/details/gtyroeasdg.html

Py:   def __str__(self): return self.name
来源：http://dali.sweek.top/Article/details/gttoerfvuo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gtciejkgja.html

JS:   toString() { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtedquzimd.html

TS:   toString(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtuchwvfrh.html

Java: @Override public String toString() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtvpxnkojw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtymarrdgp.html

Ruby: def to_s; @name; end
来源：http://dali.nanxinkj.top/Article/details/gtwtskfyax.html

C#:   public override string ToString() => Name;
来源：http://dali.chenlongwang.top/Article/details/gtstzazbmi.html

[G13] 判断对象类型
来源：http://dali.0kj1m.cn/Article/details/gtdtcuoxxg.html

Py:   isinstance(u, User)
来源：http://dali.smart0.xyz/Article/details/gtkhayduhw.html

PHP:  $u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtyflpabvn.html

JS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gtriiboado.html

TS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtfxcnpabp.html

Java: u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtrjafivwe.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sufxvd.cn/Article/details/gtdpzsyybm.html

Ruby: u.is_a?(User)
来源：http://dali.9152youxi.cn/Article/details/gtozdzmvmw.html

C#:   u is User
来源：http://dali.jinqigfzy.top/Article/details/gtzjfurtmk.html

[G14] 数据类 / record
来源：http://dali.yj202588.top/Article/details/gtncudmepm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tian-w.cn/Article/details/gtbcdvjoem.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hongshengwenyu.top/Article/details/gtkafqalmy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daxiang520.top/Article/details/gtxslpllhh.html

TS:   type User = { name: string; age: number };
来源：http://dali.0kj1m.cn/Article/details/gtnhofzchb.html

Java: record User(String name, int age) {}
来源：http://dali.gzhubu.top/Article/details/gtgyzcnuwi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aibaodan.cn/Article/details/gtxfeaqvvy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenzaomai.com/Article/details/gtwwcwqzyx.html

C#:   record User(string Name, int Age);
来源：http://dali.316326.xyz/Article/details/gtmopmqiiu.html

[G15] 枚举
来源：http://dali.jinqigfzy.top/Article/details/gtqyhaellm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenlongwang.top/Article/details/gtdxediqxt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gaohongyu789.top/Article/details/gtmctvvvmp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daxiang520.top/Article/details/gtxnhezbci.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gtsntczgwb.html

Java: enum Color { RED, GREEN }
来源：http://dali.shanyushiyangtech.top/Article/details/gtuycgasos.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tianlin.xyz/Article/details/gtzgdjogij.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigufen.top/Article/details/gtfwtbrxzs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gtttxeozta.html

[G16] 对象转数组 / 字典
来源：http://dali.dianchejie.cn/Article/details/gtpuaoplyf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tanke756.top/Article/details/gthuydyzfj.html

PHP:  get_object_vars($obj);
来源：http://dali.nanxinkj.top/Article/details/gtheanrehl.html

JS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gtubkbyrgn.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgncqabu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxjeysrqg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jiagoushi.top/Article/details/gtjaelosxb.html

Ruby: obj.instance_variables
来源：http://dali.hysaishi.cn/Article/details/gtvazzlkez.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gtxehbhdcr.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtptvrttad.html

H. 异常与错误处理
来源：http://dali.yanxiufei.cn/Article/details/gtmpibctat.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtowzhifzo.html

[H01] try / catch 基础
来源：http://dali.birdmap.top/Article/details/gtdkrtgetz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sweek.top/Article/details/gtsstkowsq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sysykeji.top/Article/details/gtzcdsxdvk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gtjfgacwle.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gtwzjpinvx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenjidiqi.icu/Article/details/gtvybvytvz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.mhx1999.top/Article/details/gteipcryfu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhixingplan.top/Article/details/gtmdanmqph.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.feifeiyinyue.top/Article/details/gtymqvhnkz.html

[H02] finally / ensure 收尾
来源：http://dali.316326.xyz/Article/details/gtsazoxjjl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgfzy.top/Article/details/gtvecphqqa.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gttmqwgpxi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtplhirmbq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtxpwfkctv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtfsstxtru.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.aizwys.cn/Article/details/gtoiyziyvh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.haohaochexian.top/Article/details/gtgbuewvmx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtptcgexqw.html

[H03] 主动抛出异常
来源：http://dali.ppjwa.cn/Article/details/gtykaoavab.html

Py:   raise ValueError("错误信息")
来源：http://dali.birdmap.top/Article/details/gtnpfcwtrx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtunmdmpnb.html

JS:   throw new Error("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtoedffiih.html

TS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gteobnwsmy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtioqiwoti.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.havefunace.top/Article/details/gtgexovnol.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258888.top/Article/details/gtwfehaqtd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtbkpqcyhg.html

[H04] 自定义异常类型
来源：http://dali.zhengqikj.top/Article/details/gtxelmyyxc.html

Py:   class MyError(Exception): pass
来源：http://dali.jianghu66.top/Article/details/gtrjyazcyp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shzxlz.cn/Article/details/gtxvrszpdz.html


<!-- 参考信息 -->