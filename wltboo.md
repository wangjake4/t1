代发 wailian999

[E18] 模板占位符替换
来源：http://dali.xuanzx.com/Article/details/gtspkyikin.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.birdmap.top/Article/details/gtfbwrikxp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnoplbad.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtdeqnorzf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtjmlrssim.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtqkydxbzr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtzxjjoyuh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cucudq.cn/Article/details/gtlsewadlx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gtbnkpckth.html

[E19] 多行文本按行拆分
来源：http://dali.nanxuanxn.top/Article/details/gtawzdblrt.html

Py:   s.splitlines()
来源：http://dali.yvedp.cn/Article/details/gtuosfaisv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtwwyuiulg.html

JS:   s.split(/\r?\n/)
来源：http://dali.ybcxt.top/Article/details/gtbmqfkpac.html

TS:   s.split(/\r?\n/)
来源：http://dali.svipenyu.cn/Article/details/gtigfdcnwz.html

Java: s.lines().toList()
来源：http://dali.cheryme.top/Article/details/gtvdfnqszy.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenlongwang.top/Article/details/gtenvivuax.html

Ruby: s.lines
来源：http://dali.shanyushiyangtech.top/Article/details/gtqurkooyi.html

C#:   s.Split('\n')
来源：http://dali.ehwqpu.com/Article/details/gtqzvdulux.html

[E20] 判断字符串是否为空
来源：http://dali.tian-w.cn/Article/details/gtmxigkgew.html

Py:   if not s:
来源：http://dali.havefunace.top/Article/details/gtexjoafao.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xuanzx.com/Article/details/gtbxosjyrl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jiagoushi.top/Article/details/gtkrqltolh.html

TS:   if (s === "") {}
来源：http://dali.sysykeji.top/Article/details/gtcshmippc.html

Java: if (s.isEmpty()) {}
来源：http://dali.aizwys.cn/Article/details/gtmofpntgu.html

Go:   if s == "" {}
来源：http://dali.yueranfly.top/Article/details/gtbfhpawgn.html

Ruby: if s.empty?
来源：http://dali.xuanzx.com/Article/details/gtvcvmynog.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenlongwang.top/Article/details/gtdltdinva.html

[E21] 超长截断加省略号
来源：http://dali.jinqigfzy.top/Article/details/gtspvmgizf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zdqjudy.top/Article/details/gtqgmmqkxo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gtrhmdfyyd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtbuofrvvp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtwzfqilbe.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtgrxzmirc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinqigfzy.top/Article/details/gtlmvxlugu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sweek.top/Article/details/gtcjmegdft.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gtherqvnkp.html

[E22] 字节长度与字符长度
来源：http://dali.meibo888.top/Article/details/gtddmdfzws.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xylfe.cn/Article/details/gtufjadthm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtovlesdmn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gtvulubcdb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ydzc1.top/Article/details/gtawqfnfel.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jianghu66.top/Article/details/gtuooauqee.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cqqwz.cn/Article/details/gtbxyrwhde.html

Ruby: s.bytesize;  s.length
来源：http://dali.daria6918.cn/Article/details/gtacetpfqb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenlongwang.top/Article/details/gtfsothlhc.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtkmlguotw.html

F. 文件与目录
来源：http://dali.shangyingyoupin.top/Article/details/gtnrccqhel.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtdrerdkqi.html

[F01] 读取整个文件
来源：http://dali.gotoacloud.top/Article/details/gtliddgoxx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fzhhl.top/Article/details/gtlktbfkww.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtzhjripgd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhixingplan.top/Article/details/gttfzxfypq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.fengsongda.top/Article/details/gtvmnpefms.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtpadbygqm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.9152youxi.cn/Article/details/gtfzpdlmaa.html

Ruby: File.read("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtpbsasheu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj202588.top/Article/details/gtednvglyh.html

[F02] 逐行读取文件
来源：http://dali.jlsjyb.cn/Article/details/gtideoxjhs.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hongshengwenyu.top/Article/details/gtbmnxacut.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhdzfmdx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkzovvzzl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cashguo.top/Article/details/gtcabriqaf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhiwuduotai.top/Article/details/gtkfqaaftf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sweek.top/Article/details/gtxtcsccnr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jqgfzy.top/Article/details/gtqynsfocx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.9152youxi.cn/Article/details/gtpuabeqca.html

[F03] 写入文件（覆盖）
来源：http://dali.aibaodan.cn/Article/details/gtjpoaofmn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenjidiqi.icu/Article/details/gtmysmhagr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.quarkkingdee.top/Article/details/gtkamlooeu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gtxsqowtxy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gtusmukvdp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.pycfn.com/Article/details/gtlayiiggs.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jianghu66.top/Article/details/gthqnnveku.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hywenlv.cn/Article/details/gtwzarpkpu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gtxbxjnsll.html

[F04] 追加写入文件
来源：http://dali.shangyingyoupin.top/Article/details/gtolpnmpoz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hysaishi.cn/Article/details/gtpysnmiru.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.0kj1m.cn/Article/details/gtdadozrej.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gtujeepzoy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gtnjhweuoa.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cqqwz.cn/Article/details/gtbmngdspd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.snrcjt.cn/Article/details/gtukyxxsxx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258.top/Article/details/gtorhouupd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yuanzhike.top/Article/details/gtaxwtfzhu.html

[F05] 判断文件或目录是否存在
来源：http://dali.yuxming.cn/Article/details/gtvlfimmco.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.haohaochexian.top/Article/details/gtqvjvqwhl.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtbtihppey.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqcvmhug.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtwzrbfsue.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtgawcyrzt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.quarkkingdee.top/Article/details/gtcmrizsma.html

Ruby: File.exist?("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtjyzshklq.html

C#:   File.Exists("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtmpmtwigh.html

[F06] 删除文件
来源：http://dali.tianlin.xyz/Article/details/gtpnjeutnp.html

Py:   os.remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gtlpzufbhp.html

PHP:  unlink("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtooshehel.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtdkuzkjcd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtnejrgsvv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtnomsywfg.html

Go:   os.Remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtgqtvenhh.html

Ruby: File.delete("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtopovbsns.html

C#:   File.Delete("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtjwmqxior.html

[F07] 创建目录（含多级）
来源：http://dali.hammf.cn/Article/details/gtgohdtehi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnxxykvaj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hnxiangtu.top/Article/details/gthsfpbbjt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gtbudpctfu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.iojbl.cn/Article/details/gtixcfaqxz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jianghu66.top/Article/details/gtjjdswmrs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ehwqpu.com/Article/details/gtofnlbnyc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj20258888.top/Article/details/gtbmmhyaqh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xylfe.cn/Article/details/gthpziwyfm.html

[F08] 遍历目录
来源：http://dali.kuanghao11.cn/Article/details/gtbtizmref.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.mhx1999.top/Article/details/gtowadbipk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.wangshuangyany.cn/Article/details/gtjhkfpntp.html

JS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gtkrdiwnim.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtftmmllob.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gtlshtzhjy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtggnfbkkz.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258888.top/Article/details/gtqymbumnd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sufxvd.cn/Article/details/gtfinoiyjn.html

[F09] 获取文件大小
来源：http://dali.cucudq.cn/Article/details/gtngqekzyy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtrrwtfcmc.html

PHP:  filesize("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gteurxcrsw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gtqnhyrxma.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zycfv.cn/Article/details/gtuatetyvj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtdjhnusef.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jianghu66.top/Article/details/gtjvpgqkky.html

Ruby: File.size("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtxzqbllrp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gthamtjuov.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.dashuyun.cn/Article/details/gtvevpxafi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtdierihyz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtiprlduho.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtxhkyldou.html

TS:   path.extname("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtvrohmwnt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guowangkeji.top/Article/details/gtkmnikceb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtomctjmtu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtuhngosut.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtaqfcegus.html

[F11] 复制与移动文件
来源：http://dali.dashuyun.cn/Article/details/gtjatdcmjg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtqmvapfkl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtyejirkyu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gturnqxvoo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtcnyxdrik.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gtjyasupvw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yongpay.top/Article/details/gtllhjevip.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtxxbposoy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.dianchejie.cn/Article/details/gtlnwudgrm.html

[F12] CSV 读写
来源：http://dali.sxryk.cn/Article/details/gteawomodn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sufxvd.cn/Article/details/gthqxauugr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zdqjudy.top/Article/details/gtbzhkcifw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daria6918.cn/Article/details/gtrkmffmww.html

TS:   // 同上
来源：http://dali.xuetiantiany.cn/Article/details/gtprbcjyny.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.birdmap.top/Article/details/gtlbsejvoy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.mhx1999.top/Article/details/gtbpxiqrya.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.haohaochexian.top/Article/details/gtidbchhqt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hysaishi.cn/Article/details/gtebqrhrlo.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtvqwfkqgm.html

G. 面向对象
来源：http://dali.yj20258888.top/Article/details/gtcguyeico.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtiqfzvgvv.html

[G01] 定义类
来源：http://dali.daxiang520.top/Article/details/gtvafshtzs.html

Py:   class User: pass
来源：http://dali.redwolf501.top/Article/details/gtlwqestzd.html

PHP:  class User {}
来源：http://dali.dashuyun.cn/Article/details/gtzrgqfisa.html

JS:   class User {}
来源：http://dali.fengsongda.top/Article/details/gtdhzvfqgx.html

TS:   class User { name: string = ""; }
来源：http://dali.hysaishi.cn/Article/details/gtpgtganud.html

Java: class User {}
来源：http://dali.ivvv.top/Article/details/gtzdqwuika.html

Go:   type User struct { Name string }
来源：http://dali.yongpay.top/Article/details/gtfdkzmaqx.html

Ruby: class User; end
来源：http://dali.sweek.top/Article/details/gtngzzegwc.html

C#:   class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtmslyhtgo.html

[G02] 构造函数
来源：http://dali.fzhhl.top/Article/details/gtxuteghlq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuetiantiany.cn/Article/details/gtmbuffxyo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shangyingyoupin.top/Article/details/gthfaaafkt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gtvgopwpic.html

TS:   constructor(public name: string) {}
来源：http://dali.zhengqikj.top/Article/details/gtkedyldlf.html

Java: User(String name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtounrqosm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.haohaochexian.top/Article/details/gtzkkrdipo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shuidangran.top/Article/details/gtxpdixeho.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gzhubu.top/Article/details/gtldvowolb.html

[G03] 实例属性
来源：http://dali.xinyue.icu/Article/details/gtsqcsyvzo.html

Py:   self.name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gtdcwclosf.html

PHP:  public string $name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gttxwqljhw.html

JS:   this.name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtkoqqcnek.html

TS:   name: string = "x";
来源：http://dali.yangfankeji.com/Article/details/gtzftllndc.html

Java: private String name;
来源：http://dali.cashguo.top/Article/details/gttfjbhlnb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yonumen.top/Article/details/gtdfnskkyt.html

Ruby: @name = "x"
来源：http://dali.daxiang520.top/Article/details/gtkkqsyvac.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zycfv.cn/Article/details/gtipsqqtyt.html

[G04] 定义方法
来源：http://dali.sweek.top/Article/details/gtugobpnjt.html

Py:   def greet(self): return self.name
来源：http://dali.pycfn.com/Article/details/gtsaljrnba.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gtqctstxtc.html

JS:   greet() { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbimrpahy.html

TS:   greet(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtgqwsnwfh.html

Java: String greet() { return name; }
来源：http://dali.xylfe.cn/Article/details/gtqajsopuc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gtlplorcyg.html

Ruby: def greet; @name; end
来源：http://dali.tanke756.top/Article/details/gtjmdwlsyv.html

C#:   public string Greet() => Name;
来源：http://dali.daria6918.cn/Article/details/gtjkzjdzww.html

[G05] 继承
来源：http://dali.yangfankeji.com/Article/details/gtbwwgigup.html

Py:   class Admin(User): pass
来源：http://dali.sysykeji.top/Article/details/gtmjbfvgol.html

PHP:  class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjntrrkj.html

JS:   class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtlxphsvge.html

TS:   class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtfncycxno.html

Java: class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtgmrwwwex.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pengpengdd.cyou/Article/details/gtqjslbtex.html

Ruby: class Admin < User; end
来源：http://dali.dashuyun.cn/Article/details/gtmrbvggwz.html

C#:   class Admin : User {}
来源：http://dali.jqgfzy.top/Article/details/gtivnkumia.html

[G06] 重写方法
来源：http://dali.smart0.xyz/Article/details/gtqgxmwtca.html

Py:   def greet(self): return "admin"
来源：http://dali.guannengcc.top/Article/details/gtwwdythie.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtnwmmhmtm.html

JS:   greet() { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtrfblncbp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtzogmmnny.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtsmauipxs.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.9152youxi.cn/Article/details/gtdqipmznl.html

Ruby: def greet; "admin"; end
来源：http://dali.svipenyu.cn/Article/details/gtjkeevmmm.html

C#:   public override string Greet() => "admin";
来源：http://dali.sweek.top/Article/details/gtqajyimaz.html

[G07] 调用父类方法
来源：http://dali.jyoumei.cn/Article/details/gtjdbmgrtj.html

Py:   super().greet()
来源：http://dali.kuanghao11.cn/Article/details/gthyjctfhr.html

PHP:  parent::greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtmyxqfdux.html

JS:   super.greet();
来源：http://dali.guowangkeji.top/Article/details/gthnbktdsl.html

TS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtergabwpr.html

Java: super.greet();
来源：http://dali.xziqi.cn/Article/details/gtujzfytvl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tian-w.cn/Article/details/gtbwtwjbwe.html

Ruby: super
来源：http://dali.fzhhl.top/Article/details/gtwlxarizo.html

C#:   base.Greet();
来源：http://dali.andypj.xyz/Article/details/gttalpzipz.html

[G08] 静态方法与属性
来源：http://dali.wangshuangyany.cn/Article/details/gtbijgfztk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangdashe.top/Article/details/gtmyusiswk.html

PHP:  public static function f() {}
来源：http://dali.dashuyun.cn/Article/details/gtvxtqrswh.html

JS:   static f() {}
来源：http://dali.mhx1999.top/Article/details/gtgnrokxyq.html

TS:   static f(): void {}
来源：http://dali.ppjwa.cn/Article/details/gtmalqsiag.html

Java: static void f() {}
来源：http://dali.sysykeji.top/Article/details/gtphuuefoj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xinyue.icu/Article/details/gtgylbyyyd.html

Ruby: def self.f; end
来源：http://dali.sweek.top/Article/details/gtkogavuns.html

C#:   public static void F() {}
来源：http://dali.jinqigufen.top/Article/details/gtcmeyoaoo.html

[G09] 接口 / 抽象类
来源：http://dali.shanyushiyangtech.top/Article/details/gtccwpuojd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cucudq.cn/Article/details/gtmjqygqye.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yonumen.top/Article/details/gtuqmzcwwt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ehwqpu.com/Article/details/gtfudleqtt.html

TS:   interface Shape { area(): number; }
来源：http://dali.sweek.top/Article/details/gtdqqwhbof.html

Java: interface Shape { double area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfbfwivps.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tianlin.xyz/Article/details/gtubxyoetl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhoulong.xyz/Article/details/gtybxewgxn.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxuanxn.top/Article/details/gtlgyabbhn.html

[G10] 访问控制
来源：http://dali.fzhhl.top/Article/details/gtuaqnymry.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigufen.top/Article/details/gtvrprfutp.html

PHP:  public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtlpujsqgc.html

JS:   #private 字段；其余公开
来源：http://dali.zhongyouzk.top/Article/details/gtybzctmer.html

TS:   public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gttgkmzeyl.html

Java: public / protected / private / 默认包级
来源：http://dali.9152youxi.cn/Article/details/gtsiwgkkll.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shzxlz.cn/Article/details/gtlegacwpe.html

Ruby: public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gtwbubnwnh.html

C#:   public / protected / private / internal
来源：http://dali.zhixingplan.top/Article/details/gtlluodryi.html

[G11] getter / setter
来源：http://dali.gogol.net.cn/Article/details/gtatusdzep.html

Py:   @property 与 @x.setter
来源：http://dali.nanxinkj.top/Article/details/gtsgrfnlzg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjorhszm.html

JS:   get name() { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gtollapxtd.html

TS:   get name(): string { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gtlsnaswfb.html

Java: public String getName() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtrkkxufyk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gtkyboroeg.html

Ruby: attr_accessor :name
来源：http://dali.sxryk.cn/Article/details/gtuhsqrlzf.html

C#:   public string Name { get; set; }
来源：http://dali.nanxinkj.top/Article/details/gtqtajwytk.html

[G12] 对象转字符串
来源：http://dali.iojbl.cn/Article/details/gtagkwgpsb.html

Py:   def __str__(self): return self.name
来源：http://dali.yangfankeji.com/Article/details/gtgqemvrij.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gteblrxwob.html

JS:   toString() { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtbytvakjc.html

TS:   toString(): string { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtgcblbonj.html

Java: @Override public String toString() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtbarujkmh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gtafvmzbvo.html

Ruby: def to_s; @name; end
来源：http://dali.shuidangran.top/Article/details/gtvvwvlede.html

C#:   public override string ToString() => Name;
来源：http://dali.cqqwz.cn/Article/details/gtjyykpdgd.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gtpstkctpp.html

Py:   isinstance(u, User)
来源：http://dali.quarkkingdee.top/Article/details/gtyhlxlukw.html

PHP:  $u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtawqfzbjf.html

JS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtssgjsmpg.html

TS:   u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtjulhknmk.html

Java: u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtioknywui.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tianlin.xyz/Article/details/gtseyxwcve.html

Ruby: u.is_a?(User)
来源：http://dali.dashuyun.cn/Article/details/gtesrwffqf.html

C#:   u is User
来源：http://dali.hongshengwenyu.top/Article/details/gtzjiuotkl.html

[G14] 数据类 / record
来源：http://dali.birdmap.top/Article/details/gteaucmhdb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpmzkczaj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gotoacloud.top/Article/details/gtzdkubqzx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.feifeiyinyue.top/Article/details/gthtrttkac.html

TS:   type User = { name: string; age: number };
来源：http://dali.hammf.cn/Article/details/gtvptbdreq.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gtjuzhgtzo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ydzc1.top/Article/details/gtwmwrhewl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pengpengdd.cyou/Article/details/gtllhqurep.html

C#:   record User(string Name, int Age);
来源：http://dali.jiagoushi.top/Article/details/gtzpfbmter.html

[G15] 枚举
来源：http://dali.birdmap.top/Article/details/gtkhszuawz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgufenzy.top/Article/details/gtwcrllbcu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.9152youxi.cn/Article/details/gtkdpiqwff.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.0kj1m.cn/Article/details/gtxgbuccrk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuanzhike.top/Article/details/gtjqfuuckn.html

Java: enum Color { RED, GREEN }
来源：http://dali.jyoumei.cn/Article/details/gtavqzfdbv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tianlin.xyz/Article/details/gtlpktnygu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aibaodan.cn/Article/details/gtzeckratr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gtwdwblhfd.html

[G16] 对象转数组 / 字典
来源：http://dali.feifeiyinyue.top/Article/details/gtttantxla.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yueranfly.top/Article/details/gtiwftoxyd.html

PHP:  get_object_vars($obj);
来源：http://dali.tian-w.cn/Article/details/gteojchpsg.html

JS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gtdayuxpps.html

TS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gtodzlddfj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fengsongda.top/Article/details/gtrdtunxzf.html


<!-- 参考信息 -->