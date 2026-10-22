代发 wailian999

Ruby: s.lines
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrptwpsht.html

C#:   s.Split('\n')
来源：http://dali.birdmap.top/Article/details/gtlmgkiigs.html

[E20] 判断字符串是否为空
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwxzishvx.html

Py:   if not s:
来源：http://dali.yuanzhike.top/Article/details/gtyzzjhoyp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hammf.cn/Article/details/gtdbqbwqkx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtejmzsriq.html

TS:   if (s === "") {}
来源：http://dali.sxryk.cn/Article/details/gtgqejcukz.html

Java: if (s.isEmpty()) {}
来源：http://dali.tanke756.top/Article/details/gtbajgultq.html

Go:   if s == "" {}
来源：http://dali.nanxinkj.top/Article/details/gtcjmgeqzc.html

Ruby: if s.empty?
来源：http://dali.havefunace.top/Article/details/gtsofjwvqm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shzxlz.cn/Article/details/gtnbqpxcde.html

[E21] 超长截断加省略号
来源：http://dali.tanke756.top/Article/details/gtsnzglkus.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhoulong.xyz/Article/details/gtetucxbey.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gtgjmgektt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gttvtwbduh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtfdwglddo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gtijiocvdc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ivvv.top/Article/details/gtjzmczoti.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtymovtuul.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtapvumfsv.html

[E22] 字节长度与字符长度
来源：http://dali.hnxiangtu.top/Article/details/gthzaqxgta.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sxryk.cn/Article/details/gtgkvhkltq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtckmzuwhz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sysykeji.top/Article/details/gtuthturkh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gogol.net.cn/Article/details/gtwamyyelz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.daria6918.cn/Article/details/gtqpfqryyv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pycfn.com/Article/details/gtnvdccwqa.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtjfiblnkf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhixingplan.top/Article/details/gtvaguvppg.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtkzzdeadx.html

F. 文件与目录
来源：http://dali.fengsongda.top/Article/details/gtjvqkdvnq.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtqmjjihga.html

[F01] 读取整个文件
来源：http://dali.bjfxy.top/Article/details/gtjkdgxebs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ehwqpu.com/Article/details/gtkyyrpxpw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtznzftoyq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinghuilouyu.cn/Article/details/gtyfqdpcit.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sweek.top/Article/details/gtfefnvtux.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtvyabjxlm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xziqi.cn/Article/details/gtbavpkrct.html

Ruby: File.read("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtikjhizaa.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtqmlqhlek.html

[F02] 逐行读取文件
来源：http://dali.aibaodan.cn/Article/details/gtjuuvqysk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj20258.top/Article/details/gttasyktvi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuetiantiany.cn/Article/details/gtwddwonvx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jiagoushi.top/Article/details/gtvrwjefre.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuanzx.com/Article/details/gtoiqqlbwg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pycfn.com/Article/details/gtnduazogc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tanke756.top/Article/details/gtukvmjvbo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cucudq.cn/Article/details/gtlieyhxmz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.316326.xyz/Article/details/gtvprymflc.html

[F03] 写入文件（覆盖）
来源：http://dali.svipenyu.cn/Article/details/gtoksodaue.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtlejafvuw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gtfgxxvnvq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gtdfeshlys.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cucudq.cn/Article/details/gtjybgijhf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jianghu66.top/Article/details/gtwqpzjxbk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shangyingyoupin.top/Article/details/gthkhikwot.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtygkqghsj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gtxihewszu.html

[F04] 追加写入文件
来源：http://dali.jyoumei.cn/Article/details/gtnwuqetme.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yuxming.cn/Article/details/gtkpvmxoor.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gaohongyu789.top/Article/details/gtoulylzhz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gtdlkufqwa.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shzxlz.cn/Article/details/gtojvvuzen.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ydzc1.top/Article/details/gtuoxnarjb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtghuktenh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.iojbl.cn/Article/details/gtfkotjrps.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnxiangtu.top/Article/details/gtudlnjpss.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtkaakyfhx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sxryk.cn/Article/details/gtmgomlxgb.html

PHP:  file_exists("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmklsqpf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtcjaksbkr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtunbljzax.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtifonfsbj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gaohongyu789.top/Article/details/gtfhuexses.html

Ruby: File.exist?("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtjruxqjjw.html

C#:   File.Exists("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtymtpwqce.html

[F06] 删除文件
来源：http://dali.haohaochexian.top/Article/details/gtiwpbozfb.html

Py:   os.remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gthcalolhd.html

PHP:  unlink("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtorwwvmzp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtlgchqscw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtjtbknrqp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gtkadtuilr.html

Go:   os.Remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtpjnkvjtf.html

Ruby: File.delete("a.txt")
来源：http://dali.yj20258.top/Article/details/gtgknygjjj.html

C#:   File.Delete("a.txt");
来源：http://dali.yonumen.top/Article/details/gthxebblvb.html

[F07] 创建目录（含多级）
来源：http://dali.jinghuilouyu.cn/Article/details/gtrqqurwso.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhengqikj.top/Article/details/gtegzfnsel.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xziqi.cn/Article/details/gtxhqvdnuh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gttzfcsowg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.havefunace.top/Article/details/gtjvjqpkxx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shangyingyoupin.top/Article/details/gthyyuaffj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hnxiangtu.top/Article/details/gtrrqkyvzs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jqgufenzy.top/Article/details/gtfjczpvwu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.mhx1999.top/Article/details/gtbanncdne.html

[F08] 遍历目录
来源：http://dali.cucudq.cn/Article/details/gttsnyvogh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.quarkkingdee.top/Article/details/gthqxtndql.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xinyue.icu/Article/details/gtcuiicgcu.html

JS:   fs.readdirSync("dir")
来源：http://dali.gzhubu.top/Article/details/gtwbauhynf.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtmpojcdlj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gtcedzvaem.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guannengcc.top/Article/details/gtepilgoef.html

Ruby: Dir.children("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtieljlpqc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ppjwa.cn/Article/details/gtczyzybpb.html

[F09] 获取文件大小
来源：http://dali.cdnleiting.top/Article/details/gtopbhwhhp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtoxgquswc.html

PHP:  filesize("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtkfxinekj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gotoacloud.top/Article/details/gtyonnuhzp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.dashuyun.cn/Article/details/gtyxkcbubx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtaxysjqwz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guowangkeji.top/Article/details/gtbmxjvzoy.html

Ruby: File.size("a.txt")
来源：http://dali.sweek.top/Article/details/gtvcapsyko.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cqqwz.cn/Article/details/gtnashsrfu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnqzz.top/Article/details/gtewtfpzcv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtuhuusrit.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gteuunksut.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtcldwrxzp.html

TS:   path.extname("a.txt")
来源：http://dali.sweek.top/Article/details/gtfetuwbnx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hongshengwenyu.top/Article/details/gtebjyqeoc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtccdsbxth.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtkkdlkskv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gttuhqyigo.html

[F11] 复制与移动文件
来源：http://dali.nanxuanxn.top/Article/details/gttopcukel.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtupvzyrkq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yonumen.top/Article/details/gtykfoyioz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtaibwlkuk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtjsywxbho.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj202588.top/Article/details/gtnybqmpif.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shuidangran.top/Article/details/gtvtewzlrs.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtucvdqxbw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhoulong.xyz/Article/details/gtfkccsiqc.html

[F12] CSV 读写
来源：http://dali.tianlin.xyz/Article/details/gtvfpbnrjz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hnxiangtu.top/Article/details/gtkgtnsmpg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhoulong.xyz/Article/details/gtggdtpbzv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxuanxn.top/Article/details/gticzidlmw.html

TS:   // 同上
来源：http://dali.yuxming.cn/Article/details/gtsbaegxpi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nanxinkj.top/Article/details/gtqhnykzsr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hysaishi.cn/Article/details/gtrdogiiwe.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.0kj1m.cn/Article/details/gtgtgmhmaj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cheryme.top/Article/details/gthxdnbpew.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtkvanmzxp.html

G. 面向对象
来源：http://dali.ivvv.top/Article/details/gthpkmevxs.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtanwykheu.html

[G01] 定义类
来源：http://dali.hywenlv.cn/Article/details/gttcmmykov.html

Py:   class User: pass
来源：http://dali.shangyingyoupin.top/Article/details/gtfqmnlnrz.html

PHP:  class User {}
来源：http://dali.shzxlz.cn/Article/details/gtpjipdmnx.html

JS:   class User {}
来源：http://dali.jianghu66.top/Article/details/gturxuysov.html

TS:   class User { name: string = ""; }
来源：http://dali.haohaochexian.top/Article/details/gtppxiyyab.html

Java: class User {}
来源：http://dali.jyoumei.cn/Article/details/gtrckcimcn.html

Go:   type User struct { Name string }
来源：http://dali.ppjwa.cn/Article/details/gttadqwwzq.html

Ruby: class User; end
来源：http://dali.meibo888.top/Article/details/gtuhbnycek.html

C#:   class User {}
来源：http://dali.zhengqikj.top/Article/details/gtokurjwwc.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gtmtfsolme.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.andypj.xyz/Article/details/gtxnqwbdxe.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jyoumei.cn/Article/details/gtlxkkvtrw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gttbgswjrz.html

TS:   constructor(public name: string) {}
来源：http://dali.zhiwuduotai.top/Article/details/gthatnbhdy.html

Java: User(String name) { this.name = name; }
来源：http://dali.sxryk.cn/Article/details/gtlgvgfzyy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.iojbl.cn/Article/details/gtgzllgxpf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxinkj.top/Article/details/gtesluetwu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtgqcxpecc.html

[G03] 实例属性
来源：http://dali.cashguo.top/Article/details/gtigkqorgs.html

Py:   self.name = "x"
来源：http://dali.ivvv.top/Article/details/gtjuuvbzoq.html

PHP:  public string $name = "x";
来源：http://dali.316326.xyz/Article/details/gtycghfmic.html

JS:   this.name = "x";
来源：http://dali.c1oappe.top/Article/details/gtwootdbvy.html

TS:   name: string = "x";
来源：http://dali.yueranfly.top/Article/details/gtujnogkjc.html

Java: private String name;
来源：http://dali.yueranfly.top/Article/details/gtnabuhcvw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daria6918.cn/Article/details/gtereriqum.html

Ruby: @name = "x"
来源：http://dali.zhaomingkeji.xyz/Article/details/gthprxpwre.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.meibo888.top/Article/details/gtfvtpjvhj.html

[G04] 定义方法
来源：http://dali.hywenlv.cn/Article/details/gtlddibquj.html

Py:   def greet(self): return self.name
来源：http://dali.yueranfly.top/Article/details/gtconzxshb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtknvwwjus.html

JS:   greet() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtwvbdamap.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtsawsngzd.html

Java: String greet() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtqmslzpjn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gttzdjwzdg.html

Ruby: def greet; @name; end
来源：http://dali.dianchejie.cn/Article/details/gtbffftqvp.html

C#:   public string Greet() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gtvhhvpbzm.html

[G05] 继承
来源：http://dali.mhx1999.top/Article/details/gtwjdpcucm.html

Py:   class Admin(User): pass
来源：http://dali.haohaochexian.top/Article/details/gtfigpleqb.html

PHP:  class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtjpaxylxa.html

JS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtkvbvtqna.html

TS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtamzonzsj.html

Java: class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtngyxtccy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.smart0.xyz/Article/details/gtjvmbylij.html

Ruby: class Admin < User; end
来源：http://dali.jinqigufen.top/Article/details/gtoxobisjy.html

C#:   class Admin : User {}
来源：http://dali.yanxiufei.cn/Article/details/gtqmydoeky.html

[G06] 重写方法
来源：http://dali.aibaodan.cn/Article/details/gttycwzlng.html

Py:   def greet(self): return "admin"
来源：http://dali.yangfankeji.com/Article/details/gtcdavwolj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtlhihxptq.html

JS:   greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtmmdhwvxy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtlcqwgspi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtcpfqfnih.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.smart0.xyz/Article/details/gtecrmcezp.html

Ruby: def greet; "admin"; end
来源：http://dali.cucudq.cn/Article/details/gtlxayelpr.html

C#:   public override string Greet() => "admin";
来源：http://dali.xziqi.cn/Article/details/gtjmubwzjg.html

[G07] 调用父类方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtfbfwwbbl.html

Py:   super().greet()
来源：http://dali.zhiwuduotai.top/Article/details/gtlyhdnphx.html

PHP:  parent::greet();
来源：http://dali.ivvv.top/Article/details/gtsqqdpupm.html

JS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtbmmddhkv.html

TS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtiqocftpd.html

Java: super.greet();
来源：http://dali.cheryme.top/Article/details/gthqmafdek.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhoulong.xyz/Article/details/gtbcwexsmd.html

Ruby: super
来源：http://dali.yonumen.top/Article/details/gtomlbupei.html

C#:   base.Greet();
来源：http://dali.yvedp.cn/Article/details/gtmpnffpzp.html

[G08] 静态方法与属性
来源：http://dali.vqdsnc.cn/Article/details/gtjjwgdemz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.snrcjt.cn/Article/details/gtsyocqsbc.html

PHP:  public static function f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtaegmakdg.html

JS:   static f() {}
来源：http://dali.zdqjudy.top/Article/details/gtnkktdael.html

TS:   static f(): void {}
来源：http://dali.dianchejie.cn/Article/details/gtexomjefi.html

Java: static void f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtvhylmxme.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhysxeuj.html

Ruby: def self.f; end
来源：http://dali.ivvv.top/Article/details/gtshvgegog.html

C#:   public static void F() {}
来源：http://dali.tanke756.top/Article/details/gturppokoh.html

[G09] 接口 / 抽象类
来源：http://dali.pengpengdd.cyou/Article/details/gtzqhxgdpr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.c1oappe.top/Article/details/gttjvsyxzm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guowangkeji.top/Article/details/gtkdawbfuh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cqqwz.cn/Article/details/gtkmanmede.html

TS:   interface Shape { area(): number; }
来源：http://dali.yongpay.top/Article/details/gtshacdvlw.html

Java: interface Shape { double area(); }
来源：http://dali.chenlongwang.top/Article/details/gtrjkxarub.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258888.top/Article/details/gttoasirjj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gtqhrzgzar.html

C#:   interface IShape { double Area(); }
来源：http://dali.hammf.cn/Article/details/gtwknrhswj.html

[G10] 访问控制
来源：http://dali.iojbl.cn/Article/details/gtfmadzers.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jiagoushi.top/Article/details/gtbzrmrsli.html

PHP:  public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gthsppgvej.html

JS:   #private 字段；其余公开
来源：http://dali.havefunace.top/Article/details/gtlvgjwbsm.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gtvmriswlx.html

Java: public / protected / private / 默认包级
来源：http://dali.nanxinkj.top/Article/details/gtlzqyfciu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sweek.top/Article/details/gtcunguvmt.html

Ruby: public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtmopvyemk.html

C#:   public / protected / private / internal
来源：http://dali.jinqigfzy.top/Article/details/gtbsvvmbra.html

[G11] getter / setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxoicifiv.html

Py:   @property 与 @x.setter
来源：http://dali.9152youxi.cn/Article/details/gtnmussdau.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtrfhwlmpm.html

JS:   get name() { return this._name; }
来源：http://dali.cheryme.top/Article/details/gtohqutfwx.html

TS:   get name(): string { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gtiurjqgjt.html

Java: public String getName() { return name; }
来源：http://dali.fengsongda.top/Article/details/gtbtpkdlxo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gtjenmcopd.html

Ruby: attr_accessor :name
来源：http://dali.cheryme.top/Article/details/gtfefdwklo.html

C#:   public string Name { get; set; }
来源：http://dali.cashguo.top/Article/details/gthdutozfq.html

[G12] 对象转字符串
来源：http://dali.tianlin.xyz/Article/details/gtdsreesou.html

Py:   def __str__(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gtggoxqfza.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gtbccpnnhr.html

JS:   toString() { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtacsxoxvx.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtwdpixkwz.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtrrysflkf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gtxhpunsqz.html

Ruby: def to_s; @name; end
来源：http://dali.jiagoushi.top/Article/details/gtfgynewku.html

C#:   public override string ToString() => Name;
来源：http://dali.daxiang520.top/Article/details/gtzxlwxnjr.html

[G13] 判断对象类型
来源：http://dali.pycfn.com/Article/details/gthaxmbibg.html

Py:   isinstance(u, User)
来源：http://dali.gotoacloud.top/Article/details/gtziuyvpfd.html

PHP:  $u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtvmaxfbkl.html

JS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtghoqfbwm.html

TS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtdlizvidw.html

Java: u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtbbbrqyuh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.haohaochexian.top/Article/details/gtmhwxfkxl.html

Ruby: u.is_a?(User)
来源：http://dali.yanxiufei.cn/Article/details/gtovxjuuoy.html

C#:   u is User
来源：http://dali.chenlongwang.top/Article/details/gtcdmpykfz.html

[G14] 数据类 / record
来源：http://dali.xylfe.cn/Article/details/gtpzplagox.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigufen.top/Article/details/gtqyqsrzod.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jiagoushi.top/Article/details/gtzfbxamss.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.vqdsnc.cn/Article/details/gtqpxvjzgl.html

TS:   type User = { name: string; age: number };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhcraorz.html

Java: record User(String name, int age) {}
来源：http://dali.yuxming.cn/Article/details/gtoxzdmtza.html

Go:   type User struct { Name string; Age int }
来源：http://dali.iojbl.cn/Article/details/gtwlgwfgsx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tianlin.xyz/Article/details/gtsyzmdusq.html

C#:   record User(string Name, int Age);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvgzsfqnz.html

[G15] 枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffxffmch.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.daxiang520.top/Article/details/gtzyhiycwi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gzhubu.top/Article/details/gtxgqjdamn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvvgorzi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gtziupfzky.html

Java: enum Color { RED, GREEN }
来源：http://dali.sxryk.cn/Article/details/gtpaqgqely.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhiwuduotai.top/Article/details/gtgtytztmc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.9152youxi.cn/Article/details/gtchtldmnb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gtmmfbevbk.html

[G16] 对象转数组 / 字典
来源：http://dali.0kj1m.cn/Article/details/gtetjcsurs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinghuilouyu.cn/Article/details/gtetwxksws.html

PHP:  get_object_vars($obj);
来源：http://dali.hnqzz.top/Article/details/gtazozxicm.html

JS:   Object.entries(obj)
来源：http://dali.jyoumei.cn/Article/details/gtmsxddcmu.html

TS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gtvfhhaegz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aibaodan.cn/Article/details/gthlxfatll.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtprkcoyuq.html

Ruby: obj.instance_variables
来源：http://dali.birdmap.top/Article/details/gtvmemgwad.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gtejrtvuxm.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtvoadlguf.html

H. 异常与错误处理
来源：http://dali.xuanzx.com/Article/details/gttovoebpv.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gthffadxos.html

[H01] try / catch 基础
来源：http://dali.yangfankeji.com/Article/details/gtpxzjihxd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.0kj1m.cn/Article/details/gtqormrxsu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hammf.cn/Article/details/gtawvtjwrs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gtuwtfvvuv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtqxixlayp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gtbavvpnox.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhixingplan.top/Article/details/gtsqcsxvkv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.9152youxi.cn/Article/details/gtgteglldi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aizwys.cn/Article/details/gtufsaxeic.html

[H02] finally / ensure 收尾
来源：http://dali.tian-w.cn/Article/details/gtyiulwyss.html


<!-- 参考信息 -->