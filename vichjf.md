代发 wailian999

Go:   if s == "" {}
来源：http://dali.yvedp.cn/Article/details/gtxovcxwkt.html

Ruby: if s.empty?
来源：http://dali.jyoumei.cn/Article/details/gtlrampbur.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gzhubu.top/Article/details/gtbmwqjmgx.html

[E21] 超长截断加省略号
来源：http://dali.hysaishi.cn/Article/details/gtizrvylwh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.mhx1999.top/Article/details/gtkdegrxun.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gtoubvrbhb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtmmnjyryf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtreuoylrl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtjyvmnxvm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxnqqqlxp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gtvssaznfn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cheryme.top/Article/details/gthfhqiwpe.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gtvjohtzgg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hnqzz.top/Article/details/gtvfcqckpw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtgteuvkaq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tanke756.top/Article/details/gtxfcjyisc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gtxaezxdwg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.iojbl.cn/Article/details/gtteyqbnqe.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.quarkkingdee.top/Article/details/gtdfyomedg.html

Ruby: s.bytesize;  s.length
来源：http://dali.cucudq.cn/Article/details/gtriurmpoo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yanxiufei.cn/Article/details/gtpgajnwsq.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtdixsqvow.html

F. 文件与目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpacwmwlf.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtnacebyuc.html

[F01] 读取整个文件
来源：http://dali.hysaishi.cn/Article/details/gtpdzgzqhj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nanxinkj.top/Article/details/gtvmrthrwo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtgrmgyoku.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.pycfn.com/Article/details/gtedxlompr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtealqxlct.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtaoybhwxl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgfzy.top/Article/details/gtvjpuykrg.html

Ruby: File.read("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtnsefdmtx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtuzyajlpb.html

[F02] 逐行读取文件
来源：http://dali.xuanzx.com/Article/details/gtutgczewp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhengqikj.top/Article/details/gtaakijubu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sufxvd.cn/Article/details/gttvgdnurk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aibaodan.cn/Article/details/gtfspivsiz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtugckeljy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gtwgfgpkzr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pycfn.com/Article/details/gtwogpaegi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.daxiang520.top/Article/details/gtbzqsdies.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dashuyun.cn/Article/details/gtzxgvknhl.html

[F03] 写入文件（覆盖）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrpbfwrtu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhongyouzk.top/Article/details/gtcglkhytc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtlkwlotti.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gtoenwakyd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtlgthemga.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yuxming.cn/Article/details/gtpizkpxsj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ivvv.top/Article/details/gtjyzejrao.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tian-w.cn/Article/details/gtzxubnrbh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gtawoolvda.html

[F04] 追加写入文件
来源：http://dali.quarkkingdee.top/Article/details/gtkgsofube.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xziqi.cn/Article/details/gtingocuny.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.daxiang520.top/Article/details/gtqrhxnenw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gtjeblvelx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtmyvfnwsh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangdashe.top/Article/details/gtpuiezisz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yongpay.top/Article/details/gtewhngiuy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258.top/Article/details/gtqodyhzem.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.mhx1999.top/Article/details/gtxmmvrzzg.html

[F05] 判断文件或目录是否存在
来源：http://dali.vqdsnc.cn/Article/details/gtylbwimdu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhixingplan.top/Article/details/gtbecyeypd.html

PHP:  file_exists("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtranujmkx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtxdhtstor.html

TS:   fs.existsSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtnkarfimp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtwcmolctw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvyfyrzni.html

Ruby: File.exist?("a.txt")
来源：http://dali.ivvv.top/Article/details/gturqjrxak.html

C#:   File.Exists("a.txt")
来源：http://dali.birdmap.top/Article/details/gtmjfdjpol.html

[F06] 删除文件
来源：http://dali.cheryme.top/Article/details/gtajcedtme.html

Py:   os.remove("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtoszhoihi.html

PHP:  unlink("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtcnqiaman.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowhtqsfb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtyjcokhdt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtwvgoitcj.html

Go:   os.Remove("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtivdgxxzb.html

Ruby: File.delete("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtkneynspi.html

C#:   File.Delete("a.txt");
来源：http://dali.sweek.top/Article/details/gttwbzqakv.html

[F07] 创建目录（含多级）
来源：http://dali.yangfankeji.com/Article/details/gtmdakxwpl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.guannengcc.top/Article/details/gtnuypxfdn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzllopux.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hongshengwenyu.top/Article/details/gtvafymvvu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yonumen.top/Article/details/gtmbkrbqfd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xuanzx.com/Article/details/gtzaocgghy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nanxuanxn.top/Article/details/gtmvbsoqnj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhongyouzk.top/Article/details/gtnxaycjct.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkyasxzgz.html

[F08] 遍历目录
来源：http://dali.cashguo.top/Article/details/gtlxillvbv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj202588.top/Article/details/gtthqamrcf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcfbactt.html

JS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gtaoftpkws.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtdigunwja.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xuetiantiany.cn/Article/details/gtglxrjtve.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yuanzhike.top/Article/details/gtlugzlvbr.html

Ruby: Dir.children("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtmyvzjzsi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.bjfxy.top/Article/details/gthfnxlvxw.html

[F09] 获取文件大小
来源：http://dali.jinqigfzy.top/Article/details/gtuknxeexs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtplbadgyp.html

PHP:  filesize("a.txt");
来源：http://dali.cashguo.top/Article/details/gtclhkdwsv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gtjniewxqq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.haohaochexian.top/Article/details/gtchexkkiy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtukzrgstx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.c1oappe.top/Article/details/gtnngrdypq.html

Ruby: File.size("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtyfwozkct.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yvedp.cn/Article/details/gtqhggtwdu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shuidangran.top/Article/details/gtrfladrzq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtlfksppqu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtxduxfaku.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtzjjwzgkw.html

TS:   path.extname("a.txt")
来源：http://dali.havefunace.top/Article/details/gtpfupkuwd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aizwys.cn/Article/details/gtjbiaydwk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtqsdfrloc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gttwcxdhey.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtftsgeqgg.html

[F11] 复制与移动文件
来源：http://dali.zhongyouzk.top/Article/details/gtsnelufgo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtkjarqjcc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtvqkzxfwl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtoaoyylor.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gtwhxwujtv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cucudq.cn/Article/details/gtlthxunsm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yanxiufei.cn/Article/details/gtjhndfamm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtgaztubvz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.aibaodan.cn/Article/details/gtpdfosfrb.html

[F12] CSV 读写
来源：http://dali.shangyingyoupin.top/Article/details/gtjlmvobdy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenlongwang.top/Article/details/gtksyixogr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gtgdtqvzpw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sxryk.cn/Article/details/gtmneyzxkb.html

TS:   // 同上
来源：http://dali.bjfxy.top/Article/details/gthfswkjpq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shanyushiyangtech.top/Article/details/gtyaihdphg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xylfe.cn/Article/details/gtwgmgpucr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sweek.top/Article/details/gtnknssljk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.haohaochexian.top/Article/details/gtludttrlf.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkljleyiq.html

G. 面向对象
来源：http://dali.cdnleiting.top/Article/details/gtxmyxkugn.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtgwojzlbo.html

[G01] 定义类
来源：http://dali.dianchejie.cn/Article/details/gtaimqkhhp.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gtqevumpqn.html

PHP:  class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtursekhvz.html

JS:   class User {}
来源：http://dali.haohaochexian.top/Article/details/gtkwlmgztj.html

TS:   class User { name: string = ""; }
来源：http://dali.redwolf501.top/Article/details/gtsriuvduw.html

Java: class User {}
来源：http://dali.hammf.cn/Article/details/gtzgdzhbas.html

Go:   type User struct { Name string }
来源：http://dali.vqdsnc.cn/Article/details/gtsnqyqtzv.html

Ruby: class User; end
来源：http://dali.nanxuanxn.top/Article/details/gttdbzpzfa.html

C#:   class User {}
来源：http://dali.316326.xyz/Article/details/gtyqmlhdqz.html

[G02] 构造函数
来源：http://dali.fzhhl.top/Article/details/gtjtooxdrf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gotoacloud.top/Article/details/gtuasypivy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnxiangtu.top/Article/details/gtdpepfmao.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gtuhyvhwuk.html

TS:   constructor(public name: string) {}
来源：http://dali.yongpay.top/Article/details/gthcaltptv.html

Java: User(String name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gtjgzmgvad.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhengqikj.top/Article/details/gtjrhwnbza.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dashuyun.cn/Article/details/gtfygbpoow.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtnvhecnva.html

[G03] 实例属性
来源：http://dali.havefunace.top/Article/details/gtfshxzyoe.html

Py:   self.name = "x"
来源：http://dali.haohaochexian.top/Article/details/gtifaxfeky.html

PHP:  public string $name = "x";
来源：http://dali.chenzaomai.com/Article/details/gtygcfmdho.html

JS:   this.name = "x";
来源：http://dali.ybcxt.top/Article/details/gtophrvjuc.html

TS:   name: string = "x";
来源：http://dali.ybcxt.top/Article/details/gtobduatox.html

Java: private String name;
来源：http://dali.hnqzz.top/Article/details/gtfblazadq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pengpengdd.cyou/Article/details/gthjuwlvqh.html

Ruby: @name = "x"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfcfupblj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxinkj.top/Article/details/gtsxwrcmrv.html

[G04] 定义方法
来源：http://dali.ydzc1.top/Article/details/gtklcugabm.html

Py:   def greet(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gtellclast.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtykxtgtip.html

JS:   greet() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtuvzovhwu.html

TS:   greet(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtcmbbhtqp.html

Java: String greet() { return name; }
来源：http://dali.havefunace.top/Article/details/gtirqgnmdp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtjuiaybgy.html

Ruby: def greet; @name; end
来源：http://dali.daria6918.cn/Article/details/gtydtampyb.html

C#:   public string Greet() => Name;
来源：http://dali.guannengcc.top/Article/details/gtewixzdkf.html

[G05] 继承
来源：http://dali.shangyingyoupin.top/Article/details/gtiqulqimx.html

Py:   class Admin(User): pass
来源：http://dali.cheryme.top/Article/details/gtwgejitml.html

PHP:  class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtocfyuttk.html

JS:   class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gteafaitiv.html

TS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtsbsuupkz.html

Java: class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtxlraitsc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hammf.cn/Article/details/gtqtrvehkp.html

Ruby: class Admin < User; end
来源：http://dali.daria6918.cn/Article/details/gtsmwisder.html

C#:   class Admin : User {}
来源：http://dali.dashuyun.cn/Article/details/gtaikgpjjd.html

[G06] 重写方法
来源：http://dali.jianghu66.top/Article/details/gtipsmocjv.html

Py:   def greet(self): return "admin"
来源：http://dali.ppjwa.cn/Article/details/gtdyxpozou.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtqdyypopy.html

JS:   greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtmdiffsie.html

TS:   greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtozkbyueb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtlliowaea.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jiagoushi.top/Article/details/gtbssbxdpj.html

Ruby: def greet; "admin"; end
来源：http://dali.pengpengdd.cyou/Article/details/gtzfvjblur.html

C#:   public override string Greet() => "admin";
来源：http://dali.daria6918.cn/Article/details/gtxjinyfvs.html

[G07] 调用父类方法
来源：http://dali.yangfankeji.com/Article/details/gtkybcwxqx.html

Py:   super().greet()
来源：http://dali.redwolf501.top/Article/details/gtolqxihgf.html

PHP:  parent::greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtbysxajvq.html

JS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gtxawsxcxl.html

TS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gtwjlrrxqg.html

Java: super.greet();
来源：http://dali.cheryme.top/Article/details/gtcoqdgefj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nwbrower.top/Article/details/gtqmoibuqv.html

Ruby: super
来源：http://dali.chenlongwang.top/Article/details/gtuldmbtxh.html

C#:   base.Greet();
来源：http://dali.ybcxt.top/Article/details/gtrqrbahmq.html

[G08] 静态方法与属性
来源：http://dali.quarkkingdee.top/Article/details/gtaxzgfooq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.smart0.xyz/Article/details/gtxrijeyiz.html

PHP:  public static function f() {}
来源：http://dali.yj20258888.top/Article/details/gtnnqoqkga.html

JS:   static f() {}
来源：http://dali.fzhhl.top/Article/details/gtenecfwqa.html

TS:   static f(): void {}
来源：http://dali.zhixingplan.top/Article/details/gtesewhlsm.html

Java: static void f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtzhxdcwlt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.havefunace.top/Article/details/gtkzzkzmyl.html

Ruby: def self.f; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gttscgmrjl.html

C#:   public static void F() {}
来源：http://dali.ehwqpu.com/Article/details/gtrbhgxbei.html

[G09] 接口 / 抽象类
来源：http://dali.yongpay.top/Article/details/gtrdcsyqbd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhengqikj.top/Article/details/gtrwiauvra.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xziqi.cn/Article/details/gtigplsthm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gtqhbujlmh.html

TS:   interface Shape { area(): number; }
来源：http://dali.yonumen.top/Article/details/gtwewdrxpl.html

Java: interface Shape { double area(); }
来源：http://dali.xuanzx.com/Article/details/gtkvengyqb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtseskqbff.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yvedp.cn/Article/details/gtlkviizom.html

C#:   interface IShape { double Area(); }
来源：http://dali.guannengcc.top/Article/details/gtvbniqzyj.html

[G10] 访问控制
来源：http://dali.xylfe.cn/Article/details/gthnvzwyyg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.vqdsnc.cn/Article/details/gtwgvdstvs.html

PHP:  public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gtfekirdgj.html

JS:   #private 字段；其余公开
来源：http://dali.wangdashe.top/Article/details/gtbjdcixaa.html

TS:   public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtssokrrzi.html

Java: public / protected / private / 默认包级
来源：http://dali.aizwys.cn/Article/details/gtnsuqyawj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yuanzhike.top/Article/details/gteimmghmd.html

Ruby: public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtsajmfpyr.html

C#:   public / protected / private / internal
来源：http://dali.xuetiantiany.cn/Article/details/gtepqwjvyf.html

[G11] getter / setter
来源：http://dali.svipenyu.cn/Article/details/gtgpcgvide.html

Py:   @property 与 @x.setter
来源：http://dali.yj202588.top/Article/details/gtkgtqzops.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gttafaequp.html

JS:   get name() { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtooortdhs.html

TS:   get name(): string { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gtoljsifvc.html

Java: public String getName() { return name; }
来源：http://dali.tanke756.top/Article/details/gtsxikuhkm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtksgifzhz.html

Ruby: attr_accessor :name
来源：http://dali.ppjwa.cn/Article/details/gthbgxefxx.html

C#:   public string Name { get; set; }
来源：http://dali.quarkkingdee.top/Article/details/gtvccnyuan.html

[G12] 对象转字符串
来源：http://dali.xziqi.cn/Article/details/gtwjxytouf.html

Py:   def __str__(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gtmqcjtobj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtfnpicktm.html

JS:   toString() { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtirhjepod.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzqgwgas.html

Java: @Override public String toString() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtcizyzndg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtzffildbd.html

Ruby: def to_s; @name; end
来源：http://dali.yueranfly.top/Article/details/gtgrwtamfp.html

C#:   public override string ToString() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtearhisfy.html

[G13] 判断对象类型
来源：http://dali.0kj1m.cn/Article/details/gttiecites.html

Py:   isinstance(u, User)
来源：http://dali.nanxuanxn.top/Article/details/gtipxjxtue.html

PHP:  $u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtcqlvppxx.html

JS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtcuraomqr.html

TS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtpsqzkdev.html

Java: u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtnbousdrf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.meibo888.top/Article/details/gtiuiqbcof.html

Ruby: u.is_a?(User)
来源：http://dali.0kj1m.cn/Article/details/gtperjifbz.html

C#:   u is User
来源：http://dali.nanxinkj.top/Article/details/gtdiocbbdn.html

[G14] 数据类 / record
来源：http://dali.chenlongwang.top/Article/details/gtzevygkjm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.feifeiyinyue.top/Article/details/gttzzuaine.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tianlin.xyz/Article/details/gtmcyhnoci.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjzxsngb.html

TS:   type User = { name: string; age: number };
来源：http://dali.hammf.cn/Article/details/gtpuwnawtz.html

Java: record User(String name, int age) {}
来源：http://dali.hywenlv.cn/Article/details/gtcvfxqdbp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gtrdxmzvmi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tianlin.xyz/Article/details/gthwekdkld.html

C#:   record User(string Name, int Age);
来源：http://dali.zhixingplan.top/Article/details/gtevbxoiyr.html

[G15] 枚举
来源：http://dali.xziqi.cn/Article/details/gtskfigvzz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jianghu66.top/Article/details/gtgkhpwtst.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtwxtjapva.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqidvbtij.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gtshsykeeb.html

Java: enum Color { RED, GREEN }
来源：http://dali.cashguo.top/Article/details/gtwsztfper.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xylfe.cn/Article/details/gtlydroaof.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cashguo.top/Article/details/gtehpojryh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gtbpsxherf.html

[G16] 对象转数组 / 字典
来源：http://dali.cashguo.top/Article/details/gtsyptctln.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhiwuduotai.top/Article/details/gtxsbrlosy.html

PHP:  get_object_vars($obj);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvziarqa.html

JS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gterdcargk.html

TS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gtediiutai.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tanke756.top/Article/details/gtpxdzmnhj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shzxlz.cn/Article/details/gtgrlljszj.html

Ruby: obj.instance_variables
来源：http://dali.yuxming.cn/Article/details/gtnzfhhkga.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.birdmap.top/Article/details/gtqbltjnds.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtbmubeqnx.html

H. 异常与错误处理
来源：http://dali.yj202588.top/Article/details/gtahfldfkx.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtwjqhlsld.html

[H01] try / catch 基础
来源：http://dali.yanxiufei.cn/Article/details/gtvlknmskp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nanxinkj.top/Article/details/gtpqhkkpog.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.fengsongda.top/Article/details/gtamsepiwz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hysaishi.cn/Article/details/gtsbjrofhu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gotoacloud.top/Article/details/gtjcrqcvmp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gtummvtbtn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tianlin.xyz/Article/details/gtmglwzjqa.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fengsongda.top/Article/details/gtcgfuviat.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guannengcc.top/Article/details/gtaauofiod.html

[H02] finally / ensure 收尾
来源：http://dali.dashuyun.cn/Article/details/gtybdevqaa.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cheryme.top/Article/details/gtskvtntfx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtcyqzdtcv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtovcktvap.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvkkqzslg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgcgzvcqd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cashguo.top/Article/details/gtoaizljmc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hongshengwenyu.top/Article/details/gtpjtmysri.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtnizagvze.html


<!-- 参考信息 -->