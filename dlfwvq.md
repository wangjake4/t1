代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yangfankeji.com/Article/details/gtuxzjjmxs.html

[E19] 多行文本按行拆分
来源：http://dali.shangyingyoupin.top/Article/details/gtcgfjyoze.html

Py:   s.splitlines()
来源：http://dali.jinghuilouyu.cn/Article/details/gtwuvzfpjj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.316326.xyz/Article/details/gtsezhfsgk.html

JS:   s.split(/\r?\n/)
来源：http://dali.yonumen.top/Article/details/gtlybcytpc.html

TS:   s.split(/\r?\n/)
来源：http://dali.fzhhl.top/Article/details/gtmlczalmq.html

Java: s.lines().toList()
来源：http://dali.zdqjudy.top/Article/details/gtwinupkxy.html

Go:   strings.Split(s, "\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtycznemss.html

Ruby: s.lines
来源：http://dali.guannengcc.top/Article/details/gtnmqfambv.html

C#:   s.Split('\n')
来源：http://dali.xziqi.cn/Article/details/gtulmbvvgj.html

[E20] 判断字符串是否为空
来源：http://dali.sufxvd.cn/Article/details/gtcdmbtvbb.html

Py:   if not s:
来源：http://dali.hysaishi.cn/Article/details/gtvxmxnntz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nanxinkj.top/Article/details/gtrdtxjspj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ivvv.top/Article/details/gtnsuamcho.html

TS:   if (s === "") {}
来源：http://dali.ivvv.top/Article/details/gtrhlyagkn.html

Java: if (s.isEmpty()) {}
来源：http://dali.cqqwz.cn/Article/details/gtcyrmwnga.html

Go:   if s == "" {}
来源：http://dali.gaohongyu789.top/Article/details/gtfqprtlib.html

Ruby: if s.empty?
来源：http://dali.gaohongyu789.top/Article/details/gtcqznfgae.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jianghu66.top/Article/details/gtlqlmpmnl.html

[E21] 超长截断加省略号
来源：http://dali.sweek.top/Article/details/gtzufaavjv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pengpengdd.cyou/Article/details/gtfnbudgeu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtexwugafk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtcvkwgyyv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtxtmfyaes.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkeqwgxkc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hammf.cn/Article/details/gtvjxzkfsg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtdtundduy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtbvzsspdn.html

[E22] 字节长度与字符长度
来源：http://dali.yuxming.cn/Article/details/gtqfhherjc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tanke756.top/Article/details/gtkgxsudmb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gtcwrmaagp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yvedp.cn/Article/details/gtfikvjiex.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gtjhntcwww.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ehwqpu.com/Article/details/gtvuouazwt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.guowangkeji.top/Article/details/gtxpyeobig.html

Ruby: s.bytesize;  s.length
来源：http://dali.zdqjudy.top/Article/details/gtjuhysaeq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.daxiang520.top/Article/details/gtobeesfru.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtdvhazmse.html

F. 文件与目录
来源：http://dali.chenjidiqi.icu/Article/details/gtoiloybvy.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtocugwrsl.html

[F01] 读取整个文件
来源：http://dali.vqdsnc.cn/Article/details/gttzkujyts.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhengqikj.top/Article/details/gthcjqqtlx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtsftiksyo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tian-w.cn/Article/details/gteppdqqeb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.c1oappe.top/Article/details/gtbftdbnvg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gttnuzaygt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.c1oappe.top/Article/details/gtttbibmzb.html

Ruby: File.read("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtphdyfgnz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqefwbbv.html

[F02] 逐行读取文件
来源：http://dali.hysaishi.cn/Article/details/gtcjkmdsay.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dianchejie.cn/Article/details/gtoviddovs.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aizwys.cn/Article/details/gtliwcfogg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cheryme.top/Article/details/gtqqfvbohi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ydzc1.top/Article/details/gtiyyxkrtb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gtxnirfnkq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xylfe.cn/Article/details/gtwcgumvhq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yueranfly.top/Article/details/gtuxogpzlt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxptilmuz.html

[F03] 写入文件（覆盖）
来源：http://dali.pycfn.com/Article/details/gtimnnfkaw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.vqdsnc.cn/Article/details/gtcmvxipxf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gthtxhcmwf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gtmqofegob.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkgmavggd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tianlin.xyz/Article/details/gtrsjtmfss.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmbimesic.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidglxhyi.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gzhubu.top/Article/details/gthnybonwk.html

[F04] 追加写入文件
来源：http://dali.yj202588.top/Article/details/gtprkbwqqi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fengsongda.top/Article/details/gtdofnrmmo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.birdmap.top/Article/details/gtncjnuqcz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtqrbksujg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gtgiwaxvyb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.daxiang520.top/Article/details/gtissusoos.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.c1oappe.top/Article/details/gtieusclij.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.aizwys.cn/Article/details/gtzxlngbuo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nanxuanxn.top/Article/details/gteyxwgqxu.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjhzffci.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yvedp.cn/Article/details/gtntvjryza.html

PHP:  file_exists("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtbjpiynkn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtxablsulp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtjlrkfrbb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtpvndopcc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yvedp.cn/Article/details/gttbusqfjy.html

Ruby: File.exist?("a.txt")
来源：http://dali.xziqi.cn/Article/details/gteavmjoev.html

C#:   File.Exists("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtpwhckidr.html

[F06] 删除文件
来源：http://dali.hfpthk.cn/Article/details/gtwmyzczrj.html

Py:   os.remove("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtswapbgts.html

PHP:  unlink("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtmvuqmsoi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtdfhpsnre.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtrtxlhrca.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gtxwcmsdrd.html

Go:   os.Remove("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtjoeuqcmm.html

Ruby: File.delete("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwrtxfkh.html

C#:   File.Delete("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtrallgcge.html

[F07] 创建目录（含多级）
来源：http://dali.gogol.net.cn/Article/details/gtxfcqtowu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cashguo.top/Article/details/gtgqcmxvke.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ivvv.top/Article/details/gtyovqcuno.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gtbbhauxhc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnqzz.top/Article/details/gtmxnpbzmj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pycfn.com/Article/details/gtiyidncgj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.svipenyu.cn/Article/details/gtqsghlcax.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hnqzz.top/Article/details/gtfepslkkv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yueranfly.top/Article/details/gtlcfeanjb.html

[F08] 遍历目录
来源：http://dali.316326.xyz/Article/details/gtdycmmiep.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj20258888.top/Article/details/gtlkcmpqvd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.andypj.xyz/Article/details/gtxpxvwypb.html

JS:   fs.readdirSync("dir")
来源：http://dali.daria6918.cn/Article/details/gtdzzjpbqv.html

TS:   fs.readdirSync("dir")
来源：http://dali.pycfn.com/Article/details/gtvzopzhvs.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jyoumei.cn/Article/details/gthgcglaee.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ydzc1.top/Article/details/gtmjkkaezj.html

Ruby: Dir.children("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtiwthrcnz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cqqwz.cn/Article/details/gtijmrhpjd.html

[F09] 获取文件大小
来源：http://dali.gzhubu.top/Article/details/gtjlxjziev.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtmtnefrti.html

PHP:  filesize("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtzlsmndkk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tianlin.xyz/Article/details/gtzvzwuxpq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj20258888.top/Article/details/gtwotbscrb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtnpgvkbbl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenjidiqi.icu/Article/details/gtwdckfvyz.html

Ruby: File.size("a.txt")
来源：http://dali.pycfn.com/Article/details/gtzufksbhu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinqigfzy.top/Article/details/gtekdypzsr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvyfyflqd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtzledndbx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yuanzhike.top/Article/details/gttvkldrqq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtpngvdphz.html

TS:   path.extname("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtvvbweocj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hywenlv.cn/Article/details/gtcmbkdwtn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtgmjytuwb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtpochznyh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtsptcaygu.html

[F11] 复制与移动文件
来源：http://dali.zdqjudy.top/Article/details/gtqppwpfvh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtoachirte.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenlongwang.top/Article/details/gtpskiuquv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbfubbhvw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtxajnunhh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gtouodkobq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.dashuyun.cn/Article/details/gtlcboecws.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtcerzgysa.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tianlin.xyz/Article/details/gtytuuquyo.html

[F12] CSV 读写
来源：http://dali.mhx1999.top/Article/details/gtifuzdkro.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhiwuduotai.top/Article/details/gtcmiqvqzj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhoulong.xyz/Article/details/gtosrhliuh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sxryk.cn/Article/details/gtwemgtsgv.html

TS:   // 同上
来源：http://dali.yvedp.cn/Article/details/gtynghyhxk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jlsjyb.cn/Article/details/gtrpharnwk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhaomingkeji.xyz/Article/details/gtspnqtpkk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj20258.top/Article/details/gtjoabredv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hammf.cn/Article/details/gtzqelqkjj.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtcbxosfnq.html

G. 面向对象
来源：http://dali.shzxlz.cn/Article/details/gtuacgsgxp.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtacuuqdkn.html

[G01] 定义类
来源：http://dali.vqdsnc.cn/Article/details/gtotqxeafy.html

Py:   class User: pass
来源：http://dali.tianlin.xyz/Article/details/gtqjkcidtt.html

PHP:  class User {}
来源：http://dali.zhixingplan.top/Article/details/gtayjeyzmo.html

JS:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtuzzyivhf.html

TS:   class User { name: string = ""; }
来源：http://dali.yvedp.cn/Article/details/gteisnxuwc.html

Java: class User {}
来源：http://dali.smart0.xyz/Article/details/gtbcopepul.html

Go:   type User struct { Name string }
来源：http://dali.yanxiufei.cn/Article/details/gtldfipwum.html

Ruby: class User; end
来源：http://dali.yongpay.top/Article/details/gtauigvgmh.html

C#:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtgwtuncel.html

[G02] 构造函数
来源：http://dali.gzhubu.top/Article/details/gtsstqdddt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zycfv.cn/Article/details/gtqkzrxlcj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.wangdashe.top/Article/details/gtkqpxngnd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gtaodoprpo.html

TS:   constructor(public name: string) {}
来源：http://dali.jyoumei.cn/Article/details/gtyzmgqncf.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gtcksujoyr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aizwys.cn/Article/details/gtrbadhytr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.c1oappe.top/Article/details/gtrndmwebt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvzjegpvx.html

[G03] 实例属性
来源：http://dali.aizwys.cn/Article/details/gtbyigoqiw.html

Py:   self.name = "x"
来源：http://dali.sufxvd.cn/Article/details/gtysrfqxyx.html

PHP:  public string $name = "x";
来源：http://dali.sufxvd.cn/Article/details/gtvkpotqtc.html

JS:   this.name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtzktkcmrf.html

TS:   name: string = "x";
来源：http://dali.fengsongda.top/Article/details/gttthtkksa.html

Java: private String name;
来源：http://dali.gotoacloud.top/Article/details/gtnslqjiwt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.dianchejie.cn/Article/details/gtzaqqaajx.html

Ruby: @name = "x"
来源：http://dali.aizwys.cn/Article/details/gtrwqgbxdw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.smart0.xyz/Article/details/gtbsrfjytx.html

[G04] 定义方法
来源：http://dali.cucudq.cn/Article/details/gtyfuvarot.html

Py:   def greet(self): return self.name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtspifalny.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gthswlfwnz.html

JS:   greet() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtpxizogwz.html

TS:   greet(): string { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtyevxzibg.html

Java: String greet() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtqzjfpqxx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtswfdbwml.html

Ruby: def greet; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gtsggdmqwb.html

C#:   public string Greet() => Name;
来源：http://dali.fzhhl.top/Article/details/gtsgluwmez.html

[G05] 继承
来源：http://dali.zhengqikj.top/Article/details/gtthdibrfd.html

Py:   class Admin(User): pass
来源：http://dali.c1oappe.top/Article/details/gteujoakte.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtxmvzpkiy.html

JS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtribsuoci.html

TS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtavocepcn.html

Java: class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gteyxeuceo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.havefunace.top/Article/details/gtfpvjtjos.html

Ruby: class Admin < User; end
来源：http://dali.cashguo.top/Article/details/gtjgebdanu.html

C#:   class Admin : User {}
来源：http://dali.shzxlz.cn/Article/details/gtxisswhoc.html

[G06] 重写方法
来源：http://dali.haohaochexian.top/Article/details/gtypqkuwyp.html

Py:   def greet(self): return "admin"
来源：http://dali.jianghu66.top/Article/details/gtmazldhjh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtzlavuvwi.html

JS:   greet() { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gtsxejnzau.html

TS:   greet(): string { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtfewllacx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gtlrycentd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cashguo.top/Article/details/gtsmssecsw.html

Ruby: def greet; "admin"; end
来源：http://dali.c1oappe.top/Article/details/gthdzniaiw.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj20258.top/Article/details/gttcqilqwt.html

[G07] 调用父类方法
来源：http://dali.dianchejie.cn/Article/details/gtlqkvsjfe.html

Py:   super().greet()
来源：http://dali.sweek.top/Article/details/gtxwxoiajm.html

PHP:  parent::greet();
来源：http://dali.havefunace.top/Article/details/gtshzkvcez.html

JS:   super.greet();
来源：http://dali.hysaishi.cn/Article/details/gtfumhrchb.html

TS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtmlbnzehf.html

Java: super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gtywsxknal.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenjidiqi.icu/Article/details/gtmqmpmjol.html

Ruby: super
来源：http://dali.mhx1999.top/Article/details/gthlbwoabc.html

C#:   base.Greet();
来源：http://dali.316326.xyz/Article/details/gtewrfbccv.html

[G08] 静态方法与属性
来源：http://dali.iojbl.cn/Article/details/gtvuvpqmje.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xinyue.icu/Article/details/gtxnpxhehq.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gtstzcrfce.html

JS:   static f() {}
来源：http://dali.zhoulong.xyz/Article/details/gtfwkijsze.html

TS:   static f(): void {}
来源：http://dali.hammf.cn/Article/details/gtjulqmvzw.html

Java: static void f() {}
来源：http://dali.zdqjudy.top/Article/details/gtaidtshcx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gtroqlphqa.html

Ruby: def self.f; end
来源：http://dali.nanxuanxn.top/Article/details/gtxosvdmwx.html

C#:   public static void F() {}
来源：http://dali.tanke756.top/Article/details/gtktnmiakv.html

[G09] 接口 / 抽象类
来源：http://dali.ivvv.top/Article/details/gtsgehelbl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pycfn.com/Article/details/gtrabyjemx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aibaodan.cn/Article/details/gtnxykmvgg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tianlin.xyz/Article/details/gtbqcxetbu.html

TS:   interface Shape { area(): number; }
来源：http://dali.316326.xyz/Article/details/gtbupckddn.html

Java: interface Shape { double area(); }
来源：http://dali.sweek.top/Article/details/gtlbcshanh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ybcxt.top/Article/details/gtqqxhhxnk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.havefunace.top/Article/details/gtpzwqnpma.html

C#:   interface IShape { double Area(); }
来源：http://dali.snrcjt.cn/Article/details/gtocibwutw.html

[G10] 访问控制
来源：http://dali.jqgfzy.top/Article/details/gtaiofnkpy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sufxvd.cn/Article/details/gtpejqhqbu.html

PHP:  public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gttrtxgglk.html

JS:   #private 字段；其余公开
来源：http://dali.9152youxi.cn/Article/details/gtqzbkagvp.html

TS:   public / protected / private
来源：http://dali.sweek.top/Article/details/gtffoplqmh.html

Java: public / protected / private / 默认包级
来源：http://dali.hnxiangtu.top/Article/details/gtboelbqyy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jlsjyb.cn/Article/details/gtuiscoexq.html

Ruby: public / protected / private
来源：http://dali.yongpay.top/Article/details/gttywlvuct.html

C#:   public / protected / private / internal
来源：http://dali.hfpthk.cn/Article/details/gtitviwwxy.html

[G11] getter / setter
来源：http://dali.jianghu66.top/Article/details/gtwrjpzvdf.html

Py:   @property 与 @x.setter
来源：http://dali.dianchejie.cn/Article/details/gtjdrqrnje.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtyargjifj.html

JS:   get name() { return this._name; }
来源：http://dali.yj202588.top/Article/details/gtaczwxsuj.html

TS:   get name(): string { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gtlbmxizbt.html

Java: public String getName() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkgoegtel.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gttwcldedg.html

Ruby: attr_accessor :name
来源：http://dali.hywenlv.cn/Article/details/gtkduyvewp.html

C#:   public string Name { get; set; }
来源：http://dali.hfpthk.cn/Article/details/gtnopanizf.html

[G12] 对象转字符串
来源：http://dali.yj20258.top/Article/details/gtmgioqfuq.html

Py:   def __str__(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gtgkrodxim.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gtushohoqd.html

JS:   toString() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtijyzplur.html

TS:   toString(): string { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkomgalaw.html

Java: @Override public String toString() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtfbrhosbs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtpwkveail.html

Ruby: def to_s; @name; end
来源：http://dali.iojbl.cn/Article/details/gtziiximrj.html

C#:   public override string ToString() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahfkmrly.html

[G13] 判断对象类型
来源：http://dali.chenzaomai.com/Article/details/gtydyesnai.html

Py:   isinstance(u, User)
来源：http://dali.chenlongwang.top/Article/details/gtvyfgynic.html

PHP:  $u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtvdbgwvek.html

JS:   u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtakgxhtrb.html

TS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjzgpept.html

Java: u instanceof User
来源：http://dali.316326.xyz/Article/details/gtwnxvytlr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hammf.cn/Article/details/gttmrayygq.html

Ruby: u.is_a?(User)
来源：http://dali.haohaochexian.top/Article/details/gtqwjwblai.html

C#:   u is User
来源：http://dali.daxiang520.top/Article/details/gtvfmcdqka.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangkeji.top/Article/details/gtefabxbat.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sweek.top/Article/details/gticgmrrhk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shzxlz.cn/Article/details/gtmjlzwobg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.aibaodan.cn/Article/details/gtbukkvdyd.html

TS:   type User = { name: string; age: number };
来源：http://dali.sweek.top/Article/details/gtaipdhqyj.html

Java: record User(String name, int age) {}
来源：http://dali.jinqigfzy.top/Article/details/gtfuokbcsm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.0kj1m.cn/Article/details/gtxmgyiyvn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xinyue.icu/Article/details/gtdlezeyah.html

C#:   record User(string Name, int Age);
来源：http://dali.xziqi.cn/Article/details/gteverqlwq.html

[G15] 枚举
来源：http://dali.yongpay.top/Article/details/gtvjvesfbd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhongyouzk.top/Article/details/gtqumfoxxc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ybcxt.top/Article/details/gtnyqfbvkx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhiwuduotai.top/Article/details/gtijyasgxt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gtuaevhkgy.html

Java: enum Color { RED, GREEN }
来源：http://dali.yvedp.cn/Article/details/gtescrtkbg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gtbirqhemq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guowangkeji.top/Article/details/gtitbjajws.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gthzxliumv.html

[G16] 对象转数组 / 字典
来源：http://dali.yj202588.top/Article/details/gtwnefbnih.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jiagoushi.top/Article/details/gtngfjqhui.html

PHP:  get_object_vars($obj);
来源：http://dali.gzhubu.top/Article/details/gtspitbrgz.html

JS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gtfosxljen.html

TS:   Object.entries(obj)
来源：http://dali.redwolf501.top/Article/details/gtxzthqmee.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhixingplan.top/Article/details/gtevzpuriu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhixingplan.top/Article/details/gtjeqqzttx.html

Ruby: obj.instance_variables
来源：http://dali.redwolf501.top/Article/details/gtisyxberu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhoulong.xyz/Article/details/gtxmzngduy.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtyusmmjtj.html

H. 异常与错误处理
来源：http://dali.pycfn.com/Article/details/gtenkryqzk.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtfppxrjfg.html

[H01] try / catch 基础
来源：http://dali.zdqjudy.top/Article/details/gtcyvsctzs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ydzc1.top/Article/details/gtlfvzmtcu.html


<!-- 参考信息 -->