代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.wangdashe.top/Article/details/gtebecxxxd.html

[E19] 多行文本按行拆分
来源：http://dali.mhx1999.top/Article/details/gtuosspeku.html

Py:   s.splitlines()
来源：http://dali.zhoulong.xyz/Article/details/gtxobbdosi.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtotuycbqv.html

JS:   s.split(/\r?\n/)
来源：http://dali.gaohongyu789.top/Article/details/gtbdywrffk.html

TS:   s.split(/\r?\n/)
来源：http://dali.nwbrower.top/Article/details/gttnwrtfsx.html

Java: s.lines().toList()
来源：http://dali.zhongyouzk.top/Article/details/gtdvrbuygn.html

Go:   strings.Split(s, "\n")
来源：http://dali.hfpthk.cn/Article/details/gtwxghxnao.html

Ruby: s.lines
来源：http://dali.zhoulong.xyz/Article/details/gtsbevnjvy.html

C#:   s.Split('\n')
来源：http://dali.jyoumei.cn/Article/details/gtkjdsvjoy.html

[E20] 判断字符串是否为空
来源：http://dali.fzhhl.top/Article/details/gtirvgmgbm.html

Py:   if not s:
来源：http://dali.zycfv.cn/Article/details/gtqoekctkq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.quarkkingdee.top/Article/details/gtabjbxshi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yuanzhike.top/Article/details/gtbmrcspjz.html

TS:   if (s === "") {}
来源：http://dali.jqgufenzy.top/Article/details/gttcdhooag.html

Java: if (s.isEmpty()) {}
来源：http://dali.fzhhl.top/Article/details/gtbynvjzcx.html

Go:   if s == "" {}
来源：http://dali.hammf.cn/Article/details/gtimbrcmsn.html

Ruby: if s.empty?
来源：http://dali.sxryk.cn/Article/details/gtgrruquth.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.iojbl.cn/Article/details/gtbutiqxae.html

[E21] 超长截断加省略号
来源：http://dali.smart0.xyz/Article/details/gtfivqzpya.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.bjfxy.top/Article/details/gtkoqfiosf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtfhztcmwj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtngwunrrs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtditqzzzp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtvdtjffsb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hnxiangtu.top/Article/details/gttenlqrgz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gtjwzfrupu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtktbpyhsa.html

[E22] 字节长度与字符长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtizajdhtw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sysykeji.top/Article/details/gtccijeujm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtiumzxegd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daria6918.cn/Article/details/gtmtekbpbl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.haohaochexian.top/Article/details/gtmxhzgwsr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hfpthk.cn/Article/details/gtgtolhfxk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ppjwa.cn/Article/details/gtugrxfqcf.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj20258.top/Article/details/gtvdmxdbsk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cdnleiting.top/Article/details/gtoynboizy.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtwjvldvbi.html

F. 文件与目录
来源：http://dali.aibaodan.cn/Article/details/gthttiaffj.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtoyjjdtbb.html

[F01] 读取整个文件
来源：http://dali.wangdashe.top/Article/details/gtwrswedqd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sweek.top/Article/details/gtaqkcivpx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtgklgomcg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nanxinkj.top/Article/details/gtmoecdywq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hnqzz.top/Article/details/gteweytfgr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gthywnftzv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zdqjudy.top/Article/details/gtqqmzfpbn.html

Ruby: File.read("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtlpkbrarg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtjduwhimd.html

[F02] 逐行读取文件
来源：http://dali.nanxuanxn.top/Article/details/gtsfnyurwt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xziqi.cn/Article/details/gtnsjrsojl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sysykeji.top/Article/details/gtyvvqhzcc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.redwolf501.top/Article/details/gthflildiq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.havefunace.top/Article/details/gtfffasmjy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gtdnraommu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yonumen.top/Article/details/gtauytarbd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ivvv.top/Article/details/gtqdfxufrh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.feifeiyinyue.top/Article/details/gtwwicwgti.html

[F03] 写入文件（覆盖）
来源：http://dali.hysaishi.cn/Article/details/gtkkmdnthw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenzaomai.com/Article/details/gthzlepsgb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sweek.top/Article/details/gtlmiqabep.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gtqsucthwk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gtoufbpuxi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ppjwa.cn/Article/details/gterxkrvkv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gaohongyu789.top/Article/details/gttmwyccvp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuxming.cn/Article/details/gtbrtebhxj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.aizwys.cn/Article/details/gtclxesfmn.html

[F04] 追加写入文件
来源：http://dali.zhongyouzk.top/Article/details/gtrswxbxxd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj202588.top/Article/details/gtjibbjfrc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hnqzz.top/Article/details/gtmkveydry.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gtwexlqzdb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gtfbdpxurz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yanxiufei.cn/Article/details/gtzehmruyc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtengurthj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.fengsongda.top/Article/details/gtmoalqfok.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jqgufenzy.top/Article/details/gttwnkycgy.html

[F05] 判断文件或目录是否存在
来源：http://dali.cdnleiting.top/Article/details/gtoehagzpm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.c1oappe.top/Article/details/gtvblqefhu.html

PHP:  file_exists("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtoymhyafy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtocbygnng.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtjoujodjc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtqsecasxc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj20258888.top/Article/details/gtxzbydpsf.html

Ruby: File.exist?("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtqtdznlqp.html

C#:   File.Exists("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtwlqtkslp.html

[F06] 删除文件
来源：http://dali.hywenlv.cn/Article/details/gtblnkrjlz.html

Py:   os.remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gtyuwddatd.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzcqxbnnu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtelgzdpio.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtejsputcy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtrxkdeurc.html

Go:   os.Remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtlthuqlst.html

Ruby: File.delete("a.txt")
来源：http://dali.birdmap.top/Article/details/gtpmbkpgzs.html

C#:   File.Delete("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtkvqahbjl.html

[F07] 创建目录（含多级）
来源：http://dali.yonumen.top/Article/details/gtlktwncit.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.svipenyu.cn/Article/details/gtzgdomrfo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hnxiangtu.top/Article/details/gtqnhgclnh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gtsimhernm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gtlijwwogu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cqqwz.cn/Article/details/gtozlymkbn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tanke756.top/Article/details/gtrvxzvruu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zycfv.cn/Article/details/gtlfkokatn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hnxiangtu.top/Article/details/gtpqmmvyma.html

[F08] 遍历目录
来源：http://dali.gotoacloud.top/Article/details/gtjlyezceb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tian-w.cn/Article/details/gtanzgfemi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gaohongyu789.top/Article/details/gtonzxaffq.html

JS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gtaxbdekas.html

TS:   fs.readdirSync("dir")
来源：http://dali.xziqi.cn/Article/details/gtaexvcpbg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ybcxt.top/Article/details/gtthlmgpfs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ybcxt.top/Article/details/gtmclsnbie.html

Ruby: Dir.children("dir")
来源：http://dali.iojbl.cn/Article/details/gtxabaczfj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.daria6918.cn/Article/details/gtwsaqjniv.html

[F09] 获取文件大小
来源：http://dali.kuanghao11.cn/Article/details/gtmgxrdyvn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtdzxfueqw.html

PHP:  filesize("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtcyaiwfsk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gtdbnmwppl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sufxvd.cn/Article/details/gtgkprwzal.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gtchzhtxzm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.pycfn.com/Article/details/gttpkvqqtc.html

Ruby: File.size("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtxkajdmgl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tian-w.cn/Article/details/gtvkobaqbv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.redwolf501.top/Article/details/gtscylniic.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtaibuvihr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.316326.xyz/Article/details/gtkyibsyqh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtntuycggf.html

TS:   path.extname("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtconeunxm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangshuangyany.cn/Article/details/gtqfeshrcs.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtpvmyrjrk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gttvyrobrj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtqajxkorl.html

[F11] 复制与移动文件
来源：http://dali.shangyingyoupin.top/Article/details/gtsjadnbeb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtohbxqhfu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xziqi.cn/Article/details/gtasruldkg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtwwbieyhp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtmzxkavmz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guowangkeji.top/Article/details/gtxpiyeyuy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hysaishi.cn/Article/details/gthjlmdtjd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtdrwrukpc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ybcxt.top/Article/details/gteuetujzq.html

[F12] CSV 读写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxdjdxdk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xylfe.cn/Article/details/gtmtuhosxw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.pengpengdd.cyou/Article/details/gtjxwslsya.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sweek.top/Article/details/gtwqspgosa.html

TS:   // 同上
来源：http://dali.iojbl.cn/Article/details/gteqehgesm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.guowangkeji.top/Article/details/gtsqdwilnk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.quarkkingdee.top/Article/details/gtvhpjixnd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gzhubu.top/Article/details/gtccneagac.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ydzc1.top/Article/details/gtepkoerih.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtskjwlojk.html

G. 面向对象
来源：http://dali.9152youxi.cn/Article/details/gttkihycgf.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtzklxdwad.html

[G01] 定义类
来源：http://dali.shzxlz.cn/Article/details/gtgcirfgkk.html

Py:   class User: pass
来源：http://dali.cashguo.top/Article/details/gtdeievlee.html

PHP:  class User {}
来源：http://dali.yuanzhike.top/Article/details/gtzjdkaubm.html

JS:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gtauobodiz.html

TS:   class User { name: string = ""; }
来源：http://dali.havefunace.top/Article/details/gtkuucrhos.html

Java: class User {}
来源：http://dali.yueranfly.top/Article/details/gtqyfvpqsx.html

Go:   type User struct { Name string }
来源：http://dali.snrcjt.cn/Article/details/gtmwipmimo.html

Ruby: class User; end
来源：http://dali.tian-w.cn/Article/details/gtohtipvyu.html

C#:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gtkgmngfxv.html

[G02] 构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gtseazrykq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fzhhl.top/Article/details/gtrklryimq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ehwqpu.com/Article/details/gtxhkuzwtd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gtqactniwd.html

TS:   constructor(public name: string) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtlatpavmo.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gtpvsvgpau.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jqgfzy.top/Article/details/gthuwnuqvn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zdqjudy.top/Article/details/gtqozreoxb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cqqwz.cn/Article/details/gtbietxnde.html

[G03] 实例属性
来源：http://dali.yvedp.cn/Article/details/gtvxlmswks.html

Py:   self.name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gtfykxujrt.html

PHP:  public string $name = "x";
来源：http://dali.smart0.xyz/Article/details/gteudgskdc.html

JS:   this.name = "x";
来源：http://dali.cdnleiting.top/Article/details/gtvvwdczxw.html

TS:   name: string = "x";
来源：http://dali.sysykeji.top/Article/details/gtenqiwqru.html

Java: private String name;
来源：http://dali.jqgufenzy.top/Article/details/gtjlmztdrq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnskqgjf.html

Ruby: @name = "x"
来源：http://dali.zdqjudy.top/Article/details/gteniwrcez.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aibaodan.cn/Article/details/gtdzilvspn.html

[G04] 定义方法
来源：http://dali.gzhubu.top/Article/details/gtpkigztgt.html

Py:   def greet(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgeuaxcy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtouydwczh.html

JS:   greet() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtnpjxzunt.html

TS:   greet(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gthnsafbmb.html

Java: String greet() { return name; }
来源：http://dali.birdmap.top/Article/details/gtrjwukbub.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gtbytwlfht.html

Ruby: def greet; @name; end
来源：http://dali.nanxinkj.top/Article/details/gtxszqnjet.html

C#:   public string Greet() => Name;
来源：http://dali.tianlin.xyz/Article/details/gtyxfxmwlv.html

[G05] 继承
来源：http://dali.snrcjt.cn/Article/details/gtvrhlqbik.html

Py:   class Admin(User): pass
来源：http://dali.guannengcc.top/Article/details/gtnqdehuqb.html

PHP:  class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtlrmfkvuc.html

JS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtdrjkjyxy.html

TS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtziifweza.html

Java: class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtbhjnsfia.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.daria6918.cn/Article/details/gtbsakjinr.html

Ruby: class Admin < User; end
来源：http://dali.jqgfzy.top/Article/details/gtlykdgquv.html

C#:   class Admin : User {}
来源：http://dali.yanxiufei.cn/Article/details/gtonyeflja.html

[G06] 重写方法
来源：http://dali.sufxvd.cn/Article/details/gtxtmcrywa.html

Py:   def greet(self): return "admin"
来源：http://dali.sysykeji.top/Article/details/gtliklugbw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtgfloxsfk.html

JS:   greet() { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtarxcfwan.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtdegouava.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtyzlqrlex.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.haohaochexian.top/Article/details/gtxbnchqiy.html

Ruby: def greet; "admin"; end
来源：http://dali.cashguo.top/Article/details/gtdlhwtivx.html

C#:   public override string Greet() => "admin";
来源：http://dali.yonumen.top/Article/details/gtpdmymqcj.html

[G07] 调用父类方法
来源：http://dali.jqgfzy.top/Article/details/gtyhmdzlro.html

Py:   super().greet()
来源：http://dali.andypj.xyz/Article/details/gtjciqgcpe.html

PHP:  parent::greet();
来源：http://dali.birdmap.top/Article/details/gtyxayquul.html

JS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gtrqtgbxoh.html

TS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtomaytamr.html

Java: super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgpqmwfj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hywenlv.cn/Article/details/gttayjvlpy.html

Ruby: super
来源：http://dali.gzhubu.top/Article/details/gtoomqxqec.html

C#:   base.Greet();
来源：http://dali.hywenlv.cn/Article/details/gtodmxlomf.html

[G08] 静态方法与属性
来源：http://dali.daxiang520.top/Article/details/gtnjwuolqm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xylfe.cn/Article/details/gtbumflzid.html

PHP:  public static function f() {}
来源：http://dali.iojbl.cn/Article/details/gtxmfiiujv.html

JS:   static f() {}
来源：http://dali.daria6918.cn/Article/details/gteacjehpv.html

TS:   static f(): void {}
来源：http://dali.yanxiufei.cn/Article/details/gtdpoydmau.html

Java: static void f() {}
来源：http://dali.tianlin.xyz/Article/details/gtiocedofl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zycfv.cn/Article/details/gtqvzmncid.html

Ruby: def self.f; end
来源：http://dali.jiagoushi.top/Article/details/gtnsvibopm.html

C#:   public static void F() {}
来源：http://dali.ybcxt.top/Article/details/gtvwonmdje.html

[G09] 接口 / 抽象类
来源：http://dali.chenlongwang.top/Article/details/gthegqjahn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cucudq.cn/Article/details/gtbjczgaal.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sxryk.cn/Article/details/gtsyagxknj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.9152youxi.cn/Article/details/gtvlvgvcfw.html

TS:   interface Shape { area(): number; }
来源：http://dali.ydzc1.top/Article/details/gthqrnyzfc.html

Java: interface Shape { double area(); }
来源：http://dali.xziqi.cn/Article/details/gtxouvsawd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.svipenyu.cn/Article/details/gtzfpaesgn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenlongwang.top/Article/details/gtemisbyhf.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtcecnhqwx.html

[G10] 访问控制
来源：http://dali.xuetiantiany.cn/Article/details/gtlrbawxsi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.havefunace.top/Article/details/gtwvxyxncw.html

PHP:  public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtmhwdkzlf.html

JS:   #private 字段；其余公开
来源：http://dali.pycfn.com/Article/details/gtonxlppnn.html

TS:   public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gtrqtuisuv.html

Java: public / protected / private / 默认包级
来源：http://dali.snrcjt.cn/Article/details/gtpgqxdftk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258888.top/Article/details/gttrtfqmfd.html

Ruby: public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gtblluutkz.html

C#:   public / protected / private / internal
来源：http://dali.jqgufenzy.top/Article/details/gtlqfhxvsq.html

[G11] getter / setter
来源：http://dali.hammf.cn/Article/details/gtqubmjbwj.html

Py:   @property 与 @x.setter
来源：http://dali.andypj.xyz/Article/details/gtdxlbcyvy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gtitxhnjtx.html

JS:   get name() { return this._name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkrectjc.html

TS:   get name(): string { return this._name; }
来源：http://dali.gogol.net.cn/Article/details/gtuqttzbty.html

Java: public String getName() { return name; }
来源：http://dali.fzhhl.top/Article/details/gtnuzokcju.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gtmkvwwsut.html

Ruby: attr_accessor :name
来源：http://dali.fzhhl.top/Article/details/gtnidzbygl.html

C#:   public string Name { get; set; }
来源：http://dali.wangdashe.top/Article/details/gtqkjuwedb.html

[G12] 对象转字符串
来源：http://dali.shzxlz.cn/Article/details/gtjbnkebae.html

Py:   def __str__(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gtcfwbqcom.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gtgdmzaedm.html

JS:   toString() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtdlhpjzay.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtbsomelfc.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangdashe.top/Article/details/gthskchjkt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtymzsfcol.html

Ruby: def to_s; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqjxcyboc.html

C#:   public override string ToString() => Name;
来源：http://dali.cashguo.top/Article/details/gtiiyfusly.html

[G13] 判断对象类型
来源：http://dali.zhixingplan.top/Article/details/gtsjxmhhdv.html

Py:   isinstance(u, User)
来源：http://dali.ybcxt.top/Article/details/gtsqmfltkl.html

PHP:  $u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtqjsxnykz.html

JS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtnallqzip.html

TS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvrmryoy.html

Java: u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gthmkeaoqb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ydzc1.top/Article/details/gtnnwfxukf.html

Ruby: u.is_a?(User)
来源：http://dali.fengsongda.top/Article/details/gtszgnhcla.html

C#:   u is User
来源：http://dali.hammf.cn/Article/details/gthywrvyih.html

[G14] 数据类 / record
来源：http://dali.yvedp.cn/Article/details/gtfvvbflbm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhongyouzk.top/Article/details/gtaezqapde.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.daria6918.cn/Article/details/gtftlrxygz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gzhubu.top/Article/details/gtrcnmobbh.html

TS:   type User = { name: string; age: number };
来源：http://dali.sysykeji.top/Article/details/gtdbhlstbu.html

Java: record User(String name, int age) {}
来源：http://dali.daxiang520.top/Article/details/gtbubogjsu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ybcxt.top/Article/details/gtcmvbeyli.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ydzc1.top/Article/details/gtaniuxbmh.html

C#:   record User(string Name, int Age);
来源：http://dali.ivvv.top/Article/details/gtbyxnwtgp.html

[G15] 枚举
来源：http://dali.jlsjyb.cn/Article/details/gtiefnljoc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuetiantiany.cn/Article/details/gtkvcfoixk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.redwolf501.top/Article/details/gteepxenjh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xziqi.cn/Article/details/gteeefqamv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shzxlz.cn/Article/details/gtkbxjmcdl.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhengqikj.top/Article/details/gtxcrzwehe.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nanxuanxn.top/Article/details/gtpixuriel.html

Ruby: Color = %i[red green].freeze
来源：http://dali.c1oappe.top/Article/details/gtegxyrzqy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gtdrrnjnno.html

[G16] 对象转数组 / 字典
来源：http://dali.zhoulong.xyz/Article/details/gtrzizkgnu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sufxvd.cn/Article/details/gtxzyngdco.html

PHP:  get_object_vars($obj);
来源：http://dali.nwbrower.top/Article/details/gtrheqdlsa.html

JS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gtnhpppbfn.html

TS:   Object.entries(obj)
来源：http://dali.redwolf501.top/Article/details/gtgboooksf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhiwuduotai.top/Article/details/gtsdkcfwtt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sufxvd.cn/Article/details/gtytadrkni.html

Ruby: obj.instance_variables
来源：http://dali.ehwqpu.com/Article/details/gtzgxeiowx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.c1oappe.top/Article/details/gtkmxiotyt.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtdlvkmpfo.html

H. 异常与错误处理
来源：http://dali.xylfe.cn/Article/details/gtzfwvtzpn.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtmwveihpl.html

[H01] try / catch 基础
来源：http://dali.jianghu66.top/Article/details/gtemkbfamv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yongpay.top/Article/details/gtrftjbutu.html


<!-- 参考信息 -->