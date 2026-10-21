代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jlsjyb.cn/Article/details/gtfosmnpok.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gtedtdqgkc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtsawymicn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtvdgyzlmo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtapxtiewc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yonumen.top/Article/details/gtyfnwgxvy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtnmhhaoen.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtsolgdzkp.html

[E22] 字节长度与字符长度
来源：http://dali.yuanzhike.top/Article/details/gtwpomjhry.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtjvnxqyzf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtgulmshff.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xylfe.cn/Article/details/gtqkupqakk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gotoacloud.top/Article/details/gtcszjjcrv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjlqtcpk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.c1oappe.top/Article/details/gtogrotpws.html

Ruby: s.bytesize;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjoceyzcr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hammf.cn/Article/details/gtlvlxiasx.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtnxyltucv.html

F. 文件与目录
来源：http://dali.sysykeji.top/Article/details/gtrpvyzauv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtirdzrdsq.html

[F01] 读取整个文件
来源：http://dali.aizwys.cn/Article/details/gtyzmirvwn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqtvgupj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtkoufpvpr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hnqzz.top/Article/details/gtuhnnbsdf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtotsxdxyb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtxqpgekik.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hongshengwenyu.top/Article/details/gtpbtgtrgm.html

Ruby: File.read("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtvjbuzdjl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtibhjrkdr.html

[F02] 逐行读取文件
来源：http://dali.chenzaomai.com/Article/details/gtltlwdvgg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.iojbl.cn/Article/details/gthiqfxthb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cheryme.top/Article/details/gtjgxfetos.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fzhhl.top/Article/details/gtvwmherzh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sysykeji.top/Article/details/gtlabfngrg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gtojacmwux.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.snrcjt.cn/Article/details/gteavbjqie.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nwbrower.top/Article/details/gtayvuqmzc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gogol.net.cn/Article/details/gthkgqxocw.html

[F03] 写入文件（覆盖）
来源：http://dali.bjfxy.top/Article/details/gtksmrzqyy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yongpay.top/Article/details/gtraahnhzl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigufen.top/Article/details/gtkjnugsdf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gtkydkyddv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xinyue.icu/Article/details/gtyjrjpuxy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yuxming.cn/Article/details/gtsrwihotj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sufxvd.cn/Article/details/gtbcxdfgtl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gtxormyafp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gtpcvxooyl.html

[F04] 追加写入文件
来源：http://dali.sweek.top/Article/details/gtastzqyat.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zdqjudy.top/Article/details/gthepbsohr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.pengpengdd.cyou/Article/details/gtyvbvemgc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhixingplan.top/Article/details/gthdytooya.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xylfe.cn/Article/details/gtvinzjmmz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jyoumei.cn/Article/details/gtquegbxsg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yueranfly.top/Article/details/gtaeuqyqgq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tian-w.cn/Article/details/gtkvrgqsfx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.daxiang520.top/Article/details/gtevrzzjxi.html

[F05] 判断文件或目录是否存在
来源：http://dali.yuxming.cn/Article/details/gtejcbjqep.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shangyingyoupin.top/Article/details/gtvkdjnhrm.html

PHP:  file_exists("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtcqqcrbas.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehvyhkwb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtflkkylab.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtgcjddjnd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj202588.top/Article/details/gttsavmpsd.html

Ruby: File.exist?("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtpcpqpoyg.html

C#:   File.Exists("a.txt")
来源：http://dali.yongpay.top/Article/details/gthypmiurl.html

[F06] 删除文件
来源：http://dali.cdnleiting.top/Article/details/gthriademr.html

Py:   os.remove("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtdqdgyalh.html

PHP:  unlink("a.txt");
来源：http://dali.316326.xyz/Article/details/gtwiqthmyv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtkqyiwibk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtrsuzdpwh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtxcyoxaxr.html

Go:   os.Remove("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtvmymtybb.html

Ruby: File.delete("a.txt")
来源：http://dali.meibo888.top/Article/details/gturhvopeq.html

C#:   File.Delete("a.txt");
来源：http://dali.meibo888.top/Article/details/gtbhgbmcgh.html

[F07] 创建目录（含多级）
来源：http://dali.meibo888.top/Article/details/gtooapjiey.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hammf.cn/Article/details/gtrxxnykdp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.birdmap.top/Article/details/gtrzjltqgu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuanzhike.top/Article/details/gtjwjowiqq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gthpkjfkqa.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.snrcjt.cn/Article/details/gtfphavgke.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.snrcjt.cn/Article/details/gtonbvvrub.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xziqi.cn/Article/details/gtiovcxtxy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yanxiufei.cn/Article/details/gtumlnksuw.html

[F08] 遍历目录
来源：http://dali.hammf.cn/Article/details/gtcvahlsiy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.meibo888.top/Article/details/gtloqfhubs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shuidangran.top/Article/details/gtpnuienfk.html

JS:   fs.readdirSync("dir")
来源：http://dali.mhx1999.top/Article/details/gtofxuleoa.html

TS:   fs.readdirSync("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtrwzhsipp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shanyushiyangtech.top/Article/details/gtreofvekm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sweek.top/Article/details/gtpyiqygkq.html

Ruby: Dir.children("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtybdylflq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigfzy.top/Article/details/gthnbyomoq.html

[F09] 获取文件大小
来源：http://dali.chenjidiqi.icu/Article/details/gtyigdrzwn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yongpay.top/Article/details/gtbmftwdjv.html

PHP:  filesize("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqqjkgma.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yanxiufei.cn/Article/details/gtgkidxbip.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gthteiciid.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gtfmzhhfbh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgfzy.top/Article/details/gtgdklzugi.html

Ruby: File.size("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtwdfvznoz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinqigfzy.top/Article/details/gthfigkbnt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxuanxn.top/Article/details/gtgsofsugz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtmtdaqhrh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtlxuasrdj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtrzpndplb.html

TS:   path.extname("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtolfuchin.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yueranfly.top/Article/details/gtvctpqrnc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtwesdeagk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtdbmigwzp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtyamkikxw.html

[F11] 复制与移动文件
来源：http://dali.zhengqikj.top/Article/details/gtwbdgsuec.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtzefhsdoz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinqigufen.top/Article/details/gtppipuurx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gtcvtcmbwl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtlbgsnycq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.316326.xyz/Article/details/gtnxeyhoeb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.mhx1999.top/Article/details/gtnmnodref.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtyxuiozzk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ivvv.top/Article/details/gtrqpipjek.html

[F12] CSV 读写
来源：http://dali.sufxvd.cn/Article/details/gtzkigtvvb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.vqdsnc.cn/Article/details/gtudbiqnfz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnxiangtu.top/Article/details/gtrervigsf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.snrcjt.cn/Article/details/gtxrvxaiyn.html

TS:   // 同上
来源：http://dali.haohaochexian.top/Article/details/gtrzqnqqct.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hongshengwenyu.top/Article/details/gttaezbfwo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gzhubu.top/Article/details/gtarfynmup.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sufxvd.cn/Article/details/gtdcgzkrkm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigfzy.top/Article/details/gtahfthvzc.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtfmrrwmij.html

G. 面向对象
来源：http://dali.jqgfzy.top/Article/details/gtowinluyw.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtaiqtqfet.html

[G01] 定义类
来源：http://dali.sysykeji.top/Article/details/gtgrpeoupg.html

Py:   class User: pass
来源：http://dali.fzhhl.top/Article/details/gtwttgfqhs.html

PHP:  class User {}
来源：http://dali.yvedp.cn/Article/details/gtqroasmeh.html

JS:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gtqtdrtqdw.html

TS:   class User { name: string = ""; }
来源：http://dali.xuanzx.com/Article/details/gtgxoucono.html

Java: class User {}
来源：http://dali.ivvv.top/Article/details/gtytxjqwad.html

Go:   type User struct { Name string }
来源：http://dali.snrcjt.cn/Article/details/gtnhsjejpl.html

Ruby: class User; end
来源：http://dali.shzxlz.cn/Article/details/gtsmeyskjo.html

C#:   class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtmngjqqxe.html

[G02] 构造函数
来源：http://dali.xuanzx.com/Article/details/gtpgbfoobn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cdnleiting.top/Article/details/gtkoqaggac.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gogol.net.cn/Article/details/gtwqzqfgyl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gtncxvzobm.html

TS:   constructor(public name: string) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtfhiidzvw.html

Java: User(String name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gtstpumtdp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xylfe.cn/Article/details/gtsgfkzbcx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hysaishi.cn/Article/details/gtipuhjzhf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.daxiang520.top/Article/details/gtkuluejen.html

[G03] 实例属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphebnftb.html

Py:   self.name = "x"
来源：http://dali.aizwys.cn/Article/details/gtwwwykvsj.html

PHP:  public string $name = "x";
来源：http://dali.c1oappe.top/Article/details/gtzwiwcrly.html

JS:   this.name = "x";
来源：http://dali.andypj.xyz/Article/details/gtaffgiokp.html

TS:   name: string = "x";
来源：http://dali.ehwqpu.com/Article/details/gtusnbyxnd.html

Java: private String name;
来源：http://dali.birdmap.top/Article/details/gtpmmloaxa.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.havefunace.top/Article/details/gtwphdxmvh.html

Ruby: @name = "x"
来源：http://dali.xuanzx.com/Article/details/gtjuzguell.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ehwqpu.com/Article/details/gtfotkqzft.html

[G04] 定义方法
来源：http://dali.meibo888.top/Article/details/gtwlgplwlx.html

Py:   def greet(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gtbagkxpzq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gtcwazihpl.html

JS:   greet() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtxpxaakly.html

TS:   greet(): string { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtfsnenjev.html

Java: String greet() { return name; }
来源：http://dali.wangdashe.top/Article/details/gtzqtuiwve.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtuushmiwb.html

Ruby: def greet; @name; end
来源：http://dali.yvedp.cn/Article/details/gtlomhvdfs.html

C#:   public string Greet() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gtzwrofjjk.html

[G05] 继承
来源：http://dali.dashuyun.cn/Article/details/gthpnjitwm.html

Py:   class Admin(User): pass
来源：http://dali.yuxming.cn/Article/details/gtnmmoahil.html

PHP:  class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtvybshxfx.html

JS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gthoikqujy.html

TS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtdvdogvax.html

Java: class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtdhgeegte.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hysaishi.cn/Article/details/gteeiqdwfu.html

Ruby: class Admin < User; end
来源：http://dali.0kj1m.cn/Article/details/gtupuqpasr.html

C#:   class Admin : User {}
来源：http://dali.jyoumei.cn/Article/details/gtspiiiccg.html

[G06] 重写方法
来源：http://dali.meibo888.top/Article/details/gtbqoyugtp.html

Py:   def greet(self): return "admin"
来源：http://dali.yueranfly.top/Article/details/gtyugzbvxz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtjxmmikke.html

JS:   greet() { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtvieqhgjn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtgwilmuvd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtvkoxzukb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xziqi.cn/Article/details/gtteqfuyqx.html

Ruby: def greet; "admin"; end
来源：http://dali.nanxinkj.top/Article/details/gtjnaichuk.html

C#:   public override string Greet() => "admin";
来源：http://dali.daria6918.cn/Article/details/gthbpnihxr.html

[G07] 调用父类方法
来源：http://dali.hywenlv.cn/Article/details/gtpklzfgll.html

Py:   super().greet()
来源：http://dali.tanke756.top/Article/details/gtxlosmuqc.html

PHP:  parent::greet();
来源：http://dali.ppjwa.cn/Article/details/gtciaxdilm.html

JS:   super.greet();
来源：http://dali.9152youxi.cn/Article/details/gtcyasbjxw.html

TS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtaarbhdko.html

Java: super.greet();
来源：http://dali.yangfankeji.com/Article/details/gtxpdgkhzz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.bjfxy.top/Article/details/gtrfwapzvg.html

Ruby: super
来源：http://dali.aizwys.cn/Article/details/gtexmjxkpa.html

C#:   base.Greet();
来源：http://dali.nwbrower.top/Article/details/gtdbdddcrq.html

[G08] 静态方法与属性
来源：http://dali.hfpthk.cn/Article/details/gtrdlgwqqz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj20258.top/Article/details/gtkiymovet.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxowkunrc.html

JS:   static f() {}
来源：http://dali.hnqzz.top/Article/details/gtgdphtwks.html

TS:   static f(): void {}
来源：http://dali.0kj1m.cn/Article/details/gtsxkdgzwa.html

Java: static void f() {}
来源：http://dali.andypj.xyz/Article/details/gtwsfahtki.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shzxlz.cn/Article/details/gtwhyanene.html

Ruby: def self.f; end
来源：http://dali.jinqigufen.top/Article/details/gthokrwubq.html

C#:   public static void F() {}
来源：http://dali.yj20258888.top/Article/details/gtsjwzcxmx.html

[G09] 接口 / 抽象类
来源：http://dali.xuanzx.com/Article/details/gtwpuhvlvg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.smart0.xyz/Article/details/gtvvwwkrrq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sysykeji.top/Article/details/gtxnurwdex.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj20258888.top/Article/details/gtbbgysflc.html

TS:   interface Shape { area(): number; }
来源：http://dali.havefunace.top/Article/details/gtgaxcmtsw.html

Java: interface Shape { double area(); }
来源：http://dali.andypj.xyz/Article/details/gtamzstniw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shuidangran.top/Article/details/gtpkwhdxbo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.kuanghao11.cn/Article/details/gtusviheuk.html

C#:   interface IShape { double Area(); }
来源：http://dali.sweek.top/Article/details/gtrxlrtpmv.html

[G10] 访问控制
来源：http://dali.cashguo.top/Article/details/gtgpqxsupu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gogol.net.cn/Article/details/gtvuwiuzur.html

PHP:  public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtjmvjwbtc.html

JS:   #private 字段；其余公开
来源：http://dali.andypj.xyz/Article/details/gtfyedctol.html

TS:   public / protected / private
来源：http://dali.andypj.xyz/Article/details/gtlwgzccxj.html

Java: public / protected / private / 默认包级
来源：http://dali.yonumen.top/Article/details/gttrdqpfjt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigfzy.top/Article/details/gtwlpqoedd.html

Ruby: public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gtvfiirjdj.html

C#:   public / protected / private / internal
来源：http://dali.ydzc1.top/Article/details/gtgbmeavxx.html

[G11] getter / setter
来源：http://dali.tanke756.top/Article/details/gtymgxipqr.html

Py:   @property 与 @x.setter
来源：http://dali.gotoacloud.top/Article/details/gtpxfuqhhm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gtixdupaiz.html

JS:   get name() { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gteqkukqbd.html

TS:   get name(): string { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gtjixismhf.html

Java: public String getName() { return name; }
来源：http://dali.cashguo.top/Article/details/gtfcrzejib.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gtdqvohlwz.html

Ruby: attr_accessor :name
来源：http://dali.tanke756.top/Article/details/gtfeesttzb.html

C#:   public string Name { get; set; }
来源：http://dali.yuanzhike.top/Article/details/gtbapmketb.html

[G12] 对象转字符串
来源：http://dali.gzhubu.top/Article/details/gtgrgtjerf.html

Py:   def __str__(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gtzfxbyssg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gtkloswlue.html

JS:   toString() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtlojmtxwu.html

TS:   toString(): string { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtazhzmtsa.html

Java: @Override public String toString() { return name; }
来源：http://dali.fengsongda.top/Article/details/gtkqbqwmda.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gtcodiavdn.html

Ruby: def to_s; @name; end
来源：http://dali.zhiwuduotai.top/Article/details/gtwcuprenz.html

C#:   public override string ToString() => Name;
来源：http://dali.gotoacloud.top/Article/details/gtlusrwikp.html

[G13] 判断对象类型
来源：http://dali.zhongyouzk.top/Article/details/gtjeqbkdpc.html

Py:   isinstance(u, User)
来源：http://dali.nanxinkj.top/Article/details/gtzohcgkru.html

PHP:  $u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtrggqocfv.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gtxupnqmbo.html

TS:   u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtykixcmdk.html

Java: u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtlfxejjly.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ehwqpu.com/Article/details/gtjpgqnxbq.html

Ruby: u.is_a?(User)
来源：http://dali.guannengcc.top/Article/details/gtlipnaqca.html

C#:   u is User
来源：http://dali.hnqzz.top/Article/details/gtafqcdeav.html

[G14] 数据类 / record
来源：http://dali.iojbl.cn/Article/details/gtkhblqzhy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.kuanghao11.cn/Article/details/gtmykuyayi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gzhubu.top/Article/details/gtgaoqnqsk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hfpthk.cn/Article/details/gtrtvsgqwl.html

TS:   type User = { name: string; age: number };
来源：http://dali.xziqi.cn/Article/details/gtnznkwznr.html

Java: record User(String name, int age) {}
来源：http://dali.cucudq.cn/Article/details/gtiiwnrjfi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ehwqpu.com/Article/details/gtngkyocvm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.aizwys.cn/Article/details/gtcwkuqcym.html

C#:   record User(string Name, int Age);
来源：http://dali.zhoulong.xyz/Article/details/gtzgikotor.html

[G15] 枚举
来源：http://dali.0kj1m.cn/Article/details/gtwugrtxky.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ybcxt.top/Article/details/gtoignqwpo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.havefunace.top/Article/details/gtfuzxmrqg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhoulong.xyz/Article/details/gtkjgxobwy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtsfkjtlio.html

Java: enum Color { RED, GREEN }
来源：http://dali.aizwys.cn/Article/details/gtymspvzmz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nwbrower.top/Article/details/gtoixlrtmw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tianlin.xyz/Article/details/gtuolcfrvf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gtiotdwoxh.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gtxesbiinp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcyivfwu.html

PHP:  get_object_vars($obj);
来源：http://dali.snrcjt.cn/Article/details/gtvpufmpgs.html

JS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gttvatbogi.html

TS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gtvcmzuvcq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hfpthk.cn/Article/details/gtkneckjbf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj202588.top/Article/details/gtkwmshdne.html

Ruby: obj.instance_variables
来源：http://dali.yonumen.top/Article/details/gtruvbpppu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.quarkkingdee.top/Article/details/gtxqtwrsou.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtuwjaqilv.html

H. 异常与错误处理
来源：http://dali.yanxiufei.cn/Article/details/gtgkwubatd.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtlhlkkutu.html

[H01] try / catch 基础
来源：http://dali.iojbl.cn/Article/details/gtfebrzmuj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.bjfxy.top/Article/details/gtzxmktduk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xinyue.icu/Article/details/gtwcqhnijm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gtsharbkcm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gtdtfgbvlf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangshuangyany.cn/Article/details/gtnizqdzrh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aizwys.cn/Article/details/gtahbivkoq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xuanzx.com/Article/details/gthabdinli.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuanzhike.top/Article/details/gtzznfuvfu.html

[H02] finally / ensure 收尾
来源：http://dali.xinyue.icu/Article/details/gtubpqiuto.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sysykeji.top/Article/details/gttszeurxw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtjbdulrmg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtfoxdnzba.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtrvjywdja.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtzxgwkhpg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdhcgjyt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guowangkeji.top/Article/details/gtjfvvkfpl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtarrxsgtw.html

[H03] 主动抛出异常
来源：http://dali.xuetiantiany.cn/Article/details/gtsqpqmszk.html

Py:   raise ValueError("错误信息")
来源：http://dali.meibo888.top/Article/details/gtlewoeosy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtfdjzycqq.html

JS:   throw new Error("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtgdciuhvy.html


<!-- 参考信息 -->