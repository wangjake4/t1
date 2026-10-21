代发 wailian999

[E18] 模板占位符替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqxeskli.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gzhubu.top/Article/details/gtnsnlvbum.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ydzc1.top/Article/details/gtbalxauan.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtymrgwhsh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtrtxzvosz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtihtsqgjm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtnivugxwj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfpcromn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yongpay.top/Article/details/gtgsbgepmc.html

[E19] 多行文本按行拆分
来源：http://dali.hysaishi.cn/Article/details/gtmjoxpaix.html

Py:   s.splitlines()
来源：http://dali.mhx1999.top/Article/details/gtnpsyevrj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yvedp.cn/Article/details/gtoqgzgqsk.html

JS:   s.split(/\r?\n/)
来源：http://dali.guannengcc.top/Article/details/gtorbrfmmw.html

TS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gtxugvyrar.html

Java: s.lines().toList()
来源：http://dali.fengsongda.top/Article/details/gtclvbuhmw.html

Go:   strings.Split(s, "\n")
来源：http://dali.c1oappe.top/Article/details/gtjxceetky.html

Ruby: s.lines
来源：http://dali.jyoumei.cn/Article/details/gttmwbhvvb.html

C#:   s.Split('\n')
来源：http://dali.redwolf501.top/Article/details/gtztswbytp.html

[E20] 判断字符串是否为空
来源：http://dali.xuanzx.com/Article/details/gtxaketcyb.html

Py:   if not s:
来源：http://dali.zhiwuduotai.top/Article/details/gtbkoxzguv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fengsongda.top/Article/details/gtgvsxkqud.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.andypj.xyz/Article/details/gtktxjllej.html

TS:   if (s === "") {}
来源：http://dali.zycfv.cn/Article/details/gtxumdauxf.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj20258.top/Article/details/gtfdctpzbx.html

Go:   if s == "" {}
来源：http://dali.xziqi.cn/Article/details/gtcidjgewf.html

Ruby: if s.empty?
来源：http://dali.hongshengwenyu.top/Article/details/gtqsxxvkfs.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aizwys.cn/Article/details/gtgixpdaft.html

[E21] 超长截断加省略号
来源：http://dali.yuxming.cn/Article/details/gtsfsunoiq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.birdmap.top/Article/details/gtyacebyfg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gtgmcclbkf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfxmixuk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtykhyfwjc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtwrcucoec.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yueranfly.top/Article/details/gtsttfjfon.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtlyaellle.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtwgdwmxnw.html

[E22] 字节长度与字符长度
来源：http://dali.hfpthk.cn/Article/details/gtjcrajpal.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yanxiufei.cn/Article/details/gtxcgvpgkh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtxhhknozf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sxryk.cn/Article/details/gtjxvqurmk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cqqwz.cn/Article/details/gtdozntwip.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.snrcjt.cn/Article/details/gtoqeokurn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.mhx1999.top/Article/details/gtgbuzmbob.html

Ruby: s.bytesize;  s.length
来源：http://dali.daxiang520.top/Article/details/gthzbeqwff.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xziqi.cn/Article/details/gtmdumgqlj.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtrqtcwqdw.html

F. 文件与目录
来源：http://dali.c1oappe.top/Article/details/gtuwtlbpso.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtewdbxgfw.html

[F01] 读取整个文件
来源：http://dali.hongshengwenyu.top/Article/details/gtdilzwxnj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.iojbl.cn/Article/details/gttxidokbp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hammf.cn/Article/details/gtbiogwakz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dashuyun.cn/Article/details/gtucjzeozm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hnqzz.top/Article/details/gtsonmfntp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gtuafxrysq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.0kj1m.cn/Article/details/gtwasvaaqq.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbqqimvbg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtlkubtumf.html

[F02] 逐行读取文件
来源：http://dali.sweek.top/Article/details/gtaduozcya.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ivvv.top/Article/details/gtbiveijmz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nwbrower.top/Article/details/gtgjaufefz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.havefunace.top/Article/details/gtkmxhfdix.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tianlin.xyz/Article/details/gtlyzbuyvt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gtlxewbkam.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sxryk.cn/Article/details/gtqiticopu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.9152youxi.cn/Article/details/gtnztwiril.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hongshengwenyu.top/Article/details/gtvbjdwnzp.html

[F03] 写入文件（覆盖）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtshtxunqj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yongpay.top/Article/details/gtwwzkhpxe.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gtafmfsvgk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkrhpbbhq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yvedp.cn/Article/details/gtyywbxufs.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.vqdsnc.cn/Article/details/gteibvobit.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigfzy.top/Article/details/gtepkjmefj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.fzhhl.top/Article/details/gtdnpjdfhl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sufxvd.cn/Article/details/gtmyjtdclt.html

[F04] 追加写入文件
来源：http://dali.daria6918.cn/Article/details/gtdhoircib.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aibaodan.cn/Article/details/gtuutortgu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.guowangkeji.top/Article/details/gttiddyoge.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gtlfqpuiwq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtvkmotikb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hysaishi.cn/Article/details/gtvgckmkxg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hysaishi.cn/Article/details/gttajkbxog.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gogol.net.cn/Article/details/gtennhbysr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.c1oappe.top/Article/details/gtkrpbcpgf.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjatzkdx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.wangshuangyany.cn/Article/details/gtuxtwgvmb.html

PHP:  file_exists("a.txt");
来源：http://dali.yonumen.top/Article/details/gtihhpznry.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtkpynbcfo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtwxpocfnt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gtfgthopqt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqzbxzody.html

Ruby: File.exist?("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtbcihwrad.html

C#:   File.Exists("a.txt")
来源：http://dali.havefunace.top/Article/details/gtjsucvuee.html

[F06] 删除文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqssxuyr.html

Py:   os.remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtimezxytm.html

PHP:  unlink("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtuxkdhide.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtansyejnh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtvrnjlxar.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtsxafsgki.html

Go:   os.Remove("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtufbvhuwu.html

Ruby: File.delete("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtvtqyllvd.html

C#:   File.Delete("a.txt");
来源：http://dali.yonumen.top/Article/details/gtkniodqxf.html

[F07] 创建目录（含多级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlcbmbqpb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.quarkkingdee.top/Article/details/gtlgriustp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgfzy.top/Article/details/gteybpbiap.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guannengcc.top/Article/details/gtjkouubxl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gogol.net.cn/Article/details/gtuvgsnhac.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.feifeiyinyue.top/Article/details/gtvmunjhab.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yangfankeji.com/Article/details/gtyltbvkal.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.smart0.xyz/Article/details/gtnzcqjehn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgfzy.top/Article/details/gtxyxnrmgg.html

[F08] 遍历目录
来源：http://dali.hammf.cn/Article/details/gtssthgupu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sweek.top/Article/details/gtvcmxiorv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj20258888.top/Article/details/gtbhonztar.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrrfnrmkk.html

TS:   fs.readdirSync("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtgnxaemhf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jyoumei.cn/Article/details/gtzcarxmue.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gteudpffjr.html

Ruby: Dir.children("dir")
来源：http://dali.sweek.top/Article/details/gtzxogqisy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtaoztrfks.html

[F09] 获取文件大小
来源：http://dali.chenzaomai.com/Article/details/gtcqpesbfu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtpgvpfcwz.html

PHP:  filesize("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtkpvllbpk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.redwolf501.top/Article/details/gtrwvexsnl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gtybuyvnea.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtjrilbgyk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.daria6918.cn/Article/details/gtlttqqpbc.html

Ruby: File.size("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtzobjnubw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwitawvyi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuetiantiany.cn/Article/details/gtijsnfwkm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtxyodzjoa.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtjvdjibli.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtyqnccbev.html

TS:   path.extname("a.txt")
来源：http://dali.yueranfly.top/Article/details/gthwkochsn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangdashe.top/Article/details/gtuveyeivd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtwzapogcv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtmfgykfec.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtiuptkzkf.html

[F11] 复制与移动文件
来源：http://dali.zhixingplan.top/Article/details/gtxzpifrur.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtxmvtlpat.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtjkdmtwoy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkvbadqay.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtwckhwngx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.birdmap.top/Article/details/gtcrorokxa.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tanke756.top/Article/details/gtukdxntny.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtgwwfwykf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pengpengdd.cyou/Article/details/gtentxfrql.html

[F12] CSV 读写
来源：http://dali.dianchejie.cn/Article/details/gturjgfmcu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ybcxt.top/Article/details/gtjegwupit.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.c1oappe.top/Article/details/gtuwonalmb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ybcxt.top/Article/details/gtmxgvrqur.html

TS:   // 同上
来源：http://dali.gotoacloud.top/Article/details/gtmsbqwcng.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.feifeiyinyue.top/Article/details/gtpczyidfb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.aibaodan.cn/Article/details/gtpsnhuxee.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.birdmap.top/Article/details/gtcbmpdfql.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yanxiufei.cn/Article/details/gtxmyhxnsh.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtdbsygdfw.html

G. 面向对象
来源：http://dali.wangshuangyany.cn/Article/details/gtiafocnnt.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtzaqmjcud.html

[G01] 定义类
来源：http://dali.dashuyun.cn/Article/details/gttyxpngvf.html

Py:   class User: pass
来源：http://dali.fzhhl.top/Article/details/gtfpbrxjkw.html

PHP:  class User {}
来源：http://dali.yvedp.cn/Article/details/gtrseensne.html

JS:   class User {}
来源：http://dali.sweek.top/Article/details/gtwiyyihfb.html

TS:   class User { name: string = ""; }
来源：http://dali.yonumen.top/Article/details/gtqyhaguvj.html

Java: class User {}
来源：http://dali.jiagoushi.top/Article/details/gtgdiflwso.html

Go:   type User struct { Name string }
来源：http://dali.andypj.xyz/Article/details/gtuhvtshmd.html

Ruby: class User; end
来源：http://dali.9152youxi.cn/Article/details/gtcdrntyor.html

C#:   class User {}
来源：http://dali.gotoacloud.top/Article/details/gtrcdgragc.html

[G02] 构造函数
来源：http://dali.xuanzx.com/Article/details/gtqrqaallj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jyoumei.cn/Article/details/gtilgaixlm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuanzx.com/Article/details/gtlyklyqla.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gtzjbkmblr.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigfzy.top/Article/details/gtxnbwpccg.html

Java: User(String name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gtlvyeatit.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daria6918.cn/Article/details/gtxmqiwhdh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yanxiufei.cn/Article/details/gtworyssur.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ybcxt.top/Article/details/gtdwlwflaz.html

[G03] 实例属性
来源：http://dali.dashuyun.cn/Article/details/gtqkldglxt.html

Py:   self.name = "x"
来源：http://dali.ppjwa.cn/Article/details/gtsnjsihnr.html

PHP:  public string $name = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxhbmwwy.html

JS:   this.name = "x";
来源：http://dali.hywenlv.cn/Article/details/gtjnrpxqgn.html

TS:   name: string = "x";
来源：http://dali.gogol.net.cn/Article/details/gtgfvplnas.html

Java: private String name;
来源：http://dali.zhiwuduotai.top/Article/details/gtrlnuuehz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cashguo.top/Article/details/gtmyvvgvlj.html

Ruby: @name = "x"
来源：http://dali.aizwys.cn/Article/details/gtvhdutqwm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtwcpnihth.html

[G04] 定义方法
来源：http://dali.fzhhl.top/Article/details/gtpmoqsptg.html

Py:   def greet(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gtdkbswufz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gtatosxhid.html

JS:   greet() { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtbpfijqnj.html

TS:   greet(): string { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gttrnzczsu.html

Java: String greet() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtrlqatizo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gtcsmdkzzw.html

Ruby: def greet; @name; end
来源：http://dali.dianchejie.cn/Article/details/gtzrfvifby.html

C#:   public string Greet() => Name;
来源：http://dali.hammf.cn/Article/details/gtmcvbduzf.html

[G05] 继承
来源：http://dali.zhoulong.xyz/Article/details/gtwnrdtxhi.html

Py:   class Admin(User): pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpcwajels.html

PHP:  class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtvxxtrqtp.html

JS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtahhrpwez.html

TS:   class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtgjsvyusw.html

Java: class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtzzseapkj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgufenzy.top/Article/details/gtxsrtazdn.html

Ruby: class Admin < User; end
来源：http://dali.chenzaomai.com/Article/details/gtsrkagrqb.html

C#:   class Admin : User {}
来源：http://dali.zycfv.cn/Article/details/gtbwgilrry.html

[G06] 重写方法
来源：http://dali.redwolf501.top/Article/details/gtbqrusgsd.html

Py:   def greet(self): return "admin"
来源：http://dali.ppjwa.cn/Article/details/gtbzhanjpy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtiskcgnck.html

JS:   greet() { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtkexwwnjb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtfkkdaszn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtvduhvfag.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sxryk.cn/Article/details/gtzjyoyvpf.html

Ruby: def greet; "admin"; end
来源：http://dali.xziqi.cn/Article/details/gtmjojfupj.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxuanxn.top/Article/details/gtsxfleytp.html

[G07] 调用父类方法
来源：http://dali.gzhubu.top/Article/details/gtlmwgjyxz.html

Py:   super().greet()
来源：http://dali.jqgfzy.top/Article/details/gtghcpwsvg.html

PHP:  parent::greet();
来源：http://dali.haohaochexian.top/Article/details/gtzvnjofhj.html

JS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtrwiidjua.html

TS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtsorurqux.html

Java: super.greet();
来源：http://dali.gzhubu.top/Article/details/gtkqgurpud.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.316326.xyz/Article/details/gttuzvrfdy.html

Ruby: super
来源：http://dali.jlsjyb.cn/Article/details/gtvpyuktln.html

C#:   base.Greet();
来源：http://dali.havefunace.top/Article/details/gtwwyrmlts.html

[G08] 静态方法与属性
来源：http://dali.guannengcc.top/Article/details/gtxqpfabwv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sxryk.cn/Article/details/gtncgfwlen.html

PHP:  public static function f() {}
来源：http://dali.bjfxy.top/Article/details/gtdovsuvmx.html

JS:   static f() {}
来源：http://dali.hfpthk.cn/Article/details/gtmduufuka.html

TS:   static f(): void {}
来源：http://dali.yj20258888.top/Article/details/gtuwlsychk.html

Java: static void f() {}
来源：http://dali.cucudq.cn/Article/details/gtdblxztnl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sysykeji.top/Article/details/gtfkhucluq.html

Ruby: def self.f; end
来源：http://dali.yanxiufei.cn/Article/details/gtyobylbfz.html

C#:   public static void F() {}
来源：http://dali.dashuyun.cn/Article/details/gteehblbxk.html

[G09] 接口 / 抽象类
来源：http://dali.wangshuangyany.cn/Article/details/gtdvjclavx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daxiang520.top/Article/details/gtbtfvpntu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258888.top/Article/details/gtnuigvdqr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ppjwa.cn/Article/details/gtbwmigkra.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigufen.top/Article/details/gtwjzbjapi.html

Java: interface Shape { double area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtvalvfvtf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cdnleiting.top/Article/details/gtlzaizktf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cdnleiting.top/Article/details/gtufixwacn.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsnrmngfn.html

[G10] 访问控制
来源：http://dali.jinqigufen.top/Article/details/gtjnjzlwou.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jyoumei.cn/Article/details/gtwgvbzrgp.html

PHP:  public / protected / private
来源：http://dali.meibo888.top/Article/details/gtsaziqshz.html

JS:   #private 字段；其余公开
来源：http://dali.chenjidiqi.icu/Article/details/gtfnrkxupf.html

TS:   public / protected / private
来源：http://dali.pycfn.com/Article/details/gtxlqgekej.html

Java: public / protected / private / 默认包级
来源：http://dali.0kj1m.cn/Article/details/gtivplvgnl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yanxiufei.cn/Article/details/gtbiahtruo.html

Ruby: public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtblfagqhg.html

C#:   public / protected / private / internal
来源：http://dali.ybcxt.top/Article/details/gtydfktxil.html

[G11] getter / setter
来源：http://dali.smart0.xyz/Article/details/gtfuieywfu.html

Py:   @property 与 @x.setter
来源：http://dali.yanxiufei.cn/Article/details/gtejirqham.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtbxxutzkf.html

JS:   get name() { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gtnhbzrqfq.html

TS:   get name(): string { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gtviyagvnb.html

Java: public String getName() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtiqskwqzv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gtdzliqgwz.html

Ruby: attr_accessor :name
来源：http://dali.daria6918.cn/Article/details/gtfbllckta.html

C#:   public string Name { get; set; }
来源：http://dali.yongpay.top/Article/details/gtnypqcnfg.html

[G12] 对象转字符串
来源：http://dali.hysaishi.cn/Article/details/gtdbikhncw.html

Py:   def __str__(self): return self.name
来源：http://dali.9152youxi.cn/Article/details/gtrvertenm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtsgzxgabl.html

JS:   toString() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtelnoqeas.html

TS:   toString(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtrznolgfa.html

Java: @Override public String toString() { return name; }
来源：http://dali.hammf.cn/Article/details/gtaaozzakz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gtwnnujdbz.html

Ruby: def to_s; @name; end
来源：http://dali.shuidangran.top/Article/details/gthkbzjkeo.html

C#:   public override string ToString() => Name;
来源：http://dali.jqgfzy.top/Article/details/gtrrvmbgnm.html

[G13] 判断对象类型
来源：http://dali.hywenlv.cn/Article/details/gtiffzwfgm.html

Py:   isinstance(u, User)
来源：http://dali.fzhhl.top/Article/details/gtmuhgeqrg.html

PHP:  $u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gthshxjjth.html

JS:   u instanceof User
来源：http://dali.ybcxt.top/Article/details/gtpwximmvl.html

TS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtjdktakty.html

Java: u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtkvfqtgia.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gzhubu.top/Article/details/gtfmpedyhf.html

Ruby: u.is_a?(User)
来源：http://dali.aizwys.cn/Article/details/gtmoqjftri.html

C#:   u is User
来源：http://dali.birdmap.top/Article/details/gtbzquuwdw.html

[G14] 数据类 / record
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpgkkmiu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tianlin.xyz/Article/details/gtwftgkvdh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aizwys.cn/Article/details/gtlyyowjmz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuetiantiany.cn/Article/details/gtsbvmwund.html

TS:   type User = { name: string; age: number };
来源：http://dali.guowangkeji.top/Article/details/gtmgjczotp.html

Java: record User(String name, int age) {}
来源：http://dali.iojbl.cn/Article/details/gtjhtnidyt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hywenlv.cn/Article/details/gtlixlbpjg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.iojbl.cn/Article/details/gtiudtfmhk.html

C#:   record User(string Name, int Age);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxzrxmhoo.html

[G15] 枚举
来源：http://dali.tanke756.top/Article/details/gtkjlogkew.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cdnleiting.top/Article/details/gttcqqqgxr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zycfv.cn/Article/details/gtzxfsrjvv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jlsjyb.cn/Article/details/gtiowqdxla.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tanke756.top/Article/details/gtyjgvtvfa.html

Java: enum Color { RED, GREEN }
来源：http://dali.9152youxi.cn/Article/details/gtdkfnxssh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yueranfly.top/Article/details/gtnesomrrn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjnbcollf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtbvltluzy.html

[G16] 对象转数组 / 字典
来源：http://dali.meibo888.top/Article/details/gtfpgzjtek.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sufxvd.cn/Article/details/gteajdnjns.html

PHP:  get_object_vars($obj);
来源：http://dali.xuanzx.com/Article/details/gthuuyfkmr.html

JS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhjfxxwi.html

TS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gtrsitoowm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gotoacloud.top/Article/details/gtfgimpcxv.html


<!-- 参考信息 -->