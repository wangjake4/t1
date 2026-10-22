代发 wailian999

[E18] 模板占位符替换
来源：http://dali.yonumen.top/Article/details/gt2pmngecqw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.kuanghao11.cn/Article/details/gt2emevngje.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jyoumei.cn/Article/details/gt2gdyftswo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gt2zdhaqgct.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ggfwmvgg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gt2knsgxkjz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dlvccvsl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cqqwz.cn/Article/details/gt2uxpiuyuq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2rtikzxai.html

[E19] 多行文本按行拆分
来源：http://dali.yongpay.top/Article/details/gt2yqrjekbv.html

Py:   s.splitlines()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zwlyifli.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.andypj.xyz/Article/details/gt2pocbcxdt.html

JS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ladxgevw.html

TS:   s.split(/\r?\n/)
来源：http://dali.ybcxt.top/Article/details/gt2sjdhfpnc.html

Java: s.lines().toList()
来源：http://dali.zhengqikj.top/Article/details/gt2udokwjrw.html

Go:   strings.Split(s, "\n")
来源：http://dali.iojbl.cn/Article/details/gt2oduzcakd.html

Ruby: s.lines
来源：http://dali.tanke756.top/Article/details/gt2iwpcwrnl.html

C#:   s.Split('\n')
来源：http://dali.haohaochexian.top/Article/details/gt2rtuvosyd.html

[E20] 判断字符串是否为空
来源：http://dali.shuidangran.top/Article/details/gt2xmusdqkx.html

Py:   if not s:
来源：http://dali.yongpay.top/Article/details/gt2aewoaqrh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ivvv.top/Article/details/gt2gchwskvg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xylfe.cn/Article/details/gt2hsqsmxcy.html

TS:   if (s === "") {}
来源：http://dali.hfpthk.cn/Article/details/gt2sljndzoz.html

Java: if (s.isEmpty()) {}
来源：http://dali.hysaishi.cn/Article/details/gt2hufjlcyu.html

Go:   if s == "" {}
来源：http://dali.316326.xyz/Article/details/gt2rysdpczx.html

Ruby: if s.empty?
来源：http://dali.dashuyun.cn/Article/details/gt2yhvqovwl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2hfhotgrn.html

[E21] 超长截断加省略号
来源：http://dali.snrcjt.cn/Article/details/gt2kpjbkzzy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.fzhhl.top/Article/details/gt2vktileif.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.birdmap.top/Article/details/gt2dolsnzzq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gt2ydprvqgh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gt2dftmnnqo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gt2ktfwfccl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cashguo.top/Article/details/gt2hfujvnrf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gt2ctqkazsv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gt2fcfnkelc.html

[E22] 字节长度与字符长度
来源：http://dali.jqgfzy.top/Article/details/gt2izukssfq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhengqikj.top/Article/details/gt2askveudf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gt2fxrxuaqs.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gt2ybkjcmlq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gt2heyvurjf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hnqzz.top/Article/details/gt2xwmxlfyz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xylfe.cn/Article/details/gt2txqpbgzv.html

Ruby: s.bytesize;  s.length
来源：http://dali.mhx1999.top/Article/details/gt2cljrjwkt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhoulong.xyz/Article/details/gt2nfwjkaob.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2mzfjhbxv.html

F. 文件与目录
来源：http://dali.iojbl.cn/Article/details/gt2geeuqziq.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2ivszybus.html

[F01] 读取整个文件
来源：http://dali.birdmap.top/Article/details/gt2iwwjbgtl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj202588.top/Article/details/gt2cwukixid.html

PHP:  file_get_contents("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2ssuxfugt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.redwolf501.top/Article/details/gt2iajvilmh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gt2vpmossvn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gt2scgqjruo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hnqzz.top/Article/details/gt2uswyelbo.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rwgrosme.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2gsoqqcba.html

[F02] 逐行读取文件
来源：http://dali.nwbrower.top/Article/details/gt2scfooifh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenzaomai.com/Article/details/gt2dgqokdyl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhongyouzk.top/Article/details/gt2rmccqgfe.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gt2gyovzsxy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tianlin.xyz/Article/details/gt2iglaxodr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gt2woksawme.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.aibaodan.cn/Article/details/gt2tjhjnlzc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.mhx1999.top/Article/details/gt2kbqvnmsl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ydzc1.top/Article/details/gt2mgpvhlsr.html

[F03] 写入文件（覆盖）
来源：http://dali.redwolf501.top/Article/details/gt2gsxkodza.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wtkawsfv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gt2xewyxqey.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cashguo.top/Article/details/gt2bynwjzkg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gt2dcnscvtq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.kuanghao11.cn/Article/details/gt2oqvoepys.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenzaomai.com/Article/details/gt2mojrdlje.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenlongwang.top/Article/details/gt2cslnwtof.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xziqi.cn/Article/details/gt2ustgkprk.html

[F04] 追加写入文件
来源：http://dali.yanxiufei.cn/Article/details/gt2wlfjasqo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhixingplan.top/Article/details/gt2pleqgbqh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2unyohbun.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gt2jcweqjxn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jmedhnlq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.bjfxy.top/Article/details/gt2uykjwfog.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.aizwys.cn/Article/details/gt2ffuxklxj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gaohongyu789.top/Article/details/gt2rfvpgmkj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangshuangyany.cn/Article/details/gt2ynakajnx.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhengqikj.top/Article/details/gt2jkdpzzus.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.haohaochexian.top/Article/details/gt2wvzscymr.html

PHP:  file_exists("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2xikxqait.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2aobdaveo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2fghgpwfd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gt2kkdysxcs.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cqqwz.cn/Article/details/gt2ycrbcnvn.html

Ruby: File.exist?("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2qfrpsgbs.html

C#:   File.Exists("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2rihbpjlx.html

[F06] 删除文件
来源：http://dali.cdnleiting.top/Article/details/gt2bxicppsk.html

Py:   os.remove("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2tqvxyddn.html

PHP:  unlink("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2cwdzdbms.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2oqehwnjb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qlzugtaw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gt2yhjssfhv.html

Go:   os.Remove("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2pqbvsmbg.html

Ruby: File.delete("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2ziwswzdu.html

C#:   File.Delete("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2wxzazmmz.html

[F07] 创建目录（含多级）
来源：http://dali.fzhhl.top/Article/details/gt2kdfemzur.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.guannengcc.top/Article/details/gt2ivfjpuve.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.smart0.xyz/Article/details/gt2iaxuoqhi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gt2jfhampxe.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigufen.top/Article/details/gt2yfmvmrts.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigufen.top/Article/details/gt2ygfowric.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cdnleiting.top/Article/details/gt2jfznzcxc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tian-w.cn/Article/details/gt2rxzihwxu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yuxming.cn/Article/details/gt2gqcskmqc.html

[F08] 遍历目录
来源：http://dali.gogol.net.cn/Article/details/gt2admubcvy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.aibaodan.cn/Article/details/gt2gxreziuo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pzkroloi.html

JS:   fs.readdirSync("dir")
来源：http://dali.c1oappe.top/Article/details/gt2zhdsvrrj.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ayujxues.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gt2dhlnvlfo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.iojbl.cn/Article/details/gt2wuippfym.html

Ruby: Dir.children("dir")
来源：http://dali.jianghu66.top/Article/details/gt2pkbfesyy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2twwuflyq.html

[F09] 获取文件大小
来源：http://dali.316326.xyz/Article/details/gt2mmdfhnaa.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2kizpjwyd.html

PHP:  filesize("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2zojxhqjn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hywenlv.cn/Article/details/gt2xmxwwrib.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gaohongyu789.top/Article/details/gt2xyqkwitz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gt2aojapyvv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wyeohtzv.html

Ruby: File.size("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2vjmvsvfl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sufxvd.cn/Article/details/gt2ilzrydnj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.quarkkingdee.top/Article/details/gt2wrcvqbmr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2pzxkxyfz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2zwrtzdeq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2dhfmgadg.html

TS:   path.extname("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2spzljhya.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zycfv.cn/Article/details/gt2hoebugtd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2eychzrxf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2ekwwouaq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2kyemmraf.html

[F11] 复制与移动文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vuzyezol.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2sifszshc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.birdmap.top/Article/details/gt2owtxdfvd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2rvmpgvtr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ipeztpkf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yonumen.top/Article/details/gt2fheinlhq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ehwqpu.com/Article/details/gt2lgjzokbd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gt2opxcyrbp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.feifeiyinyue.top/Article/details/gt2jyewokcm.html

[F12] CSV 读写
来源：http://dali.jqgfzy.top/Article/details/gt2fspwgldx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zycfv.cn/Article/details/gt2mjqvyjve.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yongpay.top/Article/details/gt2pbzhagpe.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cucudq.cn/Article/details/gt2klbpbhfh.html

TS:   // 同上
来源：http://dali.gzhubu.top/Article/details/gt2hdpavfxv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jyoumei.cn/Article/details/gt2mfjxigfe.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigufen.top/Article/details/gt2nwxaixpg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cdnleiting.top/Article/details/gt2iefqnjka.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tanke756.top/Article/details/gt2waeukkxc.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2hfsqexff.html

G. 面向对象
来源：http://dali.yuanzhike.top/Article/details/gt2vazabpxj.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2vujfklbn.html

[G01] 定义类
来源：http://dali.hnxiangtu.top/Article/details/gt2amfomwat.html

Py:   class User: pass
来源：http://dali.ydzc1.top/Article/details/gt2bbgdpajw.html

PHP:  class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2igeluztq.html

JS:   class User {}
来源：http://dali.jqgfzy.top/Article/details/gt2pitqnorw.html

TS:   class User { name: string = ""; }
来源：http://dali.aibaodan.cn/Article/details/gt2cuttuqzh.html

Java: class User {}
来源：http://dali.zhixingplan.top/Article/details/gt2jvqbdluw.html

Go:   type User struct { Name string }
来源：http://dali.cqqwz.cn/Article/details/gt2wcelbmfw.html

Ruby: class User; end
来源：http://dali.andypj.xyz/Article/details/gt2kouwmbmh.html

C#:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2rkzqzrze.html

[G02] 构造函数
来源：http://dali.zhengqikj.top/Article/details/gt2dbcloysb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hgxqsqqo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hysaishi.cn/Article/details/gt2uxvaixmx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258.top/Article/details/gt2llwligdz.html

TS:   constructor(public name: string) {}
来源：http://dali.aibaodan.cn/Article/details/gt2fvyfjydx.html

Java: User(String name) { this.name = name; }
来源：http://dali.0kj1m.cn/Article/details/gt2igtxgaqn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.snrcjt.cn/Article/details/gt2crrsfbwl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aibaodan.cn/Article/details/gt2wkvytsvd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.svipenyu.cn/Article/details/gt2aubrljxx.html

[G03] 实例属性
来源：http://dali.smart0.xyz/Article/details/gt2qvwdzgpf.html

Py:   self.name = "x"
来源：http://dali.fengsongda.top/Article/details/gt2bfrnwynx.html

PHP:  public string $name = "x";
来源：http://dali.yonumen.top/Article/details/gt2rlnwumru.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfqhxpt.html

TS:   name: string = "x";
来源：http://dali.nanxinkj.top/Article/details/gt2vgevgwmu.html

Java: private String name;
来源：http://dali.nanxuanxn.top/Article/details/gt2yormayvg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.svipenyu.cn/Article/details/gt2sgpzrgtn.html

Ruby: @name = "x"
来源：http://dali.sysykeji.top/Article/details/gt2frxkfexi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shzxlz.cn/Article/details/gt2bgnvxker.html

[G04] 定义方法
来源：http://dali.316326.xyz/Article/details/gt2rqlaakus.html

Py:   def greet(self): return self.name
来源：http://dali.yongpay.top/Article/details/gt2typcakab.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2nerorqec.html

JS:   greet() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gt2fuvlopvb.html

TS:   greet(): string { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gt2qenyoqyl.html

Java: String greet() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2bpdxfbjt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tmkglkml.html

Ruby: def greet; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2ziepxjex.html

C#:   public string Greet() => Name;
来源：http://dali.guowangkeji.top/Article/details/gt2omjyesdj.html

[G05] 继承
来源：http://dali.nanxinkj.top/Article/details/gt2sxmavdgl.html

Py:   class Admin(User): pass
来源：http://dali.sufxvd.cn/Article/details/gt2wojlzxpc.html

PHP:  class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gt2rpbddauw.html

JS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gt2rgeexmku.html

TS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gt2tneqgkmk.html

Java: class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gt2tmieapab.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shzxlz.cn/Article/details/gt2aencpcrd.html

Ruby: class Admin < User; end
来源：http://dali.yj20258888.top/Article/details/gt2pzqonmvq.html

C#:   class Admin : User {}
来源：http://dali.ppjwa.cn/Article/details/gt2izjfykee.html

[G06] 重写方法
来源：http://dali.xziqi.cn/Article/details/gt2wrsfydhk.html

Py:   def greet(self): return "admin"
来源：http://dali.tian-w.cn/Article/details/gt2snwnnwzc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gt2bzpoghwu.html

JS:   greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gt2mtgxahzp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2jgwyfppp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2vjyhngae.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.birdmap.top/Article/details/gt2tsnkdeeq.html

Ruby: def greet; "admin"; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2pefbzetv.html

C#:   public override string Greet() => "admin";
来源：http://dali.316326.xyz/Article/details/gt2popnijmq.html

[G07] 调用父类方法
来源：http://dali.pengpengdd.cyou/Article/details/gt2hlnzaevn.html

Py:   super().greet()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mvtdrgib.html

PHP:  parent::greet();
来源：http://dali.yj20258.top/Article/details/gt2oozxtezc.html

JS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gt2omwbwdsf.html

TS:   super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2idyzxgai.html

Java: super.greet();
来源：http://dali.yongpay.top/Article/details/gt2ektplyco.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.pengpengdd.cyou/Article/details/gt2bgrbbypw.html

Ruby: super
来源：http://dali.daria6918.cn/Article/details/gt2jzmsrave.html

C#:   base.Greet();
来源：http://dali.hywenlv.cn/Article/details/gt2dbybbisp.html

[G08] 静态方法与属性
来源：http://dali.smart0.xyz/Article/details/gt2rkpehoov.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nwbrower.top/Article/details/gt2copvwoxn.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jtmnwfzw.html

JS:   static f() {}
来源：http://dali.redwolf501.top/Article/details/gt2tmjgdwjk.html

TS:   static f(): void {}
来源：http://dali.quarkkingdee.top/Article/details/gt2kscciheq.html

Java: static void f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2wylnwfej.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.svipenyu.cn/Article/details/gt2yygivpwb.html

Ruby: def self.f; end
来源：http://dali.sxryk.cn/Article/details/gt2iuyxrqaz.html

C#:   public static void F() {}
来源：http://dali.jqgfzy.top/Article/details/gt2joxmulyq.html

[G09] 接口 / 抽象类
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lqhrwaly.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ydzc1.top/Article/details/gt2lkltksxr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xinyue.icu/Article/details/gt2lvquuify.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenzaomai.com/Article/details/gt2qsgdazmy.html

TS:   interface Shape { area(): number; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2jcntzwmh.html

Java: interface Shape { double area(); }
来源：http://dali.guannengcc.top/Article/details/gt2ccpilffj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fldzxtlr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnxiangtu.top/Article/details/gt2bcfoplpd.html

C#:   interface IShape { double Area(); }
来源：http://dali.jyoumei.cn/Article/details/gt2vticxffy.html

[G10] 访问控制
来源：http://dali.feifeiyinyue.top/Article/details/gt2gbvkymdj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.bjfxy.top/Article/details/gt2fhvdvmnc.html

PHP:  public / protected / private
来源：http://dali.c1oappe.top/Article/details/gt2lgtliouc.html

JS:   #private 字段；其余公开
来源：http://dali.zdqjudy.top/Article/details/gt2hcwlvwgy.html

TS:   public / protected / private
来源：http://dali.andypj.xyz/Article/details/gt2rhpqmyvi.html

Java: public / protected / private / 默认包级
来源：http://dali.haohaochexian.top/Article/details/gt2zpmbizgf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jiagoushi.top/Article/details/gt2slmxddut.html

Ruby: public / protected / private
来源：http://dali.nwbrower.top/Article/details/gt2syugezqq.html

C#:   public / protected / private / internal
来源：http://dali.aibaodan.cn/Article/details/gt2tgomrzui.html

[G11] getter / setter
来源：http://dali.svipenyu.cn/Article/details/gt2wmmvengs.html

Py:   @property 与 @x.setter
来源：http://dali.xinyue.icu/Article/details/gt2gcruhcil.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gt2sabrpxsc.html

JS:   get name() { return this._name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2edwctnrl.html

TS:   get name(): string { return this._name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2wglzihtn.html

Java: public String getName() { return name; }
来源：http://dali.bjfxy.top/Article/details/gt2pkrevsyq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gt2iorzuvwd.html

Ruby: attr_accessor :name
来源：http://dali.zhixingplan.top/Article/details/gt2naxeaggx.html

C#:   public string Name { get; set; }
来源：http://dali.tianlin.xyz/Article/details/gt2ruumfmgr.html

[G12] 对象转字符串
来源：http://dali.gotoacloud.top/Article/details/gt2lqspjdwr.html

Py:   def __str__(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gt2ccxtlfea.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gt2xrjjqofw.html

JS:   toString() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gt2zightxwz.html

TS:   toString(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gt2pyyxjskr.html

Java: @Override public String toString() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gt2fyfttkth.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gt2ckwbjynp.html

Ruby: def to_s; @name; end
来源：http://dali.haohaochexian.top/Article/details/gt2buulyiad.html

C#:   public override string ToString() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gt2bgejrjel.html

[G13] 判断对象类型
来源：http://dali.yongpay.top/Article/details/gt2irtclwxq.html

Py:   isinstance(u, User)
来源：http://dali.yj20258.top/Article/details/gt2zacickry.html

PHP:  $u instanceof User
来源：http://dali.tian-w.cn/Article/details/gt2ggfolods.html

JS:   u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gt2nkblhafz.html

TS:   u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gt2maogopei.html

Java: u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gt2njyitfmr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.kuanghao11.cn/Article/details/gt2yywtzwpc.html

Ruby: u.is_a?(User)
来源：http://dali.yuxming.cn/Article/details/gt2higykkde.html

C#:   u is User
来源：http://dali.fzhhl.top/Article/details/gt2bguzugtx.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2grxlfbxl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yueranfly.top/Article/details/gt2oidwkxus.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhixingplan.top/Article/details/gt2zpxaqbuo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangshuangyany.cn/Article/details/gt2irrrxbxk.html

TS:   type User = { name: string; age: number };
来源：http://dali.iojbl.cn/Article/details/gt2zumuoxdn.html

Java: record User(String name, int age) {}
来源：http://dali.ivvv.top/Article/details/gt2aqwyohfa.html

Go:   type User struct { Name string; Age int }
来源：http://dali.vqdsnc.cn/Article/details/gt2lqvixgiz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenzaomai.com/Article/details/gt2mfvmtvvl.html

C#:   record User(string Name, int Age);
来源：http://dali.dianchejie.cn/Article/details/gt2quhtkuhh.html

[G15] 枚举
来源：http://dali.ehwqpu.com/Article/details/gt2ekjbdbph.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jiagoushi.top/Article/details/gt2lzmiphrj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2wbsrisvp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sysykeji.top/Article/details/gt2jwgzupjy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hammf.cn/Article/details/gt2muqhtfyu.html

Java: enum Color { RED, GREEN }
来源：http://dali.xuanzx.com/Article/details/gt2prlmkcqk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.birdmap.top/Article/details/gt2xhvqnivy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cucudq.cn/Article/details/gt2knahywlf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hysaishi.cn/Article/details/gt2akubxzrb.html

[G16] 对象转数组 / 字典
来源：http://dali.cdnleiting.top/Article/details/gt2bmeojzgy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.snrcjt.cn/Article/details/gt2yvxqlxlc.html

PHP:  get_object_vars($obj);
来源：http://dali.vqdsnc.cn/Article/details/gt2lirrhibm.html

JS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2onfwfgtu.html

TS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2cwstlphc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuanzhike.top/Article/details/gt2tayvunmo.html


<!-- 参考信息 -->