代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.gaohongyu789.top/Article/details/gtvafblyuj.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj202588.top/Article/details/gtwekqtzsb.html

Java: s.lines().toList()
来源：http://dali.0kj1m.cn/Article/details/gtbktwdcag.html

Go:   strings.Split(s, "\n")
来源：http://dali.sysykeji.top/Article/details/gtcocvgbzh.html

Ruby: s.lines
来源：http://dali.sweek.top/Article/details/gtwayzcuuu.html

C#:   s.Split('\n')
来源：http://dali.ehwqpu.com/Article/details/gtsovtmmyi.html

[E20] 判断字符串是否为空
来源：http://dali.hnqzz.top/Article/details/gtnpnfcokv.html

Py:   if not s:
来源：http://dali.xuanzx.com/Article/details/gtecxlhjhe.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenjidiqi.icu/Article/details/gtffjdxrsf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gogol.net.cn/Article/details/gtrassbwhz.html

TS:   if (s === "") {}
来源：http://dali.sxryk.cn/Article/details/gtzdlsdwco.html

Java: if (s.isEmpty()) {}
来源：http://dali.yanxiufei.cn/Article/details/gtcplensqv.html

Go:   if s == "" {}
来源：http://dali.ehwqpu.com/Article/details/gtbjcdnkph.html

Ruby: if s.empty?
来源：http://dali.yonumen.top/Article/details/gtzknpwvbl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tian-w.cn/Article/details/gtumcfqzet.html

[E21] 超长截断加省略号
来源：http://dali.zhixingplan.top/Article/details/gtdfmdhpnb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ydzc1.top/Article/details/gtbiuogskf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtjkqdaptk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtqrqkbjjd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtlvyvybkp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxydlpgod.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ehwqpu.com/Article/details/gttzerwnar.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yongpay.top/Article/details/gtihbwwfdx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtmwteejok.html

[E22] 字节长度与字符长度
来源：http://dali.cdnleiting.top/Article/details/gtqsmezhjs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sysykeji.top/Article/details/gtmksottyg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gtywmsyfoz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gtdxlbhftk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gtigtnbkqx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gotoacloud.top/Article/details/gttobpezaj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.iojbl.cn/Article/details/gtevswywjz.html

Ruby: s.bytesize;  s.length
来源：http://dali.daria6918.cn/Article/details/gtnktbbnqe.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ppjwa.cn/Article/details/gtcbinhysz.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtqjtihlvb.html

F. 文件与目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfdxnbbg.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtissbhgnk.html

[F01] 读取整个文件
来源：http://dali.aizwys.cn/Article/details/gtmauhdszr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jlsjyb.cn/Article/details/gtsivondcq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtcpqbamli.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.guannengcc.top/Article/details/gtdesgwrme.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hnqzz.top/Article/details/gtyduoflkn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtbdjtkfrn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.pycfn.com/Article/details/gtisdqntop.html

Ruby: File.read("a.txt")
来源：http://dali.hammf.cn/Article/details/gtmchonckz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtikyufqoi.html

[F02] 逐行读取文件
来源：http://dali.hfpthk.cn/Article/details/gtkhpbwskt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jqgfzy.top/Article/details/gtxdhetofu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenlongwang.top/Article/details/gtgmjxqgvo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gtkhjxdjsy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrazvnlh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gtjomhoauq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gotoacloud.top/Article/details/gtfcebevni.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangtech.top/Article/details/gthgbhoccp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jiagoushi.top/Article/details/gtztdjfnbk.html

[F03] 写入文件（覆盖）
来源：http://dali.xinyue.icu/Article/details/gtwnmtrfwg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.guowangkeji.top/Article/details/gtxycxssho.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cashguo.top/Article/details/gtkykniozw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gtbtebjhrd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gtpdyhqdju.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.pycfn.com/Article/details/gtwwylwtis.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.daria6918.cn/Article/details/gtalbedsyr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigfzy.top/Article/details/gtxdrjvzep.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.9152youxi.cn/Article/details/gtuwhumgqp.html

[F04] 追加写入文件
来源：http://dali.hysaishi.cn/Article/details/gtdqsolmvc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.vqdsnc.cn/Article/details/gthibcxipb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hongshengwenyu.top/Article/details/gtjjgbbbva.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangdashe.top/Article/details/gtpuunfrzw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cqqwz.cn/Article/details/gtsmtmazrp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ybcxt.top/Article/details/gtdtcgwafb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.haohaochexian.top/Article/details/gtqfgxzlpm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jlsjyb.cn/Article/details/gtojzdeoyc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tanke756.top/Article/details/gtgzpfejky.html

[F05] 判断文件或目录是否存在
来源：http://dali.xuanzx.com/Article/details/gtvqxmtetd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xuanzx.com/Article/details/gtcbodxtzo.html

PHP:  file_exists("a.txt");
来源：http://dali.daxiang520.top/Article/details/gteaxnpxvq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtytbuboyx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtzumgmuht.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtdwjbqmum.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuanzhike.top/Article/details/gttlwuprih.html

Ruby: File.exist?("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtjilczpgy.html

C#:   File.Exists("a.txt")
来源：http://dali.316326.xyz/Article/details/gtqupwgfwv.html

[F06] 删除文件
来源：http://dali.xinyue.icu/Article/details/gtreplrghb.html

Py:   os.remove("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtxiqhabxu.html

PHP:  unlink("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtabczaeqr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtzzdmcjxh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtglebjisg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtwwpimtvt.html

Go:   os.Remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtuyunqewg.html

Ruby: File.delete("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtltqtgaef.html

C#:   File.Delete("a.txt");
来源：http://dali.aizwys.cn/Article/details/gttdehmdcj.html

[F07] 创建目录（含多级）
来源：http://dali.pycfn.com/Article/details/gtarjbozif.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.wangdashe.top/Article/details/gtehpsiwvw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jyoumei.cn/Article/details/gtjopkzpsp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pengpengdd.cyou/Article/details/gtxzaxmdnt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gtgxplhozy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yueranfly.top/Article/details/gtiiqpvgkh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.meibo888.top/Article/details/gtprhtlxth.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tian-w.cn/Article/details/gttbmfmvbo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.iojbl.cn/Article/details/gtzuzmmqbn.html

[F08] 遍历目录
来源：http://dali.daxiang520.top/Article/details/gtumcbpcrw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.redwolf501.top/Article/details/gtncakmxnn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.9152youxi.cn/Article/details/gtfjmrtvde.html

JS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gthcbusjur.html

TS:   fs.readdirSync("dir")
来源：http://dali.ehwqpu.com/Article/details/gteqvxvejq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhixingplan.top/Article/details/gtewpvbmvs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtuauhijfk.html

Ruby: Dir.children("dir")
来源：http://dali.cdnleiting.top/Article/details/gtigrhpybd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhixingplan.top/Article/details/gtfygocmdd.html

[F09] 获取文件大小
来源：http://dali.yangfankeji.com/Article/details/gthtmzypxy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gthtdekgte.html

PHP:  filesize("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtogfhswag.html

JS:   fs.statSync("a.txt").size
来源：http://dali.fzhhl.top/Article/details/gtdcbeqvso.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hywenlv.cn/Article/details/gtjdsmwlfp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtrhontqqj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gotoacloud.top/Article/details/gtzxillpoe.html

Ruby: File.size("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtlvkmhhxt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yueranfly.top/Article/details/gtslfcngyd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenlongwang.top/Article/details/gtvwrgbtzp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtbqaudowj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.wangdashe.top/Article/details/gtxdnnzzpu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtwrkbfclk.html

TS:   path.extname("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvlpzglxx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gotoacloud.top/Article/details/gtswqxsgvc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtcfelihuj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtlztlxdvs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrsuyzmw.html

[F11] 复制与移动文件
来源：http://dali.hnxiangtu.top/Article/details/gtzxrxjuhj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtowebjing.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuszpvlln.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtltjybmxc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gthnzdtgjb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zdqjudy.top/Article/details/gtafrnkbci.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yonumen.top/Article/details/gtkmxpprut.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtxthagqon.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipuwbgch.html

[F12] CSV 读写
来源：http://dali.9152youxi.cn/Article/details/gtliumxezs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jiagoushi.top/Article/details/gtkumkzsbd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzofwmoq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.fengsongda.top/Article/details/gtjrgtgoox.html

TS:   // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gtbweibmfl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.316326.xyz/Article/details/gtndhsatlt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yueranfly.top/Article/details/gtuxupuclo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gogol.net.cn/Article/details/gtqijeqqjz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hammf.cn/Article/details/gtejhsjvtz.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtlrniyjwu.html

G. 面向对象
来源：http://dali.kuanghao11.cn/Article/details/gtocgcjcju.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtvjqwlqiw.html

[G01] 定义类
来源：http://dali.hongshengwenyu.top/Article/details/gtfhcbcvtn.html

Py:   class User: pass
来源：http://dali.yj20258888.top/Article/details/gttxozmwly.html

PHP:  class User {}
来源：http://dali.aibaodan.cn/Article/details/gtydxecmbm.html

JS:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gtzxqenahz.html

TS:   class User { name: string = ""; }
来源：http://dali.yuanzhike.top/Article/details/gthflsuywe.html

Java: class User {}
来源：http://dali.bjfxy.top/Article/details/gtovzabvhn.html

Go:   type User struct { Name string }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtmzmpjg.html

Ruby: class User; end
来源：http://dali.jinqigufen.top/Article/details/gtcsokptoe.html

C#:   class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxrfyrtxj.html

[G02] 构造函数
来源：http://dali.sysykeji.top/Article/details/gtvprduqlj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.vqdsnc.cn/Article/details/gtffuemmyt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtngbnmifc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.bjfxy.top/Article/details/gtcgybujmf.html

TS:   constructor(public name: string) {}
来源：http://dali.c1oappe.top/Article/details/gtiilgciyl.html

Java: User(String name) { this.name = name; }
来源：http://dali.cqqwz.cn/Article/details/gtzzageevu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gtcvfzdshe.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjaznssy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sufxvd.cn/Article/details/gtmvtgcqxk.html

[G03] 实例属性
来源：http://dali.chenjidiqi.icu/Article/details/gteaylscib.html

Py:   self.name = "x"
来源：http://dali.wangdashe.top/Article/details/gtzpcakgie.html

PHP:  public string $name = "x";
来源：http://dali.snrcjt.cn/Article/details/gtgorhwmet.html

JS:   this.name = "x";
来源：http://dali.zhixingplan.top/Article/details/gtknxtivyq.html

TS:   name: string = "x";
来源：http://dali.dashuyun.cn/Article/details/gtqksvrdms.html

Java: private String name;
来源：http://dali.zhixingplan.top/Article/details/gtcznyetwa.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shuidangran.top/Article/details/gtcesvlyuw.html

Ruby: @name = "x"
来源：http://dali.gzhubu.top/Article/details/gtlcgixjoe.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtnvzjhspc.html

[G04] 定义方法
来源：http://dali.andypj.xyz/Article/details/gtkhtmybza.html

Py:   def greet(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gtekxihfer.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gthabkuxyn.html

JS:   greet() { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtdwgufqov.html

TS:   greet(): string { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtglaygfjt.html

Java: String greet() { return name; }
来源：http://dali.sxryk.cn/Article/details/gtksgmdrdg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gtjgenuitu.html

Ruby: def greet; @name; end
来源：http://dali.jianghu66.top/Article/details/gtctwxhyeo.html

C#:   public string Greet() => Name;
来源：http://dali.zhixingplan.top/Article/details/gtqrkekzre.html

[G05] 继承
来源：http://dali.pycfn.com/Article/details/gtezkgtwhu.html

Py:   class Admin(User): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtztwcpbsw.html

PHP:  class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtebdtgsje.html

JS:   class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtwldgtfpx.html

TS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtivwusklh.html

Java: class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtfevfntmg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zdqjudy.top/Article/details/gtodbgcbgo.html

Ruby: class Admin < User; end
来源：http://dali.tian-w.cn/Article/details/gtrzooabop.html

C#:   class Admin : User {}
来源：http://dali.sysykeji.top/Article/details/gtbxlyoltx.html

[G06] 重写方法
来源：http://dali.tanke756.top/Article/details/gtithrikwy.html

Py:   def greet(self): return "admin"
来源：http://dali.gogol.net.cn/Article/details/gtmzvfsuhi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtunbypire.html

JS:   greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtbkxgvwko.html

TS:   greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtahtsnzrw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtniufhwtm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ppjwa.cn/Article/details/gtalwrvjoe.html

Ruby: def greet; "admin"; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkyhqapkp.html

C#:   public override string Greet() => "admin";
来源：http://dali.ppjwa.cn/Article/details/gtkzngkkqh.html

[G07] 调用父类方法
来源：http://dali.jqgufenzy.top/Article/details/gtahdbmvub.html

Py:   super().greet()
来源：http://dali.guannengcc.top/Article/details/gtvuonpxnu.html

PHP:  parent::greet();
来源：http://dali.tanke756.top/Article/details/gtuhwhrcmj.html

JS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtbciminyf.html

TS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gtyejgnenx.html

Java: super.greet();
来源：http://dali.havefunace.top/Article/details/gttpavtlre.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gtrjtxyofv.html

Ruby: super
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwweqlcv.html

C#:   base.Greet();
来源：http://dali.gaohongyu789.top/Article/details/gtneuaodbk.html

[G08] 静态方法与属性
来源：http://dali.fengsongda.top/Article/details/gtyegbgalz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pengpengdd.cyou/Article/details/gtkcqgxgsl.html

PHP:  public static function f() {}
来源：http://dali.svipenyu.cn/Article/details/gtuimgkylx.html

JS:   static f() {}
来源：http://dali.yuanzhike.top/Article/details/gtfbfxyweo.html

TS:   static f(): void {}
来源：http://dali.dashuyun.cn/Article/details/gtxrgngkln.html

Java: static void f() {}
来源：http://dali.gogol.net.cn/Article/details/gtanofjijf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhiwuduotai.top/Article/details/gteoczxtbr.html

Ruby: def self.f; end
来源：http://dali.daxiang520.top/Article/details/gtolvqeqna.html

C#:   public static void F() {}
来源：http://dali.chenlongwang.top/Article/details/gtnsjpywmr.html

[G09] 接口 / 抽象类
来源：http://dali.xylfe.cn/Article/details/gtmirwvirm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pycfn.com/Article/details/gtnlkmexoe.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxuanxn.top/Article/details/gtmcwdsdnl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jlsjyb.cn/Article/details/gtbqgypxxr.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258.top/Article/details/gtgkqdukwy.html

Java: interface Shape { double area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtotnyrsbx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzstxoppp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cqqwz.cn/Article/details/gtqqwlwazf.html

C#:   interface IShape { double Area(); }
来源：http://dali.nwbrower.top/Article/details/gtwjklwouw.html

[G10] 访问控制
来源：http://dali.hysaishi.cn/Article/details/gtaiwvduye.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cdnleiting.top/Article/details/gtsecbojnj.html

PHP:  public / protected / private
来源：http://dali.316326.xyz/Article/details/gtyvcjysol.html

JS:   #private 字段；其余公开
来源：http://dali.hysaishi.cn/Article/details/gtzllfqbin.html

TS:   public / protected / private
来源：http://dali.cashguo.top/Article/details/gtwvyoodua.html

Java: public / protected / private / 默认包级
来源：http://dali.havefunace.top/Article/details/gtmvepgvfe.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.dashuyun.cn/Article/details/gtludbbpsx.html

Ruby: public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtcnzandnn.html

C#:   public / protected / private / internal
来源：http://dali.yj20258888.top/Article/details/gtelkllwsg.html

[G11] getter / setter
来源：http://dali.gzhubu.top/Article/details/gtniayrwdj.html

Py:   @property 与 @x.setter
来源：http://dali.xuetiantiany.cn/Article/details/gtalosjgqm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtoehzikif.html

JS:   get name() { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqstktqmf.html

TS:   get name(): string { return this._name; }
来源：http://dali.cheryme.top/Article/details/gtfszubpax.html

Java: public String getName() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtzppiyajy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtiqmtifeb.html

Ruby: attr_accessor :name
来源：http://dali.dashuyun.cn/Article/details/gtjcmidbbe.html

C#:   public string Name { get; set; }
来源：http://dali.wangdashe.top/Article/details/gteehylcft.html

[G12] 对象转字符串
来源：http://dali.sweek.top/Article/details/gtqhkdayww.html

Py:   def __str__(self): return self.name
来源：http://dali.ehwqpu.com/Article/details/gttsjxpwww.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gtoabgzhfo.html

JS:   toString() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtqhjsqhse.html

TS:   toString(): string { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtxbfcsphc.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangdashe.top/Article/details/gtkerhdjov.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gtcdesgnfs.html

Ruby: def to_s; @name; end
来源：http://dali.kuanghao11.cn/Article/details/gtaiwbdnfv.html

C#:   public override string ToString() => Name;
来源：http://dali.hfpthk.cn/Article/details/gtkyvjhhot.html

[G13] 判断对象类型
来源：http://dali.pengpengdd.cyou/Article/details/gttzaplhkt.html

Py:   isinstance(u, User)
来源：http://dali.haohaochexian.top/Article/details/gtwhxqjiuc.html

PHP:  $u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtbbyppaiz.html

JS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gttcdvlgff.html

TS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gtzpomkxke.html

Java: u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtbjjlxphn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ybcxt.top/Article/details/gtqmlsjqaq.html

Ruby: u.is_a?(User)
来源：http://dali.gaohongyu789.top/Article/details/gtomgwoelv.html

C#:   u is User
来源：http://dali.jinghuilouyu.cn/Article/details/gtdtoarrbt.html

[G14] 数据类 / record
来源：http://dali.sweek.top/Article/details/gtptrbunam.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.meibo888.top/Article/details/gtddhmnvbu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.andypj.xyz/Article/details/gtkwfcypjq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.bjfxy.top/Article/details/gtpcmvnfmb.html

TS:   type User = { name: string; age: number };
来源：http://dali.hnxiangtu.top/Article/details/gttdfdkhqj.html

Java: record User(String name, int age) {}
来源：http://dali.redwolf501.top/Article/details/gtqcvyjnwm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jlsjyb.cn/Article/details/gtxtvrrllv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yongpay.top/Article/details/gtpdomtzpr.html

C#:   record User(string Name, int Age);
来源：http://dali.hnqzz.top/Article/details/gtpmbyznxa.html

[G15] 枚举
来源：http://dali.jqgufenzy.top/Article/details/gtcxrenlty.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgfzy.top/Article/details/gtlmsjcbfn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hnqzz.top/Article/details/gthxankrmb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxinkj.top/Article/details/gtvnqlfodz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yangfankeji.com/Article/details/gtiwqijied.html

Java: enum Color { RED, GREEN }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmuecruos.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gogol.net.cn/Article/details/gtwovnxxws.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yueranfly.top/Article/details/gtkgdgyovl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gtiddtcish.html

[G16] 对象转数组 / 字典
来源：http://dali.pycfn.com/Article/details/gtojsxdlll.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xylfe.cn/Article/details/gtmvxhyhxd.html

PHP:  get_object_vars($obj);
来源：http://dali.shuidangran.top/Article/details/gtucvdlvlz.html

JS:   Object.entries(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtzkoizypd.html

TS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gtwzrkjdsu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jiagoushi.top/Article/details/gtehgcdnnb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daria6918.cn/Article/details/gtslhpwrwr.html

Ruby: obj.instance_variables
来源：http://dali.jlsjyb.cn/Article/details/gthsjbjoik.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.birdmap.top/Article/details/gtxzworjph.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtdwjciyaq.html

H. 异常与错误处理
来源：http://dali.hammf.cn/Article/details/gtkpbismfv.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtgecycqic.html

[H01] try / catch 基础
来源：http://dali.birdmap.top/Article/details/gtuoyjwjsh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sufxvd.cn/Article/details/gtggnuvoar.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.andypj.xyz/Article/details/gtbzhnxpsv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gtnnmmljau.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gtghbdqybt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zdqjudy.top/Article/details/gtgwovrfff.html


<!-- 参考信息 -->