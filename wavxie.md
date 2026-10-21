代发 wailian999

Ruby: s.lines
来源：http://dali.snrcjt.cn/Article/details/gtmufcmbtn.html

C#:   s.Split('\n')
来源：http://dali.birdmap.top/Article/details/gtigqonwyd.html

[E20] 判断字符串是否为空
来源：http://dali.wangshuangyany.cn/Article/details/gtcmxrzmmk.html

Py:   if not s:
来源：http://dali.jqgufenzy.top/Article/details/gtnvhdgalv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xziqi.cn/Article/details/gtuobltery.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jyoumei.cn/Article/details/gtkryldceb.html

TS:   if (s === "") {}
来源：http://dali.hnxiangtu.top/Article/details/gtyinlmmwl.html

Java: if (s.isEmpty()) {}
来源：http://dali.jlsjyb.cn/Article/details/gthqxyjehi.html

Go:   if s == "" {}
来源：http://dali.yuanzhike.top/Article/details/gtzedmcrev.html

Ruby: if s.empty?
来源：http://dali.meibo888.top/Article/details/gtgbvogfsm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.daria6918.cn/Article/details/gtviqvymdv.html

[E21] 超长截断加省略号
来源：http://dali.gaohongyu789.top/Article/details/gtxsjtzeef.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sufxvd.cn/Article/details/gtsvtentna.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gtupwpafvq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtqkbrkwzp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gtyaxzjjkw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gteqscncwn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zdqjudy.top/Article/details/gtnezcwlxv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ydzc1.top/Article/details/gthikbmier.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nwbrower.top/Article/details/gttzmtvxgo.html

[E22] 字节长度与字符长度
来源：http://dali.aizwys.cn/Article/details/gtlbhpfqva.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sysykeji.top/Article/details/gtnttfdcta.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtsrcfljbf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuanzx.com/Article/details/gtlhvvzkog.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuxming.cn/Article/details/gtxhaxtzrc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.redwolf501.top/Article/details/gtnohbwlde.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jqgfzy.top/Article/details/gtjymhmarn.html

Ruby: s.bytesize;  s.length
来源：http://dali.zdqjudy.top/Article/details/gtbpmnzeoh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsoeyqjat.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtmzgvglxz.html

F. 文件与目录
来源：http://dali.sysykeji.top/Article/details/gtnjsyhtmm.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtsjzsqtrz.html

[F01] 读取整个文件
来源：http://dali.yueranfly.top/Article/details/gtcxgnxxhl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.mhx1999.top/Article/details/gticmfjhsi.html

PHP:  file_get_contents("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtzrajmyda.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fzhhl.top/Article/details/gtjrqjmjja.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtsrletula.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gtgmvpcotq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinghuilouyu.cn/Article/details/gtawwrfgpp.html

Ruby: File.read("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshjwuuhd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtvcbzrfja.html

[F02] 逐行读取文件
来源：http://dali.yj20258.top/Article/details/gtaczcwzrs.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hammf.cn/Article/details/gtahpmpepw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yuxming.cn/Article/details/gtlksgchpg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhongyouzk.top/Article/details/gtodzgywmj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yanxiufei.cn/Article/details/gtkkmmzaqr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gtpwyuvxyz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hfpthk.cn/Article/details/gtrmdnvxqm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.guannengcc.top/Article/details/gtkhvxiqxe.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daxiang520.top/Article/details/gturrtpude.html

[F03] 写入文件（覆盖）
来源：http://dali.chenlongwang.top/Article/details/gtmvqgeujb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.wangshuangyany.cn/Article/details/gtizhjprpn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtyuvsqnuq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtevtokubs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hammf.cn/Article/details/gtowdrjtcq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hongshengwenyu.top/Article/details/gtsqumovwg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yongpay.top/Article/details/gtgmrfkobi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.kuanghao11.cn/Article/details/gtezgtugal.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhengqikj.top/Article/details/gtafleylht.html

[F04] 追加写入文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwylsgkk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ybcxt.top/Article/details/gtyztizwwa.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.havefunace.top/Article/details/gthxruutdz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpsxrmzzj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shuidangran.top/Article/details/gtmfyvhhuf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtyfgdio.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jqgfzy.top/Article/details/gtumsxxxbb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.birdmap.top/Article/details/gtabjemdpe.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ivvv.top/Article/details/gtdwbjeduj.html

[F05] 判断文件或目录是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpoxqnebx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fzhhl.top/Article/details/gtdsudzujq.html

PHP:  file_exists("a.txt");
来源：http://dali.meibo888.top/Article/details/gtfobquuoj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gttkubyiqh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtjmlszaeq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtejoofsuq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.havefunace.top/Article/details/gtdzqpjkdg.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258888.top/Article/details/gthydwrlwz.html

C#:   File.Exists("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtrdtsndjd.html

[F06] 删除文件
来源：http://dali.shzxlz.cn/Article/details/gtwdfmgpha.html

Py:   os.remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtkucbpkik.html

PHP:  unlink("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtespsdsmr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtgahvhkqx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtdcbfdzjr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtvuufymyl.html

Go:   os.Remove("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtrqjbdfhf.html

Ruby: File.delete("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gttgxduwrh.html

C#:   File.Delete("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtjjsqktyq.html

[F07] 创建目录（含多级）
来源：http://dali.redwolf501.top/Article/details/gttwxvdrsc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.kuanghao11.cn/Article/details/gtawjjurfz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xinyue.icu/Article/details/gtgjnsetcr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.0kj1m.cn/Article/details/gtchmorguf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gtwxsrdggm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.daxiang520.top/Article/details/gtzlufgmcv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gotoacloud.top/Article/details/gtuntrgfgf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shuidangran.top/Article/details/gtrhdufpil.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yvedp.cn/Article/details/gtcvamfzhf.html

[F08] 遍历目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqplragvp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenzaomai.com/Article/details/gtldgpnndm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhiwuduotai.top/Article/details/gtymvrtijz.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenzaomai.com/Article/details/gtuwswvual.html

TS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gtxzwdjbhq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gtylcwawzx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtfnutzgov.html

Ruby: Dir.children("dir")
来源：http://dali.cheryme.top/Article/details/gtfxyzomwq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenzaomai.com/Article/details/gtdwsjzarx.html

[F09] 获取文件大小
来源：http://dali.tian-w.cn/Article/details/gtfdfilqwu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtcwatoweg.html

PHP:  filesize("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtsmiodedd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yuanzhike.top/Article/details/gtyhqheejw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gthgqoezud.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtqaiyzuia.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.c1oappe.top/Article/details/gtnauvcvhf.html

Ruby: File.size("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtpdfsprbk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj202588.top/Article/details/gthgaidqtg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sysykeji.top/Article/details/gtgsdbmtkh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtqpjmhalh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtfebqcyxd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gteyzfngdk.html

TS:   path.extname("a.txt")
来源：http://dali.yj20258.top/Article/details/gtdsezwgdf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cdnleiting.top/Article/details/gtklfinnzm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtxyycdyab.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtfbgirjvc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtnyzyuspm.html

[F11] 复制与移动文件
来源：http://dali.redwolf501.top/Article/details/gteyoixucg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtijzhnrtn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.aizwys.cn/Article/details/gtojgocmhs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gttgfisbit.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtjgdlmzpq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cashguo.top/Article/details/gtcnqfocte.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenlongwang.top/Article/details/gtrxsfwhvx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtpttbasqb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cqqwz.cn/Article/details/gtudkxawvb.html

[F12] CSV 读写
来源：http://dali.c1oappe.top/Article/details/gtuvmkzkzc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hongshengwenyu.top/Article/details/gtjjquzhvs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.fengsongda.top/Article/details/gtvkhdmkhu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gotoacloud.top/Article/details/gtdyxwuqph.html

TS:   // 同上
来源：http://dali.cheryme.top/Article/details/gtjsshybea.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtxssjsh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cheryme.top/Article/details/gthkptkzuf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xylfe.cn/Article/details/gtzdpisljz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258888.top/Article/details/gtqrlzcrgi.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtacupcnpo.html

G. 面向对象
来源：http://dali.snrcjt.cn/Article/details/gtcpuapriy.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtglsnoehh.html

[G01] 定义类
来源：http://dali.yongpay.top/Article/details/gtcfljifzx.html

Py:   class User: pass
来源：http://dali.daria6918.cn/Article/details/gtflultzfw.html

PHP:  class User {}
来源：http://dali.daxiang520.top/Article/details/gtphtydqyi.html

JS:   class User {}
来源：http://dali.cqqwz.cn/Article/details/gtjcgpobmv.html

TS:   class User { name: string = ""; }
来源：http://dali.ppjwa.cn/Article/details/gtmktuvomd.html

Java: class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtcecosyis.html

Go:   type User struct { Name string }
来源：http://dali.yj20258888.top/Article/details/gtzhpugely.html

Ruby: class User; end
来源：http://dali.hongshengwenyu.top/Article/details/gtbialbsbq.html

C#:   class User {}
来源：http://dali.yj20258.top/Article/details/gtbuszcunz.html

[G02] 构造函数
来源：http://dali.daxiang520.top/Article/details/gtstkkwaqs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhiwuduotai.top/Article/details/gtyrckiyvj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gaohongyu789.top/Article/details/gthzxkoplo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtpaoiupyd.html

TS:   constructor(public name: string) {}
来源：http://dali.daxiang520.top/Article/details/gtzaiqricr.html

Java: User(String name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gtdiumepvi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gaohongyu789.top/Article/details/gtyjvujgfb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ydzc1.top/Article/details/gteenjkrvy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.c1oappe.top/Article/details/gtxxzxxzzb.html

[G03] 实例属性
来源：http://dali.jqgufenzy.top/Article/details/gtivycgfhh.html

Py:   self.name = "x"
来源：http://dali.cqqwz.cn/Article/details/gtlittsazw.html

PHP:  public string $name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtqqwdckri.html

JS:   this.name = "x";
来源：http://dali.fengsongda.top/Article/details/gtcugialaq.html

TS:   name: string = "x";
来源：http://dali.nwbrower.top/Article/details/gtnulwipdd.html

Java: private String name;
来源：http://dali.daxiang520.top/Article/details/gtcvdgiane.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sufxvd.cn/Article/details/gtdqfwinjn.html

Ruby: @name = "x"
来源：http://dali.dianchejie.cn/Article/details/gtetcsxsig.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hysaishi.cn/Article/details/gtmawvbehj.html

[G04] 定义方法
来源：http://dali.bjfxy.top/Article/details/gtybzdvdxk.html

Py:   def greet(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gtnclhheuk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmjnoapdq.html

JS:   greet() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtlceerehp.html

TS:   greet(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtbfqnqlqz.html

Java: String greet() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtylmigvyx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gtsiapqzlf.html

Ruby: def greet; @name; end
来源：http://dali.dashuyun.cn/Article/details/gtztyapwhd.html

C#:   public string Greet() => Name;
来源：http://dali.0kj1m.cn/Article/details/gtmdtjukwe.html

[G05] 继承
来源：http://dali.fengsongda.top/Article/details/gtboyvtmfw.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjincgja.html

PHP:  class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoeoojukb.html

JS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtmbeihcwv.html

TS:   class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtrqkxopjq.html

Java: class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtxojpjnxq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.daxiang520.top/Article/details/gtmtwpflvk.html

Ruby: class Admin < User; end
来源：http://dali.chenjidiqi.icu/Article/details/gtkeafcues.html

C#:   class Admin : User {}
来源：http://dali.guowangkeji.top/Article/details/gtzpmwgnbg.html

[G06] 重写方法
来源：http://dali.hfpthk.cn/Article/details/gtlaljrxtt.html

Py:   def greet(self): return "admin"
来源：http://dali.ppjwa.cn/Article/details/gtlwyhvvvr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtpdjaibkw.html

JS:   greet() { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtmumciwna.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtswpijfvq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gtjckinmep.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yvedp.cn/Article/details/gtwzezkaat.html

Ruby: def greet; "admin"; end
来源：http://dali.nanxuanxn.top/Article/details/gtslftnjzu.html

C#:   public override string Greet() => "admin";
来源：http://dali.yvedp.cn/Article/details/gthuxqmkwj.html

[G07] 调用父类方法
来源：http://dali.iojbl.cn/Article/details/gturctdvpa.html

Py:   super().greet()
来源：http://dali.quarkkingdee.top/Article/details/gtskabusay.html

PHP:  parent::greet();
来源：http://dali.sysykeji.top/Article/details/gtnipcjbqh.html

JS:   super.greet();
来源：http://dali.wangdashe.top/Article/details/gtumiaarkv.html

TS:   super.greet();
来源：http://dali.yonumen.top/Article/details/gtzzczzoji.html

Java: super.greet();
来源：http://dali.snrcjt.cn/Article/details/gtrpsywfqy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sxryk.cn/Article/details/gtdyhmpybq.html

Ruby: super
来源：http://dali.jiagoushi.top/Article/details/gtobttiebj.html

C#:   base.Greet();
来源：http://dali.xinyue.icu/Article/details/gtvowetglw.html

[G08] 静态方法与属性
来源：http://dali.chenjidiqi.icu/Article/details/gtgqbppkxb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.316326.xyz/Article/details/gtorrhgapj.html

PHP:  public static function f() {}
来源：http://dali.sxryk.cn/Article/details/gtdpycvlnj.html

JS:   static f() {}
来源：http://dali.yanxiufei.cn/Article/details/gtwouogqhy.html

TS:   static f(): void {}
来源：http://dali.jqgufenzy.top/Article/details/gtwihcdmqj.html

Java: static void f() {}
来源：http://dali.nanxuanxn.top/Article/details/gtniuomvnz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgfzy.top/Article/details/gtnsxtlctm.html

Ruby: def self.f; end
来源：http://dali.gotoacloud.top/Article/details/gtkapzsubs.html

C#:   public static void F() {}
来源：http://dali.gotoacloud.top/Article/details/gtgoampiji.html

[G09] 接口 / 抽象类
来源：http://dali.fengsongda.top/Article/details/gtfeewtxzt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ppjwa.cn/Article/details/gtjjienrhb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuetiantiany.cn/Article/details/gtokjkemwe.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ybcxt.top/Article/details/gtntfzdmza.html

TS:   interface Shape { area(): number; }
来源：http://dali.tian-w.cn/Article/details/gtgasjqizr.html

Java: interface Shape { double area(); }
来源：http://dali.yueranfly.top/Article/details/gtlnsgjdsq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cqqwz.cn/Article/details/gtrwmhepvh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hywenlv.cn/Article/details/gtlfimeokv.html

C#:   interface IShape { double Area(); }
来源：http://dali.havefunace.top/Article/details/gtvigqlxbl.html

[G10] 访问控制
来源：http://dali.yangfankeji.com/Article/details/gtrznveiki.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nanxuanxn.top/Article/details/gtmgbbdvtw.html

PHP:  public / protected / private
来源：http://dali.cashguo.top/Article/details/gtcmuxxrwa.html

JS:   #private 字段；其余公开
来源：http://dali.cashguo.top/Article/details/gtinllsqey.html

TS:   public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtktbkufup.html

Java: public / protected / private / 默认包级
来源：http://dali.zhengqikj.top/Article/details/gtcxgjbllk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guowangkeji.top/Article/details/gtgodcqlhz.html

Ruby: public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gtdutpebkr.html

C#:   public / protected / private / internal
来源：http://dali.xylfe.cn/Article/details/gtvfkyaape.html

[G11] getter / setter
来源：http://dali.guannengcc.top/Article/details/gtgfdxnwtq.html

Py:   @property 与 @x.setter
来源：http://dali.yanxiufei.cn/Article/details/gtgvxoiipl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gtxotsmici.html

JS:   get name() { return this._name; }
来源：http://dali.snrcjt.cn/Article/details/gtmqcdcngz.html

TS:   get name(): string { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gtwgxxtzdv.html

Java: public String getName() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtneejgrrt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtuhrnzfbs.html

Ruby: attr_accessor :name
来源：http://dali.cucudq.cn/Article/details/gtwpzildrw.html

C#:   public string Name { get; set; }
来源：http://dali.zhongyouzk.top/Article/details/gtovjcplri.html

[G12] 对象转字符串
来源：http://dali.zhongyouzk.top/Article/details/gtrfhcomgx.html

Py:   def __str__(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gtnsxnptsl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtgivdlsnt.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvdvnaks.html

TS:   toString(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtupaamdhw.html

Java: @Override public String toString() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtmksonlse.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtcqycoejb.html

Ruby: def to_s; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbgbhjgac.html

C#:   public override string ToString() => Name;
来源：http://dali.guannengcc.top/Article/details/gtrlxssncd.html

[G13] 判断对象类型
来源：http://dali.iojbl.cn/Article/details/gtiurvxmdp.html

Py:   isinstance(u, User)
来源：http://dali.yj202588.top/Article/details/gtrnfyowiw.html

PHP:  $u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtybgomiox.html

JS:   u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtyxvilpfz.html

TS:   u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtsqjbkbxi.html

Java: u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gtedyuyfmb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinghuilouyu.cn/Article/details/gtniyqczjv.html

Ruby: u.is_a?(User)
来源：http://dali.yonumen.top/Article/details/gtrkrwukjo.html

C#:   u is User
来源：http://dali.wangshuangyany.cn/Article/details/gtgugajtgz.html

[G14] 数据类 / record
来源：http://dali.smart0.xyz/Article/details/gtmpawevrz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ppjwa.cn/Article/details/gtnewoddft.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cheryme.top/Article/details/gtjdeyyfmr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zdqjudy.top/Article/details/gtgwdhgjhh.html

TS:   type User = { name: string; age: number };
来源：http://dali.meibo888.top/Article/details/gtzeydrklx.html

Java: record User(String name, int age) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujmtnkja.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hfpthk.cn/Article/details/gtxheadequ.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.haohaochexian.top/Article/details/gtbgqlrett.html

C#:   record User(string Name, int Age);
来源：http://dali.gogol.net.cn/Article/details/gtkvarzpab.html

[G15] 枚举
来源：http://dali.hnxiangtu.top/Article/details/gtwsstswwu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhoulong.xyz/Article/details/gtedgfbwaq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cucudq.cn/Article/details/gtlgpffwit.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sufxvd.cn/Article/details/gtrwxwprbe.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gtsrtdtmwc.html

Java: enum Color { RED, GREEN }
来源：http://dali.hnxiangtu.top/Article/details/gtqbhsfzrg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcbfrmtv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.dianchejie.cn/Article/details/gtzbqrbmik.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gtqhixfeyj.html

[G16] 对象转数组 / 字典
来源：http://dali.pengpengdd.cyou/Article/details/gtkekqzjos.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.wangdashe.top/Article/details/gtbrcifabj.html

PHP:  get_object_vars($obj);
来源：http://dali.zdqjudy.top/Article/details/gtbvjqljwk.html

JS:   Object.entries(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbqucuvck.html

TS:   Object.entries(obj)
来源：http://dali.tanke756.top/Article/details/gthnxniyyd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.c1oappe.top/Article/details/gtewopjpfw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.havefunace.top/Article/details/gtuikdmdyk.html

Ruby: obj.instance_variables
来源：http://dali.yj20258.top/Article/details/gtpzzfvpbm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tanke756.top/Article/details/gtdbjgztlc.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtwrgiydqs.html

H. 异常与错误处理
来源：http://dali.yueranfly.top/Article/details/gtkhxngmtl.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtuyumpnay.html

[H01] try / catch 基础
来源：http://dali.havefunace.top/Article/details/gtpcvkbbth.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.mhx1999.top/Article/details/gtmflggkvq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.quarkkingdee.top/Article/details/gteoolqrsg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gtxxjeejao.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxkoemhvd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtstakycmg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnxiangtu.top/Article/details/gtvdwubjmt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aibaodan.cn/Article/details/gtgqrhxolp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhixingplan.top/Article/details/gtedmjpibq.html

[H02] finally / ensure 收尾
来源：http://dali.daria6918.cn/Article/details/gtiyzswpgs.html


<!-- 参考信息 -->