代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.0kj1m.cn/Article/details/gtfcpzzanw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ppjwa.cn/Article/details/gtzrnjcvvc.html

TS:   if (s === "") {}
来源：http://dali.nwbrower.top/Article/details/gtvwwpmkjn.html

Java: if (s.isEmpty()) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtnudvazvp.html

Go:   if s == "" {}
来源：http://dali.jinqigufen.top/Article/details/gternwwqxn.html

Ruby: if s.empty?
来源：http://dali.haohaochexian.top/Article/details/gtmdpibnsa.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.havefunace.top/Article/details/gtckclxker.html

[E21] 超长截断加省略号
来源：http://dali.aibaodan.cn/Article/details/gthzqkdqex.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sysykeji.top/Article/details/gtsurthkox.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gtxyauewui.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtoatymrlt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtobtpllgy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvyegyiw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jqgfzy.top/Article/details/gtvmocmtoz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gteakghehr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtrzceqdyc.html

[E22] 字节长度与字符长度
来源：http://dali.aibaodan.cn/Article/details/gtukxvldup.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjktsygrn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gtkgqaspow.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtxpxwnmaa.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yueranfly.top/Article/details/gtyhkcsfon.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinqigfzy.top/Article/details/gttyrhxqym.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.kuanghao11.cn/Article/details/gtrqubxoot.html

Ruby: s.bytesize;  s.length
来源：http://dali.jianghu66.top/Article/details/gtfwxmtxmw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hywenlv.cn/Article/details/gtxydwhabu.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gterdijoyb.html

F. 文件与目录
来源：http://dali.xinyue.icu/Article/details/gtqltjqaju.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtgfsmlmjf.html

[F01] 读取整个文件
来源：http://dali.316326.xyz/Article/details/gthtygnkgs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sweek.top/Article/details/gtwjjipgmx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtqiiegcwc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenjidiqi.icu/Article/details/gtujivpxbk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxreqpkc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtziittmvd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zycfv.cn/Article/details/gtbwfilgqw.html

Ruby: File.read("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtbutrxwgo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtudvfowvz.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gtdkrttzaz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxinkj.top/Article/details/gthyuwethq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj20258888.top/Article/details/gtmupgbbhs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jiagoushi.top/Article/details/gtatxephdr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aizwys.cn/Article/details/gtqkjgjtta.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xinyue.icu/Article/details/gtgxlhxoqy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sufxvd.cn/Article/details/gtzhlnvafr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gtqtiidwji.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.quarkkingdee.top/Article/details/gtoorhqqjo.html

[F03] 写入文件（覆盖）
来源：http://dali.pycfn.com/Article/details/gtuypzikqg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sxryk.cn/Article/details/gtaywzpecc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.guannengcc.top/Article/details/gtvwtpdxuk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jianghu66.top/Article/details/gtfygzjndn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gtjxdxsbqi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.dianchejie.cn/Article/details/gtztxoplsj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuanzhike.top/Article/details/gtuthadidv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sxryk.cn/Article/details/gtpjbgobsq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tianlin.xyz/Article/details/gtphambatu.html

[F04] 追加写入文件
来源：http://dali.yuanzhike.top/Article/details/gtiflzqrni.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.c1oappe.top/Article/details/gtuuoscbqu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nwbrower.top/Article/details/gtheqeaupw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hywenlv.cn/Article/details/gtrgtbblgi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pycfn.com/Article/details/gtksdapkti.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hysaishi.cn/Article/details/gtlyhumxzh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigufen.top/Article/details/gtgjwytrcp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sxryk.cn/Article/details/gtfzzyhlsp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sweek.top/Article/details/gtjgrqypux.html

[F05] 判断文件或目录是否存在
来源：http://dali.pycfn.com/Article/details/gtuhtjynkh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.316326.xyz/Article/details/gtyaipdskv.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtxicywvlk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtcqitbviz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtniyllnsa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtaorksfsa.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.smart0.xyz/Article/details/gteyoccfzm.html

Ruby: File.exist?("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gthovrrmbs.html

C#:   File.Exists("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtkhzvwbre.html

[F06] 删除文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvbbikqld.html

Py:   os.remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtftqftonj.html

PHP:  unlink("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtmrpfxuez.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtopbrcjax.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvfvbwruf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtjswwzxxs.html

Go:   os.Remove("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtpjlaeqdv.html

Ruby: File.delete("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtgfobdxgq.html

C#:   File.Delete("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtucvuimqd.html

[F07] 创建目录（含多级）
来源：http://dali.yueranfly.top/Article/details/gtqcvvfyji.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gtglmtmrky.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuanzx.com/Article/details/gtrkbrqknc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgufenzy.top/Article/details/gtzjtnfwtf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.quarkkingdee.top/Article/details/gtnblrzfcs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xinyue.icu/Article/details/gtgocramax.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xziqi.cn/Article/details/gtvbwjasgc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxuanxn.top/Article/details/gtbzymipzp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhiwuduotai.top/Article/details/gtooomkzzd.html

[F08] 遍历目录
来源：http://dali.shuidangran.top/Article/details/gtvzolbyhp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yonumen.top/Article/details/gtkttewbxw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yongpay.top/Article/details/gtktjtczad.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtbnmrnuoj.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gttqojxfjx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gtdjqshjxd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.iojbl.cn/Article/details/gtlodmqyey.html

Ruby: Dir.children("dir")
来源：http://dali.havefunace.top/Article/details/gttdfccudu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yvedp.cn/Article/details/gtlzcbdage.html

[F09] 获取文件大小
来源：http://dali.ywan-chungtsiang.top/Article/details/gteunlyjpc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtjmzfemhl.html

PHP:  filesize("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtujgxtxar.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gtlcadfnkx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gtpjocoybo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gtexiddikd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.kuanghao11.cn/Article/details/gtlckpoifm.html

Ruby: File.size("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtjnjocpbi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nanxuanxn.top/Article/details/gtzuryzdrn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhiwuduotai.top/Article/details/gtasosdkex.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtsfgjhbmb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cashguo.top/Article/details/gtricjrcnd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtpvvosaud.html

TS:   path.extname("a.txt")
来源：http://dali.sweek.top/Article/details/gtbrarlgix.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ehwqpu.com/Article/details/gtfdzkqmdm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrcixjwu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtixpmnqsv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtkipjdvnd.html

[F11] 复制与移动文件
来源：http://dali.fengsongda.top/Article/details/gteeapjvbg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtqtuqsmhb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.316326.xyz/Article/details/gtrhrhmwke.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtkjedjcgw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtgazpjuww.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tian-w.cn/Article/details/gtiwyawmcf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.aibaodan.cn/Article/details/gtgucytoot.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtallnktdi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.mhx1999.top/Article/details/gtrbdzcjfe.html

[F12] CSV 读写
来源：http://dali.zhongyouzk.top/Article/details/gttlibnmlq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yuxming.cn/Article/details/gtibbwodnm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yonumen.top/Article/details/gtakoojdva.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hywenlv.cn/Article/details/gtqmmlrzez.html

TS:   // 同上
来源：http://dali.zhengqikj.top/Article/details/gtlreidatc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuxming.cn/Article/details/gtpcwiwydc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.wangshuangyany.cn/Article/details/gtkpeiwehb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yangfankeji.com/Article/details/gtntvqwmhf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jqgfzy.top/Article/details/gtpnfkcwtb.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtxsdmqeie.html

G. 面向对象
来源：http://dali.ydzc1.top/Article/details/gtdmsgzhpn.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtdpefzneu.html

[G01] 定义类
来源：http://dali.birdmap.top/Article/details/gtsfiimhkl.html

Py:   class User: pass
来源：http://dali.nanxinkj.top/Article/details/gtwyyotrzy.html

PHP:  class User {}
来源：http://dali.cucudq.cn/Article/details/gtyerpxhut.html

JS:   class User {}
来源：http://dali.redwolf501.top/Article/details/gtmbixgiul.html

TS:   class User { name: string = ""; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqteyqwja.html

Java: class User {}
来源：http://dali.yueranfly.top/Article/details/gtcbokoegx.html

Go:   type User struct { Name string }
来源：http://dali.vqdsnc.cn/Article/details/gticzcqthb.html

Ruby: class User; end
来源：http://dali.zycfv.cn/Article/details/gtosnxkcqo.html

C#:   class User {}
来源：http://dali.snrcjt.cn/Article/details/gttnyjgsbw.html

[G02] 构造函数
来源：http://dali.zhengqikj.top/Article/details/gtxxxxpdss.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cqqwz.cn/Article/details/gtlvjyywcg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtqrjqspel.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gtkbsxvnkg.html

TS:   constructor(public name: string) {}
来源：http://dali.birdmap.top/Article/details/gtfetiqthd.html

Java: User(String name) { this.name = name; }
来源：http://dali.fzhhl.top/Article/details/gtwmdiqwko.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daxiang520.top/Article/details/gtlmqxsmxm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xuanzx.com/Article/details/gtmnavxicv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.daxiang520.top/Article/details/gttqnypfgh.html

[G03] 实例属性
来源：http://dali.haohaochexian.top/Article/details/gtlhpcjcds.html

Py:   self.name = "x"
来源：http://dali.yvedp.cn/Article/details/gtmfhxcwyj.html

PHP:  public string $name = "x";
来源：http://dali.tanke756.top/Article/details/gtlviyndoc.html

JS:   this.name = "x";
来源：http://dali.redwolf501.top/Article/details/gtoqgpbujk.html

TS:   name: string = "x";
来源：http://dali.havefunace.top/Article/details/gtjgixrtun.html

Java: private String name;
来源：http://dali.aizwys.cn/Article/details/gtwuruezux.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgfzy.top/Article/details/gtelidfhsw.html

Ruby: @name = "x"
来源：http://dali.smart0.xyz/Article/details/gtdulyzkbd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guannengcc.top/Article/details/gtarlswyai.html

[G04] 定义方法
来源：http://dali.zhongyouzk.top/Article/details/gtrgcyxpjf.html

Py:   def greet(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gtpkjjwdpz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtommkpyhy.html

JS:   greet() { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gtzuqqghih.html

TS:   greet(): string { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtwigqswtt.html

Java: String greet() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtipyqwmhc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gtdvxhucpx.html

Ruby: def greet; @name; end
来源：http://dali.cucudq.cn/Article/details/gtpvzmcsvs.html

C#:   public string Greet() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gtmhvnmbqc.html

[G05] 继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gtptwjvqvg.html

Py:   class Admin(User): pass
来源：http://dali.pycfn.com/Article/details/gtgaiaxpsu.html

PHP:  class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkgralybj.html

JS:   class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtancamuzj.html

TS:   class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtfcdwiiku.html

Java: class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtuvupstbh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pengpengdd.cyou/Article/details/gtwkdremdr.html

Ruby: class Admin < User; end
来源：http://dali.hfpthk.cn/Article/details/gtxtgcjpbr.html

C#:   class Admin : User {}
来源：http://dali.cdnleiting.top/Article/details/gttgqgevkd.html

[G06] 重写方法
来源：http://dali.c1oappe.top/Article/details/gturmreixq.html

Py:   def greet(self): return "admin"
来源：http://dali.cucudq.cn/Article/details/gtfdgfblpo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtcurrfjju.html

JS:   greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtecsndrib.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtqjcrjzzt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtnndldtbz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.dashuyun.cn/Article/details/gtlddbjukt.html

Ruby: def greet; "admin"; end
来源：http://dali.wangshuangyany.cn/Article/details/gtwhsnroto.html

C#:   public override string Greet() => "admin";
来源：http://dali.hfpthk.cn/Article/details/gtqhqtnfos.html

[G07] 调用父类方法
来源：http://dali.9152youxi.cn/Article/details/gtqvmsqatg.html

Py:   super().greet()
来源：http://dali.jinqigufen.top/Article/details/gtkspabyga.html

PHP:  parent::greet();
来源：http://dali.chenlongwang.top/Article/details/gtmlxoxdih.html

JS:   super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaykbhpot.html

TS:   super.greet();
来源：http://dali.cheryme.top/Article/details/gtmqsmlnhi.html

Java: super.greet();
来源：http://dali.havefunace.top/Article/details/gttjodosaj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cdnleiting.top/Article/details/gtgtysvuis.html

Ruby: super
来源：http://dali.zhongyouzk.top/Article/details/gtqtieltow.html

C#:   base.Greet();
来源：http://dali.xziqi.cn/Article/details/gtuvawkqnj.html

[G08] 静态方法与属性
来源：http://dali.gogol.net.cn/Article/details/gtadglkkoi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hammf.cn/Article/details/gtlyjyjbcv.html

PHP:  public static function f() {}
来源：http://dali.tianlin.xyz/Article/details/gtzqupvkwp.html

JS:   static f() {}
来源：http://dali.nwbrower.top/Article/details/gtdezjoehq.html

TS:   static f(): void {}
来源：http://dali.yj202588.top/Article/details/gtyatpnreh.html

Java: static void f() {}
来源：http://dali.yanxiufei.cn/Article/details/gtuqqlsynt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yuanzhike.top/Article/details/gtbqbxiapa.html

Ruby: def self.f; end
来源：http://dali.yonumen.top/Article/details/gtlmslfhok.html

C#:   public static void F() {}
来源：http://dali.chenlongwang.top/Article/details/gtmycruvua.html

[G09] 接口 / 抽象类
来源：http://dali.cucudq.cn/Article/details/gtjupbhhys.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yangfankeji.com/Article/details/gtpelsawkf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqpvnflsd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.havefunace.top/Article/details/gtvosjhykb.html

TS:   interface Shape { area(): number; }
来源：http://dali.aibaodan.cn/Article/details/gtfmbykwcd.html

Java: interface Shape { double area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtleyouips.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258.top/Article/details/gtidkrkobz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ybcxt.top/Article/details/gtiunarckd.html

C#:   interface IShape { double Area(); }
来源：http://dali.nwbrower.top/Article/details/gtsitsmpgp.html

[G10] 访问控制
来源：http://dali.gzhubu.top/Article/details/gtfgthqezz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guowangkeji.top/Article/details/gtrvntanjx.html

PHP:  public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtnvpgqrna.html

JS:   #private 字段；其余公开
来源：http://dali.fzhhl.top/Article/details/gtktdnpiqg.html

TS:   public / protected / private
来源：http://dali.andypj.xyz/Article/details/gtcrqycqfv.html

Java: public / protected / private / 默认包级
来源：http://dali.fzhhl.top/Article/details/gtnwneyjaw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhoulong.xyz/Article/details/gtzhdmrphb.html

Ruby: public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtcdwvsckt.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gtvlzfktuq.html

[G11] getter / setter
来源：http://dali.chenlongwang.top/Article/details/gtofxezsjz.html

Py:   @property 与 @x.setter
来源：http://dali.guowangkeji.top/Article/details/gtjqhknblh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtxoldnxbn.html

JS:   get name() { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gtkzwbmabj.html

TS:   get name(): string { return this._name; }
来源：http://dali.sxryk.cn/Article/details/gttlvmvfpa.html

Java: public String getName() { return name; }
来源：http://dali.yongpay.top/Article/details/gthsacsdig.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtkhuaurwq.html

Ruby: attr_accessor :name
来源：http://dali.wangshuangyany.cn/Article/details/gtluiwwapz.html

C#:   public string Name { get; set; }
来源：http://dali.yvedp.cn/Article/details/gtrtgqlknf.html

[G12] 对象转字符串
来源：http://dali.chenlongwang.top/Article/details/gtxkzjrktw.html

Py:   def __str__(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gtvdjmbjky.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtzebiggcd.html

JS:   toString() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gtzwftnzug.html

TS:   toString(): string { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtkmgsavhz.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuanzx.com/Article/details/gtsqqlfyzc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtwvcuwpvp.html

Ruby: def to_s; @name; end
来源：http://dali.ehwqpu.com/Article/details/gtfavxlohi.html

C#:   public override string ToString() => Name;
来源：http://dali.yangfankeji.com/Article/details/gtlynafryw.html

[G13] 判断对象类型
来源：http://dali.mhx1999.top/Article/details/gtdlxnbplg.html

Py:   isinstance(u, User)
来源：http://dali.ivvv.top/Article/details/gtyjpmtqkt.html

PHP:  $u instanceof User
来源：http://dali.cucudq.cn/Article/details/gttvsxsggi.html

JS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtilgtpxjq.html

TS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gtvqmxhpjt.html

Java: u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtfnbuorps.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.birdmap.top/Article/details/gtehhnngwm.html

Ruby: u.is_a?(User)
来源：http://dali.shangyingyoupin.top/Article/details/gtaihcnjmu.html

C#:   u is User
来源：http://dali.aizwys.cn/Article/details/gtyrrjxdhl.html

[G14] 数据类 / record
来源：http://dali.gaohongyu789.top/Article/details/gtjppcdwdp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.c1oappe.top/Article/details/gtavbssttp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuecceqvt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hongshengwenyu.top/Article/details/gtgcltxunt.html

TS:   type User = { name: string; age: number };
来源：http://dali.yangfankeji.com/Article/details/gtqwdrsved.html

Java: record User(String name, int age) {}
来源：http://dali.yuxming.cn/Article/details/gtwcuzxxtd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenzaomai.com/Article/details/gtoagcterf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daria6918.cn/Article/details/gtrmshvqnu.html

C#:   record User(string Name, int Age);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsunpvbsd.html

[G15] 枚举
来源：http://dali.sweek.top/Article/details/gtgjekrdbc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jlsjyb.cn/Article/details/gtrecsxfuk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yonumen.top/Article/details/gtppbwbumj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zycfv.cn/Article/details/gtyszgqcts.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.iojbl.cn/Article/details/gtaauhnwrs.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxgowsymp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.9152youxi.cn/Article/details/gtlkiwllij.html

Ruby: Color = %i[red green].freeze
来源：http://dali.316326.xyz/Article/details/gtuwhnfpbe.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gtdwhtgbtt.html

[G16] 对象转数组 / 字典
来源：http://dali.pengpengdd.cyou/Article/details/gtpatkoxxk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.vqdsnc.cn/Article/details/gtzubdmdxx.html

PHP:  get_object_vars($obj);
来源：http://dali.wangshuangyany.cn/Article/details/gtgwtmqvtq.html

JS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gtjdqqnogk.html

TS:   Object.entries(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtuagrigrr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tianlin.xyz/Article/details/gtujrobsnt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenzaomai.com/Article/details/gtlogrufid.html

Ruby: obj.instance_variables
来源：http://dali.haohaochexian.top/Article/details/gtwcoceotu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jianghu66.top/Article/details/gtektzkjas.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtbuyimcka.html

H. 异常与错误处理
来源：http://dali.kuanghao11.cn/Article/details/gtxufdvpyq.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtidqanmbo.html

[H01] try / catch 基础
来源：http://dali.dianchejie.cn/Article/details/gtuqulzaod.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.c1oappe.top/Article/details/gtlgaasvcv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvqfaprly.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gtqjyohblw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gtnbtasqia.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hywenlv.cn/Article/details/gtxfzjhqzk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtelnkintp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.snrcjt.cn/Article/details/gtsqpnqhwv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenlongwang.top/Article/details/gtnomwbikh.html

[H02] finally / ensure 收尾
来源：http://dali.nanxinkj.top/Article/details/gtxbrrgqqb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hfpthk.cn/Article/details/gtmocwkguv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtxtykqiok.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtvyymkuso.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtoojupwmv.html


<!-- 参考信息 -->