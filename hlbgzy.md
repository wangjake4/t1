代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gt2dgcrmpur.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gt2uonlknmz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.bjfxy.top/Article/details/gt2ancgkgyh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.daria6918.cn/Article/details/gt2rjeofjbz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gzhubu.top/Article/details/gt2ltbijwys.html

[E19] 多行文本按行拆分
来源：http://dali.jqgfzy.top/Article/details/gt2bmevpdsc.html

Py:   s.splitlines()
来源：http://dali.guannengcc.top/Article/details/gt2mzbysmyg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2gafbsllv.html

JS:   s.split(/\r?\n/)
来源：http://dali.havefunace.top/Article/details/gt2eeuytsee.html

TS:   s.split(/\r?\n/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vqucwiyg.html

Java: s.lines().toList()
来源：http://dali.yj20258.top/Article/details/gt2dtyscmle.html

Go:   strings.Split(s, "\n")
来源：http://dali.tianlin.xyz/Article/details/gt2areslzgf.html

Ruby: s.lines
来源：http://dali.pycfn.com/Article/details/gt2mnrjplkn.html

C#:   s.Split('\n')
来源：http://dali.zhixingplan.top/Article/details/gt2plecasha.html

[E20] 判断字符串是否为空
来源：http://dali.nwbrower.top/Article/details/gt2vsmfuawp.html

Py:   if not s:
来源：http://dali.yuanzhike.top/Article/details/gt2ipwuhojm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cheryme.top/Article/details/gt2eykbycba.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xylfe.cn/Article/details/gt2rhytqrsi.html

TS:   if (s === "") {}
来源：http://dali.sufxvd.cn/Article/details/gt2ryovkobx.html

Java: if (s.isEmpty()) {}
来源：http://dali.aizwys.cn/Article/details/gt2gbyirlhb.html

Go:   if s == "" {}
来源：http://dali.nwbrower.top/Article/details/gt2cdddlyop.html

Ruby: if s.empty?
来源：http://dali.zhixingplan.top/Article/details/gt2woodjjry.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj202588.top/Article/details/gt2xlpldqer.html

[E21] 超长截断加省略号
来源：http://dali.ybcxt.top/Article/details/gt2lflsripi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yueranfly.top/Article/details/gt2amthrads.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gt2gaiebogs.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gt2ozkiywhk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gt2ruuplgkq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gt2sxjjxlqe.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jqgfzy.top/Article/details/gt2ocvqrnbf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gt2xhoswhik.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cashguo.top/Article/details/gt2cybjowxz.html

[E22] 字节长度与字符长度
来源：http://dali.redwolf501.top/Article/details/gt2ebeqlvwv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2kgyzzanb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gt2timnsymr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhixingplan.top/Article/details/gt2lysmbewj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zycfv.cn/Article/details/gt2uyqmtrnn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhixingplan.top/Article/details/gt2bmgrdgqk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.guannengcc.top/Article/details/gt2xneamtrr.html

Ruby: s.bytesize;  s.length
来源：http://dali.haohaochexian.top/Article/details/gt2ocyflsbg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xylfe.cn/Article/details/gt2gjqbicfc.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2sbjnmnrp.html

F. 文件与目录
来源：http://dali.yonumen.top/Article/details/gt2ppwcfuiv.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2ovckaqfy.html

[F01] 读取整个文件
来源：http://dali.ppjwa.cn/Article/details/gt2zmwltuul.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ndvcmnbl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2ggekxlow.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shzxlz.cn/Article/details/gt2mvaohmqx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gt2xqtbvhys.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gt2wnqrcxjk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hammf.cn/Article/details/gt2txuupizu.html

Ruby: File.read("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2ovidqtgb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yhpeacvh.html

[F02] 逐行读取文件
来源：http://dali.jinqigfzy.top/Article/details/gt2sfnwltxz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ppjwa.cn/Article/details/gt2umlkjkpj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.haohaochexian.top/Article/details/gt2zxdkgenu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gt2wsszskuz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jpblaryt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ekrzveba.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.vqdsnc.cn/Article/details/gt2dkyltnrx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hfpthk.cn/Article/details/gt2yczeaafi.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2mjokrmcs.html

[F03] 写入文件（覆盖）
来源：http://dali.kuanghao11.cn/Article/details/gt2npxdnhyj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rljfkjkz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shuidangran.top/Article/details/gt2tkmyymic.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gt2cpqortto.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gt2lrhqfnpp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.dashuyun.cn/Article/details/gt2irvxnqmc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.smart0.xyz/Article/details/gt2xgiqtgzm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jyoumei.cn/Article/details/gt2gzfzdwmk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gt2gcjuzbtt.html

[F04] 追加写入文件
来源：http://dali.xylfe.cn/Article/details/gt2wgrxdjhg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jyoumei.cn/Article/details/gt2rstgqunz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nwbrower.top/Article/details/gt2oltaxptp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gt2uiqlrsxt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258888.top/Article/details/gt2wwppstle.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gogol.net.cn/Article/details/gt2dfhyaexd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shuidangran.top/Article/details/gt2ppyvqkxr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.aibaodan.cn/Article/details/gt2hxfwvatp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yueranfly.top/Article/details/gt2hmhisgkn.html

[F05] 判断文件或目录是否存在
来源：http://dali.9152youxi.cn/Article/details/gt2monmwacq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sufxvd.cn/Article/details/gt2aasmhhlv.html

PHP:  file_exists("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2plsuqyzc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2ofakwigz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2rwqpuhga.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gt2wnumdyat.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sweek.top/Article/details/gt2fgwelxxc.html

Ruby: File.exist?("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qklynagh.html

C#:   File.Exists("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2fpoxqtbd.html

[F06] 删除文件
来源：http://dali.yongpay.top/Article/details/gt2awyqpykj.html

Py:   os.remove("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2lscakjqz.html

PHP:  unlink("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2bmxfgmpf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2tteefqvw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2ttmdpleh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gt2zmbmhkxf.html

Go:   os.Remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2agwjdjes.html

Ruby: File.delete("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2odxrgrta.html

C#:   File.Delete("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2kpecbhbb.html

[F07] 创建目录（含多级）
来源：http://dali.zhongyouzk.top/Article/details/gt2qkcxxino.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.pycfn.com/Article/details/gt2vhhdxxha.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ttjtsijx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tian-w.cn/Article/details/gt2eoizuhyw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gt2hztzexfl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cucudq.cn/Article/details/gt2khyddkha.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.fengsongda.top/Article/details/gt2zrnsdxmk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cucudq.cn/Article/details/gt2odvcmugi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj202588.top/Article/details/gt2hgeonjzy.html

[F08] 遍历目录
来源：http://dali.shangyingyoupin.top/Article/details/gt2erkwkvtk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenlongwang.top/Article/details/gt2yweprhrp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hpjmiowg.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj20258888.top/Article/details/gt2qpwcgbdt.html

TS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gt2tuptwrhw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.svipenyu.cn/Article/details/gt2bwobhwkp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.daria6918.cn/Article/details/gt2rrghrjiu.html

Ruby: Dir.children("dir")
来源：http://dali.quarkkingdee.top/Article/details/gt2sroucycs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hywenlv.cn/Article/details/gt2cyobslzk.html

[F09] 获取文件大小
来源：http://dali.kuanghao11.cn/Article/details/gt2ecdieoae.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2nhhjipyq.html

PHP:  filesize("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2mltfmger.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangtech.top/Article/details/gt2glilhhsi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gt2jhkhnhjn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gt2kniykjab.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tanke756.top/Article/details/gt2bmlfhudu.html

Ruby: File.size("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2ajuokqri.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.c1oappe.top/Article/details/gt2zmpyvacc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cqqwz.cn/Article/details/gt2orknrntr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2qjutpktd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2prfdsmtw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eqaefkbl.html

TS:   path.extname("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2icgrwhdy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cashguo.top/Article/details/gt2xixbritc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gt2ihidayxe.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gt2aywqkjjn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ilzivlzp.html

[F11] 复制与移动文件
来源：http://dali.ydzc1.top/Article/details/gt2ahylwspc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2vzqzwijy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hammf.cn/Article/details/gt2xjkjpeza.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gt2myvldvuz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2rbhqcwdv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zdqjudy.top/Article/details/gt2gygnbsaj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ehwqpu.com/Article/details/gt2mlndcsvr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2yhogjulq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gaohongyu789.top/Article/details/gt2rcdckvre.html

[F12] CSV 读写
来源：http://dali.yj202588.top/Article/details/gt2luqamlzp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dianchejie.cn/Article/details/gt2pgztepom.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shuidangran.top/Article/details/gt2zjralpxa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cdnleiting.top/Article/details/gt2btnfgxpr.html

TS:   // 同上
来源：http://dali.jyoumei.cn/Article/details/gt2ackuldir.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj20258.top/Article/details/gt2dqbbcfgo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xylfe.cn/Article/details/gt2allhlmcr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ydzc1.top/Article/details/gt2hawzobbl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cdnleiting.top/Article/details/gt2xtbwlwqc.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2xgpbhglf.html

G. 面向对象
来源：http://dali.smart0.xyz/Article/details/gt2vbrblcrk.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2ymbxvxiv.html

[G01] 定义类
来源：http://dali.jianghu66.top/Article/details/gt2rrkajamm.html

Py:   class User: pass
来源：http://dali.jqgfzy.top/Article/details/gt2uhmfaldn.html

PHP:  class User {}
来源：http://dali.nwbrower.top/Article/details/gt2srmxdzcy.html

JS:   class User {}
来源：http://dali.fzhhl.top/Article/details/gt2rxhcsmtn.html

TS:   class User { name: string = ""; }
来源：http://dali.tianlin.xyz/Article/details/gt2havckzlt.html

Java: class User {}
来源：http://dali.yvedp.cn/Article/details/gt2vyjyhgxs.html

Go:   type User struct { Name string }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vczdysgc.html

Ruby: class User; end
来源：http://dali.shuidangran.top/Article/details/gt2mgfqnilh.html

C#:   class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ecwmskfd.html

[G02] 构造函数
来源：http://dali.vqdsnc.cn/Article/details/gt2xewwtffr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cheryme.top/Article/details/gt2pypmgjpl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2ktaonmzr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gt2xatowyig.html

TS:   constructor(public name: string) {}
来源：http://dali.yuanzhike.top/Article/details/gt2thausani.html

Java: User(String name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zpsavaqo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fvibghie.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guannengcc.top/Article/details/gt2wlwentyy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jqgfzy.top/Article/details/gt2wveetowo.html

[G03] 实例属性
来源：http://dali.kuanghao11.cn/Article/details/gt2kqyzmgcr.html

Py:   self.name = "x"
来源：http://dali.smart0.xyz/Article/details/gt2hwbtpdhr.html

PHP:  public string $name = "x";
来源：http://dali.9152youxi.cn/Article/details/gt2xuxmgljm.html

JS:   this.name = "x";
来源：http://dali.snrcjt.cn/Article/details/gt2qgyykxaa.html

TS:   name: string = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gt2xbozrclb.html

Java: private String name;
来源：http://dali.c1oappe.top/Article/details/gt2rvfswfww.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhengqikj.top/Article/details/gt2xslbgprh.html

Ruby: @name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jgtubuhn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuanzhike.top/Article/details/gt2xobeakbe.html

[G04] 定义方法
来源：http://dali.jinqigufen.top/Article/details/gt2rpfeqonq.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iifcwhhh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gt2ivgepvnl.html

JS:   greet() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2tuzhgtsz.html

TS:   greet(): string { return this.name; }
来源：http://dali.ivvv.top/Article/details/gt2rbpixfga.html

Java: String greet() { return name; }
来源：http://dali.shuidangran.top/Article/details/gt2lewuaipf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gt2dcvodntl.html

Ruby: def greet; @name; end
来源：http://dali.gogol.net.cn/Article/details/gt2ubhacqjz.html

C#:   public string Greet() => Name;
来源：http://dali.bjfxy.top/Article/details/gt2qurfbtuu.html

[G05] 继承
来源：http://dali.guannengcc.top/Article/details/gt2mrequyaf.html

Py:   class Admin(User): pass
来源：http://dali.yongpay.top/Article/details/gt2griznwku.html

PHP:  class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gt2emzpnikw.html

JS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2mvngiyco.html

TS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gt2zkcznqqj.html

Java: class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gt2fuswcydv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenzaomai.com/Article/details/gt2dxhnlojq.html

Ruby: class Admin < User; end
来源：http://dali.dianchejie.cn/Article/details/gt2rrinmklm.html

C#:   class Admin : User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2byathxfc.html

[G06] 重写方法
来源：http://dali.yj20258.top/Article/details/gt2ugcpbaeg.html

Py:   def greet(self): return "admin"
来源：http://dali.zycfv.cn/Article/details/gt2fulddqbn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gt2zascpscy.html

JS:   greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2blpebtgd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gt2kwtefpih.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gt2srxsfddd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zycfv.cn/Article/details/gt2txcvcltb.html

Ruby: def greet; "admin"; end
来源：http://dali.daxiang520.top/Article/details/gt2chkltysf.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhoulong.xyz/Article/details/gt2crorydwd.html

[G07] 调用父类方法
来源：http://dali.bjfxy.top/Article/details/gt2jqtdeysh.html

Py:   super().greet()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fwhqhmbh.html

PHP:  parent::greet();
来源：http://dali.chenlongwang.top/Article/details/gt2omisttkb.html

JS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gt2qghuokbd.html

TS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gt2yzwsxuur.html

Java: super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gt2rrcamdsw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cdnleiting.top/Article/details/gt2olhkvrzm.html

Ruby: super
来源：http://dali.zdqjudy.top/Article/details/gt2cgccyvsi.html

C#:   base.Greet();
来源：http://dali.jlsjyb.cn/Article/details/gt2ewclzaai.html

[G08] 静态方法与属性
来源：http://dali.hammf.cn/Article/details/gt2uzqsvwmn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yangfankeji.com/Article/details/gt2yubpqvuq.html

PHP:  public static function f() {}
来源：http://dali.yangfankeji.com/Article/details/gt2reabqusx.html

JS:   static f() {}
来源：http://dali.aizwys.cn/Article/details/gt2ryziytiz.html

TS:   static f(): void {}
来源：http://dali.xinyue.icu/Article/details/gt2dwxlednk.html

Java: static void f() {}
来源：http://dali.yuxming.cn/Article/details/gt2kdfivkye.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.snrcjt.cn/Article/details/gt2grpeykbh.html

Ruby: def self.f; end
来源：http://dali.cdnleiting.top/Article/details/gt2pqlwecyo.html

C#:   public static void F() {}
来源：http://dali.xylfe.cn/Article/details/gt2bvpglmvj.html

[G09] 接口 / 抽象类
来源：http://dali.yonumen.top/Article/details/gt2lraeunxm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yuxming.cn/Article/details/gt2pbnqnzlu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ntxvcjdj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gaohongyu789.top/Article/details/gt2jpfelrgn.html

TS:   interface Shape { area(): number; }
来源：http://dali.yongpay.top/Article/details/gt2netekykt.html

Java: interface Shape { double area(); }
来源：http://dali.shuidangran.top/Article/details/gt2molcegpg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2lvyojaqk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258.top/Article/details/gt2pcmpxtkc.html

C#:   interface IShape { double Area(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vxiejjbn.html

[G10] 访问控制
来源：http://dali.shuidangran.top/Article/details/gt2memytigy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.havefunace.top/Article/details/gt2gqshqvsv.html

PHP:  public / protected / private
来源：http://dali.smart0.xyz/Article/details/gt2qbmwhads.html

JS:   #private 字段；其余公开
来源：http://dali.0kj1m.cn/Article/details/gt2ksseddok.html

TS:   public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gt2szgfndqn.html

Java: public / protected / private / 默认包级
来源：http://dali.dashuyun.cn/Article/details/gt2tnepcnfe.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.0kj1m.cn/Article/details/gt2eokwgiwf.html

Ruby: public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gt2xpmbpqai.html

C#:   public / protected / private / internal
来源：http://dali.vqdsnc.cn/Article/details/gt2kesjtpei.html

[G11] getter / setter
来源：http://dali.fengsongda.top/Article/details/gt2soxtbtsu.html

Py:   @property 与 @x.setter
来源：http://dali.chenlongwang.top/Article/details/gt2yapeadby.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2hapiudmg.html

JS:   get name() { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gt2bmetxgtw.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2lefdvhhr.html

Java: public String getName() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2fnmuepdv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gt2efijmdlt.html

Ruby: attr_accessor :name
来源：http://dali.xuetiantiany.cn/Article/details/gt2verchbit.html

C#:   public string Name { get; set; }
来源：http://dali.sweek.top/Article/details/gt2qvfbqhvl.html

[G12] 对象转字符串
来源：http://dali.xuanzx.com/Article/details/gt2znfixikd.html

Py:   def __str__(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gt2pqttjqtf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2nvgqmmxu.html

JS:   toString() { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gt2qftndchm.html

TS:   toString(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gt2bqfgxdpl.html

Java: @Override public String toString() { return name; }
来源：http://dali.yvedp.cn/Article/details/gt2yvnzlbcj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gt2fssxjrsy.html

Ruby: def to_s; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gt2vehnqkfm.html

C#:   public override string ToString() => Name;
来源：http://dali.quarkkingdee.top/Article/details/gt2qpcecvmc.html

[G13] 判断对象类型
来源：http://dali.nwbrower.top/Article/details/gt2yresychs.html

Py:   isinstance(u, User)
来源：http://dali.hnqzz.top/Article/details/gt2yxllhecd.html

PHP:  $u instanceof User
来源：http://dali.iojbl.cn/Article/details/gt2zjyikfhz.html

JS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gt2kpbcutly.html

TS:   u instanceof User
来源：http://dali.mhx1999.top/Article/details/gt2wdngkpjv.html

Java: u instanceof User
来源：http://dali.sweek.top/Article/details/gt2wfcajbyr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jqgufenzy.top/Article/details/gt2zopmnmcn.html

Ruby: u.is_a?(User)
来源：http://dali.ppjwa.cn/Article/details/gt2yczejirf.html

C#:   u is User
来源：http://dali.jqgfzy.top/Article/details/gt2sjqqfslk.html

[G14] 数据类 / record
来源：http://dali.gotoacloud.top/Article/details/gt2dgmlkgbp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gotoacloud.top/Article/details/gt2mhmyyakk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhiwuduotai.top/Article/details/gt2ilwxoklp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sufxvd.cn/Article/details/gt2ymwvdgfx.html

TS:   type User = { name: string; age: number };
来源：http://dali.yanxiufei.cn/Article/details/gt2chwarfid.html

Java: record User(String name, int age) {}
来源：http://dali.fengsongda.top/Article/details/gt2qglvbcbq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ydzc1.top/Article/details/gt2ipwftwcc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zwntlvyn.html

C#:   record User(string Name, int Age);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hecmhedz.html

[G15] 枚举
来源：http://dali.zhiwuduotai.top/Article/details/gt2jlrkassa.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cheryme.top/Article/details/gt2vgovdbto.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hvvxdzaz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vkqbtaci.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gt2tnzmtwvj.html

Java: enum Color { RED, GREEN }
来源：http://dali.smart0.xyz/Article/details/gt2aetdeqgq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wncfihcx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangshuangyany.cn/Article/details/gt2wmauexjv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.haohaochexian.top/Article/details/gt2ishsloro.html

[G16] 对象转数组 / 字典
来源：http://dali.havefunace.top/Article/details/gt2kuuqsegm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.0kj1m.cn/Article/details/gt2jxbyfcim.html

PHP:  get_object_vars($obj);
来源：http://dali.gzhubu.top/Article/details/gt2dkdgcsrn.html

JS:   Object.entries(obj)
来源：http://dali.tanke756.top/Article/details/gt2fydkfdau.html

TS:   Object.entries(obj)
来源：http://dali.yongpay.top/Article/details/gt2ohbuzqmo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cashguo.top/Article/details/gt2krifmynf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yangfankeji.com/Article/details/gt2ijbzfkcg.html

Ruby: obj.instance_variables
来源：http://dali.feifeiyinyue.top/Article/details/gt2fxtsadvc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jyoumei.cn/Article/details/gt2kmtvtyas.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2rpurrvay.html


<!-- 参考信息 -->