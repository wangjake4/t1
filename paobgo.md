代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dianchejie.cn/Article/details/gtxjubffwz.html

[E19] 多行文本按行拆分
来源：http://dali.zhengqikj.top/Article/details/gtzwtjikpr.html

Py:   s.splitlines()
来源：http://dali.shangyingyoupin.top/Article/details/gtqbwaswva.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtiswamxlc.html

JS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyuqxqaia.html

TS:   s.split(/\r?\n/)
来源：http://dali.svipenyu.cn/Article/details/gtjjwrcdwh.html

Java: s.lines().toList()
来源：http://dali.gotoacloud.top/Article/details/gtwpvokfem.html

Go:   strings.Split(s, "\n")
来源：http://dali.smart0.xyz/Article/details/gtxfpgulec.html

Ruby: s.lines
来源：http://dali.tanke756.top/Article/details/gtynfcmkam.html

C#:   s.Split('\n')
来源：http://dali.hysaishi.cn/Article/details/gthkimgtap.html

[E20] 判断字符串是否为空
来源：http://dali.0kj1m.cn/Article/details/gtabzepich.html

Py:   if not s:
来源：http://dali.c1oappe.top/Article/details/gtcgkctvxo.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hongshengwenyu.top/Article/details/gtibidpgxd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.iojbl.cn/Article/details/gtxehhnqky.html

TS:   if (s === "") {}
来源：http://dali.guannengcc.top/Article/details/gtfdqkshze.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gteykkwbaf.html

Go:   if s == "" {}
来源：http://dali.xuetiantiany.cn/Article/details/gtnuxkbsiw.html

Ruby: if s.empty?
来源：http://dali.jinqigufen.top/Article/details/gtdhgguttr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.316326.xyz/Article/details/gtnsdswvsq.html

[E21] 超长截断加省略号
来源：http://dali.ywan-chungtsiang.top/Article/details/gtduifdkpv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnxiangtu.top/Article/details/gtsoqefhlr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtyjpzewcf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtnmkcxulc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gtctfojetr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtblyldcsr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.c1oappe.top/Article/details/gtqmywoqla.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtxyznnowu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtebevarul.html

[E22] 字节长度与字符长度
来源：http://dali.nanxuanxn.top/Article/details/gtxismfynj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.fzhhl.top/Article/details/gtnilniwrq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtgqlwglsb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cashguo.top/Article/details/gtwdcgyblm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.bjfxy.top/Article/details/gtqytbmoba.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.smart0.xyz/Article/details/gtvepwzkob.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.svipenyu.cn/Article/details/gtygqeqxrs.html

Ruby: s.bytesize;  s.length
来源：http://dali.hfpthk.cn/Article/details/gtukesopur.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cqqwz.cn/Article/details/gteaaeyaji.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtffbnclec.html

F. 文件与目录
来源：http://dali.tanke756.top/Article/details/gtpikowlwt.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtawqrkxti.html

[F01] 读取整个文件
来源：http://dali.jyoumei.cn/Article/details/gtrpzxetvo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigfzy.top/Article/details/gtcegwutxz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtwliftdcl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ppjwa.cn/Article/details/gttzrlwhen.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gtgjkgzbvx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtrsbdgayy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yueranfly.top/Article/details/gteplwwnko.html

Ruby: File.read("a.txt")
来源：http://dali.sweek.top/Article/details/gtgbjfninb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtpxjeydhv.html

[F02] 逐行读取文件
来源：http://dali.yanxiufei.cn/Article/details/gtizvfavjo.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.iojbl.cn/Article/details/gtgaisgctj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yanxiufei.cn/Article/details/gtqkoagtac.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gtvvwuxjii.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sxryk.cn/Article/details/gtreusrjrz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zycfv.cn/Article/details/gtpdehyalc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zycfv.cn/Article/details/gtvigmeedx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.guannengcc.top/Article/details/gtidzmtzdd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylfoiibv.html

[F03] 写入文件（覆盖）
来源：http://dali.mhx1999.top/Article/details/gtpgapankj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.quarkkingdee.top/Article/details/gtyjaehecm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gtqrxmwemm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtvfezknnn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aizwys.cn/Article/details/gtdvwvtohb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhoulong.xyz/Article/details/gtlmizigth.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tanke756.top/Article/details/gtrlbgeugn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuanzhike.top/Article/details/gtcbkvikhg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gtxbdtoetb.html

[F04] 追加写入文件
来源：http://dali.fengsongda.top/Article/details/gtifneoaub.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jianghu66.top/Article/details/gtvdrztldx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yuanzhike.top/Article/details/gthieivqbh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jyoumei.cn/Article/details/gtclqmofbt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jyoumei.cn/Article/details/gtjypgkkxv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.smart0.xyz/Article/details/gtgyhguias.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xylfe.cn/Article/details/gteosyzdqq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzpbcaxiw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.iojbl.cn/Article/details/gtxywkccph.html

[F05] 判断文件或目录是否存在
来源：http://dali.sweek.top/Article/details/gtnfnfntrk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxinkj.top/Article/details/gtzhymzfyu.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtefesxgfe.html

JS:   fs.existsSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtidkvjyoo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtihmvjqoq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtpdjwzocz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.smart0.xyz/Article/details/gtxnhsynla.html

Ruby: File.exist?("a.txt")
来源：http://dali.316326.xyz/Article/details/gtdzcoouhf.html

C#:   File.Exists("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtubqupqmo.html

[F06] 删除文件
来源：http://dali.gaohongyu789.top/Article/details/gtwwrzfnoz.html

Py:   os.remove("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtatmsijfn.html

PHP:  unlink("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtsmzgsfhi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtlxjvneej.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtaxogxokb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtenvpbbky.html

Go:   os.Remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtspbdurbq.html

Ruby: File.delete("a.txt")
来源：http://dali.yongpay.top/Article/details/gtxnckfgfn.html

C#:   File.Delete("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtcobflckg.html

[F07] 创建目录（含多级）
来源：http://dali.ydzc1.top/Article/details/gtpfuazrdd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gaohongyu789.top/Article/details/gtyqnwkfcc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cucudq.cn/Article/details/gtrfwwxfpo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gtuknwoovt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gtamyrhekw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxuanxn.top/Article/details/gthcyaxvwa.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xziqi.cn/Article/details/gtafnkeemp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtupjeeozf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hongshengwenyu.top/Article/details/gtfwlwhxrv.html

[F08] 遍历目录
来源：http://dali.cucudq.cn/Article/details/gtovjebnqf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.aizwys.cn/Article/details/gtmblegfwm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yongpay.top/Article/details/gtnfoaaplw.html

JS:   fs.readdirSync("dir")
来源：http://dali.zdqjudy.top/Article/details/gtktozzkfu.html

TS:   fs.readdirSync("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvpdasiaq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ydzc1.top/Article/details/gtobirzfqn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.birdmap.top/Article/details/gttjvzftjt.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigufen.top/Article/details/gtpypzpbos.html

C#:   Directory.GetFiles("dir")
来源：http://dali.dianchejie.cn/Article/details/gtmdypfpfa.html

[F09] 获取文件大小
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqmznrve.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtlpycwfhu.html

PHP:  filesize("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsabzlzph.html

JS:   fs.statSync("a.txt").size
来源：http://dali.dashuyun.cn/Article/details/gtzldiurfk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.316326.xyz/Article/details/gtbnzgizkf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtompdwjfy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangshuangyany.cn/Article/details/gtpgwkvhrk.html

Ruby: File.size("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtkmqkqbvb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shzxlz.cn/Article/details/gturgobnmn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhoulong.xyz/Article/details/gtimfyswjk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtlkunfogz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtneutmsss.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtnselprpg.html

TS:   path.extname("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtxsoachsx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jqgufenzy.top/Article/details/gtacqsoxcl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtrkmovdbj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtctscylck.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtyxcnaves.html

[F11] 复制与移动文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtjcsrjjmj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtdptwzhot.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daxiang520.top/Article/details/gtbqubzudc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtqcdygfuf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtsascgdvr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nwbrower.top/Article/details/gtlheybquc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ppjwa.cn/Article/details/gtgtsgjiyf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtngpncgdq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cucudq.cn/Article/details/gtzawtgsyf.html

[F12] CSV 读写
来源：http://dali.ehwqpu.com/Article/details/gtccoholoy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dianchejie.cn/Article/details/gtzcfqqntu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tian-w.cn/Article/details/gtxuqwtawp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hnxiangtu.top/Article/details/gtnbnfxfzp.html

TS:   // 同上
来源：http://dali.chenjidiqi.icu/Article/details/gtnbfqbcok.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.quarkkingdee.top/Article/details/gtytuwstgg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ivvv.top/Article/details/gtkxzewxcj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yuanzhike.top/Article/details/gtlxblgixe.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jyoumei.cn/Article/details/gttcitzmys.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtckayjpoh.html

G. 面向对象
来源：http://dali.hammf.cn/Article/details/gtcrgtcdde.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtanzqhffd.html

[G01] 定义类
来源：http://dali.daria6918.cn/Article/details/gtjchxyvgp.html

Py:   class User: pass
来源：http://dali.gzhubu.top/Article/details/gtaggjehnd.html

PHP:  class User {}
来源：http://dali.316326.xyz/Article/details/gtbzwzxqpb.html

JS:   class User {}
来源：http://dali.havefunace.top/Article/details/gtjvgxnwfc.html

TS:   class User { name: string = ""; }
来源：http://dali.meibo888.top/Article/details/gtqkulttaq.html

Java: class User {}
来源：http://dali.andypj.xyz/Article/details/gtddprbvhl.html

Go:   type User struct { Name string }
来源：http://dali.nanxinkj.top/Article/details/gthvatgsfh.html

Ruby: class User; end
来源：http://dali.hongshengwenyu.top/Article/details/gtxieuoagq.html

C#:   class User {}
来源：http://dali.sxryk.cn/Article/details/gtqifxhylf.html

[G02] 构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtumixzsbn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yuxming.cn/Article/details/gtizvjhnzz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jyoumei.cn/Article/details/gtppexbhlx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcbmalkhv.html

TS:   constructor(public name: string) {}
来源：http://dali.vqdsnc.cn/Article/details/gtfcmysrtn.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhixingplan.top/Article/details/gtgzntvbso.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jiagoushi.top/Article/details/gtfytkyqag.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guannengcc.top/Article/details/gtwacbccsl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gzhubu.top/Article/details/gtqhwpdwmg.html

[G03] 实例属性
来源：http://dali.chenjidiqi.icu/Article/details/gtpptqovgs.html

Py:   self.name = "x"
来源：http://dali.wangdashe.top/Article/details/gtdtonwixj.html

PHP:  public string $name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtyadfuslw.html

JS:   this.name = "x";
来源：http://dali.yangfankeji.com/Article/details/gtjklrzrys.html

TS:   name: string = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtwbsqtzhj.html

Java: private String name;
来源：http://dali.jinqigfzy.top/Article/details/gtomyoijrr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cashguo.top/Article/details/gtvaewgayo.html

Ruby: @name = "x"
来源：http://dali.pycfn.com/Article/details/gtkbbysilz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.fzhhl.top/Article/details/gtofgjerwo.html

[G04] 定义方法
来源：http://dali.hfpthk.cn/Article/details/gtnaztaunf.html

Py:   def greet(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gtgzfastuj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gtpojrrfuu.html

JS:   greet() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtlyndvyqg.html

TS:   greet(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtyqssqyim.html

Java: String greet() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtinpjcawq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gthgsinvhn.html

Ruby: def greet; @name; end
来源：http://dali.shzxlz.cn/Article/details/gtxpijhdsm.html

C#:   public string Greet() => Name;
来源：http://dali.xziqi.cn/Article/details/gtfcuzssjk.html

[G05] 继承
来源：http://dali.hysaishi.cn/Article/details/gtekdltjdk.html

Py:   class Admin(User): pass
来源：http://dali.andypj.xyz/Article/details/gtfyzlzkbc.html

PHP:  class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtgxitsarg.html

JS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtibwezaii.html

TS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtvwmywyzw.html

Java: class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpyzclpna.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ybcxt.top/Article/details/gtqtpknltn.html

Ruby: class Admin < User; end
来源：http://dali.chenjidiqi.icu/Article/details/gtnbueifmu.html

C#:   class Admin : User {}
来源：http://dali.dianchejie.cn/Article/details/gtqowgapur.html

[G06] 重写方法
来源：http://dali.hnqzz.top/Article/details/gtuyowokux.html

Py:   def greet(self): return "admin"
来源：http://dali.haohaochexian.top/Article/details/gtnkuvqldc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gthzqgdhkl.html

JS:   greet() { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtyocdysdu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtkkiwcnvs.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gthszsuady.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hongshengwenyu.top/Article/details/gteyfvthdh.html

Ruby: def greet; "admin"; end
来源：http://dali.sufxvd.cn/Article/details/gtikwbdeub.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtprmilaug.html

[G07] 调用父类方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcavxxkxp.html

Py:   super().greet()
来源：http://dali.cashguo.top/Article/details/gtekzepnrn.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gtjwsxxdvk.html

JS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtnwooxqhu.html

TS:   super.greet();
来源：http://dali.smart0.xyz/Article/details/gtaqilduut.html

Java: super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtxfrrmdqc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dashuyun.cn/Article/details/gtgjufncvl.html

Ruby: super
来源：http://dali.tianlin.xyz/Article/details/gtgbjbwgtz.html

C#:   base.Greet();
来源：http://dali.sxryk.cn/Article/details/gteqnbnxoa.html

[G08] 静态方法与属性
来源：http://dali.ppjwa.cn/Article/details/gtuqvgbvyq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuetiantiany.cn/Article/details/gtvhxxuulp.html

PHP:  public static function f() {}
来源：http://dali.wangdashe.top/Article/details/gtuzovkefa.html

JS:   static f() {}
来源：http://dali.bjfxy.top/Article/details/gtflmoskvy.html

TS:   static f(): void {}
来源：http://dali.cheryme.top/Article/details/gtfgkhpyxv.html

Java: static void f() {}
来源：http://dali.sxryk.cn/Article/details/gtkrzocexa.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.svipenyu.cn/Article/details/gtqhvdqgkl.html

Ruby: def self.f; end
来源：http://dali.wangshuangyany.cn/Article/details/gthyofpelt.html

C#:   public static void F() {}
来源：http://dali.bjfxy.top/Article/details/gtwwicxtlw.html

[G09] 接口 / 抽象类
来源：http://dali.yongpay.top/Article/details/gtstxdsafr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shuidangran.top/Article/details/gttgrawtte.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangshuangyany.cn/Article/details/gtxbhgoqiu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gogol.net.cn/Article/details/gtbpvjeigb.html

TS:   interface Shape { area(): number; }
来源：http://dali.iojbl.cn/Article/details/gtpxmlgsno.html

Java: interface Shape { double area(); }
来源：http://dali.gotoacloud.top/Article/details/gtungcunaq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhoulong.xyz/Article/details/gtaszzjubk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hfpthk.cn/Article/details/gtmgaqbvys.html

C#:   interface IShape { double Area(); }
来源：http://dali.cheryme.top/Article/details/gtygdshain.html

[G10] 访问控制
来源：http://dali.vqdsnc.cn/Article/details/gtydjibftx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmebziywg.html

PHP:  public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtodufcgnk.html

JS:   #private 字段；其余公开
来源：http://dali.ehwqpu.com/Article/details/gtiswkwyax.html

TS:   public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gtryitfneq.html

Java: public / protected / private / 默认包级
来源：http://dali.zhoulong.xyz/Article/details/gtxqagbbds.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.havefunace.top/Article/details/gttecjjrnt.html

Ruby: public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtsexjzgxn.html

C#:   public / protected / private / internal
来源：http://dali.aizwys.cn/Article/details/gttdganerk.html

[G11] getter / setter
来源：http://dali.mhx1999.top/Article/details/gtkxukajoj.html

Py:   @property 与 @x.setter
来源：http://dali.yangfankeji.com/Article/details/gtdzepfksv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtprvcuexj.html

JS:   get name() { return this._name; }
来源：http://dali.316326.xyz/Article/details/gtfidanamz.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gtpgojhoqq.html

Java: public String getName() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvveuldnr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gtcyrrctzt.html

Ruby: attr_accessor :name
来源：http://dali.mhx1999.top/Article/details/gtyzcisbix.html

C#:   public string Name { get; set; }
来源：http://dali.wangdashe.top/Article/details/gttirkdmul.html

[G12] 对象转字符串
来源：http://dali.svipenyu.cn/Article/details/gtqolsxuye.html

Py:   def __str__(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gtblviwqns.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gtynlqokes.html

JS:   toString() { return this.name; }
来源：http://dali.316326.xyz/Article/details/gtuasreotn.html

TS:   toString(): string { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtmsboirjw.html

Java: @Override public String toString() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtadjkzmtd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gtdtuvhglh.html

Ruby: def to_s; @name; end
来源：http://dali.chenzaomai.com/Article/details/gtmnytdlbk.html

C#:   public override string ToString() => Name;
来源：http://dali.fzhhl.top/Article/details/gttcowgsby.html

[G13] 判断对象类型
来源：http://dali.aibaodan.cn/Article/details/gtozwylnwj.html

Py:   isinstance(u, User)
来源：http://dali.yuanzhike.top/Article/details/gtdgljytwl.html

PHP:  $u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtkiljjekn.html

JS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtowlxpgnc.html

TS:   u instanceof User
来源：http://dali.andypj.xyz/Article/details/gthtakwswq.html

Java: u instanceof User
来源：http://dali.yj202588.top/Article/details/gtdmlqhdbe.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ydzc1.top/Article/details/gtijhgcjjf.html

Ruby: u.is_a?(User)
来源：http://dali.aizwys.cn/Article/details/gtsaeoilow.html

C#:   u is User
来源：http://dali.chenlongwang.top/Article/details/gtiqfylrsx.html

[G14] 数据类 / record
来源：http://dali.hammf.cn/Article/details/gtwqnvdekg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zdqjudy.top/Article/details/gtkouefnke.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.haohaochexian.top/Article/details/gtuuzfzinf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgufenzy.top/Article/details/gtthhrdvnq.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigufen.top/Article/details/gtrzljaddw.html

Java: record User(String name, int age) {}
来源：http://dali.fzhhl.top/Article/details/gtimkfgcqt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guannengcc.top/Article/details/gttfqycide.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shuidangran.top/Article/details/gtxjddqgry.html

C#:   record User(string Name, int Age);
来源：http://dali.sxryk.cn/Article/details/gtrwglnwid.html

[G15] 枚举
来源：http://dali.ppjwa.cn/Article/details/gttbtzdqix.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.316326.xyz/Article/details/gtzplehnvy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxdvuino.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pengpengdd.cyou/Article/details/gtoxsdzlmn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuanzhike.top/Article/details/gtzabicjhi.html

Java: enum Color { RED, GREEN }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpbcfshq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenlongwang.top/Article/details/gtcarahhfj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zycfv.cn/Article/details/gthwpuixyl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gtuqwswqzi.html

[G16] 对象转数组 / 字典
来源：http://dali.shzxlz.cn/Article/details/gtfaamtray.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yanxiufei.cn/Article/details/gtfeycwpub.html

PHP:  get_object_vars($obj);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtldocztmq.html

JS:   Object.entries(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtpznzajex.html

TS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gtiilfibxa.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nwbrower.top/Article/details/gtgvfmeezs.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinghuilouyu.cn/Article/details/gtptpouehj.html

Ruby: obj.instance_variables
来源：http://dali.kuanghao11.cn/Article/details/gtmmxplyih.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gtpooprnec.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtguuyxtbw.html

H. 异常与错误处理
来源：http://dali.yuanzhike.top/Article/details/gtipycyumy.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtqnqzndqo.html

[H01] try / catch 基础
来源：http://dali.yangfankeji.com/Article/details/gtnusnuwns.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tanke756.top/Article/details/gtqhuwaszu.html


<!-- 参考信息 -->