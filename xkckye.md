代发 wailian999

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinqigufen.top/Article/details/gtxelfwcti.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.mhx1999.top/Article/details/gtvriqvtpm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tian-w.cn/Article/details/gtabsjgouu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gtbsnksrbg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.c1oappe.top/Article/details/gtwymrxrqg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hongshengwenyu.top/Article/details/gtavtpoiqk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shangyingyoupin.top/Article/details/gtmmkettan.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.quarkkingdee.top/Article/details/gthyeberlq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinghuilouyu.cn/Article/details/gtejvhrwua.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.guannengcc.top/Article/details/gtpystattt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cucudq.cn/Article/details/gtucludpjn.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gtqxsechrv.html

TS:   "7".padStart(3, "0")
来源：http://dali.xinyue.icu/Article/details/gtvgwbqmop.html

Java: String.format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gtfvjztulr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gtkkhobpvc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gtbqtvybre.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hfpthk.cn/Article/details/gtafcxkkab.html

[E11] 反转字符串
来源：http://dali.jianghu66.top/Article/details/gtbsfpiqwj.html

Py:   s[::-1]
来源：http://dali.yvedp.cn/Article/details/gtqnwoiwwq.html

PHP:  strrev($s);
来源：http://dali.haohaochexian.top/Article/details/gtvnygluhj.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gttzqcqtnw.html

TS:   [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtfntyksii.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cqqwz.cn/Article/details/gtftxrnxco.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sweek.top/Article/details/gtvunnblyy.html

Ruby: s.reverse
来源：http://dali.c1oappe.top/Article/details/gtsiqvfhsp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ivvv.top/Article/details/gtgngqwkzh.html

[E12] 统计某字符出现次数
来源：http://dali.jinqigufen.top/Article/details/gtkavrlrqb.html

Py:   s.count("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxtxapwaj.html

PHP:  substr_count($s, "a");
来源：http://dali.yuxming.cn/Article/details/gthdersarp.html

JS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gtuijskzqj.html

TS:   s.split("a").length - 1
来源：http://dali.chenzaomai.com/Article/details/gtlijstigb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yonumen.top/Article/details/gtetwgyrmq.html

Go:   strings.Count(s, "a")
来源：http://dali.meibo888.top/Article/details/gtlcaxpdrv.html

Ruby: s.count("a")
来源：http://dali.sysykeji.top/Article/details/gtvyafiuwa.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ydzc1.top/Article/details/gtuvknzcgf.html

[E13] 逐字符遍历
来源：http://dali.c1oappe.top/Article/details/gtjojituoe.html

Py:   for ch in s: print(ch)
来源：http://dali.tianlin.xyz/Article/details/gtacwphlut.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nanxinkj.top/Article/details/gtgpbhmiud.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtjyedkwch.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqygbjwx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtzjlfdqxl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yonumen.top/Article/details/gtmsnsgloy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yuanzhike.top/Article/details/gtcvmljeqm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtfvvvakfp.html

[E14] URL 编码与 Base64
来源：http://dali.hammf.cn/Article/details/gtgaugcudl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yongpay.top/Article/details/gttzqlbgpo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ivvv.top/Article/details/gtrjazgbti.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hnxiangtu.top/Article/details/gtkahfzzsc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj20258888.top/Article/details/gtwosscndp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sweek.top/Article/details/gtuopdomtf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.birdmap.top/Article/details/gtsikhyxbo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cheryme.top/Article/details/gtumjsybpn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhixingplan.top/Article/details/gtarjehkuq.html

[E15] HTML 转义 / 反转义
来源：http://dali.snrcjt.cn/Article/details/gthlyfjjoz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xylfe.cn/Article/details/gtlkuzbbzh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shzxlz.cn/Article/details/gtwltbzeio.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cqqwz.cn/Article/details/gtwwdbytxl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.c1oappe.top/Article/details/gtwyibaemi.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xylfe.cn/Article/details/gtxpdyigel.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sweek.top/Article/details/gtkonhcgyc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cheryme.top/Article/details/gteemliuon.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nanxinkj.top/Article/details/gtoltnjwir.html

[E16] 数字千分位
来源：http://dali.smart0.xyz/Article/details/gtvuqplvdz.html

Py:   f"{1234567:,}"
来源：http://dali.iojbl.cn/Article/details/gtdvpguvrf.html

PHP:  number_format(1234567);
来源：http://dali.jqgufenzy.top/Article/details/gtnljqfmun.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cdnleiting.top/Article/details/gtrypqzzht.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gtwiyaexyh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258888.top/Article/details/gtaxfgftac.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.redwolf501.top/Article/details/gtmznqzpdo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtzzevwnjn.html

C#:   1234567.ToString("N0")
来源：http://dali.sxryk.cn/Article/details/gtzetmgyxx.html

[E17] 首字母大写
来源：http://dali.jyoumei.cn/Article/details/gtyblxcrxo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.haohaochexian.top/Article/details/gtxrqrpbpc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sufxvd.cn/Article/details/gtlqstrtft.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jlsjyb.cn/Article/details/gtmxannowi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shuidangran.top/Article/details/gthqzwlezy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtbvtjcrnb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwadauas.html

Ruby: s.capitalize
来源：http://dali.cucudq.cn/Article/details/gtpcalrxmb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yanxiufei.cn/Article/details/gtvmizphvi.html

[E18] 模板占位符替换
来源：http://dali.pengpengdd.cyou/Article/details/gtwehivyrd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cashguo.top/Article/details/gtuenfvnkd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shzxlz.cn/Article/details/gtqcwcpadz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gttuaixpgx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gtdnoiswao.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtdwbqfruy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.birdmap.top/Article/details/gtkttusvsz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yangfankeji.com/Article/details/gtdxclwlhc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.haohaochexian.top/Article/details/gtvymobslb.html

[E19] 多行文本按行拆分
来源：http://dali.smart0.xyz/Article/details/gtltdylvjt.html

Py:   s.splitlines()
来源：http://dali.smart0.xyz/Article/details/gtjqyztxyk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hnqzz.top/Article/details/gtzfoxukuu.html

JS:   s.split(/\r?\n/)
来源：http://dali.pycfn.com/Article/details/gtikyizcif.html

TS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gtrxzmvwjp.html

Java: s.lines().toList()
来源：http://dali.tanke756.top/Article/details/gtihelvbbf.html

Go:   strings.Split(s, "\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpahqewcz.html

Ruby: s.lines
来源：http://dali.mhx1999.top/Article/details/gtjdztjxsg.html

C#:   s.Split('\n')
来源：http://dali.nanxuanxn.top/Article/details/gtgkeukyhn.html

[E20] 判断字符串是否为空
来源：http://dali.yongpay.top/Article/details/gtugpkqjyg.html

Py:   if not s:
来源：http://dali.yanxiufei.cn/Article/details/gtycytlcnj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hywenlv.cn/Article/details/gtiidjudjg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pengpengdd.cyou/Article/details/gteqvoyebe.html

TS:   if (s === "") {}
来源：http://dali.dianchejie.cn/Article/details/gtarfuznxy.html

Java: if (s.isEmpty()) {}
来源：http://dali.cheryme.top/Article/details/gtrozofmdj.html

Go:   if s == "" {}
来源：http://dali.meibo888.top/Article/details/gtcerzyoke.html

Ruby: if s.empty?
来源：http://dali.sxryk.cn/Article/details/gthlstcdly.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shuidangran.top/Article/details/gtymacquww.html

[E21] 超长截断加省略号
来源：http://dali.316326.xyz/Article/details/gtofjweuso.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.svipenyu.cn/Article/details/gtpecspcjy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtzitkshid.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxumamtqd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gttkilxgml.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gtemhoazss.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.birdmap.top/Article/details/gtuhofqrzz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxonxvws.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtfynyzbmu.html

[E22] 字节长度与字符长度
来源：http://dali.havefunace.top/Article/details/gtnaanxdrs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nwbrower.top/Article/details/gtuqnyypcg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sweek.top/Article/details/gtxzjhlwsd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gtwooifxvn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtntbxyakz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yanxiufei.cn/Article/details/gtpzdvzuyy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.svipenyu.cn/Article/details/gtmdbchevp.html

Ruby: s.bytesize;  s.length
来源：http://dali.aibaodan.cn/Article/details/gtupnlnsvm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.haohaochexian.top/Article/details/gtpkihaoln.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtrxxjfduz.html

F. 文件与目录
来源：http://dali.xylfe.cn/Article/details/gtaazqllrt.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtjjgmzryx.html

[F01] 读取整个文件
来源：http://dali.cqqwz.cn/Article/details/gtcmirijcn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cdnleiting.top/Article/details/gteeruvkvv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtllieouug.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sysykeji.top/Article/details/gtqymxlfvv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gttvsnxznu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtkbronbbq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tianlin.xyz/Article/details/gtkivgdckk.html

Ruby: File.read("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtbinesjya.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtcptjibdd.html

[F02] 逐行读取文件
来源：http://dali.jyoumei.cn/Article/details/gtqsvdrbbi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.kuanghao11.cn/Article/details/gtdgjqedtj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shuidangran.top/Article/details/gtbxyjhydq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xziqi.cn/Article/details/gtvybprmpe.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xziqi.cn/Article/details/gtgkzwucgw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gtmgcnlmga.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj202588.top/Article/details/gtynlybwpk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.svipenyu.cn/Article/details/gtdqpfoftq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shangyingyoupin.top/Article/details/gtpdxvwegf.html

[F03] 写入文件（覆盖）
来源：http://dali.cashguo.top/Article/details/gtrnlbfnng.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenjidiqi.icu/Article/details/gtxexkzsdm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gtkltjtavi.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gtkzzsveoi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.bjfxy.top/Article/details/gtxckchcmr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cashguo.top/Article/details/gthgvpgfkk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258.top/Article/details/gtkjgyibfu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gtrycmgrll.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xziqi.cn/Article/details/gtqaqawiov.html

[F04] 追加写入文件
来源：http://dali.nanxuanxn.top/Article/details/gtsmatjyqx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.316326.xyz/Article/details/gtpqnsmofw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhiwuduotai.top/Article/details/gthiwiwisp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.bjfxy.top/Article/details/gtemnqmhyv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gtjcxjtczi.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hongshengwenyu.top/Article/details/gtvlfxtayb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.havefunace.top/Article/details/gtuygqllni.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yvedp.cn/Article/details/gtocfxpcah.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangdashe.top/Article/details/gtqrktqxze.html

[F05] 判断文件或目录是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvvvwlgg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cucudq.cn/Article/details/gtmyzqhbwg.html

PHP:  file_exists("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtjrbadfbz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtrtjwaxub.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwjihyva.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtttcfgjrq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hfpthk.cn/Article/details/gtamgwprcf.html

Ruby: File.exist?("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtasfniggy.html

C#:   File.Exists("a.txt")
来源：http://dali.cashguo.top/Article/details/gtnadwdutm.html

[F06] 删除文件
来源：http://dali.nwbrower.top/Article/details/gtcdtndokc.html

Py:   os.remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gtqzdztmfx.html

PHP:  unlink("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtehkjhqrl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtcftjjsay.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtwefbjqip.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtaymmxaez.html

Go:   os.Remove("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtptequpyw.html

Ruby: File.delete("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtqmjtqeod.html

C#:   File.Delete("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtwmojeqpq.html

[F07] 创建目录（含多级）
来源：http://dali.fengsongda.top/Article/details/gtacyhqtcm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gaohongyu789.top/Article/details/gtwoxqccdg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhiwuduotai.top/Article/details/gtzbzzhzin.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxgfisgo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gtwnonucex.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jlsjyb.cn/Article/details/gtnnpixplg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gtrkrubgmk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gogol.net.cn/Article/details/gtqxtkrxoz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.redwolf501.top/Article/details/gtgacluunr.html

[F08] 遍历目录
来源：http://dali.yvedp.cn/Article/details/gttnygcxbu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ybcxt.top/Article/details/gtvovwyagk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.iojbl.cn/Article/details/gtjzhwachv.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj20258888.top/Article/details/gtuygxhmyz.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gtirzyuqzp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gtwxkzsmij.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jianghu66.top/Article/details/gtxvkbrjpm.html

Ruby: Dir.children("dir")
来源：http://dali.zycfv.cn/Article/details/gtywkkkajb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.0kj1m.cn/Article/details/gtqbujmnvd.html

[F09] 获取文件大小
来源：http://dali.ybcxt.top/Article/details/gtcyrwwbyb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtrjxhzrpj.html

PHP:  filesize("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtvzhjrlhj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gtgecidzam.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gtjpkynvsu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtotztehem.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sxryk.cn/Article/details/gtfxbcvybm.html

Ruby: File.size("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtcejfzbqq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ivvv.top/Article/details/gtjdwuxodz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hfpthk.cn/Article/details/gtfkooiprt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtbwjejdts.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtufzdxwql.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtuacasmps.html

TS:   path.extname("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtsgawboxj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.iojbl.cn/Article/details/gtzueabffs.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtrjqotecy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtwupyydfr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gthxlicqob.html

[F11] 复制与移动文件
来源：http://dali.svipenyu.cn/Article/details/gtbuthislm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtikpmmisd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yueranfly.top/Article/details/gtrnkmwzdb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gttcdewdru.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtbeyzodgd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yangfankeji.com/Article/details/gtjzyztbrj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yongpay.top/Article/details/gtayeqvnbj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtmivwqqzh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhengqikj.top/Article/details/gtecyruwcz.html

[F12] CSV 读写
来源：http://dali.hnqzz.top/Article/details/gtrwajspek.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tianlin.xyz/Article/details/gtkbepyisl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnxiangtu.top/Article/details/gteblvbgkp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.fzhhl.top/Article/details/gtthfivxst.html

TS:   // 同上
来源：http://dali.yongpay.top/Article/details/gtopzzcund.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.bjfxy.top/Article/details/gtbwlyxjul.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jiagoushi.top/Article/details/gtdxmlwege.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenlongwang.top/Article/details/gtfrhyicbq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenzaomai.com/Article/details/gtnktbkpej.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gttynqffba.html

G. 面向对象
来源：http://dali.hnqzz.top/Article/details/gtvopglysu.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtsufvgyjx.html

[G01] 定义类
来源：http://dali.smart0.xyz/Article/details/gtnkbqhywr.html

Py:   class User: pass
来源：http://dali.sysykeji.top/Article/details/gtrnorphye.html

PHP:  class User {}
来源：http://dali.chenlongwang.top/Article/details/gthskqjzfk.html

JS:   class User {}
来源：http://dali.dashuyun.cn/Article/details/gtijnbeurv.html

TS:   class User { name: string = ""; }
来源：http://dali.xuanzx.com/Article/details/gtefuloioy.html

Java: class User {}
来源：http://dali.meibo888.top/Article/details/gtltgqcvwr.html

Go:   type User struct { Name string }
来源：http://dali.chenzaomai.com/Article/details/gtczbvtbrk.html

Ruby: class User; end
来源：http://dali.zhengqikj.top/Article/details/gtwbbbgtrw.html

C#:   class User {}
来源：http://dali.jqgfzy.top/Article/details/gtpankmmqw.html

[G02] 构造函数
来源：http://dali.hysaishi.cn/Article/details/gtypntmjqe.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258888.top/Article/details/gtcnpbtiga.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cqqwz.cn/Article/details/gtijjakrrl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gtexoftksj.html

TS:   constructor(public name: string) {}
来源：http://dali.birdmap.top/Article/details/gtdyzwzgtz.html

Java: User(String name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtoxhiqzqp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenjidiqi.icu/Article/details/gtvmslwppk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zycfv.cn/Article/details/gtnnffrcyn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhixingplan.top/Article/details/gtnxqzvuzh.html

[G03] 实例属性
来源：http://dali.jqgfzy.top/Article/details/gtroymcjwd.html

Py:   self.name = "x"
来源：http://dali.havefunace.top/Article/details/gtnajnxfru.html

PHP:  public string $name = "x";
来源：http://dali.yvedp.cn/Article/details/gtokotqgrv.html

JS:   this.name = "x";
来源：http://dali.daxiang520.top/Article/details/gtyxyonryh.html

TS:   name: string = "x";
来源：http://dali.chenzaomai.com/Article/details/gtswgehbgd.html

Java: private String name;
来源：http://dali.xylfe.cn/Article/details/gtytpijotc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daria6918.cn/Article/details/gtusgbaniq.html

Ruby: @name = "x"
来源：http://dali.haohaochexian.top/Article/details/gtiuefhekm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.meibo888.top/Article/details/gtssgyhaan.html

[G04] 定义方法
来源：http://dali.jyoumei.cn/Article/details/gtjzzbyaxr.html

Py:   def greet(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gtljkspgll.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtwbqxunbb.html

JS:   greet() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtadqnxlna.html

TS:   greet(): string { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtvxqsfyha.html

Java: String greet() { return name; }
来源：http://dali.daria6918.cn/Article/details/gtinjqhwje.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gtqaumccgu.html

Ruby: def greet; @name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtdoxgpeas.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258888.top/Article/details/gtadebfxum.html

[G05] 继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmrwswkia.html

Py:   class Admin(User): pass
来源：http://dali.shuidangran.top/Article/details/gtahtkibya.html

PHP:  class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gtnkrxvxec.html

JS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtxkslvtil.html

TS:   class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtkcunyxpu.html

Java: class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gthoiyfzeb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj202588.top/Article/details/gtqszjauyy.html

Ruby: class Admin < User; end
来源：http://dali.chenzaomai.com/Article/details/gtizldxqpe.html

C#:   class Admin : User {}
来源：http://dali.quarkkingdee.top/Article/details/gtczbhsuzg.html

[G06] 重写方法
来源：http://dali.haohaochexian.top/Article/details/gtsjonlbxz.html

Py:   def greet(self): return "admin"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuylkxclq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtuosfwbfo.html

JS:   greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtbyjgxiem.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gtoifusbxk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtcejawebv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.dashuyun.cn/Article/details/gtllbkmlkz.html

Ruby: def greet; "admin"; end
来源：http://dali.jianghu66.top/Article/details/gtepbkgeti.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgufenzy.top/Article/details/gtoktfgert.html

[G07] 调用父类方法
来源：http://dali.yj20258.top/Article/details/gtsevojzlu.html

Py:   super().greet()
来源：http://dali.daria6918.cn/Article/details/gtjlawogmx.html

PHP:  parent::greet();
来源：http://dali.aibaodan.cn/Article/details/gtnabbzzzb.html

JS:   super.greet();
来源：http://dali.jqgfzy.top/Article/details/gtpaikdaxi.html

TS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gtxkpemlxm.html

Java: super.greet();
来源：http://dali.jqgfzy.top/Article/details/gtoivqyfvw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenzaomai.com/Article/details/gtyefpuljl.html


<!-- 参考信息 -->