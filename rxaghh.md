代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gt2hggjaewn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj20258888.top/Article/details/gt2coshsokh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.pycfn.com/Article/details/gt2rxszrckx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gt2lfjaaeoj.html

[E22] 字节长度与字符长度
来源：http://dali.daria6918.cn/Article/details/gt2rcscmrfj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daria6918.cn/Article/details/gt2ehxhiwke.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gt2vlfounoc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.haohaochexian.top/Article/details/gt2asdpnzgp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sysykeji.top/Article/details/gt2tgcwyurt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zycfv.cn/Article/details/gt2stbrtqqc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.iojbl.cn/Article/details/gt2rzyhtswe.html

Ruby: s.bytesize;  s.length
来源：http://dali.yueranfly.top/Article/details/gt2czpuupix.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xuetiantiany.cn/Article/details/gt2rrnjhnkp.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2gyvlkzik.html

F. 文件与目录
来源：http://dali.zhengqikj.top/Article/details/gt2llrdqzng.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2rkqooovt.html

[F01] 读取整个文件
来源：http://dali.yueranfly.top/Article/details/gt2vtkvqsvw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jqgufenzy.top/Article/details/gt2jrakfcuo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2lkqtcuyh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.redwolf501.top/Article/details/gt2wdtqnqnp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gt2bzflbzxc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gt2wpatzdez.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.aizwys.cn/Article/details/gt2oquxhsml.html

Ruby: File.read("a.txt")
来源：http://dali.sweek.top/Article/details/gt2zzrlefta.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj20258.top/Article/details/gt2udkhtolo.html

[F02] 逐行读取文件
来源：http://dali.0kj1m.cn/Article/details/gt2gmnhvqcl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xinyue.icu/Article/details/gt2xvbgldxq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.birdmap.top/Article/details/gt2iltaqflz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pycfn.com/Article/details/gt2cbbtgtin.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.redwolf501.top/Article/details/gt2tktubvwi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gt2jpkyjaja.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.havefunace.top/Article/details/gt2xzwukxle.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinqigfzy.top/Article/details/gt2uypuqmdl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxuanxn.top/Article/details/gt2uabkrkjf.html

[F03] 写入文件（覆盖）
来源：http://dali.fzhhl.top/Article/details/gt2azfctlbw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yueranfly.top/Article/details/gt2dhgxawym.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gt2dikqavtb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ofgkfqrd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.meibo888.top/Article/details/gt2lvohbpmv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.316326.xyz/Article/details/gt2jywjoqga.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yueranfly.top/Article/details/gt2izrxetqa.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rjvzwgch.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nanxinkj.top/Article/details/gt2fawsgwri.html

[F04] 追加写入文件
来源：http://dali.zhixingplan.top/Article/details/gt2ptsnmifa.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hysaishi.cn/Article/details/gt2oezuyjwt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nanxuanxn.top/Article/details/gt2eaeqcisn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.quarkkingdee.top/Article/details/gt2zbiempvi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pycfn.com/Article/details/gt2zqfbkdcs.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jiagoushi.top/Article/details/gt2rvaykanm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj202588.top/Article/details/gt2hjmqotde.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tian-w.cn/Article/details/gt2upirtqui.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hxnpgyxp.html

[F05] 判断文件或目录是否存在
来源：http://dali.cqqwz.cn/Article/details/gt2rhmrueub.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinqigufen.top/Article/details/gt2pojvkagd.html

PHP:  file_exists("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2qhtvilss.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2fqivujno.html

TS:   fs.existsSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2nflqxcqd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2naqfvkwb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cucudq.cn/Article/details/gt2kkfbodqr.html

Ruby: File.exist?("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2tgujahap.html

C#:   File.Exists("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2barndzlh.html

[F06] 删除文件
来源：http://dali.xinyue.icu/Article/details/gt2uivvydhc.html

Py:   os.remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2dzexdzdm.html

PHP:  unlink("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2xdkvgdkc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2ghtcaxqw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2cuznhyum.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gt2xcuxmlif.html

Go:   os.Remove("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2bnudrojf.html

Ruby: File.delete("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2eftgtgne.html

C#:   File.Delete("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2xcgkembq.html

[F07] 创建目录（含多级）
来源：http://dali.smart0.xyz/Article/details/gt2yqnynpmc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shzxlz.cn/Article/details/gt2gjhlhiyn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sxryk.cn/Article/details/gt2pqegecfp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.iojbl.cn/Article/details/gt2jkrgyqex.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuanzhike.top/Article/details/gt2uslnrzvu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jimgkogq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.0kj1m.cn/Article/details/gt2jlryxirk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hongshengwenyu.top/Article/details/gt2cwgcmtia.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenjidiqi.icu/Article/details/gt2tlgkbmuj.html

[F08] 遍历目录
来源：http://dali.xuanzx.com/Article/details/gt2busixeky.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sufxvd.cn/Article/details/gt2wozopxyf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yvedp.cn/Article/details/gt2tvszjpyw.html

JS:   fs.readdirSync("dir")
来源：http://dali.daria6918.cn/Article/details/gt2xuowwfze.html

TS:   fs.readdirSync("dir")
来源：http://dali.jiagoushi.top/Article/details/gt2ajbkqgnk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gogol.net.cn/Article/details/gt2hqzzlier.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.vqdsnc.cn/Article/details/gt2inaimzvo.html

Ruby: Dir.children("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2wkawhmkh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sufxvd.cn/Article/details/gt2oomrzzid.html

[F09] 获取文件大小
来源：http://dali.nanxuanxn.top/Article/details/gt2wyspmdzd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2kbiuatgk.html

PHP:  filesize("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2vhhynbax.html

JS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gt2odmdcieb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aizwys.cn/Article/details/gt2mkopcwvz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gt2nyainocc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hysaishi.cn/Article/details/gt2cmtalbtg.html

Ruby: File.size("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ikvsfzih.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenlongwang.top/Article/details/gt2xfmbgyjj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.birdmap.top/Article/details/gt2wmyueibb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2vajdufar.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2sdvyclbj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2kiyxpsoq.html

TS:   path.extname("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2ajbygpuq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hnqzz.top/Article/details/gt2loolwmpy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2ussxjrjh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ajgwpsvm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2xistisit.html

[F11] 复制与移动文件
来源：http://dali.yonumen.top/Article/details/gt2akpyshbi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gt2blogvpaa.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2gbnbgvmy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2nfihcmav.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2phfwadkt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ynlklush.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnqzz.top/Article/details/gt2ndgmixot.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gt2ymnwzpke.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sysykeji.top/Article/details/gt2tthwliwm.html

[F12] CSV 读写
来源：http://dali.hysaishi.cn/Article/details/gt2xeummagw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shuidangran.top/Article/details/gt2kyeajicg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nanxinkj.top/Article/details/gt2wihgnlut.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mmnizgyp.html

TS:   // 同上
来源：http://dali.guowangkeji.top/Article/details/gt2gzgjljyx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.9152youxi.cn/Article/details/gt2dhhlrljl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yangfankeji.com/Article/details/gt2cyuaxmsl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jianghu66.top/Article/details/gt2gttrpxip.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.9152youxi.cn/Article/details/gt2xcgglzdn.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2coyxzash.html

G. 面向对象
来源：http://dali.ybcxt.top/Article/details/gt2lngqvvhz.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2mhriuhpt.html

[G01] 定义类
来源：http://dali.xuanzx.com/Article/details/gt2ytedmjdi.html

Py:   class User: pass
来源：http://dali.andypj.xyz/Article/details/gt2nkptgcon.html

PHP:  class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2odkpgkap.html

JS:   class User {}
来源：http://dali.daria6918.cn/Article/details/gt2wwoogfst.html

TS:   class User { name: string = ""; }
来源：http://dali.jiagoushi.top/Article/details/gt2xdsozscq.html

Java: class User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2grnnvvwb.html

Go:   type User struct { Name string }
来源：http://dali.aizwys.cn/Article/details/gt2tkhsuebd.html

Ruby: class User; end
来源：http://dali.nwbrower.top/Article/details/gt2iugtxxyr.html

C#:   class User {}
来源：http://dali.jqgfzy.top/Article/details/gt2suugcqxh.html

[G02] 构造函数
来源：http://dali.dianchejie.cn/Article/details/gt2ormsjhbs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ybcxt.top/Article/details/gt2mucoojlt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xylfe.cn/Article/details/gt2jyrdyysv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gt2txkjihym.html

TS:   constructor(public name: string) {}
来源：http://dali.zdqjudy.top/Article/details/gt2zhzupkwk.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2trtocaen.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.dianchejie.cn/Article/details/gt2rfikoqcj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fengsongda.top/Article/details/gt2gqkddsax.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wwzscwoh.html

[G03] 实例属性
来源：http://dali.zdqjudy.top/Article/details/gt2vtookuax.html

Py:   self.name = "x"
来源：http://dali.jyoumei.cn/Article/details/gt2qrgpifty.html

PHP:  public string $name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gt2fnhybuky.html

JS:   this.name = "x";
来源：http://dali.svipenyu.cn/Article/details/gt2irntrqci.html

TS:   name: string = "x";
来源：http://dali.havefunace.top/Article/details/gt2cdsetpay.html

Java: private String name;
来源：http://dali.cdnleiting.top/Article/details/gt2uoxzfjbv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2avscnxrw.html

Ruby: @name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gt2wqltzopo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigfzy.top/Article/details/gt2ekfywaat.html

[G04] 定义方法
来源：http://dali.jinqigufen.top/Article/details/gt2qivlyayb.html

Py:   def greet(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gt2rodfqxwc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wworpfkn.html

JS:   greet() { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gt2pbpmlcnr.html

TS:   greet(): string { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gt2jcxfnqzd.html

Java: String greet() { return name; }
来源：http://dali.pycfn.com/Article/details/gt2lhsapqck.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gt2rytubsgr.html

Ruby: def greet; @name; end
来源：http://dali.yueranfly.top/Article/details/gt2oatssjxz.html

C#:   public string Greet() => Name;
来源：http://dali.tian-w.cn/Article/details/gt2egmjwoha.html

[G05] 继承
来源：http://dali.guowangkeji.top/Article/details/gt2tvffqrev.html

Py:   class Admin(User): pass
来源：http://dali.quarkkingdee.top/Article/details/gt2urwjmwny.html

PHP:  class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2ircfgyoe.html

JS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gt2fntfhttd.html

TS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gt2yvaqdktc.html

Java: class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2faplxziq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxuanxn.top/Article/details/gt2vqdiizwb.html

Ruby: class Admin < User; end
来源：http://dali.aizwys.cn/Article/details/gt2pbyatlvj.html

C#:   class Admin : User {}
来源：http://dali.tianlin.xyz/Article/details/gt2tfcokxgt.html

[G06] 重写方法
来源：http://dali.redwolf501.top/Article/details/gt2zrkcmjal.html

Py:   def greet(self): return "admin"
来源：http://dali.jqgfzy.top/Article/details/gt2zevovaoz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2tbabdefr.html

JS:   greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2thkdblwz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2amtyhzbn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2nnbmvlqy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cdnleiting.top/Article/details/gt2smscxtqg.html

Ruby: def greet; "admin"; end
来源：http://dali.hammf.cn/Article/details/gt2dmujldmj.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj202588.top/Article/details/gt2nqwkqcaz.html

[G07] 调用父类方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jevbqyht.html

Py:   super().greet()
来源：http://dali.nanxinkj.top/Article/details/gt2gaztjbbg.html

PHP:  parent::greet();
来源：http://dali.ybcxt.top/Article/details/gt2orycbocl.html

JS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gt2mjqbsocp.html

TS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gt2ysfdybzr.html

Java: super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2reqtzzno.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuanzhike.top/Article/details/gt2vxfirxpm.html

Ruby: super
来源：http://dali.hysaishi.cn/Article/details/gt2bufozgmx.html

C#:   base.Greet();
来源：http://dali.jiagoushi.top/Article/details/gt2wjbzqaze.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fsgiygfq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgfzy.top/Article/details/gt2nfxqpfpu.html

PHP:  public static function f() {}
来源：http://dali.yanxiufei.cn/Article/details/gt2tpmbwzgy.html

JS:   static f() {}
来源：http://dali.ppjwa.cn/Article/details/gt2kuwcaamo.html

TS:   static f(): void {}
来源：http://dali.snrcjt.cn/Article/details/gt2wyiddvqe.html

Java: static void f() {}
来源：http://dali.hnxiangtu.top/Article/details/gt2thqawzij.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2leqwfsgg.html

Ruby: def self.f; end
来源：http://dali.zhongyouzk.top/Article/details/gt2fjzqhupo.html

C#:   public static void F() {}
来源：http://dali.jinqigfzy.top/Article/details/gt2rtdpcadh.html

[G09] 接口 / 抽象类
来源：http://dali.guowangkeji.top/Article/details/gt2nctcyftd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ydzc1.top/Article/details/gt2lofdqzig.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gaohongyu789.top/Article/details/gt2epvgegrq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.c1oappe.top/Article/details/gt2ticdytwf.html

TS:   interface Shape { area(): number; }
来源：http://dali.cdnleiting.top/Article/details/gt2sbwfwkrd.html

Java: interface Shape { double area(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2lbbnhyzr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hysaishi.cn/Article/details/gt2kksochhy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guannengcc.top/Article/details/gt2mmhhfvbb.html

C#:   interface IShape { double Area(); }
来源：http://dali.xinyue.icu/Article/details/gt2mtuijlkc.html

[G10] 访问控制
来源：http://dali.ehwqpu.com/Article/details/gt2gjckldqf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhiwuduotai.top/Article/details/gt2ihhtdrrw.html

PHP:  public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gt2lxhiixpv.html

JS:   #private 字段；其余公开
来源：http://dali.gogol.net.cn/Article/details/gt2forzqatv.html

TS:   public / protected / private
来源：http://dali.316326.xyz/Article/details/gt2moscfmac.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258888.top/Article/details/gt2xwcuperj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnxiangtu.top/Article/details/gt2mvewzlzo.html

Ruby: public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gt2mxenydjk.html

C#:   public / protected / private / internal
来源：http://dali.xziqi.cn/Article/details/gt2pguhbxpi.html

[G11] getter / setter
来源：http://dali.chenlongwang.top/Article/details/gt2bidkoqtl.html

Py:   @property 与 @x.setter
来源：http://dali.snrcjt.cn/Article/details/gt2zpunetgt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gt2bjujjijj.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gt2pcecfruq.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gt2pzperozx.html

Java: public String getName() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2gpvklikf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gt2sbhgytuu.html

Ruby: attr_accessor :name
来源：http://dali.zhongyouzk.top/Article/details/gt2fwkenlxn.html

C#:   public string Name { get; set; }
来源：http://dali.ydzc1.top/Article/details/gt2nqafobrp.html

[G12] 对象转字符串
来源：http://dali.cashguo.top/Article/details/gt2azsjyoos.html

Py:   def __str__(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gt2brbmemaz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gt2vhtdstkd.html

JS:   toString() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gt2vhxxyvdz.html

TS:   toString(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2bjhrhgec.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2epuihnie.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gt2bleuptsd.html

Ruby: def to_s; @name; end
来源：http://dali.zdqjudy.top/Article/details/gt2bdwgaung.html

C#:   public override string ToString() => Name;
来源：http://dali.9152youxi.cn/Article/details/gt2jznvqnar.html

[G13] 判断对象类型
来源：http://dali.zycfv.cn/Article/details/gt2znkhnxzu.html

Py:   isinstance(u, User)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gmlktowv.html

PHP:  $u instanceof User
来源：http://dali.meibo888.top/Article/details/gt2xdxtxnrb.html

JS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gt2wajegljw.html

TS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gt2odzmopxv.html

Java: u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gt2pzokjhqg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yongpay.top/Article/details/gt2rsjrrkap.html

Ruby: u.is_a?(User)
来源：http://dali.tanke756.top/Article/details/gt2qmezqyaw.html

C#:   u is User
来源：http://dali.hongshengwenyu.top/Article/details/gt2bulflwps.html

[G14] 数据类 / record
来源：http://dali.tianlin.xyz/Article/details/gt2zjibvccq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ysxjbzpm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ivvv.top/Article/details/gt2szcdebkw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tanke756.top/Article/details/gt2meyrqduh.html

TS:   type User = { name: string; age: number };
来源：http://dali.yuanzhike.top/Article/details/gt2qwcpyrom.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yuokotsl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.redwolf501.top/Article/details/gt2kovxokjy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.smart0.xyz/Article/details/gt2qcxohzfn.html

C#:   record User(string Name, int Age);
来源：http://dali.zhengqikj.top/Article/details/gt2lqrupfgz.html

[G15] 枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2byywrxej.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gotoacloud.top/Article/details/gt2mghxlpjd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gzhubu.top/Article/details/gt2vcrhntha.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pengpengdd.cyou/Article/details/gt2lyxikncw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guannengcc.top/Article/details/gt2lngizwfg.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigfzy.top/Article/details/gt2mwvzbldl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jlsjyb.cn/Article/details/gt2necjdkpo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigufen.top/Article/details/gt2hgsdxcoi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jdimqavg.html

[G16] 对象转数组 / 字典
来源：http://dali.vqdsnc.cn/Article/details/gt2kktnsgqt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zycfv.cn/Article/details/gt2mxccsuxe.html

PHP:  get_object_vars($obj);
来源：http://dali.gaohongyu789.top/Article/details/gt2icgwypln.html

JS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2hwoaxraq.html

TS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gt2tybuwjhc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenlongwang.top/Article/details/gt2izamgkkn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.smart0.xyz/Article/details/gt2qnuozrvs.html

Ruby: obj.instance_variables
来源：http://dali.gotoacloud.top/Article/details/gt2tonmajmo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gt2iscccnpk.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2ejzsshei.html

H. 异常与错误处理
来源：http://dali.vqdsnc.cn/Article/details/gt2yxcqjgma.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2fcxuavuw.html

[H01] try / catch 基础
来源：http://dali.yuanzhike.top/Article/details/gt2cdoxvvzo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ucerxdhz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.fzhhl.top/Article/details/gt2ndbnjzfx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2erbiznez.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gt2sbumyqwy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.9152youxi.cn/Article/details/gt2rnuqvezp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ybcxt.top/Article/details/gt2wblrestg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sxryk.cn/Article/details/gt2tbfmndsb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.316326.xyz/Article/details/gt2eynitijl.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigfzy.top/Article/details/gt2etitvddv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dashuyun.cn/Article/details/gt2eehmtvte.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gt2kcwdidhk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gt2rymcqfwb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gt2lzfzycis.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2dxvaiwfh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.snrcjt.cn/Article/details/gt2adnkdczn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2saqubsxm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gt2zpqociww.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jqqtgtue.html

Py:   raise ValueError("错误信息")
来源：http://dali.cdnleiting.top/Article/details/gt2wubmblcv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gt2ofptwtze.html

JS:   throw new Error("错误信息");
来源：http://dali.hnqzz.top/Article/details/gt2wphqyhgr.html

TS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2ookkchgr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2fffpqele.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgfzy.top/Article/details/gt2vwrqzjfo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yonumen.top/Article/details/gt2lwmawpmu.html


<!-- 参考信息 -->