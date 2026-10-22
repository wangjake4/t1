代发 wailian999

Ruby: s.lines
来源：http://dali.sufxvd.cn/Article/details/gtuhuykpyt.html

C#:   s.Split('\n')
来源：http://dali.jinqigufen.top/Article/details/gthukubsee.html

[E20] 判断字符串是否为空
来源：http://dali.jqgfzy.top/Article/details/gtfgvaauod.html

Py:   if not s:
来源：http://dali.snrcjt.cn/Article/details/gtnrqtefvb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenzaomai.com/Article/details/gtmtdpbhwv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.fengsongda.top/Article/details/gtnftrclxr.html

TS:   if (s === "") {}
来源：http://dali.hongshengwenyu.top/Article/details/gtkvbazczp.html

Java: if (s.isEmpty()) {}
来源：http://dali.dashuyun.cn/Article/details/gtkwndchxh.html

Go:   if s == "" {}
来源：http://dali.hywenlv.cn/Article/details/gtwvdsxdds.html

Ruby: if s.empty?
来源：http://dali.yueranfly.top/Article/details/gtwydnvzmq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gzhubu.top/Article/details/gtxntjnuro.html

[E21] 超长截断加省略号
来源：http://dali.ydzc1.top/Article/details/gtnbtekdge.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tian-w.cn/Article/details/gthgnvfdpk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtfmpxqqlw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtjclotbiu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtpvwzpctg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdcolnobw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.snrcjt.cn/Article/details/gtbamaaqgv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtjpqmsscu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtwadjzlgu.html

[E22] 字节长度与字符长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmimdmvjc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.bjfxy.top/Article/details/gtjkqzcdxg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtrloiwqpt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuxming.cn/Article/details/gtyujlxhst.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gtbszkfizk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gzhubu.top/Article/details/gtmorqqglf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.guowangkeji.top/Article/details/gtvwfghwqj.html

Ruby: s.bytesize;  s.length
来源：http://dali.jqgfzy.top/Article/details/gtnuttdovu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cucudq.cn/Article/details/gtippjnqyr.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gttziaikyc.html

F. 文件与目录
来源：http://dali.yj20258888.top/Article/details/gtwqkqrwny.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtglirktxg.html

[F01] 读取整个文件
来源：http://dali.cheryme.top/Article/details/gtgnyxnwfo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrsjanfz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtklpyhynw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ehwqpu.com/Article/details/gtklyrampw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gtirslligv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gttuqtecho.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yanxiufei.cn/Article/details/gtijmdkbwn.html

Ruby: File.read("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtfnlmtksq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtykbnvjza.html

[F02] 逐行读取文件
来源：http://dali.shangyingyoupin.top/Article/details/gtqfogdukp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yueranfly.top/Article/details/gtsyhpthfi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.andypj.xyz/Article/details/gtvbpnubrq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jiagoushi.top/Article/details/gtimkcepnb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gtordemyxs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hywenlv.cn/Article/details/gtterazhhd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ybcxt.top/Article/details/gtfecacegs.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hongshengwenyu.top/Article/details/gtgjkgnpqy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.vqdsnc.cn/Article/details/gtagtizrut.html

[F03] 写入文件（覆盖）
来源：http://dali.hywenlv.cn/Article/details/gtpgenmgwl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nanxinkj.top/Article/details/gtlymirvko.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.snrcjt.cn/Article/details/gthnedtbnv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cucudq.cn/Article/details/gtjavppwck.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gtxcaqlliq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.9152youxi.cn/Article/details/gttilrszym.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhengqikj.top/Article/details/gtaxjgvbmr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.9152youxi.cn/Article/details/gtxqxighsr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.pycfn.com/Article/details/gtazdtstib.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgyimaaux.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.snrcjt.cn/Article/details/gtffuzzgez.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gaohongyu789.top/Article/details/gtnshwzblv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgufenzy.top/Article/details/gtdxuzsfpd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zdqjudy.top/Article/details/gtcfhzozmx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.316326.xyz/Article/details/gtoqthukaj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.guowangkeji.top/Article/details/gtgbzpjbcm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.andypj.xyz/Article/details/gtyamqhvlx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hywenlv.cn/Article/details/gtauhgvbsz.html

[F05] 判断文件或目录是否存在
来源：http://dali.hnqzz.top/Article/details/gtrpfcyrmi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhoulong.xyz/Article/details/gtaybrrqfx.html

PHP:  file_exists("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtlgtokxdd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtulxbsgoi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtesggguvl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtiowgstym.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sweek.top/Article/details/gtfmheccvt.html

Ruby: File.exist?("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gthhxokxhs.html

C#:   File.Exists("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtfjqsdhls.html

[F06] 删除文件
来源：http://dali.gotoacloud.top/Article/details/gtmvywvrws.html

Py:   os.remove("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtcyobelag.html

PHP:  unlink("a.txt");
来源：http://dali.sweek.top/Article/details/gtjjztyhao.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtanljrcww.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtmcbjtmmn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtsvscbzoz.html

Go:   os.Remove("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtiucbnwjv.html

Ruby: File.delete("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtibpufxxb.html

C#:   File.Delete("a.txt");
来源：http://dali.cashguo.top/Article/details/gtgugmljzs.html

[F07] 创建目录（含多级）
来源：http://dali.gzhubu.top/Article/details/gtbdbnkhpw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sweek.top/Article/details/gtbaaphwfn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgufenzy.top/Article/details/gtemrtdmvs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gtmdbsfsiv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xylfe.cn/Article/details/gtfqrhndvs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.snrcjt.cn/Article/details/gtulemrifv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.redwolf501.top/Article/details/gtaecbjhts.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hysaishi.cn/Article/details/gtiuvazcbp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhiwuduotai.top/Article/details/gtzctteknn.html

[F08] 遍历目录
来源：http://dali.yonumen.top/Article/details/gtgpyqfmpu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjqcxnix.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.svipenyu.cn/Article/details/gtwlhjzxlo.html

JS:   fs.readdirSync("dir")
来源：http://dali.xinyue.icu/Article/details/gtotlukxgz.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtaaofzaog.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinqigufen.top/Article/details/gtxstfvrpv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cashguo.top/Article/details/gtnsvuidfv.html

Ruby: Dir.children("dir")
来源：http://dali.gotoacloud.top/Article/details/gtyvkjzmqe.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fzhhl.top/Article/details/gtxnlotcnt.html

[F09] 获取文件大小
来源：http://dali.haohaochexian.top/Article/details/gteyxygcjv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtbntktfdy.html

PHP:  filesize("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtlhsnafsf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gtbzxnmmcz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gotoacloud.top/Article/details/gtibxljkdk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtgersxgam.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangshuangyany.cn/Article/details/gtynqtgiug.html

Ruby: File.size("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtnrvsutwx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.mhx1999.top/Article/details/gtwrsrldws.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hywenlv.cn/Article/details/gtinhqzjsz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtekhgcgun.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj202588.top/Article/details/gtvfkkcmhb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtloecynkb.html

TS:   path.extname("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtbuqaeknn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yanxiufei.cn/Article/details/gtyzeaynbz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtqrhjjxio.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtmfkfjhfm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gteigpbsvz.html

[F11] 复制与移动文件
来源：http://dali.dashuyun.cn/Article/details/gtrdxovxzq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtfozimlxs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtkclycfqu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtokntwcdz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtpytqvihx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gotoacloud.top/Article/details/gthuktmjyd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhiwuduotai.top/Article/details/gtfxidettb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfbfvatu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tanke756.top/Article/details/gtabpjmiuz.html

[F12] CSV 读写
来源：http://dali.redwolf501.top/Article/details/gtaogmpvyk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jyoumei.cn/Article/details/gtbhrbifbj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nwbrower.top/Article/details/gtbbfbsmqa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yongpay.top/Article/details/gtswkxaipm.html

TS:   // 同上
来源：http://dali.hywenlv.cn/Article/details/gtdbsracql.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhengqikj.top/Article/details/gtdpfohfja.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hywenlv.cn/Article/details/gtucnjhiye.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sysykeji.top/Article/details/gtvermwfbp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dianchejie.cn/Article/details/gtpnfxbxdq.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtvlqozbnl.html

G. 面向对象
来源：http://dali.yanxiufei.cn/Article/details/gtbbeupybm.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtntggwgza.html

[G01] 定义类
来源：http://dali.bjfxy.top/Article/details/gtnkgdxuoa.html

Py:   class User: pass
来源：http://dali.ehwqpu.com/Article/details/gtbhiplgdx.html

PHP:  class User {}
来源：http://dali.dashuyun.cn/Article/details/gtarurayix.html

JS:   class User {}
来源：http://dali.shuidangran.top/Article/details/gthrtccsdw.html

TS:   class User { name: string = ""; }
来源：http://dali.jyoumei.cn/Article/details/gtsvajaydx.html

Java: class User {}
来源：http://dali.yvedp.cn/Article/details/gtbqicbaff.html

Go:   type User struct { Name string }
来源：http://dali.chenzaomai.com/Article/details/gtoekkajex.html

Ruby: class User; end
来源：http://dali.xylfe.cn/Article/details/gtahwpuypr.html

C#:   class User {}
来源：http://dali.ivvv.top/Article/details/gtjeecduzc.html

[G02] 构造函数
来源：http://dali.jianghu66.top/Article/details/gtfjxrcsos.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tanke756.top/Article/details/gtmdjfxkbg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuanzx.com/Article/details/gtpznwgxjj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gtzwnvkcyz.html

TS:   constructor(public name: string) {}
来源：http://dali.zhoulong.xyz/Article/details/gtrcnebklz.html

Java: User(String name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gtymhagsql.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.havefunace.top/Article/details/gtzuewsrkf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinqigufen.top/Article/details/gtplrtsunw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jianghu66.top/Article/details/gttocffbij.html

[G03] 实例属性
来源：http://dali.hywenlv.cn/Article/details/gtuspousmz.html

Py:   self.name = "x"
来源：http://dali.gzhubu.top/Article/details/gtejasyzcr.html

PHP:  public string $name = "x";
来源：http://dali.smart0.xyz/Article/details/gttdjgegwk.html

JS:   this.name = "x";
来源：http://dali.dashuyun.cn/Article/details/gtqtikztss.html

TS:   name: string = "x";
来源：http://dali.yongpay.top/Article/details/gtiqcwogdl.html

Java: private String name;
来源：http://dali.yueranfly.top/Article/details/gtcstemmsc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnxiangtu.top/Article/details/gtuykmspqg.html

Ruby: @name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gterxbuces.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ppjwa.cn/Article/details/gthyfcitjs.html

[G04] 定义方法
来源：http://dali.0kj1m.cn/Article/details/gtxggfptym.html

Py:   def greet(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gtywsqyohq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gtrjxgiekq.html

JS:   greet() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtqzhopqrr.html

TS:   greet(): string { return this.name; }
来源：http://dali.ivvv.top/Article/details/gttvunalxl.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwlbibtky.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gtptqiyiiu.html

Ruby: def greet; @name; end
来源：http://dali.chenzaomai.com/Article/details/gtpxsmwrmz.html

C#:   public string Greet() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gtksqmgddw.html

[G05] 继承
来源：http://dali.c1oappe.top/Article/details/gtrhdwkldd.html

Py:   class Admin(User): pass
来源：http://dali.aibaodan.cn/Article/details/gtdiladuif.html

PHP:  class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gthdekqzya.html

JS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtvihqlctx.html

TS:   class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gthqjwzjql.html

Java: class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtzzadcowe.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yvedp.cn/Article/details/gtebmilsve.html

Ruby: class Admin < User; end
来源：http://dali.9152youxi.cn/Article/details/gtnptzkjlf.html

C#:   class Admin : User {}
来源：http://dali.hfpthk.cn/Article/details/gtvmrtnfhe.html

[G06] 重写方法
来源：http://dali.cucudq.cn/Article/details/gtfircrwkw.html

Py:   def greet(self): return "admin"
来源：http://dali.tanke756.top/Article/details/gtwnhyiisb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gthcfyxqtr.html

JS:   greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtxnkgueei.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gtekkwloux.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtauanzxwi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhongyouzk.top/Article/details/gtavdvupyf.html

Ruby: def greet; "admin"; end
来源：http://dali.birdmap.top/Article/details/gtxystjats.html

C#:   public override string Greet() => "admin";
来源：http://dali.yongpay.top/Article/details/gtqsalcnwy.html

[G07] 调用父类方法
来源：http://dali.fzhhl.top/Article/details/gtjdwwfmnm.html

Py:   super().greet()
来源：http://dali.aizwys.cn/Article/details/gtggwisphi.html

PHP:  parent::greet();
来源：http://dali.andypj.xyz/Article/details/gtotonnwba.html

JS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gtdfngtdoz.html

TS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gtpgytksai.html

Java: super.greet();
来源：http://dali.hywenlv.cn/Article/details/gthjkqrjcw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinqigufen.top/Article/details/gtfgwxtrvz.html

Ruby: super
来源：http://dali.shzxlz.cn/Article/details/gtkpwbdmqj.html

C#:   base.Greet();
来源：http://dali.tanke756.top/Article/details/gtqweyaidr.html

[G08] 静态方法与属性
来源：http://dali.guowangkeji.top/Article/details/gtxglpqlts.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ehwqpu.com/Article/details/gtvzjzxcjq.html

PHP:  public static function f() {}
来源：http://dali.nwbrower.top/Article/details/gtycvqtsgy.html

JS:   static f() {}
来源：http://dali.kuanghao11.cn/Article/details/gtlwxcqjev.html

TS:   static f(): void {}
来源：http://dali.birdmap.top/Article/details/gtxsvkujrk.html

Java: static void f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtdtharmtr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tianlin.xyz/Article/details/gtqimadktx.html

Ruby: def self.f; end
来源：http://dali.zycfv.cn/Article/details/gtnggpsxug.html

C#:   public static void F() {}
来源：http://dali.fzhhl.top/Article/details/gtnzkvdzoc.html

[G09] 接口 / 抽象类
来源：http://dali.yanxiufei.cn/Article/details/gtcqqupedn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.fengsongda.top/Article/details/gtrvyuiqtn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyflgfgnr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jiagoushi.top/Article/details/gtrzjupvfb.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigufen.top/Article/details/gttwbnsdwm.html

Java: interface Shape { double area(); }
来源：http://dali.ivvv.top/Article/details/gtlkuwdrow.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.andypj.xyz/Article/details/gtbwtnayph.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zdqjudy.top/Article/details/gtkzvxzlef.html

C#:   interface IShape { double Area(); }
来源：http://dali.ppjwa.cn/Article/details/gtkpzftiwr.html

[G10] 访问控制
来源：http://dali.jinghuilouyu.cn/Article/details/gtaayarfsd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fzhhl.top/Article/details/gtpyzspdaf.html

PHP:  public / protected / private
来源：http://dali.iojbl.cn/Article/details/gttxssetgw.html

JS:   #private 字段；其余公开
来源：http://dali.zycfv.cn/Article/details/gtneyawhpr.html

TS:   public / protected / private
来源：http://dali.yonumen.top/Article/details/gtywpcozjd.html

Java: public / protected / private / 默认包级
来源：http://dali.redwolf501.top/Article/details/gtdasimprs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yuanzhike.top/Article/details/gtywupeabm.html

Ruby: public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gtomueaofq.html

C#:   public / protected / private / internal
来源：http://dali.hongshengwenyu.top/Article/details/gtobavuygz.html

[G11] getter / setter
来源：http://dali.xziqi.cn/Article/details/gtorpqtpaz.html

Py:   @property 与 @x.setter
来源：http://dali.yvedp.cn/Article/details/gtgvctzimw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gtrtucglhm.html

JS:   get name() { return this._name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtocopkbaw.html

TS:   get name(): string { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gtriinyptq.html

Java: public String getName() { return name; }
来源：http://dali.shuidangran.top/Article/details/gtstqrukvj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gtspjlfjyk.html

Ruby: attr_accessor :name
来源：http://dali.dashuyun.cn/Article/details/gtdvxpdlpx.html

C#:   public string Name { get; set; }
来源：http://dali.guannengcc.top/Article/details/gtupblvidf.html

[G12] 对象转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtmtudyyfj.html

Py:   def __str__(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gtqpdrgzpr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gtopvzroka.html

JS:   toString() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtqshrxnkk.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtcccozzps.html

Java: @Override public String toString() { return name; }
来源：http://dali.xinyue.icu/Article/details/gtxddrqpxa.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtlmupcxlg.html

Ruby: def to_s; @name; end
来源：http://dali.meibo888.top/Article/details/gtqeosvixb.html

C#:   public override string ToString() => Name;
来源：http://dali.xinyue.icu/Article/details/gtokcwqjjr.html

[G13] 判断对象类型
来源：http://dali.quarkkingdee.top/Article/details/gtktqwjhvl.html

Py:   isinstance(u, User)
来源：http://dali.xinyue.icu/Article/details/gtnnfaycyp.html

PHP:  $u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtvkcaqnwu.html

JS:   u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtjicdwfsq.html

TS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtzlfyzbwq.html

Java: u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtuflijbmy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.9152youxi.cn/Article/details/gtqkjyimgq.html

Ruby: u.is_a?(User)
来源：http://dali.gaohongyu789.top/Article/details/gtzdwxdyft.html

C#:   u is User
来源：http://dali.gzhubu.top/Article/details/gtydicotuj.html

[G14] 数据类 / record
来源：http://dali.jqgfzy.top/Article/details/gtrrutqicm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.c1oappe.top/Article/details/gtxsedvnbq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ywan-chungtsiang.top/Article/details/gtecjdstnn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hnxiangtu.top/Article/details/gtavtopgce.html

TS:   type User = { name: string; age: number };
来源：http://dali.ppjwa.cn/Article/details/gtbjmusbot.html

Java: record User(String name, int age) {}
来源：http://dali.daria6918.cn/Article/details/gtkufwehku.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aizwys.cn/Article/details/gtrgksrjvj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pengpengdd.cyou/Article/details/gtiejuhtfk.html

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgwkopzd.html

[G15] 枚举
来源：http://dali.nwbrower.top/Article/details/gtddtovxsx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinqigufen.top/Article/details/gtkursrmap.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxuanxn.top/Article/details/gtnqezucsz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.iojbl.cn/Article/details/gtkyhpbauh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gtyzslkcaa.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgfzy.top/Article/details/gtoalgzdic.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sweek.top/Article/details/gtqpeathem.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxinkj.top/Article/details/gtqvzhutwn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtorskxldk.html

[G16] 对象转数组 / 字典
来源：http://dali.zhiwuduotai.top/Article/details/gtiwgmcjxx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigfzy.top/Article/details/gtdvppjaip.html

PHP:  get_object_vars($obj);
来源：http://dali.gaohongyu789.top/Article/details/gtsncvedwa.html

JS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gteccbohsj.html

TS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gtcfnaupuz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sysykeji.top/Article/details/gtdmfqmzer.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.dashuyun.cn/Article/details/gtbuphpqsk.html

Ruby: obj.instance_variables
来源：http://dali.guowangkeji.top/Article/details/gtjylsicfl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gttzmnqmsq.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtnzxmyljf.html

H. 异常与错误处理
来源：http://dali.cdnleiting.top/Article/details/gtzrsbsvuz.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtwyadogbz.html

[H01] try / catch 基础
来源：http://dali.yj202588.top/Article/details/gtcwyijnxf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenjidiqi.icu/Article/details/gtxxqolern.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtursaburw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gtryvomuma.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gtwxiyvgkq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zdqjudy.top/Article/details/gtbdnjcukn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcdztace.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.daxiang520.top/Article/details/gtzosztowf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yongpay.top/Article/details/gtkuynqrmn.html

[H02] finally / ensure 收尾
来源：http://dali.316326.xyz/Article/details/gtccivrpmv.html


<!-- 参考信息 -->