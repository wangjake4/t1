代发 wailian999

[E18] 模板占位符替换
来源：http://dali.zhiwuduotai.top/Article/details/gtvvdzhsrk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yangfankeji.com/Article/details/gtskpcbeij.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sufxvd.cn/Article/details/gtovdfuxzp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gtxphajyvx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtjkswsmvb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.havefunace.top/Article/details/gtrweiipyd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtxmchzceg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jqgufenzy.top/Article/details/gtiprdihnb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.kuanghao11.cn/Article/details/gtublouwby.html

[E19] 多行文本按行拆分
来源：http://dali.mhx1999.top/Article/details/gtfqfjuscz.html

Py:   s.splitlines()
来源：http://dali.cashguo.top/Article/details/gtiuxzvfxf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xinyue.icu/Article/details/gtzzcvuzfm.html

JS:   s.split(/\r?\n/)
来源：http://dali.bjfxy.top/Article/details/gtzntrpxlr.html

TS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gtfblrdfyj.html

Java: s.lines().toList()
来源：http://dali.cheryme.top/Article/details/gtqoncwfky.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfomqjkoj.html

Ruby: s.lines
来源：http://dali.havefunace.top/Article/details/gttoywxsin.html

C#:   s.Split('\n')
来源：http://dali.sysykeji.top/Article/details/gtrzwxukde.html

[E20] 判断字符串是否为空
来源：http://dali.birdmap.top/Article/details/gtxwcxxrco.html

Py:   if not s:
来源：http://dali.zdqjudy.top/Article/details/gtbzgtaljv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yangfankeji.com/Article/details/gthjjytcrn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.316326.xyz/Article/details/gtrsyinxtn.html

TS:   if (s === "") {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepvcxzff.html

Java: if (s.isEmpty()) {}
来源：http://dali.cqqwz.cn/Article/details/gtqklukgps.html

Go:   if s == "" {}
来源：http://dali.gzhubu.top/Article/details/gtwfmdkoqm.html

Ruby: if s.empty?
来源：http://dali.jinghuilouyu.cn/Article/details/gtajjyeyrp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xuanzx.com/Article/details/gtfaxlhpjs.html

[E21] 超长截断加省略号
来源：http://dali.guowangkeji.top/Article/details/gtvtevdfgh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sufxvd.cn/Article/details/gtuanluyck.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtnrqjqhfn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtzycckppe.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtrvdshrci.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtuufpqnyu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zycfv.cn/Article/details/gtbqfeexpv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtvqcdkfmn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtwmlhxajo.html

[E22] 字节长度与字符长度
来源：http://dali.zhiwuduotai.top/Article/details/gtgcragxfj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nanxuanxn.top/Article/details/gtluohuplr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gtlspxxfgz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shuidangran.top/Article/details/gtomjfmfjh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aizwys.cn/Article/details/gtydjhdksl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jiagoushi.top/Article/details/gtryqiwpck.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxuanxn.top/Article/details/gtlnezkfux.html

Ruby: s.bytesize;  s.length
来源：http://dali.havefunace.top/Article/details/gtsebvwtse.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nanxuanxn.top/Article/details/gtwkfvblis.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtpqfyhmpn.html

F. 文件与目录
来源：http://dali.hnqzz.top/Article/details/gtvikcrxto.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtwydkhxng.html

[F01] 读取整个文件
来源：http://dali.yuxming.cn/Article/details/gtixapovcs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ivvv.top/Article/details/gtjpjmppmc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtycgrcbtq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.daxiang520.top/Article/details/gtkfjpamrj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gtmaorhher.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtgqtiqzlb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj20258888.top/Article/details/gthawvwvjy.html

Ruby: File.read("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtczdycgzn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtpkykaivf.html

[F02] 逐行读取文件
来源：http://dali.daxiang520.top/Article/details/gtoicdseoy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yuanzhike.top/Article/details/gtcmrouvtu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.svipenyu.cn/Article/details/gtcvnpcnta.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxtyhnitr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuanzhike.top/Article/details/gthcrpnffx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj20258888.top/Article/details/gthngsfgog.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jyoumei.cn/Article/details/gtpvgbsxdx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cqqwz.cn/Article/details/gtfijiwliu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.meibo888.top/Article/details/gtcrculitn.html

[F03] 写入文件（覆盖）
来源：http://dali.pengpengdd.cyou/Article/details/gtgtgjmmuj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.iojbl.cn/Article/details/gtjnomvijc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sxryk.cn/Article/details/gtdthlpnci.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gthprhhwxs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gthejykmvx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj20258.top/Article/details/gtcpqlgvkl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.birdmap.top/Article/details/gtvtcxtdyf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigfzy.top/Article/details/gtotrxtpsj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xylfe.cn/Article/details/gtvzgmrnzt.html

[F04] 追加写入文件
来源：http://dali.c1oappe.top/Article/details/gtprdgxovk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.bjfxy.top/Article/details/gtwfnlptzb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sysykeji.top/Article/details/gtbhvojtyq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gtxxgcblex.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtzdjndlhh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ehwqpu.com/Article/details/gtmaktoonp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.snrcjt.cn/Article/details/gtzzhqhnia.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhixingplan.top/Article/details/gtfpzpvxwy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nanxuanxn.top/Article/details/gtonxchgdh.html

[F05] 判断文件或目录是否存在
来源：http://dali.jlsjyb.cn/Article/details/gtkadbhfpe.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fzhhl.top/Article/details/gtvkqwonff.html

PHP:  file_exists("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtzkmrvumh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtzszjojml.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtixefrnak.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkosrwmlg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ydzc1.top/Article/details/gtplgxskyv.html

Ruby: File.exist?("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtasvqrlsk.html

C#:   File.Exists("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtssguttde.html

[F06] 删除文件
来源：http://dali.zhongyouzk.top/Article/details/gtzoojadpj.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtloyowgaa.html

PHP:  unlink("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtdvsnbqia.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtrltcloll.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gtstonvjyw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtptddapbv.html

Go:   os.Remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtzjybbmft.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gttjsgptxw.html

C#:   File.Delete("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteaiyhzdv.html

[F07] 创建目录（含多级）
来源：http://dali.hnxiangtu.top/Article/details/gtpeziysen.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jyoumei.cn/Article/details/gtsownmfqt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hnxiangtu.top/Article/details/gtjdilkegr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.haohaochexian.top/Article/details/gtnbebyuoi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gtwdcqsasy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhengqikj.top/Article/details/gtfoivrhsp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gaohongyu789.top/Article/details/gtieouuffd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jyoumei.cn/Article/details/gtnaqjdsju.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gtbzpfhpqr.html

[F08] 遍历目录
来源：http://dali.zhixingplan.top/Article/details/gtqhenszgu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guannengcc.top/Article/details/gtmoegngms.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkkovjhpp.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj20258888.top/Article/details/gtsebskfnq.html

TS:   fs.readdirSync("dir")
来源：http://dali.aizwys.cn/Article/details/gtkwymjdkp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtupvnfvjd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.havefunace.top/Article/details/gtwfmxadbf.html

Ruby: Dir.children("dir")
来源：http://dali.zdqjudy.top/Article/details/gtggwwfwef.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtmwuxjnkc.html

[F09] 获取文件大小
来源：http://dali.cdnleiting.top/Article/details/gttlkirqtc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtlzaqoawb.html

PHP:  filesize("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtkydemfhq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtibvbifnr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gtuxvyhowg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gtoxtzjami.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj20258888.top/Article/details/gtgkujyvbn.html

Ruby: File.size("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtktyxgynq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.redwolf501.top/Article/details/gtavqbvntx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigufen.top/Article/details/gtjulmylmq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtiktdeocv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sweek.top/Article/details/gtrlamlutp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtvdxisvec.html

TS:   path.extname("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtyfoauyvs.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ybcxt.top/Article/details/gtpwoevnns.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtgqgkfvkd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtofyfhixk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtjelmfoed.html

[F11] 复制与移动文件
来源：http://dali.jinqigfzy.top/Article/details/gtytzwoayn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtohpgddjv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj20258.top/Article/details/gtouaezlmr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtastdaufe.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtyazjewxs.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nwbrower.top/Article/details/gtsrnimgxr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tian-w.cn/Article/details/gtfijrdkjr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtixcccubm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cheryme.top/Article/details/gtmpowmxde.html

[F12] CSV 读写
来源：http://dali.gotoacloud.top/Article/details/gtgaggqrva.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.fengsongda.top/Article/details/gtzlwdqhba.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gzhubu.top/Article/details/gthyeeyims.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhiwuduotai.top/Article/details/gtlsnxwove.html

TS:   // 同上
来源：http://dali.jinqigfzy.top/Article/details/gtkvnlyvur.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.aizwys.cn/Article/details/gtnwpbjall.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoiwwzsqq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangshuangyany.cn/Article/details/gtxtijkizz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangshuangyany.cn/Article/details/gtytnalfjv.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtvjogyauw.html

G. 面向对象
来源：http://dali.nanxuanxn.top/Article/details/gtpckopafi.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtvwffyrre.html

[G01] 定义类
来源：http://dali.bjfxy.top/Article/details/gtbclipedi.html

Py:   class User: pass
来源：http://dali.jinghuilouyu.cn/Article/details/gteulhfume.html

PHP:  class User {}
来源：http://dali.fzhhl.top/Article/details/gtmganqpru.html

JS:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gtjrilzcpz.html

TS:   class User { name: string = ""; }
来源：http://dali.jianghu66.top/Article/details/gtjdwcuyvk.html

Java: class User {}
来源：http://dali.jinqigufen.top/Article/details/gtazguroah.html

Go:   type User struct { Name string }
来源：http://dali.andypj.xyz/Article/details/gtgsidobfj.html

Ruby: class User; end
来源：http://dali.jlsjyb.cn/Article/details/gtjlfmntht.html

C#:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gtiyvcihzt.html

[G02] 构造函数
来源：http://dali.sufxvd.cn/Article/details/gtoilpuevq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nwbrower.top/Article/details/gtaoyixgoq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhongyouzk.top/Article/details/gtperkhnyz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yongpay.top/Article/details/gtpegkjtji.html

TS:   constructor(public name: string) {}
来源：http://dali.aibaodan.cn/Article/details/gtpnpbvyrl.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gtxpvvbxjh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.andypj.xyz/Article/details/gtpdpoweiw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtutjmnbmu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aizwys.cn/Article/details/gtrbwxafqv.html

[G03] 实例属性
来源：http://dali.0kj1m.cn/Article/details/gtmyazcvjb.html

Py:   self.name = "x"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpcoxurqi.html

PHP:  public string $name = "x";
来源：http://dali.cucudq.cn/Article/details/gtzwdwnvjo.html

JS:   this.name = "x";
来源：http://dali.hywenlv.cn/Article/details/gtnxttfiwq.html

TS:   name: string = "x";
来源：http://dali.yueranfly.top/Article/details/gtcblbajgq.html

Java: private String name;
来源：http://dali.yueranfly.top/Article/details/gtjlmramoa.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigfzy.top/Article/details/gtpuqmbeqs.html

Ruby: @name = "x"
来源：http://dali.gzhubu.top/Article/details/gtnelwlmbi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtqcajaert.html

[G04] 定义方法
来源：http://dali.chenlongwang.top/Article/details/gtdmwvvzny.html

Py:   def greet(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gtceimcxtg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtqrscdapt.html

JS:   greet() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtupovfptb.html

TS:   greet(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtaqhgbhuz.html

Java: String greet() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtxrrcuyns.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtqlcdahqc.html

Ruby: def greet; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjplgskjg.html

C#:   public string Greet() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gtxveewnyj.html

[G05] 继承
来源：http://dali.iojbl.cn/Article/details/gtzarjmsbs.html

Py:   class Admin(User): pass
来源：http://dali.cheryme.top/Article/details/gttlzqiaiz.html

PHP:  class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtjcehgvrv.html

JS:   class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtskpmofkk.html

TS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtkpeufofy.html

Java: class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtytzjixtv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guowangkeji.top/Article/details/gtffooesiy.html

Ruby: class Admin < User; end
来源：http://dali.hongshengwenyu.top/Article/details/gtdkcirznk.html

C#:   class Admin : User {}
来源：http://dali.ydzc1.top/Article/details/gtffekhnnz.html

[G06] 重写方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgxrayzff.html

Py:   def greet(self): return "admin"
来源：http://dali.hysaishi.cn/Article/details/gtzviealhv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsaeeeinp.html

JS:   greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtdvbewkjg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtgdwzpcln.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtfnodvauh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgufenzy.top/Article/details/gtqkrkzpae.html

Ruby: def greet; "admin"; end
来源：http://dali.zhongyouzk.top/Article/details/gtyrnavrcn.html

C#:   public override string Greet() => "admin";
来源：http://dali.316326.xyz/Article/details/gtkrrzewnh.html

[G07] 调用父类方法
来源：http://dali.svipenyu.cn/Article/details/gthyjajtic.html

Py:   super().greet()
来源：http://dali.chenzaomai.com/Article/details/gtmjvuplsn.html

PHP:  parent::greet();
来源：http://dali.cucudq.cn/Article/details/gtirzewcoe.html

JS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gtjqevltjj.html

TS:   super.greet();
来源：http://dali.haohaochexian.top/Article/details/gtarcnhtfb.html

Java: super.greet();
来源：http://dali.316326.xyz/Article/details/gtztnnynlm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.guannengcc.top/Article/details/gtxhohanfx.html

Ruby: super
来源：http://dali.xuanzx.com/Article/details/gtgxfoiisr.html

C#:   base.Greet();
来源：http://dali.gzhubu.top/Article/details/gtyhitjwto.html

[G08] 静态方法与属性
来源：http://dali.zhixingplan.top/Article/details/gtwuowkces.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jyoumei.cn/Article/details/gtdhpziyvx.html

PHP:  public static function f() {}
来源：http://dali.gotoacloud.top/Article/details/gtbecrdxxq.html

JS:   static f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehytpyav.html

TS:   static f(): void {}
来源：http://dali.gotoacloud.top/Article/details/gtstlyvppy.html

Java: static void f() {}
来源：http://dali.dashuyun.cn/Article/details/gtzzdolygp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.smart0.xyz/Article/details/gtkzylftzo.html

Ruby: def self.f; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtqbrgolmx.html

C#:   public static void F() {}
来源：http://dali.yuanzhike.top/Article/details/gtkewuvyee.html

[G09] 接口 / 抽象类
来源：http://dali.zycfv.cn/Article/details/gtpadyafku.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.snrcjt.cn/Article/details/gtzxkpxhnp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuetiantiany.cn/Article/details/gtbvxtguhz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tian-w.cn/Article/details/gtjfdsywxo.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlimsefxb.html

Java: interface Shape { double area(); }
来源：http://dali.nwbrower.top/Article/details/gtumkcpfww.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daria6918.cn/Article/details/gtkzmhepet.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hongshengwenyu.top/Article/details/gttcrkhaxh.html

C#:   interface IShape { double Area(); }
来源：http://dali.yvedp.cn/Article/details/gtvxglnuwf.html

[G10] 访问控制
来源：http://dali.dashuyun.cn/Article/details/gtshledpqd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.mhx1999.top/Article/details/gtgyrqoinp.html

PHP:  public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gtimdnvmng.html

JS:   #private 字段；其余公开
来源：http://dali.aizwys.cn/Article/details/gtkvsgphqz.html

TS:   public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtmlbqupze.html

Java: public / protected / private / 默认包级
来源：http://dali.shangyingyoupin.top/Article/details/gthcuqzgqg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jianghu66.top/Article/details/gtxhhaxbhn.html

Ruby: public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtopiupejk.html

C#:   public / protected / private / internal
来源：http://dali.pengpengdd.cyou/Article/details/gtbvnfpvxp.html

[G11] getter / setter
来源：http://dali.hongshengwenyu.top/Article/details/gtqxqqaiqi.html

Py:   @property 与 @x.setter
来源：http://dali.cucudq.cn/Article/details/gtjefymfow.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gtnwmidylo.html

JS:   get name() { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtakzdcedx.html

TS:   get name(): string { return this._name; }
来源：http://dali.cucudq.cn/Article/details/gtzjzfpasc.html

Java: public String getName() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtkabtjmzm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gtomhbchib.html

Ruby: attr_accessor :name
来源：http://dali.hfpthk.cn/Article/details/gtmjkrojtj.html

C#:   public string Name { get; set; }
来源：http://dali.zhoulong.xyz/Article/details/gtlehcsudq.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gtybirnkzf.html

Py:   def __str__(self): return self.name
来源：http://dali.zhiwuduotai.top/Article/details/gtjbwmhvud.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gtcwdggoyf.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gthnxhgome.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtemfigmdc.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gthkejraqb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gtupiutpse.html

Ruby: def to_s; @name; end
来源：http://dali.yangfankeji.com/Article/details/gtvdeqktkw.html

C#:   public override string ToString() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gtygziizsn.html

[G13] 判断对象类型
来源：http://dali.jinqigufen.top/Article/details/gtfkuoetkw.html

Py:   isinstance(u, User)
来源：http://dali.yj202588.top/Article/details/gtmynprgkp.html

PHP:  $u instanceof User
来源：http://dali.ivvv.top/Article/details/gteqeustwk.html

JS:   u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtgjmlbces.html

TS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtkhqmgjrp.html

Java: u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtrpqpvhdq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dianchejie.cn/Article/details/gtqozfgxst.html

Ruby: u.is_a?(User)
来源：http://dali.sweek.top/Article/details/gtmiuzbnov.html

C#:   u is User
来源：http://dali.feifeiyinyue.top/Article/details/gtgxfpztjn.html

[G14] 数据类 / record
来源：http://dali.birdmap.top/Article/details/gtpnjuzzeb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjhusoll.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.svipenyu.cn/Article/details/gtdbjrhddq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhengqikj.top/Article/details/gtqythgzha.html

TS:   type User = { name: string; age: number };
来源：http://dali.smart0.xyz/Article/details/gtirecgoad.html

Java: record User(String name, int age) {}
来源：http://dali.iojbl.cn/Article/details/gttbncwrzx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.havefunace.top/Article/details/gtilbtfraq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pycfn.com/Article/details/gtcblbdhfp.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gtsywkxbjd.html

[G15] 枚举
来源：http://dali.chenlongwang.top/Article/details/gtbfkrmvxb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ybcxt.top/Article/details/gtburgxqiy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.andypj.xyz/Article/details/gtodsgidue.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sxryk.cn/Article/details/gtiloajzqd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gtwrihtqcl.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhongyouzk.top/Article/details/gtwnzbcloj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gzhubu.top/Article/details/gtjyhngswb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.redwolf501.top/Article/details/gtsyustmcd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gtpeaydfis.html

[G16] 对象转数组 / 字典
来源：http://dali.guowangkeji.top/Article/details/gtsgmsrdxe.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daxiang520.top/Article/details/gtmmwjhwdh.html

PHP:  get_object_vars($obj);
来源：http://dali.fzhhl.top/Article/details/gtzszhylti.html

JS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gtkjoopscj.html

TS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtemcqevhm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhongyouzk.top/Article/details/gttslxxnms.html


<!-- 参考信息 -->