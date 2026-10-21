代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ehwqpu.com/Article/details/gtwhhjwrua.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cucudq.cn/Article/details/gtelayvjgy.html

Ruby: s.capitalize
来源：http://dali.hfpthk.cn/Article/details/gtttmdunku.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtabtxpzpd.html

[E18] 模板占位符替换
来源：http://dali.ehwqpu.com/Article/details/gtdqmluisp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj20258.top/Article/details/gttioregac.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cheryme.top/Article/details/gthjxctwgj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gtlogsebdh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtbfgswnxq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gttjdgmcte.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtzaclrqhs.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ydzc1.top/Article/details/gtivmvwmqi.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jqgfzy.top/Article/details/gtjqeaarnv.html

[E19] 多行文本按行拆分
来源：http://dali.vqdsnc.cn/Article/details/gtbfsvdsrb.html

Py:   s.splitlines()
来源：http://dali.jinghuilouyu.cn/Article/details/gtydgszeun.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenlongwang.top/Article/details/gtkatnwthu.html

JS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gtdailepah.html

TS:   s.split(/\r?\n/)
来源：http://dali.aibaodan.cn/Article/details/gtbeknfxfv.html

Java: s.lines().toList()
来源：http://dali.hnxiangtu.top/Article/details/gtggxrfsbn.html

Go:   strings.Split(s, "\n")
来源：http://dali.guannengcc.top/Article/details/gtxhjwsglt.html

Ruby: s.lines
来源：http://dali.cashguo.top/Article/details/gtxqkdghyq.html

C#:   s.Split('\n')
来源：http://dali.sweek.top/Article/details/gtimkdzbrm.html

[E20] 判断字符串是否为空
来源：http://dali.fengsongda.top/Article/details/gtvwbqbhop.html

Py:   if not s:
来源：http://dali.kuanghao11.cn/Article/details/gtwpyeclts.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.daria6918.cn/Article/details/gtzuwmfxwg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.haohaochexian.top/Article/details/gtiypgvpmr.html

TS:   if (s === "") {}
来源：http://dali.smart0.xyz/Article/details/gtdnpfoppq.html

Java: if (s.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gtkrtvmedk.html

Go:   if s == "" {}
来源：http://dali.hnxiangtu.top/Article/details/gtbfrxwtul.html

Ruby: if s.empty?
来源：http://dali.meibo888.top/Article/details/gtnltaegzv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.wangdashe.top/Article/details/gtltpdnfgk.html

[E21] 超长截断加省略号
来源：http://dali.xuanzx.com/Article/details/gtpboyiltb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiowtcvum.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtlrszrhze.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtlxzvrisq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtipdbpttl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtsircries.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shanyushiyangtech.top/Article/details/gtsrvgpxpc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gtvhsqiloe.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtaeqwhzpy.html

[E22] 字节长度与字符长度
来源：http://dali.xylfe.cn/Article/details/gtiobsjmxa.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgthdlxgo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gtkdurxubn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtusecuxgs.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gttwtztgqg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangshuangyany.cn/Article/details/gtapknmmsz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenjidiqi.icu/Article/details/gtvliufmul.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtvetkkhap.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nwbrower.top/Article/details/gtizdzpzyg.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtmtojjjey.html

F. 文件与目录
来源：http://dali.yj202588.top/Article/details/gtpdarrvzj.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtjbxdbjnn.html

[F01] 读取整个文件
来源：http://dali.cashguo.top/Article/details/gtednnrwmz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtscojblsh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtualnlabs.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gtyfbzfgse.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gtfruqjkpj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfuqejbwo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hammf.cn/Article/details/gtzhegpdgu.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtjgmdotqb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtajumjzir.html

[F02] 逐行读取文件
来源：http://dali.daxiang520.top/Article/details/gtsamsjvrw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhongyouzk.top/Article/details/gtzetsihbf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aizwys.cn/Article/details/gtblmzljtk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gtapzjvoic.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gtmeqimrls.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzzgfmyg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ydzc1.top/Article/details/gtfundpnvy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.guannengcc.top/Article/details/gtnbrwgxvu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gotoacloud.top/Article/details/gtzhsmsfut.html

[F03] 写入文件（覆盖）
来源：http://dali.shuidangran.top/Article/details/gtdlieochz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenlongwang.top/Article/details/gtbgjndgpo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gtuaoghzhi.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtsmjjwihh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cheryme.top/Article/details/gttoritmyr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yonumen.top/Article/details/gtzfkuytuo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jyoumei.cn/Article/details/gtoomfavmh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.daria6918.cn/Article/details/gtcuxkqltf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.andypj.xyz/Article/details/gtynmnulou.html

[F04] 追加写入文件
来源：http://dali.sweek.top/Article/details/gtzlcndzcf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gttkiwsijn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hnxiangtu.top/Article/details/gtzahdwgax.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gogol.net.cn/Article/details/gttujuyekv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yangfankeji.com/Article/details/gtpeliagge.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hongshengwenyu.top/Article/details/gtqdtxpyrg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.daxiang520.top/Article/details/gtlaqemlwl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhoulong.xyz/Article/details/gtcypxgckj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangdashe.top/Article/details/gtebofaktr.html

[F05] 判断文件或目录是否存在
来源：http://dali.gogol.net.cn/Article/details/gtofwqurri.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxinkj.top/Article/details/gthmeczuyq.html

PHP:  file_exists("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtgujpwlqo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtvxpmbrap.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtochwfwrh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtfwofvqya.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.kuanghao11.cn/Article/details/gtetaggxsn.html

Ruby: File.exist?("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtxtdrjklp.html

C#:   File.Exists("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtacwttmpk.html

[F06] 删除文件
来源：http://dali.zhixingplan.top/Article/details/gtgidsdfcw.html

Py:   os.remove("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtbdwyolwp.html

PHP:  unlink("a.txt");
来源：http://dali.mhx1999.top/Article/details/gthzaivyrm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtubjeyrur.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtpbokzurf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtxwysgttu.html

Go:   os.Remove("a.txt")
来源：http://dali.hammf.cn/Article/details/gtkzrplqud.html

Ruby: File.delete("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtdbntnjgy.html

C#:   File.Delete("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtfuzkrioc.html

[F07] 创建目录（含多级）
来源：http://dali.mhx1999.top/Article/details/gtbuuvirhy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ydzc1.top/Article/details/gtqgtiiqkq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gogol.net.cn/Article/details/gtzfnejexb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gtoxewcecm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gtrhthhfgs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtawzwtxbm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yongpay.top/Article/details/gtikwmurxu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.wangdashe.top/Article/details/gtaxdexqrs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.andypj.xyz/Article/details/gtxujhmgzn.html

[F08] 遍历目录
来源：http://dali.hnxiangtu.top/Article/details/gtyizephkz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhongyouzk.top/Article/details/gteviepoui.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tian-w.cn/Article/details/gtswoufbdf.html

JS:   fs.readdirSync("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtlnwxqpls.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtxhzixiul.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj202588.top/Article/details/gtumytyiwt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmbodvlc.html

Ruby: Dir.children("dir")
来源：http://dali.bjfxy.top/Article/details/gtysmwnprh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nwbrower.top/Article/details/gtqjwtzfhn.html

[F09] 获取文件大小
来源：http://dali.xuanzx.com/Article/details/gtwlmexzod.html

Py:   os.path.getsize("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtdoxovqtk.html

PHP:  filesize("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtbykzusbm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xuanzx.com/Article/details/gtijnevzdd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenlongwang.top/Article/details/gtvubyumab.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtuatdzfag.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.havefunace.top/Article/details/gtliscbwxr.html

Ruby: File.size("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtzauhjsqv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nwbrower.top/Article/details/gturridkwd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.guannengcc.top/Article/details/gtcagjyngz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtjgkbaezk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.316326.xyz/Article/details/gtbrepzfdk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtrqpvauix.html

TS:   path.extname("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtweyjpthb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.0kj1m.cn/Article/details/gtgnjzgwoy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtslbxvejy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtzrwmezpv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtdtbzknpx.html

[F11] 复制与移动文件
来源：http://dali.yuanzhike.top/Article/details/gtqltqgnvz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzhpxbth.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.haohaochexian.top/Article/details/gttahakkrv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtnzgdlxty.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtllplpxed.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnqzz.top/Article/details/gtpcdsruup.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.aibaodan.cn/Article/details/gtheueczfy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtpfronoml.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.c1oappe.top/Article/details/gtbzleddvt.html

[F12] CSV 读写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtepqtspvv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jlsjyb.cn/Article/details/gtbceoeraj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jqgufenzy.top/Article/details/gtgzxpgqgz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jqgfzy.top/Article/details/gtiqhalwli.html

TS:   // 同上
来源：http://dali.gaohongyu789.top/Article/details/gtduqghthz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuxming.cn/Article/details/gtsvtiaqko.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ivvv.top/Article/details/gtzioztzrg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxinkj.top/Article/details/gtcrxaplkt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yvedp.cn/Article/details/gteqnmqgpl.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtxabsarjd.html

G. 面向对象
来源：http://dali.yuanzhike.top/Article/details/gtepndpvzi.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtnrsmfwvg.html

[G01] 定义类
来源：http://dali.mhx1999.top/Article/details/gtaejnyokm.html

Py:   class User: pass
来源：http://dali.c1oappe.top/Article/details/gtrvaftitc.html

PHP:  class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtmhaqerol.html

JS:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtywekphef.html

TS:   class User { name: string = ""; }
来源：http://dali.pycfn.com/Article/details/gtjidnoetn.html

Java: class User {}
来源：http://dali.yj20258.top/Article/details/gtbpghjjue.html

Go:   type User struct { Name string }
来源：http://dali.kuanghao11.cn/Article/details/gtjzlgyzml.html

Ruby: class User; end
来源：http://dali.pengpengdd.cyou/Article/details/gtjntyutwm.html

C#:   class User {}
来源：http://dali.jqgufenzy.top/Article/details/gtujvreitz.html

[G02] 构造函数
来源：http://dali.tanke756.top/Article/details/gttcxqzeld.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xinyue.icu/Article/details/gteabpxxkq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nanxuanxn.top/Article/details/gtionolyvf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvrheenmv.html

TS:   constructor(public name: string) {}
来源：http://dali.hfpthk.cn/Article/details/gtvpxaeuxm.html

Java: User(String name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gthkkloqik.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yanxiufei.cn/Article/details/gtaalqfafs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sxryk.cn/Article/details/gtfantajwf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtfvtsuyfs.html

[G03] 实例属性
来源：http://dali.ppjwa.cn/Article/details/gtevsdebfi.html

Py:   self.name = "x"
来源：http://dali.cucudq.cn/Article/details/gtwqauvjhl.html

PHP:  public string $name = "x";
来源：http://dali.yueranfly.top/Article/details/gtfmwpswkv.html

JS:   this.name = "x";
来源：http://dali.pycfn.com/Article/details/gttjwtimfp.html

TS:   name: string = "x";
来源：http://dali.hnqzz.top/Article/details/gthjsdsawy.html

Java: private String name;
来源：http://dali.zycfv.cn/Article/details/gtemxoorxe.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.vqdsnc.cn/Article/details/gtlhemxfkb.html

Ruby: @name = "x"
来源：http://dali.yj20258.top/Article/details/gtxfiwsmwf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shzxlz.cn/Article/details/gtxpvkcipc.html

[G04] 定义方法
来源：http://dali.daxiang520.top/Article/details/gtmqtjnlgp.html

Py:   def greet(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gtdsngtmdz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gthxshmhso.html

JS:   greet() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtsuyzghtv.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtpxpkavay.html

Java: String greet() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtqdvourbc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtjjjeitvt.html

Ruby: def greet; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtzcetaaky.html

C#:   public string Greet() => Name;
来源：http://dali.gaohongyu789.top/Article/details/gtwxifvrqm.html

[G05] 继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvggxazuz.html

Py:   class Admin(User): pass
来源：http://dali.ehwqpu.com/Article/details/gtizxjeafr.html

PHP:  class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtlwytlzwe.html

JS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtsaonufzj.html

TS:   class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtqjshkldj.html

Java: class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtiwuwvobk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.bjfxy.top/Article/details/gtjipdaowx.html

Ruby: class Admin < User; end
来源：http://dali.hysaishi.cn/Article/details/gtsjlukqaw.html

C#:   class Admin : User {}
来源：http://dali.cucudq.cn/Article/details/gtwccllyfb.html

[G06] 重写方法
来源：http://dali.hongshengwenyu.top/Article/details/gtbronslfm.html

Py:   def greet(self): return "admin"
来源：http://dali.cheryme.top/Article/details/gtfhpcppjc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtrlduhcvv.html

JS:   greet() { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtugevsogg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtiifrttlv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtuucqruse.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sufxvd.cn/Article/details/gtvvhsbmkv.html

Ruby: def greet; "admin"; end
来源：http://dali.dianchejie.cn/Article/details/gtcibuaesy.html

C#:   public override string Greet() => "admin";
来源：http://dali.nwbrower.top/Article/details/gtrhfenddn.html

[G07] 调用父类方法
来源：http://dali.hywenlv.cn/Article/details/gtixokriry.html

Py:   super().greet()
来源：http://dali.hysaishi.cn/Article/details/gtbryaopcy.html

PHP:  parent::greet();
来源：http://dali.havefunace.top/Article/details/gtnjonfevo.html

JS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gtnztpaqxe.html

TS:   super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtgztcmknc.html

Java: super.greet();
来源：http://dali.daxiang520.top/Article/details/gtfbcnlsji.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gteemklcsh.html

Ruby: super
来源：http://dali.chenzaomai.com/Article/details/gtobszuuwz.html

C#:   base.Greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdrloxcw.html

[G08] 静态方法与属性
来源：http://dali.cucudq.cn/Article/details/gtnumfpfxr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.snrcjt.cn/Article/details/gtrlugephu.html

PHP:  public static function f() {}
来源：http://dali.cqqwz.cn/Article/details/gtyzydbrlt.html

JS:   static f() {}
来源：http://dali.yj20258.top/Article/details/gtlikrsymt.html

TS:   static f(): void {}
来源：http://dali.yj20258888.top/Article/details/gtdayddgeo.html

Java: static void f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtipspshby.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gzhubu.top/Article/details/gtdcfzsley.html

Ruby: def self.f; end
来源：http://dali.pengpengdd.cyou/Article/details/gtxsloaayv.html

C#:   public static void F() {}
来源：http://dali.jianghu66.top/Article/details/gtpinxhttt.html

[G09] 接口 / 抽象类
来源：http://dali.jinghuilouyu.cn/Article/details/gtjownlfoi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hnxiangtu.top/Article/details/gthxnvmbwo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yueranfly.top/Article/details/gtyjqcihty.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ivvv.top/Article/details/gtqkuzogxp.html

TS:   interface Shape { area(): number; }
来源：http://dali.aibaodan.cn/Article/details/gtmcbmvtdx.html

Java: interface Shape { double area(); }
来源：http://dali.birdmap.top/Article/details/gttuxbbuzb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hfpthk.cn/Article/details/gtyaecpsxd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.redwolf501.top/Article/details/gtadalfbvv.html

C#:   interface IShape { double Area(); }
来源：http://dali.havefunace.top/Article/details/gthsizvevk.html

[G10] 访问控制
来源：http://dali.hongshengwenyu.top/Article/details/gtldvmotnw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigufen.top/Article/details/gtqlcgumqs.html

PHP:  public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gtywrlwjfd.html

JS:   #private 字段；其余公开
来源：http://dali.xuetiantiany.cn/Article/details/gtjftcjayl.html

TS:   public / protected / private
来源：http://dali.wangdashe.top/Article/details/gtunaurycb.html

Java: public / protected / private / 默认包级
来源：http://dali.mhx1999.top/Article/details/gtnhtbdusb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nanxinkj.top/Article/details/gtntdyhfra.html

Ruby: public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gtowivfekp.html

C#:   public / protected / private / internal
来源：http://dali.yuxming.cn/Article/details/gtaxtzmhmv.html

[G11] getter / setter
来源：http://dali.shanyushiyangkeji.top/Article/details/gtziuurqgo.html

Py:   @property 与 @x.setter
来源：http://dali.wangshuangyany.cn/Article/details/gtcmnkpxpr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gtzanfwjky.html

JS:   get name() { return this._name; }
来源：http://dali.smart0.xyz/Article/details/gtzivdusla.html

TS:   get name(): string { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gtziafzdgf.html

Java: public String getName() { return name; }
来源：http://dali.meibo888.top/Article/details/gtwglszoni.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gtoizqllqc.html

Ruby: attr_accessor :name
来源：http://dali.zhengqikj.top/Article/details/gtxmphxacd.html

C#:   public string Name { get; set; }
来源：http://dali.bjfxy.top/Article/details/gtgckjtrwx.html

[G12] 对象转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjnwlmmwn.html

Py:   def __str__(self): return self.name
来源：http://dali.chenlongwang.top/Article/details/gtnphofkqg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gtqcjbloqj.html

JS:   toString() { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gtgxxodowm.html

TS:   toString(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gtnvljcocw.html

Java: @Override public String toString() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtjuoahifx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtzxmjyoyi.html

Ruby: def to_s; @name; end
来源：http://dali.cdnleiting.top/Article/details/gtvvlvawsp.html

C#:   public override string ToString() => Name;
来源：http://dali.cdnleiting.top/Article/details/gtihsazgdy.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtyivumbkm.html

Py:   isinstance(u, User)
来源：http://dali.yanxiufei.cn/Article/details/gtcqvfbjaq.html

PHP:  $u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtaqplzoyi.html

JS:   u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtywqaianr.html

TS:   u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtciywehkv.html

Java: u instanceof User
来源：http://dali.ivvv.top/Article/details/gtueptqjui.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hysaishi.cn/Article/details/gtahkgodzz.html

Ruby: u.is_a?(User)
来源：http://dali.jqgufenzy.top/Article/details/gthldqmxjw.html

C#:   u is User
来源：http://dali.ybcxt.top/Article/details/gtdhrftkdh.html

[G14] 数据类 / record
来源：http://dali.gotoacloud.top/Article/details/gtlynognsg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjygnyhig.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenzaomai.com/Article/details/gtxnjenqqn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhengqikj.top/Article/details/gtwcfrpmrn.html

TS:   type User = { name: string; age: number };
来源：http://dali.fzhhl.top/Article/details/gtycqmjxor.html

Java: record User(String name, int age) {}
来源：http://dali.316326.xyz/Article/details/gtcewkipjh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.vqdsnc.cn/Article/details/gtayjboxij.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jiagoushi.top/Article/details/gtnlrqokns.html

C#:   record User(string Name, int Age);
来源：http://dali.yueranfly.top/Article/details/gtlofneqre.html

[G15] 枚举
来源：http://dali.jyoumei.cn/Article/details/gteipcygmq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zycfv.cn/Article/details/gtzopzvkji.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xziqi.cn/Article/details/gtqliwzila.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangtech.top/Article/details/gtadntkuwc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gtjjhikdzq.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenjidiqi.icu/Article/details/gtdpfjutnw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.aizwys.cn/Article/details/gtzzarauom.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgufenzy.top/Article/details/gtrhksqvcz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gtfidexwkx.html

[G16] 对象转数组 / 字典
来源：http://dali.hfpthk.cn/Article/details/gtsetilklu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuxming.cn/Article/details/gtlfhrhhzz.html


<!-- 参考信息 -->