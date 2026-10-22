代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zoemlspz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gt2nlbdulla.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dwipdkhg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.daria6918.cn/Article/details/gt2hvttdwic.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sufxvd.cn/Article/details/gt2hugwkzkc.html

[E19] 多行文本按行拆分
来源：http://dali.gotoacloud.top/Article/details/gt2hkuasuce.html

Py:   s.splitlines()
来源：http://dali.cheryme.top/Article/details/gt2hxcsojnl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2yuhofztt.html

JS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gt2dygivkze.html

TS:   s.split(/\r?\n/)
来源：http://dali.0kj1m.cn/Article/details/gt2odcnltev.html

Java: s.lines().toList()
来源：http://dali.shzxlz.cn/Article/details/gt2iyzzalhm.html

Go:   strings.Split(s, "\n")
来源：http://dali.fzhhl.top/Article/details/gt2mbygzxxl.html

Ruby: s.lines
来源：http://dali.yj202588.top/Article/details/gt2dhvtxbnc.html

C#:   s.Split('\n')
来源：http://dali.nanxinkj.top/Article/details/gt2dsrpvfmk.html

[E20] 判断字符串是否为空
来源：http://dali.havefunace.top/Article/details/gt2kcjfpbwu.html

Py:   if not s:
来源：http://dali.andypj.xyz/Article/details/gt2ndolguxm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xziqi.cn/Article/details/gt2jnsmkqem.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2cjcivrds.html

TS:   if (s === "") {}
来源：http://dali.ydzc1.top/Article/details/gt2pfbrwmpc.html

Java: if (s.isEmpty()) {}
来源：http://dali.bjfxy.top/Article/details/gt2eukdhjmb.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqpszxo.html

Ruby: if s.empty?
来源：http://dali.zdqjudy.top/Article/details/gt2jjrbuafx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.redwolf501.top/Article/details/gt2byxwxvip.html

[E21] 超长截断加省略号
来源：http://dali.tian-w.cn/Article/details/gt2lszllbpo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.haohaochexian.top/Article/details/gt2pceczoos.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gt2napnmrru.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gt2mqjexwgs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gt2xhabvmhr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gt2sduoohfg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.svipenyu.cn/Article/details/gt2iwcbehqg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gt2fxavzitc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gt2teotpodd.html

[E22] 字节长度与字符长度
来源：http://dali.yanxiufei.cn/Article/details/gt2sbfhcxyq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.mhx1999.top/Article/details/gt2mrqoiifq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mqywlyqr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gt2cqjekmzu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gt2orvslfpw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ydzc1.top/Article/details/gt2vzzrqgyr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hongshengwenyu.top/Article/details/gt2zycgqzgr.html

Ruby: s.bytesize;  s.length
来源：http://dali.316326.xyz/Article/details/gt2ywomibay.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zkpppgqp.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2omuvxsiy.html

F. 文件与目录
来源：http://dali.sxryk.cn/Article/details/gt2lnbcmhmf.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2ziiqdpah.html

[F01] 读取整个文件
来源：http://dali.chenzaomai.com/Article/details/gt2xklhqtqi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenzaomai.com/Article/details/gt2dxoltrld.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2imewunhz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.wangshuangyany.cn/Article/details/gt2hhheiyrl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gt2dekatjtx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gt2qqsnrppl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhengqikj.top/Article/details/gt2lpvukyqb.html

Ruby: File.read("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xcrdnrjo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2ojfeuxuk.html

[F02] 逐行读取文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qchwpduz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ydzc1.top/Article/details/gt2nhtknlhz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.fengsongda.top/Article/details/gt2erxitpfo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aizwys.cn/Article/details/gt2yjbwyqup.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gt2ijibfxkf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sufxvd.cn/Article/details/gt2eyzmagjr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ydzc1.top/Article/details/gt2fvgtwvab.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.316326.xyz/Article/details/gt2czqxnjmy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.smart0.xyz/Article/details/gt2dqsisiux.html

[F03] 写入文件（覆盖）
来源：http://dali.jqgfzy.top/Article/details/gt2lbdykaxg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.daria6918.cn/Article/details/gt2xmsbjijk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gt2dfwcrsgx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gt2lmwebyxf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cashguo.top/Article/details/gt2uibgiewo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cucudq.cn/Article/details/gt2wvsidhmc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yonumen.top/Article/details/gt2asdfypph.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qjwinlar.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hysaishi.cn/Article/details/gt2mfbdgcxm.html

[F04] 追加写入文件
来源：http://dali.tianlin.xyz/Article/details/gt2azebixim.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hywenlv.cn/Article/details/gt2eatgdkga.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zycfv.cn/Article/details/gt2hxjyvsry.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gt2vwurklak.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gt2wldgppll.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shzxlz.cn/Article/details/gt2xdzdgwim.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vduiujsv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhongyouzk.top/Article/details/gt2uklbnozk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangshuangyany.cn/Article/details/gt2yhrrydvz.html

[F05] 判断文件或目录是否存在
来源：http://dali.sysykeji.top/Article/details/gt2dunyvgpv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinqigfzy.top/Article/details/gt2iyxryvbf.html

PHP:  file_exists("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2rzjawkvc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2arnlpxvv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2kpzfnudd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gt2qvhuvwlm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daxiang520.top/Article/details/gt2zdexbxmb.html

Ruby: File.exist?("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2hshgabzo.html

C#:   File.Exists("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jvuzkikk.html

[F06] 删除文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lnkrvrjw.html

Py:   os.remove("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2uxbiqvpz.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2osknuwwa.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2xphibmod.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2ekbkuiob.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gt2bjrcqkkc.html

Go:   os.Remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2rmgbaxds.html

Ruby: File.delete("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2wlraralu.html

C#:   File.Delete("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2fyaegqqh.html

[F07] 创建目录（含多级）
来源：http://dali.yonumen.top/Article/details/gt2afewegoj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjtabxx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gaohongyu789.top/Article/details/gt2vymjckmn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xrdphbkp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2omcaqldb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ydzc1.top/Article/details/gt2bzpaitkr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yanxiufei.cn/Article/details/gt2qvjhfcqt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gogol.net.cn/Article/details/gt2rtyepjvz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cucudq.cn/Article/details/gt2iagqkeiv.html

[F08] 遍历目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2stbljugj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yangfankeji.com/Article/details/gt2idpvbipj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yueranfly.top/Article/details/gt2bekuqurr.html

JS:   fs.readdirSync("dir")
来源：http://dali.jiagoushi.top/Article/details/gt2cjiylotg.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gt2vmgsupjc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gt2kjmcemqu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigfzy.top/Article/details/gt2sqnegvlj.html

Ruby: Dir.children("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gvjrqahp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dqrxjjix.html

[F09] 获取文件大小
来源：http://dali.chenlongwang.top/Article/details/gt2ggyehmeg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2ebqldywg.html

PHP:  filesize("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2gnfxymdt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gt2kkxgeuze.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yvedp.cn/Article/details/gt2guszrskp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gt2ezxsxzmr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yangfankeji.com/Article/details/gt2reqnfabu.html

Ruby: File.size("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2vrkzkced.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.c1oappe.top/Article/details/gt2qbdcxiec.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ybcxt.top/Article/details/gt2liitxhgh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2spfxligw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.havefunace.top/Article/details/gt2lczyyzsu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2widaoxkq.html

TS:   path.extname("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2hfkodfep.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tasmxghy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2ihwxzwqv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2hvffsbce.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2sletcmtu.html

[F11] 复制与移动文件
来源：http://dali.ybcxt.top/Article/details/gt2bjrrzwru.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2phltmxci.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ivvv.top/Article/details/gt2jtfmiumy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gt2evekazxh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2rrqvvrki.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenzaomai.com/Article/details/gt2tukpxhwv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.9152youxi.cn/Article/details/gt2lxddcica.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2hmmqjtpj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.bjfxy.top/Article/details/gt2zofvkgfg.html

[F12] CSV 读写
来源：http://dali.jlsjyb.cn/Article/details/gt2eunbbsye.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.smart0.xyz/Article/details/gt2awckymjq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.snrcjt.cn/Article/details/gt2iwaqucjv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jianghu66.top/Article/details/gt2yunanngd.html

TS:   // 同上
来源：http://dali.nanxuanxn.top/Article/details/gt2zbviemvh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sufxvd.cn/Article/details/gt2qdsoghcr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj20258.top/Article/details/gt2dykcztyk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.birdmap.top/Article/details/gt2ilucwvsf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xuanzx.com/Article/details/gt2wxthdcov.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sklnhqlr.html

G. 面向对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vlalivgm.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2brgawirs.html

[G01] 定义类
来源：http://dali.cucudq.cn/Article/details/gt2kxovfjzm.html

Py:   class User: pass
来源：http://dali.jqgufenzy.top/Article/details/gt2tfdkksva.html

PHP:  class User {}
来源：http://dali.fzhhl.top/Article/details/gt2yyqvrvox.html

JS:   class User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2ylrtvtdp.html

TS:   class User { name: string = ""; }
来源：http://dali.ybcxt.top/Article/details/gt2wuahglxz.html

Java: class User {}
来源：http://dali.mhx1999.top/Article/details/gt2aebiripr.html

Go:   type User struct { Name string }
来源：http://dali.yongpay.top/Article/details/gt2rbfxwlzv.html

Ruby: class User; end
来源：http://dali.yvedp.cn/Article/details/gt2lkecyvhh.html

C#:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ddwccdey.html

[G02] 构造函数
来源：http://dali.jqgufenzy.top/Article/details/gt2agfzwuij.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jianghu66.top/Article/details/gt2pxxondmm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hywenlv.cn/Article/details/gt2fnloawxn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gt2wzrnzvgs.html

TS:   constructor(public name: string) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2jnveqfut.html

Java: User(String name) { this.name = name; }
来源：http://dali.yangfankeji.com/Article/details/gt2orajvmhh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.quarkkingdee.top/Article/details/gt2qmbmictp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fgndbyec.html

C#:   public User(string name) { Name = name; }
来源：http://dali.svipenyu.cn/Article/details/gt2qykohngs.html

[G03] 实例属性
来源：http://dali.jqgfzy.top/Article/details/gt2rluxqifv.html

Py:   self.name = "x"
来源：http://dali.yj20258.top/Article/details/gt2dryitfsn.html

PHP:  public string $name = "x";
来源：http://dali.yj20258.top/Article/details/gt2ixnrkzhf.html

JS:   this.name = "x";
来源：http://dali.jiagoushi.top/Article/details/gt2inppabdw.html

TS:   name: string = "x";
来源：http://dali.xylfe.cn/Article/details/gt2kigoxmqq.html

Java: private String name;
来源：http://dali.tanke756.top/Article/details/gt2jrjsohfr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gogol.net.cn/Article/details/gt2zgltqzry.html

Ruby: @name = "x"
来源：http://dali.cashguo.top/Article/details/gt2jycugiox.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yanxiufei.cn/Article/details/gt2pncwjhgx.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtxcqhi.html

Py:   def greet(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gt2hqtcnesh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gt2rfifzzvv.html

JS:   greet() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gt2losrjibe.html

TS:   greet(): string { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gt2cgbhcdwv.html

Java: String greet() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gt2gkixlcwp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gt2dcibhtmt.html

Ruby: def greet; @name; end
来源：http://dali.gogol.net.cn/Article/details/gt2wdzrlzjw.html

C#:   public string Greet() => Name;
来源：http://dali.gaohongyu789.top/Article/details/gt2wwcuncqu.html

[G05] 继承
来源：http://dali.daxiang520.top/Article/details/gt2mxeourgf.html

Py:   class Admin(User): pass
来源：http://dali.snrcjt.cn/Article/details/gt2xuhenjat.html

PHP:  class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gt2cndxggym.html

JS:   class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2wpxhxtep.html

TS:   class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gt2egzyasbh.html

Java: class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2olrowrta.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhongyouzk.top/Article/details/gt2gajbqill.html

Ruby: class Admin < User; end
来源：http://dali.yj20258.top/Article/details/gt2vxdzkmyi.html

C#:   class Admin : User {}
来源：http://dali.yj202588.top/Article/details/gt2iwrarssk.html

[G06] 重写方法
来源：http://dali.cqqwz.cn/Article/details/gt2yrahajad.html

Py:   def greet(self): return "admin"
来源：http://dali.cqqwz.cn/Article/details/gt2qkobqhmm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sweek.top/Article/details/gt2rdwwrmjk.html

JS:   greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gt2oovfpluv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gt2mrjjzrbf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2rgceavan.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnqzz.top/Article/details/gt2hvaucbpx.html

Ruby: def greet; "admin"; end
来源：http://dali.gotoacloud.top/Article/details/gt2fhwuvguo.html

C#:   public override string Greet() => "admin";
来源：http://dali.316326.xyz/Article/details/gt2xgwzrjcu.html

[G07] 调用父类方法
来源：http://dali.sweek.top/Article/details/gt2vtjagqua.html

Py:   super().greet()
来源：http://dali.yuxming.cn/Article/details/gt2vxmujzvz.html

PHP:  parent::greet();
来源：http://dali.shzxlz.cn/Article/details/gt2iglcursx.html

JS:   super.greet();
来源：http://dali.wangdashe.top/Article/details/gt2khtgahfm.html

TS:   super.greet();
来源：http://dali.chenlongwang.top/Article/details/gt2rbkoitem.html

Java: super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2lprbxqca.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258.top/Article/details/gt2ioeglffk.html

Ruby: super
来源：http://dali.pycfn.com/Article/details/gt2urlkvpta.html

C#:   base.Greet();
来源：http://dali.aizwys.cn/Article/details/gt2edqwxwke.html

[G08] 静态方法与属性
来源：http://dali.hnxiangtu.top/Article/details/gt2tpzpaedp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gotoacloud.top/Article/details/gt2rzoueobu.html

PHP:  public static function f() {}
来源：http://dali.daxiang520.top/Article/details/gt2spluwiod.html

JS:   static f() {}
来源：http://dali.mhx1999.top/Article/details/gt2hmobyepo.html

TS:   static f(): void {}
来源：http://dali.hnqzz.top/Article/details/gt2mdoxhhdk.html

Java: static void f() {}
来源：http://dali.aibaodan.cn/Article/details/gt2ofvudrtc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.c1oappe.top/Article/details/gt2xufyvkhq.html

Ruby: def self.f; end
来源：http://dali.hammf.cn/Article/details/gt2tnpdkvba.html

C#:   public static void F() {}
来源：http://dali.nanxinkj.top/Article/details/gt2jualuysg.html

[G09] 接口 / 抽象类
来源：http://dali.316326.xyz/Article/details/gt2ympnrhdd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.redwolf501.top/Article/details/gt2ghfyaghs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xinyue.icu/Article/details/gt2fweuncib.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.316326.xyz/Article/details/gt2dzakupxj.html

TS:   interface Shape { area(): number; }
来源：http://dali.birdmap.top/Article/details/gt2fptylcpf.html

Java: interface Shape { double area(); }
来源：http://dali.fengsongda.top/Article/details/gt2fjxgilhn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mrpppuij.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yvedp.cn/Article/details/gt2ugtfcuho.html

C#:   interface IShape { double Area(); }
来源：http://dali.yonumen.top/Article/details/gt2lhnwjpid.html

[G10] 访问控制
来源：http://dali.zhongyouzk.top/Article/details/gt2bxccuekb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tianlin.xyz/Article/details/gt2sywilkpc.html

PHP:  public / protected / private
来源：http://dali.daxiang520.top/Article/details/gt2lsshbdmf.html

JS:   #private 字段；其余公开
来源：http://dali.kuanghao11.cn/Article/details/gt2tjyhmakj.html

TS:   public / protected / private
来源：http://dali.xinyue.icu/Article/details/gt2qmpzreig.html

Java: public / protected / private / 默认包级
来源：http://dali.pengpengdd.cyou/Article/details/gt2jgfgzbrn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xinyue.icu/Article/details/gt2zdxyuikj.html

Ruby: public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gt2hdwwzdyp.html

C#:   public / protected / private / internal
来源：http://dali.daria6918.cn/Article/details/gt2ctbqlxni.html

[G11] getter / setter
来源：http://dali.hfpthk.cn/Article/details/gt2ipggaufi.html

Py:   @property 与 @x.setter
来源：http://dali.0kj1m.cn/Article/details/gt2medhgwni.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gt2pwonneix.html

JS:   get name() { return this._name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oqhseeqz.html

TS:   get name(): string { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2cynuhaje.html

Java: public String getName() { return name; }
来源：http://dali.zycfv.cn/Article/details/gt2kcjbnumu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gt2gvbtvdwr.html

Ruby: attr_accessor :name
来源：http://dali.wangdashe.top/Article/details/gt2fncidhjc.html

C#:   public string Name { get; set; }
来源：http://dali.yj202588.top/Article/details/gt2zyjnjbda.html

[G12] 对象转字符串
来源：http://dali.yj20258.top/Article/details/gt2iasifamc.html

Py:   def __str__(self): return self.name
来源：http://dali.hammf.cn/Article/details/gt2lhmvjorw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2mngkkvvv.html

JS:   toString() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gt2thpepdgg.html

TS:   toString(): string { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gt2noxfesfx.html

Java: @Override public String toString() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gt2xxfhgcsr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qrngtaws.html

Ruby: def to_s; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2guxiawqh.html

C#:   public override string ToString() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gt2yaplwvkn.html

[G13] 判断对象类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2xircahqv.html

Py:   isinstance(u, User)
来源：http://dali.zhixingplan.top/Article/details/gt2fwpzdspi.html

PHP:  $u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gt2tnfhmtbm.html

JS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gt2njdskask.html

TS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gt2jjglunfy.html

Java: u instanceof User
来源：http://dali.meibo888.top/Article/details/gt2crnyixeg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cheryme.top/Article/details/gt2brwbsduy.html

Ruby: u.is_a?(User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bdjhkghl.html

C#:   u is User
来源：http://dali.bjfxy.top/Article/details/gt2gmzafpdy.html

[G14] 数据类 / record
来源：http://dali.316326.xyz/Article/details/gt2zflgskdx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhoulong.xyz/Article/details/gt2rdrwnvox.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.haohaochexian.top/Article/details/gt2botinavm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhixingplan.top/Article/details/gt2xpkitpqx.html

TS:   type User = { name: string; age: number };
来源：http://dali.fengsongda.top/Article/details/gt2swcweqxo.html

Java: record User(String name, int age) {}
来源：http://dali.birdmap.top/Article/details/gt2bmbfidut.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nanxinkj.top/Article/details/gt2lkfnrwwu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.wangshuangyany.cn/Article/details/gt2njokwbnj.html

C#:   record User(string Name, int Age);
来源：http://dali.cucudq.cn/Article/details/gt2nekaenbk.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ymptkojr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jlsjyb.cn/Article/details/gt2pdnlthgu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2rjlotgnc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.feifeiyinyue.top/Article/details/gt2wxgzvutu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daria6918.cn/Article/details/gt2tybjqiqf.html

Java: enum Color { RED, GREEN }
来源：http://dali.jianghu66.top/Article/details/gt2lxxpygxm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenlongwang.top/Article/details/gt2noklswec.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gogol.net.cn/Article/details/gt2pxzuczpg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgufenzy.top/Article/details/gt2ovewjsty.html

[G16] 对象转数组 / 字典
来源：http://dali.sweek.top/Article/details/gt2nbqqpzeg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aibaodan.cn/Article/details/gt2ovvchuad.html

PHP:  get_object_vars($obj);
来源：http://dali.pengpengdd.cyou/Article/details/gt2nfqoyfuy.html

JS:   Object.entries(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2mgyddzzv.html

TS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2kllnwdnf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gaohongyu789.top/Article/details/gt2jtiottln.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2imckvbin.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wjtimtoo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yonumen.top/Article/details/gt2pjbuuaha.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2ippsdgqd.html


<!-- 参考信息 -->