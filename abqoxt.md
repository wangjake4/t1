代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gtpqkkbkyl.html

TS:   s.split(/\r?\n/)
来源：http://dali.svipenyu.cn/Article/details/gteleoinga.html

Java: s.lines().toList()
来源：http://dali.yuanzhike.top/Article/details/gtndmdoteg.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gtnfzdgxbd.html

Ruby: s.lines
来源：http://dali.jqgufenzy.top/Article/details/gtkpuycrkd.html

C#:   s.Split('\n')
来源：http://dali.jinqigfzy.top/Article/details/gtmeyjzkaa.html

[E20] 判断字符串是否为空
来源：http://dali.jlsjyb.cn/Article/details/gttgfstwon.html

Py:   if not s:
来源：http://dali.mhx1999.top/Article/details/gtunicyhqj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ppjwa.cn/Article/details/gtjrampesf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jiagoushi.top/Article/details/gtoxtxsoqa.html

TS:   if (s === "") {}
来源：http://dali.ydzc1.top/Article/details/gtwivlqvkb.html

Java: if (s.isEmpty()) {}
来源：http://dali.birdmap.top/Article/details/gtojghpkxd.html

Go:   if s == "" {}
来源：http://dali.jiagoushi.top/Article/details/gtxkqsjrbp.html

Ruby: if s.empty?
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjnzbkuau.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ivvv.top/Article/details/gtzpwdactb.html

[E21] 超长截断加省略号
来源：http://dali.yj20258888.top/Article/details/gtiquygpbs.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hongshengwenyu.top/Article/details/gtmaxisqfw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtzaatrjdt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gtvgeyjvuc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtglrdvsyg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtwydyfosv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.kuanghao11.cn/Article/details/gteottypyv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtfelpaffn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtjdqkfwav.html

[E22] 字节长度与字符长度
来源：http://dali.cucudq.cn/Article/details/gtwgpyzpnd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tanke756.top/Article/details/gttgijykba.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gtxtdajurp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gtknnvyidr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gtkvfdgldn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.birdmap.top/Article/details/gtnjypqiww.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.quarkkingdee.top/Article/details/gtuozppazp.html

Ruby: s.bytesize;  s.length
来源：http://dali.pycfn.com/Article/details/gtxqlbtrwz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.vqdsnc.cn/Article/details/gtdnisrhnv.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtmitmtqkj.html

F. 文件与目录
来源：http://dali.hammf.cn/Article/details/gtnpkdrhor.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtnlozfqnv.html

[F01] 读取整个文件
来源：http://dali.9152youxi.cn/Article/details/gtqdsvxhqd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tanke756.top/Article/details/gtlrfslpyd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtkbwcwycc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gaohongyu789.top/Article/details/gtyqxxvsxm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangdashe.top/Article/details/gtfifoczrp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtvappfyld.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenzaomai.com/Article/details/gtznqmifbu.html

Ruby: File.read("a.txt")
来源：http://dali.yongpay.top/Article/details/gtqsheybdf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtfxxdfurh.html

[F02] 逐行读取文件
来源：http://dali.jqgfzy.top/Article/details/gtdqxkpfua.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.mhx1999.top/Article/details/gtyczixucx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.316326.xyz/Article/details/gtcquwfiuc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gtumcsholh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.snrcjt.cn/Article/details/gtgqowydgy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj20258888.top/Article/details/gtvoyqtdna.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hfpthk.cn/Article/details/gtfazrouha.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cheryme.top/Article/details/gtavhibdly.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ehwqpu.com/Article/details/gtjsfaefoe.html

[F03] 写入文件（覆盖）
来源：http://dali.hongshengwenyu.top/Article/details/gtmmorwvch.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shangyingyoupin.top/Article/details/gtcnyjbdva.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.wangdashe.top/Article/details/gtnsqxmnbx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gtbaczfwvn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gthjepozmw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jiagoushi.top/Article/details/gtwkhaqkgq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.birdmap.top/Article/details/gtxywafknn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zycfv.cn/Article/details/gtvdajtcec.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jlsjyb.cn/Article/details/gtlfmpubeh.html

[F04] 追加写入文件
来源：http://dali.birdmap.top/Article/details/gtibekwrku.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpfuuwfzw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gthswuwzam.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hywenlv.cn/Article/details/gtdhexukto.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenzaomai.com/Article/details/gtwjmvncyy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangdashe.top/Article/details/gtqracodag.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtbpmdwjjq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrcnoazgh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.snrcjt.cn/Article/details/gtlhjpnauf.html

[F05] 判断文件或目录是否存在
来源：http://dali.birdmap.top/Article/details/gtiatshcor.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ybcxt.top/Article/details/gtvwkpgtpg.html

PHP:  file_exists("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzwkxarqh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtuukantua.html

TS:   fs.existsSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtimtezqxp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtcejboajy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xuetiantiany.cn/Article/details/gtlftingqc.html

Ruby: File.exist?("a.txt")
来源：http://dali.c1oappe.top/Article/details/gttyvzdead.html

C#:   File.Exists("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehigiyhz.html

[F06] 删除文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtylgcwfwb.html

Py:   os.remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gtlkkenwqf.html

PHP:  unlink("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtgaydwngo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtbdfbdrii.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtuzdxwimj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtojgjdcju.html

Go:   os.Remove("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtgfyaluog.html

Ruby: File.delete("a.txt")
来源：http://dali.zycfv.cn/Article/details/gttkcwavzp.html

C#:   File.Delete("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwafrwgd.html

[F07] 创建目录（含多级）
来源：http://dali.yj20258888.top/Article/details/gtawfjjcvs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gogol.net.cn/Article/details/gtxpfoerhz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.redwolf501.top/Article/details/gtfnnwbxlt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gtameemmlc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenzaomai.com/Article/details/gtzllxxrdn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.9152youxi.cn/Article/details/gtgyzsabin.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.wangshuangyany.cn/Article/details/gtieuxvzev.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yanxiufei.cn/Article/details/gtheswrxyc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.fengsongda.top/Article/details/gtobmwszds.html

[F08] 遍历目录
来源：http://dali.pengpengdd.cyou/Article/details/gtlcocsons.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cheryme.top/Article/details/gtlmpazfzf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.redwolf501.top/Article/details/gtvicijobl.html

JS:   fs.readdirSync("dir")
来源：http://dali.hywenlv.cn/Article/details/gtazqvbkpa.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtypehwbsi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gtdbgkneww.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hfpthk.cn/Article/details/gteqylhiki.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigufen.top/Article/details/gtxavjnhiy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigufen.top/Article/details/gtmoeqnamh.html

[F09] 获取文件大小
来源：http://dali.gaohongyu789.top/Article/details/gtelrjaxcl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtdomxwvey.html

PHP:  filesize("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtsujfjmxb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhongyouzk.top/Article/details/gtgnnhlkrz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gtnlyamhuv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtvimcwoce.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shzxlz.cn/Article/details/gtliofufoc.html

Ruby: File.size("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtxisadyxl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuanzhike.top/Article/details/gtrgtccddx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fengsongda.top/Article/details/gtgujfizbj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtzfcsqkfc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtjioduijs.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtyzlaeugi.html

TS:   path.extname("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtmosnvdhw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenjidiqi.icu/Article/details/gtdkliehbp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtsmivvega.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtellzvrmj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxlrbaqf.html

[F11] 复制与移动文件
来源：http://dali.snrcjt.cn/Article/details/gthkvfgxqy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtyxjmhywk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cashguo.top/Article/details/gtrrjdhzvi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtsurdqlcr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtnpmbhfpr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.iojbl.cn/Article/details/gtkhfgaouh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sufxvd.cn/Article/details/gtdccyxhaj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtnjftjuwf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvcuuzhkx.html

[F12] CSV 读写
来源：http://dali.fzhhl.top/Article/details/gtdcqotcff.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinqigfzy.top/Article/details/gtamdnavpo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xinyue.icu/Article/details/gtqfycazfy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.redwolf501.top/Article/details/gtoelwodrp.html

TS:   // 同上
来源：http://dali.wangdashe.top/Article/details/gtrejoioeg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.quarkkingdee.top/Article/details/gtempstftq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigfzy.top/Article/details/gthmapjqod.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ehwqpu.com/Article/details/gtewpoisfy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ppjwa.cn/Article/details/gtsuoquddb.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtdrdwwjre.html

G. 面向对象
来源：http://dali.hongshengwenyu.top/Article/details/gtlmuswltq.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtgtnvcruy.html

[G01] 定义类
来源：http://dali.redwolf501.top/Article/details/gtqiylgcct.html

Py:   class User: pass
来源：http://dali.hongshengwenyu.top/Article/details/gtebkeushq.html

PHP:  class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtznuxuaki.html

JS:   class User {}
来源：http://dali.jianghu66.top/Article/details/gthzpnrqsz.html

TS:   class User { name: string = ""; }
来源：http://dali.zycfv.cn/Article/details/gtflamftdb.html

Java: class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtpbclrsaj.html

Go:   type User struct { Name string }
来源：http://dali.snrcjt.cn/Article/details/gthzpuvczj.html

Ruby: class User; end
来源：http://dali.fengsongda.top/Article/details/gtsnhnoakp.html

C#:   class User {}
来源：http://dali.tian-w.cn/Article/details/gtkgkyakgk.html

[G02] 构造函数
来源：http://dali.nwbrower.top/Article/details/gttnvqaeru.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.mhx1999.top/Article/details/gtkfogshmk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.havefunace.top/Article/details/gtmfoccrqq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gtdtmsindd.html

TS:   constructor(public name: string) {}
来源：http://dali.0kj1m.cn/Article/details/gtlruxsjyz.html

Java: User(String name) { this.name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gteaykwkuh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.quarkkingdee.top/Article/details/gtqioohfya.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxuanxn.top/Article/details/gtmmyhyhiw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.andypj.xyz/Article/details/gtdqrqxaxf.html

[G03] 实例属性
来源：http://dali.cashguo.top/Article/details/gtkvvrcahw.html

Py:   self.name = "x"
来源：http://dali.daxiang520.top/Article/details/gtpoeawmug.html

PHP:  public string $name = "x";
来源：http://dali.pycfn.com/Article/details/gtcsdwtvnl.html

JS:   this.name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtsmxzwkgt.html

TS:   name: string = "x";
来源：http://dali.iojbl.cn/Article/details/gtovaugeid.html

Java: private String name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwyakrznm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.iojbl.cn/Article/details/gtejmwtwfo.html

Ruby: @name = "x"
来源：http://dali.yuanzhike.top/Article/details/gtcvhwzamv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guannengcc.top/Article/details/gthwuilisi.html

[G04] 定义方法
来源：http://dali.gotoacloud.top/Article/details/gtbvxbgfam.html

Py:   def greet(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgckxgqc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtgnjniqrv.html

JS:   greet() { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtstlhtqep.html

TS:   greet(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtxljkhjoi.html

Java: String greet() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtdopbqdaj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtomeydkzj.html

Ruby: def greet; @name; end
来源：http://dali.jiagoushi.top/Article/details/gttsqlaacz.html

C#:   public string Greet() => Name;
来源：http://dali.hywenlv.cn/Article/details/gtxsvfxjxi.html

[G05] 继承
来源：http://dali.jiagoushi.top/Article/details/gtbolpdkeq.html

Py:   class Admin(User): pass
来源：http://dali.shzxlz.cn/Article/details/gtfbcgacra.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtleozobnk.html

JS:   class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtkbynysqe.html

TS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtghufondy.html

Java: class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtdkrpbtjp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hysaishi.cn/Article/details/gtqnmflwqw.html

Ruby: class Admin < User; end
来源：http://dali.cucudq.cn/Article/details/gtyqkipsss.html

C#:   class Admin : User {}
来源：http://dali.nwbrower.top/Article/details/gteibtiswb.html

[G06] 重写方法
来源：http://dali.dianchejie.cn/Article/details/gtajzinmli.html

Py:   def greet(self): return "admin"
来源：http://dali.redwolf501.top/Article/details/gtotdnudqh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtemcxqrgv.html

JS:   greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtsbfxppqd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtlawloxpb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtnywgktzr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sxryk.cn/Article/details/gtoazwpynw.html

Ruby: def greet; "admin"; end
来源：http://dali.hnqzz.top/Article/details/gtgfqbpksn.html

C#:   public override string Greet() => "admin";
来源：http://dali.hywenlv.cn/Article/details/gtoapsjrze.html

[G07] 调用父类方法
来源：http://dali.iojbl.cn/Article/details/gtsujhbbwg.html

Py:   super().greet()
来源：http://dali.sufxvd.cn/Article/details/gtipprylfr.html

PHP:  parent::greet();
来源：http://dali.zhengqikj.top/Article/details/gtlcskcpia.html

JS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gtgteuukxz.html

TS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtpxhqsqhm.html

Java: super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gtnztvdovk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.bjfxy.top/Article/details/gtnyfjjwtx.html

Ruby: super
来源：http://dali.fengsongda.top/Article/details/gtuivhvtgk.html

C#:   base.Greet();
来源：http://dali.nanxuanxn.top/Article/details/gtoyechdqd.html

[G08] 静态方法与属性
来源：http://dali.xylfe.cn/Article/details/gtmgtsdqgh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.aibaodan.cn/Article/details/gtwpbytgvh.html

PHP:  public static function f() {}
来源：http://dali.tian-w.cn/Article/details/gtswckulqu.html

JS:   static f() {}
来源：http://dali.wangdashe.top/Article/details/gtktgwvmpp.html

TS:   static f(): void {}
来源：http://dali.chenzaomai.com/Article/details/gtqrtmjsle.html

Java: static void f() {}
来源：http://dali.aizwys.cn/Article/details/gtfeyqprqp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhoulong.xyz/Article/details/gtjcafgeyq.html

Ruby: def self.f; end
来源：http://dali.tian-w.cn/Article/details/gtcgvkjcnl.html

C#:   public static void F() {}
来源：http://dali.bjfxy.top/Article/details/gturkqgrvb.html

[G09] 接口 / 抽象类
来源：http://dali.ybcxt.top/Article/details/gtlksbruvj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gotoacloud.top/Article/details/gtexgogprg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ybcxt.top/Article/details/gtqmeztnjq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ybcxt.top/Article/details/gtwjmaeuhi.html

TS:   interface Shape { area(): number; }
来源：http://dali.sweek.top/Article/details/gtxmtmiyrb.html

Java: interface Shape { double area(); }
来源：http://dali.nwbrower.top/Article/details/gtwqxyzuyb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.bjfxy.top/Article/details/gteuocadsl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwphvlqws.html

C#:   interface IShape { double Area(); }
来源：http://dali.sxryk.cn/Article/details/gthtyiztpn.html

[G10] 访问控制
来源：http://dali.xziqi.cn/Article/details/gtwhlxmuyu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhongyouzk.top/Article/details/gtmgfzydtn.html

PHP:  public / protected / private
来源：http://dali.redwolf501.top/Article/details/gtcyegwnqd.html

JS:   #private 字段；其余公开
来源：http://dali.dashuyun.cn/Article/details/gtoptrazvr.html

TS:   public / protected / private
来源：http://dali.yj20258888.top/Article/details/gteynzlqcq.html

Java: public / protected / private / 默认包级
来源：http://dali.nwbrower.top/Article/details/gtevhmkakf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhoulong.xyz/Article/details/gtjkinzjvj.html

Ruby: public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gtbpryhpxg.html

C#:   public / protected / private / internal
来源：http://dali.yangfankeji.com/Article/details/gtvhmgmiue.html

[G11] getter / setter
来源：http://dali.kuanghao11.cn/Article/details/gthycftxkz.html

Py:   @property 与 @x.setter
来源：http://dali.dianchejie.cn/Article/details/gtuyzluaci.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtzfmzaxff.html

JS:   get name() { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtbpfxkons.html

TS:   get name(): string { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtlhrszewy.html

Java: public String getName() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtngsvuktb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtgvqqznhs.html

Ruby: attr_accessor :name
来源：http://dali.9152youxi.cn/Article/details/gtmoklsdga.html

C#:   public string Name { get; set; }
来源：http://dali.xuanzx.com/Article/details/gtnebmvuxn.html

[G12] 对象转字符串
来源：http://dali.ppjwa.cn/Article/details/gtrzmnqnhz.html

Py:   def __str__(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gtnzhbjnkw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gtqtmuijqk.html

JS:   toString() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtlaerphty.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtlwxkzlae.html

Java: @Override public String toString() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtderxelzc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gtdwtntydj.html

Ruby: def to_s; @name; end
来源：http://dali.iojbl.cn/Article/details/gtmfwzhrce.html

C#:   public override string ToString() => Name;
来源：http://dali.cashguo.top/Article/details/gtqfxqafvp.html

[G13] 判断对象类型
来源：http://dali.9152youxi.cn/Article/details/gtqxilcrln.html

Py:   isinstance(u, User)
来源：http://dali.haohaochexian.top/Article/details/gtegdljvta.html

PHP:  $u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtqekglmtf.html

JS:   u instanceof User
来源：http://dali.pycfn.com/Article/details/gtleyltdbm.html

TS:   u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtjmlslqqc.html

Java: u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtuainkjyv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigfzy.top/Article/details/gtcbyptruj.html

Ruby: u.is_a?(User)
来源：http://dali.havefunace.top/Article/details/gtlpeswioc.html

C#:   u is User
来源：http://dali.daxiang520.top/Article/details/gtfuqripcm.html

[G14] 数据类 / record
来源：http://dali.xylfe.cn/Article/details/gtbhpxfugw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cdnleiting.top/Article/details/gthhjunbop.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xylfe.cn/Article/details/gtrunyyuxi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.andypj.xyz/Article/details/gtprkpfnmn.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiyotglur.html

Java: record User(String name, int age) {}
来源：http://dali.mhx1999.top/Article/details/gtljgfzskh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dashuyun.cn/Article/details/gtnbknqhkk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhongyouzk.top/Article/details/gtgzpezlcm.html

C#:   record User(string Name, int Age);
来源：http://dali.ehwqpu.com/Article/details/gtcqcjwxjn.html

[G15] 枚举
来源：http://dali.yangfankeji.com/Article/details/gtkumepbyx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuetiantiany.cn/Article/details/gtjwcigppt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.redwolf501.top/Article/details/gtjkkrqewe.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuanzhike.top/Article/details/gtwiainoor.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuanzx.com/Article/details/gtnhkaonpk.html

Java: enum Color { RED, GREEN }
来源：http://dali.ppjwa.cn/Article/details/gtmcokodnp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdttopcvn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjasabxhx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fzhhl.top/Article/details/gtycwstmmr.html

[G16] 对象转数组 / 字典
来源：http://dali.yvedp.cn/Article/details/gtiurhvmct.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhiwuduotai.top/Article/details/gtkyrntnll.html

PHP:  get_object_vars($obj);
来源：http://dali.gotoacloud.top/Article/details/gtksvlnqre.html

JS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gtonwceuxn.html

TS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gtvesmjcbh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.pycfn.com/Article/details/gtqdqftbbb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cqqwz.cn/Article/details/gthmxzhkcg.html

Ruby: obj.instance_variables
来源：http://dali.aizwys.cn/Article/details/gtfgludeej.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuanzx.com/Article/details/gtbmzmxysz.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtcnzzynhz.html

H. 异常与错误处理
来源：http://dali.pycfn.com/Article/details/gtpzmaxuxf.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtcxbxhdji.html

[H01] try / catch 基础
来源：http://dali.tianlin.xyz/Article/details/gtpxaszaqh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.wangdashe.top/Article/details/gtwdjfacim.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.dianchejie.cn/Article/details/gtygyotscm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gtjvgzmkfe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gtpmxkqbfd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nanxinkj.top/Article/details/gtkeebcifw.html


<!-- 参考信息 -->