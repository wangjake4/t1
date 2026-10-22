代发 wailian999

Go:   strings.Join(items, ",")
来源：http://dali.cdnleiting.top/Article/details/gtayhimbfl.html

Ruby: items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gtyxjzvvok.html

C#:   string.Join(",", items)
来源：http://dali.zhongyouzk.top/Article/details/gtpjafwwoq.html

[E09] 去除所有空白字符
来源：http://dali.ydzc1.top/Article/details/gtfyacdgel.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhongyouzk.top/Article/details/gtoeoqumnt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yongpay.top/Article/details/gtpnfsjswo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.vqdsnc.cn/Article/details/gtrjfnpyvy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hywenlv.cn/Article/details/gtcbdflbdk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.fengsongda.top/Article/details/gtwprxosai.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.0kj1m.cn/Article/details/gtqxariiix.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinqigufen.top/Article/details/gtlukpltmi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hysaishi.cn/Article/details/gthmhpimjp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinghuilouyu.cn/Article/details/gtnutbcupa.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdqmgffx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinqigfzy.top/Article/details/gteuuqaxlx.html

JS:   "7".padStart(3, "0")
来源：http://dali.yonumen.top/Article/details/gticguuqca.html

TS:   "7".padStart(3, "0")
来源：http://dali.tanke756.top/Article/details/gtztbayjmz.html

Java: String.format("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gtwdckeatw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gtawlsaluf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtoelrzaxa.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.svipenyu.cn/Article/details/gtvmcbswmg.html

[E11] 反转字符串
来源：http://dali.yuxming.cn/Article/details/gtgofhurjb.html

Py:   s[::-1]
来源：http://dali.ivvv.top/Article/details/gtizaxxuee.html

PHP:  strrev($s);
来源：http://dali.hfpthk.cn/Article/details/gtmhswrlyu.html

JS:   [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gtkfnxomgn.html

TS:   [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtttkzvima.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenlongwang.top/Article/details/gtvjjudtsk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenlongwang.top/Article/details/gtonecnare.html

Ruby: s.reverse
来源：http://dali.zhixingplan.top/Article/details/gtpgwnbuqy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhengqikj.top/Article/details/gtoysxljpo.html

[E12] 统计某字符出现次数
来源：http://dali.jinqigfzy.top/Article/details/gtmlrixlch.html

Py:   s.count("a")
来源：http://dali.jiagoushi.top/Article/details/gtvygjoufg.html

PHP:  substr_count($s, "a");
来源：http://dali.zhixingplan.top/Article/details/gtjorszgza.html

JS:   s.split("a").length - 1
来源：http://dali.cqqwz.cn/Article/details/gtocalgbrx.html

TS:   s.split("a").length - 1
来源：http://dali.316326.xyz/Article/details/gtubeqsaib.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yangfankeji.com/Article/details/gtwrvacvew.html

Go:   strings.Count(s, "a")
来源：http://dali.ehwqpu.com/Article/details/gttwswuctl.html

Ruby: s.count("a")
来源：http://dali.pycfn.com/Article/details/gtfulzdzol.html

C#:   s.Count(c => c == 'a')
来源：http://dali.birdmap.top/Article/details/gtbjbnwryb.html

[E13] 逐字符遍历
来源：http://dali.sysykeji.top/Article/details/gtwgpzltbc.html

Py:   for ch in s: print(ch)
来源：http://dali.ehwqpu.com/Article/details/gtlrmwhfgh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sufxvd.cn/Article/details/gtswqxbrvn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gtbeqwnhtu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ybcxt.top/Article/details/gtqhbuhgze.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtfclvvxjc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gzhubu.top/Article/details/gttmeagzci.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.snrcjt.cn/Article/details/gtadhpuqay.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtctjewnte.html

[E14] URL 编码与 Base64
来源：http://dali.zhongyouzk.top/Article/details/gtnurjkeid.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yvedp.cn/Article/details/gtfkkstbiy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhixingplan.top/Article/details/gtqcesqhfy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cdnleiting.top/Article/details/gtjaeygakd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuanzhike.top/Article/details/gtfnuiqjlk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.haohaochexian.top/Article/details/gtgtrxwcgp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.daria6918.cn/Article/details/gtxzpnvzdc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ydzc1.top/Article/details/gteklnamvg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.wangdashe.top/Article/details/gtsgphpwyv.html

[E15] HTML 转义 / 反转义
来源：http://dali.shangyingyoupin.top/Article/details/gtlsltfggk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinqigufen.top/Article/details/gtovfexlth.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yangfankeji.com/Article/details/gtqvjaxyht.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinqigfzy.top/Article/details/gtelgfvjem.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ydzc1.top/Article/details/gttcocddza.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhiwuduotai.top/Article/details/gtzilbqlai.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zdqjudy.top/Article/details/gtulboddxp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.redwolf501.top/Article/details/gtaopqpxkm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cheryme.top/Article/details/gtwnejghkx.html

[E16] 数字千分位
来源：http://dali.aibaodan.cn/Article/details/gtmixndqov.html

Py:   f"{1234567:,}"
来源：http://dali.jyoumei.cn/Article/details/gtulcvcdql.html

PHP:  number_format(1234567);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpeapfvwn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yangfankeji.com/Article/details/gtnxrypuss.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.dashuyun.cn/Article/details/gtnfjoylid.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.snrcjt.cn/Article/details/gtaoejzpnz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xinyue.icu/Article/details/gtloqcecpu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.svipenyu.cn/Article/details/gtwykjgmrp.html

C#:   1234567.ToString("N0")
来源：http://dali.yvedp.cn/Article/details/gtccjjuual.html

[E17] 首字母大写
来源：http://dali.316326.xyz/Article/details/gtkcevusxo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvemqvhqy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtklkldpni.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fzhhl.top/Article/details/gtcsufgimv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gzhubu.top/Article/details/gtfvgkggvp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hammf.cn/Article/details/gtsppriphi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gtmtffmavc.html

Ruby: s.capitalize
来源：http://dali.hnxiangtu.top/Article/details/gtoehguebx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.birdmap.top/Article/details/gttszuxbxa.html

[E18] 模板占位符替换
来源：http://dali.bjfxy.top/Article/details/gtrsxolles.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shangyingyoupin.top/Article/details/gtbvjzfsji.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.quarkkingdee.top/Article/details/gtzknusxgs.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdihofere.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtrgrmwdip.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gtmicebamq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtntdvgnph.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj202588.top/Article/details/gtxkrnnvrd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gotoacloud.top/Article/details/gtekhwrrvg.html

[E19] 多行文本按行拆分
来源：http://dali.yanxiufei.cn/Article/details/gtkxrmcsxr.html

Py:   s.splitlines()
来源：http://dali.dianchejie.cn/Article/details/gtctdyoxge.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtqfhsjwho.html

JS:   s.split(/\r?\n/)
来源：http://dali.pycfn.com/Article/details/gthbvcpxkw.html

TS:   s.split(/\r?\n/)
来源：http://dali.yanxiufei.cn/Article/details/gtxhlcwyfv.html

Java: s.lines().toList()
来源：http://dali.nanxinkj.top/Article/details/gthhjaymgy.html

Go:   strings.Split(s, "\n")
来源：http://dali.gzhubu.top/Article/details/gtycsljkhm.html

Ruby: s.lines
来源：http://dali.gogol.net.cn/Article/details/gtmtnogrzl.html

C#:   s.Split('\n')
来源：http://dali.ivvv.top/Article/details/gtcyustypu.html

[E20] 判断字符串是否为空
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrirjdlln.html

Py:   if not s:
来源：http://dali.ywan-chungtsiang.top/Article/details/gtefdwvdrc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xylfe.cn/Article/details/gtvpvetbgv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jianghu66.top/Article/details/gtkhkapdbq.html

TS:   if (s === "") {}
来源：http://dali.snrcjt.cn/Article/details/gtjjctvtho.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinqigfzy.top/Article/details/gteoehmvrj.html

Go:   if s == "" {}
来源：http://dali.jinqigfzy.top/Article/details/gthfmjmmzn.html

Ruby: if s.empty?
来源：http://dali.pengpengdd.cyou/Article/details/gtitgrrhvh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.guowangkeji.top/Article/details/gtlvepjyho.html

[E21] 超长截断加省略号
来源：http://dali.nanxuanxn.top/Article/details/gtjdjnamxt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ivvv.top/Article/details/gtzkovaovi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtbbvbngdp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtocaicidk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gthrzjrcjv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gtbjxaibex.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbgnbgoh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtlieopoze.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtbffqhsid.html

[E22] 字节长度与字符长度
来源：http://dali.ppjwa.cn/Article/details/gtoroxdlrd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ppjwa.cn/Article/details/gtyecnihph.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gtddqvkngo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gthxfyscrp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gtgninjohv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jlsjyb.cn/Article/details/gtqvpctnnx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zdqjudy.top/Article/details/gteriyhwci.html

Ruby: s.bytesize;  s.length
来源：http://dali.yuanzhike.top/Article/details/gtjdsgcvpq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zdqjudy.top/Article/details/gtgszxpgca.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtzvaaxwao.html

F. 文件与目录
来源：http://dali.mhx1999.top/Article/details/gtaaoovdoj.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtxoukndai.html

[F01] 读取整个文件
来源：http://dali.gaohongyu789.top/Article/details/gtqgkunntc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hammf.cn/Article/details/gtwgkuxlgr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yongpay.top/Article/details/gtadsdhrym.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.meibo888.top/Article/details/gttubusvym.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gtmitclokq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gtdvdkljcd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.9152youxi.cn/Article/details/gtuldreitj.html

Ruby: File.read("a.txt")
来源：http://dali.ivvv.top/Article/details/gtctuwtdru.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtcxyigzye.html

[F02] 逐行读取文件
来源：http://dali.yongpay.top/Article/details/gtrishcduj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhixingplan.top/Article/details/gtazvmxjzf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yuxming.cn/Article/details/gtqigeryqn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gtgbvpcgtv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gtljdwqsji.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhixingplan.top/Article/details/gtjfkoinpz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cucudq.cn/Article/details/gtxzsiiofr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shuidangran.top/Article/details/gtfcbsibml.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daria6918.cn/Article/details/gtlbscdahh.html

[F03] 写入文件（覆盖）
来源：http://dali.aizwys.cn/Article/details/gtvdlweoiv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cashguo.top/Article/details/gtdoftqvzp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gtzvmiizhq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xinyue.icu/Article/details/gtlceooxon.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gtoqqnyujb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hongshengwenyu.top/Article/details/gtzyldscvs.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigufen.top/Article/details/gtdlziuiwc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hammf.cn/Article/details/gtzfsvlqmp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gtriryjtvb.html

[F04] 追加写入文件
来源：http://dali.haohaochexian.top/Article/details/gtmfaivezx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yongpay.top/Article/details/gtczyfcmuh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zycfv.cn/Article/details/gtystrsnsz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jianghu66.top/Article/details/gtvezllttn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtiyeeeuek.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yvedp.cn/Article/details/gtpzjklfot.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ppjwa.cn/Article/details/gtzbkgtgat.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nanxuanxn.top/Article/details/gtgrrbmjsn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tianlin.xyz/Article/details/gtbietkfeb.html

[F05] 判断文件或目录是否存在
来源：http://dali.cucudq.cn/Article/details/gtqspqxdsh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhoulong.xyz/Article/details/gtnpqmtuig.html

PHP:  file_exists("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtpsvfejha.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtwogtineq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtduuodbmp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtjicvqmro.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.andypj.xyz/Article/details/gthwomcebc.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtcmxycbyf.html

C#:   File.Exists("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtqvxedgtq.html

[F06] 删除文件
来源：http://dali.tanke756.top/Article/details/gtodsubkog.html

Py:   os.remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtxyylqnsh.html

PHP:  unlink("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtithtyuhs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtdmzimhjw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtegignftt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtwkdfjaac.html

Go:   os.Remove("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtxmlvyhgr.html

Ruby: File.delete("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtlbjaiotm.html

C#:   File.Delete("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtskpcwcay.html

[F07] 创建目录（含多级）
来源：http://dali.ppjwa.cn/Article/details/gtsokhctpk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jiagoushi.top/Article/details/gtzswhuxhc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sweek.top/Article/details/gtqmfpcnrv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gtptibybox.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gtppjxdyuu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.haohaochexian.top/Article/details/gtancllrtr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sxryk.cn/Article/details/gtokolrbnr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxinkj.top/Article/details/gtrgmgptuc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sweek.top/Article/details/gtenvdcodd.html

[F08] 遍历目录
来源：http://dali.guowangkeji.top/Article/details/gtjfcshldi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nanxinkj.top/Article/details/gtxsnwkejj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yueranfly.top/Article/details/gtkszxjfdu.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gtjvwhcjgi.html

TS:   fs.readdirSync("dir")
来源：http://dali.c1oappe.top/Article/details/gtotjwbqlw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gtfagrikpl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xinyue.icu/Article/details/gtrusbwtmp.html

Ruby: Dir.children("dir")
来源：http://dali.haohaochexian.top/Article/details/gtqjjihqgw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtbuntbdgf.html

[F09] 获取文件大小
来源：http://dali.hfpthk.cn/Article/details/gtmpawniky.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtoypuefof.html

PHP:  filesize("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtfvdgsifk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gtljrjbygj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gtysbbtnfn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtepgxgklz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj20258888.top/Article/details/gtfieqqyqi.html

Ruby: File.size("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtycycelwo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sxryk.cn/Article/details/gtevokzqkg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.aibaodan.cn/Article/details/gtajqzglxn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtzypsivxf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.iojbl.cn/Article/details/gtmvtoumos.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdvsfpsvu.html

TS:   path.extname("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtbwwrkouq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.haohaochexian.top/Article/details/gtmmzfnqac.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtcheirotx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtsurbojkq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtrufaqldm.html

[F11] 复制与移动文件
来源：http://dali.pengpengdd.cyou/Article/details/gtaacythti.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtwglcmfsl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tianlin.xyz/Article/details/gtzjlkgkhy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtgxtxxqrr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gttblozhkr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gttqsljmwh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ybcxt.top/Article/details/gtpotzorlm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtzwyunhjm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yuxming.cn/Article/details/gtujvbauyy.html

[F12] CSV 读写
来源：http://dali.yueranfly.top/Article/details/gttbsyrhqq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.feifeiyinyue.top/Article/details/gtbinqxllu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangshuangyany.cn/Article/details/gtmqnarugb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkoqkscfx.html

TS:   // 同上
来源：http://dali.xziqi.cn/Article/details/gtynxydwbl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gtgstattlh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.guowangkeji.top/Article/details/gttcwkfsra.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuetiantiany.cn/Article/details/gtlakdvxjb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqpgcusd.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtlpthzozu.html

G. 面向对象
来源：http://dali.zhoulong.xyz/Article/details/gtfstkaxtb.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtavuzdprv.html

[G01] 定义类
来源：http://dali.cdnleiting.top/Article/details/gtagyhcsfd.html

Py:   class User: pass
来源：http://dali.yuanzhike.top/Article/details/gttzbsnxan.html

PHP:  class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtjlumubwt.html

JS:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwbmwzefx.html

TS:   class User { name: string = ""; }
来源：http://dali.havefunace.top/Article/details/gtmbaivsvj.html

Java: class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtdakyqnsl.html

Go:   type User struct { Name string }
来源：http://dali.sweek.top/Article/details/gtxmroxjnw.html

Ruby: class User; end
来源：http://dali.hongshengwenyu.top/Article/details/gtcihzxcjm.html

C#:   class User {}
来源：http://dali.iojbl.cn/Article/details/gtlluqswxv.html

[G02] 构造函数
来源：http://dali.yj20258888.top/Article/details/gtftxetivc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dashuyun.cn/Article/details/gtspitbxqk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.havefunace.top/Article/details/gtyritlryo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258888.top/Article/details/gtetwvoajg.html

TS:   constructor(public name: string) {}
来源：http://dali.ybcxt.top/Article/details/gtksorzarf.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gthflydlbw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhixingplan.top/Article/details/gtjkbqgkzw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dashuyun.cn/Article/details/gtbzqhzxva.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nwbrower.top/Article/details/gtiynzmfxf.html

[G03] 实例属性
来源：http://dali.meibo888.top/Article/details/gtpnrfiyvn.html

Py:   self.name = "x"
来源：http://dali.yonumen.top/Article/details/gtaapjulul.html

PHP:  public string $name = "x";
来源：http://dali.havefunace.top/Article/details/gtjlwntxtu.html

JS:   this.name = "x";
来源：http://dali.cheryme.top/Article/details/gtwdyqmkju.html

TS:   name: string = "x";
来源：http://dali.cucudq.cn/Article/details/gtuuygjgmy.html

Java: private String name;
来源：http://dali.hnqzz.top/Article/details/gttadqkaoa.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.bjfxy.top/Article/details/gtthouljlk.html

Ruby: @name = "x"
来源：http://dali.yangfankeji.com/Article/details/gtwbznlpqv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yvedp.cn/Article/details/gtyvfjfzhl.html

[G04] 定义方法
来源：http://dali.mhx1999.top/Article/details/gtshzuvvoy.html

Py:   def greet(self): return self.name
来源：http://dali.jinqigfzy.top/Article/details/gtarwengep.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gteutgroqp.html

JS:   greet() { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtcqdttfzn.html

TS:   greet(): string { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gtrgmkcsta.html

Java: String greet() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtqtovoubi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtkbqxgfmb.html

Ruby: def greet; @name; end
来源：http://dali.zdqjudy.top/Article/details/gtoejujslu.html

C#:   public string Greet() => Name;
来源：http://dali.cqqwz.cn/Article/details/gtgqccynoa.html

[G05] 继承
来源：http://dali.yuxming.cn/Article/details/gtopjfbwgo.html

Py:   class Admin(User): pass
来源：http://dali.aibaodan.cn/Article/details/gtxkktbdvd.html

PHP:  class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtaukmqjvv.html

JS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtcgfhinsg.html

TS:   class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtxflrtufu.html

Java: class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtabnljfcj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigfzy.top/Article/details/gtndneqkkz.html

Ruby: class Admin < User; end
来源：http://dali.xylfe.cn/Article/details/gtwcxaynio.html

C#:   class Admin : User {}
来源：http://dali.yvedp.cn/Article/details/gtndtgekpk.html

[G06] 重写方法
来源：http://dali.snrcjt.cn/Article/details/gtmusrtfln.html

Py:   def greet(self): return "admin"
来源：http://dali.sysykeji.top/Article/details/gtuggqghss.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtdzaavctu.html

JS:   greet() { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtifbsblao.html

TS:   greet(): string { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtckwkdpzc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtafubyueb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.316326.xyz/Article/details/gtsrxqkvmc.html

Ruby: def greet; "admin"; end
来源：http://dali.quarkkingdee.top/Article/details/gtpdlwnbwm.html

C#:   public override string Greet() => "admin";
来源：http://dali.shuidangran.top/Article/details/gtabvthysm.html

[G07] 调用父类方法
来源：http://dali.wangshuangyany.cn/Article/details/gtixfzkjrm.html

Py:   super().greet()
来源：http://dali.yueranfly.top/Article/details/gtbqfqdhfv.html

PHP:  parent::greet();
来源：http://dali.xylfe.cn/Article/details/gtxvwsmevv.html


<!-- 参考信息 -->