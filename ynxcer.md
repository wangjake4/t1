代发 wailian999

Go:   if s == "" {}
来源：http://dali.yueranfly.top/Article/details/gtpycygupp.html

Ruby: if s.empty?
来源：http://dali.feifeiyinyue.top/Article/details/gtfwhbydrd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jlsjyb.cn/Article/details/gtepynwyce.html

[E21] 超长截断加省略号
来源：http://dali.ehwqpu.com/Article/details/gtbibnwfec.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinqigufen.top/Article/details/gtmrnymzuf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.pycfn.com/Article/details/gttqajwopt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtzeofdoue.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtndaejedb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtebzgvgtu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.redwolf501.top/Article/details/gtryluimxc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gtbsxzkmvd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtszgcgpbg.html

[E22] 字节长度与字符长度
来源：http://dali.pycfn.com/Article/details/gtlsdjxouh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbrwvfai.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gtyfzbyspo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhengqikj.top/Article/details/gtqhnzynup.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgfzy.top/Article/details/gtyegmphyk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hammf.cn/Article/details/gtcgxmqvtr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenjidiqi.icu/Article/details/gtaalszkpf.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj20258.top/Article/details/gtryrenvaa.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gtkvitbhqy.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtfveewvdw.html

F. 文件与目录
来源：http://dali.pycfn.com/Article/details/gtnvfkieyr.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtbhnajaiq.html

[F01] 读取整个文件
来源：http://dali.gaohongyu789.top/Article/details/gtldfakzgo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sysykeji.top/Article/details/gtnwvjdwfy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gttczjohvp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.haohaochexian.top/Article/details/gtjupepodq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yueranfly.top/Article/details/gtqnkqekqg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtvoizbort.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yvedp.cn/Article/details/gtoxmpsxwq.html

Ruby: File.read("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzbkdmkhf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.birdmap.top/Article/details/gtpjrzcgtq.html

[F02] 逐行读取文件
来源：http://dali.jianghu66.top/Article/details/gttdrwevzq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gaohongyu789.top/Article/details/gtlhceliqh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinqigfzy.top/Article/details/gtjtdqxdpr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.kuanghao11.cn/Article/details/gtpvhogrmy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cheryme.top/Article/details/gthkuhvmgv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gtqkhyrqfj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sweek.top/Article/details/gtayxhwpzi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jqgufenzy.top/Article/details/gtvypjgksk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtuezbbhoj.html

[F03] 写入文件（覆盖）
来源：http://dali.sysykeji.top/Article/details/gtabqdobyj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yuxming.cn/Article/details/gtnquorykj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.quarkkingdee.top/Article/details/gtcakudndu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gtympbbrbc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daxiang520.top/Article/details/gtfdwdldrb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigufen.top/Article/details/gtkedrcijp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hnxiangtu.top/Article/details/gtosrplqwa.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigfzy.top/Article/details/gtfmtqxgoq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gtrrbbqscb.html

[F04] 追加写入文件
来源：http://dali.gaohongyu789.top/Article/details/gtuewnhtdh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.bjfxy.top/Article/details/gtzsaicukg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yvedp.cn/Article/details/gtoematytf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.mhx1999.top/Article/details/gtdvlqcxku.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gtbaavxayn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.aibaodan.cn/Article/details/gtlqytfype.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtjgfhsjjf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hammf.cn/Article/details/gtuuadrglq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ivvv.top/Article/details/gtfdifdmhr.html

[F05] 判断文件或目录是否存在
来源：http://dali.meibo888.top/Article/details/gtiiilskoh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fzhhl.top/Article/details/gtilqcxyrs.html

PHP:  file_exists("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtrvxcfmay.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtemfoolzj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtbaysiwpr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gtdsjmnerz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.meibo888.top/Article/details/gtuqtfhgwp.html

Ruby: File.exist?("a.txt")
来源：http://dali.yonumen.top/Article/details/gtasecvvsx.html

C#:   File.Exists("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtrofwgruq.html

[F06] 删除文件
来源：http://dali.guannengcc.top/Article/details/gtihmazfwn.html

Py:   os.remove("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtsoxqmtjo.html

PHP:  unlink("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtnlbknrbi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtbsxvzxig.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtvpwbjvfc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gthecmztah.html

Go:   os.Remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtdpdatqhf.html

Ruby: File.delete("a.txt")
来源：http://dali.316326.xyz/Article/details/gthxrcnuwh.html

C#:   File.Delete("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpjsesdv.html

[F07] 创建目录（含多级）
来源：http://dali.cucudq.cn/Article/details/gtgkemzliv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nanxinkj.top/Article/details/gtqwpcyzyd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgdnzkmpg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258.top/Article/details/gtnoynnlhg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gtyzqoptwr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gaohongyu789.top/Article/details/gtohlvanpv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenzaomai.com/Article/details/gthdnemgau.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jianghu66.top/Article/details/gtgxzyprdm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yuxming.cn/Article/details/gtuxgxelgy.html

[F08] 遍历目录
来源：http://dali.xinyue.icu/Article/details/gteymqsolt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.9152youxi.cn/Article/details/gtievfmurf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ppjwa.cn/Article/details/gtohwgqhmd.html

JS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrgwlzdjk.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtljkyygqb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gtqphgryre.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfryactao.html

Ruby: Dir.children("dir")
来源：http://dali.chenlongwang.top/Article/details/gtxuumoigb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hnqzz.top/Article/details/gthezelxab.html

[F09] 获取文件大小
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqaofbthl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtsicfcyql.html

PHP:  filesize("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtlhhxocjy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gtdvptjbmb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aibaodan.cn/Article/details/gtexsewloo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtdzsorbac.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gzhubu.top/Article/details/gtvgwdhxip.html

Ruby: File.size("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtzozgjrjo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.birdmap.top/Article/details/gthmvgjnpi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkzzgrcp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtakqzmtxb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xziqi.cn/Article/details/gtdqclnnge.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtfkidgpyc.html

TS:   path.extname("a.txt")
来源：http://dali.tanke756.top/Article/details/gtfjozenud.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigfzy.top/Article/details/gtxjmafndk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtvtdwgily.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gttaxwizpl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtfonohpbd.html

[F11] 复制与移动文件
来源：http://dali.svipenyu.cn/Article/details/gtoxdtwprm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtmpdeewbd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zycfv.cn/Article/details/gtkdcbktjb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtzwnnysai.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxqktxhb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cucudq.cn/Article/details/gtuuvjxswu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.redwolf501.top/Article/details/gtbsicqeou.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtmkiztbcy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.smart0.xyz/Article/details/gtalwmqeau.html

[F12] CSV 读写
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhomucky.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuetiantiany.cn/Article/details/gtemgznags.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.9152youxi.cn/Article/details/gtubhfzhur.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhiwuduotai.top/Article/details/gtcvsilthu.html

TS:   // 同上
来源：http://dali.cashguo.top/Article/details/gtlfynnjpa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sufxvd.cn/Article/details/gtuyxnrowv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxgxzcjw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfajgcmf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.redwolf501.top/Article/details/gtihfvevny.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtnxxkaktk.html

G. 面向对象
来源：http://dali.jqgufenzy.top/Article/details/gtfpgakdrg.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtrtolmdrx.html

[G01] 定义类
来源：http://dali.yj20258888.top/Article/details/gtlaqahwry.html

Py:   class User: pass
来源：http://dali.zhengqikj.top/Article/details/gtormmumft.html

PHP:  class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtthhuzscb.html

JS:   class User {}
来源：http://dali.havefunace.top/Article/details/gtetmpozgs.html

TS:   class User { name: string = ""; }
来源：http://dali.hongshengwenyu.top/Article/details/gthlgmvswa.html

Java: class User {}
来源：http://dali.yj20258.top/Article/details/gtucahjwee.html

Go:   type User struct { Name string }
来源：http://dali.cqqwz.cn/Article/details/gthjfwfqmx.html

Ruby: class User; end
来源：http://dali.redwolf501.top/Article/details/gtqrawzkxc.html

C#:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtrncyethi.html

[G02] 构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gtpkdbdjkt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jiagoushi.top/Article/details/gtixzpivsx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yvedp.cn/Article/details/gtmwsxpura.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtigvdrizi.html

TS:   constructor(public name: string) {}
来源：http://dali.yanxiufei.cn/Article/details/gtbkljcbwp.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gtqygibjiq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nwbrower.top/Article/details/gtgjkapheh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hongshengwenyu.top/Article/details/gtsffmrlek.html

C#:   public User(string name) { Name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtptuuezyq.html

[G03] 实例属性
来源：http://dali.sysykeji.top/Article/details/gtvpicnwlv.html

Py:   self.name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gttbqcmtyn.html

PHP:  public string $name = "x";
来源：http://dali.cqqwz.cn/Article/details/gttcnekksk.html

JS:   this.name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtuxbjjpbk.html

TS:   name: string = "x";
来源：http://dali.yangfankeji.com/Article/details/gtqklizkwn.html

Java: private String name;
来源：http://dali.fengsongda.top/Article/details/gtqppskuku.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cdnleiting.top/Article/details/gtqpouwdrw.html

Ruby: @name = "x"
来源：http://dali.dashuyun.cn/Article/details/gthxxzqvsg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cdnleiting.top/Article/details/gtdqajljmr.html

[G04] 定义方法
来源：http://dali.xylfe.cn/Article/details/gtcyqkvifz.html

Py:   def greet(self): return self.name
来源：http://dali.yueranfly.top/Article/details/gtqjgwacaz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtlssmyqgc.html

JS:   greet() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtcjbkvosg.html

TS:   greet(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtqvblldvn.html

Java: String greet() { return name; }
来源：http://dali.andypj.xyz/Article/details/gtlbclgucz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtwdhorgfe.html

Ruby: def greet; @name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsademfhg.html

C#:   public string Greet() => Name;
来源：http://dali.yangfankeji.com/Article/details/gtooveudok.html

[G05] 继承
来源：http://dali.shangyingyoupin.top/Article/details/gtcubfgysq.html

Py:   class Admin(User): pass
来源：http://dali.snrcjt.cn/Article/details/gtcccbbxsm.html

PHP:  class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtnsjkyyuh.html

JS:   class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtwhwakziz.html

TS:   class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtsznsyokg.html

Java: class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtcpkgfpjg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxuanxn.top/Article/details/gtycexjeuq.html

Ruby: class Admin < User; end
来源：http://dali.wangshuangyany.cn/Article/details/gtvbzlmlar.html

C#:   class Admin : User {}
来源：http://dali.jqgufenzy.top/Article/details/gtgspszuop.html

[G06] 重写方法
来源：http://dali.pycfn.com/Article/details/gtdbuclmkc.html

Py:   def greet(self): return "admin"
来源：http://dali.chenlongwang.top/Article/details/gteniliedh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gttkywtedx.html

JS:   greet() { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtqlargwpb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtxojmrahy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtwhyijfsq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yvedp.cn/Article/details/gtreegwbrv.html

Ruby: def greet; "admin"; end
来源：http://dali.daria6918.cn/Article/details/gtcckadeqd.html

C#:   public override string Greet() => "admin";
来源：http://dali.meibo888.top/Article/details/gteuieqtam.html

[G07] 调用父类方法
来源：http://dali.mhx1999.top/Article/details/gtfyocwokc.html

Py:   super().greet()
来源：http://dali.gogol.net.cn/Article/details/gtdbdobiwq.html

PHP:  parent::greet();
来源：http://dali.aizwys.cn/Article/details/gtsshmiiws.html

JS:   super.greet();
来源：http://dali.birdmap.top/Article/details/gtmiafbnqc.html

TS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtovtgkeel.html

Java: super.greet();
来源：http://dali.xuanzx.com/Article/details/gtpslbzztk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtocpkqhzq.html

Ruby: super
来源：http://dali.kuanghao11.cn/Article/details/gtvgeaeioa.html

C#:   base.Greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtwjwwdlms.html

[G08] 静态方法与属性
来源：http://dali.smart0.xyz/Article/details/gtromqhsdw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.dianchejie.cn/Article/details/gthbbrkkeb.html

PHP:  public static function f() {}
来源：http://dali.xziqi.cn/Article/details/gtsqcwqafc.html

JS:   static f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtfiwxuqjf.html

TS:   static f(): void {}
来源：http://dali.zdqjudy.top/Article/details/gtdqxgjkgf.html

Java: static void f() {}
来源：http://dali.c1oappe.top/Article/details/gtbfqniyyl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzharzuoe.html

Ruby: def self.f; end
来源：http://dali.meibo888.top/Article/details/gtcqtpdjbt.html

C#:   public static void F() {}
来源：http://dali.ehwqpu.com/Article/details/gtnenxfqkh.html

[G09] 接口 / 抽象类
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrviqqara.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zycfv.cn/Article/details/gtfkmkbozy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cheryme.top/Article/details/gtsjvhplcd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xylfe.cn/Article/details/gtnicnvfut.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangshuangyany.cn/Article/details/gtimcdhbyk.html

Java: interface Shape { double area(); }
来源：http://dali.yueranfly.top/Article/details/gtdwfvfvqv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gotoacloud.top/Article/details/gtgcttomjk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenjidiqi.icu/Article/details/gtanduoegq.html

C#:   interface IShape { double Area(); }
来源：http://dali.hywenlv.cn/Article/details/gtucegrmox.html

[G10] 访问控制
来源：http://dali.gogol.net.cn/Article/details/gttibigalx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yongpay.top/Article/details/gtnjzzdomu.html

PHP:  public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtddtmxbgu.html

JS:   #private 字段；其余公开
来源：http://dali.tianlin.xyz/Article/details/gtudiizdts.html

TS:   public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gthrrahphv.html

Java: public / protected / private / 默认包级
来源：http://dali.xuetiantiany.cn/Article/details/gtldjqloxp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xylfe.cn/Article/details/gtmkjqicez.html

Ruby: public / protected / private
来源：http://dali.fengsongda.top/Article/details/gtilsbypdg.html

C#:   public / protected / private / internal
来源：http://dali.ppjwa.cn/Article/details/gtzxqpwamc.html

[G11] getter / setter
来源：http://dali.hongshengwenyu.top/Article/details/gtzhvzccfd.html

Py:   @property 与 @x.setter
来源：http://dali.jinqigfzy.top/Article/details/gtvunepdxm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbilvweva.html

JS:   get name() { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gtosgjmqku.html

TS:   get name(): string { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gtrkcqtogn.html

Java: public String getName() { return name; }
来源：http://dali.ivvv.top/Article/details/gtcsrgmdsq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gtqdlfhbhn.html

Ruby: attr_accessor :name
来源：http://dali.pengpengdd.cyou/Article/details/gtnohkeewm.html

C#:   public string Name { get; set; }
来源：http://dali.fengsongda.top/Article/details/gtqqpmzugm.html

[G12] 对象转字符串
来源：http://dali.cucudq.cn/Article/details/gtasklaezc.html

Py:   def __str__(self): return self.name
来源：http://dali.yangfankeji.com/Article/details/gtyvkjuojr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gtqeoigbxs.html

JS:   toString() { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtcslmekkm.html

TS:   toString(): string { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdnnfzfbh.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtqcpmzifb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gtpjaheufv.html

Ruby: def to_s; @name; end
来源：http://dali.tanke756.top/Article/details/gtfhmpvjms.html

C#:   public override string ToString() => Name;
来源：http://dali.yangfankeji.com/Article/details/gttaufvzss.html

[G13] 判断对象类型
来源：http://dali.kuanghao11.cn/Article/details/gttfgonsym.html

Py:   isinstance(u, User)
来源：http://dali.smart0.xyz/Article/details/gtujxwkqvv.html

PHP:  $u instanceof User
来源：http://dali.redwolf501.top/Article/details/gteafzkceo.html

JS:   u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtpejfnwyp.html

TS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtwmntgixb.html

Java: u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtkrgemqcy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.0kj1m.cn/Article/details/gthtdfjzfu.html

Ruby: u.is_a?(User)
来源：http://dali.vqdsnc.cn/Article/details/gtpzofveut.html

C#:   u is User
来源：http://dali.yanxiufei.cn/Article/details/gtlxelldqm.html

[G14] 数据类 / record
来源：http://dali.jqgfzy.top/Article/details/gtltvdwhqi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sweek.top/Article/details/gtpevgflpl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivcqmcer.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.aibaodan.cn/Article/details/gtnaiurlku.html

TS:   type User = { name: string; age: number };
来源：http://dali.guannengcc.top/Article/details/gtnjmevgqc.html

Java: record User(String name, int age) {}
来源：http://dali.meibo888.top/Article/details/gtlqgmiphv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.vqdsnc.cn/Article/details/gtgvnyfkhb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cdnleiting.top/Article/details/gtkjsalcgd.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxuanxn.top/Article/details/gtpibjrerb.html

[G15] 枚举
来源：http://dali.cashguo.top/Article/details/gtmtqiwwgm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnxiangtu.top/Article/details/gtahqimgaj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.havefunace.top/Article/details/gtkpjgfase.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtfwjncm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.9152youxi.cn/Article/details/gtxkkpduji.html

Java: enum Color { RED, GREEN }
来源：http://dali.jyoumei.cn/Article/details/gtgftnoyma.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.0kj1m.cn/Article/details/gtoaczkyyc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmmrdamq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gtqktgrilv.html

[G16] 对象转数组 / 字典
来源：http://dali.mhx1999.top/Article/details/gtaultveal.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgfzy.top/Article/details/gtzdfnnbqv.html

PHP:  get_object_vars($obj);
来源：http://dali.smart0.xyz/Article/details/gttyvoblil.html

JS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gtyastpype.html

TS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtllasydol.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.316326.xyz/Article/details/gtqskrbhew.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangshuangyany.cn/Article/details/gteiihhdlj.html

Ruby: obj.instance_variables
来源：http://dali.daria6918.cn/Article/details/gtwpyomfve.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gtnbekfahs.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtngxottiz.html

H. 异常与错误处理
来源：http://dali.shzxlz.cn/Article/details/gtrrlqnehz.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtxzwkjsjj.html

[H01] try / catch 基础
来源：http://dali.haohaochexian.top/Article/details/gtpzhbopor.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hnxiangtu.top/Article/details/gtmtwdnqgp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.andypj.xyz/Article/details/gtqjswpebf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gtmbvvujdh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gtltimvuyu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnxiangtu.top/Article/details/gtwiwdeand.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangshuangyany.cn/Article/details/gtilzpyzhz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.mhx1999.top/Article/details/gtiufjclzc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.iojbl.cn/Article/details/gtyoldpukl.html

[H02] finally / ensure 收尾
来源：http://dali.vqdsnc.cn/Article/details/gtpowzjdfr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.havefunace.top/Article/details/gthpniqydg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtumjippnf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtwuhpydjv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtpgrdyxje.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtqpnrneqy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258888.top/Article/details/gtpqxunbhc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.svipenyu.cn/Article/details/gtgrzlxkuj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtyyvdpnwe.html


<!-- 参考信息 -->