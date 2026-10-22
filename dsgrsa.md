代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnzczxwht.html

[E19] 多行文本按行拆分
来源：http://dali.svipenyu.cn/Article/details/gtejnawajo.html

Py:   s.splitlines()
来源：http://dali.zdqjudy.top/Article/details/gtenlcckqn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.birdmap.top/Article/details/gtvhjngkgb.html

JS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gtomeiiuqg.html

TS:   s.split(/\r?\n/)
来源：http://dali.gogol.net.cn/Article/details/gtqzqcxhzt.html

Java: s.lines().toList()
来源：http://dali.redwolf501.top/Article/details/gtjluldwql.html

Go:   strings.Split(s, "\n")
来源：http://dali.andypj.xyz/Article/details/gtrsruvhkv.html

Ruby: s.lines
来源：http://dali.fengsongda.top/Article/details/gtvgrixkml.html

C#:   s.Split('\n')
来源：http://dali.svipenyu.cn/Article/details/gtxugfcbyy.html

[E20] 判断字符串是否为空
来源：http://dali.yj20258888.top/Article/details/gtwqdeplzo.html

Py:   if not s:
来源：http://dali.gzhubu.top/Article/details/gtgucaoupq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zdqjudy.top/Article/details/gtsywbcqzp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jqgufenzy.top/Article/details/gtduxtpzuj.html

TS:   if (s === "") {}
来源：http://dali.jiagoushi.top/Article/details/gtnywqibed.html

Java: if (s.isEmpty()) {}
来源：http://dali.yuxming.cn/Article/details/gthnlnafsz.html

Go:   if s == "" {}
来源：http://dali.shangyingyoupin.top/Article/details/gtjwinymwz.html

Ruby: if s.empty?
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmdyvepo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.guowangkeji.top/Article/details/gtwxzystyn.html

[E21] 超长截断加省略号
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkqesfqfd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pycfn.com/Article/details/gtjkdqglcu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtzzoxjahz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gtoynllbwa.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gthsxtschi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtyzuxibic.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gtepxvjkth.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtelbbnegl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtdfdstcrq.html

[E22] 字节长度与字符长度
来源：http://dali.yonumen.top/Article/details/gtsqfyoiqh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zdqjudy.top/Article/details/gteuphterk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gtzjxlnxpa.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gtesvzxsal.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gtggsooxnu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenjidiqi.icu/Article/details/gtoxflkmfw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shangyingyoupin.top/Article/details/gttayssdpv.html

Ruby: s.bytesize;  s.length
来源：http://dali.9152youxi.cn/Article/details/gtqjjpluch.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj20258888.top/Article/details/gtstbvxznn.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtekzqfdpd.html

F. 文件与目录
来源：http://dali.guowangkeji.top/Article/details/gtkanlvzto.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtcilthfqz.html

[F01] 读取整个文件
来源：http://dali.zycfv.cn/Article/details/gtgtqqalwk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.wangdashe.top/Article/details/gtxlokwabb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtemrscxne.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tanke756.top/Article/details/gtwknmfwgy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.andypj.xyz/Article/details/gttuxycxxk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtopzdnhlk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.316326.xyz/Article/details/gtbjxrckaj.html

Ruby: File.read("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtrlbsmsho.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtwmaqtdbm.html

[F02] 逐行读取文件
来源：http://dali.wangshuangyany.cn/Article/details/gtjsyaghoc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yuxming.cn/Article/details/gtwlcszsbj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtuytamjiu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gtoovcrspg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigufen.top/Article/details/gtquezkbky.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jyoumei.cn/Article/details/gtzcuawvly.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nanxinkj.top/Article/details/gtcalpudzg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shuidangran.top/Article/details/gtwxkjahda.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqiwdqaqu.html

[F03] 写入文件（覆盖）
来源：http://dali.pycfn.com/Article/details/gtxtoagcdo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yanxiufei.cn/Article/details/gtldqfnuds.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhengqikj.top/Article/details/gtzgwvlszp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gttrbbzhxy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gtbwrdibsg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xinyue.icu/Article/details/gtszttmxxu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ppjwa.cn/Article/details/gtlmxuwjss.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cashguo.top/Article/details/gtsyuunulq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gtogvgciae.html

[F04] 追加写入文件
来源：http://dali.pengpengdd.cyou/Article/details/gtjnshmfhg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtobzxobco.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.iojbl.cn/Article/details/gtwzbvusqx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tanke756.top/Article/details/gtoolllsik.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gtzulzjlor.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.316326.xyz/Article/details/gtltxubbva.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenzaomai.com/Article/details/gtvzkwxbpo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tian-w.cn/Article/details/gttgggcdej.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cucudq.cn/Article/details/gtrjfyhfwb.html

[F05] 判断文件或目录是否存在
来源：http://dali.guowangkeji.top/Article/details/gtwhgqknkl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guannengcc.top/Article/details/gtvsffdeml.html

PHP:  file_exists("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtzjhpwgrm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtacsitkqf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxngmqjjj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtpzctjlrx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.fengsongda.top/Article/details/gteqenvpez.html

Ruby: File.exist?("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtplgempfd.html

C#:   File.Exists("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtpfjgrmfa.html

[F06] 删除文件
来源：http://dali.iojbl.cn/Article/details/gtyphaobzd.html

Py:   os.remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtegjlmoit.html

PHP:  unlink("a.txt");
来源：http://dali.cheryme.top/Article/details/gtdttnxcku.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtjbvkbsiu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtnmmzcezx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtbjdgtslk.html

Go:   os.Remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzqzdhgyh.html

Ruby: File.delete("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtfayxefwy.html

C#:   File.Delete("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtycfmesyp.html

[F07] 创建目录（含多级）
来源：http://dali.xylfe.cn/Article/details/gtauntkpsf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yangfankeji.com/Article/details/gtldhrrbml.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkcyegpyw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gtssopjmgo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.smart0.xyz/Article/details/gtvhsplqgo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigufen.top/Article/details/gtflvqoboo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daria6918.cn/Article/details/gtowsldvra.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.fzhhl.top/Article/details/gtfspjhpjk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yanxiufei.cn/Article/details/gtqxajfbnw.html

[F08] 遍历目录
来源：http://dali.chenlongwang.top/Article/details/gtdipuxmqq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.aizwys.cn/Article/details/gtitwxhinf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhoulong.xyz/Article/details/gtfprxptmi.html

JS:   fs.readdirSync("dir")
来源：http://dali.pycfn.com/Article/details/gtkwhxawwa.html

TS:   fs.readdirSync("dir")
来源：http://dali.sweek.top/Article/details/gthwigsdjg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gtxaxfnpxb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gotoacloud.top/Article/details/gtnhzwznti.html

Ruby: Dir.children("dir")
来源：http://dali.zdqjudy.top/Article/details/gtzrlmumtm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.smart0.xyz/Article/details/gtumclqnai.html

[F09] 获取文件大小
来源：http://dali.havefunace.top/Article/details/gtalaowunc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj20258.top/Article/details/gtqjxzohyf.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtpjzbogma.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gaohongyu789.top/Article/details/gtefblqxjv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gtwwoxnkfc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtcnxqmeau.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jyoumei.cn/Article/details/gthlgjkyfx.html

Ruby: File.size("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtebvnbrlj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ivvv.top/Article/details/gtjqjhizff.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fengsongda.top/Article/details/gtkqdvhdgi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtthwiksgs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtrmlsyeim.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gteatdokyt.html

TS:   path.extname("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtrxtsbqpw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.kuanghao11.cn/Article/details/gtvawymeqh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gthruygpls.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvozzxjq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtxdkafcom.html

[F11] 复制与移动文件
来源：http://dali.cashguo.top/Article/details/gtceglbdzk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtepgwkmel.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenzaomai.com/Article/details/gtsjggpdei.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtlmgdfoih.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtsnuuynaz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cashguo.top/Article/details/gtqtcxbrwz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yonumen.top/Article/details/gtfbhgwfag.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtfghejymu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yonumen.top/Article/details/gtowqrvehd.html

[F12] CSV 读写
来源：http://dali.c1oappe.top/Article/details/gtcfwmgrij.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cheryme.top/Article/details/gtromevmgu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.316326.xyz/Article/details/gtzqvckgbu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cheryme.top/Article/details/gtjirnkhlh.html

TS:   // 同上
来源：http://dali.yj202588.top/Article/details/gtlkezzsxp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.mhx1999.top/Article/details/gtrckoahvz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.havefunace.top/Article/details/gtwoplixzg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.haohaochexian.top/Article/details/gtdpkqncgt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.c1oappe.top/Article/details/gtrdgweeno.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtddkyuizl.html

G. 面向对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtvgirigzd.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtwjuaejkk.html

[G01] 定义类
来源：http://dali.nwbrower.top/Article/details/gtsppvscqe.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gtxoojtnki.html

PHP:  class User {}
来源：http://dali.hysaishi.cn/Article/details/gtcnlvpgem.html

JS:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtxbngsrve.html

TS:   class User { name: string = ""; }
来源：http://dali.pengpengdd.cyou/Article/details/gtuevythcj.html

Java: class User {}
来源：http://dali.chenlongwang.top/Article/details/gtbhiysgai.html

Go:   type User struct { Name string }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtslmzddti.html

Ruby: class User; end
来源：http://dali.yueranfly.top/Article/details/gtbsirgbno.html

C#:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gtyizfjizb.html

[G02] 构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbqurwvfb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shuidangran.top/Article/details/gtpyjghnnt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.snrcjt.cn/Article/details/gtmcrfxwvg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gthfykzqbe.html

TS:   constructor(public name: string) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtuajqnong.html

Java: User(String name) { this.name = name; }
来源：http://dali.hysaishi.cn/Article/details/gtdtluskkg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjkpilntw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gaohongyu789.top/Article/details/gtmaazratv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.fengsongda.top/Article/details/gtsdbfbqrg.html

[G03] 实例属性
来源：http://dali.gaohongyu789.top/Article/details/gtshxhgdry.html

Py:   self.name = "x"
来源：http://dali.jqgfzy.top/Article/details/gtvqowchqx.html

PHP:  public string $name = "x";
来源：http://dali.jinqigufen.top/Article/details/gtralihbrk.html

JS:   this.name = "x";
来源：http://dali.jqgfzy.top/Article/details/gtkoibxcst.html

TS:   name: string = "x";
来源：http://dali.jinqigufen.top/Article/details/gtpvheiqsj.html

Java: private String name;
来源：http://dali.ydzc1.top/Article/details/gtnmgnwhkt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ybcxt.top/Article/details/gttsingcrz.html

Ruby: @name = "x"
来源：http://dali.jinqigufen.top/Article/details/gtqbyvnsbb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.smart0.xyz/Article/details/gtahuklbcd.html

[G04] 定义方法
来源：http://dali.sufxvd.cn/Article/details/gtonznofhf.html

Py:   def greet(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gtxknfpweh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtlpobnqdt.html

JS:   greet() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gteyxikmfs.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtnrizjsec.html

Java: String greet() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtcuehxijf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtjfdzldac.html

Ruby: def greet; @name; end
来源：http://dali.wangdashe.top/Article/details/gtgyrtlqtc.html

C#:   public string Greet() => Name;
来源：http://dali.zycfv.cn/Article/details/gtvyezaqkq.html

[G05] 继承
来源：http://dali.yuxming.cn/Article/details/gthgqjeess.html

Py:   class Admin(User): pass
来源：http://dali.zhongyouzk.top/Article/details/gtauyklskx.html

PHP:  class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtaojsvmyc.html

JS:   class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gthqicupia.html

TS:   class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gttrktfmrj.html

Java: class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtzfsiicug.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.mhx1999.top/Article/details/gtgbntdtui.html

Ruby: class Admin < User; end
来源：http://dali.havefunace.top/Article/details/gtbzzotggo.html

C#:   class Admin : User {}
来源：http://dali.jlsjyb.cn/Article/details/gtrivqevoo.html

[G06] 重写方法
来源：http://dali.c1oappe.top/Article/details/gtzluxayyn.html

Py:   def greet(self): return "admin"
来源：http://dali.xziqi.cn/Article/details/gtpoxouvtf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtquaogdxi.html

JS:   greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gthbabqhth.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwuufaefw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtdsmwxxes.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tanke756.top/Article/details/gtaifywddd.html

Ruby: def greet; "admin"; end
来源：http://dali.havefunace.top/Article/details/gtzogntooy.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqwmmqfoq.html

[G07] 调用父类方法
来源：http://dali.jinqigfzy.top/Article/details/gtkebsrtzb.html

Py:   super().greet()
来源：http://dali.shzxlz.cn/Article/details/gtimcwdmnh.html

PHP:  parent::greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwexqnrbz.html

JS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gtswxfzzgj.html

TS:   super.greet();
来源：http://dali.yj20258.top/Article/details/gtdwdcehxz.html

Java: super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtuwndqtfh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hongshengwenyu.top/Article/details/gtikitovel.html

Ruby: super
来源：http://dali.cashguo.top/Article/details/gtasnvgzbf.html

C#:   base.Greet();
来源：http://dali.yuxming.cn/Article/details/gtyzbuhoiz.html

[G08] 静态方法与属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtifdjvwgl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzjcermd.html

PHP:  public static function f() {}
来源：http://dali.c1oappe.top/Article/details/gtrsspknri.html

JS:   static f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtvmscvqme.html

TS:   static f(): void {}
来源：http://dali.sysykeji.top/Article/details/gttqmsovdd.html

Java: static void f() {}
来源：http://dali.nwbrower.top/Article/details/gtndsbmsmp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hammf.cn/Article/details/gtudjdrlzv.html

Ruby: def self.f; end
来源：http://dali.jlsjyb.cn/Article/details/gtupobmmeq.html

C#:   public static void F() {}
来源：http://dali.zhengqikj.top/Article/details/gtlvsodcpp.html

[G09] 接口 / 抽象类
来源：http://dali.nanxinkj.top/Article/details/gtitroxrfl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.fengsongda.top/Article/details/gtcrjyrruw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuanzx.com/Article/details/gteznoqgpf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ehwqpu.com/Article/details/gtjwoykxbw.html

TS:   interface Shape { area(): number; }
来源：http://dali.jiagoushi.top/Article/details/gtiqrjquxx.html

Java: interface Shape { double area(); }
来源：http://dali.yuanzhike.top/Article/details/gthvxkjesn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.quarkkingdee.top/Article/details/gthvwsdktl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cheryme.top/Article/details/gtvisvukio.html

C#:   interface IShape { double Area(); }
来源：http://dali.daria6918.cn/Article/details/gtmymkdcmh.html

[G10] 访问控制
来源：http://dali.guannengcc.top/Article/details/gtoapifgfq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sxryk.cn/Article/details/gtixuenprh.html

PHP:  public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gtldkywqmy.html

JS:   #private 字段；其余公开
来源：http://dali.hfpthk.cn/Article/details/gtfjtgpjhf.html

TS:   public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtixbjieoy.html

Java: public / protected / private / 默认包级
来源：http://dali.tian-w.cn/Article/details/gtzcksktpi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jiagoushi.top/Article/details/gttrnozsif.html

Ruby: public / protected / private
来源：http://dali.wangdashe.top/Article/details/gtydmkgwxy.html

C#:   public / protected / private / internal
来源：http://dali.yueranfly.top/Article/details/gtosngjcwg.html

[G11] getter / setter
来源：http://dali.havefunace.top/Article/details/gtknbjvaow.html

Py:   @property 与 @x.setter
来源：http://dali.hnqzz.top/Article/details/gtqsiazbmu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtnzawuudm.html

JS:   get name() { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gteprkfrxm.html

TS:   get name(): string { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gtffmworej.html

Java: public String getName() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtrdhyirqq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gtuxhovrar.html

Ruby: attr_accessor :name
来源：http://dali.hnqzz.top/Article/details/gtyylucpii.html

C#:   public string Name { get; set; }
来源：http://dali.ivvv.top/Article/details/gtdeuvxabi.html

[G12] 对象转字符串
来源：http://dali.shzxlz.cn/Article/details/gtzersndmx.html

Py:   def __str__(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gtnoiofbxx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gteymrfmex.html

JS:   toString() { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gtgzjvrmij.html

TS:   toString(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtdepbvnfc.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtsntrfjia.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtppkshsmn.html

Ruby: def to_s; @name; end
来源：http://dali.fengsongda.top/Article/details/gtbbrhdogp.html

C#:   public override string ToString() => Name;
来源：http://dali.fengsongda.top/Article/details/gtbaprdfpa.html

[G13] 判断对象类型
来源：http://dali.dianchejie.cn/Article/details/gtofnrwhva.html

Py:   isinstance(u, User)
来源：http://dali.yonumen.top/Article/details/gtpymgjrkx.html

PHP:  $u instanceof User
来源：http://dali.316326.xyz/Article/details/gtwfakmshw.html

JS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gtnchzvkwp.html

TS:   u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtthabbbxu.html

Java: u instanceof User
来源：http://dali.yj202588.top/Article/details/gtcztodlne.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gaohongyu789.top/Article/details/gtfuhqhffh.html

Ruby: u.is_a?(User)
来源：http://dali.xylfe.cn/Article/details/gtwonoezms.html

C#:   u is User
来源：http://dali.bjfxy.top/Article/details/gtezqwjxyx.html

[G14] 数据类 / record
来源：http://dali.wangshuangyany.cn/Article/details/gteuwynoao.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hfpthk.cn/Article/details/gtzfizqjxt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhiwuduotai.top/Article/details/gtkikexpjc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gotoacloud.top/Article/details/gtfxwxfzxn.html

TS:   type User = { name: string; age: number };
来源：http://dali.ppjwa.cn/Article/details/gtteqdazwz.html

Java: record User(String name, int age) {}
来源：http://dali.pycfn.com/Article/details/gtqanrasac.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlodabzrz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gtmosgansj.html

C#:   record User(string Name, int Age);
来源：http://dali.smart0.xyz/Article/details/gtempkzfjh.html

[G15] 枚举
来源：http://dali.mhx1999.top/Article/details/gtxaqgibpg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gotoacloud.top/Article/details/gtzzpmxhqy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.iojbl.cn/Article/details/gtwmimkley.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hnxiangtu.top/Article/details/gtmoolzfrh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gtxmxjlgsp.html

Java: enum Color { RED, GREEN }
来源：http://dali.cheryme.top/Article/details/gtckjyaliq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dianchejie.cn/Article/details/gtypdwfyzb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenzaomai.com/Article/details/gtytkgnscu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fzhhl.top/Article/details/gtiwocrifb.html

[G16] 对象转数组 / 字典
来源：http://dali.xinyue.icu/Article/details/gtflohqvzj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jianghu66.top/Article/details/gtjoxkeaac.html

PHP:  get_object_vars($obj);
来源：http://dali.hysaishi.cn/Article/details/gtwuyzmbcm.html

JS:   Object.entries(obj)
来源：http://dali.ydzc1.top/Article/details/gtrdslmkqd.html

TS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gtzbjgrzdb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jyoumei.cn/Article/details/gtkpvbyqms.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgufenzy.top/Article/details/gtijpctesc.html

Ruby: obj.instance_variables
来源：http://dali.cashguo.top/Article/details/gtsjsaxdqs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigfzy.top/Article/details/gtiaxajnyf.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtectiogyb.html

H. 异常与错误处理
来源：http://dali.wangdashe.top/Article/details/gttoiuvmwz.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtvvptpzqy.html

[H01] try / catch 基础
来源：http://dali.yonumen.top/Article/details/gtfehmtyut.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.meibo888.top/Article/details/gtljopgpug.html


<!-- 参考信息 -->