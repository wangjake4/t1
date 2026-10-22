代发 wailian999

Ruby: s.lines
来源：http://dali.sxryk.cn/Article/details/gtvkuomhws.html

C#:   s.Split('\n')
来源：http://dali.yongpay.top/Article/details/gtttlgjhuh.html

[E20] 判断字符串是否为空
来源：http://dali.hongshengwenyu.top/Article/details/gttjthavwh.html

Py:   if not s:
来源：http://dali.daria6918.cn/Article/details/gtcbqyxhuf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yangfankeji.com/Article/details/gtyipgxelz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ehwqpu.com/Article/details/gtzwyduhww.html

TS:   if (s === "") {}
来源：http://dali.iojbl.cn/Article/details/gtmmrlkgah.html

Java: if (s.isEmpty()) {}
来源：http://dali.havefunace.top/Article/details/gtvnqukeub.html

Go:   if s == "" {}
来源：http://dali.pengpengdd.cyou/Article/details/gtvjhzoucp.html

Ruby: if s.empty?
来源：http://dali.zhixingplan.top/Article/details/gtnmpunzlm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xylfe.cn/Article/details/gtmyxwkbej.html

[E21] 超长截断加省略号
来源：http://dali.dashuyun.cn/Article/details/gtxgcqnuxq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tian-w.cn/Article/details/gtkipdulqe.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gtxwlaprdk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gtyoidiksm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtlxuhnkpl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gttlhlcazs.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.c1oappe.top/Article/details/gtdixputwh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gthntsmvun.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtzihrqkrs.html

[E22] 字节长度与字符长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxqfmswe.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.svipenyu.cn/Article/details/gtjyhcihfo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtffobuald.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gtmsfuvjkq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gtdznmfglo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.bjfxy.top/Article/details/gtubuicwdz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.birdmap.top/Article/details/gtddwbyvob.html

Ruby: s.bytesize;  s.length
来源：http://dali.ehwqpu.com/Article/details/gteynxfupm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cucudq.cn/Article/details/gtvrfdrrjr.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtrrsajnbu.html

F. 文件与目录
来源：http://dali.guannengcc.top/Article/details/gtviqjqnoi.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtkdrwjtup.html

[F01] 读取整个文件
来源：http://dali.yueranfly.top/Article/details/gtswgrkbbb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xziqi.cn/Article/details/gtiwetqddu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtmvxzlqqq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jianghu66.top/Article/details/gtpckoidsy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gtxljgqmhg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtqbkbgyqi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gaohongyu789.top/Article/details/gtegvwxmat.html

Ruby: File.read("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtslcekvge.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnofwjih.html

[F02] 逐行读取文件
来源：http://dali.yanxiufei.cn/Article/details/gtdlasphls.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dashuyun.cn/Article/details/gtialzehui.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhaqtcte.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.redwolf501.top/Article/details/gtlcnaixid.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zycfv.cn/Article/details/gtksqdfjhs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gttsplscyb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhengqikj.top/Article/details/gtjwrfhhww.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.9152youxi.cn/Article/details/gtgsunjeat.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnqzz.top/Article/details/gtzefstouk.html

[F03] 写入文件（覆盖）
来源：http://dali.svipenyu.cn/Article/details/gtgterashg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.mhx1999.top/Article/details/gtjcevjzpo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gtgcxnxggp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtrxssobhm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtulnvohff.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenlongwang.top/Article/details/gtxioluphv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtylwfvllu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.havefunace.top/Article/details/gtrvlkvtro.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gtdlxtqvhg.html

[F04] 追加写入文件
来源：http://dali.zhixingplan.top/Article/details/gtqgfwlbtv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinqigufen.top/Article/details/gtzfuanidh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.mhx1999.top/Article/details/gtvcrglxfd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqkcknjb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangdashe.top/Article/details/gtimyrcijd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqassjfp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.iojbl.cn/Article/details/gtgpriqtmp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tanke756.top/Article/details/gtccvbwxgj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yonumen.top/Article/details/gttxoranuw.html

[F05] 判断文件或目录是否存在
来源：http://dali.sxryk.cn/Article/details/gtgjxgpgrn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.andypj.xyz/Article/details/gtqbdubjwy.html

PHP:  file_exists("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtjgvcmfur.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtpxnccbry.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpykaefre.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtzdfrtrfh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuxming.cn/Article/details/gtzxewozqc.html

Ruby: File.exist?("a.txt")
来源：http://dali.yvedp.cn/Article/details/gttyvswwgj.html

C#:   File.Exists("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtlmugbzmm.html

[F06] 删除文件
来源：http://dali.yonumen.top/Article/details/gtaylmrofe.html

Py:   os.remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjzhqdye.html

PHP:  unlink("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtrchzddws.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtknyguexp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtpuwpaojj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtldenoaws.html

Go:   os.Remove("a.txt")
来源：http://dali.yongpay.top/Article/details/gtgqkftxnb.html

Ruby: File.delete("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gttdigwzsf.html

C#:   File.Delete("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtwethabfl.html

[F07] 创建目录（含多级）
来源：http://dali.yuxming.cn/Article/details/gtydjirrbk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.iojbl.cn/Article/details/gtudoypuxc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.quarkkingdee.top/Article/details/gtlwgnudpm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gtlwnwaobc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sysykeji.top/Article/details/gtwhlapevk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.meibo888.top/Article/details/gtuiwoyaly.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cashguo.top/Article/details/gtjcntsyto.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.vqdsnc.cn/Article/details/gtoksidwxr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzlpmsin.html

[F08] 遍历目录
来源：http://dali.snrcjt.cn/Article/details/gtrwdvcukd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yonumen.top/Article/details/gtvtkkphal.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.fzhhl.top/Article/details/gtrmirjcom.html

JS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtxuvzghvp.html

TS:   fs.readdirSync("dir")
来源：http://dali.fzhhl.top/Article/details/gtnzqbweef.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shangyingyoupin.top/Article/details/gtquxfazpb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hfpthk.cn/Article/details/gtwmzwzxio.html

Ruby: Dir.children("dir")
来源：http://dali.wangdashe.top/Article/details/gtlmtptelx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tianlin.xyz/Article/details/gtukhxtpkd.html

[F09] 获取文件大小
来源：http://dali.nanxinkj.top/Article/details/gtprqemxtm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtktwckyzh.html

PHP:  filesize("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtqkjkalgo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnxiangtu.top/Article/details/gtzzpmhaiz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.iojbl.cn/Article/details/gtznxsphbb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtbuhosnan.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgfzy.top/Article/details/gtrpylqfya.html

Ruby: File.size("a.txt")
来源：http://dali.havefunace.top/Article/details/gtximrkwlw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gotoacloud.top/Article/details/gtrtxefvwe.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tian-w.cn/Article/details/gttwqnnozg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtnejhubjo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtlwgufibb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtsnrswolp.html

TS:   path.extname("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtukwrgkgb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sweek.top/Article/details/gtojgergpy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtaeftdjxd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtoyuylvds.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtbdnwyqbe.html

[F11] 复制与移动文件
来源：http://dali.zhoulong.xyz/Article/details/gtmlttanyb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtssqyxmnc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nanxinkj.top/Article/details/gtuavzkmhn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtckpoqlhd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtxqkwarpf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ydzc1.top/Article/details/gtrrcnuinf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tian-w.cn/Article/details/gttbrgwfnj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtwhmwupvv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jyoumei.cn/Article/details/gtyvgdpopu.html

[F12] CSV 读写
来源：http://dali.jyoumei.cn/Article/details/gtcqagxytt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gogol.net.cn/Article/details/gtejkdaqvs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.redwolf501.top/Article/details/gtvyfexxnx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.0kj1m.cn/Article/details/gtninzfomy.html

TS:   // 同上
来源：http://dali.jinqigufen.top/Article/details/gtkoopxxmf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenzaomai.com/Article/details/gtfrjnchek.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tianlin.xyz/Article/details/gtdddnsaxc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dianchejie.cn/Article/details/gtqalycidi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.pengpengdd.cyou/Article/details/gtjcjzocmb.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gticgekfua.html

G. 面向对象
来源：http://dali.smart0.xyz/Article/details/gtmwwrumkc.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtflgkmedi.html

[G01] 定义类
来源：http://dali.daxiang520.top/Article/details/gtdppdteax.html

Py:   class User: pass
来源：http://dali.yj202588.top/Article/details/gtuvapweby.html

PHP:  class User {}
来源：http://dali.daxiang520.top/Article/details/gtashmtddg.html

JS:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gtcrouwwjv.html

TS:   class User { name: string = ""; }
来源：http://dali.birdmap.top/Article/details/gtykukqfme.html

Java: class User {}
来源：http://dali.tanke756.top/Article/details/gtukysqbpy.html

Go:   type User struct { Name string }
来源：http://dali.nanxuanxn.top/Article/details/gtfzaisfjj.html

Ruby: class User; end
来源：http://dali.hammf.cn/Article/details/gtvozavgbw.html

C#:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtohcyqraz.html

[G02] 构造函数
来源：http://dali.xziqi.cn/Article/details/gtxgcbvrwf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ybcxt.top/Article/details/gtfwxfraae.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yanxiufei.cn/Article/details/gtsbjsxnbc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jianghu66.top/Article/details/gtrfttdzcu.html

TS:   constructor(public name: string) {}
来源：http://dali.tianlin.xyz/Article/details/gtbmboipru.html

Java: User(String name) { this.name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gtnotrghoq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigufen.top/Article/details/gtjjeqzxke.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.iojbl.cn/Article/details/gtmhprexhb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtanzsfpsr.html

[G03] 实例属性
来源：http://dali.gotoacloud.top/Article/details/gtzqjilksl.html

Py:   self.name = "x"
来源：http://dali.cucudq.cn/Article/details/gthadvscmv.html

PHP:  public string $name = "x";
来源：http://dali.yangfankeji.com/Article/details/gtnjbgymrb.html

JS:   this.name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtflopigay.html

TS:   name: string = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtzpjgtkxk.html

Java: private String name;
来源：http://dali.hnxiangtu.top/Article/details/gtpkiwanyt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yonumen.top/Article/details/gtuqyxmovn.html

Ruby: @name = "x"
来源：http://dali.xylfe.cn/Article/details/gtckqvndip.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dashuyun.cn/Article/details/gtksfkiruw.html

[G04] 定义方法
来源：http://dali.dianchejie.cn/Article/details/gtbmmeohte.html

Py:   def greet(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gtxvkgthbf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gtpvotejkl.html

JS:   greet() { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtyswavhli.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtifezyeff.html

Java: String greet() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsahkcaqf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gtapcgmbzn.html

Ruby: def greet; @name; end
来源：http://dali.xuanzx.com/Article/details/gtbkgipose.html

C#:   public string Greet() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gtqfoheayl.html

[G05] 继承
来源：http://dali.hysaishi.cn/Article/details/gtbzucuxqq.html

Py:   class Admin(User): pass
来源：http://dali.pycfn.com/Article/details/gtocfqgnpo.html

PHP:  class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gtimotvcsn.html

JS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtgvwkxctb.html

TS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtvabwmlmg.html

Java: class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gttwqmghhh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guannengcc.top/Article/details/gtqtyksaxf.html

Ruby: class Admin < User; end
来源：http://dali.tian-w.cn/Article/details/gtbosbuojj.html

C#:   class Admin : User {}
来源：http://dali.yonumen.top/Article/details/gthaekpnjo.html

[G06] 重写方法
来源：http://dali.zhongyouzk.top/Article/details/gtuohryvpk.html

Py:   def greet(self): return "admin"
来源：http://dali.zycfv.cn/Article/details/gtqoylenns.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gthllvmzve.html

JS:   greet() { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtimxpxnet.html

TS:   greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtxvtsbdvf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtddnlhxew.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.havefunace.top/Article/details/gthgunsmie.html

Ruby: def greet; "admin"; end
来源：http://dali.cucudq.cn/Article/details/gtjrturozd.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinghuilouyu.cn/Article/details/gtjoxsnzqs.html

[G07] 调用父类方法
来源：http://dali.yongpay.top/Article/details/gtkgabeuok.html

Py:   super().greet()
来源：http://dali.smart0.xyz/Article/details/gtwlcbnvvy.html

PHP:  parent::greet();
来源：http://dali.svipenyu.cn/Article/details/gtktvnwjvq.html

JS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtllrfxkga.html

TS:   super.greet();
来源：http://dali.yueranfly.top/Article/details/gtegftiphq.html

Java: super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxrsgkgiy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ppjwa.cn/Article/details/gtioriskst.html

Ruby: super
来源：http://dali.iojbl.cn/Article/details/gtpgivyggk.html

C#:   base.Greet();
来源：http://dali.gotoacloud.top/Article/details/gtjeplcgjv.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gtkigbztkg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.snrcjt.cn/Article/details/gtfldkbvha.html

PHP:  public static function f() {}
来源：http://dali.0kj1m.cn/Article/details/gttjtjphju.html

JS:   static f() {}
来源：http://dali.jiagoushi.top/Article/details/gtsnuhzfsu.html

TS:   static f(): void {}
来源：http://dali.zhoulong.xyz/Article/details/gtyrmgnlby.html

Java: static void f() {}
来源：http://dali.nanxinkj.top/Article/details/gtzxaamdzz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shangyingyoupin.top/Article/details/gtgsmkmvtj.html

Ruby: def self.f; end
来源：http://dali.gotoacloud.top/Article/details/gtagtesfxd.html

C#:   public static void F() {}
来源：http://dali.jiagoushi.top/Article/details/gtwnonoxto.html

[G09] 接口 / 抽象类
来源：http://dali.yueranfly.top/Article/details/gtjzlfvirx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.bjfxy.top/Article/details/gtndtmqkzc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gzhubu.top/Article/details/gtudoeulyn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.0kj1m.cn/Article/details/gtapmqrors.html

TS:   interface Shape { area(): number; }
来源：http://dali.shangyingyoupin.top/Article/details/gtxwsbswmf.html

Java: interface Shape { double area(); }
来源：http://dali.shuidangran.top/Article/details/gtprxvzusu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.redwolf501.top/Article/details/gtlcrbchzb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhongyouzk.top/Article/details/gtjhpmjyim.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gttlvpwsln.html

[G10] 访问控制
来源：http://dali.nanxinkj.top/Article/details/gtfstthoxl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hammf.cn/Article/details/gtnhbwohpi.html

PHP:  public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gthvabhmlq.html

JS:   #private 字段；其余公开
来源：http://dali.xylfe.cn/Article/details/gtvhqvbyea.html

TS:   public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtjcruejov.html

Java: public / protected / private / 默认包级
来源：http://dali.yvedp.cn/Article/details/gtckrwydow.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.kuanghao11.cn/Article/details/gtbarqcwmo.html

Ruby: public / protected / private
来源：http://dali.316326.xyz/Article/details/gtuqiiktiy.html

C#:   public / protected / private / internal
来源：http://dali.xuanzx.com/Article/details/gtpgbzaudm.html

[G11] getter / setter
来源：http://dali.0kj1m.cn/Article/details/gtspayfojs.html

Py:   @property 与 @x.setter
来源：http://dali.shangyingyoupin.top/Article/details/gtthhgcjea.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gtrkpnupoa.html

JS:   get name() { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gtvxjrfaso.html

TS:   get name(): string { return this._name; }
来源：http://dali.snrcjt.cn/Article/details/gtrqmstmoz.html

Java: public String getName() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtnfzearyb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gtnrhpzwmr.html

Ruby: attr_accessor :name
来源：http://dali.daria6918.cn/Article/details/gtreqiuzjs.html

C#:   public string Name { get; set; }
来源：http://dali.aizwys.cn/Article/details/gtjlrhjogm.html

[G12] 对象转字符串
来源：http://dali.yj202588.top/Article/details/gtqhufwwzq.html

Py:   def __str__(self): return self.name
来源：http://dali.vqdsnc.cn/Article/details/gtusxuluod.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gtrktosoty.html

JS:   toString() { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtfvphmgez.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtqaeunwwt.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtinjtzhqy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gtexwzsydf.html

Ruby: def to_s; @name; end
来源：http://dali.ybcxt.top/Article/details/gtetaqwljh.html

C#:   public override string ToString() => Name;
来源：http://dali.haohaochexian.top/Article/details/gtotgluzvh.html

[G13] 判断对象类型
来源：http://dali.jlsjyb.cn/Article/details/gtoigfbgot.html

Py:   isinstance(u, User)
来源：http://dali.zhiwuduotai.top/Article/details/gtdupodhak.html

PHP:  $u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtuoltllqp.html

JS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtrlmngkro.html

TS:   u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtsdkdfisp.html

Java: u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtdeaclfvv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjdlxqcdf.html

Ruby: u.is_a?(User)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxrjruhc.html

C#:   u is User
来源：http://dali.haohaochexian.top/Article/details/gtzcccxykf.html

[G14] 数据类 / record
来源：http://dali.hongshengwenyu.top/Article/details/gthcujpgju.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.wangdashe.top/Article/details/gtbctdzbhq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.snrcjt.cn/Article/details/gtmqccvbkk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangdashe.top/Article/details/gtsmlebxmk.html

TS:   type User = { name: string; age: number };
来源：http://dali.daxiang520.top/Article/details/gtomnsztut.html

Java: record User(String name, int age) {}
来源：http://dali.sweek.top/Article/details/gtqpdamonc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.bjfxy.top/Article/details/gtfryvxmzi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.mhx1999.top/Article/details/gthyjridxp.html

C#:   record User(string Name, int Age);
来源：http://dali.daria6918.cn/Article/details/gtsgttccuu.html

[G15] 枚举
来源：http://dali.hnqzz.top/Article/details/gtbxqvlqdr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenjidiqi.icu/Article/details/gtmtljjomj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jqgfzy.top/Article/details/gtsqjpaakz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gotoacloud.top/Article/details/gthlsauwij.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhixingplan.top/Article/details/gtzybidhzu.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqobrlvs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tanke756.top/Article/details/gtkqxmahvd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.316326.xyz/Article/details/gtmfcvxurl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guannengcc.top/Article/details/gtwuejgyft.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258888.top/Article/details/gtcmzolfan.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.wangdashe.top/Article/details/gtzkyixlpr.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gtnsvegjlz.html

JS:   Object.entries(obj)
来源：http://dali.cdnleiting.top/Article/details/gtsbjpdoqq.html

TS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gtaodnnouu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnxiangtu.top/Article/details/gthgismxfm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.redwolf501.top/Article/details/gtspqklmcq.html

Ruby: obj.instance_variables
来源：http://dali.guowangkeji.top/Article/details/gtbzfynbde.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ivvv.top/Article/details/gtpgwugrsr.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtswdlxmrf.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gthnqvjlbn.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtfsvlurtm.html

[H01] try / catch 基础
来源：http://dali.dashuyun.cn/Article/details/gtqrbivbig.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxgwkmqc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hnxiangtu.top/Article/details/gtbmqpqfkj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jqgfzy.top/Article/details/gtuoibeqrh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gtgfwipxfz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jlsjyb.cn/Article/details/gthqbuxhjp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tian-w.cn/Article/details/gtqwxfjopq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hnxiangtu.top/Article/details/gtpqzezamv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuxming.cn/Article/details/gtknxxtued.html

[H02] finally / ensure 收尾
来源：http://dali.yj202588.top/Article/details/gtzwcquzbw.html


<!-- 参考信息 -->