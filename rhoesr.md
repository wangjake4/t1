代发 wailian999

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jiagoushi.top/Article/details/gt2yxtvjvla.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.daria6918.cn/Article/details/gt2aruyuzcq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ralytbom.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cdnleiting.top/Article/details/gt2aztkrgbg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenzaomai.com/Article/details/gt2bniutclp.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgufenzy.top/Article/details/gt2feptpykh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zdqjudy.top/Article/details/gt2pucufhrc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2ppnwwswh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xuanzx.com/Article/details/gt2crfhrxjy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.feifeiyinyue.top/Article/details/gt2gxqfkfug.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lcsppdxt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daxiang520.top/Article/details/gt2deaicfhb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nwbrower.top/Article/details/gt2ykzzykav.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangdashe.top/Article/details/gt2eyhlvdvw.html

[E16] 数字千分位
来源：http://dali.jiagoushi.top/Article/details/gt2hxdmntfn.html

Py:   f"{1234567:,}"
来源：http://dali.0kj1m.cn/Article/details/gt2ualhhjfa.html

PHP:  number_format(1234567);
来源：http://dali.jinqigfzy.top/Article/details/gt2lgyhyozm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tanke756.top/Article/details/gt2cfnjekit.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258888.top/Article/details/gt2obuqjiki.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xziqi.cn/Article/details/gt2hlmeckbw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yanxiufei.cn/Article/details/gt2ancocysl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhiwuduotai.top/Article/details/gt2swwzhqfw.html

C#:   1234567.ToString("N0")
来源：http://dali.mhx1999.top/Article/details/gt2wxqvlvef.html

[E17] 首字母大写
来源：http://dali.ybcxt.top/Article/details/gt2usndfnuq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cdnleiting.top/Article/details/gt2fujkybst.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2lqkijawg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gotoacloud.top/Article/details/gt2zdyrmeup.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dashuyun.cn/Article/details/gt2szvcvuvx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2lyjqfxhd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zdqjudy.top/Article/details/gt2gidtwcnr.html

Ruby: s.capitalize
来源：http://dali.hnxiangtu.top/Article/details/gt2upccfmtt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hysaishi.cn/Article/details/gt2pfjnzyhb.html

[E18] 模板占位符替换
来源：http://dali.vqdsnc.cn/Article/details/gt2gnuieteb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xuanzx.com/Article/details/gt2ffsltlgb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sufxvd.cn/Article/details/gt2yimplapi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gt2qcnpzftx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gt2jlmatesi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gt2trbbfkhg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hetxzsuj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shzxlz.cn/Article/details/gt2uxeomcts.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ydzc1.top/Article/details/gt2rfgmztgn.html

[E19] 多行文本按行拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wexikflo.html

Py:   s.splitlines()
来源：http://dali.sysykeji.top/Article/details/gt2swswhrvo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangdashe.top/Article/details/gt2vzdwghah.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinqigufen.top/Article/details/gt2nrgjlfjb.html

TS:   s.split(/\r?\n/)
来源：http://dali.tianlin.xyz/Article/details/gt2uytmpmoj.html

Java: s.lines().toList()
来源：http://dali.tian-w.cn/Article/details/gt2sqiyigaj.html

Go:   strings.Split(s, "\n")
来源：http://dali.xinyue.icu/Article/details/gt2pwtwtvjf.html

Ruby: s.lines
来源：http://dali.iojbl.cn/Article/details/gt2mafkgzzj.html

C#:   s.Split('\n')
来源：http://dali.gaohongyu789.top/Article/details/gt2jhhthwti.html

[E20] 判断字符串是否为空
来源：http://dali.cdnleiting.top/Article/details/gt2wohbkuzp.html

Py:   if not s:
来源：http://dali.tianlin.xyz/Article/details/gt2gbfqbpkr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cheryme.top/Article/details/gt2ynmzzinc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhengqikj.top/Article/details/gt2hltbgnna.html

TS:   if (s === "") {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lxuehiim.html

Java: if (s.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gt2geysosjs.html

Go:   if s == "" {}
来源：http://dali.cdnleiting.top/Article/details/gt2eobznbtn.html

Ruby: if s.empty?
来源：http://dali.daxiang520.top/Article/details/gt2kxbrzinq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shzxlz.cn/Article/details/gt2dsonoiyx.html

[E21] 超长截断加省略号
来源：http://dali.wangdashe.top/Article/details/gt2ymxmoavb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xylfe.cn/Article/details/gt2gddysfia.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gt2cdmpjejb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gt2rtadhblh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gt2vhaipcnn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gt2pzawcbcf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sxryk.cn/Article/details/gt2syjtylxq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gt2viqhbmoq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gt2zhubkviv.html

[E22] 字节长度与字符长度
来源：http://dali.zdqjudy.top/Article/details/gt2bbwmsmgs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.mhx1999.top/Article/details/gt2tzogvsve.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gt2zqagpqcr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gzhubu.top/Article/details/gt2tbumeslj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gt2pfcyfjae.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hammf.cn/Article/details/gt2plfbttey.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhiwuduotai.top/Article/details/gt2qbjqdwic.html

Ruby: s.bytesize;  s.length
来源：http://dali.andypj.xyz/Article/details/gt2glprienu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sweek.top/Article/details/gt2zbngzlap.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ilknvrmc.html

F. 文件与目录
来源：http://dali.snrcjt.cn/Article/details/gt2garuycbz.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2hdkinkhp.html

[F01] 读取整个文件
来源：http://dali.316326.xyz/Article/details/gt2npabyvwy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yvedp.cn/Article/details/gt2kuvjqxjm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2rfukikyr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qhfsrsyb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nwbrower.top/Article/details/gt2gobwlrpw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gt2txunpxev.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.guowangkeji.top/Article/details/gt2xcijkqqt.html

Ruby: File.read("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2mdmibilx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2zklbdsnh.html

[F02] 逐行读取文件
来源：http://dali.jiagoushi.top/Article/details/gt2ozxkyhsh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pzxjyfxs.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zycfv.cn/Article/details/gt2pbfeegwr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.haohaochexian.top/Article/details/gt2uddpxvym.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gt2hpgttnzd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ydzc1.top/Article/details/gt2nktncdan.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.kuanghao11.cn/Article/details/gt2jxqdihis.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tanke756.top/Article/details/gt2lizdbbnf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daria6918.cn/Article/details/gt2couctjur.html

[F03] 写入文件（覆盖）
来源：http://dali.xziqi.cn/Article/details/gt2sircicfk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cqqwz.cn/Article/details/gt2qpodxoje.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yanxiufei.cn/Article/details/gt2qjifbrhp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gt2myfjqhol.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gt2pdaqerut.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.redwolf501.top/Article/details/gt2ptctpqhe.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jianghu66.top/Article/details/gt2hkytrkdj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenlongwang.top/Article/details/gt2motbvwmf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gt2jpachuoi.html

[F04] 追加写入文件
来源：http://dali.sxryk.cn/Article/details/gt2vovtmtdh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jqgufenzy.top/Article/details/gt2tbkgtlla.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ivvv.top/Article/details/gt2gspedgph.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gt2vhoogbbw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zdqjudy.top/Article/details/gt2qqknscnd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.havefunace.top/Article/details/gt2xywfugqo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ydzc1.top/Article/details/gt2pdgfobiv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ehwqpu.com/Article/details/gt2poxowhli.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.smart0.xyz/Article/details/gt2kkiakrzc.html

[F05] 判断文件或目录是否存在
来源：http://dali.yangfankeji.com/Article/details/gt2ehgwoddp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ivvv.top/Article/details/gt2bqfokcqb.html

PHP:  file_exists("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2pldrxkob.html

JS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2xvjhgphm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2bmcflgin.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gt2myubpvwe.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.c1oappe.top/Article/details/gt2gpbdktvu.html

Ruby: File.exist?("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2igvtgvcj.html

C#:   File.Exists("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2wmhhwdqc.html

[F06] 删除文件
来源：http://dali.sweek.top/Article/details/gt2fpcrmthq.html

Py:   os.remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2ijomjfhm.html

PHP:  unlink("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2eftaebwc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2jszezzck.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2tbsvcutk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gt2vlvgqdiy.html

Go:   os.Remove("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2thveaawo.html

Ruby: File.delete("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2wpjpwoek.html

C#:   File.Delete("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2rmfdvofz.html

[F07] 创建目录（含多级）
来源：http://dali.wangdashe.top/Article/details/gt2nzdbstrw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sxryk.cn/Article/details/gt2shztopsh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.andypj.xyz/Article/details/gt2xtscwldn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenzaomai.com/Article/details/gt2fitatzpt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.0kj1m.cn/Article/details/gt2tazzrmaw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.redwolf501.top/Article/details/gt2ithsdofy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.316326.xyz/Article/details/gt2rqbmiekv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xziqi.cn/Article/details/gt2fbdxdmsz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ehwqpu.com/Article/details/gt2crbsuepm.html

[F08] 遍历目录
来源：http://dali.xinyue.icu/Article/details/gt2mtqsutwb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nanxinkj.top/Article/details/gt2gdyylasu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oirlgaho.html

JS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hbzwajpl.html

TS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gt2dtryscdz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xinyue.icu/Article/details/gt2aczvfcti.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dianchejie.cn/Article/details/gt2avaowraw.html

Ruby: Dir.children("dir")
来源：http://dali.nanxuanxn.top/Article/details/gt2cmsrwfbo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.316326.xyz/Article/details/gt2yusggqjk.html

[F09] 获取文件大小
来源：http://dali.daxiang520.top/Article/details/gt2znncgsqe.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2xrvftmyk.html

PHP:  filesize("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2tonbgtqa.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gt2bogrkbpa.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qqndmxip.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gt2drvlhvmk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xuetiantiany.cn/Article/details/gt2onlroeum.html

Ruby: File.size("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2iglkcfrj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sufxvd.cn/Article/details/gt2fbnqxazf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xylfe.cn/Article/details/gt2pkrnwxic.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gt2bszdmvrb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2qfcmmbbv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2kisnegmx.html

TS:   path.extname("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2wcdmcvqd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhengqikj.top/Article/details/gt2cdmyqdka.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2xvalflhe.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2xjaleiqx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2strmfiyw.html

[F11] 复制与移动文件
来源：http://dali.c1oappe.top/Article/details/gt2flxjdasg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gt2pkmwziyc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2avmxkbzz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2zxllvcrh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hcjojwwm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.havefunace.top/Article/details/gt2xqkquhfw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cashguo.top/Article/details/gt2gnhmwlnq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gt2vzzbtebh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.feifeiyinyue.top/Article/details/gt2kvuaepdg.html

[F12] CSV 读写
来源：http://dali.andypj.xyz/Article/details/gt2mujiihxt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tianlin.xyz/Article/details/gt2rxzmhqsd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sufxvd.cn/Article/details/gt2mnjznkvk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sufxvd.cn/Article/details/gt2csarstjd.html

TS:   // 同上
来源：http://dali.jqgfzy.top/Article/details/gt2douoeavg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hywenlv.cn/Article/details/gt2dhhbagzx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xinyue.icu/Article/details/gt2zffujhmj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sysykeji.top/Article/details/gt2tfyejnzd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.pycfn.com/Article/details/gt2esvkrihj.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2fnocyvhg.html

G. 面向对象
来源：http://dali.jinqigfzy.top/Article/details/gt2jaanllfs.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2oivtwlyy.html

[G01] 定义类
来源：http://dali.nanxinkj.top/Article/details/gt2eooxfqxg.html

Py:   class User: pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fawhglhk.html

PHP:  class User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2ctwpojjc.html

JS:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gt2bldgqmgi.html

TS:   class User { name: string = ""; }
来源：http://dali.yanxiufei.cn/Article/details/gt2szqbgxgp.html

Java: class User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2opqseivh.html

Go:   type User struct { Name string }
来源：http://dali.shuidangran.top/Article/details/gt2wflclidw.html

Ruby: class User; end
来源：http://dali.nwbrower.top/Article/details/gt2izjtnpbe.html

C#:   class User {}
来源：http://dali.cqqwz.cn/Article/details/gt2bvpphlfg.html

[G02] 构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2clrgcaee.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yarabodp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bossnuhn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ynaabccb.html

TS:   constructor(public name: string) {}
来源：http://dali.cdnleiting.top/Article/details/gt2vmyevmqs.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2gjcvmazj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gzhubu.top/Article/details/gt2vypysmsm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aizwys.cn/Article/details/gt2vcunrnel.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gogol.net.cn/Article/details/gt2zteevlou.html

[G03] 实例属性
来源：http://dali.pengpengdd.cyou/Article/details/gt2bhokbzjm.html

Py:   self.name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gt2grscemna.html

PHP:  public string $name = "x";
来源：http://dali.zycfv.cn/Article/details/gt2lrhpugxo.html

JS:   this.name = "x";
来源：http://dali.zycfv.cn/Article/details/gt2dvqarreu.html

TS:   name: string = "x";
来源：http://dali.smart0.xyz/Article/details/gt2ixbofrgq.html

Java: private String name;
来源：http://dali.yj202588.top/Article/details/gt2wukurzkd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yvedp.cn/Article/details/gt2ocmpbmww.html

Ruby: @name = "x"
来源：http://dali.fzhhl.top/Article/details/gt2ofyezgkh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jianghu66.top/Article/details/gt2kclnbzrj.html

[G04] 定义方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nuxlqylo.html

Py:   def greet(self): return self.name
来源：http://dali.iojbl.cn/Article/details/gt2pqymhwpi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gt2tsebkrgz.html

JS:   greet() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gt2pksebqju.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2georigdr.html

Java: String greet() { return name; }
来源：http://dali.mhx1999.top/Article/details/gt2poanabov.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gt2kphjlile.html

Ruby: def greet; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gt2iezdjtra.html

C#:   public string Greet() => Name;
来源：http://dali.yj202588.top/Article/details/gt2armytfxe.html

[G05] 继承
来源：http://dali.snrcjt.cn/Article/details/gt2pslkiyvh.html

Py:   class Admin(User): pass
来源：http://dali.guannengcc.top/Article/details/gt2glgwpjcc.html

PHP:  class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2ohgsbboz.html

JS:   class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gt2emekcokp.html

TS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gt2igrqoahb.html

Java: class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gt2vsqhirnf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangtech.top/Article/details/gt2emyjtcxv.html

Ruby: class Admin < User; end
来源：http://dali.iojbl.cn/Article/details/gt2rihxnqnf.html

C#:   class Admin : User {}
来源：http://dali.tianlin.xyz/Article/details/gt2voksphfe.html

[G06] 重写方法
来源：http://dali.mhx1999.top/Article/details/gt2yfmaqfxg.html

Py:   def greet(self): return "admin"
来源：http://dali.chenzaomai.com/Article/details/gt2pznkqluo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2asejzqrk.html

JS:   greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gt2xxriquip.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2mqffthad.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gt2mpnfqkdz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xziqi.cn/Article/details/gt2xrevdqyx.html

Ruby: def greet; "admin"; end
来源：http://dali.vqdsnc.cn/Article/details/gt2vfaorxis.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhengqikj.top/Article/details/gt2aecjrcid.html

[G07] 调用父类方法
来源：http://dali.xuetiantiany.cn/Article/details/gt2xrrlklri.html

Py:   super().greet()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rvuknhbc.html

PHP:  parent::greet();
来源：http://dali.zhixingplan.top/Article/details/gt2eckerzsu.html

JS:   super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gt2gsfreiad.html

TS:   super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gt2rgulsctd.html

Java: super.greet();
来源：http://dali.yongpay.top/Article/details/gt2iptasqyb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yanxiufei.cn/Article/details/gt2jfupzgnc.html

Ruby: super
来源：http://dali.xuanzx.com/Article/details/gt2itgppnmv.html

C#:   base.Greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2slsmmotl.html

[G08] 静态方法与属性
来源：http://dali.ivvv.top/Article/details/gt2dqgozneg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cheryme.top/Article/details/gt2aheqmqhz.html

PHP:  public static function f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ftkxgvaz.html

JS:   static f() {}
来源：http://dali.zhoulong.xyz/Article/details/gt2oxgzxjhf.html

TS:   static f(): void {}
来源：http://dali.zhongyouzk.top/Article/details/gt2iqpdmofy.html

Java: static void f() {}
来源：http://dali.redwolf501.top/Article/details/gt2eyrpmxfn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zdqjudy.top/Article/details/gt2zffzfgwp.html

Ruby: def self.f; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zvuikxwr.html

C#:   public static void F() {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2jsexylnv.html

[G09] 接口 / 抽象类
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ojbstepw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gzhubu.top/Article/details/gt2wphegewx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zycfv.cn/Article/details/gt2hblxtabk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sysykeji.top/Article/details/gt2pkjqyakr.html

TS:   interface Shape { area(): number; }
来源：http://dali.aizwys.cn/Article/details/gt2byjhkwmj.html

Java: interface Shape { double area(); }
来源：http://dali.tian-w.cn/Article/details/gt2ynqffzqh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sysykeji.top/Article/details/gt2nxgyrrjb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aibaodan.cn/Article/details/gt2bhyhxlkv.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2hflilrhp.html

[G10] 访问控制
来源：http://dali.hywenlv.cn/Article/details/gt2xwyqjelp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sxryk.cn/Article/details/gt2zufoodna.html

PHP:  public / protected / private
来源：http://dali.tanke756.top/Article/details/gt2nhpnvfhl.html

JS:   #private 字段；其余公开
来源：http://dali.yuxming.cn/Article/details/gt2kvwucxfl.html

TS:   public / protected / private
来源：http://dali.mhx1999.top/Article/details/gt2ostzmrdo.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hcknmlqf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hfpthk.cn/Article/details/gt2mudbqqjn.html

Ruby: public / protected / private
来源：http://dali.xziqi.cn/Article/details/gt2ezdysxvq.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uvmgqorp.html

[G11] getter / setter
来源：http://dali.9152youxi.cn/Article/details/gt2efarupgi.html

Py:   @property 与 @x.setter
来源：http://dali.hywenlv.cn/Article/details/gt2jdevgxod.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gt2hezuzlbb.html

JS:   get name() { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gt2cztwkudj.html

TS:   get name(): string { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gt2pmhlyakz.html

Java: public String getName() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gt2yjffdhsc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gt2humwcfyu.html

Ruby: attr_accessor :name
来源：http://dali.redwolf501.top/Article/details/gt2etfhcrmw.html

C#:   public string Name { get; set; }
来源：http://dali.yonumen.top/Article/details/gt2ozcwigog.html

[G12] 对象转字符串
来源：http://dali.pycfn.com/Article/details/gt2wvmatsbe.html

Py:   def __str__(self): return self.name
来源：http://dali.yvedp.cn/Article/details/gt2gkisedvz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gt2mrqlzpqv.html

JS:   toString() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2yjuuzvhg.html

TS:   toString(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gt2zevufcwl.html

Java: @Override public String toString() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gt2cvefstfw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gt2kdkirsqs.html

Ruby: def to_s; @name; end
来源：http://dali.cucudq.cn/Article/details/gt2bgjqxslb.html

C#:   public override string ToString() => Name;
来源：http://dali.cdnleiting.top/Article/details/gt2ynzdalla.html

[G13] 判断对象类型
来源：http://dali.0kj1m.cn/Article/details/gt2pizczhac.html


<!-- 参考信息 -->