代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nanxinkj.top/Article/details/gtwsvnuugp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtnjqcwiak.html

Ruby: s.capitalize
来源：http://dali.fengsongda.top/Article/details/gtdptnfwrz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.aizwys.cn/Article/details/gtuzfkcelc.html

[E18] 模板占位符替换
来源：http://dali.birdmap.top/Article/details/gtvhvrgond.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guowangkeji.top/Article/details/gtvvndgydj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gtoybmcbli.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtlwdtxzdq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtizmajpaa.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtwlqbsuwz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtjbqdtvec.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkfyareer.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yonumen.top/Article/details/gtzgiorljj.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gtegqasrgh.html

Py:   s.splitlines()
来源：http://dali.cdnleiting.top/Article/details/gtnigutyne.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pycfn.com/Article/details/gtpppxrulx.html

JS:   s.split(/\r?\n/)
来源：http://dali.cheryme.top/Article/details/gtuoxgdbga.html

TS:   s.split(/\r?\n/)
来源：http://dali.jyoumei.cn/Article/details/gtyfpavwjd.html

Java: s.lines().toList()
来源：http://dali.hfpthk.cn/Article/details/gtnhbvjtqx.html

Go:   strings.Split(s, "\n")
来源：http://dali.shuidangran.top/Article/details/gtgqzrdeqi.html

Ruby: s.lines
来源：http://dali.daxiang520.top/Article/details/gtzcchnsce.html

C#:   s.Split('\n')
来源：http://dali.andypj.xyz/Article/details/gthzmhmdyv.html

[E20] 判断字符串是否为空
来源：http://dali.shangyingyoupin.top/Article/details/gtezuxeccj.html

Py:   if not s:
来源：http://dali.fzhhl.top/Article/details/gtqdkusxng.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj20258888.top/Article/details/gtgwupgrpr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj202588.top/Article/details/gthpzrqpof.html

TS:   if (s === "") {}
来源：http://dali.jiagoushi.top/Article/details/gtpjusnmwe.html

Java: if (s.isEmpty()) {}
来源：http://dali.sufxvd.cn/Article/details/gtutjlnhaf.html

Go:   if s == "" {}
来源：http://dali.redwolf501.top/Article/details/gtruiqvdra.html

Ruby: if s.empty?
来源：http://dali.andypj.xyz/Article/details/gtzlffxirw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gaohongyu789.top/Article/details/gtbmxwqwem.html

[E21] 超长截断加省略号
来源：http://dali.xinyue.icu/Article/details/gtewfzwnmg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenzaomai.com/Article/details/gtowrwgfca.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gtizmypvlx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtxszmhqbc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtvbpinxrx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtvdzrwngh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aibaodan.cn/Article/details/gtivahoxnv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtcvrozups.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtreibjpch.html

[E22] 字节长度与字符长度
来源：http://dali.haohaochexian.top/Article/details/gtynfqmlaz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.kuanghao11.cn/Article/details/gtnmnmjsdm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtfqefwtwe.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkmkjoozm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtkxeofkpi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hywenlv.cn/Article/details/gtjbdkuxmy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.birdmap.top/Article/details/gtlyulrfnc.html

Ruby: s.bytesize;  s.length
来源：http://dali.hywenlv.cn/Article/details/gtafnqrtrj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gtylmvsrlk.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtpjfumnsv.html

F. 文件与目录
来源：http://dali.yj20258888.top/Article/details/gtpitibtqy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gttforhbsx.html

[F01] 读取整个文件
来源：http://dali.shangyingyoupin.top/Article/details/gthixkkbnq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhiwuduotai.top/Article/details/gtqlkrbcir.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj20258.top/Article/details/gtnaaqjaty.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhengqikj.top/Article/details/gtjgijacxd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gtpkhzpheb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtmuwccika.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.vqdsnc.cn/Article/details/gtxqzuevvx.html

Ruby: File.read("a.txt")
来源：http://dali.yj20258.top/Article/details/gthxymwmsw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtwsrriqft.html

[F02] 逐行读取文件
来源：http://dali.shzxlz.cn/Article/details/gtdlifmuoi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.andypj.xyz/Article/details/gtsoupzbvc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sweek.top/Article/details/gtpevbyqlk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258888.top/Article/details/gtqnzmwiof.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gtxneoimpi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gtxtormlhx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.havefunace.top/Article/details/gtxbemvubf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.aibaodan.cn/Article/details/gtdojpkird.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.meibo888.top/Article/details/gtfomkypeq.html

[F03] 写入文件（覆盖）
来源：http://dali.dashuyun.cn/Article/details/gtoqoblwsy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenjidiqi.icu/Article/details/gthvtfydjo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.guannengcc.top/Article/details/gtvcqlxosa.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gtjihgoxgi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gtehahgepm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhixingplan.top/Article/details/gtiqtqrxrc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258.top/Article/details/gtkzrtyaoj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hongshengwenyu.top/Article/details/gtqpwrwnpt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gtqmuvjvcy.html

[F04] 追加写入文件
来源：http://dali.gogol.net.cn/Article/details/gtrtbhzctl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtaieouuwq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhongyouzk.top/Article/details/gtqeoodmtr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gtuepljpxj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hywenlv.cn/Article/details/gtiejapjkm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xziqi.cn/Article/details/gtlrqkvmxs.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtzqzlyybc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuanzhike.top/Article/details/gtxevdhwuo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinghuilouyu.cn/Article/details/gtwgceyvnh.html

[F05] 判断文件或目录是否存在
来源：http://dali.bjfxy.top/Article/details/gtpeaxbvjc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.wangdashe.top/Article/details/gtpyehxzag.html

PHP:  file_exists("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtlljeiwgm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtsilsinmf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtoagdtlqk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtinpzguxh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.redwolf501.top/Article/details/gtuotctvlj.html

Ruby: File.exist?("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtjedlrpqm.html

C#:   File.Exists("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtygteqlpb.html

[F06] 删除文件
来源：http://dali.tanke756.top/Article/details/gtfjbxxkvb.html

Py:   os.remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtuximhkcr.html

PHP:  unlink("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtkwnggkas.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtimeslpyq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtvgsgktgb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtxpdxzlmo.html

Go:   os.Remove("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtymkeitzr.html

Ruby: File.delete("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtvwgxdvjm.html

C#:   File.Delete("a.txt");
来源：http://dali.wangdashe.top/Article/details/gteonyghvc.html

[F07] 创建目录（含多级）
来源：http://dali.sufxvd.cn/Article/details/gttvzrjlhu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jlsjyb.cn/Article/details/gtfwfwsqfk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgfzy.top/Article/details/gtdiguummy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.bjfxy.top/Article/details/gtszpxyvvq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hongshengwenyu.top/Article/details/gtioevwawc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xziqi.cn/Article/details/gtwwjjcqlo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.316326.xyz/Article/details/gtomnuovop.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cashguo.top/Article/details/gtxrmnkxvy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenlongwang.top/Article/details/gtuhtchnii.html

[F08] 遍历目录
来源：http://dali.cdnleiting.top/Article/details/gttasobyky.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhiwuduotai.top/Article/details/gtgwnclzim.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hywenlv.cn/Article/details/gtzvuszgla.html

JS:   fs.readdirSync("dir")
来源：http://dali.yonumen.top/Article/details/gtthukxlbo.html

TS:   fs.readdirSync("dir")
来源：http://dali.ivvv.top/Article/details/gtnmtvnzox.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gtziidnnby.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhengqikj.top/Article/details/gtwslwhluf.html

Ruby: Dir.children("dir")
来源：http://dali.daria6918.cn/Article/details/gtkmatliiv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gogol.net.cn/Article/details/gtxzvgoyvo.html

[F09] 获取文件大小
来源：http://dali.xylfe.cn/Article/details/gtcysrdlwg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtyofjgdct.html

PHP:  filesize("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtwtzpxugf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnxiangtu.top/Article/details/gtuilrthad.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gotoacloud.top/Article/details/gtzczjrqgm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtvcxyvlje.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.fzhhl.top/Article/details/gttwczknjm.html

Ruby: File.size("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtajjtoqvj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.dashuyun.cn/Article/details/gtuyataxog.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigfzy.top/Article/details/gtjhjsnayb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtakzpklwc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sweek.top/Article/details/gtukxegqfi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtscmsmrvl.html

TS:   path.extname("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtshvckkzk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hysaishi.cn/Article/details/gtrlexieij.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtoxdpspjb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtusxgcanp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtwwclroea.html

[F11] 复制与移动文件
来源：http://dali.zhongyouzk.top/Article/details/gtseniirrw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gttpulwsyq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hywenlv.cn/Article/details/gtuuxcrwkq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtmnkliovw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtqwaxrzli.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnqzz.top/Article/details/gtrewdbnze.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtufaqlesy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtenljsvsg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.mhx1999.top/Article/details/gtvhuspzsu.html

[F12] CSV 读写
来源：http://dali.svipenyu.cn/Article/details/gtlhsggffc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.0kj1m.cn/Article/details/gtgfhroyzh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.dashuyun.cn/Article/details/gtoiejeqpj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.9152youxi.cn/Article/details/gtmjkkmzjr.html

TS:   // 同上
来源：http://dali.yj20258888.top/Article/details/gteqgfdklr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.mhx1999.top/Article/details/gtgyqxegwh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.0kj1m.cn/Article/details/gtlsbvgsbr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ppjwa.cn/Article/details/gtdemqzxwm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cqqwz.cn/Article/details/gtvyzgfnqf.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtoquybkfk.html

G. 面向对象
来源：http://dali.haohaochexian.top/Article/details/gttfbphbqn.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtlaqwvvhu.html

[G01] 定义类
来源：http://dali.cdnleiting.top/Article/details/gtxdbdqhyx.html

Py:   class User: pass
来源：http://dali.guannengcc.top/Article/details/gtuynywyml.html

PHP:  class User {}
来源：http://dali.daria6918.cn/Article/details/gtrmslhvqu.html

JS:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gtulhtdocf.html

TS:   class User { name: string = ""; }
来源：http://dali.dashuyun.cn/Article/details/gtltycakiu.html

Java: class User {}
来源：http://dali.ydzc1.top/Article/details/gtgamyrjyk.html

Go:   type User struct { Name string }
来源：http://dali.redwolf501.top/Article/details/gtyowmtgqj.html

Ruby: class User; end
来源：http://dali.ppjwa.cn/Article/details/gtbflrtixt.html

C#:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gttswgohhf.html

[G02] 构造函数
来源：http://dali.gzhubu.top/Article/details/gtpdbnopow.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jiagoushi.top/Article/details/gtarjvvznt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ydzc1.top/Article/details/gtiyouguyq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gtlysmxdex.html

TS:   constructor(public name: string) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtxvwhceyv.html

Java: User(String name) { this.name = name; }
来源：http://dali.fzhhl.top/Article/details/gthvhpeuak.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xuetiantiany.cn/Article/details/gthujbxeor.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.bjfxy.top/Article/details/gtcadmigel.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pycfn.com/Article/details/gtlibcnelv.html

[G03] 实例属性
来源：http://dali.c1oappe.top/Article/details/gtodnaamss.html

Py:   self.name = "x"
来源：http://dali.andypj.xyz/Article/details/gtagbnejdp.html

PHP:  public string $name = "x";
来源：http://dali.shzxlz.cn/Article/details/gtnvgnzwwp.html

JS:   this.name = "x";
来源：http://dali.nwbrower.top/Article/details/gtozwnnhry.html

TS:   name: string = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkerhsdfs.html

Java: private String name;
来源：http://dali.cashguo.top/Article/details/gtwybleewk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.havefunace.top/Article/details/gtanlzqkin.html

Ruby: @name = "x"
来源：http://dali.chenzaomai.com/Article/details/gtnuapoevz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtrkhbxsyv.html

[G04] 定义方法
来源：http://dali.jinqigufen.top/Article/details/gtisljibef.html

Py:   def greet(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gtpkequvtt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gthntxesjt.html

JS:   greet() { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtcrpilfes.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrqtimjvt.html

Java: String greet() { return name; }
来源：http://dali.cashguo.top/Article/details/gtbddekhin.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtnxnsbkyp.html

Ruby: def greet; @name; end
来源：http://dali.chenzaomai.com/Article/details/gtnciasfux.html

C#:   public string Greet() => Name;
来源：http://dali.xuanzx.com/Article/details/gtfykzlbwi.html

[G05] 继承
来源：http://dali.birdmap.top/Article/details/gtggsomjkv.html

Py:   class Admin(User): pass
来源：http://dali.daxiang520.top/Article/details/gthrmkczvq.html

PHP:  class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtmojsxohh.html

JS:   class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtizdxmkwy.html

TS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtodqertns.html

Java: class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtzocgihhr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.dashuyun.cn/Article/details/gtqywswkba.html

Ruby: class Admin < User; end
来源：http://dali.sxryk.cn/Article/details/gtvddzcmiq.html

C#:   class Admin : User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtoqkaiumo.html

[G06] 重写方法
来源：http://dali.pycfn.com/Article/details/gtnvffbdsn.html

Py:   def greet(self): return "admin"
来源：http://dali.kuanghao11.cn/Article/details/gthhfisquv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtrgryours.html

JS:   greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gteszmwdpd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtwsxvjinf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtnrpatuqu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.birdmap.top/Article/details/gtoyqaxnaq.html

Ruby: def greet; "admin"; end
来源：http://dali.zhongyouzk.top/Article/details/gtbrwihwkk.html

C#:   public override string Greet() => "admin";
来源：http://dali.gzhubu.top/Article/details/gtpgvtxvce.html

[G07] 调用父类方法
来源：http://dali.316326.xyz/Article/details/gtrbochtpr.html

Py:   super().greet()
来源：http://dali.yonumen.top/Article/details/gtlbhvlnok.html

PHP:  parent::greet();
来源：http://dali.jlsjyb.cn/Article/details/gtmdqscxwf.html

JS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gtrksqenxz.html

TS:   super.greet();
来源：http://dali.chenlongwang.top/Article/details/gtosodlkxj.html

Java: super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gtfkfnuokz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dashuyun.cn/Article/details/gtsepsobqj.html

Ruby: super
来源：http://dali.jinyuanbaomall.cn/Article/details/gtavitcnlf.html

C#:   base.Greet();
来源：http://dali.yangfankeji.com/Article/details/gtpfcjindk.html

[G08] 静态方法与属性
来源：http://dali.smart0.xyz/Article/details/gtgrszfpmu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yanxiufei.cn/Article/details/gtfvjzyjjy.html

PHP:  public static function f() {}
来源：http://dali.yueranfly.top/Article/details/gtiozhjery.html

JS:   static f() {}
来源：http://dali.svipenyu.cn/Article/details/gtyjwbtxsr.html

TS:   static f(): void {}
来源：http://dali.hongshengwenyu.top/Article/details/gtfmvqprdl.html

Java: static void f() {}
来源：http://dali.zhoulong.xyz/Article/details/gttcurplju.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gtzgomfujm.html

Ruby: def self.f; end
来源：http://dali.ydzc1.top/Article/details/gtifchoscd.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gtjdvjeiht.html

[G09] 接口 / 抽象类
来源：http://dali.sufxvd.cn/Article/details/gtsuceghjb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.meibo888.top/Article/details/gtobqwvxfs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fzhhl.top/Article/details/gtdrcoiuyh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tianlin.xyz/Article/details/gtomikwupl.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhoulong.xyz/Article/details/gtptcvnxkz.html

Java: interface Shape { double area(); }
来源：http://dali.yanxiufei.cn/Article/details/gtvleiubkl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.haohaochexian.top/Article/details/gtnhjnjtcp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfownxdfv.html

C#:   interface IShape { double Area(); }
来源：http://dali.yueranfly.top/Article/details/gtiicislcz.html

[G10] 访问控制
来源：http://dali.0kj1m.cn/Article/details/gtcyohaoju.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ydzc1.top/Article/details/gteepjhjmk.html

PHP:  public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdojqospa.html

JS:   #private 字段；其余公开
来源：http://dali.fzhhl.top/Article/details/gtaybfkwzq.html

TS:   public / protected / private
来源：http://dali.bjfxy.top/Article/details/gtkjuisery.html

Java: public / protected / private / 默认包级
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnbmanwq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shuidangran.top/Article/details/gtkxckpzyk.html

Ruby: public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtqgyivvst.html

C#:   public / protected / private / internal
来源：http://dali.zhoulong.xyz/Article/details/gtnedaexnq.html

[G11] getter / setter
来源：http://dali.aizwys.cn/Article/details/gtisdskpua.html

Py:   @property 与 @x.setter
来源：http://dali.nanxuanxn.top/Article/details/gtskswlldb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gtwgyubsmf.html

JS:   get name() { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gtodvpzspw.html

TS:   get name(): string { return this._name; }
来源：http://dali.yonumen.top/Article/details/gtgzsjyaek.html

Java: public String getName() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdbhogeq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gtgdqigtle.html

Ruby: attr_accessor :name
来源：http://dali.ydzc1.top/Article/details/gtnzozopok.html

C#:   public string Name { get; set; }
来源：http://dali.hywenlv.cn/Article/details/gtorhrixkz.html

[G12] 对象转字符串
来源：http://dali.yuxming.cn/Article/details/gtpytemhdx.html

Py:   def __str__(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gtwogpbnqm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gtmjbwxkgi.html

JS:   toString() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gttevgying.html

TS:   toString(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gttgcdwrni.html

Java: @Override public String toString() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtzjucahlv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtbautvnbp.html

Ruby: def to_s; @name; end
来源：http://dali.dashuyun.cn/Article/details/gtusuihsdt.html

C#:   public override string ToString() => Name;
来源：http://dali.bjfxy.top/Article/details/gttbdzgmyv.html

[G13] 判断对象类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmafamfz.html

Py:   isinstance(u, User)
来源：http://dali.jqgfzy.top/Article/details/gtybzoaatq.html

PHP:  $u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtfaxwrdvg.html

JS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtlokmibjo.html

TS:   u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtijhfxmyg.html

Java: u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtippzrino.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.feifeiyinyue.top/Article/details/gtejxlauhl.html

Ruby: u.is_a?(User)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvrsqykjb.html

C#:   u is User
来源：http://dali.xuanzx.com/Article/details/gttincekbg.html

[G14] 数据类 / record
来源：http://dali.ehwqpu.com/Article/details/gtifvmcyvw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ehwqpu.com/Article/details/gtaukotpup.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yangfankeji.com/Article/details/gttcffcwad.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gogol.net.cn/Article/details/gtiwpobqff.html

TS:   type User = { name: string; age: number };
来源：http://dali.gzhubu.top/Article/details/gtltfxmhxv.html

Java: record User(String name, int age) {}
来源：http://dali.sxryk.cn/Article/details/gtzejxkphj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guannengcc.top/Article/details/gtzscjmmna.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinqigfzy.top/Article/details/gtpugwcous.html

C#:   record User(string Name, int Age);
来源：http://dali.svipenyu.cn/Article/details/gtsfjjzhaa.html

[G15] 枚举
来源：http://dali.havefunace.top/Article/details/gtvisccfzi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gogol.net.cn/Article/details/gtcadasdml.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sweek.top/Article/details/gtjfnbnaqs.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhiwuduotai.top/Article/details/gtkqomkkzh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtvusigkdm.html

Java: enum Color { RED, GREEN }
来源：http://dali.zycfv.cn/Article/details/gtnnvurbwu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhongyouzk.top/Article/details/gtlleobcqh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gzhubu.top/Article/details/gtjcqupcuv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtgdkvbrfb.html

[G16] 对象转数组 / 字典
来源：http://dali.yonumen.top/Article/details/gthqvcalwn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtclvuzq.html


<!-- 参考信息 -->