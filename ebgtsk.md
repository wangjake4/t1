代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtjjpdsaiu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvpnmxooh.html

Ruby: s.capitalize
来源：http://dali.ybcxt.top/Article/details/gtyecepnqs.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj20258888.top/Article/details/gtbtyeedcs.html

[E18] 模板占位符替换
来源：http://dali.yj20258.top/Article/details/gthgxsqhvm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenlongwang.top/Article/details/gtchnvbwte.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ehwqpu.com/Article/details/gtphhnvpme.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtrgaicpih.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gtoemraeox.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtaovwvjtk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtpnsffxif.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.9152youxi.cn/Article/details/gtbzivmiog.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hnqzz.top/Article/details/gtzzjrgbjv.html

[E19] 多行文本按行拆分
来源：http://dali.haohaochexian.top/Article/details/gtvnnrwyfc.html

Py:   s.splitlines()
来源：http://dali.meibo888.top/Article/details/gtfhsgiokq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cashguo.top/Article/details/gtmgaofzyl.html

JS:   s.split(/\r?\n/)
来源：http://dali.xuanzx.com/Article/details/gtiwwtvrmj.html

TS:   s.split(/\r?\n/)
来源：http://dali.jqgufenzy.top/Article/details/gtapwlxgyf.html

Java: s.lines().toList()
来源：http://dali.shzxlz.cn/Article/details/gtnzpfwvnc.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenzaomai.com/Article/details/gtozoozigg.html

Ruby: s.lines
来源：http://dali.0kj1m.cn/Article/details/gtfductyvi.html

C#:   s.Split('\n')
来源：http://dali.meibo888.top/Article/details/gtstvnmnbj.html

[E20] 判断字符串是否为空
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehopbiud.html

Py:   if not s:
来源：http://dali.zycfv.cn/Article/details/gtgxaomasg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinqigufen.top/Article/details/gtturzfxkd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj20258.top/Article/details/gtxelzwfpq.html

TS:   if (s === "") {}
来源：http://dali.ybcxt.top/Article/details/gtaseeyefh.html

Java: if (s.isEmpty()) {}
来源：http://dali.yuanzhike.top/Article/details/gttxojhodr.html

Go:   if s == "" {}
来源：http://dali.quarkkingdee.top/Article/details/gtfgrqmzrf.html

Ruby: if s.empty?
来源：http://dali.zdqjudy.top/Article/details/gtmupybysw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtidruhrbj.html

[E21] 超长截断加省略号
来源：http://dali.guannengcc.top/Article/details/gtitzijgjc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.aizwys.cn/Article/details/gtcegqrzfn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtxfbsshst.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtvtwtewck.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtedypbowd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtebuskeqv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.316326.xyz/Article/details/gthhecrzpr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nwbrower.top/Article/details/gttooysmck.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtgvjsbksj.html

[E22] 字节长度与字符长度
来源：http://dali.sufxvd.cn/Article/details/gtmcbczoko.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.9152youxi.cn/Article/details/gtdxztgdjq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gtophzfrjn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gteqnlvonw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtzczkjase.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ybcxt.top/Article/details/gttvcqvrtt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinqigfzy.top/Article/details/gtaymceosa.html

Ruby: s.bytesize;  s.length
来源：http://dali.yuxming.cn/Article/details/gtxjypagwi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tian-w.cn/Article/details/gtgvpkasia.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtvmifodea.html

F. 文件与目录
来源：http://dali.yuanzhike.top/Article/details/gtfuarbope.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtvczdlmsd.html

[F01] 读取整个文件
来源：http://dali.316326.xyz/Article/details/gtkdgxrsge.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shangyingyoupin.top/Article/details/gtmxlsdqff.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtihlgmspb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj20258888.top/Article/details/gtpcgmbosi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.fzhhl.top/Article/details/gtbwcwjbhh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtmlburstf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj20258.top/Article/details/gttxevfbwp.html

Ruby: File.read("a.txt")
来源：http://dali.meibo888.top/Article/details/gtihgxtpfa.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hammf.cn/Article/details/gtqsbdzecv.html

[F02] 逐行读取文件
来源：http://dali.cucudq.cn/Article/details/gtbgseyonh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tanke756.top/Article/details/gtecgpnxlb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jqgfzy.top/Article/details/gtzbwsehbt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daria6918.cn/Article/details/gtnsvqcjua.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sweek.top/Article/details/gtibrsohcl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sweek.top/Article/details/gtttvvpijp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.daxiang520.top/Article/details/gtknzbbvzd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jqgufenzy.top/Article/details/gtzeyvqars.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.wangdashe.top/Article/details/gtcgrhvwuk.html

[F03] 写入文件（覆盖）
来源：http://dali.sysykeji.top/Article/details/gtwncilzip.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj20258888.top/Article/details/gtnmfwedqq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhoulong.xyz/Article/details/gtustwaccx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gtbfmimqar.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtmqvjqarq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.snrcjt.cn/Article/details/gtinpmlwjv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.bjfxy.top/Article/details/gtgukqepzm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.c1oappe.top/Article/details/gtgvtfgukj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sxryk.cn/Article/details/gttyuxfjbk.html

[F04] 追加写入文件
来源：http://dali.guannengcc.top/Article/details/gthqgxfoxj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gthcbbpuof.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhixingplan.top/Article/details/gtjiapfiwz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtlgakjbyw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.0kj1m.cn/Article/details/gtbljamyur.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cucudq.cn/Article/details/gtjdxhhasg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.daxiang520.top/Article/details/gtwmwzegyn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sweek.top/Article/details/gtgowdlgbv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj20258888.top/Article/details/gtiwtjnfhi.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlqbyrux.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxmozxpse.html

PHP:  file_exists("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtwswhcjzk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtiujhvcfm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtqpnrxmop.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gtscrouzjz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.dianchejie.cn/Article/details/gttmzcwptr.html

Ruby: File.exist?("a.txt")
来源：http://dali.fengsongda.top/Article/details/gthtwtinch.html

C#:   File.Exists("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtmucpxdgy.html

[F06] 删除文件
来源：http://dali.snrcjt.cn/Article/details/gtfsbcaejo.html

Py:   os.remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtaepvmjuc.html

PHP:  unlink("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlvnckeee.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtuvyeaeyu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gttppvicwv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtwwwfkinm.html

Go:   os.Remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtdngyeqjq.html

Ruby: File.delete("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtkexpuzdf.html

C#:   File.Delete("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtwjwpfgkp.html

[F07] 创建目录（含多级）
来源：http://dali.9152youxi.cn/Article/details/gtqdjhllos.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.guowangkeji.top/Article/details/gtxcpnnojf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ppjwa.cn/Article/details/gtnttxyrgg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuanzhike.top/Article/details/gtbtyslchn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gtmlitecgq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhongyouzk.top/Article/details/gtzhdpbqao.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.kuanghao11.cn/Article/details/gtpngpcwrs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jlsjyb.cn/Article/details/gtykobqwss.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yangfankeji.com/Article/details/gtqotlhhyv.html

[F08] 遍历目录
来源：http://dali.daxiang520.top/Article/details/gtdtcxsbqz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jlsjyb.cn/Article/details/gtwcqgzbzq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tian-w.cn/Article/details/gtavtnfcxt.html

JS:   fs.readdirSync("dir")
来源：http://dali.ehwqpu.com/Article/details/gthxaxtsfj.html

TS:   fs.readdirSync("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkgicoioh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenjidiqi.icu/Article/details/gtutxztbie.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigufen.top/Article/details/gtjhvtvyhf.html

Ruby: Dir.children("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtrblsoccm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yongpay.top/Article/details/gtwgzrrinj.html

[F09] 获取文件大小
来源：http://dali.jqgufenzy.top/Article/details/gtuikhqizw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtrsnqnqrh.html

PHP:  filesize("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtztdjrbje.html

JS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gtgjbixnph.html

TS:   fs.statSync("a.txt").size
来源：http://dali.guannengcc.top/Article/details/gtqdorjyfl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtnkvhmjpt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqlrqooyp.html

Ruby: File.size("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtdmvftbwy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nanxuanxn.top/Article/details/gtkutluvvj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hammf.cn/Article/details/gtruyckqbh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtfqqlmvoe.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ydzc1.top/Article/details/gtqecjmisx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtkeyontlq.html

TS:   path.extname("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqsdmphb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.smart0.xyz/Article/details/gtpwlotgxk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtedmeugzn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtzfovfmne.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtuemqxbkt.html

[F11] 复制与移动文件
来源：http://dali.birdmap.top/Article/details/gtbwsrlaxm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtvekeszpu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.birdmap.top/Article/details/gtilbkwzsl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtqdqsihlu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gtnrzphasy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xylfe.cn/Article/details/gtwcmqxhyd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdbnmlvq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtjwekegeq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yvedp.cn/Article/details/gtkmyobdgc.html

[F12] CSV 读写
来源：http://dali.yvedp.cn/Article/details/gtwduuphcv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxuanxn.top/Article/details/gtdaszrnbx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shuidangran.top/Article/details/gtpoltshjy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.dashuyun.cn/Article/details/gtukvcmjoz.html

TS:   // 同上
来源：http://dali.yj202588.top/Article/details/gtekdmnzlk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnqzz.top/Article/details/gtjyglwvjw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ivvv.top/Article/details/gttmvghmjg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.quarkkingdee.top/Article/details/gtbppydgfg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tanke756.top/Article/details/gtjkkgqkyh.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtxratwila.html

G. 面向对象
来源：http://dali.sxryk.cn/Article/details/gtadypsjsm.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtrtvlpioh.html

[G01] 定义类
来源：http://dali.fengsongda.top/Article/details/gtpzivlish.html

Py:   class User: pass
来源：http://dali.hnqzz.top/Article/details/gtdffkfvwu.html

PHP:  class User {}
来源：http://dali.jqgufenzy.top/Article/details/gtohlbelax.html

JS:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtexhtbdnt.html

TS:   class User { name: string = ""; }
来源：http://dali.daxiang520.top/Article/details/gtdcxecyqt.html

Java: class User {}
来源：http://dali.yuanzhike.top/Article/details/gtpxadfxsz.html

Go:   type User struct { Name string }
来源：http://dali.fzhhl.top/Article/details/gtwxnalrkw.html

Ruby: class User; end
来源：http://dali.sweek.top/Article/details/gtchrxpztt.html

C#:   class User {}
来源：http://dali.sweek.top/Article/details/gtebfbnvuo.html

[G02] 构造函数
来源：http://dali.cdnleiting.top/Article/details/gtprwebphw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hnxiangtu.top/Article/details/gtreblnrje.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.kuanghao11.cn/Article/details/gtblmzoabc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gtssuvcfxk.html

TS:   constructor(public name: string) {}
来源：http://dali.gzhubu.top/Article/details/gtugambvsi.html

Java: User(String name) { this.name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gtqtjugsup.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ppjwa.cn/Article/details/gtbqyjyilj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fengsongda.top/Article/details/gthtfxdney.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtzipxmlcq.html

[G03] 实例属性
来源：http://dali.sxryk.cn/Article/details/gtaeyfdikl.html

Py:   self.name = "x"
来源：http://dali.shzxlz.cn/Article/details/gtsaxmesxr.html

PHP:  public string $name = "x";
来源：http://dali.andypj.xyz/Article/details/gtdhgpkumf.html

JS:   this.name = "x";
来源：http://dali.jiagoushi.top/Article/details/gtxqzhsynb.html

TS:   name: string = "x";
来源：http://dali.hammf.cn/Article/details/gteigjnksa.html

Java: private String name;
来源：http://dali.smart0.xyz/Article/details/gtzzplrgjf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yongpay.top/Article/details/gtzkdjkpsn.html

Ruby: @name = "x"
来源：http://dali.fengsongda.top/Article/details/gtyjgfelyy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xylfe.cn/Article/details/gtdijvrwtu.html

[G04] 定义方法
来源：http://dali.c1oappe.top/Article/details/gthsyrnnhx.html

Py:   def greet(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gtrnmartna.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtohbkouyu.html

JS:   greet() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtpsnvbeky.html

TS:   greet(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtbcjxzokg.html

Java: String greet() { return name; }
来源：http://dali.pycfn.com/Article/details/gtoxuqiehy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gtqawhcrkj.html

Ruby: def greet; @name; end
来源：http://dali.xinyue.icu/Article/details/gtgsvongwy.html

C#:   public string Greet() => Name;
来源：http://dali.nwbrower.top/Article/details/gtiuicvwag.html

[G05] 继承
来源：http://dali.xuetiantiany.cn/Article/details/gtfvhxitua.html

Py:   class Admin(User): pass
来源：http://dali.jianghu66.top/Article/details/gtycawgsxq.html

PHP:  class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtmonggewl.html

JS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtjzljisqx.html

TS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtktiqjdjl.html

Java: class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtexqemvdz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jianghu66.top/Article/details/gtvjsskjyx.html

Ruby: class Admin < User; end
来源：http://dali.sweek.top/Article/details/gtrhrioqbl.html

C#:   class Admin : User {}
来源：http://dali.havefunace.top/Article/details/gtrahqtwsf.html

[G06] 重写方法
来源：http://dali.nanxinkj.top/Article/details/gtulvfwafg.html

Py:   def greet(self): return "admin"
来源：http://dali.kuanghao11.cn/Article/details/gtzmgfykmq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtktuaspxu.html

JS:   greet() { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtnhwkwybv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtyucpxayb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqwkksmsr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jlsjyb.cn/Article/details/gtvyznuvlc.html

Ruby: def greet; "admin"; end
来源：http://dali.zdqjudy.top/Article/details/gtlybsrdjv.html

C#:   public override string Greet() => "admin";
来源：http://dali.bjfxy.top/Article/details/gtslrkouhy.html

[G07] 调用父类方法
来源：http://dali.cdnleiting.top/Article/details/gtnvedvuuh.html

Py:   super().greet()
来源：http://dali.hywenlv.cn/Article/details/gtrmkunidq.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gtbcgaagsq.html

JS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtaxmsrzwt.html

TS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gtbzcpkduq.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtcxtiihcy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tian-w.cn/Article/details/gteiqusyfa.html

Ruby: super
来源：http://dali.hongshengwenyu.top/Article/details/gtbjerjdis.html

C#:   base.Greet();
来源：http://dali.nanxuanxn.top/Article/details/gtyuakhrmt.html

[G08] 静态方法与属性
来源：http://dali.vqdsnc.cn/Article/details/gtvkkbwhla.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhiwuduotai.top/Article/details/gtaqkuaaio.html

PHP:  public static function f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtwldotoka.html

JS:   static f() {}
来源：http://dali.guannengcc.top/Article/details/gthncnkpjg.html

TS:   static f(): void {}
来源：http://dali.aibaodan.cn/Article/details/gtidezjdee.html

Java: static void f() {}
来源：http://dali.yueranfly.top/Article/details/gtnfguvxdr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tanke756.top/Article/details/gtstzqkptz.html

Ruby: def self.f; end
来源：http://dali.chenlongwang.top/Article/details/gtpaxmgcgi.html

C#:   public static void F() {}
来源：http://dali.yongpay.top/Article/details/gtdzjyhzxa.html

[G09] 接口 / 抽象类
来源：http://dali.cheryme.top/Article/details/gtuxqbamtw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.0kj1m.cn/Article/details/gtzuiwwrfm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cucudq.cn/Article/details/gtgagdisus.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hfpthk.cn/Article/details/gtijefifqk.html

TS:   interface Shape { area(): number; }
来源：http://dali.ppjwa.cn/Article/details/gterubwedy.html

Java: interface Shape { double area(); }
来源：http://dali.cucudq.cn/Article/details/gtiuqllepw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hnqzz.top/Article/details/gtwqcotaxr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinqigufen.top/Article/details/gtocudqwpg.html

C#:   interface IShape { double Area(); }
来源：http://dali.yvedp.cn/Article/details/gtcyjylxni.html

[G10] 访问控制
来源：http://dali.yj202588.top/Article/details/gtvxhlycmx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daria6918.cn/Article/details/gttjqvudoa.html

PHP:  public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtjxvnmvir.html

JS:   #private 字段；其余公开
来源：http://dali.meibo888.top/Article/details/gtslxdnsyo.html

TS:   public / protected / private
来源：http://dali.cheryme.top/Article/details/gtwlufrbtl.html

Java: public / protected / private / 默认包级
来源：http://dali.xinyue.icu/Article/details/gtxygsqmqw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenjidiqi.icu/Article/details/gtkkxemjvd.html

Ruby: public / protected / private
来源：http://dali.andypj.xyz/Article/details/gtvibcfxis.html

C#:   public / protected / private / internal
来源：http://dali.nwbrower.top/Article/details/gtowvzqlok.html

[G11] getter / setter
来源：http://dali.sxryk.cn/Article/details/gtfeskvwoa.html

Py:   @property 与 @x.setter
来源：http://dali.316326.xyz/Article/details/gtooetmbyg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtoomtjtqa.html

JS:   get name() { return this._name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtjcgxdiwe.html

TS:   get name(): string { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcyyyhuut.html

Java: public String getName() { return name; }
来源：http://dali.yongpay.top/Article/details/gtcducyhvw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gtuyvnpgrz.html

Ruby: attr_accessor :name
来源：http://dali.xinyue.icu/Article/details/gtlwnmqtrf.html

C#:   public string Name { get; set; }
来源：http://dali.gotoacloud.top/Article/details/gtuaeruirj.html

[G12] 对象转字符串
来源：http://dali.daxiang520.top/Article/details/gtzxzldmdf.html

Py:   def __str__(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gtvhjtpfsn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gtuedrahbb.html

JS:   toString() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtqfhjdqwk.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtcznhiaim.html

Java: @Override public String toString() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtuwzhtqzz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gthinachco.html

Ruby: def to_s; @name; end
来源：http://dali.gogol.net.cn/Article/details/gtlzulljte.html

C#:   public override string ToString() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gtswjgdwyf.html

[G13] 判断对象类型
来源：http://dali.zdqjudy.top/Article/details/gtlbdxjljz.html

Py:   isinstance(u, User)
来源：http://dali.yangfankeji.com/Article/details/gtofarbabo.html

PHP:  $u instanceof User
来源：http://dali.cheryme.top/Article/details/gtjztrfpcn.html

JS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gtckcyhtip.html

TS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtlxhphcel.html

Java: u instanceof User
来源：http://dali.hammf.cn/Article/details/gtvuqrdlde.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhongyouzk.top/Article/details/gtwonitetk.html

Ruby: u.is_a?(User)
来源：http://dali.jinghuilouyu.cn/Article/details/gtttvcyscr.html

C#:   u is User
来源：http://dali.zycfv.cn/Article/details/gtnmffaoex.html

[G14] 数据类 / record
来源：http://dali.fzhhl.top/Article/details/gtmbcrczms.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258888.top/Article/details/gtgqtjgttx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hywenlv.cn/Article/details/gtkdmfnjun.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuanzhike.top/Article/details/gtepgdqwgj.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj20258888.top/Article/details/gthksbhbia.html

Java: record User(String name, int age) {}
来源：http://dali.jlsjyb.cn/Article/details/gtityhqrlz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nwbrower.top/Article/details/gtxxppxtxh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.aibaodan.cn/Article/details/gtikyepyer.html

C#:   record User(string Name, int Age);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqkgszube.html

[G15] 枚举
来源：http://dali.jinqigufen.top/Article/details/gtaomrqhom.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cdnleiting.top/Article/details/gtgcrtixcc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yvedp.cn/Article/details/gtsbqvkqpa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jlsjyb.cn/Article/details/gtkdizxemf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gtpviodoil.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj20258888.top/Article/details/gtmwnoyqjh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sweek.top/Article/details/gtfhtiwavu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigufen.top/Article/details/gtrntwrfan.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtilzwkbyh.html

[G16] 对象转数组 / 字典
来源：http://dali.xziqi.cn/Article/details/gtpjvqhifo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sweek.top/Article/details/gtzqamxwya.html


<!-- 参考信息 -->