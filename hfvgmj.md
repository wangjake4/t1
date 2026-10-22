代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gttrcdafmp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtdeyinrmw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtnsejaigl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.vqdsnc.cn/Article/details/gtahcwlltb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.feifeiyinyue.top/Article/details/gtkxqfgygt.html

[E19] 多行文本按行拆分
来源：http://dali.hnxiangtu.top/Article/details/gtmvkyolix.html

Py:   s.splitlines()
来源：http://dali.c1oappe.top/Article/details/gtucqqngmd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtuyshqstm.html

JS:   s.split(/\r?\n/)
来源：http://dali.cdnleiting.top/Article/details/gtefhkasuy.html

TS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gtratlrrow.html

Java: s.lines().toList()
来源：http://dali.xinyue.icu/Article/details/gtxdgrgzly.html

Go:   strings.Split(s, "\n")
来源：http://dali.daxiang520.top/Article/details/gttyjukdtx.html

Ruby: s.lines
来源：http://dali.jinghuilouyu.cn/Article/details/gthgvbppjq.html

C#:   s.Split('\n')
来源：http://dali.gogol.net.cn/Article/details/gtzcjkuvjg.html

[E20] 判断字符串是否为空
来源：http://dali.yj20258888.top/Article/details/gtcqolmrsq.html

Py:   if not s:
来源：http://dali.tian-w.cn/Article/details/gtspjqpjhi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenjidiqi.icu/Article/details/gtvtnayiel.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtnbtqmcxv.html

TS:   if (s === "") {}
来源：http://dali.hammf.cn/Article/details/gtvojqrjzj.html

Java: if (s.isEmpty()) {}
来源：http://dali.quarkkingdee.top/Article/details/gtpnzkhepa.html

Go:   if s == "" {}
来源：http://dali.zhiwuduotai.top/Article/details/gtuplzhack.html

Ruby: if s.empty?
来源：http://dali.jinqigufen.top/Article/details/gtqrrebvkx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zdqjudy.top/Article/details/gtrplfjimy.html

[E21] 超长截断加省略号
来源：http://dali.dashuyun.cn/Article/details/gtpwgqmsmr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenlongwang.top/Article/details/gtwlmkdcea.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gtdtpvewsg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcyyuoykg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtblgshapk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtetddkyah.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhiwuduotai.top/Article/details/gtyvxjsiii.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtthzwmpgm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtpjwnkudf.html

[E22] 字节长度与字符长度
来源：http://dali.shzxlz.cn/Article/details/gtsccgdtql.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlybkuuys.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gtlffxgosi.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zdqjudy.top/Article/details/gtokrpbpxv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.haohaochexian.top/Article/details/gtghdqfsex.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jqgfzy.top/Article/details/gtmhfhxxig.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ivvv.top/Article/details/gthzofflae.html

Ruby: s.bytesize;  s.length
来源：http://dali.tianlin.xyz/Article/details/gtekylnmxt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.redwolf501.top/Article/details/gtarslukre.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtnvuwidys.html

F. 文件与目录
来源：http://dali.cqqwz.cn/Article/details/gtcjmupcfr.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtifbsoxtn.html

[F01] 读取整个文件
来源：http://dali.pengpengdd.cyou/Article/details/gtovurjdpn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gzhubu.top/Article/details/gtsdjppits.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtygahbzuh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmcsqyjr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gtkuibxrww.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gtawvrgari.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.meibo888.top/Article/details/gtvqpgqfjx.html

Ruby: File.read("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtokmmqgqm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtjypnjool.html

[F02] 逐行读取文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgalimxg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xuanzx.com/Article/details/gtmlwntidt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrlwphtoz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjvlvxzgu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gtafksaliy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtosairtvf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yueranfly.top/Article/details/gtgwzotmya.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nanxinkj.top/Article/details/gtsrczfjnq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.wangshuangyany.cn/Article/details/gtrvyafycn.html

[F03] 写入文件（覆盖）
来源：http://dali.redwolf501.top/Article/details/gtqibwdsnw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmegjdduz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gtqbbfbbkw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtilxmspan.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gtjsqtigqk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aibaodan.cn/Article/details/gtlqofjspl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.aibaodan.cn/Article/details/gtstzxdshl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.c1oappe.top/Article/details/gtgijhjacq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbqioyab.html

[F04] 追加写入文件
来源：http://dali.hongshengwenyu.top/Article/details/gtkuglfefo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sysykeji.top/Article/details/gtnycaasmj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cheryme.top/Article/details/gtsnrvkugb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tian-w.cn/Article/details/gthqzebtrs.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtmugtjmry.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.vqdsnc.cn/Article/details/gtdgeoanqq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtcznmpwwt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenjidiqi.icu/Article/details/gtieoctzwl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xuanzx.com/Article/details/gtcfovisuh.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigfzy.top/Article/details/gtcsxiwjcg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjjpkhig.html

PHP:  file_exists("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtdapmebuu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtkdxxqzqk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtdhaoxuxt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtbzvydfeo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.kuanghao11.cn/Article/details/gtkwlhsdlk.html

Ruby: File.exist?("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtfloecpxf.html

C#:   File.Exists("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gthhhjrpmx.html

[F06] 删除文件
来源：http://dali.svipenyu.cn/Article/details/gtrkhranql.html

Py:   os.remove("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtfweihnty.html

PHP:  unlink("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtojkzznon.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtkckknbwz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gthqnzjwmd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtpsxykqio.html

Go:   os.Remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtfholkjty.html

Ruby: File.delete("a.txt")
来源：http://dali.yonumen.top/Article/details/gtmjzgcllq.html

C#:   File.Delete("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtymdyxxox.html

[F07] 创建目录（含多级）
来源：http://dali.svipenyu.cn/Article/details/gtpyjfxxqn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jqgufenzy.top/Article/details/gtykiyjasi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtijsfiutc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gttrfkviga.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinghuilouyu.cn/Article/details/gtudnqyaxd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxuanxn.top/Article/details/gtywzurkgs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xylfe.cn/Article/details/gtndjiffim.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hfpthk.cn/Article/details/gtjvdhizmw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.0kj1m.cn/Article/details/gtxwebwveg.html

[F08] 遍历目录
来源：http://dali.hnqzz.top/Article/details/gtekftejow.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.9152youxi.cn/Article/details/gtmwgonjkm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hongshengwenyu.top/Article/details/gtgsotpjck.html

JS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gtqakjzrsk.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinqigufen.top/Article/details/gtjfebktau.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthbycjxzr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yonumen.top/Article/details/gtvdhjojtr.html

Ruby: Dir.children("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtajxfrgrb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guowangkeji.top/Article/details/gtiuadreds.html

[F09] 获取文件大小
来源：http://dali.ybcxt.top/Article/details/gtvypiemyh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sweek.top/Article/details/gtgyoejkdu.html

PHP:  filesize("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtrjywhssl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gtkcedehie.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhiwuduotai.top/Article/details/gtyeqvksut.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gtfuwsahxx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jyoumei.cn/Article/details/gtswajwwqt.html

Ruby: File.size("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtyhmxdwfu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yvedp.cn/Article/details/gtuaptusqj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jiagoushi.top/Article/details/gtidpycadj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtxmljchss.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sweek.top/Article/details/gtkskwgjpr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtfnvjzrdx.html

TS:   path.extname("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gteqgykzbt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nwbrower.top/Article/details/gtbmpwnyjo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtgcrbgdyy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtazocncff.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtvjwfmnbp.html

[F11] 复制与移动文件
来源：http://dali.hnxiangtu.top/Article/details/gtcildevwc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gttcazzluu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ivvv.top/Article/details/gtgavpookh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtvymkjbmw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtibeugijh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ppjwa.cn/Article/details/gtwionjhgo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shuidangran.top/Article/details/gtojgptmte.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtkqkmvxxr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.andypj.xyz/Article/details/gtfecrhpgb.html

[F12] CSV 读写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxrssfhu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zdqjudy.top/Article/details/gtjsxnbyuh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.birdmap.top/Article/details/gtoiuthugq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shangyingyoupin.top/Article/details/gtwymbikbq.html

TS:   // 同上
来源：http://dali.shuidangran.top/Article/details/gtmiybhdrr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj20258888.top/Article/details/gtcllrmnpe.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.dashuyun.cn/Article/details/gtvbxfudjq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxinkj.top/Article/details/gtrpgcjkmm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dashuyun.cn/Article/details/gtzkttqwbd.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtiodkajvs.html

G. 面向对象
来源：http://dali.xuetiantiany.cn/Article/details/gtebtwnxxk.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtbuqywdvd.html

[G01] 定义类
来源：http://dali.cheryme.top/Article/details/gtnlvhhtkk.html

Py:   class User: pass
来源：http://dali.snrcjt.cn/Article/details/gtovkdmomz.html

PHP:  class User {}
来源：http://dali.9152youxi.cn/Article/details/gtiexzbhvf.html

JS:   class User {}
来源：http://dali.fzhhl.top/Article/details/gtmrvgoqju.html

TS:   class User { name: string = ""; }
来源：http://dali.sxryk.cn/Article/details/gtblmwgnmm.html

Java: class User {}
来源：http://dali.shuidangran.top/Article/details/gtksgjvnme.html

Go:   type User struct { Name string }
来源：http://dali.yuxming.cn/Article/details/gtclsdvsec.html

Ruby: class User; end
来源：http://dali.yj202588.top/Article/details/gtyanuhihk.html

C#:   class User {}
来源：http://dali.316326.xyz/Article/details/gtttvxzuut.html

[G02] 构造函数
来源：http://dali.guowangkeji.top/Article/details/gtsmaeccmx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ybcxt.top/Article/details/gtknqrgvkx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.c1oappe.top/Article/details/gtnbrhhkps.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtlbnqsdux.html

TS:   constructor(public name: string) {}
来源：http://dali.ybcxt.top/Article/details/gtisulgzgx.html

Java: User(String name) { this.name = name; }
来源：http://dali.c1oappe.top/Article/details/gtgrrjqnrn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigfzy.top/Article/details/gtwptbvxcd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hywenlv.cn/Article/details/gtbuzeuier.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtzzdvbcxs.html

[G03] 实例属性
来源：http://dali.havefunace.top/Article/details/gtlfgrvnxj.html

Py:   self.name = "x"
来源：http://dali.zdqjudy.top/Article/details/gtqqmjozvi.html

PHP:  public string $name = "x";
来源：http://dali.xuanzx.com/Article/details/gtvvxgovek.html

JS:   this.name = "x";
来源：http://dali.zhixingplan.top/Article/details/gtiitwsnyb.html

TS:   name: string = "x";
来源：http://dali.yangfankeji.com/Article/details/gtxpkwrjkf.html

Java: private String name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfucrtapl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daxiang520.top/Article/details/gtaamfxlhu.html

Ruby: @name = "x"
来源：http://dali.birdmap.top/Article/details/gtgdhpxtze.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.haohaochexian.top/Article/details/gtteagmmoy.html

[G04] 定义方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdbhdeee.html

Py:   def greet(self): return self.name
来源：http://dali.ehwqpu.com/Article/details/gtzxitdmel.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtkiyyyauc.html

JS:   greet() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtcblukukm.html

TS:   greet(): string { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtrfyfmacd.html

Java: String greet() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtprthovhz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpgivujju.html

Ruby: def greet; @name; end
来源：http://dali.zhiwuduotai.top/Article/details/gtejzpnhhf.html

C#:   public string Greet() => Name;
来源：http://dali.yangfankeji.com/Article/details/gtubmahxnn.html

[G05] 继承
来源：http://dali.feifeiyinyue.top/Article/details/gtcxakktza.html

Py:   class Admin(User): pass
来源：http://dali.jyoumei.cn/Article/details/gtupcbhnym.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtnbvalmew.html

JS:   class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtdnjouwwm.html

TS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gthtjdrlvf.html

Java: class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtcrbbvoby.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ivvv.top/Article/details/gtimbclxrl.html

Ruby: class Admin < User; end
来源：http://dali.hysaishi.cn/Article/details/gtcsnbpbmp.html

C#:   class Admin : User {}
来源：http://dali.sysykeji.top/Article/details/gtnqyolllh.html

[G06] 重写方法
来源：http://dali.fengsongda.top/Article/details/gtamolucqw.html

Py:   def greet(self): return "admin"
来源：http://dali.bjfxy.top/Article/details/gtuglobqhb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtigxzyhcv.html

JS:   greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtqbiaaezq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtfxwqzttg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtblvemumz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aibaodan.cn/Article/details/gtaluknqli.html

Ruby: def greet; "admin"; end
来源：http://dali.gaohongyu789.top/Article/details/gtyttqwqcx.html

C#:   public override string Greet() => "admin";
来源：http://dali.ybcxt.top/Article/details/gtfsqibgay.html

[G07] 调用父类方法
来源：http://dali.jyoumei.cn/Article/details/gtrcdtzagw.html

Py:   super().greet()
来源：http://dali.iojbl.cn/Article/details/gttbybnujm.html

PHP:  parent::greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtxtazhtiz.html

JS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gtrturmnhi.html

TS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gtlqqkkfof.html

Java: super.greet();
来源：http://dali.daxiang520.top/Article/details/gtyelhrjji.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.mhx1999.top/Article/details/gtstddvuny.html

Ruby: super
来源：http://dali.zdqjudy.top/Article/details/gtvonerdqp.html

C#:   base.Greet();
来源：http://dali.ehwqpu.com/Article/details/gtcxrashpg.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtuldtrmgo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jlsjyb.cn/Article/details/gtvfenooya.html

PHP:  public static function f() {}
来源：http://dali.nanxinkj.top/Article/details/gtvwkuoliz.html

JS:   static f() {}
来源：http://dali.smart0.xyz/Article/details/gtcqatsrqn.html

TS:   static f(): void {}
来源：http://dali.sxryk.cn/Article/details/gthpmgcioe.html

Java: static void f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gttplepzrs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.aibaodan.cn/Article/details/gtootohrxb.html

Ruby: def self.f; end
来源：http://dali.aibaodan.cn/Article/details/gtvukplbzp.html

C#:   public static void F() {}
来源：http://dali.quarkkingdee.top/Article/details/gtgblncomg.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gtcpshsgmn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.c1oappe.top/Article/details/gtnfoaqqyr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daxiang520.top/Article/details/gtzqwgmklu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daria6918.cn/Article/details/gthonjpesu.html

TS:   interface Shape { area(): number; }
来源：http://dali.zdqjudy.top/Article/details/gtprgarajo.html

Java: interface Shape { double area(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtyrdterld.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daxiang520.top/Article/details/gtoyddxhpf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cashguo.top/Article/details/gtnskvrznc.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrlzsoof.html

[G10] 访问控制
来源：http://dali.hammf.cn/Article/details/gtvxmsukpm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sysykeji.top/Article/details/gtxkgvramo.html

PHP:  public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtxoemjhya.html

JS:   #private 字段；其余公开
来源：http://dali.cucudq.cn/Article/details/gtpxyykaop.html

TS:   public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gthxwgzywr.html

Java: public / protected / private / 默认包级
来源：http://dali.kuanghao11.cn/Article/details/gtgelqhtuf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvererub.html

Ruby: public / protected / private
来源：http://dali.bjfxy.top/Article/details/gtkvvjbdnv.html

C#:   public / protected / private / internal
来源：http://dali.sysykeji.top/Article/details/gtzjqcsezo.html

[G11] getter / setter
来源：http://dali.jiagoushi.top/Article/details/gtiljhdojv.html

Py:   @property 与 @x.setter
来源：http://dali.zhengqikj.top/Article/details/gtjakkuaqw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtxgzupkwc.html

JS:   get name() { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gtlovqckbt.html

TS:   get name(): string { return this._name; }
来源：http://dali.ehwqpu.com/Article/details/gtqfgkokkd.html

Java: public String getName() { return name; }
来源：http://dali.smart0.xyz/Article/details/gtebpiawwu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtbdzihzuj.html

Ruby: attr_accessor :name
来源：http://dali.dianchejie.cn/Article/details/gtoxfkoqgz.html

C#:   public string Name { get; set; }
来源：http://dali.tianlin.xyz/Article/details/gtfmdynmtx.html

[G12] 对象转字符串
来源：http://dali.quarkkingdee.top/Article/details/gteqfnkukw.html

Py:   def __str__(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gtojplyppk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtcxkazhqs.html

JS:   toString() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnkvktsrh.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtginmiqwv.html

Java: @Override public String toString() { return name; }
来源：http://dali.yongpay.top/Article/details/gtqsocxjak.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtddtdhhxx.html

Ruby: def to_s; @name; end
来源：http://dali.havefunace.top/Article/details/gtfrkvteyu.html

C#:   public override string ToString() => Name;
来源：http://dali.jyoumei.cn/Article/details/gtkmtrepxn.html

[G13] 判断对象类型
来源：http://dali.guannengcc.top/Article/details/gtkngzrlku.html

Py:   isinstance(u, User)
来源：http://dali.hongshengwenyu.top/Article/details/gtjuwgtzsw.html

PHP:  $u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtviknomyd.html

JS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtnhtzrymz.html

TS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtfsvicoso.html

Java: u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtwnbugydx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hysaishi.cn/Article/details/gtejxzcneg.html

Ruby: u.is_a?(User)
来源：http://dali.yj20258888.top/Article/details/gtaaogxuum.html

C#:   u is User
来源：http://dali.havefunace.top/Article/details/gtucnzbcec.html

[G14] 数据类 / record
来源：http://dali.sweek.top/Article/details/gtrdjvayfg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xylfe.cn/Article/details/gtodpzfige.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tianlin.xyz/Article/details/gtezzcmuiy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenzaomai.com/Article/details/gthbkoazal.html

TS:   type User = { name: string; age: number };
来源：http://dali.shzxlz.cn/Article/details/gtqivegtup.html

Java: record User(String name, int age) {}
来源：http://dali.jqgfzy.top/Article/details/gtyejuukkr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aizwys.cn/Article/details/gtvmnbhhzr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.0kj1m.cn/Article/details/gtpxsxzepe.html

C#:   record User(string Name, int Age);
来源：http://dali.chenlongwang.top/Article/details/gtaiuxxyul.html

[G15] 枚举
来源：http://dali.andypj.xyz/Article/details/gtkxgcmotu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yuxming.cn/Article/details/gtcghibdbi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yonumen.top/Article/details/gtrflngclc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ppjwa.cn/Article/details/gtjhycyyjn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guannengcc.top/Article/details/gtlatgwwwi.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhongyouzk.top/Article/details/gthitrnniw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.0kj1m.cn/Article/details/gtowsgrbyg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tian-w.cn/Article/details/gtzrvvdnsr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gtrdvezwpg.html

[G16] 对象转数组 / 字典
来源：http://dali.316326.xyz/Article/details/gtmsyndsis.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.snrcjt.cn/Article/details/gtsusivwpe.html

PHP:  get_object_vars($obj);
来源：http://dali.sufxvd.cn/Article/details/gtowvplciu.html

JS:   Object.entries(obj)
来源：http://dali.jlsjyb.cn/Article/details/gthwddwluk.html

TS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthawsilmd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gaohongyu789.top/Article/details/gtsmbrgyxf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hnqzz.top/Article/details/gtntyojphv.html

Ruby: obj.instance_variables
来源：http://dali.tanke756.top/Article/details/gtxcostzlh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gtnjsxrthn.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtcoiarrob.html


<!-- 参考信息 -->