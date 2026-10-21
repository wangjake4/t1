代发 wailian999

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtqccqawdt.html

E. 字符串处理
来源：http://dali.ehwqpu.com/Article/details/gtgxypjchk.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtimclgnvf.html

[E01] 拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtzrxiptxy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cashguo.top/Article/details/gtsbdkmdep.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhixingplan.top/Article/details/gtolwygxmv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gtmjqjcbce.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dianchejie.cn/Article/details/gtefotrkyu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sxryk.cn/Article/details/gtihjthioo.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tanke756.top/Article/details/gtjazgffwg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zycfv.cn/Article/details/gtboumxldb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtdnpubrgb.html

[E02] 重复字符串
来源：http://dali.chenlongwang.top/Article/details/gtwfcwkbqc.html

Py:   "ab" * 3
来源：http://dali.mhx1999.top/Article/details/gtuchnjdcl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cheryme.top/Article/details/gtvhddkagq.html

JS:   "ab".repeat(3)
来源：http://dali.aizwys.cn/Article/details/gtoqannsen.html

TS:   "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gtcksuniwk.html

Java: "ab".repeat(3)
来源：http://dali.pycfn.com/Article/details/gtlbscoucw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.birdmap.top/Article/details/gtenzftnjr.html

Ruby: "ab" * 3
来源：http://dali.redwolf501.top/Article/details/gtjnjznsaz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ybcxt.top/Article/details/gtwqwzxpfu.html

[E03] 截取子串
来源：http://dali.xylfe.cn/Article/details/gtxcylibck.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yvedp.cn/Article/details/gtsbmxscpr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gtcqqnezhi.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtejfjdogn.html

TS:   s.slice(1, 4)
来源：http://dali.316326.xyz/Article/details/gtnunwjdbp.html

Java: s.substring(1, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbzhrucm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.0kj1m.cn/Article/details/gtuutkktan.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yongpay.top/Article/details/gtzlegfqwl.html

C#:   s.Substring(1, 3)
来源：http://dali.hammf.cn/Article/details/gtphvtjtax.html

[E04] 查找子串位置
来源：http://dali.zycfv.cn/Article/details/gtpwkewodr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tanke756.top/Article/details/gtgbeqgapa.html

PHP:  strpos($s, "x");
来源：http://dali.haohaochexian.top/Article/details/gtzhobcsxa.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xuanzx.com/Article/details/gtfwqwdnye.html

TS:   s.indexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gtqttxzjam.html

Java: s.indexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gtomsveejx.html

Go:   strings.Index(s, "x")
来源：http://dali.birdmap.top/Article/details/gtwatsflrv.html

Ruby: s.index("x")
来源：http://dali.meibo888.top/Article/details/gtwijaaiia.html

C#:   s.IndexOf("x")
来源：http://dali.havefunace.top/Article/details/gtqrdukqri.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.daria6918.cn/Article/details/gtmsphghyg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.daria6918.cn/Article/details/gtaxxilwuj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.meibo888.top/Article/details/gtssblgome.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gtzhazghlm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.pycfn.com/Article/details/gtlvrdrljm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gtqepspwmm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258888.top/Article/details/gtxpkdytyk.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cheryme.top/Article/details/gtudbuxivg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.nanxuanxn.top/Article/details/gtkzbegqfb.html

[E06] 替换子串
来源：http://dali.hongshengwenyu.top/Article/details/gtqicljmyj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gtavkcncsn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yanxiufei.cn/Article/details/gtpytqusmo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtlfqoffvo.html

TS:   s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gttglvrjmp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtzbfmrjlc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tianlin.xyz/Article/details/gtinsisghs.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtnrrrvnrr.html

C#:   s.Replace("a", "b")
来源：http://dali.tanke756.top/Article/details/gtfjoltenl.html

[E07] 按分隔符拆分
来源：http://dali.hysaishi.cn/Article/details/gtlwztknbh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.haohaochexian.top/Article/details/gttabbwtrb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtybnljdtd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ivvv.top/Article/details/gtfshkryin.html

TS:   s.split(",")
来源：http://dali.hnxiangtu.top/Article/details/gtxyeaavnl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.svipenyu.cn/Article/details/gtokxnejqy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yvedp.cn/Article/details/gtjjigiqfj.html

Ruby: s.split(",");  s.split
来源：http://dali.gaohongyu789.top/Article/details/gtnhakmlxh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.tianlin.xyz/Article/details/gtecaoikmf.html

[E08] 数组按分隔符合并
来源：http://dali.hammf.cn/Article/details/gtwnymwjej.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gtihtimygz.html

PHP:  implode(",", $items);
来源：http://dali.nanxuanxn.top/Article/details/gtvvsenrhf.html

JS:   items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gtqzwroiqg.html

TS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gttfayipbw.html

Java: String.join(",", items)
来源：http://dali.sufxvd.cn/Article/details/gtyewdtpkx.html

Go:   strings.Join(items, ",")
来源：http://dali.fzhhl.top/Article/details/gtwwdxucyi.html

Ruby: items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gtnkcbytwy.html

C#:   string.Join(",", items)
来源：http://dali.jianghu66.top/Article/details/gtpbreallu.html

[E09] 去除所有空白字符
来源：http://dali.jyoumei.cn/Article/details/gtnrrzwnvl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ppjwa.cn/Article/details/gtrqvzxwsi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtdxwcjfvk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xziqi.cn/Article/details/gtabrarcdg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hnqzz.top/Article/details/gtqybwjxko.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.smart0.xyz/Article/details/gteczpysii.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.daxiang520.top/Article/details/gtumvacmfi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sufxvd.cn/Article/details/gtytsmojxo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthdvwuksn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.quarkkingdee.top/Article/details/gtihgriyaz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cheryme.top/Article/details/gteqyplbtz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hfpthk.cn/Article/details/gtdtrsygjp.html

JS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gtjewatarc.html

TS:   "7".padStart(3, "0")
来源：http://dali.daria6918.cn/Article/details/gtlrcoeoto.html

Java: String.format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gtyoufmnvg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gtevgvjzwu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gtmisznlet.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.dianchejie.cn/Article/details/gtixzzkcqs.html

[E11] 反转字符串
来源：http://dali.meibo888.top/Article/details/gteraocqol.html

Py:   s[::-1]
来源：http://dali.havefunace.top/Article/details/gtrdlwudye.html

PHP:  strrev($s);
来源：http://dali.wangdashe.top/Article/details/gtjhhjqiiz.html

JS:   [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtpaycotyf.html

TS:   [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtxhxiqhhb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.guannengcc.top/Article/details/gtcyhcfzhf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.wangdashe.top/Article/details/gtjvsvczjw.html

Ruby: s.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuuwqxcsf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gthnunsclg.html

[E12] 统计某字符出现次数
来源：http://dali.zhoulong.xyz/Article/details/gtdvfjcogr.html

Py:   s.count("a")
来源：http://dali.vqdsnc.cn/Article/details/gtsiickeay.html

PHP:  substr_count($s, "a");
来源：http://dali.hnxiangtu.top/Article/details/gttamevbts.html

JS:   s.split("a").length - 1
来源：http://dali.cashguo.top/Article/details/gttjactbuu.html

TS:   s.split("a").length - 1
来源：http://dali.redwolf501.top/Article/details/gtixpdmxpx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xziqi.cn/Article/details/gtuygxkpdj.html

Go:   strings.Count(s, "a")
来源：http://dali.cucudq.cn/Article/details/gtbnogltei.html

Ruby: s.count("a")
来源：http://dali.sxryk.cn/Article/details/gtxaageakl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.0kj1m.cn/Article/details/gttthngzxv.html

[E13] 逐字符遍历
来源：http://dali.zycfv.cn/Article/details/gtghgqioid.html

Py:   for ch in s: print(ch)
来源：http://dali.nwbrower.top/Article/details/gtjjktbesk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.feifeiyinyue.top/Article/details/gtudonbmtq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cqqwz.cn/Article/details/gtvlhkxiso.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtknnsiase.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.pycfn.com/Article/details/gtbcgwikjl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.fengsongda.top/Article/details/gtmdaudkrr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhixingplan.top/Article/details/gtqezoztxr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangdashe.top/Article/details/gtodrvqaro.html

[E14] URL 编码与 Base64
来源：http://dali.fengsongda.top/Article/details/gtcgerexna.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenjidiqi.icu/Article/details/gtfhmdgeqv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.9152youxi.cn/Article/details/gtatgluvha.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.smart0.xyz/Article/details/gtzztkacet.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cdnleiting.top/Article/details/gtpvvoutqs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yuxming.cn/Article/details/gtsfvrnfsi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yvedp.cn/Article/details/gtoibcofbt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.haohaochexian.top/Article/details/gtagscwhnn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.fzhhl.top/Article/details/gtcxhapjpx.html

[E15] HTML 转义 / 反转义
来源：http://dali.havefunace.top/Article/details/gtmwqvrajk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gaohongyu789.top/Article/details/gtkeeccyvd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhoulong.xyz/Article/details/gtwsuppwsf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sweek.top/Article/details/gtrguziewg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.316326.xyz/Article/details/gtccxwpqqa.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yuxming.cn/Article/details/gtngymgbbz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.haohaochexian.top/Article/details/gtfqjfgtfp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jqgufenzy.top/Article/details/gttochmnmd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnxiangtu.top/Article/details/gtfsnxpzga.html

[E16] 数字千分位
来源：http://dali.shzxlz.cn/Article/details/gtuigjuoog.html

Py:   f"{1234567:,}"
来源：http://dali.gogol.net.cn/Article/details/gtwyrcfcjb.html

PHP:  number_format(1234567);
来源：http://dali.ivvv.top/Article/details/gtdloxvyis.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuanzhike.top/Article/details/gtlaqokezv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenlongwang.top/Article/details/gtpgiqacst.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fzhhl.top/Article/details/gtvltwfzdt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhiwuduotai.top/Article/details/gtwrabemwt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fzhhl.top/Article/details/gthjybewjt.html

C#:   1234567.ToString("N0")
来源：http://dali.hammf.cn/Article/details/gtxisrpmjg.html

[E17] 首字母大写
来源：http://dali.shuidangran.top/Article/details/gtgkafdzha.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jqgfzy.top/Article/details/gtpsuabrtn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jlsjyb.cn/Article/details/gtfwswclro.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gtghcekecy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuanzx.com/Article/details/gtoloswkjr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.316326.xyz/Article/details/gtesxtvpsn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinqigufen.top/Article/details/gtfnwkbugq.html

Ruby: s.capitalize
来源：http://dali.smart0.xyz/Article/details/gtlnitqmms.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sweek.top/Article/details/gtresfavst.html

[E18] 模板占位符替换
来源：http://dali.jinqigfzy.top/Article/details/gttnoszlux.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangshuangyany.cn/Article/details/gtnfsvykfx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenlongwang.top/Article/details/gtzqlsomqk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gtozwlnczr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtxsceliqx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.havefunace.top/Article/details/gtygvhukqb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtjgmdsuyk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.birdmap.top/Article/details/gtcopqoxeb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj202588.top/Article/details/gtsgjuzjvh.html

[E19] 多行文本按行拆分
来源：http://dali.cashguo.top/Article/details/gtcehoyztl.html

Py:   s.splitlines()
来源：http://dali.zhoulong.xyz/Article/details/gttviupman.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtqofcmqts.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtodxumdkv.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gtdmcjdgpd.html

Java: s.lines().toList()
来源：http://dali.ivvv.top/Article/details/gtmlintkwr.html

Go:   strings.Split(s, "\n")
来源：http://dali.gotoacloud.top/Article/details/gtkvnzpvqq.html

Ruby: s.lines
来源：http://dali.jinqigfzy.top/Article/details/gtygketvml.html

C#:   s.Split('\n')
来源：http://dali.zhiwuduotai.top/Article/details/gtoscjjcte.html

[E20] 判断字符串是否为空
来源：http://dali.yueranfly.top/Article/details/gtvprzbujd.html

Py:   if not s:
来源：http://dali.xuetiantiany.cn/Article/details/gtrhlbzbod.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ivvv.top/Article/details/gtcgnrvxuc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cqqwz.cn/Article/details/gtvmcctiwl.html

TS:   if (s === "") {}
来源：http://dali.316326.xyz/Article/details/gtsgluzwby.html

Java: if (s.isEmpty()) {}
来源：http://dali.sufxvd.cn/Article/details/gtjvlwixie.html

Go:   if s == "" {}
来源：http://dali.chenjidiqi.icu/Article/details/gtpeuduvtx.html

Ruby: if s.empty?
来源：http://dali.jqgfzy.top/Article/details/gtmzqzjfhe.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cashguo.top/Article/details/gtcuwixnqr.html

[E21] 超长截断加省略号
来源：http://dali.ehwqpu.com/Article/details/gtopgrnepl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yongpay.top/Article/details/gtcjlsjtqn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gtswscbvcl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtyegdqtod.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtxanqsyri.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gtvworjdbm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yueranfly.top/Article/details/gtyfzrbdsj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yonumen.top/Article/details/gttnmrhdos.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj202588.top/Article/details/gtgfzxuuda.html

[E22] 字节长度与字符长度
来源：http://dali.smart0.xyz/Article/details/gtpolzzcpg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sxryk.cn/Article/details/gtlrjcazjo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtpxidcgmu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sysykeji.top/Article/details/gtjgsqhblp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtenmgefrt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sysykeji.top/Article/details/gtiwwxbarj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yangfankeji.com/Article/details/gtzplfvudq.html

Ruby: s.bytesize;  s.length
来源：http://dali.hammf.cn/Article/details/gtqqdchcnb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ybcxt.top/Article/details/gtvummiuji.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtbosytmaq.html

F. 文件与目录
来源：http://dali.xuanzx.com/Article/details/gtbmcgfywy.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtueghzoiw.html

[F01] 读取整个文件
来源：http://dali.chenzaomai.com/Article/details/gtarwmxuzg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shuidangran.top/Article/details/gtecxmwdjo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtusjisxnd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ehwqpu.com/Article/details/gtzzaqpbcw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gthimuvbyb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtrndqeplz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.feifeiyinyue.top/Article/details/gtcspyvpys.html

Ruby: File.read("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtqwdkzoeu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtjamwndld.html

[F02] 逐行读取文件
来源：http://dali.cheryme.top/Article/details/gtsldqxioe.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.snrcjt.cn/Article/details/gtlekpxxec.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqltoyvcw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.snrcjt.cn/Article/details/gtqppxbfqw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gthlnvcyka.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gzhubu.top/Article/details/gtwlogsxrr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthdafdvqb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmqxcjuu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yanxiufei.cn/Article/details/gtyomzxwtq.html

[F03] 写入文件（覆盖）
来源：http://dali.jianghu66.top/Article/details/gtizzwnkix.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nwbrower.top/Article/details/gtulnrrvyx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.316326.xyz/Article/details/gtpksuszvh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxzimirv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gtygohszcj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hammf.cn/Article/details/gtximlbshl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gzhubu.top/Article/details/gttadjfvxl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.mhx1999.top/Article/details/gtdzzxwgbm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gtirnjsmzh.html

[F04] 追加写入文件
来源：http://dali.hysaishi.cn/Article/details/gtiseutfam.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xylfe.cn/Article/details/gtkptnrwtc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jiagoushi.top/Article/details/gtdgptpnos.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hfpthk.cn/Article/details/gtmraipqtn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hfpthk.cn/Article/details/gtgsuwlhff.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zycfv.cn/Article/details/gtwcblnqpt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.mhx1999.top/Article/details/gtlxgyojsq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.0kj1m.cn/Article/details/gtputtiabw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnqzz.top/Article/details/gtifmwuvdq.html

[F05] 判断文件或目录是否存在
来源：http://dali.ivvv.top/Article/details/gtblnfwftt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.meibo888.top/Article/details/gtrdiysems.html

PHP:  file_exists("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtlppxytob.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtrluuoeup.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtpwncphqn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtnregrsqs.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj20258888.top/Article/details/gtqykdjugl.html

Ruby: File.exist?("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtqorsmxmi.html

C#:   File.Exists("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtbquzffyf.html

[F06] 删除文件
来源：http://dali.vqdsnc.cn/Article/details/gtbmgxuuda.html

Py:   os.remove("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtfeoodpwb.html

PHP:  unlink("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtavhoyjmj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtclivxvly.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtkdzluyty.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtiazfnyqk.html

Go:   os.Remove("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtqwibyxms.html

Ruby: File.delete("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtborthsod.html

C#:   File.Delete("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtrklqpswc.html

[F07] 创建目录（含多级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdmxzsexn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yuxming.cn/Article/details/gtdtumzgzd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinqigufen.top/Article/details/gthwknbcbe.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gtawrcgiul.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.haohaochexian.top/Article/details/gtdbcxcxtu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hysaishi.cn/Article/details/gtabpfqmvh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shangyingyoupin.top/Article/details/gtgvnvgndw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xuanzx.com/Article/details/gtjppfccfx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nanxuanxn.top/Article/details/gtomxslhfu.html

[F08] 遍历目录
来源：http://dali.shzxlz.cn/Article/details/gtjomdgyyk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zycfv.cn/Article/details/gtlcmyqhvf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.c1oappe.top/Article/details/gtmnwwhfea.html

JS:   fs.readdirSync("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtcflfgivz.html

TS:   fs.readdirSync("dir")
来源：http://dali.yangfankeji.com/Article/details/gtapndpghg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aibaodan.cn/Article/details/gtpiiddcid.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtnmmvmvri.html

Ruby: Dir.children("dir")
来源：http://dali.yuanzhike.top/Article/details/gtctwyvbgc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hysaishi.cn/Article/details/gtamdrszxr.html

[F09] 获取文件大小
来源：http://dali.quarkkingdee.top/Article/details/gtyrtyiawd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtqupflkha.html

PHP:  filesize("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtrdgqtljj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gtbdmdlvpo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.mhx1999.top/Article/details/gthdseoiyy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gttkoorwzp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sweek.top/Article/details/gtsigssxri.html

Ruby: File.size("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtytcvlgip.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cdnleiting.top/Article/details/gtzsihjidr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jiagoushi.top/Article/details/gtzjxsfigg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtjcrjgqcp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.daxiang520.top/Article/details/gtszbejuio.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtiwrvdaaj.html

TS:   path.extname("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtfzkfpiql.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yangfankeji.com/Article/details/gtgsekaped.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtgtammyex.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtyncrohir.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtrjcbfyug.html

[F11] 复制与移动文件
来源：http://dali.sweek.top/Article/details/gtzergvwzk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtsblthmoj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xylfe.cn/Article/details/gthjdbdchh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtyoasvzde.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtpcwmlcah.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.haohaochexian.top/Article/details/gtolmirubq.html


<!-- 参考信息 -->