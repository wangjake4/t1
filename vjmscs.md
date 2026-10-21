代发 wailian999

Ruby: s.lines
来源：http://dali.jlsjyb.cn/Article/details/gtvfjysaba.html

C#:   s.Split('\n')
来源：http://dali.yj20258.top/Article/details/gtunhahkcd.html

[E20] 判断字符串是否为空
来源：http://dali.feifeiyinyue.top/Article/details/gthpdpfkuo.html

Py:   if not s:
来源：http://dali.cashguo.top/Article/details/gtvzaqtnui.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nanxinkj.top/Article/details/gtnmpycgcq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jiagoushi.top/Article/details/gtytgkpylh.html

TS:   if (s === "") {}
来源：http://dali.sxryk.cn/Article/details/gtyljrrmcr.html

Java: if (s.isEmpty()) {}
来源：http://dali.aibaodan.cn/Article/details/gtafuuogin.html

Go:   if s == "" {}
来源：http://dali.smart0.xyz/Article/details/gtmomqbgsi.html

Ruby: if s.empty?
来源：http://dali.yanxiufei.cn/Article/details/gthfuuehjr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ehwqpu.com/Article/details/gtbprbziwb.html

[E21] 超长截断加省略号
来源：http://dali.pycfn.com/Article/details/gtladzvhmc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.smart0.xyz/Article/details/gtepfxsdkk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gthvghussm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtsvjzxlpm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.iojbl.cn/Article/details/gttxrekifx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtlaetdzkj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jianghu66.top/Article/details/gtynjfnzqu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtxokcqppl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtzngjrzmw.html

[E22] 字节长度与字符长度
来源：http://dali.dianchejie.cn/Article/details/gttmdrtdnl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.snrcjt.cn/Article/details/gtwwcxzvbe.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtmsokughs.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtqzdksron.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfgzulkj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hfpthk.cn/Article/details/gththwmtvk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.feifeiyinyue.top/Article/details/gtnpvkylvv.html

Ruby: s.bytesize;  s.length
来源：http://dali.birdmap.top/Article/details/gtwtcpyclc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hammf.cn/Article/details/gtxarkcfdg.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtlwrplhyh.html

F. 文件与目录
来源：http://dali.dianchejie.cn/Article/details/gtmeugqdfz.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtuuwkrlij.html

[F01] 读取整个文件
来源：http://dali.zhoulong.xyz/Article/details/gthufudnxm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shuidangran.top/Article/details/gtdstvgaup.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtciizqjqj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.havefunace.top/Article/details/gtohcgvckt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cucudq.cn/Article/details/gtzzepbdru.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtfxvutncs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.vqdsnc.cn/Article/details/gtrabbiclt.html

Ruby: File.read("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtntgrchex.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cashguo.top/Article/details/gtaiuethsm.html

[F02] 逐行读取文件
来源：http://dali.zhengqikj.top/Article/details/gtcujubske.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hnqzz.top/Article/details/gtgadfdlid.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yuxming.cn/Article/details/gtqdulhuom.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtdajnxwxs.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtguwxjmnt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.feifeiyinyue.top/Article/details/gthulbfmwm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ehwqpu.com/Article/details/gtnqjbebyd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jqgfzy.top/Article/details/gtfhazlqcq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsiolualz.html

[F03] 写入文件（覆盖）
来源：http://dali.fzhhl.top/Article/details/gtggielpuv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkioohntw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sxryk.cn/Article/details/gtsmhjdate.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.birdmap.top/Article/details/gthllieswc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtptkkdrzt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gzhubu.top/Article/details/gtapnhiosm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.birdmap.top/Article/details/gtnssbcfxb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hfpthk.cn/Article/details/gtoaesfvik.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gtdqrryvzt.html

[F04] 追加写入文件
来源：http://dali.tianlin.xyz/Article/details/gtmqepwczz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cdnleiting.top/Article/details/gtvzaimuxe.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.316326.xyz/Article/details/gtxlgrcxcw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtycptziez.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tian-w.cn/Article/details/gtgqgevhwz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.kuanghao11.cn/Article/details/gtgcecjxqw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ivvv.top/Article/details/gtsuatgpnw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sufxvd.cn/Article/details/gtuxzpqaqv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxjpwyvj.html

[F05] 判断文件或目录是否存在
来源：http://dali.jyoumei.cn/Article/details/gtoyolzehq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gzhubu.top/Article/details/gtodimhobj.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtwlbswhig.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtrwqvzrlc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtwfnurmdr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtsmoxrvrv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.bjfxy.top/Article/details/gtbaxhblto.html

Ruby: File.exist?("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtknaobniz.html

C#:   File.Exists("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtyfqxjwmg.html

[F06] 删除文件
来源：http://dali.sweek.top/Article/details/gthgplpnhn.html

Py:   os.remove("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjhuytjf.html

PHP:  unlink("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtgaufioto.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtckmlycin.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtwjsjkwlh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gtccpppogk.html

Go:   os.Remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtyjiesjlv.html

Ruby: File.delete("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtaaaytraz.html

C#:   File.Delete("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtbxrykhza.html

[F07] 创建目录（含多级）
来源：http://dali.tian-w.cn/Article/details/gthndnkifb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nwbrower.top/Article/details/gtosawbuvi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jlsjyb.cn/Article/details/gtjayprnlf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gtdqmkljks.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gtytzqsghc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnxiangtu.top/Article/details/gtwpkcgjda.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj20258888.top/Article/details/gtymtqphnd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbyyfidfh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gtwixkmgpw.html

[F08] 遍历目录
来源：http://dali.316326.xyz/Article/details/gtcvolrvtv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daria6918.cn/Article/details/gtxxyctcup.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfdclpzs.html

JS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtevcotiwh.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinqigufen.top/Article/details/gttrcpckqa.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gtymyxmuhg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yonumen.top/Article/details/gtcissclnx.html

Ruby: Dir.children("dir")
来源：http://dali.fengsongda.top/Article/details/gtkmxebtft.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuanzhike.top/Article/details/gthkuvbdzf.html

[F09] 获取文件大小
来源：http://dali.jyoumei.cn/Article/details/gtxkdneibv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cheryme.top/Article/details/gthuptgqvl.html

PHP:  filesize("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtfukrspew.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gttbirrpvk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gttntfxzqb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtjygojjrh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.andypj.xyz/Article/details/gtgumuysrx.html

Ruby: File.size("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtiaqzsqro.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xziqi.cn/Article/details/gtowxozgxe.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.andypj.xyz/Article/details/gtjllafntl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gthwyhsenz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.fengsongda.top/Article/details/gtlsbfuaii.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtagetjnss.html

TS:   path.extname("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtsagroyhh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.daria6918.cn/Article/details/gtgopmkbfr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gteivxpbiu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtcwbudqww.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtrshnmpbv.html

[F11] 复制与移动文件
来源：http://dali.haohaochexian.top/Article/details/gttcxfgfwm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtogovsems.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daria6918.cn/Article/details/gtghsemknh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtofrnwrvo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxfgjznn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtwxebbfcz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangshuangyany.cn/Article/details/gtmrotqams.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtxtntwdcg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cashguo.top/Article/details/gtloncgtbq.html

[F12] CSV 读写
来源：http://dali.hywenlv.cn/Article/details/gtyewyiale.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.snrcjt.cn/Article/details/gtudrzwnuv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfztkofim.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.quarkkingdee.top/Article/details/gtseebppba.html

TS:   // 同上
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhkeeydo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yueranfly.top/Article/details/gtxkqheqxf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shuidangran.top/Article/details/gtfngkddeo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigfzy.top/Article/details/gtnlwnpssm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.quarkkingdee.top/Article/details/gtapybnurt.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtjtxxemds.html

G. 面向对象
来源：http://dali.gaohongyu789.top/Article/details/gtzysekhqy.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtvjzgndlg.html

[G01] 定义类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtciyzpdxg.html

Py:   class User: pass
来源：http://dali.pycfn.com/Article/details/gtiqfribrc.html

PHP:  class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtrkuegtrt.html

JS:   class User {}
来源：http://dali.tanke756.top/Article/details/gtadnycese.html

TS:   class User { name: string = ""; }
来源：http://dali.svipenyu.cn/Article/details/gtahbiiguv.html

Java: class User {}
来源：http://dali.0kj1m.cn/Article/details/gthlcuydjh.html

Go:   type User struct { Name string }
来源：http://dali.hywenlv.cn/Article/details/gtvnwhmjic.html

Ruby: class User; end
来源：http://dali.zhongyouzk.top/Article/details/gtdpqhrcju.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gtezptjylp.html

[G02] 构造函数
来源：http://dali.ppjwa.cn/Article/details/gtjldnyzpv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gtsqgtvvlr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.9152youxi.cn/Article/details/gtrtvpzfuk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gtgffbdaya.html

TS:   constructor(public name: string) {}
来源：http://dali.ybcxt.top/Article/details/gtgyxdecnf.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtjtuiohrh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daxiang520.top/Article/details/gttntxwxkx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhixingplan.top/Article/details/gtvnbzmumj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiutvmbau.html

[G03] 实例属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxywfcpw.html

Py:   self.name = "x"
来源：http://dali.9152youxi.cn/Article/details/gtrawvsmgt.html

PHP:  public string $name = "x";
来源：http://dali.9152youxi.cn/Article/details/gtnqgaimth.html

JS:   this.name = "x";
来源：http://dali.meibo888.top/Article/details/gtbkhvtxtm.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbgxmhmt.html

Java: private String name;
来源：http://dali.gaohongyu789.top/Article/details/gtcorwlbqa.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sufxvd.cn/Article/details/gtiyqmqpdu.html

Ruby: @name = "x"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwymbxuyj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hfpthk.cn/Article/details/gtxgkvpjrq.html

[G04] 定义方法
来源：http://dali.nwbrower.top/Article/details/gtehzlizwm.html

Py:   def greet(self): return self.name
来源：http://dali.cucudq.cn/Article/details/gtzvhnnrhp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtozriloky.html

JS:   greet() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtpuhpgoxd.html

TS:   greet(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtbspyhfis.html

Java: String greet() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqcjvjhid.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtmhwjcert.html

Ruby: def greet; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gthjtjetfs.html

C#:   public string Greet() => Name;
来源：http://dali.tanke756.top/Article/details/gtigrkiysh.html

[G05] 继承
来源：http://dali.yj20258888.top/Article/details/gtdxufexet.html

Py:   class Admin(User): pass
来源：http://dali.dianchejie.cn/Article/details/gtpskpkiyg.html

PHP:  class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gtaclaucnl.html

JS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtencsdplt.html

TS:   class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtqluydrie.html

Java: class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtmidxhtnk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jiagoushi.top/Article/details/gtrxbykxgs.html

Ruby: class Admin < User; end
来源：http://dali.jianghu66.top/Article/details/gtockdbztz.html

C#:   class Admin : User {}
来源：http://dali.sufxvd.cn/Article/details/gtbgtywpot.html

[G06] 重写方法
来源：http://dali.jqgfzy.top/Article/details/gttlxdvgho.html

Py:   def greet(self): return "admin"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezcumoey.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gtxgqhpkfq.html

JS:   greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtgndchnef.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtnbyxbgay.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtfounjbbi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nwbrower.top/Article/details/gtjxyoeyvv.html

Ruby: def greet; "admin"; end
来源：http://dali.nanxinkj.top/Article/details/gtjetsthzw.html

C#:   public override string Greet() => "admin";
来源：http://dali.xziqi.cn/Article/details/gtuleyqcbz.html

[G07] 调用父类方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfbttwyej.html

Py:   super().greet()
来源：http://dali.zdqjudy.top/Article/details/gthspzrcwd.html

PHP:  parent::greet();
来源：http://dali.xinyue.icu/Article/details/gttsfkjjun.html

JS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gtyuedfozn.html

TS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gtvtlohdxr.html

Java: super.greet();
来源：http://dali.birdmap.top/Article/details/gtofndvalf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cqqwz.cn/Article/details/gtkahqvebl.html

Ruby: super
来源：http://dali.tianlin.xyz/Article/details/gtazgemfhq.html

C#:   base.Greet();
来源：http://dali.daria6918.cn/Article/details/gtqcddczzf.html

[G08] 静态方法与属性
来源：http://dali.yangfankeji.com/Article/details/gtjfzxurvc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hywenlv.cn/Article/details/gtuobinxnf.html

PHP:  public static function f() {}
来源：http://dali.yueranfly.top/Article/details/gtefqbvsgg.html

JS:   static f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdnhsialu.html

TS:   static f(): void {}
来源：http://dali.ivvv.top/Article/details/gtmupchgpu.html

Java: static void f() {}
来源：http://dali.andypj.xyz/Article/details/gtcxhnfohz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yanxiufei.cn/Article/details/gtwoaebhbz.html

Ruby: def self.f; end
来源：http://dali.ppjwa.cn/Article/details/gtbdiysrsg.html

C#:   public static void F() {}
来源：http://dali.jinqigufen.top/Article/details/gtkpuekhnf.html

[G09] 接口 / 抽象类
来源：http://dali.aibaodan.cn/Article/details/gttlpnbmpd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ivvv.top/Article/details/gtmdfixckt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnqzz.top/Article/details/gtbowtuflu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj20258888.top/Article/details/gtzvwqtkwi.html

TS:   interface Shape { area(): number; }
来源：http://dali.hfpthk.cn/Article/details/gtpsewadob.html

Java: interface Shape { double area(); }
来源：http://dali.zhoulong.xyz/Article/details/gtrywkeghn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwsjgzdbl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tian-w.cn/Article/details/gtmjbsprrq.html

C#:   interface IShape { double Area(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtgiaxiyfa.html

[G10] 访问控制
来源：http://dali.ybcxt.top/Article/details/gtptxwrocs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.meibo888.top/Article/details/gtqmlvroqp.html

PHP:  public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtzsiutoba.html

JS:   #private 字段；其余公开
来源：http://dali.aibaodan.cn/Article/details/gtylksljeu.html

TS:   public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtcgdleafk.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigufen.top/Article/details/gtuikyznlo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tian-w.cn/Article/details/gthfevxowp.html

Ruby: public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtylydheoc.html

C#:   public / protected / private / internal
来源：http://dali.guannengcc.top/Article/details/gtvcxdqltm.html

[G11] getter / setter
来源：http://dali.zhiwuduotai.top/Article/details/gtkneoeqkf.html

Py:   @property 与 @x.setter
来源：http://dali.daria6918.cn/Article/details/gtkffsnkbr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gtkajwfmje.html

JS:   get name() { return this._name; }
来源：http://dali.gogol.net.cn/Article/details/gtbbjulujm.html

TS:   get name(): string { return this._name; }
来源：http://dali.gotoacloud.top/Article/details/gtvetwmikl.html

Java: public String getName() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtdfudjenm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtgfhecmnx.html

Ruby: attr_accessor :name
来源：http://dali.dianchejie.cn/Article/details/gtkqgtifqy.html

C#:   public string Name { get; set; }
来源：http://dali.hongshengwenyu.top/Article/details/gtzodsirfl.html

[G12] 对象转字符串
来源：http://dali.fengsongda.top/Article/details/gteoryjyuw.html

Py:   def __str__(self): return self.name
来源：http://dali.gotoacloud.top/Article/details/gtdiittyha.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gtkzxylfbi.html

JS:   toString() { return this.name; }
来源：http://dali.316326.xyz/Article/details/gtbbkceipj.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gthddczvbf.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtuxbpcpce.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gttwdlfmen.html

Ruby: def to_s; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gtzrlhablg.html

C#:   public override string ToString() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gteulqjimq.html

[G13] 判断对象类型
来源：http://dali.chenjidiqi.icu/Article/details/gtzkkbcxdu.html

Py:   isinstance(u, User)
来源：http://dali.hnqzz.top/Article/details/gttaggqnmc.html

PHP:  $u instanceof User
来源：http://dali.tanke756.top/Article/details/gtkxiejukb.html

JS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtitagqijj.html

TS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtpihddjlx.html

Java: u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtjvlakimi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ydzc1.top/Article/details/gtgqnmrtyz.html

Ruby: u.is_a?(User)
来源：http://dali.smart0.xyz/Article/details/gtkawprrvg.html

C#:   u is User
来源：http://dali.zycfv.cn/Article/details/gtatszoosb.html

[G14] 数据类 / record
来源：http://dali.guowangkeji.top/Article/details/gtjlqraieh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgufenzy.top/Article/details/gttkblpwtp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cdnleiting.top/Article/details/gtxztrzxaj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yangfankeji.com/Article/details/gtpozfpbpi.html

TS:   type User = { name: string; age: number };
来源：http://dali.sweek.top/Article/details/gtmejhgkzw.html

Java: record User(String name, int age) {}
来源：http://dali.9152youxi.cn/Article/details/gtdajjzooo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhongyouzk.top/Article/details/gtzlrsvbax.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.smart0.xyz/Article/details/gtfabapyje.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258888.top/Article/details/gtmqhnextv.html

[G15] 枚举
来源：http://dali.jiagoushi.top/Article/details/gtmnfizjwz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhoulong.xyz/Article/details/gtckzaakof.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jqgufenzy.top/Article/details/gtencclbtj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shzxlz.cn/Article/details/gtngabtxmz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvxaysnlo.html

Java: enum Color { RED, GREEN }
来源：http://dali.c1oappe.top/Article/details/gttrpvzpfh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258888.top/Article/details/gtvhwnazbp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangtech.top/Article/details/gtmygbnanu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gtfwkonaga.html

[G16] 对象转数组 / 字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsdatlkxm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daria6918.cn/Article/details/gttpfvyzry.html

PHP:  get_object_vars($obj);
来源：http://dali.iojbl.cn/Article/details/gtqszohuis.html

JS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gttmcaruaw.html

TS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtfvesqjpw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.meibo888.top/Article/details/gtzzaqxidt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hammf.cn/Article/details/gtfnbcbbat.html

Ruby: obj.instance_variables
来源：http://dali.zhongyouzk.top/Article/details/gtnydfqclc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj202588.top/Article/details/gtflgqegsz.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtsscwaxzx.html

H. 异常与错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gtchczudig.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtndzfpjyr.html

[H01] try / catch 基础
来源：http://dali.shanyushiyangkeji.top/Article/details/gtepsoenpg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuxming.cn/Article/details/gtudjuljdd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hammf.cn/Article/details/gtzbqtpmgx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gtkzceyccu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gtqkzpcsoa.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gtgqvvjrhf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.0kj1m.cn/Article/details/gtszpixlsw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ybcxt.top/Article/details/gtxsjmxljr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.kuanghao11.cn/Article/details/gtdrmliiwq.html

[H02] finally / ensure 收尾
来源：http://dali.tianlin.xyz/Article/details/gttohhjywo.html


<!-- 参考信息 -->