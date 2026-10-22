代发 wailian999

JS:   [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtkmhmrmeq.html

TS:   [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gtnvufpicg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhiwuduotai.top/Article/details/gtnrpgizuv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ybcxt.top/Article/details/gtooonzxdf.html

Ruby: s.reverse
来源：http://dali.xziqi.cn/Article/details/gtlooivlpm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tianlin.xyz/Article/details/gthkthtgks.html

[E12] 统计某字符出现次数
来源：http://dali.aizwys.cn/Article/details/gtpnqlwrpp.html

Py:   s.count("a")
来源：http://dali.jqgfzy.top/Article/details/gtjqocpteg.html

PHP:  substr_count($s, "a");
来源：http://dali.aizwys.cn/Article/details/gtteqijvuz.html

JS:   s.split("a").length - 1
来源：http://dali.jiagoushi.top/Article/details/gtvflpppvv.html

TS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gtfsextomi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhongyouzk.top/Article/details/gtvprnjzvo.html

Go:   strings.Count(s, "a")
来源：http://dali.svipenyu.cn/Article/details/gtzpwtrbtg.html

Ruby: s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gtqomnfsxf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.vqdsnc.cn/Article/details/gtrilwbfno.html

[E13] 逐字符遍历
来源：http://dali.sysykeji.top/Article/details/gtyvrsepow.html

Py:   for ch in s: print(ch)
来源：http://dali.dianchejie.cn/Article/details/gtixlgmvxa.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shzxlz.cn/Article/details/gtprhiftyk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258.top/Article/details/gtcousjdew.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yvedp.cn/Article/details/gtxvhqlqmo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jyoumei.cn/Article/details/gtbunhjqpf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shangyingyoupin.top/Article/details/gteppfwkoc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.c1oappe.top/Article/details/gtprtfhhrs.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgeodhtde.html

[E14] URL 编码与 Base64
来源：http://dali.yj20258888.top/Article/details/gtyxtwmqxe.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yueranfly.top/Article/details/gtmqxwonjb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.c1oappe.top/Article/details/gtywgnwgwd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tanke756.top/Article/details/gtuwergwsg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.mhx1999.top/Article/details/gtwjyssxfb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xziqi.cn/Article/details/gtciyblhqm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.daria6918.cn/Article/details/gtqrjmekrk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hongshengwenyu.top/Article/details/gtrfxlaosy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmmzgjxv.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhixingplan.top/Article/details/gtpgqbhils.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fzhhl.top/Article/details/gtuvrtjsmy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangshuangyany.cn/Article/details/gttttsijxv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.bjfxy.top/Article/details/gtfsnudedq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xinyue.icu/Article/details/gtgxisprfb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cheryme.top/Article/details/gtktbbibpv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gzhubu.top/Article/details/gtvvbqaozj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sweek.top/Article/details/gtolwnokmz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnqzz.top/Article/details/gtahjoqjor.html

[E16] 数字千分位
来源：http://dali.0kj1m.cn/Article/details/gtyuygppqh.html

Py:   f"{1234567:,}"
来源：http://dali.chenjidiqi.icu/Article/details/gtmjkxuvkr.html

PHP:  number_format(1234567);
来源：http://dali.ivvv.top/Article/details/gtfeysrrab.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgufenzy.top/Article/details/gtmvpjqbav.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuanzx.com/Article/details/gtojkolbaq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.0kj1m.cn/Article/details/gtftvdpkif.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ivvv.top/Article/details/gtvfetmmmw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ybcxt.top/Article/details/gtetbhmmwd.html

C#:   1234567.ToString("N0")
来源：http://dali.jqgfzy.top/Article/details/gtdkclpamp.html

[E17] 首字母大写
来源：http://dali.bjfxy.top/Article/details/gtzuwzdpaw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhoulong.xyz/Article/details/gtmlfivocv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.guowangkeji.top/Article/details/gtymcjjvml.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dianchejie.cn/Article/details/gtchwqqsdc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yvedp.cn/Article/details/gtzqblfmna.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hammf.cn/Article/details/gtwiauzrsv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdpsltwlp.html

Ruby: s.capitalize
来源：http://dali.316326.xyz/Article/details/gtcayhclqd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ybcxt.top/Article/details/gtjwagpdzb.html

[E18] 模板占位符替换
来源：http://dali.cdnleiting.top/Article/details/gtmqgnjyta.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj20258888.top/Article/details/gtrvpxueyc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aibaodan.cn/Article/details/gtwusbazez.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtozlxdptu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gtceinbgcq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.316326.xyz/Article/details/gtogcgotir.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.andypj.xyz/Article/details/gttfgtsobz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxuanxn.top/Article/details/gtgojnstid.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yanxiufei.cn/Article/details/gtxqptjktr.html

[E19] 多行文本按行拆分
来源：http://dali.yongpay.top/Article/details/gtplkmrhde.html

Py:   s.splitlines()
来源：http://dali.meibo888.top/Article/details/gtpdnneeat.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtueeajovg.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gtelyyhjja.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrgjzccfk.html

Java: s.lines().toList()
来源：http://dali.hywenlv.cn/Article/details/gtshzxiwcx.html

Go:   strings.Split(s, "\n")
来源：http://dali.smart0.xyz/Article/details/gtqivhdgge.html

Ruby: s.lines
来源：http://dali.wangdashe.top/Article/details/gtfnecbcur.html

C#:   s.Split('\n')
来源：http://dali.jiagoushi.top/Article/details/gteyucepzq.html

[E20] 判断字符串是否为空
来源：http://dali.sxryk.cn/Article/details/gthwxyihxd.html

Py:   if not s:
来源：http://dali.jqgfzy.top/Article/details/gtsulwehve.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.wangdashe.top/Article/details/gtmvmcxagd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aizwys.cn/Article/details/gttpqxacmt.html

TS:   if (s === "") {}
来源：http://dali.xinyue.icu/Article/details/gtjqtbzzwp.html

Java: if (s.isEmpty()) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtwkdwgyxb.html

Go:   if s == "" {}
来源：http://dali.aibaodan.cn/Article/details/gtuazgfxbd.html

Ruby: if s.empty?
来源：http://dali.gzhubu.top/Article/details/gtomxxbvsc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nwbrower.top/Article/details/gtdekzeonx.html

[E21] 超长截断加省略号
来源：http://dali.zhongyouzk.top/Article/details/gtzzoracio.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj202588.top/Article/details/gtaiyswahc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gtnhwiodgq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtxurwerts.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtxvfiqndi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtwejbhqfi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtealqxkfe.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yonumen.top/Article/details/gtdkhtjkqi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtsidanojb.html

[E22] 字节长度与字符长度
来源：http://dali.c1oappe.top/Article/details/gthuvsfrdu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj202588.top/Article/details/gtoxhrilxz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gtkzlbcmku.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvakfioiu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtrguwbjnb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.birdmap.top/Article/details/gtudbyqvif.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.c1oappe.top/Article/details/gtjgnuvmmr.html

Ruby: s.bytesize;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtlxqjobct.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj202588.top/Article/details/gtguuszxwi.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtasnyeivn.html

F. 文件与目录
来源：http://dali.zhoulong.xyz/Article/details/gtfxadllmr.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtabvocwce.html

[F01] 读取整个文件
来源：http://dali.shangyingyoupin.top/Article/details/gtfhjigoyf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hysaishi.cn/Article/details/gtaxvpmolw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtgsaorjlk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fzhhl.top/Article/details/gtrmegsgwr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gtwapxgghy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtdfvuesbi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.pengpengdd.cyou/Article/details/gtxayxglyy.html

Ruby: File.read("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtwncacnxo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtrmnqofoq.html

[F02] 逐行读取文件
来源：http://dali.guowangkeji.top/Article/details/gtoriosoez.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.aibaodan.cn/Article/details/gtecpbhfdp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nwbrower.top/Article/details/gtkdvrioyi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtejrlitih.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtfwqngxsu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.vqdsnc.cn/Article/details/gtmhkqzjow.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.dianchejie.cn/Article/details/gtshzsqqwr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cqqwz.cn/Article/details/gthmzjgqor.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.pengpengdd.cyou/Article/details/gtvwowfpll.html

[F03] 写入文件（覆盖）
来源：http://dali.yongpay.top/Article/details/gttohnfssb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.snrcjt.cn/Article/details/gttyuvcssi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gtqszadicz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtofcjkwcw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cucudq.cn/Article/details/gtetgfomum.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tianlin.xyz/Article/details/gtwwsjaesx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.0kj1m.cn/Article/details/gtoukzshpf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jqgufenzy.top/Article/details/gtfdhyzqbl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.svipenyu.cn/Article/details/gtdrchoxvj.html

[F04] 追加写入文件
来源：http://dali.gogol.net.cn/Article/details/gtofwvsyuq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqbjjkfj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.snrcjt.cn/Article/details/gtxjyhvvex.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gtzgqenttl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pycfn.com/Article/details/gtuejsmlax.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhixingplan.top/Article/details/gtiwkubbrb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zycfv.cn/Article/details/gtqquqnbyn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhixingplan.top/Article/details/gtobgovvjl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gogol.net.cn/Article/details/gtdmzbiqbo.html

[F05] 判断文件或目录是否存在
来源：http://dali.jqgufenzy.top/Article/details/gtmcxztpei.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jianghu66.top/Article/details/gtrunhsojx.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtbehrppsf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtbtqdhrqx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtfkumldff.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtpbvgnifd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tianlin.xyz/Article/details/gticzbjngq.html

Ruby: File.exist?("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtuptltubo.html

C#:   File.Exists("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtmlezkhvn.html

[F06] 删除文件
来源：http://dali.mhx1999.top/Article/details/gtllvmvgwj.html

Py:   os.remove("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtqbdzxtig.html

PHP:  unlink("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdijoqhgi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtwkjfpymx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtyiwkihqx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtoswikqdk.html

Go:   os.Remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtdjiqeodn.html

Ruby: File.delete("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtmyszgkzq.html

C#:   File.Delete("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtizojuhho.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gtshkuefba.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.quarkkingdee.top/Article/details/gtdvwpgafs.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xylfe.cn/Article/details/gtyezdtcmt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigufen.top/Article/details/gtfmzggwfh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gtzkdnwrhx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jianghu66.top/Article/details/gtmogofuew.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenlongwang.top/Article/details/gtpqrdpcvp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cqqwz.cn/Article/details/gtvtztzmhx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hongshengwenyu.top/Article/details/gtgsgmutpq.html

[F08] 遍历目录
来源：http://dali.yongpay.top/Article/details/gtbpqzlzye.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.redwolf501.top/Article/details/gtuvcljckw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtofvqcxem.html

JS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gtlsgswyzd.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkglegkic.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hywenlv.cn/Article/details/gtjzhjdsai.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tanke756.top/Article/details/gtrynncagz.html

Ruby: Dir.children("dir")
来源：http://dali.yongpay.top/Article/details/gtjgxhahli.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xinyue.icu/Article/details/gtwemruyuo.html

[F09] 获取文件大小
来源：http://dali.shangyingyoupin.top/Article/details/gtjaychgnj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtraetnplb.html

PHP:  filesize("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtiocvdnkg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gtsvxkbgsp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gtxbvvjknf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gthxxlmsmf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigufen.top/Article/details/gtkwkzrwjl.html

Ruby: File.size("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtbiewvncq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sweek.top/Article/details/gtrnrjnnzn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xinyue.icu/Article/details/gtvmttctqt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtxahzqyav.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cheryme.top/Article/details/gtziibqtze.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gttzjltaho.html

TS:   path.extname("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtgtffokgy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yonumen.top/Article/details/gtvvnokyty.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtcljgflyi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtksvrfqnq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtdaoytggh.html

[F11] 复制与移动文件
来源：http://dali.dianchejie.cn/Article/details/gtmhifrskk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtkcgdgpak.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.iojbl.cn/Article/details/gtcwyuftxw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtwjnwmqqx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtucfvqvxw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj20258888.top/Article/details/gtlsemcppw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zycfv.cn/Article/details/gtjhvhawza.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtmheoscvn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shuidangran.top/Article/details/gtvnlobfff.html

[F12] CSV 读写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjscgftj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhiwuduotai.top/Article/details/gtbfybxynw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvgxgilt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ppjwa.cn/Article/details/gtkkorpmug.html

TS:   // 同上
来源：http://dali.hywenlv.cn/Article/details/gtysgjrxsi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ivvv.top/Article/details/gtoxrowoiy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhaomingkeji.xyz/Article/details/gtafdutfli.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhoulong.xyz/Article/details/gtckijdvzx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hfpthk.cn/Article/details/gthlwaling.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtvjqvavrj.html

G. 面向对象
来源：http://dali.yj20258888.top/Article/details/gtbaflqorf.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtwyalwkbw.html

[G01] 定义类
来源：http://dali.c1oappe.top/Article/details/gttgzduheg.html

Py:   class User: pass
来源：http://dali.zhiwuduotai.top/Article/details/gtmkauijqv.html

PHP:  class User {}
来源：http://dali.bjfxy.top/Article/details/gtgitobxif.html

JS:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gthoaipjri.html

TS:   class User { name: string = ""; }
来源：http://dali.cqqwz.cn/Article/details/gtkfzhreke.html

Java: class User {}
来源：http://dali.cqqwz.cn/Article/details/gtbhnkllha.html

Go:   type User struct { Name string }
来源：http://dali.zhengqikj.top/Article/details/gtbzeorsjp.html

Ruby: class User; end
来源：http://dali.shzxlz.cn/Article/details/gtmudplqre.html

C#:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gtjtsqzvox.html

[G02] 构造函数
来源：http://dali.snrcjt.cn/Article/details/gtdtdiapit.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtucgeyzft.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgfzy.top/Article/details/gthgdbumjo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gtfcxspben.html

TS:   constructor(public name: string) {}
来源：http://dali.jqgfzy.top/Article/details/gtdenbudvw.html

Java: User(String name) { this.name = name; }
来源：http://dali.c1oappe.top/Article/details/gtieukpocm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.0kj1m.cn/Article/details/gtvoxhmmwf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gtisvkvkkr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sysykeji.top/Article/details/gtjpnothpz.html

[G03] 实例属性
来源：http://dali.chenjidiqi.icu/Article/details/gtfwugocct.html

Py:   self.name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gtfwilihzd.html

PHP:  public string $name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtvrwwotle.html

JS:   this.name = "x";
来源：http://dali.zhengqikj.top/Article/details/gtmmjcubxu.html

TS:   name: string = "x";
来源：http://dali.jinqigufen.top/Article/details/gtpultfbte.html

Java: private String name;
来源：http://dali.shuidangran.top/Article/details/gtauqmcahx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.birdmap.top/Article/details/gtnqtipenp.html

Ruby: @name = "x"
来源：http://dali.aibaodan.cn/Article/details/gtentsucjr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xziqi.cn/Article/details/gtmyvhskzj.html

[G04] 定义方法
来源：http://dali.fzhhl.top/Article/details/gtskxexqob.html

Py:   def greet(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gtivsiviso.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gthphtttza.html

JS:   greet() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtkedxbark.html

TS:   greet(): string { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtrmnzbozm.html

Java: String greet() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gttblfitow.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gtzbtitupi.html

Ruby: def greet; @name; end
来源：http://dali.vqdsnc.cn/Article/details/gtjpvsckvj.html

C#:   public string Greet() => Name;
来源：http://dali.gogol.net.cn/Article/details/gtankzipjg.html

[G05] 继承
来源：http://dali.chenzaomai.com/Article/details/gtbjjprace.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gtnmqvvahn.html

PHP:  class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtaphzytay.html

JS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtlsyfrllt.html

TS:   class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtelhwallv.html

Java: class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtzqxgknqn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shzxlz.cn/Article/details/gtxrztfrdl.html

Ruby: class Admin < User; end
来源：http://dali.jlsjyb.cn/Article/details/gtilziodnb.html

C#:   class Admin : User {}
来源：http://dali.sweek.top/Article/details/gtuyyellsx.html

[G06] 重写方法
来源：http://dali.sysykeji.top/Article/details/gtbxqbirzs.html

Py:   def greet(self): return "admin"
来源：http://dali.yanxiufei.cn/Article/details/gtarnhzkmw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtgqggzrnf.html

JS:   greet() { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gtafiirghs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtuudqjcuv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlupozyvb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.birdmap.top/Article/details/gtxburyurc.html

Ruby: def greet; "admin"; end
来源：http://dali.ehwqpu.com/Article/details/gtcreudpfi.html

C#:   public override string Greet() => "admin";
来源：http://dali.guowangkeji.top/Article/details/gtgxzqdqny.html

[G07] 调用父类方法
来源：http://dali.mhx1999.top/Article/details/gtijfsgtlj.html

Py:   super().greet()
来源：http://dali.xuanzx.com/Article/details/gtuhxluluh.html

PHP:  parent::greet();
来源：http://dali.zhengqikj.top/Article/details/gtnceqrvob.html

JS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gtvlbuqmql.html

TS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gtgdgrihjq.html

Java: super.greet();
来源：http://dali.hywenlv.cn/Article/details/gticuycsnm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tianlin.xyz/Article/details/gtlgktgrqk.html

Ruby: super
来源：http://dali.ybcxt.top/Article/details/gtdnrezahm.html

C#:   base.Greet();
来源：http://dali.chenlongwang.top/Article/details/gtypwlznnv.html

[G08] 静态方法与属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfvkyzvxv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nwbrower.top/Article/details/gtsjzfpkvy.html

PHP:  public static function f() {}
来源：http://dali.yj202588.top/Article/details/gtsfxfslzb.html

JS:   static f() {}
来源：http://dali.dianchejie.cn/Article/details/gtavuffyyd.html

TS:   static f(): void {}
来源：http://dali.sufxvd.cn/Article/details/gtmlbuczwu.html

Java: static void f() {}
来源：http://dali.fzhhl.top/Article/details/gtjyhnbtjm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gogol.net.cn/Article/details/gtvfvskjmx.html

Ruby: def self.f; end
来源：http://dali.jqgufenzy.top/Article/details/gtxeeijuhb.html

C#:   public static void F() {}
来源：http://dali.smart0.xyz/Article/details/gthbrujyuj.html

[G09] 接口 / 抽象类
来源：http://dali.ydzc1.top/Article/details/gtviizepxl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hywenlv.cn/Article/details/gtdffkjzye.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jyoumei.cn/Article/details/gtzowhxiwf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hywenlv.cn/Article/details/gthtgkkdij.html

TS:   interface Shape { area(): number; }
来源：http://dali.yuanzhike.top/Article/details/gtdfapgmky.html

Java: interface Shape { double area(); }
来源：http://dali.sysykeji.top/Article/details/gtsreqjuzx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhssbybu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hywenlv.cn/Article/details/gtsogkgkza.html

C#:   interface IShape { double Area(); }
来源：http://dali.yvedp.cn/Article/details/gtfygyzpzr.html


<!-- 参考信息 -->