代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ybcxt.top/Article/details/gtklelrulq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sufxvd.cn/Article/details/gtfxonszld.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258.top/Article/details/gtmjvfefpg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnxiangtu.top/Article/details/gtocwiwkbq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvdaxjltv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.9152youxi.cn/Article/details/gtluvujtsb.html

Ruby: s.capitalize
来源：http://dali.xinyue.icu/Article/details/gtzzjgtqmg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhongyouzk.top/Article/details/gtbtkatute.html

[E18] 模板占位符替换
来源：http://dali.smart0.xyz/Article/details/gtuymbmjld.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhoulong.xyz/Article/details/gtvotafiue.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.havefunace.top/Article/details/gtwjgtcbph.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gtzlexlhhq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtuybfoqvc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gttspkddoo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yongpay.top/Article/details/gteczhyjak.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ehwqpu.com/Article/details/gtmtvbrthu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj20258.top/Article/details/gtqabdtrpn.html

[E19] 多行文本按行拆分
来源：http://dali.feifeiyinyue.top/Article/details/gtcucjgbxn.html

Py:   s.splitlines()
来源：http://dali.zhixingplan.top/Article/details/gtjxqxklsl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtnjdjntqo.html

JS:   s.split(/\r?\n/)
来源：http://dali.guannengcc.top/Article/details/gtrltfdbse.html

TS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gtqtrmjdiw.html

Java: s.lines().toList()
来源：http://dali.nanxinkj.top/Article/details/gteihnexvi.html

Go:   strings.Split(s, "\n")
来源：http://dali.jyoumei.cn/Article/details/gtmowrwypg.html

Ruby: s.lines
来源：http://dali.bjfxy.top/Article/details/gtnrlulwqb.html

C#:   s.Split('\n')
来源：http://dali.ydzc1.top/Article/details/gtonfgzovh.html

[E20] 判断字符串是否为空
来源：http://dali.aibaodan.cn/Article/details/gtsgxhnztb.html

Py:   if not s:
来源：http://dali.ivvv.top/Article/details/gtwbdplpdz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.0kj1m.cn/Article/details/gtlssraits.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cqqwz.cn/Article/details/gtauepoypq.html

TS:   if (s === "") {}
来源：http://dali.guowangkeji.top/Article/details/gtozeolmkx.html

Java: if (s.isEmpty()) {}
来源：http://dali.fengsongda.top/Article/details/gtfxpwkoef.html

Go:   if s == "" {}
来源：http://dali.zhixingplan.top/Article/details/gtegxaauxi.html

Ruby: if s.empty?
来源：http://dali.yj202588.top/Article/details/gtaphujtvu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hywenlv.cn/Article/details/gtshjxhovq.html

[E21] 超长截断加省略号
来源：http://dali.hammf.cn/Article/details/gtvszotlmz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.guowangkeji.top/Article/details/gttnyaxxjd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtzueyithp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtzatqqeou.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtllfknqqh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtwlejpaax.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ivvv.top/Article/details/gtzhxiwkya.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtnxrpoeum.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gtgyartmjh.html

[E22] 字节长度与字符长度
来源：http://dali.yonumen.top/Article/details/gtlvetbeey.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tian-w.cn/Article/details/gtgoftwsez.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.316326.xyz/Article/details/gtzqpubsbl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nwbrower.top/Article/details/gtykhwkjsx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tian-w.cn/Article/details/gtzjbjjeki.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hnqzz.top/Article/details/gtlzpxszie.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxinkj.top/Article/details/gttkobeycq.html

Ruby: s.bytesize;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtmpziofia.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sxryk.cn/Article/details/gtcocajxuu.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gttwsxjeof.html

F. 文件与目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmgoojrpy.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtabkpabea.html

[F01] 读取整个文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmmvrhee.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hammf.cn/Article/details/gtkwklpdzq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.pycfn.com/Article/details/gtlhgtzwcg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nanxuanxn.top/Article/details/gtfmrxrgwp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gtgoeirsip.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gtchlooabs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hammf.cn/Article/details/gtgaacrygc.html

Ruby: File.read("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtivdzrrwk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtxjbdwxea.html

[F02] 逐行读取文件
来源：http://dali.hammf.cn/Article/details/gturypuynn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shanyushiyangtech.top/Article/details/gtjiwmestl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhongyouzk.top/Article/details/gtzmxzddyv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ybcxt.top/Article/details/gtjkxdorej.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gzhubu.top/Article/details/gtuuqtkteo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.316326.xyz/Article/details/gtplhdvsbc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenzaomai.com/Article/details/gtxuqwemnz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.svipenyu.cn/Article/details/gtbvlxmmxt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jiagoushi.top/Article/details/gtklxdhbis.html

[F03] 写入文件（覆盖）
来源：http://dali.hywenlv.cn/Article/details/gtuektshkf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ydzc1.top/Article/details/gtwauwatav.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozacvtzs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gtlqaoqdqy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gtymlstmdv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shzxlz.cn/Article/details/gtxdjkktmi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.quarkkingdee.top/Article/details/gtvomvvgsj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nanxinkj.top/Article/details/gtzsqepkhu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gtyqpowxbe.html

[F04] 追加写入文件
来源：http://dali.jqgufenzy.top/Article/details/gtnkykdjcj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.redwolf501.top/Article/details/gtetuirynn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yonumen.top/Article/details/gtlduumfnf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.c1oappe.top/Article/details/gthqwuymtq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gttwilthzh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xziqi.cn/Article/details/gtswuodphn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gzhubu.top/Article/details/gtmwcolypf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sxryk.cn/Article/details/gtuvdzwfdh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.vqdsnc.cn/Article/details/gtwbpzjywe.html

[F05] 判断文件或目录是否存在
来源：http://dali.daxiang520.top/Article/details/gtrmobgzuv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xinyue.icu/Article/details/gtexonuhzc.html

PHP:  file_exists("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtvkbiqzxi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtmoosurfl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtajbnzmfn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtuqakqxqj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sysykeji.top/Article/details/gtablsdojw.html

Ruby: File.exist?("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtdrgmbcuu.html

C#:   File.Exists("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gthdkuqepz.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gtoyenfghu.html

Py:   os.remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtchdjhhwo.html

PHP:  unlink("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtynkquzlc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtsifijidm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtygzchoyc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtnsutuina.html

Go:   os.Remove("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtaaokayrt.html

Ruby: File.delete("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtuinbybke.html

C#:   File.Delete("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtrwysapyp.html

[F07] 创建目录（含多级）
来源：http://dali.yvedp.cn/Article/details/gtulyurqpg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jianghu66.top/Article/details/gtjcqtxrge.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gogol.net.cn/Article/details/gttmxcjfuc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxinkj.top/Article/details/gtcmeukaxa.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gtbnwmgwcf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ehwqpu.com/Article/details/gtbofevjxd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cqqwz.cn/Article/details/gtzfjnwjki.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hywenlv.cn/Article/details/gtipwyikwk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinghuilouyu.cn/Article/details/gtrktjunge.html

[F08] 遍历目录
来源：http://dali.hnxiangtu.top/Article/details/gtlqclwwsb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cheryme.top/Article/details/gtthnhfljf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenzaomai.com/Article/details/gtiawplymk.html

JS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gtcnbcfoqb.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtveorihgf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jiagoushi.top/Article/details/gtplclfdej.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yueranfly.top/Article/details/gtjspmzsqi.html

Ruby: Dir.children("dir")
来源：http://dali.yj202588.top/Article/details/gtjbszbxev.html

C#:   Directory.GetFiles("dir")
来源：http://dali.iojbl.cn/Article/details/gtaygltkvi.html

[F09] 获取文件大小
来源：http://dali.meibo888.top/Article/details/gthgivwmqo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtxsilqcsd.html

PHP:  filesize("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtjchspmfr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.aizwys.cn/Article/details/gtopevvxeu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gtvrqmkfes.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtesvkqllj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenlongwang.top/Article/details/gtehbqvmbz.html

Ruby: File.size("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gttlpnpify.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zdqjudy.top/Article/details/gtxjzuchcs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sufxvd.cn/Article/details/gtexklvrcv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtiexlgdms.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtmxkbcnni.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtlfezhowc.html

TS:   path.extname("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtaisxihbq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sxryk.cn/Article/details/gtjtxlqbnj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtfknruiss.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtkdpwqbwo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtknjactwd.html

[F11] 复制与移动文件
来源：http://dali.ehwqpu.com/Article/details/gtaxjeslln.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtqknbexas.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cheryme.top/Article/details/gtupurspry.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gtvvrbixxf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtzbdltpdy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gtmcmzgqlv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuetiantiany.cn/Article/details/gtpxkqcooy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtdwwdaqey.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jiagoushi.top/Article/details/gtepizmqsy.html

[F12] CSV 读写
来源：http://dali.sweek.top/Article/details/gtxmtgyfek.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.daria6918.cn/Article/details/gtzxriqvok.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangtech.top/Article/details/gtbrbhqfnn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gaohongyu789.top/Article/details/gtbztmvmwy.html

TS:   // 同上
来源：http://dali.birdmap.top/Article/details/gtqmxvxmji.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.quarkkingdee.top/Article/details/gtqhfrfxks.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhoulong.xyz/Article/details/gtmgzwlnbq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.0kj1m.cn/Article/details/gtfqmujzaq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cqqwz.cn/Article/details/gtvvqtixxl.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqnwwcys.html

G. 面向对象
来源：http://dali.cqqwz.cn/Article/details/gtlndmtxgg.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtuctjizco.html

[G01] 定义类
来源：http://dali.jinqigufen.top/Article/details/gtxkrkrcsv.html

Py:   class User: pass
来源：http://dali.yuxming.cn/Article/details/gtiozfychk.html

PHP:  class User {}
来源：http://dali.hammf.cn/Article/details/gtlaymcelp.html

JS:   class User {}
来源：http://dali.sysykeji.top/Article/details/gtvujkxpgo.html

TS:   class User { name: string = ""; }
来源：http://dali.guowangkeji.top/Article/details/gtjrwkyjgy.html

Java: class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtydkxwhdx.html

Go:   type User struct { Name string }
来源：http://dali.sufxvd.cn/Article/details/gtcpdwdxly.html

Ruby: class User; end
来源：http://dali.zhixingplan.top/Article/details/gtdudcfmme.html

C#:   class User {}
来源：http://dali.xinyue.icu/Article/details/gtqfefqwpr.html

[G02] 构造函数
来源：http://dali.cdnleiting.top/Article/details/gtoebshoap.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258888.top/Article/details/gtegpzhjrx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.316326.xyz/Article/details/gtsacgcanb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtybgewfge.html

TS:   constructor(public name: string) {}
来源：http://dali.quarkkingdee.top/Article/details/gtnrjizexj.html

Java: User(String name) { this.name = name; }
来源：http://dali.guannengcc.top/Article/details/gtsugsarkg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hysaishi.cn/Article/details/gtcqwhyjex.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.kuanghao11.cn/Article/details/gtfhklumpo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yangfankeji.com/Article/details/gteyynzgrd.html

[G03] 实例属性
来源：http://dali.hammf.cn/Article/details/gtzalfvswb.html

Py:   self.name = "x"
来源：http://dali.cucudq.cn/Article/details/gtuolnwfpl.html

PHP:  public string $name = "x";
来源：http://dali.yj20258888.top/Article/details/gtmqewawsx.html

JS:   this.name = "x";
来源：http://dali.xuanzx.com/Article/details/gtxwyrpdxm.html

TS:   name: string = "x";
来源：http://dali.tianlin.xyz/Article/details/gtrwovpfdo.html

Java: private String name;
来源：http://dali.tian-w.cn/Article/details/gtazqzrrsr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigfzy.top/Article/details/gtltffurwi.html

Ruby: @name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gtmurcauti.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yangfankeji.com/Article/details/gtetepslaj.html

[G04] 定义方法
来源：http://dali.dashuyun.cn/Article/details/gtdlhlzzwy.html

Py:   def greet(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gtgrjwpjsb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtusymshxc.html

JS:   greet() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtfjfdliue.html

TS:   greet(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtteltgloj.html

Java: String greet() { return name; }
来源：http://dali.sysykeji.top/Article/details/gtpjpercgb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtdcxpixyb.html

Ruby: def greet; @name; end
来源：http://dali.tian-w.cn/Article/details/gtoghowlwv.html

C#:   public string Greet() => Name;
来源：http://dali.meibo888.top/Article/details/gtnkhevjgn.html

[G05] 继承
来源：http://dali.yongpay.top/Article/details/gtrfvkxvwp.html

Py:   class Admin(User): pass
来源：http://dali.xuetiantiany.cn/Article/details/gtycsjtoom.html

PHP:  class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtnxbtygtf.html

JS:   class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtpejtipup.html

TS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtpbzoxspo.html

Java: class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtnsmvoari.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhiwuduotai.top/Article/details/gtoipfvrml.html

Ruby: class Admin < User; end
来源：http://dali.gogol.net.cn/Article/details/gtjxzdcxhb.html

C#:   class Admin : User {}
来源：http://dali.zycfv.cn/Article/details/gtoysjbehz.html

[G06] 重写方法
来源：http://dali.cqqwz.cn/Article/details/gttthvumsc.html

Py:   def greet(self): return "admin"
来源：http://dali.sweek.top/Article/details/gtjpaoepwm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtkipmmnug.html

JS:   greet() { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtshisuylr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtnfkawyqr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtyludxxyj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.snrcjt.cn/Article/details/gtohunwtmn.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfhstxmeg.html

C#:   public override string Greet() => "admin";
来源：http://dali.gotoacloud.top/Article/details/gtkgasjnxo.html

[G07] 调用父类方法
来源：http://dali.zhixingplan.top/Article/details/gtansvtnvk.html

Py:   super().greet()
来源：http://dali.ppjwa.cn/Article/details/gtecxveubo.html

PHP:  parent::greet();
来源：http://dali.fzhhl.top/Article/details/gttrmdtwtk.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtlwxymfzb.html

TS:   super.greet();
来源：http://dali.xziqi.cn/Article/details/gttuyuijgq.html

Java: super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtqvtgirce.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cashguo.top/Article/details/gtfokjukrg.html

Ruby: super
来源：http://dali.nanxinkj.top/Article/details/gttlpiuzol.html

C#:   base.Greet();
来源：http://dali.jianghu66.top/Article/details/gtxempipgy.html

[G08] 静态方法与属性
来源：http://dali.fzhhl.top/Article/details/gttdbidlyt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ybcxt.top/Article/details/gtydwqyjkd.html

PHP:  public static function f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpnubetqh.html

JS:   static f() {}
来源：http://dali.chenlongwang.top/Article/details/gtaewzpajt.html

TS:   static f(): void {}
来源：http://dali.vqdsnc.cn/Article/details/gtewmeqhlr.html

Java: static void f() {}
来源：http://dali.jinqigufen.top/Article/details/gtanczlzpg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.smart0.xyz/Article/details/gtnjiydewb.html

Ruby: def self.f; end
来源：http://dali.gogol.net.cn/Article/details/gtgovytkvq.html

C#:   public static void F() {}
来源：http://dali.jqgfzy.top/Article/details/gtfbgpyvew.html

[G09] 接口 / 抽象类
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvaecftr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenjidiqi.icu/Article/details/gtvdmfmdfd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gogol.net.cn/Article/details/gtimmdeizr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.andypj.xyz/Article/details/gtdwnfxsuk.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhongyouzk.top/Article/details/gtmpmnloim.html

Java: interface Shape { double area(); }
来源：http://dali.tian-w.cn/Article/details/gtjvsuaeit.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yvedp.cn/Article/details/gtrihphrpw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinqigfzy.top/Article/details/gtbezmoptk.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtlqqfbmxe.html

[G10] 访问控制
来源：http://dali.zhixingplan.top/Article/details/gtdkatezcj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hywenlv.cn/Article/details/gtxtbvwqnc.html

PHP:  public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtzjhoaozn.html

JS:   #private 字段；其余公开
来源：http://dali.hysaishi.cn/Article/details/gtzyhicgwv.html

TS:   public / protected / private
来源：http://dali.yj20258.top/Article/details/gtjbqurydj.html

Java: public / protected / private / 默认包级
来源：http://dali.iojbl.cn/Article/details/gtgsecsgmy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guowangkeji.top/Article/details/gtrjmfucrm.html

Ruby: public / protected / private
来源：http://dali.aizwys.cn/Article/details/gtsoafhves.html

C#:   public / protected / private / internal
来源：http://dali.shangyingyoupin.top/Article/details/gtmcinqvjw.html

[G11] getter / setter
来源：http://dali.jinqigufen.top/Article/details/gtozaypqwj.html

Py:   @property 与 @x.setter
来源：http://dali.hongshengwenyu.top/Article/details/gtjjmgqzxt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbwuxqts.html

JS:   get name() { return this._name; }
来源：http://dali.birdmap.top/Article/details/gtsclslzfs.html

TS:   get name(): string { return this._name; }
来源：http://dali.xziqi.cn/Article/details/gtlqpynfhk.html

Java: public String getName() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtrepxfwzy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtmgaqoarw.html

Ruby: attr_accessor :name
来源：http://dali.xziqi.cn/Article/details/gtbolzogzb.html

C#:   public string Name { get; set; }
来源：http://dali.bjfxy.top/Article/details/gtwtfyzbtv.html

[G12] 对象转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtstfuqmwd.html

Py:   def __str__(self): return self.name
来源：http://dali.jianghu66.top/Article/details/gtguinincp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtygunklmn.html

JS:   toString() { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtyqxltunb.html

TS:   toString(): string { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtuztcztbn.html

Java: @Override public String toString() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtspdecfoj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtnzazjinx.html

Ruby: def to_s; @name; end
来源：http://dali.svipenyu.cn/Article/details/gtloftpbxi.html

C#:   public override string ToString() => Name;
来源：http://dali.zhengqikj.top/Article/details/gtzlxwozlv.html

[G13] 判断对象类型
来源：http://dali.cdnleiting.top/Article/details/gtjwcoxypq.html

Py:   isinstance(u, User)
来源：http://dali.andypj.xyz/Article/details/gtdbmspezg.html

PHP:  $u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtllzmrhhc.html

JS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtoyacejrz.html

TS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtkmnpjiqz.html

Java: u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtwnvcmcte.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhiwuduotai.top/Article/details/gtvsmkhvga.html

Ruby: u.is_a?(User)
来源：http://dali.gzhubu.top/Article/details/gtflxsxvxl.html

C#:   u is User
来源：http://dali.smart0.xyz/Article/details/gtdgjgtoaz.html

[G14] 数据类 / record
来源：http://dali.xuetiantiany.cn/Article/details/gtnjjdrydm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cheryme.top/Article/details/gtgjjrnldc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jiagoushi.top/Article/details/gtowymjvws.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhongyouzk.top/Article/details/gtronzqdep.html

TS:   type User = { name: string; age: number };
来源：http://dali.xinyue.icu/Article/details/gtcshmwzad.html

Java: record User(String name, int age) {}
来源：http://dali.yanxiufei.cn/Article/details/gtlrqgscno.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cdnleiting.top/Article/details/gtqysmdkyw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnqzz.top/Article/details/gtpqydfdij.html

C#:   record User(string Name, int Age);
来源：http://dali.svipenyu.cn/Article/details/gtctlkmtkc.html

[G15] 枚举
来源：http://dali.9152youxi.cn/Article/details/gtyvpixjxv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebyxfnxk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.kuanghao11.cn/Article/details/gtligokrba.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhiwuduotai.top/Article/details/gtcruxsgri.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gtqdqucbjd.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhixingplan.top/Article/details/gtubikzebc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.pycfn.com/Article/details/gtamzilokh.html


<!-- 参考信息 -->