代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.hfpthk.cn/Article/details/gt2sdemqolo.html

TS:   s.split(/\r?\n/)
来源：http://dali.quarkkingdee.top/Article/details/gt2mqaewwdr.html

Java: s.lines().toList()
来源：http://dali.guannengcc.top/Article/details/gt2fkfktgfo.html

Go:   strings.Split(s, "\n")
来源：http://dali.tian-w.cn/Article/details/gt2xtlpypib.html

Ruby: s.lines
来源：http://dali.hnqzz.top/Article/details/gt2vadbojhi.html

C#:   s.Split('\n')
来源：http://dali.hnqzz.top/Article/details/gt2gsgayaok.html

[E20] 判断字符串是否为空
来源：http://dali.gaohongyu789.top/Article/details/gt2osxqajbo.html

Py:   if not s:
来源：http://dali.jlsjyb.cn/Article/details/gt2pcnrmyey.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2agfkmbnx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sweek.top/Article/details/gt2bwvdjkgi.html

TS:   if (s === "") {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qxhrmzxj.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinqigufen.top/Article/details/gt2wpnkfxqk.html

Go:   if s == "" {}
来源：http://dali.9152youxi.cn/Article/details/gt2gbmhvwqc.html

Ruby: if s.empty?
来源：http://dali.pycfn.com/Article/details/gt2nfygvzsi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gogol.net.cn/Article/details/gt2oqinlyuo.html

[E21] 超长截断加省略号
来源：http://dali.nanxinkj.top/Article/details/gt2jfdktxph.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.aibaodan.cn/Article/details/gt2bfwnhilk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gt2insgjbpf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gt2hxcxgyyk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gt2drvhyqga.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gt2wbuxcdyc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jyoumei.cn/Article/details/gt2ykuiyulo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gt2vcprfkqw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gt2ohueblqi.html

[E22] 字节长度与字符长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2btoddfsb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cashguo.top/Article/details/gt2qxoisdri.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gt2fpnvlwdo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2scvjkgne.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cashguo.top/Article/details/gt2kobqigvt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.redwolf501.top/Article/details/gt2gpzukbin.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.0kj1m.cn/Article/details/gt2yratgnxy.html

Ruby: s.bytesize;  s.length
来源：http://dali.chenlongwang.top/Article/details/gt2nreglqcf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jiagoushi.top/Article/details/gt2ywznpruk.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2bucbtnde.html

F. 文件与目录
来源：http://dali.fzhhl.top/Article/details/gt2xeaurvle.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2cabnmwbx.html

[F01] 读取整个文件
来源：http://dali.pycfn.com/Article/details/gt2njokfpzq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aizwys.cn/Article/details/gt2xffdyklj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2yswheilg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj202588.top/Article/details/gt2ubsjkrdd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ydzc1.top/Article/details/gt2rzyrwewz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gt2rdmszein.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.feifeiyinyue.top/Article/details/gt2tmqkiwpy.html

Ruby: File.read("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2szhoxiae.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2fjunxddy.html

[F02] 逐行读取文件
来源：http://dali.xuanzx.com/Article/details/gt2uyyrjlcu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zdqjudy.top/Article/details/gt2gefqgyhk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lrilokot.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shuidangran.top/Article/details/gt2qripgtjy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gt2ubsvsxko.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gt2lvjprcqq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.redwolf501.top/Article/details/gt2ijjxqykj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2pagpbsdt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj20258888.top/Article/details/gt2uyicylkw.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2auuavjri.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hnxiangtu.top/Article/details/gt2ryzbcsvs.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhengqikj.top/Article/details/gt2rbrzmdox.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gt2kxnwvahu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gt2prwtxhux.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jiagoushi.top/Article/details/gt2bjnxadhc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.316326.xyz/Article/details/gt2hkvhftdr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jqgfzy.top/Article/details/gt2ochxjbwc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.meibo888.top/Article/details/gt2pwmxhuoo.html

[F04] 追加写入文件
来源：http://dali.xuanzx.com/Article/details/gt2tuwobjev.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nwbrower.top/Article/details/gt2icdpwukl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hnqzz.top/Article/details/gt2otyflzuo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gt2qkosnnht.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cjtzglmh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.haohaochexian.top/Article/details/gt2rhkvhrgl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jyoumei.cn/Article/details/gt2thcjendh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gotoacloud.top/Article/details/gt2lakulyuu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jqgufenzy.top/Article/details/gt2rhmegrqg.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxinkj.top/Article/details/gt2zzrnzvwc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.mhx1999.top/Article/details/gt2cmonlwjc.html

PHP:  file_exists("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2jxsnlcuj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2ihriavpv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2rzfgskjx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gt2ehivzafp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2goygixoj.html

Ruby: File.exist?("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2dgutcefe.html

C#:   File.Exists("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2sqylalbu.html

[F06] 删除文件
来源：http://dali.guannengcc.top/Article/details/gt2cwczejot.html

Py:   os.remove("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2gbepltwe.html

PHP:  unlink("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2pnnzyjiz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2gvhmunxe.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vhqidcne.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gt2gdxmydta.html

Go:   os.Remove("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gzwetrvu.html

Ruby: File.delete("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2eycphhcl.html

C#:   File.Delete("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cluztlaz.html

[F07] 创建目录（含多级）
来源：http://dali.andypj.xyz/Article/details/gt2fdnazzbf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yuxming.cn/Article/details/gt2loogrjpe.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ehwqpu.com/Article/details/gt2jxbedwlz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgfzy.top/Article/details/gt2clawatwz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ybcxt.top/Article/details/gt2sjownuhk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenlongwang.top/Article/details/gt2ecjlohxm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.quarkkingdee.top/Article/details/gt2rrlfkjye.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhixingplan.top/Article/details/gt2evgdsdyu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgfzy.top/Article/details/gt2xabjfyvr.html

[F08] 遍历目录
来源：http://dali.guowangkeji.top/Article/details/gt2bejfspdg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj20258888.top/Article/details/gt2kdnpxkqz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xylfe.cn/Article/details/gt2teprpqcf.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gt2dnxqrmya.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zzfxliri.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jlsjyb.cn/Article/details/gt2cinuacxn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gt2tskyybpt.html

Ruby: Dir.children("dir")
来源：http://dali.hywenlv.cn/Article/details/gt2zrcczzmk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.bjfxy.top/Article/details/gt2khoxnozl.html

[F09] 获取文件大小
来源：http://dali.gaohongyu789.top/Article/details/gt2ynvdnmvh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2belhbbcg.html

PHP:  filesize("a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2ydypmhwz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gt2keliptyk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gt2blsdzwsx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gt2hytoogwb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hywenlv.cn/Article/details/gt2dnadejah.html

Ruby: File.size("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2alozphuu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuanzx.com/Article/details/gt2pkbwxmde.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ehwqpu.com/Article/details/gt2pguvsfwr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2lbqzaevi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2vuitvyzl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2ndbmlcld.html

TS:   path.extname("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2vcqpjzvg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.0kj1m.cn/Article/details/gt2xnkodijj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2azdphibv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2vxosvnli.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tndppbpz.html

[F11] 复制与移动文件
来源：http://dali.svipenyu.cn/Article/details/gt2ymaomoao.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gt2ausqzkmg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2udxwgbnq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gt2qnpwnwal.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2wwevmkfa.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mnlagicr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zdqjudy.top/Article/details/gt2razxgnfv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2pvliegbo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xylfe.cn/Article/details/gt2jysscktz.html

[F12] CSV 读写
来源：http://dali.xylfe.cn/Article/details/gt2wlpwevlb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinqigfzy.top/Article/details/gt2ejxfenoy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.pengpengdd.cyou/Article/details/gt2yatylhgj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pycfn.com/Article/details/gt2uvqvsqct.html

TS:   // 同上
来源：http://dali.yj20258.top/Article/details/gt2etnzhkwm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hongshengwenyu.top/Article/details/gt2fncetudo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.0kj1m.cn/Article/details/gt2nitefsuc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ivvv.top/Article/details/gt2yjieazuv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenlongwang.top/Article/details/gt2hypyoreq.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2qkhwsiyt.html

G. 面向对象
来源：http://dali.yj20258.top/Article/details/gt2ibnegjlv.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2lackjajx.html

[G01] 定义类
来源：http://dali.guannengcc.top/Article/details/gt2nvdcutrg.html

Py:   class User: pass
来源：http://dali.aizwys.cn/Article/details/gt2uummjkid.html

PHP:  class User {}
来源：http://dali.yuanzhike.top/Article/details/gt2dqmigzcg.html

JS:   class User {}
来源：http://dali.cheryme.top/Article/details/gt2emvtlhxd.html

TS:   class User { name: string = ""; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2sqfmrnfx.html

Java: class User {}
来源：http://dali.jinqigufen.top/Article/details/gt2jscmvlgf.html

Go:   type User struct { Name string }
来源：http://dali.iojbl.cn/Article/details/gt2uflsbgav.html

Ruby: class User; end
来源：http://dali.hammf.cn/Article/details/gt2zuiuveyu.html

C#:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gt2lmogivwn.html

[G02] 构造函数
来源：http://dali.hnxiangtu.top/Article/details/gt2jcxbdslr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.snrcjt.cn/Article/details/gt2mxnemiyp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2uhiorkqo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2abasqpjj.html

TS:   constructor(public name: string) {}
来源：http://dali.yvedp.cn/Article/details/gt2mgnwlmwm.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2cumgkvqm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnxiangtu.top/Article/details/gt2eppkvewb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qtdrpvsz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2tvcmvtia.html

[G03] 实例属性
来源：http://dali.jqgufenzy.top/Article/details/gt2jyzvychk.html

Py:   self.name = "x"
来源：http://dali.hnqzz.top/Article/details/gt2fyzxbvkb.html

PHP:  public string $name = "x";
来源：http://dali.xinyue.icu/Article/details/gt2jrglejxd.html

JS:   this.name = "x";
来源：http://dali.sxryk.cn/Article/details/gt2iwpuywju.html

TS:   name: string = "x";
来源：http://dali.bjfxy.top/Article/details/gt2quusddrj.html

Java: private String name;
来源：http://dali.chenzaomai.com/Article/details/gt2zwyezhuy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dihbqccl.html

Ruby: @name = "x"
来源：http://dali.yj20258888.top/Article/details/gt2jtflnjkx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sxryk.cn/Article/details/gt2mnqorzke.html

[G04] 定义方法
来源：http://dali.yvedp.cn/Article/details/gt2ykvbsagl.html

Py:   def greet(self): return self.name
来源：http://dali.xuetiantiany.cn/Article/details/gt2mjwqpjpp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gt2voabjusd.html

JS:   greet() { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gt2hvknoaui.html

TS:   greet(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gt2zrudgvoj.html

Java: String greet() { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2klszfyvf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gt2xrxvhrwd.html

Ruby: def greet; @name; end
来源：http://dali.haohaochexian.top/Article/details/gt2lvvknoin.html

C#:   public string Greet() => Name;
来源：http://dali.cdnleiting.top/Article/details/gt2lhvdxerh.html

[G05] 继承
来源：http://dali.birdmap.top/Article/details/gt2nmsrqack.html

Py:   class Admin(User): pass
来源：http://dali.dashuyun.cn/Article/details/gt2fhwkgpce.html

PHP:  class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gt2xdznowmy.html

JS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gt2wppbzvgd.html

TS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gt2uqjsfukx.html

Java: class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gt2vbkiddpk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.snrcjt.cn/Article/details/gt2tqyubgdh.html

Ruby: class Admin < User; end
来源：http://dali.nanxinkj.top/Article/details/gt2slxldffb.html

C#:   class Admin : User {}
来源：http://dali.hammf.cn/Article/details/gt2zazrebwb.html

[G06] 重写方法
来源：http://dali.xinyue.icu/Article/details/gt2wsnaaaej.html

Py:   def greet(self): return "admin"
来源：http://dali.yuanzhike.top/Article/details/gt2azimnvqk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gt2rbtlkcmq.html

JS:   greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gt2intxbhai.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gt2xutitlrh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ictcxsav.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nanxinkj.top/Article/details/gt2hsgaknva.html

Ruby: def greet; "admin"; end
来源：http://dali.hnqzz.top/Article/details/gt2kegshykv.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hoygemfz.html

[G07] 调用父类方法
来源：http://dali.nwbrower.top/Article/details/gt2mtotilzs.html

Py:   super().greet()
来源：http://dali.mhx1999.top/Article/details/gt2rxdevzmu.html

PHP:  parent::greet();
来源：http://dali.daxiang520.top/Article/details/gt2rhxrsvwk.html

JS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gt2zbnkpqks.html

TS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gt2swanbogu.html

Java: super.greet();
来源：http://dali.gzhubu.top/Article/details/gt2aasonvpn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.haohaochexian.top/Article/details/gt2sjvbaqyv.html

Ruby: super
来源：http://dali.tianlin.xyz/Article/details/gt2pwrqlpop.html

C#:   base.Greet();
来源：http://dali.cucudq.cn/Article/details/gt2ybqnrfbx.html

[G08] 静态方法与属性
来源：http://dali.gogol.net.cn/Article/details/gt2eiecioxg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.haohaochexian.top/Article/details/gt2coxvbdkj.html

PHP:  public static function f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ngmbxpch.html

JS:   static f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2ynwygrus.html

TS:   static f(): void {}
来源：http://dali.vqdsnc.cn/Article/details/gt2szeofmny.html

Java: static void f() {}
来源：http://dali.hammf.cn/Article/details/gt2htkqrhsg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnxiangtu.top/Article/details/gt2yxcnflud.html

Ruby: def self.f; end
来源：http://dali.quarkkingdee.top/Article/details/gt2jzfjdxye.html

C#:   public static void F() {}
来源：http://dali.cucudq.cn/Article/details/gt2tywapsce.html

[G09] 接口 / 抽象类
来源：http://dali.xinyue.icu/Article/details/gt2tustovgt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hfpthk.cn/Article/details/gt2qjphruvp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuanzx.com/Article/details/gt2tjskxjzo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhiwuduotai.top/Article/details/gt2dfgzhqsj.html

TS:   interface Shape { area(): number; }
来源：http://dali.aizwys.cn/Article/details/gt2cghnvfxe.html

Java: interface Shape { double area(); }
来源：http://dali.svipenyu.cn/Article/details/gt2fteoizde.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2sqacitqa.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jqgufenzy.top/Article/details/gt2rsyewflj.html

C#:   interface IShape { double Area(); }
来源：http://dali.gotoacloud.top/Article/details/gt2sdvorcbi.html

[G10] 访问控制
来源：http://dali.zdqjudy.top/Article/details/gt2lkapdvcv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shangyingyoupin.top/Article/details/gt2nqadyniu.html

PHP:  public / protected / private
来源：http://dali.andypj.xyz/Article/details/gt2ijpypuyx.html

JS:   #private 字段；其余公开
来源：http://dali.snrcjt.cn/Article/details/gt2zkpkswbw.html

TS:   public / protected / private
来源：http://dali.tanke756.top/Article/details/gt2elmmrylv.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigfzy.top/Article/details/gt2lmjdyipj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.quarkkingdee.top/Article/details/gt2lrfzafyo.html

Ruby: public / protected / private
来源：http://dali.316326.xyz/Article/details/gt2yunnfygu.html

C#:   public / protected / private / internal
来源：http://dali.xinyue.icu/Article/details/gt2ovjyufqc.html

[G11] getter / setter
来源：http://dali.yongpay.top/Article/details/gt2xrlshbkf.html

Py:   @property 与 @x.setter
来源：http://dali.gogol.net.cn/Article/details/gt2nbaxukig.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gt2eefkwtxl.html

JS:   get name() { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gt2zrvymoqy.html

TS:   get name(): string { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gt2aynnplrl.html

Java: public String getName() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gt2jfdrqgie.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gt2uaedwnyu.html

Ruby: attr_accessor :name
来源：http://dali.aibaodan.cn/Article/details/gt2rsfdovaq.html

C#:   public string Name { get; set; }
来源：http://dali.guowangkeji.top/Article/details/gt2heufvxoq.html

[G12] 对象转字符串
来源：http://dali.dianchejie.cn/Article/details/gt2glrllpzq.html

Py:   def __str__(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gt2tivszvrt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gt2enannfmi.html

JS:   toString() { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gt2ayzrtvuy.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gt2ogihggiv.html

Java: @Override public String toString() { return name; }
来源：http://dali.ydzc1.top/Article/details/gt2qjzlsutt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gt2zkshiwns.html

Ruby: def to_s; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2yuwetixb.html

C#:   public override string ToString() => Name;
来源：http://dali.yuxming.cn/Article/details/gt2aljvcewe.html

[G13] 判断对象类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hhallkao.html

Py:   isinstance(u, User)
来源：http://dali.zhengqikj.top/Article/details/gt2ifhdvtmd.html

PHP:  $u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gt2kpfivojc.html

JS:   u instanceof User
来源：http://dali.pycfn.com/Article/details/gt2lulmyygh.html

TS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gt2vkwzkqby.html

Java: u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gt2piujydmz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jianghu66.top/Article/details/gt2zibogqov.html

Ruby: u.is_a?(User)
来源：http://dali.kuanghao11.cn/Article/details/gt2kyepsxns.html

C#:   u is User
来源：http://dali.xuetiantiany.cn/Article/details/gt2jgkjzqib.html

[G14] 数据类 / record
来源：http://dali.xziqi.cn/Article/details/gt2nfkkgcbw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tanke756.top/Article/details/gt2zpgnfbtg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cqqwz.cn/Article/details/gt2wwbbiwki.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ydzc1.top/Article/details/gt2qdxqkfwh.html

TS:   type User = { name: string; age: number };
来源：http://dali.dianchejie.cn/Article/details/gt2bxlrrvst.html

Java: record User(String name, int age) {}
来源：http://dali.tanke756.top/Article/details/gt2toenuxwx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xnccqnjz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xuetiantiany.cn/Article/details/gt2ozvoyyhs.html

C#:   record User(string Name, int Age);
来源：http://dali.ivvv.top/Article/details/gt2hsqkbivl.html

[G15] 枚举
来源：http://dali.tianlin.xyz/Article/details/gt2bpeiruju.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ehwqpu.com/Article/details/gt2kyrlorhe.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2atsryzfq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvqkjai.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxinkj.top/Article/details/gt2ioyapyml.html

Java: enum Color { RED, GREEN }
来源：http://dali.yvedp.cn/Article/details/gt2znfbmtfs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zycfv.cn/Article/details/gt2gvbfttgm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangtech.top/Article/details/gt2byzxlrzx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2blodudbw.html

[G16] 对象转数组 / 字典
来源：http://dali.redwolf501.top/Article/details/gt2dpbgakxm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2pnunphas.html

PHP:  get_object_vars($obj);
来源：http://dali.vqdsnc.cn/Article/details/gt2ibtqixeh.html

JS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gt2rzjsqsvt.html

TS:   Object.entries(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2wccezmza.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yueranfly.top/Article/details/gt2ylxcrylx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hywenlv.cn/Article/details/gt2umzeigbz.html

Ruby: obj.instance_variables
来源：http://dali.xuetiantiany.cn/Article/details/gt2ezhfkcvm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.mhx1999.top/Article/details/gt2qwimbcnl.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2xvdqugfw.html

H. 异常与错误处理
来源：http://dali.vqdsnc.cn/Article/details/gt2ejlcgmxg.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2fndehcci.html

[H01] try / catch 基础
来源：http://dali.zhixingplan.top/Article/details/gt2vqoyrmok.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jlsjyb.cn/Article/details/gt2tpuhbuju.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yvedp.cn/Article/details/gt2juqjwvci.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dnquuoqj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gt2xoqsovtr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sxryk.cn/Article/details/gt2pamnlver.html


<!-- 参考信息 -->