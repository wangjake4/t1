代发 wailian999

Ruby: s.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmtuatwl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jlsjyb.cn/Article/details/gtlbqfqajj.html

[E12] 统计某字符出现次数
来源：http://dali.zhengqikj.top/Article/details/gtwbcgipmd.html

Py:   s.count("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtbfmiibyr.html

PHP:  substr_count($s, "a");
来源：http://dali.iojbl.cn/Article/details/gtyhpspjyr.html

JS:   s.split("a").length - 1
来源：http://dali.cucudq.cn/Article/details/gtwjmswrky.html

TS:   s.split("a").length - 1
来源：http://dali.cdnleiting.top/Article/details/gtexcczvft.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gtmyfszxqp.html

Go:   strings.Count(s, "a")
来源：http://dali.nwbrower.top/Article/details/gtthhvipej.html

Ruby: s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gtiiatpoxl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.wangdashe.top/Article/details/gtddnsrbmb.html

[E13] 逐字符遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhhbqcyf.html

Py:   for ch in s: print(ch)
来源：http://dali.xuetiantiany.cn/Article/details/gtylrfcacl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.316326.xyz/Article/details/gtdjzswlmb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwwwnfabh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gtwjhpacmp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hammf.cn/Article/details/gtdgfyxifh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sysykeji.top/Article/details/gtmjjbzlxr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hywenlv.cn/Article/details/gtqzohzeul.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nwbrower.top/Article/details/gtwoxhakvc.html

[E14] URL 编码与 Base64
来源：http://dali.xuetiantiany.cn/Article/details/gtmnfwyale.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.feifeiyinyue.top/Article/details/gtepefglku.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenjidiqi.icu/Article/details/gttsxlcizh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sysykeji.top/Article/details/gtwpcikvzn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.birdmap.top/Article/details/gtyoguunpc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cashguo.top/Article/details/gtcmlbomqp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.redwolf501.top/Article/details/gtqznzqhxy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.birdmap.top/Article/details/gtxurhsetl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.iojbl.cn/Article/details/gtjiugzscj.html

[E15] HTML 转义 / 反转义
来源：http://dali.ybcxt.top/Article/details/gtdwoocycv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhoulong.xyz/Article/details/gtzpgsbewn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nwbrower.top/Article/details/gtrwxabjla.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sweek.top/Article/details/gtsjvymruy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shzxlz.cn/Article/details/gtofywhoqx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.0kj1m.cn/Article/details/gtftotkdjm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jianghu66.top/Article/details/gtcpzlcnzy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ehwqpu.com/Article/details/gtofkbmakp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.guowangkeji.top/Article/details/gtzkptdsqb.html

[E16] 数字千分位
来源：http://dali.zhiwuduotai.top/Article/details/gtsbrfecsr.html

Py:   f"{1234567:,}"
来源：http://dali.iojbl.cn/Article/details/gtngbgvolp.html

PHP:  number_format(1234567);
来源：http://dali.cheryme.top/Article/details/gtmaekfqlp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.iojbl.cn/Article/details/gtgybdrhhu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenjidiqi.icu/Article/details/gtdpmyzjre.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.9152youxi.cn/Article/details/gtfdnbpzlc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.iojbl.cn/Article/details/gtlmhgxikc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zycfv.cn/Article/details/gtakvvantu.html

C#:   1234567.ToString("N0")
来源：http://dali.xinyue.icu/Article/details/gtnlnxityz.html

[E17] 首字母大写
来源：http://dali.sufxvd.cn/Article/details/gtsceqtxpk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtudbacity.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.quarkkingdee.top/Article/details/gtmovpfyna.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gttuffqdhh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gtosflnceq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jianghu66.top/Article/details/gtshhxgmtz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sysykeji.top/Article/details/gtbjhxgtsr.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gtknwpwkle.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hammf.cn/Article/details/gtffmmvabz.html

[E18] 模板占位符替换
来源：http://dali.aizwys.cn/Article/details/gtbjfopbdh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guowangkeji.top/Article/details/gtcxhqxqzv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.guowangkeji.top/Article/details/gtxsqsmrjx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtnoosaras.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtppycglaf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtohpneaan.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtfzwbgvpj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ydzc1.top/Article/details/gtdvwqyvww.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ppjwa.cn/Article/details/gtymooytfn.html

[E19] 多行文本按行拆分
来源：http://dali.tian-w.cn/Article/details/gtmtyiixal.html

Py:   s.splitlines()
来源：http://dali.shanyushiyangtech.top/Article/details/gticmiztqq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ivvv.top/Article/details/gtafusnbkk.html

JS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gtijuietdo.html

TS:   s.split(/\r?\n/)
来源：http://dali.jiagoushi.top/Article/details/gtzxoshfqt.html

Java: s.lines().toList()
来源：http://dali.xinyue.icu/Article/details/gtmrdwrdhi.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj202588.top/Article/details/gtfhbsvxqx.html

Ruby: s.lines
来源：http://dali.jiagoushi.top/Article/details/gtmtfvyhvg.html

C#:   s.Split('\n')
来源：http://dali.ppjwa.cn/Article/details/gtrlegvniu.html

[E20] 判断字符串是否为空
来源：http://dali.hongshengwenyu.top/Article/details/gtmjjdodsk.html

Py:   if not s:
来源：http://dali.ppjwa.cn/Article/details/gtxrxqkdso.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.wangdashe.top/Article/details/gtjhyzudid.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yuanzhike.top/Article/details/gtstpuapld.html

TS:   if (s === "") {}
来源：http://dali.wangshuangyany.cn/Article/details/gthokqatts.html

Java: if (s.isEmpty()) {}
来源：http://dali.ivvv.top/Article/details/gtrdujvwbh.html

Go:   if s == "" {}
来源：http://dali.andypj.xyz/Article/details/gtnrjavwxb.html

Ruby: if s.empty?
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmzctffzg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhengqikj.top/Article/details/gtomimemmb.html

[E21] 超长截断加省略号
来源：http://dali.yangfankeji.com/Article/details/gtrtlcwwro.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwgwglzx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtejkhqspt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gtuispnzaz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gtsqbeumhf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtonghbjbt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.bjfxy.top/Article/details/gthaljbdyv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtsnsidymi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtdxgjgqol.html

[E22] 字节长度与字符长度
来源：http://dali.daxiang520.top/Article/details/gtiyycpvuv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.havefunace.top/Article/details/gtedvimdtz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtehtrabcf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gtlqxdkqtl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gtlpphdteq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aibaodan.cn/Article/details/gtafnzxblz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinqigfzy.top/Article/details/gtsmvudavc.html

Ruby: s.bytesize;  s.length
来源：http://dali.jianghu66.top/Article/details/gtbryqfzpl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.iojbl.cn/Article/details/gtxvdomgmp.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtjyffvior.html

F. 文件与目录
来源：http://dali.zhoulong.xyz/Article/details/gtedxpgnin.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtbnyipgdu.html

[F01] 读取整个文件
来源：http://dali.jqgufenzy.top/Article/details/gtdsjnlpyc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigufen.top/Article/details/gtlgewbkeg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbtyjlms.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shuidangran.top/Article/details/gtwpxtzfhp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cashguo.top/Article/details/gtimhptmab.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtqyjttxct.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.aibaodan.cn/Article/details/gtpkhbntbt.html

Ruby: File.read("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtpqhqepjd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.redwolf501.top/Article/details/gteeqqgxgs.html

[F02] 逐行读取文件
来源：http://dali.xuanzx.com/Article/details/gtukxadzfr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfrklhdh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hammf.cn/Article/details/gtohobhazw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhixingplan.top/Article/details/gtsglpgblx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shangyingyoupin.top/Article/details/gthxwvwqwz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gtnruaxmcb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hnxiangtu.top/Article/details/gtajwiyjqj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yueranfly.top/Article/details/gtsvenfssp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.0kj1m.cn/Article/details/gtrfqlxdpr.html

[F03] 写入文件（覆盖）
来源：http://dali.iojbl.cn/Article/details/gtizbslydr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tian-w.cn/Article/details/gtqrmgrwtr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gtjnkqsyhv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zycfv.cn/Article/details/gtumuztzqw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sysykeji.top/Article/details/gtyqcbxvpo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.vqdsnc.cn/Article/details/gtmameaotw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.316326.xyz/Article/details/gtmycquqlk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigufen.top/Article/details/gtdltkitua.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gttelwahxt.html

[F04] 追加写入文件
来源：http://dali.cucudq.cn/Article/details/gtlezvcmcl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskazqfes.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cqqwz.cn/Article/details/gtlimniezn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shuidangran.top/Article/details/gtlnxqhite.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gtnlyqtzsk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.quarkkingdee.top/Article/details/gtzjowkpjp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sysykeji.top/Article/details/gtpvojomob.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sweek.top/Article/details/gtgisxbeej.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ivvv.top/Article/details/gtvfgnllsj.html

[F05] 判断文件或目录是否存在
来源：http://dali.c1oappe.top/Article/details/gtvubgskvq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sxryk.cn/Article/details/gtjhmdzvej.html

PHP:  file_exists("a.txt");
来源：http://dali.sweek.top/Article/details/gtxbgywcho.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvadbenbw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtcpyfqajc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnbqihelp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.haohaochexian.top/Article/details/gtxfwxugpc.html

Ruby: File.exist?("a.txt")
来源：http://dali.tanke756.top/Article/details/gtjicbntjc.html

C#:   File.Exists("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtawfqsczs.html

[F06] 删除文件
来源：http://dali.xuanzx.com/Article/details/gteewsbdeg.html

Py:   os.remove("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtwjiqtvsy.html

PHP:  unlink("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtsjogvsbl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gttzheozce.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtcnbfqriz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtmvzhxzbx.html

Go:   os.Remove("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtaiiyfqos.html

Ruby: File.delete("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtomdrkllc.html

C#:   File.Delete("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtfbcmdsmg.html

[F07] 创建目录（含多级）
来源：http://dali.dashuyun.cn/Article/details/gtalfknaqu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.havefunace.top/Article/details/gtxnqferrx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.pengpengdd.cyou/Article/details/gtmriqjhvm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gtwhnnqouh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gtzduanbyb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gogol.net.cn/Article/details/gtuedismeq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.fzhhl.top/Article/details/gtnbhummfk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hnqzz.top/Article/details/gtucogtbpg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinqigfzy.top/Article/details/gtwjhagbmw.html

[F08] 遍历目录
来源：http://dali.c1oappe.top/Article/details/gtsnfhaswh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvmskfdo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.316326.xyz/Article/details/gtvkxnuehs.html

JS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwpkgntac.html

TS:   fs.readdirSync("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtviyblueb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gtwyaxqiog.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nwbrower.top/Article/details/gtjawqsbmm.html

Ruby: Dir.children("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpdpjgavl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.snrcjt.cn/Article/details/gtaqgvwklf.html

[F09] 获取文件大小
来源：http://dali.tianlin.xyz/Article/details/gthmuunsjo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtxjfaleli.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtlqyqnbkb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nanxinkj.top/Article/details/gtbdqiyvjj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gtoeehggqu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtodgawenp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigufen.top/Article/details/gtbifjxrhj.html

Ruby: File.size("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtzhrsejag.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ybcxt.top/Article/details/gtntkfdrfw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shzxlz.cn/Article/details/gtwxgsdxvz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtxehtbqfh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cucudq.cn/Article/details/gtcyntiujq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtetkkjmwn.html

TS:   path.extname("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtotnjcpif.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gotoacloud.top/Article/details/gtmtdniqbc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtcottrdjo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtuvtnpbjn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiewlbrba.html

[F11] 复制与移动文件
来源：http://dali.xylfe.cn/Article/details/gtjkzmpdkq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gteychbssx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yangfankeji.com/Article/details/gtzltpvxcn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtueplelgc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtitzzpakl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.bjfxy.top/Article/details/gtslkovmix.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tanke756.top/Article/details/gtwmrepfai.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtlcwfpygj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jianghu66.top/Article/details/gtsehpyafx.html

[F12] CSV 读写
来源：http://dali.birdmap.top/Article/details/gtlvbbezul.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.bjfxy.top/Article/details/gtyuatpuao.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hfpthk.cn/Article/details/gtyntupgaq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shanyushiyangtech.top/Article/details/gtonfvmezb.html

TS:   // 同上
来源：http://dali.yueranfly.top/Article/details/gtoagspysv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.snrcjt.cn/Article/details/gtqaeazoqg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gtouhxrkbu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.9152youxi.cn/Article/details/gtumvxkofr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hysaishi.cn/Article/details/gtxvkopiyc.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhlnwxeb.html

G. 面向对象
来源：http://dali.cdnleiting.top/Article/details/gtoxcgexac.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtnrxjhchv.html

[G01] 定义类
来源：http://dali.yongpay.top/Article/details/gtsbbrrcho.html

Py:   class User: pass
来源：http://dali.ydzc1.top/Article/details/gtedpmricl.html

PHP:  class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdnsfcbnv.html

JS:   class User {}
来源：http://dali.yuxming.cn/Article/details/gtzjjjaaqh.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gtgbwnweel.html

Java: class User {}
来源：http://dali.birdmap.top/Article/details/gtpculkmie.html

Go:   type User struct { Name string }
来源：http://dali.ydzc1.top/Article/details/gtubpatbqk.html

Ruby: class User; end
来源：http://dali.fengsongda.top/Article/details/gtzsailpvz.html

C#:   class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtqmmuouka.html

[G02] 构造函数
来源：http://dali.meibo888.top/Article/details/gtymapuezn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tianlin.xyz/Article/details/gtpddsdrig.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tian-w.cn/Article/details/gtzbfgluih.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gttgiivfbs.html

TS:   constructor(public name: string) {}
来源：http://dali.bjfxy.top/Article/details/gtxnmffxve.html

Java: User(String name) { this.name = name; }
来源：http://dali.gotoacloud.top/Article/details/gtawzxtpuf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.havefunace.top/Article/details/gtshehbwzm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.vqdsnc.cn/Article/details/gtwtlbxaqd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhixingplan.top/Article/details/gtjbeeakho.html

[G03] 实例属性
来源：http://dali.redwolf501.top/Article/details/gtuzdpiqrr.html

Py:   self.name = "x"
来源：http://dali.xuetiantiany.cn/Article/details/gtwujrvvrg.html

PHP:  public string $name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtmnnwkife.html

JS:   this.name = "x";
来源：http://dali.jiagoushi.top/Article/details/gthedfisxs.html

TS:   name: string = "x";
来源：http://dali.yongpay.top/Article/details/gtalystnty.html

Java: private String name;
来源：http://dali.birdmap.top/Article/details/gtgntoshtf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnxiangtu.top/Article/details/gtuqcbejoh.html

Ruby: @name = "x"
来源：http://dali.yj20258.top/Article/details/gtzhqxpzqf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.redwolf501.top/Article/details/gthquirkoe.html

[G04] 定义方法
来源：http://dali.chenjidiqi.icu/Article/details/gtblybffho.html

Py:   def greet(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gtpojttdxd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtwhhtewrd.html

JS:   greet() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtmrtodcwg.html

TS:   greet(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtdwprgkxh.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtraasqvkv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gttrdhscsa.html

Ruby: def greet; @name; end
来源：http://dali.tianlin.xyz/Article/details/gtlimoctbn.html

C#:   public string Greet() => Name;
来源：http://dali.cucudq.cn/Article/details/gtaplfllfi.html

[G05] 继承
来源：http://dali.zhiwuduotai.top/Article/details/gtuuvinrhm.html

Py:   class Admin(User): pass
来源：http://dali.yonumen.top/Article/details/gtsgegunml.html

PHP:  class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtokzlaxaf.html

JS:   class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtixvbwkug.html

TS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtjjudbnjr.html

Java: class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtbprdmigo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xinyue.icu/Article/details/gtubfpzhfn.html

Ruby: class Admin < User; end
来源：http://dali.yj20258888.top/Article/details/gtcqwffydz.html

C#:   class Admin : User {}
来源：http://dali.sufxvd.cn/Article/details/gttdglejcc.html

[G06] 重写方法
来源：http://dali.fengsongda.top/Article/details/gtzgwdjngp.html

Py:   def greet(self): return "admin"
来源：http://dali.shzxlz.cn/Article/details/gtjocupmre.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtrepxmmft.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtntofpzzs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtsikzkdge.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtujzurnbe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tianlin.xyz/Article/details/gtcsrfhfsp.html

Ruby: def greet; "admin"; end
来源：http://dali.cashguo.top/Article/details/gtzsfcdzyh.html

C#:   public override string Greet() => "admin";
来源：http://dali.wangshuangyany.cn/Article/details/gtgdhbksok.html

[G07] 调用父类方法
来源：http://dali.hysaishi.cn/Article/details/gtmeezibej.html

Py:   super().greet()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpceyyazk.html

PHP:  parent::greet();
来源：http://dali.xuanzx.com/Article/details/gtilncdwvb.html

JS:   super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gtctzkawbr.html

TS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gtwzoqyfio.html

Java: super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtggvzyrci.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnxiangtu.top/Article/details/gttmrxfvqw.html

Ruby: super
来源：http://dali.hfpthk.cn/Article/details/gtaoepahyx.html

C#:   base.Greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtxjziutxa.html

[G08] 静态方法与属性
来源：http://dali.sysykeji.top/Article/details/gtaeytvuxs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nanxinkj.top/Article/details/gtewttsowg.html

PHP:  public static function f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllikthlb.html

JS:   static f() {}
来源：http://dali.shzxlz.cn/Article/details/gtxzwofoyh.html

TS:   static f(): void {}
来源：http://dali.smart0.xyz/Article/details/gtgtqwioxa.html

Java: static void f() {}
来源：http://dali.yj20258888.top/Article/details/gtwfgqdodb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.c1oappe.top/Article/details/gtilvcmlrm.html

Ruby: def self.f; end
来源：http://dali.fengsongda.top/Article/details/gtlkqqfrup.html

C#:   public static void F() {}
来源：http://dali.hfpthk.cn/Article/details/gtqstdhdbq.html

[G09] 接口 / 抽象类
来源：http://dali.zdqjudy.top/Article/details/gtduohiraq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcigfpsvl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhixingplan.top/Article/details/gtetboupze.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.fzhhl.top/Article/details/gtglpjcmze.html

TS:   interface Shape { area(): number; }
来源：http://dali.shangyingyoupin.top/Article/details/gtizutkhmp.html

Java: interface Shape { double area(); }
来源：http://dali.gaohongyu789.top/Article/details/gthieyhmfx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zdqjudy.top/Article/details/gttuddoeum.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zycfv.cn/Article/details/gttwfozinv.html

C#:   interface IShape { double Area(); }
来源：http://dali.tian-w.cn/Article/details/gtpdusxqrk.html

[G10] 访问控制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevyoburp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.pengpengdd.cyou/Article/details/gtpzxozeoh.html

PHP:  public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtobtkljzp.html

JS:   #private 字段；其余公开
来源：http://dali.ppjwa.cn/Article/details/gtmwqbdvmc.html


<!-- 参考信息 -->