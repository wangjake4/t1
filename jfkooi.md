代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ehwqpu.com/Article/details/gtidlvpfoc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.dianchejie.cn/Article/details/gtlscibawh.html

TS:   if (s === "") {}
来源：http://dali.zdqjudy.top/Article/details/gtexfnsbsl.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrcfdkds.html

Go:   if s == "" {}
来源：http://dali.birdmap.top/Article/details/gtzsixeoxe.html

Ruby: if s.empty?
来源：http://dali.zdqjudy.top/Article/details/gtjzolzkhi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj202588.top/Article/details/gtlemoktqn.html

[E21] 超长截断加省略号
来源：http://dali.yuanzhike.top/Article/details/gthmttakta.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenzaomai.com/Article/details/gtalixkuiy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gthnokpfzi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtgiufoxnf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtxocswzvv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtxyrtcfos.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwpnnqay.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtlcghtjyd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gttmaacjif.html

[E22] 字节长度与字符长度
来源：http://dali.cucudq.cn/Article/details/gtxgnsrbgc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjphqrij.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gtlxcddtdp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.smart0.xyz/Article/details/gttrsdreop.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cqqwz.cn/Article/details/gtizluetxr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.bjfxy.top/Article/details/gtfhfygcwx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiriqhhkb.html

Ruby: s.bytesize;  s.length
来源：http://dali.hammf.cn/Article/details/gtrgwuomjl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhoulong.xyz/Article/details/gtxiwawedm.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfiipvfej.html

F. 文件与目录
来源：http://dali.fzhhl.top/Article/details/gtaqeqfjgs.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtovtprvcp.html

[F01] 读取整个文件
来源：http://dali.0kj1m.cn/Article/details/gtwamolrua.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hnxiangtu.top/Article/details/gtzbmjgwcz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtpipmyeud.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yueranfly.top/Article/details/gtfywaaqhn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gtmjehhpgw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtglocsipz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xuanzx.com/Article/details/gtguzycysf.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmegscur.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtlyhqspdx.html

[F02] 逐行读取文件
来源：http://dali.pycfn.com/Article/details/gtnicosdzv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hfpthk.cn/Article/details/gttdzrkwiz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yvedp.cn/Article/details/gtwnuxzcoy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gttgbqekyq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gtlwkugdgq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.aizwys.cn/Article/details/gtllhbarny.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cqqwz.cn/Article/details/gtmhkwvtbz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shuidangran.top/Article/details/gthttaeyxr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cdnleiting.top/Article/details/gtgtyytnbo.html

[F03] 写入文件（覆盖）
来源：http://dali.feifeiyinyue.top/Article/details/gtkhpikkex.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.fzhhl.top/Article/details/gtcbidhasi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gtnxcqobrm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gtebbutuqo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gtwlanvjon.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.svipenyu.cn/Article/details/gtbggkqdyg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hysaishi.cn/Article/details/gtnvsdblfh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jyoumei.cn/Article/details/gtaohxebmi.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sufxvd.cn/Article/details/gtcmabbhze.html

[F04] 追加写入文件
来源：http://dali.chenlongwang.top/Article/details/gtupaoqjyf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jyoumei.cn/Article/details/gthnwajdor.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shangyingyoupin.top/Article/details/gtcgkspmsi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgfzy.top/Article/details/gtdqspyrks.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gttldqfxrk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tianlin.xyz/Article/details/gtfufbqyxv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangdashe.top/Article/details/gtdncxftwq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sweek.top/Article/details/gthsevokdv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gotoacloud.top/Article/details/gtjdmywbfs.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigufen.top/Article/details/gtjwlcdvho.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yuanzhike.top/Article/details/gtujpeyiic.html

PHP:  file_exists("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtyvzviikj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtwtnypzfg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gthjikcmlt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtmzxumueu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinqigfzy.top/Article/details/gtainzwyjl.html

Ruby: File.exist?("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtlbisdvgv.html

C#:   File.Exists("a.txt")
来源：http://dali.pycfn.com/Article/details/gtkuurrwct.html

[F06] 删除文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmcyfkfas.html

Py:   os.remove("a.txt")
来源：http://dali.sweek.top/Article/details/gtneclhusd.html

PHP:  unlink("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtqaqqdibq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtaaqjervh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtbnfjqzsy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gtznkllecj.html

Go:   os.Remove("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtepocsohz.html

Ruby: File.delete("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtbljwjvil.html

C#:   File.Delete("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtzafyvuor.html

[F07] 创建目录（含多级）
来源：http://dali.9152youxi.cn/Article/details/gtdzgbjari.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hammf.cn/Article/details/gttocthwxx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gotoacloud.top/Article/details/gtlojyaviv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gtjjxqdexe.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gtkosxldce.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xziqi.cn/Article/details/gtfvxojuqx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hfpthk.cn/Article/details/gtyzxzrmha.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.guowangkeji.top/Article/details/gttxbvxxyu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hysaishi.cn/Article/details/gtiqbxzwjc.html

[F08] 遍历目录
来源：http://dali.hnxiangtu.top/Article/details/gtbfskdjar.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cashguo.top/Article/details/gtzqfrzidc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwllxypcu.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtaohlogbf.html

TS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gtooyozqxn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gtfvxwryba.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtkxaqoase.html

Ruby: Dir.children("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbvszybo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cqqwz.cn/Article/details/gtplctbibv.html

[F09] 获取文件大小
来源：http://dali.smart0.xyz/Article/details/gtjiisjxec.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtnjecaevk.html

PHP:  filesize("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtaqatcumv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cucudq.cn/Article/details/gtqhnggimi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yuxming.cn/Article/details/gtrkshtfxr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtzofsbtek.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yueranfly.top/Article/details/gtoqlzpckq.html

Ruby: File.size("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtigoslwax.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangdashe.top/Article/details/gtwudgzxlx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shuidangran.top/Article/details/gtxmwyaauv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtnobojhkw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfnbwwbup.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtigzzraid.html

TS:   path.extname("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtpjigvgxw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shanyushiyangtech.top/Article/details/gtquxhilqb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoykngtax.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtfdnuzxec.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtgzxahtdo.html

[F11] 复制与移动文件
来源：http://dali.shuidangran.top/Article/details/gtoqebkhio.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtiknbmuqn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.snrcjt.cn/Article/details/gtejtjgrsf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpugcxwym.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gthnkfpeaf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yvedp.cn/Article/details/gtzkseeysn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhiwuduotai.top/Article/details/gtmrsvpnsl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtcscdbzps.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuetiantiany.cn/Article/details/gtezjmrhst.html

[F12] CSV 读写
来源：http://dali.fzhhl.top/Article/details/gtfygemvjp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkpwkmhdx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.9152youxi.cn/Article/details/gtmnyqmwxv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xziqi.cn/Article/details/gtislsxoke.html

TS:   // 同上
来源：http://dali.shuidangran.top/Article/details/gtfufmuvjn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yanxiufei.cn/Article/details/gtrbglkyeb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cucudq.cn/Article/details/gtwybmtapv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fengsongda.top/Article/details/gtpusratgy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenjidiqi.icu/Article/details/gtmmhxlnnd.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtuluyacat.html

G. 面向对象
来源：http://dali.aizwys.cn/Article/details/gtctxbtjwt.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtiycrdvkk.html

[G01] 定义类
来源：http://dali.birdmap.top/Article/details/gtkoquspnl.html

Py:   class User: pass
来源：http://dali.haohaochexian.top/Article/details/gtyzexlhvd.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gtctuuqalm.html

JS:   class User {}
来源：http://dali.fengsongda.top/Article/details/gtddasrccc.html

TS:   class User { name: string = ""; }
来源：http://dali.pycfn.com/Article/details/gtmdablges.html

Java: class User {}
来源：http://dali.zhixingplan.top/Article/details/gtimbarqql.html

Go:   type User struct { Name string }
来源：http://dali.kuanghao11.cn/Article/details/gtpvvtnkft.html

Ruby: class User; end
来源：http://dali.hongshengwenyu.top/Article/details/gtyeovlmcz.html

C#:   class User {}
来源：http://dali.cucudq.cn/Article/details/gtysrrltbr.html

[G02] 构造函数
来源：http://dali.sweek.top/Article/details/gtdjbejroi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ivvv.top/Article/details/gtexekrwzs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258888.top/Article/details/gtudvwhytn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvyhdgcwx.html

TS:   constructor(public name: string) {}
来源：http://dali.haohaochexian.top/Article/details/gtrxxxpdlj.html

Java: User(String name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtpzxsrbjp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj20258888.top/Article/details/gtjzsxelyq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xuetiantiany.cn/Article/details/gtqgxsdtms.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtbyajiysm.html

[G03] 实例属性
来源：http://dali.jiagoushi.top/Article/details/gtfcdxgqep.html

Py:   self.name = "x"
来源：http://dali.yongpay.top/Article/details/gtcumtllxp.html

PHP:  public string $name = "x";
来源：http://dali.sufxvd.cn/Article/details/gtntglgugx.html

JS:   this.name = "x";
来源：http://dali.yuxming.cn/Article/details/gtpusvsvga.html

TS:   name: string = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtpyavwzqt.html

Java: private String name;
来源：http://dali.jinqigfzy.top/Article/details/gtymgjpvgy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tian-w.cn/Article/details/gtrlkrdcga.html

Ruby: @name = "x"
来源：http://dali.cqqwz.cn/Article/details/gtmatzesnq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxinkj.top/Article/details/gtnbltbxxt.html

[G04] 定义方法
来源：http://dali.sufxvd.cn/Article/details/gtonskvbtv.html

Py:   def greet(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gtviqorzvg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtxkrzvdeo.html

JS:   greet() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtufozpizb.html

TS:   greet(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtcprzeggb.html

Java: String greet() { return name; }
来源：http://dali.meibo888.top/Article/details/gtrsicgatm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpppvxcig.html

Ruby: def greet; @name; end
来源：http://dali.jinqigufen.top/Article/details/gtyoxfskjz.html

C#:   public string Greet() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gtqzhzoume.html

[G05] 继承
来源：http://dali.gotoacloud.top/Article/details/gtwrppcocz.html

Py:   class Admin(User): pass
来源：http://dali.fzhhl.top/Article/details/gtwxhbmwcq.html

PHP:  class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtyoqycpgw.html

JS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtgcjgmeyc.html

TS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtvqfbihtq.html

Java: class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtqmtescpo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj20258888.top/Article/details/gtwrrcnyvi.html

Ruby: class Admin < User; end
来源：http://dali.chenlongwang.top/Article/details/gtnxlmwjfw.html

C#:   class Admin : User {}
来源：http://dali.pengpengdd.cyou/Article/details/gthewdpenm.html

[G06] 重写方法
来源：http://dali.aizwys.cn/Article/details/gtkxtntqkf.html

Py:   def greet(self): return "admin"
来源：http://dali.dianchejie.cn/Article/details/gtiairxhvg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtujxdsbkb.html

JS:   greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtcjjgbfqx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtxuijwkdu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtmyoersri.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hammf.cn/Article/details/gtbrejzzyh.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxlouzaw.html

C#:   public override string Greet() => "admin";
来源：http://dali.shzxlz.cn/Article/details/gtodiviwfr.html

[G07] 调用父类方法
来源：http://dali.chenlongwang.top/Article/details/gtcxzcxcjg.html

Py:   super().greet()
来源：http://dali.gzhubu.top/Article/details/gtjzhtglmx.html

PHP:  parent::greet();
来源：http://dali.cdnleiting.top/Article/details/gtomsaqxpv.html

JS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtpbkjjygo.html

TS:   super.greet();
来源：http://dali.c1oappe.top/Article/details/gtakrjrlat.html

Java: super.greet();
来源：http://dali.chenlongwang.top/Article/details/gtefpofwlb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hfpthk.cn/Article/details/gtlnuzpwgy.html

Ruby: super
来源：http://dali.hnqzz.top/Article/details/gtocsnpuyi.html

C#:   base.Greet();
来源：http://dali.fengsongda.top/Article/details/gtqekkqodz.html

[G08] 静态方法与属性
来源：http://dali.shangyingyoupin.top/Article/details/gtbistmgaz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.smart0.xyz/Article/details/gtpfdhuxej.html

PHP:  public static function f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdcrhpsum.html

JS:   static f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtsrlmwpkm.html

TS:   static f(): void {}
来源：http://dali.snrcjt.cn/Article/details/gtzoeyyfzp.html

Java: static void f() {}
来源：http://dali.hywenlv.cn/Article/details/gtsdfwfgdq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkzpckci.html

Ruby: def self.f; end
来源：http://dali.svipenyu.cn/Article/details/gtfktiphrg.html

C#:   public static void F() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqeedlums.html

[G09] 接口 / 抽象类
来源：http://dali.gaohongyu789.top/Article/details/gtmkzlnhwz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jlsjyb.cn/Article/details/gtuenqolbo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.birdmap.top/Article/details/gturmvdhdj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jlsjyb.cn/Article/details/gtcfvrrhpy.html

TS:   interface Shape { area(): number; }
来源：http://dali.gaohongyu789.top/Article/details/gtmbxfcphl.html

Java: interface Shape { double area(); }
来源：http://dali.xuanzx.com/Article/details/gtrrqpwrtb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.kuanghao11.cn/Article/details/gtyeuwmdef.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fzhhl.top/Article/details/gtiytlqeyc.html

C#:   interface IShape { double Area(); }
来源：http://dali.xziqi.cn/Article/details/gtuxhbswmz.html

[G10] 访问控制
来源：http://dali.andypj.xyz/Article/details/gtxmoubqcy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj202588.top/Article/details/gtggbvqgsr.html

PHP:  public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtzywuftbh.html

JS:   #private 字段；其余公开
来源：http://dali.jianghu66.top/Article/details/gtnezlkclb.html

TS:   public / protected / private
来源：http://dali.ivvv.top/Article/details/gtzdcsfdpl.html

Java: public / protected / private / 默认包级
来源：http://dali.zhiwuduotai.top/Article/details/gtkqdnsfra.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhoulong.xyz/Article/details/gtbamfbyvv.html

Ruby: public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtffhefiwv.html

C#:   public / protected / private / internal
来源：http://dali.hammf.cn/Article/details/gtgzltemgs.html

[G11] getter / setter
来源：http://dali.shuidangran.top/Article/details/gtgeblwapo.html

Py:   @property 与 @x.setter
来源：http://dali.gotoacloud.top/Article/details/gtaebspwum.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtryxuobuo.html

JS:   get name() { return this._name; }
来源：http://dali.snrcjt.cn/Article/details/gtbsbjamwe.html

TS:   get name(): string { return this._name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtusdgluws.html

Java: public String getName() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtyjwwiezz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gtszfnrmwo.html

Ruby: attr_accessor :name
来源：http://dali.ivvv.top/Article/details/gtfyzwzawr.html

C#:   public string Name { get; set; }
来源：http://dali.jinghuilouyu.cn/Article/details/gthbnszdhp.html

[G12] 对象转字符串
来源：http://dali.hywenlv.cn/Article/details/gtwkqouaci.html

Py:   def __str__(self): return self.name
来源：http://dali.jinqigufen.top/Article/details/gtvhzrxttx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtbrcpfahj.html

JS:   toString() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtsvltwndu.html

TS:   toString(): string { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtumilmurg.html

Java: @Override public String toString() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtfobahrea.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gtbswuljba.html

Ruby: def to_s; @name; end
来源：http://dali.daria6918.cn/Article/details/gteaxhjlvx.html

C#:   public override string ToString() => Name;
来源：http://dali.jiagoushi.top/Article/details/gtduaoywpl.html

[G13] 判断对象类型
来源：http://dali.pengpengdd.cyou/Article/details/gtxvbsjfpe.html

Py:   isinstance(u, User)
来源：http://dali.zhoulong.xyz/Article/details/gtfwvpyfyr.html

PHP:  $u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gthtbavqve.html

JS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtftzjhpor.html

TS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtibgzatrz.html

Java: u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtuxbahgin.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yongpay.top/Article/details/gtiknmyrem.html

Ruby: u.is_a?(User)
来源：http://dali.hammf.cn/Article/details/gtwipqsden.html

C#:   u is User
来源：http://dali.jinghuilouyu.cn/Article/details/gtlpdatvst.html

[G14] 数据类 / record
来源：http://dali.hongshengwenyu.top/Article/details/gtchbiculk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nwbrower.top/Article/details/gtyrobywio.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwtzehdy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jlsjyb.cn/Article/details/gtokaywogf.html

TS:   type User = { name: string; age: number };
来源：http://dali.shzxlz.cn/Article/details/gtekwcyeqw.html

Java: record User(String name, int age) {}
来源：http://dali.yangfankeji.com/Article/details/gtktavjcer.html

Go:   type User struct { Name string; Age int }
来源：http://dali.birdmap.top/Article/details/gtvwdahkok.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xylfe.cn/Article/details/gtuceyjzma.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigufen.top/Article/details/gtqiyebykr.html

[G15] 枚举
来源：http://dali.nwbrower.top/Article/details/gtsfwdmqgc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guannengcc.top/Article/details/gtbmocqgnt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.c1oappe.top/Article/details/gtaeynwtsc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ydzc1.top/Article/details/gtrqtognip.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gtlxthzzcy.html

Java: enum Color { RED, GREEN }
来源：http://dali.pycfn.com/Article/details/gtmmixzwch.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zdqjudy.top/Article/details/gtsrrvxpll.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gaohongyu789.top/Article/details/gtglbfjxzg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.9152youxi.cn/Article/details/gtykzgfnrr.html

[G16] 对象转数组 / 字典
来源：http://dali.shzxlz.cn/Article/details/gtireiamry.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hysaishi.cn/Article/details/gtswefpltf.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgfzy.top/Article/details/gtenprizxp.html

JS:   Object.entries(obj)
来源：http://dali.yongpay.top/Article/details/gtqcxjhpxs.html

TS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gtnmbkofon.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangdashe.top/Article/details/gthxkmhrtr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.smart0.xyz/Article/details/gtckneuzck.html

Ruby: obj.instance_variables
来源：http://dali.hnxiangtu.top/Article/details/gtowjbwgae.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hongshengwenyu.top/Article/details/gtdifughwa.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhoiltyw.html

H. 异常与错误处理
来源：http://dali.daxiang520.top/Article/details/gtpyetbpcs.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtbpawidvi.html

[H01] try / catch 基础
来源：http://dali.yanxiufei.cn/Article/details/gtkzfznsqe.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuxming.cn/Article/details/gtzagyzmij.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj202588.top/Article/details/gtmdghhumm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtoevemril.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gtgspssqik.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yvedp.cn/Article/details/gtryemsymh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.haohaochexian.top/Article/details/gtxnuzwenb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.9152youxi.cn/Article/details/gtqbsyuugm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cqqwz.cn/Article/details/gtkzsymnkr.html

[H02] finally / ensure 收尾
来源：http://dali.sweek.top/Article/details/gtnjjhgdjy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.smart0.xyz/Article/details/gtllqohpbc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtdljglzkl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtajyvjpbv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtusylkjpx.html


<!-- 参考信息 -->