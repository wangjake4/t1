代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fmjputkd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gt2cgzmyhht.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gt2awrpnlfe.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sufxvd.cn/Article/details/gt2ulvxsqng.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yangfankeji.com/Article/details/gt2hccilzhk.html

[E19] 多行文本按行拆分
来源：http://dali.gogol.net.cn/Article/details/gt2vihovlij.html

Py:   s.splitlines()
来源：http://dali.hysaishi.cn/Article/details/gt2vypotkso.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.bjfxy.top/Article/details/gt2yvqpupph.html

JS:   s.split(/\r?\n/)
来源：http://dali.quarkkingdee.top/Article/details/gt2gobexktw.html

TS:   s.split(/\r?\n/)
来源：http://dali.cqqwz.cn/Article/details/gt2wxqgldcg.html

Java: s.lines().toList()
来源：http://dali.bjfxy.top/Article/details/gt2laxrqojf.html

Go:   strings.Split(s, "\n")
来源：http://dali.redwolf501.top/Article/details/gt2otlrxmny.html

Ruby: s.lines
来源：http://dali.havefunace.top/Article/details/gt2rctlgvje.html

C#:   s.Split('\n')
来源：http://dali.fengsongda.top/Article/details/gt2gcdyzzop.html

[E20] 判断字符串是否为空
来源：http://dali.guowangkeji.top/Article/details/gt2beqmwoyd.html

Py:   if not s:
来源：http://dali.guowangkeji.top/Article/details/gt2rgehmdtw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.aizwys.cn/Article/details/gt2jxmryjyo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2ilqpzebv.html

TS:   if (s === "") {}
来源：http://dali.daria6918.cn/Article/details/gt2fwucudyk.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gt2fzuedbig.html

Go:   if s == "" {}
来源：http://dali.kuanghao11.cn/Article/details/gt2blvvfclz.html

Ruby: if s.empty?
来源：http://dali.aizwys.cn/Article/details/gt2irmgmbaw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aibaodan.cn/Article/details/gt2sqfvsrwt.html

[E21] 超长截断加省略号
来源：http://dali.nwbrower.top/Article/details/gt2gxbftwgz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.dashuyun.cn/Article/details/gt2cixogojd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tanke756.top/Article/details/gt2chnelhga.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gt2xxhrdpuh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gt2lmcjjnon.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gt2nsvtoefl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ydzc1.top/Article/details/gt2mnmaejwe.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gt2radyllpp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.fengsongda.top/Article/details/gt2gyjejuvr.html

[E22] 字节长度与字符长度
来源：http://dali.redwolf501.top/Article/details/gt2ejkghljw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dpksmnsw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gt2leayihrx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.haohaochexian.top/Article/details/gt2jfqkpgxx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aizwys.cn/Article/details/gt2btiuzjgd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aibaodan.cn/Article/details/gt2pdvieqyf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ybcxt.top/Article/details/gt2fufecbkb.html

Ruby: s.bytesize;  s.length
来源：http://dali.tianlin.xyz/Article/details/gt2kdztyobn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nwbrower.top/Article/details/gt2geqcsdus.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2htjxkupo.html

F. 文件与目录
来源：http://dali.pengpengdd.cyou/Article/details/gt2tlaanfhb.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2ishhwtsk.html

[F01] 读取整个文件
来源：http://dali.c1oappe.top/Article/details/gt2vevthjhq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhengqikj.top/Article/details/gt2uctzeign.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2cgwcmulu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dashuyun.cn/Article/details/gt2rmooqube.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gt2zzeseayr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gt2lbqluifp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nanxuanxn.top/Article/details/gt2qxtuhxbb.html

Ruby: File.read("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2aufvawmp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2iayaemxc.html

[F02] 逐行读取文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2qwaxgmjh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.c1oappe.top/Article/details/gt2iezbvazi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.haohaochexian.top/Article/details/gt2rpleyyvh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2vzgaerzb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2iubqfncy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gt2ehblmrux.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.bjfxy.top/Article/details/gt2hfisbudq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhoulong.xyz/Article/details/gt2qysyidxr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gaohongyu789.top/Article/details/gt2addjreuy.html

[F03] 写入文件（覆盖）
来源：http://dali.kuanghao11.cn/Article/details/gt2vapqqnil.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yuanzhike.top/Article/details/gt2xcavlbqt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gt2sfpwfnbg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gt2ruawlxut.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gt2popknona.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gaohongyu789.top/Article/details/gt2qmznuzyr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuanzhike.top/Article/details/gt2rmxhxcug.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.daxiang520.top/Article/details/gt2bgvytkuq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yuxming.cn/Article/details/gt2mzjxmxzg.html

[F04] 追加写入文件
来源：http://dali.chenlongwang.top/Article/details/gt2abpplnzu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fzhhl.top/Article/details/gt2latmzhxz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yongpay.top/Article/details/gt2gprhnair.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xinyue.icu/Article/details/gt2ezvnvmyk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2uexnbxjn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yongpay.top/Article/details/gt2zkchwbao.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.fengsongda.top/Article/details/gt2hliqgsnb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yanxiufei.cn/Article/details/gt2toyhptdz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.haohaochexian.top/Article/details/gt2zegvzljq.html

[F05] 判断文件或目录是否存在
来源：http://dali.9152youxi.cn/Article/details/gt2tvrsdttp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.pycfn.com/Article/details/gt2ybcjhkxl.html

PHP:  file_exists("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2cqewncjp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2xpsrqfas.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2hhlztrji.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gt2egahxdks.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ppjwa.cn/Article/details/gt2ksctddfc.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2cbanlcwb.html

C#:   File.Exists("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2fkxrirhg.html

[F06] 删除文件
来源：http://dali.ydzc1.top/Article/details/gt2sfdeivgp.html

Py:   os.remove("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2regapptq.html

PHP:  unlink("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mxenorpn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2cxluwquk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2houjmabe.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gt2lmukwsgo.html

Go:   os.Remove("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2plrtgdfp.html

Ruby: File.delete("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2evtbuuon.html

C#:   File.Delete("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2qimqgvdr.html

[F07] 创建目录（含多级）
来源：http://dali.andypj.xyz/Article/details/gt2zsunwxcp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhoulong.xyz/Article/details/gt2tjyutgkz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yvedp.cn/Article/details/gt2xmaywute.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gt2avdnbevv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ckpbfjgm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgufenzy.top/Article/details/gt2wuuzoeta.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hwxyyvbj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gaohongyu789.top/Article/details/gt2givwtxbp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aizwys.cn/Article/details/gt2ayxxxeof.html

[F08] 遍历目录
来源：http://dali.yueranfly.top/Article/details/gt2fscufqpx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.316326.xyz/Article/details/gt2aiyageiz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shuidangran.top/Article/details/gt2ltkensex.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gt2xyfdcvap.html

TS:   fs.readdirSync("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gt2oceakkqn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gt2bxkjnyrs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gt2pxdqqxaz.html

Ruby: Dir.children("dir")
来源：http://dali.gzhubu.top/Article/details/gt2ynyzikdt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.meibo888.top/Article/details/gt2rfdjzcis.html

[F09] 获取文件大小
来源：http://dali.gzhubu.top/Article/details/gt2fvcgpoil.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2vznvvklx.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2faiwxpku.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qpjspove.html

TS:   fs.statSync("a.txt").size
来源：http://dali.dianchejie.cn/Article/details/gt2upaxmscb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gt2wqloaiyw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hammf.cn/Article/details/gt2lemyjppt.html

Ruby: File.size("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2xdmpguhu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinqigfzy.top/Article/details/gt2ebwihqwc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tianlin.xyz/Article/details/gt2ebnzzhdb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2rduulhmq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2dkozdpgt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2qfceumng.html

TS:   path.extname("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2mwufmoob.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.daxiang520.top/Article/details/gt2yshujfzv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2wiwuhgjz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2dboloiey.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gt2grwiglrm.html

[F11] 复制与移动文件
来源：http://dali.daxiang520.top/Article/details/gt2pdpvlmpb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gt2igxpnwxu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zycfv.cn/Article/details/gt2yotyhchq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gt2pdcorjof.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gt2vnnzpoxp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.9152youxi.cn/Article/details/gt2bhxsntzu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.svipenyu.cn/Article/details/gt2rrwnpbbr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gt2pzlsnwhb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tianlin.xyz/Article/details/gt2kzekbcux.html

[F12] CSV 读写
来源：http://dali.chenlongwang.top/Article/details/gt2hvcgntie.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fexpnzjg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenjidiqi.icu/Article/details/gt2wdzpccwn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj202588.top/Article/details/gt2xuukowyz.html

TS:   // 同上
来源：http://dali.svipenyu.cn/Article/details/gt2kmxzunpz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ppjwa.cn/Article/details/gt2kfbyghui.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pengpengdd.cyou/Article/details/gt2cqefzmnw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gaohongyu789.top/Article/details/gt2pjbvyzkn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zievocbw.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2sxxoprqw.html

G. 面向对象
来源：http://dali.zycfv.cn/Article/details/gt2cuankrll.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kmhgskfm.html

[G01] 定义类
来源：http://dali.fzhhl.top/Article/details/gt2hdxuqusg.html

Py:   class User: pass
来源：http://dali.xziqi.cn/Article/details/gt2hjebhfrk.html

PHP:  class User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2pbkqcdkz.html

JS:   class User {}
来源：http://dali.andypj.xyz/Article/details/gt2osthfkdl.html

TS:   class User { name: string = ""; }
来源：http://dali.hywenlv.cn/Article/details/gt2ywirqedo.html

Java: class User {}
来源：http://dali.tian-w.cn/Article/details/gt2gmpifmut.html

Go:   type User struct { Name string }
来源：http://dali.hfpthk.cn/Article/details/gt2mguffcmg.html

Ruby: class User; end
来源：http://dali.0kj1m.cn/Article/details/gt2rrgtougr.html

C#:   class User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2jumuyslp.html

[G02] 构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cesbnjid.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yuxming.cn/Article/details/gt2ffsfdsie.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yvedp.cn/Article/details/gt2heertzry.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2sorbcnta.html

TS:   constructor(public name: string) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2aibcqtth.html

Java: User(String name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gt2pthrwwic.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yanxiufei.cn/Article/details/gt2qbwzoqpr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gzhubu.top/Article/details/gt2msbonbvm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2uufjyuvs.html

[G03] 实例属性
来源：http://dali.meibo888.top/Article/details/gt2eaxrbjla.html

Py:   self.name = "x"
来源：http://dali.zdqjudy.top/Article/details/gt2aqlikddl.html

PHP:  public string $name = "x";
来源：http://dali.nwbrower.top/Article/details/gt2nliemoqf.html

JS:   this.name = "x";
来源：http://dali.jyoumei.cn/Article/details/gt2yxdlcbin.html

TS:   name: string = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gt2bvrtocvk.html

Java: private String name;
来源：http://dali.jinqigfzy.top/Article/details/gt2fksukomv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangshuangyany.cn/Article/details/gt2pwyruidz.html

Ruby: @name = "x"
来源：http://dali.yuxming.cn/Article/details/gt2boulfrjn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.andypj.xyz/Article/details/gt2lzunueus.html

[G04] 定义方法
来源：http://dali.hfpthk.cn/Article/details/gt2srudjlst.html

Py:   def greet(self): return self.name
来源：http://dali.sysykeji.top/Article/details/gt2rvzejerc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ypdohmjx.html

JS:   greet() { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gt2swqhthjv.html

TS:   greet(): string { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gt2fyjtadmo.html

Java: String greet() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gt2wyvzimaj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jzozysxv.html

Ruby: def greet; @name; end
来源：http://dali.jyoumei.cn/Article/details/gt2hfacdwio.html

C#:   public string Greet() => Name;
来源：http://dali.xuanzx.com/Article/details/gt2hejsmlpv.html

[G05] 继承
来源：http://dali.chenlongwang.top/Article/details/gt2doalxrmx.html

Py:   class Admin(User): pass
来源：http://dali.smart0.xyz/Article/details/gt2izudkrtq.html

PHP:  class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2pxghpxky.html

JS:   class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gt2elkschoz.html

TS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2qbelqimr.html

Java: class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2pxvkkkru.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.havefunace.top/Article/details/gt2klohgmcz.html

Ruby: class Admin < User; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2gixwvqkb.html

C#:   class Admin : User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2svvckeky.html

[G06] 重写方法
来源：http://dali.pycfn.com/Article/details/gt2ewnyiiod.html

Py:   def greet(self): return "admin"
来源：http://dali.gzhubu.top/Article/details/gt2rwuqeaqe.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gt2rzhwbdes.html

JS:   greet() { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gt2vvsotbjw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gt2plxuqahz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gt2wgzrnato.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cashguo.top/Article/details/gt2qsqbypyb.html

Ruby: def greet; "admin"; end
来源：http://dali.yongpay.top/Article/details/gt2yxxkviss.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhiwuduotai.top/Article/details/gt2loptdxsd.html

[G07] 调用父类方法
来源：http://dali.xinyue.icu/Article/details/gt2bklkstyi.html

Py:   super().greet()
来源：http://dali.cdnleiting.top/Article/details/gt2ohyzddbn.html

PHP:  parent::greet();
来源：http://dali.yueranfly.top/Article/details/gt2dfylcgzv.html

JS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gt2qgxdjezs.html

TS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jeljmxuz.html

Java: super.greet();
来源：http://dali.xylfe.cn/Article/details/gt2mjuxbsly.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.guannengcc.top/Article/details/gt2qskgaapw.html

Ruby: super
来源：http://dali.cashguo.top/Article/details/gt2xyawdudu.html

C#:   base.Greet();
来源：http://dali.shzxlz.cn/Article/details/gt2lgjtgzpv.html

[G08] 静态方法与属性
来源：http://dali.redwolf501.top/Article/details/gt2idrbregk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenjidiqi.icu/Article/details/gt2sfsujkcz.html

PHP:  public static function f() {}
来源：http://dali.jinqigfzy.top/Article/details/gt2kpsuhhoo.html

JS:   static f() {}
来源：http://dali.meibo888.top/Article/details/gt2khjcajof.html

TS:   static f(): void {}
来源：http://dali.316326.xyz/Article/details/gt2bbzgvnhy.html

Java: static void f() {}
来源：http://dali.cdnleiting.top/Article/details/gt2jkhaejdl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xziqi.cn/Article/details/gt2tskgeyih.html

Ruby: def self.f; end
来源：http://dali.nanxuanxn.top/Article/details/gt2uiliwego.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2agbvbsty.html

[G09] 接口 / 抽象类
来源：http://dali.gzhubu.top/Article/details/gt2xotiukeh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj202588.top/Article/details/gt2sdjhhfmf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yongpay.top/Article/details/gt2qeumwkds.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cqqwz.cn/Article/details/gt2kspklakh.html

TS:   interface Shape { area(): number; }
来源：http://dali.daxiang520.top/Article/details/gt2ztwbwmqi.html

Java: interface Shape { double area(); }
来源：http://dali.havefunace.top/Article/details/gt2fblllifa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.bjfxy.top/Article/details/gt2ptbapllw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yvedp.cn/Article/details/gt2fncchigj.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2zsdinuyx.html

[G10] 访问控制
来源：http://dali.316326.xyz/Article/details/gt2obvowcyv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.redwolf501.top/Article/details/gt2tyhuvgvf.html

PHP:  public / protected / private
来源：http://dali.daria6918.cn/Article/details/gt2zasztsze.html

JS:   #private 字段；其余公开
来源：http://dali.gogol.net.cn/Article/details/gt2qgkqbdfb.html

TS:   public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gt2hbwbkfph.html

Java: public / protected / private / 默认包级
来源：http://dali.redwolf501.top/Article/details/gt2lqtetijn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daxiang520.top/Article/details/gt2adrvibor.html

Ruby: public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gt2ydwctatf.html

C#:   public / protected / private / internal
来源：http://dali.yj20258888.top/Article/details/gt2tdvwfpsu.html

[G11] getter / setter
来源：http://dali.meibo888.top/Article/details/gt2mzhdgvyy.html

Py:   @property 与 @x.setter
来源：http://dali.iojbl.cn/Article/details/gt2mzpspjrr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gt2ugytwoxq.html

JS:   get name() { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gt2bdqveqgk.html

TS:   get name(): string { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gt2vwqevbny.html

Java: public String getName() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gt2eklcxidf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gt2tcrlnukj.html

Ruby: attr_accessor :name
来源：http://dali.jiagoushi.top/Article/details/gt2abgyudye.html

C#:   public string Name { get; set; }
来源：http://dali.gotoacloud.top/Article/details/gt2uclwqqao.html

[G12] 对象转字符串
来源：http://dali.ybcxt.top/Article/details/gt2ddxijtlg.html

Py:   def __str__(self): return self.name
来源：http://dali.hammf.cn/Article/details/gt2mjsuvktq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2bcqqwiif.html

JS:   toString() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gt2hqqvygxy.html

TS:   toString(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gt2vvpiwewd.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2thgulbsb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gt2gwkvzwrm.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258888.top/Article/details/gt2rkzrxzwa.html

C#:   public override string ToString() => Name;
来源：http://dali.zhixingplan.top/Article/details/gt2hngmmkcw.html

[G13] 判断对象类型
来源：http://dali.chenlongwang.top/Article/details/gt2wbmnptaq.html

Py:   isinstance(u, User)
来源：http://dali.hysaishi.cn/Article/details/gt2amqxzprz.html

PHP:  $u instanceof User
来源：http://dali.redwolf501.top/Article/details/gt2rfdclxgm.html

JS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gt2cvhepslt.html

TS:   u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gt2vcenuggq.html

Java: u instanceof User
来源：http://dali.fengsongda.top/Article/details/gt2cctmnhqf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.havefunace.top/Article/details/gt2xppyfpcw.html

Ruby: u.is_a?(User)
来源：http://dali.jqgufenzy.top/Article/details/gt2fjhxlecf.html

C#:   u is User
来源：http://dali.vqdsnc.cn/Article/details/gt2cruwupwl.html

[G14] 数据类 / record
来源：http://dali.aizwys.cn/Article/details/gt2jqupehlf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgufenzy.top/Article/details/gt2pcznvfae.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenjidiqi.icu/Article/details/gt2wgqthhlt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.aibaodan.cn/Article/details/gt2ylzoltki.html

TS:   type User = { name: string; age: number };
来源：http://dali.sxryk.cn/Article/details/gt2zrqyejoa.html

Java: record User(String name, int age) {}
来源：http://dali.aizwys.cn/Article/details/gt2yclszndl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.9152youxi.cn/Article/details/gt2mnjlqhqn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xylfe.cn/Article/details/gt2jylplewy.html

C#:   record User(string Name, int Age);
来源：http://dali.tianlin.xyz/Article/details/gt2qbkdxttq.html

[G15] 枚举
来源：http://dali.guowangkeji.top/Article/details/gt2lmtcsunn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yanxiufei.cn/Article/details/gt2ccauzsnm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2siwqcsyd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hammf.cn/Article/details/gt2svolrdlp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gt2tkzcmcdw.html

Java: enum Color { RED, GREEN }
来源：http://dali.quarkkingdee.top/Article/details/gt2ppwcnfxx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rlaiutmw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.smart0.xyz/Article/details/gt2gzupuwxc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gt2earruslb.html

[G16] 对象转数组 / 字典
来源：http://dali.zycfv.cn/Article/details/gt2erenbyqr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pycfn.com/Article/details/gt2tqnpsuja.html

PHP:  get_object_vars($obj);
来源：http://dali.nanxinkj.top/Article/details/gt2ykcsxmsn.html

JS:   Object.entries(obj)
来源：http://dali.tian-w.cn/Article/details/gt2qoeinrez.html

TS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2ejqymxfu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yvedp.cn/Article/details/gt2fqcnbrml.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xinyue.icu/Article/details/gt2tvmrznfi.html

Ruby: obj.instance_variables
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wvewwlnn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yueranfly.top/Article/details/gt2mkmyaxvt.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2skhrrzun.html


<!-- 参考信息 -->