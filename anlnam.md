代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.svipenyu.cn/Article/details/gtbsejmyyu.html

TS:   s.split(/\r?\n/)
来源：http://dali.svipenyu.cn/Article/details/gtabhbedmx.html

Java: s.lines().toList()
来源：http://dali.yj202588.top/Article/details/gtndntjqqb.html

Go:   strings.Split(s, "\n")
来源：http://dali.svipenyu.cn/Article/details/gtfnozzhsj.html

Ruby: s.lines
来源：http://dali.chenzaomai.com/Article/details/gtzscsfdhu.html

C#:   s.Split('\n')
来源：http://dali.birdmap.top/Article/details/gtasvtxspu.html

[E20] 判断字符串是否为空
来源：http://dali.shanyushiyangtech.top/Article/details/gtqocwcuaz.html

Py:   if not s:
来源：http://dali.yanxiufei.cn/Article/details/gtdwelbyjy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.iojbl.cn/Article/details/gtgxoaduvl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.vqdsnc.cn/Article/details/gtlawbdruo.html

TS:   if (s === "") {}
来源：http://dali.iojbl.cn/Article/details/gtrqukekog.html

Java: if (s.isEmpty()) {}
来源：http://dali.hysaishi.cn/Article/details/gtzpcetyjo.html

Go:   if s == "" {}
来源：http://dali.yonumen.top/Article/details/gtpdplrcqx.html

Ruby: if s.empty?
来源：http://dali.pengpengdd.cyou/Article/details/gtdiavuvzh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.guowangkeji.top/Article/details/gtabimhrzf.html

[E21] 超长截断加省略号
来源：http://dali.nanxuanxn.top/Article/details/gtekqrbett.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tanke756.top/Article/details/gtireebbpr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtpxoltply.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gtebtrbxia.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtcwechvcl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtiqurhwat.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.havefunace.top/Article/details/gtcgmmcqpg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtwxgtvsut.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtndiyksyl.html

[E22] 字节长度与字符长度
来源：http://dali.ppjwa.cn/Article/details/gtmefqytfj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.fengsongda.top/Article/details/gtxvapxlim.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqbzbuax.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtcfwpmhjn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xylfe.cn/Article/details/gtphtcjofp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.bjfxy.top/Article/details/gtyfoqbcqj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxinkj.top/Article/details/gtendlplad.html

Ruby: s.bytesize;  s.length
来源：http://dali.cashguo.top/Article/details/gtvjjieazk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xziqi.cn/Article/details/gtlguetttw.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gteokueyuz.html

F. 文件与目录
来源：http://dali.feifeiyinyue.top/Article/details/gtrgvllwvx.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gteteccdrb.html

[F01] 读取整个文件
来源：http://dali.yueranfly.top/Article/details/gtoxglalkp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hywenlv.cn/Article/details/gtnmuxvbht.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gttdifthaj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shuidangran.top/Article/details/gtnrcjfdzw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hammf.cn/Article/details/gtspqngccw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gthomkgndh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xziqi.cn/Article/details/gtmaswyqzk.html

Ruby: File.read("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtsfygpiyi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hammf.cn/Article/details/gtvrthecoo.html

[F02] 逐行读取文件
来源：http://dali.kuanghao11.cn/Article/details/gtpphdxusq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.feifeiyinyue.top/Article/details/gtdfajhtvz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cdnleiting.top/Article/details/gtiygrrvgq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.smart0.xyz/Article/details/gtjtmnihlz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtcbetqvqz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.dashuyun.cn/Article/details/gtmhdeyrzn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sxryk.cn/Article/details/gtcglrfigl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fzhhl.top/Article/details/gtaraaxcng.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guannengcc.top/Article/details/gtzngekmbe.html

[F03] 写入文件（覆盖）
来源：http://dali.redwolf501.top/Article/details/gtrqqrajnl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nanxinkj.top/Article/details/gtwwzsngoo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gzhubu.top/Article/details/gtuvvofate.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gtrkmjhlmk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfknzqdks.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sysykeji.top/Article/details/gtwvushxfa.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pycfn.com/Article/details/gtudbfloqx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.aibaodan.cn/Article/details/gttvabgsde.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.quarkkingdee.top/Article/details/gtoatiozoy.html

[F04] 追加写入文件
来源：http://dali.bjfxy.top/Article/details/gtbkggpjss.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.pycfn.com/Article/details/gtfqnqrycc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ehwqpu.com/Article/details/gthjejvucw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzhbdebq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gtaizieuib.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yuxming.cn/Article/details/gtnataugwg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhixingplan.top/Article/details/gtgtsqdhud.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shangyingyoupin.top/Article/details/gtybwtpwwv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.c1oappe.top/Article/details/gtgagjbjzi.html

[F05] 判断文件或目录是否存在
来源：http://dali.jlsjyb.cn/Article/details/gtdfspbsfi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fengsongda.top/Article/details/gtkuajwgsd.html

PHP:  file_exists("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtyqvggjte.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtrykmzchj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtynyzrrbd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtowpgnlsj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sweek.top/Article/details/gtkvwsilet.html

Ruby: File.exist?("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtzdhvtszn.html

C#:   File.Exists("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtnwyfprtw.html

[F06] 删除文件
来源：http://dali.zhiwuduotai.top/Article/details/gtshcxwhyg.html

Py:   os.remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtezaemaxi.html

PHP:  unlink("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtvrvglpfo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gteqpsnkgu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtkwwvjbax.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gtpvebdyht.html

Go:   os.Remove("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtupzexoxc.html

Ruby: File.delete("a.txt")
来源：http://dali.yonumen.top/Article/details/gtpwjwhxja.html

C#:   File.Delete("a.txt");
来源：http://dali.pycfn.com/Article/details/gtvoxtfzab.html

[F07] 创建目录（含多级）
来源：http://dali.shuidangran.top/Article/details/gtnmdlojfs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zycfv.cn/Article/details/gthuuurrnd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sxryk.cn/Article/details/gtgovolsku.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.quarkkingdee.top/Article/details/gtpeohwltv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tianlin.xyz/Article/details/gtaddqnwxx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.wangdashe.top/Article/details/gtayfmgbum.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jiagoushi.top/Article/details/gtshhdkysj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cheryme.top/Article/details/gtotphhbiz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jianghu66.top/Article/details/gtkekqewol.html

[F08] 遍历目录
来源：http://dali.chenzaomai.com/Article/details/gtvqcthbfv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yonumen.top/Article/details/gtdrdqafnw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxuanxn.top/Article/details/gtoohiyonz.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gtahuwgnla.html

TS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gteakltdjp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gtdedcxond.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.haohaochexian.top/Article/details/gtdmdrmhnl.html

Ruby: Dir.children("dir")
来源：http://dali.cashguo.top/Article/details/gtecqalcrt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.0kj1m.cn/Article/details/gtthmgctlp.html

[F09] 获取文件大小
来源：http://dali.xuetiantiany.cn/Article/details/gtmaewpduy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtxjwrpmlu.html

PHP:  filesize("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtszjspslx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258888.top/Article/details/gtiozmhhpx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gtpqymastv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtjykjrsek.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.pengpengdd.cyou/Article/details/gtoakcqmtb.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvaybtjw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yanxiufei.cn/Article/details/gtyzsfzjpc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.iojbl.cn/Article/details/gtjwpesiwg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtgsyhtkwo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.mhx1999.top/Article/details/gtdztswgnq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtwiaeotwm.html

TS:   path.extname("a.txt")
来源：http://dali.yongpay.top/Article/details/gtzoxkvjhy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pengpengdd.cyou/Article/details/gtxeeatxyh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdktffye.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtpvbpyyyn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtdcrbzdhy.html

[F11] 复制与移动文件
来源：http://dali.jinqigfzy.top/Article/details/gtvrtsvpzt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtcuerpumh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.haohaochexian.top/Article/details/gtavfotnvk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtmcymfajy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtibrwroyv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.birdmap.top/Article/details/gtrleelorc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhoulong.xyz/Article/details/gtptbgxwol.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtbbnirjxm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtriubkaln.html

[F12] CSV 读写
来源：http://dali.zhiwuduotai.top/Article/details/gtjyhusdpl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cheryme.top/Article/details/gtfxsgzqyd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hfpthk.cn/Article/details/gtquxgidxx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xziqi.cn/Article/details/gtcugjqrwq.html

TS:   // 同上
来源：http://dali.redwolf501.top/Article/details/gtxoeiuyvh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sysykeji.top/Article/details/gtxtzvcbvl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj20258.top/Article/details/gtpmryneud.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj20258888.top/Article/details/gtejkgxiia.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sufxvd.cn/Article/details/gtnagkwqea.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gthcklvpdb.html

G. 面向对象
来源：http://dali.yonumen.top/Article/details/gtowwxkjlm.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gttglnqbpb.html

[G01] 定义类
来源：http://dali.fengsongda.top/Article/details/gtkfjpqgpt.html

Py:   class User: pass
来源：http://dali.gogol.net.cn/Article/details/gtcvrabads.html

PHP:  class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtptncwmac.html

JS:   class User {}
来源：http://dali.yuanzhike.top/Article/details/gtmgbbgfxt.html

TS:   class User { name: string = ""; }
来源：http://dali.shuidangran.top/Article/details/gtrzdcbyhg.html

Java: class User {}
来源：http://dali.yj202588.top/Article/details/gtfjgwwvxz.html

Go:   type User struct { Name string }
来源：http://dali.wangdashe.top/Article/details/gtisrpceuw.html

Ruby: class User; end
来源：http://dali.xylfe.cn/Article/details/gtqcwmblws.html

C#:   class User {}
来源：http://dali.meibo888.top/Article/details/gtuyxiijlc.html

[G02] 构造函数
来源：http://dali.zycfv.cn/Article/details/gtmyqdvzuz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.pycfn.com/Article/details/gtphnxakys.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sxryk.cn/Article/details/gtvotpyyfx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gtuprfvjod.html

TS:   constructor(public name: string) {}
来源：http://dali.gaohongyu789.top/Article/details/gtodswyxwj.html

Java: User(String name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gtsifeyxvb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tanke756.top/Article/details/gtyvlhmfei.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ehwqpu.com/Article/details/gtgprqlojo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zdqjudy.top/Article/details/gtrolehaxx.html

[G03] 实例属性
来源：http://dali.iojbl.cn/Article/details/gtezdjdztf.html

Py:   self.name = "x"
来源：http://dali.tian-w.cn/Article/details/gtconsbozh.html

PHP:  public string $name = "x";
来源：http://dali.andypj.xyz/Article/details/gtvfxvzykp.html

JS:   this.name = "x";
来源：http://dali.yangfankeji.com/Article/details/gtureysgnh.html

TS:   name: string = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtpubgsboj.html

Java: private String name;
来源：http://dali.jianghu66.top/Article/details/gtojwwlyqn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yongpay.top/Article/details/gtjukyqzws.html

Ruby: @name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gtpxdokntc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ppjwa.cn/Article/details/gtciiuzzth.html

[G04] 定义方法
来源：http://dali.bjfxy.top/Article/details/gtybyvvumd.html

Py:   def greet(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gtfkdeblvo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtfvaqylmk.html

JS:   greet() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gthkfqhmwz.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtpcgaejbl.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtmkbowznr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gthcauxbjn.html

Ruby: def greet; @name; end
来源：http://dali.iojbl.cn/Article/details/gtiaztfoyf.html

C#:   public string Greet() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkzztsxat.html

[G05] 继承
来源：http://dali.cheryme.top/Article/details/gtbrmtxntu.html

Py:   class Admin(User): pass
来源：http://dali.iojbl.cn/Article/details/gtvghnvdly.html

PHP:  class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtsxneopce.html

JS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtgxjcnksk.html

TS:   class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtqhzdkegr.html

Java: class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtlgddfdqa.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.svipenyu.cn/Article/details/gtsodkwpre.html

Ruby: class Admin < User; end
来源：http://dali.feifeiyinyue.top/Article/details/gtoinsakbr.html

C#:   class Admin : User {}
来源：http://dali.fzhhl.top/Article/details/gtnimnuwxk.html

[G06] 重写方法
来源：http://dali.birdmap.top/Article/details/gtmoatljou.html

Py:   def greet(self): return "admin"
来源：http://dali.fzhhl.top/Article/details/gtnndmlict.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtfplksoaf.html

JS:   greet() { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpmbjmimx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtbfuslipr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtsfkydfzw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cqqwz.cn/Article/details/gtlumzqzvd.html

Ruby: def greet; "admin"; end
来源：http://dali.hammf.cn/Article/details/gtkqjqjrxc.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhengqikj.top/Article/details/gtniwjxklx.html

[G07] 调用父类方法
来源：http://dali.smart0.xyz/Article/details/gtkemxbrwo.html

Py:   super().greet()
来源：http://dali.chenzaomai.com/Article/details/gtsohpgxlj.html

PHP:  parent::greet();
来源：http://dali.jlsjyb.cn/Article/details/gtqzdytsbt.html

JS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gtnwjefvlt.html

TS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtrfrwljox.html

Java: super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtgmtrxmko.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258.top/Article/details/gtchrgvinz.html

Ruby: super
来源：http://dali.wangdashe.top/Article/details/gtrgdneexm.html

C#:   base.Greet();
来源：http://dali.hfpthk.cn/Article/details/gtqwghvaqw.html

[G08] 静态方法与属性
来源：http://dali.xuetiantiany.cn/Article/details/gtlcfxbxnd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuanzx.com/Article/details/gtgqduwlwr.html

PHP:  public static function f() {}
来源：http://dali.smart0.xyz/Article/details/gtrizibvku.html

JS:   static f() {}
来源：http://dali.smart0.xyz/Article/details/gtnbvgbbyv.html

TS:   static f(): void {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtzeqecxte.html

Java: static void f() {}
来源：http://dali.yangfankeji.com/Article/details/gtvkxkdleh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guannengcc.top/Article/details/gtnxmxtkug.html

Ruby: def self.f; end
来源：http://dali.zdqjudy.top/Article/details/gtsugvwpuk.html

C#:   public static void F() {}
来源：http://dali.gzhubu.top/Article/details/gthkijxfob.html

[G09] 接口 / 抽象类
来源：http://dali.zhengqikj.top/Article/details/gtyvflkmjt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxuanxn.top/Article/details/gtfntjnwag.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.9152youxi.cn/Article/details/gtqqaaomvm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cdnleiting.top/Article/details/gtyamzvbnp.html

TS:   interface Shape { area(): number; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbsuwtbl.html

Java: interface Shape { double area(); }
来源：http://dali.xuanzx.com/Article/details/gtrrsaghub.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jianghu66.top/Article/details/gtjogtkcjk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cashguo.top/Article/details/gtkdrwettd.html

C#:   interface IShape { double Area(); }
来源：http://dali.hfpthk.cn/Article/details/gtebzwfoqt.html

[G10] 访问控制
来源：http://dali.dashuyun.cn/Article/details/gtgcrtrcna.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hongshengwenyu.top/Article/details/gtfocvimcz.html

PHP:  public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gtdbtwalpn.html

JS:   #private 字段；其余公开
来源：http://dali.316326.xyz/Article/details/gtlksylayq.html

TS:   public / protected / private
来源：http://dali.yvedp.cn/Article/details/gtanwbccvc.html

Java: public / protected / private / 默认包级
来源：http://dali.jianghu66.top/Article/details/gtwrodrrnz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenjidiqi.icu/Article/details/gtxqdyiwox.html

Ruby: public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gtngneyqdm.html

C#:   public / protected / private / internal
来源：http://dali.jinghuilouyu.cn/Article/details/gtedhdvbvy.html

[G11] getter / setter
来源：http://dali.chenlongwang.top/Article/details/gtitlzyolc.html

Py:   @property 与 @x.setter
来源：http://dali.hywenlv.cn/Article/details/gtxltfmagz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gtgppvtzzi.html

JS:   get name() { return this._name; }
来源：http://dali.xylfe.cn/Article/details/gtrybvytpr.html

TS:   get name(): string { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gtfuxligki.html

Java: public String getName() { return name; }
来源：http://dali.yonumen.top/Article/details/gtpsjletkz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gtifsjzvpx.html

Ruby: attr_accessor :name
来源：http://dali.chenlongwang.top/Article/details/gtgkvavqds.html

C#:   public string Name { get; set; }
来源：http://dali.jqgufenzy.top/Article/details/gtqoktxpud.html

[G12] 对象转字符串
来源：http://dali.xinyue.icu/Article/details/gtarvubgzc.html

Py:   def __str__(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gtbjfujdup.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gtfsrzvugk.html

JS:   toString() { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwbawybnt.html

TS:   toString(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtfnlnmwoi.html

Java: @Override public String toString() { return name; }
来源：http://dali.daria6918.cn/Article/details/gtkoiybdsc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtywsxyghy.html

Ruby: def to_s; @name; end
来源：http://dali.sysykeji.top/Article/details/gtgwyspwgw.html

C#:   public override string ToString() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gtgcxvemyh.html

[G13] 判断对象类型
来源：http://dali.9152youxi.cn/Article/details/gtcmxheiul.html

Py:   isinstance(u, User)
来源：http://dali.sufxvd.cn/Article/details/gtrdjgbhba.html

PHP:  $u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtzagayxer.html

JS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtqhvtlvox.html

TS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtzbhhycht.html

Java: u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtdjkmybmz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigufen.top/Article/details/gtnlnyktne.html

Ruby: u.is_a?(User)
来源：http://dali.yangfankeji.com/Article/details/gtjjmsvjmi.html

C#:   u is User
来源：http://dali.birdmap.top/Article/details/gtowyrbgyo.html

[G14] 数据类 / record
来源：http://dali.jiagoushi.top/Article/details/gtarufdcya.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuanzx.com/Article/details/gtlmejfanp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigufen.top/Article/details/gtxfjqlrin.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ydzc1.top/Article/details/gtxvarxsoc.html

TS:   type User = { name: string; age: number };
来源：http://dali.sysykeji.top/Article/details/gtpkzqrsvo.html

Java: record User(String name, int age) {}
来源：http://dali.zycfv.cn/Article/details/gtalzwecyt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.9152youxi.cn/Article/details/gtdhyqrlsa.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pycfn.com/Article/details/gtwmctqpxm.html

C#:   record User(string Name, int Age);
来源：http://dali.0kj1m.cn/Article/details/gtsyabdpdu.html

[G15] 枚举
来源：http://dali.shangyingyoupin.top/Article/details/gtjlmkeepf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hongshengwenyu.top/Article/details/gtntlivluu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yvedp.cn/Article/details/gtudwmuluj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tanke756.top/Article/details/gtqcjveoda.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gtjudjfhvq.html

Java: enum Color { RED, GREEN }
来源：http://dali.316326.xyz/Article/details/gtwghqdjkg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.snrcjt.cn/Article/details/gtxqukdyee.html

Ruby: Color = %i[red green].freeze
来源：http://dali.c1oappe.top/Article/details/gtlwqazpgs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hfpthk.cn/Article/details/gtcgzhtifl.html

[G16] 对象转数组 / 字典
来源：http://dali.yongpay.top/Article/details/gtqlqlwfoa.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jianghu66.top/Article/details/gtkyuxvyrl.html

PHP:  get_object_vars($obj);
来源：http://dali.shuidangran.top/Article/details/gtmgpkdvwd.html

JS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtknccirug.html

TS:   Object.entries(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtneyelhzx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hfpthk.cn/Article/details/gtzoufzvsr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgfzy.top/Article/details/gtdfayyxse.html

Ruby: obj.instance_variables
来源：http://dali.guannengcc.top/Article/details/gtyeotmiag.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gtjsnpdnzd.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtbausnqxm.html

H. 异常与错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtygdcagtp.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtwvifoege.html

[H01] try / catch 基础
来源：http://dali.sweek.top/Article/details/gtyuslenbc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjyzoryaa.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgfzy.top/Article/details/gtmnfhzfmk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxmdbjpc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gtdmqyhdgj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.0kj1m.cn/Article/details/gtcauhfjrp.html


<!-- 参考信息 -->