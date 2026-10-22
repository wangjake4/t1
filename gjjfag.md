代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jiagoushi.top/Article/details/gthryrghrn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.dianchejie.cn/Article/details/gtmxrmepra.html

C#:   1234567.ToString("N0")
来源：http://dali.hammf.cn/Article/details/gtclzrkiim.html

[E17] 首字母大写
来源：http://dali.zhengqikj.top/Article/details/gtdusmqjct.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinghuilouyu.cn/Article/details/gtucvfkifo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ppjwa.cn/Article/details/gtuihxeogt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shuidangran.top/Article/details/gtgusewzka.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shzxlz.cn/Article/details/gtgyxvixtj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cheryme.top/Article/details/gtwwznlwgo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.guannengcc.top/Article/details/gtticsvdch.html

Ruby: s.capitalize
来源：http://dali.xylfe.cn/Article/details/gtbugismlo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tanke756.top/Article/details/gtyiebrxet.html

[E18] 模板占位符替换
来源：http://dali.xuanzx.com/Article/details/gtjxtggxmq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangdashe.top/Article/details/gtcxsjbayh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtidtradib.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtgzvnvcnf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gtarltkvps.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gtqhwwrlud.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtajfgunmg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhengqikj.top/Article/details/gtqitnwqox.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nwbrower.top/Article/details/gtycjowxze.html

[E19] 多行文本按行拆分
来源：http://dali.c1oappe.top/Article/details/gtkfzwlyfq.html

Py:   s.splitlines()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvsgikydq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtsuimlbys.html

JS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gticklwayl.html

TS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gtwqewqcfr.html

Java: s.lines().toList()
来源：http://dali.zycfv.cn/Article/details/gtrkbgfpgb.html

Go:   strings.Split(s, "\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtrrrsbumr.html

Ruby: s.lines
来源：http://dali.pengpengdd.cyou/Article/details/gtiitdtvyy.html

C#:   s.Split('\n')
来源：http://dali.hysaishi.cn/Article/details/gtxcpwnlod.html

[E20] 判断字符串是否为空
来源：http://dali.yj202588.top/Article/details/gtsfebchhv.html

Py:   if not s:
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkphecgiq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xylfe.cn/Article/details/gtngcaferl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenlongwang.top/Article/details/gtbgfkibxl.html

TS:   if (s === "") {}
来源：http://dali.tanke756.top/Article/details/gtcxivvxtd.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangdashe.top/Article/details/gtgqwpjtdw.html

Go:   if s == "" {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtplkbxkzs.html

Ruby: if s.empty?
来源：http://dali.guowangkeji.top/Article/details/gtiqjwbaof.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.redwolf501.top/Article/details/gtfggryfvx.html

[E21] 超长截断加省略号
来源：http://dali.jinqigufen.top/Article/details/gtbafyznuw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cheryme.top/Article/details/gteyxnrrdb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gttgoqfzpt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtjyijujgt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gthoumiywf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtsgsvyahs.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cdnleiting.top/Article/details/gtffrwqgek.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.fengsongda.top/Article/details/gttgzbbjgs.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxeuglnoi.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258888.top/Article/details/gtzhybnvhi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gotoacloud.top/Article/details/gtjufxspht.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gttoiwbadm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258888.top/Article/details/gtpllcttnb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gtrmyymxxu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyncompul.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hnqzz.top/Article/details/gtmhprmepu.html

Ruby: s.bytesize;  s.length
来源：http://dali.gzhubu.top/Article/details/gtbnlkpblu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.svipenyu.cn/Article/details/gtlwluaant.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtvnqdaaww.html

F. 文件与目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtepvapkgg.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtkvcpwyly.html

[F01] 读取整个文件
来源：http://dali.nwbrower.top/Article/details/gtauahmtvu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmgfzbtf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtbjmeimgf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.svipenyu.cn/Article/details/gtjpmfvwxu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gtwacdwado.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtbyrtdivd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zdqjudy.top/Article/details/gtbjicqlmx.html

Ruby: File.read("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtlniwmwre.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtmazizmeb.html

[F02] 逐行读取文件
来源：http://dali.gzhubu.top/Article/details/gtackgqxnw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdywsqxo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cashguo.top/Article/details/gtkgrzmbuw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gtlvsdmxrp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cashguo.top/Article/details/gtdufwcpmo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gtzgntehnd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hongshengwenyu.top/Article/details/gteqxkdiyb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shangyingyoupin.top/Article/details/gtequfvrxr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jyoumei.cn/Article/details/gttfyxeygh.html

[F03] 写入文件（覆盖）
来源：http://dali.zhoulong.xyz/Article/details/gtjlycmdba.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cqqwz.cn/Article/details/gtnmvhqeml.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sweek.top/Article/details/gtxhjsdqrx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gtfnkfkzfh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gtokaoyqbq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.guowangkeji.top/Article/details/gttuiysiam.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cashguo.top/Article/details/gtoycbipda.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xylfe.cn/Article/details/gtshsqedyp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj20258.top/Article/details/gtmclevdon.html

[F04] 追加写入文件
来源：http://dali.fzhhl.top/Article/details/gtdehkqcxc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zdqjudy.top/Article/details/gtfmscyqnn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinqigufen.top/Article/details/gtcwntxvri.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gttlrtgfvn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gttryfladj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinqigufen.top/Article/details/gtshfzyyhs.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtquazpatt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenjidiqi.icu/Article/details/gtwehhrylq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gtixniktvg.html

[F05] 判断文件或目录是否存在
来源：http://dali.ppjwa.cn/Article/details/gtxivkxfwx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guowangkeji.top/Article/details/gtgyqbsqac.html

PHP:  file_exists("a.txt");
来源：http://dali.meibo888.top/Article/details/gtzjfwjuvn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtfwnbrmmf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtbzeadbky.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgkwksgn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyoplqvuf.html

Ruby: File.exist?("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtnnnqmlto.html

C#:   File.Exists("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtmzfcyddi.html

[F06] 删除文件
来源：http://dali.cashguo.top/Article/details/gtcmhktjmq.html

Py:   os.remove("a.txt")
来源：http://dali.yonumen.top/Article/details/gtmpmcaflc.html

PHP:  unlink("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmniviqb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtqnskpmdb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtkmmqscml.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gthciwzhdj.html

Go:   os.Remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gtagrhsxyi.html

Ruby: File.delete("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtxqrtbafp.html

C#:   File.Delete("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtawwufbpy.html

[F07] 创建目录（含多级）
来源：http://dali.tianlin.xyz/Article/details/gtwnsoozty.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sysykeji.top/Article/details/gtwgvlapox.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinqigfzy.top/Article/details/gtiupkqlbf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.bjfxy.top/Article/details/gtnffaibmz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gtqjjflbgj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258.top/Article/details/gthnakggzt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hnqzz.top/Article/details/gteilqfznc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zycfv.cn/Article/details/gtonwhbtoj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nanxuanxn.top/Article/details/gtozhygple.html

[F08] 遍历目录
来源：http://dali.zycfv.cn/Article/details/gtgdqnuuak.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yvedp.cn/Article/details/gtwhbcpxqo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jianghu66.top/Article/details/gtltauhivn.html

JS:   fs.readdirSync("dir")
来源：http://dali.xuanzx.com/Article/details/gtvcntutbb.html

TS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gtymtecega.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gtselqskbo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.smart0.xyz/Article/details/gtewnjxaih.html

Ruby: Dir.children("dir")
来源：http://dali.zhengqikj.top/Article/details/gtdqlcjpri.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xinyue.icu/Article/details/gtyzjztnlh.html

[F09] 获取文件大小
来源：http://dali.gaohongyu789.top/Article/details/gthxdjrpmx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtngknyzkj.html

PHP:  filesize("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtoxptohyf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sxryk.cn/Article/details/gtcqbejvhv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmcpfszrc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtvqfetulw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.fzhhl.top/Article/details/gtyarsaszx.html

Ruby: File.size("a.txt")
来源：http://dali.sweek.top/Article/details/gthdikmjyv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jqgfzy.top/Article/details/gtlfwjidqg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangtech.top/Article/details/gtkvkyspex.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gttgcjuyqs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmmbbadw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gthcduczxo.html

TS:   path.extname("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtdlyllkrm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.9152youxi.cn/Article/details/gtgaujdbtz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtqndwfgzp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gthdtkwene.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gthplalrhe.html

[F11] 复制与移动文件
来源：http://dali.vqdsnc.cn/Article/details/gtuwktrodn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtgpnnydmj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hnqzz.top/Article/details/gtkyysepdr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtvlfvrqtu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gthrwhvpiw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.316326.xyz/Article/details/gtzukgbeum.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shuidangran.top/Article/details/gthsbamznd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtbjiguuyk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinqigfzy.top/Article/details/gtzridiwuc.html

[F12] CSV 读写
来源：http://dali.jyoumei.cn/Article/details/gtxxkqzvkf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.smart0.xyz/Article/details/gtfjdhsxyq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.c1oappe.top/Article/details/gtquwtyaxc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258.top/Article/details/gtrygslopm.html

TS:   // 同上
来源：http://dali.cucudq.cn/Article/details/gtgxamzter.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xziqi.cn/Article/details/gthdzhrxma.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ppjwa.cn/Article/details/gtnazkqyci.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenjidiqi.icu/Article/details/gtplgxmqld.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xziqi.cn/Article/details/gtvikifcfh.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gthdudmkhy.html

G. 面向对象
来源：http://dali.yuxming.cn/Article/details/gtegmxeblb.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjgjveur.html

[G01] 定义类
来源：http://dali.yueranfly.top/Article/details/gthicxcprs.html

Py:   class User: pass
来源：http://dali.gotoacloud.top/Article/details/gtinvmoreh.html

PHP:  class User {}
来源：http://dali.ehwqpu.com/Article/details/gtbncynfch.html

JS:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gtkixnptkn.html

TS:   class User { name: string = ""; }
来源：http://dali.kuanghao11.cn/Article/details/gtsryewuap.html

Java: class User {}
来源：http://dali.jianghu66.top/Article/details/gtoqyxvxhh.html

Go:   type User struct { Name string }
来源：http://dali.gzhubu.top/Article/details/gtygpgdccy.html

Ruby: class User; end
来源：http://dali.cucudq.cn/Article/details/gtjminkqtd.html

C#:   class User {}
来源：http://dali.hywenlv.cn/Article/details/gtezpgesee.html

[G02] 构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtgniooqml.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.mhx1999.top/Article/details/gtbjlpzpxo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftlhrgys.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nanxinkj.top/Article/details/gtdgbhxreu.html

TS:   constructor(public name: string) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdgkwfmr.html

Java: User(String name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gttfggbdpu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cheryme.top/Article/details/gtsjfdkxwi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.svipenyu.cn/Article/details/gtmxlfbsdx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yueranfly.top/Article/details/gtajkuniqh.html

[G03] 实例属性
来源：http://dali.sweek.top/Article/details/gtagxkqozs.html

Py:   self.name = "x"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbgizqmn.html

PHP:  public string $name = "x";
来源：http://dali.zycfv.cn/Article/details/gtqnwbixlw.html

JS:   this.name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtorobhaij.html

TS:   name: string = "x";
来源：http://dali.gzhubu.top/Article/details/gtkavumxsj.html

Java: private String name;
来源：http://dali.xylfe.cn/Article/details/gtfqnpqdfk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.dianchejie.cn/Article/details/gtoliuqmcq.html

Ruby: @name = "x"
来源：http://dali.yj20258888.top/Article/details/gtsyfezmvx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.fengsongda.top/Article/details/gtgfflgetg.html

[G04] 定义方法
来源：http://dali.wangshuangyany.cn/Article/details/gtaazqvyzp.html

Py:   def greet(self): return self.name
来源：http://dali.xziqi.cn/Article/details/gtblcrljsi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtcispglgz.html

JS:   greet() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtldicpqol.html

TS:   greet(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtpeeubzdl.html

Java: String greet() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtgsowahbg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gtwptwwkoa.html

Ruby: def greet; @name; end
来源：http://dali.sysykeji.top/Article/details/gtpzgqznad.html

C#:   public string Greet() => Name;
来源：http://dali.andypj.xyz/Article/details/gtdwcczekt.html

[G05] 继承
来源：http://dali.cheryme.top/Article/details/gtqevlqprw.html

Py:   class Admin(User): pass
来源：http://dali.ybcxt.top/Article/details/gtkrivqdic.html

PHP:  class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtjisinnhu.html

JS:   class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtxrrgydlm.html

TS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtwdeieesa.html

Java: class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtrlybvmkz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgfzy.top/Article/details/gtonseaeid.html

Ruby: class Admin < User; end
来源：http://dali.pycfn.com/Article/details/gtqyfmdspl.html

C#:   class Admin : User {}
来源：http://dali.hnqzz.top/Article/details/gtclnhnvtv.html

[G06] 重写方法
来源：http://dali.yonumen.top/Article/details/gtoyazledv.html

Py:   def greet(self): return "admin"
来源：http://dali.shzxlz.cn/Article/details/gtclmxydqd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtxgaymjgk.html

JS:   greet() { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxqeaagcq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtuwyyravx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtppjjdmcx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.mhx1999.top/Article/details/gthofthzuw.html

Ruby: def greet; "admin"; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhoouzpk.html

C#:   public override string Greet() => "admin";
来源：http://dali.yueranfly.top/Article/details/gtsdqsyldu.html

[G07] 调用父类方法
来源：http://dali.yanxiufei.cn/Article/details/gtockxhfpe.html

Py:   super().greet()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgcdmqczw.html

PHP:  parent::greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtnxwyaczl.html

JS:   super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gtmsatlcis.html

TS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gtngjcqcvp.html

Java: super.greet();
来源：http://dali.hnqzz.top/Article/details/gtcdodcupi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhiwuduotai.top/Article/details/gtyuohmknn.html

Ruby: super
来源：http://dali.nwbrower.top/Article/details/gtdaptcxmo.html

C#:   base.Greet();
来源：http://dali.ehwqpu.com/Article/details/gtciunlwqp.html

[G08] 静态方法与属性
来源：http://dali.c1oappe.top/Article/details/gtrnnqisdc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.fengsongda.top/Article/details/gtqjtepbre.html

PHP:  public static function f() {}
来源：http://dali.yj20258888.top/Article/details/gtlzdcwghe.html

JS:   static f() {}
来源：http://dali.chenzaomai.com/Article/details/gtakvgzavh.html

TS:   static f(): void {}
来源：http://dali.nwbrower.top/Article/details/gtsucxmuxs.html

Java: static void f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtgkyqtncq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sysykeji.top/Article/details/gtejwcbxsp.html

Ruby: def self.f; end
来源：http://dali.shuidangran.top/Article/details/gtacuouijb.html

C#:   public static void F() {}
来源：http://dali.zdqjudy.top/Article/details/gtnqttskha.html

[G09] 接口 / 抽象类
来源：http://dali.sweek.top/Article/details/gtqmttuuen.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.smart0.xyz/Article/details/gtskylswdu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fengsongda.top/Article/details/gtjuczsfzo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sweek.top/Article/details/gtmcfmkqis.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxinkj.top/Article/details/gthwvuhhlr.html

Java: interface Shape { double area(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtwrncepml.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xziqi.cn/Article/details/gtefpfadxi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.iojbl.cn/Article/details/gtkebyjwuf.html

C#:   interface IShape { double Area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtphihdohj.html

[G10] 访问控制
来源：http://dali.cucudq.cn/Article/details/gtbtuiktjg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigfzy.top/Article/details/gtdarqgkyf.html

PHP:  public / protected / private
来源：http://dali.wangdashe.top/Article/details/gtluydlrca.html

JS:   #private 字段；其余公开
来源：http://dali.hfpthk.cn/Article/details/gtskkjauem.html

TS:   public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjyvltcs.html

Java: public / protected / private / 默认包级
来源：http://dali.birdmap.top/Article/details/gtwczgytqh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hongshengwenyu.top/Article/details/gtrxltujer.html

Ruby: public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gtxmnqkvjv.html

C#:   public / protected / private / internal
来源：http://dali.mhx1999.top/Article/details/gtvxhwjuua.html

[G11] getter / setter
来源：http://dali.jiagoushi.top/Article/details/gtuzefanvt.html

Py:   @property 与 @x.setter
来源：http://dali.wangdashe.top/Article/details/gtjztlvtxf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gthmefdfnz.html

JS:   get name() { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gtjrabfvzj.html

TS:   get name(): string { return this._name; }
来源：http://dali.dianchejie.cn/Article/details/gtnoxhckab.html

Java: public String getName() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gteirzcxix.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtoeddyoiz.html

Ruby: attr_accessor :name
来源：http://dali.hfpthk.cn/Article/details/gtspykrlft.html

C#:   public string Name { get; set; }
来源：http://dali.daxiang520.top/Article/details/gteghkocau.html

[G12] 对象转字符串
来源：http://dali.tanke756.top/Article/details/gtsxmccwsl.html

Py:   def __str__(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gtdrtuzykz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gtxxeuxsdl.html

JS:   toString() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtsfmwwfsu.html

TS:   toString(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtjotnzbhf.html

Java: @Override public String toString() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gtuhhcdiol.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gtvnwzxwxe.html

Ruby: def to_s; @name; end
来源：http://dali.tian-w.cn/Article/details/gtysowuhwb.html

C#:   public override string ToString() => Name;
来源：http://dali.ehwqpu.com/Article/details/gtjusstebr.html

[G13] 判断对象类型
来源：http://dali.jyoumei.cn/Article/details/gthekduepj.html

Py:   isinstance(u, User)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcxiyeirm.html

PHP:  $u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtaycqaqmg.html

JS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtymrwmrob.html

TS:   u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtzkljmyko.html

Java: u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtulieqbod.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cashguo.top/Article/details/gtmbkqprui.html

Ruby: u.is_a?(User)
来源：http://dali.tanke756.top/Article/details/gtnwkedqgq.html

C#:   u is User
来源：http://dali.jianghu66.top/Article/details/gtfguqkzhr.html

[G14] 数据类 / record
来源：http://dali.guannengcc.top/Article/details/gtnzslibeg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yanxiufei.cn/Article/details/gtevswfnvc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hammf.cn/Article/details/gtyucjnnbp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkefzlndu.html

TS:   type User = { name: string; age: number };
来源：http://dali.ehwqpu.com/Article/details/gtbxlvgoze.html

Java: record User(String name, int age) {}
来源：http://dali.cucudq.cn/Article/details/gtjtegjept.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shzxlz.cn/Article/details/gtnbipzesk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guowangkeji.top/Article/details/gtjlczafqr.html

C#:   record User(string Name, int Age);
来源：http://dali.jlsjyb.cn/Article/details/gtbrtqsaov.html

[G15] 枚举
来源：http://dali.gotoacloud.top/Article/details/gtqmivbqqz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fengsongda.top/Article/details/gtvsbnhqec.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jqgufenzy.top/Article/details/gtfaixcray.html


<!-- 参考信息 -->