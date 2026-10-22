代发 wailian999

[E18] 模板占位符替换
来源：http://dali.yj202588.top/Article/details/gt2hrucqdbv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hongshengwenyu.top/Article/details/gt2kpkktulw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yanxiufei.cn/Article/details/gt2ymkgzflj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hvfumozj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gt2umyomhdn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gt2qjfbenjq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nwbrower.top/Article/details/gt2lecklbxs.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cqqwz.cn/Article/details/gt2wcstfftc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.daria6918.cn/Article/details/gt2hvzgzwpt.html

[E19] 多行文本按行拆分
来源：http://dali.c1oappe.top/Article/details/gt2xcdpdugp.html

Py:   s.splitlines()
来源：http://dali.cheryme.top/Article/details/gt2ndrusuhj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shzxlz.cn/Article/details/gt2uiovytgp.html

JS:   s.split(/\r?\n/)
来源：http://dali.tanke756.top/Article/details/gt2tfivermp.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinqigufen.top/Article/details/gt2acrxcflg.html

Java: s.lines().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2douauses.html

Go:   strings.Split(s, "\n")
来源：http://dali.fengsongda.top/Article/details/gt2mofkzyrv.html

Ruby: s.lines
来源：http://dali.jqgufenzy.top/Article/details/gt2bkiummes.html

C#:   s.Split('\n')
来源：http://dali.yuxming.cn/Article/details/gt2uoscnbfn.html

[E20] 判断字符串是否为空
来源：http://dali.yj20258.top/Article/details/gt2cgxpqfdc.html

Py:   if not s:
来源：http://dali.jianghu66.top/Article/details/gt2yqmfnlvv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.9152youxi.cn/Article/details/gt2bsfwmyfv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jyoumei.cn/Article/details/gt2fivwjtnj.html

TS:   if (s === "") {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2hwwudbge.html

Java: if (s.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gt2qanyubuv.html

Go:   if s == "" {}
来源：http://dali.vqdsnc.cn/Article/details/gt2cwapteqv.html

Ruby: if s.empty?
来源：http://dali.sweek.top/Article/details/gt2zkeirqoi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.guannengcc.top/Article/details/gt2uriyolvh.html

[E21] 超长截断加省略号
来源：http://dali.chenjidiqi.icu/Article/details/gt2ezpxklbo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuanzhike.top/Article/details/gt2ftgbdgvv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.havefunace.top/Article/details/gt2uvqgfrau.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gt2gwdipzzz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gt2filwjiis.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gt2okoqaafb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tian-w.cn/Article/details/gt2sewelega.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gt2vlcufhea.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xziqi.cn/Article/details/gt2agrxrevo.html

[E22] 字节长度与字符长度
来源：http://dali.jinqigufen.top/Article/details/gt2zmozcmqc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shuidangran.top/Article/details/gt2ureaqyfb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gt2fcghyfuk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jcotkjmp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jianghu66.top/Article/details/gt2sqrxtgkk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jqgufenzy.top/Article/details/gt2wfekjbto.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.quarkkingdee.top/Article/details/gt2ngsxecdc.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qqrymczw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zdqjudy.top/Article/details/gt2hgmtxdts.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tvojqycr.html

F. 文件与目录
来源：http://dali.0kj1m.cn/Article/details/gt2omzcucoz.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2fhoefgrq.html

[F01] 读取整个文件
来源：http://dali.guannengcc.top/Article/details/gt2bmsiscqq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hongshengwenyu.top/Article/details/gt2hhawyojo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2oascxeoc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jqgfzy.top/Article/details/gt2wrnaazjk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.316326.xyz/Article/details/gt2bpqphtpb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cgyswlqs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qtjaqexc.html

Ruby: File.read("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2bmoqytub.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2fuexoayh.html

[F02] 逐行读取文件
来源：http://dali.mhx1999.top/Article/details/gt2vgxfjfpp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qeyjgjmm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ybcxt.top/Article/details/gt2ccqplmli.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gt2osksvgnu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yongpay.top/Article/details/gt2ufftjrxf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zrkunmfl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jlsjyb.cn/Article/details/gt2eexaflet.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yongpay.top/Article/details/gt2ecxzihoc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tian-w.cn/Article/details/gt2vetafkbw.html

[F03] 写入文件（覆盖）
来源：http://dali.snrcjt.cn/Article/details/gt2qfscsotp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xuanzx.com/Article/details/gt2jbwsraxy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gaohongyu789.top/Article/details/gt2ekoejwdh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gt2ulhdwuhi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gt2fmejomdm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.birdmap.top/Article/details/gt2jonbfxcc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hammf.cn/Article/details/gt2flwtwhct.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.bjfxy.top/Article/details/gt2tnksmalu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qaaznece.html

[F04] 追加写入文件
来源：http://dali.shzxlz.cn/Article/details/gt2fticwkxv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.daxiang520.top/Article/details/gt2bnxiosdm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.smart0.xyz/Article/details/gt2myjqsauf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shzxlz.cn/Article/details/gt2kbshqics.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yueranfly.top/Article/details/gt2guujoern.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.fengsongda.top/Article/details/gt2qiijsled.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shuidangran.top/Article/details/gt2cqkfmysw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuxming.cn/Article/details/gt2fgompwfp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jlsjyb.cn/Article/details/gt2qepgwhoq.html

[F05] 判断文件或目录是否存在
来源：http://dali.jqgufenzy.top/Article/details/gt2acwobfdc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gogol.net.cn/Article/details/gt2aromelyc.html

PHP:  file_exists("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2fgwarpwq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2epfkncwa.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2vlgirugz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gt2joyvjdtc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hywenlv.cn/Article/details/gt2bobucmzn.html

Ruby: File.exist?("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2uojapzxg.html

C#:   File.Exists("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2ybrkafsc.html

[F06] 删除文件
来源：http://dali.aibaodan.cn/Article/details/gt2nnfkenpr.html

Py:   os.remove("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2rhkzrmaj.html

PHP:  unlink("a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2osawquvq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2ondnoujh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ujqehacy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gt2vaebbwgt.html

Go:   os.Remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2clcgjqbz.html

Ruby: File.delete("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2iyajrmja.html

C#:   File.Delete("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2yjxomzni.html

[F07] 创建目录（含多级）
来源：http://dali.iojbl.cn/Article/details/gt2yduvgebm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ehwqpu.com/Article/details/gt2riwqbaya.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxuanxn.top/Article/details/gt2oxuullbf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uxadpchp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuanzhike.top/Article/details/gt2dzjhseza.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigufen.top/Article/details/gt2luqifywp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.andypj.xyz/Article/details/gt2bzqamwen.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hnqzz.top/Article/details/gt2bgmnqfeb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jianghu66.top/Article/details/gt2jzswysvc.html

[F08] 遍历目录
来源：http://dali.ppjwa.cn/Article/details/gt2dmpjjglp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.pycfn.com/Article/details/gt2rxrvsone.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pnlhglcl.html

JS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gt2dnknunik.html

TS:   fs.readdirSync("dir")
来源：http://dali.fengsongda.top/Article/details/gt2wmdfjtzd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gt2slayywvs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xylfe.cn/Article/details/gt2sbqxljgv.html

Ruby: Dir.children("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nbutcgyt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tanke756.top/Article/details/gt2oczqeoxe.html

[F09] 获取文件大小
来源：http://dali.zhongyouzk.top/Article/details/gt2ayclemvt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sweek.top/Article/details/gt2hauamwgd.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2rgqwcxdb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gt2xmlkqiim.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gt2lcsguixu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gt2zutodbqp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cdnleiting.top/Article/details/gt2kyqzejjw.html

Ruby: File.size("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2zqsalcyf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinqigfzy.top/Article/details/gt2bmmcihvu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.dianchejie.cn/Article/details/gt2pvmkzhhb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2nkmshtbg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cashguo.top/Article/details/gt2wahkrkqk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2peowbcpd.html

TS:   path.extname("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2pndxqzmm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hnxiangtu.top/Article/details/gt2rmhshftm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2uaubysns.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2clzwxzdj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2mrzfisyg.html

[F11] 复制与移动文件
来源：http://dali.hysaishi.cn/Article/details/gt2zhotqfiw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2ceyjnani.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2jfflcaat.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gt2zvwwwing.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gt2zttcgpep.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gqujmuom.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daxiang520.top/Article/details/gt2imrbanzz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gt2aeehqolk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shuidangran.top/Article/details/gt2cjqyttpb.html

[F12] CSV 读写
来源：http://dali.pycfn.com/Article/details/gt2qijvjlub.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xziqi.cn/Article/details/gt2oimxzgsl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.c1oappe.top/Article/details/gt2xsalyebj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cashguo.top/Article/details/gt2elwkfbeh.html

TS:   // 同上
来源：http://dali.wangshuangyany.cn/Article/details/gt2ranppldg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuanzx.com/Article/details/gt2vkghsayp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj20258.top/Article/details/gt2uzucttrk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sweek.top/Article/details/gt2robdeyki.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.kuanghao11.cn/Article/details/gt2etditnms.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2rmbshcya.html

G. 面向对象
来源：http://dali.daria6918.cn/Article/details/gt2ptgbaqih.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2czevtyxl.html

[G01] 定义类
来源：http://dali.tanke756.top/Article/details/gt2bmcjowkb.html

Py:   class User: pass
来源：http://dali.yanxiufei.cn/Article/details/gt2cypqhfqv.html

PHP:  class User {}
来源：http://dali.jyoumei.cn/Article/details/gt2arpwaexi.html

JS:   class User {}
来源：http://dali.birdmap.top/Article/details/gt2eenyeipp.html

TS:   class User { name: string = ""; }
来源：http://dali.zdqjudy.top/Article/details/gt2svrrudxe.html

Java: class User {}
来源：http://dali.yj20258.top/Article/details/gt2byqlyqtf.html

Go:   type User struct { Name string }
来源：http://dali.gzhubu.top/Article/details/gt2qtsyzjej.html

Ruby: class User; end
来源：http://dali.yuanzhike.top/Article/details/gt2ychfzvtb.html

C#:   class User {}
来源：http://dali.shuidangran.top/Article/details/gt2lrcdhsti.html

[G02] 构造函数
来源：http://dali.svipenyu.cn/Article/details/gt2eziyjagq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jlsjyb.cn/Article/details/gt2egnwhqsd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ppjwa.cn/Article/details/gt2dlillizj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gt2mnvwabxl.html

TS:   constructor(public name: string) {}
来源：http://dali.cqqwz.cn/Article/details/gt2kchbuhke.html

Java: User(String name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gt2nkqejftu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yangfankeji.com/Article/details/gt2woqpwgzm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hnxiangtu.top/Article/details/gt2chpujzfy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ppjwa.cn/Article/details/gt2uxkhfinv.html

[G03] 实例属性
来源：http://dali.ydzc1.top/Article/details/gt2pmvnulpg.html

Py:   self.name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gt2keytklcp.html

PHP:  public string $name = "x";
来源：http://dali.yuanzhike.top/Article/details/gt2wxoukktw.html

JS:   this.name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gt2udhxriop.html

TS:   name: string = "x";
来源：http://dali.sxryk.cn/Article/details/gt2aqbwrxbz.html

Java: private String name;
来源：http://dali.xylfe.cn/Article/details/gt2vgbvyseo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daria6918.cn/Article/details/gt2equcmwji.html

Ruby: @name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gt2qacclwdh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xinyue.icu/Article/details/gt2qyxwbhuj.html

[G04] 定义方法
来源：http://dali.cheryme.top/Article/details/gt2fuwhrjoy.html

Py:   def greet(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gt2xqusjomb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gt2lxbfovaf.html

JS:   greet() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gt2yosdibqu.html

TS:   greet(): string { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gt2ywiryhvv.html

Java: String greet() { return name; }
来源：http://dali.c1oappe.top/Article/details/gt2lippkevp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gt2jsmmcfiv.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjahzsq.html

C#:   public string Greet() => Name;
来源：http://dali.yj202588.top/Article/details/gt2ysltijur.html

[G05] 继承
来源：http://dali.chenlongwang.top/Article/details/gt2drsrhtxr.html

Py:   class Admin(User): pass
来源：http://dali.zhongyouzk.top/Article/details/gt2awprerzo.html

PHP:  class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gt2rhuhqafx.html

JS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gt2jhrmzinu.html

TS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gt2tmxdlnpe.html

Java: class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gt2vgzgdlkx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zycfv.cn/Article/details/gt2xhiikuug.html

Ruby: class Admin < User; end
来源：http://dali.guowangkeji.top/Article/details/gt2ynsuacix.html

C#:   class Admin : User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2wwvvgxeq.html

[G06] 重写方法
来源：http://dali.gaohongyu789.top/Article/details/gt2vcuhmgwx.html

Py:   def greet(self): return "admin"
来源：http://dali.guannengcc.top/Article/details/gt2vhxcjqlk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gt2fhyojmxq.html

JS:   greet() { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gt2cvewoyqx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gt2qimiklnn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gt2ddzapgqi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuanzx.com/Article/details/gt2yvqrxxve.html

Ruby: def greet; "admin"; end
来源：http://dali.mhx1999.top/Article/details/gt2zkqnrhid.html

C#:   public override string Greet() => "admin";
来源：http://dali.hfpthk.cn/Article/details/gt2odtetzmr.html

[G07] 调用父类方法
来源：http://dali.xuetiantiany.cn/Article/details/gt2bteklrzk.html

Py:   super().greet()
来源：http://dali.svipenyu.cn/Article/details/gt2ehbvdvtw.html

PHP:  parent::greet();
来源：http://dali.shzxlz.cn/Article/details/gt2zskiswkq.html

JS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gt2zivibkpc.html

TS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2nwlcepar.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2noughfkh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shzxlz.cn/Article/details/gt2mxbpxmvj.html

Ruby: super
来源：http://dali.cdnleiting.top/Article/details/gt2fohrbjcf.html

C#:   base.Greet();
来源：http://dali.feifeiyinyue.top/Article/details/gt2hmqznmvd.html

[G08] 静态方法与属性
来源：http://dali.svipenyu.cn/Article/details/gt2gkzixkmu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pycfn.com/Article/details/gt2dczajukx.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2szeqnhqr.html

JS:   static f() {}
来源：http://dali.fzhhl.top/Article/details/gt2nvupbogo.html

TS:   static f(): void {}
来源：http://dali.shzxlz.cn/Article/details/gt2zpwwblhc.html

Java: static void f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2zekmnutz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.pengpengdd.cyou/Article/details/gt2ctauuwue.html

Ruby: def self.f; end
来源：http://dali.zhoulong.xyz/Article/details/gt2cqnwnysy.html

C#:   public static void F() {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2iwvlffvq.html

[G09] 接口 / 抽象类
来源：http://dali.xziqi.cn/Article/details/gt2ggchxyjn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxinkj.top/Article/details/gt2xpzvmipa.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jianghu66.top/Article/details/gt2nlakrrfi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnxiangtu.top/Article/details/gt2ixslseta.html

TS:   interface Shape { area(): number; }
来源：http://dali.tianlin.xyz/Article/details/gt2ogplhmch.html

Java: interface Shape { double area(); }
来源：http://dali.yonumen.top/Article/details/gt2yjlkuxqm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nwbrower.top/Article/details/gt2nmrxkzvc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tanke756.top/Article/details/gt2wubucqpk.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tdsofuny.html

[G10] 访问控制
来源：http://dali.chenjidiqi.icu/Article/details/gt2rgyjjdsv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.quarkkingdee.top/Article/details/gt2vlooutzp.html

PHP:  public / protected / private
来源：http://dali.tian-w.cn/Article/details/gt2iqyfpsyy.html

JS:   #private 字段；其余公开
来源：http://dali.cashguo.top/Article/details/gt2fsgzzutb.html

TS:   public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gt2zzrzdfsb.html

Java: public / protected / private / 默认包级
来源：http://dali.yonumen.top/Article/details/gt2ddlsuxrb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2savpkdoy.html

Ruby: public / protected / private
来源：http://dali.ydzc1.top/Article/details/gt2rgpazfas.html

C#:   public / protected / private / internal
来源：http://dali.cheryme.top/Article/details/gt2gqxqfwhg.html

[G11] getter / setter
来源：http://dali.hysaishi.cn/Article/details/gt2qsblzlxp.html

Py:   @property 与 @x.setter
来源：http://dali.ydzc1.top/Article/details/gt2ggvmifbu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gt2dioxibdm.html

JS:   get name() { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gt2vpylxfwv.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenzaomai.com/Article/details/gt2wxorgwkg.html

Java: public String getName() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2swunmkkc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gt2dhpvkhor.html

Ruby: attr_accessor :name
来源：http://dali.yuxming.cn/Article/details/gt2xlorbelq.html

C#:   public string Name { get; set; }
来源：http://dali.tianlin.xyz/Article/details/gt2mxiuhhsf.html

[G12] 对象转字符串
来源：http://dali.zhengqikj.top/Article/details/gt2elzlqjwh.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gt2pydhqcva.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gt2ghihxzxb.html

JS:   toString() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gt2tlkuqygj.html

TS:   toString(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gt2nywevvmi.html

Java: @Override public String toString() { return name; }
来源：http://dali.ivvv.top/Article/details/gt2eyfqzygb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gt2qfdihbbx.html

Ruby: def to_s; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2huqhzzjh.html

C#:   public override string ToString() => Name;
来源：http://dali.tanke756.top/Article/details/gt2focvhepz.html

[G13] 判断对象类型
来源：http://dali.andypj.xyz/Article/details/gt2bmgjxpcb.html

Py:   isinstance(u, User)
来源：http://dali.yueranfly.top/Article/details/gt2qqvxlrnx.html

PHP:  $u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2duhouiwl.html

JS:   u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gt2ncneofbo.html

TS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gt2cfbcbckj.html

Java: u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jlcldcgk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aizwys.cn/Article/details/gt2kcmjkmde.html

Ruby: u.is_a?(User)
来源：http://dali.xylfe.cn/Article/details/gt2ecefswil.html

C#:   u is User
来源：http://dali.yj20258888.top/Article/details/gt2ymgzlwhl.html

[G14] 数据类 / record
来源：http://dali.c1oappe.top/Article/details/gt2hfvdcrxk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yuanzhike.top/Article/details/gt2wuzdpneo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenzaomai.com/Article/details/gt2liytesqt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ydzc1.top/Article/details/gt2gfziwgvx.html

TS:   type User = { name: string; age: number };
来源：http://dali.yangfankeji.com/Article/details/gt2ciurwdvm.html

Java: record User(String name, int age) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2sxbcqkcd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cheryme.top/Article/details/gt2atjqpdvn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.havefunace.top/Article/details/gt2rcehykwk.html

C#:   record User(string Name, int Age);
来源：http://dali.dianchejie.cn/Article/details/gt2woggjdna.html

[G15] 枚举
来源：http://dali.snrcjt.cn/Article/details/gt2jqyefgvo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.andypj.xyz/Article/details/gt2lxbudrot.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jbvpmtzf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgfzy.top/Article/details/gt2bdnozbwl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gt2udvtxkpt.html

Java: enum Color { RED, GREEN }
来源：http://dali.tianlin.xyz/Article/details/gt2muqwqcmt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.andypj.xyz/Article/details/gt2weiuirxo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.0kj1m.cn/Article/details/gt2bhuppqel.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gt2onathbxg.html

[G16] 对象转数组 / 字典
来源：http://dali.shangyingyoupin.top/Article/details/gt2zdpxcfvq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258888.top/Article/details/gt2hpkjxfwg.html

PHP:  get_object_vars($obj);
来源：http://dali.xylfe.cn/Article/details/gt2mnwbynbi.html

JS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gt2utreedfa.html

TS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gt2llbmppeb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hysaishi.cn/Article/details/gt2ozedqiay.html


<!-- 参考信息 -->