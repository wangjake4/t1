代发 wailian999

[E18] 模板占位符替换
来源：http://dali.yuxming.cn/Article/details/gt2oyqyncee.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hfpthk.cn/Article/details/gt2hjiejczb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jqgfzy.top/Article/details/gt2tnkeeorp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gt2cbdhjrbi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gt2civhqcfo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gt2isxnspsm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gt2gfxiaogh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.meibo888.top/Article/details/gt2xpgwvymb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yuanzhike.top/Article/details/gt2wcxkifdo.html

[E19] 多行文本按行拆分
来源：http://dali.gaohongyu789.top/Article/details/gt2nfzxfnmy.html

Py:   s.splitlines()
来源：http://dali.hywenlv.cn/Article/details/gt2dfcvnggv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tianlin.xyz/Article/details/gt2jzkklxyg.html

JS:   s.split(/\r?\n/)
来源：http://dali.xuanzx.com/Article/details/gt2htcjyigx.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iejchmhy.html

Java: s.lines().toList()
来源：http://dali.fzhhl.top/Article/details/gt2kbowpfux.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuanzx.com/Article/details/gt2bqsqsvdu.html

Ruby: s.lines
来源：http://dali.jyoumei.cn/Article/details/gt2bwjimwbt.html

C#:   s.Split('\n')
来源：http://dali.zhengqikj.top/Article/details/gt2osaxowec.html

[E20] 判断字符串是否为空
来源：http://dali.andypj.xyz/Article/details/gt2xkluxpar.html

Py:   if not s:
来源：http://dali.shangyingyoupin.top/Article/details/gt2eownovsf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.pengpengdd.cyou/Article/details/gt2klcxnvwp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cqqwz.cn/Article/details/gt2qaresuen.html

TS:   if (s === "") {}
来源：http://dali.fengsongda.top/Article/details/gt2gaubiggj.html

Java: if (s.isEmpty()) {}
来源：http://dali.fzhhl.top/Article/details/gt2zqjlicdz.html

Go:   if s == "" {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vqeqypjv.html

Ruby: if s.empty?
来源：http://dali.chenzaomai.com/Article/details/gt2ignhzhdf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2yebopjem.html

[E21] 超长截断加省略号
来源：http://dali.wangshuangyany.cn/Article/details/gt2athujpox.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shzxlz.cn/Article/details/gt2tklshtyj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gt2hfrnxvka.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gt2roapgmpi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gt2jlwrjsui.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gt2pazgxcgb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.daxiang520.top/Article/details/gt2oernaoqt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gt2xzzyodcd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj20258.top/Article/details/gt2wnxazpqa.html

[E22] 字节长度与字符长度
来源：http://dali.andypj.xyz/Article/details/gt2ybvvsmgf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2snqdvwop.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gt2wntodqdl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hammf.cn/Article/details/gt2ibvmxybn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2bzihgkun.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jlsjyb.cn/Article/details/gt2ngsnsmqd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zdqjudy.top/Article/details/gt2yotnsrbx.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuanzx.com/Article/details/gt2keifedvs.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hywenlv.cn/Article/details/gt2behiifei.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2anznjwph.html

F. 文件与目录
来源：http://dali.jinqigufen.top/Article/details/gt2oakqxgeq.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2lxilplat.html

[F01] 读取整个文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2rctlnhdc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.mhx1999.top/Article/details/gt2immckrun.html

PHP:  file_get_contents("a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2gisvaxwg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.bjfxy.top/Article/details/gt2ycjydlpp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mvffwjmm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2hwbqysaa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj20258.top/Article/details/gt2ssaoexjz.html

Ruby: File.read("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2uqbwvetx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2kuxnuhgi.html

[F02] 逐行读取文件
来源：http://dali.gotoacloud.top/Article/details/gt2qgxpthaj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dianchejie.cn/Article/details/gt2mxwudulm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj20258888.top/Article/details/gt2esdnawdy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258888.top/Article/details/gt2fcemtomb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.316326.xyz/Article/details/gt2yfzknjfi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tian-w.cn/Article/details/gt2vqdnfofc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.iojbl.cn/Article/details/gt2uczwxwrg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.quarkkingdee.top/Article/details/gt2prtcgawh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gotoacloud.top/Article/details/gt2turduhzz.html

[F03] 写入文件（覆盖）
来源：http://dali.chenzaomai.com/Article/details/gt2mnhceeoy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2flhmrpun.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.guowangkeji.top/Article/details/gt2dtlgtejs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sthafmjt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gt2dkrspgwo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.smart0.xyz/Article/details/gt2ebnkwnff.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.smart0.xyz/Article/details/gt2rlqryavg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yueranfly.top/Article/details/gt2nvtjcgfg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gt2nnsqbtfo.html

[F04] 追加写入文件
来源：http://dali.yueranfly.top/Article/details/gt2erjzyldc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ivvv.top/Article/details/gt2gvvhnhuy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ppjwa.cn/Article/details/gt2nfeaxiug.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dashuyun.cn/Article/details/gt2efqmfnoe.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gt2isxpjaua.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gotoacloud.top/Article/details/gt2gdighhnz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vmulspam.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinqigfzy.top/Article/details/gt2xtebiegu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zycfv.cn/Article/details/gt2wljrxrdr.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenlongwang.top/Article/details/gt2gcuyfxru.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ajszowzu.html

PHP:  file_exists("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2zbddjobv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2kmykaqll.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2gzlgeqpw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gt2omtverek.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yangfankeji.com/Article/details/gt2herhgikm.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2jjqwrkdt.html

C#:   File.Exists("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2leuicuir.html

[F06] 删除文件
来源：http://dali.tianlin.xyz/Article/details/gt2vvumlyqb.html

Py:   os.remove("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2rtoslien.html

PHP:  unlink("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2prqzfjnk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2fzjsibvm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2vysxzibg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gt2knnnrpjd.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fzxxxxqm.html

Ruby: File.delete("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2xbpcunqm.html

C#:   File.Delete("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2bgkrmyvy.html

[F07] 创建目录（含多级）
来源：http://dali.dianchejie.cn/Article/details/gt2foiveybk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zljqdmtd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.havefunace.top/Article/details/gt2gjixdvrl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gt2ihvyrqfl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gt2yuofhntq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ivvv.top/Article/details/gt2irdirswm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.dianchejie.cn/Article/details/gt2waclntwv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pywpfgxh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhengqikj.top/Article/details/gt2nuvdxrfv.html

[F08] 遍历目录
来源：http://dali.shuidangran.top/Article/details/gt2xnepqqdr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgufenzy.top/Article/details/gt2ylhukwuf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shzxlz.cn/Article/details/gt2lzgjtrpz.html

JS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gt2xgkmfqlo.html

TS:   fs.readdirSync("dir")
来源：http://dali.ivvv.top/Article/details/gt2pcccwvor.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenlongwang.top/Article/details/gt2adkfrreo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yuanzhike.top/Article/details/gt2yhxtnosc.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkywzjp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj20258.top/Article/details/gt2ohxwpvka.html

[F09] 获取文件大小
来源：http://dali.havefunace.top/Article/details/gt2yekuufeb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2dmjekjih.html

PHP:  filesize("a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2pkvqvlod.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gt2wsbrwajc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gt2meseqboi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gt2mmukcnvg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sweek.top/Article/details/gt2usdohomy.html

Ruby: File.size("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2zuhifaea.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuxming.cn/Article/details/gt2krboihic.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nwbrower.top/Article/details/gt2rljmqeun.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2qsacrbrm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2dbmhxegw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gt2cucmwnpm.html

TS:   path.extname("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aaorstpy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangshuangyany.cn/Article/details/gt2cxjdxtta.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2xyigzwvp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2vtwvlvvc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2uzbemcxi.html

[F11] 复制与移动文件
来源：http://dali.hywenlv.cn/Article/details/gt2ewoyohjd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2sufqurky.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2obwtyqfd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2wdovpkrk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gt2dsyyhpuy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yonumen.top/Article/details/gt2eascekit.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.kuanghao11.cn/Article/details/gt2qwejbjil.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gt2jjvhlehf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yonumen.top/Article/details/gt2ivnufvbl.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgbvydb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ppjwa.cn/Article/details/gt2ecnbveji.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangdashe.top/Article/details/gt2rvzsqyuo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.0kj1m.cn/Article/details/gt2wyqeypdj.html

TS:   // 同上
来源：http://dali.havefunace.top/Article/details/gt2mmhugswj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenlongwang.top/Article/details/gt2bpeomwrl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tanke756.top/Article/details/gt2qgbtwjwu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cqqwz.cn/Article/details/gt2dvoawxsk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.kuanghao11.cn/Article/details/gt2psoxbitt.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2nyuyrsyt.html

G. 面向对象
来源：http://dali.hammf.cn/Article/details/gt2tsywcbrv.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2spuqlkgi.html

[G01] 定义类
来源：http://dali.yj20258888.top/Article/details/gt2qfnitwym.html

Py:   class User: pass
来源：http://dali.mhx1999.top/Article/details/gt2pynabuyi.html

PHP:  class User {}
来源：http://dali.cashguo.top/Article/details/gt2jibapmvo.html

JS:   class User {}
来源：http://dali.yuxming.cn/Article/details/gt2rzyjnfox.html

TS:   class User { name: string = ""; }
来源：http://dali.yonumen.top/Article/details/gt2uhalnxmk.html

Java: class User {}
来源：http://dali.nwbrower.top/Article/details/gt2wchkzzqr.html

Go:   type User struct { Name string }
来源：http://dali.jiagoushi.top/Article/details/gt2qovqbukt.html

Ruby: class User; end
来源：http://dali.nanxinkj.top/Article/details/gt2bfookqxm.html

C#:   class User {}
来源：http://dali.snrcjt.cn/Article/details/gt2jobluknw.html

[G02] 构造函数
来源：http://dali.yj20258.top/Article/details/gt2rghdxogh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.0kj1m.cn/Article/details/gt2gvrxeurg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fengsongda.top/Article/details/gt2gzduntpp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ppjwa.cn/Article/details/gt2drmktoix.html

TS:   constructor(public name: string) {}
来源：http://dali.yangfankeji.com/Article/details/gt2dckripdf.html

Java: User(String name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gt2qqwdhrhv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxinkj.top/Article/details/gt2cxjxjnzk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xinyue.icu/Article/details/gt2fajdgnks.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxinkj.top/Article/details/gt2mlqalxyy.html

[G03] 实例属性
来源：http://dali.ybcxt.top/Article/details/gt2cgwktnqu.html

Py:   self.name = "x"
来源：http://dali.yonumen.top/Article/details/gt2crrxkqbx.html

PHP:  public string $name = "x";
来源：http://dali.wangdashe.top/Article/details/gt2vsspnvaz.html

JS:   this.name = "x";
来源：http://dali.sysykeji.top/Article/details/gt2duttcfia.html

TS:   name: string = "x";
来源：http://dali.xinyue.icu/Article/details/gt2kuunjpib.html

Java: private String name;
来源：http://dali.xinyue.icu/Article/details/gt2ptjtzwet.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zycfv.cn/Article/details/gt2uxvnelso.html

Ruby: @name = "x"
来源：http://dali.daxiang520.top/Article/details/gt2jxsyrtqg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.fengsongda.top/Article/details/gt2glppxqyc.html

[G04] 定义方法
来源：http://dali.nanxuanxn.top/Article/details/gt2vhbkiokx.html

Py:   def greet(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gt2armqaiii.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gt2wlgrzpop.html

JS:   greet() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gt2qaqbnllp.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mqopursu.html

Java: String greet() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gt2eplpxoup.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gt2rupjhuco.html

Ruby: def greet; @name; end
来源：http://dali.jqgfzy.top/Article/details/gt2ycwhlire.html

C#:   public string Greet() => Name;
来源：http://dali.daria6918.cn/Article/details/gt2rdmawmcb.html

[G05] 继承
来源：http://dali.zhiwuduotai.top/Article/details/gt2adxyfsxc.html

Py:   class Admin(User): pass
来源：http://dali.wangdashe.top/Article/details/gt2hydizafs.html

PHP:  class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gt2wefungnk.html

JS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gt2ufaexdxc.html

TS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gt2bpwritli.html

Java: class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gt2vrrpyefr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.feifeiyinyue.top/Article/details/gt2tcrlfnqo.html

Ruby: class Admin < User; end
来源：http://dali.sysykeji.top/Article/details/gt2iqrtekky.html

C#:   class Admin : User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2hrcauvmo.html

[G06] 重写方法
来源：http://dali.zhixingplan.top/Article/details/gt2bfgufeyf.html

Py:   def greet(self): return "admin"
来源：http://dali.zycfv.cn/Article/details/gt2qbjwzyin.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gt2dzuiuilj.html

JS:   greet() { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gt2uzxzstmm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ykitwoim.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2qhcslugr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ppjwa.cn/Article/details/gt2ezbtedbg.html

Ruby: def greet; "admin"; end
来源：http://dali.snrcjt.cn/Article/details/gt2ytimmafw.html

C#:   public override string Greet() => "admin";
来源：http://dali.hfpthk.cn/Article/details/gt2wpipoqac.html

[G07] 调用父类方法
来源：http://dali.iojbl.cn/Article/details/gt2rmclypmo.html

Py:   super().greet()
来源：http://dali.aibaodan.cn/Article/details/gt2qviyqnqg.html

PHP:  parent::greet();
来源：http://dali.zhixingplan.top/Article/details/gt2ynpbyycp.html

JS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gt2hkxgljoq.html

TS:   super.greet();
来源：http://dali.9152youxi.cn/Article/details/gt2mazuomqu.html

Java: super.greet();
来源：http://dali.chenlongwang.top/Article/details/gt2pqsblpja.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mbnrcbgc.html

Ruby: super
来源：http://dali.aibaodan.cn/Article/details/gt2ijqswhez.html

C#:   base.Greet();
来源：http://dali.sufxvd.cn/Article/details/gt2rrrkyfzu.html

[G08] 静态方法与属性
来源：http://dali.xylfe.cn/Article/details/gt2hdobzzmm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenlongwang.top/Article/details/gt2gntxotfj.html

PHP:  public static function f() {}
来源：http://dali.sweek.top/Article/details/gt2jptbfywu.html

JS:   static f() {}
来源：http://dali.hywenlv.cn/Article/details/gt2phzgvelf.html

TS:   static f(): void {}
来源：http://dali.cqqwz.cn/Article/details/gt2jshvbtca.html

Java: static void f() {}
来源：http://dali.yonumen.top/Article/details/gt2jiozrbwp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangdashe.top/Article/details/gt2fcrsignw.html

Ruby: def self.f; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xfixwkam.html

C#:   public static void F() {}
来源：http://dali.c1oappe.top/Article/details/gt2dwsvqrdy.html

[G09] 接口 / 抽象类
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tvcfzbue.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yuxming.cn/Article/details/gt2pojbprzl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sufxvd.cn/Article/details/gt2jsvlsglh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.smart0.xyz/Article/details/gt2huohomdg.html

TS:   interface Shape { area(): number; }
来源：http://dali.zycfv.cn/Article/details/gt2ykpydlsq.html

Java: interface Shape { double area(); }
来源：http://dali.nwbrower.top/Article/details/gt2mkkzpmcr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nwbrower.top/Article/details/gt2ewzcxqym.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gogol.net.cn/Article/details/gt2dqpykqym.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2bwmwedxr.html

[G10] 访问控制
来源：http://dali.hywenlv.cn/Article/details/gt2rxgbvcdi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.vqdsnc.cn/Article/details/gt2wbyyjqfc.html

PHP:  public / protected / private
来源：http://dali.andypj.xyz/Article/details/gt2ovopzweu.html

JS:   #private 字段；其余公开
来源：http://dali.smart0.xyz/Article/details/gt2gymtfvyq.html

TS:   public / protected / private
来源：http://dali.yvedp.cn/Article/details/gt2rcfyhsax.html

Java: public / protected / private / 默认包级
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jefrerss.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.316326.xyz/Article/details/gt2gxghqzbi.html

Ruby: public / protected / private
来源：http://dali.cheryme.top/Article/details/gt2cgjcgsff.html

C#:   public / protected / private / internal
来源：http://dali.vqdsnc.cn/Article/details/gt2voklqjpx.html

[G11] getter / setter
来源：http://dali.xylfe.cn/Article/details/gt2vrrqvbih.html

Py:   @property 与 @x.setter
来源：http://dali.jianghu66.top/Article/details/gt2mgttahke.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gt2tkescjke.html

JS:   get name() { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gt2grqacags.html

TS:   get name(): string { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gt2munlwcib.html

Java: public String getName() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gt2vkqqlivc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gt2jrdsitbr.html

Ruby: attr_accessor :name
来源：http://dali.9152youxi.cn/Article/details/gt2rpxyhcxg.html

C#:   public string Name { get; set; }
来源：http://dali.andypj.xyz/Article/details/gt2eaxttedz.html

[G12] 对象转字符串
来源：http://dali.sysykeji.top/Article/details/gt2xorulxmb.html

Py:   def __str__(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gt2xqpauctt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gt2vhvbdhmt.html

JS:   toString() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gt2uveqzekp.html

TS:   toString(): string { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gt2fovgnytb.html

Java: @Override public String toString() { return name; }
来源：http://dali.c1oappe.top/Article/details/gt2nsziadhv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gt2eyxkyind.html

Ruby: def to_s; @name; end
来源：http://dali.smart0.xyz/Article/details/gt2lgzsvaay.html

C#:   public override string ToString() => Name;
来源：http://dali.meibo888.top/Article/details/gt2vfaqqtww.html

[G13] 判断对象类型
来源：http://dali.cdnleiting.top/Article/details/gt2ndyjacyu.html

Py:   isinstance(u, User)
来源：http://dali.shzxlz.cn/Article/details/gt2nhgnyuto.html

PHP:  $u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gt2xrgxvyzr.html

JS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gt2nmipacbg.html

TS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mjwefxdh.html

Java: u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gt2almjpunn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ydzc1.top/Article/details/gt2wrzpuyfi.html

Ruby: u.is_a?(User)
来源：http://dali.dashuyun.cn/Article/details/gt2zlrjghod.html

C#:   u is User
来源：http://dali.zycfv.cn/Article/details/gt2aeporhkk.html

[G14] 数据类 / record
来源：http://dali.nwbrower.top/Article/details/gt2uisikdgq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.316326.xyz/Article/details/gt2larlvmtq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yueranfly.top/Article/details/gt2pdqrleto.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2soxxbvxb.html

TS:   type User = { name: string; age: number };
来源：http://dali.kuanghao11.cn/Article/details/gt2eoanjlig.html

Java: record User(String name, int age) {}
来源：http://dali.gotoacloud.top/Article/details/gt2owvyigwo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.fengsongda.top/Article/details/gt2uynouqxl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.meibo888.top/Article/details/gt2cwefqhef.html

C#:   record User(string Name, int Age);
来源：http://dali.yongpay.top/Article/details/gt2ciiofhow.html

[G15] 枚举
来源：http://dali.shzxlz.cn/Article/details/gt2emnbhund.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sysykeji.top/Article/details/gt2vyufqtyl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2iznjgoir.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigufen.top/Article/details/gt2qsawztie.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.0kj1m.cn/Article/details/gt2qnndkwky.html

Java: enum Color { RED, GREEN }
来源：http://dali.dianchejie.cn/Article/details/gt2vleyifqr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nanxinkj.top/Article/details/gt2btjzdpgx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhiwuduotai.top/Article/details/gt2mnnjthqc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gt2apyzaivi.html

[G16] 对象转数组 / 字典
来源：http://dali.0kj1m.cn/Article/details/gt2blryelwl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxuanxn.top/Article/details/gt2xgmzcqzj.html

PHP:  get_object_vars($obj);
来源：http://dali.snrcjt.cn/Article/details/gt2jlppbynl.html

JS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cwkbxezj.html

TS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gt2exysdlvf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ivvv.top/Article/details/gt2xiqwiter.html


<!-- 参考信息 -->