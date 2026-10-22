代发 wailian999

Go:   if s == "" {}
来源：http://dali.daxiang520.top/Article/details/gt2agoxiasv.html

Ruby: if s.empty?
来源：http://dali.sufxvd.cn/Article/details/gt2upyakubb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cdnleiting.top/Article/details/gt2dhdpalou.html

[E21] 超长截断加省略号
来源：http://dali.fengsongda.top/Article/details/gt2pngohdmo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jqgfzy.top/Article/details/gt2poxhezbm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gt2oqniwcqs.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gt2ynnxhabr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gt2docejtjn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gt2zjoilgca.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rkyuggra.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gt2gapaufbm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gt2wgiepwlu.html

[E22] 字节长度与字符长度
来源：http://dali.sweek.top/Article/details/gt2lznkfaxs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2lqaowhqc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gt2unaljgad.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hysaishi.cn/Article/details/gt2cbqvkgph.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kwlgsaal.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gt2zwijxnkd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.daxiang520.top/Article/details/gt2dndknibm.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gvnqqpjl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yonumen.top/Article/details/gt2mtfgivto.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2yggmhcqa.html

F. 文件与目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xutntyui.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2kjlhusbx.html

[F01] 读取整个文件
来源：http://dali.ydzc1.top/Article/details/gt2yuajdssp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ivvv.top/Article/details/gt2zwjqsqjb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2wsbtmwda.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sysykeji.top/Article/details/gt2qkpaedeu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ckvaotda.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gt2bxdzhoce.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgfzy.top/Article/details/gt2clduqfnl.html

Ruby: File.read("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2gtcnvxir.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2kshaovky.html

[F02] 逐行读取文件
来源：http://dali.hnxiangtu.top/Article/details/gt2ypltqujs.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cucudq.cn/Article/details/gt2siysbitp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhengqikj.top/Article/details/gt2eelizxvo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxinkj.top/Article/details/gt2xvryptxx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ivvv.top/Article/details/gt2xrvncxna.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tanke756.top/Article/details/gt2dfqtrfou.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2brlzpazu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhengqikj.top/Article/details/gt2psifsjno.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jianghu66.top/Article/details/gt2okxpbfyy.html

[F03] 写入文件（覆盖）
来源：http://dali.nanxuanxn.top/Article/details/gt2fgtrkznp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.fzhhl.top/Article/details/gt2qzocbyqt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gt2arpxbvtj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gt2tkxhasdg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gt2qeowbvww.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yangfankeji.com/Article/details/gt2jpzeicsm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hnqzz.top/Article/details/gt2lvgsriwi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cdnleiting.top/Article/details/gt2aovflqam.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gt2tnogvqts.html

[F04] 追加写入文件
来源：http://dali.pycfn.com/Article/details/gt2baobgjay.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.redwolf501.top/Article/details/gt2caauugje.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenjidiqi.icu/Article/details/gt2koimjkng.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.0kj1m.cn/Article/details/gt2xvywnqqk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nootbjqg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.daxiang520.top/Article/details/gt2uhdjsjia.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xylfe.cn/Article/details/gt2vtuovldi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gotoacloud.top/Article/details/gt2waquxftf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xosyemjz.html

[F05] 判断文件或目录是否存在
来源：http://dali.xziqi.cn/Article/details/gt2qnflkvsd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yuanzhike.top/Article/details/gt2jubxcucw.html

PHP:  file_exists("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2gpwhklrd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2gwhdescr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2fbpxakzh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gt2dbapnvhk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2inxekvvp.html

Ruby: File.exist?("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2slokmmra.html

C#:   File.Exists("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2mammbtkr.html

[F06] 删除文件
来源：http://dali.yuanzhike.top/Article/details/gt2xaezhthe.html

Py:   os.remove("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2aseupusi.html

PHP:  unlink("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2grdlgglp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfizftg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2jvdxqylz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gt2rmntpebm.html

Go:   os.Remove("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2uxxmomjb.html

Ruby: File.delete("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2datibqqn.html

C#:   File.Delete("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2pxvhvtob.html

[F07] 创建目录（含多级）
来源：http://dali.daria6918.cn/Article/details/gt2nbjyqxli.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aizwys.cn/Article/details/gt2wejpvbzf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xylfe.cn/Article/details/gt2dpqmjdpe.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhongyouzk.top/Article/details/gt2qiciqqcc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhongyouzk.top/Article/details/gt2dgswzbld.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sysykeji.top/Article/details/gt2rnnsbjev.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gaohongyu789.top/Article/details/gt2oyxvcetp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tianlin.xyz/Article/details/gt2oekggphp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daxiang520.top/Article/details/gt2ifsgkqyl.html

[F08] 遍历目录
来源：http://dali.9152youxi.cn/Article/details/gt2stjzaffv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tian-w.cn/Article/details/gt2hzrgbnkp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxuanxn.top/Article/details/gt2hmrmibti.html

JS:   fs.readdirSync("dir")
来源：http://dali.svipenyu.cn/Article/details/gt2mjtblwvi.html

TS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gt2bpwqzbii.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ublxpgau.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gogol.net.cn/Article/details/gt2kliqgaos.html

Ruby: Dir.children("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gt2osztomvl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gzhubu.top/Article/details/gt2qootwdiw.html

[F09] 获取文件大小
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qfrvlutk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2ifcwkkfj.html

PHP:  filesize("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2khmcfdef.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hoyxvcnn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gt2rxhtredm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gt2ofgtyjeh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.havefunace.top/Article/details/gt2axtmwpgr.html

Ruby: File.size("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2msjvxqtb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhengqikj.top/Article/details/gt2hzenhgae.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxinkj.top/Article/details/gt2ineqxfei.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gt2niexgxlg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2ejlykzla.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2nvqzwfad.html

TS:   path.extname("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2iqmnoazx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenlongwang.top/Article/details/gt2cfnclenh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2itapwski.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2lbuzubwu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2nndabiwc.html

[F11] 复制与移动文件
来源：http://dali.sysykeji.top/Article/details/gt2vulpaflb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2preytarv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2wnubenzp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2jvvpdqji.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gt2mubggtbg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yvedp.cn/Article/details/gt2wafedodg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yangfankeji.com/Article/details/gt2vmffslar.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gt2luziiwou.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.fzhhl.top/Article/details/gt2xdclcvtf.html

[F12] CSV 读写
来源：http://dali.jlsjyb.cn/Article/details/gt2jcsnabza.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cashguo.top/Article/details/gt2asaetlsp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cashguo.top/Article/details/gt2udbcnlxe.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pengpengdd.cyou/Article/details/gt2pmcojidv.html

TS:   // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gt2zubbusyf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.kuanghao11.cn/Article/details/gt2ledtyuta.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ybcxt.top/Article/details/gt2htnchfdd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ygzuifvt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yangfankeji.com/Article/details/gt2rxijlhuw.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2faothuye.html

G. 面向对象
来源：http://dali.hfpthk.cn/Article/details/gt2ikagwyuc.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2cdkdztav.html

[G01] 定义类
来源：http://dali.ppjwa.cn/Article/details/gt2wdsmnwyj.html

Py:   class User: pass
来源：http://dali.jyoumei.cn/Article/details/gt2ybsugqcc.html

PHP:  class User {}
来源：http://dali.fengsongda.top/Article/details/gt2kmwhtkdt.html

JS:   class User {}
来源：http://dali.daxiang520.top/Article/details/gt2iksnknii.html

TS:   class User { name: string = ""; }
来源：http://dali.jianghu66.top/Article/details/gt2jxlyzttl.html

Java: class User {}
来源：http://dali.fzhhl.top/Article/details/gt2mgnixpdj.html

Go:   type User struct { Name string }
来源：http://dali.andypj.xyz/Article/details/gt2ktvnrkpi.html

Ruby: class User; end
来源：http://dali.yvedp.cn/Article/details/gt2bmgnmakx.html

C#:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gt2bdjaliqx.html

[G02] 构造函数
来源：http://dali.zdqjudy.top/Article/details/gt2gyrpahqd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dashuyun.cn/Article/details/gt2jpmaiaiq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sweek.top/Article/details/gt2qzjoflvv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gt2ipljwyad.html

TS:   constructor(public name: string) {}
来源：http://dali.yangfankeji.com/Article/details/gt2etzcyalf.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gt2hzdmwsbp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj20258.top/Article/details/gt2zqnlbycr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhengqikj.top/Article/details/gt2abfgdzte.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yueranfly.top/Article/details/gt2spjcyqmf.html

[G03] 实例属性
来源：http://dali.sufxvd.cn/Article/details/gt2xdevxaak.html

Py:   self.name = "x"
来源：http://dali.ybcxt.top/Article/details/gt2escjkuug.html

PHP:  public string $name = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gt2joqqqnyz.html

JS:   this.name = "x";
来源：http://dali.smart0.xyz/Article/details/gt2yvhqcaec.html

TS:   name: string = "x";
来源：http://dali.yonumen.top/Article/details/gt2akziumfq.html

Java: private String name;
来源：http://dali.yongpay.top/Article/details/gt2ovsotyqp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.redwolf501.top/Article/details/gt2gmnwsgiy.html

Ruby: @name = "x"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eatzveym.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2ualzmwsb.html

[G04] 定义方法
来源：http://dali.hongshengwenyu.top/Article/details/gt2qihuddft.html

Py:   def greet(self): return self.name
来源：http://dali.chenlongwang.top/Article/details/gt2ddldndyk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gt2tvakbrwy.html

JS:   greet() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2uqvlfxwt.html

TS:   greet(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gt2tvktvdgw.html

Java: String greet() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2iyjgnfml.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gt2nejezcsw.html

Ruby: def greet; @name; end
来源：http://dali.cashguo.top/Article/details/gt2bocljfao.html

C#:   public string Greet() => Name;
来源：http://dali.jyoumei.cn/Article/details/gt2cojqoicr.html

[G05] 继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ejmbnlsy.html

Py:   class Admin(User): pass
来源：http://dali.zycfv.cn/Article/details/gt2tjpfjugd.html

PHP:  class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gt2ifcvrnjq.html

JS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ulybfzki.html

TS:   class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gt2nnwnpsqi.html

Java: class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2prmzsfji.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhixingplan.top/Article/details/gt2rwdgnbdx.html

Ruby: class Admin < User; end
来源：http://dali.zhongyouzk.top/Article/details/gt2syrkmgxw.html

C#:   class Admin : User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2xzqryask.html

[G06] 重写方法
来源：http://dali.shuidangran.top/Article/details/gt2ggluvcqn.html

Py:   def greet(self): return "admin"
来源：http://dali.bjfxy.top/Article/details/gt2oawxcser.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gt2akvmkdal.html

JS:   greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gt2nxseqgun.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gt2fcmpkein.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gt2ucwtqane.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yongpay.top/Article/details/gt2maxfphtp.html

Ruby: def greet; "admin"; end
来源：http://dali.smart0.xyz/Article/details/gt2ieydezfe.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj20258.top/Article/details/gt2olhefccq.html

[G07] 调用父类方法
来源：http://dali.yongpay.top/Article/details/gt2sirsjldy.html

Py:   super().greet()
来源：http://dali.smart0.xyz/Article/details/gt2grhaemxj.html

PHP:  parent::greet();
来源：http://dali.snrcjt.cn/Article/details/gt2gefmfapg.html

JS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gt2bvmfhbow.html

TS:   super.greet();
来源：http://dali.xziqi.cn/Article/details/gt2kmxkmlag.html

Java: super.greet();
来源：http://dali.yongpay.top/Article/details/gt2judisxku.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.svipenyu.cn/Article/details/gt2hgaiyqfx.html

Ruby: super
来源：http://dali.shuidangran.top/Article/details/gt2cvkivgrt.html

C#:   base.Greet();
来源：http://dali.jyoumei.cn/Article/details/gt2nssdpklq.html

[G08] 静态方法与属性
来源：http://dali.iojbl.cn/Article/details/gt2nlkjpjxd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj202588.top/Article/details/gt2tvcxyckp.html

PHP:  public static function f() {}
来源：http://dali.xylfe.cn/Article/details/gt2ikcfimoo.html

JS:   static f() {}
来源：http://dali.cqqwz.cn/Article/details/gt2szqflahg.html

TS:   static f(): void {}
来源：http://dali.yonumen.top/Article/details/gt2bqejebbo.html

Java: static void f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2npxjqusb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj202588.top/Article/details/gt2xvevgkhz.html

Ruby: def self.f; end
来源：http://dali.dashuyun.cn/Article/details/gt2tmytlwsn.html

C#:   public static void F() {}
来源：http://dali.guannengcc.top/Article/details/gt2gqobizce.html

[G09] 接口 / 抽象类
来源：http://dali.dashuyun.cn/Article/details/gt2lnqnoere.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.snrcjt.cn/Article/details/gt2nxtujmam.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2uwhguazc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxinkj.top/Article/details/gt2qlnlxfos.html

TS:   interface Shape { area(): number; }
来源：http://dali.daria6918.cn/Article/details/gt2tayjxngy.html

Java: interface Shape { double area(); }
来源：http://dali.ivvv.top/Article/details/gt2fdymytvp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sysykeji.top/Article/details/gt2qlgajyvg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gaohongyu789.top/Article/details/gt2jebcaqfn.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangdashe.top/Article/details/gt2dotmwmcc.html

[G10] 访问控制
来源：http://dali.fzhhl.top/Article/details/gt2xcyhjekv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ehwqpu.com/Article/details/gt2oiopmizc.html

PHP:  public / protected / private
来源：http://dali.mhx1999.top/Article/details/gt2fyscdsin.html

JS:   #private 字段；其余公开
来源：http://dali.jqgufenzy.top/Article/details/gt2rbnfogur.html

TS:   public / protected / private
来源：http://dali.yj20258888.top/Article/details/gt2wgaaqsri.html

Java: public / protected / private / 默认包级
来源：http://dali.sweek.top/Article/details/gt2qxujcudl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258.top/Article/details/gt2gahjoakw.html

Ruby: public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kjkxhczp.html

C#:   public / protected / private / internal
来源：http://dali.hammf.cn/Article/details/gt2jmkpspbo.html

[G11] getter / setter
来源：http://dali.haohaochexian.top/Article/details/gt2hftijvdr.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258888.top/Article/details/gt2lbwyuhdn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ajhucxnn.html

JS:   get name() { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gt2cqiipphz.html

TS:   get name(): string { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gt2bgwktnpk.html

Java: public String getName() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2obpnmjyf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gt2aqzcsazz.html

Ruby: attr_accessor :name
来源：http://dali.cucudq.cn/Article/details/gt2yypjryem.html

C#:   public string Name { get; set; }
来源：http://dali.birdmap.top/Article/details/gt2izwdpuua.html

[G12] 对象转字符串
来源：http://dali.316326.xyz/Article/details/gt2zyncbgeg.html

Py:   def __str__(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gt2prwrphea.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gt2onwssfmf.html

JS:   toString() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gt2vajsjmxo.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gt2xlyzybrr.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjatwhoo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gt2yfmgfzyn.html

Ruby: def to_s; @name; end
来源：http://dali.redwolf501.top/Article/details/gt2plcxpuvm.html

C#:   public override string ToString() => Name;
来源：http://dali.ivvv.top/Article/details/gt2cjhwrkoq.html

[G13] 判断对象类型
来源：http://dali.nwbrower.top/Article/details/gt2lvkgslpk.html

Py:   isinstance(u, User)
来源：http://dali.fzhhl.top/Article/details/gt2unqlalpe.html

PHP:  $u instanceof User
来源：http://dali.cheryme.top/Article/details/gt2ggdxchxd.html

JS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gt2fhkuoilm.html

TS:   u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gt2mjwrntmo.html

Java: u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gt2glrnhaiv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.fzhhl.top/Article/details/gt2abcyzigp.html

Ruby: u.is_a?(User)
来源：http://dali.zhixingplan.top/Article/details/gt2ovekxvtc.html

C#:   u is User
来源：http://dali.jyoumei.cn/Article/details/gt2vdurdxsk.html

[G14] 数据类 / record
来源：http://dali.wangdashe.top/Article/details/gt2jfkzvkrw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.svipenyu.cn/Article/details/gt2rklsjvwq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenlongwang.top/Article/details/gt2ahfkdahm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hammf.cn/Article/details/gt2ycbhtzkc.html

TS:   type User = { name: string; age: number };
来源：http://dali.pengpengdd.cyou/Article/details/gt2xdjomnwi.html

Java: record User(String name, int age) {}
来源：http://dali.birdmap.top/Article/details/gt2kduprnau.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sysykeji.top/Article/details/gt2jojkefne.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jianghu66.top/Article/details/gt2xssnyzba.html

C#:   record User(string Name, int Age);
来源：http://dali.yvedp.cn/Article/details/gt2yhocjofa.html

[G15] 枚举
来源：http://dali.yonumen.top/Article/details/gt2vwlwqmwq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cashguo.top/Article/details/gt2rmammnfx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sufxvd.cn/Article/details/gt2knhrgzaw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gaohongyu789.top/Article/details/gt2otgxacpg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.mhx1999.top/Article/details/gt2eizfaojh.html

Java: enum Color { RED, GREEN }
来源：http://dali.9152youxi.cn/Article/details/gt2woihphxc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj202588.top/Article/details/gt2ozriismd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.feifeiyinyue.top/Article/details/gt2hhkzmrwj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2ynyvbofg.html

[G16] 对象转数组 / 字典
来源：http://dali.hysaishi.cn/Article/details/gt2jqzyloyf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shangyingyoupin.top/Article/details/gt2euopbqqc.html

PHP:  get_object_vars($obj);
来源：http://dali.chenlongwang.top/Article/details/gt2baraokcm.html

JS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gt2isazccmb.html

TS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2advnxfby.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nanxinkj.top/Article/details/gt2pqlxjsvr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yongpay.top/Article/details/gt2mqiaqzsq.html

Ruby: obj.instance_variables
来源：http://dali.ppjwa.cn/Article/details/gt2rdheijal.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tianlin.xyz/Article/details/gt2gbqetemx.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lnnykzdn.html

H. 异常与错误处理
来源：http://dali.tianlin.xyz/Article/details/gt2kawfqzdj.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2vfyxctbe.html

[H01] try / catch 基础
来源：http://dali.hongshengwenyu.top/Article/details/gt2oclkordj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.daxiang520.top/Article/details/gt2vpxccjnq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenzaomai.com/Article/details/gt2dqfluvhh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xqjayldm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gt2omkapbrb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sweek.top/Article/details/gt2mfsbsewk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lfgrxoyr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gaohongyu789.top/Article/details/gt2abqoojwv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigfzy.top/Article/details/gt2vvykuxha.html

[H02] finally / ensure 收尾
来源：http://dali.sweek.top/Article/details/gt2yoiwntic.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jyoumei.cn/Article/details/gt2ueqzrxhz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2zmbowhlt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gt2vqackzfh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2nbeiblaq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gt2gtnkjwia.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnxiangtu.top/Article/details/gt2wloxnnvc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daria6918.cn/Article/details/gt2mzwcxvrd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2tjfkzykc.html


<!-- 参考信息 -->