代发 wailian999

[E18] 模板占位符替换
来源：http://dali.shuidangran.top/Article/details/gt2rpyfofrq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xziqi.cn/Article/details/gt2wbwmyzyw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shangyingyoupin.top/Article/details/gt2peebkmac.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zxtkqmuk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gt2sptnwrnj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gt2gadmjwoh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gt2hycouxih.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yueranfly.top/Article/details/gt2xqbjxfvu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hywenlv.cn/Article/details/gt2eushvehv.html

[E19] 多行文本按行拆分
来源：http://dali.yvedp.cn/Article/details/gt2hulfedde.html

Py:   s.splitlines()
来源：http://dali.jqgufenzy.top/Article/details/gt2vqrxyhmf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xziqi.cn/Article/details/gt2mujulaqk.html

JS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gt2llezuaol.html

TS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gt2govpdkad.html

Java: s.lines().toList()
来源：http://dali.sysykeji.top/Article/details/gt2emoasgte.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhiwuduotai.top/Article/details/gt2jrflrufu.html

Ruby: s.lines
来源：http://dali.kuanghao11.cn/Article/details/gt2tqzapgxx.html

C#:   s.Split('\n')
来源：http://dali.cucudq.cn/Article/details/gt2qcktkvlb.html

[E20] 判断字符串是否为空
来源：http://dali.zhongyouzk.top/Article/details/gt2smluosom.html

Py:   if not s:
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pbuxndps.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.0kj1m.cn/Article/details/gt2ewprlbet.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.316326.xyz/Article/details/gt2nokymqdt.html

TS:   if (s === "") {}
来源：http://dali.xuanzx.com/Article/details/gt2vodavxpm.html

Java: if (s.isEmpty()) {}
来源：http://dali.cashguo.top/Article/details/gt2cwyerxjz.html

Go:   if s == "" {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2pqujtieu.html

Ruby: if s.empty?
来源：http://dali.ppjwa.cn/Article/details/gt2teiseyrb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cheryme.top/Article/details/gt2utaylxam.html

[E21] 超长截断加省略号
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gonjhbpy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xuetiantiany.cn/Article/details/gt2qwcgrsqd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gt2yoteiquq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gt2mfppgnwp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gt2ihigmefz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gt2ynsibwqp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aizwys.cn/Article/details/gt2linpsora.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gt2lnlrnfjd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ydzc1.top/Article/details/gt2owjwwwga.html

[E22] 字节长度与字符长度
来源：http://dali.guowangkeji.top/Article/details/gt2wmdkpdnk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nanxinkj.top/Article/details/gt2wfqzopvh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gt2lcwackbr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenlongwang.top/Article/details/gt2hsgeaweh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhengqikj.top/Article/details/gt2kioynfbl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangdashe.top/Article/details/gt2fqgfnuyg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.daxiang520.top/Article/details/gt2tpyxigwb.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gt2lvzasyaj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.birdmap.top/Article/details/gt2eccojqaw.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2cczdwqeq.html

F. 文件与目录
来源：http://dali.yj20258.top/Article/details/gt2ryekrzea.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2lnvyrdvi.html

[F01] 读取整个文件
来源：http://dali.meibo888.top/Article/details/gt2ddpzrcba.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.guannengcc.top/Article/details/gt2nynjugga.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2wgdrqznx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bdmstcsg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shuidangran.top/Article/details/gt2qrviawnd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gt2iewmdwig.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cdnleiting.top/Article/details/gt2vmfuyvkq.html

Ruby: File.read("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2fmnjnbvm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2ylhygdpq.html

[F02] 逐行读取文件
来源：http://dali.gotoacloud.top/Article/details/gt2gmnerygn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dlvwahcj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinqigfzy.top/Article/details/gt2otqlelgy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sysykeji.top/Article/details/gt2vqxvepkw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2msgffmyk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gt2fbcwbocz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.birdmap.top/Article/details/gt2uuczimry.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nanxinkj.top/Article/details/gt2qvlncxzb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sxryk.cn/Article/details/gt2sisfmufl.html

[F03] 写入文件（覆盖）
来源：http://dali.aibaodan.cn/Article/details/gt2fdfvrlql.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jianghu66.top/Article/details/gt2wgwkkswc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tianlin.xyz/Article/details/gt2lietlygk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sysykeji.top/Article/details/gt2ziixadwz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gt2hebuwrlq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xziqi.cn/Article/details/gt2lmfdvlwu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dvnvarhw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigfzy.top/Article/details/gt2ibrwjyae.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gt2bgopskhh.html

[F04] 追加写入文件
来源：http://dali.tian-w.cn/Article/details/gt2huirtnmb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yangfankeji.com/Article/details/gt2xqahpnrd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ybcxt.top/Article/details/gt2gmwygdbh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gt2gmiutoqf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.mhx1999.top/Article/details/gt2zkxfqgth.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ydzc1.top/Article/details/gt2utrosgbj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hnqzz.top/Article/details/gt2vjpdmgdy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ehwqpu.com/Article/details/gt2nyjyddfx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gotoacloud.top/Article/details/gt2tltnrzbj.html

[F05] 判断文件或目录是否存在
来源：http://dali.shzxlz.cn/Article/details/gt2drrcmnxv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yangfankeji.com/Article/details/gt2mzcahxgk.html

PHP:  file_exists("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2wiakosph.html

JS:   fs.existsSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2twxrtwvx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ungxnxgn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gt2hluulvqf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.meibo888.top/Article/details/gt2hameigef.html

Ruby: File.exist?("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2rsupiqpm.html

C#:   File.Exists("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2takmnjkz.html

[F06] 删除文件
来源：http://dali.xziqi.cn/Article/details/gt2hhcjiwju.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2kdbcvdcj.html

PHP:  unlink("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2bcawnvdq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vqvdyqcg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jbyqwhei.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gt2zzgtnmzi.html

Go:   os.Remove("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2citdgqmb.html

Ruby: File.delete("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2jbbziofi.html

C#:   File.Delete("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2thpugvou.html

[F07] 创建目录（含多级）
来源：http://dali.meibo888.top/Article/details/gt2ylndesfo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hnxiangtu.top/Article/details/gt2glwxzkpv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuanzx.com/Article/details/gt2ssoqilll.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gt2gbrkhmxd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pengpengdd.cyou/Article/details/gt2zhfmjekx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aibaodan.cn/Article/details/gt2uxqbbwzp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gogol.net.cn/Article/details/gt2jqtwgthx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.haohaochexian.top/Article/details/gt2adetqoxb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nwbrower.top/Article/details/gt2cmiqcpqf.html

[F08] 遍历目录
来源：http://dali.hnxiangtu.top/Article/details/gt2uzzwsqky.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.fzhhl.top/Article/details/gt2jmepbxzd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sufxvd.cn/Article/details/gt2ixrrdqqm.html

JS:   fs.readdirSync("dir")
来源：http://dali.mhx1999.top/Article/details/gt2kvifmjps.html

TS:   fs.readdirSync("dir")
来源：http://dali.316326.xyz/Article/details/gt2jfefuemh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ivttgxzo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yvedp.cn/Article/details/gt2gflfhrdi.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kefamaxo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ltyqrvsg.html

[F09] 获取文件大小
来源：http://dali.yongpay.top/Article/details/gt2ekddcndk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2exmnyejb.html

PHP:  filesize("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2qtvbebwn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tianlin.xyz/Article/details/gt2ypqeylrc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gt2xevawlza.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gt2twudoqin.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ijlecsnm.html

Ruby: File.size("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ytszfacy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gnsbefek.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2foubnyfo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gt2fxwobnou.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2vakdallr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2ewmpnflk.html

TS:   path.extname("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2whkgvdud.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sysykeji.top/Article/details/gt2ghezufgg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hjpgupjn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2xgsinjwa.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2ukxeoyzg.html

[F11] 复制与移动文件
来源：http://dali.yuxming.cn/Article/details/gt2yvzywlmg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2grsrtpfo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.bjfxy.top/Article/details/gt2oxzkoylt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gt2jxeijpgp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gt2ezxyusdx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gt2mxislmzg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2btwndorq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gt2yhumvonv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.andypj.xyz/Article/details/gt2igzplunx.html

[F12] CSV 读写
来源：http://dali.shuidangran.top/Article/details/gt2vohxecbl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cqqwz.cn/Article/details/gt2iiziviok.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.pycfn.com/Article/details/gt2dgqwacvs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.9152youxi.cn/Article/details/gt2bbfxqepp.html

TS:   // 同上
来源：http://dali.9152youxi.cn/Article/details/gt2myjsksfg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangshuangyany.cn/Article/details/gt2gjlwkbei.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.wangdashe.top/Article/details/gt2zgquhahx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.bjfxy.top/Article/details/gt2lzdcnviu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cucudq.cn/Article/details/gt2rukxdxhn.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2jrryuxxs.html

G. 面向对象
来源：http://dali.aizwys.cn/Article/details/gt2vlmepzzf.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2loluceek.html

[G01] 定义类
来源：http://dali.yj20258.top/Article/details/gt2paoawslu.html

Py:   class User: pass
来源：http://dali.gzhubu.top/Article/details/gt2djogfndz.html

PHP:  class User {}
来源：http://dali.tianlin.xyz/Article/details/gt2eagxzqwb.html

JS:   class User {}
来源：http://dali.aizwys.cn/Article/details/gt2ehdzyyoo.html

TS:   class User { name: string = ""; }
来源：http://dali.yongpay.top/Article/details/gt2fptqzkbp.html

Java: class User {}
来源：http://dali.hammf.cn/Article/details/gt2hstawhoi.html

Go:   type User struct { Name string }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ixgmndsq.html

Ruby: class User; end
来源：http://dali.ivvv.top/Article/details/gt2iswenhkp.html

C#:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gt2tupnqbvk.html

[G02] 构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2vagrlhmo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rlswbisa.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yueranfly.top/Article/details/gt2owcucegq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guannengcc.top/Article/details/gt2onmpnbyx.html

TS:   constructor(public name: string) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2kzrzkhkl.html

Java: User(String name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gt2jrzjrjzq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yonumen.top/Article/details/gt2wcwafmqs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhixingplan.top/Article/details/gt2duulrxza.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yvedp.cn/Article/details/gt2ysadspnt.html

[G03] 实例属性
来源：http://dali.nwbrower.top/Article/details/gt2abaftbng.html

Py:   self.name = "x"
来源：http://dali.shuidangran.top/Article/details/gt2ohhxtfkn.html

PHP:  public string $name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gt2puvmrjqg.html

JS:   this.name = "x";
来源：http://dali.wangdashe.top/Article/details/gt2nhzztujt.html

TS:   name: string = "x";
来源：http://dali.cheryme.top/Article/details/gt2pmjewibc.html

Java: private String name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pqmnegdm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.smart0.xyz/Article/details/gt2myyzbayo.html

Ruby: @name = "x"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vkvhigmp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cheryme.top/Article/details/gt2asxmfuiz.html

[G04] 定义方法
来源：http://dali.meibo888.top/Article/details/gt2wceizvua.html

Py:   def greet(self): return self.name
来源：http://dali.gotoacloud.top/Article/details/gt2yvzzleid.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gt2tnebhwes.html

JS:   greet() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gt2uhgnpgxg.html

TS:   greet(): string { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gt2trrvbquo.html

Java: String greet() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gt2bfrjulbz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gt2xtaxonxs.html

Ruby: def greet; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qbnthsmj.html

C#:   public string Greet() => Name;
来源：http://dali.sufxvd.cn/Article/details/gt2wgjdscge.html

[G05] 继承
来源：http://dali.havefunace.top/Article/details/gt2ptucmcve.html

Py:   class Admin(User): pass
来源：http://dali.cdnleiting.top/Article/details/gt2lhzopsif.html

PHP:  class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gt2rabsaliy.html

JS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gt2ozxgokrw.html

TS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gt2cvhkpkan.html

Java: class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gt2netefszi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gogol.net.cn/Article/details/gt2vaxosdcm.html

Ruby: class Admin < User; end
来源：http://dali.tian-w.cn/Article/details/gt2nhbmwjyb.html

C#:   class Admin : User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2haltnbyf.html

[G06] 重写方法
来源：http://dali.yangfankeji.com/Article/details/gt2jgwnexpw.html

Py:   def greet(self): return "admin"
来源：http://dali.ppjwa.cn/Article/details/gt2rgxvclsa.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2sacowhqw.html

JS:   greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2ftgaxgsl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gt2rnhajqev.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gt2fsrnmdln.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sxryk.cn/Article/details/gt2imzvmybp.html

Ruby: def greet; "admin"; end
来源：http://dali.havefunace.top/Article/details/gt2eeixdogs.html

C#:   public override string Greet() => "admin";
来源：http://dali.yanxiufei.cn/Article/details/gt2okmruoof.html

[G07] 调用父类方法
来源：http://dali.cheryme.top/Article/details/gt2ovablmgu.html

Py:   super().greet()
来源：http://dali.ybcxt.top/Article/details/gt2mqczcvbp.html

PHP:  parent::greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2edzedpfn.html

JS:   super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gt2ijtuqibm.html

TS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gt2ayppiwvf.html

Java: super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gt2zgihicvw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iqmggjxr.html

Ruby: super
来源：http://dali.yanxiufei.cn/Article/details/gt2ictsbvmu.html

C#:   base.Greet();
来源：http://dali.pycfn.com/Article/details/gt2ovekawxc.html

[G08] 静态方法与属性
来源：http://dali.ydzc1.top/Article/details/gt2nhfnzcyr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yangfankeji.com/Article/details/gt2wzwjcxvq.html

PHP:  public static function f() {}
来源：http://dali.cucudq.cn/Article/details/gt2yaqugkie.html

JS:   static f() {}
来源：http://dali.yj202588.top/Article/details/gt2memjovxx.html

TS:   static f(): void {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2rhitqytr.html

Java: static void f() {}
来源：http://dali.zhixingplan.top/Article/details/gt2mvignabk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tanke756.top/Article/details/gt2xifxtrun.html

Ruby: def self.f; end
来源：http://dali.ppjwa.cn/Article/details/gt2kxlyrnlh.html

C#:   public static void F() {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2lkluakex.html

[G09] 接口 / 抽象类
来源：http://dali.zycfv.cn/Article/details/gt2wrcstryv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yangfankeji.com/Article/details/gt2eitovbmc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.vqdsnc.cn/Article/details/gt2wubzrfjs.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yangfankeji.com/Article/details/gt2ftprebbr.html

TS:   interface Shape { area(): number; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2fschstee.html

Java: interface Shape { double area(); }
来源：http://dali.daria6918.cn/Article/details/gt2ugjisgps.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zbmdgbvj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hysaishi.cn/Article/details/gt2gvkcprcy.html

C#:   interface IShape { double Area(); }
来源：http://dali.guowangkeji.top/Article/details/gt2yroepviv.html

[G10] 访问控制
来源：http://dali.pycfn.com/Article/details/gt2gfnstzqc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ehwqpu.com/Article/details/gt2nxnlczlo.html

PHP:  public / protected / private
来源：http://dali.xinyue.icu/Article/details/gt2cxagubgs.html

JS:   #private 字段；其余公开
来源：http://dali.zhiwuduotai.top/Article/details/gt2thtezydm.html

TS:   public / protected / private
来源：http://dali.pycfn.com/Article/details/gt2uvdwxokl.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258.top/Article/details/gt2zeytesky.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.bjfxy.top/Article/details/gt2hqzvzvff.html

Ruby: public / protected / private
来源：http://dali.wangdashe.top/Article/details/gt2shjfvaag.html

C#:   public / protected / private / internal
来源：http://dali.yj20258.top/Article/details/gt2owhmbfex.html

[G11] getter / setter
来源：http://dali.xinyue.icu/Article/details/gt2tsoabaus.html

Py:   @property 与 @x.setter
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bkgdofrv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gt2cnvsexpr.html

JS:   get name() { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gt2wpunmblw.html

TS:   get name(): string { return this._name; }
来源：http://dali.cucudq.cn/Article/details/gt2coyzeduo.html

Java: public String getName() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gt2txorvpuy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lbsynvcr.html

Ruby: attr_accessor :name
来源：http://dali.cashguo.top/Article/details/gt2sokihgwb.html

C#:   public string Name { get; set; }
来源：http://dali.sxryk.cn/Article/details/gt2osopdokm.html

[G12] 对象转字符串
来源：http://dali.dashuyun.cn/Article/details/gt2rtvtoygz.html

Py:   def __str__(self): return self.name
来源：http://dali.svipenyu.cn/Article/details/gt2mwsgsvom.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gt2ijnkjfmt.html

JS:   toString() { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gt2llxjywqu.html

TS:   toString(): string { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gt2iukxxecn.html

Java: @Override public String toString() { return name; }
来源：http://dali.redwolf501.top/Article/details/gt2qdoaqpvs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gt2ujvvirhg.html

Ruby: def to_s; @name; end
来源：http://dali.hywenlv.cn/Article/details/gt2bufdxfeg.html

C#:   public override string ToString() => Name;
来源：http://dali.yj202588.top/Article/details/gt2mtysfhvk.html

[G13] 判断对象类型
来源：http://dali.havefunace.top/Article/details/gt2aykkqpqe.html

Py:   isinstance(u, User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mmojpaat.html

PHP:  $u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gt2phjcbjfy.html

JS:   u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gt2hsthiivm.html

TS:   u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gt2ohpwupzc.html

Java: u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2bfctdxbl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xziqi.cn/Article/details/gt2gbaidbkb.html

Ruby: u.is_a?(User)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fqweqxgo.html

C#:   u is User
来源：http://dali.ivvv.top/Article/details/gt2lnjvvixh.html

[G14] 数据类 / record
来源：http://dali.feifeiyinyue.top/Article/details/gt2pxstcjpe.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.vqdsnc.cn/Article/details/gt2fcjvfuql.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yueranfly.top/Article/details/gt2wwadykyj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ytfgsduy.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenlongwang.top/Article/details/gt2qivsnbpi.html

Java: record User(String name, int age) {}
来源：http://dali.chenlongwang.top/Article/details/gt2drobetrp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgfzy.top/Article/details/gt2gifezkae.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tianlin.xyz/Article/details/gt2wdbvdeze.html

C#:   record User(string Name, int Age);
来源：http://dali.sweek.top/Article/details/gt2glpjmxru.html

[G15] 枚举
来源：http://dali.yj20258.top/Article/details/gt2wefrqkzi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2xbnkwjbm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gogol.net.cn/Article/details/gt2fhcrrbvg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.aizwys.cn/Article/details/gt2hbyefylw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.kuanghao11.cn/Article/details/gt2rlwuesrt.html

Java: enum Color { RED, GREEN }
来源：http://dali.jiagoushi.top/Article/details/gt2npsmqebp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gzhubu.top/Article/details/gt2qmkqoyac.html

Ruby: Color = %i[red green].freeze
来源：http://dali.daxiang520.top/Article/details/gt2rshfkmbf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gt2hzjbyhah.html

[G16] 对象转数组 / 字典
来源：http://dali.c1oappe.top/Article/details/gt2rotjfdsy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xuetiantiany.cn/Article/details/gt2fgieepcg.html

PHP:  get_object_vars($obj);
来源：http://dali.yuanzhike.top/Article/details/gt2wkszfazi.html

JS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2bqwxjdia.html

TS:   Object.entries(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2pklvhjce.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.birdmap.top/Article/details/gt2leuyjqhm.html


<!-- 参考信息 -->