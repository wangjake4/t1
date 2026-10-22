代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ppjwa.cn/Article/details/gtpvgtrrva.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbmsamqw.html

Ruby: s.capitalize
来源：http://dali.xziqi.cn/Article/details/gtvzzbesiw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohyzaqml.html

[E18] 模板占位符替换
来源：http://dali.tian-w.cn/Article/details/gteiukhitl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jqgufenzy.top/Article/details/gtwllcytxi.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shangyingyoupin.top/Article/details/gtpqzjnkdd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtfytitdss.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gtmexqmdtq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtrzrdeuwe.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yueranfly.top/Article/details/gthypbvhww.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xinyue.icu/Article/details/gtseqhyyxi.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hnxiangtu.top/Article/details/gtbnpjgpnz.html

[E19] 多行文本按行拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gtfoempahz.html

Py:   s.splitlines()
来源：http://dali.9152youxi.cn/Article/details/gtgeyrmthi.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj20258.top/Article/details/gtkqrwpfkq.html

JS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gtlbdxkdvw.html

TS:   s.split(/\r?\n/)
来源：http://dali.kuanghao11.cn/Article/details/gtphdkwsgz.html

Java: s.lines().toList()
来源：http://dali.sxryk.cn/Article/details/gtkmszzwcr.html

Go:   strings.Split(s, "\n")
来源：http://dali.0kj1m.cn/Article/details/gtqxdfiftg.html

Ruby: s.lines
来源：http://dali.shuidangran.top/Article/details/gtfbttklfi.html

C#:   s.Split('\n')
来源：http://dali.yongpay.top/Article/details/gtpfhvwnqm.html

[E20] 判断字符串是否为空
来源：http://dali.0kj1m.cn/Article/details/gtbpjthbdc.html

Py:   if not s:
来源：http://dali.hammf.cn/Article/details/gtswhdaanh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tianlin.xyz/Article/details/gtfslupfyv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzcdlzon.html

TS:   if (s === "") {}
来源：http://dali.jlsjyb.cn/Article/details/gteiezysge.html

Java: if (s.isEmpty()) {}
来源：http://dali.yangfankeji.com/Article/details/gtoycuamrd.html

Go:   if s == "" {}
来源：http://dali.dianchejie.cn/Article/details/gtrteyoxpa.html

Ruby: if s.empty?
来源：http://dali.xuetiantiany.cn/Article/details/gtugiwhwcn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cucudq.cn/Article/details/gtxuxnlryh.html

[E21] 超长截断加省略号
来源：http://dali.redwolf501.top/Article/details/gtnylgfwlw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tian-w.cn/Article/details/gtwucamubj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gthfitqvzi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtkfyvkrsn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtfipkudgb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtaarzqzeb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhiwuduotai.top/Article/details/gthroqbxsb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtjjszxxov.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtheaubqjp.html

[E22] 字节长度与字符长度
来源：http://dali.wangdashe.top/Article/details/gtsshpgdbu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.bjfxy.top/Article/details/gtejpeocos.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gthprqvpgb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jianghu66.top/Article/details/gtdjdeykng.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gtndhhevbe.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgcaaklkk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.0kj1m.cn/Article/details/gtdmkviiqm.html

Ruby: s.bytesize;  s.length
来源：http://dali.bjfxy.top/Article/details/gtjilbsjrb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrmoiqvb.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtmzlekobl.html

F. 文件与目录
来源：http://dali.mhx1999.top/Article/details/gtybsadkgn.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtjqzkxwhm.html

[F01] 读取整个文件
来源：http://dali.yvedp.cn/Article/details/gtfwefrfbf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jiagoushi.top/Article/details/gtfutzwyor.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtuywupumz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zycfv.cn/Article/details/gteruoikpo.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gttxusfnpx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtkcijusut.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.daxiang520.top/Article/details/gtmvoadvug.html

Ruby: File.read("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtiviffokd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtpjpfrehh.html

[F02] 逐行读取文件
来源：http://dali.mhx1999.top/Article/details/gttazwxlpi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daxiang520.top/Article/details/gtaaemgztr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhixingplan.top/Article/details/gtbjevcaxp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.havefunace.top/Article/details/gtnftrpldj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gtfplduxcl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gthmxfcsyv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cashguo.top/Article/details/gtmribnktf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj20258888.top/Article/details/gtxnfrppuh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.pycfn.com/Article/details/gtcmwbieis.html

[F03] 写入文件（覆盖）
来源：http://dali.mhx1999.top/Article/details/gtzwwyajvq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zdqjudy.top/Article/details/gtcvlssvfx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gtqgocrbkj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gtvoibebfm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yongpay.top/Article/details/gtudzqonkt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aizwys.cn/Article/details/gtuqnrmnhq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jianghu66.top/Article/details/gtwuehobss.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.aizwys.cn/Article/details/gtapkwilqy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrafpwfvl.html

[F04] 追加写入文件
来源：http://dali.sysykeji.top/Article/details/gtijwlleyc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangdashe.top/Article/details/gtloabiwjy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tanke756.top/Article/details/gtxooqdues.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xylfe.cn/Article/details/gtoxatnquk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gtizvxlaqw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.daria6918.cn/Article/details/gtdwjcfkug.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cucudq.cn/Article/details/gthoznrahe.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.pycfn.com/Article/details/gtlswpxarj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gtvgaomlhs.html

[F05] 判断文件或目录是否存在
来源：http://dali.tian-w.cn/Article/details/gtyxfxayds.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.haohaochexian.top/Article/details/gtrohgkvyz.html

PHP:  file_exists("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtukindsfa.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtsgichcrx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtajlwcrof.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtjvtkxspz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gzhubu.top/Article/details/gtvkntprwm.html

Ruby: File.exist?("a.txt")
来源：http://dali.tanke756.top/Article/details/gtrhevgkjp.html

C#:   File.Exists("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtbqdexhxp.html

[F06] 删除文件
来源：http://dali.tanke756.top/Article/details/gtfhcywkem.html

Py:   os.remove("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtvtpxiagg.html

PHP:  unlink("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrfrxioy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtcqrbzmha.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtlychmyhi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtnzzkljzb.html

Go:   os.Remove("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtnhlpgclh.html

Ruby: File.delete("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtdlopgyps.html

C#:   File.Delete("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtnnoualjj.html

[F07] 创建目录（含多级）
来源：http://dali.jiagoushi.top/Article/details/gtexcfitpx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dashuyun.cn/Article/details/gtuwtwumnk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxktzuaro.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gtngzleidn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gtuineeaec.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.wangdashe.top/Article/details/gtecgvnjqm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hnxiangtu.top/Article/details/gtzqhgxkop.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tanke756.top/Article/details/gtqhnidvhp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dashuyun.cn/Article/details/gtxpmoktbf.html

[F08] 遍历目录
来源：http://dali.yueranfly.top/Article/details/gtyqynaroq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenzaomai.com/Article/details/gtmegtvpbr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.daxiang520.top/Article/details/gttyivjigu.html

JS:   fs.readdirSync("dir")
来源：http://dali.ivvv.top/Article/details/gtzwxtfolr.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gttzdphfzi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cqqwz.cn/Article/details/gtyfhyrzdj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hfpthk.cn/Article/details/gtrmrutvpw.html

Ruby: Dir.children("dir")
来源：http://dali.sufxvd.cn/Article/details/gtjtxvglfw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtvatfqpfi.html

[F09] 获取文件大小
来源：http://dali.aibaodan.cn/Article/details/gtxqtbkmdd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtmivseekt.html

PHP:  filesize("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtslkesebg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ehwqpu.com/Article/details/gtzxijrecb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gtwdzrshtc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtzefaxtvc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gotoacloud.top/Article/details/gtzbxxrlcm.html

Ruby: File.size("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtcrvdonar.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yanxiufei.cn/Article/details/gtwovixwmi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnqzz.top/Article/details/gtubafvhhv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtfntsvfuu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtrhdyggug.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtksprcvcy.html

TS:   path.extname("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtjcpzbjze.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigufen.top/Article/details/gtaqjnuorr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtubufwitk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gthnjgjwrk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtthvqvmwj.html

[F11] 复制与移动文件
来源：http://dali.ivvv.top/Article/details/gtzitzmayr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxqzxgjz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtoamlbofz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtnqezvjqc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtjldyebvn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ivvv.top/Article/details/gtfqjgeexa.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzijcxuee.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtqlienfpo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.fzhhl.top/Article/details/gtibmujylj.html

[F12] CSV 读写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhagdzgc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrgalhcr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gtuyllqylz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvftlfqmn.html

TS:   // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gtgkilknlw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hywenlv.cn/Article/details/gtivvmrhtp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tianlin.xyz/Article/details/gtwdatknck.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yuanzhike.top/Article/details/gtuzydkboz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jyoumei.cn/Article/details/gtmsxjyzzq.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtwlmsxmka.html

G. 面向对象
来源：http://dali.9152youxi.cn/Article/details/gtxiwluarg.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtakuruxbv.html

[G01] 定义类
来源：http://dali.havefunace.top/Article/details/gtcchsfpuk.html

Py:   class User: pass
来源：http://dali.zhengqikj.top/Article/details/gtcjwmbzhi.html

PHP:  class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtliypqnbe.html

JS:   class User {}
来源：http://dali.yj202588.top/Article/details/gtyjhafoew.html

TS:   class User { name: string = ""; }
来源：http://dali.hysaishi.cn/Article/details/gtwddzatdl.html

Java: class User {}
来源：http://dali.yj20258.top/Article/details/gtubdnbgto.html

Go:   type User struct { Name string }
来源：http://dali.yueranfly.top/Article/details/gtndscqrcm.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gtjzbatfla.html

C#:   class User {}
来源：http://dali.yueranfly.top/Article/details/gtfxpmncmn.html

[G02] 构造函数
来源：http://dali.aizwys.cn/Article/details/gtqnxuupyi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ydzc1.top/Article/details/gtfbmzidwb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zycfv.cn/Article/details/gtkmdblsxt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gtvzxzoicc.html

TS:   constructor(public name: string) {}
来源：http://dali.hywenlv.cn/Article/details/gtwaseuqin.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gtufdxycyq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gaohongyu789.top/Article/details/gtytcjliyn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yonumen.top/Article/details/gtssnihqvu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cdnleiting.top/Article/details/gtweieftey.html

[G03] 实例属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkklgusz.html

Py:   self.name = "x"
来源：http://dali.nwbrower.top/Article/details/gtuskkxupu.html

PHP:  public string $name = "x";
来源：http://dali.jyoumei.cn/Article/details/gtguuckrif.html

JS:   this.name = "x";
来源：http://dali.xinyue.icu/Article/details/gtldqqdiqi.html

TS:   name: string = "x";
来源：http://dali.guowangkeji.top/Article/details/gtzsevqwnd.html

Java: private String name;
来源：http://dali.zhixingplan.top/Article/details/gtyqlhjkgc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pycfn.com/Article/details/gtdtlxhsmf.html

Ruby: @name = "x"
来源：http://dali.redwolf501.top/Article/details/gtrpkrauui.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtnznubgwo.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gtfcnyfhrm.html

Py:   def greet(self): return self.name
来源：http://dali.haohaochexian.top/Article/details/gtrfkgilxx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtzlaldxlb.html

JS:   greet() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtvbtxskwh.html

TS:   greet(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtulfznahm.html

Java: String greet() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtyybehqgs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gtldsiznkg.html

Ruby: def greet; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gtxpsueqce.html

C#:   public string Greet() => Name;
来源：http://dali.mhx1999.top/Article/details/gtfmkmyyzu.html

[G05] 继承
来源：http://dali.pengpengdd.cyou/Article/details/gtmsrhvxmt.html

Py:   class Admin(User): pass
来源：http://dali.hnqzz.top/Article/details/gtpviivbzb.html

PHP:  class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtkmqwlvjm.html

JS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtmbeitids.html

TS:   class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtpoujekjv.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtonjkvgjq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgufenzy.top/Article/details/gtsuopromm.html

Ruby: class Admin < User; end
来源：http://dali.hongshengwenyu.top/Article/details/gtkebwphus.html

C#:   class Admin : User {}
来源：http://dali.pycfn.com/Article/details/gtdzbdodyz.html

[G06] 重写方法
来源：http://dali.xziqi.cn/Article/details/gtiujyrzrc.html

Py:   def greet(self): return "admin"
来源：http://dali.hnxiangtu.top/Article/details/gttyliyhap.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtjhgofems.html

JS:   greet() { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtulxpplvi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbusdikk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtipwfucmx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jiagoushi.top/Article/details/gtibfygspl.html

Ruby: def greet; "admin"; end
来源：http://dali.zhongyouzk.top/Article/details/gtyndtfyeu.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhiwuduotai.top/Article/details/gtpweiyhms.html

[G07] 调用父类方法
来源：http://dali.andypj.xyz/Article/details/gtrzsrutcr.html

Py:   super().greet()
来源：http://dali.tian-w.cn/Article/details/gtkuhthbdq.html

PHP:  parent::greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtkolwjtef.html

JS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gtjnzqnhzp.html

TS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gtpbdhitpx.html

Java: super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtmiavefem.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhongyouzk.top/Article/details/gtkiuhapgc.html

Ruby: super
来源：http://dali.jiagoushi.top/Article/details/gtlznjecnc.html

C#:   base.Greet();
来源：http://dali.xziqi.cn/Article/details/gtkcfwhzda.html

[G08] 静态方法与属性
来源：http://dali.fengsongda.top/Article/details/gtgxxstifl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnqzz.top/Article/details/gtlsetllka.html

PHP:  public static function f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtjnsmhzpu.html

JS:   static f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gthowqtyjw.html

TS:   static f(): void {}
来源：http://dali.hfpthk.cn/Article/details/gtluvzofyx.html

Java: static void f() {}
来源：http://dali.hnqzz.top/Article/details/gtjyulocqz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.feifeiyinyue.top/Article/details/gtafyhgvvd.html

Ruby: def self.f; end
来源：http://dali.vqdsnc.cn/Article/details/gtidsddorq.html

C#:   public static void F() {}
来源：http://dali.quarkkingdee.top/Article/details/gtvdqcivfg.html

[G09] 接口 / 抽象类
来源：http://dali.jiagoushi.top/Article/details/gtbgoolsjw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jyoumei.cn/Article/details/gtsvxfklju.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.mhx1999.top/Article/details/gtwajxiaxn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.snrcjt.cn/Article/details/gtdcueubkp.html

TS:   interface Shape { area(): number; }
来源：http://dali.ybcxt.top/Article/details/gtzwinatlk.html

Java: interface Shape { double area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtobehdbqh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenjidiqi.icu/Article/details/gthavypbwr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nanxinkj.top/Article/details/gtottvclmi.html

C#:   interface IShape { double Area(); }
来源：http://dali.hysaishi.cn/Article/details/gtqtgepcmo.html

[G10] 访问控制
来源：http://dali.sweek.top/Article/details/gtjmokyaxt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenjidiqi.icu/Article/details/gtulzqokmu.html

PHP:  public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsyeiusqp.html

JS:   #private 字段；其余公开
来源：http://dali.cucudq.cn/Article/details/gtvwvekcqa.html

TS:   public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gteirjmvwy.html

Java: public / protected / private / 默认包级
来源：http://dali.gogol.net.cn/Article/details/gtuvtopyqi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xziqi.cn/Article/details/gthfxhhtit.html

Ruby: public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gtmhssohwr.html

C#:   public / protected / private / internal
来源：http://dali.nanxuanxn.top/Article/details/gtiiaueegm.html

[G11] getter / setter
来源：http://dali.jqgfzy.top/Article/details/gtfjzwumrz.html

Py:   @property 与 @x.setter
来源：http://dali.xziqi.cn/Article/details/gthyelihph.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtzxuzmtbk.html

JS:   get name() { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gtvhwomlzh.html

TS:   get name(): string { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gttbnycxjf.html

Java: public String getName() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtmxqhnqrp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gttyxailcm.html

Ruby: attr_accessor :name
来源：http://dali.gaohongyu789.top/Article/details/gtipzrstxr.html

C#:   public string Name { get; set; }
来源：http://dali.guannengcc.top/Article/details/gtmwjloixc.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedjvcwvx.html

Py:   def __str__(self): return self.name
来源：http://dali.meibo888.top/Article/details/gtlukaismn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtvudplhfp.html

JS:   toString() { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtppweblqu.html

TS:   toString(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gthslsncui.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtvihpukbl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gtdgiwldzl.html

Ruby: def to_s; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfccbnlco.html

C#:   public override string ToString() => Name;
来源：http://dali.zhengqikj.top/Article/details/gtrjsqxbgn.html

[G13] 判断对象类型
来源：http://dali.xuanzx.com/Article/details/gtnthwxvwf.html

Py:   isinstance(u, User)
来源：http://dali.haohaochexian.top/Article/details/gtrkrmopxo.html

PHP:  $u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtuqtudoaa.html

JS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtylkhviyk.html

TS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtdbbrejgs.html

Java: u instanceof User
来源：http://dali.tanke756.top/Article/details/gtrecdujbk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuxming.cn/Article/details/gtkaqqhtay.html

Ruby: u.is_a?(User)
来源：http://dali.yj202588.top/Article/details/gtjqflhrea.html

C#:   u is User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtncizinjn.html

[G14] 数据类 / record
来源：http://dali.ydzc1.top/Article/details/gttefvwxrx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shzxlz.cn/Article/details/gtdmlfxvdt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.wangdashe.top/Article/details/gtkdugiwhs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sweek.top/Article/details/gtmrpuqxao.html

TS:   type User = { name: string; age: number };
来源：http://dali.xuanzx.com/Article/details/gtrxkuygru.html

Java: record User(String name, int age) {}
来源：http://dali.gogol.net.cn/Article/details/gtpqwbugsw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jianghu66.top/Article/details/gtnxkfkedm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.iojbl.cn/Article/details/gtxcdmthil.html

C#:   record User(string Name, int Age);
来源：http://dali.hfpthk.cn/Article/details/gtltyfkynv.html

[G15] 枚举
来源：http://dali.chenlongwang.top/Article/details/gtcqzekswr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxuanxn.top/Article/details/gtckxirjwr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xziqi.cn/Article/details/gtqzntgyog.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sysykeji.top/Article/details/gtrkwjapnp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtkycmlkya.html

Java: enum Color { RED, GREEN }
来源：http://dali.zycfv.cn/Article/details/gthzodxmcf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ppjwa.cn/Article/details/gtwgnngura.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shzxlz.cn/Article/details/gtuwuycekg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gtytgmtegj.html

[G16] 对象转数组 / 字典
来源：http://dali.sweek.top/Article/details/gtnghvhpse.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxinkj.top/Article/details/gtgjenybeo.html


<!-- 参考信息 -->