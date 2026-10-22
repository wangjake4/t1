代发 wailian999

Ruby: s.reverse
来源：http://dali.xinyue.icu/Article/details/gt2pwvximzj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cucudq.cn/Article/details/gt2leerlbzi.html

[E12] 统计某字符出现次数
来源：http://dali.zdqjudy.top/Article/details/gt2dzqsqgzd.html

Py:   s.count("a")
来源：http://dali.gaohongyu789.top/Article/details/gt2ggqpwxoq.html

PHP:  substr_count($s, "a");
来源：http://dali.zhengqikj.top/Article/details/gt2rdgkintg.html

JS:   s.split("a").length - 1
来源：http://dali.havefunace.top/Article/details/gt2foclcjvb.html

TS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gt2dpkjwytz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.dashuyun.cn/Article/details/gt2tvremcgk.html

Go:   strings.Count(s, "a")
来源：http://dali.andypj.xyz/Article/details/gt2lyssqqdd.html

Ruby: s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gt2gfcehbis.html

C#:   s.Count(c => c == 'a')
来源：http://dali.havefunace.top/Article/details/gt2qgovgqbz.html

[E13] 逐字符遍历
来源：http://dali.zhoulong.xyz/Article/details/gt2vidvgyoo.html

Py:   for ch in s: print(ch)
来源：http://dali.shzxlz.cn/Article/details/gt2ttwqcmpj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sxryk.cn/Article/details/gt2srkbarep.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xylfe.cn/Article/details/gt2nkrmfkhw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gogol.net.cn/Article/details/gt2xjiuewws.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj20258888.top/Article/details/gt2gmbxkbym.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.mhx1999.top/Article/details/gt2hbgwwloh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.redwolf501.top/Article/details/gt2efcsimzw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ketcyfys.html

[E14] URL 编码与 Base64
来源：http://dali.snrcjt.cn/Article/details/gt2jnyhqggm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinqigufen.top/Article/details/gt2lnixutui.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2zldbgfpm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xuanzx.com/Article/details/gt2lqrfeiok.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bdizcodp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aizwys.cn/Article/details/gt2jgdvzprd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cdnleiting.top/Article/details/gt2lhgbncqm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.daxiang520.top/Article/details/gt2cdrzsiaa.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lrjjbhsx.html

[E15] HTML 转义 / 反转义
来源：http://dali.iojbl.cn/Article/details/gt2gezatzxu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yongpay.top/Article/details/gt2aomxlxki.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.andypj.xyz/Article/details/gt2fvqnatbx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zdqjudy.top/Article/details/gt2gtfyjufs.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gzhubu.top/Article/details/gt2wppoqpyb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tian-w.cn/Article/details/gt2mrphexzd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.guowangkeji.top/Article/details/gt2lpqjlbqa.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2xgzwqjuz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.bjfxy.top/Article/details/gt2ucdftbpc.html

[E16] 数字千分位
来源：http://dali.yvedp.cn/Article/details/gt2pnhigmgi.html

Py:   f"{1234567:,}"
来源：http://dali.wangdashe.top/Article/details/gt2xhjkjqss.html

PHP:  number_format(1234567);
来源：http://dali.tian-w.cn/Article/details/gt2fogzrqgh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.smart0.xyz/Article/details/gt2ouebtkpu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jiagoushi.top/Article/details/gt2bmyooltu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.vqdsnc.cn/Article/details/gt2tuknaczg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.iojbl.cn/Article/details/gt2nxpzlrox.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ydzc1.top/Article/details/gt2iycbmvef.html

C#:   1234567.ToString("N0")
来源：http://dali.chenlongwang.top/Article/details/gt2xotkvrsa.html

[E17] 首字母大写
来源：http://dali.c1oappe.top/Article/details/gt2gvsfyxwb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.daria6918.cn/Article/details/gt2xwsevkxv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sysykeji.top/Article/details/gt2hyfhzebj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ayurleim.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.bjfxy.top/Article/details/gt2yvlpaymb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xuerwoiq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj20258.top/Article/details/gt2qdfxpwov.html

Ruby: s.capitalize
来源：http://dali.hammf.cn/Article/details/gt2tgdyrplx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.quarkkingdee.top/Article/details/gt2ldtxxrgd.html

[E18] 模板占位符替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tgtvkyhb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.meibo888.top/Article/details/gt2myjhmprx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hongshengwenyu.top/Article/details/gt2dgsagxir.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.pycfn.com/Article/details/gt2wydiuceb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gt2seexavub.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gt2qrqabekv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gt2ptcwujax.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.daxiang520.top/Article/details/gt2xriazrgr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xuanzx.com/Article/details/gt2jzabhujo.html

[E19] 多行文本按行拆分
来源：http://dali.hongshengwenyu.top/Article/details/gt2vtolavan.html

Py:   s.splitlines()
来源：http://dali.shzxlz.cn/Article/details/gt2lodwgzvd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jiagoushi.top/Article/details/gt2alorbhma.html

JS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gt2yklirtbl.html

TS:   s.split(/\r?\n/)
来源：http://dali.hysaishi.cn/Article/details/gt2wbnaosdx.html

Java: s.lines().toList()
来源：http://dali.xinyue.icu/Article/details/gt2ldaydubk.html

Go:   strings.Split(s, "\n")
来源：http://dali.gzhubu.top/Article/details/gt2zvfssynx.html

Ruby: s.lines
来源：http://dali.jiagoushi.top/Article/details/gt2ovtjdadw.html

C#:   s.Split('\n')
来源：http://dali.9152youxi.cn/Article/details/gt2txuhifbo.html

[E20] 判断字符串是否为空
来源：http://dali.hnxiangtu.top/Article/details/gt2qfsrnhbh.html

Py:   if not s:
来源：http://dali.quarkkingdee.top/Article/details/gt2eahsefru.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yrjaazfb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.c1oappe.top/Article/details/gt2irgoeijn.html

TS:   if (s === "") {}
来源：http://dali.nwbrower.top/Article/details/gt2odmowibx.html

Java: if (s.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gt2oedfgvpz.html

Go:   if s == "" {}
来源：http://dali.jianghu66.top/Article/details/gt2bikegcps.html

Ruby: if s.empty?
来源：http://dali.jqgufenzy.top/Article/details/gt2wjqhvwkr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2dsygqthg.html

[E21] 超长截断加省略号
来源：http://dali.shuidangran.top/Article/details/gt2npukjovy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ybcxt.top/Article/details/gt2eowhcsfg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gt2ayclambq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gt2dzxjgbvx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gt2bcqkovfs.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gt2tpnblram.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gzhubu.top/Article/details/gt2llotvhnj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gt2oyocvpzx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gt2vzkzogcr.html

[E22] 字节长度与字符长度
来源：http://dali.andypj.xyz/Article/details/gt2bsqbfqyl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2xjgbuwpg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gt2bksysqqe.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zycfv.cn/Article/details/gt2zgnklvdq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gt2ovobhnfg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangdashe.top/Article/details/gt2alkfprds.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuxming.cn/Article/details/gt2hlvblzih.html

Ruby: s.bytesize;  s.length
来源：http://dali.cashguo.top/Article/details/gt2iwbtgfcu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ehwqpu.com/Article/details/gt2dspojlrq.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2mudtfotp.html

F. 文件与目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cmzntlyj.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2nlgldccu.html

[F01] 读取整个文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2sotmwwxo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.kuanghao11.cn/Article/details/gt2jurzjruj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2dhvmchxf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ivvv.top/Article/details/gt2dqwedmiw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gt2grotcmkg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gt2acamtdre.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenzaomai.com/Article/details/gt2jwqtszno.html

Ruby: File.read("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2wikmdnyb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2lewlhnjd.html

[F02] 逐行读取文件
来源：http://dali.dashuyun.cn/Article/details/gt2xdnwstze.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.guannengcc.top/Article/details/gt2mekkdiai.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vzukbtah.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cheryme.top/Article/details/gt2omliwxmj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gt2rrlmkoai.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gt2wdjjlvqi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.9152youxi.cn/Article/details/gt2mgbvmgfv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cucudq.cn/Article/details/gt2vepanayc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinqigufen.top/Article/details/gt2cqsfkbqr.html

[F03] 写入文件（覆盖）
来源：http://dali.haohaochexian.top/Article/details/gt2vehpxnrw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.haohaochexian.top/Article/details/gt2vddldvuj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gt2guvvzzzp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wylgyeoy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gt2rbflkgmb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.0kj1m.cn/Article/details/gt2vxmwvgnm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhixingplan.top/Article/details/gt2chilyzvg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.316326.xyz/Article/details/gt2vctkvmol.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gt2soagfeyc.html

[F04] 追加写入文件
来源：http://dali.pycfn.com/Article/details/gt2fqvukodo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yuanzhike.top/Article/details/gt2suredcui.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2crmdhlyg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gt2xqlcpsjy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aizwys.cn/Article/details/gt2fdumpqqp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yanxiufei.cn/Article/details/gt2hnlrmjrg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yuanzhike.top/Article/details/gt2ykqmrvda.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yueranfly.top/Article/details/gt2wcflsdrq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jianghu66.top/Article/details/gt2vfaskbnp.html

[F05] 判断文件或目录是否存在
来源：http://dali.dianchejie.cn/Article/details/gt2cbrvxmum.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jianghu66.top/Article/details/gt2rewycgnl.html

PHP:  file_exists("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2jpbypsij.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2pwfllnjz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jgupjjpv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gt2bfwsceuc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.birdmap.top/Article/details/gt2qfnzhnvm.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zwhqngnj.html

C#:   File.Exists("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2cxpnmqnp.html

[F06] 删除文件
来源：http://dali.nanxuanxn.top/Article/details/gt2pvpxmdbl.html

Py:   os.remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2oywxmgtu.html

PHP:  unlink("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2kvakdlsy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2pkepzoqj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2iaqxgixr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hhzyixtt.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2pmnhpxzw.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vghrfkan.html

C#:   File.Delete("a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2nfmgezvh.html

[F07] 创建目录（含多级）
来源：http://dali.ehwqpu.com/Article/details/gt2miwoludn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sufxvd.cn/Article/details/gt2ukmshews.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.andypj.xyz/Article/details/gt2wkshucio.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gt2zrptqiga.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guowangkeji.top/Article/details/gt2rceddxre.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pycfn.com/Article/details/gt2rknothly.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yvedp.cn/Article/details/gt2zidgnqbs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.kuanghao11.cn/Article/details/gt2fzckpiks.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tian-w.cn/Article/details/gt2cngyxdpd.html

[F08] 遍历目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zafkonfj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yangfankeji.com/Article/details/gt2bflyqslr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zdqjudy.top/Article/details/gt2elrnvflt.html

JS:   fs.readdirSync("dir")
来源：http://dali.xuanzx.com/Article/details/gt2ustyroke.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rnnfyewr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gzhubu.top/Article/details/gt2yyivhfus.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nwbrower.top/Article/details/gt2qhweleru.html

Ruby: Dir.children("dir")
来源：http://dali.pycfn.com/Article/details/gt2jycisqhb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yonumen.top/Article/details/gt2gjnmwtfx.html

[F09] 获取文件大小
来源：http://dali.aizwys.cn/Article/details/gt2podzaqul.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2cidztadc.html

PHP:  filesize("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2xcqqrxjp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhongyouzk.top/Article/details/gt2dkifixtr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yongpay.top/Article/details/gt2eyjlrsml.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gt2eeudykti.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jlsjyb.cn/Article/details/gt2fyexfphe.html

Ruby: File.size("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2mdppenmw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.aibaodan.cn/Article/details/gt2hwalglft.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigufen.top/Article/details/gt2rmhjdpyz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2rlfprbtc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2wxkdpopa.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gt2ahnmrpii.html

TS:   path.extname("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2vlddtbmv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258888.top/Article/details/gt2fvezrfhc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2pkwajksv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2ydnjmcgi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2mdrtoksj.html

[F11] 复制与移动文件
来源：http://dali.xuanzx.com/Article/details/gt2qdvemcnr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2grqpxhgj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gzhubu.top/Article/details/gt2hkksyfvo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2hwznsztt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2dpnmfwti.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.svipenyu.cn/Article/details/gt2ynpxvgbf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ppjwa.cn/Article/details/gt2hhxogppm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2tfaqvoms.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.316326.xyz/Article/details/gt2vduwzddv.html

[F12] CSV 读写
来源：http://dali.jianghu66.top/Article/details/gt2jxcsvtks.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ivvv.top/Article/details/gt2tfswaoij.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jlsjyb.cn/Article/details/gt2curbqlim.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jyoumei.cn/Article/details/gt2uwyrapeh.html

TS:   // 同上
来源：http://dali.sysykeji.top/Article/details/gt2pgsurzgz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hammf.cn/Article/details/gt2qqsyxlxy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sxryk.cn/Article/details/gt2ojuxuojp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.snrcjt.cn/Article/details/gt2yzypngzf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.vqdsnc.cn/Article/details/gt2fsycipqo.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2xldcairg.html

G. 面向对象
来源：http://dali.aizwys.cn/Article/details/gt2oazxlmsp.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2karnwlcf.html

[G01] 定义类
来源：http://dali.sxryk.cn/Article/details/gt2elmagiyw.html

Py:   class User: pass
来源：http://dali.chenzaomai.com/Article/details/gt2hzbatubo.html

PHP:  class User {}
来源：http://dali.chenzaomai.com/Article/details/gt2qqzuoupl.html

JS:   class User {}
来源：http://dali.sweek.top/Article/details/gt2ozffnwnd.html

TS:   class User { name: string = ""; }
来源：http://dali.guannengcc.top/Article/details/gt2skuvniza.html

Java: class User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2kvxlezfi.html

Go:   type User struct { Name string }
来源：http://dali.ybcxt.top/Article/details/gt2okqxaudp.html

Ruby: class User; end
来源：http://dali.yanxiufei.cn/Article/details/gt2vbhrlerr.html

C#:   class User {}
来源：http://dali.yuxming.cn/Article/details/gt2wkngcjyy.html

[G02] 构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2gpthkfgq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.haohaochexian.top/Article/details/gt2bdoommng.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zycfv.cn/Article/details/gt2xprfeojq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gt2qzjcmeoe.html

TS:   constructor(public name: string) {}
来源：http://dali.ivvv.top/Article/details/gt2tzigzkbb.html

Java: User(String name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gt2kamcuovx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nwbrower.top/Article/details/gt2nqbsqfir.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daxiang520.top/Article/details/gt2gmqpwiqq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xcagzhun.html

[G03] 实例属性
来源：http://dali.xylfe.cn/Article/details/gt2uduapexk.html

Py:   self.name = "x"
来源：http://dali.sufxvd.cn/Article/details/gt2qqbgwtzg.html

PHP:  public string $name = "x";
来源：http://dali.yanxiufei.cn/Article/details/gt2rugfrbqm.html

JS:   this.name = "x";
来源：http://dali.zhengqikj.top/Article/details/gt2owsjdyda.html

TS:   name: string = "x";
来源：http://dali.tian-w.cn/Article/details/gt2gyrxsqyv.html

Java: private String name;
来源：http://dali.shangyingyoupin.top/Article/details/gt2lwdwsglg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yvedp.cn/Article/details/gt2hsgfssyu.html

Ruby: @name = "x"
来源：http://dali.hongshengwenyu.top/Article/details/gt2ntrstsje.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shzxlz.cn/Article/details/gt2xnwggams.html

[G04] 定义方法
来源：http://dali.yuanzhike.top/Article/details/gt2hsihldfm.html

Py:   def greet(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gt2njkxxzvb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zbgrotod.html

JS:   greet() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gt2pvtxlnyh.html

TS:   greet(): string { return this.name; }
来源：http://dali.ivvv.top/Article/details/gt2jsyuaxjv.html

Java: String greet() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gt2zdhyscer.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gt2uhtxprke.html

Ruby: def greet; @name; end
来源：http://dali.tanke756.top/Article/details/gt2cnafbzlw.html

C#:   public string Greet() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gt2xguxmkax.html

[G05] 继承
来源：http://dali.guowangkeji.top/Article/details/gt2mtykhirg.html

Py:   class Admin(User): pass
来源：http://dali.ehwqpu.com/Article/details/gt2bvotayep.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2svsvekms.html

JS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2hgyfvefv.html

TS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gt2tpvchnsb.html

Java: class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gt2bvoblcba.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sweek.top/Article/details/gt2qsukxixo.html

Ruby: class Admin < User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dcbqxgfz.html

C#:   class Admin : User {}
来源：http://dali.zdqjudy.top/Article/details/gt2icjqgtea.html

[G06] 重写方法
来源：http://dali.hongshengwenyu.top/Article/details/gt2swnkdeuz.html

Py:   def greet(self): return "admin"
来源：http://dali.guannengcc.top/Article/details/gt2nlraqpjc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gt2jatebmgw.html

JS:   greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2aalooqfb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gt2vexuqbji.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gt2etxrztnh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tanke756.top/Article/details/gt2ogknhlms.html

Ruby: def greet; "admin"; end
来源：http://dali.jqgufenzy.top/Article/details/gt2msapigcw.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgfzy.top/Article/details/gt2dimuzllh.html

[G07] 调用父类方法
来源：http://dali.meibo888.top/Article/details/gt2etogufag.html

Py:   super().greet()
来源：http://dali.guannengcc.top/Article/details/gt2hmuitjqq.html

PHP:  parent::greet();
来源：http://dali.shuidangran.top/Article/details/gt2zbieocyq.html

JS:   super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gt2ytivfqkc.html

TS:   super.greet();
来源：http://dali.jqgfzy.top/Article/details/gt2rloywugs.html

Java: super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gt2hamgpqij.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hfpthk.cn/Article/details/gt2upfsehpt.html

Ruby: super
来源：http://dali.jinqigfzy.top/Article/details/gt2oueyefpy.html

C#:   base.Greet();
来源：http://dali.shzxlz.cn/Article/details/gt2sogmobnl.html

[G08] 静态方法与属性
来源：http://dali.chenjidiqi.icu/Article/details/gt2zsflqmij.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sxryk.cn/Article/details/gt2zqtjnfha.html

PHP:  public static function f() {}
来源：http://dali.andypj.xyz/Article/details/gt2ioxsmqqy.html

JS:   static f() {}
来源：http://dali.ybcxt.top/Article/details/gt2ftthxodq.html

TS:   static f(): void {}
来源：http://dali.ybcxt.top/Article/details/gt2bsmnhhys.html

Java: static void f() {}
来源：http://dali.havefunace.top/Article/details/gt2kadxpxdp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zycfv.cn/Article/details/gt2gqygucuu.html

Ruby: def self.f; end
来源：http://dali.birdmap.top/Article/details/gt2rlxdafqa.html

C#:   public static void F() {}
来源：http://dali.svipenyu.cn/Article/details/gt2jwahzjcl.html

[G09] 接口 / 抽象类
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tlhewqxk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shangyingyoupin.top/Article/details/gt2ofeynezs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yanxiufei.cn/Article/details/gt2rwurdkel.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.dianchejie.cn/Article/details/gt2ttzvavad.html

TS:   interface Shape { area(): number; }
来源：http://dali.sufxvd.cn/Article/details/gt2ihqphygz.html

Java: interface Shape { double area(); }
来源：http://dali.ivvv.top/Article/details/gt2axjksdej.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuanzx.com/Article/details/gt2bkwnqvgi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cdnleiting.top/Article/details/gt2vkyzzxcg.html

C#:   interface IShape { double Area(); }
来源：http://dali.hysaishi.cn/Article/details/gt2oxwauzxk.html

[G10] 访问控制
来源：http://dali.zhiwuduotai.top/Article/details/gt2rxlrwowu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.pycfn.com/Article/details/gt2ssvtwkts.html

PHP:  public / protected / private
来源：http://dali.fengsongda.top/Article/details/gt2ohzyscgi.html

JS:   #private 字段；其余公开
来源：http://dali.daxiang520.top/Article/details/gt2lsejkstv.html


<!-- 参考信息 -->