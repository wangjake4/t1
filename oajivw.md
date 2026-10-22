代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.ehwqpu.com/Article/details/gtjbwillvb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tian-w.cn/Article/details/gthjwubpjb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigufen.top/Article/details/gtqvgwyqje.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yueranfly.top/Article/details/gtieatuzpi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtywxkmrtx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.snrcjt.cn/Article/details/gtcexcoyrg.html

C#:   1234567.ToString("N0")
来源：http://dali.tianlin.xyz/Article/details/gtlzctjdlh.html

[E17] 首字母大写
来源：http://dali.gotoacloud.top/Article/details/gtzzrzjmnu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.guannengcc.top/Article/details/gtfxlrsxtc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.dashuyun.cn/Article/details/gtcukfvcti.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxuanxn.top/Article/details/gtanzxtlsk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yanxiufei.cn/Article/details/gtskibzlsv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.iojbl.cn/Article/details/gtwjgqmdbg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yueranfly.top/Article/details/gthreyoxrf.html

Ruby: s.capitalize
来源：http://dali.daxiang520.top/Article/details/gtlgbcxevx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xziqi.cn/Article/details/gtfbminrjw.html

[E18] 模板占位符替换
来源：http://dali.hnqzz.top/Article/details/gttbwwpuqe.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gttogglbgo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ehwqpu.com/Article/details/gtjqnegxuk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gturzogiaw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzfcfvvab.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtkcfilgrm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtkfxwvrqh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinqigfzy.top/Article/details/gtafwdxyhx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj20258888.top/Article/details/gtfcgeguak.html

[E19] 多行文本按行拆分
来源：http://dali.sysykeji.top/Article/details/gthpzilasp.html

Py:   s.splitlines()
来源：http://dali.vqdsnc.cn/Article/details/gtaklbzosx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtmohembzd.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gtuivychur.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gtkbegkpcg.html

Java: s.lines().toList()
来源：http://dali.shzxlz.cn/Article/details/gtflqhlprv.html

Go:   strings.Split(s, "\n")
来源：http://dali.guowangkeji.top/Article/details/gttyuqxmyg.html

Ruby: s.lines
来源：http://dali.feifeiyinyue.top/Article/details/gtfovcwaah.html

C#:   s.Split('\n')
来源：http://dali.shzxlz.cn/Article/details/gtfivqxiea.html

[E20] 判断字符串是否为空
来源：http://dali.xuanzx.com/Article/details/gtwqspbado.html

Py:   if not s:
来源：http://dali.wangdashe.top/Article/details/gtohbydlkw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinghuilouyu.cn/Article/details/gthytyejzs.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.0kj1m.cn/Article/details/gtjhqispcs.html

TS:   if (s === "") {}
来源：http://dali.hnxiangtu.top/Article/details/gtncgavgmp.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj20258.top/Article/details/gtrbwjawpm.html

Go:   if s == "" {}
来源：http://dali.ehwqpu.com/Article/details/gtnbhepywr.html

Ruby: if s.empty?
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwkklseg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gaohongyu789.top/Article/details/gtokwuscgu.html

[E21] 超长截断加省略号
来源：http://dali.feifeiyinyue.top/Article/details/gtnhkktxjv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xuanzx.com/Article/details/gtweixndjp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtgehjnegm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtslrccayd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtmzqejizz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtzyxttycs.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hysaishi.cn/Article/details/gtsrzjifhf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtykmonryp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sxryk.cn/Article/details/gttqmzvvpo.html

[E22] 字节长度与字符长度
来源：http://dali.chenlongwang.top/Article/details/gtdxkwcntw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cashguo.top/Article/details/gticwoaoxn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gthaaxznta.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sufxvd.cn/Article/details/gtjfnnxdjm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ybcxt.top/Article/details/gtxtqbeimg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.feifeiyinyue.top/Article/details/gtcxviwdik.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.quarkkingdee.top/Article/details/gtcdfbmhpd.html

Ruby: s.bytesize;  s.length
来源：http://dali.tian-w.cn/Article/details/gtvmbctiaf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ydzc1.top/Article/details/gthmtkxtcp.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtmhcahomd.html

F. 文件与目录
来源：http://dali.ydzc1.top/Article/details/gtrismwxvm.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtfuvbmeuh.html

[F01] 读取整个文件
来源：http://dali.hammf.cn/Article/details/gtdauqujhm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigfzy.top/Article/details/gtgqtdpgdd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtnvmlugnq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.redwolf501.top/Article/details/gtaojnmsmn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gtprwsvepp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtxjftkvnt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cdnleiting.top/Article/details/gtcuadfrdx.html

Ruby: File.read("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtggbeaekg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtjgsaugil.html

[F02] 逐行读取文件
来源：http://dali.zdqjudy.top/Article/details/gtvokdlcsi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zycfv.cn/Article/details/gtevmcudnv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.haohaochexian.top/Article/details/gtaegojaxr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuxming.cn/Article/details/gtbdumhjle.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gogol.net.cn/Article/details/gtmdhhwpts.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj20258.top/Article/details/gtgtqwcjrn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenlongwang.top/Article/details/gtwtwzhger.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pengpengdd.cyou/Article/details/gtxhctivcx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sufxvd.cn/Article/details/gtdfeglluj.html

[F03] 写入文件（覆盖）
来源：http://dali.tian-w.cn/Article/details/gtladrgopb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.feifeiyinyue.top/Article/details/gtjxukoxfq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gtgyidkpsy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gtkcldaeqv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gtuxvlavmz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xinyue.icu/Article/details/gtqcprmoyk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yongpay.top/Article/details/gtxefsnzdv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yangfankeji.com/Article/details/gtqhyctqcd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtnmjuepjm.html

[F04] 追加写入文件
来源：http://dali.gogol.net.cn/Article/details/gtnyvnljac.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj20258888.top/Article/details/gtmpggporo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.bjfxy.top/Article/details/gtodvvqata.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dashuyun.cn/Article/details/gtpiceewbp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gteukmybkz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zycfv.cn/Article/details/gtbpzjcjyl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xuanzx.com/Article/details/gtadziqulo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shuidangran.top/Article/details/gtnrihtejr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenzaomai.com/Article/details/gthdzbvqdo.html

[F05] 判断文件或目录是否存在
来源：http://dali.ydzc1.top/Article/details/gtgmwhxgme.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ybcxt.top/Article/details/gtpotnxnzx.html

PHP:  file_exists("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtrnimpoke.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtxxqyijrs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtlwesulnz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gttsybqouv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhoulong.xyz/Article/details/gteubpvukn.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258.top/Article/details/gtgoxricuk.html

C#:   File.Exists("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtuuodqyhk.html

[F06] 删除文件
来源：http://dali.cqqwz.cn/Article/details/gthipdwxww.html

Py:   os.remove("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtvnmrohrq.html

PHP:  unlink("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtyjosvqjh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcqehwcan.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gttbuzmqmk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gthkymaoll.html

Go:   os.Remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtsiqcquoi.html

Ruby: File.delete("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtojcgnqlo.html

C#:   File.Delete("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtyjotfaub.html

[F07] 创建目录（含多级）
来源：http://dali.smart0.xyz/Article/details/gtnwhauznd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfryknjc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.havefunace.top/Article/details/gtxiyoqznk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shangyingyoupin.top/Article/details/gtxvvbixay.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gtpvtwsjlf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tanke756.top/Article/details/gtdvbryhfk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yuanzhike.top/Article/details/gtjdarbqpb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zycfv.cn/Article/details/gtstmgprnf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.9152youxi.cn/Article/details/gtoskfbeee.html

[F08] 遍历目录
来源：http://dali.ybcxt.top/Article/details/gtdwnpvtsx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xziqi.cn/Article/details/gtfqaafdxu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cdnleiting.top/Article/details/gtcwklrqih.html

JS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gtxxyoehhi.html

TS:   fs.readdirSync("dir")
来源：http://dali.ybcxt.top/Article/details/gtnvdueqqj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cashguo.top/Article/details/gtosgpbqzg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtapktxrwc.html

Ruby: Dir.children("dir")
来源：http://dali.xinyue.icu/Article/details/gtlsepqodu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hysaishi.cn/Article/details/gtkirnzcqi.html

[F09] 获取文件大小
来源：http://dali.fengsongda.top/Article/details/gtcyubvosn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtiyfnndjt.html

PHP:  filesize("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtpzohiqiu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenjidiqi.icu/Article/details/gtniukvylw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.vqdsnc.cn/Article/details/gtkovstufz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtfweabuvq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzjzprbk.html

Ruby: File.size("a.txt")
来源：http://dali.fengsongda.top/Article/details/gttuzsdvxs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmqrayltm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuetiantiany.cn/Article/details/gtgyapcmvx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtgtwvqnok.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jianghu66.top/Article/details/gtsgdehydz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtjatubhct.html

TS:   path.extname("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtdwbdndew.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nanxinkj.top/Article/details/gtepldbdzw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtkfncbbcz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gttsratgzs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtiiggwddx.html

[F11] 复制与移动文件
来源：http://dali.zhengqikj.top/Article/details/gtzcceqphf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtzqlzadjt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cqqwz.cn/Article/details/gtderjpqdc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtbaxqvjmq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtovixqwnh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hywenlv.cn/Article/details/gtozvunuhp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ivvv.top/Article/details/gtilsmeabl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtzfuhldsr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258.top/Article/details/gtndiqtpuz.html

[F12] CSV 读写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbqzolsq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.guowangkeji.top/Article/details/gtdntqrgvj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhongyouzk.top/Article/details/gtiokwurwi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jqgfzy.top/Article/details/gtbyucvhun.html

TS:   // 同上
来源：http://dali.yj20258.top/Article/details/gtwlckjfmq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jiagoushi.top/Article/details/gtpkzvddho.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjttreks.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.c1oappe.top/Article/details/gtsjhalemp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cheryme.top/Article/details/gttxsrywbb.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtijygniao.html

G. 面向对象
来源：http://dali.ydzc1.top/Article/details/gtsvunaigy.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtsgvjlzvq.html

[G01] 定义类
来源：http://dali.vqdsnc.cn/Article/details/gtbfjtccwf.html

Py:   class User: pass
来源：http://dali.xuetiantiany.cn/Article/details/gtczkidflj.html

PHP:  class User {}
来源：http://dali.hfpthk.cn/Article/details/gtkxuhzsjh.html

JS:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gtaordbyxq.html

TS:   class User { name: string = ""; }
来源：http://dali.xuetiantiany.cn/Article/details/gtramondfm.html

Java: class User {}
来源：http://dali.316326.xyz/Article/details/gtiairyrtf.html

Go:   type User struct { Name string }
来源：http://dali.sweek.top/Article/details/gtlyrchwak.html

Ruby: class User; end
来源：http://dali.meibo888.top/Article/details/gtyqnuvdwk.html

C#:   class User {}
来源：http://dali.redwolf501.top/Article/details/gtdgckzuyz.html

[G02] 构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gtapmbyagk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.wangshuangyany.cn/Article/details/gttkcvfrih.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cucudq.cn/Article/details/gtyczbjgmq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtkfcwxsfg.html

TS:   constructor(public name: string) {}
来源：http://dali.quarkkingdee.top/Article/details/gtiwuwghkp.html

Java: User(String name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gtdqjugope.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.316326.xyz/Article/details/gtiipiqkni.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtczhbcijy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtveeqruis.html

[G03] 实例属性
来源：http://dali.316326.xyz/Article/details/gtnzfezmom.html

Py:   self.name = "x"
来源：http://dali.0kj1m.cn/Article/details/gttxrtxusk.html

PHP:  public string $name = "x";
来源：http://dali.shzxlz.cn/Article/details/gtmkmnsgec.html

JS:   this.name = "x";
来源：http://dali.jinqigufen.top/Article/details/gtplrunxst.html

TS:   name: string = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtxtxvhwgn.html

Java: private String name;
来源：http://dali.gaohongyu789.top/Article/details/gtdddmbpku.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangdashe.top/Article/details/gtsaiqdlys.html

Ruby: @name = "x"
来源：http://dali.daria6918.cn/Article/details/gthsdzabwk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.andypj.xyz/Article/details/gtjstfwexn.html

[G04] 定义方法
来源：http://dali.shzxlz.cn/Article/details/gtzueuppfy.html

Py:   def greet(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gtfjhmbkvl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gtsoexvjzv.html

JS:   greet() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtdnqnsghv.html

TS:   greet(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtpmbvtrxi.html

Java: String greet() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtyutywmzp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gtbmfjigog.html

Ruby: def greet; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gtfcopacqs.html

C#:   public string Greet() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gtsviwoxbl.html

[G05] 继承
来源：http://dali.yuanzhike.top/Article/details/gtpnpchftr.html

Py:   class Admin(User): pass
来源：http://dali.nanxuanxn.top/Article/details/gtselidefd.html

PHP:  class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtbqaqrqoy.html

JS:   class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gtddvyesja.html

TS:   class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gtygyqldld.html

Java: class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtizgokwrv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuetiantiany.cn/Article/details/gtrxfgspki.html

Ruby: class Admin < User; end
来源：http://dali.svipenyu.cn/Article/details/gtruqlmhoi.html

C#:   class Admin : User {}
来源：http://dali.dianchejie.cn/Article/details/gtxomvsdka.html

[G06] 重写方法
来源：http://dali.kuanghao11.cn/Article/details/gtakrzofww.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258888.top/Article/details/gtvzzjijus.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtthqpkxax.html

JS:   greet() { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gttbajjuxn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gtsqfxdskf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtuohotmad.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigufen.top/Article/details/gtgjmzaafb.html

Ruby: def greet; "admin"; end
来源：http://dali.ivvv.top/Article/details/gtqnxcxlbu.html

C#:   public override string Greet() => "admin";
来源：http://dali.ehwqpu.com/Article/details/gtbikycdre.html

[G07] 调用父类方法
来源：http://dali.vqdsnc.cn/Article/details/gtlogtatms.html

Py:   super().greet()
来源：http://dali.jinqigufen.top/Article/details/gtwscjthgr.html

PHP:  parent::greet();
来源：http://dali.kuanghao11.cn/Article/details/gtyurjfiod.html

JS:   super.greet();
来源：http://dali.bjfxy.top/Article/details/gtveiespvz.html

TS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvxolkjg.html

Java: super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtrwxebdia.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yueranfly.top/Article/details/gtdcvoasyl.html

Ruby: super
来源：http://dali.yuanzhike.top/Article/details/gtttltlomd.html

C#:   base.Greet();
来源：http://dali.sxryk.cn/Article/details/gtvzaidxnp.html

[G08] 静态方法与属性
来源：http://dali.yanxiufei.cn/Article/details/gttaztxepj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.meibo888.top/Article/details/gtvuuigfru.html

PHP:  public static function f() {}
来源：http://dali.chenlongwang.top/Article/details/gtlueggoho.html

JS:   static f() {}
来源：http://dali.iojbl.cn/Article/details/gtqnexpgbz.html

TS:   static f(): void {}
来源：http://dali.sufxvd.cn/Article/details/gttvmbokiy.html

Java: static void f() {}
来源：http://dali.zhixingplan.top/Article/details/gtbqfqvrke.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnxiangtu.top/Article/details/gtzlkjorjl.html

Ruby: def self.f; end
来源：http://dali.andypj.xyz/Article/details/gtdcyhupan.html

C#:   public static void F() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtceyqoeha.html

[G09] 接口 / 抽象类
来源：http://dali.jiagoushi.top/Article/details/gtgnfcsfey.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.9152youxi.cn/Article/details/gtlzxeqhzx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ivvv.top/Article/details/gtmlbqbypm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjlqwnpf.html

TS:   interface Shape { area(): number; }
来源：http://dali.cashguo.top/Article/details/gtdpowptjz.html

Java: interface Shape { double area(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgegfbqep.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhixingplan.top/Article/details/gtvelqikxh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.andypj.xyz/Article/details/gtwqumixqo.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigufen.top/Article/details/gtxwxpetet.html

[G10] 访问控制
来源：http://dali.jqgfzy.top/Article/details/gtboqisjtf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jyoumei.cn/Article/details/gtyyukwffr.html

PHP:  public / protected / private
来源：http://dali.cheryme.top/Article/details/gtblqjhuvy.html

JS:   #private 字段；其余公开
来源：http://dali.cqqwz.cn/Article/details/gtxeoxngvw.html

TS:   public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtmpnfuynp.html

Java: public / protected / private / 默认包级
来源：http://dali.hfpthk.cn/Article/details/gtubpprbdc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhaomingkeji.xyz/Article/details/gteoxyvdox.html

Ruby: public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtkekyxtjv.html

C#:   public / protected / private / internal
来源：http://dali.chenzaomai.com/Article/details/gtkjpfwoon.html

[G11] getter / setter
来源：http://dali.iojbl.cn/Article/details/gtogljxxjp.html

Py:   @property 与 @x.setter
来源：http://dali.ivvv.top/Article/details/gtsooasxfq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gtlujkucbh.html

JS:   get name() { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gtwjpvcquf.html

TS:   get name(): string { return this._name; }
来源：http://dali.snrcjt.cn/Article/details/gtnsizvqta.html

Java: public String getName() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gthffqrfoy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gtbnyndzri.html

Ruby: attr_accessor :name
来源：http://dali.guannengcc.top/Article/details/gtubgywthy.html

C#:   public string Name { get; set; }
来源：http://dali.andypj.xyz/Article/details/gtislyisct.html

[G12] 对象转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtpbnpvomm.html

Py:   def __str__(self): return self.name
来源：http://dali.hongshengwenyu.top/Article/details/gtipihugsz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gteuhkuimm.html

JS:   toString() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtagghymdd.html

TS:   toString(): string { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtoibhlopw.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtkswnxgxg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtdnxfrbvn.html

Ruby: def to_s; @name; end
来源：http://dali.ehwqpu.com/Article/details/gtbonhbspp.html

C#:   public override string ToString() => Name;
来源：http://dali.shuidangran.top/Article/details/gtfbmbhkhy.html

[G13] 判断对象类型
来源：http://dali.gzhubu.top/Article/details/gtwjcbonvd.html

Py:   isinstance(u, User)
来源：http://dali.hnqzz.top/Article/details/gtawkmjuyi.html

PHP:  $u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpybhoqeh.html

JS:   u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtubwjqxvd.html

TS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtklnvlhhj.html

Java: u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtpsagcqbc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gogol.net.cn/Article/details/gtdwcitnww.html

Ruby: u.is_a?(User)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrwsetzml.html

C#:   u is User
来源：http://dali.aizwys.cn/Article/details/gtiuqczzwz.html

[G14] 数据类 / record
来源：http://dali.jyoumei.cn/Article/details/gtfuggamii.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gogol.net.cn/Article/details/gtvmxwdwyv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hywenlv.cn/Article/details/gtalporfmg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.snrcjt.cn/Article/details/gtveclaszg.html

TS:   type User = { name: string; age: number };
来源：http://dali.yuanzhike.top/Article/details/gtzxhtjzhk.html

Java: record User(String name, int age) {}
来源：http://dali.xuanzx.com/Article/details/gtxfungutr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dashuyun.cn/Article/details/gtorquqgrq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhongyouzk.top/Article/details/gtvfwwzmsm.html


<!-- 参考信息 -->