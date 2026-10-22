代发 wailian999

Go:   if s == "" {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mraagwbf.html

Ruby: if s.empty?
来源：http://dali.316326.xyz/Article/details/gt2dklufjqf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ydzc1.top/Article/details/gt2hekawasr.html

[E21] 超长截断加省略号
来源：http://dali.dianchejie.cn/Article/details/gt2qimsvfqo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhiwuduotai.top/Article/details/gt2ypxgwsbs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tanke756.top/Article/details/gt2qqinlcxc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gt2hrlstazi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2swbjnzlt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gt2aviekwln.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sxryk.cn/Article/details/gt2yjzaqikq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gt2kctrnrwp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpzvqko.html

[E22] 字节长度与字符长度
来源：http://dali.svipenyu.cn/Article/details/gt2lvekufak.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yangfankeji.com/Article/details/gt2fkkdbwrj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gt2kctpeezn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2amlqlynx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sysykeji.top/Article/details/gt2cwtgeqqz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2teghukcf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuanzhike.top/Article/details/gt2qrgdqzll.html

Ruby: s.bytesize;  s.length
来源：http://dali.sxryk.cn/Article/details/gt2dvsauswi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.andypj.xyz/Article/details/gt2hpgqgycy.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2blasyqze.html

F. 文件与目录
来源：http://dali.chenjidiqi.icu/Article/details/gt2vrmzcdcq.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2xvlacvcc.html

[F01] 读取整个文件
来源：http://dali.jyoumei.cn/Article/details/gt2vbuengei.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zycfv.cn/Article/details/gt2bqqyfkkc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2pjagpzbi.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yuanzhike.top/Article/details/gt2rppjnasy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cheryme.top/Article/details/gt2bizkusxg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gt2nmuewgml.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sweek.top/Article/details/gt2aplicddm.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2jnehmvxy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2grpowyfw.html

[F02] 逐行读取文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2cstmopia.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.mhx1999.top/Article/details/gt2njbgghxm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2eqviaqlz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2tchqxdhz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2mtwpymja.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jhbclzxz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ppjwa.cn/Article/details/gt2fdlytrus.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj20258.top/Article/details/gt2flnnxjxe.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.pycfn.com/Article/details/gt2oyjripbr.html

[F03] 写入文件（覆盖）
来源：http://dali.0kj1m.cn/Article/details/gt2kldmwmkx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jqgfzy.top/Article/details/gt2twlpiiau.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gotoacloud.top/Article/details/gt2cfouppjm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gt2wovejecs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cucudq.cn/Article/details/gt2ztcwsqgi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ehwqpu.com/Article/details/gt2tbuhkeia.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.havefunace.top/Article/details/gt2uaxxgqnn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj20258.top/Article/details/gt2tkccmfeq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jqgufenzy.top/Article/details/gt2gnnhwdrp.html

[F04] 追加写入文件
来源：http://dali.daxiang520.top/Article/details/gt2udoswacd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gt2wwzvesmd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.feifeiyinyue.top/Article/details/gt2bolcjqmx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wlgwueac.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yangfankeji.com/Article/details/gt2rqlskqrv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cdnleiting.top/Article/details/gt2ypmhbder.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gt2atxpqphv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xziqi.cn/Article/details/gt2zcfdtkin.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnxiangtu.top/Article/details/gt2dndicfzx.html

[F05] 判断文件或目录是否存在
来源：http://dali.smart0.xyz/Article/details/gt2znowyrez.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tcmiugad.html

PHP:  file_exists("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2xwhgsesp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2nnakoiqs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2lrkrfjsc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gt2foxrvauo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj20258888.top/Article/details/gt2ytxrrerv.html

Ruby: File.exist?("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2mfppnipm.html

C#:   File.Exists("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2jrufbyvc.html

[F06] 删除文件
来源：http://dali.yvedp.cn/Article/details/gt2vqhmsjhi.html

Py:   os.remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2clmscuaq.html

PHP:  unlink("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2lsyzkwec.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2lsvnurok.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2tjfiyqat.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gt2vjwwmtud.html

Go:   os.Remove("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2cplvzrmd.html

Ruby: File.delete("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2qxjoxlgg.html

C#:   File.Delete("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2sxxbmwjz.html

[F07] 创建目录（含多级）
来源：http://dali.pengpengdd.cyou/Article/details/gt2tjmkrqtu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.c1oappe.top/Article/details/gt2xmmcwtze.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cheryme.top/Article/details/gt2izfcltak.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gt2ktiqffrx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gt2psunzqxz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2gynaspbt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yuxming.cn/Article/details/gt2sdmfculu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.bjfxy.top/Article/details/gt2tgyrmrod.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xinyue.icu/Article/details/gt2nqombozk.html

[F08] 遍历目录
来源：http://dali.dianchejie.cn/Article/details/gt2kgnsafml.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgufenzy.top/Article/details/gt2nmgzkgmi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2klhqxnhg.html

JS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gt2hfhkgswq.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rrljecwx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gt2ewaflxwu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.fengsongda.top/Article/details/gt2rgkhvjme.html

Ruby: Dir.children("dir")
来源：http://dali.c1oappe.top/Article/details/gt2qaglvool.html

C#:   Directory.GetFiles("dir")
来源：http://dali.andypj.xyz/Article/details/gt2dtfumhej.html

[F09] 获取文件大小
来源：http://dali.guannengcc.top/Article/details/gt2urmapxtn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2zxouynvj.html

PHP:  filesize("a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2wfqmvjgj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258888.top/Article/details/gt2ozsusofb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhiwuduotai.top/Article/details/gt2enjjkded.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gt2dxkykfim.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sysykeji.top/Article/details/gt2piqtblpu.html

Ruby: File.size("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2psruegvn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ydzc1.top/Article/details/gt2ovowyssu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.iojbl.cn/Article/details/gt2bfgginvd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2awmdyaph.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2aypworcg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2kmtufnjt.html

TS:   path.extname("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2ouaukwwb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenzaomai.com/Article/details/gt2pvgxsxvt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qsxzglev.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2bbliepnc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2lfgannmi.html

[F11] 复制与移动文件
来源：http://dali.hfpthk.cn/Article/details/gt2txwqzxcf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2cigskqoo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xwjyhazu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gt2nvqyacok.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2wknjacbb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhengqikj.top/Article/details/gt2khdfhjdk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zycfv.cn/Article/details/gt2vguwubdv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gt2hhposavm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tianlin.xyz/Article/details/gt2aoqrmthp.html

[F12] CSV 读写
来源：http://dali.hnxiangtu.top/Article/details/gt2bryqlyhr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxuanxn.top/Article/details/gt2maqumkpk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eziusvek.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.havefunace.top/Article/details/gt2vyledxpf.html

TS:   // 同上
来源：http://dali.gogol.net.cn/Article/details/gt2wzrsaijl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuanzhike.top/Article/details/gt2odccvhpf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.mhx1999.top/Article/details/gt2hqoioluc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxuanxn.top/Article/details/gt2lvgaaawv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cdnleiting.top/Article/details/gt2rraotamz.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2lgoisggh.html

G. 面向对象
来源：http://dali.cqqwz.cn/Article/details/gt2hucrtpsu.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2ugknczwi.html

[G01] 定义类
来源：http://dali.gzhubu.top/Article/details/gt2mgowkeiw.html

Py:   class User: pass
来源：http://dali.zhixingplan.top/Article/details/gt2cbsvskct.html

PHP:  class User {}
来源：http://dali.mhx1999.top/Article/details/gt2zqwgwemr.html

JS:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gt2ylrvnali.html

TS:   class User { name: string = ""; }
来源：http://dali.hnqzz.top/Article/details/gt2zkwhrenu.html

Java: class User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2nmvwmore.html

Go:   type User struct { Name string }
来源：http://dali.ydzc1.top/Article/details/gt2jussqxjo.html

Ruby: class User; end
来源：http://dali.aibaodan.cn/Article/details/gt2boijplsh.html

C#:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gt2unfmlknh.html

[G02] 构造函数
来源：http://dali.havefunace.top/Article/details/gt2jevtbgpd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cashguo.top/Article/details/gt2ulzwytqv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jianghu66.top/Article/details/gt2rkxeoqxi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zdqjudy.top/Article/details/gt2cduvnkkf.html

TS:   constructor(public name: string) {}
来源：http://dali.xuanzx.com/Article/details/gt2ptsdokil.html

Java: User(String name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gt2csenqeta.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.c1oappe.top/Article/details/gt2kwlxutee.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xylfe.cn/Article/details/gt2kbrjbboj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.svipenyu.cn/Article/details/gt2nkesfmnd.html

[G03] 实例属性
来源：http://dali.wangshuangyany.cn/Article/details/gt2reveidod.html

Py:   self.name = "x"
来源：http://dali.dashuyun.cn/Article/details/gt2bxmgdkgj.html

PHP:  public string $name = "x";
来源：http://dali.316326.xyz/Article/details/gt2eretgtgu.html

JS:   this.name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yaaeywgp.html

TS:   name: string = "x";
来源：http://dali.kuanghao11.cn/Article/details/gt2txtvpbod.html

Java: private String name;
来源：http://dali.0kj1m.cn/Article/details/gt2kxzwmnch.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jianghu66.top/Article/details/gt2cwwmfiym.html

Ruby: @name = "x"
来源：http://dali.yj20258888.top/Article/details/gt2ihtriszy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gogol.net.cn/Article/details/gt2oafgzdhp.html

[G04] 定义方法
来源：http://dali.tanke756.top/Article/details/gt2vjwjdnzi.html

Py:   def greet(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gt2fjhnjyob.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gt2aldgxjzi.html

JS:   greet() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gt2ujcibyxe.html

TS:   greet(): string { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2xffhitih.html

Java: String greet() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2kfujrqau.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gt2kyeavnmu.html

Ruby: def greet; @name; end
来源：http://dali.yongpay.top/Article/details/gt2zbhofofu.html

C#:   public string Greet() => Name;
来源：http://dali.snrcjt.cn/Article/details/gt2bsijeqep.html

[G05] 继承
来源：http://dali.yuanzhike.top/Article/details/gt2hvvuuisp.html

Py:   class Admin(User): pass
来源：http://dali.shzxlz.cn/Article/details/gt2cqvfcral.html

PHP:  class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gt2aejfgmvs.html

JS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gt2jfmxrhgu.html

TS:   class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2ieluznxz.html

Java: class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gt2blraciyt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xylfe.cn/Article/details/gt2ullgtbzt.html

Ruby: class Admin < User; end
来源：http://dali.jianghu66.top/Article/details/gt2jbtdccgj.html

C#:   class Admin : User {}
来源：http://dali.dashuyun.cn/Article/details/gt2qjnrejfs.html

[G06] 重写方法
来源：http://dali.xylfe.cn/Article/details/gt2xaoigled.html

Py:   def greet(self): return "admin"
来源：http://dali.c1oappe.top/Article/details/gt2lcrpesyp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gt2swqeysdn.html

JS:   greet() { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gt2vrxxnuii.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2xlwtqnft.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nmyipzov.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhengqikj.top/Article/details/gt2evawadlr.html

Ruby: def greet; "admin"; end
来源：http://dali.tanke756.top/Article/details/gt2kndhwwsh.html

C#:   public override string Greet() => "admin";
来源：http://dali.jlsjyb.cn/Article/details/gt2xwlwggiu.html

[G07] 调用父类方法
来源：http://dali.smart0.xyz/Article/details/gt2mzaxemwk.html

Py:   super().greet()
来源：http://dali.dianchejie.cn/Article/details/gt2npciaric.html

PHP:  parent::greet();
来源：http://dali.xinyue.icu/Article/details/gt2tnonrdtx.html

JS:   super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gt2xfkhixgf.html

TS:   super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lhbrjomv.html

Java: super.greet();
来源：http://dali.smart0.xyz/Article/details/gt2xouaumdz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shzxlz.cn/Article/details/gt2kcsjyijb.html

Ruby: super
来源：http://dali.ehwqpu.com/Article/details/gt2jxeakycz.html

C#:   base.Greet();
来源：http://dali.yueranfly.top/Article/details/gt2kpkyywgl.html

[G08] 静态方法与属性
来源：http://dali.hywenlv.cn/Article/details/gt2nxvofkew.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.andypj.xyz/Article/details/gt2yaopwsba.html

PHP:  public static function f() {}
来源：http://dali.316326.xyz/Article/details/gt2cilpfirr.html

JS:   static f() {}
来源：http://dali.gzhubu.top/Article/details/gt2sfbqysty.html

TS:   static f(): void {}
来源：http://dali.jqgufenzy.top/Article/details/gt2rzbjdwwb.html

Java: static void f() {}
来源：http://dali.shzxlz.cn/Article/details/gt2vqtgnbdd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fengsongda.top/Article/details/gt2dzeomfso.html

Ruby: def self.f; end
来源：http://dali.daxiang520.top/Article/details/gt2zwnqwipz.html

C#:   public static void F() {}
来源：http://dali.jqgufenzy.top/Article/details/gt2uuhtsfyh.html

[G09] 接口 / 抽象类
来源：http://dali.zdqjudy.top/Article/details/gt2thqmwafo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gogol.net.cn/Article/details/gt2ndgxftsv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.havefunace.top/Article/details/gt2cyufunht.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnxiangtu.top/Article/details/gt2xfwglgtr.html

TS:   interface Shape { area(): number; }
来源：http://dali.sysykeji.top/Article/details/gt2mkttnyss.html

Java: interface Shape { double area(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2dkhjdeix.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yvedp.cn/Article/details/gt2xdzppdaa.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tvdsfklt.html

C#:   interface IShape { double Area(); }
来源：http://dali.sxryk.cn/Article/details/gt2kypvpsvz.html

[G10] 访问控制
来源：http://dali.jianghu66.top/Article/details/gt2zjggpgij.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258888.top/Article/details/gt2qxasacby.html

PHP:  public / protected / private
来源：http://dali.daxiang520.top/Article/details/gt2thxcxrbx.html

JS:   #private 字段；其余公开
来源：http://dali.hnxiangtu.top/Article/details/gt2mcrwnwol.html

TS:   public / protected / private
来源：http://dali.guannengcc.top/Article/details/gt2txjcjowp.html

Java: public / protected / private / 默认包级
来源：http://dali.yonumen.top/Article/details/gt2xbjpbugc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cdnleiting.top/Article/details/gt2rkzdlqoz.html

Ruby: public / protected / private
来源：http://dali.cashguo.top/Article/details/gt2rlcppovw.html

C#:   public / protected / private / internal
来源：http://dali.xinyue.icu/Article/details/gt2jxkpcjxp.html

[G11] getter / setter
来源：http://dali.0kj1m.cn/Article/details/gt2vejlbhja.html

Py:   @property 与 @x.setter
来源：http://dali.smart0.xyz/Article/details/gt2tfvdnuaj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gt2rutyanpt.html

JS:   get name() { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gt2boinocds.html

TS:   get name(): string { return this._name; }
来源：http://dali.xziqi.cn/Article/details/gt2tjohthoq.html

Java: public String getName() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2jwbavntv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gt2ntlwsueu.html

Ruby: attr_accessor :name
来源：http://dali.wangdashe.top/Article/details/gt2bsfuiszi.html

C#:   public string Name { get; set; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2uivysywy.html

[G12] 对象转字符串
来源：http://dali.316326.xyz/Article/details/gt2xkjqxikf.html

Py:   def __str__(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qizepebe.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gt2wzoswyhj.html

JS:   toString() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gt2xevvbfbz.html

TS:   toString(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2llkosqsh.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gt2pvayurpe.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gt2dyzzbdjl.html

Ruby: def to_s; @name; end
来源：http://dali.meibo888.top/Article/details/gt2netxrdye.html

C#:   public override string ToString() => Name;
来源：http://dali.sysykeji.top/Article/details/gt2mpgecocz.html

[G13] 判断对象类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2nseyfuzu.html

Py:   isinstance(u, User)
来源：http://dali.cheryme.top/Article/details/gt2esqlbjyi.html

PHP:  $u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gt2znuefykw.html

JS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hbkpntnp.html

TS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tyvtrrpw.html

Java: u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gt2seqztblg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.iojbl.cn/Article/details/gt2lphqiixx.html

Ruby: u.is_a?(User)
来源：http://dali.cashguo.top/Article/details/gt2ilspznix.html

C#:   u is User
来源：http://dali.jyoumei.cn/Article/details/gt2hvqjigcq.html

[G14] 数据类 / record
来源：http://dali.pycfn.com/Article/details/gt2xabxghwj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ydzc1.top/Article/details/gt2wvxdvsds.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.andypj.xyz/Article/details/gt2oeltdrsp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nanxinkj.top/Article/details/gt2colwanhm.html

TS:   type User = { name: string; age: number };
来源：http://dali.yvedp.cn/Article/details/gt2cmmzymft.html

Java: record User(String name, int age) {}
来源：http://dali.ydzc1.top/Article/details/gt2gqvhhptm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhixingplan.top/Article/details/gt2mrgdofol.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2wclrxfjj.html

C#:   record User(string Name, int Age);
来源：http://dali.wangdashe.top/Article/details/gt2eyqhdlfw.html

[G15] 枚举
来源：http://dali.hnqzz.top/Article/details/gt2zvotpcid.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ivvv.top/Article/details/gt2wxbvacbc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2rejaoghi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.aibaodan.cn/Article/details/gt2mecphssa.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gt2hdytphcy.html

Java: enum Color { RED, GREEN }
来源：http://dali.xuanzx.com/Article/details/gt2miceiyim.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zdqjudy.top/Article/details/gt2gqdxswed.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nwbrower.top/Article/details/gt2annjlgrf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nicimqol.html

[G16] 对象转数组 / 字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2omfwpoye.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tianlin.xyz/Article/details/gt2rnkoanwx.html

PHP:  get_object_vars($obj);
来源：http://dali.zhixingplan.top/Article/details/gt2itkppwps.html

JS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2xpjjpigk.html

TS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2jmkzmkqu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnxiangtu.top/Article/details/gt2bjdcuugd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gogol.net.cn/Article/details/gt2jgxyurhc.html

Ruby: obj.instance_variables
来源：http://dali.meibo888.top/Article/details/gt2wscweapf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gt2fgqrlkgg.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qigfqtmi.html

H. 异常与错误处理
来源：http://dali.yvedp.cn/Article/details/gt2yhyhhleg.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2neifpoeo.html

[H01] try / catch 基础
来源：http://dali.dashuyun.cn/Article/details/gt2iljwpkhd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.smart0.xyz/Article/details/gt2aeinxyqn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj20258888.top/Article/details/gt2ntsqnwgt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gt2corwqlnk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyejggfq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.meibo888.top/Article/details/gt2smpnqymd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ppjwa.cn/Article/details/gt2qtlazwch.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tianlin.xyz/Article/details/gt2titodjik.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aibaodan.cn/Article/details/gt2kzvsiiju.html

[H02] finally / ensure 收尾
来源：http://dali.feifeiyinyue.top/Article/details/gt2gwpxzlqi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgufenzy.top/Article/details/gt2jhfugzxz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2riwqnsut.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gt2nzzdyhet.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2owmjyrqx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gt2xeaicyzk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.aizwys.cn/Article/details/gt2ogjqxfyw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.haohaochexian.top/Article/details/gt2ekopzyyg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yonumen.top/Article/details/gt2epggwlsu.html


<!-- 参考信息 -->