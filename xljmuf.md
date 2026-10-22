代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jianghu66.top/Article/details/gtyujwuhrc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sweek.top/Article/details/gtahfhmgpn.html

TS:   if (s === "") {}
来源：http://dali.shanyushiyangtech.top/Article/details/gthwfbvrvm.html

Java: if (s.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gtceyhzuuq.html

Go:   if s == "" {}
来源：http://dali.zycfv.cn/Article/details/gtngvvoxbk.html

Ruby: if s.empty?
来源：http://dali.shangyingyoupin.top/Article/details/gtufdkbpqa.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtysiyeb.html

[E21] 超长截断加省略号
来源：http://dali.nwbrower.top/Article/details/gtfomnwraf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinqigufen.top/Article/details/gtktkwtkiz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtzgwnbbpy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtfvhyxxug.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtnjbeslhs.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gtqfdabdal.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj20258888.top/Article/details/gtuwmjfejb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtuxskhwgm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtrzgdaaog.html

[E22] 字节长度与字符长度
来源：http://dali.xinyue.icu/Article/details/gtwpnvaywo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqykiwidr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gtprphfgyx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hysaishi.cn/Article/details/gtpbohjlde.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenlongwang.top/Article/details/gtdtnmsbiy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.vqdsnc.cn/Article/details/gtmvvvsosr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.andypj.xyz/Article/details/gtcmvpebdx.html

Ruby: s.bytesize;  s.length
来源：http://dali.cucudq.cn/Article/details/gtxuhgcsdm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.fzhhl.top/Article/details/gtdrnenzuz.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtrkixusyr.html

F. 文件与目录
来源：http://dali.sweek.top/Article/details/gtxlhagybv.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtpssmvwuz.html

[F01] 读取整个文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmsrdkiey.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yuanzhike.top/Article/details/gtdakwojho.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtohgboxju.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sweek.top/Article/details/gthushgyvw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzuhjzkjr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtqoanrpmj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.feifeiyinyue.top/Article/details/gttmujpsmx.html

Ruby: File.read("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtpszrfyep.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tian-w.cn/Article/details/gthvaneabb.html

[F02] 逐行读取文件
来源：http://dali.yanxiufei.cn/Article/details/gthecanqcj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.redwolf501.top/Article/details/gtbadittel.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aizwys.cn/Article/details/gtrtdwqqqj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tian-w.cn/Article/details/gtfbyrsmmr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gtfzrhxcuk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ppjwa.cn/Article/details/gtktyymgfa.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj20258.top/Article/details/gtewfdeeyx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jianghu66.top/Article/details/gtzsngkzan.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dianchejie.cn/Article/details/gtgaqliqog.html

[F03] 写入文件（覆盖）
来源：http://dali.yuxming.cn/Article/details/gtbrbbagjm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.wangshuangyany.cn/Article/details/gtyxkrexej.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gtovqcgrfe.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gtcioorikj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gtajgavyja.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xinyue.icu/Article/details/gtocnwibmg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.guannengcc.top/Article/details/gtxngiosio.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tianlin.xyz/Article/details/gtmdrdqupq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gtzliubvyf.html

[F04] 追加写入文件
来源：http://dali.meibo888.top/Article/details/gtmrvihbzz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.guowangkeji.top/Article/details/gtyxmgobhc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.vqdsnc.cn/Article/details/gtrbadnpwh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yvedp.cn/Article/details/gtvjdwgknu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtbetkpotn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hfpthk.cn/Article/details/gtjwukohke.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtavsxnjow.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hywenlv.cn/Article/details/gtvgrqljjw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.pycfn.com/Article/details/gtcygugehc.html

[F05] 判断文件或目录是否存在
来源：http://dali.hnqzz.top/Article/details/gtpvhojseo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xinyue.icu/Article/details/gtfscrqayw.html

PHP:  file_exists("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gthojblxar.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtrvepgyey.html

TS:   fs.existsSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtbiioeaby.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtiwcyxnwz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgfzy.top/Article/details/gtwqoiuebl.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtceazgavl.html

C#:   File.Exists("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtavppkkgw.html

[F06] 删除文件
来源：http://dali.sysykeji.top/Article/details/gtwmmhtqly.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gtazucrnaw.html

PHP:  unlink("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtidzjxmdk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtbjdgnauj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtvsqsimdn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtqaatozux.html

Go:   os.Remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtrodinvqt.html

Ruby: File.delete("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtggpiqlvh.html

C#:   File.Delete("a.txt");
来源：http://dali.xziqi.cn/Article/details/gteaqnmqsy.html

[F07] 创建目录（含多级）
来源：http://dali.jianghu66.top/Article/details/gtubsnpwiq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenlongwang.top/Article/details/gtpdypddvm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.0kj1m.cn/Article/details/gtqlqpajxm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gtdtiwybpj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gotoacloud.top/Article/details/gtafhixozw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yvedp.cn/Article/details/gtlsatutdo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfripqpoj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yueranfly.top/Article/details/gtqtmpljwx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zdqjudy.top/Article/details/gtbheexjwf.html

[F08] 遍历目录
来源：http://dali.hysaishi.cn/Article/details/gthzgomfot.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.0kj1m.cn/Article/details/gtzdwjcvil.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xuetiantiany.cn/Article/details/gtvjfabafg.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenlongwang.top/Article/details/gtfmgmqewe.html

TS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gtkjzcmerz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gtdnqeccxw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zdqjudy.top/Article/details/gtzagvlypa.html

Ruby: Dir.children("dir")
来源：http://dali.yvedp.cn/Article/details/gtidrlcczc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gogol.net.cn/Article/details/gtyxxklzvm.html

[F09] 获取文件大小
来源：http://dali.zhixingplan.top/Article/details/gtbvpmsnyk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtjquuifkx.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtcvhfxxyh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gthwzhilqb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gtdcxvhkhm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtmiztyyfd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guowangkeji.top/Article/details/gtlqgouhne.html

Ruby: File.size("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtuchvvkpm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gotoacloud.top/Article/details/gtgithbpxm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgfzy.top/Article/details/gtmnpiyzrb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtresobivx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yueranfly.top/Article/details/gtshyelopz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtmyxsqeds.html

TS:   path.extname("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqdfyzrr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.haohaochexian.top/Article/details/gtewgnsevu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtxwcvkvtw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtkauptaht.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gterrhyrmi.html

[F11] 复制与移动文件
来源：http://dali.c1oappe.top/Article/details/gtmmocxigp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtbpimwccg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhengqikj.top/Article/details/gtcffeuqnm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gticunczmi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtbtlpehxn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmalkzaan.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.quarkkingdee.top/Article/details/gtivozcwpq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtxitrmqcj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cashguo.top/Article/details/gtciqxviyw.html

[F12] CSV 读写
来源：http://dali.zhiwuduotai.top/Article/details/gtpqrwfwud.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.redwolf501.top/Article/details/gtlkkdyoln.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hongshengwenyu.top/Article/details/gtlakkvrbv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pengpengdd.cyou/Article/details/gtborvxuik.html

TS:   // 同上
来源：http://dali.redwolf501.top/Article/details/gttxsxrzoq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuetiantiany.cn/Article/details/gtvsjcgkju.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ybcxt.top/Article/details/gtmqvwnjmk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhongyouzk.top/Article/details/gtyvjxhptt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.pycfn.com/Article/details/gtbtvtbfbi.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtozhzvdru.html

G. 面向对象
来源：http://dali.cdnleiting.top/Article/details/gtjoimlwrd.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gttsifpvoy.html

[G01] 定义类
来源：http://dali.snrcjt.cn/Article/details/gthqvaqsil.html

Py:   class User: pass
来源：http://dali.hnxiangtu.top/Article/details/gtbchmacaq.html

PHP:  class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtylixftvr.html

JS:   class User {}
来源：http://dali.birdmap.top/Article/details/gtfkxawirl.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gtpxjunnex.html

Java: class User {}
来源：http://dali.haohaochexian.top/Article/details/gtiihoalkq.html

Go:   type User struct { Name string }
来源：http://dali.yonumen.top/Article/details/gtszhrlhbw.html

Ruby: class User; end
来源：http://dali.zhixingplan.top/Article/details/gtyubrqvmm.html

C#:   class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtpeeizflh.html

[G02] 构造函数
来源：http://dali.cdnleiting.top/Article/details/gtdbhuxldf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zdqjudy.top/Article/details/gtulgasldl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gzhubu.top/Article/details/gtdeesqsor.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gtgxvtlewh.html

TS:   constructor(public name: string) {}
来源：http://dali.shuidangran.top/Article/details/gtidojhgwe.html

Java: User(String name) { this.name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gtkcfanizj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.iojbl.cn/Article/details/gtvuncrmmu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtxiokomlj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sufxvd.cn/Article/details/gttlxaeqxv.html

[G03] 实例属性
来源：http://dali.jianghu66.top/Article/details/gtqmwvlpsm.html

Py:   self.name = "x"
来源：http://dali.ehwqpu.com/Article/details/gthyiivovm.html

PHP:  public string $name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtwjtuuard.html

JS:   this.name = "x";
来源：http://dali.dashuyun.cn/Article/details/gtxlikfqkr.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhvgfist.html

Java: private String name;
来源：http://dali.svipenyu.cn/Article/details/gtmneiwmoa.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhengqikj.top/Article/details/gtvleyeaxs.html

Ruby: @name = "x"
来源：http://dali.shuidangran.top/Article/details/gtegeaqvni.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdjgagar.html

[G04] 定义方法
来源：http://dali.yueranfly.top/Article/details/gtnnozwhbz.html

Py:   def greet(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gtphnrotft.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmobslzt.html

JS:   greet() { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtdniwnbzs.html

TS:   greet(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtecywaddp.html

Java: String greet() { return name; }
来源：http://dali.redwolf501.top/Article/details/gtaybaafpc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gtonginqks.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpyeugwoz.html

C#:   public string Greet() => Name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtgeonlbga.html

[G05] 继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajwpjdua.html

Py:   class Admin(User): pass
来源：http://dali.snrcjt.cn/Article/details/gtmsmqjmqt.html

PHP:  class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtcdhmszfp.html

JS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtqxibcqcx.html

TS:   class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtnvkgnitm.html

Java: class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtelsguopj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zycfv.cn/Article/details/gtmeecibfa.html

Ruby: class Admin < User; end
来源：http://dali.hfpthk.cn/Article/details/gtawambugt.html

C#:   class Admin : User {}
来源：http://dali.nanxuanxn.top/Article/details/gtkixcgljt.html

[G06] 重写方法
来源：http://dali.hnqzz.top/Article/details/gtctduqhcr.html

Py:   def greet(self): return "admin"
来源：http://dali.9152youxi.cn/Article/details/gtndrrylzk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtfcyohrax.html

JS:   greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtxzhmianp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtlyzbylgr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtgztefonj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.iojbl.cn/Article/details/gtthfshonn.html

Ruby: def greet; "admin"; end
来源：http://dali.xuanzx.com/Article/details/gtbngltojv.html

C#:   public override string Greet() => "admin";
来源：http://dali.ivvv.top/Article/details/gtezdofghq.html

[G07] 调用父类方法
来源：http://dali.ybcxt.top/Article/details/gtbgreanfk.html

Py:   super().greet()
来源：http://dali.hnxiangtu.top/Article/details/gttzoynjey.html

PHP:  parent::greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtnqtohsuo.html

JS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gtwsljfvqs.html

TS:   super.greet();
来源：http://dali.wangdashe.top/Article/details/gtakrrumhb.html

Java: super.greet();
来源：http://dali.xziqi.cn/Article/details/gtikqzdcqb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yvedp.cn/Article/details/gtwrmyqyps.html

Ruby: super
来源：http://dali.zhixingplan.top/Article/details/gthgmgzrwz.html

C#:   base.Greet();
来源：http://dali.xuanzx.com/Article/details/gtazabrgbz.html

[G08] 静态方法与属性
来源：http://dali.chenzaomai.com/Article/details/gtdjoiftvv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnxiangtu.top/Article/details/gtfruziwaa.html

PHP:  public static function f() {}
来源：http://dali.snrcjt.cn/Article/details/gtvwodhuhz.html

JS:   static f() {}
来源：http://dali.hammf.cn/Article/details/gtoxmmklts.html

TS:   static f(): void {}
来源：http://dali.sufxvd.cn/Article/details/gtrcenfdes.html

Java: static void f() {}
来源：http://dali.kuanghao11.cn/Article/details/gtzilobavh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sufxvd.cn/Article/details/gtbwrzvzbg.html

Ruby: def self.f; end
来源：http://dali.yongpay.top/Article/details/gtptoqxtsm.html

C#:   public static void F() {}
来源：http://dali.yangfankeji.com/Article/details/gtumokjnui.html

[G09] 接口 / 抽象类
来源：http://dali.pengpengdd.cyou/Article/details/gtscwfpkgx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pycfn.com/Article/details/gtszfxpaqr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hywenlv.cn/Article/details/gtnfneubgf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xuanzx.com/Article/details/gtdmabhvgq.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmepyrkmw.html

Java: interface Shape { double area(); }
来源：http://dali.hfpthk.cn/Article/details/gtvphsixay.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dashuyun.cn/Article/details/gtmaqommgh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daxiang520.top/Article/details/gtgyaiepqu.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxinkj.top/Article/details/gtqdaqsokj.html

[G10] 访问控制
来源：http://dali.xuetiantiany.cn/Article/details/gtphhpbddl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guannengcc.top/Article/details/gtimmkrmsv.html

PHP:  public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtlcvygqix.html

JS:   #private 字段；其余公开
来源：http://dali.cashguo.top/Article/details/gtkxgvmtug.html

TS:   public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtbxlkbdsz.html

Java: public / protected / private / 默认包级
来源：http://dali.shzxlz.cn/Article/details/gtfjalobpm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shangyingyoupin.top/Article/details/gtygptnxpc.html

Ruby: public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gtzimdnvuw.html

C#:   public / protected / private / internal
来源：http://dali.jqgfzy.top/Article/details/gtvbezkewn.html

[G11] getter / setter
来源：http://dali.yanxiufei.cn/Article/details/gtdsqegigl.html

Py:   @property 与 @x.setter
来源：http://dali.yuxming.cn/Article/details/gtyywtqaam.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gtzrftmjda.html

JS:   get name() { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtjonectbc.html

TS:   get name(): string { return this._name; }
来源：http://dali.nwbrower.top/Article/details/gtmnejbkbe.html

Java: public String getName() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtsctngmhr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtdiiazqzq.html

Ruby: attr_accessor :name
来源：http://dali.jianghu66.top/Article/details/gtdylcumgr.html

C#:   public string Name { get; set; }
来源：http://dali.bjfxy.top/Article/details/gtxgihnslh.html

[G12] 对象转字符串
来源：http://dali.yj20258.top/Article/details/gtioqxaupc.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258888.top/Article/details/gtdtdyrwzl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gtbbjbraly.html

JS:   toString() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbylqiaff.html

TS:   toString(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtyhgugbuw.html

Java: @Override public String toString() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtjkgxivrg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtlonbxzbq.html

Ruby: def to_s; @name; end
来源：http://dali.fengsongda.top/Article/details/gtessgsqkj.html

C#:   public override string ToString() => Name;
来源：http://dali.jyoumei.cn/Article/details/gtdvjesybp.html

[G13] 判断对象类型
来源：http://dali.feifeiyinyue.top/Article/details/gtidivmjai.html

Py:   isinstance(u, User)
来源：http://dali.yongpay.top/Article/details/gttgcmfoao.html

PHP:  $u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtasolqfxn.html

JS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtlcwjqtao.html

TS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gtnrzoyxhk.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gtwsmoonxm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrbalcfpk.html

Ruby: u.is_a?(User)
来源：http://dali.hnqzz.top/Article/details/gtktfhgdfc.html

C#:   u is User
来源：http://dali.gogol.net.cn/Article/details/gtyhgcatwo.html

[G14] 数据类 / record
来源：http://dali.zdqjudy.top/Article/details/gtkpcgznrb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yvedp.cn/Article/details/gtxezczduy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ydzc1.top/Article/details/gtqcahdpcs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hammf.cn/Article/details/gtksirsfij.html

TS:   type User = { name: string; age: number };
来源：http://dali.pycfn.com/Article/details/gtmjklfkvr.html

Java: record User(String name, int age) {}
来源：http://dali.tanke756.top/Article/details/gtflotesjy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yvedp.cn/Article/details/gtmycczesl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuanzhike.top/Article/details/gtnptsdigy.html

C#:   record User(string Name, int Age);
来源：http://dali.sufxvd.cn/Article/details/gtkxfatjle.html

[G15] 枚举
来源：http://dali.shuidangran.top/Article/details/gtwadopnal.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jlsjyb.cn/Article/details/gtdhqdzohj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpkfhxdkq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tanke756.top/Article/details/gtpmdlvgac.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gtqovdxrqv.html

Java: enum Color { RED, GREEN }
来源：http://dali.hfpthk.cn/Article/details/gtopxaldzu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xziqi.cn/Article/details/gtoofgpqjn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj202588.top/Article/details/gtvvfhfnqr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtxdsucbfi.html

[G16] 对象转数组 / 字典
来源：http://dali.jlsjyb.cn/Article/details/gtydkpvigp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.mhx1999.top/Article/details/gttmdyltts.html

PHP:  get_object_vars($obj);
来源：http://dali.ppjwa.cn/Article/details/gtblynewxy.html

JS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gtlfsmjwci.html

TS:   Object.entries(obj)
来源：http://dali.redwolf501.top/Article/details/gthrvtqhbl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.vqdsnc.cn/Article/details/gtwuqlichc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtupldyfcx.html

Ruby: obj.instance_variables
来源：http://dali.haohaochexian.top/Article/details/gtgluoigoh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.mhx1999.top/Article/details/gtlrcvribc.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtymhhaqhj.html

H. 异常与错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfjcxrdic.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtzyiyetfc.html

[H01] try / catch 基础
来源：http://dali.daria6918.cn/Article/details/gtpkggojlm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpfhhizt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhoulong.xyz/Article/details/gtahylzelg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gtwcjwidrq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gtljukpnuy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.316326.xyz/Article/details/gtfhxogqrg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxinkj.top/Article/details/gtgjqvvxyo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj202588.top/Article/details/gtayaxnowh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zycfv.cn/Article/details/gtxijgkeat.html

[H02] finally / ensure 收尾
来源：http://dali.cqqwz.cn/Article/details/gtuvlzeeyj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gotoacloud.top/Article/details/gtrafghdki.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtntloiisj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtxrwsnaod.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gteeyoavzv.html


<!-- 参考信息 -->