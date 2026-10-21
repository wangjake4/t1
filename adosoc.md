代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gttltqczic.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.daria6918.cn/Article/details/gtdhvgemot.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj202588.top/Article/details/gtmkgilynl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtlemeoovi.html

[E22] 字节长度与字符长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfntdelj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hysaishi.cn/Article/details/gtlzhnwrfs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gtmdoaxcha.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.haohaochexian.top/Article/details/gtggupwjjg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxinkj.top/Article/details/gttxjzctie.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.kuanghao11.cn/Article/details/gtvictwcfp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cheryme.top/Article/details/gtmnhboqwk.html

Ruby: s.bytesize;  s.length
来源：http://dali.tanke756.top/Article/details/gtizntfjcy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj20258888.top/Article/details/gtgljkwicu.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtaptjzmad.html

F. 文件与目录
来源：http://dali.zhongyouzk.top/Article/details/gtdhhylqcm.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtdtcufqfe.html

[F01] 读取整个文件
来源：http://dali.bjfxy.top/Article/details/gtfgtqzcla.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sweek.top/Article/details/gtqdcxbscv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj20258888.top/Article/details/gteuorcjrl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ivvv.top/Article/details/gtkvqwhlyu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj20258.top/Article/details/gtleivqham.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtdwyblprq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ybcxt.top/Article/details/gtchpgrmqt.html

Ruby: File.read("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtlvbuoeax.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.316326.xyz/Article/details/gtaainhbkn.html

[F02] 逐行读取文件
来源：http://dali.316326.xyz/Article/details/gtkjrvizqn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yongpay.top/Article/details/gtxycjrjtv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinqigfzy.top/Article/details/gtysnnqagc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cashguo.top/Article/details/gtskyinqzx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cdnleiting.top/Article/details/gtzccnrjls.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gtxeilqvqu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.vqdsnc.cn/Article/details/gtsrxllznw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cqqwz.cn/Article/details/gtlgzgrmyu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ppjwa.cn/Article/details/gtbyinciwi.html

[F03] 写入文件（覆盖）
来源：http://dali.xziqi.cn/Article/details/gtkomgyosu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinqigfzy.top/Article/details/gtyvmeoteb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.havefunace.top/Article/details/gtlwmnzghs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gtbwnurpva.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtvczpcpfq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.haohaochexian.top/Article/details/gtsnrfagky.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.0kj1m.cn/Article/details/gtfwdwwfek.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cucudq.cn/Article/details/gtvboygoiz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.quarkkingdee.top/Article/details/gtxtacldlt.html

[F04] 追加写入文件
来源：http://dali.hysaishi.cn/Article/details/gtuarluwwg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj202588.top/Article/details/gthfdnnntj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfftsccms.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhengqikj.top/Article/details/gtrkojgfih.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ybcxt.top/Article/details/gtjsopdqjo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nanxuanxn.top/Article/details/gtxpeexexp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hfpthk.cn/Article/details/gtgkzfjcae.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.svipenyu.cn/Article/details/gteuhpotwk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gzhubu.top/Article/details/gtitlekosx.html

[F05] 判断文件或目录是否存在
来源：http://dali.jqgfzy.top/Article/details/gtjvgyuulv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnqzz.top/Article/details/gtrqxdcxwp.html

PHP:  file_exists("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtmqlvfmui.html

JS:   fs.existsSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtnugzfelh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtrjtrmevg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtrpgyetjc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzlddfvgl.html

Ruby: File.exist?("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtdwoafcvr.html

C#:   File.Exists("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtsitjinnn.html

[F06] 删除文件
来源：http://dali.xziqi.cn/Article/details/gtrnhdcdxb.html

Py:   os.remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gtwefsoaqg.html

PHP:  unlink("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtazsvesca.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtbdiomkcl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gttniqgrbf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtjdxglnne.html

Go:   os.Remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gtqgoaalow.html

Ruby: File.delete("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtvgwlcoha.html

C#:   File.Delete("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtpvyhduii.html

[F07] 创建目录（含多级）
来源：http://dali.fzhhl.top/Article/details/gtdqwhzbbf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xziqi.cn/Article/details/gtrmtfxyoa.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.redwolf501.top/Article/details/gtugdpeqfu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gtmeihqvrg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gtzsaypudv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgufenzy.top/Article/details/gtgclfddyi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nwbrower.top/Article/details/gtapjsatxe.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hongshengwenyu.top/Article/details/gtvfjhkafu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.pengpengdd.cyou/Article/details/gtfgmventl.html

[F08] 遍历目录
来源：http://dali.zhongyouzk.top/Article/details/gtkfqfgnxe.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nanxinkj.top/Article/details/gtrpgpjosw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cashguo.top/Article/details/gtgysnwdvj.html

JS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gtqnksngdk.html

TS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gtvkyvrtlb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gtihyljcpd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtppvbdljc.html

Ruby: Dir.children("dir")
来源：http://dali.jianghu66.top/Article/details/gtqapbswgu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgfzy.top/Article/details/gtjcqcfpem.html

[F09] 获取文件大小
来源：http://dali.yvedp.cn/Article/details/gtqzmtibps.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtzqpulpfh.html

PHP:  filesize("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtlgbrncop.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gthytmedlt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gtonuakdfb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtdbpvdiks.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yueranfly.top/Article/details/gtlqkfldql.html

Ruby: File.size("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtpyamuauw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.bjfxy.top/Article/details/gtiwvgqajd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jlsjyb.cn/Article/details/gtpfoztjix.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtsvxtvwfu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.guannengcc.top/Article/details/gtpxvgrjsn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtltowcfgp.html

TS:   path.extname("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtsagapaxo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yangfankeji.com/Article/details/gtzorxiqgx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtgukjggbx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gteaqtinrk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtubdpautj.html

[F11] 复制与移动文件
来源：http://dali.gzhubu.top/Article/details/gtexlsegpw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqseskomn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hysaishi.cn/Article/details/gthgmfmoch.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtmelqdeea.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtcmmkpcev.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenzaomai.com/Article/details/gtmdqtrrlr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tianlin.xyz/Article/details/gtxtnazyyj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtkvmmznty.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tianlin.xyz/Article/details/gtpusobcyy.html

[F12] CSV 读写
来源：http://dali.shangyingyoupin.top/Article/details/gtmprftppv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hfpthk.cn/Article/details/gtfklytpvs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.redwolf501.top/Article/details/gtjwudsfhy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnzudivx.html

TS:   // 同上
来源：http://dali.ybcxt.top/Article/details/gtnzwpchco.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.c1oappe.top/Article/details/gtjowvwcox.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ppjwa.cn/Article/details/gtnmhxcnwn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigufen.top/Article/details/gtuknohbdf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dashuyun.cn/Article/details/gtwbowtxai.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtwlqwnbff.html

G. 面向对象
来源：http://dali.sweek.top/Article/details/gtilohjlga.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtmajwncwt.html

[G01] 定义类
来源：http://dali.guannengcc.top/Article/details/gtulmmuird.html

Py:   class User: pass
来源：http://dali.316326.xyz/Article/details/gtsuneejbb.html

PHP:  class User {}
来源：http://dali.zhixingplan.top/Article/details/gtvydnuybq.html

JS:   class User {}
来源：http://dali.zycfv.cn/Article/details/gttbxlipbr.html

TS:   class User { name: string = ""; }
来源：http://dali.wangshuangyany.cn/Article/details/gtyccxrmzk.html

Java: class User {}
来源：http://dali.dianchejie.cn/Article/details/gtymjsvoek.html

Go:   type User struct { Name string }
来源：http://dali.xuanzx.com/Article/details/gtmpepknoe.html

Ruby: class User; end
来源：http://dali.zhengqikj.top/Article/details/gtxtjbvvad.html

C#:   class User {}
来源：http://dali.aibaodan.cn/Article/details/gtqgjnalax.html

[G02] 构造函数
来源：http://dali.nanxinkj.top/Article/details/gthirddzbb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.c1oappe.top/Article/details/gtlvrkqopa.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.andypj.xyz/Article/details/gtqwdggnxk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.c1oappe.top/Article/details/gteugloasa.html

TS:   constructor(public name: string) {}
来源：http://dali.shuidangran.top/Article/details/gthhavzchb.html

Java: User(String name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gtuxlhljld.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xuetiantiany.cn/Article/details/gtrwxykvla.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ivvv.top/Article/details/gtbhfxskuk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.9152youxi.cn/Article/details/gtndolirhs.html

[G03] 实例属性
来源：http://dali.zycfv.cn/Article/details/gttypayihq.html

Py:   self.name = "x"
来源：http://dali.guannengcc.top/Article/details/gtqldhqckp.html

PHP:  public string $name = "x";
来源：http://dali.gogol.net.cn/Article/details/gtueonfkjy.html

JS:   this.name = "x";
来源：http://dali.316326.xyz/Article/details/gtmojbinai.html

TS:   name: string = "x";
来源：http://dali.sufxvd.cn/Article/details/gtttrsnrfq.html

Java: private String name;
来源：http://dali.yongpay.top/Article/details/gttanhrtvr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.smart0.xyz/Article/details/gtfxgoiati.html

Ruby: @name = "x"
来源：http://dali.aibaodan.cn/Article/details/gtzcgmggoh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtmfzcingm.html

[G04] 定义方法
来源：http://dali.hongshengwenyu.top/Article/details/gtrrvzbmhr.html

Py:   def greet(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gtpfphvrtp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gtgvnfawla.html

JS:   greet() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtuodfayfc.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtozxqulus.html

Java: String greet() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtofikpkwr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwnqeocmx.html

Ruby: def greet; @name; end
来源：http://dali.fzhhl.top/Article/details/gtumpzqwwy.html

C#:   public string Greet() => Name;
来源：http://dali.snrcjt.cn/Article/details/gtlzpeurtk.html

[G05] 继承
来源：http://dali.shanyushiyangtech.top/Article/details/gtuuuzdpef.html

Py:   class Admin(User): pass
来源：http://dali.hnqzz.top/Article/details/gtvzdzkplg.html

PHP:  class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtmtlsqshs.html

JS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtgnjaahms.html

TS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtnddtnrwu.html

Java: class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtcdkozzlo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuanzx.com/Article/details/gtwxktyzke.html

Ruby: class Admin < User; end
来源：http://dali.jianghu66.top/Article/details/gtirprjaod.html

C#:   class Admin : User {}
来源：http://dali.xziqi.cn/Article/details/gtrlkhulxw.html

[G06] 重写方法
来源：http://dali.zhoulong.xyz/Article/details/gtueaegdfg.html

Py:   def greet(self): return "admin"
来源：http://dali.cucudq.cn/Article/details/gttkjagdcc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtswasdmmx.html

JS:   greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtukwoaodi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtkrzxhgwp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gtrzgcdtwx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.iojbl.cn/Article/details/gtmzrqjqbf.html

Ruby: def greet; "admin"; end
来源：http://dali.nwbrower.top/Article/details/gtsqpfxrkp.html

C#:   public override string Greet() => "admin";
来源：http://dali.iojbl.cn/Article/details/gtljmmnvmz.html

[G07] 调用父类方法
来源：http://dali.jinqigufen.top/Article/details/gtehqmohey.html

Py:   super().greet()
来源：http://dali.guowangkeji.top/Article/details/gtushnktoz.html

PHP:  parent::greet();
来源：http://dali.ehwqpu.com/Article/details/gtbnytonzg.html

JS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gtcqkkseoj.html

TS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gtzvcbuqmv.html

Java: super.greet();
来源：http://dali.sweek.top/Article/details/gttskejmuo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.meibo888.top/Article/details/gteuiaabib.html

Ruby: super
来源：http://dali.vqdsnc.cn/Article/details/gtlhoxyjrl.html

C#:   base.Greet();
来源：http://dali.snrcjt.cn/Article/details/gtkfbfqipf.html

[G08] 静态方法与属性
来源：http://dali.jinqigufen.top/Article/details/gtyjsogspx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenzaomai.com/Article/details/gttqgoyesi.html

PHP:  public static function f() {}
来源：http://dali.xziqi.cn/Article/details/gtmntdtepo.html

JS:   static f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzeokemab.html

TS:   static f(): void {}
来源：http://dali.chenlongwang.top/Article/details/gttpglkokk.html

Java: static void f() {}
来源：http://dali.nwbrower.top/Article/details/gtnghnpzbb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.mhx1999.top/Article/details/gtuvuxwsqx.html

Ruby: def self.f; end
来源：http://dali.nanxuanxn.top/Article/details/gtilhckrjl.html

C#:   public static void F() {}
来源：http://dali.havefunace.top/Article/details/gtgnmljwzb.html

[G09] 接口 / 抽象类
来源：http://dali.jqgufenzy.top/Article/details/gtjyoxbovy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ybcxt.top/Article/details/gthrkusvuq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fengsongda.top/Article/details/gtopogxhpy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cheryme.top/Article/details/gteltkkgih.html

TS:   interface Shape { area(): number; }
来源：http://dali.zycfv.cn/Article/details/gtyeyoawuz.html

Java: interface Shape { double area(); }
来源：http://dali.jyoumei.cn/Article/details/gtmgbqhatp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.feifeiyinyue.top/Article/details/gthjxlksuc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.316326.xyz/Article/details/gtjzvdnuyn.html

C#:   interface IShape { double Area(); }
来源：http://dali.iojbl.cn/Article/details/gtxaysvdlv.html

[G10] 访问控制
来源：http://dali.ppjwa.cn/Article/details/gttqfshfaz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cucudq.cn/Article/details/gtwunmnofe.html

PHP:  public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gtseeabtgx.html

JS:   #private 字段；其余公开
来源：http://dali.fengsongda.top/Article/details/gtuygqvfoy.html

TS:   public / protected / private
来源：http://dali.sxryk.cn/Article/details/gtbzuylszo.html

Java: public / protected / private / 默认包级
来源：http://dali.yongpay.top/Article/details/gtrxsihyul.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhoulong.xyz/Article/details/gtclfwjhse.html

Ruby: public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtufrwztwa.html

C#:   public / protected / private / internal
来源：http://dali.zhoulong.xyz/Article/details/gtcmsbmidq.html

[G11] getter / setter
来源：http://dali.sysykeji.top/Article/details/gtdlrbttbe.html

Py:   @property 与 @x.setter
来源：http://dali.wangdashe.top/Article/details/gtmetviovs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtdeajbirc.html

JS:   get name() { return this._name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrkqbllsm.html

TS:   get name(): string { return this._name; }
来源：http://dali.sxryk.cn/Article/details/gtqxyyzikp.html

Java: public String getName() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtfxswsucb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gtlrovbdpi.html

Ruby: attr_accessor :name
来源：http://dali.tanke756.top/Article/details/gtwzsemjtd.html

C#:   public string Name { get; set; }
来源：http://dali.cucudq.cn/Article/details/gtokekgxbb.html

[G12] 对象转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtrzmaztgd.html

Py:   def __str__(self): return self.name
来源：http://dali.quarkkingdee.top/Article/details/gtdwuyvyfa.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtiinkpsqm.html

JS:   toString() { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtjljcvdmj.html

TS:   toString(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gttjvedipc.html

Java: @Override public String toString() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtikdbribk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtbnaqwqac.html

Ruby: def to_s; @name; end
来源：http://dali.c1oappe.top/Article/details/gtqtooqckp.html

C#:   public override string ToString() => Name;
来源：http://dali.yonumen.top/Article/details/gthtltsvqb.html

[G13] 判断对象类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqiqeaoz.html

Py:   isinstance(u, User)
来源：http://dali.xuetiantiany.cn/Article/details/gtvumahaac.html

PHP:  $u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtiwrjdptb.html

JS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtyjtljkmg.html

TS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gtssfanvtn.html

Java: u instanceof User
来源：http://dali.yj20258.top/Article/details/gtibinacnc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gtqirrpgao.html

Ruby: u.is_a?(User)
来源：http://dali.nanxuanxn.top/Article/details/gtkketgmka.html

C#:   u is User
来源：http://dali.jqgufenzy.top/Article/details/gtzzlghynv.html

[G14] 数据类 / record
来源：http://dali.cucudq.cn/Article/details/gtngvcwfaa.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shuidangran.top/Article/details/gtvmnbfoor.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnxiangtu.top/Article/details/gtgafalbhp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhoulong.xyz/Article/details/gtoioqtzxv.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigufen.top/Article/details/gteoqazvca.html

Java: record User(String name, int age) {}
来源：http://dali.zhiwuduotai.top/Article/details/gttglobyml.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yuxming.cn/Article/details/gtlgrectyq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.vqdsnc.cn/Article/details/gtjuwhfihh.html

C#:   record User(string Name, int Age);
来源：http://dali.haohaochexian.top/Article/details/gtbnhbyatl.html

[G15] 枚举
来源：http://dali.shangyingyoupin.top/Article/details/gtwgglfroc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.smart0.xyz/Article/details/gtkzhbljms.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sysykeji.top/Article/details/gtcbvinmlg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yonumen.top/Article/details/gtzvgmbbbw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwztgqqjn.html

Java: enum Color { RED, GREEN }
来源：http://dali.9152youxi.cn/Article/details/gtbkbfyifs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shanyushiyangtech.top/Article/details/gthczujgqv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavmzcsof.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sufxvd.cn/Article/details/gtdrfahloc.html

[G16] 对象转数组 / 字典
来源：http://dali.gotoacloud.top/Article/details/gthmzcqwdo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jyoumei.cn/Article/details/gtfjfwfmkr.html

PHP:  get_object_vars($obj);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqzqzombc.html

JS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmexehnyq.html

TS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gthzbhzueg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yonumen.top/Article/details/gtdrvpkcdc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.snrcjt.cn/Article/details/gtghopyrai.html

Ruby: obj.instance_variables
来源：http://dali.vqdsnc.cn/Article/details/gtktwvmxpv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yueranfly.top/Article/details/gtvxtmmkkp.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtmsrpgkil.html

H. 异常与错误处理
来源：http://dali.chenzaomai.com/Article/details/gtjipowmft.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtyvzttelt.html

[H01] try / catch 基础
来源：http://dali.redwolf501.top/Article/details/gtlqklacwe.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jlsjyb.cn/Article/details/gttrftcahp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guannengcc.top/Article/details/gtulsayewj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gtsemcfjud.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljopnwyw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgufenzy.top/Article/details/gtdiijchfu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hysaishi.cn/Article/details/gtpxikpuzr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jlsjyb.cn/Article/details/gtzhgtenji.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhiwuduotai.top/Article/details/gtvkznzhed.html

[H02] finally / ensure 收尾
来源：http://dali.zycfv.cn/Article/details/gtipuvgejn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hammf.cn/Article/details/gtxjxnzkao.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtxlnhveyk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtbtbjplpe.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtpnojpicf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtqwvgcwhl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinghuilouyu.cn/Article/details/gtzndatfir.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.0kj1m.cn/Article/details/gtfrhwkdmg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtppbepgcd.html

[H03] 主动抛出异常
来源：http://dali.yj202588.top/Article/details/gtqeqkosbd.html

Py:   raise ValueError("错误信息")
来源：http://dali.ybcxt.top/Article/details/gttwqobwyl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtyqtxuqwz.html

JS:   throw new Error("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtxlmjzzqq.html

TS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtvpsnyrqr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtsgwbesvf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigufen.top/Article/details/gtlqixejmu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnqzz.top/Article/details/gtiqcschhy.html


<!-- 参考信息 -->