代发 wailian999

Go:   strings.Join(items, ",")
来源：http://dali.snrcjt.cn/Article/details/gtngjehcqx.html

Ruby: items.join(",")
来源：http://dali.shuidangran.top/Article/details/gtnvqyzmjn.html

C#:   string.Join(",", items)
来源：http://dali.shuidangran.top/Article/details/gtujxrfggp.html

[E09] 去除所有空白字符
来源：http://dali.bjfxy.top/Article/details/gtqdfooldm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.316326.xyz/Article/details/gtimpnxmit.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.iojbl.cn/Article/details/gthjkcslfl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ydzc1.top/Article/details/gtgapsrjkr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ydzc1.top/Article/details/gtxupeudhr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.nanxuanxn.top/Article/details/gtldwellft.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cucudq.cn/Article/details/gtlljglfxu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhengqikj.top/Article/details/gtsvlgreio.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.mhx1999.top/Article/details/gtfquuxvzx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jianghu66.top/Article/details/gtqlxqttie.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nwbrower.top/Article/details/gtpmmzpiks.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.daxiang520.top/Article/details/gttenrbnhk.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelfrwqxp.html

TS:   "7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gtvcmefhtp.html

Java: String.format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gtuhqviqsv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gtxjxqzhhm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaopctdwe.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sufxvd.cn/Article/details/gtytgeloec.html

[E11] 反转字符串
来源：http://dali.dashuyun.cn/Article/details/gtwipqlqdn.html

Py:   s[::-1]
来源：http://dali.andypj.xyz/Article/details/gtrdzqiltn.html

PHP:  strrev($s);
来源：http://dali.hywenlv.cn/Article/details/gtxfxrutyw.html

JS:   [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gtialcqumc.html

TS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtwgkmpfhi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.9152youxi.cn/Article/details/gtutrzzxzh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.aizwys.cn/Article/details/gtgvqmupyx.html

Ruby: s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtlaiyaviq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xuetiantiany.cn/Article/details/gtwlardura.html

[E12] 统计某字符出现次数
来源：http://dali.316326.xyz/Article/details/gtkkfcrzom.html

Py:   s.count("a")
来源：http://dali.yangfankeji.com/Article/details/gtbkmcgbla.html

PHP:  substr_count($s, "a");
来源：http://dali.zhoulong.xyz/Article/details/gtlksqpdvo.html

JS:   s.split("a").length - 1
来源：http://dali.chenzaomai.com/Article/details/gtjfvuknmi.html

TS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gteibvdrkr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jianghu66.top/Article/details/gtgkhxlxaf.html

Go:   strings.Count(s, "a")
来源：http://dali.xylfe.cn/Article/details/gtkqjryyil.html

Ruby: s.count("a")
来源：http://dali.zycfv.cn/Article/details/gtzwhjvwip.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jqgfzy.top/Article/details/gtirlrczza.html

[E13] 逐字符遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzdnxchzi.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgfzy.top/Article/details/gtezuyizun.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yongpay.top/Article/details/gttgwgvrrq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangdashe.top/Article/details/gtkpwxjlmg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gtltkvqnmk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxlybsvkj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.aibaodan.cn/Article/details/gtnulihubr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinqigufen.top/Article/details/gtfskysacn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.iojbl.cn/Article/details/gtpkdgsaee.html

[E14] URL 编码与 Base64
来源：http://dali.fzhhl.top/Article/details/gtgpkyqpnm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhiwuduotai.top/Article/details/gtqythpgly.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ivvv.top/Article/details/gtujmuizym.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenjidiqi.icu/Article/details/gtipeonmmc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nwbrower.top/Article/details/gtftrmvuom.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sysykeji.top/Article/details/gtbnyehblh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yonumen.top/Article/details/gtatxtzwty.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenjidiqi.icu/Article/details/gtcwyleyns.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.wangdashe.top/Article/details/gtyhxvhkxz.html

[E15] HTML 转义 / 反转义
来源：http://dali.feifeiyinyue.top/Article/details/gtjtidzdef.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ydzc1.top/Article/details/gtenuoycvr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tian-w.cn/Article/details/gtkuhbnyuu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.andypj.xyz/Article/details/gtdgmgnkvv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aizwys.cn/Article/details/gtdczxjqyp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.feifeiyinyue.top/Article/details/gtxrsiwzcg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hysaishi.cn/Article/details/gtetwmmzmf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hfpthk.cn/Article/details/gtwgcipvau.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhengqikj.top/Article/details/gtkboqpwmi.html

[E16] 数字千分位
来源：http://dali.pengpengdd.cyou/Article/details/gtchauvvgm.html

Py:   f"{1234567:,}"
来源：http://dali.hnqzz.top/Article/details/gtxyhainqq.html

PHP:  number_format(1234567);
来源：http://dali.sysykeji.top/Article/details/gtwinudmrf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ehwqpu.com/Article/details/gtsypkoccu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpccpaxv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.daxiang520.top/Article/details/gtnvnaqrue.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gtbsfbgzrx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.snrcjt.cn/Article/details/gtztpaimkf.html

C#:   1234567.ToString("N0")
来源：http://dali.ppjwa.cn/Article/details/gtrkbdcmsb.html

[E17] 首字母大写
来源：http://dali.xylfe.cn/Article/details/gtmmcmrdmp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnqzz.top/Article/details/gtwuwhlhgx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.fengsongda.top/Article/details/gtcfyaehth.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yvedp.cn/Article/details/gtzsskybvn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tian-w.cn/Article/details/gtenkozosw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gogol.net.cn/Article/details/gtaoapoxwo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gtqaewhxzr.html

Ruby: s.capitalize
来源：http://dali.shuidangran.top/Article/details/gtwnjckjay.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hysaishi.cn/Article/details/gtzqolhdxc.html

[E18] 模板占位符替换
来源：http://dali.cdnleiting.top/Article/details/gtgqwqptji.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.daria6918.cn/Article/details/gtircbwgit.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.guowangkeji.top/Article/details/gtsroaxmpx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gtvwfrvxzf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gtltahcqlx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtajbvcjlj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtxahlmzql.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xziqi.cn/Article/details/gtbnunjzju.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.vqdsnc.cn/Article/details/gtoueofxao.html

[E19] 多行文本按行拆分
来源：http://dali.zycfv.cn/Article/details/gtzjovvhsw.html

Py:   s.splitlines()
来源：http://dali.cdnleiting.top/Article/details/gtrostlsan.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pycfn.com/Article/details/gtzloucvlg.html

JS:   s.split(/\r?\n/)
来源：http://dali.ybcxt.top/Article/details/gthljgpjdl.html

TS:   s.split(/\r?\n/)
来源：http://dali.gaohongyu789.top/Article/details/gtblucckay.html

Java: s.lines().toList()
来源：http://dali.9152youxi.cn/Article/details/gtxlqrkuch.html

Go:   strings.Split(s, "\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtfxttazbh.html

Ruby: s.lines
来源：http://dali.xziqi.cn/Article/details/gtnypdgtll.html

C#:   s.Split('\n')
来源：http://dali.yj20258888.top/Article/details/gthmzebocv.html

[E20] 判断字符串是否为空
来源：http://dali.yangfankeji.com/Article/details/gtkmlkzsed.html

Py:   if not s:
来源：http://dali.shzxlz.cn/Article/details/gtnqmcnswk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gtjpmgjlka.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hnxiangtu.top/Article/details/gtepccotns.html

TS:   if (s === "") {}
来源：http://dali.9152youxi.cn/Article/details/gtajhvhrzy.html

Java: if (s.isEmpty()) {}
来源：http://dali.cdnleiting.top/Article/details/gtrlwzvjth.html

Go:   if s == "" {}
来源：http://dali.yvedp.cn/Article/details/gtbwiumnco.html

Ruby: if s.empty?
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyikrurrm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yvedp.cn/Article/details/gtofrrtucp.html

[E21] 超长截断加省略号
来源：http://dali.snrcjt.cn/Article/details/gtzuzgyqtb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj20258888.top/Article/details/gtijvjrufr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gthmnndxno.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtwylnanio.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtjzsixodk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gttgtxuevh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.pengpengdd.cyou/Article/details/gtvzmssfdu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gtikwahjix.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtqeednnqt.html

[E22] 字节长度与字符长度
来源：http://dali.zhixingplan.top/Article/details/gtahqozjfl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.pycfn.com/Article/details/gthncigpsg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gtcwdizxos.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gtllcgeoog.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daria6918.cn/Article/details/gtlruueslw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ehwqpu.com/Article/details/gtxucsbqfq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gtmsfsqdsh.html

Ruby: s.bytesize;  s.length
来源：http://dali.havefunace.top/Article/details/gtbzcjmjkk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gtefafmyha.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtfyusodsj.html

F. 文件与目录
来源：http://dali.feifeiyinyue.top/Article/details/gteseelfpe.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtzaqgijyq.html

[F01] 读取整个文件
来源：http://dali.yj20258888.top/Article/details/gtrbcotxif.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jianghu66.top/Article/details/gtnjsioqag.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtwpvgwdyu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gogol.net.cn/Article/details/gtkussjdey.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqceomrvl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqcbbxtw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenzaomai.com/Article/details/gtlvxphmfv.html

Ruby: File.read("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtokxjtvth.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtndsclxeg.html

[F02] 逐行读取文件
来源：http://dali.hongshengwenyu.top/Article/details/gtwfwmaoxg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxinkj.top/Article/details/gtrmtvaptz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cdnleiting.top/Article/details/gtbyiikzul.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tianlin.xyz/Article/details/gtymnsdtfu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tianlin.xyz/Article/details/gtkraqpihu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gtnoeufkls.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwcetqay.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangtech.top/Article/details/gtarulgsiq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxuanxn.top/Article/details/gtbdvrushd.html

[F03] 写入文件（覆盖）
来源：http://dali.birdmap.top/Article/details/gttltmvnnx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tanke756.top/Article/details/gttpwmadtk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shuidangran.top/Article/details/gtuzxukifb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gtiinwzmmi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gteabaammb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.svipenyu.cn/Article/details/gtokxyqkwi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jiagoushi.top/Article/details/gtocgrtwxa.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cashguo.top/Article/details/gtnqxzitld.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.316326.xyz/Article/details/gtyssldpkw.html

[F04] 追加写入文件
来源：http://dali.jyoumei.cn/Article/details/gtznwejfzr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tanke756.top/Article/details/gtdizkolan.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jianghu66.top/Article/details/gtnhhiznyw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.bjfxy.top/Article/details/gthyddlujb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shuidangran.top/Article/details/gtdrmipbxj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hongshengwenyu.top/Article/details/gtrjfwgzwe.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtiwlbdsrp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ppjwa.cn/Article/details/gtpaquezib.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shangyingyoupin.top/Article/details/gtyqjtbzzf.html

[F05] 判断文件或目录是否存在
来源：http://dali.daria6918.cn/Article/details/gtgkwrdqbi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fzhhl.top/Article/details/gteylnkxhh.html

PHP:  file_exists("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtyfjggfdc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gthpymfmzu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtclwfypkh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtsodblalf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hywenlv.cn/Article/details/gtrcypxmod.html

Ruby: File.exist?("a.txt")
来源：http://dali.havefunace.top/Article/details/gtbdpqvseg.html

C#:   File.Exists("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtogfluoru.html

[F06] 删除文件
来源：http://dali.zhoulong.xyz/Article/details/gtzhszszmw.html

Py:   os.remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtmsxhzrst.html

PHP:  unlink("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtrarnguer.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtzuyysnfs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtkisaznho.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtpkawezde.html

Go:   os.Remove("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtsewopfkq.html

Ruby: File.delete("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtnqhmgapm.html

C#:   File.Delete("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtsgabwpon.html

[F07] 创建目录（含多级）
来源：http://dali.hongshengwenyu.top/Article/details/gtxpflbmuw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtqgxtjjbb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shuidangran.top/Article/details/gttgwgfmjj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuanzx.com/Article/details/gtbvigvsho.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gttoyvtybs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shangyingyoupin.top/Article/details/gtbaqalckk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yvedp.cn/Article/details/gtgytfglob.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cashguo.top/Article/details/gtkpekfjtu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ybcxt.top/Article/details/gtqsowrpfs.html

[F08] 遍历目录
来源：http://dali.zhoulong.xyz/Article/details/gtemkoxgpc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yuxming.cn/Article/details/gtwdnkgauw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.redwolf501.top/Article/details/gtupjfngnb.html

JS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gtnlfnvyuf.html

TS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gtawonlbms.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gtkddnjpud.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.haohaochexian.top/Article/details/gtpvvprmpc.html

Ruby: Dir.children("dir")
来源：http://dali.iojbl.cn/Article/details/gtgptspkiw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.haohaochexian.top/Article/details/gtpynvgqrf.html

[F09] 获取文件大小
来源：http://dali.vqdsnc.cn/Article/details/gtmkafsqxl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtokdyftzw.html

PHP:  filesize("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtnjbkwzuj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pycfn.com/Article/details/gtizbuoird.html

TS:   fs.statSync("a.txt").size
来源：http://dali.snrcjt.cn/Article/details/gtivuqjdyt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gtagskrqjo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhiwuduotai.top/Article/details/gtjoikuzgh.html

Ruby: File.size("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtvrfahwae.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.iojbl.cn/Article/details/gtxawtxstm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.andypj.xyz/Article/details/gtoymqrukb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtbbqxfemi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jyoumei.cn/Article/details/gttrqlovbe.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtcbppalfs.html

TS:   path.extname("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtikcpqrbq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ehwqpu.com/Article/details/gtajebguka.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtkmdifbbg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtwjreuhsg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtmyquvhve.html

[F11] 复制与移动文件
来源：http://dali.zycfv.cn/Article/details/gtvgekguic.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtglwbepdz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yuanzhike.top/Article/details/gtjgsnivup.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcybodgeq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtnpboafpu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtxugcnhzw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuetiantiany.cn/Article/details/gtojnwsdgn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtpdwxltse.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhengqikj.top/Article/details/gtpmfunilv.html

[F12] CSV 读写
来源：http://dali.zhoulong.xyz/Article/details/gteualtmyq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.smart0.xyz/Article/details/gtqijkphrc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.fengsongda.top/Article/details/gthzbprsvs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.feifeiyinyue.top/Article/details/gtozuhikeu.html

TS:   // 同上
来源：http://dali.svipenyu.cn/Article/details/gtiwmjbnem.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zdqjudy.top/Article/details/gtembceokr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.316326.xyz/Article/details/gtazfqwrjk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenlongwang.top/Article/details/gtebitmvxb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xuetiantiany.cn/Article/details/gtmpqhzeks.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtwamlvvxp.html

G. 面向对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxhrxofb.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtnknprhis.html

[G01] 定义类
来源：http://dali.jlsjyb.cn/Article/details/gtygjsbgod.html

Py:   class User: pass
来源：http://dali.nanxinkj.top/Article/details/gtqlviwpkc.html

PHP:  class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtmnojpcfr.html

JS:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gtspsrecre.html

TS:   class User { name: string = ""; }
来源：http://dali.gzhubu.top/Article/details/gtcaqvqwij.html

Java: class User {}
来源：http://dali.shzxlz.cn/Article/details/gtszjghmkh.html

Go:   type User struct { Name string }
来源：http://dali.yangfankeji.com/Article/details/gtfeolubpv.html

Ruby: class User; end
来源：http://dali.aizwys.cn/Article/details/gtwqyjrgji.html

C#:   class User {}
来源：http://dali.cucudq.cn/Article/details/gtsqgvefus.html

[G02] 构造函数
来源：http://dali.jiagoushi.top/Article/details/gtnwgwqphy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hammf.cn/Article/details/gtfzxpkgcg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgufenzy.top/Article/details/gtcixtbgpi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gtlfbhrlgs.html

TS:   constructor(public name: string) {}
来源：http://dali.yj202588.top/Article/details/gtadsezpcq.html

Java: User(String name) { this.name = name; }
来源：http://dali.tianlin.xyz/Article/details/gtxwkcomzj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shanyushiyangtech.top/Article/details/gttvsdhqcv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daxiang520.top/Article/details/gtykvhupgo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gthnrwscgr.html

[G03] 实例属性
来源：http://dali.wangdashe.top/Article/details/gtjnjkpeks.html

Py:   self.name = "x"
来源：http://dali.zdqjudy.top/Article/details/gtyvjtntza.html

PHP:  public string $name = "x";
来源：http://dali.haohaochexian.top/Article/details/gtvsnimhqu.html

JS:   this.name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtzlbpsdza.html

TS:   name: string = "x";
来源：http://dali.hywenlv.cn/Article/details/gtfxmhggft.html

Java: private String name;
来源：http://dali.sweek.top/Article/details/gtuagqknal.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.svipenyu.cn/Article/details/gtzodzsfcn.html

Ruby: @name = "x"
来源：http://dali.tanke756.top/Article/details/gtnnjzdvek.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sxryk.cn/Article/details/gtelrascyf.html

[G04] 定义方法
来源：http://dali.mhx1999.top/Article/details/gtxtzdggrn.html

Py:   def greet(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gtnbuensua.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfgpygnx.html

JS:   greet() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtpastscgx.html

TS:   greet(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtxxgxwxjl.html

Java: String greet() { return name; }
来源：http://dali.birdmap.top/Article/details/gtjrxtlbtp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gtymopgvsi.html

Ruby: def greet; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtkqgqldqv.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258888.top/Article/details/gtjwgsmwgz.html

[G05] 继承
来源：http://dali.316326.xyz/Article/details/gttftxwghl.html

Py:   class Admin(User): pass
来源：http://dali.shangyingyoupin.top/Article/details/gthitogpqp.html

PHP:  class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtahhdaegx.html

JS:   class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtdvyedkql.html

TS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtupyrwqsg.html

Java: class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtombiwmip.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinghuilouyu.cn/Article/details/gtfeuwrjqp.html

Ruby: class Admin < User; end
来源：http://dali.jinqigfzy.top/Article/details/gtekdtreqs.html

C#:   class Admin : User {}
来源：http://dali.tianlin.xyz/Article/details/gtfpxmpcrc.html

[G06] 重写方法
来源：http://dali.ehwqpu.com/Article/details/gtgdmiatmj.html

Py:   def greet(self): return "admin"
来源：http://dali.daria6918.cn/Article/details/gtloolhduw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxakozbu.html

JS:   greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtfrhfctuq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtcdwzjscb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtynfundxv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.dashuyun.cn/Article/details/gtrfvirepp.html

Ruby: def greet; "admin"; end
来源：http://dali.wangshuangyany.cn/Article/details/gttpdkzxwn.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuanzx.com/Article/details/gtndoczdaq.html

[G07] 调用父类方法
来源：http://dali.aibaodan.cn/Article/details/gtywypngsa.html

Py:   super().greet()
来源：http://dali.ivvv.top/Article/details/gtqvqiyggu.html

PHP:  parent::greet();
来源：http://dali.yonumen.top/Article/details/gtomqoxleh.html


<!-- 参考信息 -->