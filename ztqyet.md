代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cheryme.top/Article/details/gtggstqckh.html

[E19] 多行文本按行拆分
来源：http://dali.sweek.top/Article/details/gtytyjsmty.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gtqteofbtj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cashguo.top/Article/details/gtnwucluoa.html

JS:   s.split(/\r?\n/)
来源：http://dali.jiagoushi.top/Article/details/gthpfdeyec.html

TS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gtsxsjhkeg.html

Java: s.lines().toList()
来源：http://dali.fengsongda.top/Article/details/gtkucjpmbw.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinqigfzy.top/Article/details/gtnojeirqv.html

Ruby: s.lines
来源：http://dali.sxryk.cn/Article/details/gtiwonpzhx.html

C#:   s.Split('\n')
来源：http://dali.yvedp.cn/Article/details/gtegitnovl.html

[E20] 判断字符串是否为空
来源：http://dali.yanxiufei.cn/Article/details/gtirlzkiwz.html

Py:   if not s:
来源：http://dali.chenjidiqi.icu/Article/details/gtbsuqsnib.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.quarkkingdee.top/Article/details/gthuaickjj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenzaomai.com/Article/details/gtgwesnedi.html

TS:   if (s === "") {}
来源：http://dali.jlsjyb.cn/Article/details/gtjvnuckuh.html

Java: if (s.isEmpty()) {}
来源：http://dali.yongpay.top/Article/details/gtoeudceqr.html

Go:   if s == "" {}
来源：http://dali.daria6918.cn/Article/details/gtmxcmkobd.html

Ruby: if s.empty?
来源：http://dali.cheryme.top/Article/details/gthogxisms.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gtmompiujm.html

[E21] 超长截断加省略号
来源：http://dali.daria6918.cn/Article/details/gtwfqiasvd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sysykeji.top/Article/details/gtdqqrauwb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrsqldvq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtbusmznat.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtyxrhoqqm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpggxlqta.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jianghu66.top/Article/details/gtbzbdcblm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtbbwjjqhy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ivvv.top/Article/details/gtkzgalpcp.html

[E22] 字节长度与字符长度
来源：http://dali.daria6918.cn/Article/details/gtfoidpfab.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jlsjyb.cn/Article/details/gtxomqcajn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gtzygekzck.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gtnidegxau.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtnihfzrgy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ivvv.top/Article/details/gtjuwtrgea.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jianghu66.top/Article/details/gtphlhbjfk.html

Ruby: s.bytesize;  s.length
来源：http://dali.tian-w.cn/Article/details/gtqnkkdmwu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gtqmknsgkz.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtgxbexhjq.html

F. 文件与目录
来源：http://dali.yuanzhike.top/Article/details/gtmcqmxyim.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtepssjyei.html

[F01] 读取整个文件
来源：http://dali.yueranfly.top/Article/details/gtmfqpykmd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hnqzz.top/Article/details/gtslpalnzj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfeykvigx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nanxuanxn.top/Article/details/gtqpritiju.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtsyeaudeb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtmwdqzvxy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhiwuduotai.top/Article/details/gtwarcahsr.html

Ruby: File.read("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtzsooetms.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtqcdyrwus.html

[F02] 逐行读取文件
来源：http://dali.xziqi.cn/Article/details/gtrpyuxjiy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj20258888.top/Article/details/gtvqavhrpe.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yueranfly.top/Article/details/gtpzobgogz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cqqwz.cn/Article/details/gtfkfqowdk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtxprnziiv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ybcxt.top/Article/details/gtcexdgdsx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gaohongyu789.top/Article/details/gtkilnstiv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fzhhl.top/Article/details/gthucsiffx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.316326.xyz/Article/details/gtfhwcxdnh.html

[F03] 写入文件（覆盖）
来源：http://dali.sysykeji.top/Article/details/gtsyptuzjk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jyoumei.cn/Article/details/gtsjlcljuo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gtihsfjnpk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xinyue.icu/Article/details/gtysdwhjxb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gthkzpxbvl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtiaabyvpg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuanzhike.top/Article/details/gtmpmjnnpw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cashguo.top/Article/details/gtkfcwdlak.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tanke756.top/Article/details/gtppztprvx.html

[F04] 追加写入文件
来源：http://dali.dashuyun.cn/Article/details/gtasatdyqu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cashguo.top/Article/details/gtunwgsrnk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cdnleiting.top/Article/details/gtbprfgswg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zdqjudy.top/Article/details/gtczhqoien.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cucudq.cn/Article/details/gtwecmrjwy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhongyouzk.top/Article/details/gtfdrgpuud.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.dianchejie.cn/Article/details/gtheardkjp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.snrcjt.cn/Article/details/gtnhrlygsv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmvhneag.html

[F05] 判断文件或目录是否存在
来源：http://dali.snrcjt.cn/Article/details/gtdgqbjxbc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nwbrower.top/Article/details/gtwqjyeipr.html

PHP:  file_exists("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtoqcsrwah.html

JS:   fs.existsSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gtsquatvek.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtlczkkhuy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtsaiwwwjn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgufenzy.top/Article/details/gtebqngkdk.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtjzpwljie.html

C#:   File.Exists("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gthozkjtdc.html

[F06] 删除文件
来源：http://dali.haohaochexian.top/Article/details/gtgggctibl.html

Py:   os.remove("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtighlnulh.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtlgppfwpj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gttinvzric.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtuyhmesau.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtkagbtelr.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjzqcmls.html

Ruby: File.delete("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtxapohtcf.html

C#:   File.Delete("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtaakabvhu.html

[F07] 创建目录（含多级）
来源：http://dali.snrcjt.cn/Article/details/gtzkmaysyw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yvedp.cn/Article/details/gtaiokacre.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtfidikdnt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gtsdwfxtyr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gtvoheueje.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hammf.cn/Article/details/gtaurlmjwg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.9152youxi.cn/Article/details/gtewsjtxsb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nwbrower.top/Article/details/gtzhdzeoxp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nwbrower.top/Article/details/gtzevzraas.html

[F08] 遍历目录
来源：http://dali.cucudq.cn/Article/details/gtpoxhdpvr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cheryme.top/Article/details/gtzwxqlfuf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtccfqbqjw.html

JS:   fs.readdirSync("dir")
来源：http://dali.svipenyu.cn/Article/details/gteeziimlv.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gtyhujucgv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tian-w.cn/Article/details/gtctedjodz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dashuyun.cn/Article/details/gtgkfzgifg.html

Ruby: Dir.children("dir")
来源：http://dali.yonumen.top/Article/details/gtmjhbnzdl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.snrcjt.cn/Article/details/gtjmgjbmah.html

[F09] 获取文件大小
来源：http://dali.hammf.cn/Article/details/gtuvnsewgp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtdhhxzjze.html

PHP:  filesize("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtttwbqryr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xuetiantiany.cn/Article/details/gtustaizhy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cucudq.cn/Article/details/gtfohbxeri.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtquhdmnfz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenzaomai.com/Article/details/gtudojkxff.html

Ruby: File.size("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gttelxkkfp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.andypj.xyz/Article/details/gtrkpuutje.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.aibaodan.cn/Article/details/gtqhsfzkua.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtbatgefwy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hnqzz.top/Article/details/gtifjtlozc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhpyyoey.html

TS:   path.extname("a.txt")
来源：http://dali.ivvv.top/Article/details/gtzziyxwvq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ppjwa.cn/Article/details/gtxsalgkto.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gteildvvgk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtnyvklqoa.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtbfclfzqs.html

[F11] 复制与移动文件
来源：http://dali.nwbrower.top/Article/details/gtlnqurutc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gtucugzjda.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daria6918.cn/Article/details/gtzttiwuih.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtegnjuxkp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtzpngqdjv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.redwolf501.top/Article/details/gtxfrczocx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ppjwa.cn/Article/details/gtaesmylgz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtqdjlfpqw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daxiang520.top/Article/details/gtcygmuymc.html

[F12] CSV 读写
来源：http://dali.hongshengwenyu.top/Article/details/gtdyctcmql.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.c1oappe.top/Article/details/gtqkedybgi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yongpay.top/Article/details/gtieoyzgoo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.dianchejie.cn/Article/details/gtpmwpzaka.html

TS:   // 同上
来源：http://dali.xuanzx.com/Article/details/gtxtmzqryv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinghuilouyu.cn/Article/details/gtsvklfjrh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj20258.top/Article/details/gtbepbfehz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hnqzz.top/Article/details/gtgyrifbus.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ybcxt.top/Article/details/gtrkeihjmw.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtiblxvzyu.html

G. 面向对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqolpljyk.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqeosgzk.html

[G01] 定义类
来源：http://dali.daria6918.cn/Article/details/gtufpnjcck.html

Py:   class User: pass
来源：http://dali.fzhhl.top/Article/details/gtpfbuvfzf.html

PHP:  class User {}
来源：http://dali.ehwqpu.com/Article/details/gtddpzowlk.html

JS:   class User {}
来源：http://dali.yueranfly.top/Article/details/gtfzhjfezx.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxinkj.top/Article/details/gtyetfgxko.html

Java: class User {}
来源：http://dali.zycfv.cn/Article/details/gttzwixmee.html

Go:   type User struct { Name string }
来源：http://dali.aibaodan.cn/Article/details/gtjyhaancq.html

Ruby: class User; end
来源：http://dali.xinyue.icu/Article/details/gttsbopqsv.html

C#:   class User {}
来源：http://dali.ydzc1.top/Article/details/gtypcehvkf.html

[G02] 构造函数
来源：http://dali.hnxiangtu.top/Article/details/gtfrewoftt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.redwolf501.top/Article/details/gtpbxupeio.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj202588.top/Article/details/gtcfvstkge.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtifvngdou.html

TS:   constructor(public name: string) {}
来源：http://dali.shuidangran.top/Article/details/gtuozcgrit.html

Java: User(String name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtjwbobpul.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guowangkeji.top/Article/details/gtkdtkaljk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhygsxaq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nwbrower.top/Article/details/gtkxymmpic.html

[G03] 实例属性
来源：http://dali.yj20258.top/Article/details/gtesmwbzbj.html

Py:   self.name = "x"
来源：http://dali.yuanzhike.top/Article/details/gtlebigdjm.html

PHP:  public string $name = "x";
来源：http://dali.cashguo.top/Article/details/gtktwovddg.html

JS:   this.name = "x";
来源：http://dali.gogol.net.cn/Article/details/gtotzrcmht.html

TS:   name: string = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtlmdjziou.html

Java: private String name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmsuzqjv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cucudq.cn/Article/details/gtfcmcsxam.html

Ruby: @name = "x"
来源：http://dali.xuanzx.com/Article/details/gtyxrtwycq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtgsekitkq.html

[G04] 定义方法
来源：http://dali.redwolf501.top/Article/details/gtoppqslbd.html

Py:   def greet(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gtjeahhxpp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtstrlwubw.html

JS:   greet() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtpfefzkvh.html

TS:   greet(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gttsnirann.html

Java: String greet() { return name; }
来源：http://dali.yj20258.top/Article/details/gtsmsgzttq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gtgrhhzhtj.html

Ruby: def greet; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gtextymxiw.html

C#:   public string Greet() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gtwaoqogxi.html

[G05] 继承
来源：http://dali.ppjwa.cn/Article/details/gtnxvyfrdf.html

Py:   class Admin(User): pass
来源：http://dali.yvedp.cn/Article/details/gtvjoohgep.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtvuyegrjc.html

JS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtpbxcdoyu.html

TS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gthseskufx.html

Java: class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtjcmvcnlp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nwbrower.top/Article/details/gtbhiujkgj.html

Ruby: class Admin < User; end
来源：http://dali.hongshengwenyu.top/Article/details/gtihpnuanj.html

C#:   class Admin : User {}
来源：http://dali.vqdsnc.cn/Article/details/gtdzfgmrfm.html

[G06] 重写方法
来源：http://dali.bjfxy.top/Article/details/gtfalteudz.html

Py:   def greet(self): return "admin"
来源：http://dali.quarkkingdee.top/Article/details/gtdcwuumhl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtfclnpeyf.html

JS:   greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtrvniapkv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtwtrsoggb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtiqvkdnzw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guannengcc.top/Article/details/gttyipuhnb.html

Ruby: def greet; "admin"; end
来源：http://dali.shangyingyoupin.top/Article/details/gtazdptsya.html

C#:   public override string Greet() => "admin";
来源：http://dali.redwolf501.top/Article/details/gteajagipf.html

[G07] 调用父类方法
来源：http://dali.hnqzz.top/Article/details/gtfihrdhpg.html

Py:   super().greet()
来源：http://dali.0kj1m.cn/Article/details/gthwwqnerw.html

PHP:  parent::greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtstykmmxd.html

JS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gtklfpldkd.html

TS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtzvwgamel.html

Java: super.greet();
来源：http://dali.zycfv.cn/Article/details/gtsndnetby.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxhjpdlo.html

Ruby: super
来源：http://dali.cdnleiting.top/Article/details/gtbiskpesv.html

C#:   base.Greet();
来源：http://dali.sufxvd.cn/Article/details/gtwqvvjdjx.html

[G08] 静态方法与属性
来源：http://dali.havefunace.top/Article/details/gtwajrciji.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj20258.top/Article/details/gtvowbtcxs.html

PHP:  public static function f() {}
来源：http://dali.yuanzhike.top/Article/details/gtnlhvvthp.html

JS:   static f() {}
来源：http://dali.jinqigfzy.top/Article/details/gtvjmcgwiz.html

TS:   static f(): void {}
来源：http://dali.quarkkingdee.top/Article/details/gtgbqfmffc.html

Java: static void f() {}
来源：http://dali.nanxuanxn.top/Article/details/gtwzjmvoyt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzsxmygcl.html

Ruby: def self.f; end
来源：http://dali.gzhubu.top/Article/details/gtmnbkxhtq.html

C#:   public static void F() {}
来源：http://dali.ppjwa.cn/Article/details/gtzrlxcxql.html

[G09] 接口 / 抽象类
来源：http://dali.andypj.xyz/Article/details/gtfaplgfqj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhongyouzk.top/Article/details/gtnjtuelne.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fengsongda.top/Article/details/gtwxphrzgy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.meibo888.top/Article/details/gtucmbyzoy.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigfzy.top/Article/details/gtlrbtpipb.html

Java: interface Shape { double area(); }
来源：http://dali.yvedp.cn/Article/details/gtmrzekhbv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ppjwa.cn/Article/details/gtbozdeqpe.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangdashe.top/Article/details/gtnkjznzyu.html

C#:   interface IShape { double Area(); }
来源：http://dali.hfpthk.cn/Article/details/gtpgdyjxxb.html

[G10] 访问控制
来源：http://dali.jyoumei.cn/Article/details/gtujnarfdh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnstdsbg.html

PHP:  public / protected / private
来源：http://dali.yvedp.cn/Article/details/gtjgrxbtqg.html

JS:   #private 字段；其余公开
来源：http://dali.jqgfzy.top/Article/details/gtmnwwznog.html

TS:   public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtdjkqwnvr.html

Java: public / protected / private / 默认包级
来源：http://dali.cqqwz.cn/Article/details/gtwgeprdrq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.dashuyun.cn/Article/details/gtuiygsbko.html

Ruby: public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwpeimwrg.html

C#:   public / protected / private / internal
来源：http://dali.xinyue.icu/Article/details/gtachyjhri.html

[G11] getter / setter
来源：http://dali.nanxinkj.top/Article/details/gtdsemgelv.html

Py:   @property 与 @x.setter
来源：http://dali.sysykeji.top/Article/details/gtsesmemau.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtetbyydtg.html

JS:   get name() { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gtfcplidwd.html

TS:   get name(): string { return this._name; }
来源：http://dali.dashuyun.cn/Article/details/gtdcxvjoku.html

Java: public String getName() { return name; }
来源：http://dali.andypj.xyz/Article/details/gtqmqtlneg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gtmqldoeuw.html

Ruby: attr_accessor :name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtklipowtj.html

C#:   public string Name { get; set; }
来源：http://dali.dianchejie.cn/Article/details/gtrnegcdia.html

[G12] 对象转字符串
来源：http://dali.yvedp.cn/Article/details/gteotpdepm.html

Py:   def __str__(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gtverkvlue.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtajtzxnxy.html

JS:   toString() { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gthbgiqmxm.html

TS:   toString(): string { return this.name; }
来源：http://dali.ivvv.top/Article/details/gttfthuviq.html

Java: @Override public String toString() { return name; }
来源：http://dali.shuidangran.top/Article/details/gtevheqamp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gtyxtapucv.html

Ruby: def to_s; @name; end
来源：http://dali.yonumen.top/Article/details/gtritkjjai.html

C#:   public override string ToString() => Name;
来源：http://dali.jyoumei.cn/Article/details/gtzljjsrjx.html

[G13] 判断对象类型
来源：http://dali.redwolf501.top/Article/details/gthcydfqyq.html

Py:   isinstance(u, User)
来源：http://dali.chenlongwang.top/Article/details/gtjisalrbc.html

PHP:  $u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtoqdtvqff.html

JS:   u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtlnwdoefm.html

TS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbylwjto.html

Java: u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtwejumsug.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gotoacloud.top/Article/details/gtqgdiwrlt.html

Ruby: u.is_a?(User)
来源：http://dali.chenjidiqi.icu/Article/details/gtddlvhwqj.html

C#:   u is User
来源：http://dali.birdmap.top/Article/details/gtioygybhj.html

[G14] 数据类 / record
来源：http://dali.yuanzhike.top/Article/details/gtgzrneqda.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.quarkkingdee.top/Article/details/gtdmxzdafb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.andypj.xyz/Article/details/gtlojjstfk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yvedp.cn/Article/details/gtotwgrjbo.html

TS:   type User = { name: string; age: number };
来源：http://dali.nanxuanxn.top/Article/details/gtvazgfetd.html

Java: record User(String name, int age) {}
来源：http://dali.jinqigfzy.top/Article/details/gtoqvbyemu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.c1oappe.top/Article/details/gtglkkugwc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yongpay.top/Article/details/gtmnnugnde.html

C#:   record User(string Name, int Age);
来源：http://dali.hnxiangtu.top/Article/details/gtzvnatvxh.html

[G15] 枚举
来源：http://dali.9152youxi.cn/Article/details/gtavovhiha.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.daria6918.cn/Article/details/gtvsefsaqe.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gaohongyu789.top/Article/details/gtldqejclt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.snrcjt.cn/Article/details/gtdzhruebo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gtzldkqtpv.html

Java: enum Color { RED, GREEN }
来源：http://dali.nanxinkj.top/Article/details/gtgybfuxhk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sysykeji.top/Article/details/gtfknfwams.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yanxiufei.cn/Article/details/gtzyhvqzyx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.andypj.xyz/Article/details/gtzrazzkmn.html

[G16] 对象转数组 / 字典
来源：http://dali.zhixingplan.top/Article/details/gtaarongns.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yanxiufei.cn/Article/details/gtegpgxlvw.html

PHP:  get_object_vars($obj);
来源：http://dali.0kj1m.cn/Article/details/gtruqveovi.html

JS:   Object.entries(obj)
来源：http://dali.jyoumei.cn/Article/details/gtduqejglg.html

TS:   Object.entries(obj)
来源：http://dali.sysykeji.top/Article/details/gtsxwhgaem.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.mhx1999.top/Article/details/gtgnucyitq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shangyingyoupin.top/Article/details/gtuyrxukdg.html

Ruby: obj.instance_variables
来源：http://dali.gotoacloud.top/Article/details/gtcglvsfcv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.bjfxy.top/Article/details/gtcvakmksv.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpzgixxkc.html

H. 异常与错误处理
来源：http://dali.fzhhl.top/Article/details/gtlclaexpp.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtjlycqwcp.html

[H01] try / catch 基础
来源：http://dali.chenzaomai.com/Article/details/gtpbougfaw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwusyazw.html


<!-- 参考信息 -->