代发 wailian999

Ruby: s.lines
来源：http://dali.daxiang520.top/Article/details/gtyfyeakbh.html

C#:   s.Split('\n')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjrxdqam.html

[E20] 判断字符串是否为空
来源：http://dali.sxryk.cn/Article/details/gtcoskslxr.html

Py:   if not s:
来源：http://dali.shangyingyoupin.top/Article/details/gtuxdxzeuo.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.guannengcc.top/Article/details/gtsmknxulo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.snrcjt.cn/Article/details/gticuvpzuy.html

TS:   if (s === "") {}
来源：http://dali.aibaodan.cn/Article/details/gtjexxvlpo.html

Java: if (s.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gtpcdaludo.html

Go:   if s == "" {}
来源：http://dali.tian-w.cn/Article/details/gtljhgvhlz.html

Ruby: if s.empty?
来源：http://dali.jinqigufen.top/Article/details/gtkloxzwff.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fzhhl.top/Article/details/gtmrjrprpf.html

[E21] 超长截断加省略号
来源：http://dali.gotoacloud.top/Article/details/gtyfnlfsbp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hysaishi.cn/Article/details/gtuouvcjfd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtcoosfbts.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gtuckhutkt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtveyiteyx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtelirqtyo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.9152youxi.cn/Article/details/gtavgdnwpt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtmfamdtle.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guannengcc.top/Article/details/gthbxghrdo.html

[E22] 字节长度与字符长度
来源：http://dali.zhoulong.xyz/Article/details/gtgsgkncrf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtnmlwyjto.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtpgxfbhdf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xylfe.cn/Article/details/gtbtxkxqkm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xylfe.cn/Article/details/gttxyswzov.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hysaishi.cn/Article/details/gtubwvwnca.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cheryme.top/Article/details/gtmkeppemr.html

Ruby: s.bytesize;  s.length
来源：http://dali.yvedp.cn/Article/details/gtjdnahafc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hywenlv.cn/Article/details/gtnwelyihx.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgqmvupq.html

F. 文件与目录
来源：http://dali.chenlongwang.top/Article/details/gtdvnfjrtd.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtvjyqucdw.html

[F01] 读取整个文件
来源：http://dali.daxiang520.top/Article/details/gtaukwjsfs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pycfn.com/Article/details/gtizklykff.html

PHP:  file_get_contents("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gterdkzdki.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xinyue.icu/Article/details/gtvsarikaw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gtxavlbpib.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtnozzjtaa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xinyue.icu/Article/details/gtykiistko.html

Ruby: File.read("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtrulerojv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yongpay.top/Article/details/gtulyzembm.html

[F02] 逐行读取文件
来源：http://dali.shangyingyoupin.top/Article/details/gtoochfgbf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.andypj.xyz/Article/details/gtckaqxvjx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yvedp.cn/Article/details/gtzmjjpejy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ybcxt.top/Article/details/gttoinvihz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sufxvd.cn/Article/details/gtuujrfntd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xuanzx.com/Article/details/gtaienvewy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xuetiantiany.cn/Article/details/gtaesbckdb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yangfankeji.com/Article/details/gteslixyuv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjgwfnzan.html

[F03] 写入文件（覆盖）
来源：http://dali.guowangkeji.top/Article/details/gtjcwmayrw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hammf.cn/Article/details/gthsilfpvq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gtbddmdaeq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daxiang520.top/Article/details/gtdnweagkc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gtojwqphsx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.wangdashe.top/Article/details/gtduwdhlaj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ybcxt.top/Article/details/gtidolnkiy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gttisvwuuq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gtdyxtznlj.html

[F04] 追加写入文件
来源：http://dali.hywenlv.cn/Article/details/gthvsicqlr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtmfnqhnhc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shzxlz.cn/Article/details/gthykktwqs.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gteastrpyb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gtwrdokpkf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhongyouzk.top/Article/details/gtrxvmgbvt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yvedp.cn/Article/details/gtzwahjnmq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jqgufenzy.top/Article/details/gtnijszxya.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgpqndkce.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdgsnpfx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwrinfphl.html

PHP:  file_exists("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtfqcoxtlz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtsatmrlht.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtoenophon.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gttasmmwrl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shzxlz.cn/Article/details/gtoyzqewml.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258.top/Article/details/gthrmrhsvc.html

C#:   File.Exists("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtkwyalyuj.html

[F06] 删除文件
来源：http://dali.tianlin.xyz/Article/details/gtzffgqhbc.html

Py:   os.remove("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtmlwrdnmz.html

PHP:  unlink("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtcbeisrwf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtbrlvozse.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtswkcsmaw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtdtzieffg.html

Go:   os.Remove("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtesfmqkrz.html

Ruby: File.delete("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtixjcsjcg.html

C#:   File.Delete("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtywwnfxxt.html

[F07] 创建目录（含多级）
来源：http://dali.hnxiangtu.top/Article/details/gtdcvapdok.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.snrcjt.cn/Article/details/gtllprxjuv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tanke756.top/Article/details/gtgavppsov.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigufen.top/Article/details/gtxopscmao.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gtnyngtpms.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shzxlz.cn/Article/details/gtiaafpuro.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnitfmvp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gotoacloud.top/Article/details/gtgeirwyqp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.iojbl.cn/Article/details/gtbrybeqtg.html

[F08] 遍历目录
来源：http://dali.yvedp.cn/Article/details/gtbystzvpj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yongpay.top/Article/details/gtdaprzizu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.316326.xyz/Article/details/gttphokqrn.html

JS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtugdgiteu.html

TS:   fs.readdirSync("dir")
来源：http://dali.xuanzx.com/Article/details/gttabhvzty.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gtmzmiwupk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hfpthk.cn/Article/details/gtavqhqjvy.html

Ruby: Dir.children("dir")
来源：http://dali.aibaodan.cn/Article/details/gtlovebrta.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ivvv.top/Article/details/gtnpivhnrx.html

[F09] 获取文件大小
来源：http://dali.yj20258888.top/Article/details/gtworijeau.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtvwlpekag.html

PHP:  filesize("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtjlitykwt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nanxuanxn.top/Article/details/gtuutfrhfe.html

TS:   fs.statSync("a.txt").size
来源：http://dali.redwolf501.top/Article/details/gtgjnxaypo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtplpargpt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.mhx1999.top/Article/details/gtnspillvp.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgscrdidd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.0kj1m.cn/Article/details/gtsdlbunny.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.aibaodan.cn/Article/details/gtfmrvqdda.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtootlfqou.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xuanzx.com/Article/details/gtioykfqdf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtnxhbiiht.html

TS:   path.extname("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtcpbreake.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.9152youxi.cn/Article/details/gtysfngbgb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtvrtuncvb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtzwwxlzcg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtrilqexpt.html

[F11] 复制与移动文件
来源：http://dali.xziqi.cn/Article/details/gtyaowkcka.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtcewrfxmv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.316326.xyz/Article/details/gtjurdsxda.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtqmvnhtfi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtzsevfjml.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gzhubu.top/Article/details/gtpqhjvcsx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guannengcc.top/Article/details/gtksysfplb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gttokeaisj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.kuanghao11.cn/Article/details/gtgthlitpx.html

[F12] CSV 读写
来源：http://dali.chenjidiqi.icu/Article/details/gtrxamcwkl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.guowangkeji.top/Article/details/gtlsmvjtnn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tianlin.xyz/Article/details/gtfrzhiwld.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xuetiantiany.cn/Article/details/gtmefiamyx.html

TS:   // 同上
来源：http://dali.ydzc1.top/Article/details/gtgjpzicct.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.9152youxi.cn/Article/details/gtecbpirgu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.wangshuangyany.cn/Article/details/gtdxrxrfgl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yuanzhike.top/Article/details/gtbyavtzba.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljuwttpd.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtuurtsqng.html

G. 面向对象
来源：http://dali.gogol.net.cn/Article/details/gtcbrwcrtn.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtepqzkawf.html

[G01] 定义类
来源：http://dali.chenjidiqi.icu/Article/details/gtersskxqm.html

Py:   class User: pass
来源：http://dali.yvedp.cn/Article/details/gthyrxupif.html

PHP:  class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtgufxidhj.html

JS:   class User {}
来源：http://dali.fengsongda.top/Article/details/gtqitelhkc.html

TS:   class User { name: string = ""; }
来源：http://dali.feifeiyinyue.top/Article/details/gtuwmeiipc.html

Java: class User {}
来源：http://dali.meibo888.top/Article/details/gtektqbfuz.html

Go:   type User struct { Name string }
来源：http://dali.cqqwz.cn/Article/details/gtbhhfpvfi.html

Ruby: class User; end
来源：http://dali.andypj.xyz/Article/details/gtvkcwxnur.html

C#:   class User {}
来源：http://dali.yueranfly.top/Article/details/gtvuidltwi.html

[G02] 构造函数
来源：http://dali.jinqigufen.top/Article/details/gtwgrhksne.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jqgfzy.top/Article/details/gttgzvbpum.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtudjyobvy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sxryk.cn/Article/details/gtlishcwbh.html

TS:   constructor(public name: string) {}
来源：http://dali.xinyue.icu/Article/details/gtqbjdasvw.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtzghdqnhi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jiagoushi.top/Article/details/gtqqtkmytv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hysaishi.cn/Article/details/gtnfiuvoik.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tianlin.xyz/Article/details/gtqhefggji.html

[G03] 实例属性
来源：http://dali.shuidangran.top/Article/details/gtcnapspbk.html

Py:   self.name = "x"
来源：http://dali.hammf.cn/Article/details/gtuvtjcmeh.html

PHP:  public string $name = "x";
来源：http://dali.hfpthk.cn/Article/details/gttldwtimr.html

JS:   this.name = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtkvqfverb.html

TS:   name: string = "x";
来源：http://dali.chenlongwang.top/Article/details/gtgvyihfwf.html

Java: private String name;
来源：http://dali.gogol.net.cn/Article/details/gtgiytfyty.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yangfankeji.com/Article/details/gtpyyvpbau.html

Ruby: @name = "x"
来源：http://dali.wangdashe.top/Article/details/gtdyteffcw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guowangkeji.top/Article/details/gtlgadidrt.html

[G04] 定义方法
来源：http://dali.sufxvd.cn/Article/details/gtisxaxapv.html

Py:   def greet(self): return self.name
来源：http://dali.yj202588.top/Article/details/gtmqqgqwmy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtbyyzlhol.html

JS:   greet() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtylwzxxsk.html

TS:   greet(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtfnqmdczz.html

Java: String greet() { return name; }
来源：http://dali.meibo888.top/Article/details/gtqhdyinrz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gttxsipupz.html

Ruby: def greet; @name; end
来源：http://dali.ybcxt.top/Article/details/gtxmefkjry.html

C#:   public string Greet() => Name;
来源：http://dali.0kj1m.cn/Article/details/gteglzgtfd.html

[G05] 继承
来源：http://dali.yj20258888.top/Article/details/gtisrlxgmh.html

Py:   class Admin(User): pass
来源：http://dali.jiagoushi.top/Article/details/gtgeeertnk.html

PHP:  class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtcpknecrp.html

JS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtifgxmxol.html

TS:   class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtvfdmvgkl.html

Java: class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtpigrxsdq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tianlin.xyz/Article/details/gtgnbcsdoe.html

Ruby: class Admin < User; end
来源：http://dali.c1oappe.top/Article/details/gtnwgozumh.html

C#:   class Admin : User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudquzjsv.html

[G06] 重写方法
来源：http://dali.zhoulong.xyz/Article/details/gtgoonaglm.html

Py:   def greet(self): return "admin"
来源：http://dali.daria6918.cn/Article/details/gtdosdypai.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttumqkdbw.html

JS:   greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtgoeovssk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtuodnzhvg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtfgjbnjwh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daxiang520.top/Article/details/gtzgmfwnxr.html

Ruby: def greet; "admin"; end
来源：http://dali.ivvv.top/Article/details/gtnrfpfyzn.html

C#:   public override string Greet() => "admin";
来源：http://dali.wangshuangyany.cn/Article/details/gtmzstzjjf.html

[G07] 调用父类方法
来源：http://dali.gotoacloud.top/Article/details/gtcsiqndlq.html

Py:   super().greet()
来源：http://dali.guannengcc.top/Article/details/gtmbrorjsr.html

PHP:  parent::greet();
来源：http://dali.jyoumei.cn/Article/details/gtzmjcyclg.html

JS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gtpwrvfqbw.html

TS:   super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtbupfamtp.html

Java: super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtcfmumvdr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tanke756.top/Article/details/gteiswgdre.html

Ruby: super
来源：http://dali.shuidangran.top/Article/details/gtfbngzcjh.html

C#:   base.Greet();
来源：http://dali.bjfxy.top/Article/details/gtknbgutlg.html

[G08] 静态方法与属性
来源：http://dali.chenjidiqi.icu/Article/details/gtoxazvgfe.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.smart0.xyz/Article/details/gtrezbrvbb.html

PHP:  public static function f() {}
来源：http://dali.hywenlv.cn/Article/details/gtisuofvjt.html

JS:   static f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjcrcfhs.html

TS:   static f(): void {}
来源：http://dali.pengpengdd.cyou/Article/details/gtsqckvkpl.html

Java: static void f() {}
来源：http://dali.snrcjt.cn/Article/details/gtuqjcdcrq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.feifeiyinyue.top/Article/details/gtiguyivar.html

Ruby: def self.f; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtasurifxm.html

C#:   public static void F() {}
来源：http://dali.jqgfzy.top/Article/details/gtootjaude.html

[G09] 接口 / 抽象类
来源：http://dali.cqqwz.cn/Article/details/gtopuperbf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xylfe.cn/Article/details/gtmxznxqgz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yuanzhike.top/Article/details/gtorlsiqft.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yuanzhike.top/Article/details/gtvglfzqkn.html

TS:   interface Shape { area(): number; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gteamtijfv.html

Java: interface Shape { double area(); }
来源：http://dali.xuanzx.com/Article/details/gttlrazvez.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhixingplan.top/Article/details/gtiyrkkvcg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yonumen.top/Article/details/gttltgsjjn.html

C#:   interface IShape { double Area(); }
来源：http://dali.9152youxi.cn/Article/details/gtychqmlgm.html

[G10] 访问控制
来源：http://dali.jlsjyb.cn/Article/details/gtprhuehfd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhixingplan.top/Article/details/gtzubxfqfu.html

PHP:  public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtcznphcve.html

JS:   #private 字段；其余公开
来源：http://dali.havefunace.top/Article/details/gtdxybwfoh.html

TS:   public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gtmoyprpae.html

Java: public / protected / private / 默认包级
来源：http://dali.chenlongwang.top/Article/details/gtwueaerhk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hongshengwenyu.top/Article/details/gtfjkvjjam.html

Ruby: public / protected / private
来源：http://dali.cashguo.top/Article/details/gtyiadczoi.html

C#:   public / protected / private / internal
来源：http://dali.quarkkingdee.top/Article/details/gtjjhrwsoe.html

[G11] getter / setter
来源：http://dali.gzhubu.top/Article/details/gtvaifkpkc.html

Py:   @property 与 @x.setter
来源：http://dali.nanxinkj.top/Article/details/gtezpwechh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gtlurtvwda.html

JS:   get name() { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gtxlprpjlb.html

TS:   get name(): string { return this._name; }
来源：http://dali.dashuyun.cn/Article/details/gtumdfjtuj.html

Java: public String getName() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtvrucwtbx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtsphubtun.html

Ruby: attr_accessor :name
来源：http://dali.jinqigfzy.top/Article/details/gtlmrdfvqj.html

C#:   public string Name { get; set; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtngnuomht.html

[G12] 对象转字符串
来源：http://dali.svipenyu.cn/Article/details/gtexxqkcsb.html

Py:   def __str__(self): return self.name
来源：http://dali.zdqjudy.top/Article/details/gtpioqfhob.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gttjysrmix.html

JS:   toString() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtfuhdgesg.html

TS:   toString(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtsikjrhpd.html

Java: @Override public String toString() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtqsdgtmbd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtrngmkelx.html

Ruby: def to_s; @name; end
来源：http://dali.c1oappe.top/Article/details/gtiewndaiz.html

C#:   public override string ToString() => Name;
来源：http://dali.yueranfly.top/Article/details/gtuciqencx.html

[G13] 判断对象类型
来源：http://dali.316326.xyz/Article/details/gtahihpumc.html

Py:   isinstance(u, User)
来源：http://dali.jinqigfzy.top/Article/details/gtnsoymwgj.html

PHP:  $u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvhqaagpc.html

JS:   u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtiqbqzjac.html

TS:   u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtmhjysrou.html

Java: u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtdrezwfpy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sysykeji.top/Article/details/gtfxnjpdff.html

Ruby: u.is_a?(User)
来源：http://dali.shanyushiyangtech.top/Article/details/gtccdgporh.html

C#:   u is User
来源：http://dali.cdnleiting.top/Article/details/gtrvpsvntg.html

[G14] 数据类 / record
来源：http://dali.hysaishi.cn/Article/details/gtosohrizp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yonumen.top/Article/details/gtzbowdstq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.316326.xyz/Article/details/gttohkjxfa.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hysaishi.cn/Article/details/gtvcelohei.html

TS:   type User = { name: string; age: number };
来源：http://dali.shuidangran.top/Article/details/gtqlkcuogl.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258888.top/Article/details/gthgmwoxuy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sxryk.cn/Article/details/gtpwmodinc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.dashuyun.cn/Article/details/gtblexfdop.html

C#:   record User(string Name, int Age);
来源：http://dali.meibo888.top/Article/details/gtlwfesfdb.html

[G15] 枚举
来源：http://dali.jiagoushi.top/Article/details/gtiyipvwxj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuetiantiany.cn/Article/details/gtwucqayfh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.haohaochexian.top/Article/details/gtbnsgvbhy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zdqjudy.top/Article/details/gtlbbnmfqx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnifasvqy.html

Java: enum Color { RED, GREEN }
来源：http://dali.yonumen.top/Article/details/gtqeoqlnjl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hnqzz.top/Article/details/gtleznmxuz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.pengpengdd.cyou/Article/details/gtsmwdkgpf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gtqynidvrs.html

[G16] 对象转数组 / 字典
来源：http://dali.gogol.net.cn/Article/details/gtogbduxhw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cheryme.top/Article/details/gtemzxwmpj.html

PHP:  get_object_vars($obj);
来源：http://dali.nanxuanxn.top/Article/details/gtrszztkfi.html

JS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gtwmstlqor.html

TS:   Object.entries(obj)
来源：http://dali.birdmap.top/Article/details/gtkfllibrc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fzhhl.top/Article/details/gtzhomxqia.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sysykeji.top/Article/details/gtzmpzafan.html

Ruby: obj.instance_variables
来源：http://dali.shangyingyoupin.top/Article/details/gthqtlryfk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ehwqpu.com/Article/details/gthnvdtaar.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gthxujzzim.html

H. 异常与错误处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtalcgjcmd.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchwcbpmp.html

[H01] try / catch 基础
来源：http://dali.jqgufenzy.top/Article/details/gtivalkxkn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cucudq.cn/Article/details/gtmvjhfuyu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgfzy.top/Article/details/gtqgaligss.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gtwyiqjvvk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gotoacloud.top/Article/details/gtkxbffqvi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zdqjudy.top/Article/details/gtasllzjea.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sweek.top/Article/details/gtsuecftcz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.andypj.xyz/Article/details/gtfofobngm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhiwuduotai.top/Article/details/gtarrqawjg.html

[H02] finally / ensure 收尾
来源：http://dali.jlsjyb.cn/Article/details/gtzrjjlpmn.html


<!-- 参考信息 -->