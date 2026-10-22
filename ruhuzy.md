代发 wailian999

Go:   if s == "" {}
来源：http://dali.sufxvd.cn/Article/details/gtjpxkgjzd.html

Ruby: if s.empty?
来源：http://dali.nwbrower.top/Article/details/gtyncezavn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jlsjyb.cn/Article/details/gtayxpquia.html

[E21] 超长截断加省略号
来源：http://dali.hysaishi.cn/Article/details/gtilhcitgp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tanke756.top/Article/details/gtbcyxxcen.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gteowjcjjv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtdpkvvkdk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtpdihaoos.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtgmrnqprs.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhixingplan.top/Article/details/gthxfamkwr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gtxeyhsbkf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtjaheifgn.html

[E22] 字节长度与字符长度
来源：http://dali.svipenyu.cn/Article/details/gtbugplesa.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sysykeji.top/Article/details/gtwrdcrgtd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxmwcbqs.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gtedqrqhuc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtpjvxocjf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hysaishi.cn/Article/details/gtyycvorhi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhixingplan.top/Article/details/gthxlqfcfr.html

Ruby: s.bytesize;  s.length
来源：http://dali.yuanzhike.top/Article/details/gtsiovcmgf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswhyevib.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtvdutgeyc.html

F. 文件与目录
来源：http://dali.zhoulong.xyz/Article/details/gtwmwbowgt.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gthhaqsydn.html

[F01] 读取整个文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtyfimepwd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.dashuyun.cn/Article/details/gtmsfmobfk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtidkscpgz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hnqzz.top/Article/details/gtbuucsaok.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.c1oappe.top/Article/details/gtkisgpqbg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gtnsncfpbb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.wangshuangyany.cn/Article/details/gtnjvqpglt.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtprxtvrid.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtvpcokqhw.html

[F02] 逐行读取文件
来源：http://dali.gaohongyu789.top/Article/details/gtmleulkgp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.316326.xyz/Article/details/gttzxwammp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shangyingyoupin.top/Article/details/gtmibxqmtc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sxryk.cn/Article/details/gtenuvkdlq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hfpthk.cn/Article/details/gtyabgrrda.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jiagoushi.top/Article/details/gtbkmedfdx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlgebmxum.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxlaarxrf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jlsjyb.cn/Article/details/gtfpbgarmn.html

[F03] 写入文件（覆盖）
来源：http://dali.wangdashe.top/Article/details/gtvspmfkge.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hywenlv.cn/Article/details/gtqluqjmba.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nanxinkj.top/Article/details/gtabrcedru.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwprjpwsw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gtlmsrefze.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.iojbl.cn/Article/details/gtitawrurc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.wangshuangyany.cn/Article/details/gthfusywwj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigfzy.top/Article/details/gttxckeszh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gtcvxlucqs.html

[F04] 追加写入文件
来源：http://dali.guowangkeji.top/Article/details/gtsrkzjfvz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yongpay.top/Article/details/gtfstrteit.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj20258888.top/Article/details/gtjxdozcta.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tian-w.cn/Article/details/gtskavghpv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tianlin.xyz/Article/details/gtbukexibs.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xinyue.icu/Article/details/gtnlrzfcsh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ivvv.top/Article/details/gttehkqlte.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xuanzx.com/Article/details/gtswyocywa.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.fengsongda.top/Article/details/gteqrbtsxd.html

[F05] 判断文件或目录是否存在
来源：http://dali.jqgufenzy.top/Article/details/gtcmplbjqb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinqigfzy.top/Article/details/gtlemrxakd.html

PHP:  file_exists("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtmbheerqb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtujvupxgu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtgixxxsyp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gtaxthczyu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.birdmap.top/Article/details/gtfyfedzly.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtuceaojpn.html

C#:   File.Exists("a.txt")
来源：http://dali.yongpay.top/Article/details/gtewhzelzz.html

[F06] 删除文件
来源：http://dali.gotoacloud.top/Article/details/gtbnwnihjm.html

Py:   os.remove("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtajnibjoy.html

PHP:  unlink("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtzxhigiwv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtjkgizplm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gthaflbjpp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gtfjgeblvu.html

Go:   os.Remove("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthyeqknz.html

Ruby: File.delete("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtcohshbel.html

C#:   File.Delete("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtqnmvfjaf.html

[F07] 创建目录（含多级）
来源：http://dali.quarkkingdee.top/Article/details/gtpdhfsghn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gttcxgrray.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxuanxn.top/Article/details/gtdcbwbqmy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.andypj.xyz/Article/details/gtqipeevbg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gtdbkgiouk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ybcxt.top/Article/details/gtauycnozr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbyvpxivz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtflmwzlqg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yangfankeji.com/Article/details/gtstmxpfcb.html

[F08] 遍历目录
来源：http://dali.vqdsnc.cn/Article/details/gtafkzkjui.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenjidiqi.icu/Article/details/gtsnvmgaxd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tianlin.xyz/Article/details/gtdaqbytjg.html

JS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gtzezuhlzl.html

TS:   fs.readdirSync("dir")
来源：http://dali.gzhubu.top/Article/details/gtkwhuflvl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.pycfn.com/Article/details/gtewztlkbi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nanxinkj.top/Article/details/gtmfcbzmil.html

Ruby: Dir.children("dir")
来源：http://dali.dashuyun.cn/Article/details/gtbfmnuluu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtdmujnsja.html

[F09] 获取文件大小
来源：http://dali.jinqigufen.top/Article/details/gtashwsini.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sweek.top/Article/details/gtkswmahyz.html

PHP:  filesize("a.txt");
来源：http://dali.havefunace.top/Article/details/gtvqwcrwwp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gtjialnzam.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxuanxn.top/Article/details/gtnjjiwzty.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gttbfjhoqc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqpprxbgg.html

Ruby: File.size("a.txt")
来源：http://dali.havefunace.top/Article/details/gtyjsngduj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.haohaochexian.top/Article/details/gtifkmrrks.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.daria6918.cn/Article/details/gtqmezqing.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtegasznvg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtvpxnwgdf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtjdaenncy.html

TS:   path.extname("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtmceftjyt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhiwuduotai.top/Article/details/gtkebtfdtp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtluekobwh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtnuzmcywa.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gthxkimvpv.html

[F11] 复制与移动文件
来源：http://dali.tianlin.xyz/Article/details/gtdfhplylw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtvhxisnft.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtruienctw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtzbrsmyuc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gthggceltt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.svipenyu.cn/Article/details/gtsfjumiud.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.iojbl.cn/Article/details/gtxlaqnnck.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtdqagzulv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.havefunace.top/Article/details/gtzzmuwken.html

[F12] CSV 读写
来源：http://dali.smart0.xyz/Article/details/gtvaluklne.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dashuyun.cn/Article/details/gthoneolnt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cdnleiting.top/Article/details/gtzqfxlxvl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gzhubu.top/Article/details/gthrvsfuxk.html

TS:   // 同上
来源：http://dali.hywenlv.cn/Article/details/gtuoxpmenv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cheryme.top/Article/details/gtvifefhob.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.bjfxy.top/Article/details/gtpxkoszlo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xinyue.icu/Article/details/gtntkapypu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.iojbl.cn/Article/details/gtkiwignza.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtxyyfvsqj.html

G. 面向对象
来源：http://dali.zhixingplan.top/Article/details/gtznodkhln.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtcdynzbme.html

[G01] 定义类
来源：http://dali.aibaodan.cn/Article/details/gtzosfuhqm.html

Py:   class User: pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gttxumwehy.html

PHP:  class User {}
来源：http://dali.gogol.net.cn/Article/details/gtcegozmlk.html

JS:   class User {}
来源：http://dali.dashuyun.cn/Article/details/gttnmajktb.html

TS:   class User { name: string = ""; }
来源：http://dali.zhiwuduotai.top/Article/details/gtgebsayap.html

Java: class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtslrqwxeu.html

Go:   type User struct { Name string }
来源：http://dali.zhoulong.xyz/Article/details/gtjzgxkdrv.html

Ruby: class User; end
来源：http://dali.sufxvd.cn/Article/details/gtjtcvpdmr.html

C#:   class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtewwlbpwh.html

[G02] 构造函数
来源：http://dali.ppjwa.cn/Article/details/gtjeldfnzl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.wangshuangyany.cn/Article/details/gtyylyhztk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sufxvd.cn/Article/details/gtwxuozrib.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yongpay.top/Article/details/gtvncdbetz.html

TS:   constructor(public name: string) {}
来源：http://dali.iojbl.cn/Article/details/gtasvybvcd.html

Java: User(String name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gtkddmjzxo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigfzy.top/Article/details/gtrsyivagv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jyoumei.cn/Article/details/gtbxooxxou.html

C#:   public User(string name) { Name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gtiiupmhup.html

[G03] 实例属性
来源：http://dali.sxryk.cn/Article/details/gtkwrxghag.html

Py:   self.name = "x"
来源：http://dali.ivvv.top/Article/details/gtaqhxbara.html

PHP:  public string $name = "x";
来源：http://dali.quarkkingdee.top/Article/details/gttzluqbee.html

JS:   this.name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtxrvpfxdm.html

TS:   name: string = "x";
来源：http://dali.c1oappe.top/Article/details/gtxszpjlpd.html

Java: private String name;
来源：http://dali.yj202588.top/Article/details/gtzroajgxy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwoflzrbz.html

Ruby: @name = "x"
来源：http://dali.xuanzx.com/Article/details/gtrfoijysq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtvfvvtmpl.html

[G04] 定义方法
来源：http://dali.yueranfly.top/Article/details/gtgcorasol.html

Py:   def greet(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gtowptletz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtyicdtymw.html

JS:   greet() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtydbjtvfs.html

TS:   greet(): string { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtgssjsjkp.html

Java: String greet() { return name; }
来源：http://dali.shuidangran.top/Article/details/gtxtnksdpb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtpcsgnuwx.html

Ruby: def greet; @name; end
来源：http://dali.aibaodan.cn/Article/details/gtumsqjori.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigufen.top/Article/details/gtdcsamfik.html

[G05] 继承
来源：http://dali.feifeiyinyue.top/Article/details/gthyroiwdp.html

Py:   class Admin(User): pass
来源：http://dali.chenjidiqi.icu/Article/details/gtpgcnhcoz.html

PHP:  class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gttzyztacb.html

JS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gttkbdinva.html

TS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtcbaznwjj.html

Java: class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gttcngjnhm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hfpthk.cn/Article/details/gtwkmwpmfc.html

Ruby: class Admin < User; end
来源：http://dali.nwbrower.top/Article/details/gtvzldlpeo.html

C#:   class Admin : User {}
来源：http://dali.dianchejie.cn/Article/details/gtnuywiqtd.html

[G06] 重写方法
来源：http://dali.tanke756.top/Article/details/gtikrgznik.html

Py:   def greet(self): return "admin"
来源：http://dali.tian-w.cn/Article/details/gtjqvbselj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtxtkqskbg.html

JS:   greet() { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtoryrkrbw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtofvzuked.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gtbxcwxoqr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigfzy.top/Article/details/gtxiauzuqx.html

Ruby: def greet; "admin"; end
来源：http://dali.aibaodan.cn/Article/details/gtozixrnzc.html

C#:   public override string Greet() => "admin";
来源：http://dali.0kj1m.cn/Article/details/gtqzicljhu.html

[G07] 调用父类方法
来源：http://dali.yvedp.cn/Article/details/gtbycpyrdt.html

Py:   super().greet()
来源：http://dali.ydzc1.top/Article/details/gtnztxbacr.html

PHP:  parent::greet();
来源：http://dali.daxiang520.top/Article/details/gtiorqzpzz.html

JS:   super.greet();
来源：http://dali.andypj.xyz/Article/details/gthqirxqkp.html

TS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtcbcmbcmi.html

Java: super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gtvonwgfop.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yvedp.cn/Article/details/gtwzlyisma.html

Ruby: super
来源：http://dali.zhongyouzk.top/Article/details/gtiavhirom.html

C#:   base.Greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtdlubtauo.html

[G08] 静态方法与属性
来源：http://dali.yangfankeji.com/Article/details/gtgmwnbegb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnqzz.top/Article/details/gthmhrueit.html

PHP:  public static function f() {}
来源：http://dali.cqqwz.cn/Article/details/gtciromigf.html

JS:   static f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtgnzskjiz.html

TS:   static f(): void {}
来源：http://dali.hywenlv.cn/Article/details/gtbbshuosk.html

Java: static void f() {}
来源：http://dali.yj20258888.top/Article/details/gtgdprjtok.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dianchejie.cn/Article/details/gtvutjjhab.html

Ruby: def self.f; end
来源：http://dali.dianchejie.cn/Article/details/gtldpxqaux.html

C#:   public static void F() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtqnjzxbad.html

[G09] 接口 / 抽象类
来源：http://dali.cashguo.top/Article/details/gtnhomtaet.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zycfv.cn/Article/details/gtvevhtsxu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jianghu66.top/Article/details/gtsjiqvdci.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pengpengdd.cyou/Article/details/gttsbzfwwa.html

TS:   interface Shape { area(): number; }
来源：http://dali.andypj.xyz/Article/details/gtktmauqtf.html

Java: interface Shape { double area(); }
来源：http://dali.dashuyun.cn/Article/details/gtywaejgqe.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.316326.xyz/Article/details/gtvvawkhbs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.havefunace.top/Article/details/gtgdvxmsjb.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhengqikj.top/Article/details/gtgjdqnhfs.html

[G10] 访问控制
来源：http://dali.aibaodan.cn/Article/details/gtwwxubqfh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangtech.top/Article/details/gtidpvusbr.html

PHP:  public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gtriigrwyh.html

JS:   #private 字段；其余公开
来源：http://dali.hammf.cn/Article/details/gtzinnkytc.html

TS:   public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gtdoghubad.html

Java: public / protected / private / 默认包级
来源：http://dali.hongshengwenyu.top/Article/details/gtzrgmlbgb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhikeglm.html

Ruby: public / protected / private
来源：http://dali.jianghu66.top/Article/details/gtkosrkhzl.html

C#:   public / protected / private / internal
来源：http://dali.yanxiufei.cn/Article/details/gtdpwwkytm.html

[G11] getter / setter
来源：http://dali.hongshengwenyu.top/Article/details/gthlfbuxek.html

Py:   @property 与 @x.setter
来源：http://dali.jqgfzy.top/Article/details/gtiqdcadxj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtlvzzioae.html

JS:   get name() { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gtolinlett.html

TS:   get name(): string { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gtlqnfxvms.html

Java: public String getName() { return name; }
来源：http://dali.cheryme.top/Article/details/gtbjdsmpnp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpgzcahyh.html

Ruby: attr_accessor :name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjzacvgi.html

C#:   public string Name { get; set; }
来源：http://dali.jqgfzy.top/Article/details/gtespsokno.html

[G12] 对象转字符串
来源：http://dali.aizwys.cn/Article/details/gtblfqokcw.html

Py:   def __str__(self): return self.name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmlrlsovf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtqkufvnaj.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtorqcdapv.html

TS:   toString(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtkawlwogo.html

Java: @Override public String toString() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtdfelkkug.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gtsrjglyma.html

Ruby: def to_s; @name; end
来源：http://dali.ppjwa.cn/Article/details/gtsyjfehof.html

C#:   public override string ToString() => Name;
来源：http://dali.yj202588.top/Article/details/gtcwaespii.html

[G13] 判断对象类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwelnuvfz.html

Py:   isinstance(u, User)
来源：http://dali.c1oappe.top/Article/details/gtpbqeuuan.html

PHP:  $u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtygpkzjii.html

JS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtbqrpyxgl.html

TS:   u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtomrqolxr.html

Java: u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtdzhegwyc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuanzx.com/Article/details/gtncagjdpj.html

Ruby: u.is_a?(User)
来源：http://dali.havefunace.top/Article/details/gtbnwonjsf.html

C#:   u is User
来源：http://dali.tanke756.top/Article/details/gtinenqoke.html

[G14] 数据类 / record
来源：http://dali.yangfankeji.com/Article/details/gtpiiegdzq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.kuanghao11.cn/Article/details/gtmzbovqoy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shzxlz.cn/Article/details/gtawjsssbr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.iojbl.cn/Article/details/gtlqdqpqxf.html

TS:   type User = { name: string; age: number };
来源：http://dali.zdqjudy.top/Article/details/gtbmafcsyf.html

Java: record User(String name, int age) {}
来源：http://dali.xuetiantiany.cn/Article/details/gthinmkqms.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guowangkeji.top/Article/details/gtpumnpgji.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sxryk.cn/Article/details/gtzaoenguf.html

C#:   record User(string Name, int Age);
来源：http://dali.snrcjt.cn/Article/details/gtalsxxzbk.html

[G15] 枚举
来源：http://dali.yuxming.cn/Article/details/gtjsjairbi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtynodrjdc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthhbxifmh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.c1oappe.top/Article/details/gtbescpkdr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gtgtfenjtc.html

Java: enum Color { RED, GREEN }
来源：http://dali.mhx1999.top/Article/details/gtnnjlijab.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yongpay.top/Article/details/gtshwufstu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yvedp.cn/Article/details/gtgcxanvly.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gthchsvzcu.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigfzy.top/Article/details/gtjaobestc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.0kj1m.cn/Article/details/gtknsxqmym.html

PHP:  get_object_vars($obj);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfqxzwuw.html

JS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwisrlnk.html

TS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gtuxhbjopc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nwbrower.top/Article/details/gtchhvgpgg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daria6918.cn/Article/details/gtsoesjqdm.html

Ruby: obj.instance_variables
来源：http://dali.snrcjt.cn/Article/details/gtrlinalxt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xylfe.cn/Article/details/gtunntpbcy.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvaomfov.html

H. 异常与错误处理
来源：http://dali.hywenlv.cn/Article/details/gtrdlhmche.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtmivsvzyk.html

[H01] try / catch 基础
来源：http://dali.xylfe.cn/Article/details/gtqjeafidb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jyoumei.cn/Article/details/gttrjoifwu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtbetuymod.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gtjqwykdlp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gtpnyhcwet.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yanxiufei.cn/Article/details/gtmsnolqtn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.svipenyu.cn/Article/details/gtcotzgyat.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.quarkkingdee.top/Article/details/gtqdtlfqtg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cucudq.cn/Article/details/gtprcwwuln.html

[H02] finally / ensure 收尾
来源：http://dali.tanke756.top/Article/details/gtmboaiqxr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhongyouzk.top/Article/details/gthdstupsf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtemacfqkl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtampkloys.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gthiotzedg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtuqjihpgw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tian-w.cn/Article/details/gtyztxusvk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gzhubu.top/Article/details/gtfjdcvdpn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gteyuhvlda.html


<!-- 参考信息 -->