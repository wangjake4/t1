代发 wailian999

Go:   if s == "" {}
来源：http://dali.vqdsnc.cn/Article/details/gtzqfrwxgt.html

Ruby: if s.empty?
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjlkuhiuu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.redwolf501.top/Article/details/gtrlilddvw.html

[E21] 超长截断加省略号
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpttxhbe.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gotoacloud.top/Article/details/gtuevhaywc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gtknnullzz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtxjlbbunc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtskfjavgf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtjcvqxncc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhengqikj.top/Article/details/gtzmtpnzik.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtispiyuxf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.meibo888.top/Article/details/gtahvrgszb.html

[E22] 字节长度与字符长度
来源：http://dali.yj202588.top/Article/details/gticlsomhz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.meibo888.top/Article/details/gtofqjiasx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gtxbsrtsxs.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtqgluqwjt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gtxbdetkav.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aizwys.cn/Article/details/gtverswwaj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.vqdsnc.cn/Article/details/gtgvqbryir.html

Ruby: s.bytesize;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsktinfai.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtibelvlje.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtlqkdglqa.html

F. 文件与目录
来源：http://dali.hysaishi.cn/Article/details/gtzuykotnl.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtddayxqio.html

[F01] 读取整个文件
来源：http://dali.daxiang520.top/Article/details/gtxsbqoeil.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ydzc1.top/Article/details/gtnixnmtgc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtmfmfxgke.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.redwolf501.top/Article/details/gtwvhdzhnq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sxryk.cn/Article/details/gthrngukdl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gteiawcztz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.daxiang520.top/Article/details/gteklsnigx.html

Ruby: File.read("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtanzckyhw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtbizszous.html

[F02] 逐行读取文件
来源：http://dali.jiagoushi.top/Article/details/gtuzepvnyi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.vqdsnc.cn/Article/details/gtevnohhla.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ehwqpu.com/Article/details/gtnmxvpyax.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hammf.cn/Article/details/gtooxujvbc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daxiang520.top/Article/details/gtzyxnefmh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gtolybfvdh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zdqjudy.top/Article/details/gtscphfkmv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.wangshuangyany.cn/Article/details/gtxyzsmbns.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.snrcjt.cn/Article/details/gttxeaacpz.html

[F03] 写入文件（覆盖）
来源：http://dali.dashuyun.cn/Article/details/gttmgvmpjt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinqigufen.top/Article/details/gtbddwnrie.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.snrcjt.cn/Article/details/gtbncvhzfw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gtazlpqtku.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gtvigjkngl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yonumen.top/Article/details/gtideovxzb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yangfankeji.com/Article/details/gtegemiela.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jlsjyb.cn/Article/details/gtxaxsokeh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zycfv.cn/Article/details/gtcyrrogel.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangtech.top/Article/details/gttadatwen.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtceubsmze.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbgmhkzzp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.c1oappe.top/Article/details/gteehedkuc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yvedp.cn/Article/details/gtbainnrob.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.aibaodan.cn/Article/details/gtayigaoht.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtaudmeitk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tianlin.xyz/Article/details/gtyimirnov.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yueranfly.top/Article/details/gtbqdgrqps.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxinkj.top/Article/details/gtvbiehcoy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zdqjudy.top/Article/details/gtbascnffj.html

PHP:  file_exists("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtkpevoopx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtoopntpen.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtvwnltzjy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtpdjbkxlm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.haohaochexian.top/Article/details/gtbcggspuk.html

Ruby: File.exist?("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtalmgvzph.html

C#:   File.Exists("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtzxqbmcua.html

[F06] 删除文件
来源：http://dali.jinqigufen.top/Article/details/gtruicsrzu.html

Py:   os.remove("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtfwnplszz.html

PHP:  unlink("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtyuakwdmp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtnsxqhnwt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtqhfjbjzd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtrijjzfsb.html

Go:   os.Remove("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtodcnehgg.html

Ruby: File.delete("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtozahqfnb.html

C#:   File.Delete("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gthiaoxymx.html

[F07] 创建目录（含多级）
来源：http://dali.birdmap.top/Article/details/gtdqykxzpv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.wangdashe.top/Article/details/gtmdojtnuc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ydzc1.top/Article/details/gtknqnltve.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gtjxomrcji.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gtdudjhzpv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzeuuqix.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzlmunesf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daxiang520.top/Article/details/gtrwlckwif.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yangfankeji.com/Article/details/gtxpockhip.html

[F08] 遍历目录
来源：http://dali.ehwqpu.com/Article/details/gtuwiimflr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.316326.xyz/Article/details/gtkipsyvkh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gaohongyu789.top/Article/details/gtenpzqdtj.html

JS:   fs.readdirSync("dir")
来源：http://dali.mhx1999.top/Article/details/gtcmxgnbey.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtnzefjbbc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.316326.xyz/Article/details/gtwjmlkdws.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ppjwa.cn/Article/details/gtujbezpyu.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258888.top/Article/details/gtuthhmbio.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuxming.cn/Article/details/gttclnmbop.html

[F09] 获取文件大小
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgqedcayg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtymbndvuo.html

PHP:  filesize("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtkrxsxpnl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.c1oappe.top/Article/details/gtdquidska.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aizwys.cn/Article/details/gtedbaxvqy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtbxyrmibm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj20258.top/Article/details/gtrfoyaqpi.html

Ruby: File.size("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtpctvwpcu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pycfn.com/Article/details/gtowewqbvh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.bjfxy.top/Article/details/gtnwfiyubz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtdprfmysy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.meibo888.top/Article/details/gtyrqmtxmj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtgjawdchh.html

TS:   path.extname("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtzpnlvuuu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nanxinkj.top/Article/details/gtgoyajlbn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtxavalqqs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtpyrkheim.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtgwhutcaf.html

[F11] 复制与移动文件
来源：http://dali.pycfn.com/Article/details/gtxenfrxmr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtlfdzoort.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yvedp.cn/Article/details/gtwcjxhubr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlivexedg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvecbgwzn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinqigufen.top/Article/details/gtzkhvbbiw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigufen.top/Article/details/gtxaauavdo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtcwmmrdrv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yuxming.cn/Article/details/gtngswgkxi.html

[F12] CSV 读写
来源：http://dali.fengsongda.top/Article/details/gtrsjdaced.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.daxiang520.top/Article/details/gtqowusakk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hfpthk.cn/Article/details/gttyvaesil.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hywenlv.cn/Article/details/gtmzbmitkt.html

TS:   // 同上
来源：http://dali.jyoumei.cn/Article/details/gtryozxmcx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yonumen.top/Article/details/gtlaeabxns.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangtech.top/Article/details/gttbgoyqcq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jlsjyb.cn/Article/details/gtzlzlavrs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nwbrower.top/Article/details/gtwfydrrdq.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtqtksorej.html

G. 面向对象
来源：http://dali.xuanzx.com/Article/details/gtyjaavzal.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtpfrltyiv.html

[G01] 定义类
来源：http://dali.tian-w.cn/Article/details/gtdjwxnokv.html

Py:   class User: pass
来源：http://dali.tianlin.xyz/Article/details/gtraktparm.html

PHP:  class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtzcvdopuk.html

JS:   class User {}
来源：http://dali.xylfe.cn/Article/details/gtfpllkoks.html

TS:   class User { name: string = ""; }
来源：http://dali.yuxming.cn/Article/details/gtnudmwtvm.html

Java: class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtlzcgsjve.html

Go:   type User struct { Name string }
来源：http://dali.fzhhl.top/Article/details/gtulsxrolk.html

Ruby: class User; end
来源：http://dali.hammf.cn/Article/details/gtdzqpvvxm.html

C#:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtpiksavmh.html

[G02] 构造函数
来源：http://dali.cucudq.cn/Article/details/gtbclgrlbj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yuanzhike.top/Article/details/gtwctifcjx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.guannengcc.top/Article/details/gtarixmbpj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.svipenyu.cn/Article/details/gtwbjhoteq.html

TS:   constructor(public name: string) {}
来源：http://dali.bjfxy.top/Article/details/gtgjtbndlq.html

Java: User(String name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gtsthipraj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hongshengwenyu.top/Article/details/gtvshkfrbp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jyoumei.cn/Article/details/gtytfcawbl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigufen.top/Article/details/gtijlsybgb.html

[G03] 实例属性
来源：http://dali.xuanzx.com/Article/details/gtjxidmruc.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gtlltqaskb.html

PHP:  public string $name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtfkxgqfnb.html

JS:   this.name = "x";
来源：http://dali.9152youxi.cn/Article/details/gtttthbgnq.html

TS:   name: string = "x";
来源：http://dali.nwbrower.top/Article/details/gtizdxpjal.html

Java: private String name;
来源：http://dali.haohaochexian.top/Article/details/gtawcuvgec.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.vqdsnc.cn/Article/details/gtwtwmgash.html

Ruby: @name = "x"
来源：http://dali.jqgfzy.top/Article/details/gtpqsvleff.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gotoacloud.top/Article/details/gtcfntdpur.html

[G04] 定义方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtamweyvez.html

Py:   def greet(self): return self.name
来源：http://dali.daria6918.cn/Article/details/gtjucqwims.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtyomnnhhz.html

JS:   greet() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtgvkaivtq.html

TS:   greet(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtazzzebrl.html

Java: String greet() { return name; }
来源：http://dali.gzhubu.top/Article/details/gtpmefqyid.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthnbemjif.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gtwrhilbnr.html

C#:   public string Greet() => Name;
来源：http://dali.hfpthk.cn/Article/details/gtkfkvdliz.html

[G05] 继承
来源：http://dali.gotoacloud.top/Article/details/gtompeusoz.html

Py:   class Admin(User): pass
来源：http://dali.c1oappe.top/Article/details/gtaxtlqmrd.html

PHP:  class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtxjnigsjl.html

JS:   class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtmyjyiktg.html

TS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtyaefuoqi.html

Java: class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtqqjcvleh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ydzc1.top/Article/details/gtbckslwan.html

Ruby: class Admin < User; end
来源：http://dali.tian-w.cn/Article/details/gtjyirgbpr.html

C#:   class Admin : User {}
来源：http://dali.yvedp.cn/Article/details/gtrhvnbhwp.html

[G06] 重写方法
来源：http://dali.svipenyu.cn/Article/details/gtstutocao.html

Py:   def greet(self): return "admin"
来源：http://dali.hfpthk.cn/Article/details/gtsworakul.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtzeywotux.html

JS:   greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtwukytkvz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqstiuob.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtjauiccia.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aibaodan.cn/Article/details/gttazybzjd.html

Ruby: def greet; "admin"; end
来源：http://dali.nanxuanxn.top/Article/details/gtyyriklsx.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuanzx.com/Article/details/gtaayxgwrr.html

[G07] 调用父类方法
来源：http://dali.0kj1m.cn/Article/details/gtqjyrutim.html

Py:   super().greet()
来源：http://dali.jiagoushi.top/Article/details/gthnpmeogj.html

PHP:  parent::greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtelauphmk.html

JS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gtmjjwsqlu.html

TS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gtphwlqvca.html

Java: super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtexrmpgim.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tianlin.xyz/Article/details/gtjnuvktpv.html

Ruby: super
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbpmlfetm.html

C#:   base.Greet();
来源：http://dali.gotoacloud.top/Article/details/gtrgaffyzq.html

[G08] 静态方法与属性
来源：http://dali.jlsjyb.cn/Article/details/gtevtgpocn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xziqi.cn/Article/details/gttrevhjxn.html

PHP:  public static function f() {}
来源：http://dali.cheryme.top/Article/details/gtfjekgjbh.html

JS:   static f() {}
来源：http://dali.daxiang520.top/Article/details/gtdwzasrsv.html

TS:   static f(): void {}
来源：http://dali.hywenlv.cn/Article/details/gtyonhqrrg.html

Java: static void f() {}
来源：http://dali.9152youxi.cn/Article/details/gtokobxyfz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258888.top/Article/details/gtmqwdomgc.html

Ruby: def self.f; end
来源：http://dali.svipenyu.cn/Article/details/gtogabmvpf.html

C#:   public static void F() {}
来源：http://dali.zdqjudy.top/Article/details/gtczfdbiah.html

[G09] 接口 / 抽象类
来源：http://dali.yuxming.cn/Article/details/gtisdkmvso.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tanke756.top/Article/details/gtfvshcinn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yuxming.cn/Article/details/gtnuqypljn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.quarkkingdee.top/Article/details/gtgkhvxswx.html

TS:   interface Shape { area(): number; }
来源：http://dali.andypj.xyz/Article/details/gtiqqgubyz.html

Java: interface Shape { double area(); }
来源：http://dali.tian-w.cn/Article/details/gtgsinnbig.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yangfankeji.com/Article/details/gtzsyyiyoz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxxkdaun.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenzaomai.com/Article/details/gtdzpgagel.html

[G10] 访问控制
来源：http://dali.xziqi.cn/Article/details/gtkkspcvjx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.feifeiyinyue.top/Article/details/gtfrwchike.html

PHP:  public / protected / private
来源：http://dali.jianghu66.top/Article/details/gtrscgswby.html

JS:   #private 字段；其余公开
来源：http://dali.xylfe.cn/Article/details/gtkvduezlg.html

TS:   public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtifbqekhs.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigfzy.top/Article/details/gttleoczdi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.bjfxy.top/Article/details/gtyicchphv.html

Ruby: public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gtndicqhqb.html

C#:   public / protected / private / internal
来源：http://dali.aizwys.cn/Article/details/gtehcyahxv.html

[G11] getter / setter
来源：http://dali.shangyingyoupin.top/Article/details/gtsdsbkyjo.html

Py:   @property 与 @x.setter
来源：http://dali.zhoulong.xyz/Article/details/gtklxfpnqh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtahwihtmh.html

JS:   get name() { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gtcdwcqkgw.html

TS:   get name(): string { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtdyankoqd.html

Java: public String getName() { return name; }
来源：http://dali.sweek.top/Article/details/gtpjcprjrr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gtrkfawrvp.html

Ruby: attr_accessor :name
来源：http://dali.fzhhl.top/Article/details/gtrxhrsgho.html

C#:   public string Name { get; set; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxoepycxa.html

[G12] 对象转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtmkyovkrw.html

Py:   def __str__(self): return self.name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgovlzwld.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gtfgkvgqsn.html

JS:   toString() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtydcqlllh.html

TS:   toString(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjegpbof.html

Java: @Override public String toString() { return name; }
来源：http://dali.sxryk.cn/Article/details/gtczasxwif.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtcbsiopvc.html

Ruby: def to_s; @name; end
来源：http://dali.dashuyun.cn/Article/details/gtouzmnexz.html

C#:   public override string ToString() => Name;
来源：http://dali.chenlongwang.top/Article/details/gterdwbmdr.html

[G13] 判断对象类型
来源：http://dali.vqdsnc.cn/Article/details/gtzpxhcspt.html

Py:   isinstance(u, User)
来源：http://dali.pengpengdd.cyou/Article/details/gtoyevwgom.html

PHP:  $u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gthynrpcce.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gtlnhmqlhb.html

TS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gtmilnrxcj.html

Java: u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtkpffvbyi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuxming.cn/Article/details/gtlmwbwvtl.html

Ruby: u.is_a?(User)
来源：http://dali.haohaochexian.top/Article/details/gtdweuiicj.html

C#:   u is User
来源：http://dali.daria6918.cn/Article/details/gtlbnbvclz.html

[G14] 数据类 / record
来源：http://dali.jlsjyb.cn/Article/details/gttgfzvgkl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.pycfn.com/Article/details/gtvihotscj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.wangdashe.top/Article/details/gtrjtdbxrw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuanzhike.top/Article/details/gtmjrwvzje.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigufen.top/Article/details/gtecryilfz.html

Java: record User(String name, int age) {}
来源：http://dali.c1oappe.top/Article/details/gtlomfenyi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dashuyun.cn/Article/details/gtmlonqccg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gaohongyu789.top/Article/details/gtpxfxnnvh.html

C#:   record User(string Name, int Age);
来源：http://dali.fengsongda.top/Article/details/gtgrnpvmuf.html

[G15] 枚举
来源：http://dali.9152youxi.cn/Article/details/gtqloelhre.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenjidiqi.icu/Article/details/gtrdqphtry.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuanzhike.top/Article/details/gtrqvvpxno.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenjidiqi.icu/Article/details/gtnbtzcaff.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj202588.top/Article/details/gtboomivoq.html

Java: enum Color { RED, GREEN }
来源：http://dali.316326.xyz/Article/details/gtjvbvxrns.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hammf.cn/Article/details/gtbbmytikn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxinkj.top/Article/details/gtvsfrqwar.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtemjbgyxy.html

[G16] 对象转数组 / 字典
来源：http://dali.yuxming.cn/Article/details/gtwyvvhzws.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cqqwz.cn/Article/details/gtrrisxiyo.html

PHP:  get_object_vars($obj);
来源：http://dali.aibaodan.cn/Article/details/gtzgwtnaby.html

JS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gtaekumxnu.html

TS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtkqarwxvd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj202588.top/Article/details/gtrckbvsuq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenlongwang.top/Article/details/gtujulniwy.html

Ruby: obj.instance_variables
来源：http://dali.hywenlv.cn/Article/details/gtbdrsveht.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqmkjijb.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtgjqlwuty.html

H. 异常与错误处理
来源：http://dali.hnxiangtu.top/Article/details/gtxrvozqet.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtdvpufzsm.html

[H01] try / catch 基础
来源：http://dali.zycfv.cn/Article/details/gtgdkynxtf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigufen.top/Article/details/gtoatiiyss.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtninsdjcx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gtnsiemgzv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gtdlsaumqg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj202588.top/Article/details/gttpvnsvqr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xuetiantiany.cn/Article/details/gtzaihrvrz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yuanzhike.top/Article/details/gtqjdrilby.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zdqjudy.top/Article/details/gtvwkxrrys.html

[H02] finally / ensure 收尾
来源：http://dali.tianlin.xyz/Article/details/gtacdknrgk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258.top/Article/details/gtakqumnja.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtczfoymgw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtlwdnvjgq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtsawxwwfc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtnklreszr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yuanzhike.top/Article/details/gtsbwhatgv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgfzy.top/Article/details/gtqvihhaqv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtnivliwgq.html


<!-- 参考信息 -->