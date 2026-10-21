代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aizwys.cn/Article/details/gtihoqwjkz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xylfe.cn/Article/details/gtqznqjqco.html

[E16] 数字千分位
来源：http://dali.redwolf501.top/Article/details/gtmarvwmnr.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtwyuraaab.html

PHP:  number_format(1234567);
来源：http://dali.zhongyouzk.top/Article/details/gtajtyncwr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.vqdsnc.cn/Article/details/gtdnruiuwg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sysykeji.top/Article/details/gtctyjscbq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.vqdsnc.cn/Article/details/gtqnsyfrwg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jianghu66.top/Article/details/gtqzudvqwo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ivvv.top/Article/details/gtcyinwwfd.html

C#:   1234567.ToString("N0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqrjojnjd.html

[E17] 首字母大写
来源：http://dali.yj202588.top/Article/details/gtsbfkyfgh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jqgufenzy.top/Article/details/gthqrmeede.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkvozbmbl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jyoumei.cn/Article/details/gtetynlrek.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gtldfpxgwa.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tianlin.xyz/Article/details/gtwwjyemqn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dianchejie.cn/Article/details/gtcyhibzai.html

Ruby: s.capitalize
来源：http://dali.hongshengwenyu.top/Article/details/gtdulgxqyl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.c1oappe.top/Article/details/gtpaemzbjz.html

[E18] 模板占位符替换
来源：http://dali.guannengcc.top/Article/details/gtzrgnwrqr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xuanzx.com/Article/details/gtwssxngym.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tian-w.cn/Article/details/gtvsejcoao.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtwaofyjxm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gtviawsmiy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtvywzlcne.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzanhjei.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guannengcc.top/Article/details/gthioizvtl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shzxlz.cn/Article/details/gteaftpakt.html

[E19] 多行文本按行拆分
来源：http://dali.tianlin.xyz/Article/details/gteokgtdkr.html

Py:   s.splitlines()
来源：http://dali.nwbrower.top/Article/details/gtlpyatjay.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gteqzgmpqp.html

JS:   s.split(/\r?\n/)
来源：http://dali.cqqwz.cn/Article/details/gtziwawzzk.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhsxjdpz.html

Java: s.lines().toList()
来源：http://dali.shzxlz.cn/Article/details/gttspfmpli.html

Go:   strings.Split(s, "\n")
来源：http://dali.xziqi.cn/Article/details/gtgxosacka.html

Ruby: s.lines
来源：http://dali.yueranfly.top/Article/details/gtkdcohojt.html

C#:   s.Split('\n')
来源：http://dali.feifeiyinyue.top/Article/details/gtabrnihcw.html

[E20] 判断字符串是否为空
来源：http://dali.jqgufenzy.top/Article/details/gtkqbsspad.html

Py:   if not s:
来源：http://dali.mhx1999.top/Article/details/gtqwsfoewp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xuetiantiany.cn/Article/details/gtuwdlzdar.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.birdmap.top/Article/details/gtbsobxzbq.html

TS:   if (s === "") {}
来源：http://dali.jqgufenzy.top/Article/details/gtavtasubm.html

Java: if (s.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcgblbee.html

Go:   if s == "" {}
来源：http://dali.tian-w.cn/Article/details/gtsfnltvdo.html

Ruby: if s.empty?
来源：http://dali.bjfxy.top/Article/details/gtotaefpvb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.bjfxy.top/Article/details/gtxrwhyblz.html

[E21] 超长截断加省略号
来源：http://dali.yj202588.top/Article/details/gtppftnuyw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sufxvd.cn/Article/details/gtvtscnzjh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtmcahmtuw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtvnddizqp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gthwwplzsx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gthgdjzaiz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtosvjwqaz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtcalcdvbb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtepjbwvuw.html

[E22] 字节长度与字符长度
来源：http://dali.andypj.xyz/Article/details/gtlrytjdzk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yvedp.cn/Article/details/gtrbjhovsg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gtflqdyrbd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtkycpdwfm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gtcnbvexen.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangdashe.top/Article/details/gtqdlcdtpx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jqgufenzy.top/Article/details/gtidwkciaf.html

Ruby: s.bytesize;  s.length
来源：http://dali.316326.xyz/Article/details/gtzajwhvho.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zycfv.cn/Article/details/gtpaddfope.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtfdwlejbk.html

F. 文件与目录
来源：http://dali.jinqigfzy.top/Article/details/gtwgdfgpaj.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtrtvppaia.html

[F01] 读取整个文件
来源：http://dali.zhongyouzk.top/Article/details/gtneoxaymv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.kuanghao11.cn/Article/details/gttfbbxdxi.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtjbboifzf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fzhhl.top/Article/details/gtjrnkitgm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthynunfjz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtgkxmotwm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.fengsongda.top/Article/details/gteeddchjl.html

Ruby: File.read("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtmgngrdgb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtqyfbewyw.html

[F02] 逐行读取文件
来源：http://dali.yanxiufei.cn/Article/details/gtbyebmwdb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ywan-chungtsiang.top/Article/details/gttndjavmj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yonumen.top/Article/details/gtpwovqyin.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cdnleiting.top/Article/details/gtatzchpre.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.9152youxi.cn/Article/details/gtqbwlmiak.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj20258888.top/Article/details/gtymwxzcsm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangdashe.top/Article/details/gtqakynxaq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzpecpxtl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhongyouzk.top/Article/details/gtjzgysglp.html

[F03] 写入文件（覆盖）
来源：http://dali.sxryk.cn/Article/details/gtlcwomfev.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sufxvd.cn/Article/details/gtkgtxddni.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nwbrower.top/Article/details/gtsvftcjfa.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtixwwmxdp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gtlcrlabqz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtmdktxjrf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zdqjudy.top/Article/details/gtixvxxsdm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhoulong.xyz/Article/details/gtqbkjdikn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gtebdjsjnh.html

[F04] 追加写入文件
来源：http://dali.cdnleiting.top/Article/details/gtomrlxzsy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.redwolf501.top/Article/details/gtltpqcgni.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.svipenyu.cn/Article/details/gthzfgxhsm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shzxlz.cn/Article/details/gtjrbhocot.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dianchejie.cn/Article/details/gtbuuwlqjk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.daria6918.cn/Article/details/gttovxtoxv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hysaishi.cn/Article/details/gtkekbwctu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.quarkkingdee.top/Article/details/gtvwrkrcou.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gogol.net.cn/Article/details/gtveoqijxu.html

[F05] 判断文件或目录是否存在
来源：http://dali.yangfankeji.com/Article/details/gtvkrcsvkh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sufxvd.cn/Article/details/gtgyzfvbep.html

PHP:  file_exists("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtbzqwpojk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtpaizsvfz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtfsronvcm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtrgbenaze.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xuetiantiany.cn/Article/details/gtxvhtwvpx.html

Ruby: File.exist?("a.txt")
来源：http://dali.sweek.top/Article/details/gtuabcdzyj.html

C#:   File.Exists("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtmajvajpn.html

[F06] 删除文件
来源：http://dali.dashuyun.cn/Article/details/gtraqmgapl.html

Py:   os.remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtlhaazqtd.html

PHP:  unlink("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrrsvyow.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtqbpgprqf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gtzsnmfink.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtyoxlehmr.html

Go:   os.Remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtlmgxdijz.html

Ruby: File.delete("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtkynrgfcw.html

C#:   File.Delete("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtzvbpkhnx.html

[F07] 创建目录（含多级）
来源：http://dali.yj20258.top/Article/details/gtzlbbbdfw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.0kj1m.cn/Article/details/gttoknidud.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yonumen.top/Article/details/gturbftnbk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.smart0.xyz/Article/details/gtggfqswvg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ivvv.top/Article/details/gthreqlkji.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhengqikj.top/Article/details/gtugizmugc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jlsjyb.cn/Article/details/gtirfpvlst.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yangfankeji.com/Article/details/gtdwwptsbx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yonumen.top/Article/details/gtkqrpxuwy.html

[F08] 遍历目录
来源：http://dali.aibaodan.cn/Article/details/gtyzyshcau.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.wangshuangyany.cn/Article/details/gtcjnqfzzg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnqzz.top/Article/details/gtwwtmrdqk.html

JS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gtsiamgizv.html

TS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtimuhjood.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gtzdwuhfrq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gzhubu.top/Article/details/gtxprpqgfd.html

Ruby: Dir.children("dir")
来源：http://dali.shzxlz.cn/Article/details/gtwepmivrt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj20258.top/Article/details/gtylpqprap.html

[F09] 获取文件大小
来源：http://dali.sysykeji.top/Article/details/gtfqxygylt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtdwfcluug.html

PHP:  filesize("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtfkzhunok.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gtwnvkdlmo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.meibo888.top/Article/details/gtzyclgrmb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtrqtdlonk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xylfe.cn/Article/details/gtxxnmjkww.html

Ruby: File.size("a.txt")
来源：http://dali.birdmap.top/Article/details/gttcopsrly.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuxming.cn/Article/details/gtasoqjyig.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yonumen.top/Article/details/gtojppgtsk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtnrpbkydm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yonumen.top/Article/details/gtedjbyfle.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtptfpionr.html

TS:   path.extname("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtrrjzavhz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yvedp.cn/Article/details/gtdylltvnh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtlnageseu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtspxfbfrj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtgmwwkyhc.html

[F11] 复制与移动文件
来源：http://dali.gogol.net.cn/Article/details/gtzfiyajtp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtuatrevhv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhoulong.xyz/Article/details/gttoeqhvvz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtjbxwhkbe.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtehfvmtqv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gtpsiraryx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shzxlz.cn/Article/details/gtacufqwky.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gthqsertfh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.andypj.xyz/Article/details/gttixdnkru.html

[F12] CSV 读写
来源：http://dali.xylfe.cn/Article/details/gtyuwkmmeq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shangyingyoupin.top/Article/details/gtrvvgyvpc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tanke756.top/Article/details/gtgpblsvmy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhoulong.xyz/Article/details/gtylzzvtcj.html

TS:   // 同上
来源：http://dali.zhongyouzk.top/Article/details/gtgwfalgls.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuxming.cn/Article/details/gthepkvnif.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xinyue.icu/Article/details/gtnqpdzwwi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.bjfxy.top/Article/details/gtjjsdrubp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ydzc1.top/Article/details/gtjybutyys.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gttcfbdakm.html

G. 面向对象
来源：http://dali.feifeiyinyue.top/Article/details/gtaraltumz.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzugwykv.html

[G01] 定义类
来源：http://dali.zhixingplan.top/Article/details/gtfmnomczv.html

Py:   class User: pass
来源：http://dali.smart0.xyz/Article/details/gthntmpdte.html

PHP:  class User {}
来源：http://dali.ydzc1.top/Article/details/gtxxoerrzn.html

JS:   class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtmmnyqkvx.html

TS:   class User { name: string = ""; }
来源：http://dali.wangdashe.top/Article/details/gtextpzzvv.html

Java: class User {}
来源：http://dali.sxryk.cn/Article/details/gtgaeipoyq.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtobbvgrvs.html

Ruby: class User; end
来源：http://dali.smart0.xyz/Article/details/gtjfvwwowd.html

C#:   class User {}
来源：http://dali.xinyue.icu/Article/details/gtqcatwkmi.html

[G02] 构造函数
来源：http://dali.ppjwa.cn/Article/details/gtenwryxqi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gtqaiclend.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtiezwwiym.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gtnimrpcla.html

TS:   constructor(public name: string) {}
来源：http://dali.daria6918.cn/Article/details/gtalwieqwj.html

Java: User(String name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtwyprvxpc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ehwqpu.com/Article/details/gtjeeycdpf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sufxvd.cn/Article/details/gtlutoqdqv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gtsrftgned.html

[G03] 实例属性
来源：http://dali.316326.xyz/Article/details/gtklqyennp.html

Py:   self.name = "x"
来源：http://dali.cheryme.top/Article/details/gtvocfbldi.html

PHP:  public string $name = "x";
来源：http://dali.hysaishi.cn/Article/details/gtnmmpmkfq.html

JS:   this.name = "x";
来源：http://dali.hfpthk.cn/Article/details/gtsteiyqww.html

TS:   name: string = "x";
来源：http://dali.ydzc1.top/Article/details/gtcypgozno.html

Java: private String name;
来源：http://dali.vqdsnc.cn/Article/details/gtsmjhcuvt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yvedp.cn/Article/details/gtnhwsicdp.html

Ruby: @name = "x"
来源：http://dali.smart0.xyz/Article/details/gtkivscqpw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuxming.cn/Article/details/gtboqhntou.html

[G04] 定义方法
来源：http://dali.cucudq.cn/Article/details/gtujhmetks.html

Py:   def greet(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gtfqiagdnc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtrfitzibe.html

JS:   greet() { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtekzgogof.html

TS:   greet(): string { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gttcjqhnzz.html

Java: String greet() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtqncqresx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gtbjouycnm.html

Ruby: def greet; @name; end
来源：http://dali.yj202588.top/Article/details/gtxulyjgnf.html

C#:   public string Greet() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gtfkcdtbge.html

[G05] 继承
来源：http://dali.sweek.top/Article/details/gtkwtbjhzp.html

Py:   class Admin(User): pass
来源：http://dali.haohaochexian.top/Article/details/gtpldyifnr.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtmytfuynn.html

JS:   class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtwapepnml.html

TS:   class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtynnhzmdp.html

Java: class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtuqeojtje.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiixerjlh.html

Ruby: class Admin < User; end
来源：http://dali.kuanghao11.cn/Article/details/gtnippoqpo.html

C#:   class Admin : User {}
来源：http://dali.daria6918.cn/Article/details/gtxewozjxv.html

[G06] 重写方法
来源：http://dali.xylfe.cn/Article/details/gtefyddvfs.html

Py:   def greet(self): return "admin"
来源：http://dali.c1oappe.top/Article/details/gtiuvnddru.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtwifkivup.html

JS:   greet() { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtwkdjvmxf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttexvuucq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtvqdbwcqb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.dianchejie.cn/Article/details/gtuklploem.html

Ruby: def greet; "admin"; end
来源：http://dali.wangshuangyany.cn/Article/details/gtfoeacmoy.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghbogrcl.html

[G07] 调用父类方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvwzzrnwj.html

Py:   super().greet()
来源：http://dali.daxiang520.top/Article/details/gtlxtyemzc.html

PHP:  parent::greet();
来源：http://dali.xziqi.cn/Article/details/gtfceomxam.html

JS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gthjbtpgcv.html

TS:   super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkxvtfrhx.html

Java: super.greet();
来源：http://dali.nwbrower.top/Article/details/gtseanhirk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zycfv.cn/Article/details/gttipkpxot.html

Ruby: super
来源：http://dali.birdmap.top/Article/details/gtucwzralq.html

C#:   base.Greet();
来源：http://dali.jqgfzy.top/Article/details/gtdjznnwgt.html

[G08] 静态方法与属性
来源：http://dali.redwolf501.top/Article/details/gtolhdwyvh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigfzy.top/Article/details/gttibgafbz.html

PHP:  public static function f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtzmxrprdn.html

JS:   static f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllzdfice.html

TS:   static f(): void {}
来源：http://dali.haohaochexian.top/Article/details/gtigdnwvzu.html

Java: static void f() {}
来源：http://dali.aibaodan.cn/Article/details/gthblmjmlj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xziqi.cn/Article/details/gtowtusdqi.html

Ruby: def self.f; end
来源：http://dali.zhongyouzk.top/Article/details/gtxyxjaovg.html

C#:   public static void F() {}
来源：http://dali.yvedp.cn/Article/details/gtbyhrnkzj.html

[G09] 接口 / 抽象类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsmkpaxj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgufenzy.top/Article/details/gtxrcfjwsq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aibaodan.cn/Article/details/gtzxisvmev.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yvedp.cn/Article/details/gtkpbzqwky.html

TS:   interface Shape { area(): number; }
来源：http://dali.sufxvd.cn/Article/details/gtylywcwem.html

Java: interface Shape { double area(); }
来源：http://dali.svipenyu.cn/Article/details/gttdhcgmdl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuanzx.com/Article/details/gtvdwpbxpf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258888.top/Article/details/gtldwfghba.html

C#:   interface IShape { double Area(); }
来源：http://dali.ydzc1.top/Article/details/gtgklquhch.html

[G10] 访问控制
来源：http://dali.redwolf501.top/Article/details/gtdbqkrbka.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gotoacloud.top/Article/details/gtujugfsrd.html

PHP:  public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtajlkwntd.html

JS:   #private 字段；其余公开
来源：http://dali.nanxuanxn.top/Article/details/gtaowfzvkg.html

TS:   public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfjaaqrq.html

Java: public / protected / private / 默认包级
来源：http://dali.svipenyu.cn/Article/details/gtnspqzqlu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258.top/Article/details/gtjydzlrel.html

Ruby: public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gtphumbjay.html

C#:   public / protected / private / internal
来源：http://dali.sufxvd.cn/Article/details/gtkppndwee.html

[G11] getter / setter
来源：http://dali.iojbl.cn/Article/details/gtlcoajekr.html

Py:   @property 与 @x.setter
来源：http://dali.cashguo.top/Article/details/gtgipadtvi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtbjvvqlfx.html

JS:   get name() { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gtrqgyqeme.html

TS:   get name(): string { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gtgisukkdt.html

Java: public String getName() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtbfujamqy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtfzvjjukf.html

Ruby: attr_accessor :name
来源：http://dali.sweek.top/Article/details/gtozkuckzo.html

C#:   public string Name { get; set; }
来源：http://dali.fengsongda.top/Article/details/gtwcqgfiql.html

[G12] 对象转字符串
来源：http://dali.shuidangran.top/Article/details/gtvrzlswrx.html

Py:   def __str__(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gtpshxcfna.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtdvvweahw.html

JS:   toString() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gttsvivnmd.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtuumoyjoi.html

Java: @Override public String toString() { return name; }
来源：http://dali.pycfn.com/Article/details/gtaoxuzxpq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gtqbnyowkh.html

Ruby: def to_s; @name; end
来源：http://dali.redwolf501.top/Article/details/gtyiphajjr.html

C#:   public override string ToString() => Name;
来源：http://dali.cqqwz.cn/Article/details/gtimxhkbfu.html

[G13] 判断对象类型
来源：http://dali.vqdsnc.cn/Article/details/gtppzpznuc.html

Py:   isinstance(u, User)
来源：http://dali.yueranfly.top/Article/details/gtwhpngcjq.html

PHP:  $u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gttqremooa.html

JS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gtfhkvxhgs.html

TS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoppishpd.html

Java: u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtculxesib.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yangfankeji.com/Article/details/gtvymhfbot.html

Ruby: u.is_a?(User)
来源：http://dali.zhoulong.xyz/Article/details/gtriuuxkxm.html

C#:   u is User
来源：http://dali.hammf.cn/Article/details/gtndrdrhme.html

[G14] 数据类 / record
来源：http://dali.nanxuanxn.top/Article/details/gtczncvanq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.andypj.xyz/Article/details/gtfswakxxj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sufxvd.cn/Article/details/gtwhvvqjhy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nanxinkj.top/Article/details/gtxmnaimsi.html


<!-- 参考信息 -->