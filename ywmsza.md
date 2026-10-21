代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gtxizlftwc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtvlwpenls.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gteysitobg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yueranfly.top/Article/details/gtdfrmstyk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jqgfzy.top/Article/details/gtoqwdrayf.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gtuypxwbgr.html

Py:   s.splitlines()
来源：http://dali.xuanzx.com/Article/details/gtbrmneokr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtblemgaph.html

JS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gtocllimjl.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnqzz.top/Article/details/gtdbchftws.html

Java: s.lines().toList()
来源：http://dali.tanke756.top/Article/details/gtildvhfsu.html

Go:   strings.Split(s, "\n")
来源：http://dali.sxryk.cn/Article/details/gtijmdsumy.html

Ruby: s.lines
来源：http://dali.xylfe.cn/Article/details/gtwittskbi.html

C#:   s.Split('\n')
来源：http://dali.iojbl.cn/Article/details/gtgpfjzaur.html

[E20] 判断字符串是否为空
来源：http://dali.sweek.top/Article/details/gttsorpvpp.html

Py:   if not s:
来源：http://dali.hnqzz.top/Article/details/gtwlezyipi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.birdmap.top/Article/details/gtzmxvksfu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtbtiyicsb.html

TS:   if (s === "") {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvilaicyp.html

Java: if (s.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gtafvuhgko.html

Go:   if s == "" {}
来源：http://dali.redwolf501.top/Article/details/gtgayygnza.html

Ruby: if s.empty?
来源：http://dali.yj202588.top/Article/details/gtmvkgpbno.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zdqjudy.top/Article/details/gtgwmrkulh.html

[E21] 超长截断加省略号
来源：http://dali.ydzc1.top/Article/details/gtvvmneqig.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.vqdsnc.cn/Article/details/gthrqdicmm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gtxyweupnh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtsdnmnvvr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtybdklogt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtletbfjqy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ydzc1.top/Article/details/gtpmnvcgpa.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ivvv.top/Article/details/gtqufjwktr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sweek.top/Article/details/gtuwlcxibk.html

[E22] 字节长度与字符长度
来源：http://dali.gogol.net.cn/Article/details/gtwvfmscqk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.havefunace.top/Article/details/gtbbuqgdzz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtnrehyyks.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuanzhike.top/Article/details/gtrxzzcqaj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jianghu66.top/Article/details/gtzspcgdrp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shzxlz.cn/Article/details/gtyhpgsjsz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cdnleiting.top/Article/details/gthezoxsex.html

Ruby: s.bytesize;  s.length
来源：http://dali.sxryk.cn/Article/details/gtzhzdguge.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gtciqrxiss.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtafaikuch.html

F. 文件与目录
来源：http://dali.jyoumei.cn/Article/details/gtebqbpgqi.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtksgfeqlf.html

[F01] 读取整个文件
来源：http://dali.pycfn.com/Article/details/gtuvfvlllr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangtech.top/Article/details/gtimhcxguk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtpygwkxdy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nanxuanxn.top/Article/details/gtgemrsitu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gtgxjeepnu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gteorlzoax.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.wangdashe.top/Article/details/gtmbujtuci.html

Ruby: File.read("a.txt")
来源：http://dali.pycfn.com/Article/details/gtdaratqao.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtrmhtscjw.html

[F02] 逐行读取文件
来源：http://dali.zhiwuduotai.top/Article/details/gtkddgngvr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.9152youxi.cn/Article/details/gtjzdvksut.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhoulong.xyz/Article/details/gtnpdffirf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gzhubu.top/Article/details/gtmmkvahwb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jyoumei.cn/Article/details/gthjfstans.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shangyingyoupin.top/Article/details/gtkfuotlvr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yonumen.top/Article/details/gtwwgyvqqb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.9152youxi.cn/Article/details/gtamecdawz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yanxiufei.cn/Article/details/gtgwkwcqhc.html

[F03] 写入文件（覆盖）
来源：http://dali.9152youxi.cn/Article/details/gtqcieejco.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cheryme.top/Article/details/gtzdwghcnd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj20258888.top/Article/details/gtsvoecaxa.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.meibo888.top/Article/details/gtuhnprgxc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfvsbpxp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigufen.top/Article/details/gtwqkqltlw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.316326.xyz/Article/details/gtfkqrwwgx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.fengsongda.top/Article/details/gtpieuorsi.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gtpysplpna.html

[F04] 追加写入文件
来源：http://dali.c1oappe.top/Article/details/gtphvzaahd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.iojbl.cn/Article/details/gthqcydhis.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.bjfxy.top/Article/details/gtezrzzhgh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenzaomai.com/Article/details/gtorhpljhd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gtdpbfxzdu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hywenlv.cn/Article/details/gtbdgoyvqa.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yonumen.top/Article/details/gtafyoatbe.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yonumen.top/Article/details/gtjiindaeg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shuidangran.top/Article/details/gtjbjxtirc.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gthenezmcy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.mhx1999.top/Article/details/gtfccqctmg.html

PHP:  file_exists("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtxtkepqhn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtrplpipjq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtqwwkvsbo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtgxntogsl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cucudq.cn/Article/details/gtjffbcudl.html

Ruby: File.exist?("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtqtwcmkmz.html

C#:   File.Exists("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtgzhmukap.html

[F06] 删除文件
来源：http://dali.yueranfly.top/Article/details/gtjahvawix.html

Py:   os.remove("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtgeqkzvnj.html

PHP:  unlink("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtawqpvtld.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtxmeepixi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtxnrrlyqn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtwarcphqb.html

Go:   os.Remove("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtytvspdho.html

Ruby: File.delete("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtflkrqpfb.html

C#:   File.Delete("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtovaavzkr.html

[F07] 创建目录（含多级）
来源：http://dali.yanxiufei.cn/Article/details/gtopiuwtvv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jqgfzy.top/Article/details/gtdbcwboko.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yvedp.cn/Article/details/gtbduwvimq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yonumen.top/Article/details/gtabhmxfms.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenzaomai.com/Article/details/gtuxupfhin.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dianchejie.cn/Article/details/gtcrljjmbp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ehwqpu.com/Article/details/gteeueaglj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daria6918.cn/Article/details/gtnjruesci.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gaohongyu789.top/Article/details/gtfxozfhdv.html

[F08] 遍历目录
来源：http://dali.yuxming.cn/Article/details/gtohimifii.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhixingplan.top/Article/details/gttlyenrat.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.quarkkingdee.top/Article/details/gtrkaniywc.html

JS:   fs.readdirSync("dir")
来源：http://dali.jiagoushi.top/Article/details/gtrlkgonco.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtvwdniogi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sweek.top/Article/details/gtdlgomedk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenlongwang.top/Article/details/gtlgtyjnsn.html

Ruby: Dir.children("dir")
来源：http://dali.smart0.xyz/Article/details/gtuvhpqxec.html

C#:   Directory.GetFiles("dir")
来源：http://dali.andypj.xyz/Article/details/gtlugagjpv.html

[F09] 获取文件大小
来源：http://dali.andypj.xyz/Article/details/gthzchnozw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtazgqaizj.html

PHP:  filesize("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtriodizsm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sxryk.cn/Article/details/gtzdxhwgyu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhixingplan.top/Article/details/gtluiwrnmu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtppclecqw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ppjwa.cn/Article/details/gtnbrpjdri.html

Ruby: File.size("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtesbnlbti.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yanxiufei.cn/Article/details/gtokjcqhln.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.aibaodan.cn/Article/details/gtniczomcv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtvtfivaqu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tian-w.cn/Article/details/gtckoujfhj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtbshvzucw.html

TS:   path.extname("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttztdtpks.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nanxuanxn.top/Article/details/gtexbipeex.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtwwazfkzg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtattxwltd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gttxhqxdhf.html

[F11] 复制与移动文件
来源：http://dali.cucudq.cn/Article/details/gtzjjamzde.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtbuucvkqh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hysaishi.cn/Article/details/gtdrpvlgyx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtwudjhqeg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtfybqfvnd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sufxvd.cn/Article/details/gtgkuoprrj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yueranfly.top/Article/details/gtmzalimux.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtediexaoe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.iojbl.cn/Article/details/gtukdcxics.html

[F12] CSV 读写
来源：http://dali.ehwqpu.com/Article/details/gtacxdkexc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shangyingyoupin.top/Article/details/gtxgpjybtz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenjidiqi.icu/Article/details/gtloabamgj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shangyingyoupin.top/Article/details/gtystebirj.html

TS:   // 同上
来源：http://dali.fzhhl.top/Article/details/gtfnobwfzs.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cashguo.top/Article/details/gtrffyskcl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgpsjyev.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yanxiufei.cn/Article/details/gtekmavzps.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xylfe.cn/Article/details/gtldphhqjm.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtropknbxu.html

G. 面向对象
来源：http://dali.hysaishi.cn/Article/details/gtmremkina.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtidvsraea.html

[G01] 定义类
来源：http://dali.hnqzz.top/Article/details/gtfmlxkzbz.html

Py:   class User: pass
来源：http://dali.sufxvd.cn/Article/details/gtjswqwpln.html

PHP:  class User {}
来源：http://dali.pycfn.com/Article/details/gtogbvavnt.html

JS:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gtwilqrdut.html

TS:   class User { name: string = ""; }
来源：http://dali.dashuyun.cn/Article/details/gtmrqamhxc.html

Java: class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtuqdhezey.html

Go:   type User struct { Name string }
来源：http://dali.zdqjudy.top/Article/details/gtfdhjsgts.html

Ruby: class User; end
来源：http://dali.smart0.xyz/Article/details/gtmhutpkpm.html

C#:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gtbxnprxrw.html

[G02] 构造函数
来源：http://dali.sweek.top/Article/details/gtdnyycfzi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zdqjudy.top/Article/details/gtvrycukxr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fengsongda.top/Article/details/gtofmvqsnv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gtkczgssom.html

TS:   constructor(public name: string) {}
来源：http://dali.kuanghao11.cn/Article/details/gtfavkpvwh.html

Java: User(String name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gtwnzfhyjm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hywenlv.cn/Article/details/gtzfdpmjab.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.andypj.xyz/Article/details/gtfbwtxeog.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hammf.cn/Article/details/gtzgnwjqjw.html

[G03] 实例属性
来源：http://dali.zhongyouzk.top/Article/details/gtbrccdeek.html

Py:   self.name = "x"
来源：http://dali.xylfe.cn/Article/details/gtbqdalhgw.html

PHP:  public string $name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gttjmtrtte.html

JS:   this.name = "x";
来源：http://dali.daria6918.cn/Article/details/gtognuzxed.html

TS:   name: string = "x";
来源：http://dali.yangfankeji.com/Article/details/gttvizojrn.html

Java: private String name;
来源：http://dali.sxryk.cn/Article/details/gtmephmepr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gaohongyu789.top/Article/details/gthlivjidz.html

Ruby: @name = "x"
来源：http://dali.dashuyun.cn/Article/details/gtabkwbcne.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.bjfxy.top/Article/details/gtpcvaetxq.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gttfdaxzlk.html

Py:   def greet(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gtnyjiqsyb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gtdqantvhd.html

JS:   greet() { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtbflmxpoa.html

TS:   greet(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtjsnbiztg.html

Java: String greet() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtstubussp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtsujtcmkv.html

Ruby: def greet; @name; end
来源：http://dali.zhengqikj.top/Article/details/gtvqhtraec.html

C#:   public string Greet() => Name;
来源：http://dali.gzhubu.top/Article/details/gtzvzqvwzg.html

[G05] 继承
来源：http://dali.hfpthk.cn/Article/details/gtqlrkkcdq.html

Py:   class Admin(User): pass
来源：http://dali.jinqigufen.top/Article/details/gtqkgfazls.html

PHP:  class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtirgngzzd.html

JS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gttztiwmxl.html

TS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtkgffkpxm.html

Java: class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtspumbvas.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgfzy.top/Article/details/gtpjjagjkn.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzxudbje.html

C#:   class Admin : User {}
来源：http://dali.hammf.cn/Article/details/gttigjfkgo.html

[G06] 重写方法
来源：http://dali.daria6918.cn/Article/details/gtdewdwoew.html

Py:   def greet(self): return "admin"
来源：http://dali.jqgfzy.top/Article/details/gtbeqshkvz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtnxkobfaz.html

JS:   greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtsvcrudgz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtnicbsnix.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtpihsyztf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xinyue.icu/Article/details/gtdzgjysan.html

Ruby: def greet; "admin"; end
来源：http://dali.chenlongwang.top/Article/details/gtdjktybzy.html

C#:   public override string Greet() => "admin";
来源：http://dali.ppjwa.cn/Article/details/gtjvidmipo.html

[G07] 调用父类方法
来源：http://dali.fzhhl.top/Article/details/gtiyfhnujn.html

Py:   super().greet()
来源：http://dali.jqgfzy.top/Article/details/gtxqiyqqif.html

PHP:  parent::greet();
来源：http://dali.xziqi.cn/Article/details/gtvfynybyr.html

JS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtfbyqoymp.html

TS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gtmuolpvro.html

Java: super.greet();
来源：http://dali.hysaishi.cn/Article/details/gtyuribxux.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daria6918.cn/Article/details/gtkgyqeuaj.html

Ruby: super
来源：http://dali.xylfe.cn/Article/details/gtrksueulu.html

C#:   base.Greet();
来源：http://dali.meibo888.top/Article/details/gthbipzjnn.html

[G08] 静态方法与属性
来源：http://dali.ehwqpu.com/Article/details/gtovasykmd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj20258888.top/Article/details/gtnhqaysww.html

PHP:  public static function f() {}
来源：http://dali.yuxming.cn/Article/details/gtxtvrteds.html

JS:   static f() {}
来源：http://dali.yanxiufei.cn/Article/details/gtglyleukn.html

TS:   static f(): void {}
来源：http://dali.tianlin.xyz/Article/details/gtudwjnnaj.html

Java: static void f() {}
来源：http://dali.yanxiufei.cn/Article/details/gtjatwghlr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangdashe.top/Article/details/gthfyfjjmn.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gtxgtcfgve.html

C#:   public static void F() {}
来源：http://dali.aizwys.cn/Article/details/gtdoqqwrhk.html

[G09] 接口 / 抽象类
来源：http://dali.ybcxt.top/Article/details/gtwiddzjau.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hongshengwenyu.top/Article/details/gtwrrnying.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zdqjudy.top/Article/details/gtbalvugqx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xinyue.icu/Article/details/gtzoxyhikk.html

TS:   interface Shape { area(): number; }
来源：http://dali.havefunace.top/Article/details/gtwescsmht.html

Java: interface Shape { double area(); }
来源：http://dali.yonumen.top/Article/details/gtrivzmwsw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuetiantiany.cn/Article/details/gtehcwfwpa.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gogol.net.cn/Article/details/gtnjrijejr.html

C#:   interface IShape { double Area(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtjamgfccn.html

[G10] 访问控制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvnlshuu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jqgufenzy.top/Article/details/gtvxsxviek.html

PHP:  public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtuihculma.html

JS:   #private 字段；其余公开
来源：http://dali.jyoumei.cn/Article/details/gtaboxaybo.html

TS:   public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtoxpgdomr.html

Java: public / protected / private / 默认包级
来源：http://dali.yvedp.cn/Article/details/gtnejfuobo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfgsjire.html

Ruby: public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gtqatbpafy.html

C#:   public / protected / private / internal
来源：http://dali.zhongyouzk.top/Article/details/gtxxablhuy.html

[G11] getter / setter
来源：http://dali.tian-w.cn/Article/details/gtogotpnrp.html

Py:   @property 与 @x.setter
来源：http://dali.redwolf501.top/Article/details/gtsmljvkuj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrgeopvx.html

JS:   get name() { return this._name; }
来源：http://dali.snrcjt.cn/Article/details/gtzpzbvgyi.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gtbwophwas.html

Java: public String getName() { return name; }
来源：http://dali.jianghu66.top/Article/details/gtemfmdfiz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gtkvglhbls.html

Ruby: attr_accessor :name
来源：http://dali.ydzc1.top/Article/details/gtvuvwapzs.html

C#:   public string Name { get; set; }
来源：http://dali.hnxiangtu.top/Article/details/gtbqbwoslg.html

[G12] 对象转字符串
来源：http://dali.yj202588.top/Article/details/gtpjvkfxfx.html

Py:   def __str__(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gtrqnkojss.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtfwjvwarp.html

JS:   toString() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtxchiywbr.html

TS:   toString(): string { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtyssaqdyx.html

Java: @Override public String toString() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtioqkgron.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gtlnqsdkhr.html

Ruby: def to_s; @name; end
来源：http://dali.yuanzhike.top/Article/details/gtvbedblvt.html

C#:   public override string ToString() => Name;
来源：http://dali.9152youxi.cn/Article/details/gtuzfkmnlu.html

[G13] 判断对象类型
来源：http://dali.kuanghao11.cn/Article/details/gtofcvbkpm.html

Py:   isinstance(u, User)
来源：http://dali.chenjidiqi.icu/Article/details/gtvjukmkdl.html

PHP:  $u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtekqibkvt.html

JS:   u instanceof User
来源：http://dali.ybcxt.top/Article/details/gthellxeqb.html

TS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtgtjbjusb.html

Java: u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtjbnhnspv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ivvv.top/Article/details/gtbtwasmnb.html

Ruby: u.is_a?(User)
来源：http://dali.cheryme.top/Article/details/gtvluoscql.html

C#:   u is User
来源：http://dali.c1oappe.top/Article/details/gtcyogjysy.html

[G14] 数据类 / record
来源：http://dali.aibaodan.cn/Article/details/gtudprkcod.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpohdxrac.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenjidiqi.icu/Article/details/gtpqvlviqm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.birdmap.top/Article/details/gtznvppwot.html

TS:   type User = { name: string; age: number };
来源：http://dali.yonumen.top/Article/details/gttfntziyq.html

Java: record User(String name, int age) {}
来源：http://dali.yvedp.cn/Article/details/gtowfmbnga.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yuxming.cn/Article/details/gtybxppfey.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnqzz.top/Article/details/gtmfmdpqnq.html

C#:   record User(string Name, int Age);
来源：http://dali.aibaodan.cn/Article/details/gtsjgqqyxn.html

[G15] 枚举
来源：http://dali.yueranfly.top/Article/details/gthtrbdzgv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinqigufen.top/Article/details/gtwdhjtbsu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.haohaochexian.top/Article/details/gtdsrjxywu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cheryme.top/Article/details/gtqyjwxbfe.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gtcpswonhf.html

Java: enum Color { RED, GREEN }
来源：http://dali.yangfankeji.com/Article/details/gtebkshtdg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ybcxt.top/Article/details/gtbygpixwo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.birdmap.top/Article/details/gtazxmtshx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxinkj.top/Article/details/gtbdmhoyli.html

[G16] 对象转数组 / 字典
来源：http://dali.fengsongda.top/Article/details/gtpawnmiup.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tian-w.cn/Article/details/gtlcuaqyxm.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgufenzy.top/Article/details/gtsoqilmog.html

JS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gteulqhpiv.html

TS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gtsmgifdyh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.bjfxy.top/Article/details/gthrsfgdrg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenlongwang.top/Article/details/gtrqoyhscp.html

Ruby: obj.instance_variables
来源：http://dali.c1oappe.top/Article/details/gturagvodl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gtpsnaflrh.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtukwkjpqa.html


<!-- 参考信息 -->