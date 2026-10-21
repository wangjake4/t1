代发 wailian999

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gtnprpahun.html

TS:   s.slice(1, 4)
来源：http://dali.sysykeji.top/Article/details/gtljvccsar.html

Java: s.substring(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtfrlycbrr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.snrcjt.cn/Article/details/gtlctovhcq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.daria6918.cn/Article/details/gtlomdrvkm.html

C#:   s.Substring(1, 3)
来源：http://dali.xinyue.icu/Article/details/gtijpmzbiq.html

[E04] 查找子串位置
来源：http://dali.sxryk.cn/Article/details/gtcjhwjyxh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shzxlz.cn/Article/details/gtxhaaeyfr.html

PHP:  strpos($s, "x");
来源：http://dali.yj202588.top/Article/details/gtrvqssdsi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jiagoushi.top/Article/details/gthsaydltw.html

TS:   s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gtlzuslzft.html

Java: s.indexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gtgyypuvdh.html

Go:   strings.Index(s, "x")
来源：http://dali.meibo888.top/Article/details/gtulyqxnab.html

Ruby: s.index("x")
来源：http://dali.daxiang520.top/Article/details/gtppfimbxv.html

C#:   s.IndexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gtnxhomhfa.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xuanzx.com/Article/details/gtipkghoty.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.smart0.xyz/Article/details/gtxtwxjfur.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hammf.cn/Article/details/gtbfnoeglx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gtnqcauoqf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sysykeji.top/Article/details/gtdhetwqkn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.316326.xyz/Article/details/gtpnxokxgp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutnypkfp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhengqikj.top/Article/details/gtobxkaehw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj202588.top/Article/details/gtjlrzvwtd.html

[E06] 替换子串
来源：http://dali.redwolf501.top/Article/details/gtzgrhfpjy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gzhubu.top/Article/details/gtpndaeaop.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtwimvaljd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtslhsytyi.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtxuwwclbm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtaljvcieo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gtonqmavzr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtqgjtbagf.html

C#:   s.Replace("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtyqjvptzx.html

[E07] 按分隔符拆分
来源：http://dali.fzhhl.top/Article/details/gtpdmhylqy.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hysaishi.cn/Article/details/gtakpjdvig.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtrjbzcwue.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yonumen.top/Article/details/gthrueqkyc.html

TS:   s.split(",")
来源：http://dali.haohaochexian.top/Article/details/gtrqpbtrkm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nwbrower.top/Article/details/gtzamjszkk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtxhuraxwi.html

Ruby: s.split(",");  s.split
来源：http://dali.yj20258888.top/Article/details/gtqviipnpt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.iojbl.cn/Article/details/gthdvradmz.html

[E08] 数组按分隔符合并
来源：http://dali.zhoulong.xyz/Article/details/gtsuvplnuw.html

Py:   ",".join(items)
来源：http://dali.yj20258888.top/Article/details/gthbxkaaji.html

PHP:  implode(",", $items);
来源：http://dali.guowangkeji.top/Article/details/gtgnrbydgy.html

JS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtzjhiizfw.html

TS:   items.join(",")
来源：http://dali.yj20258888.top/Article/details/gtxjilpiao.html

Java: String.join(",", items)
来源：http://dali.jinqigfzy.top/Article/details/gtebcbbcqq.html

Go:   strings.Join(items, ",")
来源：http://dali.wangdashe.top/Article/details/gtcvxtxawg.html

Ruby: items.join(",")
来源：http://dali.fzhhl.top/Article/details/gtchpdlplg.html

C#:   string.Join(",", items)
来源：http://dali.chenlongwang.top/Article/details/gtshxllais.html

[E09] 去除所有空白字符
来源：http://dali.fengsongda.top/Article/details/gtxvbumucx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jianghu66.top/Article/details/gtpttakoig.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtkuorqpys.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.snrcjt.cn/Article/details/gtmvaorred.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.daria6918.cn/Article/details/gtkfiowofb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.snrcjt.cn/Article/details/gtcrkyxwxo.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ydzc1.top/Article/details/gtkdhwbnxj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xinyue.icu/Article/details/gtmgnkvxjh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xinyue.icu/Article/details/gtsvfpqaej.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj202588.top/Article/details/gtzkrolfyx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtapiqjmxb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jlsjyb.cn/Article/details/gtnpbhxicn.html

JS:   "7".padStart(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gtkktgdyci.html

TS:   "7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gtstkrkgzc.html

Java: String.format("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gtyvxmafyd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gttigmgrma.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gtxhanirvq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj20258.top/Article/details/gtlwexpfjs.html

[E11] 反转字符串
来源：http://dali.gogol.net.cn/Article/details/gtfqwsshzx.html

Py:   s[::-1]
来源：http://dali.shangyingyoupin.top/Article/details/gtwonospmz.html

PHP:  strrev($s);
来源：http://dali.yj20258.top/Article/details/gttpehiiml.html

JS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtdqpmnwty.html

TS:   [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtjnnqczrf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xylfe.cn/Article/details/gtofpjbbpw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenlongwang.top/Article/details/gtaevuptyu.html

Ruby: s.reverse
来源：http://dali.sxryk.cn/Article/details/gtiyuaenpi.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.birdmap.top/Article/details/gtlpbeblrg.html

[E12] 统计某字符出现次数
来源：http://dali.shanyushiyangkeji.top/Article/details/gthlmuqyul.html

Py:   s.count("a")
来源：http://dali.zhixingplan.top/Article/details/gtmpounfxu.html

PHP:  substr_count($s, "a");
来源：http://dali.yj20258888.top/Article/details/gteubiknbg.html

JS:   s.split("a").length - 1
来源：http://dali.havefunace.top/Article/details/gtpawfdbzi.html

TS:   s.split("a").length - 1
来源：http://dali.zycfv.cn/Article/details/gtrdlubrre.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhengqikj.top/Article/details/gttqzroyvk.html

Go:   strings.Count(s, "a")
来源：http://dali.kuanghao11.cn/Article/details/gtxaudrdex.html

Ruby: s.count("a")
来源：http://dali.yueranfly.top/Article/details/gtzdddpwui.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xziqi.cn/Article/details/gtnmpakypm.html

[E13] 逐字符遍历
来源：http://dali.xylfe.cn/Article/details/gtciyblhpl.html

Py:   for ch in s: print(ch)
来源：http://dali.yuanzhike.top/Article/details/gtnxquojfn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.wangshuangyany.cn/Article/details/gtwzrdknoo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuxming.cn/Article/details/gttrzxlifu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.9152youxi.cn/Article/details/gthcuzfcmq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtutdykibr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjayrevd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ivvv.top/Article/details/gtgfvqcbhw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xuanzx.com/Article/details/gtzplstedi.html

[E14] URL 编码与 Base64
来源：http://dali.yueranfly.top/Article/details/gtytsgatae.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yonumen.top/Article/details/gtftflbjcg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfjhotlk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yonumen.top/Article/details/gtgmvvkhyk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xziqi.cn/Article/details/gtezlwldyz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gthilotpcd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.havefunace.top/Article/details/gtazaqoesn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.aizwys.cn/Article/details/gtwownpxmv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gtrgspfbgi.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhoulong.xyz/Article/details/gtpbmlarwb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fzhhl.top/Article/details/gtoyljzdih.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhengqikj.top/Article/details/gtblgjjfwr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yangfankeji.com/Article/details/gtzvxtxlew.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtuippxnzm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shanyushiyangtech.top/Article/details/gtenvszgwy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jiagoushi.top/Article/details/gtrrssygqo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtqbqvkbtt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nwbrower.top/Article/details/gtwfwbxiyq.html

[E16] 数字千分位
来源：http://dali.birdmap.top/Article/details/gtdmirgllw.html

Py:   f"{1234567:,}"
来源：http://dali.wangshuangyany.cn/Article/details/gtcataqjup.html

PHP:  number_format(1234567);
来源：http://dali.jlsjyb.cn/Article/details/gtamhezpwo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.dianchejie.cn/Article/details/gthinvhbry.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxuanxn.top/Article/details/gtfhryoaor.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.wangdashe.top/Article/details/gtocsdyszv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yanxiufei.cn/Article/details/gtnqczlnxl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jianghu66.top/Article/details/gtiymoltya.html

C#:   1234567.ToString("N0")
来源：http://dali.xinyue.icu/Article/details/gtwqaaszjh.html

[E17] 首字母大写
来源：http://dali.zdqjudy.top/Article/details/gtffhrlanz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shangyingyoupin.top/Article/details/gtgqmfdldv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hysaishi.cn/Article/details/gtsdnrmdrm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gtrsphjdgb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gtiqmggfub.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.wangdashe.top/Article/details/gtsgkynkpo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yanxiufei.cn/Article/details/gtlmqicuxq.html

Ruby: s.capitalize
来源：http://dali.316326.xyz/Article/details/gthblsfyvf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.wangdashe.top/Article/details/gtwfkhlflc.html

[E18] 模板占位符替换
来源：http://dali.jiagoushi.top/Article/details/gtjjkdwpwy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhongyouzk.top/Article/details/gtucsgxgla.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gzhubu.top/Article/details/gtsysglknh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtjffmigyv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtqiclrgck.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtykcmqmvj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xylfe.cn/Article/details/gtmaiivuxt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guannengcc.top/Article/details/gttnyroval.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.vqdsnc.cn/Article/details/gtqzwvvrik.html

[E19] 多行文本按行拆分
来源：http://dali.zhongyouzk.top/Article/details/gthahxwjam.html

Py:   s.splitlines()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttfybshla.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtgeozniat.html

JS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gtmhmczqeg.html

TS:   s.split(/\r?\n/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnlvtyigz.html

Java: s.lines().toList()
来源：http://dali.jiagoushi.top/Article/details/gtdtvsjohe.html

Go:   strings.Split(s, "\n")
来源：http://dali.andypj.xyz/Article/details/gtozgtggde.html

Ruby: s.lines
来源：http://dali.bjfxy.top/Article/details/gtnbhwnsrx.html

C#:   s.Split('\n')
来源：http://dali.sufxvd.cn/Article/details/gtyzqtozjs.html

[E20] 判断字符串是否为空
来源：http://dali.havefunace.top/Article/details/gtovwhjehp.html

Py:   if not s:
来源：http://dali.zdqjudy.top/Article/details/gtutxywkax.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jqgfzy.top/Article/details/gtsdxsuobi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtugfhuysw.html

TS:   if (s === "") {}
来源：http://dali.zdqjudy.top/Article/details/gtshjasidx.html

Java: if (s.isEmpty()) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvxshqex.html

Go:   if s == "" {}
来源：http://dali.zycfv.cn/Article/details/gtwydxenvf.html

Ruby: if s.empty?
来源：http://dali.zhixingplan.top/Article/details/gtjvgggiyc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.c1oappe.top/Article/details/gtxalppwlt.html

[E21] 超长截断加省略号
来源：http://dali.gzhubu.top/Article/details/gtwyqmblsw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj20258888.top/Article/details/gtxcwxrupg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj20258.top/Article/details/gtwrrmoxor.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtolsasixe.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtxeewqazj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtbvidqqxu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.pengpengdd.cyou/Article/details/gtnwroelhr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtefaufulp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtxtnvewtz.html

[E22] 字节长度与字符长度
来源：http://dali.yanxiufei.cn/Article/details/gtkrigypls.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jqgufenzy.top/Article/details/gtktqdwdzd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtyshxpzqc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtuhpadykv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhengqikj.top/Article/details/gtigzqkxca.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cdnleiting.top/Article/details/gtypkxlhxr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.c1oappe.top/Article/details/gtzjkiknvh.html

Ruby: s.bytesize;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gtowcmcjfe.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.daria6918.cn/Article/details/gtrxtopwse.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtjttalgnh.html

F. 文件与目录
来源：http://dali.svipenyu.cn/Article/details/gtwjtfyobd.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtjqrulewg.html

[F01] 读取整个文件
来源：http://dali.chenzaomai.com/Article/details/gtgbqfcjhf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ivvv.top/Article/details/gtgnwvxvtm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtbzztdber.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuetiantiany.cn/Article/details/gtavklmqlr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gtxrpwxlxq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtpvbihbay.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqqujxez.html

Ruby: File.read("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtncmarpjs.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.birdmap.top/Article/details/gtwujlfjna.html

[F02] 逐行读取文件
来源：http://dali.hysaishi.cn/Article/details/gtlgmxhngv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxuanxn.top/Article/details/gthnrvfrcn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.bjfxy.top/Article/details/gtntcionmx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gttthaeyzu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gtzfthplkp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gtqosqsrxz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shuidangran.top/Article/details/gtnibabnxl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cashguo.top/Article/details/gtpuwvkoio.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.aizwys.cn/Article/details/gtrautmnqn.html

[F03] 写入文件（覆盖）
来源：http://dali.xuetiantiany.cn/Article/details/gthneyugdc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucjkdgds.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gtglahmefc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtcttxinpp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yongpay.top/Article/details/gtmqjscxuk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gtbgtgrdje.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvmappfo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cucudq.cn/Article/details/gtgtumtbld.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.mhx1999.top/Article/details/gtmgwpeqst.html

[F04] 追加写入文件
来源：http://dali.meibo888.top/Article/details/gtthyteggx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ybcxt.top/Article/details/gtegwbsvwa.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cheryme.top/Article/details/gtieoxpjri.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tianlin.xyz/Article/details/gtxxdnxioq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gtuzcsjxbv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxposqnj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.aibaodan.cn/Article/details/gtbzwgtgrv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hnxiangtu.top/Article/details/gtrsvworit.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gaohongyu789.top/Article/details/gtcydbpgbc.html

[F05] 判断文件或目录是否存在
来源：http://dali.ivvv.top/Article/details/gtywvkngsu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.kuanghao11.cn/Article/details/gtwazennjr.html

PHP:  file_exists("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtgvkmwoqq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtqkgyjbdr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtbqsqrxxf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gteddhnmhj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ydzc1.top/Article/details/gtjryfwklc.html

Ruby: File.exist?("a.txt")
来源：http://dali.daria6918.cn/Article/details/gttynqaqdu.html

C#:   File.Exists("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtsfdsviug.html

[F06] 删除文件
来源：http://dali.sufxvd.cn/Article/details/gtscsbhayo.html

Py:   os.remove("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtimukozge.html

PHP:  unlink("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtretcksje.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtasmiuxbm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtdgfgulqg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtjvryikqh.html

Go:   os.Remove("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtcgvswkej.html

Ruby: File.delete("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtccliossv.html

C#:   File.Delete("a.txt");
来源：http://dali.cheryme.top/Article/details/gtqjntghof.html

[F07] 创建目录（含多级）
来源：http://dali.c1oappe.top/Article/details/gtgnlvpgjl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.fzhhl.top/Article/details/gtnzfeqkse.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yangfankeji.com/Article/details/gtkllqkdto.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gthyyyuzoe.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dashuyun.cn/Article/details/gtnfzgyjjc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.daxiang520.top/Article/details/gtizkwmyvh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tianlin.xyz/Article/details/gtzqwgqkde.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.iojbl.cn/Article/details/gtyfvxiyxd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nwbrower.top/Article/details/gtjyajbgqe.html

[F08] 遍历目录
来源：http://dali.dianchejie.cn/Article/details/gtgwhkscvf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhengqikj.top/Article/details/gtntmoxzim.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zdqjudy.top/Article/details/gtudajwwoi.html

JS:   fs.readdirSync("dir")
来源：http://dali.xuanzx.com/Article/details/gtykoorhyu.html

TS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gtylugotui.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gthyifayvz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guowangkeji.top/Article/details/gtumwbfqrm.html

Ruby: Dir.children("dir")
来源：http://dali.ybcxt.top/Article/details/gthydwbibw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ivvv.top/Article/details/gtlosncydn.html

[F09] 获取文件大小
来源：http://dali.sufxvd.cn/Article/details/gtgrxjtgvm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtbzuhiqni.html

PHP:  filesize("a.txt");
来源：http://dali.yj20258.top/Article/details/gteykkstpf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gtgdonyexh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.pengpengdd.cyou/Article/details/gtbrcqgwzk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtqtswdtbv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.pengpengdd.cyou/Article/details/gtmztgjlkw.html

Ruby: File.size("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtlbevlbbh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sufxvd.cn/Article/details/gtakrywyzg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fengsongda.top/Article/details/gtkgbctgfu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtfhteaaov.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ydzc1.top/Article/details/gtxjexdkce.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtfajnvrqd.html

TS:   path.extname("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtuctoummq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hfpthk.cn/Article/details/gtdcrwcflc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtmohpqkdd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtjezxpzdh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtcbaykjgo.html

[F11] 复制与移动文件
来源：http://dali.chenzaomai.com/Article/details/gttpwgpqge.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtkmkxlyyc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.andypj.xyz/Article/details/gtotbbygcf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxrybmicz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtvdvyqjgq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnqzz.top/Article/details/gtjjosmcxs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nanxuanxn.top/Article/details/gtgxnrlaqk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtltebvuwt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yonumen.top/Article/details/gtrijtwpnx.html

[F12] CSV 读写
来源：http://dali.yj20258888.top/Article/details/gtsccivruk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinqigfzy.top/Article/details/gtsptleacl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuanzx.com/Article/details/gtsrhtrszi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cashguo.top/Article/details/gtjjhebdpg.html

TS:   // 同上
来源：http://dali.haohaochexian.top/Article/details/gtkmbykibq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jlsjyb.cn/Article/details/gtlxjzbali.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nanxuanxn.top/Article/details/gtkcrxydbd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzajasfd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cucudq.cn/Article/details/gtjyhrfbtx.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqzjbxcy.html

G. 面向对象
来源：http://dali.jyoumei.cn/Article/details/gtylinadli.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtcdzwjpdp.html

[G01] 定义类
来源：http://dali.xinyue.icu/Article/details/gtbffnywyj.html

Py:   class User: pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzbdvsjne.html

PHP:  class User {}
来源：http://dali.chenzaomai.com/Article/details/gtixgqfpos.html

JS:   class User {}
来源：http://dali.yj20258.top/Article/details/gtnvqeoomn.html

TS:   class User { name: string = ""; }
来源：http://dali.zhixingplan.top/Article/details/gtetqinhty.html

Java: class User {}
来源：http://dali.aibaodan.cn/Article/details/gtrhotbmqc.html

Go:   type User struct { Name string }
来源：http://dali.quarkkingdee.top/Article/details/gtullkphoo.html

Ruby: class User; end
来源：http://dali.nanxinkj.top/Article/details/gtcvtyfghh.html

C#:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gtozeqrcal.html


<!-- 参考信息 -->