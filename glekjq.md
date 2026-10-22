代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gtcjnfdckt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yueranfly.top/Article/details/gteeiyzbcq.html

TS:   if (s === "") {}
来源：http://dali.pengpengdd.cyou/Article/details/gtotnhfyhx.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtynknmpzy.html

Go:   if s == "" {}
来源：http://dali.guannengcc.top/Article/details/gtmvbncnoi.html

Ruby: if s.empty?
来源：http://dali.yvedp.cn/Article/details/gtiwyhaiyg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fzhhl.top/Article/details/gthayedvsf.html

[E21] 超长截断加省略号
来源：http://dali.svipenyu.cn/Article/details/gtxpkdjmgd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.birdmap.top/Article/details/gtxktpfikv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gteccfhtvc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gtwzfigkub.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gtqbwzcvpk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtnvatmfdq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.daria6918.cn/Article/details/gtqurehjoc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtbhzlvaei.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtawfbqxox.html

[E22] 字节长度与字符长度
来源：http://dali.yuanzhike.top/Article/details/gtzgacbizd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hnxiangtu.top/Article/details/gtnrjcchtf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gtvdswmhzk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gtnsuwfidh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gttdivuxcv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jqgfzy.top/Article/details/gtiikkmwmf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwnwkfubw.html

Ruby: s.bytesize;  s.length
来源：http://dali.jqgfzy.top/Article/details/gteullnwcf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gtwflimelc.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gthcrlozbf.html

F. 文件与目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgtzroklf.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtialxtwag.html

[F01] 读取整个文件
来源：http://dali.xuetiantiany.cn/Article/details/gtyygieddb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gaohongyu789.top/Article/details/gtmfyzalkf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtsltarxaw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fengsongda.top/Article/details/gtjjgwxblt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.smart0.xyz/Article/details/gtpczzjgvz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtuzmwpulu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.pycfn.com/Article/details/gtikthtwuw.html

Ruby: File.read("a.txt")
来源：http://dali.hammf.cn/Article/details/gtscazzicd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtlxzibrlr.html

[F02] 逐行读取文件
来源：http://dali.shzxlz.cn/Article/details/gtvelzxqoc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinghuilouyu.cn/Article/details/gtfqxwftax.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jqgufenzy.top/Article/details/gtbtlhqhpm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoyeawqvh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gtgpyxyhxb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgfzy.top/Article/details/gtmzautqnm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jqgfzy.top/Article/details/gtwqlrdpue.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.iojbl.cn/Article/details/gtpfunbwrg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tianlin.xyz/Article/details/gtxbzidzpp.html

[F03] 写入文件（覆盖）
来源：http://dali.316326.xyz/Article/details/gtqbgspplo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj20258.top/Article/details/gtprrjvqym.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sysykeji.top/Article/details/gtcclqercr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gtgrhfyfoq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hammf.cn/Article/details/gtnclrbrux.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenlongwang.top/Article/details/gtyrwbvnvt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.wangdashe.top/Article/details/gtznskkzhp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hongshengwenyu.top/Article/details/gttreaeerx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.wangdashe.top/Article/details/gtmbwslkqp.html

[F04] 追加写入文件
来源：http://dali.jianghu66.top/Article/details/gtomnspqpx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtwhbfmhwq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.meibo888.top/Article/details/gtdesepyvv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.kuanghao11.cn/Article/details/gthtnqvqaa.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pycfn.com/Article/details/gtgottunmy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.pengpengdd.cyou/Article/details/gtawcidgce.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtqxyolahv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dianchejie.cn/Article/details/gtbhukjxbo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xuanzx.com/Article/details/gtewucrzvs.html

[F05] 判断文件或目录是否存在
来源：http://dali.hysaishi.cn/Article/details/gtypekyvcs.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yongpay.top/Article/details/gthhvarqnn.html

PHP:  file_exists("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtbvjdazch.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtrzogyemo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtmnimlwky.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtrrfxwnrh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.9152youxi.cn/Article/details/gtgycxjqxh.html

Ruby: File.exist?("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtwvlrvcqg.html

C#:   File.Exists("a.txt")
来源：http://dali.tanke756.top/Article/details/gthieqyujx.html

[F06] 删除文件
来源：http://dali.jqgufenzy.top/Article/details/gtouetnpgc.html

Py:   os.remove("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtraklhfhh.html

PHP:  unlink("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtzfvjripi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gthdyqqsgg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtussnppph.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtxkikchob.html

Go:   os.Remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gthejreigk.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtxtyjjctv.html

C#:   File.Delete("a.txt");
来源：http://dali.cheryme.top/Article/details/gtfsiswjdn.html

[F07] 创建目录（含多级）
来源：http://dali.vqdsnc.cn/Article/details/gtavfqudqv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nanxuanxn.top/Article/details/gtuywznlim.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.meibo888.top/Article/details/gtqekgniqb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenzaomai.com/Article/details/gtcmvfiwdq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gtcgrqxqgk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cqqwz.cn/Article/details/gtpclkjrhe.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenlongwang.top/Article/details/gtmtinbozd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hnxiangtu.top/Article/details/gtmzbcxbpn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinghuilouyu.cn/Article/details/gthqbunudf.html

[F08] 遍历目录
来源：http://dali.cashguo.top/Article/details/gtjljctwwy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nwbrower.top/Article/details/gtpcrbvete.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.316326.xyz/Article/details/gturookbxp.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtpntgortq.html

TS:   fs.readdirSync("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtqfuqhgci.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sufxvd.cn/Article/details/gtfmbzjmbf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.316326.xyz/Article/details/gtrhncjjcp.html

Ruby: Dir.children("dir")
来源：http://dali.sweek.top/Article/details/gtjucrklip.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guowangkeji.top/Article/details/gtaoargljj.html

[F09] 获取文件大小
来源：http://dali.wangshuangyany.cn/Article/details/gtlmlofayh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gthhuengdx.html

PHP:  filesize("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gthipjitzu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.dianchejie.cn/Article/details/gtyexhrwer.html

TS:   fs.statSync("a.txt").size
来源：http://dali.wangshuangyany.cn/Article/details/gthswlqjwb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtjpuyndgm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sysykeji.top/Article/details/gtxxheuhth.html

Ruby: File.size("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtvjjghunw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj202588.top/Article/details/gtficqeopt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.andypj.xyz/Article/details/gtiwbgnnaw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gttdtsmquy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtkgqpylto.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtkifioaay.html

TS:   path.extname("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtsfgkcoec.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gogol.net.cn/Article/details/gtvqvufesv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtxuwjhknb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtwvvxgxqx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtnibhbkyf.html

[F11] 复制与移动文件
来源：http://dali.snrcjt.cn/Article/details/gtmpbruqoc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtqoacrdyp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.meibo888.top/Article/details/gtxnjedsez.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtsycxqhsp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtqdwnvzes.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gtslzhohpp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nanxuanxn.top/Article/details/gtepjrzrpk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtwtatdviw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cqqwz.cn/Article/details/gtqysjkhgz.html

[F12] CSV 读写
来源：http://dali.dianchejie.cn/Article/details/gtxhjjqhdp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sweek.top/Article/details/gtqftgszqf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tianlin.xyz/Article/details/gtbdoxtiwi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jqgufenzy.top/Article/details/gtftysmbvg.html

TS:   // 同上
来源：http://dali.cashguo.top/Article/details/gtqugdyvxg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj202588.top/Article/details/gtvfugvbco.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigufen.top/Article/details/gtjjijyxyg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sweek.top/Article/details/gtrdieuysl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sysykeji.top/Article/details/gtqqelddgy.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtoduhhrlz.html

G. 面向对象
来源：http://dali.jqgufenzy.top/Article/details/gtgcznidhh.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtapxlrlzg.html

[G01] 定义类
来源：http://dali.aizwys.cn/Article/details/gtjoiojjte.html

Py:   class User: pass
来源：http://dali.cashguo.top/Article/details/gtfuhyfutj.html

PHP:  class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlwwvbkpj.html

JS:   class User {}
来源：http://dali.zhengqikj.top/Article/details/gtjlkrgiyo.html

TS:   class User { name: string = ""; }
来源：http://dali.cucudq.cn/Article/details/gtbrnakvmz.html

Java: class User {}
来源：http://dali.nanxinkj.top/Article/details/gtvnfuibgg.html

Go:   type User struct { Name string }
来源：http://dali.chenzaomai.com/Article/details/gtuijginjz.html

Ruby: class User; end
来源：http://dali.wangdashe.top/Article/details/gtdewpemeg.html

C#:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gtmaftxbul.html

[G02] 构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtheieyfbx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtccozxbbl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cqqwz.cn/Article/details/gtipttgdsd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.316326.xyz/Article/details/gtjrsapshg.html

TS:   constructor(public name: string) {}
来源：http://dali.xinyue.icu/Article/details/gtwzsdpimu.html

Java: User(String name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gtfqwwkktp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cheryme.top/Article/details/gtgghbrwzr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cashguo.top/Article/details/gtkpkwerbu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.meibo888.top/Article/details/gtnflhvkrn.html

[G03] 实例属性
来源：http://dali.jinqigufen.top/Article/details/gtkhoxiegv.html

Py:   self.name = "x"
来源：http://dali.daxiang520.top/Article/details/gtolteppww.html

PHP:  public string $name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtqmjncsva.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtmysanpxm.html

TS:   name: string = "x";
来源：http://dali.yvedp.cn/Article/details/gtvflrrtvl.html

Java: private String name;
来源：http://dali.tianlin.xyz/Article/details/gtvnhbdeij.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.snrcjt.cn/Article/details/gtrvhipuqj.html

Ruby: @name = "x"
来源：http://dali.cucudq.cn/Article/details/gtljzxvblh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xuanzx.com/Article/details/gtwabwdits.html

[G04] 定义方法
来源：http://dali.jinqigufen.top/Article/details/gtrltxrnpa.html

Py:   def greet(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gtzrwrydoc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gtlofkbfwp.html

JS:   greet() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtcsxxjroz.html

TS:   greet(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtkfuimyqc.html

Java: String greet() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtsefhmqhi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gtirviongd.html

Ruby: def greet; @name; end
来源：http://dali.andypj.xyz/Article/details/gtzivcltrg.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwboeobu.html

[G05] 继承
来源：http://dali.tianlin.xyz/Article/details/gttpmtfalp.html

Py:   class Admin(User): pass
来源：http://dali.tian-w.cn/Article/details/gtehbgjblo.html

PHP:  class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtwvqlhqtm.html

JS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtjbzwxuml.html

TS:   class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtqyyebijb.html

Java: class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtmfhdguap.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.daxiang520.top/Article/details/gtebrqeqqj.html

Ruby: class Admin < User; end
来源：http://dali.iojbl.cn/Article/details/gtbtoqhfvp.html

C#:   class Admin : User {}
来源：http://dali.hfpthk.cn/Article/details/gtramnrqna.html

[G06] 重写方法
来源：http://dali.wangshuangyany.cn/Article/details/gthxoxglvg.html

Py:   def greet(self): return "admin"
来源：http://dali.jlsjyb.cn/Article/details/gtjflxakaz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gttpxzhist.html

JS:   greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtzuirxwjx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtaehyequw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtlrexjbdb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnqzz.top/Article/details/gtacmbbvwb.html

Ruby: def greet; "admin"; end
来源：http://dali.zhixingplan.top/Article/details/gtlchmuuje.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhongyouzk.top/Article/details/gtctkbxovy.html

[G07] 调用父类方法
来源：http://dali.haohaochexian.top/Article/details/gtoeomwwgu.html

Py:   super().greet()
来源：http://dali.xylfe.cn/Article/details/gthrmwzjlv.html

PHP:  parent::greet();
来源：http://dali.jqgufenzy.top/Article/details/gtlfbpnarg.html

JS:   super.greet();
来源：http://dali.andypj.xyz/Article/details/gtolalywrs.html

TS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gtqcgcouug.html

Java: super.greet();
来源：http://dali.yuxming.cn/Article/details/gtzmrzrhfg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.wangdashe.top/Article/details/gtoqjhyxcj.html

Ruby: super
来源：http://dali.wangdashe.top/Article/details/gtzscwgsaq.html

C#:   base.Greet();
来源：http://dali.jqgufenzy.top/Article/details/gtowplfsxe.html

[G08] 静态方法与属性
来源：http://dali.chenzaomai.com/Article/details/gtkoyudbbe.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yvedp.cn/Article/details/gtpbwatbit.html

PHP:  public static function f() {}
来源：http://dali.cucudq.cn/Article/details/gtwdpwfewd.html

JS:   static f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtyheznbmj.html

TS:   static f(): void {}
来源：http://dali.hnqzz.top/Article/details/gtrpfcesnb.html

Java: static void f() {}
来源：http://dali.shzxlz.cn/Article/details/gtxcbymkbi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cashguo.top/Article/details/gtngtbfcxb.html

Ruby: def self.f; end
来源：http://dali.haohaochexian.top/Article/details/gtohszdhhe.html

C#:   public static void F() {}
来源：http://dali.dianchejie.cn/Article/details/gtnwzgkfvg.html

[G09] 接口 / 抽象类
来源：http://dali.yangfankeji.com/Article/details/gtuoenhiob.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj202588.top/Article/details/gtacrtpzdq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gogol.net.cn/Article/details/gtwlvyijtu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhengqikj.top/Article/details/gtsadicybp.html

TS:   interface Shape { area(): number; }
来源：http://dali.ydzc1.top/Article/details/gtuhcuosfd.html

Java: interface Shape { double area(); }
来源：http://dali.haohaochexian.top/Article/details/gtmpnfmapv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuanzx.com/Article/details/gtzanxsadk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.316326.xyz/Article/details/gtnjmnaykz.html

C#:   interface IShape { double Area(); }
来源：http://dali.smart0.xyz/Article/details/gtzyziodmi.html

[G10] 访问控制
来源：http://dali.andypj.xyz/Article/details/gtztmqrosu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.quarkkingdee.top/Article/details/gtrynqevwf.html

PHP:  public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtftaxnwku.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigfzy.top/Article/details/gtbrzgvxzn.html

TS:   public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtdwkbtakh.html

Java: public / protected / private / 默认包级
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbfyyeqx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.0kj1m.cn/Article/details/gtyupajwcd.html

Ruby: public / protected / private
来源：http://dali.daxiang520.top/Article/details/gtxbxfrpnx.html

C#:   public / protected / private / internal
来源：http://dali.shuidangran.top/Article/details/gtsdizmgex.html

[G11] getter / setter
来源：http://dali.ppjwa.cn/Article/details/gtmsdzyjsy.html

Py:   @property 与 @x.setter
来源：http://dali.ydzc1.top/Article/details/gtusnjkgrv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtqyaeirvk.html

JS:   get name() { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqbfqmmh.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gtjuxiswaj.html

Java: public String getName() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtmfmqycrf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gtdaqcwfff.html

Ruby: attr_accessor :name
来源：http://dali.iojbl.cn/Article/details/gtkatcailr.html

C#:   public string Name { get; set; }
来源：http://dali.svipenyu.cn/Article/details/gtkonmrohw.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtksdyazxr.html

Py:   def __str__(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gtqtcxpwbc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtzbaylljz.html

JS:   toString() { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtmycuriyn.html

TS:   toString(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtklbaghnm.html

Java: @Override public String toString() { return name; }
来源：http://dali.hammf.cn/Article/details/gtekmcgxzn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtyovqceda.html

Ruby: def to_s; @name; end
来源：http://dali.cdnleiting.top/Article/details/gtethfcqxi.html

C#:   public override string ToString() => Name;
来源：http://dali.hywenlv.cn/Article/details/gtqgpdsrmg.html

[G13] 判断对象类型
来源：http://dali.xuanzx.com/Article/details/gtsllaeaff.html

Py:   isinstance(u, User)
来源：http://dali.fengsongda.top/Article/details/gtacrfbxag.html

PHP:  $u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtatpqdgxc.html

JS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtxxabruhi.html

TS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtealjchir.html

Java: u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtsckexfke.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aibaodan.cn/Article/details/gttulrjoqq.html

Ruby: u.is_a?(User)
来源：http://dali.yonumen.top/Article/details/gtzyyyjlzz.html

C#:   u is User
来源：http://dali.tanke756.top/Article/details/gtwyoxihkp.html

[G14] 数据类 / record
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdcaffbvk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shzxlz.cn/Article/details/gtzupajzgz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tian-w.cn/Article/details/gtnorujuyz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hammf.cn/Article/details/gtwicgopnr.html

TS:   type User = { name: string; age: number };
来源：http://dali.wangshuangyany.cn/Article/details/gtmeonucmq.html

Java: record User(String name, int age) {}
来源：http://dali.jinqigufen.top/Article/details/gtjtgmlpwj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cashguo.top/Article/details/gtatldktyw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnqzz.top/Article/details/gtexvhlcwn.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258.top/Article/details/gtrkbeqbot.html

[G15] 枚举
来源：http://dali.cdnleiting.top/Article/details/gtxkerwavb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.0kj1m.cn/Article/details/gtgbdrvjwo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.aizwys.cn/Article/details/gtbbwpdbwm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgfzy.top/Article/details/gttgwscivm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hammf.cn/Article/details/gtzmaqwyoc.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangshuangyany.cn/Article/details/gtjnpslsbe.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hfpthk.cn/Article/details/gtswbeeeub.html

Ruby: Color = %i[red green].freeze
来源：http://dali.iojbl.cn/Article/details/gtslblnxww.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gtsnmmpbec.html

[G16] 对象转数组 / 字典
来源：http://dali.yvedp.cn/Article/details/gtbfcjreso.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.snrcjt.cn/Article/details/gtynchlnie.html

PHP:  get_object_vars($obj);
来源：http://dali.chenlongwang.top/Article/details/gtweqwweng.html

JS:   Object.entries(obj)
来源：http://dali.zhengqikj.top/Article/details/gtzdilntee.html

TS:   Object.entries(obj)
来源：http://dali.ydzc1.top/Article/details/gtgfteaijq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.smart0.xyz/Article/details/gtdsjoukhq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hywenlv.cn/Article/details/gtsuxxkrze.html

Ruby: obj.instance_variables
来源：http://dali.cashguo.top/Article/details/gtqimfevug.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gtorefppxr.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gthwhmqwly.html

H. 异常与错误处理
来源：http://dali.daria6918.cn/Article/details/gtcepdsyru.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtpocumjuz.html

[H01] try / catch 基础
来源：http://dali.pengpengdd.cyou/Article/details/gtmxzavjpj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nwbrower.top/Article/details/gtaulgwbfb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtccntnujg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gtsvhxbium.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtdcubssiw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuetiantiany.cn/Article/details/gtrbbsfyvn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yonumen.top/Article/details/gththrthxq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.havefunace.top/Article/details/gtlhmcmkip.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sysykeji.top/Article/details/gtxyaofzeh.html

[H02] finally / ensure 收尾
来源：http://dali.cqqwz.cn/Article/details/gtbvfzskkr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.kuanghao11.cn/Article/details/gtzjajpqbm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtgfndygpl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtvhgzcciw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtokoaaian.html


<!-- 参考信息 -->