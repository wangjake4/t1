代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jlsjyb.cn/Article/details/gtjpggvvyw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gtbffsnreo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtzviqyews.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtdcfnuqnp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtedpaxjpz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhengqikj.top/Article/details/gtxeiahtpm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtkslqzuzp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtuxaxsbfx.html

[E22] 字节长度与字符长度
来源：http://dali.quarkkingdee.top/Article/details/gtfiaartur.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yonumen.top/Article/details/gtcpynwmqu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtifocrmcf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ivvv.top/Article/details/gtcarsbmpy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuxming.cn/Article/details/gtqfkuazur.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xziqi.cn/Article/details/gtdsakyonu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.kuanghao11.cn/Article/details/gtweozmsty.html

Ruby: s.bytesize;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gtodggngiy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.dashuyun.cn/Article/details/gtsomnaokc.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtnbwipkwj.html

F. 文件与目录
来源：http://dali.yj20258888.top/Article/details/gtmkvvnfgb.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtljtcwdsk.html

[F01] 读取整个文件
来源：http://dali.zdqjudy.top/Article/details/gtaclwdjfz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yvedp.cn/Article/details/gtxvotelfj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yongpay.top/Article/details/gtlldnxhyk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ydzc1.top/Article/details/gtcevseutu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.havefunace.top/Article/details/gtnkifnsfe.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtmtngjsup.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shangyingyoupin.top/Article/details/gtdpbtwqed.html

Ruby: File.read("a.txt")
来源：http://dali.yj20258.top/Article/details/gtkrvvrjiv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sweek.top/Article/details/gtqvqfktwf.html

[F02] 逐行读取文件
来源：http://dali.shzxlz.cn/Article/details/gtgmzxecle.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cashguo.top/Article/details/gtihqqqgqb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.daxiang520.top/Article/details/gtexnqyfzz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zycfv.cn/Article/details/gtybbmjepo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gtcasfixtt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gthgaevmnp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xuanzx.com/Article/details/gtmexwhlpg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj20258.top/Article/details/gtzbhxlkmx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tianlin.xyz/Article/details/gtvteuqsre.html

[F03] 写入文件（覆盖）
来源：http://dali.svipenyu.cn/Article/details/gtvfmaqxvm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.kuanghao11.cn/Article/details/gtkojfarho.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sweek.top/Article/details/gtvswijwuy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daxiang520.top/Article/details/gthwdnrykn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gtnglmrtid.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hfpthk.cn/Article/details/gtnivtuozo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuxming.cn/Article/details/gtueqipmav.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.fzhhl.top/Article/details/gtiwhgxwar.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gtachyevdh.html

[F04] 追加写入文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotjxwrxu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinqigufen.top/Article/details/gtopfhpfmg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zdqjudy.top/Article/details/gtrviiprhm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gtaywgplyg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zycfv.cn/Article/details/gtsmubleqc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.bjfxy.top/Article/details/gticapazdl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tian-w.cn/Article/details/gtexqnhatr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gaohongyu789.top/Article/details/gtssxynihn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gaohongyu789.top/Article/details/gtgothkhnh.html

[F05] 判断文件或目录是否存在
来源：http://dali.wangshuangyany.cn/Article/details/gtyyloobwy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cqqwz.cn/Article/details/gtlhosjlqt.html

PHP:  file_exists("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtfkuxffln.html

JS:   fs.existsSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtvvueeppm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtahmsrnit.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtczjakfbv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zdqjudy.top/Article/details/gtwbgckenw.html

Ruby: File.exist?("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gteoacohob.html

C#:   File.Exists("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtchomthme.html

[F06] 删除文件
来源：http://dali.9152youxi.cn/Article/details/gtrltraupn.html

Py:   os.remove("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtfjwqutde.html

PHP:  unlink("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtnzjkwyfb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtabgoabmu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtfmpsmwjb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gttiplumws.html

Go:   os.Remove("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzocfdjyt.html

Ruby: File.delete("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtcrvahcqw.html

C#:   File.Delete("a.txt");
来源：http://dali.cashguo.top/Article/details/gtjswrmoer.html

[F07] 创建目录（含多级）
来源：http://dali.vqdsnc.cn/Article/details/gttevwsrvm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ivvv.top/Article/details/gtmjmsoqws.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yuxming.cn/Article/details/gtxgocrzrw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cashguo.top/Article/details/gtplohbnuf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gtdnyflian.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.wangdashe.top/Article/details/gtkypyyizd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.wangdashe.top/Article/details/gtxgmvmhlv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jianghu66.top/Article/details/gtynnqmphj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cdnleiting.top/Article/details/gtgaluiist.html

[F08] 遍历目录
来源：http://dali.hongshengwenyu.top/Article/details/gtbgdziwzm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cqqwz.cn/Article/details/gtsuzrizba.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.bjfxy.top/Article/details/gtdgitdgtm.html

JS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gtartvhoun.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gttaohgjnp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.0kj1m.cn/Article/details/gtkuffvlex.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shuidangran.top/Article/details/gtyqqifxxy.html

Ruby: Dir.children("dir")
来源：http://dali.cucudq.cn/Article/details/gtnjgksaua.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tianlin.xyz/Article/details/gtagjoyuzh.html

[F09] 获取文件大小
来源：http://dali.vqdsnc.cn/Article/details/gtyumombzs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtghlgrsgk.html

PHP:  filesize("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtfysursdh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gtagqlgvqx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gtmrypglrz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtnussinyp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangshuangyany.cn/Article/details/gtajokrkhx.html

Ruby: File.size("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtiyantwjs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hysaishi.cn/Article/details/gtwmsilebx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hongshengwenyu.top/Article/details/gtjkpxxuao.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtxubzglsb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtqdttxzqm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtdrpwhrlf.html

TS:   path.extname("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsbfvkdnj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yuxming.cn/Article/details/gteyenezhg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gttlazzwbx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtdeufxqlx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtdosbxyxe.html

[F11] 复制与移动文件
来源：http://dali.zycfv.cn/Article/details/gtjddtwslz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gteddddorj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.redwolf501.top/Article/details/gtmppfzrdw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtlbnkrocg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtluymfuzl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gotoacloud.top/Article/details/gtcbcjhkuz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nanxuanxn.top/Article/details/gtsoxcomfi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gtfxwadyij.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.mhx1999.top/Article/details/gtqhpywpjz.html

[F12] CSV 读写
来源：http://dali.jinghuilouyu.cn/Article/details/gtcegrzequ.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ivvv.top/Article/details/gtifhdmjor.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hammf.cn/Article/details/gtgbkoykti.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tianlin.xyz/Article/details/gtcrqlkcll.html

TS:   // 同上
来源：http://dali.xinyue.icu/Article/details/gtmnlphtzh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhoulong.xyz/Article/details/gtaclaitvb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.svipenyu.cn/Article/details/gtokivzbhq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhiwuduotai.top/Article/details/gtteluelfc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shuidangran.top/Article/details/gtboirqprn.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtfywkekil.html

G. 面向对象
来源：http://dali.xuanzx.com/Article/details/gtfjtwthlq.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtcgelzwzl.html

[G01] 定义类
来源：http://dali.jinqigufen.top/Article/details/gtqblbojak.html

Py:   class User: pass
来源：http://dali.iojbl.cn/Article/details/gtecsukywf.html

PHP:  class User {}
来源：http://dali.jqgfzy.top/Article/details/gttovylkwr.html

JS:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gtldakddqm.html

TS:   class User { name: string = ""; }
来源：http://dali.jlsjyb.cn/Article/details/gtvycnjvur.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gtbearxuiq.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gttryeaesb.html

Ruby: class User; end
来源：http://dali.dianchejie.cn/Article/details/gtxtjhzfme.html

C#:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtqcyihfjo.html

[G02] 构造函数
来源：http://dali.mhx1999.top/Article/details/gtlmftydob.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.birdmap.top/Article/details/gtzsqxrzpr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.redwolf501.top/Article/details/gtepqfwxqc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gtkgggqwlw.html

TS:   constructor(public name: string) {}
来源：http://dali.sxryk.cn/Article/details/gtokpnsios.html

Java: User(String name) { this.name = name; }
来源：http://dali.sufxvd.cn/Article/details/gtxjkmiomh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tianlin.xyz/Article/details/gtpaecuppi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aibaodan.cn/Article/details/gtfaqqnfcs.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gthbuipgkq.html

[G03] 实例属性
来源：http://dali.yj20258.top/Article/details/gtfrfjjhwv.html

Py:   self.name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gttzaqbgxf.html

PHP:  public string $name = "x";
来源：http://dali.cashguo.top/Article/details/gttxlrlhtf.html

JS:   this.name = "x";
来源：http://dali.316326.xyz/Article/details/gtchlyxabd.html

TS:   name: string = "x";
来源：http://dali.gzhubu.top/Article/details/gtipdtfhrb.html

Java: private String name;
来源：http://dali.fzhhl.top/Article/details/gtjkkoffkm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhengqikj.top/Article/details/gtigfncxtu.html

Ruby: @name = "x"
来源：http://dali.cqqwz.cn/Article/details/gtbdxwbgqc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtdidkpkdg.html

[G04] 定义方法
来源：http://dali.zhongyouzk.top/Article/details/gtxzlbdykm.html

Py:   def greet(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gtfvjkjvgs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gtlburbvep.html

JS:   greet() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtrzqprdzw.html

TS:   greet(): string { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gtfslftbpg.html

Java: String greet() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtpchcmmmg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gtpjaqroxi.html

Ruby: def greet; @name; end
来源：http://dali.shzxlz.cn/Article/details/gttcwhzayy.html

C#:   public string Greet() => Name;
来源：http://dali.quarkkingdee.top/Article/details/gtblsxpmqh.html

[G05] 继承
来源：http://dali.xuetiantiany.cn/Article/details/gtfbcuixgw.html

Py:   class Admin(User): pass
来源：http://dali.zhongyouzk.top/Article/details/gtxxnltgql.html

PHP:  class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtycklxjeo.html

JS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gttstsuimd.html

TS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtisavhtfi.html

Java: class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtsqvkmake.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxinkj.top/Article/details/gtthkpuawk.html

Ruby: class Admin < User; end
来源：http://dali.xuetiantiany.cn/Article/details/gtvkhpzhhj.html

C#:   class Admin : User {}
来源：http://dali.c1oappe.top/Article/details/gtxohjlbef.html

[G06] 重写方法
来源：http://dali.shangyingyoupin.top/Article/details/gtxydjxrpi.html

Py:   def greet(self): return "admin"
来源：http://dali.daria6918.cn/Article/details/gtwzzawbgl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtnmnsthng.html

JS:   greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtzdljabjr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtplpwwngw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvzpxbdi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gtjdvobwyu.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiejjldxv.html

C#:   public override string Greet() => "admin";
来源：http://dali.guowangkeji.top/Article/details/gtnvmbqfvm.html

[G07] 调用父类方法
来源：http://dali.sysykeji.top/Article/details/gtbxxibwkm.html

Py:   super().greet()
来源：http://dali.andypj.xyz/Article/details/gtyztmfwhx.html

PHP:  parent::greet();
来源：http://dali.jlsjyb.cn/Article/details/gtphmkaktx.html

JS:   super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtcnirgpvm.html

TS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gtrhhwwjld.html

Java: super.greet();
来源：http://dali.dianchejie.cn/Article/details/gtcikffzem.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinqigfzy.top/Article/details/gtsbqcvygm.html

Ruby: super
来源：http://dali.sweek.top/Article/details/gtuwfzggdl.html

C#:   base.Greet();
来源：http://dali.sxryk.cn/Article/details/gtkfxkuyfz.html

[G08] 静态方法与属性
来源：http://dali.xinyue.icu/Article/details/gtfuhzfpyf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gtlcsidznv.html

PHP:  public static function f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtkonpvbuy.html

JS:   static f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtvpdkoksa.html

TS:   static f(): void {}
来源：http://dali.iojbl.cn/Article/details/gtaphqwzhv.html

Java: static void f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzliiwiu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.daxiang520.top/Article/details/gtmymvwgjw.html

Ruby: def self.f; end
来源：http://dali.ivvv.top/Article/details/gtifguczwy.html

C#:   public static void F() {}
来源：http://dali.gaohongyu789.top/Article/details/gttnnreduc.html

[G09] 接口 / 抽象类
来源：http://dali.kuanghao11.cn/Article/details/gteuakbcah.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gzhubu.top/Article/details/gtsfkrbicv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhoulong.xyz/Article/details/gtzuwwuapy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhongyouzk.top/Article/details/gticaztvmw.html

TS:   interface Shape { area(): number; }
来源：http://dali.fengsongda.top/Article/details/gtlzeyssmw.html

Java: interface Shape { double area(); }
来源：http://dali.yvedp.cn/Article/details/gtxcjejrkx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigfzy.top/Article/details/gtvndhifgo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hfpthk.cn/Article/details/gtbujinzdc.html

C#:   interface IShape { double Area(); }
来源：http://dali.daria6918.cn/Article/details/gtybrbejro.html

[G10] 访问控制
来源：http://dali.haohaochexian.top/Article/details/gtkxyalplx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.9152youxi.cn/Article/details/gtihsadfga.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gtibglutrz.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gtuqtdzomp.html

TS:   public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gtiaiwoxsg.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangtech.top/Article/details/gtwlktjspr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jianghu66.top/Article/details/gtwdsytxsi.html

Ruby: public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtijkutgnt.html

C#:   public / protected / private / internal
来源：http://dali.jqgufenzy.top/Article/details/gtacfkjcjb.html

[G11] getter / setter
来源：http://dali.meibo888.top/Article/details/gtgswowidy.html

Py:   @property 与 @x.setter
来源：http://dali.0kj1m.cn/Article/details/gtolrkficp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtldwhudqu.html

JS:   get name() { return this._name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlpoyneoc.html

TS:   get name(): string { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gtkyvbwarq.html

Java: public String getName() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtdtmsezgr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gtiadqcjao.html

Ruby: attr_accessor :name
来源：http://dali.hywenlv.cn/Article/details/gtifytvwbo.html

C#:   public string Name { get; set; }
来源：http://dali.havefunace.top/Article/details/gtvxhsfhot.html

[G12] 对象转字符串
来源：http://dali.gaohongyu789.top/Article/details/gturmwqlkx.html

Py:   def __str__(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gtvaxabxki.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gtoecdlihx.html

JS:   toString() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gttowqyirn.html

TS:   toString(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtqtsotcay.html

Java: @Override public String toString() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtvqfrslvx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtyjvvytbi.html

Ruby: def to_s; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtuacufbwz.html

C#:   public override string ToString() => Name;
来源：http://dali.dianchejie.cn/Article/details/gtuekpcsfb.html

[G13] 判断对象类型
来源：http://dali.jinqigufen.top/Article/details/gtrxafexjt.html

Py:   isinstance(u, User)
来源：http://dali.9152youxi.cn/Article/details/gtrnmuejyg.html

PHP:  $u instanceof User
来源：http://dali.havefunace.top/Article/details/gtlomkdofp.html

JS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtrjstuirj.html

TS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gtgmkwfyeb.html

Java: u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtlfazfdsq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ehwqpu.com/Article/details/gtxavhmoor.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gthhttfhvf.html

C#:   u is User
来源：http://dali.ivvv.top/Article/details/gtubqlxpkq.html

[G14] 数据类 / record
来源：http://dali.pengpengdd.cyou/Article/details/gtnikbpirx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tanke756.top/Article/details/gtbtxmlfru.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yongpay.top/Article/details/gtavggpotz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ivvv.top/Article/details/gtgnbxmkvn.html

TS:   type User = { name: string; age: number };
来源：http://dali.vqdsnc.cn/Article/details/gtlqsnrqzz.html

Java: record User(String name, int age) {}
来源：http://dali.xziqi.cn/Article/details/gtorhkxwes.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pycfn.com/Article/details/gtsstcyuel.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jqgufenzy.top/Article/details/gtujeqxnbd.html

C#:   record User(string Name, int Age);
来源：http://dali.yongpay.top/Article/details/gtiulfpzjx.html

[G15] 枚举
来源：http://dali.zhongyouzk.top/Article/details/gtsmwssuaw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.dashuyun.cn/Article/details/gtwmfdawey.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtoyojtbvh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yangfankeji.com/Article/details/gtkjrgikvu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnqzz.top/Article/details/gtokhmglfo.html

Java: enum Color { RED, GREEN }
来源：http://dali.pycfn.com/Article/details/gthbfxique.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgwaapfzp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.daxiang520.top/Article/details/gtuuygvokg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnnqehmwj.html

[G16] 对象转数组 / 字典
来源：http://dali.ehwqpu.com/Article/details/gtzuygtovk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sweek.top/Article/details/gtgmmfvtou.html

PHP:  get_object_vars($obj);
来源：http://dali.redwolf501.top/Article/details/gtcnroonih.html

JS:   Object.entries(obj)
来源：http://dali.0kj1m.cn/Article/details/gtegdngoaz.html

TS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gtskidabri.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jlsjyb.cn/Article/details/gtklyokenz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hfpthk.cn/Article/details/gtseattrss.html

Ruby: obj.instance_variables
来源：http://dali.cqqwz.cn/Article/details/gtpfgzhvcq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.meibo888.top/Article/details/gtilivqgwa.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gthxltdffl.html

H. 异常与错误处理
来源：http://dali.redwolf501.top/Article/details/gtiusqdegz.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtekatdvhb.html

[H01] try / catch 基础
来源：http://dali.yongpay.top/Article/details/gtjjgyznqf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.haohaochexian.top/Article/details/gtkqfvgtqh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xuanzx.com/Article/details/gtsuidpdhu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gttuwkwwyc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gtzbkxwvhz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.c1oappe.top/Article/details/gtdbitzpld.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.quarkkingdee.top/Article/details/gtzoegkqlh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.iojbl.cn/Article/details/gthfrawwsr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258.top/Article/details/gtyntibawe.html

[H02] finally / ensure 收尾
来源：http://dali.zhengqikj.top/Article/details/gtpqvxgcxi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yonumen.top/Article/details/gtldduscca.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtitfmefjc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtznuacoqp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtjmltysog.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtgglbjzvg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xziqi.cn/Article/details/gtklmxruxc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daria6918.cn/Article/details/gtehkqclza.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtfputkyui.html

[H03] 主动抛出异常
来源：http://dali.ppjwa.cn/Article/details/gtslovuklo.html

Py:   raise ValueError("错误信息")
来源：http://dali.yonumen.top/Article/details/gtnasujoth.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtjjgwgcas.html

JS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtnemqalmt.html


<!-- 参考信息 -->