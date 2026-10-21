代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.andypj.xyz/Article/details/gtlwdejoif.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hywenlv.cn/Article/details/gtfxdnrwjn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xinyue.icu/Article/details/gtmzagiaqd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.iojbl.cn/Article/details/gtawfjgirs.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tianlin.xyz/Article/details/gthawvhplr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmygbnuid.html

C#:   1234567.ToString("N0")
来源：http://dali.0kj1m.cn/Article/details/gtsaobmigm.html

[E17] 首字母大写
来源：http://dali.yangfankeji.com/Article/details/gtoiymgjsg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nwbrower.top/Article/details/gtumezpyaw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jqgufenzy.top/Article/details/gtaopmswkx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daria6918.cn/Article/details/gtzrqsvoxi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gtqnxjextt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.vqdsnc.cn/Article/details/gtkxqhpzyq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shuidangran.top/Article/details/gtbakrfljy.html

Ruby: s.capitalize
来源：http://dali.zhongyouzk.top/Article/details/gtuormjkru.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tian-w.cn/Article/details/gtfmyjurfc.html

[E18] 模板占位符替换
来源：http://dali.meibo888.top/Article/details/gtdetynnqa.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.dianchejie.cn/Article/details/gtozgeyprf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sufxvd.cn/Article/details/gtoqfselzq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtqshzeahj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtomwmvxpd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gttskdiolr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtcgynnhew.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhcrboql.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.guannengcc.top/Article/details/gtpnmwaqyp.html

[E19] 多行文本按行拆分
来源：http://dali.xuanzx.com/Article/details/gtkywiinnt.html

Py:   s.splitlines()
来源：http://dali.ehwqpu.com/Article/details/gtufzlsvsi.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtmxbchwfw.html

JS:   s.split(/\r?\n/)
来源：http://dali.cheryme.top/Article/details/gtflsoidti.html

TS:   s.split(/\r?\n/)
来源：http://dali.yangfankeji.com/Article/details/gtxxxtcswp.html

Java: s.lines().toList()
来源：http://dali.aizwys.cn/Article/details/gtocyyorkb.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenzaomai.com/Article/details/gtqwuxgfhf.html

Ruby: s.lines
来源：http://dali.pengpengdd.cyou/Article/details/gtciadboym.html

C#:   s.Split('\n')
来源：http://dali.quarkkingdee.top/Article/details/gtiqgkruku.html

[E20] 判断字符串是否为空
来源：http://dali.cqqwz.cn/Article/details/gtgjrsdtia.html

Py:   if not s:
来源：http://dali.fzhhl.top/Article/details/gtpuhwujzn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj20258888.top/Article/details/gtjueywmld.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.dianchejie.cn/Article/details/gtbvgjlxna.html

TS:   if (s === "") {}
来源：http://dali.gaohongyu789.top/Article/details/gtmiizbzvo.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgfsjkyc.html

Go:   if s == "" {}
来源：http://dali.yongpay.top/Article/details/gtwhitpgxl.html

Ruby: if s.empty?
来源：http://dali.jyoumei.cn/Article/details/gtnzpoelft.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.meibo888.top/Article/details/gtfpxnrohj.html

[E21] 超长截断加省略号
来源：http://dali.guannengcc.top/Article/details/gtsfprweqc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nwbrower.top/Article/details/gtrncjrccn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gtnllerqkx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtozqmofbp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtyqqbczne.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtwgtrhzii.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.guannengcc.top/Article/details/gtqpobnrig.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258.top/Article/details/gtvzjpmwtf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmgxnptv.html

[E22] 字节长度与字符长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtufrxzjmp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daria6918.cn/Article/details/gtgrqdiaus.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gtolkrvrsr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sufxvd.cn/Article/details/gtdcxqndkk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gttomtobnb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.redwolf501.top/Article/details/gtdfnmoewb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hywenlv.cn/Article/details/gtrftqbfcd.html

Ruby: s.bytesize;  s.length
来源：http://dali.snrcjt.cn/Article/details/gtcwwvthuw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cheryme.top/Article/details/gtatpipekj.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtyutkxhzr.html

F. 文件与目录
来源：http://dali.svipenyu.cn/Article/details/gtngrpswwi.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtjzvjeicb.html

[F01] 读取整个文件
来源：http://dali.hysaishi.cn/Article/details/gtxekvfxfx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.guowangkeji.top/Article/details/gtpmpcsfxo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtkurohacz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.guannengcc.top/Article/details/gttttgzaaa.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.smart0.xyz/Article/details/gtndcrmyyk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtkmbfpmxa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ydzc1.top/Article/details/gtguvywofc.html

Ruby: File.read("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtcvbweodm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtfzcwjmkf.html

[F02] 逐行读取文件
来源：http://dali.gaohongyu789.top/Article/details/gtwashsiyz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hnxiangtu.top/Article/details/gtxcicznlv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj202588.top/Article/details/gtnvugvxrt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cqqwz.cn/Article/details/gtwnwyyamy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cashguo.top/Article/details/gtuutbwqzk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gtkubslcxv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.9152youxi.cn/Article/details/gtsipilirp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.mhx1999.top/Article/details/gtxmipcwmx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shangyingyoupin.top/Article/details/gtuxrgltjr.html

[F03] 写入文件（覆盖）
来源：http://dali.fengsongda.top/Article/details/gttxpwxzuo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yvedp.cn/Article/details/gtlhqbindm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhoulong.xyz/Article/details/gtnbaibqev.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangdashe.top/Article/details/gttofhgorp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtegayyjuo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yueranfly.top/Article/details/gtpwonsuqf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.quarkkingdee.top/Article/details/gtpiavbhai.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gtoxzlpjmx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfyekumib.html

[F04] 追加写入文件
来源：http://dali.ybcxt.top/Article/details/gtgpnhrmbf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtficrptyw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jianghu66.top/Article/details/gtxhvcmyqn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjskgkdgk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtsgjpnctp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgcerrcgc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jianghu66.top/Article/details/gtsyzlnaqw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gzhubu.top/Article/details/gtjbsrqiao.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.redwolf501.top/Article/details/gtixhghwjn.html

[F05] 判断文件或目录是否存在
来源：http://dali.gzhubu.top/Article/details/gtoqaiisvt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ivvv.top/Article/details/gthzsyiqdn.html

PHP:  file_exists("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtxibkkkwr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtdnukkhzb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtlhrfywip.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gthgzivxlg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hysaishi.cn/Article/details/gtomwaixzd.html

Ruby: File.exist?("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtdpkedzdx.html

C#:   File.Exists("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtfawmcamj.html

[F06] 删除文件
来源：http://dali.guowangkeji.top/Article/details/gtzplqydkh.html

Py:   os.remove("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtlcanxzzu.html

PHP:  unlink("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtgfablmdi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtupiqvtcu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtgzusaiib.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtujbfdliu.html

Go:   os.Remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gttctfajhl.html

Ruby: File.delete("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtvanypyej.html

C#:   File.Delete("a.txt");
来源：http://dali.cashguo.top/Article/details/gtxzwdhwri.html

[F07] 创建目录（含多级）
来源：http://dali.hfpthk.cn/Article/details/gtxxptoiku.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ehwqpu.com/Article/details/gtmygyrmxq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shzxlz.cn/Article/details/gtwquzkycj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gtxzhmgwdi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.smart0.xyz/Article/details/gttposzvlu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yueranfly.top/Article/details/gtkqqaaujj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.fengsongda.top/Article/details/gtoiazrfvk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cheryme.top/Article/details/gtezyqjcyv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hammf.cn/Article/details/gtklomosyb.html

[F08] 遍历目录
来源：http://dali.snrcjt.cn/Article/details/gtxgqgdezg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.kuanghao11.cn/Article/details/gtlhlfsigl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jianghu66.top/Article/details/gtwnywswin.html

JS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gtzehuayze.html

TS:   fs.readdirSync("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtmrjrhznk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gtojindbzi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtjlhelycs.html

Ruby: Dir.children("dir")
来源：http://dali.jqgfzy.top/Article/details/gtnocmplex.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttjcaziow.html

[F09] 获取文件大小
来源：http://dali.andypj.xyz/Article/details/gtoooasrwj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yonumen.top/Article/details/gtqdatuajk.html

PHP:  filesize("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtedyundqm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gtielumcjl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sxryk.cn/Article/details/gtlyqgvzan.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtncxrblvx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zycfv.cn/Article/details/gtwmpwbwpy.html

Ruby: File.size("a.txt")
来源：http://dali.hammf.cn/Article/details/gtsdrqtuhy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cqqwz.cn/Article/details/gtwpbtiiiz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.aibaodan.cn/Article/details/gtylbtywet.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtitinmntr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.iojbl.cn/Article/details/gtcawoxasc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtqeyjowsy.html

TS:   path.extname("a.txt")
来源：http://dali.havefunace.top/Article/details/gtvehxlfll.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guannengcc.top/Article/details/gtruyzkfuk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtgyjeypkc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gttupzqvro.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gttetnwdzt.html

[F11] 复制与移动文件
来源：http://dali.sweek.top/Article/details/gtbjuvitun.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtnbejenvj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tanke756.top/Article/details/gtjfrrahhl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtdkmjsckl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtgjmyzbew.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xylfe.cn/Article/details/gtrmgisybe.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuetiantiany.cn/Article/details/gteidkxpur.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtayfrlycd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gtqccabqgx.html

[F12] CSV 读写
来源：http://dali.gzhubu.top/Article/details/gtnzeancxn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ehwqpu.com/Article/details/gthewbetcv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnxiangtu.top/Article/details/gtiwjcjwgp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.snrcjt.cn/Article/details/gtrssvjaha.html

TS:   // 同上
来源：http://dali.jlsjyb.cn/Article/details/gtctojgiyt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgufenzy.top/Article/details/gtvkoqhpng.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nanxinkj.top/Article/details/gthpvmfsek.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hongshengwenyu.top/Article/details/gtgykmsixr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenzaomai.com/Article/details/gthqfpbuag.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtycucxnqz.html

G. 面向对象
来源：http://dali.hnqzz.top/Article/details/gtfkyixjuj.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtmigixslb.html

[G01] 定义类
来源：http://dali.hnqzz.top/Article/details/gtcexuaaoc.html

Py:   class User: pass
来源：http://dali.zhengqikj.top/Article/details/gtwahfwblx.html

PHP:  class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtenzbviay.html

JS:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gttwjhcgzr.html

TS:   class User { name: string = ""; }
来源：http://dali.snrcjt.cn/Article/details/gteqazejfs.html

Java: class User {}
来源：http://dali.dianchejie.cn/Article/details/gteadsmrqy.html

Go:   type User struct { Name string }
来源：http://dali.xuetiantiany.cn/Article/details/gtfaocbbjz.html

Ruby: class User; end
来源：http://dali.jinqigfzy.top/Article/details/gtnqfjxjjo.html

C#:   class User {}
来源：http://dali.smart0.xyz/Article/details/gtmbznwduh.html

[G02] 构造函数
来源：http://dali.daria6918.cn/Article/details/gthshsfhlw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ydzc1.top/Article/details/gtmjqjmbsm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuanzx.com/Article/details/gteodspmyp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtxpnnbhwy.html

TS:   constructor(public name: string) {}
来源：http://dali.havefunace.top/Article/details/gtgvrdxrqx.html

Java: User(String name) { this.name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gtphegwywa.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.pengpengdd.cyou/Article/details/gtkarwiehl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhixingplan.top/Article/details/gthceqfqml.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtvjpnxqob.html

[G03] 实例属性
来源：http://dali.zhixingplan.top/Article/details/gtuofctuje.html

Py:   self.name = "x"
来源：http://dali.quarkkingdee.top/Article/details/gtgsmwhfvj.html

PHP:  public string $name = "x";
来源：http://dali.wangdashe.top/Article/details/gtpafvbxsk.html

JS:   this.name = "x";
来源：http://dali.shzxlz.cn/Article/details/gtxkfribdt.html

TS:   name: string = "x";
来源：http://dali.svipenyu.cn/Article/details/gtprxekwng.html

Java: private String name;
来源：http://dali.jinqigufen.top/Article/details/gtasebqgzu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhongyouzk.top/Article/details/gtxudqpihk.html

Ruby: @name = "x"
来源：http://dali.shuidangran.top/Article/details/gtddgiaksd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.0kj1m.cn/Article/details/gtgdlxcefm.html

[G04] 定义方法
来源：http://dali.gzhubu.top/Article/details/gtjgpgztpq.html

Py:   def greet(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gtfjpsvyxr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gtpzrmwlly.html

JS:   greet() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtywkevamr.html

TS:   greet(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtemnetbaa.html

Java: String greet() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtikvzywxa.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtnsgxwcjb.html

Ruby: def greet; @name; end
来源：http://dali.daxiang520.top/Article/details/gtahfrknyb.html

C#:   public string Greet() => Name;
来源：http://dali.zhixingplan.top/Article/details/gtvlgagftw.html

[G05] 继承
来源：http://dali.gotoacloud.top/Article/details/gtcsmkkyaz.html

Py:   class Admin(User): pass
来源：http://dali.yuxming.cn/Article/details/gtnhtowotc.html

PHP:  class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdxuzhid.html

JS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gthfkzjnpj.html

TS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtjgqblhfv.html

Java: class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gtjuvlhxaa.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aizwys.cn/Article/details/gtbwfqpxxn.html

Ruby: class Admin < User; end
来源：http://dali.nanxinkj.top/Article/details/gtexhuwunt.html

C#:   class Admin : User {}
来源：http://dali.ybcxt.top/Article/details/gtksubukul.html

[G06] 重写方法
来源：http://dali.smart0.xyz/Article/details/gtnqcrpbff.html

Py:   def greet(self): return "admin"
来源：http://dali.guannengcc.top/Article/details/gthfaufsme.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtibuazjmv.html

JS:   greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtxgyzmatt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gttduxgywa.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtvjwxbixg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.snrcjt.cn/Article/details/gtuqxrsabx.html

Ruby: def greet; "admin"; end
来源：http://dali.pycfn.com/Article/details/gtjeqnglev.html

C#:   public override string Greet() => "admin";
来源：http://dali.daxiang520.top/Article/details/gtpimuvpow.html

[G07] 调用父类方法
来源：http://dali.guowangkeji.top/Article/details/gtkhdtoica.html

Py:   super().greet()
来源：http://dali.yvedp.cn/Article/details/gtijncwist.html

PHP:  parent::greet();
来源：http://dali.yuanzhike.top/Article/details/gtsehahqid.html

JS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gtceaxfugf.html

TS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gtwunsvlvt.html

Java: super.greet();
来源：http://dali.zhengqikj.top/Article/details/gtdrzsbleg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cheryme.top/Article/details/gtsfpnrrdh.html

Ruby: super
来源：http://dali.sufxvd.cn/Article/details/gtozsdibcr.html

C#:   base.Greet();
来源：http://dali.yonumen.top/Article/details/gtgaydqbpu.html

[G08] 静态方法与属性
来源：http://dali.chenlongwang.top/Article/details/gtszovyoii.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ehwqpu.com/Article/details/gtypilbucp.html

PHP:  public static function f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtcnegsxsu.html

JS:   static f() {}
来源：http://dali.cdnleiting.top/Article/details/gtqoyrglfh.html

TS:   static f(): void {}
来源：http://dali.hongshengwenyu.top/Article/details/gtaypmtlia.html

Java: static void f() {}
来源：http://dali.chenzaomai.com/Article/details/gtsvobznax.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sweek.top/Article/details/gtzcbnhykt.html

Ruby: def self.f; end
来源：http://dali.svipenyu.cn/Article/details/gthnyonexn.html

C#:   public static void F() {}
来源：http://dali.dashuyun.cn/Article/details/gtkhignnjc.html

[G09] 接口 / 抽象类
来源：http://dali.wangdashe.top/Article/details/gtfpclppzs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.meibo888.top/Article/details/gtopuoymox.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ivvv.top/Article/details/gtzmrteycp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.smart0.xyz/Article/details/gtjutburzg.html

TS:   interface Shape { area(): number; }
来源：http://dali.tanke756.top/Article/details/gtmuklbrlg.html

Java: interface Shape { double area(); }
来源：http://dali.yuxming.cn/Article/details/gtzeocsrre.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenjidiqi.icu/Article/details/gtydqtxbmk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xylfe.cn/Article/details/gtikyzfltb.html

C#:   interface IShape { double Area(); }
来源：http://dali.fzhhl.top/Article/details/gtfpppxhcj.html

[G10] 访问控制
来源：http://dali.hammf.cn/Article/details/gttjmnsvdr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gaohongyu789.top/Article/details/gticoznbsc.html

PHP:  public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gtmckyvcuc.html

JS:   #private 字段；其余公开
来源：http://dali.yongpay.top/Article/details/gtnsiwfcpd.html

TS:   public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gtbypwdyib.html

Java: public / protected / private / 默认包级
来源：http://dali.sweek.top/Article/details/gttcdqnaqj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhiwuduotai.top/Article/details/gtcaqcknww.html

Ruby: public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtuzdqmyzv.html

C#:   public / protected / private / internal
来源：http://dali.kuanghao11.cn/Article/details/gtxobxjzey.html

[G11] getter / setter
来源：http://dali.tanke756.top/Article/details/gtbqmlzfyd.html

Py:   @property 与 @x.setter
来源：http://dali.zycfv.cn/Article/details/gtfqbcwnaq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtawgwxfgr.html

JS:   get name() { return this._name; }
来源：http://dali.guowangkeji.top/Article/details/gtwtrmrnjq.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj202588.top/Article/details/gtzktthwpr.html

Java: public String getName() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtjfhqbzby.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtpsgrzlut.html

Ruby: attr_accessor :name
来源：http://dali.zhixingplan.top/Article/details/gtfgsjbtkp.html

C#:   public string Name { get; set; }
来源：http://dali.smart0.xyz/Article/details/gtkrnwmunu.html

[G12] 对象转字符串
来源：http://dali.andypj.xyz/Article/details/gtyxdxgsxr.html

Py:   def __str__(self): return self.name
来源：http://dali.ehwqpu.com/Article/details/gtedpjhkpy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtlnjcveic.html

JS:   toString() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtqdeshwhr.html

TS:   toString(): string { return this.name; }
来源：http://dali.316326.xyz/Article/details/gtsmxprmdj.html

Java: @Override public String toString() { return name; }
来源：http://dali.fengsongda.top/Article/details/gtfpoquqct.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gteiscbylv.html

Ruby: def to_s; @name; end
来源：http://dali.xuanzx.com/Article/details/gtoydryrlx.html

C#:   public override string ToString() => Name;
来源：http://dali.andypj.xyz/Article/details/gtuddpvuth.html

[G13] 判断对象类型
来源：http://dali.jianghu66.top/Article/details/gtkihyrqyk.html

Py:   isinstance(u, User)
来源：http://dali.xylfe.cn/Article/details/gtlavmleeb.html

PHP:  $u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtoyeihxvh.html

JS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtzhssrlkk.html

TS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtzlejeihu.html

Java: u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtwrwwfzlo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tian-w.cn/Article/details/gtopkypknp.html

Ruby: u.is_a?(User)
来源：http://dali.yvedp.cn/Article/details/gtkiferuxq.html

C#:   u is User
来源：http://dali.cdnleiting.top/Article/details/gtfyoqtobp.html

[G14] 数据类 / record
来源：http://dali.sweek.top/Article/details/gtbklhjwjh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yangfankeji.com/Article/details/gtqpnqjmeg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gotoacloud.top/Article/details/gtpnkidvvb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shuidangran.top/Article/details/gtyoocgyxp.html

TS:   type User = { name: string; age: number };
来源：http://dali.cheryme.top/Article/details/gtbsmimuxq.html

Java: record User(String name, int age) {}
来源：http://dali.hywenlv.cn/Article/details/gtpvjbmian.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shangyingyoupin.top/Article/details/gtazrskttt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fengsongda.top/Article/details/gtwebrdnhq.html


<!-- 参考信息 -->