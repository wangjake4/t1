代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.gogol.net.cn/Article/details/gtewialxha.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dianchejie.cn/Article/details/gtkxxzecfw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.meibo888.top/Article/details/gtpxrmkfma.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrakhbsea.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tian-w.cn/Article/details/gtxuixaunw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nanxinkj.top/Article/details/gtfvgcwuql.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvgcnzlwk.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtykqwtvpo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gtulqhboqg.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtjrdyeodk.html

F. 文件与目录
来源：http://dali.hysaishi.cn/Article/details/gtwymbbmnl.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtpsrqfkvb.html

[F01] 读取整个文件
来源：http://dali.yj20258.top/Article/details/gtouyieryb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gzhubu.top/Article/details/gtrbvuwfhd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtomlwaknz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zdqjudy.top/Article/details/gtaqynrmoa.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zycfv.cn/Article/details/gtrfjshsqp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtpfziogsh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cdnleiting.top/Article/details/gtrgcysnsa.html

Ruby: File.read("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtucrvpboo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtvnjvsqtu.html

[F02] 逐行读取文件
来源：http://dali.hammf.cn/Article/details/gtejsmqbij.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxinkj.top/Article/details/gtuvcuedqb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.bjfxy.top/Article/details/gttgjkfaso.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.smart0.xyz/Article/details/gtkslfuyny.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigfzy.top/Article/details/gtakxsrwra.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gtmbecrans.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ybcxt.top/Article/details/gtzctbshdg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nanxuanxn.top/Article/details/gtbhdiuxaf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.316326.xyz/Article/details/gtnekxzhpj.html

[F03] 写入文件（覆盖）
来源：http://dali.zdqjudy.top/Article/details/gtffpjdnmk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xuetiantiany.cn/Article/details/gtuuwzmvbc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.316326.xyz/Article/details/gtfmaxvfuc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdnflaxec.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ivvv.top/Article/details/gtctfhjvxq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gtqenilrps.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenzaomai.com/Article/details/gthnahyvzn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jyoumei.cn/Article/details/gtzthybtrk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gthczedawc.html

[F04] 追加写入文件
来源：http://dali.yj202588.top/Article/details/gtugumrrwq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtcnykgdmt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nwbrower.top/Article/details/gtdomnckjz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yvedp.cn/Article/details/gtdklicprv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gtjlkcqzux.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinqigfzy.top/Article/details/gtucssstfa.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.bjfxy.top/Article/details/gtxsdghhtw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xylfe.cn/Article/details/gtuglejful.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.smart0.xyz/Article/details/gteyqxzwik.html

[F05] 判断文件或目录是否存在
来源：http://dali.wangshuangyany.cn/Article/details/gtjdhmkfaj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhixingplan.top/Article/details/gtavuibuex.html

PHP:  file_exists("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtxggmarfi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtcrexyatj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtwewmakkm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtrbvaitsd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhengqikj.top/Article/details/gtivsneqvs.html

Ruby: File.exist?("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtousjgtsq.html

C#:   File.Exists("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtpenaravs.html

[F06] 删除文件
来源：http://dali.zhongyouzk.top/Article/details/gtucovqsog.html

Py:   os.remove("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtgrdpoayi.html

PHP:  unlink("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtavovdunb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtjprcjqxi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtunpobuco.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtehlsocyx.html

Go:   os.Remove("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtropklbhy.html

Ruby: File.delete("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtbnvdppqg.html

C#:   File.Delete("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtszsaenkr.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gtbuwdhycy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtalojddaf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.c1oappe.top/Article/details/gtpdjsvbvf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhengqikj.top/Article/details/gtarnljlyh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ppjwa.cn/Article/details/gtwgqjglkq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.svipenyu.cn/Article/details/gtgocydrep.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tanke756.top/Article/details/gtakorkilf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yongpay.top/Article/details/gtcbxobjbq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.havefunace.top/Article/details/gtmeehxxht.html

[F08] 遍历目录
来源：http://dali.zhoulong.xyz/Article/details/gtrgdlsazg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xylfe.cn/Article/details/gtpfgvzhiu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.aibaodan.cn/Article/details/gtkmrysuyq.html

JS:   fs.readdirSync("dir")
来源：http://dali.ehwqpu.com/Article/details/gtlrtqrmli.html

TS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gtudtqrwku.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gtwwawhnel.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xuanzx.com/Article/details/gtwyhnxxns.html

Ruby: Dir.children("dir")
来源：http://dali.yj202588.top/Article/details/gtkjlieqhg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xuanzx.com/Article/details/gtqkittenq.html

[F09] 获取文件大小
来源：http://dali.ybcxt.top/Article/details/gtvptbbrlp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtyvhfgaql.html

PHP:  filesize("a.txt");
来源：http://dali.redwolf501.top/Article/details/gttzizhiae.html

JS:   fs.statSync("a.txt").size
来源：http://dali.svipenyu.cn/Article/details/gtlriicfzo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.iojbl.cn/Article/details/gtbnepmbuf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtawdnoggx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sufxvd.cn/Article/details/gtcaaevxpu.html

Ruby: File.size("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtwuzbckoi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuanzhike.top/Article/details/gtjuocmztj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cucudq.cn/Article/details/gtgasagczd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtpuzowhgz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtihspoiou.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtvwkilygx.html

TS:   path.extname("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtzxqwngaz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gzhubu.top/Article/details/gthwcnipeg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtbauhmxgg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtigsopekr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtesrbbgrr.html

[F11] 复制与移动文件
来源：http://dali.hongshengwenyu.top/Article/details/gtpytnpkwy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtemcyzdgo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hysaishi.cn/Article/details/gtmvqojtuq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gtavwfcdku.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtvsccewgi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dianchejie.cn/Article/details/gtgphplfqa.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzlrxtuiz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtesozoubc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shuidangran.top/Article/details/gtfvraxokr.html

[F12] CSV 读写
来源：http://dali.jianghu66.top/Article/details/gtrbqlaclv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shzxlz.cn/Article/details/gtzylxjegt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yuxming.cn/Article/details/gthxgsquoa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hammf.cn/Article/details/gtalfofwvm.html

TS:   // 同上
来源：http://dali.zycfv.cn/Article/details/gtiwizjgzy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.316326.xyz/Article/details/gtobhjfbjh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zycfv.cn/Article/details/gtmsvzfayn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yongpay.top/Article/details/gttyneyecf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gotoacloud.top/Article/details/gtrjlkmozl.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtdynpypgx.html

G. 面向对象
来源：http://dali.hnqzz.top/Article/details/gtllqfgpxk.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdnzvwfgm.html

[G01] 定义类
来源：http://dali.hysaishi.cn/Article/details/gtrxotpvzj.html

Py:   class User: pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrflkjsnu.html

PHP:  class User {}
来源：http://dali.dashuyun.cn/Article/details/gtflyykrjj.html

JS:   class User {}
来源：http://dali.bjfxy.top/Article/details/gtkyhraxgq.html

TS:   class User { name: string = ""; }
来源：http://dali.jyoumei.cn/Article/details/gtolbunrki.html

Java: class User {}
来源：http://dali.mhx1999.top/Article/details/gtamqphzts.html

Go:   type User struct { Name string }
来源：http://dali.zhixingplan.top/Article/details/gtgqxcxgam.html

Ruby: class User; end
来源：http://dali.yvedp.cn/Article/details/gtfwykxuki.html

C#:   class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtrakfwhay.html

[G02] 构造函数
来源：http://dali.shuidangran.top/Article/details/gtzotrbaxw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258888.top/Article/details/gtkzbogedb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.kuanghao11.cn/Article/details/gtxwqjvzph.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gtwnqpgdod.html

TS:   constructor(public name: string) {}
来源：http://dali.nanxuanxn.top/Article/details/gtscrajnhq.html

Java: User(String name) { this.name = name; }
来源：http://dali.fzhhl.top/Article/details/gtsnyqqbqa.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guowangkeji.top/Article/details/gtpgjoixnl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gtativnbpe.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ydzc1.top/Article/details/gtijrnwphi.html

[G03] 实例属性
来源：http://dali.daria6918.cn/Article/details/gtinlttrof.html

Py:   self.name = "x"
来源：http://dali.birdmap.top/Article/details/gtywhdnorj.html

PHP:  public string $name = "x";
来源：http://dali.birdmap.top/Article/details/gtkheuovxm.html

JS:   this.name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtybwrwtpb.html

TS:   name: string = "x";
来源：http://dali.meibo888.top/Article/details/gtqyrfjtzo.html

Java: private String name;
来源：http://dali.yj20258.top/Article/details/gtnebnfdsw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jiagoushi.top/Article/details/gtsvtzotjk.html

Ruby: @name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gttdfwjuzj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hammf.cn/Article/details/gtyfraitsc.html

[G04] 定义方法
来源：http://dali.shangyingyoupin.top/Article/details/gtrnhcjfuo.html

Py:   def greet(self): return self.name
来源：http://dali.ydzc1.top/Article/details/gtavsdqdof.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gtfgxmcsyr.html

JS:   greet() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtomwadrtf.html

TS:   greet(): string { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtotbkocwj.html

Java: String greet() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtvdrfxupn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gtucmeljtf.html

Ruby: def greet; @name; end
来源：http://dali.zhongyouzk.top/Article/details/gteepmlvqz.html

C#:   public string Greet() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gtxnlytxjw.html

[G05] 继承
来源：http://dali.jianghu66.top/Article/details/gtfdripqcr.html

Py:   class Admin(User): pass
来源：http://dali.hfpthk.cn/Article/details/gtonhndsba.html

PHP:  class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtzzijwvuz.html

JS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtqlnpgknr.html

TS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gttpczbkwx.html

Java: class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtzpahhhuu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.9152youxi.cn/Article/details/gthyfdmtaq.html

Ruby: class Admin < User; end
来源：http://dali.aibaodan.cn/Article/details/gtdnchgmgt.html

C#:   class Admin : User {}
来源：http://dali.tianlin.xyz/Article/details/gtwoozdbfp.html

[G06] 重写方法
来源：http://dali.andypj.xyz/Article/details/gtestupulz.html

Py:   def greet(self): return "admin"
来源：http://dali.yangfankeji.com/Article/details/gtqdzmaysj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtnnijkeoz.html

JS:   greet() { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtgdwvxwfo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtuujxbcgy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtoryloqdn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhongyouzk.top/Article/details/gtnirhwxjv.html

Ruby: def greet; "admin"; end
来源：http://dali.chenzaomai.com/Article/details/gttdwdoogs.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhixingplan.top/Article/details/gtwoibcniv.html

[G07] 调用父类方法
来源：http://dali.tian-w.cn/Article/details/gtphgddiqr.html

Py:   super().greet()
来源：http://dali.zdqjudy.top/Article/details/gtvltymbah.html

PHP:  parent::greet();
来源：http://dali.chenlongwang.top/Article/details/gtjbfigxam.html

JS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gtzyrwxbxo.html

TS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtvrpwdrub.html

Java: super.greet();
来源：http://dali.9152youxi.cn/Article/details/gtzwihlghd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtejxyxxxa.html

Ruby: super
来源：http://dali.haohaochexian.top/Article/details/gtihakfpya.html

C#:   base.Greet();
来源：http://dali.zhongyouzk.top/Article/details/gtrndnbvki.html

[G08] 静态方法与属性
来源：http://dali.feifeiyinyue.top/Article/details/gtcrpynnin.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangdashe.top/Article/details/gtfyxplhkb.html

PHP:  public static function f() {}
来源：http://dali.yvedp.cn/Article/details/gtpbrrrlgv.html

JS:   static f() {}
来源：http://dali.hnqzz.top/Article/details/gtmbmtdksu.html

TS:   static f(): void {}
来源：http://dali.svipenyu.cn/Article/details/gtccibfdcx.html

Java: static void f() {}
来源：http://dali.nwbrower.top/Article/details/gtevxmqnns.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenlongwang.top/Article/details/gtjdjvhpcj.html

Ruby: def self.f; end
来源：http://dali.xylfe.cn/Article/details/gtvtmjhmhw.html

C#:   public static void F() {}
来源：http://dali.hysaishi.cn/Article/details/gtvwcjgpid.html

[G09] 接口 / 抽象类
来源：http://dali.havefunace.top/Article/details/gtlgveqqgq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hysaishi.cn/Article/details/gtdfwzwrcd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yanxiufei.cn/Article/details/gtknssemam.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hywenlv.cn/Article/details/gtbssavoag.html

TS:   interface Shape { area(): number; }
来源：http://dali.daxiang520.top/Article/details/gtwgalvrnt.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258.top/Article/details/gtfkwdsxyt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daria6918.cn/Article/details/gtgjyonlbq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cashguo.top/Article/details/gtnjrpaiwk.html

C#:   interface IShape { double Area(); }
来源：http://dali.tanke756.top/Article/details/gtzeibragk.html

[G10] 访问控制
来源：http://dali.zhiwuduotai.top/Article/details/gtxvekwkdp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shangyingyoupin.top/Article/details/gtvxhwkgia.html

PHP:  public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gtixnvuehm.html

JS:   #private 字段；其余公开
来源：http://dali.sweek.top/Article/details/gtzmngeboz.html

TS:   public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtofehddnb.html

Java: public / protected / private / 默认包级
来源：http://dali.pengpengdd.cyou/Article/details/gtanuvupnu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gtlzuxojgg.html

Ruby: public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtnkotfbki.html

C#:   public / protected / private / internal
来源：http://dali.shuidangran.top/Article/details/gtzbtzeagd.html

[G11] getter / setter
来源：http://dali.daxiang520.top/Article/details/gtntyizvdu.html

Py:   @property 与 @x.setter
来源：http://dali.meibo888.top/Article/details/gtqwrctoaw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtecycjtub.html

JS:   get name() { return this._name; }
来源：http://dali.smart0.xyz/Article/details/gtztslkvqh.html

TS:   get name(): string { return this._name; }
来源：http://dali.birdmap.top/Article/details/gtvnojekhb.html

Java: public String getName() { return name; }
来源：http://dali.ybcxt.top/Article/details/gtfzkeioog.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gthcfjzmke.html

Ruby: attr_accessor :name
来源：http://dali.quarkkingdee.top/Article/details/gtzfodeybx.html

C#:   public string Name { get; set; }
来源：http://dali.sxryk.cn/Article/details/gtxkcxndeu.html

[G12] 对象转字符串
来源：http://dali.zhengqikj.top/Article/details/gtocaatbzl.html

Py:   def __str__(self): return self.name
来源：http://dali.316326.xyz/Article/details/gtrhnlwuuh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtwvuvrnmi.html

JS:   toString() { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gtzxrvmfni.html

TS:   toString(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtrrsdfsjx.html

Java: @Override public String toString() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtrfvfdcmp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtdytgpjgr.html

Ruby: def to_s; @name; end
来源：http://dali.hysaishi.cn/Article/details/gtimfrpuge.html

C#:   public override string ToString() => Name;
来源：http://dali.smart0.xyz/Article/details/gtzszwvyia.html

[G13] 判断对象类型
来源：http://dali.wangdashe.top/Article/details/gtrxfiwpha.html

Py:   isinstance(u, User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgtdubrxh.html

PHP:  $u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtnxupuqjx.html

JS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtjixhpcil.html

TS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtztlzmttv.html

Java: u instanceof User
来源：http://dali.ivvv.top/Article/details/gtappsjsdz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqthtxdzk.html

Ruby: u.is_a?(User)
来源：http://dali.yongpay.top/Article/details/gtqwncymij.html

C#:   u is User
来源：http://dali.meibo888.top/Article/details/gtpoflouct.html

[G14] 数据类 / record
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjoydcqel.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ehwqpu.com/Article/details/gtxerajvqb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sufxvd.cn/Article/details/gtfdgrzcwv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jlsjyb.cn/Article/details/gtdusnbvwc.html

TS:   type User = { name: string; age: number };
来源：http://dali.andypj.xyz/Article/details/gtgwmhoaeo.html

Java: record User(String name, int age) {}
来源：http://dali.daria6918.cn/Article/details/gtpmunzjyz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj20258.top/Article/details/gttqfkupuw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yangfankeji.com/Article/details/gtrnejqoux.html

C#:   record User(string Name, int Age);
来源：http://dali.hammf.cn/Article/details/gtmqvkqmdi.html

[G15] 枚举
来源：http://dali.redwolf501.top/Article/details/gtttmylali.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.c1oappe.top/Article/details/gtjvkqugsx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhengqikj.top/Article/details/gtlqgnlxie.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhixingplan.top/Article/details/gtfsmrwofk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuanzhike.top/Article/details/gtscfmurbm.html

Java: enum Color { RED, GREEN }
来源：http://dali.guannengcc.top/Article/details/gtqcitxnzj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ivvv.top/Article/details/gtzqtbilys.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jianghu66.top/Article/details/gtpgvgvkjc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtmaljzwck.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258888.top/Article/details/gtzimrjhya.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shanyushiyangtech.top/Article/details/gtumcbbluy.html

PHP:  get_object_vars($obj);
来源：http://dali.zhengqikj.top/Article/details/gtbxtssqjn.html

JS:   Object.entries(obj)
来源：http://dali.tian-w.cn/Article/details/gtelxygecw.html

TS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdibzzgbi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gaohongyu789.top/Article/details/gtctkpbnpi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ppjwa.cn/Article/details/gtxilzlbzi.html

Ruby: obj.instance_variables
来源：http://dali.redwolf501.top/Article/details/gtgdntyvdv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gtnbmkczyc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gthbdjzobz.html

H. 异常与错误处理
来源：http://dali.c1oappe.top/Article/details/gtzzyyqent.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjibhzunw.html

[H01] try / catch 基础
来源：http://dali.nanxinkj.top/Article/details/gtoblcaxyx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fzhhl.top/Article/details/gtzabqqqvy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtndjnjgdk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtnylznrsu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhongyouzk.top/Article/details/gtuqwyccwz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nwbrower.top/Article/details/gtankhtvuu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.feifeiyinyue.top/Article/details/gtkfppbczn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.svipenyu.cn/Article/details/gtapcourup.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzswvoxdq.html

[H02] finally / ensure 收尾
来源：http://dali.hnxiangtu.top/Article/details/gtllnksyob.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.guannengcc.top/Article/details/gteibuyxul.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gturybxehb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtthddjftg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtndhzassq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gthbasfrtp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hywenlv.cn/Article/details/gtolhtonfb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.havefunace.top/Article/details/gtdiapblkl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtfpvscpqj.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtllgufnez.html

Py:   raise ValueError("错误信息")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvurgtrok.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtvflffqdp.html

JS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtyprwruzc.html

TS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtfruuioci.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtkctgeeie.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gaohongyu789.top/Article/details/gtnmwijaqi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ivvv.top/Article/details/gtbhmflesh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtrrlliisl.html

[H04] 自定义异常类型
来源：http://dali.zdqjudy.top/Article/details/gtfunszlwq.html

Py:   class MyError(Exception): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvejkpwyc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gtwhtummbb.html


<!-- 参考信息 -->