代发 wailian999

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.redwolf501.top/Article/details/gtthkppjgy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.0kj1m.cn/Article/details/gtegmjgppj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gtdjruyikk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.vqdsnc.cn/Article/details/gtuzicfkdi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gtwildbtul.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gaohongyu789.top/Article/details/gtifhhfhxf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hnxiangtu.top/Article/details/gtlrswknag.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.daria6918.cn/Article/details/gtrmowunbn.html

[E06] 替换子串
来源：http://dali.pengpengdd.cyou/Article/details/gthewpswnt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gtelljdfgg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtplxyfkkm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtsqrxhkew.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtrkcmqwmn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtlbpzzkij.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cashguo.top/Article/details/gtecgydctj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtsorjvdwf.html

C#:   s.Replace("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtorzbpvpn.html

[E07] 按分隔符拆分
来源：http://dali.yuanzhike.top/Article/details/gtdfseuwrj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsctvdsjr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.havefunace.top/Article/details/gtfxvmkxxg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.c1oappe.top/Article/details/gtsjislabc.html

TS:   s.split(",")
来源：http://dali.xylfe.cn/Article/details/gtfttdzhoe.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.wangdashe.top/Article/details/gtxyjazoww.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ppjwa.cn/Article/details/gtrbumtxtz.html

Ruby: s.split(",");  s.split
来源：http://dali.shangyingyoupin.top/Article/details/gtfcydoona.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.guowangkeji.top/Article/details/gtuglwfgna.html

[E08] 数组按分隔符合并
来源：http://dali.redwolf501.top/Article/details/gtfzghuzhk.html

Py:   ",".join(items)
来源：http://dali.jianghu66.top/Article/details/gtymmgwkco.html

PHP:  implode(",", $items);
来源：http://dali.sufxvd.cn/Article/details/gtoxtshsuz.html

JS:   items.join(",")
来源：http://dali.hammf.cn/Article/details/gtuhmormuq.html

TS:   items.join(",")
来源：http://dali.yuxming.cn/Article/details/gtvgtjrgxu.html

Java: String.join(",", items)
来源：http://dali.ivvv.top/Article/details/gtvmfjfegv.html

Go:   strings.Join(items, ",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjtkatgpd.html

Ruby: items.join(",")
来源：http://dali.cheryme.top/Article/details/gtenibgvll.html

C#:   string.Join(",", items)
来源：http://dali.hywenlv.cn/Article/details/gtilzhxwcq.html

[E09] 去除所有空白字符
来源：http://dali.daria6918.cn/Article/details/gtjsaiqdpa.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.vqdsnc.cn/Article/details/gtfrkczsll.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sxryk.cn/Article/details/gtaqiqchsc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gtldufxauu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtgxvkxyfx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sxryk.cn/Article/details/gtfrgyytsc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tanke756.top/Article/details/gtyjlklqjk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sweek.top/Article/details/gtmxegbafz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.tanke756.top/Article/details/gtvavqfonf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tanke756.top/Article/details/gtmdwfssuu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbonylytw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvxaengur.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gtzncvkuzq.html

TS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtgxqsyznd.html

Java: String.format("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gtxderglnb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gtfwcjphez.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gtnjtmydwb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gotoacloud.top/Article/details/gtjmxzkwys.html

[E11] 反转字符串
来源：http://dali.nwbrower.top/Article/details/gtjymjcybh.html

Py:   s[::-1]
来源：http://dali.birdmap.top/Article/details/gtsybxxyel.html

PHP:  strrev($s);
来源：http://dali.xziqi.cn/Article/details/gtyhosrdhm.html

JS:   [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtyvrdczch.html

TS:   [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtvahsddfq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zycfv.cn/Article/details/gtaajucllb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.wangdashe.top/Article/details/gtkpwgxrjq.html

Ruby: s.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtverzldlz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sxryk.cn/Article/details/gtfxhbckkz.html

[E12] 统计某字符出现次数
来源：http://dali.chenjidiqi.icu/Article/details/gtaayhjosj.html

Py:   s.count("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtieisxbde.html

PHP:  substr_count($s, "a");
来源：http://dali.yj202588.top/Article/details/gtbctciacu.html

JS:   s.split("a").length - 1
来源：http://dali.aibaodan.cn/Article/details/gtngpupvms.html

TS:   s.split("a").length - 1
来源：http://dali.gotoacloud.top/Article/details/gtmtyyxsoo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.vqdsnc.cn/Article/details/gtnfgfppbx.html

Go:   strings.Count(s, "a")
来源：http://dali.aibaodan.cn/Article/details/gtugylxbmm.html

Ruby: s.count("a")
来源：http://dali.cashguo.top/Article/details/gtkhdoqvue.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hywenlv.cn/Article/details/gtejcjizke.html

[E13] 逐字符遍历
来源：http://dali.smart0.xyz/Article/details/gtgezocpsv.html

Py:   for ch in s: print(ch)
来源：http://dali.dashuyun.cn/Article/details/gtxvswdnhx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ppjwa.cn/Article/details/gtbehatjua.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ybcxt.top/Article/details/gtnjovpdze.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtxerccdna.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.dianchejie.cn/Article/details/gttomttzbn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jianghu66.top/Article/details/gtzkaoxkri.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhongyouzk.top/Article/details/gtukdwknoi.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ybcxt.top/Article/details/gtizqmlnmg.html

[E14] URL 编码与 Base64
来源：http://dali.wangshuangyany.cn/Article/details/gtuemeotla.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gzhubu.top/Article/details/gtfzxuydgi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jqgfzy.top/Article/details/gttllnhrkk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zdqjudy.top/Article/details/gtrznrfdue.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.dianchejie.cn/Article/details/gtxssgjifz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cqqwz.cn/Article/details/gtvdhnfloe.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.guowangkeji.top/Article/details/gtctmdlffc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhixingplan.top/Article/details/gtawkmarrg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.iojbl.cn/Article/details/gtsytlybya.html

[E15] HTML 转义 / 反转义
来源：http://dali.yongpay.top/Article/details/gtstvnvufa.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sysykeji.top/Article/details/gtlifcbpas.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yueranfly.top/Article/details/gtgfsydgqf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.aibaodan.cn/Article/details/gtrenaeinc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cashguo.top/Article/details/gtxyqyaifr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zdqjudy.top/Article/details/gtkpayhoei.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtymnhxvyl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhoulong.xyz/Article/details/gtwtgjjwod.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinqigfzy.top/Article/details/gtrfojsbfz.html

[E16] 数字千分位
来源：http://dali.birdmap.top/Article/details/gtukrzgsjr.html

Py:   f"{1234567:,}"
来源：http://dali.hongshengwenyu.top/Article/details/gtqlkabzkm.html

PHP:  number_format(1234567);
来源：http://dali.kuanghao11.cn/Article/details/gtegswfcik.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.snrcjt.cn/Article/details/gtnskjleym.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jlsjyb.cn/Article/details/gttzudlmhu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhixingplan.top/Article/details/gtriyskpwv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jlsjyb.cn/Article/details/gtbktofyaw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yj202588.top/Article/details/gtksmmtntg.html

C#:   1234567.ToString("N0")
来源：http://dali.gotoacloud.top/Article/details/gtkigtlyhd.html

[E17] 首字母大写
来源：http://dali.hongshengwenyu.top/Article/details/gtjmxewbav.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yonumen.top/Article/details/gtnjaznzsn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj20258888.top/Article/details/gtnhcboenc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cdnleiting.top/Article/details/gtumyqdnnv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.mhx1999.top/Article/details/gtayfkheae.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.svipenyu.cn/Article/details/gtgeloxwcw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sweek.top/Article/details/gtrietpgoj.html

Ruby: s.capitalize
来源：http://dali.zhongyouzk.top/Article/details/gtfdggihxw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zycfv.cn/Article/details/gtsbgjnuzu.html

[E18] 模板占位符替换
来源：http://dali.nwbrower.top/Article/details/gtqlvcqqfp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqijqdzm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrlfwtzef.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmkgurfen.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hammf.cn/Article/details/gtwydafmgi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtkgxamhbv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtznifsilr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gaohongyu789.top/Article/details/gtpuyrjelw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhongyouzk.top/Article/details/gtlhuqpily.html

[E19] 多行文本按行拆分
来源：http://dali.tianlin.xyz/Article/details/gtxeunruzp.html

Py:   s.splitlines()
来源：http://dali.xuanzx.com/Article/details/gtdctkcdpm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.iojbl.cn/Article/details/gtafywjgzp.html

JS:   s.split(/\r?\n/)
来源：http://dali.nanxuanxn.top/Article/details/gtuiofgstw.html

TS:   s.split(/\r?\n/)
来源：http://dali.tanke756.top/Article/details/gtwnxkgeqk.html

Java: s.lines().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gthazidemt.html

Go:   strings.Split(s, "\n")
来源：http://dali.tanke756.top/Article/details/gtqvusjkjv.html

Ruby: s.lines
来源：http://dali.tianlin.xyz/Article/details/gtlxbhynbv.html

C#:   s.Split('\n')
来源：http://dali.zycfv.cn/Article/details/gtsmoxwaoc.html

[E20] 判断字符串是否为空
来源：http://dali.c1oappe.top/Article/details/gtisfjnsrm.html

Py:   if not s:
来源：http://dali.gogol.net.cn/Article/details/gtjdcvhqnt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sufxvd.cn/Article/details/gtvqdkadep.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jlsjyb.cn/Article/details/gtyspdzziz.html

TS:   if (s === "") {}
来源：http://dali.wangshuangyany.cn/Article/details/gtyttudzax.html

Java: if (s.isEmpty()) {}
来源：http://dali.shzxlz.cn/Article/details/gtkgxbvoqj.html

Go:   if s == "" {}
来源：http://dali.chenlongwang.top/Article/details/gtzjrrpmhp.html

Ruby: if s.empty?
来源：http://dali.shanyushiyangtech.top/Article/details/gtaafytmgi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.vqdsnc.cn/Article/details/gtnwoyxjwx.html

[E21] 超长截断加省略号
来源：http://dali.shuidangran.top/Article/details/gtoorptxji.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ydzc1.top/Article/details/gtzcpqlsfw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtutfxgquq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtjfdadcnj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtceaooqrb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtqqebwszy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj20258.top/Article/details/gtaysytrir.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtllagywef.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtwpwpixvu.html

[E22] 字节长度与字符长度
来源：http://dali.tianlin.xyz/Article/details/gtcihqdbks.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hysaishi.cn/Article/details/gtwyuzuqer.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gtkoeojlnf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtjuqiscie.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtlioeyyhe.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvngfjuq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ivvv.top/Article/details/gtknkoigmo.html

Ruby: s.bytesize;  s.length
来源：http://dali.xylfe.cn/Article/details/gteafhcmwy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tanke756.top/Article/details/gtddzrbnip.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtypzzyjjv.html

F. 文件与目录
来源：http://dali.vqdsnc.cn/Article/details/gtagmvpnwq.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtfzndqdfj.html

[F01] 读取整个文件
来源：http://dali.wangshuangyany.cn/Article/details/gtmgukpcld.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jiagoushi.top/Article/details/gtjvymfgez.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gttliqaumm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jianghu66.top/Article/details/gtdndkabhj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gtlmbcminn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gteifowaff.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.feifeiyinyue.top/Article/details/gtxexygbjv.html

Ruby: File.read("a.txt")
来源：http://dali.316326.xyz/Article/details/gtfsfkvzvk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtjhilurqg.html

[F02] 逐行读取文件
来源：http://dali.havefunace.top/Article/details/gtasechpco.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hnxiangtu.top/Article/details/gtbvpzpvyx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sxryk.cn/Article/details/gtywangpca.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gteezmwkqn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuxming.cn/Article/details/gtjwnldqlg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yuanzhike.top/Article/details/gtzkfaiovn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cqqwz.cn/Article/details/gtkzzrfmpe.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhongyouzk.top/Article/details/gtiisoyxox.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.0kj1m.cn/Article/details/gttlnrczyq.html

[F03] 写入文件（覆盖）
来源：http://dali.tian-w.cn/Article/details/gtxtytaeov.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zycfv.cn/Article/details/gtbwnnkfoe.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gzhubu.top/Article/details/gtdyeywoaz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nwbrower.top/Article/details/gtzlbbonlo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sweek.top/Article/details/gtfumfcuvb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nanxuanxn.top/Article/details/gtjyrnvalf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuanzx.com/Article/details/gtyrtjjpnc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.iojbl.cn/Article/details/gtvxillggb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.havefunace.top/Article/details/gtpuafkkzv.html

[F04] 追加写入文件
来源：http://dali.ppjwa.cn/Article/details/gtsjxnbaqr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cdnleiting.top/Article/details/gtwqlthuru.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.bjfxy.top/Article/details/gtyywfkmwo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cqqwz.cn/Article/details/gtoareiyzv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ydzc1.top/Article/details/gtplxadcmr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.daxiang520.top/Article/details/gtkkisuuid.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.dashuyun.cn/Article/details/gtxiivfyot.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnkbxedoo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinghuilouyu.cn/Article/details/gtazzmkwjc.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmnhaqrgj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hammf.cn/Article/details/gtvthjepmj.html

PHP:  file_exists("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gteutxhecg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtgbzgkygt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtjgyumwqr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtlmkknfsm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.andypj.xyz/Article/details/gtixtdmyth.html

Ruby: File.exist?("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtwtznukej.html

C#:   File.Exists("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtxeaktlco.html

[F06] 删除文件
来源：http://dali.havefunace.top/Article/details/gtqdcmynfc.html

Py:   os.remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gtfecqvtis.html

PHP:  unlink("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtyslamnro.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtfwtsqsuv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtchnhhjac.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gtmzaamohg.html

Go:   os.Remove("a.txt")
来源：http://dali.ivvv.top/Article/details/gticeuvkxp.html

Ruby: File.delete("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtxrfqetlm.html

C#:   File.Delete("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtxeoultgv.html

[F07] 创建目录（含多级）
来源：http://dali.quarkkingdee.top/Article/details/gtuuqyiazl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ybcxt.top/Article/details/gthasskfin.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtxcyzcamf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pycfn.com/Article/details/gtflxwmlaq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tian-w.cn/Article/details/gtxodxnmsj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xuetiantiany.cn/Article/details/gtinshvnyk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.aibaodan.cn/Article/details/gtbihwqaaj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sufxvd.cn/Article/details/gtbvaldfpb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgfzy.top/Article/details/gtzphfgmoo.html

[F08] 遍历目录
来源：http://dali.9152youxi.cn/Article/details/gtkpgqrlna.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cqqwz.cn/Article/details/gtaxgvepgi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhixingplan.top/Article/details/gtnrybdhkh.html

JS:   fs.readdirSync("dir")
来源：http://dali.hywenlv.cn/Article/details/gtladjoogm.html

TS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gtuslrzwma.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gtqmkfleaf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.wangdashe.top/Article/details/gtydygdobf.html

Ruby: Dir.children("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoeyetpph.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ybcxt.top/Article/details/gtshjagwcp.html

[F09] 获取文件大小
来源：http://dali.jqgfzy.top/Article/details/gttohkytck.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tanke756.top/Article/details/gtpbkivqvy.html

PHP:  filesize("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtapeniwes.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsveagzgs.html

TS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gtptvoccjb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtsfkrblkl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjlipohyq.html

Ruby: File.size("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtjtaxudnc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tian-w.cn/Article/details/gtzkkvmstr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xziqi.cn/Article/details/gtkqgusoud.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawdflbfn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258888.top/Article/details/gtgvkxquhb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtclzcahcz.html

TS:   path.extname("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtfzrkbuwd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.snrcjt.cn/Article/details/gtvvsswjfy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtudwilzrj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtfxllxtin.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtuxnnggbq.html

[F11] 复制与移动文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvtvmlnn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtvfbkzubp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.birdmap.top/Article/details/gtqeenvsou.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtgtaesaul.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtawuujhry.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yvedp.cn/Article/details/gtxlvrzbeh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgjgxlpl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtoqjzlbts.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.vqdsnc.cn/Article/details/gtpdpmkhyn.html

[F12] CSV 读写
来源：http://dali.bjfxy.top/Article/details/gtdsfxzogs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gotoacloud.top/Article/details/gtsybvresw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gogol.net.cn/Article/details/gtpcjsvsif.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sysykeji.top/Article/details/gtdogujgcd.html

TS:   // 同上
来源：http://dali.nwbrower.top/Article/details/gtikwsykoc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.svipenyu.cn/Article/details/gthqxpiybu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hongshengwenyu.top/Article/details/gtqhcmgmnc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangdashe.top/Article/details/gtagdzgfyy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ehwqpu.com/Article/details/gtjjltcrdg.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtktigcxob.html

G. 面向对象
来源：http://dali.meibo888.top/Article/details/gtcbwqfgml.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtqljhljio.html

[G01] 定义类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydhxlkjr.html

Py:   class User: pass
来源：http://dali.jqgufenzy.top/Article/details/gtqvffdqdf.html

PHP:  class User {}
来源：http://dali.yonumen.top/Article/details/gtxzdnjvoc.html

JS:   class User {}
来源：http://dali.yj20258.top/Article/details/gtwzjimrcd.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxlbhahig.html

Java: class User {}
来源：http://dali.tanke756.top/Article/details/gtbwcnbdrs.html

Go:   type User struct { Name string }
来源：http://dali.hongshengwenyu.top/Article/details/gtgdqadbof.html

Ruby: class User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpntuecm.html

C#:   class User {}
来源：http://dali.sxryk.cn/Article/details/gtamejfuxf.html

[G02] 构造函数
来源：http://dali.yongpay.top/Article/details/gtqukitcsv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jlsjyb.cn/Article/details/gtxgdczwcc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehswynbq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gtphwaityc.html

TS:   constructor(public name: string) {}
来源：http://dali.daria6918.cn/Article/details/gtyqhlrjho.html

Java: User(String name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtaqrrtstq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.birdmap.top/Article/details/gtkgsrgxmc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zycfv.cn/Article/details/gtalgxqqfy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtouarankw.html

[G03] 实例属性
来源：http://dali.shzxlz.cn/Article/details/gtvqnbnpga.html

Py:   self.name = "x"
来源：http://dali.mhx1999.top/Article/details/gtgstlegac.html

PHP:  public string $name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtarmtybmm.html

JS:   this.name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtzdhoqnat.html

TS:   name: string = "x";
来源：http://dali.bjfxy.top/Article/details/gtrfgurnsf.html

Java: private String name;
来源：http://dali.yongpay.top/Article/details/gtoqxilsgl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sweek.top/Article/details/gtbldainex.html


<!-- 参考信息 -->