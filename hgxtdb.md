代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.iojbl.cn/Article/details/gttwjvqlah.html

TS:   s.split(/\r?\n/)
来源：http://dali.andypj.xyz/Article/details/gtzqayjeqr.html

Java: s.lines().toList()
来源：http://dali.hfpthk.cn/Article/details/gtztycjnvd.html

Go:   strings.Split(s, "\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvaxhspa.html

Ruby: s.lines
来源：http://dali.iojbl.cn/Article/details/gtddpdshsd.html

C#:   s.Split('\n')
来源：http://dali.yuanzhike.top/Article/details/gtlnlqaikr.html

[E20] 判断字符串是否为空
来源：http://dali.gotoacloud.top/Article/details/gtiwoaecus.html

Py:   if not s:
来源：http://dali.wangdashe.top/Article/details/gtaogciswk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.haohaochexian.top/Article/details/gtlovfpfzl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhongyouzk.top/Article/details/gtmhwjgelf.html

TS:   if (s === "") {}
来源：http://dali.hywenlv.cn/Article/details/gtpfpestvs.html

Java: if (s.isEmpty()) {}
来源：http://dali.gzhubu.top/Article/details/gtqkmlfrkv.html

Go:   if s == "" {}
来源：http://dali.xuetiantiany.cn/Article/details/gtmrejkqlh.html

Ruby: if s.empty?
来源：http://dali.jinqigufen.top/Article/details/gtdxjssyka.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cheryme.top/Article/details/gtnoipmqfy.html

[E21] 超长截断加省略号
来源：http://dali.xuanzx.com/Article/details/gtsgtxnned.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cucudq.cn/Article/details/gtvkqxcrkf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtzwcfllza.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtteczmxye.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtwfsgbqyw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gthrfihaom.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.9152youxi.cn/Article/details/gtfmuzaycn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtgqaqqqtu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtklctsyis.html

[E22] 字节长度与字符长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaugjipxy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinqigfzy.top/Article/details/gtkywlhgcl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gtteizlmvb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtboqyuhwz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gtauwgcrym.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkeddqwku.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cheryme.top/Article/details/gtvoyvpihy.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gthouspbhd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.birdmap.top/Article/details/gtztxgarpx.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtezkhpghi.html

F. 文件与目录
来源：http://dali.ydzc1.top/Article/details/gtewovabbe.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtdsxobngx.html

[F01] 读取整个文件
来源：http://dali.jinqigufen.top/Article/details/gteakahwrg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yangfankeji.com/Article/details/gtjgmcalto.html

PHP:  file_get_contents("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtrmjcmhfk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fengsongda.top/Article/details/gtjqxsvplf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yongpay.top/Article/details/gttqbfkjiv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtyrxuyamq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yvedp.cn/Article/details/gtlleeqigw.html

Ruby: File.read("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtyksbuqnr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtfljaolge.html

[F02] 逐行读取文件
来源：http://dali.sysykeji.top/Article/details/gtiylwqdfu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nwbrower.top/Article/details/gttkozaxka.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nanxinkj.top/Article/details/gtqtujxqvq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cashguo.top/Article/details/gtwthqkbyy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gtrrewriig.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gtynlctsjc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shuidangran.top/Article/details/gtudjqbzsd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhongyouzk.top/Article/details/gtwhfzthsa.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.quarkkingdee.top/Article/details/gtrqejdjmh.html

[F03] 写入文件（覆盖）
来源：http://dali.pengpengdd.cyou/Article/details/gtkxtoentl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jiagoushi.top/Article/details/gtwfmcfjeo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.guannengcc.top/Article/details/gtjvfwdbkn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gtwxphfxyf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gtqzqiiszc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.0kj1m.cn/Article/details/gtzgphpxcz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hfpthk.cn/Article/details/gtwkjljvzc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.daxiang520.top/Article/details/gtecpiflbz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gtbtjfnvvi.html

[F04] 追加写入文件
来源：http://dali.nanxinkj.top/Article/details/gthiufbicb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj20258.top/Article/details/gtxpoqnfnw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gtrkjcfyaq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dashuyun.cn/Article/details/gtebsssnih.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daria6918.cn/Article/details/gtochzekal.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hfpthk.cn/Article/details/gtkbnsubfw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtmoyehxqr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuanzhike.top/Article/details/gtxgkxeymx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinqigfzy.top/Article/details/gthibtlmhd.html

[F05] 判断文件或目录是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gtobgtfzne.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guannengcc.top/Article/details/gtdaocjfki.html

PHP:  file_exists("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtaoowokxk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gthmpizblp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtckyolyvc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjmkgtkf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhengqikj.top/Article/details/gteixflhhw.html

Ruby: File.exist?("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtcmmictob.html

C#:   File.Exists("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwctrxijh.html

[F06] 删除文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgpmkvmtp.html

Py:   os.remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gtiqdkncop.html

PHP:  unlink("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtehirvwto.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtkzqffdtw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtfcxenvjp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtjyekuqgx.html

Go:   os.Remove("a.txt")
来源：http://dali.ivvv.top/Article/details/gtzkbgqvhg.html

Ruby: File.delete("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtlrhevusy.html

C#:   File.Delete("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtmwoaclji.html

[F07] 创建目录（含多级）
来源：http://dali.hywenlv.cn/Article/details/gtgkpkljhh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hywenlv.cn/Article/details/gtqtzktcri.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cucudq.cn/Article/details/gtxjqzbrgz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gtkdjainsu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmljyoktf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guannengcc.top/Article/details/gtkdxjoyik.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj20258888.top/Article/details/gtfvinkkrf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.0kj1m.cn/Article/details/gthvnduyos.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jyoumei.cn/Article/details/gtpusdyjgo.html

[F08] 遍历目录
来源：http://dali.sysykeji.top/Article/details/gtcvjklbrd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.andypj.xyz/Article/details/gtnurhroyw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shuidangran.top/Article/details/gtuqqtcmjc.html

JS:   fs.readdirSync("dir")
来源：http://dali.dianchejie.cn/Article/details/gtgdiqcpng.html

TS:   fs.readdirSync("dir")
来源：http://dali.snrcjt.cn/Article/details/gtsremrtmv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jyoumei.cn/Article/details/gtuzbuoozr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hfpthk.cn/Article/details/gtaokbdmch.html

Ruby: Dir.children("dir")
来源：http://dali.zhixingplan.top/Article/details/gtkwwxyfjk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hywenlv.cn/Article/details/gtkecolwwx.html

[F09] 获取文件大小
来源：http://dali.yvedp.cn/Article/details/gtgwswquoq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtnlkfqtxm.html

PHP:  filesize("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsijvlpng.html

JS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gtkoctqknq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.mhx1999.top/Article/details/gtisrjucax.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtxzwavrtq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yuanzhike.top/Article/details/gtgqwyhflj.html

Ruby: File.size("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtqrkrorcv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zdqjudy.top/Article/details/gtlccapque.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hammf.cn/Article/details/gtuvwahjmh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtnssqraso.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtqkpkizvq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtaffalwiu.html

TS:   path.extname("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtfphnqwjq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sweek.top/Article/details/gtettrfato.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtvhnwpiuc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtwnxdatkz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtadlssaon.html

[F11] 复制与移动文件
来源：http://dali.jqgufenzy.top/Article/details/gtlvsjotfn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtactaukad.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbydfpwb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gthzxumfau.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtuzjkhsha.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.redwolf501.top/Article/details/gtbpyfhwmq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.haohaochexian.top/Article/details/gtgxepzytu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtugseqxsr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.vqdsnc.cn/Article/details/gtjngbkidt.html

[F12] CSV 读写
来源：http://dali.0kj1m.cn/Article/details/gtthdnhcmd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinqigfzy.top/Article/details/gtibfplist.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhiwuduotai.top/Article/details/gtlkuwpfuo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cashguo.top/Article/details/gtgestbfjs.html

TS:   // 同上
来源：http://dali.ppjwa.cn/Article/details/gthsgsoarv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gaohongyu789.top/Article/details/gtnduvltuy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.mhx1999.top/Article/details/gtfytpnkmr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gogol.net.cn/Article/details/gtbqlkudid.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gotoacloud.top/Article/details/gtshncupwl.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gttgrpfbbt.html

G. 面向对象
来源：http://dali.ehwqpu.com/Article/details/gtueqwjuwk.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtlxqkwkkw.html

[G01] 定义类
来源：http://dali.haohaochexian.top/Article/details/gtmdlmcxmt.html

Py:   class User: pass
来源：http://dali.zhongyouzk.top/Article/details/gtiivhnhof.html

PHP:  class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtihgowyno.html

JS:   class User {}
来源：http://dali.mhx1999.top/Article/details/gtpcpngszn.html

TS:   class User { name: string = ""; }
来源：http://dali.vqdsnc.cn/Article/details/gtjlxijkyz.html

Java: class User {}
来源：http://dali.yangfankeji.com/Article/details/gtbyqgscdq.html

Go:   type User struct { Name string }
来源：http://dali.zdqjudy.top/Article/details/gtpphthvmp.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gtargoejlu.html

C#:   class User {}
来源：http://dali.tian-w.cn/Article/details/gtigqrryna.html

[G02] 构造函数
来源：http://dali.mhx1999.top/Article/details/gttpuksrnz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cashguo.top/Article/details/gtcpcqukyn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cucudq.cn/Article/details/gtznikraae.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.svipenyu.cn/Article/details/gthoyawuqe.html

TS:   constructor(public name: string) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtodhnskdt.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtyltjfxwz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cashguo.top/Article/details/gtymxdetxv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xuanzx.com/Article/details/gtivdutqgp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gotoacloud.top/Article/details/gtjpioseyd.html

[G03] 实例属性
来源：http://dali.sufxvd.cn/Article/details/gtvgrcfpno.html

Py:   self.name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gtrvaxhnon.html

PHP:  public string $name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtxhunkccw.html

JS:   this.name = "x";
来源：http://dali.smart0.xyz/Article/details/gttqzcbwfz.html

TS:   name: string = "x";
来源：http://dali.sxryk.cn/Article/details/gtdxqitpiy.html

Java: private String name;
来源：http://dali.svipenyu.cn/Article/details/gttwuesjct.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ivvv.top/Article/details/gtttbggdkx.html

Ruby: @name = "x"
来源：http://dali.ehwqpu.com/Article/details/gtvorrmpvz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hywenlv.cn/Article/details/gtfmccfxou.html

[G04] 定义方法
来源：http://dali.cashguo.top/Article/details/gtaldfrnpg.html

Py:   def greet(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gtivtjrjdd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gttscyajhb.html

JS:   greet() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtdrczinht.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxwbjqmw.html

Java: String greet() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtgufblgiy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtjhivplfy.html

Ruby: def greet; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gtutshswqk.html

C#:   public string Greet() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gtyvtyeyzy.html

[G05] 继承
来源：http://dali.xuanzx.com/Article/details/gtxoxnfqdd.html

Py:   class Admin(User): pass
来源：http://dali.aibaodan.cn/Article/details/gtirqgxffl.html

PHP:  class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtxhjbwyln.html

JS:   class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtkftblwxj.html

TS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtwvpnojjj.html

Java: class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gteutzzvvb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangtech.top/Article/details/gteulavcqw.html

Ruby: class Admin < User; end
来源：http://dali.ehwqpu.com/Article/details/gtbbqsjcqs.html

C#:   class Admin : User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtwfraixrs.html

[G06] 重写方法
来源：http://dali.zhiwuduotai.top/Article/details/gtuwizciku.html

Py:   def greet(self): return "admin"
来源：http://dali.guowangkeji.top/Article/details/gtysrojxtv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtluvltabf.html

JS:   greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtbhlsfvuj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtznegwjqp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtipjdscfn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangshuangyany.cn/Article/details/gtlfiwftcc.html

Ruby: def greet; "admin"; end
来源：http://dali.kuanghao11.cn/Article/details/gtszqjxykk.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhengqikj.top/Article/details/gtxtmkfcpn.html

[G07] 调用父类方法
来源：http://dali.chenjidiqi.icu/Article/details/gtghybowfn.html

Py:   super().greet()
来源：http://dali.pycfn.com/Article/details/gtocobzqif.html

PHP:  parent::greet();
来源：http://dali.cheryme.top/Article/details/gtreqtjrrc.html

JS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtbwrhlpfv.html

TS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gtmmoflwax.html

Java: super.greet();
来源：http://dali.ivvv.top/Article/details/gtaxoeulgb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xziqi.cn/Article/details/gtpsfwajhk.html

Ruby: super
来源：http://dali.sweek.top/Article/details/gtukwmnjjc.html

C#:   base.Greet();
来源：http://dali.hnxiangtu.top/Article/details/gtbxmwlurm.html

[G08] 静态方法与属性
来源：http://dali.daxiang520.top/Article/details/gttpwveeqg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnqzz.top/Article/details/gtuxgrmrej.html

PHP:  public static function f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtuboyfeqm.html

JS:   static f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyefryinv.html

TS:   static f(): void {}
来源：http://dali.yvedp.cn/Article/details/gtpdotldnh.html

Java: static void f() {}
来源：http://dali.dashuyun.cn/Article/details/gtvcnvuqwy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.haohaochexian.top/Article/details/gtxwimwsfl.html

Ruby: def self.f; end
来源：http://dali.cucudq.cn/Article/details/gtldwhikgi.html

C#:   public static void F() {}
来源：http://dali.aizwys.cn/Article/details/gtjftkdziw.html

[G09] 接口 / 抽象类
来源：http://dali.daxiang520.top/Article/details/gttinvadho.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yonumen.top/Article/details/gtajviyihk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.iojbl.cn/Article/details/gtfcgrbwks.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj20258.top/Article/details/gtnrzquwvt.html

TS:   interface Shape { area(): number; }
来源：http://dali.zycfv.cn/Article/details/gtfoxfmdyi.html

Java: interface Shape { double area(); }
来源：http://dali.dianchejie.cn/Article/details/gtyeocqlgc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvzrvvgig.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yueranfly.top/Article/details/gtgphjbxxz.html

C#:   interface IShape { double Area(); }
来源：http://dali.sysykeji.top/Article/details/gtlzkgvulp.html

[G10] 访问控制
来源：http://dali.fengsongda.top/Article/details/gtyhzagapf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhongyouzk.top/Article/details/gtwlxesxgf.html

PHP:  public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gtvjnubanq.html

JS:   #private 字段；其余公开
来源：http://dali.yongpay.top/Article/details/gtwrghocjm.html

TS:   public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtfkbsgxda.html

Java: public / protected / private / 默认包级
来源：http://dali.xinyue.icu/Article/details/gtgwyrifjj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guowangkeji.top/Article/details/gtrtopzctt.html

Ruby: public / protected / private
来源：http://dali.wangdashe.top/Article/details/gttvvvabml.html

C#:   public / protected / private / internal
来源：http://dali.nanxinkj.top/Article/details/gtyjhfwmjl.html

[G11] getter / setter
来源：http://dali.hywenlv.cn/Article/details/gtnjtzqbmm.html

Py:   @property 与 @x.setter
来源：http://dali.yongpay.top/Article/details/gtzvthwoca.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gttcdghajt.html

JS:   get name() { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gtxhyqdvdn.html

TS:   get name(): string { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gtwljmqfdr.html

Java: public String getName() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtsciufhua.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgibyyxaz.html

Ruby: attr_accessor :name
来源：http://dali.jinqigufen.top/Article/details/gtwkoismez.html

C#:   public string Name { get; set; }
来源：http://dali.nanxuanxn.top/Article/details/gtsypqmtiq.html

[G12] 对象转字符串
来源：http://dali.tianlin.xyz/Article/details/gtifhanaxe.html

Py:   def __str__(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gtetezbfbq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gtxlqtqiog.html

JS:   toString() { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtziwlwhlp.html

TS:   toString(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gthhzxkhxd.html

Java: @Override public String toString() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtsjciymjm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gtuaqmhoox.html

Ruby: def to_s; @name; end
来源：http://dali.nwbrower.top/Article/details/gtunwmhcuo.html

C#:   public override string ToString() => Name;
来源：http://dali.zhoulong.xyz/Article/details/gttesleibv.html

[G13] 判断对象类型
来源：http://dali.gogol.net.cn/Article/details/gtlritsqjo.html

Py:   isinstance(u, User)
来源：http://dali.vqdsnc.cn/Article/details/gtcjrypajt.html

PHP:  $u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gthaxbiwaj.html

JS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gttchdacmw.html

TS:   u instanceof User
来源：http://dali.ybcxt.top/Article/details/gteoqvyxxe.html

Java: u instanceof User
来源：http://dali.yongpay.top/Article/details/gtoyimwctm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jqgufenzy.top/Article/details/gtxyavvxuv.html

Ruby: u.is_a?(User)
来源：http://dali.yuxming.cn/Article/details/gtohujdhai.html

C#:   u is User
来源：http://dali.chenjidiqi.icu/Article/details/gtqhocxwlt.html

[G14] 数据类 / record
来源：http://dali.fengsongda.top/Article/details/gtrinrfuuj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nwbrower.top/Article/details/gttgrddcxb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.9152youxi.cn/Article/details/gtobiaycir.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gtastjaayb.html

TS:   type User = { name: string; age: number };
来源：http://dali.gotoacloud.top/Article/details/gteocwrgsl.html

Java: record User(String name, int age) {}
来源：http://dali.zhengqikj.top/Article/details/gtvmgcheti.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jlsjyb.cn/Article/details/gtgijltbye.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenjidiqi.icu/Article/details/gttwfdfalo.html

C#:   record User(string Name, int Age);
来源：http://dali.mhx1999.top/Article/details/gttivvllyt.html

[G15] 枚举
来源：http://dali.iojbl.cn/Article/details/gtfcqdpfvj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.dashuyun.cn/Article/details/gtnadhyslb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttimfiezy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrqcvglf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuanzx.com/Article/details/gtvnppwbfz.html

Java: enum Color { RED, GREEN }
来源：http://dali.snrcjt.cn/Article/details/gtdcynbvow.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sxryk.cn/Article/details/gtofesttze.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nwbrower.top/Article/details/gtwezvahws.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbdcqchn.html

[G16] 对象转数组 / 字典
来源：http://dali.hysaishi.cn/Article/details/gtrdigwgcb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.havefunace.top/Article/details/gtdwueiyur.html

PHP:  get_object_vars($obj);
来源：http://dali.ybcxt.top/Article/details/gtlagjafyq.html

JS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtraythuku.html

TS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gtgvcgtovl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.svipenyu.cn/Article/details/gtsfslovrc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ehwqpu.com/Article/details/gtunryuwzw.html

Ruby: obj.instance_variables
来源：http://dali.yangfankeji.com/Article/details/gtdnfktxln.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.daria6918.cn/Article/details/gtffumkqdj.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtxjdqnefz.html

H. 异常与错误处理
来源：http://dali.shzxlz.cn/Article/details/gtqtkgxhzy.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtrfadbavo.html

[H01] try / catch 基础
来源：http://dali.zhiwuduotai.top/Article/details/gtoxlnwasu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gaohongyu789.top/Article/details/gthbmwrtsg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shzxlz.cn/Article/details/gtvgibkdfx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gtcjiivwmu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gtifabmozh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gtwlmbrgyf.html


<!-- 参考信息 -->