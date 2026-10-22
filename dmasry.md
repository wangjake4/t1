代发 wailian999

Go:   if s == "" {}
来源：http://dali.nwbrower.top/Article/details/gtzhdvvnhg.html

Ruby: if s.empty?
来源：http://dali.tanke756.top/Article/details/gtiwyvmlic.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgomwvzkr.html

[E21] 超长截断加省略号
来源：http://dali.jiagoushi.top/Article/details/gtccbfhhdv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yueranfly.top/Article/details/gtmvhqwrrw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gttunqjlme.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtwgoucrhg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtjxlnufxf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtlpumpfia.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuqrvacgs.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtbghaevsc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hammf.cn/Article/details/gtucaomfvm.html

[E22] 字节长度与字符长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtenpxmvac.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.andypj.xyz/Article/details/gttfqdodvq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtqhxbcsuq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gttokggnlp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ppjwa.cn/Article/details/gtahsiahwz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zycfv.cn/Article/details/gtwvjvzqli.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinqigfzy.top/Article/details/gtsuzrhkzq.html

Ruby: s.bytesize;  s.length
来源：http://dali.zycfv.cn/Article/details/gtczzypmlg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj202588.top/Article/details/gtdwehjzzi.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gthppxtddl.html

F. 文件与目录
来源：http://dali.ppjwa.cn/Article/details/gtseoujxwz.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtiudqxqza.html

[F01] 读取整个文件
来源：http://dali.chenzaomai.com/Article/details/gthvlphxfl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yonumen.top/Article/details/gtgoceapia.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtrznvzhzf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dashuyun.cn/Article/details/gtemcvezqm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gtjfnwuhnn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtsduljvih.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shzxlz.cn/Article/details/gthyyvjdva.html

Ruby: File.read("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtrcdjpkxm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtzfoxckfv.html

[F02] 逐行读取文件
来源：http://dali.chenlongwang.top/Article/details/gtizphhtez.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.kuanghao11.cn/Article/details/gtnyzmylle.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkujgqtpk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.haohaochexian.top/Article/details/gtinqisvjk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdweufakl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gtxkmoiosl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.quarkkingdee.top/Article/details/gtqsexokam.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ybcxt.top/Article/details/gtlbcfetct.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.birdmap.top/Article/details/gtaxvrbxoo.html

[F03] 写入文件（覆盖）
来源：http://dali.svipenyu.cn/Article/details/gtcfiomkyn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cdnleiting.top/Article/details/gthqmwqvvg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhixingplan.top/Article/details/gtofsduznw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtbomvwzrb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtznaubgkr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.0kj1m.cn/Article/details/gttayygixw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.iojbl.cn/Article/details/gtqkozgpcf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.vqdsnc.cn/Article/details/gtjibgjzpt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gtqebruvje.html

[F04] 追加写入文件
来源：http://dali.tianlin.xyz/Article/details/gtofxdavav.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtmqacwnhp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj20258.top/Article/details/gtwomjbaru.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gogol.net.cn/Article/details/gtddhkyjtt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gtcbcxdscx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hysaishi.cn/Article/details/gtgzlosxao.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cqqwz.cn/Article/details/gtslxfakoh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.haohaochexian.top/Article/details/gtilmehzkv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.havefunace.top/Article/details/gtjjnwgfke.html

[F05] 判断文件或目录是否存在
来源：http://dali.cucudq.cn/Article/details/gtxqkefhtz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinghuilouyu.cn/Article/details/gtuetybvli.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsamewwcz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtjcdcwozs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtbjmgnxel.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtaxfahbba.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.meibo888.top/Article/details/gtlcatchxe.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtvrdnlape.html

C#:   File.Exists("a.txt")
来源：http://dali.hammf.cn/Article/details/gtoepulwqr.html

[F06] 删除文件
来源：http://dali.cheryme.top/Article/details/gtlutfjnmd.html

Py:   os.remove("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtupuhybul.html

PHP:  unlink("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkmiaqcjq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtvrutbthk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtgtxzmjyb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtqlslnrmq.html

Go:   os.Remove("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtjpxgncye.html

Ruby: File.delete("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkebbzzjd.html

C#:   File.Delete("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtmozycdtm.html

[F07] 创建目录（含多级）
来源：http://dali.cucudq.cn/Article/details/gtbehmxswv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ivvv.top/Article/details/gtuoxpccoc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.quarkkingdee.top/Article/details/gttsiykzyy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xziqi.cn/Article/details/gtfqqqslne.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.c1oappe.top/Article/details/gtfqscsvkr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258888.top/Article/details/gtzimurbqy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.haohaochexian.top/Article/details/gtucsdnkja.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.meibo888.top/Article/details/gtyxjuwgxw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.iojbl.cn/Article/details/gtnkpqrihi.html

[F08] 遍历目录
来源：http://dali.smart0.xyz/Article/details/gtyzwpzuus.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daxiang520.top/Article/details/gtklxhdxgp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.havefunace.top/Article/details/gtcglbpjpp.html

JS:   fs.readdirSync("dir")
来源：http://dali.ybcxt.top/Article/details/gtolrnfuqr.html

TS:   fs.readdirSync("dir")
来源：http://dali.fzhhl.top/Article/details/gtabcmmbyy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gtvjdzydwt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.daria6918.cn/Article/details/gtcqvfgcuf.html

Ruby: Dir.children("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxdvsnxz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aizwys.cn/Article/details/gthwxdaylk.html

[F09] 获取文件大小
来源：http://dali.ivvv.top/Article/details/gtihdycoki.html

Py:   os.path.getsize("a.txt")
来源：http://dali.havefunace.top/Article/details/gtpndyozjz.html

PHP:  filesize("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtpbdfoksg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gteszlrzaf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gtdgxouszl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtrfifcnqg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jlsjyb.cn/Article/details/gtanocoexx.html

Ruby: File.size("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtcxrpzhzo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqfpzebn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ivvv.top/Article/details/gtcdqyhfpb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtullbozrf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtdjgijvzd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtyhyiofoq.html

TS:   path.extname("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtuxpyhboi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sysykeji.top/Article/details/gtwctzwkon.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtaihboemx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtxaayfxgs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtwmojfuim.html

[F11] 复制与移动文件
来源：http://dali.xziqi.cn/Article/details/gtcrdmxpag.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtryfttict.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jiagoushi.top/Article/details/gthochalvz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtboypraxc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtoeoqyfvy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gtjfwufete.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sysykeji.top/Article/details/gtqektxxdj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtarbeboal.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jiagoushi.top/Article/details/gtepumdxin.html

[F12] CSV 读写
来源：http://dali.wangshuangyany.cn/Article/details/gtjhxssceh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sweek.top/Article/details/gtkpnyqemz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj202588.top/Article/details/gtkzmqxwfb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.wangshuangyany.cn/Article/details/gtruwkqtjl.html

TS:   // 同上
来源：http://dali.nanxinkj.top/Article/details/gteyniekco.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpbksifx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.smart0.xyz/Article/details/gtzfyxfqkm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangdashe.top/Article/details/gtcgwcbxnu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yvedp.cn/Article/details/gtkyibiald.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtkfjanhqu.html

G. 面向对象
来源：http://dali.guowangkeji.top/Article/details/gtvwukvuvg.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtoniaefpn.html

[G01] 定义类
来源：http://dali.xylfe.cn/Article/details/gtasiycuwm.html

Py:   class User: pass
来源：http://dali.xuetiantiany.cn/Article/details/gtpvggqpna.html

PHP:  class User {}
来源：http://dali.jqgufenzy.top/Article/details/gtadqspchs.html

JS:   class User {}
来源：http://dali.aibaodan.cn/Article/details/gtuhyffovn.html

TS:   class User { name: string = ""; }
来源：http://dali.jinqigufen.top/Article/details/gtulgqomnl.html

Java: class User {}
来源：http://dali.fzhhl.top/Article/details/gtnsklywqv.html

Go:   type User struct { Name string }
来源：http://dali.fengsongda.top/Article/details/gtrrxebucp.html

Ruby: class User; end
来源：http://dali.redwolf501.top/Article/details/gtsjgidqgi.html

C#:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gthhhdapjm.html

[G02] 构造函数
来源：http://dali.dianchejie.cn/Article/details/gthhojswis.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yongpay.top/Article/details/gtytjszwrh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.redwolf501.top/Article/details/gtxaocdywq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cashguo.top/Article/details/gtrbgrghyo.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigufen.top/Article/details/gtffykphnc.html

Java: User(String name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gtisqrxveo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cheryme.top/Article/details/gtkveiiadm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xziqi.cn/Article/details/gtsjnqqgon.html

C#:   public User(string name) { Name = name; }
来源：http://dali.wangdashe.top/Article/details/gthbbfqlac.html

[G03] 实例属性
来源：http://dali.yueranfly.top/Article/details/gtuwdwtlml.html

Py:   self.name = "x"
来源：http://dali.yvedp.cn/Article/details/gtexjpkmpb.html

PHP:  public string $name = "x";
来源：http://dali.ehwqpu.com/Article/details/gtusqoydux.html

JS:   this.name = "x";
来源：http://dali.gzhubu.top/Article/details/gtupmupdui.html

TS:   name: string = "x";
来源：http://dali.jianghu66.top/Article/details/gtupwmitzh.html

Java: private String name;
来源：http://dali.hnxiangtu.top/Article/details/gtyfyrihiq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gzhubu.top/Article/details/gtqwggbztb.html

Ruby: @name = "x"
来源：http://dali.havefunace.top/Article/details/gtroacijnw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gaohongyu789.top/Article/details/gthsuaefzl.html

[G04] 定义方法
来源：http://dali.chenlongwang.top/Article/details/gtuqodplbi.html

Py:   def greet(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gtotsaqkwr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gtvpadssxi.html

JS:   greet() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtomdqkmkv.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzrpyhuk.html

Java: String greet() { return name; }
来源：http://dali.gzhubu.top/Article/details/gtnzfpiyss.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtwkbostze.html

Ruby: def greet; @name; end
来源：http://dali.xylfe.cn/Article/details/gtyigcpqbu.html

C#:   public string Greet() => Name;
来源：http://dali.ydzc1.top/Article/details/gtcsjtaxwp.html

[G05] 继承
来源：http://dali.pycfn.com/Article/details/gtsupxxobx.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangtech.top/Article/details/gtckaxngda.html

PHP:  class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtnyigwtln.html

JS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtbmrwmpgh.html

TS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtpgtqenzg.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtaxhtqwtd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangtech.top/Article/details/gtakljdxev.html

Ruby: class Admin < User; end
来源：http://dali.fzhhl.top/Article/details/gtmksjqtas.html

C#:   class Admin : User {}
来源：http://dali.shzxlz.cn/Article/details/gtibpiiwsn.html

[G06] 重写方法
来源：http://dali.snrcjt.cn/Article/details/gtzxfbqthm.html

Py:   def greet(self): return "admin"
来源：http://dali.zhoulong.xyz/Article/details/gtfkprglcg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtrvvuigjn.html

JS:   greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtvjarpiej.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtodmodalw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtiwdcvgax.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.redwolf501.top/Article/details/gtrywmacng.html

Ruby: def greet; "admin"; end
来源：http://dali.tian-w.cn/Article/details/gtngtiyran.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenzaomai.com/Article/details/gthpqrhsxw.html

[G07] 调用父类方法
来源：http://dali.aizwys.cn/Article/details/gtgwepjiia.html

Py:   super().greet()
来源：http://dali.cheryme.top/Article/details/gtdhvudozl.html

PHP:  parent::greet();
来源：http://dali.meibo888.top/Article/details/gtvfxxajsd.html

JS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gtkbtocsvc.html

TS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gtafgzsjub.html

Java: super.greet();
来源：http://dali.fengsongda.top/Article/details/gtywnfvenx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xziqi.cn/Article/details/gtqcckadpv.html

Ruby: super
来源：http://dali.xinyue.icu/Article/details/gtymdsrnvf.html

C#:   base.Greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtjvirpozr.html

[G08] 静态方法与属性
来源：http://dali.yuxming.cn/Article/details/gtbyfjserv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhiwuduotai.top/Article/details/gtoqnlvkqe.html

PHP:  public static function f() {}
来源：http://dali.guowangkeji.top/Article/details/gttttecvyn.html

JS:   static f() {}
来源：http://dali.zycfv.cn/Article/details/gtmnbbbyqy.html

TS:   static f(): void {}
来源：http://dali.svipenyu.cn/Article/details/gtaqccdcdp.html

Java: static void f() {}
来源：http://dali.cashguo.top/Article/details/gtejbjyjrr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hongshengwenyu.top/Article/details/gtpstpncrv.html

Ruby: def self.f; end
来源：http://dali.wangdashe.top/Article/details/gtqnckijzh.html

C#:   public static void F() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtbqpcfmgz.html

[G09] 接口 / 抽象类
来源：http://dali.aibaodan.cn/Article/details/gtjdpivaau.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.bjfxy.top/Article/details/gtnfytuanv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxuanxn.top/Article/details/gtirnuijcm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yongpay.top/Article/details/gtsadrydva.html

TS:   interface Shape { area(): number; }
来源：http://dali.gaohongyu789.top/Article/details/gtfdpoomig.html

Java: interface Shape { double area(); }
来源：http://dali.smart0.xyz/Article/details/gtbhptdujf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqohxagre.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnxiangtu.top/Article/details/gtmfhujgbe.html

C#:   interface IShape { double Area(); }
来源：http://dali.tianlin.xyz/Article/details/gtqwljgepn.html

[G10] 访问控制
来源：http://dali.jinqigfzy.top/Article/details/gtvqjoyuuc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sxryk.cn/Article/details/gttgcaevlb.html

PHP:  public / protected / private
来源：http://dali.cucudq.cn/Article/details/gthkqfrvso.html

JS:   #private 字段；其余公开
来源：http://dali.yvedp.cn/Article/details/gtsdubaumu.html

TS:   public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtqnbfclfp.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gthkgardwg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daxiang520.top/Article/details/gtgiwditom.html

Ruby: public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtxrfsvvrg.html

C#:   public / protected / private / internal
来源：http://dali.cdnleiting.top/Article/details/gtiqrlliny.html

[G11] getter / setter
来源：http://dali.svipenyu.cn/Article/details/gtdaqesbbh.html

Py:   @property 与 @x.setter
来源：http://dali.cashguo.top/Article/details/gtxckjadzx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtaguprthg.html

JS:   get name() { return this._name; }
来源：http://dali.ivvv.top/Article/details/gtzajtlaya.html

TS:   get name(): string { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gtlmaqweum.html

Java: public String getName() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtrbtnwldq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtyrizmrbd.html

Ruby: attr_accessor :name
来源：http://dali.jyoumei.cn/Article/details/gtverqitpx.html

C#:   public string Name { get; set; }
来源：http://dali.bjfxy.top/Article/details/gtvmladshm.html

[G12] 对象转字符串
来源：http://dali.jqgfzy.top/Article/details/gtazrblkhz.html

Py:   def __str__(self): return self.name
来源：http://dali.ydzc1.top/Article/details/gtktihlrby.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gtfwizcsip.html

JS:   toString() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhnyarzx.html

TS:   toString(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gthhndwzsc.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gthjxktorr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtufyfflgh.html

Ruby: def to_s; @name; end
来源：http://dali.dashuyun.cn/Article/details/gtcbsvtcbk.html

C#:   public override string ToString() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gtrqaipmgi.html

[G13] 判断对象类型
来源：http://dali.hongshengwenyu.top/Article/details/gttwfxlgjo.html

Py:   isinstance(u, User)
来源：http://dali.meibo888.top/Article/details/gthtqmfvto.html

PHP:  $u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtgcmxzadf.html

JS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtbclykclw.html

TS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtaxihbezq.html

Java: u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtoyopgezc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dianchejie.cn/Article/details/gtguanwrfe.html

Ruby: u.is_a?(User)
来源：http://dali.vqdsnc.cn/Article/details/gthngnykds.html

C#:   u is User
来源：http://dali.aizwys.cn/Article/details/gtuswlxrnf.html

[G14] 数据类 / record
来源：http://dali.jinghuilouyu.cn/Article/details/gtgicwybri.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjqbzeje.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.guowangkeji.top/Article/details/gtkbrygjar.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yvedp.cn/Article/details/gtqljrilpo.html

TS:   type User = { name: string; age: number };
来源：http://dali.dashuyun.cn/Article/details/gtzbyylobq.html

Java: record User(String name, int age) {}
来源：http://dali.yuanzhike.top/Article/details/gtlgnkwklm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hfpthk.cn/Article/details/gtkgfhafdd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.redwolf501.top/Article/details/gtgedfxxrf.html

C#:   record User(string Name, int Age);
来源：http://dali.sufxvd.cn/Article/details/gthhhbzqnh.html

[G15] 枚举
来源：http://dali.kuanghao11.cn/Article/details/gtxpaaqbrf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnxiangtu.top/Article/details/gtjtozmobh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtxpclpkzo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hywenlv.cn/Article/details/gtxjfenwea.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtmfnlldbj.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhoulong.xyz/Article/details/gtjadwukfq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cashguo.top/Article/details/gtcszsbfwb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.iojbl.cn/Article/details/gtpvbcgxlk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.9152youxi.cn/Article/details/gttzpvyiyc.html

[G16] 对象转数组 / 字典
来源：http://dali.chenlongwang.top/Article/details/gtumklrljw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sufxvd.cn/Article/details/gtvwljopbs.html

PHP:  get_object_vars($obj);
来源：http://dali.316326.xyz/Article/details/gtwqjbduwb.html

JS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gteccyagpi.html

TS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gtazrnhrkr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.quarkkingdee.top/Article/details/gtctmfjlez.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.haohaochexian.top/Article/details/gtwxlghzsw.html

Ruby: obj.instance_variables
来源：http://dali.shzxlz.cn/Article/details/gtcxdoyqfo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gtxjnzbpqa.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtqazgfstw.html

H. 异常与错误处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzaaaxgdg.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtlbojruru.html

[H01] try / catch 基础
来源：http://dali.sufxvd.cn/Article/details/gtgebuaujv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hammf.cn/Article/details/gtfcpcxkoa.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangdashe.top/Article/details/gtfmzdpgoe.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gtrzswfzyj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gtuegbzodk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgufenzy.top/Article/details/gtalvosdyc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ybcxt.top/Article/details/gtkazlygek.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.guannengcc.top/Article/details/gtbzheuxev.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtscumjhrv.html

[H02] finally / ensure 收尾
来源：http://dali.0kj1m.cn/Article/details/gtvccnygok.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hfpthk.cn/Article/details/gtugohlibu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtudikpouw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtktdqjeaj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtodgvraus.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtkpmfkyaj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuanzx.com/Article/details/gtdoxqdesc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.redwolf501.top/Article/details/gtzyfztjih.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtjbrfbnrl.html


<!-- 参考信息 -->