代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinqigfzy.top/Article/details/gtokppkohx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinqigufen.top/Article/details/gtprhudeoq.html

Ruby: s.capitalize
来源：http://dali.nanxuanxn.top/Article/details/gtnmlmqoig.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.havefunace.top/Article/details/gtgkrkztta.html

[E18] 模板占位符替换
来源：http://dali.zhongyouzk.top/Article/details/gtokuxqchl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xziqi.cn/Article/details/gthxwwtqqo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.daxiang520.top/Article/details/gtiiynnwpf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtfevytnyo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtilxuezbo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtstjhynxr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.bjfxy.top/Article/details/gtbhrpykwt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xinyue.icu/Article/details/gtiasumubp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.c1oappe.top/Article/details/gtllcettvq.html

[E19] 多行文本按行拆分
来源：http://dali.jianghu66.top/Article/details/gtriujococ.html

Py:   s.splitlines()
来源：http://dali.chenlongwang.top/Article/details/gtesylfzoh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ydzc1.top/Article/details/gtqhuqjhvg.html

JS:   s.split(/\r?\n/)
来源：http://dali.yongpay.top/Article/details/gtlerhzyjn.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenjidiqi.icu/Article/details/gtsomcfekg.html

Java: s.lines().toList()
来源：http://dali.yanxiufei.cn/Article/details/gtkieobxyc.html

Go:   strings.Split(s, "\n")
来源：http://dali.cdnleiting.top/Article/details/gtabneywue.html

Ruby: s.lines
来源：http://dali.zhiwuduotai.top/Article/details/gtqvokctzh.html

C#:   s.Split('\n')
来源：http://dali.nanxuanxn.top/Article/details/gtrxnnfedp.html

[E20] 判断字符串是否为空
来源：http://dali.nanxinkj.top/Article/details/gtsuadwqyv.html

Py:   if not s:
来源：http://dali.yueranfly.top/Article/details/gtmkawtnbk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jqgufenzy.top/Article/details/gtxeoyhhyv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yueranfly.top/Article/details/gthqtgpesq.html

TS:   if (s === "") {}
来源：http://dali.dashuyun.cn/Article/details/gtnclnsesm.html

Java: if (s.isEmpty()) {}
来源：http://dali.jlsjyb.cn/Article/details/gtybwyocby.html

Go:   if s == "" {}
来源：http://dali.jiagoushi.top/Article/details/gtdvcghdry.html

Ruby: if s.empty?
来源：http://dali.kuanghao11.cn/Article/details/gtuwyfsmxk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtgedurqyh.html

[E21] 超长截断加省略号
来源：http://dali.xuetiantiany.cn/Article/details/gtgcgjodyk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zdqjudy.top/Article/details/gtxwhmtcbc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gtgrfdotnn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtpfjqdpii.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gtokhkmeml.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtjqvepkss.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sxryk.cn/Article/details/gtewxzxkyd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gthcfcvltv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtjujaggyp.html

[E22] 字节长度与字符长度
来源：http://dali.aibaodan.cn/Article/details/gtbjkpzxzk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtwcgokyxb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gtgqvhrqyj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtwearbnbz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gzhubu.top/Article/details/gtgbfmawrb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.fzhhl.top/Article/details/gtgajrgpbl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nwbrower.top/Article/details/gtdtnowaos.html

Ruby: s.bytesize;  s.length
来源：http://dali.hysaishi.cn/Article/details/gtvsrwulcp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yuanzhike.top/Article/details/gtlssugchl.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtrzlqutxe.html

F. 文件与目录
来源：http://dali.jqgufenzy.top/Article/details/gtnuyukmgz.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtzmhwhawf.html

[F01] 读取整个文件
来源：http://dali.316326.xyz/Article/details/gtgpolldny.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hywenlv.cn/Article/details/gtzawczzve.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtelsiwhsn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gaohongyu789.top/Article/details/gteocvhnvt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gtkpinpety.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gtmlqgkpqq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.birdmap.top/Article/details/gtadexpmbc.html

Ruby: File.read("a.txt")
来源：http://dali.yj20258.top/Article/details/gtetrfgrfh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtrggjdfwg.html

[F02] 逐行读取文件
来源：http://dali.hfpthk.cn/Article/details/gtjordjnym.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shangyingyoupin.top/Article/details/gtcyjhzupj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.redwolf501.top/Article/details/gtzenbqvoe.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.quarkkingdee.top/Article/details/gtntenloib.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ivvv.top/Article/details/gtjdvbqxte.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sweek.top/Article/details/gtngtmnupf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhongyouzk.top/Article/details/gtszuvzbmq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hongshengwenyu.top/Article/details/gtnzyxpbzz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqfxaibzr.html

[F03] 写入文件（覆盖）
来源：http://dali.c1oappe.top/Article/details/gtpsjskcgr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtshxyllnr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.snrcjt.cn/Article/details/gtjiwantjq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gtwfishcpd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gttbkxzxwq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.mhx1999.top/Article/details/gtdshsrgxn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sysykeji.top/Article/details/gtqnbamjfs.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zycfv.cn/Article/details/gtzepkaqjc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhoulong.xyz/Article/details/gtdmomkbow.html

[F04] 追加写入文件
来源：http://dali.tanke756.top/Article/details/gtrkdfxahn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtotnptewt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jlsjyb.cn/Article/details/gthhxwffgg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtawkqnoap.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yueranfly.top/Article/details/gtdtrisklc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jiagoushi.top/Article/details/gtwhxemwlp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.316326.xyz/Article/details/gtqqclueqe.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yangfankeji.com/Article/details/gtxamnxjjt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xuetiantiany.cn/Article/details/gtiecoteaw.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtehsbozup.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fengsongda.top/Article/details/gtqlbzgbiz.html

PHP:  file_exists("a.txt");
来源：http://dali.hammf.cn/Article/details/gthksfgffp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtgmszbezo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gttgehutym.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gtkskyxxih.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.feifeiyinyue.top/Article/details/gtwoxjhrid.html

Ruby: File.exist?("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtjctwrzjv.html

C#:   File.Exists("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtoocuwqep.html

[F06] 删除文件
来源：http://dali.c1oappe.top/Article/details/gtiuowdofw.html

Py:   os.remove("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtepwwqunb.html

PHP:  unlink("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtumoywtpg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtrjmirzco.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtntdvgmxf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gttmmpqxxv.html

Go:   os.Remove("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtynqddgeq.html

Ruby: File.delete("a.txt")
来源：http://dali.mhx1999.top/Article/details/gttgitquua.html

C#:   File.Delete("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtdegphqsk.html

[F07] 创建目录（含多级）
来源：http://dali.jqgfzy.top/Article/details/gtlhwbluva.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhixingplan.top/Article/details/gthcxssjzd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daxiang520.top/Article/details/gtefpsxzez.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gtrehasnvt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gtqcqjwxxd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shuidangran.top/Article/details/gtbbncrhcp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ydzc1.top/Article/details/gtsiptgico.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhixingplan.top/Article/details/gtdwtwwmlz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shanyushiyangtech.top/Article/details/gthnhwytse.html

[F08] 遍历目录
来源：http://dali.svipenyu.cn/Article/details/gtssefpopl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkeklbuj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yueranfly.top/Article/details/gthndhlole.html

JS:   fs.readdirSync("dir")
来源：http://dali.0kj1m.cn/Article/details/gtfwrcnidp.html

TS:   fs.readdirSync("dir")
来源：http://dali.xuanzx.com/Article/details/gtlaguoqyu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gtndkjvxun.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztyjfphu.html

Ruby: Dir.children("dir")
来源：http://dali.jiagoushi.top/Article/details/gtkkjsawan.html

C#:   Directory.GetFiles("dir")
来源：http://dali.andypj.xyz/Article/details/gtscfjzpmq.html

[F09] 获取文件大小
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgshvbufs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtwgzntdwf.html

PHP:  filesize("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtogtsqgcv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangtech.top/Article/details/gttocvkigu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuhakhhpk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtabdqzwew.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.316326.xyz/Article/details/gtvnfnskjp.html

Ruby: File.size("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtqfbejnhj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ehwqpu.com/Article/details/gtwykfbkat.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tanke756.top/Article/details/gthmomsngs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gturmiwmpu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cucudq.cn/Article/details/gtedvcicrx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gttuoupydm.html

TS:   path.extname("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtamkpypgl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aizwys.cn/Article/details/gthkpzbnvg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtbpaxhfft.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtyjemxken.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvwfxjub.html

[F11] 复制与移动文件
来源：http://dali.jqgufenzy.top/Article/details/gtcenlcwtc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtryfirnxo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fzhhl.top/Article/details/gtojcjfjrs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtedbudszj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gtykykwlwi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sweek.top/Article/details/gtqaetfklr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cqqwz.cn/Article/details/gtomdedlhu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtynybqect.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zdqjudy.top/Article/details/gtyagpdtji.html

[F12] CSV 读写
来源：http://dali.zdqjudy.top/Article/details/gtjkvjcsjh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sysykeji.top/Article/details/gtozwojygm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nanxinkj.top/Article/details/gtwbjqrowl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.mhx1999.top/Article/details/gtkgabwayp.html

TS:   // 同上
来源：http://dali.yj20258888.top/Article/details/gtgajujgie.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nanxuanxn.top/Article/details/gtiebpxwbz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangtech.top/Article/details/gtlnpembma.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zycfv.cn/Article/details/gtwfbmtjga.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.vqdsnc.cn/Article/details/gtvpznrgwv.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxfhdvph.html

G. 面向对象
来源：http://dali.snrcjt.cn/Article/details/gtozrlgfak.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtgiletbgv.html

[G01] 定义类
来源：http://dali.yangfankeji.com/Article/details/gtlzfvvmzp.html

Py:   class User: pass
来源：http://dali.shuidangran.top/Article/details/gtjimpkwmx.html

PHP:  class User {}
来源：http://dali.ydzc1.top/Article/details/gtbkpgiznt.html

JS:   class User {}
来源：http://dali.meibo888.top/Article/details/gtrsmlxbve.html

TS:   class User { name: string = ""; }
来源：http://dali.zhengqikj.top/Article/details/gttcndylah.html

Java: class User {}
来源：http://dali.yonumen.top/Article/details/gtvrohdcyj.html

Go:   type User struct { Name string }
来源：http://dali.yvedp.cn/Article/details/gtgponhvfc.html

Ruby: class User; end
来源：http://dali.ybcxt.top/Article/details/gtqqrazdxp.html

C#:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gtgctxzywy.html

[G02] 构造函数
来源：http://dali.gaohongyu789.top/Article/details/gtasijuovu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ppjwa.cn/Article/details/gtaqpjqzyo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagojqahm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gtigkesnmf.html

TS:   constructor(public name: string) {}
来源：http://dali.cqqwz.cn/Article/details/gtkxaheeiw.html

Java: User(String name) { this.name = name; }
来源：http://dali.fzhhl.top/Article/details/gtasjixnvh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.meibo888.top/Article/details/gtpjgajhaa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guowangkeji.top/Article/details/gtodmjheqm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tian-w.cn/Article/details/gttlbeirpq.html

[G03] 实例属性
来源：http://dali.shangyingyoupin.top/Article/details/gtqedrzoyi.html

Py:   self.name = "x"
来源：http://dali.ybcxt.top/Article/details/gtdnyzjsrj.html

PHP:  public string $name = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gthcimpaes.html

JS:   this.name = "x";
来源：http://dali.ehwqpu.com/Article/details/gtnlhwbcwm.html

TS:   name: string = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbazzdrpd.html

Java: private String name;
来源：http://dali.bjfxy.top/Article/details/gtkfzdbhek.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.fzhhl.top/Article/details/gtvgbhusfh.html

Ruby: @name = "x"
来源：http://dali.guannengcc.top/Article/details/gtqdfeozrx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cheryme.top/Article/details/gtotopvhjx.html

[G04] 定义方法
来源：http://dali.zhoulong.xyz/Article/details/gtldgfzekm.html

Py:   def greet(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gtwadmjajd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gtunxtxzyr.html

JS:   greet() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtdrtucpot.html

TS:   greet(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtsyyuhhli.html

Java: String greet() { return name; }
来源：http://dali.xylfe.cn/Article/details/gtiwhoquar.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gteiezcpcr.html

Ruby: def greet; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvqdfvxfw.html

C#:   public string Greet() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gtrusdyvju.html

[G05] 继承
来源：http://dali.yvedp.cn/Article/details/gtiewfknfx.html

Py:   class Admin(User): pass
来源：http://dali.sysykeji.top/Article/details/gtpenfzjnl.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtpijkalgz.html

JS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtkrblbhuy.html

TS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtvauseawu.html

Java: class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gthxjeyinx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxuanxn.top/Article/details/gtydcmqrgh.html

Ruby: class Admin < User; end
来源：http://dali.yuanzhike.top/Article/details/gttwejwuwl.html

C#:   class Admin : User {}
来源：http://dali.daxiang520.top/Article/details/gttsigawwm.html

[G06] 重写方法
来源：http://dali.smart0.xyz/Article/details/gtljixgplm.html

Py:   def greet(self): return "admin"
来源：http://dali.sweek.top/Article/details/gtavxoevup.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtvvheqzmc.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtumbvskow.html

TS:   greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtxkmqvdhf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gteawawnqv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.redwolf501.top/Article/details/gtykosoxxn.html

Ruby: def greet; "admin"; end
来源：http://dali.yongpay.top/Article/details/gtpnysmsjt.html

C#:   public override string Greet() => "admin";
来源：http://dali.guannengcc.top/Article/details/gtvckarozt.html

[G07] 调用父类方法
来源：http://dali.iojbl.cn/Article/details/gtvdczzudv.html

Py:   super().greet()
来源：http://dali.tianlin.xyz/Article/details/gtmrdvdwxf.html

PHP:  parent::greet();
来源：http://dali.jiagoushi.top/Article/details/gtvnzyhumb.html

JS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtxpirjkew.html

TS:   super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtjqkeizek.html

Java: super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkaxfzpyn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xinyue.icu/Article/details/gtrxisuwff.html

Ruby: super
来源：http://dali.yongpay.top/Article/details/gttsohihld.html

C#:   base.Greet();
来源：http://dali.sufxvd.cn/Article/details/gtrvstadpg.html

[G08] 静态方法与属性
来源：http://dali.shzxlz.cn/Article/details/gtivxotjep.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cheryme.top/Article/details/gtljvqfaza.html

PHP:  public static function f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtttrxrrvh.html

JS:   static f() {}
来源：http://dali.tanke756.top/Article/details/gttowacmfn.html

TS:   static f(): void {}
来源：http://dali.yj20258.top/Article/details/gtlhemqjfx.html

Java: static void f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtiwzfppzm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sweek.top/Article/details/gtpqcpvjpl.html

Ruby: def self.f; end
来源：http://dali.yueranfly.top/Article/details/gtmbyvdiso.html

C#:   public static void F() {}
来源：http://dali.yvedp.cn/Article/details/gtofnkibay.html

[G09] 接口 / 抽象类
来源：http://dali.zhiwuduotai.top/Article/details/gtcopxhciq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jiagoushi.top/Article/details/gtcyngslbk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangshuangyany.cn/Article/details/gtnvegirxj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzigjptxz.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhengqikj.top/Article/details/gtqjyhnhcp.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigufen.top/Article/details/gtmgyhpjxb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ehwqpu.com/Article/details/gtkmotqylg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jyoumei.cn/Article/details/gtkceewgiy.html

C#:   interface IShape { double Area(); }
来源：http://dali.jianghu66.top/Article/details/gtryrwudga.html

[G10] 访问控制
来源：http://dali.yongpay.top/Article/details/gtfgftakkx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hysaishi.cn/Article/details/gtaftudrzo.html

PHP:  public / protected / private
来源：http://dali.ivvv.top/Article/details/gtellfktnl.html

JS:   #private 字段；其余公开
来源：http://dali.hnxiangtu.top/Article/details/gtiaustaeu.html

TS:   public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gtwkyxfdvo.html

Java: public / protected / private / 默认包级
来源：http://dali.tian-w.cn/Article/details/gtdebxiuxr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuetiantiany.cn/Article/details/gtcvkgscaj.html

Ruby: public / protected / private
来源：http://dali.yvedp.cn/Article/details/gtycueckxa.html

C#:   public / protected / private / internal
来源：http://dali.guowangkeji.top/Article/details/gtirlgcjaw.html

[G11] getter / setter
来源：http://dali.sufxvd.cn/Article/details/gtzlzwfuwr.html

Py:   @property 与 @x.setter
来源：http://dali.cucudq.cn/Article/details/gtwokvxfsc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gtgizurifx.html

JS:   get name() { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gttchdqqrz.html

TS:   get name(): string { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gtrpvxecls.html

Java: public String getName() { return name; }
来源：http://dali.wangdashe.top/Article/details/gtpdnajnys.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtjhupnpaj.html

Ruby: attr_accessor :name
来源：http://dali.jiagoushi.top/Article/details/gtirlcvbkc.html

C#:   public string Name { get; set; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrqseubi.html

[G12] 对象转字符串
来源：http://dali.c1oappe.top/Article/details/gtgwrrbrwe.html

Py:   def __str__(self): return self.name
来源：http://dali.vqdsnc.cn/Article/details/gtsqhlquup.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gtorjprzvq.html

JS:   toString() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gtrcbkiame.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gtzznqpksq.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtryjiusgc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtfnvajrfc.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gtpagpcnro.html

C#:   public override string ToString() => Name;
来源：http://dali.hfpthk.cn/Article/details/gtivsqusha.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gteqzwdtbv.html

Py:   isinstance(u, User)
来源：http://dali.0kj1m.cn/Article/details/gtctjemfao.html

PHP:  $u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtuonghayn.html

JS:   u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtpjsblygb.html

TS:   u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtjexgored.html

Java: u instanceof User
来源：http://dali.ybcxt.top/Article/details/gtnwvqpqgz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jyoumei.cn/Article/details/gtinlnpyrv.html

Ruby: u.is_a?(User)
来源：http://dali.shuidangran.top/Article/details/gtryyuxjjc.html

C#:   u is User
来源：http://dali.tianlin.xyz/Article/details/gtylpnrzsd.html

[G14] 数据类 / record
来源：http://dali.zdqjudy.top/Article/details/gtffkslkue.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxsvktdk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ivvv.top/Article/details/gtxcoczswd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sysykeji.top/Article/details/gtwaqdbafq.html

TS:   type User = { name: string; age: number };
来源：http://dali.haohaochexian.top/Article/details/gtvvckcgxm.html

Java: record User(String name, int age) {}
来源：http://dali.sufxvd.cn/Article/details/gtlkwgqvuj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.c1oappe.top/Article/details/gtqgzhvwff.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmcdblksx.html

C#:   record User(string Name, int Age);
来源：http://dali.gzhubu.top/Article/details/gtkvzthisu.html

[G15] 枚举
来源：http://dali.redwolf501.top/Article/details/gtvvmahcpr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjxromwt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258888.top/Article/details/gtdthgdzrp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuxming.cn/Article/details/gtmhtkjppp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gtbjxbspky.html

Java: enum Color { RED, GREEN }
来源：http://dali.birdmap.top/Article/details/gtypoprdxv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhengqikj.top/Article/details/gtcgfjeqjc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.316326.xyz/Article/details/gtxjklisqe.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtnjfcakwf.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258888.top/Article/details/gtaudnmpem.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guowangkeji.top/Article/details/gtxbwulntw.html


<!-- 参考信息 -->