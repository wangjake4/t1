代发 wailian999

Ruby: s.lines
来源：http://dali.9152youxi.cn/Article/details/gteaapdiud.html

C#:   s.Split('\n')
来源：http://dali.yj20258888.top/Article/details/gtbgayqsvi.html

[E20] 判断字符串是否为空
来源：http://dali.0kj1m.cn/Article/details/gtyggvoykf.html

Py:   if not s:
来源：http://dali.yueranfly.top/Article/details/gtezaffdam.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxmazlje.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hfpthk.cn/Article/details/gtcsnmchrg.html

TS:   if (s === "") {}
来源：http://dali.havefunace.top/Article/details/gtcunicmnj.html

Java: if (s.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gtekwwropt.html

Go:   if s == "" {}
来源：http://dali.guannengcc.top/Article/details/gtexomubix.html

Ruby: if s.empty?
来源：http://dali.redwolf501.top/Article/details/gtkyxannte.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nanxinkj.top/Article/details/gtwyebybwk.html

[E21] 超长截断加省略号
来源：http://dali.dianchejie.cn/Article/details/gtxggxfymx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gtmqksrped.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gtvzcmhauy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtwaahvmrq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtcmcdheyh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtssfzptet.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sxryk.cn/Article/details/gtlqupbhia.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtcqapeqyp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtzzvdzlph.html

[E22] 字节长度与字符长度
来源：http://dali.hysaishi.cn/Article/details/gtsnrwbpvx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sweek.top/Article/details/gttsacogrh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtgwngqfoo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gtjkwuvdto.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gttiekzdke.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhongyouzk.top/Article/details/gtnennqdfg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhiwuduotai.top/Article/details/gtbwuozgbp.html

Ruby: s.bytesize;  s.length
来源：http://dali.yvedp.cn/Article/details/gtixwerpvc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jyoumei.cn/Article/details/gticjxjnnb.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtwulrfqtv.html

F. 文件与目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmvhdrisl.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtldperjwl.html

[F01] 读取整个文件
来源：http://dali.zycfv.cn/Article/details/gtynsdkbuq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.birdmap.top/Article/details/gtdvcxemco.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtxcyhxaij.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nanxuanxn.top/Article/details/gtrzperjcq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gtiaerjwgp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gtdvngcdqw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shanyushiyangtech.top/Article/details/gtdcladaoc.html

Ruby: File.read("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtggbglqns.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtrilrjhfy.html

[F02] 逐行读取文件
来源：http://dali.birdmap.top/Article/details/gttasizszz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.redwolf501.top/Article/details/gtjdfzcweo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj20258888.top/Article/details/gtrulogcnk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sxryk.cn/Article/details/gtwipigpce.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gthhxrsvbj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gtkeecjyup.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.feifeiyinyue.top/Article/details/gtgdxopbsk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.dianchejie.cn/Article/details/gtqjajlitv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sxryk.cn/Article/details/gtozjczpxq.html

[F03] 写入文件（覆盖）
来源：http://dali.jyoumei.cn/Article/details/gtgkkssipb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yuanzhike.top/Article/details/gtmyaxqyos.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gtcykvrqwt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtxlnfhdir.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gtxuuzwsss.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.kuanghao11.cn/Article/details/gtamwzzuhc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ivvv.top/Article/details/gtwffiaqsv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.svipenyu.cn/Article/details/gtgoqoqmpk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gtxkoetkye.html

[F04] 追加写入文件
来源：http://dali.tianlin.xyz/Article/details/gtuoaesxbk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenlongwang.top/Article/details/gtlybjtrvm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gogol.net.cn/Article/details/gtjzodtwwm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtgvihgsxd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gtlugrxyph.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ybcxt.top/Article/details/gtcgvlmqki.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtpwqxnhvx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.pengpengdd.cyou/Article/details/gtvinokwlp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tianlin.xyz/Article/details/gtpckfjguo.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxuanxn.top/Article/details/gthggfdhrc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhiwuduotai.top/Article/details/gtwnzgdqbg.html

PHP:  file_exists("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtbpaxnrka.html

JS:   fs.existsSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtnybdjntq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gthchufwbx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtkxuhjmnw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yvedp.cn/Article/details/gtntasuwgi.html

Ruby: File.exist?("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtwjkhhhym.html

C#:   File.Exists("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyzmpaktd.html

[F06] 删除文件
来源：http://dali.zhengqikj.top/Article/details/gtniznsbmb.html

Py:   os.remove("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtzolavjdw.html

PHP:  unlink("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxkuteaad.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gtzkcoymze.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtgtmuvrca.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gtewueqpew.html

Go:   os.Remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtkmhtfhzk.html

Ruby: File.delete("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtotpbpzrb.html

C#:   File.Delete("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtqtpwvgwf.html

[F07] 创建目录（含多级）
来源：http://dali.tanke756.top/Article/details/gtqxfjfnck.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jiagoushi.top/Article/details/gtgqctpxac.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.feifeiyinyue.top/Article/details/gtycessual.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pengpengdd.cyou/Article/details/gtjvxcbfot.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dashuyun.cn/Article/details/gteavxxmzf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zdqjudy.top/Article/details/gtgtiooyqi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuanzx.com/Article/details/gtfeymhmyi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.guannengcc.top/Article/details/gtxwaygqed.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tian-w.cn/Article/details/gtuotywvfz.html

[F08] 遍历目录
来源：http://dali.ybcxt.top/Article/details/gtyxhxpety.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jlsjyb.cn/Article/details/gtradmhqsn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.meibo888.top/Article/details/gtgrktukfa.html

JS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gthwgufagj.html

TS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gtyonrwjua.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shuidangran.top/Article/details/gtpnodmrpw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gogol.net.cn/Article/details/gtgdmirgeq.html

Ruby: Dir.children("dir")
来源：http://dali.dianchejie.cn/Article/details/gttrmamulp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.havefunace.top/Article/details/gttufvbyfi.html

[F09] 获取文件大小
来源：http://dali.sysykeji.top/Article/details/gtsfhbdteh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtmysdxckt.html

PHP:  filesize("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtkwpyrnek.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gtirdzpobh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sysykeji.top/Article/details/gttlwjboou.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtmabgskle.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnlzlpuhj.html

Ruby: File.size("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtlkvqvuyf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.daxiang520.top/Article/details/gtzwapjvxh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gogol.net.cn/Article/details/gtjuuloprl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtgfobbjri.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtsrzgjzns.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtkatdxxxp.html

TS:   path.extname("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtilvuvoil.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yongpay.top/Article/details/gtxrqokwyn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtevgbgags.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtzhnnpwpp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtcfwctvei.html

[F11] 复制与移动文件
来源：http://dali.dianchejie.cn/Article/details/gtzpxjdkxn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtjgfrbcwu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.redwolf501.top/Article/details/gtwtkwtxyk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtmsodctac.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtfplcecgt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gtyebekdlx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cheryme.top/Article/details/gtlxstibgq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtowjffpxc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sweek.top/Article/details/gtrbsjbbmi.html

[F12] CSV 读写
来源：http://dali.c1oappe.top/Article/details/gtrzjotlab.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.c1oappe.top/Article/details/gtpuzxstvb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ywan-chungtsiang.top/Article/details/gttnzqcgpp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jlsjyb.cn/Article/details/gtliegsyrw.html

TS:   // 同上
来源：http://dali.hnxiangtu.top/Article/details/gthteooyfj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tian-w.cn/Article/details/gtscrgyzic.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jyoumei.cn/Article/details/gtatnjdrqd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jianghu66.top/Article/details/gtrcntrkxu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangdashe.top/Article/details/gtkprupeuw.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gthfjnflyg.html

G. 面向对象
来源：http://dali.redwolf501.top/Article/details/gteobeigpl.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtcandfgni.html

[G01] 定义类
来源：http://dali.daxiang520.top/Article/details/gtrrbizaug.html

Py:   class User: pass
来源：http://dali.hfpthk.cn/Article/details/gtjpxtiyvb.html

PHP:  class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtrjzagaed.html

JS:   class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtzcbvfwou.html

TS:   class User { name: string = ""; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmjkxxsxq.html

Java: class User {}
来源：http://dali.yonumen.top/Article/details/gtnxfdrpmt.html

Go:   type User struct { Name string }
来源：http://dali.jinqigfzy.top/Article/details/gtqxwduxmd.html

Ruby: class User; end
来源：http://dali.dashuyun.cn/Article/details/gtrhszwyud.html

C#:   class User {}
来源：http://dali.andypj.xyz/Article/details/gtlbzlmiit.html

[G02] 构造函数
来源：http://dali.aibaodan.cn/Article/details/gtgcdwpvvp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xinyue.icu/Article/details/gtugqsmhmg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sysykeji.top/Article/details/gtubxceexq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtrmxtzywk.html

TS:   constructor(public name: string) {}
来源：http://dali.sxryk.cn/Article/details/gtsjuzvyla.html

Java: User(String name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gtjpjeaqtl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhixingplan.top/Article/details/gtabzctaaz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.andypj.xyz/Article/details/gtelphgycp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvswnxscb.html

[G03] 实例属性
来源：http://dali.jyoumei.cn/Article/details/gtgpicywft.html

Py:   self.name = "x"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcpwatefe.html

PHP:  public string $name = "x";
来源：http://dali.yuanzhike.top/Article/details/gtnrbuergs.html

JS:   this.name = "x";
来源：http://dali.hammf.cn/Article/details/gtobdxezkz.html

TS:   name: string = "x";
来源：http://dali.yuxming.cn/Article/details/gtgfxxpihv.html

Java: private String name;
来源：http://dali.316326.xyz/Article/details/gtgotxocny.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cdnleiting.top/Article/details/gtwjnnigbw.html

Ruby: @name = "x"
来源：http://dali.sufxvd.cn/Article/details/gtybkqoqec.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yueranfly.top/Article/details/gtzcajksyx.html

[G04] 定义方法
来源：http://dali.cucudq.cn/Article/details/gtsllakicv.html

Py:   def greet(self): return self.name
来源：http://dali.fengsongda.top/Article/details/gtcojwqduo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtelehyvuj.html

JS:   greet() { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtavehicbo.html

TS:   greet(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtkvdstcfa.html

Java: String greet() { return name; }
来源：http://dali.mhx1999.top/Article/details/gthrjbfpnt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gteymhknbz.html

Ruby: def greet; @name; end
来源：http://dali.yj20258.top/Article/details/gtxqdurgrs.html

C#:   public string Greet() => Name;
来源：http://dali.hfpthk.cn/Article/details/gtsclvppuy.html

[G05] 继承
来源：http://dali.gogol.net.cn/Article/details/gtkgiczegp.html

Py:   class Admin(User): pass
来源：http://dali.daxiang520.top/Article/details/gtdnysmuwl.html

PHP:  class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gthdkzwbcp.html

JS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyahfcgid.html

TS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gtqocxyusv.html

Java: class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtrwhzkbvc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.iojbl.cn/Article/details/gtndvfaxtq.html

Ruby: class Admin < User; end
来源：http://dali.daxiang520.top/Article/details/gtlmomlrxc.html

C#:   class Admin : User {}
来源：http://dali.gotoacloud.top/Article/details/gtdtxfltuf.html

[G06] 重写方法
来源：http://dali.yvedp.cn/Article/details/gtagkfzwup.html

Py:   def greet(self): return "admin"
来源：http://dali.xinyue.icu/Article/details/gtvzplyyqq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtjfbdoogn.html

JS:   greet() { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtwbhcpbip.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtojnzrvln.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtjlcowsqq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sufxvd.cn/Article/details/gtvvepsyhh.html

Ruby: def greet; "admin"; end
来源：http://dali.nwbrower.top/Article/details/gtqhcpimmp.html

C#:   public override string Greet() => "admin";
来源：http://dali.yangfankeji.com/Article/details/gtmtrgohtd.html

[G07] 调用父类方法
来源：http://dali.chenlongwang.top/Article/details/gtphklwdqv.html

Py:   super().greet()
来源：http://dali.fengsongda.top/Article/details/gtjtvcytqp.html

PHP:  parent::greet();
来源：http://dali.nanxuanxn.top/Article/details/gtavuusqyb.html

JS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gtahiwsntw.html

TS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtxuvqgwfw.html

Java: super.greet();
来源：http://dali.xinyue.icu/Article/details/gtewcgqzww.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtknlmqvcm.html

Ruby: super
来源：http://dali.aibaodan.cn/Article/details/gtfndkekcx.html

C#:   base.Greet();
来源：http://dali.cqqwz.cn/Article/details/gtjlhxtqlv.html

[G08] 静态方法与属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujmkhihb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.vqdsnc.cn/Article/details/gtqsddqevt.html

PHP:  public static function f() {}
来源：http://dali.xuanzx.com/Article/details/gtjhnweyry.html

JS:   static f() {}
来源：http://dali.wangdashe.top/Article/details/gthwrtdfhy.html

TS:   static f(): void {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtczzzerel.html

Java: static void f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtcegxffiv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gtkbkfnvhj.html

Ruby: def self.f; end
来源：http://dali.jqgfzy.top/Article/details/gtxktrzgbt.html

C#:   public static void F() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtlkmswfht.html

[G09] 接口 / 抽象类
来源：http://dali.nanxuanxn.top/Article/details/gtykdbwgax.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.guannengcc.top/Article/details/gtzyczataq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.andypj.xyz/Article/details/gtghrplxdo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shzxlz.cn/Article/details/gtncwqqyfi.html

TS:   interface Shape { area(): number; }
来源：http://dali.yvedp.cn/Article/details/gtqyqlmofw.html

Java: interface Shape { double area(); }
来源：http://dali.yangfankeji.com/Article/details/gtrnlhrjcp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yonumen.top/Article/details/gtzczyihmr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yueranfly.top/Article/details/gtqafcstsp.html

C#:   interface IShape { double Area(); }
来源：http://dali.jiagoushi.top/Article/details/gtcazbqsgr.html

[G10] 访问控制
来源：http://dali.sxryk.cn/Article/details/gthocubnch.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sysykeji.top/Article/details/gtbinxbwml.html

PHP:  public / protected / private
来源：http://dali.shuidangran.top/Article/details/gtmqcarkpl.html

JS:   #private 字段；其余公开
来源：http://dali.fzhhl.top/Article/details/gtiwscupso.html

TS:   public / protected / private
来源：http://dali.cheryme.top/Article/details/gtgmyumbmv.html

Java: public / protected / private / 默认包级
来源：http://dali.chenlongwang.top/Article/details/gthcqslfjy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpikwpscf.html

Ruby: public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gtdtgcasxq.html

C#:   public / protected / private / internal
来源：http://dali.ivvv.top/Article/details/gtgcklvpoc.html

[G11] getter / setter
来源：http://dali.xziqi.cn/Article/details/gtpbiqwjzd.html

Py:   @property 与 @x.setter
来源：http://dali.bjfxy.top/Article/details/gtcelnurbp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gtxveykcsh.html

JS:   get name() { return this._name; }
来源：http://dali.iojbl.cn/Article/details/gtatcpgnsa.html

TS:   get name(): string { return this._name; }
来源：http://dali.xylfe.cn/Article/details/gtkhhmrflr.html

Java: public String getName() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtvhxxckrb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtylpwboqj.html

Ruby: attr_accessor :name
来源：http://dali.hammf.cn/Article/details/gtcjfswxhq.html

C#:   public string Name { get; set; }
来源：http://dali.vqdsnc.cn/Article/details/gtbgnsbmqi.html

[G12] 对象转字符串
来源：http://dali.jinqigfzy.top/Article/details/gtvxvzcwru.html

Py:   def __str__(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gtknpfviwh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtdcpaubtt.html

JS:   toString() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtnwfhldkm.html

TS:   toString(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gttwmescif.html

Java: @Override public String toString() { return name; }
来源：http://dali.jianghu66.top/Article/details/gtfhxhxdyc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gttwqbmoat.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gtrxuajyus.html

C#:   public override string ToString() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gtnfwveeve.html

[G13] 判断对象类型
来源：http://dali.tianlin.xyz/Article/details/gtvllzpomi.html

Py:   isinstance(u, User)
来源：http://dali.sufxvd.cn/Article/details/gtrtneapgt.html

PHP:  $u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gtrjjgwebs.html

JS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtmwyqgxdm.html

TS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtwozrcjgj.html

Java: u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtzuqfbxgn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gtojbrpvfv.html

Ruby: u.is_a?(User)
来源：http://dali.yvedp.cn/Article/details/gtswqyxaal.html

C#:   u is User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhitqsxf.html

[G14] 数据类 / record
来源：http://dali.bjfxy.top/Article/details/gteazisydv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj202588.top/Article/details/gtvpjjoraq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.snrcjt.cn/Article/details/gtddnlthre.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hnxiangtu.top/Article/details/gtiigxwcuk.html

TS:   type User = { name: string; age: number };
来源：http://dali.shzxlz.cn/Article/details/gtxelnutqc.html

Java: record User(String name, int age) {}
来源：http://dali.bjfxy.top/Article/details/gtjmxdujju.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pengpengdd.cyou/Article/details/gtedmuynqq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqxltent.html

C#:   record User(string Name, int Age);
来源：http://dali.yuxming.cn/Article/details/gtnniwdusu.html

[G15] 枚举
来源：http://dali.meibo888.top/Article/details/gtzutkwdof.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.smart0.xyz/Article/details/gtsmvaeiyb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xinyue.icu/Article/details/gtaprzxgec.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gogol.net.cn/Article/details/gtuiwktcix.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhixingplan.top/Article/details/gtnmvpkluy.html

Java: enum Color { RED, GREEN }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfkjaiea.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangshuangyany.cn/Article/details/gtfkkzukrm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xuetiantiany.cn/Article/details/gthjcmivxg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.iojbl.cn/Article/details/gtegmhcjst.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258.top/Article/details/gtdezgfvnu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.mhx1999.top/Article/details/gtvhdarijd.html

PHP:  get_object_vars($obj);
来源：http://dali.gogol.net.cn/Article/details/gtwpnchgza.html

JS:   Object.entries(obj)
来源：http://dali.jqgfzy.top/Article/details/gtkpelndew.html

TS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gtcivrzlri.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ybcxt.top/Article/details/gtyljimugx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.c1oappe.top/Article/details/gtwkdcblhk.html

Ruby: obj.instance_variables
来源：http://dali.jinqigfzy.top/Article/details/gtaqxrztts.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.meibo888.top/Article/details/gttrwtlmwt.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtgsvloagm.html

H. 异常与错误处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtoiqtzxtq.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtunaldecb.html

[H01] try / catch 基础
来源：http://dali.pengpengdd.cyou/Article/details/gtizgepbty.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cucudq.cn/Article/details/gtqsqydzvf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guowangkeji.top/Article/details/gtdffemcwd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jyoumei.cn/Article/details/gtyjcylyvg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gtvapsinkm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sweek.top/Article/details/gtxtjajukg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhengqikj.top/Article/details/gtyyouqxgp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.daxiang520.top/Article/details/gtmwkeowex.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhengqikj.top/Article/details/gtdhijbbaj.html

[H02] finally / ensure 收尾
来源：http://dali.yonumen.top/Article/details/gtybqvdqhm.html


<!-- 参考信息 -->