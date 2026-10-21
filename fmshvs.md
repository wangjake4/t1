代发 wailian999

[E18] 模板占位符替换
来源：http://dali.iojbl.cn/Article/details/gtsnyyjxlg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jlsjyb.cn/Article/details/gtbmomatwb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.svipenyu.cn/Article/details/gtnzfqfvgu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtzwxcjrbu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gthqpvsyng.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtkruvnpwi.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtfuxzzkpj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jqgfzy.top/Article/details/gtcsogxuyv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gzhubu.top/Article/details/gttsxwgvav.html

[E19] 多行文本按行拆分
来源：http://dali.nanxinkj.top/Article/details/gtfrfkjlum.html

Py:   s.splitlines()
来源：http://dali.tianlin.xyz/Article/details/gtkhovsdqx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xuanzx.com/Article/details/gtayqvwwhs.html

JS:   s.split(/\r?\n/)
来源：http://dali.shuidangran.top/Article/details/gtyrbkhrqm.html

TS:   s.split(/\r?\n/)
来源：http://dali.yonumen.top/Article/details/gthxnouxag.html

Java: s.lines().toList()
来源：http://dali.hfpthk.cn/Article/details/gteukwcnpb.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhengqikj.top/Article/details/gtxxdwuybm.html

Ruby: s.lines
来源：http://dali.hnxiangtu.top/Article/details/gtpvjuahar.html

C#:   s.Split('\n')
来源：http://dali.nanxuanxn.top/Article/details/gtjaygrodb.html

[E20] 判断字符串是否为空
来源：http://dali.shangyingyoupin.top/Article/details/gtfeusgphs.html

Py:   if not s:
来源：http://dali.yongpay.top/Article/details/gtygufhprf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nwbrower.top/Article/details/gticmzhbwi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.daria6918.cn/Article/details/gtczbkxdej.html

TS:   if (s === "") {}
来源：http://dali.smart0.xyz/Article/details/gttsbkddzi.html

Java: if (s.isEmpty()) {}
来源：http://dali.aizwys.cn/Article/details/gtewrnyica.html

Go:   if s == "" {}
来源：http://dali.snrcjt.cn/Article/details/gtbxgeceow.html

Ruby: if s.empty?
来源：http://dali.cheryme.top/Article/details/gtqjmdixmm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sweek.top/Article/details/gtjryxloxs.html

[E21] 超长截断加省略号
来源：http://dali.jyoumei.cn/Article/details/gtzckffexp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nwbrower.top/Article/details/gtfnjprmhf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gtqqdisozi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtusifvvqw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtizmayrcm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtewwfeqoo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hongshengwenyu.top/Article/details/gtmmvjbqoz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gtqqhucpdm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtqhpkyras.html

[E22] 字节长度与字符长度
来源：http://dali.yueranfly.top/Article/details/gtvgbjqrro.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gaohongyu789.top/Article/details/gtadwyuylt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtkkngltcm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cashguo.top/Article/details/gtwehndfrt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuxming.cn/Article/details/gtvexbiuit.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gotoacloud.top/Article/details/gthotvwwez.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.kuanghao11.cn/Article/details/gtjdemffhs.html

Ruby: s.bytesize;  s.length
来源：http://dali.cashguo.top/Article/details/gtqkdhfhhu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.quarkkingdee.top/Article/details/gteqtoxctf.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtmballppo.html

F. 文件与目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtduospsmj.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtksrnvsjo.html

[F01] 读取整个文件
来源：http://dali.yvedp.cn/Article/details/gtvdtodkdu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.vqdsnc.cn/Article/details/gtdhcrsqrr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtcbvthwqc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.mhx1999.top/Article/details/gtodvlefkf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtwbvvhzvh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtsjmmjoeu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.dashuyun.cn/Article/details/gtvglkrgdb.html

Ruby: File.read("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gttldefxsp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtboghpgft.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gtmmhasxrb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xinyue.icu/Article/details/gtcecnqtgq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zycfv.cn/Article/details/gtfxrjuooa.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sysykeji.top/Article/details/gtfeabmiai.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gtwijwgtol.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gtlmtytoov.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guowangkeji.top/Article/details/gtyaprdard.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttlzhudjy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daxiang520.top/Article/details/gtrffmqdcy.html

[F03] 写入文件（覆盖）
来源：http://dali.yonumen.top/Article/details/gtjyanmrrk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhengqikj.top/Article/details/gtpwegavqh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cucudq.cn/Article/details/gtdzgkpwtt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gtmkybfllx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.havefunace.top/Article/details/gtfvrcoblq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.dashuyun.cn/Article/details/gtybcozwvs.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cashguo.top/Article/details/gtyouvfryt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.dianchejie.cn/Article/details/gtpzmqahzo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hysaishi.cn/Article/details/gtythtawih.html

[F04] 追加写入文件
来源：http://dali.sxryk.cn/Article/details/gtzqtuvyjw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvopjijt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinqigfzy.top/Article/details/gtnucybrgh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ehwqpu.com/Article/details/gtpiqltghm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ybcxt.top/Article/details/gtqagadwuk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sysykeji.top/Article/details/gtjzsxqvci.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.havefunace.top/Article/details/gtlazpvxqg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.c1oappe.top/Article/details/gtscptyvrf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jqgufenzy.top/Article/details/gtdwxhkyzw.html

[F05] 判断文件或目录是否存在
来源：http://dali.kuanghao11.cn/Article/details/gtpoipuzna.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jqgufenzy.top/Article/details/gtnhpovxwm.html

PHP:  file_exists("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtrgsgmflo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtgtqjicls.html

TS:   fs.existsSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtjiacbbpu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtuigdjets.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.316326.xyz/Article/details/gtmcmprrqx.html

Ruby: File.exist?("a.txt")
来源：http://dali.cheryme.top/Article/details/gtyymuwkon.html

C#:   File.Exists("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtcsupmook.html

[F06] 删除文件
来源：http://dali.hywenlv.cn/Article/details/gtzrxvjedo.html

Py:   os.remove("a.txt")
来源：http://dali.bjfxy.top/Article/details/gttgfawatf.html

PHP:  unlink("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtkqofzhzv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtkotkyvmo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtforbsdqx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtffbpxezu.html

Go:   os.Remove("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtlglavnxd.html

Ruby: File.delete("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gttvyshjix.html

C#:   File.Delete("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspfifqnq.html

[F07] 创建目录（含多级）
来源：http://dali.xuanzx.com/Article/details/gtxfdduvzh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tianlin.xyz/Article/details/gtybsfaqjm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgfzy.top/Article/details/gtluwznoor.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.haohaochexian.top/Article/details/gtscumhuzi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gtskgpwagj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenzaomai.com/Article/details/gtyxkoaxgj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tanke756.top/Article/details/gtapiqwukq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhongyouzk.top/Article/details/gtypwfmbjp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzogqivjb.html

[F08] 遍历目录
来源：http://dali.cqqwz.cn/Article/details/gtceyxdvgz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgfzy.top/Article/details/gtughazeze.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenzaomai.com/Article/details/gtiimrnhjc.html

JS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gtjhhpywsd.html

TS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gtasauzcyf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gtlxvexjri.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yongpay.top/Article/details/gtypwyupil.html

Ruby: Dir.children("dir")
来源：http://dali.andypj.xyz/Article/details/gtnocxmcvk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.bjfxy.top/Article/details/gtlgjmkjpv.html

[F09] 获取文件大小
来源：http://dali.dashuyun.cn/Article/details/gtoraxvftl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtuzxtrvgx.html

PHP:  filesize("a.txt");
来源：http://dali.havefunace.top/Article/details/gtntusyjud.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcgpccqni.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aibaodan.cn/Article/details/gtuzndluzq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtnyqubfxl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.mhx1999.top/Article/details/gtpnxiuquz.html

Ruby: File.size("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtzabziihv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwygpwdst.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jlsjyb.cn/Article/details/gtxxbgsojt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtczqvphfg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.iojbl.cn/Article/details/gtesszxjdb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtydapimih.html

TS:   path.extname("a.txt")
来源：http://dali.yj202588.top/Article/details/gtvaskerdo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xinyue.icu/Article/details/gtrxssdvsq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtslyhdraq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtovjvuylf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtidpybxpv.html

[F11] 复制与移动文件
来源：http://dali.cheryme.top/Article/details/gtrzlmgoux.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtaafaywzg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sysykeji.top/Article/details/gtlqnnkncz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtpahpugel.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtkuzddthu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guannengcc.top/Article/details/gtzsajhwql.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jlsjyb.cn/Article/details/gtujwusbcn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtqerlsodh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sxryk.cn/Article/details/gtdhhxkwpw.html

[F12] CSV 读写
来源：http://dali.xuanzx.com/Article/details/gtcmunfdlz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hnxiangtu.top/Article/details/gtbapttgoi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtksvzmlsp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxinkj.top/Article/details/gtrqqdfmwr.html

TS:   // 同上
来源：http://dali.dianchejie.cn/Article/details/gtnzltfpqs.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cdnleiting.top/Article/details/gtuaumhafp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.c1oappe.top/Article/details/gtdhuxprtg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigufen.top/Article/details/gtawtkothd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.daxiang520.top/Article/details/gtctctpmqt.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtgesciicy.html

G. 面向对象
来源：http://dali.jianghu66.top/Article/details/gtsapyalxr.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtrnidrxjv.html

[G01] 定义类
来源：http://dali.cdnleiting.top/Article/details/gtwwfvxqup.html

Py:   class User: pass
来源：http://dali.wangshuangyany.cn/Article/details/gtdmrqcaey.html

PHP:  class User {}
来源：http://dali.dianchejie.cn/Article/details/gtwxaxzjjt.html

JS:   class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtftnsetkh.html

TS:   class User { name: string = ""; }
来源：http://dali.hongshengwenyu.top/Article/details/gtpozqjynl.html

Java: class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtutxfrbkc.html

Go:   type User struct { Name string }
来源：http://dali.kuanghao11.cn/Article/details/gtxpuborao.html

Ruby: class User; end
来源：http://dali.daria6918.cn/Article/details/gteliojwsm.html

C#:   class User {}
来源：http://dali.havefunace.top/Article/details/gtjtjatvfo.html

[G02] 构造函数
来源：http://dali.zhoulong.xyz/Article/details/gteelahcbe.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.316326.xyz/Article/details/gthgzctzuh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.pycfn.com/Article/details/gtalwjaqhg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtdxailuqf.html

TS:   constructor(public name: string) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlzewhpaj.html

Java: User(String name) { this.name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtvmofvugi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.svipenyu.cn/Article/details/gtjwnybqdb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fzhhl.top/Article/details/gtfhsixulm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.bjfxy.top/Article/details/gtyiisbold.html

[G03] 实例属性
来源：http://dali.yuanzhike.top/Article/details/gtkuhbipjn.html

Py:   self.name = "x"
来源：http://dali.hysaishi.cn/Article/details/gtlladhmdn.html

PHP:  public string $name = "x";
来源：http://dali.chenlongwang.top/Article/details/gtxglyqqfn.html

JS:   this.name = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbeoxeei.html

TS:   name: string = "x";
来源：http://dali.birdmap.top/Article/details/gthrcyoirj.html

Java: private String name;
来源：http://dali.shuidangran.top/Article/details/gtpgvvgpqf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj202588.top/Article/details/gtvweooejc.html

Ruby: @name = "x"
来源：http://dali.shzxlz.cn/Article/details/gttafwdemb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtqlimjlag.html

[G04] 定义方法
来源：http://dali.hnxiangtu.top/Article/details/gtnjoxbwlc.html

Py:   def greet(self): return self.name
来源：http://dali.quarkkingdee.top/Article/details/gtvcwhinqf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gtvgclkjer.html

JS:   greet() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtlopjchwc.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtsujjctex.html

Java: String greet() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtvvzaaxqw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtwnxucgcb.html

Ruby: def greet; @name; end
来源：http://dali.gogol.net.cn/Article/details/gtgidntbky.html

C#:   public string Greet() => Name;
来源：http://dali.dashuyun.cn/Article/details/gtgvwumnrl.html

[G05] 继承
来源：http://dali.daxiang520.top/Article/details/gtqljkzgko.html

Py:   class Admin(User): pass
来源：http://dali.hfpthk.cn/Article/details/gtdvpfigbs.html

PHP:  class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtwzvjslqw.html

JS:   class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtkabhpzdw.html

TS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtziujiykq.html

Java: class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtmqpxbupg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfzdelokc.html

Ruby: class Admin < User; end
来源：http://dali.haohaochexian.top/Article/details/gtmsxfhkor.html

C#:   class Admin : User {}
来源：http://dali.quarkkingdee.top/Article/details/gtcmnielbq.html

[G06] 重写方法
来源：http://dali.yueranfly.top/Article/details/gtrsybtnfj.html

Py:   def greet(self): return "admin"
来源：http://dali.wangshuangyany.cn/Article/details/gtypsycpnk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtmvilcuef.html

JS:   greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtmtddanwp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtkkwhglzm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtsskfzjam.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pycfn.com/Article/details/gtnotydrax.html

Ruby: def greet; "admin"; end
来源：http://dali.sweek.top/Article/details/gtrpwqwhqy.html

C#:   public override string Greet() => "admin";
来源：http://dali.gogol.net.cn/Article/details/gtuscvtoto.html

[G07] 调用父类方法
来源：http://dali.sufxvd.cn/Article/details/gtkpsxxodx.html

Py:   super().greet()
来源：http://dali.pengpengdd.cyou/Article/details/gtmktgvcug.html

PHP:  parent::greet();
来源：http://dali.zhoulong.xyz/Article/details/gtbxdoonrl.html

JS:   super.greet();
来源：http://dali.birdmap.top/Article/details/gtqyqszsjt.html

TS:   super.greet();
来源：http://dali.snrcjt.cn/Article/details/gttwutncvk.html

Java: super.greet();
来源：http://dali.shzxlz.cn/Article/details/gttwsbsuym.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.svipenyu.cn/Article/details/gtdebsfpdv.html

Ruby: super
来源：http://dali.zhengqikj.top/Article/details/gtmhrrloqw.html

C#:   base.Greet();
来源：http://dali.aibaodan.cn/Article/details/gtalxsnupz.html

[G08] 静态方法与属性
来源：http://dali.zycfv.cn/Article/details/gtzojcwzwx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gogol.net.cn/Article/details/gtuidiwzls.html

PHP:  public static function f() {}
来源：http://dali.quarkkingdee.top/Article/details/gtprpidqmt.html

JS:   static f() {}
来源：http://dali.jianghu66.top/Article/details/gtxgmkazpl.html

TS:   static f(): void {}
来源：http://dali.ydzc1.top/Article/details/gtrqcugabc.html

Java: static void f() {}
来源：http://dali.svipenyu.cn/Article/details/gtuxakrbig.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhengqikj.top/Article/details/gtninfkyrd.html

Ruby: def self.f; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtghftiaig.html

C#:   public static void F() {}
来源：http://dali.ppjwa.cn/Article/details/gttnuiuchb.html

[G09] 接口 / 抽象类
来源：http://dali.sxryk.cn/Article/details/gtmkvvtygr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.smart0.xyz/Article/details/gtukqecexr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhixingplan.top/Article/details/gtmyekqnci.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhiwuduotai.top/Article/details/gtvxgjilyd.html

TS:   interface Shape { area(): number; }
来源：http://dali.hywenlv.cn/Article/details/gtuydwivvi.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258888.top/Article/details/gtujvpymtp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtviqpejeh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj202588.top/Article/details/gtauqwrswq.html

C#:   interface IShape { double Area(); }
来源：http://dali.tanke756.top/Article/details/gtnzlfhzfc.html

[G10] 访问控制
来源：http://dali.iojbl.cn/Article/details/gtfailnwse.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hnxiangtu.top/Article/details/gtnzimysoe.html

PHP:  public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gtoppatyqv.html

JS:   #private 字段；其余公开
来源：http://dali.zhiwuduotai.top/Article/details/gtiqhwjwfb.html

TS:   public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gtlbohnqgn.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhbeaybz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.haohaochexian.top/Article/details/gteeozfndr.html

Ruby: public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gtzznhemge.html

C#:   public / protected / private / internal
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdztxukk.html

[G11] getter / setter
来源：http://dali.dashuyun.cn/Article/details/gtjmauaezb.html

Py:   @property 与 @x.setter
来源：http://dali.chenjidiqi.icu/Article/details/gtomklgduc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gttrdgigeq.html

JS:   get name() { return this._name; }
来源：http://dali.cashguo.top/Article/details/gtpjmdxqua.html

TS:   get name(): string { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtltvyihbt.html

Java: public String getName() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtogoqoesj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtyxtlwtav.html

Ruby: attr_accessor :name
来源：http://dali.jinqigfzy.top/Article/details/gtuizmeglq.html

C#:   public string Name { get; set; }
来源：http://dali.chenjidiqi.icu/Article/details/gtbzmazncw.html

[G12] 对象转字符串
来源：http://dali.haohaochexian.top/Article/details/gtzekjzxwo.html

Py:   def __str__(self): return self.name
来源：http://dali.yueranfly.top/Article/details/gtzbfchtxr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gtkqoyuipq.html

JS:   toString() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtekxbgixq.html

TS:   toString(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtnqusjncf.html

Java: @Override public String toString() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtmwwosagu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtvvxhrrhs.html

Ruby: def to_s; @name; end
来源：http://dali.ybcxt.top/Article/details/gtpqiidemh.html

C#:   public override string ToString() => Name;
来源：http://dali.sxryk.cn/Article/details/gtpskftvtb.html

[G13] 判断对象类型
来源：http://dali.xinyue.icu/Article/details/gtzheucxaa.html

Py:   isinstance(u, User)
来源：http://dali.xinyue.icu/Article/details/gtvdheagob.html

PHP:  $u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtfgyvucef.html

JS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gtfyfzfjap.html

TS:   u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtnlxczqsl.html

Java: u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtmxglzteq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jlsjyb.cn/Article/details/gtimnihkeg.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gtciwwbthc.html

C#:   u is User
来源：http://dali.dianchejie.cn/Article/details/gtujrihtcw.html

[G14] 数据类 / record
来源：http://dali.cdnleiting.top/Article/details/gtibqydmke.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj202588.top/Article/details/gtnjqjpmfq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangtech.top/Article/details/gtjpfvumia.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nanxinkj.top/Article/details/gtqszaqkdt.html

TS:   type User = { name: string; age: number };
来源：http://dali.cashguo.top/Article/details/gtoohudycg.html

Java: record User(String name, int age) {}
来源：http://dali.aibaodan.cn/Article/details/gtoctqnuwa.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjdiotkw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenlongwang.top/Article/details/gtlkuasiqg.html

C#:   record User(string Name, int Age);
来源：http://dali.vqdsnc.cn/Article/details/gtojsxkstd.html

[G15] 枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrndqswfn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hysaishi.cn/Article/details/gtrtaznqkt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zdqjudy.top/Article/details/gtekgdwjte.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ydzc1.top/Article/details/gtbwfiqpyv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gtlfoymtdy.html

Java: enum Color { RED, GREEN }
来源：http://dali.ehwqpu.com/Article/details/gtbheqmzja.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tianlin.xyz/Article/details/gtqmivuejr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aibaodan.cn/Article/details/gtktlnhfnb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtkaphlepk.html

[G16] 对象转数组 / 字典
来源：http://dali.9152youxi.cn/Article/details/gtkvpcnctk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xuanzx.com/Article/details/gtwcfuymqf.html

PHP:  get_object_vars($obj);
来源：http://dali.cdnleiting.top/Article/details/gtreycnuov.html

JS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gthptqnrse.html

TS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnacugskw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenlongwang.top/Article/details/gtpqtnbdfq.html


<!-- 参考信息 -->