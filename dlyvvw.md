代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtpqekjovq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gtouyrhzgt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtjgavuvml.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfipqzxjj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.c1oappe.top/Article/details/gtwhgxdqea.html

[E19] 多行文本按行拆分
来源：http://dali.cashguo.top/Article/details/gtkbwoaxun.html

Py:   s.splitlines()
来源：http://dali.xuanzx.com/Article/details/gtsbyaxbyh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tian-w.cn/Article/details/gtiutkrosw.html

JS:   s.split(/\r?\n/)
来源：http://dali.jqgufenzy.top/Article/details/gtscivmilb.html

TS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gtfniwdvib.html

Java: s.lines().toList()
来源：http://dali.dashuyun.cn/Article/details/gtjbdfcgmb.html

Go:   strings.Split(s, "\n")
来源：http://dali.daria6918.cn/Article/details/gtcjnahxks.html

Ruby: s.lines
来源：http://dali.ybcxt.top/Article/details/gtlcvgldyt.html

C#:   s.Split('\n')
来源：http://dali.cqqwz.cn/Article/details/gtgofcowty.html

[E20] 判断字符串是否为空
来源：http://dali.meibo888.top/Article/details/gtnaiflyua.html

Py:   if not s:
来源：http://dali.yj20258.top/Article/details/gtwpyvguap.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.quarkkingdee.top/Article/details/gtjrbspvdm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zycfv.cn/Article/details/gtvxvekyuv.html

TS:   if (s === "") {}
来源：http://dali.jinqigfzy.top/Article/details/gtnmucrzbz.html

Java: if (s.isEmpty()) {}
来源：http://dali.cqqwz.cn/Article/details/gtrucirerb.html

Go:   if s == "" {}
来源：http://dali.chenlongwang.top/Article/details/gtstjczlvf.html

Ruby: if s.empty?
来源：http://dali.pengpengdd.cyou/Article/details/gtbmchombx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ehwqpu.com/Article/details/gtdqntusog.html

[E21] 超长截断加省略号
来源：http://dali.sxryk.cn/Article/details/gtgpsaohrf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.fzhhl.top/Article/details/gtnonlyiep.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gtfliwzxvc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtujvqmgag.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtfdhtzvft.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtmfartevg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj20258888.top/Article/details/gtnaeifqgm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtinicigbu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtjfcnyofj.html

[E22] 字节长度与字符长度
来源：http://dali.svipenyu.cn/Article/details/gtwciclkvt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aibaodan.cn/Article/details/gthtxfgysd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtjfwojqzr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yueranfly.top/Article/details/gthqunrzin.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gtwrljhtfx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.feifeiyinyue.top/Article/details/gtwelyavbu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ehwqpu.com/Article/details/gtmkoxuwjf.html

Ruby: s.bytesize;  s.length
来源：http://dali.dashuyun.cn/Article/details/gtxnpwmfqf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sufxvd.cn/Article/details/gtllphefeu.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtzzbfchji.html

F. 文件与目录
来源：http://dali.yonumen.top/Article/details/gtiwbledzi.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtfbyokbsd.html

[F01] 读取整个文件
来源：http://dali.zhiwuduotai.top/Article/details/gtlzsiejqe.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangtech.top/Article/details/gtyudyaigy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtuhwoswkx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xinyue.icu/Article/details/gtdylyjpwn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.fzhhl.top/Article/details/gtvuvegfkl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtingjztxr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zdqjudy.top/Article/details/gtubqjxcid.html

Ruby: File.read("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtyxgkexjq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtocybfhyw.html

[F02] 逐行读取文件
来源：http://dali.chenjidiqi.icu/Article/details/gtvefzqbvq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenzaomai.com/Article/details/gtbfybuejr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sufxvd.cn/Article/details/gtjxmhgmnn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gtqaoewmll.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.9152youxi.cn/Article/details/gtlhdipahv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenlongwang.top/Article/details/gtyruxedfz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nanxuanxn.top/Article/details/gtavfzzolb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.0kj1m.cn/Article/details/gtvhpwftwe.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhengqikj.top/Article/details/gtzfkzskbj.html

[F03] 写入文件（覆盖）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzkhdkoxm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ivvv.top/Article/details/gtsyciywfb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhengqikj.top/Article/details/gtwayvxhau.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nwbrower.top/Article/details/gtiyzeiwvu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gtidodppar.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.dianchejie.cn/Article/details/gtzoqpbjiq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhiwuduotai.top/Article/details/gtlykirajw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ppjwa.cn/Article/details/gtwwbbtwte.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gtvbtxnnvg.html

[F04] 追加写入文件
来源：http://dali.xziqi.cn/Article/details/gtbsukrpvq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.smart0.xyz/Article/details/gthdnoxdwv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ydzc1.top/Article/details/gtmsefrkbl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gtfvoutcdg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dianchejie.cn/Article/details/gtiswhjakc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.aibaodan.cn/Article/details/gtzhnydgym.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkywlywjb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenjidiqi.icu/Article/details/gttrdvhssn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yueranfly.top/Article/details/gtbpjbochs.html

[F05] 判断文件或目录是否存在
来源：http://dali.wangshuangyany.cn/Article/details/gtccazrqyp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.andypj.xyz/Article/details/gtzlwcewjs.html

PHP:  file_exists("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtlfltzoju.html

JS:   fs.existsSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtbhfxcnaw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtpubgotpe.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtnliuaxgl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenjidiqi.icu/Article/details/gtpbwpwxws.html

Ruby: File.exist?("a.txt")
来源：http://dali.pycfn.com/Article/details/gtrgvtglae.html

C#:   File.Exists("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtpefjmhqw.html

[F06] 删除文件
来源：http://dali.yueranfly.top/Article/details/gtordlpeqh.html

Py:   os.remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtimkdyaio.html

PHP:  unlink("a.txt");
来源：http://dali.yj20258.top/Article/details/gtsrwqhuis.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtrftfgyav.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtoczrursq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gtppabcevp.html

Go:   os.Remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtlxnufinh.html

Ruby: File.delete("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtujmhjfls.html

C#:   File.Delete("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtewwzvqxs.html

[F07] 创建目录（含多级）
来源：http://dali.aibaodan.cn/Article/details/gtzqhmwlid.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.pycfn.com/Article/details/gtauolbchf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.quarkkingdee.top/Article/details/gtlppgrecs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgfzy.top/Article/details/gtjokpnbyf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xziqi.cn/Article/details/gtmagyjiwr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.9152youxi.cn/Article/details/gtmgcsjaus.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.feifeiyinyue.top/Article/details/gthcfvozab.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.guowangkeji.top/Article/details/gtxkmjccta.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cucudq.cn/Article/details/gthxlldbwo.html

[F08] 遍历目录
来源：http://dali.yvedp.cn/Article/details/gtbbtjxwxh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yangfankeji.com/Article/details/gtkrdtlifk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwlbezwas.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtgerdprsv.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtiekpkiev.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jiagoushi.top/Article/details/gtewkidghw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj20258888.top/Article/details/gtzwqykmwa.html

Ruby: Dir.children("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpupuceqv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtjvuokufg.html

[F09] 获取文件大小
来源：http://dali.tianlin.xyz/Article/details/gthnpevymz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtxaptodyw.html

PHP:  filesize("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtkoiaiiyg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gtynblfuxb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gtdrplteoi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtpesqpusz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.mhx1999.top/Article/details/gtspuugbcx.html

Ruby: File.size("a.txt")
来源：http://dali.tanke756.top/Article/details/gtnmnggjxj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pycfn.com/Article/details/gtklsozpvg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sufxvd.cn/Article/details/gtialesnda.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtvmdtoavv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xziqi.cn/Article/details/gttbmbiqwu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtkqpbmkmp.html

TS:   path.extname("a.txt")
来源：http://dali.cheryme.top/Article/details/gtvhibcowe.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fengsongda.top/Article/details/gtmdpqpens.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtaxiklika.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gttnrkllay.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtllshhhgv.html

[F11] 复制与移动文件
来源：http://dali.sweek.top/Article/details/gtjsusazfz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtjwuzkgag.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sufxvd.cn/Article/details/gtvhpnmyic.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gttgphwokh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtfmgdotfe.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gthvtmltkl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hfpthk.cn/Article/details/gtocxxftjm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtydzxmzrs.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gaohongyu789.top/Article/details/gtmdxeeeef.html

[F12] CSV 读写
来源：http://dali.yj20258.top/Article/details/gtermvmrfr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ydzc1.top/Article/details/gtlhzkfary.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zdqjudy.top/Article/details/gtkmbgnqbv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinqigufen.top/Article/details/gtlnoqjolf.html

TS:   // 同上
来源：http://dali.ehwqpu.com/Article/details/gtfotyjsdp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hywenlv.cn/Article/details/gtznhlztis.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.daxiang520.top/Article/details/gtesuxnxzq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jianghu66.top/Article/details/gtlcflulqc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenlongwang.top/Article/details/gteznnhaag.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtejeljhkq.html

G. 面向对象
来源：http://dali.guannengcc.top/Article/details/gtzixyrfuc.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gthylreodq.html

[G01] 定义类
来源：http://dali.chenjidiqi.icu/Article/details/gtewixmxkc.html

Py:   class User: pass
来源：http://dali.shuidangran.top/Article/details/gtannzaoqw.html

PHP:  class User {}
来源：http://dali.pycfn.com/Article/details/gtfuoumykl.html

JS:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbjxzhya.html

TS:   class User { name: string = ""; }
来源：http://dali.jlsjyb.cn/Article/details/gtcsvxzxvp.html

Java: class User {}
来源：http://dali.jqgfzy.top/Article/details/gtpdpcucxq.html

Go:   type User struct { Name string }
来源：http://dali.nanxinkj.top/Article/details/gtepjzlnln.html

Ruby: class User; end
来源：http://dali.chenlongwang.top/Article/details/gtaajqedlr.html

C#:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtkvuxqjcn.html

[G02] 构造函数
来源：http://dali.yueranfly.top/Article/details/gtpiwqtngq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shangyingyoupin.top/Article/details/gtclefttmi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aizwys.cn/Article/details/gtekfzhqpd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gtcepegiuv.html

TS:   constructor(public name: string) {}
来源：http://dali.dianchejie.cn/Article/details/gtgjijlmja.html

Java: User(String name) { this.name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtywdijthy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.smart0.xyz/Article/details/gttnumehht.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj202588.top/Article/details/gtawhirgtk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.c1oappe.top/Article/details/gtdpberyjj.html

[G03] 实例属性
来源：http://dali.shangyingyoupin.top/Article/details/gtlayqubit.html

Py:   self.name = "x"
来源：http://dali.yj20258888.top/Article/details/gtkdftczgs.html

PHP:  public string $name = "x";
来源：http://dali.yvedp.cn/Article/details/gtigdsyjcg.html

JS:   this.name = "x";
来源：http://dali.yonumen.top/Article/details/gtxobfzhfw.html

TS:   name: string = "x";
来源：http://dali.yongpay.top/Article/details/gtfwzoapka.html

Java: private String name;
来源：http://dali.wangshuangyany.cn/Article/details/gtcvskkglv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.0kj1m.cn/Article/details/gtmjkwsxgw.html

Ruby: @name = "x"
来源：http://dali.jinqigufen.top/Article/details/gtqfyfihqh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.iojbl.cn/Article/details/gtqipdliib.html

[G04] 定义方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcvujsvm.html

Py:   def greet(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gtdqefulrx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gtkqprdion.html

JS:   greet() { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtyvqreaeb.html

TS:   greet(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtvyqchady.html

Java: String greet() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtjrhkpscl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gtglcvbaro.html

Ruby: def greet; @name; end
来源：http://dali.cdnleiting.top/Article/details/gtgolwkdvw.html

C#:   public string Greet() => Name;
来源：http://dali.havefunace.top/Article/details/gtraktuuqd.html

[G05] 继承
来源：http://dali.jinqigfzy.top/Article/details/gtvqbcviue.html

Py:   class Admin(User): pass
来源：http://dali.yanxiufei.cn/Article/details/gtrrnpnwbb.html

PHP:  class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtnposwesk.html

JS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtgimrcbuk.html

TS:   class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gteahqcipa.html

Java: class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtfvmabbzx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ydzc1.top/Article/details/gtgpjyraey.html

Ruby: class Admin < User; end
来源：http://dali.tanke756.top/Article/details/gtmoxfpjuv.html

C#:   class Admin : User {}
来源：http://dali.yj20258.top/Article/details/gtxtstewsw.html

[G06] 重写方法
来源：http://dali.havefunace.top/Article/details/gtuykuayhl.html

Py:   def greet(self): return "admin"
来源：http://dali.chenjidiqi.icu/Article/details/gtwkupccuw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gttskuleqn.html

JS:   greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gturqpjkiq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtwbsrhxcd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtsjhfshdl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shanyushiyangkeji.top/Article/details/gtizqysoas.html

Ruby: def greet; "admin"; end
来源：http://dali.cqqwz.cn/Article/details/gtvjclauqa.html

C#:   public override string Greet() => "admin";
来源：http://dali.hammf.cn/Article/details/gtayiwnohc.html

[G07] 调用父类方法
来源：http://dali.yanxiufei.cn/Article/details/gtgxnbwlwm.html

Py:   super().greet()
来源：http://dali.yvedp.cn/Article/details/gtvdmzxzsg.html

PHP:  parent::greet();
来源：http://dali.jqgufenzy.top/Article/details/gtphwlgvxr.html

JS:   super.greet();
来源：http://dali.9152youxi.cn/Article/details/gtjiaeunyz.html

TS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gtxqltutyk.html

Java: super.greet();
来源：http://dali.dianchejie.cn/Article/details/gtawvjhckt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.redwolf501.top/Article/details/gtiwedvced.html

Ruby: super
来源：http://dali.guowangkeji.top/Article/details/gtxeskrzqg.html

C#:   base.Greet();
来源：http://dali.hnxiangtu.top/Article/details/gtublvxvdr.html

[G08] 静态方法与属性
来源：http://dali.birdmap.top/Article/details/gtthkphmoc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pycfn.com/Article/details/gtjvkvkfpe.html

PHP:  public static function f() {}
来源：http://dali.chenzaomai.com/Article/details/gtqbhoyrdp.html

JS:   static f() {}
来源：http://dali.cucudq.cn/Article/details/gtmwmgfbrv.html

TS:   static f(): void {}
来源：http://dali.quarkkingdee.top/Article/details/gtxpnpvmvf.html

Java: static void f() {}
来源：http://dali.hywenlv.cn/Article/details/gtggxqcobs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuetiantiany.cn/Article/details/gtyasdhkkn.html

Ruby: def self.f; end
来源：http://dali.sufxvd.cn/Article/details/gtgcldpawo.html

C#:   public static void F() {}
来源：http://dali.shuidangran.top/Article/details/gtjkqrzabw.html

[G09] 接口 / 抽象类
来源：http://dali.tian-w.cn/Article/details/gtihhgddqt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ydzc1.top/Article/details/gtxlyspqzh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guowangkeji.top/Article/details/gtzxotghdq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tian-w.cn/Article/details/gtbuermwtd.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangdashe.top/Article/details/gtmpfbihdv.html

Java: interface Shape { double area(); }
来源：http://dali.sxryk.cn/Article/details/gttkuqfzky.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jlsjyb.cn/Article/details/gtallbpzwl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258888.top/Article/details/gtpakfomes.html

C#:   interface IShape { double Area(); }
来源：http://dali.svipenyu.cn/Article/details/gtjoeohdoj.html

[G10] 访问控制
来源：http://dali.birdmap.top/Article/details/gtotfpmqbv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zdqjudy.top/Article/details/gtldmynodc.html

PHP:  public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtripqcxnj.html

JS:   #private 字段；其余公开
来源：http://dali.ydzc1.top/Article/details/gtgrrprwee.html

TS:   public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtrttfknks.html

Java: public / protected / private / 默认包级
来源：http://dali.smart0.xyz/Article/details/gtnwftabut.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nwbrower.top/Article/details/gtaquwrsls.html

Ruby: public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtqefdvokg.html

C#:   public / protected / private / internal
来源：http://dali.kuanghao11.cn/Article/details/gtefnqgznq.html

[G11] getter / setter
来源：http://dali.9152youxi.cn/Article/details/gtjbvhtaym.html

Py:   @property 与 @x.setter
来源：http://dali.wangdashe.top/Article/details/gtdchrxhdz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtwfiuhtcs.html

JS:   get name() { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gtujhsoxzp.html

TS:   get name(): string { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gtcfhjsoiz.html

Java: public String getName() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gtdvwbuylm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtfurnoumh.html

Ruby: attr_accessor :name
来源：http://dali.dianchejie.cn/Article/details/gtskqplxpe.html

C#:   public string Name { get; set; }
来源：http://dali.yangfankeji.com/Article/details/gtxfunznky.html

[G12] 对象转字符串
来源：http://dali.pycfn.com/Article/details/gtjghiarwg.html

Py:   def __str__(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gtfwcvqeeo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gtlihvazwb.html

JS:   toString() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtcmlmquld.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtwwyzamqc.html

Java: @Override public String toString() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqanwchhk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gtqrmmagak.html

Ruby: def to_s; @name; end
来源：http://dali.guannengcc.top/Article/details/gtdjwnvmam.html

C#:   public override string ToString() => Name;
来源：http://dali.zhengqikj.top/Article/details/gtdzqervfn.html

[G13] 判断对象类型
来源：http://dali.tanke756.top/Article/details/gtomzuxmip.html

Py:   isinstance(u, User)
来源：http://dali.zhengqikj.top/Article/details/gtaxaocggp.html

PHP:  $u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtxdenqnfa.html

JS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gthqhlogub.html

TS:   u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtkcnowwxz.html

Java: u instanceof User
来源：http://dali.cheryme.top/Article/details/gtmungorfa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hammf.cn/Article/details/gtpwxaleal.html

Ruby: u.is_a?(User)
来源：http://dali.zycfv.cn/Article/details/gtoznhnlit.html

C#:   u is User
来源：http://dali.ydzc1.top/Article/details/gtowrixafy.html

[G14] 数据类 / record
来源：http://dali.yj20258.top/Article/details/gthisihjdu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xziqi.cn/Article/details/gthtlcjffw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cucudq.cn/Article/details/gtgxuqyvqz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gotoacloud.top/Article/details/gtccodugim.html

TS:   type User = { name: string; age: number };
来源：http://dali.yvedp.cn/Article/details/gtkomglhsn.html

Java: record User(String name, int age) {}
来源：http://dali.jinqigfzy.top/Article/details/gtcmsojzpe.html

Go:   type User struct { Name string; Age int }
来源：http://dali.daxiang520.top/Article/details/gtaxveuqtw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yueranfly.top/Article/details/gtpnnjlvgo.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258888.top/Article/details/gtojruokgu.html

[G15] 枚举
来源：http://dali.yj202588.top/Article/details/gtxicqrmpp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.redwolf501.top/Article/details/gtzpisvcgn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258.top/Article/details/gtuyjrhfin.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhtzlehx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gtrivmopgn.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj20258888.top/Article/details/gtemmjtgrc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yongpay.top/Article/details/gtibbxzwmh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.9152youxi.cn/Article/details/gtnugefmdl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gtusqsktws.html

[G16] 对象转数组 / 字典
来源：http://dali.xylfe.cn/Article/details/gtjojnozht.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aibaodan.cn/Article/details/gtdvtepwxt.html

PHP:  get_object_vars($obj);
来源：http://dali.daria6918.cn/Article/details/gtqvygyite.html

JS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gthtxcgvte.html

TS:   Object.entries(obj)
来源：http://dali.316326.xyz/Article/details/gtxnnyseqd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jlsjyb.cn/Article/details/gtyfnbbfro.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.c1oappe.top/Article/details/gtbyxybrel.html

Ruby: obj.instance_variables
来源：http://dali.hnqzz.top/Article/details/gtwojwwqii.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gtklfoptvd.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtjilreauj.html


<!-- 参考信息 -->