代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.hywenlv.cn/Article/details/gtzqovthyx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gtbokhouvx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cashguo.top/Article/details/gtmegqfszp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258888.top/Article/details/gtrixrbpoa.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.aibaodan.cn/Article/details/gtnloirppu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cucudq.cn/Article/details/gtwoniyfuh.html

C#:   1234567.ToString("N0")
来源：http://dali.pycfn.com/Article/details/gtjjlubudy.html

[E17] 首字母大写
来源：http://dali.hnqzz.top/Article/details/gtftmljbkk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj20258.top/Article/details/gtgbcwrpjm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtdlwttwee.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yangfankeji.com/Article/details/gtvdfdpdoa.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sufxvd.cn/Article/details/gtinektalr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nanxinkj.top/Article/details/gtnvfmlbcx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gtxhfxnsts.html

Ruby: s.capitalize
来源：http://dali.jlsjyb.cn/Article/details/gttzaeirsg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yanxiufei.cn/Article/details/gtynejosse.html

[E18] 模板占位符替换
来源：http://dali.xuanzx.com/Article/details/gtdywusxlu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xylfe.cn/Article/details/gtjkqtjkkr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj202588.top/Article/details/gtlpgziyww.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtresyawkl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtxlxeubxe.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpatxxboh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtttawpkhb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.bjfxy.top/Article/details/gtlbiiwubz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tian-w.cn/Article/details/gtjngwjjfl.html

[E19] 多行文本按行拆分
来源：http://dali.shangyingyoupin.top/Article/details/gtuegrwcoz.html

Py:   s.splitlines()
来源：http://dali.yuanzhike.top/Article/details/gtpjjwscys.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ehwqpu.com/Article/details/gtukyhuoyg.html

JS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gtcrrvhkrp.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnqzz.top/Article/details/gtlerllyfe.html

Java: s.lines().toList()
来源：http://dali.iojbl.cn/Article/details/gtiqvzdpbc.html

Go:   strings.Split(s, "\n")
来源：http://dali.ehwqpu.com/Article/details/gtfbwehers.html

Ruby: s.lines
来源：http://dali.yuanzhike.top/Article/details/gtrxtfjacp.html

C#:   s.Split('\n')
来源：http://dali.meibo888.top/Article/details/gtkvaklzyi.html

[E20] 判断字符串是否为空
来源：http://dali.yvedp.cn/Article/details/gtfzjmyjjg.html

Py:   if not s:
来源：http://dali.tanke756.top/Article/details/gtvpkvbibe.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinqigufen.top/Article/details/gtamctsgfk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hysaishi.cn/Article/details/gtmcibsmyc.html

TS:   if (s === "") {}
来源：http://dali.jinqigfzy.top/Article/details/gtpykrjska.html

Java: if (s.isEmpty()) {}
来源：http://dali.cashguo.top/Article/details/gtocpbfdge.html

Go:   if s == "" {}
来源：http://dali.redwolf501.top/Article/details/gtgxedtrqp.html

Ruby: if s.empty?
来源：http://dali.chenjidiqi.icu/Article/details/gtnmxehoxw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jiagoushi.top/Article/details/gtyljlihln.html

[E21] 超长截断加省略号
来源：http://dali.mhx1999.top/Article/details/gtydkcklet.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhengqikj.top/Article/details/gtjyawhqof.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtlwqzcfdp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtlgbhofuc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gthmtreebu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtltphawxg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shuidangran.top/Article/details/gtbvcvoroi.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtgifwftgm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtastrysoq.html

[E22] 字节长度与字符长度
来源：http://dali.hnqzz.top/Article/details/gtxrxrxjzp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nanxinkj.top/Article/details/gtvmjfqpnm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtzltgemgz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtturmiwxy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtdpdneidw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinqigufen.top/Article/details/gtsfpfnkgn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj20258.top/Article/details/gtphctqckb.html

Ruby: s.bytesize;  s.length
来源：http://dali.yvedp.cn/Article/details/gtbtrmvuun.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgrftsxdb.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtnpkqlrlg.html

F. 文件与目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlzqjezkp.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtdzudgmgb.html

[F01] 读取整个文件
来源：http://dali.yueranfly.top/Article/details/gtggbcxtyw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.mhx1999.top/Article/details/gtvabfgptt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtqgjqxdee.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.c1oappe.top/Article/details/gtplstkmgx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.fengsongda.top/Article/details/gtekilnwtg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtgtxlbvoa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tian-w.cn/Article/details/gtucdlengb.html

Ruby: File.read("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtevskkend.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtatoghhnl.html

[F02] 逐行读取文件
来源：http://dali.sufxvd.cn/Article/details/gthibvtwwf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pengpengdd.cyou/Article/details/gtvmsokkgj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yangfankeji.com/Article/details/gtzcxwvjkb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gtajrnbfci.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gtyjhbqzmj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gtbgadprpx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.fengsongda.top/Article/details/gtdgjvrssf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gotoacloud.top/Article/details/gtloaamkkl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xziqi.cn/Article/details/gthwsewxtc.html

[F03] 写入文件（覆盖）
来源：http://dali.guannengcc.top/Article/details/gtrjbksjtm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xuanzx.com/Article/details/gtxwtudwrj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.316326.xyz/Article/details/gtyzozsopj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtglualkxp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gtqegcycxv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hnqzz.top/Article/details/gtfownknpx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gaohongyu789.top/Article/details/gtnzhjlujr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jianghu66.top/Article/details/gtedgvslwr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yueranfly.top/Article/details/gtmnshsetu.html

[F04] 追加写入文件
来源：http://dali.svipenyu.cn/Article/details/gtxeefeyfm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hnqzz.top/Article/details/gtgsbocuke.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jyoumei.cn/Article/details/gttntdixye.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtawjvcysg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtnzqycuzs.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsxjscbih.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cucudq.cn/Article/details/gtumbjlozo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.havefunace.top/Article/details/gtnwomauuw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hywenlv.cn/Article/details/gtqosrfhqm.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcykbbopq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.316326.xyz/Article/details/gtdcxjcotk.html

PHP:  file_exists("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gthhuokgnr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtbzjncfdq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtmuynxcqu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtdlkkjhze.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daxiang520.top/Article/details/gtxylxeluz.html

Ruby: File.exist?("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtdzsddoop.html

C#:   File.Exists("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtmibyddvi.html

[F06] 删除文件
来源：http://dali.fengsongda.top/Article/details/gthisaagtu.html

Py:   os.remove("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtomvjccfq.html

PHP:  unlink("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtcicfiwsc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtoqntmpro.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtqfzshsdj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gtdppxwxul.html

Go:   os.Remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gthpqhwbxu.html

Ruby: File.delete("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtzgnpizqo.html

C#:   File.Delete("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtummfpvvt.html

[F07] 创建目录（含多级）
来源：http://dali.quarkkingdee.top/Article/details/gtueiojowf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hfpthk.cn/Article/details/gtfjmklagu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinqigfzy.top/Article/details/gtkghdearo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gtjkzhvbbz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gtsvhrsksf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nwbrower.top/Article/details/gtsuuyqczu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gtvterkxrf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gogol.net.cn/Article/details/gtuuceglmv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hfpthk.cn/Article/details/gtyurzqdkw.html

[F08] 遍历目录
来源：http://dali.redwolf501.top/Article/details/gtfykrgjgg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hysaishi.cn/Article/details/gtpcxqonfc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gtgxxetpqi.html

JS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtuetbyyrs.html

TS:   fs.readdirSync("dir")
来源：http://dali.mhx1999.top/Article/details/gtwgqtbkmk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cheryme.top/Article/details/gtrjrasudt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hnqzz.top/Article/details/gtmdrmrjoi.html

Ruby: Dir.children("dir")
来源：http://dali.shuidangran.top/Article/details/gthaqrrvfv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.meibo888.top/Article/details/gtqoikkqze.html

[F09] 获取文件大小
来源：http://dali.fzhhl.top/Article/details/gtppxjtbbk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtisgpjoph.html

PHP:  filesize("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtovuijbas.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pengpengdd.cyou/Article/details/gtgpectzhd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aibaodan.cn/Article/details/gtidoglqnk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtxnhwjtzo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.bjfxy.top/Article/details/gtsymiegnt.html

Ruby: File.size("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtbrefltem.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.daxiang520.top/Article/details/gtcyivfnrw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkgbsvwo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtydkzwexj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwxowicsb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtluqaznsw.html

TS:   path.extname("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtfqfwdnop.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aizwys.cn/Article/details/gttihpydde.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtuqjjfvuf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtkeyevvum.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtuqsjivbd.html

[F11] 复制与移动文件
来源：http://dali.ppjwa.cn/Article/details/gttrsntwqs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtizegbztd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtycibfscv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtmaozdnll.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtnjfskfyj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dianchejie.cn/Article/details/gtjoqncmij.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jqgfzy.top/Article/details/gthwgdgbub.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtmbbpkazv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258.top/Article/details/gtingpdcvm.html

[F12] CSV 读写
来源：http://dali.guowangkeji.top/Article/details/gtdfdlurgg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.snrcjt.cn/Article/details/gtaemxmkla.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258888.top/Article/details/gtoaivvvsr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hammf.cn/Article/details/gtemmwwcyd.html

TS:   // 同上
来源：http://dali.gaohongyu789.top/Article/details/gtjukdwlgn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhongyouzk.top/Article/details/gthoblvagw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nanxinkj.top/Article/details/gtdawuzcin.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tian-w.cn/Article/details/gtzchdeqtz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangshuangyany.cn/Article/details/gtlkowvwkw.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtnhdaonzz.html

G. 面向对象
来源：http://dali.jiagoushi.top/Article/details/gtlpyjzome.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpzmhrcc.html

[G01] 定义类
来源：http://dali.dianchejie.cn/Article/details/gtyfhdwofb.html

Py:   class User: pass
来源：http://dali.snrcjt.cn/Article/details/gtgkelwigw.html

PHP:  class User {}
来源：http://dali.9152youxi.cn/Article/details/gtgwmfxnqo.html

JS:   class User {}
来源：http://dali.xuanzx.com/Article/details/gtyywdvdqo.html

TS:   class User { name: string = ""; }
来源：http://dali.316326.xyz/Article/details/gtxbebhkeg.html

Java: class User {}
来源：http://dali.fengsongda.top/Article/details/gtkwghmlgv.html

Go:   type User struct { Name string }
来源：http://dali.aizwys.cn/Article/details/gttmfgbsuk.html

Ruby: class User; end
来源：http://dali.chenzaomai.com/Article/details/gtylamschl.html

C#:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gtvuehotrw.html

[G02] 构造函数
来源：http://dali.dashuyun.cn/Article/details/gtguvjlqyb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cashguo.top/Article/details/gtmhyvuoze.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtvnjhqasd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtzngnbyuj.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gtzbhtvbuj.html

Java: User(String name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gtxieadzpd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxuanxn.top/Article/details/gthdammzyd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.0kj1m.cn/Article/details/gttdaycxlb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sysykeji.top/Article/details/gtwinuvlue.html

[G03] 实例属性
来源：http://dali.dashuyun.cn/Article/details/gtatvnctap.html

Py:   self.name = "x"
来源：http://dali.jlsjyb.cn/Article/details/gtlepciobd.html

PHP:  public string $name = "x";
来源：http://dali.mhx1999.top/Article/details/gtroztllhx.html

JS:   this.name = "x";
来源：http://dali.guowangkeji.top/Article/details/gtiygpkiiu.html

TS:   name: string = "x";
来源：http://dali.jqgufenzy.top/Article/details/gthhaklell.html

Java: private String name;
来源：http://dali.birdmap.top/Article/details/gtxglmlfpd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnqzz.top/Article/details/gtcwttnkcx.html

Ruby: @name = "x"
来源：http://dali.wangdashe.top/Article/details/gttpwxlnsc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtjbbikixt.html

[G04] 定义方法
来源：http://dali.pycfn.com/Article/details/gtczyrzhjc.html

Py:   def greet(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaprqeznd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gtlhfcqzlq.html

JS:   greet() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gteojknxok.html

TS:   greet(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtmobielhj.html

Java: String greet() { return name; }
来源：http://dali.fengsongda.top/Article/details/gtkkuigocq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gtgqdsoyeo.html

Ruby: def greet; @name; end
来源：http://dali.chenzaomai.com/Article/details/gtjgwtntvw.html

C#:   public string Greet() => Name;
来源：http://dali.yvedp.cn/Article/details/gtytutymjw.html

[G05] 继承
来源：http://dali.xylfe.cn/Article/details/gtzyicdpex.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdchqxfny.html

PHP:  class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvyvpzga.html

JS:   class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtnqztctis.html

TS:   class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtdoqzoxul.html

Java: class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtksifilzn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ydzc1.top/Article/details/gtqbybfyay.html

Ruby: class Admin < User; end
来源：http://dali.smart0.xyz/Article/details/gtrpkvvrea.html

C#:   class Admin : User {}
来源：http://dali.sysykeji.top/Article/details/gtgmatlshc.html

[G06] 重写方法
来源：http://dali.zhiwuduotai.top/Article/details/gtqvlmsycm.html

Py:   def greet(self): return "admin"
来源：http://dali.svipenyu.cn/Article/details/gthhixwblj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtpijxheil.html

JS:   greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtvncdylbh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtdhrbybgl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtzqcisuzj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.redwolf501.top/Article/details/gtqsvfdimh.html

Ruby: def greet; "admin"; end
来源：http://dali.meibo888.top/Article/details/gttlbtbmgo.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxinkj.top/Article/details/gtttmztfsg.html

[G07] 调用父类方法
来源：http://dali.yj202588.top/Article/details/gtsnqofxow.html

Py:   super().greet()
来源：http://dali.birdmap.top/Article/details/gthrxllqhl.html

PHP:  parent::greet();
来源：http://dali.chenzaomai.com/Article/details/gtmkmxxhsy.html

JS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtdumbrfyw.html

TS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtucbvssmj.html

Java: super.greet();
来源：http://dali.guowangkeji.top/Article/details/gtpdnzcrrx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dashuyun.cn/Article/details/gtmnxqptad.html

Ruby: super
来源：http://dali.tian-w.cn/Article/details/gtnbqphglr.html

C#:   base.Greet();
来源：http://dali.yanxiufei.cn/Article/details/gtazhcbvcc.html

[G08] 静态方法与属性
来源：http://dali.havefunace.top/Article/details/gtehdekyui.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yueranfly.top/Article/details/gthxfbttta.html

PHP:  public static function f() {}
来源：http://dali.shuidangran.top/Article/details/gtejupjnyl.html

JS:   static f() {}
来源：http://dali.smart0.xyz/Article/details/gtskpfwmkq.html

TS:   static f(): void {}
来源：http://dali.aizwys.cn/Article/details/gtbsqdwukz.html

Java: static void f() {}
来源：http://dali.jqgfzy.top/Article/details/gtglfshxjv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuanzx.com/Article/details/gtlpkqjela.html

Ruby: def self.f; end
来源：http://dali.c1oappe.top/Article/details/gtijrvsvdf.html

C#:   public static void F() {}
来源：http://dali.tian-w.cn/Article/details/gtntzjepyf.html

[G09] 接口 / 抽象类
来源：http://dali.hysaishi.cn/Article/details/gtsfkthexv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkcuspqu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuanzx.com/Article/details/gtjmytvqba.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.bjfxy.top/Article/details/gtmcztcncq.html

TS:   interface Shape { area(): number; }
来源：http://dali.sxryk.cn/Article/details/gtcjagglsa.html

Java: interface Shape { double area(); }
来源：http://dali.sxryk.cn/Article/details/gtuqsgjfod.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yangfankeji.com/Article/details/gtsbcsibti.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gotoacloud.top/Article/details/gtgoysimsa.html

C#:   interface IShape { double Area(); }
来源：http://dali.bjfxy.top/Article/details/gtyvhygcsn.html

[G10] 访问控制
来源：http://dali.yonumen.top/Article/details/gtlofwanhs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangtech.top/Article/details/gtmowsfydp.html

PHP:  public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtqjnysatt.html

JS:   #private 字段；其余公开
来源：http://dali.ybcxt.top/Article/details/gtbkptoizs.html

TS:   public / protected / private
来源：http://dali.ydzc1.top/Article/details/gtudlwcmps.html

Java: public / protected / private / 默认包级
来源：http://dali.cqqwz.cn/Article/details/gtohmcsatw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gotoacloud.top/Article/details/gtlfmkpqyn.html

Ruby: public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gtertpgxaf.html

C#:   public / protected / private / internal
来源：http://dali.xziqi.cn/Article/details/gtkuaujmpb.html

[G11] getter / setter
来源：http://dali.zhengqikj.top/Article/details/gtvfizafnl.html

Py:   @property 与 @x.setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvomizwk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtulybuest.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gtrxqhxslj.html

TS:   get name(): string { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gtzuvitrxs.html

Java: public String getName() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwqfmapw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtwtiwjwpj.html

Ruby: attr_accessor :name
来源：http://dali.yangfankeji.com/Article/details/gtbjtnkxrs.html

C#:   public string Name { get; set; }
来源：http://dali.pycfn.com/Article/details/gtangwqnis.html

[G12] 对象转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtadjbrsqk.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258.top/Article/details/gtbczdukit.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtglmsdbav.html

JS:   toString() { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtlkdqmikl.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gttdfnewgt.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtrsznusyw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtztnecjxa.html

Ruby: def to_s; @name; end
来源：http://dali.zhengqikj.top/Article/details/gtgrvvevcf.html

C#:   public override string ToString() => Name;
来源：http://dali.aizwys.cn/Article/details/gtztxshynp.html

[G13] 判断对象类型
来源：http://dali.kuanghao11.cn/Article/details/gtfzzjyoxi.html

Py:   isinstance(u, User)
来源：http://dali.daxiang520.top/Article/details/gtraqzmqbd.html

PHP:  $u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtsqbxxtfl.html

JS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtmkdgkegs.html

TS:   u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtdzmxedpd.html

Java: u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtsfwbxpbd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.316326.xyz/Article/details/gtzeurvhyq.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gtwzsrfiii.html

C#:   u is User
来源：http://dali.hnxiangtu.top/Article/details/gtpyithdez.html

[G14] 数据类 / record
来源：http://dali.pengpengdd.cyou/Article/details/gtjvdrwfeg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhoulong.xyz/Article/details/gtuaoizfxt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangkeji.top/Article/details/gtopxpoplp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sysykeji.top/Article/details/gtkjkbcshr.html

TS:   type User = { name: string; age: number };
来源：http://dali.c1oappe.top/Article/details/gtrautqojv.html

Java: record User(String name, int age) {}
来源：http://dali.sxryk.cn/Article/details/gteloudhre.html

Go:   type User struct { Name string; Age int }
来源：http://dali.birdmap.top/Article/details/gthwenlelb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.c1oappe.top/Article/details/gtkfxjsbbt.html


<!-- 参考信息 -->