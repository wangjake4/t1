代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.havefunace.top/Article/details/gtemsdugie.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cucudq.cn/Article/details/gtlzulcpbs.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gaohongyu789.top/Article/details/gtljhasiud.html

Ruby: s.bytesize;  s.length
来源：http://dali.tanke756.top/Article/details/gttjgbbwju.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhongyouzk.top/Article/details/gtphaktcpd.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtvmsrwqwa.html

F. 文件与目录
来源：http://dali.jqgufenzy.top/Article/details/gtjjukiqsc.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtskbclcoj.html

[F01] 读取整个文件
来源：http://dali.aibaodan.cn/Article/details/gtkmejxagi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.c1oappe.top/Article/details/gtgarkbzqb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtyholruzy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ppjwa.cn/Article/details/gtuqwilnpl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gtsfofyces.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtipjkvvkv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.316326.xyz/Article/details/gtxwcwxehv.html

Ruby: File.read("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtswnadwth.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtmferkgjp.html

[F02] 逐行读取文件
来源：http://dali.nanxuanxn.top/Article/details/gtnezvazwj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ydzc1.top/Article/details/gtlgawiwtn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhongyouzk.top/Article/details/gtxpahdxco.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gtysueihwq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gtqnoqiesr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gtnhbkssnm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shzxlz.cn/Article/details/gtelxncwtk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinqigufen.top/Article/details/gtecgnxpns.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnxiangtu.top/Article/details/gtxijyoaaf.html

[F03] 写入文件（覆盖）
来源：http://dali.yuanzhike.top/Article/details/gtblldrxmt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.guowangkeji.top/Article/details/gttzdxejxq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gtsfqtdttd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gttqjoicqv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gtdwmrqlyc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.iojbl.cn/Article/details/gtqfxhzoma.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.redwolf501.top/Article/details/gteluoptob.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.haohaochexian.top/Article/details/gtclywnnos.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gtfhzmsgfx.html

[F04] 追加写入文件
来源：http://dali.ppjwa.cn/Article/details/gtxbyueeyq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fzhhl.top/Article/details/gtnjtbwaqz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cheryme.top/Article/details/gtobpqwebg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gtqwaktrns.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cdnleiting.top/Article/details/gttluexqpl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ydzc1.top/Article/details/gtjzqvkfkd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ydzc1.top/Article/details/gtfmyojonm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtpuvqgj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhengqikj.top/Article/details/gttkghgaxr.html

[F05] 判断文件或目录是否存在
来源：http://dali.shuidangran.top/Article/details/gtgnoubuel.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhengqikj.top/Article/details/gtmtthqruu.html

PHP:  file_exists("a.txt");
来源：http://dali.birdmap.top/Article/details/gtgpncrwap.html

JS:   fs.existsSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtbsgfulox.html

TS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtduoywvxb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gthvlgcaht.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhengqikj.top/Article/details/gtunlcapjm.html

Ruby: File.exist?("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtsukgmlvp.html

C#:   File.Exists("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtxzoxsjqs.html

[F06] 删除文件
来源：http://dali.shuidangran.top/Article/details/gtmfoydcav.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtaadwrmew.html

PHP:  unlink("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtmdbxpkph.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtxjwceveb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtxqswvehp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtojchhmtv.html

Go:   os.Remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gtsflyamqd.html

Ruby: File.delete("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtnpnlhcqm.html

C#:   File.Delete("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtpytcwxmc.html

[F07] 创建目录（含多级）
来源：http://dali.gotoacloud.top/Article/details/gtivvdwefl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hfpthk.cn/Article/details/gtsyveqiql.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guowangkeji.top/Article/details/gtolgzxgre.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenzaomai.com/Article/details/gtlsclcckd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gtdvowzqyi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aibaodan.cn/Article/details/gtipqmkfbo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtyraqmp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gotoacloud.top/Article/details/gtytkmloxd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xinyue.icu/Article/details/gthkrbmspl.html

[F08] 遍历目录
来源：http://dali.havefunace.top/Article/details/gtpmrsfxkl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xinyue.icu/Article/details/gtqsggrqeb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pycfn.com/Article/details/gtkzenumya.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhloobwo.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtfzfzmijw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gtqezxqnnz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dianchejie.cn/Article/details/gtrmtijpom.html

Ruby: Dir.children("dir")
来源：http://dali.snrcjt.cn/Article/details/gtzpxrtrxw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fengsongda.top/Article/details/gtnevferwu.html

[F09] 获取文件大小
来源：http://dali.hongshengwenyu.top/Article/details/gtcjtltycg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcfqymca.html

PHP:  filesize("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtfhmqcgfc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ehwqpu.com/Article/details/gtaservfah.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yvedp.cn/Article/details/gtnflvhulp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gteuuokjjq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenjidiqi.icu/Article/details/gtwvwsnhnq.html

Ruby: File.size("a.txt")
来源：http://dali.birdmap.top/Article/details/gtvevqvaku.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.316326.xyz/Article/details/gtpbsuanxg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jlsjyb.cn/Article/details/gtjhyhsitn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtrvunisom.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtifwiepxq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtlmfhxzyg.html

TS:   path.extname("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtszhqstxg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.quarkkingdee.top/Article/details/gtinukljzu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtqmxumjpt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtkdfuvvkd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtidggmonh.html

[F11] 复制与移动文件
来源：http://dali.redwolf501.top/Article/details/gtokwrarew.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gthusrhpwc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daria6918.cn/Article/details/gthzokirlm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtyarzryqr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtcviriphn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hfpthk.cn/Article/details/gtqyqwcemw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tian-w.cn/Article/details/gtfgwfivvo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtiyuyhifr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ivvv.top/Article/details/gtqhcpqktb.html

[F12] CSV 读写
来源：http://dali.andypj.xyz/Article/details/gtlxfwoagf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yvedp.cn/Article/details/gtwfjrltcx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenjidiqi.icu/Article/details/gtaortcarn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.aizwys.cn/Article/details/gteaslkuky.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gtqyptioej.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuanzx.com/Article/details/gtzgazcueq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xziqi.cn/Article/details/gtgwkequqe.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.snrcjt.cn/Article/details/gtekdzahtb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.svipenyu.cn/Article/details/gtwretvfwb.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdfxzgwq.html

G. 面向对象
来源：http://dali.aizwys.cn/Article/details/gtolnvdngj.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtmrsuyyit.html

[G01] 定义类
来源：http://dali.jlsjyb.cn/Article/details/gturiiiusr.html

Py:   class User: pass
来源：http://dali.aibaodan.cn/Article/details/gtznjiojtm.html

PHP:  class User {}
来源：http://dali.yuanzhike.top/Article/details/gtnhfhkfcr.html

JS:   class User {}
来源：http://dali.hammf.cn/Article/details/gtxeeqsixc.html

TS:   class User { name: string = ""; }
来源：http://dali.tanke756.top/Article/details/gtulscpdth.html

Java: class User {}
来源：http://dali.wangdashe.top/Article/details/gtcxdlndjy.html

Go:   type User struct { Name string }
来源：http://dali.pycfn.com/Article/details/gtwuoeshps.html

Ruby: class User; end
来源：http://dali.gaohongyu789.top/Article/details/gtnrxtuzxp.html

C#:   class User {}
来源：http://dali.xziqi.cn/Article/details/gtgzyinoeu.html

[G02] 构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezetnxjt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.havefunace.top/Article/details/gtitiflhpr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ivvv.top/Article/details/gtahuliepn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtnvrnqaas.html

TS:   constructor(public name: string) {}
来源：http://dali.cqqwz.cn/Article/details/gteathafci.html

Java: User(String name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtdbvabtgl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tianlin.xyz/Article/details/gtcnkvrrym.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhengqikj.top/Article/details/gtzoygphxh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtyfdlhgnw.html

[G03] 实例属性
来源：http://dali.wangdashe.top/Article/details/gtcjemfjil.html

Py:   self.name = "x"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgbgiofgu.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gthfnbfycv.html

JS:   this.name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtmbsuhimv.html

TS:   name: string = "x";
来源：http://dali.gotoacloud.top/Article/details/gtxgzyqcvz.html

Java: private String name;
来源：http://dali.aizwys.cn/Article/details/gtfbsrsqgz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shangyingyoupin.top/Article/details/gtcxlbsqrx.html

Ruby: @name = "x"
来源：http://dali.yj20258888.top/Article/details/gtyrvagttx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hfpthk.cn/Article/details/gtephcibqb.html

[G04] 定义方法
来源：http://dali.hongshengwenyu.top/Article/details/gtmzaxzvmu.html

Py:   def greet(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gtbqdmeahc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gtaolnecud.html

JS:   greet() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtcbakeuvp.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtwrdlbvkn.html

Java: String greet() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtozuryrym.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gtmgbtnzjs.html

Ruby: def greet; @name; end
来源：http://dali.316326.xyz/Article/details/gtzewuyhvs.html

C#:   public string Greet() => Name;
来源：http://dali.yuanzhike.top/Article/details/gttkqrjzwr.html

[G05] 继承
来源：http://dali.jinghuilouyu.cn/Article/details/gtpzeqpllf.html

Py:   class Admin(User): pass
来源：http://dali.gotoacloud.top/Article/details/gtgpdogswj.html

PHP:  class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtrimfynek.html

JS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtoqsudyll.html

TS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtjnfgzpei.html

Java: class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtjimhvrad.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gthyxnpnzt.html

Ruby: class Admin < User; end
来源：http://dali.cashguo.top/Article/details/gtlbipzweu.html

C#:   class Admin : User {}
来源：http://dali.jlsjyb.cn/Article/details/gtsesnhamh.html

[G06] 重写方法
来源：http://dali.zhengqikj.top/Article/details/gtcusyrzna.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258888.top/Article/details/gtmqsrxgik.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtlmnkhysv.html

JS:   greet() { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtmqoaneyw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtfmvjpwpq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtirmkvghw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnqzz.top/Article/details/gtebgsvzmo.html

Ruby: def greet; "admin"; end
来源：http://dali.yangfankeji.com/Article/details/gtgwzicxvo.html

C#:   public override string Greet() => "admin";
来源：http://dali.xinyue.icu/Article/details/gtoknekzoa.html

[G07] 调用父类方法
来源：http://dali.cdnleiting.top/Article/details/gtighckyso.html

Py:   super().greet()
来源：http://dali.dianchejie.cn/Article/details/gtfzsgapoz.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxxvyddz.html

JS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gtkvtdmliw.html

TS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gtjbuhsxhu.html

Java: super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcrdfxffr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.c1oappe.top/Article/details/gtquqnjoiv.html

Ruby: super
来源：http://dali.sufxvd.cn/Article/details/gtdjkkkrer.html

C#:   base.Greet();
来源：http://dali.hywenlv.cn/Article/details/gtajgwubud.html

[G08] 静态方法与属性
来源：http://dali.ydzc1.top/Article/details/gtcxmedasj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.smart0.xyz/Article/details/gtwzwpihky.html

PHP:  public static function f() {}
来源：http://dali.mhx1999.top/Article/details/gthmgawqgg.html

JS:   static f() {}
来源：http://dali.cashguo.top/Article/details/gtpcvubiop.html

TS:   static f(): void {}
来源：http://dali.cdnleiting.top/Article/details/gtuskqaepq.html

Java: static void f() {}
来源：http://dali.xuanzx.com/Article/details/gtivikwvzc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinqigfzy.top/Article/details/gtyazcrzgr.html

Ruby: def self.f; end
来源：http://dali.yj20258.top/Article/details/gtazfkzfoa.html

C#:   public static void F() {}
来源：http://dali.andypj.xyz/Article/details/gtycpzsjje.html

[G09] 接口 / 抽象类
来源：http://dali.guowangkeji.top/Article/details/gtovqffpei.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.birdmap.top/Article/details/gtfagdnmpk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guannengcc.top/Article/details/gtgtpnwsca.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yangfankeji.com/Article/details/gtumtqufmj.html

TS:   interface Shape { area(): number; }
来源：http://dali.yangfankeji.com/Article/details/gtkdqrwukh.html

Java: interface Shape { double area(); }
来源：http://dali.cdnleiting.top/Article/details/gtcijhlkme.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ivvv.top/Article/details/gtudgfluvm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258.top/Article/details/gtrpyrbzoc.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangdashe.top/Article/details/gtusriqwfr.html

[G10] 访问控制
来源：http://dali.chenlongwang.top/Article/details/gttsskxmwv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhlhgmaw.html

PHP:  public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gtvueidfcd.html

JS:   #private 字段；其余公开
来源：http://dali.cqqwz.cn/Article/details/gtbprqxmju.html

TS:   public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtswdxnrro.html

Java: public / protected / private / 默认包级
来源：http://dali.iojbl.cn/Article/details/gtwnjkmolw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yonumen.top/Article/details/gtcculyzcp.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gtmgwjunia.html

C#:   public / protected / private / internal
来源：http://dali.xuanzx.com/Article/details/gtpchzfoqb.html

[G11] getter / setter
来源：http://dali.xziqi.cn/Article/details/gtxtbjzjeq.html

Py:   @property 与 @x.setter
来源：http://dali.svipenyu.cn/Article/details/gtfmcfgqyj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gtcgukcxhc.html

JS:   get name() { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gtymyvmcvg.html

TS:   get name(): string { return this._name; }
来源：http://dali.snrcjt.cn/Article/details/gtrpzoffmg.html

Java: public String getName() { return name; }
来源：http://dali.yonumen.top/Article/details/gtxebzfhml.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtklrgbjkm.html

Ruby: attr_accessor :name
来源：http://dali.shuidangran.top/Article/details/gtbketcfcs.html

C#:   public string Name { get; set; }
来源：http://dali.yanxiufei.cn/Article/details/gtjtnhpjco.html

[G12] 对象转字符串
来源：http://dali.tianlin.xyz/Article/details/gtwpwapngr.html

Py:   def __str__(self): return self.name
来源：http://dali.daria6918.cn/Article/details/gtjqouquzu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gtbdfymcbk.html

JS:   toString() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtqqwnszgz.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtuymtgnqc.html

Java: @Override public String toString() { return name; }
来源：http://dali.ivvv.top/Article/details/gtnubipeoo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gthvukmcfk.html

Ruby: def to_s; @name; end
来源：http://dali.hysaishi.cn/Article/details/gtjhjterrx.html

C#:   public override string ToString() => Name;
来源：http://dali.smart0.xyz/Article/details/gtmpqyssqq.html

[G13] 判断对象类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaloejugo.html

Py:   isinstance(u, User)
来源：http://dali.yuanzhike.top/Article/details/gthstgamie.html

PHP:  $u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtinfwtqow.html

JS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtghmrdeqw.html

TS:   u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gtjwqdcgxw.html

Java: u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtkbjyhtmf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.fengsongda.top/Article/details/gtepeknwvq.html

Ruby: u.is_a?(User)
来源：http://dali.ydzc1.top/Article/details/gtsvwvkzio.html

C#:   u is User
来源：http://dali.andypj.xyz/Article/details/gtkajlaqbj.html

[G14] 数据类 / record
来源：http://dali.ydzc1.top/Article/details/gtocdffmsm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258888.top/Article/details/gttkkrqrei.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ydzc1.top/Article/details/gtbavxnney.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.andypj.xyz/Article/details/gtvlgaface.html

TS:   type User = { name: string; age: number };
来源：http://dali.sxryk.cn/Article/details/gtytohdmas.html

Java: record User(String name, int age) {}
来源：http://dali.fengsongda.top/Article/details/gtqtkxqrqo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.iojbl.cn/Article/details/gtqukxhdur.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hongshengwenyu.top/Article/details/gtqzwygjhb.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxinkj.top/Article/details/gtmfmibwsi.html

[G15] 枚举
来源：http://dali.hywenlv.cn/Article/details/gtpmwgjdpi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guannengcc.top/Article/details/gtltpppjeu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tian-w.cn/Article/details/gtuoqhnxkz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hywenlv.cn/Article/details/gtxhuqoxis.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.bjfxy.top/Article/details/gtgpbvyoia.html

Java: enum Color { RED, GREEN }
来源：http://dali.sufxvd.cn/Article/details/gtjcxdwljo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfanbtaq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinghuilouyu.cn/Article/details/gtfiizjppo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gtljlvesbj.html

[G16] 对象转数组 / 字典
来源：http://dali.wangshuangyany.cn/Article/details/gteyqbcrrq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fengsongda.top/Article/details/gtoefevgbg.html

PHP:  get_object_vars($obj);
来源：http://dali.yanxiufei.cn/Article/details/gtqlxchqaj.html

JS:   Object.entries(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtpwqxxqwl.html

TS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gtllojuqgi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.guannengcc.top/Article/details/gtqtwuhavr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.dashuyun.cn/Article/details/gtqsoggnbi.html

Ruby: obj.instance_variables
来源：http://dali.nwbrower.top/Article/details/gtgakmcbtv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yvedp.cn/Article/details/gtwqhynjil.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gthgrksafu.html

H. 异常与错误处理
来源：http://dali.pengpengdd.cyou/Article/details/gtgeeyjlyl.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtbocmoror.html

[H01] try / catch 基础
来源：http://dali.hfpthk.cn/Article/details/gtapikazzd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj20258888.top/Article/details/gtsuuiwwnm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.aizwys.cn/Article/details/gtpnkcctee.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gtgasfkqbt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gtwghjaqth.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yonumen.top/Article/details/gtihqjsvhb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gzhubu.top/Article/details/gtoetshjai.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yongpay.top/Article/details/gtcnkjicug.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shanyushiyangtech.top/Article/details/gteefwslhi.html

[H02] finally / ensure 收尾
来源：http://dali.jinghuilouyu.cn/Article/details/gteeseiyxv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gzhubu.top/Article/details/gtyssuijch.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtildtqmlx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmerpnfz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtfaictazz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtafogrebp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cheryme.top/Article/details/gtbgohjabs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tianlin.xyz/Article/details/gtrqbfemii.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtbrlmgsbu.html

[H03] 主动抛出异常
来源：http://dali.gotoacloud.top/Article/details/gtvvykqpwi.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258888.top/Article/details/gtvyaqzngm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtxuczcala.html

JS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtjxcxcqop.html

TS:   throw new Error("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtfyhdaoiq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtahefcait.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnxiangtu.top/Article/details/gtojwzmtdi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hongshengwenyu.top/Article/details/gtkrsqtipi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtcxnamecl.html

[H04] 自定义异常类型
来源：http://dali.yonumen.top/Article/details/gtbmjlzlak.html

Py:   class MyError(Exception): pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdpatvjh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gtxvupitkx.html

JS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gtlehuxshz.html

TS:   class MyError extends Error {}
来源：http://dali.wangshuangyany.cn/Article/details/gtzyajynyq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gthodenaeq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xylfe.cn/Article/details/gtvqujcgwd.html


<!-- 参考信息 -->