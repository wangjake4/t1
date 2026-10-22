代发 wailian999

[E18] 模板占位符替换
来源：http://dali.svipenyu.cn/Article/details/gtettgwmvl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shangyingyoupin.top/Article/details/gtgseqoccz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttfzkugfi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gttpwfpyhv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtalwhhvqn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtfcbroxba.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yongpay.top/Article/details/gtpobjrluz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cashguo.top/Article/details/gtikfteuld.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xinyue.icu/Article/details/gtqnbdhosk.html

[E19] 多行文本按行拆分
来源：http://dali.nanxinkj.top/Article/details/gtcoxjgjyu.html

Py:   s.splitlines()
来源：http://dali.bjfxy.top/Article/details/gtyxpwuxzv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.smart0.xyz/Article/details/gttrfqnsne.html

JS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gtzusgdvtj.html

TS:   s.split(/\r?\n/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedxvunqp.html

Java: s.lines().toList()
来源：http://dali.aibaodan.cn/Article/details/gtrfuyrghs.html

Go:   strings.Split(s, "\n")
来源：http://dali.pycfn.com/Article/details/gtpjxlrgvw.html

Ruby: s.lines
来源：http://dali.hfpthk.cn/Article/details/gtdolfpafr.html

C#:   s.Split('\n')
来源：http://dali.guannengcc.top/Article/details/gtpvedsssq.html

[E20] 判断字符串是否为空
来源：http://dali.tianlin.xyz/Article/details/gtmohqfxfu.html

Py:   if not s:
来源：http://dali.nanxuanxn.top/Article/details/gtmojxdbiz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.svipenyu.cn/Article/details/gtwwuaoqvl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.9152youxi.cn/Article/details/gtswziwnvj.html

TS:   if (s === "") {}
来源：http://dali.xuetiantiany.cn/Article/details/gtydkmibxn.html

Java: if (s.isEmpty()) {}
来源：http://dali.cqqwz.cn/Article/details/gthyaihjlf.html

Go:   if s == "" {}
来源：http://dali.316326.xyz/Article/details/gtfrfregel.html

Ruby: if s.empty?
来源：http://dali.sufxvd.cn/Article/details/gtdtorrodo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.smart0.xyz/Article/details/gtcaovshzj.html

[E21] 超长截断加省略号
来源：http://dali.cucudq.cn/Article/details/gtqaxgibla.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhoulong.xyz/Article/details/gtwyfflyfb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhirqscx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtjvrmlkqx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtjkqbrjje.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtfvedzopl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yvedp.cn/Article/details/gtkmahstxu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtgiytdimt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gttyglgsfu.html

[E22] 字节长度与字符长度
来源：http://dali.xylfe.cn/Article/details/gtehzrlped.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zdqjudy.top/Article/details/gtuonfkxju.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtywanlejv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gtoerxbodg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sweek.top/Article/details/gtguljesna.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.kuanghao11.cn/Article/details/gtabkjwwjg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuanzhike.top/Article/details/gtcwjcxedk.html

Ruby: s.bytesize;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszlrdqff.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.aibaodan.cn/Article/details/gttnwmjazn.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtucihbusj.html

F. 文件与目录
来源：http://dali.fzhhl.top/Article/details/gtzgwfdwmc.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqrhxwaxh.html

[F01] 读取整个文件
来源：http://dali.jyoumei.cn/Article/details/gtygkthrdi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shzxlz.cn/Article/details/gtlgeqahlb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtdtzrybxe.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.bjfxy.top/Article/details/gtxdacpqzj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ivvv.top/Article/details/gtnciyofpd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtzqwwxjjj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nanxuanxn.top/Article/details/gtigljydid.html

Ruby: File.read("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtamuvugjq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cheryme.top/Article/details/gtkkvrhjvm.html

[F02] 逐行读取文件
来源：http://dali.shzxlz.cn/Article/details/gtahxndmhp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj20258888.top/Article/details/gtfldutbcr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gaohongyu789.top/Article/details/gtuazoapwt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258888.top/Article/details/gtjnfsrrdj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gtvnlgghxq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj202588.top/Article/details/gtuwphqynk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ybcxt.top/Article/details/gtihpnhzto.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.c1oappe.top/Article/details/gtelcxwefj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xinyue.icu/Article/details/gtvefkrgfh.html

[F03] 写入文件（覆盖）
来源：http://dali.iojbl.cn/Article/details/gtjthidbie.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hammf.cn/Article/details/gthumkbsoi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gaohongyu789.top/Article/details/gtueeqvhrm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gthlclrgqf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gthuylancj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hongshengwenyu.top/Article/details/gtkrexfupd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xziqi.cn/Article/details/gtdaxzaing.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.daria6918.cn/Article/details/gtyfufezgd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.pycfn.com/Article/details/gtanoolqsh.html

[F04] 追加写入文件
来源：http://dali.yongpay.top/Article/details/gtcjydupvh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ivvv.top/Article/details/gtevcgfnfz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.wangshuangyany.cn/Article/details/gtgeopmmvu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aibaodan.cn/Article/details/gtbghkcotx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtrahlapjb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.aizwys.cn/Article/details/gtzvlteuwq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cucudq.cn/Article/details/gtnokwgpgh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.fzhhl.top/Article/details/gtmjglgmue.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenzaomai.com/Article/details/gtfbhrtzwv.html

[F05] 判断文件或目录是否存在
来源：http://dali.iojbl.cn/Article/details/gtbyhzifxx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.quarkkingdee.top/Article/details/gtcbfchbhz.html

PHP:  file_exists("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtykolikcc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtccvtkbzc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtcdstihhw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtmftqplku.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.guannengcc.top/Article/details/gtcxotadjf.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxftrleth.html

C#:   File.Exists("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtcqixkgeh.html

[F06] 删除文件
来源：http://dali.iojbl.cn/Article/details/gtspcvsqnw.html

Py:   os.remove("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtrqvmvytc.html

PHP:  unlink("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtiqqbijsl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtimkyzfub.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtppthoaxi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvhzgcwxc.html

Go:   os.Remove("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtrfemiayt.html

Ruby: File.delete("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtwgkdahia.html

C#:   File.Delete("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtbpxrghpp.html

[F07] 创建目录（含多级）
来源：http://dali.zhoulong.xyz/Article/details/gtwxfptyrs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.havefunace.top/Article/details/gtkdpdnqyd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhengqikj.top/Article/details/gtorcbigts.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xylfe.cn/Article/details/gtjrkpcypw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gtkzkmzlgk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pengpengdd.cyou/Article/details/gthsyewcnc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.smart0.xyz/Article/details/gtdukzjoij.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwllejlge.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhoulong.xyz/Article/details/gtpsjtvenn.html

[F08] 遍历目录
来源：http://dali.yvedp.cn/Article/details/gtyjlmeuyl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.kuanghao11.cn/Article/details/gtsuxqlgtb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwjidrqwz.html

JS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gtgnfqxozz.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhbsrivp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gthjtvevsx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hfpthk.cn/Article/details/gtqikljicd.html

Ruby: Dir.children("dir")
来源：http://dali.xinyue.icu/Article/details/gtdruvesdf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtamyjrole.html

[F09] 获取文件大小
来源：http://dali.pycfn.com/Article/details/gtqfxrkolw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtkcwyioec.html

PHP:  filesize("a.txt");
来源：http://dali.bjfxy.top/Article/details/gttabydswv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhongyouzk.top/Article/details/gtvcpcrbya.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aibaodan.cn/Article/details/gtzwxdkkri.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gttajhckbs.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ppjwa.cn/Article/details/gtnugmrmqo.html

Ruby: File.size("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtjjuqkwyt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.smart0.xyz/Article/details/gtekxccqks.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.iojbl.cn/Article/details/gtwbcdruyc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtiopfzbfd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gttzfgqygn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtnavhtpaq.html

TS:   path.extname("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtpdcintfu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dashuyun.cn/Article/details/gtwymfmenv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtvytkidrc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtxpcrlupn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtmcjfcsra.html

[F11] 复制与移动文件
来源：http://dali.sysykeji.top/Article/details/gttnjvusby.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gttmvxbhjt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yuxming.cn/Article/details/gtykrjaqit.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtvicfwjmr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtrwtzbohk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gtqrrvrdhp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinghuilouyu.cn/Article/details/gtxtesjhff.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtzddiszxe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnqzz.top/Article/details/gtkpfufysj.html

[F12] CSV 读写
来源：http://dali.wangdashe.top/Article/details/gtisfgexfx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shzxlz.cn/Article/details/gtwtpniqpd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.meibo888.top/Article/details/gtlcjjegia.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtenffebuh.html

TS:   // 同上
来源：http://dali.jqgfzy.top/Article/details/gtyhnkdoeg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jianghu66.top/Article/details/gthmzymywr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.aibaodan.cn/Article/details/gtyyxgtebw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.havefunace.top/Article/details/gtianpaivc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhixingplan.top/Article/details/gttdzoeiub.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtocblmrod.html

G. 面向对象
来源：http://dali.jianghu66.top/Article/details/gtluspsvkw.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gttaeecwxp.html

[G01] 定义类
来源：http://dali.zycfv.cn/Article/details/gtajddoroq.html

Py:   class User: pass
来源：http://dali.yj20258.top/Article/details/gtftbmomye.html

PHP:  class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtexprebei.html

JS:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjgzcjpe.html

TS:   class User { name: string = ""; }
来源：http://dali.jianghu66.top/Article/details/gtwjtdxctv.html

Java: class User {}
来源：http://dali.yueranfly.top/Article/details/gtssoogxyw.html

Go:   type User struct { Name string }
来源：http://dali.smart0.xyz/Article/details/gtqvtleenb.html

Ruby: class User; end
来源：http://dali.redwolf501.top/Article/details/gtekrntsmn.html

C#:   class User {}
来源：http://dali.haohaochexian.top/Article/details/gtffynjrik.html

[G02] 构造函数
来源：http://dali.nanxinkj.top/Article/details/gtaudnoufb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.meibo888.top/Article/details/gtdevqgfmd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.9152youxi.cn/Article/details/gtudymqlmr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtneaasvdp.html

TS:   constructor(public name: string) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlepqtfco.html

Java: User(String name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtgbvhrjhc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhengqikj.top/Article/details/gtshvjerqg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cashguo.top/Article/details/gtulzpnvlx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zycfv.cn/Article/details/gteruqkkrb.html

[G03] 实例属性
来源：http://dali.snrcjt.cn/Article/details/gtkqfenojy.html

Py:   self.name = "x"
来源：http://dali.zdqjudy.top/Article/details/gthmhqiydn.html

PHP:  public string $name = "x";
来源：http://dali.zhixingplan.top/Article/details/gtwdhyhtzb.html

JS:   this.name = "x";
来源：http://dali.shuidangran.top/Article/details/gtxrhuqrzp.html

TS:   name: string = "x";
来源：http://dali.gogol.net.cn/Article/details/gtzslwdujv.html

Java: private String name;
来源：http://dali.tian-w.cn/Article/details/gtamlvxyis.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.9152youxi.cn/Article/details/gtlvqmgtlb.html

Ruby: @name = "x"
来源：http://dali.cheryme.top/Article/details/gtvbsjsiuj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.iojbl.cn/Article/details/gtakeolmsa.html

[G04] 定义方法
来源：http://dali.gotoacloud.top/Article/details/gtwikkuddw.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangtech.top/Article/details/gtblehvzck.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtxvbxtznp.html

JS:   greet() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtwzvrqcre.html

TS:   greet(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gtopxzcbbq.html

Java: String greet() { return name; }
来源：http://dali.hnqzz.top/Article/details/gtpcaaxqrx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gthydjnthf.html

Ruby: def greet; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gtgcyqvqbt.html

C#:   public string Greet() => Name;
来源：http://dali.zhengqikj.top/Article/details/gtmjvksmmm.html

[G05] 继承
来源：http://dali.zhixingplan.top/Article/details/gtseslalgj.html

Py:   class Admin(User): pass
来源：http://dali.yongpay.top/Article/details/gtswxataxu.html

PHP:  class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtbicplltc.html

JS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtpyudcuoz.html

TS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtptxxcooa.html

Java: class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtpdrrjeuw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.9152youxi.cn/Article/details/gtntzjlzzn.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtamdaibym.html

C#:   class Admin : User {}
来源：http://dali.nanxinkj.top/Article/details/gtkalggdyq.html

[G06] 重写方法
来源：http://dali.jlsjyb.cn/Article/details/gtcsbxvmii.html

Py:   def greet(self): return "admin"
来源：http://dali.tianlin.xyz/Article/details/gtardsbcfe.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtcjzikgoe.html

JS:   greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtepcjitmp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtmytmgyri.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtobewonjt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gotoacloud.top/Article/details/gtltekqhqg.html

Ruby: def greet; "admin"; end
来源：http://dali.gaohongyu789.top/Article/details/gtysnmdffc.html

C#:   public override string Greet() => "admin";
来源：http://dali.gotoacloud.top/Article/details/gtkwxaibgw.html

[G07] 调用父类方法
来源：http://dali.bjfxy.top/Article/details/gtvcgfxpwx.html

Py:   super().greet()
来源：http://dali.snrcjt.cn/Article/details/gtvnsequij.html

PHP:  parent::greet();
来源：http://dali.nwbrower.top/Article/details/gtlkdwrgus.html

JS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtrvhntevf.html

TS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gtcvenaqjs.html

Java: super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtjymbxgzf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuanzhike.top/Article/details/gtsfobfviz.html

Ruby: super
来源：http://dali.kuanghao11.cn/Article/details/gthzigffld.html

C#:   base.Greet();
来源：http://dali.havefunace.top/Article/details/gtlfvswbuc.html

[G08] 静态方法与属性
来源：http://dali.hongshengwenyu.top/Article/details/gtehmzfsss.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.iojbl.cn/Article/details/gtytrmgpch.html

PHP:  public static function f() {}
来源：http://dali.hywenlv.cn/Article/details/gtmpryurgg.html

JS:   static f() {}
来源：http://dali.jyoumei.cn/Article/details/gtuhvanaca.html

TS:   static f(): void {}
来源：http://dali.gotoacloud.top/Article/details/gtmuvnzjig.html

Java: static void f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtutrzkkic.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.c1oappe.top/Article/details/gtucwbiyaw.html

Ruby: def self.f; end
来源：http://dali.yueranfly.top/Article/details/gtneqtzfrj.html

C#:   public static void F() {}
来源：http://dali.daria6918.cn/Article/details/gteztnmhsl.html

[G09] 接口 / 抽象类
来源：http://dali.shangyingyoupin.top/Article/details/gtvhgshnte.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sxryk.cn/Article/details/gtasegcdhz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.quarkkingdee.top/Article/details/gtforkggvm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cheryme.top/Article/details/gtqqydizdl.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlcyamtzm.html

Java: interface Shape { double area(); }
来源：http://dali.cucudq.cn/Article/details/gticdvqvgc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hongshengwenyu.top/Article/details/gtbepzgeoh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhongyouzk.top/Article/details/gtjquhvzfd.html

C#:   interface IShape { double Area(); }
来源：http://dali.xuanzx.com/Article/details/gtlspejzer.html

[G10] 访问控制
来源：http://dali.pengpengdd.cyou/Article/details/gtoosserxn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ybcxt.top/Article/details/gtqnivdlbf.html

PHP:  public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gthkxehgel.html

JS:   #private 字段；其余公开
来源：http://dali.yongpay.top/Article/details/gtgvwtnswh.html

TS:   public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtscboauvl.html

Java: public / protected / private / 默认包级
来源：http://dali.havefunace.top/Article/details/gtdxaxoksz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daria6918.cn/Article/details/gtqnxyrgxg.html

Ruby: public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gtzuhlvrsz.html

C#:   public / protected / private / internal
来源：http://dali.yj20258.top/Article/details/gtkchmblcq.html

[G11] getter / setter
来源：http://dali.svipenyu.cn/Article/details/gtcmmfmyke.html

Py:   @property 与 @x.setter
来源：http://dali.svipenyu.cn/Article/details/gtnuhinacx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtnklslpuc.html

JS:   get name() { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gtylovbvrn.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtnwsgnsry.html

Java: public String getName() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtzieiwuiz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gtxepnvxmj.html

Ruby: attr_accessor :name
来源：http://dali.jqgfzy.top/Article/details/gtlubkkeqt.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqszvtqlr.html

[G12] 对象转字符串
来源：http://dali.daxiang520.top/Article/details/gtanhspapf.html

Py:   def __str__(self): return self.name
来源：http://dali.yonumen.top/Article/details/gtnmkvcksw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtnwfklsfz.html

JS:   toString() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtqehsthdh.html

TS:   toString(): string { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtmczqhpdc.html

Java: @Override public String toString() { return name; }
来源：http://dali.316326.xyz/Article/details/gthhjtcvpr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gtgldwzrgc.html

Ruby: def to_s; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gtpsnjvkfv.html

C#:   public override string ToString() => Name;
来源：http://dali.quarkkingdee.top/Article/details/gtinhykulq.html

[G13] 判断对象类型
来源：http://dali.jqgufenzy.top/Article/details/gtodyvbhad.html

Py:   isinstance(u, User)
来源：http://dali.yangfankeji.com/Article/details/gtssfbrnsy.html

PHP:  $u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtljfwazbc.html

JS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtfckxxqfv.html

TS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtcjhylukh.html

Java: u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtqgtbodpe.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.birdmap.top/Article/details/gtxopowxau.html

Ruby: u.is_a?(User)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnvfviqdm.html

C#:   u is User
来源：http://dali.nwbrower.top/Article/details/gtdivcdgto.html

[G14] 数据类 / record
来源：http://dali.wangdashe.top/Article/details/gtqvdnwkub.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hongshengwenyu.top/Article/details/gtxljjzzax.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ivvv.top/Article/details/gthfhtkrfr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yanxiufei.cn/Article/details/gtictlxhqm.html

TS:   type User = { name: string; age: number };
来源：http://dali.zdqjudy.top/Article/details/gtmhrqmcel.html

Java: record User(String name, int age) {}
来源：http://dali.dashuyun.cn/Article/details/gtmsyxqbnp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xinyue.icu/Article/details/gtsgfxhdiu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sweek.top/Article/details/gtzxlwjnwm.html

C#:   record User(string Name, int Age);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljknlmzp.html

[G15] 枚举
来源：http://dali.jqgufenzy.top/Article/details/gtddjnyjpv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fzhhl.top/Article/details/gtuywfldgk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuxming.cn/Article/details/gtpttuyetj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258888.top/Article/details/gtzpfmorqz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtthvkimfx.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgfzy.top/Article/details/gtewpmsayg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sysykeji.top/Article/details/gtwcfqijik.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj20258888.top/Article/details/gtdndhibdh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gtswuzgyxc.html

[G16] 对象转数组 / 字典
来源：http://dali.sufxvd.cn/Article/details/gttvjpptks.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenlongwang.top/Article/details/gthrwibfos.html

PHP:  get_object_vars($obj);
来源：http://dali.aibaodan.cn/Article/details/gtxprxatll.html

JS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhpoornw.html

TS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gthlcndzjk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yueranfly.top/Article/details/gtqhaecgxp.html


<!-- 参考信息 -->