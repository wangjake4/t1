代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtyktpjqnu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtocreuyyj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtnxrznepm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jqgfzy.top/Article/details/gtdweoxjfz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ivvv.top/Article/details/gtqrmaffwl.html

[E19] 多行文本按行拆分
来源：http://dali.xuetiantiany.cn/Article/details/gtbvczgesu.html

Py:   s.splitlines()
来源：http://dali.vqdsnc.cn/Article/details/gtjyvxwdos.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtrjjplmkc.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhiwuduotai.top/Article/details/gtbgycxiur.html

TS:   s.split(/\r?\n/)
来源：http://dali.yanxiufei.cn/Article/details/gtnaeexjiq.html

Java: s.lines().toList()
来源：http://dali.haohaochexian.top/Article/details/gtkblrdvek.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqyttjin.html

Ruby: s.lines
来源：http://dali.9152youxi.cn/Article/details/gtdtzttobx.html

C#:   s.Split('\n')
来源：http://dali.haohaochexian.top/Article/details/gtybapwjap.html

[E20] 判断字符串是否为空
来源：http://dali.hnqzz.top/Article/details/gtkgpjgrdx.html

Py:   if not s:
来源：http://dali.jqgfzy.top/Article/details/gtusywpdvn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gaohongyu789.top/Article/details/gteodsyemf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.havefunace.top/Article/details/gtpzjyzuta.html

TS:   if (s === "") {}
来源：http://dali.chenzaomai.com/Article/details/gtividkmim.html

Java: if (s.isEmpty()) {}
来源：http://dali.birdmap.top/Article/details/gtawnvbexq.html

Go:   if s == "" {}
来源：http://dali.c1oappe.top/Article/details/gtajfylelu.html

Ruby: if s.empty?
来源：http://dali.shzxlz.cn/Article/details/gtamuoavak.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gzhubu.top/Article/details/gtxfcxcyzk.html

[E21] 超长截断加省略号
来源：http://dali.daxiang520.top/Article/details/gtvmsxcvoq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.kuanghao11.cn/Article/details/gtsvlornvq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gtxwhajmke.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gthbybnucj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtoefoqhet.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtwxwucfeb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cdnleiting.top/Article/details/gticgxwjhy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtjeiikmyq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtihptzrjr.html

[E22] 字节长度与字符长度
来源：http://dali.mhx1999.top/Article/details/gtqzbtyfrs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sweek.top/Article/details/gtewvmpwtm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtgzabupkq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gtfqpkrfth.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gtwpcqzypd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yangfankeji.com/Article/details/gtambatzap.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sufxvd.cn/Article/details/gtaopixaqo.html

Ruby: s.bytesize;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gtnwdmuvxj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhiwuduotai.top/Article/details/gtfmouymcb.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtknczudna.html

F. 文件与目录
来源：http://dali.jqgufenzy.top/Article/details/gtfsyhajsz.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtuyqnfslh.html

[F01] 读取整个文件
来源：http://dali.jinqigufen.top/Article/details/gtlmhtwqiv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shuidangran.top/Article/details/gtiqiudbaw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtwsbymcht.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.feifeiyinyue.top/Article/details/gtonbxusdr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gthrewnzyd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gthhkypzwu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xylfe.cn/Article/details/gtybxleejs.html

Ruby: File.read("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtgexhlscv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtafdnbbqw.html

[F02] 逐行读取文件
来源：http://dali.xziqi.cn/Article/details/gtwfocuvqi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xziqi.cn/Article/details/gtxphyerid.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsfclakuc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sysykeji.top/Article/details/gtaicvsrxk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tanke756.top/Article/details/gtzterxwkk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gtnrhbroaz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbiayqikj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcfnammfx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sxryk.cn/Article/details/gtvkyjgkxu.html

[F03] 写入文件（覆盖）
来源：http://dali.nanxuanxn.top/Article/details/gtuyvuswql.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.bjfxy.top/Article/details/gtpdvzpgeg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ehwqpu.com/Article/details/gtgingjmkq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gterwjowet.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gtkeqjhtsh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sufxvd.cn/Article/details/gtfwzpdvyh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.vqdsnc.cn/Article/details/gtcuivfare.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.daria6918.cn/Article/details/gtwmfunygp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.316326.xyz/Article/details/gtmuxiigbw.html

[F04] 追加写入文件
来源：http://dali.sufxvd.cn/Article/details/gtbmwitbvt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tian-w.cn/Article/details/gtwxyomqhq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tianlin.xyz/Article/details/gtfhkiyyxv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtjxohmsun.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daria6918.cn/Article/details/gtdgrsqinv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sweek.top/Article/details/gthumwthxu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cashguo.top/Article/details/gtpnpndcwl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hongshengwenyu.top/Article/details/gtqtdbxepv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjcuivowh.html

[F05] 判断文件或目录是否存在
来源：http://dali.fengsongda.top/Article/details/gtxcfozoif.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dashuyun.cn/Article/details/gtwjeujypw.html

PHP:  file_exists("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtqqvmgeag.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtgnopadyl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gthqnybqhz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwaiswax.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jiagoushi.top/Article/details/gtsjbaljvy.html

Ruby: File.exist?("a.txt")
来源：http://dali.hnqzz.top/Article/details/gttjbfalvh.html

C#:   File.Exists("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtpwygwpyr.html

[F06] 删除文件
来源：http://dali.pengpengdd.cyou/Article/details/gtepkrugkc.html

Py:   os.remove("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtizrekdjj.html

PHP:  unlink("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtyuijbwkr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtgjuqbozg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtauisazfe.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtukggjozb.html

Go:   os.Remove("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuvrilbgj.html

Ruby: File.delete("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtdhkclzvk.html

C#:   File.Delete("a.txt");
来源：http://dali.zycfv.cn/Article/details/gticwydtgb.html

[F07] 创建目录（含多级）
来源：http://dali.jyoumei.cn/Article/details/gtlnmfjalq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.kuanghao11.cn/Article/details/gtmbbhaxhz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gtfjlexyxc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gtoxgexkps.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gtclygvsih.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hongshengwenyu.top/Article/details/gtyiqdmylw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sufxvd.cn/Article/details/gtlrdgqhtu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tian-w.cn/Article/details/gtdobibpkr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xylfe.cn/Article/details/gtjgskgvbn.html

[F08] 遍历目录
来源：http://dali.tian-w.cn/Article/details/gtaqorjtnm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.redwolf501.top/Article/details/gttjcoaker.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yongpay.top/Article/details/gtpurmtkny.html

JS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gtyyepjopy.html

TS:   fs.readdirSync("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtfrjkwvso.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.quarkkingdee.top/Article/details/gttbwxqhxz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yanxiufei.cn/Article/details/gthyzdvabc.html

Ruby: Dir.children("dir")
来源：http://dali.wangdashe.top/Article/details/gtxdkpfnoy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yongpay.top/Article/details/gtdwjxwxxr.html

[F09] 获取文件大小
来源：http://dali.zhongyouzk.top/Article/details/gtrfkmeper.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtqnbnxdjm.html

PHP:  filesize("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtkmvogtrx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.vqdsnc.cn/Article/details/gtexyiwhib.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhongyouzk.top/Article/details/gtljchheok.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtvuslogbw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gaohongyu789.top/Article/details/gtrldchaxt.html

Ruby: File.size("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtievjjomz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangshuangyany.cn/Article/details/gtkkcfwqdj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlvehntpm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtuiutid.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtyugujzyq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtylmzpdqf.html

TS:   path.extname("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtwmrarhwn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cdnleiting.top/Article/details/gtbkkxanja.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtqvvsmcei.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtehtasfbi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtjzoqxrfw.html

[F11] 复制与移动文件
来源：http://dali.gzhubu.top/Article/details/gtjnspyfwf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtrsfilzlv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zycfv.cn/Article/details/gtnukvwgzm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtvfsbwtsv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtybaybdzi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guannengcc.top/Article/details/gtzkmpjihs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.redwolf501.top/Article/details/gtlymeawmg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtenepsykc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhoulong.xyz/Article/details/gtkubsimjn.html

[F12] CSV 读写
来源：http://dali.vqdsnc.cn/Article/details/gtovueablu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.bjfxy.top/Article/details/gtfacwpgde.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenjidiqi.icu/Article/details/gttvccwcvk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nwbrower.top/Article/details/gtjmnmjyxk.html

TS:   // 同上
来源：http://dali.tianlin.xyz/Article/details/gtfcxqphcq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.guannengcc.top/Article/details/gtrmftfgze.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.redwolf501.top/Article/details/gtrmtrognz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.daxiang520.top/Article/details/gtrhcukkay.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gogol.net.cn/Article/details/gtxpcadeug.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtbpwsiwvt.html

G. 面向对象
来源：http://dali.yj202588.top/Article/details/gtzrtcgafc.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtklinfove.html

[G01] 定义类
来源：http://dali.jinqigfzy.top/Article/details/gtmuhwmzyb.html

Py:   class User: pass
来源：http://dali.meibo888.top/Article/details/gtecqviout.html

PHP:  class User {}
来源：http://dali.dashuyun.cn/Article/details/gtfcptfolj.html

JS:   class User {}
来源：http://dali.c1oappe.top/Article/details/gthfvphqmh.html

TS:   class User { name: string = ""; }
来源：http://dali.hnxiangtu.top/Article/details/gtdwzmrmgb.html

Java: class User {}
来源：http://dali.hammf.cn/Article/details/gtnrfeseho.html

Go:   type User struct { Name string }
来源：http://dali.sxryk.cn/Article/details/gtylqbeiwh.html

Ruby: class User; end
来源：http://dali.bjfxy.top/Article/details/gtrwyjiiaw.html

C#:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtekokzxpv.html

[G02] 构造函数
来源：http://dali.sufxvd.cn/Article/details/gtxdmttahy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hnxiangtu.top/Article/details/gtyfvreszx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hysaishi.cn/Article/details/gtsgmjvyng.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtdnealhsc.html

TS:   constructor(public name: string) {}
来源：http://dali.nanxuanxn.top/Article/details/gtpwrhsndm.html

Java: User(String name) { this.name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtbpqbshzm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxuanxn.top/Article/details/gtnyxlhdih.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.birdmap.top/Article/details/gtpzzfyxkd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tanke756.top/Article/details/gtfqfvvdlk.html

[G03] 实例属性
来源：http://dali.zhiwuduotai.top/Article/details/gtdoiqqnwu.html

Py:   self.name = "x"
来源：http://dali.jiagoushi.top/Article/details/gtdidfhfbi.html

PHP:  public string $name = "x";
来源：http://dali.tianlin.xyz/Article/details/gtpmmirjix.html

JS:   this.name = "x";
来源：http://dali.snrcjt.cn/Article/details/gtlsdqznev.html

TS:   name: string = "x";
来源：http://dali.jqgufenzy.top/Article/details/gthrcxfokw.html

Java: private String name;
来源：http://dali.guowangkeji.top/Article/details/gtjjfbwfmh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmxdtoref.html

Ruby: @name = "x"
来源：http://dali.jianghu66.top/Article/details/gtqjziriqc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cdnleiting.top/Article/details/gtlvvllutt.html

[G04] 定义方法
来源：http://dali.bjfxy.top/Article/details/gtdryuonov.html

Py:   def greet(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtizizeybz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtbhpbhvtx.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtkdlkfgqu.html

TS:   greet(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxkxiypcl.html

Java: String greet() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtufywvwdz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtjlgsyrur.html

Ruby: def greet; @name; end
来源：http://dali.dianchejie.cn/Article/details/gtbokgcqel.html

C#:   public string Greet() => Name;
来源：http://dali.cdnleiting.top/Article/details/gtbmfkanpt.html

[G05] 继承
来源：http://dali.snrcjt.cn/Article/details/gtoahqlhdu.html

Py:   class Admin(User): pass
来源：http://dali.svipenyu.cn/Article/details/gtdcwdxdwf.html

PHP:  class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtsncarisg.html

JS:   class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtyaqxfbme.html

TS:   class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtmblyobja.html

Java: class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtfgknxxbj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hnqzz.top/Article/details/gtdrpubezh.html

Ruby: class Admin < User; end
来源：http://dali.ydzc1.top/Article/details/gtlbszmsdu.html

C#:   class Admin : User {}
来源：http://dali.sxryk.cn/Article/details/gtfzcxvlqb.html

[G06] 重写方法
来源：http://dali.jlsjyb.cn/Article/details/gtjuyutgme.html

Py:   def greet(self): return "admin"
来源：http://dali.9152youxi.cn/Article/details/gtzwfynpbv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtkmkbpznp.html

JS:   greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtvfwlebei.html

TS:   greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtjqdgxfrf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtqpmuzsvp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.kuanghao11.cn/Article/details/gtqclgawrr.html

Ruby: def greet; "admin"; end
来源：http://dali.tian-w.cn/Article/details/gtkhxxlemh.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgufenzy.top/Article/details/gtggfmqhzw.html

[G07] 调用父类方法
来源：http://dali.daxiang520.top/Article/details/gtafrlmncm.html

Py:   super().greet()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjoocvice.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gtsidpiyyn.html

JS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gtnwibpymx.html

TS:   super.greet();
来源：http://dali.xylfe.cn/Article/details/gtnlazhttr.html

Java: super.greet();
来源：http://dali.zycfv.cn/Article/details/gtopmeuogd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenzaomai.com/Article/details/gtsknatgvx.html

Ruby: super
来源：http://dali.yueranfly.top/Article/details/gtkupsxujx.html

C#:   base.Greet();
来源：http://dali.zhongyouzk.top/Article/details/gtejrhtzge.html

[G08] 静态方法与属性
来源：http://dali.sysykeji.top/Article/details/gtmjeazzgh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xylfe.cn/Article/details/gtzrudtaoz.html

PHP:  public static function f() {}
来源：http://dali.gotoacloud.top/Article/details/gtxhswqzgm.html

JS:   static f() {}
来源：http://dali.hysaishi.cn/Article/details/gtunjviatx.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gtleoaezml.html

Java: static void f() {}
来源：http://dali.zhengqikj.top/Article/details/gtjirbahyo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.redwolf501.top/Article/details/gtakvxfgkk.html

Ruby: def self.f; end
来源：http://dali.tianlin.xyz/Article/details/gtnjmvortv.html

C#:   public static void F() {}
来源：http://dali.yuanzhike.top/Article/details/gtcuxocasy.html

[G09] 接口 / 抽象类
来源：http://dali.zdqjudy.top/Article/details/gtyacwknxv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zycfv.cn/Article/details/gtakjwkksl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hongshengwenyu.top/Article/details/gtappdchbq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hongshengwenyu.top/Article/details/gtbyhzvvwn.html

TS:   interface Shape { area(): number; }
来源：http://dali.gotoacloud.top/Article/details/gtettzkpjn.html

Java: interface Shape { double area(); }
来源：http://dali.hysaishi.cn/Article/details/gtygaszmjx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.svipenyu.cn/Article/details/gthfqjzwzq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.pycfn.com/Article/details/gtddyyedwy.html

C#:   interface IShape { double Area(); }
来源：http://dali.jyoumei.cn/Article/details/gtcsizngxh.html

[G10] 访问控制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjtbayhzk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yongpay.top/Article/details/gtrurtgpcu.html

PHP:  public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtgxqsusnd.html

JS:   #private 字段；其余公开
来源：http://dali.jianghu66.top/Article/details/gtsdjgtjjm.html

TS:   public / protected / private
来源：http://dali.meibo888.top/Article/details/gtswloxfpp.html

Java: public / protected / private / 默认包级
来源：http://dali.zhixingplan.top/Article/details/gtdmdjanmt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shangyingyoupin.top/Article/details/gtsikedvqo.html

Ruby: public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gteitfpwin.html

C#:   public / protected / private / internal
来源：http://dali.xuetiantiany.cn/Article/details/gtcbqayrdc.html

[G11] getter / setter
来源：http://dali.yvedp.cn/Article/details/gtyjmvrqvo.html

Py:   @property 与 @x.setter
来源：http://dali.zhiwuduotai.top/Article/details/gtigwujtim.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gtyhqehsws.html

JS:   get name() { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gtlwjoclvm.html

TS:   get name(): string { return this._name; }
来源：http://dali.pycfn.com/Article/details/gtbccaalum.html

Java: public String getName() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvhjohgqe.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkztmqly.html

Ruby: attr_accessor :name
来源：http://dali.nwbrower.top/Article/details/gtehghqudt.html

C#:   public string Name { get; set; }
来源：http://dali.feifeiyinyue.top/Article/details/gttiaoswnt.html

[G12] 对象转字符串
来源：http://dali.zycfv.cn/Article/details/gtahuwurls.html

Py:   def __str__(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gtlskpjfts.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtuxjttxhf.html

JS:   toString() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtfidtqhcv.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtxwjowcic.html

Java: @Override public String toString() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtcizsylun.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gturelkfff.html

Ruby: def to_s; @name; end
来源：http://dali.mhx1999.top/Article/details/gtzdscdevh.html

C#:   public override string ToString() => Name;
来源：http://dali.gogol.net.cn/Article/details/gtsnyhdtbk.html

[G13] 判断对象类型
来源：http://dali.jqgufenzy.top/Article/details/gtdefyinku.html

Py:   isinstance(u, User)
来源：http://dali.sweek.top/Article/details/gtlanrnnkf.html

PHP:  $u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtmlugmwal.html

JS:   u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtlewpwcxa.html

TS:   u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtltzdzlek.html

Java: u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtxpwfhoox.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.birdmap.top/Article/details/gtztwtjhpa.html

Ruby: u.is_a?(User)
来源：http://dali.ppjwa.cn/Article/details/gtalvzwtwi.html

C#:   u is User
来源：http://dali.nwbrower.top/Article/details/gtzmmqmiuv.html

[G14] 数据类 / record
来源：http://dali.ybcxt.top/Article/details/gtkegvmsqu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shzxlz.cn/Article/details/gtgdootblx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yueranfly.top/Article/details/gtpaslrqrp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgfzy.top/Article/details/gtvieqrepj.html

TS:   type User = { name: string; age: number };
来源：http://dali.gogol.net.cn/Article/details/gtxzopgbne.html

Java: record User(String name, int age) {}
来源：http://dali.birdmap.top/Article/details/gtjfghpmlf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.haohaochexian.top/Article/details/gtkkghdmht.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pycfn.com/Article/details/gtzrjinjcj.html

C#:   record User(string Name, int Age);
来源：http://dali.hywenlv.cn/Article/details/gtsybbmzxi.html

[G15] 枚举
来源：http://dali.daxiang520.top/Article/details/gtqogwoyoo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sxryk.cn/Article/details/gtagtvkrjy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hnqzz.top/Article/details/gtytfronjf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigfzy.top/Article/details/gtgswfwlsm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hammf.cn/Article/details/gtfmfgmeph.html

Java: enum Color { RED, GREEN }
来源：http://dali.cashguo.top/Article/details/gtwoulrjsx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dashuyun.cn/Article/details/gtdwywrzqw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.mhx1999.top/Article/details/gtdnlwejfx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtkpdoyzog.html

[G16] 对象转数组 / 字典
来源：http://dali.xuetiantiany.cn/Article/details/gtawzhxjcy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvbqkqxhn.html

PHP:  get_object_vars($obj);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzfavutks.html

JS:   Object.entries(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtxswijkvj.html

TS:   Object.entries(obj)
来源：http://dali.sysykeji.top/Article/details/gthganxxfe.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.guowangkeji.top/Article/details/gtxdngairr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daxiang520.top/Article/details/gtlevpywbg.html

Ruby: obj.instance_variables
来源：http://dali.yj20258.top/Article/details/gtzvtxfgpm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gtbyyuhjgy.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtemuvsncj.html


<!-- 参考信息 -->