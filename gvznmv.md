代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.chenjidiqi.icu/Article/details/gthomsqavt.html

TS:   s.split(/\r?\n/)
来源：http://dali.dashuyun.cn/Article/details/gtoyqhhstf.html

Java: s.lines().toList()
来源：http://dali.guowangkeji.top/Article/details/gtxmbmdlsy.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvxaintt.html

Ruby: s.lines
来源：http://dali.jqgufenzy.top/Article/details/gtxjflwbpp.html

C#:   s.Split('\n')
来源：http://dali.daxiang520.top/Article/details/gtrzvvtwme.html

[E20] 判断字符串是否为空
来源：http://dali.xinyue.icu/Article/details/gtmzupikkr.html

Py:   if not s:
来源：http://dali.tianlin.xyz/Article/details/gtrlpeqwrw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.0kj1m.cn/Article/details/gtqvohtbeu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenlongwang.top/Article/details/gtxoanrqhh.html

TS:   if (s === "") {}
来源：http://dali.chenlongwang.top/Article/details/gtxrmmvarb.html

Java: if (s.isEmpty()) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtsxfldwwi.html

Go:   if s == "" {}
来源：http://dali.316326.xyz/Article/details/gthherbras.html

Ruby: if s.empty?
来源：http://dali.xuanzx.com/Article/details/gturnrhnmz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sweek.top/Article/details/gtmldynxyz.html

[E21] 超长截断加省略号
来源：http://dali.xinyue.icu/Article/details/gtimdzoudg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hongshengwenyu.top/Article/details/gtdeazxmdo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtqisqlftm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtixalrsno.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtldvbfhes.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtslumjijf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jiagoushi.top/Article/details/gtjtuexwhc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtcnnlkcnf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtkqlunutz.html

[E22] 字节长度与字符长度
来源：http://dali.yj202588.top/Article/details/gtxgnpsrsx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ydzc1.top/Article/details/gtpqpnhoem.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gtkmxxkcjs.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sufxvd.cn/Article/details/gtipemogbq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtydirplif.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hammf.cn/Article/details/gtnbtgfvcx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jqgufenzy.top/Article/details/gtxdhmudve.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gtzjgwitdm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nwbrower.top/Article/details/gtwsvxundn.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvgqwade.html

F. 文件与目录
来源：http://dali.hysaishi.cn/Article/details/gtydwwijca.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtiawcxjcs.html

[F01] 读取整个文件
来源：http://dali.316326.xyz/Article/details/gtrptbjqyf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.wangdashe.top/Article/details/gtuamhfvvq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtqgrescgy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fzhhl.top/Article/details/gtoacnqrvs.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cheryme.top/Article/details/gthendkqtz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gtwqfdxvhc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sufxvd.cn/Article/details/gthorsygid.html

Ruby: File.read("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtmllzhfdn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtmhpyovgg.html

[F02] 逐行读取文件
来源：http://dali.nwbrower.top/Article/details/gtjfswderv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ehwqpu.com/Article/details/gtwfpiiwyf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.9152youxi.cn/Article/details/gtxtkubwhy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daxiang520.top/Article/details/gtwtzujogc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.mhx1999.top/Article/details/gtvfzovcvf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.feifeiyinyue.top/Article/details/gtueyngyko.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shzxlz.cn/Article/details/gtluenygbg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yangfankeji.com/Article/details/gtmnsssahw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tianlin.xyz/Article/details/gtjdzhthtr.html

[F03] 写入文件（覆盖）
来源：http://dali.hammf.cn/Article/details/gtnpguqcno.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jqgfzy.top/Article/details/gtunrmbkih.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gtnkqhvjnl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gtccnicwxa.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtcykbstbr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.0kj1m.cn/Article/details/gtbhckzaul.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.smart0.xyz/Article/details/gtuhvatooe.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.9152youxi.cn/Article/details/gtuqiyohcu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.316326.xyz/Article/details/gteqaftsiw.html

[F04] 追加写入文件
来源：http://dali.svipenyu.cn/Article/details/gtcjhgmpza.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfalgggks.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cucudq.cn/Article/details/gtjttguasr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tanke756.top/Article/details/gtyvlkhrjj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shuidangran.top/Article/details/gtnkmhcgyx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sweek.top/Article/details/gtailgynyc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cucudq.cn/Article/details/gtzluuwwrx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xuanzx.com/Article/details/gtejiwktme.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.dashuyun.cn/Article/details/gtlafcoxgg.html

[F05] 判断文件或目录是否存在
来源：http://dali.ppjwa.cn/Article/details/gtrcvyfdoi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.iojbl.cn/Article/details/gtszwhrnvv.html

PHP:  file_exists("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtynytjtdf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtpeumutpg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtpsyijszc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtbrzexlqn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj20258888.top/Article/details/gtlevpjtzi.html

Ruby: File.exist?("a.txt")
来源：http://dali.yongpay.top/Article/details/gtedxzkgiw.html

C#:   File.Exists("a.txt")
来源：http://dali.pycfn.com/Article/details/gtlentvfwb.html

[F06] 删除文件
来源：http://dali.hnqzz.top/Article/details/gttnctijlw.html

Py:   os.remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtchfzyvgo.html

PHP:  unlink("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtzykcowfq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtitnklypi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtvdayecdq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtsxqmwcrk.html

Go:   os.Remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtkidutuce.html

Ruby: File.delete("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtjylzinii.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmqznkjn.html

[F07] 创建目录（含多级）
来源：http://dali.zhiwuduotai.top/Article/details/gtlsjlqqvb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daxiang520.top/Article/details/gthgtkyeih.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ppjwa.cn/Article/details/gttfnfykwl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gtlmuwrofs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gtfuhrnpih.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.havefunace.top/Article/details/gtlfvmtfgd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.smart0.xyz/Article/details/gtaivayfai.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gotoacloud.top/Article/details/gtoacqcemx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenjidiqi.icu/Article/details/gtjgehrxys.html

[F08] 遍历目录
来源：http://dali.sufxvd.cn/Article/details/gtxuiihrjc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sysykeji.top/Article/details/gtevcopvpl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.iojbl.cn/Article/details/gtzfhjtbfq.html

JS:   fs.readdirSync("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtwmzkdcgv.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj20258.top/Article/details/gtxsmpfllb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj202588.top/Article/details/gtntzcxcru.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxmuipfu.html

Ruby: Dir.children("dir")
来源：http://dali.smart0.xyz/Article/details/gtrupqrmoj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cdnleiting.top/Article/details/gtwkzftluv.html

[F09] 获取文件大小
来源：http://dali.wangshuangyany.cn/Article/details/gtprbnucsk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtndmpwpqq.html

PHP:  filesize("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtffrgmjev.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shuidangran.top/Article/details/gtatefrfsw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gtsgurwvfn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gthxguakad.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sxryk.cn/Article/details/gtqhvndmvm.html

Ruby: File.size("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtptzpoafj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jqgufenzy.top/Article/details/gtdnrvwpyi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.birdmap.top/Article/details/gtdtvtpthp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtuxnopmxp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtdjmiujzc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtiyavodwn.html

TS:   path.extname("a.txt")
来源：http://dali.havefunace.top/Article/details/gthynldvkq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zdqjudy.top/Article/details/gtwxsesqat.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtygvbyapa.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtfhwulhmy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gthpyzcdga.html

[F11] 复制与移动文件
来源：http://dali.wangdashe.top/Article/details/gtyhpxrgpe.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtawlpxapy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtbzrafkgh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtrituwkvw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtrivcalzr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sxryk.cn/Article/details/gtilmacmcq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuanzx.com/Article/details/gtrubpvsde.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtuwxwcczs.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zycfv.cn/Article/details/gttyxuydsw.html

[F12] CSV 读写
来源：http://dali.sufxvd.cn/Article/details/gtahtvalpw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.snrcjt.cn/Article/details/gtzsrfggpo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sxryk.cn/Article/details/gtkhfkdixk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.wangdashe.top/Article/details/gtqqpqgfvc.html

TS:   // 同上
来源：http://dali.gotoacloud.top/Article/details/gteshqczbz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fzhhl.top/Article/details/gtjgpwyfif.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cqqwz.cn/Article/details/gtvwobqtuc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.iojbl.cn/Article/details/gtlicdlvhh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gtjbhtchhy.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtukzliqec.html

G. 面向对象
来源：http://dali.aizwys.cn/Article/details/gtxwquzfix.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gttgxelvnj.html

[G01] 定义类
来源：http://dali.vqdsnc.cn/Article/details/gtyfegcfoc.html

Py:   class User: pass
来源：http://dali.haohaochexian.top/Article/details/gtwraunait.html

PHP:  class User {}
来源：http://dali.316326.xyz/Article/details/gtgjnfzllo.html

JS:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtfhxmcyjx.html

TS:   class User { name: string = ""; }
来源：http://dali.pycfn.com/Article/details/gtlivfllre.html

Java: class User {}
来源：http://dali.vqdsnc.cn/Article/details/gthasqthoz.html

Go:   type User struct { Name string }
来源：http://dali.aizwys.cn/Article/details/gtffiljbet.html

Ruby: class User; end
来源：http://dali.c1oappe.top/Article/details/gtjgokrikq.html

C#:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtrnqtpgfr.html

[G02] 构造函数
来源：http://dali.gzhubu.top/Article/details/gtneevpfun.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenjidiqi.icu/Article/details/gtepfrbygo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gtlhihexzo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gtzupzztha.html

TS:   constructor(public name: string) {}
来源：http://dali.snrcjt.cn/Article/details/gtybtahezr.html

Java: User(String name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gtshcnefhl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.smart0.xyz/Article/details/gtpnumtpxt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenjidiqi.icu/Article/details/gtlkdwjvkr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cucudq.cn/Article/details/gtlfpeobsl.html

[G03] 实例属性
来源：http://dali.zhoulong.xyz/Article/details/gthswmbvxh.html

Py:   self.name = "x"
来源：http://dali.cashguo.top/Article/details/gtaczyzfth.html

PHP:  public string $name = "x";
来源：http://dali.yvedp.cn/Article/details/gtswcaevml.html

JS:   this.name = "x";
来源：http://dali.c1oappe.top/Article/details/gtclybxygd.html

TS:   name: string = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtwfrxpyby.html

Java: private String name;
来源：http://dali.yvedp.cn/Article/details/gtnhhxmexj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jyoumei.cn/Article/details/gtcdauhjcd.html

Ruby: @name = "x"
来源：http://dali.fzhhl.top/Article/details/gtsqvpsywp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yueranfly.top/Article/details/gtxbslarbr.html

[G04] 定义方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtyidgdcgu.html

Py:   def greet(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gtrwekhfkr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gthdbnzkeo.html

JS:   greet() { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtcfigmfvg.html

TS:   greet(): string { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gthhhmxjbi.html

Java: String greet() { return name; }
来源：http://dali.xinyue.icu/Article/details/gtfgdqsotj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gtfagplnpg.html

Ruby: def greet; @name; end
来源：http://dali.jyoumei.cn/Article/details/gtntypzpov.html

C#:   public string Greet() => Name;
来源：http://dali.daxiang520.top/Article/details/gtkjdlvvgp.html

[G05] 继承
来源：http://dali.smart0.xyz/Article/details/gtozpeqxir.html

Py:   class Admin(User): pass
来源：http://dali.nanxinkj.top/Article/details/gtkwnsfyxj.html

PHP:  class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtejnjzjbw.html

JS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtmfflydtg.html

TS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtfltoxibm.html

Java: class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtsxhykrdt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cashguo.top/Article/details/gtthqgsizu.html

Ruby: class Admin < User; end
来源：http://dali.hnxiangtu.top/Article/details/gtzngicdxs.html

C#:   class Admin : User {}
来源：http://dali.yuxming.cn/Article/details/gtedpubvaa.html

[G06] 重写方法
来源：http://dali.sysykeji.top/Article/details/gteeincdsk.html

Py:   def greet(self): return "admin"
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrehdnea.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtxaexxbta.html

JS:   greet() { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtgjhkpzan.html

TS:   greet(): string { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtoarwrvqu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtseqrghgm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aibaodan.cn/Article/details/gtuxeslzsl.html

Ruby: def greet; "admin"; end
来源：http://dali.sxryk.cn/Article/details/gtfzzimosy.html

C#:   public override string Greet() => "admin";
来源：http://dali.fzhhl.top/Article/details/gtrrcinqef.html

[G07] 调用父类方法
来源：http://dali.yangfankeji.com/Article/details/gtannpaqpn.html

Py:   super().greet()
来源：http://dali.jlsjyb.cn/Article/details/gtcreoomot.html

PHP:  parent::greet();
来源：http://dali.havefunace.top/Article/details/gtmcbtiolt.html

JS:   super.greet();
来源：http://dali.sweek.top/Article/details/gtdjwndlld.html

TS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gtjhixqsvw.html

Java: super.greet();
来源：http://dali.yj202588.top/Article/details/gtccuzuaem.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cheryme.top/Article/details/gtqdxmilhm.html

Ruby: super
来源：http://dali.aibaodan.cn/Article/details/gtzmytdbhh.html

C#:   base.Greet();
来源：http://dali.jyoumei.cn/Article/details/gtdczuhaiq.html

[G08] 静态方法与属性
来源：http://dali.andypj.xyz/Article/details/gtfulquprp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.fzhhl.top/Article/details/gtkjugcqnp.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gtyxzjykkt.html

JS:   static f() {}
来源：http://dali.andypj.xyz/Article/details/gtmxepanoj.html

TS:   static f(): void {}
来源：http://dali.yangfankeji.com/Article/details/gtlhrkwgec.html

Java: static void f() {}
来源：http://dali.yj20258888.top/Article/details/gtpbearjvl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinqigfzy.top/Article/details/gtjyqugpqu.html

Ruby: def self.f; end
来源：http://dali.svipenyu.cn/Article/details/gtcboxoxix.html

C#:   public static void F() {}
来源：http://dali.fengsongda.top/Article/details/gtvcinlrtg.html

[G09] 接口 / 抽象类
来源：http://dali.xylfe.cn/Article/details/gtqtdbkmmf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sxryk.cn/Article/details/gtdjrwpqdy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.dashuyun.cn/Article/details/gtohhxxlnn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yuxming.cn/Article/details/gtcnzcxyee.html

TS:   interface Shape { area(): number; }
来源：http://dali.yueranfly.top/Article/details/gtqakxzqva.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigfzy.top/Article/details/gtisvgpjwe.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ppjwa.cn/Article/details/gtigjksdso.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hongshengwenyu.top/Article/details/gthjjbnpst.html

C#:   interface IShape { double Area(); }
来源：http://dali.tianlin.xyz/Article/details/gtuimjpcjr.html

[G10] 访问控制
来源：http://dali.c1oappe.top/Article/details/gtwoemsbeg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhoulong.xyz/Article/details/gtzxeenysc.html

PHP:  public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtnvesnudf.html

JS:   #private 字段；其余公开
来源：http://dali.gzhubu.top/Article/details/gtfsujxugd.html

TS:   public / protected / private
来源：http://dali.ybcxt.top/Article/details/gtrtbxdxgo.html

Java: public / protected / private / 默认包级
来源：http://dali.yanxiufei.cn/Article/details/gtjngdyucn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigufen.top/Article/details/gtdkydmdcm.html

Ruby: public / protected / private
来源：http://dali.fengsongda.top/Article/details/gtzohrjamx.html

C#:   public / protected / private / internal
来源：http://dali.sufxvd.cn/Article/details/gteupkxksn.html

[G11] getter / setter
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxaixhyi.html

Py:   @property 与 @x.setter
来源：http://dali.vqdsnc.cn/Article/details/gthpasmpul.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtoedqcufk.html

JS:   get name() { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gtynydaooq.html

TS:   get name(): string { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gtelzwwmgi.html

Java: public String getName() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtkprbxytl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtuadfqrfb.html

Ruby: attr_accessor :name
来源：http://dali.hnxiangtu.top/Article/details/gtwifqihdz.html

C#:   public string Name { get; set; }
来源：http://dali.aibaodan.cn/Article/details/gtmlpqmimb.html

[G12] 对象转字符串
来源：http://dali.sysykeji.top/Article/details/gtffcqqipz.html

Py:   def __str__(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gtsbseenag.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtrztxqzet.html

JS:   toString() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gttzipfgws.html

TS:   toString(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtnzmbpkhp.html

Java: @Override public String toString() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtviydajqb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gtlursodgu.html

Ruby: def to_s; @name; end
来源：http://dali.ydzc1.top/Article/details/gtxxeppyvg.html

C#:   public override string ToString() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsrxxaqgb.html

[G13] 判断对象类型
来源：http://dali.snrcjt.cn/Article/details/gtmferanwa.html

Py:   isinstance(u, User)
来源：http://dali.cashguo.top/Article/details/gtzfaoqmdr.html

PHP:  $u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtuqzizsob.html

JS:   u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtwgrmuilc.html

TS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gtlkxbpkba.html

Java: u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtnkyyfrdo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.guannengcc.top/Article/details/gtidkndokh.html

Ruby: u.is_a?(User)
来源：http://dali.smart0.xyz/Article/details/gthrbenlkd.html

C#:   u is User
来源：http://dali.jinqigufen.top/Article/details/gtiaqxbihn.html

[G14] 数据类 / record
来源：http://dali.daria6918.cn/Article/details/gtzqssahhu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dianchejie.cn/Article/details/gtkxkldjth.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dashuyun.cn/Article/details/gttktfswtl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xylfe.cn/Article/details/gtxutexezw.html

TS:   type User = { name: string; age: number };
来源：http://dali.ppjwa.cn/Article/details/gtlodcgtkx.html

Java: record User(String name, int age) {}
来源：http://dali.jiagoushi.top/Article/details/gteynnjbkc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yuanzhike.top/Article/details/gtacwfdqbo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.svipenyu.cn/Article/details/gtajpyxzlx.html

C#:   record User(string Name, int Age);
来源：http://dali.fengsongda.top/Article/details/gtlsmxoggy.html

[G15] 枚举
来源：http://dali.316326.xyz/Article/details/gtrxqqgxod.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhixingplan.top/Article/details/gtuhzrmxaf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hywenlv.cn/Article/details/gtolmvtfoj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nwbrower.top/Article/details/gteuevlztn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.0kj1m.cn/Article/details/gtzfkbwjmo.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinghuilouyu.cn/Article/details/gtomdjgpir.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zdqjudy.top/Article/details/gtugbtzyfz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.quarkkingdee.top/Article/details/gtobhyixqm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtomsxnjva.html

[G16] 对象转数组 / 字典
来源：http://dali.ydzc1.top/Article/details/gtwevikobp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhongyouzk.top/Article/details/gtbnoljaeg.html

PHP:  get_object_vars($obj);
来源：http://dali.xinyue.icu/Article/details/gthspslmae.html

JS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gtqxadmjph.html

TS:   Object.entries(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtdvgexkzw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daxiang520.top/Article/details/gtnducvshm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tianlin.xyz/Article/details/gtcvchzvvj.html

Ruby: obj.instance_variables
来源：http://dali.shangyingyoupin.top/Article/details/gtmhijhrtr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.meibo888.top/Article/details/gttrxkdhns.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtdgogrrye.html

H. 异常与错误处理
来源：http://dali.havefunace.top/Article/details/gtrdelbdij.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtclbrrolf.html

[H01] try / catch 基础
来源：http://dali.gzhubu.top/Article/details/gtxspoavua.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenjidiqi.icu/Article/details/gtcqawcqvi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhoulong.xyz/Article/details/gtrktuvfyu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gtcngwvcbm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gtbvfdcokk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.vqdsnc.cn/Article/details/gthqwroazt.html


<!-- 参考信息 -->