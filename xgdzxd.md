代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.316326.xyz/Article/details/gtvvmdeqgl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.havefunace.top/Article/details/gthnpokrtp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.meibo888.top/Article/details/gtcftjxsel.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhixingplan.top/Article/details/gtwlwoihrs.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.guowangkeji.top/Article/details/gthpkfeuul.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jyoumei.cn/Article/details/gttchndxfb.html

[E16] 数字千分位
来源：http://dali.hnxiangtu.top/Article/details/gtasdnsccj.html

Py:   f"{1234567:,}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiurpmrcg.html

PHP:  number_format(1234567);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnhnehbbo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.birdmap.top/Article/details/gtdpytwknz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zdqjudy.top/Article/details/gtmrrvggse.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtikxprm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guowangkeji.top/Article/details/gttmwralqw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tian-w.cn/Article/details/gtagrinzvt.html

C#:   1234567.ToString("N0")
来源：http://dali.jinqigfzy.top/Article/details/gtgzcnjrll.html

[E17] 首字母大写
来源：http://dali.wangdashe.top/Article/details/gtstrkzrfp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ydzc1.top/Article/details/gttmjqtfyi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.redwolf501.top/Article/details/gtnpsaremv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gogol.net.cn/Article/details/gtmpcphpbp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gtaxrerura.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.9152youxi.cn/Article/details/gtkbqmgvdz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hywenlv.cn/Article/details/gthcpujiuy.html

Ruby: s.capitalize
来源：http://dali.birdmap.top/Article/details/gtamkggokc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.pengpengdd.cyou/Article/details/gthxbzyvac.html

[E18] 模板占位符替换
来源：http://dali.gaohongyu789.top/Article/details/gttnadecqv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvntaoyjj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.birdmap.top/Article/details/gtyyjiiwjg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gtlluxrrtp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtowlzxinl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtpclfyoad.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtqmghwnor.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yvedp.cn/Article/details/gtjmofdvcb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhqejrpv.html

[E19] 多行文本按行拆分
来源：http://dali.ydzc1.top/Article/details/gtvyjbhpqm.html

Py:   s.splitlines()
来源：http://dali.andypj.xyz/Article/details/gtdfxrtfjc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj202588.top/Article/details/gtuzmbveph.html

JS:   s.split(/\r?\n/)
来源：http://dali.svipenyu.cn/Article/details/gtwzrlymdl.html

TS:   s.split(/\r?\n/)
来源：http://dali.svipenyu.cn/Article/details/gttklhosfn.html

Java: s.lines().toList()
来源：http://dali.jiagoushi.top/Article/details/gtguvfsaeu.html

Go:   strings.Split(s, "\n")
来源：http://dali.fzhhl.top/Article/details/gtnmcuvynt.html

Ruby: s.lines
来源：http://dali.jyoumei.cn/Article/details/gtmfgvbhbp.html

C#:   s.Split('\n')
来源：http://dali.tanke756.top/Article/details/gtcteuzuie.html

[E20] 判断字符串是否为空
来源：http://dali.shanyushiyangtech.top/Article/details/gtojkxxisb.html

Py:   if not s:
来源：http://dali.hfpthk.cn/Article/details/gtrvkikobe.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhaomingkeji.xyz/Article/details/gtobjopbqu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.bjfxy.top/Article/details/gthjgbiuwc.html

TS:   if (s === "") {}
来源：http://dali.chenzaomai.com/Article/details/gttzqlfmts.html

Java: if (s.isEmpty()) {}
来源：http://dali.sufxvd.cn/Article/details/gtyiwzyzja.html

Go:   if s == "" {}
来源：http://dali.jqgufenzy.top/Article/details/gtwsvvyowq.html

Ruby: if s.empty?
来源：http://dali.smart0.xyz/Article/details/gtosrkfrok.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.havefunace.top/Article/details/gtgbrcaddv.html

[E21] 超长截断加省略号
来源：http://dali.nwbrower.top/Article/details/gtqowkvzsl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ydzc1.top/Article/details/gtzzvbmikk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gtqwqwqryb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtcmrqdvly.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gthsmjpvvi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtytjszrot.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenzaomai.com/Article/details/gtaoogcaei.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtrilyymhu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj20258.top/Article/details/gtzqwxawwt.html

[E22] 字节长度与字符长度
来源：http://dali.gzhubu.top/Article/details/gtmnrvndvh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sxryk.cn/Article/details/gtmlbackqw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtoaeijffz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cashguo.top/Article/details/gtplfncjro.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtivpsfhzz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hfpthk.cn/Article/details/gtsazzhjox.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.feifeiyinyue.top/Article/details/gtdhfoitnq.html

Ruby: s.bytesize;  s.length
来源：http://dali.zycfv.cn/Article/details/gtxisruyla.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenlongwang.top/Article/details/gtjlhcofgx.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtpdshbhem.html

F. 文件与目录
来源：http://dali.hnxiangtu.top/Article/details/gtmsrbgxkr.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gthaiqdyam.html

[F01] 读取整个文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtrwbfqayl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xuanzx.com/Article/details/gtconvcbwx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtblvxpnve.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.c1oappe.top/Article/details/gtmjztyznc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.c1oappe.top/Article/details/gtjukpkzqq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtaocxmilm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cucudq.cn/Article/details/gtrsrwulmm.html

Ruby: File.read("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtcadqguao.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj20258.top/Article/details/gtkiitqopk.html

[F02] 逐行读取文件
来源：http://dali.cdnleiting.top/Article/details/gtgxfrvrcq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gzhubu.top/Article/details/gtwdilyzqr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gzhubu.top/Article/details/gtpeqxinlh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtlgydimyl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jlsjyb.cn/Article/details/gtqbqjkcme.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhiwuduotai.top/Article/details/gttnupkasc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sufxvd.cn/Article/details/gtdbzdwjly.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shzxlz.cn/Article/details/gtcijpzeeu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shuidangran.top/Article/details/gtcxiopmyz.html

[F03] 写入文件（覆盖）
来源：http://dali.fzhhl.top/Article/details/gtktdkscpw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.wangshuangyany.cn/Article/details/gtiazzvvoj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xylfe.cn/Article/details/gtvpllqiin.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gtxapopnxr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gtiimcepec.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenjidiqi.icu/Article/details/gtsdeddgop.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigufen.top/Article/details/gtyqlxarzn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nwbrower.top/Article/details/gtusbmkofy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gtzujncyps.html

[F04] 追加写入文件
来源：http://dali.jianghu66.top/Article/details/gtclcgsimq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtdmfbvblb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.fzhhl.top/Article/details/gtiqaughty.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.svipenyu.cn/Article/details/gtiunzggsr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gtswugixre.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.fzhhl.top/Article/details/gtjedjwvdj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sweek.top/Article/details/gtkljfeqzv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tanke756.top/Article/details/gtdknaojyn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sufxvd.cn/Article/details/gtuseymemf.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtduqpfqoi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zycfv.cn/Article/details/gtwskxvmfi.html

PHP:  file_exists("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtahknortx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gthixmwdki.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtnbxczvwf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtnhiffevt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gogol.net.cn/Article/details/gtvjglpzrs.html

Ruby: File.exist?("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtlgcwsdqy.html

C#:   File.Exists("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtgoyipmkf.html

[F06] 删除文件
来源：http://dali.yj20258888.top/Article/details/gtaaixfsov.html

Py:   os.remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtxneqpsat.html

PHP:  unlink("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtgebwxibe.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtlugtiqwo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtbwlgpzau.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtmrnvxbqu.html

Go:   os.Remove("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtzcdkkzpi.html

Ruby: File.delete("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gthoorjxxv.html

C#:   File.Delete("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtipaxujft.html

[F07] 创建目录（含多级）
来源：http://dali.pengpengdd.cyou/Article/details/gtolyatzeu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hfpthk.cn/Article/details/gtzufhrrwl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cheryme.top/Article/details/gtiynjgnal.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gtqlcwwycm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pengpengdd.cyou/Article/details/gtdstijxdb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gthpfkagvk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gotoacloud.top/Article/details/gtkxapqmzs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daxiang520.top/Article/details/gtpyrdtnem.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgufenzy.top/Article/details/gtvhhhhimw.html

[F08] 遍历目录
来源：http://dali.zhongyouzk.top/Article/details/gtmsqdnfil.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gaohongyu789.top/Article/details/gtgzbsexzv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guowangkeji.top/Article/details/gtjrktnslb.html

JS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gtzddxmwdp.html

TS:   fs.readdirSync("dir")
来源：http://dali.aibaodan.cn/Article/details/gtlrrwqjyo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.snrcjt.cn/Article/details/gtlggndmhm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.aibaodan.cn/Article/details/gtseupjcig.html

Ruby: Dir.children("dir")
来源：http://dali.meibo888.top/Article/details/gtxsugxhud.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ppjwa.cn/Article/details/gtainttblq.html

[F09] 获取文件大小
来源：http://dali.cheryme.top/Article/details/gtzgsqtfhc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtmqrnessq.html

PHP:  filesize("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwimabhnc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gtjcnjomla.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cheryme.top/Article/details/gtxzyehzku.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtspcswfys.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jyoumei.cn/Article/details/gtmoiobbci.html

Ruby: File.size("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtciyvfdwl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sufxvd.cn/Article/details/gtccxdayrj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ehwqpu.com/Article/details/gtczlkaref.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtybidjejk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ybcxt.top/Article/details/gtlutebnpc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtlfkxvzoy.html

TS:   path.extname("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtbuslpfyd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nanxinkj.top/Article/details/gtjakunrby.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gttknildcg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtfytmsctq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtysrqtuqn.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gtmpocvrny.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtejkaefpn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sxryk.cn/Article/details/gtzpapvtxx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtuaipdvsl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtliwhujdh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.wangdashe.top/Article/details/gtdrveiqzk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.0kj1m.cn/Article/details/gtzzptpnba.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtfyzlwocl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tianlin.xyz/Article/details/gtgfpyuamo.html

[F12] CSV 读写
来源：http://dali.jqgufenzy.top/Article/details/gtlszlmrqd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.fengsongda.top/Article/details/gteyreegbx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinqigufen.top/Article/details/gtuofkwbap.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gaohongyu789.top/Article/details/gtgqlyesnl.html

TS:   // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gtimddswmv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hammf.cn/Article/details/gtazuowpjk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenjidiqi.icu/Article/details/gtoaadlmse.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xinyue.icu/Article/details/gtfyzbizdd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cqqwz.cn/Article/details/gtrpovhksc.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtlgphdxao.html

G. 面向对象
来源：http://dali.haohaochexian.top/Article/details/gtbsfiwvby.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtiglrxzbr.html

[G01] 定义类
来源：http://dali.yuanzhike.top/Article/details/gtzqdohmkn.html

Py:   class User: pass
来源：http://dali.iojbl.cn/Article/details/gtewbefzqh.html

PHP:  class User {}
来源：http://dali.chenlongwang.top/Article/details/gtkknivhei.html

JS:   class User {}
来源：http://dali.zycfv.cn/Article/details/gtwdgknrmv.html

TS:   class User { name: string = ""; }
来源：http://dali.jqgufenzy.top/Article/details/gtaswzagsq.html

Java: class User {}
来源：http://dali.nanxinkj.top/Article/details/gtuokobnis.html

Go:   type User struct { Name string }
来源：http://dali.dianchejie.cn/Article/details/gtvizwdjnb.html

Ruby: class User; end
来源：http://dali.aibaodan.cn/Article/details/gtmchedueb.html

C#:   class User {}
来源：http://dali.yueranfly.top/Article/details/gtuiekydbw.html

[G02] 构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtckkzmhnq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.iojbl.cn/Article/details/gtdpmlhxzz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.bjfxy.top/Article/details/gttmpyqbde.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yvedp.cn/Article/details/gtgyrbqbpt.html

TS:   constructor(public name: string) {}
来源：http://dali.jiagoushi.top/Article/details/gtymetfoal.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgmncfgzb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gtkgtcwwny.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.svipenyu.cn/Article/details/gtojymaphk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.birdmap.top/Article/details/gtlpdljftu.html

[G03] 实例属性
来源：http://dali.chenzaomai.com/Article/details/gtomzuijpv.html

Py:   self.name = "x"
来源：http://dali.bjfxy.top/Article/details/gtnbjhests.html

PHP:  public string $name = "x";
来源：http://dali.shuidangran.top/Article/details/gttejdzlfa.html

JS:   this.name = "x";
来源：http://dali.ybcxt.top/Article/details/gtepbkwfis.html

TS:   name: string = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtvzvoadzs.html

Java: private String name;
来源：http://dali.ivvv.top/Article/details/gttfhxsxvl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenzaomai.com/Article/details/gtjozfttuw.html

Ruby: @name = "x"
来源：http://dali.nanxinkj.top/Article/details/gtjamgbzsg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtssnkjcqy.html

[G04] 定义方法
来源：http://dali.hywenlv.cn/Article/details/gtebrhuyox.html

Py:   def greet(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gtpegrqdjn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtbxjwxetn.html

JS:   greet() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtbpgoqnjr.html

TS:   greet(): string { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtzwchgcrn.html

Java: String greet() { return name; }
来源：http://dali.redwolf501.top/Article/details/gtmdjcfypj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gteccepamu.html

Ruby: def greet; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gtwedomzmc.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gtbyckiqfj.html

[G05] 继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhswfdup.html

Py:   class Admin(User): pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqijkibhq.html

PHP:  class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtcpvgyehq.html

JS:   class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtqnzjkprw.html

TS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtrkgugket.html

Java: class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gtxcvixsrn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.c1oappe.top/Article/details/gtikmjcmzw.html

Ruby: class Admin < User; end
来源：http://dali.c1oappe.top/Article/details/gtydipsfac.html

C#:   class Admin : User {}
来源：http://dali.yvedp.cn/Article/details/gttgqxdrxr.html

[G06] 重写方法
来源：http://dali.nanxuanxn.top/Article/details/gtgayyozug.html

Py:   def greet(self): return "admin"
来源：http://dali.fzhhl.top/Article/details/gtdeeivexw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtoslxysvg.html

JS:   greet() { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtrozvrlgl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtfxfagata.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtxrsqzsgy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gtfzlyzvqq.html

Ruby: def greet; "admin"; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwblxnqwm.html

C#:   public override string Greet() => "admin";
来源：http://dali.aibaodan.cn/Article/details/gtokkeckrx.html

[G07] 调用父类方法
来源：http://dali.wangshuangyany.cn/Article/details/gtofbmitol.html

Py:   super().greet()
来源：http://dali.daria6918.cn/Article/details/gtjtlltghc.html

PHP:  parent::greet();
来源：http://dali.jyoumei.cn/Article/details/gtjqntdqfn.html

JS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtvhdikymi.html

TS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gtvelagrqc.html

Java: super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtcztuxwxp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jlsjyb.cn/Article/details/gtngpmblti.html

Ruby: super
来源：http://dali.pengpengdd.cyou/Article/details/gtkgjmkbua.html

C#:   base.Greet();
来源：http://dali.redwolf501.top/Article/details/gtkgbmokvk.html

[G08] 静态方法与属性
来源：http://dali.yongpay.top/Article/details/gtmxkqodwq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tianlin.xyz/Article/details/gtvzdnvwyv.html

PHP:  public static function f() {}
来源：http://dali.zdqjudy.top/Article/details/gttowjjtpi.html

JS:   static f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtgxdussip.html

TS:   static f(): void {}
来源：http://dali.nanxinkj.top/Article/details/gtvkrzihko.html

Java: static void f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtntzelorp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhixxmhk.html

Ruby: def self.f; end
来源：http://dali.snrcjt.cn/Article/details/gtilzytfhk.html

C#:   public static void F() {}
来源：http://dali.redwolf501.top/Article/details/gtoccbwqgl.html

[G09] 接口 / 抽象类
来源：http://dali.jyoumei.cn/Article/details/gtkvdchlaw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.dashuyun.cn/Article/details/gtixsdrapv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.c1oappe.top/Article/details/gtksvkpyhl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.kuanghao11.cn/Article/details/gtwhmpoxog.html

TS:   interface Shape { area(): number; }
来源：http://dali.sxryk.cn/Article/details/gtkssmqqio.html

Java: interface Shape { double area(); }
来源：http://dali.snrcjt.cn/Article/details/gtikvrwxmo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hongshengwenyu.top/Article/details/gtninwyvct.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangdashe.top/Article/details/gtuwuwxjsk.html

C#:   interface IShape { double Area(); }
来源：http://dali.snrcjt.cn/Article/details/gtmjqyqlis.html

[G10] 访问控制
来源：http://dali.ehwqpu.com/Article/details/gtmvdvwzwu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cqqwz.cn/Article/details/gtmciczcez.html

PHP:  public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gthvdpezuk.html

JS:   #private 字段；其余公开
来源：http://dali.quarkkingdee.top/Article/details/gtobqrrffd.html

TS:   public / protected / private
来源：http://dali.cucudq.cn/Article/details/gtjumykesx.html

Java: public / protected / private / 默认包级
来源：http://dali.0kj1m.cn/Article/details/gtdgwpekoy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuetiantiany.cn/Article/details/gtrnylfljb.html

Ruby: public / protected / private
来源：http://dali.meibo888.top/Article/details/gtkxellffb.html

C#:   public / protected / private / internal
来源：http://dali.c1oappe.top/Article/details/gtjmhvnkoj.html

[G11] getter / setter
来源：http://dali.andypj.xyz/Article/details/gtdvtplblx.html

Py:   @property 与 @x.setter
来源：http://dali.yongpay.top/Article/details/gtjbdlrqrp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gtqgdykdyv.html

JS:   get name() { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gtbiuokxcn.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtrkbbypnw.html

Java: public String getName() { return name; }
来源：http://dali.daria6918.cn/Article/details/gtxmmvzmfs.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtdladarmw.html

Ruby: attr_accessor :name
来源：http://dali.aizwys.cn/Article/details/gtxvuolfgm.html

C#:   public string Name { get; set; }
来源：http://dali.wangdashe.top/Article/details/gtonfjvteg.html

[G12] 对象转字符串
来源：http://dali.fzhhl.top/Article/details/gtdjxcgtti.html

Py:   def __str__(self): return self.name
来源：http://dali.yonumen.top/Article/details/gtqpbjyxkx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtofbkfebx.html

JS:   toString() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gtdgjbmtfy.html

TS:   toString(): string { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtjwyasqiw.html

Java: @Override public String toString() { return name; }
来源：http://dali.meibo888.top/Article/details/gtudujlixy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtwspvwqhh.html

Ruby: def to_s; @name; end
来源：http://dali.guowangkeji.top/Article/details/gtgvrtchsv.html

C#:   public override string ToString() => Name;
来源：http://dali.ppjwa.cn/Article/details/gtwxwchzxd.html

[G13] 判断对象类型
来源：http://dali.xylfe.cn/Article/details/gtviqqkczp.html

Py:   isinstance(u, User)
来源：http://dali.ydzc1.top/Article/details/gtstefvweh.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtjzpejuef.html

JS:   u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gtkzqostjm.html

TS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtwyycjcdl.html

Java: u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtqomymsug.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pengpengdd.cyou/Article/details/gtgnqgmjik.html

Ruby: u.is_a?(User)
来源：http://dali.hongshengwenyu.top/Article/details/gtmcqtgvin.html

C#:   u is User
来源：http://dali.smart0.xyz/Article/details/gtlwgpkzcg.html


<!-- 参考信息 -->