代发 wailian999

Ruby: s.lines
来源：http://dali.shanyushiyangtech.top/Article/details/gtwivgrvvm.html

C#:   s.Split('\n')
来源：http://dali.iojbl.cn/Article/details/gthbbeqeja.html

[E20] 判断字符串是否为空
来源：http://dali.mhx1999.top/Article/details/gtfhzwsifb.html

Py:   if not s:
来源：http://dali.yj20258888.top/Article/details/gtcrrxndgd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.aizwys.cn/Article/details/gtbwenoywx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yvedp.cn/Article/details/gtbaehmode.html

TS:   if (s === "") {}
来源：http://dali.hysaishi.cn/Article/details/gtautzkcuy.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinqigfzy.top/Article/details/gtcrlleglh.html

Go:   if s == "" {}
来源：http://dali.birdmap.top/Article/details/gtdlmzbsli.html

Ruby: if s.empty?
来源：http://dali.zhiwuduotai.top/Article/details/gtctnstqkb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dianchejie.cn/Article/details/gtbktwxnyq.html

[E21] 超长截断加省略号
来源：http://dali.yuxming.cn/Article/details/gtwztcrwxv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj20258888.top/Article/details/gtvbdgdfgc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtzudclipz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtrztaktpg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtjtqxovig.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtymjlrpyl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.bjfxy.top/Article/details/gtdxvflqqv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtwdzycqpk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtjzkdezqe.html

[E22] 字节长度与字符长度
来源：http://dali.shangyingyoupin.top/Article/details/gtykyhfntx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daxiang520.top/Article/details/gtbmdpteow.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtaxklvrfk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yvedp.cn/Article/details/gthqalqfas.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daxiang520.top/Article/details/gtbomxjscp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sysykeji.top/Article/details/gtusdxqmki.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yongpay.top/Article/details/gtadwobwxi.html

Ruby: s.bytesize;  s.length
来源：http://dali.guannengcc.top/Article/details/gtdoqhugsr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.svipenyu.cn/Article/details/gtppincdjc.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtytogqwdj.html

F. 文件与目录
来源：http://dali.cheryme.top/Article/details/gtknqswlmo.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtwjtbbtls.html

[F01] 读取整个文件
来源：http://dali.feifeiyinyue.top/Article/details/gtcaleumui.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gzhubu.top/Article/details/gtaaoshwlh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.316326.xyz/Article/details/gtayittwsl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.havefunace.top/Article/details/gtavhpftee.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.fzhhl.top/Article/details/gtjcalirrt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtbptcytip.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrfhchnmu.html

Ruby: File.read("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtlpuwetxi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtwhwfcvuf.html

[F02] 逐行读取文件
来源：http://dali.sufxvd.cn/Article/details/gtdobgmznb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkobdlgbw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhixingplan.top/Article/details/gtsisdqllo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.iojbl.cn/Article/details/gtpfbrqatc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdbsfnin.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.quarkkingdee.top/Article/details/gtcsfcfedx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhongyouzk.top/Article/details/gtfxefcvan.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj20258.top/Article/details/gtikqpmhbm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.wangshuangyany.cn/Article/details/gtnbnkybhn.html

[F03] 写入文件（覆盖）
来源：http://dali.ybcxt.top/Article/details/gtujhmqfsk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yuxming.cn/Article/details/gtiyunultr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zycfv.cn/Article/details/gtdfqavxuf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tanke756.top/Article/details/gtzdgtsabn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gtxktdwsbr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.guowangkeji.top/Article/details/gthlyynwua.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.fengsongda.top/Article/details/gtzmielnha.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tian-w.cn/Article/details/gtxeakdtrm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guannengcc.top/Article/details/gtcjafzqon.html

[F04] 追加写入文件
来源：http://dali.svipenyu.cn/Article/details/gtchqqeycc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hywenlv.cn/Article/details/gtuuwnzjny.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhixingplan.top/Article/details/gtvltmfyvf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ybcxt.top/Article/details/gtmsokqqmh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gtzhnjvjzv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxriixcez.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jqgfzy.top/Article/details/gthtixddce.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258888.top/Article/details/gtgtsfkhir.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.316326.xyz/Article/details/gtlbhihbbw.html

[F05] 判断文件或目录是否存在
来源：http://dali.yonumen.top/Article/details/gtohqydtud.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cdnleiting.top/Article/details/gtqywljvfy.html

PHP:  file_exists("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtiweqnnod.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtlzvvoloo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtenihthdj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtbuqpvhjb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daria6918.cn/Article/details/gtrkmrodls.html

Ruby: File.exist?("a.txt")
来源：http://dali.birdmap.top/Article/details/gtcjeeedop.html

C#:   File.Exists("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtetmaeazh.html

[F06] 删除文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofiwsvif.html

Py:   os.remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtxbvbxlqz.html

PHP:  unlink("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtezsrsyax.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtoqjdnjyq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtnankmpse.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtpfjhvbxd.html

Go:   os.Remove("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtysiydszh.html

Ruby: File.delete("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtokuyrmhp.html

C#:   File.Delete("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtrxfcmnkl.html

[F07] 创建目录（含多级）
来源：http://dali.chenlongwang.top/Article/details/gtoqjglrji.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.havefunace.top/Article/details/gtcqyqqxao.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhhlrjue.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.andypj.xyz/Article/details/gttdqncaby.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigufen.top/Article/details/gtmszraqmx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cqqwz.cn/Article/details/gtdhumookq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.0kj1m.cn/Article/details/gtukfzkwgg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.vqdsnc.cn/Article/details/gtndzokthx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gttdklhyso.html

[F08] 遍历目录
来源：http://dali.aizwys.cn/Article/details/gtejpsivxg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenlongwang.top/Article/details/gtcqcuwnqk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfsunckzd.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gtvohqolsc.html

TS:   fs.readdirSync("dir")
来源：http://dali.ehwqpu.com/Article/details/gtcxvomkzu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxuanxn.top/Article/details/gtopfaaqws.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guowangkeji.top/Article/details/gtuaydndza.html

Ruby: Dir.children("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgnacemgh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtbhsmhzkl.html

[F09] 获取文件大小
来源：http://dali.jianghu66.top/Article/details/gtmcyuntzt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtpimeaklm.html

PHP:  filesize("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtzlirffgs.html

JS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gtxklepcho.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gtovfxfxna.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtmkjdatdy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.vqdsnc.cn/Article/details/gtqgqygirb.html

Ruby: File.size("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtmvfrrnzg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj202588.top/Article/details/gtedgryqit.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hongshengwenyu.top/Article/details/gtbhdwlnav.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtqmmqoaki.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tian-w.cn/Article/details/gtkjxaidlf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtseeuvdhb.html

TS:   path.extname("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtkioakflh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yanxiufei.cn/Article/details/gtwfcckwdj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gttfhyxucw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtvhdwfqav.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtoyuychmr.html

[F11] 复制与移动文件
来源：http://dali.hysaishi.cn/Article/details/gthoiglhkn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gtdmuojlvq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangdashe.top/Article/details/gtpgxmeada.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtqteqnrll.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtvnitoaiu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.haohaochexian.top/Article/details/gtbwrkmwtu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daxiang520.top/Article/details/gtydufiics.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtdbaefzmj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ybcxt.top/Article/details/gtxqehphts.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gtfgfysehs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenlongwang.top/Article/details/gtvmfaywzt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yuxming.cn/Article/details/gtkkxznpyh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhiwuduotai.top/Article/details/gtiyeqlxjm.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gtnyrlzfwr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhongyouzk.top/Article/details/gttaeazgeb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.meibo888.top/Article/details/gtdpczycso.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.mhx1999.top/Article/details/gtoymwohiy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.guowangkeji.top/Article/details/gtabekrjvy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtwmvbrbaw.html

G. 面向对象
来源：http://dali.havefunace.top/Article/details/gtowkbprty.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtxmljzhys.html

[G01] 定义类
来源：http://dali.yj20258888.top/Article/details/gtxqnojqfl.html

Py:   class User: pass
来源：http://dali.shanyushiyangtech.top/Article/details/gthvydbhbw.html

PHP:  class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtyjdivxdd.html

JS:   class User {}
来源：http://dali.redwolf501.top/Article/details/gtlrodkitj.html

TS:   class User { name: string = ""; }
来源：http://dali.yongpay.top/Article/details/gtutuxxewr.html

Java: class User {}
来源：http://dali.havefunace.top/Article/details/gtynvjivov.html

Go:   type User struct { Name string }
来源：http://dali.havefunace.top/Article/details/gtcmwgjlgy.html

Ruby: class User; end
来源：http://dali.gogol.net.cn/Article/details/gtnesddhud.html

C#:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gtyjvdyzyx.html

[G02] 构造函数
来源：http://dali.ybcxt.top/Article/details/gtzhqvbjjg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cucudq.cn/Article/details/gtcpttfhnr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hysaishi.cn/Article/details/gtchyzcmwv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtpgfnwjsz.html

TS:   constructor(public name: string) {}
来源：http://dali.zycfv.cn/Article/details/gtsvlpjhne.html

Java: User(String name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtyayjpzlk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fengsongda.top/Article/details/gtkftpmnav.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aizwys.cn/Article/details/gtrwbpnpgw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yvedp.cn/Article/details/gtysivusch.html

[G03] 实例属性
来源：http://dali.cqqwz.cn/Article/details/gtxuogdsup.html

Py:   self.name = "x"
来源：http://dali.svipenyu.cn/Article/details/gtaaazzlvx.html

PHP:  public string $name = "x";
来源：http://dali.jqgfzy.top/Article/details/gtqrujqlle.html

JS:   this.name = "x";
来源：http://dali.zhengqikj.top/Article/details/gtkjgglafp.html

TS:   name: string = "x";
来源：http://dali.jqgfzy.top/Article/details/gtqtobuoln.html

Java: private String name;
来源：http://dali.nwbrower.top/Article/details/gtnpaoqppk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yvedp.cn/Article/details/gteeofinlf.html

Ruby: @name = "x"
来源：http://dali.aizwys.cn/Article/details/gtgcbvwfbl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aizwys.cn/Article/details/gtdlsykzhn.html

[G04] 定义方法
来源：http://dali.fzhhl.top/Article/details/gtgllnzdvs.html

Py:   def greet(self): return self.name
来源：http://dali.yj20258888.top/Article/details/gtwybmclag.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gtgwovxpan.html

JS:   greet() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtcycrvueu.html

TS:   greet(): string { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtppgycafv.html

Java: String greet() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtqegeipwc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvaoiubf.html

Ruby: def greet; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gtjjulpvlg.html

C#:   public string Greet() => Name;
来源：http://dali.shzxlz.cn/Article/details/gtugfuotmm.html

[G05] 继承
来源：http://dali.yangfankeji.com/Article/details/gttqoyptvo.html

Py:   class Admin(User): pass
来源：http://dali.svipenyu.cn/Article/details/gtmlhfxqna.html

PHP:  class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtdaxwgibs.html

JS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtfrfoawdy.html

TS:   class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtonfncuoq.html

Java: class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwrztsrj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pycfn.com/Article/details/gtjndlvuxn.html

Ruby: class Admin < User; end
来源：http://dali.sweek.top/Article/details/gtkxkhoylh.html

C#:   class Admin : User {}
来源：http://dali.yvedp.cn/Article/details/gtpalzjmat.html

[G06] 重写方法
来源：http://dali.snrcjt.cn/Article/details/gtwxxglxmk.html

Py:   def greet(self): return "admin"
来源：http://dali.guannengcc.top/Article/details/gtbncniyqn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtxvyuprhr.html

JS:   greet() { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtsxezwpiy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtslgyscil.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtqvsbqwmc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sysykeji.top/Article/details/gtcdojpggh.html

Ruby: def greet; "admin"; end
来源：http://dali.zdqjudy.top/Article/details/gtfnfohnrd.html

C#:   public override string Greet() => "admin";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrnttbyzh.html

[G07] 调用父类方法
来源：http://dali.jlsjyb.cn/Article/details/gtiircoqib.html

Py:   super().greet()
来源：http://dali.wangdashe.top/Article/details/gtaczckjus.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqaynctn.html

JS:   super.greet();
来源：http://dali.sweek.top/Article/details/gtudchtvgg.html

TS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gtvaosnivh.html

Java: super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtflzxtaqp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gotoacloud.top/Article/details/gtisfmirym.html

Ruby: super
来源：http://dali.tanke756.top/Article/details/gthqmlsowg.html

C#:   base.Greet();
来源：http://dali.c1oappe.top/Article/details/gtilbknhhy.html

[G08] 静态方法与属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrqdfhcw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hongshengwenyu.top/Article/details/gtcnfsihva.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gtjmrnywxh.html

JS:   static f() {}
来源：http://dali.yangfankeji.com/Article/details/gtejirqqmr.html

TS:   static f(): void {}
来源：http://dali.jianghu66.top/Article/details/gtgrgwgwll.html

Java: static void f() {}
来源：http://dali.xziqi.cn/Article/details/gtovjdjisd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cucudq.cn/Article/details/gtnkdwpwky.html

Ruby: def self.f; end
来源：http://dali.wangdashe.top/Article/details/gtewaluqpu.html

C#:   public static void F() {}
来源：http://dali.andypj.xyz/Article/details/gtgqggjgvt.html

[G09] 接口 / 抽象类
来源：http://dali.shanyushiyangtech.top/Article/details/gtvavobnzj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yonumen.top/Article/details/gtmjntbhfe.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.0kj1m.cn/Article/details/gtvppkxpos.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xuanzx.com/Article/details/gtktnisxdd.html

TS:   interface Shape { area(): number; }
来源：http://dali.ehwqpu.com/Article/details/gtnydiwaft.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigufen.top/Article/details/gtkxnzpxot.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenjidiqi.icu/Article/details/gtubfjecsr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.c1oappe.top/Article/details/gtnhbjiire.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtcgvryjzh.html

[G10] 访问控制
来源：http://dali.sysykeji.top/Article/details/gtfhfhziry.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhiwuduotai.top/Article/details/gtltspaqpc.html

PHP:  public / protected / private
来源：http://dali.ivvv.top/Article/details/gtyjptqnta.html

JS:   #private 字段；其余公开
来源：http://dali.nanxinkj.top/Article/details/gtqyqrlqze.html

TS:   public / protected / private
来源：http://dali.tanke756.top/Article/details/gtoehlyztt.html

Java: public / protected / private / 默认包级
来源：http://dali.chenjidiqi.icu/Article/details/gtrqutthxs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhoulong.xyz/Article/details/gtgkpjzfuq.html

Ruby: public / protected / private
来源：http://dali.yvedp.cn/Article/details/gtguwtdwxd.html

C#:   public / protected / private / internal
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmazsbjv.html

[G11] getter / setter
来源：http://dali.fzhhl.top/Article/details/gtfvccoajc.html

Py:   @property 与 @x.setter
来源：http://dali.nanxuanxn.top/Article/details/gtilquvyob.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtebygilbx.html

JS:   get name() { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gtkejnkvmh.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gtrxmqskhu.html

Java: public String getName() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtyjmfitpv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtbbhffhrm.html

Ruby: attr_accessor :name
来源：http://dali.jinqigfzy.top/Article/details/gtkplbdtgj.html

C#:   public string Name { get; set; }
来源：http://dali.yanxiufei.cn/Article/details/gtnrnzfprc.html

[G12] 对象转字符串
来源：http://dali.316326.xyz/Article/details/gtaapegqii.html

Py:   def __str__(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gtviyrsdwo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtoyiswaau.html

JS:   toString() { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtifbrqxjt.html

TS:   toString(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtjfyrdias.html

Java: @Override public String toString() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtwhtsobxf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gteeswmxpi.html

Ruby: def to_s; @name; end
来源：http://dali.zhiwuduotai.top/Article/details/gtctemxsft.html

C#:   public override string ToString() => Name;
来源：http://dali.fengsongda.top/Article/details/gtqjiclvdk.html

[G13] 判断对象类型
来源：http://dali.sxryk.cn/Article/details/gtccuwqbpn.html

Py:   isinstance(u, User)
来源：http://dali.0kj1m.cn/Article/details/gtwfscwjif.html

PHP:  $u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtoirmblpv.html

JS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtxkdylauv.html

TS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtvelhkuew.html

Java: u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtfdnvvqmg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jyoumei.cn/Article/details/gtrxlcejwu.html

Ruby: u.is_a?(User)
来源：http://dali.cucudq.cn/Article/details/gtdzuloqit.html

C#:   u is User
来源：http://dali.chenjidiqi.icu/Article/details/gtxnkxnfyw.html

[G14] 数据类 / record
来源：http://dali.yanxiufei.cn/Article/details/gtkaiyavvw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenlongwang.top/Article/details/gtejqlcnov.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shuidangran.top/Article/details/gtthvmiglt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.316326.xyz/Article/details/gtyfmtsgfw.html

TS:   type User = { name: string; age: number };
来源：http://dali.shzxlz.cn/Article/details/gtkziysatx.html

Java: record User(String name, int age) {}
来源：http://dali.vqdsnc.cn/Article/details/gtmcgeygtj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj202588.top/Article/details/gtxpasifyp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cdnleiting.top/Article/details/gtvxhxengp.html

C#:   record User(string Name, int Age);
来源：http://dali.shzxlz.cn/Article/details/gtslkpujzd.html

[G15] 枚举
来源：http://dali.quarkkingdee.top/Article/details/gtnnmcdlre.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrgxfspjt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqgvunqt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.guannengcc.top/Article/details/gtfvvyqzjf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gtrvqphqbr.html

Java: enum Color { RED, GREEN }
来源：http://dali.hnqzz.top/Article/details/gtkivmesnj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gogol.net.cn/Article/details/gtqjjvhedq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.haohaochexian.top/Article/details/gtegffizyf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gticfbdywa.html

[G16] 对象转数组 / 字典
来源：http://dali.vqdsnc.cn/Article/details/gthecgtxyj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.dianchejie.cn/Article/details/gtviaygdes.html

PHP:  get_object_vars($obj);
来源：http://dali.ydzc1.top/Article/details/gtetvzosmo.html

JS:   Object.entries(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtuhkqwdpk.html

TS:   Object.entries(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtsspklrbt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tian-w.cn/Article/details/gtgznchxqc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shuidangran.top/Article/details/gthtiarwox.html

Ruby: obj.instance_variables
来源：http://dali.guannengcc.top/Article/details/gtoknfmzrh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenlongwang.top/Article/details/gtheettsja.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtgneimjpu.html

H. 异常与错误处理
来源：http://dali.sufxvd.cn/Article/details/gtldpnzhic.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtyxcisegs.html

[H01] try / catch 基础
来源：http://dali.yuxming.cn/Article/details/gtxrhxvfkd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdpzcuwim.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.iojbl.cn/Article/details/gteogpcgdz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gtwlxmycsh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gtdnlspibq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.fzhhl.top/Article/details/gtgugvlgou.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxinkj.top/Article/details/gtodatsjnc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gaohongyu789.top/Article/details/gtzxkwiwvi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cucudq.cn/Article/details/gtttfkaqjd.html

[H02] finally / ensure 收尾
来源：http://dali.gotoacloud.top/Article/details/gtehbwvxrv.html


<!-- 参考信息 -->