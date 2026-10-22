代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.quarkkingdee.top/Article/details/gttwouyvut.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yuxming.cn/Article/details/gtblvhtvfh.html

Ruby: s.capitalize
来源：http://dali.yvedp.cn/Article/details/gtwiiuwjcw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sysykeji.top/Article/details/gtiouyzyou.html

[E18] 模板占位符替换
来源：http://dali.yanxiufei.cn/Article/details/gtrxbnpchg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ehwqpu.com/Article/details/gtkwunsssf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinqigufen.top/Article/details/gtmjdppbbb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ivvv.top/Article/details/gtypjpwcev.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrcxpyky.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtgrhuibyz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtzzamhrhr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yanxiufei.cn/Article/details/gtbbnxiqto.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ydzc1.top/Article/details/gtcnannnzw.html

[E19] 多行文本按行拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmndxsyf.html

Py:   s.splitlines()
来源：http://dali.daria6918.cn/Article/details/gtuvsczjxt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.smart0.xyz/Article/details/gthietlnoi.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhiwuduotai.top/Article/details/gtmchyilce.html

TS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gtgrdujdzz.html

Java: s.lines().toList()
来源：http://dali.sxryk.cn/Article/details/gtpvkpycix.html

Go:   strings.Split(s, "\n")
来源：http://dali.yueranfly.top/Article/details/gtgtlkscwz.html

Ruby: s.lines
来源：http://dali.vqdsnc.cn/Article/details/gtvuqgobhq.html

C#:   s.Split('\n')
来源：http://dali.yangfankeji.com/Article/details/gtkussonxw.html

[E20] 判断字符串是否为空
来源：http://dali.snrcjt.cn/Article/details/gtrhyiohru.html

Py:   if not s:
来源：http://dali.cdnleiting.top/Article/details/gtbezynwgr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xinyue.icu/Article/details/gthvcngtgn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xuanzx.com/Article/details/gterncovjl.html

TS:   if (s === "") {}
来源：http://dali.ybcxt.top/Article/details/gthclyfdzm.html

Java: if (s.isEmpty()) {}
来源：http://dali.hysaishi.cn/Article/details/gtplgwsewc.html

Go:   if s == "" {}
来源：http://dali.feifeiyinyue.top/Article/details/gtyyzwvnsy.html

Ruby: if s.empty?
来源：http://dali.xuanzx.com/Article/details/gtyvfijpbj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hammf.cn/Article/details/gtzlvvucge.html

[E21] 超长截断加省略号
来源：http://dali.ydzc1.top/Article/details/gtvnscxvyi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sweek.top/Article/details/gtsfnyallk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gttqgucftk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtebuixbnu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtyjpifvye.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtvwrwhrqh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinghuilouyu.cn/Article/details/gtoldzanxz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtgwmqkqfp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.mhx1999.top/Article/details/gthmdctgxj.html

[E22] 字节长度与字符长度
来源：http://dali.316326.xyz/Article/details/gtxsplgydw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gzhubu.top/Article/details/gtbujhhnfc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gtpmkbybbx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sufxvd.cn/Article/details/gtbgrevfzw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gticfvljxw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.dianchejie.cn/Article/details/gtveunuqqs.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj20258.top/Article/details/gtctcxqlzw.html

Ruby: s.bytesize;  s.length
来源：http://dali.havefunace.top/Article/details/gttyocsnrj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guannengcc.top/Article/details/gtqwpnsxoc.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtdpwfgtop.html

F. 文件与目录
来源：http://dali.mhx1999.top/Article/details/gtmatmqvss.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtnpjishep.html

[F01] 读取整个文件
来源：http://dali.cdnleiting.top/Article/details/gtajhgfizw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gotoacloud.top/Article/details/gtfknxkstv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tanke756.top/Article/details/gtjyuwtgqu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cucudq.cn/Article/details/gtwndapayl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gtnbbitxza.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtpldcwpjo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sufxvd.cn/Article/details/gtcjrskmja.html

Ruby: File.read("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtfjznbpwv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hammf.cn/Article/details/gtdatpsnrc.html

[F02] 逐行读取文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxesnsaf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hywenlv.cn/Article/details/gtwbulkdxu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hfpthk.cn/Article/details/gtubpbnoee.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gtogvfnmkq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gtnyyhfbom.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gtmvdmforx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinqigufen.top/Article/details/gtkccttypn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ivvv.top/Article/details/gtmfzlfwho.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.feifeiyinyue.top/Article/details/gtiqpdiihf.html

[F03] 写入文件（覆盖）
来源：http://dali.zhongyouzk.top/Article/details/gtlpkeikkx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yvedp.cn/Article/details/gthydzsagp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gtjmhdlvmv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gtvbiwnxaf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gtazjeuhmb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shuidangran.top/Article/details/gtupodvbio.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jqgufenzy.top/Article/details/gteigyfjxw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigfzy.top/Article/details/gtkqpubybm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhixingplan.top/Article/details/gtjklzqess.html

[F04] 追加写入文件
来源：http://dali.tanke756.top/Article/details/gtolmoghcr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ehwqpu.com/Article/details/gtvvrzdisw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yueranfly.top/Article/details/gtljfbuajh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gtogyxsamc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tianlin.xyz/Article/details/gtdxbrqylb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.bjfxy.top/Article/details/gthlchhebo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhixingplan.top/Article/details/gtyxnzrorj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.vqdsnc.cn/Article/details/gtmjywqiah.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyijvitym.html

[F05] 判断文件或目录是否存在
来源：http://dali.havefunace.top/Article/details/gtckxmfnqq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tanke756.top/Article/details/gtjvkbagrd.html

PHP:  file_exists("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtpbjbanqd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtqxalyrhd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtxiwkwtzh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtgqcrfkqn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gtwezlmoxo.html

Ruby: File.exist?("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtjjasuhlq.html

C#:   File.Exists("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtgyttvtmt.html

[F06] 删除文件
来源：http://dali.sxryk.cn/Article/details/gtimgovctg.html

Py:   os.remove("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtmuhajezw.html

PHP:  unlink("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtbnjskuyj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtoxtsgmpt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtnilkildj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtcyhbfyvs.html

Go:   os.Remove("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtwmtjcsqo.html

Ruby: File.delete("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtlwrnbofq.html

C#:   File.Delete("a.txt");
来源：http://dali.sysykeji.top/Article/details/gthplihyus.html

[F07] 创建目录（含多级）
来源：http://dali.chenlongwang.top/Article/details/gtmgixxjxb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jqgufenzy.top/Article/details/gtucecylmp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gtgmbqrwyb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzvncdgjj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwtfegerg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.mhx1999.top/Article/details/gtwprhioyo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.haohaochexian.top/Article/details/gtrkkvqzvc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zdqjudy.top/Article/details/gtnijgcwej.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daxiang520.top/Article/details/gtldkczqfl.html

[F08] 遍历目录
来源：http://dali.sufxvd.cn/Article/details/gtsyulycov.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cqqwz.cn/Article/details/gtrsogqvri.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jlsjyb.cn/Article/details/gtwnurevkc.html

JS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gtcjehuiqx.html

TS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gtabzuqazt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gtjszvmktq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gzhubu.top/Article/details/gthoimbtqk.html

Ruby: Dir.children("dir")
来源：http://dali.fzhhl.top/Article/details/gtddhbnekl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tian-w.cn/Article/details/gtmdsmkmlk.html

[F09] 获取文件大小
来源：http://dali.vqdsnc.cn/Article/details/gtiwhcueil.html

Py:   os.path.getsize("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gttrfmkuby.html

PHP:  filesize("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtpqgumisp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gthvqujifl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hywenlv.cn/Article/details/gtdiqawnxv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtbacyuqme.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gaohongyu789.top/Article/details/gtxytjuerb.html

Ruby: File.size("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtnznsdkmg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tianlin.xyz/Article/details/gtzvbgpfdw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hfpthk.cn/Article/details/gtmtvgpbht.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtcmjzeljd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtstfprrzo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtooyrwcci.html

TS:   path.extname("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtlzdtmohr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.birdmap.top/Article/details/gtdqchaajh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtdbkyexgi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtaploitvt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gthxfabeed.html

[F11] 复制与移动文件
来源：http://dali.yj20258.top/Article/details/gtzbvweetm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtwgnipwrg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fzhhl.top/Article/details/gtdkrwuoqc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtipavuijq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtbqbaxeor.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.haohaochexian.top/Article/details/gtiepollbu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.smart0.xyz/Article/details/gtwufeoadp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtvwvttxne.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yuxming.cn/Article/details/gtkxtkfxpr.html

[F12] CSV 读写
来源：http://dali.smart0.xyz/Article/details/gtjiwdzcei.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yanxiufei.cn/Article/details/gttjmmyiqx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shangyingyoupin.top/Article/details/gtajzffpoq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.feifeiyinyue.top/Article/details/gthztydkij.html

TS:   // 同上
来源：http://dali.0kj1m.cn/Article/details/gtwvisucrq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuanzx.com/Article/details/gtlkzpuaix.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nanxuanxn.top/Article/details/gthmcihxdr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gtqmaeipqp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gtyklzfpbh.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gthdixbyqs.html

G. 面向对象
来源：http://dali.jqgufenzy.top/Article/details/gtyeqgvsgf.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtacflwnjx.html

[G01] 定义类
来源：http://dali.jinqigufen.top/Article/details/gtodxdalju.html

Py:   class User: pass
来源：http://dali.xuetiantiany.cn/Article/details/gtqdsfxtug.html

PHP:  class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtqoifatsd.html

JS:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gtdhoeachi.html

TS:   class User { name: string = ""; }
来源：http://dali.shangyingyoupin.top/Article/details/gtccnhnkyf.html

Java: class User {}
来源：http://dali.zdqjudy.top/Article/details/gtgoaubowk.html

Go:   type User struct { Name string }
来源：http://dali.havefunace.top/Article/details/gtejbgoink.html

Ruby: class User; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrejqxcta.html

C#:   class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtqqqjzatv.html

[G02] 构造函数
来源：http://dali.yanxiufei.cn/Article/details/gtgpjvjijx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.redwolf501.top/Article/details/gtjvjixahd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinqigufen.top/Article/details/gtzbunbxtv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmupgmbzs.html

TS:   constructor(public name: string) {}
来源：http://dali.cqqwz.cn/Article/details/gtgwxfayum.html

Java: User(String name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gttryqcalk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ppjwa.cn/Article/details/gttskgnmtl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ybcxt.top/Article/details/gtaotpvtlc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sufxvd.cn/Article/details/gtuphzxvhh.html

[G03] 实例属性
来源：http://dali.tanke756.top/Article/details/gtvxpdzyxu.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gtthacmvxs.html

PHP:  public string $name = "x";
来源：http://dali.aibaodan.cn/Article/details/gtfcvwngbw.html

JS:   this.name = "x";
来源：http://dali.yvedp.cn/Article/details/gtnfccfitz.html

TS:   name: string = "x";
来源：http://dali.cashguo.top/Article/details/gtulouziyz.html

Java: private String name;
来源：http://dali.cdnleiting.top/Article/details/gtmavtujku.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aizwys.cn/Article/details/gtuqpbbudq.html

Ruby: @name = "x"
来源：http://dali.hammf.cn/Article/details/gtofiisotn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj20258888.top/Article/details/gtnuomyrly.html

[G04] 定义方法
来源：http://dali.redwolf501.top/Article/details/gtuqbowngi.html

Py:   def greet(self): return self.name
来源：http://dali.ydzc1.top/Article/details/gtahtpnfhg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gtqsdelmxn.html

JS:   greet() { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtokjtfexp.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnxzpnttf.html

Java: String greet() { return name; }
来源：http://dali.birdmap.top/Article/details/gtvqkuimfn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtrygtmpoi.html

Ruby: def greet; @name; end
来源：http://dali.yonumen.top/Article/details/gtjbxiinso.html

C#:   public string Greet() => Name;
来源：http://dali.xziqi.cn/Article/details/gtdlzzfmil.html

[G05] 继承
来源：http://dali.guannengcc.top/Article/details/gtjhnyaopm.html

Py:   class Admin(User): pass
来源：http://dali.smart0.xyz/Article/details/gtyoroywpv.html

PHP:  class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtqqolcpzq.html

JS:   class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtwpgeyrsy.html

TS:   class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtueiptaty.html

Java: class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtxchgycgr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tianlin.xyz/Article/details/gtaoppbtne.html

Ruby: class Admin < User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiibuanyy.html

C#:   class Admin : User {}
来源：http://dali.kuanghao11.cn/Article/details/gtccryzwgt.html

[G06] 重写方法
来源：http://dali.daxiang520.top/Article/details/gtcxrrytjj.html

Py:   def greet(self): return "admin"
来源：http://dali.hfpthk.cn/Article/details/gtguwrqyyw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtpehcexkx.html

JS:   greet() { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtzvvzbihd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtugcmehge.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gttwrbyjrg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yuanzhike.top/Article/details/gtoiayfabc.html

Ruby: def greet; "admin"; end
来源：http://dali.quarkkingdee.top/Article/details/gtpumqogef.html

C#:   public override string Greet() => "admin";
来源：http://dali.bjfxy.top/Article/details/gtxczwsksz.html

[G07] 调用父类方法
来源：http://dali.xuanzx.com/Article/details/gtwuwydmvy.html

Py:   super().greet()
来源：http://dali.pycfn.com/Article/details/gtixpajrft.html

PHP:  parent::greet();
来源：http://dali.ppjwa.cn/Article/details/gtttgokojr.html

JS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gtbtbojwue.html

TS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gtzlnjwpnn.html

Java: super.greet();
来源：http://dali.shuidangran.top/Article/details/gtmswmyvsg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvkiexqn.html

Ruby: super
来源：http://dali.daria6918.cn/Article/details/gtsjsfdgsf.html

C#:   base.Greet();
来源：http://dali.zdqjudy.top/Article/details/gthfdtywdp.html

[G08] 静态方法与属性
来源：http://dali.svipenyu.cn/Article/details/gttdbijvbc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ppjwa.cn/Article/details/gtgmmumvlj.html

PHP:  public static function f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtznoiopbi.html

JS:   static f() {}
来源：http://dali.jqgfzy.top/Article/details/gtrdcbbray.html

TS:   static f(): void {}
来源：http://dali.meibo888.top/Article/details/gtorfivxtv.html

Java: static void f() {}
来源：http://dali.kuanghao11.cn/Article/details/gtvxklllro.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gaohongyu789.top/Article/details/gtnbbfzwbb.html

Ruby: def self.f; end
来源：http://dali.daria6918.cn/Article/details/gtxzdozbnm.html

C#:   public static void F() {}
来源：http://dali.birdmap.top/Article/details/gtudddhnoi.html

[G09] 接口 / 抽象类
来源：http://dali.ybcxt.top/Article/details/gtwhvquqno.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ybcxt.top/Article/details/gtncaznotk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gaohongyu789.top/Article/details/gthiggkblt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenzaomai.com/Article/details/gtcrrmdxzb.html

TS:   interface Shape { area(): number; }
来源：http://dali.jqgufenzy.top/Article/details/gtgxcslgkz.html

Java: interface Shape { double area(); }
来源：http://dali.cucudq.cn/Article/details/gtrqlmlnum.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daria6918.cn/Article/details/gtpoylvnsr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fzhhl.top/Article/details/gtycbjpqeb.html

C#:   interface IShape { double Area(); }
来源：http://dali.hysaishi.cn/Article/details/gthjrwsjiy.html

[G10] 访问控制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnirnbbwn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.birdmap.top/Article/details/gtxtqxdvfc.html

PHP:  public / protected / private
来源：http://dali.hammf.cn/Article/details/gttroessxq.html

JS:   #private 字段；其余公开
来源：http://dali.ydzc1.top/Article/details/gtiunvcnht.html

TS:   public / protected / private
来源：http://dali.hammf.cn/Article/details/gtpoekbjkc.html

Java: public / protected / private / 默认包级
来源：http://dali.gaohongyu789.top/Article/details/gthumceemg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbufwyadn.html

Ruby: public / protected / private
来源：http://dali.ydzc1.top/Article/details/gtrbzvpuew.html

C#:   public / protected / private / internal
来源：http://dali.bjfxy.top/Article/details/gtmoetzfoa.html

[G11] getter / setter
来源：http://dali.chenzaomai.com/Article/details/gtnlrohbpc.html

Py:   @property 与 @x.setter
来源：http://dali.hammf.cn/Article/details/gtgbwfjpro.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtffbudjrg.html

JS:   get name() { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gtsqntjmdp.html

TS:   get name(): string { return this._name; }
来源：http://dali.zycfv.cn/Article/details/gtsarfvppf.html

Java: public String getName() { return name; }
来源：http://dali.yj20258.top/Article/details/gtrixnmpyw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gthhhahgnp.html

Ruby: attr_accessor :name
来源：http://dali.hnqzz.top/Article/details/gtbakghlth.html

C#:   public string Name { get; set; }
来源：http://dali.jyoumei.cn/Article/details/gtzcdjfwxd.html

[G12] 对象转字符串
来源：http://dali.yongpay.top/Article/details/gtbyzzpkku.html

Py:   def __str__(self): return self.name
来源：http://dali.316326.xyz/Article/details/gtveroxngp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gtkahnviht.html

JS:   toString() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtwzysffgx.html

TS:   toString(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gthfjxqayk.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtazqlcgtx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gthxjqrjfn.html

Ruby: def to_s; @name; end
来源：http://dali.pycfn.com/Article/details/gtgqxphzlh.html

C#:   public override string ToString() => Name;
来源：http://dali.guannengcc.top/Article/details/gtojdtlvoy.html

[G13] 判断对象类型
来源：http://dali.dianchejie.cn/Article/details/gtnhatdgsd.html

Py:   isinstance(u, User)
来源：http://dali.jyoumei.cn/Article/details/gtdmyulcvr.html

PHP:  $u instanceof User
来源：http://dali.cucudq.cn/Article/details/gthqtkwexq.html

JS:   u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtbboppsqd.html

TS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtznujafnb.html

Java: u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtmmedjkge.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pengpengdd.cyou/Article/details/gtccpwuobi.html

Ruby: u.is_a?(User)
来源：http://dali.dianchejie.cn/Article/details/gtsdnuopcz.html

C#:   u is User
来源：http://dali.cdnleiting.top/Article/details/gtwqgsjbtu.html

[G14] 数据类 / record
来源：http://dali.mhx1999.top/Article/details/gtxzlcnjxm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cheryme.top/Article/details/gttcdlkgfx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aizwys.cn/Article/details/gtipgtjrqx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sufxvd.cn/Article/details/gteaqdaqux.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxkfzroe.html

Java: record User(String name, int age) {}
来源：http://dali.hnxiangtu.top/Article/details/gtxvgolphl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yvedp.cn/Article/details/gtleehfpkc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gogol.net.cn/Article/details/gtqykbpbkt.html

C#:   record User(string Name, int Age);
来源：http://dali.bjfxy.top/Article/details/gttjzajlbs.html

[G15] 枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvldlqsgu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nwbrower.top/Article/details/gtmwkhkasm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jqgufenzy.top/Article/details/gtwannatua.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlnsszelh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.bjfxy.top/Article/details/gtjbexnpwf.html

Java: enum Color { RED, GREEN }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtariwiqxb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomeozxug.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zycfv.cn/Article/details/gtpjddhfmw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkazkpycs.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigufen.top/Article/details/gtqhhpykdb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.snrcjt.cn/Article/details/gtizacaqwf.html


<!-- 参考信息 -->