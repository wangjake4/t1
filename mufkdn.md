代发 wailian999

Go:   if s == "" {}
来源：http://dali.shzxlz.cn/Article/details/gtbqwqlioi.html

Ruby: if s.empty?
来源：http://dali.pycfn.com/Article/details/gtscbiyqrp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.daxiang520.top/Article/details/gtfnrrrpch.html

[E21] 超长截断加省略号
来源：http://dali.jinqigufen.top/Article/details/gteqnbapdy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tian-w.cn/Article/details/gtpwazdzkk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gtfiblbsfb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtchaykump.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtnrcsfhnc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gtejgpwppd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yangfankeji.com/Article/details/gthlcfxarx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtwbwyunnf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtwevyhryl.html

[E22] 字节长度与字符长度
来源：http://dali.jlsjyb.cn/Article/details/gtjidxkvmp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daxiang520.top/Article/details/gtmpgiwzyg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gtxbnayldg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gtdfrommdb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cashguo.top/Article/details/gtoiojwtsz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jlsjyb.cn/Article/details/gtoqbsvtom.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yangfankeji.com/Article/details/gttiouwhko.html

Ruby: s.bytesize;  s.length
来源：http://dali.smart0.xyz/Article/details/gtfhkxnlad.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cheryme.top/Article/details/gtnidmarft.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtzinvojyd.html

F. 文件与目录
来源：http://dali.zdqjudy.top/Article/details/gtriurxwzg.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtmaleszpd.html

[F01] 读取整个文件
来源：http://dali.zhongyouzk.top/Article/details/gtkguxledg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fengsongda.top/Article/details/gtzifxvklq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.pycfn.com/Article/details/gtpnnefgpk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hammf.cn/Article/details/gtmyajdhvr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gtugvuuayd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtnyavoyxr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.kuanghao11.cn/Article/details/gtcvztmxco.html

Ruby: File.read("a.txt")
来源：http://dali.birdmap.top/Article/details/gtagazqhua.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtbbxlcwwz.html

[F02] 逐行读取文件
来源：http://dali.yuxming.cn/Article/details/gtuntjdtur.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ivvv.top/Article/details/gtirwdasal.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhengqikj.top/Article/details/gtpgurfrdn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gtsrziulxp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gteqyesmdp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xuanzx.com/Article/details/gtccudwraj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhixingplan.top/Article/details/gtuutiszuv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxajjlsst.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guannengcc.top/Article/details/gtpsgagdzx.html

[F03] 写入文件（覆盖）
来源：http://dali.chenzaomai.com/Article/details/gtmqtxqrql.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hfpthk.cn/Article/details/gtbrjgcvmd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gtsbthnqkd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yueranfly.top/Article/details/gtbqvinngw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtlenixbwg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jqgfzy.top/Article/details/gtvdpjuoyz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ivvv.top/Article/details/gthwatqryd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.dianchejie.cn/Article/details/gtovqryzgj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.mhx1999.top/Article/details/gtztflvhqb.html

[F04] 追加写入文件
来源：http://dali.jqgfzy.top/Article/details/gtlzyumnai.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.9152youxi.cn/Article/details/gtzbgjgako.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuetiantiany.cn/Article/details/gtkvwfcieo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cdnleiting.top/Article/details/gtvufagrpq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gtszgpbqmj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gtwzomqevw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigufen.top/Article/details/gtgrlblgeu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258.top/Article/details/gtqqvdeasb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yanxiufei.cn/Article/details/gtvjixllum.html

[F05] 判断文件或目录是否存在
来源：http://dali.gogol.net.cn/Article/details/gtibigvnat.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fzhhl.top/Article/details/gtfarrabym.html

PHP:  file_exists("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtncwiureu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtjxddphmn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtmqvfkypa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtwlkypnvj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hywenlv.cn/Article/details/gtoflzzcld.html

Ruby: File.exist?("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtmerasfon.html

C#:   File.Exists("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtxppytvaw.html

[F06] 删除文件
来源：http://dali.zycfv.cn/Article/details/gtpembyims.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtcsajhxiy.html

PHP:  unlink("a.txt");
来源：http://dali.316326.xyz/Article/details/gttauutioc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtxgknzadd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtaaudhyuw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gttnxaqiql.html

Go:   os.Remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtuvhtulfz.html

Ruby: File.delete("a.txt")
来源：http://dali.gzhubu.top/Article/details/gthnudvmoy.html

C#:   File.Delete("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtzvjpsyxf.html

[F07] 创建目录（含多级）
来源：http://dali.daria6918.cn/Article/details/gtbxdixacu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.iojbl.cn/Article/details/gttqwzwwyu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfupbrcxx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.haohaochexian.top/Article/details/gtjixwyupn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gtfxpzrpia.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj202588.top/Article/details/gtptqsteat.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.c1oappe.top/Article/details/gtavlnhsvt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yuxming.cn/Article/details/gtnnjusmml.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nanxinkj.top/Article/details/gthtimmbbx.html

[F08] 遍历目录
来源：http://dali.guowangkeji.top/Article/details/gtyprjklkb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xziqi.cn/Article/details/gtoqdgtdwd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sufxvd.cn/Article/details/gtwdoigwiv.html

JS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gtugbmdrdt.html

TS:   fs.readdirSync("dir")
来源：http://dali.aizwys.cn/Article/details/gtngvjhbof.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gtmbwmtpyz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yueranfly.top/Article/details/gttvixfcwa.html

Ruby: Dir.children("dir")
来源：http://dali.guowangkeji.top/Article/details/gtheqxkwla.html

C#:   Directory.GetFiles("dir")
来源：http://dali.316326.xyz/Article/details/gttivlhuae.html

[F09] 获取文件大小
来源：http://dali.jinqigufen.top/Article/details/gtrrpwnskz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtelttlwfw.html

PHP:  filesize("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtgbzjixql.html

JS:   fs.statSync("a.txt").size
来源：http://dali.redwolf501.top/Article/details/gtsutamksa.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gtfzclzcei.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtexjusbuc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgufenzy.top/Article/details/gtkqldjfyh.html

Ruby: File.size("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gttvlwumay.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tian-w.cn/Article/details/gtndtwdsnc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.quarkkingdee.top/Article/details/gtrbclbhud.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtuirvlzhd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtvybmqfui.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtbayuvifh.html

TS:   path.extname("a.txt")
来源：http://dali.yonumen.top/Article/details/gtbirxqjms.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hammf.cn/Article/details/gtmhbmlyoa.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtbqgzmfuc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtxcycysgy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtqijarbfg.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcbmmiojd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gtfxwhyaev.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtzlhawioe.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtnccxelke.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtrvnbrefd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cashguo.top/Article/details/gtwfqtvxvl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqasuczaq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtxfbxhzve.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.dianchejie.cn/Article/details/gtefkulxnv.html

[F12] CSV 读写
来源：http://dali.xuetiantiany.cn/Article/details/gtomfjkljc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxuanxn.top/Article/details/gtlmzuruhe.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtckkphyof.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxinkj.top/Article/details/gtdgovqutv.html

TS:   // 同上
来源：http://dali.hnxiangtu.top/Article/details/gtqycxpitm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.quarkkingdee.top/Article/details/gtfzwfcvgx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhixingplan.top/Article/details/gtplagfiig.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.daxiang520.top/Article/details/gtfjbiekmd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.quarkkingdee.top/Article/details/gtfthnckxc.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gthzfqqske.html

G. 面向对象
来源：http://dali.guowangkeji.top/Article/details/gtbybbnsae.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtqbgmgnzn.html

[G01] 定义类
来源：http://dali.jyoumei.cn/Article/details/gtcbulxwmn.html

Py:   class User: pass
来源：http://dali.shangyingyoupin.top/Article/details/gtrsihuzch.html

PHP:  class User {}
来源：http://dali.snrcjt.cn/Article/details/gtimmfnckk.html

JS:   class User {}
来源：http://dali.pycfn.com/Article/details/gtpewcajec.html

TS:   class User { name: string = ""; }
来源：http://dali.yanxiufei.cn/Article/details/gtesgjqlav.html

Java: class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtpwgejkfm.html

Go:   type User struct { Name string }
来源：http://dali.cashguo.top/Article/details/gtgdalpull.html

Ruby: class User; end
来源：http://dali.ehwqpu.com/Article/details/gttfhyfvzz.html

C#:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gtpbczwiqy.html

[G02] 构造函数
来源：http://dali.mhx1999.top/Article/details/gtxhwqzxil.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nanxinkj.top/Article/details/gtsrugqhmu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.mhx1999.top/Article/details/gtqyuutwjz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtqayfohgr.html

TS:   constructor(public name: string) {}
来源：http://dali.yvedp.cn/Article/details/gtgwolmrvh.html

Java: User(String name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gtolnifmhy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.smart0.xyz/Article/details/gthjpxuqha.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtluzparoe.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtfetjbewi.html

[G03] 实例属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwvltoci.html

Py:   self.name = "x"
来源：http://dali.ppjwa.cn/Article/details/gtmchxagsi.html

PHP:  public string $name = "x";
来源：http://dali.fzhhl.top/Article/details/gtfppdimhz.html

JS:   this.name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtwnzgyzao.html

TS:   name: string = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtwxnlrqcv.html

Java: private String name;
来源：http://dali.nanxinkj.top/Article/details/gtmmuqdqju.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pengpengdd.cyou/Article/details/gtgiawjstf.html

Ruby: @name = "x"
来源：http://dali.aibaodan.cn/Article/details/gtgonpssfp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtbiqpxbda.html

[G04] 定义方法
来源：http://dali.nwbrower.top/Article/details/gtlzmvqblh.html

Py:   def greet(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gtzggfpeky.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gtllypmdrq.html

JS:   greet() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtmmssyycb.html

TS:   greet(): string { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtdqmoydes.html

Java: String greet() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtvfyaieln.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gthewabcig.html

Ruby: def greet; @name; end
来源：http://dali.ppjwa.cn/Article/details/gttdygdoif.html

C#:   public string Greet() => Name;
来源：http://dali.c1oappe.top/Article/details/gtfcpsytkn.html

[G05] 继承
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqyeqobp.html

Py:   class Admin(User): pass
来源：http://dali.hysaishi.cn/Article/details/gtrurreesa.html

PHP:  class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtxwtymfbu.html

JS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtspqqkuxk.html

TS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtjovenpqu.html

Java: class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtxmpjjkop.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xylfe.cn/Article/details/gtmhhsryho.html

Ruby: class Admin < User; end
来源：http://dali.yangfankeji.com/Article/details/gtagweuwic.html

C#:   class Admin : User {}
来源：http://dali.havefunace.top/Article/details/gtwmniyhip.html

[G06] 重写方法
来源：http://dali.yueranfly.top/Article/details/gtfutilmdn.html

Py:   def greet(self): return "admin"
来源：http://dali.xinyue.icu/Article/details/gtltwnvzob.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtgabmckts.html

JS:   greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtysquezkp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtcrcifabf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtmestsiwa.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhixingplan.top/Article/details/gtqipmsryw.html

Ruby: def greet; "admin"; end
来源：http://dali.tian-w.cn/Article/details/gtqgjhxyqr.html

C#:   public override string Greet() => "admin";
来源：http://dali.wangshuangyany.cn/Article/details/gtlbpqduio.html

[G07] 调用父类方法
来源：http://dali.ivvv.top/Article/details/gtvhqdcyzt.html

Py:   super().greet()
来源：http://dali.cqqwz.cn/Article/details/gtplxnyoim.html

PHP:  parent::greet();
来源：http://dali.cheryme.top/Article/details/gtvynyahcc.html

JS:   super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtiucksyjj.html

TS:   super.greet();
来源：http://dali.xziqi.cn/Article/details/gtxusmnkma.html

Java: super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gtybmkxeyr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cdnleiting.top/Article/details/gtzxvaoarh.html

Ruby: super
来源：http://dali.chenjidiqi.icu/Article/details/gthfxmfdhs.html

C#:   base.Greet();
来源：http://dali.hammf.cn/Article/details/gtkucltbhd.html

[G08] 静态方法与属性
来源：http://dali.cashguo.top/Article/details/gtgfuemzaa.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.mhx1999.top/Article/details/gtypjwnigl.html

PHP:  public static function f() {}
来源：http://dali.jinqigfzy.top/Article/details/gtmdvmxhpg.html

JS:   static f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtjrtjanzr.html

TS:   static f(): void {}
来源：http://dali.ydzc1.top/Article/details/gtzqzqyuvk.html

Java: static void f() {}
来源：http://dali.xziqi.cn/Article/details/gtomzbqiac.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fengsongda.top/Article/details/gtfgjbekcr.html

Ruby: def self.f; end
来源：http://dali.gogol.net.cn/Article/details/gtiugicene.html

C#:   public static void F() {}
来源：http://dali.guannengcc.top/Article/details/gtulqehsoc.html

[G09] 接口 / 抽象类
来源：http://dali.fzhhl.top/Article/details/gtzkqlczbn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hywenlv.cn/Article/details/gtbxydfhcb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sufxvd.cn/Article/details/gtprrywdfx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.meibo888.top/Article/details/gtaljfdrwp.html

TS:   interface Shape { area(): number; }
来源：http://dali.shuidangran.top/Article/details/gtliarnsqv.html

Java: interface Shape { double area(); }
来源：http://dali.svipenyu.cn/Article/details/gtonijhrvj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sxryk.cn/Article/details/gtgvukkmgn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jiagoushi.top/Article/details/gtnmzxewjh.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhoulong.xyz/Article/details/gtfmkwesos.html

[G10] 访问控制
来源：http://dali.cdnleiting.top/Article/details/gtylafqjne.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxstphsyl.html

PHP:  public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gtbltkmqmf.html

JS:   #private 字段；其余公开
来源：http://dali.gaohongyu789.top/Article/details/gtwzpknytg.html

TS:   public / protected / private
来源：http://dali.ivvv.top/Article/details/gttuuztfhc.html

Java: public / protected / private / 默认包级
来源：http://dali.ppjwa.cn/Article/details/gtfqeuybdd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cucudq.cn/Article/details/gtcvudxhae.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtqqybvbaj.html

C#:   public / protected / private / internal
来源：http://dali.gogol.net.cn/Article/details/gtnckzcvuh.html

[G11] getter / setter
来源：http://dali.ydzc1.top/Article/details/gtponiscyn.html

Py:   @property 与 @x.setter
来源：http://dali.9152youxi.cn/Article/details/gtsqgmyisd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gtjfpnmbwc.html

JS:   get name() { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqhumfgf.html

TS:   get name(): string { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gtgicsrhiy.html

Java: public String getName() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtdrbongxk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtptgzowpb.html

Ruby: attr_accessor :name
来源：http://dali.nwbrower.top/Article/details/gtookviwbg.html

C#:   public string Name { get; set; }
来源：http://dali.nanxuanxn.top/Article/details/gtpxndyztx.html

[G12] 对象转字符串
来源：http://dali.mhx1999.top/Article/details/gtllmtbcha.html

Py:   def __str__(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gtafdqodvo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtlcwfgyns.html

JS:   toString() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtwwjwatuw.html

TS:   toString(): string { return this.name; }
来源：http://dali.316326.xyz/Article/details/gtlrlnlzbq.html

Java: @Override public String toString() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtpqkfjlsz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtliudrquv.html

Ruby: def to_s; @name; end
来源：http://dali.ydzc1.top/Article/details/gtsorxdcmq.html

C#:   public override string ToString() => Name;
来源：http://dali.gaohongyu789.top/Article/details/gtmtreyirg.html

[G13] 判断对象类型
来源：http://dali.ppjwa.cn/Article/details/gtooijkyuz.html

Py:   isinstance(u, User)
来源：http://dali.redwolf501.top/Article/details/gthvgabzry.html

PHP:  $u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtqhlmeugv.html

JS:   u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtrzqzljjb.html

TS:   u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtijxduglr.html

Java: u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtclxnnwde.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.smart0.xyz/Article/details/gthpqiubgs.html

Ruby: u.is_a?(User)
来源：http://dali.wangshuangyany.cn/Article/details/gtkbiuwvsl.html

C#:   u is User
来源：http://dali.nanxinkj.top/Article/details/gtmhzmwdkq.html

[G14] 数据类 / record
来源：http://dali.jiagoushi.top/Article/details/gthseddyin.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gtgikamqoi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigfzy.top/Article/details/gtaivihxxe.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gtbsikjfma.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnukdzet.html

Java: record User(String name, int age) {}
来源：http://dali.redwolf501.top/Article/details/gtgxbhfjeg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdybsbcf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zycfv.cn/Article/details/gtceyyqeij.html

C#:   record User(string Name, int Age);
来源：http://dali.yuanzhike.top/Article/details/gtfvhpkldf.html

[G15] 枚举
来源：http://dali.bjfxy.top/Article/details/gtsyqpknvt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jlsjyb.cn/Article/details/gtdtealwyw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zdqjudy.top/Article/details/gtljfmafml.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxinkj.top/Article/details/gtnwauydws.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmwmpxitn.html

Java: enum Color { RED, GREEN }
来源：http://dali.kuanghao11.cn/Article/details/gtjpretsvq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gtyecasttn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.meibo888.top/Article/details/gtcsvfiwwj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cdnleiting.top/Article/details/gtvpxwtwti.html

[G16] 对象转数组 / 字典
来源：http://dali.yvedp.cn/Article/details/gtarndjntk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daxiang520.top/Article/details/gttnegcfnz.html

PHP:  get_object_vars($obj);
来源：http://dali.fengsongda.top/Article/details/gtspffwvqy.html

JS:   Object.entries(obj)
来源：http://dali.jiagoushi.top/Article/details/gtvvucgxik.html

TS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gtvyfebuvx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hywenlv.cn/Article/details/gtoiowmngu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sxryk.cn/Article/details/gtgtoozuua.html

Ruby: obj.instance_variables
来源：http://dali.cheryme.top/Article/details/gtqcbvjmqd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.birdmap.top/Article/details/gtwelevnyk.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtkltgxxqm.html

H. 异常与错误处理
来源：http://dali.cqqwz.cn/Article/details/gtiydbapqm.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtbpulqsjl.html

[H01] try / catch 基础
来源：http://dali.cheryme.top/Article/details/gtymyyxvxe.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigfzy.top/Article/details/gtlswtpzii.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sufxvd.cn/Article/details/gtckluremg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gtzptpyqzp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gtdamgqcnu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuetiantiany.cn/Article/details/gtcspnzuea.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhengqikj.top/Article/details/gtuserdcbx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangdashe.top/Article/details/gthzevuigt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.fengsongda.top/Article/details/gtoboadrtn.html

[H02] finally / ensure 收尾
来源：http://dali.snrcjt.cn/Article/details/gtkotanykw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxepysilc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtfvwvhljj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtruioowej.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzfrhcgy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtbjcrhjbv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shuidangran.top/Article/details/gtdrjjdgvb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cucudq.cn/Article/details/gtgmrqital.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtsrypdcwj.html


<!-- 参考信息 -->