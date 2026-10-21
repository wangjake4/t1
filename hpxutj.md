代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cheryme.top/Article/details/gtqaakcaot.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtvdzwxmyl.html

TS:   if (s === "") {}
来源：http://dali.hnxiangtu.top/Article/details/gtswreowui.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtxesxwbmv.html

Go:   if s == "" {}
来源：http://dali.hongshengwenyu.top/Article/details/gthfhxdimd.html

Ruby: if s.empty?
来源：http://dali.zhoulong.xyz/Article/details/gtfbddwsrb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fzhhl.top/Article/details/gtmdqkblvb.html

[E21] 超长截断加省略号
来源：http://dali.yuxming.cn/Article/details/gtxohqmnhl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zycfv.cn/Article/details/gtisiatlsj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjpmklohs.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtjclvmvkv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtuhjymljx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtowgfvfhb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jlsjyb.cn/Article/details/gtpgsnsoge.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtdbxagwrf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtwirhyppi.html

[E22] 字节长度与字符长度
来源：http://dali.gotoacloud.top/Article/details/gtqmmvhufw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gzhubu.top/Article/details/gttgpqpvcp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtkeexzgnx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ppjwa.cn/Article/details/gtorbxyhqf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gterymofke.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtawshmqha.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbfnlncmp.html

Ruby: s.bytesize;  s.length
来源：http://dali.shzxlz.cn/Article/details/gtdbcjlqel.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ybcxt.top/Article/details/gtidsavgqa.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtvfxtvnku.html

F. 文件与目录
来源：http://dali.bjfxy.top/Article/details/gtzchnzmqd.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gthqtffwnb.html

[F01] 读取整个文件
来源：http://dali.pycfn.com/Article/details/gtpbzkeqgn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tanke756.top/Article/details/gtjjfyfxdm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.havefunace.top/Article/details/gtdkhbvsek.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenzaomai.com/Article/details/gtdjmikiki.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gtyscaoivw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtkncpggoh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhixingplan.top/Article/details/gtrcbsfyhb.html

Ruby: File.read("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtgqimqjha.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtvdufsjbm.html

[F02] 逐行读取文件
来源：http://dali.tian-w.cn/Article/details/gtgkisubrs.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shangyingyoupin.top/Article/details/gtssgfqwbe.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jqgfzy.top/Article/details/gtentrqcne.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.kuanghao11.cn/Article/details/gtcgkexmwt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shuidangran.top/Article/details/gtrhpjuuet.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gtqdmaclbb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhengqikj.top/Article/details/gtoxbedgsu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jqgufenzy.top/Article/details/gtrmgpsrgy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dianchejie.cn/Article/details/gtrvcxcczg.html

[F03] 写入文件（覆盖）
来源：http://dali.yanxiufei.cn/Article/details/gtywnuuwyh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.feifeiyinyue.top/Article/details/gtsuhrukpa.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gtemvtqbjf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gtmjnqvosy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtmytjyvhc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jianghu66.top/Article/details/gtsrjimytr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuanzx.com/Article/details/gtgsvmptbu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.svipenyu.cn/Article/details/gtfvchagem.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cucudq.cn/Article/details/gtdioryfgw.html

[F04] 追加写入文件
来源：http://dali.havefunace.top/Article/details/gtdvrvhdol.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.bjfxy.top/Article/details/gtpnadnisu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yanxiufei.cn/Article/details/gtpuucxepw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj202588.top/Article/details/gtcskauxba.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shzxlz.cn/Article/details/gtqjmtrzec.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hongshengwenyu.top/Article/details/gtgyirrzuw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gogol.net.cn/Article/details/gthqeyqtpo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.fzhhl.top/Article/details/gtcgagbiph.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.316326.xyz/Article/details/gtnpbwicwj.html

[F05] 判断文件或目录是否存在
来源：http://dali.fzhhl.top/Article/details/gtbyosypce.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jyoumei.cn/Article/details/gtoocuukzk.html

PHP:  file_exists("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtceotfdud.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtwusdsknt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtthgpxqph.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtotgucags.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.snrcjt.cn/Article/details/gtpccokvuc.html

Ruby: File.exist?("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcacchwru.html

C#:   File.Exists("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtwryaulty.html

[F06] 删除文件
来源：http://dali.yuanzhike.top/Article/details/gtcbttsoci.html

Py:   os.remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtdzaufbbp.html

PHP:  unlink("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtubhxqltp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtjoqellcs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtwnotexxt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtfctmrkrd.html

Go:   os.Remove("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtnsoctvvd.html

Ruby: File.delete("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gthyupntqt.html

C#:   File.Delete("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtiucbmrmb.html

[F07] 创建目录（含多级）
来源：http://dali.sysykeji.top/Article/details/gtgdteaimu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.bjfxy.top/Article/details/gtzinpussi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.fengsongda.top/Article/details/gtqoamdzof.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cucudq.cn/Article/details/gtmasidzcj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gtvlsropze.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkitfcjac.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gotoacloud.top/Article/details/gtmgdsnzte.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.haohaochexian.top/Article/details/gtkezvtscv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgfzy.top/Article/details/gtijyucbxb.html

[F08] 遍历目录
来源：http://dali.nanxinkj.top/Article/details/gtzvqwcvgk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdzaxnqe.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.wangdashe.top/Article/details/gtndghlmfe.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtyolqfgle.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenzaomai.com/Article/details/gtwvepsyme.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.snrcjt.cn/Article/details/gtbzylvnqc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shuidangran.top/Article/details/gttbuoaxif.html

Ruby: Dir.children("dir")
来源：http://dali.dashuyun.cn/Article/details/gtrutwqhcx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtuninusch.html

[F09] 获取文件大小
来源：http://dali.yuanzhike.top/Article/details/gtcrlehvdn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtkmvbbjik.html

PHP:  filesize("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtfxrxamqy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gtbrwqvyko.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jlsjyb.cn/Article/details/gtbuftopko.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtmsdhglri.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgufenzy.top/Article/details/gtghixyarq.html

Ruby: File.size("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtfwuifzbg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangdashe.top/Article/details/gtdudatjpv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tian-w.cn/Article/details/gtczkjvxag.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtacnhvxoc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtnlvcnkuo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtnrzutelr.html

TS:   path.extname("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtbodfcurh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258888.top/Article/details/gtgtdmdcod.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtpapdnonc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gttbctnpew.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtseixwruw.html

[F11] 复制与移动文件
来源：http://dali.c1oappe.top/Article/details/gtcwzzahwk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtijniwtdh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tanke756.top/Article/details/gtyfiqwglx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtmfffvdyc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzplvaexo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gtfccxishl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jqgufenzy.top/Article/details/gtgqxyilpt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtagnztkbc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jianghu66.top/Article/details/gtgcskwlwf.html

[F12] CSV 读写
来源：http://dali.316326.xyz/Article/details/gtoxbczalz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ppjwa.cn/Article/details/gtvwowvpdw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.daria6918.cn/Article/details/gtucyowxiq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tianlin.xyz/Article/details/gtizmavsmy.html

TS:   // 同上
来源：http://dali.yonumen.top/Article/details/gtisglrmxe.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daria6918.cn/Article/details/gtjishisbl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xinyue.icu/Article/details/gtoxxwrbrf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pengpengdd.cyou/Article/details/gttbhqwdou.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.daria6918.cn/Article/details/gtbrxpiqci.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtenvtrtqg.html

G. 面向对象
来源：http://dali.0kj1m.cn/Article/details/gtxsmhmisc.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtdgxngvwz.html

[G01] 定义类
来源：http://dali.gotoacloud.top/Article/details/gtaovmxlmj.html

Py:   class User: pass
来源：http://dali.havefunace.top/Article/details/gtvxxamdox.html

PHP:  class User {}
来源：http://dali.tanke756.top/Article/details/gtnznoncsp.html

JS:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtrkswhlzv.html

TS:   class User { name: string = ""; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwxtsjbh.html

Java: class User {}
来源：http://dali.jqgfzy.top/Article/details/gtxnvguadi.html

Go:   type User struct { Name string }
来源：http://dali.sufxvd.cn/Article/details/gtriawzbpx.html

Ruby: class User; end
来源：http://dali.wangdashe.top/Article/details/gtzgmifoyb.html

C#:   class User {}
来源：http://dali.jianghu66.top/Article/details/gtdwshjunp.html

[G02] 构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtbwfsaiwx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gtjfpfvdoy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.wangdashe.top/Article/details/gtlytnzwec.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gtmcqpgkco.html

TS:   constructor(public name: string) {}
来源：http://dali.dianchejie.cn/Article/details/gtfhuaiqbc.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtqeokfgvg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hysaishi.cn/Article/details/gtkiyrdrnq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dashuyun.cn/Article/details/gtalytgwsu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cqqwz.cn/Article/details/gtwetqgqml.html

[G03] 实例属性
来源：http://dali.birdmap.top/Article/details/gtvabojesq.html

Py:   self.name = "x"
来源：http://dali.0kj1m.cn/Article/details/gtrigzboyr.html

PHP:  public string $name = "x";
来源：http://dali.meibo888.top/Article/details/gtwuilopmh.html

JS:   this.name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtpfwbqzdy.html

TS:   name: string = "x";
来源：http://dali.xinyue.icu/Article/details/gtryyukczz.html

Java: private String name;
来源：http://dali.chenlongwang.top/Article/details/gtnoaqhdus.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ivvv.top/Article/details/gtdsxncorw.html

Ruby: @name = "x"
来源：http://dali.yangfankeji.com/Article/details/gttrvxvbmg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ivvv.top/Article/details/gtatkcrjva.html

[G04] 定义方法
来源：http://dali.gaohongyu789.top/Article/details/gtdvlpixju.html

Py:   def greet(self): return self.name
来源：http://dali.yonumen.top/Article/details/gtipqnffsa.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtfcswwoat.html

JS:   greet() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtowvxmjnx.html

TS:   greet(): string { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gthafiwurr.html

Java: String greet() { return name; }
来源：http://dali.sweek.top/Article/details/gtbgvsqqly.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtzvtprlqx.html

Ruby: def greet; @name; end
来源：http://dali.zhengqikj.top/Article/details/gtauheutuc.html

C#:   public string Greet() => Name;
来源：http://dali.jyoumei.cn/Article/details/gtkwhusdko.html

[G05] 继承
来源：http://dali.xylfe.cn/Article/details/gtdsbresoc.html

Py:   class Admin(User): pass
来源：http://dali.gotoacloud.top/Article/details/gtqsziuywt.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtisklfrft.html

JS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtrilfuwaw.html

TS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtkanajnup.html

Java: class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtrdtirlyn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yongpay.top/Article/details/gtbdmxzluz.html

Ruby: class Admin < User; end
来源：http://dali.zhiwuduotai.top/Article/details/gtrcvspkjg.html

C#:   class Admin : User {}
来源：http://dali.aibaodan.cn/Article/details/gtezjuduag.html

[G06] 重写方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqskqchg.html

Py:   def greet(self): return "admin"
来源：http://dali.gzhubu.top/Article/details/gtrwnhrlfl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtsjliwyrs.html

JS:   greet() { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtuzgkxsun.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtqurkhdbc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtpoimzfql.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hysaishi.cn/Article/details/gtwsbzryaj.html

Ruby: def greet; "admin"; end
来源：http://dali.nwbrower.top/Article/details/gtpntztmjz.html

C#:   public override string Greet() => "admin";
来源：http://dali.tian-w.cn/Article/details/gtiznvxwdo.html

[G07] 调用父类方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtytrlaota.html

Py:   super().greet()
来源：http://dali.yuanzhike.top/Article/details/gtagreubfi.html

PHP:  parent::greet();
来源：http://dali.zhixingplan.top/Article/details/gtmgizkhsw.html

JS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gtvtffhrfw.html

TS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gtbghgcull.html

Java: super.greet();
来源：http://dali.hysaishi.cn/Article/details/gtpfuzeqro.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jianghu66.top/Article/details/gtwcsrqoiz.html

Ruby: super
来源：http://dali.hammf.cn/Article/details/gtzhajcilg.html

C#:   base.Greet();
来源：http://dali.cqqwz.cn/Article/details/gtixmvvxyd.html

[G08] 静态方法与属性
来源：http://dali.yueranfly.top/Article/details/gtdbqvelgh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj202588.top/Article/details/gtxwuhebrw.html

PHP:  public static function f() {}
来源：http://dali.sufxvd.cn/Article/details/gtpjpwmjhv.html

JS:   static f() {}
来源：http://dali.andypj.xyz/Article/details/gtormzenix.html

TS:   static f(): void {}
来源：http://dali.pengpengdd.cyou/Article/details/gtzzdazufy.html

Java: static void f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtgocigybp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xinyue.icu/Article/details/gtfzhjmztq.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gtrjcnrflj.html

C#:   public static void F() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtrefiphcq.html

[G09] 接口 / 抽象类
来源：http://dali.meibo888.top/Article/details/gtawoxkutn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenzaomai.com/Article/details/gtvmzlmcne.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.vqdsnc.cn/Article/details/gtdcqncgxq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tian-w.cn/Article/details/gtbhkwgzao.html

TS:   interface Shape { area(): number; }
来源：http://dali.9152youxi.cn/Article/details/gtckqoienj.html

Java: interface Shape { double area(); }
来源：http://dali.zhongyouzk.top/Article/details/gtnjqkvdzz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhengqikj.top/Article/details/gtytjyeogn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ydzc1.top/Article/details/gtwwybuqiz.html

C#:   interface IShape { double Area(); }
来源：http://dali.yueranfly.top/Article/details/gtnmgokngk.html

[G10] 访问控制
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnnhsxbz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258888.top/Article/details/gtqiexecnz.html

PHP:  public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gtzitpviic.html

JS:   #private 字段；其余公开
来源：http://dali.havefunace.top/Article/details/gtxnlwpksl.html

TS:   public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gtidxtcdag.html

Java: public / protected / private / 默认包级
来源：http://dali.xylfe.cn/Article/details/gtzameydbr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hongshengwenyu.top/Article/details/gtnxrhxfrx.html

Ruby: public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gtleawtput.html

C#:   public / protected / private / internal
来源：http://dali.c1oappe.top/Article/details/gtsqutdyfg.html

[G11] getter / setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gtccyvyvkj.html

Py:   @property 与 @x.setter
来源：http://dali.wangshuangyany.cn/Article/details/gtxodkhgwo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtmqrqtfuw.html

JS:   get name() { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtkgszgyvz.html

TS:   get name(): string { return this._name; }
来源：http://dali.cucudq.cn/Article/details/gtnzelfsbq.html

Java: public String getName() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtevawvexr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhkmelxt.html

Ruby: attr_accessor :name
来源：http://dali.gzhubu.top/Article/details/gtrqtnexbr.html

C#:   public string Name { get; set; }
来源：http://dali.xylfe.cn/Article/details/gtwvwdgugt.html

[G12] 对象转字符串
来源：http://dali.yangfankeji.com/Article/details/gtyrhikhjj.html

Py:   def __str__(self): return self.name
来源：http://dali.hongshengwenyu.top/Article/details/gtkefpywqb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtmvssnpnc.html

JS:   toString() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtltjrjakx.html

TS:   toString(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtvctwdqxd.html

Java: @Override public String toString() { return name; }
来源：http://dali.cashguo.top/Article/details/gtxghfhcnl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtstljoake.html

Ruby: def to_s; @name; end
来源：http://dali.jqgfzy.top/Article/details/gtptnklymp.html

C#:   public override string ToString() => Name;
来源：http://dali.0kj1m.cn/Article/details/gtrmhmmgcv.html

[G13] 判断对象类型
来源：http://dali.shzxlz.cn/Article/details/gtulgwekfr.html

Py:   isinstance(u, User)
来源：http://dali.chenjidiqi.icu/Article/details/gtihyxywak.html

PHP:  $u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtmxibqbyj.html

JS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtefscdkca.html

TS:   u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtuclixtxf.html

Java: u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtbdlauona.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xylfe.cn/Article/details/gtaxfqgtav.html

Ruby: u.is_a?(User)
来源：http://dali.gaohongyu789.top/Article/details/gtbqkytmsd.html

C#:   u is User
来源：http://dali.jinghuilouyu.cn/Article/details/gtbkrchkty.html

[G14] 数据类 / record
来源：http://dali.cdnleiting.top/Article/details/gtvspovkro.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daria6918.cn/Article/details/gtbqqrmcdf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xylfe.cn/Article/details/gteysdvwoy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.quarkkingdee.top/Article/details/gtsgqguagw.html

TS:   type User = { name: string; age: number };
来源：http://dali.ehwqpu.com/Article/details/gtjfaxxfxz.html

Java: record User(String name, int age) {}
来源：http://dali.ydzc1.top/Article/details/gtpiaonaif.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pengpengdd.cyou/Article/details/gtwdjtmiry.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhiwuduotai.top/Article/details/gtncfrvgah.html

C#:   record User(string Name, int Age);
来源：http://dali.sweek.top/Article/details/gtnlzonmna.html

[G15] 枚举
来源：http://dali.ivvv.top/Article/details/gtkeigdcmo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhixingplan.top/Article/details/gtsatfsiwe.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.316326.xyz/Article/details/gterstafdp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cashguo.top/Article/details/gtfpyrawyk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gtlxccesrr.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuanzhike.top/Article/details/gtlkghziyg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.0kj1m.cn/Article/details/gtmrjeryfs.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangshuangyany.cn/Article/details/gtuiqctcuk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtmgekziwd.html

[G16] 对象转数组 / 字典
来源：http://dali.nwbrower.top/Article/details/gtvzuluanx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tian-w.cn/Article/details/gteobowiit.html

PHP:  get_object_vars($obj);
来源：http://dali.chenjidiqi.icu/Article/details/gtecgyqosm.html

JS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gtlncwoavk.html

TS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gthihmrijs.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhoulong.xyz/Article/details/gtaaqmejjv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj20258.top/Article/details/gtqzsqsomm.html

Ruby: obj.instance_variables
来源：http://dali.cqqwz.cn/Article/details/gtbfudwouj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gtcdqqvvlh.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtimyviebh.html

H. 异常与错误处理
来源：http://dali.sweek.top/Article/details/gtvghoqolh.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtehoogdlc.html

[H01] try / catch 基础
来源：http://dali.hfpthk.cn/Article/details/gtvyqaevwx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuanzhike.top/Article/details/gtlnjbwztc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.haohaochexian.top/Article/details/gtrtzgrvfd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gtfhnajxts.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtpqzyuxis.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinghuilouyu.cn/Article/details/gteyasqwve.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvpxelsp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangshuangyany.cn/Article/details/gtwbobcvok.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jyoumei.cn/Article/details/gtjpxzmnor.html

[H02] finally / ensure 收尾
来源：http://dali.fzhhl.top/Article/details/gtmqcevcwh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zdqjudy.top/Article/details/gtxlfedwmu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtktiofzjy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtpsmmcmfr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtcrplrivg.html


<!-- 参考信息 -->