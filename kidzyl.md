代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gtdlrtxxcm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.mhx1999.top/Article/details/gtioufsnaj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj20258.top/Article/details/gtqvfwxwwk.html

Ruby: s.bytesize;  s.length
来源：http://dali.wangdashe.top/Article/details/gtqqsaakbc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ivvv.top/Article/details/gtovragdjh.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtndokeprw.html

F. 文件与目录
来源：http://dali.ppjwa.cn/Article/details/gtggvvhmbr.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtrkhzgmoa.html

[F01] 读取整个文件
来源：http://dali.wangshuangyany.cn/Article/details/gtplmratrv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xuanzx.com/Article/details/gtenmvhzdb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ivvv.top/Article/details/gtxakxotsw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xziqi.cn/Article/details/gtcuivvblh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yonumen.top/Article/details/gthnggcyet.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtrzflvqvj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgufenzy.top/Article/details/gtvxzbxzzt.html

Ruby: File.read("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtffzkuvud.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtsmycgakx.html

[F02] 逐行读取文件
来源：http://dali.zhoulong.xyz/Article/details/gtxylaidsm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.bjfxy.top/Article/details/gtjwratmox.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xinyue.icu/Article/details/gtgewgptga.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxuanxn.top/Article/details/gttgqqeqtv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigfzy.top/Article/details/gtdfjmacxr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.snrcjt.cn/Article/details/gtquxknirp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.daxiang520.top/Article/details/gtaekklkiq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.svipenyu.cn/Article/details/gtppvkrvci.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.mhx1999.top/Article/details/gtelujxrsl.html

[F03] 写入文件（覆盖）
来源：http://dali.jqgufenzy.top/Article/details/gtkcmirvvr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cheryme.top/Article/details/gthshhnaew.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yanxiufei.cn/Article/details/gtaaaklayx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gtlitwfumw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtdsnnsaos.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj20258.top/Article/details/gtcmsslfyf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuanzhike.top/Article/details/gttzlafrtj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ydzc1.top/Article/details/gtbqdhupkm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtmwqnylgt.html

[F04] 追加写入文件
来源：http://dali.gogol.net.cn/Article/details/gtykhqilwc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnluqzvih.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yvedp.cn/Article/details/gteoytrjrs.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnqzz.top/Article/details/gtcjwaxovd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cheryme.top/Article/details/gtnutlnljz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.andypj.xyz/Article/details/gtpkeyyggg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxinkj.top/Article/details/gtogsbuyow.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dashuyun.cn/Article/details/gtlcbrzbni.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.daria6918.cn/Article/details/gtzftuyydi.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigfzy.top/Article/details/gtlkswpbne.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guannengcc.top/Article/details/gtjqeopbfy.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtbybsjtcj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtombhawvx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtfhewcygo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtzoslwbgw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ivvv.top/Article/details/gtrawmoogl.html

Ruby: File.exist?("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtkunhcswm.html

C#:   File.Exists("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtilgibgpo.html

[F06] 删除文件
来源：http://dali.jlsjyb.cn/Article/details/gtnoxatfwo.html

Py:   os.remove("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtjyiwqxft.html

PHP:  unlink("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtolatgnrh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtezkaliaq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtriyhejqe.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtjdunaglj.html

Go:   os.Remove("a.txt")
来源：http://dali.ivvv.top/Article/details/gtevodjxft.html

Ruby: File.delete("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxjaelha.html

C#:   File.Delete("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtjplvdmye.html

[F07] 创建目录（含多级）
来源：http://dali.hongshengwenyu.top/Article/details/gtgxewsucz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ehwqpu.com/Article/details/gtuzsuttiw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.quarkkingdee.top/Article/details/gtlllshfod.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tian-w.cn/Article/details/gtzqgpixfi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.bjfxy.top/Article/details/gtrhirblic.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnxiangtu.top/Article/details/gtuyhzgivu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tanke756.top/Article/details/gtvvbkdrqg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jianghu66.top/Article/details/gthqeutwhy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ppjwa.cn/Article/details/gtuqamrhvi.html

[F08] 遍历目录
来源：http://dali.ybcxt.top/Article/details/gtevoikwsz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.9152youxi.cn/Article/details/gtzogkahcp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.iojbl.cn/Article/details/gthjzucdrd.html

JS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gthjbjbheo.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gtvviztzwv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtputivqgp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sysykeji.top/Article/details/gtwxqjnvxv.html

Ruby: Dir.children("dir")
来源：http://dali.dianchejie.cn/Article/details/gtrjpaugxy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhengqikj.top/Article/details/gtgkdjqacc.html

[F09] 获取文件大小
来源：http://dali.yanxiufei.cn/Article/details/gtwtunvxtl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.meibo888.top/Article/details/gtszrjeewj.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtkobxwwfo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.mhx1999.top/Article/details/gtzpdfcemp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gttrbybxbu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtkdegqhld.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nanxinkj.top/Article/details/gtknbrqnpc.html

Ruby: File.size("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtdksedpmr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfwgpokx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenzaomai.com/Article/details/gtnzsldhrn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtsmjynrvg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtzvigaquo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtwggswcwg.html

TS:   path.extname("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gturknlioz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenzaomai.com/Article/details/gtqbnbttti.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtmersktmd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtaffqydcw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtywozkivb.html

[F11] 复制与移动文件
来源：http://dali.hywenlv.cn/Article/details/gtzhdbgowf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtpdimhsme.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zycfv.cn/Article/details/gthdjrlvos.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtczbnlnnn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtxikhubab.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gzhubu.top/Article/details/gtyjamtqyk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhengqikj.top/Article/details/gthjjvtxkb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtrttjmjxu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yangfankeji.com/Article/details/gtadawbrti.html

[F12] CSV 读写
来源：http://dali.xylfe.cn/Article/details/gtxomcynrp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.snrcjt.cn/Article/details/gtjccwbefi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.havefunace.top/Article/details/gtpcakyhbv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.guannengcc.top/Article/details/gtscdvfhqj.html

TS:   // 同上
来源：http://dali.ehwqpu.com/Article/details/gtqgbknwjw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yvedp.cn/Article/details/gtauqenlxa.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yvedp.cn/Article/details/gtirudqwst.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.svipenyu.cn/Article/details/gtxcbfkcda.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tian-w.cn/Article/details/gtrwaxpoil.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtfxejdxgm.html

G. 面向对象
来源：http://dali.c1oappe.top/Article/details/gtukdlzirm.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgaiosyr.html

[G01] 定义类
来源：http://dali.chenlongwang.top/Article/details/gthizxirqx.html

Py:   class User: pass
来源：http://dali.kuanghao11.cn/Article/details/gtnuipecnx.html

PHP:  class User {}
来源：http://dali.sysykeji.top/Article/details/gthmpqwevf.html

JS:   class User {}
来源：http://dali.wangdashe.top/Article/details/gtktggklll.html

TS:   class User { name: string = ""; }
来源：http://dali.yuxming.cn/Article/details/gtuybhqukg.html

Java: class User {}
来源：http://dali.zycfv.cn/Article/details/gtubmwsjgv.html

Go:   type User struct { Name string }
来源：http://dali.yvedp.cn/Article/details/gtalwuhrrv.html

Ruby: class User; end
来源：http://dali.redwolf501.top/Article/details/gtdiarjqdu.html

C#:   class User {}
来源：http://dali.yongpay.top/Article/details/gtfunbentk.html

[G02] 构造函数
来源：http://dali.nanxinkj.top/Article/details/gtxauyatej.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xinyue.icu/Article/details/gttfmypadm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.svipenyu.cn/Article/details/gtpdqnmfws.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gthdvgymdv.html

TS:   constructor(public name: string) {}
来源：http://dali.redwolf501.top/Article/details/gtrckvyhee.html

Java: User(String name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtagsoyqph.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zycfv.cn/Article/details/gtmcfojgrt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sweek.top/Article/details/gtfhbukbow.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hnqzz.top/Article/details/gtdrvlxjbq.html

[G03] 实例属性
来源：http://dali.0kj1m.cn/Article/details/gtltfmcigm.html

Py:   self.name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gtvqpanufs.html

PHP:  public string $name = "x";
来源：http://dali.sufxvd.cn/Article/details/gtcgnrmuwz.html

JS:   this.name = "x";
来源：http://dali.yvedp.cn/Article/details/gtrxvucfed.html

TS:   name: string = "x";
来源：http://dali.hysaishi.cn/Article/details/gtobyoyrel.html

Java: private String name;
来源：http://dali.zdqjudy.top/Article/details/gtcvetzwws.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.dashuyun.cn/Article/details/gtqfikgett.html

Ruby: @name = "x"
来源：http://dali.gzhubu.top/Article/details/gtimupqhet.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.0kj1m.cn/Article/details/gtyqagbfry.html

[G04] 定义方法
来源：http://dali.yanxiufei.cn/Article/details/gtcjphdjpd.html

Py:   def greet(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gtgvnvwdmb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtrximoiwp.html

JS:   greet() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gttzvuidvp.html

TS:   greet(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtssqnnaxt.html

Java: String greet() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtrifrjgwh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gtdixltstu.html

Ruby: def greet; @name; end
来源：http://dali.haohaochexian.top/Article/details/gtbosdsqxc.html

C#:   public string Greet() => Name;
来源：http://dali.aibaodan.cn/Article/details/gtfllcnzeb.html

[G05] 继承
来源：http://dali.jinqigfzy.top/Article/details/gtreodwyne.html

Py:   class Admin(User): pass
来源：http://dali.tian-w.cn/Article/details/gtodybnfhe.html

PHP:  class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtvawotrwz.html

JS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gthouuabcv.html

TS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwnlaarg.html

Java: class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdrfhwzib.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuanzhike.top/Article/details/gtsbdzcrsa.html

Ruby: class Admin < User; end
来源：http://dali.ehwqpu.com/Article/details/gtcnfoxejv.html

C#:   class Admin : User {}
来源：http://dali.zhongyouzk.top/Article/details/gtguldcpcb.html

[G06] 重写方法
来源：http://dali.c1oappe.top/Article/details/gthweoziwe.html

Py:   def greet(self): return "admin"
来源：http://dali.havefunace.top/Article/details/gtuvmgovru.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtibvukjvl.html

JS:   greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtjnlmwdxf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtvqvpukek.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtwlepmgth.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daria6918.cn/Article/details/gtzjkrftmz.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgdcvtmf.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvmysoaqb.html

[G07] 调用父类方法
来源：http://dali.nwbrower.top/Article/details/gteytctsvn.html

Py:   super().greet()
来源：http://dali.yuanzhike.top/Article/details/gtbqcyemfh.html

PHP:  parent::greet();
来源：http://dali.ydzc1.top/Article/details/gtvrbaywwt.html

JS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtccssjwkd.html

TS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gtgjkqydaq.html

Java: super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtucpatcqg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hywenlv.cn/Article/details/gtajafwsdz.html

Ruby: super
来源：http://dali.sweek.top/Article/details/gtrrtemewh.html

C#:   base.Greet();
来源：http://dali.smart0.xyz/Article/details/gtififfrcz.html

[G08] 静态方法与属性
来源：http://dali.gogol.net.cn/Article/details/gtuhodgusj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.dashuyun.cn/Article/details/gtmvicddoz.html

PHP:  public static function f() {}
来源：http://dali.jqgfzy.top/Article/details/gtishpdzmp.html

JS:   static f() {}
来源：http://dali.zhengqikj.top/Article/details/gteehqmfzv.html

TS:   static f(): void {}
来源：http://dali.hammf.cn/Article/details/gtzoqbatpm.html

Java: static void f() {}
来源：http://dali.daxiang520.top/Article/details/gtjhgxqwmr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnqzz.top/Article/details/gtshbbxbsq.html

Ruby: def self.f; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmyawatxd.html

C#:   public static void F() {}
来源：http://dali.ivvv.top/Article/details/gtuenqolbd.html

[G09] 接口 / 抽象类
来源：http://dali.smart0.xyz/Article/details/gtvgbjodfg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jyoumei.cn/Article/details/gtbvcnsemn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ppjwa.cn/Article/details/gtkzygnvcl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenlongwang.top/Article/details/gtwkcnqlqa.html

TS:   interface Shape { area(): number; }
来源：http://dali.sweek.top/Article/details/gtqkwgxtlr.html

Java: interface Shape { double area(); }
来源：http://dali.guowangkeji.top/Article/details/gtslchbymc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhiwuduotai.top/Article/details/gtriciowjv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhnpmmrk.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtzgllgygp.html

[G10] 访问控制
来源：http://dali.iojbl.cn/Article/details/gtobjmltkx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258888.top/Article/details/gtploeusyd.html

PHP:  public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gtvovwjiqe.html

JS:   #private 字段；其余公开
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfmxfiap.html

TS:   public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtognozcpx.html

Java: public / protected / private / 默认包级
来源：http://dali.ivvv.top/Article/details/gtnyxphpxa.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxyfmnvx.html

Ruby: public / protected / private
来源：http://dali.meibo888.top/Article/details/gtglicbyax.html

C#:   public / protected / private / internal
来源：http://dali.nanxinkj.top/Article/details/gtvjcaxjpc.html

[G11] getter / setter
来源：http://dali.jinqigufen.top/Article/details/gtmbfdtxzd.html

Py:   @property 与 @x.setter
来源：http://dali.havefunace.top/Article/details/gtwqsexdpk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtsoztbgil.html

JS:   get name() { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqtunuorw.html

TS:   get name(): string { return this._name; }
来源：http://dali.yonumen.top/Article/details/gtcejukcsy.html

Java: public String getName() { return name; }
来源：http://dali.sxryk.cn/Article/details/gtvnrefibl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtxohhasiy.html

Ruby: attr_accessor :name
来源：http://dali.yj20258888.top/Article/details/gtmfxbmtzs.html

C#:   public string Name { get; set; }
来源：http://dali.snrcjt.cn/Article/details/gtvjjhtfqb.html

[G12] 对象转字符串
来源：http://dali.snrcjt.cn/Article/details/gtykydlyqk.html

Py:   def __str__(self): return self.name
来源：http://dali.sysykeji.top/Article/details/gtyaisdyif.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gtfmodzpez.html

JS:   toString() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtmqdbhiyy.html

TS:   toString(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtwsjkjvla.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangdashe.top/Article/details/gtsetmepdg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gthpxyhkph.html

Ruby: def to_s; @name; end
来源：http://dali.hysaishi.cn/Article/details/gtgskgphkh.html

C#:   public override string ToString() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvogcmerk.html

[G13] 判断对象类型
来源：http://dali.pengpengdd.cyou/Article/details/gtqvdtwnzk.html

Py:   isinstance(u, User)
来源：http://dali.cheryme.top/Article/details/gtfranwanu.html

PHP:  $u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtwpdjqjnh.html

JS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtwglzipic.html

TS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqnxjdvv.html

Java: u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtzkmbotxm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zycfv.cn/Article/details/gtoamjxvsi.html

Ruby: u.is_a?(User)
来源：http://dali.birdmap.top/Article/details/gtcvrwplsf.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gtwnslnris.html

[G14] 数据类 / record
来源：http://dali.guannengcc.top/Article/details/gtxpoydxqm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.snrcjt.cn/Article/details/gtdfarlwao.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.redwolf501.top/Article/details/gtdpzdbeci.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ehwqpu.com/Article/details/gtdgpzxdhi.html

TS:   type User = { name: string; age: number };
来源：http://dali.birdmap.top/Article/details/gtrcsrqhuo.html

Java: record User(String name, int age) {}
来源：http://dali.gzhubu.top/Article/details/gtzgjqbsji.html

Go:   type User struct { Name string; Age int }
来源：http://dali.kuanghao11.cn/Article/details/gtvnibsrln.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinqigufen.top/Article/details/gttzcvpdpo.html

C#:   record User(string Name, int Age);
来源：http://dali.ppjwa.cn/Article/details/gtbfkvoula.html

[G15] 枚举
来源：http://dali.xuetiantiany.cn/Article/details/gtwkwsjhhf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgufenzy.top/Article/details/gtcykyokot.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yvedp.cn/Article/details/gtfnoqgjiv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuetiantiany.cn/Article/details/gtsgpgfmoc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gtgahqarsh.html

Java: enum Color { RED, GREEN }
来源：http://dali.gzhubu.top/Article/details/gtlyowounf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daxiang520.top/Article/details/gtuktnxzjt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xylfe.cn/Article/details/gttglreecc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gtsapnopry.html

[G16] 对象转数组 / 字典
来源：http://dali.fengsongda.top/Article/details/gtsldogrzd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aibaodan.cn/Article/details/gttakuschp.html

PHP:  get_object_vars($obj);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnwldrnvi.html

JS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gtralfxxvx.html

TS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtokhuifgd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnqzz.top/Article/details/gtttlpifyf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aibaodan.cn/Article/details/gtclzedgqh.html

Ruby: obj.instance_variables
来源：http://dali.zhiwuduotai.top/Article/details/gtrsicoeno.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aibaodan.cn/Article/details/gthcprudkd.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtjjuhqheu.html

H. 异常与错误处理
来源：http://dali.yonumen.top/Article/details/gtgatesqln.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtdofdogzo.html

[H01] try / catch 基础
来源：http://dali.sweek.top/Article/details/gtzwfdivqt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhiwuduotai.top/Article/details/gtnixoqkve.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtzqypyeyd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gtzirilogx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gtxdavvxzn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnqzz.top/Article/details/gtytpkgrnb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.vqdsnc.cn/Article/details/gtvdfqhdvj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aibaodan.cn/Article/details/gtqfuotamp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.0kj1m.cn/Article/details/gttnpwrycf.html

[H02] finally / ensure 收尾
来源：http://dali.dashuyun.cn/Article/details/gtufnepkyc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhoulong.xyz/Article/details/gtqizabwmx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtydvpnxnm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtxxbnendz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtvpbvyner.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtnsprgrgo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgufenzy.top/Article/details/gttrqrdltk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tianlin.xyz/Article/details/gtllcgyjjx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtyjeeafwe.html

[H03] 主动抛出异常
来源：http://dali.jqgufenzy.top/Article/details/gtysoyvdgd.html

Py:   raise ValueError("错误信息")
来源：http://dali.guowangkeji.top/Article/details/gtbgwupfba.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwhozxrz.html

JS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtobjqgwpb.html

TS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtqjjubmpn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtckdabfoh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hammf.cn/Article/details/gttyzeiofs.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.vqdsnc.cn/Article/details/gtfcwnbwex.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtcokaxwhc.html

[H04] 自定义异常类型
来源：http://dali.gaohongyu789.top/Article/details/gttjdpvrkm.html

Py:   class MyError(Exception): pass
来源：http://dali.svipenyu.cn/Article/details/gtzrynnans.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gtbdlhvrrt.html

JS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gtyskxdybe.html

TS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gtmvwdktxw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gtaidzkusr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sysykeji.top/Article/details/gteckubmvb.html


<!-- 参考信息 -->