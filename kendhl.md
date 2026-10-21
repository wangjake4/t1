代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.sweek.top/Article/details/gtynyxkett.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gtwakqvtio.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gtpejyymhu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenzaomai.com/Article/details/gttcxrgynx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenlongwang.top/Article/details/gtoxamkhep.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nanxuanxn.top/Article/details/gtnlzfibce.html

C#:   1234567.ToString("N0")
来源：http://dali.chenlongwang.top/Article/details/gtqeahiwix.html

[E17] 首字母大写
来源：http://dali.guowangkeji.top/Article/details/gttizwodlj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.aibaodan.cn/Article/details/gtvffrsnit.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinqigfzy.top/Article/details/gtdszekeex.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hywenlv.cn/Article/details/gtmwruboji.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.svipenyu.cn/Article/details/gtgvuuemkj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yanxiufei.cn/Article/details/gtvtmgnavh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cucudq.cn/Article/details/gtmlezhjap.html

Ruby: s.capitalize
来源：http://dali.316326.xyz/Article/details/gtbythtwva.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.fzhhl.top/Article/details/gtwnlsqipg.html

[E18] 模板占位符替换
来源：http://dali.hammf.cn/Article/details/gtosaodayx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.svipenyu.cn/Article/details/gtjqgcdewk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhongyouzk.top/Article/details/gttefjwkeg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtdhczzmth.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtfutbllow.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtntyyepvm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtxmyeopcn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dianchejie.cn/Article/details/gtdbwctujs.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.birdmap.top/Article/details/gtidshccpn.html

[E19] 多行文本按行拆分
来源：http://dali.ybcxt.top/Article/details/gttqvajlgj.html

Py:   s.splitlines()
来源：http://dali.c1oappe.top/Article/details/gtlkvrjjpn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ehwqpu.com/Article/details/gthfsjrjnr.html

JS:   s.split(/\r?\n/)
来源：http://dali.ehwqpu.com/Article/details/gtsehklbrs.html

TS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gtdgcnpfzi.html

Java: s.lines().toList()
来源：http://dali.gogol.net.cn/Article/details/gtjuhtczxj.html

Go:   strings.Split(s, "\n")
来源：http://dali.cqqwz.cn/Article/details/gthuzecmze.html

Ruby: s.lines
来源：http://dali.sweek.top/Article/details/gteffxbfcj.html

C#:   s.Split('\n')
来源：http://dali.jiagoushi.top/Article/details/gtuuuhmtyp.html

[E20] 判断字符串是否为空
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwmyhmxa.html

Py:   if not s:
来源：http://dali.yj20258.top/Article/details/gtlpmmsmxl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinqigufen.top/Article/details/gtkdupihgj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.kuanghao11.cn/Article/details/gtqcqfeseb.html

TS:   if (s === "") {}
来源：http://dali.jlsjyb.cn/Article/details/gtogzhxstf.html

Java: if (s.isEmpty()) {}
来源：http://dali.havefunace.top/Article/details/gttgdteevs.html

Go:   if s == "" {}
来源：http://dali.yongpay.top/Article/details/gtghyveuxe.html

Ruby: if s.empty?
来源：http://dali.fzhhl.top/Article/details/gtcphgfmte.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sweek.top/Article/details/gtoincaksr.html

[E21] 超长截断加省略号
来源：http://dali.jqgufenzy.top/Article/details/gtwpdmggff.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.havefunace.top/Article/details/gtvdszpnpz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtenhzakgs.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtjxddutvr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtedlxtxgo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtsdfgnkud.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.dianchejie.cn/Article/details/gtubjbbhwb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtuhhmbcsv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtuaoqrrmd.html

[E22] 字节长度与字符长度
来源：http://dali.c1oappe.top/Article/details/gtihwljswg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.redwolf501.top/Article/details/gtmolqutfr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gtxjboxfrs.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.snrcjt.cn/Article/details/gtivjzubdj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj202588.top/Article/details/gtxrfddkwn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhongyouzk.top/Article/details/gtkfvzfiom.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cucudq.cn/Article/details/gtbsiknhya.html

Ruby: s.bytesize;  s.length
来源：http://dali.tian-w.cn/Article/details/gtaurajdnc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gtrnbbcujb.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtjqrvirvf.html

F. 文件与目录
来源：http://dali.zdqjudy.top/Article/details/gtgciphyrx.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtpdbiisys.html

[F01] 读取整个文件
来源：http://dali.yj202588.top/Article/details/gtcunsekhg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yanxiufei.cn/Article/details/gthwunwccw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yongpay.top/Article/details/gtjmvuryct.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.feifeiyinyue.top/Article/details/gtpbcsdumc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gtzzvsesru.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtydwfdmdl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhoulong.xyz/Article/details/gtpzhavdgz.html

Ruby: File.read("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtuxncjthu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtrbssptud.html

[F02] 逐行读取文件
来源：http://dali.0kj1m.cn/Article/details/gtsrlynkyd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daxiang520.top/Article/details/gtuerautjk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cucudq.cn/Article/details/gtyjmwhgjz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhengqikj.top/Article/details/gtihpxrbjq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guannengcc.top/Article/details/gtfnuyiipr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gtkiktcjmi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hfpthk.cn/Article/details/gtctjlxzyy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenlongwang.top/Article/details/gtnjziiqkc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.0kj1m.cn/Article/details/gtzqxdgybf.html

[F03] 写入文件（覆盖）
来源：http://dali.haohaochexian.top/Article/details/gtomsnuhgg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gaohongyu789.top/Article/details/gtczhzuqst.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.daria6918.cn/Article/details/gtlqoozgmg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gtaswkatlo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gtdvvdvhvj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gtqkjvpetu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuetiantiany.cn/Article/details/gtxjhvqdni.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hnqzz.top/Article/details/gtbvhplqsn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gtayhkdpne.html

[F04] 追加写入文件
来源：http://dali.cheryme.top/Article/details/gtdheherhl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxydahxce.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xziqi.cn/Article/details/gtabokmjxz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hywenlv.cn/Article/details/gtolbaantt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gtitcfxixt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.fengsongda.top/Article/details/gtktytmajl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenzaomai.com/Article/details/gtvvyltpuc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yueranfly.top/Article/details/gtotdzhcnf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tian-w.cn/Article/details/gtwiwkrmyq.html

[F05] 判断文件或目录是否存在
来源：http://dali.vqdsnc.cn/Article/details/gttojlrfcw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gzhubu.top/Article/details/gthbkjilwd.html

PHP:  file_exists("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gthcsqhdro.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtlwqqhhnv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtjoqowtvf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtgbstsnbn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jiagoushi.top/Article/details/gterdguyjq.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhvdfsgd.html

C#:   File.Exists("a.txt")
来源：http://dali.meibo888.top/Article/details/gtapfwhlvf.html

[F06] 删除文件
来源：http://dali.hysaishi.cn/Article/details/gttrflbzav.html

Py:   os.remove("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtxnwppmib.html

PHP:  unlink("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtizksrqgz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtpdthhkwr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtkriqrhwa.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkepsggzs.html

Go:   os.Remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtxppifvan.html

Ruby: File.delete("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtlxcivyle.html

C#:   File.Delete("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtugmxzywa.html

[F07] 创建目录（含多级）
来源：http://dali.mhx1999.top/Article/details/gtduanevmy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258.top/Article/details/gtpxvktcru.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgufenzy.top/Article/details/gtyscovzmw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gtxgyhmnce.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.meibo888.top/Article/details/gtmltfkhuv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zdqjudy.top/Article/details/gtswebddjq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zycfv.cn/Article/details/gtgetecizx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jqgfzy.top/Article/details/gtqbjwumuy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ydzc1.top/Article/details/gtysmaggcr.html

[F08] 遍历目录
来源：http://dali.wangshuangyany.cn/Article/details/gtdsgeqoxx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nanxuanxn.top/Article/details/gtfkykfnmx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guannengcc.top/Article/details/gtvmfeutft.html

JS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gtqmerqxjh.html

TS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gtmtcdmqnc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenjidiqi.icu/Article/details/gtsevbbivz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nwbrower.top/Article/details/gtetvlhrfr.html

Ruby: Dir.children("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtzkovoapi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hammf.cn/Article/details/gtzqqegsoo.html

[F09] 获取文件大小
来源：http://dali.jqgfzy.top/Article/details/gtoptjlhpj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtzgckzsck.html

PHP:  filesize("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtxkkeswjq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gtkodzqsur.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxuanxn.top/Article/details/gtshwckykr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtmmtsnuvz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.feifeiyinyue.top/Article/details/gtlvaekicg.html

Ruby: File.size("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtdlexkrro.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.guannengcc.top/Article/details/gtwekqmtwf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.quarkkingdee.top/Article/details/gtaqrraqsg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gteqkwlcbs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtpzgurhzx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtderqahsc.html

TS:   path.extname("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtqnisvnod.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenzaomai.com/Article/details/gtcbflayic.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtkxdhcmkh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtugkjjukr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtzetigjzv.html

[F11] 复制与移动文件
来源：http://dali.yueranfly.top/Article/details/gtjecyzgqt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtjyngimrn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nanxinkj.top/Article/details/gtemhylqmz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtysiwsgtx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtvhdffjdl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.iojbl.cn/Article/details/gtsrdpbcqb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gtgjmiqtod.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtxvdxrdpb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuetiantiany.cn/Article/details/gtnaxlwwfi.html

[F12] CSV 读写
来源：http://dali.cucudq.cn/Article/details/gtumazmjbz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zdqjudy.top/Article/details/gtudasaqms.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yongpay.top/Article/details/gthtpaphqd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sufxvd.cn/Article/details/gtaibtlzwv.html

TS:   // 同上
来源：http://dali.havefunace.top/Article/details/gtpxqrjiev.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sysykeji.top/Article/details/gtysfhdete.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.birdmap.top/Article/details/gthpnlxtpm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjaqjxynm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shangyingyoupin.top/Article/details/gtguljnzpq.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtoyymqgsl.html

G. 面向对象
来源：http://dali.yuxming.cn/Article/details/gtipuwfnix.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtcekvxbcr.html

[G01] 定义类
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcjdgntgs.html

Py:   class User: pass
来源：http://dali.yongpay.top/Article/details/gtdbtqdyqb.html

PHP:  class User {}
来源：http://dali.hysaishi.cn/Article/details/gtzldavotg.html

JS:   class User {}
来源：http://dali.ydzc1.top/Article/details/gtpalpkhdr.html

TS:   class User { name: string = ""; }
来源：http://dali.nwbrower.top/Article/details/gtrjdbbuvk.html

Java: class User {}
来源：http://dali.meibo888.top/Article/details/gtrudwghht.html

Go:   type User struct { Name string }
来源：http://dali.ppjwa.cn/Article/details/gtbpwcrljb.html

Ruby: class User; end
来源：http://dali.yuxming.cn/Article/details/gttxgmihuy.html

C#:   class User {}
来源：http://dali.aizwys.cn/Article/details/gtlvqczrcs.html

[G02] 构造函数
来源：http://dali.yj202588.top/Article/details/gtnwvxomco.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinqigfzy.top/Article/details/gtdqzlwbql.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.guowangkeji.top/Article/details/gtlnvjvxzn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gtrgeafhft.html

TS:   constructor(public name: string) {}
来源：http://dali.sxryk.cn/Article/details/gtepgsnaox.html

Java: User(String name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gtbxfwurym.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.kuanghao11.cn/Article/details/gtebqhuinb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jlsjyb.cn/Article/details/gtxqnhchmd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cheryme.top/Article/details/gtxtysqnki.html

[G03] 实例属性
来源：http://dali.aizwys.cn/Article/details/gtwgkyqjbf.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gtrtmyvzlr.html

PHP:  public string $name = "x";
来源：http://dali.ivvv.top/Article/details/gtqfjflzwk.html

JS:   this.name = "x";
来源：http://dali.zycfv.cn/Article/details/gtsjnukudn.html

TS:   name: string = "x";
来源：http://dali.meibo888.top/Article/details/gtnbycqrok.html

Java: private String name;
来源：http://dali.pycfn.com/Article/details/gtzsuqabgl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hammf.cn/Article/details/gtyliowvnt.html

Ruby: @name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gtesabeami.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daxiang520.top/Article/details/gtimrkpkgj.html

[G04] 定义方法
来源：http://dali.birdmap.top/Article/details/gthgtdiptw.html

Py:   def greet(self): return self.name
来源：http://dali.pycfn.com/Article/details/gtdaymxkel.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtnokitime.html

JS:   greet() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gthmgmvdtb.html

TS:   greet(): string { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtgwdwobzp.html

Java: String greet() { return name; }
来源：http://dali.yj20258.top/Article/details/gtvqiqakuh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtbnudvqfe.html

Ruby: def greet; @name; end
来源：http://dali.gzhubu.top/Article/details/gtwzpjabwv.html

C#:   public string Greet() => Name;
来源：http://dali.snrcjt.cn/Article/details/gtxtazubxk.html

[G05] 继承
来源：http://dali.nanxuanxn.top/Article/details/gthhnjsuej.html

Py:   class Admin(User): pass
来源：http://dali.zhiwuduotai.top/Article/details/gtrbnkkqpt.html

PHP:  class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gttfjurowe.html

JS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtoqdpmtft.html

TS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtxohuhiqd.html

Java: class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtgfmjnlsa.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sweek.top/Article/details/gtxwiqzlih.html

Ruby: class Admin < User; end
来源：http://dali.fengsongda.top/Article/details/gtjyagyzrg.html

C#:   class Admin : User {}
来源：http://dali.jinqigfzy.top/Article/details/gtibvpsfjf.html

[G06] 重写方法
来源：http://dali.nanxinkj.top/Article/details/gthwqmeydj.html

Py:   def greet(self): return "admin"
来源：http://dali.shuidangran.top/Article/details/gthbpnufme.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtfnysldgo.html

JS:   greet() { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtrkcxzvlv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtdgoicfux.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtwrsahgop.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hongshengwenyu.top/Article/details/gtwpujwiah.html

Ruby: def greet; "admin"; end
来源：http://dali.zhongyouzk.top/Article/details/gtjblbqjhd.html

C#:   public override string Greet() => "admin";
来源：http://dali.yvedp.cn/Article/details/gtplsffjkr.html

[G07] 调用父类方法
来源：http://dali.dashuyun.cn/Article/details/gtriepeaam.html

Py:   super().greet()
来源：http://dali.hnxiangtu.top/Article/details/gtkcrbdmqr.html

PHP:  parent::greet();
来源：http://dali.aibaodan.cn/Article/details/gtccvgtlne.html

JS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtpazcmsqw.html

TS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtaokidbwc.html

Java: super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtgfbyjgox.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daxiang520.top/Article/details/gtopxetelr.html

Ruby: super
来源：http://dali.0kj1m.cn/Article/details/gtcvveienw.html

C#:   base.Greet();
来源：http://dali.guowangkeji.top/Article/details/gtwpvkhrul.html

[G08] 静态方法与属性
来源：http://dali.guowangkeji.top/Article/details/gtovgvjarh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.316326.xyz/Article/details/gtbwnfretd.html

PHP:  public static function f() {}
来源：http://dali.yangfankeji.com/Article/details/gthdqqirle.html

JS:   static f() {}
来源：http://dali.fengsongda.top/Article/details/gtxtnsyaal.html

TS:   static f(): void {}
来源：http://dali.feifeiyinyue.top/Article/details/gthmldjpks.html

Java: static void f() {}
来源：http://dali.nanxinkj.top/Article/details/gtezpgjdqj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hfpthk.cn/Article/details/gtnqgndkkh.html

Ruby: def self.f; end
来源：http://dali.yonumen.top/Article/details/gtfprrfrxj.html

C#:   public static void F() {}
来源：http://dali.fengsongda.top/Article/details/gtqfqukpiy.html

[G09] 接口 / 抽象类
来源：http://dali.pycfn.com/Article/details/gtgrjnukyt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jiagoushi.top/Article/details/gtgqtcfxkf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yanxiufei.cn/Article/details/gtymcxacqh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tanke756.top/Article/details/gtyhbzyhqr.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangdashe.top/Article/details/gtzupdbejr.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtojzhzaxz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhengqikj.top/Article/details/gtriliipgh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinqigufen.top/Article/details/gtazqjkfid.html

C#:   interface IShape { double Area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtjitgvugc.html

[G10] 访问控制
来源：http://dali.ybcxt.top/Article/details/gtrhlgpnmg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tian-w.cn/Article/details/gtsrkdqiug.html

PHP:  public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtflirqcet.html

JS:   #private 字段；其余公开
来源：http://dali.nanxinkj.top/Article/details/gtjeuzclrt.html

TS:   public / protected / private
来源：http://dali.hammf.cn/Article/details/gtialfkpig.html

Java: public / protected / private / 默认包级
来源：http://dali.hnxiangtu.top/Article/details/gtwfvvjkwr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigfzy.top/Article/details/gtjvpwpunl.html

Ruby: public / protected / private
来源：http://dali.sweek.top/Article/details/gttzkqixsn.html

C#:   public / protected / private / internal
来源：http://dali.redwolf501.top/Article/details/gtijeobjqa.html

[G11] getter / setter
来源：http://dali.haohaochexian.top/Article/details/gtlxjlxgtv.html

Py:   @property 与 @x.setter
来源：http://dali.zhixingplan.top/Article/details/gtyoxbfkma.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtfzusemeg.html

JS:   get name() { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gtzshhxdac.html

TS:   get name(): string { return this._name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctciitva.html

Java: public String getName() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtskermaas.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gtjrdzwvbz.html

Ruby: attr_accessor :name
来源：http://dali.jqgufenzy.top/Article/details/gtnyncktnr.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258.top/Article/details/gtbuhmkkah.html

[G12] 对象转字符串
来源：http://dali.dashuyun.cn/Article/details/gtvmwjkvuq.html

Py:   def __str__(self): return self.name
来源：http://dali.zhiwuduotai.top/Article/details/gtmszzsvnz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtlfnhmpjz.html

JS:   toString() { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtzyimqhbw.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtpsudujhl.html

Java: @Override public String toString() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtbmtgncnb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtvypfzhcy.html

Ruby: def to_s; @name; end
来源：http://dali.andypj.xyz/Article/details/gtslygoyqw.html

C#:   public override string ToString() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gtnydprbjq.html

[G13] 判断对象类型
来源：http://dali.pycfn.com/Article/details/gtpbqxuqck.html

Py:   isinstance(u, User)
来源：http://dali.tianlin.xyz/Article/details/gtfdqdfoud.html

PHP:  $u instanceof User
来源：http://dali.smart0.xyz/Article/details/gteziowqgb.html

JS:   u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtuvdbetqb.html

TS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gtyjdjysjy.html

Java: u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gthzjvmoky.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdocarmc.html

Ruby: u.is_a?(User)
来源：http://dali.cqqwz.cn/Article/details/gtfqjlzmzy.html

C#:   u is User
来源：http://dali.shzxlz.cn/Article/details/gtefngivaw.html

[G14] 数据类 / record
来源：http://dali.xziqi.cn/Article/details/gtdkfqmfeg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hnxiangtu.top/Article/details/gtiwnanvoo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.andypj.xyz/Article/details/gtznuzwksv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cdnleiting.top/Article/details/gtwgtrcluh.html

TS:   type User = { name: string; age: number };
来源：http://dali.ivvv.top/Article/details/gtwherhjgz.html

Java: record User(String name, int age) {}
来源：http://dali.sysykeji.top/Article/details/gtjlmljlof.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrypxhvic.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhengqikj.top/Article/details/gtfffctryo.html


<!-- 参考信息 -->