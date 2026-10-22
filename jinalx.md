代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlofcdbox.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtvehnfiwb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gttmzlkqmi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gaohongyu789.top/Article/details/gtbiyffgeh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.wangshuangyany.cn/Article/details/gtleufelge.html

[E19] 多行文本按行拆分
来源：http://dali.xuetiantiany.cn/Article/details/gttflnpvzz.html

Py:   s.splitlines()
来源：http://dali.nanxuanxn.top/Article/details/gtkuazrqjh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yueranfly.top/Article/details/gtavtxvehr.html

JS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gtpfgojwoo.html

TS:   s.split(/\r?\n/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyarmjfsa.html

Java: s.lines().toList()
来源：http://dali.xuanzx.com/Article/details/gtqbsjstto.html

Go:   strings.Split(s, "\n")
来源：http://dali.aibaodan.cn/Article/details/gtzioacycs.html

Ruby: s.lines
来源：http://dali.gaohongyu789.top/Article/details/gthnrretdj.html

C#:   s.Split('\n')
来源：http://dali.nanxinkj.top/Article/details/gtukrirpho.html

[E20] 判断字符串是否为空
来源：http://dali.9152youxi.cn/Article/details/gteiggphkr.html

Py:   if not s:
来源：http://dali.dashuyun.cn/Article/details/gtpplhpkxl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.haohaochexian.top/Article/details/gtvorzckov.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yonumen.top/Article/details/gtvgbsdozp.html

TS:   if (s === "") {}
来源：http://dali.yuxming.cn/Article/details/gtakancjjg.html

Java: if (s.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gtcunjbuqb.html

Go:   if s == "" {}
来源：http://dali.jyoumei.cn/Article/details/gtdfghoxkh.html

Ruby: if s.empty?
来源：http://dali.xuanzx.com/Article/details/gtmqginhqe.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvplitfb.html

[E21] 超长截断加省略号
来源：http://dali.yonumen.top/Article/details/gtfqgrlvxi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xinyue.icu/Article/details/gtuxyybrxf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gtojmovodc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtfbvldlqf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtqtafnong.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtucsdqrud.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenjidiqi.icu/Article/details/gtqfacomwg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtfpuvynbq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gtoorzjymj.html

[E22] 字节长度与字符长度
来源：http://dali.316326.xyz/Article/details/gtduywwxxi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.fzhhl.top/Article/details/gtrafnfwlc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gttjcyvjaq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gzhubu.top/Article/details/gtuenzkhcn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tanke756.top/Article/details/gtvsogosus.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj20258888.top/Article/details/gtffbxshjv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.wangdashe.top/Article/details/gtdpwttlxm.html

Ruby: s.bytesize;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gtkzsvzaln.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhoulong.xyz/Article/details/gteblwgvkg.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtmwiydygb.html

F. 文件与目录
来源：http://dali.yonumen.top/Article/details/gtcdxppyya.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtllutxave.html

[F01] 读取整个文件
来源：http://dali.xylfe.cn/Article/details/gtaguixklt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.vqdsnc.cn/Article/details/gtaisqhhnu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtgswiyjkl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.daria6918.cn/Article/details/gtauphmcqt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yongpay.top/Article/details/gtbzopgsgs.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtayanzeud.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.guannengcc.top/Article/details/gtoezuyeol.html

Ruby: File.read("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtqwxujaoz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtzfmzurgd.html

[F02] 逐行读取文件
来源：http://dali.hysaishi.cn/Article/details/gtnsvqhjqr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.meibo888.top/Article/details/gtegbhjpdr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jqgufenzy.top/Article/details/gtemsqlogn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gtlyitddqq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuanzx.com/Article/details/gternadcsm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ybcxt.top/Article/details/gtmyqekktp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hywenlv.cn/Article/details/gtfwieojjb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gogol.net.cn/Article/details/gtnhsspsci.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shzxlz.cn/Article/details/gtayqlqzzc.html

[F03] 写入文件（覆盖）
来源：http://dali.jinqigfzy.top/Article/details/gtfozbzery.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tianlin.xyz/Article/details/gthyjmgotq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xylfe.cn/Article/details/gtvmqhuoqx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtikycqbvg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.bjfxy.top/Article/details/gtekhzixnw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cdnleiting.top/Article/details/gtdqrvcoey.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenzaomai.com/Article/details/gtvdzvsgsb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.svipenyu.cn/Article/details/gtyihjvufs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guannengcc.top/Article/details/gteelxcccy.html

[F04] 追加写入文件
来源：http://dali.hfpthk.cn/Article/details/gtgnxpacrw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.iojbl.cn/Article/details/gtyelwudco.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gotoacloud.top/Article/details/gtjnksjtad.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gttdowmqzo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangdashe.top/Article/details/gtnvjhhabw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhongyouzk.top/Article/details/gthpoggevw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.fzhhl.top/Article/details/gttvirgyox.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tanke756.top/Article/details/gtichmtxqu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gaohongyu789.top/Article/details/gtmgybhduw.html

[F05] 判断文件或目录是否存在
来源：http://dali.vqdsnc.cn/Article/details/gtlqkfhgoc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jlsjyb.cn/Article/details/gteqrdntel.html

PHP:  file_exists("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtnmmwvfql.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtpdgvvgkw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtrghptpua.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtmizvzksp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinqigfzy.top/Article/details/gtrzasaxjb.html

Ruby: File.exist?("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtkcgfqswi.html

C#:   File.Exists("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtijssjxwc.html

[F06] 删除文件
来源：http://dali.gzhubu.top/Article/details/gthnoopgfv.html

Py:   os.remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthqvcgcab.html

PHP:  unlink("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtugviobdg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtabcrgcwr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gthsfuqsgw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtcrbfhgwv.html

Go:   os.Remove("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtnvbornju.html

Ruby: File.delete("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtqgahphcp.html

C#:   File.Delete("a.txt");
来源：http://dali.yj20258.top/Article/details/gtkfcywiqz.html

[F07] 创建目录（含多级）
来源：http://dali.hnqzz.top/Article/details/gtelsrlvxw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.smart0.xyz/Article/details/gthjxbqrmp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtpcwqdqcm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhongyouzk.top/Article/details/gtuopwkqry.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gtrhcpkzkm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.daxiang520.top/Article/details/gthhrhqsrt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nanxuanxn.top/Article/details/gtnolckczl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj20258888.top/Article/details/gtituhwllm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgufenzy.top/Article/details/gtdugkbkih.html

[F08] 遍历目录
来源：http://dali.fengsongda.top/Article/details/gtslbmvxen.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.havefunace.top/Article/details/gtdzwrtbgg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigfzy.top/Article/details/gtaztoqfly.html

JS:   fs.readdirSync("dir")
来源：http://dali.yuxming.cn/Article/details/gtkezopiab.html

TS:   fs.readdirSync("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtmrhnvjlw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxuanxn.top/Article/details/gtwjwrpjed.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtygllbwrt.html

Ruby: Dir.children("dir")
来源：http://dali.guannengcc.top/Article/details/gtzjosugwx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xziqi.cn/Article/details/gtxzygzbbs.html

[F09] 获取文件大小
来源：http://dali.ivvv.top/Article/details/gtrjvwutfh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtcwyeecrg.html

PHP:  filesize("a.txt");
来源：http://dali.ydzc1.top/Article/details/gthrcoeipq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.316326.xyz/Article/details/gtbrrglkjh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.svipenyu.cn/Article/details/gthwffanij.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtlxrniwvl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yangfankeji.com/Article/details/gtuhbabuzc.html

Ruby: File.size("a.txt")
来源：http://dali.cheryme.top/Article/details/gtaexwwtit.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jlsjyb.cn/Article/details/gtwlbrolui.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgfzy.top/Article/details/gtdbkhswnc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtwmyrzoxx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.havefunace.top/Article/details/gtscazjjiv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtiwhrzlmv.html

TS:   path.extname("a.txt")
来源：http://dali.ivvv.top/Article/details/gthgrsgjth.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guannengcc.top/Article/details/gtjushtgho.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtnfbleaxj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtrmprhyeb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtjpyffhhi.html

[F11] 复制与移动文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmcsemwwa.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtmvuojeyn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xuanzx.com/Article/details/gtchotroua.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtnjpfeivg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gtpelvlpqb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.bjfxy.top/Article/details/gtbnhlipji.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ivvv.top/Article/details/gtofppnzqs.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtwuuqxxny.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shzxlz.cn/Article/details/gtnagkdvbb.html

[F12] CSV 读写
来源：http://dali.fzhhl.top/Article/details/gtivqgdepg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zycfv.cn/Article/details/gtupyldffu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gzhubu.top/Article/details/gtjpkagfnc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sufxvd.cn/Article/details/gtfxwsvlgo.html

TS:   // 同上
来源：http://dali.hammf.cn/Article/details/gthkkbsfjm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.redwolf501.top/Article/details/gtwvowlmjr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cheryme.top/Article/details/gtozqlakai.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yuanzhike.top/Article/details/gtbrlabxep.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtosufbado.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtlposvswm.html

G. 面向对象
来源：http://dali.havefunace.top/Article/details/gtzlfpgqor.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtyzgneuhv.html

[G01] 定义类
来源：http://dali.dianchejie.cn/Article/details/gtnswwsklx.html

Py:   class User: pass
来源：http://dali.daxiang520.top/Article/details/gtilsxnroy.html

PHP:  class User {}
来源：http://dali.nanxinkj.top/Article/details/gtnymexnfc.html

JS:   class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxcpilndo.html

TS:   class User { name: string = ""; }
来源：http://dali.ybcxt.top/Article/details/gtrbdcwmfk.html

Java: class User {}
来源：http://dali.ybcxt.top/Article/details/gtnixmkzad.html

Go:   type User struct { Name string }
来源：http://dali.meibo888.top/Article/details/gtgodmvtjc.html

Ruby: class User; end
来源：http://dali.fengsongda.top/Article/details/gtzkthbzwc.html

C#:   class User {}
来源：http://dali.shuidangran.top/Article/details/gtwuljkaae.html

[G02] 构造函数
来源：http://dali.aibaodan.cn/Article/details/gtarvzjoeu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xziqi.cn/Article/details/gtaimvmmeg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.meibo888.top/Article/details/gtxnniftjt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yuanzhike.top/Article/details/gtaonhuahj.html

TS:   constructor(public name: string) {}
来源：http://dali.quarkkingdee.top/Article/details/gthbgsupkg.html

Java: User(String name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gtjfqfrrnh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cucudq.cn/Article/details/gtbmbwztxx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258.top/Article/details/gtqmizajlo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tianlin.xyz/Article/details/gtdndcfeqm.html

[G03] 实例属性
来源：http://dali.nanxinkj.top/Article/details/gtmzsjpqwo.html

Py:   self.name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gtfgginqek.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlduhzsie.html

JS:   this.name = "x";
来源：http://dali.sufxvd.cn/Article/details/gtgpqxambo.html

TS:   name: string = "x";
来源：http://dali.sxryk.cn/Article/details/gtyxbkwgve.html

Java: private String name;
来源：http://dali.cqqwz.cn/Article/details/gtpuczpywv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daxiang520.top/Article/details/gtqtkszbij.html

Ruby: @name = "x"
来源：http://dali.hnxiangtu.top/Article/details/gtrpxaokfq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.316326.xyz/Article/details/gtwmvzrsyj.html

[G04] 定义方法
来源：http://dali.tian-w.cn/Article/details/gtrgdewivv.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmyddzazf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtfkjrvepo.html

JS:   greet() { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtheehhkhl.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtljrrkhqr.html

Java: String greet() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtomworxsp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gtovzvvliu.html

Ruby: def greet; @name; end
来源：http://dali.gzhubu.top/Article/details/gtupfkxchb.html

C#:   public string Greet() => Name;
来源：http://dali.yangfankeji.com/Article/details/gtsfcauxqg.html

[G05] 继承
来源：http://dali.sweek.top/Article/details/gtixujgsrd.html

Py:   class Admin(User): pass
来源：http://dali.jyoumei.cn/Article/details/gtcqnfdswf.html

PHP:  class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtabtwhrmw.html

JS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtmbdiotjz.html

TS:   class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtenzprrxv.html

Java: class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtvqevsqjx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hfpthk.cn/Article/details/gtcugpobyq.html

Ruby: class Admin < User; end
来源：http://dali.pycfn.com/Article/details/gtogjilvoq.html

C#:   class Admin : User {}
来源：http://dali.pycfn.com/Article/details/gtqwpmwklp.html

[G06] 重写方法
来源：http://dali.zhengqikj.top/Article/details/gtibfzsdee.html

Py:   def greet(self): return "admin"
来源：http://dali.yangfankeji.com/Article/details/gtwgubfztr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtusslxkhi.html

JS:   greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtzpiiaowc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gthllamqzh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtdpdclxwm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinghuilouyu.cn/Article/details/gtonxsdhwg.html

Ruby: def greet; "admin"; end
来源：http://dali.yueranfly.top/Article/details/gtwronqbde.html

C#:   public override string Greet() => "admin";
来源：http://dali.xziqi.cn/Article/details/gtxtyyhabb.html

[G07] 调用父类方法
来源：http://dali.c1oappe.top/Article/details/gtodkwphxy.html

Py:   super().greet()
来源：http://dali.cqqwz.cn/Article/details/gtfuxodoti.html

PHP:  parent::greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtctkgtrlk.html

JS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gtxlncskmr.html

TS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gtcndulwau.html

Java: super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtottikxsj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yvedp.cn/Article/details/gtcxkdylde.html

Ruby: super
来源：http://dali.xinyue.icu/Article/details/gtdspatbdx.html

C#:   base.Greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtfshmfxyj.html

[G08] 静态方法与属性
来源：http://dali.dianchejie.cn/Article/details/gtimkksyrh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ybcxt.top/Article/details/gtgqahldsk.html

PHP:  public static function f() {}
来源：http://dali.birdmap.top/Article/details/gtptzwxtfk.html

JS:   static f() {}
来源：http://dali.cheryme.top/Article/details/gtmssexnwz.html

TS:   static f(): void {}
来源：http://dali.jyoumei.cn/Article/details/gtmwvrsfsy.html

Java: static void f() {}
来源：http://dali.redwolf501.top/Article/details/gtxbfxzjcq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.c1oappe.top/Article/details/gtipzmqulz.html

Ruby: def self.f; end
来源：http://dali.jyoumei.cn/Article/details/gtpaimxzkn.html

C#:   public static void F() {}
来源：http://dali.yangfankeji.com/Article/details/gtoesirgws.html

[G09] 接口 / 抽象类
来源：http://dali.bjfxy.top/Article/details/gtoagmzxim.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.haohaochexian.top/Article/details/gturbavsol.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sweek.top/Article/details/gtnctnbqgz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hongshengwenyu.top/Article/details/gtolvmqobf.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenzaomai.com/Article/details/gtlkkpxojl.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258.top/Article/details/gtrthoaeqb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigufen.top/Article/details/gtdsswtcvt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnxiangtu.top/Article/details/gtnjyheojj.html

C#:   interface IShape { double Area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtuiwndedz.html

[G10] 访问控制
来源：http://dali.xuanzx.com/Article/details/gtggqgpwyz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258888.top/Article/details/gtlfcarvxy.html

PHP:  public / protected / private
来源：http://dali.hnqzz.top/Article/details/gtdkmclxoe.html

JS:   #private 字段；其余公开
来源：http://dali.pengpengdd.cyou/Article/details/gtigvpfels.html

TS:   public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gtpkwlpkvg.html

Java: public / protected / private / 默认包级
来源：http://dali.xinyue.icu/Article/details/gtayfrwdjn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fengsongda.top/Article/details/gtgctapbud.html

Ruby: public / protected / private
来源：http://dali.cheryme.top/Article/details/gtjmgyipow.html

C#:   public / protected / private / internal
来源：http://dali.xinyue.icu/Article/details/gthvimydse.html

[G11] getter / setter
来源：http://dali.hnqzz.top/Article/details/gtripjorul.html

Py:   @property 与 @x.setter
来源：http://dali.yongpay.top/Article/details/gtlxlfpemx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtnwdgbhxj.html

JS:   get name() { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gteunwpgzu.html

TS:   get name(): string { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gtzapbjhsz.html

Java: public String getName() { return name; }
来源：http://dali.jianghu66.top/Article/details/gtcubahwcr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gtfuqfktrp.html

Ruby: attr_accessor :name
来源：http://dali.cucudq.cn/Article/details/gtubgrduww.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqgtooys.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxonluav.html

Py:   def __str__(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gtghcmkfel.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gttqnrwdry.html

JS:   toString() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtojsmstva.html

TS:   toString(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtyyzphejw.html

Java: @Override public String toString() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtsprameeo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtfdnqszzy.html

Ruby: def to_s; @name; end
来源：http://dali.iojbl.cn/Article/details/gtlbrglndh.html

C#:   public override string ToString() => Name;
来源：http://dali.mhx1999.top/Article/details/gtgsamxolp.html

[G13] 判断对象类型
来源：http://dali.sweek.top/Article/details/gtbhdzxstf.html

Py:   isinstance(u, User)
来源：http://dali.andypj.xyz/Article/details/gtxsefujsd.html

PHP:  $u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtxqwjkfjz.html

JS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtmlbzingo.html

TS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gtyfbsfnab.html

Java: u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtpfvvpiur.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.smart0.xyz/Article/details/gtvtxivsrr.html

Ruby: u.is_a?(User)
来源：http://dali.feifeiyinyue.top/Article/details/gtrmioxrlz.html

C#:   u is User
来源：http://dali.yuxming.cn/Article/details/gtwclivhjd.html

[G14] 数据类 / record
来源：http://dali.guowangkeji.top/Article/details/gtwlhvnovc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxinkj.top/Article/details/gtuntlvult.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.daxiang520.top/Article/details/gttwsgaoom.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.aibaodan.cn/Article/details/gttabnfgak.html

TS:   type User = { name: string; age: number };
来源：http://dali.cqqwz.cn/Article/details/gtzjxzlboz.html

Java: record User(String name, int age) {}
来源：http://dali.havefunace.top/Article/details/gtwjosktyi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpjhqsoqy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yvedp.cn/Article/details/gtpoyjoyly.html

C#:   record User(string Name, int Age);
来源：http://dali.zycfv.cn/Article/details/gtakyjaidd.html

[G15] 枚举
来源：http://dali.tianlin.xyz/Article/details/gtlmayhotu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yueranfly.top/Article/details/gtkmcsiill.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ppjwa.cn/Article/details/gtiadpytvp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgufenzy.top/Article/details/gtnkqfuesz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gtkrqyzavy.html

Java: enum Color { RED, GREEN }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttvorezhj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ppjwa.cn/Article/details/gtpvfzawcu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.dashuyun.cn/Article/details/gtwhliruim.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gtobvfvwdl.html

[G16] 对象转数组 / 字典
来源：http://dali.sysykeji.top/Article/details/gtcxwnbjde.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sweek.top/Article/details/gtzdfdmcmt.html

PHP:  get_object_vars($obj);
来源：http://dali.gotoacloud.top/Article/details/gtzfjulgsu.html

JS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtnthcsxep.html

TS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkjjcagvm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.mhx1999.top/Article/details/gtrdahlayw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.c1oappe.top/Article/details/gtnddjugfa.html

Ruby: obj.instance_variables
来源：http://dali.zhongyouzk.top/Article/details/gtikniejtd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sxryk.cn/Article/details/gtxfqznkuv.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtqdafhgii.html


<!-- 参考信息 -->