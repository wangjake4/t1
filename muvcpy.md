代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ydzc1.top/Article/details/gt2sjzqgriv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xziqi.cn/Article/details/gt2sllemksd.html

C#:   1234567.ToString("N0")
来源：http://dali.jinqigfzy.top/Article/details/gt2qildsgpv.html

[E17] 首字母大写
来源：http://dali.sysykeji.top/Article/details/gt2bsrcfqff.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shzxlz.cn/Article/details/gt2wnrmyxiu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhixingplan.top/Article/details/gt2sqmdvhdu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2mjgfqftg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gt2bvkfvnvg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.dianchejie.cn/Article/details/gt2dzznrnyg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.haohaochexian.top/Article/details/gt2kbyslehq.html

Ruby: s.capitalize
来源：http://dali.kuanghao11.cn/Article/details/gt2hilkwefv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jqgufenzy.top/Article/details/gt2rkoqhqza.html

[E18] 模板占位符替换
来源：http://dali.316326.xyz/Article/details/gt2zfryaxjg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guowangkeji.top/Article/details/gt2wlcngkyv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tian-w.cn/Article/details/gt2jpqklkyj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gt2ghsxtcyn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gt2owikymlm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cashguo.top/Article/details/gt2xebdcgje.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gt2jwaiimqj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hfpthk.cn/Article/details/gt2dbyirkjo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shzxlz.cn/Article/details/gt2avlbeuii.html

[E19] 多行文本按行拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2buqbamzi.html

Py:   s.splitlines()
来源：http://dali.smart0.xyz/Article/details/gt2ctawfrfw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.c1oappe.top/Article/details/gt2ixcprccb.html

JS:   s.split(/\r?\n/)
来源：http://dali.iojbl.cn/Article/details/gt2ahaoknkw.html

TS:   s.split(/\r?\n/)
来源：http://dali.haohaochexian.top/Article/details/gt2ppwajzkz.html

Java: s.lines().toList()
来源：http://dali.yuxming.cn/Article/details/gt2xsemapey.html

Go:   strings.Split(s, "\n")
来源：http://dali.tanke756.top/Article/details/gt2cmydjvfl.html

Ruby: s.lines
来源：http://dali.tianlin.xyz/Article/details/gt2mtcxphve.html

C#:   s.Split('\n')
来源：http://dali.hammf.cn/Article/details/gt2mfxrsaio.html

[E20] 判断字符串是否为空
来源：http://dali.zhongyouzk.top/Article/details/gt2llutmvns.html

Py:   if not s:
来源：http://dali.hnqzz.top/Article/details/gt2oxmupkfo.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xuetiantiany.cn/Article/details/gt2ibbnmaab.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cheryme.top/Article/details/gt2svbqpxqr.html

TS:   if (s === "") {}
来源：http://dali.guowangkeji.top/Article/details/gt2huxeatuw.html

Java: if (s.isEmpty()) {}
来源：http://dali.svipenyu.cn/Article/details/gt2rxavnvhf.html

Go:   if s == "" {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2zxaiezqw.html

Ruby: if s.empty?
来源：http://dali.yj20258.top/Article/details/gt2pvsthhnj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.316326.xyz/Article/details/gt2bfcvoomm.html

[E21] 超长截断加省略号
来源：http://dali.yj20258888.top/Article/details/gt2soszsmrr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jqgfzy.top/Article/details/gt2poknnisx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gt2zemrutdq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gt2trycwooy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gt2ymiintkx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gt2jtkpgjip.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shangyingyoupin.top/Article/details/gt2utkfkfdf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gt2eoorphpj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gt2qtrwqkzj.html

[E22] 字节长度与字符长度
来源：http://dali.ivvv.top/Article/details/gt2zepreyhv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.0kj1m.cn/Article/details/gt2lzqnjncb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gt2sawqxpso.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gt2miivgmbp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gt2ujysnnun.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tksyptiq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tianlin.xyz/Article/details/gt2pvlxvkdd.html

Ruby: s.bytesize;  s.length
来源：http://dali.yangfankeji.com/Article/details/gt2yvlbrlny.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hongshengwenyu.top/Article/details/gt2kqaipehv.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2nqfzupux.html

F. 文件与目录
来源：http://dali.snrcjt.cn/Article/details/gt2qhykczum.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2fqucparb.html

[F01] 读取整个文件
来源：http://dali.cashguo.top/Article/details/gt2uelbdrxn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yangfankeji.com/Article/details/gt2teghcnue.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwvxqvh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.andypj.xyz/Article/details/gt2voaurkfo.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gt2qwismusq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2zpmndfst.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.aizwys.cn/Article/details/gt2xavntadz.html

Ruby: File.read("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2vxmhxtxv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2sywvzapc.html

[F02] 逐行读取文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2xmoxxtjo.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.snrcjt.cn/Article/details/gt2emxbkalv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.vqdsnc.cn/Article/details/gt2xrixwrfa.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lgvryqbw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wxufqqyd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gt2mkdkgzjb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tanke756.top/Article/details/gt2qyfedxvy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnxiangtu.top/Article/details/gt2tggdbwmu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnxiangtu.top/Article/details/gt2ybgoaiof.html

[F03] 写入文件（覆盖）
来源：http://dali.fengsongda.top/Article/details/gt2rnynqmwg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.vqdsnc.cn/Article/details/gt2tusbdtyl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gt2eajwytqk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gt2cldmzycs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gt2vabylhwm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.mhx1999.top/Article/details/gt2mtmarisc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258.top/Article/details/gt2nxrncwec.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenjidiqi.icu/Article/details/gt2kwkxvpqd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.fengsongda.top/Article/details/gt2fepaycad.html

[F04] 追加写入文件
来源：http://dali.aibaodan.cn/Article/details/gt2fjcyowdg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.316326.xyz/Article/details/gt2edzkitjc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenlongwang.top/Article/details/gt2hwcseqmf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sogdsows.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yueranfly.top/Article/details/gt2aqyrkjzi.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.vqdsnc.cn/Article/details/gt2twnggnqj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yangfankeji.com/Article/details/gt2nffqmqbe.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tbbvwewm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.aizwys.cn/Article/details/gt2imdcsbcj.html

[F05] 判断文件或目录是否存在
来源：http://dali.xylfe.cn/Article/details/gt2ilammdon.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dflzeuhz.html

PHP:  file_exists("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2huwcnmlo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2mxrzpegb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jqaetyjr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gt2lhoifsxo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cqqwz.cn/Article/details/gt2xigtbicc.html

Ruby: File.exist?("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2aigxlzro.html

C#:   File.Exists("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2sslqdgxn.html

[F06] 删除文件
来源：http://dali.cdnleiting.top/Article/details/gt2ypndalpu.html

Py:   os.remove("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2uguyskei.html

PHP:  unlink("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2nbxebhbp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2arvtezsf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2ekjboajy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gt2imqtblcx.html

Go:   os.Remove("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2tqmbdbgx.html

Ruby: File.delete("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2dvhtstvj.html

C#:   File.Delete("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2ttowrexn.html

[F07] 创建目录（含多级）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vhzgzadr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hbnyhshb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.feifeiyinyue.top/Article/details/gt2nhuhbdok.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gt2tefxtszj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gotoacloud.top/Article/details/gt2fekysodr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gzhubu.top/Article/details/gt2ejzgzxyf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.quarkkingdee.top/Article/details/gt2zasghrfh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yavukqkv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xziqi.cn/Article/details/gt2zrkdltzp.html

[F08] 遍历目录
来源：http://dali.chenzaomai.com/Article/details/gt2celyibgl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yvedp.cn/Article/details/gt2sxohdxxn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigufen.top/Article/details/gt2qprfikfo.html

JS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2xkehspat.html

TS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gt2fghadria.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hywenlv.cn/Article/details/gt2ujotlmcs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigufen.top/Article/details/gt2blmsrldq.html

Ruby: Dir.children("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gt2tgldcocg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj202588.top/Article/details/gt2wgnqibds.html

[F09] 获取文件大小
来源：http://dali.xziqi.cn/Article/details/gt2nyiwbdpw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2lzyvthto.html

PHP:  filesize("a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2fulkewux.html

JS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gt2jempcdkp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.c1oappe.top/Article/details/gt2sjrquaon.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gt2obzdrihr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhixingplan.top/Article/details/gt2nhyiumdl.html

Ruby: File.size("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2tlinszvc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ppjwa.cn/Article/details/gt2swvtjhdx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xylfe.cn/Article/details/gt2mcxwgyhe.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2pgzshgbm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2wcwjnglx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2qupvvxwt.html

TS:   path.extname("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2oswklddy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nanxuanxn.top/Article/details/gt2twkystbd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2zmykjxpq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2gynqnbxo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2jabvdclr.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ciwunqtj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gt2bomwsemp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jianghu66.top/Article/details/gt2ghrkgmbe.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gt2nfsztivs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2ksnihfvn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gt2roktgpsd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daria6918.cn/Article/details/gt2tywuwpjm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gt2nkbqvapr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.mhx1999.top/Article/details/gt2rztlabut.html

[F12] CSV 读写
来源：http://dali.gotoacloud.top/Article/details/gt2cfhpiong.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aibaodan.cn/Article/details/gt2skxqsjqx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258.top/Article/details/gt2wktnzuws.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhoulong.xyz/Article/details/gt2zfujucad.html

TS:   // 同上
来源：http://dali.316326.xyz/Article/details/gt2totnrzwj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj20258888.top/Article/details/gt2gczskfkz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ybcxt.top/Article/details/gt2kcrxeexl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mgqfjwig.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.havefunace.top/Article/details/gt2kwqbzjqt.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2wohxymzm.html

G. 面向对象
来源：http://dali.jqgufenzy.top/Article/details/gt2gonvlvkj.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2cezeyoqv.html

[G01] 定义类
来源：http://dali.cashguo.top/Article/details/gt2dyfwqbmp.html

Py:   class User: pass
来源：http://dali.fzhhl.top/Article/details/gt2mfknuoen.html

PHP:  class User {}
来源：http://dali.guowangkeji.top/Article/details/gt2hvtjlvuw.html

JS:   class User {}
来源：http://dali.dashuyun.cn/Article/details/gt2dsaacupx.html

TS:   class User { name: string = ""; }
来源：http://dali.zhongyouzk.top/Article/details/gt2dguwqnxe.html

Java: class User {}
来源：http://dali.guowangkeji.top/Article/details/gt2ryefezcu.html

Go:   type User struct { Name string }
来源：http://dali.0kj1m.cn/Article/details/gt2lfgnjypt.html

Ruby: class User; end
来源：http://dali.gotoacloud.top/Article/details/gt2jzvpjcth.html

C#:   class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ebdypckp.html

[G02] 构造函数
来源：http://dali.nwbrower.top/Article/details/gt2apzcwjsv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hnqzz.top/Article/details/gt2utrhoetc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cashguo.top/Article/details/gt2fgvqnsea.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gt2nhqkrvpm.html

TS:   constructor(public name: string) {}
来源：http://dali.jiagoushi.top/Article/details/gt2xjipnwai.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gt2ezykkftl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj20258888.top/Article/details/gt2zzogxyuz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ivvv.top/Article/details/gt2weioetuk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.fengsongda.top/Article/details/gt2yanfkutf.html

[G03] 实例属性
来源：http://dali.xuanzx.com/Article/details/gt2kbyaiuqr.html

Py:   self.name = "x"
来源：http://dali.yvedp.cn/Article/details/gt2bmffdsxb.html

PHP:  public string $name = "x";
来源：http://dali.zhoulong.xyz/Article/details/gt2agdtzsje.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ksqcpqth.html

TS:   name: string = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gt2mjcfztwo.html

Java: private String name;
来源：http://dali.ivvv.top/Article/details/gt2xjplijku.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ydzc1.top/Article/details/gt2byzkxsml.html

Ruby: @name = "x"
来源：http://dali.zdqjudy.top/Article/details/gt2imytdhly.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xuanzx.com/Article/details/gt2ofqimiiv.html

[G04] 定义方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vsyewsqe.html

Py:   def greet(self): return self.name
来源：http://dali.jinqigfzy.top/Article/details/gt2vpnowais.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gt2vflhqcmp.html

JS:   greet() { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gt2fajphewz.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cvfuhzxd.html

Java: String greet() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2teexenym.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qgmovjpa.html

Ruby: def greet; @name; end
来源：http://dali.dashuyun.cn/Article/details/gt2hkwoaeix.html

C#:   public string Greet() => Name;
来源：http://dali.yj202588.top/Article/details/gt2nrkcbpvy.html

[G05] 继承
来源：http://dali.tanke756.top/Article/details/gt2lvpyhppr.html

Py:   class Admin(User): pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pybrzlut.html

PHP:  class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gt2djvrlhnm.html

JS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gt2umrobyzg.html

TS:   class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gt2hdlpnzxw.html

Java: class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gt2bincrdvx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuxming.cn/Article/details/gt2dtgmkfrk.html

Ruby: class Admin < User; end
来源：http://dali.fzhhl.top/Article/details/gt2zsmzvwdo.html

C#:   class Admin : User {}
来源：http://dali.haohaochexian.top/Article/details/gt2mbbxhqce.html

[G06] 重写方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2twfhqkar.html

Py:   def greet(self): return "admin"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zpgkbwgj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gt2huyeggyt.html

JS:   greet() { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2mgbcgrlc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gt2pkuixjpj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gt2wizfziko.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tianlin.xyz/Article/details/gt2qxwfiiaf.html

Ruby: def greet; "admin"; end
来源：http://dali.ppjwa.cn/Article/details/gt2yhgvkklr.html

C#:   public override string Greet() => "admin";
来源：http://dali.xinyue.icu/Article/details/gt2ddwfsdjo.html

[G07] 调用父类方法
来源：http://dali.quarkkingdee.top/Article/details/gt2kmwpuuha.html

Py:   super().greet()
来源：http://dali.shangyingyoupin.top/Article/details/gt2libdubdj.html

PHP:  parent::greet();
来源：http://dali.gaohongyu789.top/Article/details/gt2dzcilvqc.html

JS:   super.greet();
来源：http://dali.yj202588.top/Article/details/gt2zbcofxtl.html

TS:   super.greet();
来源：http://dali.sysykeji.top/Article/details/gt2kkevfpyf.html

Java: super.greet();
来源：http://dali.xylfe.cn/Article/details/gt2vsfbdbeg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.quarkkingdee.top/Article/details/gt2axihkwdm.html

Ruby: super
来源：http://dali.9152youxi.cn/Article/details/gt2icngelon.html

C#:   base.Greet();
来源：http://dali.jianghu66.top/Article/details/gt2zmbmhotc.html

[G08] 静态方法与属性
来源：http://dali.pengpengdd.cyou/Article/details/gt2esdlakfh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuetiantiany.cn/Article/details/gt2bnjepnnb.html

PHP:  public static function f() {}
来源：http://dali.jiagoushi.top/Article/details/gt2nfqqmhpr.html

JS:   static f() {}
来源：http://dali.daria6918.cn/Article/details/gt2yhkznpeu.html

TS:   static f(): void {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cvatiaqb.html

Java: static void f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nxslxjtg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangshuangyany.cn/Article/details/gt2llgjvyib.html

Ruby: def self.f; end
来源：http://dali.jiagoushi.top/Article/details/gt2unyzqnxj.html

C#:   public static void F() {}
来源：http://dali.hnqzz.top/Article/details/gt2taexwohd.html

[G09] 接口 / 抽象类
来源：http://dali.pycfn.com/Article/details/gt2kefopmxj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tian-w.cn/Article/details/gt2oddqvmav.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tanke756.top/Article/details/gt2ydttkzgp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tanke756.top/Article/details/gt2roomjwgl.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxinkj.top/Article/details/gt2ccbamspv.html

Java: interface Shape { double area(); }
来源：http://dali.nwbrower.top/Article/details/gt2bmvahbcm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxinkj.top/Article/details/gt2bzgaccax.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yipwedhq.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2wckteict.html

[G10] 访问控制
来源：http://dali.feifeiyinyue.top/Article/details/gt2nlqnohiq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.pengpengdd.cyou/Article/details/gt2qleestra.html

PHP:  public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gt2fuucrybj.html

JS:   #private 字段；其余公开
来源：http://dali.zhongyouzk.top/Article/details/gt2vchyptbu.html

TS:   public / protected / private
来源：http://dali.hammf.cn/Article/details/gt2zvbgagct.html

Java: public / protected / private / 默认包级
来源：http://dali.0kj1m.cn/Article/details/gt2erhljiyo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnxiangtu.top/Article/details/gt2kjcdwfgv.html

Ruby: public / protected / private
来源：http://dali.ybcxt.top/Article/details/gt2rcaoumoi.html

C#:   public / protected / private / internal
来源：http://dali.fengsongda.top/Article/details/gt2liwmvjje.html

[G11] getter / setter
来源：http://dali.hnxiangtu.top/Article/details/gt2dxsmzhbi.html

Py:   @property 与 @x.setter
来源：http://dali.xuetiantiany.cn/Article/details/gt2rfmjkzbp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gt2txzuxeqt.html

JS:   get name() { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eyentjam.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfynkdi.html

Java: public String getName() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gt2bmusqmzx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gt2joqqdfer.html

Ruby: attr_accessor :name
来源：http://dali.jinqigfzy.top/Article/details/gt2occgudjx.html

C#:   public string Name { get; set; }
来源：http://dali.jianghu66.top/Article/details/gt2llzuqpqf.html

[G12] 对象转字符串
来源：http://dali.gogol.net.cn/Article/details/gt2phrkinhs.html

Py:   def __str__(self): return self.name
来源：http://dali.meibo888.top/Article/details/gt2uxeljpnb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2ttoeviwd.html

JS:   toString() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gt2hafspdsa.html

TS:   toString(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gwbdzjld.html

Java: @Override public String toString() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2luucdzih.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gt2tudpjtch.html

Ruby: def to_s; @name; end
来源：http://dali.ehwqpu.com/Article/details/gt2kiwyphvj.html

C#:   public override string ToString() => Name;
来源：http://dali.gogol.net.cn/Article/details/gt2twnzkxpa.html

[G13] 判断对象类型
来源：http://dali.cheryme.top/Article/details/gt2atzxhfyg.html

Py:   isinstance(u, User)
来源：http://dali.snrcjt.cn/Article/details/gt2mocnvmfa.html

PHP:  $u instanceof User
来源：http://dali.mhx1999.top/Article/details/gt2oyzlyhbw.html

JS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gt2nveawxjc.html

TS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gt2lgdfpbdj.html

Java: u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gt2uzamdjqm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.0kj1m.cn/Article/details/gt2tewajams.html

Ruby: u.is_a?(User)
来源：http://dali.cashguo.top/Article/details/gt2aovjubdv.html

C#:   u is User
来源：http://dali.meibo888.top/Article/details/gt2kbmkbgca.html

[G14] 数据类 / record
来源：http://dali.yuanzhike.top/Article/details/gt2eoiacbau.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fnnfmtwn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.316326.xyz/Article/details/gt2kpedjfys.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2qspccvqw.html

TS:   type User = { name: string; age: number };
来源：http://dali.daria6918.cn/Article/details/gt2zomzhanj.html

Java: record User(String name, int age) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2cimxeezq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgufenzy.top/Article/details/gt2tdfswuvv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ybcxt.top/Article/details/gt2ysgrczql.html

C#:   record User(string Name, int Age);
来源：http://dali.yuanzhike.top/Article/details/gt2jxdfimtk.html

[G15] 枚举
来源：http://dali.jyoumei.cn/Article/details/gt2dcrxtujj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lyveikek.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cheryme.top/Article/details/gt2fytdliwa.html


<!-- 参考信息 -->