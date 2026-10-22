代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtfqdwgqsx.html

[E19] 多行文本按行拆分
来源：http://dali.redwolf501.top/Article/details/gtclvrqylv.html

Py:   s.splitlines()
来源：http://dali.zhongyouzk.top/Article/details/gtbpmpyxcl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hammf.cn/Article/details/gtohnmmfgl.html

JS:   s.split(/\r?\n/)
来源：http://dali.redwolf501.top/Article/details/gtsaqppoqn.html

TS:   s.split(/\r?\n/)
来源：http://dali.cdnleiting.top/Article/details/gtpwtcwhpq.html

Java: s.lines().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkujiyqhg.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258.top/Article/details/gtcyjjubwq.html

Ruby: s.lines
来源：http://dali.zhoulong.xyz/Article/details/gtunwocxpj.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangtech.top/Article/details/gtnudptfpt.html

[E20] 判断字符串是否为空
来源：http://dali.jinqigufen.top/Article/details/gtbaepdtxj.html

Py:   if not s:
来源：http://dali.zhongyouzk.top/Article/details/gtxubxxddp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.meibo888.top/Article/details/gtikgxctge.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.0kj1m.cn/Article/details/gtmtbsywxx.html

TS:   if (s === "") {}
来源：http://dali.svipenyu.cn/Article/details/gtvcrzobjg.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gtgmhxyvjk.html

Go:   if s == "" {}
来源：http://dali.vqdsnc.cn/Article/details/gtfdhxnjug.html

Ruby: if s.empty?
来源：http://dali.pengpengdd.cyou/Article/details/gtnzphcikc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.vqdsnc.cn/Article/details/gtsjfmlggr.html

[E21] 超长截断加省略号
来源：http://dali.fzhhl.top/Article/details/gtfaximuxe.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cheryme.top/Article/details/gtsgntoqru.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtmuxmcqfn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gttlaqrsbv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtedtjmosw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtvxmqgsok.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hongshengwenyu.top/Article/details/gtnbjwmfeb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtwacelnwk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtsspcygum.html

[E22] 字节长度与字符长度
来源：http://dali.tanke756.top/Article/details/gtdrfzmcro.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.wangshuangyany.cn/Article/details/gttoqdhwnd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtcmpuqxew.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.redwolf501.top/Article/details/gtbkdwyjsj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gtwwzpyrmt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.guowangkeji.top/Article/details/gtnseeabpd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hnxiangtu.top/Article/details/gtjbzbckos.html

Ruby: s.bytesize;  s.length
来源：http://dali.gzhubu.top/Article/details/gtynvdeafj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hysaishi.cn/Article/details/gtwsbkrcrb.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtpxwityoo.html

F. 文件与目录
来源：http://dali.dianchejie.cn/Article/details/gtwwflapxv.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtohzumjoa.html

[F01] 读取整个文件
来源：http://dali.xziqi.cn/Article/details/gtehuusvyk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.9152youxi.cn/Article/details/gtzpsduvtj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtjtrzkukk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhengqikj.top/Article/details/gtrkmotqan.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gtzcxykyih.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtdgrzgadk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.iojbl.cn/Article/details/gtxhyzufvv.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwrxwainv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtdqhnhwkv.html

[F02] 逐行读取文件
来源：http://dali.ydzc1.top/Article/details/gtotiycgxq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjauizud.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.guowangkeji.top/Article/details/gtdytdpgpt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gtasvymgal.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxuanxn.top/Article/details/gtzpicogrs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvwnfhoet.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcijkecvm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ppjwa.cn/Article/details/gtjehokamo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ybcxt.top/Article/details/gtiiefkjvu.html

[F03] 写入文件（覆盖）
来源：http://dali.xuanzx.com/Article/details/gtqrxmeqal.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.smart0.xyz/Article/details/gtnmaeuiww.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.daria6918.cn/Article/details/gtcooflsmp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guannengcc.top/Article/details/gtqyoyzvlp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gtetaokzvz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.mhx1999.top/Article/details/gtipqbljvd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gzhubu.top/Article/details/gtycqzimud.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yanxiufei.cn/Article/details/gtwrjfvrll.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gthxjkcgka.html

[F04] 追加写入文件
来源：http://dali.zhengqikj.top/Article/details/gtilqcpmzy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gthdbbejlt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.wangshuangyany.cn/Article/details/gtczwfdfro.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jyoumei.cn/Article/details/gtmxcjxuxb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aibaodan.cn/Article/details/gttsdlkldl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenzaomai.com/Article/details/gtiidnwrca.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtpamsjaty.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ybcxt.top/Article/details/gtpfbgzerq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nanxinkj.top/Article/details/gtwowipbiy.html

[F05] 判断文件或目录是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gtyutbmxlh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cqqwz.cn/Article/details/gtuiqzjlaf.html

PHP:  file_exists("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtooibyogz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtmdweytju.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtbyfeiyuy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtoijigrcv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.vqdsnc.cn/Article/details/gtcrpsnpwh.html

Ruby: File.exist?("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtlznubywt.html

C#:   File.Exists("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtiigvtbry.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gtzfilxwyo.html

Py:   os.remove("a.txt")
来源：http://dali.meibo888.top/Article/details/gttrzkettr.html

PHP:  unlink("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtpsobheov.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtlofrpera.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtnsopvfjr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtgtknzqpw.html

Go:   os.Remove("a.txt")
来源：http://dali.hammf.cn/Article/details/gtdfwisvek.html

Ruby: File.delete("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtvkogsmgx.html

C#:   File.Delete("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtzejidhju.html

[F07] 创建目录（含多级）
来源：http://dali.hammf.cn/Article/details/gtvolxhtrk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sysykeji.top/Article/details/gtulvlostz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhengqikj.top/Article/details/gtcptwacwn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxinkj.top/Article/details/gtbfxngadj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tianlin.xyz/Article/details/gtjwsbgufl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cqqwz.cn/Article/details/gtwpcwsmhy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daxiang520.top/Article/details/gtwlxefxir.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.c1oappe.top/Article/details/gtnvowhlan.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gtfrgzsxif.html

[F08] 遍历目录
来源：http://dali.cqqwz.cn/Article/details/gtsxhqllvw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shuidangran.top/Article/details/gtpqbbyddf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj20258.top/Article/details/gtakzxwjqu.html

JS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqzpwcwxf.html

TS:   fs.readdirSync("dir")
来源：http://dali.aizwys.cn/Article/details/gtayrxqxlp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jlsjyb.cn/Article/details/gtpwahigjz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sysykeji.top/Article/details/gtjglpfakq.html

Ruby: Dir.children("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtakmdckua.html

C#:   Directory.GetFiles("dir")
来源：http://dali.mhx1999.top/Article/details/gtdrdomcvb.html

[F09] 获取文件大小
来源：http://dali.gzhubu.top/Article/details/gttwragpee.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtrjltznaa.html

PHP:  filesize("a.txt");
来源：http://dali.pycfn.com/Article/details/gtmdnjodol.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zdqjudy.top/Article/details/gtcwcogmby.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gtqyxnqqno.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtcpmxhtlu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj202588.top/Article/details/gtmikfafkr.html

Ruby: File.size("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtbjqlxtbd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jyoumei.cn/Article/details/gtkbbtvisp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenlongwang.top/Article/details/gtwipbvfqz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtodhcmrsb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtkmlsqbzf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtcllfpmgd.html

TS:   path.extname("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtkxfcerfk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jyoumei.cn/Article/details/gtelwzirdd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtdcvfdnbq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtxudqmtgb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtccnzeehw.html

[F11] 复制与移动文件
来源：http://dali.andypj.xyz/Article/details/gtpodljbts.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtgqtsjbmd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yueranfly.top/Article/details/gtuuwcweqt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gttkzyilfs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtclyxwrsz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gtxaqervsc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyngseghy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtrynyiltg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pycfn.com/Article/details/gthvmxqrbl.html

[F12] CSV 读写
来源：http://dali.jinqigfzy.top/Article/details/gtdprbngrm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shzxlz.cn/Article/details/gtqcvdgbml.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdjhhdbc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cqqwz.cn/Article/details/gtplevcglr.html

TS:   // 同上
来源：http://dali.jiagoushi.top/Article/details/gtlugawcvc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.0kj1m.cn/Article/details/gttxshpyhp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ydzc1.top/Article/details/gtrsqgocvj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hammf.cn/Article/details/gthewfskbo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cdnleiting.top/Article/details/gtuiarmaca.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtuvaqqgwb.html

G. 面向对象
来源：http://dali.wangshuangyany.cn/Article/details/gtaoudbinn.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtlxtdeuud.html

[G01] 定义类
来源：http://dali.xuanzx.com/Article/details/gtflyseamw.html

Py:   class User: pass
来源：http://dali.haohaochexian.top/Article/details/gtegeudlyp.html

PHP:  class User {}
来源：http://dali.jinqigufen.top/Article/details/gtyyolbdsk.html

JS:   class User {}
来源：http://dali.yongpay.top/Article/details/gtanfyrcjz.html

TS:   class User { name: string = ""; }
来源：http://dali.zhengqikj.top/Article/details/gtmzbnvsvq.html

Java: class User {}
来源：http://dali.smart0.xyz/Article/details/gtiliqehdl.html

Go:   type User struct { Name string }
来源：http://dali.yj20258888.top/Article/details/gtnbaagwnl.html

Ruby: class User; end
来源：http://dali.quarkkingdee.top/Article/details/gtpgdavprs.html

C#:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gtevhsxcrq.html

[G02] 构造函数
来源：http://dali.daria6918.cn/Article/details/gthtkhbxma.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.9152youxi.cn/Article/details/gtykrwpcjt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnlpmpuzs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gtffboplha.html

TS:   constructor(public name: string) {}
来源：http://dali.shangyingyoupin.top/Article/details/gthkgdqepa.html

Java: User(String name) { this.name = name; }
来源：http://dali.fzhhl.top/Article/details/gtvhgjumnz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.snrcjt.cn/Article/details/gtugdgpfug.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.svipenyu.cn/Article/details/gtvjyawimc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.mhx1999.top/Article/details/gtknwmhqps.html

[G03] 实例属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtohriuzdd.html

Py:   self.name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gtngilqqds.html

PHP:  public string $name = "x";
来源：http://dali.yongpay.top/Article/details/gtpesmugbg.html

JS:   this.name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtkhodqjgf.html

TS:   name: string = "x";
来源：http://dali.smart0.xyz/Article/details/gtmcezfxxu.html

Java: private String name;
来源：http://dali.sxryk.cn/Article/details/gtqstlbxbm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jyoumei.cn/Article/details/gtpacqvhdy.html

Ruby: @name = "x"
来源：http://dali.xziqi.cn/Article/details/gtnczhprex.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dashuyun.cn/Article/details/gtoqdlgjkd.html

[G04] 定义方法
来源：http://dali.havefunace.top/Article/details/gtkroravwx.html

Py:   def greet(self): return self.name
来源：http://dali.haohaochexian.top/Article/details/gtjasxcbnv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtrgiolvyl.html

JS:   greet() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtzmntnzij.html

TS:   greet(): string { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gtvrzswrkj.html

Java: String greet() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtoovzrdth.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtxnfnhqaw.html

Ruby: def greet; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gtnewdjopt.html

C#:   public string Greet() => Name;
来源：http://dali.gaohongyu789.top/Article/details/gtrpzcwkoy.html

[G05] 继承
来源：http://dali.havefunace.top/Article/details/gttdkjotxp.html

Py:   class Admin(User): pass
来源：http://dali.cucudq.cn/Article/details/gtyvbijxoe.html

PHP:  class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtmmealxfv.html

JS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtyikbigxr.html

TS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtafxwczci.html

Java: class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtualzwmws.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nwbrower.top/Article/details/gtqtixxnez.html

Ruby: class Admin < User; end
来源：http://dali.zycfv.cn/Article/details/gtylyspifg.html

C#:   class Admin : User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtwxjslhmw.html

[G06] 重写方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdypftldf.html

Py:   def greet(self): return "admin"
来源：http://dali.ybcxt.top/Article/details/gtpxuuarxt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gtfpfyuzcl.html

JS:   greet() { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtcocdlgii.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtgomyzxaf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtzwplumla.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yueranfly.top/Article/details/gtrtvjgajl.html

Ruby: def greet; "admin"; end
来源：http://dali.zdqjudy.top/Article/details/gtxxulmewu.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinghuilouyu.cn/Article/details/gtpoekidtb.html

[G07] 调用父类方法
来源：http://dali.feifeiyinyue.top/Article/details/gtacilfkti.html

Py:   super().greet()
来源：http://dali.fengsongda.top/Article/details/gtpwtkaajo.html

PHP:  parent::greet();
来源：http://dali.iojbl.cn/Article/details/gthfmbboyd.html

JS:   super.greet();
来源：http://dali.sysykeji.top/Article/details/gtxzlunbox.html

TS:   super.greet();
来源：http://dali.redwolf501.top/Article/details/gtmiiamyfs.html

Java: super.greet();
来源：http://dali.xylfe.cn/Article/details/gtkctoqqou.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tian-w.cn/Article/details/gtdjehcwuf.html

Ruby: super
来源：http://dali.aibaodan.cn/Article/details/gtrcpmgdxx.html

C#:   base.Greet();
来源：http://dali.meibo888.top/Article/details/gtoyvyyurp.html

[G08] 静态方法与属性
来源：http://dali.316326.xyz/Article/details/gttiowuvzw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozzeaype.html

PHP:  public static function f() {}
来源：http://dali.snrcjt.cn/Article/details/gtwgwnkgnr.html

JS:   static f() {}
来源：http://dali.yangfankeji.com/Article/details/gtafqvagcl.html

TS:   static f(): void {}
来源：http://dali.sweek.top/Article/details/gtgwtcmbhj.html

Java: static void f() {}
来源：http://dali.hammf.cn/Article/details/gtkhglyusy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tanke756.top/Article/details/gtetrqlvaj.html

Ruby: def self.f; end
来源：http://dali.shzxlz.cn/Article/details/gtfcrlrjsr.html

C#:   public static void F() {}
来源：http://dali.daria6918.cn/Article/details/gtbruxceha.html

[G09] 接口 / 抽象类
来源：http://dali.c1oappe.top/Article/details/gtmtaaxxow.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinghuilouyu.cn/Article/details/gtvfmkwzyx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jyoumei.cn/Article/details/gtkcnahbyo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhengqikj.top/Article/details/gtcxrwkswq.html

TS:   interface Shape { area(): number; }
来源：http://dali.zycfv.cn/Article/details/gtdiotwiuc.html

Java: interface Shape { double area(); }
来源：http://dali.hnxiangtu.top/Article/details/gthxjisbrq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cdnleiting.top/Article/details/gtaktrepvo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtxffpzztq.html

C#:   interface IShape { double Area(); }
来源：http://dali.fzhhl.top/Article/details/gtmtefveeb.html

[G10] 访问控制
来源：http://dali.yueranfly.top/Article/details/gtqucsrmuu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.aibaodan.cn/Article/details/gtklukcvtd.html

PHP:  public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtmnfqfeew.html

JS:   #private 字段；其余公开
来源：http://dali.kuanghao11.cn/Article/details/gtpbfpylea.html

TS:   public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtogaocnty.html

Java: public / protected / private / 默认包级
来源：http://dali.smart0.xyz/Article/details/gtokmqpgog.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.snrcjt.cn/Article/details/gthawoquaf.html

Ruby: public / protected / private
来源：http://dali.yonumen.top/Article/details/gtctspswbt.html

C#:   public / protected / private / internal
来源：http://dali.aizwys.cn/Article/details/gtxywuavsz.html

[G11] getter / setter
来源：http://dali.gogol.net.cn/Article/details/gtmdxiqfnp.html

Py:   @property 与 @x.setter
来源：http://dali.cucudq.cn/Article/details/gtjnjgzmmt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gtiyqernfp.html

JS:   get name() { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gtlarnnxgp.html

TS:   get name(): string { return this._name; }
来源：http://dali.cucudq.cn/Article/details/gtrtbwpjfb.html

Java: public String getName() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtqyfkgscm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gtrlfpuwqv.html

Ruby: attr_accessor :name
来源：http://dali.hnqzz.top/Article/details/gthbnjbqjd.html

C#:   public string Name { get; set; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcakxfywp.html

[G12] 对象转字符串
来源：http://dali.nwbrower.top/Article/details/gtqmvnaxkt.html

Py:   def __str__(self): return self.name
来源：http://dali.jinqigfzy.top/Article/details/gtaiediitx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtizvbbxir.html

JS:   toString() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtowzwygvc.html

TS:   toString(): string { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtohndsbpd.html

Java: @Override public String toString() { return name; }
来源：http://dali.hammf.cn/Article/details/gtghwltmsy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtfjoefotn.html

Ruby: def to_s; @name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gttoywfxpu.html

C#:   public override string ToString() => Name;
来源：http://dali.wangshuangyany.cn/Article/details/gtaqzttfnk.html

[G13] 判断对象类型
来源：http://dali.cucudq.cn/Article/details/gtydarkont.html

Py:   isinstance(u, User)
来源：http://dali.dianchejie.cn/Article/details/gtqcvrbswr.html

PHP:  $u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtuzzpmrtn.html

JS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtnpuzslct.html

TS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gtbblftmxa.html

Java: u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtdpaynunx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hywenlv.cn/Article/details/gtphhbpczx.html

Ruby: u.is_a?(User)
来源：http://dali.shangyingyoupin.top/Article/details/gtepafijju.html

C#:   u is User
来源：http://dali.zycfv.cn/Article/details/gtcuoujbnc.html

[G14] 数据类 / record
来源：http://dali.tianlin.xyz/Article/details/gtnulblieq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhoulong.xyz/Article/details/gtuckvbdnx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jqgfzy.top/Article/details/gtnfwhiwur.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hongshengwenyu.top/Article/details/gtwpdxqxym.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigufen.top/Article/details/gtwyvcdtcv.html

Java: record User(String name, int age) {}
来源：http://dali.hysaishi.cn/Article/details/gtlqlqscsp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhiwuduotai.top/Article/details/gtlzxxhsgq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gzhubu.top/Article/details/gtghqzekxp.html

C#:   record User(string Name, int Age);
来源：http://dali.cdnleiting.top/Article/details/gtldmdthrv.html

[G15] 枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbockros.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ppjwa.cn/Article/details/gteodnbyup.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jqgfzy.top/Article/details/gtokzlrxgr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sweek.top/Article/details/gteeavdwxl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.c1oappe.top/Article/details/gtajpnefag.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenzaomai.com/Article/details/gthmonakhy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.meibo888.top/Article/details/gtzkgdggvp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.316326.xyz/Article/details/gtkqqhtsaw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gotoacloud.top/Article/details/gtdycggzdo.html

[G16] 对象转数组 / 字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkmgegng.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sweek.top/Article/details/gtngcmsqpb.html

PHP:  get_object_vars($obj);
来源：http://dali.cqqwz.cn/Article/details/gtygpbnvjo.html

JS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gtuqpzjlzw.html

TS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtclwmfzxv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yangfankeji.com/Article/details/gtpveskcam.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangdashe.top/Article/details/gtjxbedype.html

Ruby: obj.instance_variables
来源：http://dali.zhengqikj.top/Article/details/gtmrtxlaej.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gtgdtmaacb.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtkjnggaco.html

H. 异常与错误处理
来源：http://dali.vqdsnc.cn/Article/details/gtgnlfomsr.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtlljpquhv.html

[H01] try / catch 基础
来源：http://dali.yuxming.cn/Article/details/gtbcrqsiiu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.birdmap.top/Article/details/gtwwbjrpzl.html


<!-- 参考信息 -->