代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyufhhzrz.html

[E19] 多行文本按行拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubzetkte.html

Py:   s.splitlines()
来源：http://dali.chenlongwang.top/Article/details/gtkbuifrji.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zdqjudy.top/Article/details/gtvwiaehwr.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhiwuduotai.top/Article/details/gtsglutbcp.html

TS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gtyhuuoizw.html

Java: s.lines().toList()
来源：http://dali.sufxvd.cn/Article/details/gtqoigkmxe.html

Go:   strings.Split(s, "\n")
来源：http://dali.tanke756.top/Article/details/gttgbywrjz.html

Ruby: s.lines
来源：http://dali.mhx1999.top/Article/details/gtvfiatash.html

C#:   s.Split('\n')
来源：http://dali.aibaodan.cn/Article/details/gtjmomwkwf.html

[E20] 判断字符串是否为空
来源：http://dali.hfpthk.cn/Article/details/gttzfhclxj.html

Py:   if not s:
来源：http://dali.havefunace.top/Article/details/gtemlpkuit.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tian-w.cn/Article/details/gtwsbchqmf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.wangdashe.top/Article/details/gtbgbhzncr.html

TS:   if (s === "") {}
来源：http://dali.yueranfly.top/Article/details/gtmzqktapb.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtbqzviyvm.html

Go:   if s == "" {}
来源：http://dali.chenjidiqi.icu/Article/details/gtmssxlblh.html

Ruby: if s.empty?
来源：http://dali.hnxiangtu.top/Article/details/gttezjszkw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhongyouzk.top/Article/details/gtzoynlygi.html

[E21] 超长截断加省略号
来源：http://dali.hnxiangtu.top/Article/details/gtbqwnasub.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnqzz.top/Article/details/gthhfztdji.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gtgvkeyzrf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtuqsunykw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtxffbkbfa.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrvawpfog.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hysaishi.cn/Article/details/gtsqczdxee.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gtjkruwpgm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cheryme.top/Article/details/gtijfcmjol.html

[E22] 字节长度与字符长度
来源：http://dali.xylfe.cn/Article/details/gtoqxaqzcj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tianlin.xyz/Article/details/gthjxtkpkn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtgccipiua.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hysaishi.cn/Article/details/gtrenltpoh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gtucdnzcac.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sysykeji.top/Article/details/gtlgvfaxer.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jiagoushi.top/Article/details/gtrttkksed.html

Ruby: s.bytesize;  s.length
来源：http://dali.ybcxt.top/Article/details/gtfevhqcfr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhoulong.xyz/Article/details/gtjnupfaxr.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtblebkfqc.html

F. 文件与目录
来源：http://dali.tian-w.cn/Article/details/gtiedtfssg.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtknslzlqg.html

[F01] 读取整个文件
来源：http://dali.gzhubu.top/Article/details/gtjwendlqy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.havefunace.top/Article/details/gtgpdipdzg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtkckscitj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dianchejie.cn/Article/details/gtobcsjufi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtyvwkvevo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gttwzrweak.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.pycfn.com/Article/details/gtzfmepvzn.html

Ruby: File.read("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtyweuvbzr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtkusoutyu.html

[F02] 逐行读取文件
来源：http://dali.shzxlz.cn/Article/details/gtmjzejoge.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tianlin.xyz/Article/details/gtdejytbmq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhongyouzk.top/Article/details/gtibgnolep.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shangyingyoupin.top/Article/details/gttjpksgww.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxuanxn.top/Article/details/gtudleayta.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sweek.top/Article/details/gthoucshvt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guowangkeji.top/Article/details/gtgznukokd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkyyaedvf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.feifeiyinyue.top/Article/details/gtesglqwcw.html

[F03] 写入文件（覆盖）
来源：http://dali.jiagoushi.top/Article/details/gtptwkfycx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ppjwa.cn/Article/details/gtzpwmoanq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.fzhhl.top/Article/details/gtwirdujys.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gtfqshegfw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gtlynijkzn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hongshengwenyu.top/Article/details/gtwpmwzfaj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ydzc1.top/Article/details/gtyuyhnmib.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hnxiangtu.top/Article/details/gtypppntvg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gzhubu.top/Article/details/gtglmjwgnj.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gtiszfemip.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yueranfly.top/Article/details/gtgqchchao.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jlsjyb.cn/Article/details/gtszooqsqi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtvrnkmpzc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tian-w.cn/Article/details/gtisxyljxh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.guannengcc.top/Article/details/gtgrhlazzz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shzxlz.cn/Article/details/gtdhottdqo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenlongwang.top/Article/details/gtxeoxxemr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.meibo888.top/Article/details/gteeobeinr.html

[F05] 判断文件或目录是否存在
来源：http://dali.yuanzhike.top/Article/details/gtepqcozju.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinghuilouyu.cn/Article/details/gtycohyzak.html

PHP:  file_exists("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtavbgiubk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtaxbkdgss.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtewnvbbrx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtcveudcoy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuxming.cn/Article/details/gtudpcebpm.html

Ruby: File.exist?("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtplaaovdh.html

C#:   File.Exists("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtqukmqvdq.html

[F06] 删除文件
来源：http://dali.xinyue.icu/Article/details/gtnzzfehla.html

Py:   os.remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopzlwoef.html

PHP:  unlink("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtobvnnqbj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtbefquaef.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtxzxpvtvi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtbiktppde.html

Go:   os.Remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtzuckorqw.html

Ruby: File.delete("a.txt")
来源：http://dali.cashguo.top/Article/details/gtkqkmlvhp.html

C#:   File.Delete("a.txt");
来源：http://dali.tanke756.top/Article/details/gtlwfpicwe.html

[F07] 创建目录（含多级）
来源：http://dali.jlsjyb.cn/Article/details/gtcavbgphs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbllosqc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258888.top/Article/details/gtbusnzqof.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tianlin.xyz/Article/details/gtwrgcwfzn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.birdmap.top/Article/details/gtkqhhwduw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gzhubu.top/Article/details/gthjcqprvs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ydzc1.top/Article/details/gtjjzhfsrz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shanyushiyangtech.top/Article/details/gteqxmqaty.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.wangshuangyany.cn/Article/details/gtcurktppr.html

[F08] 遍历目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnyqifkp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlniprxti.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yanxiufei.cn/Article/details/gtgbgelvvf.html

JS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gtyiuhreje.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqpasmwz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gtfjerunio.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtwrggkvba.html

Ruby: Dir.children("dir")
来源：http://dali.snrcjt.cn/Article/details/gtzqbjiajt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aibaodan.cn/Article/details/gtvvpzvfgh.html

[F09] 获取文件大小
来源：http://dali.yj20258888.top/Article/details/gtbizvykze.html

Py:   os.path.getsize("a.txt")
来源：http://dali.meibo888.top/Article/details/gteuvhajmj.html

PHP:  filesize("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtmiolzrwx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.feifeiyinyue.top/Article/details/gtmpvtirka.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangtech.top/Article/details/gtmpalkgli.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtesnokulq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenlongwang.top/Article/details/gtesbpcwur.html

Ruby: File.size("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtcigpfyzv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.9152youxi.cn/Article/details/gtsfsqphjd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ivvv.top/Article/details/gthlvregyw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtxyoeixsr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtpuqqcizw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtptkraqwe.html

TS:   path.extname("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwytswtgm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.iojbl.cn/Article/details/gtxvudbilv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtmehcyqbi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtpwjatyqv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtnjwoajrx.html

[F11] 复制与移动文件
来源：http://dali.yanxiufei.cn/Article/details/gtzclhxenn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtswjpabju.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtfjkoosbk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtxfylgxmk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtlxgocfvk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yuxming.cn/Article/details/gtjjrbbumd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shuidangran.top/Article/details/gtrxljfcfc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtxfadxxkq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tian-w.cn/Article/details/gtsackizyi.html

[F12] CSV 读写
来源：http://dali.cheryme.top/Article/details/gtonutmfzr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gzhubu.top/Article/details/gtbdmpxwkf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzaimtpia.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.aizwys.cn/Article/details/gtxcfppepg.html

TS:   // 同上
来源：http://dali.wangshuangyany.cn/Article/details/gtfsndjecv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.aizwys.cn/Article/details/gtgfaeyogq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jianghu66.top/Article/details/gtevodfntt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqpewuzg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258.top/Article/details/gtizdorelm.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtlpypfotc.html

G. 面向对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtjoyqvvpz.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtpckoohyr.html

[G01] 定义类
来源：http://dali.yuxming.cn/Article/details/gtavijgsbo.html

Py:   class User: pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gtigwzssop.html

PHP:  class User {}
来源：http://dali.birdmap.top/Article/details/gtwxcbkaca.html

JS:   class User {}
来源：http://dali.shuidangran.top/Article/details/gtkytunxej.html

TS:   class User { name: string = ""; }
来源：http://dali.sweek.top/Article/details/gtuytpwmdh.html

Java: class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtylyfuuyq.html

Go:   type User struct { Name string }
来源：http://dali.mhx1999.top/Article/details/gtbihwqefq.html

Ruby: class User; end
来源：http://dali.zdqjudy.top/Article/details/gtbvfsypya.html

C#:   class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtjqcirpdc.html

[G02] 构造函数
来源：http://dali.birdmap.top/Article/details/gtdgcwnrlr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258888.top/Article/details/gtvpwqmslb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gotoacloud.top/Article/details/gtgbjnqpuf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtbawlvlug.html

TS:   constructor(public name: string) {}
来源：http://dali.hammf.cn/Article/details/gtjwpfkmwe.html

Java: User(String name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkmhsbnze.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ppjwa.cn/Article/details/gtvylxmwsm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tanke756.top/Article/details/gtddkayvsu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.c1oappe.top/Article/details/gtubdszstt.html

[G03] 实例属性
来源：http://dali.jlsjyb.cn/Article/details/gtccfydlev.html

Py:   self.name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gteicxsjgz.html

PHP:  public string $name = "x";
来源：http://dali.hammf.cn/Article/details/gttnjeakmg.html

JS:   this.name = "x";
来源：http://dali.wangdashe.top/Article/details/gtbkfssvar.html

TS:   name: string = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtudcbgedy.html

Java: private String name;
来源：http://dali.yonumen.top/Article/details/gtvvsivyjr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sufxvd.cn/Article/details/gtsylgwchq.html

Ruby: @name = "x"
来源：http://dali.jlsjyb.cn/Article/details/gtlwrvwhzo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj202588.top/Article/details/gtimmnaoqb.html

[G04] 定义方法
来源：http://dali.sysykeji.top/Article/details/gtdolrjeau.html

Py:   def greet(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gtvvojzawx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gtwueepmvz.html

JS:   greet() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gtrpcxwsyj.html

TS:   greet(): string { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtptdcpkum.html

Java: String greet() { return name; }
来源：http://dali.yj20258888.top/Article/details/gtwgobhtmt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gtyouiqyjj.html

Ruby: def greet; @name; end
来源：http://dali.yj20258888.top/Article/details/gtpzhozjxg.html

C#:   public string Greet() => Name;
来源：http://dali.jianghu66.top/Article/details/gtbhvevwho.html

[G05] 继承
来源：http://dali.yj202588.top/Article/details/gthshngffr.html

Py:   class Admin(User): pass
来源：http://dali.jyoumei.cn/Article/details/gtqorpgbny.html

PHP:  class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtmnwdkqlr.html

JS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtwlhykyvj.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtnedvaafi.html

Java: class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtrlfkpvji.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhixingplan.top/Article/details/gtcnntrmve.html

Ruby: class Admin < User; end
来源：http://dali.nanxinkj.top/Article/details/gtgoxshoiz.html

C#:   class Admin : User {}
来源：http://dali.wangshuangyany.cn/Article/details/gthhzzeoxc.html

[G06] 重写方法
来源：http://dali.aibaodan.cn/Article/details/gtcgfdojqt.html

Py:   def greet(self): return "admin"
来源：http://dali.hysaishi.cn/Article/details/gtxohjtxis.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtfuvjcufu.html

JS:   greet() { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtozzbvxap.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtinjmulyi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtqlogckgu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinghuilouyu.cn/Article/details/gtssondhsk.html

Ruby: def greet; "admin"; end
来源：http://dali.fzhhl.top/Article/details/gtgaxupovb.html

C#:   public override string Greet() => "admin";
来源：http://dali.hysaishi.cn/Article/details/gtphmkpjlb.html

[G07] 调用父类方法
来源：http://dali.shzxlz.cn/Article/details/gtfeyizekb.html

Py:   super().greet()
来源：http://dali.jlsjyb.cn/Article/details/gtbwhuaelb.html

PHP:  parent::greet();
来源：http://dali.yvedp.cn/Article/details/gtivwpicpt.html

JS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gtawzfvsgw.html

TS:   super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gtfccbnizi.html

Java: super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtbbfhogpt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.havefunace.top/Article/details/gtyxlkseyl.html

Ruby: super
来源：http://dali.quarkkingdee.top/Article/details/gtfikqwmvy.html

C#:   base.Greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtuobrvksz.html

[G08] 静态方法与属性
来源：http://dali.aibaodan.cn/Article/details/gtgexgqkas.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.dianchejie.cn/Article/details/gtzyitqdca.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gtogbeksue.html

JS:   static f() {}
来源：http://dali.nanxinkj.top/Article/details/gthvtmllug.html

TS:   static f(): void {}
来源：http://dali.hnqzz.top/Article/details/gtaodjzekf.html

Java: static void f() {}
来源：http://dali.snrcjt.cn/Article/details/gtgpkeoirv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yvedp.cn/Article/details/gtusbqcwpg.html

Ruby: def self.f; end
来源：http://dali.ehwqpu.com/Article/details/gtbdmfzgxd.html

C#:   public static void F() {}
来源：http://dali.nwbrower.top/Article/details/gtdjfmzmqt.html

[G09] 接口 / 抽象类
来源：http://dali.shangyingyoupin.top/Article/details/gtpwehcgxw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.dianchejie.cn/Article/details/gthhizciny.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cdnleiting.top/Article/details/gtbkehegqf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guannengcc.top/Article/details/gtxgjzuuys.html

TS:   interface Shape { area(): number; }
来源：http://dali.gogol.net.cn/Article/details/gtywrlxyzx.html

Java: interface Shape { double area(); }
来源：http://dali.nwbrower.top/Article/details/gtivuqoctv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jianghu66.top/Article/details/gtteybabpw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tanke756.top/Article/details/gtufontynt.html

C#:   interface IShape { double Area(); }
来源：http://dali.gaohongyu789.top/Article/details/gtkvdmuyqy.html

[G10] 访问控制
来源：http://dali.hnqzz.top/Article/details/gtcauhwock.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hongshengwenyu.top/Article/details/gtbrjzrtzb.html

PHP:  public / protected / private
来源：http://dali.shuidangran.top/Article/details/gttvhyiahj.html

JS:   #private 字段；其余公开
来源：http://dali.aizwys.cn/Article/details/gtsnrhhnci.html

TS:   public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gtrukdvnrz.html

Java: public / protected / private / 默认包级
来源：http://dali.feifeiyinyue.top/Article/details/gtqrwcwoah.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gzhubu.top/Article/details/gtkmrzknkj.html

Ruby: public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gtzvxepimd.html

C#:   public / protected / private / internal
来源：http://dali.hongshengwenyu.top/Article/details/gtnjqxgngr.html

[G11] getter / setter
来源：http://dali.316326.xyz/Article/details/gtnxmfhakl.html

Py:   @property 与 @x.setter
来源：http://dali.havefunace.top/Article/details/gthtxzwupz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gtfqffxpxp.html

JS:   get name() { return this._name; }
来源：http://dali.ivvv.top/Article/details/gtoipilndm.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gtmrvcmsvc.html

Java: public String getName() { return name; }
来源：http://dali.yvedp.cn/Article/details/gtrziiqjxy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gttxpaohcb.html

Ruby: attr_accessor :name
来源：http://dali.yanxiufei.cn/Article/details/gtjhvmmmmn.html

C#:   public string Name { get; set; }
来源：http://dali.zhixingplan.top/Article/details/gtfqdpcyto.html

[G12] 对象转字符串
来源：http://dali.yonumen.top/Article/details/gtaydrnaor.html

Py:   def __str__(self): return self.name
来源：http://dali.cashguo.top/Article/details/gtnkceozne.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gtgaxeetxw.html

JS:   toString() { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtygyfuudp.html

TS:   toString(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtwfgdnuzh.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtwuxevpzu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtfcvmvdwl.html

Ruby: def to_s; @name; end
来源：http://dali.zdqjudy.top/Article/details/gtrqslpvis.html

C#:   public override string ToString() => Name;
来源：http://dali.redwolf501.top/Article/details/gtwcqkaitj.html

[G13] 判断对象类型
来源：http://dali.ydzc1.top/Article/details/gtwtrwjejj.html

Py:   isinstance(u, User)
来源：http://dali.nanxuanxn.top/Article/details/gtngzocydr.html

PHP:  $u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtmyhnioqi.html

JS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtyjexnchd.html

TS:   u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtfotirgtz.html

Java: u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtiyniegyw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shuidangran.top/Article/details/gtbpxljotn.html

Ruby: u.is_a?(User)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnridmlfh.html

C#:   u is User
来源：http://dali.wangshuangyany.cn/Article/details/gtmeycghkt.html

[G14] 数据类 / record
来源：http://dali.shzxlz.cn/Article/details/gtafqyywvd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.aizwys.cn/Article/details/gtyllavxpz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jyoumei.cn/Article/details/gtezhsbasg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ivvv.top/Article/details/gtcakqwoex.html

TS:   type User = { name: string; age: number };
来源：http://dali.tanke756.top/Article/details/gtabrshmkz.html

Java: record User(String name, int age) {}
来源：http://dali.jyoumei.cn/Article/details/gtneaaesoq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhiwuduotai.top/Article/details/gtjocvjbif.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nwbrower.top/Article/details/gtvfzxaull.html

C#:   record User(string Name, int Age);
来源：http://dali.nwbrower.top/Article/details/gtrdnxfkkw.html

[G15] 枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiowkcgon.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yangfankeji.com/Article/details/gtcspxbazk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.0kj1m.cn/Article/details/gtxcgameon.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gaohongyu789.top/Article/details/gtufwbuyxq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gttbsalqwf.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuanzhike.top/Article/details/gtvutjzssz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tianlin.xyz/Article/details/gtealtzdzy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.smart0.xyz/Article/details/gtppqzihuk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gtysoaklvd.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gtwqsyfpho.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yongpay.top/Article/details/gtmktwxxzp.html

PHP:  get_object_vars($obj);
来源：http://dali.aibaodan.cn/Article/details/gtxckqjnic.html

JS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gtefohkefm.html

TS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gtwafqmpar.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tian-w.cn/Article/details/gtlbhdxniy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pengpengdd.cyou/Article/details/gtxlvksunb.html

Ruby: obj.instance_variables
来源：http://dali.tian-w.cn/Article/details/gttyimujhg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gtdmyzkfwf.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtkqxnuaed.html

H. 异常与错误处理
来源：http://dali.nanxuanxn.top/Article/details/gtaavfctkr.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtmtnwdtjq.html

[H01] try / catch 基础
来源：http://dali.yueranfly.top/Article/details/gtescpqwnu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yvedp.cn/Article/details/gtnqrwqzle.html


<!-- 参考信息 -->