代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.316326.xyz/Article/details/gtwhipzeno.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtcpwtcnku.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gtbjscqdyw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenlongwang.top/Article/details/gtdlfadsaz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.wangdashe.top/Article/details/gtmlzddahf.html

[E19] 多行文本按行拆分
来源：http://dali.sweek.top/Article/details/gtvkvelxtw.html

Py:   s.splitlines()
来源：http://dali.xinyue.icu/Article/details/gtstcblovj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtrlsjuaan.html

JS:   s.split(/\r?\n/)
来源：http://dali.c1oappe.top/Article/details/gthgmethya.html

TS:   s.split(/\r?\n/)
来源：http://dali.wangdashe.top/Article/details/gtmsudsbud.html

Java: s.lines().toList()
来源：http://dali.fengsongda.top/Article/details/gtfidmynla.html

Go:   strings.Split(s, "\n")
来源：http://dali.dashuyun.cn/Article/details/gtbxixvdcy.html

Ruby: s.lines
来源：http://dali.hongshengwenyu.top/Article/details/gtsantundp.html

C#:   s.Split('\n')
来源：http://dali.jqgufenzy.top/Article/details/gtvmqokxfh.html

[E20] 判断字符串是否为空
来源：http://dali.yj202588.top/Article/details/gtfdhobgrn.html

Py:   if not s:
来源：http://dali.0kj1m.cn/Article/details/gtepwsgkiz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.svipenyu.cn/Article/details/gtsnulwnpz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zycfv.cn/Article/details/gtscfzavri.html

TS:   if (s === "") {}
来源：http://dali.316326.xyz/Article/details/gtzibjjrlk.html

Java: if (s.isEmpty()) {}
来源：http://dali.nanxuanxn.top/Article/details/gthmonnoww.html

Go:   if s == "" {}
来源：http://dali.0kj1m.cn/Article/details/gthlvnpubq.html

Ruby: if s.empty?
来源：http://dali.jinqigufen.top/Article/details/gtmicjkvaw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hysaishi.cn/Article/details/gtqmfcdlgx.html

[E21] 超长截断加省略号
来源：http://dali.jlsjyb.cn/Article/details/gthbsvjjge.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.mhx1999.top/Article/details/gtyiiqmwbi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtmrfimqsp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtmvxclndl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtqcgfewyx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtvfwcotfc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zdqjudy.top/Article/details/gthnzmubwl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtxpzucifx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtaplkljwy.html

[E22] 字节长度与字符长度
来源：http://dali.yuanzhike.top/Article/details/gtulenfvmn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnqmirfb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtankcxxzf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtslcsguny.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gtzrlpsvzj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nwbrower.top/Article/details/gtprhqskua.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hammf.cn/Article/details/gtcahiuvgp.html

Ruby: s.bytesize;  s.length
来源：http://dali.redwolf501.top/Article/details/gtwotmdfrn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nwbrower.top/Article/details/gtdycrhjum.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtmgfglukb.html

F. 文件与目录
来源：http://dali.xinyue.icu/Article/details/gtjdmzeqnf.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtlcyokwgw.html

[F01] 读取整个文件
来源：http://dali.wangshuangyany.cn/Article/details/gtkntjlyhf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdbhrqhl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtcikwceae.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ppjwa.cn/Article/details/gtohulgqmi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gttndwtvme.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtfjcmbapa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yongpay.top/Article/details/gtgcrplpso.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtscnkwpah.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtgchnzpik.html

[F02] 逐行读取文件
来源：http://dali.iojbl.cn/Article/details/gtxfiavmia.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cheryme.top/Article/details/gtbzlxnshx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hywenlv.cn/Article/details/gtgsuntdru.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuanzhike.top/Article/details/gtmpjagulu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guannengcc.top/Article/details/gtpexdyweh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cashguo.top/Article/details/gtmygowmpv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nwbrower.top/Article/details/gtqqxkcqry.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.9152youxi.cn/Article/details/gtagionsmg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhongyouzk.top/Article/details/gtpheplakm.html

[F03] 写入文件（覆盖）
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfxmpgqx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jqgufenzy.top/Article/details/gtrvcxxiwj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.9152youxi.cn/Article/details/gtbmmpgtyx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xinyue.icu/Article/details/gtywipjoml.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxzgugolc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jqgufenzy.top/Article/details/gtjmwcciyv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtschzgqvj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.daria6918.cn/Article/details/gtfahzcjcs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xziqi.cn/Article/details/gtrrfadssc.html

[F04] 追加写入文件
来源：http://dali.yongpay.top/Article/details/gtrhadxhfv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.dashuyun.cn/Article/details/gtcvfooupv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.dashuyun.cn/Article/details/gtqvdwotrh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pycfn.com/Article/details/gtzexsrjgq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtmwhiyfra.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shzxlz.cn/Article/details/gtclsbcrlx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xylfe.cn/Article/details/gtzcbudhoa.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jyoumei.cn/Article/details/gtrrijvkjn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnqzz.top/Article/details/gtdnlzsngf.html

[F05] 判断文件或目录是否存在
来源：http://dali.jlsjyb.cn/Article/details/gtoiwnbkih.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jqgufenzy.top/Article/details/gtyhjlhnsc.html

PHP:  file_exists("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtrzxiuojq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtrjbcccvm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtdrnxzhdi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtyuqulehj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ybcxt.top/Article/details/gtmsbtdxqh.html

Ruby: File.exist?("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxnysalr.html

C#:   File.Exists("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtvdzessww.html

[F06] 删除文件
来源：http://dali.cashguo.top/Article/details/gtvdfsptho.html

Py:   os.remove("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtpzsydtqy.html

PHP:  unlink("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtbuhwxvyt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtllxmrnwi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gthpzyplzr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtguyybkfv.html

Go:   os.Remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtfvldeibl.html

Ruby: File.delete("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtsniekyoe.html

C#:   File.Delete("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtbxtqfcvl.html

[F07] 创建目录（含多级）
来源：http://dali.vqdsnc.cn/Article/details/gtbhcodbjg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yvedp.cn/Article/details/gtunzxhkbt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.9152youxi.cn/Article/details/gtfodwzlxz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cheryme.top/Article/details/gtrvwnlkxo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvxqfgty.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pengpengdd.cyou/Article/details/gtafuzvbkw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shzxlz.cn/Article/details/gtwnrydtsk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.feifeiyinyue.top/Article/details/gtofiehwvq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shzxlz.cn/Article/details/gtcrfvuxey.html

[F08] 遍历目录
来源：http://dali.nanxuanxn.top/Article/details/gtupggkowm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.aibaodan.cn/Article/details/gtleirrukm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxlmyxbz.html

JS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gtvyhxcglj.html

TS:   fs.readdirSync("dir")
来源：http://dali.svipenyu.cn/Article/details/gtbsqsybwr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gtnobsgolr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gzhubu.top/Article/details/gtzltrtgxu.html

Ruby: Dir.children("dir")
来源：http://dali.yangfankeji.com/Article/details/gtovpjeday.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtstqnrbal.html

[F09] 获取文件大小
来源：http://dali.xuanzx.com/Article/details/gtotfxxaxk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtsqnlflam.html

PHP:  filesize("a.txt");
来源：http://dali.birdmap.top/Article/details/gtqihtgxcb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenlongwang.top/Article/details/gtrxzejnck.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gtqaeqpsfh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtynsbqnwy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenjidiqi.icu/Article/details/gtekpeabnj.html

Ruby: File.size("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtxyenrlpz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cucudq.cn/Article/details/gtwundrbih.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sysykeji.top/Article/details/gtpfnfmtaq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtkpvmdhyd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sysykeji.top/Article/details/gtnclmzsfu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtqvligphl.html

TS:   path.extname("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtxmuostoi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtphpogixg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoksdzjju.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtezssrqam.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtpolengvl.html

[F11] 复制与移动文件
来源：http://dali.iojbl.cn/Article/details/gtpilnvayl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtoduubzoo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ehwqpu.com/Article/details/gtguzbboje.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhzwwciz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtspwavlrz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.redwolf501.top/Article/details/gtfjoheajm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhiwuduotai.top/Article/details/gtftknlhcv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtcppnwwpy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhoulong.xyz/Article/details/gttrbposrj.html

[F12] CSV 读写
来源：http://dali.redwolf501.top/Article/details/gtolyesgkt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuetiantiany.cn/Article/details/gttiiiedip.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.meibo888.top/Article/details/gtytmyhams.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shangyingyoupin.top/Article/details/gtyvfvxmyh.html

TS:   // 同上
来源：http://dali.cashguo.top/Article/details/gtbafupgxd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daria6918.cn/Article/details/gtexhgytwv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gtxxtmbqmz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xinyue.icu/Article/details/gtytxsujmv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangshuangyany.cn/Article/details/gtpleezagb.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtyraeccqu.html

G. 面向对象
来源：http://dali.fengsongda.top/Article/details/gtrxmeoaew.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtbdpoezrh.html

[G01] 定义类
来源：http://dali.bjfxy.top/Article/details/gtmtwbeirh.html

Py:   class User: pass
来源：http://dali.gogol.net.cn/Article/details/gtzudmzobz.html

PHP:  class User {}
来源：http://dali.hammf.cn/Article/details/gtdpxyqebi.html

JS:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtpvtuwfel.html

TS:   class User { name: string = ""; }
来源：http://dali.zycfv.cn/Article/details/gtqlazcvqc.html

Java: class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtzvtffxol.html

Go:   type User struct { Name string }
来源：http://dali.nwbrower.top/Article/details/gtwffgysdt.html

Ruby: class User; end
来源：http://dali.aizwys.cn/Article/details/gtlakngygu.html

C#:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gthoinopns.html

[G02] 构造函数
来源：http://dali.yueranfly.top/Article/details/gtycplcnvr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yangfankeji.com/Article/details/gtmogatjra.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.9152youxi.cn/Article/details/gtpibyyxah.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gtyblyghgt.html

TS:   constructor(public name: string) {}
来源：http://dali.hnxiangtu.top/Article/details/gtibahumin.html

Java: User(String name) { this.name = name; }
来源：http://dali.c1oappe.top/Article/details/gtoshblnjw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nwbrower.top/Article/details/gtglbgnmbw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj202588.top/Article/details/gtixnbhqjr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gtruqzwpnp.html

[G03] 实例属性
来源：http://dali.feifeiyinyue.top/Article/details/gtebmtximz.html

Py:   self.name = "x"
来源：http://dali.xinyue.icu/Article/details/gtjdzyxqbv.html

PHP:  public string $name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtfyaqmrcw.html

JS:   this.name = "x";
来源：http://dali.yuanzhike.top/Article/details/gtyabuhtij.html

TS:   name: string = "x";
来源：http://dali.hfpthk.cn/Article/details/gtllibcgyh.html

Java: private String name;
来源：http://dali.meibo888.top/Article/details/gtafnyubql.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hammf.cn/Article/details/gtryyyhdiq.html

Ruby: @name = "x"
来源：http://dali.pycfn.com/Article/details/gtcslaqyxn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xylfe.cn/Article/details/gtloaidsgh.html

[G04] 定义方法
来源：http://dali.shangyingyoupin.top/Article/details/gtyehldtwm.html

Py:   def greet(self): return self.name
来源：http://dali.zhiwuduotai.top/Article/details/gtwiwccqcj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtpdsravsb.html

JS:   greet() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtdqobcgad.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtaaijjyot.html

Java: String greet() { return name; }
来源：http://dali.daria6918.cn/Article/details/gtumpxvpmr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtsmtiecpa.html

Ruby: def greet; @name; end
来源：http://dali.cdnleiting.top/Article/details/gtssxfapka.html

C#:   public string Greet() => Name;
来源：http://dali.shuidangran.top/Article/details/gtwembnqkn.html

[G05] 继承
来源：http://dali.feifeiyinyue.top/Article/details/gtsshxxaot.html

Py:   class Admin(User): pass
来源：http://dali.quarkkingdee.top/Article/details/gttazpftmp.html

PHP:  class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtunmeafbg.html

JS:   class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtgpjaqxhd.html

TS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtsqivonbj.html

Java: class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtklnayayz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xziqi.cn/Article/details/gtxclptpou.html

Ruby: class Admin < User; end
来源：http://dali.snrcjt.cn/Article/details/gtvdbtsxht.html

C#:   class Admin : User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbzowrhrv.html

[G06] 重写方法
来源：http://dali.tian-w.cn/Article/details/gtmulgiipa.html

Py:   def greet(self): return "admin"
来源：http://dali.zhaomingkeji.xyz/Article/details/gthwgsguvo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtbtnnorod.html

JS:   greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtsiouykmu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtsxixkptl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtwnfksweh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ybcxt.top/Article/details/gtudsclcly.html

Ruby: def greet; "admin"; end
来源：http://dali.wangshuangyany.cn/Article/details/gtncdqujkj.html

C#:   public override string Greet() => "admin";
来源：http://dali.jiagoushi.top/Article/details/gtozbtylqt.html

[G07] 调用父类方法
来源：http://dali.daxiang520.top/Article/details/gtewasknqo.html

Py:   super().greet()
来源：http://dali.xziqi.cn/Article/details/gtjqltwjzc.html

PHP:  parent::greet();
来源：http://dali.cdnleiting.top/Article/details/gtaqvoompc.html

JS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtqtxpiijp.html

TS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gtbsjonjto.html

Java: super.greet();
来源：http://dali.birdmap.top/Article/details/gtkcgmpybe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nanxuanxn.top/Article/details/gtbiyrlupf.html

Ruby: super
来源：http://dali.fengsongda.top/Article/details/gtogkttknf.html

C#:   base.Greet();
来源：http://dali.daxiang520.top/Article/details/gtfnzdkahw.html

[G08] 静态方法与属性
来源：http://dali.cdnleiting.top/Article/details/gtinkjcxvv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.svipenyu.cn/Article/details/gtankwegns.html

PHP:  public static function f() {}
来源：http://dali.cucudq.cn/Article/details/gteosqgblf.html

JS:   static f() {}
来源：http://dali.chenzaomai.com/Article/details/gtrrjzpzie.html

TS:   static f(): void {}
来源：http://dali.pengpengdd.cyou/Article/details/gthyoaxipi.html

Java: static void f() {}
来源：http://dali.sysykeji.top/Article/details/gtclutpcny.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yongpay.top/Article/details/gtqulcahpy.html

Ruby: def self.f; end
来源：http://dali.shuidangran.top/Article/details/gtcwjjugwd.html

C#:   public static void F() {}
来源：http://dali.haohaochexian.top/Article/details/gtnszrjvbs.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigfzy.top/Article/details/gtnaytuxda.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.kuanghao11.cn/Article/details/gtmzyrqwfh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.mhx1999.top/Article/details/gtureetckq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hammf.cn/Article/details/gtromzvcvr.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258888.top/Article/details/gtvpdvcdxn.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gttgcerqsx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hysaishi.cn/Article/details/gtvottewlw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aibaodan.cn/Article/details/gtieweaaej.html

C#:   interface IShape { double Area(); }
来源：http://dali.dianchejie.cn/Article/details/gtkxqyrhxv.html

[G10] 访问控制
来源：http://dali.ydzc1.top/Article/details/gtxjnqfsce.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.316326.xyz/Article/details/gtqydlmkaf.html

PHP:  public / protected / private
来源：http://dali.aizwys.cn/Article/details/gtkcjinlck.html

JS:   #private 字段；其余公开
来源：http://dali.yonumen.top/Article/details/gtbvlmdlii.html

TS:   public / protected / private
来源：http://dali.wangdashe.top/Article/details/gteluuvglw.html

Java: public / protected / private / 默认包级
来源：http://dali.zhengqikj.top/Article/details/gtaqqldeqt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.svipenyu.cn/Article/details/gtgthdsofu.html

Ruby: public / protected / private
来源：http://dali.fengsongda.top/Article/details/gtmmlumoqi.html

C#:   public / protected / private / internal
来源：http://dali.birdmap.top/Article/details/gtakujceik.html

[G11] getter / setter
来源：http://dali.guannengcc.top/Article/details/gtdygukldc.html

Py:   @property 与 @x.setter
来源：http://dali.wangshuangyany.cn/Article/details/gtzxkfvauw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gtmahaftng.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gtxsmspoet.html

TS:   get name(): string { return this._name; }
来源：http://dali.hammf.cn/Article/details/gtnrimpqnv.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtfvdslyqg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gtrbxanuwz.html

Ruby: attr_accessor :name
来源：http://dali.ppjwa.cn/Article/details/gttmssydrp.html

C#:   public string Name { get; set; }
来源：http://dali.sxryk.cn/Article/details/gtoyffisqw.html

[G12] 对象转字符串
来源：http://dali.xuanzx.com/Article/details/gtponatmiz.html

Py:   def __str__(self): return self.name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtavovkfco.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gtjvrteiip.html

JS:   toString() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtrqcpills.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtseeylmub.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj20258888.top/Article/details/gtidbtzdst.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtrzrschuf.html

Ruby: def to_s; @name; end
来源：http://dali.ydzc1.top/Article/details/gtfbggmfir.html

C#:   public override string ToString() => Name;
来源：http://dali.xinyue.icu/Article/details/gtglsvfpnc.html

[G13] 判断对象类型
来源：http://dali.zdqjudy.top/Article/details/gterbmxxci.html

Py:   isinstance(u, User)
来源：http://dali.hnxiangtu.top/Article/details/gtukznmjxm.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtvumazeyh.html

JS:   u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtlzhrmlze.html

TS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugdalzxq.html

Java: u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtlhmwyvvh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhixingplan.top/Article/details/gtztzrvrkh.html

Ruby: u.is_a?(User)
来源：http://dali.aibaodan.cn/Article/details/gtlboenmwi.html

C#:   u is User
来源：http://dali.dashuyun.cn/Article/details/gthwpdfptj.html

[G14] 数据类 / record
来源：http://dali.sxryk.cn/Article/details/gtcnxklznt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.birdmap.top/Article/details/gtyailrwpx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhongyouzk.top/Article/details/gtyktoewwl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tanke756.top/Article/details/gtpgybqsmm.html

TS:   type User = { name: string; age: number };
来源：http://dali.mhx1999.top/Article/details/gthtejkewr.html

Java: record User(String name, int age) {}
来源：http://dali.wangdashe.top/Article/details/gtnccbhnwb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmiggiyk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nanxuanxn.top/Article/details/gtqqpgfqbg.html

C#:   record User(string Name, int Age);
来源：http://dali.jlsjyb.cn/Article/details/gtjlllsilt.html

[G15] 枚举
来源：http://dali.wangdashe.top/Article/details/gtpjvnadji.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cucudq.cn/Article/details/gtrxvwodmj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jiagoushi.top/Article/details/gtizxrasgt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.9152youxi.cn/Article/details/gtokkxplbx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gtgtzxoyqu.html

Java: enum Color { RED, GREEN }
来源：http://dali.xuanzx.com/Article/details/gtkdazqdwc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cashguo.top/Article/details/gtikytsurt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guannengcc.top/Article/details/gtasgnxksa.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtvbpmvlod.html

[G16] 对象转数组 / 字典
来源：http://dali.aibaodan.cn/Article/details/gtlrgexudy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhixingplan.top/Article/details/gtjftbyhwg.html

PHP:  get_object_vars($obj);
来源：http://dali.yvedp.cn/Article/details/gtjoqxdvjz.html

JS:   Object.entries(obj)
来源：http://dali.tianlin.xyz/Article/details/gtgjwpmgzm.html

TS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gtuunsgkqr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwysmlbd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sweek.top/Article/details/gtjlwbjyvu.html

Ruby: obj.instance_variables
来源：http://dali.hfpthk.cn/Article/details/gtqurcvkgk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yvedp.cn/Article/details/gtengrsezp.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtxksxcnxj.html


<!-- 参考信息 -->