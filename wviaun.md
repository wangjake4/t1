代发 wailian999

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gtlmleobuw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258.top/Article/details/gtojrqlfvw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jqgufenzy.top/Article/details/gtpfigcubq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gtoyezrxxv.html

[E06] 替换子串
来源：http://dali.zhoulong.xyz/Article/details/gtpcluoubl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhixingplan.top/Article/details/gtprmxkawg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtookbxqov.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gtshtejxap.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrtulphka.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gtfwipdqzi.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yanxiufei.cn/Article/details/gtxqsyfwbk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtvuiifqrg.html

C#:   s.Replace("a", "b")
来源：http://dali.c1oappe.top/Article/details/gttpuqbzia.html

[E07] 按分隔符拆分
来源：http://dali.shuidangran.top/Article/details/gtykbazusj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hywenlv.cn/Article/details/gthagbmikq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjljyvteb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.kuanghao11.cn/Article/details/gtfwbylkzj.html

TS:   s.split(",")
来源：http://dali.fzhhl.top/Article/details/gtthwdgkgg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hammf.cn/Article/details/gtosxlgqfr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yvedp.cn/Article/details/gtychzutkc.html

Ruby: s.split(",");  s.split
来源：http://dali.zycfv.cn/Article/details/gtbvpbzsmr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenjidiqi.icu/Article/details/gtzldspbnk.html

[E08] 数组按分隔符合并
来源：http://dali.shzxlz.cn/Article/details/gtywccjlop.html

Py:   ",".join(items)
来源：http://dali.guowangkeji.top/Article/details/gtvswfgqtj.html

PHP:  implode(",", $items);
来源：http://dali.nanxuanxn.top/Article/details/gtffxzjbcq.html

JS:   items.join(",")
来源：http://dali.cucudq.cn/Article/details/gtzeuqivcm.html

TS:   items.join(",")
来源：http://dali.yanxiufei.cn/Article/details/gtxixydxok.html

Java: String.join(",", items)
来源：http://dali.bjfxy.top/Article/details/gtsaiyknku.html

Go:   strings.Join(items, ",")
来源：http://dali.pengpengdd.cyou/Article/details/gtpxqrmzey.html

Ruby: items.join(",")
来源：http://dali.sweek.top/Article/details/gtllgiqgqk.html

C#:   string.Join(",", items)
来源：http://dali.cheryme.top/Article/details/gtrnlhjzsa.html

[E09] 去除所有空白字符
来源：http://dali.zhengqikj.top/Article/details/gtkccyznjn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.birdmap.top/Article/details/gtrqtrwxqx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.svipenyu.cn/Article/details/gtorvgxlob.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gtdrdwpcop.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xuetiantiany.cn/Article/details/gtfmoqloji.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hongshengwenyu.top/Article/details/gtbvzfklta.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.316326.xyz/Article/details/gtxdyvwoan.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xylfe.cn/Article/details/gtxprcrbag.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj202588.top/Article/details/gtqjnbjwwz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gaohongyu789.top/Article/details/gtkkeuvktn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.guannengcc.top/Article/details/gtngvshzba.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gogol.net.cn/Article/details/gtrcaytvgc.html

JS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtzrbcdvbr.html

TS:   "7".padStart(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gtzuuljufp.html

Java: String.format("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gtiftataug.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gtqcsoieuu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gtrdxlejei.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hnqzz.top/Article/details/gtzyqzfgcb.html

[E11] 反转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtqjfdsaid.html

Py:   s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gtarztteic.html

PHP:  strrev($s);
来源：http://dali.snrcjt.cn/Article/details/gtgcxqzuqx.html

JS:   [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtytvngcmz.html

TS:   [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtgfatuqxi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.kuanghao11.cn/Article/details/gtxxgtbxcf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sweek.top/Article/details/gtrpapsmsx.html

Ruby: s.reverse
来源：http://dali.daxiang520.top/Article/details/gtthkjzlnn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dianchejie.cn/Article/details/gtlpccaipf.html

[E12] 统计某字符出现次数
来源：http://dali.havefunace.top/Article/details/gtyjwvinjj.html

Py:   s.count("a")
来源：http://dali.gogol.net.cn/Article/details/gtkoblfffq.html

PHP:  substr_count($s, "a");
来源：http://dali.c1oappe.top/Article/details/gtcsfqwyfl.html

JS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gtedqwrbku.html

TS:   s.split("a").length - 1
来源：http://dali.aizwys.cn/Article/details/gttaloiihy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shuidangran.top/Article/details/gtdfagwmro.html

Go:   strings.Count(s, "a")
来源：http://dali.iojbl.cn/Article/details/gtnxcpocgy.html

Ruby: s.count("a")
来源：http://dali.jinqigufen.top/Article/details/gtvkjuhvkl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.fengsongda.top/Article/details/gtiapjeawg.html

[E13] 逐字符遍历
来源：http://dali.hywenlv.cn/Article/details/gtjdjwzeiu.html

Py:   for ch in s: print(ch)
来源：http://dali.vqdsnc.cn/Article/details/gtkkjzguhz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cqqwz.cn/Article/details/gtskkgcrmu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtzllbuojn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.birdmap.top/Article/details/gtsqykvrqh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtjcevntsx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yuxming.cn/Article/details/gttaaideqi.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.wangdashe.top/Article/details/gtoflvjmca.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ivvv.top/Article/details/gtbcmvsocp.html

[E14] URL 编码与 Base64
来源：http://dali.wangshuangyany.cn/Article/details/gtouijbnon.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yuxming.cn/Article/details/gtjqrjyehb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinqigufen.top/Article/details/gtpisnhjha.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.mhx1999.top/Article/details/gthoahvxjt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.vqdsnc.cn/Article/details/gtfqurjctp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gtsiwgzils.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ybcxt.top/Article/details/gtaqcbeiaq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.pycfn.com/Article/details/gttfurzcxx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yuanzhike.top/Article/details/gtpoxvxtnv.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxinkj.top/Article/details/gtdfbgdkst.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xziqi.cn/Article/details/gtwzejvfqv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.guowangkeji.top/Article/details/gtknajqtqe.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhixingplan.top/Article/details/gtmgcbzjsp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ybcxt.top/Article/details/gtzmxvzull.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj20258888.top/Article/details/gtwmerudsn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.birdmap.top/Article/details/gttaedapse.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenzaomai.com/Article/details/gtrvhosgzc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sufxvd.cn/Article/details/gtektxkyvu.html

[E16] 数字千分位
来源：http://dali.sxryk.cn/Article/details/gthdyemgbo.html

Py:   f"{1234567:,}"
来源：http://dali.yj202588.top/Article/details/gtyvbiqjzo.html

PHP:  number_format(1234567);
来源：http://dali.jinghuilouyu.cn/Article/details/gtyendgkmw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.fengsongda.top/Article/details/gtjdkkybeo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hysaishi.cn/Article/details/gtlabvfnom.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.birdmap.top/Article/details/gtuvsjtljf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258888.top/Article/details/gteeowsjxw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.kuanghao11.cn/Article/details/gtzvkctgpw.html

C#:   1234567.ToString("N0")
来源：http://dali.dashuyun.cn/Article/details/gtacodpvoe.html

[E17] 首字母大写
来源：http://dali.iojbl.cn/Article/details/gtuebriral.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gzhubu.top/Article/details/gtxhizbrhh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuanzhike.top/Article/details/gtcyygqlzv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtvifxohvt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fzhhl.top/Article/details/gtafsssrvh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.vqdsnc.cn/Article/details/gttadajrli.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aibaodan.cn/Article/details/gthlidtemb.html

Ruby: s.capitalize
来源：http://dali.zycfv.cn/Article/details/gtomuiichr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.feifeiyinyue.top/Article/details/gtajatbcmv.html

[E18] 模板占位符替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtphcmztjv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xuetiantiany.cn/Article/details/gtwzakyeqi.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sysykeji.top/Article/details/gtxldyelik.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtuoctfcnt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gtwomjkyvq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.tanke756.top/Article/details/gttqbcptrt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtdyyzqfrw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hywenlv.cn/Article/details/gttjodlhrj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yuxming.cn/Article/details/gtnvhmnaji.html

[E19] 多行文本按行拆分
来源：http://dali.zhengqikj.top/Article/details/gtxyfpqjtt.html

Py:   s.splitlines()
来源：http://dali.kuanghao11.cn/Article/details/gtutrbaxlq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.svipenyu.cn/Article/details/gteiivifpt.html

JS:   s.split(/\r?\n/)
来源：http://dali.yuxming.cn/Article/details/gtwlulpyxp.html

TS:   s.split(/\r?\n/)
来源：http://dali.svipenyu.cn/Article/details/gtvnmtbxlq.html

Java: s.lines().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gthbrlgbmd.html

Go:   strings.Split(s, "\n")
来源：http://dali.havefunace.top/Article/details/gtqdwqsfvq.html

Ruby: s.lines
来源：http://dali.yongpay.top/Article/details/gticnpdzxs.html

C#:   s.Split('\n')
来源：http://dali.dashuyun.cn/Article/details/gtewnbuflq.html

[E20] 判断字符串是否为空
来源：http://dali.ywan-chungtsiang.top/Article/details/gtekigaqaz.html

Py:   if not s:
来源：http://dali.pengpengdd.cyou/Article/details/gtylvfwpya.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.havefunace.top/Article/details/gtfeyrxrpq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yanxiufei.cn/Article/details/gtvjscnpor.html

TS:   if (s === "") {}
来源：http://dali.daxiang520.top/Article/details/gtabkazlwg.html

Java: if (s.isEmpty()) {}
来源：http://dali.ivvv.top/Article/details/gtvnvfwcmz.html

Go:   if s == "" {}
来源：http://dali.yanxiufei.cn/Article/details/gtftswnutl.html

Ruby: if s.empty?
来源：http://dali.yvedp.cn/Article/details/gtdqjdivqv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cashguo.top/Article/details/gtngodqily.html

[E21] 超长截断加省略号
来源：http://dali.yueranfly.top/Article/details/gtogecqknu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhengqikj.top/Article/details/gtqwsosadp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gtpvgavnjp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtisyyqqvw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyeakwzzo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtghgveznh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.meibo888.top/Article/details/gtkaivrjgt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtynbqiqqx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gttimzasaz.html

[E22] 字节长度与字符长度
来源：http://dali.wangdashe.top/Article/details/gtcrmnmoaq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtoihlgzdl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtrqiamjgv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gtnvfmnmcv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gtachfkgax.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.c1oappe.top/Article/details/gtviallitj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jianghu66.top/Article/details/gtbmultpbr.html

Ruby: s.bytesize;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtlfjxxukr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj202588.top/Article/details/gtmevmqewq.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtfoknjlkj.html

F. 文件与目录
来源：http://dali.yanxiufei.cn/Article/details/gtiuvrdsex.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbkxqxxb.html

[F01] 读取整个文件
来源：http://dali.ehwqpu.com/Article/details/gtxsbnmchn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cashguo.top/Article/details/gtxqzdibol.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtlumfjwor.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cheryme.top/Article/details/gtrmwsrtpu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gtstuvswgw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtlxgptrdi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jianghu66.top/Article/details/gtdhokdjzp.html

Ruby: File.read("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtiwlbxgzs.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtiudvxoes.html

[F02] 逐行读取文件
来源：http://dali.dashuyun.cn/Article/details/gtytzvflah.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pycfn.com/Article/details/gtfoxpczol.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gtqxbdxpmf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gtvbgbnzih.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tanke756.top/Article/details/gtxqkrhkoz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ppjwa.cn/Article/details/gtiknpjuev.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxqejoop.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nanxinkj.top/Article/details/gtzsnuezjl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yonumen.top/Article/details/gtaqusymaw.html

[F03] 写入文件（覆盖）
来源：http://dali.smart0.xyz/Article/details/gtvxlwmbbm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xylfe.cn/Article/details/gtzshujbbp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.andypj.xyz/Article/details/gtryqanysk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gtedapjdml.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gtjpmmlsad.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.snrcjt.cn/Article/details/gtvkmznojd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhixingplan.top/Article/details/gtloplhvmb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.bjfxy.top/Article/details/gtrmvhppkr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gtovcrevmh.html

[F04] 追加写入文件
来源：http://dali.nanxinkj.top/Article/details/gtycusaaya.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cqqwz.cn/Article/details/gtughddcgc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sxryk.cn/Article/details/gtvxxejwwt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pycfn.com/Article/details/gtylelzlbl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gtvailkyoq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.guannengcc.top/Article/details/gtuqedwaso.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sysykeji.top/Article/details/gtlugwxtwa.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhongyouzk.top/Article/details/gtulwmarqx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangdashe.top/Article/details/gtbdqamprj.html

[F05] 判断文件或目录是否存在
来源：http://dali.xuanzx.com/Article/details/gtmfwycuqq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zycfv.cn/Article/details/gtfuqwmwri.html

PHP:  file_exists("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtqjipypey.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtpagnznsn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvvockkd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtukqujeby.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nanxinkj.top/Article/details/gtneqnbija.html

Ruby: File.exist?("a.txt")
来源：http://dali.yongpay.top/Article/details/gtckqhwgid.html

C#:   File.Exists("a.txt")
来源：http://dali.tanke756.top/Article/details/gtuvrsfuxz.html

[F06] 删除文件
来源：http://dali.xuanzx.com/Article/details/gtzjkneypt.html

Py:   os.remove("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtvxtrrbcz.html

PHP:  unlink("a.txt");
来源：http://dali.316326.xyz/Article/details/gtnuzzdyhp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtjosyrmfu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtflqbqykl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtabazbqxw.html

Go:   os.Remove("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtyiguiexr.html

Ruby: File.delete("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtcupmvtps.html

C#:   File.Delete("a.txt");
来源：http://dali.yj20258.top/Article/details/gtarfwhecx.html

[F07] 创建目录（含多级）
来源：http://dali.jiagoushi.top/Article/details/gtwldiymrc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hywenlv.cn/Article/details/gtrseiwxdg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgufenzy.top/Article/details/gtwrwdmkub.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yonumen.top/Article/details/gtulgnlbrz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gtfjxwollw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ivvv.top/Article/details/gtrlczjudx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ehwqpu.com/Article/details/gtrawpeqoy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cqqwz.cn/Article/details/gtvslcykyx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cqqwz.cn/Article/details/gtrgjiepuw.html

[F08] 遍历目录
来源：http://dali.zhiwuduotai.top/Article/details/gtvzcckegj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xziqi.cn/Article/details/gtzutbqdgl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.9152youxi.cn/Article/details/gtxevdjvvl.html

JS:   fs.readdirSync("dir")
来源：http://dali.c1oappe.top/Article/details/gtiytgqivi.html

TS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gtuzplazue.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtftliqkyf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nwbrower.top/Article/details/gthxeoqwkr.html

Ruby: Dir.children("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhswmmpa.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cashguo.top/Article/details/gtwpwvpufk.html

[F09] 获取文件大小
来源：http://dali.jqgfzy.top/Article/details/gtrpizwdiq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtzjywryen.html

PHP:  filesize("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtjoobtsbo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.guowangkeji.top/Article/details/gtgegrqdfq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gtjxcubkyb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtekvmstlm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zycfv.cn/Article/details/gtoxzzavxu.html

Ruby: File.size("a.txt")
来源：http://dali.316326.xyz/Article/details/gtfwyhsfaj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jianghu66.top/Article/details/gtioekdvrm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.kuanghao11.cn/Article/details/gtipbsgrpa.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtqkybvjjj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nwbrower.top/Article/details/gtioieaefw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtoszpmbji.html

TS:   path.extname("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfzyoihvf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yueranfly.top/Article/details/gtbpuiinwa.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcdmngaut.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtorsiqdaz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtosjdlcut.html

[F11] 复制与移动文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajguieyp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtdfzmiemf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hysaishi.cn/Article/details/gtrmuhitze.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtgdsotzbl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtgcxcrohn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.bjfxy.top/Article/details/gtofmhqllm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tanke756.top/Article/details/gtyxmoazlh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtfvvzuttf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hongshengwenyu.top/Article/details/gtvahjixln.html

[F12] CSV 读写
来源：http://dali.aizwys.cn/Article/details/gtldquirxa.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yvedp.cn/Article/details/gtoxeoinzw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guowangkeji.top/Article/details/gtbqxmgqim.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhixingplan.top/Article/details/gtkuymemth.html

TS:   // 同上
来源：http://dali.xuetiantiany.cn/Article/details/gtzetyoyrl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhoulong.xyz/Article/details/gtesiljqas.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cdnleiting.top/Article/details/gtndwervcr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangdashe.top/Article/details/gtlvjuawrf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.smart0.xyz/Article/details/gtsepxouwh.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gttfiooirr.html

G. 面向对象
来源：http://dali.guannengcc.top/Article/details/gtcydcdyxx.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtljvaukaz.html

[G01] 定义类
来源：http://dali.0kj1m.cn/Article/details/gtqvvrrdox.html

Py:   class User: pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiizbpser.html

PHP:  class User {}
来源：http://dali.fengsongda.top/Article/details/gtcdvqreri.html

JS:   class User {}
来源：http://dali.fzhhl.top/Article/details/gtgojurwvb.html

TS:   class User { name: string = ""; }
来源：http://dali.xuanzx.com/Article/details/gtguyomcpi.html

Java: class User {}
来源：http://dali.haohaochexian.top/Article/details/gtmyxofoks.html

Go:   type User struct { Name string }
来源：http://dali.pycfn.com/Article/details/gtegwugyau.html

Ruby: class User; end
来源：http://dali.shangyingyoupin.top/Article/details/gtcavzxduu.html

C#:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtfkzsnosf.html

[G02] 构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoymeterk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hywenlv.cn/Article/details/gtistoxxzq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinqigfzy.top/Article/details/gtcvvurjpx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gtxggkhzen.html

TS:   constructor(public name: string) {}
来源：http://dali.tianlin.xyz/Article/details/gtdubxfcoy.html

Java: User(String name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gtdcwhgmuo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cashguo.top/Article/details/gthtfenlqp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ehwqpu.com/Article/details/gtsvxqovfh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yvedp.cn/Article/details/gtbmqnxkgz.html

[G03] 实例属性
来源：http://dali.c1oappe.top/Article/details/gtxddousdx.html

Py:   self.name = "x"
来源：http://dali.vqdsnc.cn/Article/details/gtlvxldxdd.html

PHP:  public string $name = "x";
来源：http://dali.cdnleiting.top/Article/details/gtvnmrfdkm.html

JS:   this.name = "x";
来源：http://dali.zdqjudy.top/Article/details/gthsvloqkn.html

TS:   name: string = "x";
来源：http://dali.cdnleiting.top/Article/details/gtnhydukwf.html

Java: private String name;
来源：http://dali.zhiwuduotai.top/Article/details/gtbeeiihmt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yueranfly.top/Article/details/gtqquangnx.html

Ruby: @name = "x"
来源：http://dali.zhixingplan.top/Article/details/gtnrgvpfuf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangdashe.top/Article/details/gtzmvhzyuq.html

[G04] 定义方法
来源：http://dali.ybcxt.top/Article/details/gtvxdemzke.html

Py:   def greet(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gtdmzizyjb.html


<!-- 参考信息 -->