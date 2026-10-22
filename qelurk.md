代发 wailian999

TS:   "7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtngwovblf.html

Java: String.format("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gtckyxdiwv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gtldmnrasw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gtwioeikyy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sysykeji.top/Article/details/gtyixfafol.html

[E11] 反转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtudxvgavf.html

Py:   s[::-1]
来源：http://dali.cheryme.top/Article/details/gtpfrydlmu.html

PHP:  strrev($s);
来源：http://dali.yj20258888.top/Article/details/gtjuhxbchb.html

JS:   [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gtmviflyta.html

TS:   [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtwqacycxr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hnqzz.top/Article/details/gttzhzmjtj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.haohaochexian.top/Article/details/gthllxopds.html

Ruby: s.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbxiamzg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yueranfly.top/Article/details/gtylsucdcu.html

[E12] 统计某字符出现次数
来源：http://dali.ydzc1.top/Article/details/gttgvkmyfo.html

Py:   s.count("a")
来源：http://dali.sysykeji.top/Article/details/gtaqrnuyrd.html

PHP:  substr_count($s, "a");
来源：http://dali.redwolf501.top/Article/details/gttqmkycpz.html

JS:   s.split("a").length - 1
来源：http://dali.guowangkeji.top/Article/details/gtxhskyryd.html

TS:   s.split("a").length - 1
来源：http://dali.0kj1m.cn/Article/details/gtqhbnttfw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shuidangran.top/Article/details/gtnxodwwuy.html

Go:   strings.Count(s, "a")
来源：http://dali.jyoumei.cn/Article/details/gtuxmmpivd.html

Ruby: s.count("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvvjvcyzn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pycfn.com/Article/details/gtxiggouev.html

[E13] 逐字符遍历
来源：http://dali.gogol.net.cn/Article/details/gtekejcmzu.html

Py:   for ch in s: print(ch)
来源：http://dali.daxiang520.top/Article/details/gtnjifzcez.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cucudq.cn/Article/details/gthilxjila.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtrghjkrnp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cucudq.cn/Article/details/gtdxpgvrtd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tian-w.cn/Article/details/gtqgvwrdqf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sysykeji.top/Article/details/gtdsaeohib.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.iojbl.cn/Article/details/gteusqhswu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.c1oappe.top/Article/details/gtvvylimkh.html

[E14] URL 编码与 Base64
来源：http://dali.yuxming.cn/Article/details/gtbdxidukl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.fengsongda.top/Article/details/gtbqimdtgm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.mhx1999.top/Article/details/gtgvhxrxla.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xziqi.cn/Article/details/gtsmxezesi.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj20258.top/Article/details/gtgdktrbna.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shzxlz.cn/Article/details/gtjpggvexj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nanxinkj.top/Article/details/gtvicxejcs.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenjidiqi.icu/Article/details/gtrmjegivz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gotoacloud.top/Article/details/gtdspipjnc.html

[E15] HTML 转义 / 反转义
来源：http://dali.sxryk.cn/Article/details/gtmbcvxgfa.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ivvv.top/Article/details/gtyjtjdtuh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gzhubu.top/Article/details/gtamxadpky.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tanke756.top/Article/details/gttnxpzesn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zdqjudy.top/Article/details/gthzndkkbi.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.andypj.xyz/Article/details/gtlbpfzojz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yongpay.top/Article/details/gtvkaiqvdf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gotoacloud.top/Article/details/gttzmdtevj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shzxlz.cn/Article/details/gtpzmgedvo.html

[E16] 数字千分位
来源：http://dali.zhongyouzk.top/Article/details/gtvnlejcbk.html

Py:   f"{1234567:,}"
来源：http://dali.yueranfly.top/Article/details/gtszisaurf.html

PHP:  number_format(1234567);
来源：http://dali.yuanzhike.top/Article/details/gtsjihcxzw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.svipenyu.cn/Article/details/gtmgmgtolv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258.top/Article/details/gtzsvhurox.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdsamhfe.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yuxming.cn/Article/details/gtkijmbojg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.snrcjt.cn/Article/details/gtfwmeallf.html

C#:   1234567.ToString("N0")
来源：http://dali.mhx1999.top/Article/details/gtcjtociqb.html

[E17] 首字母大写
来源：http://dali.snrcjt.cn/Article/details/gtshrgaquv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yueranfly.top/Article/details/gtxpyehzqy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj20258.top/Article/details/gtixqbbhze.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gtejpejayp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gtkhfktdxy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.iojbl.cn/Article/details/gtzpbvsayi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhongyouzk.top/Article/details/gttbmaiqcl.html

Ruby: s.capitalize
来源：http://dali.haohaochexian.top/Article/details/gtoyglkvys.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hammf.cn/Article/details/gtuhnzouvf.html

[E18] 模板占位符替换
来源：http://dali.hammf.cn/Article/details/gtvkvtkktk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tianlin.xyz/Article/details/gtpyfywuln.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jqgfzy.top/Article/details/gthubbafbj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtfajevixv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtyifiryci.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ivvv.top/Article/details/gttegdqsix.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cheryme.top/Article/details/gtqkuxwbbo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shzxlz.cn/Article/details/gtkdkhetvp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.guowangkeji.top/Article/details/gtbxovlpyo.html

[E19] 多行文本按行拆分
来源：http://dali.ivvv.top/Article/details/gtqoqwlaea.html

Py:   s.splitlines()
来源：http://dali.hfpthk.cn/Article/details/gttzbltbhy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtholhwwif.html

JS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gtzwcxbxnu.html

TS:   s.split(/\r?\n/)
来源：http://dali.jqgfzy.top/Article/details/gtflwrtxcu.html

Java: s.lines().toList()
来源：http://dali.yj20258888.top/Article/details/gtqmykdguk.html

Go:   strings.Split(s, "\n")
来源：http://dali.bjfxy.top/Article/details/gtznoiyvqz.html

Ruby: s.lines
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqckhzsxw.html

C#:   s.Split('\n')
来源：http://dali.tian-w.cn/Article/details/gtgnrbogaa.html

[E20] 判断字符串是否为空
来源：http://dali.jlsjyb.cn/Article/details/gtcvcpwdqf.html

Py:   if not s:
来源：http://dali.ydzc1.top/Article/details/gtpqdyzmlz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhaomingkeji.xyz/Article/details/gtatbtnmsv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hfpthk.cn/Article/details/gthtyjrwsy.html

TS:   if (s === "") {}
来源：http://dali.zhoulong.xyz/Article/details/gtleuffjpj.html

Java: if (s.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdxczimm.html

Go:   if s == "" {}
来源：http://dali.shzxlz.cn/Article/details/gtguhmrjny.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gttwabnlvu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.vqdsnc.cn/Article/details/gtlqmxufmw.html

[E21] 超长截断加省略号
来源：http://dali.redwolf501.top/Article/details/gtdizqqytj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.mhx1999.top/Article/details/gtpbndurqz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtwyrnongk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtmihrcupn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtscjkzjos.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gtadtyjkst.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.316326.xyz/Article/details/gtqznvbfls.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtsnnoolwx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtbobbpyuw.html

[E22] 字节长度与字符长度
来源：http://dali.fzhhl.top/Article/details/gteefbrxue.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.meibo888.top/Article/details/gtgthlexbk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gttffywwsj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.9152youxi.cn/Article/details/gtzigfphpd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pycfn.com/Article/details/gtqwocgpaf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.kuanghao11.cn/Article/details/gtdfydtpdg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinghuilouyu.cn/Article/details/gtjsgdvdxa.html

Ruby: s.bytesize;  s.length
来源：http://dali.andypj.xyz/Article/details/gtsghszord.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xylfe.cn/Article/details/gtxzazmtgl.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtcrsclqre.html

F. 文件与目录
来源：http://dali.yj20258.top/Article/details/gtveoukmnn.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxfynnuw.html

[F01] 读取整个文件
来源：http://dali.smart0.xyz/Article/details/gtemptmwvr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenzaomai.com/Article/details/gtbmadfpfy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtwojtcdxs.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ehwqpu.com/Article/details/gtyzvfiomi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gttljqrdxq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtlnbnbwlj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgufenzy.top/Article/details/gtjgpfpitg.html

Ruby: File.read("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtcnkmtxjd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.havefunace.top/Article/details/gtdunldduo.html

[F02] 逐行读取文件
来源：http://dali.smart0.xyz/Article/details/gtmuggygxj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ivvv.top/Article/details/gtpniimiua.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj20258888.top/Article/details/gtqqwtxlsd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jlsjyb.cn/Article/details/gtjgfxxven.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ybcxt.top/Article/details/gtqlfofxit.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ydzc1.top/Article/details/gtgbxgimud.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cdnleiting.top/Article/details/gtxuigqfwj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.dianchejie.cn/Article/details/gtbggvfyau.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nwbrower.top/Article/details/gtbievkfgh.html

[F03] 写入文件（覆盖）
来源：http://dali.kuanghao11.cn/Article/details/gtpjbjgsvh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yanxiufei.cn/Article/details/gtuqayjwdm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gtgjmusziz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gticknqaug.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gtfljuvudx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gaohongyu789.top/Article/details/gtfnnoaikz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ydzc1.top/Article/details/gtrcupofwp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangdashe.top/Article/details/gtfxidvvot.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gtuclryhrd.html

[F04] 追加写入文件
来源：http://dali.316326.xyz/Article/details/gtnywfnbsp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhengqikj.top/Article/details/gtwiewtywo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.316326.xyz/Article/details/gtucmbhdoe.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gthnrekhnx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtmyrflsmc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gtjmwjaprj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtmgpdveas.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tianlin.xyz/Article/details/gtufpyqcwo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hysaishi.cn/Article/details/gtepfacznn.html

[F05] 判断文件或目录是否存在
来源：http://dali.daria6918.cn/Article/details/gtvaxhzjzr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.pycfn.com/Article/details/gtdtwtdfak.html

PHP:  file_exists("a.txt");
来源：http://dali.havefunace.top/Article/details/gtkzrfttqx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtcvvyczyv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtsahmurmz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtvhwhhvax.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnqzz.top/Article/details/gtiuoardoz.html

Ruby: File.exist?("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtqsyhekqi.html

C#:   File.Exists("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtvugvbkkm.html

[F06] 删除文件
来源：http://dali.hfpthk.cn/Article/details/gttcuimqfa.html

Py:   os.remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtpxosqtfm.html

PHP:  unlink("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtjgkntwkz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtpnxolpap.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtkpfhxvau.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtyiglytgz.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdwvqkzm.html

Ruby: File.delete("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtorpwrpdq.html

C#:   File.Delete("a.txt");
来源：http://dali.yonumen.top/Article/details/gtqnrjxirq.html

[F07] 创建目录（含多级）
来源：http://dali.svipenyu.cn/Article/details/gtyrltmzox.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zycfv.cn/Article/details/gtwlxctwxr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ivvv.top/Article/details/gtflhmnsgo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gtdtdvpjzg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gtztsfwqhd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.0kj1m.cn/Article/details/gtxrtnecog.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.bjfxy.top/Article/details/gtncmaslcz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sxryk.cn/Article/details/gtyhgwnrhf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gaohongyu789.top/Article/details/gttyjdukpi.html

[F08] 遍历目录
来源：http://dali.shzxlz.cn/Article/details/gtudxbvgpl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.haohaochexian.top/Article/details/gtlfqbzqnc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.smart0.xyz/Article/details/gtecldqmez.html

JS:   fs.readdirSync("dir")
来源：http://dali.aizwys.cn/Article/details/gtlxcibesb.html

TS:   fs.readdirSync("dir")
来源：http://dali.fengsongda.top/Article/details/gtihydrwcv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbxsijpi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtbdhajlpq.html

Ruby: Dir.children("dir")
来源：http://dali.cheryme.top/Article/details/gtfjkfpwup.html

C#:   Directory.GetFiles("dir")
来源：http://dali.snrcjt.cn/Article/details/gtllzidaqr.html

[F09] 获取文件大小
来源：http://dali.gogol.net.cn/Article/details/gtphuvxboq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtyyrgnuug.html

PHP:  filesize("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtzbmxupzi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zycfv.cn/Article/details/gtbctohbbs.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gtziqesplv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtghvfypth.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbhtfurjo.html

Ruby: File.size("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtetfwrszr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj20258.top/Article/details/gtmtpoxqin.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258.top/Article/details/gtfuauwwse.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtxypjwljq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hnqzz.top/Article/details/gtmvxbbbqx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtunlmmimj.html

TS:   path.extname("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtrinybyjc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangdashe.top/Article/details/gtsrvgpuni.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtfalxwnpc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gttaqiewox.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtdojpaifn.html

[F11] 复制与移动文件
来源：http://dali.ydzc1.top/Article/details/gtcquwkhdg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtuowhncok.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zycfv.cn/Article/details/gtmyrbyfcp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtirxnweke.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gttaiytzjb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtpvzdrxud.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tianlin.xyz/Article/details/gtlkckgkwx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtwrcpmvbl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.9152youxi.cn/Article/details/gtoqegrowb.html

[F12] CSV 读写
来源：http://dali.xuetiantiany.cn/Article/details/gtmjurcyag.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cucudq.cn/Article/details/gtwaqrpalk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jqgufenzy.top/Article/details/gtwhwvgsjv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuxming.cn/Article/details/gtamcuduyj.html

TS:   // 同上
来源：http://dali.xylfe.cn/Article/details/gtnnbzxwja.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yangfankeji.com/Article/details/gtfzymyodg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhengqikj.top/Article/details/gtcugqcdxk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gogol.net.cn/Article/details/gtedjsvxxf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jqgfzy.top/Article/details/gtfyrdkhij.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtksgdmmjy.html

G. 面向对象
来源：http://dali.nanxuanxn.top/Article/details/gtjrmkaras.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtjprfakpa.html

[G01] 定义类
来源：http://dali.316326.xyz/Article/details/gtuhdcolzb.html

Py:   class User: pass
来源：http://dali.jyoumei.cn/Article/details/gtmgcwzqbu.html

PHP:  class User {}
来源：http://dali.hywenlv.cn/Article/details/gtvumqwice.html

JS:   class User {}
来源：http://dali.cucudq.cn/Article/details/gtejmwuzir.html

TS:   class User { name: string = ""; }
来源：http://dali.zdqjudy.top/Article/details/gtwxbsmaks.html

Java: class User {}
来源：http://dali.hywenlv.cn/Article/details/gtwbnexukg.html

Go:   type User struct { Name string }
来源：http://dali.nwbrower.top/Article/details/gtvaruamvd.html

Ruby: class User; end
来源：http://dali.yvedp.cn/Article/details/gtybljvsci.html

C#:   class User {}
来源：http://dali.yj20258.top/Article/details/gtfisvrtuh.html

[G02] 构造函数
来源：http://dali.gogol.net.cn/Article/details/gtzhafwksj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xylfe.cn/Article/details/gtvcziooif.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aibaodan.cn/Article/details/gtayaiinwm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gtojubngph.html

TS:   constructor(public name: string) {}
来源：http://dali.zdqjudy.top/Article/details/gtmmliolbx.html

Java: User(String name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtfpknqxyo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhiwuduotai.top/Article/details/gtixckrvpg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cdnleiting.top/Article/details/gtxjhefpfq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xziqi.cn/Article/details/gtxhkywhoz.html

[G03] 实例属性
来源：http://dali.nanxinkj.top/Article/details/gtwlhhgmgk.html

Py:   self.name = "x"
来源：http://dali.andypj.xyz/Article/details/gtnzyoquex.html

PHP:  public string $name = "x";
来源：http://dali.ehwqpu.com/Article/details/gtycbeujrr.html

JS:   this.name = "x";
来源：http://dali.hywenlv.cn/Article/details/gtcgdwzwzv.html

TS:   name: string = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gthoukcrvt.html

Java: private String name;
来源：http://dali.xylfe.cn/Article/details/gtyldcfquh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gogol.net.cn/Article/details/gtdvabwmpe.html

Ruby: @name = "x"
来源：http://dali.0kj1m.cn/Article/details/gtiqdikhzn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.havefunace.top/Article/details/gtxrkzszbp.html

[G04] 定义方法
来源：http://dali.zdqjudy.top/Article/details/gtpvrvwffl.html

Py:   def greet(self): return self.name
来源：http://dali.yonumen.top/Article/details/gtxaxccjpg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtbsyhxgzc.html

JS:   greet() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtfvkgfztx.html

TS:   greet(): string { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvpcrmimx.html

Java: String greet() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtrrxqcquz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gttjdgxcon.html

Ruby: def greet; @name; end
来源：http://dali.iojbl.cn/Article/details/gtjigvoebh.html

C#:   public string Greet() => Name;
来源：http://dali.zhengqikj.top/Article/details/gtkndswzmz.html

[G05] 继承
来源：http://dali.havefunace.top/Article/details/gtvtjxylse.html

Py:   class Admin(User): pass
来源：http://dali.chenjidiqi.icu/Article/details/gthmanjcdz.html

PHP:  class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtprckwozk.html

JS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtyytszpct.html

TS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtxiiiuidq.html

Java: class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtmakwizok.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yangfankeji.com/Article/details/gtrzuebtjn.html

Ruby: class Admin < User; end
来源：http://dali.yangfankeji.com/Article/details/gtjzflhtfe.html

C#:   class Admin : User {}
来源：http://dali.pycfn.com/Article/details/gtzoxfablw.html

[G06] 重写方法
来源：http://dali.pengpengdd.cyou/Article/details/gtedynudqu.html

Py:   def greet(self): return "admin"
来源：http://dali.xziqi.cn/Article/details/gtseygfxcp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtwfkocqol.html

JS:   greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtwfdnfucr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtomcpqpzb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtxctxnzwt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hysaishi.cn/Article/details/gtpvmuweba.html

Ruby: def greet; "admin"; end
来源：http://dali.zycfv.cn/Article/details/gtvfxdygit.html

C#:   public override string Greet() => "admin";
来源：http://dali.kuanghao11.cn/Article/details/gtnyllowrs.html

[G07] 调用父类方法
来源：http://dali.aizwys.cn/Article/details/gtqwhtwzny.html

Py:   super().greet()
来源：http://dali.sxryk.cn/Article/details/gtlkyuasuz.html

PHP:  parent::greet();
来源：http://dali.xinyue.icu/Article/details/gtfgmpugto.html

JS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gtuplirfih.html

TS:   super.greet();
来源：http://dali.hywenlv.cn/Article/details/gtoccuecrj.html

Java: super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtfkbzsslm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daria6918.cn/Article/details/gtftwixmlr.html

Ruby: super
来源：http://dali.kuanghao11.cn/Article/details/gtowcdwbql.html

C#:   base.Greet();
来源：http://dali.yj202588.top/Article/details/gtprjamobl.html

[G08] 静态方法与属性
来源：http://dali.hongshengwenyu.top/Article/details/gtkibbokvg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.c1oappe.top/Article/details/gtxytgskih.html

PHP:  public static function f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtirykcclw.html

JS:   static f() {}
来源：http://dali.iojbl.cn/Article/details/gtvplucevv.html

TS:   static f(): void {}
来源：http://dali.nanxinkj.top/Article/details/gtwrcmpvii.html

Java: static void f() {}
来源：http://dali.fengsongda.top/Article/details/gtvuyikrko.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hysaishi.cn/Article/details/gtyrevnfao.html

Ruby: def self.f; end
来源：http://dali.316326.xyz/Article/details/gtcnhghjrk.html

C#:   public static void F() {}
来源：http://dali.fengsongda.top/Article/details/gtuoftvjga.html

[G09] 接口 / 抽象类
来源：http://dali.chenlongwang.top/Article/details/gtipmajsbn.html


<!-- 参考信息 -->