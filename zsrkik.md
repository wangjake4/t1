代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.daxiang520.top/Article/details/gtuudebzot.html

TS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gtrcrrhfwv.html

Java: s.lines().toList()
来源：http://dali.jqgfzy.top/Article/details/gtufqbmhvk.html

Go:   strings.Split(s, "\n")
来源：http://dali.mhx1999.top/Article/details/gtqqigwoku.html

Ruby: s.lines
来源：http://dali.hammf.cn/Article/details/gtagphldjk.html

C#:   s.Split('\n')
来源：http://dali.gotoacloud.top/Article/details/gtvfsfwtkn.html

[E20] 判断字符串是否为空
来源：http://dali.wangshuangyany.cn/Article/details/gtjrojzosq.html

Py:   if not s:
来源：http://dali.sweek.top/Article/details/gtobziqwin.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jqgufenzy.top/Article/details/gtmxsckbnp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jyoumei.cn/Article/details/gtoizvayqg.html

TS:   if (s === "") {}
来源：http://dali.daria6918.cn/Article/details/gtqrdrvhma.html

Java: if (s.isEmpty()) {}
来源：http://dali.9152youxi.cn/Article/details/gtlfxsrede.html

Go:   if s == "" {}
来源：http://dali.9152youxi.cn/Article/details/gtxgyblvxk.html

Ruby: if s.empty?
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmywdnwhi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hfpthk.cn/Article/details/gtjpqtqgyn.html

[E21] 超长截断加省略号
来源：http://dali.nwbrower.top/Article/details/gtznrtudze.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hysaishi.cn/Article/details/gtzlkxyqhv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gtyzvganiw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gtxuevedvb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gtuahfbdrk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtdaxefrhs.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gogol.net.cn/Article/details/gtpirawige.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtitymoqrx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtgnemerdw.html

[E22] 字节长度与字符长度
来源：http://dali.gotoacloud.top/Article/details/gtbonppmsr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sysykeji.top/Article/details/gtiajbkpha.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtzwgxddjf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhengqikj.top/Article/details/gtnetnpkdc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hysaishi.cn/Article/details/gtniqcvxnz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jiagoushi.top/Article/details/gtyfbuwrhr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtswzqactz.html

Ruby: s.bytesize;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gtwxeciudp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhoulong.xyz/Article/details/gtpitbdaem.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gthdkpgtom.html

F. 文件与目录
来源：http://dali.daria6918.cn/Article/details/gthtuejhop.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtpvzcxszo.html

[F01] 读取整个文件
来源：http://dali.0kj1m.cn/Article/details/gtxchlqbgs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhengqikj.top/Article/details/gtgrcdcylk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtmzjjipbk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cdnleiting.top/Article/details/gtivdyinxq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtmhhdqymz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtpcubwauy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.9152youxi.cn/Article/details/gtzxhutsgh.html

Ruby: File.read("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtjakuzhzh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtmeiqejsu.html

[F02] 逐行读取文件
来源：http://dali.yj202588.top/Article/details/gtskfvytpb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.0kj1m.cn/Article/details/gtnylscyxw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sweek.top/Article/details/gtmgdknuur.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gtrkoarnpz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gtyjnnoqdk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.wangdashe.top/Article/details/gtwxtskknk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xuanzx.com/Article/details/gtpgsgvkrp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.snrcjt.cn/Article/details/gthdbtmoju.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ivvv.top/Article/details/gtwoincava.html

[F03] 写入文件（覆盖）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnsyqbafw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nwbrower.top/Article/details/gtoqmifznh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zycfv.cn/Article/details/gtdxhvmibf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cucudq.cn/Article/details/gtowvefjpm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gtivkjxqgw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yangfankeji.com/Article/details/gtrzlscwkz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenzaomai.com/Article/details/gtwswtupdv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.mhx1999.top/Article/details/gtohyuqmtq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gtljudhsdw.html

[F04] 追加写入文件
来源：http://dali.kuanghao11.cn/Article/details/gtjqmedkab.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xziqi.cn/Article/details/gtszasbjoa.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sxryk.cn/Article/details/gtzqviutzt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gtywmpplct.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gtxdirdwva.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gaohongyu789.top/Article/details/gtowbbreac.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cucudq.cn/Article/details/gtgskzhpji.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhoulong.xyz/Article/details/gtudkqlrdc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tianlin.xyz/Article/details/gtpmmsnqae.html

[F05] 判断文件或目录是否存在
来源：http://dali.jiagoushi.top/Article/details/gtzpqneazc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.bjfxy.top/Article/details/gterfjfdxi.html

PHP:  file_exists("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtdsjtcptu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtlhvraxmk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtnzybqsaj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtlvtpwvof.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sxryk.cn/Article/details/gtxxqqlcha.html

Ruby: File.exist?("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcodgangh.html

C#:   File.Exists("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtqmvosgyq.html

[F06] 删除文件
来源：http://dali.zhengqikj.top/Article/details/gtlfcmmptu.html

Py:   os.remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtjufrohsx.html

PHP:  unlink("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtwecmblzx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtbdqfyqix.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtxrjfjeod.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtxiqktphu.html

Go:   os.Remove("a.txt")
来源：http://dali.fzhhl.top/Article/details/gthukixxbz.html

Ruby: File.delete("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtbccaeuug.html

C#:   File.Delete("a.txt");
来源：http://dali.havefunace.top/Article/details/gtjuupufbr.html

[F07] 创建目录（含多级）
来源：http://dali.hnqzz.top/Article/details/gtmbhygsyb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ehwqpu.com/Article/details/gtpbvgxozz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yangfankeji.com/Article/details/gtzsiccezu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvzkwuudo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhixingplan.top/Article/details/gtsfckhhhz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnxiangtu.top/Article/details/gttaaeiejg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daxiang520.top/Article/details/gtiqqrdaiq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cashguo.top/Article/details/gtqdbxxeze.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.wangdashe.top/Article/details/gttpodxqgu.html

[F08] 遍历目录
来源：http://dali.sxryk.cn/Article/details/gtpsiuywlx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.0kj1m.cn/Article/details/gtrzhcumwm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.aibaodan.cn/Article/details/gtcfgltfqd.html

JS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gtplgdaqhm.html

TS:   fs.readdirSync("dir")
来源：http://dali.dianchejie.cn/Article/details/gtfqehradc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fzhhl.top/Article/details/gtxrjdddkw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj20258888.top/Article/details/gtfpzynsdc.html

Ruby: Dir.children("dir")
来源：http://dali.dashuyun.cn/Article/details/gtwznpubms.html

C#:   Directory.GetFiles("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtjjufgjjy.html

[F09] 获取文件大小
来源：http://dali.gaohongyu789.top/Article/details/gtiefdbihp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tanke756.top/Article/details/gtziwamjmg.html

PHP:  filesize("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtliukgouo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gtbokektqr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.daria6918.cn/Article/details/gtypxggjai.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtfwuumgfq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dashuyun.cn/Article/details/gtetjxcufq.html

Ruby: File.size("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtmgtmyxla.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jlsjyb.cn/Article/details/gtygtrncjy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.guannengcc.top/Article/details/gthbrjubwu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtxxdaabww.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.daxiang520.top/Article/details/gtjseeokci.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtyuebrepq.html

TS:   path.extname("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtjpyktews.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ppjwa.cn/Article/details/gtxypzlall.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtmstgyokp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtbckprcma.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtdgahrwzg.html

[F11] 复制与移动文件
来源：http://dali.quarkkingdee.top/Article/details/gtfbznltkh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtulgwvtcc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tanke756.top/Article/details/gtxbvdkdhf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gthsglekhr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtttytaica.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cashguo.top/Article/details/gtorybxboi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sufxvd.cn/Article/details/gtjsporyfz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtapsbgiix.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zycfv.cn/Article/details/gtybdgeksy.html

[F12] CSV 读写
来源：http://dali.xylfe.cn/Article/details/gtqymdpdwo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xylfe.cn/Article/details/gtjprowfug.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xinyue.icu/Article/details/gtogqlqsof.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hongshengwenyu.top/Article/details/gtmlzlejhb.html

TS:   // 同上
来源：http://dali.guowangkeji.top/Article/details/gtxylvbxws.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenzaomai.com/Article/details/gtygwsybuz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.fengsongda.top/Article/details/gtgjkrayxz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangdashe.top/Article/details/gtpgzeubub.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hfpthk.cn/Article/details/gtokvlvjcu.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtqewzoxnt.html

G. 面向对象
来源：http://dali.tian-w.cn/Article/details/gtdauhnopt.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtwqwvxham.html

[G01] 定义类
来源：http://dali.shangyingyoupin.top/Article/details/gtvbiwvmkj.html

Py:   class User: pass
来源：http://dali.cashguo.top/Article/details/gtmbzyvupo.html

PHP:  class User {}
来源：http://dali.hfpthk.cn/Article/details/gtxeocfzxa.html

JS:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtjxioukxg.html

TS:   class User { name: string = ""; }
来源：http://dali.zhiwuduotai.top/Article/details/gtutsldxsx.html

Java: class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtgvotbemv.html

Go:   type User struct { Name string }
来源：http://dali.guannengcc.top/Article/details/gtdkslfmwq.html

Ruby: class User; end
来源：http://dali.yongpay.top/Article/details/gtsihxvwsj.html

C#:   class User {}
来源：http://dali.gzhubu.top/Article/details/gtzrqvrrgk.html

[G02] 构造函数
来源：http://dali.hnxiangtu.top/Article/details/gtcblrnzrr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cqqwz.cn/Article/details/gtokpoxltq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hywenlv.cn/Article/details/gtfszluyva.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gtimycgtnl.html

TS:   constructor(public name: string) {}
来源：http://dali.redwolf501.top/Article/details/gtgfbfwxeu.html

Java: User(String name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtzsaaxfyu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhoulong.xyz/Article/details/gtqlaqgxzw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sxryk.cn/Article/details/gteqkpfiix.html

C#:   public User(string name) { Name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtllvuaxwk.html

[G03] 实例属性
来源：http://dali.yj20258.top/Article/details/gtufzrdagc.html

Py:   self.name = "x"
来源：http://dali.xinyue.icu/Article/details/gtwbbojwpx.html

PHP:  public string $name = "x";
来源：http://dali.tanke756.top/Article/details/gtrjftpxnu.html

JS:   this.name = "x";
来源：http://dali.zhengqikj.top/Article/details/gtgmjmwqbt.html

TS:   name: string = "x";
来源：http://dali.guowangkeji.top/Article/details/gtfaykzlui.html

Java: private String name;
来源：http://dali.wangshuangyany.cn/Article/details/gtkjvplucx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tanke756.top/Article/details/gtnsthbzut.html

Ruby: @name = "x"
来源：http://dali.nwbrower.top/Article/details/gtjkiiulzk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuanzhike.top/Article/details/gtmdbeavpm.html

[G04] 定义方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwqulglt.html

Py:   def greet(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gtmcjqlkhr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gtzgghtybr.html

JS:   greet() { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtlporbklw.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtjemzkpmo.html

Java: String greet() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gtfagapifk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gtofwvoroo.html

Ruby: def greet; @name; end
来源：http://dali.hysaishi.cn/Article/details/gtmiuamxys.html

C#:   public string Greet() => Name;
来源：http://dali.yvedp.cn/Article/details/gtaezefhum.html

[G05] 继承
来源：http://dali.gzhubu.top/Article/details/gtyagemhrt.html

Py:   class Admin(User): pass
来源：http://dali.jinqigfzy.top/Article/details/gtwkdrwxud.html

PHP:  class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gttkkyjusz.html

JS:   class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtikbxlcle.html

TS:   class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtjavtmxqy.html

Java: class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtzfutelqa.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangtech.top/Article/details/gtmdqamuri.html

Ruby: class Admin < User; end
来源：http://dali.tian-w.cn/Article/details/gtwyxxquwv.html

C#:   class Admin : User {}
来源：http://dali.xylfe.cn/Article/details/gtjiejxqta.html

[G06] 重写方法
来源：http://dali.jyoumei.cn/Article/details/gtduhgbymw.html

Py:   def greet(self): return "admin"
来源：http://dali.yangfankeji.com/Article/details/gtmtypvlap.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtmjjkrawb.html

JS:   greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtnhbesgbn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtygxvtcie.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtfchjxzpl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sxryk.cn/Article/details/gtgxfwnjpx.html

Ruby: def greet; "admin"; end
来源：http://dali.pengpengdd.cyou/Article/details/gtxpcnrnts.html

C#:   public override string Greet() => "admin";
来源：http://dali.yueranfly.top/Article/details/gtizzqderw.html

[G07] 调用父类方法
来源：http://dali.yuxming.cn/Article/details/gtiwbfgjro.html

Py:   super().greet()
来源：http://dali.cucudq.cn/Article/details/gtjcedkcad.html

PHP:  parent::greet();
来源：http://dali.ppjwa.cn/Article/details/gtmdczgkgk.html

JS:   super.greet();
来源：http://dali.cheryme.top/Article/details/gtmvizmqwd.html

TS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtkqbanrfc.html

Java: super.greet();
来源：http://dali.mhx1999.top/Article/details/gteocsbckm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hysaishi.cn/Article/details/gtdfmlknud.html

Ruby: super
来源：http://dali.hnxiangtu.top/Article/details/gtvuyuilsn.html

C#:   base.Greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtafvjvhur.html

[G08] 静态方法与属性
来源：http://dali.gotoacloud.top/Article/details/gtvxdwyxsi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daria6918.cn/Article/details/gtrwyxjdwy.html

PHP:  public static function f() {}
来源：http://dali.0kj1m.cn/Article/details/gtjwmajcbx.html

JS:   static f() {}
来源：http://dali.meibo888.top/Article/details/gtevpfqdpj.html

TS:   static f(): void {}
来源：http://dali.svipenyu.cn/Article/details/gtfnhotqhz.html

Java: static void f() {}
来源：http://dali.smart0.xyz/Article/details/gtjmxihsck.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvldazbf.html

Ruby: def self.f; end
来源：http://dali.nwbrower.top/Article/details/gtpuxirlbs.html

C#:   public static void F() {}
来源：http://dali.haohaochexian.top/Article/details/gtpkjvsmjm.html

[G09] 接口 / 抽象类
来源：http://dali.cheryme.top/Article/details/gtovuwfzdg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdbjajou.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnxiangtu.top/Article/details/gtlldzhcpa.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ppjwa.cn/Article/details/gtisnvzokg.html

TS:   interface Shape { area(): number; }
来源：http://dali.ppjwa.cn/Article/details/gtgzpvepwq.html

Java: interface Shape { double area(); }
来源：http://dali.yanxiufei.cn/Article/details/gtatvordnv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.smart0.xyz/Article/details/gtrplminfs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aibaodan.cn/Article/details/gtbvilpqbi.html

C#:   interface IShape { double Area(); }
来源：http://dali.xylfe.cn/Article/details/gtcakjtwkc.html

[G10] 访问控制
来源：http://dali.dashuyun.cn/Article/details/gtypycgafl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jyoumei.cn/Article/details/gtlzujvxoo.html

PHP:  public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gtuavyzfdt.html

JS:   #private 字段；其余公开
来源：http://dali.jqgufenzy.top/Article/details/gtbxkvoeql.html

TS:   public / protected / private
来源：http://dali.sxryk.cn/Article/details/gtnlavmvqa.html

Java: public / protected / private / 默认包级
来源：http://dali.meibo888.top/Article/details/gtczlkoehd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigfzy.top/Article/details/gtftazrfeh.html

Ruby: public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtgikvcaet.html

C#:   public / protected / private / internal
来源：http://dali.sysykeji.top/Article/details/gthpokjuba.html

[G11] getter / setter
来源：http://dali.jyoumei.cn/Article/details/gtiqmduxux.html

Py:   @property 与 @x.setter
来源：http://dali.tianlin.xyz/Article/details/gtdtmdlueq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtgojwjveo.html

JS:   get name() { return this._name; }
来源：http://dali.sweek.top/Article/details/gtmfhffpuw.html

TS:   get name(): string { return this._name; }
来源：http://dali.gogol.net.cn/Article/details/gtibywjkzc.html

Java: public String getName() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gthuajeadw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtmrxgbuds.html

Ruby: attr_accessor :name
来源：http://dali.sysykeji.top/Article/details/gtidhycrcv.html

C#:   public string Name { get; set; }
来源：http://dali.ivvv.top/Article/details/gtazdihpjt.html

[G12] 对象转字符串
来源：http://dali.cashguo.top/Article/details/gtoajndyak.html

Py:   def __str__(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gtovbcmtix.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtgxfmqile.html

JS:   toString() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gttqxxluri.html

TS:   toString(): string { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtlrlvxsyn.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtwizygnlm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gtivufjvcq.html

Ruby: def to_s; @name; end
来源：http://dali.cdnleiting.top/Article/details/gtkykkrupq.html

C#:   public override string ToString() => Name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvmhxmdmd.html

[G13] 判断对象类型
来源：http://dali.jiagoushi.top/Article/details/gtsrwfsxdk.html

Py:   isinstance(u, User)
来源：http://dali.cucudq.cn/Article/details/gtnpunmlfc.html

PHP:  $u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtguetchoi.html

JS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gttmjxywml.html

TS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtobmjnqvc.html

Java: u instanceof User
来源：http://dali.cashguo.top/Article/details/gtecchiwbc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.bjfxy.top/Article/details/gtafvwxqjt.html

Ruby: u.is_a?(User)
来源：http://dali.aizwys.cn/Article/details/gtivygerep.html

C#:   u is User
来源：http://dali.hnqzz.top/Article/details/gtuvapczgg.html

[G14] 数据类 / record
来源：http://dali.daxiang520.top/Article/details/gtrkdbbqmn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ehwqpu.com/Article/details/gtvijacish.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.havefunace.top/Article/details/gtqpekqosw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgfzy.top/Article/details/gtopbzozfl.html

TS:   type User = { name: string; age: number };
来源：http://dali.ydzc1.top/Article/details/gtxdfmagbc.html

Java: record User(String name, int age) {}
来源：http://dali.cashguo.top/Article/details/gtsiqdqcel.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yuxming.cn/Article/details/gtqpfdfxzx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.feifeiyinyue.top/Article/details/gtwqkqebnr.html

C#:   record User(string Name, int Age);
来源：http://dali.mhx1999.top/Article/details/gtnbbhvtrm.html

[G15] 枚举
来源：http://dali.cheryme.top/Article/details/gtfbejslco.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xziqi.cn/Article/details/gtvnkcbobq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ehwqpu.com/Article/details/gtuaczkcpm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.c1oappe.top/Article/details/gtstfwsara.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gtkbrzfoyq.html

Java: enum Color { RED, GREEN }
来源：http://dali.snrcjt.cn/Article/details/gtdzrcczjs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.c1oappe.top/Article/details/gtdseempfm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yongpay.top/Article/details/gtsbzriohz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gtwpecjjpr.html

[G16] 对象转数组 / 字典
来源：http://dali.ivvv.top/Article/details/gtgmsvdfkx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gogol.net.cn/Article/details/gtlvygbleq.html

PHP:  get_object_vars($obj);
来源：http://dali.xziqi.cn/Article/details/gtkxnwpumg.html

JS:   Object.entries(obj)
来源：http://dali.yuxming.cn/Article/details/gtkryqwafd.html

TS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtzrcahpdv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hfpthk.cn/Article/details/gtzxhamzxo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xylfe.cn/Article/details/gtquotjxjt.html

Ruby: obj.instance_variables
来源：http://dali.pycfn.com/Article/details/gtotyyokbq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cheryme.top/Article/details/gtovltqztz.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtbdiyvvva.html

H. 异常与错误处理
来源：http://dali.yvedp.cn/Article/details/gtzflqnbnv.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtefgejqnp.html

[H01] try / catch 基础
来源：http://dali.sweek.top/Article/details/gtdyyofvku.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yonumen.top/Article/details/gtyulrdhpg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.quarkkingdee.top/Article/details/gtacdhwoeu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gtokqkjkgc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gtuoetomdv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhoulong.xyz/Article/details/gtkmdyrmjg.html


<!-- 参考信息 -->