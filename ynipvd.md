代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gttmvoxvys.html

TS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gtwzahzapy.html

Java: s.lines().toList()
来源：http://dali.guannengcc.top/Article/details/gttdkvkvic.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhengqikj.top/Article/details/gtpiicxnxi.html

Ruby: s.lines
来源：http://dali.yuxming.cn/Article/details/gtohvqgjvi.html

C#:   s.Split('\n')
来源：http://dali.cucudq.cn/Article/details/gtewdkkphx.html

[E20] 判断字符串是否为空
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvqkrmjnv.html

Py:   if not s:
来源：http://dali.meibo888.top/Article/details/gttmhszmrd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yangfankeji.com/Article/details/gtnhkantsg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.dianchejie.cn/Article/details/gtewwxmozo.html

TS:   if (s === "") {}
来源：http://dali.mhx1999.top/Article/details/gtnnczgzkc.html

Java: if (s.isEmpty()) {}
来源：http://dali.yueranfly.top/Article/details/gtzgvkbpvn.html

Go:   if s == "" {}
来源：http://dali.ydzc1.top/Article/details/gteyuctroq.html

Ruby: if s.empty?
来源：http://dali.gzhubu.top/Article/details/gtcnustbpo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtrtmzrvyd.html

[E21] 超长截断加省略号
来源：http://dali.hnqzz.top/Article/details/gtjmovibbx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.redwolf501.top/Article/details/gtpwtbdddt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowyyxovu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtynornuqw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtbjsiwdjc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtoxcqouof.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ehwqpu.com/Article/details/gtztlzjbfg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtfpsmrlib.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbiwbsya.html

[E22] 字节长度与字符长度
来源：http://dali.cheryme.top/Article/details/gtvvbdwhsu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tian-w.cn/Article/details/gtakuvhoed.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtqhdnhpdf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cashguo.top/Article/details/gtdhsohrei.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgfzy.top/Article/details/gtivzsdepm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aibaodan.cn/Article/details/gtqmtdjdxd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.guannengcc.top/Article/details/gtygtfikyu.html

Ruby: s.bytesize;  s.length
来源：http://dali.sysykeji.top/Article/details/gtqlyqzyvq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.redwolf501.top/Article/details/gtxuzqysvk.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtsmovyedy.html

F. 文件与目录
来源：http://dali.jiagoushi.top/Article/details/gtzfpzuqjc.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtamsjfcdr.html

[F01] 读取整个文件
来源：http://dali.shuidangran.top/Article/details/gtrbptnnth.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.redwolf501.top/Article/details/gtujkqqajr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtfwhaypzg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenlongwang.top/Article/details/gthewisnzm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangdashe.top/Article/details/gtrzguefds.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtpbxxbgco.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nanxinkj.top/Article/details/gtxkvmzkpz.html

Ruby: File.read("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtltiirdtz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtxzyaaukz.html

[F02] 逐行读取文件
来源：http://dali.ehwqpu.com/Article/details/gthkacrwma.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj20258888.top/Article/details/gtpbebdgro.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zycfv.cn/Article/details/gtuyvqwpak.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daria6918.cn/Article/details/gtbmrcsmol.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gtxkmwlxah.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xinyue.icu/Article/details/gtdistoroe.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtukazntqv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gzhubu.top/Article/details/gtcbdaohqx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlzzkygai.html

[F03] 写入文件（覆盖）
来源：http://dali.zhiwuduotai.top/Article/details/gtzucxfuik.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.daxiang520.top/Article/details/gtwbfearqc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtjeygqbsq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtpoarqcpa.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gtgjjlnrfv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zycfv.cn/Article/details/gtyllnwewy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hfpthk.cn/Article/details/gtoecuwiae.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tanke756.top/Article/details/gtqofhadxt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gtfdstnyma.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtivddyaax.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.mhx1999.top/Article/details/gtrqhqhdpo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmcjozzmz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtetfzjnth.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfawhajww.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258888.top/Article/details/gtxqwrgfen.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtrwhuuvmi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ydzc1.top/Article/details/gtmgkpipvn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinyuanbaomall.cn/Article/details/gthuoauodi.html

[F05] 判断文件或目录是否存在
来源：http://dali.cqqwz.cn/Article/details/gtsfnnzzlp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yvedp.cn/Article/details/gtimdakwsx.html

PHP:  file_exists("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtggfsysvo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtbaytheka.html

TS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtobtezumr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtotfbysim.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdmvkfdra.html

Ruby: File.exist?("a.txt")
来源：http://dali.havefunace.top/Article/details/gttyfzlkqk.html

C#:   File.Exists("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkhthpnue.html

[F06] 删除文件
来源：http://dali.birdmap.top/Article/details/gtyehhtpnp.html

Py:   os.remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtdwnrcqws.html

PHP:  unlink("a.txt");
来源：http://dali.hammf.cn/Article/details/gtobshsirc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtehtlchzd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtfvdvphqc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtpdrxwosc.html

Go:   os.Remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtuucxbuqe.html

Ruby: File.delete("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtzstiabks.html

C#:   File.Delete("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtskyvwyae.html

[F07] 创建目录（含多级）
来源：http://dali.gzhubu.top/Article/details/gtvrwpbfjx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.pycfn.com/Article/details/gtcksqbtha.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.316326.xyz/Article/details/gtecivpcyg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gtudtnswng.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gttpfkqlyj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigufen.top/Article/details/gtqayaucxc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.svipenyu.cn/Article/details/gtzdjnarjg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daria6918.cn/Article/details/gthujsydox.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ivvv.top/Article/details/gtbpxevyhi.html

[F08] 遍历目录
来源：http://dali.yuxming.cn/Article/details/gthwzcqjha.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuetiantiany.cn/Article/details/gtapmtjuuh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.9152youxi.cn/Article/details/gtpivdzhbk.html

JS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gtlpulxlvn.html

TS:   fs.readdirSync("dir")
来源：http://dali.zdqjudy.top/Article/details/gtgnporlph.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yanxiufei.cn/Article/details/gtppbhmzsc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoevvzeaq.html

Ruby: Dir.children("dir")
来源：http://dali.tian-w.cn/Article/details/gtqjhxshwt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtyjicoraw.html

[F09] 获取文件大小
来源：http://dali.cdnleiting.top/Article/details/gtnljszsxw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.bjfxy.top/Article/details/gthtkyggxs.html

PHP:  filesize("a.txt");
来源：http://dali.yongpay.top/Article/details/gtfehzhqxc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.guowangkeji.top/Article/details/gtzysobxtu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xuetiantiany.cn/Article/details/gtuomcrkim.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtxtpekvgj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.c1oappe.top/Article/details/gtmmsmbyyx.html

Ruby: File.size("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtgmurstso.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ybcxt.top/Article/details/gtqbjuhyob.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hysaishi.cn/Article/details/gtdyznilwd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtgcqxjwzm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfpjprmff.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtjfqvowfs.html

TS:   path.extname("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtdirbnpps.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yvedp.cn/Article/details/gtitdxumhn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gteonqsatv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtssfpqvvs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtojtufccl.html

[F11] 复制与移动文件
来源：http://dali.yj202588.top/Article/details/gtnmvxcsjn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtcqwiheqg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yueranfly.top/Article/details/gtuwjfdvwd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtamvogaza.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtatdqlvrj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gtnxwsgxme.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenlongwang.top/Article/details/gtjwtmdeam.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtrukvylaj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gtqiovhahw.html

[F12] CSV 读写
来源：http://dali.chenzaomai.com/Article/details/gtmtiqiwed.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.andypj.xyz/Article/details/gtzvaefbyn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hywenlv.cn/Article/details/gtjwhcqcud.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xuetiantiany.cn/Article/details/gtspuwlgfm.html

TS:   // 同上
来源：http://dali.9152youxi.cn/Article/details/gtqyfekgvd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sysykeji.top/Article/details/gtxksmkzpm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yanxiufei.cn/Article/details/gtsigpadux.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenjidiqi.icu/Article/details/gtppujbibw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cqqwz.cn/Article/details/gtcoombnzh.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtiwuwepej.html

G. 面向对象
来源：http://dali.jyoumei.cn/Article/details/gtcocjtccp.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtbvwleuoi.html

[G01] 定义类
来源：http://dali.9152youxi.cn/Article/details/gtervptqsm.html

Py:   class User: pass
来源：http://dali.316326.xyz/Article/details/gtbyalfoeb.html

PHP:  class User {}
来源：http://dali.xuanzx.com/Article/details/gtrirxyklu.html

JS:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtxoiisklk.html

TS:   class User { name: string = ""; }
来源：http://dali.meibo888.top/Article/details/gtmvwujayz.html

Java: class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtuwpbeotl.html

Go:   type User struct { Name string }
来源：http://dali.ivvv.top/Article/details/gtmniiwihd.html

Ruby: class User; end
来源：http://dali.xinyue.icu/Article/details/gtoccegnvb.html

C#:   class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtciqsjceh.html

[G02] 构造函数
来源：http://dali.svipenyu.cn/Article/details/gtzlbxtxan.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gtknmkuwih.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenzaomai.com/Article/details/gtbrizuvup.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gtpowbpnvp.html

TS:   constructor(public name: string) {}
来源：http://dali.haohaochexian.top/Article/details/gtkzfkgsmj.html

Java: User(String name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gtmuakyljv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yueranfly.top/Article/details/gttevsjfsz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cheryme.top/Article/details/gtopsfrgcp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.mhx1999.top/Article/details/gtixeeusyj.html

[G03] 实例属性
来源：http://dali.fengsongda.top/Article/details/gtnmvducpw.html

Py:   self.name = "x"
来源：http://dali.vqdsnc.cn/Article/details/gtatbgoptd.html

PHP:  public string $name = "x";
来源：http://dali.xuanzx.com/Article/details/gtokzefaji.html

JS:   this.name = "x";
来源：http://dali.yonumen.top/Article/details/gtmqtmohiy.html

TS:   name: string = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtjimxyfzx.html

Java: private String name;
来源：http://dali.yonumen.top/Article/details/gtkgwmdljs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.iojbl.cn/Article/details/gtogzavddm.html

Ruby: @name = "x"
来源：http://dali.jqgfzy.top/Article/details/gtnccyqelb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cdnleiting.top/Article/details/gtwodqvyht.html

[G04] 定义方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbcmobhup.html

Py:   def greet(self): return self.name
来源：http://dali.yongpay.top/Article/details/gtnnmwxrco.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtafiiucpo.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqsiajzjn.html

TS:   greet(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtvzvijqft.html

Java: String greet() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzyebeti.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtqlktajda.html

Ruby: def greet; @name; end
来源：http://dali.yvedp.cn/Article/details/gtmtbfgmlp.html

C#:   public string Greet() => Name;
来源：http://dali.xuanzx.com/Article/details/gtvrtndhfp.html

[G05] 继承
来源：http://dali.vqdsnc.cn/Article/details/gtwikebggz.html

Py:   class Admin(User): pass
来源：http://dali.hongshengwenyu.top/Article/details/gtrdmwogzh.html

PHP:  class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtvthepyzy.html

JS:   class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtzfsdvpxi.html

TS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtfayorhop.html

Java: class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtshwhnexp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zycfv.cn/Article/details/gtwpoqjdde.html

Ruby: class Admin < User; end
来源：http://dali.sysykeji.top/Article/details/gtrmnlihxq.html

C#:   class Admin : User {}
来源：http://dali.yuanzhike.top/Article/details/gtnbjsitmj.html

[G06] 重写方法
来源：http://dali.jyoumei.cn/Article/details/gtfmtarinu.html

Py:   def greet(self): return "admin"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufdyxrxo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gthzpyedyx.html

JS:   greet() { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtgfhwfyha.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtqiddlusd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtygolkyhh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cqqwz.cn/Article/details/gttbmkfmwx.html

Ruby: def greet; "admin"; end
来源：http://dali.jyoumei.cn/Article/details/gtyfoldbyf.html

C#:   public override string Greet() => "admin";
来源：http://dali.iojbl.cn/Article/details/gtuisjeneb.html

[G07] 调用父类方法
来源：http://dali.jinqigfzy.top/Article/details/gtvmrlchxc.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gtnmfsmunf.html

PHP:  parent::greet();
来源：http://dali.ydzc1.top/Article/details/gtxkqobkix.html

JS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gttiuixejp.html

TS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gtvufgrqkl.html

Java: super.greet();
来源：http://dali.xinyue.icu/Article/details/gtmlqxdzld.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ydzc1.top/Article/details/gttvadsisc.html

Ruby: super
来源：http://dali.9152youxi.cn/Article/details/gtriuzxscn.html

C#:   base.Greet();
来源：http://dali.vqdsnc.cn/Article/details/gtufjtcglt.html

[G08] 静态方法与属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiyoyjleg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.kuanghao11.cn/Article/details/gtiilwuork.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtjikbdvlk.html

JS:   static f() {}
来源：http://dali.jianghu66.top/Article/details/gtimctsewg.html

TS:   static f(): void {}
来源：http://dali.zhongyouzk.top/Article/details/gtxcojxyki.html

Java: static void f() {}
来源：http://dali.9152youxi.cn/Article/details/gtiyqmeoao.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuanzx.com/Article/details/gtyudowswp.html

Ruby: def self.f; end
来源：http://dali.xuetiantiany.cn/Article/details/gtdbiiebdy.html

C#:   public static void F() {}
来源：http://dali.fengsongda.top/Article/details/gtrrvnbdbo.html

[G09] 接口 / 抽象类
来源：http://dali.daxiang520.top/Article/details/gtkdzyrcda.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.havefunace.top/Article/details/gtdxicrzdv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shzxlz.cn/Article/details/gtuijizjnm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangkeji.top/Article/details/gthyvzmeew.html

TS:   interface Shape { area(): number; }
来源：http://dali.aibaodan.cn/Article/details/gtrlsjlgrm.html

Java: interface Shape { double area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmpazsivx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigfzy.top/Article/details/gtzeyptere.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ehwqpu.com/Article/details/gtruhqojyi.html

C#:   interface IShape { double Area(); }
来源：http://dali.aizwys.cn/Article/details/gtuzervbgm.html

[G10] 访问控制
来源：http://dali.xuanzx.com/Article/details/gtpgbtbxmb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuanzhike.top/Article/details/gtxqugalvu.html

PHP:  public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gtbeqdilgb.html

JS:   #private 字段；其余公开
来源：http://dali.xuanzx.com/Article/details/gtixbdjnuj.html

TS:   public / protected / private
来源：http://dali.nwbrower.top/Article/details/gtvpkygvyi.html

Java: public / protected / private / 默认包级
来源：http://dali.yuxming.cn/Article/details/gthteidawo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.smart0.xyz/Article/details/gtmwcikrkb.html

Ruby: public / protected / private
来源：http://dali.ybcxt.top/Article/details/gtcevbshtj.html

C#:   public / protected / private / internal
来源：http://dali.guannengcc.top/Article/details/gtjmjnkkaq.html

[G11] getter / setter
来源：http://dali.yangfankeji.com/Article/details/gttivpibbq.html

Py:   @property 与 @x.setter
来源：http://dali.tanke756.top/Article/details/gtjgzrptvp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gtgqodpxqw.html

JS:   get name() { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gtweqtdqmg.html

TS:   get name(): string { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gtgjvxzytp.html

Java: public String getName() { return name; }
来源：http://dali.guannengcc.top/Article/details/gteeblxoez.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gttuqmwesj.html

Ruby: attr_accessor :name
来源：http://dali.nanxinkj.top/Article/details/gtlaabqvkg.html

C#:   public string Name { get; set; }
来源：http://dali.yvedp.cn/Article/details/gtjphdoykn.html

[G12] 对象转字符串
来源：http://dali.yuanzhike.top/Article/details/gtgeukmmvb.html

Py:   def __str__(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gtcjzzwqgb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gtvdrlaxhk.html

JS:   toString() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtdpljrgfy.html

TS:   toString(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtcxfoyblv.html

Java: @Override public String toString() { return name; }
来源：http://dali.bjfxy.top/Article/details/gtyvvzcfim.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gtkqafuree.html

Ruby: def to_s; @name; end
来源：http://dali.tianlin.xyz/Article/details/gtdlayrypt.html

C#:   public override string ToString() => Name;
来源：http://dali.yongpay.top/Article/details/gtydjcnkgg.html

[G13] 判断对象类型
来源：http://dali.daxiang520.top/Article/details/gtdqemteic.html

Py:   isinstance(u, User)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgsufekmh.html

PHP:  $u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtopxqaqyx.html

JS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtfaoiscub.html

TS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gtqokogcrp.html

Java: u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gttearpony.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gtwrltlzen.html

Ruby: u.is_a?(User)
来源：http://dali.xziqi.cn/Article/details/gtyobzfjjn.html

C#:   u is User
来源：http://dali.sweek.top/Article/details/gtbkggkrjl.html

[G14] 数据类 / record
来源：http://dali.xuanzx.com/Article/details/gtxnuqtofb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tianlin.xyz/Article/details/gtxkghmtpn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dashuyun.cn/Article/details/gtstdprjjd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.9152youxi.cn/Article/details/gtuwqnuxzz.html

TS:   type User = { name: string; age: number };
来源：http://dali.tian-w.cn/Article/details/gtnkjpmiwl.html

Java: record User(String name, int age) {}
来源：http://dali.xziqi.cn/Article/details/gtyehdyrrz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yanxiufei.cn/Article/details/gtkiprqqjz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ydzc1.top/Article/details/gtcedpgoll.html

C#:   record User(string Name, int Age);
来源：http://dali.hongshengwenyu.top/Article/details/gtbsjqsjnt.html

[G15] 枚举
来源：http://dali.hysaishi.cn/Article/details/gtvewrwwrc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sufxvd.cn/Article/details/gtuxdazvop.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hysaishi.cn/Article/details/gtnqyzbwjl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigfzy.top/Article/details/gtxdwobxmz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gterrkgpoi.html

Java: enum Color { RED, GREEN }
来源：http://dali.hnqzz.top/Article/details/gtopiwtgfh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.316326.xyz/Article/details/gtnturxjec.html

Ruby: Color = %i[red green].freeze
来源：http://dali.quarkkingdee.top/Article/details/gtvrfcfzgd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.svipenyu.cn/Article/details/gtactzujyt.html

[G16] 对象转数组 / 字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjnfrylid.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pycfn.com/Article/details/gtktadzlps.html

PHP:  get_object_vars($obj);
来源：http://dali.daxiang520.top/Article/details/gtcgbtixke.html

JS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gtsqkqorqe.html

TS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gtfjwzniix.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fzhhl.top/Article/details/gtiyengykb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xuetiantiany.cn/Article/details/gtuilqnrey.html

Ruby: obj.instance_variables
来源：http://dali.jinqigfzy.top/Article/details/gtdgafytds.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxnmbpeu.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtikroxmht.html

H. 异常与错误处理
来源：http://dali.aizwys.cn/Article/details/gtrfellujs.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtspzytaxx.html

[H01] try / catch 基础
来源：http://dali.jinqigfzy.top/Article/details/gttuuaqksd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjffedtzv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtymlwlyio.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gtcszymnha.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gtvsudtpmn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gaohongyu789.top/Article/details/gtqdhkeynh.html


<!-- 参考信息 -->