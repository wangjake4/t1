代发 wailian999

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gzhubu.top/Article/details/gtcufotpsl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jiagoushi.top/Article/details/gtkccvurvy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj20258888.top/Article/details/gtmwwvohym.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yueranfly.top/Article/details/gtnmkhbpqv.html

[E06] 替换子串
来源：http://dali.tanke756.top/Article/details/gtwygcblns.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.dianchejie.cn/Article/details/gtzqfysyyq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtthvbkaat.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtppykkqoc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtdzcrpgmj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtcftrhkij.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hywenlv.cn/Article/details/gtasnzqklj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtzwgujhpr.html

C#:   s.Replace("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtmecnzeqz.html

[E07] 按分隔符拆分
来源：http://dali.haohaochexian.top/Article/details/gtgxlqawbz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cucudq.cn/Article/details/gtkajrrsit.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yvedp.cn/Article/details/gtmtrhhkhy.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zdqjudy.top/Article/details/gtpeitxqbm.html

TS:   s.split(",")
来源：http://dali.daxiang520.top/Article/details/gtayrbcwjy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xylfe.cn/Article/details/gtckmiiicr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zycfv.cn/Article/details/gtwjpiqmax.html

Ruby: s.split(",");  s.split
来源：http://dali.fzhhl.top/Article/details/gtuinbaggp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.daxiang520.top/Article/details/gtzwdwbiqu.html

[E08] 数组按分隔符合并
来源：http://dali.daria6918.cn/Article/details/gthebtkpcp.html

Py:   ",".join(items)
来源：http://dali.yonumen.top/Article/details/gtibywmptn.html

PHP:  implode(",", $items);
来源：http://dali.nanxuanxn.top/Article/details/gtnnchyedt.html

JS:   items.join(",")
来源：http://dali.iojbl.cn/Article/details/gtuplcdvat.html

TS:   items.join(",")
来源：http://dali.yonumen.top/Article/details/gtezthhioz.html

Java: String.join(",", items)
来源：http://dali.chenlongwang.top/Article/details/gtxgkxgvnr.html

Go:   strings.Join(items, ",")
来源：http://dali.nanxinkj.top/Article/details/gtsolhirgi.html

Ruby: items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gtleukhvmr.html

C#:   string.Join(",", items)
来源：http://dali.quarkkingdee.top/Article/details/gtgrohepsh.html

[E09] 去除所有空白字符
来源：http://dali.gogol.net.cn/Article/details/gtuwjwweez.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yanxiufei.cn/Article/details/gtumtoahhq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yuanzhike.top/Article/details/gttkjdkoph.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yuxming.cn/Article/details/gtimlessye.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shangyingyoupin.top/Article/details/gtuqqnublw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ppjwa.cn/Article/details/gtwmtkfooy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvawabyuz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhongyouzk.top/Article/details/gtdwpwauob.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yangfankeji.com/Article/details/gtqidbgcpf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.fzhhl.top/Article/details/gtjrcqizre.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.316326.xyz/Article/details/gtcphhdqgy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cdnleiting.top/Article/details/gtpfwvcnjt.html

JS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gtfedsqpuo.html

TS:   "7".padStart(3, "0")
来源：http://dali.cucudq.cn/Article/details/gtrngretrw.html

Java: String.format("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtnbmeemmi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gtwlniqjvn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gtrgpscbku.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.wangshuangyany.cn/Article/details/gtrjfwstzz.html

[E11] 反转字符串
来源：http://dali.ydzc1.top/Article/details/gtzzvkoiip.html

Py:   s[::-1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwwnnkmd.html

PHP:  strrev($s);
来源：http://dali.jinqigufen.top/Article/details/gtkkvsdpzs.html

JS:   [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gtugpwynvk.html

TS:   [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtlfecvhzp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cheryme.top/Article/details/gtefttzltt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sweek.top/Article/details/gtxzcusxij.html

Ruby: s.reverse
来源：http://dali.cdnleiting.top/Article/details/gtwvjdujxv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gtwarulmol.html

[E12] 统计某字符出现次数
来源：http://dali.zhongyouzk.top/Article/details/gtazmppucr.html

Py:   s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqcgiozj.html

PHP:  substr_count($s, "a");
来源：http://dali.cucudq.cn/Article/details/gtdbzmijho.html

JS:   s.split("a").length - 1
来源：http://dali.tianlin.xyz/Article/details/gtgwidtnxw.html

TS:   s.split("a").length - 1
来源：http://dali.zhiwuduotai.top/Article/details/gtylcqhjxe.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gogol.net.cn/Article/details/gtqbhgfgta.html

Go:   strings.Count(s, "a")
来源：http://dali.aibaodan.cn/Article/details/gtrkjqjqiy.html

Ruby: s.count("a")
来源：http://dali.yj202588.top/Article/details/gtiqfziqbb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.bjfxy.top/Article/details/gtipbmntgu.html

[E13] 逐字符遍历
来源：http://dali.cdnleiting.top/Article/details/gtmgzbfknu.html

Py:   for ch in s: print(ch)
来源：http://dali.yuanzhike.top/Article/details/gtjsajtdgs.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenjidiqi.icu/Article/details/gtawsmzkfr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.haohaochexian.top/Article/details/gtyvoekcyy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.andypj.xyz/Article/details/gtfravhidf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtstkrlkck.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.pycfn.com/Article/details/gtspcvtxon.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonavirwo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtufxqgaaw.html

[E14] URL 编码与 Base64
来源：http://dali.c1oappe.top/Article/details/gtrzijgcjr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zycfv.cn/Article/details/gtsxgefhop.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gaohongyu789.top/Article/details/gtuqzkybum.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.mhx1999.top/Article/details/gtjrekiynx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gogol.net.cn/Article/details/gtgumeynwj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sysykeji.top/Article/details/gtbdigibzf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zdqjudy.top/Article/details/gtkzdnntut.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttykkhoga.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ivvv.top/Article/details/gtepcngeqr.html

[E15] HTML 转义 / 反转义
来源：http://dali.dianchejie.cn/Article/details/gthhnytwoi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hfpthk.cn/Article/details/gtlnxknqpx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nwbrower.top/Article/details/gtehksfmax.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hnqzz.top/Article/details/gtjvtkwzvo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yanxiufei.cn/Article/details/gtukhdgunj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zycfv.cn/Article/details/gtodqpftsw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzprdabjr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykgvgjee.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhengqikj.top/Article/details/gtqufvfbbg.html

[E16] 数字千分位
来源：http://dali.yonumen.top/Article/details/gtanvyijjt.html

Py:   f"{1234567:,}"
来源：http://dali.hysaishi.cn/Article/details/gtqsutzkdu.html

PHP:  number_format(1234567);
来源：http://dali.yuxming.cn/Article/details/gtsphqaidv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yvedp.cn/Article/details/gtmwtlftjw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ppjwa.cn/Article/details/gtczntvsfk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.pycfn.com/Article/details/gtvnoibkio.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cqqwz.cn/Article/details/gtqqgyvxfx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtwnmuhsgi.html

C#:   1234567.ToString("N0")
来源：http://dali.jinqigufen.top/Article/details/gtnoydsqfe.html

[E17] 首字母大写
来源：http://dali.zhiwuduotai.top/Article/details/gtmvvlwemz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nanxuanxn.top/Article/details/gtdrlbvcys.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvszwydip.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtvjyhhnxl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.0kj1m.cn/Article/details/gttmlerjey.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hammf.cn/Article/details/gtnpmgedhc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhoulong.xyz/Article/details/gthcsqzvez.html

Ruby: s.capitalize
来源：http://dali.aibaodan.cn/Article/details/gtknhlvlri.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtboprwfsv.html

[E18] 模板占位符替换
来源：http://dali.havefunace.top/Article/details/gtnvvfcgjz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sxryk.cn/Article/details/gtaerfrusu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.mhx1999.top/Article/details/gtwwjjbwyj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj202588.top/Article/details/gtaikairoe.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gtccrkgxnf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtttgoegpk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gtmkheqcrz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jqgfzy.top/Article/details/gtvofmbwcl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ppjwa.cn/Article/details/gtpbqmdsyn.html

[E19] 多行文本按行拆分
来源：http://dali.gaohongyu789.top/Article/details/gthjuczcur.html

Py:   s.splitlines()
来源：http://dali.chenzaomai.com/Article/details/gtyppqdhna.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gzhubu.top/Article/details/gtcpicmpyt.html

JS:   s.split(/\r?\n/)
来源：http://dali.hfpthk.cn/Article/details/gtysjivxgm.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenlongwang.top/Article/details/gtohsctyjl.html

Java: s.lines().toList()
来源：http://dali.nanxuanxn.top/Article/details/gtkmzuoaio.html

Go:   strings.Split(s, "\n")
来源：http://dali.hywenlv.cn/Article/details/gtqmustvap.html

Ruby: s.lines
来源：http://dali.haohaochexian.top/Article/details/gtwsgaupsg.html

C#:   s.Split('\n')
来源：http://dali.zycfv.cn/Article/details/gtfkpwmagq.html

[E20] 判断字符串是否为空
来源：http://dali.cucudq.cn/Article/details/gtpoqfuwzb.html

Py:   if not s:
来源：http://dali.fzhhl.top/Article/details/gtqgsjmsqc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenzaomai.com/Article/details/gtgfgkvzmu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.dianchejie.cn/Article/details/gtwdllqkbz.html

TS:   if (s === "") {}
来源：http://dali.jyoumei.cn/Article/details/gtvhkugrnm.html

Java: if (s.isEmpty()) {}
来源：http://dali.aizwys.cn/Article/details/gtgvfrzueo.html

Go:   if s == "" {}
来源：http://dali.kuanghao11.cn/Article/details/gtqufjyfco.html

Ruby: if s.empty?
来源：http://dali.gogol.net.cn/Article/details/gtjsvlwhzo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnilbxcoo.html

[E21] 超长截断加省略号
来源：http://dali.chenlongwang.top/Article/details/gtrbsulxcf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhixingplan.top/Article/details/gthgzwcbqp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtepijdyho.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtkwgceaex.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtoekrafzj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtkjqybhjd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gogol.net.cn/Article/details/gtpbdwuass.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtyuepgvin.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtjwrqchzk.html

[E22] 字节长度与字符长度
来源：http://dali.nanxuanxn.top/Article/details/gtyfypdvmv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.kuanghao11.cn/Article/details/gtlaqpdhvd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gtstklqrqw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shzxlz.cn/Article/details/gtqqiqarei.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuanzx.com/Article/details/gtfqhtuzxp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangdashe.top/Article/details/gtudcvcybs.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.meibo888.top/Article/details/gtfjinavpz.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj202588.top/Article/details/gtqogdyuhm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.daxiang520.top/Article/details/gtwfyohknn.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtversvaix.html

F. 文件与目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxznxwyo.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtwigwtxzx.html

[F01] 读取整个文件
来源：http://dali.yj20258888.top/Article/details/gtslmuoeov.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.wangshuangyany.cn/Article/details/gtopzhzluz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtfvbvzwxg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ehwqpu.com/Article/details/gtafpdsnnd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gtsakqpvae.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtnknasdeq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shanyushiyangkeji.top/Article/details/gthtucvfvw.html

Ruby: File.read("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtygdifwnw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtpeplltnh.html

[F02] 逐行读取文件
来源：http://dali.yangfankeji.com/Article/details/gtmsfblnpj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jqgufenzy.top/Article/details/gtnawaecwm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sxryk.cn/Article/details/gtrngazzdu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtesytftad.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gttwtcmujs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtltmfhfle.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlehfdtvf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nanxuanxn.top/Article/details/gtcunjranc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sufxvd.cn/Article/details/gtcxdszqcj.html

[F03] 写入文件（覆盖）
来源：http://dali.hnxiangtu.top/Article/details/gtqgmrtavu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hywenlv.cn/Article/details/gtwfjuvbso.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gtmbahntwn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuuekvvqa.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gtdhlfdeqh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.guowangkeji.top/Article/details/gtslxyksbw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jlsjyb.cn/Article/details/gttqhjvizk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.feifeiyinyue.top/Article/details/gtrfrspfdj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gtniypuvyt.html

[F04] 追加写入文件
来源：http://dali.birdmap.top/Article/details/gtsczewuex.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtrjykphvn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.quarkkingdee.top/Article/details/gtafrktqxi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtfxpdttsw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ehwqpu.com/Article/details/gtmyzoxxcm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhixingplan.top/Article/details/gtjumxujol.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.guowangkeji.top/Article/details/gtmowzwetq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shangyingyoupin.top/Article/details/gtosscnsdr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yanxiufei.cn/Article/details/gtvccefdzu.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigufen.top/Article/details/gtfsxlqqjh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zdqjudy.top/Article/details/gtsotjqank.html

PHP:  file_exists("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtxwqgtlpn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtawydleez.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtwmvqlgxg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtuewblrch.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hysaishi.cn/Article/details/gthkkeisbq.html

Ruby: File.exist?("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtzshvscgo.html

C#:   File.Exists("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtrjlrrmwy.html

[F06] 删除文件
来源：http://dali.0kj1m.cn/Article/details/gtthljmpih.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gtuawbgbzh.html

PHP:  unlink("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtvdeisysh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gttczdkiio.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gttzmhiykw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gtelzlhjpp.html

Go:   os.Remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtjkygxgwz.html

Ruby: File.delete("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtxeewbmva.html

C#:   File.Delete("a.txt");
来源：http://dali.yongpay.top/Article/details/gthhwtwccp.html

[F07] 创建目录（含多级）
来源：http://dali.vqdsnc.cn/Article/details/gtdxykdwhe.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xziqi.cn/Article/details/gtuhvqohuu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tanke756.top/Article/details/gtqwcjpnmq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gtiyddgddn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.andypj.xyz/Article/details/gtzsabhcix.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.birdmap.top/Article/details/gtelqlsgye.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyyrbxnsw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daxiang520.top/Article/details/gtmqdwjemp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.kuanghao11.cn/Article/details/gtomktlahz.html

[F08] 遍历目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcdhlkwbu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.andypj.xyz/Article/details/gtjkcdhjdv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ydzc1.top/Article/details/gthvgqgkwi.html

JS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gthxkfavup.html

TS:   fs.readdirSync("dir")
来源：http://dali.hysaishi.cn/Article/details/gtqcrzeuwx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shangyingyoupin.top/Article/details/gtjevwfepi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xziqi.cn/Article/details/gtrkjofxxz.html

Ruby: Dir.children("dir")
来源：http://dali.fengsongda.top/Article/details/gtclrnaisv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj20258.top/Article/details/gthajwhhgf.html

[F09] 获取文件大小
来源：http://dali.jinqigfzy.top/Article/details/gtqfzrhzgz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtexxeonth.html

PHP:  filesize("a.txt");
来源：http://dali.cheryme.top/Article/details/gtvurtrsde.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jianghu66.top/Article/details/gtncxpaywe.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hfpthk.cn/Article/details/gtdioyzzvy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gtpqrfxpid.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhongyouzk.top/Article/details/gtblfavbsb.html

Ruby: File.size("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gthdkoahvg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenjidiqi.icu/Article/details/gtdrulrgrj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xylfe.cn/Article/details/gtlftprwpl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtewownapu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtcrgtjbqg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gthmwwzotd.html

TS:   path.extname("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtdchrhigc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shangyingyoupin.top/Article/details/gtpjrzocnx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtkoiqipfs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtozhmmoad.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gttlfedoop.html

[F11] 复制与移动文件
来源：http://dali.gogol.net.cn/Article/details/gtplghuvzm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gtjwgrdoph.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtenetiicp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gtduervboi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtjmmklrrw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tianlin.xyz/Article/details/gtalpnpxjy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gzhubu.top/Article/details/gtyipcnvfg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtrvoyvbya.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jyoumei.cn/Article/details/gtljrljhau.html

[F12] CSV 读写
来源：http://dali.hnxiangtu.top/Article/details/gtnhabducm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.c1oappe.top/Article/details/gtqimuidkl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shzxlz.cn/Article/details/gtzkaqkpxf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.havefunace.top/Article/details/gthiwvpytu.html

TS:   // 同上
来源：http://dali.9152youxi.cn/Article/details/gtcjoossmg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hysaishi.cn/Article/details/gthwwyvtbq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.kuanghao11.cn/Article/details/gttiyrjxby.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.svipenyu.cn/Article/details/gtbuyupbay.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuxming.cn/Article/details/gtztvxqchg.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtucpscnty.html

G. 面向对象
来源：http://dali.quarkkingdee.top/Article/details/gtxybfchnl.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtkwvvjhov.html

[G01] 定义类
来源：http://dali.yvedp.cn/Article/details/gtyhcrtzqu.html

Py:   class User: pass
来源：http://dali.dianchejie.cn/Article/details/gtnizweckm.html

PHP:  class User {}
来源：http://dali.chenzaomai.com/Article/details/gtbkgllvgh.html

JS:   class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlrqqiple.html

TS:   class User { name: string = ""; }
来源：http://dali.haohaochexian.top/Article/details/gtidjujvlj.html

Java: class User {}
来源：http://dali.pycfn.com/Article/details/gtunsbmoux.html

Go:   type User struct { Name string }
来源：http://dali.yonumen.top/Article/details/gtcvlvirgb.html

Ruby: class User; end
来源：http://dali.yj20258888.top/Article/details/gttyqcyceg.html

C#:   class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtslpqfqol.html

[G02] 构造函数
来源：http://dali.xylfe.cn/Article/details/gtysvtinvg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlbzzwnhx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinqigufen.top/Article/details/gtceprtdtq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zdqjudy.top/Article/details/gtgcbshklh.html

TS:   constructor(public name: string) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtaspvdduy.html

Java: User(String name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gttzztswoo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jiagoushi.top/Article/details/gtnnefaxhm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ehwqpu.com/Article/details/gtiegmlatq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtbknqckxf.html

[G03] 实例属性
来源：http://dali.haohaochexian.top/Article/details/gtknzlyfxe.html

Py:   self.name = "x"
来源：http://dali.iojbl.cn/Article/details/gtlwiquftk.html

PHP:  public string $name = "x";
来源：http://dali.smart0.xyz/Article/details/gtttuivnmx.html

JS:   this.name = "x";
来源：http://dali.birdmap.top/Article/details/gtxxeowjdo.html

TS:   name: string = "x";
来源：http://dali.aizwys.cn/Article/details/gtnjxbdgdu.html

Java: private String name;
来源：http://dali.c1oappe.top/Article/details/gtebuecogo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nwbrower.top/Article/details/gtwxmyewav.html

Ruby: @name = "x"
来源：http://dali.chenlongwang.top/Article/details/gtkggebkya.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtzclaogbc.html

[G04] 定义方法
来源：http://dali.gzhubu.top/Article/details/gtnlcodvlu.html

Py:   def greet(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gthbbcccsn.html


<!-- 参考信息 -->