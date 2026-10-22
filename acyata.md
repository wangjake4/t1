代发 wailian999

JS:   [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gt2ybocpvkl.html

TS:   [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gt2yhohjcuf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.fzhhl.top/Article/details/gt2ssxubnmu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cqqwz.cn/Article/details/gt2qluasakz.html

Ruby: s.reverse
来源：http://dali.jinqigufen.top/Article/details/gt2yfcznjhw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.mhx1999.top/Article/details/gt2zgfapltl.html

[E12] 统计某字符出现次数
来源：http://dali.zhiwuduotai.top/Article/details/gt2jhzxrjgy.html

Py:   s.count("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gbauiqch.html

PHP:  substr_count($s, "a");
来源：http://dali.snrcjt.cn/Article/details/gt2imghkelp.html

JS:   s.split("a").length - 1
来源：http://dali.zycfv.cn/Article/details/gt2kovmmhny.html

TS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gt2zbppejcc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xuanzx.com/Article/details/gt2wmbgrull.html

Go:   strings.Count(s, "a")
来源：http://dali.meibo888.top/Article/details/gt2yyclwogc.html

Ruby: s.count("a")
来源：http://dali.ydzc1.top/Article/details/gt2ftuhioch.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shzxlz.cn/Article/details/gt2zztexwhx.html

[E13] 逐字符遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2roloanxv.html

Py:   for ch in s: print(ch)
来源：http://dali.vqdsnc.cn/Article/details/gt2mlhucubw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cheryme.top/Article/details/gt2dvbndwfi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gt2vzpmmkql.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yonumen.top/Article/details/gt2vrofydxj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.dianchejie.cn/Article/details/gt2zikrvcgn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ybcxt.top/Article/details/gt2glvghvrs.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zfffomwg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sxryk.cn/Article/details/gt2ikepkcrr.html

[E14] URL 编码与 Base64
来源：http://dali.yanxiufei.cn/Article/details/gt2xqlernui.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wtgsnlzf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2kyvyvqlh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jxvatbzf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jyoumei.cn/Article/details/gt2tihfixfc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aizwys.cn/Article/details/gt2tphzkync.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.316326.xyz/Article/details/gt2zefktfnu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shzxlz.cn/Article/details/gt2cisyrpvg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sufxvd.cn/Article/details/gt2xnmvfrzs.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhengqikj.top/Article/details/gt2bochblyq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2fvjpbldp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhixingplan.top/Article/details/gt2sbqyqrpd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sufxvd.cn/Article/details/gt2cqgkhzbw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yangfankeji.com/Article/details/gt2zcsppikf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sysykeji.top/Article/details/gt2qjrtilqv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.meibo888.top/Article/details/gt2dodahqwq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.daria6918.cn/Article/details/gt2qysvduek.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yj20258.top/Article/details/gt2ddyuokiy.html

[E16] 数字千分位
来源：http://dali.wangshuangyany.cn/Article/details/gt2ektxzual.html

Py:   f"{1234567:,}"
来源：http://dali.tanke756.top/Article/details/gt2utvsulaa.html

PHP:  number_format(1234567);
来源：http://dali.yonumen.top/Article/details/gt2qvnzizaj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sxryk.cn/Article/details/gt2mdsddwrp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yongpay.top/Article/details/gt2rfivzxtg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.quarkkingdee.top/Article/details/gt2qaadthsp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xinyue.icu/Article/details/gt2geqsvewu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nanxuanxn.top/Article/details/gt2vdzocisv.html

C#:   1234567.ToString("N0")
来源：http://dali.tanke756.top/Article/details/gt2medyqalz.html

[E17] 首字母大写
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2niecjasd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nanxuanxn.top/Article/details/gt2xfuimrav.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.mhx1999.top/Article/details/gt2kmojqepn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yonumen.top/Article/details/gt2ejvubepa.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hfpthk.cn/Article/details/gt2fmburrkq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2athkcdtg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinqigfzy.top/Article/details/gt2kqxfqixt.html

Ruby: s.capitalize
来源：http://dali.havefunace.top/Article/details/gt2megawoxg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xziqi.cn/Article/details/gt2vxneuoxj.html

[E18] 模板占位符替换
来源：http://dali.sxryk.cn/Article/details/gt2qicjnvup.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ydzc1.top/Article/details/gt2ldiaetaj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jianghu66.top/Article/details/gt2gstkicoz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gt2ykkffojh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gt2fmxtgjmc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gt2idpffmse.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gt2yvtmnonk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhixingplan.top/Article/details/gt2lgfynrug.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hfpthk.cn/Article/details/gt2fjkjhdit.html

[E19] 多行文本按行拆分
来源：http://dali.chenlongwang.top/Article/details/gt2kxaiiqet.html

Py:   s.splitlines()
来源：http://dali.zhengqikj.top/Article/details/gt2bgxdsbik.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2hjzqiixv.html

JS:   s.split(/\r?\n/)
来源：http://dali.nanxuanxn.top/Article/details/gt2otdfhqcy.html

TS:   s.split(/\r?\n/)
来源：http://dali.dashuyun.cn/Article/details/gt2bdklzruw.html

Java: s.lines().toList()
来源：http://dali.tian-w.cn/Article/details/gt2qjzvqxij.html

Go:   strings.Split(s, "\n")
来源：http://dali.yueranfly.top/Article/details/gt2eeplcwcs.html

Ruby: s.lines
来源：http://dali.zhiwuduotai.top/Article/details/gt2ohlfrrjn.html

C#:   s.Split('\n')
来源：http://dali.xuanzx.com/Article/details/gt2crtkiomq.html

[E20] 判断字符串是否为空
来源：http://dali.sweek.top/Article/details/gt2yttvuiqn.html

Py:   if not s:
来源：http://dali.ybcxt.top/Article/details/gt2mprrdyvf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yangfankeji.com/Article/details/gt2qeipeesk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jyoumei.cn/Article/details/gt2buwsoyrl.html

TS:   if (s === "") {}
来源：http://dali.pycfn.com/Article/details/gt2iwzlplbg.html

Java: if (s.isEmpty()) {}
来源：http://dali.snrcjt.cn/Article/details/gt2lnrpvosz.html

Go:   if s == "" {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2knnpzonx.html

Ruby: if s.empty?
来源：http://dali.aibaodan.cn/Article/details/gt2pmsadhto.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.havefunace.top/Article/details/gt2zqyyypis.html

[E21] 超长截断加省略号
来源：http://dali.yj20258888.top/Article/details/gt2lrzbznyq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gotoacloud.top/Article/details/gt2tpkivufe.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2efykmrbi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gt2pjktighk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2etybqujb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gt2ggflmrog.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jlsjyb.cn/Article/details/gt2edxdhfqz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2xndldkng.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yuxming.cn/Article/details/gt2aoqjxxnp.html

[E22] 字节长度与字符长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fbgqldnk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2aygtvnmd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sweek.top/Article/details/gt2qigehopf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yvedp.cn/Article/details/gt2nqrmbvno.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gt2mgjlwmla.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.bjfxy.top/Article/details/gt2yzluvnfw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.snrcjt.cn/Article/details/gt2admnywhu.html

Ruby: s.bytesize;  s.length
来源：http://dali.yangfankeji.com/Article/details/gt2wkmksouj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guowangkeji.top/Article/details/gt2jlkcoyzo.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2sefdiyox.html

F. 文件与目录
来源：http://dali.nanxuanxn.top/Article/details/gt2xpcnquoq.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2zdjnqmul.html

[F01] 读取整个文件
来源：http://dali.shzxlz.cn/Article/details/gt2ojhdjtfn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.guannengcc.top/Article/details/gt2nmowwrue.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2vwihqrat.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigufen.top/Article/details/gt2bastsmsu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gt2edvonbsb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gt2dhcvgeuu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hywenlv.cn/Article/details/gt2vfxsrzrb.html

Ruby: File.read("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2efyljpzu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2mxqnlhmc.html

[F02] 逐行读取文件
来源：http://dali.zdqjudy.top/Article/details/gt2vtgzbcyg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.aizwys.cn/Article/details/gt2yikiycry.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ybcxt.top/Article/details/gt2ctxfjjkp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gt2lsworwzv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2sonllhtb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gt2uznguczx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinqigfzy.top/Article/details/gt2dvfsqdhp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yonumen.top/Article/details/gt2oxiragjl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.vqdsnc.cn/Article/details/gt2qxcgdiwp.html

[F03] 写入文件（覆盖）
来源：http://dali.vqdsnc.cn/Article/details/gt2zubxmxeh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2debtlizn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gaohongyu789.top/Article/details/gt2ugeuatcj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gt2mocgkuvz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jianghu66.top/Article/details/gt2uutggtuo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.iojbl.cn/Article/details/gt2muwmgftp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yanxiufei.cn/Article/details/gt2gmdclzhi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yanxiufei.cn/Article/details/gt2snbsgtdx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gt2tlqdjbej.html

[F04] 追加写入文件
来源：http://dali.hnxiangtu.top/Article/details/gt2bkvvlkwo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.quarkkingdee.top/Article/details/gt2zvvnqtcu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.c1oappe.top/Article/details/gt2jskhumsn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gt2reinncpj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenlongwang.top/Article/details/gt2tywffyik.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xziqi.cn/Article/details/gt2lvhkogth.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigufen.top/Article/details/gt2lnpyfqsl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shangyingyoupin.top/Article/details/gt2cadjlxch.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangdashe.top/Article/details/gt2gnvvwref.html

[F05] 判断文件或目录是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gt2fdqbbywp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zdqjudy.top/Article/details/gt2xzgfaexy.html

PHP:  file_exists("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2suudbyru.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2vcszicyn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bfjyhsfp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gt2cdbzkvht.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenzaomai.com/Article/details/gt2qhftgswi.html

Ruby: File.exist?("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2fhnrbckf.html

C#:   File.Exists("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2jylazote.html

[F06] 删除文件
来源：http://dali.yj20258888.top/Article/details/gt2mkfgcgih.html

Py:   os.remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2tcbgkzqe.html

PHP:  unlink("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2loaodbnm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2carshztt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2wudugqsy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gt2zurtyjno.html

Go:   os.Remove("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2uoyengux.html

Ruby: File.delete("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2coepvmuj.html

C#:   File.Delete("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2bauzqrwz.html

[F07] 创建目录（含多级）
来源：http://dali.havefunace.top/Article/details/gt2odosgneb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hnxiangtu.top/Article/details/gt2zkajuaee.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zycfv.cn/Article/details/gt2jgfxhmxo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gt2pazfxyjf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cashguo.top/Article/details/gt2zrbeoxpf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnqzz.top/Article/details/gt2ljpqqgji.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.aizwys.cn/Article/details/gt2gkemcgcc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2smzunchu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gaohongyu789.top/Article/details/gt2uengdclg.html

[F08] 遍历目录
来源：http://dali.ehwqpu.com/Article/details/gt2znoxlgzj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ydzc1.top/Article/details/gt2solvewqb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jianghu66.top/Article/details/gt2tlhpuiax.html

JS:   fs.readdirSync("dir")
来源：http://dali.ehwqpu.com/Article/details/gt2shuszbxm.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gt2fpkaabzf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxuanxn.top/Article/details/gt2wbfyatgn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.pycfn.com/Article/details/gt2uvnnqagv.html

Ruby: Dir.children("dir")
来源：http://dali.quarkkingdee.top/Article/details/gt2hkmydxvl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jyoumei.cn/Article/details/gt2mujrmxfw.html

[F09] 获取文件大小
来源：http://dali.birdmap.top/Article/details/gt2npbakmmm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2bnisotqs.html

PHP:  filesize("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gfwahjkc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gt2csxsjsgf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gt2fcvjbrif.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gt2utprkvlu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnxiangtu.top/Article/details/gt2ktnypfmh.html

Ruby: File.size("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2onesxuue.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cdnleiting.top/Article/details/gt2ryxvsdtd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuetiantiany.cn/Article/details/gt2mqghdcna.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2kgixsngc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2npztnoew.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2jxagexlt.html

TS:   path.extname("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2zpwssusc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ivvv.top/Article/details/gt2fcvskufs.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2ucnwsgoy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2zhplnsgg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2oiwtqhcf.html

[F11] 复制与移动文件
来源：http://dali.hywenlv.cn/Article/details/gt2fqcngmfy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2guveovdo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nwbrower.top/Article/details/gt2srqmrwmq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gt2qfgorxra.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2taljdoxt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gt2aeebxxrw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yuxming.cn/Article/details/gt2vyahmsnh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mnefqywe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.meibo888.top/Article/details/gt2ylvfnplw.html

[F12] CSV 读写
来源：http://dali.dianchejie.cn/Article/details/gt2durrgnhj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dvvtvmnd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jlsjyb.cn/Article/details/gt2naewnrcu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdkmtjf.html

TS:   // 同上
来源：http://dali.nwbrower.top/Article/details/gt2tdlhqhep.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dashuyun.cn/Article/details/gt2mckkuvuj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.aizwys.cn/Article/details/gt2zxyydizh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cucudq.cn/Article/details/gt2cnqnxdoe.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xuetiantiany.cn/Article/details/gt2akjoxqdo.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2kaueopfz.html

G. 面向对象
来源：http://dali.zhongyouzk.top/Article/details/gt2pdycjjbz.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2ilwkfkds.html

[G01] 定义类
来源：http://dali.redwolf501.top/Article/details/gt2gpyvwxrn.html

Py:   class User: pass
来源：http://dali.jiagoushi.top/Article/details/gt2nbitqwop.html

PHP:  class User {}
来源：http://dali.chenzaomai.com/Article/details/gt2mjtdfknn.html

JS:   class User {}
来源：http://dali.dashuyun.cn/Article/details/gt2hoxjfkgu.html

TS:   class User { name: string = ""; }
来源：http://dali.cqqwz.cn/Article/details/gt2knfbvgoe.html

Java: class User {}
来源：http://dali.jiagoushi.top/Article/details/gt2jixiejxr.html

Go:   type User struct { Name string }
来源：http://dali.bjfxy.top/Article/details/gt2epajtsux.html

Ruby: class User; end
来源：http://dali.ppjwa.cn/Article/details/gt2cdrkstwu.html

C#:   class User {}
来源：http://dali.c1oappe.top/Article/details/gt2qpabmtdm.html

[G02] 构造函数
来源：http://dali.yongpay.top/Article/details/gt2nujwbckx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yanxiufei.cn/Article/details/gt2hnjbnjzi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2cnfqprhp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2baeaawwt.html

TS:   constructor(public name: string) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2yzwyzhbc.html

Java: User(String name) { this.name = name; }
来源：http://dali.jianghu66.top/Article/details/gt2rwxxwict.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yongpay.top/Article/details/gt2jtmptadd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hnxiangtu.top/Article/details/gt2lbhqealj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.haohaochexian.top/Article/details/gt2yyxmjxeq.html

[G03] 实例属性
来源：http://dali.daria6918.cn/Article/details/gt2bzswqbvc.html

Py:   self.name = "x"
来源：http://dali.tianlin.xyz/Article/details/gt2nrfckutq.html

PHP:  public string $name = "x";
来源：http://dali.ppjwa.cn/Article/details/gt2lzliujsv.html

JS:   this.name = "x";
来源：http://dali.meibo888.top/Article/details/gt2tbkvyiua.html

TS:   name: string = "x";
来源：http://dali.dianchejie.cn/Article/details/gt2gxaplupm.html

Java: private String name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zafqoclp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhengqikj.top/Article/details/gt2mkebmbbp.html

Ruby: @name = "x"
来源：http://dali.bjfxy.top/Article/details/gt2bhdszgxi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenlongwang.top/Article/details/gt2kphodbus.html

[G04] 定义方法
来源：http://dali.guannengcc.top/Article/details/gt2tsnlgixz.html

Py:   def greet(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gt2pzgjzbft.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gt2dlxyjquz.html

JS:   greet() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gt2kznurfut.html

TS:   greet(): string { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gt2vwjmbkij.html

Java: String greet() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gt2gkabrogm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gt2vgycvhmu.html

Ruby: def greet; @name; end
来源：http://dali.gzhubu.top/Article/details/gt2dmlxluee.html

C#:   public string Greet() => Name;
来源：http://dali.snrcjt.cn/Article/details/gt2bwyxxutw.html

[G05] 继承
来源：http://dali.tian-w.cn/Article/details/gt2xzrmcagh.html

Py:   class Admin(User): pass
来源：http://dali.hysaishi.cn/Article/details/gt2gkdxaqek.html

PHP:  class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gt2rxmsrbnh.html

JS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2fihkmoav.html

TS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gt2lmdfbskj.html

Java: class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tpvxuqvy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhongyouzk.top/Article/details/gt2twdriaxr.html

Ruby: class Admin < User; end
来源：http://dali.jlsjyb.cn/Article/details/gt2bwurbpab.html

C#:   class Admin : User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2aixeahnp.html

[G06] 重写方法
来源：http://dali.gotoacloud.top/Article/details/gt2soxnyvid.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigfzy.top/Article/details/gt2tcyugzuw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2vzgeplvq.html

JS:   greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2jokkcdhq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ddnymryj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gt2ckqxulmu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daria6918.cn/Article/details/gt2bseoucdi.html

Ruby: def greet; "admin"; end
来源：http://dali.yj202588.top/Article/details/gt2hcvbdexr.html

C#:   public override string Greet() => "admin";
来源：http://dali.meibo888.top/Article/details/gt2flfvgiuu.html

[G07] 调用父类方法
来源：http://dali.daria6918.cn/Article/details/gt2amebazsu.html

Py:   super().greet()
来源：http://dali.316326.xyz/Article/details/gt2plpfygex.html

PHP:  parent::greet();
来源：http://dali.cashguo.top/Article/details/gt2nkawjhxh.html

JS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gt2zjqoubin.html

TS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gt2bdkwxhes.html

Java: super.greet();
来源：http://dali.smart0.xyz/Article/details/gt2tolkxxto.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yonumen.top/Article/details/gt2pychqmyv.html

Ruby: super
来源：http://dali.xinyue.icu/Article/details/gt2phkfhchs.html

C#:   base.Greet();
来源：http://dali.guannengcc.top/Article/details/gt2nhrhyvms.html

[G08] 静态方法与属性
来源：http://dali.ivvv.top/Article/details/gt2kcnhucvw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xylfe.cn/Article/details/gt2byfbmnkd.html

PHP:  public static function f() {}
来源：http://dali.fengsongda.top/Article/details/gt2gcappbmq.html

JS:   static f() {}
来源：http://dali.iojbl.cn/Article/details/gt2hfmwnmuv.html

TS:   static f(): void {}
来源：http://dali.sysykeji.top/Article/details/gt2xhoxrvgm.html

Java: static void f() {}
来源：http://dali.dashuyun.cn/Article/details/gt2xpyjefga.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnqzz.top/Article/details/gt2swgfdnxj.html

Ruby: def self.f; end
来源：http://dali.daxiang520.top/Article/details/gt2psapcxfv.html

C#:   public static void F() {}
来源：http://dali.sweek.top/Article/details/gt2ezlktrrm.html

[G09] 接口 / 抽象类
来源：http://dali.zhengqikj.top/Article/details/gt2svhnolrh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenjidiqi.icu/Article/details/gt2ymugwbxa.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.0kj1m.cn/Article/details/gt2okpqubce.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gotoacloud.top/Article/details/gt2czdjwgsl.html

TS:   interface Shape { area(): number; }
来源：http://dali.cheryme.top/Article/details/gt2qfqyjtyi.html

Java: interface Shape { double area(); }
来源：http://dali.redwolf501.top/Article/details/gt2kixqpkrq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenzaomai.com/Article/details/gt2yekfrbnq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhengqikj.top/Article/details/gt2cnmoptbw.html

C#:   interface IShape { double Area(); }
来源：http://dali.andypj.xyz/Article/details/gt2dpienlau.html


<!-- 参考信息 -->