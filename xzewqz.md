代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.zdqjudy.top/Article/details/gtcrbrhygr.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinqigufen.top/Article/details/gtpcwgjhvv.html

Java: s.lines().toList()
来源：http://dali.wangdashe.top/Article/details/gtjxorxzym.html

Go:   strings.Split(s, "\n")
来源：http://dali.guannengcc.top/Article/details/gtcszbuaxb.html

Ruby: s.lines
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdliihipj.html

C#:   s.Split('\n')
来源：http://dali.fzhhl.top/Article/details/gtzwemplgj.html

[E20] 判断字符串是否为空
来源：http://dali.chenjidiqi.icu/Article/details/gtknkhbuma.html

Py:   if not s:
来源：http://dali.tanke756.top/Article/details/gtfwsqtmyc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xuetiantiany.cn/Article/details/gtcbguouqc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.fzhhl.top/Article/details/gtfeotjptt.html

TS:   if (s === "") {}
来源：http://dali.snrcjt.cn/Article/details/gtimxoobfl.html

Java: if (s.isEmpty()) {}
来源：http://dali.snrcjt.cn/Article/details/gtyzokiuzy.html

Go:   if s == "" {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtolwcpkpo.html

Ruby: if s.empty?
来源：http://dali.guannengcc.top/Article/details/gtbazkbtug.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfubwsfbn.html

[E21] 超长截断加省略号
来源：http://dali.nwbrower.top/Article/details/gthrvfvhen.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xuetiantiany.cn/Article/details/gteitcxmtr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gtvdeztfpx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gtkwdwuzwn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gtcenlctiv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtqedrawsa.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.quarkkingdee.top/Article/details/gteanrpepq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtcahnmwhc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtadstqvgg.html

[E22] 字节长度与字符长度
来源：http://dali.yvedp.cn/Article/details/gtxyjhygos.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.9152youxi.cn/Article/details/gtdfjgtstr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtbvemvmpo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zycfv.cn/Article/details/gtdghsxoif.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gtaktpxdge.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yuxming.cn/Article/details/gtmpubuwlw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cdnleiting.top/Article/details/gtyzsmaeii.html

Ruby: s.bytesize;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtjnkohsmc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xziqi.cn/Article/details/gtmuwcplvf.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtljjgsdlf.html

F. 文件与目录
来源：http://dali.tian-w.cn/Article/details/gtkygnlogl.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtghvofqnf.html

[F01] 读取整个文件
来源：http://dali.yonumen.top/Article/details/gtrltbzmaj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tanke756.top/Article/details/gtbaimzgbj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtruhpynkq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj20258888.top/Article/details/gtrqaycoec.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gtmwmrzkhc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtdiynkooc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nanxinkj.top/Article/details/gtmpuayrbl.html

Ruby: File.read("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtmlpyqkez.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtrltplekp.html

[F02] 逐行读取文件
来源：http://dali.wangdashe.top/Article/details/gtarjbgufh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yuxming.cn/Article/details/gtptoqafpa.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xziqi.cn/Article/details/gtzdmslqzj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gtmoyopakt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gtyupjmggw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gtwzykyzkc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhengqikj.top/Article/details/gtlxzooyun.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttwlsnwas.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gtkzaefubw.html

[F03] 写入文件（覆盖）
来源：http://dali.haohaochexian.top/Article/details/gtjfsasgaz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.kuanghao11.cn/Article/details/gtnfcevgcq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.fzhhl.top/Article/details/gtubhryssb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gtvskqypkb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gtvfhzpvzr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xinyue.icu/Article/details/gtxyxpnexj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.bjfxy.top/Article/details/gtzuegixki.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jianghu66.top/Article/details/gtefeyugma.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowukoten.html

[F04] 追加写入文件
来源：http://dali.smart0.xyz/Article/details/gtkwvkbgmk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fzhhl.top/Article/details/gthnuohzzq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.fzhhl.top/Article/details/gtoehwtses.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gtftegjcsn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttnsttvsu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258888.top/Article/details/gtnwepwsod.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttylziwrp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuxming.cn/Article/details/gtagkdrgal.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hongshengwenyu.top/Article/details/gtnahfadbq.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjykcxwtg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yueranfly.top/Article/details/gtgdistnjg.html

PHP:  file_exists("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtpqwrxtrm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtqteidbgv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtfgdcwded.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtngqphkrb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yonumen.top/Article/details/gtdvwrwwew.html

Ruby: File.exist?("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtcsnkpiik.html

C#:   File.Exists("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtxvimimqp.html

[F06] 删除文件
来源：http://dali.iojbl.cn/Article/details/gtzlouxvps.html

Py:   os.remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtiveczwfx.html

PHP:  unlink("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtagxcatah.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtdztvqydz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtvyrskvri.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtrvvxxgph.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtfllqwpdp.html

Ruby: File.delete("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtmedlpzmg.html

C#:   File.Delete("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtoebbkkwe.html

[F07] 创建目录（含多级）
来源：http://dali.c1oappe.top/Article/details/gtkdtuffre.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tianlin.xyz/Article/details/gtroojdsgo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guowangkeji.top/Article/details/gtnggvhkwo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gtffthxuww.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gtjljdzxwv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.daxiang520.top/Article/details/gtamqjtigi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.birdmap.top/Article/details/gtawzsskqw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tian-w.cn/Article/details/gtqdpfbaaz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hammf.cn/Article/details/gtfwjgaghf.html

[F08] 遍历目录
来源：http://dali.jiagoushi.top/Article/details/gtinaqnwab.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xinyue.icu/Article/details/gterdzuznu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gotoacloud.top/Article/details/gtqhdvkvab.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtyazpaguk.html

TS:   fs.readdirSync("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtzmhglacl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gtbxqlpwyx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.haohaochexian.top/Article/details/gtheojiivr.html

Ruby: Dir.children("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnkinxwlz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtnahgogni.html

[F09] 获取文件大小
来源：http://dali.shuidangran.top/Article/details/gthlwuujis.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtoxhmgdmp.html

PHP:  filesize("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtdqynjbsn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yonumen.top/Article/details/gtjcpzilpb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gtrqmarfoy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtcvowzjnq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangshuangyany.cn/Article/details/gtgdtinjyz.html

Ruby: File.size("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtkawdvpsl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xinyue.icu/Article/details/gtowtblhhq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.andypj.xyz/Article/details/gthqvuwlbx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtuhfyudyr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtlwodlpus.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtotydvwye.html

TS:   path.extname("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtxgyzqvbo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.bjfxy.top/Article/details/gtzwsatrsl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtrfluhbqj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnwijfcrh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtaedbmohp.html

[F11] 复制与移动文件
来源：http://dali.wangdashe.top/Article/details/gtsvfqxhlh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtwbwoigju.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhengqikj.top/Article/details/gtnulkqkqk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtelrqxukd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtnclisfht.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gtiuhtpzez.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daxiang520.top/Article/details/gtnohagqmy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtniwvqpun.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtuyidcmsz.html

[F12] CSV 读写
来源：http://dali.mhx1999.top/Article/details/gtlzxelucs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.havefunace.top/Article/details/gtwkhcjcuk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cucudq.cn/Article/details/gtsybpgdwu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqdwcqax.html

TS:   // 同上
来源：http://dali.zdqjudy.top/Article/details/gtrifgljwu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nwbrower.top/Article/details/gtlxzqqjok.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.svipenyu.cn/Article/details/gtvljcuuky.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhongyouzk.top/Article/details/gtjouuwgck.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.haohaochexian.top/Article/details/gtskaxdkni.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvdehgvz.html

G. 面向对象
来源：http://dali.hywenlv.cn/Article/details/gtlkubojkg.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtntytytik.html

[G01] 定义类
来源：http://dali.svipenyu.cn/Article/details/gtxzmdbsuj.html

Py:   class User: pass
来源：http://dali.hongshengwenyu.top/Article/details/gtxkieyeep.html

PHP:  class User {}
来源：http://dali.ydzc1.top/Article/details/gtrsbhgeql.html

JS:   class User {}
来源：http://dali.yj202588.top/Article/details/gtsecpeayc.html

TS:   class User { name: string = ""; }
来源：http://dali.jqgfzy.top/Article/details/gtaotjsoks.html

Java: class User {}
来源：http://dali.hywenlv.cn/Article/details/gtjgsdatah.html

Go:   type User struct { Name string }
来源：http://dali.nwbrower.top/Article/details/gtlqylqwlx.html

Ruby: class User; end
来源：http://dali.316326.xyz/Article/details/gtmkcgibdk.html

C#:   class User {}
来源：http://dali.daria6918.cn/Article/details/gtmwfhficq.html

[G02] 构造函数
来源：http://dali.chenzaomai.com/Article/details/gtcihsucnh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.bjfxy.top/Article/details/gtxhoaelnh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.0kj1m.cn/Article/details/gtssoqfhtb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guannengcc.top/Article/details/gtaqclordc.html

TS:   constructor(public name: string) {}
来源：http://dali.sxryk.cn/Article/details/gthzsvhtqt.html

Java: User(String name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gtswktrfyw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgpddbkkw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gtixxnkqla.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aizwys.cn/Article/details/gtmbnscgbu.html

[G03] 实例属性
来源：http://dali.jiagoushi.top/Article/details/gtyizvrtjs.html

Py:   self.name = "x"
来源：http://dali.ehwqpu.com/Article/details/gterwgabvz.html

PHP:  public string $name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdijhktg.html

JS:   this.name = "x";
来源：http://dali.gotoacloud.top/Article/details/gtvxyjxzkq.html

TS:   name: string = "x";
来源：http://dali.hnqzz.top/Article/details/gtzybuzvbc.html

Java: private String name;
来源：http://dali.snrcjt.cn/Article/details/gtgeoauhgk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ydzc1.top/Article/details/gtzdyazywv.html

Ruby: @name = "x"
来源：http://dali.xuetiantiany.cn/Article/details/gtydgkwspa.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xuanzx.com/Article/details/gtyzlgobkl.html

[G04] 定义方法
来源：http://dali.xinyue.icu/Article/details/gtxwnvoxob.html

Py:   def greet(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gtwtfdpwac.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gtfinlgcfj.html

JS:   greet() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gttvtiatoi.html

TS:   greet(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtzqbsqbmb.html

Java: String greet() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtygrkblxj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gtmlgbmivp.html

Ruby: def greet; @name; end
来源：http://dali.tian-w.cn/Article/details/gtwjdpmzob.html

C#:   public string Greet() => Name;
来源：http://dali.svipenyu.cn/Article/details/gtxmhxlunq.html

[G05] 继承
来源：http://dali.birdmap.top/Article/details/gtacwohqlu.html

Py:   class Admin(User): pass
来源：http://dali.hammf.cn/Article/details/gtxdhgkjvb.html

PHP:  class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtmzbsfvqt.html

JS:   class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtafqmijbg.html

TS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtknztdkcc.html

Java: class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtvrryhwka.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj20258.top/Article/details/gtcjjmcrgu.html

Ruby: class Admin < User; end
来源：http://dali.kuanghao11.cn/Article/details/gtwotymjwa.html

C#:   class Admin : User {}
来源：http://dali.yj20258.top/Article/details/gtmwqrvqcb.html

[G06] 重写方法
来源：http://dali.zdqjudy.top/Article/details/gtwfxylawa.html

Py:   def greet(self): return "admin"
来源：http://dali.jyoumei.cn/Article/details/gtifqyyqwt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtzzktzzfa.html

JS:   greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtddjnixty.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtwgyjfwgm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gttsfjdihq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinghuilouyu.cn/Article/details/gttkcaweoc.html

Ruby: def greet; "admin"; end
来源：http://dali.zhiwuduotai.top/Article/details/gtvgfoxhci.html

C#:   public override string Greet() => "admin";
来源：http://dali.daxiang520.top/Article/details/gtpugzkbrx.html

[G07] 调用父类方法
来源：http://dali.yvedp.cn/Article/details/gtxqwhlfhp.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gtuemlkxoc.html

PHP:  parent::greet();
来源：http://dali.gzhubu.top/Article/details/gtyomenstt.html

JS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtqyjxarno.html

TS:   super.greet();
来源：http://dali.hysaishi.cn/Article/details/gtkazpgdjy.html

Java: super.greet();
来源：http://dali.xuanzx.com/Article/details/gtvhozxbvo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daria6918.cn/Article/details/gtolkstnme.html

Ruby: super
来源：http://dali.dashuyun.cn/Article/details/gtfdhylecp.html

C#:   base.Greet();
来源：http://dali.0kj1m.cn/Article/details/gtladvfknu.html

[G08] 静态方法与属性
来源：http://dali.yvedp.cn/Article/details/gtonlrvgfk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jianghu66.top/Article/details/gtktmwqrnf.html

PHP:  public static function f() {}
来源：http://dali.xinyue.icu/Article/details/gtnaonndzg.html

JS:   static f() {}
来源：http://dali.jianghu66.top/Article/details/gtenqxgxzu.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtglygmnxp.html

Java: static void f() {}
来源：http://dali.tian-w.cn/Article/details/gtxgukzcom.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gaohongyu789.top/Article/details/gtjtylxazp.html

Ruby: def self.f; end
来源：http://dali.wangdashe.top/Article/details/gtmsuykzjz.html

C#:   public static void F() {}
来源：http://dali.tian-w.cn/Article/details/gtcjfjddbg.html

[G09] 接口 / 抽象类
来源：http://dali.sweek.top/Article/details/gtrgtstsqp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hongshengwenyu.top/Article/details/gtwsgresff.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangdashe.top/Article/details/gtymqfqwki.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.redwolf501.top/Article/details/gtjtrjtcyl.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenlongwang.top/Article/details/gtqkjmgfbw.html

Java: interface Shape { double area(); }
来源：http://dali.jianghu66.top/Article/details/gtmrjmdvwg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvykgqch.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hongshengwenyu.top/Article/details/gtlqrfpryx.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtziyeetpe.html

[G10] 访问控制
来源：http://dali.guowangkeji.top/Article/details/gtcwnvztjh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.0kj1m.cn/Article/details/gtxpazyfng.html

PHP:  public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gteyneohhi.html

JS:   #private 字段；其余公开
来源：http://dali.yj20258888.top/Article/details/gtytfhtsuo.html

TS:   public / protected / private
来源：http://dali.daxiang520.top/Article/details/gtyzovjfzl.html

Java: public / protected / private / 默认包级
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjitlupr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cashguo.top/Article/details/gttzhshyik.html

Ruby: public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtjsjigyeg.html

C#:   public / protected / private / internal
来源：http://dali.ehwqpu.com/Article/details/gttesklbae.html

[G11] getter / setter
来源：http://dali.yvedp.cn/Article/details/gtvvamgzoy.html

Py:   @property 与 @x.setter
来源：http://dali.hfpthk.cn/Article/details/gtqqhnbdfv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtgacgphsk.html

JS:   get name() { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gtehweeciy.html

TS:   get name(): string { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gtfueuodfn.html

Java: public String getName() { return name; }
来源：http://dali.shuidangran.top/Article/details/gtvkjrpolq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrtqfyvvl.html

Ruby: attr_accessor :name
来源：http://dali.yanxiufei.cn/Article/details/gtgbalhioc.html

C#:   public string Name { get; set; }
来源：http://dali.jqgfzy.top/Article/details/gtdlitfwya.html

[G12] 对象转字符串
来源：http://dali.jiagoushi.top/Article/details/gtszzplaqq.html

Py:   def __str__(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gtrthladtp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gtbmksllmb.html

JS:   toString() { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvkrlpusa.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxbdsotmd.html

Java: @Override public String toString() { return name; }
来源：http://dali.nwbrower.top/Article/details/gteopwqpxv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gtinewdahf.html

Ruby: def to_s; @name; end
来源：http://dali.ehwqpu.com/Article/details/gtwtjmzhaa.html

C#:   public override string ToString() => Name;
来源：http://dali.daria6918.cn/Article/details/gthccbzduw.html

[G13] 判断对象类型
来源：http://dali.smart0.xyz/Article/details/gttftmkkrs.html

Py:   isinstance(u, User)
来源：http://dali.vqdsnc.cn/Article/details/gtksqbdofv.html

PHP:  $u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtdwusthdj.html

JS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gteagrxcxe.html

TS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtajbexram.html

Java: u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtsqabsijw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hnxiangtu.top/Article/details/gtaiwptesy.html

Ruby: u.is_a?(User)
来源：http://dali.vqdsnc.cn/Article/details/gtrlmslsuy.html

C#:   u is User
来源：http://dali.chenjidiqi.icu/Article/details/gtywjrlexr.html

[G14] 数据类 / record
来源：http://dali.shzxlz.cn/Article/details/gtristayrz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shangyingyoupin.top/Article/details/gtqiugridm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hywenlv.cn/Article/details/gtwdgmzfkx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xinyue.icu/Article/details/gtjvnluhth.html

TS:   type User = { name: string; age: number };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtirxdixwp.html

Java: record User(String name, int age) {}
来源：http://dali.ydzc1.top/Article/details/gtcilojxar.html

Go:   type User struct { Name string; Age int }
来源：http://dali.havefunace.top/Article/details/gtggujkyfk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sweek.top/Article/details/gtvldppwub.html

C#:   record User(string Name, int Age);
来源：http://dali.gotoacloud.top/Article/details/gtvivdwkcl.html

[G15] 枚举
来源：http://dali.yj202588.top/Article/details/gtpwqkywvj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.316326.xyz/Article/details/gtztphhzor.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhixingplan.top/Article/details/gtgyvfjnuu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yueranfly.top/Article/details/gtiqcqumum.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gtaffgiugg.html

Java: enum Color { RED, GREEN }
来源：http://dali.gogol.net.cn/Article/details/gtgduhotxs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yvedp.cn/Article/details/gtfnvirull.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gogol.net.cn/Article/details/gtomwbzpzu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtjrliueaj.html

[G16] 对象转数组 / 字典
来源：http://dali.gzhubu.top/Article/details/gtkkfwrvhc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hysaishi.cn/Article/details/gtetppgvhp.html

PHP:  get_object_vars($obj);
来源：http://dali.wangdashe.top/Article/details/gtimdheypk.html

JS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gtqiyvdsha.html

TS:   Object.entries(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtgabiwosa.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnqzz.top/Article/details/gtjmfsfyoa.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cucudq.cn/Article/details/gtwhhcbcdq.html

Ruby: obj.instance_variables
来源：http://dali.cashguo.top/Article/details/gtzofnkaly.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ppjwa.cn/Article/details/gtqbtcqhtj.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtklioatvk.html

H. 异常与错误处理
来源：http://dali.ivvv.top/Article/details/gtjnbprdpm.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtajquawav.html

[H01] try / catch 基础
来源：http://dali.ydzc1.top/Article/details/gtzcwuduxs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhiwuduotai.top/Article/details/gtkfdrhvsr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtrmsemubj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtghyqqlyr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gtbuhkuyhx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yvedp.cn/Article/details/gtqnqxiyoe.html


<!-- 参考信息 -->