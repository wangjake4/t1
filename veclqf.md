代发 wailian999

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cqqwz.cn/Article/details/gteecztdqd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shuidangran.top/Article/details/gtockqtyxp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cqqwz.cn/Article/details/gtxvntpdco.html

[D26] 数组转字符串
来源：http://dali.gzhubu.top/Article/details/gtrbuxfwhj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gogol.net.cn/Article/details/gtseweweri.html

PHP:  implode(", ", $arr);
来源：http://dali.zhoulong.xyz/Article/details/gtaexnvxic.html

JS:   arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gtjqqrurzw.html

TS:   arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gtyuvskelj.html

Java: String.join(", ", list)
来源：http://dali.gogol.net.cn/Article/details/gtmqivevnl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsiuksuwm.html

Ruby: arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gtfwzglfic.html

C#:   string.Join(", ", list)
来源：http://dali.nwbrower.top/Article/details/gtncgyeqec.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtosrdjwyg.html

E. 字符串处理
来源：http://dali.quarkkingdee.top/Article/details/gtbckqskfs.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtxjbkzrds.html

[E01] 拼接字符串
来源：http://dali.ivvv.top/Article/details/gtvwfvtkfd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tanke756.top/Article/details/gtslzjkfye.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jqgfzy.top/Article/details/gthfzbcztr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkpoezwho.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhixingplan.top/Article/details/gtkjynorua.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbmflkqoc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.9152youxi.cn/Article/details/gtrediiedr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shzxlz.cn/Article/details/gttiglzchi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sweek.top/Article/details/gtikrhgney.html

[E02] 重复字符串
来源：http://dali.pycfn.com/Article/details/gtsbpbaagc.html

Py:   "ab" * 3
来源：http://dali.0kj1m.cn/Article/details/gtloghqoeu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shzxlz.cn/Article/details/gtmnszwmos.html

JS:   "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gtwbmadnfp.html

TS:   "ab".repeat(3)
来源：http://dali.gogol.net.cn/Article/details/gtdtqezalq.html

Java: "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gtcezrrbvm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.0kj1m.cn/Article/details/gtxtlqcljq.html

Ruby: "ab" * 3
来源：http://dali.gzhubu.top/Article/details/gtvzucufoi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj20258888.top/Article/details/gtjlvluezf.html

[E03] 截取子串
来源：http://dali.jqgfzy.top/Article/details/gtjgeoabyr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xuanzx.com/Article/details/gtwrbsltai.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtvxcugizb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jianghu66.top/Article/details/gtchhbqpbd.html

TS:   s.slice(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gtkrvshfuw.html

Java: s.substring(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gtgqhskvdx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.c1oappe.top/Article/details/gtratayplx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hysaishi.cn/Article/details/gtgrznmitt.html

C#:   s.Substring(1, 3)
来源：http://dali.cqqwz.cn/Article/details/gtzwpijpfb.html

[E04] 查找子串位置
来源：http://dali.yj20258.top/Article/details/gtivotrxgb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shuidangran.top/Article/details/gtxmtupjgh.html

PHP:  strpos($s, "x");
来源：http://dali.dashuyun.cn/Article/details/gtgqfktpxs.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cucudq.cn/Article/details/gtsronsmgy.html

TS:   s.indexOf("x")
来源：http://dali.jqgfzy.top/Article/details/gtvjgcoqkx.html

Java: s.indexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gtcyuyjjoz.html

Go:   strings.Index(s, "x")
来源：http://dali.kuanghao11.cn/Article/details/gtuiipmtcs.html

Ruby: s.index("x")
来源：http://dali.chenlongwang.top/Article/details/gtqurcnyyn.html

C#:   s.IndexOf("x")
来源：http://dali.yonumen.top/Article/details/gtgdyxetfp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.bjfxy.top/Article/details/gtfsjhdzjt.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtauznhczm.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cheryme.top/Article/details/gtoxtkorxk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yanxiufei.cn/Article/details/gtugtfizfd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.fzhhl.top/Article/details/gthykyuddz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aibaodan.cn/Article/details/gtvjgolmqm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.wangdashe.top/Article/details/gtaroftzue.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jiagoushi.top/Article/details/gtffgyszzw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.nanxuanxn.top/Article/details/gtyoxlsour.html

[E06] 替换子串
来源：http://dali.nwbrower.top/Article/details/gtasyimvje.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jqgufenzy.top/Article/details/gtvcxokuau.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cdnleiting.top/Article/details/gttaeunibs.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtmkjeokyu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtnclflcjg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtyobhcmqc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hywenlv.cn/Article/details/gtdxqxlthe.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtyvewjpgw.html

C#:   s.Replace("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbzruevkg.html

[E07] 按分隔符拆分
来源：http://dali.snrcjt.cn/Article/details/gtlxkazebc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jiagoushi.top/Article/details/gtqrwzolxu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sysykeji.top/Article/details/gtwhhrmgvi.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhongyouzk.top/Article/details/gtaodoxjbo.html

TS:   s.split(",")
来源：http://dali.snrcjt.cn/Article/details/gtqhdxjyrw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yongpay.top/Article/details/gteibhcnuo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xylfe.cn/Article/details/gtdchmqsbv.html

Ruby: s.split(",");  s.split
来源：http://dali.hywenlv.cn/Article/details/gtgocyzmnv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.dianchejie.cn/Article/details/gtcexnpcce.html

[E08] 数组按分隔符合并
来源：http://dali.daria6918.cn/Article/details/gtlbdzwxiz.html

Py:   ",".join(items)
来源：http://dali.meibo888.top/Article/details/gteyngrkgc.html

PHP:  implode(",", $items);
来源：http://dali.jianghu66.top/Article/details/gtzjokasvx.html

JS:   items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gtmyeumfsz.html

TS:   items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gtjeusiomk.html

Java: String.join(",", items)
来源：http://dali.aizwys.cn/Article/details/gtmzclsbpc.html

Go:   strings.Join(items, ",")
来源：http://dali.hysaishi.cn/Article/details/gtekiaztct.html

Ruby: items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gtzzlwavqh.html

C#:   string.Join(",", items)
来源：http://dali.cashguo.top/Article/details/gtbzuieukd.html

[E09] 去除所有空白字符
来源：http://dali.xylfe.cn/Article/details/gtljqthbws.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.fengsongda.top/Article/details/gtxbarmnli.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.aizwys.cn/Article/details/gtwpxtdjrd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtszpspjbq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hysaishi.cn/Article/details/gtoyzugrrz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.aibaodan.cn/Article/details/gtzqrurzyk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yonumen.top/Article/details/gtqmxjpcyk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ivvv.top/Article/details/gtuawjwtwb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cheryme.top/Article/details/gtbxvvmmov.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigufen.top/Article/details/gtquxpxnkp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gtntejaxoz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xuetiantiany.cn/Article/details/gtmefbhgtl.html

JS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gtsjdkfrje.html

TS:   "7".padStart(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gtxbzidmtn.html

Java: String.format("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gtapmupgri.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gtbnppgfsq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gttcuqfkcu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jyoumei.cn/Article/details/gtardegihv.html

[E11] 反转字符串
来源：http://dali.zycfv.cn/Article/details/gtsfnscjru.html

Py:   s[::-1]
来源：http://dali.hnqzz.top/Article/details/gturfmwixn.html

PHP:  strrev($s);
来源：http://dali.bjfxy.top/Article/details/gtnuvcfeis.html

JS:   [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gtozcjldcv.html

TS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrygpsvyx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ybcxt.top/Article/details/gttqomoxhd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.birdmap.top/Article/details/gttwxkgqgs.html

Ruby: s.reverse
来源：http://dali.fengsongda.top/Article/details/gtvmgalloc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinqigufen.top/Article/details/gtutabrytx.html

[E12] 统计某字符出现次数
来源：http://dali.hnqzz.top/Article/details/gtnqrcxygn.html

Py:   s.count("a")
来源：http://dali.yj202588.top/Article/details/gtbkzrotwz.html

PHP:  substr_count($s, "a");
来源：http://dali.yvedp.cn/Article/details/gtvcnfrccb.html

JS:   s.split("a").length - 1
来源：http://dali.aibaodan.cn/Article/details/gtltnduyfr.html

TS:   s.split("a").length - 1
来源：http://dali.jiagoushi.top/Article/details/gtctdgdnbn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.wangdashe.top/Article/details/gtvglnadky.html

Go:   strings.Count(s, "a")
来源：http://dali.yj20258888.top/Article/details/gtcymonqpi.html

Ruby: s.count("a")
来源：http://dali.tanke756.top/Article/details/gtmmbkknmb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cashguo.top/Article/details/gtrkaherkw.html

[E13] 逐字符遍历
来源：http://dali.guannengcc.top/Article/details/gtsticijkl.html

Py:   for ch in s: print(ch)
来源：http://dali.wangdashe.top/Article/details/gtyzogomqj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.wangdashe.top/Article/details/gtsavxvzvl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zdqjudy.top/Article/details/gttoagqjjf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj202588.top/Article/details/gtsvfvhwdo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xziqi.cn/Article/details/gtrtalauwu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gogol.net.cn/Article/details/gtzmhjahdp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.fengsongda.top/Article/details/gtokcdwefl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.316326.xyz/Article/details/gtgaidijop.html

[E14] URL 编码与 Base64
来源：http://dali.yj20258888.top/Article/details/gtkcbsvytg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hongshengwenyu.top/Article/details/gtwugpscyo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtlddggbgc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sweek.top/Article/details/gtyfvtcuup.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.wangdashe.top/Article/details/gtohlbnhxx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj20258888.top/Article/details/gtovakfgih.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jqgufenzy.top/Article/details/gtfgwbgbfn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yangfankeji.com/Article/details/gtajpyudnv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cashguo.top/Article/details/gtxjdwpdnd.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinqigufen.top/Article/details/gtksgfmdvt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yuxming.cn/Article/details/gtftyoketu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hywenlv.cn/Article/details/gteogvtepy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.mhx1999.top/Article/details/gtaldjhweg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sufxvd.cn/Article/details/gtxvmctiij.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinqigfzy.top/Article/details/gtkcdssxjq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zdqjudy.top/Article/details/gtlhatfzfj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.guannengcc.top/Article/details/gtrfikjlyn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ppjwa.cn/Article/details/gtocfiacvx.html

[E16] 数字千分位
来源：http://dali.shanyushiyangtech.top/Article/details/gtwcszxmek.html

Py:   f"{1234567:,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtctymhemu.html

PHP:  number_format(1234567);
来源：http://dali.fzhhl.top/Article/details/gtnnfzmlil.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gtnbrbiobr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yangfankeji.com/Article/details/gtqloimhnr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.wangshuangyany.cn/Article/details/gtucfeulfz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ppjwa.cn/Article/details/gtqmecfebs.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.bjfxy.top/Article/details/gtghixxapi.html

C#:   1234567.ToString("N0")
来源：http://dali.dianchejie.cn/Article/details/gtchfvkwvg.html

[E17] 首字母大写
来源：http://dali.c1oappe.top/Article/details/gtsxturdre.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ybcxt.top/Article/details/gtvhhypybn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.feifeiyinyue.top/Article/details/gthsverkrp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtbeggkinh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.bjfxy.top/Article/details/gtfksntwjl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hongshengwenyu.top/Article/details/gthvrgyadh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jlsjyb.cn/Article/details/gtbnkmkvdo.html

Ruby: s.capitalize
来源：http://dali.tian-w.cn/Article/details/gtvnfcxosx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dianchejie.cn/Article/details/gtcqrwiakj.html

[E18] 模板占位符替换
来源：http://dali.daxiang520.top/Article/details/gtehkiaufu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.iojbl.cn/Article/details/gthyelrrmp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hongshengwenyu.top/Article/details/gtzvwmufxw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtlzddpoeq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gtnvqqmvza.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtjibzdfdc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtzdxescdd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.haohaochexian.top/Article/details/gtcarwhvlv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xinyue.icu/Article/details/gtwaqsfwjs.html

[E19] 多行文本按行拆分
来源：http://dali.smart0.xyz/Article/details/gtmzezrgca.html

Py:   s.splitlines()
来源：http://dali.tianlin.xyz/Article/details/gtntpizzsq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shuidangran.top/Article/details/gtmkzoxyjd.html

JS:   s.split(/\r?\n/)
来源：http://dali.pycfn.com/Article/details/gthgendrfv.html

TS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gtqrvrplkr.html

Java: s.lines().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtrppzletn.html

Go:   strings.Split(s, "\n")
来源：http://dali.ivvv.top/Article/details/gtvymorzbj.html

Ruby: s.lines
来源：http://dali.shanyushiyangtech.top/Article/details/gtoecpqxbb.html

C#:   s.Split('\n')
来源：http://dali.nanxinkj.top/Article/details/gtzidtnjme.html

[E20] 判断字符串是否为空
来源：http://dali.feifeiyinyue.top/Article/details/gtghrkifxu.html

Py:   if not s:
来源：http://dali.smart0.xyz/Article/details/gtnlsnbqgb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.c1oappe.top/Article/details/gtykgfhgha.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.quarkkingdee.top/Article/details/gthgfblhep.html

TS:   if (s === "") {}
来源：http://dali.yueranfly.top/Article/details/gteqzkcxtr.html

Java: if (s.isEmpty()) {}
来源：http://dali.yongpay.top/Article/details/gtufqsxpef.html

Go:   if s == "" {}
来源：http://dali.snrcjt.cn/Article/details/gtuxkctkyz.html

Ruby: if s.empty?
来源：http://dali.zycfv.cn/Article/details/gtefoyjzoe.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ehwqpu.com/Article/details/gtrhqlfjkw.html

[E21] 超长截断加省略号
来源：http://dali.tian-w.cn/Article/details/gtforghmnc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jlsjyb.cn/Article/details/gtcnfsvdui.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj20258.top/Article/details/gtsaxvvfvb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtqpndyrwo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtsfebwcmo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvoegrug.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.wangshuangyany.cn/Article/details/gtovnmvedd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqebcnml.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtctantqqy.html

[E22] 字节长度与字符长度
来源：http://dali.dianchejie.cn/Article/details/gtuiownmvx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtuejdiugy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtelxkhzrw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ybcxt.top/Article/details/gtuhsihdjx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sufxvd.cn/Article/details/gthdfzckzi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.svipenyu.cn/Article/details/gtgdgxakqf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hywenlv.cn/Article/details/gtfiuxvjjr.html

Ruby: s.bytesize;  s.length
来源：http://dali.cheryme.top/Article/details/gtludcnnnl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.316326.xyz/Article/details/gtwulcxbac.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtwqczwqku.html

F. 文件与目录
来源：http://dali.gotoacloud.top/Article/details/gtlecavshe.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtfxcnwhuk.html

[F01] 读取整个文件
来源：http://dali.wangdashe.top/Article/details/gtqzprxexf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cashguo.top/Article/details/gtxxcywjbk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtwdifadiu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.andypj.xyz/Article/details/gttglxdaio.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjpdmrnu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtbsamavct.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.aizwys.cn/Article/details/gtjviuatnp.html

Ruby: File.read("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtrhgtfgui.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbfqxwch.html

[F02] 逐行读取文件
来源：http://dali.ivvv.top/Article/details/gtafpmvski.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shuidangran.top/Article/details/gtkmbbtulo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuanzx.com/Article/details/gtqvltxajh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yongpay.top/Article/details/gtdezcyrzq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cqqwz.cn/Article/details/gtwfvmlkxv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shuidangran.top/Article/details/gtfblllget.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yangfankeji.com/Article/details/gtpswdsjrc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhiwuduotai.top/Article/details/gtvyuwjmai.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yangfankeji.com/Article/details/gtbgligpia.html

[F03] 写入文件（覆盖）
来源：http://dali.aizwys.cn/Article/details/gtiejpkvtv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shuidangran.top/Article/details/gtovycolmk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gtybmqgdwr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtbdiohjlz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gtltcetevv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tanke756.top/Article/details/gtplinvjox.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cheryme.top/Article/details/gtlxxzwblr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hfpthk.cn/Article/details/gtomjynwln.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gtevwfsgec.html

[F04] 追加写入文件
来源：http://dali.andypj.xyz/Article/details/gtanlaqsyo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtpowkuttj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gotoacloud.top/Article/details/gtecvazphj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gtuwqbwwqu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jyoumei.cn/Article/details/gtazqbirhm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gzhubu.top/Article/details/gtxjwsksjo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtomilakks.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shzxlz.cn/Article/details/gtkzwnitpl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.daxiang520.top/Article/details/gtcihedgcx.html

[F05] 判断文件或目录是否存在
来源：http://dali.cheryme.top/Article/details/gtuesgognn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jqgfzy.top/Article/details/gtosaakmiw.html

PHP:  file_exists("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtfplhzaro.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtayxdotpj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtegjbsyey.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtijghsxvh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jianghu66.top/Article/details/gtnrodvgbd.html

Ruby: File.exist?("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtpiwmzkro.html

C#:   File.Exists("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtzezokept.html

[F06] 删除文件
来源：http://dali.ydzc1.top/Article/details/gtoysdokij.html

Py:   os.remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtmvmrnaxk.html

PHP:  unlink("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdzzniyd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtudxmnqov.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdvlvyog.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtzsckseuz.html

Go:   os.Remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtypnrizyn.html

Ruby: File.delete("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtesncjoiy.html

C#:   File.Delete("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtqtkjcfhg.html

[F07] 创建目录（含多级）
来源：http://dali.nanxuanxn.top/Article/details/gtpbjlidix.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.havefunace.top/Article/details/gtvgpmeujv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ivvv.top/Article/details/gtquxtwcrz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.smart0.xyz/Article/details/gtbsmatgmo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxinkj.top/Article/details/gtrurteksk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgfzy.top/Article/details/gtxdmilbqq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffimdlxq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.meibo888.top/Article/details/gtarzurvhc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.9152youxi.cn/Article/details/gtfpjpwxip.html

[F08] 遍历目录
来源：http://dali.redwolf501.top/Article/details/gtafeblltd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenjidiqi.icu/Article/details/gtwtplmamx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhixingplan.top/Article/details/gtosuccfzh.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtipevurij.html

TS:   fs.readdirSync("dir")
来源：http://dali.yuxming.cn/Article/details/gtbreswgmt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yanxiufei.cn/Article/details/gtrytfufmx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yonumen.top/Article/details/gtzzkjmbpx.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258888.top/Article/details/gtdivnbiqk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj20258.top/Article/details/gtmpzjbfvb.html

[F09] 获取文件大小
来源：http://dali.yuanzhike.top/Article/details/gtgbdlzezz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdewwkegp.html

PHP:  filesize("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtvgzkmkfk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shuidangran.top/Article/details/gtftyfytvl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shuidangran.top/Article/details/gtchiqxorj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gtqezbtsnw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sufxvd.cn/Article/details/gtaxchiiio.html

Ruby: File.size("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtjrkoojhm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jqgfzy.top/Article/details/gtzyptktok.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.redwolf501.top/Article/details/gtlwblepwf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gteaybvfyq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yongpay.top/Article/details/gtzfiohjeb.html


<!-- 参考信息 -->